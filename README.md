Extended Backus-Naur Form Mode
==============================

Astonishingly, Emacs does not already include a highlighting mode for
Extended Backus-Naur Form texts. Who doesn't want a little more angry
fruit salad in their lives, right? So here we are with a dead simple
syntax highlighting mode for EBNF texts.

So get to it! Define some syntaxes!

Modification by MechaMagpie
---------------------------

Rewrote mode definition to make ebnf-mode derive from prog-mode, so that prog-mode-hook fires and I don't have to manually turn on fci-mode. Yes, I am that lazy.
