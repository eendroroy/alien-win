# alien-win

[![GitHub tag](https://img.shields.io/github/tag/eendroroy/alien-win.svg)](https://github.com/eendroroy/alien-win/tags)

[![Contributors](https://img.shields.io/github/contributors/eendroroy/alien-win.svg)](https://github.com/eendroroy/alien-win/graphs/contributors)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/eendroroy/alien-win/master.svg)](https://github.com/eendroroy/alien-win)
[![license](https://img.shields.io/github/license/eendroroy/alien-win.svg)](https://github.com/eendroroy/alien-win/blob/master/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/eendroroy/alien-win.svg)](https://github.com/eendroroy/alien-win/issues)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/eendroroy/alien-win.svg)](https://github.com/eendroroy/alien-win/issues?q=is%3Aissue+is%3Aclosed)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/eendroroy/alien-win.svg)](https://github.com/eendroroy/alien-win/pulls)
[![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/eendroroy/alien-win.svg)](https://github.com/eendroroy/alien-win/pulls?q=is%3Apr+is%3Aclosed)

This is a port of [alien](https://github.com/eendroroy/alien) theme for windows (on cygwin).

**For details see the original [readme](https://github.com/eendroroy/alien/README.md)

## Requirements

- zsh (obviously)
- powerline patched fonts [**see here**](https://github.com/powerline/fonts)

## Installation

Add the following line to your .zshrc depending on your zsh plugin manager

##### [antigen](https://github.com/zsh-users/antigen):

    antigen theme eendroroy/alien-win alien-win

##### [zgen](https://github.com/tarjoilija/zgen):

    zgen load eendroroy/alien-win

##### [zplug](https://github.com/zplug/zplug):

    zplug "eendroroy/alien-win"

##### [oh-my-zsh: Overriding and Adding Themes](https://github.com/robbyrussell/oh-my-zsh/wiki/Customization#overriding-and-adding-themes)

##### Manually clonning

```bash
git clone https://github.com/eendroroy/alien-win.git
cd alien-win
git submodule update --init --recursive
```

Add the following line to your `~/.zshrc`

```bash
source ~/alien-win/alien-win.zsh
```

## Libraries Used

- ['256color'](https://github.com/chrissicool/zsh-256color) by **[@chrissicool](https://github.com/chrissicool)**
- ['promptlib-zsh'](https://github.com/eendroroy/promptlib-zsh) by **[@eendroroy](https://github.com/eendroroy)**

## Author

* **indrajit** - *Owner* - [eendroroy](https://github.com/eendroroy)

## License

The project is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
