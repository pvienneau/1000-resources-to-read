## Events

#### SyntheticEvent

*Your event handlers will be passed instances of SyntheticEvent, a cross-browser wrapper around the browser's native event. It has the same interface as the browser's native event, including stopPropagation() and preventDefault(), except the events work identically across all browsers.*

https://facebook.github.io/react/docs/events.html

> **TL;DR**: React wraps ever DOM events into a Synthetic event, which allows for full browser compatibility. Its intent is to still behave like any DOM event, and so you still have access to the common methods and data. One thing to note is that the synthetic events cannot be access asynchronously as they are pooled. If you need to access an event asynchronously, you should use `e.persist()`.

#### Handling Events

https://facebook.github.io/react/docs/handling-events.html

> **TL;DR**: Handling events on React elemnents is very similar to handing events on DOM elements. A few key difference is that React events are named camelCase instead of lowercase (ie on DOM or React elements) and in React you pass a function reference as the event handler, as opposed to a string referencing a function.
