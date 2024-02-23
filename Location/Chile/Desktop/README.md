Linux in Chile - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Chile.

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

Total: 420

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | X99 V1.0                    | [202a9720c4](https://linux-hardware.org/?probe=202a9720c4) | Jan 30, 2024 |
| ASUSTek       | PRIME X670-P                | [1d4943457c](https://linux-hardware.org/?probe=1d4943457c) | Jan 26, 2024 |
| ASUSTek       | PRIME X670-P                | [75379edae7](https://linux-hardware.org/?probe=75379edae7) | Jan 26, 2024 |
| HP            | 304Ah                       | [5e40a8acee](https://linux-hardware.org/?probe=5e40a8acee) | Jan 24, 2024 |
| ECS           | G31T-M7                     | [254ece65d1](https://linux-hardware.org/?probe=254ece65d1) | Jan 12, 2024 |
| Shenzhen M... | F7BSC                       | [80d405caee](https://linux-hardware.org/?probe=80d405caee) | Jan 09, 2024 |
| ANGXUN        | X79 (INTEL Xeon E5/Corei... | [92d3ce2ee5](https://linux-hardware.org/?probe=92d3ce2ee5) | Dec 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [da4285cce4](https://linux-hardware.org/?probe=da4285cce4) | Dec 26, 2023 |
| MSI           | PRO B550M-P GEN3            | [9662ee22d6](https://linux-hardware.org/?probe=9662ee22d6) | Dec 26, 2023 |
| eMachines     | EMCP61M                     | [d464b480dd](https://linux-hardware.org/?probe=d464b480dd) | Dec 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [e8847d53ec](https://linux-hardware.org/?probe=e8847d53ec) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [1d510c91de](https://linux-hardware.org/?probe=1d510c91de) | Dec 12, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [5121b6a20c](https://linux-hardware.org/?probe=5121b6a20c) | Dec 09, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [f6ed574e0d](https://linux-hardware.org/?probe=f6ed574e0d) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [8198e47786](https://linux-hardware.org/?probe=8198e47786) | Dec 08, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [2a593d9294](https://linux-hardware.org/?probe=2a593d9294) | Dec 06, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [9b6c1bfbf2](https://linux-hardware.org/?probe=9b6c1bfbf2) | Dec 06, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | [707fd0c687](https://linux-hardware.org/?probe=707fd0c687) | Dec 02, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [80be39f0d4](https://linux-hardware.org/?probe=80be39f0d4) | Dec 01, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [6005ac3fdd](https://linux-hardware.org/?probe=6005ac3fdd) | Nov 26, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [f3956e461c](https://linux-hardware.org/?probe=f3956e461c) | Nov 23, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [f8778aa9e9](https://linux-hardware.org/?probe=f8778aa9e9) | Nov 20, 2023 |
| ECS           | H77H2-EM                    | [20c68c0667](https://linux-hardware.org/?probe=20c68c0667) | Nov 16, 2023 |
| MSI           | 880GM-E41                   | [707f319e17](https://linux-hardware.org/?probe=707f319e17) | Nov 12, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [2c921ede59](https://linux-hardware.org/?probe=2c921ede59) | Nov 08, 2023 |
| Foxconn       | P35A01                      | [e63e8acdaa](https://linux-hardware.org/?probe=e63e8acdaa) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6f89b3f8ad](https://linux-hardware.org/?probe=6f89b3f8ad) | Oct 22, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [19d60d452f](https://linux-hardware.org/?probe=19d60d452f) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [69f9b41478](https://linux-hardware.org/?probe=69f9b41478) | Oct 11, 2023 |
| MSI           | MS-7392                     | [5107ce50a1](https://linux-hardware.org/?probe=5107ce50a1) | Oct 09, 2023 |
| HP            | 2ADE                        | [b701a5c589](https://linux-hardware.org/?probe=b701a5c589) | Sep 27, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [16fe0e3ba6](https://linux-hardware.org/?probe=16fe0e3ba6) | Sep 22, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [aab34fa582](https://linux-hardware.org/?probe=aab34fa582) | Sep 22, 2023 |
| Dell          | 0WN7Y6 A01                  | [f4d4f80645](https://linux-hardware.org/?probe=f4d4f80645) | Sep 20, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [a44de9f197](https://linux-hardware.org/?probe=a44de9f197) | Sep 15, 2023 |
| HP            | 0A60h                       | [107f849e6b](https://linux-hardware.org/?probe=107f849e6b) | Sep 13, 2023 |
| ECS           | H81H3-M4                    | [f1cff1b2ac](https://linux-hardware.org/?probe=f1cff1b2ac) | Sep 11, 2023 |
| Dell          | 04Y8V0 A02                  | [aa2d2a4c29](https://linux-hardware.org/?probe=aa2d2a4c29) | Sep 08, 2023 |
| HP            | 2ADE                        | [f7b01f93c4](https://linux-hardware.org/?probe=f7b01f93c4) | Sep 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6215db2c5a](https://linux-hardware.org/?probe=6215db2c5a) | Sep 02, 2023 |
| Unknown       | Unknown                     | [3e3433226b](https://linux-hardware.org/?probe=3e3433226b) | Sep 01, 2023 |
| ASRock        | B550M Pro4                  | [6554eecc36](https://linux-hardware.org/?probe=6554eecc36) | Aug 24, 2023 |
| ASUSTek       | H110M-R                     | [3151636f73](https://linux-hardware.org/?probe=3151636f73) | Aug 16, 2023 |
| ASUSTek       | PRIME H410M-E               | [a9d7216b70](https://linux-hardware.org/?probe=a9d7216b70) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [c27b841a97](https://linux-hardware.org/?probe=c27b841a97) | Aug 15, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [ac7079fac9](https://linux-hardware.org/?probe=ac7079fac9) | Aug 05, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [b8f1735d23](https://linux-hardware.org/?probe=b8f1735d23) | Aug 04, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [6a6f453881](https://linux-hardware.org/?probe=6a6f453881) | Aug 02, 2023 |
| ECS           | H61H2-M17                   | [360623689a](https://linux-hardware.org/?probe=360623689a) | Jul 29, 2023 |
| ECS           | H61H2-M17                   | [aa0f0813e4](https://linux-hardware.org/?probe=aa0f0813e4) | Jul 29, 2023 |
| Unknown       | Unknown                     | [d9c029afa4](https://linux-hardware.org/?probe=d9c029afa4) | Jul 28, 2023 |
| MSI           | B85-G43 GAMING              | [ba47e8e20f](https://linux-hardware.org/?probe=ba47e8e20f) | Jul 27, 2023 |
| ASUSTek       | H110M-R                     | [5300c80b7e](https://linux-hardware.org/?probe=5300c80b7e) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [ab65cec6fe](https://linux-hardware.org/?probe=ab65cec6fe) | Jul 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [e056c22283](https://linux-hardware.org/?probe=e056c22283) | Jul 15, 2023 |
| Unknown       | Unknown                     | [3820e840f0](https://linux-hardware.org/?probe=3820e840f0) | Jul 15, 2023 |
| ASUSTek       | PRIME B450M-A               | [6c541c67b9](https://linux-hardware.org/?probe=6c541c67b9) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [eb024b5188](https://linux-hardware.org/?probe=eb024b5188) | Jul 10, 2023 |
| MSI           | H81M-E33                    | [804d078deb](https://linux-hardware.org/?probe=804d078deb) | Jul 10, 2023 |
| ASUSTek       | P7H55-M LX                  | [8a0d6c1825](https://linux-hardware.org/?probe=8a0d6c1825) | Jun 29, 2023 |
| MSI           | 880GM-E41                   | [91a2474332](https://linux-hardware.org/?probe=91a2474332) | Jun 28, 2023 |
| Unknown       | Unknown                     | [172c84a53d](https://linux-hardware.org/?probe=172c84a53d) | Jun 22, 2023 |
| BESSTAR Te... | UM700                       | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [6294c25695](https://linux-hardware.org/?probe=6294c25695) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [7e8ae5cb7a](https://linux-hardware.org/?probe=7e8ae5cb7a) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [176973d157](https://linux-hardware.org/?probe=176973d157) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [989287c8b1](https://linux-hardware.org/?probe=989287c8b1) | Jun 16, 2023 |
| ECS           | H61H2-M17                   | [63ded73edb](https://linux-hardware.org/?probe=63ded73edb) | Jun 14, 2023 |
| ECS           | H61H2-M17                   | [fb57cc3ed4](https://linux-hardware.org/?probe=fb57cc3ed4) | Jun 13, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [a597fc235e](https://linux-hardware.org/?probe=a597fc235e) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [6a368b8ecc](https://linux-hardware.org/?probe=6a368b8ecc) | Jun 09, 2023 |
| BESSTAR Te... | UM700                       | [92645b42ac](https://linux-hardware.org/?probe=92645b42ac) | Jun 08, 2023 |
| ASRock        | Z590 Phantom Gaming 4       | [1e9eef0102](https://linux-hardware.org/?probe=1e9eef0102) | Jun 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [259865e80e](https://linux-hardware.org/?probe=259865e80e) | Jun 01, 2023 |
| Intel         | H61                         | [685bd5d439](https://linux-hardware.org/?probe=685bd5d439) | May 12, 2023 |
| Lenovo        | SDK0E50510 WIN 262507960... | [2892c822d5](https://linux-hardware.org/?probe=2892c822d5) | May 12, 2023 |
| ASUSTek       | PRIME B560M-K               | [ce0391bdee](https://linux-hardware.org/?probe=ce0391bdee) | May 09, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [c8b7ffa6dc](https://linux-hardware.org/?probe=c8b7ffa6dc) | May 02, 2023 |
| ASUSTek       | PRIME J4005I-C              | [611ed4a200](https://linux-hardware.org/?probe=611ed4a200) | May 01, 2023 |
| ASUSTek       | PRIME X670-P                | [37f98c9450](https://linux-hardware.org/?probe=37f98c9450) | Apr 25, 2023 |
| ASUSTek       | PRIME X670-P                | [ebe7f36c99](https://linux-hardware.org/?probe=ebe7f36c99) | Apr 23, 2023 |
| Gigabyte      | B550M DS3H                  | [1950979b24](https://linux-hardware.org/?probe=1950979b24) | Apr 22, 2023 |
| Intel         | DG41RQ AAE54511-203         | [6a17fe6ead](https://linux-hardware.org/?probe=6a17fe6ead) | Apr 21, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [a7b05c2528](https://linux-hardware.org/?probe=a7b05c2528) | Apr 20, 2023 |
| WZA300S2R1... | SA300-D4                    | [e2a6ae91b9](https://linux-hardware.org/?probe=e2a6ae91b9) | Apr 17, 2023 |
| HP            | 8433 11                     | [911f2844c9](https://linux-hardware.org/?probe=911f2844c9) | Apr 13, 2023 |
| MSI           | MS-7360                     | [48bee654fc](https://linux-hardware.org/?probe=48bee654fc) | Apr 13, 2023 |
| ASRock        | B360M/OEM                   | [d1feabb956](https://linux-hardware.org/?probe=d1feabb956) | Apr 07, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [712e78de35](https://linux-hardware.org/?probe=712e78de35) | Apr 05, 2023 |
| Unknown       | X99-GT                      | [d4b6b3ebe8](https://linux-hardware.org/?probe=d4b6b3ebe8) | Apr 05, 2023 |
| HP            | 8433 11                     | [55f7473ba8](https://linux-hardware.org/?probe=55f7473ba8) | Mar 29, 2023 |
| MSI           | Z270 GAMING M3              | [2c25601c7c](https://linux-hardware.org/?probe=2c25601c7c) | Mar 22, 2023 |
| HP            | 18E7                        | [9e4b5010d8](https://linux-hardware.org/?probe=9e4b5010d8) | Mar 20, 2023 |
| MSI           | MS-7360                     | [6c8cb5d98f](https://linux-hardware.org/?probe=6c8cb5d98f) | Mar 18, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [8a802fa8fe](https://linux-hardware.org/?probe=8a802fa8fe) | Mar 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [679da48c41](https://linux-hardware.org/?probe=679da48c41) | Mar 16, 2023 |
| MSI           | H110M PRO-VH PLUS           | [088b681bdd](https://linux-hardware.org/?probe=088b681bdd) | Mar 13, 2023 |
| MSI           | X58 PLATINUM SLI            | [c8875fb17f](https://linux-hardware.org/?probe=c8875fb17f) | Mar 08, 2023 |
| HP            | 339A                        | [a2af229dad](https://linux-hardware.org/?probe=a2af229dad) | Mar 05, 2023 |
| Dell          | 0NW6H5 A00                  | [b4485b65b3](https://linux-hardware.org/?probe=b4485b65b3) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | [a52e16df32](https://linux-hardware.org/?probe=a52e16df32) | Feb 27, 2023 |
| MSI           | B85-G43 GAMING              | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [89f1272cd8](https://linux-hardware.org/?probe=89f1272cd8) | Feb 13, 2023 |
| Gigabyte      | B450M DS3H V2               | [a326374047](https://linux-hardware.org/?probe=a326374047) | Feb 12, 2023 |
| HP            | 1850                        | [54f5b16151](https://linux-hardware.org/?probe=54f5b16151) | Feb 11, 2023 |
| MSI           | 970 GAMING                  | [552d730c6d](https://linux-hardware.org/?probe=552d730c6d) | Feb 09, 2023 |
| ASUSTek       | P5B-Deluxe                  | [3fce6d5f05](https://linux-hardware.org/?probe=3fce6d5f05) | Feb 07, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [104a086d29](https://linux-hardware.org/?probe=104a086d29) | Feb 05, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [578b166faa](https://linux-hardware.org/?probe=578b166faa) | Feb 05, 2023 |
| Dell          | 06D7TR A02                  | [b3bb51473f](https://linux-hardware.org/?probe=b3bb51473f) | Feb 01, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| MACHINIST     | X99Z V102 IENGINEER         | [d2cfaf56df](https://linux-hardware.org/?probe=d2cfaf56df) | Jan 31, 2023 |
| ViewSonic     | VOT132                      | [a8ecfadd53](https://linux-hardware.org/?probe=a8ecfadd53) | Jan 30, 2023 |
| Dell          | 06D7TR A02                  | [cd487a22cd](https://linux-hardware.org/?probe=cd487a22cd) | Jan 25, 2023 |
| HP            | 2ADE                        | [b927cb3f98](https://linux-hardware.org/?probe=b927cb3f98) | Jan 24, 2023 |
| ASUSTek       | F2A55-M LK2                 | [93db1bee75](https://linux-hardware.org/?probe=93db1bee75) | Jan 23, 2023 |
| ASUSTek       | H110M-R                     | [f872a64ba1](https://linux-hardware.org/?probe=f872a64ba1) | Jan 20, 2023 |
| MSI           | H81M-E33                    | [ddb1be1cc6](https://linux-hardware.org/?probe=ddb1be1cc6) | Jan 18, 2023 |
| HC            | HCAR357-MI V1.0             | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [1a68bed616](https://linux-hardware.org/?probe=1a68bed616) | Jan 12, 2023 |
| HP            | 83F2                        | [7482186165](https://linux-hardware.org/?probe=7482186165) | Jan 11, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [247bb9fe04](https://linux-hardware.org/?probe=247bb9fe04) | Jan 10, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [68e1087fde](https://linux-hardware.org/?probe=68e1087fde) | Nov 25, 2022 |
| HP            | 8309                        | [8329dc7b8d](https://linux-hardware.org/?probe=8329dc7b8d) | Nov 23, 2022 |
| MSI           | A320M-A PRO MAX             | [c3aaf6eed2](https://linux-hardware.org/?probe=c3aaf6eed2) | Nov 09, 2022 |
| MSI           | A320M-A PRO MAX             | [5030ff83c2](https://linux-hardware.org/?probe=5030ff83c2) | Nov 08, 2022 |
| ASRock        | H310CM-HDV                  | [cb1cecc5e1](https://linux-hardware.org/?probe=cb1cecc5e1) | Nov 05, 2022 |
| Pegatron      | IPPCR-SS                    | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| Huanan        | X99-QD4 V1.0                | [2e4c04ada0](https://linux-hardware.org/?probe=2e4c04ada0) | Oct 27, 2022 |
| Huanan        | X99-QD4 V1.0                | [cb31f9ab8b](https://linux-hardware.org/?probe=cb31f9ab8b) | Oct 26, 2022 |
| HP            | 225E                        | [7e246d254b](https://linux-hardware.org/?probe=7e246d254b) | Oct 24, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| ASUSTek       | P5B-Deluxe                  | [e3dcca8113](https://linux-hardware.org/?probe=e3dcca8113) | Oct 11, 2022 |
| ASUSTek       | P5B-Deluxe                  | [cf179c716e](https://linux-hardware.org/?probe=cf179c716e) | Sep 27, 2022 |
| ASUSTek       | PRIME A320M-K               | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| BESSTAR Te... | UM700                       | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| Dell          | 060K5C A00                  | [a64a44387b](https://linux-hardware.org/?probe=a64a44387b) | Sep 13, 2022 |
| BESSTAR Te... | UM700                       | [6847632df3](https://linux-hardware.org/?probe=6847632df3) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2176e4d70f](https://linux-hardware.org/?probe=2176e4d70f) | Sep 05, 2022 |
| ECS           | H61H-G11/7.0                | [790b93cbee](https://linux-hardware.org/?probe=790b93cbee) | Sep 03, 2022 |
| BESSTAR Te... | UM700                       | [f1198508de](https://linux-hardware.org/?probe=f1198508de) | Sep 03, 2022 |
| MSI           | H81M-E33                    | [ec88b5b492](https://linux-hardware.org/?probe=ec88b5b492) | Sep 02, 2022 |
| ASRock        | X99 Taichi                  | [4cd4bf6c89](https://linux-hardware.org/?probe=4cd4bf6c89) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [8e1734f31a](https://linux-hardware.org/?probe=8e1734f31a) | Sep 01, 2022 |
| SZMZ          | X99M-G2                     | [eff1231310](https://linux-hardware.org/?probe=eff1231310) | Aug 31, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [8712171422](https://linux-hardware.org/?probe=8712171422) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [f065870080](https://linux-hardware.org/?probe=f065870080) | Aug 30, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [93f28535f8](https://linux-hardware.org/?probe=93f28535f8) | Aug 23, 2022 |
| MSI           | H81M-E33                    | [56808775ee](https://linux-hardware.org/?probe=56808775ee) | Aug 23, 2022 |
| Intel         | X79M-S                      | [b6746f7b8d](https://linux-hardware.org/?probe=b6746f7b8d) | Aug 18, 2022 |
| Intel         | X79M-S                      | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| BESSTAR Te... | UM700                       | [81a59240ea](https://linux-hardware.org/?probe=81a59240ea) | Aug 13, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [3db0355713](https://linux-hardware.org/?probe=3db0355713) | Aug 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f9efd8697b](https://linux-hardware.org/?probe=f9efd8697b) | Aug 11, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [18b6026d87](https://linux-hardware.org/?probe=18b6026d87) | Aug 09, 2022 |
| MACHINIST     | X79 V2.82H                  | [29694e2098](https://linux-hardware.org/?probe=29694e2098) | Jul 29, 2022 |
| Intel         | D54250WYK H13922-303        | [71b03b93a2](https://linux-hardware.org/?probe=71b03b93a2) | Jul 27, 2022 |
| Olidata       | Unknown                     | [ac7a530d9d](https://linux-hardware.org/?probe=ac7a530d9d) | Jul 19, 2022 |
| Gigabyte      | H410M H                     | [8a0a0ed167](https://linux-hardware.org/?probe=8a0a0ed167) | Jul 16, 2022 |
| Gigabyte      | H410M H                     | [e94723280f](https://linux-hardware.org/?probe=e94723280f) | Jul 16, 2022 |
| MSI           | A320M-A PRO MAX             | [31127e76f8](https://linux-hardware.org/?probe=31127e76f8) | Jul 14, 2022 |
| MSI           | A320M-A PRO MAX             | [ed83060c1a](https://linux-hardware.org/?probe=ed83060c1a) | Jul 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0c96551a28](https://linux-hardware.org/?probe=0c96551a28) | Jul 09, 2022 |
| MSI           | B350 GAMING PLUS            | [de014d917d](https://linux-hardware.org/?probe=de014d917d) | Jul 05, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [f5d7a0bba4](https://linux-hardware.org/?probe=f5d7a0bba4) | Jun 17, 2022 |
| BESSTAR Te... | UM700                       | [d0c247db91](https://linux-hardware.org/?probe=d0c247db91) | Jun 17, 2022 |
| MSI           | B350 PC MATE                | [baf792ad50](https://linux-hardware.org/?probe=baf792ad50) | Jun 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [576c9acdaa](https://linux-hardware.org/?probe=576c9acdaa) | Jun 08, 2022 |
| Intel         | DH61BF AAG81311-101         | [b1fe95fd93](https://linux-hardware.org/?probe=b1fe95fd93) | May 31, 2022 |
| ECS           | MCP61M-M3                   | [b785b68657](https://linux-hardware.org/?probe=b785b68657) | May 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [b7b419d941](https://linux-hardware.org/?probe=b7b419d941) | May 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [713dcb3d05](https://linux-hardware.org/?probe=713dcb3d05) | May 17, 2022 |
| HP            | 2ADE                        | [77c2ea750b](https://linux-hardware.org/?probe=77c2ea750b) | May 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f2f965ba56](https://linux-hardware.org/?probe=f2f965ba56) | May 13, 2022 |
| ASUSTek       | Maximus VI EXTREME          | [21e4e874a2](https://linux-hardware.org/?probe=21e4e874a2) | May 06, 2022 |
| ASUSTek       | Maximus VI EXTREME          | [37e77cbfe5](https://linux-hardware.org/?probe=37e77cbfe5) | May 06, 2022 |
| MSI           | B250M GAMING PRO            | [cd1e81afae](https://linux-hardware.org/?probe=cd1e81afae) | May 03, 2022 |
| MSI           | B250M GAMING PRO            | [bf6d6784ab](https://linux-hardware.org/?probe=bf6d6784ab) | May 03, 2022 |
| MSI           | B450M BAZOOKA               | [a913401ce9](https://linux-hardware.org/?probe=a913401ce9) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | [726be8a4f1](https://linux-hardware.org/?probe=726be8a4f1) | May 02, 2022 |
| ASUSTek       | H110M-R                     | [0fa0b3d5f4](https://linux-hardware.org/?probe=0fa0b3d5f4) | May 01, 2022 |
| MSI           | H110M PRO-VH PLUS           | [876baf36d7](https://linux-hardware.org/?probe=876baf36d7) | Apr 29, 2022 |
| Intel         | DH61BF AAG81311-101         | [f40f12b9be](https://linux-hardware.org/?probe=f40f12b9be) | Apr 27, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [cb4bc274b3](https://linux-hardware.org/?probe=cb4bc274b3) | Apr 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [79eb10a5ef](https://linux-hardware.org/?probe=79eb10a5ef) | Apr 19, 2022 |
| MSI           | H81M-E33                    | [ff9197cd63](https://linux-hardware.org/?probe=ff9197cd63) | Apr 17, 2022 |
| ASUSTek       | PRIME A320M-K               | [7d0cde0bcd](https://linux-hardware.org/?probe=7d0cde0bcd) | Apr 13, 2022 |
| MSI           | B350 TOMAHAWK               | [f531f62c1b](https://linux-hardware.org/?probe=f531f62c1b) | Apr 03, 2022 |
| HP            | 1998                        | [13b901f36a](https://linux-hardware.org/?probe=13b901f36a) | Mar 29, 2022 |
| ASUSTek       | PRIME B450M-A               | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| ASUSTek       | PRIME H410M-E               | [e02f2032f1](https://linux-hardware.org/?probe=e02f2032f1) | Mar 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9183654349](https://linux-hardware.org/?probe=9183654349) | Mar 22, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [539ebb7dd9](https://linux-hardware.org/?probe=539ebb7dd9) | Mar 15, 2022 |
| ASUSTek       | PRIME H410M-E               | [671a3fc70b](https://linux-hardware.org/?probe=671a3fc70b) | Mar 12, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [332a3f936b](https://linux-hardware.org/?probe=332a3f936b) | Feb 28, 2022 |
| ASUSTek       | B85-PRO GAMER               | [3f97cefeb4](https://linux-hardware.org/?probe=3f97cefeb4) | Feb 26, 2022 |
| Dell          | 0CT017                      | [27a31fcb1b](https://linux-hardware.org/?probe=27a31fcb1b) | Feb 17, 2022 |
| Gigabyte      | B450M DS3H V2               | [824518037a](https://linux-hardware.org/?probe=824518037a) | Feb 10, 2022 |
| Pegatron      | 2ACB                        | [b7987fdaa7](https://linux-hardware.org/?probe=b7987fdaa7) | Feb 10, 2022 |
| Gigabyte      | B560M DS3H                  | [3c0ad9ce1b](https://linux-hardware.org/?probe=3c0ad9ce1b) | Feb 08, 2022 |
| MSI           | H310M GAMING ARCTIC         | [842ee88335](https://linux-hardware.org/?probe=842ee88335) | Jan 26, 2022 |
| MSI           | B85M-E33 V2                 | [ef65c0c144](https://linux-hardware.org/?probe=ef65c0c144) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | [8107f2613f](https://linux-hardware.org/?probe=8107f2613f) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | [704e9c09ad](https://linux-hardware.org/?probe=704e9c09ad) | Jan 05, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [2e00250378](https://linux-hardware.org/?probe=2e00250378) | Dec 16, 2021 |
| ASUSTek       | AM1M-A                      | [5113655631](https://linux-hardware.org/?probe=5113655631) | Dec 14, 2021 |
| ASUSTek       | PRIME A320M-K               | [fc49eed81d](https://linux-hardware.org/?probe=fc49eed81d) | Dec 09, 2021 |
| MSI           | 3664h                       | [c4bc6c8049](https://linux-hardware.org/?probe=c4bc6c8049) | Nov 29, 2021 |
| ASUSTek       | PRIME Z590-P                | [6490a6beba](https://linux-hardware.org/?probe=6490a6beba) | Nov 29, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [e9b3a62560](https://linux-hardware.org/?probe=e9b3a62560) | Nov 26, 2021 |
| ASUSTek       | PRIME X570-PRO              | [93e8bc8935](https://linux-hardware.org/?probe=93e8bc8935) | Nov 24, 2021 |
| HP            | 2215                        | [4e65fa6078](https://linux-hardware.org/?probe=4e65fa6078) | Nov 09, 2021 |
| MSI           | B365M PRO-VH                | [c2976ad59c](https://linux-hardware.org/?probe=c2976ad59c) | Nov 03, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3f67c7622c](https://linux-hardware.org/?probe=3f67c7622c) | Oct 22, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| Nvidia        | NF-MCP61                    | [666f204c08](https://linux-hardware.org/?probe=666f204c08) | Oct 18, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [8f7c7a493b](https://linux-hardware.org/?probe=8f7c7a493b) | Oct 16, 2021 |
| ASUSTek       | PRIME Z590-P                | [36e45017ff](https://linux-hardware.org/?probe=36e45017ff) | Oct 14, 2021 |
| ASUSTek       | PRIME Z590-P                | [36d8e83f29](https://linux-hardware.org/?probe=36d8e83f29) | Oct 11, 2021 |
| Intel         | DG41WV AAE90316-103         | [0055a963ef](https://linux-hardware.org/?probe=0055a963ef) | Sep 30, 2021 |
| Gigabyte      | A520M DS3H                  | [228b36fb26](https://linux-hardware.org/?probe=228b36fb26) | Sep 28, 2021 |
| ASUSTek       | P8H61-M LX                  | [7360f8d859](https://linux-hardware.org/?probe=7360f8d859) | Sep 23, 2021 |
| Huanan        | X79 249PC V2.3              | [feb9cf5a3f](https://linux-hardware.org/?probe=feb9cf5a3f) | Sep 20, 2021 |
| Huanan        | X79 249PC V2.3              | [0025ab8888](https://linux-hardware.org/?probe=0025ab8888) | Sep 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [99773cf00e](https://linux-hardware.org/?probe=99773cf00e) | Sep 19, 2021 |
| ASRock        | Z490 Phantom Gaming 4G      | [7857ce2ffa](https://linux-hardware.org/?probe=7857ce2ffa) | Sep 16, 2021 |
| ASUSTek       | B85M-E                      | [27a6448b5e](https://linux-hardware.org/?probe=27a6448b5e) | Sep 12, 2021 |
| HC            | HCAR357-MI V1.0             | [e2df45f5f6](https://linux-hardware.org/?probe=e2df45f5f6) | Sep 12, 2021 |
| Intel         | X79M-S                      | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| ASUSTek       | B85M-E                      | [36685ad5ea](https://linux-hardware.org/?probe=36685ad5ea) | Sep 11, 2021 |
| HP            | 339A                        | [ae80063e20](https://linux-hardware.org/?probe=ae80063e20) | Sep 07, 2021 |
| HC            | HCAR357-MI V1.0             | [14536c9a37](https://linux-hardware.org/?probe=14536c9a37) | Sep 06, 2021 |
| Intel         | X79M-S                      | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| HP            | 339A                        | [ceb91782c2](https://linux-hardware.org/?probe=ceb91782c2) | Sep 05, 2021 |
| HC            | HCAR357-MI V1.0             | [3697a37403](https://linux-hardware.org/?probe=3697a37403) | Sep 04, 2021 |
| HC            | HCAR357-MI V1.0             | [e4d2306204](https://linux-hardware.org/?probe=e4d2306204) | Sep 04, 2021 |
| HP            | 339A                        | [2c96fd74fb](https://linux-hardware.org/?probe=2c96fd74fb) | Sep 04, 2021 |
| HP            | 339A                        | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | 339A                        | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [190ef257e8](https://linux-hardware.org/?probe=190ef257e8) | Aug 30, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [f6049274c5](https://linux-hardware.org/?probe=f6049274c5) | Aug 27, 2021 |
| Gigabyte      | H97M-D3H                    | [a2afd00e64](https://linux-hardware.org/?probe=a2afd00e64) | Aug 26, 2021 |
| Dell          | 0GDG8Y A00                  | [2a0bf4d1a9](https://linux-hardware.org/?probe=2a0bf4d1a9) | Aug 21, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [0eb2abca1d](https://linux-hardware.org/?probe=0eb2abca1d) | Aug 18, 2021 |
| Gigabyte      | B450M DS3H V2               | [9c25f25e8f](https://linux-hardware.org/?probe=9c25f25e8f) | Aug 16, 2021 |
| Pegatron      | 2ADC                        | [48cc7f548e](https://linux-hardware.org/?probe=48cc7f548e) | Aug 13, 2021 |
| MSI           | B75MA-E33                   | [8a1743cb75](https://linux-hardware.org/?probe=8a1743cb75) | Aug 10, 2021 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [482c64a9c9](https://linux-hardware.org/?probe=482c64a9c9) | Aug 03, 2021 |
| ASUSTek       | PRIME B450M-A               | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60b58b4557](https://linux-hardware.org/?probe=60b58b4557) | Jul 28, 2021 |
| ASUSTek       | PRIME H410M-E               | [cae2419e98](https://linux-hardware.org/?probe=cae2419e98) | Jul 25, 2021 |
| MSI           | 3664h                       | [491117f46c](https://linux-hardware.org/?probe=491117f46c) | Jul 25, 2021 |
| MSI           | 3664h                       | [c9f3c48709](https://linux-hardware.org/?probe=c9f3c48709) | Jul 24, 2021 |
| ASUSTek       | PRIME B450M-A               | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| MSI           | H81M-E33                    | [f56f54e2fa](https://linux-hardware.org/?probe=f56f54e2fa) | Jul 18, 2021 |
| ASUSTek       | PRIME X570-P                | [783a5cafc2](https://linux-hardware.org/?probe=783a5cafc2) | Jul 18, 2021 |
| eMachines     | EL1352                      | [83c494c15a](https://linux-hardware.org/?probe=83c494c15a) | Jul 17, 2021 |
| R-StyleCom... | ALICON AI2S-A21 00.69       | [85a8017eaf](https://linux-hardware.org/?probe=85a8017eaf) | Jul 15, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5320824c78](https://linux-hardware.org/?probe=5320824c78) | Jul 11, 2021 |
| Dell          | 0Y5DDC A00                  | [1888baa539](https://linux-hardware.org/?probe=1888baa539) | Jul 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a87404851f](https://linux-hardware.org/?probe=a87404851f) | Jul 01, 2021 |
| MSI           | A75MA-G55                   | [3611191f22](https://linux-hardware.org/?probe=3611191f22) | Jun 30, 2021 |
| Intel         | X79 V2.72B                  | [c78b66e96e](https://linux-hardware.org/?probe=c78b66e96e) | Jun 25, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [aa0efa1872](https://linux-hardware.org/?probe=aa0efa1872) | Jun 19, 2021 |
| Unknown       | Intel X79                   | [5be1e4c74c](https://linux-hardware.org/?probe=5be1e4c74c) | Jun 18, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [033cd8c9eb](https://linux-hardware.org/?probe=033cd8c9eb) | Jun 17, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [8bb06ce851](https://linux-hardware.org/?probe=8bb06ce851) | Jun 16, 2021 |
| MSI           | 970A-G46                    | [f7b1001ef1](https://linux-hardware.org/?probe=f7b1001ef1) | Jun 13, 2021 |
| Intel         | DZ77GA-70K AAG39009-401     | [a88c5c7685](https://linux-hardware.org/?probe=a88c5c7685) | Jun 09, 2021 |
| ASUSTek       | PRIME X570-P                | [587e4453b3](https://linux-hardware.org/?probe=587e4453b3) | Jun 04, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [86060380c8](https://linux-hardware.org/?probe=86060380c8) | May 23, 2021 |
| ASUSTek       | P5K3 Deluxe                 | [458525ba70](https://linux-hardware.org/?probe=458525ba70) | May 22, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [0be7d156c5](https://linux-hardware.org/?probe=0be7d156c5) | May 17, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [493edc40c4](https://linux-hardware.org/?probe=493edc40c4) | May 15, 2021 |
| Intel         | YL-3160L2                   | [c282d94246](https://linux-hardware.org/?probe=c282d94246) | May 13, 2021 |
| Lenovo        | ThinkCentre M55 8808E19     | [a53c13a5c9](https://linux-hardware.org/?probe=a53c13a5c9) | May 12, 2021 |
| MSI           | X58 PLATINUM SLI            | [1fba25dbcf](https://linux-hardware.org/?probe=1fba25dbcf) | May 12, 2021 |
| MSI           | X58 PLATINUM SLI            | [c71715672c](https://linux-hardware.org/?probe=c71715672c) | May 12, 2021 |
| Olidata       | Unknown                     | [1dc7094a4d](https://linux-hardware.org/?probe=1dc7094a4d) | May 09, 2021 |
| HP            | 339A                        | [c103096e94](https://linux-hardware.org/?probe=c103096e94) | May 09, 2021 |
| HP            | 339A                        | [1b94801e8b](https://linux-hardware.org/?probe=1b94801e8b) | May 09, 2021 |
| Olidata       | Unknown                     | [0c2f6b27a9](https://linux-hardware.org/?probe=0c2f6b27a9) | May 08, 2021 |
| MSI           | H81M-E33                    | [47447aaec1](https://linux-hardware.org/?probe=47447aaec1) | May 05, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [ef811a6184](https://linux-hardware.org/?probe=ef811a6184) | May 01, 2021 |
| Gigabyte      | B450M GAMING                | [8ed2b2284e](https://linux-hardware.org/?probe=8ed2b2284e) | Apr 24, 2021 |
| ASUSTek       | P5K SE                      | [73a2ad1fd9](https://linux-hardware.org/?probe=73a2ad1fd9) | Apr 18, 2021 |
| ECS           | MCP61M-M3                   | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| MSI           | H81M-E33                    | [a5ebd5e702](https://linux-hardware.org/?probe=a5ebd5e702) | Apr 13, 2021 |
| Unknown       | Unknown                     | [a13b6fcbcd](https://linux-hardware.org/?probe=a13b6fcbcd) | Apr 12, 2021 |
| ASUSTek       | PRIME J4005I-C              | [5a1bc2f8fe](https://linux-hardware.org/?probe=5a1bc2f8fe) | Apr 10, 2021 |
| ASUSTek       | PRIME J4005I-C              | [79f36c06be](https://linux-hardware.org/?probe=79f36c06be) | Apr 09, 2021 |
| ASUSTek       | PRIME B450M-A               | [8e2a8be8ce](https://linux-hardware.org/?probe=8e2a8be8ce) | Apr 06, 2021 |
| Foxconn       | G31MV/G31MV-K FAB           | [18047eb612](https://linux-hardware.org/?probe=18047eb612) | Apr 01, 2021 |
| ASUSTek       | P5K SE                      | [fb06c3aee0](https://linux-hardware.org/?probe=fb06c3aee0) | Mar 31, 2021 |
| ASUSTek       | P5K SE                      | [22e69da73a](https://linux-hardware.org/?probe=22e69da73a) | Mar 30, 2021 |
| MSI           | 970A-G46                    | [09083497aa](https://linux-hardware.org/?probe=09083497aa) | Mar 26, 2021 |
| MSI           | 970A-G46                    | [dfb535cf31](https://linux-hardware.org/?probe=dfb535cf31) | Mar 26, 2021 |
| HP            | 18E9                        | [db74abc8b8](https://linux-hardware.org/?probe=db74abc8b8) | Mar 23, 2021 |
| HP            | 18E9                        | [13bfb17279](https://linux-hardware.org/?probe=13bfb17279) | Mar 23, 2021 |
| HP            | ProLiant ML10               | [1b448e4a71](https://linux-hardware.org/?probe=1b448e4a71) | Mar 23, 2021 |
| HP            | ProLiant ML10               | [cd6b0c3826](https://linux-hardware.org/?probe=cd6b0c3826) | Mar 22, 2021 |
| ASUSTek       | H110M-D                     | [da2dd5ad1a](https://linux-hardware.org/?probe=da2dd5ad1a) | Mar 15, 2021 |
| ECS           | A740GM-M                    | [442aa41981](https://linux-hardware.org/?probe=442aa41981) | Mar 08, 2021 |
| Intel         | X79 V1.x                    | [2b98f9b956](https://linux-hardware.org/?probe=2b98f9b956) | Mar 08, 2021 |
| Gigabyte      | 970A-DS3P                   | [000cba3fb5](https://linux-hardware.org/?probe=000cba3fb5) | Feb 28, 2021 |
| ASUSTek       | M5A97 R2.0                  | [485a4f1e98](https://linux-hardware.org/?probe=485a4f1e98) | Feb 25, 2021 |
| Unknown       | AD12-B                      | [8167d089b9](https://linux-hardware.org/?probe=8167d089b9) | Feb 20, 2021 |
| MSI           | MS-7267                     | [79cfa785c3](https://linux-hardware.org/?probe=79cfa785c3) | Feb 16, 2021 |
| MSI           | MS-7267                     | [9677e2392c](https://linux-hardware.org/?probe=9677e2392c) | Feb 16, 2021 |
| Dell          | 0CRH6C A01                  | [31da132ae8](https://linux-hardware.org/?probe=31da132ae8) | Feb 08, 2021 |
| Dell          | 0CRH6C A01                  | [8e9e7ffea0](https://linux-hardware.org/?probe=8e9e7ffea0) | Feb 08, 2021 |
| Unknown       | AD12-B                      | [6635cbda4d](https://linux-hardware.org/?probe=6635cbda4d) | Feb 06, 2021 |
| Unknown       | AD12-B                      | [05ad299f0e](https://linux-hardware.org/?probe=05ad299f0e) | Feb 06, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [121e3e7d2d](https://linux-hardware.org/?probe=121e3e7d2d) | Feb 02, 2021 |
| HP            | 2ADE                        | [2ee5093250](https://linux-hardware.org/?probe=2ee5093250) | Feb 02, 2021 |
| ECS           | MCP61M-M3                   | [445f06dbde](https://linux-hardware.org/?probe=445f06dbde) | Jan 29, 2021 |
| ASUSTek       | PRIME B450M-A               | [1a8312f66a](https://linux-hardware.org/?probe=1a8312f66a) | Jan 29, 2021 |
| ASUSTek       | PRIME B450M-A               | [b024bfc145](https://linux-hardware.org/?probe=b024bfc145) | Jan 29, 2021 |
| Intel         | SHARKBAY                    | [c1df3dc860](https://linux-hardware.org/?probe=c1df3dc860) | Jan 21, 2021 |
| IBM           | 813311S                     | [c65634928d](https://linux-hardware.org/?probe=c65634928d) | Jan 20, 2021 |
| IBM           | 813311S                     | [9dc5e1fd39](https://linux-hardware.org/?probe=9dc5e1fd39) | Jan 19, 2021 |
| Huanan        | X79 VAA1                    | [d88d20e6fc](https://linux-hardware.org/?probe=d88d20e6fc) | Jan 15, 2021 |
| MSI           | B360M PRO-VH                | [f666aa301e](https://linux-hardware.org/?probe=f666aa301e) | Jan 08, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [fb8fa788e3](https://linux-hardware.org/?probe=fb8fa788e3) | Jan 07, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [fb56fb77b9](https://linux-hardware.org/?probe=fb56fb77b9) | Jan 07, 2021 |
| ASUSTek       | M5A78L-M LX PLUS            | [74ccd1687d](https://linux-hardware.org/?probe=74ccd1687d) | Dec 24, 2020 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [df5beb221f](https://linux-hardware.org/?probe=df5beb221f) | Nov 15, 2020 |
| Gigabyte      | H97-Gaming 3                | [2c19015153](https://linux-hardware.org/?probe=2c19015153) | Nov 05, 2020 |
| ECS           | A785GM-M                    | [fa61acdd56](https://linux-hardware.org/?probe=fa61acdd56) | Oct 30, 2020 |
| ASUSTek       | A68HM-PLUS                  | [e31a805419](https://linux-hardware.org/?probe=e31a805419) | Oct 24, 2020 |
| ASUSTek       | M5A99X EVO                  | [e2a0899961](https://linux-hardware.org/?probe=e2a0899961) | Oct 23, 2020 |
| ASUSTek       | A68HM-PLUS                  | [e1ac94acb7](https://linux-hardware.org/?probe=e1ac94acb7) | Oct 23, 2020 |
| Intel         | X99                         | [53e51e0b25](https://linux-hardware.org/?probe=53e51e0b25) | Oct 22, 2020 |
| Intel         | X99                         | [194038048f](https://linux-hardware.org/?probe=194038048f) | Oct 22, 2020 |
| MSI           | B75MA-E33                   | [1616dff15a](https://linux-hardware.org/?probe=1616dff15a) | Oct 04, 2020 |
| Intel         | DH55PJ AAE93812-301         | [f6a0fd4389](https://linux-hardware.org/?probe=f6a0fd4389) | Sep 30, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [5e196929f0](https://linux-hardware.org/?probe=5e196929f0) | Sep 28, 2020 |
| ASUSTek       | F2A55-M LK2                 | [0ad4bcad78](https://linux-hardware.org/?probe=0ad4bcad78) | Sep 23, 2020 |
| HP            | 2ADE                        | [0ac3191171](https://linux-hardware.org/?probe=0ac3191171) | Sep 10, 2020 |
| HP            | 2ADE                        | [1cf059d943](https://linux-hardware.org/?probe=1cf059d943) | Sep 10, 2020 |
| MSI           | H61M-P20                    | [9eafb382df](https://linux-hardware.org/?probe=9eafb382df) | Aug 28, 2020 |
| HP            | 81C3                        | [d558ddad9e](https://linux-hardware.org/?probe=d558ddad9e) | Aug 22, 2020 |
| PCPartner     | G43-F71862                  | [6f7db25de0](https://linux-hardware.org/?probe=6f7db25de0) | Aug 12, 2020 |
| Colorful T... | C.Q1900M PRO V20            | [55195790be](https://linux-hardware.org/?probe=55195790be) | Aug 10, 2020 |
| AMI           | Cherry Trail CR             | [69e0a22aed](https://linux-hardware.org/?probe=69e0a22aed) | Aug 07, 2020 |
| Gigabyte      | H310M H x.x                 | [8067b679a3](https://linux-hardware.org/?probe=8067b679a3) | Aug 06, 2020 |
| MSI           | H61M-P20                    | [594f095da2](https://linux-hardware.org/?probe=594f095da2) | Aug 02, 2020 |
| Dell          | 0GDG8Y A00                  | [a1fb518075](https://linux-hardware.org/?probe=a1fb518075) | Jul 12, 2020 |
| Dell          | 0GDG8Y A00                  | [8bb25da515](https://linux-hardware.org/?probe=8bb25da515) | Jul 09, 2020 |
| ASRock        | B450M Pro4                  | [06da0a5ed7](https://linux-hardware.org/?probe=06da0a5ed7) | Jul 05, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [4788e05f08](https://linux-hardware.org/?probe=4788e05f08) | Jul 01, 2020 |
| ASUSTek       | P5KPL-AM                    | [8b9bb2543f](https://linux-hardware.org/?probe=8b9bb2543f) | Jun 28, 2020 |
| ASUSTek       | M5A78L-M LX                 | [ee35b699fa](https://linux-hardware.org/?probe=ee35b699fa) | Jun 24, 2020 |
| Apple         | Mac-F42C88C8 Proto1         | [646f93ec3a](https://linux-hardware.org/?probe=646f93ec3a) | Jun 20, 2020 |
| Apple         | Mac-F42C88C8 Proto1         | [08ce018dd0](https://linux-hardware.org/?probe=08ce018dd0) | Jun 20, 2020 |
| MSI           | MS-7379                     | [b7f52ad261](https://linux-hardware.org/?probe=b7f52ad261) | Jun 18, 2020 |
| TPV-INVENT... | 2AC6 A01                    | [90725b3c8a](https://linux-hardware.org/?probe=90725b3c8a) | Jun 18, 2020 |
| Elo TouchS... | ESY1XDX                     | [64aded4262](https://linux-hardware.org/?probe=64aded4262) | Jun 09, 2020 |
| HP            | 0AA8h                       | [2f692488e5](https://linux-hardware.org/?probe=2f692488e5) | Jun 05, 2020 |
| HP            | 0AA8h                       | [1ee6fa5fb7](https://linux-hardware.org/?probe=1ee6fa5fb7) | Jun 03, 2020 |
| HP            | 0AA8h                       | [3226f7a8da](https://linux-hardware.org/?probe=3226f7a8da) | Jun 03, 2020 |
| Elo TouchS... | ESY1XDX                     | [467adf2413](https://linux-hardware.org/?probe=467adf2413) | Jun 01, 2020 |
| Gigabyte      | 970A-UD3P                   | [6661e20292](https://linux-hardware.org/?probe=6661e20292) | May 28, 2020 |
| Gigabyte      | GA-MA790FX-DS5              | [bc3ed232f3](https://linux-hardware.org/?probe=bc3ed232f3) | May 28, 2020 |
| Olidata       | Unknown                     | [4d13b52bae](https://linux-hardware.org/?probe=4d13b52bae) | May 23, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [f170547556](https://linux-hardware.org/?probe=f170547556) | May 16, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [6f3a5a041d](https://linux-hardware.org/?probe=6f3a5a041d) | May 08, 2020 |
| Intel         | D54250WYK H13922-304        | [cc19077417](https://linux-hardware.org/?probe=cc19077417) | May 01, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [d6abc4c56c](https://linux-hardware.org/?probe=d6abc4c56c) | Apr 29, 2020 |
| ECS           | A740GM-M                    | [8af834c918](https://linux-hardware.org/?probe=8af834c918) | Apr 28, 2020 |
| Intel         | DN2820FYK H24582-204        | [77cf46ddde](https://linux-hardware.org/?probe=77cf46ddde) | Apr 06, 2020 |
| ECS           | A780GM-A                    | [3530b26663](https://linux-hardware.org/?probe=3530b26663) | Mar 30, 2020 |
| ASRock        | A320M-HDV R4.0              | [ab20239127](https://linux-hardware.org/?probe=ab20239127) | Feb 09, 2020 |
| ECS           | A960M-MV                    | [b5991a8181](https://linux-hardware.org/?probe=b5991a8181) | Jan 13, 2020 |
| Gigabyte      | G41MT-S2                    | [1b60792885](https://linux-hardware.org/?probe=1b60792885) | Nov 12, 2019 |
| ASUSTek       | M5A99X EVO                  | [a0de23ca8b](https://linux-hardware.org/?probe=a0de23ca8b) | Oct 21, 2019 |
| Intel         | DG31PR AAD97573-204         | [3ca8dab2bd](https://linux-hardware.org/?probe=3ca8dab2bd) | Oct 14, 2019 |
| ASUSTek       | H81M-A                      | [dbb29527ff](https://linux-hardware.org/?probe=dbb29527ff) | Oct 08, 2019 |
| ASUSTek       | H81M-A                      | [3337b6ddbf](https://linux-hardware.org/?probe=3337b6ddbf) | Oct 08, 2019 |
| ASUSTek       | F1A75-M LE                  | [711b77b300](https://linux-hardware.org/?probe=711b77b300) | Sep 28, 2019 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [e8a0b17de8](https://linux-hardware.org/?probe=e8a0b17de8) | Sep 13, 2019 |
| ASUSTek       | B75M-A                      | [58ec049231](https://linux-hardware.org/?probe=58ec049231) | Sep 04, 2019 |
| ASUSTek       | P5QC                        | [441e7f2005](https://linux-hardware.org/?probe=441e7f2005) | Aug 19, 2019 |
| ASUSTek       | P5QC                        | [68e31b6013](https://linux-hardware.org/?probe=68e31b6013) | Aug 19, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [017c004a48](https://linux-hardware.org/?probe=017c004a48) | Aug 12, 2019 |
| ASUSTek       | F1A55-M LX                  | [db521911e3](https://linux-hardware.org/?probe=db521911e3) | Aug 06, 2019 |
| ECS           | A960M-MV                    | [4a3c832524](https://linux-hardware.org/?probe=4a3c832524) | Aug 05, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | [7875ecd5a5](https://linux-hardware.org/?probe=7875ecd5a5) | Jul 17, 2019 |
| MSI           | X399 SLI PLUS               | [db1a79ac69](https://linux-hardware.org/?probe=db1a79ac69) | Jun 29, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | [dc8d42d5d1](https://linux-hardware.org/?probe=dc8d42d5d1) | Jun 15, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | [b189962fa8](https://linux-hardware.org/?probe=b189962fa8) | Jun 14, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | [3166cd0be4](https://linux-hardware.org/?probe=3166cd0be4) | Jun 14, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | [b08781392f](https://linux-hardware.org/?probe=b08781392f) | Jun 13, 2019 |
| TPV-INVENT... | 2AC6 A01                    | [461345008c](https://linux-hardware.org/?probe=461345008c) | Jun 10, 2019 |
| TPV-INVENT... | 2AC6 A01                    | [4421365140](https://linux-hardware.org/?probe=4421365140) | Jun 10, 2019 |
| HP            | 0AA8h                       | [6d02866e6c](https://linux-hardware.org/?probe=6d02866e6c) | Jun 05, 2019 |
| Gigabyte      | Z77X-UD5H                   | [09ccaf8ccf](https://linux-hardware.org/?probe=09ccaf8ccf) | Jun 03, 2019 |
| MSI           | B250M GAMING PRO            | [a935e6e9c7](https://linux-hardware.org/?probe=a935e6e9c7) | May 27, 2019 |
| ASUSTek       | P6T DELUXE V2               | [d1f1be1b36](https://linux-hardware.org/?probe=d1f1be1b36) | May 24, 2019 |
| ASUSTek       | P6T DELUXE V2               | [77f0aad272](https://linux-hardware.org/?probe=77f0aad272) | May 24, 2019 |
| HP            | 0AA8h                       | [f2fbc75122](https://linux-hardware.org/?probe=f2fbc75122) | May 16, 2019 |
| MSI           | H61M-P31/W8                 | [915fd7548f](https://linux-hardware.org/?probe=915fd7548f) | May 13, 2019 |
| HP            | 0AA8h                       | [f0d1f05c8e](https://linux-hardware.org/?probe=f0d1f05c8e) | May 10, 2019 |
| ECS           | A780LM-M                    | [ca438dd2a7](https://linux-hardware.org/?probe=ca438dd2a7) | May 08, 2019 |
| Gigabyte      | A320M-S2H                   | [b4d5cdee78](https://linux-hardware.org/?probe=b4d5cdee78) | May 07, 2019 |
| Gigabyte      | EP45-DS3R                   | [8c9b60b665](https://linux-hardware.org/?probe=8c9b60b665) | May 01, 2019 |
| Dell          | 0GXM1W A02                  | [3841c32f4a](https://linux-hardware.org/?probe=3841c32f4a) | May 01, 2019 |
| Dell          | 0GXM1W A02                  | [e9c14efd74](https://linux-hardware.org/?probe=e9c14efd74) | Apr 30, 2019 |
| Pegatron      | 2AA1h                       | [df47c88db6](https://linux-hardware.org/?probe=df47c88db6) | Apr 23, 2019 |
| Pegatron      | 2AA1h                       | [70922676a8](https://linux-hardware.org/?probe=70922676a8) | Apr 23, 2019 |
| Pegatron      | 2AA1h                       | [07c7ac4546](https://linux-hardware.org/?probe=07c7ac4546) | Apr 23, 2019 |
| MSI           | A58M-E33                    | [987015c03b](https://linux-hardware.org/?probe=987015c03b) | Apr 18, 2019 |
| HP            | 0B4Ch D                     | [8dc7a1b1e8](https://linux-hardware.org/?probe=8dc7a1b1e8) | Feb 14, 2019 |
| Quanta        | 2AC7 011                    | [7a9d5af1ce](https://linux-hardware.org/?probe=7a9d5af1ce) | Jan 27, 2019 |
| Quanta        | 2AC7 011                    | [a2533c8043](https://linux-hardware.org/?probe=a2533c8043) | Jan 27, 2019 |
| ASUSTek       | F2A85-M LE                  | [efbf81762c](https://linux-hardware.org/?probe=efbf81762c) | Jan 09, 2019 |
| ASUSTek       | B85-PRO GAMER               | [09848aacf0](https://linux-hardware.org/?probe=09848aacf0) | Dec 26, 2018 |
| ASUSTek       | B85-PRO GAMER               | [7f0c38474e](https://linux-hardware.org/?probe=7f0c38474e) | Oct 29, 2018 |
| ASUSTek       | P5KC                        | [8ee7c3b1f4](https://linux-hardware.org/?probe=8ee7c3b1f4) | Sep 23, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 24       | 8.14%   |
| Ubuntu 18.04        | 19       | 6.44%   |
| Ubuntu 22.04        | 15       | 5.08%   |
| Arch Rolling        | 11       | 3.73%   |
| Arch                | 10       | 3.39%   |
| Zorin 16            | 9        | 3.05%   |
| Pop!_OS 22.04       | 8        | 2.71%   |
| OpenMandriva 4.2    | 8        | 2.71%   |
| Ubuntu 19.04        | 7        | 2.37%   |
| OpenMandriva 4.3    | 7        | 2.37%   |
| Manjaro             | 7        | 2.37%   |
| Linux Mint 21.2     | 6        | 2.03%   |
| Linux Mint 21.1     | 6        | 2.03%   |
| Linux Mint 20.1     | 6        | 2.03%   |
| Zorin 15            | 5        | 1.69%   |
| Pop!_OS 20.10       | 5        | 1.69%   |
| OpenMandriva 23.01  | 5        | 1.69%   |
| KDE neon 20.04      | 5        | 1.69%   |
| Fedora 38           | 5        | 1.69%   |
| Debian Testing      | 5        | 1.69%   |
| Ubuntu 21.04        | 4        | 1.36%   |
| OpenMandriva 23.03  | 4        | 1.36%   |
| Fedora 34           | 4        | 1.36%   |
| Debian 11           | 4        | 1.36%   |
| Ubuntu 22.10        | 3        | 1.02%   |
| Ubuntu 21.10        | 3        | 1.02%   |
| Ubuntu 19.10        | 3        | 1.02%   |
| Linux Mint 20       | 3        | 1.02%   |
| Linux Mint 19.3     | 3        | 1.02%   |
| Kubuntu 20.04       | 3        | 1.02%   |
| Fedora 37           | 3        | 1.02%   |
| Fedora 35           | 3        | 1.02%   |
| Fedora 33           | 3        | 1.02%   |
| Fedora 32           | 3        | 1.02%   |
| EndeavourOS Rolling | 3        | 1.02%   |
| Debian 12           | 3        | 1.02%   |
| Ubuntu 23.04        | 2        | 0.68%   |
| Ubuntu 20.10        | 2        | 0.68%   |
| Ubuntu 18.10        | 2        | 0.68%   |
| Ubuntu 16.04        | 2        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 85       | 30.25%  |
| Linux Mint       | 29       | 10.32%  |
| OpenMandriva     | 27       | 9.61%   |
| Fedora           | 22       | 7.83%   |
| Arch             | 18       | 6.41%   |
| Pop!_OS          | 16       | 5.69%   |
| Zorin            | 15       | 5.34%   |
| Debian           | 13       | 4.63%   |
| Manjaro          | 10       | 3.56%   |
| Kubuntu          | 7        | 2.49%   |
| KDE neon         | 7        | 2.49%   |
| Nobara           | 3        | 1.07%   |
| EndeavourOS      | 3        | 1.07%   |
| Ubuntu MATE      | 2        | 0.71%   |
| openSUSE         | 2        | 0.71%   |
| Garuda Linux     | 2        | 0.71%   |
| Elementary       | 2        | 0.71%   |
| ArcoLinux        | 2        | 0.71%   |
| Void Linux       | 1        | 0.36%   |
| Ubuntu Budgie    | 1        | 0.36%   |
| ROSA             | 1        | 0.36%   |
| org.kde.Platform | 1        | 0.36%   |
| MX               | 1        | 0.36%   |
| Lubuntu          | 1        | 0.36%   |
| Loc OS           | 1        | 0.36%   |
| LMDE             | 1        | 0.36%   |
| LinuxFX          | 1        | 0.36%   |
| Linux Lite       | 1        | 0.36%   |
| Kali             | 1        | 0.36%   |
| Gentoo           | 1        | 0.36%   |
| Endless          | 1        | 0.36%   |
| Clear Linux      | 1        | 0.36%   |
| ChimeraOS        | 1        | 0.36%   |
| blendOS          | 1        | 0.36%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 7        | 2.11%   |
| 5.10.14-desktop-1omv4002 | 7        | 2.11%   |
| 5.4.0-42-generic         | 6        | 1.81%   |
| 5.15.0-58-generic        | 6        | 1.81%   |
| 6.1.1-desktop-1omv2290   | 5        | 1.51%   |
| 6.2.6-desktop-1omv2390   | 4        | 1.21%   |
| 5.9.16-1-MANJARO         | 4        | 1.21%   |
| 5.0.0-13-generic         | 4        | 1.21%   |
| 5.4.0-77-generic         | 3        | 0.91%   |
| 5.4.0-33-generic         | 3        | 0.91%   |
| 5.4.0-26-generic         | 3        | 0.91%   |
| 5.15.0-82-generic        | 3        | 0.91%   |
| 5.11.0-7614-generic      | 3        | 0.91%   |
| 4.18.0-18-generic        | 3        | 0.91%   |
| 6.2.6-76060206-generic   | 2        | 0.6%    |
| 6.1.0-13-amd64           | 2        | 0.6%    |
| 5.8.0-59-generic         | 2        | 0.6%    |
| 5.8.0-48-generic         | 2        | 0.6%    |
| 5.4.0-89-generic         | 2        | 0.6%    |
| 5.4.0-74-generic         | 2        | 0.6%    |
| 5.4.0-70-generic         | 2        | 0.6%    |
| 5.4.0-65-generic         | 2        | 0.6%    |
| 5.4.0-52-generic         | 2        | 0.6%    |
| 5.4.0-47-generic         | 2        | 0.6%    |
| 5.4.0-29-generic         | 2        | 0.6%    |
| 5.4.0-124-generic        | 2        | 0.6%    |
| 5.4.0-117-generic        | 2        | 0.6%    |
| 5.3.0-53-generic         | 2        | 0.6%    |
| 5.19.0-46-generic        | 2        | 0.6%    |
| 5.18.10-76051810-generic | 2        | 0.6%    |
| 5.17.5-76051705-generic  | 2        | 0.6%    |
| 5.15.0-91-generic        | 2        | 0.6%    |
| 5.15.0-88-generic        | 2        | 0.6%    |
| 5.15.0-76-generic        | 2        | 0.6%    |
| 5.15.0-52-generic        | 2        | 0.6%    |
| 5.13.0-39-generic        | 2        | 0.6%    |
| 5.11.0-41-generic        | 2        | 0.6%    |
| 5.11.0-34-generic        | 2        | 0.6%    |
| 5.11.0-27-generic        | 2        | 0.6%    |
| 5.11.0-18-generic        | 2        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 40       | 12.66%  |
| 5.15.0  | 30       | 9.49%   |
| 5.11.0  | 15       | 4.75%   |
| 4.15.0  | 14       | 4.43%   |
| 5.8.0   | 11       | 3.48%   |
| 5.0.0   | 10       | 3.16%   |
| 4.18.0  | 10       | 3.16%   |
| 5.3.0   | 9        | 2.85%   |
| 5.19.0  | 9        | 2.85%   |
| 5.13.0  | 9        | 2.85%   |
| 6.2.6   | 7        | 2.22%   |
| 6.2.0   | 7        | 2.22%   |
| 5.16.7  | 7        | 2.22%   |
| 5.10.14 | 7        | 2.22%   |
| 6.1.1   | 6        | 1.9%    |
| 5.9.16  | 5        | 1.58%   |
| 6.1.0   | 4        | 1.27%   |
| 6.6.2   | 3        | 0.95%   |
| 6.1.11  | 3        | 0.95%   |
| 5.18.10 | 3        | 0.95%   |
| 5.17.5  | 3        | 0.95%   |
| 5.10.0  | 3        | 0.95%   |
| 6.4.4   | 2        | 0.63%   |
| 6.4.3   | 2        | 0.63%   |
| 6.4.12  | 2        | 0.63%   |
| 6.3.8   | 2        | 0.63%   |
| 6.2.9   | 2        | 0.63%   |
| 5.8.12  | 2        | 0.63%   |
| 5.16.16 | 2        | 0.63%   |
| 5.14.0  | 2        | 0.63%   |
| 5.13.13 | 2        | 0.63%   |
| 5.13.12 | 2        | 0.63%   |
| 6.6.8   | 1        | 0.32%   |
| 6.6.7   | 1        | 0.32%   |
| 6.6.6   | 1        | 0.32%   |
| 6.6.4   | 1        | 0.32%   |
| 6.6.12  | 1        | 0.32%   |
| 6.5.7   | 1        | 0.32%   |
| 6.5.6   | 1        | 0.32%   |
| 6.5.2   | 1        | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 41       | 13.4%   |
| 5.15    | 34       | 11.11%  |
| 6.2     | 19       | 6.21%   |
| 5.11    | 18       | 5.88%   |
| 5.13    | 17       | 5.56%   |
| 5.10    | 17       | 5.56%   |
| 6.1     | 16       | 5.23%   |
| 5.19    | 14       | 4.58%   |
| 4.15    | 14       | 4.58%   |
| 5.8     | 13       | 4.25%   |
| 5.3     | 10       | 3.27%   |
| 5.16    | 10       | 3.27%   |
| 5.0     | 10       | 3.27%   |
| 4.18    | 10       | 3.27%   |
| 6.4     | 9        | 2.94%   |
| 6.6     | 7        | 2.29%   |
| 5.9     | 7        | 2.29%   |
| 6.5     | 6        | 1.96%   |
| 5.17    | 6        | 1.96%   |
| 5.14    | 6        | 1.96%   |
| 6.3     | 5        | 1.63%   |
| 5.18    | 5        | 1.63%   |
| 5.12    | 3        | 0.98%   |
| 6.0     | 2        | 0.65%   |
| 5.7     | 2        | 0.65%   |
| 5.6     | 2        | 0.65%   |
| 4.19    | 2        | 0.65%   |
| 4.9     | 1        | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 268      | 98.89%  |
| i686   | 3        | 1.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 113      | 40.36%  |
| KDE5       | 60       | 21.43%  |
| Unknown    | 34       | 12.14%  |
| X-Cinnamon | 24       | 8.57%   |
| XFCE       | 21       | 7.5%    |
| KDE        | 10       | 3.57%   |
| LXDE       | 4        | 1.43%   |
| MATE       | 3        | 1.07%   |
| xmonad     | 2        | 0.71%   |
| Pantheon   | 2        | 0.71%   |
| Cinnamon   | 2        | 0.71%   |
| Budgie     | 2        | 0.71%   |
| KDE4       | 1        | 0.36%   |
| i3         | 1        | 0.36%   |
| Deepin     | 1        | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 201      | 72.56%  |
| Wayland | 45       | 16.25%  |
| Unknown | 28       | 10.11%  |
| Tty     | 3        | 1.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 161      | 56.49%  |
| SDDM    | 46       | 16.14%  |
| GDM     | 28       | 9.82%   |
| LightDM | 21       | 7.37%   |
| GDM3    | 19       | 6.67%   |
| TDM     | 6        | 2.11%   |
| LXDM    | 2        | 0.7%    |
| LY-DM   | 1        | 0.35%   |
| KDM     | 1        | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang     | Desktops | Percent |
|----------|----------|---------|
| es_CL    | 147      | 52.5%   |
| en_US    | 65       | 23.21%  |
| Unknown  | 35       | 12.5%   |
| es_ES    | 16       | 5.71%   |
| es_MX    | 6        | 2.14%   |
| en_GB    | 5        | 1.79%   |
| C        | 3        | 1.07%   |
| pt_BR    | 1        | 0.36%   |
| latam_IT | 1        | 0.36%   |
| es_UY    | 1        | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 169      | 60.36%  |
| EFI  | 111      | 39.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 201      | 71.53%  |
| Btrfs   | 35       | 12.46%  |
| Overlay | 24       | 8.54%   |
| Unknown | 7        | 2.49%   |
| Tmpfs   | 6        | 2.14%   |
| Ext2    | 3        | 1.07%   |
| Zfs     | 2        | 0.71%   |
| Xfs     | 2        | 0.71%   |
| Jfs     | 1        | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 165      | 58.3%   |
| GPT     | 90       | 31.8%   |
| MBR     | 28       | 9.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 231      | 83.09%  |
| Yes       | 47       | 16.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 177      | 63.21%  |
| Yes       | 103      | 36.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 79       | 29.15%  |
| MSI                                  | 46       | 16.97%  |
| Gigabyte Technology                  | 26       | 9.59%   |
| Hewlett-Packard                      | 21       | 7.75%   |
| Intel                                | 18       | 6.64%   |
| ECS                                  | 14       | 5.17%   |
| Dell                                 | 10       | 3.69%   |
| ASRock                               | 9        | 3.32%   |
| Unknown                              | 7        | 2.58%   |
| Lenovo                               | 5        | 1.85%   |
| Huanan                               | 5        | 1.85%   |
| Pegatron                             | 4        | 1.48%   |
| TPV-INVENTA                          | 2        | 0.74%   |
| MACHINIST                            | 2        | 0.74%   |
| HC                                   | 2        | 0.74%   |
| Foxconn                              | 2        | 0.74%   |
| eMachines                            | 2        | 0.74%   |
| WZA300S2R120                         | 1        | 0.37%   |
| ViewSonic                            | 1        | 0.37%   |
| SZMZ                                 | 1        | 0.37%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.37%   |
| R-StyleComputers                     | 1        | 0.37%   |
| Quanta                               | 1        | 0.37%   |
| PCPartner                            | 1        | 0.37%   |
| Olidata                              | 1        | 0.37%   |
| Nvidia                               | 1        | 0.37%   |
| JGINYUE                              | 1        | 0.37%   |
| IBM                                  | 1        | 0.37%   |
| Elo TouchSystems                     | 1        | 0.37%   |
| Colorful Technology                  | 1        | 0.37%   |
| BESSTAR Tech                         | 1        | 0.37%   |
| Apple                                | 1        | 0.37%   |
| ANGXUN                               | 1        | 0.37%   |
| AMI                                  | 1        | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 8        | 2.95%   |
| MSI MS-7817                                | 6        | 2.21%   |
| ASUS All Series                            | 6        | 2.21%   |
| ASUS PRIME B450M-A                         | 5        | 1.85%   |
| ASUS PRIME A320M-K                         | 5        | 1.85%   |
| MSI MS-7A34                                | 3        | 1.11%   |
| MSI MS-7788                                | 3        | 1.11%   |
| HP Compaq Pro 4300 SFF PC                  | 3        | 1.11%   |
| ASUS TUF Gaming B450M-PLUS II              | 3        | 1.11%   |
| ASUS PRIME H410M-E                         | 3        | 1.11%   |
| MSI Pro 3000/3080                          | 2        | 0.74%   |
| MSI MS-7A65                                | 2        | 0.74%   |
| MSI MS-7A15                                | 2        | 0.74%   |
| MSI MS-7816                                | 2        | 0.74%   |
| MSI MS-7693                                | 2        | 0.74%   |
| MSI MS-7360                                | 2        | 0.74%   |
| Intel X79M-S                               | 2        | 0.74%   |
| HP Compaq Pro 6300 SFF                     | 2        | 0.74%   |
| HC HCAR357-MI                              | 2        | 0.74%   |
| Gigabyte B550 AORUS ELITE V2               | 2        | 0.74%   |
| Gigabyte B450M DS3H V2                     | 2        | 0.74%   |
| Gigabyte B450 AORUS PRO WIFI               | 2        | 0.74%   |
| Gigabyte A320M-S2H V2                      | 2        | 0.74%   |
| ECS MCP61M-M3                              | 2        | 0.74%   |
| ECS A960M-MV                               | 2        | 0.74%   |
| ECS A740GM-M                               | 2        | 0.74%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 0.74%   |
| ASUS TUF Gaming B460M-PLUS                 | 2        | 0.74%   |
| ASUS SABERTOOTH 990FX R2.0                 | 2        | 0.74%   |
| ASUS M5A99X EVO                            | 2        | 0.74%   |
| ASUS M5A97 R2.0                            | 2        | 0.74%   |
| ASUS H110M-R                               | 2        | 0.74%   |
| ASUS F2A55-M LK2                           | 2        | 0.74%   |
| WZA300S2R120 SA300-D4                      | 1        | 0.37%   |
| ViewSonic VOT132                           | 1        | 0.37%   |
| TPV-INVENTA Pro 1005 Series All-in-One PC  | 1        | 0.37%   |
| TPV-INVENTA CQ1-3130LA                     | 1        | 0.37%   |
| SZMZ X99M-G2                               | 1        | 0.37%   |
| Shenzhen Meigao Electronic Equipment F7BSC | 1        | 0.37%   |
| R-StyleComputers ALICON AI2S-A21 00.69     | 1        | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 22       | 8.12%   |
| ASUS TUF              | 15       | 5.54%   |
| HP Compaq             | 10       | 3.69%   |
| Unknown               | 8        | 2.95%   |
| MSI MS-7817           | 6        | 2.21%   |
| ASUS All              | 6        | 2.21%   |
| Lenovo ThinkCentre    | 5        | 1.85%   |
| Dell OptiPlex         | 5        | 1.85%   |
| ASUS ROG              | 5        | 1.85%   |
| ASUS M5A78L-M         | 4        | 1.48%   |
| MSI MS-7A34           | 3        | 1.11%   |
| MSI MS-7788           | 3        | 1.11%   |
| Huanan X79            | 3        | 1.11%   |
| HP ProDesk            | 3        | 1.11%   |
| HP EliteDesk          | 3        | 1.11%   |
| Gigabyte B450M        | 3        | 1.11%   |
| Gigabyte A320M-S2H    | 3        | 1.11%   |
| Dell Precision        | 3        | 1.11%   |
| ASUS SABERTOOTH       | 3        | 1.11%   |
| MSI Pro               | 2        | 0.74%   |
| MSI MS-7A65           | 2        | 0.74%   |
| MSI MS-7A15           | 2        | 0.74%   |
| MSI MS-7816           | 2        | 0.74%   |
| MSI MS-7693           | 2        | 0.74%   |
| MSI MS-7360           | 2        | 0.74%   |
| Intel X99             | 2        | 0.74%   |
| Intel X79M-S          | 2        | 0.74%   |
| Intel D54250WYK       | 2        | 0.74%   |
| HC HCAR357-MI         | 2        | 0.74%   |
| Gigabyte B550         | 2        | 0.74%   |
| Gigabyte B450         | 2        | 0.74%   |
| ECS MCP61M-M3         | 2        | 0.74%   |
| ECS A960M-MV          | 2        | 0.74%   |
| ECS A740GM-M          | 2        | 0.74%   |
| ASUS M5A99X           | 2        | 0.74%   |
| ASUS M5A97            | 2        | 0.74%   |
| ASUS H110M-R          | 2        | 0.74%   |
| ASUS F2A55-M          | 2        | 0.74%   |
| WZA300S2R120 SA300-D4 | 1        | 0.37%   |
| ViewSonic VOT132      | 1        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 35       | 12.92%  |
| 2012 | 29       | 10.7%   |
| 2018 | 28       | 10.33%  |
| 2013 | 22       | 8.12%   |
| 2014 | 19       | 7.01%   |
| 2019 | 17       | 6.27%   |
| 2017 | 16       | 5.9%    |
| 2007 | 16       | 5.9%    |
| 2011 | 15       | 5.54%   |
| 2021 | 11       | 4.06%   |
| 2016 | 11       | 4.06%   |
| 2010 | 11       | 4.06%   |
| 2008 | 11       | 4.06%   |
| 2022 | 10       | 3.69%   |
| 2009 | 9        | 3.32%   |
| 2023 | 4        | 1.48%   |
| 2015 | 4        | 1.48%   |
| 2006 | 2        | 0.74%   |
| 2005 | 1        | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 271      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 267      | 97.8%   |
| Enabled  | 6        | 2.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 271      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 65       | 23.64%  |
| 16.01-24.0  | 58       | 21.09%  |
| 32.01-64.0  | 42       | 15.27%  |
| 3.01-4.0    | 42       | 15.27%  |
| 4.01-8.0    | 41       | 14.91%  |
| 1.01-2.0    | 11       | 4%      |
| 24.01-32.0  | 8        | 2.91%   |
| 2.01-3.0    | 4        | 1.45%   |
| 64.01-256.0 | 4        | 1.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 98       | 32.78%  |
| 2.01-3.0   | 82       | 27.42%  |
| 4.01-8.0   | 45       | 15.05%  |
| 3.01-4.0   | 45       | 15.05%  |
| 8.01-16.0  | 17       | 5.69%   |
| 0.51-1.0   | 9        | 3.01%   |
| 0.01-0.5   | 2        | 0.67%   |
| 16.01-24.0 | 1        | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 106      | 37.59%  |
| 2      | 87       | 30.85%  |
| 3      | 45       | 15.96%  |
| 4      | 28       | 9.93%   |
| 5      | 11       | 3.9%    |
| 7      | 2        | 0.71%   |
| 0      | 2        | 0.71%   |
| 6      | 1        | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 62.87%  |
| Yes       | 101      | 37.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 268      | 98.89%  |
| No        | 3        | 1.11%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 145      | 52.92%  |
| Yes       | 129      | 47.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 185      | 66.79%  |
| Yes       | 92       | 33.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Chile   | 271      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Santiago            | 95       | 33.1%   |
| Viña del Mar       | 11       | 3.83%   |
| Concepción         | 10       | 3.48%   |
| Maipu               | 9        | 3.14%   |
| Las Condes          | 9        | 3.14%   |
| Puente Alto         | 8        | 2.79%   |
| Antofagasta         | 8        | 2.79%   |
| Valparaíso         | 7        | 2.44%   |
| Port Montt          | 7        | 2.44%   |
| Nunoa               | 7        | 2.44%   |
| Valdivia            | 6        | 2.09%   |
| La Florida          | 6        | 2.09%   |
| Temuco              | 5        | 1.74%   |
| Providencia         | 5        | 1.74%   |
| Central             | 5        | 1.74%   |
| San Miguel          | 4        | 1.39%   |
| Osorno              | 4        | 1.39%   |
| La Serena           | 4        | 1.39%   |
| Chillan             | 4        | 1.39%   |
| Quilpué            | 3        | 1.05%   |
| Penalolen           | 3        | 1.05%   |
| Melipilla           | 3        | 1.05%   |
| El Bosque           | 3        | 1.05%   |
| Coquimbo            | 3        | 1.05%   |
| Arica               | 3        | 1.05%   |
| Vitacura            | 2        | 0.7%    |
| Vallenar            | 2        | 0.7%    |
| Tome                | 2        | 0.7%    |
| Talca               | 2        | 0.7%    |
| San Pedro de la Paz | 2        | 0.7%    |
| Recoleta            | 2        | 0.7%    |
| Rancagua            | 2        | 0.7%    |
| Quilicura           | 2        | 0.7%    |
| Los Ángeles        | 2        | 0.7%    |
| La Granja           | 2        | 0.7%    |
| Hualpen             | 2        | 0.7%    |
| Coronel             | 2        | 0.7%    |
| Colina              | 2        | 0.7%    |
| Villa Alemana       | 1        | 0.35%   |
| Villa Alegre        | 1        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 109      | 186    | 21.89%  |
| Seagate                     | 84       | 124    | 16.87%  |
| Kingston                    | 59       | 95     | 11.85%  |
| Toshiba                     | 50       | 61     | 10.04%  |
| Crucial                     | 32       | 41     | 6.43%   |
| SanDisk                     | 22       | 33     | 4.42%   |
| Samsung Electronics         | 22       | 39     | 4.42%   |
| Hitachi                     | 17       | 21     | 3.41%   |
| Silicon Motion              | 13       | 13     | 2.61%   |
| China                       | 10       | 13     | 2.01%   |
| Unknown                     | 6        | 7      | 1.2%    |
| XPG                         | 5        | 14     | 1%      |
| Micron/Crucial Technology   | 5        | 8      | 1%      |
| Maxtor                      | 5        | 7      | 1%      |
| Lexar                       | 5        | 5      | 1%      |
| Realtek Semiconductor       | 4        | 4      | 0.8%    |
| Kingston Technology Company | 4        | 5      | 0.8%    |
| Corsair                     | 4        | 9      | 0.8%    |
| XrayDisk                    | 3        | 3      | 0.6%    |
| Micron Technology           | 3        | 6      | 0.6%    |
| KingSpec                    | 3        | 3      | 0.6%    |
| A-DATA Technology           | 3        | 3      | 0.6%    |
| JMicron Technology          | 2        | 2      | 0.4%    |
| Gigabyte Technology         | 2        | 4      | 0.4%    |
| ZOTAC                       | 1        | 1      | 0.2%    |
| WALRAM                      | 1        | 2      | 0.2%    |
| USB3.0                      | 1        | 1      | 0.2%    |
| Transcend                   | 1        | 1      | 0.2%    |
| StoreJet                    | 1        | 1      | 0.2%    |
| SK hynix                    | 1        | 1      | 0.2%    |
| Seagate Technology          | 1        | 1      | 0.2%    |
| SCY                         | 1        | 1      | 0.2%    |
| PNY                         | 1        | 1      | 0.2%    |
| Phison Electronics          | 1        | 1      | 0.2%    |
| Patriot                     | 1        | 1      | 0.2%    |
| OCZ                         | 1        | 2      | 0.2%    |
| NGFF                        | 1        | 1      | 0.2%    |
| Netac                       | 1        | 1      | 0.2%    |
| Mass                        | 1        | 1      | 0.2%    |
| LuminouTek                  | 1        | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                | 16       | 2.8%    |
| Toshiba HDWD110 1TB                                   | 15       | 2.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 14       | 2.45%   |
| Seagate ST500DM002-1BD142 500GB                       | 14       | 2.45%   |
| Kingston SA400S37240G 240GB SSD                       | 12       | 2.1%    |
| Kingston SA400S37120G 120GB SSD                       | 10       | 1.75%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 9        | 1.58%   |
| Kingston SA400S37480G 480GB SSD                       | 9        | 1.58%   |
| WDC WD5000AAKX-001CA0 500GB                           | 6        | 1.05%   |
| Toshiba DT01ACA050 500GB                              | 6        | 1.05%   |
| Crucial CT500MX500SSD1 500GB                          | 6        | 1.05%   |
| Crucial CT480BX500SSD1 480GB                          | 6        | 1.05%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 5        | 0.88%   |
| WDC WD5000AAKX-00ERMA0 500GB                          | 5        | 0.88%   |
| Seagate ST3500418AS 500GB                             | 5        | 0.88%   |
| Seagate ST1000DM010-2EP102 1TB                        | 5        | 0.88%   |
| SanDisk NVMe SSD Drive 1TB                            | 5        | 0.88%   |
| Crucial CT240BX500SSD1 240GB                          | 5        | 0.88%   |
| XPG GAMMIX S11 Pro 256GB                              | 4        | 0.7%    |
| WDC WD10EZEX-00BN5A0 1TB                              | 4        | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB | 4        | 0.7%    |
| Seagate ST3320418AS 320GB                             | 4        | 0.7%    |
| Sandisk WD_BLACK SN770 1TB                            | 4        | 0.7%    |
| Kingston SUV400S37240G 240GB SSD                      | 4        | 0.7%    |
| Kingston SUV400S37120G 120GB SSD                      | 4        | 0.7%    |
| Hitachi HDS721050CLA362 500GB                         | 4        | 0.7%    |
| XPG SPECTRIX S40G 1TB                                 | 3        | 0.53%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 3        | 0.53%   |
| Seagate ST9640320AS 640GB                             | 3        | 0.53%   |
| Seagate ST500LT012-9WS142 500GB                       | 3        | 0.53%   |
| Seagate ST500LT012-1DG142 500GB                       | 3        | 0.53%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3        | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB                        | 3        | 0.53%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 3        | 0.53%   |
| SanDisk NVMe SSD Drive 500GB                          | 3        | 0.53%   |
| Lexar 128GB SSD                                       | 3        | 0.53%   |
| Kingston SA400M8120G 120GB SSD                        | 3        | 0.53%   |
| Hitachi HDS721032CLA362 320GB                         | 3        | 0.53%   |
| Crucial CT250MX500SSD1 250GB                          | 3        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB                           | 3        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 83       | 126    | 33.2%   |
| Seagate             | 83       | 123    | 33.2%   |
| Toshiba             | 50       | 61     | 20%     |
| Hitachi             | 17       | 21     | 6.8%    |
| Samsung Electronics | 6        | 8      | 2.4%    |
| Maxtor              | 4        | 6      | 1.6%    |
| Unknown             | 2        | 2      | 0.8%    |
| StoreJet            | 1        | 1      | 0.4%    |
| JMicron Technology  | 1        | 1      | 0.4%    |
| HGST                | 1        | 1      | 0.4%    |
| ASMT                | 1        | 1      | 0.4%    |
| Apple               | 1        | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 52       | 77     | 29.71%  |
| WDC                 | 35       | 50     | 20%     |
| Crucial             | 32       | 40     | 18.29%  |
| Samsung Electronics | 11       | 20     | 6.29%   |
| China               | 10       | 13     | 5.71%   |
| Lexar               | 5        | 5      | 2.86%   |
| Corsair             | 4        | 9      | 2.29%   |
| KingSpec            | 3        | 3      | 1.71%   |
| XrayDisk            | 2        | 2      | 1.14%   |
| Micron Technology   | 2        | 2      | 1.14%   |
| Gigabyte Technology | 2        | 4      | 1.14%   |
| ZOTAC               | 1        | 1      | 0.57%   |
| WALRAM              | 1        | 1      | 0.57%   |
| USB3.0              | 1        | 1      | 0.57%   |
| SCY                 | 1        | 1      | 0.57%   |
| SanDisk             | 1        | 1      | 0.57%   |
| PNY                 | 1        | 1      | 0.57%   |
| Patriot             | 1        | 1      | 0.57%   |
| OCZ                 | 1        | 2      | 0.57%   |
| NGFF                | 1        | 1      | 0.57%   |
| Maxtor              | 1        | 1      | 0.57%   |
| LuminouTek          | 1        | 1      | 0.57%   |
| Intenso             | 1        | 1      | 0.57%   |
| FORESEE             | 1        | 1      | 0.57%   |
| BIWIN               | 1        | 1      | 0.57%   |
| ASMedia             | 1        | 2      | 0.57%   |
| A-DATA Technology   | 1        | 1      | 0.57%   |
| Unknown             | 1        | 1      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 187      | 352    | 44.74%  |
| SSD     | 147      | 244    | 35.17%  |
| NVMe    | 74       | 129    | 17.7%   |
| Unknown | 8        | 9      | 1.91%   |
| MMC     | 2        | 2      | 0.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 251      | 585    | 73.61%  |
| NVMe | 74       | 129    | 21.7%   |
| SAS  | 14       | 20     | 4.11%   |
| MMC  | 2        | 2      | 0.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 201      | 370    | 58.6%   |
| 0.51-1.0   | 95       | 153    | 27.7%   |
| 1.01-2.0   | 31       | 43     | 9.04%   |
| 3.01-4.0   | 7        | 8      | 2.04%   |
| 2.01-3.0   | 5        | 12     | 1.46%   |
| 4.01-10.0  | 4        | 10     | 1.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 63       | 21.58%  |
| 101-250        | 57       | 19.52%  |
| 501-1000       | 44       | 15.07%  |
| 1001-2000      | 32       | 10.96%  |
| More than 3000 | 28       | 9.59%   |
| 1-20           | 22       | 7.53%   |
| 2001-3000      | 15       | 5.14%   |
| 51-100         | 15       | 5.14%   |
| Unknown        | 9        | 3.08%   |
| 21-50          | 7        | 2.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 99       | 32.57%  |
| 21-50          | 58       | 19.08%  |
| 101-250        | 30       | 9.87%   |
| 51-100         | 26       | 8.55%   |
| 501-1000       | 25       | 8.22%   |
| 1001-2000      | 23       | 7.57%   |
| 251-500        | 18       | 5.92%   |
| More than 3000 | 9        | 2.96%   |
| Unknown        | 9        | 2.96%   |
| 2001-3000      | 6        | 1.97%   |
| 0              | 1        | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Desktops | Drives | Percent |
|--------------------------------------|----------|--------|---------|
| WDC WD1600BB-00GUC0 160GB            | 2        | 2      | 5%      |
| Seagate ST500DM002-1BD142 500GB      | 2        | 2      | 5%      |
| Seagate ST31000528AS 1TB             | 2        | 2      | 5%      |
| Kingston SKC400S371T 1TB SSD         | 2        | 11     | 5%      |
| Kingston SA400S37240G 240GB SSD      | 2        | 2      | 5%      |
| XrayDisk SSD 256GB                   | 1        | 1      | 2.5%    |
| XPG SPECTRIX S40G 1TB                | 1        | 1      | 2.5%    |
| WDC WD5000AAKX-083CA1 500GB          | 1        | 1      | 2.5%    |
| WDC WD5000AAKX-00ERMA0 500GB         | 1        | 1      | 2.5%    |
| WDC WD5000AAKX-001CA0 500GB          | 1        | 2      | 2.5%    |
| WDC WD20EARX-00PASB0 2TB             | 1        | 1      | 2.5%    |
| WDC WD10EARS-003BB1 1TB              | 1        | 1      | 2.5%    |
| WDC WD Blue SA510 2.5 1000GB SSD     | 1        | 1      | 2.5%    |
| Toshiba MK1652GSX 160GB              | 1        | 1      | 2.5%    |
| Toshiba DT01ACA100 1TB               | 1        | 1      | 2.5%    |
| Toshiba DT01ACA050 500GB             | 1        | 1      | 2.5%    |
| Seagate ST500LT012-9WS142 500GB      | 1        | 1      | 2.5%    |
| Seagate ST500LM000-1EJ162-SSHD 500GB | 1        | 1      | 2.5%    |
| Seagate ST3500418AS 500GB            | 1        | 1      | 2.5%    |
| Seagate ST2000DM001-1CH164 2TB       | 1        | 1      | 2.5%    |
| Samsung Electronics SSD 870 EVO 1TB  | 1        | 1      | 2.5%    |
| Samsung Electronics HD250HJ 250GB    | 1        | 2      | 2.5%    |
| Samsung Electronics HD081GJ 80GB     | 1        | 1      | 2.5%    |
| Maxtor 2B020H1 20GB                  | 1        | 1      | 2.5%    |
| Kingston SNV2S500G 500GB             | 1        | 1      | 2.5%    |
| Kingston SA400S37480G 480GB SSD      | 1        | 1      | 2.5%    |
| Kingston SA400S37120G 120GB SSD      | 1        | 1      | 2.5%    |
| Hitachi HTS547550A9E384 500GB        | 1        | 1      | 2.5%    |
| Hitachi HTS545050B9A300 500GB        | 1        | 1      | 2.5%    |
| Hitachi HTS545050A7E380 500GB        | 1        | 1      | 2.5%    |
| Hitachi HTS543232A7A384 320GB        | 1        | 1      | 2.5%    |
| Hitachi HDT721010SLA360 1TB          | 1        | 1      | 2.5%    |
| Hitachi HDS721050CLA660 500GB        | 1        | 1      | 2.5%    |
| Hitachi HDS721032CLA362 320GB        | 1        | 1      | 2.5%    |
| A-DATA Technology SX8100NP 1TB       | 1        | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 9      | 21.05%  |
| Seagate             | 8        | 8      | 21.05%  |
| Kingston            | 7        | 16     | 18.42%  |
| Hitachi             | 6        | 7      | 15.79%  |
| Toshiba             | 3        | 3      | 7.89%   |
| Samsung Electronics | 2        | 4      | 5.26%   |
| XrayDisk            | 1        | 1      | 2.63%   |
| XPG                 | 1        | 1      | 2.63%   |
| Maxtor              | 1        | 1      | 2.63%   |
| A-DATA Technology   | 1        | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 8      | 30.77%  |
| WDC                 | 7        | 8      | 26.92%  |
| Hitachi             | 6        | 7      | 23.08%  |
| Toshiba             | 3        | 3      | 11.54%  |
| Samsung Electronics | 1        | 3      | 3.85%   |
| Maxtor              | 1        | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 30     | 62.5%   |
| SSD  | 9        | 18     | 28.13%  |
| NVMe | 3        | 3      | 9.38%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Toshiba MQ01ABF050 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 183      | 458    | 59.03%  |
| Works    | 95       | 226    | 30.65%  |
| Malfunc  | 31       | 51     | 10%     |
| Failed   | 1        | 1      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 158      | 42.7%   |
| AMD                          | 100      | 27.03%  |
| SanDisk                      | 27       | 7.3%    |
| Silicon Motion               | 15       | 4.05%   |
| Kingston Technology Company  | 10       | 2.7%    |
| Realtek Semiconductor        | 9        | 2.43%   |
| JMicron Technology           | 9        | 2.43%   |
| Marvell Technology Group     | 8        | 2.16%   |
| Samsung Electronics          | 6        | 1.62%   |
| Nvidia                       | 6        | 1.62%   |
| Micron/Crucial Technology    | 6        | 1.62%   |
| ASMedia Technology           | 5        | 1.35%   |
| ADATA Technology             | 5        | 1.35%   |
| VIA Technologies             | 1        | 0.27%   |
| SK hynix                     | 1        | 0.27%   |
| Shenzhen Longsys Electronics | 1        | 0.27%   |
| Seagate Technology           | 1        | 0.27%   |
| Phison Electronics           | 1        | 0.27%   |
| Micron Technology            | 1        | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 52       | 10.97%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25       | 5.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 21       | 4.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 15       | 3.16%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 14       | 2.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 13       | 2.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13       | 2.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11       | 2.32%   |
| AMD 500 Series Chipset SATA Controller                                                  | 10       | 2.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 9        | 1.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9        | 1.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 1.69%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 8        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 1.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 1.69%   |
| AMD FCH SATA Controller D                                                               | 8        | 1.69%   |
| AMD 300 Series Chipset SATA Controller                                                  | 8        | 1.69%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 7        | 1.48%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 1.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 1.48%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 7        | 1.48%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 6        | 1.27%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.27%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 1.27%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 1.27%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6        | 1.27%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 5        | 1.05%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 5        | 1.05%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 1.05%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 5        | 1.05%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 5        | 1.05%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.05%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 1.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 0.84%   |
| Nvidia MCP61 IDE                                                                        | 4        | 0.84%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 0.84%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 4        | 0.84%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 210      | 57.69%  |
| NVMe | 74       | 20.33%  |
| IDE  | 69       | 18.96%  |
| RAID | 11       | 3.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 163      | 60.15%  |
| AMD    | 108      | 39.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4460 CPU @ 3.20GHz            | 6        | 2.16%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 5        | 1.8%    |
| AMD FX-8350 Eight-Core Processor            | 5        | 1.8%    |
| AMD FX-6300 Six-Core Processor              | 5        | 1.8%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 1.44%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 4        | 1.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 1.44%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 1.44%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 3        | 1.08%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 1.08%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 1.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.08%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.08%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 3        | 1.08%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.08%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 1.08%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.08%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 1.08%   |
| AMD E-450 APU with Radeon HD Graphics       | 3        | 1.08%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 3        | 1.08%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 2        | 0.72%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 2        | 0.72%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 2        | 0.72%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 2        | 0.72%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 2        | 0.72%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2        | 0.72%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 0.72%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 2        | 0.72%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 0.72%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.72%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.72%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 2        | 0.72%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 0.72%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 0.72%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 0.72%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 0.72%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 0.72%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2        | 0.72%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 2        | 0.72%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 2        | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 38       | 13.72%  |
| Intel Xeon              | 28       | 10.11%  |
| Intel Core i7           | 26       | 9.39%   |
| AMD Ryzen 5             | 26       | 9.39%   |
| Intel Core i3           | 20       | 7.22%   |
| AMD Ryzen 7             | 15       | 5.42%   |
| AMD FX                  | 14       | 5.05%   |
| Intel Core 2 Duo        | 10       | 3.61%   |
| AMD Ryzen 3             | 10       | 3.61%   |
| Intel Celeron           | 9        | 3.25%   |
| Other                   | 7        | 2.53%   |
| AMD Ryzen 9             | 7        | 2.53%   |
| AMD A6                  | 7        | 2.53%   |
| Intel Pentium           | 6        | 2.17%   |
| AMD Athlon              | 6        | 2.17%   |
| Intel Pentium Dual      | 5        | 1.81%   |
| Intel Core 2 Quad       | 3        | 1.08%   |
| AMD Phenom              | 3        | 1.08%   |
| AMD E                   | 3        | 1.08%   |
| AMD Athlon II X2        | 3        | 1.08%   |
| Intel Pentium Dual-Core | 2        | 0.72%   |
| Intel Pentium 4         | 2        | 0.72%   |
| Intel Core i9           | 2        | 0.72%   |
| Intel Core 2            | 2        | 0.72%   |
| Intel Atom              | 2        | 0.72%   |
| AMD Ryzen 5 PRO         | 2        | 0.72%   |
| AMD Phenom II X6        | 2        | 0.72%   |
| AMD Phenom II X4        | 2        | 0.72%   |
| AMD Athlon 64 X2        | 2        | 0.72%   |
| AMD A8                  | 2        | 0.72%   |
| AMD A10                 | 2        | 0.72%   |
| Intel Xeon Bronze       | 1        | 0.36%   |
| Intel Pentium Gold      | 1        | 0.36%   |
| Intel Genuine           | 1        | 0.36%   |
| AMD Ryzen Threadripper  | 1        | 0.36%   |
| AMD Phenom II X2        | 1        | 0.36%   |
| AMD Athlon X4           | 1        | 0.36%   |
| AMD Athlon II X4        | 1        | 0.36%   |
| AMD Athlon II           | 1        | 0.36%   |
| AMD A4                  | 1        | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 97       | 34.89%  |
| 2       | 72       | 25.9%   |
| 6       | 40       | 14.39%  |
| 8       | 32       | 11.51%  |
| 12      | 11       | 3.96%   |
| 1       | 9        | 3.24%   |
| 3       | 8        | 2.88%   |
| 10      | 5        | 1.8%    |
| 16      | 2        | 0.72%   |
| 14      | 1        | 0.36%   |
| Unknown | 1        | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 268      | 98.89%  |
| 2      | 3        | 1.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 162      | 59.56%  |
| 1       | 109      | 40.07%  |
| Unknown | 1        | 0.37%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 265      | 97.79%  |
| Unknown        | 4        | 1.48%   |
| 64-bit         | 1        | 0.37%   |
| 32-bit         | 1        | 0.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 95       | 32.87%  |
| 0x306c3    | 17       | 5.88%   |
| 0x306a9    | 12       | 4.15%   |
| 0x08701021 | 12       | 4.15%   |
| 0x206a7    | 9        | 3.11%   |
| 0x08108109 | 9        | 3.11%   |
| 0x06000852 | 9        | 3.11%   |
| 0x1067a    | 7        | 2.42%   |
| 0xa0653    | 6        | 2.08%   |
| 0x6fd      | 6        | 2.08%   |
| 0x906ea    | 5        | 1.73%   |
| 0x906e9    | 5        | 1.73%   |
| 0x10676    | 5        | 1.73%   |
| 0x0800820d | 5        | 1.73%   |
| 0x306f2    | 4        | 1.38%   |
| 0x206d7    | 4        | 1.38%   |
| 0x03000027 | 4        | 1.38%   |
| 0x010000c8 | 4        | 1.38%   |
| 0x6fb      | 3        | 1.04%   |
| 0x506e3    | 3        | 1.04%   |
| 0x306e4    | 3        | 1.04%   |
| 0x08108102 | 3        | 1.04%   |
| 0x06001119 | 3        | 1.04%   |
| 0x0600063e | 3        | 1.04%   |
| 0x40651    | 2        | 0.69%   |
| 0x30678    | 2        | 0.69%   |
| 0x20655    | 2        | 0.69%   |
| 0x106a5    | 2        | 0.69%   |
| 0x0a50000d | 2        | 0.69%   |
| 0x0a20120a | 2        | 0.69%   |
| 0x0a201016 | 2        | 0.69%   |
| 0x08701013 | 2        | 0.69%   |
| 0x08101016 | 2        | 0.69%   |
| 0x08001138 | 2        | 0.69%   |
| 0x06003106 | 2        | 0.69%   |
| 0x05000119 | 2        | 0.69%   |
| 0x010000bf | 2        | 0.69%   |
| 0x01000095 | 2        | 0.69%   |
| 0xf65      | 1        | 0.35%   |
| 0xf41      | 1        | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 36       | 13.09%  |
| IvyBridge        | 22       | 8%      |
| KabyLake         | 21       | 7.64%   |
| Zen+             | 19       | 6.91%   |
| Zen 2            | 19       | 6.91%   |
| Penryn           | 17       | 6.18%   |
| Piledriver       | 16       | 5.82%   |
| SandyBridge      | 15       | 5.45%   |
| Zen 3            | 13       | 4.73%   |
| K10              | 13       | 4.73%   |
| Core             | 13       | 4.73%   |
| Zen              | 11       | 4%      |
| CometLake        | 10       | 3.64%   |
| Skylake          | 6        | 2.18%   |
| Unknown          | 5        | 1.82%   |
| Westmere         | 4        | 1.45%   |
| Silvermont       | 4        | 1.45%   |
| K10 Llano        | 4        | 1.45%   |
| Steamroller      | 3        | 1.09%   |
| Nehalem          | 3        | 1.09%   |
| K8 Hammer        | 3        | 1.09%   |
| Bulldozer        | 3        | 1.09%   |
| Bobcat           | 3        | 1.09%   |
| NetBurst         | 2        | 0.73%   |
| Icelake          | 2        | 0.73%   |
| Alderlake Hybrid | 2        | 0.73%   |
| Jaguar           | 1        | 0.36%   |
| Gracemont        | 1        | 0.36%   |
| Goldmont plus    | 1        | 0.36%   |
| Excavator        | 1        | 0.36%   |
| Broadwell        | 1        | 0.36%   |
| Bonnell          | 1        | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 104      | 35.74%  |
| AMD                        | 104      | 35.74%  |
| Intel                      | 80       | 27.49%  |
| VIA Technologies           | 1        | 0.34%   |
| Matrox Electronics Systems | 1        | 0.34%   |
| ATI Technologies           | 1        | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 15       | 4.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 10       | 3.32%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 2.99%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 2.33%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 2.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 2.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 2.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 1.99%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 5        | 1.66%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 5        | 1.66%   |
| Intel HD Graphics 530                                                       | 5        | 1.66%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 1.66%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 1.66%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 5        | 1.66%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 1.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.33%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.33%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 4        | 1.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 1.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 1%      |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 1%      |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1%      |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3        | 1%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1%      |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1%      |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1%      |
| AMD Wrestler [Radeon HD 6320]                                               | 3        | 1%      |
| AMD Sumo [Radeon HD 6530D]                                                  | 3        | 1%      |
| AMD RS780L [Radeon 3000]                                                    | 3        | 1%      |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 3        | 1%      |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 1%      |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 1%      |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 1%      |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 3        | 1%      |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 96       | 35.04%  |
| 1 x AMD        | 89       | 32.48%  |
| 1 x Intel      | 70       | 25.55%  |
| AMD + Nvidia   | 7        | 2.55%   |
| 2 x AMD        | 6        | 2.19%   |
| Intel + Nvidia | 2        | 0.73%   |
| Intel + AMD    | 2        | 0.73%   |
| 1 x VIA        | 1        | 0.36%   |
| 1 x Matrox     | 1        | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 204      | 74.73%  |
| Proprietary | 60       | 21.98%  |
| Unknown     | 9        | 3.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 129      | 45.74%  |
| 1.01-2.0   | 42       | 14.89%  |
| 0.51-1.0   | 30       | 10.64%  |
| 0.01-0.5   | 24       | 8.51%   |
| 3.01-4.0   | 22       | 7.8%    |
| 7.01-8.0   | 10       | 3.55%   |
| 5.01-6.0   | 10       | 3.55%   |
| 8.01-16.0  | 10       | 3.55%   |
| 2.01-3.0   | 5        | 1.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 64       | 22.86%  |
| Goldstar             | 51       | 18.21%  |
| Hewlett-Packard      | 29       | 10.36%  |
| Dell                 | 16       | 5.71%   |
| AOC                  | 14       | 5%      |
| LG Electronics       | 12       | 4.29%   |
| Lenovo               | 10       | 3.57%   |
| Unknown              | 8        | 2.86%   |
| ViewSonic            | 7        | 2.5%    |
| SAC                  | 6        | 2.14%   |
| ___                  | 5        | 1.79%   |
| Sony                 | 5        | 1.79%   |
| KTC                  | 5        | 1.79%   |
| ASUSTek Computer     | 5        | 1.79%   |
| Plain Tree Systems   | 3        | 1.07%   |
| Philips              | 3        | 1.07%   |
| Packard Bell         | 3        | 1.07%   |
| MSI                  | 3        | 1.07%   |
| Mi                   | 3        | 1.07%   |
| Envision             | 3        | 1.07%   |
| Ancor Communications | 3        | 1.07%   |
| Acer                 | 3        | 1.07%   |
| Unknown (XXX)        | 2        | 0.71%   |
| Sharp                | 2        | 0.71%   |
| Hitachi              | 2        | 0.71%   |
| CHR                  | 2        | 0.71%   |
| Westinghouse         | 1        | 0.36%   |
| Wacom                | 1        | 0.36%   |
| SKY                  | 1        | 0.36%   |
| Pixio                | 1        | 0.36%   |
| NCS                  | 1        | 0.36%   |
| HUAWEI               | 1        | 0.36%   |
| HKC                  | 1        | 0.36%   |
| GDH                  | 1        | 0.36%   |
| Denver               | 1        | 0.36%   |
| BenQ                 | 1        | 0.36%   |
| Unknown              | 1        | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 8        | 2.68%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7        | 2.34%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5        | 1.67%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 5        | 1.67%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                 | 4        | 1.34%   |
| ___ LCDTV16 ___9000 1360x768                                          | 3        | 1%      |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 3        | 1%      |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3        | 1%      |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3        | 1%      |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch     | 3        | 1%      |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                    | 3        | 1%      |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 3        | 1%      |
| Goldstar MONITOR GSM59C6 1920x1080 509x286mm 23.0-inch                | 3        | 1%      |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 3        | 1%      |
| ___ LCD TV ___0101 1920x1080                                          | 2        | 0.67%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 2        | 0.67%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                    | 2        | 0.67%   |
| Unknown (XXX) Beyond TV XXX2851 2560x1440 1209x680mm 54.6-inch        | 2        | 0.67%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch     | 2        | 0.67%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 2        | 0.67%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 0.67%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 890x500mm 40.2-inch | 2        | 0.67%   |
| Philips 190P PHL0831 1280x1024 376x301mm 19.0-inch                    | 2        | 0.67%   |
| LG Electronics LCD Monitor 23MP55 1920x1080                           | 2        | 0.67%   |
| Lenovo LEN S22e-19 LEN61C9 1920x1080 476x268mm 21.5-inch              | 2        | 0.67%   |
| Lenovo G27q-20 LEN66C3 2560x1440 597x336mm 27.0-inch                  | 2        | 0.67%   |
| Hewlett-Packard Z23i HWP308F 1920x1080 509x286mm 23.0-inch            | 2        | 0.67%   |
| Hewlett-Packard w1907 HWP26A3 1440x900 408x255mm 18.9-inch            | 2        | 0.67%   |
| Hewlett-Packard TouchSmart HWP4211 1920x1080 509x286mm 23.0-inch      | 2        | 0.67%   |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch             | 2        | 0.67%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 2        | 0.67%   |
| Goldstar LG HDR QHD GSM5B96 2560x1440 700x390mm 31.5-inch             | 2        | 0.67%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 2        | 0.67%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                   | 2        | 0.67%   |
| CHR LCD Monitor CHR7511 1920x1080 519x324mm 24.1-inch                 | 2        | 0.67%   |
| ASUSTek Computer VP248QG AUS24A9 1920x1080 531x299mm 24.0-inch        | 2        | 0.67%   |
| AOC LE24H037 AOC2407 1920x1080 521x293mm 23.5-inch                    | 2        | 0.67%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 2        | 0.67%   |
| Westinghouse LCM-19v5 WDE1905 1280x1024 376x301mm 19.0-inch           | 1        | 0.33%   |
| Wacom Cintiq 21UX 2 WAC1022 1600x1200 432x324mm 21.3-inch             | 1        | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 112      | 41.33%  |
| 3840x2160 (4K)     | 25       | 9.23%   |
| 1366x768 (WXGA)    | 25       | 9.23%   |
| 1360x768           | 19       | 7.01%   |
| 1440x900 (WXGA+)   | 17       | 6.27%   |
| 1600x900 (HD+)     | 13       | 4.8%    |
| 2560x1440 (QHD)    | 11       | 4.06%   |
| 1280x1024 (SXGA)   | 11       | 4.06%   |
| 2560x1080          | 9        | 3.32%   |
| 1680x1050 (WSXGA+) | 6        | 2.21%   |
| Unknown            | 5        | 1.85%   |
| 3840x1080          | 4        | 1.48%   |
| 3440x1440          | 4        | 1.48%   |
| 1024x768 (XGA)     | 4        | 1.48%   |
| 5760x1080          | 1        | 0.37%   |
| 3840x1600          | 1        | 0.37%   |
| 3286x1080          | 1        | 0.37%   |
| 1600x1200          | 1        | 0.37%   |
| 1280x960           | 1        | 0.37%   |
| 1280x768           | 1        | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 42       | 15.11%  |
| 23      | 39       | 14.03%  |
| Unknown | 30       | 10.79%  |
| 18      | 23       | 8.27%   |
| 24      | 18       | 6.47%   |
| 27      | 17       | 6.12%   |
| 19      | 16       | 5.76%   |
| 34      | 13       | 4.68%   |
| 20      | 13       | 4.68%   |
| 15      | 10       | 3.6%    |
| 31      | 9        | 3.24%   |
| 17      | 9        | 3.24%   |
| 72      | 7        | 2.52%   |
| 32      | 7        | 2.52%   |
| 84      | 6        | 2.16%   |
| 54      | 4        | 1.44%   |
| 22      | 3        | 1.08%   |
| 40      | 2        | 0.72%   |
| 28      | 2        | 0.72%   |
| 65      | 1        | 0.36%   |
| 52      | 1        | 0.36%   |
| 49      | 1        | 0.36%   |
| 48      | 1        | 0.36%   |
| 46      | 1        | 0.36%   |
| 37      | 1        | 0.36%   |
| 14      | 1        | 0.36%   |
| 13      | 1        | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 86       | 31.97%  |
| 501-600     | 67       | 24.91%  |
| Unknown     | 30       | 11.15%  |
| 701-800     | 20       | 7.43%   |
| 301-350     | 17       | 6.32%   |
| 601-700     | 15       | 5.58%   |
| 1501-2000   | 13       | 4.83%   |
| 1001-1500   | 9        | 3.35%   |
| 351-400     | 7        | 2.6%    |
| 801-900     | 3        | 1.12%   |
| 201-300     | 2        | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 172      | 68.53%  |
| Unknown | 25       | 9.96%   |
| 16/10   | 21       | 8.37%   |
| 21/9    | 13       | 5.18%   |
| 5/4     | 12       | 4.78%   |
| 4/3     | 6        | 2.39%   |
| 32/9    | 2        | 0.8%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 89       | 32.6%   |
| 151-200        | 36       | 13.19%  |
| 351-500        | 31       | 11.36%  |
| Unknown        | 30       | 10.99%  |
| 141-150        | 27       | 9.89%   |
| More than 1000 | 19       | 6.96%   |
| 301-350        | 17       | 6.23%   |
| 101-110        | 11       | 4.03%   |
| 501-1000       | 6        | 2.2%    |
| 251-300        | 4        | 1.47%   |
| 131-140        | 2        | 0.73%   |
| 91-100         | 1        | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 146      | 55.73%  |
| 101-120 | 56       | 21.37%  |
| Unknown | 30       | 11.45%  |
| 1-50    | 22       | 8.4%    |
| 121-160 | 7        | 2.67%   |
| 161-240 | 1        | 0.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 210      | 75.81%  |
| 2     | 46       | 16.61%  |
| 0     | 14       | 5.05%   |
| 3     | 7        | 2.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 195      | 48.39%  |
| Intel                           | 79       | 19.6%   |
| Qualcomm Atheros                | 22       | 5.46%   |
| Ralink Technology               | 14       | 3.47%   |
| Ralink                          | 13       | 3.23%   |
| TP-Link                         | 10       | 2.48%   |
| Broadcom Limited                | 9        | 2.23%   |
| Broadcom                        | 9        | 2.23%   |
| Xiaomi                          | 8        | 1.99%   |
| D-Link System                   | 6        | 1.49%   |
| Qualcomm Atheros Communications | 4        | 0.99%   |
| Nvidia                          | 4        | 0.99%   |
| Microsoft                       | 4        | 0.99%   |
| D-Link                          | 4        | 0.99%   |
| Motorola PCS                    | 3        | 0.74%   |
| Marvell Technology Group        | 3        | 0.74%   |
| Huawei Technologies             | 3        | 0.74%   |
| VIA Technologies                | 2        | 0.5%    |
| Samsung Electronics             | 2        | 0.5%    |
| Spreadtrum Communications       | 1        | 0.25%   |
| Padix (Rockfire)                | 1        | 0.25%   |
| Oculus VR                       | 1        | 0.25%   |
| Mercucys                        | 1        | 0.25%   |
| MediaTek                        | 1        | 0.25%   |
| Manta                           | 1        | 0.25%   |
| ICS Advent                      | 1        | 0.25%   |
| HMD Global                      | 1        | 0.25%   |
| DisplayLink                     | 1        | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 156      | 34.59%  |
| Realtek RTL8125 2.5GbE Controller                                      | 12       | 2.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11       | 2.44%   |
| Intel I211 Gigabit Network Connection                                  | 9        | 2%      |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 8        | 1.77%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 8        | 1.77%   |
| Ralink MT7601U Wireless Adapter                                        | 7        | 1.55%   |
| Intel Wi-Fi 6 AX200                                                    | 7        | 1.55%   |
| Realtek 802.11ac NIC                                                   | 6        | 1.33%   |
| Intel Wireless 7260                                                    | 6        | 1.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 5        | 1.11%   |
| Intel Ethernet Connection I217-V                                       | 5        | 1.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5        | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4        | 0.89%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 4        | 0.89%   |
| Ralink RT5392 PCIe Wireless Network Adapter                            | 4        | 0.89%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 4        | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 4        | 0.89%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 0.89%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 0.89%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 0.89%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 3        | 0.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 3        | 0.67%   |
| Realtek RTL8187 Wireless Adapter                                       | 3        | 0.67%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 3        | 0.67%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3        | 0.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3        | 0.67%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 3        | 0.67%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 3        | 0.67%   |
| Intel Wireless 7265                                                    | 3        | 0.67%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3        | 0.67%   |
| Intel Ethernet Controller I225-V                                       | 3        | 0.67%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 0.67%   |
| Intel 82579V Gigabit Network Connection                                | 3        | 0.67%   |
| Huawei STG-LX1                                                         | 3        | 0.67%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]   | 3        | 0.67%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 3        | 0.67%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                | 3        | 0.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 40       | 27.97%  |
| Realtek Semiconductor           | 34       | 23.78%  |
| Ralink Technology               | 14       | 9.79%   |
| Ralink                          | 13       | 9.09%   |
| TP-Link                         | 10       | 6.99%   |
| Qualcomm Atheros                | 9        | 6.29%   |
| Qualcomm Atheros Communications | 4        | 2.8%    |
| Microsoft                       | 4        | 2.8%    |
| D-Link                          | 4        | 2.8%    |
| Broadcom Limited                | 4        | 2.8%    |
| D-Link System                   | 3        | 2.1%    |
| Broadcom                        | 3        | 2.1%    |
| Mercucys                        | 1        | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 8        | 5.59%   |
| Ralink MT7601U Wireless Adapter                                      | 7        | 4.9%    |
| Intel Wi-Fi 6 AX200                                                  | 7        | 4.9%    |
| Realtek 802.11ac NIC                                                 | 6        | 4.2%    |
| Intel Wireless 7260                                                  | 6        | 4.2%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 5        | 3.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4        | 2.8%    |
| Ralink RT2870/RT3070 Wireless Adapter                                | 4        | 2.8%    |
| Ralink RT5392 PCIe Wireless Network Adapter                          | 4        | 2.8%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 4        | 2.8%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 3        | 2.1%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 3        | 2.1%    |
| Realtek RTL8187 Wireless Adapter                                     | 3        | 2.1%    |
| Qualcomm Atheros AR9271 802.11n                                      | 3        | 2.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 3        | 2.1%    |
| Microsoft Xbox 360 Wireless Adapter                                  | 3        | 2.1%    |
| Intel Wireless 7265                                                  | 3        | 2.1%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 3        | 2.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3        | 2.1%    |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 3        | 2.1%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 1.4%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2        | 1.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2        | 1.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2        | 1.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 2        | 1.4%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller            | 2        | 1.4%    |
| Ralink RT5370 Wireless Adapter                                       | 2        | 1.4%    |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2        | 1.4%    |
| Intel Wireless 8260                                                  | 2        | 1.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2        | 1.4%    |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 2        | 1.4%    |
| D-Link WLAN controller                                               | 2        | 1.4%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                | 1        | 0.7%    |
| TP-Link Archer T4U ver.3                                             | 1        | 0.7%    |
| TP-Link 802.11ac WLAN Adapter                                        | 1        | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1        | 0.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.7%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1        | 0.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 184      | 61.95%  |
| Intel                     | 56       | 18.86%  |
| Qualcomm Atheros          | 14       | 4.71%   |
| Xiaomi                    | 8        | 2.69%   |
| Broadcom                  | 6        | 2.02%   |
| Broadcom Limited          | 5        | 1.68%   |
| Nvidia                    | 4        | 1.35%   |
| Marvell Technology Group  | 3        | 1.01%   |
| Huawei Technologies       | 3        | 1.01%   |
| D-Link System             | 3        | 1.01%   |
| VIA Technologies          | 2        | 0.67%   |
| Samsung Electronics       | 2        | 0.67%   |
| Motorola PCS              | 2        | 0.67%   |
| Spreadtrum Communications | 1        | 0.34%   |
| MediaTek                  | 1        | 0.34%   |
| ICS Advent                | 1        | 0.34%   |
| HMD Global                | 1        | 0.34%   |
| DisplayLink               | 1        | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 156      | 51.32%  |
| Realtek RTL8125 2.5GbE Controller                                      | 12       | 3.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11       | 3.62%   |
| Intel I211 Gigabit Network Connection                                  | 9        | 2.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 8        | 2.63%   |
| Intel Ethernet Connection I217-V                                       | 5        | 1.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5        | 1.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 4        | 1.32%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 1.32%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 1.32%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 1.32%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 3        | 0.99%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 3        | 0.99%   |
| Intel Ethernet Controller I225-V                                       | 3        | 0.99%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 0.99%   |
| Intel 82579V Gigabit Network Connection                                | 3        | 0.99%   |
| Huawei STG-LX1                                                         | 3        | 0.99%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 3        | 0.99%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                | 3        | 0.99%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2        | 0.66%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 2        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2        | 0.66%   |
| Motorola PCS moto g52                                                  | 2        | 0.66%   |
| Intel Ethernet Controller I226-V                                       | 2        | 0.66%   |
| Intel Ethernet Connection I218-V                                       | 2        | 0.66%   |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 0.66%   |
| Intel Ethernet Connection (12) I219-V                                  | 2        | 0.66%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 0.66%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 2        | 0.66%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 2        | 0.66%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1        | 0.33%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 0.33%   |
| Spreadtrum Unisoc Phone                                                | 1        | 0.33%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1        | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1        | 0.33%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1        | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 268      | 66.83%  |
| WiFi     | 129      | 32.17%  |
| Unknown  | 3        | 0.75%   |
| Modem    | 1        | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 207      | 74.73%  |
| WiFi     | 70       | 25.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 180      | 64.75%  |
| 2     | 82       | 29.5%   |
| 3     | 12       | 4.32%   |
| 4     | 2        | 0.72%   |
| 0     | 2        | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 247      | 89.17%  |
| Yes  | 30       | 10.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 37       | 38.95%  |
| Cambridge Silicon Radio         | 29       | 30.53%  |
| Realtek Semiconductor           | 14       | 14.74%  |
| Broadcom                        | 9        | 9.47%   |
| Qualcomm Atheros Communications | 2        | 2.11%   |
| ASUSTek Computer                | 2        | 2.11%   |
| Apple                           | 2        | 2.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 29       | 30.53%  |
| Realtek Bluetooth Radio                             | 12       | 12.63%  |
| Intel Bluetooth wireless interface                  | 11       | 11.58%  |
| Intel AX210 Bluetooth                               | 8        | 8.42%   |
| Intel AX200 Bluetooth                               | 7        | 7.37%   |
| Broadcom Bluetooth 3.0 Dongle                       | 5        | 5.26%   |
| Intel AX201 Bluetooth                               | 4        | 4.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 3.16%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 3.16%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 2.11%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 1.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.05%   |
| Broadcom HP Bluetooth Module                        | 1        | 1.05%   |
| Broadcom HP Bluethunder                             | 1        | 1.05%   |
| Broadcom Bluetooth 3.0 Device                       | 1        | 1.05%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 1.05%   |
| ASUS Bluetooth Radio                                | 1        | 1.05%   |
| ASUS BCM20702A0                                     | 1        | 1.05%   |
| Apple Bluetooth Host Controller                     | 1        | 1.05%   |
| Apple Bluetooth HCI                                 | 1        | 1.05%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 156      | 34.29%  |
| AMD                                          | 132      | 29.01%  |
| Nvidia                                       | 97       | 21.32%  |
| C-Media Electronics                          | 10       | 2.2%    |
| Creative Labs                                | 8        | 1.76%   |
| Logitech                                     | 7        | 1.54%   |
| Razer USA                                    | 5        | 1.1%    |
| Kingston Technology                          | 4        | 0.88%   |
| Zoran Co. Personal Media Division (Nogatech) | 3        | 0.66%   |
| JMTek                                        | 3        | 0.66%   |
| Generalplus Technology                       | 3        | 0.66%   |
| Creative Technology                          | 3        | 0.66%   |
| VIA Technologies                             | 2        | 0.44%   |
| Texas Instruments                            | 2        | 0.44%   |
| Focusrite-Novation                           | 2        | 0.44%   |
| Corsair                                      | 2        | 0.44%   |
| Arturia                                      | 2        | 0.44%   |
| Unknown                                      | 1        | 0.22%   |
| Trust                                        | 1        | 0.22%   |
| Synaptics                                    | 1        | 0.22%   |
| Realtek Semiconductor                        | 1        | 0.22%   |
| PreSonus Audio Electronics                   | 1        | 0.22%   |
| Native Instruments                           | 1        | 0.22%   |
| Micro Star International                     | 1        | 0.22%   |
| Hewlett-Packard                              | 1        | 0.22%   |
| GYROCOM C&C                                  | 1        | 0.22%   |
| eMPIA Technology                             | 1        | 0.22%   |
| Blue Microphones                             | 1        | 0.22%   |
| ATI Technologies                             | 1        | 0.22%   |
| Apple                                        | 1        | 0.22%   |
| Afatech                                      | 1        | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 27       | 4.92%   |
| AMD Starship/Matisse HD Audio Controller                                          | 27       | 4.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 26       | 4.74%   |
| AMD Family 17h/19h HD Audio Controller                                            | 26       | 4.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 17       | 3.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 16       | 2.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 14       | 2.55%   |
| AMD FCH Azalia Controller                                                         | 13       | 2.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 11       | 2%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 11       | 2%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 11       | 2%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 11       | 2%      |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 10       | 1.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10       | 1.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 9        | 1.64%   |
| Nvidia TU116 High Definition Audio Controller                                     | 8        | 1.46%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 8        | 1.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 8        | 1.46%   |
| AMD Navi 10 HDMI Audio                                                            | 8        | 1.46%   |
| Nvidia GP108 High Definition Audio Controller                                     | 7        | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7        | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                                     | 7        | 1.28%   |
| Intel Comet Lake PCH-V cAVS                                                       | 7        | 1.28%   |
| Intel Cannon Lake PCH cAVS                                                        | 7        | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 7        | 1.28%   |
| Intel 200 Series PCH HD Audio                                                     | 7        | 1.28%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 7        | 1.28%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 7        | 1.28%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 1.28%   |
| Nvidia MCP61 High Definition Audio                                                | 5        | 0.91%   |
| Nvidia GM206 High Definition Audio Controller                                     | 5        | 0.91%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5        | 0.91%   |
| Nvidia GA106 High Definition Audio Controller                                     | 5        | 0.91%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 5        | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4        | 0.73%   |
| Nvidia GK104 HDMI Audio Controller                                                | 4        | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 4        | 0.73%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 4        | 0.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 4        | 0.73%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 33       | 22.45%  |
| Crucial             | 23       | 15.65%  |
| Unknown             | 17       | 11.56%  |
| Samsung Electronics | 17       | 11.56%  |
| Corsair             | 15       | 10.2%   |
| SK hynix            | 8        | 5.44%   |
| Micron Technology   | 8        | 5.44%   |
| G.Skill             | 6        | 4.08%   |
| A-DATA Technology   | 6        | 4.08%   |
| Patriot             | 3        | 2.04%   |
| Hikvision           | 2        | 1.36%   |
| Team                | 1        | 0.68%   |
| Ramaxel Technology  | 1        | 0.68%   |
| Nanya Technology    | 1        | 0.68%   |
| Kreton              | 1        | 0.68%   |
| Goldenmars          | 1        | 0.68%   |
| GLOWAY              | 1        | 0.68%   |
| Elpida              | 1        | 0.68%   |
| Atermiter           | 1        | 0.68%   |
| Ankowall            | 1        | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 4        | 2.44%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 4        | 2.44%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 3        | 1.83%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3600MT/s      | 3        | 1.83%   |
| Crucial RAM CT4G4DFS6266.C4FJ 4GB DIMM DDR4 2666MT/s     | 3        | 1.83%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 2        | 1.22%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 2        | 1.22%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 2        | 1.22%   |
| Kingston RAM KHX3466C17D4/16GX 16GB DIMM DDR4 3466MT/s   | 2        | 1.22%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s     | 2        | 1.22%   |
| Crucial RAM BLS8G4D30AESEK.M8FE 8GB DIMM DDR4 3600MT/s   | 2        | 1.22%   |
| Corsair RAM VS2GB1333D3 2048MB DIMM DDR3 1333MT/s        | 2        | 1.22%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s     | 2        | 1.22%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s              | 2        | 1.22%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                | 1        | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.61%   |
| Unknown RAM Module 8192MB DIMM DDR3                      | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                | 1        | 0.61%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 0.61%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 400MT/s                 | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM                              | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                  | 1        | 0.61%   |
| Unknown RAM Module 1GB DIMM SDRAM                        | 1        | 0.61%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s      | 1        | 0.61%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s          | 1        | 0.61%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s            | 1        | 0.61%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB DIMM SDRAM 2048MT/s | 1        | 0.61%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.61%   |
| SK hynix RAM HMT151R7BFR4C 4096MB DIMM DDR3 1333MT/s     | 1        | 0.61%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s     | 1        | 0.61%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s   | 1        | 0.61%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s     | 1        | 0.61%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                | 1        | 0.61%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR5 6400MT/s      | 1        | 0.61%   |
| Samsung RAM M471B1G73QHO-YK0 8GB SODIMM DDR3 1600MT/s    | 1        | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 61       | 49.19%  |
| DDR3    | 44       | 35.48%  |
| DDR2    | 7        | 5.65%   |
| SDRAM   | 6        | 4.84%   |
| Unknown | 3        | 2.42%   |
| LPDDR5  | 1        | 0.81%   |
| DDR5    | 1        | 0.81%   |
| DDR     | 1        | 0.81%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 111      | 90.24%  |
| SODIMM       | 11       | 8.94%   |
| Row Of Chips | 1        | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 58       | 40.85%  |
| 4096  | 31       | 21.83%  |
| 2048  | 25       | 17.61%  |
| 16384 | 17       | 11.97%  |
| 32768 | 9        | 6.34%   |
| 1024  | 2        | 1.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 26       | 17.33%  |
| 1333    | 19       | 12.67%  |
| 2133    | 12       | 8%      |
| 3600    | 10       | 6.67%   |
| 2667    | 10       | 6.67%   |
| 2400    | 8        | 5.33%   |
| 3200    | 7        | 4.67%   |
| 3466    | 6        | 4%      |
| Unknown | 6        | 4%      |
| 2666    | 5        | 3.33%   |
| 3733    | 4        | 2.67%   |
| 2933    | 4        | 2.67%   |
| 1866    | 4        | 2.67%   |
| 667     | 4        | 2.67%   |
| 3800    | 3        | 2%      |
| 800     | 3        | 2%      |
| 6400    | 2        | 1.33%   |
| 3400    | 2        | 1.33%   |
| 3066    | 2        | 1.33%   |
| 3000    | 2        | 1.33%   |
| 1334    | 2        | 1.33%   |
| 1066    | 2        | 1.33%   |
| 4000    | 1        | 0.67%   |
| 3666    | 1        | 0.67%   |
| 3134    | 1        | 0.67%   |
| 2800    | 1        | 0.67%   |
| 2048    | 1        | 0.67%   |
| 1067    | 1        | 0.67%   |
| 400     | 1        | 0.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson         | 5        | 29.41%  |
| Canon               | 4        | 23.53%  |
| Brother Industries  | 4        | 23.53%  |
| Hewlett-Packard     | 3        | 17.65%  |
| QinHeng Electronics | 1        | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Brother HL-1200 series     | 3        | 17.65%  |
| Seiko Epson XP-2100 Series | 1        | 5.88%   |
| Seiko Epson Printer        | 1        | 5.88%   |
| Seiko Epson L3150 Series   | 1        | 5.88%   |
| Seiko Epson L3110 Series   | 1        | 5.88%   |
| Seiko Epson L210 Series    | 1        | 5.88%   |
| QinHeng CH340S             | 1        | 5.88%   |
| HP Deskjet 4640 series     | 1        | 5.88%   |
| HP Deskjet 4620 series     | 1        | 5.88%   |
| HP Deskjet 2050 J510       | 1        | 5.88%   |
| Canon PIXMA MP250          | 1        | 5.88%   |
| Canon LBP6000              | 1        | 5.88%   |
| Canon G2000 series         | 1        | 5.88%   |
| Canon G1000 series         | 1        | 5.88%   |
| Brother HL-1210W series    | 1        | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 2        | 50%     |
| Canon       | 2        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 1        | 25%     |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 25%     |
| Canon CanoScan LiDE 110                       | 1        | 25%     |
| Canon CanoScan D1250U2                        | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia                      | 8        | 12.7%   |
| Logitech                      | 8        | 12.7%   |
| Generalplus Technology        | 6        | 9.52%   |
| Chicony Electronics           | 6        | 9.52%   |
| Sunplus Innovation Technology | 5        | 7.94%   |
| Apple                         | 4        | 6.35%   |
| Microsoft                     | 3        | 4.76%   |
| Lenovo                        | 3        | 4.76%   |
| Jieli Technology              | 3        | 4.76%   |
| webcamvendor                  | 2        | 3.17%   |
| Realtek Semiconductor         | 2        | 3.17%   |
| Alcor Micro                   | 2        | 3.17%   |
| Z-Star Microelectronics       | 1        | 1.59%   |
| YGTek                         | 1        | 1.59%   |
| Unknown                       | 1        | 1.59%   |
| Remo Tech                     | 1        | 1.59%   |
| Razer USA                     | 1        | 1.59%   |
| OmniVision Technologies       | 1        | 1.59%   |
| MacroSilicon                  | 1        | 1.59%   |
| KYE Systems (Mouse Systems)   | 1        | 1.59%   |
| AVerMedia Technologies        | 1        | 1.59%   |
| Arkmicro Technologies         | 1        | 1.59%   |
| 04004000_P040200_SN0002       | 1        | 1.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Generalplus GENERAL WEBCAM                    | 6        | 9.52%   |
| Microdia USB 2.0 Camera                       | 5        | 7.94%   |
| Logitech C922 Pro Stream Webcam               | 4        | 6.35%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR            | 4        | 6.35%   |
| Jieli USB PHY 2.0                             | 3        | 4.76%   |
| Chicony HP 0.3MP Webcam                       | 3        | 4.76%   |
| webcamvendor webcamproduct                    | 2        | 3.17%   |
| Sunplus USB Camera                            | 2        | 3.17%   |
| Sunplus HD 720P webcam                        | 2        | 3.17%   |
| Microsoft MicrosoftÂ LifeCam Studio          | 2        | 3.17%   |
| Microdia Webcam Vitade AF                     | 2        | 3.17%   |
| Lenovo Lenovo 500 RGB Camera                  | 2        | 3.17%   |
| Z-Star Integrated Camera                      | 1        | 1.59%   |
| YGTek Webcam                                  | 1        | 1.59%   |
| Unknown HD camera                             | 1        | 1.59%   |
| Sunplus FHD Camera Microphone                 | 1        | 1.59%   |
| Remo Tech OBSBOT Tiny                         | 1        | 1.59%   |
| Realtek USB Camera                            | 1        | 1.59%   |
| Realtek NexiGo N660P FHD Webcam               | 1        | 1.59%   |
| Razer USA Razer Kiyo Pro                      | 1        | 1.59%   |
| OmniVision OV511+ Webcam                      | 1        | 1.59%   |
| Microsoft LifeCam VX-800                      | 1        | 1.59%   |
| Microdia USB camera                           | 1        | 1.59%   |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1        | 1.59%   |
| Logitech Webcam C270                          | 1        | 1.59%   |
| Logitech Webcam C210                          | 1        | 1.59%   |
| Logitech Webcam C170                          | 1        | 1.59%   |
| Logitech StreamCam                            | 1        | 1.59%   |
| Lenovo FHD Webcam Audio                       | 1        | 1.59%   |
| KYE Systems (Mouse Systems) FaceCam 1000X     | 1        | 1.59%   |
| Chicony HP High Definition 1MP Webcam         | 1        | 1.59%   |
| Chicony HP 1.0MP High Definition Webcam       | 1        | 1.59%   |
| Chicony CNF8050 Webcam                        | 1        | 1.59%   |
| AVerMedia Live Streamer CAM 313               | 1        | 1.59%   |
| Arkmicro USB2.0 PC CAMERA                     | 1        | 1.59%   |
| Alcor Micro USB Video Device                  | 1        | 1.59%   |
| Alcor Micro USB 2.0 PC Camera                 | 1        | 1.59%   |
| 04004000_P040200_SN0002 1080P Web Camera      | 1        | 1.59%   |

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
| 0     | 232      | 84.36%  |
| 1     | 36       | 13.09%  |
| 2     | 7        | 2.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 28.26%  |
| Graphics card            | 12       | 26.09%  |
| Unassigned class         | 6        | 13.04%  |
| Sound                    | 4        | 8.7%    |
| Communication controller | 4        | 8.7%    |
| Network                  | 3        | 6.52%   |
| Multimedia controller    | 1        | 2.17%   |
| Firewire controller      | 1        | 2.17%   |
| Camera                   | 1        | 2.17%   |
| Bluetooth                | 1        | 2.17%   |

