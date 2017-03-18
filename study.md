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

## Assigning properties to Ember Objects

If you wanted to add a property of `height` to our `person` Ember Object how would you access that property?

```md
person.get('height');
```

## Ember.Object.extend

In your own words, what does `Ember.Object.extend({})` do?

```md
It creates a subclass of an Ember object, which is different from a normal
javascript object because it allows state tracking.  This is necessary for an
ember app to function properly.
```

## Computed properties

What is an advantage to using computed properties?

```md
It allows code to stay much DRY'er if one property of an object relies on data
that is in another object.  Instead of forcing the user to input that data
multiple times, a computed property can take the simplest input and transform it
into whatever the program needs.
```
