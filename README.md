# VehControl FlavyV Re-Edit | VehControl NUI Menu

# To Change Resource Name
  > Replace fv-vehcontrol in vehui.html with your name you want to name it

# Use For Radial Menu 

      {
         id = 'openmenu',
         title = 'Open Control Menu',
         icon = 'car',
         type = 'client',
         event = 'vehcontrol:openExternal',
         shouldClose = true
      },

# NUI visual menu vehicle script for FiveM

![image](https://i.imgur.com/9thToV6.png)

## Features

* Control
    - Hood
    - Trunk
    - Doors
    - Windows
    - Interior Light
    - Change Seats
    - Leave Engine Running on Exit

## NUI Controls

**Open** - Script Default: HOME

- Script Default can be changed via config

- Client changeable via Settings->Keybinds->FiveM game menu

**Close** - ESC

## Commands

**/engine** - Start/Stop Vehicle Engine

**/hood** - Open/Close Hood

**/trunk** - Open/Close Trunk

**/seat** [1-4]- Move Seat

**/door** [1-4] - Open/Close Door

**/window** [1-4] - Roll Up/Down Window

**/windowfront** - Roll Up/Down Front Windows

**/windowback** - Roll Up/Down Back Windows

**/windowall** - Roll Up/Down All Windows

**/vehcontrolclose** - Close NUI (in F8 if stuck open)

## Config
UseCommands [true/false] - Allow the use of /commands

DisableSeatShuffle [true/false] - Allow auto-seat shuffle from passenger to driver

LeaveRunning [true/false] - Allow the engine to keep running on exit of the vehicle with a long F keypress

DefaultOpen - This is they default key to open the menu, client can change in the game menu (Settings->Key Binds->FiveM)

- USABLE KEY LIST https://docs.fivem.net/docs/game-references/input-mapper-parameter-ids/keyboard/

## Exporting and Events

The following ways can be used to open the menu from another resource depending on how the resource is coded

Open menu from another resource with exports
>```exports.vehcontrol:openExternal()```

Open menu from another resource with events
>```TriggerEvent("vehcontrol:openExternal")```

## TODO

** Nothing So Far **

Feature request can be made [Here](https://github.com/Flaruto/fv-vehcontrol/issues/new)

## Changelog

** Nothing So Far **

## Bug

** Nothing So Far **

## Original 

https://github.com/Manvaril/vehcontrol

## License

Copyright 2020 Manvaril

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
