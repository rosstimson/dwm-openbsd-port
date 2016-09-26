# My Personal dwm OpenBSD Port

This is the standard OpenBSD port with a few extra patches included to
customise dwm to my liking.

## Usage

Replace the standard port in `/usr/ports/x11/dwm` and install as usual
with `make install clean`.

## Changes

* Use Win/Mac key (Mod4) instead of Alt.
* Use `urxvtc` as default terminal.
* Don't use resize hints, this causes gaps when you open terminals.
* Apply [noborder](http://dwm.suckless.org/patches/noborder) patch.
