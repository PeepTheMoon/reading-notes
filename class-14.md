# https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html?auth=login-email&login=email

"studies show that groups tend to innovate faster, see mistakes more quickly and find better solutions to problems. Studies also show that people working in teams tend to achieve better results and report higher job satisfaction."

collective intelligence declines when only one person or a small group within a team talk  Equal speaking is important. Having more social sensitivity (sensitivity to what others may be thinking or feeling) were more successful.  Fosters psychological safety.

## https://learn.shayhowe.com/advanced-html-css/css-transforms/

the transform property offers new ways of positiooning, sizing and changing elements.  Can be 2d or 3d, each with its own individual properties and values.

transform property includes multiple vendor prefixes to gain the best support across all browsers.
 ex: div {
        -webkit-transform: scale(1.5);
            -moz-transform: scale(1.5);
            -o-transform: scale(1.5);
                transform: scale(1.5);
        }

2d transforms:
The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically

 the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.

 It is possible to scale only the height or width of an element using the scaleX and scaleY values. The scaleX value will scale the width of an element while the scaleY value will scale the height of an element. To scale both the height and width of an element but at different sizes, the x and y axis values may be set simultaneously. To do so, use the scale transform declaring the x axis value first, followed by a comma, and then the y axis value.

 The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document. Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.

As with the scale value, to set both the x and y axis values at once, use the translate value and declare the x axis value first, followed by a comma, and then the y axis value.

The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both.

It is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time for example using commas.

default transform origin is the dead center of an element, both 50% horizontally and 50% vertically. To change this default origin position the transform-origin property may be used.

The transform-origin property can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. If two values are specified, the first is used for the horizontal axis and the second is used for the vertical axis.

In order for three-dimensional transforms to work the elements need a perspective from which to transform. The perspective for each element can be thought of as a vanishing point, similar to that which can be seen in three-dimensional drawings.

The perspective of an element can be set in two different ways. One way includes using the perspective value within the transform property on individual elements, while the other includes using the perspective property on the parent element residing over child elements being transformed.

The perspective value can be set as none or a length measurement. The none value turns off any perspective, while the length value will set the depth of the perspective. The higher the value, the further away the perspective appears, thus creating a fairly low intensity perspective and a small three-dimensional change. The lower the value the closer the perspective appears, thus creating a high intensity perspective and a large three-dimensional change.

As with setting a transform-origin you can also set a perspective-origin. The same values used for the transform-origin property may also be used with the perspective-origin property, and maintain the same relationship to the element. The large difference between the two falls where the origin of a transform determines the coordinates used to calculate the change of a transform, while the origin of a perspective identifies the coordinates of the vanishing point of a transform.


more on 3d specifics.

### https://learn.shayhowe.com/advanced-html-css/transitions-animations/

for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

Vendor prefixes are needed here as well.

It is important to note, not all properties may be transitioned, only properties that have an identifiable halfway point. Colors, font sizes, and the alike may be transitioned from one value to another as they have recognizable values in-between one another. The display property, for example, may not be transitioned as it does not have any midpoint. A handful of the more popular transitional properties include the following.

background-colorbackground-positionborder-colorborder-widthborder-spacingbottomclipcolorcropfont-sizefont-weightheightleftletter-spacingline-heightmarginmax-heightmax-widthmin-heightmin-widthopacityoutline-coloroutline-offsetoutline-widthpaddingrighttext-indenttext-shadowtopvertical-alignvisibilitywidthword-spacingz-index

#### https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users/
 Cool techniques like:
 1. fade in
 1. change color
 1. grow and shrink
 1. rotate elements
 1. square to circle
 1. 3d shadow
 1. swing
 1. inset border

 ##### 
 more ways to animate buttons, create bouncing balls, moving numbers, keyframes, etc.