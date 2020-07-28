# Fix hl1-steam-linux bugs

`sudo pacman -S lib32-sdl2` after downloading this move the file `libSDL2-2.0.so.0.10.0` from `usr/lib32/` to `~/.steam/steam/steamapps/common/Half-Life/` and rename it to `libSDL2-2.0.so.0`

...after doing this add these lines to your .cfg file
- `cl_forwardspeed 400`
- `cl_sidespeed 400`

# OpenAg .cfg
- rename `openag.cfg` to `autoexec.cfg`

# CSGO .cfg
- move `ze.cfg` inside `csgo` to `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg` and then execute it by typing in the console `exec ze` or `exec muteze`

# EzQuake/Nquake
- nquake https://github.com/nQuake/client-linux/raw/master/releases/nquake_installer-linux-latest.tar.gz
- ezquake https://github.com/jujey/Games/blob/master/Custom%20Executables/ezquake-linux
- cfg https://github.com/jujey/Games/blob/master/CFG'S/ezquake.cfg
- old models `default` in console

# CDDA Dependencies
`sudo pacman -S sdl2_image sdl2_ttf sdl2_mixer freetype2 ncurses`
# Hexen: Beyond Heretic
To play Hexen: Beyond Heretic you'll need **Wine** and [Gzdoom](https://www.zdoom.org/downloads).
- **Wine** ➡️`sudo pacman -S wine`

# Discord
Use nativefier:
`nativefier https://discord.com/channels/@me`

# Add Permissions To Execute, Write, Delete, etc...
For example: `sudo chmod a+rx /usr/bin/cdda`
