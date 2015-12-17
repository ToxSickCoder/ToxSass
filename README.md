# ToxLESS
## Introduction
A small LESS framework written for websites or web applications. I wrote this to easily create beautiful websites within the same theme. Feel free to use this or to build upon this. This project uses the MIT license.

## How to use
Either you can grab the source files in the **src** folder and start edit the LESS files. You can also use the **toxless.min.js** file from the **css** folder and go from there.

You can use the **<a href="https://github.com/ToxSickProductions/ToxLESS/blob/master/index.html">index.html</a>** page to see examples of what you can do with ToxLESS.

## Features
### Grid
ToxLESS features a percentual grid. There are six different sizes and four different display sizes. The column sizes are *100, 75, 66, 50, 33 or 25%*. The disiplay sizes are *lg (>=1200px), md (>=992px), sm (>=768px)* and less (<768px).

Everything with a size below the class minimum gets turned into a 100% column. defaults to a 100% column. Examples:

* col-100 (always 100%)
* col-75-lg (75% on a display >=768px, else 100%)
* col-50-md (50% on a display >=992px, else 100%)
* col-60-sm (60% on a display <768px, else 100%).

The highest display size counts. For example *class="col-75-lg col-66-md"*. This means the column is 75% if the display is >=1200px, if the display is between 1200px and 992px the screen will be 66% and otherwise it will default to 100% width.

### Table
For a simple but beautiful table use the *table-flat* class. See the **<a href="https://github.com/ToxSickProductions/ToxLESS/blob/master/index.html">index.html</a>** for an example.
