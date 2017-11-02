# 1000 Resources to Read

- [JSConf](#jsconf)
- [Styling](#styling)
   - [CSS](#css)
   - [SCSS](#scss)
   - [BEM](#BEM)
   - [Styled Components](#styled-components)
- [Javascript](#javascript)
   - [Functional Programming](#functional-programming)
   - [ES6](#es6)
   - [ImmutableJS](#immutablejs)
   - [General Patterns](#general-patterns)
   - [Helper Libraries](#helper-libraries)
   - [Observables](#observables)
- [React](#react)
   - [Components](#components)
   - [Styling](#styling)
   - [State](#state)
   - [Redux](#redux)
   - [Events](#react-events)
- [Testing](#testing)
   - [React](#react)
   - [Jest](#jest)
   - [Jasmine](#jasmine)
   - [Snapshot Testing](#snapshot-testing)
   - [Redux](#redux)
   - [Integration Testing](#integration-testing)

## JSConf

#### [Video - 31:31] Hacking Games and Why You Should Do It

https://www.youtube.com/watch?v=pSMljRkpP64

> **TL;DR** Hacking games allows you to perfect your analytical code skills while having fun. It also exposes to other developers' code, which may help you improve your own.

#### [Video - 30:44] Machine Learning with Node.js

> **TL;DR** Machine learning is all about computing probabilities for a defined set of inputs and possible outcomes. Neural networks allow you to reinforce strong data relationships while mutating weaker ones.

## Styling

### CSS

#### How Flexbox works — explained with big, colorful, animated gifs

*Flexbox promises to save us from the evils of plain CSS (like vertical alignment). Well, Flexbox does deliver on that goal. But mastering its new mental model can be challenging.*

https://medium.freecodecamp.com/an-animated-guide-to-flexbox-d280cf6afc35#.pmvck2u9x

> **TL;DR**: `flex-direction` plays directly onto the main (horizontal) and cross (vertical) axes by inverting them in the case of `flex-direction:column`. Secondary styles such as `justify-content` and `align-items` work directly on these axes and it's important to keep in mind in which direction the main axes is currently oriented, in order to correctly guage the result. 

#### EM vs REM vs PX – Why you shouldn't "just use pixels"

*We, like many others, were ready to ditch REMs and return to the beloved pixel. We lost track of why we adopted the use of REMs in the first place. The problem doesn’t just revolve around font-sizes - it’s also about accessibility.*

http://engageinteractive.co.uk/blog/em-vs-rem-vs-px

> **TL;DR**: REMs are a relative unit, similar to EMs, that measure its size relative to the `HTML` element. This means that you allow for better accessibility by being able to grow all text by a relative size, such as EMs, while not experiencing nested hell by need to set your size relative to the parent element.

#### Pointer-Events

*The `pointer-events` property allows for control over how HTML elements respond to mouse/touch events – including CSS hover/active states, click/tap events in Javascript, and whether or not the cursor is visible.*

https://css-tricks.com/almanac/properties/p/pointer-events/

> **TL;DR**: `pointer-events` allows to control user intentions through and around a given HTML element. By setting `pointer-events` to `none`, the browser will handler user interactions on the next available element below the given element, while Javascript events will behave the same way.

#### A Complete Guide to Flexbox

*The Flexbox Layout module aims at providing a more efficient way to lay out, align and distribute space among items in a container, even when their size is unknown and/or dynamic*

https://css-tricks.com/snippets/css/a-guide-to-flexbox/

> **TL;DR**: Flexboxes are handy when it comes to altering a container's items on a certain axis for all of its rendering properties (dimensions, direction, alignment, wrapping, ordering, ...). This system offers an alternative to the display block/inline solutions that have limitations when it comes to creating a grid of items that are fully flexible.

#### A Complete Guide to Grid

*CSS Grid Layout is the most powerful layout system available in CSS. It is a 2-dimensional system, meaning it can handle both columns and rows, unlike flexbox which is largely a 1-dimensional system. You work with Grid Layout by applying CSS rules both to a parent element (which becomes the Grid Container) and to that elements children (which become Grid Items).*

https://css-tricks.com/snippets/css/complete-guide-grid/

> **TL;DR**: CSS Grid systems helps fill in the gap that is left by Flexbox, when trying to build 2-dimensional grid systems (in both rows and columns). It allows you to build this system fully in CSS, so unlike buildling grids through `table`s or `flexbox`, your structure isn't being defined in HTML.

#### An Introduction to the `fr` CSS unit

*With all the excitement around CSS Grid, I haven't seen as much talk about the new fr CSS length unit. And now that browser support is rapidly improving for this feature, I think this is the time to explore how it can be used in conjunction with our fancy new layout engine because there are a number of benefits when using it; more legible and maintainable code being the primary reasons for making the switch.*

https://css-tricks.com/introduction-fr-css-unit/

> **TL;DR**: The `fr` unit allows you to create `flex fraction`s, which essentially takes the remaining space allows to given components and splits it based on the accumulated `fr`s found in all its siblings. Given that this can be mixed with other more static units of measurements in CSS, this allows you to create highly dynamic and flexible systems, such as a fluid column system that takes the remaining space around a fixed-size sidebar.

#### [Video - 2:59] Grid by Example: the fr unit

https://www.youtube.com/watch?v=N731aTpo8TI

> **TL;DR**: A few examples of working through certain scenarios with `fr` units.

### SCSS

#### How to Use Sass Mixins

*Sass is incredible. Whether using it as Sass or SCSS, it improves productivity and makes complex CSS tasks easy. Sass is easy to debug and lets us do more with CSS.*

https://scotch.io/tutorials/how-to-use-sass-mixins

> **TL;DR**: Sass is a powerful tool to complement your css styling, allowing you to reduce your code complexity through code re-use, both on styles and style selector rules.

### BEM

#### BEM - Block Element Modifier

*On smaller brochure sites, how you organize your styles isn’t usually a big concern. You get in there, write some CSS, or maybe even some SASS. You compile it all into a single stylesheet with SASS’s production settings, and then you aggregate it to get all the stylesheets from modules into a nice tidy package.*

http://getbem.com/introduction/

> **TL;DR**: BEM allows you to better organize your styling by defining a naming convention for your classes, which sets purpose to your class assignments. It also imposes a nesting structure, which also works great for limiting styling overflow between elements.

#### ‘Why BEM?’ in a nutshell

**The two base concepts of CSS? Inheritance and specificity.**

https://blog.decaf.de/2015/06/24/why-bem-in-a-nutshell/

> **TL;DR**: BEM tries to solve two of CSS's main issues: inheritence and specificity. By scoping blocks to a certain namespace (BEM block name), you are scoping down your styles to only affect the one block element and below. In terms of specificity, keeping these blocks as small as possible reduces the specificity required to override styles within these blocks.

### Styled Components

#### The magic behind styled-components

http://mxstbr.blog/2016/11/styled-components-magic-explained/

> **TL;DR**: Styled components leverages Tagged Template Literals, a new feature coming from ES6 which allows us to call a function while providing template interpolations as separate functions to the argument set, which allows Styled Components to render out styles as a function of the results of these interpolations.

#### [Video - 1:10:45] Styled Components - JS Channel

https://www.youtube.com/watch?v=ftSzsghg2io

> **TL;DR** Great walkthrough of the various solutions to styling in React, presents the pros and cons of all solutions and explains why Styled Components helps improve organization and implementation while maintaining full CSS support.

#### Add styled components - Let's talk

https://github.com/gitpoint/git-point/issues/480#issuecomment-337886247

> **TL;DR**: Insightful discussion thread about a code repository transitionning to using styled components. A good insight into the decision making of what/how this would affect an every day codebase.

## Javascript

### Functional Programming

#### [Video - 29:56] Anjana Vakil: Learning Functional Programming with JavaScript

https://www.youtube.com/watch?v=e-5obm1G_FY

> **TL;DR**: One concept to remember from this is that immutability is exploiting object's use of references to allow to minimize structure repeat between mutated data structures by referencing structures between objects that have not been modified. Although it speaks more to the usage of functional programming as a whole, it unfortunately doesn't go into depth about the functional programmning mindset.

#### Why Curry Helps

*A programmer’s pipe-dream is to write code, and be able to use it repeatedly with little effort. It’s expressive because you write in a way that expresses what is needed, and it’s reuse because.. well, you’re reusing. What more could you want?*

https://hughfdjackson.com/javascript/why-curry-helps/

   > **TL;DR**: In these examples, currying is used to setup each operation with Ramda functions, and passing data through each sequentially through a Promise object. The same pattern can be used with a compose to stream the result of each operation through to the next. The advantage of this is that it allows you to either break complex data operations into smaller pieces or abstract it away into its own method, currying as you get more data.

#### Understanding Javascript Array Reduce in 1 Minute

*Everybody knows what looping over a collection is. But do you know what reducing a collection means?*

https://www.airpair.com/javascript/javascript-array-reduce

> **TL;DR** Reduce essentially iterates through your Array set, pushing along an accumulator value that you can set values to. 

#### FunFunFunction

https://www.youtube.com/channel/UCO1cgjhGzsSYb1rsB4bFe4Q

> **TL;DR**: A great channel that walks you through the various facets of functional programming, building on the fundamental principles to punch the boundaries on what you can achieve. Also has many videos on thoughts/opinions on what makes a programmer good, both from the perspective of an employer but also from the perspective of a fellow programmer.

#### [Video - 30:16] Hey Underscore, You're Doing It Wrong!

*Brian Lonsdorf has a love-hate relationship with Underscore.js. Yes, it offers a bunch of tools included in today's functional programming paradigm (like map, filter, reduce, take, drop, compose, etc.), but in Underscore the functions are sometimes verbose and unintuitive. It claims to be a functional programming language, but how true is that?*

https://www.youtube.com/watch?v=m3svKOdZijA

> **TL;DR**: Some functional libraries such as **Underscore** and **lodash** do offer functions that are leveraged through functional programming, but fall short of truly embodying the patterns offered by functional programming. The examples are shown alongside **Ramda**, in order to demonstrate the power of such a library that fully implements functional programming.

### ES6

#### Javascript ES6: Learn important features in a few minutes

*The next-generation of javascript also known as ECMAScript 6 (also called ES6 or Harmony), is bringing us lots of amazing features that you probably will need to know. But instead of you spend too much time learning and researching all of the features I separated a few that I felt are the ones you'll be probably using in your daily basis.*

https://www.frontendjournal.com/javascript-es6-learn-important-features-in-a-few-minutes/

> **TL;DR** ES6 Javascript offers alot of features that have been lacking in Javascript in the past. Node.js has been supporting ES6 for a while, while browsers are lacking behind, but are slowly catching up. Therefore, it's good to start learning these new syntaxes. It's important to keep in mind that quite a few ES6 syntax is really just *"sugar syntax"*, meaning that it's simplified syntax that accomplishes the same task as some syntax you're already accustomed to. Knowing this, you shouldn't shy away of learning these new syntaxes.

#### 6 Great Uses of the Spread Operator

*Thanks to ES6 and the likes of Babel, writing JavaScript has become incredibly dynamic, from new language syntax to custom parsing like JSX.  I've become a big fan of the spread operator, three dots that may change the way you complete tasks within JavaScript.  The following is a listing of my favorite uses of the spread operator within JavaScript!*

https://davidwalsh.name/spread-operator

> **TL;DR** Spread operators are great when trying grab or set *all* values found within a variable. This can be used to quickly manipulate objects, arrays, event arguments lists into whatever configuration or structure you require.

### [Video - 31:10] React.js Conf 2015 - Immutable Data and React

*Immutable data unlocks powerful memoization techniques and prohibits accidental coupling via shared mutable state. It's no accident that these are the the same benefits provided by React.*

https://www.youtube.com/watch?v=I7IdS-PbEgI

> **TL;DR**: ImmutableJS offers a persistent data structure by never modifying the current state, always returning the new state. This allows your functions to be memoized by returning the old state if no changes to the function's parameters is passed. 

### ImmutableJS

### General Patterns

#### The Difference Between Throttling and Debouncing

*I got these confused the other day and someone corrected me. So I tossed it on the ol' list of blog post ideas and here we are. Both of them are ways to limit the amount of JavaScript you are executing based on DOM events for performance reasons. But they are, you guessed it, different.*

https://css-tricks.com/the-difference-between-throttling-and-debouncing/

> **TL;DR**: **Debouncing** enforces that a function not be called again until a certain amount of time has passed without it being called. **Throttling** enforces a maximum number of times a function can be called over time.

### Helper Libraries

#### Underscore vs Lo-Dash

https://benmccormick.org/2014/11/12/underscore-vs-lodash/

> **TL;DR** Underscore and Lo-Dash intends to address the same problem: Cross-browser compatibility functional programming. Based on this article, Lo-dash comes out the clear winner on three aspects: Performance, Usability and functionality offered. Keep in mind that this article was written in 2014.

### Observable

#### Streams - FunFunFunction

https://www.youtube.com/watch?v=UD2dZw9iHCc

*A stream is a flow of values that will be arriving whenever they feel like.*

> **TL;DR** You can see streams as a collection of data that is iterable like an array, but that will be iterated as the data arrives, just like a promise.

#### RxJS Observables Crash Course

*Over an hour of programming with RxJS (Reactive Extensions) using observables and asynchronous data streams. The content is based on our ReactiveX Eduonix course*

> **TL;DR** A good coverage of the fundamentals of observables through RxJS, covering the most common Observable setups and operators.

## React

#### How I built a product in 5 weeks using Meteor and React

*Or how Ruutly came to life*

https://blog.416serg.me/how-i-built-a-product-in-5-weeks-using-meteor-and-react-ca2cfad35dcc#.jb37d55b3

> **TL;DR** Meteor works very well with React when developing native apps. 

#### Reconciliation

*React provides a declarative API so that you don't have to worry about exactly what changes on every update. This makes writing applications a lot easier, but it might not be obvious how this is implemented within React.*

https://facebook.github.io/react/docs/reconciliation.html

> **TL;DR** React's reconciliation algorithm allows to more efficiently update the DOM based on the new React trees. Making a few assumptions, its algorithms chooses which parts of the new React tree has changed compared to the previous tree, so it can reduce the number of unecessary manipulations on the DOM. 

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

#### Never Write Another HoC

*Michael Jackson, creator of the React Router library, gives this talk where he says a component with a render prop or children prop as renderer can do anything an HoC (Higher Order Component) can do, and more.*

https://www.youtube.com/watch?v=BcVAq3YFiuc

> **TL;DR** Higher Order Components have fundamental issues as a pattern that does create unecessary abstraction and separation of knowledge between its class implementation and composition. Components with render props attempt to solve these HOC shortcomings by simplifying the execution flow through these components. By using a render prop, you allow your components do be alot more declarative and explicit to the values it receives and uses, while avoiding the common pitfalls of HoCs.

### Styling

#### Modular CSS with React

*A lot of thought was given to the challenges that arise from building complex applications, and this stack solves a lot of them beautifully. Yet, I still wasn’t sure how to make styling live up to React’s modularity and reusability.*

*Fortunately, there have been some very interesting developments in CSS-land recently, with a lot of patterns and tools emerging to make modular CSS a reality.*

https://medium.com/@pioul/modular-css-with-react-61638ae9ea3e#.c997jfnkn

> **TL;DR** Both CSS ([CSS-Modules](https://github.com/css-modules/css-modules)) and Javascript ([CSS-in-JS](https://speakerdeck.com/vjeux/react-css-in-js)) propose opposing implementations to a similar solution/result. As tools allowing you to better handle styling in Javascript evolve and improve, so will CSS standards and availability of pre/post-processors through Webpack. On paper, they offer similar functionality coverage, with both having better implementation ease in certain situations. However, CSS-Modules seem to allow for better styling since they more *easily* offer pseudo styles, such as media queries, pseudo elements and pseudo selectors.  

### State

#### 3 Reasons why I stopped using React.setState
*Since a few months I’ve stopped using React’s setState on all my new React components. Don’t get me wrong, I didn’t stop having local component state, I just stopped using React to manage it. And it’s been delightful!*

https://medium.com/@mweststrate/3-reasons-why-i-stopped-using-react-setstate-ab73fc67a42e

> **TL;DR** `React.setState` can be misleading since it doesn't necessarily assign the new state immediately; it could simply schedule a state change in the near future. It's important to note that `React.setState` is asynchronous, which means that it's easy to fall into a few pitfalls. Firstly, when trying to access state right after calling `React.setState` won't necessarily get you the updated value since this is an asynchronous function. Secondly, when running calculations that are based off of previous state, it's a good idea to pass a function through `React.setState` in order to execute that operation once it's scheduled/ready to run (other state changes might have occured betweeen scheduling and execution.

### Redux

#### [Video - 37:13] Netflix JavaScript Talks - RxJS + Redux + React = Amazing!

*Jay Phelps (@_jayphelps ) talks about why Netflix loves reactive programming with Rx. In this talk he shares the basics of RxJS 5 Observables and how they can be used with React and Redux to manage asynchronous effects using redux-observable.*

https://www.youtube.com/watch?v=AslncyG8whg

> **TL;DR** [Redux-Observable](https://github.com/redux-observable/redux-observable) offers means of tracking, managing and cancelling your asynchronous executions. This offers a middleware between your action creators and reducers in your Redux world.

#### You Might Not Need Redux

*People often choose Redux before they need it. “What if our app doesn’t scale without it?” Later, developers frown at the indirection Redux introduced to their code. “Why do I have to touch three files to get a simple feature working?” Why indeed!*

https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367#.x7p4tms7k

> **TL;DR**: Redux, offering its benefits, has its own trade-off with its own constraints it sets on the data. It would be safe decision to not always jump the gun on committing to a Redux implementation, as it comes with certain strong conventions on how data should be managed. Although the questions asked here isn't necessarily "Is Redux the best tool", what it's trying to ask is "Is it too soon in the development lifecycle of the application to be commiting to Redux".

### Events

#### SyntheticEvent

*Your event handlers will be passed instances of SyntheticEvent, a cross-browser wrapper around the browser's native event. It has the same interface as the browser's native event, including stopPropagation() and preventDefault(), except the events work identically across all browsers.*

https://facebook.github.io/react/docs/events.html

> **TL;DR**: React wraps ever DOM events into a Synthetic event, which allows for full browser compatibility. Its intent is to still behave like any DOM event, and so you still have access to the common methods and data. One thing to note is that the synthetic events cannot be access asynchronously as they are pooled. If you need to access an event asynchronously, you should use `e.persist()`.

#### Handling Events

https://facebook.github.io/react/docs/handling-events.html

> **TL;DR**: Handling events on React elemnents is very similar to handing events on DOM elements. A few key difference is that React events are named camelCase instead of lowercase (ie on DOM or React elements) and in React you pass a function reference as the event handler, as opposed to a string referencing a function.

## Testing

### React

#### The Right Way to Test React Components
*There’s a lot of confusion right now about the “right” way to test your React components. Should you write all your tests by hand, or only use snapshots, or some of both? Should you test props? State? Styles/Layout?*

*I don’t think there’s one “right” way, but I’ve found a few patterns and tips that work really well for me that I’d like to share.*

https://medium.freecodecamp.com/the-right-way-to-test-react-components-548a4736ab22#.wgubj2c04

> **TL;DR** Understanding the role (*"contract"*) of a component is key to being confident that your tests are correctly testing the component's functionalities without testing aspects that are outside of its scope of concern. Breaking these functionalities into small statements (or predicates) allows you to better structure your tests in logical groupings based on the individual goal and environment setup.

#### Why you should stub, not shallow render, child components when testing React

*Stubbing/mocking a React component is a better way than shallow rendering to avoid brittle unit tests while still preserving the ability to test the full component lifecycle.*

http://engineering.pivotal.io/post/stub-dont-shallow-render-your-child-components/

> **TL;DR**: It's important to test your components separate from the implementation of their child components, in order to avoid making your components brittle. While `shallow` mounting through `Enzyme` might be fine for most of your tests, you do lose access to the component lifecycle methods, meaning that you have less tools at your disposal when testing your components. By stubbing your Child components, you avoid brittleness in your tests as you're assured that any functional dependencies in those implementations don't need to be accounted for on the tests of your parent component.

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

> **TL;DR**: Snapshot testing offers a strong strategy for regression testing, but there are trade-offs to be calculated before running ahead with it. Firstly, snapshot testing requires human interaction to validate the diffs prior to it being merged into the code base, which raised a risk of errors being introduced. Context is also hard to define for tests through snapshots since the tests don't always offer as much description since code is minimal. 

#### Snapshot Testing in React Storybook

*Snapshot testing is a way to test your UI component without writing actual test cases*

https://voice.kadira.io/snapshot-testing-in-react-storybook-43b3b71cec4f#.skc9w5rkj

> **TL;DR**: Jest's snapshot testing has now been introduced to [Storybook](https://github.com/storybooks/react-storybook) which allows you to leverage the stories written out for rendering regression testings. Although snapshot testing won't replace all unit tests for React components, it will be able to automatically run the more mundane tests relating to the proper rendering of a component.

### Redux

#### Encapsulating the Redux State Tree

*In a Redux application, the bulk of the application’s data is stored as a “state tree” in a central location, the store. The shape and structure of the state tree has a large impact on the ease of development and performance of the application. It is often valuable to refactor the state tree over time to address issues. How do we do this safely?*

http://randycoulman.com/blog/2016/09/13/encapsulating-the-redux-state-tree/

> **TL;DR**: Encapsulation is a powerful pattern in the Redux world in order to centralize each type of execution of the store data in the same location. From reading through selectors or writing in reducers and action creators, it greatly simplifies your component code and testing code by enforcing a certain flow through these modules. For example, writing your reducer tests by referencing action creators and selectors allows you to more easily refactor your store without having to refactor your tests.

### Integration Testing

#### [Video - 1:00:31] Testing, the way it should be

*Testing is the essential bedrock of software, and we can all agree it a must-have. But when we talk about writing tests for the front-end, most developers immediately run into several challenges. Brian Mann will introduce a new JavaScript testing tool, Cypress.io, which solves the hardest challenges of testing modern, complex applications. You'll leave this talk re-energized and believe that testing can be a fun, enjoyable experience without the soul crushing pain it is today.*

https://www.youtube.com/watch?v=yq99BvSe1AQ&t=666s

> **TL;DR**: [Cypress.io](https://www.cypress.io/) attempts to solve all the developper pain points of End-to-end testing frameworks by making tests easy to write, quick to run and simple to debug. It also allows to take snapshots of the rendering, run on different browsers and control the viewport size. All you need.

#### Testing React Components using Storybook and Cypress

https://medium.com/@mtiller/testing-react-components-using-storybook-and-cypress-1689a27f55aa

> **TL;DR**: interesting take on automating testing in of React components in Storybook through Cypress. Especially with Crypress's generated artifcacts on test failure, this would be a great approach to cover cross-browser compatibility, rendering regression and overall component functionality. 

### Cypress.io

#### Cypress.io - `cy.contains()`

https://docs.cypress.io/api/commands/contains.html#Scopes

> **TL;DR**: Great article about the exceptional bhaviours of the `.contains()` function, as opposed to other selecting operations in Cypres.io.
