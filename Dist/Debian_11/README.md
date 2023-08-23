Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

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

Total: 9378

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Notebook    | [2e76349d2c](https://linux-hardware.org/?probe=2e76349d2c) | Aug 12, 2023 |
| Unknown       | Unknown                     | Soc         | [a28cd220cd](https://linux-hardware.org/?probe=a28cd220cd) | Aug 12, 2023 |
| Unknown       | Unknown                     | Soc         | [f62d9a8a9a](https://linux-hardware.org/?probe=f62d9a8a9a) | Aug 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ed029dd5e3](https://linux-hardware.org/?probe=ed029dd5e3) | Aug 12, 2023 |
| ASRock        | J4125B-ITX                  | Desktop     | [fa9ebd523f](https://linux-hardware.org/?probe=fa9ebd523f) | Aug 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [053608e18a](https://linux-hardware.org/?probe=053608e18a) | Aug 11, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [9964e9a820](https://linux-hardware.org/?probe=9964e9a820) | Aug 11, 2023 |
| ASUSTek       | 1005PE                      | Notebook    | [088a155ec9](https://linux-hardware.org/?probe=088a155ec9) | Aug 10, 2023 |
| AZW           | GTR V01                     | Mini pc     | [8b0b0e8cc4](https://linux-hardware.org/?probe=8b0b0e8cc4) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2be2a9d5f4](https://linux-hardware.org/?probe=2be2a9d5f4) | Aug 09, 2023 |
| HP            | 8433 11                     | Desktop     | [93432b3df2](https://linux-hardware.org/?probe=93432b3df2) | Aug 09, 2023 |
| Unknown       | Unknown                     | Soc         | [42d4093f63](https://linux-hardware.org/?probe=42d4093f63) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [04d19635d5](https://linux-hardware.org/?probe=04d19635d5) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [671a686166](https://linux-hardware.org/?probe=671a686166) | Aug 08, 2023 |
| Biostar       | B365MHC                     | Desktop     | [1a7d051f1e](https://linux-hardware.org/?probe=1a7d051f1e) | Aug 06, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [4b57f7d6ea](https://linux-hardware.org/?probe=4b57f7d6ea) | Aug 06, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [217bd70a25](https://linux-hardware.org/?probe=217bd70a25) | Aug 06, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f529a830c](https://linux-hardware.org/?probe=2f529a830c) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [9d00f10bab](https://linux-hardware.org/?probe=9d00f10bab) | Aug 05, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [079428c572](https://linux-hardware.org/?probe=079428c572) | Aug 05, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [663f989185](https://linux-hardware.org/?probe=663f989185) | Aug 05, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [3aa0e077c0](https://linux-hardware.org/?probe=3aa0e077c0) | Aug 05, 2023 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [c157382bd3](https://linux-hardware.org/?probe=c157382bd3) | Aug 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [da2ada0c83](https://linux-hardware.org/?probe=da2ada0c83) | Aug 05, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [d930261042](https://linux-hardware.org/?probe=d930261042) | Aug 04, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [1b1f671f30](https://linux-hardware.org/?probe=1b1f671f30) | Aug 04, 2023 |
| Dell          | 0K095G A01                  | Desktop     | [ee2fb87d2f](https://linux-hardware.org/?probe=ee2fb87d2f) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [18f95b58ac](https://linux-hardware.org/?probe=18f95b58ac) | Aug 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [df3495c01c](https://linux-hardware.org/?probe=df3495c01c) | Aug 04, 2023 |
| HP            | Lantis                      | Notebook    | [2c917365b3](https://linux-hardware.org/?probe=2c917365b3) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [349de8928b](https://linux-hardware.org/?probe=349de8928b) | Aug 04, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [d74aab937a](https://linux-hardware.org/?probe=d74aab937a) | Aug 02, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [127555ff0c](https://linux-hardware.org/?probe=127555ff0c) | Aug 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4a4ac95dcc](https://linux-hardware.org/?probe=4a4ac95dcc) | Aug 01, 2023 |
| ASRock        | X300-ITX                    | Desktop     | [70a181c62b](https://linux-hardware.org/?probe=70a181c62b) | Jul 31, 2023 |
| Intel         | DH55HC AAE70933-502         | Desktop     | [e849da706a](https://linux-hardware.org/?probe=e849da706a) | Jul 31, 2023 |
| Packard Be... | H17HV                       | Notebook    | [de2003d390](https://linux-hardware.org/?probe=de2003d390) | Jul 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [11d7923fa3](https://linux-hardware.org/?probe=11d7923fa3) | Jul 31, 2023 |
| ASUSTek       | M4N78-AM                    | Desktop     | [a4740d2b14](https://linux-hardware.org/?probe=a4740d2b14) | Jul 31, 2023 |
| Gigabyte      | B550M K                     | Desktop     | [139e314619](https://linux-hardware.org/?probe=139e314619) | Jul 31, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [cd8671be26](https://linux-hardware.org/?probe=cd8671be26) | Jul 31, 2023 |
| NEC Comput... | PC-VY22GXZCA                | Notebook    | [180d6cf97d](https://linux-hardware.org/?probe=180d6cf97d) | Jul 31, 2023 |
| Intel         | NUC7i7DNB J83500-207        | Mini pc     | [e18855dc59](https://linux-hardware.org/?probe=e18855dc59) | Jul 30, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [80b81f5eff](https://linux-hardware.org/?probe=80b81f5eff) | Jul 30, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [f201460a34](https://linux-hardware.org/?probe=f201460a34) | Jul 30, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ffda715e5e](https://linux-hardware.org/?probe=ffda715e5e) | Jul 30, 2023 |
| Lenovo        | ThinkPad X220 42914XG       | Notebook    | [053a30cc87](https://linux-hardware.org/?probe=053a30cc87) | Jul 30, 2023 |
| Sony          | SVS13A1Z9RN                 | Notebook    | [533b3018ea](https://linux-hardware.org/?probe=533b3018ea) | Jul 29, 2023 |
| Dell          | Latitude 5520               | Notebook    | [5151c4275a](https://linux-hardware.org/?probe=5151c4275a) | Jul 29, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [532a72a722](https://linux-hardware.org/?probe=532a72a722) | Jul 29, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [76394a9fc7](https://linux-hardware.org/?probe=76394a9fc7) | Jul 29, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [4cbba6622f](https://linux-hardware.org/?probe=4cbba6622f) | Jul 28, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [8cf3decf30](https://linux-hardware.org/?probe=8cf3decf30) | Jul 28, 2023 |
| Acer          | Extensa 215-32              | Notebook    | [18d32a6c36](https://linux-hardware.org/?probe=18d32a6c36) | Jul 27, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [e873051e73](https://linux-hardware.org/?probe=e873051e73) | Jul 27, 2023 |
| Compaq        | PRESARIOCQ18                | Notebook    | [c528c90b50](https://linux-hardware.org/?probe=c528c90b50) | Jul 27, 2023 |
| ABIT          | NF7-S/NF7,NF7-V,1.0         | Desktop     | [f5184af4e0](https://linux-hardware.org/?probe=f5184af4e0) | Jul 27, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [b2dd23136f](https://linux-hardware.org/?probe=b2dd23136f) | Jul 26, 2023 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [c7373023dd](https://linux-hardware.org/?probe=c7373023dd) | Jul 26, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [9793da4c20](https://linux-hardware.org/?probe=9793da4c20) | Jul 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2fa28e6952](https://linux-hardware.org/?probe=2fa28e6952) | Jul 26, 2023 |
| ASRock        | X570 PG Velocita            | Desktop     | [64d86600a4](https://linux-hardware.org/?probe=64d86600a4) | Jul 26, 2023 |
| Dell          | 09CGW2 A04                  | Server      | [159d6b1be1](https://linux-hardware.org/?probe=159d6b1be1) | Jul 26, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [9cf2abf318](https://linux-hardware.org/?probe=9cf2abf318) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | Desktop     | [9791c84b0d](https://linux-hardware.org/?probe=9791c84b0d) | Jul 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [787c6a9252](https://linux-hardware.org/?probe=787c6a9252) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | Desktop     | [8e271c334d](https://linux-hardware.org/?probe=8e271c334d) | Jul 24, 2023 |
| HP            | ProLiant DL580 G7           | Server      | [5a9a1e320d](https://linux-hardware.org/?probe=5a9a1e320d) | Jul 24, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [9243bb6a08](https://linux-hardware.org/?probe=9243bb6a08) | Jul 24, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [980ed56abe](https://linux-hardware.org/?probe=980ed56abe) | Jul 24, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [73f0811a7b](https://linux-hardware.org/?probe=73f0811a7b) | Jul 23, 2023 |
| Dell          | Latitude E7250              | Notebook    | [4b91b375d4](https://linux-hardware.org/?probe=4b91b375d4) | Jul 23, 2023 |
| Dell          | Latitude 7480               | Notebook    | [acad753aa8](https://linux-hardware.org/?probe=acad753aa8) | Jul 23, 2023 |
| Dell          | 0K7CVF A03                  | Server      | [228949ef5a](https://linux-hardware.org/?probe=228949ef5a) | Jul 23, 2023 |
| Lenovo        | ThinkCentre M58 7360W1J     | Desktop     | [1e1e565ac4](https://linux-hardware.org/?probe=1e1e565ac4) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | Desktop     | [9297c88bef](https://linux-hardware.org/?probe=9297c88bef) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | Desktop     | [15827e6939](https://linux-hardware.org/?probe=15827e6939) | Jul 23, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [b2938336ce](https://linux-hardware.org/?probe=b2938336ce) | Jul 22, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [cdb9b29f94](https://linux-hardware.org/?probe=cdb9b29f94) | Jul 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [97edd15b78](https://linux-hardware.org/?probe=97edd15b78) | Jul 21, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | Notebook    | [fc45e9b064](https://linux-hardware.org/?probe=fc45e9b064) | Jul 21, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [a9214c4672](https://linux-hardware.org/?probe=a9214c4672) | Jul 21, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | Notebook    | [820630ba9e](https://linux-hardware.org/?probe=820630ba9e) | Jul 20, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8f26110e1a](https://linux-hardware.org/?probe=8f26110e1a) | Jul 20, 2023 |
| AAEON         | GENE-CML5 V1.0              | Desktop     | [4120e07431](https://linux-hardware.org/?probe=4120e07431) | Jul 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [98cddbfe0e](https://linux-hardware.org/?probe=98cddbfe0e) | Jul 18, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [8e456f1108](https://linux-hardware.org/?probe=8e456f1108) | Jul 18, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | Notebook    | [f789cd31fa](https://linux-hardware.org/?probe=f789cd31fa) | Jul 18, 2023 |
| ASUSTek       | Z87-C                       | Desktop     | [5324c1542f](https://linux-hardware.org/?probe=5324c1542f) | Jul 18, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [da4d6e8a5c](https://linux-hardware.org/?probe=da4d6e8a5c) | Jul 18, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [00c711574a](https://linux-hardware.org/?probe=00c711574a) | Jul 17, 2023 |
| HP            | 805A                        | Desktop     | [d4e6fca09f](https://linux-hardware.org/?probe=d4e6fca09f) | Jul 17, 2023 |
| ASUSTek       | X505BA                      | Notebook    | [fcd96492f0](https://linux-hardware.org/?probe=fcd96492f0) | Jul 17, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [a8b082a8be](https://linux-hardware.org/?probe=a8b082a8be) | Jul 17, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [6d77ef17a0](https://linux-hardware.org/?probe=6d77ef17a0) | Jul 17, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0d3af45e51](https://linux-hardware.org/?probe=0d3af45e51) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [0c592730d7](https://linux-hardware.org/?probe=0c592730d7) | Jul 16, 2023 |
| Dell          | Latitude E6440              | Notebook    | [c1de0cf4d1](https://linux-hardware.org/?probe=c1de0cf4d1) | Jul 16, 2023 |
| Dell          | Latitude E6320              | Notebook    | [0087a8e5cf](https://linux-hardware.org/?probe=0087a8e5cf) | Jul 16, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [65e4fb1356](https://linux-hardware.org/?probe=65e4fb1356) | Jul 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [1073620f0c](https://linux-hardware.org/?probe=1073620f0c) | Jul 16, 2023 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [15d31e889c](https://linux-hardware.org/?probe=15d31e889c) | Jul 16, 2023 |
| Unknown       | Unknown                     | Soc         | [99bfa94ff7](https://linux-hardware.org/?probe=99bfa94ff7) | Jul 16, 2023 |
| GEEKOM        | Mini IT 8                   | Desktop     | [4754a5fc1b](https://linux-hardware.org/?probe=4754a5fc1b) | Jul 16, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [d2620e5fee](https://linux-hardware.org/?probe=d2620e5fee) | Jul 16, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [9161db3013](https://linux-hardware.org/?probe=9161db3013) | Jul 15, 2023 |
| ASUSTek       | Z87-C                       | Desktop     | [33e96d6f34](https://linux-hardware.org/?probe=33e96d6f34) | Jul 15, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [4a6f56c54a](https://linux-hardware.org/?probe=4a6f56c54a) | Jul 15, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | Notebook    | [8d3168b6c4](https://linux-hardware.org/?probe=8d3168b6c4) | Jul 15, 2023 |
| Acer          | Aspire R7-371T              | Notebook    | [c4f6270bdb](https://linux-hardware.org/?probe=c4f6270bdb) | Jul 15, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [8ca31a1cfb](https://linux-hardware.org/?probe=8ca31a1cfb) | Jul 15, 2023 |
| Intel         | M70KLP2SB M22209-100        | Server      | [afa5fbc4a3](https://linux-hardware.org/?probe=afa5fbc4a3) | Jul 14, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [19fdd69149](https://linux-hardware.org/?probe=19fdd69149) | Jul 14, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [e6d47a005f](https://linux-hardware.org/?probe=e6d47a005f) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | Notebook    | [ae8ecf10e7](https://linux-hardware.org/?probe=ae8ecf10e7) | Jul 13, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [42aba63af0](https://linux-hardware.org/?probe=42aba63af0) | Jul 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c4af2e9b6c](https://linux-hardware.org/?probe=c4af2e9b6c) | Jul 13, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [70b2ff6533](https://linux-hardware.org/?probe=70b2ff6533) | Jul 13, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [13f3a107dc](https://linux-hardware.org/?probe=13f3a107dc) | Jul 13, 2023 |
| MSI           | H170M PRO-VDH               | Desktop     | [ce0a8a33fb](https://linux-hardware.org/?probe=ce0a8a33fb) | Jul 13, 2023 |
| Dell          | Latitude E6330              | Notebook    | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| ASRockRack    | ROMED8QM-2T                 | Desktop     | [a4fe5ea9c9](https://linux-hardware.org/?probe=a4fe5ea9c9) | Jul 13, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [1976f92f56](https://linux-hardware.org/?probe=1976f92f56) | Jul 12, 2023 |
| Positivo      | Mobile                      | Notebook    | [463636c0a2](https://linux-hardware.org/?probe=463636c0a2) | Jul 12, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [27a207ead6](https://linux-hardware.org/?probe=27a207ead6) | Jul 12, 2023 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [3a06b254a5](https://linux-hardware.org/?probe=3a06b254a5) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | Desktop     | [b330e5c4fb](https://linux-hardware.org/?probe=b330e5c4fb) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | Desktop     | [c0fb949fdc](https://linux-hardware.org/?probe=c0fb949fdc) | Jul 12, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [3866c4a7ff](https://linux-hardware.org/?probe=3866c4a7ff) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [ab432dcb0e](https://linux-hardware.org/?probe=ab432dcb0e) | Jul 11, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [58fb207824](https://linux-hardware.org/?probe=58fb207824) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [d7209e7141](https://linux-hardware.org/?probe=d7209e7141) | Jul 11, 2023 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [02a820f6b2](https://linux-hardware.org/?probe=02a820f6b2) | Jul 11, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [544563aaae](https://linux-hardware.org/?probe=544563aaae) | Jul 11, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [8d33346009](https://linux-hardware.org/?probe=8d33346009) | Jul 10, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [33aa3fcdbc](https://linux-hardware.org/?probe=33aa3fcdbc) | Jul 10, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [1e6fc6f253](https://linux-hardware.org/?probe=1e6fc6f253) | Jul 10, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [16aac702d5](https://linux-hardware.org/?probe=16aac702d5) | Jul 10, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [ae3e8910bf](https://linux-hardware.org/?probe=ae3e8910bf) | Jul 10, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [437e2c44d9](https://linux-hardware.org/?probe=437e2c44d9) | Jul 09, 2023 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [6381f6da84](https://linux-hardware.org/?probe=6381f6da84) | Jul 09, 2023 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [f9d1d19d05](https://linux-hardware.org/?probe=f9d1d19d05) | Jul 09, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ba7cde1766](https://linux-hardware.org/?probe=ba7cde1766) | Jul 09, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [798f921e70](https://linux-hardware.org/?probe=798f921e70) | Jul 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [89a5a4461f](https://linux-hardware.org/?probe=89a5a4461f) | Jul 09, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [003c30f690](https://linux-hardware.org/?probe=003c30f690) | Jul 09, 2023 |
| AZW           | U59                         | Desktop     | [5cf3ddbe4b](https://linux-hardware.org/?probe=5cf3ddbe4b) | Jul 08, 2023 |
| AZW           | U59                         | Desktop     | [ea367423d1](https://linux-hardware.org/?probe=ea367423d1) | Jul 08, 2023 |
| AZW           | MINI S                      | Desktop     | [b13eb96728](https://linux-hardware.org/?probe=b13eb96728) | Jul 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [0a2ad7c1a6](https://linux-hardware.org/?probe=0a2ad7c1a6) | Jul 08, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [cbc100e6b1](https://linux-hardware.org/?probe=cbc100e6b1) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [3177785c7f](https://linux-hardware.org/?probe=3177785c7f) | Jul 07, 2023 |
| Lenovo        | ThinkPad T450s 20BWS0PJ0... | Notebook    | [2345d00757](https://linux-hardware.org/?probe=2345d00757) | Jul 07, 2023 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [6afd29fd20](https://linux-hardware.org/?probe=6afd29fd20) | Jul 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f4b26c97fe](https://linux-hardware.org/?probe=f4b26c97fe) | Jul 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8daacdd31c](https://linux-hardware.org/?probe=8daacdd31c) | Jul 06, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [4bbbfd7eb9](https://linux-hardware.org/?probe=4bbbfd7eb9) | Jul 05, 2023 |
| HP            | 895C                        | Desktop     | [8a7f102530](https://linux-hardware.org/?probe=8a7f102530) | Jul 05, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [69d01e9a98](https://linux-hardware.org/?probe=69d01e9a98) | Jul 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e57d7c40d](https://linux-hardware.org/?probe=1e57d7c40d) | Jul 05, 2023 |
| NEC Comput... | PC-VK27MBZCG                | Notebook    | [5db0d02025](https://linux-hardware.org/?probe=5db0d02025) | Jul 04, 2023 |
| Dell          | 0KYWH7 A00                  | Desktop     | [0c16b66976](https://linux-hardware.org/?probe=0c16b66976) | Jul 04, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [b7328dc212](https://linux-hardware.org/?probe=b7328dc212) | Jul 04, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [234e7f985d](https://linux-hardware.org/?probe=234e7f985d) | Jul 04, 2023 |
| Dell          | 0X904N A05                  | Server      | [b7335a46c8](https://linux-hardware.org/?probe=b7335a46c8) | Jul 03, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [e000de29fe](https://linux-hardware.org/?probe=e000de29fe) | Jul 03, 2023 |
| EPoX Compu... | Intel I945 DDR2 : 5P945-... | Desktop     | [5aa77af58f](https://linux-hardware.org/?probe=5aa77af58f) | Jul 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8bb4af1cb5](https://linux-hardware.org/?probe=8bb4af1cb5) | Jul 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7cd68e8f8b](https://linux-hardware.org/?probe=7cd68e8f8b) | Jul 03, 2023 |
| Gigabyte      | B550 UD AC                  | Desktop     | [8e758ec922](https://linux-hardware.org/?probe=8e758ec922) | Jul 03, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [ed37dd6278](https://linux-hardware.org/?probe=ed37dd6278) | Jul 03, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [f17cce1847](https://linux-hardware.org/?probe=f17cce1847) | Jul 02, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [2eb6c4356c](https://linux-hardware.org/?probe=2eb6c4356c) | Jul 02, 2023 |
| Unknown       | Unknown                     | Soc         | [bc8f4620bd](https://linux-hardware.org/?probe=bc8f4620bd) | Jul 02, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a66c76ab6c](https://linux-hardware.org/?probe=a66c76ab6c) | Jul 02, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [bac142132d](https://linux-hardware.org/?probe=bac142132d) | Jul 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [24adbf0475](https://linux-hardware.org/?probe=24adbf0475) | Jul 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [bd84f79486](https://linux-hardware.org/?probe=bd84f79486) | Jul 01, 2023 |
| NetGear       | ReadyDATA 5200              | Desktop     | [b89ca471ef](https://linux-hardware.org/?probe=b89ca471ef) | Jul 01, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4d4d992cb0](https://linux-hardware.org/?probe=4d4d992cb0) | Jul 01, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [7e37520061](https://linux-hardware.org/?probe=7e37520061) | Jun 30, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [cb1bcce659](https://linux-hardware.org/?probe=cb1bcce659) | Jun 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7cb124d729](https://linux-hardware.org/?probe=7cb124d729) | Jun 30, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [0fae87e118](https://linux-hardware.org/?probe=0fae87e118) | Jun 29, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [b9291d6951](https://linux-hardware.org/?probe=b9291d6951) | Jun 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [62ff10cadc](https://linux-hardware.org/?probe=62ff10cadc) | Jun 29, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b6c2bcb025](https://linux-hardware.org/?probe=b6c2bcb025) | Jun 29, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [f40af0020a](https://linux-hardware.org/?probe=f40af0020a) | Jun 29, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [305a3e3c1a](https://linux-hardware.org/?probe=305a3e3c1a) | Jun 29, 2023 |
| Dell          | Latitude 7370               | Notebook    | [cb11921012](https://linux-hardware.org/?probe=cb11921012) | Jun 28, 2023 |
| Shuttle       | FS61                        | Desktop     | [a67d2edea8](https://linux-hardware.org/?probe=a67d2edea8) | Jun 28, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [f60ead06fd](https://linux-hardware.org/?probe=f60ead06fd) | Jun 28, 2023 |
| Lenovo        | ThinkPad X280 20KF001RUK    | Notebook    | [a1da72b9a5](https://linux-hardware.org/?probe=a1da72b9a5) | Jun 27, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [65fb07ed8d](https://linux-hardware.org/?probe=65fb07ed8d) | Jun 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [1143a7eebc](https://linux-hardware.org/?probe=1143a7eebc) | Jun 27, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [baf77629c1](https://linux-hardware.org/?probe=baf77629c1) | Jun 26, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [fe211e4239](https://linux-hardware.org/?probe=fe211e4239) | Jun 26, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [b4fcf1904c](https://linux-hardware.org/?probe=b4fcf1904c) | Jun 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [29cc577c0c](https://linux-hardware.org/?probe=29cc577c0c) | Jun 26, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [695dd94347](https://linux-hardware.org/?probe=695dd94347) | Jun 25, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [a65485d236](https://linux-hardware.org/?probe=a65485d236) | Jun 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [9dce40179d](https://linux-hardware.org/?probe=9dce40179d) | Jun 25, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [356b066ca9](https://linux-hardware.org/?probe=356b066ca9) | Jun 24, 2023 |
| Google        | Kip                         | Notebook    | [4e1bfd359e](https://linux-hardware.org/?probe=4e1bfd359e) | Jun 24, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [2b61a56610](https://linux-hardware.org/?probe=2b61a56610) | Jun 24, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [53dbc2e799](https://linux-hardware.org/?probe=53dbc2e799) | Jun 24, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [2d49269787](https://linux-hardware.org/?probe=2d49269787) | Jun 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4a11a4190a](https://linux-hardware.org/?probe=4a11a4190a) | Jun 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [71f114122e](https://linux-hardware.org/?probe=71f114122e) | Jun 23, 2023 |
| Lenovo        | Edge 15 80H1                | Notebook    | [aff25effc2](https://linux-hardware.org/?probe=aff25effc2) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [6d8c00ff02](https://linux-hardware.org/?probe=6d8c00ff02) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [1c1a2724f4](https://linux-hardware.org/?probe=1c1a2724f4) | Jun 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [1ca06fb3a9](https://linux-hardware.org/?probe=1ca06fb3a9) | Jun 23, 2023 |
| HP            | 3397                        | Desktop     | [8c9be2f4c0](https://linux-hardware.org/?probe=8c9be2f4c0) | Jun 23, 2023 |
| VIT           | P2423                       | Notebook    | [19242b2ddb](https://linux-hardware.org/?probe=19242b2ddb) | Jun 23, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [d419086209](https://linux-hardware.org/?probe=d419086209) | Jun 22, 2023 |
| Supermicro    | X8DTU                       | Server      | [d8d978bd73](https://linux-hardware.org/?probe=d8d978bd73) | Jun 22, 2023 |
| HP            | 3397                        | Desktop     | [a47ce0d4dc](https://linux-hardware.org/?probe=a47ce0d4dc) | Jun 22, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [1cdf3502e8](https://linux-hardware.org/?probe=1cdf3502e8) | Jun 21, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [7bbc89ec0f](https://linux-hardware.org/?probe=7bbc89ec0f) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [a7b7b2c413](https://linux-hardware.org/?probe=a7b7b2c413) | Jun 21, 2023 |
| Dell          | Latitude E5550              | Notebook    | [72f4d53246](https://linux-hardware.org/?probe=72f4d53246) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [d4bd011ff9](https://linux-hardware.org/?probe=d4bd011ff9) | Jun 21, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [76fbd356a0](https://linux-hardware.org/?probe=76fbd356a0) | Jun 21, 2023 |
| Dell          | Latitude E5550              | Notebook    | [e1fdcf84b3](https://linux-hardware.org/?probe=e1fdcf84b3) | Jun 21, 2023 |
| libre-comp... | roc-rk3328-cc               | Soc         | [f18c138ec9](https://linux-hardware.org/?probe=f18c138ec9) | Jun 21, 2023 |
| Lenovo        | 01GR176                     | Server      | [6d28cbec97](https://linux-hardware.org/?probe=6d28cbec97) | Jun 21, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [9e0ba5032b](https://linux-hardware.org/?probe=9e0ba5032b) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [291796e3e4](https://linux-hardware.org/?probe=291796e3e4) | Jun 21, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [6bbc56b36c](https://linux-hardware.org/?probe=6bbc56b36c) | Jun 20, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [16c4045c3b](https://linux-hardware.org/?probe=16c4045c3b) | Jun 20, 2023 |
| MSI           | H81M-P33                    | Desktop     | [62fb9cda50](https://linux-hardware.org/?probe=62fb9cda50) | Jun 20, 2023 |
| Dell          | 06FW8P A02                  | Desktop     | [f65ec61ffc](https://linux-hardware.org/?probe=f65ec61ffc) | Jun 20, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [98626bde6c](https://linux-hardware.org/?probe=98626bde6c) | Jun 20, 2023 |
| Dell          | Latitude 3410               | Notebook    | [1e0348842a](https://linux-hardware.org/?probe=1e0348842a) | Jun 19, 2023 |
| Amlogic       | Meson GXL (S905X) P212 D... | Soc         | [7c79fa6641](https://linux-hardware.org/?probe=7c79fa6641) | Jun 19, 2023 |
| Dell          | 0PU052                      | Desktop     | [2eb6dceca9](https://linux-hardware.org/?probe=2eb6dceca9) | Jun 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3eab70981f](https://linux-hardware.org/?probe=3eab70981f) | Jun 19, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [1559b0a68d](https://linux-hardware.org/?probe=1559b0a68d) | Jun 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [640ff2ce2e](https://linux-hardware.org/?probe=640ff2ce2e) | Jun 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d8d9101ef6](https://linux-hardware.org/?probe=d8d9101ef6) | Jun 19, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [33785e2493](https://linux-hardware.org/?probe=33785e2493) | Jun 18, 2023 |
| AZW           | U59                         | Desktop     | [6f1191e5e2](https://linux-hardware.org/?probe=6f1191e5e2) | Jun 18, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [f431c0b66f](https://linux-hardware.org/?probe=f431c0b66f) | Jun 18, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [7d246caf6f](https://linux-hardware.org/?probe=7d246caf6f) | Jun 18, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [ec95321dfb](https://linux-hardware.org/?probe=ec95321dfb) | Jun 17, 2023 |
| Dell          | Precision M2800             | Notebook    | [e9f259595a](https://linux-hardware.org/?probe=e9f259595a) | Jun 17, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [19e270cab0](https://linux-hardware.org/?probe=19e270cab0) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [e4b27c6a92](https://linux-hardware.org/?probe=e4b27c6a92) | Jun 16, 2023 |
| Dell          | Latitude D620               | Notebook    | [8dc25931d7](https://linux-hardware.org/?probe=8dc25931d7) | Jun 16, 2023 |
| Dell          | Latitude D620               | Notebook    | [819f346812](https://linux-hardware.org/?probe=819f346812) | Jun 16, 2023 |
| Dell          | Latitude E6400              | Notebook    | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | Desktop     | [9994571651](https://linux-hardware.org/?probe=9994571651) | Jun 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1cabb1c87f](https://linux-hardware.org/?probe=1cabb1c87f) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [67ed3346c2](https://linux-hardware.org/?probe=67ed3346c2) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [07f1089ee7](https://linux-hardware.org/?probe=07f1089ee7) | Jun 15, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b55662cc58](https://linux-hardware.org/?probe=b55662cc58) | Jun 15, 2023 |
| HP            | 1589                        | Desktop     | [6bfe1d5b63](https://linux-hardware.org/?probe=6bfe1d5b63) | Jun 15, 2023 |
| Medion        | E6214                       | Notebook    | [71b2e69534](https://linux-hardware.org/?probe=71b2e69534) | Jun 15, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [c1375ab639](https://linux-hardware.org/?probe=c1375ab639) | Jun 15, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2754ddde7f](https://linux-hardware.org/?probe=2754ddde7f) | Jun 15, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [4cc6199522](https://linux-hardware.org/?probe=4cc6199522) | Jun 15, 2023 |
| Dell          | Latitude 5480               | Notebook    | [677cb87f98](https://linux-hardware.org/?probe=677cb87f98) | Jun 14, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [6e241e56cf](https://linux-hardware.org/?probe=6e241e56cf) | Jun 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f9ebdca1bd](https://linux-hardware.org/?probe=f9ebdca1bd) | Jun 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [b639a64b45](https://linux-hardware.org/?probe=b639a64b45) | Jun 14, 2023 |
| Supermicro    | X11DPU                      | Server      | [f7937cfbf6](https://linux-hardware.org/?probe=f7937cfbf6) | Jun 14, 2023 |
| Supermicro    | X11DPH-T                    | Server      | [ed5dc59bc2](https://linux-hardware.org/?probe=ed5dc59bc2) | Jun 14, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [3b954125c5](https://linux-hardware.org/?probe=3b954125c5) | Jun 13, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [84cd8a6537](https://linux-hardware.org/?probe=84cd8a6537) | Jun 13, 2023 |
| HP            | 2AED                        | Desktop     | [2550c16272](https://linux-hardware.org/?probe=2550c16272) | Jun 13, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [b8631b65c4](https://linux-hardware.org/?probe=b8631b65c4) | Jun 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3c113d457b](https://linux-hardware.org/?probe=3c113d457b) | Jun 13, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [97b6ba8bd6](https://linux-hardware.org/?probe=97b6ba8bd6) | Jun 13, 2023 |
| Intel         | JSL MRD                     | Desktop     | [764e533752](https://linux-hardware.org/?probe=764e533752) | Jun 13, 2023 |
| Dell          | Inspiron 1521               | Notebook    | [b4a1eae7be](https://linux-hardware.org/?probe=b4a1eae7be) | Jun 12, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [675f082570](https://linux-hardware.org/?probe=675f082570) | Jun 12, 2023 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [d2ee0bc234](https://linux-hardware.org/?probe=d2ee0bc234) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | Notebook    | [45b16c1cdf](https://linux-hardware.org/?probe=45b16c1cdf) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | Notebook    | [1da963b3f4](https://linux-hardware.org/?probe=1da963b3f4) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | Notebook    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [2ea9fd5a4a](https://linux-hardware.org/?probe=2ea9fd5a4a) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [9ed0a99c90](https://linux-hardware.org/?probe=9ed0a99c90) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [5bc42066ca](https://linux-hardware.org/?probe=5bc42066ca) | Jun 12, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [f7397ff305](https://linux-hardware.org/?probe=f7397ff305) | Jun 11, 2023 |
| Lenovo        | ThinkPad T420s 4175A16      | Notebook    | [3d23465019](https://linux-hardware.org/?probe=3d23465019) | Jun 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [59a9e7e2e8](https://linux-hardware.org/?probe=59a9e7e2e8) | Jun 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [5e3b6bfb4c](https://linux-hardware.org/?probe=5e3b6bfb4c) | Jun 11, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [8772d55075](https://linux-hardware.org/?probe=8772d55075) | Jun 10, 2023 |
| Dell          | Latitude 7440               | Notebook    | [f63ada6c61](https://linux-hardware.org/?probe=f63ada6c61) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | Notebook    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | Notebook    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [4dcc51e897](https://linux-hardware.org/?probe=4dcc51e897) | Jun 10, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [e54f1a9447](https://linux-hardware.org/?probe=e54f1a9447) | Jun 10, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [65b3c16165](https://linux-hardware.org/?probe=65b3c16165) | Jun 10, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ba4527394e](https://linux-hardware.org/?probe=ba4527394e) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | Notebook    | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| Acidanther... | MacBookPro15,2              | Notebook    | [fb30b2eb35](https://linux-hardware.org/?probe=fb30b2eb35) | Jun 10, 2023 |
| IBM           | FAB2 Controller Producti... | Server      | [af396cb333](https://linux-hardware.org/?probe=af396cb333) | Jun 10, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [012e8255f3](https://linux-hardware.org/?probe=012e8255f3) | Jun 09, 2023 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [b47fab6285](https://linux-hardware.org/?probe=b47fab6285) | Jun 09, 2023 |
| Intel         | powered classmate PC        | Notebook    | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ea724e204b](https://linux-hardware.org/?probe=ea724e204b) | Jun 09, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [e37bceb6fb](https://linux-hardware.org/?probe=e37bceb6fb) | Jun 09, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [c66d30943e](https://linux-hardware.org/?probe=c66d30943e) | Jun 09, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [9536bf547a](https://linux-hardware.org/?probe=9536bf547a) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [ab35c95b72](https://linux-hardware.org/?probe=ab35c95b72) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [bcad738da6](https://linux-hardware.org/?probe=bcad738da6) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [6b42200bee](https://linux-hardware.org/?probe=6b42200bee) | Jun 09, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [50844825e2](https://linux-hardware.org/?probe=50844825e2) | Jun 08, 2023 |
| HP            | G42                         | Notebook    | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | G42                         | Notebook    | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [0fa009ad04](https://linux-hardware.org/?probe=0fa009ad04) | Jun 08, 2023 |
| Inventec      | VXC Class A02               | Desktop     | [c2bc26120f](https://linux-hardware.org/?probe=c2bc26120f) | Jun 08, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [230465c003](https://linux-hardware.org/?probe=230465c003) | Jun 08, 2023 |
| MSI           | GE60 2PL                    | Notebook    | [e1d118e2d2](https://linux-hardware.org/?probe=e1d118e2d2) | Jun 08, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [09b2301e59](https://linux-hardware.org/?probe=09b2301e59) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | Notebook    | [d992393271](https://linux-hardware.org/?probe=d992393271) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | Notebook    | [dd385507aa](https://linux-hardware.org/?probe=dd385507aa) | Jun 08, 2023 |
| HP            | Pavilion 17                 | Notebook    | [da809f90cc](https://linux-hardware.org/?probe=da809f90cc) | Jun 07, 2023 |
| Dell          | Latitude 5530               | Notebook    | [1e3452635f](https://linux-hardware.org/?probe=1e3452635f) | Jun 07, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [7ed0f0346c](https://linux-hardware.org/?probe=7ed0f0346c) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| HP            | ProBook 4530s               | Notebook    | [bdb6739deb](https://linux-hardware.org/?probe=bdb6739deb) | Jun 07, 2023 |
| Intel         | HURONRIVER                  | Notebook    | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| Lenovo        | ThinkCentre A58e 0841B4Y    | Desktop     | [fe410cd5db](https://linux-hardware.org/?probe=fe410cd5db) | Jun 07, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [490ae0bc1c](https://linux-hardware.org/?probe=490ae0bc1c) | Jun 07, 2023 |
| MSI           | Pulse GL66 12UDK            | Notebook    | [8c9a9eb310](https://linux-hardware.org/?probe=8c9a9eb310) | Jun 06, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [2532dfadd0](https://linux-hardware.org/?probe=2532dfadd0) | Jun 06, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [5cc10b1e1e](https://linux-hardware.org/?probe=5cc10b1e1e) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| HP            | Pavilion g7                 | Notebook    | [f8cccf0fec](https://linux-hardware.org/?probe=f8cccf0fec) | Jun 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [be9987ca28](https://linux-hardware.org/?probe=be9987ca28) | Jun 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [c685007aa8](https://linux-hardware.org/?probe=c685007aa8) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d288737b23](https://linux-hardware.org/?probe=d288737b23) | Jun 05, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [22143d333a](https://linux-hardware.org/?probe=22143d333a) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [3a1c1daa3d](https://linux-hardware.org/?probe=3a1c1daa3d) | Jun 05, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [72eb9f0d86](https://linux-hardware.org/?probe=72eb9f0d86) | Jun 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [da03bf4e08](https://linux-hardware.org/?probe=da03bf4e08) | Jun 05, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [e7bbac1b14](https://linux-hardware.org/?probe=e7bbac1b14) | Jun 04, 2023 |
| Dell          | Latitude 3410               | Notebook    | [820e62c9d3](https://linux-hardware.org/?probe=820e62c9d3) | Jun 04, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | GL75 Leopard 10SER          | Notebook    | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| Dell          | Latitude 3410               | Notebook    | [12515d41c8](https://linux-hardware.org/?probe=12515d41c8) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [0bd883cae2](https://linux-hardware.org/?probe=0bd883cae2) | Jun 04, 2023 |
| ASUSTek       | Q502LA                      | Notebook    | [679a477085](https://linux-hardware.org/?probe=679a477085) | Jun 04, 2023 |
| Clevo         | M670SRU                     | Notebook    | [0935f74d34](https://linux-hardware.org/?probe=0935f74d34) | Jun 04, 2023 |
| Clevo         | M670SRU                     | Notebook    | [e163d57d56](https://linux-hardware.org/?probe=e163d57d56) | Jun 04, 2023 |
| AVITA         | NS14A8                      | Notebook    | [a576b4d5cc](https://linux-hardware.org/?probe=a576b4d5cc) | Jun 04, 2023 |
| Toshiba       | WT8-A                       | Notebook    | [01e8918ef6](https://linux-hardware.org/?probe=01e8918ef6) | Jun 04, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [8690705151](https://linux-hardware.org/?probe=8690705151) | Jun 04, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [138d22e03e](https://linux-hardware.org/?probe=138d22e03e) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | Notebook    | [a10a42a44d](https://linux-hardware.org/?probe=a10a42a44d) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | Notebook    | [e58b2a1237](https://linux-hardware.org/?probe=e58b2a1237) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | Notebook    | [ce54d0192d](https://linux-hardware.org/?probe=ce54d0192d) | Jun 04, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [18cb6a946b](https://linux-hardware.org/?probe=18cb6a946b) | Jun 03, 2023 |
| Lenovo        | ThinkPad E420 1141R79       | Notebook    | [7f66bf0045](https://linux-hardware.org/?probe=7f66bf0045) | Jun 03, 2023 |
| Acer          | Aspire V3-372               | Notebook    | [1200863830](https://linux-hardware.org/?probe=1200863830) | Jun 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [8d4d1f7313](https://linux-hardware.org/?probe=8d4d1f7313) | Jun 03, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [b1513dc005](https://linux-hardware.org/?probe=b1513dc005) | Jun 03, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [5bd684bed6](https://linux-hardware.org/?probe=5bd684bed6) | Jun 02, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [f454cdf394](https://linux-hardware.org/?probe=f454cdf394) | Jun 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Gigabyte      | P75-D3                      | Desktop     | [a56c3ceb55](https://linux-hardware.org/?probe=a56c3ceb55) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [9bf36ef4a5](https://linux-hardware.org/?probe=9bf36ef4a5) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d6561ecd7b](https://linux-hardware.org/?probe=d6561ecd7b) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
| ASUSTek       | Z87-C                       | Desktop     | [20242d8299](https://linux-hardware.org/?probe=20242d8299) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Dell          | Latitude E6430              | Notebook    | [b129765265](https://linux-hardware.org/?probe=b129765265) | Jun 02, 2023 |
| Dell          | 0D456H A00                  | Server      | [4e0d53d64d](https://linux-hardware.org/?probe=4e0d53d64d) | Jun 02, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [5846820609](https://linux-hardware.org/?probe=5846820609) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [81ec1cc134](https://linux-hardware.org/?probe=81ec1cc134) | Jun 01, 2023 |
| Intel         | NUC11ATBPE M49844-202       | Mini pc     | [2a1e548be7](https://linux-hardware.org/?probe=2a1e548be7) | Jun 01, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [e00e626ea6](https://linux-hardware.org/?probe=e00e626ea6) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Dell          | Latitude E5510              | Notebook    | [4a0bc9e53f](https://linux-hardware.org/?probe=4a0bc9e53f) | Jun 01, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [ea09e45a4f](https://linux-hardware.org/?probe=ea09e45a4f) | Jun 01, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [78e4d7a22b](https://linux-hardware.org/?probe=78e4d7a22b) | Jun 01, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [5fc6ec135b](https://linux-hardware.org/?probe=5fc6ec135b) | Jun 01, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [31e0f624be](https://linux-hardware.org/?probe=31e0f624be) | Jun 01, 2023 |
| Dell          | Latitude E5510              | Notebook    | [9457826049](https://linux-hardware.org/?probe=9457826049) | Jun 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a4363d8242](https://linux-hardware.org/?probe=a4363d8242) | Jun 01, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [19043cab25](https://linux-hardware.org/?probe=19043cab25) | Jun 01, 2023 |
| Positivo      | C500                        | Notebook    | [8dba4589fe](https://linux-hardware.org/?probe=8dba4589fe) | Jun 01, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [5f1045564e](https://linux-hardware.org/?probe=5f1045564e) | Jun 01, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [433df815db](https://linux-hardware.org/?probe=433df815db) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | Notebook    | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| ASUSTek       | 1225B                       | Notebook    | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [32a85827df](https://linux-hardware.org/?probe=32a85827df) | May 31, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [8459f7cfee](https://linux-hardware.org/?probe=8459f7cfee) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [5f8bd19e3d](https://linux-hardware.org/?probe=5f8bd19e3d) | May 31, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [1e5f49bbf4](https://linux-hardware.org/?probe=1e5f49bbf4) | May 31, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [354e883340](https://linux-hardware.org/?probe=354e883340) | May 31, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [aad1baf686](https://linux-hardware.org/?probe=aad1baf686) | May 31, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [41177ef027](https://linux-hardware.org/?probe=41177ef027) | May 31, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [166031ba4d](https://linux-hardware.org/?probe=166031ba4d) | May 31, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [8f55c9aa98](https://linux-hardware.org/?probe=8f55c9aa98) | May 31, 2023 |
| Dell          | Latitude 5411               | Notebook    | [8583aa2091](https://linux-hardware.org/?probe=8583aa2091) | May 31, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [ad0b57d7c6](https://linux-hardware.org/?probe=ad0b57d7c6) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [e065b72b88](https://linux-hardware.org/?probe=e065b72b88) | May 31, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [7709d9fd16](https://linux-hardware.org/?probe=7709d9fd16) | May 31, 2023 |
| Dell          | Latitude E5510              | Notebook    | [52e1023195](https://linux-hardware.org/?probe=52e1023195) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [52047d2230](https://linux-hardware.org/?probe=52047d2230) | May 31, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [8a18b7bada](https://linux-hardware.org/?probe=8a18b7bada) | May 31, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [611cf59f44](https://linux-hardware.org/?probe=611cf59f44) | May 31, 2023 |
| Intel         | X99                         | Desktop     | [cef654d9c5](https://linux-hardware.org/?probe=cef654d9c5) | May 30, 2023 |
| Dell          | Latitude E5510              | Notebook    | [aa0f6a81b6](https://linux-hardware.org/?probe=aa0f6a81b6) | May 30, 2023 |
| ASUSTek       | P4S8L                       | Desktop     | [c26269028e](https://linux-hardware.org/?probe=c26269028e) | May 30, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [3222c41173](https://linux-hardware.org/?probe=3222c41173) | May 30, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [698e3b5e35](https://linux-hardware.org/?probe=698e3b5e35) | May 30, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | Notebook    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [e4fde15d9f](https://linux-hardware.org/?probe=e4fde15d9f) | May 30, 2023 |
| Supermicro    | X9DR3-F                     | Server      | [afcfc0fdf3](https://linux-hardware.org/?probe=afcfc0fdf3) | May 30, 2023 |
| MSI           | H55M-ED55                   | Desktop     | [a89bdc8ec0](https://linux-hardware.org/?probe=a89bdc8ec0) | May 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [dd6ecadb7e](https://linux-hardware.org/?probe=dd6ecadb7e) | May 30, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6e68e63f53](https://linux-hardware.org/?probe=6e68e63f53) | May 29, 2023 |
| ASRock        | H310CM-HDV                  | Desktop     | [e6e310a9b4](https://linux-hardware.org/?probe=e6e310a9b4) | May 29, 2023 |
| ASRock        | H310CM-HDV                  | Desktop     | [84e791ec5e](https://linux-hardware.org/?probe=84e791ec5e) | May 29, 2023 |
| Inventec      | VXC Class A02               | Desktop     | [0befe25313](https://linux-hardware.org/?probe=0befe25313) | May 29, 2023 |
| Inventec      | VXC Class A02               | Desktop     | [363827ad8c](https://linux-hardware.org/?probe=363827ad8c) | May 29, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [aac95cf765](https://linux-hardware.org/?probe=aac95cf765) | May 29, 2023 |
| Dell          | Latitude E5470              | Notebook    | [77d85b619e](https://linux-hardware.org/?probe=77d85b619e) | May 29, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [c797a10bff](https://linux-hardware.org/?probe=c797a10bff) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [deaa4b357c](https://linux-hardware.org/?probe=deaa4b357c) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [af312b5e91](https://linux-hardware.org/?probe=af312b5e91) | May 29, 2023 |
| ASUSTek       | Z10PA-D8 Series             | Desktop     | [02821a3220](https://linux-hardware.org/?probe=02821a3220) | May 29, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [bce6b61241](https://linux-hardware.org/?probe=bce6b61241) | May 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [26f783c383](https://linux-hardware.org/?probe=26f783c383) | May 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [ca1cea162c](https://linux-hardware.org/?probe=ca1cea162c) | May 29, 2023 |
| Dell          | 0D456H A00                  | Server      | [3151099615](https://linux-hardware.org/?probe=3151099615) | May 29, 2023 |
| Lenovo        | ThinkPad W530 2447GH2       | Notebook    | [f902d43115](https://linux-hardware.org/?probe=f902d43115) | May 29, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [54afc82ebc](https://linux-hardware.org/?probe=54afc82ebc) | May 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [a47a934500](https://linux-hardware.org/?probe=a47a934500) | May 29, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [4b53ed4ede](https://linux-hardware.org/?probe=4b53ed4ede) | May 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [81e905b8bf](https://linux-hardware.org/?probe=81e905b8bf) | May 29, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [b0be576b32](https://linux-hardware.org/?probe=b0be576b32) | May 28, 2023 |
| Lenovo        | Edge 15 80H1                | Notebook    | [75fdd71ca1](https://linux-hardware.org/?probe=75fdd71ca1) | May 28, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [7ac306d4fa](https://linux-hardware.org/?probe=7ac306d4fa) | May 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d5a3141562](https://linux-hardware.org/?probe=d5a3141562) | May 28, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [c256cd6942](https://linux-hardware.org/?probe=c256cd6942) | May 28, 2023 |
| Intel         | X99                         | Desktop     | [70895d913f](https://linux-hardware.org/?probe=70895d913f) | May 28, 2023 |
| HP            | Mini 110-3700               | Notebook    | [0f9528a8d2](https://linux-hardware.org/?probe=0f9528a8d2) | May 28, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [a81daffe89](https://linux-hardware.org/?probe=a81daffe89) | May 28, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [ef918dfbfa](https://linux-hardware.org/?probe=ef918dfbfa) | May 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [671d716ee3](https://linux-hardware.org/?probe=671d716ee3) | May 27, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [69adae13fe](https://linux-hardware.org/?probe=69adae13fe) | May 27, 2023 |
| HP            | G42                         | Notebook    | [7b9612a51a](https://linux-hardware.org/?probe=7b9612a51a) | May 27, 2023 |
| AZW           | MINI S                      | Desktop     | [55c17a6700](https://linux-hardware.org/?probe=55c17a6700) | May 27, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [3ad8935a92](https://linux-hardware.org/?probe=3ad8935a92) | May 27, 2023 |
| Dell          | Inspiron 7391 2n1           | Convertible | [b99041460e](https://linux-hardware.org/?probe=b99041460e) | May 27, 2023 |
| MSI           | H55M-ED55                   | Desktop     | [61e1fc3841](https://linux-hardware.org/?probe=61e1fc3841) | May 27, 2023 |
| Dell          | 0WCJNT A06                  | Server      | [b3215bf901](https://linux-hardware.org/?probe=b3215bf901) | May 27, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [a262345925](https://linux-hardware.org/?probe=a262345925) | May 27, 2023 |
| HP            | 2B38                        | Desktop     | [528dfa2310](https://linux-hardware.org/?probe=528dfa2310) | May 27, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [ac03083cbd](https://linux-hardware.org/?probe=ac03083cbd) | May 27, 2023 |
| HP            | 895C                        | Desktop     | [f0986c3613](https://linux-hardware.org/?probe=f0986c3613) | May 26, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | Notebook    | [0696598319](https://linux-hardware.org/?probe=0696598319) | May 26, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [357c1fd091](https://linux-hardware.org/?probe=357c1fd091) | May 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [4c3aa6334b](https://linux-hardware.org/?probe=4c3aa6334b) | May 26, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [d229a8eb01](https://linux-hardware.org/?probe=d229a8eb01) | May 26, 2023 |
| ASUSTek       | P4S8L                       | Desktop     | [75096a0d55](https://linux-hardware.org/?probe=75096a0d55) | May 25, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [4a6c3586fa](https://linux-hardware.org/?probe=4a6c3586fa) | May 25, 2023 |
| Acer          | Aspire V3-551               | Notebook    | [316db578fe](https://linux-hardware.org/?probe=316db578fe) | May 25, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [2a14c05edc](https://linux-hardware.org/?probe=2a14c05edc) | May 25, 2023 |
| Acer          | EG31M R01-A4                | Desktop     | [447645dad3](https://linux-hardware.org/?probe=447645dad3) | May 25, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [3a85770148](https://linux-hardware.org/?probe=3a85770148) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2a3382aa0c](https://linux-hardware.org/?probe=2a3382aa0c) | May 25, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [7884ad9bf4](https://linux-hardware.org/?probe=7884ad9bf4) | May 25, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [95321eedeb](https://linux-hardware.org/?probe=95321eedeb) | May 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [24d62f2da3](https://linux-hardware.org/?probe=24d62f2da3) | May 25, 2023 |
| ASUSTek       | Berkeley                    | Desktop     | [c3e5448952](https://linux-hardware.org/?probe=c3e5448952) | May 24, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4f91b6897e](https://linux-hardware.org/?probe=4f91b6897e) | May 24, 2023 |
| HP            | 1496                        | Desktop     | [2edc574902](https://linux-hardware.org/?probe=2edc574902) | May 24, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [e1681daf09](https://linux-hardware.org/?probe=e1681daf09) | May 24, 2023 |
| Dell          | Latitude 7220 Rugged Ext... | Notebook    | [442b7239c8](https://linux-hardware.org/?probe=442b7239c8) | May 24, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [278fefa10a](https://linux-hardware.org/?probe=278fefa10a) | May 24, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | Desktop     | [05a334c56f](https://linux-hardware.org/?probe=05a334c56f) | May 24, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [f20bf1430d](https://linux-hardware.org/?probe=f20bf1430d) | May 24, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [84b7538837](https://linux-hardware.org/?probe=84b7538837) | May 23, 2023 |
| Boot Hardw... | MBD-B650-10G                | Server      | [00e04948fa](https://linux-hardware.org/?probe=00e04948fa) | May 23, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [7b6c90320b](https://linux-hardware.org/?probe=7b6c90320b) | May 23, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [25b79c51e2](https://linux-hardware.org/?probe=25b79c51e2) | May 23, 2023 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [b3062be7f2](https://linux-hardware.org/?probe=b3062be7f2) | May 23, 2023 |
| HP            | 530                         | Notebook    | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| Intel         | S2600STB J17012-601         | Server      | [2fa80c021a](https://linux-hardware.org/?probe=2fa80c021a) | May 23, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [8ae80f0665](https://linux-hardware.org/?probe=8ae80f0665) | May 23, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [db6ba1c42e](https://linux-hardware.org/?probe=db6ba1c42e) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [584c6658c6](https://linux-hardware.org/?probe=584c6658c6) | May 23, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [6ab7e9c82d](https://linux-hardware.org/?probe=6ab7e9c82d) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [e7d7c8f7d8](https://linux-hardware.org/?probe=e7d7c8f7d8) | May 23, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | Desktop     | [c5d225afe1](https://linux-hardware.org/?probe=c5d225afe1) | May 23, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [9532d524c9](https://linux-hardware.org/?probe=9532d524c9) | May 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [aec9e5a959](https://linux-hardware.org/?probe=aec9e5a959) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [44b6477648](https://linux-hardware.org/?probe=44b6477648) | May 22, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [0e982abd6b](https://linux-hardware.org/?probe=0e982abd6b) | May 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [2b3ef0afc4](https://linux-hardware.org/?probe=2b3ef0afc4) | May 22, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [82f235bfbb](https://linux-hardware.org/?probe=82f235bfbb) | May 22, 2023 |
| AZW           | U59                         | Desktop     | [59edf1c8a6](https://linux-hardware.org/?probe=59edf1c8a6) | May 22, 2023 |
| AZW           | U59                         | Desktop     | [b365dbf63a](https://linux-hardware.org/?probe=b365dbf63a) | May 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2b2367f9b1](https://linux-hardware.org/?probe=2b2367f9b1) | May 22, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [4438fdd9b2](https://linux-hardware.org/?probe=4438fdd9b2) | May 22, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [46de86898c](https://linux-hardware.org/?probe=46de86898c) | May 22, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [17d027794e](https://linux-hardware.org/?probe=17d027794e) | May 22, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [243f08edd7](https://linux-hardware.org/?probe=243f08edd7) | May 22, 2023 |
| Dell          | 0J1C3P A00                  | Desktop     | [5f3d8a94e6](https://linux-hardware.org/?probe=5f3d8a94e6) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [0ab3a9817b](https://linux-hardware.org/?probe=0ab3a9817b) | May 21, 2023 |
| HP            | 2B38                        | Desktop     | [b45d316c65](https://linux-hardware.org/?probe=b45d316c65) | May 21, 2023 |
| HP            | 2B38                        | Desktop     | [c2ab5ab32a](https://linux-hardware.org/?probe=c2ab5ab32a) | May 21, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [e2d9f2e00f](https://linux-hardware.org/?probe=e2d9f2e00f) | May 21, 2023 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [f573a9cfae](https://linux-hardware.org/?probe=f573a9cfae) | May 21, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Dell          | Inspiron 3451               | Notebook    | [e69cefc8da](https://linux-hardware.org/?probe=e69cefc8da) | May 21, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [b7463aea3a](https://linux-hardware.org/?probe=b7463aea3a) | May 21, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [a28c25cf6a](https://linux-hardware.org/?probe=a28c25cf6a) | May 21, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [874345ef99](https://linux-hardware.org/?probe=874345ef99) | May 21, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [118adf4d65](https://linux-hardware.org/?probe=118adf4d65) | May 20, 2023 |
| Lenovo        | ThinkPad W510 4391DK3       | Notebook    | [ac8db768ce](https://linux-hardware.org/?probe=ac8db768ce) | May 20, 2023 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [e6e79ac2ca](https://linux-hardware.org/?probe=e6e79ac2ca) | May 20, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [35b5231ed2](https://linux-hardware.org/?probe=35b5231ed2) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | Desktop     | [d17f4a61d7](https://linux-hardware.org/?probe=d17f4a61d7) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | Desktop     | [0362a8829c](https://linux-hardware.org/?probe=0362a8829c) | May 20, 2023 |
| MSI           | 2AE0                        | Desktop     | [5f47fbb9cb](https://linux-hardware.org/?probe=5f47fbb9cb) | May 19, 2023 |
| MSI           | 2AE0                        | Desktop     | [c14f84a498](https://linux-hardware.org/?probe=c14f84a498) | May 19, 2023 |
| Dell          | Latitude 5411               | Notebook    | [8929285bca](https://linux-hardware.org/?probe=8929285bca) | May 19, 2023 |
| Gigabyte      | GA-6LASL 01234567           | Server      | [13eb4e7266](https://linux-hardware.org/?probe=13eb4e7266) | May 19, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [6b5bc55aeb](https://linux-hardware.org/?probe=6b5bc55aeb) | May 18, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [e26f4ecf2f](https://linux-hardware.org/?probe=e26f4ecf2f) | May 18, 2023 |
| Lenovo        | ThinkPad X200s 7470WUB      | Notebook    | [e5ad235f60](https://linux-hardware.org/?probe=e5ad235f60) | May 18, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [875d854ec4](https://linux-hardware.org/?probe=875d854ec4) | May 18, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [c9d1849e5e](https://linux-hardware.org/?probe=c9d1849e5e) | May 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [5d69cc1112](https://linux-hardware.org/?probe=5d69cc1112) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0c6bb22a24](https://linux-hardware.org/?probe=0c6bb22a24) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [e042bb19ba](https://linux-hardware.org/?probe=e042bb19ba) | May 18, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [26dc842484](https://linux-hardware.org/?probe=26dc842484) | May 18, 2023 |
| HP            | 8076                        | Desktop     | [fe142eecf2](https://linux-hardware.org/?probe=fe142eecf2) | May 18, 2023 |
| Dell          | Latitude E7450              | Notebook    | [3000905b05](https://linux-hardware.org/?probe=3000905b05) | May 18, 2023 |
| Dell          | Latitude E7450              | Notebook    | [10f138711f](https://linux-hardware.org/?probe=10f138711f) | May 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [4aadc89f41](https://linux-hardware.org/?probe=4aadc89f41) | May 17, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [2f6a330442](https://linux-hardware.org/?probe=2f6a330442) | May 17, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [2a6dcbf826](https://linux-hardware.org/?probe=2a6dcbf826) | May 17, 2023 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [d43fc4e5b9](https://linux-hardware.org/?probe=d43fc4e5b9) | May 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [863f20642f](https://linux-hardware.org/?probe=863f20642f) | May 17, 2023 |
| ASUSTek       | B150-PLUS                   | Desktop     | [41b19667a8](https://linux-hardware.org/?probe=41b19667a8) | May 17, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [94ee6e64c4](https://linux-hardware.org/?probe=94ee6e64c4) | May 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [a1fb71ff2f](https://linux-hardware.org/?probe=a1fb71ff2f) | May 17, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [60abe2cf78](https://linux-hardware.org/?probe=60abe2cf78) | May 17, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [84ee42ec2e](https://linux-hardware.org/?probe=84ee42ec2e) | May 17, 2023 |
| Dell          | 0D883F A04                  | Desktop     | [62cee990ff](https://linux-hardware.org/?probe=62cee990ff) | May 17, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [8aef05613d](https://linux-hardware.org/?probe=8aef05613d) | May 17, 2023 |
| Pegatron      | Yangtze                     | Desktop     | [4e3ce38e7b](https://linux-hardware.org/?probe=4e3ce38e7b) | May 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [6ce8f784b0](https://linux-hardware.org/?probe=6ce8f784b0) | May 17, 2023 |
| Dell          | 07KY25 A00                  | Desktop     | [16e4096f62](https://linux-hardware.org/?probe=16e4096f62) | May 16, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [46b31c9243](https://linux-hardware.org/?probe=46b31c9243) | May 16, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [3699048599](https://linux-hardware.org/?probe=3699048599) | May 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [af42d74d41](https://linux-hardware.org/?probe=af42d74d41) | May 16, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [4dcf0cf794](https://linux-hardware.org/?probe=4dcf0cf794) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [0f9a26db5f](https://linux-hardware.org/?probe=0f9a26db5f) | May 16, 2023 |
| Lenovo        | ThinkPad T490 20N2004JAD    | Notebook    | [c765eed46d](https://linux-hardware.org/?probe=c765eed46d) | May 16, 2023 |
| Dell          | Latitude 5521               | Notebook    | [9f671f21c1](https://linux-hardware.org/?probe=9f671f21c1) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [56056f7c9a](https://linux-hardware.org/?probe=56056f7c9a) | May 15, 2023 |
| Acer          | AO532h                      | Notebook    | [6cfe2a58cc](https://linux-hardware.org/?probe=6cfe2a58cc) | May 15, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [db27da6896](https://linux-hardware.org/?probe=db27da6896) | May 15, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [61e6c3f5f1](https://linux-hardware.org/?probe=61e6c3f5f1) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [4ef8752290](https://linux-hardware.org/?probe=4ef8752290) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [b5c9664f50](https://linux-hardware.org/?probe=b5c9664f50) | May 15, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d4ad39c5d7](https://linux-hardware.org/?probe=d4ad39c5d7) | May 15, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3e839501e9](https://linux-hardware.org/?probe=3e839501e9) | May 15, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [c1bcc07617](https://linux-hardware.org/?probe=c1bcc07617) | May 15, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [7b0f6f3dc2](https://linux-hardware.org/?probe=7b0f6f3dc2) | May 15, 2023 |
| Dell          | G15 5510                    | Notebook    | [5624d414be](https://linux-hardware.org/?probe=5624d414be) | May 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [c82f72f0e2](https://linux-hardware.org/?probe=c82f72f0e2) | May 15, 2023 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [cd0a78ce39](https://linux-hardware.org/?probe=cd0a78ce39) | May 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7978974828](https://linux-hardware.org/?probe=7978974828) | May 14, 2023 |
| HP            | 339A                        | Desktop     | [4c56331906](https://linux-hardware.org/?probe=4c56331906) | May 14, 2023 |
| Intel         | D510MO AAE76523-404         | Desktop     | [03221e90c1](https://linux-hardware.org/?probe=03221e90c1) | May 14, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [87d2f8b907](https://linux-hardware.org/?probe=87d2f8b907) | May 14, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [7e2caae7ea](https://linux-hardware.org/?probe=7e2caae7ea) | May 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [1d3db7b456](https://linux-hardware.org/?probe=1d3db7b456) | May 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [9459f4eae8](https://linux-hardware.org/?probe=9459f4eae8) | May 14, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e887133fce](https://linux-hardware.org/?probe=e887133fce) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [2be4ad0e3d](https://linux-hardware.org/?probe=2be4ad0e3d) | May 14, 2023 |
| Dell          | Latitude 7410               | Notebook    | [542e1d7f7b](https://linux-hardware.org/?probe=542e1d7f7b) | May 14, 2023 |
| AMI           | Intel                       | Notebook    | [958f5ffc92](https://linux-hardware.org/?probe=958f5ffc92) | May 14, 2023 |
| AMI           | Intel                       | Notebook    | [0c9a68a20c](https://linux-hardware.org/?probe=0c9a68a20c) | May 13, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [72ba449391](https://linux-hardware.org/?probe=72ba449391) | May 13, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a712c6b44a](https://linux-hardware.org/?probe=a712c6b44a) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E5410              | Notebook    | [c62a002948](https://linux-hardware.org/?probe=c62a002948) | May 13, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [036fd352bf](https://linux-hardware.org/?probe=036fd352bf) | May 13, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [b15a6ee63f](https://linux-hardware.org/?probe=b15a6ee63f) | May 13, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [921f919bb6](https://linux-hardware.org/?probe=921f919bb6) | May 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [bf54c69e0c](https://linux-hardware.org/?probe=bf54c69e0c) | May 12, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [b56358c287](https://linux-hardware.org/?probe=b56358c287) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| HP            | 1632                        | Desktop     | [d3a5a15faa](https://linux-hardware.org/?probe=d3a5a15faa) | May 12, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [cbc84d049a](https://linux-hardware.org/?probe=cbc84d049a) | May 12, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [c458dad4b3](https://linux-hardware.org/?probe=c458dad4b3) | May 12, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [c51d42778d](https://linux-hardware.org/?probe=c51d42778d) | May 12, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [e65b0be462](https://linux-hardware.org/?probe=e65b0be462) | May 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [9201edcfb8](https://linux-hardware.org/?probe=9201edcfb8) | May 12, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [848eedb681](https://linux-hardware.org/?probe=848eedb681) | May 12, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [3a92115c6c](https://linux-hardware.org/?probe=3a92115c6c) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6c61b581ba](https://linux-hardware.org/?probe=6c61b581ba) | May 12, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [2302fc6860](https://linux-hardware.org/?probe=2302fc6860) | May 12, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | Notebook    | [65b165e2f1](https://linux-hardware.org/?probe=65b165e2f1) | May 12, 2023 |
| Apple         | MacBook10,1                 | Notebook    | [d26983a399](https://linux-hardware.org/?probe=d26983a399) | May 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [c686c521dd](https://linux-hardware.org/?probe=c686c521dd) | May 12, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [ba542c09f2](https://linux-hardware.org/?probe=ba542c09f2) | May 12, 2023 |
| AZW           | Green G3                    | Desktop     | [e11013e93f](https://linux-hardware.org/?probe=e11013e93f) | May 11, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [e0ebf9fa8a](https://linux-hardware.org/?probe=e0ebf9fa8a) | May 11, 2023 |
| Medion        | E2292                       | Convertible | [116727a473](https://linux-hardware.org/?probe=116727a473) | May 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [f02c2abaab](https://linux-hardware.org/?probe=f02c2abaab) | May 11, 2023 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [4b5279de3c](https://linux-hardware.org/?probe=4b5279de3c) | May 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [661a7cf306](https://linux-hardware.org/?probe=661a7cf306) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7d19994aa2](https://linux-hardware.org/?probe=7d19994aa2) | May 11, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [e07b012f6b](https://linux-hardware.org/?probe=e07b012f6b) | May 10, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [25b993b097](https://linux-hardware.org/?probe=25b993b097) | May 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [eb6941b1b8](https://linux-hardware.org/?probe=eb6941b1b8) | May 10, 2023 |
| Supermicro    | X10DRi                      | Server      | [5fc37f06cb](https://linux-hardware.org/?probe=5fc37f06cb) | May 10, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [f612c54f9c](https://linux-hardware.org/?probe=f612c54f9c) | May 09, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [9c14434a99](https://linux-hardware.org/?probe=9c14434a99) | May 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [4a0ccb88d2](https://linux-hardware.org/?probe=4a0ccb88d2) | May 09, 2023 |
| Dell          | 0C1R19 A01                  | Desktop     | [8a436329aa](https://linux-hardware.org/?probe=8a436329aa) | May 09, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [bcb5863b0a](https://linux-hardware.org/?probe=bcb5863b0a) | May 09, 2023 |
| Lenovo        | ThinkPad T530 2394CE2       | Notebook    | [d232fefed2](https://linux-hardware.org/?probe=d232fefed2) | May 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [99dfb3e933](https://linux-hardware.org/?probe=99dfb3e933) | May 09, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d9681f2d77](https://linux-hardware.org/?probe=d9681f2d77) | May 09, 2023 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [0971c53d86](https://linux-hardware.org/?probe=0971c53d86) | May 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [e98eff32d6](https://linux-hardware.org/?probe=e98eff32d6) | May 08, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [26e8efdd69](https://linux-hardware.org/?probe=26e8efdd69) | May 08, 2023 |
| HP            | 0AA8h                       | Desktop     | [05689fe634](https://linux-hardware.org/?probe=05689fe634) | May 08, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c95999b5ad](https://linux-hardware.org/?probe=c95999b5ad) | May 08, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [670e910889](https://linux-hardware.org/?probe=670e910889) | May 08, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c5687c048f](https://linux-hardware.org/?probe=c5687c048f) | May 08, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [d0cef22171](https://linux-hardware.org/?probe=d0cef22171) | May 08, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [4a8c2101e8](https://linux-hardware.org/?probe=4a8c2101e8) | May 08, 2023 |
| HP            | 3031h                       | Desktop     | [dc7b257f83](https://linux-hardware.org/?probe=dc7b257f83) | May 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [83c0f8e7e5](https://linux-hardware.org/?probe=83c0f8e7e5) | May 08, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [967e39a2d3](https://linux-hardware.org/?probe=967e39a2d3) | May 08, 2023 |
| MSI           | H61M-E23                    | Desktop     | [22cdfbec52](https://linux-hardware.org/?probe=22cdfbec52) | May 08, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYFR    | Notebook    | [f945ec106e](https://linux-hardware.org/?probe=f945ec106e) | May 07, 2023 |
| HP            | 255 G3                      | Notebook    | [d95f6211dc](https://linux-hardware.org/?probe=d95f6211dc) | May 07, 2023 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | Desktop     | [2a26d32cc3](https://linux-hardware.org/?probe=2a26d32cc3) | May 07, 2023 |
| ASUSTek       | K73SJ                       | Notebook    | [13b8c8be10](https://linux-hardware.org/?probe=13b8c8be10) | May 07, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [0fa7cb39ce](https://linux-hardware.org/?probe=0fa7cb39ce) | May 07, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [08b1152328](https://linux-hardware.org/?probe=08b1152328) | May 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [18dcba612c](https://linux-hardware.org/?probe=18dcba612c) | May 07, 2023 |
| Unknown       | Unknown                     | Soc         | [55f6caec2d](https://linux-hardware.org/?probe=55f6caec2d) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [6ec1762e12](https://linux-hardware.org/?probe=6ec1762e12) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [6816b3dddd](https://linux-hardware.org/?probe=6816b3dddd) | May 07, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [e40d8038da](https://linux-hardware.org/?probe=e40d8038da) | May 07, 2023 |
| ASUSTek       | E3 PRO GAMING V5            | Desktop     | [507036954e](https://linux-hardware.org/?probe=507036954e) | May 07, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [e3dc4ed549](https://linux-hardware.org/?probe=e3dc4ed549) | May 06, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [9d7736a816](https://linux-hardware.org/?probe=9d7736a816) | May 06, 2023 |
| Lenovo        | IdeaPad Y480 20131          | Notebook    | [d625664bee](https://linux-hardware.org/?probe=d625664bee) | May 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [dd406112de](https://linux-hardware.org/?probe=dd406112de) | May 06, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [701907636a](https://linux-hardware.org/?probe=701907636a) | May 06, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [8ce0b92713](https://linux-hardware.org/?probe=8ce0b92713) | May 06, 2023 |
| Lenovo        | Mixx-700-12ISK 80QL         | Notebook    | [14bc666ec3](https://linux-hardware.org/?probe=14bc666ec3) | May 06, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [25f9d02593](https://linux-hardware.org/?probe=25f9d02593) | May 06, 2023 |
| Lenovo        | ThinkPad T410 2537CC5       | Notebook    | [10de9f17e1](https://linux-hardware.org/?probe=10de9f17e1) | May 06, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [2d767e0513](https://linux-hardware.org/?probe=2d767e0513) | May 06, 2023 |
| HP            | 1998                        | Desktop     | [59c2c05cdb](https://linux-hardware.org/?probe=59c2c05cdb) | May 05, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [f7c7c572e4](https://linux-hardware.org/?probe=f7c7c572e4) | May 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [808f3370fc](https://linux-hardware.org/?probe=808f3370fc) | May 05, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [c545869ec5](https://linux-hardware.org/?probe=c545869ec5) | May 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 2i 21A... | Notebook    | [064df1260c](https://linux-hardware.org/?probe=064df1260c) | May 05, 2023 |
| Dell          | 0RN474                      | Desktop     | [b638694274](https://linux-hardware.org/?probe=b638694274) | May 05, 2023 |
| Dell          | Latitude D630               | Notebook    | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [e7f4d1fdda](https://linux-hardware.org/?probe=e7f4d1fdda) | May 05, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [417be33443](https://linux-hardware.org/?probe=417be33443) | May 05, 2023 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [7b25457d55](https://linux-hardware.org/?probe=7b25457d55) | May 04, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [4f2fbcc26f](https://linux-hardware.org/?probe=4f2fbcc26f) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2660b0df6d](https://linux-hardware.org/?probe=2660b0df6d) | May 04, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | Desktop     | [4e80f798e2](https://linux-hardware.org/?probe=4e80f798e2) | May 04, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [b68f20e323](https://linux-hardware.org/?probe=b68f20e323) | May 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8a4aacb421](https://linux-hardware.org/?probe=8a4aacb421) | May 04, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [78dbd4cfb6](https://linux-hardware.org/?probe=78dbd4cfb6) | May 04, 2023 |
| sunxi         | Unknown                     | Soc         | [952b46c211](https://linux-hardware.org/?probe=952b46c211) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [fbcadee14f](https://linux-hardware.org/?probe=fbcadee14f) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [f9071ed10e](https://linux-hardware.org/?probe=f9071ed10e) | May 03, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [f636b7c230](https://linux-hardware.org/?probe=f636b7c230) | May 03, 2023 |
| HPE           | ProLiant DL360 Gen10 Plu... | Server      | [74466ad718](https://linux-hardware.org/?probe=74466ad718) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [fc1bd7fffc](https://linux-hardware.org/?probe=fc1bd7fffc) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [c8373114ef](https://linux-hardware.org/?probe=c8373114ef) | May 03, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | Desktop     | [0b303a3773](https://linux-hardware.org/?probe=0b303a3773) | May 03, 2023 |
| Lenovo        | ThinkPad T470 20HES63400    | Notebook    | [6628ac6681](https://linux-hardware.org/?probe=6628ac6681) | May 03, 2023 |
| HP            | Notebook                    | Notebook    | [c6316b5a64](https://linux-hardware.org/?probe=c6316b5a64) | May 03, 2023 |
| Dell          | Precision 7510              | Notebook    | [1e73564cf9](https://linux-hardware.org/?probe=1e73564cf9) | May 03, 2023 |
| Dell          | Latitude 5414               | Notebook    | [6922f7db46](https://linux-hardware.org/?probe=6922f7db46) | May 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [93a11302fb](https://linux-hardware.org/?probe=93a11302fb) | May 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model A P... | Soc         | [d0c2c987fc](https://linux-hardware.org/?probe=d0c2c987fc) | May 03, 2023 |
| HP            | 83C3 A01                    | Mini pc     | [bb29a94285](https://linux-hardware.org/?probe=bb29a94285) | May 03, 2023 |
| GreatWall     | DF                          | Soc         | [5a3cb266db](https://linux-hardware.org/?probe=5a3cb266db) | May 03, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [7beeddc27c](https://linux-hardware.org/?probe=7beeddc27c) | May 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| BESSTAR Te... | DMAF5                       | Desktop     | [b9f947fec3](https://linux-hardware.org/?probe=b9f947fec3) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2fabcbe5dc](https://linux-hardware.org/?probe=2fabcbe5dc) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fa453d9183](https://linux-hardware.org/?probe=fa453d9183) | May 02, 2023 |
| Dell          | Latitude 7370               | Notebook    | [c984360af7](https://linux-hardware.org/?probe=c984360af7) | May 02, 2023 |
| Dell          | Latitude 7370               | Notebook    | [295b50d5b2](https://linux-hardware.org/?probe=295b50d5b2) | May 02, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [86b607e7d4](https://linux-hardware.org/?probe=86b607e7d4) | May 02, 2023 |
| MSI           | Z87-G43                     | Desktop     | [8ba78b7b0b](https://linux-hardware.org/?probe=8ba78b7b0b) | May 02, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7ae18f770d](https://linux-hardware.org/?probe=7ae18f770d) | May 02, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [f149f8c9fb](https://linux-hardware.org/?probe=f149f8c9fb) | May 02, 2023 |
| ASUSTek       | PN50                        | Mini pc     | [c1bf3a9c44](https://linux-hardware.org/?probe=c1bf3a9c44) | May 02, 2023 |
| MSI           | Katana GF76 12UEK           | Notebook    | [5af5d6aec3](https://linux-hardware.org/?probe=5af5d6aec3) | May 01, 2023 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [3174c98e9c](https://linux-hardware.org/?probe=3174c98e9c) | May 01, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [9098e5d498](https://linux-hardware.org/?probe=9098e5d498) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | Desktop     | [ec30321519](https://linux-hardware.org/?probe=ec30321519) | May 01, 2023 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [cfe5e305c8](https://linux-hardware.org/?probe=cfe5e305c8) | May 01, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [0d041ed447](https://linux-hardware.org/?probe=0d041ed447) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | Desktop     | [a237c703d9](https://linux-hardware.org/?probe=a237c703d9) | May 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [f5f4abd1f3](https://linux-hardware.org/?probe=f5f4abd1f3) | May 01, 2023 |
| HP            | 2B38                        | Desktop     | [bf99202e8b](https://linux-hardware.org/?probe=bf99202e8b) | May 01, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [7fb1708706](https://linux-hardware.org/?probe=7fb1708706) | May 01, 2023 |
| HP            | 2B38                        | Desktop     | [6942eb2544](https://linux-hardware.org/?probe=6942eb2544) | May 01, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [e03d5ff056](https://linux-hardware.org/?probe=e03d5ff056) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | Notebook    | [07e2cc77f8](https://linux-hardware.org/?probe=07e2cc77f8) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | Notebook    | [638e747fb1](https://linux-hardware.org/?probe=638e747fb1) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | Notebook    | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [c8c9c1e591](https://linux-hardware.org/?probe=c8c9c1e591) | Apr 30, 2023 |
| Positivo      | Q464C                       | Notebook    | [8e41593bd3](https://linux-hardware.org/?probe=8e41593bd3) | Apr 30, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ccb46c2a2b](https://linux-hardware.org/?probe=ccb46c2a2b) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | Notebook    | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7804689b38](https://linux-hardware.org/?probe=7804689b38) | Apr 30, 2023 |
| COPELION I... | QX-250 Series               | Notebook    | [409821566f](https://linux-hardware.org/?probe=409821566f) | Apr 29, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [139d61e128](https://linux-hardware.org/?probe=139d61e128) | Apr 29, 2023 |
| HP            | 3397                        | Desktop     | [8b84766d3d](https://linux-hardware.org/?probe=8b84766d3d) | Apr 29, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4cc7c839fb](https://linux-hardware.org/?probe=4cc7c839fb) | Apr 29, 2023 |
| Lenovo        | ThinkPad X280 20KESBC402    | Notebook    | [0d5b86146e](https://linux-hardware.org/?probe=0d5b86146e) | Apr 29, 2023 |
| Medion        | MS-7708                     | Desktop     | [af2020cd9c](https://linux-hardware.org/?probe=af2020cd9c) | Apr 28, 2023 |
| Rockchip      | Unknown                     | Soc         | [5236b9452c](https://linux-hardware.org/?probe=5236b9452c) | Apr 28, 2023 |
| Medion        | MS-7708                     | Desktop     | [424c4ca2db](https://linux-hardware.org/?probe=424c4ca2db) | Apr 28, 2023 |
| Intel         | H61 V124                    | Desktop     | [1fa0b34b3c](https://linux-hardware.org/?probe=1fa0b34b3c) | Apr 28, 2023 |
| Supermicro    | X12SPL-F                    | Server      | [8382988ca9](https://linux-hardware.org/?probe=8382988ca9) | Apr 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | Desktop     | [429d6f994a](https://linux-hardware.org/?probe=429d6f994a) | Apr 28, 2023 |
| ASUSTek       | B150-PRO D3                 | Desktop     | [35fa6f9a33](https://linux-hardware.org/?probe=35fa6f9a33) | Apr 28, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [cded55a936](https://linux-hardware.org/?probe=cded55a936) | Apr 28, 2023 |
| Dell          | Latitude E7450              | Notebook    | [6afa2ff009](https://linux-hardware.org/?probe=6afa2ff009) | Apr 28, 2023 |
| Unknown       | Unknown                     | Soc         | [e5ff381254](https://linux-hardware.org/?probe=e5ff381254) | Apr 28, 2023 |
| BESSTAR Te... | HM80                        | Desktop     | [476c573547](https://linux-hardware.org/?probe=476c573547) | Apr 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [bab222234a](https://linux-hardware.org/?probe=bab222234a) | Apr 27, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [e2f7b853b1](https://linux-hardware.org/?probe=e2f7b853b1) | Apr 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [e9f8ff6596](https://linux-hardware.org/?probe=e9f8ff6596) | Apr 27, 2023 |
| HP            | 17E2                        | Mini pc     | [02ee837763](https://linux-hardware.org/?probe=02ee837763) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [69d1f17b35](https://linux-hardware.org/?probe=69d1f17b35) | Apr 27, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | Notebook    | [e61f528ba5](https://linux-hardware.org/?probe=e61f528ba5) | Apr 27, 2023 |
| AMD           | Volcano                     | Server      | [b7e67f8130](https://linux-hardware.org/?probe=b7e67f8130) | Apr 27, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [475e46f565](https://linux-hardware.org/?probe=475e46f565) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [40970f0528](https://linux-hardware.org/?probe=40970f0528) | Apr 26, 2023 |
| MSI           | MS-B0A21                    | Desktop     | [646d14f7b0](https://linux-hardware.org/?probe=646d14f7b0) | Apr 26, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | Notebook    | [cec3a72c8a](https://linux-hardware.org/?probe=cec3a72c8a) | Apr 26, 2023 |
| Google        | Terra                       | Notebook    | [b22deb9f09](https://linux-hardware.org/?probe=b22deb9f09) | Apr 26, 2023 |
| Dell          | Latitude E6440              | Notebook    | [f5cdf825fa](https://linux-hardware.org/?probe=f5cdf825fa) | Apr 26, 2023 |
| HP            | ENVY 15                     | Notebook    | [1f50420c44](https://linux-hardware.org/?probe=1f50420c44) | Apr 26, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [90e4883dca](https://linux-hardware.org/?probe=90e4883dca) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [c3c972facf](https://linux-hardware.org/?probe=c3c972facf) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [f993513cd3](https://linux-hardware.org/?probe=f993513cd3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d8088982c3](https://linux-hardware.org/?probe=d8088982c3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4cffa55fb1](https://linux-hardware.org/?probe=4cffa55fb1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [e6380a2186](https://linux-hardware.org/?probe=e6380a2186) | Apr 26, 2023 |
| HP            | Laptop 15                   | Notebook    | [34a2ebf6a1](https://linux-hardware.org/?probe=34a2ebf6a1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [872138980a](https://linux-hardware.org/?probe=872138980a) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2122bd37a5](https://linux-hardware.org/?probe=2122bd37a5) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af7b14d259](https://linux-hardware.org/?probe=af7b14d259) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7fbd802154](https://linux-hardware.org/?probe=7fbd802154) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ffe6065419](https://linux-hardware.org/?probe=ffe6065419) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [94ddc76aae](https://linux-hardware.org/?probe=94ddc76aae) | Apr 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [23571a99b1](https://linux-hardware.org/?probe=23571a99b1) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [ace6df6aee](https://linux-hardware.org/?probe=ace6df6aee) | Apr 25, 2023 |
| Dell          | Cherry Trail CR A00         | Mini pc     | [f1fb89d0f7](https://linux-hardware.org/?probe=f1fb89d0f7) | Apr 25, 2023 |
| Lenovo        | ThinkPad T530 23594ZC       | Notebook    | [7aec73dfa1](https://linux-hardware.org/?probe=7aec73dfa1) | Apr 25, 2023 |
| Lenovo        | ThinkPad X200 7459KM3       | Notebook    | [cbea785e27](https://linux-hardware.org/?probe=cbea785e27) | Apr 25, 2023 |
| Dell          | 0KYJ8C A00                  | Desktop     | [1e8226d149](https://linux-hardware.org/?probe=1e8226d149) | Apr 25, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [5d03070db6](https://linux-hardware.org/?probe=5d03070db6) | Apr 24, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [aa1b58a2a2](https://linux-hardware.org/?probe=aa1b58a2a2) | Apr 24, 2023 |
| HP            | 8056                        | Desktop     | [a7686ee1af](https://linux-hardware.org/?probe=a7686ee1af) | Apr 24, 2023 |
| AZW           | MINI S                      | Desktop     | [d71153ae6e](https://linux-hardware.org/?probe=d71153ae6e) | Apr 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [de825a326c](https://linux-hardware.org/?probe=de825a326c) | Apr 24, 2023 |
| Intel         | SE7320EP2 D11950-402        | Desktop     | [ad1a126878](https://linux-hardware.org/?probe=ad1a126878) | Apr 24, 2023 |
| MSI           | Z87-G43                     | Desktop     | [4d908cb615](https://linux-hardware.org/?probe=4d908cb615) | Apr 24, 2023 |
| Dell          | 0N0992 A01                  | Desktop     | [a8e8000610](https://linux-hardware.org/?probe=a8e8000610) | Apr 24, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [971055139b](https://linux-hardware.org/?probe=971055139b) | Apr 24, 2023 |
| Dell          | 03FV9K A00                  | Server      | [4d9f06ca7b](https://linux-hardware.org/?probe=4d9f06ca7b) | Apr 24, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [32546113c8](https://linux-hardware.org/?probe=32546113c8) | Apr 24, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [5f760ed90e](https://linux-hardware.org/?probe=5f760ed90e) | Apr 23, 2023 |
| Biostar       | B350ET2                     | Desktop     | [47289e48eb](https://linux-hardware.org/?probe=47289e48eb) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | Desktop     | [3a9f7b19fa](https://linux-hardware.org/?probe=3a9f7b19fa) | Apr 23, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [74cf7ef6e5](https://linux-hardware.org/?probe=74cf7ef6e5) | Apr 23, 2023 |
| HP            | 15                          | Notebook    | [fd68fb06af](https://linux-hardware.org/?probe=fd68fb06af) | Apr 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [78c1951456](https://linux-hardware.org/?probe=78c1951456) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | Desktop     | [965aa93228](https://linux-hardware.org/?probe=965aa93228) | Apr 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [0605faa66d](https://linux-hardware.org/?probe=0605faa66d) | Apr 23, 2023 |
| AZW           | U59                         | Desktop     | [8921a6910d](https://linux-hardware.org/?probe=8921a6910d) | Apr 23, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [c88cba109a](https://linux-hardware.org/?probe=c88cba109a) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [45d7bd0907](https://linux-hardware.org/?probe=45d7bd0907) | Apr 23, 2023 |
| Shuttle       | DS20U                       | Desktop     | [2e8e79b5ff](https://linux-hardware.org/?probe=2e8e79b5ff) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [c7367bfdff](https://linux-hardware.org/?probe=c7367bfdff) | Apr 23, 2023 |
| HP            | 845A                        | Desktop     | [41a0cad635](https://linux-hardware.org/?probe=41a0cad635) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [ccb49b32a0](https://linux-hardware.org/?probe=ccb49b32a0) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [2651f47f8c](https://linux-hardware.org/?probe=2651f47f8c) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | Notebook    | [adee59c351](https://linux-hardware.org/?probe=adee59c351) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | Notebook    | [c5c43186bc](https://linux-hardware.org/?probe=c5c43186bc) | Apr 23, 2023 |
| Dell          | G15 5520                    | Notebook    | [07751c950a](https://linux-hardware.org/?probe=07751c950a) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [03a331aa44](https://linux-hardware.org/?probe=03a331aa44) | Apr 22, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [0a90dc180c](https://linux-hardware.org/?probe=0a90dc180c) | Apr 22, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b5ffb4ee22](https://linux-hardware.org/?probe=b5ffb4ee22) | Apr 22, 2023 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [45af810de1](https://linux-hardware.org/?probe=45af810de1) | Apr 21, 2023 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [868456ca5d](https://linux-hardware.org/?probe=868456ca5d) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5f61e3a174](https://linux-hardware.org/?probe=5f61e3a174) | Apr 21, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e98b4fdd23](https://linux-hardware.org/?probe=e98b4fdd23) | Apr 21, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [a92b4a305f](https://linux-hardware.org/?probe=a92b4a305f) | Apr 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [3caa3d5076](https://linux-hardware.org/?probe=3caa3d5076) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [8c8d2eb3b5](https://linux-hardware.org/?probe=8c8d2eb3b5) | Apr 21, 2023 |
| Dell          | Precision 3550              | Notebook    | [7434822402](https://linux-hardware.org/?probe=7434822402) | Apr 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [4392c46287](https://linux-hardware.org/?probe=4392c46287) | Apr 20, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [cde1ecf1c6](https://linux-hardware.org/?probe=cde1ecf1c6) | Apr 20, 2023 |
| Toshiba       | Satellite Pro NB10-A-125    | Notebook    | [3a77f344af](https://linux-hardware.org/?probe=3a77f344af) | Apr 20, 2023 |
| Shuttle       | FS81                        | Desktop     | [051b7f4753](https://linux-hardware.org/?probe=051b7f4753) | Apr 20, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [cb5f73ff63](https://linux-hardware.org/?probe=cb5f73ff63) | Apr 20, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [9af253f4e0](https://linux-hardware.org/?probe=9af253f4e0) | Apr 20, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [2d4578e52a](https://linux-hardware.org/?probe=2d4578e52a) | Apr 20, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [9ab965fcb8](https://linux-hardware.org/?probe=9ab965fcb8) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [4abfcb4ab3](https://linux-hardware.org/?probe=4abfcb4ab3) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [e93357961f](https://linux-hardware.org/?probe=e93357961f) | Apr 19, 2023 |
| Lenovo        | ThinkPad T500 2055WAB       | Notebook    | [4e293261bb](https://linux-hardware.org/?probe=4e293261bb) | Apr 19, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [3b8c115c1a](https://linux-hardware.org/?probe=3b8c115c1a) | Apr 19, 2023 |
| MSI           | MPG Z590 GAMING EDGE WIF... | Desktop     | [97860c01ca](https://linux-hardware.org/?probe=97860c01ca) | Apr 19, 2023 |
| Toshiba       | Satellite Pro A100          | Notebook    | [4240870be8](https://linux-hardware.org/?probe=4240870be8) | Apr 19, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [f691871296](https://linux-hardware.org/?probe=f691871296) | Apr 19, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [5fc25cc033](https://linux-hardware.org/?probe=5fc25cc033) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [895abaa15e](https://linux-hardware.org/?probe=895abaa15e) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [f70d811bbd](https://linux-hardware.org/?probe=f70d811bbd) | Apr 19, 2023 |
| sunxi         | Unknown                     | Soc         | [bb26b3803b](https://linux-hardware.org/?probe=bb26b3803b) | Apr 19, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [699e2a2a80](https://linux-hardware.org/?probe=699e2a2a80) | Apr 18, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [213cd129cd](https://linux-hardware.org/?probe=213cd129cd) | Apr 18, 2023 |
| sunxi         | Unknown                     | Soc         | [586cbefdb3](https://linux-hardware.org/?probe=586cbefdb3) | Apr 18, 2023 |
| Lenovo        | 374B No DPK                 | All in one  | [c87417466c](https://linux-hardware.org/?probe=c87417466c) | Apr 18, 2023 |
| Lenovo        | 374B No DPK                 | All in one  | [4a7133799c](https://linux-hardware.org/?probe=4a7133799c) | Apr 18, 2023 |
| Toshiba       | Satellite Pro C850-1J2      | Notebook    | [e5c63957a2](https://linux-hardware.org/?probe=e5c63957a2) | Apr 18, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fd82dc08dc](https://linux-hardware.org/?probe=fd82dc08dc) | Apr 18, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [35c6970ec2](https://linux-hardware.org/?probe=35c6970ec2) | Apr 18, 2023 |
| Supermicro    | X9DRW                       | Server      | [6994c89077](https://linux-hardware.org/?probe=6994c89077) | Apr 17, 2023 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [121237b9c1](https://linux-hardware.org/?probe=121237b9c1) | Apr 17, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [11f85df48e](https://linux-hardware.org/?probe=11f85df48e) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [438e774de5](https://linux-hardware.org/?probe=438e774de5) | Apr 17, 2023 |
| HP            | 0AECh D                     | Desktop     | [f6c67d337e](https://linux-hardware.org/?probe=f6c67d337e) | Apr 17, 2023 |
| LG Electro... | P530-KE6BK                  | Notebook    | [b1f0863c79](https://linux-hardware.org/?probe=b1f0863c79) | Apr 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [6ea01fad49](https://linux-hardware.org/?probe=6ea01fad49) | Apr 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7f5feb82ab](https://linux-hardware.org/?probe=7f5feb82ab) | Apr 17, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [a4bb147f89](https://linux-hardware.org/?probe=a4bb147f89) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d5db24c28d](https://linux-hardware.org/?probe=d5db24c28d) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [89eb2b2c32](https://linux-hardware.org/?probe=89eb2b2c32) | Apr 17, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [6364dbb93a](https://linux-hardware.org/?probe=6364dbb93a) | Apr 16, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4f3345aced](https://linux-hardware.org/?probe=4f3345aced) | Apr 16, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [4443ff9154](https://linux-hardware.org/?probe=4443ff9154) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [9c885fa5cf](https://linux-hardware.org/?probe=9c885fa5cf) | Apr 16, 2023 |
| HP            | 18E7                        | Desktop     | [6c2c248eec](https://linux-hardware.org/?probe=6c2c248eec) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [8fb4ed64eb](https://linux-hardware.org/?probe=8fb4ed64eb) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5943787304](https://linux-hardware.org/?probe=5943787304) | Apr 16, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1f02ee3393](https://linux-hardware.org/?probe=1f02ee3393) | Apr 16, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [d532f6fdbd](https://linux-hardware.org/?probe=d532f6fdbd) | Apr 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [c622c73721](https://linux-hardware.org/?probe=c622c73721) | Apr 16, 2023 |
| HP            | Notebook                    | Notebook    | [7614984f1d](https://linux-hardware.org/?probe=7614984f1d) | Apr 15, 2023 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [8ca60a45fe](https://linux-hardware.org/?probe=8ca60a45fe) | Apr 15, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7d9278e08a](https://linux-hardware.org/?probe=7d9278e08a) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [e0b2a066ee](https://linux-hardware.org/?probe=e0b2a066ee) | Apr 15, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [be369fe18a](https://linux-hardware.org/?probe=be369fe18a) | Apr 15, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [984cf8fd47](https://linux-hardware.org/?probe=984cf8fd47) | Apr 14, 2023 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [cb1763401c](https://linux-hardware.org/?probe=cb1763401c) | Apr 14, 2023 |
| Medion        | TJ4125                      | Desktop     | [887d24e023](https://linux-hardware.org/?probe=887d24e023) | Apr 14, 2023 |
| Lenovo        | 7Z73CTO1WW 05               | Server      | [29f89998ee](https://linux-hardware.org/?probe=29f89998ee) | Apr 14, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [39afaea9e3](https://linux-hardware.org/?probe=39afaea9e3) | Apr 14, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [6fdb6931f0](https://linux-hardware.org/?probe=6fdb6931f0) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d7768947bc](https://linux-hardware.org/?probe=d7768947bc) | Apr 14, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [b3c99bf352](https://linux-hardware.org/?probe=b3c99bf352) | Apr 14, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [5d37070bf0](https://linux-hardware.org/?probe=5d37070bf0) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [6af1f492c4](https://linux-hardware.org/?probe=6af1f492c4) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [f4cbe67033](https://linux-hardware.org/?probe=f4cbe67033) | Apr 14, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [cc951809ed](https://linux-hardware.org/?probe=cc951809ed) | Apr 14, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [c76a516113](https://linux-hardware.org/?probe=c76a516113) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [9ab8e04a20](https://linux-hardware.org/?probe=9ab8e04a20) | Apr 14, 2023 |
| Acer          | AO756                       | Notebook    | [58efd2f87f](https://linux-hardware.org/?probe=58efd2f87f) | Apr 14, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [7730eb04fa](https://linux-hardware.org/?probe=7730eb04fa) | Apr 14, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6106a2c31f](https://linux-hardware.org/?probe=6106a2c31f) | Apr 13, 2023 |
| sunxi         | LeMaker Banana Pi           | Soc         | [7a60bb63b4](https://linux-hardware.org/?probe=7a60bb63b4) | Apr 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [70e0ac9475](https://linux-hardware.org/?probe=70e0ac9475) | Apr 13, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | Desktop     | [5be961705c](https://linux-hardware.org/?probe=5be961705c) | Apr 13, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [1a327ce647](https://linux-hardware.org/?probe=1a327ce647) | Apr 13, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [33a7fad816](https://linux-hardware.org/?probe=33a7fad816) | Apr 13, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [721a60ff30](https://linux-hardware.org/?probe=721a60ff30) | Apr 13, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [bc3ccff50c](https://linux-hardware.org/?probe=bc3ccff50c) | Apr 13, 2023 |
| ASRock        | H410M-HVS R2.0              | Desktop     | [7f388965d7](https://linux-hardware.org/?probe=7f388965d7) | Apr 13, 2023 |
| HP            | 21EF                        | Desktop     | [d2b3751fd1](https://linux-hardware.org/?probe=d2b3751fd1) | Apr 13, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [c3962286cb](https://linux-hardware.org/?probe=c3962286cb) | Apr 13, 2023 |
| Dell          | 0XD433 A00                  | Desktop     | [e0a30bf441](https://linux-hardware.org/?probe=e0a30bf441) | Apr 12, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [533131a67a](https://linux-hardware.org/?probe=533131a67a) | Apr 12, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [401c4d8143](https://linux-hardware.org/?probe=401c4d8143) | Apr 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [abedf2741f](https://linux-hardware.org/?probe=abedf2741f) | Apr 12, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [5411d789c3](https://linux-hardware.org/?probe=5411d789c3) | Apr 12, 2023 |
| HP            | Pavilion dv6                | Notebook    | [09b80dd551](https://linux-hardware.org/?probe=09b80dd551) | Apr 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [4363479bf0](https://linux-hardware.org/?probe=4363479bf0) | Apr 12, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [9408f6348b](https://linux-hardware.org/?probe=9408f6348b) | Apr 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [108725a205](https://linux-hardware.org/?probe=108725a205) | Apr 12, 2023 |
| MSI           | Z370 PC PRO                 | Desktop     | [fb3078d5c3](https://linux-hardware.org/?probe=fb3078d5c3) | Apr 12, 2023 |
| Intel         | H61 V124                    | Desktop     | [28b73b97b3](https://linux-hardware.org/?probe=28b73b97b3) | Apr 12, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [4eb8c9f372](https://linux-hardware.org/?probe=4eb8c9f372) | Apr 12, 2023 |
| MSI           | MS-7060                     | Desktop     | [d78aaad9ec](https://linux-hardware.org/?probe=d78aaad9ec) | Apr 12, 2023 |
| Lenovo        | ThinkPad E470 20H2S00700    | Notebook    | [ea2aa5245d](https://linux-hardware.org/?probe=ea2aa5245d) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [c074d665d9](https://linux-hardware.org/?probe=c074d665d9) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [845a04c326](https://linux-hardware.org/?probe=845a04c326) | Apr 11, 2023 |
| HP            | 8158 A01                    | Mini pc     | [a7d7e5c675](https://linux-hardware.org/?probe=a7d7e5c675) | Apr 11, 2023 |
| Packard Be... | EasyNote_MX45               | Notebook    | [95935443c0](https://linux-hardware.org/?probe=95935443c0) | Apr 11, 2023 |
| HP            | 1589                        | Desktop     | [c04488f359](https://linux-hardware.org/?probe=c04488f359) | Apr 11, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [e4299a2ce6](https://linux-hardware.org/?probe=e4299a2ce6) | Apr 11, 2023 |
| ASUSTek       | X550JF                      | Notebook    | [dff4654bd2](https://linux-hardware.org/?probe=dff4654bd2) | Apr 11, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [7232d92c69](https://linux-hardware.org/?probe=7232d92c69) | Apr 11, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [c039220e20](https://linux-hardware.org/?probe=c039220e20) | Apr 11, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [1f19b2c0dc](https://linux-hardware.org/?probe=1f19b2c0dc) | Apr 11, 2023 |
| HP            | 1589                        | Desktop     | [e52c705c13](https://linux-hardware.org/?probe=e52c705c13) | Apr 11, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [64759fca72](https://linux-hardware.org/?probe=64759fca72) | Apr 10, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [5d84a5a711](https://linux-hardware.org/?probe=5d84a5a711) | Apr 10, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [94efe20a0f](https://linux-hardware.org/?probe=94efe20a0f) | Apr 10, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a3062022a3](https://linux-hardware.org/?probe=a3062022a3) | Apr 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE1M    | Notebook    | [eb794b0dc7](https://linux-hardware.org/?probe=eb794b0dc7) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | Notebook    | [fec574fe0d](https://linux-hardware.org/?probe=fec574fe0d) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | Notebook    | [f97c4e6d47](https://linux-hardware.org/?probe=f97c4e6d47) | Apr 10, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ea4fdd80e6](https://linux-hardware.org/?probe=ea4fdd80e6) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [5b0601fc42](https://linux-hardware.org/?probe=5b0601fc42) | Apr 09, 2023 |
| Medion        | TJ4125                      | Desktop     | [5c5f39a8fd](https://linux-hardware.org/?probe=5c5f39a8fd) | Apr 09, 2023 |
| Supermicro    | X9DRW                       | Server      | [dae7b6b11e](https://linux-hardware.org/?probe=dae7b6b11e) | Apr 09, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [085d715399](https://linux-hardware.org/?probe=085d715399) | Apr 09, 2023 |
| HP            | 2B29                        | Desktop     | [b909d3c46d](https://linux-hardware.org/?probe=b909d3c46d) | Apr 09, 2023 |
| HP            | 2B29                        | Desktop     | [1fd9cd3d7c](https://linux-hardware.org/?probe=1fd9cd3d7c) | Apr 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3b665833d1](https://linux-hardware.org/?probe=3b665833d1) | Apr 09, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [bff5545041](https://linux-hardware.org/?probe=bff5545041) | Apr 08, 2023 |
| HP            | 83E9                        | Desktop     | [4e62f72ee2](https://linux-hardware.org/?probe=4e62f72ee2) | Apr 08, 2023 |
| HP            | 83E9                        | Desktop     | [36fdd064cc](https://linux-hardware.org/?probe=36fdd064cc) | Apr 08, 2023 |
| libre-comp... | aml-s905x-cc                | Soc         | [2c41d3c020](https://linux-hardware.org/?probe=2c41d3c020) | Apr 08, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [d5fb19d97c](https://linux-hardware.org/?probe=d5fb19d97c) | Apr 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [fc28f6d3f0](https://linux-hardware.org/?probe=fc28f6d3f0) | Apr 08, 2023 |
| HP            | ENVY dv6                    | Notebook    | [0d89a1797e](https://linux-hardware.org/?probe=0d89a1797e) | Apr 08, 2023 |
| MSI           | GL65 Leopard 10SCSR         | Notebook    | [3063414a8c](https://linux-hardware.org/?probe=3063414a8c) | Apr 08, 2023 |
| AMI           | Intel                       | Desktop     | [48c620d141](https://linux-hardware.org/?probe=48c620d141) | Apr 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [48ab84d4f4](https://linux-hardware.org/?probe=48ab84d4f4) | Apr 08, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [8f34b2347f](https://linux-hardware.org/?probe=8f34b2347f) | Apr 07, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [36c87da9d9](https://linux-hardware.org/?probe=36c87da9d9) | Apr 07, 2023 |
| Lenovo        | ThinkPad T450 20BUA05900    | Notebook    | [e771177cca](https://linux-hardware.org/?probe=e771177cca) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | Notebook    | [6d50e55675](https://linux-hardware.org/?probe=6d50e55675) | Apr 07, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3ec1e98abd](https://linux-hardware.org/?probe=3ec1e98abd) | Apr 07, 2023 |
| Google        | Reks                        | Notebook    | [25341f2040](https://linux-hardware.org/?probe=25341f2040) | Apr 07, 2023 |
| Google        | Reks                        | Notebook    | [21c7e0c282](https://linux-hardware.org/?probe=21c7e0c282) | Apr 07, 2023 |
| Google        | Terra                       | Notebook    | [09a6a1ca8f](https://linux-hardware.org/?probe=09a6a1ca8f) | Apr 07, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [3d53baddbf](https://linux-hardware.org/?probe=3d53baddbf) | Apr 07, 2023 |
| Inventec      | VXC Class A02               | Desktop     | [3ff1b18b81](https://linux-hardware.org/?probe=3ff1b18b81) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | Notebook    | [a74c66fc15](https://linux-hardware.org/?probe=a74c66fc15) | Apr 07, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [023a578b76](https://linux-hardware.org/?probe=023a578b76) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | Notebook    | [46990342e8](https://linux-hardware.org/?probe=46990342e8) | Apr 06, 2023 |
| Acer          | TravelMate 5735Z            | Notebook    | [6d0065dea2](https://linux-hardware.org/?probe=6d0065dea2) | Apr 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [d5c75a0967](https://linux-hardware.org/?probe=d5c75a0967) | Apr 06, 2023 |
| MSI           | MS-7253                     | Desktop     | [1b9074e1ac](https://linux-hardware.org/?probe=1b9074e1ac) | Apr 06, 2023 |
| Dell          | Latitude E7250              | Notebook    | [e5fe0c7962](https://linux-hardware.org/?probe=e5fe0c7962) | Apr 06, 2023 |
| Foxconn       | 2A8C                        | Desktop     | [f202bac0de](https://linux-hardware.org/?probe=f202bac0de) | Apr 06, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | Desktop     | [6d7db3d917](https://linux-hardware.org/?probe=6d7db3d917) | Apr 06, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [ca1cdc7f46](https://linux-hardware.org/?probe=ca1cdc7f46) | Apr 06, 2023 |
| MSI           | MS-B1831                    | Desktop     | [9ea2ec4f47](https://linux-hardware.org/?probe=9ea2ec4f47) | Apr 06, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [6a8c52faa7](https://linux-hardware.org/?probe=6a8c52faa7) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [ea7a921618](https://linux-hardware.org/?probe=ea7a921618) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [125f93468e](https://linux-hardware.org/?probe=125f93468e) | Apr 06, 2023 |
| HP            | 895C                        | Desktop     | [27de3e2244](https://linux-hardware.org/?probe=27de3e2244) | Apr 06, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a1d46a2184](https://linux-hardware.org/?probe=a1d46a2184) | Apr 06, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | Desktop     | [9c6a3de994](https://linux-hardware.org/?probe=9c6a3de994) | Apr 05, 2023 |
| HP            | 895C                        | Desktop     | [3c87e6de19](https://linux-hardware.org/?probe=3c87e6de19) | Apr 05, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6dbb59e2fc](https://linux-hardware.org/?probe=6dbb59e2fc) | Apr 05, 2023 |
| Dell          | 0V0D45 A01                  | All in one  | [1940c6417c](https://linux-hardware.org/?probe=1940c6417c) | Apr 05, 2023 |
| Toshiba       | Satellite C855D-12J         | Notebook    | [cb3dedf5e8](https://linux-hardware.org/?probe=cb3dedf5e8) | Apr 05, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [d9ab0a1946](https://linux-hardware.org/?probe=d9ab0a1946) | Apr 05, 2023 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [2783ec6da9](https://linux-hardware.org/?probe=2783ec6da9) | Apr 05, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [ba90a2c123](https://linux-hardware.org/?probe=ba90a2c123) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [7f6103b394](https://linux-hardware.org/?probe=7f6103b394) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [ac039ed7e6](https://linux-hardware.org/?probe=ac039ed7e6) | Apr 05, 2023 |
| Dell          | Precision M4700             | Notebook    | [1e2be52d80](https://linux-hardware.org/?probe=1e2be52d80) | Apr 05, 2023 |
| HP            | 1790                        | Desktop     | [55e3d423e0](https://linux-hardware.org/?probe=55e3d423e0) | Apr 05, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [58cf8c28ff](https://linux-hardware.org/?probe=58cf8c28ff) | Apr 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 965       | 13.17%  |
| 5.10.0-7-amd64         | 691       | 9.43%   |
| 5.10.0-10-amd64        | 575       | 7.84%   |
| 5.10.0-21-amd64        | 468       | 6.38%   |
| 5.10.0-16-amd64        | 371       | 5.06%   |
| 5.10.0-20-amd64        | 367       | 5.01%   |
| 5.10.0-9-amd64         | 327       | 4.46%   |
| 5.10.0-18-amd64        | 291       | 3.97%   |
| 5.10.0-19-amd64        | 290       | 3.96%   |
| 5.10.0-13-amd64        | 265       | 3.62%   |
| 5.10.0-23-amd64        | 203       | 2.77%   |
| 5.10.0-11-amd64        | 194       | 2.65%   |
| 5.10.0-2-amd64         | 158       | 2.16%   |
| 5.10.0-14-amd64        | 140       | 1.91%   |
| 5.10.0-17-amd64        | 126       | 1.72%   |
| 5.10.0-15-amd64        | 104       | 1.42%   |
| 5.10.0-22-amd64        | 97        | 1.32%   |
| 5.10.0-12-amd64        | 74        | 1.01%   |
| 5.10.0-6-amd64         | 46        | 0.63%   |
| 6.0.0-0.deb11.6-amd64  | 44        | 0.6%    |
| 5.18.0-0.deb11.4-amd64 | 40        | 0.55%   |
| 5.15.0-2-amd64         | 38        | 0.52%   |
| 5.16.0-0.bpo.4-amd64   | 37        | 0.5%    |
| 5.10.0-13-686-pae      | 30        | 0.41%   |
| 6.0.0-0.deb11.2-amd64  | 29        | 0.4%    |
| 5.19.0-0.deb11.2-amd64 | 26        | 0.35%   |
| 5.15.74-1-pve          | 26        | 0.35%   |
| 5.18.0-0.bpo.1-amd64   | 25        | 0.34%   |
| 5.14.0-0.bpo.2-amd64   | 25        | 0.34%   |
| 5.13.19-6-pve          | 24        | 0.33%   |
| 5.15.85-1-pve          | 21        | 0.29%   |
| 6.1.0-0.deb11.7-amd64  | 20        | 0.27%   |
| 5.15.107-2-pve         | 20        | 0.27%   |
| 5.15.102-1-pve         | 20        | 0.27%   |
| 5.15.84-v8+            | 19        | 0.26%   |
| 6.1.0-0.deb11.5-amd64  | 18        | 0.25%   |
| 5.15.83-1-pve          | 18        | 0.25%   |
| 5.10.0-8-arm64         | 18        | 0.25%   |
| 5.15.32-v8+            | 17        | 0.23%   |
| 5.15.30-2-pve          | 17        | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 5486      | 81.12%  |
| 6.0.0    | 98        | 1.45%   |
| 5.18.0   | 94        | 1.39%   |
| 5.15.0   | 80        | 1.18%   |
| 5.16.0   | 68        | 1.01%   |
| 6.1.0    | 63        | 0.93%   |
| 5.19.0   | 60        | 0.89%   |
| 5.13.19  | 59        | 0.87%   |
| 5.14.0   | 43        | 0.64%   |
| 5.15.107 | 35        | 0.52%   |
| 5.15.74  | 30        | 0.44%   |
| 5.11.22  | 26        | 0.38%   |
| 5.17.0   | 24        | 0.35%   |
| 5.15.85  | 21        | 0.31%   |
| 5.15.84  | 20        | 0.3%    |
| 5.15.102 | 20        | 0.3%    |
| 5.15.83  | 19        | 0.28%   |
| 5.15.39  | 18        | 0.27%   |
| 5.15.32  | 18        | 0.27%   |
| 5.15.30  | 18        | 0.27%   |
| 5.15.35  | 17        | 0.25%   |
| 6.1.21   | 16        | 0.24%   |
| 5.15.76  | 15        | 0.22%   |
| 5.10.92  | 15        | 0.22%   |
| 5.15.53  | 14        | 0.21%   |
| 5.15.61  | 13        | 0.19%   |
| 4.19.0   | 11        | 0.16%   |
| 5.15.104 | 10        | 0.15%   |
| 6.1.15   | 8         | 0.12%   |
| 5.15.60  | 8         | 0.12%   |
| 6.2.6    | 7         | 0.1%    |
| 5.15.108 | 7         | 0.1%    |
| 5.13.0   | 7         | 0.1%    |
| 5.10.63  | 7         | 0.1%    |
| 6.2.9    | 6         | 0.09%   |
| 6.1.19   | 6         | 0.09%   |
| 5.19.17  | 6         | 0.09%   |
| 5.10.60  | 6         | 0.09%   |
| 6.2.11   | 5         | 0.07%   |
| 6.1.11   | 5         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10     | 5565      | 82.7%   |
| 5.15     | 391       | 5.81%   |
| 6.0      | 112       | 1.66%   |
| 6.1      | 108       | 1.6%    |
| 5.18     | 103       | 1.53%   |
| 5.19     | 80        | 1.19%   |
| 5.16     | 78        | 1.16%   |
| 5.13     | 78        | 1.16%   |
| 5.14     | 50        | 0.74%   |
| 5.11     | 35        | 0.52%   |
| 5.17     | 34        | 0.51%   |
| 6.2      | 27        | 0.4%    |
| 4.19     | 13        | 0.19%   |
| 5.4      | 10        | 0.15%   |
| 5.12     | 9         | 0.13%   |
| 6.3      | 7         | 0.1%    |
| 5        | 5         | 0.07%   |
| 4.4      | 4         | 0.06%   |
| 5.9      | 3         | 0.04%   |
| 5.1      | 3         | 0.04%   |
| 4.9      | 3         | 0.04%   |
| 6.4      | 2         | 0.03%   |
| 3.18     | 2         | 0.03%   |
| 5.8      | 1         | 0.01%   |
| 5.5      | 1         | 0.01%   |
| 5.15.6   | 1         | 0.01%   |
| 5.10.164 | 1         | 0.01%   |
| 4.14     | 1         | 0.01%   |
| 3.8      | 1         | 0.01%   |
| 3.10     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6164      | 93.58%  |
| i686    | 194       | 2.95%   |
| aarch64 | 190       | 2.88%   |
| armv7l  | 33        | 0.5%    |
| riscv64 | 5         | 0.08%   |
| i586    | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 2489      | 37.22%  |
| GNOME             | 1486      | 22.22%  |
| XFCE              | 755       | 11.29%  |
| KDE5              | 740       | 11.06%  |
| MATE              | 250       | 3.74%   |
| LXDE              | 203       | 3.04%   |
| X-Cinnamon        | 201       | 3.01%   |
| Cinnamon          | 156       | 2.33%   |
| LXQt              | 86        | 1.29%   |
| i3                | 69        | 1.03%   |
| KDE               | 51        | 0.76%   |
| Openbox           | 41        | 0.61%   |
| GNOME Flashback   | 38        | 0.57%   |
| lightdm-xsession  | 28        | 0.42%   |
| Trinity           | 22        | 0.33%   |
| Budgie            | 15        | 0.22%   |
| GNOME Classic     | 14        | 0.21%   |
| sway              | 5         | 0.07%   |
| awesome           | 5         | 0.07%   |
| DWM               | 4         | 0.06%   |
| x-session-manager | 3         | 0.04%   |
| Enlightenment     | 3         | 0.04%   |
| Cutefish          | 3         | 0.04%   |
| BunsenLabs        | 3         | 0.04%   |
| ICEWM             | 2         | 0.03%   |
| GNUstep           | 2         | 0.03%   |
| xmonad            | 1         | 0.01%   |
| wmaker-common     | 1         | 0.01%   |
| UKUI              | 1         | 0.01%   |
| Phosh:GNOME       | 1         | 0.01%   |
| mwm               | 1         | 0.01%   |
| matchbox          | 1         | 0.01%   |
| jwm               | 1         | 0.01%   |
| gnome-xorg        | 1         | 0.01%   |
| fvwm              | 1         | 0.01%   |
| fluxbox           | 1         | 0.01%   |
| e16-session       | 1         | 0.01%   |
| default           | 1         | 0.01%   |
| Deepin            | 1         | 0.01%   |
| /etc/X11/Xsession | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 3047      | 45.67%  |
| Unknown     | 1846      | 27.67%  |
| Wayland     | 965       | 14.46%  |
| Tty         | 806       | 12.08%  |
| Unspecified | 5         | 0.07%   |
| Web         | 3         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3195      | 47.99%  |
| LightDM | 1302      | 19.56%  |
| GDM     | 1179      | 17.71%  |
| SDDM    | 651       | 9.78%   |
| TDM     | 156       | 2.34%   |
| GDM3    | 124       | 1.86%   |
| XDM     | 15        | 0.23%   |
| SLiM    | 13        | 0.2%    |
| LXDM    | 11        | 0.17%   |
| NODM    | 6         | 0.09%   |
| SU      | 2         | 0.03%   |
| Ly      | 2         | 0.03%   |
| WDM     | 1         | 0.02%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2201      | 33.09%  |
| ru_RU   | 946       | 14.22%  |
| Unknown | 939       | 14.12%  |
| de_DE   | 394       | 5.92%   |
| fr_FR   | 333       | 5.01%   |
| en_GB   | 324       | 4.87%   |
| es_ES   | 191       | 2.87%   |
| it_IT   | 148       | 2.23%   |
| pt_BR   | 143       | 2.15%   |
| pl_PL   | 104       | 1.56%   |
| C       | 81        | 1.22%   |
| en_CA   | 76        | 1.14%   |
| en_AU   | 75        | 1.13%   |
| es_MX   | 49        | 0.74%   |
| zh_CN   | 41        | 0.62%   |
| es_AR   | 40        | 0.6%    |
| hu_HU   | 31        | 0.47%   |
| es_VE   | 30        | 0.45%   |
| en_IN   | 29        | 0.44%   |
| en_IE   | 29        | 0.44%   |
| ja_JP   | 24        | 0.36%   |
| de_CH   | 24        | 0.36%   |
| de_AT   | 22        | 0.33%   |
| nl_NL   | 19        | 0.29%   |
| fi_FI   | 17        | 0.26%   |
| en_NZ   | 17        | 0.26%   |
| sv_SE   | 16        | 0.24%   |
| pt_PT   | 16        | 0.24%   |
| es_CL   | 13        | 0.2%    |
| cs_CZ   | 13        | 0.2%    |
| nl_BE   | 12        | 0.18%   |
| fr_BE   | 12        | 0.18%   |
| es_CO   | 12        | 0.18%   |
| tr_TR   | 11        | 0.17%   |
| en_ZA   | 11        | 0.17%   |
| fr_CH   | 10        | 0.15%   |
| nb_NO   | 9         | 0.14%   |
| en_SG   | 9         | 0.14%   |
| zh_TW   | 8         | 0.12%   |
| uk_UA   | 8         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3836      | 57.62%  |
| BIOS | 2821      | 42.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 4313      | 65.2%   |
| Overlay | 1879      | 28.41%  |
| Btrfs   | 196       | 2.96%   |
| Zfs     | 108       | 1.63%   |
| Xfs     | 67        | 1.01%   |
| Tmpfs   | 18        | 0.27%   |
| Ext3    | 13        | 0.2%    |
| Ext2    | 9         | 0.14%   |
| Unknown | 8         | 0.12%   |
| Rootfs  | 2         | 0.03%   |
| Aufs    | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3986      | 59.89%  |
| MBR     | 1797      | 27%     |
| Unknown | 873       | 13.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5399      | 81.27%  |
| Yes       | 1244      | 18.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4640      | 69.85%  |
| Yes       | 2003      | 30.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 949       | 14.41%  |
| Lenovo                  | 920       | 13.97%  |
| Hewlett-Packard         | 708       | 10.75%  |
| Apple                   | 684       | 10.39%  |
| Dell                    | 658       | 9.99%   |
| Gigabyte Technology     | 416       | 6.32%   |
| MSI                     | 307       | 4.66%   |
| Acer                    | 229       | 3.48%   |
| ASRock                  | 227       | 3.45%   |
| Intel                   | 153       | 2.32%   |
| Google                  | 141       | 2.14%   |
| Raspberry Pi Foundation | 139       | 2.11%   |
| Unknown                 | 102       | 1.55%   |
| Supermicro              | 65        | 0.99%   |
| Toshiba                 | 52        | 0.79%   |
| Fujitsu                 | 50        | 0.76%   |
| ECS                     | 48        | 0.73%   |
| Aquarius                | 47        | 0.71%   |
| Samsung Electronics     | 44        | 0.67%   |
| AZW                     | 33        | 0.5%    |
| ASRockRack              | 30        | 0.46%   |
| HUAWEI                  | 28        | 0.43%   |
| Foxconn                 | 28        | 0.43%   |
| Sony                    | 19        | 0.29%   |
| Notebook                | 19        | 0.29%   |
| Pegatron                | 17        | 0.26%   |
| Packard Bell            | 16        | 0.24%   |
| Medion                  | 15        | 0.23%   |
| AMI                     | 14        | 0.21%   |
| Inventec                | 13        | 0.2%    |
| Biostar                 | 13        | 0.2%    |
| Hardkernel              | 12        | 0.18%   |
| BESSTAR Tech            | 12        | 0.18%   |
| sunxi                   | 11        | 0.17%   |
| Positivo                | 11        | 0.17%   |
| Microsoft               | 11        | 0.17%   |
| Panasonic               | 9         | 0.14%   |
| IBM                     | 9         | 0.14%   |
| Clevo                   | 9         | 0.14%   |
| Xunlong                 | 8         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 353       | 5.36%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 114       | 1.73%   |
| Unknown                                   | 113       | 1.72%   |
| ASUS All Series                           | 80        | 1.21%   |
| Apple MacBookAir7,2                       | 77        | 1.17%   |
| Apple MacBookAir7,1                       | 77        | 1.17%   |
| Google Enguarde                           | 74        | 1.12%   |
| ASUS S20 K29                              | 55        | 0.84%   |
| Apple MacBook2,1                          | 55        | 0.84%   |
| Aquarius NS585                            | 44        | 0.67%   |
| MSI MS-7996                               | 38        | 0.58%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 28        | 0.43%   |
| Lenovo ThinkPad E475 20H40006US           | 24        | 0.36%   |
| Google Terra                              | 23        | 0.35%   |
| MSI MS-7817                               | 22        | 0.33%   |
| ECS G31T-M9                               | 22        | 0.33%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 21        | 0.32%   |
| Apple MacBook4,1                          | 21        | 0.32%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 20        | 0.3%    |
| ASRock H470M-HVS                          | 20        | 0.3%    |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 19        | 0.29%   |
| HP Notebook                               | 18        | 0.27%   |
| Gigabyte H81M-S2V                         | 18        | 0.27%   |
| Supermicro Super Server                   | 17        | 0.26%   |
| ASUS PRIME H510M-A                        | 17        | 0.26%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.24%   |
| Gigabyte H410M S2H                        | 16        | 0.24%   |
| ECS H61H2-M13                             | 16        | 0.24%   |
| ASUS P8H61-M LX3 R2.0                     | 15        | 0.23%   |
| Acer Aspire A315-23                       | 15        | 0.23%   |
| ASUS 1005HA                               | 14        | 0.21%   |
| Google Reks                               | 13        | 0.2%    |
| Dell OptiPlex 7010                        | 13        | 0.2%    |
| HP Pavilion g6                            | 12        | 0.18%   |
| Gigabyte B450M DS3H                       | 11        | 0.17%   |
| AZW U59                                   | 11        | 0.17%   |
| RPi Raspberry Pi 4 Model B Rev 1.5        | 10        | 0.15%   |
| HP Laptop 15-db0xxx                       | 10        | 0.15%   |
| AZW MINI S                                | 10        | 0.15%   |
| ASUS PRIME B450M-A                        | 10        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 580       | 8.81%   |
| Apple MacBook5     | 353       | 5.36%   |
| Dell Latitude      | 185       | 2.81%   |
| Apple MacBookAir7  | 154       | 2.34%   |
| Acer Aspire        | 147       | 2.23%   |
| Dell Inspiron      | 142       | 2.16%   |
| RPi Raspberry      | 139       | 2.11%   |
| ASUS PRIME         | 134       | 2.03%   |
| Unknown            | 113       | 1.72%   |
| Lenovo IdeaPad     | 108       | 1.64%   |
| HP EliteBook       | 105       | 1.59%   |
| Dell OptiPlex      | 96        | 1.46%   |
| HP Pavilion        | 88        | 1.34%   |
| ASUS All           | 80        | 1.21%   |
| Google Enguarde    | 74        | 1.12%   |
| Dell Precision     | 74        | 1.12%   |
| HP Laptop          | 71        | 1.08%   |
| HP Compaq          | 71        | 1.08%   |
| Lenovo ThinkCentre | 61        | 0.93%   |
| ASUS ROG           | 60        | 0.91%   |
| HP ProBook         | 57        | 0.87%   |
| ASUS S20           | 55        | 0.84%   |
| Apple MacBook2     | 55        | 0.84%   |
| Dell XPS           | 52        | 0.79%   |
| ASUS TUF           | 49        | 0.74%   |
| Aquarius NS585     | 44        | 0.67%   |
| ASUS VivoBook      | 43        | 0.65%   |
| Toshiba Satellite  | 42        | 0.64%   |
| Dell PowerEdge     | 41        | 0.62%   |
| Dell Vostro        | 40        | 0.61%   |
| MSI MS-7996        | 38        | 0.58%   |
| HP ProLiant        | 36        | 0.55%   |
| ASUS P8H61-M       | 31        | 0.47%   |
| HP ENVY            | 25        | 0.38%   |
| HP ELITEDESK       | 25        | 0.38%   |
| Gigabyte B450M     | 25        | 0.38%   |
| ASUS ASUS          | 25        | 0.38%   |
| HP ZBook           | 23        | 0.35%   |
| Google Terra       | 23        | 0.35%   |
| ASUS ZenBook       | 23        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 759       | 11.53%  |
| 2021    | 615       | 9.34%   |
| 2009    | 560       | 8.5%    |
| 2019    | 496       | 7.53%   |
| 2018    | 455       | 6.91%   |
| 2012    | 450       | 6.83%   |
| 2013    | 380       | 5.77%   |
| 2015    | 359       | 5.45%   |
| 2011    | 337       | 5.12%   |
| 2017    | 335       | 5.09%   |
| 2016    | 332       | 5.04%   |
| 2022    | 298       | 4.53%   |
| 2014    | 292       | 4.43%   |
| 2010    | 228       | 3.46%   |
| Unknown | 200       | 3.04%   |
| 2008    | 183       | 2.78%   |
| 2007    | 162       | 2.46%   |
| 2006    | 52        | 0.79%   |
| 2005    | 36        | 0.55%   |
| 2023    | 26        | 0.39%   |
| 2003    | 15        | 0.23%   |
| 2004    | 10        | 0.15%   |
| 2001    | 3         | 0.05%   |
| 2002    | 1         | 0.02%   |
| 2000    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3338      | 50.69%  |
| Desktop        | 2448      | 37.18%  |
| System on chip | 212       | 3.22%   |
| Convertible    | 200       | 3.04%   |
| Mini pc        | 160       | 2.43%   |
| Server         | 137       | 2.08%   |
| All in one     | 53        | 0.8%    |
| Tablet         | 32        | 0.49%   |
| Phone          | 4         | 0.06%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6244      | 94.43%  |
| Enabled  | 368       | 5.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6432      | 97.66%  |
| Yes  | 154       | 2.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1512      | 22.76%  |
| 16.01-24.0      | 1193      | 17.96%  |
| 3.01-4.0        | 1182      | 17.79%  |
| 8.01-16.0       | 839       | 12.63%  |
| 1.01-2.0        | 655       | 9.86%   |
| 32.01-64.0      | 545       | 8.2%    |
| 64.01-256.0     | 315       | 4.74%   |
| 0.51-1.0        | 126       | 1.9%    |
| 2.01-3.0        | 123       | 1.85%   |
| 24.01-32.0      | 96        | 1.44%   |
| 0.01-0.5        | 31        | 0.47%   |
| More than 256.0 | 26        | 0.39%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 2354      | 33.89%  |
| 0.51-1.0        | 1229      | 17.7%   |
| 2.01-3.0        | 1166      | 16.79%  |
| 4.01-8.0        | 784       | 11.29%  |
| 3.01-4.0        | 616       | 8.87%   |
| 0.01-0.5        | 339       | 4.88%   |
| 8.01-16.0       | 263       | 3.79%   |
| 16.01-24.0      | 77        | 1.11%   |
| 32.01-64.0      | 52        | 0.75%   |
| 24.01-32.0      | 37        | 0.53%   |
| 64.01-256.0     | 24        | 0.35%   |
| More than 256.0 | 2         | 0.03%   |
| Unknown         | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 4499      | 67.19%  |
| 2      | 1217      | 18.18%  |
| 3      | 390       | 5.82%   |
| 4      | 227       | 3.39%   |
| 5      | 108       | 1.61%   |
| 6      | 64        | 0.96%   |
| 0      | 55        | 0.82%   |
| 7      | 39        | 0.58%   |
| 8      | 34        | 0.51%   |
| 9      | 14        | 0.21%   |
| 10     | 12        | 0.18%   |
| 13     | 10        | 0.15%   |
| 12     | 7         | 0.1%    |
| 14     | 4         | 0.06%   |
| 11     | 4         | 0.06%   |
| 28     | 2         | 0.03%   |
| 79     | 1         | 0.01%   |
| 47     | 1         | 0.01%   |
| 29     | 1         | 0.01%   |
| 27     | 1         | 0.01%   |
| 26     | 1         | 0.01%   |
| 22     | 1         | 0.01%   |
| 21     | 1         | 0.01%   |
| 19     | 1         | 0.01%   |
| 18     | 1         | 0.01%   |
| 16     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4498      | 68.08%  |
| Yes       | 2109      | 31.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5691      | 86.29%  |
| No        | 904       | 13.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4440      | 67.26%  |
| No        | 2161      | 32.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3694      | 55.85%  |
| No        | 2920      | 44.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 1725      | 26.14%  |
| Russia      | 1009      | 15.29%  |
| Germany     | 611       | 9.26%   |
| France      | 424       | 6.42%   |
| Spain       | 248       | 3.76%   |
| Italy       | 202       | 3.06%   |
| Brazil      | 197       | 2.98%   |
| UK          | 170       | 2.58%   |
| Poland      | 158       | 2.39%   |
| Canada      | 134       | 2.03%   |
| Netherlands | 106       | 1.61%   |
| Australia   | 105       | 1.59%   |
| Switzerland | 95        | 1.44%   |
| Mexico      | 76        | 1.15%   |
| China       | 76        | 1.15%   |
| Argentina   | 68        | 1.03%   |
| Sweden      | 56        | 0.85%   |
| Austria     | 51        | 0.77%   |
| Hungary     | 50        | 0.76%   |
| Belgium     | 50        | 0.76%   |
| Ukraine     | 49        | 0.74%   |
| Finland     | 43        | 0.65%   |
| India       | 42        | 0.64%   |
| Czechia     | 42        | 0.64%   |
| Norway      | 41        | 0.62%   |
| Portugal    | 39        | 0.59%   |
| Turkey      | 37        | 0.56%   |
| Venezuela   | 35        | 0.53%   |
| Bulgaria    | 34        | 0.52%   |
| Japan       | 33        | 0.5%    |
| Romania     | 30        | 0.45%   |
| Ireland     | 26        | 0.39%   |
| Greece      | 23        | 0.35%   |
| Taiwan      | 22        | 0.33%   |
| New Zealand | 22        | 0.33%   |
| Denmark     | 22        | 0.33%   |
| Colombia    | 21        | 0.32%   |
| Croatia     | 20        | 0.3%    |
| Slovakia    | 19        | 0.29%   |
| Chile       | 18        | 0.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Bangor            | 757       | 11%     |
| Voronezh          | 715       | 10.39%  |
| Dover-Foxcroft    | 304       | 4.42%   |
| Paris             | 67        | 0.97%   |
| Moscow            | 67        | 0.97%   |
| Seville           | 53        | 0.77%   |
| St Petersburg     | 52        | 0.76%   |
| Berlin            | 43        | 0.62%   |
| Madrid            | 38        | 0.55%   |
| Warsaw            | 37        | 0.54%   |
| Vienna            | 37        | 0.54%   |
| Barcelona         | 32        | 0.46%   |
| Munich            | 31        | 0.45%   |
| Zurich            | 30        | 0.44%   |
| Milan             | 30        | 0.44%   |
| Amsterdam         | 29        | 0.42%   |
| Sao Paulo         | 27        | 0.39%   |
| Toronto           | 24        | 0.35%   |
| Falkenstein       | 24        | 0.35%   |
| Sydney            | 23        | 0.33%   |
| Melbourne         | 21        | 0.31%   |
| Hamburg           | 21        | 0.31%   |
| Frankfurt am Main | 21        | 0.31%   |
| Brisbane          | 21        | 0.31%   |
| Perm              | 20        | 0.29%   |
| London            | 20        | 0.29%   |
| Stuttgart         | 18        | 0.26%   |
| Helsinki          | 18        | 0.26%   |
| Buenos Aires      | 18        | 0.26%   |
| Prague            | 17        | 0.25%   |
| Istanbul          | 17        | 0.25%   |
| Dublin            | 17        | 0.25%   |
| Cologne           | 17        | 0.25%   |
| Chicago           | 16        | 0.23%   |
| San Jose          | 15        | 0.22%   |
| Leipzig           | 15        | 0.22%   |
| Budapest          | 15        | 0.22%   |
| Valencia          | 14        | 0.2%    |
| Sofia             | 14        | 0.2%    |
| Nuremberg         | 14        | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1352      | 1982   | 14.88%  |
| WDC                 | 1202      | 1937   | 13.23%  |
| Seagate             | 1131      | 2065   | 12.44%  |
| Toshiba             | 624       | 901    | 6.87%   |
| Kingston            | 553       | 691    | 6.08%   |
| Unknown             | 512       | 656    | 5.63%   |
| Crucial             | 422       | 512    | 4.64%   |
| SanDisk             | 358       | 447    | 3.94%   |
| Fujitsu             | 284       | 294    | 3.13%   |
| Hitachi             | 261       | 342    | 2.87%   |
| Intel               | 208       | 291    | 2.29%   |
| Apple               | 197       | 235    | 2.17%   |
| SK hynix            | 183       | 225    | 2.01%   |
| A-DATA Technology   | 162       | 271    | 1.78%   |
| HGST                | 144       | 233    | 1.58%   |
| Micron Technology   | 124       | 150    | 1.36%   |
| China               | 105       | 120    | 1.16%   |
| Unknown             | 74        | 79     | 0.81%   |
| KIOXIA              | 62        | 68     | 0.68%   |
| SPCC                | 60        | 70     | 0.66%   |
| PNY                 | 56        | 96     | 0.62%   |
| Transcend           | 47        | 54     | 0.52%   |
| Phison              | 42        | 53     | 0.46%   |
| Intenso             | 41        | 52     | 0.45%   |
| JMicron Technology  | 37        | 40     | 0.41%   |
| Netac               | 35        | 95     | 0.39%   |
| LITEON              | 35        | 42     | 0.39%   |
| Corsair             | 32        | 53     | 0.35%   |
| Patriot             | 31        | 37     | 0.34%   |
| SABRENT             | 29        | 30     | 0.32%   |
| Hewlett-Packard     | 27        | 47     | 0.3%    |
| GOODRAM             | 26        | 43     | 0.29%   |
| Silicon Motion      | 24        | 30     | 0.26%   |
| OCZ                 | 23        | 27     | 0.25%   |
| Maxtor              | 23        | 28     | 0.25%   |
| Team                | 22        | 43     | 0.24%   |
| Gigabyte Technology | 22        | 24     | 0.24%   |
| LITEONIT            | 20        | 27     | 0.22%   |
| Apacer              | 20        | 20     | 0.22%   |
| ASMT                | 18        | 25     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 237       | 2.37%   |
| Kingston SA400S37240G 240GB SSD    | 130       | 1.3%    |
| Samsung MZVLB512HBJQ-000L7 512GB   | 122       | 1.22%   |
| Seagate ST500DM002-1BD142 500GB    | 82        | 0.82%   |
| Crucial CT480BX500SSD1 480GB       | 77        | 0.77%   |
| Apple SSD AP0128H 121GB            | 77        | 0.77%   |
| Unknown                            | 74        | 0.74%   |
| Apple SSD SM0128G 121GB            | 72        | 0.72%   |
| Kingston SA400S37120G 120GB SSD    | 65        | 0.65%   |
| Kingston SV300S37A120G 120GB SSD   | 64        | 0.64%   |
| Toshiba DT01ACA050 500GB           | 61        | 0.61%   |
| Samsung SSD 860 EVO 500GB          | 60        | 0.6%    |
| Kingston SA400S37480G 480GB SSD    | 60        | 0.6%    |
| Samsung SSD 860 EVO 250GB          | 58        | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB       | 54        | 0.54%   |
| Crucial CT500MX500SSD1 500GB       | 54        | 0.54%   |
| Toshiba MK1655GSXF 160GB           | 53        | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB     | 53        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB        | 52        | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB     | 49        | 0.49%   |
| A-DATA SU800 512GB SSD             | 48        | 0.48%   |
| Unknown MMC Card  32GB             | 44        | 0.44%   |
| Samsung SSD 860 EVO 1TB            | 44        | 0.44%   |
| Samsung SSD 850 EVO 250GB          | 44        | 0.44%   |
| Toshiba MK1653GSX 160GB            | 43        | 0.43%   |
| Crucial CT240BX500SSD1 240GB       | 40        | 0.4%    |
| Unknown AGND3R  16GB               | 39        | 0.39%   |
| Samsung SSD 970 EVO Plus 500GB     | 39        | 0.39%   |
| Samsung SSD 850 EVO 500GB          | 39        | 0.39%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 37        | 0.37%   |
| Toshiba DT01ACA100 1TB             | 37        | 0.37%   |
| Samsung SSD 870 EVO 500GB          | 36        | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 35        | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB     | 35        | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB           | 33        | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB     | 33        | 0.33%   |
| Hitachi HDS721050CLA362 500GB      | 32        | 0.32%   |
| Unknown HAG2e  16GB                | 30        | 0.3%    |
| Toshiba HDWD110 1TB                | 30        | 0.3%    |
| SanDisk NVMe SSD Drive 1TB         | 29        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1100      | 2002   | 31.87%  |
| WDC                 | 894       | 1496   | 25.91%  |
| Toshiba             | 523       | 773    | 15.16%  |
| Fujitsu             | 284       | 294    | 8.23%   |
| Hitachi             | 261       | 342    | 7.56%   |
| HGST                | 144       | 233    | 4.17%   |
| Samsung Electronics | 87        | 107    | 2.52%   |
| Unknown             | 28        | 37     | 0.81%   |
| JMicron Technology  | 23        | 26     | 0.67%   |
| Maxtor              | 21        | 23     | 0.61%   |
| Apple               | 13        | 16     | 0.38%   |
| ASMT                | 11        | 15     | 0.32%   |
| Hewlett-Packard     | 7         | 17     | 0.2%    |
| External            | 6         | 7      | 0.17%   |
| Intenso             | 5         | 5      | 0.14%   |
| ASMedia             | 5         | 5      | 0.14%   |
| USB3.0              | 4         | 4      | 0.12%   |
| QNAP                | 3         | 4      | 0.09%   |
| HPE                 | 3         | 10     | 0.09%   |
| IBM/Hitachi         | 2         | 2      | 0.06%   |
| IBM-ESXS            | 2         | 4      | 0.06%   |
| WD MediaMax         | 1         | 6      | 0.03%   |
| Unknown (CF)        | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| SSK                 | 1         | 1      | 0.03%   |
| SILICONMOTION       | 1         | 1      | 0.03%   |
| SD                  | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| pqi                 | 1         | 1      | 0.03%   |
| Pear 2TB            | 1         | 1      | 0.03%   |
| NAS                 | 1         | 5      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 4      | 0.03%   |
| MARSHAL             | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| IBM                 | 1         | 1      | 0.03%   |
| Hajaan              | 1         | 1      | 0.03%   |
| H/W                 | 1         | 3      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 630       | 853    | 20.68%  |
| Kingston            | 469       | 593    | 15.39%  |
| Crucial             | 368       | 443    | 12.08%  |
| SanDisk             | 239       | 300    | 7.84%   |
| WDC                 | 138       | 165    | 4.53%   |
| A-DATA Technology   | 121       | 202    | 3.97%   |
| China               | 103       | 118    | 3.38%   |
| Apple               | 98        | 107    | 3.22%   |
| Intel               | 89        | 131    | 2.92%   |
| Micron Technology   | 54        | 74     | 1.77%   |
| SPCC                | 49        | 56     | 1.61%   |
| PNY                 | 43        | 80     | 1.41%   |
| Transcend           | 42        | 49     | 1.38%   |
| Toshiba             | 39        | 48     | 1.28%   |
| SK hynix            | 38        | 48     | 1.25%   |
| Netac               | 34        | 94     | 1.12%   |
| Intenso             | 33        | 42     | 1.08%   |
| LITEON              | 29        | 34     | 0.95%   |
| Patriot             | 26        | 28     | 0.85%   |
| OCZ                 | 23        | 27     | 0.75%   |
| GOODRAM             | 21        | 29     | 0.69%   |
| Team                | 20        | 38     | 0.66%   |
| LITEONIT            | 20        | 27     | 0.66%   |
| Apacer              | 18        | 18     | 0.59%   |
| Unknown             | 16        | 18     | 0.53%   |
| Seagate             | 12        | 15     | 0.39%   |
| Hewlett-Packard     | 12        | 18     | 0.39%   |
| Gigabyte Technology | 12        | 12     | 0.39%   |
| Corsair             | 11        | 15     | 0.36%   |
| KingDian            | 9         | 9      | 0.3%    |
| Plextor             | 8         | 11     | 0.26%   |
| Unknown             | 7         | 10     | 0.23%   |
| Mushkin             | 7         | 8      | 0.23%   |
| Lexar               | 7         | 9      | 0.23%   |
| Hajaan              | 7         | 8      | 0.23%   |
| LDLC                | 6         | 6      | 0.2%    |
| Xinhaike            | 5         | 8      | 0.16%   |
| NGFF                | 5         | 5      | 0.16%   |
| KIOXIA-EXCERIA      | 5         | 8      | 0.16%   |
| Kingchuxing         | 5         | 6      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2970      | 5464   | 35.92%  |
| SSD     | 2691      | 3965   | 32.54%  |
| NVMe    | 1969      | 2754   | 23.81%  |
| MMC     | 537       | 663    | 6.49%   |
| Unknown | 102       | 154    | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4684      | 8936   | 62.28%  |
| NVMe | 1938      | 2711   | 25.77%  |
| MMC  | 537       | 663    | 7.14%   |
| SAS  | 362       | 690    | 4.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| 0.01-0.5    | 3688      | 5164   | 61.58%  |
| 0.51-1.0    | 1383      | 2147   | 23.09%  |
| 1.01-2.0    | 413       | 731    | 6.9%    |
| 3.01-4.0    | 194       | 523    | 3.24%   |
| 4.01-10.0   | 171       | 467    | 2.86%   |
| 2.01-3.0    | 91        | 180    | 1.52%   |
| 10.01-20.0  | 47        | 212    | 0.78%   |
| 20.01-50.0  | 1         | 1      | 0.02%   |
| 50.01-100.0 | 1         | 4      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1495      | 22.13%  |
| 101-250        | 1470      | 21.76%  |
| 251-500        | 1129      | 16.71%  |
| 501-1000       | 736       | 10.89%  |
| 51-100         | 411       | 6.08%   |
| 1-20           | 378       | 5.6%    |
| 1001-2000      | 368       | 5.45%   |
| More than 3000 | 336       | 4.97%   |
| 21-50          | 288       | 4.26%   |
| 2001-3000      | 145       | 2.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2510      | 36.42%  |
| Unknown        | 1495      | 21.69%  |
| 21-50          | 643       | 9.33%   |
| 101-250        | 618       | 8.97%   |
| 51-100         | 538       | 7.81%   |
| 251-500        | 389       | 5.64%   |
| 501-1000       | 296       | 4.29%   |
| 1001-2000      | 166       | 2.41%   |
| More than 3000 | 140       | 2.03%   |
| 2001-3000      | 75        | 1.09%   |
| 0              | 22        | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB       | 25        | 25     | 2.57%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 21        | 25     | 2.16%   |
| Kingston SV300S37A120G 120GB SSD     | 21        | 21     | 2.16%   |
| Seagate ST500DM002-1BD142 500GB      | 20        | 34     | 2.06%   |
| Hitachi HTS543216L9SA02 160GB        | 11        | 11     | 1.13%   |
| Seagate ST9500325AS 500GB            | 10        | 12     | 1.03%   |
| Toshiba MK1655GSXF 160GB             | 9         | 9      | 0.92%   |
| Toshiba MK1653GSX 160GB              | 9         | 9      | 0.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 9         | 10     | 0.92%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 8         | 8      | 0.82%   |
| Hitachi HDS721050CLA362 500GB        | 8         | 8      | 0.82%   |
| Toshiba DT01ACA050 500GB             | 7         | 8      | 0.72%   |
| Seagate ST9500420AS 500GB            | 7         | 7      | 0.72%   |
| Seagate ST250DM000-1BD141 250GB      | 7         | 7      | 0.72%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 6         | 7      | 0.62%   |
| Seagate ST3500418AS 500GB            | 6         | 8      | 0.62%   |
| Seagate ST3250318AS 250GB            | 6         | 6      | 0.62%   |
| Seagate ST31000528AS 1TB             | 6         | 7      | 0.62%   |
| Seagate ST1000DM003-9YN162 1TB       | 6         | 7      | 0.62%   |
| Hitachi HDS721050DLE630 500GB        | 6         | 11     | 0.62%   |
| HGST HTS541010A9E680 1TB             | 6         | 6      | 0.62%   |
| WDC WD20EARX-00PASB0 2TB             | 5         | 5      | 0.51%   |
| WDC WD20EARS-00MVWB0 2TB             | 5         | 5      | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB             | 5         | 5      | 0.51%   |
| Seagate ST500LM021-1KJ152 500GB      | 5         | 5      | 0.51%   |
| Seagate ST31500341AS 1TB             | 5         | 7      | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 6      | 0.51%   |
| Hitachi HTS542512K9SA00 120GB        | 5         | 6      | 0.51%   |
| HGST HTS725050A7E630 500GB           | 5         | 6      | 0.51%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 4         | 4      | 0.41%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 4         | 5      | 0.41%   |
| WDC WD1600BUDT-63DPZY0 160GB         | 4         | 4      | 0.41%   |
| Toshiba MQ01ABD100 1TB               | 4         | 4      | 0.41%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 4      | 0.41%   |
| Seagate ST500LT012-1DG142 500GB      | 4         | 4      | 0.41%   |
| Seagate ST3500413AS 500GB            | 4         | 5      | 0.41%   |
| Seagate ST3320613AS 320GB            | 4         | 4      | 0.41%   |
| Seagate ST2000DL003-9VT166 2TB       | 4         | 4      | 0.41%   |
| Seagate ST1000DM003-1CH162 1TB       | 4         | 4      | 0.41%   |
| Samsung Electronics SSD 970 EVO 1TB  | 4         | 5      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 250       | 336    | 26.48%  |
| WDC                 | 202       | 253    | 21.4%   |
| Hitachi             | 95        | 114    | 10.06%  |
| Toshiba             | 72        | 76     | 7.63%   |
| Samsung Electronics | 54        | 59     | 5.72%   |
| Kingston            | 45        | 50     | 4.77%   |
| Fujitsu             | 35        | 36     | 3.71%   |
| Intel               | 33        | 40     | 3.5%    |
| HGST                | 24        | 26     | 2.54%   |
| SK hynix            | 20        | 24     | 2.12%   |
| Crucial             | 16        | 21     | 1.69%   |
| SanDisk             | 15        | 16     | 1.59%   |
| A-DATA Technology   | 15        | 18     | 1.59%   |
| Micron Technology   | 14        | 20     | 1.48%   |
| Maxtor              | 9         | 9      | 0.95%   |
| LITEONIT            | 4         | 5      | 0.42%   |
| LITEON              | 3         | 3      | 0.32%   |
| Hewlett-Packard     | 3         | 5      | 0.32%   |
| China               | 3         | 3      | 0.32%   |
| Transcend           | 2         | 2      | 0.21%   |
| SPCC                | 2         | 2      | 0.21%   |
| ShiJi               | 2         | 2      | 0.21%   |
| PNY                 | 2         | 7      | 0.21%   |
| OCZ                 | 2         | 2      | 0.21%   |
| JMicron Technology  | 2         | 3      | 0.21%   |
| Apple               | 2         | 3      | 0.21%   |
| Apacer              | 2         | 2      | 0.21%   |
| Unknown             | 2         | 2      | 0.21%   |
| Western Digital     | 1         | 2      | 0.11%   |
| USB3.0              | 1         | 1      | 0.11%   |
| Plextor             | 1         | 1      | 0.11%   |
| Patriot             | 1         | 1      | 0.11%   |
| Netac               | 1         | 1      | 0.11%   |
| Lenovo              | 1         | 1      | 0.11%   |
| KingSpec            | 1         | 1      | 0.11%   |
| KingDian            | 1         | 1      | 0.11%   |
| Intenso             | 1         | 1      | 0.11%   |
| IBM/Hitachi         | 1         | 1      | 0.11%   |
| IBM                 | 1         | 1      | 0.11%   |
| GOODRAM             | 1         | 1      | 0.11%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 250       | 336    | 35.11%  |
| WDC                 | 194       | 244    | 27.25%  |
| Hitachi             | 95        | 114    | 13.34%  |
| Toshiba             | 69        | 73     | 9.69%   |
| Fujitsu             | 35        | 36     | 4.92%   |
| Samsung Electronics | 25        | 25     | 3.51%   |
| HGST                | 24        | 26     | 3.37%   |
| Maxtor              | 9         | 9      | 1.26%   |
| Hewlett-Packard     | 3         | 5      | 0.42%   |
| JMicron Technology  | 2         | 3      | 0.28%   |
| Apple               | 2         | 3      | 0.28%   |
| USB3.0              | 1         | 1      | 0.14%   |
| IBM/Hitachi         | 1         | 1      | 0.14%   |
| IBM                 | 1         | 1      | 0.14%   |
| ASMedia             | 1         | 1      | 0.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 681       | 878    | 74.84%  |
| SSD  | 191       | 227    | 20.99%  |
| NVMe | 38        | 49     | 4.18%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 3.85%   |
| WDC WD4001FFSX-68JNUN0 4TB                      | 1         | 1      | 3.85%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1      | 3.85%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 3.85%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 3.85%   |
| Seagate ST500DM005 HD502HJ 500GB                | 1         | 1      | 3.85%   |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 2      | 3.85%   |
| Seagate ST3500830AS 500GB                       | 1         | 1      | 3.85%   |
| Seagate ST3500630A 500GB                        | 1         | 1      | 3.85%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB     | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 980 250GB               | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 980 1TB                 | 1         | 1      | 3.85%   |
| Samsung Electronics SP0802N 80GB                | 1         | 1      | 3.85%   |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 3.85%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 3.85%   |
| Samsung Electronics HD253GJ 250GB               | 1         | 1      | 3.85%   |
| Samsung Electronics HD103SJ 1TB                 | 1         | 1      | 3.85%   |
| KingDian S400 120GB                             | 1         | 1      | 3.85%   |
| Intel SSDSC2KW256G8 256GB                       | 1         | 1      | 3.85%   |
| Inland SATA SSD 128GB                           | 1         | 1      | 3.85%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 3.85%   |
| HGST HUH728080ALN600 8TB                        | 1         | 1      | 3.85%   |
| HGST HTS725050A7E630 500GB                      | 1         | 2      | 3.85%   |
| HGST HDN724040ALE640 4TB                        | 1         | 1      | 3.85%   |
| Hewlett-Packard SSD S700 500GB                  | 1         | 2      | 3.85%   |
| Crucial CT500P2SSD8 500GB                       | 1         | 1      | 3.85%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 30.77%  |
| Seagate             | 6         | 7      | 23.08%  |
| HGST                | 3         | 4      | 11.54%  |
| WDC                 | 2         | 2      | 7.69%   |
| Toshiba             | 1         | 1      | 3.85%   |
| KingDian            | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |
| Inland              | 1         | 1      | 3.85%   |
| Hitachi             | 1         | 2      | 3.85%   |
| Hewlett-Packard     | 1         | 2      | 3.85%   |
| Crucial             | 1         | 1      | 3.85%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 4741      | 8701   | 65.29%  |
| Detected | 1606      | 3113   | 22.12%  |
| Malfunc  | 886       | 1154   | 12.2%   |
| Failed   | 26        | 30     | 0.36%   |
| Limited  | 2         | 2      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3923      | 49.85%  |
| AMD                              | 1008      | 12.81%  |
| Samsung Electronics              | 798       | 10.14%  |
| Nvidia                           | 428       | 5.44%   |
| SanDisk                          | 319       | 4.05%   |
| SK hynix                         | 139       | 1.77%   |
| ASMedia Technology               | 127       | 1.61%   |
| Phison Electronics               | 111       | 1.41%   |
| Kingston Technology Company      | 97        | 1.23%   |
| Apple                            | 86        | 1.09%   |
| Marvell Technology Group         | 79        | 1%      |
| Toshiba America Info Systems     | 72        | 0.91%   |
| JMicron Technology               | 72        | 0.91%   |
| Micron Technology                | 71        | 0.9%    |
| Micron/Crucial Technology        | 68        | 0.86%   |
| LSI Logic / Symbios Logic        | 63        | 0.8%    |
| KIOXIA                           | 63        | 0.8%    |
| Broadcom / LSI                   | 56        | 0.71%   |
| ADATA Technology                 | 52        | 0.66%   |
| Silicon Motion                   | 49        | 0.62%   |
| VIA Technologies                 | 32        | 0.41%   |
| Hewlett-Packard                  | 16        | 0.2%    |
| Solid State Storage Technology   | 15        | 0.19%   |
| Adaptec                          | 15        | 0.19%   |
| Realtek Semiconductor            | 14        | 0.18%   |
| MAXIO Technology (Hangzhou)      | 14        | 0.18%   |
| Union Memory (Shenzhen)          | 9         | 0.11%   |
| Silicon Image                    | 9         | 0.11%   |
| Silicon Integrated Systems [SiS] | 8         | 0.1%    |
| Lite-On Technology               | 7         | 0.09%   |
| Seagate Technology               | 6         | 0.08%   |
| Shenzhen Longsys Electronics     | 5         | 0.06%   |
| Lenovo                           | 4         | 0.05%   |
| INNOGRIT                         | 4         | 0.05%   |
| Yangtze Memory Technologies      | 3         | 0.04%   |
| ULi Electronics                  | 3         | 0.04%   |
| Jiangsu Huacun Elec.             | 3         | 0.04%   |
| Biwin Storage Technology         | 3         | 0.04%   |
| 3ware                            | 3         | 0.04%   |
| Integrated Technology Express    | 2         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 690       | 7.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 417       | 4.62%   |
| Nvidia MCP79 AHCI Controller                                                            | 366       | 4.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 292       | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 263       | 2.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 219       | 2.42%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 177       | 1.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 155       | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 154       | 1.7%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 150       | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 147       | 1.63%   |
| AMD 400 Series Chipset SATA Controller                                                  | 146       | 1.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 145       | 1.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 135       | 1.49%   |
| Samsung NVMe SSD Controller 980                                                         | 133       | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 122       | 1.35%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 116       | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 115       | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 113       | 1.25%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 102       | 1.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 99        | 1.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 99        | 1.1%    |
| AMD 500 Series Chipset SATA Controller                                                  | 95        | 1.05%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 92        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 85        | 0.94%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                              | 84        | 0.93%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 83        | 0.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 80        | 0.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 80        | 0.89%   |
| Apple S1X NVMe Controller                                                               | 79        | 0.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 76        | 0.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 76        | 0.84%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 74        | 0.82%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 70        | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 69        | 0.76%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 65        | 0.72%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 63        | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 63        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 63        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 63        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4601      | 57.35%  |
| NVMe | 1938      | 24.16%  |
| IDE  | 894       | 11.14%  |
| RAID | 477       | 5.95%   |
| SAS  | 91        | 1.13%   |
| SCSI | 21        | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5132      | 77.92%  |
| AMD                   | 1219      | 18.51%  |
| ARM                   | 216       | 3.28%   |
| CentaurHauls          | 7         | 0.11%   |
| Phytium               | 4         | 0.06%   |
| sifive,u74-mc         | 3         | 0.05%   |
| Unknown               | 2         | 0.03%   |
| Qualcomm              | 1         | 0.02%   |
| Marvell Semiconductor | 1         | 0.02%   |
| HISILICON             | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 355       | 5.38%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 181       | 2.74%   |
| ARM Processor                                 | 180       | 2.73%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 148       | 2.24%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 92        | 1.39%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 75        | 1.14%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 63        | 0.96%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 60        | 0.91%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 59        | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 49        | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 49        | 0.74%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 47        | 0.71%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 45        | 0.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 41        | 0.62%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 40        | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 38        | 0.58%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 0.55%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 35        | 0.53%   |
| Intel Celeron N5105 @ 2.00GHz                 | 35        | 0.53%   |
| AMD Ryzen 5 3600 6-Core Processor             | 34        | 0.52%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 31        | 0.47%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 31        | 0.47%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 30        | 0.45%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 30        | 0.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 29        | 0.44%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 29        | 0.44%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 28        | 0.42%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 28        | 0.42%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 28        | 0.42%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 28        | 0.42%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 27        | 0.41%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 27        | 0.41%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 27        | 0.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 26        | 0.39%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 26        | 0.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 26        | 0.39%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 25        | 0.38%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 25        | 0.38%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 24        | 0.36%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 24        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1298      | 19.7%   |
| Intel Core i7           | 778       | 11.81%  |
| Other                   | 734       | 11.14%  |
| Intel Core 2 Duo        | 588       | 8.92%   |
| Intel Celeron           | 484       | 7.35%   |
| Intel Core i3           | 479       | 7.27%   |
| AMD Ryzen 5             | 305       | 4.63%   |
| Intel Xeon              | 250       | 3.79%   |
| Intel Pentium           | 230       | 3.49%   |
| AMD Ryzen 7             | 210       | 3.19%   |
| Intel Atom              | 130       | 1.97%   |
| AMD Ryzen 9             | 98        | 1.49%   |
| Intel Core 2            | 77        | 1.17%   |
| Intel Pentium Dual-Core | 74        | 1.12%   |
| AMD FX                  | 69        | 1.05%   |
| AMD Ryzen 3             | 50        | 0.76%   |
| Intel Core 2 Quad       | 37        | 0.56%   |
| AMD A6                  | 37        | 0.56%   |
| AMD Ryzen 7 PRO         | 32        | 0.49%   |
| AMD A10                 | 31        | 0.47%   |
| Intel Core i9           | 30        | 0.46%   |
| AMD Ryzen Threadripper  | 25        | 0.38%   |
| AMD A4                  | 25        | 0.38%   |
| Intel Genuine           | 24        | 0.36%   |
| AMD Ryzen 5 PRO         | 24        | 0.36%   |
| AMD Athlon              | 23        | 0.35%   |
| Intel Pentium M         | 22        | 0.33%   |
| Intel Pentium Gold      | 22        | 0.33%   |
| Intel Pentium 4         | 22        | 0.33%   |
| Intel Pentium Silver    | 21        | 0.32%   |
| AMD A8                  | 20        | 0.3%    |
| Intel Pentium Dual      | 19        | 0.29%   |
| AMD Athlon II X2        | 18        | 0.27%   |
| ARM Allwinner           | 17        | 0.26%   |
| AMD Phenom II X4        | 17        | 0.26%   |
| AMD Athlon 64 X2        | 17        | 0.26%   |
| AMD GX                  | 15        | 0.23%   |
| AMD G                   | 12        | 0.18%   |
| AMD E                   | 12        | 0.18%   |
| AMD Phenom II X6        | 11        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2824      | 42.83%  |
| 4       | 2200      | 33.37%  |
| 6       | 572       | 8.68%   |
| 8       | 438       | 6.64%   |
| 1       | 215       | 3.26%   |
| 12      | 94        | 1.43%   |
| 16      | 85        | 1.29%   |
| 10      | 43        | 0.65%   |
| 3       | 26        | 0.39%   |
| 24      | 18        | 0.27%   |
| 14      | 17        | 0.26%   |
| Unknown | 17        | 0.26%   |
| 32      | 16        | 0.24%   |
| 20      | 6         | 0.09%   |
| 28      | 5         | 0.08%   |
| 18      | 4         | 0.06%   |
| 48      | 3         | 0.05%   |
| 44      | 2         | 0.03%   |
| 36      | 2         | 0.03%   |
| 192     | 1         | 0.02%   |
| 96      | 1         | 0.02%   |
| 80      | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 56      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6435      | 97.66%  |
| 2       | 127       | 1.93%   |
| Unknown | 17        | 0.26%   |
| 3       | 5         | 0.08%   |
| 4       | 3         | 0.05%   |
| 8       | 1         | 0.02%   |
| 0       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3763      | 57.08%  |
| 1       | 2811      | 42.64%  |
| Unknown | 17        | 0.26%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6403      | 97.19%  |
| 32-bit         | 116       | 1.76%   |
| Unknown        | 50        | 0.76%   |
| 64-bit         | 19        | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1266      | 18.9%   |
| 0x1067a    | 553       | 8.26%   |
| 0x306a9    | 298       | 4.45%   |
| 0x306c3    | 288       | 4.3%    |
| 0x206a7    | 279       | 4.17%   |
| 0x806c1    | 274       | 4.09%   |
| 0x306d4    | 224       | 3.34%   |
| 0x906ea    | 158       | 2.36%   |
| 0x506e3    | 141       | 2.11%   |
| 0x806ec    | 131       | 1.96%   |
| 0x806e9    | 123       | 1.84%   |
| 0x30678    | 120       | 1.79%   |
| 0x806ea    | 100       | 1.49%   |
| 0x406e3    | 93        | 1.39%   |
| 0x40651    | 87        | 1.3%    |
| 0x406c4    | 83        | 1.24%   |
| 0x08108109 | 83        | 1.24%   |
| 0xa0653    | 79        | 1.18%   |
| 0x906e9    | 79        | 1.18%   |
| 0x6f6      | 72        | 1.07%   |
| 0x906c0    | 70        | 1.05%   |
| 0x08701021 | 67        | 1%      |
| 0x0a50000c | 63        | 0.94%   |
| 0x906eb    | 62        | 0.93%   |
| 0x20655    | 59        | 0.88%   |
| 0x08600106 | 59        | 0.88%   |
| 0xa0652    | 57        | 0.85%   |
| 0x10676    | 54        | 0.81%   |
| 0x706a8    | 53        | 0.79%   |
| 0x506c9    | 49        | 0.73%   |
| 0x6fd      | 48        | 0.72%   |
| 0x0a201016 | 42        | 0.63%   |
| 0xa0655    | 40        | 0.6%    |
| 0x706e5    | 40        | 0.6%    |
| 0x08608103 | 40        | 0.6%    |
| 0x0600611a | 39        | 0.58%   |
| 0xa0671    | 38        | 0.57%   |
| 0x106c2    | 35        | 0.52%   |
| 0x0800820d | 35        | 0.52%   |
| 0x306f2    | 32        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 864       | 13.1%   |
| Penryn           | 642       | 9.73%   |
| Haswell          | 507       | 7.69%   |
| Unknown          | 418       | 6.34%   |
| IvyBridge        | 391       | 5.93%   |
| SandyBridge      | 382       | 5.79%   |
| TigerLake        | 318       | 4.82%   |
| Skylake          | 311       | 4.71%   |
| Broadwell        | 265       | 4.02%   |
| Silvermont       | 259       | 3.93%   |
| Zen 2            | 221       | 3.35%   |
| CometLake        | 211       | 3.2%    |
| Zen 3            | 210       | 3.18%   |
| Zen+             | 192       | 2.91%   |
| Core             | 191       | 2.9%    |
| Westmere         | 137       | 2.08%   |
| Excavator        | 92        | 1.39%   |
| Zen              | 88        | 1.33%   |
| Goldmont plus    | 87        | 1.32%   |
| K10              | 81        | 1.23%   |
| IceLake          | 79        | 1.2%    |
| Tremont          | 77        | 1.17%   |
| Piledriver       | 77        | 1.17%   |
| Bonnell          | 74        | 1.12%   |
| Goldmont         | 58        | 0.88%   |
| P6               | 55        | 0.83%   |
| Nehalem          | 41        | 0.62%   |
| Alderlake Hybrid | 41        | 0.62%   |
| NetBurst         | 40        | 0.61%   |
| Bobcat           | 38        | 0.58%   |
| K8 Hammer        | 35        | 0.53%   |
| Puma             | 30        | 0.45%   |
| Steamroller      | 23        | 0.35%   |
| Jaguar           | 23        | 0.35%   |
| Bulldozer        | 18        | 0.27%   |
| K10 Llano        | 11        | 0.17%   |
| K8 & K10 hybrid  | 4         | 0.06%   |
| K6               | 4         | 0.06%   |
| Gracemont        | 1         | 0.02%   |
| Geode            | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3845      | 53.73%  |
| Nvidia                                       | 1816      | 25.38%  |
| AMD                                          | 1288      | 18%     |
| ASPEED Technology                            | 96        | 1.34%   |
| Matrox Electronics Systems                   | 92        | 1.29%   |
| VIA Technologies                             | 7         | 0.1%    |
| Silicon Integrated Systems [SiS]             | 6         | 0.08%   |
| Zhaoxin                                      | 3         | 0.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| S3 Graphics                                  | 1         | 0.01%   |
| ATI Technologies                             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 353       | 4.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 293       | 3.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 260       | 3.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 198       | 2.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 165       | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 158       | 2.13%   |
| Intel HD Graphics 6000                                                                   | 155       | 2.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 146       | 1.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 134       | 1.81%   |
| Intel HD Graphics 620                                                                    | 121       | 1.63%   |
| Intel UHD Graphics 620                                                                   | 116       | 1.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 111       | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 108       | 1.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 106       | 1.43%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 104       | 1.4%    |
| AMD Renoir                                                                               | 104       | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 97        | 1.31%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 96        | 1.3%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 96        | 1.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 88        | 1.19%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 84        | 1.13%   |
| Intel HD Graphics 530                                                                    | 83        | 1.12%   |
| Intel HD Graphics 5500                                                                   | 80        | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 79        | 1.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 75        | 1.01%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 75        | 1.01%   |
| Intel JasperLake [UHD Graphics]                                                          | 73        | 0.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 71        | 0.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 70        | 0.95%   |
| Intel HD Graphics 630                                                                    | 66        | 0.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 66        | 0.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 59        | 0.8%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 59        | 0.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 57        | 0.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 57        | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 56        | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 56        | 0.76%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 54        | 0.73%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 52        | 0.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 52        | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 3155      | 47.74%  |
| 1 x Nvidia                        | 1185      | 17.93%  |
| 1 x AMD                           | 1044      | 15.8%   |
| Intel + Nvidia                    | 521       | 7.88%   |
| Other                             | 250       | 3.78%   |
| Intel + AMD                       | 95        | 1.44%   |
| 1 x Matrox                        | 88        | 1.33%   |
| AMD + Nvidia                      | 81        | 1.23%   |
| 1 x ASPEED                        | 73        | 1.1%    |
| 2 x AMD                           | 58        | 0.88%   |
| Nvidia + ASPEED                   | 12        | 0.18%   |
| AMD + ASPEED                      | 8         | 0.12%   |
| 2 x Nvidia                        | 7         | 0.11%   |
| 1 x VIA                           | 7         | 0.11%   |
| 1 x SiS                           | 6         | 0.09%   |
| 2 x Intel                         | 3         | 0.05%   |
| 1 x Zhaoxin                       | 3         | 0.05%   |
| Nvidia + Matrox                   | 3         | 0.05%   |
| Intel + 2 x Nvidia                | 3         | 0.05%   |
| 2 x Nvidia + 1 x ASPEED           | 2         | 0.03%   |
| 3 x AMD                           | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.02%   |
| 1 x S3 Graphics                   | 1         | 0.02%   |
| Nvidia + XGI                      | 1         | 0.02%   |
| AMD + Matrox                      | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4696      | 70.85%  |
| Unknown     | 1399      | 21.11%  |
| Proprietary | 533       | 8.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 4773      | 71.73%  |
| 0.01-0.5       | 795       | 11.95%  |
| 1.01-2.0       | 353       | 5.31%   |
| 3.01-4.0       | 229       | 3.44%   |
| 0.51-1.0       | 227       | 3.41%   |
| 7.01-8.0       | 126       | 1.89%   |
| 5.01-6.0       | 77        | 1.16%   |
| 8.01-16.0      | 33        | 0.5%    |
| 2.01-3.0       | 26        | 0.39%   |
| 16.01-24.0     | 7         | 0.11%   |
| 4.01-5.0       | 5         | 0.08%   |
| More than 64.0 | 1         | 0.02%   |
| 32.01-64.0     | 1         | 0.02%   |
| 24.01-32.0     | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 688       | 12%     |
| Apple                   | 658       | 11.47%  |
| Samsung Electronics     | 549       | 9.57%   |
| BOE                     | 476       | 8.3%    |
| LG Display              | 417       | 7.27%   |
| Chimei Innolux          | 403       | 7.03%   |
| Dell                    | 302       | 5.27%   |
| Goldstar                | 246       | 4.29%   |
| Hewlett-Packard         | 164       | 2.86%   |
| Acer                    | 147       | 2.56%   |
| BenQ                    | 134       | 2.34%   |
| AOC                     | 119       | 2.07%   |
| Lenovo                  | 118       | 2.06%   |
| Philips                 | 110       | 1.92%   |
| Ancor Communications    | 106       | 1.85%   |
| Sharp                   | 76        | 1.33%   |
| Unknown                 | 68        | 1.19%   |
| ViewSonic               | 67        | 1.17%   |
| Iiyama                  | 65        | 1.13%   |
| Chi Mei Optoelectronics | 64        | 1.12%   |
| InfoVision              | 57        | 0.99%   |
| Eizo                    | 40        | 0.7%    |
| PANDA                   | 38        | 0.66%   |
| ASUSTek Computer        | 36        | 0.63%   |
| HannStar                | 33        | 0.58%   |
| NEC Computers           | 32        | 0.56%   |
| Sony                    | 30        | 0.52%   |
| LG Philips              | 22        | 0.38%   |
| LG Electronics          | 22        | 0.38%   |
| MSI                     | 17        | 0.3%    |
| CSO                     | 17        | 0.3%    |
| Unknown                 | 16        | 0.28%   |
| Panasonic               | 15        | 0.26%   |
| Vestel Elektronik       | 14        | 0.24%   |
| Vizio                   | 11        | 0.19%   |
| Toshiba                 | 11        | 0.19%   |
| Medion                  | 10        | 0.17%   |
| Fujitsu Siemens         | 9         | 0.16%   |
| CPT                     | 8         | 0.14%   |
| AGO                     | 8         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 209       | 3.56%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 187       | 3.19%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch       | 112       | 1.91%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 54        | 0.92%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 53        | 0.9%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 42        | 0.72%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 41        | 0.7%    |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 41        | 0.7%    |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 38        | 0.65%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 28        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 26        | 0.44%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 25        | 0.43%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 25        | 0.43%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 22        | 0.37%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 22        | 0.37%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 21        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 20        | 0.34%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch               | 18        | 0.31%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 18        | 0.31%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 18        | 0.31%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 16        | 0.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 16        | 0.27%   |
| Unknown                                                              | 16        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 15        | 0.26%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 14        | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 14        | 0.24%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                     | 13        | 0.22%   |
| BenQ GW2470 BNQ78E4 1920x1080 530x300mm 24.0-inch                    | 13        | 0.22%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 13        | 0.22%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 12        | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 11        | 0.19%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                 | 11        | 0.19%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 10        | 0.17%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 10        | 0.17%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 10        | 0.17%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 10        | 0.17%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 10        | 0.17%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 10        | 0.17%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 10        | 0.17%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 10        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2211      | 40.14%  |
| 1366x768 (WXGA)    | 969       | 17.59%  |
| 1280x800 (WXGA)    | 527       | 9.57%   |
| 3840x2160 (4K)     | 291       | 5.28%   |
| 1280x1024 (SXGA)   | 210       | 3.81%   |
| 2560x1440 (QHD)    | 203       | 3.69%   |
| 1600x900 (HD+)     | 174       | 3.16%   |
| 1440x900 (WXGA+)   | 162       | 2.94%   |
| 1920x1200 (WUXGA)  | 118       | 2.14%   |
| 1680x1050 (WSXGA+) | 109       | 1.98%   |
| Unknown            | 62        | 1.13%   |
| 2288x1287          | 55        | 1%      |
| 1024x600           | 49        | 0.89%   |
| 1024x768 (XGA)     | 42        | 0.76%   |
| 3440x1440          | 38        | 0.69%   |
| 2560x1080          | 37        | 0.67%   |
| 1360x768           | 35        | 0.64%   |
| 2560x1600          | 27        | 0.49%   |
| 3840x1080          | 22        | 0.4%    |
| 1600x1200          | 22        | 0.4%    |
| 1920x540           | 14        | 0.25%   |
| 3840x2400          | 13        | 0.24%   |
| 2880x1800          | 10        | 0.18%   |
| 2160x1440          | 9         | 0.16%   |
| 1400x1050          | 7         | 0.13%   |
| 2736x1824          | 6         | 0.11%   |
| 1920x1280          | 6         | 0.11%   |
| 4480x1440          | 5         | 0.09%   |
| 5760x1080          | 4         | 0.07%   |
| 3840x1200          | 4         | 0.07%   |
| 3200x1080          | 4         | 0.07%   |
| 2048x1152          | 4         | 0.07%   |
| 1280x720 (HD)      | 4         | 0.07%   |
| 3840x1600          | 3         | 0.05%   |
| 3200x1800 (QHD+)   | 3         | 0.05%   |
| 1800x1200          | 3         | 0.05%   |
| 1024x576           | 3         | 0.05%   |
| 5760x2160          | 2         | 0.04%   |
| 5360x1440          | 2         | 0.04%   |
| 3840x1100          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 1092      | 19.2%   |
| 15      | 1063      | 18.69%  |
| 14      | 426       | 7.49%   |
| 24      | 398       | 7%      |
| 27      | 330       | 5.8%    |
| 23      | 322       | 5.66%   |
| 17      | 275       | 4.83%   |
| 21      | 261       | 4.59%   |
| 11      | 261       | 4.59%   |
| Unknown | 188       | 3.31%   |
| 19      | 141       | 2.48%   |
| 12      | 130       | 2.29%   |
| 18      | 109       | 1.92%   |
| 31      | 98        | 1.72%   |
| 22      | 71        | 1.25%   |
| 20      | 70        | 1.23%   |
| 10      | 56        | 0.98%   |
| 34      | 54        | 0.95%   |
| 142     | 53        | 0.93%   |
| 84      | 34        | 0.6%    |
| 32      | 27        | 0.47%   |
| 16      | 26        | 0.46%   |
| 72      | 23        | 0.4%    |
| 25      | 22        | 0.39%   |
| 54      | 19        | 0.33%   |
| 40      | 15        | 0.26%   |
| 28      | 15        | 0.26%   |
| 29      | 12        | 0.21%   |
| 26      | 12        | 0.21%   |
| 65      | 9         | 0.16%   |
| 52      | 7         | 0.12%   |
| 48      | 6         | 0.11%   |
| 43      | 6         | 0.11%   |
| 33      | 6         | 0.11%   |
| 46      | 5         | 0.09%   |
| 42      | 5         | 0.09%   |
| 49      | 4         | 0.07%   |
| 47      | 4         | 0.07%   |
| 35      | 4         | 0.07%   |
| 8       | 4         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1844      | 32.94%  |
| 201-300        | 1277      | 22.81%  |
| 501-600        | 968       | 17.29%  |
| 401-500        | 551       | 9.84%   |
| 351-400        | 296       | 5.29%   |
| Unknown        | 188       | 3.36%   |
| 601-700        | 168       | 3%      |
| 701-800        | 88        | 1.57%   |
| 1001-1500      | 63        | 1.13%   |
| 1501-2000      | 61        | 1.09%   |
| More than 2000 | 54        | 0.96%   |
| 801-900        | 26        | 0.46%   |
| 901-1000       | 9         | 0.16%   |
| 101-200        | 5         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3602      | 68.94%  |
| 16/10   | 983       | 18.81%  |
| 5/4     | 195       | 3.73%   |
| Unknown | 154       | 2.95%   |
| 4/3     | 85        | 1.63%   |
| 21/9    | 68        | 1.3%    |
| 1.00    | 55        | 1.05%   |
| 3/2     | 48        | 0.92%   |
| 6/5     | 13        | 0.25%   |
| 32/9    | 5         | 0.1%    |
| 2.65    | 5         | 0.1%    |
| 3.40    | 2         | 0.04%   |
| 3.20    | 2         | 0.04%   |
| 1.96    | 2         | 0.04%   |
| 0.56    | 2         | 0.04%   |
| 3.73    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 11/10   | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 1167      | 20.7%   |
| 101-110        | 1054      | 18.69%  |
| 201-250        | 829       | 14.7%   |
| 71-80          | 353       | 6.26%   |
| 301-350        | 339       | 6.01%   |
| 151-200        | 294       | 5.21%   |
| 51-60          | 264       | 4.68%   |
| 351-500        | 206       | 3.65%   |
| 141-150        | 192       | 3.41%   |
| Unknown        | 188       | 3.33%   |
| More than 1000 | 163       | 2.89%   |
| 251-300        | 152       | 2.7%    |
| 121-130        | 144       | 2.55%   |
| 61-70          | 118       | 2.09%   |
| 41-50          | 55        | 0.98%   |
| 501-1000       | 47        | 0.83%   |
| 131-140        | 31        | 0.55%   |
| 111-120        | 24        | 0.43%   |
| 91-100         | 13        | 0.23%   |
| 1-40           | 5         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1592      | 28.9%   |
| 121-160       | 1583      | 28.73%  |
| 101-120       | 1551      | 28.15%  |
| 161-240       | 381       | 6.92%   |
| Unknown       | 188       | 3.41%   |
| 1-50          | 144       | 2.61%   |
| More than 240 | 70        | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4360      | 65.17%  |
| 0     | 1494      | 22.33%  |
| 2     | 750       | 11.21%  |
| 3     | 83        | 1.24%   |
| 4     | 2         | 0.03%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3081      | 32.28%  |
| Intel                             | 2961      | 31.02%  |
| Qualcomm Atheros                  | 833       | 8.73%   |
| Broadcom                          | 806       | 8.45%   |
| Nvidia                            | 416       | 4.36%   |
| Broadcom Limited                  | 269       | 2.82%   |
| Marvell Technology Group          | 141       | 1.48%   |
| MediaTek                          | 100       | 1.05%   |
| Ralink Technology                 | 80        | 0.84%   |
| TP-Link                           | 75        | 0.79%   |
| ASIX Electronics                  | 61        | 0.64%   |
| Ralink                            | 57        | 0.6%    |
| Samsung Electronics               | 45        | 0.47%   |
| Dell                              | 30        | 0.31%   |
| Sierra Wireless                   | 29        | 0.3%    |
| Microchip Technology              | 29        | 0.3%    |
| Xiaomi                            | 26        | 0.27%   |
| Mellanox Technologies             | 26        | 0.27%   |
| Qualcomm Atheros Communications   | 22        | 0.23%   |
| Qualcomm                          | 21        | 0.22%   |
| Huawei Technologies               | 21        | 0.22%   |
| Aquantia                          | 19        | 0.2%    |
| DisplayLink                       | 18        | 0.19%   |
| NetGear                           | 17        | 0.18%   |
| Lenovo                            | 16        | 0.17%   |
| American Megatrends               | 16        | 0.17%   |
| D-Link System                     | 15        | 0.16%   |
| D-Link                            | 14        | 0.15%   |
| JMicron Technology                | 13        | 0.14%   |
| Ericsson Business Mobile Networks | 13        | 0.14%   |
| ASUSTek Computer                  | 13        | 0.14%   |
| Microsoft                         | 12        | 0.13%   |
| Hewlett-Packard                   | 12        | 0.13%   |
| Edimax Technology                 | 12        | 0.13%   |
| Dresden Elektronik                | 12        | 0.13%   |
| VIA Technologies                  | 10        | 0.1%    |
| OPPO Electronics                  | 10        | 0.1%    |
| ICS Advent                        | 10        | 0.1%    |
| Sigma Designs                     | 9         | 0.09%   |
| Standard Microsystems             | 7         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 2167      | 19.42%  |
| Nvidia MCP79 Ethernet                                                                 | 367       | 3.29%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 362       | 3.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 308       | 2.76%   |
| Intel Wi-Fi 6 AX201                                                                   | 261       | 2.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 211       | 1.89%   |
| Intel Wi-Fi 6 AX200                                                                   | 198       | 1.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 172       | 1.54%   |
| Intel Wireless 7260                                                                   | 169       | 1.51%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 165       | 1.48%   |
| Intel Wireless 8265 / 8275                                                            | 161       | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 159       | 1.43%   |
| Intel Wireless 7265                                                                   | 152       | 1.36%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 137       | 1.23%   |
| Intel Ethernet Connection (13) I219-V                                                 | 136       | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 108       | 0.97%   |
| Intel I211 Gigabit Network Connection                                                 | 94        | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 92        | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 91        | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 90        | 0.81%   |
| Intel Wireless 8260                                                                   | 89        | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 86        | 0.77%   |
| Intel Wireless 3165                                                                   | 85        | 0.76%   |
| Intel Ethernet Controller I225-V                                                      | 85        | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 83        | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 82        | 0.73%   |
| Intel I210 Gigabit Network Connection                                                 | 81        | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 78        | 0.7%    |
| Intel Ethernet Connection I217-LM                                                     | 76        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 70        | 0.63%   |
| Intel Ethernet Connection (2) I219-V                                                  | 61        | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 61        | 0.55%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 59        | 0.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 57        | 0.51%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                                  | 55        | 0.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 52        | 0.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 51        | 0.46%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 51        | 0.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 50        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2086      | 44.91%  |
| Qualcomm Atheros                      | 677       | 14.57%  |
| Realtek Semiconductor                 | 610       | 13.13%  |
| Broadcom                              | 581       | 12.51%  |
| Broadcom Limited                      | 213       | 4.59%   |
| MediaTek                              | 92        | 1.98%   |
| Ralink Technology                     | 80        | 1.72%   |
| Ralink                                | 57        | 1.23%   |
| TP-Link                               | 55        | 1.18%   |
| Sierra Wireless                       | 29        | 0.62%   |
| Qualcomm Atheros Communications       | 22        | 0.47%   |
| Dell                                  | 18        | 0.39%   |
| NetGear                               | 17        | 0.37%   |
| ASUSTek Computer                      | 13        | 0.28%   |
| Edimax Technology                     | 12        | 0.26%   |
| D-Link                                | 11        | 0.24%   |
| Qualcomm                              | 8         | 0.17%   |
| Microsoft                             | 8         | 0.17%   |
| D-Link System                         | 8         | 0.17%   |
| Marvell Technology Group              | 7         | 0.15%   |
| Fibocom                               | 7         | 0.15%   |
| Belkin Components                     | 7         | 0.15%   |
| Gemtek                                | 4         | 0.09%   |
| IMC Networks                          | 3         | 0.06%   |
| Ericsson Business Mobile Networks     | 3         | 0.06%   |
| AVM                                   | 3         | 0.06%   |
| Wilocity                              | 2         | 0.04%   |
| Linksys                               | 2         | 0.04%   |
| Z-Com                                 | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Hewlett-Packard                       | 1         | 0.02%   |
| Encore Electronics                    | 1         | 0.02%   |
| CyberTAN Technology                   | 1         | 0.02%   |
| BUFFALO                               | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |
| 3Com                                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 362       | 7.76%   |
| Intel Wi-Fi 6 AX201                                                                   | 261       | 5.6%    |
| Intel Wi-Fi 6 AX200                                                                   | 198       | 4.25%   |
| Intel Wireless 7260                                                                   | 169       | 3.62%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 165       | 3.54%   |
| Intel Wireless 8265 / 8275                                                            | 161       | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 159       | 3.41%   |
| Intel Wireless 7265                                                                   | 152       | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 108       | 2.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 92        | 1.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 91        | 1.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 90        | 1.93%   |
| Intel Wireless 8260                                                                   | 89        | 1.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 86        | 1.84%   |
| Intel Wireless 3165                                                                   | 85        | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 83        | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 82        | 1.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 78        | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 70        | 1.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 61        | 1.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 57        | 1.22%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 52        | 1.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 51        | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 51        | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 50        | 1.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 46        | 0.99%   |
| Intel Wireless-AC 9260                                                                | 42        | 0.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 40        | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 40        | 0.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 39        | 0.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 35        | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 35        | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 35        | 0.75%   |
| Realtek 802.11ac NIC                                                                  | 30        | 0.64%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 30        | 0.64%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 29        | 0.62%   |
| Intel Wireless 3160                                                                   | 28        | 0.6%    |
| Intel Centrino Ultimate-N 6300                                                        | 27        | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 26        | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2836      | 46.28%  |
| Intel                            | 1740      | 28.39%  |
| Nvidia                           | 416       | 6.79%   |
| Broadcom                         | 271       | 4.42%   |
| Qualcomm Atheros                 | 233       | 3.8%    |
| Marvell Technology Group         | 135       | 2.2%    |
| ASIX Electronics                 | 61        | 1%      |
| Broadcom Limited                 | 59        | 0.96%   |
| Samsung Electronics              | 30        | 0.49%   |
| Microchip Technology             | 29        | 0.47%   |
| Xiaomi                           | 26        | 0.42%   |
| Mellanox Technologies            | 23        | 0.38%   |
| TP-Link                          | 20        | 0.33%   |
| Aquantia                         | 19        | 0.31%   |
| DisplayLink                      | 18        | 0.29%   |
| Lenovo                           | 16        | 0.26%   |
| American Megatrends              | 16        | 0.26%   |
| JMicron Technology               | 13        | 0.21%   |
| Huawei Technologies              | 13        | 0.21%   |
| Qualcomm                         | 12        | 0.2%    |
| VIA Technologies                 | 10        | 0.16%   |
| OPPO Electronics                 | 10        | 0.16%   |
| ICS Advent                       | 10        | 0.16%   |
| Standard Microsystems            | 7         | 0.11%   |
| Silicon Integrated Systems [SiS] | 7         | 0.11%   |
| MediaTek                         | 7         | 0.11%   |
| D-Link System                    | 7         | 0.11%   |
| Cypress Semiconductor            | 6         | 0.1%    |
| Motorola PCS                     | 5         | 0.08%   |
| IBM                              | 5         | 0.08%   |
| 3Com                             | 5         | 0.08%   |
| ZTE WCDMA Technologies MSM       | 4         | 0.07%   |
| NetXen Incorporated              | 4         | 0.07%   |
| Hewlett-Packard                  | 4         | 0.07%   |
| Emulex                           | 4         | 0.07%   |
| Attansic Technology              | 4         | 0.07%   |
| QLogic                           | 3         | 0.05%   |
| Microsoft                        | 3         | 0.05%   |
| Dell                             | 3         | 0.05%   |
| D-Link                           | 3         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2167      | 34.22%  |
| Nvidia MCP79 Ethernet                                             | 367       | 5.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 308       | 4.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 211       | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 172       | 2.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 137       | 2.16%   |
| Intel Ethernet Connection (13) I219-V                             | 136       | 2.15%   |
| Intel I211 Gigabit Network Connection                             | 94        | 1.48%   |
| Intel Ethernet Controller I225-V                                  | 85        | 1.34%   |
| Intel I210 Gigabit Network Connection                             | 81        | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 76        | 1.2%    |
| Intel Ethernet Connection (2) I219-V                              | 61        | 0.96%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 59        | 0.93%   |
| Intel Ethernet Connection (4) I219-V                              | 55        | 0.87%   |
| ASIX AX88179 Gigabit Ethernet                                     | 49        | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 48        | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 47        | 0.74%   |
| Intel 82574L Gigabit Network Connection                           | 47        | 0.74%   |
| Intel I350 Gigabit Network Connection                             | 44        | 0.69%   |
| Intel Ethernet Connection I219-LM                                 | 44        | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 44        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 42        | 0.66%   |
| Intel Ethernet Connection (6) I219-V                              | 40        | 0.63%   |
| Intel Ethernet Connection (14) I219-V                             | 40        | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 37        | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 37        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 36        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 32        | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 30        | 0.47%   |
| Intel Ethernet Connection (10) I219-V                             | 30        | 0.47%   |
| Nvidia MCP61 Ethernet                                             | 29        | 0.46%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 29        | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 28        | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 28        | 0.44%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 28        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 27        | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.41%   |
| Intel 82577LM Gigabit Network Connection                          | 26        | 0.41%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 25        | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                             | 25        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5689      | 55.33%  |
| WiFi     | 4435      | 43.13%  |
| Modem    | 144       | 1.4%    |
| Unknown  | 14        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3472      | 53.32%  |
| WiFi     | 3039      | 46.67%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3384      | 51.24%  |
| 1     | 2588      | 39.19%  |
| 0     | 278       | 4.21%   |
| 3     | 196       | 2.97%   |
| 4     | 81        | 1.23%   |
| 6     | 23        | 0.35%   |
| 5     | 22        | 0.33%   |
| 8     | 12        | 0.18%   |
| 7     | 8         | 0.12%   |
| 9     | 3         | 0.05%   |
| 20    | 2         | 0.03%   |
| 12    | 2         | 0.03%   |
| 17    | 1         | 0.02%   |
| 16    | 1         | 0.02%   |
| 14    | 1         | 0.02%   |
| 13    | 1         | 0.02%   |
| 11    | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5396      | 81.3%   |
| Yes  | 1241      | 18.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1694      | 45.33%  |
| Apple                           | 669       | 17.9%   |
| Realtek Semiconductor           | 297       | 7.95%   |
| Qualcomm Atheros Communications | 236       | 6.32%   |
| Cambridge Silicon Radio         | 176       | 4.71%   |
| Broadcom                        | 142       | 3.8%    |
| IMC Networks                    | 123       | 3.29%   |
| Lite-On Technology              | 107       | 2.86%   |
| Foxconn / Hon Hai               | 69        | 1.85%   |
| ASUSTek Computer                | 44        | 1.18%   |
| Dell                            | 39        | 1.04%   |
| Hewlett-Packard                 | 28        | 0.75%   |
| MediaTek                        | 26        | 0.7%    |
| Toshiba                         | 17        | 0.45%   |
| Realtek                         | 16        | 0.43%   |
| Ralink                          | 11        | 0.29%   |
| Ralink Technology               | 6         | 0.16%   |
| TP-Link                         | 4         | 0.11%   |
| Foxconn International           | 4         | 0.11%   |
| Taiyo Yuden                     | 3         | 0.08%   |
| Fujitsu                         | 3         | 0.08%   |
| Belkin Components               | 3         | 0.08%   |
| Alps Electric                   | 3         | 0.08%   |
| Marvell Semiconductor           | 2         | 0.05%   |
| Edimax Technology               | 2         | 0.05%   |
| Unknown                         | 2         | 0.05%   |
| USI                             | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Microsoft                       | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 647       | 17.3%   |
| Intel AX201 Bluetooth                               | 420       | 11.23%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 364       | 9.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 223       | 5.96%   |
| Realtek Bluetooth Radio                             | 196       | 5.24%   |
| Intel AX200 Bluetooth                               | 190       | 5.08%   |
| Apple Bluetooth USB Host Controller                 | 181       | 4.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 176       | 4.71%   |
| Qualcomm Atheros  Bluetooth Device                  | 144       | 3.85%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 2.03%   |
| Realtek  Bluetooth 4.2 Adapter                      | 66        | 1.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 50        | 1.34%   |
| Intel Bluetooth Device                              | 40        | 1.07%   |
| Intel AX210 Bluetooth                               | 40        | 1.07%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 39        | 1.04%   |
| Apple Bluetooth Host Controller                     | 38        | 1.02%   |
| IMC Networks Bluetooth Radio                        | 37        | 0.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 36        | 0.96%   |
| IMC Networks Bluetooth Device                       | 31        | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 30        | 0.8%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 30        | 0.8%    |
| Lite-On Bluetooth Device                            | 28        | 0.75%   |
| MediaTek Wireless_Device                            | 25        | 0.67%   |
| IMC Networks Wireless_Device                        | 24        | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.64%   |
| Foxconn / Hon Hai Bluetooth Device                  | 22        | 0.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 0.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 0.53%   |
| Realtek RTL8723B Bluetooth                          | 19        | 0.51%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.51%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 0.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 18        | 0.48%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 17        | 0.45%   |
| Dell BCM20702A0 Bluetooth Module                    | 16        | 0.43%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.4%    |
| Realtek 802.11ac WLAN Adapter                       | 13        | 0.35%   |
| Lite-On Wireless_Device                             | 12        | 0.32%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.32%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 12        | 0.32%   |
| Ralink RT3290 Bluetooth                             | 11        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4445      | 56.01%  |
| Nvidia                                       | 1450      | 18.27%  |
| AMD                                          | 1360      | 17.14%  |
| C-Media Electronics                          | 103       | 1.3%    |
| Logitech                                     | 51        | 0.64%   |
| Creative Labs                                | 35        | 0.44%   |
| ASUSTek Computer                             | 28        | 0.35%   |
| Texas Instruments                            | 26        | 0.33%   |
| Generalplus Technology                       | 26        | 0.33%   |
| Realtek Semiconductor                        | 24        | 0.3%    |
| Plantronics                                  | 21        | 0.26%   |
| KTMicro                                      | 21        | 0.26%   |
| Lenovo                                       | 20        | 0.25%   |
| Creative Technology                          | 18        | 0.23%   |
| GN Netcom                                    | 16        | 0.2%    |
| VIA Technologies                             | 15        | 0.19%   |
| JMTek                                        | 15        | 0.19%   |
| Zoran Co. Personal Media Division (Nogatech) | 12        | 0.15%   |
| Focusrite-Novation                           | 12        | 0.15%   |
| Micro Star International                     | 11        | 0.14%   |
| Kingston Technology                          | 11        | 0.14%   |
| Hewlett-Packard                              | 9         | 0.11%   |
| Silicon Integrated Systems [SiS]             | 8         | 0.1%    |
| RODE Microphones                             | 8         | 0.1%    |
| Razer USA                                    | 8         | 0.1%    |
| SteelSeries ApS                              | 7         | 0.09%   |
| Sennheiser Communications                    | 7         | 0.09%   |
| GYROCOM C&C                                  | 7         | 0.09%   |
| Dell                                         | 7         | 0.09%   |
| BEHRINGER International                      | 7         | 0.09%   |
| Yamaha                                       | 5         | 0.06%   |
| Tenx Technology                              | 5         | 0.06%   |
| Microsoft                                    | 5         | 0.06%   |
| Giga-Byte Technology                         | 5         | 0.06%   |
| Cambridge Silicon Radio                      | 5         | 0.06%   |
| Ensoniq                                      | 4         | 0.05%   |
| Corsair                                      | 4         | 0.05%   |
| Apple                                        | 4         | 0.05%   |
| Zhaoxin                                      | 3         | 0.04%   |
| XMOS                                         | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 461       | 4.91%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 391       | 4.16%   |
| Nvidia MCP79 High Definition Audio                                                                | 370       | 3.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 347       | 3.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 334       | 3.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 317       | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 307       | 3.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 274       | 2.92%   |
| Intel Broadwell-U Audio Controller                                                                | 245       | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 243       | 2.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 240       | 2.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 228       | 2.43%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 195       | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 180       | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                                        | 177       | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 169       | 1.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 156       | 1.66%   |
| Intel 200 Series PCH HD Audio                                                                     | 154       | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 131       | 1.39%   |
| Intel Comet Lake PCH cAVS                                                                         | 123       | 1.31%   |
| AMD FCH Azalia Controller                                                                         | 121       | 1.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 120       | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 115       | 1.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 115       | 1.22%   |
| Intel 8 Series HD Audio Controller                                                                | 115       | 1.22%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 110       | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 102       | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 101       | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 97        | 1.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 97        | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 92        | 0.98%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 91        | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 86        | 0.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 83        | 0.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 83        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 74        | 0.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 73        | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 71        | 0.76%   |
| Intel Jasper Lake HD Audio                                                                        | 71        | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 64        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1358      | 21.42%  |
| SK hynix            | 1309      | 20.65%  |
| Kingston            | 672       | 10.6%   |
| Unknown             | 600       | 9.47%   |
| Micron Technology   | 530       | 8.36%   |
| Crucial             | 514       | 8.11%   |
| Corsair             | 238       | 3.75%   |
| G.Skill             | 156       | 2.46%   |
| Elpida              | 119       | 1.88%   |
| A-DATA Technology   | 105       | 1.66%   |
| Ramaxel Technology  | 85        | 1.34%   |
| Patriot             | 74        | 1.17%   |
| Unknown (ABCD)      | 59        | 0.93%   |
| Nanya Technology    | 56        | 0.88%   |
| Unknown             | 56        | 0.88%   |
| Team                | 38        | 0.6%    |
| GOODRAM             | 34        | 0.54%   |
| Smart               | 30        | 0.47%   |
| Transcend           | 24        | 0.38%   |
| AMD                 | 22        | 0.35%   |
| Hikvision           | 21        | 0.33%   |
| Hewlett-Packard     | 14        | 0.22%   |
| Apacer              | 14        | 0.22%   |
| Timetec             | 12        | 0.19%   |
| Qimonda             | 9         | 0.14%   |
| Silicon Power       | 8         | 0.13%   |
| PNY                 | 7         | 0.11%   |
| Avant               | 7         | 0.11%   |
| Unknown (0x5846)    | 6         | 0.09%   |
| GeIL                | 6         | 0.09%   |
| ASint Technology    | 6         | 0.09%   |
| Wilk                | 5         | 0.08%   |
| Unifosa             | 5         | 0.08%   |
| Infineon            | 5         | 0.08%   |
| Goldkey             | 5         | 0.08%   |
| 48spaces            | 5         | 0.08%   |
| Toshiba             | 4         | 0.06%   |
| Kllisre             | 4         | 0.06%   |
| Kingmax             | 4         | 0.06%   |
| Unknown (AB)        | 3         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                       | 264       | 3.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 143       | 2.11%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                       | 69        | 1.02%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                       | 63        | 0.93%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s             | 61        | 0.9%    |
| Unknown                                                           | 56        | 0.83%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 45        | 0.67%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s           | 44        | 0.65%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                        | 41        | 0.61%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                      | 39        | 0.58%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM 1866MT/s                  | 36        | 0.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 34        | 0.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 33        | 0.49%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s             | 33        | 0.49%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 32        | 0.47%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s          | 32        | 0.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 31        | 0.46%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s             | 31        | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 30        | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 29        | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 29        | 0.43%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                        | 29        | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 29        | 0.43%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s            | 29        | 0.43%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 28        | 0.41%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 28        | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                        | 26        | 0.38%   |
| Unknown RAM Module 1GB DIMM SDRAM                                 | 26        | 0.38%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                       | 26        | 0.38%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                       | 25        | 0.37%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s            | 25        | 0.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 24        | 0.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 24        | 0.35%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s              | 24        | 0.35%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 23        | 0.34%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 23        | 0.34%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s             | 23        | 0.34%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s             | 22        | 0.33%   |
| Micron RAM EDF8132A3MA-GD-F 2GB LPDDR3 1600MT/s                   | 21        | 0.31%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 20        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 2394      | 42.62%  |
| DDR3         | 1832      | 32.62%  |
| DDR2         | 649       | 11.55%  |
| SDRAM        | 189       | 3.36%   |
| Unknown      | 175       | 3.12%   |
| LPDDR4       | 157       | 2.8%    |
| LPDDR3       | 118       | 2.1%    |
| DDR          | 58        | 1.03%   |
| DDR5         | 27        | 0.48%   |
| DRAM         | 12        | 0.21%   |
| LPDDR5       | 5         | 0.09%   |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3226      | 57.63%  |
| DIMM         | 2066      | 36.91%  |
| Row Of Chips | 208       | 3.72%   |
| Unknown      | 54        | 0.96%   |
| Chip         | 28        | 0.5%    |
| RIMM         | 8         | 0.14%   |
| FB-DIMM      | 8         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 1946      | 32.17%  |
| 4096    | 1420      | 23.47%  |
| 2048    | 939       | 15.52%  |
| 16384   | 766       | 12.66%  |
| 1024    | 627       | 10.36%  |
| 32768   | 257       | 4.25%   |
| 512     | 63        | 1.04%   |
| 256     | 17        | 0.28%   |
| 65536   | 10        | 0.17%   |
| 8072    | 1         | 0.02%   |
| 1536    | 1         | 0.02%   |
| 384     | 1         | 0.02%   |
| 128     | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1239      | 20.63%  |
| 3200    | 868       | 14.45%  |
| 2667    | 735       | 12.24%  |
| 800     | 487       | 8.11%   |
| 1333    | 408       | 6.79%   |
| 2400    | 378       | 6.29%   |
| 2133    | 261       | 4.35%   |
| 667     | 205       | 3.41%   |
| Unknown | 163       | 2.71%   |
| 1334    | 129       | 2.15%   |
| 3600    | 111       | 1.85%   |
| 1867    | 90        | 1.5%    |
| 2666    | 80        | 1.33%   |
| 1866    | 77        | 1.28%   |
| 1067    | 72        | 1.2%    |
| 1066    | 59        | 0.98%   |
| 4267    | 46        | 0.77%   |
| 3266    | 45        | 0.75%   |
| 2933    | 39        | 0.65%   |
| 4800    | 36        | 0.6%    |
| 3000    | 33        | 0.55%   |
| 3733    | 32        | 0.53%   |
| 3400    | 30        | 0.5%    |
| 1800    | 27        | 0.45%   |
| 2866    | 26        | 0.43%   |
| 533     | 26        | 0.43%   |
| 4199    | 23        | 0.38%   |
| 2048    | 21        | 0.35%   |
| 3800    | 17        | 0.28%   |
| 400     | 17        | 0.28%   |
| 3466    | 16        | 0.27%   |
| 333     | 13        | 0.22%   |
| 8400    | 11        | 0.18%   |
| 3533    | 11        | 0.18%   |
| 266     | 11        | 0.18%   |
| 3933    | 10        | 0.17%   |
| 3866    | 10        | 0.17%   |
| 3534    | 10        | 0.17%   |
| 975     | 10        | 0.17%   |
| 4266    | 9         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 44        | 33.08%  |
| Brother Industries     | 25        | 18.8%   |
| Canon                  | 18        | 13.53%  |
| Samsung Electronics    | 9         | 6.77%   |
| Xerox                  | 8         | 6.02%   |
| Seiko Epson            | 7         | 5.26%   |
| Dymo-CoStar            | 4         | 3.01%   |
| Prolific Technology    | 3         | 2.26%   |
| Zebra                  | 2         | 1.5%    |
| Pantum                 | 2         | 1.5%    |
| Lexmark International  | 2         | 1.5%    |
| STMicroelectronics     | 1         | 0.75%   |
| QinHeng Electronics    | 1         | 0.75%   |
| Printer                | 1         | 0.75%   |
| Panasonic (Matsushita) | 1         | 0.75%   |
| Oki Data               | 1         | 0.75%   |
| Kyocera                | 1         | 0.75%   |
| Konica Minolta         | 1         | 0.75%   |
| GODEX INTERNATIONAL    | 1         | 0.75%   |
| Apple                  | 1         | 0.75%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xerox B205                                                            | 7         | 5.26%   |
| HP LaserJet 1200                                                      | 5         | 3.76%   |
| Samsung ML-1660 Series                                                | 3         | 2.26%   |
| Prolific PL2305 Parallel Port                                         | 3         | 2.26%   |
| HP LaserJet P1005                                                     | 3         | 2.26%   |
| HP LaserJet M101-M106                                                 | 3         | 2.26%   |
| HP LaserJet 1020                                                      | 3         | 2.26%   |
| Canon PIXMA MG3600 Series                                             | 3         | 2.26%   |
| HP LaserJet 1150                                                      | 2         | 1.5%    |
| HP ENVY 4520 series                                                   | 2         | 1.5%    |
| HP DeskJet 2620 All-in-One Printer                                    | 2         | 1.5%    |
| HP DeskJet 2130 series                                                | 2         | 1.5%    |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 2         | 1.5%    |
| Canon PIXMA MX920 Series                                              | 2         | 1.5%    |
| Canon MF4410                                                          | 2         | 1.5%    |
| Canon LiDE 400                                                        | 2         | 1.5%    |
| Canon G3010 series                                                    | 2         | 1.5%    |
| Brother PT-9500PC                                                     | 2         | 1.5%    |
| Brother MFC-7460DN                                                    | 2         | 1.5%    |
| Brother HL-L2395DW series                                             | 2         | 1.5%    |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.75%   |
| Zebra ZTC ZD420-203dpi ZPL                                            | 1         | 0.75%   |
| Xerox Phaser 3250                                                     | 1         | 0.75%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 0.75%   |
| Seiko Epson XP-200 Series                                             | 1         | 0.75%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.75%   |
| Seiko Epson M105 Series                                               | 1         | 0.75%   |
| Seiko Epson L4260 Series                                              | 1         | 0.75%   |
| Seiko Epson L120 Series                                               | 1         | 0.75%   |
| Seiko Epson ET-2710 Series                                            | 1         | 0.75%   |
| Seiko Epson ET-2700 Series                                            | 1         | 0.75%   |
| Samsung SCX-4x26 Series                                               | 1         | 0.75%   |
| Samsung SCX-4650 4x21S Series                                         | 1         | 0.75%   |
| Samsung SCX-3200 Series                                               | 1         | 0.75%   |
| Samsung ML-216x Series Laser Printer                                  | 1         | 0.75%   |
| Samsung ML-2010P Mono Laser Printer                                   | 1         | 0.75%   |
| Samsung ML-1520 Laser Printer                                         | 1         | 0.75%   |
| QinHeng CH340S                                                        | 1         | 0.75%   |
| Printer Printer                                                       | 1         | 0.75%   |
| Pantum P2500W series                                                  | 1         | 0.75%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 19        | 59.38%  |
| Seiko Epson     | 7         | 21.88%  |
| Hewlett-Packard | 3         | 9.38%   |
| AGFA-Gevaert NV | 2         | 6.25%   |
| Mustek Systems  | 1         | 3.13%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                            | 4         | 12.5%   |
| Canon CanoScan LiDE 220                                       | 4         | 12.5%   |
| Canon CanoScan LiDE 210                                       | 2         | 6.25%   |
| Canon CanoScan LiDE 120                                       | 2         | 6.25%   |
| Canon CanoScan LiDE 110                                       | 2         | 6.25%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2         | 6.25%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 1         | 3.13%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1         | 3.13%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1         | 3.13%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 3.13%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 3.13%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                 | 1         | 3.13%   |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 3.13%   |
| Mustek Systems BearPaw 2400 CU Plus                           | 1         | 3.13%   |
| HP ScanJet Pro 2500 f1                                        | 1         | 3.13%   |
| HP ScanJet 3970c                                              | 1         | 3.13%   |
| HP Scanjet 300                                                | 1         | 3.13%   |
| Canon CanoScan LiDE 60                                        | 1         | 3.13%   |
| Canon CanoScan LIDE 25                                        | 1         | 3.13%   |
| Canon CanoScan 8800F                                          | 1         | 3.13%   |
| Canon CanoScan 5600F                                          | 1         | 3.13%   |
| Canon CanoScan 4400F                                          | 1         | 3.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 706       | 22.62%  |
| Bison Electronics                      | 285       | 9.13%   |
| IMC Networks                           | 282       | 9.04%   |
| Quanta                                 | 236       | 7.56%   |
| Microdia                               | 219       | 7.02%   |
| Realtek Semiconductor                  | 192       | 6.15%   |
| Logitech                               | 177       | 5.67%   |
| Sunplus Innovation Technology          | 134       | 4.29%   |
| Acer                                   | 94        | 3.01%   |
| Cheng Uei Precision Industry (Foxlink) | 92        | 2.95%   |
| Apple                                  | 89        | 2.85%   |
| Suyin                                  | 75        | 2.4%    |
| Lite-On Technology                     | 69        | 2.21%   |
| Syntek                                 | 58        | 1.86%   |
| Luxvisions Innotech Limited            | 55        | 1.76%   |
| Silicon Motion                         | 30        | 0.96%   |
| Alcor Micro                            | 26        | 0.83%   |
| Lenovo                                 | 23        | 0.74%   |
| Generalplus Technology                 | 18        | 0.58%   |
| Z-Star Microelectronics                | 15        | 0.48%   |
| Microsoft                              | 15        | 0.48%   |
| Sonix Technology                       | 14        | 0.45%   |
| Samsung Electronics                    | 14        | 0.45%   |
| Ricoh                                  | 12        | 0.38%   |
| Creative Technology                    | 11        | 0.35%   |
| Primax Electronics                     | 10        | 0.32%   |
| ARC International                      | 10        | 0.32%   |
| Jieli Technology                       | 9         | 0.29%   |
| Genesys Logic                          | 9         | 0.29%   |
| KYE Systems (Mouse Systems)            | 8         | 0.26%   |
| Importek                               | 8         | 0.26%   |
| SunplusIT                              | 6         | 0.19%   |
| GEMBIRD                                | 6         | 0.19%   |
| ALi                                    | 6         | 0.19%   |
| MacroSilicon                           | 5         | 0.16%   |
| Intel                                  | 5         | 0.16%   |
| icSpring                               | 5         | 0.16%   |
| Y Media                                | 4         | 0.13%   |
| OmniVision Technologies                | 4         | 0.13%   |
| Google                                 | 4         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 216       | 6.8%    |
| Bison Integrated Camera                             | 108       | 3.4%    |
| Microdia Integrated_Webcam_HD                       | 101       | 3.18%   |
| IMC Networks Integrated Camera                      | 86        | 2.71%   |
| Bison Integrated 5M Camera                          | 73        | 2.3%    |
| Realtek Integrated_Webcam_HD                        | 69        | 2.17%   |
| Quanta Chromebook HD Camera                         | 69        | 2.17%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 66        | 2.08%   |
| Chicony HD WebCam                                   | 54        | 1.7%    |
| Logitech Webcam C270                                | 53        | 1.67%   |
| Bison BisonCam, NB Pro                              | 51        | 1.6%    |
| Chicony Integrated 5M Camera                        | 43        | 1.35%   |
| Sunplus Integrated_Webcam_HD                        | 40        | 1.26%   |
| Acer Integrated Camera                              | 40        | 1.26%   |
| Chicony USB2.0 HD UVC WebCam                        | 36        | 1.13%   |
| Chicony HP HD Camera                                | 35        | 1.1%    |
| Apple Built-in iSight                               | 31        | 0.98%   |
| Syntek Integrated Camera                            | 30        | 0.94%   |
| Quanta HP TrueVision HD Camera                      | 30        | 0.94%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 30        | 0.94%   |
| Quanta HD User Facing                               | 29        | 0.91%   |
| Quanta VGA WebCam                                   | 24        | 0.76%   |
| Lite-On Integrated Camera                           | 24        | 0.76%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 23        | 0.72%   |
| Microdia Integrated Webcam                          | 22        | 0.69%   |
| Quanta HP HD Camera                                 | 21        | 0.66%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 21        | 0.66%   |
| Logitech HD Pro Webcam C920                         | 21        | 0.66%   |
| Lite-On HP HD Camera                                | 21        | 0.66%   |
| Bison SunplusIT Integrated Camera                   | 21        | 0.66%   |
| Realtek USB Camera                                  | 20        | 0.63%   |
| Apple FaceTime HD Camera (Built-in)                 | 19        | 0.6%    |
| Chicony Integrated Camera (1280x720@30)             | 18        | 0.57%   |
| Chicony HP Truevision HD camera                     | 17        | 0.53%   |
| Chicony HD User Facing                              | 17        | 0.53%   |
| Sunplus HD WebCam                                   | 16        | 0.5%    |
| Microdia USB 2.0 Camera                             | 16        | 0.5%    |
| Luxvisions Innotech Limited HP HD Camera            | 15        | 0.47%   |
| Logitech C922 Pro Stream Webcam                     | 15        | 0.47%   |
| Chicony Lenovo EasyCamera                           | 15        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 283       | 43.07%  |
| Validity Sensors                   | 188       | 28.61%  |
| Shenzhen Goodix Technology         | 73        | 11.11%  |
| Upek                               | 29        | 4.41%   |
| AuthenTec                          | 28        | 4.26%   |
| Elan Microelectronics              | 26        | 3.96%   |
| LighTuning Technology              | 18        | 2.74%   |
| STMicroelectronics                 | 9         | 1.37%   |
| Samsung Electronics                | 1         | 0.15%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.15%   |
| Focal-systems.Corp                 | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 179       | 27.25%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 42        | 6.39%   |
| Shenzhen Goodix  Fingerprint Device                                        | 41        | 6.24%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 33        | 5.02%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 32        | 4.87%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 26        | 3.96%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 24        | 3.65%   |
| Validity Sensors Synaptics WBDI                                            | 22        | 3.35%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 17        | 2.59%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 2.59%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 2.28%   |
| Elan ELAN:Fingerprint                                                      | 14        | 2.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 13        | 1.98%   |
| Elan ELAN:ARM-M4                                                           | 12        | 1.83%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 1.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 1.52%   |
| Validity Sensors VFS491                                                    | 9         | 1.37%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.37%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.37%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.22%   |
| Synaptics UWP WBDI                                                         | 8         | 1.22%   |
| Synaptics  WBDI                                                            | 8         | 1.22%   |
| AuthenTec AES2810                                                          | 8         | 1.22%   |
| Synaptics WBDI                                                             | 7         | 1.07%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.07%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 0.91%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 0.91%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 0.91%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.91%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.61%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.61%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.46%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.46%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.46%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.46%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.3%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.3%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.3%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 110       | 36.67%  |
| Alcor Micro               | 97        | 32.33%  |
| Upek                      | 24        | 8%      |
| O2 Micro                  | 22        | 7.33%   |
| Lenovo                    | 17        | 5.67%   |
| Gemalto (was Gemplus)     | 6         | 2%      |
| SCM Microsystems          | 5         | 1.67%   |
| Yubico.com                | 3         | 1%      |
| Advanced Card Systems     | 3         | 1%      |
| Reiner SCT Kartensysteme  | 2         | 0.67%   |
| Clay Logic                | 2         | 0.67%   |
| Cherry                    | 2         | 0.67%   |
| Aladdin Knowledge Systems | 2         | 0.67%   |
| Realtek Semiconductor     | 1         | 0.33%   |
| OmniKey                   | 1         | 0.33%   |
| Feitian Technologies      | 1         | 0.33%   |
| Chicony Electronics       | 1         | 0.33%   |
| C3PO                      | 1         | 0.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 95        | 31.67%  |
| Broadcom 58200                                                               | 37        | 12.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 29        | 9.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 8%      |
| Broadcom 5880                                                                | 23        | 7.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 19        | 6.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 6%      |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.33%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.67%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.67%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.67%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.67%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.67%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.67%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.67%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.67%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.33%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.33%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.33%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.33%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.33%   |
| OmniKey CardMan 4321                                                         | 1         | 0.33%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.33%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.33%   |
| Feitian Technologies SCR301                                                  | 1         | 0.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.33%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.33%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.33%   |
| C3PO LTC31v2                                                                 | 1         | 0.33%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3825      | 57.46%  |
| 1     | 2281      | 34.26%  |
| 2     | 434       | 6.52%   |
| 3     | 93        | 1.4%    |
| 4     | 17        | 0.26%   |
| 5     | 5         | 0.08%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1456      | 43.58%  |
| Fingerprint reader       | 654       | 19.57%  |
| Net/wireless             | 294       | 8.8%    |
| Chipcard                 | 273       | 8.17%   |
| Multimedia controller    | 236       | 7.06%   |
| Communication controller | 126       | 3.77%   |
| Unassigned class         | 84        | 2.51%   |
| Bluetooth                | 49        | 1.47%   |
| Sound                    | 30        | 0.9%    |
| Camera                   | 30        | 0.9%    |
| Card reader              | 28        | 0.84%   |
| Storage                  | 24        | 0.72%   |
| Net/ethernet             | 16        | 0.48%   |
| Network                  | 9         | 0.27%   |
| Modem                    | 8         | 0.24%   |
| Storage/raid             | 7         | 0.21%   |
| Tv card                  | 5         | 0.15%   |
| Flash memory             | 4         | 0.12%   |
| Dvb card                 | 4         | 0.12%   |
| Firewire controller      | 2         | 0.06%   |
| Storage/nvme             | 1         | 0.03%   |
| Storage/ide              | 1         | 0.03%   |

