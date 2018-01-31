## SCSS

#### How to Use Sass Mixins

*Sass is incredible. Whether using it as Sass or SCSS, it improves productivity and makes complex CSS tasks easy. Sass is easy to debug and lets us do more with CSS.*

https://scotch.io/tutorials/how-to-use-sass-mixins

> **TL;DR**: Sass is a powerful tool to complement your css styling, allowing you to reduce your code complexity through code re-use, both on styles and style selector rules.

#### Should you use a Sass mixin or @extend?

*If you want to DRY your CSS, the easiest way is to start using a pre-processor like Sass. Specially in the beginning though, you need to regularly look at what your Sass compiles to. By using mixins for instance, you can seriously scale back the amount of code you need to write. But if you don’t know how things compile, you’ll end up with DRY Sass and bloated CSS. Since that’s what gets send to the user agent eventually, you should try to prevent that.*

https://roy.io/should-you-use-a-sass-mixin-or-extend/

> **TL;DR**: Very concise article comparing Sass mixin and @extend. The bottom line is that the @extend groups your selectors together in order to reduce the amount of style duplication that is produced in your CSS. However, @extend will only take in static styles; if dynamic styles are needed, best fall back to mixins.
