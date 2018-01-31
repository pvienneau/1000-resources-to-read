## Redux

#### [Video - 37:13] Netflix JavaScript Talks - RxJS + Redux + React = Amazing!

*Jay Phelps (@_jayphelps ) talks about why Netflix loves reactive programming with Rx. In this talk he shares the basics of RxJS 5 Observables and how they can be used with React and Redux to manage asynchronous effects using redux-observable.*

https://www.youtube.com/watch?v=AslncyG8whg

> **TL;DR** [Redux-Observable](https://github.com/redux-observable/redux-observable) offers means of tracking, managing and cancelling your asynchronous executions. This offers a middleware between your action creators and reducers in your Redux world.

#### You Might Not Need Redux

*People often choose Redux before they need it. “What if our app doesn’t scale without it?” Later, developers frown at the indirection Redux introduced to their code. “Why do I have to touch three files to get a simple feature working?” Why indeed!*

https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367#.x7p4tms7k

> **TL;DR**: Redux, offering its benefits, has its own trade-off with its own constraints it sets on the data. It would be safe decision to not always jump the gun on committing to a Redux implementation, as it comes with certain strong conventions on how data should be managed. Although the questions asked here isn't necessarily "Is Redux the best tool", what it's trying to ask is "Is it too soon in the development lifecycle of the application to be committing to Redux".

#### Encapsulating the Redux State Tree

*In a Redux application, the bulk of the application’s data is stored as a “state tree” in a central location, the store. The shape and structure of the state tree has a large impact on the ease of development and performance of the application. It is often valuable to refactor the state tree over time to address issues. How do we do this safely?*

http://randycoulman.com/blog/2016/09/13/encapsulating-the-redux-state-tree/

> **TL;DR**: Encapsulation is a powerful pattern in the Redux world in order to centralize each type of execution of the store data in the same location. From reading through selectors or writing in reducers and action creators, it greatly simplifies your component code and testing code by enforcing a certain flow through these modules. For example, writing your reducer tests by referencing action creators and selectors allows you to more easily refactor your store without having to refactor your tests.
