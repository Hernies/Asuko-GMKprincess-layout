# Asuko GMKprincess layout
Coleman-DH mod for international use (Spanish and English).

I made this layout for my GMK67, a 65% keyboard, this repo is so I or anyone else can set up my layout on any linux xorg-based system. Only the .xmodmap file is necessary  but since I enjoy having multiple layouts I also set up a ubuntu custom keyboard layout.

It is useful for programming too since it has the US-ANSI symbol layout (for the most part). Layout inspired by reddit user u/simianeditions from [this post](https://www.reddit.com/r/Colemak/comments/v7jzj4/colemak_in_spanish_dh_mod/). 


## Setting it up
If you want **only a remapped keyboard**, you can go ahead and just [download this .xmodmap file](asuko.xmodmap)
If instead you want a layout that can be switched to and from, go ahead and be ready to dive deep into Xorgs documentations (just kidding I already did that)

first create a new symbols file: 
```bash
sudo nano /usr/share/X11/xkb/symbols/ak
```
