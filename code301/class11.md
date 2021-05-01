### EJS
Install by using npm install --save ejs. Set up by using app.set. In parameter x we add view engine, and in y we add ejs.
We can make strings available in the ejs view by adding madulo in elements inside of html; inside the carrots. Similar to a class or id tag. Also, similar to mustache.
![img](https://www.veracode.com/sites/default/files/styles/blog_post_resize_960/public/blog-secure-dev-context-matters-nodejs-templates.jpg?itok=BtIs8vrV)

# Using ejs with for loops and arrays.
Using madulo inside of html we can build a for loop to run through an array. We can then call an object from js from inside of html. We would call it in the same way we call objects in js. Something like object.name or object.animal.

# Using ejs and if/else statements
If else statements may also be used with ejs inside of html. 

# Ejs layouts
We can install ejs layouts using npm install package. We then use a variable at the top and add express-ejs-layouts. After we call it with app.use(expressLayouts). With this we can create a layout in html that will help us keep one layout through multiple web pages.

* Features of EJS :
* Fast compilation and rendering
* Simple template tags: `<% %>`
* Both server JS and browser support
* Static caching of intermediate JavaScript
* Static caching of templates
* Complies with the Express view system
* to install EJS with NPM write this in your terminal :` npm install ejs`
* Caching : EJS ships with a basic in-process cache for caching the intermediate JavaScript functions used to render templates.
* Layouts : EJS does not specifically support blocks, but layouts can be implemented by including headers and footers.

## Caveats
* Obviously, since you do not have access to the filesystem, `ejs.renderFile` won't work.
* For the same reason, includes do not work unless you use an include callback .

## We can use EJS to Template our Node Application
* For applications that need quick templating, there are many options that we can use :
  * `Jade` : comes as the view engine for Express by default 
  * `EJS` : is one alternative does that job well and is very easy to set up

***We can use `EJS` to include repeatable parts of our site (partials) and pass data to our views.***

* `package.json` :  will hold our Node application information and the dependencies we need `(express and EJS)`
* `server.js` :  will hold our Express server setup, configuration 
### Conclusion

* EJS let's us spin up quick applications when we don't need anything too complex. By using partials and having the ability to easily pass variables to our views, we can build some great applications quickly.
