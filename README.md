# 1000 Resources to Read

- [JSConf](#jsconf)
- [React](#react)
 - [Components](#components)
 - [Redux](#redux)
- [Testing](#testing)
 - [Jest](#jest)
 - [Jasmine](#jasmine)

## JSConf

#### [Video - 31:31] Hacking Games and Why You Should Do It

https://www.youtube.com/watch?v=pSMljRkpP64

> **TL;DR**: Hacking games allows you to perfect your analytical code skills while having fun. It also exposes to other developers' code, which may help you improve your own.

## React

### Components

#### Presentational and Container Components

https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.gycwunsod

> **TL;DR** There is advantages to splitting components into separate components with specific purposes; container and presentational components. In general terms, presentational components should be solely responsible for the rendering of its data, while container components' purpose is more focused on the transformation of the data and the dispatching of this data through other components. Although there is no specific technical rule for how to split components, components can more easily be split based on their roles and areas of concern.

### Redux

#### [Video - 37:13] Netflix JavaScript Talks - RxJS + Redux + React = Amazing!
*Jay Phelps (@_jayphelps ) talks about why Netflix loves reactive programming with Rx. In this talk he shares the basics of RxJS 5 Observables and how they can be used with React and Redux to manage asynchronous effects using redux-observable.*

https://www.youtube.com/watch?v=AslncyG8whg

> **TL;DR** [Redux-Observable](https://github.com/redux-observable/redux-observable) offers means of tracking, managing and cancelling your asynchronous executions. This offers a middleware between your action creators and reducers in your Redux world.

## Testing

### Jest

#### Testing your app with Jest
*Learn how to test your React/Redux app thoroughly, including actions, reducers and components!*

http://academy.plot.ly/react/6-testing/

> **TL;DR** See every aspects of React & Redux (components, action creators, reducers) as pure functions; each can be tested by varying the combination of parameters pushed through them and you should expect to receive a consistent result every time a test is run with the same parameter combination.

#### [Video - 3:42] Use Jest's Snapshot Testing Feature

*Often when testing, you use the actual result to create your assertion and have to manually update it as you make changes to the feature. With Jest snapshot testing, you can let Jest do this part for you and write more tests and features faster and with more confidence. Let's learn about how you can use Jest snapshot testing to improve your own workflow.*

https://egghead.io/lessons/javascript-use-jest-s-snapshot-testing-feature

> **TL;DR** Snapshots allow you not only to track changes to the rendering of your components, but to any data structure. Snap files are a nice file to have in your pull requests in order to be more precise with your code review.

#### Jest 14.0: React Tree Snapshot Testing

http://facebook.github.io/jest/blog/2016/07/27/jest-14.html

> **TL;DR** 2017 will be a big year for Jest, especially when it comes to snapshot testing. Fundamentally, snapshot testing allows developers to validate the spread of their changes, in order to minimize unwanted or unexpected changes to other components.

#### Jest: Tutorial - React

http://facebook.github.io/jest/docs/tutorial-react.html

> **TL;DR** This tutorial offers two great examples. Firstly, using snapshots allows you to test the manipulation of a compnent's rendering through state changes by taking snapshots at various intervals. It's important to note that you want to reduce the scope of your snapshots to only the relevant code, in order to reduce the frequency at which snapshots expire through normal development. In this case, [Enzyme](https://github.com/airbnb/enzyme) is a great tool to scope your rendered component down to exactly what you want to take a snapshot (ie, a label and not its containers). However, if you're testing a computed value, such as a label title, you can simply evaluate its value through Enzyme's methods.

### Jasmine

#### Writing Beautiful Specs with Jasmine Custom Matchers

*Custom matchers are one of Jasmine’s most powerful, and yet underutilized, features.*

https://content.pivotal.io/blog/writing-beautiful-specs-with-jasmine-custom-matchers

> **TL;DR** Jasmine custom matchers' benefits are twofold: it allows you to be more precise with your assertions and test functions by pushing repetitive logic into the test itself (keeping code DRY), while allowing you to generate more relevant error messages to the assertion that is being tested. Two great Jasmine matcher libraries are [Jasmine Matchers](https://github.com/JamieMason/Jasmine-Matchers) and [Jasmine jQuery](https://github.com/velesin/jasmine-jquery).
