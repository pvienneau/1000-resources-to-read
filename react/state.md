## State

#### 3 Reasons why I stopped using React.setState
*Since a few months I’ve stopped using React’s setState on all my new React components. Don’t get me wrong, I didn’t stop having local component state, I just stopped using React to manage it. And it’s been delightful!*

https://medium.com/@mweststrate/3-reasons-why-i-stopped-using-react-setstate-ab73fc67a42e

> **TL;DR** `React.setState` can be misleading since it doesn't necessarily assign the new state immediately; it could simply schedule a state change in the near future. It's important to note that `React.setState` is asynchronous, which means that it's easy to fall into a few pitfalls. Firstly, when trying to access state right after calling `React.setState` won't necessarily get you the updated value since this is an asynchronous function. Secondly, when running calculations that are based off of previous state, it's a good idea to pass a function through `React.setState` in order to execute that operation once it's scheduled/ready to run (other state changes might have occured betweeen scheduling and execution.
