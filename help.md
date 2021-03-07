# Wow Open Box online HELP

## Basic information
![Window Layout](sshotWindowLayout.png)

1. Use the "Window Layout" UI to setup your Windows automatically. And you can tweak the intelligent auto layouts by:
    + Dragging any window to reposition it
    + Resize it by dragging the orange bottom right corner
    + Toggle "Stay on top" by clicking on the text
    + Use the snap to grid feature to constraint the position
    + Use the arrow keys for precise movement by 1 pixel

1. _and/or tweak it using:_ Manual Setup (from main window):

    1. Manually select the Size you want your next window to be(*)

    1. Manually select the position you want it to be at(*)

    1. Decide if that window should stay on top of others. you can use a hotkey (default `Ctrl-Shit-T`) to toggle that setting on the fly.(*)

1. Use the Bnet launcher to start your wow windows so you don't need to type your password, WOB/OMB will make them borderless automatically for you, but check in game resolution options to avoid pixelization.

1. Press the "Capture" button or use its hotkey (default `Ctrl-Shift-C`). If you want to manage other games than World of Warcraft, change the game in settings or check the Capture using foreground window (<img src="fgcapture.png"> box)

1. Press a hotkey to change which window gets the keyboard input: default key are `Ctrl-F1` for Wow 1, `Ctrl-F2` for Wow 2, etc.. or rotate between windows with hotkeys to focus the next window (defaults to `Ctrl-Shift-N`) and previous window (defaults to `Ctrl-Shift-P`). Hotkeys are changeable in settings.

1. Press a hotkey to bring window N to the main (1) window: default `Ctrl-Shift-F2` will swap 1 and 2,  `Ctrl-Shift-F3` for swapping 1 and 3, etc... changeable in settings. Or rotate the swap between all windows by repeatedly pressing `Ctrl-OEM3` (OEM3 is the `~` key on us keyboards) for forward swap or `Ctrl-Shift-OEM3` for backward swap.

1. You can toggle the overlay on/off at any time using the default hotkey `Ctrl-Shift-O` or the checkbox on the main window.

1. If you used the optional Round Robin enabler feature, by starting the `OpenMultiBoxing_RR` exe instead of the base one, you will see the Round Robin section in the UI and can use `Ctrl-Shift-R` as the default hotkey to toggle it on/off. Enter which keys should trigger round robin in the entry box (default keys 1 through = and SPACE and . (dot) and F10 are round robin keys, see the [FAQ entry](https://github.com/WowOpenBox/WowOpenBox/wiki/FAQ#what-special-key-names-can-i-use-in-the-round-robin-key-list) for complete list of special key names).  You can use the FocusMain hotkey (`Ctrl-Shift-W`) to always get focus back to the physical main window location (even if it's, say, Wow3 in it). You can use that before using movement keys to ensure you drive from main window even if you didn't complete a full RR rotation back to first window.

*: You can change all settings at any time and they will be saved, per window index when you click "Update" or "Save and Apply" in the Window Layout GUI.

Your settings are saved in `wowopenboxSettings.tcl` in same folder as WowOpenBox and can be edited pressing the "Edit Settings" button.

Make sure to also explore the File, Option etc menus (menu bar is at the top of the window) and read mouse over tooltips present in most UI elements of WOB/OMB.

<p align="center">
<img src="sshot3_5.png" alt="WOB 3.5 Screenshot (with RR)">
</p>

## Mouse control

You can change the focus following mouse and auto raise/set foreground and the delay

Note that to change the delay you need to hit the Return key

There is a "Track Mouse" (and stop tracking) button (and hotkey, default `Ctrl-Shift-M`) to track coordinates to help doing pixel perfect placement of your windows

You can toggle the focus follow mouse behavior using a hotkey (default `Ctrl-Shift-F`)

## Need more help? Report a problem? Suggest a new feature?

Make sure you are running the latest [release](https://github.com/WowOpenBox/WowOpenBox/releases)

Check if your [issue](https://github.com/WowOpenBox/WowOpenBox/issues/) or suggestion has already been report and if not make a new detailed one

Check the [FAQ](https://github.com/WowOpenBox/WowOpenBox/wiki/FAQ)

Reach out on <a href="https://discord.gg/SMGvEeb"><img src="discord.svg" alt="Discord" align="center" height="24pt"></a>
