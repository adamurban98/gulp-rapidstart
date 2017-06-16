# gulp-rapidstart

my personal mini-project to start front-end development asap.

## Getting Started

To get things running smoothly, I assume you have installed these packages installed globally.
* [NPM@6](https://www.npmjs.com) ( you can use [Yarn](https://yarnpkg.com) )
* [Gulp.js](http://gulpjs.com)
* [Bower](https://bower.io)


### Installing

* ```cd <your project>```
* ```npm install```
* ```bower install```

If everything runs smoothly, you should be able to run ```gulp serve```.


## Additional informations
*TinyPNG* - to run gulp task *tinypng* (compressing images), you have to insert your API key in /gulpfile.babel.js:28 . If you don't have one, you can get it at [tinypng website](https://tinypng.com/developers) (500 images per month for free!).
*Building production version* - just run ```gulp``` or ```gulp build```
*Wiredep* - if you don't ```gulp serve``` ATM, after editing bower.json run ```gulp wiredep```


## Front-End Dependencies included
They are all optional. You can add/remove them as you wish in /bower.json
* [Bootstrap](http://getbootstrap.com) - Front-End Framework ( v3.3.7 )
* [Font Awesome](http://fontawesome.io) - The iconic font and CSS toolkit
* [jQuery Validation](https://jqueryvalidation.org) - Form validation with jQuery
* [normalize-css](https://necolas.github.io/normalize.css/) - A modern, HTML5-ready alternative to CSS resets
* [Tooltipster](http://iamceege.github.io/tooltipster/) - jQuery plugin for modern tooltips
* [Cookieconsent](https://cookieconsent.insites.com) - The most popular solution to the EU cookie law
* [Owl Carousel 2](https://owlcarousel2.github.io/OwlCarousel2/) - Beautiful responsive carousel sliders
* [matchHeight](https://github.com/liabru/jquery-match-height) - a responsive equal heights plugin for jQuery
* [WOW](https://github.com/matthieua/WOW) - Reveal CSS animation as you scroll down a page
* and others.

## Authors
* **Me** - [keevvinc](https://github.com/keevvinc)