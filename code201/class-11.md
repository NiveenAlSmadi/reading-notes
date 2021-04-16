# Images
![img](https://tse4.explicit.bing.net/th?id=OIP.MaJmXaAJQkU3aZgwpkKDQwHaFj&pid=Api&P=0&w=234&h=176)

* You can specify the dimensions of images using CSS.
This is very helpful when you use the same sized
images on several pages of your site.

Property |	Description
-------- | --------
height |	Sets the height of an element
max-height |	Sets the maximum height of an element
max-width |	Sets the maximum width of an element
min-height |	Sets the minimum height of an element
min-width |	Sets the minimum width of an element
width |	Sets the width of an element



## background-image :

The background-image property allows you to place an image behind any HTML element. This could be the entire page or just part of the page. By default, a background image will repeat to fill the entire box, & youcan use:

`repeat` :attr to let background image is repeated both horizontally and vertically (the default way it is shown if the backgroundrepeat property isn’t used).

`repeat-x` :attr to let image is repeated horizontally only (as shown in the first example on the left).

# Video and Audio

## Video :
 using `<video>` tag you can add video to your page also:
1. `controls` :attribute adds video controls, like play, pause, and volume
2. `width` and `height` attributes can be included

## Audio :
 using `<audio>` tag you can add video to your page also:
- `controls` :attribute adds video controls, like play, pause, and volume
 

* Images can be aligned both horizontally and vertically
using CSS.

* You can use a background image behind the box
created by any element on a page.

* Background images can appear just once or be
repeated across the background of the box.

* You can create image rollover effects by moving the
background position of an image.


Value |	Description
-------- | --------
url('URL') |	The URL to the image. To specify more than one image, separate the URLs with a comma
none |	No background image will be displayed. This is default
linear-gradient() |	Sets a linear gradient as the background image. Define at least two colors (top to bottom)
radial-gradient() |	Sets a radial gradient as the background image. Define at least two colors (center to edges)
repeating-linear-gradient() |	Repeats a linear gradient
repeating-radial-gradient() |	Repeats a radial gradient
initial |	Sets this property to its default value. Read about initial
inherit |	Inherits this property from its parent element. Read about inherit


* To reduce the number of images your browser has to
load, you can create image sprites.

# Chapter 19 “Practical Information” 

* Search engine optimization helps visitors find your
sites when using search engines.

* Analytics tools such as Google Analytics allow you to
see how many people visit your site, how they find it,
and what they do when they get there.

* To put your site on the web, you will need to obtain a
domain name and web hosting.

**Domain:_** name is the address of your website that people type in the browser’s URL bar to visit your website.

**Web hosting:_** 

-Upload website to a web server, so that other people can see it .

- **Web servers** : special computers that are
constantly connected to the
Internet. They are set
up to serve web pages when
they are requested .

- **key things to choose hosting company** :
1. Disk space
2. Bandwidth
3. Backups
4. Email accounts
5. Server-side
languages and
databases


# Domain Names & Hosting
In order to put your site on the web you will need a domain name and web hosting.

Notes:
Search engine optimization helps visitors find your sites when using search engines.
Analytics tools such as Google Analytics allow you to see how many people visit your site, how they find it, and what they do when they get there.
To put your site on the web, you will need to obtain a domain name and web hosting.
FTP programs allow you to transfer files from your local computer to your web server.
Many companies provide platforms for blogging, email newsletters, e-commerce and other popular website tools (to save you writing them from scratch).

# MDN article on audio and video elements

 some suggestions for ways you could enhance the existing example we've built up:

The time display currently breaks if the video is an hour long or more (well, it won't display hours; just minutes and seconds). Can you figure out how to change the example to make it display hours?

Because `<audio>` elements have the same `HTMLMediaElement` functionality available to them, you could easily get this player to work for an `<audio>` element too. Try doing so.

Can you work out a way to turn the timer inner `<div>` element into a true seek bar/scrobbler — i.e., when you click somewhere on the bar, it jumps to that relative position in the video playback? As a hint, you can find out the X and Y values of the element's left/right and top/bottom sides via the `getBoundingClientRect()` method, and you can find the coordinates of a mouse click via the event object of the click event, called on the `Document` object. For example:

`document.onclick = function(e) { console.log(e.x) + ',' + console.log(e.y)}`