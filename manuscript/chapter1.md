# Chapter 1

## TypeScript

The first thing you may discover when you start reading the documentation for
Angular 2 is that you have to make a choice: you can choose to develop in one of
three languages! The choices are TypeScript, Dart, and finally JavaScript. This
book will not cover Dart, but it will cover TypeScript (hereafter "TS") because
Angular 2 is in fact built using TS and the documentation and tooling for TS
Angular 2 development has outpaced the other two options.

TS is a superset of ES2015 (formerly called ES6). Thus, any existing valid code
written in ES2015 is already valid TS. Conventionally, TS files use the
extension ".ts".

The following sections will provide the background in TS for you to be
able to read and understand as well as write code using TS and Angular 2.

### module loading

You will frequently need to incorporate external modules into your code. A2
uses System.js as its module loader, so A2 apps can use ES2015 module syntax even
if some dependencies use other syntaxes.

Here is an example from the Angular 2 5 Min Quickstart:

```javascript
import {bootstrap, Component} from 'angular2/angular2';
```

The `import` keyword is part of the ES2015 syntax, and indicates that the current
module (file) depends on what comes next in the curly brackets. In the above
example, `bootstrap` and `Component` are named exports we expect to be provided
by the module `angular2/angular2`.

### decorators

A decorator is a language feature added to ES2015 by TypeScript

### classes

Classes were added to the ES2015 specification as syntactic sugar over
prototypal inheritance. They do not work the same way as classes in many other
popular object oriented languages.
