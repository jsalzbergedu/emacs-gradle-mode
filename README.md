emacs-gradle-mode
=================

minor mode for emacs to run gradle from emacs and not have to go to a terminal!

# To Install #

```lisp
(require 'gradle-mode)
```

# How to Use??? #
The prefix keybinding is `C-c C-g` to invoke gradle.  

Adding an `r` will prompt you for the command to run in a new gradle instance.
Addding a `d` will prompt you for the command to run with the gradle **daemon**.

I have preprogrammed the basic keybindings of `build` and `test` only.  

To run normally, the prefix would be `C-c C-g`, and to run in `daemon` use the binding `C-c C-g C-d`.  From there the acronyms of `b` would issue the `build` command and `t` would issue the `test` command.
