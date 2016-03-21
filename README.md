# Bootstrap-Sass-FontAwesome 

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

![Bootstrap-Sass-FontAwesome](website/images/bootstrap-sass.jpg)

## Installation
1. Download and install [NodeJS](https://nodejs.org/).
2. Download and install [Ruby](https://www.ruby-lang.org/en/).
3. Open command line and type `gem install sass`.
4. Clone or Download project straight from GitHub.
5. Extract the zip file and start working.

## Updates
* 2.0.0, 6/24/2015 - Added uncss, autoprefix, minify and auto-update to HTML files.
* 1.0.0, 5/18/2015 - Initial release, Added Bootstrap Sass Official 3.3.3, FontAwesome 4.3.0 and all its dependencies.

## Directions
* cd into the directory and run `npm install`.
* Run `gulp` and it will pull in all dependencies and compile. (if you get an error run again)
* Run `gulp watch` to watch and compile the SASS files.

When finished development
* Run `grunt clean` to uncss, autoprefix, minify and auto-update your HTML files.

## Updating configuration
* At [Gruntfile.js](https://github.com/GBratsos/Zurb-Foundation-SASS/blob/master/Gruntfile.js) on lines 22 and 52 you can insert your project files in order to automatically get updated with the minified CSS file.
* At [config.rb](https://github.com/GBratsos/Zurb-Foundation-SASS/blob/master/config.rb) you can edit the SASS configuration.
* On new HTML files add these lines of code in order to auto-update with gulp command.

`<!-- build:css css/style.min.css -->
    <link rel="stylesheet" href="css/style.css" />
    <!-- /build -->`

## File Tree Explaination
* /resoures - contains the SCSS files.
* /website - contains the website files (images, fonts, js, css, html).

## License
[GPLv3](LICENSE)

## Sass Resources
* Learn about [SASS](http://sass-lang.com/guide).
* Tutorial about [SASS](http://leveluptuts.com/tutorials/sass-tutorials).
* Learn about [Twitter Bootstrap](http://getbootstrap.com/css/).

## CSS Guidelines
* [CSS Guidelines](http://cssguidelin.es/)

## Recommended SASS compiler
You can use [Koala app](http://koala-app.com/).

## Recommended Text Editor

You can use [Brackets](http://brackets.io/).

Check out some awesome [Plugins](https://github.com/GBratsos/brackets-zurb-foundation) for Brackets text editor.
