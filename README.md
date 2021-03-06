# dotfiles

[![Circle CI](https://circleci.com/gh/yutakatay/dotfiles.svg?style=shield&circle-token=ad0dde00aa79d62e4d8becd310868691b0e82995)](https://circleci.com/gh/yutakatay/dotfiles)
[![Code Climate](https://codeclimate.com/github/yutakatay/dotfiles/badges/gpa.svg)](https://codeclimate.com/github/yutakatay/dotfiles)
[![Test Coverage](https://codeclimate.com/github/yutakatay/dotfiles/badges/coverage.svg)](https://codeclimate.com/github/yutakatay/dotfiles/coverage)
[![Issue Count](https://codeclimate.com/github/yutakatay/dotfiles/badges/issue_count.svg)](https://codeclimate.com/github/yutakatay/dotfiles)
![](http://img.shields.io/badge/license-MIT-blue.svg)
![](https://img.shields.io/badge/OS-arch%2Fubuntu%2Fcent%2Ffedora%2Falpine-blue.svg)
[![Join the chat at https://gitter.im/yutakatay/dotfiles](https://badges.gitter.im/yutakatay/dotfiles.svg)](https://gitter.im/yutakatay/dotfiles?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


## Overview

My home dotfiles

![overview](https://raw.githubusercontent.com/yutakatay/img/master/dotfiles/overview.png)


## Install

1. Download  
`$ git clone https://github.com/yutakatay/dotfiles.git`
2. Install  
`$ ./dotfiles/.bin/dotsinstaller.sh`  
 (NoGUI)  
`$ ./dotfiles/.bin/dotsinstaller.sh --no-gui`
3. vim plugin install  
`$ vi +PlugInstall` or `:PlugInstall` after vim boot
4. zsh plugin install  
`$ exec zsh`
5. Enjoy!


### Temporary Install

If you do not want to dirty your home directory

1. Download
```
$ mkdir /tmp/tmphome
$ cd /tmp/tmphome
$ git clone https://github.com/yutakatay/dotfiles.git
```
2. Set HOME environment temporary  
`export HOME=/tmp/tmphome`
3. Install  
`$ ./dotfiles/.bin/dotsinstaller.sh`  
 (NoGUI)  
`$ ./dotfiles/.bin/dotsinstaller.sh --no-gui`
4. vim plugin install  
`$ vi +PlugInstall` or `:PlugInstall` after vim boot
5. zsh plugin install  
`$ exec zsh`


## Components

- zsh
- neovim(vim)
- tmux
- i3-gaps(optional)


## Usage

### Frequently used shortcuts

#### tmux

|key|action|
|---|---|
|Alt-h/j/k/l|switch window|
|Alt-j|close window|
|Alt-k|create window|
|S-Up/Down/Left/Right|switch pane|

#### i3

|key|action|
|---|---|
|Mod-h/j/k/l|switch window|
|Mod-S-h/j/k/l|move window|
|Mod-C-S-h/j/k/l|move workspace|

