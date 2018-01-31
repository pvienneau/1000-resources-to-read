## React

#### How I built a product in 5 weeks using Meteor and React

*Or how Ruutly came to life*

https://blog.416serg.me/how-i-built-a-product-in-5-weeks-using-meteor-and-react-ca2cfad35dcc#.jb37d55b3

> **TL;DR** Meteor works very well with React when developing native apps.

#### Reconciliation

*React provides a declarative API so that you don't have to worry about exactly what changes on every update. This makes writing applications a lot easier, but it might not be obvious how this is implemented within React.*

https://facebook.github.io/react/docs/reconciliation.html

> **TL;DR** React's reconciliation algorithm allows to more efficiently update the DOM based on the new React trees. Making a few assumptions, its algorithms chooses which parts of the new React tree has changed compared to the previous tree, so it can reduce the number of unecessary manipulations on the DOM.
