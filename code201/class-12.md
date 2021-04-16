# CHART.JS
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

## Setting up
The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script.

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
    <body>
    </body>
</html>
```
## Drawing a line chart
To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page.



* Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart. Add this immediately above the line that begins ‘var buyers=’:



## Drawing a pie chart
Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element

```
<canvas id="countries" width="600" height="400"></canvas>
```

* Next, we need to get the context and to instantiate the chart:

```
var countries= document.getElementById("countries").getContext("2d");
new Chart(countries).Pie(pieData, pieOptions);
```

* You’ll notice that this time, we are going to supply some options to the chart.

* Next we need to create the data. This data is a little different to the line chart because the pie chart is simpler, we just need to supply a value and a color for each section

* Now, immediately after the pieData we’ll add our options

```
var pieOptions = {
	segmentShowStroke : false,
	animateScale : true
}
```

These options do two things, first they remove the stroke from the segments, and then they animate the scale of the pie so that it zooms out from nothing.

## Drawing a bar chart

```
<canvas id="income" width="600" height="400"></canvas>
```

* Next, we retrieve the element and create the graph:

```
var income = document.getElementById("income").getContext("2d");
new Chart(income).Bar(barData);
```



# Basic usage of canvas

## The `<canvas>` element

```
<canvas id="tutorial" width="150" height="150"></canvas>
```

# Drawing shapes with canvas
* The grid
 Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. 

* Drawing rectangles
 There are three functions that draw rectangles on the canvas:

`fillRect(x, y, width, height)`

Draws a filled rectangle.

`strokeRect(x, y, width, height)`

Draws a rectangular outline.

`clearRect(x, y, width, height)`

Clears the specified rectangular area, making it fully transparent.
Each of these three functions takes the same parameters. x and y specify the position on the canvas (relative to the origin) of the top-left corner of the rectangle. width and height provide the rectangle's size.

# Applying styles and colors
## Colors

`fillStyle = color`

Sets the style used when filling shapes.

`strokeStyle = color`

Sets the style for shapes' outlines.

# Drawing text

`fillText(text, x, y [, maxWidth])`

Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

`strokeText(text, x, y [, maxWidth])`

Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
