Ember Best Practices
====================

## Tooling

### Ember CLI

Ember CLI will allow one to easily implement best practices that are baked into the CLI tool:

* "Pod" Based Folder Structure
* ES6 transpilation
* Unit Testing

## Routes

### Don't pollute your user's browser history.

* When possible utilize beforeModel to evaluate if it is the correct route.
* Utilize replace() to opt out of a certain route before transitioning to it.

## Resources

* [Ember Best Practices for Large Scale projects](http://discuss.emberjs.com/t/ember-design-best-practices-for-large-scale-projects/6006/7)
* [Nathan Hammond - Controlling Route Traversal with Flows by ](https://www.youtube.com/watch?v=iFBOYMxDl40&list=PLE7tQUdRKcyaOyfBnAndJxQ9PNVmKva0d&index=3)
