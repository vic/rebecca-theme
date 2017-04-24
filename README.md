# Rebecca, the purple turtle.

<a href="http://spacemacs.org"><img src="https://cdn.rawgit.com/syl20bnr/spacemacs/442d025779da2f62fc86c2082703697714db6514/assets/spacemacs-badge.svg" alt="Made with Spacemacs"></a>

[![MELPA](https://melpa.org/packages/rebecca-theme-badge.svg)](https://melpa.org/#/rebecca-theme)
[![help maintain this lib](https://img.shields.io/badge/looking%20for%20maintainer-DM%20%40vborja-663399.svg)](https://twitter.com/vborja)



Rebecca is a dark emacs theme with purple/violet colors.


### Screenshots

#### GUI

[![screen shot 2016-12-27 at 2 13 55 pm](https://cloud.githubusercontent.com/assets/331/21507655/e4e04196-cc3f-11e6-9dd4-4b26d562182f.png)](https://github.com/vic/rebecca-theme/issues/1#emacsplus-on-osx)

#### Terminal
[![screen shot 2017-04-24 at 3 30 44 pm](https://cloud.githubusercontent.com/assets/331/25357351/1a07cb80-2903-11e7-9bd1-1abf9c093d03.png)](https://github.com/vic/rebecca-theme/issues/1#running-on-terminal)



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
