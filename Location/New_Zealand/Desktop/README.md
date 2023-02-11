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

Total: 429

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0D28YY A01                  | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eb4687961f](https://linux-hardware.org/?probe=eb4687961f) | Jan 31, 2023 |
| ASRock        | 890GM Pro3                  | [b2bb32cbbc](https://linux-hardware.org/?probe=b2bb32cbbc) | Jan 31, 2023 |
| Gigabyte      | B75M-D3H                    | [b5ca740834](https://linux-hardware.org/?probe=b5ca740834) | Jan 28, 2023 |
| ASUSTek       | PRIME H310M-K               | [ec43ef5c17](https://linux-hardware.org/?probe=ec43ef5c17) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d27e517254](https://linux-hardware.org/?probe=d27e517254) | Jan 21, 2023 |
| DFI           | CR101-CST                   | [604ce5b10f](https://linux-hardware.org/?probe=604ce5b10f) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [02089f3393](https://linux-hardware.org/?probe=02089f3393) | Jan 20, 2023 |
| Dell          | 0D28YY A01                  | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| Gigabyte      | B550M DS3H AC               | [dae35d1c18](https://linux-hardware.org/?probe=dae35d1c18) | Jan 19, 2023 |
| MSI           | MAG B550M MORTAR            | [bcae5d5664](https://linux-hardware.org/?probe=bcae5d5664) | Jan 18, 2023 |
| ASUSTek       | Z97M-PLUS                   | [ea58101334](https://linux-hardware.org/?probe=ea58101334) | Jan 17, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [18e82e414a](https://linux-hardware.org/?probe=18e82e414a) | Jan 11, 2023 |
| Dell          | 09KPNV A01                  | [aaf51b3c3b](https://linux-hardware.org/?probe=aaf51b3c3b) | Jan 09, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| HP            | ProLiant ML350p Gen8        | [8a7807ff8c](https://linux-hardware.org/?probe=8a7807ff8c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | [1b66a8a1a8](https://linux-hardware.org/?probe=1b66a8a1a8) | Jan 02, 2023 |
| Dell          | 09KPNV A01                  | [3f2b642eb0](https://linux-hardware.org/?probe=3f2b642eb0) | Jan 01, 2023 |
| HP            | 3648h                       | [5b3a2d7e48](https://linux-hardware.org/?probe=5b3a2d7e48) | Dec 25, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [03c35b7588](https://linux-hardware.org/?probe=03c35b7588) | Dec 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fe5df748b0](https://linux-hardware.org/?probe=fe5df748b0) | Dec 23, 2022 |
| Dell          | 09KPNV A01                  | [534f769938](https://linux-hardware.org/?probe=534f769938) | Dec 22, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [39bac65c16](https://linux-hardware.org/?probe=39bac65c16) | Dec 18, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [967204fede](https://linux-hardware.org/?probe=967204fede) | Dec 09, 2022 |
| Gigabyte      | H77M-D3H                    | [5a6ebebd51](https://linux-hardware.org/?probe=5a6ebebd51) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [68004f52cd](https://linux-hardware.org/?probe=68004f52cd) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [3912675c64](https://linux-hardware.org/?probe=3912675c64) | Dec 06, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1b361e2f17](https://linux-hardware.org/?probe=1b361e2f17) | Dec 02, 2022 |
| HP            | 1495                        | [138b5bb823](https://linux-hardware.org/?probe=138b5bb823) | Dec 01, 2022 |
| ASUSTek       | M4A87TD/USB3                | [81a2eaf6e4](https://linux-hardware.org/?probe=81a2eaf6e4) | Nov 24, 2022 |
| ASUSTek       | P5GC-MX/1333                | [dd85fb5c80](https://linux-hardware.org/?probe=dd85fb5c80) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [9d942ddc9c](https://linux-hardware.org/?probe=9d942ddc9c) | Nov 13, 2022 |
| HP            | 339A                        | [c995f831b8](https://linux-hardware.org/?probe=c995f831b8) | Nov 13, 2022 |
| Gigabyte      | H77M-D3H                    | [2382574dbd](https://linux-hardware.org/?probe=2382574dbd) | Nov 12, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [226409c98f](https://linux-hardware.org/?probe=226409c98f) | Nov 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b414369067](https://linux-hardware.org/?probe=b414369067) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [27bc8e172c](https://linux-hardware.org/?probe=27bc8e172c) | Nov 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9e7c028b0b](https://linux-hardware.org/?probe=9e7c028b0b) | Oct 27, 2022 |
| Gigabyte      | B560M DS3H AC               | [e939a5f236](https://linux-hardware.org/?probe=e939a5f236) | Oct 19, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [93698d1670](https://linux-hardware.org/?probe=93698d1670) | Oct 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| Gigabyte      | H270-Gaming 3               | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| ASUSTek       | M5A97 R2.0                  | [9b3c73c104](https://linux-hardware.org/?probe=9b3c73c104) | Sep 28, 2022 |
| ASUSTek       | M5A97 R2.0                  | [4cdcef3ebd](https://linux-hardware.org/?probe=4cdcef3ebd) | Sep 28, 2022 |
| ASUSTek       | P5G41T-M LX                 | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | [74e31be1be](https://linux-hardware.org/?probe=74e31be1be) | Sep 19, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9bfc1472d1](https://linux-hardware.org/?probe=9bfc1472d1) | Sep 16, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [4db3f9151e](https://linux-hardware.org/?probe=4db3f9151e) | Sep 11, 2022 |
| Gigabyte      | Z68AP-D3                    | [1ac8cbcc47](https://linux-hardware.org/?probe=1ac8cbcc47) | Sep 10, 2022 |
| Dell          | 0T10XW A02                  | [33faaf5341](https://linux-hardware.org/?probe=33faaf5341) | Sep 10, 2022 |
| Dell          | 0M863N A01                  | [a353883ee2](https://linux-hardware.org/?probe=a353883ee2) | Sep 07, 2022 |
| MSI           | MS-98H3                     | [41ad960dd6](https://linux-hardware.org/?probe=41ad960dd6) | Sep 06, 2022 |
| Gigabyte      | B85M-HD3                    | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Gigabyte      | M61PME-S2                   | [8f8107b683](https://linux-hardware.org/?probe=8f8107b683) | Aug 27, 2022 |
| Gigabyte      | M61PME-S2                   | [e3b89ab2db](https://linux-hardware.org/?probe=e3b89ab2db) | Aug 27, 2022 |
| Dell          | 073MMW A03                  | [b41e0fcad5](https://linux-hardware.org/?probe=b41e0fcad5) | Aug 24, 2022 |
| ASUSTek       | PRIME Z370-A II             | [d7dee32799](https://linux-hardware.org/?probe=d7dee32799) | Aug 23, 2022 |
| ASRock        | 890GM Pro3                  | [51f5d50d85](https://linux-hardware.org/?probe=51f5d50d85) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | [002a0c3f5a](https://linux-hardware.org/?probe=002a0c3f5a) | Aug 22, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [b12d6e7967](https://linux-hardware.org/?probe=b12d6e7967) | Aug 20, 2022 |
| Gigabyte      | B560M DS3H AC               | [c9e9691195](https://linux-hardware.org/?probe=c9e9691195) | Aug 10, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [ca1d7dd61b](https://linux-hardware.org/?probe=ca1d7dd61b) | Aug 03, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [4956d72048](https://linux-hardware.org/?probe=4956d72048) | Aug 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [163affcbb8](https://linux-hardware.org/?probe=163affcbb8) | Aug 01, 2022 |
| HP            | 8054                        | [3b76696319](https://linux-hardware.org/?probe=3b76696319) | Jul 27, 2022 |
| Intel         | STK1AW32SC H91596-307       | [78225ba5b9](https://linux-hardware.org/?probe=78225ba5b9) | Jul 21, 2022 |
| HP            | 3397                        | [83bdaea8fc](https://linux-hardware.org/?probe=83bdaea8fc) | Jul 17, 2022 |
| Gigabyte      | H87M-D3H                    | [5056c4f640](https://linux-hardware.org/?probe=5056c4f640) | Jul 13, 2022 |
| Gigabyte      | B460M D3H                   | [d620225518](https://linux-hardware.org/?probe=d620225518) | Jun 30, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [86a93d8ea0](https://linux-hardware.org/?probe=86a93d8ea0) | Jun 29, 2022 |
| Alienware     | 01NYPT A00                  | [97b8d855bd](https://linux-hardware.org/?probe=97b8d855bd) | Jun 28, 2022 |
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
| Ubuntu 20.04                 | 36       | 12.46%  |
| Ubuntu 18.04                 | 32       | 11.07%  |
| Pop!_OS 20.10                | 9        | 3.11%   |
| Arch Rolling                 | 9        | 3.11%   |
| Pop!_OS 20.04                | 8        | 2.77%   |
| Ubuntu 20.10                 | 7        | 2.42%   |
| Linux Mint 20.1              | 7        | 2.42%   |
| Ubuntu 22.04                 | 6        | 2.08%   |
| Ubuntu 21.04                 | 6        | 2.08%   |
| Ubuntu 18.10                 | 6        | 2.08%   |
| Manjaro                      | 6        | 2.08%   |
| Pop!_OS 21.10                | 5        | 1.73%   |
| Pop!_OS 21.04                | 5        | 1.73%   |
| Linux Mint 20.3              | 5        | 1.73%   |
| KDE neon 20.04               | 5        | 1.73%   |
| Fedora 36                    | 5        | 1.73%   |
| Fedora 34                    | 5        | 1.73%   |
| Zorin 16                     | 4        | 1.38%   |
| Ubuntu 16.04                 | 4        | 1.38%   |
| Linux Mint 20                | 4        | 1.38%   |
| Fedora 33                    | 4        | 1.38%   |
| Debian 11                    | 4        | 1.38%   |
| Debian 10                    | 4        | 1.38%   |
| Ubuntu 21.10                 | 3        | 1.04%   |
| Ubuntu 19.10                 | 3        | 1.04%   |
| Ubuntu 19.04                 | 3        | 1.04%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.04%   |
| OpenMandriva 4.50            | 3        | 1.04%   |
| OpenMandriva 4.3             | 3        | 1.04%   |
| OpenMandriva 4.2             | 3        | 1.04%   |
| Linux Mint 20.2              | 3        | 1.04%   |
| Kubuntu 22.04                | 3        | 1.04%   |
| Kubuntu 20.04                | 3        | 1.04%   |
| Fedora 31                    | 3        | 1.04%   |
| Xubuntu 20.04                | 2        | 0.69%   |
| ROSA R11                     | 2        | 0.69%   |
| OpenMandriva 23.01           | 2        | 0.69%   |
| Lubuntu 20.04                | 2        | 0.69%   |
| Linux Mint 21                | 2        | 0.69%   |
| Linux Mint 19.3              | 2        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 101      | 38.11%  |
| Linux Mint   | 25       | 9.43%   |
| Pop!_OS      | 24       | 9.06%   |
| Fedora       | 20       | 7.55%   |
| OpenMandriva | 11       | 4.15%   |
| Arch         | 11       | 4.15%   |
| Manjaro      | 10       | 3.77%   |
| Endless      | 9        | 3.4%    |
| Debian       | 9        | 3.4%    |
| KDE neon     | 7        | 2.64%   |
| Kubuntu      | 6        | 2.26%   |
| Zorin        | 5        | 1.89%   |
| Xubuntu      | 3        | 1.13%   |
| openSUSE     | 3        | 1.13%   |
| Ubuntu Unity | 2        | 0.75%   |
| ROSA         | 2        | 0.75%   |
| Lubuntu      | 2        | 0.75%   |
| Devuan       | 2        | 0.75%   |
| Ubuntu MATE  | 1        | 0.38%   |
| RHEL         | 1        | 0.38%   |
| Regata OS    | 1        | 0.38%   |
| Redcore      | 1        | 0.38%   |
| Peppermint   | 1        | 0.38%   |
| Nobara       | 1        | 0.38%   |
| NixOS        | 1        | 0.38%   |
| MX           | 1        | 0.38%   |
| Linux Lite   | 1        | 0.38%   |
| Gentoo       | 1        | 0.38%   |
| Elementary   | 1        | 0.38%   |
| Deepin       | 1        | 0.38%   |
| ArcoLinux    | 1        | 0.38%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 6        | 1.77%   |
| 5.4.0-7634-generic       | 5        | 1.47%   |
| 5.4.0-52-generic         | 5        | 1.47%   |
| 5.3.0-46-generic         | 5        | 1.47%   |
| 5.15.0-46-generic        | 5        | 1.47%   |
| 5.13.0-30-generic        | 4        | 1.18%   |
| 5.11.0-37-generic        | 4        | 1.18%   |
| 5.8.0-50-generic         | 3        | 0.88%   |
| 5.8.0-44-generic         | 3        | 0.88%   |
| 5.4.0-65-generic         | 3        | 0.88%   |
| 5.4.0-33-generic         | 3        | 0.88%   |
| 5.3.0-40-generic         | 3        | 0.88%   |
| 5.16.7-desktop-1omv4003  | 3        | 0.88%   |
| 5.15.0-56-generic        | 3        | 0.88%   |
| 5.13.0-7614-generic      | 3        | 0.88%   |
| 5.13.0-39-generic        | 3        | 0.88%   |
| 5.11.0-7614-generic      | 3        | 0.88%   |
| 5.11.0-34-generic        | 3        | 0.88%   |
| 5.10.14-desktop-1omv4002 | 3        | 0.88%   |
| 5.0.0-37-generic         | 3        | 0.88%   |
| 4.18.0-25-generic        | 3        | 0.88%   |
| 6.1.1-desktop-1omv2290   | 2        | 0.59%   |
| 5.9.16-200.fc33.x86_64   | 2        | 0.59%   |
| 5.8.0-7630-generic       | 2        | 0.59%   |
| 5.8.0-59-generic         | 2        | 0.59%   |
| 5.8.0-55-generic         | 2        | 0.59%   |
| 5.8.0-43-generic         | 2        | 0.59%   |
| 5.8.0-33-generic         | 2        | 0.59%   |
| 5.8.0-14-generic         | 2        | 0.59%   |
| 5.4.0-77-generic         | 2        | 0.59%   |
| 5.4.0-7642-generic       | 2        | 0.59%   |
| 5.4.0-74-generic         | 2        | 0.59%   |
| 5.4.0-58-generic         | 2        | 0.59%   |
| 5.4.0-54-generic         | 2        | 0.59%   |
| 5.4.0-19-generic         | 2        | 0.59%   |
| 5.4.0-125-generic        | 2        | 0.59%   |
| 5.3.0-42-generic         | 2        | 0.59%   |
| 5.3.0-12-generic         | 2        | 0.59%   |
| 5.18.13-200.fc36.x86_64  | 2        | 0.59%   |
| 5.15.15-76051515-generic | 2        | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 50       | 16.5%   |
| 4.15.0  | 25       | 8.25%   |
| 5.8.0   | 23       | 7.59%   |
| 5.11.0  | 23       | 7.59%   |
| 5.13.0  | 19       | 6.27%   |
| 5.15.0  | 18       | 5.94%   |
| 5.3.0   | 16       | 5.28%   |
| 4.18.0  | 14       | 4.62%   |
| 5.0.0   | 8        | 2.64%   |
| 5.10.0  | 6        | 1.98%   |
| 5.9.16  | 3        | 0.99%   |
| 5.19.0  | 3        | 0.99%   |
| 5.16.7  | 3        | 0.99%   |
| 5.10.15 | 3        | 0.99%   |
| 5.10.14 | 3        | 0.99%   |
| 6.1.7   | 2        | 0.66%   |
| 6.1.6   | 2        | 0.66%   |
| 6.1.1   | 2        | 0.66%   |
| 5.8.12  | 2        | 0.66%   |
| 5.7.0   | 2        | 0.66%   |
| 5.6.11  | 2        | 0.66%   |
| 5.18.5  | 2        | 0.66%   |
| 5.18.13 | 2        | 0.66%   |
| 5.17.4  | 2        | 0.66%   |
| 5.15.8  | 2        | 0.66%   |
| 5.15.15 | 2        | 0.66%   |
| 5.15.11 | 2        | 0.66%   |
| 6.1.8   | 1        | 0.33%   |
| 6.1.4   | 1        | 0.33%   |
| 6.0.7   | 1        | 0.33%   |
| 6.0.5   | 1        | 0.33%   |
| 6.0.2   | 1        | 0.33%   |
| 6.0.17  | 1        | 0.33%   |
| 6.0.12  | 1        | 0.33%   |
| 5.9.8   | 1        | 0.33%   |
| 5.9.14  | 1        | 0.33%   |
| 5.9.1   | 1        | 0.33%   |
| 5.9.0   | 1        | 0.33%   |
| 5.8.3   | 1        | 0.33%   |
| 5.8.1   | 1        | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 53       | 17.73%  |
| 5.15    | 28       | 9.36%   |
| 5.11    | 28       | 9.36%   |
| 5.8     | 27       | 9.03%   |
| 4.15    | 25       | 8.36%   |
| 5.13    | 22       | 7.36%   |
| 5.3     | 18       | 6.02%   |
| 4.18    | 14       | 4.68%   |
| 5.10    | 13       | 4.35%   |
| 5.0     | 9        | 3.01%   |
| 6.1     | 8        | 2.68%   |
| 5.19    | 8        | 2.68%   |
| 5.9     | 7        | 2.34%   |
| 5.7     | 6        | 2.01%   |
| 5.6     | 5        | 1.67%   |
| 5.18    | 5        | 1.67%   |
| 5.16    | 5        | 1.67%   |
| 5.14    | 4        | 1.34%   |
| 5.12    | 4        | 1.34%   |
| 6.0     | 3        | 1%      |
| 5.17    | 3        | 1%      |
| 4.19    | 2        | 0.67%   |
| 5.5     | 1        | 0.33%   |
| 5.2     | 1        | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 254      | 99.61%  |
| i686   | 1        | 0.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 127      | 47.04%  |
| Unknown    | 44       | 16.3%   |
| KDE5       | 35       | 12.96%  |
| X-Cinnamon | 23       | 8.52%   |
| XFCE       | 13       | 4.81%   |
| KDE        | 11       | 4.07%   |
| MATE       | 7        | 2.59%   |
| Unity      | 2        | 0.74%   |
| LXQt       | 2        | 0.74%   |
| LXDE       | 2        | 0.74%   |
| Cinnamon   | 2        | 0.74%   |
| Pantheon   | 1        | 0.37%   |
| Deepin     | 1        | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 200      | 77.22%  |
| Wayland | 27       | 10.42%  |
| Unknown | 25       | 9.65%   |
| Tty     | 7        | 2.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 161      | 60.3%   |
| SDDM    | 33       | 12.36%  |
| LightDM | 21       | 7.87%   |
| GDM     | 20       | 7.49%   |
| GDM3    | 18       | 6.74%   |
| TDM     | 11       | 4.12%   |
| SLiM    | 3        | 1.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_NZ   | 152      | 56.3%   |
| en_US   | 53       | 19.63%  |
| Unknown | 43       | 15.93%  |
| en_AU   | 9        | 3.33%   |
| en_GB   | 7        | 2.59%   |
| C       | 4        | 1.48%   |
| zh_CN   | 2        | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 157      | 59.25%  |
| EFI  | 108      | 40.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 207      | 79.62%  |
| Btrfs   | 17       | 6.54%   |
| Overlay | 15       | 5.77%   |
| Unknown | 13       | 5%      |
| Zfs     | 3        | 1.15%   |
| Xfs     | 2        | 0.77%   |
| Tmpfs   | 1        | 0.38%   |
| F2fs    | 1        | 0.38%   |
| Ext3    | 1        | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 168      | 63.88%  |
| GPT     | 77       | 29.28%  |
| MBR     | 18       | 6.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 217      | 82.82%  |
| Yes       | 45       | 17.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 178      | 68.2%   |
| Yes       | 83       | 31.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 70       | 27.45%  |
| ASUSTek Computer    | 66       | 25.88%  |
| Hewlett-Packard     | 35       | 13.73%  |
| ASRock              | 19       | 7.45%   |
| MSI                 | 16       | 6.27%   |
| Dell                | 15       | 5.88%   |
| Lenovo              | 9        | 3.53%   |
| Intel               | 7        | 2.75%   |
| Unknown             | 3        | 1.18%   |
| IBM                 | 2        | 0.78%   |
| Acer                | 2        | 0.78%   |
| Supermicro          | 1        | 0.39%   |
| Pegatron            | 1        | 0.39%   |
| OEM                 | 1        | 0.39%   |
| MediaVue            | 1        | 0.39%   |
| JGINYUE             | 1        | 0.39%   |
| Huanan              | 1        | 0.39%   |
| DFI                 | 1        | 0.39%   |
| Colorful Technology | 1        | 0.39%   |
| Biostar             | 1        | 0.39%   |
| Alienware           | 1        | 0.39%   |
| AAEON               | 1        | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Gigabyte H77M-D3H               | 6        | 2.35%   |
| ASUS All Series                 | 5        | 1.96%   |
| ASUS TUF Gaming X570-PLUS       | 4        | 1.57%   |
| MSI MS-7B89                     | 3        | 1.18%   |
| HP EliteDesk 800 G1 SFF         | 3        | 1.18%   |
| HP Compaq 8200 Elite SFF PC     | 3        | 1.18%   |
| Gigabyte B75M-D3H               | 3        | 1.18%   |
| Gigabyte 970A-D3P               | 3        | 1.18%   |
| ASRock B450M Steel Legend       | 3        | 1.18%   |
| Unknown                         | 3        | 1.18%   |
| MSI MS-7C91                     | 2        | 0.78%   |
| MSI MS-7C02                     | 2        | 0.78%   |
| Lenovo ThinkCentre M58p 7479RS2 | 2        | 0.78%   |
| HP ProDesk 600 G1 SFF           | 2        | 0.78%   |
| HP Compaq Pro 6300 SFF          | 2        | 0.78%   |
| HP Compaq Elite 8300 USDT       | 2        | 0.78%   |
| HP Compaq Elite 8300 SFF        | 2        | 0.78%   |
| HP Compaq 8100 Elite SFF PC     | 2        | 0.78%   |
| HP Compaq 6200 Pro SFF PC       | 2        | 0.78%   |
| Gigabyte Z77X-D3H               | 2        | 0.78%   |
| Gigabyte Z68AP-D3               | 2        | 0.78%   |
| Gigabyte GA-78LMT-USB3          | 2        | 0.78%   |
| Gigabyte F2A75M-D3H             | 2        | 0.78%   |
| Gigabyte F2A55M-DS2             | 2        | 0.78%   |
| Gigabyte B550M DS3H             | 2        | 0.78%   |
| Gigabyte B450M S2H              | 2        | 0.78%   |
| Gigabyte AB350-Gaming           | 2        | 0.78%   |
| Dell OptiPlex 3010              | 2        | 0.78%   |
| ASUS SABERTOOTH 990FX R2.0      | 2        | 0.78%   |
| ASUS ROG STRIX X570-E GAMING    | 2        | 0.78%   |
| ASUS ROG STRIX B550-F GAMING    | 2        | 0.78%   |
| ASUS PRIME B450-PLUS            | 2        | 0.78%   |
| ASUS PRIME B350M-A              | 2        | 0.78%   |
| ASRock A320M-HDV                | 2        | 0.78%   |
| ASRock 970 Pro3 R2.0            | 2        | 0.78%   |
| Supermicro X8SIL                | 1        | 0.39%   |
| Pegatron CQ3320AN               | 1        | 0.39%   |
| OEM H81U                        | 1        | 0.39%   |
| MSI PPPPP-CCC#MMMMMMMM          | 1        | 0.39%   |
| MSI p6-2302a                    | 1        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| HP Compaq              | 17       | 6.67%   |
| ASUS ROG               | 16       | 6.27%   |
| ASUS PRIME             | 13       | 5.1%    |
| Dell OptiPlex          | 9        | 3.53%   |
| Lenovo ThinkCentre     | 7        | 2.75%   |
| ASUS TUF               | 7        | 2.75%   |
| HP EliteDesk           | 6        | 2.35%   |
| Gigabyte H77M-D3H      | 6        | 2.35%   |
| ASUS All               | 5        | 1.96%   |
| Dell Precision         | 4        | 1.57%   |
| MSI MS-7B89            | 3        | 1.18%   |
| HP ProLiant            | 3        | 1.18%   |
| Gigabyte GA-78LMT-USB3 | 3        | 1.18%   |
| Gigabyte B75M-D3H      | 3        | 1.18%   |
| Gigabyte B550M         | 3        | 1.18%   |
| Gigabyte AB350-Gaming  | 3        | 1.18%   |
| Gigabyte 970A-D3P      | 3        | 1.18%   |
| ASRock B450M           | 3        | 1.18%   |
| Unknown                | 3        | 1.18%   |
| MSI MS-7C91            | 2        | 0.78%   |
| MSI MS-7C02            | 2        | 0.78%   |
| IBM System             | 2        | 0.78%   |
| HP ProDesk             | 2        | 0.78%   |
| Gigabyte Z77X-D3H      | 2        | 0.78%   |
| Gigabyte Z68AP-D3      | 2        | 0.78%   |
| Gigabyte X570          | 2        | 0.78%   |
| Gigabyte F2A75M-D3H    | 2        | 0.78%   |
| Gigabyte F2A55M-DS2    | 2        | 0.78%   |
| Gigabyte B560M         | 2        | 0.78%   |
| Gigabyte B450M         | 2        | 0.78%   |
| ASUS SABERTOOTH        | 2        | 0.78%   |
| ASUS P7P55D-E          | 2        | 0.78%   |
| ASUS P5G41T-M          | 2        | 0.78%   |
| ASUS M5A97             | 2        | 0.78%   |
| ASRock A320M-HDV       | 2        | 0.78%   |
| ASRock 970             | 2        | 0.78%   |
| Acer Aspire            | 2        | 0.78%   |
| Supermicro X8SIL       | 1        | 0.39%   |
| Pegatron CQ3320AN      | 1        | 0.39%   |
| OEM H81U               | 1        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 47       | 18.43%  |
| 2019    | 28       | 10.98%  |
| 2011    | 22       | 8.63%   |
| 2013    | 21       | 8.24%   |
| 2018    | 20       | 7.84%   |
| 2020    | 19       | 7.45%   |
| 2017    | 19       | 7.45%   |
| 2014    | 13       | 5.1%    |
| 2010    | 13       | 5.1%    |
| 2009    | 12       | 4.71%   |
| 2008    | 12       | 4.71%   |
| 2015    | 11       | 4.31%   |
| 2021    | 6        | 2.35%   |
| 2016    | 4        | 1.57%   |
| 2007    | 3        | 1.18%   |
| 2005    | 2        | 0.78%   |
| 2022    | 1        | 0.39%   |
| 2004    | 1        | 0.39%   |
| Unknown | 1        | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 255      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 245      | 96.08%  |
| Enabled  | 10       | 3.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 254      | 99.61%  |
| Yes  | 1        | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 77       | 29.17%  |
| 8.01-16.0   | 53       | 20.08%  |
| 32.01-64.0  | 46       | 17.42%  |
| 4.01-8.0    | 33       | 12.5%   |
| 3.01-4.0    | 31       | 11.74%  |
| 64.01-256.0 | 11       | 4.17%   |
| 24.01-32.0  | 6        | 2.27%   |
| 1.01-2.0    | 5        | 1.89%   |
| 2.01-3.0    | 2        | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 99       | 33.45%  |
| 2.01-3.0   | 79       | 26.69%  |
| 4.01-8.0   | 46       | 15.54%  |
| 3.01-4.0   | 33       | 11.15%  |
| 8.01-16.0  | 18       | 6.08%   |
| 0.51-1.0   | 14       | 4.73%   |
| 16.01-24.0 | 3        | 1.01%   |
| 0.01-0.5   | 3        | 1.01%   |
| 32.01-64.0 | 1        | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 91       | 33.46%  |
| 2      | 86       | 31.62%  |
| 3      | 44       | 16.18%  |
| 4      | 29       | 10.66%  |
| 5      | 9        | 3.31%   |
| 6      | 7        | 2.57%   |
| 7      | 3        | 1.1%    |
| 8      | 2        | 0.74%   |
| 20     | 1        | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 51.72%  |
| Yes       | 126      | 48.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 254      | 99.61%  |
| No        | 1        | 0.39%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 142      | 54.83%  |
| Yes       | 117      | 45.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 184      | 71.6%   |
| Yes       | 73       | 28.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| New Zealand | 255      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Auckland         | 129      | 48.13%  |
| Wellington       | 33       | 12.31%  |
| Christchurch     | 31       | 11.57%  |
| Hamilton         | 16       | 5.97%   |
| Tauranga         | 11       | 4.1%    |
| Dunedin          | 8        | 2.99%   |
| Palmerston North | 7        | 2.61%   |
| Whangarei        | 4        | 1.49%   |
| Napier City      | 4        | 1.49%   |
| Whanganui        | 2        | 0.75%   |
| New Plymouth     | 2        | 0.75%   |
| Nelson           | 2        | 0.75%   |
| Invercargill     | 2        | 0.75%   |
| Cambridge        | 2        | 0.75%   |
| Westport         | 1        | 0.37%   |
| Wellsford        | 1        | 0.37%   |
| Waihi            | 1        | 0.37%   |
| Stratford        | 1        | 0.37%   |
| Rotorua          | 1        | 0.37%   |
| Queenstown       | 1        | 0.37%   |
| Mount Eden       | 1        | 0.37%   |
| Milton           | 1        | 0.37%   |
| Havelock North   | 1        | 0.37%   |
| Hastings         | 1        | 0.37%   |
| Grafton          | 1        | 0.37%   |
| Darfield         | 1        | 0.37%   |
| Carterton        | 1        | 0.37%   |
| Ashburton        | 1        | 0.37%   |
| Albany           | 1        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 120      | 236    | 25.42%  |
| WDC                       | 102      | 183    | 21.61%  |
| Samsung Electronics       | 69       | 148    | 14.62%  |
| Crucial                   | 28       | 45     | 5.93%   |
| Kingston                  | 24       | 33     | 5.08%   |
| Intel                     | 18       | 25     | 3.81%   |
| Hitachi                   | 16       | 24     | 3.39%   |
| Toshiba                   | 15       | 20     | 3.18%   |
| SanDisk                   | 15       | 20     | 3.18%   |
| A-DATA Technology         | 9        | 12     | 1.91%   |
| Micron Technology         | 5        | 6      | 1.06%   |
| HGST                      | 5        | 6      | 1.06%   |
| Unknown                   | 4        | 5      | 0.85%   |
| Lexar                     | 3        | 3      | 0.64%   |
| Gigabyte Technology       | 3        | 3      | 0.64%   |
| External                  | 3        | 3      | 0.64%   |
| Apacer                    | 3        | 3      | 0.64%   |
| XPG                       | 2        | 2      | 0.42%   |
| Transcend                 | 2        | 2      | 0.42%   |
| TO Exter                  | 2        | 2      | 0.42%   |
| Team                      | 2        | 2      | 0.42%   |
| SK hynix                  | 2        | 2      | 0.42%   |
| Silicon Motion            | 2        | 3      | 0.42%   |
| Corsair                   | 2        | 3      | 0.42%   |
| China                     | 2        | 3      | 0.42%   |
| USB                       | 1        | 2      | 0.21%   |
| Realtek Semiconductor     | 1        | 1      | 0.21%   |
| PNY                       | 1        | 1      | 0.21%   |
| Phison                    | 1        | 1      | 0.21%   |
| OCZ                       | 1        | 1      | 0.21%   |
| Micron/Crucial Technology | 1        | 1      | 0.21%   |
| LITEON                    | 1        | 1      | 0.21%   |
| KingSpec                  | 1        | 1      | 0.21%   |
| JMicron Technology        | 1        | 1      | 0.21%   |
| Innodisk                  | 1        | 1      | 0.21%   |
| Hewlett-Packard           | 1        | 2      | 0.21%   |
| GAMER                     | 1        | 1      | 0.21%   |
| ASMT                      | 1        | 1      | 0.21%   |
| Apple                     | 1        | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB                      | 11       | 1.91%   |
| Seagate Expansion Desk 6TB                          | 10       | 1.74%   |
| Seagate ST500DM002-1BD142 500GB                     | 8        | 1.39%   |
| Samsung SSD 860 EVO 500GB                           | 8        | 1.39%   |
| Crucial CT240BX500SSD1 240GB                        | 8        | 1.39%   |
| Seagate ST31000528AS 1TB                            | 7        | 1.22%   |
| Seagate ST2000DM006-2DM164 2TB                      | 7        | 1.22%   |
| Seagate ST1000DM003-1CH162 1TB                      | 7        | 1.22%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 6        | 1.04%   |
| Samsung SSD 850 EVO 250GB                           | 6        | 1.04%   |
| Samsung NVMe SSD Drive 500GB                        | 6        | 1.04%   |
| Toshiba THNS128GG4BBAA 128GB SSD                    | 5        | 0.87%   |
| Seagate ST1000DM010-2EP102 1TB                      | 5        | 0.87%   |
| Seagate Expansion 240GB                             | 5        | 0.87%   |
| Samsung SSD 870 EVO 1TB                             | 5        | 0.87%   |
| Samsung SSD 850 EVO 500GB                           | 5        | 0.87%   |
| Kingston SA400S37120G 120GB SSD                     | 5        | 0.87%   |
| WDC WD20EARX-00PASB0 2TB                            | 4        | 0.7%    |
| WDC WD10EZEX-00WN4A0 1TB                            | 4        | 0.7%    |
| Seagate ST3500418AS 500GB                           | 4        | 0.7%    |
| Seagate ST2000DM001-1CH164 2TB                      | 4        | 0.7%    |
| Samsung NVMe SSD Drive 1TB                          | 4        | 0.7%    |
| Kingston SA400S37240G 240GB SSD                     | 4        | 0.7%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 3        | 0.52%   |
| WDC WD10EALX-009BA0 1TB                             | 3        | 0.52%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 3        | 0.52%   |
| Seagate ST9500325AS 500GB                           | 3        | 0.52%   |
| Seagate ST3500413AS 500GB                           | 3        | 0.52%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3        | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB                      | 3        | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB                      | 3        | 0.52%   |
| SanDisk SDSSDA240G 240GB                            | 3        | 0.52%   |
| Samsung SSD 870 QVO 1TB                             | 3        | 0.52%   |
| Samsung SSD 860 EVO 250GB                           | 3        | 0.52%   |
| Samsung SSD 840 EVO 120GB                           | 3        | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3        | 0.52%   |
| Kingston SV300S37A240G 240GB SSD                    | 3        | 0.52%   |
| Kingston SV300S37A120G 120GB SSD                    | 3        | 0.52%   |
| Kingston SUV400S37240G 240GB SSD                    | 3        | 0.52%   |
| Intel SSDSA2CW080G3 80GB                            | 3        | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 117      | 226    | 46.99%  |
| WDC                 | 94       | 166    | 37.75%  |
| Hitachi             | 16       | 24     | 6.43%   |
| Toshiba             | 8        | 13     | 3.21%   |
| HGST                | 5        | 6      | 2.01%   |
| Samsung Electronics | 3        | 5      | 1.2%    |
| Unknown             | 2        | 2      | 0.8%    |
| USB                 | 1        | 2      | 0.4%    |
| External            | 1        | 1      | 0.4%    |
| ASMT                | 1        | 1      | 0.4%    |
| Apple               | 1        | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 47       | 78     | 27.65%  |
| Crucial             | 26       | 40     | 15.29%  |
| Kingston            | 19       | 28     | 11.18%  |
| Intel               | 15       | 19     | 8.82%   |
| SanDisk             | 12       | 17     | 7.06%   |
| WDC                 | 8        | 11     | 4.71%   |
| A-DATA Technology   | 7        | 9      | 4.12%   |
| Toshiba             | 5        | 5      | 2.94%   |
| Seagate             | 3        | 5      | 1.76%   |
| Micron Technology   | 3        | 4      | 1.76%   |
| Lexar               | 3        | 3      | 1.76%   |
| Apacer              | 3        | 3      | 1.76%   |
| TO Exter            | 2        | 2      | 1.18%   |
| Team                | 2        | 2      | 1.18%   |
| Gigabyte Technology | 2        | 2      | 1.18%   |
| Corsair             | 2        | 3      | 1.18%   |
| China               | 2        | 2      | 1.18%   |
| Transcend           | 1        | 1      | 0.59%   |
| SK hynix            | 1        | 1      | 0.59%   |
| OCZ                 | 1        | 1      | 0.59%   |
| LITEON              | 1        | 1      | 0.59%   |
| KingSpec            | 1        | 1      | 0.59%   |
| JMicron Technology  | 1        | 1      | 0.59%   |
| Innodisk            | 1        | 1      | 0.59%   |
| Hewlett-Packard     | 1        | 2      | 0.59%   |
| GAMER               | 1        | 1      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 190      | 447    | 47.62%  |
| SSD     | 144      | 243    | 36.09%  |
| NVMe    | 59       | 113    | 14.79%  |
| Unknown | 4        | 5      | 1%      |
| MMC     | 2        | 2      | 0.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 239      | 655    | 73.31%  |
| NVMe | 58       | 111    | 17.79%  |
| SAS  | 27       | 42     | 8.28%   |
| MMC  | 2        | 2      | 0.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 188      | 344    | 47.36%  |
| 0.51-1.0   | 108      | 184    | 27.2%   |
| 1.01-2.0   | 52       | 82     | 13.1%   |
| 3.01-4.0   | 18       | 36     | 4.53%   |
| 4.01-10.0  | 17       | 23     | 4.28%   |
| 2.01-3.0   | 12       | 14     | 3.02%   |
| 10.01-20.0 | 2        | 7      | 0.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 62       | 21.99%  |
| 501-1000       | 45       | 15.96%  |
| 251-500        | 40       | 14.18%  |
| More than 3000 | 36       | 12.77%  |
| 1001-2000      | 36       | 12.77%  |
| 2001-3000      | 27       | 9.57%   |
| 1-20           | 18       | 6.38%   |
| 51-100         | 10       | 3.55%   |
| Unknown        | 7        | 2.48%   |
| 21-50          | 1        | 0.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 85       | 28.43%  |
| 21-50          | 49       | 16.39%  |
| 251-500        | 28       | 9.36%   |
| 101-250        | 27       | 9.03%   |
| 501-1000       | 27       | 9.03%   |
| 1001-2000      | 24       | 8.03%   |
| 51-100         | 24       | 8.03%   |
| More than 3000 | 14       | 4.68%   |
| 2001-3000      | 14       | 4.68%   |
| Unknown        | 7        | 2.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB           | 2        | 3      | 5.71%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 2        | 2      | 5.71%   |
| Seagate ST3500418AS 500GB             | 2        | 2      | 5.71%   |
| Samsung Electronics SSD 980 1TB       | 2        | 2      | 5.71%   |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1        | 1      | 2.86%   |
| WDC WD15EARS-00S0XB0 1TB              | 1        | 1      | 2.86%   |
| WDC WD10EFRX-68FYTN0 1TB              | 1        | 3      | 2.86%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1        | 1      | 2.86%   |
| SK hynix HFS256G32MND-2900A 256GB SSD | 1        | 1      | 2.86%   |
| Seagate ST8000VN0022-2EL112 8TB       | 1        | 3      | 2.86%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 2.86%   |
| Seagate ST3250310AS 250GB             | 1        | 1      | 2.86%   |
| Seagate ST3200822A 200GB              | 1        | 1      | 2.86%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 2.86%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 2.86%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 2.86%   |
| Seagate ST2000DX002-2DV164 2TB        | 1        | 1      | 2.86%   |
| Seagate ST2000DX001-1CM164 2TB        | 1        | 1      | 2.86%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 2.86%   |
| Seagate ST2000DM001-1CH164 2TB        | 1        | 1      | 2.86%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1      | 2.86%   |
| SanDisk SSD PLUS 240 GB               | 1        | 1      | 2.86%   |
| Samsung Electronics SSD 980 PRO 2TB   | 1        | 1      | 2.86%   |
| Samsung Electronics SSD 980 PRO 250GB | 1        | 1      | 2.86%   |
| Intel SSDSC2CT240A4 240GB             | 1        | 1      | 2.86%   |
| Innodisk Corp. - mSATA 3ME4 128GB     | 1        | 1      | 2.86%   |
| Hitachi HTS541010A9E680 1TB           | 1        | 1      | 2.86%   |
| HGST HTS545050A7E380 500GB            | 1        | 1      | 2.86%   |
| Crucial CT480M500SSD1 480GB           | 1        | 1      | 2.86%   |
| Crucial CT480BX500SSD1 480GB          | 1        | 1      | 2.86%   |
| Crucial CT1000BX500SSD1 1TB           | 1        | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 16     | 34.38%  |
| WDC                 | 8        | 11     | 25%     |
| Samsung Electronics | 4        | 4      | 12.5%   |
| Crucial             | 3        | 3      | 9.38%   |
| SK hynix            | 1        | 1      | 3.13%   |
| SanDisk             | 1        | 1      | 3.13%   |
| Intel               | 1        | 1      | 3.13%   |
| Innodisk            | 1        | 1      | 3.13%   |
| Hitachi             | 1        | 1      | 3.13%   |
| HGST                | 1        | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 16     | 52.38%  |
| WDC     | 8        | 11     | 38.1%   |
| Hitachi | 1        | 1      | 4.76%   |
| HGST    | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 29     | 64.52%  |
| SSD  | 7        | 7      | 22.58%  |
| NVMe | 4        | 4      | 12.9%   |

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
| Detected | 172      | 504    | 58.5%   |
| Works    | 92       | 266    | 31.29%  |
| Malfunc  | 30       | 40     | 10.2%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 156      | 43.7%   |
| AMD                          | 92       | 25.77%  |
| Samsung Electronics          | 33       | 9.24%   |
| JMicron Technology           | 12       | 3.36%   |
| Marvell Technology Group     | 11       | 3.08%   |
| ASMedia Technology           | 10       | 2.8%    |
| Nvidia                       | 6        | 1.68%   |
| Kingston Technology Company  | 5        | 1.4%    |
| Silicon Motion               | 4        | 1.12%   |
| SanDisk                      | 4        | 1.12%   |
| Seagate Technology           | 3        | 0.84%   |
| Micron/Crucial Technology    | 3        | 0.84%   |
| LSI Logic / Symbios Logic    | 3        | 0.84%   |
| Toshiba America Info Systems | 2        | 0.56%   |
| Realtek Semiconductor        | 2        | 0.56%   |
| Phison Electronics           | 2        | 0.56%   |
| Micron Technology            | 2        | 0.56%   |
| Hewlett-Packard              | 2        | 0.56%   |
| VIA Technologies             | 1        | 0.28%   |
| SK hynix                     | 1        | 0.28%   |
| Silicon Image                | 1        | 0.28%   |
| Broadcom / LSI               | 1        | 0.28%   |
| ADATA Technology             | 1        | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 51       | 10.81%  |
| AMD 400 Series Chipset SATA Controller                                                  | 21       | 4.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 20       | 4.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 17       | 3.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 17       | 3.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 3.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 16       | 3.39%   |
| Intel SATA Controller [RAID mode]                                                       | 13       | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 2.75%   |
| AMD 500 Series Chipset SATA Controller                                                  | 11       | 2.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 10       | 2.12%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 2.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 1.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 1.69%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 1.48%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7        | 1.48%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 7        | 1.48%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 7        | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 1.48%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 1.48%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 1.27%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6        | 1.27%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 6        | 1.27%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 6        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 1.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 1.06%   |
| Samsung NVMe SSD Controller 980                                                         | 4        | 0.85%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.85%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.64%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.64%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 3        | 0.64%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 3        | 0.64%   |
| JMicron JMB368 IDE controller                                                           | 3        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 200      | 55.56%  |
| IDE  | 75       | 20.83%  |
| NVMe | 60       | 16.67%  |
| RAID | 23       | 6.39%   |
| SAS  | 1        | 0.28%   |
| SCSI | 1        | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 157      | 61.57%  |
| AMD    | 98       | 38.43%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz       | 10       | 3.92%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 8        | 3.14%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 7        | 2.75%   |
| AMD Ryzen 5 3600 6-Core Processor      | 6        | 2.35%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 5        | 1.96%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 4        | 1.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 4        | 1.57%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 4        | 1.57%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz  | 4        | 1.57%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 4        | 1.57%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 4        | 1.57%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 4        | 1.57%   |
| AMD Ryzen 5 1600 Six-Core Processor    | 4        | 1.57%   |
| AMD FX-6300 Six-Core Processor         | 4        | 1.57%   |
| Intel Core i7-10700 CPU @ 2.90GHz      | 3        | 1.18%   |
| Intel Core i7 CPU 950 @ 3.07GHz        | 3        | 1.18%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 3        | 1.18%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 3        | 1.18%   |
| AMD FX-8320 Eight-Core Processor       | 3        | 1.18%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 0.78%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 2        | 0.78%   |
| Intel Core i7-4770K CPU @ 3.50GHz      | 2        | 0.78%   |
| Intel Core i7 CPU 860 @ 2.80GHz        | 2        | 0.78%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 2        | 0.78%   |
| Intel Core i5-8600K CPU @ 3.60GHz      | 2        | 0.78%   |
| Intel Core i5-4670 CPU @ 3.40GHz       | 2        | 0.78%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 2        | 0.78%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 2        | 0.78%   |
| Intel Core i5-3470S CPU @ 2.90GHz      | 2        | 0.78%   |
| Intel Core i5-2500K CPU @ 3.30GHz      | 2        | 0.78%   |
| Intel Core i5 CPU 750 @ 2.67GHz        | 2        | 0.78%   |
| Intel Core i3-4130 CPU @ 3.40GHz       | 2        | 0.78%   |
| Intel Core i3-3220 CPU @ 3.30GHz       | 2        | 0.78%   |
| Intel Core i3 CPU 540 @ 3.07GHz        | 2        | 0.78%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz  | 2        | 0.78%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz  | 2        | 0.78%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 2        | 0.78%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz   | 2        | 0.78%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 2        | 0.78%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 2        | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 53       | 20.78%  |
| Intel Core i7           | 43       | 16.86%  |
| AMD Ryzen 5             | 21       | 8.24%   |
| AMD Ryzen 7             | 20       | 7.84%   |
| Intel Core i3           | 16       | 6.27%   |
| AMD FX                  | 16       | 6.27%   |
| Intel Xeon              | 15       | 5.88%   |
| Intel Core 2 Quad       | 10       | 3.92%   |
| AMD Ryzen 9             | 9        | 3.53%   |
| Intel Core 2 Duo        | 6        | 2.35%   |
| Intel Pentium           | 5        | 1.96%   |
| AMD Ryzen 3             | 5        | 1.96%   |
| AMD Athlon 64 X2        | 5        | 1.96%   |
| AMD Ryzen Threadripper  | 4        | 1.57%   |
| AMD Athlon II X2        | 4        | 1.57%   |
| Intel Atom              | 3        | 1.18%   |
| Intel Pentium Dual-Core | 2        | 0.78%   |
| AMD A8                  | 2        | 0.78%   |
| AMD A6                  | 2        | 0.78%   |
| AMD A4                  | 2        | 0.78%   |
| Intel Pentium Dual      | 1        | 0.39%   |
| Intel Pentium 4         | 1        | 0.39%   |
| Intel Core i9           | 1        | 0.39%   |
| Intel Celeron           | 1        | 0.39%   |
| AMD Ryzen 7 PRO         | 1        | 0.39%   |
| AMD Phenom II X6        | 1        | 0.39%   |
| AMD Phenom II X4        | 1        | 0.39%   |
| AMD Opteron             | 1        | 0.39%   |
| AMD GX                  | 1        | 0.39%   |
| AMD Athlon II X4        | 1        | 0.39%   |
| AMD A12                 | 1        | 0.39%   |
| AMD A10                 | 1        | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 119      | 46.67%  |
| 2      | 49       | 19.22%  |
| 6      | 35       | 13.73%  |
| 8      | 27       | 10.59%  |
| 12     | 10       | 3.92%   |
| 3      | 5        | 1.96%   |
| 16     | 4        | 1.57%   |
| 1      | 3        | 1.18%   |
| 24     | 1        | 0.39%   |
| 14     | 1        | 0.39%   |
| 10     | 1        | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 253      | 99.22%  |
| 2      | 2        | 0.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 155      | 60.78%  |
| 1      | 100      | 39.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 251      | 97.67%  |
| Unknown        | 6        | 2.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 67       | 25%     |
| 0x306a9    | 22       | 8.21%   |
| 0x306c3    | 20       | 7.46%   |
| 0x206a7    | 16       | 5.97%   |
| 0x08701021 | 15       | 5.6%    |
| 0x1067a    | 10       | 3.73%   |
| 0x06000852 | 9        | 3.36%   |
| 0x106e5    | 6        | 2.24%   |
| 0xa0655    | 5        | 1.87%   |
| 0x906e9    | 5        | 1.87%   |
| 0x506e3    | 5        | 1.87%   |
| 0x0a50000c | 5        | 1.87%   |
| 0x0800820d | 5        | 1.87%   |
| 0x08001137 | 5        | 1.87%   |
| 0x106a5    | 4        | 1.49%   |
| 0x08701013 | 4        | 1.49%   |
| 0x906ea    | 3        | 1.12%   |
| 0x6fb      | 3        | 1.12%   |
| 0x20655    | 3        | 1.12%   |
| 0x0a201009 | 3        | 1.12%   |
| 0x06001119 | 3        | 1.12%   |
| 0x010000c8 | 3        | 1.12%   |
| 0x906ed    | 2        | 0.75%   |
| 0x50654    | 2        | 0.75%   |
| 0x406c3    | 2        | 0.75%   |
| 0x306f2    | 2        | 0.75%   |
| 0x206d7    | 2        | 0.75%   |
| 0x10677    | 2        | 0.75%   |
| 0x0a201016 | 2        | 0.75%   |
| 0x08108109 | 2        | 0.75%   |
| 0x08001138 | 2        | 0.75%   |
| 0x08001129 | 2        | 0.75%   |
| 0x0700010f | 2        | 0.75%   |
| 0x0600063e | 2        | 0.75%   |
| 0x906eb    | 1        | 0.37%   |
| 0x6fd      | 1        | 0.37%   |
| 0x506c9    | 1        | 0.37%   |
| 0x406e3    | 1        | 0.37%   |
| 0x406c4    | 1        | 0.37%   |
| 0x40651    | 1        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 30       | 11.76%  |
| Haswell     | 28       | 10.98%  |
| Zen 2       | 24       | 9.41%   |
| SandyBridge | 20       | 7.84%   |
| Piledriver  | 19       | 7.45%   |
| KabyLake    | 17       | 6.67%   |
| Penryn      | 16       | 6.27%   |
| Zen 3       | 12       | 4.71%   |
| Zen         | 12       | 4.71%   |
| Nehalem     | 12       | 4.71%   |
| Zen+        | 11       | 4.31%   |
| Skylake     | 10       | 3.92%   |
| CometLake   | 8        | 3.14%   |
| K10         | 7        | 2.75%   |
| Westmere    | 5        | 1.96%   |
| K8 Hammer   | 5        | 1.96%   |
| Core        | 5        | 1.96%   |
| Silvermont  | 3        | 1.18%   |
| Bulldozer   | 3        | 1.18%   |
| Jaguar      | 2        | 0.78%   |
| NetBurst    | 1        | 0.39%   |
| K10 Llano   | 1        | 0.39%   |
| Goldmont    | 1        | 0.39%   |
| Excavator   | 1        | 0.39%   |
| Bonnell     | 1        | 0.39%   |
| Unknown     | 1        | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 97       | 35.14%  |
| AMD                        | 95       | 34.42%  |
| Intel                      | 79       | 28.62%  |
| Matrox Electronics Systems | 4        | 1.45%   |
| ASPEED Technology          | 1        | 0.36%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 17       | 5.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 14       | 4.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11       | 3.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11       | 3.82%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 7        | 2.43%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6        | 2.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6        | 2.08%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5        | 1.74%   |
| Intel HD Graphics 630                                                                    | 5        | 1.74%   |
| Intel HD Graphics 530                                                                    | 5        | 1.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 1.74%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 5        | 1.74%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 1.39%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 1.39%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 1.39%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4        | 1.39%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 4        | 1.39%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 4        | 1.39%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4        | 1.39%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4        | 1.39%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4        | 1.39%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 3        | 1.04%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 3        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.04%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 1.04%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 3        | 1.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 1.04%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3        | 1.04%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2        | 0.69%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 2        | 0.69%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2        | 0.69%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2        | 0.69%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                        | 2        | 0.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 0.69%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 0.69%   |
| Nvidia GK107GL [Quadro K2000]                                                            | 2        | 0.69%   |
| Nvidia GK107 [GeForce GT 740]                                                            | 2        | 0.69%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2        | 0.69%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 2        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 92       | 35.11%  |
| 1 x AMD        | 83       | 31.68%  |
| 1 x Intel      | 66       | 25.19%  |
| 2 x AMD        | 6        | 2.29%   |
| 1 x Matrox     | 4        | 1.53%   |
| Intel + AMD    | 4        | 1.53%   |
| AMD + Nvidia   | 3        | 1.15%   |
| Intel + Nvidia | 2        | 0.76%   |
| 2 x Nvidia     | 1        | 0.38%   |
| AMD + ASPEED   | 1        | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 191      | 74.03%  |
| Proprietary | 62       | 24.03%  |
| Unknown     | 5        | 1.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 106      | 39.7%   |
| 1.01-2.0   | 43       | 16.1%   |
| 0.01-0.5   | 27       | 10.11%  |
| 7.01-8.0   | 25       | 9.36%   |
| 0.51-1.0   | 24       | 8.99%   |
| 3.01-4.0   | 14       | 5.24%   |
| 5.01-6.0   | 13       | 4.87%   |
| 8.01-16.0  | 11       | 4.12%   |
| 2.01-3.0   | 3        | 1.12%   |
| 16.01-24.0 | 1        | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 42       | 14.33%  |
| AOC                     | 41       | 13.99%  |
| Dell                    | 38       | 12.97%  |
| Goldstar                | 28       | 9.56%   |
| Philips                 | 25       | 8.53%   |
| ViewSonic               | 22       | 7.51%   |
| Hewlett-Packard         | 14       | 4.78%   |
| Sony                    | 9        | 3.07%   |
| Panasonic               | 9        | 3.07%   |
| Acer                    | 8        | 2.73%   |
| Lenovo                  | 7        | 2.39%   |
| BenQ                    | 7        | 2.39%   |
| Ancor Communications    | 7        | 2.39%   |
| MiTAC                   | 6        | 2.05%   |
| Denver                  | 6        | 2.05%   |
| LG Electronics          | 4        | 1.37%   |
| Unknown                 | 2        | 0.68%   |
| Konka                   | 2        | 0.68%   |
| Chi Mei Optoelectronics | 2        | 0.68%   |
| ASUSTek Computer        | 2        | 0.68%   |
| Unknown (AAA)           | 1        | 0.34%   |
| SANYO                   | 1        | 0.34%   |
| Plain Tree Systems      | 1        | 0.34%   |
| NEC Computers           | 1        | 0.34%   |
| Marantz                 | 1        | 0.34%   |
| KTC                     | 1        | 0.34%   |
| Iiyama                  | 1        | 0.34%   |
| GVV                     | 1        | 0.34%   |
| eMachines               | 1        | 0.34%   |
| Elo Touch               | 1        | 0.34%   |
| CVT                     | 1        | 0.34%   |
| CEI                     | 1        | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                   | 7        | 2.13%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                | 4        | 1.22%   |
| ViewSonic VA2248 SERIES VSC0E28 1920x1080 477x268mm 21.5-inch         | 3        | 0.91%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3        | 0.91%   |
| MiTAC Smart TV SZM0030 1920x1080 708x398mm 32.0-inch                  | 3        | 0.91%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3        | 0.91%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                     | 3        | 0.91%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 3        | 0.91%   |
| AOC 2367 AOC2367 1920x1080 509x286mm 23.0-inch                        | 3        | 0.91%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 2        | 0.61%   |
| ViewSonic VA2231 Series VSCBB25 1920x1080 477x268mm 21.5-inch         | 2        | 0.61%   |
| ViewSonic LCD Monitor VSCB51D 1280x1024 340x270mm 17.1-inch           | 2        | 0.61%   |
| Sony TV SNYEE01 1920x1080                                             | 2        | 0.61%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 2        | 0.61%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.61%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch  | 2        | 0.61%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch     | 2        | 0.61%   |
| Konka TV_MONITOR KOA0030 2288x1430 708x398mm 32.0-inch                | 2        | 0.61%   |
| Hewlett-Packard P221 HWP3057 1920x1080 476x268mm 21.5-inch            | 2        | 0.61%   |
| Goldstar W1941 GSM4B91 1360x768 406x229mm 18.4-inch                   | 2        | 0.61%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.61%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 0.61%   |
| Goldstar E2351 GSM5872 1920x1080 510x290mm 23.1-inch                  | 2        | 0.61%   |
| Denver PGM340 LHC3400 3440x1440 798x334mm 34.1-inch                   | 2        | 0.61%   |
| Denver FQ270 LHC2700 2560x1440 597x336mm 27.0-inch                    | 2        | 0.61%   |
| Dell G2410 DEL404B 1920x1080 531x298mm 24.0-inch                      | 2        | 0.61%   |
| Dell E228WFP DELD014 1680x1050 470x300mm 22.0-inch                    | 2        | 0.61%   |
| Dell 1907FP DEL4015 1280x1024 376x301mm 19.0-inch                     | 2        | 0.61%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 2        | 0.61%   |
| AOC U2868 AOC2868 3840x2160 621x341mm 27.9-inch                       | 2        | 0.61%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 2        | 0.61%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 2        | 0.61%   |
| AOC 2778X AOC2778 2560x1440 597x336mm 27.0-inch                       | 2        | 0.61%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 2        | 0.61%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                     | 2        | 0.61%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 2        | 0.61%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch            | 1        | 0.3%    |
| ViewSonic VX2770 SERIES VSC3A2C 1920x1080 597x336mm 27.0-inch         | 1        | 0.3%    |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch         | 1        | 0.3%    |
| ViewSonic VX2439wm VSC3D24 1920x1080 520x290mm 23.4-inch              | 1        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 127      | 43.49%  |
| 3840x2160 (4K)     | 40       | 13.7%   |
| 1680x1050 (WSXGA+) | 23       | 7.88%   |
| 1280x1024 (SXGA)   | 18       | 6.16%   |
| 2560x1440 (QHD)    | 15       | 5.14%   |
| 1440x900 (WXGA+)   | 12       | 4.11%   |
| Unknown            | 10       | 3.42%   |
| 3440x1440          | 8        | 2.74%   |
| 1600x900 (HD+)     | 6        | 2.05%   |
| 3840x1080          | 5        | 1.71%   |
| 1360x768           | 5        | 1.71%   |
| 1366x768 (WXGA)    | 4        | 1.37%   |
| 1920x1200 (WUXGA)  | 3        | 1.03%   |
| 2560x1080          | 2        | 0.68%   |
| 1600x1200          | 2        | 0.68%   |
| 7680x1080          | 1        | 0.34%   |
| 6720x1080          | 1        | 0.34%   |
| 3840x1600          | 1        | 0.34%   |
| 3840x1200          | 1        | 0.34%   |
| 3360x1080          | 1        | 0.34%   |
| 2960x1050          | 1        | 0.34%   |
| 2560x1600          | 1        | 0.34%   |
| 2560x1024          | 1        | 0.34%   |
| 2288x1287          | 1        | 0.34%   |
| 2048x1152          | 1        | 0.34%   |
| 1280x800 (WXGA)    | 1        | 0.34%   |
| 1024x768 (XGA)     | 1        | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 43       | 14.58%  |
| 21      | 40       | 13.56%  |
| 27      | 33       | 11.19%  |
| 24      | 32       | 10.85%  |
| Unknown | 28       | 9.49%   |
| 22      | 16       | 5.42%   |
| 19      | 15       | 5.08%   |
| 31      | 14       | 4.75%   |
| 17      | 11       | 3.73%   |
| 84      | 10       | 3.39%   |
| 20      | 10       | 3.39%   |
| 34      | 7        | 2.37%   |
| 72      | 6        | 2.03%   |
| 18      | 6        | 2.03%   |
| 32      | 5        | 1.69%   |
| 52      | 3        | 1.02%   |
| 46      | 2        | 0.68%   |
| 35      | 2        | 0.68%   |
| 15      | 2        | 0.68%   |
| 142     | 1        | 0.34%   |
| 65      | 1        | 0.34%   |
| 54      | 1        | 0.34%   |
| 49      | 1        | 0.34%   |
| 40      | 1        | 0.34%   |
| 37      | 1        | 0.34%   |
| 36      | 1        | 0.34%   |
| 30      | 1        | 0.34%   |
| 29      | 1        | 0.34%   |
| 26      | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 93       | 32.98%  |
| 401-500        | 78       | 27.66%  |
| Unknown        | 28       | 9.93%   |
| 601-700        | 23       | 8.16%   |
| 1501-2000      | 14       | 4.96%   |
| 701-800        | 13       | 4.61%   |
| 301-350        | 13       | 4.61%   |
| 1001-1500      | 8        | 2.84%   |
| 351-400        | 7        | 2.48%   |
| 801-900        | 4        | 1.42%   |
| More than 2000 | 1        | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 166      | 61.94%  |
| 16/10   | 41       | 15.3%   |
| Unknown | 25       | 9.33%   |
| 5/4     | 18       | 6.72%   |
| 21/9    | 11       | 4.1%    |
| 4/3     | 3        | 1.12%   |
| 6/5     | 1        | 0.37%   |
| 32/9    | 1        | 0.37%   |
| 3/2     | 1        | 0.37%   |
| 1.00    | 1        | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 106      | 37.46%  |
| 151-200        | 36       | 12.72%  |
| 301-350        | 34       | 12.01%  |
| 351-500        | 29       | 10.25%  |
| Unknown        | 28       | 9.89%   |
| More than 1000 | 20       | 7.07%   |
| 141-150        | 14       | 4.95%   |
| 251-300        | 8        | 2.83%   |
| 501-1000       | 6        | 2.12%   |
| 101-110        | 2        | 0.71%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 152      | 54.68%  |
| 101-120 | 55       | 19.78%  |
| Unknown | 28       | 10.07%  |
| 1-50    | 20       | 7.19%   |
| 121-160 | 18       | 6.47%   |
| 161-240 | 5        | 1.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 189      | 71.32%  |
| 2     | 60       | 22.64%  |
| 0     | 8        | 3.02%   |
| 3     | 6        | 2.26%   |
| 4     | 2        | 0.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 140      | 36.94%  |
| Intel                                 | 117      | 30.87%  |
| Qualcomm Atheros                      | 27       | 7.12%   |
| Ralink Technology                     | 13       | 3.43%   |
| Broadcom                              | 12       | 3.17%   |
| TP-Link                               | 10       | 2.64%   |
| Marvell Technology Group              | 8        | 2.11%   |
| Ralink                                | 6        | 1.58%   |
| Nvidia                                | 6        | 1.58%   |
| Samsung Electronics                   | 4        | 1.06%   |
| Qualcomm Atheros Communications       | 4        | 1.06%   |
| NetGear                               | 3        | 0.79%   |
| MediaTek                              | 3        | 0.79%   |
| Edimax Technology                     | 3        | 0.79%   |
| Aquantia                              | 3        | 0.79%   |
| Microsoft                             | 2        | 0.53%   |
| Microchip Technology                  | 2        | 0.53%   |
| IBM                                   | 2        | 0.53%   |
| Broadcom Limited                      | 2        | 0.53%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.26%   |
| Wilocity                              | 1        | 0.26%   |
| Mellanox Technologies                 | 1        | 0.26%   |
| MCS                                   | 1        | 0.26%   |
| Huawei Technologies                   | 1        | 0.26%   |
| DisplayLink                           | 1        | 0.26%   |
| D-Link                                | 1        | 0.26%   |
| Bose                                  | 1        | 0.26%   |
| Belkin Components                     | 1        | 0.26%   |
| ASUSTek Computer                      | 1        | 0.26%   |
| ASIX Electronics                      | 1        | 0.26%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 117      | 28.13%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20       | 4.81%   |
| Intel I211 Gigabit Network Connection                             | 17       | 4.09%   |
| Intel Wi-Fi 6 AX200                                               | 15       | 3.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 2.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8        | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 1.92%   |
| Intel Ethernet Connection (2) I219-V                              | 8        | 1.92%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8        | 1.92%   |
| Intel Wireless-AC 9260                                            | 7        | 1.68%   |
| Intel Ethernet Controller I225-V                                  | 6        | 1.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5        | 1.2%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 5        | 1.2%    |
| Ralink MT7601U Wireless Adapter                                   | 5        | 1.2%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 5        | 1.2%    |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.2%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                             | 4        | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 0.96%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3        | 0.72%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3        | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3        | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.72%   |
| Nvidia MCP61 Ethernet                                             | 3        | 0.72%   |
| Intel Wireless 8265 / 8275                                        | 3        | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.72%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.72%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3        | 0.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 0.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.48%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.48%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2        | 0.48%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 2        | 0.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.48%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.48%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 34       | 27.2%   |
| Realtek Semiconductor                 | 27       | 21.6%   |
| Ralink Technology                     | 13       | 10.4%   |
| Qualcomm Atheros                      | 11       | 8.8%    |
| TP-Link                               | 10       | 8%      |
| Ralink                                | 6        | 4.8%    |
| Broadcom                              | 5        | 4%      |
| Qualcomm Atheros Communications       | 4        | 3.2%    |
| NetGear                               | 3        | 2.4%    |
| Edimax Technology                     | 3        | 2.4%    |
| Microsoft                             | 2        | 1.6%    |
| MediaTek                              | 2        | 1.6%    |
| Wilocity                              | 1        | 0.8%    |
| D-Link                                | 1        | 0.8%    |
| Belkin Components                     | 1        | 0.8%    |
| ASUSTek Computer                      | 1        | 0.8%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.8%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 15       | 11.72%  |
| Intel Wireless-AC 9260                                              | 7        | 5.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 5        | 3.91%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 5        | 3.91%   |
| Ralink MT7601U Wireless Adapter                                     | 5        | 3.91%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 4        | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 4        | 3.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 3        | 2.34%   |
| Qualcomm Atheros AR9271 802.11n                                     | 3        | 2.34%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 3        | 2.34%   |
| Intel Wireless 8265 / 8275                                          | 3        | 2.34%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 3        | 2.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 2        | 1.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 2        | 1.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 2        | 1.56%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 2        | 1.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2        | 1.56%   |
| Ralink RT5370 Wireless Adapter                                      | 2        | 1.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 2        | 1.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                           | 2        | 1.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 2        | 1.56%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]      | 2        | 1.56%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                  | 1        | 0.78%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                 | 1        | 0.78%   |
| TP-Link Archer T4U ver.3                                            | 1        | 0.78%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 0.78%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 1        | 0.78%   |
| TP-Link 802.11ac WLAN Adapter                                       | 1        | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.78%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                 | 1        | 0.78%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                     | 1        | 0.78%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 1        | 0.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1        | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 0.78%   |
| Ralink RT5572 Wireless Adapter                                      | 1        | 0.78%   |
| Ralink RT2770 Wireless Adapter                                      | 1        | 0.78%   |
| Ralink RT2501/RT2573 Wireless Adapter                               | 1        | 0.78%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                   | 1        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 127      | 45.2%   |
| Intel                      | 98       | 34.88%  |
| Qualcomm Atheros           | 18       | 6.41%   |
| Marvell Technology Group   | 8        | 2.85%   |
| Broadcom                   | 7        | 2.49%   |
| Nvidia                     | 6        | 2.14%   |
| Samsung Electronics        | 4        | 1.42%   |
| Aquantia                   | 3        | 1.07%   |
| IBM                        | 2        | 0.71%   |
| Broadcom Limited           | 2        | 0.71%   |
| ZTE WCDMA Technologies MSM | 1        | 0.36%   |
| Mellanox Technologies      | 1        | 0.36%   |
| MediaTek                   | 1        | 0.36%   |
| Huawei Technologies        | 1        | 0.36%   |
| DisplayLink                | 1        | 0.36%   |
| ASIX Electronics           | 1        | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 117      | 41.34%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20       | 7.07%   |
| Intel I211 Gigabit Network Connection                             | 17       | 6.01%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 3.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8        | 2.83%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 2.83%   |
| Intel Ethernet Connection (2) I219-V                              | 8        | 2.83%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8        | 2.83%   |
| Intel Ethernet Controller I225-V                                  | 6        | 2.12%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 5        | 1.77%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 1.41%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 1.06%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.06%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.06%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 1.06%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2        | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.71%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 0.71%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2        | 0.71%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.71%   |
| Intel Ethernet Connection (5) I219-LM                             | 2        | 0.71%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.71%   |
| IBM RNDIS/CDC ETHER                                               | 2        | 0.71%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                       | 2        | 0.71%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.71%   |
| ZTE WCDMA MSM Spreadtrum Phone                                    | 1        | 0.35%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.35%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.35%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.35%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1        | 0.35%   |
| MediaTek File-CD Gadget                                           | 1        | 0.35%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.35%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.35%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 254      | 67.55%  |
| WiFi     | 117      | 31.12%  |
| Modem    | 4        | 1.06%   |
| Unknown  | 1        | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 203      | 76.32%  |
| WiFi     | 63       | 23.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 159      | 61.63%  |
| 2     | 86       | 33.33%  |
| 3     | 11       | 4.26%   |
| 4     | 2        | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 223      | 84.47%  |
| Yes  | 41       | 15.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 31       | 41.33%  |
| Cambridge Silicon Radio         | 21       | 28%     |
| Broadcom                        | 6        | 8%      |
| Realtek Semiconductor           | 3        | 4%      |
| Qualcomm Atheros Communications | 3        | 4%      |
| ASUSTek Computer                | 3        | 4%      |
| Ralink                          | 2        | 2.67%   |
| MediaTek                        | 1        | 1.33%   |
| Integrated System Solution      | 1        | 1.33%   |
| IMC Networks                    | 1        | 1.33%   |
| HTC (High Tech Computer)        | 1        | 1.33%   |
| Foxconn / Hon Hai               | 1        | 1.33%   |
| Edimax Technology               | 1        | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 21       | 27.27%  |
| Intel AX200 Bluetooth                                                | 12       | 15.58%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 7        | 9.09%   |
| Intel Bluetooth wireless interface                                   | 6        | 7.79%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 4        | 5.19%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 4        | 5.19%   |
| Realtek Bluetooth Radio                                              | 2        | 2.6%    |
| Ralink RT3290 Bluetooth                                              | 2        | 2.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 2        | 2.6%    |
| Intel AX210 Bluetooth                                                | 2        | 2.6%    |
| Broadcom HP Portable Bumble Bee                                      | 2        | 2.6%    |
| ASUS Bluetooth Radio                                                 | 2        | 2.6%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 1.3%    |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 1.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1        | 1.3%    |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 1.3%    |
| MediaTek Wireless_Device                                             | 1        | 1.3%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 1.3%    |
| IMC Networks Bluetooth Radio                                         | 1        | 1.3%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 1.3%    |
| Foxconn / Hon Hai Wireless_Device                                    | 1        | 1.3%    |
| Edimax Bluetooth Adapter                                             | 1        | 1.3%    |
| ASUS Bluetooth Device                                                | 1        | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 149      | 34.02%  |
| AMD                     | 129      | 29.45%  |
| Nvidia                  | 91       | 20.78%  |
| Logitech                | 13       | 2.97%   |
| C-Media Electronics     | 13       | 2.97%   |
| Kingston Technology     | 6        | 1.37%   |
| SteelSeries ApS         | 4        | 0.91%   |
| GN Netcom               | 3        | 0.68%   |
| Razer USA               | 2        | 0.46%   |
| JMTek                   | 2        | 0.46%   |
| GYROCOM C&C             | 2        | 0.46%   |
| Generalplus Technology  | 2        | 0.46%   |
| Dell                    | 2        | 0.46%   |
| Creative Technology     | 2        | 0.46%   |
| AKAI Professional M.I.  | 2        | 0.46%   |
| XMOS                    | 1        | 0.23%   |
| Texas Instruments       | 1        | 0.23%   |
| RODE Microphones        | 1        | 0.23%   |
| RME                     | 1        | 0.23%   |
| Microsoft               | 1        | 0.23%   |
| Lenovo                  | 1        | 0.23%   |
| KTMicro                 | 1        | 0.23%   |
| Jieli Technology        | 1        | 0.23%   |
| Giga-Byte Technology    | 1        | 0.23%   |
| Creative Labs           | 1        | 0.23%   |
| Cambridge Silicon Radio | 1        | 0.23%   |
| Blue Microphones        | 1        | 0.23%   |
| Audio-Technica          | 1        | 0.23%   |
| ASUSTek Computer        | 1        | 0.23%   |
| Astro Gaming            | 1        | 0.23%   |
| Apogee Electronics      | 1        | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 30       | 5.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 27       | 5.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 21       | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 19       | 3.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 18       | 3.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 17       | 3.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 17       | 3.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 16       | 3.1%    |
| Intel 200 Series PCH HD Audio                                                     | 13       | 2.52%   |
| AMD Family 17h/19h HD Audio Controller                                            | 10       | 1.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 9        | 1.74%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 8        | 1.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 8        | 1.55%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 8        | 1.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 8        | 1.55%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 8        | 1.55%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 8        | 1.55%   |
| AMD Navi 10 HDMI Audio                                                            | 8        | 1.55%   |
| AMD FCH Azalia Controller                                                         | 8        | 1.55%   |
| Nvidia GP106 High Definition Audio Controller                                     | 7        | 1.36%   |
| Nvidia GP102 HDMI Audio Controller                                                | 7        | 1.36%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 7        | 1.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7        | 1.36%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 7        | 1.36%   |
| Nvidia GK107 HDMI Audio Controller                                                | 6        | 1.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 6        | 1.16%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 6        | 1.16%   |
| Nvidia High Definition Audio Controller                                           | 5        | 0.97%   |
| Nvidia GP108 High Definition Audio Controller                                     | 5        | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 5        | 0.97%   |
| Nvidia GP104 High Definition Audio Controller                                     | 5        | 0.97%   |
| Nvidia GK104 HDMI Audio Controller                                                | 5        | 0.97%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 5        | 0.97%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4        | 0.78%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 0.78%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 4        | 0.78%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 4        | 0.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 4        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 26       | 18.84%  |
| Kingston            | 19       | 13.77%  |
| Unknown             | 15       | 10.87%  |
| SK hynix            | 15       | 10.87%  |
| Samsung Electronics | 12       | 8.7%    |
| Crucial             | 11       | 7.97%   |
| Corsair             | 9        | 6.52%   |
| A-DATA Technology   | 8        | 5.8%    |
| Team                | 5        | 3.62%   |
| Micron Technology   | 5        | 3.62%   |
| Transcend           | 2        | 1.45%   |
| Strontium           | 2        | 1.45%   |
| Elpida              | 2        | 1.45%   |
| Unknown (ABCD)      | 1        | 0.72%   |
| Ramaxel Technology  | 1        | 0.72%   |
| pqi                 | 1        | 0.72%   |
| PNY                 | 1        | 0.72%   |
| Nanya Technology    | 1        | 0.72%   |
| Innodisk            | 1        | 0.72%   |
| Hewlett-Packard     | 1        | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s       | 4        | 2.74%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s           | 3        | 2.05%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                         | 2        | 1.37%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                 | 2        | 1.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2        | 1.37%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s         | 2        | 1.37%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s               | 2        | 1.37%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 2        | 1.37%   |
| Kingston RAM 9905403-011.A03LF 2GB DIMM DDR3 1333MT/s        | 2        | 1.37%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s          | 2        | 1.37%   |
| G.Skill RAM F4-3200C16-8GTZB 8GB DIMM DDR4 3200MT/s          | 2        | 1.37%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 2        | 1.37%   |
| G.Skill RAM F4-2666C15-8GVR 8GB DIMM DDR4 2800MT/s           | 2        | 1.37%   |
| G.Skill RAM F3-1600C9-4GAB 4GB DIMM DDR3 1600MT/s            | 2        | 1.37%   |
| G.Skill RAM F3-14900CL10-8GBXL 8GB DIMM DDR3 1867MT/s        | 2        | 1.37%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s        | 2        | 1.37%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s        | 2        | 1.37%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s       | 2        | 1.37%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 2        | 1.37%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1        | 0.68%   |
| Unknown RAM Module 8GB DIMM 1066MT/s                         | 1        | 0.68%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                       | 1        | 0.68%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                      | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM 800MT/s                          | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM                                  | 1        | 0.68%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1066MT/s                | 1        | 0.68%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                 | 1        | 0.68%   |
| Unknown RAM Module 4096MB DIMM DDR2 1067MT/s                 | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1        | 0.68%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                  | 1        | 0.68%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 0.68%   |
| Transcend RAM TS512MSK64V3N 4GB SODIMM DDR3 1333MT/s         | 1        | 0.68%   |
| Transcend RAM JM1333KLN-4GK 2048MB DIMM DDR3 1333MT/s        | 1        | 0.68%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s           | 1        | 0.68%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s          | 1        | 0.68%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s           | 1        | 0.68%   |
| Strontium RAM SRT2G86U1-H9H 2048MB DIMM DDR3 1333MT/s        | 1        | 0.68%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                | 1        | 0.68%   |
| SK hynix RAM Module 1024MB DIMM DDR3 1333MT/s                | 1        | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 52       | 46.02%  |
| DDR3    | 44       | 38.94%  |
| Unknown | 8        | 7.08%   |
| SDRAM   | 4        | 3.54%   |
| DDR2    | 3        | 2.65%   |
| LPDDR4  | 1        | 0.88%   |
| DDR5    | 1        | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 104      | 93.69%  |
| SODIMM | 7        | 6.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 45       | 36.89%  |
| 4096  | 29       | 23.77%  |
| 16384 | 25       | 20.49%  |
| 2048  | 13       | 10.66%  |
| 32768 | 7        | 5.74%   |
| 1024  | 3        | 2.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 29       | 23.02%  |
| 3600    | 20       | 15.87%  |
| 1333    | 16       | 12.7%   |
| 3200    | 12       | 9.52%   |
| 2400    | 5        | 3.97%   |
| 1867    | 5        | 3.97%   |
| 3733    | 4        | 3.17%   |
| 2666    | 4        | 3.17%   |
| 2133    | 4        | 3.17%   |
| 2667    | 3        | 2.38%   |
| 800     | 3        | 2.38%   |
| 3800    | 2        | 1.59%   |
| 3400    | 2        | 1.59%   |
| 2800    | 2        | 1.59%   |
| 1800    | 2        | 1.59%   |
| 1066    | 2        | 1.59%   |
| 667     | 2        | 1.59%   |
| 4800    | 1        | 0.79%   |
| 3466    | 1        | 0.79%   |
| 2933    | 1        | 0.79%   |
| 2465    | 1        | 0.79%   |
| 2448    | 1        | 0.79%   |
| 2000    | 1        | 0.79%   |
| 1866    | 1        | 0.79%   |
| 1067    | 1        | 0.79%   |
| Unknown | 1        | 0.79%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 8        | 42.11%  |
| Hewlett-Packard    | 6        | 31.58%  |
| Canon              | 3        | 15.79%  |
| Fuji Xerox         | 1        | 5.26%   |
| Dymo-CoStar        | 1        | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| HP Officejet 4630 series         | 2        | 10.53%  |
| Brother Printer                  | 2        | 10.53%  |
| HP OfficeJet 8010 series         | 1        | 5.26%   |
| HP LaserJet Professional P1102w  | 1        | 5.26%   |
| HP ENVY 4520 series              | 1        | 5.26%   |
| HP DeskJet 2130 series           | 1        | 5.26%   |
| Fuji Xerox DocuPrint CM315/318 z | 1        | 5.26%   |
| Dymo-CoStar LabelWriter 450      | 1        | 5.26%   |
| Canon TS3100 series              | 1        | 5.26%   |
| Canon MB5300 series              | 1        | 5.26%   |
| Canon i950                       | 1        | 5.26%   |
| Brother MFC-J430W                | 1        | 5.26%   |
| Brother MFC-9140CDN              | 1        | 5.26%   |
| Brother MFC-7340                 | 1        | 5.26%   |
| Brother HL-L3230CDW series       | 1        | 5.26%   |
| Brother HL-2270DW Laser Printer  | 1        | 5.26%   |
| Brother HL-1430 Laser Printer    | 1        | 5.26%   |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 24       | 48.98%  |
| Microdia                    | 4        | 8.16%   |
| Samsung Electronics         | 3        | 6.12%   |
| GEMBIRD                     | 3        | 6.12%   |
| ARC International           | 3        | 6.12%   |
| Z-Star Microelectronics     | 1        | 2.04%   |
| Xiongmai                    | 1        | 2.04%   |
| Realtek Semiconductor       | 1        | 2.04%   |
| Novatek Microelectronics    | 1        | 2.04%   |
| Microsoft                   | 1        | 2.04%   |
| Lenovo                      | 1        | 2.04%   |
| KYE Systems (Mouse Systems) | 1        | 2.04%   |
| Google                      | 1        | 2.04%   |
| Generalplus Technology      | 1        | 2.04%   |
| EVGA                        | 1        | 2.04%   |
| Chicony Electronics         | 1        | 2.04%   |
| Arkmicro Technologies       | 1        | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 5        | 10.2%   |
| Logitech Webcam C170                              | 4        | 8.16%   |
| Samsung Galaxy A5 (MTP)                           | 3        | 6.12%   |
| Logitech QuickCam Pro 9000                        | 3        | 6.12%   |
| ARC International Camera                          | 3        | 6.12%   |
| Logitech Webcam Pro 9000                          | 2        | 4.08%   |
| Logitech Webcam C600                              | 2        | 4.08%   |
| Logitech HD Pro Webcam C920                       | 2        | 4.08%   |
| Logitech C922 Pro Stream Webcam                   | 2        | 4.08%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 2        | 4.08%   |
| Z-Star Venus USB2.0 Camera                        | 1        | 2.04%   |
| Xiongmai web camera                               | 1        | 2.04%   |
| Realtek HD 720P Webcam                            | 1        | 2.04%   |
| Novatek HP High Definition 2MP Webcam             | 1        | 2.04%   |
| Microsoft LifeCam HD-3000                         | 1        | 2.04%   |
| Microdia USB Microscope                           | 1        | 2.04%   |
| Microdia Sonix USB 2.0 Camera                     | 1        | 2.04%   |
| Microdia Laptop_Integrated_Webcam_FHD             | 1        | 2.04%   |
| Microdia Camera                                   | 1        | 2.04%   |
| Logitech Webcam C300                              | 1        | 2.04%   |
| Logitech Mic (Fusion)                             | 1        | 2.04%   |
| Logitech HD Webcam C615                           | 1        | 2.04%   |
| Logitech HD Webcam C525                           | 1        | 2.04%   |
| Lenovo FULL HD 1080P Webcam                       | 1        | 2.04%   |
| KYE Systems (Mouse Systems) FaceCam 1000X         | 1        | 2.04%   |
| Google Nexus/Pixel Device (MTP + debug)           | 1        | 2.04%   |
| Generalplus 2K HD Camera                          | 1        | 2.04%   |
| GEMBIRD USB2.0 PC CAMERA                          | 1        | 2.04%   |
| EVGA XR1 Capture Box                              | 1        | 2.04%   |
| Chicony HP High Definition 1MP Webcam             | 1        | 2.04%   |
| Arkmicro Webcam Carrefour                         | 1        | 2.04%   |

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
| 0     | 220      | 83.33%  |
| 1     | 40       | 15.15%  |
| 2     | 3        | 1.14%   |
| 5     | 1        | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 27.66%  |
| Graphics card            | 12       | 25.53%  |
| Bluetooth                | 5        | 10.64%  |
| Sound                    | 3        | 6.38%   |
| Multimedia controller    | 3        | 6.38%   |
| Dvb card                 | 3        | 6.38%   |
| Unassigned class         | 2        | 4.26%   |
| Storage/ide              | 2        | 4.26%   |
| Communication controller | 2        | 4.26%   |
| Storage/raid             | 1        | 2.13%   |
| Modem                    | 1        | 2.13%   |

