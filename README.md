# BootUp
A pelican theme

# Installation
Put in a directory under your pelican site and point 'THEME' in pelicanconf.py to it.

# Configuration
All pages are linked statically via *MENUITEMS* in pelicanconf.py.
This was necessary to bypass template pages not being able to be identified for active states.
Any new template pages also need to have *active_page* set to the same name as the page's title in pelican.conf before including anything else.

`{% set active_page = Index %}

{% extends "base.html" %}

...`

# License
[MIT](https://github.com/dankolbman/dankolbman.com-Reboot.git)
