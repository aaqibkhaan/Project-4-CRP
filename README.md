## Project 4 : Website Performance Optimization

###How to run the Project

You can [download](https://github.com/aaqibkhaan/Project-4-CRP/archive/master.zip) it in your desktop and unzip it to see the files or you can clone it from <https://github.com/aaqibkhaan/Project-4-CRP.git> 

###Part 1: Optimize PageSpeed Insights score for index.html

You can view the [Live Demo](https://aaqibkhaan.github.io/Project-4-CRP)

####Results:
* Mobile : 93/100
* Desktop : 93/100

####Changes made in index.html
* Fonts loading using javaScript
* Sorting out the order of code i.e: Scripts at the bottom
* External script loading to async
* Minify Js and Css
* Redundant and unused styles removed
* Css inlined for better performance 

###Part 2: Optimize Frames per Second in pizza.html

You can view the [Live Demo](https://aaqibkhaan.github.io/Project-4-CRP/views/pizza.html)

####Results
* Time to resize pizza under 5ms.
* 60 fps

####Changes made in pizza.html
* updatePositions() updated with memory efficient code.
* changePizzaSizes() calculating newWidth once in % .
* for() loops modified for better performance.

### Sources

* <https://tinypng.com>
* <http://www.willpeavy.com/minifier>
* <https://jscompress.com>
