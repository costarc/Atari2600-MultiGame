# Atari 2600 MultiGame Cartridge

Bill of material
--
Bill of Material is in interactive mode - click on file https://github.com/costarc/Atari2600-MultiGame/blob/master/ibom.html (you may need to download to your local computer to see it properly)

## 📖 The Book

This project is **Chapter 6, "Atari 2600 MultiGame"**, in a book:

**Chips, Code, and Cartridges: Turn Curiosity into Creation with 13 Hands-On Projects, from 8-bit Classics to FPGAs**

It walks through thirteen of my own hardware and software projects, from 8-bit classics to FPGAs, for beginners and curious makers. Each chapter explains how one project works and how to build it, with colour diagrams and real code from its repository.

### 👉 [Get the book on Amazon](https://link.amazon/B013Yaq9y)

<sub>As an Amazon Associate, the author earns from qualifying purchases. Buying through this link
supports these projects at no extra cost to you.</sub>

# Description

This cartridge supports 2K and 4K games.
2K games must be 4K as well (two copies of the same file appended). For example, the followign two commands will (compatible with Mac OS, Linux and CygWin in windows) will create a 4kgame.bin file with two copies of the same 2kgame.bin:<br>
<code>
cat 2kgame.bin >  4kgame.bin<br>
cat 2kgame.bin >> 4kgame.bin<br>
</code>
<br>
The PCB supports 27C512 ROMs and EPROMS and can hold up to 16 games, switchable via the DIP Switch at the back of the cartridge.

