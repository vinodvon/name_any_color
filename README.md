# name_any_color

A JavaScript library for finding the closest color name to any given color value..
This npm module can be used on any JavaScript framework or environment that supports the CommonJS module system .

## Installation

npm install name_any_color

## Usage

To use "name_any_color", you can import it into your JavaScript code using the following syntax:
const nac = require('name_any_color');

Or, if you're using a framework like ReactJS, AngularJS, or Vue.js, you can import it using one of the following syntaxes:
import nac from 'name_any_color'; // for ReactJS
import \* as nac from 'name_any_color'; // for AngularJS and Vue.js

"name_any_color" provides a function called name() which takes a color value as input (in hex code or RGB format) and returns an array containing the closest color name, its hex code, and a boolean value indicating if the color is an exact match or an approximate match.

Examples
nac.name("#FFA500"); // returns ["#FFA500", "Orange", false]
nac.name("rgb(255, 105, 180)"); // returns ["#FF69B4", "HotPink", false]

The name() function can be useful for displaying color names in a UI element or mapping color values to color names in a database.
