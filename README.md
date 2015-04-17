# Atomic CSS bootstrap w/ SASS

This is just an example of a SASS estructure to define some Atomic CSS modifiers 

## How to create the final CSS

The final css will be created at `/dist/atomic.css` 
To create from the SASS files at `src/scss/` we need to do the following

1. Install the NPM dependiencies 

    npm install

To launch the [grunt](http://juanmaguitar.github.io/grunt-workshop/) tasks we need to have grunt-cli installed globally. If we don't have it, we'll need to do first:

    npm install -g grunt-cli


2. Launch the task grunt that compiles SASS into CSS

    grunt compass

After doing this we should have our final css at `/dist/atomic.css` 

### More info: 

- http://www.smashingmagazine.com/2013/10/21/challenging-css-best-practices-atomic-approach/
- http://engineering.appfolio.com/2012/11/16/css-architecture/

### TO-DO
- Add variables to filter if apply or not some modifiers