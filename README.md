# Rebecca, the purple turtle.

<a href="http://spacemacs.org"><img src="https://cdn.rawgit.com/syl20bnr/spacemacs/442d025779da2f62fc86c2082703697714db6514/assets/spacemacs-badge.svg" alt="Made with Spacemacs"></a>

[![MELPA](https://melpa.org/packages/rebecca-theme-badge.svg)](https://melpa.org/#/rebecca-theme)



Rebecca is a dark emacs theme with purple/violet colors.

Works best with [this soundtrack](https://www.youtube.com/watch?v=rDBbaGCCIhk) and [Liam Wong's photos](http://liamwon9.tumblr.com/) as background.


### Screenshots

#### GUI

[![screen shot 2016-12-27 at 2 13 55 pm](https://cloud.githubusercontent.com/assets/331/21507655/e4e04196-cc3f-11e6-9dd4-4b26d562182f.png)](https://github.com/vic/rebecca-theme/issues/1#emacsplus-on-osx)

#### Terminal
[![screen shot 2018-04-01 at 11 37 43 pm](https://user-images.githubusercontent.com/331/38183422-f26862f4-3605-11e8-9209-335c4b04325e.png)](https://github.com/vic/rebecca-theme/issues/1#running-on-terminal)



[more screenshots](https://github.com/vic/rebecca-theme/issues/1)

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



