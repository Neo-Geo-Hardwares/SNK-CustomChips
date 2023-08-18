# SNK - Neo-Geo Custom Chips
 
Neo-Geo was introduced to the world on 1990.

The Neo Geo originally launched as the Multi Video System (MVS) coin-operated arcade machine. 

With its games stored on self-contained cartridges, a game cabinet can easily be changed to a different game title by swapping the game's cartridge and cabinet artwork.

The Neo Geo was marketed as the first 24-bit system; its CPU is actually a 16/32-bit 68000 with an 8-bit Z80 coprocessor, while its GPU chipset has a 24-bit graphics data bus. 

## This Repository

On this Repository, you will find the KiCad Custom Library with definition of SNK's custom chips:

### Sony Ram ICs
- **CXK5814P** : Fast Ram 2048 word x 8 bit High Speed CMOS Static RAM
- **CXK5863AP** : Fast Ram 8192 word x 8 bit High Speed CMOS Static RAM

### SNK ICs
- **LSPC2-A2** : NEO-GEO LSPC2 Custom Chip
- **NEO-B1** : Both fix graphics from the S ROM and serialized sprite graphics from the C ROMs are fed to NEO-B1 for display on screen via 2 pairs of alternating line buffers
- **NEO-C1** : Multi-purpose keystone chip used for address decoding, inter-CPU communications, wait cycle generation, and player inputs.
- **NEO-E0** (_MV2B_) : 24-bit buffer and logic for 68k vector table swapping (Version MV2B)
- **NEO-E0** (_MV2F_) : 24-bit buffer and logic for 68k vector table swapping (Version MV2F)

### Toshiba
**TC53100AP** : 128K Word x 8 bit CMOS Mask Rom

### Others
**UPD4990AC** : Serial I/O Calendar & Clock CMOS LSI
**CRE401** : Custom Hybrids ICs
