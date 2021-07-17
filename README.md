# Prog keyboard layout

This is a customized keyboard layout I created in college. I've decided to keep it in my Github so I won't lose it anymore.

The main difference between this layout and normal QWERTY is that the punctuation marks used commonly in programming are found in the number row. This pattern was inspired by [Programmer Dvorak](https://www.kaufmann.no/roland/dvorak/).

I created this on Windows and also have a version that works for Mac OS, but XKB is by far the most annoying to configure, so it's the only one in this repo so far. I can add the others on request.

# XKB a.k.a. most Linuxes Installation
1. Copy the `prog` file to `/usr/share/X11/xkb/symbols` and copy `evdev.xml` to `/usr/share/X11/xkb/rules`.

2. Add the new keyboard layout using your Desktop Environment

Caveats:
- You don't really need to copy this particular `evdev.xml`. There is only a single entry in there for `prog` that is necessary, but I find it easier to copy the entire thing because I don't really use many keyboard layouts. This `evdev.xml` is what happened to be on my computer when I wrote this.
- `evdev.xml` is overwritten from time to time when I upgrade my distro. So from every once in a while, you need to copy it back from here or re-add the entry for `prog`


