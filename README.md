# name_any_color

A JavaScript library for finding the closest color name to any given color value..
This npm module can be used on any JavaScript framework or environment that supports the CommonJS module system .

## Installation

npm install name_any_color

## Usage

NodeJS
const nac = require('name_any_color');

ReactJS
import nac from 'name_any_color';

AngularJS
import \* as nac from 'name_any_color';

Vue.js
import \* as nac from 'name_any_color';

'''''''''''''''
Here are some example inputs and outputs for each of the() Functions:

'''''''''''''''
|name() Function|

"This function is useful for getting the name of a color given its hex code or RGB value. It could be used, for example, to display the name of a color in a UI element, or to map color values to color names in a database."

Input : nac.name("#FFA500");
Output: ["#FFA500", "Orange", false]

Input : nac.name("rgb(255, 105, 180)");
Output: ["#FF69B4", "HotPink", false]

Input : nac.name("blue");
Output: ["#0000FF", "Blue", true]

Input : nac.name("not a valid color");
Output: ["#000000", "Invalid Color: not a valid color", false]

'''''''''''''''
|rgbToHsl() Function|
"This function is useful for converting RGB colors to HSL colors, which can be more intuitive to work with in certain situations. It could be used, for example, in a graphics or image processing application."

Input : nac.rgbToHsl(255, 0, 0);
Output: [0, 100, 50]

Input : nac.rgbToHsl(0, 128, 0);
Output: [120, 100, 25]

Input : nac.rgbToHsl(0, 0, 255);
Output: [240, 100, 50]

'''''''''''''''
|randomColor() Function|
"This function is useful for generating random colors for use in UI elements or graphics. It could be used, for example, to assign a random color to a user's avatar or to generate random colors for a chart or graph."

Input : nac.randomColor();
Output: "#1B4B3A"

Input : nac.randomColor();
Output: "#6E1C0B"

Input : nac.randomColor();
Output: "#6F546C"

'''''''''''''''
|adjustColor() Function|
"This function is useful for lightening or darkening a color by a specified amount. It could be used, for example, to dynamically adjust the color of a UI element in response to user input or to create variations on a base color for use in a design."

Input : nac.adjustColor("#FF0000", 50);
Output: "#FF3232"

Input : nac.adjustColor("#0000FF", -100);
Output: "#000000"

'''''''''''''''
|contrastRatio() Function|
"This function is useful for calculating the contrast ratio between two colors, which is important for ensuring that text is readable against a background color. It could be used, for example, in a web application to check that the contrast ratio between text and background colors meets accessibility guidelines."

Input : nac.contrastRatio("#000000", "#FFFFFF");
Output: "21.00"

Input : nac.contrastRatio("#FF0000", "#00FF00");
Output: "1.16"

'''''''''''''''
|brightness() Function|
"This function is useful for calculating the brightness of a color, which can be used to sort and filter colors by brightness. It could be used, for example, in a photo editing application to adjust the brightness of an image or to group similar colors together."

Input : nac.brightness("#FF0000");
Output: 76.245

Input : nac.brightness("#00FF00");
Output: 145.66

'''''''''''''''
|saturation() Function|
"This function is useful for calculating the saturation of a color, which can be used to sort and filter colors by saturation. It could be used, for example, in a design tool to help users choose color schemes based on saturation or to create variations on a base color."

Input : nac.saturation("#FF0000");
Output: 100

Input : nac.saturation("#00FF00");
Output: 100

Input : nac.saturation("#808080");
Output: 0

'''''''''''''''
|webSafeColor() Function|
"This function is useful for converting a color to its nearest web-safe color, which ensures that the color will display consistently across different browsers and platforms. It could be used, for example, in a web application to ensure that colors are displayed consistently on different devices or to convert legacy color codes to web-safe equivalents."

Input : nac.webSafeColor("#E63A2E");
Output: "#CC3333"

Input : nac.webSafeColor("#9B59B6");
Output: "#993399"

'''''''''''''''
|isValidColor() Function|
"This function is useful for validating whether a color value is valid, which can prevent errors and ensure that applications function correctly. It could be used, for example, to validate user input in a form or to check that a color value is valid before performing operations on it."

Input : nac.isValidColor("#FF0000");
Output: true

Input : nac.isValidColor("#notacolor");
Output: false

```

```

```

```
