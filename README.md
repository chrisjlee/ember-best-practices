Ember Best Practices
====================

# Ember Philosophies, the "Ember Way"

## Data down, Ember Up

Data should always migrate down from it's parent and into it's child component / resource / etc. The data shouldn't be manipulated. Once the data is migrated down, use an action to bubble it back up.


## Actions

* When naming actions use verbs to indicate an action

## Routes

### Don't pollute your user's browser history.

* When possible utilize beforeModel to evaluate if it is the correct route.
* Utilize replaceWith() to opt out of a certain route before transitioning to it.

## Tooling

### Ember CLI

Ember CLI will allow one to easily implement best practices that are baked into the CLI tool:

* "Pod" Based Folder Structure
* ES6 transpilation
* Unit Testing

<hr />

## Resources

* [Ember Best Practices for Large Scale projects](http://discuss.emberjs.com/t/ember-design-best-practices-for-large-scale-projects/6006/7)
* [Nathan Hammond - Controlling Route Traversal with Flows by ](https://www.youtube.com/watch?v=iFBOYMxDl40&list=PLE7tQUdRKcyaOyfBnAndJxQ9PNVmKva0d&index=3)
