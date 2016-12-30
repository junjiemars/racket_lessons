# Common Lisp

## Environments

### View Source Code
Set sbcl's source path via
```common-lisp
(sb-ext:set-sbcl-source-location "/opt/open/sbcl/")
```
Use ```M-.``` jump to ```*slime-xref*``` list.


## Variables & Expressions

### Assignment
* [set setq setq](http://stackoverflow.com/questions/869529/difference-between-set-setq-and-setf-in-common-lisp)
* [what does the f in setf stand for](http://stackoverflow.com/questions/23808189/what-does-the-f-in-setf-stand-for)
* [naming conversions](http://www.cliki.net/Naming+conventions)

**q** of ```setq``` means ```(set (quote x) 123)```, **q** is for ```quote```

**f** of ```setf``` means field/form/function ?

```defparameter``` always assigns a value, but ```defvar``` does it only once.

