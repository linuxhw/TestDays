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
| Gigabyte   | 970A-DS3P                   | [9b62457757](https://linux-hardware.org/?probe=9b62457757) | Aug 11, 2021 |
| ASUSTek    | PRIME A320M-K               | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| ASUSTek    | STRIX B250H GAMING          | [78223998b6](https://linux-hardware.org/?probe=78223998b6) | Aug 10, 2021 |
| MSI        | B250M PRO-VDH               | [d6be998202](https://linux-hardware.org/?probe=d6be998202) | Aug 10, 2021 |
| ASUSTek    | PRIME A320M-K               | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Dell       | 04MFRM A01                  | [c0094def97](https://linux-hardware.org/?probe=c0094def97) | Aug 09, 2021 |
| MSI        | B450 TOMAHAWK               | [58b4f52cc0](https://linux-hardware.org/?probe=58b4f52cc0) | Aug 09, 2021 |
| Gigabyte   | H470M DS3H                  | [29de4693d8](https://linux-hardware.org/?probe=29de4693d8) | Aug 09, 2021 |
| ASRock     | 970A-G                      | [f1e9959894](https://linux-hardware.org/?probe=f1e9959894) | Aug 09, 2021 |
| Toshiba    | STI 910090 STIJ             | [389ebd7675](https://linux-hardware.org/?probe=389ebd7675) | Aug 08, 2021 |
| ASRock     | X370 Killer SLI             | [8a0885afb6](https://linux-hardware.org/?probe=8a0885afb6) | Aug 08, 2021 |
| MSI        | Z490-A PRO                  | [eac37d633f](https://linux-hardware.org/?probe=eac37d633f) | Aug 08, 2021 |
| ASRock     | Z97 Pro4                    | [090d12a96f](https://linux-hardware.org/?probe=090d12a96f) | Aug 08, 2021 |
| ASUSTek    | ROG STRIX B350-F GAMING     | [39eb5a1578](https://linux-hardware.org/?probe=39eb5a1578) | Aug 08, 2021 |
| Toshiba    | STI 005038 G31T-M7          | [faa8f15725](https://linux-hardware.org/?probe=faa8f15725) | Aug 08, 2021 |
| Gigabyte   | Z77-D3H                     | [9dafe47483](https://linux-hardware.org/?probe=9dafe47483) | Aug 07, 2021 |
| MSI        | X470 GAMING PLUS MAX        | [da833ac33e](https://linux-hardware.org/?probe=da833ac33e) | Aug 07, 2021 |
| ASUSTek    | TUF Z370-PLUS GAMING        | [80c7711147](https://linux-hardware.org/?probe=80c7711147) | Aug 07, 2021 |
| Gigabyte   | Z77-D3H                     | [4ff5966d22](https://linux-hardware.org/?probe=4ff5966d22) | Aug 07, 2021 |
| ASUSTek    | PRIME X470-PRO              | [5839492cd8](https://linux-hardware.org/?probe=5839492cd8) | Aug 07, 2021 |
| ASUSTek    | PRIME B460-PLUS             | [733a3e325c](https://linux-hardware.org/?probe=733a3e325c) | Aug 07, 2021 |
| Dell       | 08WKV3 A01                  | [8ab0ff9442](https://linux-hardware.org/?probe=8ab0ff9442) | Aug 07, 2021 |
| MSI        | MEG X399 CREATION           | [7cada9aaed](https://linux-hardware.org/?probe=7cada9aaed) | Aug 07, 2021 |
| MSI        | B250M PRO-VDH               | [187e4dd872](https://linux-hardware.org/?probe=187e4dd872) | Aug 07, 2021 |
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
| 5.10.0-8-amd64                 | 104      | 58.1%   |
| 5.10.0-7-amd64                 | 44       | 24.58%  |
| 5.10.0-6-amd64                 | 9        | 5.03%   |
| 5.11.22-1-pve                  | 3        | 1.68%   |
| 5.10.0-8-rt-amd64              | 2        | 1.12%   |
| 5.10.0-8-686-pae               | 2        | 1.12%   |
| 5.8.0-3-amd64                  | 1        | 0.56%   |
| 5.13.8-gnu                     | 1        | 0.56%   |
| 5.13.4                         | 1        | 0.56%   |
| 5.13.1a                        | 1        | 0.56%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1        | 0.56%   |
| 5.11.22-2-pve                  | 1        | 0.56%   |
| 5.11.0-21.1-liquorix-amd64     | 1        | 0.56%   |
| 5.11.0-16.1-liquorix-amd64     | 1        | 0.56%   |
| 5.10.46custom                  | 1        | 0.56%   |
| 5.10.42+truenas                | 1        | 0.56%   |
| 5.10.38-falcot                 | 1        | 0.56%   |
| 5.10.0-8-686                   | 1        | 0.56%   |
| 5.10.0-7-686-pae               | 1        | 0.56%   |
| 5.10.0-3-amd64                 | 1        | 0.56%   |
| 5.10.0-2-amd64                 | 1        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 162      | 92.05%  |
| 5.11.22 | 4        | 2.27%   |
| 5.11.0  | 2        | 1.14%   |
| 5.8.0   | 1        | 0.57%   |
| 5.13.8  | 1        | 0.57%   |
| 5.13.4  | 1        | 0.57%   |
| 5.13.1  | 1        | 0.57%   |
| 5.13.0  | 1        | 0.57%   |
| 5.10.46 | 1        | 0.57%   |
| 5.10.42 | 1        | 0.57%   |
| 5.10.38 | 1        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 165      | 93.75%  |
| 5.11    | 6        | 3.41%   |
| 5.13    | 4        | 2.27%   |
| 5.8     | 1        | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 172      | 97.73%  |
| i686   | 4        | 2.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KDE5             | 36       | 20.34%  |
| GNOME            | 33       | 18.64%  |
| Unknown          | 25       | 14.12%  |
| XFCE             | 20       | 11.3%   |
| MATE             | 16       | 9.04%   |
| Cinnamon         | 11       | 6.21%   |
| LXQt             | 6        | 3.39%   |
| Trinity          | 5        | 2.82%   |
| LXDE             | 5        | 2.82%   |
| i3               | 5        | 2.82%   |
| X-Cinnamon       | 4        | 2.26%   |
| KDE              | 4        | 2.26%   |
| lightdm-xsession | 2        | 1.13%   |
| GNOME Flashback  | 2        | 1.13%   |
| sway             | 1        | 0.56%   |
| GNUstep          | 1        | 0.56%   |
| Budgie           | 1        | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 124      | 70.45%  |
| Tty     | 22       | 12.5%   |
| Wayland | 20       | 11.36%  |
| Unknown | 10       | 5.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 64       | 36.16%  |
| Unknown | 37       | 20.9%   |
| SDDM    | 35       | 19.77%  |
| GDM     | 32       | 18.08%  |
| LightDM | 5        | 2.82%   |
| SLiM    | 3        | 1.69%   |
| XDM     | 1        | 0.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 80       | 45.45%  |
| ru_RU   | 15       | 8.52%   |
| en_GB   | 12       | 6.82%   |
| fr_FR   | 10       | 5.68%   |
| de_DE   | 8        | 4.55%   |
| Unknown | 7        | 3.98%   |
| pt_BR   | 5        | 2.84%   |
| es_ES   | 5        | 2.84%   |
| C       | 4        | 2.27%   |
| pl_PL   | 3        | 1.7%    |
| en_CA   | 3        | 1.7%    |
| en_AU   | 3        | 1.7%    |
| nl_BE   | 2        | 1.14%   |
| es_AR   | 2        | 1.14%   |
| uk_UA   | 1        | 0.57%   |
| sv_SE   | 1        | 0.57%   |
| sr_RS   | 1        | 0.57%   |
| ru_UA   | 1        | 0.57%   |
| ro_RO   | 1        | 0.57%   |
| nl_NL   | 1        | 0.57%   |
| it_IT   | 1        | 0.57%   |
| hu_HU   | 1        | 0.57%   |
| hr_HR   | 1        | 0.57%   |
| es_VE   | 1        | 0.57%   |
| es_US   | 1        | 0.57%   |
| en_PH   | 1        | 0.57%   |
| en_IN   | 1        | 0.57%   |
| en_IE   | 1        | 0.57%   |
| en_HK   | 1        | 0.57%   |
| de_CH   | 1        | 0.57%   |
| cs_CZ   | 1        | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 91       | 51.41%  |
| BIOS | 86       | 48.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 130      | 73.86%  |
| Overlay | 18       | 10.23%  |
| Btrfs   | 16       | 9.09%   |
| Ext3    | 5        | 2.84%   |
| Zfs     | 4        | 2.27%   |
| Xfs     | 2        | 1.14%   |
| Unknown | 1        | 0.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 114      | 64.41%  |
| MBR     | 48       | 27.12%  |
| Unknown | 15       | 8.47%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 126      | 71.59%  |
| Yes       | 50       | 28.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 130      | 73.45%  |
| Yes       | 47       | 26.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 44       | 25%     |
| Gigabyte Technology | 37       | 21.02%  |
| ASRock              | 26       | 14.77%  |
| MSI                 | 22       | 12.5%   |
| Dell                | 16       | 9.09%   |
| Hewlett-Packard     | 10       | 5.68%   |
| Lenovo              | 3        | 1.7%    |
| Intel               | 3        | 1.7%    |
| Supermicro          | 2        | 1.14%   |
| Semp Toshiba        | 2        | 1.14%   |
| Huanan              | 2        | 1.14%   |
| Foxconn             | 2        | 1.14%   |
| Shuttle             | 1        | 0.57%   |
| Protectli           | 1        | 0.57%   |
| HARDKERNEL          | 1        | 0.57%   |
| ECS                 | 1        | 0.57%   |
| Biostar             | 1        | 0.57%   |
| ASRockRack          | 1        | 0.57%   |
| Unknown             | 1        | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 4        | 2.27%   |
| Gigabyte Z77-D3H                  | 3        | 1.7%    |
| Gigabyte B550I AORUS PRO AX       | 3        | 1.7%    |
| ASRock B450M Pro4                 | 3        | 1.7%    |
| Semp Toshiba STI                  | 2        | 1.14%   |
| MSI MS-7A70                       | 2        | 1.14%   |
| HP Z620 Workstation               | 2        | 1.14%   |
| Gigabyte Z370 AORUS Gaming 5      | 2        | 1.14%   |
| Gigabyte 970A-DS3P                | 2        | 1.14%   |
| Dell OptiPlex 760                 | 2        | 1.14%   |
| ASUS PRIME B550-PLUS              | 2        | 1.14%   |
| ASUS PRIME B450M-A                | 2        | 1.14%   |
| ASUS PRIME A320M-K                | 2        | 1.14%   |
| Supermicro SYS-5038MA-H24TRF      | 1        | 0.57%   |
| Supermicro SYS-5019S-MR           | 1        | 0.57%   |
| Shuttle SX79R                     | 1        | 0.57%   |
| Protectli FW6                     | 1        | 0.57%   |
| MSI MS-7C94                       | 1        | 0.57%   |
| MSI MS-7C84                       | 1        | 0.57%   |
| MSI MS-7C75                       | 1        | 0.57%   |
| MSI MS-7C56                       | 1        | 0.57%   |
| MSI MS-7C35                       | 1        | 0.57%   |
| MSI MS-7C02                       | 1        | 0.57%   |
| MSI MS-7B92                       | 1        | 0.57%   |
| MSI MS-7B89                       | 1        | 0.57%   |
| MSI MS-7B79                       | 1        | 0.57%   |
| MSI MS-7B46                       | 1        | 0.57%   |
| MSI MS-7B09                       | 1        | 0.57%   |
| MSI MS-7A40                       | 1        | 0.57%   |
| MSI MS-7A38                       | 1        | 0.57%   |
| MSI MS-7995                       | 1        | 0.57%   |
| MSI MS-7823                       | 1        | 0.57%   |
| MSI MS-7759                       | 1        | 0.57%   |
| MSI MS-7721                       | 1        | 0.57%   |
| MSI MS-7641                       | 1        | 0.57%   |
| MSI MS-7562                       | 1        | 0.57%   |
| MSI MS-6712                       | 1        | 0.57%   |
| Lenovo ThinkCentre M92p 3209EK4   | 1        | 0.57%   |
| Lenovo ThinkCentre M73 10B00005US | 1        | 0.57%   |
| Lenovo ThinkCentre M55p 8808D8U   | 1        | 0.57%   |
| Intel DP55WG AAE57269-407         | 1        | 0.57%   |
| Intel DP55WB AAE64798-206         | 1        | 0.57%   |
| Intel DN2820FYK H24582-201        | 1        | 0.57%   |
| Huanan X99-F8                     | 1        | 0.57%   |
| Huanan X99-8M-F V1.1              | 1        | 0.57%   |
| HP Z840 Workstation               | 1        | 0.57%   |
| HP t620 Dual Core TC              | 1        | 0.57%   |
| HP ProLiant MicroServer Gen8      | 1        | 0.57%   |
| HP ProLiant MicroServer           | 1        | 0.57%   |
| HP EliteDesk 705 G1 SFF           | 1        | 0.57%   |
| HP Compaq 8200 Elite SFF PC       | 1        | 0.57%   |
| HP Compaq 6005 Pro MT PC          | 1        | 0.57%   |
| HP 200-010hk                      | 1        | 0.57%   |
| HARDKERNEL ODROID-H2              | 1        | 0.57%   |
| Gigabyte Z97X-UD3H                | 1        | 0.57%   |
| Gigabyte Z170X-GamingG1           | 1        | 0.57%   |
| Gigabyte Z170M-D3H                | 1        | 0.57%   |
| Gigabyte X570 I AORUS PRO WIFI    | 1        | 0.57%   |
| Gigabyte X399 AORUS XTREME        | 1        | 0.57%   |
| Gigabyte P35C-DS3R                | 1        | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS PRIME                   | 18       | 10.23%  |
| Dell OptiPlex                | 11       | 6.25%   |
| ASUS ROG                     | 6        | 3.41%   |
| Dell Precision               | 4        | 2.27%   |
| ASUS All                     | 4        | 2.27%   |
| Lenovo ThinkCentre           | 3        | 1.7%    |
| Gigabyte Z77-D3H             | 3        | 1.7%    |
| Gigabyte B550I               | 3        | 1.7%    |
| ASRock Z97                   | 3        | 1.7%    |
| ASRock B450M                 | 3        | 1.7%    |
| Semp Toshiba STI             | 2        | 1.14%   |
| MSI MS-7A70                  | 2        | 1.14%   |
| HP Z620                      | 2        | 1.14%   |
| HP ProLiant                  | 2        | 1.14%   |
| HP Compaq                    | 2        | 1.14%   |
| Gigabyte Z370                | 2        | 1.14%   |
| Gigabyte 970A-DS3P           | 2        | 1.14%   |
| Supermicro SYS-5038MA-H24TRF | 1        | 0.57%   |
| Supermicro SYS-5019S-MR      | 1        | 0.57%   |
| Shuttle SX79R                | 1        | 0.57%   |
| Protectli FW6                | 1        | 0.57%   |
| MSI MS-7C94                  | 1        | 0.57%   |
| MSI MS-7C84                  | 1        | 0.57%   |
| MSI MS-7C75                  | 1        | 0.57%   |
| MSI MS-7C56                  | 1        | 0.57%   |
| MSI MS-7C35                  | 1        | 0.57%   |
| MSI MS-7C02                  | 1        | 0.57%   |
| MSI MS-7B92                  | 1        | 0.57%   |
| MSI MS-7B89                  | 1        | 0.57%   |
| MSI MS-7B79                  | 1        | 0.57%   |
| MSI MS-7B46                  | 1        | 0.57%   |
| MSI MS-7B09                  | 1        | 0.57%   |
| MSI MS-7A40                  | 1        | 0.57%   |
| MSI MS-7A38                  | 1        | 0.57%   |
| MSI MS-7995                  | 1        | 0.57%   |
| MSI MS-7823                  | 1        | 0.57%   |
| MSI MS-7759                  | 1        | 0.57%   |
| MSI MS-7721                  | 1        | 0.57%   |
| MSI MS-7641                  | 1        | 0.57%   |
| MSI MS-7562                  | 1        | 0.57%   |
| MSI MS-6712                  | 1        | 0.57%   |
| Intel DP55WG                 | 1        | 0.57%   |
| Intel DP55WB                 | 1        | 0.57%   |
| Intel DN2820FYK              | 1        | 0.57%   |
| Huanan X99-F8                | 1        | 0.57%   |
| Huanan X99-8M-F              | 1        | 0.57%   |
| HP Z840                      | 1        | 0.57%   |
| HP t620                      | 1        | 0.57%   |
| HP EliteDesk                 | 1        | 0.57%   |
| HP 200-010hk                 | 1        | 0.57%   |
| HARDKERNEL ODROID-H2         | 1        | 0.57%   |
| Gigabyte Z97X-UD3H           | 1        | 0.57%   |
| Gigabyte Z170X-GamingG1      | 1        | 0.57%   |
| Gigabyte Z170M-D3H           | 1        | 0.57%   |
| Gigabyte X570                | 1        | 0.57%   |
| Gigabyte X399                | 1        | 0.57%   |
| Gigabyte P35C-DS3R           | 1        | 0.57%   |
| Gigabyte H87-HD3             | 1        | 0.57%   |
| Gigabyte H81M-S2H            | 1        | 0.57%   |
| Gigabyte H61MS               | 1        | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 34       | 19.32%  |
| 2019 | 26       | 14.77%  |
| 2018 | 21       | 11.93%  |
| 2021 | 16       | 9.09%   |
| 2016 | 14       | 7.95%   |
| 2014 | 11       | 6.25%   |
| 2012 | 11       | 6.25%   |
| 2015 | 9        | 5.11%   |
| 2010 | 8        | 4.55%   |
| 2013 | 6        | 3.41%   |
| 2009 | 6        | 3.41%   |
| 2017 | 4        | 2.27%   |
| 2011 | 3        | 1.7%    |
| 2007 | 3        | 1.7%    |
| 2006 | 2        | 1.14%   |
| 2008 | 1        | 0.57%   |
| 2001 | 1        | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 176      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 173      | 98.3%   |
| Enabled  | 3        | 1.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 175      | 99.43%  |
| Yes  | 1        | 0.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 57       | 32.39%  |
| 8.01-16.0       | 32       | 18.18%  |
| 32.01-64.0      | 30       | 17.05%  |
| 64.01-256.0     | 19       | 10.8%   |
| 4.01-8.0        | 17       | 9.66%   |
| 3.01-4.0        | 10       | 5.68%   |
| 1.01-2.0        | 5        | 2.84%   |
| 24.01-32.0      | 2        | 1.14%   |
| 2.01-3.0        | 2        | 1.14%   |
| More than 256.0 | 1        | 0.57%   |
| 0.51-1.0        | 1        | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 34       | 19.21%  |
| 4.01-8.0    | 31       | 17.51%  |
| 3.01-4.0    | 30       | 16.95%  |
| 2.01-3.0    | 28       | 15.82%  |
| 0.51-1.0    | 17       | 9.6%    |
| 8.01-16.0   | 14       | 7.91%   |
| 0.01-0.5    | 11       | 6.21%   |
| 16.01-24.0  | 5        | 2.82%   |
| 24.01-32.0  | 4        | 2.26%   |
| 32.01-64.0  | 2        | 1.13%   |
| 64.01-256.0 | 1        | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 56       | 31.82%  |
| 2      | 49       | 27.84%  |
| 3      | 31       | 17.61%  |
| 4      | 16       | 9.09%   |
| 5      | 11       | 6.25%   |
| 8      | 4        | 2.27%   |
| 6      | 4        | 2.27%   |
| 9      | 3        | 1.7%    |
| 10     | 2        | 1.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 55.11%  |
| Yes       | 79       | 44.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 175      | 99.43%  |
| No        | 1        | 0.57%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 126      | 71.59%  |
| Yes       | 50       | 28.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 76.7%   |
| Yes       | 41       | 23.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 43       | 24.43%  |
| Russia                 | 17       | 9.66%   |
| Germany                | 13       | 7.39%   |
| France                 | 13       | 7.39%   |
| UK                     | 12       | 6.82%   |
| Ukraine                | 8        | 4.55%   |
| Spain                  | 7        | 3.98%   |
| Poland                 | 5        | 2.84%   |
| Brazil                 | 5        | 2.84%   |
| Australia              | 4        | 2.27%   |
| Sweden                 | 3        | 1.7%    |
| Netherlands            | 3        | 1.7%    |
| Mexico                 | 3        | 1.7%    |
| Czechia                | 3        | 1.7%    |
| Canada                 | 3        | 1.7%    |
| Bulgaria               | 3        | 1.7%    |
| Belgium                | 3        | 1.7%    |
| Argentina              | 3        | 1.7%    |
| Venezuela              | 2        | 1.14%   |
| Switzerland            | 2        | 1.14%   |
| Norway                 | 2        | 1.14%   |
| Italy                  | 2        | 1.14%   |
| Hungary                | 2        | 1.14%   |
| Finland                | 2        | 1.14%   |
| Syria                  | 1        | 0.57%   |
| Singapore              | 1        | 0.57%   |
| Serbia                 | 1        | 0.57%   |
| Romania                | 1        | 0.57%   |
| New Caledonia          | 1        | 0.57%   |
| Madagascar             | 1        | 0.57%   |
| India                  | 1        | 0.57%   |
| Hong Kong              | 1        | 0.57%   |
| Greece                 | 1        | 0.57%   |
| Ecuador                | 1        | 0.57%   |
| Croatia                | 1        | 0.57%   |
| Bosnia and Herzegovina | 1        | 0.57%   |
| Austria                | 1        | 0.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Ocala                       | 5        | 2.81%   |
| Lyon                        | 5        | 2.81%   |
| Portland                    | 4        | 2.25%   |
| Sofia                       | 3        | 1.69%   |
| London                      | 3        | 1.69%   |
| Kalamazoo                   | 3        | 1.69%   |
| Ensenada                    | 3        | 1.69%   |
| Warsaw                      | 2        | 1.12%   |
| Stockholm                   | 2        | 1.12%   |
| Saint-Denis                 | 2        | 1.12%   |
| Perm                        | 2        | 1.12%   |
| New York                    | 2        | 1.12%   |
| Moscow                      | 2        | 1.12%   |
| Las Vegas                   | 2        | 1.12%   |
| Kyiv                        | 2        | 1.12%   |
| Kharkiv                     | 2        | 1.12%   |
| Clitheroe                   | 2        | 1.12%   |
| Athens                      | 2        | 1.12%   |
| Érd                        | 1        | 0.56%   |
| Zastavka                    | 1        | 0.56%   |
| Zagreb                      | 1        | 0.56%   |
| Yuncos                      | 1        | 0.56%   |
| Yekaterinburg               | 1        | 0.56%   |
| Woolloongabba               | 1        | 0.56%   |
| Woodstock                   | 1        | 0.56%   |
| Wenatchee                   | 1        | 0.56%   |
| Waregem                     | 1        | 0.56%   |
| Voerde                      | 1        | 0.56%   |
| Vladimir                    | 1        | 0.56%   |
| Vienna                      | 1        | 0.56%   |
| Vancouver                   | 1        | 0.56%   |
| Valera                      | 1        | 0.56%   |
| Vaasa                       | 1        | 0.56%   |
| Ulyanovsk                   | 1        | 0.56%   |
| Ufa                         | 1        | 0.56%   |
| Turku                       | 1        | 0.56%   |
| Toulouse                    | 1        | 0.56%   |
| Thionville                  | 1        | 0.56%   |
| Tai Kok Tsui                | 1        | 0.56%   |
| Stroud                      | 1        | 0.56%   |
| Strasbourg                  | 1        | 0.56%   |
| Stockelsdorf                | 1        | 0.56%   |
| Stavanger                   | 1        | 0.56%   |
| St Petersburg               | 1        | 0.56%   |
| Springfield                 | 1        | 0.56%   |
| Sosnowiec                   | 1        | 0.56%   |
| Singapore                   | 1        | 0.56%   |
| Sevastopol                  | 1        | 0.56%   |
| S??o Paulo                  | 1        | 0.56%   |
| Saratov                     | 1        | 0.56%   |
| Sarajevo                    | 1        | 0.56%   |
| Santa Brigida               | 1        | 0.56%   |
| San Francisco               | 1        | 0.56%   |
| San Cristóbal de La Laguna | 1        | 0.56%   |
| Rochester                   | 1        | 0.56%   |
| Ribeirao Pires              | 1        | 0.56%   |
| Reedsburg                   | 1        | 0.56%   |
| Prague                      | 1        | 0.56%   |
| Phoenix                     | 1        | 0.56%   |
| Pforzheim                   | 1        | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 69       | 112    | 21.56%  |
| Seagate             | 65       | 106    | 20.31%  |
| Samsung Electronics | 47       | 74     | 14.69%  |
| Crucial             | 22       | 26     | 6.88%   |
| Toshiba             | 20       | 36     | 6.25%   |
| Kingston            | 20       | 24     | 6.25%   |
| SanDisk             | 11       | 14     | 3.44%   |
| Intel               | 10       | 17     | 3.13%   |
| Hitachi             | 9        | 10     | 2.81%   |
| SPCC                | 5        | 5      | 1.56%   |
| HGST                | 5        | 7      | 1.56%   |
| A-DATA Technology   | 5        | 7      | 1.56%   |
| PNY                 | 4        | 4      | 1.25%   |
| Gigabyte Technology | 3        | 3      | 0.94%   |
| Unknown             | 2        | 2      | 0.63%   |
| SABRENT             | 2        | 2      | 0.63%   |
| Phison Electronics  | 2        | 2      | 0.63%   |
| Phison              | 2        | 2      | 0.63%   |
| Corsair             | 2        | 2      | 0.63%   |
| Transcend           | 1        | 2      | 0.31%   |
| Team                | 1        | 1      | 0.31%   |
| T-FORCE             | 1        | 1      | 0.31%   |
| SK Hynix            | 1        | 2      | 0.31%   |
| Patriot             | 1        | 1      | 0.31%   |
| OCZ                 | 1        | 1      | 0.31%   |
| NAS                 | 1        | 5      | 0.31%   |
| Micron Technology   | 1        | 1      | 0.31%   |
| MaxDigital          | 1        | 2      | 0.31%   |
| Lexar               | 1        | 1      | 0.31%   |
| KingDian            | 1        | 1      | 0.31%   |
| Intenso             | 1        | 2      | 0.31%   |
| Hewlett-Packard     | 1        | 1      | 0.31%   |
| DOGFISH             | 1        | 1      | 0.31%   |
| China               | 1        | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB           | 8        | 2.04%   |
| Seagate ST1000DM010-2EP102 1TB    | 6        | 1.53%   |
| Toshiba HDWD110 1TB               | 5        | 1.27%   |
| Seagate ST4000DM004-2CV104 4TB    | 5        | 1.27%   |
| Samsung SSD 970 EVO Plus 500GB    | 5        | 1.27%   |
| Samsung SSD 850 EVO 500GB         | 5        | 1.27%   |
| Toshiba DT01ACA300 3TB            | 4        | 1.02%   |
| Toshiba DT01ACA200 2TB            | 4        | 1.02%   |
| Seagate ST500DM002-1BD142 500GB   | 4        | 1.02%   |
| Samsung SSD 970 EVO Plus 1TB      | 4        | 1.02%   |
| Samsung SSD 970 EVO 500GB         | 4        | 1.02%   |
| Samsung SSD 850 EVO 250GB         | 4        | 1.02%   |
| Kingston SA400S37120G 120GB SSD   | 4        | 1.02%   |
| WDC WDS500G3X0C-00SJG0 500GB      | 3        | 0.76%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 3        | 0.76%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 3        | 0.76%   |
| WDC WD40EFRX-68N32N0 4TB          | 3        | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB          | 3        | 0.76%   |
| WDC WD10EZEX-00BN5A0 1TB          | 3        | 0.76%   |
| Seagate ST3000DM001-1CH166 3TB    | 3        | 0.76%   |
| Seagate ST2000DM008-2FR102 2TB    | 3        | 0.76%   |
| Seagate ST2000DM001-1ER164 2TB    | 3        | 0.76%   |
| Kingston SV300S37A240G 240GB SSD  | 3        | 0.76%   |
| Kingston SV300S37A120G 120GB SSD  | 3        | 0.76%   |
| Kingston SA400S37240G 240GB SSD   | 3        | 0.76%   |
| Hitachi HUS724040ALE641 4TB       | 3        | 0.76%   |
| Crucial CT500P1SSD8 500GB         | 3        | 0.76%   |
| Crucial CT240BX500SSD1 240GB      | 3        | 0.76%   |
| Crucial CT1000MX500SSD1 1TB       | 3        | 0.76%   |
| WDC WDS500G2B0C-00PXH0 500GB      | 2        | 0.51%   |
| WDC WD5000AADS-00S9B0 500GB       | 2        | 0.51%   |
| WDC WD20EZAZ-00GGJB0 2TB          | 2        | 0.51%   |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 0.51%   |
| WDC WD20EARX-00PASB0 2TB          | 2        | 0.51%   |
| WDC WD20EARS-00MVWB0 2TB          | 2        | 0.51%   |
| WDC WD10EFRX-68FYTN0 1TB          | 2        | 0.51%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 2        | 0.51%   |
| Seagate ST4000DM000-1F2168 4TB    | 2        | 0.51%   |
| Seagate ST3160815AS 160GB         | 2        | 0.51%   |
| Seagate ST2000DM006-2DM164 2TB    | 2        | 0.51%   |
| Seagate ST1000DM003-1CH162 1TB    | 2        | 0.51%   |
| Seagate BUP Slim BL 2TB           | 2        | 0.51%   |
| Seagate Backup+ Hub BK 4TB        | 2        | 0.51%   |
| SanDisk SD8SBAT128G1122 128GB SSD | 2        | 0.51%   |
| Sandisk NVMe SSD Drive 1TB        | 2        | 0.51%   |
| Samsung SSD 960 EVO 250GB         | 2        | 0.51%   |
| Samsung SSD 860 EVO 500GB         | 2        | 0.51%   |
| Samsung SSD 860 EVO 2TB           | 2        | 0.51%   |
| Samsung SSD 860 EVO 250GB         | 2        | 0.51%   |
| Samsung SSD 840 PRO Series 256GB  | 2        | 0.51%   |
| Samsung HD103SJ 1TB               | 2        | 0.51%   |
| SABRENT Disk 4TB                  | 2        | 0.51%   |
| Phison PCIe SSD 512GB             | 2        | 0.51%   |
| Kingston SUV500240G 240GB SSD     | 2        | 0.51%   |
| Intel SSDPEKNW010T9 1TB           | 2        | 0.51%   |
| Intel NVMe SSD Drive 1024GB       | 2        | 0.51%   |
| Intel MEMPEK1J016GAL 16GB         | 2        | 0.51%   |
| Crucial CT525MX300SSD1 528GB      | 2        | 0.51%   |
| Crucial CT500P2SSD8 500GB         | 2        | 0.51%   |
| Crucial CT500MX500SSD1 500GB      | 2        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 62       | 93     | 38.99%  |
| WDC                 | 56       | 91     | 35.22%  |
| Toshiba             | 18       | 32     | 11.32%  |
| Hitachi             | 9        | 10     | 5.66%   |
| Samsung Electronics | 7        | 8      | 4.4%    |
| HGST                | 5        | 7      | 3.14%   |
| NAS                 | 1        | 5      | 0.63%   |
| MaxDigital          | 1        | 2      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 27       | 39     | 24.77%  |
| Kingston            | 19       | 23     | 17.43%  |
| Crucial             | 16       | 18     | 14.68%  |
| WDC                 | 10       | 11     | 9.17%   |
| SanDisk             | 8        | 10     | 7.34%   |
| A-DATA Technology   | 5        | 6      | 4.59%   |
| SPCC                | 4        | 4      | 3.67%   |
| PNY                 | 3        | 3      | 2.75%   |
| Toshiba             | 2        | 4      | 1.83%   |
| SABRENT             | 2        | 2      | 1.83%   |
| Unknown             | 1        | 1      | 0.92%   |
| Transcend           | 1        | 2      | 0.92%   |
| Team                | 1        | 1      | 0.92%   |
| T-FORCE             | 1        | 1      | 0.92%   |
| Seagate             | 1        | 1      | 0.92%   |
| Patriot             | 1        | 1      | 0.92%   |
| OCZ                 | 1        | 1      | 0.92%   |
| Micron Technology   | 1        | 1      | 0.92%   |
| Lexar               | 1        | 1      | 0.92%   |
| KingDian            | 1        | 1      | 0.92%   |
| Gigabyte Technology | 1        | 1      | 0.92%   |
| DOGFISH             | 1        | 1      | 0.92%   |
| China               | 1        | 1      | 0.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 126      | 248    | 42.86%  |
| SSD     | 101      | 134    | 34.35%  |
| NVMe    | 60       | 81     | 20.41%  |
| Unknown | 6        | 14     | 2.04%   |
| MMC     | 1        | 1      | 0.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 160      | 373    | 68.09%  |
| NVMe | 60       | 81     | 25.53%  |
| SAS  | 14       | 23     | 5.96%   |
| MMC  | 1        | 1      | 0.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 107      | 152    | 42.8%   |
| 0.51-1.0   | 67       | 92     | 26.8%   |
| 1.01-2.0   | 38       | 52     | 15.2%   |
| 3.01-4.0   | 17       | 44     | 6.8%    |
| 2.01-3.0   | 11       | 18     | 4.4%    |
| 4.01-10.0  | 8        | 21     | 3.2%    |
| 10.01-20.0 | 2        | 3      | 0.8%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 33       | 18.75%  |
| 251-500        | 28       | 15.91%  |
| 101-250        | 22       | 12.5%   |
| 501-1000       | 22       | 12.5%   |
| 1001-2000      | 21       | 11.93%  |
| 1-20           | 18       | 10.23%  |
| 2001-3000      | 12       | 6.82%   |
| 51-100         | 9        | 5.11%   |
| Unknown        | 7        | 3.98%   |
| 21-50          | 4        | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 46       | 25.99%  |
| 101-250        | 20       | 11.3%   |
| 501-1000       | 19       | 10.73%  |
| 251-500        | 18       | 10.17%  |
| 21-50          | 17       | 9.6%    |
| More than 3000 | 15       | 8.47%   |
| 1001-2000      | 15       | 8.47%   |
| 51-100         | 12       | 6.78%   |
| 2001-3000      | 7        | 3.95%   |
| Unknown        | 7        | 3.95%   |
| 0              | 1        | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 4.17%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 4.17%   |
| WDC WD5003ABYX-18WERA0 500GB          | 1        | 2      | 2.08%   |
| WDC WD5000AAKX-00U6AA0 500GB          | 1        | 1      | 2.08%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 2.08%   |
| WDC WD5000AAKS-22V1A0 500GB           | 1        | 1      | 2.08%   |
| WDC WD5000AAJS-22A8B0 500GB           | 1        | 1      | 2.08%   |
| WDC WD40EFZX-68AWUN0 4TB              | 1        | 6      | 2.08%   |
| WDC WD400BB-00DEA0 40GB               | 1        | 1      | 2.08%   |
| WDC WD30EZRX-00AZ6B0 3TB              | 1        | 1      | 2.08%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 2.08%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 2.08%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1        | 1      | 2.08%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1        | 1      | 2.08%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 2.08%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 2.08%   |
| WDC WD1001FALS-75J7B0 1TB             | 1        | 1      | 2.08%   |
| Toshiba MK2565GSX 250GB               | 1        | 1      | 2.08%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 2.08%   |
| SK Hynix PC401 NVMe 512GB             | 1        | 2      | 2.08%   |
| Seagate ST3320620A 320GB              | 1        | 1      | 2.08%   |
| Seagate ST3200827AS 200GB             | 1        | 1      | 2.08%   |
| Seagate ST32000542AS 2TB              | 1        | 1      | 2.08%   |
| Seagate ST3160813AS 160GB             | 1        | 1      | 2.08%   |
| Seagate ST31500341AS 1TB              | 1        | 1      | 2.08%   |
| Seagate ST3120827AS 120GB             | 1        | 1      | 2.08%   |
| Seagate ST31000333AS 1TB              | 1        | 1      | 2.08%   |
| Seagate ST3000DM001-9YN166 320GB      | 1        | 1      | 2.08%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 2.08%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 2.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 2.08%   |
| Seagate ST1000DM003-9YN162 1TB        | 1        | 1      | 2.08%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 2.08%   |
| SanDisk SSD PLUS 120 GB               | 1        | 1      | 2.08%   |
| Samsung Electronics SSD 970 EVO 250GB | 1        | 1      | 2.08%   |
| Samsung Electronics SP0842N 80GB      | 1        | 1      | 2.08%   |
| Samsung Electronics HD161GJ 160GB     | 1        | 1      | 2.08%   |
| PNY SSD2SC240G3LC709B121-460P 240GB   | 1        | 1      | 2.08%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 2.08%   |
| Kingston SE100S3100G 100GB SSD        | 1        | 1      | 2.08%   |
| KingDian S280-240GB SSD               | 1        | 1      | 2.08%   |
| Intel SSDPEKKW010T7 1TB               | 1        | 2      | 2.08%   |
| Hitachi HUA722020ALA331 2TB           | 1        | 1      | 2.08%   |
| Hitachi HDS722525VLAT80 250GB         | 1        | 1      | 2.08%   |
| A-DATA Technology SU800 256GB SSD     | 1        | 2      | 2.08%   |
| A-DATA Technology SSD DP900 128GB-DL3 | 1        | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 24     | 36.96%  |
| Seagate             | 13       | 15     | 28.26%  |
| Samsung Electronics | 3        | 3      | 6.52%   |
| Toshiba             | 2        | 2      | 4.35%   |
| Kingston            | 2        | 2      | 4.35%   |
| Hitachi             | 2        | 2      | 4.35%   |
| A-DATA Technology   | 2        | 3      | 4.35%   |
| SK Hynix            | 1        | 2      | 2.17%   |
| SanDisk             | 1        | 1      | 2.17%   |
| PNY                 | 1        | 1      | 2.17%   |
| KingDian            | 1        | 1      | 2.17%   |
| Intel               | 1        | 2      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 24     | 47.22%  |
| Seagate             | 13       | 15     | 36.11%  |
| Toshiba             | 2        | 2      | 5.56%   |
| Samsung Electronics | 2        | 2      | 5.56%   |
| Hitachi             | 2        | 2      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 35       | 45     | 77.78%  |
| SSD  | 7        | 8      | 15.56%  |
| NVMe | 3        | 5      | 6.67%   |

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
| Works    | 155      | 363    | 69.82%  |
| Malfunc  | 42       | 58     | 18.92%  |
| Detected | 23       | 55     | 10.36%  |
| Failed   | 2        | 2      | 0.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 100      | 39.68%  |
| AMD                         | 75       | 29.76%  |
| Samsung Electronics         | 23       | 9.13%   |
| Sandisk                     | 10       | 3.97%   |
| Phison Electronics          | 9        | 3.57%   |
| Micron/Crucial Technology   | 7        | 2.78%   |
| ASMedia Technology          | 7        | 2.78%   |
| Marvell Technology Group    | 5        | 1.98%   |
| JMicron Technology          | 3        | 1.19%   |
| VIA Technologies            | 2        | 0.79%   |
| Nvidia                      | 2        | 0.79%   |
| Broadcom / LSI              | 2        | 0.79%   |
| SK Hynix                    | 1        | 0.4%    |
| Silicon Motion              | 1        | 0.4%    |
| Silicon Image               | 1        | 0.4%    |
| Seagate Technology          | 1        | 0.4%    |
| Kingston Technology Company | 1        | 0.4%    |
| ADATA Technology            | 1        | 0.4%    |
| Adaptec                     | 1        | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 47       | 14.16%  |
| AMD 400 Series Chipset SATA Controller                                                  | 19       | 5.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 18       | 5.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 15       | 4.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 3.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11       | 3.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 3.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 2.71%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 9        | 2.71%   |
| Phison E12 NVMe Controller                                                              | 6        | 1.81%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 1.81%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 1.81%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 5        | 1.51%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 1.51%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 1.51%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4        | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 1.2%    |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.2%    |
| AMD X399 Series Chipset SATA Controller                                                 | 4        | 1.2%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.9%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 0.9%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.9%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.9%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 0.9%    |
| AMD X370 Series Chipset SATA Controller                                                 | 3        | 0.9%    |
| AMD FCH SATA Controller D                                                               | 3        | 0.9%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.6%    |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.6%    |
| Nvidia MCP61 IDE                                                                        | 2        | 0.6%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.6%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.6%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.6%    |
| Intel SSD 660P Series                                                                   | 2        | 0.6%    |
| Intel SSD 600P Series                                                                   | 2        | 0.6%    |
| Intel NVMe Optane Memory Series                                                         | 2        | 0.6%    |
| Intel Non-Volatile memory controller                                                    | 2        | 0.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 0.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 0.6%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.6%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.6%    |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 0.6%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.6%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.6%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.6%    |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.3%    |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                             | 1        | 0.3%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.3%    |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.3%    |
| Seagate FireCuda 510 SSD                                                                | 1        | 0.3%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 0.3%    |
| Sandisk WD Black SN850                                                                  | 1        | 0.3%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.3%    |
| Samsung NVMe Controller                                                                 | 1        | 0.3%    |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 153      | 57.95%  |
| NVMe | 60       | 22.73%  |
| IDE  | 36       | 13.64%  |
| RAID | 10       | 3.79%   |
| SAS  | 5        | 1.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 99       | 56.25%  |
| AMD    | 77       | 43.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 10       | 5.68%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 4        | 2.27%   |
| Intel Core i7-7700 CPU @ 3.60GHz               | 3        | 1.7%    |
| Intel Core i5-7500 CPU @ 3.40GHz               | 3        | 1.7%    |
| Intel Core i5-4570 CPU @ 3.20GHz               | 3        | 1.7%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 3        | 1.7%    |
| AMD Ryzen 9 3900X 12-Core Processor            | 3        | 1.7%    |
| AMD Ryzen 7 5800X 8-Core Processor             | 3        | 1.7%    |
| AMD Ryzen 5 5600X 6-Core Processor             | 3        | 1.7%    |
| AMD Ryzen 5 1600 Six-Core Processor            | 3        | 1.7%    |
| AMD FX-8350 Eight-Core Processor               | 3        | 1.7%    |
| Intel Pentium Gold G5420 CPU @ 3.80GHz         | 2        | 1.14%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 1.14%   |
| Intel Core i7-8086K CPU @ 4.00GHz              | 2        | 1.14%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 2        | 1.14%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 2        | 1.14%   |
| Intel Core i5-6600 CPU @ 3.30GHz               | 2        | 1.14%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 2        | 1.14%   |
| Intel Core i5-4460 CPU @ 3.20GHz               | 2        | 1.14%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 2        | 1.14%   |
| Intel Core i5 CPU 650 @ 3.20GHz                | 2        | 1.14%   |
| Intel Core i3-10100 CPU @ 3.60GHz              | 2        | 1.14%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 2        | 1.14%   |
| AMD Ryzen Threadripper 2950X 16-Core Processor | 2        | 1.14%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 2        | 1.14%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 1.14%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 2        | 1.14%   |
| AMD Ryzen 3 1200 Quad-Core Processor           | 2        | 1.14%   |
| AMD Phenom II X4 965 Processor                 | 2        | 1.14%   |
| AMD FX-4300 Quad-Core Processor                | 2        | 1.14%   |
| Intel Xeon W-2145 CPU @ 3.70GHz                | 1        | 0.57%   |
| Intel Xeon CPU W3503 @ 2.40GHz                 | 1        | 0.57%   |
| Intel Xeon CPU E5-2699 v4 @ 2.20GHz            | 1        | 0.57%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz            | 1        | 0.57%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz             | 1        | 0.57%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz            | 1        | 0.57%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz             | 1        | 0.57%   |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz            | 1        | 0.57%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz             | 1        | 0.57%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz             | 1        | 0.57%   |
| Intel Xeon CPU E3-1230 v6 @ 3.50GHz            | 1        | 0.57%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 1        | 0.57%   |
| Intel Pentium CPU N3700 @ 1.60GHz              | 1        | 0.57%   |
| Intel Pentium CPU G3258 @ 3.20GHz              | 1        | 0.57%   |
| Intel Pentium CPU G3250 @ 3.20GHz              | 1        | 0.57%   |
| Intel Pentium CPU G2030 @ 3.00GHz              | 1        | 0.57%   |
| Intel Pentium 4 CPU 3.06GHz                    | 1        | 0.57%   |
| Intel Pentium 4 CPU 2.80GHz                    | 1        | 0.57%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 1        | 0.57%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 0.57%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1        | 0.57%   |
| Intel Core i7-4820K CPU @ 3.70GHz              | 1        | 0.57%   |
| Intel Core i7-4790S CPU @ 3.20GHz              | 1        | 0.57%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 0.57%   |
| Intel Core i7-10710U CPU @ 1.10GHz             | 1        | 0.57%   |
| Intel Core i7-10700K CPU @ 3.80GHz             | 1        | 0.57%   |
| Intel Core i7 CPU 860 @ 2.80GHz                | 1        | 0.57%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 0.57%   |
| Intel Core i5-9400F CPU @ 2.90GHz              | 1        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 34       | 19.32%  |
| AMD Ryzen 5             | 23       | 13.07%  |
| Intel Core i7           | 20       | 11.36%  |
| AMD Ryzen 7             | 14       | 7.95%   |
| Intel Xeon              | 11       | 6.25%   |
| AMD FX                  | 9        | 5.11%   |
| Intel Core i3           | 6        | 3.41%   |
| Intel Celeron           | 6        | 3.41%   |
| Intel Core 2 Duo        | 5        | 2.84%   |
| AMD Ryzen Threadripper  | 5        | 2.84%   |
| Intel Pentium           | 4        | 2.27%   |
| AMD Ryzen 9             | 4        | 2.27%   |
| AMD Ryzen 3             | 4        | 2.27%   |
| AMD Phenom II X4        | 4        | 2.27%   |
| Intel Core 2 Quad       | 3        | 1.7%    |
| Intel Pentium Gold      | 2        | 1.14%   |
| Intel Pentium 4         | 2        | 1.14%   |
| Intel Core 2            | 2        | 1.14%   |
| AMD Athlon X4           | 2        | 1.14%   |
| AMD A10                 | 2        | 1.14%   |
| Other                   | 1        | 0.57%   |
| Intel Pentium Dual-Core | 1        | 0.57%   |
| Intel Core i9           | 1        | 0.57%   |
| Intel Atom              | 1        | 0.57%   |
| AMD Sempron             | 1        | 0.57%   |
| AMD PRO A8              | 1        | 0.57%   |
| AMD Phenom II X3        | 1        | 0.57%   |
| AMD GX                  | 1        | 0.57%   |
| AMD Athlon XP           | 1        | 0.57%   |
| AMD Athlon II X2        | 1        | 0.57%   |
| AMD Athlon II Neo       | 1        | 0.57%   |
| AMD Athlon Dual Core    | 1        | 0.57%   |
| AMD A8                  | 1        | 0.57%   |
| AMD A6                  | 1        | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 64       | 36.36%  |
| 2      | 37       | 21.02%  |
| 6      | 33       | 18.75%  |
| 8      | 22       | 12.5%   |
| 1      | 6        | 3.41%   |
| 16     | 5        | 2.84%   |
| 12     | 5        | 2.84%   |
| 44     | 1        | 0.57%   |
| 32     | 1        | 0.57%   |
| 28     | 1        | 0.57%   |
| 3      | 1        | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 173      | 98.3%   |
| 2      | 3        | 1.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 103      | 58.52%  |
| 1      | 73       | 41.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 174      | 98.86%  |
| 32-bit         | 2        | 1.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 16.38%  |
| 0x306c3    | 15       | 8.47%   |
| 0x08701021 | 15       | 8.47%   |
| 0x306a9    | 8        | 4.52%   |
| 0x906e9    | 7        | 3.95%   |
| 0x0800820d | 6        | 3.39%   |
| 0x06003106 | 6        | 3.39%   |
| 0x906ea    | 5        | 2.82%   |
| 0x506e3    | 5        | 2.82%   |
| 0x206a7    | 5        | 2.82%   |
| 0x06000852 | 5        | 2.82%   |
| 0x206d7    | 4        | 2.26%   |
| 0x1067a    | 4        | 2.26%   |
| 0x0a201009 | 4        | 2.26%   |
| 0xa0655    | 3        | 1.69%   |
| 0x306f2    | 3        | 1.69%   |
| 0x08001138 | 3        | 1.69%   |
| 0x010000c8 | 3        | 1.69%   |
| 0x010000b6 | 3        | 1.69%   |
| 0xa0653    | 2        | 1.13%   |
| 0x6fb      | 2        | 1.13%   |
| 0x0a201016 | 2        | 1.13%   |
| 0x08701013 | 2        | 1.13%   |
| 0x08001137 | 2        | 1.13%   |
| 0xf49      | 1        | 0.56%   |
| 0xf41      | 1        | 0.56%   |
| 0xf29      | 1        | 0.56%   |
| 0xa0671    | 1        | 0.56%   |
| 0xa0660    | 1        | 0.56%   |
| 0x906ed    | 1        | 0.56%   |
| 0x906ec    | 1        | 0.56%   |
| 0x906eb    | 1        | 0.56%   |
| 0x806e9    | 1        | 0.56%   |
| 0x706a1    | 1        | 0.56%   |
| 0x6fd      | 1        | 0.56%   |
| 0x6f6      | 1        | 0.56%   |
| 0x6f2      | 1        | 0.56%   |
| 0x50654    | 1        | 0.56%   |
| 0x406f1    | 1        | 0.56%   |
| 0x406d8    | 1        | 0.56%   |
| 0x406c3    | 1        | 0.56%   |
| 0x40651    | 1        | 0.56%   |
| 0x306e4    | 1        | 0.56%   |
| 0x30678    | 1        | 0.56%   |
| 0x30673    | 1        | 0.56%   |
| 0x20655    | 1        | 0.56%   |
| 0x106e5    | 1        | 0.56%   |
| 0x106a5    | 1        | 0.56%   |
| 0x0830104d | 1        | 0.56%   |
| 0x08108109 | 1        | 0.56%   |
| 0x08101016 | 1        | 0.56%   |
| 0x0800820b | 1        | 0.56%   |
| 0x08001129 | 1        | 0.56%   |
| 0x0700010f | 1        | 0.56%   |
| 0x0600081c | 1        | 0.56%   |
| 0x0600063e | 1        | 0.56%   |
| 0x0600063d | 1        | 0.56%   |
| 0x010000db | 1        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 23       | 13.07%  |
| KabyLake      | 20       | 11.36%  |
| Haswell       | 20       | 11.36%  |
| Zen+          | 12       | 6.82%   |
| IvyBridge     | 11       | 6.25%   |
| SandyBridge   | 9        | 5.11%   |
| Zen           | 8        | 4.55%   |
| Skylake       | 8        | 4.55%   |
| K10           | 8        | 4.55%   |
| Zen 3         | 7        | 3.98%   |
| Steamroller   | 7        | 3.98%   |
| Piledriver    | 7        | 3.98%   |
| Core          | 6        | 3.41%   |
| CometLake     | 6        | 3.41%   |
| Penryn        | 5        | 2.84%   |
| Silvermont    | 4        | 2.27%   |
| NetBurst      | 3        | 1.7%    |
| Westmere      | 2        | 1.14%   |
| Nehalem       | 2        | 1.14%   |
| Bulldozer     | 2        | 1.14%   |
| K8 Hammer     | 1        | 0.57%   |
| K6            | 1        | 0.57%   |
| Jaguar        | 1        | 0.57%   |
| Goldmont plus | 1        | 0.57%   |
| Broadwell     | 1        | 0.57%   |
| Unknown       | 1        | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 69       | 37.91%  |
| AMD                        | 59       | 32.42%  |
| Intel                      | 47       | 25.82%  |
| ASPEED Technology          | 5        | 2.75%   |
| VIA Technologies           | 1        | 0.55%   |
| Matrox Electronics Systems | 1        | 0.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 15       | 8.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 8        | 4.37%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 7        | 3.83%   |
| Nvidia GK208B [GeForce GT 710]                                                | 7        | 3.83%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 7        | 3.83%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 6        | 3.28%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 6        | 3.28%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 5        | 2.73%   |
| ASPEED Technology ASPEED Graphics Family                                      | 5        | 2.73%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 4        | 2.19%   |
| AMD Kaveri [Radeon R7 Graphics]                                               | 4        | 2.19%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 3        | 1.64%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 3        | 1.64%   |
| Intel HD Graphics 530                                                         | 3        | 1.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3        | 1.64%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 3        | 1.64%   |
| Nvidia GT218 [GeForce 210]                                                    | 2        | 1.09%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 2        | 1.09%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 2        | 1.09%   |
| Nvidia GK104 [GeForce GTX 670]                                                | 2        | 1.09%   |
| Nvidia GF104 [GeForce GTX 460]                                                | 2        | 1.09%   |
| Nvidia G98 [Quadro NVS 295]                                                   | 2        | 1.09%   |
| Intel HD Graphics 630                                                         | 2        | 1.09%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                     | 2        | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2        | 1.09%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 2        | 1.09%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                      | 2        | 1.09%   |
| AMD RS780L [Radeon 3000]                                                      | 2        | 1.09%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 2        | 1.09%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.55%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 1        | 0.55%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1        | 0.55%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 1        | 0.55%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 1        | 0.55%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                        | 1        | 0.55%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                        | 1        | 0.55%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 1        | 0.55%   |
| Nvidia GV100GL [Quadro GV100]                                                 | 1        | 0.55%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1        | 0.55%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 1        | 0.55%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                            | 1        | 0.55%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 1        | 0.55%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 1        | 0.55%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                             | 1        | 0.55%   |
| Nvidia GK110 [GeForce GTX 780]                                                | 1        | 0.55%   |
| Nvidia GK107GL [Quadro K2000]                                                 | 1        | 0.55%   |
| Nvidia GK107 [GeForce GTX 650]                                                | 1        | 0.55%   |
| Nvidia GK106GL [Quadro K4000]                                                 | 1        | 0.55%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                             | 1        | 0.55%   |
| Nvidia GK104 [GeForce GTX 770]                                                | 1        | 0.55%   |
| Nvidia GF119 [GeForce GT 520]                                                 | 1        | 0.55%   |
| Nvidia GF119 [GeForce 605]                                                    | 1        | 0.55%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                         | 1        | 0.55%   |
| Nvidia GF110 [GeForce GTX 560 Ti 448 Cores]                                   | 1        | 0.55%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1        | 0.55%   |
| Nvidia GF108 [GeForce GT 440]                                                 | 1        | 0.55%   |
| Nvidia GF106GL [Quadro 2000]                                                  | 1        | 0.55%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                            | 1        | 0.55%   |
| Nvidia GA102 [GeForce RTX 3090]                                               | 1        | 0.55%   |
| Nvidia G92 [GeForce GTS 250]                                                  | 1        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 66       | 37.5%   |
| 1 x AMD        | 56       | 31.82%  |
| 1 x Intel      | 43       | 24.43%  |
| 1 x ASPEED     | 4        | 2.27%   |
| Intel + Nvidia | 2        | 1.14%   |
| 2 x AMD        | 1        | 0.57%   |
| 1 x VIA        | 1        | 0.57%   |
| 1 x Matrox     | 1        | 0.57%   |
| AMD + Nvidia   | 1        | 0.57%   |
| AMD + ASPEED   | 1        | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 125      | 71.02%  |
| Proprietary | 46       | 26.14%  |
| Unknown     | 5        | 2.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 72       | 40.68%  |
| 7.01-8.0   | 23       | 12.99%  |
| 1.01-2.0   | 23       | 12.99%  |
| 3.01-4.0   | 18       | 10.17%  |
| 0.51-1.0   | 15       | 8.47%   |
| 0.01-0.5   | 13       | 7.34%   |
| 5.01-6.0   | 6        | 3.39%   |
| 8.01-16.0  | 3        | 1.69%   |
| 2.01-3.0   | 2        | 1.13%   |
| 24.01-32.0 | 1        | 0.56%   |
| 16.01-24.0 | 1        | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 25       | 13.09%  |
| Dell                 | 25       | 13.09%  |
| Goldstar             | 24       | 12.57%  |
| Acer                 | 18       | 9.42%   |
| Ancor Communications | 15       | 7.85%   |
| Hewlett-Packard      | 12       | 6.28%   |
| BenQ                 | 11       | 5.76%   |
| Philips              | 9        | 4.71%   |
| AOC                  | 9        | 4.71%   |
| ViewSonic            | 4        | 2.09%   |
| Eizo                 | 4        | 2.09%   |
| ASUSTek Computer     | 4        | 2.09%   |
| NEC Computers        | 3        | 1.57%   |
| Lenovo               | 3        | 1.57%   |
| Unknown              | 2        | 1.05%   |
| Sony                 | 2        | 1.05%   |
| LG Electronics       | 2        | 1.05%   |
| Iiyama               | 2        | 1.05%   |
| VMO                  | 1        | 0.52%   |
| Vizio                | 1        | 0.52%   |
| Vestel Elektronik    | 1        | 0.52%   |
| Prestigio            | 1        | 0.52%   |
| ODH                  | 1        | 0.52%   |
| MSI                  | 1        | 0.52%   |
| MIT                  | 1        | 0.52%   |
| Mi                   | 1        | 0.52%   |
| Medion               | 1        | 0.52%   |
| JVC                  | 1        | 0.52%   |
| INFOTRONIC           | 1        | 0.52%   |
| Idek Iiyama          | 1        | 0.52%   |
| HKC                  | 1        | 0.52%   |
| Hitachi              | 1        | 0.52%   |
| HannStar Display     | 1        | 0.52%   |
| COBY                 | 1        | 0.52%   |
| Belinea              | 1        | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 3        | 1.48%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 3        | 1.48%   |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3        | 1.48%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 2        | 0.99%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2        | 0.99%   |
| Lenovo L2251x Wide LEN0A12 1680x1050 474x296mm 22.0-inch               | 2        | 0.99%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2        | 0.99%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 0.99%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 2        | 0.99%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2        | 0.99%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2        | 0.99%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 2        | 0.99%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2        | 0.99%   |
| VMO WQX DP VMO1507 2560x1600 1600x1000mm 74.3-inch                     | 1        | 0.49%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                     | 1        | 0.49%   |
| ViewSonic VA926 Series VSC7D20 1280x1024 376x301mm 19.0-inch           | 1        | 0.49%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch              | 1        | 0.49%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.49%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.49%   |
| Sony TV *00 SNY3F05 3840x2160 952x535mm 43.0-inch                      | 1        | 0.49%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch      | 1        | 0.49%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.49%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch      | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch    | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch   | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 304x228mm 15.0-inch    | 1        | 0.49%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch     | 1        | 0.49%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch   | 1        | 0.49%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1        | 0.49%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch      | 1        | 0.49%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 0.49%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch       | 1        | 0.49%   |
| Samsung Electronics Monitor SAM1057 1280x1024 306x230mm 15.1-inch      | 1        | 0.49%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 0.49%   |
| Samsung Electronics LF27T850 SAM704F 2560x1440 597x336mm 27.0-inch     | 1        | 0.49%   |
| Samsung Electronics LCD Monitor SyncMaster 5760x1080                   | 1        | 0.49%   |
| Samsung Electronics LCD Monitor SMB2430L                               | 1        | 0.49%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch   | 1        | 0.49%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch  | 1        | 0.49%   |
| Samsung Electronics LCD Monitor SAM0BC9 1920x1080 600x340mm 27.2-inch  | 1        | 0.49%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 0.49%   |
| Samsung Electronics LCD Monitor C24F390 3360x1080                      | 1        | 0.49%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch     | 1        | 0.49%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1        | 0.49%   |
| Samsung Electronics C24FG70 SAM0D58 1920x1080 532x304mm 24.1-inch      | 1        | 0.49%   |
| Prestigio P151 ASB0503 1024x768 304x228mm 15.0-inch                    | 1        | 0.49%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1        | 0.49%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 0.49%   |
| Philips PHL 242E1GZ PHLC24C 1920x1080 527x296mm 23.8-inch              | 1        | 0.49%   |
| Philips PHL 241E1 PHLC207 1920x1080 530x300mm 24.0-inch                | 1        | 0.49%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1        | 0.49%   |
| Philips LCD Monitor PHLC0B8 1920x1080 600x340mm 27.2-inch              | 1        | 0.49%   |
| Philips LCD Monitor PHL0850 1680x1050 470x300mm 22.0-inch              | 1        | 0.49%   |
| Philips LCD Monitor PHL 243V7 3840x1080                                | 1        | 0.49%   |
| Philips LCD Monitor PHL 243V7                                          | 1        | 0.49%   |
| Philips 240S PHL087D 1920x1200 519x324mm 24.1-inch                     | 1        | 0.49%   |
| ODH LM24 ODH2492 1920x1080 345x259mm 17.0-inch                         | 1        | 0.49%   |
| NEC Computers LCD1550V NEC65C6 1024x768 304x228mm 15.0-inch            | 1        | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 76       | 40.43%  |
| 2560x1440 (QHD)    | 21       | 11.17%  |
| 3840x2160 (4K)     | 17       | 9.04%   |
| 1280x1024 (SXGA)   | 14       | 7.45%   |
| 1680x1050 (WSXGA+) | 10       | 5.32%   |
| 1920x1200 (WUXGA)  | 9        | 4.79%   |
| 1366x768 (WXGA)    | 7        | 3.72%   |
| 1600x900 (HD+)     | 5        | 2.66%   |
| Unknown            | 5        | 2.66%   |
| 2560x1080          | 4        | 2.13%   |
| 2560x1600          | 3        | 1.6%    |
| 1440x900 (WXGA+)   | 3        | 1.6%    |
| 1024x768 (XGA)     | 3        | 1.6%    |
| 2288x1287          | 2        | 1.06%   |
| 1600x1200          | 2        | 1.06%   |
| 7680x4320          | 1        | 0.53%   |
| 5760x1080          | 1        | 0.53%   |
| 4480x1440          | 1        | 0.53%   |
| 3840x1080          | 1        | 0.53%   |
| 3440x1440          | 1        | 0.53%   |
| 3360x1080          | 1        | 0.53%   |
| 1920x540           | 1        | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 34       | 17.99%  |
| 27      | 31       | 16.4%   |
| 23      | 27       | 14.29%  |
| 21      | 15       | 7.94%   |
| Unknown | 14       | 7.41%   |
| 17      | 10       | 5.29%   |
| 31      | 9        | 4.76%   |
| 18      | 7        | 3.7%    |
| 22      | 6        | 3.17%   |
| 20      | 5        | 2.65%   |
| 19      | 5        | 2.65%   |
| 15      | 5        | 2.65%   |
| 34      | 4        | 2.12%   |
| 142     | 2        | 1.06%   |
| 84      | 2        | 1.06%   |
| 29      | 2        | 1.06%   |
| 28      | 2        | 1.06%   |
| 74      | 1        | 0.53%   |
| 72      | 1        | 0.53%   |
| 55      | 1        | 0.53%   |
| 48      | 1        | 0.53%   |
| 38      | 1        | 0.53%   |
| 32      | 1        | 0.53%   |
| 26      | 1        | 0.53%   |
| 25      | 1        | 0.53%   |
| 16      | 1        | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 82       | 45.05%  |
| 401-500        | 37       | 20.33%  |
| 601-700        | 16       | 8.79%   |
| 301-350        | 16       | 8.79%   |
| Unknown        | 14       | 7.69%   |
| 701-800        | 5        | 2.75%   |
| 1501-2000      | 4        | 2.2%    |
| 351-400        | 3        | 1.65%   |
| More than 2000 | 2        | 1.1%    |
| 1001-1500      | 2        | 1.1%    |
| 801-900        | 1        | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 113      | 62.78%  |
| 16/10   | 23       | 12.78%  |
| Unknown | 13       | 7.22%   |
| 5/4     | 12       | 6.67%   |
| 4/3     | 7        | 3.89%   |
| 21/9    | 5        | 2.78%   |
| 1.00    | 3        | 1.67%   |
| 3/2     | 2        | 1.11%   |
| 6/5     | 1        | 0.56%   |
| 1.96    | 1        | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 62       | 33.7%   |
| 301-350        | 31       | 16.85%  |
| 351-500        | 18       | 9.78%   |
| 151-200        | 15       | 8.15%   |
| 251-300        | 14       | 7.61%   |
| 141-150        | 14       | 7.61%   |
| Unknown        | 14       | 7.61%   |
| More than 1000 | 7        | 3.8%    |
| 101-110        | 5        | 2.72%   |
| 131-140        | 2        | 1.09%   |
| 501-1000       | 2        | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 108      | 61.36%  |
| 101-120 | 31       | 17.61%  |
| Unknown | 14       | 7.95%   |
| 121-160 | 10       | 5.68%   |
| 161-240 | 7        | 3.98%   |
| 1-50    | 6        | 3.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 126      | 71.59%  |
| 2     | 33       | 18.75%  |
| 0     | 12       | 6.82%   |
| 3     | 4        | 2.27%   |
| 4     | 1        | 0.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 96       | 43.05%  |
| Intel                           | 82       | 36.77%  |
| Qualcomm Atheros                | 15       | 6.73%   |
| Broadcom                        | 8        | 3.59%   |
| Ralink Technology               | 3        | 1.35%   |
| TP-Link                         | 2        | 0.9%    |
| Nvidia                          | 2        | 0.9%    |
| Microsoft                       | 2        | 0.9%    |
| Mellanox Technologies           | 2        | 0.9%    |
| ZTE WCDMA Technologies MSM      | 1        | 0.45%   |
| Xiaomi                          | 1        | 0.45%   |
| VIA Technologies                | 1        | 0.45%   |
| Ralink                          | 1        | 0.45%   |
| Qualcomm Atheros Communications | 1        | 0.45%   |
| Marvell Technology Group        | 1        | 0.45%   |
| Edimax Technology               | 1        | 0.45%   |
| D-Link                          | 1        | 0.45%   |
| Broadcom Limited                | 1        | 0.45%   |
| Aquantia                        | 1        | 0.45%   |
| American Megatrends             | 1        | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 76       | 30.4%   |
| Intel I211 Gigabit Network Connection                               | 15       | 6%      |
| Intel Ethernet Connection (2) I219-V                                | 12       | 4.8%    |
| Realtek RTL8125 2.5GbE Controller                                   | 10       | 4%      |
| Intel Wi-Fi 6 AX200                                                 | 8        | 3.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 7        | 2.8%    |
| Intel I210 Gigabit Network Connection                               | 6        | 2.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 6        | 2.4%    |
| Intel Ethernet Connection (2) I218-V                                | 4        | 1.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 3        | 1.2%    |
| Intel Ethernet Connection I217-V                                    | 3        | 1.2%    |
| Intel 82574L Gigabit Network Connection                             | 3        | 1.2%    |
| Intel 82567LM-3 Gigabit Network Connection                          | 3        | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.8%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2        | 0.8%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 2        | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2        | 0.8%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.8%    |
| Nvidia MCP61 Ethernet                                               | 2        | 0.8%    |
| Microsoft Xbox 360 Wireless Adapter                                 | 2        | 0.8%    |
| Mellanox MT27500 Family [ConnectX-3]                                | 2        | 0.8%    |
| Intel Wireless 8260                                                 | 2        | 0.8%    |
| Intel Wireless 7260                                                 | 2        | 0.8%    |
| Intel Wireless 3165                                                 | 2        | 0.8%    |
| Intel Ethernet Controller 10G X550T                                 | 2        | 0.8%    |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.8%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                    | 2        | 0.8%    |
| ZTE WCDMA MSM USB SCSI CD-ROM                                       | 1        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.4%    |
| VIA VT6102/VT6103 [Rhine-II]                                        | 1        | 0.4%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                 | 1        | 0.4%    |
| TP-Link Archer T4U ver.3                                            | 1        | 0.4%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.4%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1        | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 1        | 0.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 0.4%    |
| Realtek 802.11ac NIC                                                | 1        | 0.4%    |
| Ralink RT5372 Wireless Adapter                                      | 1        | 0.4%    |
| Ralink RT5370 Wireless Adapter                                      | 1        | 0.4%    |
| Ralink MT7601U Wireless Adapter                                     | 1        | 0.4%    |
| Ralink RT5392 PCIe Wireless Network Adapter                         | 1        | 0.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.4%    |
| Qualcomm Atheros AR9271 802.11n                                     | 1        | 0.4%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                          | 1        | 0.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1        | 0.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 1        | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.4%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 0.4%    |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.4%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                   | 1        | 0.4%    |
| Intel Wireless-AC 9260                                              | 1        | 0.4%    |
| Intel Wireless 8265 / 8275                                          | 1        | 0.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 1        | 0.4%    |
| Intel NM10/ICH7 Family LAN Controller                               | 1        | 0.4%    |
| Intel I350 Gigabit Network Connection                               | 1        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 22       | 44%     |
| Realtek Semiconductor           | 9        | 18%     |
| Qualcomm Atheros                | 5        | 10%     |
| Ralink Technology               | 3        | 6%      |
| Broadcom                        | 3        | 6%      |
| TP-Link                         | 2        | 4%      |
| Microsoft                       | 2        | 4%      |
| Ralink                          | 1        | 2%      |
| Qualcomm Atheros Communications | 1        | 2%      |
| Edimax Technology               | 1        | 2%      |
| D-Link                          | 1        | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 8        | 16%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6        | 12%     |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2        | 4%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2        | 4%      |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2        | 4%      |
| Microsoft Xbox 360 Wireless Adapter                                     | 2        | 4%      |
| Intel Wireless 8260                                                     | 2        | 4%      |
| Intel Wireless 7260                                                     | 2        | 4%      |
| Intel Wireless 3165                                                     | 2        | 4%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1        | 2%      |
| TP-Link Archer T4U ver.3                                                | 1        | 2%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 2%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1        | 2%      |
| Realtek 802.11ac NIC                                                    | 1        | 2%      |
| Ralink RT5372 Wireless Adapter                                          | 1        | 2%      |
| Ralink RT5370 Wireless Adapter                                          | 1        | 2%      |
| Ralink MT7601U Wireless Adapter                                         | 1        | 2%      |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1        | 2%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 2%      |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 2%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 2%      |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1        | 2%      |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1        | 2%      |
| Intel Wireless-AC 9260                                                  | 1        | 2%      |
| Intel Wireless 8265 / 8275                                              | 1        | 2%      |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1        | 2%      |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 2%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1        | 2%      |
| Broadcom BCM43142 802.11b/g/n                                           | 1        | 2%      |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1        | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 92       | 48.68%  |
| Intel                    | 71       | 37.57%  |
| Qualcomm Atheros         | 11       | 5.82%   |
| Broadcom                 | 5        | 2.65%   |
| Nvidia                   | 2        | 1.06%   |
| Mellanox Technologies    | 2        | 1.06%   |
| Xiaomi                   | 1        | 0.53%   |
| VIA Technologies         | 1        | 0.53%   |
| Marvell Technology Group | 1        | 0.53%   |
| Broadcom Limited         | 1        | 0.53%   |
| Aquantia                 | 1        | 0.53%   |
| American Megatrends      | 1        | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76       | 38.19%  |
| Intel I211 Gigabit Network Connection                             | 15       | 7.54%   |
| Intel Ethernet Connection (2) I219-V                              | 12       | 6.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 5.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 3.52%   |
| Intel I210 Gigabit Network Connection                             | 6        | 3.02%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 2.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.51%   |
| Intel Ethernet Connection I217-V                                  | 3        | 1.51%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 1.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 1.01%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 1.01%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 1.01%   |
| Nvidia MCP61 Ethernet                                             | 2        | 1.01%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2        | 1.01%   |
| Intel Ethernet Controller 10G X550T                               | 2        | 1.01%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 1.01%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.5%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.5%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.5%    |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.5%    |
| Intel I350 Gigabit Network Connection                             | 1        | 0.5%    |
| Intel Ethernet Virtual Function 700 Series                        | 1        | 0.5%    |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 0.5%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.5%    |
| Intel Ethernet Connection I354                                    | 1        | 0.5%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.5%    |
| Intel Ethernet Connection (6) I219-V                              | 1        | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.5%    |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.5%    |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.5%    |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.5%    |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.5%    |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.5%    |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 0.5%    |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.5%    |
| Intel 82540EM Gigabit Ethernet Controller                         | 1        | 0.5%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.5%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.5%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 0.5%    |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 1        | 0.5%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.5%    |
| American Megatrends Virtual Ethernet                              | 1        | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 175      | 77.43%  |
| WiFi     | 50       | 22.12%  |
| Modem    | 1        | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 160      | 83.33%  |
| WiFi     | 32       | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 113      | 64.2%   |
| 2     | 50       | 28.41%  |
| 3     | 7        | 3.98%   |
| 4     | 2        | 1.14%   |
| 13    | 1        | 0.57%   |
| 6     | 1        | 0.57%   |
| 5     | 1        | 0.57%   |
| 0     | 1        | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 138      | 78.41%  |
| Yes  | 38       | 21.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 21       | 50%     |
| Cambridge Silicon Radio         | 10       | 23.81%  |
| Broadcom                        | 5        | 11.9%   |
| ASUSTek Computer                | 4        | 9.52%   |
| Realtek Semiconductor           | 1        | 2.38%   |
| Qualcomm Atheros Communications | 1        | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10       | 23.81%  |
| Intel AX200 Bluetooth                               | 8        | 19.05%  |
| Intel Wireless-AC 3168 Bluetooth                    | 5        | 11.9%   |
| Intel Bluetooth wireless interface                  | 3        | 7.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 4.76%   |
| Intel Bluetooth Device                              | 2        | 4.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 4.76%   |
| Realtek Bluetooth Radio                             | 1        | 2.38%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 2.38%   |
| Intel AX210 Bluetooth                               | 1        | 2.38%   |
| Broadcom Bluetooth 3.0 Device                       | 1        | 2.38%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 2.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 2.38%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 2.38%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1        | 2.38%   |
| ASUS Bluetooth Radio                                | 1        | 2.38%   |
| ASUS Bluetooth Adapter                              | 1        | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 90       | 30.82%  |
| AMD                        | 84       | 28.77%  |
| Nvidia                     | 64       | 21.92%  |
| C-Media Electronics        | 11       | 3.77%   |
| Logitech                   | 5        | 1.71%   |
| GYROCOM C&C                | 4        | 1.37%   |
| Creative Labs              | 4        | 1.37%   |
| VIA Technologies           | 3        | 1.03%   |
| Generalplus Technology     | 3        | 1.03%   |
| XMOS                       | 2        | 0.68%   |
| Samson Technologies        | 2        | 0.68%   |
| GN Netcom                  | 2        | 0.68%   |
| BEHRINGER International    | 2        | 0.68%   |
| Unknown                    | 1        | 0.34%   |
| Texas Instruments          | 1        | 0.34%   |
| TEAC                       | 1        | 0.34%   |
| SteelSeries ApS            | 1        | 0.34%   |
| RODE Microphones           | 1        | 0.34%   |
| ROCCAT                     | 1        | 0.34%   |
| PreSonus Audio Electronics | 1        | 0.34%   |
| JMTek                      | 1        | 0.34%   |
| Hangzhou Worlde            | 1        | 0.34%   |
| Dell                       | 1        | 0.34%   |
| Blue Microphones           | 1        | 0.34%   |
| AXELVOX                    | 1        | 0.34%   |
| AVID Technology            | 1        | 0.34%   |
| Audioengine                | 1        | 0.34%   |
| ASUSTek Computer           | 1        | 0.34%   |
| Alesis                     | 1        | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                    | 28       | 8.26%   |
| Intel 200 Series PCH HD Audio                                               | 16       | 4.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 15       | 4.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 15       | 4.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 15       | 4.42%   |
| Nvidia GP107GL High Definition Audio Controller                             | 10       | 2.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 10       | 2.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 9        | 2.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 8        | 2.36%   |
| AMD Navi 10 HDMI Audio                                                      | 8        | 2.36%   |
| AMD FCH Azalia Controller                                                   | 8        | 2.36%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 7        | 2.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 7        | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 7        | 2.06%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                | 7        | 2.06%   |
| Nvidia GP104 High Definition Audio Controller                               | 6        | 1.77%   |
| Intel C600/X79 series chipset High Definition Audio Controller              | 5        | 1.47%   |
| Intel 9 Series Chipset Family HD Audio Controller                           | 5        | 1.47%   |
| AMD Kaveri HDMI/DP Audio Controller                                         | 5        | 1.47%   |
| Intel Comet Lake PCH cAVS                                                   | 4        | 1.18%   |
| Nvidia GP108 High Definition Audio Controller                               | 3        | 0.88%   |
| Nvidia GK104 HDMI Audio Controller                                          | 3        | 0.88%   |
| Intel C610/X99 series chipset HD Audio Controller                           | 3        | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 3        | 0.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 3        | 0.88%   |
| GYROCOM C&C Fiio E10                                                        | 3        | 0.88%   |
| Generalplus Technology Usb Audio Device                                     | 3        | 0.88%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                               | 3        | 0.88%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                         | 3        | 0.88%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                   | 2        | 0.59%   |
| Nvidia TU116 High Definition Audio Controller                               | 2        | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                               | 2        | 0.59%   |
| Nvidia TU104 HD Audio Controller                                            | 2        | 0.59%   |
| Nvidia MCP61 High Definition Audio                                          | 2        | 0.59%   |
| Nvidia High Definition Audio Controller                                     | 2        | 0.59%   |
| Nvidia GM204 High Definition Audio Controller                               | 2        | 0.59%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]               | 2        | 0.59%   |
| Nvidia GK107 HDMI Audio Controller                                          | 2        | 0.59%   |
| Nvidia GK106 HDMI Audio Controller                                          | 2        | 0.59%   |
| Nvidia GF119 HDMI Audio Controller                                          | 2        | 0.59%   |
| Nvidia GF108 High Definition Audio Controller                               | 2        | 0.59%   |
| Nvidia GF104 High Definition Audio Controller                               | 2        | 0.59%   |
| Logitech G430 Surround Sound Gaming Headset                                 | 2        | 0.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 2        | 0.59%   |
| Intel Cannon Lake PCH cAVS                                                  | 2        | 0.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller  | 2        | 0.59%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 2        | 0.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                              | 2        | 0.59%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                          | 2        | 0.59%   |
| C-Media Electronics USB Audio Device                                        | 2        | 0.59%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                  | 2        | 0.59%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]     | 2        | 0.59%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                   | 2        | 0.59%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 2        | 0.59%   |
| XMOS MIYO USB Audio 2.0                                                     | 1        | 0.29%   |
| XMOS HIFI DSD                                                               | 1        | 0.29%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.29%   |
| Unknown USB MIDI Interface                                                  | 1        | 0.29%   |
| Texas Instruments PCM2902 Audio Codec                                       | 1        | 0.29%   |
| TEAC US-2x2                                                                 | 1        | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 40       | 21.74%  |
| Corsair             | 32       | 17.39%  |
| Unknown             | 27       | 14.67%  |
| Samsung Electronics | 19       | 10.33%  |
| G.Skill             | 15       | 8.15%   |
| Crucial             | 14       | 7.61%   |
| SK Hynix            | 13       | 7.07%   |
| Micron Technology   | 5        | 2.72%   |
| Patriot             | 4        | 2.17%   |
| A-DATA Technology   | 3        | 1.63%   |
| Team                | 2        | 1.09%   |
| Kllisre             | 2        | 1.09%   |
| Elpida              | 2        | 1.09%   |
| V-Color             | 1        | 0.54%   |
| Unknown (ABCD)      | 1        | 0.54%   |
| Kingmax             | 1        | 0.54%   |
| KETECH              | 1        | 0.54%   |
| GOODRAM             | 1        | 0.54%   |
| GeIL                | 1        | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 5        | 2.35%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s            | 4        | 1.88%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s             | 4        | 1.88%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                 | 3        | 1.41%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s               | 3        | 1.41%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s             | 3        | 1.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s          | 3        | 1.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                         | 2        | 0.94%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 2        | 0.94%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 2        | 0.94%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                          | 2        | 0.94%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                        | 2        | 0.94%   |
| Unknown RAM 99[2/7/4]164(F/R) 4GB DIMM DDR3 1600MT/s              | 2        | 0.94%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s               | 2        | 0.94%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s                | 2        | 0.94%   |
| Kingston RAM KHX2666C16/8G 8192MB DIMM DDR4 3200MT/s              | 2        | 0.94%   |
| Kingston RAM KHX2133C14D4/8G 8192MB DIMM DDR4 2667MT/s            | 2        | 0.94%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1867MT/s               | 2        | 0.94%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s               | 2        | 0.94%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s            | 2        | 0.94%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s            | 2        | 0.94%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s             | 2        | 0.94%   |
| Corsair RAM CMK32GX4M2A2666C16 16384MB DIMM DDR4 3100MT/s         | 2        | 0.94%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s             | 2        | 0.94%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s                  | 1        | 0.47%   |
| Unknown RAM V02D4LF8GB5285282400 8192MB DIMM DDR4 2400MT/s        | 1        | 0.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1        | 0.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 1        | 0.47%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 1        | 0.47%   |
| Unknown RAM Module 512MB DIMM SDRAM 400MT/s                       | 1        | 0.47%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                        | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM 800MT/s                               | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM 400MT/s                               | 1        | 0.47%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s                        | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM 800MT/s                               | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM 400MT/s                               | 1        | 0.47%   |
| Unknown RAM Module 256MB DIMM SDRAM 400MT/s                       | 1        | 0.47%   |
| Unknown RAM Module 256MB DIMM                                     | 1        | 0.47%   |
| Unknown RAM Module 1GB DIMM SDRAM                                 | 1        | 0.47%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                          | 1        | 0.47%   |
| Unknown RAM Module 1GB DIMM                                       | 1        | 0.47%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                        | 1        | 0.47%   |
| Unknown RAM 7EH64AA# 8GB DIMM DDR4 2667MT/s                       | 1        | 0.47%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s             | 1        | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2133MT/s | 1        | 0.47%   |
| Team RAM TEAMGROUP-UD3-1333 8GB DIMM DDR3 1333MT/s                | 1        | 0.47%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                        | 1        | 0.47%   |
| SK Hynix RAM S949A4UUH-ITR 16GB DIMM DDR4 2400MT/s                | 1        | 0.47%   |
| SK Hynix RAM HYMP512U64CP8-S5 1GB DIMM DDR2 400MT/s               | 1        | 0.47%   |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 400MT/s               | 1        | 0.47%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1        | 0.47%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1        | 0.47%   |
| SK Hynix RAM HMT41GE7BFR8A-PB 8GB DIMM DDR3 1600MT/s              | 1        | 0.47%   |
| SK Hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 1333MT/s                 | 1        | 0.47%   |
| SK Hynix RAM HMT325U7CFR8A-H9 2GB DIMM DDR3 1333MT/s              | 1        | 0.47%   |
| SK Hynix RAM HMT31GR7BFR4A-H9 8GB DIMM DDR3 1333MT/s              | 1        | 0.47%   |
| SK Hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1        | 0.47%   |
| SK Hynix RAM HMT125U6TFR8C-G7 2GB DIMM DDR3 1067MT/s              | 1        | 0.47%   |
| SK Hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s              | 1        | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 82       | 50%     |
| DDR3    | 58       | 35.37%  |
| Unknown | 10       | 6.1%    |
| SDRAM   | 7        | 4.27%   |
| DDR2    | 6        | 3.66%   |
| LPDDR4  | 1        | 0.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 157      | 96.32%  |
| SODIMM | 5        | 3.07%   |
| RIMM   | 1        | 0.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 75       | 41.44%  |
| 4096  | 36       | 19.89%  |
| 16384 | 29       | 16.02%  |
| 2048  | 17       | 9.39%   |
| 32768 | 10       | 5.52%   |
| 1024  | 8        | 4.42%   |
| 512   | 3        | 1.66%   |
| 256   | 2        | 1.1%    |
| 65536 | 1        | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 39       | 20.86%  |
| 1333    | 24       | 12.83%  |
| 3200    | 21       | 11.23%  |
| 2667    | 15       | 8.02%   |
| 2400    | 13       | 6.95%   |
| 3600    | 12       | 6.42%   |
| 2933    | 6        | 3.21%   |
| 1866    | 6        | 3.21%   |
| 800     | 6        | 3.21%   |
| 2133    | 5        | 2.67%   |
| 3466    | 4        | 2.14%   |
| 2666    | 4        | 2.14%   |
| 1867    | 4        | 2.14%   |
| Unknown | 4        | 2.14%   |
| 3000    | 3        | 1.6%    |
| 667     | 3        | 1.6%    |
| 400     | 3        | 1.6%    |
| 3500    | 2        | 1.07%   |
| 3400    | 2        | 1.07%   |
| 3100    | 2        | 1.07%   |
| 1067    | 2        | 1.07%   |
| 3533    | 1        | 0.53%   |
| 3066    | 1        | 0.53%   |
| 2866    | 1        | 0.53%   |
| 2465    | 1        | 0.53%   |
| 2000    | 1        | 0.53%   |
| 1800    | 1        | 0.53%   |
| 1367    | 1        | 0.53%   |

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
| Logitech                      | 13       | 35.14%  |
| Microdia                      | 5        | 13.51%  |
| Samsung Electronics           | 3        | 8.11%   |
| Genesys Logic                 | 2        | 5.41%   |
| Generalplus Technology        | 2        | 5.41%   |
| Z-Star Microelectronics       | 1        | 2.7%    |
| Xiongmai                      | 1        | 2.7%    |
| Sunplus Innovation Technology | 1        | 2.7%    |
| SiGma Micro                   | 1        | 2.7%    |
| Razer USA                     | 1        | 2.7%    |
| Lenovo                        | 1        | 2.7%    |
| Jieli Technology              | 1        | 2.7%    |
| Huawei Technologies           | 1        | 2.7%    |
| Hewlett-Packard               | 1        | 2.7%    |
| eMPIA Technology              | 1        | 2.7%    |
| AVerMedia Technologies        | 1        | 2.7%    |
| ARC International             | 1        | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)             | 3        | 8.11%   |
| Microdia Webcam Vitade AF           | 3        | 8.11%   |
| Logitech Webcam C270                | 3        | 8.11%   |
| Logitech HD Pro Webcam C920         | 3        | 8.11%   |
| Logitech HD Webcam C910             | 2        | 5.41%   |
| Logitech HD Webcam C615             | 2        | 5.41%   |
| Z-Star Venus USB2.0 Camera          | 1        | 2.7%    |
| Xiongmai web camera                 | 1        | 2.7%    |
| Sunplus HD USB Camaer 4K            | 1        | 2.7%    |
| SiGma Micro WebCam SiGma Micro      | 1        | 2.7%    |
| Razer USA Razer Kiyo                | 1        | 2.7%    |
| Microdia USB Live camera            | 1        | 2.7%    |
| Microdia Integrated Camera          | 1        | 2.7%    |
| Logitech Webcam C260                | 1        | 2.7%    |
| Logitech Quickcam 3000 For Business | 1        | 2.7%    |
| Logitech BRIO                       | 1        | 2.7%    |
| Lenovo FHD Webcam                   | 1        | 2.7%    |
| Jieli USB PHY 2.0                   | 1        | 2.7%    |
| Huawei UVC Camera                   | 1        | 2.7%    |
| HP Webcam 3110                      | 1        | 2.7%    |
| Genesys Logic USB2.0 Digital Camera | 1        | 2.7%    |
| Genesys Logic Camera                | 1        | 2.7%    |
| Generalplus GENERAL WEBCAM          | 1        | 2.7%    |
| Generalplus 808 Camera              | 1        | 2.7%    |
| eMPIA M035 Compact Web Cam          | 1        | 2.7%    |
| AVerMedia Live Gamer Ultra-Video    | 1        | 2.7%    |
| ARC International Camera            | 1        | 2.7%    |

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
| 0     | 159      | 90.34%  |
| 1     | 15       | 8.52%   |
| 5     | 1        | 0.57%   |
| 2     | 1        | 0.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 8        | 47.06%  |
| Unassigned class         | 3        | 17.65%  |
| Communication controller | 2        | 11.76%  |
| Sound                    | 1        | 5.88%   |
| Network                  | 1        | 5.88%   |
| Net/wireless             | 1        | 5.88%   |
| Multimedia controller    | 1        | 5.88%   |

