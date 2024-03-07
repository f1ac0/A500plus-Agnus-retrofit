# A500+ Agnus retrofit
I accidentally zapped my precious 8375 Agnus with ESD on my A500(+) rev8 motherboard, and I am planing to use a cheaper 8371 to continue the development of the Pistorm'X500 and other Amiga projects.

It is based on the same idea as the DietAgnus https://github.com/LIV2/Diet-Agnus-A500-plus except I plan to keep the PLCC84 socket to restore the original system later on. I am also looking forward modern replacement projects such as the ReAgnus https://github.com/jbilander/ReAgnus or https://github.com/jbilander/ReAgnus-MegAChip.

There are two versions in this repository :
- The Through Hole version was the first one I designed : it is based on a TH PLCC84 socket connected to a "plug" PCB using standard 2.54mm pin headers ; to ensure the contact with the motherboard socket, the plug PCB needs to mimic the PLCC "legs" with the addition of single core wires soldered from each top pad to its bottom counterpart all around the edges.
- The SMD version uses a SMD PLCC84 socket ; four strips of 1.27mm angled pin headers with a 0.46mm square section are used as contacts to the motherboard socket ; the spacer PCB(s) should help to solder the pins in place, push them on the contacts of the motherboard socket, and make it rigid enough to stay in place (stack two or 3 and glue them together).

These are not tested yet.

# Disclaimer
This is a hobbyist project, it comes with no warranty and no support. Also remember that the Amiga machines are about 30 years old and may fail because of such hardware expansions.

There are many Agnus versions and Amiga motherboards, so you really should look for information about the specific parts you plan to use.

I publish my work under the CC-BY-NC-SA license.

If you find it useful and want to reward my hard work : I am always looking for Amiga/Atari/Amstrad/Commodore/Sinclair/Thomson... to repair and hack, please contact me.

# Making it
Pull _XCLKEN to 5V using either a solder blob or a resistor.

If your Agnus is marked with VBB, install a 0.1uF ceramic cap on the TEST/VBB pin. Otherwise it may be closed to switch to NTSC.

