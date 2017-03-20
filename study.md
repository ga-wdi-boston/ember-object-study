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
`person.get('firstName');`
```

## Assigning properties to Ember Objects

If you wanted to add a property of `height` to our `person` Ember Object how would you access that property?

```md
`person.reopen({ height: something })` or if person is a class, `person.reopenClass({ height: something })`
```

## Ember.Object.extend

In your own words, what does `Ember.Object.extend({})` do?

```md
This method is the method which defines a new class which inherits from the standard Ember Object.
```

## Computed properties

What is an advantage to using computed properties?

```md
An advantage to using computed properties is that they update based on changes to the properties they are calculating from. Thus if an object has many values that depend on a specific one, making them cpmuted allows them to stay current with changes made to the main property.
```
