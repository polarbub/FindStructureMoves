# FindStructureMoves
This is a mod for developing the Protosky mod. The Protosky mod skips a step of world generation where some structures 
are moved to their final locations. This detects which structures do that, so they can be moved down without placing the blocks. 
This mod doesn't work at the same time as the Protosky mod as this mod hooks into structure generation which the Protosky mod
skips.

### Usage
This mod add two commands

`/detectStructureMoves <player> (all|<structure>)`

This teleports the specified player either to all known structures or just the specified one to check if they move.

`/detectStructureMoves stop`

This stops `/detectStructureMoves <player> all` before it has gone through all structures.

### I would forget otherwise
Patch releases: 1.0 or 1.0.x or ~1.0.4  
Minor releases: 1 or 1.x or ^1.0.4  
Major releases: * or x  

### Licence

Copyright (C) 2023  polarbub

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <https://www.gnu.org/licenses/>.
