Yeoman generator that scaffolds out a front-end web app. forked from generator-webapp with flexibility in mind.

## Features

* CSS Autoprefixing (new)
* Built-in preview server with LiveReload
* Automagically compile CoffeeScript & Compass
* Automagically lint your scripts
* Automagically wire up your Bower components with [bower-install](https://github.com/stephenplusplus/grunt-bower-install).
* Awesome Image Optimization (via OptiPNG, pngquant, jpegtran and gifsicle)
* Mocha Unit Testing with PhantomJS
* Optional - JQuery
* Optional - Twitter Bootstrap for SASS
* Optional - Leaner Modernizr builds (new)
* Optional - Susy grid system (new)

## Getting Started

- Install: `npm install -g yo`
- Install: `npm install -g generator-axyz`
- Run: `yo axyz`
- Run `grunt` for building and `grunt server` for preview


## Options

* `--skip-install`

  Skips the automatic execution of `bower` and `npm` after scaffolding has finished.

* `--test-framework <framework>`

  Defaults to `mocha`. Can be switched for another supported testing framework like `jasmine`.


## License

[BSD license](http://opensource.org/licenses/bsd-license.php)
