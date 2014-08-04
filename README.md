Ember Best Practices
====================

## Actions

* When naming actions use verbs to indicate an action
* Use actions to traverse between routes

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
