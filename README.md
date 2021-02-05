# my_first_tts_script
Learning Lua and TableTop Simulator

## Setup
* The main mod needs to be downloaded from [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2086541048). (Authentication Required)
* It should have 2 files that point to the github tracked source code. 
* Your scripts and UI should be nothing more than a single `#include file` or `<Include src="file"/>`
  * Note: If you have the Moonsharp debugger installed (see below) then you will see a lot of code from that too.

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

* [EmmyLua](https://github.com/EmmyLua/VSCode-EmmyLua) 
  * Depends on JDK 8 (aka 1.8) `choco install jdk8`
  
* [TTS Community Moonsharp debugger](https://github.com/tts-community/moonsharp)
  * VSCode integration
  * Step through code
  * Real time variable inspection

* [TTS Console](https://github.com/onelivesleft/Console)
  * Adds a > debugging console into TTS's chat
