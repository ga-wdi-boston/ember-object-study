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
person.firstName
```

## Assigning properties to Ember Objects

If you wanted to add a property of `height` to our `person` Ember Object how would you access that property?

```md
person.height
```

## Ember.Object.extend

In your own words, what does `Ember.Object.extend({})` do?

```md
Extend defines a new JS Class which inherits from the class that I am extending but does not create an instance of that class as create() does.
```

## Computed properties

What is an advantage to using computed properties?

```md
Computed properties let me declare functions as properties. And then I can use it
as static property. It's handy for taking one or more normal properties and transforming
their data to create a new value.
```
