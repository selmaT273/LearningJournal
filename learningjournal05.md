Chapter 10 
CSS creates rules that specify what the content of an element should appear as
Block and inline elements
Block level
Looks like they start on a new line
Examples of block level elements are p h1 div
Inline
Flow within text, do not start on a new line
Examples are b, i, img, em, span
Example styles
Boxes
w & h
Borders (color, w, and style)
Background color/images
Position in browser window
Text
Typeface
Size 
Color
Italics, bold, uppercase, lowercase, small caps
Specific
Elements like lists, tables, and forms have specific ways of styling them
CSS gives style rules to HTML elements using a selector and declaration
Selectors
Tell which element the following declaration applies to
Can apply the same rule to more than one element if you separate elements with a comma
Universal selector
*{ }
Type selector
H1, h2, h3 { }
Class selector 
.note { }
Id selector
#introduction { }
Child selector
Descendant selector
Adjacent sibling selector
General sibling selector


Declarations
Says how the selected element should be styled 
2 parts separated by colon
Property and value
Property
Aspects of the element you want to change
Color, font, width, height, border
Value 
Specifies settings you want to use for the chosen properties
Sit inside curly brackets
Specificity
If one selector is more specific than another, the more specific one will take precedence
Inheritance


Color
Background-color sets the specific color for the background of that particular box
You can specify the color in one of three ways
Rgb values
Represented by values for red green and blue as numbers between 0 and 255
Hex codes
Values for RGB but in hexadecimal code
#FFFFFF
Color names
Colors represented by predefined names
Hue
Saturation
Brightness
Contrast
Medium contrast is best for extended periods of reading
Opacity
RGBA -the A represents the value set for opacity
Number between 0.0 and 1.0


Padding property
Separates text from edges of the box to make it easier to read
