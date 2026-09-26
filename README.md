# RedBox QEMU for Windows

RedBox QEMU is a Windows desktop GUI frontend for QEMU, designed to make creating, configuring, and running virtual machines easier through a simple graphical interface.

> ⚠️ RedBox QEMU is currently in early Alpha development. Features may change and bugs may occur.

## Features

- Create and manage multiple virtual machines
- Create QCOW2 and RAW virtual disks
- Use existing virtual disk images
- Attach bootable ISO images
- Configure RAM and CPU cores
- PC (i440FX) and Q35 machine types
- BIOS / SeaBIOS configuration
- Display device selection
- Network device selection
- Sound device selection
- WHPX and TCG acceleration options
- Boot priority configuration
- Start saved virtual machines with QEMU
- Edit existing virtual machine configurations
- View detailed VM information
- Delete virtual machines from RedBox
- Built-in QEMU log viewer
- Configurable QEMU executable path
- Dark Windows desktop interface

## Requirements

- Windows 10 or Windows 11 (64-bit)
- QEMU for Windows
- 64-bit PC

RedBox QEMU currently expects a QEMU installation containing:

`qemu-system-x86_64.exe`

The QEMU executable path can be configured from **Settings** inside RedBox QEMU.

## Installation

1. Download the latest RedBox QEMU installer from the **Releases** section.
2. Run the installer.
3. Follow the setup wizard.
4. Launch RedBox QEMU.
5. Make sure the QEMU executable path is configured correctly.
6. Create or add a virtual machine.

## Virtual Machine Data

RedBox QEMU stores its virtual machine configuration data under:

`%LOCALAPPDATA%\RedBoxQemu\VMs`

RedBox-created virtual disks are stored inside their corresponding VM folders.

External disk images and ISO files selected by the user remain in their original locations.

## QEMU

RedBox QEMU is a graphical frontend for QEMU.

QEMU is a separate project and is not developed by Rimvydop.

RedBox QEMU v0.0.1 Alpha does not bundle QEMU. Users need to install QEMU separately.

## Development Status

RedBox QEMU is under active development.

## Disclaimer

RedBox QEMU is experimental Alpha software. Back up important virtual machines and disk images before use.
