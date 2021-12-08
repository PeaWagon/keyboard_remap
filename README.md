# Keyboard remapping

Here is the link that I used for reference material: [StackOverflow](https://askubuntu.com/questions/325272/permanent-xmodmap-in-ubuntu-13-04/347382#347382?newreg=4eb097870a15490ebbe39d78412f9797) and [UbuntuDocs](https://help.ubuntu.com/community/Custom%20keyboard%20layout%20definitions?action=show&redirect=Howto%3A+Custom+keyboard+layout+definitions)

## General Steps

1. Make a backup of the default file: `sudo cp /usr/share/X11/xkb/symbols/pc /usr/share/X11/xkb/symbols/pc.backup`
2. Edit the pc file: `sudo nano /usr/share/X11/xkb/symbols/pc`
3. Swap keybindings as needed (for me, it was PgUp with Home and PgDn with End).
