# React Redux

This class will review Redux with a close look at react-redux. 

## Actions 

Actions are best kept in their own file. 

Action types are strings. These should be defined as constants 
that are exported from the same file as the action creator that use
them. 

## Dispatcher/Reducers

Reducers should be organized by the pieces of state they manage. 

Organizing reducers into a a single file for each reducer is a good
idea. 

## Store 

The store is a single JavaScript object. State is stored as key 
values where each reducer is responsible for the piece of state 
under that key. 

Paying attention to naming here is a good idea. 

## Redux

Redux is a JavaScript implementaion of Flux. 

JavaScript Application State: https://stateofjs.com/2016/statemanagement/
Redux: https://medium.com/@modernserf/whats-so-great-about-redux-ac16f1cc0f8b

Learn about Redux from the author: https://egghead.io/courses/getting-started-with-redux

