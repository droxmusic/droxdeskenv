# droxdeskenv
An Openbox-based Desktop Environment for Powerusers

What
====
ddenv is a Desktop Environment without frills and streamlined for a specific workflow and selectable performance while not looking too bad. Idle runs at ~500 MB and many tasks have two programs for use, one less demanding than the other. The workflow relies heavily on hotkey use with but most functionality can be done with the mouse if you enable windows decorations (CTRL-b). Left-right tile windows with Super+Left/Right, move desktops with A-C-Left/Right, Move the window with you with A-S-Left/Right. The system works best by giving desktops a purpose and keeping associated programs there (hence desktop icons)
---
In most cases a graphical program is started with rofi via Super-r. For system Configuration, Super+space opens a menu with shortcuts to system configuration programs along with shortcuts to some very common tasks. Think of this as system settings menu, not as a start menu.

For CLI one can either launch a termite window with Super+Enter or press F2 to bring Tilda into focus. The Tilda session is always on and accessible and F11 and F12 will toggle fullscreen and transparency. Use Tilda as an "always open" terminal session for your general use and launch termites when you need a purpose driven window or dont want to work with tilda tabs.
---
Props
=====
Before the Program list I want to give credit to [addy-dclxvi](https://github.com/addy-dclxvi/Ultimate-Dotfiles) As thier whole setup was the basis of many of these configs (some even largely unchanged). 
---
Programs
========
* Window Manager: Openbox
* Compositor: Compton
* Theme: Adapta-Nokto-Eta
* Icons: Sradi Flat
* Font: Roboto
* Monospace: M+ 1mn
---
* Terminal: Tilda and termite
* Shell: zsh with oh_my_zsh using Nerdfont Powerline
* Taskbar: polybar and Tint2
* Launcher: rofi
* Files: Thunar
---
* Text: Atom and Geany
* Documents: evince
* Photos: Ristretto and feh
* Music: mpd
* Video: mpv
---
* Browser: Vivaldi and Waterfox
* Email: mutt
* Chat: Riot and hexchat
* Calendar: calcurse-caldav
---
Installing
==========
Unfortunately I don't have an install setup done yet. Nor do I have a package list filling in my gaps of the listed programs. Best bet to install is to have a second session to try as you find the missing programs to install in the case the booed desktop is unusable. ALSO any references to /home/drox/ must be changed to your home folder. I'm doing my best to turn them into relative paths for general use. Keep posted for easy installation
