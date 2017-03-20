# Ember Object Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

-   [The Object Model](https://guides.emberjs.com/v2.11.0/object-model/) (The sections marked as (optional) are just that)
    - Objects in Ember
    - Classes and Instances (optional)
    - Reopening Classes and Instances (optional)
    - Computed Properties
    - Computed Properties and Aggregate Data
    - Observers
    - Bindings
    - Enumerables (optional)

## EXAMPLE: Accessing Ember Objects

If `person` is an Ember Object with `firstName` defined as a property, how would you access that property?

```md
person.get('firstName');
```
https://guides.emberjs.com/v2.11.0/object-model/classes-and-instances/#toc_accessing-object-properties

## Assigning properties to Ember Objects

If you wanted to add a property of `height` to our `person` Ember Object how would you access that property?

```md
person.set('height', '72');

// or to add it as a base property of the `Person` class.
Persion.reopenClass({
  height: <someValue>,
})
```
https://guides.emberjs.com/v2.11.0/object-model/reopening-classes-and-instances/
https://guides.emberjs.com/v2.11.0/object-model/reopening-classes-and-instances/

## Ember.Object.extend

In your own words, what does `Ember.Object.extend({})` do?

```md
`Ember.Object.extend({})` creates a new type of object that is a subclass of an Ember Object. Ember Objects support the obeservation of property values so that these they can use Ember's binding system. They also feature a class system and have some helpful built in methods like `get()` and `set()`.
```
https://guides.emberjs.com/v2.11.0/object-model/

## Computed properties

What is an advantage to using computed properties?

```md
A computed property can simplify the creation of new attributes. This can be especially useful in transforming/manipulating static value properties into other useful properties. One nice thing about computed properties is that when their underlying data changes, the computed property will change with it. Additionally, they can be used to bind properties to the values of other objects.
```
https://guides.emberjs.com/v2.11.0/object-model/computed-properties/
https://guides.emberjs.com/v2.11.0/object-model/bindings/
