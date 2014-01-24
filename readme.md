# Simple mixin library for sass and less

This will hopefully be a more flexible framework that everyone can use. Keeping it a simple mixin library for both sass and less will mean that we can maintain it more easily and use it across all our CMSs while learning both sass and less.

## Made by

Benn Pearson 
twitter.com/bennpearson

## Roadmap

Version 1.0

### Example file structure

FED mixin library
- core (current supported code)
-- sass
--- Mixins
---- _animation.scss
---- _background.scss
---- _border-radius.scss
--- Functions
---- _compact.scss
---- _flex-grid.scss
---- _golden-ratio.scss
--- Addons
---- _button.scss
---- _clearfix.scss
---- _hide-text.scss
-- less
--- Mixins
---- _animation.less
---- _background.less
---- _border-radius.less
--- Functions
---- _compact.less
---- _flex-grid.less
---- _golden-ratio.less
--- Addons
---- _button.less
---- _clearfix.less
---- _hide-text.less
- beta (future not currently supported code but will be)
-- sass
--- Mixins
--- Functions
---- _baseline.scss
---- _grid.scss (based on W3C grid module)
--- Addons
-- less
--- Mixins
--- Functions
---- _baseline.less
---- _grid.less (based on W3C grid module)
--- Addons

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