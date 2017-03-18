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
<!-- In order to access the first name property you would use person.get('firstName'); and in order to set a new firstName you use person.set("firstName", "whatever the new name was"); -->
```

## Assigning properties to Ember Objects

If you wanted to add a property of `height` to our `person` Ember Object how would you access that property?

```md
<!-- In order to add a new property to a exsisting object you would use the reopen() method. Person.reopen({
  height: "whatever you want to set"
}) -->
```

## Ember.Object.extend

In your own words, what does `Ember.Object.extend({})` do?

```md
<!-- This allows you to create a new class. It will define a class with whatever you put in the params as a property or method.  -->
```

## Computed properties

What is an advantage to using computed properties?

```md
<!-- These allow you to effect properties without haveing to write new variables, to display the adjustment that the varaiables and the value of the variables.   -->
```
