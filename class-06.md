 # Article
Understanding the problem doiman is difficult, but taking the time to understand how something should work and why is important to understanding the problem you're working on.

 ## JS Chapter 3: “Object Literals” (pp.100-105)
 Objects group together a set of variables and functions to create a model of something.  Variables and functions take on new names in objects.

 In an onject, variables become known as properties.  Properties tell us about the object.

 In an onbject, functions become known as methods.  Methods represent tasks that are associated with an object.

 Properties and methods have a name and a value.  The name is called a key.  The value of a method is called a function.

 Literal notation is the easiest and most popular way to create objects.

 YOu access the properties and methods of an object using dot notation.

### Chapter 5: “Document Object Model” (pp.183-242)

The DOM specifies how browsers create a model of an HTML page and how JavaScript can access and update the contents while it's in the browser window.  

It's called the Document Objact Model becaue the model (the DOM tree) is made up of objects and each object represents a different part of the page.

The DOM is also called an API )Application Programming Interface) and lets programs and scripts talk to eachother.  

A DOM Tree contains four types of nodes:
1. Document node- EvEry element, attribute, and piece of text is represented by its own DOM node.
2. Elements nodes- To access the DOM tree, you start by looking for HTML elements.
3. Attribute nodes- they are part of the element.  Specific JavaScript methods and properties can read or change that element's atributes.  
4. Text nodes- Once you haev accessed an element node, you can then reach the text within that element.  Text nodes cannot have children.  

Accessing elements can be done with: (p.188)
1. getElementById() -individual element node
2. querySelector() -individual element node
3. geElementsByClassName() -select multiple elements
4. getElementsByTagName() -select multiple elements
5. querySelectorAll() -select multiple elements
6. parentNode -traversing between element nodes 
7. previousSibling / nextSibling -traversing between element nodes 
8. firstChild / lastChild -traversing between element nodes 

Working with those elements: (p.189)
1. nodeValue -access / update text nodes
2. innerHTML -work with HTML content
3. textContent -work with HTML content
4. createElement() -work with HTML content
5. createTextNode() -work with HTML content
6. appendChild() / removeChild() -work with HTML content
7. className / id -access or update attribute values
8. hasAttribute() -access or update attribute values
9. getAttribute() -access or update attribute values
10. setAttribute() -access or update attribute values
11. removeAttribute() -access or update attribute values

Methods that find elements in the DOM tree are called DOM queries.  Store the result of queries you'll use more than once in variables (known as caching).

Nodelists are DOM queries that return more than one element, given an index number like arrays but a type of object called a collection.  You can select elements from node lists using the item() methos or array syntax.  Array syntax is preferred.  If you repetedly use the NodeList, store it in a variable.

You can select elements using the class attributes, tag name and/or CSS selectors.  You can also loop through a nodelist.

Most browsers add a text node wherever they come across whitespace between elements.

How to get / update content:
Adding or removing HTML content can be approached with the innerHTML property or DOM manipultaion menthods.


