# HTML list 
HTML provide 3 difreent kinds of lists wich is:

- Ordered lists : you can use the tag <ol> to create one and use <li> tag for each item in the list it should looks like:
cap

- Unordered lists : as in orderd list you can use the tag <ul> to create one and also use <li> tag for each item in the list it should looks like:
cap

![list](https://tse2.mm.bing.net/th?id=OIP.dU9pBAQQCnvoQjxXuplAmwHaEK&pid=Api&P=0&w=317&h=179)



- Definition lists : use the tag <dl> to create one and use <dt> tag to create the defintion term and use <dd> tag for each content defention it should looks like: cap
you can create Nested lists by adding second list inside an <li> element to create a sublist or nested list




![list](https://tse1.mm.bing.net/th?id=OIP.EzVHNqOx_qerklaYbT14HwHaFj&pid=Api&P=0&w=211&h=159)





- Nested Lists: Browsers display nested lists
indented further than the parent
list. In nested unordered lists,
the browser will usually change
the style of the bullet point too.



![list](https://tse2.mm.bing.net/th?id=OIP.ivkEg8lpbLuJEjpOpGmZmAAAAA&pid=Api&P=0&w=191&h=181)


## Review : 
There are three types of HTML lists: 
 - ordered, unordered, and definition.
 - Ordered lists use numbers.
 - Unordered lists use bullets.
 - Definition lists are used to define terminology.
 - Lists can be nested inside one another

# HTML boxes 
 css treat every elemnt in HTML as it lives in own box, so you can set several properties that affect the appearance of these boxes lets talk littel bit about it :
 ## Dimensions
- width, height:
By default a box is sized just big
enough to hold its contents. To
set your own dimensions for a
box you can use the height and
width properties.
- Limiting Width / min-width, max-width:
  can use min-width property specifies the smallest size a box can be displayed at when the browser window is narrow and also max-width property indicates the maximum width a box can stretch to when the browser window 

- Limiting Hight :
as Limiting Width you can use min-hight property specifies the smallest hight of the box, can be displayed at when the browser window is narrow and also max-hight property indicates the maximum hight a box can stretch to when the browser window is wide . 

## Overflowing Content
overflow:
The overflow property tells the
browser what to do if the content
contained within a box is larger
than the box itself. It can have
one of two values:
- hidden
This property simply hides any
extra content that does not fit in
the box.
- scroll
This property adds a scrollbar to
the box so that users can scroll
to see the missing content.


## Border, Margin & Padding



![bmp](https://tse2.mm.bing.net/th?id=OIP.riH3iHYxN6UKqTZGGU6jGgHaEK&pid=Api&P=0&w=315&h=178)


## Border Style



![bs](http://www.c-sharpcorner.com/UploadFile/eda428/css-border-property-part-2-in-html/Images/border-style-in-HTML.png)


- Inline/Block :
display witch allows you to turn an inline element into a block-level element, and uses values :

inline :witch causes a block-level element to act like an inline element
block :witch causes an inline element to act like a block-level element
inline-block :witch causes a block-level element to flow like an inline element, while retaining other features of a block-level element
none :witch hides an element from the page

- Hiding Boxes :
visibility use this property with values : hidden & visible

# Box Shadows :



![BOX](https://tse3.mm.bing.net/th?id=OIP.hTXM4HjsJHKmHxcTk1tHiAHaE9&pid=Api&P=0&w=241&h=162)



- Horizontal offset :Negative values position theshadow to the left of the box
Vertical offset :Negative values position the shadow to the top of the box
Blur distance :If omitted, the shadow is a solid line like a border
Spread of shadow :If used, a positive value will cause the shadow to expand in all directions, and a negative value will make it contract it .

- Rounded Corners :
border-radius use this proparity to make the corners mre rounded, also you can specify witch corner to rounded by useing: border-top-right-radius, border-bottom-right-radius, border-bottom-left-radius, border-top-left-radius also you can use shorthand way with it like :border-radius: 5px, 10px, 5px, 10px; you can also create Elliptical Shpes with this proparty .

# so CSS treats each HTMLE BY :

1. You can use CSS to control the dimensions of a box.
2. You can also control the borders, margin and padding
for each box with CSS.
3. It is possible to hide elements using the display and
visibility properties.
4. Block-level boxes can be made into inline boxes, and
inline boxes made into block-level boxes.


# Decisions and Loops in js :


![js](https://tse4.mm.bing.net/th?id=OIP.caol4Mt-V57ZGtR0vvXTawHaD8&pid=Api&P=0&w=302&h=162)


## Loops :

its another kind of cheak conditions, if it returns true the code after will run, then it will recheak again if it is still return true and keep cheak and run until returns flse and there is 3 typs of loops: 

1. FOR : it is usually a counter which is used to tell how many times loop should run



![for](https://tse3.mm.bing.net/th?id=OIP.-yw9r4SmzlREGmnr1XqosAHaEF&pid=Api&P=0&w=276&h=153)


2. WHILE : you can use while if you dont know how many times the code will keep loop, it will keep loop until the condition is true 


![while](https://tse1.mm.bing.net/th?id=OIP.1RgzgAsI7Cje5SgQuUs7jgHaCb&pid=Api&P=0&w=512&h=169)


3. DO WHILE : its same of ehile loop but in difference: it will always run thr statments inside the curly braces at least once, even if the condation evaluates to false..



![do](https://i2.wp.com/simplesnippets.tech/wp-content/uploads/2018/10/dowhile-loop-in-javascript-featured-image.jpg?resize=750%2C350&ssl=1)

