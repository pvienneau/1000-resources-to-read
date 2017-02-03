# 1000 Resources to Read

- [JSConf](#jsconf)
- [React](#react)
 - [Components](#components)
 - [Redux](#redux)
- [Testing](#testing)
 - [Jest](#jest)
 - [Jasmine](#jasmine)
 - [Snapshot Testing](#snapshot-testing)

## JSConf

#### [Video - 31:31] Hacking Games and Why You Should Do It

https://www.youtube.com/watch?v=pSMljRkpP64

> **TL;DR**: Hacking games allows you to perfect your analytical code skills while having fun. It also exposes to other developers' code, which may help you improve your own.

## React

#### How I built a product in 5 weeks using Meteor and React

*Or how Ruutly came to life*

https://blog.416serg.me/how-i-built-a-product-in-5-weeks-using-meteor-and-react-ca2cfad35dcc#.jb37d55b3

> **TL;DR** Meteor works very well with React when developing native apps. 

### Components

#### Presentational and Container Components

https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.gycwunsod

> **TL;DR** There is advantages to splitting components into separate components with specific purposes; container and presentational components. In general terms, presentational components should be solely responsible for the rendering of its data, while container components' purpose is more focused on the transformation of the data and the dispatching of this data through other components. Although there is no specific technical rule for how to split components, components can more easily be split based on their roles and areas of concern.

### Redux

#### [Video - 37:13] Netflix JavaScript Talks - RxJS + Redux + React = Amazing!
*Jay Phelps (@_jayphelps ) talks about why Netflix loves reactive programming with Rx. In this talk he shares the basics of RxJS 5 Observables and how they can be used with React and Redux to manage asynchronous effects using redux-observable.*

https://www.youtube.com/watch?v=AslncyG8whg

> **TL;DR** [Redux-Observable](https://github.com/redux-observable/redux-observable) offers means of tracking, managing and cancelling your asynchronous executions. This offers a middleware between your action creators and reducers in your Redux world.

#### You Might Not Need Redux

*People often choose Redux before they need it. “What if our app doesn’t scale without it?” Later, developers frown at the indirection Redux introduced to their code. “Why do I have to touch three files to get a simple feature working?” Why indeed!*

https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367#.x7p4tms7k

> **TL;DR**: Redux, offering its benefits, has its own trade-off with its own constraints it sets on the data. It would be safe decision to not always jump the gun on committing to a Redux implementation, as it comes with certain strong conventions on how data should be managed. Although the questions asked here isn't necessarily "Is Redux the best tool", what it's trying to ask is "Is it too soon in the development lifecycle of the application to be commiting to Redux".

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

### Snapshot

#### Snapshot Testing in React Storybook

*Snapshot testing is a way to test your UI component without writing actual test cases*

https://voice.kadira.io/snapshot-testing-in-react-storybook-43b3b71cec4f#.skc9w5rkj

> **TL;DR**: Jest's snapshot testing has now been introduced to [Storybook](https://github.com/storybooks/react-storybook) which allows you to leverage the stories written out for rendering regression testings. Although snapshot testing won't replace all unit tests for React components, it will be able to automatically run the more mundane tests relating to the proper rendering of a component.
