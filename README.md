# [Redux Multipurpose Toolkit](https://github.com/KitCarson88/redux-multipurpose-toolkit)
The repository is an Angular 2+ project that contains libraries of a suite of redux facilities called @redux-multipurpose.
Based on @reduxjs/toolkit, the purpose of this suite is to ease the developer during redux integration, including some of most popular redux packages commonly used.

## @Redux-multipurpose
The suite is composed from:
- [@redux-multipurpose/core](https://kitcarson88.github.io/redux-multipurpose-toolkit/CORE): in addition to common redux store functionalities such as operations of actions dispatching and state selection (both synchronously and asynchronously), it let the developer to easily initialize redux subpackages (such as redux-logger, redux-saga, redux-observable, etc.). It offers also some combinators to ease data selection operations and actions dispatching tipically used in @angular-redux/store (@angular-redux/store is not integrated in this package).
- [@redux-multipurpose/angular-router](https://kitcarson88.github.io/redux-multipurpose-toolkit/ROUTER): the core package offers the possibility to integrate a navigation routing track providing a custom reducer during initialization. @redux-multipurpose/angular-router is an implementation that can be used in an Angular 2+ application.
- [@redux-multipurpose/angular-cli](https://kitcarson88.github.io/redux-multipurpose-angular-cli/): Redux Multipurpose command line tool to integrate redux-multipurpose in an Angular 2+ application. In addition to store creation functionalities, it let the developer to automate the integration of base files and lines of code to add new substates, epics, sagas and others redux stuff

## Usage
To integrate the store with the @redux-multipurpose tools, please refer to the [redux-multipurpose-template](https://github.com/KitCarson88/redux-multipurpose-template) example repository.
