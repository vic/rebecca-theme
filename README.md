# Rebecca, the purple turtle.

<a href="http://spacemacs.org"><img src="https://cdn.rawgit.com/syl20bnr/spacemacs/442d025779da2f62fc86c2082703697714db6514/assets/spacemacs-badge.svg" alt="Made with Spacemacs"></a>

[![MELPA](https://melpa.org/packages/rebecca-theme-badge.svg)](https://melpa.org/#/rebecca-theme)

Rebecca is a dark emacs theme with purple/violet colors.


### Screenshots

![rebecca](https://cloud.githubusercontent.com/assets/331/21472087/a4d40b08-ca8e-11e6-8715-a3e11484506e.png)
![rebecca2](https://cloud.githubusercontent.com/assets/331/21472090/b359061a-ca8e-11e6-8320-fad08268e883.png)
![rebecca3](https://cloud.githubusercontent.com/assets/331/21472128/71d7d944-ca90-11e6-80f6-524ac4807761.png)

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
