# LESS vs. Less

This project, forked from Joni Korpi's [Less Framework](http://lessframework.com), aims to combine his awesome work with the super-cool [LESS CSS](http://lesscss.org). Mostly it just make things easier for me to code, but I thought I'd stick it up on GitHub since it came out well.

*NOTE:* I'm not really using this anymore. Since then I've moved on to using either fluid em-based grids or hand-coded breakpoints. That being said, Joni's framework has informed the way I work and lay out styles to this day.

> Less Framework is a CSS grid system for designing adaptive web sites. It contains 4 layouts and 3 sets of typography presets, all based on a single grid.
> 
> For more information, visit http://lessframework.com/

## Differences to the version at lessframework.com

The [configurable version](http://lessframework.com/) lets you choose between three sets of type presets, as well as lets you add an optional Retina media query and the [http://code.google.com/p/html5shim/](HTML5 Shim). In this version, the type presets have been split into three versions of the main CSS file, all of which also include the Retina media query. The HTML5 Shim is not included.

## Included files

- main.html: Required HTML
- main-16px.css: Required CSS with type presets based on a font-size of 16px at a line-height of 24px
- main-17px.css: Same as above, but based on a font-size of 17px
- main-18px.css: Same as above, but based on a font-size of 18px

## Usage

Solid knowledge of HTML and CSS is recommended. You'll find the dimensions for each layout noted down in comments within the CSS files.

Less Framework is licensed under MIT: http://opensource.org/licenses/mit-license.php
