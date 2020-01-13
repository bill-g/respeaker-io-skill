## Respeaker Pixel Ring
Use respeaker pixel ring

## Description
This skills supports the led pixel ring of seeedstudio respeaker mic array v2.

Install with:
mycroft-msm install https://github.com/bill-g/respeaker-io-skill.git

Note: by default, the libraries used will not have the correct access to the usb respeaker. To resolve add the following udev rule (I added to /etc/udev/rules.d/99-com.rules):
SUBSYSTEM=="usb", ATTRS{idVendor}=="2886", ATTRS{idProduct}=="0018", GROUP="plugdev", MODE="0666"

## Examples
 - "Enable pixel ring"
 - "Disable pixel ring"


## Credits
Dominik (@domcross)


