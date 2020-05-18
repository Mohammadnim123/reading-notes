# Chapter 15 “Layout”

> **Building Blocks :**
CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.

> Block-level elements
start on a new line
Examples include:
\<h1\> \<p\> \<ul\> \<li\>.

> Inline elements
flow in between
surrounding text
Examples include:
\<img\> \<b\> \<i\>

> **Containing Elements:**
If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.

>**Controlling the Position of Elements :** CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.

>**Normal flow:**
Every block-level element
appears on a new line, causing
each item to appear lower down
the page than the previous one.

>**Relative Positioning:**
This moves an element from the
position it would be in normal
flow, shifting it to the top, right,
bottom, or left of where it
would have been placed.

>**Absolute positioning:**
This positions the element
in relation to its containing
element.

>To indicate where a box should be positioned, you may also need to use
box offset properties to tell the browser how far from the top or bottom
and left or right it should be placed. (You will meet these when we
introduce the positioning schemes on the following pages.)

>**Fixed Positioning:**
This is a form of absolute
positioning that positions
the element in relation to the
browser window, as opposed
to the containing element.

>**Floating Elements:**
Floating an element allows
you to take that element out
of normal flow and position
it to the far left or right of a
containing box.

>When you move
any element from
normal flow, boxes
can overlap. The
z-index property
allows you to control
which box appears
on top.

> * \<div\> elements are often used as containing elements
to group together sections of a page.

> * Browsers display pages in normal flow unless you
specify relative, absolute, or fixed positioning.

> * The float property moves content to the left or right
of the page and can be used to create multi-column
layouts. (Floated items require a defined width.)

> * Pages can be fixed width or liquid (stretchy) layouts.

> * Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).

> * Grids help create professional and flexible designs.

> * CSS Frameworks provide rules for common tasks.

> * You can include multiple CSS files in one page.

**This is an example about Wireframe :**

![gg](https://miro.medium.com/proxy/1*ia4V5qfk6Ki3iWIn-SmErw.png)