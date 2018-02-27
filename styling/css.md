## CSS

#### EM vs REM vs PX – Why you shouldn't "just use pixels"

*We, like many others, were ready to ditch REMs and return to the beloved pixel. We lost track of why we adopted the use of REMs in the first place. TheMigrate problem doesn’t just revolve around font-sizes - it’s also about accessibility.*

http://engageinteractive.co.uk/blog/em-vs-rem-vs-px

> **TL;DR**: REMs are a relative unit, similar to EMs, that measure its size relative to the `HTML` element. This means that you allow for better accessibility by being able to grow all text by a relative size, such as EMs, while not experiencing nested hell by need to set your size relative to the parent element.

#### Pointer-Events

*The `pointer-events` property allows for control over how HTML elements respond to mouse/touch events – including CSS hover/active states, click/tap events in Javascript, and whether or not the cursor is visible.*

https://css-tricks.com/almanac/properties/p/pointer-events/

> **TL;DR**: `pointer-events` allows to control user intentions through and around a given HTML element. By setting `pointer-events` to `none`, the browser will handler user interactions on the next available element below the given element, while Javascript events will behave the same way.

#### A Complete Guide to Grid

*CSS Grid Layout is the most powerful layout system available in CSS. It is a 2-dimensional system, meaning it can handle both columns and rows, unlike flexbox which is largely a 1-dimensional system. You work with Grid Layout by applying CSS rules both to a parent element (which becomes the Grid Container) and to that elements children (which become Grid Items).*

https://css-tricks.com/snippets/css/complete-guide-grid/

> **TL;DR**: CSS Grid systems helps fill in the gap that is left by Flexbox, when trying to build 2-dimensional grid systems (in both rows and columns). It allows you to build this system fully in CSS, so unlike buildling grids through `table`s or `flexbox`, your structure isn't being defined in HTML.

#### An Introduction to the `fr` CSS unit

*With all the excitement around CSS Grid, I haven't seen as much talk about the new fr CSS length unit. And now that browser support is rapidly improving for this feature, I think this is the time to explore how it can be used in conjunction with our fancy new layout engine because there are a number of benefits when using it; more legible and maintainable code being the primary reasons for making the switch.*

https://css-tricks.com/introduction-fr-css-unit/

> **TL;DR**: The `fr` unit allows you to create `flex fraction`s, which essentially takes the remaining space allows to given components and splits it based on the accumulated `fr`s found in all its siblings. Given that this can be mixed with other more static units of measurements in CSS, this allows you to create highly dynamic and flexible systems, such as a fluid column system that takes the remaining space around a fixed-size sidebar.

#### CSS Grid Layout: The Fr Unit

*With CSS Grid Layout, we get a new flexible unit: the Fr unit. Fr is a fractional unit and 1fr is for 1 part of the available space.*

https://alligator.io/css/css-grid-layout-fr-unit/

> **TL;DR**: A few good examples of how `fr` units can be used with `css grids` in order to affect the dimensions of grid items, alongside other units, such as percentages and pixels.

#### [Video - 2:59] Grid by Example: the fr unit

https://www.youtube.com/watch?v=N731aTpo8TI

> **TL;DR**: A few examples of working through certain scenarios with `fr` units.

#### What No One Told You About Z-Index

*The problem with z-index is that very few people understand how it really works. It’s not complicated, but it if you’ve never taken the time to read its specification, there are almost certainly crucial aspects that you’re completely unaware of.*

https://philipwalton.com/articles/what-no-one-told-you-about-z-index/

> **TL;DR** It's important to conceptualize z-index values as through their respective stack context, in order to avoid the traps of layering elements properly. Certain CSS styles reset this stacking order, so it's important to be aware of those.

#### CSS stacking contexts: What they are and how they work

*Stacking contexts are an aspect of CSS that trips up most developers. Sure, I understood that z-index required position to be something besides static. But that's about as far as my comprehension went.*

https://tiffanybbrown.com/2015/09/css-stacking-contexts-wtf/index.html

> **TL;DR** Basic summary of stacking context in z-index layering. Mentions the rules of layering, and powers of priority in specifying certain css properties, such as `position` and `z-index`.

#### Stunning hover effects with CSS variables

*I recently got inspired by the playful hover animation on the Grover website. Moving your mouse over the subscribe-button reveals a colorful gradient that follows your cursor as it moves. The idea is simple, but the result is a button that stands out from the reset and waits to be clicked.*

https://blog.prototypr.io/stunning-hover-effects-with-css-variables-f855e7b95330

> **TL;DR** By leveraging the power of CSS variables, you can write minial Javascript code that will simply update those variables on the fly, allowing your CSS to do all the heavy lifting and dynamically render out based on those updated variables.
