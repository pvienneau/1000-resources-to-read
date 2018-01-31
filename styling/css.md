## CSS

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

#### CSS Grid Layout: The Fr Unit

*With CSS Grid Layout, we get a new flexible unit: the Fr unit. Fr is a fractional unit and 1fr is for 1 part of the available space.*

https://alligator.io/css/css-grid-layout-fr-unit/

> **TL;DR**: A few good examples of how `fr` units can be used with `css grids` in order to affect the dimensions of grid items, alongside other units, such as percentages and pixels.

#### [Video - 2:59] Grid by Example: the fr unit

https://www.youtube.com/watch?v=N731aTpo8TI

> **TL;DR**: A few examples of working through certain scenarios with `fr` units.