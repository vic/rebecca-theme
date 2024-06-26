#  The future was cooler in the 80's. 

<a href="http://spacemacs.org"><img src="https://cdn.rawgit.com/syl20bnr/spacemacs/442d025779da2f62fc86c2082703697714db6514/assets/spacemacs-badge.svg" alt="Made with Spacemacs"></a>

[![MELPA](https://melpa.org/packages/rebecca-theme-badge.svg)](https://melpa.org/#/rebecca-theme)



Rebecca is a dark emacs theme with purple/violet colors.

Works best with [this soundtrack](https://www.youtube.com/watch?v=rDBbaGCCIhk) and [Liam Wong's photos](http://liamwon9.tumblr.com/) as background.


### Screenshots

# Rebecca, the purple turtle.

![screen shot 2016-12-27 at 2 13 55 pm](https://cloud.githubusercontent.com/assets/331/21507655/e4e04196-cc3f-11e6-9dd4-4b26d562182f.png)

## emacsplus on OSX 

![screen shot 2016-12-27 at 2 21 45 pm](https://cloud.githubusercontent.com/assets/331/21507653/e4bc1708-cc3f-11e6-976a-ccea9d94e584.png)
![screen shot 2016-12-27 at 2 17 04 pm](https://cloud.githubusercontent.com/assets/331/21507654/e4d1f7d0-cc3f-11e6-97c6-aeb536221013.png)
![rebecca](https://cloud.githubusercontent.com/assets/331/21472090/b359061a-ca8e-11e6-8320-fad08268e883.png)

## running on terminal 

##### TERM=xterm-24bits

[on tmux in iterm2 with emacs patched for 24bit colors, vimpowerline](https://gist.github.com/vic/fa58918694af3b3767fbc7dc22cbc406)

![screen shot 2018-04-01 at 11 56 34 pm](https://user-images.githubusercontent.com/331/38183752-7d26debe-3608-11e8-8809-fc09da5dc979.png)

![screen shot 2018-04-01 at 11 37 43 pm](https://user-images.githubusercontent.com/331/38183422-f26862f4-3605-11e8-9209-335c4b04325e.png)


##### TERM=screen-256color

![screen shot 2017-04-24 at 3 23 56 pm](https://cloud.githubusercontent.com/assets/331/25357349/17ba8214-2903-11e7-9cc0-03229e053da9.png)
![screen shot 2017-04-24 at 3 30 44 pm](https://cloud.githubusercontent.com/assets/331/25357351/1a07cb80-2903-11e7-9bd1-1abf9c093d03.png)

## on Android inside termux

![screenshot_20180129-030747](https://user-images.githubusercontent.com/331/35502267-17bf1e34-04a2-11e8-9285-5764429901be.png)





[Rebecca at emacsthemes.com](https://emacsthemes.com/themes/rebecca-theme.html)


# Installation

#### With [Spacemacs](http://spacemacs.org)

Rebecca is now included in spacemacs' [theme-megapack](https://github.com/syl20bnr/spacemacs/tree/develop/layers/%2Bthemes/themes-megapack).

To set it as default just add it to the top of themes preference on your ~/.spacemacs file:

```emacs-lisp
dotspacemacs-themes '(
   rebecca
)
```

Or activate it using the theme switcher:

```
SPC T s rebecca [RET]
```

#### From [MELPA](https://melpa.org/#/rebecca-theme)

```
M-x package-install [RET] rebecca-theme [RET]
M-x load-theme [RET] rebecca [RET]
```

#### Manually

put rebecca-theme.el in either the custom-theme-directory or load-path.

You can apply the theme via M-x customize-themes, or make it the default by adding the following to your Emacs configuration:

```emacs-lisp
   (load-theme #'rebecca t)
```   

## Term color scheme

The Rebecca color scheme has been [ported to `iterm2` and many other terminals](https://github.com/mbadolato/iTerm2-Color-Schemes).

Also, some [base16-rebecca](https://github.com/vic/base16-rebecca) iterm colors can be [found here](https://github.com/martinlindhe/base16-iterm2/tree/master/itermcolors)

## Emacs terminal 24bit colors

For getting the best experience on terminal, I'd recommend to use an emacs patched with 24bit color support.

Instructions for getting emacs with 24bit colors can be [found here](https://gist.github.com/vic/fa58918694af3b3767fbc7dc22cbc406)

## Wezterm

Wezterm includes the rebbeca theme by default, to enable it use something like the following on your `$XDG_HOME/.config/wezterm/wezterm.lua` file:

```lua
local wezterm = require 'wezterm'
local config = {}
config.color_scheme = 'rebecca'
return config
```

## Zellij

A port of this theme for zellij can be [found here](https://github.com/vic/zellij-rebecca-theme)


