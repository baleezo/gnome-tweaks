# Change the top bar panel clock font size
vim ~/.local/share/themes/pragmalin/gnome-shell/gnome-shell.css
```
@import url("resource:///org/gnome/theme/gnome-shell.css");


stage {
  /*font-family: Noto Sans Mono;*/
  font-size: 22px;
}


#panel .clock-display {
  padding: 8px 0;
  font-size: 28px;
}
```
sudo apt install gnome-tweaks
sudo apt install gnome-shell-extensions

gnome-tweaks/Extensions -> enable user themes
gnome-tweaks/Appearance/shell -> select Paragmalin
