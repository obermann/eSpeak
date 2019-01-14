# eSpeak
EventGhost plugin for using eSpeak text to speach program.

## Installation
eSpeak installation does not contain **libespeak.dll** which is required for this plugin.
Portable 32-bit libespeak.dll for eSpeak version 1.48 is supplied with this plugin 
(in its directory) -- you are free to use and relocate it as eSpeak licence permits.

If you did not run eSpeak installation program, system has no eSpeak **registry** record
and no environment variable **ESPEAK_DATA_PATH** with the path of the directory which contains 
the **espeak-data** directory. You can configure plugin to you use eSpeak without them, 
just locate espeak-data directory containing data of metioned eSpeak version.
The configuration failures will be printed to EventGhost log.

## FAQ
*Why not eSpeakNG?*

Because original eSpeak has integration with [MBROLA](http://tcts.fpms.ac.be/synthesis/mbrola.html):  
https://github.com/espeak-ng/espeak-ng/issues/76

*What's a use case?*

When listening to podcasts without display use your remote control with [EventGhost](http://www.eventghost.net) to hear the duration/position of/on the track (you certainly can do it with [XMPlay audio player](https://github.com/obermann/XMPlay)). For Lithuanian language use [SkaitvardisPlugin](https://github.com/obermann/SkaitvardisPlugin) and Lithuanian [MBROLA voices](https://github.com/numediart/MBROLA-voices).

## Resources
[eSpeak](http://espeak.sourceforge.net)

[eSpeak Documentation](http://espeak.sourceforge.net/docindex.html)

[Search Path Used by Windows to Locate a DLL](https://docs.microsoft.com/en-us/windows/desktop/Dlls/dynamic-link-library-search-order)

[MBROLA](http://tcts.fpms.ac.be/synthesis/mbrola.html)

[MBROLA on Github](https://github.com/numediart)
