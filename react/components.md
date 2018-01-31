## Components

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

#### React, Inline Functions, and Performance

https://cdb.reacttraining.com/react-inline-functions-and-performance-bdff784f5578

**TL;DR**: Speaking towards component rendering performance, the case is being made the inline functions, being re-defined per render call execution, doesn't really burden your application. Rather, the focus should more around correct usage of the `shouldComponentUpdate` lifecycle method and the `PureComponent` component.

#### [Video - 21:59] Netflix JavaScript Talks - React plus X: Best Practices for Reusable UI Components

*Mars Jullian ([@marsjosephine](https://twitter.com/marsjosephine)), Senior UI Engineer at Netflix, shares best practices for writing reusable components with React including h ow to define flexible props for React components and keep your coworkers from going crazy.*

https://www.youtube.com/watch?v=Yy7gFgETp0o

**TL;DR** Many great UI best practices are offered here to optimize the self-sufficiency and integration of reusable components. Firstly, it's worth being as explicit as possible when defining your components' behaviour in order for other developers to gain as much context as possible on how to properly use your components. This is accomplished by defining a detailed set of `proptypes` for your components, even when defining complex data structures. Also, the `rest` operator would be discouraged on the fact that it allows a backdoor access to your HTML elements, by allowing outside forces to push unexpected props to your component, that will get pushed directly through to your HTML elements. Additionally, a good point was made with regards to styling your components; styling that affects the outside of your element's box, such as margin and padding, should not be defined by the component itself, rather by its parent component. This is because components should be self-sufficient, only affecting content that is considered within its world.

#### Function as Child Components

https://medium.com/merrickchristensen/function-as-child-components-5f3920a9ace9#.qlfg97204

> **TL;DR** Function as child components allows better flexibility outside of your component as to how render the data out. By passing a function as a child to a component (and that component calling that function on render), you are empowering outside components to defined their own render logic. An excellent example of this is if you created a `<MediaQuery />` component, you could defined a function as a child that would take in a boolean flag that let you render specific components whenever that specific query is matched.

#### Never Write Another HoC

*Michael Jackson, creator of the React Router library, gives this talk where he says a component with a render prop or children prop as renderer can do anything an HoC (Higher Order Component) can do, and more.*

https://www.youtube.com/watch?v=BcVAq3YFiuc

> **TL;DR** Higher Order Components have fundamental issues as a pattern that does create unecessary abstraction and separation of knowledge between its class implementation and composition. Components with render props attempt to solve these HOC shortcomings by simplifying the execution flow through these components. By using a render prop, you allow your components do be alot more declarative and explicit to the values it receives and uses, while avoiding the common pitfalls of HoCs.
