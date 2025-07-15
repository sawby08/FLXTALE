# FLXTALE (Sawby's fork)
## Hello!
<p>Hi! This is a fork of nennneko5787's FLXTALE engine that I made to fix some bugs and try to maintain myself so I can learn HaxeFlixel a little. Don't expect a lot of activity from here!</p>

## How to Build
1. Download and install [Haxe](https://haxe.org/download/).
2. Execute the following commands in your Command Prompt/Terminal:

- [(Download Git from here if you don't have it!)](https://git-scm.com/)
```
haxelib install hmm
haxelib run hmm install
haxelib run lime setup flixel
haxelib run lime setup
haxelib run flixel-tools setup
haxelib set lime 8.0.1
haxelib set openfl 9.2.1
haxelib set flixel 5.2.2
haxelib set flixel-tools 1.5.1
haxelib set flixel-addons 3.0.2
haxelib set flixel-ui 2.5.0
```
For Windows users, download the [Visual Studio build tools](https://aka.ms/vs/17/release/vs_BuildTools.exe).
On the Visual Studio installer screen, go to the "Individual components" tab and only select these options:
- MSVC v143 VS 2022 C++ x64/x86 build tools.
- Windows 10/11 SDK.

<p>The game can be built with `lime build windows` if you're on windows, `lime build mac` if you're on MacOS or `lime build linux` if you're on a linux distro.<br><br>To build the game to HTML5, remove the Discord Rich Presence and the crash handler from Main.hx.</p>