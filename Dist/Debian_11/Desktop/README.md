Debian 11 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ Kernel                   ](#kernel)
  - [ Kernel Family            ](#kernel-family)
  - [ Kernel Major Ver.        ](#kernel-major-ver)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linuxbsd)
  - [ Dual Boot (Win)          ](#dual-boot-win)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Secure Boot              ](#secure-boot)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Op-Modes             ](#cpu-op-modes)
  - [ CPU Microcode            ](#cpu-microcode)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte   | GA-78LMT-USB3               | [31d159af99](https://linux-hardware.org/?probe=31d159af99) | Aug 06, 2021 |
| Lenovo     | Board                       | [18138486db](https://linux-hardware.org/?probe=18138486db) | Aug 05, 2021 |
| Intel      | DN2820FYK H24582-201        | [7caf949908](https://linux-hardware.org/?probe=7caf949908) | Aug 05, 2021 |
| Unknown    | Intel X79                   | [fc0dedbb3c](https://linux-hardware.org/?probe=fc0dedbb3c) | Aug 05, 2021 |
| Gigabyte   | 970A-D3                     | [91825066e0](https://linux-hardware.org/?probe=91825066e0) | Aug 04, 2021 |
| HP         | 3047h                       | [6294617672](https://linux-hardware.org/?probe=6294617672) | Aug 03, 2021 |
| ASRock     | FM2A68M-HD+                 | [a7bdbd8ebe](https://linux-hardware.org/?probe=a7bdbd8ebe) | Aug 03, 2021 |
| ASUSTek    | PRIME B450-PLUS             | [55cd593df1](https://linux-hardware.org/?probe=55cd593df1) | Aug 03, 2021 |
| Gigabyte   | X399 AORUS XTREME-CF        | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| MSI        | 760GM-P23                   | [93b6f212af](https://linux-hardware.org/?probe=93b6f212af) | Aug 02, 2021 |
| Supermicro | X11SSH-F                    | [641e4fd8ce](https://linux-hardware.org/?probe=641e4fd8ce) | Aug 02, 2021 |
| ASRock     | H310CM-DVS                  | [f84e5eba5a](https://linux-hardware.org/?probe=f84e5eba5a) | Aug 02, 2021 |
| ASUSTek    | M4A785TD-M EVO              | [e90a873ad0](https://linux-hardware.org/?probe=e90a873ad0) | Aug 02, 2021 |
| ASUSTek    | P5QL-E                      | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| ASUSTek    | A88X-PRO                    | [ed95430eec](https://linux-hardware.org/?probe=ed95430eec) | Aug 02, 2021 |
| HP         | 2187 A01                    | [16bfdd86e3](https://linux-hardware.org/?probe=16bfdd86e3) | Aug 02, 2021 |
| Gigabyte   | 970A-DS3P                   | [61886d812f](https://linux-hardware.org/?probe=61886d812f) | Aug 01, 2021 |
| ASRock     | J1900D2Y                    | [0dc4afc8c4](https://linux-hardware.org/?probe=0dc4afc8c4) | Aug 01, 2021 |
| ASRock     | N68C-S UCC                  | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| Dell       | 0WVYMC A00                  | [4d2aa42e3c](https://linux-hardware.org/?probe=4d2aa42e3c) | Jul 31, 2021 |
| ASUSTek    | Pro WS WRX80E-SAGE SE WI... | [159ff0ba7f](https://linux-hardware.org/?probe=159ff0ba7f) | Jul 31, 2021 |
| ASRock     | Z370M-ITX/ac                | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| ASUSTek    | Pro WS WRX80E-SAGE SE WI... | [3f0c3901f6](https://linux-hardware.org/?probe=3f0c3901f6) | Jul 30, 2021 |
| MSI        | Z490-A PRO                  | [b882a9cf0d](https://linux-hardware.org/?probe=b882a9cf0d) | Jul 29, 2021 |
| MSI        | Q45MDO                      | [ab547f0047](https://linux-hardware.org/?probe=ab547f0047) | Jul 29, 2021 |
| MSI        | Q45MDO                      | [6b5aaa6969](https://linux-hardware.org/?probe=6b5aaa6969) | Jul 29, 2021 |
| Dell       | 0TY915                      | [9cb5aed659](https://linux-hardware.org/?probe=9cb5aed659) | Jul 29, 2021 |
| Gigabyte   | B550M AORUS PRO-P           | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| ASUSTek    | LEONITE                     | [3bf9048839](https://linux-hardware.org/?probe=3bf9048839) | Jul 29, 2021 |
| Foxconn    | 2AA9                        | [920a813aaf](https://linux-hardware.org/?probe=920a813aaf) | Jul 29, 2021 |
| ASRock     | B85M Pro4                   | [32e615b538](https://linux-hardware.org/?probe=32e615b538) | Jul 29, 2021 |
| ASRock     | FM2A88X Extreme6+           | [f449b8ce85](https://linux-hardware.org/?probe=f449b8ce85) | Jul 29, 2021 |
| ECS        | H61H2-M12                   | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| MSI        | B450M PRO-VDH PLUS          | [cccaebb483](https://linux-hardware.org/?probe=cccaebb483) | Jul 28, 2021 |
| Gigabyte   | GA-990FX-GAMING             | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte   | GA-990FX-GAMING             | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [f96bcc3ab2](https://linux-hardware.org/?probe=f96bcc3ab2) | Jul 28, 2021 |
| Shuttle    | FX79R                       | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| ASUSTek    | PRIME X570-PRO              | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| ASRockRack | X570D4U-2L2T                | [7bb34c9dec](https://linux-hardware.org/?probe=7bb34c9dec) | Jul 27, 2021 |
| ASUSTek    | A88X-PLUS/USB               | [57b54cc925](https://linux-hardware.org/?probe=57b54cc925) | Jul 27, 2021 |
| ASRock     | N68C-GS FX                  | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| ASUSTek    | PRIME Z490-P                | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| Dell       | 0X8DXD A00                  | [7821dfc370](https://linux-hardware.org/?probe=7821dfc370) | Jul 27, 2021 |
| ASUSTek    | M4A785D-M PRO               | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| Foxconn    | 915MH Series                | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| ASUSTek    | PRIME H310M-R R2.0          | [dc4a709a3b](https://linux-hardware.org/?probe=dc4a709a3b) | Jul 27, 2021 |
| Dell       | 0WMJ54 A01                  | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| ASUSTek    | PRIME H310M-K R2.0          | [1e69873301](https://linux-hardware.org/?probe=1e69873301) | Jul 27, 2021 |
| Dell       | 0M863N A00                  | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Gigabyte   | P35C-DS3R                   | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI        | X399 GAMING PRO CARBON A... | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| MSI        | MEG X570 UNIFY              | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| ASRock     | Z97 Pro3                    | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| MSI        | Z370 SLI PLUS               | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| ASUSTek    | PRIME X370-PRO              | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock     | B450 Pro4                   | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP         | 2B38                        | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP         | 2B38                        | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock     | 970 Pro3 R2.0               | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek    | PRIME B550-PLUS             | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek    | PRIME B550-PLUS             | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASRock     | X570 Steel Legend           | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek    | PRIME B350-PLUS             | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Gigabyte   | AB350-Gaming 3-CF           | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Gigabyte   | AB350-Gaming 3-CF           | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek    | M5A78L-M LX3                | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Gigabyte   | B450M DS3H-CF               | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek    | B85-PRO GAMER               | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek    | M5A78L-M LX3                | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell       | 0D28YY A02                  | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock     | H470M-ITX/ac                | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| ASUSTek    | M5A78L-M LX3                | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek    | PRIME B450M-A               | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| MSI        | B450 TOMAHAWK MAX II        | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Gigabyte   | H110M-S2H-CF                | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell       | 0PTTT9 A00                  | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell       | 0X8DXD A00                  | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| ASUSTek    | PRIME H270M-PLUS            | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte   | Z170M-D3H-CF                | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| ASRock     | P67 Pro3                    | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro | A1SA2-2750FA                | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte   | H87-HD3                     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| ASUSTek    | ROG STRIX B450-I GAMING     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte   | AB350M-DS3H V2-CF           | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| Dell       | 0Y1057                      | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP         | ProLiant MicroServer Gen... | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock     | B450M Pro4                  | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| ASRock     | Z97 Extreme6                | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo     | 3098 0B98401 PRO            | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP         | 1495                        | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| HP         | 158A                        | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| HP         | 158A                        | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| ASUSTek    | H110M-A/M.2                 | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| Gigabyte   | H110N-CF                    | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| MSI        | MAG B550M MORTAR            | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell       | 0X8DXD A00                  | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP         | 2129                        | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Intel      | DP55WG AAE57269-407         | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock     | B85 Anniversary             | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte   | B550I AORUS PRO AX          | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte   | B550I AORUS PRO AX          | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Gigabyte   | Z97X-UD3H-CF                | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| ASUSTek    | PRIME B250M-A               | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| ASRock     | B450M Pro4                  | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| ASRock     | B450M Pro4                  | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Gigabyte   | H61MS                       | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Gigabyte   | H81M-S2H GSM                | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell       | 09KPNV A01                  | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| ASUSTek    | PRIME A320I-K               | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| ASUSTek    | H61M-K                      | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell       | 0NK5PH A00                  | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte   | Z77-D3H                     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| Intel      | DP55WB AAE64798-206         | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Protectli  | FW6                         | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek    | ROG STRIX Z390-F GAMING     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte   | X570 I AORUS PRO WIFI       | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek    | Z170-DELUXE                 | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte   | 970A-D3P                    | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Dell       | 0D441T A03                  | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| MSI        | H110I PRO AC                | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek    | PRIME Z370-A                | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek    | H87-PRO                     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI        | Z77MA-G45                   | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| ASRock     | FM2A68M-DG3+                | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Gigabyte   | B560M D3H                   | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| ASUSTek    | ROG STRIX Z370-H GAMING     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek    | P8Z68-V                     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| HP         | ProLiant MicroServer        | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| MSI        | A68HM-E33 V2                | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Huanan     | X99-F8 V2.0                 | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell       | 0M863N A00                  | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| MSI        | MPG B550 GAMING PLUS        | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek    | H81M-E                      | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP         | 2215                        | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| HP         | 2215                        | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| MSI        | MS-6712                     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| ASRock     | H77 Pro4-M                  | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte   | B550I AORUS PRO AX          | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| Gigabyte   | AX370-Gaming K7             | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| MSI        | B85M-G43                    | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| Huanan     | X99-8M-F V1.1               | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| ASRock     | FM2A68M-HD+                 | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Gigabyte   | Z370 AORUS Gaming 5-CF      | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte   | Z370 AORUS Gaming 5-CF      | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock     | B550 Pro4                   | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock     | X399 Taichi                 | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL | ODROID-H2                   | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING ... | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| Gigabyte   | AB350M-Gaming 3-CF          | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| MSI        | B450M MORTAR MAX            | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING ... | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| ASUSTek    | PRIME B450M-A               | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Gigabyte   | MCMLUAB-00                  | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| ASUSTek    | PRIME A320M-K               | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| Dell       | 0Y7WYT A00                  | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| ASUSTek    | Z97-AR                      | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| ASRock     | B450M Pro4                  | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| ASUSTek    | PRIME A320M-K               | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| ASRock     | B450M Pro4                  | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| ASUSTek    | M4A88T-M/USB3               | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Dell       | 0YXT71 A02                  | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| ASUSTek    | PRIME B550-PLUS             | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| ASUSTek    | P5B-Deluxe                  | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Gigabyte   | B450 AORUS PRO WIFI-CF      | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI        | B250M BAZOOKA               | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| MSI        | B450I GAMING PLUS AC        | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Gigabyte   | AB350M-D3H-CF               | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Gigabyte   | Z170X-GamingG1              | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| Gigabyte   | Z77-D3H                     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Lenovo     | MAHOBAY                     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| Biostar    | B450MH                      | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| Gigabyte   | EG41MF-US2H                 | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.10.0-8-amd64                 | 86       | 54.43%  |
| 5.10.0-7-amd64                 | 43       | 27.22%  |
| 5.10.0-6-amd64                 | 9        | 5.7%    |
| 5.11.22-1-pve                  | 3        | 1.9%    |
| 5.10.0-8-rt-amd64              | 2        | 1.27%   |
| 5.8.0-3-amd64                  | 1        | 0.63%   |
| 5.13.4                         | 1        | 0.63%   |
| 5.13.1a                        | 1        | 0.63%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1        | 0.63%   |
| 5.11.22-2-pve                  | 1        | 0.63%   |
| 5.11.0-21.1-liquorix-amd64     | 1        | 0.63%   |
| 5.11.0-16.1-liquorix-amd64     | 1        | 0.63%   |
| 5.10.46custom                  | 1        | 0.63%   |
| 5.10.42+truenas                | 1        | 0.63%   |
| 5.10.38-falcot                 | 1        | 0.63%   |
| 5.10.0-8-686-pae               | 1        | 0.63%   |
| 5.10.0-8-686                   | 1        | 0.63%   |
| 5.10.0-7-686-pae               | 1        | 0.63%   |
| 5.10.0-3-amd64                 | 1        | 0.63%   |
| 5.10.0-2-amd64                 | 1        | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 143      | 91.67%  |
| 5.11.22 | 4        | 2.56%   |
| 5.11.0  | 2        | 1.28%   |
| 5.8.0   | 1        | 0.64%   |
| 5.13.4  | 1        | 0.64%   |
| 5.13.1  | 1        | 0.64%   |
| 5.13.0  | 1        | 0.64%   |
| 5.10.46 | 1        | 0.64%   |
| 5.10.42 | 1        | 0.64%   |
| 5.10.38 | 1        | 0.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 146      | 93.59%  |
| 5.11    | 6        | 3.85%   |
| 5.13    | 3        | 1.92%   |
| 5.8     | 1        | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 153      | 98.08%  |
| i686   | 3        | 1.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 30       | 19.11%  |
| KDE5             | 29       | 18.47%  |
| Unknown          | 23       | 14.65%  |
| XFCE             | 16       | 10.19%  |
| MATE             | 14       | 8.92%   |
| Cinnamon         | 11       | 7.01%   |
| LXQt             | 6        | 3.82%   |
| Trinity          | 5        | 3.18%   |
| LXDE             | 5        | 3.18%   |
| i3               | 5        | 3.18%   |
| KDE              | 4        | 2.55%   |
| X-Cinnamon       | 3        | 1.91%   |
| GNOME Flashback  | 2        | 1.27%   |
| sway             | 1        | 0.64%   |
| lightdm-xsession | 1        | 0.64%   |
| GNUstep          | 1        | 0.64%   |
| Budgie           | 1        | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 107      | 68.59%  |
| Wayland | 20       | 12.82%  |
| Tty     | 19       | 12.18%  |
| Unknown | 10       | 6.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 56       | 35.67%  |
| Unknown | 35       | 22.29%  |
| GDM     | 30       | 19.11%  |
| SDDM    | 28       | 17.83%  |
| LightDM | 5        | 3.18%   |
| SLiM    | 2        | 1.27%   |
| XDM     | 1        | 0.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 70       | 44.87%  |
| ru_RU   | 13       | 8.33%   |
| en_GB   | 11       | 7.05%   |
| fr_FR   | 10       | 6.41%   |
| de_DE   | 8        | 5.13%   |
| Unknown | 7        | 4.49%   |
| C       | 4        | 2.56%   |
| pt_BR   | 3        | 1.92%   |
| pl_PL   | 3        | 1.92%   |
| es_ES   | 3        | 1.92%   |
| en_CA   | 3        | 1.92%   |
| nl_BE   | 2        | 1.28%   |
| es_AR   | 2        | 1.28%   |
| en_AU   | 2        | 1.28%   |
| uk_UA   | 1        | 0.64%   |
| sv_SE   | 1        | 0.64%   |
| sr_RS   | 1        | 0.64%   |
| ru_UA   | 1        | 0.64%   |
| ro_RO   | 1        | 0.64%   |
| it_IT   | 1        | 0.64%   |
| hu_HU   | 1        | 0.64%   |
| hr_HR   | 1        | 0.64%   |
| es_VE   | 1        | 0.64%   |
| es_US   | 1        | 0.64%   |
| en_PH   | 1        | 0.64%   |
| en_IN   | 1        | 0.64%   |
| en_IE   | 1        | 0.64%   |
| en_HK   | 1        | 0.64%   |
| cs_CZ   | 1        | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 80       | 50.96%  |
| BIOS | 77       | 49.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 117      | 75%     |
| Overlay | 14       | 8.97%   |
| Btrfs   | 13       | 8.33%   |
| Ext3    | 5        | 3.21%   |
| Zfs     | 4        | 2.56%   |
| Xfs     | 2        | 1.28%   |
| Unknown | 1        | 0.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 99       | 63.06%  |
| MBR     | 43       | 27.39%  |
| Unknown | 15       | 9.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 110      | 70.51%  |
| Yes       | 46       | 29.49%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 115      | 73.25%  |
| Yes       | 42       | 26.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 38       | 24.36%  |
| Gigabyte Technology | 34       | 21.79%  |
| ASRock              | 23       | 14.74%  |
| MSI                 | 18       | 11.54%  |
| Dell                | 14       | 8.97%   |
| Hewlett-Packard     | 10       | 6.41%   |
| Lenovo              | 3        | 1.92%   |
| Intel               | 3        | 1.92%   |
| Supermicro          | 2        | 1.28%   |
| Huanan              | 2        | 1.28%   |
| Foxconn             | 2        | 1.28%   |
| Shuttle             | 1        | 0.64%   |
| Protectli           | 1        | 0.64%   |
| HARDKERNEL          | 1        | 0.64%   |
| ECS                 | 1        | 0.64%   |
| Biostar             | 1        | 0.64%   |
| ASRockRack          | 1        | 0.64%   |
| Unknown             | 1        | 0.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 4        | 2.56%   |
| Gigabyte B550I AORUS PRO AX       | 3        | 1.92%   |
| ASRock B450M Pro4                 | 3        | 1.92%   |
| HP Z620 Workstation               | 2        | 1.28%   |
| Gigabyte Z77-D3H                  | 2        | 1.28%   |
| Gigabyte Z370 AORUS Gaming 5      | 2        | 1.28%   |
| Dell OptiPlex 760                 | 2        | 1.28%   |
| ASUS PRIME B550-PLUS              | 2        | 1.28%   |
| ASUS PRIME B450M-A                | 2        | 1.28%   |
| Supermicro SYS-5038MA-H24TRF      | 1        | 0.64%   |
| Supermicro SYS-5019S-MR           | 1        | 0.64%   |
| Shuttle SX79R                     | 1        | 0.64%   |
| Protectli FW6                     | 1        | 0.64%   |
| MSI MS-7C94                       | 1        | 0.64%   |
| MSI MS-7C84                       | 1        | 0.64%   |
| MSI MS-7C75                       | 1        | 0.64%   |
| MSI MS-7C56                       | 1        | 0.64%   |
| MSI MS-7C35                       | 1        | 0.64%   |
| MSI MS-7B89                       | 1        | 0.64%   |
| MSI MS-7B46                       | 1        | 0.64%   |
| MSI MS-7B09                       | 1        | 0.64%   |
| MSI MS-7A70                       | 1        | 0.64%   |
| MSI MS-7A40                       | 1        | 0.64%   |
| MSI MS-7A38                       | 1        | 0.64%   |
| MSI MS-7995                       | 1        | 0.64%   |
| MSI MS-7823                       | 1        | 0.64%   |
| MSI MS-7759                       | 1        | 0.64%   |
| MSI MS-7721                       | 1        | 0.64%   |
| MSI MS-7641                       | 1        | 0.64%   |
| MSI MS-7562                       | 1        | 0.64%   |
| MSI MS-6712                       | 1        | 0.64%   |
| Lenovo ThinkCentre M92p 3209EK4   | 1        | 0.64%   |
| Lenovo ThinkCentre M73 10B00005US | 1        | 0.64%   |
| Lenovo ThinkCentre M55p 8808D8U   | 1        | 0.64%   |
| Intel DP55WG AAE57269-407         | 1        | 0.64%   |
| Intel DP55WB AAE64798-206         | 1        | 0.64%   |
| Intel DN2820FYK H24582-201        | 1        | 0.64%   |
| Huanan X99-F8                     | 1        | 0.64%   |
| Huanan X99-8M-F V1.1              | 1        | 0.64%   |
| HP Z840 Workstation               | 1        | 0.64%   |
| HP t620 Dual Core TC              | 1        | 0.64%   |
| HP ProLiant MicroServer Gen8      | 1        | 0.64%   |
| HP ProLiant MicroServer           | 1        | 0.64%   |
| HP EliteDesk 705 G1 SFF           | 1        | 0.64%   |
| HP Compaq 8200 Elite SFF PC       | 1        | 0.64%   |
| HP Compaq 6005 Pro MT PC          | 1        | 0.64%   |
| HP 200-010hk                      | 1        | 0.64%   |
| HARDKERNEL ODROID-H2              | 1        | 0.64%   |
| Gigabyte Z97X-UD3H                | 1        | 0.64%   |
| Gigabyte Z170X-GamingG1           | 1        | 0.64%   |
| Gigabyte Z170M-D3H                | 1        | 0.64%   |
| Gigabyte X570 I AORUS PRO WIFI    | 1        | 0.64%   |
| Gigabyte X399 AORUS XTREME        | 1        | 0.64%   |
| Gigabyte P35C-DS3R                | 1        | 0.64%   |
| Gigabyte H87-HD3                  | 1        | 0.64%   |
| Gigabyte H81M-S2H GSM             | 1        | 0.64%   |
| Gigabyte H61MS                    | 1        | 0.64%   |
| Gigabyte H110N                    | 1        | 0.64%   |
| Gigabyte H110M-S2H                | 1        | 0.64%   |
| Gigabyte GA-990FX-GAMING          | 1        | 0.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS PRIME                   | 15       | 9.62%   |
| Dell OptiPlex                | 9        | 5.77%   |
| ASUS ROG                     | 5        | 3.21%   |
| Dell Precision               | 4        | 2.56%   |
| ASUS All                     | 4        | 2.56%   |
| Lenovo ThinkCentre           | 3        | 1.92%   |
| Gigabyte B550I               | 3        | 1.92%   |
| ASRock B450M                 | 3        | 1.92%   |
| HP Z620                      | 2        | 1.28%   |
| HP ProLiant                  | 2        | 1.28%   |
| HP Compaq                    | 2        | 1.28%   |
| Gigabyte Z77-D3H             | 2        | 1.28%   |
| Gigabyte Z370                | 2        | 1.28%   |
| ASRock Z97                   | 2        | 1.28%   |
| Supermicro SYS-5038MA-H24TRF | 1        | 0.64%   |
| Supermicro SYS-5019S-MR      | 1        | 0.64%   |
| Shuttle SX79R                | 1        | 0.64%   |
| Protectli FW6                | 1        | 0.64%   |
| MSI MS-7C94                  | 1        | 0.64%   |
| MSI MS-7C84                  | 1        | 0.64%   |
| MSI MS-7C75                  | 1        | 0.64%   |
| MSI MS-7C56                  | 1        | 0.64%   |
| MSI MS-7C35                  | 1        | 0.64%   |
| MSI MS-7B89                  | 1        | 0.64%   |
| MSI MS-7B46                  | 1        | 0.64%   |
| MSI MS-7B09                  | 1        | 0.64%   |
| MSI MS-7A70                  | 1        | 0.64%   |
| MSI MS-7A40                  | 1        | 0.64%   |
| MSI MS-7A38                  | 1        | 0.64%   |
| MSI MS-7995                  | 1        | 0.64%   |
| MSI MS-7823                  | 1        | 0.64%   |
| MSI MS-7759                  | 1        | 0.64%   |
| MSI MS-7721                  | 1        | 0.64%   |
| MSI MS-7641                  | 1        | 0.64%   |
| MSI MS-7562                  | 1        | 0.64%   |
| MSI MS-6712                  | 1        | 0.64%   |
| Intel DP55WG                 | 1        | 0.64%   |
| Intel DP55WB                 | 1        | 0.64%   |
| Intel DN2820FYK              | 1        | 0.64%   |
| Huanan X99-F8                | 1        | 0.64%   |
| Huanan X99-8M-F              | 1        | 0.64%   |
| HP Z840                      | 1        | 0.64%   |
| HP t620                      | 1        | 0.64%   |
| HP EliteDesk                 | 1        | 0.64%   |
| HP 200-010hk                 | 1        | 0.64%   |
| HARDKERNEL ODROID-H2         | 1        | 0.64%   |
| Gigabyte Z97X-UD3H           | 1        | 0.64%   |
| Gigabyte Z170X-GamingG1      | 1        | 0.64%   |
| Gigabyte Z170M-D3H           | 1        | 0.64%   |
| Gigabyte X570                | 1        | 0.64%   |
| Gigabyte X399                | 1        | 0.64%   |
| Gigabyte P35C-DS3R           | 1        | 0.64%   |
| Gigabyte H87-HD3             | 1        | 0.64%   |
| Gigabyte H81M-S2H            | 1        | 0.64%   |
| Gigabyte H61MS               | 1        | 0.64%   |
| Gigabyte H110N               | 1        | 0.64%   |
| Gigabyte H110M-S2H           | 1        | 0.64%   |
| Gigabyte GA-990FX-GAMING     | 1        | 0.64%   |
| Gigabyte GA-78LMT-USB3       | 1        | 0.64%   |
| Gigabyte EG41MF-US2H         | 1        | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 30       | 19.23%  |
| 2019 | 21       | 13.46%  |
| 2018 | 19       | 12.18%  |
| 2021 | 15       | 9.62%   |
| 2016 | 12       | 7.69%   |
| 2014 | 11       | 7.05%   |
| 2012 | 10       | 6.41%   |
| 2015 | 8        | 5.13%   |
| 2010 | 8        | 5.13%   |
| 2013 | 6        | 3.85%   |
| 2009 | 5        | 3.21%   |
| 2011 | 3        | 1.92%   |
| 2017 | 2        | 1.28%   |
| 2007 | 2        | 1.28%   |
| 2006 | 2        | 1.28%   |
| 2008 | 1        | 0.64%   |
| 2001 | 1        | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 156      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 153      | 98.08%  |
| Enabled  | 3        | 1.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 155      | 99.36%  |
| Yes  | 1        | 0.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 49       | 31.41%  |
| 8.01-16.0       | 28       | 17.95%  |
| 32.01-64.0      | 27       | 17.31%  |
| 64.01-256.0     | 18       | 11.54%  |
| 4.01-8.0        | 16       | 10.26%  |
| 3.01-4.0        | 9        | 5.77%   |
| 1.01-2.0        | 4        | 2.56%   |
| 2.01-3.0        | 2        | 1.28%   |
| More than 256.0 | 1        | 0.64%   |
| 24.01-32.0      | 1        | 0.64%   |
| 0.51-1.0        | 1        | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 29       | 18.47%  |
| 4.01-8.0   | 28       | 17.83%  |
| 1.01-2.0   | 27       | 17.2%   |
| 2.01-3.0   | 24       | 15.29%  |
| 0.51-1.0   | 15       | 9.55%   |
| 8.01-16.0  | 14       | 8.92%   |
| 0.01-0.5   | 10       | 6.37%   |
| 24.01-32.0 | 4        | 2.55%   |
| 16.01-24.0 | 4        | 2.55%   |
| 32.01-64.0 | 2        | 1.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 31.41%  |
| 2      | 44       | 28.21%  |
| 3      | 28       | 17.95%  |
| 4      | 14       | 8.97%   |
| 5      | 11       | 7.05%   |
| 9      | 3        | 1.92%   |
| 8      | 3        | 1.92%   |
| 6      | 3        | 1.92%   |
| 10     | 1        | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 53.85%  |
| Yes       | 72       | 46.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 155      | 99.36%  |
| No        | 1        | 0.64%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 109      | 69.87%  |
| Yes       | 47       | 30.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 118      | 75.64%  |
| Yes       | 38       | 24.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 40       | 25.64%  |
| Russia                 | 16       | 10.26%  |
| France                 | 13       | 8.33%   |
| Germany                | 12       | 7.69%   |
| UK                     | 10       | 6.41%   |
| Ukraine                | 7        | 4.49%   |
| Spain                  | 5        | 3.21%   |
| Poland                 | 5        | 3.21%   |
| Mexico                 | 3        | 1.92%   |
| Canada                 | 3        | 1.92%   |
| Bulgaria               | 3        | 1.92%   |
| Brazil                 | 3        | 1.92%   |
| Australia              | 3        | 1.92%   |
| Argentina              | 3        | 1.92%   |
| Venezuela              | 2        | 1.28%   |
| Sweden                 | 2        | 1.28%   |
| Norway                 | 2        | 1.28%   |
| Netherlands            | 2        | 1.28%   |
| Italy                  | 2        | 1.28%   |
| Hungary                | 2        | 1.28%   |
| Finland                | 2        | 1.28%   |
| Czechia                | 2        | 1.28%   |
| Belgium                | 2        | 1.28%   |
| Syria                  | 1        | 0.64%   |
| Singapore              | 1        | 0.64%   |
| Serbia                 | 1        | 0.64%   |
| New Caledonia          | 1        | 0.64%   |
| Madagascar             | 1        | 0.64%   |
| India                  | 1        | 0.64%   |
| Hong Kong              | 1        | 0.64%   |
| Greece                 | 1        | 0.64%   |
| Ecuador                | 1        | 0.64%   |
| Croatia                | 1        | 0.64%   |
| Bosnia and Herzegovina | 1        | 0.64%   |
| Austria                | 1        | 0.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Ocala                       | 5        | 3.21%   |
| Lyon                        | 5        | 3.21%   |
| Portland                    | 4        | 2.56%   |
| Sofia                       | 3        | 1.92%   |
| Kalamazoo                   | 3        | 1.92%   |
| Ensenada                    | 3        | 1.92%   |
| Warsaw                      | 2        | 1.28%   |
| Saint-Denis                 | 2        | 1.28%   |
| Perm                        | 2        | 1.28%   |
| New York                    | 2        | 1.28%   |
| Moscow                      | 2        | 1.28%   |
| Las Vegas                   | 2        | 1.28%   |
| Kyiv                        | 2        | 1.28%   |
| Kharkiv                     | 2        | 1.28%   |
| Clitheroe                   | 2        | 1.28%   |
| Athens                      | 2        | 1.28%   |
| Érd                        | 1        | 0.64%   |
| Zagreb                      | 1        | 0.64%   |
| Yekaterinburg               | 1        | 0.64%   |
| Woolloongabba               | 1        | 0.64%   |
| Woodstock                   | 1        | 0.64%   |
| Wenatchee                   | 1        | 0.64%   |
| Waregem                     | 1        | 0.64%   |
| Voerde                      | 1        | 0.64%   |
| Vladimir                    | 1        | 0.64%   |
| Vienna                      | 1        | 0.64%   |
| Vancouver                   | 1        | 0.64%   |
| Valera                      | 1        | 0.64%   |
| Vaasa                       | 1        | 0.64%   |
| Ulyanovsk                   | 1        | 0.64%   |
| Ufa                         | 1        | 0.64%   |
| Turku                       | 1        | 0.64%   |
| Toulouse                    | 1        | 0.64%   |
| Thionville                  | 1        | 0.64%   |
| Tai Kok Tsui                | 1        | 0.64%   |
| Stroud                      | 1        | 0.64%   |
| Strasbourg                  | 1        | 0.64%   |
| Stockholm                   | 1        | 0.64%   |
| Stockelsdorf                | 1        | 0.64%   |
| Stavanger                   | 1        | 0.64%   |
| Springfield                 | 1        | 0.64%   |
| Sosnowiec                   | 1        | 0.64%   |
| Singapore                   | 1        | 0.64%   |
| Saratov                     | 1        | 0.64%   |
| Sarajevo                    | 1        | 0.64%   |
| San Francisco               | 1        | 0.64%   |
| San Cristóbal de La Laguna | 1        | 0.64%   |
| Rochester                   | 1        | 0.64%   |
| Ribeirao Pires              | 1        | 0.64%   |
| Prague                      | 1        | 0.64%   |
| Phoenix                     | 1        | 0.64%   |
| Pforzheim                   | 1        | 0.64%   |
| Perth                       | 1        | 0.64%   |
| Paris                       | 1        | 0.64%   |
| Ostrava                     | 1        | 0.64%   |
| Orlando                     | 1        | 0.64%   |
| Omsk                        | 1        | 0.64%   |
| Oleksandrivka               | 1        | 0.64%   |
| Oldham                      | 1        | 0.64%   |
| Noumea                      | 1        | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 60       | 98     | 21.28%  |
| Seagate             | 58       | 92     | 20.57%  |
| Samsung Electronics | 38       | 57     | 13.48%  |
| Toshiba             | 19       | 34     | 6.74%   |
| Crucial             | 18       | 21     | 6.38%   |
| Kingston            | 17       | 21     | 6.03%   |
| Sandisk             | 11       | 14     | 3.9%    |
| Intel               | 9        | 16     | 3.19%   |
| Hitachi             | 9        | 10     | 3.19%   |
| HGST                | 5        | 7      | 1.77%   |
| A-DATA Technology   | 5        | 7      | 1.77%   |
| SPCC                | 4        | 4      | 1.42%   |
| PNY                 | 4        | 4      | 1.42%   |
| Gigabyte Technology | 3        | 3      | 1.06%   |
| Unknown             | 2        | 2      | 0.71%   |
| SABRENT             | 2        | 2      | 0.71%   |
| Phison Electronics  | 2        | 2      | 0.71%   |
| Phison              | 2        | 2      | 0.71%   |
| Corsair             | 2        | 2      | 0.71%   |
| Transcend           | 1        | 2      | 0.35%   |
| Team                | 1        | 1      | 0.35%   |
| T-FORCE             | 1        | 1      | 0.35%   |
| SK Hynix            | 1        | 2      | 0.35%   |
| Patriot             | 1        | 1      | 0.35%   |
| OCZ                 | 1        | 1      | 0.35%   |
| MaxDigital          | 1        | 2      | 0.35%   |
| Lexar               | 1        | 1      | 0.35%   |
| KingDian            | 1        | 1      | 0.35%   |
| Intenso             | 1        | 2      | 0.35%   |
| DOGFISH             | 1        | 1      | 0.35%   |
| China               | 1        | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB           | 8        | 2.32%   |
| Toshiba HDWD110 1TB               | 4        | 1.16%   |
| Toshiba DT01ACA300 3TB            | 4        | 1.16%   |
| Toshiba DT01ACA200 2TB            | 4        | 1.16%   |
| Seagate ST500DM002-1BD142 500GB   | 4        | 1.16%   |
| Seagate ST4000DM004-2CV104 4TB    | 4        | 1.16%   |
| Seagate ST1000DM010-2EP102 1TB    | 4        | 1.16%   |
| Samsung SSD 970 EVO Plus 500GB    | 4        | 1.16%   |
| Samsung SSD 970 EVO Plus 1TB      | 4        | 1.16%   |
| Kingston SA400S37120G 120GB SSD   | 4        | 1.16%   |
| WDC WDS500G3X0C-00SJG0 500GB      | 3        | 0.87%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 3        | 0.87%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 3        | 0.87%   |
| Seagate ST2000DM001-1ER164 2TB    | 3        | 0.87%   |
| Samsung SSD 850 EVO 500GB         | 3        | 0.87%   |
| Samsung SSD 850 EVO 250GB         | 3        | 0.87%   |
| Kingston SV300S37A240G 240GB SSD  | 3        | 0.87%   |
| Hitachi HUS724040ALE641 4TB       | 3        | 0.87%   |
| Crucial CT500P1SSD8 500GB         | 3        | 0.87%   |
| WDC WDS500G2B0C-00PXH0 500GB      | 2        | 0.58%   |
| WDC WD40EFRX-68N32N0 4TB          | 2        | 0.58%   |
| WDC WD20EZAZ-00GGJB0 2TB          | 2        | 0.58%   |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 0.58%   |
| WDC WD20EARX-00PASB0 2TB          | 2        | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB          | 2        | 0.58%   |
| WDC WD10EZEX-00BN5A0 1TB          | 2        | 0.58%   |
| WDC WD10EFRX-68FYTN0 1TB          | 2        | 0.58%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 2        | 0.58%   |
| Seagate ST3160815AS 160GB         | 2        | 0.58%   |
| Seagate ST3000DM001-1CH166 3TB    | 2        | 0.58%   |
| Seagate ST2000DM008-2FR102 2TB    | 2        | 0.58%   |
| Seagate ST2000DM006-2DM164 2TB    | 2        | 0.58%   |
| Seagate ST1000DM003-1CH162 1TB    | 2        | 0.58%   |
| Seagate BUP Slim BL 2TB           | 2        | 0.58%   |
| Seagate Backup+ Hub BK 4TB        | 2        | 0.58%   |
| SanDisk SD8SBAT128G1122 128GB SSD | 2        | 0.58%   |
| Sandisk NVMe SSD Drive 1TB        | 2        | 0.58%   |
| Samsung SSD 970 EVO 500GB         | 2        | 0.58%   |
| Samsung SSD 860 EVO 500GB         | 2        | 0.58%   |
| Samsung SSD 860 EVO 2TB           | 2        | 0.58%   |
| Samsung SSD 860 EVO 250GB         | 2        | 0.58%   |
| Samsung SSD 840 PRO Series 256GB  | 2        | 0.58%   |
| Samsung HD103SJ 1TB               | 2        | 0.58%   |
| SABRENT Disk 160GB                | 2        | 0.58%   |
| Phison PCIe SSD 512GB             | 2        | 0.58%   |
| Kingston SV300S37A120G 120GB SSD  | 2        | 0.58%   |
| Kingston SUV500240G 240GB SSD     | 2        | 0.58%   |
| Kingston SA400S37240G 240GB SSD   | 2        | 0.58%   |
| Intel SSDPEKNW010T9 1TB           | 2        | 0.58%   |
| Intel NVMe SSD Drive 1024GB       | 2        | 0.58%   |
| Intel MEMPEK1J016GAL 16GB         | 2        | 0.58%   |
| Crucial CT500P2SSD8 500GB         | 2        | 0.58%   |
| Crucial CT500MX500SSD1 500GB      | 2        | 0.58%   |
| Crucial CT1000P1SSD8 1TB          | 2        | 0.58%   |
| WDC WUH721414ALE6L4 14TB          | 1        | 0.29%   |
| WDC WDS500G2B0B-00YS70 500GB SSD  | 1        | 0.29%   |
| WDC WDS500G1B0C-00S6U0 500GB      | 1        | 0.29%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD  | 1        | 0.29%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 55       | 79     | 39.29%  |
| WDC                 | 47       | 77     | 33.57%  |
| Toshiba             | 17       | 31     | 12.14%  |
| Hitachi             | 9        | 10     | 6.43%   |
| Samsung Electronics | 6        | 7      | 4.29%   |
| HGST                | 5        | 7      | 3.57%   |
| MaxDigital          | 1        | 2      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 31     | 23.96%  |
| Kingston            | 16       | 20     | 16.67%  |
| Crucial             | 12       | 13     | 12.5%   |
| WDC                 | 10       | 11     | 10.42%  |
| SanDisk             | 8        | 10     | 8.33%   |
| A-DATA Technology   | 5        | 6      | 5.21%   |
| SPCC                | 3        | 3      | 3.13%   |
| PNY                 | 3        | 3      | 3.13%   |
| Toshiba             | 2        | 3      | 2.08%   |
| SABRENT             | 2        | 2      | 2.08%   |
| Unknown             | 1        | 1      | 1.04%   |
| Transcend           | 1        | 2      | 1.04%   |
| Team                | 1        | 1      | 1.04%   |
| T-FORCE             | 1        | 1      | 1.04%   |
| Seagate             | 1        | 1      | 1.04%   |
| Patriot             | 1        | 1      | 1.04%   |
| OCZ                 | 1        | 1      | 1.04%   |
| Lexar               | 1        | 1      | 1.04%   |
| KingDian            | 1        | 1      | 1.04%   |
| Gigabyte Technology | 1        | 1      | 1.04%   |
| DOGFISH             | 1        | 1      | 1.04%   |
| China               | 1        | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 111      | 213    | 42.37%  |
| SSD     | 91       | 115    | 34.73%  |
| NVMe    | 53       | 71     | 20.23%  |
| Unknown | 6        | 14     | 2.29%   |
| MMC     | 1        | 1      | 0.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 142      | 321    | 67.94%  |
| NVMe | 53       | 71     | 25.36%  |
| SAS  | 13       | 21     | 6.22%   |
| MMC  | 1        | 1      | 0.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 97       | 138    | 44.29%  |
| 0.51-1.0   | 57       | 78     | 26.03%  |
| 1.01-2.0   | 34       | 42     | 15.53%  |
| 3.01-4.0   | 13       | 35     | 5.94%   |
| 2.01-3.0   | 9        | 14     | 4.11%   |
| 4.01-10.0  | 7        | 18     | 3.2%    |
| 10.01-20.0 | 2        | 3      | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 30       | 19.23%  |
| 251-500        | 25       | 16.03%  |
| 101-250        | 21       | 13.46%  |
| 1001-2000      | 20       | 12.82%  |
| 501-1000       | 19       | 12.18%  |
| 1-20           | 14       | 8.97%   |
| 2001-3000      | 10       | 6.41%   |
| 51-100         | 7        | 4.49%   |
| Unknown        | 7        | 4.49%   |
| 21-50          | 3        | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 38       | 24.2%   |
| 101-250        | 18       | 11.46%  |
| 251-500        | 16       | 10.19%  |
| 21-50          | 16       | 10.19%  |
| 501-1000       | 16       | 10.19%  |
| More than 3000 | 13       | 8.28%   |
| 1001-2000      | 13       | 8.28%   |
| 51-100         | 12       | 7.64%   |
| 2001-3000      | 7        | 4.46%   |
| Unknown        | 7        | 4.46%   |
| 0              | 1        | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 4.44%   |
| WDC WD5003ABYX-18WERA0 500GB          | 1        | 2      | 2.22%   |
| WDC WD5000AAKX-00U6AA0 500GB          | 1        | 1      | 2.22%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 2.22%   |
| WDC WD5000AAKS-22V1A0 500GB           | 1        | 1      | 2.22%   |
| WDC WD5000AAJS-22A8B0 500GB           | 1        | 1      | 2.22%   |
| WDC WD40EFZX-68AWUN0 4TB              | 1        | 6      | 2.22%   |
| WDC WD400BB-00DEA0 40GB               | 1        | 1      | 2.22%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 2.22%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 2.22%   |
| WDC WD20EARS-00MVWB0 2TB              | 1        | 1      | 2.22%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1        | 1      | 2.22%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1        | 1      | 2.22%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 2.22%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 2.22%   |
| WDC WD1001FALS-75J7B0 1TB             | 1        | 1      | 2.22%   |
| Toshiba MK2565GSX 250GB               | 1        | 1      | 2.22%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 2.22%   |
| SK Hynix PC401 NVMe 512GB             | 1        | 2      | 2.22%   |
| Seagate ST3320620A 320GB              | 1        | 1      | 2.22%   |
| Seagate ST3200827AS 200GB             | 1        | 1      | 2.22%   |
| Seagate ST32000542AS 2TB              | 1        | 1      | 2.22%   |
| Seagate ST3160813AS 160GB             | 1        | 1      | 2.22%   |
| Seagate ST31500341AS 1TB              | 1        | 1      | 2.22%   |
| Seagate ST3120827AS 120GB             | 1        | 1      | 2.22%   |
| Seagate ST31000333AS 1TB              | 1        | 1      | 2.22%   |
| Seagate ST3000DM001-9YN166 320GB      | 1        | 1      | 2.22%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 2.22%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 2.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 2.22%   |
| Seagate ST1000DM003-9YN162 1TB        | 1        | 1      | 2.22%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 2.22%   |
| SanDisk SSD PLUS 120 GB               | 1        | 1      | 2.22%   |
| Samsung Electronics SSD 970 EVO 250GB | 1        | 1      | 2.22%   |
| Samsung Electronics HD161GJ 160GB     | 1        | 1      | 2.22%   |
| PNY SSD2SC240G3LC709B121-460P 240GB   | 1        | 1      | 2.22%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 2.22%   |
| Kingston SE100S3100G 100GB SSD        | 1        | 1      | 2.22%   |
| KingDian S280 240GB SSD               | 1        | 1      | 2.22%   |
| Intel SSDPEKKW010T7 1TB               | 1        | 2      | 2.22%   |
| Hitachi HUA722020ALA331 2TB           | 1        | 1      | 2.22%   |
| Hitachi HDS722525VLAT80 250GB         | 1        | 1      | 2.22%   |
| A-DATA Technology SU800 256GB SSD     | 1        | 2      | 2.22%   |
| A-DATA Technology SSD DP900 128GB-DL3 | 1        | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 22     | 34.88%  |
| Seagate             | 13       | 15     | 30.23%  |
| Toshiba             | 2        | 2      | 4.65%   |
| Samsung Electronics | 2        | 2      | 4.65%   |
| Kingston            | 2        | 2      | 4.65%   |
| Hitachi             | 2        | 2      | 4.65%   |
| A-DATA Technology   | 2        | 3      | 4.65%   |
| SK Hynix            | 1        | 2      | 2.33%   |
| SanDisk             | 1        | 1      | 2.33%   |
| PNY                 | 1        | 1      | 2.33%   |
| KingDian            | 1        | 1      | 2.33%   |
| Intel               | 1        | 2      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 22     | 45.45%  |
| Seagate             | 13       | 15     | 39.39%  |
| Toshiba             | 2        | 2      | 6.06%   |
| Hitachi             | 2        | 2      | 6.06%   |
| Samsung Electronics | 1        | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 32       | 42     | 76.19%  |
| SSD  | 7        | 8      | 16.67%  |
| NVMe | 3        | 5      | 7.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM005 HD502HJ 500GB | 1        | 1      | 50%     |
| Seagate ST3500830AS 500GB        | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 136      | 304    | 68.34%  |
| Malfunc  | 39       | 55     | 19.6%   |
| Detected | 22       | 53     | 11.06%  |
| Failed   | 2        | 2      | 1.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 90       | 40%     |
| AMD                         | 66       | 29.33%  |
| Samsung Electronics         | 18       | 8%      |
| Sandisk                     | 10       | 4.44%   |
| Phison Electronics          | 9        | 4%      |
| Micron/Crucial Technology   | 7        | 3.11%   |
| ASMedia Technology          | 7        | 3.11%   |
| Marvell Technology Group    | 4        | 1.78%   |
| JMicron Technology          | 3        | 1.33%   |
| Nvidia                      | 2        | 0.89%   |
| Broadcom / LSI              | 2        | 0.89%   |
| VIA Technologies            | 1        | 0.44%   |
| SK Hynix                    | 1        | 0.44%   |
| Silicon Image               | 1        | 0.44%   |
| Seagate Technology          | 1        | 0.44%   |
| Kingston Technology Company | 1        | 0.44%   |
| ADATA Technology            | 1        | 0.44%   |
| Adaptec                     | 1        | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 41       | 13.95%  |
| AMD 400 Series Chipset SATA Controller                                                  | 16       | 5.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14       | 4.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12       | 4.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 3.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 3.06%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 9        | 3.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 3.06%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 3.06%   |
| Phison E12 NVMe Controller                                                              | 6        | 2.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 2.04%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 5        | 1.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 1.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 1.7%    |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.7%    |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4        | 1.36%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.36%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 1.36%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.36%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 1.02%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 1.02%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 1.02%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.02%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.02%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 1.02%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.68%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.68%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.68%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.68%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.68%   |
| Intel SSD 660P Series                                                                   | 2        | 0.68%   |
| Intel SSD 600P Series                                                                   | 2        | 0.68%   |
| Intel NVMe Optane Memory Series                                                         | 2        | 0.68%   |
| Intel Non-Volatile memory controller                                                    | 2        | 0.68%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.68%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.68%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.68%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 0.68%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.68%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.34%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                             | 1        | 0.34%   |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.34%   |
| Seagate FireCuda 510 SSD                                                                | 1        | 0.34%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 0.34%   |
| Sandisk WD Black SN850                                                                  | 1        | 0.34%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.34%   |
| Samsung NVMe Controller                                                                 | 1        | 0.34%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.34%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.34%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.34%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.34%   |
| Marvell Group 88NR2241 Non-Volatile memory controller                                   | 1        | 0.34%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.34%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 136      | 57.63%  |
| NVMe | 53       | 22.46%  |
| IDE  | 32       | 13.56%  |
| RAID | 10       | 4.24%   |
| SAS  | 5        | 2.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 88       | 56.41%  |
| AMD    | 68       | 43.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 9        | 5.77%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 4        | 2.56%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 3        | 1.92%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 1.92%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 3        | 1.92%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 3        | 1.92%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 3        | 1.92%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 3        | 1.92%   |
| AMD FX-8350 Eight-Core Processor       | 3        | 1.92%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz | 2        | 1.28%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 2        | 1.28%   |
| Intel Core i5-6600 CPU @ 3.30GHz       | 2        | 1.28%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 2        | 1.28%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 2        | 1.28%   |
| Intel Core i5-2500K CPU @ 3.30GHz      | 2        | 1.28%   |
| Intel Core i5 CPU 650 @ 3.20GHz        | 2        | 1.28%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz  | 2        | 1.28%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 2        | 1.28%   |
| AMD Ryzen 5 3600X 6-Core Processor     | 2        | 1.28%   |
| AMD Phenom II X4 965 Processor         | 2        | 1.28%   |
| Intel Xeon W-2145 CPU @ 3.70GHz        | 1        | 0.64%   |
| Intel Xeon CPU W3503 @ 2.40GHz         | 1        | 0.64%   |
| Intel Xeon CPU E5-2699 v4 @ 2.20GHz    | 1        | 0.64%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz    | 1        | 0.64%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz     | 1        | 0.64%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz    | 1        | 0.64%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz     | 1        | 0.64%   |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz    | 1        | 0.64%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz     | 1        | 0.64%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz     | 1        | 0.64%   |
| Intel Xeon CPU E3-1230 v6 @ 3.50GHz    | 1        | 0.64%   |
| Intel Pentium CPU N3700 @ 1.60GHz      | 1        | 0.64%   |
| Intel Pentium CPU G3250 @ 3.20GHz      | 1        | 0.64%   |
| Intel Pentium CPU G2030 @ 3.00GHz      | 1        | 0.64%   |
| Intel Pentium 4 CPU 2.80GHz            | 1        | 0.64%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 1        | 0.64%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 0.64%   |
| Intel Core i7-8086K CPU @ 4.00GHz      | 1        | 0.64%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 1        | 0.64%   |
| Intel Core i7-4820K CPU @ 3.70GHz      | 1        | 0.64%   |
| Intel Core i7-4790S CPU @ 3.20GHz      | 1        | 0.64%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 1        | 0.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 1        | 0.64%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 0.64%   |
| Intel Core i7-10710U CPU @ 1.10GHz     | 1        | 0.64%   |
| Intel Core i7-10700K CPU @ 3.80GHz     | 1        | 0.64%   |
| Intel Core i7-10700 CPU @ 2.90GHz      | 1        | 0.64%   |
| Intel Core i7 CPU 860 @ 2.80GHz        | 1        | 0.64%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 1        | 0.64%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 1        | 0.64%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 1        | 0.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 1        | 0.64%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 1        | 0.64%   |
| Intel Core i5-4690 CPU @ 3.50GHz       | 1        | 0.64%   |
| Intel Core i5-4590S CPU @ 3.00GHz      | 1        | 0.64%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1        | 0.64%   |
| Intel Core i5-4430 CPU @ 3.00GHz       | 1        | 0.64%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 1        | 0.64%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 1        | 0.64%   |
| Intel Core i5-3550 CPU @ 3.30GHz       | 1        | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 30       | 19.23%  |
| AMD Ryzen 5            | 19       | 12.18%  |
| Intel Core i7          | 17       | 10.9%   |
| AMD Ryzen 7            | 13       | 8.33%   |
| Intel Xeon             | 11       | 7.05%   |
| AMD FX                 | 7        | 4.49%   |
| Intel Celeron          | 6        | 3.85%   |
| Intel Core i3          | 5        | 3.21%   |
| Intel Core 2 Duo       | 5        | 3.21%   |
| AMD Ryzen Threadripper | 4        | 2.56%   |
| AMD Ryzen 9            | 4        | 2.56%   |
| AMD Phenom II X4       | 4        | 2.56%   |
| Intel Pentium          | 3        | 1.92%   |
| Intel Core 2 Quad      | 3        | 1.92%   |
| AMD Ryzen 3            | 3        | 1.92%   |
| Intel Pentium Gold     | 2        | 1.28%   |
| Intel Core 2           | 2        | 1.28%   |
| AMD Athlon X4          | 2        | 1.28%   |
| AMD A10                | 2        | 1.28%   |
| Other                  | 1        | 0.64%   |
| Intel Pentium 4        | 1        | 0.64%   |
| Intel Core i9          | 1        | 0.64%   |
| Intel Atom             | 1        | 0.64%   |
| AMD Sempron            | 1        | 0.64%   |
| AMD PRO A8             | 1        | 0.64%   |
| AMD Phenom II X3       | 1        | 0.64%   |
| AMD GX                 | 1        | 0.64%   |
| AMD Athlon XP          | 1        | 0.64%   |
| AMD Athlon II X2       | 1        | 0.64%   |
| AMD Athlon II Neo      | 1        | 0.64%   |
| AMD Athlon Dual Core   | 1        | 0.64%   |
| AMD A8                 | 1        | 0.64%   |
| AMD A6                 | 1        | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 57       | 36.54%  |
| 2      | 33       | 21.15%  |
| 6      | 28       | 17.95%  |
| 8      | 20       | 12.82%  |
| 12     | 5        | 3.21%   |
| 1      | 5        | 3.21%   |
| 16     | 4        | 2.56%   |
| 44     | 1        | 0.64%   |
| 32     | 1        | 0.64%   |
| 28     | 1        | 0.64%   |
| 3      | 1        | 0.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 153      | 98.08%  |
| 2      | 3        | 1.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 90       | 57.69%  |
| 1      | 66       | 42.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 154      | 98.72%  |
| 32-bit         | 2        | 1.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 17.2%   |
| 0x08701021 | 14       | 8.92%   |
| 0x306c3    | 13       | 8.28%   |
| 0x306a9    | 7        | 4.46%   |
| 0x06003106 | 6        | 3.82%   |
| 0x906e9    | 5        | 3.18%   |
| 0x506e3    | 5        | 3.18%   |
| 0x206a7    | 5        | 3.18%   |
| 0x906ea    | 4        | 2.55%   |
| 0x206d7    | 4        | 2.55%   |
| 0x0a201009 | 4        | 2.55%   |
| 0x0800820d | 4        | 2.55%   |
| 0x306f2    | 3        | 1.91%   |
| 0x1067a    | 3        | 1.91%   |
| 0x08001138 | 3        | 1.91%   |
| 0x06000852 | 3        | 1.91%   |
| 0x010000c8 | 3        | 1.91%   |
| 0x010000b6 | 3        | 1.91%   |
| 0xa0655    | 2        | 1.27%   |
| 0x6fb      | 2        | 1.27%   |
| 0x0a201016 | 2        | 1.27%   |
| 0x08701013 | 2        | 1.27%   |
| 0xf41      | 1        | 0.64%   |
| 0xf29      | 1        | 0.64%   |
| 0xa0671    | 1        | 0.64%   |
| 0xa0660    | 1        | 0.64%   |
| 0xa0653    | 1        | 0.64%   |
| 0x906ed    | 1        | 0.64%   |
| 0x906ec    | 1        | 0.64%   |
| 0x906eb    | 1        | 0.64%   |
| 0x806e9    | 1        | 0.64%   |
| 0x706a1    | 1        | 0.64%   |
| 0x6fd      | 1        | 0.64%   |
| 0x6f6      | 1        | 0.64%   |
| 0x6f2      | 1        | 0.64%   |
| 0x50654    | 1        | 0.64%   |
| 0x406f1    | 1        | 0.64%   |
| 0x406d8    | 1        | 0.64%   |
| 0x406c3    | 1        | 0.64%   |
| 0x40651    | 1        | 0.64%   |
| 0x306e4    | 1        | 0.64%   |
| 0x30678    | 1        | 0.64%   |
| 0x30673    | 1        | 0.64%   |
| 0x20655    | 1        | 0.64%   |
| 0x106e5    | 1        | 0.64%   |
| 0x106a5    | 1        | 0.64%   |
| 0x0830104d | 1        | 0.64%   |
| 0x08108109 | 1        | 0.64%   |
| 0x0800820b | 1        | 0.64%   |
| 0x08001137 | 1        | 0.64%   |
| 0x0700010f | 1        | 0.64%   |
| 0x0600081c | 1        | 0.64%   |
| 0x0600063e | 1        | 0.64%   |
| 0x0600063d | 1        | 0.64%   |
| 0x010000db | 1        | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 22       | 14.1%   |
| Haswell       | 18       | 11.54%  |
| KabyLake      | 16       | 10.26%  |
| IvyBridge     | 10       | 6.41%   |
| Zen+          | 9        | 5.77%   |
| SandyBridge   | 9        | 5.77%   |
| Skylake       | 8        | 5.13%   |
| K10           | 8        | 5.13%   |
| Zen 3         | 7        | 4.49%   |
| Steamroller   | 7        | 4.49%   |
| Core          | 6        | 3.85%   |
| Zen           | 5        | 3.21%   |
| Piledriver    | 5        | 3.21%   |
| Silvermont    | 4        | 2.56%   |
| Penryn        | 4        | 2.56%   |
| CometLake     | 4        | 2.56%   |
| Westmere      | 2        | 1.28%   |
| NetBurst      | 2        | 1.28%   |
| Nehalem       | 2        | 1.28%   |
| Bulldozer     | 2        | 1.28%   |
| K8 Hammer     | 1        | 0.64%   |
| K6            | 1        | 0.64%   |
| Jaguar        | 1        | 0.64%   |
| Goldmont plus | 1        | 0.64%   |
| Broadwell     | 1        | 0.64%   |
| Unknown       | 1        | 0.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 64       | 39.75%  |
| AMD                        | 52       | 32.3%   |
| Intel                      | 39       | 24.22%  |
| ASPEED Technology          | 5        | 3.11%   |
| Matrox Electronics Systems | 1        | 0.62%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 14       | 8.64%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 4.32%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 3.7%    |
| ASPEED Technology ASPEED Graphics Family                                    | 5        | 3.09%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 3.09%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 3.09%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 2.47%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 2.47%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 2.47%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 2.47%   |
| Intel HD Graphics 530                                                       | 3        | 1.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.85%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.23%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.23%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.23%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.23%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 2        | 1.23%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 2        | 1.23%   |
| Nvidia G98 [Quadro NVS 295]                                                 | 2        | 1.23%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 2        | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 1.23%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.23%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 1.23%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 1.23%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.23%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.23%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.62%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.62%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.62%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.62%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.62%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.62%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.62%   |
| Nvidia GV100GL [Quadro GV100]                                               | 1        | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.62%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.62%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.62%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.62%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 0.62%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 0.62%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.62%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.62%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 0.62%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 0.62%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.62%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 0.62%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 0.62%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                       | 1        | 0.62%   |
| Nvidia GF110 [GeForce GTX 560 Ti 448 Cores]                                 | 1        | 0.62%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.62%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 0.62%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.62%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 0.62%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.62%   |
| Nvidia G92 [GeForce GTS 250]                                                | 1        | 0.62%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 0.62%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 1        | 0.62%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 61       | 39.1%   |
| 1 x AMD        | 49       | 31.41%  |
| 1 x Intel      | 36       | 23.08%  |
| 1 x ASPEED     | 4        | 2.56%   |
| Intel + Nvidia | 2        | 1.28%   |
| 2 x AMD        | 1        | 0.64%   |
| 1 x Matrox     | 1        | 0.64%   |
| AMD + Nvidia   | 1        | 0.64%   |
| AMD + ASPEED   | 1        | 0.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 111      | 71.15%  |
| Proprietary | 41       | 26.28%  |
| Unknown     | 4        | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 63       | 40.13%  |
| 7.01-8.0   | 21       | 13.38%  |
| 1.01-2.0   | 20       | 12.74%  |
| 3.01-4.0   | 15       | 9.55%   |
| 0.51-1.0   | 13       | 8.28%   |
| 0.01-0.5   | 13       | 8.28%   |
| 5.01-6.0   | 6        | 3.82%   |
| 2.01-3.0   | 2        | 1.27%   |
| 8.01-16.0  | 2        | 1.27%   |
| 24.01-32.0 | 1        | 0.64%   |
| 16.01-24.0 | 1        | 0.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 23       | 13.45%  |
| Dell                 | 23       | 13.45%  |
| Samsung Electronics  | 22       | 12.87%  |
| Acer                 | 17       | 9.94%   |
| Ancor Communications | 13       | 7.6%    |
| Hewlett-Packard      | 11       | 6.43%   |
| BenQ                 | 10       | 5.85%   |
| AOC                  | 8        | 4.68%   |
| Philips              | 7        | 4.09%   |
| ASUSTek Computer     | 4        | 2.34%   |
| ViewSonic            | 3        | 1.75%   |
| NEC Computers        | 3        | 1.75%   |
| Unknown              | 2        | 1.17%   |
| Sony                 | 2        | 1.17%   |
| LG Electronics       | 2        | 1.17%   |
| Lenovo               | 2        | 1.17%   |
| Iiyama               | 2        | 1.17%   |
| Eizo                 | 2        | 1.17%   |
| Vizio                | 1        | 0.58%   |
| Vestel Elektronik    | 1        | 0.58%   |
| Prestigio            | 1        | 0.58%   |
| ODH                  | 1        | 0.58%   |
| MIT                  | 1        | 0.58%   |
| Mi                   | 1        | 0.58%   |
| Medion               | 1        | 0.58%   |
| JVC                  | 1        | 0.58%   |
| INFOTRONIC           | 1        | 0.58%   |
| Idek Iiyama          | 1        | 0.58%   |
| HKC                  | 1        | 0.58%   |
| Hitachi              | 1        | 0.58%   |
| HannStar Display     | 1        | 0.58%   |
| COBY                 | 1        | 0.58%   |
| Belinea              | 1        | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 3        | 1.66%   |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3        | 1.66%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 2        | 1.1%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2        | 1.1%    |
| Lenovo L2251x Wide LEN0A12 1680x1050 474x296mm 22.0-inch               | 2        | 1.1%    |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2        | 1.1%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 1.1%    |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 2        | 1.1%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2        | 1.1%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2        | 1.1%    |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2        | 1.1%    |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 2        | 1.1%    |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2        | 1.1%    |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                     | 1        | 0.55%   |
| ViewSonic VA926 Series VSC7D20 1280x1024 376x301mm 19.0-inch           | 1        | 0.55%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.55%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.55%   |
| Sony TV *00 SNY3F05 3840x2160 952x535mm 43.0-inch                      | 1        | 0.55%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.55%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch      | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch    | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch   | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 304x228mm 15.0-inch    | 1        | 0.55%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch     | 1        | 0.55%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch   | 1        | 0.55%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1        | 0.55%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch      | 1        | 0.55%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 0.55%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch       | 1        | 0.55%   |
| Samsung Electronics Monitor SAM1057 1280x1024 306x230mm 15.1-inch      | 1        | 0.55%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 0.55%   |
| Samsung Electronics LF27T850 SAM704F 2560x1440 597x336mm 27.0-inch     | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SyncMaster 5760x1080                   | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SMB2430L                               | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM0BC9 1920x1080 600x340mm 27.2-inch  | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 0.55%   |
| Samsung Electronics LCD Monitor C24F390 3360x1080                      | 1        | 0.55%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch     | 1        | 0.55%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1        | 0.55%   |
| Samsung Electronics C24FG70 SAM0D58 1920x1080 532x304mm 24.1-inch      | 1        | 0.55%   |
| Prestigio P151 ASB0503 1024x768 304x228mm 15.0-inch                    | 1        | 0.55%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1        | 0.55%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 0.55%   |
| Philips PHL 242E1GZ PHLC24C 1920x1080 527x296mm 23.8-inch              | 1        | 0.55%   |
| Philips PHL 241E1 PHLC207 1920x1080 530x300mm 24.0-inch                | 1        | 0.55%   |
| Philips LCD Monitor PHLC0B8 1920x1080 600x340mm 27.2-inch              | 1        | 0.55%   |
| Philips LCD Monitor PHL0850 1680x1050 470x300mm 22.0-inch              | 1        | 0.55%   |
| Philips 240S PHL087D 1920x1200 519x324mm 24.1-inch                     | 1        | 0.55%   |
| ODH LM24 ODH2492 1920x1080 345x259mm 17.0-inch                         | 1        | 0.55%   |
| NEC Computers LCD1550V NEC65C6 1024x768 304x228mm 15.0-inch            | 1        | 0.55%   |
| NEC Computers EA243WM NEC6865 1920x1200 519x324mm 24.1-inch            | 1        | 0.55%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch            | 1        | 0.55%   |
| MIT LCD Monitor MIT2015 3840x2160 520x330mm 24.2-inch                  | 1        | 0.55%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1        | 0.55%   |
| Medion MD41077EA MED078B 1280x1024 330x270mm 16.8-inch                 | 1        | 0.55%   |
| LG Electronics LCD Monitor LG IPS FULLHD                               | 1        | 0.55%   |
| LG Electronics LCD Monitor LG HDR QHD 4480x1440                        | 1        | 0.55%   |
| LG Electronics LCD Monitor 27GL850 2560x1440                           | 1        | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 67       | 40.12%  |
| 2560x1440 (QHD)    | 18       | 10.78%  |
| 3840x2160 (4K)     | 15       | 8.98%   |
| 1280x1024 (SXGA)   | 13       | 7.78%   |
| 1680x1050 (WSXGA+) | 10       | 5.99%   |
| 1920x1200 (WUXGA)  | 7        | 4.19%   |
| 1366x768 (WXGA)    | 6        | 3.59%   |
| 1600x900 (HD+)     | 5        | 2.99%   |
| 2560x1080          | 4        | 2.4%    |
| Unknown            | 4        | 2.4%    |
| 1440x900 (WXGA+)   | 3        | 1.8%    |
| 1024x768 (XGA)     | 3        | 1.8%    |
| 2560x1600          | 2        | 1.2%    |
| 2288x1287          | 2        | 1.2%    |
| 1600x1200          | 2        | 1.2%    |
| 7680x4320          | 1        | 0.6%    |
| 5760x1080          | 1        | 0.6%    |
| 4480x1440          | 1        | 0.6%    |
| 3440x1440          | 1        | 0.6%    |
| 3360x1080          | 1        | 0.6%    |
| 1920x540           | 1        | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 31       | 18.34%  |
| 27      | 28       | 16.57%  |
| 23      | 24       | 14.2%   |
| 21      | 13       | 7.69%   |
| Unknown | 13       | 7.69%   |
| 17      | 9        | 5.33%   |
| 31      | 8        | 4.73%   |
| 18      | 7        | 4.14%   |
| 22      | 5        | 2.96%   |
| 20      | 5        | 2.96%   |
| 19      | 5        | 2.96%   |
| 34      | 4        | 2.37%   |
| 15      | 4        | 2.37%   |
| 142     | 2        | 1.18%   |
| 29      | 2        | 1.18%   |
| 28      | 2        | 1.18%   |
| 84      | 1        | 0.59%   |
| 72      | 1        | 0.59%   |
| 55      | 1        | 0.59%   |
| 48      | 1        | 0.59%   |
| 38      | 1        | 0.59%   |
| 25      | 1        | 0.59%   |
| 16      | 1        | 0.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 73       | 45.06%  |
| 401-500        | 33       | 20.37%  |
| 601-700        | 15       | 9.26%   |
| 301-350        | 14       | 8.64%   |
| Unknown        | 13       | 8.02%   |
| 701-800        | 4        | 2.47%   |
| 351-400        | 3        | 1.85%   |
| More than 2000 | 2        | 1.23%   |
| 1501-2000      | 2        | 1.23%   |
| 1001-1500      | 2        | 1.23%   |
| 801-900        | 1        | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 100      | 62.5%   |
| 16/10   | 19       | 11.88%  |
| Unknown | 12       | 7.5%    |
| 5/4     | 11       | 6.88%   |
| 4/3     | 7        | 4.38%   |
| 21/9    | 5        | 3.13%   |
| 3/2     | 2        | 1.25%   |
| 1.00    | 2        | 1.25%   |
| 6/5     | 1        | 0.63%   |
| 1.96    | 1        | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 56       | 34.15%  |
| 301-350        | 28       | 17.07%  |
| 351-500        | 15       | 9.15%   |
| 151-200        | 14       | 8.54%   |
| 141-150        | 13       | 7.93%   |
| Unknown        | 13       | 7.93%   |
| 251-300        | 12       | 7.32%   |
| More than 1000 | 5        | 3.05%   |
| 101-110        | 4        | 2.44%   |
| 131-140        | 2        | 1.22%   |
| 501-1000       | 2        | 1.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 97       | 62.18%  |
| 101-120 | 25       | 16.03%  |
| Unknown | 13       | 8.33%   |
| 121-160 | 9        | 5.77%   |
| 161-240 | 7        | 4.49%   |
| 1-50    | 5        | 3.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 110      | 70.51%  |
| 2     | 30       | 19.23%  |
| 0     | 11       | 7.05%   |
| 3     | 4        | 2.56%   |
| 4     | 1        | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 89       | 44.5%   |
| Intel                      | 72       | 36%     |
| Qualcomm Atheros           | 13       | 6.5%    |
| Broadcom                   | 8        | 4%      |
| Ralink Technology          | 3        | 1.5%    |
| Nvidia                     | 2        | 1%      |
| Microsoft                  | 2        | 1%      |
| ZTE WCDMA Technologies MSM | 1        | 0.5%    |
| Xiaomi                     | 1        | 0.5%    |
| TP-Link                    | 1        | 0.5%    |
| Ralink                     | 1        | 0.5%    |
| Mellanox Technologies      | 1        | 0.5%    |
| Marvell Technology Group   | 1        | 0.5%    |
| Edimax Technology          | 1        | 0.5%    |
| D-Link                     | 1        | 0.5%    |
| Broadcom Limited           | 1        | 0.5%    |
| Aquantia                   | 1        | 0.5%    |
| American Megatrends        | 1        | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 69       | 30.4%   |
| Intel I211 Gigabit Network Connection                               | 12       | 5.29%   |
| Realtek RTL8125 2.5GbE Controller                                   | 10       | 4.41%   |
| Intel Ethernet Connection (2) I219-V                                | 10       | 4.41%   |
| Intel Wi-Fi 6 AX200                                                 | 7        | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 7        | 3.08%   |
| Intel I210 Gigabit Network Connection                               | 6        | 2.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 6        | 2.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 3        | 1.32%   |
| Intel Ethernet Connection I217-V                                    | 3        | 1.32%   |
| Intel Ethernet Connection (2) I218-V                                | 3        | 1.32%   |
| Intel 82574L Gigabit Network Connection                             | 3        | 1.32%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 3        | 1.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.88%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2        | 0.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 2        | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2        | 0.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.88%   |
| Nvidia MCP61 Ethernet                                               | 2        | 0.88%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 2        | 0.88%   |
| Intel Wireless 8260                                                 | 2        | 0.88%   |
| Intel Wireless 7260                                                 | 2        | 0.88%   |
| Intel Wireless 3165                                                 | 2        | 0.88%   |
| Intel Ethernet Controller 10G X550T                                 | 2        | 0.88%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                    | 2        | 0.88%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                       | 1        | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.44%   |
| TP-Link Archer T4U ver.3                                            | 1        | 0.44%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.44%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1        | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 1        | 0.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 0.44%   |
| Realtek 802.11ac NIC                                                | 1        | 0.44%   |
| Ralink RT5372 Wireless Adapter                                      | 1        | 0.44%   |
| Ralink RT5370 Wireless Adapter                                      | 1        | 0.44%   |
| Ralink MT7601U Wireless Adapter                                     | 1        | 0.44%   |
| Ralink RT5392 PCIe Wireless Network Adapter                         | 1        | 0.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1        | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 1        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1        | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.44%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 0.44%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 0.44%   |
| Mellanox MT27500 Family [ConnectX-3]                                | 1        | 0.44%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.44%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                   | 1        | 0.44%   |
| Intel Wireless-AC 9260                                              | 1        | 0.44%   |
| Intel Wireless 8265 / 8275                                          | 1        | 0.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 1        | 0.44%   |
| Intel NM10/ICH7 Family LAN Controller                               | 1        | 0.44%   |
| Intel I350 Gigabit Network Connection                               | 1        | 0.44%   |
| Intel Ethernet Virtual Function 700 Series                          | 1        | 0.44%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                    | 1        | 0.44%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                       | 1        | 0.44%   |
| Intel Ethernet Connection I354                                      | 1        | 0.44%   |
| Intel Ethernet Connection (7) I219-V                                | 1        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 21       | 44.68%  |
| Realtek Semiconductor | 9        | 19.15%  |
| Qualcomm Atheros      | 5        | 10.64%  |
| Ralink Technology     | 3        | 6.38%   |
| Broadcom              | 3        | 6.38%   |
| Microsoft             | 2        | 4.26%   |
| TP-Link               | 1        | 2.13%   |
| Ralink                | 1        | 2.13%   |
| Edimax Technology     | 1        | 2.13%   |
| D-Link                | 1        | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 7        | 14.89%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6        | 12.77%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2        | 4.26%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2        | 4.26%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2        | 4.26%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 2        | 4.26%   |
| Intel Wireless 8260                                                     | 2        | 4.26%   |
| Intel Wireless 7260                                                     | 2        | 4.26%   |
| Intel Wireless 3165                                                     | 2        | 4.26%   |
| TP-Link Archer T4U ver.3                                                | 1        | 2.13%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 2.13%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1        | 2.13%   |
| Realtek 802.11ac NIC                                                    | 1        | 2.13%   |
| Ralink RT5372 Wireless Adapter                                          | 1        | 2.13%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 2.13%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 2.13%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1        | 2.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 2.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 2.13%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1        | 2.13%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1        | 2.13%   |
| Intel Wireless-AC 9260                                                  | 1        | 2.13%   |
| Intel Wireless 8265 / 8275                                              | 1        | 2.13%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1        | 2.13%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 2.13%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1        | 2.13%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1        | 2.13%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1        | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 85       | 50.3%   |
| Intel                    | 62       | 36.69%  |
| Qualcomm Atheros         | 9        | 5.33%   |
| Broadcom                 | 5        | 2.96%   |
| Nvidia                   | 2        | 1.18%   |
| Xiaomi                   | 1        | 0.59%   |
| Mellanox Technologies    | 1        | 0.59%   |
| Marvell Technology Group | 1        | 0.59%   |
| Broadcom Limited         | 1        | 0.59%   |
| Aquantia                 | 1        | 0.59%   |
| American Megatrends      | 1        | 0.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69       | 38.55%  |
| Intel I211 Gigabit Network Connection                             | 12       | 6.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 5.59%   |
| Intel Ethernet Connection (2) I219-V                              | 10       | 5.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 3.91%   |
| Intel I210 Gigabit Network Connection                             | 6        | 3.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.68%   |
| Intel Ethernet Connection I217-V                                  | 3        | 1.68%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.68%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.68%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 1.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 1.12%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 1.12%   |
| Nvidia MCP61 Ethernet                                             | 2        | 1.12%   |
| Intel Ethernet Controller 10G X550T                               | 2        | 1.12%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.56%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 0.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.56%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.56%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.56%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.56%   |
| Intel Ethernet Virtual Function 700 Series                        | 1        | 0.56%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 0.56%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.56%   |
| Intel Ethernet Connection I354                                    | 1        | 0.56%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 1        | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.56%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.56%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.56%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.56%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.56%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.56%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.56%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.56%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.56%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 0.56%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.56%   |
| Intel 82540EM Gigabit Ethernet Controller                         | 1        | 0.56%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.56%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.56%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 0.56%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 1        | 0.56%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.56%   |
| American Megatrends Virtual Ethernet                              | 1        | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 155      | 76.35%  |
| WiFi     | 47       | 23.15%  |
| Modem    | 1        | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 141      | 82.94%  |
| WiFi     | 29       | 17.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 94       | 60.26%  |
| 2     | 49       | 31.41%  |
| 3     | 7        | 4.49%   |
| 4     | 2        | 1.28%   |
| 13    | 1        | 0.64%   |
| 6     | 1        | 0.64%   |
| 5     | 1        | 0.64%   |
| 0     | 1        | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 124      | 79.49%  |
| Yes  | 32       | 20.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 19       | 48.72%  |
| Cambridge Silicon Radio         | 9        | 23.08%  |
| Broadcom                        | 5        | 12.82%  |
| ASUSTek Computer                | 4        | 10.26%  |
| Realtek Semiconductor           | 1        | 2.56%   |
| Qualcomm Atheros Communications | 1        | 2.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 23.08%  |
| Intel AX200 Bluetooth                               | 7        | 17.95%  |
| Intel Wireless-AC 3168 Bluetooth                    | 5        | 12.82%  |
| Intel Bluetooth wireless interface                  | 5        | 12.82%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 5.13%   |
| Realtek Bluetooth Radio                             | 1        | 2.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 2.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.56%   |
| Intel Bluetooth Device                              | 1        | 2.56%   |
| Broadcom Bluetooth 3.0 Device                       | 1        | 2.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 2.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 2.56%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 2.56%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1        | 2.56%   |
| ASUS Bluetooth Radio                                | 1        | 2.56%   |
| ASUS Bluetooth Adapter                              | 1        | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 80       | 30.65%  |
| AMD                        | 75       | 28.74%  |
| Nvidia                     | 59       | 22.61%  |
| C-Media Electronics        | 10       | 3.83%   |
| GYROCOM C&C                | 4        | 1.53%   |
| Creative Labs              | 4        | 1.53%   |
| Logitech                   | 3        | 1.15%   |
| Generalplus Technology     | 3        | 1.15%   |
| Samson Technologies        | 2        | 0.77%   |
| GN Netcom                  | 2        | 0.77%   |
| BEHRINGER International    | 2        | 0.77%   |
| XMOS                       | 1        | 0.38%   |
| VIA Technologies           | 1        | 0.38%   |
| Texas Instruments          | 1        | 0.38%   |
| TEAC                       | 1        | 0.38%   |
| SteelSeries ApS            | 1        | 0.38%   |
| RODE Microphones           | 1        | 0.38%   |
| ROCCAT                     | 1        | 0.38%   |
| PreSonus Audio Electronics | 1        | 0.38%   |
| JMTek                      | 1        | 0.38%   |
| Hangzhou Worlde            | 1        | 0.38%   |
| Dell                       | 1        | 0.38%   |
| Blue Microphones           | 1        | 0.38%   |
| AXELVOX                    | 1        | 0.38%   |
| AVID Technology            | 1        | 0.38%   |
| Audioengine                | 1        | 0.38%   |
| ASUSTek Computer           | 1        | 0.38%   |
| Alesis                     | 1        | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 27       | 9%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 14       | 4.67%   |
| Intel 200 Series PCH HD Audio                                              | 13       | 4.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13       | 4.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 11       | 3.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9        | 3%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 2.67%   |
| AMD FCH Azalia Controller                                                  | 8        | 2.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 2.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 2.33%   |
| AMD Navi 10 HDMI Audio                                                     | 7        | 2.33%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 2%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 2%      |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 1.67%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 5        | 1.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 1.67%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 1.33%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 1%      |
| Intel Comet Lake PCH cAVS                                                  | 3        | 1%      |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 1%      |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1%      |
| GYROCOM C&C Fiio E10                                                       | 3        | 1%      |
| Generalplus Technology USB Audio Device                                    | 3        | 1%      |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 1%      |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.67%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.67%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.67%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.67%   |
| Nvidia High Definition Audio Controller                                    | 2        | 0.67%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.67%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.67%   |
| Nvidia GF104 High Definition Audio Controller                              | 2        | 0.67%   |
| Logitech G430 Surround Sound Gaming Headset                                | 2        | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 0.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2        | 0.67%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                         | 2        | 0.67%   |
| C-Media Electronics USB Audio Device                                       | 2        | 0.67%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 0.67%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 2        | 0.67%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 2        | 0.67%   |
| XMOS HIFI DSD                                                              | 1        | 0.33%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 0.33%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.33%   |
| TEAC US-2x2                                                                | 1        | 0.33%   |
| SteelSeries ApS SteelSeries Arctis 9                                       | 1        | 0.33%   |
| Samson Technologies Q1U dynamic microphone                                 | 1        | 0.33%   |
| Samson Technologies Meteorite condenser microphone                         | 1        | 0.33%   |
| RODE Microphones RODE NT-USB Mini                                          | 1        | 0.33%   |
| ROCCAT Juke                                                                | 1        | 0.33%   |
| PreSonus Audio Electronics PreSonus AudioBox iTwo                          | 1        | 0.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 35       | 21.47%  |
| Unknown             | 25       | 15.34%  |
| Corsair             | 24       | 14.72%  |
| Samsung Electronics | 16       | 9.82%   |
| G.Skill             | 14       | 8.59%   |
| Crucial             | 14       | 8.59%   |
| SK Hynix            | 13       | 7.98%   |
| Micron Technology   | 4        | 2.45%   |
| Patriot             | 3        | 1.84%   |
| A-DATA Technology   | 3        | 1.84%   |
| Team                | 2        | 1.23%   |
| Kllisre             | 2        | 1.23%   |
| Elpida              | 2        | 1.23%   |
| V-Color             | 1        | 0.61%   |
| Unknown (ABCD)      | 1        | 0.61%   |
| Kingmax             | 1        | 0.61%   |
| KETECH              | 1        | 0.61%   |
| GOODRAM             | 1        | 0.61%   |
| GeIL                | 1        | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 5        | 2.67%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s            | 4        | 2.14%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s               | 3        | 1.6%    |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s             | 3        | 1.6%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s             | 3        | 1.6%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                         | 2        | 1.07%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 2        | 1.07%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                          | 2        | 1.07%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                        | 2        | 1.07%   |
| Unknown RAM 99[2/7/4]164(F/R) 4GB DIMM DDR3 1600MT/s              | 2        | 1.07%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s                | 2        | 1.07%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                 | 2        | 1.07%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                 | 2        | 1.07%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s               | 2        | 1.07%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s               | 2        | 1.07%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s               | 2        | 1.07%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s            | 2        | 1.07%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s            | 2        | 1.07%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s             | 2        | 1.07%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s             | 2        | 1.07%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s                  | 1        | 0.53%   |
| Unknown RAM V02D4LF8GB5285282400 8192MB DIMM DDR4 2400MT/s        | 1        | 0.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1        | 0.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 1        | 0.53%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 1        | 0.53%   |
| Unknown RAM Module 512MB DIMM SDRAM 400MT/s                       | 1        | 0.53%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                        | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM 800MT/s                               | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM 400MT/s                               | 1        | 0.53%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s                        | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM 800MT/s                               | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM 400MT/s                               | 1        | 0.53%   |
| Unknown RAM Module 256MB DIMM SDRAM 400MT/s                       | 1        | 0.53%   |
| Unknown RAM Module 1GB DIMM SDRAM                                 | 1        | 0.53%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                          | 1        | 0.53%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                        | 1        | 0.53%   |
| Unknown RAM 7EH64AA# 8GB DIMM DDR4 2667MT/s                       | 1        | 0.53%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s             | 1        | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2133MT/s | 1        | 0.53%   |
| Team RAM TEAMGROUP-UD3-1333 8GB DIMM DDR3 1333MT/s                | 1        | 0.53%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                        | 1        | 0.53%   |
| SK Hynix RAM S949A4UUH-ITR 16GB DIMM DDR4 2400MT/s                | 1        | 0.53%   |
| SK Hynix RAM HYMP512U64CP8-S5 1GB DIMM DDR2 400MT/s               | 1        | 0.53%   |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 400MT/s               | 1        | 0.53%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1        | 0.53%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1        | 0.53%   |
| SK Hynix RAM HMT41GE7BFR8A-PB 8GB DIMM DDR3 1600MT/s              | 1        | 0.53%   |
| SK Hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 1333MT/s                 | 1        | 0.53%   |
| SK Hynix RAM HMT325U7CFR8A-H9 2GB DIMM DDR3 1333MT/s              | 1        | 0.53%   |
| SK Hynix RAM HMT31GR7BFR4A-H9 8GB DIMM DDR3 1333MT/s              | 1        | 0.53%   |
| SK Hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1        | 0.53%   |
| SK Hynix RAM HMT125U6TFR8C-G7 2GB DIMM DDR3 1067MT/s              | 1        | 0.53%   |
| SK Hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s              | 1        | 0.53%   |
| SK Hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s              | 1        | 0.53%   |
| SK Hynix RAM HMA41GR7AFR4N-TF 8GB DIMM DDR4 2133MT/s              | 1        | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s          | 1        | 0.53%   |
| Samsung RAM M471B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s               | 1        | 0.53%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s               | 1        | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 69       | 47.92%  |
| DDR3    | 53       | 36.81%  |
| Unknown | 9        | 6.25%   |
| SDRAM   | 6        | 4.17%   |
| DDR2    | 6        | 4.17%   |
| LPDDR4  | 1        | 0.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 138      | 96.5%   |
| SODIMM | 4        | 2.8%    |
| RIMM   | 1        | 0.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 61       | 38.85%  |
| 4096  | 33       | 21.02%  |
| 16384 | 26       | 16.56%  |
| 2048  | 16       | 10.19%  |
| 32768 | 9        | 5.73%   |
| 1024  | 7        | 4.46%   |
| 512   | 3        | 1.91%   |
| 65536 | 1        | 0.64%   |
| 256   | 1        | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 36       | 21.95%  |
| 1333    | 23       | 14.02%  |
| 3200    | 19       | 11.59%  |
| 2667    | 14       | 8.54%   |
| 2400    | 11       | 6.71%   |
| 3600    | 10       | 6.1%    |
| 800     | 6        | 3.66%   |
| 2133    | 5        | 3.05%   |
| 2933    | 4        | 2.44%   |
| 1867    | 4        | 2.44%   |
| 1866    | 4        | 2.44%   |
| 3466    | 3        | 1.83%   |
| 2666    | 3        | 1.83%   |
| 667     | 3        | 1.83%   |
| 400     | 3        | 1.83%   |
| 3400    | 2        | 1.22%   |
| 3000    | 2        | 1.22%   |
| 1067    | 2        | 1.22%   |
| Unknown | 2        | 1.22%   |
| 3533    | 1        | 0.61%   |
| 3500    | 1        | 0.61%   |
| 3100    | 1        | 0.61%   |
| 3066    | 1        | 0.61%   |
| 2465    | 1        | 0.61%   |
| 2000    | 1        | 0.61%   |
| 1800    | 1        | 0.61%   |
| 1367    | 1        | 0.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 57.14%  |
| Samsung Electronics | 1        | 14.29%  |
| Konica Minolta      | 1        | 14.29%  |
| Canon               | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Samsung ML-1660 Series      | 1        | 14.29%  |
| Konica Minolta bizhub 4402P | 1        | 14.29%  |
| HP LaserJet P1006           | 1        | 14.29%  |
| HP LaserJet M101-M106       | 1        | 14.29%  |
| HP LaserJet 1200            | 1        | 14.29%  |
| HP ENVY 4520 series         | 1        | 14.29%  |
| Canon iP2700 series         | 1        | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 12       | 34.29%  |
| Microdia                      | 5        | 14.29%  |
| Samsung Electronics           | 3        | 8.57%   |
| Genesys Logic                 | 2        | 5.71%   |
| Generalplus Technology        | 2        | 5.71%   |
| Z-Star Microelectronics       | 1        | 2.86%   |
| Xiongmai                      | 1        | 2.86%   |
| Sunplus Innovation Technology | 1        | 2.86%   |
| SiGma Micro                   | 1        | 2.86%   |
| Razer USA                     | 1        | 2.86%   |
| Jieli Technology              | 1        | 2.86%   |
| Huawei Technologies           | 1        | 2.86%   |
| Hewlett-Packard               | 1        | 2.86%   |
| eMPIA Technology              | 1        | 2.86%   |
| AVerMedia Technologies        | 1        | 2.86%   |
| ARC International             | 1        | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)             | 3        | 8.57%   |
| Microdia Webcam Vitade AF           | 3        | 8.57%   |
| Logitech HD Pro Webcam C920         | 3        | 8.57%   |
| Logitech Webcam C270                | 2        | 5.71%   |
| Logitech HD Webcam C910             | 2        | 5.71%   |
| Logitech HD Webcam C615             | 2        | 5.71%   |
| Z-Star Venus USB2.0 Camera          | 1        | 2.86%   |
| Xiongmai web camera                 | 1        | 2.86%   |
| Sunplus HD USB Camaer 4K            | 1        | 2.86%   |
| SiGma Micro WebCam SiGma Micro      | 1        | 2.86%   |
| Razer USA Razer Kiyo                | 1        | 2.86%   |
| Microdia USB 2.0 Camera             | 1        | 2.86%   |
| Microdia Integrated Camera          | 1        | 2.86%   |
| Logitech Webcam C260                | 1        | 2.86%   |
| Logitech Quickcam 3000 For Business | 1        | 2.86%   |
| Logitech BRIO                       | 1        | 2.86%   |
| Jieli USB PHY 2.0                   | 1        | 2.86%   |
| Huawei UVC Camera                   | 1        | 2.86%   |
| HP Webcam 3110                      | 1        | 2.86%   |
| Genesys Logic USB2.0 Digital Camera | 1        | 2.86%   |
| Genesys Logic Camera                | 1        | 2.86%   |
| Generalplus GENERAL WEBCAM          | 1        | 2.86%   |
| Generalplus 808 Camera              | 1        | 2.86%   |
| eMPIA M035 Compact Web Cam          | 1        | 2.86%   |
| AVerMedia Live Gamer Ultra-Video    | 1        | 2.86%   |
| ARC International Camera            | 1        | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Yubico.com            | 1        | 50%     |
| Gemalto (was Gemplus) | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Yubico.com Yubikey 4 CCID                         | 1        | 50%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 141      | 90.38%  |
| 1     | 13       | 8.33%   |
| 5     | 1        | 0.64%   |
| 2     | 1        | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 46.67%  |
| Unassigned class         | 3        | 20%     |
| Sound                    | 1        | 6.67%   |
| Network                  | 1        | 6.67%   |
| Net/wireless             | 1        | 6.67%   |
| Multimedia controller    | 1        | 6.67%   |
| Communication controller | 1        | 6.67%   |

