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

    1. Decide if that window should stay on top of others. you can use a hotkey (default `Ctrl-Shift-T`) to toggle that setting on the fly.(*)

1. Use the Bnet launcher to start your wow windows so you don't need to type your password, WOB/OMB will make them borderless automatically for you, but check in game resolution options to avoid pixelization (100% Render Scale, Correct window size).

1. Wob since version 4.1 will automatically capture and place the windows in their respective position for you (you can turn that option off in the Option menu). Otherwise, press the "Capture" button or use its hotkey (default `Ctrl-Shift-C`). If you want to manage other games than World of Warcraft, see the ['Other Games' section below](#other-games)

1. Press a hotkey to change which window gets the keyboard input: default key are `Ctrl-F1` for Wow 1, `Ctrl-F2` for Wow 2, etc.. or rotate between windows with hotkeys to focus the next window (defaults to `Ctrl-Shift-N`) and previous window (defaults to `Ctrl-Shift-P`). Hotkeys can be changed in File > "Hotkeys..." (see [below](#hotkeys)).

1. Press a hotkey to bring window N to the main (1) window: default `Ctrl-Shift-F2` will swap 1 and 2,  `Ctrl-Shift-F3` for swapping 1 and 3, etc... Or rotate the swap between all windows by repeatedly pressing `Ctrl-~` for forward swap or `Ctrl-Shift-~` for backward swap.

1. You can toggle the overlay on/off at any time using the default hotkey `Ctrl-Shift-O` or the checkbox on the main window.

1. You can use the FocusMain hotkey (`Ctrl-Shift-W`) to always get focus back to the physical main window location (even if it's, say, Wow3 in it).

1. **Profiles**: save different setups, for instance one per window layout (a big main window with smaller ones vs. a full screen main window), with File > "New Profile...", then change the Window Layout and "Save and Apply". Switch between them in the Profile menu or cycle through them with `Ctrl-Shift-L` (next) and `Ctrl-Shift-Alt-L` (previous). Profile > "Profiles in rotation..." picks which profiles are cycled through (all but Default by default).

*: You can change all settings at any time and they will be saved, per window index when you click "Update" or "Save and Apply" in the Window Layout GUI.

### Hotkeys

File > "Hotkeys..." shows all the hotkeys. Click one and press the new key combination (`Esc` cancels), right click clears it. A key combination already used by another hotkey is cleared from that one. Changes apply and are saved right away; Undo (or `Ctrl-Z`) goes back, up to how the hotkeys were when the window opened. If another application already uses some hotkeys, WOB opens that window with them in red so you can pick different ones.

<p align="center">
<img src="sshotHotkeys.png" alt="WOB Hotkeys window">
</p>

### Settings

Your settings are saved in `wowopenboxSettings.tcl` in same folder as WowOpenBox and can be edited pressing the "Edit Settings" button.

Make sure to also explore the File, Option etc menus (menu bar is at the top of the window) and read mouse over tooltips present in most UI elements of WOB/OMB.

<p align="center">
<img src="wob2025_4_9.png" alt="WOB2025 4.9 Screenshot">
</p>

## Mouse control

The "Focus follows mouse" checkbox turns on the Windows "Activate on hover" accessibility feature (Settings > Accessibility > Mouse) and sets its delay to instant (0 ms, while the Windows slider's minimum of 1 is 100 ms and its default of 5 is 500 ms). You can change that delay with `mouseDelay` (in ms) in your settings (see above). On exit, the previous Windows delay is restored and the feature turned off (unless you uncheck "Turn off focus follow mouse on exit" in the Option menu).

Whether hovering also brings the window to the front is the "Mouse auto foreground window" option in the Option menu (same as Windows' "Move window to top when activating for mouse hover").

There is a "Track Mouse" (and stop tracking) button (and hotkey, default `Ctrl-Shift-M`) to track coordinates to help doing pixel perfect placement of your windows

You can toggle the focus follow mouse behavior using a hotkey (default `Ctrl-Shift-F`)

## Other Games

Use the Game menu to select your Game and/or check the Capture using foreground window:

<p align="center">
<img src="sshot_game_menu.PNG" alt="Game Menu screenshot">
</p>

Read the help text mouse over tooltip:

<p align="center">
<img src="sshot_capturefg.png" alt="Capture foreground screenshot">
</p>

You must click your game window and use the capture hotkey (`Ctrl-Shift-C` by default, changeable in settings) to use that mode; after which your game name should be recorded in the Game menu and you can stick to normal Auto Capture (Options Menu).


## Need more help? Report a problem? Suggest a new feature?

Make sure you are running the latest [release](https://github.com/WowOpenBox/WowOpenBox/releases)

In rare case if things seems wrong, you can try to either restart WOB/OMB, it will resume where you left off so no need to touch your game windows when or if you do. Or you can use the Reset-All hotkey (default binding is `Ctrl-Shift-Alt-R`) which should put all windows in their home position. But if this persists please file a bug and explain in details how to reproduce the problem with minimal steps:

Check if your [issue](https://github.com/WowOpenBox/WowOpenBox/issues/) or suggestion has already been report and if not make a new detailed one

Check the [FAQ](https://github.com/WowOpenBox/WowOpenBox/wiki/FAQ)

Reach out on <a href="https://discord.gg/SMGvEeb"><img src="discord.svg" alt="Discord" align="center" height="24pt"></a>

If your game or application allows Broadcasting, switch over to [OMB (OpenMultiboxing)](https://openmultiboxing.org).
