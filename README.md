# What is duplicate-line.el ?
Duplicate line or region, don't need move cursor.

Those code wrote at 2009, i extract duplicate functions from my basic-toolkit.el

## Installation
Clone or download this repository (path of the folder is the `<path-to-duplicate-line>` used below).

In your `~/.emacs`, add the following two lines:
```Elisp
(add-to-list 'load-path "<path-to-duplicate-line>") ; add duplicate-line to your load-path
(require 'duplicate-line)
```

## Usage
Bind your favorite key to functions:

 | Function                       | Description                                            |
 | :--------                      | :----                                                  |
 | duplicate-line-or-region-above | Duplicate current line or region above                 |
 | duplicate-line-or-region-below | Duplicate current line or region below                 |
 | duplicate-line-above-comment   | Duplicate current line above, and comment current line |
 | duplicate-line-below-comment   | Duplicate current line below, and comment current line |

