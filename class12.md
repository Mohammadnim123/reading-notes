# Chart.js API

**_Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create._**

1. Setting up : The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in.
1. Drawing a line chart : To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart
1. Drawing a bar chart :he syntax for the bar chart is very similar to the line chart we’ve already added.
1. Drawing a pie chart

# Basic usage 

The `<canvas>` element differs from an `<img>` tag in that, like for `<video>`, `<audio>`, or `<picture>` elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.

Providing fallback content is very straightforward: just insert the alternate content inside the `<canvas>` element. Browsers that don't support `<canvas>` will ignore the container and render the fallback content inside it. Browsers that do support `<canvas>` will ignore the content inside the container, and just render the canvas normally.

As a consequence of the way fallback is provided, unlike the `<img>` element, the `<canvas>` element requires the closing tag `</canvas>`. If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.

# Drawing shapes with canvas

**We can use canvas to drawing alot of things such as:**

1. The grid.
1. Drawing rectangles.
1. Drawing paths.
1. Drawing a triangle.
1. Moving the pen.
1. Lines.
1. Arcs.
1. Bezier and quadratic curves.
1. Cubic Bezier curves.

# Applying styles and colors

**the canvas options we have at our disposal to make our drawings a little more attractive. You will learn how to add different colors, line styles, gradients, patterns and shadows to your drawings.**

1. Colors : fillStyle , strokeStyle
1. Transparency : globalAlpha , using rgba()
1. Line styles : lineWidth , lineCap , lineJoin , Using line dashes
1. miterLimit property
1. Gradients : createLinearGradient , createRadialGradient 
1. Patterns : createPattern 
1. Shadows
1. Canvas fill rules

# Drawing text

The canvas rendering context provides two methods to render text:

`fillText(text, x, y [, maxWidth])`
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

`strokeText(text, x, y [, maxWidth])`
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

1. Styling text  
1. Advanced text measurements : you need to obtain more details about the text.
1. Gecko-specific notes


