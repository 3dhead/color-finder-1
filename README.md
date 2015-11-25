# color-finder

This class can get you a common color from the image by url.
But be careful of ussing this as there are Cross Origin policy which may block some images from different domains.

## Usage

`ColorFinder.fromImage('http://....jpg', function(color) {...})`

**color** is an array which contains RGB values (like [234, 48, 255]).

You can also specify maximum value for RGB complement by calling:

`ColorFinder.setConfig('maxColorValue', 230)`

Here **230** will be limit for output color.

#### Author
**Alex Malkevich**
