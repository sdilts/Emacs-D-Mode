# Emacs D Mode

[![Build Status](https://travis-ci.org/dmakarov/Emacs-D-Mode.svg?branch=testing)](https://travis-ci.org/dmakarov/Emacs-D-Mode)
[![Coverage Status](https://coveralls.io/repos/dmakarov/Emacs-D-Mode/badge.svg?branch=testing)](https://coveralls.io/r/dmakarov/Emacs-D-Mode?branch=testing)
[![MELPA](http://melpa.org/packages/d-mode-badge.svg)](http://melpa.org/#/d-mode)

An Emacs major mode for editing D code.

This mode is currently known to work with Emacs 24 and believed to work with Emacs 23.

The best way of installing this major mode, at least for Emacs 24, is to use the packaging system. Add MELPA
or MELPA Stable to the list of repositories to access this mode. For those who want only formal, tagged
releases use MELPA Stable:

    (require 'package)
    (add-to-list 'package-archives
             '("melpa-stable" . "https://stable.melpa.org/packages/") t)
    (package-initialize)

For those who want rolling releases as they happen use MELPA:

    (require 'package)
    (add-to-list 'package-archives
             '("melpa" . "https://melpa.org/packages/") t)
    (package-initialize)

and then use M-x package-list-packages to get to the package listing and install from there. MELPA tracks
this Git repository and updates relatively soon after each commit or formal release. For more detail on
setting up see [MELPA Getting Started](https://melpa.org/#/getting-started).

The master of all the material is the Git repository at
https://github.com/Emacs-D-Mode-Maintainers/Emacs-D-Mode .

This software is licenced under GNU General Public Licence version 2.
