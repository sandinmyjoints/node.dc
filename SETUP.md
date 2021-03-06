# Setup of Node.dc Community Website

## How to get it running
This is a quick how-to to get the website running locally.

Check Node/NPM versions:

    $ node --version
    v0.10.22
    $ npm --version
    1.3.14

Install Grunt-CLI & Bower globally.:

    $ npm install -g grunt-cli
    $ npm install -g bower

Install required packages:

    $ npm install
    
Install required resources

    $ bower install

Serve website:

    $ node server.js
    Express server listening on port 3000

## Development Ideas

### Going Forward
This website is leveraging both [Node.js](http://nodejs.org) and [Angular.js](http://angularjs.org/). Node.js will be used for an API interface to Angular.js so that we can use both of these technologies to their full advantages.

Currently, in `routes/api.js` we have a simple "API" call returning a name to use within the Angular.js partials. In the future, all APIs will be written in Node.js feeding the Angular.js app.

The Node.js views and Angular.js partials are all written using the templating language [Jade](http://jade-lang.com/).
