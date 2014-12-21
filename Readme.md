English is not my first language, so feel free to correct me of any mistake.

isearch-dabbrev
============

This extension allows you to tab-complete words in isearch-mode.


Installation
------------

put isearch-dabbrev.el somewhere in your load-path and add these
lines to your .emacs:
```lisp
(eval-after-load "isearch"
  '(progn
     (require 'isearch-dabbrev)
     (define-key isearch-mode-map (kbd "<tab>") 'isearch-dabbrev-expand)))
```

Credits
-------

This script is heavily inspired by vim plugin [SearchComplete](http://www.vim.org/scripts/script.php?script_id=474).
