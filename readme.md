# Simple mixin library for sass and less
This is a simple set of tools that you can include in your projects if you wish. It is not a framework; you can simply pick and choose what you want to use, and if you don't use them, you won't see them in your compiled CSS. You are then free to add any additional tools your project requires, and we can add them here if they're likely to be useful in other projects too.

Keeping it a simple library for both Sass and Less will mean that we can maintain it more easily, and use it across all our CMSs while learning both Sass and Less.

## Made by
[Benn Pearson](http://twitter.com/bennpearson) & [Pete Naish](http://twitter.com/tweet_naish)

### Folder structure
Sass is shown below, but the same exists for Less.

    sass
    |
    +-- tools
    |   |
    |   +-- functions // maths and calculations
    |   |   |
    |   |   +-- _all.scss
    |   |   +-- _em-calc.scss
    |   |   +-- _grid--flex.scss
    |   |   +-- _percentage.scss
    |   |   +-- _strip-units.scss
    |   |
    |   +-- mixins // prefixers etc
    |   |   |
    |   |   +-- _all.scss
    |   |   +-- _animation.scss
    |   |   +-- _background.scss
    |   |   +-- _border-radius.scss
    |   |   +-- _font-face.scss
    |   |   +-- _media-query.scss
    |   |   +-- _media-query--hi-dpi.scss
    |   |   +-- _prefix.scss
    |   |   +-- _transform.scss
    |   |   +-- _transition.scss
    |   |
    |   +-- helpers // common tasks
    |   |   |
    |   |   +-- _all.scss
    |   |   +-- _clearfix.scss
    |   |   +-- _hide-text.scss
    |   |   +-- _image-replacement.scss
    |   |   +-- _retina-image.scss
    |   |
    |

### Mixins
animation

background

border-radius

appearance

backface-visibility

border-image

box-sizing

columns

flex-box

font-face

inline-block

hidpi

image-rendering

keyframes

placeholder

perspective

linear-gradient

radial-gradient

user-select

transform

transition

### Example functions
compact

flex-grid

golden-ratio

grid-width

linear-gradient

modular-scale

radial-gradient

shade

tint

### Example helpers
button

clearfix

hide-text

em

position

prefixer

retina-image

size

triangle

HTML5 Inputs

font-family

timing-functions

## To do

- Add [Vertical Rhythm](http://24ways.org/2006/compose-to-a-vertical-rhythm/) mixin
- Add partials to repo