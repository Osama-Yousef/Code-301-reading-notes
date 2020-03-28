# Read:01 Summary
## Shay Howe’s intro to RWD Summary
* RWD : refers to Responsive Web Design
* The growth of mobile Internet usage is also far out pacing that of general Internet usage growth.
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


