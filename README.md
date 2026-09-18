# US-International - AltGr Keyboard Layout

## Description

This keyboard layout makes it possible to type accented characters on a US keyboard without having dead keys interfere with ordinary characters.

The layout was inspired by the **Linux US-International AltGr dead-key layout** and is **100% compatible with the Microsoft US-International keyboard layout**. All character assignments are identical to the standard Microsoft US-International layout, except for the placement of the dead keys.

The dead keys have been moved to the **AltGr layer** and replaced with their plain-character versions on the base layer. As a result, the layout remains 100% compatible with the standard US keyboard layout, with the exception that the **Right Alt** key functions as **AltGr** (see more below).

## Tools

The layout was created using **Microsoft Keyboard Layout Creator**. The source file is
`kbdusalt.klc`.

## Registry Files

If you want the layout to be completely 1-to-1 compatible with the standard US keyboard layout, you can use the included registry scripts to remap the AltGr key.

The `remap_win2altgr_altgr2alt.reg` registry file remaps the Windows keys to **Right Alt** and the Right Alt key to **Left Alt**. This allows the Windows keys to function as AltGr keys for the international layout while preserving the usual behavior of the Alt keys.

The `remap_altgr2alt.reg` registry file remaps only the Right Alt key to **Left Alt**. The Alt keys then behave as they do on the standard US layout, while international characters remain accessible through **Ctrl+Alt** combinations.

The `restore_keys.reg` file removes the custom key assignments and restores the default behavior.

## Contact

For questions or comments, contact <info@toklumpp.net> or visit <https://www.toklumpp.net>.

## License

MIT