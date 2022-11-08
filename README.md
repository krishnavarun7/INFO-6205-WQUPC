

Functions: 
You may construct complicated operations on SassScript data using functions, which you can then reuse throughout your stylesheet.

A function that alters the text color depending on the backdrop color has been defined.
In _functions.scss, the functions are demonstrated. 

Variables: Instead of taking the value with you every time, variables allow you to keep a value in a name and utilize it anywhere.
There are certain variables that can store colors.
The _variables.scss file uses a number of variables. 

Nesting:
Using the same visual hierarchy as your HTML, Sass will allow you to stack your CSS selectors.
Numerous places, including the about section, have introduced nesting.
For examples, see style.scss. 

Mixins: Mixins allow you to construct styles that can be used in several locations across your CSS.
The Mixins are illustrated in _mixins.scss.
The 'p' tag in the menu, about, and contact sections is an example of how they are utilized in this assignment to change the text format.
(Text-Plot Mixin)

Interpolation: To integrate the outcome of a SassScript expression into a section of CSS, interpolation can be used practically anywhere in a Sass stylesheet.
Simply enclosing an expression in # wherever.
Due to its length and frequent usage, we employed it for text-decoration purposes.
The Mixins are stylishly illustrated.

Flexbox Layout: Flexbox was created for one-dimensional layout
Flexbox has only really been used for the nav and about sections' icon sets. 

Grid Layout: The grid was created for simultaneous rows and columns in a two-dimensional layout.

Grid has only really been used in the menu and contact sections.


Selectors of placeholders:
It resembles a class selector in appearance and behavior, but it begins with a% and isn't part of the CSS output.
We used it to adjust the text size.
the _placeholder.scss file
Color, among other custom attributes, are included.

