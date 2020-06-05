# Shawns build of dwm

## FAQ

> What is dwm?

Upstream is at [suckless](https://git.suckless.org/dwm/)

> What are the bindings?

This is suckless, mmmbud, the source code is the documentation! Check out [config.h](config.h).

Luke had a readme in `larbs.mom` for the whole system, but I'm not updating that.
Press `super+F1` to view it in dwm (zathura is required for that binding).
I haven't kept `man dwm`/`dwm.1` updated though. PRs welcome on that, lol.

## Patches and features

- Clickable statusbar with my build of [dwmblocks](https://github.com/scresante/dwmblocks).
  (broken)
- Probably messes up your keyboard repeat delay
- Reads xresources colors/variables (i.e. works with `pywal`, etc.).
- ~scratchpad: Accessible with mod+shift+enter.~
- New layouts: bstack, fibonacci, deck, centered master and more. All bound to keys `super+(shift+)t/y/u/i`.
- True fullscreen (`super+f`) and prevents focus shifting.
- Windows can be made sticky (`super+s`).

- stacker: Move windows up the stack manually (`super-K/J`).
- shiftview: Cycle through tags (`super+g/;`).
- vanitygaps: Gaps allowed across all layouts.
- swallow patch: if a program run from a terminal would make it inoperable, it temporarily takes its place to save space.

## Please **dont** install `libxft-bgra`!

It is bloat, & a major PITA considering the AUR for that is currently broken

Nobody needs "color emoji" in a status bar anyways
