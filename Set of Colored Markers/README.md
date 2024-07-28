# CSS Concepts and Properties

### 1. Title Element and SEO
The ```<title>``` element provides essential information to search engines about the content of a web page. It also displays the title in the following ways:
* In the title bar: When the page is open, the title appears in the title bar of the browser window.
* In the browser tab: The title is displayed in the browser tab and appears as a tooltip when you hover over the tab, even if the tab is inactive.

### 2. Character Encoding: charset
The charset attribute specifies the character encoding used by the document.```UTF-8``` (Unicode Transformation Format – 8-bit) is a widely used character encoding standard in electronic communication, ensuring that text is consistently represented across different systems and platforms.

### 3. Shorthand Margin Property
The margin property in CSS can be specified using shorthand notation. When two values are provided:
* The first value sets the margin-top and margin-bottom.
* The second value sets the margin-left and margin-right.
For example:
```margin: 10px 20px```;
This sets the top and bottom margins to 10px and the left and right margins to 20px.

### 4. Adding Multiple Classes
To apply multiple CSS classes to an element, list the classes in the class attribute, separated by spaces.
For example:
```HTML
<div class="animal dog"></div>
```
This element now has both the animal and dog classes, allowing it to inherit styles from both.

### 5. Color Models
RGB (Red, Green, Blue) Model
The RGB model is used in electronic displays. Colors are created by combining varying intensities of red, green, and blue light, starting from black.
Example of using RGB in CSS:
```color: rgb(255, 0, 0)```; /* Red */
CMYK (Cyan, Magenta, Yellow, Black) Model
The CMYK model is commonly used in printing. It uses four ink colors to produce a wide range of colors on paper.

### 6. Color Wheel and Complementary Colors
A color wheel is a circular diagram representing the relationships between colors. Colors that are opposite each other on the wheel are called complementary colors. When placed side-by-side, complementary colors create strong visual contrast and appear more vibrant.

### 7. Hexadecimal (Hex) Color Values
Hex color values are a way to represent RGB colors in CSS. They start with a # and are followed by six hexadecimal digits, where:
* The first two digits represent red.
* The next two digits represent green.
* The last two digits represent blue.
Example:
```color: #4B5320```; /* A shade of green */

### 8. HSL (Hue, Saturation, Lightness) Color Model
The HSL color model describes colors in terms of:
* Hue: A degree on the color wheel from 0 to 360 (e.g., 0 is red, 120 is green, 240 is blue).
* Saturation: The intensity of the color, ranging from 0% (gray) to 100% (full color).
* Lightness: The brightness of the color, ranging from 0% (black) to 100% (white).
Example:
```color: hsl(120, 100%, 50%)```; /* Pure green */

### 9. Gradients
A gradient creates a smooth transition between colors. The linear-gradient function allows you to specify the direction and colors used.
Example:
background: ```linear-gradient(90deg, red 90%, black)```;
In this example, the gradient transitions from red to black at 90% along the gradient line.

### 10. Opacity and Alpha Channel
Opacity controls the transparency of an element:
* opacity: 0; makes an element fully transparent.
* opacity: 1; makes it fully opaque.
The alpha channel is an extension of the RGB color model, denoted as rgba, where the fourth parameter specifies opacity from 0 (transparent) to 1 (opaque).
Example:
```background-color: rgba(255, 0, 0, 0.5)```; /* Semi-transparent red */

### 11. Block-Level Elements and Display Property
Block-level elements like ```HTML<div>``` by default take up the full width of their container and stack vertically. The default display property for block elements can be changed to other values like inline, inline-block, etc., to alter their layout behavior.

### 12. Borders and Box Shadows
The border and box-shadow properties in CSS allow you to style element borders and add shadows, respectively.
* border-left: Sets the width, style, and color of the left border.
Example:
```border-left: 5px solid red```;
* box-shadow: Adds a shadow effect to an element.
Basic syntax:
box-shadow: offsetX offsetY blurRadius color;
Example with optional spread radius:
```box-shadow: 5px 5px 10px 2px rgba(0, 0, 0, 0.5)```;
* offsetX and offsetY: Determine the position of the shadow.
* blurRadius: Controls the blurring of the shadow edges.
* spreadRadius: Increases or decreases the size of the shadow.
