# To compile
```bash
make clean
bear -- make
```

# To run
required Exports
```bash
export DOOMWADDIR=/path/to/folder/where/doom.wad/is
export DISPLAY=:3 # or any other display number you used

# xephyr
sudo Xephyr :3 -ac -screen 640x480x8
```

# Dependencies that were missing on my system (Ubuntu 20.04)
```bash
sudo apt install bear libx11-dev libxext-dev libnsl-dev xserver-xephyr
```

Copyright (c) ZeniMax Media Inc.
Licensed under the GNU General Public License 2.0.
