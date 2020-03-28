# Read:01 Summary
## Shay Howe’s intro to RWD (Summary)
> RWD : refers to Responsive Web Design
* The growth of mobile Internet usage is also far out pacing that of general Internet usage growth .

***With the growth in mobile Internet usage comes the question of how to build websites suitable for all users ??? .***

* The industry response to this question has become responsive web design, also known as RWD.
> Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop.
* Responsive generally means to react quickly and positively to any change, while adaptive means to be easily modified for a new purpose or situation, such as change. 
* With responsive design websites continually and fluidly change based on different factors, such as viewport width, while adaptive websites are built to a group of preset factors
* Mobile websites can be extremely light but they do come with the dependencies of a new code base and browser sniffing, all of which can become an obstacle for both developers and users.

***Responsive web design is broken down into three main components, including flexible layouts, media queries, and flexible media.***

> The formula is based around taking the target width of an element and dividing it by the width of it’s parent element. The result is the relative width of the target element.

> target ÷ context = result

* Flexible Grid : we can take all of the fixed units of length and turn them into relative units. 
* Taking the flexible layout concept, and formula, and reapplying it to all parts of a grid will create a completely dynamic website, scaling to every viewport size
* The flexible layout approach alone isn’t enough .Specifically, when the layout gets too small, or too large, text may become illegible and the layout may begin to break. 
* In this event, media queries can be used to help build a better experience.
* Media Queries : provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example. Being able to apply uniquely targeted styles opens up a world of opportunity and leverage to responsive web design.
* There are a couple different ways to use media queries, using the `@media` rule inside of an existing style sheet, importing a new style sheet using the `@import` rule, or by linking to a separate style sheet from within the HTML document.
* Logical operators in media queries help build powerful expressions. There are three different logical operators available for use within media queries, including `and`, `not`, and `only`.
* Knowing the media query syntax and how logical operators work is a great introduction to media queries but the true work comes with media features. Media features identify what attributes or properties will be targeted within the media query expression.
* One popular technique with using media queries is called `mobile first`. The `mobile first` approach includes using styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows.
* Using the `viewport` meta tag with either the `height` or `width` values will define the height or width of the viewport respectively.
* Viewport Scale : To control how a website is scaled on a mobile device, and how users can continue to scale a website.
* Flexible Media : The final, equally important aspect to responsive web design involves flexible media. As viewports begin to change size media doesn’t always follow suit. Images, videos, and other media types need to be scalable, changing their size as the size of the viewport changes.

## All About Floats (summary)
> Float: is a CSS positioning property so that images may be set into the page such that text wraps around them as needed.

***There are four valid values for the `float` property.*** ` Left` and `Right` float elements those directions respectively.`None` (the default) ensures the element will not float and `Inherit` which will assume the float value from that elements parent element.

> floats can be used to create entire web layouts.

* Float's sister property is `clear`. An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float.
* `Clear` ***has four valid values as well.*** `Both` is most commonly used, which clears floats coming from either direction. `Left ` and `Right` can be used to only clear the float from one direction respectively.` None` is the default, which is typically unnecessary unless removing a clear value from a cascade. `Inherit` would be the fifth, but is strangely not supported in Internet Explorer. Clearing only the left or right float, while less commonly seen in the wild, definitely has its uses.

## Don’t Overthink It Grids (summary)

> The vast majority of websites out there use a grid.

> If a more complex layout presents itself, people often reach for a grid framework.

* A block level element is as wide as the parent it's inside `(width: auto;)`.
* The hardest part about grids is `gutters`. So far we've made our grid flexible by using percentages for widths. We could make the math all complicated and use percentages for gutters as well.

## CSS Floats Explained By Riding An Escalator (summary)
* Your `<div>` is almost perfect. You decide to introduce some floats to fix the relationship between a few elements.
* There is a left flow and a right flow, and the elements that are not floated can easily fill the space that is not taken by the floated elements.
* the `float` property also gives an indication of an element’s relationship to surrounding elements.
* `Clear` :  allows elements to specify where they should align in comparison to the floated elements.
* One of the most frequent uses of the clear property is ` “clear:both” `. This allows you to reset the flow of elements, as opposed to continuing to maintain a right, left and normal flow.

## SMACSS Official Documentation (summary)
> SMACSS refers to scalable and modular architecture for css

> SMACSS is becoming one of the most useful contributions to front-end discussions in years

***It is a flexible guide for developing sites*** 

* SMACSS is more style guide than rigid framework. There is no library within here for you to download or install. There is no git repository for you to clone. SMACSS is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process. It is an attempt to document a consistent approach to site development when using CSS.


