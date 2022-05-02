Minara Common Lisp
==================

Minara - the editable vector graphics editor.

MINARA stands for "Minara Is Not A Recursive Acronym".

This is the Common Lisp port of the Guile Scheme version of Minara.

Setup
-----

* Install sbcl and quicklisp.
* Install flexichain and cl-opengl with quicklisp.
* Add or link minara/src/ to ~/common-lisp/ .

Usage
-----

    sbcl --eval "(require :minara)" --eval "(minara:main-entry-point)"
