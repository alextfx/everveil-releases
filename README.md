# Everveil desktop launcher downloads

This repository holds the installers of the desktop launcher for [Everveil](https://playeverveil.com), a fantasy role-playing game you can also play in a browser. There is no source code here: only releases. Get the current build from the [Releases](https://github.com/alextfx/everveil-releases/releases) page or from https://playeverveil.com/download/.

## The builds are not signed yet

Your system will warn you the first time you open one. Signed builds will follow.

- **macOS** (`.dmg`): open it and drag Everveil to Applications. The first time, macOS says it could not verify "Everveil". Close the message, open System Settings → Privacy & Security, and choose **Open Anyway**. On macOS 13 and 14: Control-click the app and choose **Open**.
- **Windows** (`.exe`): the blue SmartScreen box appears. Choose **More info**, then **Run anyway**. The publisher shows as unknown.
- **Linux** (`.AppImage`): `chmod +x` the file and run it. Ubuntu 22.04 and later need `libfuse2`.

The Windows and Linux builds were made on a Mac and have not yet been run on a real machine. If one does not start, play in your browser at https://playeverveil.com and tell us.

`SHA256SUMS.txt` in each release lists the checksum of every file.
