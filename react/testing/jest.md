## Jest

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
