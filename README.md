# ToxSass
## Introduction
A small Sass framework written for websites or web applications. I wrote this to easily create beautiful websites within the same theme. Feel free to use this or to build upon this. This project uses the MIT license.

## How to use
Either you can grab the source files in the **src** folder and start edit the Sass files. You can also use the **toxsass.min.js** file from the **css** folder and go from there.

You can use the **<a href="https://github.com/ToxSickProductions/ToxSass/blob/master/index.html">index.html</a>** page to see examples of what you can do with ToxSass.

## Features
### Variables
ToxSass works with variables to easily changes colors, grid sizes or more. You can find and change the variables in the found in the **<a href="https://github.com/ToxSickProductions/ToxSass/blob/master/src/_variables.scss">_variables.sass</a>** file.

Every color is based on a few main colors, especially the **@accent-color**. Try playing with the value to see what changes. The standard value is #070.
### Grid
ToxSass features a percentual grid. There are six different sizes and four different display sizes. The column sizes are *100, 75, 66, 50, 33 or 25%*. The display sizes are *lg (>=1200px), md (>=992px), sm (>=768px)* and less (<768px).

Everything with a size below the class minimum gets turned into a 100% column. defaults to a 100% column. Examples:

* col-100 (always 100%)
* col-lg-75 (75% on a display >=768px, else 100%)
* col-md-50 (50% on a display >=992px, else 100%)
* col-sm-66 (60% on a display <768px, else 100%).

The highest display size counts. For example *class="col-lg-75 col-md-66"*. This means the column is 75% if the display is >=1200px, if the display is between 1200px and 992px the screen will be 66% and otherwise it will default to 100% width.

### Table
For a simple but beautiful table use the *table-flat* class. See the **<a href="https://github.com/ToxSickProductions/ToxSass/blob/master/index.html">index.html</a>** for an example.

### Forms
You can build forms in two ways: either with the grid system or without it. The first example in the **<a href="https://github.com/ToxSickProductions/ToxSass/blob/master/index.html">index.html</a>** file doesn't use the grid while the second example does.

The second example features inline form rows, but this isn't required. It just depends on how you use the grid system.

### Buttons
There are three button sizes and 4 button types you can use. The sizes are: *button-lg*, *button-sm* and normal. The types are: *dark*, *light*, *inverted* and normal. See the **<a href="https://github.com/ToxSickProductions/ToxSass/blob/master/index.html">index.html</a>** for an example.
