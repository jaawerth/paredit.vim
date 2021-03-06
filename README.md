# paredit.vim fork for proper Fennel support

This is a fork of https://github.com/vim-scripts/paredit.vim with a simple modification to
add proper [Fennel](https://github.com/bakpakin/Fennel) support for `[]{}` by extending the
existing support for Clojure, Scheme, and Racket to apply to Fennel.

It's intended as a placeholder until I can re-implement paredit in Fennel itself for use in neovim
(and vim with Lua enabled).

## Original paredit README

This is a mirror of http://www.vim.org/scripts/script.php?script_id=3998

Paredit performs structured editing of Lisp S-expressions in Vim. Paredit.vim is similar to paredit.el for Emacs. Paredit Mode tries to maintain the balanced state of matched characters (parenthesis marks, square and curly braces, double quotes). Matched characters are inserted and removed in pairs, also when working with a block of text (well, mostly). Paredit also implements many paredit.el s-expression handling functions, like Split/Join/Wrap/Splice/Raise. Slurpage and Barfage known from Emacs is also possible but in a different fashion: you don't move the list element in or out of the list, rather you move the opening or closing parenthesis over the element or sub-list.

Paredit.vim is also part of the Slimv plugin (http://www.vim.org/scripts/script.php?script_id=2531). Slimv is a SWANK client for Vim, similarly to SLIME for Emacs. Paredit.vim is extracted from Slimv for users who want to use a different SWANK client or don't need a SWANK client at all. In case you need structured editing together with the SWANK functionality then please install Slimv instead, you don't need to additionally install Paredit.

For more information see the included documentation.
