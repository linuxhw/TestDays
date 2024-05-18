openSUSE Leap-15.5 - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE_Leap-15.5/Desktop/README.md) and [notebooks](/Dist/openSUSE_Leap-15.5/Notebook/README.md).

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

Total: 438

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z97-HD3                     | Desktop     | [85dee8d963](https://linux-hardware.org/?probe=85dee8d963) | May 07, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [42a7c6fb23](https://linux-hardware.org/?probe=42a7c6fb23) | May 06, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [3fafaee792](https://linux-hardware.org/?probe=3fafaee792) | May 05, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [ed934b8b61](https://linux-hardware.org/?probe=ed934b8b61) | May 05, 2024 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [a1541c5122](https://linux-hardware.org/?probe=a1541c5122) | May 02, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [9c08740bb5](https://linux-hardware.org/?probe=9c08740bb5) | May 02, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [8a00241444](https://linux-hardware.org/?probe=8a00241444) | May 01, 2024 |
| Medion        | P662X                       | Notebook    | [3689ca2476](https://linux-hardware.org/?probe=3689ca2476) | May 01, 2024 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [cdfcbe795b](https://linux-hardware.org/?probe=cdfcbe795b) | May 01, 2024 |
| Dell          | Inspiron 5748               | Notebook    | [43d176db3e](https://linux-hardware.org/?probe=43d176db3e) | Apr 29, 2024 |
| Acer          | Aspire 7741                 | Notebook    | [69f109864f](https://linux-hardware.org/?probe=69f109864f) | Apr 28, 2024 |
| Lenovo        | ThinkPad L520 786035U       | Notebook    | [711272241a](https://linux-hardware.org/?probe=711272241a) | Apr 28, 2024 |
| ASUSTek       | N751JK                      | Notebook    | [1d2d8c3d7a](https://linux-hardware.org/?probe=1d2d8c3d7a) | Apr 25, 2024 |
| Lenovo        | U31-70 80M5                 | Notebook    | [2a4ad09169](https://linux-hardware.org/?probe=2a4ad09169) | Apr 25, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [ec99c46757](https://linux-hardware.org/?probe=ec99c46757) | Apr 25, 2024 |
| ASRock        | Z390 Taichi Ultimate        | Desktop     | [8f95604689](https://linux-hardware.org/?probe=8f95604689) | Apr 24, 2024 |
| HP            | 158B                        | Desktop     | [38acb31ca9](https://linux-hardware.org/?probe=38acb31ca9) | Apr 24, 2024 |
| Acer          | Aspire 5750G                | Notebook    | [a35bd4ad42](https://linux-hardware.org/?probe=a35bd4ad42) | Apr 23, 2024 |
| Biostar       | A960D+V2                    | Desktop     | [e6d3b07d8e](https://linux-hardware.org/?probe=e6d3b07d8e) | Apr 23, 2024 |
| ASRock        | Z790 PG SONIC               | Desktop     | [6426fb59eb](https://linux-hardware.org/?probe=6426fb59eb) | Apr 22, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [8b5161f4ab](https://linux-hardware.org/?probe=8b5161f4ab) | Apr 22, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [0247606ff3](https://linux-hardware.org/?probe=0247606ff3) | Apr 21, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [cf7eac1515](https://linux-hardware.org/?probe=cf7eac1515) | Apr 21, 2024 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [542fb126b0](https://linux-hardware.org/?probe=542fb126b0) | Apr 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8cff3fe858](https://linux-hardware.org/?probe=8cff3fe858) | Apr 20, 2024 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [8a42c0cd30](https://linux-hardware.org/?probe=8a42c0cd30) | Apr 18, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e7bc6ac35e](https://linux-hardware.org/?probe=e7bc6ac35e) | Apr 17, 2024 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [f14f8b8b13](https://linux-hardware.org/?probe=f14f8b8b13) | Apr 17, 2024 |
| ASUSTek       | N751JK                      | Notebook    | [39bb3da888](https://linux-hardware.org/?probe=39bb3da888) | Apr 16, 2024 |
| Gigabyte      | P55-UD5                     | Desktop     | [736814c1df](https://linux-hardware.org/?probe=736814c1df) | Apr 13, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [b29f521f01](https://linux-hardware.org/?probe=b29f521f01) | Apr 12, 2024 |
| ASUSTek       | ROG Rampage VI EXTREME      | Desktop     | [fb483fb3bc](https://linux-hardware.org/?probe=fb483fb3bc) | Apr 10, 2024 |
| HP            | EliteBook 2730p             | Notebook    | [843cd11924](https://linux-hardware.org/?probe=843cd11924) | Apr 10, 2024 |
| Fujitsu       | CELSIUS H780                | Notebook    | [f5dc0c7623](https://linux-hardware.org/?probe=f5dc0c7623) | Apr 10, 2024 |
| Dell          | Precision M4800             | Notebook    | [e0cd62ded2](https://linux-hardware.org/?probe=e0cd62ded2) | Apr 10, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [75b15c6330](https://linux-hardware.org/?probe=75b15c6330) | Apr 09, 2024 |
| Dell          | Precision 3561              | Notebook    | [6bc6a2a9d9](https://linux-hardware.org/?probe=6bc6a2a9d9) | Apr 09, 2024 |
| Dell          | Latitude E7240              | Notebook    | [08dd3e8b44](https://linux-hardware.org/?probe=08dd3e8b44) | Apr 09, 2024 |
| ASUSTek       | ROG Rampage VI EXTREME      | Desktop     | [0de5191161](https://linux-hardware.org/?probe=0de5191161) | Apr 08, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [ea4485f45b](https://linux-hardware.org/?probe=ea4485f45b) | Apr 08, 2024 |
| HP            | ProLiant ML350 G6           | Desktop     | [3a9aaf0732](https://linux-hardware.org/?probe=3a9aaf0732) | Apr 07, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [92dd5d1690](https://linux-hardware.org/?probe=92dd5d1690) | Apr 07, 2024 |
| MSI           | Summit E13FlipEvo A11MT     | Notebook    | [3c1bd6247c](https://linux-hardware.org/?probe=3c1bd6247c) | Apr 06, 2024 |
| HP            | 3048h                       | Desktop     | [98a7ae878b](https://linux-hardware.org/?probe=98a7ae878b) | Apr 06, 2024 |
| HP            | ProLiant ML350 G6           | Desktop     | [d70516fc56](https://linux-hardware.org/?probe=d70516fc56) | Apr 06, 2024 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e009d9dd56](https://linux-hardware.org/?probe=e009d9dd56) | Apr 05, 2024 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [05643228c4](https://linux-hardware.org/?probe=05643228c4) | Apr 02, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [bb4170e7fc](https://linux-hardware.org/?probe=bb4170e7fc) | Apr 01, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [9dc48f27f9](https://linux-hardware.org/?probe=9dc48f27f9) | Apr 01, 2024 |
| Gigabyte      | EP35-DS3                    | Desktop     | [3d93a78c1b](https://linux-hardware.org/?probe=3d93a78c1b) | Mar 31, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [cf27d76a8a](https://linux-hardware.org/?probe=cf27d76a8a) | Mar 29, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [21456be41e](https://linux-hardware.org/?probe=21456be41e) | Mar 26, 2024 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [b9faafe90e](https://linux-hardware.org/?probe=b9faafe90e) | Mar 25, 2024 |
| Dell          | Vostro 3520                 | Notebook    | [233178d530](https://linux-hardware.org/?probe=233178d530) | Mar 25, 2024 |
| GEEKOM        | Mini IT11                   | Desktop     | [959133190b](https://linux-hardware.org/?probe=959133190b) | Mar 24, 2024 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [8fa61ae34a](https://linux-hardware.org/?probe=8fa61ae34a) | Mar 24, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [d3e9088b43](https://linux-hardware.org/?probe=d3e9088b43) | Mar 23, 2024 |
| Dell          | 0272WF A00                  | Server      | [ecb7c501fd](https://linux-hardware.org/?probe=ecb7c501fd) | Mar 23, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [36c66318b0](https://linux-hardware.org/?probe=36c66318b0) | Mar 22, 2024 |
| Dell          | 0M9KCM A02                  | Desktop     | [e612c937ca](https://linux-hardware.org/?probe=e612c937ca) | Mar 22, 2024 |
| ASRock        | Z790 Riptide WiFi           | Desktop     | [a03071be8b](https://linux-hardware.org/?probe=a03071be8b) | Mar 21, 2024 |
| ASRock        | Z790 Riptide WiFi           | Desktop     | [b8d5bc7323](https://linux-hardware.org/?probe=b8d5bc7323) | Mar 21, 2024 |
| ASRock        | B560 Pro4                   | Desktop     | [a34877f66c](https://linux-hardware.org/?probe=a34877f66c) | Mar 21, 2024 |
| Dell          | Precision 5520              | Notebook    | [8d942977e2](https://linux-hardware.org/?probe=8d942977e2) | Mar 20, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4d9cfcc0fb](https://linux-hardware.org/?probe=4d9cfcc0fb) | Mar 19, 2024 |
| ASUSTek       | Pro WS W680-ACE             | Desktop     | [c1ef51d3b0](https://linux-hardware.org/?probe=c1ef51d3b0) | Mar 19, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [153f16ac8d](https://linux-hardware.org/?probe=153f16ac8d) | Mar 18, 2024 |
| Acer          | Aspire 5745                 | Notebook    | [512b58fc90](https://linux-hardware.org/?probe=512b58fc90) | Mar 16, 2024 |
| Dell          | 0272WF A00                  | Server      | [5399f81241](https://linux-hardware.org/?probe=5399f81241) | Mar 15, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [174ace72e6](https://linux-hardware.org/?probe=174ace72e6) | Mar 15, 2024 |
| HP            | 2B29                        | Desktop     | [0db8d7c93c](https://linux-hardware.org/?probe=0db8d7c93c) | Mar 13, 2024 |
| Schenker      | KEY (E23)                   | Notebook    | [f555bec75a](https://linux-hardware.org/?probe=f555bec75a) | Mar 12, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [1e7f921f12](https://linux-hardware.org/?probe=1e7f921f12) | Mar 12, 2024 |
| BESSTAR Te... | GB1B                        | Mini pc     | [21d3f26046](https://linux-hardware.org/?probe=21d3f26046) | Mar 12, 2024 |
| Acer          | TravelMate P215-54          | Notebook    | [a8e5c041ef](https://linux-hardware.org/?probe=a8e5c041ef) | Mar 11, 2024 |
| ASUSTek       | P8B75-V                     | Desktop     | [6529cfcd8e](https://linux-hardware.org/?probe=6529cfcd8e) | Mar 11, 2024 |
| HP            | EliteBook 8570w             | Notebook    | [4b83d77529](https://linux-hardware.org/?probe=4b83d77529) | Mar 10, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9793665868](https://linux-hardware.org/?probe=9793665868) | Mar 08, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [66f2f3a361](https://linux-hardware.org/?probe=66f2f3a361) | Mar 04, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [3ab9b49b3e](https://linux-hardware.org/?probe=3ab9b49b3e) | Mar 04, 2024 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [97c41f0fd8](https://linux-hardware.org/?probe=97c41f0fd8) | Mar 04, 2024 |
| MSI           | Katana GF66 11UE            | Notebook    | [95b3dd2821](https://linux-hardware.org/?probe=95b3dd2821) | Mar 03, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [548005c028](https://linux-hardware.org/?probe=548005c028) | Mar 02, 2024 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [146b43cf79](https://linux-hardware.org/?probe=146b43cf79) | Mar 01, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [8464bee9a7](https://linux-hardware.org/?probe=8464bee9a7) | Feb 29, 2024 |
| HP            | 3031h                       | Desktop     | [7f8ca0e8e8](https://linux-hardware.org/?probe=7f8ca0e8e8) | Feb 29, 2024 |
| Acer          | Aspire 5742Z                | Notebook    | [22ba0ca014](https://linux-hardware.org/?probe=22ba0ca014) | Feb 29, 2024 |
| HP            | Pavilion dv9500             | Notebook    | [233bd911e6](https://linux-hardware.org/?probe=233bd911e6) | Feb 28, 2024 |
| Lenovo        | ThinkPad L530 24814YG       | Notebook    | [41599a23c0](https://linux-hardware.org/?probe=41599a23c0) | Feb 28, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [2934279a7d](https://linux-hardware.org/?probe=2934279a7d) | Feb 28, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [cc59cfab4f](https://linux-hardware.org/?probe=cc59cfab4f) | Feb 27, 2024 |
| HP            | Pavilion dv9500             | Notebook    | [8c5ec97398](https://linux-hardware.org/?probe=8c5ec97398) | Feb 27, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [cded833645](https://linux-hardware.org/?probe=cded833645) | Feb 25, 2024 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [85f840ba85](https://linux-hardware.org/?probe=85f840ba85) | Feb 24, 2024 |
| ASUSTek       | X751LX                      | Notebook    | [702ddba05b](https://linux-hardware.org/?probe=702ddba05b) | Feb 24, 2024 |
| Dell          | 0J3C2F A02                  | Desktop     | [e757c4ef0c](https://linux-hardware.org/?probe=e757c4ef0c) | Feb 21, 2024 |
| HP            | Laptop 17z-ca200            | Notebook    | [1dbf9d63d5](https://linux-hardware.org/?probe=1dbf9d63d5) | Feb 21, 2024 |
| ASUSTek       | A68HM-K                     | Desktop     | [5ba603ce75](https://linux-hardware.org/?probe=5ba603ce75) | Feb 21, 2024 |
| Acer          | Aspire A315-51              | Notebook    | [3e89cd8ab4](https://linux-hardware.org/?probe=3e89cd8ab4) | Feb 19, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [aa4c2879d1](https://linux-hardware.org/?probe=aa4c2879d1) | Feb 13, 2024 |
| HP            | EliteBook 8560p             | Notebook    | [748b126968](https://linux-hardware.org/?probe=748b126968) | Feb 12, 2024 |
| Dell          | 0C522T A01                  | Desktop     | [aa4b8ca306](https://linux-hardware.org/?probe=aa4b8ca306) | Feb 12, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [f72f15f296](https://linux-hardware.org/?probe=f72f15f296) | Feb 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [d916f30fdc](https://linux-hardware.org/?probe=d916f30fdc) | Feb 10, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [f4930d0549](https://linux-hardware.org/?probe=f4930d0549) | Feb 09, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [c8567d0dcc](https://linux-hardware.org/?probe=c8567d0dcc) | Feb 06, 2024 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [8d65745585](https://linux-hardware.org/?probe=8d65745585) | Feb 05, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [91197e4fa0](https://linux-hardware.org/?probe=91197e4fa0) | Feb 05, 2024 |
| ASRock        | B75 Pro3                    | Desktop     | [d15b9f0cc9](https://linux-hardware.org/?probe=d15b9f0cc9) | Feb 04, 2024 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [7955c56c67](https://linux-hardware.org/?probe=7955c56c67) | Jan 29, 2024 |
| HP            | ProLiant ML10 v2            | Desktop     | [b16f323611](https://linux-hardware.org/?probe=b16f323611) | Jan 28, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [d41cb5632c](https://linux-hardware.org/?probe=d41cb5632c) | Jan 28, 2024 |
| Acer          | Aspire A317-32              | Notebook    | [9baf9646df](https://linux-hardware.org/?probe=9baf9646df) | Jan 27, 2024 |
| Lenovo        | ThinkPad E14 20RAS1S600     | Notebook    | [8544584b30](https://linux-hardware.org/?probe=8544584b30) | Jan 27, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [af91485fb2](https://linux-hardware.org/?probe=af91485fb2) | Jan 25, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [343af19ed9](https://linux-hardware.org/?probe=343af19ed9) | Jan 24, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [6dd363b754](https://linux-hardware.org/?probe=6dd363b754) | Jan 22, 2024 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [f3a19638cd](https://linux-hardware.org/?probe=f3a19638cd) | Jan 21, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [195dbfe0e7](https://linux-hardware.org/?probe=195dbfe0e7) | Jan 20, 2024 |
| Dell          | Latitude E6400              | Notebook    | [b2765b0e50](https://linux-hardware.org/?probe=b2765b0e50) | Jan 19, 2024 |
| MSI           | B450 TOMAHAWK               | Desktop     | [9bed697ae6](https://linux-hardware.org/?probe=9bed697ae6) | Jan 18, 2024 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d0f45c11a7](https://linux-hardware.org/?probe=d0f45c11a7) | Jan 18, 2024 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [28a227c7d1](https://linux-hardware.org/?probe=28a227c7d1) | Jan 16, 2024 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [1ec6103b31](https://linux-hardware.org/?probe=1ec6103b31) | Jan 16, 2024 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [96e3e7f937](https://linux-hardware.org/?probe=96e3e7f937) | Jan 16, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [c2c3082933](https://linux-hardware.org/?probe=c2c3082933) | Jan 16, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [b082a9bd9f](https://linux-hardware.org/?probe=b082a9bd9f) | Jan 14, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [4dc1a2b98c](https://linux-hardware.org/?probe=4dc1a2b98c) | Jan 11, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [088dbf4c2f](https://linux-hardware.org/?probe=088dbf4c2f) | Jan 10, 2024 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [6cf5d66e62](https://linux-hardware.org/?probe=6cf5d66e62) | Jan 10, 2024 |
| Lenovo        | ThinkPad T530 2394W19       | Notebook    | [0dff2ac4a3](https://linux-hardware.org/?probe=0dff2ac4a3) | Jan 10, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2e0223d4eb](https://linux-hardware.org/?probe=2e0223d4eb) | Jan 09, 2024 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [dc1999f5b3](https://linux-hardware.org/?probe=dc1999f5b3) | Jan 09, 2024 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [5d90ffe9df](https://linux-hardware.org/?probe=5d90ffe9df) | Jan 09, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [0e9f707dea](https://linux-hardware.org/?probe=0e9f707dea) | Jan 06, 2024 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [a304de1339](https://linux-hardware.org/?probe=a304de1339) | Jan 06, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [e340939ad8](https://linux-hardware.org/?probe=e340939ad8) | Jan 06, 2024 |
| Acer          | Aspire A317-32              | Notebook    | [806a8b59fb](https://linux-hardware.org/?probe=806a8b59fb) | Jan 05, 2024 |
| HP            | 8AB6 SMVB                   | Desktop     | [b846966b99](https://linux-hardware.org/?probe=b846966b99) | Jan 04, 2024 |
| ASUSTek       | UX510UXK                    | Notebook    | [17be26f2de](https://linux-hardware.org/?probe=17be26f2de) | Jan 04, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [1504d9c050](https://linux-hardware.org/?probe=1504d9c050) | Jan 03, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [b7d97486fb](https://linux-hardware.org/?probe=b7d97486fb) | Jan 01, 2024 |
| Samsung       | 730QFG                      | Convertible | [3cb8ce6daf](https://linux-hardware.org/?probe=3cb8ce6daf) | Dec 30, 2023 |
| Dell          | Inspiron 3443               | Notebook    | [0c56a0465b](https://linux-hardware.org/?probe=0c56a0465b) | Dec 29, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [7b5d790450](https://linux-hardware.org/?probe=7b5d790450) | Dec 28, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [16a5247446](https://linux-hardware.org/?probe=16a5247446) | Dec 28, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [82f94ea967](https://linux-hardware.org/?probe=82f94ea967) | Dec 28, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [cb215ce5f6](https://linux-hardware.org/?probe=cb215ce5f6) | Dec 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [87e63ff33e](https://linux-hardware.org/?probe=87e63ff33e) | Dec 27, 2023 |
| MSI           | B150 GAMING M3              | Desktop     | [2b312f609c](https://linux-hardware.org/?probe=2b312f609c) | Dec 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [626b056720](https://linux-hardware.org/?probe=626b056720) | Dec 27, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [a271d8355d](https://linux-hardware.org/?probe=a271d8355d) | Dec 26, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [d12d3a2f21](https://linux-hardware.org/?probe=d12d3a2f21) | Dec 23, 2023 |
| Dell          | System XPS L322X            | Notebook    | [6b050ff1c8](https://linux-hardware.org/?probe=6b050ff1c8) | Dec 23, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [51cee07e16](https://linux-hardware.org/?probe=51cee07e16) | Dec 22, 2023 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [f8215b7e03](https://linux-hardware.org/?probe=f8215b7e03) | Dec 21, 2023 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [476ef9075c](https://linux-hardware.org/?probe=476ef9075c) | Dec 21, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [e0b9ef0f5e](https://linux-hardware.org/?probe=e0b9ef0f5e) | Dec 18, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [e83b933182](https://linux-hardware.org/?probe=e83b933182) | Dec 18, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [7e2afccdd6](https://linux-hardware.org/?probe=7e2afccdd6) | Dec 18, 2023 |
| System76      | Bonobo WS                   | Notebook    | [22f5ef6fce](https://linux-hardware.org/?probe=22f5ef6fce) | Dec 16, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [b949261978](https://linux-hardware.org/?probe=b949261978) | Dec 13, 2023 |
| ASUSTek       | M3A78                       | Desktop     | [d2c14973f1](https://linux-hardware.org/?probe=d2c14973f1) | Dec 10, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1e3585333b](https://linux-hardware.org/?probe=1e3585333b) | Dec 10, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [e8383035b9](https://linux-hardware.org/?probe=e8383035b9) | Dec 10, 2023 |
| HP            | Compaq 515                  | Notebook    | [025d4116ed](https://linux-hardware.org/?probe=025d4116ed) | Dec 09, 2023 |
| HP            | 3397                        | Desktop     | [f840ce3d4e](https://linux-hardware.org/?probe=f840ce3d4e) | Dec 08, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3cdaec0eab](https://linux-hardware.org/?probe=3cdaec0eab) | Dec 07, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [9d717185fb](https://linux-hardware.org/?probe=9d717185fb) | Dec 07, 2023 |
| Dell          | 0GM819                      | Desktop     | [8ff7ec90b2](https://linux-hardware.org/?probe=8ff7ec90b2) | Dec 05, 2023 |
| Intel         | S1200RP G62254-407          | Server      | [7db1ebe060](https://linux-hardware.org/?probe=7db1ebe060) | Dec 05, 2023 |
| AMI           | Intel                       | Desktop     | [7fdef1f7fc](https://linux-hardware.org/?probe=7fdef1f7fc) | Dec 04, 2023 |
| HP            | Notebook                    | Notebook    | [0a554c91b1](https://linux-hardware.org/?probe=0a554c91b1) | Dec 01, 2023 |
| ASUSTek       | M4A88T-M LE                 | Desktop     | [a2f1655886](https://linux-hardware.org/?probe=a2f1655886) | Dec 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [4ba2fc285f](https://linux-hardware.org/?probe=4ba2fc285f) | Nov 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [0f9a06cc9f](https://linux-hardware.org/?probe=0f9a06cc9f) | Nov 30, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [9accd13cb5](https://linux-hardware.org/?probe=9accd13cb5) | Nov 30, 2023 |
| HP            | Notebook                    | Notebook    | [93464a0904](https://linux-hardware.org/?probe=93464a0904) | Nov 30, 2023 |
| ASUSTek       | M4A88T-M LE                 | Desktop     | [1e982d5ac9](https://linux-hardware.org/?probe=1e982d5ac9) | Nov 30, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [f6e7c5e8a3](https://linux-hardware.org/?probe=f6e7c5e8a3) | Nov 29, 2023 |
| Acer          | Aspire A317-32              | Notebook    | [02b205724a](https://linux-hardware.org/?probe=02b205724a) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [1eda316922](https://linux-hardware.org/?probe=1eda316922) | Nov 28, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [b46ec04a69](https://linux-hardware.org/?probe=b46ec04a69) | Nov 27, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d3122d678f](https://linux-hardware.org/?probe=d3122d678f) | Nov 27, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [84e4d06443](https://linux-hardware.org/?probe=84e4d06443) | Nov 26, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [312776837c](https://linux-hardware.org/?probe=312776837c) | Nov 26, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [8104fc2789](https://linux-hardware.org/?probe=8104fc2789) | Nov 26, 2023 |
| HP            | 212B                        | Desktop     | [90bc0d4d2d](https://linux-hardware.org/?probe=90bc0d4d2d) | Nov 25, 2023 |
| ASUSTek       | M3A78                       | Desktop     | [c4895d59da](https://linux-hardware.org/?probe=c4895d59da) | Nov 23, 2023 |
| Biostar       | TF570 SLI A2+               | Desktop     | [50eb6f63d8](https://linux-hardware.org/?probe=50eb6f63d8) | Nov 23, 2023 |
| Biostar       | TF570 SLI A2+               | Desktop     | [052c9cc626](https://linux-hardware.org/?probe=052c9cc626) | Nov 23, 2023 |
| Acer          | Aspire A515-45G             | Notebook    | [1ec9d0635f](https://linux-hardware.org/?probe=1ec9d0635f) | Nov 23, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [718e30ca5e](https://linux-hardware.org/?probe=718e30ca5e) | Nov 22, 2023 |
| System76      | Lemur Pro                   | Notebook    | [45a6298cb5](https://linux-hardware.org/?probe=45a6298cb5) | Nov 22, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [1d8de35042](https://linux-hardware.org/?probe=1d8de35042) | Nov 21, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [4949cbc96a](https://linux-hardware.org/?probe=4949cbc96a) | Nov 19, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [36ce4210e3](https://linux-hardware.org/?probe=36ce4210e3) | Nov 19, 2023 |
| ASUSTek       | M3A78                       | Desktop     | [a6392d3aae](https://linux-hardware.org/?probe=a6392d3aae) | Nov 19, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [5cdf728f08](https://linux-hardware.org/?probe=5cdf728f08) | Nov 15, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9fc66b4436](https://linux-hardware.org/?probe=9fc66b4436) | Nov 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [d169a02b18](https://linux-hardware.org/?probe=d169a02b18) | Nov 14, 2023 |
| Dell          | Latitude E6410              | Notebook    | [1e9606e755](https://linux-hardware.org/?probe=1e9606e755) | Nov 14, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [383553241b](https://linux-hardware.org/?probe=383553241b) | Nov 14, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [242621dab3](https://linux-hardware.org/?probe=242621dab3) | Nov 13, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [474f3dea0b](https://linux-hardware.org/?probe=474f3dea0b) | Nov 13, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [6406ede8d4](https://linux-hardware.org/?probe=6406ede8d4) | Nov 11, 2023 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [161674ce4a](https://linux-hardware.org/?probe=161674ce4a) | Nov 10, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [9222374410](https://linux-hardware.org/?probe=9222374410) | Nov 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [e736653169](https://linux-hardware.org/?probe=e736653169) | Nov 08, 2023 |
| Lenovo        | ThinkPad W541 20EGS1LB00    | Notebook    | [7a31e185b9](https://linux-hardware.org/?probe=7a31e185b9) | Nov 07, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [680fae0bef](https://linux-hardware.org/?probe=680fae0bef) | Nov 07, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [1c86a5a6de](https://linux-hardware.org/?probe=1c86a5a6de) | Nov 05, 2023 |
| Lenovo        | ThinkPad T490 20N2000LSP    | Notebook    | [55e3cdf0cc](https://linux-hardware.org/?probe=55e3cdf0cc) | Nov 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [d1d65399a0](https://linux-hardware.org/?probe=d1d65399a0) | Nov 03, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [f446da83f1](https://linux-hardware.org/?probe=f446da83f1) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [137dba2261](https://linux-hardware.org/?probe=137dba2261) | Nov 02, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [1a9eef3748](https://linux-hardware.org/?probe=1a9eef3748) | Nov 02, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [9893d57e1b](https://linux-hardware.org/?probe=9893d57e1b) | Nov 01, 2023 |
| ASUSTek       | M5A87                       | Desktop     | [b254c30981](https://linux-hardware.org/?probe=b254c30981) | Nov 01, 2023 |
| MSI           | X370 GAMING PRO             | Desktop     | [c8ba0de51d](https://linux-hardware.org/?probe=c8ba0de51d) | Oct 31, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [7d5dc09b04](https://linux-hardware.org/?probe=7d5dc09b04) | Oct 30, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [fa410ee23c](https://linux-hardware.org/?probe=fa410ee23c) | Oct 29, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [16417bdac2](https://linux-hardware.org/?probe=16417bdac2) | Oct 29, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [33d021b931](https://linux-hardware.org/?probe=33d021b931) | Oct 28, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [ae8894002e](https://linux-hardware.org/?probe=ae8894002e) | Oct 27, 2023 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [0990fc4382](https://linux-hardware.org/?probe=0990fc4382) | Oct 26, 2023 |
| ASUSTek       | ZenBook UX434FL             | Notebook    | [139d1a74ed](https://linux-hardware.org/?probe=139d1a74ed) | Oct 25, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [b615345fa6](https://linux-hardware.org/?probe=b615345fa6) | Oct 21, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [75f2f0b411](https://linux-hardware.org/?probe=75f2f0b411) | Oct 21, 2023 |
| Gigabyte      | B85M-D2V                    | Desktop     | [572daeb059](https://linux-hardware.org/?probe=572daeb059) | Oct 19, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [398445f93d](https://linux-hardware.org/?probe=398445f93d) | Oct 14, 2023 |
| HP            | ProBook 4535s               | Notebook    | [e52e92c95b](https://linux-hardware.org/?probe=e52e92c95b) | Oct 14, 2023 |
| Lenovo        | Annapurna CRB 0B98401 PR... | Desktop     | [e550587c85](https://linux-hardware.org/?probe=e550587c85) | Oct 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [729234c285](https://linux-hardware.org/?probe=729234c285) | Oct 14, 2023 |
| ASRock        | WRX80 Creator R2.0          | Other       | [56b055ab70](https://linux-hardware.org/?probe=56b055ab70) | Oct 12, 2023 |
| HP            | 3048h                       | Desktop     | [79350e657a](https://linux-hardware.org/?probe=79350e657a) | Oct 12, 2023 |
| Lenovo        | ThinkPad T400 27658JG       | Notebook    | [3b3b7832c9](https://linux-hardware.org/?probe=3b3b7832c9) | Oct 11, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [5e8749954f](https://linux-hardware.org/?probe=5e8749954f) | Oct 11, 2023 |
| ASRock        | WRX80 Creator R2.0          | Other       | [8b9a5127c0](https://linux-hardware.org/?probe=8b9a5127c0) | Oct 11, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [9ff3f35842](https://linux-hardware.org/?probe=9ff3f35842) | Oct 11, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4c0b8f71c3](https://linux-hardware.org/?probe=4c0b8f71c3) | Oct 10, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [541d9a0542](https://linux-hardware.org/?probe=541d9a0542) | Oct 10, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [c98952b2ee](https://linux-hardware.org/?probe=c98952b2ee) | Oct 10, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [814f6c5c52](https://linux-hardware.org/?probe=814f6c5c52) | Oct 09, 2023 |
| ASUSTek       | P5Q3                        | Desktop     | [5d51aca6b2](https://linux-hardware.org/?probe=5d51aca6b2) | Oct 08, 2023 |
| ASUSTek       | P5Q3                        | Desktop     | [9beb6f3b26](https://linux-hardware.org/?probe=9beb6f3b26) | Oct 08, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [4f2f37c5ba](https://linux-hardware.org/?probe=4f2f37c5ba) | Oct 08, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [f6fc0aee5b](https://linux-hardware.org/?probe=f6fc0aee5b) | Oct 07, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [c0c10b1767](https://linux-hardware.org/?probe=c0c10b1767) | Oct 07, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [7d321bffa1](https://linux-hardware.org/?probe=7d321bffa1) | Oct 07, 2023 |
| Dell          | Precision M6500             | Notebook    | [18605f38d4](https://linux-hardware.org/?probe=18605f38d4) | Oct 05, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [d48122086b](https://linux-hardware.org/?probe=d48122086b) | Oct 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [ab02b2a3e7](https://linux-hardware.org/?probe=ab02b2a3e7) | Oct 04, 2023 |
| Lenovo        | ThinkPad X390 20Q1S5K400    | Notebook    | [4d9d1bf62a](https://linux-hardware.org/?probe=4d9d1bf62a) | Oct 02, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [d6c281a706](https://linux-hardware.org/?probe=d6c281a706) | Oct 01, 2023 |
| HP            | 198E                        | Desktop     | [a311728a5f](https://linux-hardware.org/?probe=a311728a5f) | Sep 29, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [013801fc61](https://linux-hardware.org/?probe=013801fc61) | Sep 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [6fc52a277a](https://linux-hardware.org/?probe=6fc52a277a) | Sep 28, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [c09e747a85](https://linux-hardware.org/?probe=c09e747a85) | Sep 27, 2023 |
| OEM           | B75 Ver:1.41                | Desktop     | [01109ec772](https://linux-hardware.org/?probe=01109ec772) | Sep 24, 2023 |
| Intel         | S1200RP G62254-407          | Server      | [1d003db534](https://linux-hardware.org/?probe=1d003db534) | Sep 24, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [f5ed151e3e](https://linux-hardware.org/?probe=f5ed151e3e) | Sep 24, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [f94566dde6](https://linux-hardware.org/?probe=f94566dde6) | Sep 23, 2023 |
| HP            | ENVY 17                     | Notebook    | [4f6463148f](https://linux-hardware.org/?probe=4f6463148f) | Sep 22, 2023 |
| Lenovo        | ThinkPad W500 40624DG       | Notebook    | [9bdd448e89](https://linux-hardware.org/?probe=9bdd448e89) | Sep 22, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [b962cd9626](https://linux-hardware.org/?probe=b962cd9626) | Sep 19, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [1bd2a17c99](https://linux-hardware.org/?probe=1bd2a17c99) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | Notebook    | [d68a92e72a](https://linux-hardware.org/?probe=d68a92e72a) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | Notebook    | [8b335d6bb0](https://linux-hardware.org/?probe=8b335d6bb0) | Sep 19, 2023 |
| ASRock        | Z590M Pro4                  | Desktop     | [d63be526d2](https://linux-hardware.org/?probe=d63be526d2) | Sep 18, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [8e044378bd](https://linux-hardware.org/?probe=8e044378bd) | Sep 15, 2023 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [6cc800f5dc](https://linux-hardware.org/?probe=6cc800f5dc) | Sep 14, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [4714deba45](https://linux-hardware.org/?probe=4714deba45) | Sep 14, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [bd161c3850](https://linux-hardware.org/?probe=bd161c3850) | Sep 14, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [de53daa0f8](https://linux-hardware.org/?probe=de53daa0f8) | Sep 12, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8fc40b8424](https://linux-hardware.org/?probe=8fc40b8424) | Sep 12, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [de229ab61f](https://linux-hardware.org/?probe=de229ab61f) | Sep 11, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [4d658a922b](https://linux-hardware.org/?probe=4d658a922b) | Sep 10, 2023 |
| Dell          | Precision 7540              | Notebook    | [ced1086a24](https://linux-hardware.org/?probe=ced1086a24) | Sep 09, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [d6a8fc3557](https://linux-hardware.org/?probe=d6a8fc3557) | Sep 08, 2023 |
| Dell          | Latitude 5431               | Notebook    | [b2d976a088](https://linux-hardware.org/?probe=b2d976a088) | Sep 08, 2023 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [394dd17b98](https://linux-hardware.org/?probe=394dd17b98) | Sep 07, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [d34f211b22](https://linux-hardware.org/?probe=d34f211b22) | Sep 07, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [098294fb47](https://linux-hardware.org/?probe=098294fb47) | Sep 07, 2023 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | Desktop     | [1e743d0b2d](https://linux-hardware.org/?probe=1e743d0b2d) | Sep 06, 2023 |
| Sony          | SVF1521A7EB                 | Notebook    | [8b130feb09](https://linux-hardware.org/?probe=8b130feb09) | Sep 06, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [12ed8aee3f](https://linux-hardware.org/?probe=12ed8aee3f) | Sep 05, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [fdcab89946](https://linux-hardware.org/?probe=fdcab89946) | Sep 05, 2023 |
| ASRock        | Z490 Phantom Gaming 4/ac    | Desktop     | [5fa23571c9](https://linux-hardware.org/?probe=5fa23571c9) | Sep 04, 2023 |
| Medion        | S15449                      | Notebook    | [7e8cd1a434](https://linux-hardware.org/?probe=7e8cd1a434) | Sep 02, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [22c3bee6fa](https://linux-hardware.org/?probe=22c3bee6fa) | Sep 02, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [315510322c](https://linux-hardware.org/?probe=315510322c) | Sep 02, 2023 |
| Acer          | Aspire A317-32              | Notebook    | [0a46c781fc](https://linux-hardware.org/?probe=0a46c781fc) | Sep 01, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [e7c4150ded](https://linux-hardware.org/?probe=e7c4150ded) | Sep 01, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [fd3c900751](https://linux-hardware.org/?probe=fd3c900751) | Aug 31, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [a21f3ba335](https://linux-hardware.org/?probe=a21f3ba335) | Aug 30, 2023 |
| Dell          | 0K06NC A00                  | All in one  | [75acf7c3bf](https://linux-hardware.org/?probe=75acf7c3bf) | Aug 30, 2023 |
| Dell          | 0K06NC A00                  | All in one  | [616c88aa53](https://linux-hardware.org/?probe=616c88aa53) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470p 20J60014P... | Notebook    | [7690eb9089](https://linux-hardware.org/?probe=7690eb9089) | Aug 30, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [704a62ef33](https://linux-hardware.org/?probe=704a62ef33) | Aug 29, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [beb1174dde](https://linux-hardware.org/?probe=beb1174dde) | Aug 29, 2023 |
| Gigabyte      | B75M-D3P                    | Desktop     | [73562af96c](https://linux-hardware.org/?probe=73562af96c) | Aug 28, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [c5b6554c6b](https://linux-hardware.org/?probe=c5b6554c6b) | Aug 26, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [083aa2f63c](https://linux-hardware.org/?probe=083aa2f63c) | Aug 25, 2023 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [0cf842e282](https://linux-hardware.org/?probe=0cf842e282) | Aug 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [58d50740e7](https://linux-hardware.org/?probe=58d50740e7) | Aug 24, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [b141917712](https://linux-hardware.org/?probe=b141917712) | Aug 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6b9175d89e](https://linux-hardware.org/?probe=6b9175d89e) | Aug 22, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [2e8b5e3b34](https://linux-hardware.org/?probe=2e8b5e3b34) | Aug 20, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [5a62fd8541](https://linux-hardware.org/?probe=5a62fd8541) | Aug 17, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [4c36ef643e](https://linux-hardware.org/?probe=4c36ef643e) | Aug 17, 2023 |
| ASUSTek       | M4A77TD                     | Desktop     | [a2c6278e77](https://linux-hardware.org/?probe=a2c6278e77) | Aug 15, 2023 |
| Toshiba       | Satellite Pro C70-A         | Notebook    | [dbb00fe95b](https://linux-hardware.org/?probe=dbb00fe95b) | Aug 15, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [2f82c5eb18](https://linux-hardware.org/?probe=2f82c5eb18) | Aug 14, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [f523831970](https://linux-hardware.org/?probe=f523831970) | Aug 14, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [b0e10f6505](https://linux-hardware.org/?probe=b0e10f6505) | Aug 13, 2023 |
| Intel         | DX58OG AAG10926-205         | Desktop     | [cb3a9289f9](https://linux-hardware.org/?probe=cb3a9289f9) | Aug 13, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [66bcc74be2](https://linux-hardware.org/?probe=66bcc74be2) | Aug 13, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e374cc3341](https://linux-hardware.org/?probe=e374cc3341) | Aug 12, 2023 |
| HP            | 1589                        | Desktop     | [1a38154020](https://linux-hardware.org/?probe=1a38154020) | Aug 12, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8193c225e5](https://linux-hardware.org/?probe=8193c225e5) | Aug 11, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [6f722400c2](https://linux-hardware.org/?probe=6f722400c2) | Aug 11, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [c2b7b4e760](https://linux-hardware.org/?probe=c2b7b4e760) | Aug 10, 2023 |
| Dell          | 0272WF A00                  | Server      | [39abbc5ab8](https://linux-hardware.org/?probe=39abbc5ab8) | Aug 09, 2023 |
| Dell          | Precision 7740              | Notebook    | [954d8472e5](https://linux-hardware.org/?probe=954d8472e5) | Aug 09, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [bb99f6f69e](https://linux-hardware.org/?probe=bb99f6f69e) | Aug 07, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [f4beee823e](https://linux-hardware.org/?probe=f4beee823e) | Aug 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7637f0d91d](https://linux-hardware.org/?probe=7637f0d91d) | Aug 06, 2023 |
| ASUSTek       | Z97-PRO/USB                 | Desktop     | [edd74878c3](https://linux-hardware.org/?probe=edd74878c3) | Aug 05, 2023 |
| HP            | 470 G7 Notebook PC          | Notebook    | [7e4a9b4618](https://linux-hardware.org/?probe=7e4a9b4618) | Aug 04, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [fe0a1dbc45](https://linux-hardware.org/?probe=fe0a1dbc45) | Aug 04, 2023 |
| Dell          | 082WXT A03                  | Desktop     | [27a50c4491](https://linux-hardware.org/?probe=27a50c4491) | Aug 03, 2023 |
| MSI           | X370 GAMING PRO             | Desktop     | [b684b97e44](https://linux-hardware.org/?probe=b684b97e44) | Aug 02, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [8fb651def8](https://linux-hardware.org/?probe=8fb651def8) | Aug 02, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [356dae8360](https://linux-hardware.org/?probe=356dae8360) | Jul 30, 2023 |
| Dell          | 0272WF A00                  | Server      | [ab789b12e1](https://linux-hardware.org/?probe=ab789b12e1) | Jul 30, 2023 |
| Biostar       | A320MH                      | Desktop     | [8fbc21fb3e](https://linux-hardware.org/?probe=8fbc21fb3e) | Jul 29, 2023 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [3a81b2b0d9](https://linux-hardware.org/?probe=3a81b2b0d9) | Jul 29, 2023 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [4d6a620df3](https://linux-hardware.org/?probe=4d6a620df3) | Jul 29, 2023 |
| HP            | 3048h                       | Desktop     | [cd83e4a73a](https://linux-hardware.org/?probe=cd83e4a73a) | Jul 29, 2023 |
| HP            | 3048h                       | Desktop     | [56918c8bad](https://linux-hardware.org/?probe=56918c8bad) | Jul 29, 2023 |
| Sony          | Unknown                     | Notebook    | [80613731cb](https://linux-hardware.org/?probe=80613731cb) | Jul 28, 2023 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [7e89496549](https://linux-hardware.org/?probe=7e89496549) | Jul 27, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [9d891afae0](https://linux-hardware.org/?probe=9d891afae0) | Jul 26, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [1568ba2843](https://linux-hardware.org/?probe=1568ba2843) | Jul 25, 2023 |
| HP            | 1589                        | Desktop     | [5c0bd1ec07](https://linux-hardware.org/?probe=5c0bd1ec07) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [b7c7b058b7](https://linux-hardware.org/?probe=b7c7b058b7) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [edf7b092ec](https://linux-hardware.org/?probe=edf7b092ec) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [421c2ff6b0](https://linux-hardware.org/?probe=421c2ff6b0) | Jul 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [c741f10f18](https://linux-hardware.org/?probe=c741f10f18) | Jul 23, 2023 |
| MSI           | X58 Pro-E                   | Desktop     | [01f822dec1](https://linux-hardware.org/?probe=01f822dec1) | Jul 22, 2023 |
| Medion        | E6224                       | Notebook    | [c33b8a1fb1](https://linux-hardware.org/?probe=c33b8a1fb1) | Jul 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d8d58cb5fb](https://linux-hardware.org/?probe=d8d58cb5fb) | Jul 21, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [7b6300dfc7](https://linux-hardware.org/?probe=7b6300dfc7) | Jul 20, 2023 |
| Sony          | Unknown                     | Notebook    | [427e52d6a6](https://linux-hardware.org/?probe=427e52d6a6) | Jul 20, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [65da6837ae](https://linux-hardware.org/?probe=65da6837ae) | Jul 20, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [a2779c6ac8](https://linux-hardware.org/?probe=a2779c6ac8) | Jul 19, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [fe065234a9](https://linux-hardware.org/?probe=fe065234a9) | Jul 17, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [295bc58365](https://linux-hardware.org/?probe=295bc58365) | Jul 17, 2023 |
| Medion        | E6224                       | Notebook    | [4ffae87044](https://linux-hardware.org/?probe=4ffae87044) | Jul 17, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [fd05b31515](https://linux-hardware.org/?probe=fd05b31515) | Jul 16, 2023 |
| Lenovo        | B5400 80B6QB0               | Notebook    | [7108435241](https://linux-hardware.org/?probe=7108435241) | Jul 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [6b351b341e](https://linux-hardware.org/?probe=6b351b341e) | Jul 15, 2023 |
| Lenovo        | ThinkPad T530 2394W19       | Notebook    | [874f8b41a7](https://linux-hardware.org/?probe=874f8b41a7) | Jul 14, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [78f620581b](https://linux-hardware.org/?probe=78f620581b) | Jul 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [9bee6805c0](https://linux-hardware.org/?probe=9bee6805c0) | Jul 13, 2023 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [9b03d78d55](https://linux-hardware.org/?probe=9b03d78d55) | Jul 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [93d94feca6](https://linux-hardware.org/?probe=93d94feca6) | Jul 11, 2023 |
| ASUSTek       | K53SM                       | Notebook    | [7aac135bc0](https://linux-hardware.org/?probe=7aac135bc0) | Jul 11, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [becf9726c7](https://linux-hardware.org/?probe=becf9726c7) | Jul 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [a52e535dcb](https://linux-hardware.org/?probe=a52e535dcb) | Jul 11, 2023 |
| Dell          | Latitude E5410              | Notebook    | [8d980136c2](https://linux-hardware.org/?probe=8d980136c2) | Jul 10, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [9f920e8a7e](https://linux-hardware.org/?probe=9f920e8a7e) | Jul 10, 2023 |
| HP            | Notebook                    | Notebook    | [a1c37a6a4b](https://linux-hardware.org/?probe=a1c37a6a4b) | Jul 09, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [c00debe968](https://linux-hardware.org/?probe=c00debe968) | Jul 08, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [a72d3eff75](https://linux-hardware.org/?probe=a72d3eff75) | Jul 08, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [8a5cbee239](https://linux-hardware.org/?probe=8a5cbee239) | Jul 08, 2023 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [f459621198](https://linux-hardware.org/?probe=f459621198) | Jul 06, 2023 |
| HP            | 8B3B A                      | Desktop     | [b003988978](https://linux-hardware.org/?probe=b003988978) | Jul 05, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [b3530f3e0e](https://linux-hardware.org/?probe=b3530f3e0e) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | Desktop     | [7592c0cc37](https://linux-hardware.org/?probe=7592c0cc37) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | Desktop     | [71505f347f](https://linux-hardware.org/?probe=71505f347f) | Jul 05, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [40b7950cb2](https://linux-hardware.org/?probe=40b7950cb2) | Jul 05, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [73435e5646](https://linux-hardware.org/?probe=73435e5646) | Jul 05, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [427fc931a0](https://linux-hardware.org/?probe=427fc931a0) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [27c53e1152](https://linux-hardware.org/?probe=27c53e1152) | Jul 01, 2023 |
| Lenovo        | ThinkPad T530 2394W19       | Notebook    | [a1fc2e0020](https://linux-hardware.org/?probe=a1fc2e0020) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a203a588f9](https://linux-hardware.org/?probe=a203a588f9) | Jun 30, 2023 |
| HP            | 8055                        | Desktop     | [47536e2cde](https://linux-hardware.org/?probe=47536e2cde) | Jun 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2dd6be0ddc](https://linux-hardware.org/?probe=2dd6be0ddc) | Jun 29, 2023 |
| Lenovo        | ThinkPad X200 7458AH8       | Notebook    | [a81af2d7e2](https://linux-hardware.org/?probe=a81af2d7e2) | Jun 29, 2023 |
| HP            | 1589                        | Desktop     | [dcb3289360](https://linux-hardware.org/?probe=dcb3289360) | Jun 29, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [1ef1762ac3](https://linux-hardware.org/?probe=1ef1762ac3) | Jun 28, 2023 |
| Gigabyte      | EG45M-DS2H                  | Desktop     | [b9b25df5a3](https://linux-hardware.org/?probe=b9b25df5a3) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [1fe3acdf83](https://linux-hardware.org/?probe=1fe3acdf83) | Jun 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [17c221fa68](https://linux-hardware.org/?probe=17c221fa68) | Jun 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6c015f633b](https://linux-hardware.org/?probe=6c015f633b) | Jun 24, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [905653d393](https://linux-hardware.org/?probe=905653d393) | Jun 24, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [761a478742](https://linux-hardware.org/?probe=761a478742) | Jun 22, 2023 |
| Pegatron      | JESSE                       | Desktop     | [fa09a247a7](https://linux-hardware.org/?probe=fa09a247a7) | Jun 19, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [733af664a4](https://linux-hardware.org/?probe=733af664a4) | Jun 18, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [7412881615](https://linux-hardware.org/?probe=7412881615) | Jun 18, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [bbb32d23be](https://linux-hardware.org/?probe=bbb32d23be) | Jun 17, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | Notebook    | [0210669ff3](https://linux-hardware.org/?probe=0210669ff3) | Jun 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [fdc4101cba](https://linux-hardware.org/?probe=fdc4101cba) | Jun 13, 2023 |
| Fujitsu       | D2942-B1 S26361-D2942-B1    | Desktop     | [ed8bd3839f](https://linux-hardware.org/?probe=ed8bd3839f) | Jun 12, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [87b818815c](https://linux-hardware.org/?probe=87b818815c) | Jun 10, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [6d70667d42](https://linux-hardware.org/?probe=6d70667d42) | Jun 09, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [6d989f49b6](https://linux-hardware.org/?probe=6d989f49b6) | Jun 09, 2023 |
| Fujitsu       | D2942-B1 S26361-D2942-B1    | Desktop     | [9fb55abc56](https://linux-hardware.org/?probe=9fb55abc56) | Jun 08, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [ad5baed526](https://linux-hardware.org/?probe=ad5baed526) | Jun 08, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [f6fddfcd65](https://linux-hardware.org/?probe=f6fddfcd65) | Jun 07, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8e0a13cdd1](https://linux-hardware.org/?probe=8e0a13cdd1) | Jun 04, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d8f3391b68](https://linux-hardware.org/?probe=d8f3391b68) | Jun 02, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [ab7c62da47](https://linux-hardware.org/?probe=ab7c62da47) | Jun 02, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [2cf19f7b32](https://linux-hardware.org/?probe=2cf19f7b32) | Jun 02, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [a313036ec2](https://linux-hardware.org/?probe=a313036ec2) | May 31, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [2881299761](https://linux-hardware.org/?probe=2881299761) | May 30, 2023 |
| ASRock        | J3355B-ITX                  | Desktop     | [02f6d0b74b](https://linux-hardware.org/?probe=02f6d0b74b) | May 29, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [eb9ee9f38e](https://linux-hardware.org/?probe=eb9ee9f38e) | May 27, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [e0920f015d](https://linux-hardware.org/?probe=e0920f015d) | May 25, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [f133543500](https://linux-hardware.org/?probe=f133543500) | May 23, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [c903e06758](https://linux-hardware.org/?probe=c903e06758) | May 22, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [7087600ab6](https://linux-hardware.org/?probe=7087600ab6) | May 17, 2023 |
| Dell          | Inspiron 7573               | Convertible | [8f57130549](https://linux-hardware.org/?probe=8f57130549) | May 17, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [74c412b40a](https://linux-hardware.org/?probe=74c412b40a) | May 16, 2023 |
| Dell          | Inspiron 7573               | Convertible | [6f1d226305](https://linux-hardware.org/?probe=6f1d226305) | May 16, 2023 |
| ASRock        | J3355B-ITX                  | Desktop     | [443ee2bf3a](https://linux-hardware.org/?probe=443ee2bf3a) | May 16, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [2dc2bdd057](https://linux-hardware.org/?probe=2dc2bdd057) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [29d2a588e0](https://linux-hardware.org/?probe=29d2a588e0) | Apr 27, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d73e1b6350](https://linux-hardware.org/?probe=d73e1b6350) | Apr 24, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | Desktop     | [2f50a76b96](https://linux-hardware.org/?probe=2f50a76b96) | Mar 22, 2023 |
| Dell          | Latitude D530               | Notebook    | [92cf04edba](https://linux-hardware.org/?probe=92cf04edba) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9b0a8de7a1](https://linux-hardware.org/?probe=9b0a8de7a1) | Feb 02, 2023 |
| Fujitsu Si... | D2399 S26361-D2399          | Desktop     | [77a5931c66](https://linux-hardware.org/?probe=77a5931c66) | Oct 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [706514d122](https://linux-hardware.org/?probe=706514d122) | Sep 10, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.14.21-150500.53-default      | 65        | 19.23%  |
| 5.14.21-150500.55.52-default   | 45        | 13.31%  |
| 5.14.21-150500.55.19-default   | 41        | 12.13%  |
| 5.14.21-150500.55.39-default   | 33        | 9.76%   |
| 5.14.21-150500.55.36-default   | 31        | 9.17%   |
| 5.14.21-150500.55.49-default   | 23        | 6.8%    |
| 5.14.21-150500.55.31-default   | 20        | 5.92%   |
| 5.14.21-150500.55.7-default    | 16        | 4.73%   |
| 5.14.21-150500.55.12-default   | 12        | 3.55%   |
| 5.14.21-150500.55.28-default   | 11        | 3.25%   |
| 5.14.21-150500.55.44-default   | 10        | 2.96%   |
| 5.14.21-150500.52-default      | 9         | 2.66%   |
| 5.14.21-150500.55.59-default   | 8         | 2.37%   |
| 5.14.21-150500.43-default      | 2         | 0.59%   |
| 5.14.21-150400.24.18-default   | 2         | 0.59%   |
| 6.6.3-1-default                | 1         | 0.3%    |
| 6.6.11-lp155.3-default         | 1         | 0.3%    |
| 6.5.9-lp155.2-default          | 1         | 0.3%    |
| 6.5.4-1-default                | 1         | 0.3%    |
| 6.4.4-lp154.2.g919c802-default | 1         | 0.3%    |
| 5.14.21-150500.50-default      | 1         | 0.3%    |
| 5.14.21-150500.49-default      | 1         | 0.3%    |
| 5.14.21-150500.37-default      | 1         | 0.3%    |
| 5.14.21-150400.24.55-default   | 1         | 0.3%    |
| 5.14.21-150400.24.46-default   | 1         | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.21 | 299       | 98.36%  |
| 6.6.3   | 1         | 0.33%   |
| 6.6.11  | 1         | 0.33%   |
| 6.5.9   | 1         | 0.33%   |
| 6.5.4   | 1         | 0.33%   |
| 6.4.4   | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 299       | 98.36%  |
| 6.6     | 2         | 0.66%   |
| 6.5     | 2         | 0.66%   |
| 6.4     | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 303       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 233       | 76.39%  |
| GNOME    | 46        | 15.08%  |
| XFCE     | 12        | 3.93%   |
| Unknown  | 5         | 1.64%   |
| MATE     | 2         | 0.66%   |
| ICEWM    | 2         | 0.66%   |
| Cinnamon | 2         | 0.66%   |
| Trinity  | 1         | 0.33%   |
| KDE      | 1         | 0.33%   |
| Budgie   | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 259       | 84.36%  |
| Wayland | 38        | 12.38%  |
| Tty     | 9         | 2.93%   |
| Unknown | 1         | 0.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 193       | 63.07%  |
| SDDM    | 83        | 27.12%  |
| LightDM | 16        | 5.23%   |
| GDM     | 8         | 2.61%   |
| XDM     | 6         | 1.96%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 104       | 34.1%   |
| de_DE           | 78        | 25.57%  |
| POSIX           | 28        | 9.18%   |
| pt_BR           | 14        | 4.59%   |
| ru_RU           | 13        | 4.26%   |
| es_ES           | 11        | 3.61%   |
| fr_FR           | 8         | 2.62%   |
| pl_PL           | 7         | 2.3%    |
| nl_NL           | 7         | 2.3%    |
| en_GB           | 7         | 2.3%    |
| it_IT           | 6         | 1.97%   |
| hu_HU           | 3         | 0.98%   |
| C               | 3         | 0.98%   |
| zh_CN           | 2         | 0.66%   |
| sk_SK           | 2         | 0.66%   |
| en_DK           | 2         | 0.66%   |
| ja_JP           | 1         | 0.33%   |
| fi_FI           | 1         | 0.33%   |
| es_DO           | 1         | 0.33%   |
| en_ZA           | 1         | 0.33%   |
| en_US.ISO8859-1 | 1         | 0.33%   |
| el_GR           | 1         | 0.33%   |
| da_DK           | 1         | 0.33%   |
| cs_CZ           | 1         | 0.33%   |
| ar_AE           | 1         | 0.33%   |
| Unknown         | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 211       | 68.95%  |
| EFI  | 95        | 31.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 238       | 78.03%  |
| Ext4  | 57        | 18.69%  |
| Xfs   | 7         | 2.3%    |
| Tmpfs | 2         | 0.66%   |
| Zfs   | 1         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 187       | 61.11%  |
| GPT     | 107       | 34.97%  |
| MBR     | 12        | 3.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 274       | 90.13%  |
| Yes       | 30        | 9.87%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 251       | 82.57%  |
| Yes       | 53        | 17.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 47        | 15.51%  |
| Hewlett-Packard     | 46        | 15.18%  |
| ASUSTek Computer    | 46        | 15.18%  |
| Dell                | 32        | 10.56%  |
| Gigabyte Technology | 26        | 8.58%   |
| ASRock              | 18        | 5.94%   |
| Acer                | 18        | 5.94%   |
| MSI                 | 16        | 5.28%   |
| Intel               | 5         | 1.65%   |
| Fujitsu             | 5         | 1.65%   |
| TUXEDO              | 3         | 0.99%   |
| Medion              | 3         | 0.99%   |
| Biostar             | 3         | 0.99%   |
| Apple               | 3         | 0.99%   |
| Toshiba             | 2         | 0.66%   |
| System76            | 2         | 0.66%   |
| Sony                | 2         | 0.66%   |
| Samsung Electronics | 2         | 0.66%   |
| Notebook            | 2         | 0.66%   |
| HUAWEI              | 2         | 0.66%   |
| HC Technology.      | 2         | 0.66%   |
| Fujitsu Siemens     | 2         | 0.66%   |
| AZW                 | 2         | 0.66%   |
| Wortmann AG         | 1         | 0.33%   |
| Schenker            | 1         | 0.33%   |
| Pegatron            | 1         | 0.33%   |
| Panasonic           | 1         | 0.33%   |
| OEM                 | 1         | 0.33%   |
| GEEKOM              | 1         | 0.33%   |
| Framework           | 1         | 0.33%   |
| Foxconn             | 1         | 0.33%   |
| Dynabook            | 1         | 0.33%   |
| Colorful Technology | 1         | 0.33%   |
| BESSTAR Tech        | 1         | 0.33%   |
| AMI                 | 1         | 0.33%   |
| Alienware           | 1         | 0.33%   |
| Unknown             | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASUS M5A97 R2.0                                                                          | 3         | 0.99%   |
| TUXEDO Aura 15 Gen2                                                                      | 2         | 0.66%   |
| HP Z420 Workstation                                                                      | 2         | 0.66%   |
| HP Victus by Gaming Laptop 15-fb0xxx                                                     | 2         | 0.66%   |
| HP Notebook                                                                              | 2         | 0.66%   |
| HC Technology. HCAR5000-MI                                                               | 2         | 0.66%   |
| Gigabyte B550M DS3H                                                                      | 2         | 0.66%   |
| AZW SER                                                                                  | 2         | 0.66%   |
| ASUS ROG STRIX X570-E GAMING                                                             | 2         | 0.66%   |
| Unknown                                                                                  | 2         | 0.66%   |
| Wortmann AG TERRA_MOBILE_1749                                                            | 1         | 0.33%   |
| TUXEDO Pulse 15 Gen2                                                                     | 1         | 0.33%   |
| Toshiba Satellite Pro C70-A                                                              | 1         | 0.33%   |
| Toshiba dynabook Satellite B552/H                                                        | 1         | 0.33%   |
| System76 Lemur Pro                                                                       | 1         | 0.33%   |
| System76 Bonobo WS                                                                       | 1         | 0.33%   |
| Sony SVF1521A7EB                                                                         | 1         | 0.33%   |
| Schenker KEY (E23)                                                                       | 1         | 0.33%   |
| Samsung 730QFG                                                                           | 1         | 0.33%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.33%   |
| Pegatron NY603AA-ABA 300-1007                                                            | 1         | 0.33%   |
| Panasonic CF-C2CUGZXKM                                                                   | 1         | 0.33%   |
| OEM B75                                                                                  | 1         | 0.33%   |
| Notebook NS50_70MU                                                                       | 1         | 0.33%   |
| Notebook NLx0MU                                                                          | 1         | 0.33%   |
| MSI Summit E13FlipEvo A11MT                                                              | 1         | 0.33%   |
| MSI MS-7D74                                                                              | 1         | 0.33%   |
| MSI MS-7D54                                                                              | 1         | 0.33%   |
| MSI MS-7C95                                                                              | 1         | 0.33%   |
| MSI MS-7C91                                                                              | 1         | 0.33%   |
| MSI MS-7C80                                                                              | 1         | 0.33%   |
| MSI MS-7C52                                                                              | 1         | 0.33%   |
| MSI MS-7C02                                                                              | 1         | 0.33%   |
| MSI MS-7B89                                                                              | 1         | 0.33%   |
| MSI MS-7B85                                                                              | 1         | 0.33%   |
| MSI MS-7B17                                                                              | 1         | 0.33%   |
| MSI MS-7A33                                                                              | 1         | 0.33%   |
| MSI MS-7978                                                                              | 1         | 0.33%   |
| MSI MS-7522                                                                              | 1         | 0.33%   |
| MSI Katana GF66 11UE                                                                     | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 21        | 6.93%   |
| Acer Aspire                | 12        | 3.96%   |
| Dell Precision             | 7         | 2.31%   |
| ASUS ROG                   | 7         | 2.31%   |
| Lenovo IdeaPad             | 6         | 1.98%   |
| HP Laptop                  | 6         | 1.98%   |
| HP EliteBook               | 6         | 1.98%   |
| Dell OptiPlex              | 6         | 1.98%   |
| Dell Latitude              | 6         | 1.98%   |
| Dell Inspiron              | 6         | 1.98%   |
| Lenovo ThinkCentre         | 5         | 1.65%   |
| Lenovo Legion              | 5         | 1.65%   |
| HP ProLiant                | 5         | 1.65%   |
| ASUS PRIME                 | 5         | 1.65%   |
| HP ENVY                    | 4         | 1.32%   |
| HP Compaq                  | 4         | 1.32%   |
| HP Pavilion                | 3         | 0.99%   |
| Dell Vostro                | 3         | 0.99%   |
| ASUS VivoBook              | 3         | 0.99%   |
| ASUS M5A97                 | 3         | 0.99%   |
| TUXEDO Aura                | 2         | 0.66%   |
| HP Z420                    | 2         | 0.66%   |
| HP Victus                  | 2         | 0.66%   |
| HP ProBook                 | 2         | 0.66%   |
| HP OMEN                    | 2         | 0.66%   |
| HP Notebook                | 2         | 0.66%   |
| HC Technology. HCAR5000-MI | 2         | 0.66%   |
| Gigabyte B550M             | 2         | 0.66%   |
| Gigabyte B450M             | 2         | 0.66%   |
| Fujitsu ESPRIMO            | 2         | 0.66%   |
| Dell XPS                   | 2         | 0.66%   |
| AZW SER                    | 2         | 0.66%   |
| ASRock Z790                | 2         | 0.66%   |
| ASRock Z390                | 2         | 0.66%   |
| Acer TravelMate            | 2         | 0.66%   |
| Acer Nitro                 | 2         | 0.66%   |
| Unknown                    | 2         | 0.66%   |
| Wortmann AG TERRA          | 1         | 0.33%   |
| TUXEDO Pulse               | 1         | 0.33%   |
| Toshiba Satellite          | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 34        | 11.22%  |
| 2020 | 27        | 8.91%   |
| 2022 | 23        | 7.59%   |
| 2012 | 22        | 7.26%   |
| 2023 | 21        | 6.93%   |
| 2010 | 21        | 6.93%   |
| 2018 | 20        | 6.6%    |
| 2019 | 19        | 6.27%   |
| 2015 | 19        | 6.27%   |
| 2013 | 19        | 6.27%   |
| 2011 | 16        | 5.28%   |
| 2017 | 14        | 4.62%   |
| 2014 | 12        | 3.96%   |
| 2016 | 10        | 3.3%    |
| 2009 | 9         | 2.97%   |
| 2008 | 9         | 2.97%   |
| 2007 | 6         | 1.98%   |
| 2024 | 1         | 0.33%   |
| 2006 | 1         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 146       | 48.18%  |
| Desktop     | 139       | 45.87%  |
| Convertible | 6         | 1.98%   |
| Mini pc     | 5         | 1.65%   |
| Server      | 4         | 1.32%   |
| All in one  | 2         | 0.66%   |
| Other       | 1         | 0.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 280       | 92.41%  |
| Enabled  | 23        | 7.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 301       | 99.34%  |
| Yes  | 2         | 0.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 71        | 23.28%  |
| 16.01-24.0      | 70        | 22.95%  |
| 8.01-16.0       | 59        | 19.34%  |
| 32.01-64.0      | 46        | 15.08%  |
| 3.01-4.0        | 28        | 9.18%   |
| 64.01-256.0     | 19        | 6.23%   |
| 1.01-2.0        | 6         | 1.97%   |
| 24.01-32.0      | 5         | 1.64%   |
| More than 256.0 | 1         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 117       | 36.11%  |
| 1.01-2.0   | 66        | 20.37%  |
| 3.01-4.0   | 61        | 18.83%  |
| 4.01-8.0   | 55        | 16.98%  |
| 8.01-16.0  | 13        | 4.01%   |
| 0.51-1.0   | 8         | 2.47%   |
| 16.01-24.0 | 3         | 0.93%   |
| 24.01-32.0 | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 165       | 53.92%  |
| 2      | 74        | 24.18%  |
| 3      | 39        | 12.75%  |
| 4      | 13        | 4.25%   |
| 5      | 9         | 2.94%   |
| 6      | 5         | 1.63%   |
| 8      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 172       | 56.58%  |
| Yes       | 132       | 43.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 278       | 91.75%  |
| No        | 25        | 8.25%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 209       | 68.52%  |
| No        | 96        | 31.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 59.67%  |
| No        | 123       | 40.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 87        | 28.71%  |
| USA          | 51        | 16.83%  |
| Russia       | 16        | 5.28%   |
| Brazil       | 16        | 5.28%   |
| Poland       | 10        | 3.3%    |
| Italy        | 8         | 2.64%   |
| UK           | 7         | 2.31%   |
| Netherlands  | 7         | 2.31%   |
| Greece       | 6         | 1.98%   |
| Switzerland  | 5         | 1.65%   |
| India        | 5         | 1.65%   |
| France       | 5         | 1.65%   |
| Belgium      | 5         | 1.65%   |
| Spain        | 4         | 1.32%   |
| Hungary      | 4         | 1.32%   |
| Finland      | 4         | 1.32%   |
| Canada       | 4         | 1.32%   |
| Australia    | 4         | 1.32%   |
| Ukraine      | 3         | 0.99%   |
| Sweden       | 3         | 0.99%   |
| Mexico       | 3         | 0.99%   |
| Colombia     | 3         | 0.99%   |
| Argentina    | 3         | 0.99%   |
| South Africa | 2         | 0.66%   |
| Slovenia     | 2         | 0.66%   |
| Slovakia     | 2         | 0.66%   |
| Serbia       | 2         | 0.66%   |
| Hong Kong    | 2         | 0.66%   |
| Czechia      | 2         | 0.66%   |
| China        | 2         | 0.66%   |
| Bulgaria     | 2         | 0.66%   |
| Austria      | 2         | 0.66%   |
| Vietnam      | 1         | 0.33%   |
| Venezuela    | 1         | 0.33%   |
| Turkey       | 1         | 0.33%   |
| South Korea  | 1         | 0.33%   |
| Senegal      | 1         | 0.33%   |
| Romania      | 1         | 0.33%   |
| Portugal     | 1         | 0.33%   |
| Peru         | 1         | 0.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Munich               | 8         | 2.56%   |
| Berlin               | 7         | 2.24%   |
| Warsaw               | 4         | 1.28%   |
| St Petersburg        | 3         | 0.96%   |
| Kyiv                 | 3         | 0.96%   |
| Hamburg              | 3         | 0.96%   |
| Enschede             | 3         | 0.96%   |
| Budapest             | 3         | 0.96%   |
| Zurich               | 2         | 0.64%   |
| Zetel                | 2         | 0.64%   |
| Sydney               | 2         | 0.64%   |
| Sofia                | 2         | 0.64%   |
| Sao Vicente          | 2         | 0.64%   |
| Sao Paulo            | 2         | 0.64%   |
| Sacramento           | 2         | 0.64%   |
| Rüsselsheim am Main | 2         | 0.64%   |
| Rostock              | 2         | 0.64%   |
| Rio de Janeiro       | 2         | 0.64%   |
| Nuremberg            | 2         | 0.64%   |
| Milan                | 2         | 0.64%   |
| Ljubljana            | 2         | 0.64%   |
| Leipzig              | 2         | 0.64%   |
| Krakow               | 2         | 0.64%   |
| Kansas City          | 2         | 0.64%   |
| Johannesburg         | 2         | 0.64%   |
| Ithaca               | 2         | 0.64%   |
| Heraklion            | 2         | 0.64%   |
| Hanover              | 2         | 0.64%   |
| Denver               | 2         | 0.64%   |
| Cherry Hill          | 2         | 0.64%   |
| Central              | 2         | 0.64%   |
| Bremen               | 2         | 0.64%   |
| Bonn                 | 2         | 0.64%   |
| Alcobendas           | 2         | 0.64%   |
| Zuchwil              | 1         | 0.32%   |
| Zagreb               | 1         | 0.32%   |
| Yokohama             | 1         | 0.32%   |
| Yekaterinburg        | 1         | 0.32%   |
| Yakutsk              | 1         | 0.32%   |
| Wuppertal            | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 91        | 134    | 19.16%  |
| Seagate                     | 69        | 112    | 14.53%  |
| WDC                         | 54        | 95     | 11.37%  |
| Kingston                    | 26        | 35     | 5.47%   |
| SanDisk                     | 25        | 36     | 5.26%   |
| Crucial                     | 20        | 22     | 4.21%   |
| Toshiba                     | 17        | 21     | 3.58%   |
| Hitachi                     | 16        | 16     | 3.37%   |
| Intel                       | 14        | 15     | 2.95%   |
| SK hynix                    | 13        | 15     | 2.74%   |
| Micron Technology           | 12        | 13     | 2.53%   |
| Unknown                     | 11        | 11     | 2.32%   |
| Silicon Motion              | 7         | 7      | 1.47%   |
| Intenso                     | 7         | 8      | 1.47%   |
| Micron/Crucial Technology   | 6         | 7      | 1.26%   |
| Kingston Technology Company | 6         | 8      | 1.26%   |
| HGST                        | 6         | 7      | 1.26%   |
| China                       | 5         | 6      | 1.05%   |
| A-DATA Technology           | 5         | 5      | 1.05%   |
| Phison Electronics          | 4         | 4      | 0.84%   |
| KIOXIA                      | 4         | 5      | 0.84%   |
| Apple                       | 4         | 4      | 0.84%   |
| ADATA Technology            | 4         | 4      | 0.84%   |
| SPCC                        | 3         | 3      | 0.63%   |
| Hewlett-Packard             | 3         | 3      | 0.63%   |
| XrayDisk                    | 2         | 2      | 0.42%   |
| SABRENT                     | 2         | 2      | 0.42%   |
| PNY                         | 2         | 4      | 0.42%   |
| Netac                       | 2         | 4      | 0.42%   |
| Leven                       | 2         | 2      | 0.42%   |
| Dogfish                     | 2         | 2      | 0.42%   |
| ASMT                        | 2         | 3      | 0.42%   |
| Yangtze Memory Technologies | 1         | 1      | 0.21%   |
| XSTAR                       | 1         | 1      | 0.21%   |
| USB                         | 1         | 1      | 0.21%   |
| Union Memory                | 1         | 1      | 0.21%   |
| Transcend                   | 1         | 1      | 0.21%   |
| T-FORCE                     | 1         | 1      | 0.21%   |
| Synology                    | 1         | 1      | 0.21%   |
| StoreJet                    | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 16        | 3.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 12        | 2.3%    |
| Seagate ST500DM002-1BD142 500GB                       | 6         | 1.15%   |
| Samsung SSD 870 EVO 1TB                               | 6         | 1.15%   |
| Seagate ST2000DM008-2FR102 2TB                        | 5         | 0.96%   |
| Samsung SSD 840 EVO 250GB                             | 5         | 0.96%   |
| Kingston SA400S37480G 480GB SSD                       | 5         | 0.96%   |
| Kingston SA400S37120G 120GB SSD                       | 5         | 0.96%   |
| Intel SSD 660P Series 1024GB                          | 5         | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 4         | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 4         | 0.77%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                    | 4         | 0.77%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 4         | 0.77%   |
| Crucial CT275MX300SSD1 275GB                          | 4         | 0.77%   |
| Seagate ST500LM012 HN-M500MBB 500GB                   | 3         | 0.58%   |
| Seagate ST4000DM004-2CV104 4TB                        | 3         | 0.58%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 3         | 0.58%   |
| Samsung SSD 990 PRO 2TB                               | 3         | 0.58%   |
| Samsung SSD 860 EVO 1TB                               | 3         | 0.58%   |
| Samsung SSD 850 EVO 250GB                             | 3         | 0.58%   |
| Samsung SSD 840 EVO 120GB                             | 3         | 0.58%   |
| Kingston SV300S37A120G 120GB SSD                      | 3         | 0.58%   |
| Kingston SA400S37240G 240GB SSD                       | 3         | 0.58%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                      | 2         | 0.38%   |
| WDC WD10EZRX-00A8LB0 1TB                              | 2         | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 2         | 0.38%   |
| WDC WD10EZEX-08M2NA0 1TB                              | 2         | 0.38%   |
| WDC WD1003FZEX-00K3CA0 1TB                            | 2         | 0.38%   |
| Unknown SD/MMC/MS PRO 128GB                           | 2         | 0.38%   |
| Unknown MMC Card  64GB                                | 2         | 0.38%   |
| Unknown MMC Card  32GB                                | 2         | 0.38%   |
| Unknown MMC Card  16GB                                | 2         | 0.38%   |
| Toshiba MQ04ABF100 1TB                                | 2         | 0.38%   |
| Toshiba MQ01ABD100 1TB                                | 2         | 0.38%   |
| Toshiba HDWD130 3TB                                   | 2         | 0.38%   |
| Toshiba DT01ACA100 1TB                                | 2         | 0.38%   |
| Toshiba DT01ACA050 500GB                              | 2         | 0.38%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 2TB     | 2         | 0.38%   |
| Seagate ST9500325AS 500GB                             | 2         | 0.38%   |
| Seagate ST8000DM004-2U9188 8TB                        | 2         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 103    | 37.79%  |
| WDC                 | 47        | 78     | 27.33%  |
| Hitachi             | 16        | 16     | 9.3%    |
| Toshiba             | 12        | 14     | 6.98%   |
| Samsung Electronics | 12        | 14     | 6.98%   |
| HGST                | 6         | 7      | 3.49%   |
| Apple               | 3         | 3      | 1.74%   |
| Unknown             | 2         | 2      | 1.16%   |
| SABRENT             | 2         | 2      | 1.16%   |
| Hewlett-Packard     | 2         | 2      | 1.16%   |
| XrayDisk            | 1         | 1      | 0.58%   |
| Synology            | 1         | 1      | 0.58%   |
| Maxone              | 1         | 1      | 0.58%   |
| Fujitsu             | 1         | 2      | 0.58%   |
| ASMT                | 1         | 2      | 0.58%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 63     | 26.62%  |
| Kingston            | 21        | 27     | 13.64%  |
| Crucial             | 20        | 22     | 12.99%  |
| WDC                 | 8         | 16     | 5.19%   |
| SanDisk             | 8         | 12     | 5.19%   |
| Intenso             | 6         | 6      | 3.9%    |
| China               | 5         | 6      | 3.25%   |
| A-DATA Technology   | 5         | 5      | 3.25%   |
| Toshiba             | 4         | 5      | 2.6%    |
| Intel               | 4         | 5      | 2.6%    |
| SPCC                | 3         | 3      | 1.95%   |
| Micron Technology   | 3         | 3      | 1.95%   |
| SK hynix            | 2         | 2      | 1.3%    |
| PNY                 | 2         | 4      | 1.3%    |
| Netac               | 2         | 4      | 1.3%    |
| Leven               | 2         | 2      | 1.3%    |
| Dogfish             | 2         | 2      | 1.3%    |
| XSTAR               | 1         | 1      | 0.65%   |
| XrayDisk            | 1         | 1      | 0.65%   |
| Transcend           | 1         | 1      | 0.65%   |
| StoreJet            | 1         | 1      | 0.65%   |
| Radeon              | 1         | 1      | 0.65%   |
| Patriot             | 1         | 1      | 0.65%   |
| LITEON              | 1         | 1      | 0.65%   |
| Hewlett-Packard     | 1         | 1      | 0.65%   |
| GOODRAM             | 1         | 1      | 0.65%   |
| Gigabyte Technology | 1         | 1      | 0.65%   |
| FIKWOT              | 1         | 1      | 0.65%   |
| Fanxiang            | 1         | 2      | 0.65%   |
| BAITITON            | 1         | 1      | 0.65%   |
| ASMT                | 1         | 1      | 0.65%   |
| Apple               | 1         | 1      | 0.65%   |
| AMD                 | 1         | 1      | 0.65%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 130       | 248    | 32.18%  |
| SSD     | 129       | 204    | 31.93%  |
| NVMe    | 126       | 173    | 31.19%  |
| Unknown | 11        | 14     | 2.72%   |
| MMC     | 8         | 8      | 1.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 207       | 426    | 56.56%  |
| NVMe | 126       | 171    | 34.43%  |
| SAS  | 25        | 42     | 6.83%   |
| MMC  | 8         | 8      | 2.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 142       | 214    | 49.82%  |
| 0.51-1.0   | 83        | 140    | 29.12%  |
| 1.01-2.0   | 30        | 54     | 10.53%  |
| 3.01-4.0   | 17        | 26     | 5.96%   |
| 4.01-10.0  | 5         | 9      | 1.75%   |
| 2.01-3.0   | 4         | 4      | 1.4%    |
| 10.01-20.0 | 4         | 5      | 1.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 114       | 36.66%  |
| 1001-2000      | 61        | 19.61%  |
| 2001-3000      | 37        | 11.9%   |
| 501-1000       | 37        | 11.9%   |
| 251-500        | 30        | 9.65%   |
| 101-250        | 20        | 6.43%   |
| 51-100         | 5         | 1.61%   |
| 21-50          | 3         | 0.96%   |
| Unknown        | 3         | 0.96%   |
| 1-20           | 1         | 0.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 92        | 28.31%  |
| 51-100         | 60        | 18.46%  |
| 251-500        | 47        | 14.46%  |
| 501-1000       | 38        | 11.69%  |
| 1001-2000      | 27        | 8.31%   |
| 1-20           | 20        | 6.15%   |
| More than 3000 | 16        | 4.92%   |
| 21-50          | 16        | 4.92%   |
| 2001-3000      | 6         | 1.85%   |
| Unknown        | 3         | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2         | 2      | 16.67%  |
| Kingston SA400S37120G 120GB SSD                  | 2         | 4      | 16.67%  |
| Toshiba MD04ACA400 4TB                           | 1         | 1      | 8.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 8.33%   |
| Seagate ST4000NM0035-1V4107 4TB                  | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 840 EVO 120GB            | 1         | 1      | 8.33%   |
| Samsung Electronics MZALQ256HBJD-00BL2 256GB     | 1         | 1      | 8.33%   |
| Samsung Electronics MZ7TE256HMHP-000L7 256GB SSD | 1         | 1      | 8.33%   |
| Intel SSD 600P Series 256GB                      | 1         | 1      | 8.33%   |
| Hitachi HTS727550A9E364 500GB                    | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 36.36%  |
| Samsung Electronics | 2         | 3      | 18.18%  |
| Kingston            | 2         | 4      | 18.18%  |
| Toshiba             | 1         | 1      | 9.09%   |
| Intel               | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 66.67%  |
| Toshiba | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 54.55%  |
| SSD  | 3         | 6      | 27.27%  |
| NVMe | 2         | 2      | 18.18%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HD502HJ 500GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 194       | 425    | 60.63%  |
| Works    | 115       | 206    | 35.94%  |
| Malfunc  | 10        | 14     | 3.13%   |
| Failed   | 1         | 2      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 190       | 45.13%  |
| AMD                           | 72        | 17.1%   |
| Samsung Electronics           | 46        | 10.93%  |
| SanDisk                       | 18        | 4.28%   |
| SK hynix                      | 11        | 2.61%   |
| Kingston Technology Company   | 11        | 2.61%   |
| Micron Technology             | 9         | 2.14%   |
| ASMedia Technology            | 8         | 1.9%    |
| Silicon Motion                | 7         | 1.66%   |
| Micron/Crucial Technology     | 6         | 1.43%   |
| JMicron Technology            | 6         | 1.43%   |
| Seagate Technology            | 4         | 0.95%   |
| Phison Electronics            | 4         | 0.95%   |
| Marvell Technology Group      | 4         | 0.95%   |
| KIOXIA                        | 4         | 0.95%   |
| Broadcom / LSI                | 4         | 0.95%   |
| ADATA Technology              | 4         | 0.95%   |
| Toshiba America Info Systems  | 2         | 0.48%   |
| Nvidia                        | 2         | 0.48%   |
| Yangtze Memory Technologies   | 1         | 0.24%   |
| VIA Technologies              | 1         | 0.24%   |
| Union Memory (Shenzhen)       | 1         | 0.24%   |
| Realtek Semiconductor         | 1         | 0.24%   |
| MAXIO Technology (Hangzhou)   | 1         | 0.24%   |
| Integrated Technology Express | 1         | 0.24%   |
| Hewlett-Packard               | 1         | 0.24%   |
| Adaptec                       | 1         | 0.24%   |
| Unknown                       | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 38        | 7.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 16        | 3.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 2.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12        | 2.42%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 12        | 2.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 2.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 2.22%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 10        | 2.02%   |
| AMD 400 Series Chipset SATA Controller                                         | 10        | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 9         | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 1.81%   |
| AMD 500 Series Chipset SATA Controller                                         | 9         | 1.81%   |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 1.61%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 8         | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 1.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7         | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 1.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 1.21%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.01%   |
| JMicron JMB363 SATA/IDE Controller                                             | 5         | 1.01%   |
| Intel SSD 660P Series                                                          | 5         | 1.01%   |
| Intel SATA Controller [RAID Mode]                                              | 5         | 1.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.01%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 5         | 1.01%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.01%   |
| AMD FCH SATA Controller D                                                      | 5         | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 4         | 0.81%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 4         | 0.81%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 4         | 0.81%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4         | 0.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 0.81%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 4         | 0.81%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 4         | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 0.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 0.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 230       | 52.75%  |
| NVMe | 126       | 28.9%   |
| IDE  | 43        | 9.86%   |
| RAID | 30        | 6.88%   |
| SAS  | 6         | 1.38%   |
| SCSI | 1         | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 211       | 69.64%  |
| AMD    | 92        | 30.36%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 2.31%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 6         | 1.98%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 6         | 1.98%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 6         | 1.98%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 1.65%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 4         | 1.32%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 0.99%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 3         | 0.99%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 3         | 0.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 0.99%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 3         | 0.99%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 3         | 0.99%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 3         | 0.99%   |
| Intel 13th Gen Core i9-13900HX          | 3         | 0.99%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 3         | 0.99%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 3         | 0.99%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 3         | 0.99%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 3         | 0.99%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3         | 0.99%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 3         | 0.99%   |
| Intel Xeon CPU X5650 @ 2.67GHz          | 2         | 0.66%   |
| Intel Xeon CPU E5-1603 0 @ 2.80GHz      | 2         | 0.66%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 2         | 0.66%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz      | 2         | 0.66%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 2         | 0.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 2         | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 0.66%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 0.66%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 2         | 0.66%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz   | 2         | 0.66%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 2         | 0.66%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2         | 0.66%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 2         | 0.66%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 0.66%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 2         | 0.66%   |
| AMD FX-8370 Eight-Core Processor        | 2         | 0.66%   |
| AMD FX-8350 Eight-Core Processor        | 2         | 0.66%   |
| Intel Xeon E-2276M CPU @ 2.80GHz        | 1         | 0.33%   |
| Intel Xeon CPU W3530 @ 2.80GHz          | 1         | 0.33%   |
| Intel Xeon CPU E5450 @ 3.00GHz          | 1         | 0.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 48        | 15.84%  |
| Intel Core i5           | 48        | 15.84%  |
| Other                   | 42        | 13.86%  |
| AMD Ryzen 5             | 26        | 8.58%   |
| Intel Core i3           | 19        | 6.27%   |
| AMD Ryzen 7             | 19        | 6.27%   |
| Intel Xeon              | 15        | 4.95%   |
| Intel Core 2 Duo        | 10        | 3.3%    |
| Intel Celeron           | 10        | 3.3%    |
| AMD FX                  | 9         | 2.97%   |
| Intel Pentium           | 7         | 2.31%   |
| AMD Ryzen 9             | 7         | 2.31%   |
| Intel Core 2 Quad       | 4         | 1.32%   |
| AMD A8                  | 4         | 1.32%   |
| AMD Ryzen 7 PRO         | 3         | 0.99%   |
| AMD Ryzen 3             | 3         | 0.99%   |
| AMD A6                  | 3         | 0.99%   |
| Intel Pentium Dual-Core | 2         | 0.66%   |
| Intel Core i9           | 2         | 0.66%   |
| AMD Phenom II X4        | 2         | 0.66%   |
| AMD Athlon              | 2         | 0.66%   |
| AMD A4                  | 2         | 0.66%   |
| Intel Pentium Silver    | 1         | 0.33%   |
| Intel Pentium Gold      | 1         | 0.33%   |
| Intel Pentium Dual      | 1         | 0.33%   |
| Intel Core 2 Extreme    | 1         | 0.33%   |
| AMD Ryzen Threadripper  | 1         | 0.33%   |
| AMD Ryzen 5 PRO         | 1         | 0.33%   |
| AMD Ryzen 3 PRO         | 1         | 0.33%   |
| AMD Phenom II X6        | 1         | 0.33%   |
| AMD Phenom              | 1         | 0.33%   |
| AMD Opteron             | 1         | 0.33%   |
| AMD Athlon X4           | 1         | 0.33%   |
| AMD Athlon X2           | 1         | 0.33%   |
| AMD Athlon II X4        | 1         | 0.33%   |
| AMD Athlon II X3        | 1         | 0.33%   |
| AMD Athlon II X2        | 1         | 0.33%   |
| AMD Athlon 64 X2        | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 104       | 34.32%  |
| 2      | 86        | 28.38%  |
| 6      | 43        | 14.19%  |
| 8      | 30        | 9.9%    |
| 12     | 14        | 4.62%   |
| 16     | 6         | 1.98%   |
| 24     | 4         | 1.32%   |
| 1      | 4         | 1.32%   |
| 14     | 3         | 0.99%   |
| 10     | 3         | 0.99%   |
| 3      | 3         | 0.99%   |
| 64     | 1         | 0.33%   |
| 32     | 1         | 0.33%   |
| 20     | 1         | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 297       | 98.02%  |
| 2      | 5         | 1.65%   |
| 4      | 1         | 0.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 223       | 73.6%   |
| 1      | 80        | 26.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 303       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 178       | 57.98%  |
| 0x806c1    | 10        | 3.26%   |
| 0x08608103 | 8         | 2.61%   |
| 0x1067a    | 7         | 2.28%   |
| 0xb0671    | 6         | 1.95%   |
| 0x906ea    | 5         | 1.63%   |
| 0x806ec    | 5         | 1.63%   |
| 0x0a50000d | 5         | 1.63%   |
| 0x906e9    | 4         | 1.3%    |
| 0x306c3    | 4         | 1.3%    |
| 0x306a9    | 4         | 1.3%    |
| 0xa0671    | 3         | 0.98%   |
| 0x506e3    | 3         | 0.98%   |
| 0x406e3    | 3         | 0.98%   |
| 0x206d7    | 3         | 0.98%   |
| 0x0a50000c | 3         | 0.98%   |
| 0x08600106 | 3         | 0.98%   |
| 0xb06a2    | 2         | 0.65%   |
| 0x906ed    | 2         | 0.65%   |
| 0x906a3    | 2         | 0.65%   |
| 0x806ea    | 2         | 0.65%   |
| 0x806e9    | 2         | 0.65%   |
| 0x806c2    | 2         | 0.65%   |
| 0x706a8    | 2         | 0.65%   |
| 0x40651    | 2         | 0.65%   |
| 0x206a7    | 2         | 0.65%   |
| 0x106e5    | 2         | 0.65%   |
| 0x0a601203 | 2         | 0.65%   |
| 0x08701021 | 2         | 0.65%   |
| 0x08608102 | 2         | 0.65%   |
| 0x0800820d | 2         | 0.65%   |
| 0x06001119 | 2         | 0.65%   |
| 0xa0655    | 1         | 0.33%   |
| 0x806d1    | 1         | 0.33%   |
| 0x706e5    | 1         | 0.33%   |
| 0x706a1    | 1         | 0.33%   |
| 0x50654    | 1         | 0.33%   |
| 0x306d4    | 1         | 0.33%   |
| 0x20655    | 1         | 0.33%   |
| 0x10677    | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 36        | 11.88%  |
| Unknown          | 33        | 10.89%  |
| Zen 3            | 23        | 7.59%   |
| IvyBridge        | 23        | 7.59%   |
| Haswell          | 22        | 7.26%   |
| SandyBridge      | 19        | 6.27%   |
| TigerLake        | 17        | 5.61%   |
| Penryn           | 15        | 4.95%   |
| Skylake          | 14        | 4.62%   |
| Zen 2            | 10        | 3.3%    |
| Westmere         | 10        | 3.3%    |
| Piledriver       | 10        | 3.3%    |
| Alderlake Hybrid | 10        | 3.3%    |
| Nehalem          | 7         | 2.31%   |
| K10              | 7         | 2.31%   |
| Zen              | 6         | 1.98%   |
| Icelake          | 6         | 1.98%   |
| Goldmont plus    | 5         | 1.65%   |
| Core             | 5         | 1.65%   |
| Broadwell        | 5         | 1.65%   |
| Zen+             | 4         | 1.32%   |
| K10 Llano        | 3         | 0.99%   |
| Excavator        | 3         | 0.99%   |
| CometLake        | 3         | 0.99%   |
| Bulldozer        | 2         | 0.66%   |
| Steamroller      | 1         | 0.33%   |
| Puma             | 1         | 0.33%   |
| K8 Hammer        | 1         | 0.33%   |
| K8 & K10 hybrid  | 1         | 0.33%   |
| Goldmont         | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 153       | 42.38%  |
| Nvidia                     | 108       | 29.92%  |
| AMD                        | 96        | 26.59%  |
| Matrox Electronics Systems | 4         | 1.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 15        | 4.04%   |
| AMD Lucienne                                                                | 13        | 3.5%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 10        | 2.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 10        | 2.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9         | 2.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 7         | 1.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 6         | 1.62%   |
| Intel HD Graphics 530                                                       | 6         | 1.62%   |
| Intel Core Processor Integrated Graphics Controller                         | 6         | 1.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 6         | 1.62%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5         | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5         | 1.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5         | 1.35%   |
| Intel HD Graphics 630                                                       | 5         | 1.35%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4         | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4         | 1.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 4         | 1.08%   |
| Intel UHD Graphics 620                                                      | 4         | 1.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 4         | 1.08%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 4         | 1.08%   |
| Intel HD Graphics 620                                                       | 4         | 1.08%   |
| Intel HD Graphics 5500                                                      | 4         | 1.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4         | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 4         | 1.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 4         | 1.08%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 4         | 1.08%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                              | 4         | 1.08%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 3         | 0.81%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3         | 0.81%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 0.81%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 3         | 0.81%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                             | 3         | 0.81%   |
| Matrox Electronics Systems MGA G200EH                                       | 3         | 0.81%   |
| Intel Raptor Lake-S UHD Graphics                                            | 3         | 0.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 0.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 0.81%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 3         | 0.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3         | 0.81%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| 1 x Intel        | 106       | 34.75%  |
| 1 x AMD          | 71        | 23.28%  |
| 1 x Nvidia       | 64        | 20.98%  |
| Intel + Nvidia   | 34        | 11.15%  |
| Intel + AMD      | 12        | 3.93%   |
| AMD + Nvidia     | 8         | 2.62%   |
| 2 x AMD          | 5         | 1.64%   |
| 1 x Matrox       | 3         | 0.98%   |
| Nvidia + Matrox  | 1         | 0.33%   |
| AMD + 2 x Nvidia | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 241       | 78.5%   |
| Proprietary | 55        | 17.92%  |
| Unknown     | 11        | 3.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 215       | 69.13%  |
| 1.01-2.0   | 25        | 8.04%   |
| 0.01-0.5   | 25        | 8.04%   |
| 3.01-4.0   | 16        | 5.14%   |
| 7.01-8.0   | 10        | 3.22%   |
| 8.01-16.0  | 7         | 2.25%   |
| 0.51-1.0   | 5         | 1.61%   |
| 5.01-6.0   | 4         | 1.29%   |
| 2.01-3.0   | 2         | 0.64%   |
| 24.01-32.0 | 1         | 0.32%   |
| 16.01-24.0 | 1         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 43        | 12.65%  |
| AU Optronics            | 34        | 10%     |
| BOE                     | 28        | 8.24%   |
| LG Display              | 26        | 7.65%   |
| Goldstar                | 25        | 7.35%   |
| Chimei Innolux          | 25        | 7.35%   |
| Dell                    | 19        | 5.59%   |
| AOC                     | 14        | 4.12%   |
| BenQ                    | 13        | 3.82%   |
| Hewlett-Packard         | 12        | 3.53%   |
| Acer                    | 9         | 2.65%   |
| Lenovo                  | 8         | 2.35%   |
| Sony                    | 6         | 1.76%   |
| Philips                 | 6         | 1.76%   |
| Ancor Communications    | 6         | 1.76%   |
| Sharp                   | 5         | 1.47%   |
| Fujitsu Siemens         | 5         | 1.47%   |
| Chi Mei Optoelectronics | 5         | 1.47%   |
| ViewSonic               | 4         | 1.18%   |
| Unknown                 | 4         | 1.18%   |
| ASUSTek Computer        | 4         | 1.18%   |
| Panasonic               | 3         | 0.88%   |
| Iiyama                  | 3         | 0.88%   |
| Eizo                    | 3         | 0.88%   |
| CSO                     | 3         | 0.88%   |
| Apple                   | 3         | 0.88%   |
| HKC                     | 2         | 0.59%   |
| ___                     | 1         | 0.29%   |
| TTK                     | 1         | 0.29%   |
| Toshiba                 | 1         | 0.29%   |
| Sun                     | 1         | 0.29%   |
| SANYO                   | 1         | 0.29%   |
| RTK                     | 1         | 0.29%   |
| PXO                     | 1         | 0.29%   |
| Plain Tree Systems      | 1         | 0.29%   |
| PANDA                   | 1         | 0.29%   |
| MStar                   | 1         | 0.29%   |
| LSC                     | 1         | 0.29%   |
| LG Electronics          | 1         | 0.29%   |
| IPS                     | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 1.15%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.86%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                       | 3         | 0.86%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                         | 3         | 0.86%   |
| Sony TV *00 SNY4904 3840x2160                                            | 2         | 0.57%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch        | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.57%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.57%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                        | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.57%   |
| BOE LCD Monitor BOE0BB7 3840x2160 381x214mm 17.2-inch                    | 2         | 0.57%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 0.57%   |
| AU Optronics LCD Monitor AUOFA9B 1920x1200 301x188mm 14.0-inch           | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch            | 2         | 0.57%   |
| AOC 2236 AOC2236 1920x1080 477x268mm 21.5-inch                           | 2         | 0.57%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 2         | 0.57%   |
| ___ LCDTV16 ___9000 1360x768                                             | 1         | 0.29%   |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch            | 1         | 0.29%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch            | 1         | 0.29%   |
| ViewSonic VA903 SERIES VSC111E 1280x1024 376x301mm 19.0-inch             | 1         | 0.29%   |
| ViewSonic VA2446 Series VSC732E 1920x1080 521x293mm 23.5-inch            | 1         | 0.29%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                     | 1         | 0.29%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                        | 1         | 0.29%   |
| Unknown LCD Monitor KON TV_MONITOR 1920x1080                             | 1         | 0.29%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 1         | 0.29%   |
| TTK CCL250i TTK8541 1600x1200 408x306mm 20.1-inch                        | 1         | 0.29%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 0.29%   |
| Sun X7149A SUN058A 1600x1200 400x300mm 19.7-inch                         | 1         | 0.29%   |
| Sony TV SNYEE01 1920x1080                                                | 1         | 0.29%   |
| Sony TV SNY2203 1920x1080 560x420mm 27.6-inch                            | 1         | 0.29%   |
| Sony TV *00 SNYF303 1920x1080 1218x685mm 55.0-inch                       | 1         | 0.29%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.29%   |
| Sharp LQ156D1JW04 SHP1436 3840x2160 346x194mm 15.6-inch                  | 1         | 0.29%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch                  | 1         | 0.29%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                  | 1         | 0.29%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 144       | 44.04%  |
| 1366x768 (WXGA)    | 40        | 12.23%  |
| 3840x2160 (4K)     | 33        | 10.09%  |
| 2560x1440 (QHD)    | 15        | 4.59%   |
| 1920x1200 (WUXGA)  | 15        | 4.59%   |
| 1280x1024 (SXGA)   | 15        | 4.59%   |
| 1600x900 (HD+)     | 13        | 3.98%   |
| 1440x900 (WXGA+)   | 10        | 3.06%   |
| 2560x1600          | 6         | 1.83%   |
| 1680x1050 (WSXGA+) | 6         | 1.83%   |
| 1280x800 (WXGA)    | 4         | 1.22%   |
| 3840x1080          | 3         | 0.92%   |
| 2560x1080          | 3         | 0.92%   |
| 1920x540           | 3         | 0.92%   |
| 1600x1200          | 3         | 0.92%   |
| 1024x768 (XGA)     | 3         | 0.92%   |
| Unknown            | 3         | 0.92%   |
| 1360x768           | 2         | 0.61%   |
| 3440x1440          | 1         | 0.31%   |
| 2880x1800          | 1         | 0.31%   |
| 2520x1680          | 1         | 0.31%   |
| 2288x1287          | 1         | 0.31%   |
| 2256x1504          | 1         | 0.31%   |
| 2160x1440          | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 82        | 24.62%  |
| 24      | 36        | 10.81%  |
| 17      | 28        | 8.41%   |
| 27      | 24        | 7.21%   |
| 23      | 20        | 6.01%   |
| 14      | 18        | 5.41%   |
| 21      | 17        | 5.11%   |
| Unknown | 14        | 4.2%    |
| 19      | 13        | 3.9%    |
| 13      | 13        | 3.9%    |
| 31      | 10        | 3%      |
| 16      | 10        | 3%      |
| 72      | 5         | 1.5%    |
| 12      | 5         | 1.5%    |
| 22      | 4         | 1.2%    |
| 18      | 4         | 1.2%    |
| 54      | 3         | 0.9%    |
| 36      | 3         | 0.9%    |
| 34      | 3         | 0.9%    |
| 20      | 3         | 0.9%    |
| 84      | 2         | 0.6%    |
| 32      | 2         | 0.6%    |
| 28      | 2         | 0.6%    |
| 142     | 1         | 0.3%    |
| 86      | 1         | 0.3%    |
| 75      | 1         | 0.3%    |
| 65      | 1         | 0.3%    |
| 52      | 1         | 0.3%    |
| 50      | 1         | 0.3%    |
| 43      | 1         | 0.3%    |
| 40      | 1         | 0.3%    |
| 38      | 1         | 0.3%    |
| 35      | 1         | 0.3%    |
| 33      | 1         | 0.3%    |
| 25      | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 114       | 34.65%  |
| 501-600        | 74        | 22.49%  |
| 351-400        | 36        | 10.94%  |
| 401-500        | 32        | 9.73%   |
| 601-700        | 16        | 4.86%   |
| 201-300        | 14        | 4.26%   |
| Unknown        | 14        | 4.26%   |
| 701-800        | 9         | 2.74%   |
| 1501-2000      | 8         | 2.43%   |
| 1001-1500      | 7         | 2.13%   |
| 801-900        | 3         | 0.91%   |
| More than 2000 | 1         | 0.3%    |
| 901-1000       | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 219       | 72.76%  |
| 16/10   | 43        | 14.29%  |
| 5/4     | 11        | 3.65%   |
| Unknown | 9         | 2.99%   |
| 4/3     | 7         | 2.33%   |
| 21/9    | 4         | 1.33%   |
| 3/2     | 3         | 1%      |
| 6/5     | 2         | 0.66%   |
| 32/9    | 1         | 0.33%   |
| 1.00    | 1         | 0.33%   |
| 0.56    | 1         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 83        | 25.15%  |
| 201-250        | 54        | 16.36%  |
| 81-90          | 25        | 7.58%   |
| 301-350        | 23        | 6.97%   |
| 151-200        | 22        | 6.67%   |
| 351-500        | 20        | 6.06%   |
| 121-130        | 18        | 5.45%   |
| More than 1000 | 16        | 4.85%   |
| 251-300        | 16        | 4.85%   |
| Unknown        | 14        | 4.24%   |
| 111-120        | 9         | 2.73%   |
| 141-150        | 8         | 2.42%   |
| 71-80          | 6         | 1.82%   |
| 501-1000       | 6         | 1.82%   |
| 61-70          | 5         | 1.52%   |
| 131-140        | 5         | 1.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 127       | 39.08%  |
| 121-160       | 83        | 25.54%  |
| 101-120       | 61        | 18.77%  |
| 161-240       | 23        | 7.08%   |
| Unknown       | 14        | 4.31%   |
| 1-50          | 11        | 3.38%   |
| More than 240 | 6         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 233       | 76.14%  |
| 2     | 55        | 17.97%  |
| 0     | 14        | 4.58%   |
| 3     | 4         | 1.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 184       | 39.91%  |
| Intel                             | 150       | 32.54%  |
| Qualcomm Atheros                  | 33        | 7.16%   |
| Broadcom                          | 28        | 6.07%   |
| MediaTek                          | 10        | 2.17%   |
| Broadcom Limited                  | 5         | 1.08%   |
| ASIX Electronics                  | 4         | 0.87%   |
| Ralink Technology                 | 3         | 0.65%   |
| Marvell Technology Group          | 3         | 0.65%   |
| ASUSTek Computer                  | 3         | 0.65%   |
| Aquantia                          | 3         | 0.65%   |
| Xiaomi                            | 2         | 0.43%   |
| Samsung Electronics               | 2         | 0.43%   |
| QLogic                            | 2         | 0.43%   |
| OPPO Electronics                  | 2         | 0.43%   |
| Lenovo                            | 2         | 0.43%   |
| DisplayLink                       | 2         | 0.43%   |
| Dell                              | 2         | 0.43%   |
| D-Link System                     | 2         | 0.43%   |
| Belkin Components                 | 2         | 0.43%   |
| AVM                               | 2         | 0.43%   |
| Wilocity                          | 1         | 0.22%   |
| U-Blox                            | 1         | 0.22%   |
| TP-Link                           | 1         | 0.22%   |
| Sierra Wireless                   | 1         | 0.22%   |
| Ralink                            | 1         | 0.22%   |
| Qualcomm                          | 1         | 0.22%   |
| Nvidia                            | 1         | 0.22%   |
| Mellanox Technologies             | 1         | 0.22%   |
| Linksys                           | 1         | 0.22%   |
| ICS Advent                        | 1         | 0.22%   |
| Huawei Technologies               | 1         | 0.22%   |
| Ericsson Business Mobile Networks | 1         | 0.22%   |
| D-Link                            | 1         | 0.22%   |
| Atmel                             | 1         | 0.22%   |
| American Megatrends               | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 134       | 24.63%  |
| Intel Wi-Fi 6 AX200                                                    | 18        | 3.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 2.39%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11        | 2.02%   |
| Intel Wi-Fi 6 AX201                                                    | 9         | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 1.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 1.47%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 8         | 1.47%   |
| Broadcom BCM43142 802.11b/g/n                                          | 7         | 1.29%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 6         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 1.1%    |
| Intel Wireless 8260                                                    | 6         | 1.1%    |
| Intel Ethernet Connection (2) I219-V                                   | 6         | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 0.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 5         | 0.92%   |
| Intel I211 Gigabit Network Connection                                  | 5         | 0.92%   |
| Intel Ethernet Connection (7) I219-V                                   | 5         | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 0.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 0.92%   |
| Intel 82574L Gigabit Network Connection                                | 5         | 0.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.74%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 4         | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 4         | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.55%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 0.55%   |
| Realtek 802.11ac NIC                                                   | 3         | 0.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 3         | 0.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 0.55%   |
| Intel Wireless 8265 / 8275                                             | 3         | 0.55%   |
| Intel Wireless 7260                                                    | 3         | 0.55%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3         | 0.55%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 3         | 0.55%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.55%   |
| Intel Ethernet Controller I225-V                                       | 3         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 104       | 46.43%  |
| Realtek Semiconductor | 43        | 19.2%   |
| Qualcomm Atheros      | 28        | 12.5%   |
| Broadcom              | 14        | 6.25%   |
| MediaTek              | 10        | 4.46%   |
| Broadcom Limited      | 4         | 1.79%   |
| Ralink Technology     | 3         | 1.34%   |
| ASUSTek Computer      | 3         | 1.34%   |
| Dell                  | 2         | 0.89%   |
| D-Link System         | 2         | 0.89%   |
| Belkin Components     | 2         | 0.89%   |
| AVM                   | 2         | 0.89%   |
| Wilocity              | 1         | 0.45%   |
| TP-Link               | 1         | 0.45%   |
| Sierra Wireless       | 1         | 0.45%   |
| Ralink                | 1         | 0.45%   |
| Qualcomm              | 1         | 0.45%   |
| Linksys               | 1         | 0.45%   |
| D-Link                | 1         | 0.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 18        | 8%      |
| Intel Wi-Fi 6 AX201                                                     | 9         | 4%      |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 8         | 3.56%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 3.11%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 6         | 2.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.67%   |
| Intel Wireless 8260                                                     | 6         | 2.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 5         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 2.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 2.22%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.78%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 4         | 1.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.33%   |
| Realtek 802.11ac NIC                                                    | 3         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.33%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.33%   |
| Intel Wireless 7260                                                     | 3         | 1.33%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 3         | 1.33%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 3         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.33%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.89%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 2         | 0.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.89%   |
| Realtek RTL8187 Wireless Adapter                                        | 2         | 0.89%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.89%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 0.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.89%   |
| Intel Wireless 7265                                                     | 2         | 0.89%   |
| Intel Wireless 3165                                                     | 2         | 0.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 166       | 54.97%  |
| Intel                    | 84        | 27.81%  |
| Broadcom                 | 18        | 5.96%   |
| Qualcomm Atheros         | 8         | 2.65%   |
| ASIX Electronics         | 4         | 1.32%   |
| Marvell Technology Group | 3         | 0.99%   |
| Aquantia                 | 3         | 0.99%   |
| Xiaomi                   | 2         | 0.66%   |
| Samsung Electronics      | 2         | 0.66%   |
| OPPO Electronics         | 2         | 0.66%   |
| Lenovo                   | 2         | 0.66%   |
| DisplayLink              | 2         | 0.66%   |
| QLogic                   | 1         | 0.33%   |
| Nvidia                   | 1         | 0.33%   |
| ICS Advent               | 1         | 0.33%   |
| Huawei Technologies      | 1         | 0.33%   |
| Broadcom Limited         | 1         | 0.33%   |
| American Megatrends      | 1         | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 134       | 42.81%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 13        | 4.15%   |
| Realtek RTL8125 2.5GbE Controller                                              | 11        | 3.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 2.56%   |
| Intel Ethernet Connection (2) I219-V                                           | 6         | 1.92%   |
| Intel I211 Gigabit Network Connection                                          | 5         | 1.6%    |
| Intel Ethernet Connection (7) I219-V                                           | 5         | 1.6%    |
| Intel 82574L Gigabit Network Connection                                        | 5         | 1.6%    |
| Intel Ethernet Connection (7) I219-LM                                          | 4         | 1.28%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 4         | 1.28%   |
| Realtek Killer E2600 GbE Controller                                            | 3         | 0.96%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 0.96%   |
| Intel Ethernet Controller I225-V                                               | 3         | 0.96%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.96%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 0.96%   |
| Intel Ethernet Connection (14) I219-V                                          | 3         | 0.96%   |
| Intel Ethernet Connection (13) I219-V                                          | 3         | 0.96%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.96%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.96%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.64%   |
| Intel Ethernet Controller I226-V                                               | 2         | 0.64%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.64%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.64%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.64%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 0.64%   |
| Intel 82567LF Gigabit Network Connection                                       | 2         | 0.64%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 2         | 0.64%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 2         | 0.64%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 2         | 0.64%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2         | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.32%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.32%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.32%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 279       | 56.59%  |
| WiFi     | 208       | 42.19%  |
| Modem    | 3         | 0.61%   |
| Unknown  | 3         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 180       | 57.32%  |
| WiFi     | 134       | 42.68%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 160       | 52.81%  |
| 1     | 126       | 41.58%  |
| 3     | 9         | 2.97%   |
| 5     | 2         | 0.66%   |
| 4     | 2         | 0.66%   |
| 0     | 2         | 0.66%   |
| 8     | 1         | 0.33%   |
| 6     | 1         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 185       | 60.66%  |
| Yes  | 120       | 39.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 46.2%   |
| Realtek Semiconductor           | 27        | 14.67%  |
| Cambridge Silicon Radio         | 13        | 7.07%   |
| Foxconn / Hon Hai               | 9         | 4.89%   |
| Qualcomm Atheros Communications | 8         | 4.35%   |
| Broadcom                        | 8         | 4.35%   |
| Lite-On Technology              | 6         | 3.26%   |
| IMC Networks                    | 5         | 2.72%   |
| Hewlett-Packard                 | 4         | 2.17%   |
| Dell                            | 4         | 2.17%   |
| TP-Link                         | 3         | 1.63%   |
| Apple                           | 3         | 1.63%   |
| MediaTek                        | 2         | 1.09%   |
| Foxconn International           | 2         | 1.09%   |
| ASUSTek Computer                | 2         | 1.09%   |
| USI                             | 1         | 0.54%   |
| Realtek                         | 1         | 0.54%   |
| Integrated System Solution      | 1         | 0.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                               | 18        | 9.78%   |
| Intel AX200 Bluetooth                                 | 18        | 9.78%   |
| Intel AX201 Bluetooth                                 | 17        | 9.24%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 13        | 7.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 11        | 5.98%   |
| Intel Bluetooth Device                                | 10        | 5.43%   |
| Intel Bluetooth wireless interface                    | 8         | 4.35%   |
| Intel AX210 Bluetooth                                 | 8         | 4.35%   |
| Intel AX211 Bluetooth                                 | 7         | 3.8%    |
| TP-Link UB500 Adapter                                 | 3         | 1.63%   |
| Realtek  Bluetooth 4.2 Adapter                        | 3         | 1.63%   |
| Realtek 802.11ac WLAN Adapter                         | 3         | 1.63%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 3         | 1.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 3         | 1.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3         | 1.63%   |
| IMC Networks Wireless_Device                          | 3         | 1.63%   |
| HP Broadcom 2070 Bluetooth Combo                      | 3         | 1.63%   |
| Foxconn / Hon Hai Wireless_Device                     | 3         | 1.63%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 3         | 1.63%   |
| Qualcomm Atheros  Bluetooth Device                    | 2         | 1.09%   |
| MediaTek Wireless_Device                              | 2         | 1.09%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2         | 1.09%   |
| Foxconn International BCM43142A0 Bluetooth module     | 2         | 1.09%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 2         | 1.09%   |
| Apple Bluetooth USB Host Controller                   | 2         | 1.09%   |
| USI Bluetooth Device                                  | 1         | 0.54%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 1         | 0.54%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.54%   |
| Realtek RTL8723B Bluetooth                            | 1         | 0.54%   |
| Realtek Bluetooth Radio                               | 1         | 0.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1         | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.54%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1         | 0.54%   |
| Lite-On Wireless_Device                               | 1         | 0.54%   |
| Lite-On Bluetooth Device                              | 1         | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                      | 1         | 0.54%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 0.54%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.54%   |
| IMC Networks Bluetooth Module                         | 1         | 0.54%   |
| IMC Networks Bluetooth Device                         | 1         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 200       | 46.3%   |
| AMD                                  | 111       | 25.69%  |
| Nvidia                               | 75        | 17.36%  |
| C-Media Electronics                  | 10        | 2.31%   |
| Logitech                             | 3         | 0.69%   |
| Creative Labs                        | 3         | 0.69%   |
| ASUSTek Computer                     | 3         | 0.69%   |
| Texas Instruments                    | 2         | 0.46%   |
| Lenovo                               | 2         | 0.46%   |
| DSEA A/S                             | 2         | 0.46%   |
| Yamaha                               | 1         | 0.23%   |
| VIA Technologies                     | 1         | 0.23%   |
| TX                                   | 1         | 0.23%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.23%   |
| Sony                                 | 1         | 0.23%   |
| Schiit Audio                         | 1         | 0.23%   |
| RODE Microphones                     | 1         | 0.23%   |
| Realtek Semiconductor                | 1         | 0.23%   |
| Plantronics                          | 1         | 0.23%   |
| ONN                                  | 1         | 0.23%   |
| Micro Star International             | 1         | 0.23%   |
| Kingston Technology                  | 1         | 0.23%   |
| HiBy                                 | 1         | 0.23%   |
| GN Netcom                            | 1         | 0.23%   |
| Generalplus Technology               | 1         | 0.23%   |
| FiiO Electronics Technology          | 1         | 0.23%   |
| Elgato Systems                       | 1         | 0.23%   |
| Cambridge Audio                      | 1         | 0.23%   |
| BR25                                 | 1         | 0.23%   |
| ASRock                               | 1         | 0.23%   |
| Arturia                              | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 43        | 8.4%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 30        | 5.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21        | 4.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 17        | 3.32%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15        | 2.93%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 2.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 2.54%   |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 2.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 2.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.15%   |
| Nvidia Audio device                                                        | 10        | 1.95%   |
| AMD FCH Azalia Controller                                                  | 8         | 1.56%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 1.37%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.37%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7         | 1.37%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 1.17%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 0.98%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 0.98%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 5         | 0.98%   |
| Intel Raptor Lake High Definition Audio Controller                         | 5         | 0.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 0.98%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5         | 0.98%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5         | 0.98%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 0.98%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 0.98%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 0.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 0.98%   |
| Nvidia TU104 HD Audio Controller                                           | 4         | 0.78%   |
| Nvidia GP108 High Definition Audio Controller                              | 4         | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.78%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 0.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 0.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 0.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 23.02%  |
| Micron Technology   | 20        | 14.39%  |
| SK hynix            | 19        | 13.67%  |
| Kingston            | 19        | 13.67%  |
| Corsair             | 13        | 9.35%   |
| Unknown             | 8         | 5.76%   |
| Crucial             | 5         | 3.6%    |
| G.Skill             | 4         | 2.88%   |
| Unknown (ABCD)      | 2         | 1.44%   |
| Team                | 2         | 1.44%   |
| Smart               | 2         | 1.44%   |
| Hewlett-Packard     | 2         | 1.44%   |
| Elpida              | 2         | 1.44%   |
| A-DATA Technology   | 2         | 1.44%   |
| Unknown             | 2         | 1.44%   |
| Unknown (0x0B45)    | 1         | 0.72%   |
| Silicon Power       | 1         | 0.72%   |
| Nanya Technology    | 1         | 0.72%   |
| Lexar               | 1         | 0.72%   |
| GOODRAM             | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 3.4%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 2.04%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 1.36%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 1.36%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 2         | 1.36%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.36%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s            | 2         | 1.36%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.36%   |
| Unknown                                                          | 2         | 1.36%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                        | 1         | 0.68%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.68%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s                        | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM                                      | 1         | 0.68%   |
| Unknown (0x0B45) RAM WPBH32D408SWM-16G 16GB SODIMM DDR4 3200MT/s | 1         | 0.68%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3200MT/s               | 1         | 0.68%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.68%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 1         | 0.68%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s           | 1         | 0.68%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.68%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.68%   |
| SK hynix RAM HMT325U6CFR8C-H9 2048MB DIMM 1333MT/s               | 1         | 0.68%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 0.68%   |
| SK hynix RAM HMAA1GU6CJR6N-XN 8192MB DIMM DDR4 3200MT/s          | 1         | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.68%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s             | 1         | 0.68%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.68%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.68%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.68%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.68%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s             | 1         | 0.68%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.68%   |
| SK hynix RAM H58G78BK7BX114 8GB SODIMM LPDDR5 6400MT/s           | 1         | 0.68%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 1         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 72        | 58.54%  |
| DDR3    | 24        | 19.51%  |
| DDR5    | 7         | 5.69%   |
| LPDDR5  | 5         | 4.07%   |
| LPDDR4  | 5         | 4.07%   |
| SDRAM   | 3         | 2.44%   |
| DDR2    | 3         | 2.44%   |
| Unknown | 2         | 1.63%   |
| LPDDR3  | 1         | 0.81%   |
| DDR     | 1         | 0.81%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 63        | 51.22%  |
| DIMM         | 49        | 39.84%  |
| Row Of Chips | 11        | 8.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 57        | 43.85%  |
| 16384 | 28        | 21.54%  |
| 4096  | 21        | 16.15%  |
| 2048  | 15        | 11.54%  |
| 32768 | 8         | 6.15%   |
| 49152 | 1         | 0.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 40        | 30.3%   |
| 2667    | 16        | 12.12%  |
| 1600    | 14        | 10.61%  |
| 2400    | 11        | 8.33%   |
| 1333    | 7         | 5.3%    |
| 5600    | 5         | 3.79%   |
| 2133    | 5         | 3.79%   |
| 6400    | 4         | 3.03%   |
| 1867    | 3         | 2.27%   |
| 1334    | 3         | 2.27%   |
| 800     | 3         | 2.27%   |
| 4800    | 2         | 1.52%   |
| 4267    | 2         | 1.52%   |
| 3600    | 2         | 1.52%   |
| 2933    | 2         | 1.52%   |
| 7500    | 1         | 0.76%   |
| 3866    | 1         | 0.76%   |
| 3800    | 1         | 0.76%   |
| 3666    | 1         | 0.76%   |
| 3534    | 1         | 0.76%   |
| 3266    | 1         | 0.76%   |
| 3066    | 1         | 0.76%   |
| 3000    | 1         | 0.76%   |
| 2048    | 1         | 0.76%   |
| 1067    | 1         | 0.76%   |
| 975     | 1         | 0.76%   |
| 533     | 1         | 0.76%   |
| Unknown | 1         | 0.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Seiko Epson           | 5         | 26.32%  |
| Hewlett-Packard       | 5         | 26.32%  |
| Brother Industries    | 5         | 26.32%  |
| Xerox                 | 1         | 5.26%   |
| Samsung Electronics   | 1         | 5.26%   |
| Pantum                | 1         | 5.26%   |
| Lexmark International | 1         | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Xerox WorkCentre 3220            | 1         | 5.26%   |
| Seiko Epson XP-4200 Series       | 1         | 5.26%   |
| Seiko Epson XP-4100 Series       | 1         | 5.26%   |
| Seiko Epson WF-4830 Series       | 1         | 5.26%   |
| Seiko Epson L300 Series          | 1         | 5.26%   |
| Seiko Epson ET-2820 Series       | 1         | 5.26%   |
| Samsung Phaser 3121              | 1         | 5.26%   |
| Pantum P2200-series              | 1         | 5.26%   |
| Lexmark International MC3224dwe  | 1         | 5.26%   |
| HP OfficeJet 6950                | 1         | 5.26%   |
| HP LaserJet 1200                 | 1         | 5.26%   |
| HP LaserJet 1018                 | 1         | 5.26%   |
| HP Ink Tank 310 series           | 1         | 5.26%   |
| HP DeskJet 4100 series           | 1         | 5.26%   |
| Brother Printer                  | 1         | 5.26%   |
| Brother MFC-7360N                | 1         | 5.26%   |
| Brother HL-L3230CDW series       | 1         | 5.26%   |
| Brother DCP-L2520DW              | 1         | 5.26%   |
| Brother DCP-7057 scanner/printer | 1         | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 50%     |
| Canon CanoScan LiDE 220                       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 33        | 21.29%  |
| IMC Networks                           | 14        | 9.03%   |
| Logitech                               | 11        | 7.1%    |
| Bison Electronics                      | 11        | 7.1%    |
| Microdia                               | 9         | 5.81%   |
| Realtek Semiconductor                  | 8         | 5.16%   |
| Quanta                                 | 8         | 5.16%   |
| Syntek                                 | 7         | 4.52%   |
| Sunplus Innovation Technology          | 7         | 4.52%   |
| Suyin                                  | 6         | 3.87%   |
| Luxvisions Innotech Limited            | 6         | 3.87%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.23%   |
| Primax Electronics                     | 3         | 1.94%   |
| Generalplus Technology                 | 3         | 1.94%   |
| Apple                                  | 3         | 1.94%   |
| Acer                                   | 3         | 1.94%   |
| Z-Star Microelectronics                | 2         | 1.29%   |
| Sonix Technology                       | 2         | 1.29%   |
| Microsoft                              | 2         | 1.29%   |
| Trust                                  | 1         | 0.65%   |
| SunplusIT                              | 1         | 0.65%   |
| Sunplus Technology                     | 1         | 0.65%   |
| Samsung Electronics                    | 1         | 0.65%   |
| Ricoh                                  | 1         | 0.65%   |
| Lite-On Technology                     | 1         | 0.65%   |
| Lenovo                                 | 1         | 0.65%   |
| Jieli Technology                       | 1         | 0.65%   |
| Importek                               | 1         | 0.65%   |
| icSpring                               | 1         | 0.65%   |
| Creative Technology                    | 1         | 0.65%   |
| ALi                                    | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 8         | 5.16%   |
| Syntek Integrated Camera                                    | 6         | 3.87%   |
| IMC Networks Integrated Camera                              | 6         | 3.87%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 2.58%   |
| Microdia Integrated_Webcam_HD                               | 4         | 2.58%   |
| Bison BisonCam,NB Pro                                       | 4         | 2.58%   |
| Realtek Integrated_Webcam_HD                                | 3         | 1.94%   |
| Primax HP HD Webcam [Fixed]                                 | 3         | 1.94%   |
| Generalplus CAMERA - UVC                                    | 3         | 1.94%   |
| Chicony USB2.0 Camera                                       | 3         | 1.94%   |
| Chicony HD User Facing                                      | 3         | 1.94%   |
| Quanta VGA WebCam                                           | 2         | 1.29%   |
| Quanta HP TrueVision HD Camera                              | 2         | 1.29%   |
| Quanta HD User Facing                                       | 2         | 1.29%   |
| Microsoft LifeCam HD-3000                                   | 2         | 1.29%   |
| Microdia Integrated Webcam                                  | 2         | 1.29%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera        | 2         | 1.29%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 2         | 1.29%   |
| Logitech Webcam C270                                        | 2         | 1.29%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 1.29%   |
| Chicony HP HD Camera                                        | 2         | 1.29%   |
| Chicony HD WebCam                                           | 2         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 1.29%   |
| Bison Integrated Camera                                     | 2         | 1.29%   |
| Bison HD Webcam                                             | 2         | 1.29%   |
| Acer Lenovo Integrated Webcam                               | 2         | 1.29%   |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 0.65%   |
| Z-Star Integrated Camera                                    | 1         | 0.65%   |
| Trust WB-6250X Webcam                                       | 1         | 0.65%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.65%   |
| Suyin USB 2.0 UVC 1.3M WebCam                               | 1         | 0.65%   |
| Suyin Sony Visual Communication Camera                      | 1         | 0.65%   |
| Suyin Integrated Webcam                                     | 1         | 0.65%   |
| Suyin HP Truevision HD                                      | 1         | 0.65%   |
| Suyin HP ENVY HD Webcam                                     | 1         | 0.65%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.65%   |
| SunplusIT 1080p FHD Camera                                  | 1         | 0.65%   |
| Sunplus 1.3M HD WebCam                                      | 1         | 0.65%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 0.65%   |
| Sunplus Laptop Integrated Webcam HD                         | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 32%     |
| Validity Sensors           | 6         | 24%     |
| Shenzhen Goodix Technology | 4         | 16%     |
| Upek                       | 3         | 12%     |
| AuthenTec                  | 3         | 12%     |
| Next Biometrics            | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 4         | 16%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 12%     |
| Shenzhen Goodix  FingerPrint Device                    | 3         | 12%     |
| Validity Sensors Synaptics WBDI                        | 2         | 8%      |
| AuthenTec AES2810                                      | 2         | 8%      |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4%      |
| Validity Sensors VFS491                                | 1         | 4%      |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4%      |
| Synaptics UWP WBDI Device                              | 1         | 4%      |
| Synaptics UWP WBDI                                     | 1         | 4%      |
| Synaptics  WBDI                                        | 1         | 4%      |
| Synaptics Fingerprint scanner                          | 1         | 4%      |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 4%      |
| Next Biometrics NB-2020-U Fingerprint Reader           | 1         | 4%      |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 8         | 47.06%  |
| Alcor Micro      | 5         | 29.41%  |
| Upek             | 1         | 5.88%   |
| SCM Microsystems | 1         | 5.88%   |
| O2 Micro         | 1         | 5.88%   |
| CHERRY           | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 29.41%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 17.65%  |
| Broadcom 58200                                                               | 3         | 17.65%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 11.76%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.88%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 5.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.88%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 205       | 66.34%  |
| 1     | 80        | 25.89%  |
| 2     | 21        | 6.8%    |
| 3     | 3         | 0.97%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 32        | 25.81%  |
| Fingerprint reader       | 25        | 20.16%  |
| Net/wireless             | 21        | 16.94%  |
| Chipcard                 | 15        | 12.1%   |
| Multimedia controller    | 9         | 7.26%   |
| Sound                    | 8         | 6.45%   |
| Camera                   | 4         | 3.23%   |
| Card reader              | 3         | 2.42%   |
| Net/ethernet             | 2         | 1.61%   |
| Unassigned class         | 1         | 0.81%   |
| Network                  | 1         | 0.81%   |
| Modem                    | 1         | 0.81%   |
| Communication controller | 1         | 0.81%   |
| Bluetooth                | 1         | 0.81%   |

