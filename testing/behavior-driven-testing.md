#Behavior-Driven Testing (BDD)

#### Assertion Styles

http://chaijs.com/guide/styles/#differences

> **TL;DR**: `expect` and `should` serve the same purpose, but function in different ways. The main different is that `expect` is initialized through individual assertions, while `should` extends `Object.prototype`, allowing you to assert directly on perperties and variables. The one functional drawback of using `should` is that you can't assert on undefined or nulled objects, since these values aren't extended by `should`.
