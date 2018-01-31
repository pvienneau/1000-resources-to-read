## Testing

#### The Right Way to Test React Components
*There’s a lot of confusion right now about the “right” way to test your React components. Should you write all your tests by hand, or only use snapshots, or some of both? Should you test props? State? Styles/Layout?*

*I don’t think there’s one “right” way, but I’ve found a few patterns and tips that work really well for me that I’d like to share.*

https://medium.freecodecamp.com/the-right-way-to-test-react-components-548a4736ab22#.wgubj2c04

> **TL;DR** Understanding the role (*"contract"*) of a component is key to being confident that your tests are correctly testing the component's functionalities without testing aspects that are outside of its scope of concern. Breaking these functionalities into small statements (or predicates) allows you to better structure your tests in logical groupings based on the individual goal and environment setup.

#### Why you should stub, not shallow render, child components when testing React

*Stubbing/mocking a React component is a better way than shallow rendering to avoid brittle unit tests while still preserving the ability to test the full component lifecycle.*

http://engineering.pivotal.io/post/stub-dont-shallow-render-your-child-components/

> **TL;DR**: It's important to test your components separate from the implementation of their child components, in order to avoid making your components brittle. While `shallow` mounting through `Enzyme` might be fine for most of your tests, you do lose access to the component lifecycle methods, meaning that you have less tools at your disposal when testing your components. By stubbing your Child components, you avoid brittleness in your tests as you're assured that any functional dependencies in those implementations don't need to be accounted for on the tests of your parent component.
