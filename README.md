# Visualizer

Transforms cava music visualizer in a cool desktop decoration.

Author: GuidoFe

![Screenshot](https://i.imgur.com/00M3lBQ.png)

# Usage:
 First of all, set the parameters at the beginning of the file and save the changes. 
 
 To start the visualizer, execute this script. To stop it, execute this script again.

# Dependencies (and credits): 
- [xdotool](https://github.com/jordansissel/xdotool)
- [cava](https://github.com/karlstav/cava)
- [devilspie](https://github.com/plaes/devilspie)
- URxvt

# Description:

This script starts the cava music visualizer on a transparent backround through URxvt
('cause it's easy to customize and supports transparent foreground and background). It
then uses devilspie to strip it of his window decorations and rules, move it to the 
right place and resize it.
