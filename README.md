# MK-LAB FEMcab

Modal analysis of loudspeaker cabinets. FEMcab reads a cabinet as a STEP file, meshes it and computes at which
frequencies its walls vibrate, and how: the shape of every mode, the boards that carry it, and how strongly the
drivers excite it. Variants with other materials, drivers or braces are computed and compared side by side.

This page only holds the downloads. FEMcab is free software under the GNU General Public License, version 3 or
later; its source code comes with every installer, in the folder `source`. One term is added under section 7(b)
of the licence: whoever passes FEMcab or a work based on it on, in whole or in part, keeps its copyright notices
and writes “Based on MK-LAB FEMcab by MK-LAB, https://mk-audiolab.de” in their licence notices and
documentation. The full text is in the file `NOTICE`, next to the licence.

## Download

Under [Releases](../../releases/latest), with the SHA-256 checksum of every file next to it:

| System | File | Size |
|---|---|---|
| Windows 10 or 11, 64 bit | `FEMcab-0.4.0-setup.exe` | 199 MB |
| macOS with an Apple chip (M1 and later) | `FEMcab-0.4.0-macos-arm64.sh` | 162 MB |
| macOS with an Intel chip | `FEMcab-0.4.0-macos-x86_64.sh` | 176 MB |
| Linux, x86-64 (Ubuntu 20.04, Debian 11 and newer) | `FEMcab-0.4.0-linux-x86_64.sh` | 372 MB |

**Windows:** run the file. It installs for the signed-in user, without administrator rights, and takes about 1 GB.
The installer is not signed yet, so Windows SmartScreen may warn on its first start: click “More info”, then
“Run anyway”.

**macOS:** in the Terminal, `sh ~/Downloads/FEMcab-0.4.0-macos-arm64.sh` (on an Intel Mac `…-macos-x86_64.sh`).
FEMcab is then in `~/Applications` and opens in a Terminal window; closing that window ends it.

**Linux:** in a terminal, `sh FEMcab-0.4.0-linux-x86_64.sh`, without root. It takes about 1.5 GB; FEMcab is then
in the applications menu and runs in a terminal window.

## First steps

At the first start a short tour leads through the program, with an example box to try it on. It comes back under
“Help → Take the tour”.

## Problems

In FEMcab: “Help → Report a problem …”. If the server cannot be reached, the report waits and goes out later by
itself, or you save it as a file and send it by email to info@mk-audiolab.de.

More about FEMcab: https://mk-audiolab.de
