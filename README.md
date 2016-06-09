[![MIT](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

# DOOM for Emacs

A pack of themes made for [DOOM Emacs](https://github.com/hlissner/emacs.d) and
inspired by the One Dark/Light UI and syntax themes for [Atom](http://atom.io).

+ **doom-one**: inspired by Atom One Dark
+ **doom-one-light** (WIP): inspired by Atom One Light
+ **doom-dark**: inspired by Molokai, used for terminal emacs

NOTE: Makes use of `face-remapping-alist`. See `doom-enable-bright-minibuffer`
and `doom-enable-bright-buffers`.

## Configuration

+ `doom-enable-bright-minibuffer` (default: `t`): if non-nil, the minibuffer's background
  will be slightly brighter when in use (see `doom-minibuffer-active` face)
+ `doom-enable-bright-buffers` (default: `t`): if non-nil, source buffers' backgrounds
  will be slightly brighter than special buffers. This looks great for
  distinguishing sidebars and popups from source code buffers (See
  `doom-default` face)
+ `doom-enable-bold` (default: `t`)
+ `doom-enable-italic` (default: `t`)
+ `doom-enable-neotree-theme` (default: `nil`): if non-nil, Neotree will use
  the unicode icons depicted in screenshots (has only been tested in the
  emacs-mac port on OSX).

## Screenshots

### doom-one (dark)

![](../screenshots/one-dark/01.png)

(more to come)

