rnas-mode
=========

*Restart node.js after save mode (rnas-mode) for Emacs*

This mode opens the shell and (re)starts node.js on `.js` files' save event. Node executes a script that you specify when enabling the mode.

###Installation
Run 
```
git clone https://github.com/vadimrostok/rnas-mode.git path-you-like
```
and add
```
(load "path-you-like/rnas-mode.el")
```
to your `.emacs` file.

###Use
`M-x rnas-mode`
