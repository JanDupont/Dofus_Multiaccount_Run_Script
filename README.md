# Dofus_Multiaccount_Run_Script
simple script to walk or close UI windows on multiple characters with a single click.

This makes questing with a team much more comfortable.  
Wasn't bannable in the past, use at own risk tho.

# How to use
Add one line per character, exchange <CHARACTERNAME> with your character name (without <>)
```ahk
ControlClick, x%xpos% y%ypos%, <CHARACTERNAME>
```
The last one in the line will be the focused window after the script ran (so most likely put your main last).
