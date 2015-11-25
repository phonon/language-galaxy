# Atom SCII Galaxy language support

Atom support for Blizzard's StarCraft II Galaxy scripting language. Contains language syntax highlighting and Blizzard native/builtin functions and constants highlighting and autocompletion snippets.

Natives and builtins were parsed using a python script (gist.github.com/nmosfet/d8ec8a2f2cd9402b2ca7). Natives declarations can be found inside Blizzard StarCraft II CASC libraries ("SC2Data" folder in the Blizzard StarCraft II installation folder).

Blizzard files used for constant and function grammar and snippet matching are:
- natives.galaxy
- NativeLib_h.galaxy
- AI.galaxy
- LibertyLib_h.galaxy
- SwarmLib_h.galaxy
- VoidLib_h.galaxy
- GameData.galaxy
