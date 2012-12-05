# Slate #
An emacs major mode for [Slate](https://github.com/jigish/slate)

# Installation #

## el-get ##
Add the following recipe to `el-get-sources`:

```lisp
(:name slate-mode
               :type github
               :pkgname "ddjfreedom/slate-mode"
               :features slate-mode)
```

Then run `M-x el-get-install` to install `slate-mode`.

## Manual ##
Put `slate-mode.el` into a directory in `load-path`, and add

```lisp
(require 'slate-mode)
```

into emacs init file.

