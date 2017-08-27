# Grove-OLED

```
var LCD = require('jsupm_i2clcd');

var myLcd = new LCD.SSD1327 (1, 0x3C);

myLcd.setCursor(1, 0);
myLcd.setGrayLevel(12);
myLcd.write('Hello World');

setTimeout(function(){
	myLcd.clear();
},3000)
```
