# Read:13 Summary 
## SENDING FORM DATA

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
in the body of the HTTP request.
***the server receives a string that will be parsed in order to get the data as a list of key/value pairs.***
* high quality frameworks that make handling forms easier, such as:
  * Django for Python
  * Express for Node.js.
  * Laravel for PHP.
  * Ruby On Rails for Ruby

* If you want to send files, you need to take three steps:

  * Set the method attribute to POST because file content can't be put inside URL parameters.
  * Set the value of enctype to multipart/form-data because the data will be split into multiple parts, one for each file plus one for the text data included in the form body (if text is also entered into the form).
  * Include one or more <input type="file"> controls to allow your users to select the file(s) that will be uploaded.
  
### Security issues
* All data that comes to your server must be checked and sanitized. Always. No exception
* Limit the incoming amount of data to allow only what's necessary.
* HTML forms are by far the most common server attack vectors (places where attacks can occur).the problem comes from how the server 
handles data.

