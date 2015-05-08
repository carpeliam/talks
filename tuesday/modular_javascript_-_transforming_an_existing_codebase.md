# Modular JavaScript - Transforming an Existing Codebase

How can we create a consistent, updatable user-experience across all devices?

UI <=> Platform

### WebKit-based HTML5 UI
* performance on devices made innovation difficult
* do we really need the entire DOM (and all that baggage)?
* removed JS interpreter from platform


### Anti-Patterns
* singletons with state
* no unit tests
* some failures of JS itself (lack of encapsulation, lack of true modules)

### Modular Programming
* less team ownership
* programming by contract

### How did they get there?
* They slowly, gradually changed things over time
* moved from CMake to Grunt - built exactly the same artifact
* used Browserify for Common JS
* Jasmine for Unit Tests

### Take-Aways
* get your infrastructure in place
* start small by exporting API of one or two modules
* implement new features as modules