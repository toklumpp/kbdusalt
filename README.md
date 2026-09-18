# US-International - AltGr Keyboard Layout

## Description

I created this keyboard layout to use accented characters on an US
keyboard without dead keys interfering with the base characters.
All assignments are exactly the same as on the standard US-International
layout, except for the dead keys. The dead keys were moved to
the AltGr layer and replaced with their plain versions on the base layer.
The layout is therefore 100% backwards-compatible with the standard US
keyboard layout except for the right Alt key which serves as AltGr
(see below).

## Tools

The layout was created using Microsoft Keyboard Layout Creator.

## Registry files

If you want your layout to be absolutely 1-to-1 compatible to the standard
US layout you can use these registry scripts to remap the AltGr key to Alt again.

The registry file remap_win2altgr_altgr2alt.reg remaps the Windows keys
to "Right Alt" and the right Alt key to "Left Alt". Therefore the Windows
keys serve as AltGr keys for the international layout and the Alt keys work
as in the non-international layout.

The registry file remap_altgr2alt.reg only remaps the right Alt key to
"Left Alt". The Alt keys will work as in the non-international layout
while the international characters are only reachable through Ctrl+Alt.

The file restore_keys.reg removes the custom key assignments and
restores the default behaviour.

## Contact

If you want to contact me you can reach me at <info@toklumpp.net>.
You can also check out my website at https://www.toklumpp.net.

## License

MIT