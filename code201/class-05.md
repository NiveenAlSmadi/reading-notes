# Images in HTML 
## HOW to How to add images to pages??
- Include an image i ●● n your web pages using HTML :
To add an image into the page
you need to use an <img>
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes

- src
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).
 - alt
This provides a text description
of the image which describes the
image if you cannot see it.

- title
You can also use the title
attribute with the <img> element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the imag


![img](https://tse2.mm.bing.net/th?id=OIP.yB-m1l3ux0YUTh4G34x-YQHaEZ&pid=Api&P=0&w=292&h=174)

- we can also  edit the img by :


1. height
This specifies the height of the
image in pixels.
2. width
This specifies the width of the
image in pixels.


## Aligning Images Horizontally :
align horizontally.html HTML
The align attribute was
commonly used to indicate how
the other parts of a page should
flow around an image.
The align attribute can take
these horizontal values:
- left:

This aligns the image to the left
(allowing text to flow around its
right-hand side).

- right :

This aligns the image to the right
(allowing text to flow around its
left-hand side).

## Aligning Images Vertically :

- by top :
This aligns the first line of the
surrounding text with the top of
the image.

- middle :
This aligns the first line of the
surrounding text with the middle
of the image.

- bottom :
This aligns the first line of the
surrounding text with the bottom
of the image.


## Three Rules for Creating Images
1. Save images in the right format
2. Save images at the right size
3. Use the correct resolution



# HTML 5: Figure and Figure Caption 
<figure>
Images often come with
captions. HTML5 has introduced
a new <figure> element to
contain images and their caption
so that the two are associated.
You can have more than one
image inside the <figure>
element as long as they all share
the same caption.
<figcaption>
The <figcaption> element has
been added to HTML5 in order
to allow web page authors to add
a caption to an image.

- so You should save images at the size you will be using
them on the web page and in the appropriate format.
and Photographs are best saved as JPEGs; illustrations or
logos that use flat colors are better saved as GIFs.

# colors 
### How to specify colors??

- Color can really bring your pages to life. 
- You can specify any color in CSS in one of three ways:
1. rgb values
2. hex codes
3. color names

![css](https://tse1.mm.bing.net/th?id=OIP.J58C8K6cUzjvDc5EgaPTYwFrCs&pid=Api&P=0&w=341&h=162)


## css3  
- CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
- CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.

attach here an cheat sheet re (https://www.smashingmagazine.com/)


![css3](https://tse4.mm.bing.net/th?id=OIP.SJg7zqiG4eJL9ETSepIDaQHaDz&pid=Api&P=0&w=330&h=170)

# TEXT 

CSS has a lot of properties for formatting text.
- The text-align property is used to set the horizontal alignment of a text.
- A text can be left or right aligned, centered, or justified. 
- The direction and unicode-bidi properties can be used to change the text direction of an element
- The vertical-align property sets the vertical alignment of an element.
- The text-decoration property is used to set or remove decorations from text.
- The text-transform property is used to specify uppercase and lowercase letters in a text.It can be used to turn everything into uppercase or lowercase letters, or capitalize the first letter of each word.
- The text-indent property is used to specify the indentation of the first line of a text
- The text-shadow property adds shadow to text.


## Generic Font Families
In CSS there are five generic font families:

- Serif fonts have a small stroke at the edges of each letter. They create a sense of formality and elegance.
- Sans-serif fonts have clean lines (no small strokes attached). They create a modern and minimalistic look.
- Monospace fonts - here all the letters have the same fixed width. They create a mechanical look. 
- Cursive fonts imitate human handwriting.
- Fantasy fonts are decorative/playful fonts.
- All the different font names belong to one of the generic font families. 

![font](https://tse3.mm.bing.net/th?id=OIP.zEJJefJma3JcpskrVGAyngHaCp&pid=Api&P=0&w=398&h=142)



## The CSS font-family Property
In CSS, we use the font-family property to specify the font of a text.

The font-family property should hold several font names as a "fallback" system, to ensure maximum compatibility between browsers/operating systems. Start with the font you want, and end with a generic family (to let the browser pick a similar font in the generic family, if no other fonts are available). The font names should be separated with comma.

![font](https://i0.wp.com/www.foxinfotech.in/wp-content/uploads/2019/04/font-family-css.jpg?fit=757%2C333&ssl=1)

- so  You can control the space between lines of text,
individual letters, and words. Text can also be aligned
to the left, right, center, or justified. It can also be
indented. and  You can use pseudo-classes to change the style of an
element when a user hovers over or clicks on text, or
when they have visited a link.

# JPEG vs PNG vs GIF — which image format to use and when ??

1. JPEG is a lossy compression specification that takes advantage of human perception. and jpeg don’t support transparency and are hence not usable for such cases.
2. GIF is a lossless image format that uses LZW compression algorithm , support transparency by declaring a single colour in the colour palette as transparent (index transparency).
3. PNG is a lossless image format using DEFLATE compression. and  support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single colour as transparent (index transparency). Partial transparency makes the edges blend smoothly into the background.



![img](https://tse4.mm.bing.net/th?id=OIP.o7bfuocNOCpPGokvYYLC1AHaF7&pid=Api&P=0&w=192&h=155)






recorces :
1. Duckett HTML book
2. www. w3schools.com 
3. https://blog.imagekit.io/ 


