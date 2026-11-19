# Sparking! ZERO VR

A VR mod for DRAGON BALL Sparking! ZERO: play in first person with motion controls. It runs on UEVR.

This is an early release, made for offline training matches. I'm working through every character to make each one the best it can be, so there's more to come.

**Download:** get `SparkingZERO-Win64-Shipping.zip` from the [Releases](../../releases) page.

> **Offline only.** Bandai Namco has announced bans for mods in online play, so the mod switches itself off outside offline modes. Don't take it online.

## Requirements

- A PC VR headset. Tested on Quest 3 with Virtual Desktop.
- An NVIDIA RTX GPU for DLSS.
- UEVR nightly 01143.

## Install

1. Get UEVR nightly 01143: on [praydog/UEVR-nightly releases](https://github.com/praydog/UEVR-nightly/releases) find "UEVR Nightly 01143", download `uevr.zip`, unpack it and run `UEVRInjector.exe`.
2. Choose **Import Config** on UEVR's left and pick the zip. Keep its name: UEVR names the game's profile after it. UEVR warns that the zip holds DLLs (the mod's plugin and NVIDIA's DLSS): answer Yes.

## Play

3. Connect your headset and start the game.
4. In UEVR, pick the game in the list at the top (if it isn't there, close UEVR and open it again). Choose **OpenXR** (tested with Virtual Desktop's VDXR) and press **Inject**.
5. UEVR's overlay opens by itself, and the controllers won't reach the game until you close it: press Insert, or press both sticks in. The same keys open it again.
6. Start an offline training match: Battle & Training, then Super Training, then Training.
7. Get comfortable and recenter: in the overlay under VR, Runtime, press **Recenter Horizon**, then **Set Standing Origin**.
8. The mod's settings are in the overlay under LuaLoader, Script UI. Use **Measure my arms** once, in the position you play in, so your in-game arms match yours.

## Credits

- NVIDIA DLSS: the release ships NVIDIA's `nvngx_dlss.dll` (DLSS 310.9.16), unchanged, under NVIDIA's terms (`NVIDIA-DLSS-LICENSE.txt` in the zip). NVIDIA and DLSS are trademarks of NVIDIA Corporation.
- UEVR by praydog: the mod's plugin is built against UEVR's plugin API (MIT).

## Disclaimer

Sparking! ZERO VR is an unofficial fan mod. It is not affiliated with, endorsed by or sponsored by Bandai Namco Entertainment, Toei Animation, Bird Studio/Shueisha or NVIDIA. DRAGON BALL and DRAGON BALL Sparking! ZERO belong to their owners. The code is MIT licensed (see `LICENSE`).
