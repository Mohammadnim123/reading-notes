# HTML

## Chapter 7 “Forms” 

**We can use HTML to make forms like this :**

![form](https://4.bp.blogspot.com/-wQbB1UGof_s/XBDQOiglarI/AAAAAAAACYA/NPi55ILw33MXI-k_m0_E3styMTMHesfPACLcBGAs/s640/HTML%2BForm.PNG)


* Whenever you want to collect information from
visitors you will need a form, which lives inside a
`<form>` element.

* Information from a form is sent in name/value pairs.

* Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.

* HTML5 introduces new form elements which make it
easier for visitors to fill in forms.

**We can use these tags to build our form:**

![tags](https://slideplayer.com/slide/4205843/14/images/38/HTML+Forms+and+Input+HTML+Form+Tags+++Tag+Description.jpg)

## Chapter 14 “Lists, Tables & Forms”

**in this chapter we will make style for Lists, Tables & Forms to be like this and more beautiful:**

![formc](https://1.bp.blogspot.com/-EhJnq1-r_ws/Xr5bfGzv_iI/AAAAAAAAAac/SgyS8xnl-UImRQcm8rolVrQIVQaXfqRXgCLcBGAsYHQ/s1600/Registration%2Bform.png)

>The list-style-type property
allows you to control the shape
or style of a bullet point (also
known as a marker).

>You can specify an image to act
as a bullet point using the
list-style-image property.

* In addition to the CSS properties covered in other
chapters which work with the contents of all elements,
there are several others that are specifically used to
control the appearance of lists, tables, and forms.

* List markers can be given different appearances
using the list-style-type and list-style image
properties.

* Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.

* Forms are easier to use if the form controls are
vertically aligned using CSS.

* Forms benefit from styles that make them feel more
interactive.

# JavaScript

## Chapter 6: “Events”

**HTML events are "things" that happen to HTML elements.When JavaScript is used in HTML pages, JavaScript can "react" on these events.**

_Here are some examples of HTML events:_

1. An HTML web page has finished loading
1. An HTML input field was changed
1. An HTML button was clicked.

Often, when events happen, you may want to do something.JavaScript lets you execute code when events are detected.HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.

With single quotes:

`<element event='some JavaScript'>`
With double quotes:

`<element event="some JavaScript">`

**JavaScript code is often several lines long. It is more common to see event attributes calling functions**

**Common HTML Events**

Event |	Description
--------|--------
onchange  |	An HTML element has been changed
onclick	| The user clicks an HTML element 
onmouseover | The user moves the mouse over an HTML element
onmouseout | The user moves the mouse away from an HTML element
onkeydown |	The user pushes a keyboard key onload	The browser has finished loading the page

**What can JavaScript Do?**

_Event handlers can be used to handle, and verify, user input, user actions, and browser actions:_

* Things that should be done every time a page loads

* Things that should be done when the page is closed

* Action that should be performed when a user clicks a button

* Content that should be verified when a user inputs data

* And more ...

_Many different methods can be used to let JavaScript work with events:_

* HTML event attributes can execute JavaScript code directly

* HTML event attributes can call JavaScript functions

* You can assign your own event handler functions to HTML elements

* You can prevent events from being sent or being handled

* And more ...

>* Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).

>* Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.

>* When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user.

>* You can use event delegation to monitor for events
that happen on all of the children of an element.

>* The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events.

