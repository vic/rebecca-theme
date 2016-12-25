# Rebecca, the purple turtle.

<a href="http://spacemacs.org"><img src="https://cdn.rawgit.com/syl20bnr/spacemacs/442d025779da2f62fc86c2082703697714db6514/assets/spacemacs-badge.svg" alt="Made with Spacemacs"></a>

[![MELPA](https://melpa.org/packages/rebecca-theme-badge.svg)](https://melpa.org/#/rebecca-theme)

Rebecca is a dark emacs theme with purple/violet colors.


### Screenshot

![Rebecca](https://github.com/vic/rebecca-theme/raw/master/rebecca.png)

![Rebecca](https://github.com/vic/rebecca-theme/raw/master/rebecca2.png)


# Installation

#### With [Spacemacs](http://spacemacs.org)

Add the following two settings on your `~/.spacemacs` file

```emacs-lisp
dotspacemacs-additional-packages '(
   rebecca-theme
)

dotspacemacs-themes '(
   rebecca
)
```

#### From [MELPA](https://melpa.org/#/rebecca-theme)

```
M-x package-install [RET] rebecca-theme [RET]
```

Otherwise, put rebecca-theme.el in either the custom-theme-directory or load-path.

You can apply the theme via M-x customize-themes, or make it the default by adding the following to your Emacs configuration:

```emacs-lisp
   (load-theme #'rebecca t)
```   
