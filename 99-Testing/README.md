# Testing

Testing is import in large scale apps. In small apps
you may find that you write more test code than non
test code. 

## Testing with Jest

Jest is a test library made for React. 

Set up Jest by following the guide here: 

http://www.softwareishard.com/blog/testing/modern-react-component-testing-with-create-react-app-jest-and-enzyme/

**tl;dr**

- Install some tools
  - `npm install --save enzyme react-addons-test-utils`
  - `yarn install` 
- Run tests
  - `npm test`
  
## Why test?

Imagine having a system that lets' you know when things break
and where they break without having to run the application
and run it through all possible uses. 

### Types of tests

**Unit Tests**

Unit tests test individual software units. These are 
things like functions. You can call a function 
provide input and compare the output against an 
expected result. 

**Integration Tests** 

These are tests that test the integration of software
modules. These are tests that look at groups of 
software modules are test together. 

### How to Test

A testing framework is used to run tests and display 
the results. Mocha, Jasmine, Jest are all testing 
frameworks. 

React is a special case due to it's use of JSX and 
ES6. Jest and Enzyme are frameworks made for testing
with React. 

### What is a test?

A is usally made up of a test case that contains one 
or more assertions. 

The test case is something like: Testing a method
like an action creator. 

An assertion is one specific thing you might test. 
For example you might assert that an action creator 
returns an object. A test case for an action 
creatir might have the following assertions: 

- expect the method to return an object
- expect the object to have a type 
- expect the object to have a payload with a named property


Redux Mock Store

- https://codeburst.io/deliberate-practice-what-i-learned-from-reading-redux-mock-store-8d2d79a4b24d

