# HTML

## CHAPTER 1

**_HTML_ : HyperText Markup Language.**

>In the browser window you can see a web page that features exactly the same content as the Word document you met on the page 18. To describe the structure of a web page, we add code to the words we want to appear on the page.

>The HTML code (in blue) is made up of characters that live inside angled brackets — these are called HTML **_elements_**.

>Elements are usually made up of two tags: an opening tag and a closing tag and tags act like containers. They tell you something about the information that lies between their opening and closing tags.

>Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.

>The attribute name indicates what kind of extra information you are supplying about the element's content. It should be written in lowercase.

>The value is the information or setting for the attribute. It should be placed in double quotes. Different attributes can have different values.

**Some major tags:**

tag | definition
--------|--------
| \<body\> | You met the <body> element in the first example we created. Everything inside this element is shown inside the main browser window. |
| \<head\> | Before the <body> element you will often see a <head> element. This contains information about the page (rather than information that is shown within the main part of the browser window that is highlighted in blue on the opposite page). You will usually find a <title> element inside the <head> element. |
| <title> | The contents of the <title> element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that page (if your browser uses tabs to allow you to view multiple pages at the same time). |

To create your first web page You might also like to download a free editor called Notepad++ from notepad-plus-plus.org. After that start making your structure on HTML.

>HTML pages are text documents.
>HTML uses tags (characters that sit inside angled brackets) to give the information they surround special meaning.
>Tags are often referred to as elements.
>Tags usually come in pairs. The opening tag denotes the start of a piece of content; the closing tag denotes the end.
>Opening tags can carry attributes, which tell us more about the content of that element.
>Attributes require a name and a value.
>To learn HTML you need to know what tags are available for you to use, what they do, and where they can go.

## CHAPTER 8

>DOCTYPES tell browsers which version of HTML you are using.
>You can add comments to your code between the <!-- and --> markers.
>The id and class attributes allow you to identify particular elements.
>The <div> and <span> elements allow you to group block-level and inline elements together.
><iframes> cut windows into your web pages through which other pages can be displayed.
>The <meta> tag allows you to supply all kinds of information about your web page.
>Escape characters are used to include special characters in your pages such as <, >, and ©

## CHAPTER 17

>The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.
>The new elements provide clearer code (compared with using multiple <div> elements).
>Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.
>To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed, which is available free from Google


## CHAPTER 18

>It is important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return.
>Site maps allow you to plan the structure of a site.
>Wireframes allow you to organize the information that will need to go on each page.
>Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.
>You can differentiate between pieces of information using size, color, and style.
>You can use grouping and similarity to help simplify the information you present.

# JavaScript

## Script Definition

**_script:_ is a series of instructions that a computer can follow to achieve a goal.**

>To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.

Start with the big picture of what you want to achieve, and break that down into smaller steps:
1 . DEFINE THE GOAL.
2 . DESIGN THE FLOW CHART.
3 . DESIGN THE SCRIPT.
4 . CODE EACH STEP.

>Vocabulary: The words that computers understand.

>Syntax: How you put those words together to create instructions computers can follow.

* Each time the script runs, it might only use a subset of all the instructions.
* Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically.
* To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help).

## How do computers fit in with the world around them ?

* computers create models of the world using data.
* The models use objects to represent physical things. Objects can have: properties that tell us about the object and methods that perform task using the propeties of object and events which are triggered when a user interacts with the computer.
* prorammers can write code to say "when event this occurs then run that code".
* Web browsers use HTML markup to create a model of the web page. Each element creates its own node (which is a kind of object).
* To make web pages interactive, you write code that uses the browser model of the web page.

## Write A Script For A Web Page

* It is the best to keep JavaScript code in its own JavaScript file. JavaScript files are a text files (like HTML page andCSS style sheets), but they have .js extention.
* The HTML <script> element is used in HTML pages to tell the browser to load the JavaScript file (rather like the <link> element can used to load a CSS file).
* If you view the source code of the page in the browser, the Java Script will not have changed the HTM L, because the script works with the model of the web page that the browser has created. 

