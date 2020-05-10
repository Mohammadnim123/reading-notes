# HTML
## CHAPTER 2 "TEXT"


>**_markup:_** tags to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.

* __Structural markup:__ the elements that you can use to
describe both headings and paragraphs.

* __Semantic markup:__ which provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on

This table show the markup:

the tag | definition
--------|--------
\<h1.......h6\> | \<h1\> is used for main headings \<h2\> is used for subheadings
\<p\> | To create a paragraph, surround the words that make up the paragraph with an opening \<p\> tag and closing \</p\> tag
\<br\> | the browser will automatically show each new paragraph or heading on a new line.
\<hr \> | To create a break between themes.
\<blockquote\> | The <blockquote> element is used for longer quotes that take up an entire paragraph.
\<q\> | used for shorter quotes that sit within a paragraph.
\<abbr\> | If you use an abbreviation or an acronym, then the \<abbr\> element can be used. A title attribute on the opening tag is used to specify the full term. 
\<ins\> | it can be used to show content that has been inserted into a document.
\<del\> | it can show text that has been deleted from it.

![logo](https://miro.medium.com/max/638/1*EjUlBjd1yQFFcOvo0VYLog.jpeg)

* HTML elements are used to describe the structure of the page such as headings, subheadings and paragraphs.

* They also provide semantic information (e.g. where emphasis should be placed, the definition of any acronyms used, when given text is a quotation).

## CHAPTER 2 "TEXT"

**_Selectors :_** indicate which
element the rule applies to.
The same rule can apply to
more than one element if you
separate the element names
with commas.

**_Declarations :_** indicate how
the elements referred to in
the selector should be styled.
Declarations are split into two
parts (a property and a value),
and are separated by a colon.

![CSS](https://catalin.red/dist/uploads/2009/12/css-structure-anatomy.png)

> * CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that
element should look.

> * Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).

> * Different types of selectors allow you to target your
rules at different elements.

> * Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.

> * CSS rules usually appear in a separate document,
although they may appear within an HTML page.

> \<link\> 
external-css.html HTML
The \<link\> element can be used
in an HTML document to tell the
browser where to find the CSS
file used to style the page. It is an
empty element (meaning it does
not need a closing tag), and it
lives inside the \<head\> element.
It should use three attributes:

> href :
This specifies the path to the
CSS file (which is often placed in
a folder called css or styles).

>type : 
This attribute specifies the type
of document being linked to. The
value should be text/css.

>rel :
This specifies the relationship
between the HTML page and
the file it is linked to. The value
should be stylesheet when
linking to a CSS file.

# JavaScript
## CHAPTER 2 "Basic JavaScript Instructions"

> * A script is made up of a series of statements. Each
statement is like a step in a recipe.

> * Scripts contain very precise instructions. For example,
you might specify that a value must be remembered
before creating a calculation using that value.

> * Variables are used to temporarily store pieces of
information used in the script.

> * Arrays are special types of variables that store more
than one piece of related information.

> * JavaScript distinguishes between numbers (0-9),
strings (text), and Boolean values (true or false).

> * Expressions evaluate into a single value.

> * Expressions rely on operators to calculate a value.

### OPERATORS:

**they allow programmers to create a single value from one or more values.**

>ASSIGNMENT OPERATORS : like color = 'beige';

>COMPARISON OPERATORS : like color = 'beige';

>ARITHMETIC OPERATORS : like area = 3 * 2;
![ar](https://1.bp.blogspot.com/-N4BTD_uvqPg/XJh7TKNaH3I/AAAAAAAACI4/X73EKI50S-QGxynBSiT5i3kWjJS0vbCIgCLcBGAs/s1600/Arithmetic%2Boperators.png)

>LOGICAL OPERATORS : like buy= (5 > 3) && (2 < 4);

>STRING OPERATORS : like greeting= 'Hi 1 + 'Mol ly';


## CHAPTER 4 “Decisions and Loops”

 EVALUATING CONDITION

> Equal to (==): compare two value if thay are same value.

>not Equal to (!=): compare two value if thay are not same value.

>STRICT Equal to (===): compare two da value if thay are same value and data type.

>STRICT NOT Equal to (!==): compare two da value if thay are not same value and data type.

>GREATER THAN (>): chick the number on the left greater than on  the right.

>LESS THAN (<): chick the number on the right less than on  the left.

>GREATER THAN OR EQUAL TO (>=): chick the number on the left greater than or equal on  the right.

>LESS THAN OR EQUAL TO (<=): chick the number on the right less than or equal on  the left.

![ff](https://i.ytimg.com/vi/wFB-ywsNPwg/maxresdefault.jpg)

### LOGIC OPRERATORS :

**There are three logical operators in JavaScript: || (OR), && (AND), ! (NOT) we can view it in the truth table.**

![tru](https://instrumentationtools.com/wp-content/uploads/2018/10/Logic-Gates-and-Truth-tables.png)

### LOOPS

Loops : commands can can execute a block of code a number of times and there are two type of it.

![loop](https://www.tutorialspoint.com/javascript/images/for_loop.jpg)

>for - loops through a block of code a number of times

>while - loops through a block of code while a specified condition is true

>do/while - also loops through a block of code while a specified condition is true

**This is the structure of the for loop :**
![for](https://www.sitesbay.com/cpp/images/control-statement/for-loop-steps.png)

>the for loop will stop if the condition give false.

**And this is the structure for While loop :**

![wh](https://media.geeksforgeeks.org/wp-content/uploads/20191118164726/While-Loop-GeeksforGeeks.jpg)

>This loop will continue to run
for as long as the condition in
the parentheses is true.



