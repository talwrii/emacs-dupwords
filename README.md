# dumpwords.el

A fork of [Stephen Eglen's](http://www.damtp.cam.ac.uk/user/sje30/emacs/) `dupwords.el` found [here](http://www.damtp.cam.ac.uk/user/eglen/emacs/dupwords.el).

Avoid jarring language in the text you write. Highlight duplicated words in sentences or paragraphs in [Emacs](https://www.gnu.org/software/emacs/) while writing.

# Motivation

Using the same word several times or even just twice within a paragraph can have a jarring effect when reading.
However, one often will not notice when one uses the same word: distracted as one is by the writing processes.
`dumpword.el` library tries allow one to notice when this happens.

# Installing

Check out the code

```
git clone https://github.com/talwrii/emacs-dupwords ~/.emacs.d/emacs-dupwords
```

Add the code to your `load-path` and require it

```
(add-to-list 'load-path "~/.emacs.d/emacs-dupwords")
(require 'dupwords)
```
