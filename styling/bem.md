## BEM

#### BEM - Block Element Modifier

*On smaller brochure sites, how you organize your styles isn’t usually a big concern. You get in there, write some CSS, or maybe even some SASS. You compile it all into a single stylesheet with SASS’s production settings, and then you aggregate it to get all the stylesheets from modules into a nice tidy package.*

http://getbem.com/introduction/

> **TL;DR**: BEM allows you to better organize your styling by defining a naming convention for your classes, which sets purpose to your class assignments. It also imposes a nesting structure, which also works great for limiting styling overflow between elements.

#### ‘Why BEM?’ in a nutshell

**The two base concepts of CSS? Inheritance and specificity.**

https://blog.decaf.de/2015/06/24/why-bem-in-a-nutshell/

> **TL;DR**: BEM tries to solve two of CSS's main issues: inheritence and specificity. By scoping blocks to a certain namespace (BEM block name), you are scoping down your styles to only affect the one block element and below. In terms of specificity, keeping these blocks as small as possible reduces the specificity required to override styles within these blocks.
