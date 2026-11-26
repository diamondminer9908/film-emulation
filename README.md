# Film Emulation for DaVinci Resolve

An OpenFX plugin that makes digital footage look like it was shot on film and printed: film stock colour and contrast, halation, grain, gate weave and more. It works in DaVinci Resolve and Resolve Studio on Mac and Windows.

This page only holds the finished plugin. Install it once with the installer below, and new versions then install themselves.

## Install with automatic updates

**Mac** (macOS 11 or later, Apple Silicon or Intel)
1. Quit DaVinci Resolve.
2. Download [Install-Film-Emulation-Mac.pkg](https://github.com/diamondminer9908/film-emulation/releases/latest/download/Install-Film-Emulation-Mac.pkg).
3. Right-click the file and choose **Open**, then click **Open** again. The installer isn't signed with an Apple developer certificate, so a plain double-click is blocked the first time. If there's no Open button, go to **System Settings > Privacy & Security** and click **Open Anyway**.
4. Follow the steps and enter your Mac password. The installer downloads and installs the newest plugin.
5. Start Resolve. Film Emulation is under **Color page > Effects > OpenFX > Filters > Film Lab**.

New versions install by themselves. The Mac checks every hour and whenever the network changes, and shows a notification when it updates. If Resolve was open, restart Resolve to use the new version.

To uninstall, open Terminal and run:

```
sudo "/Library/Application Support/FilmEmulationUpdater/uninstall.sh"
```

**Windows** (64-bit Windows 10 or 11)
1. Quit DaVinci Resolve.
2. Download [Install-Film-Emulation-Windows.zip](https://github.com/diamondminer9908/film-emulation/releases/latest/download/Install-Film-Emulation-Windows.zip), right-click it and choose **Extract All**.
3. In the extracted folder, double-click **Install Film Emulation.cmd** and click **Yes** when Windows asks for administrator rights. If SmartScreen says "Windows protected your PC", click **More info**, then **Run anyway**.
4. Start Resolve. Film Emulation is under **Color page > Effects > OpenFX > Filters > Film Lab**.

New versions install by themselves at startup, every 15 minutes and when the network connects, and a Windows notification tells you when one is installed. If Resolve was open, restart Resolve to use the new version. If you installed before version 3.3, run **Install Film Emulation.cmd** once more to get the notifications. To uninstall, double-click **Uninstall Film Emulation.cmd** in the same folder.

To see which version you have, look at the **Version** line at the very top of the Film Emulation panel.

## Install by hand (no automatic updates)

Download the Mac or Windows zip from the [latest release](https://github.com/diamondminer9908/film-emulation/releases/latest). Each zip has install instructions and a Getting Started guide.

## What's new

Each [release](https://github.com/diamondminer9908/film-emulation/releases) lists what changed in that version.
