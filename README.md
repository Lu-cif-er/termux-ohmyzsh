# Termux-ohmyzsh

A fork from [oh-my-termux](https://github.com/4679/oh-my-termux). It makes the app more colorful.

Termux-ohmyzsh implements oh-my-zsh and [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) on your Termux app, as well as some color schemes (most are from [Gogh](https://github.com/Mayccoll/Gogh)), and some Powerline fonts (ported from [powerline/fonts](https://github.com/powerline/fonts)). Default set is agnoster for oh-my-zsh, Tango for color scheme, and Ubuntu font.



**This repo requires Termux official repo. In mainland China, you may need to add Termux app to your proxy list in order to gain access to Termux official repository.**

## Install:
```shell
sh -c "$(curl -fsSL https://github.com/Cabbagec/termux-ohmyzsh/raw/master/install.sh)"
```

## Change color scheme:
Run `chcolor` to change color scheme, or run:
```shell
~/.termux/colors.sh
```
## Change font:
Run `chfont` to change font, or run:
```shell
~/.termux/fonts.sh
```

## Example
Tango color scheme + agnoster oh-my-zsh theme + Ubuntu font:

![](./termux-ohmyzsh.png)
