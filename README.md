# Ripple

Targeted to be the build environment Kali / RPI 3B+ / PineApple

- Kali is up ad running along with support for iwconfig and rmon capabilities.  Using the Alfa High Gain USB 3.0 adapter.  Unfortunately  this is the version where the mfgtr implemented bot past and future standards withint the firmware.

Full functionality of the Wifi is working although the init sequence requires alternative / non-standard enablement at times.  This will not be fixed so currently determining if this is enough hassel to bother with another wireless adapter.  If so then I can finalize config when the new wireless adaqpter arrives. TBD

Currently:

   - Running with Kali on a RPI 3B+ with 64 GB SSD & 32GB SD Card
   - Disk image is GPT.  This standard has a 16 MB FAT16 file systeam starting at 4Kb to 16Mb for /boot,  then a Full Sized 512MB-1Gb (max) which can be FAT32 os EXT2.  This file system is specific to the RPIso please monitor the NOOBS disk releases notes.

PineApple content was reviewed and the initial capture of their portal has begun.  Givent that it is primarily dd-wrt build it is yet to be determined whether this is a wishful thinking endeavor of an earnest effort.  Tying in the Wireless AP may occure sometime in the future pending.  
