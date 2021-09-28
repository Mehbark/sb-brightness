# sb-brightness
dwmblock that shows the current backlight brightness, and can be clicked to change the brightness with the included script
## Requires `light`, which can be installed with `yay`
## Installation:
```
curl -s https://raw.githubusercontent.com/Mehbark/sb-brightness/main/install.sh | sh -s
```
Then just add the line 
```
{"",	"sb-brightness",	0,	24},
```
in your config.h, recompile dwmblocks, renew dwm and everything should work.
if you are using a different file structure the install script will not work, so figure things out yourself
