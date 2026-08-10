# Natzirt-BK

Making Subaru tuning software work on Linux. currently focused on CachyOS since that's the distro I use.

Working setups include fully functional **RomRaider Editor**, **RomRaider Logger**, and
**EcuFlash**. **EvoScan** support is currently in development.

The DimeMod version of RomRaider Editor and Logger are used.
EcuFlash with an authentic Tactrix OpenPort 2.0.
EvoScan project ongoing...


## Current project

- [Subaru ECU Tools for Linux](https://github.com/Natzirt-BK/subaru-ecu-tools-linux) — an experimental OpenPort 2.0 Wine bridge for EcuFlash, plus portable RomRaider editor and logger launch helpers.

The main upstream fork was built on:

  - NikolaKozina/j2534 — https://github.com/NikolaKozina/j2534
    This supplied the OpenPort 2.0 J2534/libusb foundation. The EcuFlash Wine driver and launch fixes extend this project.

  Oh and consulted these as USB-driver references:

  - mcuee/libusb-win32 — https://github.com/mcuee/libusb-win32
  - mcuee/libusbk — https://github.com/mcuee/libusbk

  NikolaKozina/j2534—was the important foundation. The mcuee repositories were references during troubleshooting, not code we directly included in my published
  repository.


The focuses on this project are reproducible setup instructions, Wine compatibility,
hardware-access fixes, and cautious read-only validation before any ECU writing
is attempted so as to not brick the ECU. 
