# Sway-configs-
personal configuration for Sway Wm

Awsome icons 4 for waybar icons. 
Doom Emacs
Gruv-box factory. 

Merge gruvbox wallpapers into wallpapers files. 

Themes: GTK theme: 
https://github.com/sainnhe/gruvbox-material-gtk
https://github.com/salimundo/Pop-gruvbox

Icons: 
gruvbox icons:https://www.opencode.net/adhe/gruvboxplasma 
also found on the KDE store with a quick search. 

Firefox ricing: 
-Firefox halo: in the User Chrome Css file, remove this bit(the navigator-toolbox):  
/* Removes the border below the bookmarks toolbar */
#navigator-toolbox {
	border: none !important;
}

changing the colours to guvbox in the userContent.css: 
(this is still the defaults, not gruvbox, edit the colour scheme at a later date)
/* This theoretically should make it so that you can just change the colors from here */
body {
  --main-color: #1a1a1a;
  --private-main-color: #261010; /* This one does not work for some reason*/
  --main-accent-color: #b24747;
  --glow-color: #993d3d;
  --newtab-textbox-background-color: var(--main-accent-color);
}

-wdisplay as gui replacement for Arandr. 
-snaps: put this: systemctl enable snapd into the .zshrc file. 






