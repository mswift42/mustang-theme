mustang-theme
=============

port of vim's mustang theme to emacs24.

![Screenshot](https://github.com/mswift42/mustang-theme/raw/master/Screenshot.png)

It's available on [Melpa](http://melpa.milkbox.net/#/), i.e. you can install it via Emacs package manager if you have enabled the Melpa repository.

Installation Instructions
-------------------------

add the following lines to your init.el (only if you have not done so already):

    (setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                             ("marmalade" . "http://marmalade-repo.org/packages/")
                             ("melpa" . "http://melpa.milkbox.net/packages/")))

    (package-initialize)



This will add the gnu, marmalade and melpa repos to your emacs setup.

To install the theme

**M-x package-install** mustang-theme


To use the mustang theme when starting emacs, add this to your init.el:

    (load-theme 'mustang)


Credits
-------

This is a port of the [vim theme](http://hcalves.deviantart.com/art/Mustang-Vim-Colorspcheme-98974484) by Henrique C. Alves


