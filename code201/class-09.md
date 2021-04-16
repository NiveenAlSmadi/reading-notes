# Forms 
# what is the forms?
we use forms to get the informations from the user

-The best known form on the web is probably
the search box that sits right in the middle of
Google's homepage.

# Form Controls
There are several types of form controls that
you can use to collect information from visitors
to your site. 
1. ADDING TEXT :(Text input, Password input, Text area)
2. Making Choices :(Radio buttons, Checkboxes, Drop-down boxes)
3. Submitting Forms :(Submit buttons, Image buttons)
4. Uploading Files :(File upload)


# How Forms Work :

![img](https://img.webnots.com/2014/01/How-HTML-Form-Works.png)


## Form Structure : 
use `<form>` tag as parent for forms controls inside, and it takes `action` as attrbute and `method` (witch has one of two methods: 'get or post') and `id` att..

 1. Text Input :
witch uses `<input>` tag and have `type="text", name, maxlength, size` as attrbuts

 2. Password Input :
witch uses `<input>` tag and have `type="password", name, maxlength, size` as attrbuts

 3. Text Area :
witch uses `<textarea>` tag

4. Radio Button :
witch uses `<input>` tag and have `type="radio", name, value, checked` as attrbuts
 5. Checkbox :
witch uses `<input>` tag and have `type="checkbox", name, value, checked` as attrbuts



## The HTML < form> Elements

The HTML < form> element can contain one or more of the following form elements:

* < input>
* < label>
* < select>
* < textarea>
* < button>
* < fieldset>
* < legend>
* < datalist>
* < output>
* < option>
* < optgroup>

### so Whenever you want to collect information from
visitors you will need a form, which lives inside a
'<form>' element.
### Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.


# Lists, Tables and Forms

- The list-style-type property
allows you to control the shape
or style of a bullet point (also
known as a marker).
It can be used on rules that
apply to the '<ol>', '<ul>', and '<li>'
elements.

## Tables
using the following:
- width to set the width of the
table

- padding to set the space
between the border of each table
cell and its content

- text-transform to convert the
content of the table headers to
uppercase

- letter-spacing, font-size
to add additional styling to the
content of the table headers

- border-top, border-bottom
to set borders above and below
the table headers

- text-align to align the writing
to the left of some table cells and
to the right of the others


- background-color to change
the background color of the
alternating table rows


- Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.




# Events
browser registers different types of events javaScript then respond to these events.

Events are the browser’s way of indicating when something has happened

(such as when a page has finished loading or a button has been clicked).

## When an event occurs on an element??

- it can trigger a JavaScript function.
When this function then changes the web page in some way, it feels interactive becauseit has responded to the user.
Terminology
When an event has occurred, it is often described as having fired or been raised

Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon. (3 ways for binding)

event delegation to monitor for events that happen on all of the children of an element.

Event FLow
The order of how events fire .
directions of event flow :
1. inwards : event capturing
2. outwards : event bubbling

- The addEventListener() method
1.  The addEventListener() method attaches an event handler to the specified element.

2.  The addEventListener() method attaches an event handler to an element without overwriting existing event handlers.

3. element.addEventListener(event, function, useCapture);

The removeEventListener() method
The removeEventListener() method removes event handlers that have been attached with the addEventListener() method

