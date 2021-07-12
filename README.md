# My build of dwm

[dwm](https://dwm.suckless.org/) is a dynamic window manager for X. 

## Features and patches

### Features

+ Status bar with my build of [dwmblocks](https://github.com/ayylouu/dwmblocks)
+ **no keybindings for programs** I use [sxhkd](https://github.com/baskerville/sxhkd/) for that [my sxhkd config](https://github.com/ayylouu/dotfiles/tree/master/.config/sxhkd)

### Patches

+ **swallow** Clients marked with `isterminal` in config.h swallow a window opened by any child process
+ **actualfullscreen** Full screen with `super+shift+f`
+ **fullgaps** adds gap between client windows. `super+shift+p`/`super+p` to increase/decrease gaps with
+ **movestack** move clients around in the stack with `super+shift+j` and `super+shift+k`
+ **statuscmd** for a clickable status bar

## Installation

```bash
git clone https://github.com/ayylouu/dwm.git
cd dwm/
sudo make install
```

