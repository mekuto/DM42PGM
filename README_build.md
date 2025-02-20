---
layout: docu
---

# Building Instructions

## Prerequisites

GNU ARM toolchain can be downloaded from
  https://developer.arm.com/open-source/gnu-toolchain/gnu-rm/downloads.
We are currently using Version 7-2018-q2-update Linux 64-bit.

Make is usually available in some base development package, but you
can install it directly, e.g. for debian like systems
```
  sudo apt-get install make
```

Basic shell utilities (usually present in system):
```
  bash, dd, sed, tac, printf, find, etc.
```

Some usually available aux utilities (could require separate installation):
```
  crc32, sha1sum
```



## Build

Add ARM toolchain bin/ directory to PATH.
```
(e.g. ~/arm/gcc-arm-none-eabi-7-2018-q2-update/bin)
```

Run make to build the program.

Generated program 
```
  build/DM42PGM.pgm
```

Contents of QSPI
```
  build/DM42PGM_qspi.bin
```



## DM42PGM repository

The latest version of DM42PGM is available at
  [https://github.com/swissmicros/DM42PGM](https://github.com/swissmicros/DM42PGM)




