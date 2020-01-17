# ob-pipemenu
pipemenus for openbox. They are written as shell scripts using bash features, for the express purpose of being usable by the most standard of openbox setups, no extra packages needed.

* **bin-pipemenu**
  - show files in user's bin folder, as well as their permissions, with checks to see if it is a shortcut to show linked file options. File commands as of v4 are Edit, change executable status, and Run, broken down into run or run in terminal, as well as run in terminal as root
---
* **conky-pipemenu**
  - shows file in a folder and sub folders. File commands as of v3 are Run, Kill, and Edit.
---
* **moc-pipemenu**
  - as of v2 shows player status, current song, and player controls. if moc is not running it will only show a start option, otherwise commands are Play/Pause, Next, Previous, Stop, Volume selection and Shuffle/Repeat/Auto-next selection. further options are song info, open player, open music folder, kill moc
---
* **rom-pipemenu**
  - shows files in a folder and sub folder. File commands as of v4 are set based on file type to correct emulator, unless file is a disk image. Disk images are given a list of emulators to select from. To increase performance, each folder is set as a pipemenu with in itself, so that the menu only has to load the folders that you are looking in.
---
* **transmission-pipemenu**
  - shows transmission controlls, and a list of torrents, with controlls.
---
* **Defaults**
  - File Manager: Thunar
  - Editor: Geany
  - Terminal: Terminator
