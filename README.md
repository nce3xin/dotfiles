# Nce3xin's dotfiles
This repo is my dotfiles using i3wm in linux.

## Table of Contents
- [Screenshot](#Screenshot)
- [Components](#Components)
- [Key Bindings](#Key-Bindings)
- [The best way to store your dotfiles](#The-best-way-to-store-your-dotfiles)

## Screenshot
![](Screenshots/sc.png)

## Components

### i3-gaps
[i3-gaps](https://github.com/Airblader/i3) -- i3 with more features. i3-gaps is a fork of i3wm, a tiling window manager for X11. It is kept up to date with upstream, adding a few additional features such as gaps between windows.

### Terminal
- [Tilix](https://github.com/gnunn1/tilix) is used as the default terminal.

### Shell
- Throw away your bash and embrace the [zsh](https://www.zsh.org/).
- [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh). Oh My Zsh is an open source, community-driven framework for managing your zsh configuration.

### Others
- [neofetch](https://github.com/dylanaraps/neofetch). Neofetch is a command-line system information tool. Neofetch displays information about your operating system, software and hardware in an aesthetic and visually pleasing way.
- [polybar](https://github.com/jaagr/polybar). Polybar aims to help users build beautiful and highly customizable status bars for their desktop environment, without the need of having a black belt in shell scripting. A collection of polybar themes can be found here: [polybar themes](https://github.com/adi1090x/polybar-themes). I use the polybar-4 theme.
- [i3lock-fancy](https://github.com/meskarune/i3lock-fancy). This is an i3lock bash script that takes a screenshot of the desktop, blurs the background and adds a lock icon and text.
- [ranger](https://github.com/ranger/ranger). Ranger is a console file manager with VI key bindings. It provides a minimalistic and nice curses interface with a view on the directory hierarchy.
- [feh](https://github.com/derf/feh). Feh is a light-weight, configurable and versatile image viewer. Here feh is used to set the wallpaper.
- [rofi](https://github.com/davatorium/rofi). Rofi, a window switcher, application launcher and dmenu replacement.
- [visual studio code](https://code.visualstudio.com/). A well-known IDE-like editor for developers.
- [google chrome](https://www.google.com/chrome/). Needless to say, the best browser.
- [compton](https://github.com/chjj/compton). Compton is a compositor for X, supporting terminal transparency.

## Key Bindings
### Which key is mod key ?
- The windows key
### Open new terminal
- mod + enter
### Close window
- mod + shift + q
### change focus
- mod + up / down / left / right
### move focused  window
- move left: mod + shift + left
- move right: mod + shift + right
- move up: mod + shift + up
- move down: mod + shift + down
### split window
- split in horizontal orientation: mod + h
- split in vertical orientation: mod + v
### fullscreen mode for the focused container
- mod + f
### toggle tiling / floating
- mod + shift + space
### change focus between tiling / floating windows
- mod + space
### switch the workspace
- mod + num
### move focused container to workspace
- mod + shift + num
### reload the configuration file
- mod + shift + c
### restart i3 in place
- mod + shift + r
### exit i3
- mod + shift + e
### resize window
- mod + r, then up / down / left / right. Esc to exit resize mode.
### launch applications
- mod + d, then a rofi window will pop up.

## The best way to store your dotfiles
[The best way to store your dotfiles: A bare Git repository](https://developer.atlassian.com/blog/2016/02/best-way-to-store-dotfiles-git-bare-repo/). This repo uses this method.

