# Atari 2600 MultiGame Cartridge

Bill of material
--
Bill of Material is in interactive mode - click on file https://github.com/costarc/Atari2600-MultiGame/blob/master/ibom.html

# Description

This cartridge supports 2K and 4K games.
2K games must be 4K as well (two copies of the same file appended). For example, the followign two commands will (compatible with Mac OS, Linux and CygWin in windows) will create a 4kgame.bin file with two copies of the same 2kgame.bin:<br>
<code>
cat 2kgame.bin >  4kgame.bin<br>
cat 2kgame.bin >> 4kgame.bin<br>
</code>
<br>
The PCB supports 37C512 ROMs and EPROMS supoprts up to 16 games switchable via the DIP Switch at the back of the cartridge.

