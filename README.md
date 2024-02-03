# awesome-terminal-fonts

install this font
pached/Droid+Sans+Mono+Awesome.ttf

verify it is installed

`fc-list | grep "Awe"`

2024-update: `gnome-terminal` cannot set the awsome fonts, use 
1st list the profiles
`dconf dump /org/gnome/terminal/legacy/profiles:/`
get the profile hash
and 
```
dconf write /org/gnome/terminal/legacy/profiles:/:b1dcc9dd-5262-4d8d-a863-c897e6d979b9/font  "'<chosen_font_name> <font_size>'"
ie.
dconf write /org/gnome/terminal/legacy/profiles:/:b1dcc9dd-5262-4d8d-a863-c897e6d979b9/font "'Droid Sans Mono Awesome 12'"
```

