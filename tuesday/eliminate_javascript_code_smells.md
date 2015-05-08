# Eliminate JavaScript Code Smells

## Copy and Paste
Tools:

* JsInspect
* JSCPD - works with other languages (maybe CoffeeScript? also, Ruby and CSS/SCSS/markup)

## Switch Statements
violates the open/closed principle (one of Uncle Bob's SOLID principles)

Instead: strategy design pattern

## Magic Strings
identifying anything by a string is pretty meh - typos are easy

Addy Osmani has free JS Code Smell book

## "This Abyss"
reassigning "this" to an object .. ES6, CoffeeScript solve this, otherwise you need to bind

## Concatenation in JS
looks ugly. simple JS function can do lite stuff, but ES6 and CoffeeScript solve this

## Inappropriate Intimacy
Tightly coupled dependencies.

Solutions:

* Dependency Injection (pass into constructor)
* Message broker

http://bit.ly/js-smells