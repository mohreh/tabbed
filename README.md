# tabbed - generic tabbed interface

tabbed is a simple tabbed X window container.

## Requirements

In order to build tabbed you need the Xlib header files.

## Installation

    sudo make install

## Running tabbed

See the man page for details.

# Screenshots

<img src="https://ik.imagekit.io/mohreh/GitHub_Media/alacritty-tabbed_Pqf4geX7F.png?ik-sdk-version=javascript-1.4.3&updatedAt=1644959698796">

# Quick use

     open alacritty terminal with tabbed mode :  "tabbed alacritty --embed"  (make a keybind for this)

     open new tab : Ctrl + shift + enter <br>

     to keep a single instance of opened terminal u can use this command in ur keybinds : "wmctrl -x -a "tabbed" || tabbed alacritty --embed"

check the config.h for few more keybinds

- NOTE : tabs will open appear only if more than one alacritty window is opened .
- customize tabbed colors via xresources

```
  example :

  tabbed.selbgcolor:   #282c34
  tabbed.selfgcolor:   #d6d8eb

  tabbed.normfgcolor:  #9294a8
  tabbed.normbgcolor:  #353b45

```

# Credits

@6gk for centered title patch
