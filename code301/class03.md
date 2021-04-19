## Flexbox and Templating

### Templating with Mustache
## Javascript Templating:
Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source
The template engine then replaces variables and instances declared in a template file with actual values at runtime, and convert the template into an HTML file sent to the client.

## Mustache
Mustache is a logic-less template syntax. It can be used for HTML, config files, source code â€” anything

Mustache-Express
You can use mustache-express. To install
With Yarn: `yarn add mustache-express`
or with NPM:
`npm install mustache --save`
lexBox
CSS Flexbox Layout Module

### The flex item properties are:

- order
- flex-grow
- flex-shrink
- flex-basis
- flex
- align-self
- align content
- normal (default): items are packed in their default position as if no value was set.

### justify-content property, 
which aligns items horizontally and accepts the following values:
- flex-start: Items align to the left side of the container.
- flex-end: Items align to the right side of the container.
- center: Items align at the center of the container.
- space-between: Items display with equal spacing between them.
- space-around: Items display with equal spacing around them

### A Guide to Flexbox:
I'll just mention three if it here :

- display This defines a flex container; inline or block depending on the given value
.container { display: flex; /* or inline-flex */ }

- flex-direction This establishes the main-axis, thus defining the direction flex items are placed in the flex container.
.container { flex-direction: row | row-reverse | column | column-reverse; }

- flex-flow This is a shorthand for the flex-direction and flex-wrap properties, which together define the flex containerâ€™s main and cross axes
.container { flex-flow: column wrap; }