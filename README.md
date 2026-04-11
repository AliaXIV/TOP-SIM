# TOP-SIM
**The Omega Protocol (Ultimate) simulator for FFXIV.**

This is a solo, offline simulator for TOP fight in FFXIV, built with the idea of being as accurate as possible to the game. 
As of now it only supports [LPDU](https://discord.com/invite/lpdu) strats, implementation of other DC strats is planned as well.

Currently in development. Codebase of the project will be added in the future (once I figure out what to do with all the assets).

## Instructions

The sim files are provided on the [Releases](https://github.com/AliaXIV/TOP-SIM/releases) page. After unziping the archive run the `TOP-SIM.exe`. Camera and keybind configuration is available after pressing `[Esc]` button.  The UI as of now can only be handled with mouse.

## Features

- Timeline based simulation with bots
- Selectable raid position
- Automarker (accurate to the most common settings) on all P5 mechanics
- Controller support

### Mechanics

| Mechanic                     | Status                          | Info        |
|---------------------------|--------------------------------------|--------------|
| P1 Looper                 | ❌ Planned (Late) | Everyone does Looper a bit differently so its difficult to accurately sim it |
| P1 Pantokrator            | ❌ Planned (Late) | Everyone does Panto differently, not sure yet how to implement bot behaviour there |
| P2 Party Synergy          | ✅ Complete       | --- |
| P2 Limitless Synergy      | ❌ Planned (Late) | Probably does not require sim at all, but will get implemented for consistency |
| Intermission              | ⏳ Planned        | --- |
| P3 Hello World            | ❌ Planned (Late) | --- |
| P3 Monitors               | ✅ Complete       | --- |
| P4                        | ⏳ Planned        | --- |
| P5 Delta                  | ✅ Complete       | --- |
| P5 Sigma                  | ✅ Complete       | --- |
| P5 Omega                  | ✅ Complete       | --- |
| P6 Exalines               | ✅ Complete       |  Two options, with Cosmo Dive 1 and Wave Cannon 2|
| P6 Full Phase             | 🚧 In Progress    | Because of the nature of P6 (pacing, full body/consistency check) entire P6 sim is planned in the future |

## TODO
 - Implement remaining mechanics
 - RNG customization per fight
 - Other DC strats
 - Pause simulation option
 - Free Cam "observer" mode
 - Automarker toggle for certain mechanics
 - Add gapclosers
 - Add cast bars and enmity list
 - Add correct animations and replace some of the generic AoE effects with dedicated ones that are more accurate to how game renders it
 - Scaling and repositioning of UI elements
 - UI control with a controller

## Known issues
- Delta Same RNG is not working correctly
- On simulation failure characters keep their animation if they were moving
- Fauilure list is not scrolling properly when it's overflowed
- Some character models have issues with clipping of some parts of the models

# About

If you encountered any issues or problems make sure to let me know via [GitHub issue system](https://github.com/AliaXIV/TOP-SIM/issues)!

This is a passion project I'm developing in my free time. If you found it helpful and want to support a project you can do so with [![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/aliaxiv) 😊
