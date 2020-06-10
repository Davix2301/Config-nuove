Config di i3, i3status e altra roba.
Don't KANG PLOX
roba da installare/fare:
brightnessctl, NON INSTALLARE XF86-VIDEO-INTEL, la roba di vaapi


per il tap to click: 
sudo nano /etc/X11/xorg.conf.d/90-touchpad.conf

Section "InputClass"
        Identifier "touchpad"
        MatchIsTouchpad "on"
        Driver "libinput"
        Option "Tapping" "on"
        Option "TappingButtonMap" "lrm"
        Option "NaturalScrolling" "on"
        Option "ScrollMethod" "twofinger"
EndSection

usare nmtui per il wifi
