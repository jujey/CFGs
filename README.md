# fix hl1-steam-linux bugs

`sudo pacman -S lib32-sdl2` after downloading this move the file `libSDL2-2.0.so.0.10.0` from `usr/lib32/` to `~/.steam/steam/steamapps/common/Half-Life/` and rename it to `libSDL2-2.0.so.0`

after doing this if you don't want to use my `openag.cfg` as your config file, add these lines to your HL1 .cfg file
- cl_forwardspeed 400
- cl_sidespeed 400
# what to do

**openag**
- rename `openag.cfg` to `autoexec.cfg`

**csgo**
- move my cfg called `ze.cfg` inside `csgo` to `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg` and then execute it by typing in the console `exec ze`


## test (don't mind this)
https://gitlab.com/torkel104/libstrangle
