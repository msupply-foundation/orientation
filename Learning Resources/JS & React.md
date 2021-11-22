# JS and ReactJS resources 
This is intended to be consumed from top to bottom, starting with JavaScript (often abbreviated to just 'JS') and followed up with ReactJS.

Assumed knowledge: That you have experience programming and have core principles fairly ingrained.

## JavaScript
### Tutorials

* [Introduction to JavaScript](https://www.codecademy.com/learn/introduction-to-javascript). Provides a good coverage of the JS language, including new features.
* [Learn ES6](https://egghead.io/courses/learn-es6-ecmascript-2015). A good review of new JS features.

### Reference

* [Mozilla Development Network](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference). The ultimate source for JS language specifications.

## ReactJS
* [A good, short blog post on what ReactJS is and why it is great.](https://www.syncano.io/blog/reactjs-reasons-why-part-1/)
* [The Official React Documention Quick Start](https://facebook.github.io/react/docs/installation.html) is an excellent starting point that covers all the react principles, from installing react and starting a project, how react components work to how design react code structures.)
* [This Egghead course](https://egghead.io/lessons/react-hello-world-first-component) gives an excellent walkthrough that is concise and informative.)

### FlexBox
[Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) is a CSS tool for defining dynamic sizing and arrangement in interfaces that respond well to screen/window size changes.

[React Native flexbox](https://facebook.github.io/react-native/docs/flexbox) implementation is very similar but has some syntactic and API differences.

[flexboxin5](https://cvan.io/flexboxin5/) provides a nice interactive guide for figuring out the flexbox parameters that you may want.

### Redux

[Redux](https://redux.js.org/) is a state management tool which helps implement the [flux](http://facebook.github.io/flux/) architectural pattern. It was designed by facebook for react, but is not strictly a react only tool.

It is a more advanced topic that has a bit of a learning curve, but once understood it makes the state of an application and the manipulation of that state far simpler and consistent. The [redux docs](https://redux.js.org/introduction/getting-started) are a great place to start, once you are more familiar with JS, react & react-native.

### Finding Components and tools

[Node Package Manager (NPM)](https://www.npmjs.com/) is a great start and the main source of JS dependancies online. 
[JS.Coach](https://js.coach/react) is a good opinionated place to explore NPM packages, with better potential for finding powerful gems (that you may have missed directly in NPM or Google).

### Coding Style
We aim to use the latest Javascript language features in many of our repositories. They are ever evolving, so keep learning and make the case to support new features if it makes our code easier.

This repository has [eslint](https://eslint.org/) rules configured that should help detect mistakes be it invalid code, or breaking style rules.

In terms of formatting, we use [prettier](https://prettier.io/) to automatically format code in a consistent way. Code how you want, then let prettier make it consistent with the codebase for you.
