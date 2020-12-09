# CSS

## Class Notes

- CSS is style portion of webpage
- CSS: Cascading Style Sheets
- How differ from HTML? Comes after, uses syntax
- Reads from top to bottom, includes values like size
- Can add directly into HTML doc or have own page
- Now only really do own doc - scalability - can change colors across full site and all pages
- Scope of responsibility
- ID or class important to target different area of webpage

## Ch 10: Introducing CSS

- remember box vs inline elements (b, l, img, span)
- box styling - width, height, border, background, position
- text styling - font, size, color, italics etc
- other - lists, tables, forms
- CSS rule = selector + declaration
- selector = what element, can be multiple
- declaration = how styled. prooperty + value, separated by a colon :
- declarations sit inside curly brackets `{example}` and made up of property and value, separated by colon
- can separate several properties in one declaration each separated by a semi-colon
- properties = aspect of element you want to change (ex: font-family)
- value - settings you choose (ex: Arial)
- put CSS in head with `<link href="path to CSS file" type="type of doc, value should be text/css" rel="stylesheet" />`
-to put CSS inside page `<style type="text/css">` in head
- CSS Selectors on page 238
- Precedence given to : last rule, most specific rule, or add !important after any property that should take precedence
- inherited properties - font family
- non inherited properties - background color or border
- can force properties to inherit bu using inherit in value of properties
- different browsers display css differently (browser quirk or CSS bug) - use test site before deploy

## Ch 11: Color

- 3 ways: RGB (`rgb(100,100,90)`), Hex Codes (`#ee3e80"`), Color Names
`/* comment */` - way to add comment in CSS file
- RGB values between 0 and 255
- Hue - similar to color. Expressed as angle between 0 and 360 degrees on color wheel
- Saturation - amount of gray in a color. max saturation = no gray, min saturation = mostly gray, expressed as percentage
- Brightness = how much black in a color vs Lightness = offers both black and white (0% is white, 50% is normal, and 100% is black)
- Contrast - if text is light on dark background, increase height between lines and weight of font to make easier to read
- Opacity - between 0.0 and 1.0
- RBGA 4th value is opacity - doesn't affect child elements
- HSL Colors - Hue, Saturation, Lightness
- Older browsers don't recognize HSL or HSLA - add extra rule specifying color with RBG, Hex or Color Name BEFORE HSL or HSLA rule as fallback
- HSL ex: '<hsl(0,0%,78%)>'
- HSLA adds transparency. a stands for Alpha. Number between 0 and 1.0. Ex: .5 is 50% transparency

To navigate back to the main page click [here](https://hmay1415.github.io/reading-notes/)
