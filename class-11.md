# Read:11 Summary
## EJS
> EJS : refers to `Embedded JavaScript templating`.

* `EJS` :  is a simple templating language that lets you generate HTML markup with plain JavaScript.***No religiousness about how to organize things. No reinvention of iteration and control-flow. It's just plain JavaScript.***

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

### Caveats
* Obviously, since you do not have access to the filesystem, `ejs.renderFile` won't work.
* For the same reason, includes do not work unless you use an include callback .
-----------------------------------------------------------------------------------------------
### We can use EJS to Template our Node Application
* For applications that need quick templating, there are many options that we can use :
  * `Jade` : comes as the view engine for Express by default 
  * `EJS` : is one alternative does that job well and is very easy to set up

***We can use `EJS` to include repeatable parts of our site (partials) and pass data to our views.***

* `package.json` :  will hold our Node application information and the dependencies we need `(express and EJS)`
* `server.js` :  will hold our Express server setup, configuration 
### Conclusion

* EJS let's us spin up quick applications when we don't need anything too complex. By using partials and having the ability to easily pass variables to our views, we can build some great applications quickly.

