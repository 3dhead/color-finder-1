# color-finder [![Build Status](https://travis-ci.org/gund/color-finder.svg?branch=master)](https://travis-ci.org/gund/color-finder)  [![Coverage Status](https://coveralls.io/repos/gund/color-finder/badge.svg?branch=master&service=github)](https://coveralls.io/github/gund/color-finder?branch=master)

This class can get you a common color from the image by url.
But be careful of ussing this as there are Cross Origin policy which may block some images from different domains.

Live Demo: http://preview.16mb.com/color-finder/

## Installation

**Using bower:**

`bower install color-finder --save`

**Using npm:**

`npm install color-finder`

or just download latest release from Github.

## Usage

`ColorFinder.fromImage('http://....jpg', function(color) {...})`

**color** is an array which contains RGB value (like [234, 48, 255]).

You can also specify maximum value for RGB complement by calling:

`ColorFinder.setConfig('maxColorValue', 230)`

Here **230** will be limit for output color.

## Development

To build this package run `gulp`

To run tests run `npm test`

### Credits

- Nick Rabinowitz – Thanks for the modified median cut quantization JS port (http://www.leptonica.com)

#### Author
**Alex Malkevich**
