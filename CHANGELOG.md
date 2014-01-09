# Changelog

## 0.4.1

* Added anchors (ids) to headlines

## 0.4.2

* Added `display` properties to avoid conflicts with resets

## 0.5.0

* Added support for Haml code in examples (`haml-example`,
  `haml-layout-example`)

## 0.5.1

* Fixed highlighting in Haml code examples
* Use the Haml syntax highlighter

## 0.5.2

* More stable CSS

## 0.6.0.alpha.0

* Implemented command line interface

## 0.6.0.alpha.1

* Added Rails support
* Removed globbing
* Set .html.lsg as default file extension

## 0.6.0.alpha.2

* Better support for load paths in Rails
* Fix for colors
* New YAML based configuration
  ([see this gist](https://gist.github.com/hagenburger/7945859#file-styleguide-1-html-lsg))
* Option to set the HTML title
* Custom footer and header HTML
  ([example](https://github.com/hagenburger/livingstyleguide/blob/master/test/fixtures/standalone/styleguide-with-header-footer.html.lsg))
* Linking of JavaScript files (like jQuery, application.js, …) into the
  style guide
  ([example](https://github.com/hagenburger/livingstyleguide/blob/master/test/fixtures/standalone/styleguide-with-javascript.html.lsg))
* Custom styles can be set within YAML configuration
  ([example](https://github.com/hagenburger/livingstyleguide/blob/master/test/fixtures/standalone/styleguide-with-style.html.lsg))
