## SENDING FORM DATA
## Client Server
Client makes a request to a server using HTTP protocol. Server will answer using HTTP. 
- Apache
- Nginx 
- IIS
- Tomcat
HTML is the form we use to configure HTTP request to the server.Information is delivered in this way to the HTTP request

## Form
This defines how data is sent. All attributes are designed for requests to be sent when the submit button is used. 
## Action
This is where the data is sent. Or where the data is going to. It's value is a relative or an absolute URL. If it doesn't have an attribute everything goes to the page that contains the form.

#
- Get method asks the browser to ask the server to send a resource. 
- Post uses data and asks the browser to look at the data and send back a result.
#
## HTML 5
- Name defines identifier for a button within a form.
- Value sent to the server when submitting a form.
- Type defines the button type.
- Action defines which url the forms info is sent to.
- Method defines the HTTP method used when submitting the form.
- Target defines in which tab the clicked link will show up.
- Required tells the browser that this input is required before moving forward with form input. It won't load anything unless the form field is filled out.
* An HTML form on a web page is nothing more than a convenient user-friendly way to configure an HTTP request to send data to a server. This enables
the user to provide information to be delivered in the HTTP request.
* All of the `form` attributes are designed to let you configure the request to be sent when a user hits a submit button. The two most important attributes
are (`action` and `method`).
* The `action` attribute : defines where the data gets sent.so Its value must be a valid relative or absolute URL.
* The` method` attribute defines how data is sent.
* An `HTTP` request consists of two parts :
  * `header` : contains a set of global metadata about the browser's capabilities
  * `body` : contains information necessary for the server to process the specific request.
* client (usually a web browser) : sends a request to a server (most of the time a web server like `Apache`, `Nginx`, `IIS`, `Tomcat`, etc.), 
using the HTTP protocol.Then the  server answers the request using the same protocol.

***GET method : used by the browser to ask the server to send back a given resource.then the browser sends an empty body.***

***POST method : browser using this method to talk to the server when asking for a response that takes into account the data provided
in the body of the HTTP request.***

***the server receives a string that will be parsed in order to get the data as a list of key/value pairs.***

* high quality frameworks that make handling forms easier, such as:
  * Django for Python
  * Express for Node.js.
  * Laravel for PHP.
  * Ruby On Rails for Ruby
