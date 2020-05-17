# Domain Modeling

Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

Here's some tips to follow when building your own domain models.

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
1. Model its attributes with a constructor function that defines and initializes properties.
1. Model its behaviors with small methods that focus on doing one job well.
1. Create instances using the `new` keyword followed by a call to a constructor function.
1. Store the newly created object in a variable so you can access its properties and methods from **outside**.
1. Use the `this` variable within methods so you can access the object's properties and methods from **inside**.

# HTML

## Chapter 6 “Tables”

* The `<table>` element is used to add tables to a web
page.

* A table is drawn out row by row. Each row is created
with the `<tr>` element.

* Inside each row there are a number of cells
represented by the `<td>` element (or `<th>` if it is a
header).

* You can make cells of a table span more than one row
For long tables you can split the table into a `<thead>`,
`<tbody>`, and `<tfoot>`.

![tab](https://vertex-academy.com/tutorials/wp-content/uploads/2016/08/table.png)

# JavaScript

## Chapter 3 “Functions, Methods, and Objects”

* Functions allow you to group a set of related
statements together that represent a single task.

* Functions can take parameters (informatiorJ required
to do their job) and may return a value.

* An object is a series of variables and functions that
represent something from the world around you.

* In an object, variables are known as properties of the
object; functions are known as methods of the object.

* Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window.

* JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.

* Arrays and objects can be used to create complex data
sets (and both can contain the other).