A constructor that takes an object of values, or a CSS color string in either rgb, rgba, hsl, hsla or hex formats, and creates an object that has methods for format conversion and color manipulation.


Use

var color1 = Color('hsl(84,20%,12%)');
var color2 = Color({ r: 0.6, g: 0.6, b: 0.8 });
var color3 = Color('rgba(200,220,255,0.44)');


Methods

.rgbString()

Returns string in the form 'rgb([0-255],[0-255],[0-255])',

.rgbaString()

Returns string in the form 'rgbaString([0-255],[0-255],[0-255],[0-1])'

.hexString()

Returns string in the form '#[00-ff][00-ff][00-ff]'