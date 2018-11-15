# Practice-HTML-CSS

#### _All the the information below, as well as practice exercise and projects (code) shared in this repository were extracted from_ [Code Academy](https://www.codecademy.com/)

## The Box Model

_The four properties of the box model: height and width, padding, borders, and margins. Understanding the box model is an important step towards learning more advanced HTML and CSS topics._ 

1. The box model comprises a set of properties used to create space around and between HTML elements.
2. The height and width of a content area can be set in pixels or percentage.
3. Borders surround the content area and padding of an element. The color, style, and thickness of a border can be set with CSS properties.
4. Padding is the space between the content area and the border. It can be set in pixels or percent.
5. Margin is the amount of spacing outside of an element's border.
6. Horizontal margins add, so the total space between the borders of adjacent elements is equal to the sum of the right margin of one element and the left margin of the adjacent element.
7. Vertical margins collapse, so the space between vertically adjacent elements is equal to the larger margin.
8. **_margin: 0 auto_** horizontally centers an element inside of its parent content area, if it has a width.
9. The **_overflow_** property can be set to **_display_**, **_hide_**, or **_scroll_**, and dictates how HTML will render content that overflows its parent's content area.
10. The **_visibility_** property can hide or show elements.


## Changing the Box Model

1. In the default box model, box dimensions are affected by border thickness and padding.
2. The **_box-sizing_** property controls the box model used by the browser.
3. The default value of the **_box-sizing_** property is **_content-box_**.
4. The value for the new box model is **_border-box_**.
5. The border-box model is not affected by border thickness or padding.

## Layout

_How to control the positioning of elements on a web page._

1.	The position property allows you to specify the position of an element in three different ways.
2.	When set to relative, an element's position is relative to its default position on the page.
3.	When set to absolute, an element's position is relative to its closest positioned parent element. It can be pinned to any part of the web page, but the element will still move with the rest of the document when the page is scrolled.
4.	When set to fixed, an element's position can be pinned to any part of the web page. The element will remain in view no matter what.
5.	The z-index of an element specifies how far back or how far forward an element appears on the page when it overlaps other elements.
6.	The display property allows you control how an element flows vertically and horizontally a document.
7.	inline elements take up as little space as possible, and they cannot have manually-adjusted width or height.
8.	block elements take up the width of their container and can have manually-adjusted heights.
9.	inline-block elements can have set widthand height, but they can also appear next to each other and do not take up their entire container width.
10.	The float property can move elements as far left or as far right as possible on a web page.
11.	You can clear an element's left or right side (or both) using the clear property.

## Color

_There are four ways to represent color in CSS:_

-	Named colors — there are 147 named colors, which you can review here.
- Hexadecimal or hex colors
  - Hexadecimal is a number system with has sixteen digits, 0 to 9 followed by "A" to "F".
  - Hex values always begin with # and specify values of red, blue and green using hexademical numbers such as #23F41A.
- RGB
  - RGB colors use the rgb() syntax with one value for red, one value for blue and one value for green.
  - RGB values range from 0 to 255 and look like this: rgb(7, 210, 50).
- HSL
  - HSL stands for hue (the color itself), saturation (the intensity of the color), and lightness (how light or dark a color is).
  - Hue ranges from 0 to 360 and saturation and lightness are both represented as percentages like this: hsl(200, 20%, 50%).
- You can add opacity to color in RGB and HSL by adding a fourth value, a, which is represented as a percentage.

## Typography

_Typography is an important aspect of the user experience._

1.	Typography is the art of arranging text on a page.
2.	Text can appear in any number of weights, with the font-weight property.
3.	Text can appear in italics with the font-styleproperty.
4.	The vertical spacing between lines of text can be modified with the line-height property.
5.	Serif fonts have extra details on the ends of each letter. Sans-Serif fonts do not.
6.	Fallback fonts are used when a certain font is not installed on a user's computer.
7.	Google Fonts provides free fonts that can be used in an HTML file with the <link> tag or the @font-face property.
8.	Local fonts can be added to a document with the @font-face property and the path to the font's source.
9.  The word-spacing property changes how far apart individual words are.
10.	The letter-spacing property changes how far apart individual letters are.
11.	The text-align property changes the horizontal alignment of text.
