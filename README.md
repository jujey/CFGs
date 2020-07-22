# Fix hl1-steam-linux bugs

`sudo pacman -S lib32-sdl2` after downloading this move the file `libSDL2-2.0.so.0.10.0` from `usr/lib32/` to `~/.steam/steam/steamapps/common/Half-Life/` and rename it to `libSDL2-2.0.so.0`

...after doing this add these lines to your HL1 .cfg file
- `cl_forwardspeed 400`
- `cl_sidespeed 400`

# OpenAg .cfg
- rename `openag.cfg` to `autoexec.cfg`

# CSGO .cfg
- move `ze.cfg` inside `csgo` to `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg` and then execute it by typing in the console `exec ze` or `exec muteze`

# CDDA Dependencies
`sudo pacman -S sdl2_image sdl2_ttf sdl2_mixer freetype2 ncurses`

# Add Permissions To Execute, Write, Delete, etc...
for example: `sudo chmod a+rx /usr/bin/cdda`
