# https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/
Notes for setting up charts.js in your files.  Good for line, bar, and pie graphs (and more).

## Chart.js docs:
Extension that allows for easier chart creation.

### Basic usage
https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage

Canvas element has two attributes, width and height.  Specify these in the canvas attribute of HTML and not in CSS.  The id isn't specific to the canvas element.  Supply one to make it easier to identify in a script.  

It is easy to define fallback content for older browsers and this should be done.  

This element requires a closing tag < /canvas>  

Images can renedered in 2D or 3D.

#### Drawing shapes with canvas
https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes

Coordinate space = canvas grid.  A default grid is provided but this can be changed.  Different shapes like lines, rectangles, quadratic and bezier curves, arcs or circles, etc. are detailed here.

##### Applying styles and colors
https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors

you can set styles for filling shapes and outlines with color. Once you set a color, it needs to be renamed every time beacuse it becomes the default for everything after it.

You can draw semi-transparent or opaque shapes.

You can change line styles, line width, and add caps to lines.  You can also change the way lines meet.  

You can add shadows to text and create patterns!

###### Drawing text
https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text

Drawing and styling text examples.
