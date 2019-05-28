# LESS & SASS

## Tools

* current version of LESS and SASS
* Install Ruby
* LESS compiler: SimpLESS
* npm install -g sass
* sass styles.scss styles.css
* npm install -g less
* lessc styles.less styles.css

## LESS

* @ for variables
* mixIns (variables for rules)
* nested and &:hover
* operators: +, -, /, *, (...)
* mix params, defaults and @arguments
* pattern matching
* guarded mixin when
* functions - color, math
* @imports __"fileName.less"__

## SASS

* $ for variables !default
* @mixin directive, @include, @extend, %
* nested and &:hover
* operators: +, -, /, *, (...)
* if Conditional
* mix params, defaults and @arguments
* functions - color, math
* @imports __"fileName.scss"__
* sass style.scss styles.css --watch
* &.class { ... }
* .class & { ... }
* **_fileName.scss** is a partial file
* @mixin foo($opacity:null) { opacity: $opacity} if no variable passed to this mixin opacity null will not be compiled to css rules
* @content uses the content of where it is placed
* $i from i through 5
* $maps: ('m':'margin', 'p': 'padding');
* map-get($map, $key);
* $list: ('a', 'b', 'c');
* nth($list, $n)
* $dir in $direction { #{nth($dim,1)}-#{nth($dim,2)}}
* @function & @return
* font: { size: 10px; weight: bold}

## Variables

* hextractor: extracts colors in css files
* put colors in variables
* __#{$var}__
* var args (var...)

## mixin

* you can use apply mixin in root

## function

* darken
* lighten
* transparentize
* opacify
* __#{$var}__

## flow control

* @if, @else if, @else, @return
* @for $i from 1 through 6
* @each $speaker in $speakers
* @each $key,$value in $map
* @while

## frameworks

* susy
* brealpoint-sass
* compass