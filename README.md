LightDM Webkit LinuxLite Theme
==============================

A fork of a fork.
This is a LightDM webkit greeter theme for LinuxLite. Based on [LightDM-Webkit-MacOSX-Theme](http://github.com/Wattos/LightDM-Webkit-MacOSX-Theme) and [lightdm-webkit-archlinux-theme](https://github.com/shosca/lightdm-webkit-archlinux-theme)

Location details
================

The configuration file for lightdm.conf:

<pre>
/etc/lightdm/lightdm.conf
</pre>

Change the 'greeter-session' value to 'lightdm-webkit-greeter' in lightdm.conf:

<pre>
[SeatDefaults]
greeter-session=lightdm-webkit-greeter
user-session=xfce
#autologin-user=yourname
allow-guest=false
</pre>

The theme is installed to:

<pre>
/usr/share/lightdm-webkit/themes/linuxlite
</pre>

Edit the /etc/lightdm/lightdm-webkit-greeter.conf file to:

<pre>
webkit-theme=linuxlite
</pre>

The theme will change upon reboot.
