# NatZirt BK

Independent community software for Subaru and Mitsubishi ECU editing, diagnostics,
logging, and Linux compatibility.

## Projects

| Project | Purpose | Current status |
| --- | --- | --- |
| [RomRaider2 downloads](https://github.com/Natzirt-BK/RomRaider2-Releases/releases) | Desktop and Android ROM editing, vehicle logging and datalog review | Public **1.1.12 RC1** testing builds; 1.1.13 remains in private development |
| [ECU Tools for Linux](https://github.com/Natzirt-BK/subaru-ecu-tools-linux) | EcuFlash and DimeMod installation, OpenPort 2.0 compatibility, plus a pinned RomRaider2 package | Linux installer currently targets RomRaider2 **1.1.12** |
| [SubaruDefs](https://github.com/Natzirt-BK/SubaruDefs) | Subaru ECU calibration definitions | Historical Stable and Alpha branches plus experimental A2WC412I work |

RomRaider2 is under active development. Linux is the primary qualification
platform; Windows and Android are also development targets. macOS work is
deferred. The private RomRaider2 source repository is not a public download
location. Release candidates and their corresponding source archives are
available from the public downloads link above.

## Compatibility and safety

RomRaider2 does **not** currently provide production ECU flashing or live
tuning. EcuFlash is a separate program in the Linux tools setup; it is not
a RomRaider2 flashing feature. Vehicle compatibility must be verified for
the exact ECU, adapter, driver, definition, and operation. Keep original ROM
backups and do not treat software-only tests as proof of safe physical writes.

## Credits

These projects build on upstream work from
[RomRaider](https://github.com/RomRaider/RomRaider),
[DimeMod](https://github.com/DimeSPb/RomRaider), and
[NikolaKozina/j2534](https://github.com/NikolaKozina/j2534).
The [libusb-win32](https://github.com/mcuee/libusb-win32) and
[libusbK](https://github.com/mcuee/libusbk) repositories were consulted as
driver references, not directly included as source in the published
ECU Tools repository. Each project retains its own licence and third-party
attribution.
