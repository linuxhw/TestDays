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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z97N-WIFI                   | [be9383850e](https://linux-hardware.org/?probe=be9383850e) | Aug 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [7911fbd6a6](https://linux-hardware.org/?probe=7911fbd6a6) | Aug 17, 2021 |
| MSI           | FM2-A55M-E33                | [6972c43e80](https://linux-hardware.org/?probe=6972c43e80) | Aug 17, 2021 |
| ASUSTek       | P5KC                        | [5e2f61d652](https://linux-hardware.org/?probe=5e2f61d652) | Aug 16, 2021 |
| Intel         | DN2820FYK H24582-201        | [86cf4755a0](https://linux-hardware.org/?probe=86cf4755a0) | Aug 16, 2021 |
| ASRock        | B460 Phantom Gaming 4       | [51f9388874](https://linux-hardware.org/?probe=51f9388874) | Aug 15, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [88160f850f](https://linux-hardware.org/?probe=88160f850f) | Aug 15, 2021 |
| ASUSTek       | M5A99X EVO                  | [53aff8d681](https://linux-hardware.org/?probe=53aff8d681) | Aug 15, 2021 |
| ECS           | KBN-I                       | [bbfe1ba1a2](https://linux-hardware.org/?probe=bbfe1ba1a2) | Aug 15, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [987ab1f3bf](https://linux-hardware.org/?probe=987ab1f3bf) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | [a6e0859eac](https://linux-hardware.org/?probe=a6e0859eac) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | [5ce5d800d3](https://linux-hardware.org/?probe=5ce5d800d3) | Aug 14, 2021 |
| ASUSTek       | PRIME Z390-P                | [dfe51161fe](https://linux-hardware.org/?probe=dfe51161fe) | Aug 14, 2021 |
| ASRock        | Z97 Pro3                    | [0e5746a060](https://linux-hardware.org/?probe=0e5746a060) | Aug 14, 2021 |
| Dell          | 0X9M3X A01                  | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| HP            | 3397                        | [a3425b956c](https://linux-hardware.org/?probe=a3425b956c) | Aug 14, 2021 |
| ASUSTek       | X99-DELUXE                  | [f59179a579](https://linux-hardware.org/?probe=f59179a579) | Aug 13, 2021 |
| ASUSTek       | Z170-PRO                    | [7f9b5606a5](https://linux-hardware.org/?probe=7f9b5606a5) | Aug 13, 2021 |
| HP            | 3048h                       | [894950911f](https://linux-hardware.org/?probe=894950911f) | Aug 11, 2021 |
| Gigabyte      | 970A-DS3P                   | [9b62457757](https://linux-hardware.org/?probe=9b62457757) | Aug 11, 2021 |
| ASUSTek       | PRIME A320M-K               | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [78223998b6](https://linux-hardware.org/?probe=78223998b6) | Aug 10, 2021 |
| MSI           | B250M PRO-VDH               | [d6be998202](https://linux-hardware.org/?probe=d6be998202) | Aug 10, 2021 |
| ASUSTek       | PRIME A320M-K               | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Dell          | 04MFRM A01                  | [c0094def97](https://linux-hardware.org/?probe=c0094def97) | Aug 09, 2021 |
| MSI           | B450 TOMAHAWK               | [58b4f52cc0](https://linux-hardware.org/?probe=58b4f52cc0) | Aug 09, 2021 |
| Gigabyte      | H470M DS3H                  | [29de4693d8](https://linux-hardware.org/?probe=29de4693d8) | Aug 09, 2021 |
| ASRock        | 970A-G                      | [f1e9959894](https://linux-hardware.org/?probe=f1e9959894) | Aug 09, 2021 |
| Toshiba       | STI 910090 STIJ             | [389ebd7675](https://linux-hardware.org/?probe=389ebd7675) | Aug 08, 2021 |
| ASRock        | X370 Killer SLI             | [8a0885afb6](https://linux-hardware.org/?probe=8a0885afb6) | Aug 08, 2021 |
| MSI           | Z490-A PRO                  | [eac37d633f](https://linux-hardware.org/?probe=eac37d633f) | Aug 08, 2021 |
| ASRock        | Z97 Pro4                    | [090d12a96f](https://linux-hardware.org/?probe=090d12a96f) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [39eb5a1578](https://linux-hardware.org/?probe=39eb5a1578) | Aug 08, 2021 |
| Toshiba       | STI 005038 G31T-M7          | [faa8f15725](https://linux-hardware.org/?probe=faa8f15725) | Aug 08, 2021 |
| Gigabyte      | Z77-D3H                     | [9dafe47483](https://linux-hardware.org/?probe=9dafe47483) | Aug 07, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [da833ac33e](https://linux-hardware.org/?probe=da833ac33e) | Aug 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [80c7711147](https://linux-hardware.org/?probe=80c7711147) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | [4ff5966d22](https://linux-hardware.org/?probe=4ff5966d22) | Aug 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | [5839492cd8](https://linux-hardware.org/?probe=5839492cd8) | Aug 07, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [733a3e325c](https://linux-hardware.org/?probe=733a3e325c) | Aug 07, 2021 |
| Dell          | 08WKV3 A01                  | [8ab0ff9442](https://linux-hardware.org/?probe=8ab0ff9442) | Aug 07, 2021 |
| MSI           | MEG X399 CREATION           | [7cada9aaed](https://linux-hardware.org/?probe=7cada9aaed) | Aug 07, 2021 |
| MSI           | B250M PRO-VDH               | [187e4dd872](https://linux-hardware.org/?probe=187e4dd872) | Aug 07, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [31d159af99](https://linux-hardware.org/?probe=31d159af99) | Aug 06, 2021 |
| Lenovo        | Board                       | [18138486db](https://linux-hardware.org/?probe=18138486db) | Aug 05, 2021 |
| Intel         | DN2820FYK H24582-201        | [7caf949908](https://linux-hardware.org/?probe=7caf949908) | Aug 05, 2021 |
| Unknown       | Intel X79                   | [fc0dedbb3c](https://linux-hardware.org/?probe=fc0dedbb3c) | Aug 05, 2021 |
| AMD           | 970A-D3                     | [91825066e0](https://linux-hardware.org/?probe=91825066e0) | Aug 04, 2021 |
| HP            | 3047h                       | [6294617672](https://linux-hardware.org/?probe=6294617672) | Aug 03, 2021 |
| ASRock        | FM2A68M-HD+                 | [a7bdbd8ebe](https://linux-hardware.org/?probe=a7bdbd8ebe) | Aug 03, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [55cd593df1](https://linux-hardware.org/?probe=55cd593df1) | Aug 03, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| MSI           | 760GM-P23                   | [93b6f212af](https://linux-hardware.org/?probe=93b6f212af) | Aug 02, 2021 |
| Supermicro    | X11SSH-F                    | [641e4fd8ce](https://linux-hardware.org/?probe=641e4fd8ce) | Aug 02, 2021 |
| ASRock        | H310CM-DVS                  | [f84e5eba5a](https://linux-hardware.org/?probe=f84e5eba5a) | Aug 02, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [e90a873ad0](https://linux-hardware.org/?probe=e90a873ad0) | Aug 02, 2021 |
| ASUSTek       | P5QL-E                      | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| ASUSTek       | A88X-PRO                    | [ed95430eec](https://linux-hardware.org/?probe=ed95430eec) | Aug 02, 2021 |
| HP            | 2187 A01                    | [16bfdd86e3](https://linux-hardware.org/?probe=16bfdd86e3) | Aug 02, 2021 |
| Gigabyte      | 970A-DS3P                   | [61886d812f](https://linux-hardware.org/?probe=61886d812f) | Aug 01, 2021 |
| ASRock        | J1900D2Y                    | [0dc4afc8c4](https://linux-hardware.org/?probe=0dc4afc8c4) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| Dell          | 0WVYMC A00                  | [4d2aa42e3c](https://linux-hardware.org/?probe=4d2aa42e3c) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [159ff0ba7f](https://linux-hardware.org/?probe=159ff0ba7f) | Jul 31, 2021 |
| ASRock        | Z370M-ITX/ac                | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [3f0c3901f6](https://linux-hardware.org/?probe=3f0c3901f6) | Jul 30, 2021 |
| MSI           | Z490-A PRO                  | [b882a9cf0d](https://linux-hardware.org/?probe=b882a9cf0d) | Jul 29, 2021 |
| MSI           | Q45MDO                      | [ab547f0047](https://linux-hardware.org/?probe=ab547f0047) | Jul 29, 2021 |
| MSI           | Q45MDO                      | [6b5aaa6969](https://linux-hardware.org/?probe=6b5aaa6969) | Jul 29, 2021 |
| Dell          | 0TY915                      | [9cb5aed659](https://linux-hardware.org/?probe=9cb5aed659) | Jul 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| ASUSTek       | LEONITE                     | [3bf9048839](https://linux-hardware.org/?probe=3bf9048839) | Jul 29, 2021 |
| Foxconn       | 2AA9                        | [920a813aaf](https://linux-hardware.org/?probe=920a813aaf) | Jul 29, 2021 |
| ASRock        | B85M Pro4                   | [32e615b538](https://linux-hardware.org/?probe=32e615b538) | Jul 29, 2021 |
| ASRock        | FM2A88X Extreme6+           | [f449b8ce85](https://linux-hardware.org/?probe=f449b8ce85) | Jul 29, 2021 |
| ECS           | H61H2-M12                   | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| MSI           | B450M PRO-VDH PLUS          | [cccaebb483](https://linux-hardware.org/?probe=cccaebb483) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f96bcc3ab2](https://linux-hardware.org/?probe=f96bcc3ab2) | Jul 28, 2021 |
| Shuttle       | FX79R                       | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| ASRockRack    | X570D4U-2L2T                | [7bb34c9dec](https://linux-hardware.org/?probe=7bb34c9dec) | Jul 27, 2021 |
| ASUSTek       | A88X-PLUS/USB               | [57b54cc925](https://linux-hardware.org/?probe=57b54cc925) | Jul 27, 2021 |
| ASRock        | N68C-GS FX                  | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| ASUSTek       | PRIME Z490-P                | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| Dell          | 0X8DXD A00                  | [7821dfc370](https://linux-hardware.org/?probe=7821dfc370) | Jul 27, 2021 |
| ASUSTek       | M4A785D-M PRO               | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| Foxconn       | 915MH Series                | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [dc4a709a3b](https://linux-hardware.org/?probe=dc4a709a3b) | Jul 27, 2021 |
| Dell          | 0WMJ54 A01                  | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [1e69873301](https://linux-hardware.org/?probe=1e69873301) | Jul 27, 2021 |
| Dell          | 0M863N A00                  | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| ASRock        | Z97 Pro3                    | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| MSI           | Z370 SLI PLUS               | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock        | B450 Pro4                   | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP            | 2B38                        | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | 970 Pro3 R2.0               | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASRock        | X570 Steel Legend           | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell          | 0D28YY A02                  | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock        | H470M-ITX/ac                | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Gigabyte      | H110M-S2H-CF                | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell          | 0PTTT9 A00                  | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte      | Z170M-D3H-CF                | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| ASRock        | P67 Pro3                    | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte      | H87-HD3                     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| Dell          | 0Y1057                      | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP            | 1495                        | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| HP            | 158A                        | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| HP            | 158A                        | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP            | 2129                        | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Protectli     | FW6                         | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| HP            | ProLiant MicroServer        | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| MSI           | A68HM-E33 V2                | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Huanan        | X99-F8 V2.0                 | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| HP            | 2215                        | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| MSI           | MS-6712                     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| ASRock        | H77 Pro4-M                  | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| Gigabyte      | AX370-Gaming K7             | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| MSI           | B85M-G43                    | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| Huanan        | X99-8M-F V1.1               | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| MSI           | B450M MORTAR MAX            | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| ASUSTek       | PRIME B450M-A               | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| Dell          | 0Y7WYT A00                  | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| ASRock        | B450M Pro4                  | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| ASUSTek       | PRIME A320M-K               | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| ASRock        | B450M Pro4                  | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| ASUSTek       | M4A88T-M/USB3               | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Dell          | 0YXT71 A02                  | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| ASUSTek       | P5B-Deluxe                  | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI           | B250M BAZOOKA               | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| MSI           | B450I GAMING PLUS AC        | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Gigabyte      | Z170X-GamingG1              | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| Gigabyte      | Z77-D3H                     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Lenovo        | MAHOBAY                     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| Biostar       | B450MH                      | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| Gigabyte      | EG41MF-US2H                 | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |

Test Cases
----------

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z97N-WIFI                   | [be9383850e](https://linux-hardware.org/?probe=be9383850e) | Aug 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [7911fbd6a6](https://linux-hardware.org/?probe=7911fbd6a6) | Aug 17, 2021 |
| MSI           | FM2-A55M-E33                | [6972c43e80](https://linux-hardware.org/?probe=6972c43e80) | Aug 17, 2021 |
| ASUSTek       | P5KC                        | [5e2f61d652](https://linux-hardware.org/?probe=5e2f61d652) | Aug 16, 2021 |
| Intel         | DN2820FYK H24582-201        | [86cf4755a0](https://linux-hardware.org/?probe=86cf4755a0) | Aug 16, 2021 |
| ASRock        | B460 Phantom Gaming 4       | [51f9388874](https://linux-hardware.org/?probe=51f9388874) | Aug 15, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [88160f850f](https://linux-hardware.org/?probe=88160f850f) | Aug 15, 2021 |
| ASUSTek       | M5A99X EVO                  | [53aff8d681](https://linux-hardware.org/?probe=53aff8d681) | Aug 15, 2021 |
| ECS           | KBN-I                       | [bbfe1ba1a2](https://linux-hardware.org/?probe=bbfe1ba1a2) | Aug 15, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [987ab1f3bf](https://linux-hardware.org/?probe=987ab1f3bf) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | [a6e0859eac](https://linux-hardware.org/?probe=a6e0859eac) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | [5ce5d800d3](https://linux-hardware.org/?probe=5ce5d800d3) | Aug 14, 2021 |
| ASUSTek       | PRIME Z390-P                | [dfe51161fe](https://linux-hardware.org/?probe=dfe51161fe) | Aug 14, 2021 |
| ASRock        | Z97 Pro3                    | [0e5746a060](https://linux-hardware.org/?probe=0e5746a060) | Aug 14, 2021 |
| Dell          | 0X9M3X A01                  | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| HP            | 3397                        | [a3425b956c](https://linux-hardware.org/?probe=a3425b956c) | Aug 14, 2021 |
| ASUSTek       | X99-DELUXE                  | [f59179a579](https://linux-hardware.org/?probe=f59179a579) | Aug 13, 2021 |
| ASUSTek       | Z170-PRO                    | [7f9b5606a5](https://linux-hardware.org/?probe=7f9b5606a5) | Aug 13, 2021 |
| HP            | 3048h                       | [894950911f](https://linux-hardware.org/?probe=894950911f) | Aug 11, 2021 |
| Gigabyte      | 970A-DS3P                   | [9b62457757](https://linux-hardware.org/?probe=9b62457757) | Aug 11, 2021 |
| ASUSTek       | PRIME A320M-K               | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [78223998b6](https://linux-hardware.org/?probe=78223998b6) | Aug 10, 2021 |
| MSI           | B250M PRO-VDH               | [d6be998202](https://linux-hardware.org/?probe=d6be998202) | Aug 10, 2021 |
| ASUSTek       | PRIME A320M-K               | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Dell          | 04MFRM A01                  | [c0094def97](https://linux-hardware.org/?probe=c0094def97) | Aug 09, 2021 |
| MSI           | B450 TOMAHAWK               | [58b4f52cc0](https://linux-hardware.org/?probe=58b4f52cc0) | Aug 09, 2021 |
| Gigabyte      | H470M DS3H                  | [29de4693d8](https://linux-hardware.org/?probe=29de4693d8) | Aug 09, 2021 |
| ASRock        | 970A-G                      | [f1e9959894](https://linux-hardware.org/?probe=f1e9959894) | Aug 09, 2021 |
| Toshiba       | STI 910090 STIJ             | [389ebd7675](https://linux-hardware.org/?probe=389ebd7675) | Aug 08, 2021 |
| ASRock        | X370 Killer SLI             | [8a0885afb6](https://linux-hardware.org/?probe=8a0885afb6) | Aug 08, 2021 |
| MSI           | Z490-A PRO                  | [eac37d633f](https://linux-hardware.org/?probe=eac37d633f) | Aug 08, 2021 |
| ASRock        | Z97 Pro4                    | [090d12a96f](https://linux-hardware.org/?probe=090d12a96f) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [39eb5a1578](https://linux-hardware.org/?probe=39eb5a1578) | Aug 08, 2021 |
| Toshiba       | STI 005038 G31T-M7          | [faa8f15725](https://linux-hardware.org/?probe=faa8f15725) | Aug 08, 2021 |
| Gigabyte      | Z77-D3H                     | [9dafe47483](https://linux-hardware.org/?probe=9dafe47483) | Aug 07, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [da833ac33e](https://linux-hardware.org/?probe=da833ac33e) | Aug 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [80c7711147](https://linux-hardware.org/?probe=80c7711147) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | [4ff5966d22](https://linux-hardware.org/?probe=4ff5966d22) | Aug 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | [5839492cd8](https://linux-hardware.org/?probe=5839492cd8) | Aug 07, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [733a3e325c](https://linux-hardware.org/?probe=733a3e325c) | Aug 07, 2021 |
| Dell          | 08WKV3 A01                  | [8ab0ff9442](https://linux-hardware.org/?probe=8ab0ff9442) | Aug 07, 2021 |
| MSI           | MEG X399 CREATION           | [7cada9aaed](https://linux-hardware.org/?probe=7cada9aaed) | Aug 07, 2021 |
| MSI           | B250M PRO-VDH               | [187e4dd872](https://linux-hardware.org/?probe=187e4dd872) | Aug 07, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [31d159af99](https://linux-hardware.org/?probe=31d159af99) | Aug 06, 2021 |
| Lenovo        | Board                       | [18138486db](https://linux-hardware.org/?probe=18138486db) | Aug 05, 2021 |
| Intel         | DN2820FYK H24582-201        | [7caf949908](https://linux-hardware.org/?probe=7caf949908) | Aug 05, 2021 |
| Unknown       | Intel X79                   | [fc0dedbb3c](https://linux-hardware.org/?probe=fc0dedbb3c) | Aug 05, 2021 |
| AMD           | 970A-D3                     | [91825066e0](https://linux-hardware.org/?probe=91825066e0) | Aug 04, 2021 |
| HP            | 3047h                       | [6294617672](https://linux-hardware.org/?probe=6294617672) | Aug 03, 2021 |
| ASRock        | FM2A68M-HD+                 | [a7bdbd8ebe](https://linux-hardware.org/?probe=a7bdbd8ebe) | Aug 03, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [55cd593df1](https://linux-hardware.org/?probe=55cd593df1) | Aug 03, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| MSI           | 760GM-P23                   | [93b6f212af](https://linux-hardware.org/?probe=93b6f212af) | Aug 02, 2021 |
| Supermicro    | X11SSH-F                    | [641e4fd8ce](https://linux-hardware.org/?probe=641e4fd8ce) | Aug 02, 2021 |
| ASRock        | H310CM-DVS                  | [f84e5eba5a](https://linux-hardware.org/?probe=f84e5eba5a) | Aug 02, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [e90a873ad0](https://linux-hardware.org/?probe=e90a873ad0) | Aug 02, 2021 |
| ASUSTek       | P5QL-E                      | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| ASUSTek       | A88X-PRO                    | [ed95430eec](https://linux-hardware.org/?probe=ed95430eec) | Aug 02, 2021 |
| HP            | 2187 A01                    | [16bfdd86e3](https://linux-hardware.org/?probe=16bfdd86e3) | Aug 02, 2021 |
| Gigabyte      | 970A-DS3P                   | [61886d812f](https://linux-hardware.org/?probe=61886d812f) | Aug 01, 2021 |
| ASRock        | J1900D2Y                    | [0dc4afc8c4](https://linux-hardware.org/?probe=0dc4afc8c4) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| Dell          | 0WVYMC A00                  | [4d2aa42e3c](https://linux-hardware.org/?probe=4d2aa42e3c) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [159ff0ba7f](https://linux-hardware.org/?probe=159ff0ba7f) | Jul 31, 2021 |
| ASRock        | Z370M-ITX/ac                | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [3f0c3901f6](https://linux-hardware.org/?probe=3f0c3901f6) | Jul 30, 2021 |
| MSI           | Z490-A PRO                  | [b882a9cf0d](https://linux-hardware.org/?probe=b882a9cf0d) | Jul 29, 2021 |
| MSI           | Q45MDO                      | [ab547f0047](https://linux-hardware.org/?probe=ab547f0047) | Jul 29, 2021 |
| MSI           | Q45MDO                      | [6b5aaa6969](https://linux-hardware.org/?probe=6b5aaa6969) | Jul 29, 2021 |
| Dell          | 0TY915                      | [9cb5aed659](https://linux-hardware.org/?probe=9cb5aed659) | Jul 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| ASUSTek       | LEONITE                     | [3bf9048839](https://linux-hardware.org/?probe=3bf9048839) | Jul 29, 2021 |
| Foxconn       | 2AA9                        | [920a813aaf](https://linux-hardware.org/?probe=920a813aaf) | Jul 29, 2021 |
| ASRock        | B85M Pro4                   | [32e615b538](https://linux-hardware.org/?probe=32e615b538) | Jul 29, 2021 |
| ASRock        | FM2A88X Extreme6+           | [f449b8ce85](https://linux-hardware.org/?probe=f449b8ce85) | Jul 29, 2021 |
| ECS           | H61H2-M12                   | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| MSI           | B450M PRO-VDH PLUS          | [cccaebb483](https://linux-hardware.org/?probe=cccaebb483) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f96bcc3ab2](https://linux-hardware.org/?probe=f96bcc3ab2) | Jul 28, 2021 |
| Shuttle       | FX79R                       | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| ASRockRack    | X570D4U-2L2T                | [7bb34c9dec](https://linux-hardware.org/?probe=7bb34c9dec) | Jul 27, 2021 |
| ASUSTek       | A88X-PLUS/USB               | [57b54cc925](https://linux-hardware.org/?probe=57b54cc925) | Jul 27, 2021 |
| ASRock        | N68C-GS FX                  | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| ASUSTek       | PRIME Z490-P                | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| Dell          | 0X8DXD A00                  | [7821dfc370](https://linux-hardware.org/?probe=7821dfc370) | Jul 27, 2021 |
| ASUSTek       | M4A785D-M PRO               | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| Foxconn       | 915MH Series                | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [dc4a709a3b](https://linux-hardware.org/?probe=dc4a709a3b) | Jul 27, 2021 |
| Dell          | 0WMJ54 A01                  | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [1e69873301](https://linux-hardware.org/?probe=1e69873301) | Jul 27, 2021 |
| Dell          | 0M863N A00                  | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| ASRock        | Z97 Pro3                    | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| MSI           | Z370 SLI PLUS               | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock        | B450 Pro4                   | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP            | 2B38                        | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | 970 Pro3 R2.0               | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASRock        | X570 Steel Legend           | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell          | 0D28YY A02                  | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock        | H470M-ITX/ac                | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Gigabyte      | H110M-S2H-CF                | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell          | 0PTTT9 A00                  | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte      | Z170M-D3H-CF                | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| ASRock        | P67 Pro3                    | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte      | H87-HD3                     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| Dell          | 0Y1057                      | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP            | 1495                        | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| HP            | 158A                        | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| HP            | 158A                        | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP            | 2129                        | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Protectli     | FW6                         | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| HP            | ProLiant MicroServer        | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| MSI           | A68HM-E33 V2                | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Huanan        | X99-F8 V2.0                 | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| HP            | 2215                        | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| MSI           | MS-6712                     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| ASRock        | H77 Pro4-M                  | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| Gigabyte      | AX370-Gaming K7             | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| MSI           | B85M-G43                    | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| Huanan        | X99-8M-F V1.1               | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| MSI           | B450M MORTAR MAX            | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| ASUSTek       | PRIME B450M-A               | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| Dell          | 0Y7WYT A00                  | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| ASRock        | B450M Pro4                  | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| ASUSTek       | PRIME A320M-K               | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| ASRock        | B450M Pro4                  | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| ASUSTek       | M4A88T-M/USB3               | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Dell          | 0YXT71 A02                  | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| ASUSTek       | P5B-Deluxe                  | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI           | B250M BAZOOKA               | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| MSI           | B450I GAMING PLUS AC        | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Gigabyte      | Z170X-GamingG1              | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| Gigabyte      | Z77-D3H                     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Lenovo        | MAHOBAY                     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| Biostar       | B450MH                      | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| Gigabyte      | EG41MF-US2H                 | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.10.0-8-amd64                 | 118      | 61.14%  |
| 5.10.0-7-amd64                 | 44       | 22.8%   |
| 5.10.0-6-amd64                 | 9        | 4.66%   |
| 5.11.22-1-pve                  | 3        | 1.55%   |
| 5.10.0-8-rt-amd64              | 2        | 1.04%   |
| 5.10.0-8-686-pae               | 2        | 1.04%   |
| 5.8.0-3-amd64                  | 1        | 0.52%   |
| 5.13.8-gnu                     | 1        | 0.52%   |
| 5.13.4                         | 1        | 0.52%   |
| 5.13.1a                        | 1        | 0.52%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1        | 0.52%   |
| 5.11.22-2-pve                  | 1        | 0.52%   |
| 5.11.0-21.1-liquorix-amd64     | 1        | 0.52%   |
| 5.11.0-16.1-liquorix-amd64     | 1        | 0.52%   |
| 5.10.46custom                  | 1        | 0.52%   |
| 5.10.42+truenas                | 1        | 0.52%   |
| 5.10.38-falcot                 | 1        | 0.52%   |
| 5.10.0-8-686                   | 1        | 0.52%   |
| 5.10.0-7-686-pae               | 1        | 0.52%   |
| 5.10.0-3-amd64                 | 1        | 0.52%   |
| 5.10.0-2-amd64                 | 1        | 0.52%   |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.10.0-8-amd64                 | 118      | 61.14%  |
| 5.10.0-7-amd64                 | 44       | 22.8%   |
| 5.10.0-6-amd64                 | 9        | 4.66%   |
| 5.11.22-1-pve                  | 3        | 1.55%   |
| 5.10.0-8-rt-amd64              | 2        | 1.04%   |
| 5.10.0-8-686-pae               | 2        | 1.04%   |
| 5.8.0-3-amd64                  | 1        | 0.52%   |
| 5.13.8-gnu                     | 1        | 0.52%   |
| 5.13.4                         | 1        | 0.52%   |
| 5.13.1a                        | 1        | 0.52%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1        | 0.52%   |
| 5.11.22-2-pve                  | 1        | 0.52%   |
| 5.11.0-21.1-liquorix-amd64     | 1        | 0.52%   |
| 5.11.0-16.1-liquorix-amd64     | 1        | 0.52%   |
| 5.10.46custom                  | 1        | 0.52%   |
| 5.10.42+truenas                | 1        | 0.52%   |
| 5.10.38-falcot                 | 1        | 0.52%   |
| 5.10.0-8-686                   | 1        | 0.52%   |
| 5.10.0-7-686-pae               | 1        | 0.52%   |
| 5.10.0-3-amd64                 | 1        | 0.52%   |
| 5.10.0-2-amd64                 | 1        | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 176      | 92.63%  |
| 5.11.22 | 4        | 2.11%   |
| 5.11.0  | 2        | 1.05%   |
| 5.8.0   | 1        | 0.53%   |
| 5.13.8  | 1        | 0.53%   |
| 5.13.4  | 1        | 0.53%   |
| 5.13.1  | 1        | 0.53%   |
| 5.13.0  | 1        | 0.53%   |
| 5.10.46 | 1        | 0.53%   |
| 5.10.42 | 1        | 0.53%   |
| 5.10.38 | 1        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 176      | 92.63%  |
| 5.11.22 | 4        | 2.11%   |
| 5.11.0  | 2        | 1.05%   |
| 5.8.0   | 1        | 0.53%   |
| 5.13.8  | 1        | 0.53%   |
| 5.13.4  | 1        | 0.53%   |
| 5.13.1  | 1        | 0.53%   |
| 5.13.0  | 1        | 0.53%   |
| 5.10.46 | 1        | 0.53%   |
| 5.10.42 | 1        | 0.53%   |
| 5.10.38 | 1        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 179      | 94.21%  |
| 5.11    | 6        | 3.16%   |
| 5.13    | 4        | 2.11%   |
| 5.8     | 1        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 179      | 94.21%  |
| 5.11    | 6        | 3.16%   |
| 5.13    | 4        | 2.11%   |
| 5.8     | 1        | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 186      | 97.89%  |
| i686   | 4        | 2.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 186      | 97.89%  |
| i686   | 4        | 2.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KDE5             | 40       | 20.94%  |
| GNOME            | 39       | 20.42%  |
| Unknown          | 28       | 14.66%  |
| XFCE             | 21       | 10.99%  |
| MATE             | 17       | 8.9%    |
| Cinnamon         | 11       | 5.76%   |
| LXQt             | 6        | 3.14%   |
| Trinity          | 5        | 2.62%   |
| LXDE             | 5        | 2.62%   |
| i3               | 5        | 2.62%   |
| KDE              | 4        | 2.09%   |
| X-Cinnamon       | 3        | 1.57%   |
| lightdm-xsession | 2        | 1.05%   |
| GNOME Flashback  | 2        | 1.05%   |
| sway             | 1        | 0.52%   |
| GNUstep          | 1        | 0.52%   |
| Budgie           | 1        | 0.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KDE5             | 40       | 20.94%  |
| GNOME            | 39       | 20.42%  |
| Unknown          | 28       | 14.66%  |
| XFCE             | 21       | 10.99%  |
| MATE             | 17       | 8.9%    |
| Cinnamon         | 11       | 5.76%   |
| LXQt             | 6        | 3.14%   |
| Trinity          | 5        | 2.62%   |
| LXDE             | 5        | 2.62%   |
| i3               | 5        | 2.62%   |
| KDE              | 4        | 2.09%   |
| X-Cinnamon       | 3        | 1.57%   |
| lightdm-xsession | 2        | 1.05%   |
| GNOME Flashback  | 2        | 1.05%   |
| sway             | 1        | 0.52%   |
| GNUstep          | 1        | 0.52%   |
| Budgie           | 1        | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 132      | 69.47%  |
| Wayland | 23       | 12.11%  |
| Tty     | 23       | 12.11%  |
| Unknown | 12       | 6.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 132      | 69.47%  |
| Wayland | 23       | 12.11%  |
| Tty     | 23       | 12.11%  |
| Unknown | 12       | 6.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 64       | 33.51%  |
| Unknown | 42       | 21.99%  |
| SDDM    | 39       | 20.42%  |
| GDM     | 35       | 18.32%  |
| LightDM | 7        | 3.66%   |
| SLiM    | 3        | 1.57%   |
| XDM     | 1        | 0.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 64       | 33.51%  |
| Unknown | 42       | 21.99%  |
| SDDM    | 39       | 20.42%  |
| GDM     | 35       | 18.32%  |
| LightDM | 7        | 3.66%   |
| SLiM    | 3        | 1.57%   |
| XDM     | 1        | 0.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 87       | 45.79%  |
| ru_RU   | 17       | 8.95%   |
| en_GB   | 14       | 7.37%   |
| fr_FR   | 11       | 5.79%   |
| de_DE   | 8        | 4.21%   |
| Unknown | 8        | 4.21%   |
| pt_BR   | 5        | 2.63%   |
| es_ES   | 5        | 2.63%   |
| C       | 4        | 2.11%   |
| pl_PL   | 3        | 1.58%   |
| en_CA   | 3        | 1.58%   |
| en_AU   | 3        | 1.58%   |
| nl_BE   | 2        | 1.05%   |
| uk_UA   | 1        | 0.53%   |
| sv_SE   | 1        | 0.53%   |
| sr_RS   | 1        | 0.53%   |
| ru_UA   | 1        | 0.53%   |
| ro_RO   | 1        | 0.53%   |
| nl_NL   | 1        | 0.53%   |
| it_IT   | 1        | 0.53%   |
| hu_HU   | 1        | 0.53%   |
| hr_HR   | 1        | 0.53%   |
| es_VE   | 1        | 0.53%   |
| es_US   | 1        | 0.53%   |
| es_AR   | 1        | 0.53%   |
| en_PH   | 1        | 0.53%   |
| en_NZ   | 1        | 0.53%   |
| en_IN   | 1        | 0.53%   |
| en_IE   | 1        | 0.53%   |
| en_HK   | 1        | 0.53%   |
| de_CH   | 1        | 0.53%   |
| cs_CZ   | 1        | 0.53%   |
| bg_BG   | 1        | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 87       | 45.79%  |
| ru_RU   | 17       | 8.95%   |
| en_GB   | 14       | 7.37%   |
| fr_FR   | 11       | 5.79%   |
| de_DE   | 8        | 4.21%   |
| Unknown | 8        | 4.21%   |
| pt_BR   | 5        | 2.63%   |
| es_ES   | 5        | 2.63%   |
| C       | 4        | 2.11%   |
| pl_PL   | 3        | 1.58%   |
| en_CA   | 3        | 1.58%   |
| en_AU   | 3        | 1.58%   |
| nl_BE   | 2        | 1.05%   |
| uk_UA   | 1        | 0.53%   |
| sv_SE   | 1        | 0.53%   |
| sr_RS   | 1        | 0.53%   |
| ru_UA   | 1        | 0.53%   |
| ro_RO   | 1        | 0.53%   |
| nl_NL   | 1        | 0.53%   |
| it_IT   | 1        | 0.53%   |
| hu_HU   | 1        | 0.53%   |
| hr_HR   | 1        | 0.53%   |
| es_VE   | 1        | 0.53%   |
| es_US   | 1        | 0.53%   |
| es_AR   | 1        | 0.53%   |
| en_PH   | 1        | 0.53%   |
| en_NZ   | 1        | 0.53%   |
| en_IN   | 1        | 0.53%   |
| en_IE   | 1        | 0.53%   |
| en_HK   | 1        | 0.53%   |
| de_CH   | 1        | 0.53%   |
| cs_CZ   | 1        | 0.53%   |
| bg_BG   | 1        | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 97       | 50.79%  |
| BIOS | 94       | 49.21%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 97       | 50.79%  |
| BIOS | 94       | 49.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 139      | 73.16%  |
| Overlay | 21       | 11.05%  |
| Btrfs   | 18       | 9.47%   |
| Ext3    | 5        | 2.63%   |
| Zfs     | 4        | 2.11%   |
| Xfs     | 2        | 1.05%   |
| Unknown | 1        | 0.53%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 139      | 73.16%  |
| Overlay | 21       | 11.05%  |
| Btrfs   | 18       | 9.47%   |
| Ext3    | 5        | 2.63%   |
| Zfs     | 4        | 2.11%   |
| Xfs     | 2        | 1.05%   |
| Unknown | 1        | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 124      | 64.92%  |
| MBR     | 49       | 25.65%  |
| Unknown | 18       | 9.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 124      | 64.92%  |
| MBR     | 49       | 25.65%  |
| Unknown | 18       | 9.42%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 140      | 73.68%  |
| Yes       | 50       | 26.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 140      | 73.68%  |
| Yes       | 50       | 26.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 137      | 71.73%  |
| Yes       | 54       | 28.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 137      | 71.73%  |
| Yes       | 54       | 28.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 51       | 26.84%  |
| Gigabyte Technology | 37       | 19.47%  |
| ASRock              | 27       | 14.21%  |
| MSI                 | 23       | 12.11%  |
| Dell                | 17       | 8.95%   |
| Hewlett-Packard     | 12       | 6.32%   |
| Lenovo              | 3        | 1.58%   |
| Intel               | 3        | 1.58%   |
| Supermicro          | 2        | 1.05%   |
| Semp Toshiba        | 2        | 1.05%   |
| Huanan              | 2        | 1.05%   |
| Foxconn             | 2        | 1.05%   |
| ECS                 | 2        | 1.05%   |
| Shuttle             | 1        | 0.53%   |
| Protectli           | 1        | 0.53%   |
| HARDKERNEL          | 1        | 0.53%   |
| Fujitsu Siemens     | 1        | 0.53%   |
| Biostar             | 1        | 0.53%   |
| ASRockRack          | 1        | 0.53%   |
| Unknown             | 1        | 0.53%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 51       | 26.84%  |
| Gigabyte Technology | 37       | 19.47%  |
| ASRock              | 27       | 14.21%  |
| MSI                 | 23       | 12.11%  |
| Dell                | 17       | 8.95%   |
| Hewlett-Packard     | 12       | 6.32%   |
| Lenovo              | 3        | 1.58%   |
| Intel               | 3        | 1.58%   |
| Supermicro          | 2        | 1.05%   |
| Semp Toshiba        | 2        | 1.05%   |
| Huanan              | 2        | 1.05%   |
| Foxconn             | 2        | 1.05%   |
| ECS                 | 2        | 1.05%   |
| Shuttle             | 1        | 0.53%   |
| Protectli           | 1        | 0.53%   |
| HARDKERNEL          | 1        | 0.53%   |
| Fujitsu Siemens     | 1        | 0.53%   |
| Biostar             | 1        | 0.53%   |
| ASRockRack          | 1        | 0.53%   |
| Unknown             | 1        | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 5        | 2.63%   |
| Gigabyte Z77-D3H                  | 3        | 1.58%   |
| Gigabyte B550I AORUS PRO AX       | 3        | 1.58%   |
| ASRock B450M Pro4                 | 3        | 1.58%   |
| Semp Toshiba STI                  | 2        | 1.05%   |
| MSI MS-7A70                       | 2        | 1.05%   |
| MSI MS-7721                       | 2        | 1.05%   |
| HP Z620 Workstation               | 2        | 1.05%   |
| Gigabyte Z370 AORUS Gaming 5      | 2        | 1.05%   |
| Gigabyte 970A-DS3P                | 2        | 1.05%   |
| Dell OptiPlex 760                 | 2        | 1.05%   |
| ASUS PRIME B550-PLUS              | 2        | 1.05%   |
| ASUS PRIME B450M-A                | 2        | 1.05%   |
| ASUS PRIME A320M-K                | 2        | 1.05%   |
| Supermicro SYS-5038MA-H24TRF      | 1        | 0.53%   |
| Supermicro SYS-5019S-MR           | 1        | 0.53%   |
| Shuttle SX79R                     | 1        | 0.53%   |
| Protectli FW6                     | 1        | 0.53%   |
| MSI MS-7C94                       | 1        | 0.53%   |
| MSI MS-7C84                       | 1        | 0.53%   |
| MSI MS-7C75                       | 1        | 0.53%   |
| MSI MS-7C56                       | 1        | 0.53%   |
| MSI MS-7C35                       | 1        | 0.53%   |
| MSI MS-7C02                       | 1        | 0.53%   |
| MSI MS-7B92                       | 1        | 0.53%   |
| MSI MS-7B89                       | 1        | 0.53%   |
| MSI MS-7B79                       | 1        | 0.53%   |
| MSI MS-7B46                       | 1        | 0.53%   |
| MSI MS-7B09                       | 1        | 0.53%   |
| MSI MS-7A40                       | 1        | 0.53%   |
| MSI MS-7A38                       | 1        | 0.53%   |
| MSI MS-7995                       | 1        | 0.53%   |
| MSI MS-7823                       | 1        | 0.53%   |
| MSI MS-7759                       | 1        | 0.53%   |
| MSI MS-7641                       | 1        | 0.53%   |
| MSI MS-7562                       | 1        | 0.53%   |
| MSI MS-6712                       | 1        | 0.53%   |
| Lenovo ThinkCentre M92p 3209EK4   | 1        | 0.53%   |
| Lenovo ThinkCentre M73 10B00005US | 1        | 0.53%   |
| Lenovo ThinkCentre M55p 8808D8U   | 1        | 0.53%   |
| Intel DP55WG AAE57269-407         | 1        | 0.53%   |
| Intel DP55WB AAE64798-206         | 1        | 0.53%   |
| Intel DN2820FYK H24582-201        | 1        | 0.53%   |
| Huanan X99-F8                     | 1        | 0.53%   |
| Huanan X99-8M-F V1.1              | 1        | 0.53%   |
| HP Z840 Workstation               | 1        | 0.53%   |
| HP t620 Dual Core TC              | 1        | 0.53%   |
| HP ProLiant MicroServer Gen8      | 1        | 0.53%   |
| HP ProLiant MicroServer           | 1        | 0.53%   |
| HP EliteDesk 705 G1 SFF           | 1        | 0.53%   |
| HP Compaq Elite 8300 SFF          | 1        | 0.53%   |
| HP Compaq 8200 Elite SFF PC       | 1        | 0.53%   |
| HP Compaq 6005 Pro MT PC          | 1        | 0.53%   |
| HP Compaq 6000 Pro SFF PC         | 1        | 0.53%   |
| HP 200-010hk                      | 1        | 0.53%   |
| HARDKERNEL ODROID-H2              | 1        | 0.53%   |
| Gigabyte Z97X-UD3H                | 1        | 0.53%   |
| Gigabyte Z97N-WIFI                | 1        | 0.53%   |
| Gigabyte Z170X-GamingG1           | 1        | 0.53%   |
| Gigabyte Z170M-D3H                | 1        | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 5        | 2.63%   |
| Gigabyte Z77-D3H                  | 3        | 1.58%   |
| Gigabyte B550I AORUS PRO AX       | 3        | 1.58%   |
| ASRock B450M Pro4                 | 3        | 1.58%   |
| Semp Toshiba STI                  | 2        | 1.05%   |
| MSI MS-7A70                       | 2        | 1.05%   |
| MSI MS-7721                       | 2        | 1.05%   |
| HP Z620 Workstation               | 2        | 1.05%   |
| Gigabyte Z370 AORUS Gaming 5      | 2        | 1.05%   |
| Gigabyte 970A-DS3P                | 2        | 1.05%   |
| Dell OptiPlex 760                 | 2        | 1.05%   |
| ASUS PRIME B550-PLUS              | 2        | 1.05%   |
| ASUS PRIME B450M-A                | 2        | 1.05%   |
| ASUS PRIME A320M-K                | 2        | 1.05%   |
| Supermicro SYS-5038MA-H24TRF      | 1        | 0.53%   |
| Supermicro SYS-5019S-MR           | 1        | 0.53%   |
| Shuttle SX79R                     | 1        | 0.53%   |
| Protectli FW6                     | 1        | 0.53%   |
| MSI MS-7C94                       | 1        | 0.53%   |
| MSI MS-7C84                       | 1        | 0.53%   |
| MSI MS-7C75                       | 1        | 0.53%   |
| MSI MS-7C56                       | 1        | 0.53%   |
| MSI MS-7C35                       | 1        | 0.53%   |
| MSI MS-7C02                       | 1        | 0.53%   |
| MSI MS-7B92                       | 1        | 0.53%   |
| MSI MS-7B89                       | 1        | 0.53%   |
| MSI MS-7B79                       | 1        | 0.53%   |
| MSI MS-7B46                       | 1        | 0.53%   |
| MSI MS-7B09                       | 1        | 0.53%   |
| MSI MS-7A40                       | 1        | 0.53%   |
| MSI MS-7A38                       | 1        | 0.53%   |
| MSI MS-7995                       | 1        | 0.53%   |
| MSI MS-7823                       | 1        | 0.53%   |
| MSI MS-7759                       | 1        | 0.53%   |
| MSI MS-7641                       | 1        | 0.53%   |
| MSI MS-7562                       | 1        | 0.53%   |
| MSI MS-6712                       | 1        | 0.53%   |
| Lenovo ThinkCentre M92p 3209EK4   | 1        | 0.53%   |
| Lenovo ThinkCentre M73 10B00005US | 1        | 0.53%   |
| Lenovo ThinkCentre M55p 8808D8U   | 1        | 0.53%   |
| Intel DP55WG AAE57269-407         | 1        | 0.53%   |
| Intel DP55WB AAE64798-206         | 1        | 0.53%   |
| Intel DN2820FYK H24582-201        | 1        | 0.53%   |
| Huanan X99-F8                     | 1        | 0.53%   |
| Huanan X99-8M-F V1.1              | 1        | 0.53%   |
| HP Z840 Workstation               | 1        | 0.53%   |
| HP t620 Dual Core TC              | 1        | 0.53%   |
| HP ProLiant MicroServer Gen8      | 1        | 0.53%   |
| HP ProLiant MicroServer           | 1        | 0.53%   |
| HP EliteDesk 705 G1 SFF           | 1        | 0.53%   |
| HP Compaq Elite 8300 SFF          | 1        | 0.53%   |
| HP Compaq 8200 Elite SFF PC       | 1        | 0.53%   |
| HP Compaq 6005 Pro MT PC          | 1        | 0.53%   |
| HP Compaq 6000 Pro SFF PC         | 1        | 0.53%   |
| HP 200-010hk                      | 1        | 0.53%   |
| HARDKERNEL ODROID-H2              | 1        | 0.53%   |
| Gigabyte Z97X-UD3H                | 1        | 0.53%   |
| Gigabyte Z97N-WIFI                | 1        | 0.53%   |
| Gigabyte Z170X-GamingG1           | 1        | 0.53%   |
| Gigabyte Z170M-D3H                | 1        | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS PRIME                   | 18       | 9.47%   |
| Dell OptiPlex                | 11       | 5.79%   |
| ASUS ROG                     | 7        | 3.68%   |
| Dell Precision               | 5        | 2.63%   |
| ASUS All                     | 5        | 2.63%   |
| HP Compaq                    | 4        | 2.11%   |
| Lenovo ThinkCentre           | 3        | 1.58%   |
| Gigabyte Z77-D3H             | 3        | 1.58%   |
| Gigabyte B550I               | 3        | 1.58%   |
| ASRock Z97                   | 3        | 1.58%   |
| ASRock B450M                 | 3        | 1.58%   |
| Semp Toshiba STI             | 2        | 1.05%   |
| MSI MS-7A70                  | 2        | 1.05%   |
| MSI MS-7721                  | 2        | 1.05%   |
| HP Z620                      | 2        | 1.05%   |
| HP ProLiant                  | 2        | 1.05%   |
| Gigabyte Z370                | 2        | 1.05%   |
| Gigabyte 970A-DS3P           | 2        | 1.05%   |
| ASUS Pro                     | 2        | 1.05%   |
| Supermicro SYS-5038MA-H24TRF | 1        | 0.53%   |
| Supermicro SYS-5019S-MR      | 1        | 0.53%   |
| Shuttle SX79R                | 1        | 0.53%   |
| Protectli FW6                | 1        | 0.53%   |
| MSI MS-7C94                  | 1        | 0.53%   |
| MSI MS-7C84                  | 1        | 0.53%   |
| MSI MS-7C75                  | 1        | 0.53%   |
| MSI MS-7C56                  | 1        | 0.53%   |
| MSI MS-7C35                  | 1        | 0.53%   |
| MSI MS-7C02                  | 1        | 0.53%   |
| MSI MS-7B92                  | 1        | 0.53%   |
| MSI MS-7B89                  | 1        | 0.53%   |
| MSI MS-7B79                  | 1        | 0.53%   |
| MSI MS-7B46                  | 1        | 0.53%   |
| MSI MS-7B09                  | 1        | 0.53%   |
| MSI MS-7A40                  | 1        | 0.53%   |
| MSI MS-7A38                  | 1        | 0.53%   |
| MSI MS-7995                  | 1        | 0.53%   |
| MSI MS-7823                  | 1        | 0.53%   |
| MSI MS-7759                  | 1        | 0.53%   |
| MSI MS-7641                  | 1        | 0.53%   |
| MSI MS-7562                  | 1        | 0.53%   |
| MSI MS-6712                  | 1        | 0.53%   |
| Intel DP55WG                 | 1        | 0.53%   |
| Intel DP55WB                 | 1        | 0.53%   |
| Intel DN2820FYK              | 1        | 0.53%   |
| Huanan X99-F8                | 1        | 0.53%   |
| Huanan X99-8M-F              | 1        | 0.53%   |
| HP Z840                      | 1        | 0.53%   |
| HP t620                      | 1        | 0.53%   |
| HP EliteDesk                 | 1        | 0.53%   |
| HP 200-010hk                 | 1        | 0.53%   |
| HARDKERNEL ODROID-H2         | 1        | 0.53%   |
| Gigabyte Z97X-UD3H           | 1        | 0.53%   |
| Gigabyte Z97N-WIFI           | 1        | 0.53%   |
| Gigabyte Z170X-GamingG1      | 1        | 0.53%   |
| Gigabyte Z170M-D3H           | 1        | 0.53%   |
| Gigabyte X570                | 1        | 0.53%   |
| Gigabyte X399                | 1        | 0.53%   |
| Gigabyte P35C-DS3R           | 1        | 0.53%   |
| Gigabyte H87-HD3             | 1        | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS PRIME                   | 18       | 9.47%   |
| Dell OptiPlex                | 11       | 5.79%   |
| ASUS ROG                     | 7        | 3.68%   |
| Dell Precision               | 5        | 2.63%   |
| ASUS All                     | 5        | 2.63%   |
| HP Compaq                    | 4        | 2.11%   |
| Lenovo ThinkCentre           | 3        | 1.58%   |
| Gigabyte Z77-D3H             | 3        | 1.58%   |
| Gigabyte B550I               | 3        | 1.58%   |
| ASRock Z97                   | 3        | 1.58%   |
| ASRock B450M                 | 3        | 1.58%   |
| Semp Toshiba STI             | 2        | 1.05%   |
| MSI MS-7A70                  | 2        | 1.05%   |
| MSI MS-7721                  | 2        | 1.05%   |
| HP Z620                      | 2        | 1.05%   |
| HP ProLiant                  | 2        | 1.05%   |
| Gigabyte Z370                | 2        | 1.05%   |
| Gigabyte 970A-DS3P           | 2        | 1.05%   |
| ASUS Pro                     | 2        | 1.05%   |
| Supermicro SYS-5038MA-H24TRF | 1        | 0.53%   |
| Supermicro SYS-5019S-MR      | 1        | 0.53%   |
| Shuttle SX79R                | 1        | 0.53%   |
| Protectli FW6                | 1        | 0.53%   |
| MSI MS-7C94                  | 1        | 0.53%   |
| MSI MS-7C84                  | 1        | 0.53%   |
| MSI MS-7C75                  | 1        | 0.53%   |
| MSI MS-7C56                  | 1        | 0.53%   |
| MSI MS-7C35                  | 1        | 0.53%   |
| MSI MS-7C02                  | 1        | 0.53%   |
| MSI MS-7B92                  | 1        | 0.53%   |
| MSI MS-7B89                  | 1        | 0.53%   |
| MSI MS-7B79                  | 1        | 0.53%   |
| MSI MS-7B46                  | 1        | 0.53%   |
| MSI MS-7B09                  | 1        | 0.53%   |
| MSI MS-7A40                  | 1        | 0.53%   |
| MSI MS-7A38                  | 1        | 0.53%   |
| MSI MS-7995                  | 1        | 0.53%   |
| MSI MS-7823                  | 1        | 0.53%   |
| MSI MS-7759                  | 1        | 0.53%   |
| MSI MS-7641                  | 1        | 0.53%   |
| MSI MS-7562                  | 1        | 0.53%   |
| MSI MS-6712                  | 1        | 0.53%   |
| Intel DP55WG                 | 1        | 0.53%   |
| Intel DP55WB                 | 1        | 0.53%   |
| Intel DN2820FYK              | 1        | 0.53%   |
| Huanan X99-F8                | 1        | 0.53%   |
| Huanan X99-8M-F              | 1        | 0.53%   |
| HP Z840                      | 1        | 0.53%   |
| HP t620                      | 1        | 0.53%   |
| HP EliteDesk                 | 1        | 0.53%   |
| HP 200-010hk                 | 1        | 0.53%   |
| HARDKERNEL ODROID-H2         | 1        | 0.53%   |
| Gigabyte Z97X-UD3H           | 1        | 0.53%   |
| Gigabyte Z97N-WIFI           | 1        | 0.53%   |
| Gigabyte Z170X-GamingG1      | 1        | 0.53%   |
| Gigabyte Z170M-D3H           | 1        | 0.53%   |
| Gigabyte X570                | 1        | 0.53%   |
| Gigabyte X399                | 1        | 0.53%   |
| Gigabyte P35C-DS3R           | 1        | 0.53%   |
| Gigabyte H87-HD3             | 1        | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 36       | 18.95%  |
| 2019 | 27       | 14.21%  |
| 2018 | 24       | 12.63%  |
| 2021 | 18       | 9.47%   |
| 2016 | 14       | 7.37%   |
| 2014 | 12       | 6.32%   |
| 2012 | 11       | 5.79%   |
| 2015 | 10       | 5.26%   |
| 2010 | 8        | 4.21%   |
| 2013 | 7        | 3.68%   |
| 2009 | 7        | 3.68%   |
| 2017 | 4        | 2.11%   |
| 2011 | 4        | 2.11%   |
| 2007 | 3        | 1.58%   |
| 2008 | 2        | 1.05%   |
| 2006 | 2        | 1.05%   |
| 2001 | 1        | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 36       | 18.95%  |
| 2019 | 27       | 14.21%  |
| 2018 | 24       | 12.63%  |
| 2021 | 18       | 9.47%   |
| 2016 | 14       | 7.37%   |
| 2014 | 12       | 6.32%   |
| 2012 | 11       | 5.79%   |
| 2015 | 10       | 5.26%   |
| 2010 | 8        | 4.21%   |
| 2013 | 7        | 3.68%   |
| 2009 | 7        | 3.68%   |
| 2017 | 4        | 2.11%   |
| 2011 | 4        | 2.11%   |
| 2007 | 3        | 1.58%   |
| 2008 | 2        | 1.05%   |
| 2006 | 2        | 1.05%   |
| 2001 | 1        | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 190      | 100%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 190      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 187      | 98.42%  |
| Enabled  | 3        | 1.58%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 187      | 98.42%  |
| Enabled  | 3        | 1.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 189      | 99.47%  |
| Yes  | 1        | 0.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 189      | 99.47%  |
| Yes  | 1        | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 61       | 32.11%  |
| 8.01-16.0       | 35       | 18.42%  |
| 32.01-64.0      | 33       | 17.37%  |
| 64.01-256.0     | 21       | 11.05%  |
| 4.01-8.0        | 17       | 8.95%   |
| 3.01-4.0        | 11       | 5.79%   |
| 1.01-2.0        | 5        | 2.63%   |
| 2.01-3.0        | 3        | 1.58%   |
| 24.01-32.0      | 2        | 1.05%   |
| More than 256.0 | 1        | 0.53%   |
| 0.51-1.0        | 1        | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 61       | 32.11%  |
| 8.01-16.0       | 35       | 18.42%  |
| 32.01-64.0      | 33       | 17.37%  |
| 64.01-256.0     | 21       | 11.05%  |
| 4.01-8.0        | 17       | 8.95%   |
| 3.01-4.0        | 11       | 5.79%   |
| 1.01-2.0        | 5        | 2.63%   |
| 2.01-3.0        | 3        | 1.58%   |
| 24.01-32.0      | 2        | 1.05%   |
| More than 256.0 | 1        | 0.53%   |
| 0.51-1.0        | 1        | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 35       | 18.23%  |
| 4.01-8.0    | 34       | 17.71%  |
| 3.01-4.0    | 32       | 16.67%  |
| 2.01-3.0    | 32       | 16.67%  |
| 0.51-1.0    | 20       | 10.42%  |
| 8.01-16.0   | 14       | 7.29%   |
| 0.01-0.5    | 13       | 6.77%   |
| 16.01-24.0  | 5        | 2.6%    |
| 24.01-32.0  | 4        | 2.08%   |
| 32.01-64.0  | 2        | 1.04%   |
| 64.01-256.0 | 1        | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 35       | 18.23%  |
| 4.01-8.0    | 34       | 17.71%  |
| 3.01-4.0    | 32       | 16.67%  |
| 2.01-3.0    | 32       | 16.67%  |
| 0.51-1.0    | 20       | 10.42%  |
| 8.01-16.0   | 14       | 7.29%   |
| 0.01-0.5    | 13       | 6.77%   |
| 16.01-24.0  | 5        | 2.6%    |
| 24.01-32.0  | 4        | 2.08%   |
| 32.01-64.0  | 2        | 1.04%   |
| 64.01-256.0 | 1        | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 59       | 31.05%  |
| 2      | 53       | 27.89%  |
| 3      | 34       | 17.89%  |
| 4      | 19       | 10%     |
| 5      | 12       | 6.32%   |
| 8      | 4        | 2.11%   |
| 6      | 4        | 2.11%   |
| 9      | 3        | 1.58%   |
| 10     | 2        | 1.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 59       | 31.05%  |
| 2      | 53       | 27.89%  |
| 3      | 34       | 17.89%  |
| 4      | 19       | 10%     |
| 5      | 12       | 6.32%   |
| 8      | 4        | 2.11%   |
| 6      | 4        | 2.11%   |
| 9      | 3        | 1.58%   |
| 10     | 2        | 1.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 53.68%  |
| Yes       | 88       | 46.32%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 53.68%  |
| Yes       | 88       | 46.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 189      | 99.47%  |
| No        | 1        | 0.53%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 189      | 99.47%  |
| No        | 1        | 0.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 132      | 69.47%  |
| Yes       | 58       | 30.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 132      | 69.47%  |
| Yes       | 58       | 30.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 142      | 74.74%  |
| Yes       | 48       | 25.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 142      | 74.74%  |
| Yes       | 48       | 25.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 47       | 24.74%  |
| Russia                 | 19       | 10%     |
| UK                     | 14       | 7.37%   |
| France                 | 14       | 7.37%   |
| Germany                | 13       | 6.84%   |
| Ukraine                | 8        | 4.21%   |
| Spain                  | 8        | 4.21%   |
| Poland                 | 5        | 2.63%   |
| Brazil                 | 5        | 2.63%   |
| Netherlands            | 4        | 2.11%   |
| Bulgaria               | 4        | 2.11%   |
| Belgium                | 4        | 2.11%   |
| Australia              | 4        | 2.11%   |
| Sweden                 | 3        | 1.58%   |
| Mexico                 | 3        | 1.58%   |
| Czechia                | 3        | 1.58%   |
| Canada                 | 3        | 1.58%   |
| Venezuela              | 2        | 1.05%   |
| Switzerland            | 2        | 1.05%   |
| Norway                 | 2        | 1.05%   |
| Italy                  | 2        | 1.05%   |
| Hungary                | 2        | 1.05%   |
| Finland                | 2        | 1.05%   |
| Argentina              | 2        | 1.05%   |
| Syria                  | 1        | 0.53%   |
| Singapore              | 1        | 0.53%   |
| Serbia                 | 1        | 0.53%   |
| Romania                | 1        | 0.53%   |
| New Zealand            | 1        | 0.53%   |
| New Caledonia          | 1        | 0.53%   |
| Madagascar             | 1        | 0.53%   |
| Ireland                | 1        | 0.53%   |
| India                  | 1        | 0.53%   |
| Hong Kong              | 1        | 0.53%   |
| Greece                 | 1        | 0.53%   |
| Ecuador                | 1        | 0.53%   |
| Croatia                | 1        | 0.53%   |
| Bosnia and Herzegovina | 1        | 0.53%   |
| Austria                | 1        | 0.53%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 47       | 24.74%  |
| Russia                 | 19       | 10%     |
| UK                     | 14       | 7.37%   |
| France                 | 14       | 7.37%   |
| Germany                | 13       | 6.84%   |
| Ukraine                | 8        | 4.21%   |
| Spain                  | 8        | 4.21%   |
| Poland                 | 5        | 2.63%   |
| Brazil                 | 5        | 2.63%   |
| Netherlands            | 4        | 2.11%   |
| Bulgaria               | 4        | 2.11%   |
| Belgium                | 4        | 2.11%   |
| Australia              | 4        | 2.11%   |
| Sweden                 | 3        | 1.58%   |
| Mexico                 | 3        | 1.58%   |
| Czechia                | 3        | 1.58%   |
| Canada                 | 3        | 1.58%   |
| Venezuela              | 2        | 1.05%   |
| Switzerland            | 2        | 1.05%   |
| Norway                 | 2        | 1.05%   |
| Italy                  | 2        | 1.05%   |
| Hungary                | 2        | 1.05%   |
| Finland                | 2        | 1.05%   |
| Argentina              | 2        | 1.05%   |
| Syria                  | 1        | 0.53%   |
| Singapore              | 1        | 0.53%   |
| Serbia                 | 1        | 0.53%   |
| Romania                | 1        | 0.53%   |
| New Zealand            | 1        | 0.53%   |
| New Caledonia          | 1        | 0.53%   |
| Madagascar             | 1        | 0.53%   |
| Ireland                | 1        | 0.53%   |
| India                  | 1        | 0.53%   |
| Hong Kong              | 1        | 0.53%   |
| Greece                 | 1        | 0.53%   |
| Ecuador                | 1        | 0.53%   |
| Croatia                | 1        | 0.53%   |
| Bosnia and Herzegovina | 1        | 0.53%   |
| Austria                | 1        | 0.53%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Portland                    | 5        | 2.6%    |
| Ocala                       | 5        | 2.6%    |
| Lyon                        | 5        | 2.6%    |
| Sofia                       | 4        | 2.08%   |
| London                      | 4        | 2.08%   |
| Moscow                      | 3        | 1.56%   |
| Kalamazoo                   | 3        | 1.56%   |
| Frankfort                   | 3        | 1.56%   |
| Ensenada                    | 3        | 1.56%   |
| Warsaw                      | 2        | 1.04%   |
| Stockholm                   | 2        | 1.04%   |
| Saint-Denis                 | 2        | 1.04%   |
| Perm                        | 2        | 1.04%   |
| New York                    | 2        | 1.04%   |
| Las Vegas                   | 2        | 1.04%   |
| Kyiv                        | 2        | 1.04%   |
| Kharkiv                     | 2        | 1.04%   |
| Clitheroe                   | 2        | 1.04%   |
| Athens                      | 2        | 1.04%   |
| Amsterdam                   | 2        | 1.04%   |
| Érd                        | 1        | 0.52%   |
| Zastavka                    | 1        | 0.52%   |
| Zagreb                      | 1        | 0.52%   |
| Yuncos                      | 1        | 0.52%   |
| Ypres                       | 1        | 0.52%   |
| Yekaterinburg               | 1        | 0.52%   |
| Woolloongabba               | 1        | 0.52%   |
| Woodstock                   | 1        | 0.52%   |
| Wenatchee                   | 1        | 0.52%   |
| Waregem                     | 1        | 0.52%   |
| Voerde                      | 1        | 0.52%   |
| Vladivostok                 | 1        | 0.52%   |
| Vladimir                    | 1        | 0.52%   |
| Vienna                      | 1        | 0.52%   |
| Vancouver                   | 1        | 0.52%   |
| Valladolid                  | 1        | 0.52%   |
| Valera                      | 1        | 0.52%   |
| Vaasa                       | 1        | 0.52%   |
| Ulyanovsk                   | 1        | 0.52%   |
| Ufa                         | 1        | 0.52%   |
| Turku                       | 1        | 0.52%   |
| Toulouse                    | 1        | 0.52%   |
| Thionville                  | 1        | 0.52%   |
| Tai Kok Tsui                | 1        | 0.52%   |
| Stroud                      | 1        | 0.52%   |
| Strasbourg                  | 1        | 0.52%   |
| Stockelsdorf                | 1        | 0.52%   |
| Stavanger                   | 1        | 0.52%   |
| St Petersburg               | 1        | 0.52%   |
| Springfield                 | 1        | 0.52%   |
| Sosnowiec                   | 1        | 0.52%   |
| Singapore                   | 1        | 0.52%   |
| Sevastopol                  | 1        | 0.52%   |
| S??o Paulo                  | 1        | 0.52%   |
| Saratov                     | 1        | 0.52%   |
| Sarajevo                    | 1        | 0.52%   |
| Santa Brigida               | 1        | 0.52%   |
| San Francisco               | 1        | 0.52%   |
| San Cristóbal de La Laguna | 1        | 0.52%   |
| Rochester                   | 1        | 0.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Portland                    | 5        | 2.6%    |
| Ocala                       | 5        | 2.6%    |
| Lyon                        | 5        | 2.6%    |
| Sofia                       | 4        | 2.08%   |
| London                      | 4        | 2.08%   |
| Moscow                      | 3        | 1.56%   |
| Kalamazoo                   | 3        | 1.56%   |
| Frankfort                   | 3        | 1.56%   |
| Ensenada                    | 3        | 1.56%   |
| Warsaw                      | 2        | 1.04%   |
| Stockholm                   | 2        | 1.04%   |
| Saint-Denis                 | 2        | 1.04%   |
| Perm                        | 2        | 1.04%   |
| New York                    | 2        | 1.04%   |
| Las Vegas                   | 2        | 1.04%   |
| Kyiv                        | 2        | 1.04%   |
| Kharkiv                     | 2        | 1.04%   |
| Clitheroe                   | 2        | 1.04%   |
| Athens                      | 2        | 1.04%   |
| Amsterdam                   | 2        | 1.04%   |
| Érd                        | 1        | 0.52%   |
| Zastavka                    | 1        | 0.52%   |
| Zagreb                      | 1        | 0.52%   |
| Yuncos                      | 1        | 0.52%   |
| Ypres                       | 1        | 0.52%   |
| Yekaterinburg               | 1        | 0.52%   |
| Woolloongabba               | 1        | 0.52%   |
| Woodstock                   | 1        | 0.52%   |
| Wenatchee                   | 1        | 0.52%   |
| Waregem                     | 1        | 0.52%   |
| Voerde                      | 1        | 0.52%   |
| Vladivostok                 | 1        | 0.52%   |
| Vladimir                    | 1        | 0.52%   |
| Vienna                      | 1        | 0.52%   |
| Vancouver                   | 1        | 0.52%   |
| Valladolid                  | 1        | 0.52%   |
| Valera                      | 1        | 0.52%   |
| Vaasa                       | 1        | 0.52%   |
| Ulyanovsk                   | 1        | 0.52%   |
| Ufa                         | 1        | 0.52%   |
| Turku                       | 1        | 0.52%   |
| Toulouse                    | 1        | 0.52%   |
| Thionville                  | 1        | 0.52%   |
| Tai Kok Tsui                | 1        | 0.52%   |
| Stroud                      | 1        | 0.52%   |
| Strasbourg                  | 1        | 0.52%   |
| Stockelsdorf                | 1        | 0.52%   |
| Stavanger                   | 1        | 0.52%   |
| St Petersburg               | 1        | 0.52%   |
| Springfield                 | 1        | 0.52%   |
| Sosnowiec                   | 1        | 0.52%   |
| Singapore                   | 1        | 0.52%   |
| Sevastopol                  | 1        | 0.52%   |
| S??o Paulo                  | 1        | 0.52%   |
| Saratov                     | 1        | 0.52%   |
| Sarajevo                    | 1        | 0.52%   |
| Santa Brigida               | 1        | 0.52%   |
| San Francisco               | 1        | 0.52%   |
| San Cristóbal de La Laguna | 1        | 0.52%   |
| Rochester                   | 1        | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 72       | 116    | 20.51%  |
| Seagate             | 72       | 119    | 20.51%  |
| Samsung Electronics | 55       | 84     | 15.67%  |
| Crucial             | 25       | 29     | 7.12%   |
| Kingston            | 23       | 27     | 6.55%   |
| Toshiba             | 20       | 36     | 5.7%    |
| SanDisk             | 12       | 15     | 3.42%   |
| Hitachi             | 11       | 12     | 3.13%   |
| Intel               | 10       | 17     | 2.85%   |
| SPCC                | 5        | 5      | 1.42%   |
| PNY                 | 5        | 5      | 1.42%   |
| HGST                | 5        | 7      | 1.42%   |
| A-DATA Technology   | 5        | 7      | 1.42%   |
| Gigabyte Technology | 3        | 3      | 0.85%   |
| Unknown             | 2        | 2      | 0.57%   |
| SABRENT             | 2        | 2      | 0.57%   |
| Phison Electronics  | 2        | 2      | 0.57%   |
| Phison              | 2        | 2      | 0.57%   |
| Micron Technology   | 2        | 2      | 0.57%   |
| Corsair             | 2        | 2      | 0.57%   |
| Transcend           | 1        | 2      | 0.28%   |
| Team                | 1        | 1      | 0.28%   |
| T-FORCE             | 1        | 1      | 0.28%   |
| SK Hynix            | 1        | 2      | 0.28%   |
| Patriot             | 1        | 1      | 0.28%   |
| OCZ                 | 1        | 1      | 0.28%   |
| Netac               | 1        | 1      | 0.28%   |
| NAS                 | 1        | 5      | 0.28%   |
| MAXTOR              | 1        | 1      | 0.28%   |
| MaxDigital          | 1        | 2      | 0.28%   |
| Lexar               | 1        | 1      | 0.28%   |
| KingDian            | 1        | 1      | 0.28%   |
| Intenso             | 1        | 2      | 0.28%   |
| Hewlett-Packard     | 1        | 1      | 0.28%   |
| DOGFISH             | 1        | 1      | 0.28%   |
| China               | 1        | 1      | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 72       | 116    | 20.51%  |
| Seagate             | 72       | 119    | 20.51%  |
| Samsung Electronics | 55       | 84     | 15.67%  |
| Crucial             | 25       | 29     | 7.12%   |
| Kingston            | 23       | 27     | 6.55%   |
| Toshiba             | 20       | 36     | 5.7%    |
| SanDisk             | 12       | 15     | 3.42%   |
| Hitachi             | 11       | 12     | 3.13%   |
| Intel               | 10       | 17     | 2.85%   |
| SPCC                | 5        | 5      | 1.42%   |
| PNY                 | 5        | 5      | 1.42%   |
| HGST                | 5        | 7      | 1.42%   |
| A-DATA Technology   | 5        | 7      | 1.42%   |
| Gigabyte Technology | 3        | 3      | 0.85%   |
| Unknown             | 2        | 2      | 0.57%   |
| SABRENT             | 2        | 2      | 0.57%   |
| Phison Electronics  | 2        | 2      | 0.57%   |
| Phison              | 2        | 2      | 0.57%   |
| Micron Technology   | 2        | 2      | 0.57%   |
| Corsair             | 2        | 2      | 0.57%   |
| Transcend           | 1        | 2      | 0.28%   |
| Team                | 1        | 1      | 0.28%   |
| T-FORCE             | 1        | 1      | 0.28%   |
| SK Hynix            | 1        | 2      | 0.28%   |
| Patriot             | 1        | 1      | 0.28%   |
| OCZ                 | 1        | 1      | 0.28%   |
| Netac               | 1        | 1      | 0.28%   |
| NAS                 | 1        | 5      | 0.28%   |
| MAXTOR              | 1        | 1      | 0.28%   |
| MaxDigital          | 1        | 2      | 0.28%   |
| Lexar               | 1        | 1      | 0.28%   |
| KingDian            | 1        | 1      | 0.28%   |
| Intenso             | 1        | 2      | 0.28%   |
| Hewlett-Packard     | 1        | 1      | 0.28%   |
| DOGFISH             | 1        | 1      | 0.28%   |
| China               | 1        | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB           | 9        | 2.1%    |
| Seagate ST500DM002-1BD142 500GB   | 6        | 1.4%    |
| Seagate ST1000DM010-2EP102 1TB    | 6        | 1.4%    |
| Samsung SSD 850 EVO 250GB         | 6        | 1.4%    |
| Kingston SA400S37120G 120GB SSD   | 6        | 1.4%    |
| Toshiba HDWD110 1TB               | 5        | 1.17%   |
| Seagate ST4000DM004-2CV104 4TB    | 5        | 1.17%   |
| Samsung SSD 970 EVO Plus 500GB    | 5        | 1.17%   |
| Samsung SSD 850 EVO 500GB         | 5        | 1.17%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 4        | 0.93%   |
| Toshiba DT01ACA300 3TB            | 4        | 0.93%   |
| Toshiba DT01ACA200 2TB            | 4        | 0.93%   |
| Seagate ST2000DM008-2FR102 2TB    | 4        | 0.93%   |
| Seagate ST2000DM001-1ER164 2TB    | 4        | 0.93%   |
| Samsung SSD 970 EVO Plus 1TB      | 4        | 0.93%   |
| Samsung SSD 970 EVO 500GB         | 4        | 0.93%   |
| Kingston SV300S37A240G 240GB SSD  | 4        | 0.93%   |
| WDC WDS500G3X0C-00SJG0 500GB      | 3        | 0.7%    |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 3        | 0.7%    |
| WDC WD40EFRX-68N32N0 4TB          | 3        | 0.7%    |
| WDC WD10EZEX-08WN4A0 1TB          | 3        | 0.7%    |
| WDC WD10EZEX-00BN5A0 1TB          | 3        | 0.7%    |
| Seagate ST3000DM001-1CH166 3TB    | 3        | 0.7%    |
| SanDisk SD8SBAT128G1122 128GB SSD | 3        | 0.7%    |
| Samsung SSD 980 PRO 1TB           | 3        | 0.7%    |
| Kingston SV300S37A120G 120GB SSD  | 3        | 0.7%    |
| Kingston SA400S37240G 240GB SSD   | 3        | 0.7%    |
| Hitachi HUS724040ALE641 4TB       | 3        | 0.7%    |
| Crucial CT500P1SSD8 500GB         | 3        | 0.7%    |
| Crucial CT500MX500SSD1 500GB      | 3        | 0.7%    |
| Crucial CT240BX500SSD1 240GB      | 3        | 0.7%    |
| Crucial CT1000MX500SSD1 1TB       | 3        | 0.7%    |
| WDC WDS500G2B0C-00PXH0 500GB      | 2        | 0.47%   |
| WDC WD5000AADS-00S9B0 500GB       | 2        | 0.47%   |
| WDC WD20EZAZ-00GGJB0 2TB          | 2        | 0.47%   |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 0.47%   |
| WDC WD20EARX-00PASB0 2TB          | 2        | 0.47%   |
| WDC WD20EARS-00MVWB0 2TB          | 2        | 0.47%   |
| WDC WD10EFRX-68FYTN0 1TB          | 2        | 0.47%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 2        | 0.47%   |
| Seagate ST4000DM000-1F2168 4TB    | 2        | 0.47%   |
| Seagate ST3320620A 320GB          | 2        | 0.47%   |
| Seagate ST3160815AS 160GB         | 2        | 0.47%   |
| Seagate ST2000DM006-2DM164 2TB    | 2        | 0.47%   |
| Seagate ST1000DM003-1CH162 1TB    | 2        | 0.47%   |
| Seagate BUP Slim BL 2TB           | 2        | 0.47%   |
| Seagate Backup+ Hub BK 500GB      | 2        | 0.47%   |
| Sandisk NVMe SSD Drive 1TB        | 2        | 0.47%   |
| Samsung SSD 960 EVO 250GB         | 2        | 0.47%   |
| Samsung SSD 860 EVO 500GB         | 2        | 0.47%   |
| Samsung SSD 860 EVO 2TB           | 2        | 0.47%   |
| Samsung SSD 860 EVO 250GB         | 2        | 0.47%   |
| Samsung SSD 840 PRO Series 256GB  | 2        | 0.47%   |
| Samsung SSD 840 EVO 250GB         | 2        | 0.47%   |
| Samsung HD103SJ 1TB               | 2        | 0.47%   |
| SABRENT Disk 500GB                | 2        | 0.47%   |
| Phison PCIe SSD 1TB               | 2        | 0.47%   |
| Kingston SUV500240G 240GB SSD     | 2        | 0.47%   |
| Intel SSDPEKNW010T9 1TB           | 2        | 0.47%   |
| Intel NVMe SSD Drive 1024GB       | 2        | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB           | 9        | 2.1%    |
| Seagate ST500DM002-1BD142 500GB   | 6        | 1.4%    |
| Seagate ST1000DM010-2EP102 1TB    | 6        | 1.4%    |
| Samsung SSD 850 EVO 250GB         | 6        | 1.4%    |
| Kingston SA400S37120G 120GB SSD   | 6        | 1.4%    |
| Toshiba HDWD110 1TB               | 5        | 1.17%   |
| Seagate ST4000DM004-2CV104 4TB    | 5        | 1.17%   |
| Samsung SSD 970 EVO Plus 500GB    | 5        | 1.17%   |
| Samsung SSD 850 EVO 500GB         | 5        | 1.17%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 4        | 0.93%   |
| Toshiba DT01ACA300 3TB            | 4        | 0.93%   |
| Toshiba DT01ACA200 2TB            | 4        | 0.93%   |
| Seagate ST2000DM008-2FR102 2TB    | 4        | 0.93%   |
| Seagate ST2000DM001-1ER164 2TB    | 4        | 0.93%   |
| Samsung SSD 970 EVO Plus 1TB      | 4        | 0.93%   |
| Samsung SSD 970 EVO 500GB         | 4        | 0.93%   |
| Kingston SV300S37A240G 240GB SSD  | 4        | 0.93%   |
| WDC WDS500G3X0C-00SJG0 500GB      | 3        | 0.7%    |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 3        | 0.7%    |
| WDC WD40EFRX-68N32N0 4TB          | 3        | 0.7%    |
| WDC WD10EZEX-08WN4A0 1TB          | 3        | 0.7%    |
| WDC WD10EZEX-00BN5A0 1TB          | 3        | 0.7%    |
| Seagate ST3000DM001-1CH166 3TB    | 3        | 0.7%    |
| SanDisk SD8SBAT128G1122 128GB SSD | 3        | 0.7%    |
| Samsung SSD 980 PRO 1TB           | 3        | 0.7%    |
| Kingston SV300S37A120G 120GB SSD  | 3        | 0.7%    |
| Kingston SA400S37240G 240GB SSD   | 3        | 0.7%    |
| Hitachi HUS724040ALE641 4TB       | 3        | 0.7%    |
| Crucial CT500P1SSD8 500GB         | 3        | 0.7%    |
| Crucial CT500MX500SSD1 500GB      | 3        | 0.7%    |
| Crucial CT240BX500SSD1 240GB      | 3        | 0.7%    |
| Crucial CT1000MX500SSD1 1TB       | 3        | 0.7%    |
| WDC WDS500G2B0C-00PXH0 500GB      | 2        | 0.47%   |
| WDC WD5000AADS-00S9B0 500GB       | 2        | 0.47%   |
| WDC WD20EZAZ-00GGJB0 2TB          | 2        | 0.47%   |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 0.47%   |
| WDC WD20EARX-00PASB0 2TB          | 2        | 0.47%   |
| WDC WD20EARS-00MVWB0 2TB          | 2        | 0.47%   |
| WDC WD10EFRX-68FYTN0 1TB          | 2        | 0.47%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 2        | 0.47%   |
| Seagate ST4000DM000-1F2168 4TB    | 2        | 0.47%   |
| Seagate ST3320620A 320GB          | 2        | 0.47%   |
| Seagate ST3160815AS 160GB         | 2        | 0.47%   |
| Seagate ST2000DM006-2DM164 2TB    | 2        | 0.47%   |
| Seagate ST1000DM003-1CH162 1TB    | 2        | 0.47%   |
| Seagate BUP Slim BL 2TB           | 2        | 0.47%   |
| Seagate Backup+ Hub BK 500GB      | 2        | 0.47%   |
| Sandisk NVMe SSD Drive 1TB        | 2        | 0.47%   |
| Samsung SSD 960 EVO 250GB         | 2        | 0.47%   |
| Samsung SSD 860 EVO 500GB         | 2        | 0.47%   |
| Samsung SSD 860 EVO 2TB           | 2        | 0.47%   |
| Samsung SSD 860 EVO 250GB         | 2        | 0.47%   |
| Samsung SSD 840 PRO Series 256GB  | 2        | 0.47%   |
| Samsung SSD 840 EVO 250GB         | 2        | 0.47%   |
| Samsung HD103SJ 1TB               | 2        | 0.47%   |
| SABRENT Disk 500GB                | 2        | 0.47%   |
| Phison PCIe SSD 1TB               | 2        | 0.47%   |
| Kingston SUV500240G 240GB SSD     | 2        | 0.47%   |
| Intel SSDPEKNW010T9 1TB           | 2        | 0.47%   |
| Intel NVMe SSD Drive 1024GB       | 2        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 69       | 106    | 40.12%  |
| WDC                 | 59       | 95     | 34.3%   |
| Toshiba             | 18       | 32     | 10.47%  |
| Hitachi             | 11       | 12     | 6.4%    |
| Samsung Electronics | 7        | 8      | 4.07%   |
| HGST                | 5        | 7      | 2.91%   |
| NAS                 | 1        | 5      | 0.58%   |
| MAXTOR              | 1        | 1      | 0.58%   |
| MaxDigital          | 1        | 2      | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 69       | 106    | 40.12%  |
| WDC                 | 59       | 95     | 34.3%   |
| Toshiba             | 18       | 32     | 10.47%  |
| Hitachi             | 11       | 12     | 6.4%    |
| Samsung Electronics | 7        | 8      | 4.07%   |
| HGST                | 5        | 7      | 2.91%   |
| NAS                 | 1        | 5      | 0.58%   |
| MAXTOR              | 1        | 1      | 0.58%   |
| MaxDigital          | 1        | 2      | 0.58%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 32       | 45     | 26.23%  |
| Kingston            | 22       | 26     | 18.03%  |
| Crucial             | 19       | 21     | 15.57%  |
| WDC                 | 10       | 11     | 8.2%    |
| SanDisk             | 9        | 11     | 7.38%   |
| A-DATA Technology   | 5        | 6      | 4.1%    |
| SPCC                | 4        | 4      | 3.28%   |
| PNY                 | 3        | 3      | 2.46%   |
| Toshiba             | 2        | 4      | 1.64%   |
| SABRENT             | 2        | 2      | 1.64%   |
| Unknown             | 1        | 1      | 0.82%   |
| Transcend           | 1        | 2      | 0.82%   |
| Team                | 1        | 1      | 0.82%   |
| T-FORCE             | 1        | 1      | 0.82%   |
| Seagate             | 1        | 1      | 0.82%   |
| Patriot             | 1        | 1      | 0.82%   |
| OCZ                 | 1        | 1      | 0.82%   |
| Netac               | 1        | 1      | 0.82%   |
| Micron Technology   | 1        | 1      | 0.82%   |
| Lexar               | 1        | 1      | 0.82%   |
| KingDian            | 1        | 1      | 0.82%   |
| Gigabyte Technology | 1        | 1      | 0.82%   |
| DOGFISH             | 1        | 1      | 0.82%   |
| China               | 1        | 1      | 0.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 32       | 45     | 26.23%  |
| Kingston            | 22       | 26     | 18.03%  |
| Crucial             | 19       | 21     | 15.57%  |
| WDC                 | 10       | 11     | 8.2%    |
| SanDisk             | 9        | 11     | 7.38%   |
| A-DATA Technology   | 5        | 6      | 4.1%    |
| SPCC                | 4        | 4      | 3.28%   |
| PNY                 | 3        | 3      | 2.46%   |
| Toshiba             | 2        | 4      | 1.64%   |
| SABRENT             | 2        | 2      | 1.64%   |
| Unknown             | 1        | 1      | 0.82%   |
| Transcend           | 1        | 2      | 0.82%   |
| Team                | 1        | 1      | 0.82%   |
| T-FORCE             | 1        | 1      | 0.82%   |
| Seagate             | 1        | 1      | 0.82%   |
| Patriot             | 1        | 1      | 0.82%   |
| OCZ                 | 1        | 1      | 0.82%   |
| Netac               | 1        | 1      | 0.82%   |
| Micron Technology   | 1        | 1      | 0.82%   |
| Lexar               | 1        | 1      | 0.82%   |
| KingDian            | 1        | 1      | 0.82%   |
| Gigabyte Technology | 1        | 1      | 0.82%   |
| DOGFISH             | 1        | 1      | 0.82%   |
| China               | 1        | 1      | 0.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 135      | 268    | 42.59%  |
| SSD     | 111      | 148    | 35.02%  |
| NVMe    | 64       | 87     | 20.19%  |
| Unknown | 6        | 14     | 1.89%   |
| MMC     | 1        | 1      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 135      | 268    | 42.59%  |
| SSD     | 111      | 148    | 35.02%  |
| NVMe    | 64       | 87     | 20.19%  |
| Unknown | 6        | 14     | 1.89%   |
| MMC     | 1        | 1      | 0.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 172      | 407    | 68.53%  |
| NVMe | 64       | 87     | 25.5%   |
| SAS  | 14       | 23     | 5.58%   |
| MMC  | 1        | 1      | 0.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 172      | 407    | 68.53%  |
| NVMe | 64       | 87     | 25.5%   |
| SAS  | 14       | 23     | 5.58%   |
| MMC  | 1        | 1      | 0.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 119      | 177    | 44.07%  |
| 0.51-1.0   | 70       | 95     | 25.93%  |
| 1.01-2.0   | 41       | 56     | 15.19%  |
| 3.01-4.0   | 17       | 43     | 6.3%    |
| 2.01-3.0   | 11       | 18     | 4.07%   |
| 4.01-10.0  | 10       | 24     | 3.7%    |
| 10.01-20.0 | 2        | 3      | 0.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 119      | 177    | 44.07%  |
| 0.51-1.0   | 70       | 95     | 25.93%  |
| 1.01-2.0   | 41       | 56     | 15.19%  |
| 3.01-4.0   | 17       | 43     | 6.3%    |
| 2.01-3.0   | 11       | 18     | 4.07%   |
| 4.01-10.0  | 10       | 24     | 3.7%    |
| 10.01-20.0 | 2        | 3      | 0.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 35       | 18.42%  |
| 251-500        | 29       | 15.26%  |
| 101-250        | 25       | 13.16%  |
| 501-1000       | 24       | 12.63%  |
| 1001-2000      | 23       | 12.11%  |
| 1-20           | 20       | 10.53%  |
| 2001-3000      | 13       | 6.84%   |
| 51-100         | 9        | 4.74%   |
| Unknown        | 7        | 3.68%   |
| 21-50          | 5        | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 35       | 18.42%  |
| 251-500        | 29       | 15.26%  |
| 101-250        | 25       | 13.16%  |
| 501-1000       | 24       | 12.63%  |
| 1001-2000      | 23       | 12.11%  |
| 1-20           | 20       | 10.53%  |
| 2001-3000      | 13       | 6.84%   |
| 51-100         | 9        | 4.74%   |
| Unknown        | 7        | 3.68%   |
| 21-50          | 5        | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 52       | 27.23%  |
| 501-1000       | 22       | 11.52%  |
| 101-250        | 21       | 10.99%  |
| 251-500        | 19       | 9.95%   |
| 21-50          | 16       | 8.38%   |
| 1001-2000      | 16       | 8.38%   |
| More than 3000 | 15       | 7.85%   |
| 51-100         | 15       | 7.85%   |
| 2001-3000      | 7        | 3.66%   |
| Unknown        | 7        | 3.66%   |
| 0              | 1        | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 52       | 27.23%  |
| 501-1000       | 22       | 11.52%  |
| 101-250        | 21       | 10.99%  |
| 251-500        | 19       | 9.95%   |
| 21-50          | 16       | 8.38%   |
| 1001-2000      | 16       | 8.38%   |
| More than 3000 | 15       | 7.85%   |
| 51-100         | 15       | 7.85%   |
| 2001-3000      | 7        | 3.66%   |
| Unknown        | 7        | 3.66%   |
| 0              | 1        | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 4.08%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 4.08%   |
| WDC WD5003ABYX-18WERA0 500GB          | 1        | 2      | 2.04%   |
| WDC WD5000AAKX-00U6AA0 500GB          | 1        | 1      | 2.04%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 2.04%   |
| WDC WD5000AAKS-22V1A0 500GB           | 1        | 1      | 2.04%   |
| WDC WD5000AAJS-22A8B0 500GB           | 1        | 1      | 2.04%   |
| WDC WD40EFZX-68AWUN0 4TB              | 1        | 6      | 2.04%   |
| WDC WD400BB-00DEA0 40GB               | 1        | 1      | 2.04%   |
| WDC WD30EZRX-00AZ6B0 3TB              | 1        | 1      | 2.04%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 2.04%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 2.04%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1        | 1      | 2.04%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1        | 1      | 2.04%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 2.04%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 2.04%   |
| WDC WD1001FALS-75J7B0 1TB             | 1        | 1      | 2.04%   |
| Toshiba MK2565GSX 250GB               | 1        | 1      | 2.04%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 2.04%   |
| SK Hynix PC401 NVMe 512GB             | 1        | 2      | 2.04%   |
| Seagate ST3320620A 320GB              | 1        | 1      | 2.04%   |
| Seagate ST3200827AS 200GB             | 1        | 2      | 2.04%   |
| Seagate ST32000542AS 2TB              | 1        | 1      | 2.04%   |
| Seagate ST3160813AS 160GB             | 1        | 1      | 2.04%   |
| Seagate ST31500341AS 1TB              | 1        | 1      | 2.04%   |
| Seagate ST3120827AS 120GB             | 1        | 2      | 2.04%   |
| Seagate ST31000333AS 1TB              | 1        | 1      | 2.04%   |
| Seagate ST3000DM001-9YN166 320GB      | 1        | 1      | 2.04%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 2.04%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 2.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 2.04%   |
| Seagate ST1000DM003-9YN162 1TB        | 1        | 1      | 2.04%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 2.04%   |
| SanDisk SSD PLUS 120 GB               | 1        | 1      | 2.04%   |
| Samsung Electronics SSD 970 EVO 250GB | 1        | 1      | 2.04%   |
| Samsung Electronics SP0842N 80GB      | 1        | 1      | 2.04%   |
| Samsung Electronics HD161GJ 160GB     | 1        | 1      | 2.04%   |
| PNY SSD2SC240G3LC709B121-460P 240GB   | 1        | 1      | 2.04%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 2.04%   |
| Kingston SE100S3100G 100GB SSD        | 1        | 1      | 2.04%   |
| KingDian S280 240GB                   | 1        | 1      | 2.04%   |
| Intel SSDPEKKW010T7 1TB               | 1        | 2      | 2.04%   |
| Hitachi HUA722020ALA331 2TB           | 1        | 1      | 2.04%   |
| Hitachi HDS722525VLAT80 250GB         | 1        | 1      | 2.04%   |
| Crucial CT128MX100SSD1 128GB          | 1        | 1      | 2.04%   |
| A-DATA Technology SU800 256GB SSD     | 1        | 2      | 2.04%   |
| A-DATA Technology SSD DP900 128GB-DL3 | 1        | 1      | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 4.08%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 4.08%   |
| WDC WD5003ABYX-18WERA0 500GB          | 1        | 2      | 2.04%   |
| WDC WD5000AAKX-00U6AA0 500GB          | 1        | 1      | 2.04%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 2.04%   |
| WDC WD5000AAKS-22V1A0 500GB           | 1        | 1      | 2.04%   |
| WDC WD5000AAJS-22A8B0 500GB           | 1        | 1      | 2.04%   |
| WDC WD40EFZX-68AWUN0 4TB              | 1        | 6      | 2.04%   |
| WDC WD400BB-00DEA0 40GB               | 1        | 1      | 2.04%   |
| WDC WD30EZRX-00AZ6B0 3TB              | 1        | 1      | 2.04%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 2.04%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 2.04%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1        | 1      | 2.04%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1        | 1      | 2.04%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 2.04%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 2.04%   |
| WDC WD1001FALS-75J7B0 1TB             | 1        | 1      | 2.04%   |
| Toshiba MK2565GSX 250GB               | 1        | 1      | 2.04%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 2.04%   |
| SK Hynix PC401 NVMe 512GB             | 1        | 2      | 2.04%   |
| Seagate ST3320620A 320GB              | 1        | 1      | 2.04%   |
| Seagate ST3200827AS 200GB             | 1        | 2      | 2.04%   |
| Seagate ST32000542AS 2TB              | 1        | 1      | 2.04%   |
| Seagate ST3160813AS 160GB             | 1        | 1      | 2.04%   |
| Seagate ST31500341AS 1TB              | 1        | 1      | 2.04%   |
| Seagate ST3120827AS 120GB             | 1        | 2      | 2.04%   |
| Seagate ST31000333AS 1TB              | 1        | 1      | 2.04%   |
| Seagate ST3000DM001-9YN166 320GB      | 1        | 1      | 2.04%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 2.04%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 2.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 2.04%   |
| Seagate ST1000DM003-9YN162 1TB        | 1        | 1      | 2.04%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 2.04%   |
| SanDisk SSD PLUS 120 GB               | 1        | 1      | 2.04%   |
| Samsung Electronics SSD 970 EVO 250GB | 1        | 1      | 2.04%   |
| Samsung Electronics SP0842N 80GB      | 1        | 1      | 2.04%   |
| Samsung Electronics HD161GJ 160GB     | 1        | 1      | 2.04%   |
| PNY SSD2SC240G3LC709B121-460P 240GB   | 1        | 1      | 2.04%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 2.04%   |
| Kingston SE100S3100G 100GB SSD        | 1        | 1      | 2.04%   |
| KingDian S280 240GB                   | 1        | 1      | 2.04%   |
| Intel SSDPEKKW010T7 1TB               | 1        | 2      | 2.04%   |
| Hitachi HUA722020ALA331 2TB           | 1        | 1      | 2.04%   |
| Hitachi HDS722525VLAT80 250GB         | 1        | 1      | 2.04%   |
| Crucial CT128MX100SSD1 128GB          | 1        | 1      | 2.04%   |
| A-DATA Technology SU800 256GB SSD     | 1        | 2      | 2.04%   |
| A-DATA Technology SSD DP900 128GB-DL3 | 1        | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 24     | 36.17%  |
| Seagate             | 13       | 17     | 27.66%  |
| Samsung Electronics | 3        | 3      | 6.38%   |
| Toshiba             | 2        | 2      | 4.26%   |
| Kingston            | 2        | 2      | 4.26%   |
| Hitachi             | 2        | 2      | 4.26%   |
| A-DATA Technology   | 2        | 3      | 4.26%   |
| SK Hynix            | 1        | 2      | 2.13%   |
| SanDisk             | 1        | 1      | 2.13%   |
| PNY                 | 1        | 1      | 2.13%   |
| KingDian            | 1        | 1      | 2.13%   |
| Intel               | 1        | 2      | 2.13%   |
| Crucial             | 1        | 1      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 24     | 36.17%  |
| Seagate             | 13       | 17     | 27.66%  |
| Samsung Electronics | 3        | 3      | 6.38%   |
| Toshiba             | 2        | 2      | 4.26%   |
| Kingston            | 2        | 2      | 4.26%   |
| Hitachi             | 2        | 2      | 4.26%   |
| A-DATA Technology   | 2        | 3      | 4.26%   |
| SK Hynix            | 1        | 2      | 2.13%   |
| SanDisk             | 1        | 1      | 2.13%   |
| PNY                 | 1        | 1      | 2.13%   |
| KingDian            | 1        | 1      | 2.13%   |
| Intel               | 1        | 2      | 2.13%   |
| Crucial             | 1        | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 24     | 47.22%  |
| Seagate             | 13       | 17     | 36.11%  |
| Toshiba             | 2        | 2      | 5.56%   |
| Samsung Electronics | 2        | 2      | 5.56%   |
| Hitachi             | 2        | 2      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 24     | 47.22%  |
| Seagate             | 13       | 17     | 36.11%  |
| Toshiba             | 2        | 2      | 5.56%   |
| Samsung Electronics | 2        | 2      | 5.56%   |
| Hitachi             | 2        | 2      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 35       | 47     | 76.09%  |
| SSD  | 8        | 9      | 17.39%  |
| NVMe | 3        | 5      | 6.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 35       | 47     | 76.09%  |
| SSD  | 8        | 9      | 17.39%  |
| NVMe | 3        | 5      | 6.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM005 HD502HJ 500GB | 1        | 1      | 50%     |
| Seagate ST3500830AS 500GB        | 1        | 1      | 50%     |

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
| Works    | 166      | 392    | 70.04%  |
| Malfunc  | 43       | 61     | 18.14%  |
| Detected | 26       | 63     | 10.97%  |
| Failed   | 2        | 2      | 0.84%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 166      | 392    | 70.04%  |
| Malfunc  | 43       | 61     | 18.14%  |
| Detected | 26       | 63     | 10.97%  |
| Failed   | 2        | 2      | 0.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 109      | 39.64%  |
| AMD                         | 79       | 28.73%  |
| Samsung Electronics         | 27       | 9.82%   |
| Sandisk                     | 10       | 3.64%   |
| Phison Electronics          | 10       | 3.64%   |
| ASMedia Technology          | 8        | 2.91%   |
| Micron/Crucial Technology   | 7        | 2.55%   |
| Marvell Technology Group    | 6        | 2.18%   |
| JMicron Technology          | 5        | 1.82%   |
| VIA Technologies            | 2        | 0.73%   |
| Nvidia                      | 2        | 0.73%   |
| Broadcom / LSI              | 2        | 0.73%   |
| SK Hynix                    | 1        | 0.36%   |
| Silicon Motion              | 1        | 0.36%   |
| Silicon Image               | 1        | 0.36%   |
| Seagate Technology          | 1        | 0.36%   |
| Micron Technology           | 1        | 0.36%   |
| Kingston Technology Company | 1        | 0.36%   |
| ADATA Technology            | 1        | 0.36%   |
| Adaptec                     | 1        | 0.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 109      | 39.64%  |
| AMD                         | 79       | 28.73%  |
| Samsung Electronics         | 27       | 9.82%   |
| Sandisk                     | 10       | 3.64%   |
| Phison Electronics          | 10       | 3.64%   |
| ASMedia Technology          | 8        | 2.91%   |
| Micron/Crucial Technology   | 7        | 2.55%   |
| Marvell Technology Group    | 6        | 2.18%   |
| JMicron Technology          | 5        | 1.82%   |
| VIA Technologies            | 2        | 0.73%   |
| Nvidia                      | 2        | 0.73%   |
| Broadcom / LSI              | 2        | 0.73%   |
| SK Hynix                    | 1        | 0.36%   |
| Silicon Motion              | 1        | 0.36%   |
| Silicon Image               | 1        | 0.36%   |
| Seagate Technology          | 1        | 0.36%   |
| Micron Technology           | 1        | 0.36%   |
| Kingston Technology Company | 1        | 0.36%   |
| ADATA Technology            | 1        | 0.36%   |
| Adaptec                     | 1        | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 51       | 14.37%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 19       | 5.35%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19       | 5.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 15       | 4.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 3.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12       | 3.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 2.82%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 9        | 2.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 2.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 1.97%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 1.97%   |
| Phison E12 NVMe Controller                                                              | 6        | 1.69%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 1.69%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 1.41%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 5        | 1.41%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 1.41%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 1.41%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4        | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.13%   |
| AMD X399 Series Chipset SATA Controller                                                 | 4        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.13%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 0.85%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 0.85%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 0.85%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 0.85%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.85%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.85%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 0.85%   |
| AMD X370 Series Chipset SATA Controller                                                 | 3        | 0.85%   |
| AMD FCH SATA Controller D                                                               | 3        | 0.85%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.56%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.56%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.56%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.56%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.56%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.56%   |
| Intel SSD 660P Series                                                                   | 2        | 0.56%   |
| Intel SSD 600P Series                                                                   | 2        | 0.56%   |
| Intel NVMe Optane Memory Series                                                         | 2        | 0.56%   |
| Intel Non-Volatile memory controller                                                    | 2        | 0.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 0.56%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.56%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.56%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 0.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.56%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.56%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.56%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.28%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                             | 1        | 0.28%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.28%   |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.28%   |
| Seagate FireCuda 510 SSD                                                                | 1        | 0.28%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 0.28%   |
| Sandisk WD Black SN850                                                                  | 1        | 0.28%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 51       | 14.37%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 19       | 5.35%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19       | 5.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 15       | 4.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 3.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12       | 3.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 2.82%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 9        | 2.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 2.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 1.97%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 1.97%   |
| Phison E12 NVMe Controller                                                              | 6        | 1.69%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 1.69%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 1.41%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 5        | 1.41%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 1.41%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 1.41%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4        | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.13%   |
| AMD X399 Series Chipset SATA Controller                                                 | 4        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.13%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 0.85%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 0.85%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 0.85%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 0.85%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.85%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.85%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 0.85%   |
| AMD X370 Series Chipset SATA Controller                                                 | 3        | 0.85%   |
| AMD FCH SATA Controller D                                                               | 3        | 0.85%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.56%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.56%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.56%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.56%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.56%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.56%   |
| Intel SSD 660P Series                                                                   | 2        | 0.56%   |
| Intel SSD 600P Series                                                                   | 2        | 0.56%   |
| Intel NVMe Optane Memory Series                                                         | 2        | 0.56%   |
| Intel Non-Volatile memory controller                                                    | 2        | 0.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 0.56%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.56%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.56%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 0.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.56%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.56%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.56%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.28%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                             | 1        | 0.28%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.28%   |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.28%   |
| Seagate FireCuda 510 SSD                                                                | 1        | 0.28%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 0.28%   |
| Sandisk WD Black SN850                                                                  | 1        | 0.28%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 163      | 57.8%   |
| NVMe | 64       | 22.7%   |
| IDE  | 38       | 13.48%  |
| RAID | 12       | 4.26%   |
| SAS  | 5        | 1.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 163      | 57.8%   |
| NVMe | 64       | 22.7%   |
| IDE  | 38       | 13.48%  |
| RAID | 12       | 4.26%   |
| SAS  | 5        | 1.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 109      | 57.37%  |
| AMD    | 81       | 42.63%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 109      | 57.37%  |
| AMD    | 81       | 42.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 10       | 5.26%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 4        | 2.11%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 4        | 2.11%   |
| Intel Core i7-7700 CPU @ 3.60GHz               | 3        | 1.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 3        | 1.58%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 3        | 1.58%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 3        | 1.58%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 3        | 1.58%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 3        | 1.58%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 3        | 1.58%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 3        | 1.58%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz         | 2        | 1.05%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 1.05%   |
| Intel Core i7-8086K CPU @ 4.00GHz              | 2        | 1.05%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 2        | 1.05%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 2        | 1.05%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 2        | 1.05%   |
| Intel Core i5-6600 CPU @ 3.30GHz               | 2        | 1.05%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 2        | 1.05%   |
| Intel Core i5-4460 CPU @ 3.20GHz               | 2        | 1.05%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 2        | 1.05%   |
| Intel Core i5 CPU 650 @ 3.20GHz                | 2        | 1.05%   |
| Intel Core i3-10100 CPU @ 3.60GHz              | 2        | 1.05%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 2        | 1.05%   |
| AMD Ryzen Threadripper 2950X 16-Core Processor | 2        | 1.05%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 2        | 1.05%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 2        | 1.05%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 1.05%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 2        | 1.05%   |
| AMD Ryzen 3 1200 Quad-Core Processor           | 2        | 1.05%   |
| AMD Phenom II X4 965 Processor                 | 2        | 1.05%   |
| AMD FX-8350 Eight-Core Processor               | 2        | 1.05%   |
| AMD FX-8120 Eight-Core Processor               | 2        | 1.05%   |
| AMD FX-4300 Quad-Core Processor                | 2        | 1.05%   |
| Intel Xeon W-2145 CPU @ 3.70GHz                | 1        | 0.53%   |
| Intel Xeon CPU W3503 @ 2.40GHz                 | 1        | 0.53%   |
| Intel Xeon CPU E5-2699 v4 @ 2.20GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz             | 1        | 0.53%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz             | 1        | 0.53%   |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz             | 1        | 0.53%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz             | 1        | 0.53%   |
| Intel Xeon CPU E3-1230 v6 @ 3.50GHz            | 1        | 0.53%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz    | 1        | 0.53%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 1        | 0.53%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1        | 0.53%   |
| Intel Pentium CPU N3700 @ 1.60GHz              | 1        | 0.53%   |
| Intel Pentium CPU G3258 @ 3.20GHz              | 1        | 0.53%   |
| Intel Pentium CPU G3250 @ 3.20GHz              | 1        | 0.53%   |
| Intel Pentium CPU G2030 @ 3.00GHz              | 1        | 0.53%   |
| Intel Pentium 4 CPU 3.06GHz                    | 1        | 0.53%   |
| Intel Pentium 4 CPU 2.80GHz                    | 1        | 0.53%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 1        | 0.53%   |
| Intel Core i7-9700F CPU @ 3.00GHz              | 1        | 0.53%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 0.53%   |
| Intel Core i7-5930K CPU @ 3.50GHz              | 1        | 0.53%   |
| Intel Core i7-4820K CPU @ 3.70GHz              | 1        | 0.53%   |
| Intel Core i7-4790S CPU @ 3.20GHz              | 1        | 0.53%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 10       | 5.26%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 4        | 2.11%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 4        | 2.11%   |
| Intel Core i7-7700 CPU @ 3.60GHz               | 3        | 1.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 3        | 1.58%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 3        | 1.58%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 3        | 1.58%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 3        | 1.58%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 3        | 1.58%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 3        | 1.58%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 3        | 1.58%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz         | 2        | 1.05%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 1.05%   |
| Intel Core i7-8086K CPU @ 4.00GHz              | 2        | 1.05%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 2        | 1.05%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 2        | 1.05%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 2        | 1.05%   |
| Intel Core i5-6600 CPU @ 3.30GHz               | 2        | 1.05%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 2        | 1.05%   |
| Intel Core i5-4460 CPU @ 3.20GHz               | 2        | 1.05%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 2        | 1.05%   |
| Intel Core i5 CPU 650 @ 3.20GHz                | 2        | 1.05%   |
| Intel Core i3-10100 CPU @ 3.60GHz              | 2        | 1.05%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 2        | 1.05%   |
| AMD Ryzen Threadripper 2950X 16-Core Processor | 2        | 1.05%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 2        | 1.05%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 2        | 1.05%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 1.05%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 2        | 1.05%   |
| AMD Ryzen 3 1200 Quad-Core Processor           | 2        | 1.05%   |
| AMD Phenom II X4 965 Processor                 | 2        | 1.05%   |
| AMD FX-8350 Eight-Core Processor               | 2        | 1.05%   |
| AMD FX-8120 Eight-Core Processor               | 2        | 1.05%   |
| AMD FX-4300 Quad-Core Processor                | 2        | 1.05%   |
| Intel Xeon W-2145 CPU @ 3.70GHz                | 1        | 0.53%   |
| Intel Xeon CPU W3503 @ 2.40GHz                 | 1        | 0.53%   |
| Intel Xeon CPU E5-2699 v4 @ 2.20GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz             | 1        | 0.53%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz             | 1        | 0.53%   |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz             | 1        | 0.53%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz             | 1        | 0.53%   |
| Intel Xeon CPU E3-1230 v6 @ 3.50GHz            | 1        | 0.53%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz    | 1        | 0.53%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 1        | 0.53%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1        | 0.53%   |
| Intel Pentium CPU N3700 @ 1.60GHz              | 1        | 0.53%   |
| Intel Pentium CPU G3258 @ 3.20GHz              | 1        | 0.53%   |
| Intel Pentium CPU G3250 @ 3.20GHz              | 1        | 0.53%   |
| Intel Pentium CPU G2030 @ 3.00GHz              | 1        | 0.53%   |
| Intel Pentium 4 CPU 3.06GHz                    | 1        | 0.53%   |
| Intel Pentium 4 CPU 2.80GHz                    | 1        | 0.53%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 1        | 0.53%   |
| Intel Core i7-9700F CPU @ 3.00GHz              | 1        | 0.53%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 0.53%   |
| Intel Core i7-5930K CPU @ 3.50GHz              | 1        | 0.53%   |
| Intel Core i7-4820K CPU @ 3.70GHz              | 1        | 0.53%   |
| Intel Core i7-4790S CPU @ 3.20GHz              | 1        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 35       | 18.42%  |
| Intel Core i7           | 25       | 13.16%  |
| AMD Ryzen 5             | 23       | 12.11%  |
| AMD Ryzen 7             | 15       | 7.89%   |
| Intel Xeon              | 11       | 5.79%   |
| AMD FX                  | 9        | 4.74%   |
| Intel Core i3           | 7        | 3.68%   |
| Intel Core 2 Duo        | 6        | 3.16%   |
| Intel Celeron           | 6        | 3.16%   |
| AMD Ryzen Threadripper  | 6        | 3.16%   |
| Intel Pentium           | 4        | 2.11%   |
| AMD Ryzen 9             | 4        | 2.11%   |
| AMD Ryzen 3             | 4        | 2.11%   |
| AMD Phenom II X4        | 4        | 2.11%   |
| Intel Pentium Dual-Core | 3        | 1.58%   |
| Intel Core 2 Quad       | 3        | 1.58%   |
| Intel Pentium Gold      | 2        | 1.05%   |
| Intel Pentium 4         | 2        | 1.05%   |
| Intel Core 2            | 2        | 1.05%   |
| AMD Athlon X4           | 2        | 1.05%   |
| AMD A10                 | 2        | 1.05%   |
| Other                   | 1        | 0.53%   |
| Intel Core i9           | 1        | 0.53%   |
| Intel Atom              | 1        | 0.53%   |
| AMD Sempron             | 1        | 0.53%   |
| AMD PRO A8              | 1        | 0.53%   |
| AMD Phenom II X3        | 1        | 0.53%   |
| AMD GX                  | 1        | 0.53%   |
| AMD E1                  | 1        | 0.53%   |
| AMD Athlon XP           | 1        | 0.53%   |
| AMD Athlon II X2        | 1        | 0.53%   |
| AMD Athlon II Neo       | 1        | 0.53%   |
| AMD Athlon Dual Core    | 1        | 0.53%   |
| AMD A8                  | 1        | 0.53%   |
| AMD A6                  | 1        | 0.53%   |
| AMD A4                  | 1        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 35       | 18.42%  |
| Intel Core i7           | 25       | 13.16%  |
| AMD Ryzen 5             | 23       | 12.11%  |
| AMD Ryzen 7             | 15       | 7.89%   |
| Intel Xeon              | 11       | 5.79%   |
| AMD FX                  | 9        | 4.74%   |
| Intel Core i3           | 7        | 3.68%   |
| Intel Core 2 Duo        | 6        | 3.16%   |
| Intel Celeron           | 6        | 3.16%   |
| AMD Ryzen Threadripper  | 6        | 3.16%   |
| Intel Pentium           | 4        | 2.11%   |
| AMD Ryzen 9             | 4        | 2.11%   |
| AMD Ryzen 3             | 4        | 2.11%   |
| AMD Phenom II X4        | 4        | 2.11%   |
| Intel Pentium Dual-Core | 3        | 1.58%   |
| Intel Core 2 Quad       | 3        | 1.58%   |
| Intel Pentium Gold      | 2        | 1.05%   |
| Intel Pentium 4         | 2        | 1.05%   |
| Intel Core 2            | 2        | 1.05%   |
| AMD Athlon X4           | 2        | 1.05%   |
| AMD A10                 | 2        | 1.05%   |
| Other                   | 1        | 0.53%   |
| Intel Core i9           | 1        | 0.53%   |
| Intel Atom              | 1        | 0.53%   |
| AMD Sempron             | 1        | 0.53%   |
| AMD PRO A8              | 1        | 0.53%   |
| AMD Phenom II X3        | 1        | 0.53%   |
| AMD GX                  | 1        | 0.53%   |
| AMD E1                  | 1        | 0.53%   |
| AMD Athlon XP           | 1        | 0.53%   |
| AMD Athlon II X2        | 1        | 0.53%   |
| AMD Athlon II Neo       | 1        | 0.53%   |
| AMD Athlon Dual Core    | 1        | 0.53%   |
| AMD A8                  | 1        | 0.53%   |
| AMD A6                  | 1        | 0.53%   |
| AMD A4                  | 1        | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 67       | 35.26%  |
| 2      | 42       | 22.11%  |
| 6      | 35       | 18.42%  |
| 8      | 24       | 12.63%  |
| 1      | 7        | 3.68%   |
| 16     | 5        | 2.63%   |
| 12     | 5        | 2.63%   |
| 44     | 1        | 0.53%   |
| 32     | 1        | 0.53%   |
| 28     | 1        | 0.53%   |
| 24     | 1        | 0.53%   |
| 3      | 1        | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 67       | 35.26%  |
| 2      | 42       | 22.11%  |
| 6      | 35       | 18.42%  |
| 8      | 24       | 12.63%  |
| 1      | 7        | 3.68%   |
| 16     | 5        | 2.63%   |
| 12     | 5        | 2.63%   |
| 44     | 1        | 0.53%   |
| 32     | 1        | 0.53%   |
| 28     | 1        | 0.53%   |
| 24     | 1        | 0.53%   |
| 3      | 1        | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 187      | 98.42%  |
| 2      | 3        | 1.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 187      | 98.42%  |
| 2      | 3        | 1.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 112      | 58.95%  |
| 1      | 78       | 41.05%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 112      | 58.95%  |
| 1      | 78       | 41.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 188      | 98.95%  |
| 32-bit         | 2        | 1.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 188      | 98.95%  |
| 32-bit         | 2        | 1.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 16.75%  |
| 0x08701021 | 16       | 8.38%   |
| 0x306c3    | 15       | 7.85%   |
| 0x306a9    | 10       | 5.24%   |
| 0x906e9    | 7        | 3.66%   |
| 0x506e3    | 6        | 3.14%   |
| 0x1067a    | 6        | 3.14%   |
| 0x0800820d | 6        | 3.14%   |
| 0x06003106 | 6        | 3.14%   |
| 0x906ea    | 5        | 2.62%   |
| 0x206a7    | 5        | 2.62%   |
| 0xa0655    | 4        | 2.09%   |
| 0x206d7    | 4        | 2.09%   |
| 0x0a201009 | 4        | 2.09%   |
| 0x06000852 | 4        | 2.09%   |
| 0x306f2    | 3        | 1.57%   |
| 0x08001138 | 3        | 1.57%   |
| 0x010000c8 | 3        | 1.57%   |
| 0x010000b6 | 3        | 1.57%   |
| 0xa0653    | 2        | 1.05%   |
| 0x906ed    | 2        | 1.05%   |
| 0x6fb      | 2        | 1.05%   |
| 0x0a201016 | 2        | 1.05%   |
| 0x08701013 | 2        | 1.05%   |
| 0x08001137 | 2        | 1.05%   |
| 0x0700010f | 2        | 1.05%   |
| 0x0600063e | 2        | 1.05%   |
| 0xf49      | 1        | 0.52%   |
| 0xf41      | 1        | 0.52%   |
| 0xf29      | 1        | 0.52%   |
| 0xa0671    | 1        | 0.52%   |
| 0xa0660    | 1        | 0.52%   |
| 0x906ec    | 1        | 0.52%   |
| 0x906eb    | 1        | 0.52%   |
| 0x806e9    | 1        | 0.52%   |
| 0x706a1    | 1        | 0.52%   |
| 0x6fd      | 1        | 0.52%   |
| 0x6f6      | 1        | 0.52%   |
| 0x6f2      | 1        | 0.52%   |
| 0x50654    | 1        | 0.52%   |
| 0x406f1    | 1        | 0.52%   |
| 0x406d8    | 1        | 0.52%   |
| 0x406c3    | 1        | 0.52%   |
| 0x40651    | 1        | 0.52%   |
| 0x306e4    | 1        | 0.52%   |
| 0x30678    | 1        | 0.52%   |
| 0x30673    | 1        | 0.52%   |
| 0x20655    | 1        | 0.52%   |
| 0x106e5    | 1        | 0.52%   |
| 0x106a5    | 1        | 0.52%   |
| 0x0830104d | 1        | 0.52%   |
| 0x08301039 | 1        | 0.52%   |
| 0x08108109 | 1        | 0.52%   |
| 0x08101016 | 1        | 0.52%   |
| 0x0800820b | 1        | 0.52%   |
| 0x08001129 | 1        | 0.52%   |
| 0x06001119 | 1        | 0.52%   |
| 0x0600081c | 1        | 0.52%   |
| 0x0600063d | 1        | 0.52%   |
| 0x010000db | 1        | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 16.75%  |
| 0x08701021 | 16       | 8.38%   |
| 0x306c3    | 15       | 7.85%   |
| 0x306a9    | 10       | 5.24%   |
| 0x906e9    | 7        | 3.66%   |
| 0x506e3    | 6        | 3.14%   |
| 0x1067a    | 6        | 3.14%   |
| 0x0800820d | 6        | 3.14%   |
| 0x06003106 | 6        | 3.14%   |
| 0x906ea    | 5        | 2.62%   |
| 0x206a7    | 5        | 2.62%   |
| 0xa0655    | 4        | 2.09%   |
| 0x206d7    | 4        | 2.09%   |
| 0x0a201009 | 4        | 2.09%   |
| 0x06000852 | 4        | 2.09%   |
| 0x306f2    | 3        | 1.57%   |
| 0x08001138 | 3        | 1.57%   |
| 0x010000c8 | 3        | 1.57%   |
| 0x010000b6 | 3        | 1.57%   |
| 0xa0653    | 2        | 1.05%   |
| 0x906ed    | 2        | 1.05%   |
| 0x6fb      | 2        | 1.05%   |
| 0x0a201016 | 2        | 1.05%   |
| 0x08701013 | 2        | 1.05%   |
| 0x08001137 | 2        | 1.05%   |
| 0x0700010f | 2        | 1.05%   |
| 0x0600063e | 2        | 1.05%   |
| 0xf49      | 1        | 0.52%   |
| 0xf41      | 1        | 0.52%   |
| 0xf29      | 1        | 0.52%   |
| 0xa0671    | 1        | 0.52%   |
| 0xa0660    | 1        | 0.52%   |
| 0x906ec    | 1        | 0.52%   |
| 0x906eb    | 1        | 0.52%   |
| 0x806e9    | 1        | 0.52%   |
| 0x706a1    | 1        | 0.52%   |
| 0x6fd      | 1        | 0.52%   |
| 0x6f6      | 1        | 0.52%   |
| 0x6f2      | 1        | 0.52%   |
| 0x50654    | 1        | 0.52%   |
| 0x406f1    | 1        | 0.52%   |
| 0x406d8    | 1        | 0.52%   |
| 0x406c3    | 1        | 0.52%   |
| 0x40651    | 1        | 0.52%   |
| 0x306e4    | 1        | 0.52%   |
| 0x30678    | 1        | 0.52%   |
| 0x30673    | 1        | 0.52%   |
| 0x20655    | 1        | 0.52%   |
| 0x106e5    | 1        | 0.52%   |
| 0x106a5    | 1        | 0.52%   |
| 0x0830104d | 1        | 0.52%   |
| 0x08301039 | 1        | 0.52%   |
| 0x08108109 | 1        | 0.52%   |
| 0x08101016 | 1        | 0.52%   |
| 0x0800820b | 1        | 0.52%   |
| 0x08001129 | 1        | 0.52%   |
| 0x06001119 | 1        | 0.52%   |
| 0x0600081c | 1        | 0.52%   |
| 0x0600063d | 1        | 0.52%   |
| 0x010000db | 1        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 25       | 13.16%  |
| Haswell       | 22       | 11.58%  |
| KabyLake      | 21       | 11.05%  |
| IvyBridge     | 13       | 6.84%   |
| Zen+          | 12       | 6.32%   |
| Skylake       | 9        | 4.74%   |
| SandyBridge   | 9        | 4.74%   |
| Zen           | 8        | 4.21%   |
| Penryn        | 8        | 4.21%   |
| K10           | 8        | 4.21%   |
| Zen 3         | 7        | 3.68%   |
| Steamroller   | 7        | 3.68%   |
| Piledriver    | 7        | 3.68%   |
| CometLake     | 7        | 3.68%   |
| Core          | 6        | 3.16%   |
| Silvermont    | 4        | 2.11%   |
| NetBurst      | 3        | 1.58%   |
| Bulldozer     | 3        | 1.58%   |
| Westmere      | 2        | 1.05%   |
| Nehalem       | 2        | 1.05%   |
| Jaguar        | 2        | 1.05%   |
| K8 Hammer     | 1        | 0.53%   |
| K6            | 1        | 0.53%   |
| Goldmont plus | 1        | 0.53%   |
| Broadwell     | 1        | 0.53%   |
| Unknown       | 1        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 25       | 13.16%  |
| Haswell       | 22       | 11.58%  |
| KabyLake      | 21       | 11.05%  |
| IvyBridge     | 13       | 6.84%   |
| Zen+          | 12       | 6.32%   |
| Skylake       | 9        | 4.74%   |
| SandyBridge   | 9        | 4.74%   |
| Zen           | 8        | 4.21%   |
| Penryn        | 8        | 4.21%   |
| K10           | 8        | 4.21%   |
| Zen 3         | 7        | 3.68%   |
| Steamroller   | 7        | 3.68%   |
| Piledriver    | 7        | 3.68%   |
| CometLake     | 7        | 3.68%   |
| Core          | 6        | 3.16%   |
| Silvermont    | 4        | 2.11%   |
| NetBurst      | 3        | 1.58%   |
| Bulldozer     | 3        | 1.58%   |
| Westmere      | 2        | 1.05%   |
| Nehalem       | 2        | 1.05%   |
| Jaguar        | 2        | 1.05%   |
| K8 Hammer     | 1        | 0.53%   |
| K6            | 1        | 0.53%   |
| Goldmont plus | 1        | 0.53%   |
| Broadwell     | 1        | 0.53%   |
| Unknown       | 1        | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 78       | 39.59%  |
| AMD                        | 62       | 31.47%  |
| Intel                      | 50       | 25.38%  |
| ASPEED Technology          | 5        | 2.54%   |
| VIA Technologies           | 1        | 0.51%   |
| Matrox Electronics Systems | 1        | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 78       | 39.59%  |
| AMD                        | 62       | 31.47%  |
| Intel                      | 50       | 25.38%  |
| ASPEED Technology          | 5        | 2.54%   |
| VIA Technologies           | 1        | 0.51%   |
| Matrox Electronics Systems | 1        | 0.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 16       | 8.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 9        | 4.55%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 8        | 4.04%   |
| Nvidia GK208B [GeForce GT 710]                                                | 7        | 3.54%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 7        | 3.54%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 7        | 3.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 5        | 2.53%   |
| ASPEED Technology ASPEED Graphics Family                                      | 5        | 2.53%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 5        | 2.53%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 4        | 2.02%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 4        | 2.02%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 4        | 2.02%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 4        | 2.02%   |
| AMD Kaveri [Radeon R7 Graphics]                                               | 4        | 2.02%   |
| Nvidia GT218 [GeForce 210]                                                    | 3        | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 3        | 1.52%   |
| Intel HD Graphics 530                                                         | 3        | 1.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3        | 1.52%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 3        | 1.52%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 2        | 1.01%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 2        | 1.01%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 2        | 1.01%   |
| Nvidia GK104 [GeForce GTX 670]                                                | 2        | 1.01%   |
| Nvidia GF104 [GeForce GTX 460]                                                | 2        | 1.01%   |
| Nvidia GA102 [GeForce RTX 3090]                                               | 2        | 1.01%   |
| Nvidia G98 [Quadro NVS 295]                                                   | 2        | 1.01%   |
| Intel HD Graphics 630                                                         | 2        | 1.01%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                     | 2        | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2        | 1.01%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                      | 2        | 1.01%   |
| AMD RS780L [Radeon 3000]                                                      | 2        | 1.01%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 2        | 1.01%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.51%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 1        | 0.51%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1        | 0.51%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 1        | 0.51%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 1        | 0.51%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                        | 1        | 0.51%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                        | 1        | 0.51%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 1        | 0.51%   |
| Nvidia GV100GL [Quadro GV100]                                                 | 1        | 0.51%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                            | 1        | 0.51%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 1        | 0.51%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 1        | 0.51%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                             | 1        | 0.51%   |
| Nvidia GK110 [GeForce GTX 780]                                                | 1        | 0.51%   |
| Nvidia GK107GL [Quadro K2000]                                                 | 1        | 0.51%   |
| Nvidia GK107 [GeForce GTX 650]                                                | 1        | 0.51%   |
| Nvidia GK106GL [Quadro K4000]                                                 | 1        | 0.51%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                             | 1        | 0.51%   |
| Nvidia GK104 [GeForce GTX 770]                                                | 1        | 0.51%   |
| Nvidia GF119 [GeForce GT 520]                                                 | 1        | 0.51%   |
| Nvidia GF119 [GeForce 605]                                                    | 1        | 0.51%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                         | 1        | 0.51%   |
| Nvidia GF110 [GeForce GTX 560 Ti 448 Cores]                                   | 1        | 0.51%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1        | 0.51%   |
| Nvidia GF108 [GeForce GT 440]                                                 | 1        | 0.51%   |
| Nvidia GF106GL [Quadro 2000]                                                  | 1        | 0.51%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                            | 1        | 0.51%   |
| Nvidia G96C [GeForce 9500 GT]                                                 | 1        | 0.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 16       | 8.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 9        | 4.55%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 8        | 4.04%   |
| Nvidia GK208B [GeForce GT 710]                                                | 7        | 3.54%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 7        | 3.54%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 7        | 3.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 5        | 2.53%   |
| ASPEED Technology ASPEED Graphics Family                                      | 5        | 2.53%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 5        | 2.53%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 4        | 2.02%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 4        | 2.02%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 4        | 2.02%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 4        | 2.02%   |
| AMD Kaveri [Radeon R7 Graphics]                                               | 4        | 2.02%   |
| Nvidia GT218 [GeForce 210]                                                    | 3        | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 3        | 1.52%   |
| Intel HD Graphics 530                                                         | 3        | 1.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3        | 1.52%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 3        | 1.52%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 2        | 1.01%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 2        | 1.01%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 2        | 1.01%   |
| Nvidia GK104 [GeForce GTX 670]                                                | 2        | 1.01%   |
| Nvidia GF104 [GeForce GTX 460]                                                | 2        | 1.01%   |
| Nvidia GA102 [GeForce RTX 3090]                                               | 2        | 1.01%   |
| Nvidia G98 [Quadro NVS 295]                                                   | 2        | 1.01%   |
| Intel HD Graphics 630                                                         | 2        | 1.01%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                     | 2        | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2        | 1.01%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                      | 2        | 1.01%   |
| AMD RS780L [Radeon 3000]                                                      | 2        | 1.01%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 2        | 1.01%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.51%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 1        | 0.51%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1        | 0.51%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 1        | 0.51%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 1        | 0.51%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                        | 1        | 0.51%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                        | 1        | 0.51%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 1        | 0.51%   |
| Nvidia GV100GL [Quadro GV100]                                                 | 1        | 0.51%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                            | 1        | 0.51%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 1        | 0.51%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 1        | 0.51%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                             | 1        | 0.51%   |
| Nvidia GK110 [GeForce GTX 780]                                                | 1        | 0.51%   |
| Nvidia GK107GL [Quadro K2000]                                                 | 1        | 0.51%   |
| Nvidia GK107 [GeForce GTX 650]                                                | 1        | 0.51%   |
| Nvidia GK106GL [Quadro K4000]                                                 | 1        | 0.51%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                             | 1        | 0.51%   |
| Nvidia GK104 [GeForce GTX 770]                                                | 1        | 0.51%   |
| Nvidia GF119 [GeForce GT 520]                                                 | 1        | 0.51%   |
| Nvidia GF119 [GeForce 605]                                                    | 1        | 0.51%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                         | 1        | 0.51%   |
| Nvidia GF110 [GeForce GTX 560 Ti 448 Cores]                                   | 1        | 0.51%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1        | 0.51%   |
| Nvidia GF108 [GeForce GT 440]                                                 | 1        | 0.51%   |
| Nvidia GF106GL [Quadro 2000]                                                  | 1        | 0.51%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                            | 1        | 0.51%   |
| Nvidia G96C [GeForce 9500 GT]                                                 | 1        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 74       | 38.95%  |
| 1 x AMD        | 59       | 31.05%  |
| 1 x Intel      | 45       | 23.68%  |
| 1 x ASPEED     | 4        | 2.11%   |
| Intel + Nvidia | 3        | 1.58%   |
| 2 x AMD        | 1        | 0.53%   |
| 1 x VIA        | 1        | 0.53%   |
| 1 x Matrox     | 1        | 0.53%   |
| AMD + Nvidia   | 1        | 0.53%   |
| AMD + ASPEED   | 1        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 74       | 38.95%  |
| 1 x AMD        | 59       | 31.05%  |
| 1 x Intel      | 45       | 23.68%  |
| 1 x ASPEED     | 4        | 2.11%   |
| Intel + Nvidia | 3        | 1.58%   |
| 2 x AMD        | 1        | 0.53%   |
| 1 x VIA        | 1        | 0.53%   |
| 1 x Matrox     | 1        | 0.53%   |
| AMD + Nvidia   | 1        | 0.53%   |
| AMD + ASPEED   | 1        | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 132      | 69.47%  |
| Proprietary | 52       | 27.37%  |
| Unknown     | 6        | 3.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 132      | 69.47%  |
| Proprietary | 52       | 27.37%  |
| Unknown     | 6        | 3.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 78       | 40.84%  |
| 7.01-8.0   | 26       | 13.61%  |
| 1.01-2.0   | 22       | 11.52%  |
| 3.01-4.0   | 20       | 10.47%  |
| 0.51-1.0   | 17       | 8.9%    |
| 0.01-0.5   | 14       | 7.33%   |
| 5.01-6.0   | 6        | 3.14%   |
| 8.01-16.0  | 3        | 1.57%   |
| 2.01-3.0   | 2        | 1.05%   |
| 16.01-24.0 | 2        | 1.05%   |
| 24.01-32.0 | 1        | 0.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 78       | 40.84%  |
| 7.01-8.0   | 26       | 13.61%  |
| 1.01-2.0   | 22       | 11.52%  |
| 3.01-4.0   | 20       | 10.47%  |
| 0.51-1.0   | 17       | 8.9%    |
| 0.01-0.5   | 14       | 7.33%   |
| 5.01-6.0   | 6        | 3.14%   |
| 8.01-16.0  | 3        | 1.57%   |
| 2.01-3.0   | 2        | 1.05%   |
| 16.01-24.0 | 2        | 1.05%   |
| 24.01-32.0 | 1        | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 28       | 13.59%  |
| Goldstar                | 26       | 12.62%  |
| Dell                    | 25       | 12.14%  |
| Acer                    | 18       | 8.74%   |
| Ancor Communications    | 17       | 8.25%   |
| BenQ                    | 13       | 6.31%   |
| Hewlett-Packard         | 12       | 5.83%   |
| Philips                 | 9        | 4.37%   |
| AOC                     | 9        | 4.37%   |
| Eizo                    | 5        | 2.43%   |
| ASUSTek Computer        | 5        | 2.43%   |
| ViewSonic               | 4        | 1.94%   |
| Sony                    | 3        | 1.46%   |
| NEC Computers           | 3        | 1.46%   |
| Lenovo                  | 3        | 1.46%   |
| Unknown                 | 2        | 0.97%   |
| MSI                     | 2        | 0.97%   |
| LG Electronics          | 2        | 0.97%   |
| Iiyama                  | 2        | 0.97%   |
| VMO                     | 1        | 0.49%   |
| Vizio                   | 1        | 0.49%   |
| Vestel Elektronik       | 1        | 0.49%   |
| Prestigio               | 1        | 0.49%   |
| ODH                     | 1        | 0.49%   |
| MIT                     | 1        | 0.49%   |
| Mi                      | 1        | 0.49%   |
| Medion                  | 1        | 0.49%   |
| JVC                     | 1        | 0.49%   |
| INFOTRONIC              | 1        | 0.49%   |
| Idek Iiyama             | 1        | 0.49%   |
| Hyundai ImageQuest      | 1        | 0.49%   |
| HKC                     | 1        | 0.49%   |
| Hitachi                 | 1        | 0.49%   |
| HannStar Display        | 1        | 0.49%   |
| COBY                    | 1        | 0.49%   |
| Chi Mei Optoelectronics | 1        | 0.49%   |
| Belinea                 | 1        | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 28       | 13.59%  |
| Goldstar                | 26       | 12.62%  |
| Dell                    | 25       | 12.14%  |
| Acer                    | 18       | 8.74%   |
| Ancor Communications    | 17       | 8.25%   |
| BenQ                    | 13       | 6.31%   |
| Hewlett-Packard         | 12       | 5.83%   |
| Philips                 | 9        | 4.37%   |
| AOC                     | 9        | 4.37%   |
| Eizo                    | 5        | 2.43%   |
| ASUSTek Computer        | 5        | 2.43%   |
| ViewSonic               | 4        | 1.94%   |
| Sony                    | 3        | 1.46%   |
| NEC Computers           | 3        | 1.46%   |
| Lenovo                  | 3        | 1.46%   |
| Unknown                 | 2        | 0.97%   |
| MSI                     | 2        | 0.97%   |
| LG Electronics          | 2        | 0.97%   |
| Iiyama                  | 2        | 0.97%   |
| VMO                     | 1        | 0.49%   |
| Vizio                   | 1        | 0.49%   |
| Vestel Elektronik       | 1        | 0.49%   |
| Prestigio               | 1        | 0.49%   |
| ODH                     | 1        | 0.49%   |
| MIT                     | 1        | 0.49%   |
| Mi                      | 1        | 0.49%   |
| Medion                  | 1        | 0.49%   |
| JVC                     | 1        | 0.49%   |
| INFOTRONIC              | 1        | 0.49%   |
| Idek Iiyama             | 1        | 0.49%   |
| Hyundai ImageQuest      | 1        | 0.49%   |
| HKC                     | 1        | 0.49%   |
| Hitachi                 | 1        | 0.49%   |
| HannStar Display        | 1        | 0.49%   |
| COBY                    | 1        | 0.49%   |
| Chi Mei Optoelectronics | 1        | 0.49%   |
| Belinea                 | 1        | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 3        | 1.38%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 3        | 1.38%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 3        | 1.38%   |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3        | 1.38%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 3        | 1.38%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 2        | 0.92%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2        | 0.92%   |
| Lenovo L2251x Wide LEN0A12 1680x1050 474x296mm 22.0-inch               | 2        | 0.92%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2        | 0.92%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 0.92%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2        | 0.92%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2        | 0.92%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                      | 2        | 0.92%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2        | 0.92%   |
| VMO WQX DP VMO1507 2560x1600 1600x1000mm 74.3-inch                     | 1        | 0.46%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                     | 1        | 0.46%   |
| ViewSonic VA926 Series VSC7D20 1280x1024 376x301mm 19.0-inch           | 1        | 0.46%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch              | 1        | 0.46%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.46%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.46%   |
| Sony TV *00 SNY8004 3840x2160 1085x610mm 49.0-inch                     | 1        | 0.46%   |
| Sony TV *00 SNY3F05 3840x2160 952x535mm 43.0-inch                      | 1        | 0.46%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch      | 1        | 0.46%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.46%   |
| Samsung Electronics U24E850 SAM0CCF 3840x2160 521x293mm 23.5-inch      | 1        | 0.46%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch      | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch    | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch   | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 304x228mm 15.0-inch    | 1        | 0.46%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch     | 1        | 0.46%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch   | 1        | 0.46%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1        | 0.46%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 598x336mm 27.0-inch      | 1        | 0.46%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch      | 1        | 0.46%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 0.46%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch      | 1        | 0.46%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch       | 1        | 0.46%   |
| Samsung Electronics Monitor SAM1057 1280x1024 306x230mm 15.1-inch      | 1        | 0.46%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 0.46%   |
| Samsung Electronics LF27T850 SAM704F 2560x1440 597x336mm 27.0-inch     | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SyncMaster 5760x1080                   | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SMB2430L                               | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch   | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch  | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0BC9 1920x1080 600x340mm 27.2-inch  | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 0.46%   |
| Samsung Electronics LCD Monitor C24F390 3360x1080                      | 1        | 0.46%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch     | 1        | 0.46%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1        | 0.46%   |
| Samsung Electronics C24FG70 SAM0D58 1920x1080 532x304mm 24.1-inch      | 1        | 0.46%   |
| Prestigio P151 ASB0503 1024x768 304x228mm 15.0-inch                    | 1        | 0.46%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1        | 0.46%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 0.46%   |
| Philips PHL 242E1GZ PHLC24C 1920x1080 527x296mm 23.8-inch              | 1        | 0.46%   |
| Philips PHL 241E1 PHLC207 1920x1080 530x300mm 24.0-inch                | 1        | 0.46%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1        | 0.46%   |
| Philips LCD Monitor PHLC0B8 1920x1080 600x340mm 27.2-inch              | 1        | 0.46%   |
| Philips LCD Monitor PHL0850 1680x1050 470x300mm 22.0-inch              | 1        | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 3        | 1.38%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 3        | 1.38%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 3        | 1.38%   |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3        | 1.38%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 3        | 1.38%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 2        | 0.92%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2        | 0.92%   |
| Lenovo L2251x Wide LEN0A12 1680x1050 474x296mm 22.0-inch               | 2        | 0.92%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2        | 0.92%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 0.92%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2        | 0.92%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2        | 0.92%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                      | 2        | 0.92%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2        | 0.92%   |
| VMO WQX DP VMO1507 2560x1600 1600x1000mm 74.3-inch                     | 1        | 0.46%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                     | 1        | 0.46%   |
| ViewSonic VA926 Series VSC7D20 1280x1024 376x301mm 19.0-inch           | 1        | 0.46%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch              | 1        | 0.46%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.46%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.46%   |
| Sony TV *00 SNY8004 3840x2160 1085x610mm 49.0-inch                     | 1        | 0.46%   |
| Sony TV *00 SNY3F05 3840x2160 952x535mm 43.0-inch                      | 1        | 0.46%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch      | 1        | 0.46%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.46%   |
| Samsung Electronics U24E850 SAM0CCF 3840x2160 521x293mm 23.5-inch      | 1        | 0.46%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch      | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch    | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch   | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 304x228mm 15.0-inch    | 1        | 0.46%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch     | 1        | 0.46%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch   | 1        | 0.46%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1        | 0.46%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 598x336mm 27.0-inch      | 1        | 0.46%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch      | 1        | 0.46%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 0.46%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch      | 1        | 0.46%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch       | 1        | 0.46%   |
| Samsung Electronics Monitor SAM1057 1280x1024 306x230mm 15.1-inch      | 1        | 0.46%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 0.46%   |
| Samsung Electronics LF27T850 SAM704F 2560x1440 597x336mm 27.0-inch     | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SyncMaster 5760x1080                   | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SMB2430L                               | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch   | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch  | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0BC9 1920x1080 600x340mm 27.2-inch  | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 0.46%   |
| Samsung Electronics LCD Monitor C24F390 3360x1080                      | 1        | 0.46%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch     | 1        | 0.46%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1        | 0.46%   |
| Samsung Electronics C24FG70 SAM0D58 1920x1080 532x304mm 24.1-inch      | 1        | 0.46%   |
| Prestigio P151 ASB0503 1024x768 304x228mm 15.0-inch                    | 1        | 0.46%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1        | 0.46%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 0.46%   |
| Philips PHL 242E1GZ PHLC24C 1920x1080 527x296mm 23.8-inch              | 1        | 0.46%   |
| Philips PHL 241E1 PHLC207 1920x1080 530x300mm 24.0-inch                | 1        | 0.46%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1        | 0.46%   |
| Philips LCD Monitor PHLC0B8 1920x1080 600x340mm 27.2-inch              | 1        | 0.46%   |
| Philips LCD Monitor PHL0850 1680x1050 470x300mm 22.0-inch              | 1        | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 83       | 40.89%  |
| 2560x1440 (QHD)    | 21       | 10.34%  |
| 3840x2160 (4K)     | 19       | 9.36%   |
| 1280x1024 (SXGA)   | 16       | 7.88%   |
| 1680x1050 (WSXGA+) | 11       | 5.42%   |
| 1920x1200 (WUXGA)  | 9        | 4.43%   |
| 1366x768 (WXGA)    | 7        | 3.45%   |
| 2560x1080          | 5        | 2.46%   |
| 1600x900 (HD+)     | 5        | 2.46%   |
| Unknown            | 5        | 2.46%   |
| 2560x1600          | 3        | 1.48%   |
| 1440x900 (WXGA+)   | 3        | 1.48%   |
| 1024x768 (XGA)     | 3        | 1.48%   |
| 3440x1440          | 2        | 0.99%   |
| 2288x1287          | 2        | 0.99%   |
| 1600x1200          | 2        | 0.99%   |
| 7680x4320          | 1        | 0.49%   |
| 5760x1080          | 1        | 0.49%   |
| 4480x1440          | 1        | 0.49%   |
| 3840x1080          | 1        | 0.49%   |
| 3360x1080          | 1        | 0.49%   |
| 1920x540           | 1        | 0.49%   |
| 1024x600           | 1        | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 83       | 40.89%  |
| 2560x1440 (QHD)    | 21       | 10.34%  |
| 3840x2160 (4K)     | 19       | 9.36%   |
| 1280x1024 (SXGA)   | 16       | 7.88%   |
| 1680x1050 (WSXGA+) | 11       | 5.42%   |
| 1920x1200 (WUXGA)  | 9        | 4.43%   |
| 1366x768 (WXGA)    | 7        | 3.45%   |
| 2560x1080          | 5        | 2.46%   |
| 1600x900 (HD+)     | 5        | 2.46%   |
| Unknown            | 5        | 2.46%   |
| 2560x1600          | 3        | 1.48%   |
| 1440x900 (WXGA+)   | 3        | 1.48%   |
| 1024x768 (XGA)     | 3        | 1.48%   |
| 3440x1440          | 2        | 0.99%   |
| 2288x1287          | 2        | 0.99%   |
| 1600x1200          | 2        | 0.99%   |
| 7680x4320          | 1        | 0.49%   |
| 5760x1080          | 1        | 0.49%   |
| 4480x1440          | 1        | 0.49%   |
| 3840x1080          | 1        | 0.49%   |
| 3360x1080          | 1        | 0.49%   |
| 1920x540           | 1        | 0.49%   |
| 1024x600           | 1        | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 35       | 17.24%  |
| 24      | 34       | 16.75%  |
| 23      | 30       | 14.78%  |
| 21      | 15       | 7.39%   |
| Unknown | 14       | 6.9%    |
| 17      | 10       | 4.93%   |
| 31      | 9        | 4.43%   |
| 22      | 7        | 3.45%   |
| 19      | 7        | 3.45%   |
| 18      | 7        | 3.45%   |
| 34      | 6        | 2.96%   |
| 20      | 5        | 2.46%   |
| 15      | 5        | 2.46%   |
| 142     | 2        | 0.99%   |
| 84      | 2        | 0.99%   |
| 29      | 2        | 0.99%   |
| 28      | 2        | 0.99%   |
| 74      | 1        | 0.49%   |
| 72      | 1        | 0.49%   |
| 65      | 1        | 0.49%   |
| 55      | 1        | 0.49%   |
| 48      | 1        | 0.49%   |
| 38      | 1        | 0.49%   |
| 32      | 1        | 0.49%   |
| 26      | 1        | 0.49%   |
| 25      | 1        | 0.49%   |
| 16      | 1        | 0.49%   |
| 10      | 1        | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 35       | 17.24%  |
| 24      | 34       | 16.75%  |
| 23      | 30       | 14.78%  |
| 21      | 15       | 7.39%   |
| Unknown | 14       | 6.9%    |
| 17      | 10       | 4.93%   |
| 31      | 9        | 4.43%   |
| 22      | 7        | 3.45%   |
| 19      | 7        | 3.45%   |
| 18      | 7        | 3.45%   |
| 34      | 6        | 2.96%   |
| 20      | 5        | 2.46%   |
| 15      | 5        | 2.46%   |
| 142     | 2        | 0.99%   |
| 84      | 2        | 0.99%   |
| 29      | 2        | 0.99%   |
| 28      | 2        | 0.99%   |
| 74      | 1        | 0.49%   |
| 72      | 1        | 0.49%   |
| 65      | 1        | 0.49%   |
| 55      | 1        | 0.49%   |
| 48      | 1        | 0.49%   |
| 38      | 1        | 0.49%   |
| 32      | 1        | 0.49%   |
| 26      | 1        | 0.49%   |
| 25      | 1        | 0.49%   |
| 16      | 1        | 0.49%   |
| 10      | 1        | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 90       | 45.69%  |
| 401-500        | 38       | 19.29%  |
| 601-700        | 16       | 8.12%   |
| 301-350        | 16       | 8.12%   |
| Unknown        | 14       | 7.11%   |
| 701-800        | 7        | 3.55%   |
| 351-400        | 5        | 2.54%   |
| 1501-2000      | 4        | 2.03%   |
| 1001-1500      | 3        | 1.52%   |
| More than 2000 | 2        | 1.02%   |
| 801-900        | 1        | 0.51%   |
| 201-300        | 1        | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 90       | 45.69%  |
| 401-500        | 38       | 19.29%  |
| 601-700        | 16       | 8.12%   |
| 301-350        | 16       | 8.12%   |
| Unknown        | 14       | 7.11%   |
| 701-800        | 7        | 3.55%   |
| 351-400        | 5        | 2.54%   |
| 1501-2000      | 4        | 2.03%   |
| 1001-1500      | 3        | 1.52%   |
| More than 2000 | 2        | 1.02%   |
| 801-900        | 1        | 0.51%   |
| 201-300        | 1        | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 121      | 62.37%  |
| 16/10   | 25       | 12.89%  |
| 5/4     | 14       | 7.22%   |
| Unknown | 13       | 6.7%    |
| 4/3     | 7        | 3.61%   |
| 21/9    | 7        | 3.61%   |
| 1.00    | 3        | 1.55%   |
| 3/2     | 2        | 1.03%   |
| 6/5     | 1        | 0.52%   |
| 1.96    | 1        | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 121      | 62.37%  |
| 16/10   | 25       | 12.89%  |
| 5/4     | 14       | 7.22%   |
| Unknown | 13       | 6.7%    |
| 4/3     | 7        | 3.61%   |
| 21/9    | 7        | 3.61%   |
| 1.00    | 3        | 1.55%   |
| 3/2     | 2        | 1.03%   |
| 6/5     | 1        | 0.52%   |
| 1.96    | 1        | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 66       | 33.17%  |
| 301-350        | 35       | 17.59%  |
| 351-500        | 20       | 10.05%  |
| 151-200        | 17       | 8.54%   |
| 251-300        | 15       | 7.54%   |
| 141-150        | 14       | 7.04%   |
| Unknown        | 14       | 7.04%   |
| More than 1000 | 8        | 4.02%   |
| 101-110        | 5        | 2.51%   |
| 131-140        | 2        | 1.01%   |
| 501-1000       | 2        | 1.01%   |
| 41-50          | 1        | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 66       | 33.17%  |
| 301-350        | 35       | 17.59%  |
| 351-500        | 20       | 10.05%  |
| 151-200        | 17       | 8.54%   |
| 251-300        | 15       | 7.54%   |
| 141-150        | 14       | 7.04%   |
| Unknown        | 14       | 7.04%   |
| More than 1000 | 8        | 4.02%   |
| 101-110        | 5        | 2.51%   |
| 131-140        | 2        | 1.01%   |
| 501-1000       | 2        | 1.01%   |
| 41-50          | 1        | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 119      | 62.63%  |
| 101-120 | 33       | 17.37%  |
| Unknown | 14       | 7.37%   |
| 121-160 | 10       | 5.26%   |
| 161-240 | 8        | 4.21%   |
| 1-50    | 6        | 3.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 119      | 62.63%  |
| 101-120 | 33       | 17.37%  |
| Unknown | 14       | 7.37%   |
| 121-160 | 10       | 5.26%   |
| 161-240 | 8        | 4.21%   |
| 1-50    | 6        | 3.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 138      | 72.63%  |
| 2     | 34       | 17.89%  |
| 0     | 13       | 6.84%   |
| 3     | 4        | 2.11%   |
| 4     | 1        | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 138      | 72.63%  |
| 2     | 34       | 17.89%  |
| 0     | 13       | 6.84%   |
| 3     | 4        | 2.11%   |
| 4     | 1        | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 101      | 41.22%  |
| Intel                           | 92       | 37.55%  |
| Qualcomm Atheros                | 18       | 7.35%   |
| Broadcom                        | 10       | 4.08%   |
| Ralink Technology               | 3        | 1.22%   |
| TP-Link                         | 2        | 0.82%   |
| Ralink                          | 2        | 0.82%   |
| Nvidia                          | 2        | 0.82%   |
| Microsoft                       | 2        | 0.82%   |
| Mellanox Technologies           | 2        | 0.82%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.41%   |
| Xiaomi                          | 1        | 0.41%   |
| VIA Technologies                | 1        | 0.41%   |
| Qualcomm Atheros Communications | 1        | 0.41%   |
| Marvell Technology Group        | 1        | 0.41%   |
| Edimax Technology               | 1        | 0.41%   |
| D-Link                          | 1        | 0.41%   |
| Broadcom Limited                | 1        | 0.41%   |
| ASIX Electronics                | 1        | 0.41%   |
| Aquantia                        | 1        | 0.41%   |
| American Megatrends             | 1        | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 101      | 41.22%  |
| Intel                           | 92       | 37.55%  |
| Qualcomm Atheros                | 18       | 7.35%   |
| Broadcom                        | 10       | 4.08%   |
| Ralink Technology               | 3        | 1.22%   |
| TP-Link                         | 2        | 0.82%   |
| Ralink                          | 2        | 0.82%   |
| Nvidia                          | 2        | 0.82%   |
| Microsoft                       | 2        | 0.82%   |
| Mellanox Technologies           | 2        | 0.82%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.41%   |
| Xiaomi                          | 1        | 0.41%   |
| VIA Technologies                | 1        | 0.41%   |
| Qualcomm Atheros Communications | 1        | 0.41%   |
| Marvell Technology Group        | 1        | 0.41%   |
| Edimax Technology               | 1        | 0.41%   |
| D-Link                          | 1        | 0.41%   |
| Broadcom Limited                | 1        | 0.41%   |
| ASIX Electronics                | 1        | 0.41%   |
| Aquantia                        | 1        | 0.41%   |
| American Megatrends             | 1        | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 79       | 28.62%  |
| Intel I211 Gigabit Network Connection                               | 18       | 6.52%   |
| Intel Ethernet Connection (2) I219-V                                | 13       | 4.71%   |
| Realtek RTL8125 2.5GbE Controller                                   | 11       | 3.99%   |
| Intel Wi-Fi 6 AX200                                                 | 9        | 3.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 9        | 3.26%   |
| Intel I210 Gigabit Network Connection                               | 6        | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 6        | 2.17%   |
| Intel Ethernet Connection (2) I218-V                                | 5        | 1.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 4        | 1.45%   |
| Intel Ethernet Connection I217-V                                    | 4        | 1.45%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 4        | 1.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 3        | 1.09%   |
| Intel Wireless 8260                                                 | 3        | 1.09%   |
| Intel Wireless 7260                                                 | 3        | 1.09%   |
| Intel 82574L Gigabit Network Connection                             | 3        | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.72%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2        | 0.72%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 2        | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2        | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.72%   |
| Nvidia MCP61 Ethernet                                               | 2        | 0.72%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 2        | 0.72%   |
| Mellanox MT27500 Family [ConnectX-3]                                | 2        | 0.72%   |
| Intel Wireless 3165                                                 | 2        | 0.72%   |
| Intel Ethernet Controller 10G X550T                                 | 2        | 0.72%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                    | 2        | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 2        | 0.72%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                       | 1        | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.36%   |
| VIA VT6102/VT6103 [Rhine-II]                                        | 1        | 0.36%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                               | 1        | 0.36%   |
| TP-Link Archer T4U ver.3                                            | 1        | 0.36%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.36%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1        | 0.36%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 1        | 0.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 0.36%   |
| Realtek 802.11ac NIC                                                | 1        | 0.36%   |
| Ralink RT5372 Wireless Adapter                                      | 1        | 0.36%   |
| Ralink RT5370 Wireless Adapter                                      | 1        | 0.36%   |
| Ralink MT7601U Wireless Adapter                                     | 1        | 0.36%   |
| Ralink RT5392 PCIe Wireless Network Adapter                         | 1        | 0.36%   |
| Ralink RT2800 802.11n PCI                                           | 1        | 0.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.36%   |
| Qualcomm Atheros AR9271 802.11n                                     | 1        | 0.36%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                          | 1        | 0.36%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                       | 1        | 0.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1        | 0.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 1        | 0.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 1        | 0.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.36%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 0.36%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.36%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                   | 1        | 0.36%   |
| Intel Wireless-AC 9260                                              | 1        | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 79       | 28.62%  |
| Intel I211 Gigabit Network Connection                               | 18       | 6.52%   |
| Intel Ethernet Connection (2) I219-V                                | 13       | 4.71%   |
| Realtek RTL8125 2.5GbE Controller                                   | 11       | 3.99%   |
| Intel Wi-Fi 6 AX200                                                 | 9        | 3.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 9        | 3.26%   |
| Intel I210 Gigabit Network Connection                               | 6        | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 6        | 2.17%   |
| Intel Ethernet Connection (2) I218-V                                | 5        | 1.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 4        | 1.45%   |
| Intel Ethernet Connection I217-V                                    | 4        | 1.45%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 4        | 1.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 3        | 1.09%   |
| Intel Wireless 8260                                                 | 3        | 1.09%   |
| Intel Wireless 7260                                                 | 3        | 1.09%   |
| Intel 82574L Gigabit Network Connection                             | 3        | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.72%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2        | 0.72%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 2        | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2        | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.72%   |
| Nvidia MCP61 Ethernet                                               | 2        | 0.72%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 2        | 0.72%   |
| Mellanox MT27500 Family [ConnectX-3]                                | 2        | 0.72%   |
| Intel Wireless 3165                                                 | 2        | 0.72%   |
| Intel Ethernet Controller 10G X550T                                 | 2        | 0.72%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                    | 2        | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 2        | 0.72%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                       | 1        | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.36%   |
| VIA VT6102/VT6103 [Rhine-II]                                        | 1        | 0.36%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                               | 1        | 0.36%   |
| TP-Link Archer T4U ver.3                                            | 1        | 0.36%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.36%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1        | 0.36%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 1        | 0.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 0.36%   |
| Realtek 802.11ac NIC                                                | 1        | 0.36%   |
| Ralink RT5372 Wireless Adapter                                      | 1        | 0.36%   |
| Ralink RT5370 Wireless Adapter                                      | 1        | 0.36%   |
| Ralink MT7601U Wireless Adapter                                     | 1        | 0.36%   |
| Ralink RT5392 PCIe Wireless Network Adapter                         | 1        | 0.36%   |
| Ralink RT2800 802.11n PCI                                           | 1        | 0.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.36%   |
| Qualcomm Atheros AR9271 802.11n                                     | 1        | 0.36%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                          | 1        | 0.36%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                       | 1        | 0.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1        | 0.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 1        | 0.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 1        | 0.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.36%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 0.36%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.36%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                   | 1        | 0.36%   |
| Intel Wireless-AC 9260                                              | 1        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 27       | 46.55%  |
| Realtek Semiconductor           | 9        | 15.52%  |
| Qualcomm Atheros                | 6        | 10.34%  |
| Broadcom                        | 4        | 6.9%    |
| Ralink Technology               | 3        | 5.17%   |
| TP-Link                         | 2        | 3.45%   |
| Ralink                          | 2        | 3.45%   |
| Microsoft                       | 2        | 3.45%   |
| Qualcomm Atheros Communications | 1        | 1.72%   |
| Edimax Technology               | 1        | 1.72%   |
| D-Link                          | 1        | 1.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 27       | 46.55%  |
| Realtek Semiconductor           | 9        | 15.52%  |
| Qualcomm Atheros                | 6        | 10.34%  |
| Broadcom                        | 4        | 6.9%    |
| Ralink Technology               | 3        | 5.17%   |
| TP-Link                         | 2        | 3.45%   |
| Ralink                          | 2        | 3.45%   |
| Microsoft                       | 2        | 3.45%   |
| Qualcomm Atheros Communications | 1        | 1.72%   |
| Edimax Technology               | 1        | 1.72%   |
| D-Link                          | 1        | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 9        | 15.52%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6        | 10.34%  |
| Intel Wireless 8260                                                     | 3        | 5.17%   |
| Intel Wireless 7260                                                     | 3        | 5.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2        | 3.45%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2        | 3.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2        | 3.45%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 2        | 3.45%   |
| Intel Wireless 3165                                                     | 2        | 3.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2        | 3.45%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 1        | 1.72%   |
| TP-Link Archer T4U ver.3                                                | 1        | 1.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1        | 1.72%   |
| Realtek 802.11ac NIC                                                    | 1        | 1.72%   |
| Ralink RT5372 Wireless Adapter                                          | 1        | 1.72%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 1.72%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 1.72%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1        | 1.72%   |
| Ralink RT2800 802.11n PCI                                               | 1        | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 1.72%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 1.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1        | 1.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 1.72%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1        | 1.72%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1        | 1.72%   |
| Intel Wireless-AC 9260                                                  | 1        | 1.72%   |
| Intel Wireless 8265 / 8275                                              | 1        | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 1.72%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1        | 1.72%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 1.72%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1        | 1.72%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1        | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 9        | 15.52%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6        | 10.34%  |
| Intel Wireless 8260                                                     | 3        | 5.17%   |
| Intel Wireless 7260                                                     | 3        | 5.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2        | 3.45%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2        | 3.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2        | 3.45%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 2        | 3.45%   |
| Intel Wireless 3165                                                     | 2        | 3.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2        | 3.45%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 1        | 1.72%   |
| TP-Link Archer T4U ver.3                                                | 1        | 1.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1        | 1.72%   |
| Realtek 802.11ac NIC                                                    | 1        | 1.72%   |
| Ralink RT5372 Wireless Adapter                                          | 1        | 1.72%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 1.72%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 1.72%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1        | 1.72%   |
| Ralink RT2800 802.11n PCI                                               | 1        | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 1.72%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 1.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1        | 1.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 1.72%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1        | 1.72%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1        | 1.72%   |
| Intel Wireless-AC 9260                                                  | 1        | 1.72%   |
| Intel Wireless 8265 / 8275                                              | 1        | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 1.72%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1        | 1.72%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 1.72%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1        | 1.72%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1        | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 97       | 47.09%  |
| Intel                    | 79       | 38.35%  |
| Qualcomm Atheros         | 13       | 6.31%   |
| Broadcom                 | 6        | 2.91%   |
| Nvidia                   | 2        | 0.97%   |
| Mellanox Technologies    | 2        | 0.97%   |
| Xiaomi                   | 1        | 0.49%   |
| VIA Technologies         | 1        | 0.49%   |
| Marvell Technology Group | 1        | 0.49%   |
| Broadcom Limited         | 1        | 0.49%   |
| ASIX Electronics         | 1        | 0.49%   |
| Aquantia                 | 1        | 0.49%   |
| American Megatrends      | 1        | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 97       | 47.09%  |
| Intel                    | 79       | 38.35%  |
| Qualcomm Atheros         | 13       | 6.31%   |
| Broadcom                 | 6        | 2.91%   |
| Nvidia                   | 2        | 0.97%   |
| Mellanox Technologies    | 2        | 0.97%   |
| Xiaomi                   | 1        | 0.49%   |
| VIA Technologies         | 1        | 0.49%   |
| Marvell Technology Group | 1        | 0.49%   |
| Broadcom Limited         | 1        | 0.49%   |
| ASIX Electronics         | 1        | 0.49%   |
| Aquantia                 | 1        | 0.49%   |
| American Megatrends      | 1        | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79       | 36.41%  |
| Intel I211 Gigabit Network Connection                             | 18       | 8.29%   |
| Intel Ethernet Connection (2) I219-V                              | 13       | 5.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11       | 5.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 4.15%   |
| Intel I210 Gigabit Network Connection                             | 6        | 2.76%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 2.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 1.84%   |
| Intel Ethernet Connection I217-V                                  | 4        | 1.84%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 1.38%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.92%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.92%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.92%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2        | 0.92%   |
| Intel Ethernet Controller 10G X550T                               | 2        | 0.92%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.92%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.46%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.46%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.46%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.46%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.46%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.46%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.46%   |
| Intel Ethernet Virtual Function 700 Series                        | 1        | 0.46%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 0.46%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.46%   |
| Intel Ethernet Connection I354                                    | 1        | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 0.46%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.46%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.46%   |
| Intel Ethernet Connection (6) I219-V                              | 1        | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.46%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.46%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.46%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.46%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.46%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.46%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.46%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.46%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 0.46%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.46%   |
| Intel 82540EM Gigabit Ethernet Controller                         | 1        | 0.46%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.46%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.46%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 0.46%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 0.46%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 1        | 0.46%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79       | 36.41%  |
| Intel I211 Gigabit Network Connection                             | 18       | 8.29%   |
| Intel Ethernet Connection (2) I219-V                              | 13       | 5.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11       | 5.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 4.15%   |
| Intel I210 Gigabit Network Connection                             | 6        | 2.76%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 2.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 1.84%   |
| Intel Ethernet Connection I217-V                                  | 4        | 1.84%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 1.38%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.92%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.92%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.92%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2        | 0.92%   |
| Intel Ethernet Controller 10G X550T                               | 2        | 0.92%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.92%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.46%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.46%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.46%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.46%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.46%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.46%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.46%   |
| Intel Ethernet Virtual Function 700 Series                        | 1        | 0.46%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 0.46%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.46%   |
| Intel Ethernet Connection I354                                    | 1        | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 0.46%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.46%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.46%   |
| Intel Ethernet Connection (6) I219-V                              | 1        | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.46%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.46%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.46%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.46%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.46%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.46%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.46%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.46%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 0.46%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.46%   |
| Intel 82540EM Gigabit Ethernet Controller                         | 1        | 0.46%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.46%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.46%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 0.46%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 0.46%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 1        | 0.46%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 189      | 76.21%  |
| WiFi     | 58       | 23.39%  |
| Modem    | 1        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 189      | 76.21%  |
| WiFi     | 58       | 23.39%  |
| Modem    | 1        | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 172      | 81.52%  |
| WiFi     | 39       | 18.48%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 172      | 81.52%  |
| WiFi     | 39       | 18.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 119      | 62.63%  |
| 2     | 55       | 28.95%  |
| 3     | 10       | 5.26%   |
| 4     | 2        | 1.05%   |
| 13    | 1        | 0.53%   |
| 6     | 1        | 0.53%   |
| 5     | 1        | 0.53%   |
| 0     | 1        | 0.53%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 119      | 62.63%  |
| 2     | 55       | 28.95%  |
| 3     | 10       | 5.26%   |
| 4     | 2        | 1.05%   |
| 13    | 1        | 0.53%   |
| 6     | 1        | 0.53%   |
| 5     | 1        | 0.53%   |
| 0     | 1        | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 151      | 79.47%  |
| Yes  | 39       | 20.53%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 151      | 79.47%  |
| Yes  | 39       | 20.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 25       | 51.02%  |
| Cambridge Silicon Radio         | 10       | 20.41%  |
| Broadcom                        | 6        | 12.24%  |
| ASUSTek Computer                | 5        | 10.2%   |
| Qualcomm Atheros Communications | 2        | 4.08%   |
| Realtek Semiconductor           | 1        | 2.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 25       | 51.02%  |
| Cambridge Silicon Radio         | 10       | 20.41%  |
| Broadcom                        | 6        | 12.24%  |
| ASUSTek Computer                | 5        | 10.2%   |
| Qualcomm Atheros Communications | 2        | 4.08%   |
| Realtek Semiconductor           | 1        | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 10       | 20.41%  |
| Intel AX200 Bluetooth                                 | 9        | 18.37%  |
| Intel Wireless-AC 3168 Bluetooth                      | 5        | 10.2%   |
| Intel Bluetooth wireless interface                    | 4        | 8.16%   |
| Intel Bluetooth Device                                | 3        | 6.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 2        | 4.08%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 4.08%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 4.08%   |
| Realtek Bluetooth Radio                               | 1        | 2.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 2.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1        | 2.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 2.04%   |
| Intel AX210 Bluetooth                                 | 1        | 2.04%   |
| Broadcom Bluetooth 3.0 Device                         | 1        | 2.04%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1        | 2.04%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 2.04%   |
| Broadcom BCM2035 Bluetooth dongle                     | 1        | 2.04%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 2.04%   |
| ASUS Bluetooth Radio                                  | 1        | 2.04%   |
| ASUS Bluetooth Device                                 | 1        | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 10       | 20.41%  |
| Intel AX200 Bluetooth                                 | 9        | 18.37%  |
| Intel Wireless-AC 3168 Bluetooth                      | 5        | 10.2%   |
| Intel Bluetooth wireless interface                    | 4        | 8.16%   |
| Intel Bluetooth Device                                | 3        | 6.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 2        | 4.08%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 4.08%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 4.08%   |
| Realtek Bluetooth Radio                               | 1        | 2.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 2.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1        | 2.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 2.04%   |
| Intel AX210 Bluetooth                                 | 1        | 2.04%   |
| Broadcom Bluetooth 3.0 Device                         | 1        | 2.04%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1        | 2.04%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 2.04%   |
| Broadcom BCM2035 Bluetooth dongle                     | 1        | 2.04%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 2.04%   |
| ASUS Bluetooth Radio                                  | 1        | 2.04%   |
| ASUS Bluetooth Device                                 | 1        | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 99       | 30.94%  |
| AMD                        | 89       | 27.81%  |
| Nvidia                     | 72       | 22.5%   |
| C-Media Electronics        | 11       | 3.44%   |
| Logitech                   | 5        | 1.56%   |
| GYROCOM C&C                | 4        | 1.25%   |
| Creative Labs              | 4        | 1.25%   |
| VIA Technologies           | 3        | 0.94%   |
| Generalplus Technology     | 3        | 0.94%   |
| XMOS                       | 2        | 0.63%   |
| Samson Technologies        | 2        | 0.63%   |
| GN Netcom                  | 2        | 0.63%   |
| BEHRINGER International    | 2        | 0.63%   |
| ASUSTek Computer           | 2        | 0.63%   |
| Unknown                    | 1        | 0.31%   |
| Texas Instruments          | 1        | 0.31%   |
| TEAC                       | 1        | 0.31%   |
| SteelSeries ApS            | 1        | 0.31%   |
| RODE Microphones           | 1        | 0.31%   |
| ROCCAT                     | 1        | 0.31%   |
| PreSonus Audio Electronics | 1        | 0.31%   |
| Micronas                   | 1        | 0.31%   |
| M-Audio                    | 1        | 0.31%   |
| JMTek                      | 1        | 0.31%   |
| Hangzhou Worlde            | 1        | 0.31%   |
| Focusrite-Novation         | 1        | 0.31%   |
| Dell                       | 1        | 0.31%   |
| Creative Technology        | 1        | 0.31%   |
| Cambridge Silicon Radio    | 1        | 0.31%   |
| Blue Microphones           | 1        | 0.31%   |
| AXELVOX                    | 1        | 0.31%   |
| AVID Technology            | 1        | 0.31%   |
| Audioengine                | 1        | 0.31%   |
| Alesis                     | 1        | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 99       | 30.94%  |
| AMD                        | 89       | 27.81%  |
| Nvidia                     | 72       | 22.5%   |
| C-Media Electronics        | 11       | 3.44%   |
| Logitech                   | 5        | 1.56%   |
| GYROCOM C&C                | 4        | 1.25%   |
| Creative Labs              | 4        | 1.25%   |
| VIA Technologies           | 3        | 0.94%   |
| Generalplus Technology     | 3        | 0.94%   |
| XMOS                       | 2        | 0.63%   |
| Samson Technologies        | 2        | 0.63%   |
| GN Netcom                  | 2        | 0.63%   |
| BEHRINGER International    | 2        | 0.63%   |
| ASUSTek Computer           | 2        | 0.63%   |
| Unknown                    | 1        | 0.31%   |
| Texas Instruments          | 1        | 0.31%   |
| TEAC                       | 1        | 0.31%   |
| SteelSeries ApS            | 1        | 0.31%   |
| RODE Microphones           | 1        | 0.31%   |
| ROCCAT                     | 1        | 0.31%   |
| PreSonus Audio Electronics | 1        | 0.31%   |
| Micronas                   | 1        | 0.31%   |
| M-Audio                    | 1        | 0.31%   |
| JMTek                      | 1        | 0.31%   |
| Hangzhou Worlde            | 1        | 0.31%   |
| Focusrite-Novation         | 1        | 0.31%   |
| Dell                       | 1        | 0.31%   |
| Creative Technology        | 1        | 0.31%   |
| Cambridge Silicon Radio    | 1        | 0.31%   |
| Blue Microphones           | 1        | 0.31%   |
| AXELVOX                    | 1        | 0.31%   |
| AVID Technology            | 1        | 0.31%   |
| Audioengine                | 1        | 0.31%   |
| Alesis                     | 1        | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 30       | 8.11%   |
| Intel 200 Series PCH HD Audio                                              | 16       | 4.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 16       | 4.32%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15       | 4.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15       | 4.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11       | 2.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10       | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 2.7%    |
| AMD FCH Azalia Controller                                                  | 10       | 2.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 2.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 2.43%   |
| AMD Navi 10 HDMI Audio                                                     | 9        | 2.43%   |
| Nvidia GP104 High Definition Audio Controller                              | 7        | 1.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 1.89%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6        | 1.62%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 1.62%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 1.35%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 5        | 1.35%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 1.08%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 1.08%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 1.08%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 4        | 1.08%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 1.08%   |
| Nvidia High Definition Audio Controller                                    | 3        | 0.81%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 0.81%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 0.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.81%   |
| GYROCOM C&C Fiio E10                                                       | 3        | 0.81%   |
| Generalplus Technology USB Audio Device                                    | 3        | 0.81%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 0.81%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 3        | 0.81%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 2        | 0.54%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.54%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.54%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.54%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.54%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.54%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.54%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.54%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.54%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.54%   |
| Nvidia GF104 High Definition Audio Controller                              | 2        | 0.54%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.54%   |
| Logitech G430 Surround Sound Gaming Headset                                | 2        | 0.54%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller             | 2        | 0.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 0.54%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2        | 0.54%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                         | 2        | 0.54%   |
| C-Media Electronics USB Audio Device                                       | 2        | 0.54%   |
| ASUSTek Computer USB Audio                                                 | 2        | 0.54%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 0.54%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 0.54%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 2        | 0.54%   |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 0.54%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 0.54%   |
| XMOS MIYO USB Audio 2.0                                                    | 1        | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 30       | 8.11%   |
| Intel 200 Series PCH HD Audio                                              | 16       | 4.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 16       | 4.32%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15       | 4.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15       | 4.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11       | 2.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10       | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 2.7%    |
| AMD FCH Azalia Controller                                                  | 10       | 2.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 2.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 2.43%   |
| AMD Navi 10 HDMI Audio                                                     | 9        | 2.43%   |
| Nvidia GP104 High Definition Audio Controller                              | 7        | 1.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 1.89%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6        | 1.62%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 1.62%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 1.35%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 5        | 1.35%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 1.08%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 1.08%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 1.08%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 4        | 1.08%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 1.08%   |
| Nvidia High Definition Audio Controller                                    | 3        | 0.81%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 0.81%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 0.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.81%   |
| GYROCOM C&C Fiio E10                                                       | 3        | 0.81%   |
| Generalplus Technology USB Audio Device                                    | 3        | 0.81%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 0.81%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 3        | 0.81%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 2        | 0.54%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.54%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.54%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.54%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.54%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.54%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.54%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.54%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.54%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.54%   |
| Nvidia GF104 High Definition Audio Controller                              | 2        | 0.54%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.54%   |
| Logitech G430 Surround Sound Gaming Headset                                | 2        | 0.54%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller             | 2        | 0.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 0.54%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2        | 0.54%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                         | 2        | 0.54%   |
| C-Media Electronics USB Audio Device                                       | 2        | 0.54%   |
| ASUSTek Computer USB Audio                                                 | 2        | 0.54%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 0.54%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 0.54%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 2        | 0.54%   |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 0.54%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 0.54%   |
| XMOS MIYO USB Audio 2.0                                                    | 1        | 0.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 44       | 22.11%  |
| Corsair             | 33       | 16.58%  |
| Unknown             | 28       | 14.07%  |
| Samsung Electronics | 21       | 10.55%  |
| G.Skill             | 17       | 8.54%   |
| Crucial             | 17       | 8.54%   |
| SK Hynix            | 13       | 6.53%   |
| Micron Technology   | 5        | 2.51%   |
| Patriot             | 4        | 2.01%   |
| A-DATA Technology   | 3        | 1.51%   |
| Team                | 2        | 1.01%   |
| Kllisre             | 2        | 1.01%   |
| Elpida              | 2        | 1.01%   |
| V-Color             | 1        | 0.5%    |
| Unknown (ABCD)      | 1        | 0.5%    |
| OCZ                 | 1        | 0.5%    |
| Nanya Technology    | 1        | 0.5%    |
| Kingmax             | 1        | 0.5%    |
| KETECH              | 1        | 0.5%    |
| GOODRAM             | 1        | 0.5%    |
| GeIL                | 1        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 44       | 22.11%  |
| Corsair             | 33       | 16.58%  |
| Unknown             | 28       | 14.07%  |
| Samsung Electronics | 21       | 10.55%  |
| G.Skill             | 17       | 8.54%   |
| Crucial             | 17       | 8.54%   |
| SK Hynix            | 13       | 6.53%   |
| Micron Technology   | 5        | 2.51%   |
| Patriot             | 4        | 2.01%   |
| A-DATA Technology   | 3        | 1.51%   |
| Team                | 2        | 1.01%   |
| Kllisre             | 2        | 1.01%   |
| Elpida              | 2        | 1.01%   |
| V-Color             | 1        | 0.5%    |
| Unknown (ABCD)      | 1        | 0.5%    |
| OCZ                 | 1        | 0.5%    |
| Nanya Technology    | 1        | 0.5%    |
| Kingmax             | 1        | 0.5%    |
| KETECH              | 1        | 0.5%    |
| GOODRAM             | 1        | 0.5%    |
| GeIL                | 1        | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 5        | 2.19%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s          | 5        | 2.19%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 4        | 1.75%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 3        | 1.32%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s              | 3        | 1.32%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 3        | 1.32%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 3        | 1.32%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s       | 3        | 1.32%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2        | 0.88%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 2        | 0.88%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 2        | 0.88%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                     | 2        | 0.88%   |
| Unknown RAM 99[2/7/4]164(F/R) 4GB DIMM DDR3 1600MT/s           | 2        | 0.88%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s            | 2        | 0.88%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 2        | 0.88%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s             | 2        | 0.88%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s           | 2        | 0.88%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s              | 2        | 0.88%   |
| Kingston RAM KHX2133C14D4/8G 8192MB DIMM DDR4 2667MT/s         | 2        | 0.88%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1867MT/s         | 2        | 0.88%   |
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1866MT/s         | 2        | 0.88%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s         | 2        | 0.88%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s         | 2        | 0.88%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s          | 2        | 0.88%   |
| Corsair RAM CMK32GX4M2A2666C16 16384MB DIMM DDR4 3100MT/s      | 2        | 0.88%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s          | 2        | 0.88%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s               | 1        | 0.44%   |
| Unknown RAM V02D4LF8GB5285282400 8192MB DIMM DDR4 2400MT/s     | 1        | 0.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.44%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM SDRAM 400MT/s                    | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                     | 1        | 0.44%   |
| Unknown RAM Module 4GB DIMM 800MT/s                            | 1        | 0.44%   |
| Unknown RAM Module 4GB DIMM 400MT/s                            | 1        | 0.44%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s                     | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM 400MT/s                            | 1        | 0.44%   |
| Unknown RAM Module 256MB DIMM SDRAM 400MT/s                    | 1        | 0.44%   |
| Unknown RAM Module 256MB DIMM                                  | 1        | 0.44%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1        | 0.44%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 1        | 0.44%   |
| Unknown RAM Module 1GB DIMM                                    | 1        | 0.44%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                     | 1        | 0.44%   |
| Unknown RAM 7EH64AA# 8GB DIMM DDR4 2667MT/s                    | 1        | 0.44%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s          | 1        | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.44%   |
| Team RAM TEAMGROUP-UD3-1333 8GB DIMM DDR3 1333MT/s             | 1        | 0.44%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                     | 1        | 0.44%   |
| SK Hynix RAM S949A4UUH-ITR 16GB DIMM DDR4 2400MT/s             | 1        | 0.44%   |
| SK Hynix RAM HYMP512U64CP8-S5 1GB DIMM DDR2 400MT/s            | 1        | 0.44%   |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 400MT/s            | 1        | 0.44%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.44%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.44%   |
| SK Hynix RAM HMT41GE7BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.44%   |
| SK Hynix RAM HMT351U6CFR8C 4096MB DIMM DDR3 1333MT/s           | 1        | 0.44%   |
| SK Hynix RAM HMT325U7CFR8A-H9 2GB DIMM DDR3 1333MT/s           | 1        | 0.44%   |
| SK Hynix RAM HMT31GR7BFR4A-H9 8GB DIMM DDR3 1333MT/s           | 1        | 0.44%   |
| SK Hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 0.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 5        | 2.19%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s          | 5        | 2.19%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 4        | 1.75%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 3        | 1.32%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s              | 3        | 1.32%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 3        | 1.32%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 3        | 1.32%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s       | 3        | 1.32%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2        | 0.88%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 2        | 0.88%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 2        | 0.88%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                     | 2        | 0.88%   |
| Unknown RAM 99[2/7/4]164(F/R) 4GB DIMM DDR3 1600MT/s           | 2        | 0.88%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s            | 2        | 0.88%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 2        | 0.88%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s             | 2        | 0.88%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s           | 2        | 0.88%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s              | 2        | 0.88%   |
| Kingston RAM KHX2133C14D4/8G 8192MB DIMM DDR4 2667MT/s         | 2        | 0.88%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1867MT/s         | 2        | 0.88%   |
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1866MT/s         | 2        | 0.88%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s         | 2        | 0.88%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s         | 2        | 0.88%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s          | 2        | 0.88%   |
| Corsair RAM CMK32GX4M2A2666C16 16384MB DIMM DDR4 3100MT/s      | 2        | 0.88%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s          | 2        | 0.88%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s               | 1        | 0.44%   |
| Unknown RAM V02D4LF8GB5285282400 8192MB DIMM DDR4 2400MT/s     | 1        | 0.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.44%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM SDRAM 400MT/s                    | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                     | 1        | 0.44%   |
| Unknown RAM Module 4GB DIMM 800MT/s                            | 1        | 0.44%   |
| Unknown RAM Module 4GB DIMM 400MT/s                            | 1        | 0.44%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s                     | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM 400MT/s                            | 1        | 0.44%   |
| Unknown RAM Module 256MB DIMM SDRAM 400MT/s                    | 1        | 0.44%   |
| Unknown RAM Module 256MB DIMM                                  | 1        | 0.44%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1        | 0.44%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 1        | 0.44%   |
| Unknown RAM Module 1GB DIMM                                    | 1        | 0.44%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                     | 1        | 0.44%   |
| Unknown RAM 7EH64AA# 8GB DIMM DDR4 2667MT/s                    | 1        | 0.44%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s          | 1        | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.44%   |
| Team RAM TEAMGROUP-UD3-1333 8GB DIMM DDR3 1333MT/s             | 1        | 0.44%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                     | 1        | 0.44%   |
| SK Hynix RAM S949A4UUH-ITR 16GB DIMM DDR4 2400MT/s             | 1        | 0.44%   |
| SK Hynix RAM HYMP512U64CP8-S5 1GB DIMM DDR2 400MT/s            | 1        | 0.44%   |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 400MT/s            | 1        | 0.44%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.44%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.44%   |
| SK Hynix RAM HMT41GE7BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.44%   |
| SK Hynix RAM HMT351U6CFR8C 4096MB DIMM DDR3 1333MT/s           | 1        | 0.44%   |
| SK Hynix RAM HMT325U7CFR8A-H9 2GB DIMM DDR3 1333MT/s           | 1        | 0.44%   |
| SK Hynix RAM HMT31GR7BFR4A-H9 8GB DIMM DDR3 1333MT/s           | 1        | 0.44%   |
| SK Hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 87       | 49.43%  |
| DDR3    | 64       | 36.36%  |
| Unknown | 10       | 5.68%   |
| SDRAM   | 7        | 3.98%   |
| DDR2    | 7        | 3.98%   |
| LPDDR4  | 1        | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 87       | 49.43%  |
| DDR3    | 64       | 36.36%  |
| Unknown | 10       | 5.68%   |
| SDRAM   | 7        | 3.98%   |
| DDR2    | 7        | 3.98%   |
| LPDDR4  | 1        | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 169      | 96.57%  |
| SODIMM | 5        | 2.86%   |
| RIMM   | 1        | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 169      | 96.57%  |
| SODIMM | 5        | 2.86%   |
| RIMM   | 1        | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 79       | 40.51%  |
| 4096  | 39       | 20%     |
| 16384 | 31       | 15.9%   |
| 2048  | 20       | 10.26%  |
| 32768 | 11       | 5.64%   |
| 1024  | 9        | 4.62%   |
| 512   | 3        | 1.54%   |
| 256   | 2        | 1.03%   |
| 65536 | 1        | 0.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 79       | 40.51%  |
| 4096  | 39       | 20%     |
| 16384 | 31       | 15.9%   |
| 2048  | 20       | 10.26%  |
| 32768 | 11       | 5.64%   |
| 1024  | 9        | 4.62%   |
| 512   | 3        | 1.54%   |
| 256   | 2        | 1.03%   |
| 65536 | 1        | 0.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 42       | 20.9%   |
| 1333    | 25       | 12.44%  |
| 3200    | 21       | 10.45%  |
| 2667    | 15       | 7.46%   |
| 3600    | 12       | 5.97%   |
| 2400    | 12       | 5.97%   |
| 2933    | 6        | 2.99%   |
| 2666    | 6        | 2.99%   |
| 1867    | 6        | 2.99%   |
| 1866    | 6        | 2.99%   |
| 800     | 6        | 2.99%   |
| 3466    | 5        | 2.49%   |
| 2133    | 5        | 2.49%   |
| 3000    | 4        | 1.99%   |
| 667     | 4        | 1.99%   |
| Unknown | 4        | 1.99%   |
| 400     | 3        | 1.49%   |
| 3533    | 2        | 1%      |
| 3500    | 2        | 1%      |
| 3400    | 2        | 1%      |
| 3100    | 2        | 1%      |
| 2000    | 2        | 1%      |
| 1067    | 2        | 1%      |
| 3733    | 1        | 0.5%    |
| 3066    | 1        | 0.5%    |
| 2866    | 1        | 0.5%    |
| 2465    | 1        | 0.5%    |
| 1800    | 1        | 0.5%    |
| 1400    | 1        | 0.5%    |
| 1367    | 1        | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 42       | 20.9%   |
| 1333    | 25       | 12.44%  |
| 3200    | 21       | 10.45%  |
| 2667    | 15       | 7.46%   |
| 3600    | 12       | 5.97%   |
| 2400    | 12       | 5.97%   |
| 2933    | 6        | 2.99%   |
| 2666    | 6        | 2.99%   |
| 1867    | 6        | 2.99%   |
| 1866    | 6        | 2.99%   |
| 800     | 6        | 2.99%   |
| 3466    | 5        | 2.49%   |
| 2133    | 5        | 2.49%   |
| 3000    | 4        | 1.99%   |
| 667     | 4        | 1.99%   |
| Unknown | 4        | 1.99%   |
| 400     | 3        | 1.49%   |
| 3533    | 2        | 1%      |
| 3500    | 2        | 1%      |
| 3400    | 2        | 1%      |
| 3100    | 2        | 1%      |
| 2000    | 2        | 1%      |
| 1067    | 2        | 1%      |
| 3733    | 1        | 0.5%    |
| 3066    | 1        | 0.5%    |
| 2866    | 1        | 0.5%    |
| 2465    | 1        | 0.5%    |
| 1800    | 1        | 0.5%    |
| 1400    | 1        | 0.5%    |
| 1367    | 1        | 0.5%    |

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
| Logitech                      | 13       | 32.5%   |
| Microdia                      | 6        | 15%     |
| Samsung Electronics           | 3        | 7.5%    |
| Sunplus Innovation Technology | 2        | 5%      |
| Genesys Logic                 | 2        | 5%      |
| Generalplus Technology        | 2        | 5%      |
| Z-Star Microelectronics       | 1        | 2.5%    |
| Xiongmai                      | 1        | 2.5%    |
| SiGma Micro                   | 1        | 2.5%    |
| Razer USA                     | 1        | 2.5%    |
| Lenovo                        | 1        | 2.5%    |
| Huawei Technologies           | 1        | 2.5%    |
| Hewlett-Packard               | 1        | 2.5%    |
| eMPIA Technology              | 1        | 2.5%    |
| Creative Technology           | 1        | 2.5%    |
| AVerMedia Technologies        | 1        | 2.5%    |
| ARC International             | 1        | 2.5%    |
| Apple                         | 1        | 2.5%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 13       | 32.5%   |
| Microdia                      | 6        | 15%     |
| Samsung Electronics           | 3        | 7.5%    |
| Sunplus Innovation Technology | 2        | 5%      |
| Genesys Logic                 | 2        | 5%      |
| Generalplus Technology        | 2        | 5%      |
| Z-Star Microelectronics       | 1        | 2.5%    |
| Xiongmai                      | 1        | 2.5%    |
| SiGma Micro                   | 1        | 2.5%    |
| Razer USA                     | 1        | 2.5%    |
| Lenovo                        | 1        | 2.5%    |
| Huawei Technologies           | 1        | 2.5%    |
| Hewlett-Packard               | 1        | 2.5%    |
| eMPIA Technology              | 1        | 2.5%    |
| Creative Technology           | 1        | 2.5%    |
| AVerMedia Technologies        | 1        | 2.5%    |
| ARC International             | 1        | 2.5%    |
| Apple                         | 1        | 2.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Microdia Webcam Vitade AF           | 4        | 10%     |
| Samsung Galaxy A5 (MTP)             | 3        | 7.5%    |
| Logitech Webcam C270                | 3        | 7.5%    |
| Logitech HD Pro Webcam C920         | 3        | 7.5%    |
| Logitech HD Webcam C910             | 2        | 5%      |
| Logitech HD Webcam C615             | 2        | 5%      |
| Z-Star Venus USB2.0 Camera          | 1        | 2.5%    |
| Xiongmai web camera                 | 1        | 2.5%    |
| Sunplus HD USB Camaer 4K            | 1        | 2.5%    |
| Sunplus HD 720P webcam              | 1        | 2.5%    |
| SiGma Micro WebCam SiGma Micro      | 1        | 2.5%    |
| Razer USA Razer Kiyo                | 1        | 2.5%    |
| Microdia USB 2.0 Camera             | 1        | 2.5%    |
| Microdia Integrated Camera          | 1        | 2.5%    |
| Logitech Webcam C260                | 1        | 2.5%    |
| Logitech Quickcam 3000 For Business | 1        | 2.5%    |
| Logitech BRIO                       | 1        | 2.5%    |
| Lenovo FHD Webcam                   | 1        | 2.5%    |
| Huawei HiCamera                     | 1        | 2.5%    |
| HP Webcam 3110                      | 1        | 2.5%    |
| Genesys Logic USB2.0 Digital Camera | 1        | 2.5%    |
| Genesys Logic Camera                | 1        | 2.5%    |
| Generalplus GENERAL WEBCAM          | 1        | 2.5%    |
| Generalplus 808 Camera              | 1        | 2.5%    |
| eMPIA M035 Compact Web Cam          | 1        | 2.5%    |
| Creative Live! Cam Chat HD [VF0700] | 1        | 2.5%    |
| AVerMedia Live Gamer Ultra-Video    | 1        | 2.5%    |
| ARC International Camera            | 1        | 2.5%    |
| Apple iPhone 5/5C/5S/6/SE           | 1        | 2.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Microdia Webcam Vitade AF           | 4        | 10%     |
| Samsung Galaxy A5 (MTP)             | 3        | 7.5%    |
| Logitech Webcam C270                | 3        | 7.5%    |
| Logitech HD Pro Webcam C920         | 3        | 7.5%    |
| Logitech HD Webcam C910             | 2        | 5%      |
| Logitech HD Webcam C615             | 2        | 5%      |
| Z-Star Venus USB2.0 Camera          | 1        | 2.5%    |
| Xiongmai web camera                 | 1        | 2.5%    |
| Sunplus HD USB Camaer 4K            | 1        | 2.5%    |
| Sunplus HD 720P webcam              | 1        | 2.5%    |
| SiGma Micro WebCam SiGma Micro      | 1        | 2.5%    |
| Razer USA Razer Kiyo                | 1        | 2.5%    |
| Microdia USB 2.0 Camera             | 1        | 2.5%    |
| Microdia Integrated Camera          | 1        | 2.5%    |
| Logitech Webcam C260                | 1        | 2.5%    |
| Logitech Quickcam 3000 For Business | 1        | 2.5%    |
| Logitech BRIO                       | 1        | 2.5%    |
| Lenovo FHD Webcam                   | 1        | 2.5%    |
| Huawei HiCamera                     | 1        | 2.5%    |
| HP Webcam 3110                      | 1        | 2.5%    |
| Genesys Logic USB2.0 Digital Camera | 1        | 2.5%    |
| Genesys Logic Camera                | 1        | 2.5%    |
| Generalplus GENERAL WEBCAM          | 1        | 2.5%    |
| Generalplus 808 Camera              | 1        | 2.5%    |
| eMPIA M035 Compact Web Cam          | 1        | 2.5%    |
| Creative Live! Cam Chat HD [VF0700] | 1        | 2.5%    |
| AVerMedia Live Gamer Ultra-Video    | 1        | 2.5%    |
| ARC International Camera            | 1        | 2.5%    |
| Apple iPhone 5/5C/5S/6/SE           | 1        | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

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
| 0     | 171      | 90%     |
| 1     | 17       | 8.95%   |
| 5     | 1        | 0.53%   |
| 2     | 1        | 0.53%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 171      | 90%     |
| 1     | 17       | 8.95%   |
| 5     | 1        | 0.53%   |
| 2     | 1        | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 9        | 47.37%  |
| Unassigned class         | 4        | 21.05%  |
| Communication controller | 2        | 10.53%  |
| Sound                    | 1        | 5.26%   |
| Network                  | 1        | 5.26%   |
| Net/wireless             | 1        | 5.26%   |
| Multimedia controller    | 1        | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 9        | 47.37%  |
| Unassigned class         | 4        | 21.05%  |
| Communication controller | 2        | 10.53%  |
| Sound                    | 1        | 5.26%   |
| Network                  | 1        | 5.26%   |
| Net/wireless             | 1        | 5.26%   |
| Multimedia controller    | 1        | 5.26%   |

