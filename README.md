# i3-config (v4.23)

update to the latest version on mint:

https://askubuntu.com/questions/1415720/ubuntu-22-04-jammy-jellyfish-cannot-install-i3-gaps

dependencies:

- nitrogen (wallpaper)
- pavucontrol (audio)
- ulauncher (user-themes folder is for this launcher)
- compton (compositor)
- lxapperance (system theme)

*remember to add a dot in the i3status.conf and Xmodmap*

*for the xmodmap work permanently you have to modify the xinitrc file in ```/etc/X11/xinit```, adding ```usermodmap=$HOME/.Xmodmap```.*
