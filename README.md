# my_first_tts_script
Learning Lua and TableTop Simulator

## Setup
* The main mod needs to be downloaded from [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2086541048). (Authentication Required)
* It should have 2 files that point to the github tracked source code. 
* Your scripts and UI should be nothing more than a single `#include file` or `<Include src="file"/>`
  * Note: If you have the TTS Console installed (see below) then you will see a lot of code from that too.

For example, `Global.-1.ttslua` contains:
```
-- steam workshop id = 2086541048
#include my_first_tts_script\my_first_tts_script
```
* Clone this repo to `C:\Users\<username>\Documents\Tabletop Simulator\my_first_tts_script` and the `#include` will pick it up.

## Recommended Tools
* VSCode [Tabletop Simulator Lua extension](https://github.com/rolandostar/tabletopsimulator-lua-vscode)
  * Gets/Sends scripts
  * Syntax Highlighting
  * Automatically installs [TTS Console](https://github.com/onelivesleft/Console)
    * Adds a > debugging console into TTS's chat
  * Usage
    * Ctrl+Alt+` : Open TTS Console++
    * Ctrl+Alt+L: Get Lua Scripts
    * Ctrl+Alt+S: Save And Play

* [EmmyLua](https://github.com/EmmyLua/VSCode-EmmyLua) 
  * Depends on JDK 8 (aka 1.8) `choco install jdk8`
  * Lua IDE/Debugger Plugin for VSCode
  
* [TTS Community Moonsharp debugger](https://github.com/tts-community/moonsharp)
  * VSCode integration
  * Step through code
  * Real time variable inspection
  * Install Notes
    * Requires copying the MoonsharpDef.dll from the release into the `TTS Install Folder\Tabletop Simulator_Data\Managed`
    * [How to setup a launch.json](https://code.visualstudio.com/docs/editor/debugging#_launch-configurations) to enable the debugger 

## Helpful Directories
* Saved Games: `C:\Users\dlardo\Documents\My Games\Tabletop Simulator\Saves`
* TTS Install Folder: `C:\Program Files (x86)\Steam\steamapps\common\Tabletop Simulator\`
