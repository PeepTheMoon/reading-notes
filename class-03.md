# HTML book: Chapter 3: “Lists” (pp.62-73)

HTML Offers 3 types of lists:
1. Ordered lists (numbered) <ol> and <li> as child elements
2. Unordered lists (bullet points)<ul> and <li> as child elements
3. definition lists (terms and definitions)<dl> with <dt> for term identified and <dd> for the definition

Lists can be nested.


## HTML Chapter 13: “Boxes” (pp.300-329)

A box is sized big enough to hold its contents.  Set your own dimensions with heigth and width properties.  You can name these properties with pixels, percentages or ems.
1. pixels allow for accurate size control
2. percentages mean the box is relative to the browser window or the elements containing box.
3. ems means the box will be based on the size of the text within it and are flexible across screen sizes.

Limiting width and height:
Min-width property specifies the smallest size a box can be when browser width is narrow and max-width can stretch to when the browser window is wide.
Max-height and min-height.

Overflowing content:
Overflow property tells the browser what to do when the content is larger than the box itself.  
Hidden hides content that doesn't fit in the box.
Scroll adds a scrollbar.

Whitespace and vertical margin are able to be controlled with the border, margin and padding properties of the boxes of the page's elements.  These elements can be applied to each side of a box individually.

Control border width, style and color.  each side can be controlled individually.  Shorthand allows control for all 3 in one and needed to be coded in a specific order:
        p {
            width: 250px;
            border: 3px, dotted, #0088dd;
        }

Centering content:
set left-margin and right-margin to auto.  This puts an equal gap on each side of the box.  For older browsers the element should have a text-align: center.  This property is inherited by child elements. 

Display property:
Inline allows for a block level elements to act like an inline element, and vice versa with block.  Inline-block flows like an inline element but retains block element features. None hides an element from the page.

Visibility:
Allows you to hide boxes from users but leaves a space.  Can take hidden (hides) and visible (shows).

You can apply border images and box shadows, and box shadows and have different offsets and spreads, as well as blurring (p.320).

Round corners and create elliptical shapes with border-radius, each corner can be set individually as well (p.322).


### JS Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)

Switch statements:
Compares values against possible outcomes. Are run faster than if statements.  Switch statements stop the code with a break; as soon as the match is found.  Has a default option is no match is found.

Type coersion- data types can be coerced from one form into another.

Truthy = data types treated as if they are true.
Falsy= data types treated as if they are false.

Due to type coercion, use strict equality operators === and !==.  Results in fewer unexpected values.

Short-circuit values (p.169). *

Loops:
1. For loop (has a counter that runs the loop a specific number of times).
2. While loops run for as long as the condition is true.  
3. Do while loops are similar to while loops, except that they'll always run at least once, even if the condition evaluates to false.

Break stops a loop and tells interpreter to move on to next line of code.

Continue tells the interpreter to stop the current iteration, update, and check the condition again (runs again if true).

Loops are commonly used with arrays.

Avoid infinite loops!  Define all possible variables outside of the loop.  Be sure to return false at some point to break the loop.



