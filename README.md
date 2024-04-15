# github-primer-theme for Emacs

This theme implements colors from [Primer](https://primer.style) into Emacs.

## Installation & configuration

Here is an example configuration to use in your Emacs [init](https://www.gnu.org/software/emacs/manual/html_node/emacs/Init-File.html) file:

```lisp
(use-package github-primer-theme
  :vc (:url "https://github.com/thiagopolastri/github-primer-theme-emacs" :branch "main")
  :custom (github-primer-color-theme "dark")
  :commands (github-primer-cycle)
  :bind ("<f5>" . github-primer-cycle)
  :init (load-theme 'github-primer t))
```
