# Rofi config for neon-84

Files present: 

* rofi.sh: runs rofi with appropriate arguments
* rofi-Xresources: Xresources file to set colors / options for rofi

Set rofi.sh to be triggered by your preferred keyboard shortcut,
I use <Alt>Space.  

Load rofi-Xresources when your desktop session starts.  That can be
accomplished by coping the contents of rofi-Xresources to the end of
your ~/.Xresources file. It can also be accomplished by adding this 
command to your session startup process:

   xrdb -m rofi-Xresources  


