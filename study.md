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
<!-- person.get("firstName"); -->
```

## Assigning properties to Ember Objects

If you wanted to add a property of `height` to our `person` Ember Object how would you access that property?

```md
<!-- person.incrementProperty('height');
}); -->
```

## Ember.Object.extend

In your own words, what does `Ember.Object.extend({})` do?

```md
<!-- It is a clone new named class of a parent object and the clone inherits all properties from the parent object. Properties in the clone can be modified and new properties can be added as well.  -->
```

## Computed properties

What is an advantage to using computed properties?

```md
<!-- A function used as a property to concatenate other properties as well as to be used as a setter of new values. -->
```
