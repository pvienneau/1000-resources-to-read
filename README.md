# 1000 Resources to Read

- [JSConf](#jsconf)
- [CSS](#css)
- [Javascript](#javascript)
 - [Functional Programming](#functional-programming)
 - [ES6](#es6)
- [React](#react)
 - [Components](#components)
 - [Styling](#styling)
 - [Redux](#redux)
- [Testing](#testing)
 - [React](#react)
 - [Jest](#jest)
 - [Jasmine](#jasmine)
 - [Snapshot Testing](#snapshot-testing)
 - [Redux](#Redux)

## JSConf

#### [Video - 31:31] Hacking Games and Why You Should Do It

https://www.youtube.com/watch?v=pSMljRkpP64

> **TL;DR** Hacking games allows you to perfect your analytical code skills while having fun. It also exposes to other developers' code, which may help you improve your own.

## CSS

#### How Flexbox works — explained with big, colorful, animated gifs

*Flexbox promises to save us from the evils of plain CSS (like vertical alignment). Well, Flexbox does deliver on that goal. But mastering its new mental model can be challenging.*

https://medium.freecodecamp.com/an-animated-guide-to-flexbox-d280cf6afc35#.pmvck2u9x

> **TL;DR**: `flex-direction` plays directly onto the main (horizontal) and cross (vertical) axes by inverting them in the case of `flex-direction:column`. Secondary styles such as `justify-content` and `align-items` work directly on these axes and it's important to keep in mind in which direction the main axes is currently oriented, in order to correctly guage the result. 

## Javascript

### Functional Programming

#### [Video - 29:56] Anjana Vakil: Learning Functional Programming with JavaScript

https://www.youtube.com/watch?v=e-5obm1G_FY

> **TL;DR**: One concept to remember from this is that immutability is exploiting object's use of references to allow to minimize structure repeat between mutated data structures by referencing structures between objects that have not been modified. Although it speaks more to the usage of functional programming as a whole, it unfortunately doesn't go into depth about the functional programmning mindset.

#### Understanding Javascript Array Reduce in 1 Minute

*Everybody knows what looping over a collection is. But do you know what reducing a collection means?*

https://www.airpair.com/javascript/javascript-array-reduce

> **TL;DR** Reduce essentially iterates through your Array set, pushing along an accumulator value that you can set values to. 

### ES6 (#es6)

#### Javascript ES6: Learn important features in a few minutes

*The next-generation of javascript also known as ECMAScript 6 (also called ES6 or Harmony), is bringing us lots of amazing features that you probably will need to know. But instead of you spend too much time learning and researching all of the features I separated a few that I felt are the ones you'll be probably using in your daily basis.*

https://www.frontendjournal.com/javascript-es6-learn-important-features-in-a-few-minutes/

> **TL;DR** ES6 Javascript offers alot of features that have been lacking in Javascript in the past. Node.js has been supporting ES6 for a while, while browsers are lacking behind, but are slowly catching up. Therefore, it's good to start learning these new syntaxes. It's important to keep in mind that quite a few ES6 syntax is really just *"sugar syntax"*, meaning that it's simplified syntax that accomplishes the same task as some syntax you're already accustomed to. Knowing this, you shouldn't shy away of learning these new syntaxes.

## React

#### How I built a product in 5 weeks using Meteor and React

*Or how Ruutly came to life*

https://blog.416serg.me/how-i-built-a-product-in-5-weeks-using-meteor-and-react-ca2cfad35dcc#.jb37d55b3

> **TL;DR** Meteor works very well with React when developing native apps. 

### Components

#### Presentational and Container Components

https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.gycwunsod

> **TL;DR** There is advantages to splitting components into separate components with specific purposes; container and presentational components. In general terms, presentational components should be solely responsible for the rendering of its data, while container components' purpose is more focused on the transformation of the data and the dispatching of this data through other components. Although there is no specific technical rule for how to split components, components can more easily be split based on their roles and areas of concern.

#### Container Components

*One React pattern that has had the greatest effect on my code is the container component pattern.*

https://medium.com/@learnreact/container-components-c0e67432e005#.l4toj1nl2

> **TL;DR** Splitting your components into two area of concern (UI and data) offers better reusability (since the data/context and UI not as tightly coupled) and it offers an extra layer of of prop valiation through PropTypes in order to avoid your application failing silently.

#### How we’re using Component Based Design

*Component Based Design is often talked about in context of large, complex projects. In this post we’re making the case that it can also be very beneficial for smaller projects and teams. We now use Component Based Design for every project, big or small.*

https://medium.com/@lewisplushumphreys/how-were-using-component-based-design-5f9e3176babb#.83bks7z0h

> **TL;DR** Building React components from the ground up (component-based design) allows you to maintain a high level of reusability across your project from the start. By defining varying levels of purposes for components, you can maximize your reusability while keeping maintainability as simple as possible.

#### Binding callbacks in React components

https://medium.com/@rjun07a/binding-callbacks-in-react-components-9133c0b396c6#.hmyr5muij

> **TL;DR**: As React class methods aren't automatically binded to their scope, this step needs to be done manually. It's best to avoid binding these inside the render function since the two most common approaches to method binding - arrow functions and `bind()` generate a new function per call, adding extra weight on the `render()` method's execution. For that reason, it's best to do this outside of the `render()` method, either in the constructor or with an arrow function class property.

#### [Video - 21:59] Netflix JavaScript Talks - React plus X: Best Practices for Reusable UI Components

Mars Jullian ([@marsjosephine](https://twitter.com/marsjosephine)), Senior UI Engineer at Netflix, shares best practices for writing reusable components with React including h ow to define flexible props for React components and keep your coworkers from going crazy.

https://www.youtube.com/watch?v=Yy7gFgETp0o

**TL;DR** Many great UI best practices are offered here to optimize the self-sufficiency and integration of reusable components. Firstly, it's worth being as explicit as possible when defining your components' behaviour in order for other developers to gain as much context as possible on how to properly use your components. This is accomplished by defining a detailed set of `proptypes` for your components, even when defining complex data structures. Also, the `rest` operator would be discouraged on the fact that it allows a backdoor access to your HTML elements, by allowing outside forces to push unexpected props to your component, that will get pushed directly through to your HTML elements. Additionally, a good point was made with regards to styling your components; styling that affects the outside of your element's box, such as margin and padding, should not be defined by the component itself, rather by its parent component. This is because components should be self-sufficient, only affecting content that is considered within its world.

#### Function as Child Components

https://medium.com/merrickchristensen/function-as-child-components-5f3920a9ace9#.qlfg97204

> **TL;DR** Function as child components allows better flexibility outside of your component as to how render the data out. By passing a function as a child to a component (and that component calling that function on render), you are empowering outside components to defined their own render logic. An excellent example of this is if you created a `<MediaQuery />` component, you could defined a function as a child that would take in a boolean flag that let you render specific components whenever that specific query is matched.

### Styling

#### Modular CSS with React

*A lot of thought was given to the challenges that arise from building complex applications, and this stack solves a lot of them beautifully. Yet, I still wasn’t sure how to make styling live up to React’s modularity and reusability.*

*Fortunately, there have been some very interesting developments in CSS-land recently, with a lot of patterns and tools emerging to make modular CSS a reality.*

https://medium.com/@pioul/modular-css-with-react-61638ae9ea3e#.c997jfnkn

> **TL;DR** Both CSS ([CSS-Modules](https://github.com/css-modules/css-modules)) and Javascript ([CSS-in-JS](https://speakerdeck.com/vjeux/react-css-in-js)) propose opposing implementations to a similar solution/result. As tools allowing you to better handle styling in Javascript evolve and improve, so will CSS standards and availability of pre/post-processors through Webpack. On paper, they offer similar functionality coverage, with both having better implementation ease in certain situations. However, CSS-Modules seem to allow for better styling since they more *easily* offer pseudo styles, such as media queries, pseudo elements and pseudo selectors.  

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

### React

#### The Right Way to Test React Components
*There’s a lot of confusion right now about the “right” way to test your React components. Should you write all your tests by hand, or only use snapshots, or some of both? Should you test props? State? Styles/Layout?*

*I don’t think there’s one “right” way, but I’ve found a few patterns and tips that work really well for me that I’d like to share.*

https://medium.freecodecamp.com/the-right-way-to-test-react-components-548a4736ab22#.wgubj2c04

> **TL;DR** Understanding the role (*"contract"*) of a component is key to being confident that your tests are correctly testing the component's functionalities without testing aspects that are outside of its scope of concern. Breaking these functionalities into small statements (or predicates) allows you to better structure your tests in logical groupings based on the individual goal and environment setup.

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

#### Snapshot Testing: Use With Care

*Snapshot Testing has been getting a fair bit of attention recently with some new tool support that makes it easy to use. But is that a good thing?*

http://randycoulman.com/blog/2016/09/06/snapshot-testing-use-with-care/

> **TL;DR** Snapshot testing offers a strong strategy for regression testing, but there are trade-offs to be calculated before running ahead with it. Firstly, snapshot testing requires human interaction to validate the diffs prior to it being merged into the code base, which raised a risk of errors being introduced. Context is also hard to define for tests through snapshots since the tests don't always offer as much description since code is minimal. 

#### Snapshot Testing in React Storybook

*Snapshot testing is a way to test your UI component without writing actual test cases*

https://voice.kadira.io/snapshot-testing-in-react-storybook-43b3b71cec4f#.skc9w5rkj

> **TL;DR** Jest's snapshot testing has now been introduced to [Storybook](https://github.com/storybooks/react-storybook) which allows you to leverage the stories written out for rendering regression testings. Although snapshot testing won't replace all unit tests for React components, it will be able to automatically run the more mundane tests relating to the proper rendering of a component.

### Redux

#### Encapsulating the Redux State Tree

*In a Redux application, the bulk of the application’s data is stored as a “state tree” in a central location, the store. The shape and structure of the state tree has a large impact on the ease of development and performance of the application. It is often valuable to refactor the state tree over time to address issues. How do we do this safely?*

http://randycoulman.com/blog/2016/09/13/encapsulating-the-redux-state-tree/

> **TL;DR** Encapsulation is a powerful pattern in the Redux world in order to centralize each type of execution of the store data in the same location. From reading through selectors or writing in reducers and action creators, it greatly simplifies your component code and testing code by enforcing a certain flow through these modules. For example, writing your reducer tests by referencing action creators and selectors allows you to more easily refactor your store without having to refactor your tests.
