# sb-brightness
dwmblock that shows the current backlight brightness, and can be clicked to change the brightness with the included script
## Requires `light`, can be installed with `yay`
## Installation:
```
git clone https://github.com/mehbark/sb-brightness
sh install.sh
```
Then just add the line 
```
{"",	"sb-brightness",	0,	24},
```
in your config.h, renew dwm and everything should work if you are using a different file structure the install script will not work, but you can figure things out yourself
