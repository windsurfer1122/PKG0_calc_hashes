# PKG0_calc_hashes.py by "windsurfer1122" (c) 2018
Calculate hashes for data blocks inside PS3/PSX/PSP/PSV/PSM packages.

Goals:
* Build CMAC and SHA-1/256 hashes of data, just like it is used in the 0x40 digest of PKG0 packages (PS3/PSX/PSP/PSV/PSM)
* Support of all known package types: PS3/PSX/PSP, PSV/PSM
* Easy to maintain and no compiler necessary (=interpreter language)
* Cross platform support
  * Decision: Python 3
    * Compatible with Python 2 (target version 2.7)
      * Identical output
      * Forward-compatible solutions preferred

For options execute: PKG0_calc_hashes.py -h<br>
Use at your own risk!


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


git master repository at https://github.com/windsurfer1122
