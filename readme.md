# Simple mixin library for sass and less

This will hopefully be a more flexible framework that everyone can use. Keeping it a simple mixin library for both sass and less will mean that we can maintain it more easily and use it across all our CMSs while learning both sass and less.

## Made by

[Benn Pearson](twitter.com/bennpearson)
[Pete Naish](twitter.com/tweet_naish)


## Roadmap

Version 1.0

### Example file structure

FE mixin library

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


- **functions**
    - _compact.scss
    - _golden-ratio.scss
    - _(baseline).scss
    - _(grid).scss
- **addons**
    - _button.scss


### Example Mixins
_animation

_background

_border-radius

_appearance

_backface-visibility

_border-image

_box-sizing

_columns

_flex-box

_font-face

_inline-block

_hidpi

_image-rendering

_keyframes

_placeholder

_perspective

_linear-gradient

_radial-gradient

_user-select

_transform

_transition

### Example functions
_compact

_flex-grid

_golden-ratio

_grid-width

_linear-gradient

_modular-scale

_radial-gradient

_shade

_tint

### Example Addons
_button

_clearfix

_hide-text

_em

_position

_prefixer

_retina-image

_size

_triangle

_HTML5 Inputs

_font-family

_timing-functions
