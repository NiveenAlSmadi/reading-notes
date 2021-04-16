# What is the hardest thing about writing code?
- is learning the problem domain.
# Why problem domains are hard?
- is because we  can’t really see what we are trying to build very clearly. 
- also we often don't have a complete information about the problem domain, so we don’t even have the information we need to understand it.
## Remember : Programming is easy if you understand the problem domain.
## What can you do about it?
If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

- Make the problem domain easier
- Get better at understanding the problem domain


# WHAT IS AN OBJECT?
- Object : group set of variables and functions to create a model
of a something you would recognize from the real world.


## In objects :
1. VARIABLES BECOME KNOWN AS PROPERTIES : Properties tell us about the object /can be a string, number, Boolean, array, or
even another object.
2. FUNCTIONS BECOME KNOWN AS METHODS: Methods represent tasks that are associated with
the object./The value of a method is always a function

### In an object, the name is called a key.
- An object cannot have two keys with the same name . 
- Objects consist of a set of name/value pairs (but the names are referred to as keys).
# How i can creat objects?
using :
-  literal notation : the easiest and most popular way .


![img](https://image.slidesharecdn.com/criawt-les5-oojavascript-100318150455-phpapp02/95/oo-javascript-4-728.jpg?cb=1268924711)

## How i can access the object ?
- we can access the properties or methods of an object 
1. using dot notation 


![img](https://tse4.mm.bing.net/th?id=OIP.L-ypkYIIy-Vh9yN0B49FwwAAAA&pid=Api&P=0&w=421&h=166)



2. using square brackets (for propreties only )


# What is the DOM (Document Object Model)??
- specifies how browsers should create a model of an HTML
page and how JavaScript can access and update the contents of a web page while it is in the browser window .


- The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules.
It is implemented by all major browser makers, and covers two primary areas

- THE DOM TREE IS A MODEL OF A WEB PAGE 

- Each node is an object with methods and properties.
Scripts access and update this DOM tree (not the source HTML file).
Any changes made to the DOM tree are reflected in the browser .



![img](https://tse1.mm.bing.net/th?id=OIP.0bAEHftoYBWdHp2erpc8xgHaF-&pid=Api&P=0&w=227&h=184)


## ACCESS THE ELEMENTS 
1. three common ways to select an individual element :
- get El ement Byld ()
- querySe 1 ector ()
- select individual elements by traversing from one element to another within the DOM tree (see third column).

2. three common ways to select multiple elements "
-getElementsByClassName() 
- getElementsByTagName()
- querySelectorAll() 

3. move from one element node to a related element node:
- parentNode
- previousSibl ing / nextSibl ing
- firstChild / lastChild


# cashing dom queries 


![img](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/Js-Dom-Tree.png)


# soThe browser represents the page using a DOM tree.
- DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes.
- You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax.
Whenever a DOM query can return more than one
node, it will always return a Nadel i st.

- child elements that are siblings of each other.
In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).

- Browsers offer tools for viewing the DOM tree .





