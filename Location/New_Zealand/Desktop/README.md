Linux in New Zealand - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in New Zealand.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 366

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z68MA-D2H-B3                | [4956d72048](https://linux-hardware.org/?probe=4956d72048) | Aug 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [163affcbb8](https://linux-hardware.org/?probe=163affcbb8) | Aug 01, 2022 |
| HP            | 8054                        | [3b76696319](https://linux-hardware.org/?probe=3b76696319) | Jul 27, 2022 |
| Intel         | STK1AW32SC H91596-307       | [78225ba5b9](https://linux-hardware.org/?probe=78225ba5b9) | Jul 21, 2022 |
| HP            | 3397                        | [83bdaea8fc](https://linux-hardware.org/?probe=83bdaea8fc) | Jul 17, 2022 |
| Gigabyte      | H87M-D3H                    | [5056c4f640](https://linux-hardware.org/?probe=5056c4f640) | Jul 13, 2022 |
| Gigabyte      | B460M D3H                   | [d620225518](https://linux-hardware.org/?probe=d620225518) | Jun 30, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [86a93d8ea0](https://linux-hardware.org/?probe=86a93d8ea0) | Jun 29, 2022 |
| Alienware     | 01NYPT A00                  | [97b8d855bd](https://linux-hardware.org/?probe=97b8d855bd) | Jun 28, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [fd93206df4](https://linux-hardware.org/?probe=fd93206df4) | Jun 27, 2022 |
| Dell          | 0XHGV1 A01                  | [9d9ae107c9](https://linux-hardware.org/?probe=9d9ae107c9) | Jun 25, 2022 |
| ASRock        | X370 Taichi                 | [788acf13f2](https://linux-hardware.org/?probe=788acf13f2) | Jun 24, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [d11995947a](https://linux-hardware.org/?probe=d11995947a) | Jun 23, 2022 |
| Dell          | 0XHGV1 A01                  | [656f558626](https://linux-hardware.org/?probe=656f558626) | Jun 23, 2022 |
| HP            | 18E7                        | [2fd690b3b4](https://linux-hardware.org/?probe=2fd690b3b4) | Jun 22, 2022 |
| ASUSTek       | H97M-PLUS                   | [874c85b694](https://linux-hardware.org/?probe=874c85b694) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [38bf9d2a7b](https://linux-hardware.org/?probe=38bf9d2a7b) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a2e10758ca](https://linux-hardware.org/?probe=a2e10758ca) | May 13, 2022 |
| HP            | 1998                        | [b717b34f5b](https://linux-hardware.org/?probe=b717b34f5b) | May 08, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [6693954f79](https://linux-hardware.org/?probe=6693954f79) | May 07, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | [2553bf03d1](https://linux-hardware.org/?probe=2553bf03d1) | May 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | [03a7fc3c23](https://linux-hardware.org/?probe=03a7fc3c23) | May 05, 2022 |
| ASUSTek       | B150M PRO GAMING            | [a31ab08668](https://linux-hardware.org/?probe=a31ab08668) | May 04, 2022 |
| MSI           | MAG B550M MORTAR            | [c994128afd](https://linux-hardware.org/?probe=c994128afd) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7e84138ea1](https://linux-hardware.org/?probe=7e84138ea1) | Apr 29, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [8888cb88d3](https://linux-hardware.org/?probe=8888cb88d3) | Apr 22, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [78a785e4a9](https://linux-hardware.org/?probe=78a785e4a9) | Apr 15, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [5ec598483e](https://linux-hardware.org/?probe=5ec598483e) | Apr 14, 2022 |
| ASUSTek       | PRIME B450M-A               | [d4295c9a47](https://linux-hardware.org/?probe=d4295c9a47) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [3ddf8a6825](https://linux-hardware.org/?probe=3ddf8a6825) | Apr 11, 2022 |
| HP            | 1790                        | [5fd16b3e1e](https://linux-hardware.org/?probe=5fd16b3e1e) | Apr 03, 2022 |
| Dell          | 0M017G A00                  | [a7ee814f3a](https://linux-hardware.org/?probe=a7ee814f3a) | Apr 02, 2022 |
| Dell          | 0M863N A01                  | [c05eaeb499](https://linux-hardware.org/?probe=c05eaeb499) | Mar 24, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [cf9c727b0d](https://linux-hardware.org/?probe=cf9c727b0d) | Mar 24, 2022 |
| ASUSTek       | P5E                         | [ec2b80980d](https://linux-hardware.org/?probe=ec2b80980d) | Mar 18, 2022 |
| Gigabyte      | B560M DS3H AC               | [64f278889f](https://linux-hardware.org/?probe=64f278889f) | Mar 13, 2022 |
| HP            | 2ADC                        | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| Gigabyte      | B460M DS3H AC               | [5a570f493c](https://linux-hardware.org/?probe=5a570f493c) | Mar 06, 2022 |
| Gigabyte      | H110M-H-CF                  | [5c169a1d32](https://linux-hardware.org/?probe=5c169a1d32) | Feb 25, 2022 |
| ASRock        | B450M Steel Legend          | [dfebbb508b](https://linux-hardware.org/?probe=dfebbb508b) | Feb 24, 2022 |
| ASRock        | B450M Steel Legend          | [26729d3227](https://linux-hardware.org/?probe=26729d3227) | Feb 22, 2022 |
| HP            | 2AF7                        | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| ASUSTek       | P6X58D-E                    | [c7a12417f1](https://linux-hardware.org/?probe=c7a12417f1) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [cc2c71140b](https://linux-hardware.org/?probe=cc2c71140b) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [4d1d42c8cc](https://linux-hardware.org/?probe=4d1d42c8cc) | Feb 20, 2022 |
| ASRock        | B450M Steel Legend          | [024513d4a8](https://linux-hardware.org/?probe=024513d4a8) | Feb 18, 2022 |
| ASRock        | B450M Steel Legend          | [9bc33ce91e](https://linux-hardware.org/?probe=9bc33ce91e) | Feb 16, 2022 |
| ASRock        | B450M Steel Legend          | [cc420f69ce](https://linux-hardware.org/?probe=cc420f69ce) | Feb 16, 2022 |
| ASUSTek       | P8B75-M                     | [caf1721ebe](https://linux-hardware.org/?probe=caf1721ebe) | Feb 12, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [24bd4956b6](https://linux-hardware.org/?probe=24bd4956b6) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d8ec503f66](https://linux-hardware.org/?probe=d8ec503f66) | Jan 21, 2022 |
| MediaVue      | MV-890GX V1.2               | [201163da2f](https://linux-hardware.org/?probe=201163da2f) | Jan 16, 2022 |
| Gigabyte      | X570S AERO G                | [fc3f2a485a](https://linux-hardware.org/?probe=fc3f2a485a) | Jan 08, 2022 |
| Gigabyte      | Z77X-D3H                    | [44cbef1c02](https://linux-hardware.org/?probe=44cbef1c02) | Dec 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [51f97b7e46](https://linux-hardware.org/?probe=51f97b7e46) | Dec 25, 2021 |
| Gigabyte      | B460M DS3H AC               | [7bde1c408f](https://linux-hardware.org/?probe=7bde1c408f) | Dec 21, 2021 |
| Colorful T... | BATTLE-AX B450M-G DELUXE... | [52614e9f8d](https://linux-hardware.org/?probe=52614e9f8d) | Dec 19, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [a6ddae1f31](https://linux-hardware.org/?probe=a6ddae1f31) | Dec 15, 2021 |
| Intel         | DQ87PG AAG74154-403         | [e2a6d57861](https://linux-hardware.org/?probe=e2a6d57861) | Dec 13, 2021 |
| Huanan        | X99-F8 V2.0                 | [71f69762fe](https://linux-hardware.org/?probe=71f69762fe) | Dec 08, 2021 |
| Dell          | 0M863N A01                  | [01a565720c](https://linux-hardware.org/?probe=01a565720c) | Dec 04, 2021 |
| Gigabyte      | B75M-D3H                    | [939cd87ee7](https://linux-hardware.org/?probe=939cd87ee7) | Nov 22, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [e2bb3dc142](https://linux-hardware.org/?probe=e2bb3dc142) | Nov 21, 2021 |
| HP            | 3396                        | [db69ec8696](https://linux-hardware.org/?probe=db69ec8696) | Nov 17, 2021 |
| HP            | 3396                        | [70fc3e699a](https://linux-hardware.org/?probe=70fc3e699a) | Nov 17, 2021 |
| ASUSTek       | P8Z77-V                     | [c7a18968cf](https://linux-hardware.org/?probe=c7a18968cf) | Nov 03, 2021 |
| MSI           | MAG B365M MORTAR            | [95e40c6343](https://linux-hardware.org/?probe=95e40c6343) | Oct 30, 2021 |
| MSI           | MAG B365M MORTAR            | [f2ce1a8260](https://linux-hardware.org/?probe=f2ce1a8260) | Oct 26, 2021 |
| Gigabyte      | H97M-D3H                    | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| ASUSTek       | PRIME B560-PLUS             | [97bd114229](https://linux-hardware.org/?probe=97bd114229) | Oct 23, 2021 |
| Gigabyte      | B75M-D3H                    | [74c2c9d725](https://linux-hardware.org/?probe=74c2c9d725) | Oct 22, 2021 |
| IBM           | 81Y7071 SVT-R               | [033203aade](https://linux-hardware.org/?probe=033203aade) | Oct 16, 2021 |
| Gigabyte      | B365M HD3                   | [26e0d9a3d9](https://linux-hardware.org/?probe=26e0d9a3d9) | Oct 16, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [530994c225](https://linux-hardware.org/?probe=530994c225) | Oct 11, 2021 |
| MSI           | 2AE0                        | [e5ede0905a](https://linux-hardware.org/?probe=e5ede0905a) | Oct 10, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [55620348e7](https://linux-hardware.org/?probe=55620348e7) | Oct 08, 2021 |
| Dell          | 0D6H9T A02                  | [42b9320d55](https://linux-hardware.org/?probe=42b9320d55) | Oct 06, 2021 |
| Gigabyte      | X570 UD                     | [636ef76e1e](https://linux-hardware.org/?probe=636ef76e1e) | Oct 05, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | [5a7e6805d3](https://linux-hardware.org/?probe=5a7e6805d3) | Oct 02, 2021 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [ca8c02f319](https://linux-hardware.org/?probe=ca8c02f319) | Sep 29, 2021 |
| JGINYUE       | H97I PLUS V2.0              | [2e66de23a2](https://linux-hardware.org/?probe=2e66de23a2) | Sep 28, 2021 |
| Dell          | 0D6H9T A02                  | [30e914656e](https://linux-hardware.org/?probe=30e914656e) | Sep 27, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [fb59bae064](https://linux-hardware.org/?probe=fb59bae064) | Sep 23, 2021 |
| HP            | 3398                        | [2b8efc01ba](https://linux-hardware.org/?probe=2b8efc01ba) | Sep 22, 2021 |
| HP            | 3398                        | [18b064d0d6](https://linux-hardware.org/?probe=18b064d0d6) | Sep 22, 2021 |
| HP            | 1905                        | [56945cef9c](https://linux-hardware.org/?probe=56945cef9c) | Sep 19, 2021 |
| ASRock        | 970 Pro3 R2.0               | [d172a59c18](https://linux-hardware.org/?probe=d172a59c18) | Sep 14, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [a7e1713e87](https://linux-hardware.org/?probe=a7e1713e87) | Sep 11, 2021 |
| Intel         | DG33BU AAD79951-407         | [69bbaa38d9](https://linux-hardware.org/?probe=69bbaa38d9) | Sep 08, 2021 |
| ASUSTek       | P6X58D-E                    | [cf4c0a5a4d](https://linux-hardware.org/?probe=cf4c0a5a4d) | Aug 28, 2021 |
| ASRock        | 990FX Killer                | [6dd735449b](https://linux-hardware.org/?probe=6dd735449b) | Aug 27, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [badc363516](https://linux-hardware.org/?probe=badc363516) | Aug 26, 2021 |
| HP            | 304Ah                       | [0898c11493](https://linux-hardware.org/?probe=0898c11493) | Aug 19, 2021 |
| Gigabyte      | G41M-ES2L                   | [996054b23c](https://linux-hardware.org/?probe=996054b23c) | Aug 18, 2021 |
| HP            | 3397                        | [a3425b956c](https://linux-hardware.org/?probe=a3425b956c) | Aug 14, 2021 |
| MSI           | MS-7028 10B                 | [d9d570cae6](https://linux-hardware.org/?probe=d9d570cae6) | Aug 12, 2021 |
| Gigabyte      | Z68AP-D3                    | [8e107590a6](https://linux-hardware.org/?probe=8e107590a6) | Aug 09, 2021 |
| ASUSTek       | P6X58D-E                    | [bd3b6b4f35](https://linux-hardware.org/?probe=bd3b6b4f35) | Jul 28, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [cd88f96d38](https://linux-hardware.org/?probe=cd88f96d38) | Jul 26, 2021 |
| Gigabyte      | 990FXA-UD3                  | [215f44bec5](https://linux-hardware.org/?probe=215f44bec5) | Jul 24, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [120f3a158c](https://linux-hardware.org/?probe=120f3a158c) | Jul 21, 2021 |
| Gigabyte      | H81M-HD3                    | [72cf6d1ac2](https://linux-hardware.org/?probe=72cf6d1ac2) | Jul 20, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [f410d6449b](https://linux-hardware.org/?probe=f410d6449b) | Jul 19, 2021 |
| MSI           | MS-7028 10B                 | [2c536a7e90](https://linux-hardware.org/?probe=2c536a7e90) | Jul 18, 2021 |
| MSI           | MS-7028 10B                 | [4077783ab8](https://linux-hardware.org/?probe=4077783ab8) | Jul 17, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9339298035](https://linux-hardware.org/?probe=9339298035) | Jul 14, 2021 |
| Gigabyte      | P55-UD3                     | [6431c6f93c](https://linux-hardware.org/?probe=6431c6f93c) | Jul 12, 2021 |
| Gigabyte      | P55-UD3                     | [ac267d27d6](https://linux-hardware.org/?probe=ac267d27d6) | Jul 12, 2021 |
| HP            | 1497                        | [eecafd7c6c](https://linux-hardware.org/?probe=eecafd7c6c) | Jul 09, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [e3ee4893c9](https://linux-hardware.org/?probe=e3ee4893c9) | Jul 07, 2021 |
| ASRock        | A320M-HDV                   | [841fb32f2d](https://linux-hardware.org/?probe=841fb32f2d) | Jul 05, 2021 |
| ASUSTek       | Z97M-PLUS                   | [9b30ecd00d](https://linux-hardware.org/?probe=9b30ecd00d) | Jul 03, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [7926c787f0](https://linux-hardware.org/?probe=7926c787f0) | Jun 28, 2021 |
| Gigabyte      | B150M-D3H-CF                | [02924c7c01](https://linux-hardware.org/?probe=02924c7c01) | Jun 25, 2021 |
| ASRock        | 970 Pro3 R2.0               | [8ed5dab80e](https://linux-hardware.org/?probe=8ed5dab80e) | Jun 22, 2021 |
| Lenovo        | ThinkCentre M58p 7479RS2    | [0a417745c3](https://linux-hardware.org/?probe=0a417745c3) | Jun 20, 2021 |
| ASUSTek       | P5GC-MX/1333                | [79b90a017a](https://linux-hardware.org/?probe=79b90a017a) | Jun 15, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [259f649837](https://linux-hardware.org/?probe=259f649837) | Jun 13, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [b8540739ff](https://linux-hardware.org/?probe=b8540739ff) | Jun 12, 2021 |
| ASRock        | X370 Taichi                 | [15b3d9a238](https://linux-hardware.org/?probe=15b3d9a238) | Jun 10, 2021 |
| ASRock        | X370 Taichi                 | [1ad5e88410](https://linux-hardware.org/?probe=1ad5e88410) | Jun 10, 2021 |
| ASRock        | N68-S UCC                   | [155ac9e15e](https://linux-hardware.org/?probe=155ac9e15e) | Jun 09, 2021 |
| Dell          | 0GDG8Y A00                  | [90c9163323](https://linux-hardware.org/?probe=90c9163323) | Jun 07, 2021 |
| Dell          | 0GDG8Y A00                  | [bebce06283](https://linux-hardware.org/?probe=bebce06283) | Jun 07, 2021 |
| MSI           | MS-7125                     | [66e6adf1ec](https://linux-hardware.org/?probe=66e6adf1ec) | Jun 04, 2021 |
| Dell          | 0GDG8Y A00                  | [7bc9fd5174](https://linux-hardware.org/?probe=7bc9fd5174) | Jun 04, 2021 |
| Dell          | 0RCPW3 A03                  | [536202a82c](https://linux-hardware.org/?probe=536202a82c) | May 22, 2021 |
| Dell          | 0RCPW3 A03                  | [ea6ed65a9e](https://linux-hardware.org/?probe=ea6ed65a9e) | May 20, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [363912f531](https://linux-hardware.org/?probe=363912f531) | May 14, 2021 |
| Gigabyte      | H470 HD3                    | [fb5a619781](https://linux-hardware.org/?probe=fb5a619781) | May 10, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [dcd72d6f14](https://linux-hardware.org/?probe=dcd72d6f14) | May 08, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [f409c90490](https://linux-hardware.org/?probe=f409c90490) | May 01, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fbb7ce2f8b](https://linux-hardware.org/?probe=fbb7ce2f8b) | Apr 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [04a24d00e5](https://linux-hardware.org/?probe=04a24d00e5) | Apr 30, 2021 |
| Gigabyte      | B150M-D3H-CF                | [4ea82584ae](https://linux-hardware.org/?probe=4ea82584ae) | Apr 23, 2021 |
| Gigabyte      | B550M DS3H                  | [3193d396aa](https://linux-hardware.org/?probe=3193d396aa) | Apr 22, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | [190824abc9](https://linux-hardware.org/?probe=190824abc9) | Apr 16, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [9c114a5942](https://linux-hardware.org/?probe=9c114a5942) | Apr 15, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [e23906e5f0](https://linux-hardware.org/?probe=e23906e5f0) | Apr 15, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | [d998403a6d](https://linux-hardware.org/?probe=d998403a6d) | Apr 14, 2021 |
| HP            | 304Ah                       | [92d8929cdf](https://linux-hardware.org/?probe=92d8929cdf) | Apr 10, 2021 |
| Lenovo        | ThinkCentre A57 9704A36     | [cdde4de4ea](https://linux-hardware.org/?probe=cdde4de4ea) | Apr 05, 2021 |
| Gigabyte      | Z77X-D3H                    | [1343705e98](https://linux-hardware.org/?probe=1343705e98) | Apr 05, 2021 |
| Gigabyte      | Z87M-D3H                    | [aaa8a98fce](https://linux-hardware.org/?probe=aaa8a98fce) | Apr 02, 2021 |
| ASRock        | N68-S UCC                   | [e566e1d5a2](https://linux-hardware.org/?probe=e566e1d5a2) | Mar 31, 2021 |
| Intel         | DQ45CB AAE30148-207         | [7f8e7a4f95](https://linux-hardware.org/?probe=7f8e7a4f95) | Mar 28, 2021 |
| ASUSTek       | KCMA-D8                     | [df17b4ced6](https://linux-hardware.org/?probe=df17b4ced6) | Mar 20, 2021 |
| ASRock        | N68-S UCC                   | [15e00c5d4a](https://linux-hardware.org/?probe=15e00c5d4a) | Mar 20, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [402cbaf164](https://linux-hardware.org/?probe=402cbaf164) | Mar 15, 2021 |
| HP            | 3399                        | [ca3f4aa75a](https://linux-hardware.org/?probe=ca3f4aa75a) | Mar 15, 2021 |
| HP            | 3399                        | [08dbcb0c9c](https://linux-hardware.org/?probe=08dbcb0c9c) | Mar 15, 2021 |
| ASRock        | B450M Steel Legend          | [e4dca1478e](https://linux-hardware.org/?probe=e4dca1478e) | Mar 14, 2021 |
| Gigabyte      | EP45-DS3L                   | [cf36728751](https://linux-hardware.org/?probe=cf36728751) | Mar 08, 2021 |
| Dell          | 002KVM A00                  | [84dbce50b0](https://linux-hardware.org/?probe=84dbce50b0) | Mar 06, 2021 |
| Gigabyte      | GA-970A-D3                  | [ed941773ff](https://linux-hardware.org/?probe=ed941773ff) | Mar 05, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [57d8b65b84](https://linux-hardware.org/?probe=57d8b65b84) | Mar 04, 2021 |
| Gigabyte      | B75M-D3H                    | [ff15fd93df](https://linux-hardware.org/?probe=ff15fd93df) | Mar 01, 2021 |
| MSI           | MS-7125                     | [3bab98fcf2](https://linux-hardware.org/?probe=3bab98fcf2) | Feb 25, 2021 |
| Gigabyte      | H77M-D3H                    | [3ffa3067b0](https://linux-hardware.org/?probe=3ffa3067b0) | Feb 24, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [0b85af69c2](https://linux-hardware.org/?probe=0b85af69c2) | Feb 23, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [5d129c6417](https://linux-hardware.org/?probe=5d129c6417) | Feb 23, 2021 |
| MSI           | B450M MORTAR MAX            | [97b32c8185](https://linux-hardware.org/?probe=97b32c8185) | Feb 22, 2021 |
| HP            | 1495                        | [7e0c673361](https://linux-hardware.org/?probe=7e0c673361) | Feb 17, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [d7508c8abc](https://linux-hardware.org/?probe=d7508c8abc) | Feb 16, 2021 |
| Supermicro    | X8SIL                       | [b7ead0e2d5](https://linux-hardware.org/?probe=b7ead0e2d5) | Feb 16, 2021 |
| MSI           | MS-7125                     | [104c9a719f](https://linux-hardware.org/?probe=104c9a719f) | Feb 16, 2021 |
| ASUSTek       | P8Z68-V                     | [bfeecd13dd](https://linux-hardware.org/?probe=bfeecd13dd) | Feb 15, 2021 |
| ASUSTek       | P8Z68-V                     | [ced39cce40](https://linux-hardware.org/?probe=ced39cce40) | Feb 15, 2021 |
| ASUSTek       | P5GC-MX/1333                | [eded5967ea](https://linux-hardware.org/?probe=eded5967ea) | Feb 15, 2021 |
| ASUSTek       | P6TD DELUXE                 | [4db8ac896d](https://linux-hardware.org/?probe=4db8ac896d) | Feb 15, 2021 |
| Dell          | 0DFRFW A01                  | [308dadd545](https://linux-hardware.org/?probe=308dadd545) | Feb 12, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [6bee16fdd6](https://linux-hardware.org/?probe=6bee16fdd6) | Feb 08, 2021 |
| ASUSTek       | P6X58D-E                    | [65ca4b3fd8](https://linux-hardware.org/?probe=65ca4b3fd8) | Feb 08, 2021 |
| IBM           | 94Y7718 SIT                 | [f45bb4d28d](https://linux-hardware.org/?probe=f45bb4d28d) | Feb 02, 2021 |
| IBM           | 94Y7718 SIT                 | [4eda682182](https://linux-hardware.org/?probe=4eda682182) | Feb 01, 2021 |
| HP            | 82FE 11                     | [e0890897e2](https://linux-hardware.org/?probe=e0890897e2) | Jan 24, 2021 |
| HP            | 82FE 11                     | [f11621cd76](https://linux-hardware.org/?probe=f11621cd76) | Jan 24, 2021 |
| Gigabyte      | X58A-UD5                    | [e6bc960206](https://linux-hardware.org/?probe=e6bc960206) | Jan 05, 2021 |
| HP            | 304Ah                       | [484bc076eb](https://linux-hardware.org/?probe=484bc076eb) | Jan 03, 2021 |
| MSI           | B450M MORTAR MAX            | [cff3edf070](https://linux-hardware.org/?probe=cff3edf070) | Dec 22, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [da31ffedd3](https://linux-hardware.org/?probe=da31ffedd3) | Dec 19, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [365cef4ed3](https://linux-hardware.org/?probe=365cef4ed3) | Dec 18, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [da5b8f33d0](https://linux-hardware.org/?probe=da5b8f33d0) | Dec 14, 2020 |
| Gigabyte      | 970A-D3P                    | [59bb1dc077](https://linux-hardware.org/?probe=59bb1dc077) | Dec 09, 2020 |
| ASRock        | 960GM-VGS3 FX               | [d98dd8c58b](https://linux-hardware.org/?probe=d98dd8c58b) | Dec 06, 2020 |
| Lenovo        | 310C SDK0J40709 WIN 3259... | [9fed57ace1](https://linux-hardware.org/?probe=9fed57ace1) | Dec 03, 2020 |
| Lenovo        | 310C SDK0J40709 WIN 3259... | [1e4de9cf24](https://linux-hardware.org/?probe=1e4de9cf24) | Dec 03, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [6c7616d830](https://linux-hardware.org/?probe=6c7616d830) | Nov 30, 2020 |
| Gigabyte      | B450M S2H                   | [f420bcff80](https://linux-hardware.org/?probe=f420bcff80) | Nov 29, 2020 |
| HP            | 304Ah                       | [879eecaa2c](https://linux-hardware.org/?probe=879eecaa2c) | Nov 24, 2020 |
| HP            | 304Ah                       | [8822926229](https://linux-hardware.org/?probe=8822926229) | Nov 24, 2020 |
| Gigabyte      | Z68AP-D3                    | [b861a3897c](https://linux-hardware.org/?probe=b861a3897c) | Nov 24, 2020 |
| Gigabyte      | Z68AP-D3                    | [6693dd023e](https://linux-hardware.org/?probe=6693dd023e) | Nov 23, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [0343088b2c](https://linux-hardware.org/?probe=0343088b2c) | Nov 20, 2020 |
| MSI           | B450M MORTAR MAX            | [9fb23cbe75](https://linux-hardware.org/?probe=9fb23cbe75) | Nov 17, 2020 |
| ASUSTek       | PRIME X399-A                | [b32b7c28e2](https://linux-hardware.org/?probe=b32b7c28e2) | Nov 17, 2020 |
| Gigabyte      | A520M DS3H AC               | [163ddf8d0b](https://linux-hardware.org/?probe=163ddf8d0b) | Nov 16, 2020 |
| Dell          | 042P49 A00                  | [e88a5663df](https://linux-hardware.org/?probe=e88a5663df) | Nov 15, 2020 |
| Gigabyte      | B450M S2H                   | [b77ab61c1d](https://linux-hardware.org/?probe=b77ab61c1d) | Nov 10, 2020 |
| Gigabyte      | B450M S2H                   | [b2054d891d](https://linux-hardware.org/?probe=b2054d891d) | Nov 10, 2020 |
| HP            | 304Ah                       | [b306a58bbe](https://linux-hardware.org/?probe=b306a58bbe) | Nov 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [424e7b661d](https://linux-hardware.org/?probe=424e7b661d) | Nov 06, 2020 |
| Gigabyte      | H55M-USB3                   | [d8003cd392](https://linux-hardware.org/?probe=d8003cd392) | Nov 01, 2020 |
| Gigabyte      | H55M-USB3                   | [eeca2887d3](https://linux-hardware.org/?probe=eeca2887d3) | Nov 01, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [66e528143c](https://linux-hardware.org/?probe=66e528143c) | Oct 31, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [4d5717bdb1](https://linux-hardware.org/?probe=4d5717bdb1) | Oct 26, 2020 |
| Gigabyte      | H87M-D3H                    | [50cdb98356](https://linux-hardware.org/?probe=50cdb98356) | Oct 26, 2020 |
| HP            | ProLiant ML350 G6           | [862c82ee17](https://linux-hardware.org/?probe=862c82ee17) | Oct 26, 2020 |
| Gigabyte      | F2A75M-D3H                  | [7851a0c8a4](https://linux-hardware.org/?probe=7851a0c8a4) | Oct 21, 2020 |
| HP            | 3396                        | [df383be5cf](https://linux-hardware.org/?probe=df383be5cf) | Oct 20, 2020 |
| HP            | 8055                        | [9cabb3c0e9](https://linux-hardware.org/?probe=9cabb3c0e9) | Oct 18, 2020 |
| Gigabyte      | B550M DS3H                  | [f5fdcbbf41](https://linux-hardware.org/?probe=f5fdcbbf41) | Oct 15, 2020 |
| Gigabyte      | F2A75M-D3H                  | [222313e9d4](https://linux-hardware.org/?probe=222313e9d4) | Oct 06, 2020 |
| ASRock        | AB350M Pro4                 | [d8f8b18b1f](https://linux-hardware.org/?probe=d8f8b18b1f) | Oct 06, 2020 |
| ASRock        | B450M Steel Legend          | [a01b2e0545](https://linux-hardware.org/?probe=a01b2e0545) | Sep 30, 2020 |
| Gigabyte      | H77M-D3H                    | [42e057fc77](https://linux-hardware.org/?probe=42e057fc77) | Sep 29, 2020 |
| Gigabyte      | H77M-D3H                    | [4737809a8c](https://linux-hardware.org/?probe=4737809a8c) | Sep 16, 2020 |
| ASUSTek       | Maximus VII HERO            | [c5f5fd0a14](https://linux-hardware.org/?probe=c5f5fd0a14) | Sep 12, 2020 |
| MSI           | B450M MORTAR MAX            | [aacb67377f](https://linux-hardware.org/?probe=aacb67377f) | Sep 03, 2020 |
| ASRock        | B450M Steel Legend          | [b8d61937bc](https://linux-hardware.org/?probe=b8d61937bc) | Sep 03, 2020 |
| ASRock        | A320M-HDV                   | [3b6586255c](https://linux-hardware.org/?probe=3b6586255c) | Sep 03, 2020 |
| Gigabyte      | Z77MX-D3H                   | [c5c33f3570](https://linux-hardware.org/?probe=c5c33f3570) | Aug 31, 2020 |
| HP            | 8055                        | [55806cdf5c](https://linux-hardware.org/?probe=55806cdf5c) | Aug 30, 2020 |
| ASRock        | X370 Taichi                 | [8cf31213d6](https://linux-hardware.org/?probe=8cf31213d6) | Aug 26, 2020 |
| HP            | 339A                        | [8b33d851ce](https://linux-hardware.org/?probe=8b33d851ce) | Aug 20, 2020 |
| HP            | 3398                        | [ab1609f338](https://linux-hardware.org/?probe=ab1609f338) | Aug 13, 2020 |
| Supermicro    | X8SIL                       | [bdee911e92](https://linux-hardware.org/?probe=bdee911e92) | Aug 12, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [89f99d81f3](https://linux-hardware.org/?probe=89f99d81f3) | Aug 12, 2020 |
| Gigabyte      | H81M-DS2                    | [9902d7243c](https://linux-hardware.org/?probe=9902d7243c) | Aug 07, 2020 |
| ASUSTek       | Z97M-PLUS                   | [b895b895f3](https://linux-hardware.org/?probe=b895b895f3) | Aug 04, 2020 |
| HP            | 1998                        | [f9df3fb967](https://linux-hardware.org/?probe=f9df3fb967) | Jul 31, 2020 |
| HP            | 18E7                        | [6c1c183fc6](https://linux-hardware.org/?probe=6c1c183fc6) | Jul 31, 2020 |
| ASUSTek       | P5E3 Deluxe                 | [0355090a1c](https://linux-hardware.org/?probe=0355090a1c) | Jul 31, 2020 |
| Gigabyte      | H81M-HD3                    | [4b574045ce](https://linux-hardware.org/?probe=4b574045ce) | Jul 30, 2020 |
| Gigabyte      | H81M-HD3                    | [8b5a82ed70](https://linux-hardware.org/?probe=8b5a82ed70) | Jul 29, 2020 |
| Gigabyte      | H81M-DS2                    | [b17cece7fd](https://linux-hardware.org/?probe=b17cece7fd) | Jul 24, 2020 |
| HP            | 1998                        | [aa54cd9e2c](https://linux-hardware.org/?probe=aa54cd9e2c) | Jul 22, 2020 |
| Gigabyte      | AB350-Gaming-CF             | [db6c2584ca](https://linux-hardware.org/?probe=db6c2584ca) | Jul 15, 2020 |
| Unknown       | MNIC8PI                     | [0f24f7650f](https://linux-hardware.org/?probe=0f24f7650f) | Jul 13, 2020 |
| HP            | 212B                        | [9b5c44d526](https://linux-hardware.org/?probe=9b5c44d526) | Jul 10, 2020 |
| ASRock        | X370 Taichi                 | [4a4c813642](https://linux-hardware.org/?probe=4a4c813642) | Jul 08, 2020 |
| Gigabyte      | F2A75M-D3H                  | [67339ac7fd](https://linux-hardware.org/?probe=67339ac7fd) | Jul 05, 2020 |
| Lenovo        | MAHOBAY NOK                 | [61948190fd](https://linux-hardware.org/?probe=61948190fd) | Jul 01, 2020 |
| ASRock        | X370 Taichi                 | [803ec85b14](https://linux-hardware.org/?probe=803ec85b14) | Jun 30, 2020 |
| Gigabyte      | 970A-D3P                    | [55e71afa91](https://linux-hardware.org/?probe=55e71afa91) | Jun 29, 2020 |
| Biostar       | A68N-5000                   | [33f0f081e9](https://linux-hardware.org/?probe=33f0f081e9) | Jun 27, 2020 |
| Gigabyte      | F2A75M-D3H                  | [8f67a7b83f](https://linux-hardware.org/?probe=8f67a7b83f) | Jun 18, 2020 |
| Acer          | Aspire XC-704G              | [3a13e1d14a](https://linux-hardware.org/?probe=3a13e1d14a) | Jun 12, 2020 |
| Acer          | Aspire XC-704G              | [3fd600b32c](https://linux-hardware.org/?probe=3fd600b32c) | Jun 12, 2020 |
| ASRock        | Z87 Killer                  | [edb30202da](https://linux-hardware.org/?probe=edb30202da) | Jun 10, 2020 |
| Gigabyte      | 970A-D3P                    | [cd7ee5a475](https://linux-hardware.org/?probe=cd7ee5a475) | Jun 06, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [4e7221a789](https://linux-hardware.org/?probe=4e7221a789) | Jun 06, 2020 |
| Gigabyte      | H81M-DS2                    | [4d45a85cae](https://linux-hardware.org/?probe=4d45a85cae) | Jun 06, 2020 |
| Gigabyte      | X58A-UD7                    | [2e81a03c85](https://linux-hardware.org/?probe=2e81a03c85) | Jun 01, 2020 |
| Gigabyte      | X58A-UD7                    | [004ae34d21](https://linux-hardware.org/?probe=004ae34d21) | Jun 01, 2020 |
| Gigabyte      | 970A-D3P                    | [83ba796d11](https://linux-hardware.org/?probe=83ba796d11) | Jun 01, 2020 |
| ASRock        | Z77 Extreme4                | [2e074b7913](https://linux-hardware.org/?probe=2e074b7913) | May 30, 2020 |
| ASUSTek       | ROG Maximus XI FORMULA      | [2892347213](https://linux-hardware.org/?probe=2892347213) | May 25, 2020 |
| ASUSTek       | M2N68-AM                    | [dbaf375be0](https://linux-hardware.org/?probe=dbaf375be0) | May 22, 2020 |
| HP            | 3396                        | [6ac1ff7341](https://linux-hardware.org/?probe=6ac1ff7341) | May 19, 2020 |
| HP            | 21B4 A01                    | [a787f75e19](https://linux-hardware.org/?probe=a787f75e19) | May 19, 2020 |
| HP            | 3396                        | [236a304cab](https://linux-hardware.org/?probe=236a304cab) | May 19, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [df2b313ce9](https://linux-hardware.org/?probe=df2b313ce9) | May 17, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [01e35cb482](https://linux-hardware.org/?probe=01e35cb482) | May 17, 2020 |
| Gigabyte      | 970A-D3P                    | [973e075347](https://linux-hardware.org/?probe=973e075347) | May 15, 2020 |
| Intel         | DG31PR AAD97573-202         | [5558e7aa8c](https://linux-hardware.org/?probe=5558e7aa8c) | May 14, 2020 |
| ASUSTek       | H110M-A                     | [b865ea9cea](https://linux-hardware.org/?probe=b865ea9cea) | May 12, 2020 |
| ASUSTek       | H110M-A                     | [e8880c2c12](https://linux-hardware.org/?probe=e8880c2c12) | May 12, 2020 |
| Lenovo        | ThinkCentre M58p 7479RS2    | [569705d7d7](https://linux-hardware.org/?probe=569705d7d7) | May 10, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [050a2216f8](https://linux-hardware.org/?probe=050a2216f8) | May 10, 2020 |
| Lenovo        | ThinkCentre M58p 7483AC4    | [65dc50f256](https://linux-hardware.org/?probe=65dc50f256) | May 05, 2020 |
| Gigabyte      | H77M-D3H                    | [3c0cbfbf66](https://linux-hardware.org/?probe=3c0cbfbf66) | May 04, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [c1760ffe1b](https://linux-hardware.org/?probe=c1760ffe1b) | Apr 30, 2020 |
| ASUSTek       | M3A78-EM                    | [5d4f28e58b](https://linux-hardware.org/?probe=5d4f28e58b) | Apr 29, 2020 |
| HP            | 1495                        | [a1f532749d](https://linux-hardware.org/?probe=a1f532749d) | Apr 25, 2020 |
| ASUSTek       | Maximus VII HERO            | [ab309746a3](https://linux-hardware.org/?probe=ab309746a3) | Apr 23, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [ae8010c021](https://linux-hardware.org/?probe=ae8010c021) | Apr 21, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [b67554882d](https://linux-hardware.org/?probe=b67554882d) | Apr 19, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [3a29b79970](https://linux-hardware.org/?probe=3a29b79970) | Apr 18, 2020 |
| Pegatron      | 2A99                        | [23eb1431c9](https://linux-hardware.org/?probe=23eb1431c9) | Apr 13, 2020 |
| ASUSTek       | M2N68-AM                    | [60aac968a5](https://linux-hardware.org/?probe=60aac968a5) | Apr 06, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [3005d3d129](https://linux-hardware.org/?probe=3005d3d129) | Apr 05, 2020 |
| ASUSTek       | PRIME B350M-A               | [7ec6fbac2b](https://linux-hardware.org/?probe=7ec6fbac2b) | Mar 29, 2020 |
| ASUSTek       | H81M-K                      | [8805131c92](https://linux-hardware.org/?probe=8805131c92) | Mar 27, 2020 |
| ASUSTek       | PRIME B350M-A               | [a39b2c1a02](https://linux-hardware.org/?probe=a39b2c1a02) | Mar 27, 2020 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [20fcc93972](https://linux-hardware.org/?probe=20fcc93972) | Mar 22, 2020 |
| ASUSTek       | M2N68-AM                    | [0d0cb38926](https://linux-hardware.org/?probe=0d0cb38926) | Mar 15, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [de4392a815](https://linux-hardware.org/?probe=de4392a815) | Mar 08, 2020 |
| Gigabyte      | H77M-D3H                    | [76a4b4dc8c](https://linux-hardware.org/?probe=76a4b4dc8c) | Mar 08, 2020 |
| HP            | 1998                        | [4976d49be8](https://linux-hardware.org/?probe=4976d49be8) | Feb 13, 2020 |
| HP            | 1496                        | [d031f2ddb3](https://linux-hardware.org/?probe=d031f2ddb3) | Feb 02, 2020 |
| Gigabyte      | P67A-UD3R-B3                | [56653049b3](https://linux-hardware.org/?probe=56653049b3) | Jan 25, 2020 |
| Intel         | DB75EN AAG39650-400         | [9829bf7442](https://linux-hardware.org/?probe=9829bf7442) | Jan 25, 2020 |
| Intel         | DB75EN AAG39650-400         | [7d5c355cec](https://linux-hardware.org/?probe=7d5c355cec) | Jan 25, 2020 |
| ASUSTek       | PRIME X470-PRO              | [bfacbe4d23](https://linux-hardware.org/?probe=bfacbe4d23) | Jan 18, 2020 |
| HP            | 1998                        | [d3cafd611f](https://linux-hardware.org/?probe=d3cafd611f) | Jan 17, 2020 |
| ASUSTek       | PRIME X470-PRO              | [a766080680](https://linux-hardware.org/?probe=a766080680) | Jan 11, 2020 |
| Dell          | 0TCYKM A00                  | [dc961a7541](https://linux-hardware.org/?probe=dc961a7541) | Jan 11, 2020 |
| Dell          | 0TCYKM A00                  | [fbe7233d08](https://linux-hardware.org/?probe=fbe7233d08) | Jan 11, 2020 |
| Gigabyte      | P67A-UD3R-B3                | [9670dcf2cf](https://linux-hardware.org/?probe=9670dcf2cf) | Jan 10, 2020 |
| Lenovo        | 0837A85                     | [70b8f03213](https://linux-hardware.org/?probe=70b8f03213) | Jan 08, 2020 |
| HP            | 1998                        | [bebd400cf6](https://linux-hardware.org/?probe=bebd400cf6) | Jan 05, 2020 |
| Intel         | DQ57TM AAE70931-403         | [e8d5ed783b](https://linux-hardware.org/?probe=e8d5ed783b) | Jan 05, 2020 |
| Intel         | DQ57TM AAE70931-403         | [4b841fa47f](https://linux-hardware.org/?probe=4b841fa47f) | Jan 05, 2020 |
| Lenovo        | 0837A85                     | [444269a73d](https://linux-hardware.org/?probe=444269a73d) | Jan 04, 2020 |
| Gigabyte      | P67A-UD3R-B3                | [04dde34cd2](https://linux-hardware.org/?probe=04dde34cd2) | Dec 30, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a0231b59de](https://linux-hardware.org/?probe=a0231b59de) | Dec 30, 2019 |
| ASUSTek       | PRIME B350M-A               | [4ed3a4a663](https://linux-hardware.org/?probe=4ed3a4a663) | Dec 24, 2019 |
| Acer          | Aspire X3470                | [4d5a234113](https://linux-hardware.org/?probe=4d5a234113) | Dec 01, 2019 |
| HP            | ProLiant ML330 G6           | [df7a5ac424](https://linux-hardware.org/?probe=df7a5ac424) | Nov 26, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [dba8a4e258](https://linux-hardware.org/?probe=dba8a4e258) | Nov 15, 2019 |
| ASRock        | H110M-HDV                   | [6a3d4aeb04](https://linux-hardware.org/?probe=6a3d4aeb04) | Nov 13, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [53a489591d](https://linux-hardware.org/?probe=53a489591d) | Nov 09, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [9bcd5c3692](https://linux-hardware.org/?probe=9bcd5c3692) | Nov 09, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [a40193b9fb](https://linux-hardware.org/?probe=a40193b9fb) | Nov 01, 2019 |
| Acer          | Aspire X3470                | [bb12fa0496](https://linux-hardware.org/?probe=bb12fa0496) | Oct 27, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [590377c04a](https://linux-hardware.org/?probe=590377c04a) | Oct 25, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [7b02110be5](https://linux-hardware.org/?probe=7b02110be5) | Oct 17, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [023414eea0](https://linux-hardware.org/?probe=023414eea0) | Oct 10, 2019 |
| OEM           | H81U                        | [cd430ca9b3](https://linux-hardware.org/?probe=cd430ca9b3) | Oct 10, 2019 |
| ASUSTek       | P7P55D-E LX                 | [efc5587c83](https://linux-hardware.org/?probe=efc5587c83) | Oct 04, 2019 |
| Unknown       | Unknown                     | [daa8a7d137](https://linux-hardware.org/?probe=daa8a7d137) | Oct 03, 2019 |
| ASUSTek       | P7P55D-E LX                 | [ef7d61dbd6](https://linux-hardware.org/?probe=ef7d61dbd6) | Oct 01, 2019 |
| ASUSTek       | P7P55D-E LX                 | [a8134f553c](https://linux-hardware.org/?probe=a8134f553c) | Oct 01, 2019 |
| Dell          | 0Y958C A00                  | [f5b1443aa9](https://linux-hardware.org/?probe=f5b1443aa9) | Sep 29, 2019 |
| ASUSTek       | PRIME Z270-AR               | [11473758bd](https://linux-hardware.org/?probe=11473758bd) | Sep 29, 2019 |
| ASUSTek       | ROG Maximus XI FORMULA      | [6de2802483](https://linux-hardware.org/?probe=6de2802483) | Sep 22, 2019 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [3da3a9d9ad](https://linux-hardware.org/?probe=3da3a9d9ad) | Sep 18, 2019 |
| HP            | 1497                        | [51c0a64a32](https://linux-hardware.org/?probe=51c0a64a32) | Sep 14, 2019 |
| ASUSTek       | ROG Maximus XI FORMULA      | [fbac50573d](https://linux-hardware.org/?probe=fbac50573d) | Sep 12, 2019 |
| ASUSTek       | ROG Maximus XI FORMULA      | [a86676d54b](https://linux-hardware.org/?probe=a86676d54b) | Sep 12, 2019 |
| HP            | 1998                        | [5c09dfef4e](https://linux-hardware.org/?probe=5c09dfef4e) | Sep 07, 2019 |
| HP            | 1998                        | [08674f223f](https://linux-hardware.org/?probe=08674f223f) | Sep 01, 2019 |
| MSI           | B250M PRO-VH                | [520d23673a](https://linux-hardware.org/?probe=520d23673a) | Aug 20, 2019 |
| ASUSTek       | P7P55D-E PRO                | [00d0b17230](https://linux-hardware.org/?probe=00d0b17230) | Aug 10, 2019 |
| ASUSTek       | TUF X299 MARK 2             | [3a0644689a](https://linux-hardware.org/?probe=3a0644689a) | Aug 10, 2019 |
| ASUSTek       | P7P55D-E PRO                | [27f23cfc02](https://linux-hardware.org/?probe=27f23cfc02) | Aug 10, 2019 |
| ASRock        | Z97 Extreme6                | [cc9738c393](https://linux-hardware.org/?probe=cc9738c393) | Jul 21, 2019 |
| ASUSTek       | PRIME Z370-P                | [57bc67a21b](https://linux-hardware.org/?probe=57bc67a21b) | Jul 21, 2019 |
| Gigabyte      | P67A-UD3-B3                 | [68241fdb6a](https://linux-hardware.org/?probe=68241fdb6a) | Jul 17, 2019 |
| Gigabyte      | GA-K8NF-9                   | [556ae96f13](https://linux-hardware.org/?probe=556ae96f13) | Jul 17, 2019 |
| Gigabyte      | Z97X-UD3H-CF                | [2ddbcf3d21](https://linux-hardware.org/?probe=2ddbcf3d21) | Jul 06, 2019 |
| ASUSTek       | ROG ZENITH EXTREME          | [5f582a0578](https://linux-hardware.org/?probe=5f582a0578) | Jun 29, 2019 |
| ASUSTek       | P5G41T-M LE                 | [ad98351c8d](https://linux-hardware.org/?probe=ad98351c8d) | Jun 20, 2019 |
| HP            | 304Ah                       | [617269b6e1](https://linux-hardware.org/?probe=617269b6e1) | Jun 01, 2019 |
| Gigabyte      | F2A55M-DS2                  | [09bcc236c3](https://linux-hardware.org/?probe=09bcc236c3) | May 31, 2019 |
| AAEON         | UP-APL01 V0.4               | [6f498d9d7d](https://linux-hardware.org/?probe=6f498d9d7d) | May 28, 2019 |
| Gigabyte      | F2A55M-DS2                  | [e7e92370e2](https://linux-hardware.org/?probe=e7e92370e2) | May 24, 2019 |
| MSI           | IONA                        | [bb5e8345c0](https://linux-hardware.org/?probe=bb5e8345c0) | May 16, 2019 |
| OEM           | H81U                        | [17cab2af03](https://linux-hardware.org/?probe=17cab2af03) | May 08, 2019 |
| HP            | 304Ah                       | [055c45cffd](https://linux-hardware.org/?probe=055c45cffd) | May 05, 2019 |
| MSI           | IONA                        | [68df9179a1](https://linux-hardware.org/?probe=68df9179a1) | Apr 30, 2019 |
| Gigabyte      | F2A55M-DS2                  | [f47857828a](https://linux-hardware.org/?probe=f47857828a) | Apr 10, 2019 |
| ASRock        | N3700-ITX                   | [d79cedb01e](https://linux-hardware.org/?probe=d79cedb01e) | Apr 02, 2019 |
| Gigabyte      | 970A-D3P                    | [a4c7d814b0](https://linux-hardware.org/?probe=a4c7d814b0) | Mar 19, 2019 |
| HP            | 1496                        | [4e44453a25](https://linux-hardware.org/?probe=4e44453a25) | Mar 10, 2019 |
| ASUSTek       | H81M-K                      | [320985bb4c](https://linux-hardware.org/?probe=320985bb4c) | Mar 10, 2019 |
| HP            | 1496                        | [260f13dbef](https://linux-hardware.org/?probe=260f13dbef) | Mar 03, 2019 |
| Gigabyte      | H81M-S2H                    | [d56268e6dd](https://linux-hardware.org/?probe=d56268e6dd) | Feb 02, 2019 |
| Unknown       | Unknown                     | [2ad7f7c63c](https://linux-hardware.org/?probe=2ad7f7c63c) | Jan 08, 2019 |
| ASUSTek       | H81M-K                      | [6501d739bb](https://linux-hardware.org/?probe=6501d739bb) | Dec 16, 2018 |
| ASRock        | 970 Pro3 R2.0               | [43e0d718d9](https://linux-hardware.org/?probe=43e0d718d9) | Dec 03, 2018 |
| ASRock        | 970 Pro3 R2.0               | [d86366c2d9](https://linux-hardware.org/?probe=d86366c2d9) | Dec 03, 2018 |
| HP            | 83E1                        | [6676ac3581](https://linux-hardware.org/?probe=6676ac3581) | Nov 20, 2018 |
| Gigabyte      | AB350-Gaming-CF             | [6fad0c649d](https://linux-hardware.org/?probe=6fad0c649d) | Nov 17, 2018 |
| Gigabyte      | H77M-D3H                    | [9e6f5f9def](https://linux-hardware.org/?probe=9e6f5f9def) | Nov 08, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 34       | 13.65%  |
| Ubuntu 18.04                 | 32       | 12.85%  |
| Pop!_OS 20.10                | 9        | 3.61%   |
| Pop!_OS 20.04                | 8        | 3.21%   |
| Ubuntu 20.10                 | 7        | 2.81%   |
| Linux Mint 20.1              | 7        | 2.81%   |
| Ubuntu 21.04                 | 6        | 2.41%   |
| Ubuntu 18.10                 | 6        | 2.41%   |
| Manjaro                      | 6        | 2.41%   |
| Pop!_OS 21.10                | 5        | 2.01%   |
| Pop!_OS 21.04                | 5        | 2.01%   |
| KDE neon 20.04               | 5        | 2.01%   |
| Fedora 34                    | 5        | 2.01%   |
| Arch Rolling                 | 5        | 2.01%   |
| Ubuntu 22.04                 | 4        | 1.61%   |
| Ubuntu 16.04                 | 4        | 1.61%   |
| Linux Mint 20.3              | 4        | 1.61%   |
| Fedora 33                    | 4        | 1.61%   |
| Debian 10                    | 4        | 1.61%   |
| Zorin 16                     | 3        | 1.2%    |
| Ubuntu 21.10                 | 3        | 1.2%    |
| Ubuntu 19.10                 | 3        | 1.2%    |
| Ubuntu 19.04                 | 3        | 1.2%    |
| OpenMandriva 4.2             | 3        | 1.2%    |
| Linux Mint 20.2              | 3        | 1.2%    |
| Fedora 36                    | 3        | 1.2%    |
| Fedora 31                    | 3        | 1.2%    |
| ROSA R11                     | 2        | 0.8%    |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 0.8%    |
| OpenMandriva 4.3             | 2        | 0.8%    |
| Lubuntu 20.04                | 2        | 0.8%    |
| Linux Mint 20                | 2        | 0.8%    |
| Linux Mint 19.3              | 2        | 0.8%    |
| Linux Mint 19                | 2        | 0.8%    |
| Kubuntu 20.04                | 2        | 0.8%    |
| KDE neon 18.04               | 2        | 0.8%    |
| Fedora 35                    | 2        | 0.8%    |
| Fedora 32                    | 2        | 0.8%    |
| Fedora 30                    | 2        | 0.8%    |
| Endless 3.8.4                | 2        | 0.8%    |
| Endless 3.7.3                | 2        | 0.8%    |
| Devuan 4                     | 2        | 0.8%    |
| Arch                         | 2        | 0.8%    |
| Zorin 15                     | 1        | 0.4%    |
| Xubuntu 20.04                | 1        | 0.4%    |
| Xubuntu 18.04                | 1        | 0.4%    |
| Ubuntu Core 16               | 1        | 0.4%    |
| RHEL 8                       | 1        | 0.4%    |
| Regata OS 19.1               | 1        | 0.4%    |
| Redcore                      | 1        | 0.4%    |
| Peppermint 10                | 1        | 0.4%    |
| OpenMandriva 4.50            | 1        | 0.4%    |
| NixOS 21.05.20210929.ee90403 | 1        | 0.4%    |
| Manjaro 21.1.5               | 1        | 0.4%    |
| Manjaro 21.1.4               | 1        | 0.4%    |
| Manjaro 20.2.1               | 1        | 0.4%    |
| Manjaro 20.0.1               | 1        | 0.4%    |
| Manjaro 20.0                 | 1        | 0.4%    |
| Linux Mint 19.2              | 1        | 0.4%    |
| Linux Mint 19.1              | 1        | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 97       | 41.99%  |
| Pop!_OS      | 24       | 10.39%  |
| Linux Mint   | 20       | 8.66%   |
| Fedora       | 18       | 7.79%   |
| Manjaro      | 10       | 4.33%   |
| Endless      | 8        | 3.46%   |
| KDE neon     | 7        | 3.03%   |
| Arch         | 7        | 3.03%   |
| OpenMandriva | 6        | 2.6%    |
| Debian       | 6        | 2.6%    |
| Zorin        | 4        | 1.73%   |
| Kubuntu      | 4        | 1.73%   |
| Xubuntu      | 2        | 0.87%   |
| ROSA         | 2        | 0.87%   |
| openSUSE     | 2        | 0.87%   |
| Lubuntu      | 2        | 0.87%   |
| Devuan       | 2        | 0.87%   |
| RHEL         | 1        | 0.43%   |
| Regata OS    | 1        | 0.43%   |
| Redcore      | 1        | 0.43%   |
| Peppermint   | 1        | 0.43%   |
| NixOS        | 1        | 0.43%   |
| Linux Lite   | 1        | 0.43%   |
| Gentoo       | 1        | 0.43%   |
| Elementary   | 1        | 0.43%   |
| Deepin       | 1        | 0.43%   |
| ArcoLinux    | 1        | 0.43%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 6        | 2.06%   |
| 5.4.0-7634-generic       | 5        | 1.72%   |
| 5.3.0-46-generic         | 5        | 1.72%   |
| 5.4.0-52-generic         | 4        | 1.37%   |
| 5.13.0-30-generic        | 4        | 1.37%   |
| 5.11.0-37-generic        | 4        | 1.37%   |
| 5.8.0-50-generic         | 3        | 1.03%   |
| 5.8.0-44-generic         | 3        | 1.03%   |
| 5.4.0-65-generic         | 3        | 1.03%   |
| 5.4.0-33-generic         | 3        | 1.03%   |
| 5.3.0-40-generic         | 3        | 1.03%   |
| 5.13.0-7614-generic      | 3        | 1.03%   |
| 5.13.0-39-generic        | 3        | 1.03%   |
| 5.11.0-7614-generic      | 3        | 1.03%   |
| 5.11.0-34-generic        | 3        | 1.03%   |
| 5.10.14-desktop-1omv4002 | 3        | 1.03%   |
| 5.0.0-37-generic         | 3        | 1.03%   |
| 4.18.0-25-generic        | 3        | 1.03%   |
| 5.9.16-200.fc33.x86_64   | 2        | 0.69%   |
| 5.8.0-7630-generic       | 2        | 0.69%   |
| 5.8.0-59-generic         | 2        | 0.69%   |
| 5.8.0-55-generic         | 2        | 0.69%   |
| 5.8.0-43-generic         | 2        | 0.69%   |
| 5.8.0-33-generic         | 2        | 0.69%   |
| 5.8.0-14-generic         | 2        | 0.69%   |
| 5.4.0-77-generic         | 2        | 0.69%   |
| 5.4.0-7642-generic       | 2        | 0.69%   |
| 5.4.0-74-generic         | 2        | 0.69%   |
| 5.4.0-58-generic         | 2        | 0.69%   |
| 5.4.0-54-generic         | 2        | 0.69%   |
| 5.4.0-19-generic         | 2        | 0.69%   |
| 5.3.0-42-generic         | 2        | 0.69%   |
| 5.3.0-12-generic         | 2        | 0.69%   |
| 5.18.13-200.fc36.x86_64  | 2        | 0.69%   |
| 5.16.7-desktop-1omv4003  | 2        | 0.69%   |
| 5.15.15-76051515-generic | 2        | 0.69%   |
| 5.15.0-41-generic        | 2        | 0.69%   |
| 5.15.0-33-generic        | 2        | 0.69%   |
| 5.13.0-51-generic        | 2        | 0.69%   |
| 5.13.0-21-generic        | 2        | 0.69%   |
| 5.11.0-7620-generic      | 2        | 0.69%   |
| 5.11.0-7612-generic      | 2        | 0.69%   |
| 5.11.0-31-generic        | 2        | 0.69%   |
| 5.11.0-25-generic        | 2        | 0.69%   |
| 5.11.0-18-generic        | 2        | 0.69%   |
| 5.10.0-8-amd64           | 2        | 0.69%   |
| 5.0.0-29-generic         | 2        | 0.69%   |
| 4.18.0-20-generic        | 2        | 0.69%   |
| 4.18.0-18-generic        | 2        | 0.69%   |
| 4.18.0-12-generic        | 2        | 0.69%   |
| 4.18.0-10-generic        | 2        | 0.69%   |
| 4.15.0-64-generic        | 2        | 0.69%   |
| 5.9.8-100.fc32.x86_64    | 1        | 0.34%   |
| 5.9.16-050916-generic    | 1        | 0.34%   |
| 5.9.14-200.fc33.x86_64   | 1        | 0.34%   |
| 5.9.1-050901-generic     | 1        | 0.34%   |
| 5.9.0-1-amd64            | 1        | 0.34%   |
| 5.8.3-arch1-1            | 1        | 0.34%   |
| 5.8.12-zen1-1-zen        | 1        | 0.34%   |
| 5.8.12-1-default         | 1        | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 46       | 17.83%  |
| 4.15.0  | 24       | 9.3%    |
| 5.8.0   | 23       | 8.91%   |
| 5.11.0  | 21       | 8.14%   |
| 5.13.0  | 19       | 7.36%   |
| 5.3.0   | 16       | 6.2%    |
| 4.18.0  | 14       | 5.43%   |
| 5.0.0   | 8        | 3.1%    |
| 5.15.0  | 6        | 2.33%   |
| 5.9.16  | 3        | 1.16%   |
| 5.10.15 | 3        | 1.16%   |
| 5.10.14 | 3        | 1.16%   |
| 5.10.0  | 3        | 1.16%   |
| 5.8.12  | 2        | 0.78%   |
| 5.7.0   | 2        | 0.78%   |
| 5.6.11  | 2        | 0.78%   |
| 5.18.5  | 2        | 0.78%   |
| 5.18.13 | 2        | 0.78%   |
| 5.17.4  | 2        | 0.78%   |
| 5.16.7  | 2        | 0.78%   |
| 5.15.8  | 2        | 0.78%   |
| 5.15.15 | 2        | 0.78%   |
| 5.15.11 | 2        | 0.78%   |
| 5.9.8   | 1        | 0.39%   |
| 5.9.14  | 1        | 0.39%   |
| 5.9.1   | 1        | 0.39%   |
| 5.9.0   | 1        | 0.39%   |
| 5.8.3   | 1        | 0.39%   |
| 5.8.1   | 1        | 0.39%   |
| 5.7.9   | 1        | 0.39%   |
| 5.7.8   | 1        | 0.39%   |
| 5.7.7   | 1        | 0.39%   |
| 5.7.6   | 1        | 0.39%   |
| 5.7.14  | 1        | 0.39%   |
| 5.6.8   | 1        | 0.39%   |
| 5.6.7   | 1        | 0.39%   |
| 5.6.0   | 1        | 0.39%   |
| 5.5.9   | 1        | 0.39%   |
| 5.4.6   | 1        | 0.39%   |
| 5.4.35  | 1        | 0.39%   |
| 5.4.34  | 1        | 0.39%   |
| 5.3.8   | 1        | 0.39%   |
| 5.3.16  | 1        | 0.39%   |
| 5.2.11  | 1        | 0.39%   |
| 5.17.9  | 1        | 0.39%   |
| 5.16.15 | 1        | 0.39%   |
| 5.16.11 | 1        | 0.39%   |
| 5.15.6  | 1        | 0.39%   |
| 5.15.5  | 1        | 0.39%   |
| 5.15.32 | 1        | 0.39%   |
| 5.15.23 | 1        | 0.39%   |
| 5.15.12 | 1        | 0.39%   |
| 5.14.2  | 1        | 0.39%   |
| 5.14.15 | 1        | 0.39%   |
| 5.14.11 | 1        | 0.39%   |
| 5.14.10 | 1        | 0.39%   |
| 5.13.2  | 1        | 0.39%   |
| 5.13.19 | 1        | 0.39%   |
| 5.13.13 | 1        | 0.39%   |
| 5.12.9  | 1        | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 49       | 19.14%  |
| 5.8     | 27       | 10.55%  |
| 5.11    | 26       | 10.16%  |
| 4.15    | 24       | 9.38%   |
| 5.13    | 22       | 8.59%   |
| 5.3     | 18       | 7.03%   |
| 5.15    | 16       | 6.25%   |
| 4.18    | 14       | 5.47%   |
| 5.10    | 10       | 3.91%   |
| 5.0     | 9        | 3.52%   |
| 5.9     | 7        | 2.73%   |
| 5.7     | 6        | 2.34%   |
| 5.6     | 5        | 1.95%   |
| 5.18    | 4        | 1.56%   |
| 5.16    | 4        | 1.56%   |
| 5.14    | 4        | 1.56%   |
| 5.12    | 4        | 1.56%   |
| 5.17    | 3        | 1.17%   |
| 4.19    | 2        | 0.78%   |
| 5.5     | 1        | 0.39%   |
| 5.2     | 1        | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 223      | 99.55%  |
| i686   | 1        | 0.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 116      | 49.15%  |
| Unknown    | 43       | 18.22%  |
| KDE5       | 23       | 9.75%   |
| X-Cinnamon | 18       | 7.63%   |
| KDE        | 11       | 4.66%   |
| XFCE       | 10       | 4.24%   |
| MATE       | 5        | 2.12%   |
| Unity      | 2        | 0.85%   |
| LXQt       | 2        | 0.85%   |
| LXDE       | 2        | 0.85%   |
| Cinnamon   | 2        | 0.85%   |
| Pantheon   | 1        | 0.42%   |
| Deepin     | 1        | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 176      | 77.19%  |
| Unknown | 24       | 10.53%  |
| Wayland | 23       | 10.09%  |
| Tty     | 5        | 2.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 149      | 64.5%   |
| SDDM    | 22       | 9.52%   |
| GDM     | 19       | 8.23%   |
| LightDM | 14       | 6.06%   |
| GDM3    | 13       | 5.63%   |
| TDM     | 11       | 4.76%   |
| SLiM    | 3        | 1.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_NZ   | 131      | 55.27%  |
| en_US   | 43       | 18.14%  |
| Unknown | 43       | 18.14%  |
| en_AU   | 8        | 3.38%   |
| en_GB   | 7        | 2.95%   |
| C       | 3        | 1.27%   |
| zh_CN   | 2        | 0.84%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 133      | 57.58%  |
| EFI  | 98       | 42.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 185      | 81.14%  |
| Btrfs   | 13       | 5.7%    |
| Unknown | 13       | 5.7%    |
| Overlay | 11       | 4.82%   |
| Zfs     | 2        | 0.88%   |
| Xfs     | 1        | 0.44%   |
| Tmpfs   | 1        | 0.44%   |
| F2fs    | 1        | 0.44%   |
| Ext3    | 1        | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 155      | 67.98%  |
| GPT     | 60       | 26.32%  |
| MBR     | 13       | 5.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 192      | 84.21%  |
| Yes       | 36       | 15.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 154      | 66.96%  |
| Yes       | 76       | 33.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 62       | 27.68%  |
| ASUSTek Computer    | 54       | 24.11%  |
| Hewlett-Packard     | 31       | 13.84%  |
| ASRock              | 18       | 8.04%   |
| MSI                 | 15       | 6.7%    |
| Dell                | 11       | 4.91%   |
| Lenovo              | 9        | 4.02%   |
| Intel               | 7        | 3.13%   |
| Unknown             | 3        | 1.34%   |
| IBM                 | 2        | 0.89%   |
| Acer                | 2        | 0.89%   |
| Supermicro          | 1        | 0.45%   |
| Pegatron            | 1        | 0.45%   |
| OEM                 | 1        | 0.45%   |
| MediaVue            | 1        | 0.45%   |
| JGINYUE             | 1        | 0.45%   |
| Huanan              | 1        | 0.45%   |
| Colorful Technology | 1        | 0.45%   |
| Biostar             | 1        | 0.45%   |
| Alienware           | 1        | 0.45%   |
| AAEON               | 1        | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Gigabyte H77M-D3H                      | 5        | 2.23%   |
| ASUS All Series                        | 5        | 2.23%   |
| MSI MS-7B89                            | 3        | 1.34%   |
| HP EliteDesk 800 G1 SFF                | 3        | 1.34%   |
| Gigabyte 970A-D3P                      | 3        | 1.34%   |
| ASRock B450M Steel Legend              | 3        | 1.34%   |
| Unknown                                | 3        | 1.34%   |
| MSI MS-7C91                            | 2        | 0.89%   |
| MSI MS-7C02                            | 2        | 0.89%   |
| Lenovo ThinkCentre M58p 7479RS2        | 2        | 0.89%   |
| HP ProDesk 600 G1 SFF                  | 2        | 0.89%   |
| HP Compaq Elite 8300 USDT              | 2        | 0.89%   |
| HP Compaq Elite 8300 SFF               | 2        | 0.89%   |
| HP Compaq 8200 Elite SFF PC            | 2        | 0.89%   |
| HP Compaq 8100 Elite SFF PC            | 2        | 0.89%   |
| HP Compaq 6200 Pro SFF PC              | 2        | 0.89%   |
| Gigabyte Z77X-D3H                      | 2        | 0.89%   |
| Gigabyte F2A75M-D3H                    | 2        | 0.89%   |
| Gigabyte F2A55M-DS2                    | 2        | 0.89%   |
| Gigabyte B75M-D3H                      | 2        | 0.89%   |
| Gigabyte B550M DS3H                    | 2        | 0.89%   |
| Gigabyte B450M S2H                     | 2        | 0.89%   |
| Gigabyte AB350-Gaming                  | 2        | 0.89%   |
| ASUS TUF Gaming X570-PLUS              | 2        | 0.89%   |
| ASUS SABERTOOTH 990FX R2.0             | 2        | 0.89%   |
| ASUS ROG STRIX B550-F GAMING           | 2        | 0.89%   |
| ASUS PRIME B450-PLUS                   | 2        | 0.89%   |
| ASUS PRIME B350M-A                     | 2        | 0.89%   |
| ASRock A320M-HDV                       | 2        | 0.89%   |
| ASRock 970 Pro3 R2.0                   | 2        | 0.89%   |
| Supermicro X8SIL                       | 1        | 0.45%   |
| Pegatron CQ3320AN                      | 1        | 0.45%   |
| OEM H81U                               | 1        | 0.45%   |
| MSI PPPPP-CCC#MMMMMMMM                 | 1        | 0.45%   |
| MSI p6-2302a                           | 1        | 0.45%   |
| MSI MS-7C94                            | 1        | 0.45%   |
| MSI MS-7C67                            | 1        | 0.45%   |
| MSI MS-7B86                            | 1        | 0.45%   |
| MSI MS-7A74                            | 1        | 0.45%   |
| MSI MS-7125                            | 1        | 0.45%   |
| MSI MS-7028                            | 1        | 0.45%   |
| MediaVue MV-890GX V1.2                 | 1        | 0.45%   |
| Lenovo ThinkCentre M92p 32272H4        | 1        | 0.45%   |
| Lenovo ThinkCentre M91p 4518E2M        | 1        | 0.45%   |
| Lenovo ThinkCentre M910x 10N0CTO1WW    | 1        | 0.45%   |
| Lenovo ThinkCentre M58p 7483AC4        | 1        | 0.45%   |
| Lenovo ThinkCentre A57 9704A36         | 1        | 0.45%   |
| Lenovo IdeaCentre 3 07ADA05 90MV008VAU | 1        | 0.45%   |
| Lenovo 0837A85                         | 1        | 0.45%   |
| JGINYUE H97I PLUS V2.0                 | 1        | 0.45%   |
| Intel WX307-SCMS                       | 1        | 0.45%   |
| Intel STK1AW32SC                       | 1        | 0.45%   |
| Intel DQ87PG AAG74154-403              | 1        | 0.45%   |
| Intel DQ57TM AAE70931-403              | 1        | 0.45%   |
| Intel DQ45CB AAE30148-207              | 1        | 0.45%   |
| Intel DG31PR AAD97573-202              | 1        | 0.45%   |
| Intel DB75EN AAG39650-400              | 1        | 0.45%   |
| IBM System x3200 M3 -[732754M]         | 1        | 0.45%   |
| IBM System x3100 M4: -[2582E4M]        | 1        | 0.45%   |
| Huanan X99-F8                          | 1        | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| HP Compaq              | 14       | 6.25%   |
| ASUS ROG               | 12       | 5.36%   |
| ASUS PRIME             | 11       | 4.91%   |
| Lenovo ThinkCentre     | 7        | 3.13%   |
| Dell OptiPlex          | 7        | 3.13%   |
| HP EliteDesk           | 6        | 2.68%   |
| Gigabyte H77M-D3H      | 5        | 2.23%   |
| ASUS TUF               | 5        | 2.23%   |
| ASUS All               | 5        | 2.23%   |
| MSI MS-7B89            | 3        | 1.34%   |
| Gigabyte AB350-Gaming  | 3        | 1.34%   |
| Gigabyte 970A-D3P      | 3        | 1.34%   |
| ASRock B450M           | 3        | 1.34%   |
| Unknown                | 3        | 1.34%   |
| MSI MS-7C91            | 2        | 0.89%   |
| MSI MS-7C02            | 2        | 0.89%   |
| IBM System             | 2        | 0.89%   |
| HP ProLiant            | 2        | 0.89%   |
| HP ProDesk             | 2        | 0.89%   |
| Gigabyte Z77X-D3H      | 2        | 0.89%   |
| Gigabyte X570          | 2        | 0.89%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.89%   |
| Gigabyte F2A75M-D3H    | 2        | 0.89%   |
| Gigabyte F2A55M-DS2    | 2        | 0.89%   |
| Gigabyte B75M-D3H      | 2        | 0.89%   |
| Gigabyte B560M         | 2        | 0.89%   |
| Gigabyte B550M         | 2        | 0.89%   |
| Gigabyte B450M         | 2        | 0.89%   |
| Dell Precision         | 2        | 0.89%   |
| ASUS SABERTOOTH        | 2        | 0.89%   |
| ASUS P7P55D-E          | 2        | 0.89%   |
| ASRock A320M-HDV       | 2        | 0.89%   |
| ASRock 970             | 2        | 0.89%   |
| Acer Aspire            | 2        | 0.89%   |
| Supermicro X8SIL       | 1        | 0.45%   |
| Pegatron CQ3320AN      | 1        | 0.45%   |
| OEM H81U               | 1        | 0.45%   |
| MSI PPPPP-CCC#MMMMMMMM | 1        | 0.45%   |
| MSI p6-2302a           | 1        | 0.45%   |
| MSI MS-7C94            | 1        | 0.45%   |
| MSI MS-7C67            | 1        | 0.45%   |
| MSI MS-7B86            | 1        | 0.45%   |
| MSI MS-7A74            | 1        | 0.45%   |
| MSI MS-7125            | 1        | 0.45%   |
| MSI MS-7028            | 1        | 0.45%   |
| MediaVue MV-890GX      | 1        | 0.45%   |
| Lenovo IdeaCentre      | 1        | 0.45%   |
| Lenovo 0837A85         | 1        | 0.45%   |
| JGINYUE H97I           | 1        | 0.45%   |
| Intel WX307-SCMS       | 1        | 0.45%   |
| Intel STK1AW32SC       | 1        | 0.45%   |
| Intel DQ87PG           | 1        | 0.45%   |
| Intel DQ57TM           | 1        | 0.45%   |
| Intel DQ45CB           | 1        | 0.45%   |
| Intel DG31PR           | 1        | 0.45%   |
| Intel DB75EN           | 1        | 0.45%   |
| Huanan X99-F8          | 1        | 0.45%   |
| HP Z440                | 1        | 0.45%   |
| HP Z230                | 1        | 0.45%   |
| HP Z220                | 1        | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 40       | 17.86%  |
| 2019    | 22       | 9.82%   |
| 2013    | 20       | 8.93%   |
| 2020    | 19       | 8.48%   |
| 2017    | 19       | 8.48%   |
| 2011    | 18       | 8.04%   |
| 2018    | 17       | 7.59%   |
| 2014    | 12       | 5.36%   |
| 2009    | 11       | 4.91%   |
| 2008    | 11       | 4.91%   |
| 2015    | 10       | 4.46%   |
| 2010    | 9        | 4.02%   |
| 2021    | 5        | 2.23%   |
| 2016    | 3        | 1.34%   |
| 2007    | 3        | 1.34%   |
| 2005    | 2        | 0.89%   |
| 2022    | 1        | 0.45%   |
| 2004    | 1        | 0.45%   |
| Unknown | 1        | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 224      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 215      | 95.98%  |
| Enabled  | 9        | 4.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 223      | 99.55%  |
| Yes  | 1        | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 66       | 28.57%  |
| 8.01-16.0   | 50       | 21.65%  |
| 32.01-64.0  | 39       | 16.88%  |
| 4.01-8.0    | 31       | 13.42%  |
| 3.01-4.0    | 25       | 10.82%  |
| 64.01-256.0 | 8        | 3.46%   |
| 24.01-32.0  | 5        | 2.16%   |
| 1.01-2.0    | 5        | 2.16%   |
| 2.01-3.0    | 2        | 0.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 90       | 34.75%  |
| 2.01-3.0   | 67       | 25.87%  |
| 4.01-8.0   | 40       | 15.44%  |
| 3.01-4.0   | 27       | 10.42%  |
| 8.01-16.0  | 16       | 6.18%   |
| 0.51-1.0   | 13       | 5.02%   |
| 0.01-0.5   | 3        | 1.16%   |
| 16.01-24.0 | 2        | 0.77%   |
| 32.01-64.0 | 1        | 0.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 80       | 33.61%  |
| 2      | 78       | 32.77%  |
| 3      | 38       | 15.97%  |
| 4      | 27       | 11.34%  |
| 5      | 7        | 2.94%   |
| 6      | 4        | 1.68%   |
| 7      | 3        | 1.26%   |
| 8      | 1        | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 118      | 51.53%  |
| Yes       | 111      | 48.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 223      | 99.55%  |
| No        | 1        | 0.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 122      | 53.74%  |
| Yes       | 105      | 46.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 163      | 72.12%  |
| Yes       | 63       | 27.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| New Zealand | 224      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Auckland         | 117      | 49.79%  |
| Christchurch     | 28       | 11.91%  |
| Wellington       | 27       | 11.49%  |
| Hamilton         | 13       | 5.53%   |
| Tauranga         | 9        | 3.83%   |
| Dunedin          | 7        | 2.98%   |
| Palmerston North | 6        | 2.55%   |
| Napier City      | 4        | 1.7%    |
| Whangarei        | 3        | 1.28%   |
| New Plymouth     | 2        | 0.85%   |
| Nelson           | 2        | 0.85%   |
| Whanganui        | 1        | 0.43%   |
| Westport         | 1        | 0.43%   |
| Wellsford        | 1        | 0.43%   |
| Waihi            | 1        | 0.43%   |
| Stratford        | 1        | 0.43%   |
| Rotorua          | 1        | 0.43%   |
| Queenstown       | 1        | 0.43%   |
| Mount Eden       | 1        | 0.43%   |
| Milton           | 1        | 0.43%   |
| Invercargill     | 1        | 0.43%   |
| Hastings         | 1        | 0.43%   |
| Grafton          | 1        | 0.43%   |
| Darfield         | 1        | 0.43%   |
| Carterton        | 1        | 0.43%   |
| Cambridge        | 1        | 0.43%   |
| Ashburton        | 1        | 0.43%   |
| Albany           | 1        | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 101      | 186    | 24.63%  |
| WDC                       | 90       | 156    | 21.95%  |
| Samsung Electronics       | 63       | 125    | 15.37%  |
| Crucial                   | 24       | 38     | 5.85%   |
| Kingston                  | 19       | 28     | 4.63%   |
| Intel                     | 17       | 23     | 4.15%   |
| Toshiba                   | 15       | 19     | 3.66%   |
| Hitachi                   | 15       | 22     | 3.66%   |
| SanDisk                   | 12       | 15     | 2.93%   |
| A-DATA Technology         | 9        | 12     | 2.2%    |
| Micron Technology         | 5        | 6      | 1.22%   |
| Unknown                   | 3        | 3      | 0.73%   |
| Lexar                     | 3        | 3      | 0.73%   |
| HGST                      | 3        | 4      | 0.73%   |
| Gigabyte Technology       | 3        | 3      | 0.73%   |
| Apacer                    | 3        | 3      | 0.73%   |
| XPG                       | 2        | 2      | 0.49%   |
| Transcend                 | 2        | 2      | 0.49%   |
| TO Exter                  | 2        | 2      | 0.49%   |
| SK hynix                  | 2        | 2      | 0.49%   |
| Silicon Motion            | 2        | 3      | 0.49%   |
| External                  | 2        | 2      | 0.49%   |
| Corsair                   | 2        | 3      | 0.49%   |
| China                     | 2        | 3      | 0.49%   |
| USB                       | 1        | 2      | 0.24%   |
| Team                      | 1        | 1      | 0.24%   |
| Phison                    | 1        | 1      | 0.24%   |
| OCZ                       | 1        | 1      | 0.24%   |
| Micron/Crucial Technology | 1        | 1      | 0.24%   |
| KingSpec                  | 1        | 1      | 0.24%   |
| JMicron Technology        | 1        | 1      | 0.24%   |
| GAMER                     | 1        | 1      | 0.24%   |
| Apple                     | 1        | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB   | 10       | 2.03%   |
| Seagate Expansion Desk 4TB       | 9        | 1.83%   |
| Samsung SSD 860 EVO 500GB        | 8        | 1.62%   |
| Seagate ST31000528AS 1TB         | 7        | 1.42%   |
| Crucial CT240BX500SSD1 240GB     | 7        | 1.42%   |
| Seagate ST500DM002-1BD142 500GB  | 6        | 1.22%   |
| Seagate ST2000DM006-2DM164 2TB   | 6        | 1.22%   |
| Seagate ST1000DM003-1CH162 1TB   | 6        | 1.22%   |
| Samsung SSD 850 EVO 250GB        | 6        | 1.22%   |
| Samsung NVMe SSD Drive 500GB     | 6        | 1.22%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 5        | 1.01%   |
| Toshiba THNS128GG4BBAA 128GB SSD | 5        | 1.01%   |
| Seagate ST1000DM010-2EP102 1TB   | 5        | 1.01%   |
| Seagate Expansion 1TB            | 5        | 1.01%   |
| Samsung SSD 870 EVO 1TB          | 5        | 1.01%   |
| Samsung SSD 850 EVO 500GB        | 5        | 1.01%   |
| WDC WD10EZEX-00WN4A0 1TB         | 4        | 0.81%   |
| Seagate ST2000DM001-1CH164 2TB   | 4        | 0.81%   |
| Samsung NVMe SSD Drive 1TB       | 4        | 0.81%   |
| Kingston SA400S37240G 240GB SSD  | 4        | 0.81%   |
| Kingston SA400S37120G 120GB SSD  | 4        | 0.81%   |
| WDC WD20EARX-00PASB0 2TB         | 3        | 0.61%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 0.61%   |
| WDC WD10EALX-009BA0 1TB          | 3        | 0.61%   |
| Seagate ST3500418AS 500GB        | 3        | 0.61%   |
| Seagate ST3000DM001-1ER166 3TB   | 3        | 0.61%   |
| Samsung SSD 860 EVO 250GB        | 3        | 0.61%   |
| Samsung SSD 840 EVO 120GB        | 3        | 0.61%   |
| Kingston SV300S37A120G 120GB SSD | 3        | 0.61%   |
| Kingston SUV400S37240G 240GB SSD | 3        | 0.61%   |
| Intel SSDSA2CW080G3 80GB         | 3        | 0.61%   |
| Crucial CT960BX500SSD1 960GB     | 3        | 0.61%   |
| Crucial CT500MX500SSD1 500GB     | 3        | 0.61%   |
| XPG GAMMIX S11 480GB             | 2        | 0.41%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2        | 0.41%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 2        | 0.41%   |
| WDC WD5000AAKS-00UU3A0 500GB     | 2        | 0.41%   |
| WDC WD5000AADS-00S9B0 500GB      | 2        | 0.41%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 2        | 0.41%   |
| WDC WD40EFRX-68N32N0 4TB         | 2        | 0.41%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2        | 0.41%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 2        | 0.41%   |
| WDC WD10EZEX-60WN4A1 1TB         | 2        | 0.41%   |
| WDC WD10EZEX-22MFCA0 1TB         | 2        | 0.41%   |
| WDC WD10EZEX-00ZF5A0 1TB         | 2        | 0.41%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 2        | 0.41%   |
| Unknown SD/MMC/MS PRO 64GB       | 2        | 0.41%   |
| Toshiba DT01ACA200 2TB           | 2        | 0.41%   |
| TO Exter nal USB 3.0 1TB         | 2        | 0.41%   |
| Seagate ST9500325AS 500GB        | 2        | 0.41%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 0.41%   |
| Seagate ST3500413AS 500GB        | 2        | 0.41%   |
| Seagate ST3250312AS 250GB        | 2        | 0.41%   |
| Seagate ST31000333AS 1TB         | 2        | 0.41%   |
| Seagate ST3000DM001-9YN166 3TB   | 2        | 0.41%   |
| Seagate ST2000DX002-2DV164 2TB   | 2        | 0.41%   |
| Seagate ST2000DM001-1ER164 2TB   | 2        | 0.41%   |
| Seagate ST1000DX002-2DV162 1TB   | 2        | 0.41%   |
| Seagate ST1000DM003-9YN162 1TB   | 2        | 0.41%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 99       | 177    | 46.26%  |
| WDC                 | 82       | 139    | 38.32%  |
| Hitachi             | 15       | 22     | 7.01%   |
| Toshiba             | 8        | 12     | 3.74%   |
| HGST                | 3        | 4      | 1.4%    |
| Unknown             | 2        | 2      | 0.93%   |
| Samsung Electronics | 2        | 3      | 0.93%   |
| USB                 | 1        | 2      | 0.47%   |
| External            | 1        | 1      | 0.47%   |
| Apple               | 1        | 1      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 43       | 71     | 28.29%  |
| Crucial             | 22       | 33     | 14.47%  |
| Kingston            | 16       | 25     | 10.53%  |
| Intel               | 15       | 19     | 9.87%   |
| SanDisk             | 11       | 14     | 7.24%   |
| WDC                 | 8        | 11     | 5.26%   |
| A-DATA Technology   | 7        | 9      | 4.61%   |
| Toshiba             | 5        | 5      | 3.29%   |
| Micron Technology   | 3        | 4      | 1.97%   |
| Lexar               | 3        | 3      | 1.97%   |
| Apacer              | 3        | 3      | 1.97%   |
| TO Exter            | 2        | 2      | 1.32%   |
| Seagate             | 2        | 4      | 1.32%   |
| Gigabyte Technology | 2        | 2      | 1.32%   |
| Corsair             | 2        | 3      | 1.32%   |
| China               | 2        | 2      | 1.32%   |
| Transcend           | 1        | 1      | 0.66%   |
| Team                | 1        | 1      | 0.66%   |
| SK hynix            | 1        | 1      | 0.66%   |
| OCZ                 | 1        | 1      | 0.66%   |
| KingSpec            | 1        | 1      | 0.66%   |
| GAMER               | 1        | 1      | 0.66%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 166      | 363    | 47.29%  |
| SSD     | 129      | 216    | 36.75%  |
| NVMe    | 51       | 91     | 14.53%  |
| Unknown | 3        | 3      | 0.85%   |
| MMC     | 2        | 2      | 0.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 212      | 550    | 73.87%  |
| NVMe | 50       | 89     | 17.42%  |
| SAS  | 23       | 34     | 8.01%   |
| MMC  | 2        | 2      | 0.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 161      | 293    | 46.67%  |
| 0.51-1.0   | 100      | 158    | 28.99%  |
| 1.01-2.0   | 45       | 69     | 13.04%  |
| 3.01-4.0   | 23       | 34     | 6.67%   |
| 2.01-3.0   | 10       | 12     | 2.9%    |
| 4.01-10.0  | 4        | 6      | 1.16%   |
| 10.01-20.0 | 2        | 7      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 53       | 21.63%  |
| 501-1000       | 41       | 16.73%  |
| 251-500        | 36       | 14.69%  |
| More than 3000 | 31       | 12.65%  |
| 1001-2000      | 30       | 12.24%  |
| 2001-3000      | 23       | 9.39%   |
| 1-20           | 16       | 6.53%   |
| 51-100         | 9        | 3.67%   |
| Unknown        | 5        | 2.04%   |
| 21-50          | 1        | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 78       | 29.55%  |
| 21-50          | 43       | 16.29%  |
| 251-500        | 26       | 9.85%   |
| 501-1000       | 26       | 9.85%   |
| 101-250        | 22       | 8.33%   |
| 1001-2000      | 22       | 8.33%   |
| 51-100         | 20       | 7.58%   |
| More than 3000 | 11       | 4.17%   |
| 2001-3000      | 11       | 4.17%   |
| Unknown        | 5        | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD20EZRZ-00Z5HB0 2TB              | 2        | 2      | 8.33%   |
| WDC WD5000AAKX-001CA0 500GB           | 1        | 1      | 4.17%   |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1        | 1      | 4.17%   |
| WDC WD15EARS-00S0XB0 1TB              | 1        | 1      | 4.17%   |
| WDC WD10EFRX-68FYTN0 1TB              | 1        | 3      | 4.17%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1        | 1      | 4.17%   |
| SK hynix HFS256G32MND-2900A 256GB SSD | 1        | 1      | 4.17%   |
| Seagate ST8000VN0022-2EL112 8TB       | 1        | 3      | 4.17%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 4.17%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 4.17%   |
| Seagate ST3250310AS 250GB             | 1        | 1      | 4.17%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 4.17%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 4.17%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 4.17%   |
| Seagate ST2000DX002-2DV164 2TB        | 1        | 1      | 4.17%   |
| Seagate ST2000DX001-1CM164 2TB        | 1        | 1      | 4.17%   |
| Seagate ST2000DM001-1CH164 2TB        | 1        | 1      | 4.17%   |
| SanDisk SSD PLUS 240 GB               | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 980 PRO 250GB | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 980 1TB       | 1        | 1      | 4.17%   |
| Intel SSDSC2CT240A4 240GB             | 1        | 1      | 4.17%   |
| Crucial CT480M500SSD1 480GB           | 1        | 1      | 4.17%   |
| Crucial CT480BX500SSD1 480GB          | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 12     | 36.36%  |
| WDC                 | 7        | 9      | 31.82%  |
| Samsung Electronics | 2        | 2      | 9.09%   |
| Crucial             | 2        | 2      | 9.09%   |
| SK hynix            | 1        | 1      | 4.55%   |
| SanDisk             | 1        | 1      | 4.55%   |
| Intel               | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 8        | 12     | 53.33%  |
| WDC     | 7        | 9      | 46.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 21     | 68.18%  |
| SSD  | 5        | 5      | 22.73%  |
| NVMe | 2        | 2      | 9.09%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 155      | 451    | 61.26%  |
| Works    | 76       | 196    | 30.04%  |
| Malfunc  | 22       | 28     | 8.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 138      | 44.09%  |
| AMD                          | 80       | 25.56%  |
| Samsung Electronics          | 29       | 9.27%   |
| Marvell Technology Group     | 11       | 3.51%   |
| JMicron Technology           | 11       | 3.51%   |
| ASMedia Technology           | 9        | 2.88%   |
| Nvidia                       | 5        | 1.6%    |
| Silicon Motion               | 4        | 1.28%   |
| Seagate Technology           | 3        | 0.96%   |
| SanDisk                      | 3        | 0.96%   |
| Micron/Crucial Technology    | 3        | 0.96%   |
| LSI Logic / Symbios Logic    | 3        | 0.96%   |
| Kingston Technology Company  | 3        | 0.96%   |
| Toshiba America Info Systems | 2        | 0.64%   |
| Micron Technology            | 2        | 0.64%   |
| VIA Technologies             | 1        | 0.32%   |
| SK hynix                     | 1        | 0.32%   |
| Silicon Image                | 1        | 0.32%   |
| Realtek Semiconductor        | 1        | 0.32%   |
| Phison Electronics           | 1        | 0.32%   |
| Hewlett-Packard              | 1        | 0.32%   |
| ADATA Technology             | 1        | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 47       | 11.33%  |
| AMD 400 Series Chipset SATA Controller                                                  | 20       | 4.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 18       | 4.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 15       | 3.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14       | 3.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 14       | 3.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14       | 3.37%   |
| Intel SATA Controller [RAID mode]                                                       | 11       | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 2.41%   |
| AMD 500 Series Chipset SATA Controller                                                  | 10       | 2.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 2.17%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9        | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 1.69%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 1.69%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7        | 1.69%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 7        | 1.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 1.69%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 1.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.45%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 1.45%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 6        | 1.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 1.2%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5        | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 5        | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 5        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 1.2%    |
| Samsung NVMe SSD Controller 980                                                         | 4        | 0.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.96%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 0.96%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.72%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 3        | 0.72%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 3        | 0.72%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 0.72%   |
| Intel SSD 600P Series                                                                   | 3        | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 0.72%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.72%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 0.72%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 0.72%   |
| AMD FCH IDE Controller                                                                  | 3        | 0.72%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2        | 0.48%   |
| Seagate FireCuda 520 SSD                                                                | 2        | 0.48%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.48%   |
| Nvidia CK804 Serial ATA Controller                                                      | 2        | 0.48%   |
| Nvidia CK804 IDE                                                                        | 2        | 0.48%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 0.48%   |
| Micron Non-Volatile memory controller                                                   | 2        | 0.48%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                                    | 2        | 0.48%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.48%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 0.48%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.48%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 2        | 0.48%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.48%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 0.48%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2        | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 175      | 55.56%  |
| IDE  | 68       | 21.59%  |
| NVMe | 52       | 16.51%  |
| RAID | 19       | 6.03%   |
| SCSI | 1        | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 139      | 62.05%  |
| AMD    | 85       | 37.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 10       | 4.46%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 7        | 3.13%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 6        | 2.68%   |
| AMD Ryzen 5 3600 6-Core Processor           | 6        | 2.68%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 4        | 1.79%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 1.79%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 4        | 1.79%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 1.79%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 1.79%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 1.79%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 1.34%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.34%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 3        | 1.34%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 3        | 1.34%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 3        | 1.34%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 1.34%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 1.34%   |
| AMD FX-6300 Six-Core Processor              | 3        | 1.34%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 0.89%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 0.89%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.89%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 2        | 0.89%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.89%   |
| Intel Core i5-4670 CPU @ 3.40GHz            | 2        | 0.89%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.89%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 0.89%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 2        | 0.89%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 0.89%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 0.89%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 0.89%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 2        | 0.89%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz       | 2        | 0.89%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 0.89%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 0.89%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 2        | 0.89%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 0.89%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2        | 0.89%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 2        | 0.89%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 0.89%   |
| AMD FX-8370 Eight-Core Processor            | 2        | 0.89%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 0.89%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 2        | 0.89%   |
| Intel Xeon W-2175 CPU @ 2.50GHz             | 1        | 0.45%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1        | 0.45%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 1        | 0.45%   |
| Intel Xeon CPU X3450 @ 2.67GHz              | 1        | 0.45%   |
| Intel Xeon CPU X3440 @ 2.53GHz              | 1        | 0.45%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1        | 0.45%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.45%   |
| Intel Xeon CPU E5-1660 0 @ 3.30GHz          | 1        | 0.45%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1        | 0.45%   |
| Intel Xeon CPU E3110 @ 3.00GHz              | 1        | 0.45%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz         | 1        | 0.45%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 1        | 0.45%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.45%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.45%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1        | 0.45%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 1        | 0.45%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 0.45%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 48       | 21.43%  |
| Intel Core i7           | 38       | 16.96%  |
| AMD Ryzen 7             | 19       | 8.48%   |
| AMD Ryzen 5             | 19       | 8.48%   |
| Intel Core i3           | 13       | 5.8%    |
| AMD FX                  | 13       | 5.8%    |
| Intel Xeon              | 12       | 5.36%   |
| Intel Core 2 Quad       | 9        | 4.02%   |
| Intel Core 2 Duo        | 6        | 2.68%   |
| Intel Pentium           | 5        | 2.23%   |
| AMD Ryzen 9             | 5        | 2.23%   |
| AMD Ryzen 3             | 5        | 2.23%   |
| AMD Ryzen Threadripper  | 4        | 1.79%   |
| AMD Athlon II X2        | 4        | 1.79%   |
| AMD Athlon 64 X2        | 4        | 1.79%   |
| Intel Atom              | 3        | 1.34%   |
| AMD A8                  | 2        | 0.89%   |
| AMD A6                  | 2        | 0.89%   |
| AMD A4                  | 2        | 0.89%   |
| Intel Pentium Dual-Core | 1        | 0.45%   |
| Intel Pentium Dual      | 1        | 0.45%   |
| Intel Pentium 4         | 1        | 0.45%   |
| Intel Core i9           | 1        | 0.45%   |
| Intel Celeron           | 1        | 0.45%   |
| AMD Ryzen 7 PRO         | 1        | 0.45%   |
| AMD Opteron             | 1        | 0.45%   |
| AMD GX                  | 1        | 0.45%   |
| AMD Athlon II X4        | 1        | 0.45%   |
| AMD A12                 | 1        | 0.45%   |
| AMD A10                 | 1        | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 105      | 46.88%  |
| 2      | 44       | 19.64%  |
| 6      | 30       | 13.39%  |
| 8      | 26       | 11.61%  |
| 12     | 7        | 3.13%   |
| 3      | 4        | 1.79%   |
| 1      | 3        | 1.34%   |
| 16     | 2        | 0.89%   |
| 24     | 1        | 0.45%   |
| 14     | 1        | 0.45%   |
| 10     | 1        | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 223      | 99.55%  |
| 2      | 1        | 0.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 134      | 59.82%  |
| 1      | 90       | 40.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 220      | 97.35%  |
| Unknown        | 6        | 2.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 55       | 23.71%  |
| 0x306c3    | 20       | 8.62%   |
| 0x306a9    | 19       | 8.19%   |
| 0x206a7    | 13       | 5.6%    |
| 0x08701021 | 13       | 5.6%    |
| 0x1067a    | 8        | 3.45%   |
| 0x06000852 | 7        | 3.02%   |
| 0x106e5    | 6        | 2.59%   |
| 0xa0655    | 5        | 2.16%   |
| 0x506e3    | 5        | 2.16%   |
| 0x0800820d | 5        | 2.16%   |
| 0x08001137 | 5        | 2.16%   |
| 0x906e9    | 4        | 1.72%   |
| 0x106a5    | 4        | 1.72%   |
| 0x0a50000c | 4        | 1.72%   |
| 0x08701013 | 4        | 1.72%   |
| 0x6fb      | 3        | 1.29%   |
| 0x20655    | 3        | 1.29%   |
| 0x06001119 | 3        | 1.29%   |
| 0x906ed    | 2        | 0.86%   |
| 0x906ea    | 2        | 0.86%   |
| 0x50654    | 2        | 0.86%   |
| 0x406c3    | 2        | 0.86%   |
| 0x306f2    | 2        | 0.86%   |
| 0x10677    | 2        | 0.86%   |
| 0x08001138 | 2        | 0.86%   |
| 0x08001129 | 2        | 0.86%   |
| 0x0700010f | 2        | 0.86%   |
| 0x0600063e | 2        | 0.86%   |
| 0x010000c8 | 2        | 0.86%   |
| 0x906eb    | 1        | 0.43%   |
| 0x6fd      | 1        | 0.43%   |
| 0x506c9    | 1        | 0.43%   |
| 0x406c4    | 1        | 0.43%   |
| 0x40651    | 1        | 0.43%   |
| 0x206d7    | 1        | 0.43%   |
| 0x206c2    | 1        | 0.43%   |
| 0x20652    | 1        | 0.43%   |
| 0x106ca    | 1        | 0.43%   |
| 0x10676    | 1        | 0.43%   |
| 0x0a20120a | 1        | 0.43%   |
| 0x0a201016 | 1        | 0.43%   |
| 0x0a201009 | 1        | 0.43%   |
| 0x08600106 | 1        | 0.43%   |
| 0x08301025 | 1        | 0.43%   |
| 0x08108109 | 1        | 0.43%   |
| 0x0810100b | 1        | 0.43%   |
| 0x0800820c | 1        | 0.43%   |
| 0x0800820b | 1        | 0.43%   |
| 0x08001136 | 1        | 0.43%   |
| 0x0600611a | 1        | 0.43%   |
| 0x03000027 | 1        | 0.43%   |
| 0x010000db | 1        | 0.43%   |
| 0x010000c7 | 1        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 26       | 11.61%  |
| IvyBridge   | 25       | 11.16%  |
| Zen 2       | 22       | 9.82%   |
| SandyBridge | 16       | 7.14%   |
| Piledriver  | 16       | 7.14%   |
| Penryn      | 14       | 6.25%   |
| KabyLake    | 14       | 6.25%   |
| Zen         | 12       | 5.36%   |
| Zen+        | 11       | 4.91%   |
| Nehalem     | 11       | 4.91%   |
| Skylake     | 9        | 4.02%   |
| Zen 3       | 8        | 3.57%   |
| CometLake   | 8        | 3.57%   |
| Westmere    | 5        | 2.23%   |
| K10         | 5        | 2.23%   |
| Core        | 5        | 2.23%   |
| K8 Hammer   | 4        | 1.79%   |
| Silvermont  | 3        | 1.34%   |
| Bulldozer   | 3        | 1.34%   |
| Jaguar      | 2        | 0.89%   |
| NetBurst    | 1        | 0.45%   |
| K10 Llano   | 1        | 0.45%   |
| Goldmont    | 1        | 0.45%   |
| Excavator   | 1        | 0.45%   |
| Bonnell     | 1        | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 87       | 35.8%   |
| Nvidia                     | 83       | 34.16%  |
| Intel                      | 69       | 28.4%   |
| Matrox Electronics Systems | 3        | 1.23%   |
| ASPEED Technology          | 1        | 0.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 17       | 6.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13       | 5.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10       | 3.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8        | 3.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6        | 2.38%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 6        | 2.38%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5        | 1.98%   |
| Intel HD Graphics 630                                                                    | 5        | 1.98%   |
| Intel HD Graphics 530                                                                    | 5        | 1.98%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 1.98%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5        | 1.98%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 5        | 1.98%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 1.59%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 1.59%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4        | 1.59%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 4        | 1.59%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 4        | 1.59%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4        | 1.59%   |
| AMD Cezanne                                                                              | 4        | 1.59%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4        | 1.59%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 3        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 1.19%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2        | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2        | 0.79%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 2        | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2        | 0.79%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                        | 2        | 0.79%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 0.79%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 0.79%   |
| Nvidia GK107 [GeForce GT 740]                                                            | 2        | 0.79%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2        | 0.79%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2        | 0.79%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 2        | 0.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 0.79%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2        | 0.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 0.79%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 0.79%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 2        | 0.79%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                               | 2        | 0.79%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 0.79%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2        | 0.79%   |
| AMD ES1000                                                                               | 2        | 0.79%   |
| AMD Cayman PRO [Radeon HD 6950]                                                          | 2        | 0.79%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.4%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 0.4%    |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1        | 0.4%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1        | 0.4%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.4%    |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1        | 0.4%    |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.4%    |
| Nvidia GP107GL [Quadro P620]                                                             | 1        | 0.4%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 0.4%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 0.4%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.4%    |
| Nvidia GM107GL [Quadro K2200]                                                            | 1        | 0.4%    |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 1        | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 79       | 34.35%  |
| 1 x AMD        | 75       | 32.61%  |
| 1 x Intel      | 58       | 25.22%  |
| 2 x AMD        | 5        | 2.17%   |
| Intel + AMD    | 4        | 1.74%   |
| 1 x Matrox     | 3        | 1.3%    |
| AMD + Nvidia   | 3        | 1.3%    |
| 2 x Nvidia     | 1        | 0.43%   |
| Intel + Nvidia | 1        | 0.43%   |
| AMD + ASPEED   | 1        | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 171      | 75.66%  |
| Proprietary | 51       | 22.57%  |
| Unknown     | 4        | 1.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 89       | 38.2%   |
| 1.01-2.0   | 37       | 15.88%  |
| 0.01-0.5   | 26       | 11.16%  |
| 7.01-8.0   | 24       | 10.3%   |
| 0.51-1.0   | 22       | 9.44%   |
| 5.01-6.0   | 13       | 5.58%   |
| 3.01-4.0   | 12       | 5.15%   |
| 8.01-16.0  | 7        | 3%      |
| 2.01-3.0   | 3        | 1.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 37       | 14.4%   |
| Dell                    | 34       | 13.23%  |
| AOC                     | 34       | 13.23%  |
| Philips                 | 25       | 9.73%   |
| Goldstar                | 25       | 9.73%   |
| ViewSonic               | 22       | 8.56%   |
| Hewlett-Packard         | 12       | 4.67%   |
| Panasonic               | 8        | 3.11%   |
| Sony                    | 7        | 2.72%   |
| Lenovo                  | 7        | 2.72%   |
| BenQ                    | 6        | 2.33%   |
| MiTAC                   | 5        | 1.95%   |
| Ancor Communications    | 5        | 1.95%   |
| Acer                    | 5        | 1.95%   |
| LG Electronics          | 4        | 1.56%   |
| Denver                  | 4        | 1.56%   |
| Unknown                 | 2        | 0.78%   |
| Konka                   | 2        | 0.78%   |
| Chi Mei Optoelectronics | 2        | 0.78%   |
| Unknown (AAA)           | 1        | 0.39%   |
| SANYO                   | 1        | 0.39%   |
| Plain Tree Systems      | 1        | 0.39%   |
| NEC Computers           | 1        | 0.39%   |
| Marantz                 | 1        | 0.39%   |
| KTC                     | 1        | 0.39%   |
| Iiyama                  | 1        | 0.39%   |
| GVV                     | 1        | 0.39%   |
| eMachines               | 1        | 0.39%   |
| Elo Touch               | 1        | 0.39%   |
| ASUSTek Computer        | 1        | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Panasonic TV MEIA296 1280x1024 698x392mm 31.5-inch                    | 6        | 2.08%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                | 4        | 1.38%   |
| ViewSonic LCD Monitor VSC0E28 1920x1080 480x270mm 21.7-inch           | 3        | 1.04%   |
| MiTAC Smart TV SZM0030 1920x1080 708x398mm 32.0-inch                  | 3        | 1.04%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                     | 3        | 1.04%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 2        | 0.69%   |
| ViewSonic VA2231 Series VSCBB25 1920x1080 477x268mm 21.5-inch         | 2        | 0.69%   |
| ViewSonic LCD Monitor VSCB51D 1280x1024 340x270mm 17.1-inch           | 2        | 0.69%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2        | 0.69%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 2        | 0.69%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch  | 2        | 0.69%   |
| Konka TV MONIOR KOA0030 1920x540 708x398mm 32.0-inch                  | 2        | 0.69%   |
| Hewlett-Packard P221 HWP3057 1920x1080 480x270mm 21.7-inch            | 2        | 0.69%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 0.69%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.69%   |
| Goldstar E2351 GSM5872 1920x1080 510x290mm 23.1-inch                  | 2        | 0.69%   |
| Denver 274K144IGHUCA LHC2700 3840x2160 597x336mm 27.0-inch            | 2        | 0.69%   |
| Dell G2410 DEL404B 1920x1080 531x298mm 24.0-inch                      | 2        | 0.69%   |
| Dell 1907FP DEL4015 1280x1024 376x301mm 19.0-inch                     | 2        | 0.69%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 2        | 0.69%   |
| AOC U2868 AOC2868 3840x2160 621x341mm 27.9-inch                       | 2        | 0.69%   |
| AOC 2778X AOC2778 2560x1440 597x336mm 27.0-inch                       | 2        | 0.69%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 2        | 0.69%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 2        | 0.69%   |
| AOC 2367 AOC2367 1920x1080 509x286mm 23.0-inch                        | 2        | 0.69%   |
| AOC 2260W AOC2260 1920x1080 477x268mm 21.5-inch                       | 2        | 0.69%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 2        | 0.69%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch            | 1        | 0.35%   |
| ViewSonic VX2770 SERIES VSC3A2C 1920x1080 597x336mm 27.0-inch         | 1        | 0.35%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch         | 1        | 0.35%   |
| ViewSonic VX2439wm VSC3D24 1920x1080 521x293mm 23.5-inch              | 1        | 0.35%   |
| ViewSonic VX2270 SERIES VSCE02C 1920x1080 476x267mm 21.5-inch         | 1        | 0.35%   |
| ViewSonic VX2235wm-EU VSC591E 1680x1050 474x296mm 22.0-inch           | 1        | 0.35%   |
| ViewSonic VX1937 SERIES VSC2D24 1440x900 408x255mm 18.9-inch          | 1        | 0.35%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1        | 0.35%   |
| ViewSonic VP2250wb VSC5320 1920x1080 465x291mm 21.6-inch              | 1        | 0.35%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 1        | 0.35%   |
| ViewSonic VA2446 Series VSC732E 1920x1080 521x293mm 23.5-inch         | 1        | 0.35%   |
| ViewSonic VA2349 Series VSC702E 1920x1080 509x286mm 23.0-inch         | 1        | 0.35%   |
| ViewSonic VA1903wSERIES VSC701F 1440x900 408x255mm 18.9-inch          | 1        | 0.35%   |
| ViewSonic TD2220 VSC052C 1920x1080 480x270mm 21.7-inch                | 1        | 0.35%   |
| ViewSonic PJ VSC1536 1920x1080                                        | 1        | 0.35%   |
| ViewSonic LCD Monitor VX2235wm                                        | 1        | 0.35%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1        | 0.35%   |
| Unknown LCD Monitor XXX Union TV                                      | 1        | 0.35%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 0.35%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1        | 0.35%   |
| Sony TV SNYEF03 1600x900                                              | 1        | 0.35%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 0.35%   |
| Sony TV SNYDF02 1600x900 708x398mm 32.0-inch                          | 1        | 0.35%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                         | 1        | 0.35%   |
| Sony TV SNYA401 1920x1080                                             | 1        | 0.35%   |
| Sony TV SNY7702 1920x1080 886x498mm 40.0-inch                         | 1        | 0.35%   |
| Sony LCD Monitor TV 1360x768                                          | 1        | 0.35%   |
| SANYO SANCY SAN052D 1600x1200 304x228mm 15.0-inch                     | 1        | 0.35%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 697x392mm 31.5-inch     | 1        | 0.35%   |
| Samsung Electronics U32H85x SAM0E3B 3840x2160 700x390mm 31.5-inch     | 1        | 0.35%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1        | 0.35%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1        | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 110      | 42.97%  |
| 3840x2160 (4K)     | 34       | 13.28%  |
| 1680x1050 (WSXGA+) | 21       | 8.2%    |
| 2560x1440 (QHD)    | 15       | 5.86%   |
| 1280x1024 (SXGA)   | 15       | 5.86%   |
| 1440x900 (WXGA+)   | 11       | 4.3%    |
| Unknown            | 10       | 3.91%   |
| 3440x1440          | 6        | 2.34%   |
| 3840x1080          | 5        | 1.95%   |
| 1600x900 (HD+)     | 5        | 1.95%   |
| 1920x1200 (WUXGA)  | 3        | 1.17%   |
| 1366x768 (WXGA)    | 3        | 1.17%   |
| 1360x768           | 3        | 1.17%   |
| 2560x1080          | 2        | 0.78%   |
| 1600x1200          | 2        | 0.78%   |
| 7680x1080          | 1        | 0.39%   |
| 6720x1080          | 1        | 0.39%   |
| 3840x1600          | 1        | 0.39%   |
| 3840x1200          | 1        | 0.39%   |
| 3360x1080          | 1        | 0.39%   |
| 2960x1050          | 1        | 0.39%   |
| 2560x1600          | 1        | 0.39%   |
| 2560x1024          | 1        | 0.39%   |
| 2288x1287          | 1        | 0.39%   |
| 2048x1152          | 1        | 0.39%   |
| 1024x768 (XGA)     | 1        | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 38       | 14.79%  |
| 21      | 35       | 13.62%  |
| 27      | 29       | 11.28%  |
| 24      | 28       | 10.89%  |
| Unknown | 27       | 10.51%  |
| 22      | 14       | 5.45%   |
| 19      | 13       | 5.06%   |
| 31      | 11       | 4.28%   |
| 84      | 9        | 3.5%    |
| 20      | 9        | 3.5%    |
| 17      | 9        | 3.5%    |
| 72      | 5        | 1.95%   |
| 34      | 5        | 1.95%   |
| 32      | 5        | 1.95%   |
| 18      | 5        | 1.95%   |
| 52      | 3        | 1.17%   |
| 46      | 2        | 0.78%   |
| 35      | 2        | 0.78%   |
| 142     | 1        | 0.39%   |
| 65      | 1        | 0.39%   |
| 54      | 1        | 0.39%   |
| 49      | 1        | 0.39%   |
| 40      | 1        | 0.39%   |
| 37      | 1        | 0.39%   |
| 30      | 1        | 0.39%   |
| 15      | 1        | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 80       | 32.52%  |
| 401-500        | 69       | 28.05%  |
| Unknown        | 27       | 10.98%  |
| 601-700        | 18       | 7.32%   |
| 1501-2000      | 13       | 5.28%   |
| 701-800        | 10       | 4.07%   |
| 301-350        | 10       | 4.07%   |
| 1001-1500      | 8        | 3.25%   |
| 351-400        | 6        | 2.44%   |
| 801-900        | 4        | 1.63%   |
| More than 2000 | 1        | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 143      | 60.85%  |
| 16/10   | 38       | 16.17%  |
| Unknown | 24       | 10.21%  |
| 5/4     | 15       | 6.38%   |
| 21/9    | 8        | 3.4%    |
| 4/3     | 3        | 1.28%   |
| 6/5     | 1        | 0.43%   |
| 32/9    | 1        | 0.43%   |
| 3/2     | 1        | 0.43%   |
| 1.00    | 1        | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 92       | 37.25%  |
| 151-200        | 32       | 12.96%  |
| 301-350        | 29       | 11.74%  |
| Unknown        | 27       | 10.93%  |
| 351-500        | 24       | 9.72%   |
| More than 1000 | 19       | 7.69%   |
| 141-150        | 11       | 4.45%   |
| 251-300        | 7        | 2.83%   |
| 501-1000       | 5        | 2.02%   |
| 101-110        | 1        | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 131      | 53.91%  |
| 101-120 | 48       | 19.75%  |
| Unknown | 27       | 11.11%  |
| 1-50    | 16       | 6.58%   |
| 121-160 | 16       | 6.58%   |
| 161-240 | 5        | 2.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 170      | 72.96%  |
| 2     | 49       | 21.03%  |
| 3     | 6        | 2.58%   |
| 0     | 6        | 2.58%   |
| 4     | 2        | 0.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 123      | 37.16%  |
| Intel                                 | 105      | 31.72%  |
| Qualcomm Atheros                      | 22       | 6.65%   |
| Ralink Technology                     | 12       | 3.63%   |
| Broadcom                              | 10       | 3.02%   |
| TP-Link                               | 8        | 2.42%   |
| Marvell Technology Group              | 8        | 2.42%   |
| Ralink                                | 6        | 1.81%   |
| Nvidia                                | 5        | 1.51%   |
| Qualcomm Atheros Communications       | 4        | 1.21%   |
| Samsung Electronics                   | 3        | 0.91%   |
| NetGear                               | 3        | 0.91%   |
| Aquantia                              | 3        | 0.91%   |
| Microsoft                             | 2        | 0.6%    |
| Microchip Technology                  | 2        | 0.6%    |
| MediaTek                              | 2        | 0.6%    |
| IBM                                   | 2        | 0.6%    |
| Broadcom Limited                      | 2        | 0.6%    |
| ZTE WCDMA Technologies MSM            | 1        | 0.3%    |
| Wilocity                              | 1        | 0.3%    |
| Mellanox Technologies                 | 1        | 0.3%    |
| Edimax Technology                     | 1        | 0.3%    |
| DisplayLink                           | 1        | 0.3%    |
| D-Link                                | 1        | 0.3%    |
| Belkin Components                     | 1        | 0.3%    |
| ASUSTek Computer                      | 1        | 0.3%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 103      | 28.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 17       | 4.66%   |
| Intel Wi-Fi 6 AX200                                                 | 14       | 3.84%   |
| Intel I211 Gigabit Network Connection                               | 14       | 3.84%   |
| Realtek RTL8125 2.5GbE Controller                                   | 8        | 2.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 7        | 1.92%   |
| Intel Wireless-AC 9260                                              | 7        | 1.92%   |
| Intel Ethernet Connection I217-LM                                   | 7        | 1.92%   |
| Intel Ethernet Connection (2) I219-V                                | 7        | 1.92%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 7        | 1.92%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 5        | 1.37%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 5        | 1.37%   |
| Intel Ethernet Controller I225-V                                    | 5        | 1.37%   |
| Intel 82574L Gigabit Network Connection                             | 5        | 1.37%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 4        | 1.1%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 4        | 1.1%    |
| Ralink MT7601U Wireless Adapter                                     | 4        | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                               | 4        | 1.1%    |
| Intel Ethernet Connection (2) I218-V                                | 4        | 1.1%    |
| Qualcomm Atheros AR9271 802.11n                                     | 3        | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 3        | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 3        | 0.82%   |
| Intel Wireless 8265 / 8275                                          | 3        | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 3        | 0.82%   |
| Intel 82579V Gigabit Network Connection                             | 3        | 0.82%   |
| Intel 82578DM Gigabit Network Connection                            | 3        | 0.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 3        | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 2        | 0.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 2        | 0.55%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 2        | 0.55%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 2        | 0.55%   |
| Ralink RT5370 Wireless Adapter                                      | 2        | 0.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 2        | 0.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                           | 2        | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 2        | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 2        | 0.55%   |
| Nvidia MCP61 Ethernet                                               | 2        | 0.55%   |
| Nvidia CK804 Ethernet Controller                                    | 2        | 0.55%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller             | 2        | 0.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 2        | 0.55%   |
| Intel Ethernet Connection (7) I219-V                                | 2        | 0.55%   |
| Intel Ethernet Connection (5) I219-LM                               | 2        | 0.55%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.55%   |
| IBM RNDIS/CDC ETHER                                                 | 2        | 0.55%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                         | 2        | 0.55%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 0.55%   |
| ZTE WCDMA MSM Z6201V                                                | 1        | 0.27%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                  | 1        | 0.27%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                 | 1        | 0.27%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 1        | 0.27%   |
| TP-Link 802.11ac NIC                                                | 1        | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 1        | 0.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.27%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                 | 1        | 0.27%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                     | 1        | 0.27%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 1        | 0.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 1        | 0.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 32       | 28.57%  |
| Realtek Semiconductor                 | 24       | 21.43%  |
| Ralink Technology                     | 12       | 10.71%  |
| Qualcomm Atheros                      | 9        | 8.04%   |
| TP-Link                               | 8        | 7.14%   |
| Ralink                                | 6        | 5.36%   |
| Broadcom                              | 5        | 4.46%   |
| Qualcomm Atheros Communications       | 4        | 3.57%   |
| NetGear                               | 3        | 2.68%   |
| Microsoft                             | 2        | 1.79%   |
| Wilocity                              | 1        | 0.89%   |
| MediaTek                              | 1        | 0.89%   |
| Edimax Technology                     | 1        | 0.89%   |
| D-Link                                | 1        | 0.89%   |
| Belkin Components                     | 1        | 0.89%   |
| ASUSTek Computer                      | 1        | 0.89%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 14       | 12.17%  |
| Intel Wireless-AC 9260                                                        | 7        | 6.09%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 5        | 4.35%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 4        | 3.48%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 4        | 3.48%   |
| Ralink MT7601U Wireless Adapter                                               | 4        | 3.48%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3        | 2.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 3        | 2.61%   |
| Intel Wireless 8265 / 8275                                                    | 3        | 2.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 2.61%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 3        | 2.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2        | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 1.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 2        | 1.74%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 2        | 1.74%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 2        | 1.74%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 1.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 2        | 1.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 2        | 1.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2        | 1.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2        | 1.74%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                            | 1        | 0.87%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 0.87%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1        | 0.87%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.87%   |
| TP-Link 802.11ac NIC                                                          | 1        | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.87%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                           | 1        | 0.87%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 1        | 0.87%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1        | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 0.87%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1        | 0.87%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 0.87%   |
| Ralink RT2770 Wireless Adapter                                                | 1        | 0.87%   |
| Ralink RT2501/RT2573 Wireless Adapter                                         | 1        | 0.87%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 1        | 0.87%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 1        | 0.87%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                     | 1        | 0.87%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1        | 0.87%   |
| Ralink RT2800 802.11n PCI                                                     | 1        | 0.87%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.87%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 0.87%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1        | 0.87%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1        | 0.87%   |
| NetGear A6210                                                                 | 1        | 0.87%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                   | 1        | 0.87%   |
| Microsoft XBOX ACC                                                            | 1        | 0.87%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 0.87%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 1        | 0.87%   |
| Intel Wireless 8260                                                           | 1        | 0.87%   |
| Intel Wireless 7265                                                           | 1        | 0.87%   |
| Intel Wireless 7260                                                           | 1        | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1        | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 0.87%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1        | 0.87%   |
| D-Link 802.11n WLAN Adapter                                                   | 1        | 0.87%   |
| Broadcom Network controller                                                   | 1        | 0.87%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                            | 1        | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 112      | 45.53%  |
| Intel                      | 87       | 35.37%  |
| Qualcomm Atheros           | 15       | 6.1%    |
| Marvell Technology Group   | 8        | 3.25%   |
| Nvidia                     | 5        | 2.03%   |
| Broadcom                   | 5        | 2.03%   |
| Samsung Electronics        | 3        | 1.22%   |
| Aquantia                   | 3        | 1.22%   |
| IBM                        | 2        | 0.81%   |
| Broadcom Limited           | 2        | 0.81%   |
| ZTE WCDMA Technologies MSM | 1        | 0.41%   |
| Mellanox Technologies      | 1        | 0.41%   |
| MediaTek                   | 1        | 0.41%   |
| DisplayLink                | 1        | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 103      | 41.7%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17       | 6.88%   |
| Intel I211 Gigabit Network Connection                             | 14       | 5.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 3.24%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7        | 2.83%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.83%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 2.83%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7        | 2.83%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 5        | 2.02%   |
| Intel Ethernet Controller I225-V                                  | 5        | 2.02%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 2.02%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 1.62%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 1.21%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.21%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 1.21%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.81%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.81%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 0.81%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2        | 0.81%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.81%   |
| Intel Ethernet Connection (5) I219-LM                             | 2        | 0.81%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.81%   |
| IBM RNDIS/CDC ETHER                                               | 2        | 0.81%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                       | 2        | 0.81%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.81%   |
| ZTE WCDMA MSM Z6201V                                              | 1        | 0.4%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.4%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.4%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.4%    |
| Nvidia MCP67 Ethernet                                             | 1        | 0.4%    |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1        | 0.4%    |
| MediaTek moto e(6) plus                                           | 1        | 0.4%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.4%    |
| Intel Ethernet Connection I217-V                                  | 1        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.4%    |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.4%    |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.4%    |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.4%    |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.4%    |
| DisplayLink ThinkPad USB 3.0 Pro Dock                             | 1        | 0.4%    |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 0.4%    |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.4%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 0.4%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 0.4%    |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 1        | 0.4%    |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 223      | 67.37%  |
| WiFi     | 105      | 31.72%  |
| Modem    | 2        | 0.6%    |
| Unknown  | 1        | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 177      | 75.64%  |
| WiFi     | 57       | 24.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 136      | 60.18%  |
| 2     | 80       | 35.4%   |
| 3     | 9        | 3.98%   |
| 4     | 1        | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 201      | 86.64%  |
| Yes  | 31       | 13.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 29       | 45.31%  |
| Cambridge Silicon Radio         | 18       | 28.13%  |
| Broadcom                        | 4        | 6.25%   |
| Realtek Semiconductor           | 3        | 4.69%   |
| ASUSTek Computer                | 3        | 4.69%   |
| Ralink                          | 2        | 3.13%   |
| Qualcomm Atheros Communications | 2        | 3.13%   |
| MediaTek                        | 1        | 1.56%   |
| IMC Networks                    | 1        | 1.56%   |
| HTC (High Tech Computer)        | 1        | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 18       | 27.27%  |
| Intel AX200 Bluetooth                                                | 11       | 16.67%  |
| Intel Bluetooth Device                                               | 7        | 10.61%  |
| Intel Bluetooth wireless interface                                   | 6        | 9.09%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 4.55%   |
| Realtek Bluetooth Radio                                              | 2        | 3.03%   |
| Ralink RT3290 Bluetooth                                              | 2        | 3.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 2        | 3.03%   |
| Intel AX210 Bluetooth                                                | 2        | 3.03%   |
| Broadcom HP Portable Bumble Bee                                      | 2        | 3.03%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 3.03%   |
| ASUS Bluetooth Radio                                                 | 2        | 3.03%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 1.52%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 1.52%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 1.52%   |
| MediaTek Wireless_Device                                             | 1        | 1.52%   |
| IMC Networks Bluetooth Radio                                         | 1        | 1.52%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 1.52%   |
| ASUS Bluetooth Device                                                | 1        | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 133      | 34.82%  |
| AMD                     | 114      | 29.84%  |
| Nvidia                  | 78       | 20.42%  |
| Logitech                | 12       | 3.14%   |
| C-Media Electronics     | 10       | 2.62%   |
| Kingston Technology     | 5        | 1.31%   |
| SteelSeries ApS         | 3        | 0.79%   |
| Razer USA               | 2        | 0.52%   |
| JMTek                   | 2        | 0.52%   |
| GYROCOM C&C             | 2        | 0.52%   |
| GN Netcom               | 2        | 0.52%   |
| Generalplus Technology  | 2        | 0.52%   |
| AKAI Professional M.I.  | 2        | 0.52%   |
| XMOS                    | 1        | 0.26%   |
| Texas Instruments       | 1        | 0.26%   |
| RODE Microphones        | 1        | 0.26%   |
| RME                     | 1        | 0.26%   |
| Microsoft               | 1        | 0.26%   |
| Lenovo                  | 1        | 0.26%   |
| Jieli Technology        | 1        | 0.26%   |
| Giga-Byte Technology    | 1        | 0.26%   |
| Dell                    | 1        | 0.26%   |
| DCMT Technology         | 1        | 0.26%   |
| Creative Technology     | 1        | 0.26%   |
| Creative Labs           | 1        | 0.26%   |
| Cambridge Silicon Radio | 1        | 0.26%   |
| Astro Gaming            | 1        | 0.26%   |
| Apogee Electronics      | 1        | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                          | 25       | 5.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23       | 5.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 18       | 4%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 17       | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16       | 3.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 16       | 3.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15       | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14       | 3.11%   |
| Intel 200 Series PCH HD Audio                                                                     | 11       | 2.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9        | 2%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 9        | 2%      |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 8        | 1.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8        | 1.78%   |
| AMD Navi 10 HDMI Audio                                                                            | 8        | 1.78%   |
| AMD FCH Azalia Controller                                                                         | 8        | 1.78%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 7        | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7        | 1.56%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 7        | 1.56%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 7        | 1.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 7        | 1.56%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 6        | 1.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6        | 1.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 6        | 1.33%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 6        | 1.33%   |
| Nvidia High Definition Audio Controller                                                           | 5        | 1.11%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 5        | 1.11%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 5        | 1.11%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 5        | 1.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5        | 1.11%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4        | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4        | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4        | 0.89%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 4        | 0.89%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 4        | 0.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4        | 0.89%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 4        | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4        | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3        | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3        | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3        | 0.67%   |
| Logitech [G533 Wireless Headset Dongle]                                                           | 3        | 0.67%   |
| Logitech G733 Gaming Headset                                                                      | 3        | 0.67%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 3        | 0.67%   |
| Intel Comet Lake PCH cAVS                                                                         | 3        | 0.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3        | 0.67%   |
| Intel Audio device                                                                                | 3        | 0.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3        | 0.67%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3        | 0.67%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3        | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2        | 0.44%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2        | 0.44%   |
| Nvidia MCP61 High Definition Audio                                                                | 2        | 0.44%   |
| Nvidia GM200 High Definition Audio                                                                | 2        | 0.44%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2        | 0.44%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2        | 0.44%   |
| Nvidia CK804 AC'97 Audio Controller                                                               | 2        | 0.44%   |
| Logitech G930                                                                                     | 2        | 0.44%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2        | 0.44%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2        | 0.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 22       | 19.13%  |
| Kingston            | 16       | 13.91%  |
| SK hynix            | 12       | 10.43%  |
| Unknown             | 11       | 9.57%   |
| Samsung Electronics | 11       | 9.57%   |
| Crucial             | 10       | 8.7%    |
| A-DATA Technology   | 8        | 6.96%   |
| Corsair             | 7        | 6.09%   |
| Team                | 5        | 4.35%   |
| Micron Technology   | 5        | 4.35%   |
| Unknown (ABCD)      | 1        | 0.87%   |
| Transcend           | 1        | 0.87%   |
| Strontium           | 1        | 0.87%   |
| Ramaxel Technology  | 1        | 0.87%   |
| pqi                 | 1        | 0.87%   |
| PNY                 | 1        | 0.87%   |
| Nanya Technology    | 1        | 0.87%   |
| Elpida              | 1        | 0.87%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s             | 3        | 2.44%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                   | 2        | 1.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2        | 1.63%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s                 | 2        | 1.63%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 2        | 1.63%   |
| Kingston RAM 9905403-011.A03LF 2048MB DIMM 1333MT/s            | 2        | 1.63%   |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s      | 2        | 1.63%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s            | 2        | 1.63%   |
| G.Skill RAM F4-3200C16-8GTZB 8GB DIMM DDR4 3200MT/s            | 2        | 1.63%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 2        | 1.63%   |
| G.Skill RAM F4-2666C15-8GVR 8GB DIMM DDR4 2800MT/s             | 2        | 1.63%   |
| G.Skill RAM F3-1600C9-4GAB 4096MB DIMM DDR3 1600MT/s           | 2        | 1.63%   |
| G.Skill RAM F3-14900CL10-8GBXL 8GB DIMM DDR3 1867MT/s          | 2        | 1.63%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s          | 2        | 1.63%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 2        | 1.63%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 2        | 1.63%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 1        | 0.81%   |
| Unknown RAM Module 8GB DIMM 1066MT/s                           | 1        | 0.81%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                         | 1        | 0.81%   |
| Unknown RAM Module 4GB DIMM 800MT/s                            | 1        | 0.81%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1066MT/s                  | 1        | 0.81%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 1        | 0.81%   |
| Unknown RAM Module 4096MB DIMM DDR2 1067MT/s                   | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                    | 1        | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s | 1        | 0.81%   |
| Transcend RAM JM1333KLN-4GK 2048MB DIMM DDR3 1333MT/s          | 1        | 0.81%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s             | 1        | 0.81%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s            | 1        | 0.81%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s             | 1        | 0.81%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                  | 1        | 0.81%   |
| SK hynix RAM Module 1024MB DIMM DDR3 1333MT/s                  | 1        | 0.81%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.81%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8192MB DIMM DDR3 1600MT/s        | 1        | 0.81%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s           | 1        | 0.81%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1066MT/s           | 1        | 0.81%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s           | 1        | 0.81%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s      | 1        | 0.81%   |
| SK hynix RAM HMT325U6CFR8C-H9 2048MB DIMM DDR3 1333MT/s        | 1        | 0.81%   |
| SK hynix RAM HMT325U6CFR8C-H9 2048MB DIMM 1333MT/s             | 1        | 0.81%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s        | 1        | 0.81%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8192MB DIMM DDR4 2465MT/s        | 1        | 0.81%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                      | 1        | 0.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 0.81%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1        | 0.81%   |
| Samsung RAM M391A2K43BB1-CTD 16384MB DIMM DDR4 3600MT/s        | 1        | 0.81%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s            | 1        | 0.81%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 1        | 0.81%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s            | 1        | 0.81%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s            | 1        | 0.81%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 1        | 0.81%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s            | 1        | 0.81%   |
| Ramaxel RAM RMR5030MM58E8F1600 2GB DIMM DDR3 1600MT/s          | 1        | 0.81%   |
| pqi RAM Module 1GB DIMM DDR2 667MT/s                           | 1        | 0.81%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s           | 1        | 0.81%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s             | 1        | 0.81%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                       | 1        | 0.81%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2400MT/s             | 1        | 0.81%   |
| Micron RAM 18KSF1G72PDZ-1G6N1 8GB DIMM DDR3 1333MT/s           | 1        | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 44       | 46.32%  |
| DDR3    | 38       | 40%     |
| Unknown | 5        | 5.26%   |
| SDRAM   | 4        | 4.21%   |
| DDR2    | 3        | 3.16%   |
| LPDDR4  | 1        | 1.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 89       | 95.7%   |
| SODIMM | 4        | 4.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 40       | 38.83%  |
| 16384 | 22       | 21.36%  |
| 4096  | 22       | 21.36%  |
| 2048  | 13       | 12.62%  |
| 32768 | 3        | 2.91%   |
| 1024  | 3        | 2.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 23       | 21.9%   |
| 3600  | 17       | 16.19%  |
| 1333  | 11       | 10.48%  |
| 3200  | 9        | 8.57%   |
| 2667  | 5        | 4.76%   |
| 2400  | 5        | 4.76%   |
| 1867  | 5        | 4.76%   |
| 2666  | 4        | 3.81%   |
| 2133  | 4        | 3.81%   |
| 3733  | 3        | 2.86%   |
| 1066  | 3        | 2.86%   |
| 800   | 3        | 2.86%   |
| 667   | 3        | 2.86%   |
| 3400  | 2        | 1.9%    |
| 2800  | 2        | 1.9%    |
| 3466  | 1        | 0.95%   |
| 2933  | 1        | 0.95%   |
| 2465  | 1        | 0.95%   |
| 2000  | 1        | 0.95%   |
| 1800  | 1        | 0.95%   |
| 1067  | 1        | 0.95%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 7        | 41.18%  |
| Hewlett-Packard    | 5        | 29.41%  |
| Canon              | 3        | 17.65%  |
| Fuji Xerox         | 1        | 5.88%   |
| Dymo-CoStar        | 1        | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| HP Officejet 4630 series         | 2        | 11.76%  |
| Brother Printer                  | 2        | 11.76%  |
| HP LaserJet Professional P1102w  | 1        | 5.88%   |
| HP ENVY 4520 series              | 1        | 5.88%   |
| HP DeskJet 2130 series           | 1        | 5.88%   |
| Fuji Xerox DocuPrint CM315/318 z | 1        | 5.88%   |
| Dymo-CoStar LabelWriter 450      | 1        | 5.88%   |
| Canon TS3100 series              | 1        | 5.88%   |
| Canon MB5300 series              | 1        | 5.88%   |
| Canon i950                       | 1        | 5.88%   |
| Brother MFC-J430W                | 1        | 5.88%   |
| Brother MFC-9140CDN              | 1        | 5.88%   |
| Brother HL-L3230CDW series       | 1        | 5.88%   |
| Brother HL-2270DW Laser Printer  | 1        | 5.88%   |
| Brother HL-1430 Laser Printer    | 1        | 5.88%   |

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


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Canon CanoScan LiDE 500F | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 23       | 54.76%  |
| Microdia                 | 4        | 9.52%   |
| Samsung Electronics      | 3        | 7.14%   |
| ARC International        | 3        | 7.14%   |
| GEMBIRD                  | 2        | 4.76%   |
| Z-Star Microelectronics  | 1        | 2.38%   |
| Xiongmai                 | 1        | 2.38%   |
| Realtek Semiconductor    | 1        | 2.38%   |
| Novatek Microelectronics | 1        | 2.38%   |
| Lenovo                   | 1        | 2.38%   |
| Google                   | 1        | 2.38%   |
| Chicony Electronics      | 1        | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 5        | 11.9%   |
| Logitech Webcam C170                              | 4        | 9.52%   |
| Samsung Galaxy A5 (MTP)                           | 3        | 7.14%   |
| Logitech QuickCam Pro 9000                        | 3        | 7.14%   |
| ARC International Camera                          | 3        | 7.14%   |
| Logitech Webcam Pro 9000                          | 2        | 4.76%   |
| Logitech Webcam C600                              | 2        | 4.76%   |
| Logitech HD Pro Webcam C920                       | 2        | 4.76%   |
| Logitech C922 Pro Stream Webcam                   | 2        | 4.76%   |
| Z-Star Venus USB2.0 Camera                        | 1        | 2.38%   |
| Xiongmai web camera                               | 1        | 2.38%   |
| Realtek USB CAMERA                                | 1        | 2.38%   |
| Novatek HP High Definition 2MP Webcam             | 1        | 2.38%   |
| Microdia USB Microscope                           | 1        | 2.38%   |
| Microdia Sonix USB 2.0 Camera                     | 1        | 2.38%   |
| Microdia Integrated Camera                        | 1        | 2.38%   |
| Microdia Camera                                   | 1        | 2.38%   |
| Logitech Webcam C300                              | 1        | 2.38%   |
| Logitech Mic (Fusion)                             | 1        | 2.38%   |
| Logitech HD Webcam C525                           | 1        | 2.38%   |
| Lenovo FULL HD 1080P Webcam                       | 1        | 2.38%   |
| Google Nexus/Pixel Device (MTP + debug)           | 1        | 2.38%   |
| GEMBIRD USB2.0 PC CAMERA                          | 1        | 2.38%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 2.38%   |
| Chicony HP High Definition 1MP Webcam             | 1        | 2.38%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 196      | 84.85%  |
| 1     | 31       | 13.42%  |
| 2     | 3        | 1.3%    |
| 5     | 1        | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 12       | 31.58%  |
| Net/wireless             | 11       | 28.95%  |
| Bluetooth                | 3        | 7.89%   |
| Unassigned class         | 2        | 5.26%   |
| Storage/ide              | 2        | 5.26%   |
| Multimedia controller    | 2        | 5.26%   |
| Dvb card                 | 2        | 5.26%   |
| Communication controller | 2        | 5.26%   |
| Storage/raid             | 1        | 2.63%   |
| Sound                    | 1        | 2.63%   |

