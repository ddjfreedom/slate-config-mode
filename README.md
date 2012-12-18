# slate-config-mode #
An emacs major mode for [Slate](https://github.com/jigish/slate)

# Installation #

## el-get ##
Add the following recipe to `el-get-sources`:

```lisp
(:name slate-config-mode
               :type github
               :pkgname "ddjfreedom/slate-config-mode"
               :features slate-config-mode)
```

Then run `M-x el-get-install` to install `slate-config-mode`.

## Manual ##
Put `slate-config-mode.el` into a directory in `load-path`, and add

```lisp
(require 'slate-config-mode)
```

into emacs init file.

