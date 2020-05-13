# my_first_tts_script
Learning Lua and TableTop Simulator

## Setup
The main mod needs to be downloaded from [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2086541048). 
It should have 2 files that point to the github tracked source code. Your scripts and UI should be nothing more than a single `#include file` or `<Include src="file"/>`

For example, `Global.-1.ttslua` contains:
```
-- steam workshop id = 2086541048
#include my_first_tts_script\my_first_tts_script
```

Contents of this repo should live in `C:\Users\<username>\Documents\Tabletop Simulator\my_first_tts_script`

## Dependencies
Requires VSCode installed with [Tabletop Simulator Lua extension](https://github.com/rolandostar/tabletopsimulator-lua-vscode)

Optional but recommended: [EmmyLua](https://github.com/EmmyLua/VSCode-EmmyLua) and [TTS Community Moonsharp debugger](https://github.com/tts-community/moonsharp)
