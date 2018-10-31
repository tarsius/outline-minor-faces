Heading faces for `outline-minor-mode`
======================================

Unlike `outline-mode`, `outline-minor-mode` does not change
the appearance of headings to look different from comments.

This package defines the faces `outline-minor-N`, which inherit
from the respective `outline-N` faces used in `outline-mode` and
arranges for them to be used in `outline-minor-mode`.

### Usage

```elisp
(use-package outline-minor-faces
  :after outline
  :config (add-hook 'outline-minor-mode-hook
                    'outline-minor-faces-add-font-lock-keywords))
```
