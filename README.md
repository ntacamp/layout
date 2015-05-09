# NTACamp page html layout
## How to develop

### Tools you need

    # Install Node.js
    [install wiki](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager)

    # Install Grunt
    npm install grunt-cli -g

    # Install Compass
    gem install compass



### Development

After `package.jsonz has changed, or if just cloned repository, run:

    npm install

Then use
    
    # Perform all tasks
    grunt

    # Generate SASS to CSS
    grunt sass:dist 

    # Watch for HTML and SCSS file changes, auto-generates CSS, reloads(*) page
    grunt watch

* `grunt watch` will reload page if your HTML file contains JavaScript `<script src="//localhost:35729/livereload.js"></script>`