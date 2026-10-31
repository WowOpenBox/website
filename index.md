# Wow Open Box (Open Source, compliant, Multiboxing)

Welcome to WowOpenBox.org the hub for truly Open Source and Blizzard rules compliant World of Warcraft MultiBoxing/Dual-Boxing!

_July 2025 Update_: **The Round Robin capability has been entirely removed in an effort to ensure full compliance with Blizzard's (vague) multiboxing policy.**

We started this effort Mid November 2020 and already have dozens of ever improving feature-full releases and many happy users.

Join the conversation through GitHub, make or help prioritize [issues](https://github.com/WowOpenBox/WowOpenBox/issues/), PRs, or on our <a href="https://discord.gg/SMGvEeb"><img src="discord.svg" alt="discord" align="center" height="24pt"></a>

The first of many functional [release](https://github.com/WowOpenBox/WowOpenBox/releases) was on November 22nd 2020!

Participate and let's make this the best tool for multiboxing (in addition to being the only Open Source one).

See also a [comparison](https://github.com/WowOpenBox/WowOpenBox/wiki/compare) of WowOpenBox and other multiboxing solutions.

See also the [help](help) page.

WowOpenBox (WOB) is optimized to be the safest and best solution for Blizzard's World of Warcraft but can also be use to manage multiple windows of [other applications or games](help#other-games)).

If your game or application allows Broadcasting, switch over to [OMB (OpenMultiboxing)](https://openmultiboxing.org).

## Main features

- Window Layout wizard and manual tweaking; get your game windows exactly how you want them to be to play.
   - Save different layouts as profiles (File > New Profile...) and cycle through them with the Ctrl-Shift-L (next) and Ctrl-Shift-Alt-L (previous) hotkeys. Pick which profiles are in the rotation with Profile > "Profiles in rotation..." (all but Default by default).
- Instant swapping of windows; with keyboard hotkeys for fast switching to the next or any specific window.
   - Change any hotkey in File > "Hotkeys...": click it and press the new key combination (right click clears it, Undo goes back).
- **Mirrors** (WOB2027 v4.11.0+): live, zoomable copies of an area of any game window (e.g. a bigger minimap, or the portraits of the small windows), anywhere on screen. File > "Mirrors...": "Add a mirror", click a window, drag the area; then drag to move, drag the sides to extend/shrink the area, mouse wheel to zoom, right click for options. Mirrors stay on their window as it gets swapped (or follow whichever window is main) and let mouse clicks through outside of edit mode. See the [help](help#mirrors).
   - **Mirrored layout**: check "Mirrored" in Window Layout to stack all the game windows under the main one and show the other positions as live mirrors of them: instant swaps (no resizing), click a mirror to make that window main. See the [help](help#mirrored-layout).
- Many additional options to switch which window your keys are going to:
  - Focus follow mouse: turns on/off the Windows&trade; accessibility feature so you just hover a window to make it receive keys (instantly: WOB sets the hover delay to 0 ms, below the 100 ms minimum of the Windows slider)
  - Focus next/previous/specific windows with hotkeys.
- Free, OpenSource and the [Safest](https://github.com/WowOpenBox/WowOpenBox/wiki/FAQ#i-heard-wob-is-safer-than-jmb-how-so) option available: WOB respects Blizzard's new directive to not do any software input broadcasting. Multiboxing legitimately with peace of mind.
- Online [help](help), menus and tooltips on most UI element to help discovering features.

## Installation

WowOpenBox is optimized for Microsoft Windows 10.

Since release 2.2, WOB/OMB is entirely built automatically from source by GitHub actions CI (continuous integration).

Simply download the all in one zip (WOB2027-vX.Y.Z.zip, not the source zip) from the latest release at: [https://github.com/WowOpenBox/WowOpenBox/releases](https://github.com/WowOpenBox/WowOpenBox/releases) and extract it all to your desktop for instance.

Run the `WOB2027` exe and enjoy!

Coming from WOB2025: extract the new zip in the same folder (or copy your `wowopenboxSettings*.tcl` files next to the new exe) to keep your settings and profiles. The WOB2025 exe keeps working and updating, only the mirrors need the WOB2027 one.

(Please report any problem!)

<p align="center">
<img src="wob2025_4_9.png" alt="WOB2025 4.9 Screenshot">
</p>

Window Layout wizard:

<p align="center">
<a href="sshotWindowLayout.png"><img src="sshotWindowLayout.png" alt="WOB Window Layout"></a>
</p>

Optional/toggle-able overlay information indicating which window has focus:

<p align="center">
<a href="sshotOverlay.png"><img src="sshotOverlay.png" alt="WOB Window Layout"></a>
</p>

Intro video (best viewed as recorded, at least 1440p)
<style>
.video-container {
	position:relative;
	padding-bottom:56.25%;
	padding-top:30px;
	height:0;
	overflow:hidden;
}

.video-container iframe, .video-container object, .video-container embed {
	position:absolute;
	top:0;
	left:0;
	width:100%;
	height:100%;
}
</style>

<div class="video-container"><iframe width="560" height="315" src="https://www.youtube.com/embed/s4sCBdkXqUk" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
