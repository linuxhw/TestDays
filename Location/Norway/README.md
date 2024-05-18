Linux in Norway - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Norway.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Norway/Desktop/README.md) and [notebooks](/Location/Norway/Notebook/README.md).

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

Total: 2302

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Panasonic     | CF-53SAWZYMN                | Notebook    | [15a322275f](https://linux-hardware.org/?probe=15a322275f) | May 08, 2024 |
| Dell          | 0GN6JF A01                  | Desktop     | [b9877feccd](https://linux-hardware.org/?probe=b9877feccd) | May 08, 2024 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [b941b8d062](https://linux-hardware.org/?probe=b941b8d062) | May 07, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [92d80bd754](https://linux-hardware.org/?probe=92d80bd754) | May 06, 2024 |
| MSI           | 2AE0                        | Desktop     | [25c9b3836b](https://linux-hardware.org/?probe=25c9b3836b) | May 06, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [37ed88bcea](https://linux-hardware.org/?probe=37ed88bcea) | May 03, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [c7a39f14e7](https://linux-hardware.org/?probe=c7a39f14e7) | May 03, 2024 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [67f5f847c9](https://linux-hardware.org/?probe=67f5f847c9) | May 03, 2024 |
| HP            | EliteBook 8570w             | Notebook    | [050889a119](https://linux-hardware.org/?probe=050889a119) | May 03, 2024 |
| HP            | EliteBook 8570w             | Notebook    | [6b53737811](https://linux-hardware.org/?probe=6b53737811) | May 03, 2024 |
| Lenovo        | ThinkPad T480 20L60034MX    | Notebook    | [eec0c4ee95](https://linux-hardware.org/?probe=eec0c4ee95) | May 02, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [def7a0898e](https://linux-hardware.org/?probe=def7a0898e) | May 02, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [10d6846920](https://linux-hardware.org/?probe=10d6846920) | May 01, 2024 |
| IGEL Techn... | M350C                       | Notebook    | [c63a48250c](https://linux-hardware.org/?probe=c63a48250c) | May 01, 2024 |
| Acer          | EM61SM/EM61PM               | Desktop     | [3b2c0bd5f6](https://linux-hardware.org/?probe=3b2c0bd5f6) | May 01, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [bb7791835b](https://linux-hardware.org/?probe=bb7791835b) | May 01, 2024 |
| Lenovo        | ThinkPad T510 43494JG       | Notebook    | [fe8480c6c4](https://linux-hardware.org/?probe=fe8480c6c4) | Apr 30, 2024 |
| Dell          | 06NWYK A00                  | Desktop     | [ec673a2386](https://linux-hardware.org/?probe=ec673a2386) | Apr 30, 2024 |
| ASUSTek       | ROG STRIX B460-F GAMING     | Desktop     | [b335a417f1](https://linux-hardware.org/?probe=b335a417f1) | Apr 30, 2024 |
| HP            | 0A98h                       | Desktop     | [1ebb8c49e0](https://linux-hardware.org/?probe=1ebb8c49e0) | Apr 29, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [4ef11d14a3](https://linux-hardware.org/?probe=4ef11d14a3) | Apr 29, 2024 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [cabdbdd8b4](https://linux-hardware.org/?probe=cabdbdd8b4) | Apr 29, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [3c89d5f47c](https://linux-hardware.org/?probe=3c89d5f47c) | Apr 29, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [58fc3d5b13](https://linux-hardware.org/?probe=58fc3d5b13) | Apr 29, 2024 |
| ASUSTek       | PRIME X299-A                | Desktop     | [82f302ed14](https://linux-hardware.org/?probe=82f302ed14) | Apr 29, 2024 |
| ASUSTek       | PRIME X299-A                | Desktop     | [18f815fd59](https://linux-hardware.org/?probe=18f815fd59) | Apr 29, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [723af200e1](https://linux-hardware.org/?probe=723af200e1) | Apr 27, 2024 |
| HP            | ProBook 440 G6              | Notebook    | [3cf105c072](https://linux-hardware.org/?probe=3cf105c072) | Apr 26, 2024 |
| MSI           | MS-B1831                    | Desktop     | [63fec5c61b](https://linux-hardware.org/?probe=63fec5c61b) | Apr 25, 2024 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [3f76329bd6](https://linux-hardware.org/?probe=3f76329bd6) | Apr 23, 2024 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [5d84a72fcf](https://linux-hardware.org/?probe=5d84a72fcf) | Apr 22, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f126ef0f39](https://linux-hardware.org/?probe=f126ef0f39) | Apr 22, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [89c9b39716](https://linux-hardware.org/?probe=89c9b39716) | Apr 22, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [994aae0769](https://linux-hardware.org/?probe=994aae0769) | Apr 21, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [e26cecc411](https://linux-hardware.org/?probe=e26cecc411) | Apr 21, 2024 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [252a0c4e05](https://linux-hardware.org/?probe=252a0c4e05) | Apr 21, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [0231457347](https://linux-hardware.org/?probe=0231457347) | Apr 21, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [bf7ed0943a](https://linux-hardware.org/?probe=bf7ed0943a) | Apr 21, 2024 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [28f75ed494](https://linux-hardware.org/?probe=28f75ed494) | Apr 21, 2024 |
| Acer          | Enduro EUN314-51W           | Notebook    | [7a57f25e0e](https://linux-hardware.org/?probe=7a57f25e0e) | Apr 20, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [bef996dda3](https://linux-hardware.org/?probe=bef996dda3) | Apr 20, 2024 |
| Acer          | Aspire XC-705               | Desktop     | [da91a97808](https://linux-hardware.org/?probe=da91a97808) | Apr 20, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [d99c576d13](https://linux-hardware.org/?probe=d99c576d13) | Apr 19, 2024 |
| Lenovo        | ThinkPad T520 42433ZG       | Notebook    | [d2899d8de6](https://linux-hardware.org/?probe=d2899d8de6) | Apr 19, 2024 |
| Apple         | MacBookAir6,1               | Notebook    | [08ca3d5ea0](https://linux-hardware.org/?probe=08ca3d5ea0) | Apr 19, 2024 |
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [6b0dd29862](https://linux-hardware.org/?probe=6b0dd29862) | Apr 19, 2024 |
| Clevo         | P170EM                      | Notebook    | [62fe8276aa](https://linux-hardware.org/?probe=62fe8276aa) | Apr 18, 2024 |
| Clevo         | P170EM                      | Notebook    | [46daa154fe](https://linux-hardware.org/?probe=46daa154fe) | Apr 18, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [f841d88fe9](https://linux-hardware.org/?probe=f841d88fe9) | Apr 17, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [0cd0c2f953](https://linux-hardware.org/?probe=0cd0c2f953) | Apr 17, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e9fcf03a9f](https://linux-hardware.org/?probe=e9fcf03a9f) | Apr 17, 2024 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [8d77664d91](https://linux-hardware.org/?probe=8d77664d91) | Apr 16, 2024 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [40c6d6959f](https://linux-hardware.org/?probe=40c6d6959f) | Apr 15, 2024 |
| Google        | Morphius                    | Notebook    | [422dcd7238](https://linux-hardware.org/?probe=422dcd7238) | Apr 14, 2024 |
| Google        | Morphius                    | Notebook    | [97da05767b](https://linux-hardware.org/?probe=97da05767b) | Apr 13, 2024 |
| Dell          | 06X1TJ A00                  | Desktop     | [462d691265](https://linux-hardware.org/?probe=462d691265) | Apr 12, 2024 |
| Dell          | 06X1TJ A00                  | Desktop     | [be5c35a265](https://linux-hardware.org/?probe=be5c35a265) | Apr 12, 2024 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [4ea596e363](https://linux-hardware.org/?probe=4ea596e363) | Apr 11, 2024 |
| Acer          | Enduro EUN314-51W           | Notebook    | [fa7d224ee9](https://linux-hardware.org/?probe=fa7d224ee9) | Apr 11, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | Notebook    | [5ec749c52a](https://linux-hardware.org/?probe=5ec749c52a) | Apr 08, 2024 |
| Dell          | Latitude E7240              | Notebook    | [a323cf8e2e](https://linux-hardware.org/?probe=a323cf8e2e) | Apr 08, 2024 |
| MSI           | Katana GF76 11SC            | Notebook    | [937a23fec5](https://linux-hardware.org/?probe=937a23fec5) | Apr 08, 2024 |
| Acer          | Aspire XC-705               | Desktop     | [867eb764b1](https://linux-hardware.org/?probe=867eb764b1) | Apr 08, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [8ebbe74fff](https://linux-hardware.org/?probe=8ebbe74fff) | Apr 08, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [0079f0fad1](https://linux-hardware.org/?probe=0079f0fad1) | Apr 07, 2024 |
| Radxa         | ROCK 5 Model B              | Soc         | [eccb316f36](https://linux-hardware.org/?probe=eccb316f36) | Apr 07, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [b35623df85](https://linux-hardware.org/?probe=b35623df85) | Apr 07, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [bae1a9abd7](https://linux-hardware.org/?probe=bae1a9abd7) | Apr 06, 2024 |
| Lenovo        | ThinkPad W530 24476F1       | Notebook    | [14d694fe39](https://linux-hardware.org/?probe=14d694fe39) | Apr 05, 2024 |
| Acer          | ConceptD CC715-71P          | Convertible | [cefbc5d802](https://linux-hardware.org/?probe=cefbc5d802) | Apr 04, 2024 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [bdff9c20d1](https://linux-hardware.org/?probe=bdff9c20d1) | Apr 03, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [ced1751326](https://linux-hardware.org/?probe=ced1751326) | Apr 01, 2024 |
| HP            | ProBook 450 G2              | Notebook    | [1753d19bc6](https://linux-hardware.org/?probe=1753d19bc6) | Mar 30, 2024 |
| Notebook      | NJx0AU                      | Notebook    | [93425cb488](https://linux-hardware.org/?probe=93425cb488) | Mar 29, 2024 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [81603f2f58](https://linux-hardware.org/?probe=81603f2f58) | Mar 29, 2024 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [363b15345f](https://linux-hardware.org/?probe=363b15345f) | Mar 28, 2024 |
| ASUSTek       | G53SX                       | Notebook    | [6d2eeefcd5](https://linux-hardware.org/?probe=6d2eeefcd5) | Mar 27, 2024 |
| Huanan        | X99-F8D PLUS V1.3           | Desktop     | [f21a67ba94](https://linux-hardware.org/?probe=f21a67ba94) | Mar 26, 2024 |
| Lenovo        | ThinkPad X280 20KES6M100    | Notebook    | [07c23b72ec](https://linux-hardware.org/?probe=07c23b72ec) | Mar 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8ee75a3460](https://linux-hardware.org/?probe=8ee75a3460) | Mar 23, 2024 |
| HP            | 8266                        | Desktop     | [df49dd1099](https://linux-hardware.org/?probe=df49dd1099) | Mar 22, 2024 |
| Dell          | Latitude E7240              | Notebook    | [a295e64d94](https://linux-hardware.org/?probe=a295e64d94) | Mar 21, 2024 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b862d6b8c5](https://linux-hardware.org/?probe=b862d6b8c5) | Mar 19, 2024 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [69a6ff7b62](https://linux-hardware.org/?probe=69a6ff7b62) | Mar 18, 2024 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [f58b97df65](https://linux-hardware.org/?probe=f58b97df65) | Mar 18, 2024 |
| ASUSTek       | P8P67 EVO                   | Desktop     | [3ece14c501](https://linux-hardware.org/?probe=3ece14c501) | Mar 13, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [8406675c12](https://linux-hardware.org/?probe=8406675c12) | Mar 11, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [dac802bc03](https://linux-hardware.org/?probe=dac802bc03) | Mar 11, 2024 |
| MSI           | GP70 2QF                    | Notebook    | [0b3d8c1b0e](https://linux-hardware.org/?probe=0b3d8c1b0e) | Mar 10, 2024 |
| HP            | EliteBook x360 1030 G7 N... | Convertible | [0f0640b2bf](https://linux-hardware.org/?probe=0f0640b2bf) | Mar 10, 2024 |
| Microsoft     | Surface Pro 7               | Tablet      | [352a2fc191](https://linux-hardware.org/?probe=352a2fc191) | Mar 08, 2024 |
| Dell          | Latitude 7280               | Notebook    | [1149975fb9](https://linux-hardware.org/?probe=1149975fb9) | Mar 08, 2024 |
| MSI           | P67A-C45                    | Desktop     | [061c462ad8](https://linux-hardware.org/?probe=061c462ad8) | Mar 07, 2024 |
| Toshiba       | Satellite C50D-A-133        | Notebook    | [65ea7ee4de](https://linux-hardware.org/?probe=65ea7ee4de) | Mar 07, 2024 |
| AAEON         | UP-APL03 V1.0               | Desktop     | [81f53abe10](https://linux-hardware.org/?probe=81f53abe10) | Mar 06, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [3c91f66fcd](https://linux-hardware.org/?probe=3c91f66fcd) | Mar 04, 2024 |
| Cepter        | N530-01                     | Notebook    | [00dd983443](https://linux-hardware.org/?probe=00dd983443) | Mar 03, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [0ea6482b6a](https://linux-hardware.org/?probe=0ea6482b6a) | Feb 29, 2024 |
| Acer          | Spin SP513-51               | Convertible | [83c6f25aaa](https://linux-hardware.org/?probe=83c6f25aaa) | Feb 27, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [bada5f6377](https://linux-hardware.org/?probe=bada5f6377) | Feb 25, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [b3e5fe0754](https://linux-hardware.org/?probe=b3e5fe0754) | Feb 24, 2024 |
| Acer          | Aspire VN7-592G             | Notebook    | [dd6617c3d7](https://linux-hardware.org/?probe=dd6617c3d7) | Feb 23, 2024 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [244cd38058](https://linux-hardware.org/?probe=244cd38058) | Feb 23, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [e131682563](https://linux-hardware.org/?probe=e131682563) | Feb 22, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [a87320ad88](https://linux-hardware.org/?probe=a87320ad88) | Feb 22, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [086a1782c7](https://linux-hardware.org/?probe=086a1782c7) | Feb 22, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [2cb764d171](https://linux-hardware.org/?probe=2cb764d171) | Feb 21, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [a308cdb145](https://linux-hardware.org/?probe=a308cdb145) | Feb 20, 2024 |
| HP            | EliteBook x360 1030 G4      | Convertible | [42cd24e908](https://linux-hardware.org/?probe=42cd24e908) | Feb 20, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [2a1f27fe39](https://linux-hardware.org/?probe=2a1f27fe39) | Feb 19, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8ff055ea98](https://linux-hardware.org/?probe=8ff055ea98) | Feb 18, 2024 |
| MSI           | Katana GF76 11SC            | Notebook    | [255453e6e0](https://linux-hardware.org/?probe=255453e6e0) | Feb 18, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [20ae1292c5](https://linux-hardware.org/?probe=20ae1292c5) | Feb 18, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [64223925d6](https://linux-hardware.org/?probe=64223925d6) | Feb 18, 2024 |
| HP            | ProBook 430 G2              | Notebook    | [a4b236fd41](https://linux-hardware.org/?probe=a4b236fd41) | Feb 17, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [963e62d63c](https://linux-hardware.org/?probe=963e62d63c) | Feb 17, 2024 |
| Gigabyte      | Z790 AORUS PRO X            | Desktop     | [1036cc6203](https://linux-hardware.org/?probe=1036cc6203) | Feb 16, 2024 |
| Acer          | v1.0                        | Desktop     | [a7ba3b84dc](https://linux-hardware.org/?probe=a7ba3b84dc) | Feb 14, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [02bcb4fe60](https://linux-hardware.org/?probe=02bcb4fe60) | Feb 14, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [3103ce546a](https://linux-hardware.org/?probe=3103ce546a) | Feb 14, 2024 |
| Acer          | Aspire V5-552               | Notebook    | [e442dc1b93](https://linux-hardware.org/?probe=e442dc1b93) | Feb 13, 2024 |
| HP            | 805D                        | Desktop     | [1d6e8a52ad](https://linux-hardware.org/?probe=1d6e8a52ad) | Feb 13, 2024 |
| Acer          | Swift SF14-71T              | Notebook    | [be5a1a32c8](https://linux-hardware.org/?probe=be5a1a32c8) | Feb 13, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [1c7c2e02cb](https://linux-hardware.org/?probe=1c7c2e02cb) | Feb 13, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [ba2e17a0f0](https://linux-hardware.org/?probe=ba2e17a0f0) | Feb 11, 2024 |
| HP            | ProBook 430 G1              | Notebook    | [191e61f6f6](https://linux-hardware.org/?probe=191e61f6f6) | Feb 09, 2024 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [4dae359014](https://linux-hardware.org/?probe=4dae359014) | Feb 09, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [2130b12c50](https://linux-hardware.org/?probe=2130b12c50) | Feb 09, 2024 |
| Dell          | Inspiron 7559               | Notebook    | [9f3df9cfa3](https://linux-hardware.org/?probe=9f3df9cfa3) | Feb 09, 2024 |
| HP            | ProBook 6450b               | Notebook    | [423b15dea2](https://linux-hardware.org/?probe=423b15dea2) | Feb 09, 2024 |
| ASRock        | 990FX Professional          | Desktop     | [1f9d6c28fc](https://linux-hardware.org/?probe=1f9d6c28fc) | Feb 08, 2024 |
| HP            | 212B                        | Desktop     | [720fcf3685](https://linux-hardware.org/?probe=720fcf3685) | Feb 08, 2024 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [9a088ac635](https://linux-hardware.org/?probe=9a088ac635) | Feb 08, 2024 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [24923511bf](https://linux-hardware.org/?probe=24923511bf) | Feb 08, 2024 |
| HP            | ProBook 450 G2              | Notebook    | [7a2fbcd83a](https://linux-hardware.org/?probe=7a2fbcd83a) | Feb 08, 2024 |
| HP            | ProBook 450 G2              | Notebook    | [77995292b4](https://linux-hardware.org/?probe=77995292b4) | Feb 08, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [d4ab212d03](https://linux-hardware.org/?probe=d4ab212d03) | Feb 06, 2024 |
| HP            | 212B                        | Desktop     | [b3bc6c9d57](https://linux-hardware.org/?probe=b3bc6c9d57) | Feb 05, 2024 |
| HP            | 212B                        | Desktop     | [4ce740d8ad](https://linux-hardware.org/?probe=4ce740d8ad) | Feb 05, 2024 |
| HP            | 212B                        | Desktop     | [7ea5081cc7](https://linux-hardware.org/?probe=7ea5081cc7) | Feb 05, 2024 |
| HP            | 212B                        | Desktop     | [13dac46d00](https://linux-hardware.org/?probe=13dac46d00) | Feb 05, 2024 |
| HP            | 212B                        | Desktop     | [ca3ce84394](https://linux-hardware.org/?probe=ca3ce84394) | Feb 05, 2024 |
| HP            | 212B                        | Desktop     | [3e5dd21126](https://linux-hardware.org/?probe=3e5dd21126) | Feb 05, 2024 |
| HP            | 212B                        | Desktop     | [94722f627b](https://linux-hardware.org/?probe=94722f627b) | Feb 05, 2024 |
| HP            | 212B                        | Desktop     | [45ef556ddc](https://linux-hardware.org/?probe=45ef556ddc) | Feb 05, 2024 |
| HP            | 212B                        | Desktop     | [a289a17f37](https://linux-hardware.org/?probe=a289a17f37) | Feb 05, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [f6f21ad952](https://linux-hardware.org/?probe=f6f21ad952) | Feb 04, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [4e9d6930c7](https://linux-hardware.org/?probe=4e9d6930c7) | Feb 03, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [158530e4dc](https://linux-hardware.org/?probe=158530e4dc) | Feb 02, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [3953592045](https://linux-hardware.org/?probe=3953592045) | Feb 01, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [52f18f604d](https://linux-hardware.org/?probe=52f18f604d) | Feb 01, 2024 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [ad0630a0fc](https://linux-hardware.org/?probe=ad0630a0fc) | Feb 01, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [ffaf5dab37](https://linux-hardware.org/?probe=ffaf5dab37) | Jan 31, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [f47e169ab1](https://linux-hardware.org/?probe=f47e169ab1) | Jan 30, 2024 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [429541ce17](https://linux-hardware.org/?probe=429541ce17) | Jan 29, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [7f3a619e25](https://linux-hardware.org/?probe=7f3a619e25) | Jan 27, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [26cf710a63](https://linux-hardware.org/?probe=26cf710a63) | Jan 27, 2024 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [30954e841f](https://linux-hardware.org/?probe=30954e841f) | Jan 26, 2024 |
| Gigabyte      | Z68X-UD4-B3                 | Desktop     | [e114381673](https://linux-hardware.org/?probe=e114381673) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [5948bdd871](https://linux-hardware.org/?probe=5948bdd871) | Jan 25, 2024 |
| MSI           | P65 Creator 9SE             | Notebook    | [863ad9098e](https://linux-hardware.org/?probe=863ad9098e) | Jan 24, 2024 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [e78a5c9804](https://linux-hardware.org/?probe=e78a5c9804) | Jan 24, 2024 |
| Lenovo        | ThinkPad T490 20N3SA9100    | Notebook    | [02efe357c0](https://linux-hardware.org/?probe=02efe357c0) | Jan 21, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [7f5c817c53](https://linux-hardware.org/?probe=7f5c817c53) | Jan 21, 2024 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [f5eb92f644](https://linux-hardware.org/?probe=f5eb92f644) | Jan 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [50d318d640](https://linux-hardware.org/?probe=50d318d640) | Jan 18, 2024 |
| HP            | ZBook 14 G2                 | Notebook    | [e2c1850473](https://linux-hardware.org/?probe=e2c1850473) | Jan 18, 2024 |
| Samsung       | R780                        | Notebook    | [b3adbfa6ae](https://linux-hardware.org/?probe=b3adbfa6ae) | Jan 17, 2024 |
| Lenovo        | ThinkPad T460p 20FXS1G70... | Notebook    | [519458acdc](https://linux-hardware.org/?probe=519458acdc) | Jan 15, 2024 |
| Acer          | Aspire V5-551G              | Notebook    | [699c652ddd](https://linux-hardware.org/?probe=699c652ddd) | Jan 12, 2024 |
| Acer          | Aspire V5-551G              | Notebook    | [8c23e0fefc](https://linux-hardware.org/?probe=8c23e0fefc) | Jan 12, 2024 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [1b8551739b](https://linux-hardware.org/?probe=1b8551739b) | Jan 12, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [9b78bbc950](https://linux-hardware.org/?probe=9b78bbc950) | Jan 11, 2024 |
| Dell          | Latitude 7420               | Notebook    | [03a0ad44ae](https://linux-hardware.org/?probe=03a0ad44ae) | Jan 09, 2024 |
| MSI           | Katana GF76 11SC            | Notebook    | [e85c0b091c](https://linux-hardware.org/?probe=e85c0b091c) | Jan 08, 2024 |
| MSI           | P65 Creator 9SE             | Notebook    | [33a2ceb954](https://linux-hardware.org/?probe=33a2ceb954) | Jan 08, 2024 |
| HP            | ZBook 14 G2                 | Notebook    | [a5d8d9ecc9](https://linux-hardware.org/?probe=a5d8d9ecc9) | Jan 06, 2024 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [329f1f3fa2](https://linux-hardware.org/?probe=329f1f3fa2) | Jan 05, 2024 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [2cefb2c1d5](https://linux-hardware.org/?probe=2cefb2c1d5) | Jan 04, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [353e6f7966](https://linux-hardware.org/?probe=353e6f7966) | Jan 03, 2024 |
| Notebook      | X170KM-G                    | Notebook    | [731411ae4d](https://linux-hardware.org/?probe=731411ae4d) | Jan 02, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [0c40685bac](https://linux-hardware.org/?probe=0c40685bac) | Jan 02, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [67ef36b749](https://linux-hardware.org/?probe=67ef36b749) | Jan 01, 2024 |
| MSI           | P65 Creator 9SE             | Notebook    | [2e5c1a6b06](https://linux-hardware.org/?probe=2e5c1a6b06) | Jan 01, 2024 |
| MSI           | X99A RAIDER                 | Desktop     | [bb37fe4632](https://linux-hardware.org/?probe=bb37fe4632) | Jan 01, 2024 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [bc788ac36f](https://linux-hardware.org/?probe=bc788ac36f) | Dec 31, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [fa478c5226](https://linux-hardware.org/?probe=fa478c5226) | Dec 31, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [a7a54aba38](https://linux-hardware.org/?probe=a7a54aba38) | Dec 31, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [a9aee13c48](https://linux-hardware.org/?probe=a9aee13c48) | Dec 31, 2023 |
| ASRock        | Q1900M                      | Desktop     | [67778ed569](https://linux-hardware.org/?probe=67778ed569) | Dec 31, 2023 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [0181b68b4a](https://linux-hardware.org/?probe=0181b68b4a) | Dec 31, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [646c8d24fb](https://linux-hardware.org/?probe=646c8d24fb) | Dec 30, 2023 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [4cb0683071](https://linux-hardware.org/?probe=4cb0683071) | Dec 30, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [0d092c7ece](https://linux-hardware.org/?probe=0d092c7ece) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [159d5b2ef2](https://linux-hardware.org/?probe=159d5b2ef2) | Dec 28, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [42985f8c13](https://linux-hardware.org/?probe=42985f8c13) | Dec 28, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [6be155ee0d](https://linux-hardware.org/?probe=6be155ee0d) | Dec 27, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [67492721ec](https://linux-hardware.org/?probe=67492721ec) | Dec 26, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [814681e28a](https://linux-hardware.org/?probe=814681e28a) | Dec 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [bd10b63ca1](https://linux-hardware.org/?probe=bd10b63ca1) | Dec 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b150280df5](https://linux-hardware.org/?probe=b150280df5) | Dec 24, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [6d8c495e90](https://linux-hardware.org/?probe=6d8c495e90) | Dec 23, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6ff6445717](https://linux-hardware.org/?probe=6ff6445717) | Dec 22, 2023 |
| Dell          | 0FM586                      | Desktop     | [eadcdb629b](https://linux-hardware.org/?probe=eadcdb629b) | Dec 20, 2023 |
| Dell          | Latitude 5430               | Notebook    | [bce74a439e](https://linux-hardware.org/?probe=bce74a439e) | Dec 18, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [8cb0e95e29](https://linux-hardware.org/?probe=8cb0e95e29) | Dec 18, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [84c183a024](https://linux-hardware.org/?probe=84c183a024) | Dec 18, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0baa198f9f](https://linux-hardware.org/?probe=0baa198f9f) | Dec 17, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [047995ad80](https://linux-hardware.org/?probe=047995ad80) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [d34cfca6c8](https://linux-hardware.org/?probe=d34cfca6c8) | Dec 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [95deb85c40](https://linux-hardware.org/?probe=95deb85c40) | Dec 16, 2023 |
| Dell          | 0FM586                      | Desktop     | [c895a8d51f](https://linux-hardware.org/?probe=c895a8d51f) | Dec 15, 2023 |
| HP            | 1496                        | Desktop     | [a89ca6e62d](https://linux-hardware.org/?probe=a89ca6e62d) | Dec 14, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [03b847bfea](https://linux-hardware.org/?probe=03b847bfea) | Dec 13, 2023 |
| Gigabyte      | P35-DS3                     | Desktop     | [b8b172a5f2](https://linux-hardware.org/?probe=b8b172a5f2) | Dec 12, 2023 |
| Gigabyte      | P35-DS3                     | Desktop     | [d386a28d7e](https://linux-hardware.org/?probe=d386a28d7e) | Dec 12, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [41ff1cd0ca](https://linux-hardware.org/?probe=41ff1cd0ca) | Dec 12, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [076e19b0aa](https://linux-hardware.org/?probe=076e19b0aa) | Dec 11, 2023 |
| Dell          | Latitude 5400               | Notebook    | [6e887e1547](https://linux-hardware.org/?probe=6e887e1547) | Dec 11, 2023 |
| Google        | Electro                     | Notebook    | [503645df79](https://linux-hardware.org/?probe=503645df79) | Dec 11, 2023 |
| Dell          | 0FM586                      | Desktop     | [2bf8665376](https://linux-hardware.org/?probe=2bf8665376) | Dec 10, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [6d01f19f82](https://linux-hardware.org/?probe=6d01f19f82) | Dec 08, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [cd7c131bf1](https://linux-hardware.org/?probe=cd7c131bf1) | Dec 07, 2023 |
| MSI           | P67A-C45                    | Desktop     | [65f9196217](https://linux-hardware.org/?probe=65f9196217) | Dec 07, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [a1b25ec823](https://linux-hardware.org/?probe=a1b25ec823) | Dec 04, 2023 |
| HP            | ProBook 4330s               | Notebook    | [48a060af86](https://linux-hardware.org/?probe=48a060af86) | Dec 04, 2023 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [c5f6a282c6](https://linux-hardware.org/?probe=c5f6a282c6) | Dec 03, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f59641873e](https://linux-hardware.org/?probe=f59641873e) | Dec 03, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [427b578e83](https://linux-hardware.org/?probe=427b578e83) | Dec 02, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [e9b9374641](https://linux-hardware.org/?probe=e9b9374641) | Dec 02, 2023 |
| Dell          | Latitude E7240              | Notebook    | [e5ac912c4c](https://linux-hardware.org/?probe=e5ac912c4c) | Dec 02, 2023 |
| HP            | Pavilion dv7                | Notebook    | [dc015f1023](https://linux-hardware.org/?probe=dc015f1023) | Dec 01, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [1199d4ddfe](https://linux-hardware.org/?probe=1199d4ddfe) | Dec 01, 2023 |
| HP            | 212B                        | Desktop     | [dc1382e549](https://linux-hardware.org/?probe=dc1382e549) | Dec 01, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [deafec47f7](https://linux-hardware.org/?probe=deafec47f7) | Dec 01, 2023 |
| ASUSTek       | Zenbook UX6404VI_UX6404V... | Notebook    | [e52dad2488](https://linux-hardware.org/?probe=e52dad2488) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K540... | Notebook    | [fc00682f42](https://linux-hardware.org/?probe=fc00682f42) | Nov 29, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [64f654aa34](https://linux-hardware.org/?probe=64f654aa34) | Nov 29, 2023 |
| Dell          | Latitude 7440               | Notebook    | [aa4dce8576](https://linux-hardware.org/?probe=aa4dce8576) | Nov 27, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [4819314a84](https://linux-hardware.org/?probe=4819314a84) | Nov 27, 2023 |
| Dell          | Latitude 3350               | Notebook    | [395158b705](https://linux-hardware.org/?probe=395158b705) | Nov 27, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [440b3f0798](https://linux-hardware.org/?probe=440b3f0798) | Nov 25, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [904f3a4c07](https://linux-hardware.org/?probe=904f3a4c07) | Nov 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [4515ea6be6](https://linux-hardware.org/?probe=4515ea6be6) | Nov 24, 2023 |
| Dell          | Latitude 7440               | Notebook    | [c05ecee673](https://linux-hardware.org/?probe=c05ecee673) | Nov 23, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [8470d1677a](https://linux-hardware.org/?probe=8470d1677a) | Nov 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [21257dcbad](https://linux-hardware.org/?probe=21257dcbad) | Nov 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [b69760e673](https://linux-hardware.org/?probe=b69760e673) | Nov 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c4ade3f05e](https://linux-hardware.org/?probe=c4ade3f05e) | Nov 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [ead4849578](https://linux-hardware.org/?probe=ead4849578) | Nov 22, 2023 |
| Supermicro    | X9DRE-TF+/X9DR7-TF+         | Server      | [383f5969c5](https://linux-hardware.org/?probe=383f5969c5) | Nov 21, 2023 |
| Dell          | Latitude 5400               | Notebook    | [a2994234ca](https://linux-hardware.org/?probe=a2994234ca) | Nov 21, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [e696c3dd13](https://linux-hardware.org/?probe=e696c3dd13) | Nov 21, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [07e18044ae](https://linux-hardware.org/?probe=07e18044ae) | Nov 21, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3844682c90](https://linux-hardware.org/?probe=3844682c90) | Nov 21, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [8295e7e21e](https://linux-hardware.org/?probe=8295e7e21e) | Nov 20, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [fd4876bdbc](https://linux-hardware.org/?probe=fd4876bdbc) | Nov 20, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [9c025dacfd](https://linux-hardware.org/?probe=9c025dacfd) | Nov 19, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [1aed7bfcb8](https://linux-hardware.org/?probe=1aed7bfcb8) | Nov 19, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [8c24f72ac9](https://linux-hardware.org/?probe=8c24f72ac9) | Nov 19, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [fc41df67a4](https://linux-hardware.org/?probe=fc41df67a4) | Nov 19, 2023 |
| Gigabyte      | P35-DS3                     | Desktop     | [ece45e3b1c](https://linux-hardware.org/?probe=ece45e3b1c) | Nov 18, 2023 |
| Gigabyte      | P35-DS3                     | Desktop     | [1f7e5feb84](https://linux-hardware.org/?probe=1f7e5feb84) | Nov 17, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [204303d116](https://linux-hardware.org/?probe=204303d116) | Nov 17, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [c8af1c096b](https://linux-hardware.org/?probe=c8af1c096b) | Nov 17, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [75009bf512](https://linux-hardware.org/?probe=75009bf512) | Nov 17, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [362ad8efa4](https://linux-hardware.org/?probe=362ad8efa4) | Nov 16, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [2118effdd4](https://linux-hardware.org/?probe=2118effdd4) | Nov 15, 2023 |
| Gigabyte      | P35-DS3                     | Desktop     | [fac1d1b119](https://linux-hardware.org/?probe=fac1d1b119) | Nov 14, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [3cd966cd6a](https://linux-hardware.org/?probe=3cd966cd6a) | Nov 14, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [7b7cf69882](https://linux-hardware.org/?probe=7b7cf69882) | Nov 14, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [bb0f5fe1e2](https://linux-hardware.org/?probe=bb0f5fe1e2) | Nov 14, 2023 |
| Lenovo        | 330B NOK                    | Mini pc     | [f720496c11](https://linux-hardware.org/?probe=f720496c11) | Nov 13, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [61994e2e2e](https://linux-hardware.org/?probe=61994e2e2e) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [8762b09fbd](https://linux-hardware.org/?probe=8762b09fbd) | Nov 12, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [1473413ce2](https://linux-hardware.org/?probe=1473413ce2) | Nov 09, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [d660dfe17a](https://linux-hardware.org/?probe=d660dfe17a) | Nov 09, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [4345e63ae2](https://linux-hardware.org/?probe=4345e63ae2) | Nov 08, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [722c36be7f](https://linux-hardware.org/?probe=722c36be7f) | Nov 07, 2023 |
| HP            | 8594                        | Desktop     | [d51c507511](https://linux-hardware.org/?probe=d51c507511) | Nov 06, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [8d9bbb07dd](https://linux-hardware.org/?probe=8d9bbb07dd) | Nov 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3a2a72df26](https://linux-hardware.org/?probe=3a2a72df26) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [9655bf2db1](https://linux-hardware.org/?probe=9655bf2db1) | Nov 06, 2023 |
| MSI           | Z77 MPower                  | Desktop     | [9a199b462a](https://linux-hardware.org/?probe=9a199b462a) | Nov 05, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [8e5ae08c12](https://linux-hardware.org/?probe=8e5ae08c12) | Nov 05, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [be39067306](https://linux-hardware.org/?probe=be39067306) | Nov 05, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [7834b537a1](https://linux-hardware.org/?probe=7834b537a1) | Nov 05, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [387194bdf6](https://linux-hardware.org/?probe=387194bdf6) | Nov 03, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [9ea1c674f9](https://linux-hardware.org/?probe=9ea1c674f9) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [26bc5f025c](https://linux-hardware.org/?probe=26bc5f025c) | Nov 02, 2023 |
| HP            | ProBook 6450b               | Notebook    | [75ad2cf5f8](https://linux-hardware.org/?probe=75ad2cf5f8) | Nov 02, 2023 |
| Supermicro    | X9DRE-TF+/X9DR7-TF+         | Server      | [1274766930](https://linux-hardware.org/?probe=1274766930) | Nov 02, 2023 |
| Lenovo        | ThinkPad L460 20FVS12A00    | Notebook    | [fab360eece](https://linux-hardware.org/?probe=fab360eece) | Nov 02, 2023 |
| Lenovo        | ThinkPad L460 20FVS12A00    | Notebook    | [a2273dea0e](https://linux-hardware.org/?probe=a2273dea0e) | Nov 01, 2023 |
| ASRockRack    | X570D4U-2L2T/BCM            | Server      | [66607ff17c](https://linux-hardware.org/?probe=66607ff17c) | Oct 31, 2023 |
| Dell          | Latitude 7430               | Notebook    | [3e9717ffe0](https://linux-hardware.org/?probe=3e9717ffe0) | Oct 31, 2023 |
| ASRock        | H110 Pro BTC+               | Desktop     | [c889a29b7f](https://linux-hardware.org/?probe=c889a29b7f) | Oct 31, 2023 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | Notebook    | [3fe09c27c2](https://linux-hardware.org/?probe=3fe09c27c2) | Oct 29, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [12d5c69b6a](https://linux-hardware.org/?probe=12d5c69b6a) | Oct 29, 2023 |
| ASUSTek       | ZenBook UX431FA_UX431FA     | Notebook    | [8f56c1076b](https://linux-hardware.org/?probe=8f56c1076b) | Oct 28, 2023 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | Notebook    | [0277411276](https://linux-hardware.org/?probe=0277411276) | Oct 28, 2023 |
| Dell          | Latitude 7430               | Notebook    | [e9cfada6a4](https://linux-hardware.org/?probe=e9cfada6a4) | Oct 26, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [4f269eeaa7](https://linux-hardware.org/?probe=4f269eeaa7) | Oct 23, 2023 |
| Dell          | Latitude E7240              | Notebook    | [6fead70e93](https://linux-hardware.org/?probe=6fead70e93) | Oct 23, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [6f65dcd448](https://linux-hardware.org/?probe=6f65dcd448) | Oct 23, 2023 |
| ASUSTek       | X550JX                      | Notebook    | [b1a9053ac6](https://linux-hardware.org/?probe=b1a9053ac6) | Oct 22, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [d19756d24b](https://linux-hardware.org/?probe=d19756d24b) | Oct 22, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3ba4cde45a](https://linux-hardware.org/?probe=3ba4cde45a) | Oct 22, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [b1a3bf1a75](https://linux-hardware.org/?probe=b1a3bf1a75) | Oct 21, 2023 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [36827ef46c](https://linux-hardware.org/?probe=36827ef46c) | Oct 21, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [edefe667a4](https://linux-hardware.org/?probe=edefe667a4) | Oct 21, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [95c5dfe865](https://linux-hardware.org/?probe=95c5dfe865) | Oct 19, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [7fab57f39a](https://linux-hardware.org/?probe=7fab57f39a) | Oct 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ed3ce7aaa6](https://linux-hardware.org/?probe=ed3ce7aaa6) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [9d7f8ee0f1](https://linux-hardware.org/?probe=9d7f8ee0f1) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [8422037a50](https://linux-hardware.org/?probe=8422037a50) | Oct 17, 2023 |
| Lenovo        | ThinkPad T480 20L50101US    | Notebook    | [c6913c1b75](https://linux-hardware.org/?probe=c6913c1b75) | Oct 16, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a2d4463dfc](https://linux-hardware.org/?probe=a2d4463dfc) | Oct 12, 2023 |
| ASUSTek       | Pro WS W480-ACE             | Desktop     | [110e9a1566](https://linux-hardware.org/?probe=110e9a1566) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [d44d655589](https://linux-hardware.org/?probe=d44d655589) | Oct 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4ce0d26e3c](https://linux-hardware.org/?probe=4ce0d26e3c) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [5089a21326](https://linux-hardware.org/?probe=5089a21326) | Oct 07, 2023 |
| HP            | ProBook 6450b               | Notebook    | [70e33902c1](https://linux-hardware.org/?probe=70e33902c1) | Oct 07, 2023 |
| HP            | ProBook 6450b               | Notebook    | [ddd8417a28](https://linux-hardware.org/?probe=ddd8417a28) | Oct 07, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5181895f59](https://linux-hardware.org/?probe=5181895f59) | Oct 06, 2023 |
| Dell          | Precision 5530              | Notebook    | [38fdcea75f](https://linux-hardware.org/?probe=38fdcea75f) | Oct 06, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [560aec8a01](https://linux-hardware.org/?probe=560aec8a01) | Oct 06, 2023 |
| ASUSTek       | G750JH                      | Notebook    | [66396378dd](https://linux-hardware.org/?probe=66396378dd) | Oct 06, 2023 |
| Dell          | Latitude E6540              | Notebook    | [78c4b71781](https://linux-hardware.org/?probe=78c4b71781) | Oct 04, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [bbff3c4662](https://linux-hardware.org/?probe=bbff3c4662) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [82820de211](https://linux-hardware.org/?probe=82820de211) | Oct 03, 2023 |
| Dell          | Latitude E6540              | Notebook    | [290b4bd42e](https://linux-hardware.org/?probe=290b4bd42e) | Oct 03, 2023 |
| Lenovo        | ThinkPad L430 24662W2       | Notebook    | [21ee2a6e8f](https://linux-hardware.org/?probe=21ee2a6e8f) | Oct 03, 2023 |
| Lenovo        | ThinkPad L460 20FVS12A00    | Notebook    | [ad3d8f3522](https://linux-hardware.org/?probe=ad3d8f3522) | Oct 02, 2023 |
| HP            | 212B                        | Desktop     | [079a0c34d3](https://linux-hardware.org/?probe=079a0c34d3) | Oct 02, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [75667a0116](https://linux-hardware.org/?probe=75667a0116) | Oct 02, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [49375c2b21](https://linux-hardware.org/?probe=49375c2b21) | Oct 02, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [336d3c6536](https://linux-hardware.org/?probe=336d3c6536) | Oct 02, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [7144e87b6b](https://linux-hardware.org/?probe=7144e87b6b) | Oct 02, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [21e6d88bd9](https://linux-hardware.org/?probe=21e6d88bd9) | Oct 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [5442de3655](https://linux-hardware.org/?probe=5442de3655) | Oct 02, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [42f7e22cf3](https://linux-hardware.org/?probe=42f7e22cf3) | Oct 02, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [5f76307503](https://linux-hardware.org/?probe=5f76307503) | Oct 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3e13770075](https://linux-hardware.org/?probe=3e13770075) | Oct 01, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [83d91ea2fe](https://linux-hardware.org/?probe=83d91ea2fe) | Sep 30, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [0fad85dfc9](https://linux-hardware.org/?probe=0fad85dfc9) | Sep 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [a36938e994](https://linux-hardware.org/?probe=a36938e994) | Sep 30, 2023 |
| MSI           | Z68A-GD65                   | Desktop     | [c0f968740b](https://linux-hardware.org/?probe=c0f968740b) | Sep 29, 2023 |
| Dell          | Latitude 5430               | Notebook    | [583aa8cf02](https://linux-hardware.org/?probe=583aa8cf02) | Sep 29, 2023 |
| Intel         | SharkBay Platform           | Notebook    | [2406bf1c0d](https://linux-hardware.org/?probe=2406bf1c0d) | Sep 29, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [960cd34617](https://linux-hardware.org/?probe=960cd34617) | Sep 29, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [a5e7296c29](https://linux-hardware.org/?probe=a5e7296c29) | Sep 28, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [2a507c567b](https://linux-hardware.org/?probe=2a507c567b) | Sep 28, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b69e9b97ec](https://linux-hardware.org/?probe=b69e9b97ec) | Sep 26, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [ab332c2dcb](https://linux-hardware.org/?probe=ab332c2dcb) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [f934062b23](https://linux-hardware.org/?probe=f934062b23) | Sep 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c6dc860de5](https://linux-hardware.org/?probe=c6dc860de5) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [7aa2ea2853](https://linux-hardware.org/?probe=7aa2ea2853) | Sep 24, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [45c1c156af](https://linux-hardware.org/?probe=45c1c156af) | Sep 23, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [220a0f8733](https://linux-hardware.org/?probe=220a0f8733) | Sep 23, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [908d74fdc8](https://linux-hardware.org/?probe=908d74fdc8) | Sep 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [987e4c193b](https://linux-hardware.org/?probe=987e4c193b) | Sep 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [1180346586](https://linux-hardware.org/?probe=1180346586) | Sep 19, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [96a6758726](https://linux-hardware.org/?probe=96a6758726) | Sep 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F7... | Notebook    | [2c90700f4f](https://linux-hardware.org/?probe=2c90700f4f) | Sep 16, 2023 |
| Acer          | Predator PH317-53           | Notebook    | [13e8645c6c](https://linux-hardware.org/?probe=13e8645c6c) | Sep 16, 2023 |
| Acer          | Predator PH317-53           | Notebook    | [183adfb8b6](https://linux-hardware.org/?probe=183adfb8b6) | Sep 16, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [35bc7480cb](https://linux-hardware.org/?probe=35bc7480cb) | Sep 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [de94d54f00](https://linux-hardware.org/?probe=de94d54f00) | Sep 15, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [d1ef9fa580](https://linux-hardware.org/?probe=d1ef9fa580) | Sep 15, 2023 |
| Lenovo        | ThinkPad E14 20RA005MMX     | Notebook    | [d9d0c012b3](https://linux-hardware.org/?probe=d9d0c012b3) | Sep 13, 2023 |
| Lenovo        | ThinkPad X260 20F5S7QT00    | Notebook    | [8475dc74df](https://linux-hardware.org/?probe=8475dc74df) | Sep 09, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [83b997b3ab](https://linux-hardware.org/?probe=83b997b3ab) | Sep 09, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [c936953cf7](https://linux-hardware.org/?probe=c936953cf7) | Sep 08, 2023 |
| HP            | EliteBook x360 1030 G4      | Convertible | [f4ddf6b6ec](https://linux-hardware.org/?probe=f4ddf6b6ec) | Sep 08, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [362b2dadfc](https://linux-hardware.org/?probe=362b2dadfc) | Sep 08, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [7a0e6bd16c](https://linux-hardware.org/?probe=7a0e6bd16c) | Sep 07, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [bedbf331b0](https://linux-hardware.org/?probe=bedbf331b0) | Sep 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [0434d08b59](https://linux-hardware.org/?probe=0434d08b59) | Sep 07, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [96d3b5db5c](https://linux-hardware.org/?probe=96d3b5db5c) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8c22ca23f2](https://linux-hardware.org/?probe=8c22ca23f2) | Sep 07, 2023 |
| Acer          | Swift SF314-51              | Notebook    | [7e7c32364d](https://linux-hardware.org/?probe=7e7c32364d) | Sep 06, 2023 |
| Panasonic     | CF-191HACHFN                | Notebook    | [2c3ca0bdcf](https://linux-hardware.org/?probe=2c3ca0bdcf) | Sep 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c06fdd0648](https://linux-hardware.org/?probe=c06fdd0648) | Sep 05, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [59b20fdfab](https://linux-hardware.org/?probe=59b20fdfab) | Sep 04, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [6bf9db20f8](https://linux-hardware.org/?probe=6bf9db20f8) | Sep 04, 2023 |
| Star Labs     | StarBook                    | Notebook    | [ac568bfcd4](https://linux-hardware.org/?probe=ac568bfcd4) | Sep 03, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [499d13e212](https://linux-hardware.org/?probe=499d13e212) | Sep 03, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [9607f36921](https://linux-hardware.org/?probe=9607f36921) | Sep 03, 2023 |
| Dell          | Latitude 3540               | Notebook    | [e7d1d4f160](https://linux-hardware.org/?probe=e7d1d4f160) | Sep 03, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [72c5c271b6](https://linux-hardware.org/?probe=72c5c271b6) | Sep 03, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [19e076e3e1](https://linux-hardware.org/?probe=19e076e3e1) | Sep 01, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [ef4c22cc94](https://linux-hardware.org/?probe=ef4c22cc94) | Sep 01, 2023 |
| Google        | Galtic                      | Notebook    | [e9ccd3a286](https://linux-hardware.org/?probe=e9ccd3a286) | Sep 01, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [7f9db7db99](https://linux-hardware.org/?probe=7f9db7db99) | Sep 01, 2023 |
| MSI           | X299 SLI PLUS               | Desktop     | [572982299a](https://linux-hardware.org/?probe=572982299a) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [44e98cb157](https://linux-hardware.org/?probe=44e98cb157) | Aug 29, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [771adfa310](https://linux-hardware.org/?probe=771adfa310) | Aug 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [3067310cf8](https://linux-hardware.org/?probe=3067310cf8) | Aug 25, 2023 |
| Dell          | Latitude E7240              | Notebook    | [cb61859037](https://linux-hardware.org/?probe=cb61859037) | Aug 24, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [68c01672c3](https://linux-hardware.org/?probe=68c01672c3) | Aug 24, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [5a388c766a](https://linux-hardware.org/?probe=5a388c766a) | Aug 23, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [10345216a9](https://linux-hardware.org/?probe=10345216a9) | Aug 22, 2023 |
| Dell          | Precision M4700             | Notebook    | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| eMachines     | E520 V1.06                  | Notebook    | [bd63874856](https://linux-hardware.org/?probe=bd63874856) | Aug 20, 2023 |
| Dell          | Precision 5520              | Notebook    | [42587aac96](https://linux-hardware.org/?probe=42587aac96) | Aug 20, 2023 |
| Dell          | Precision 5520              | Notebook    | [bec735d800](https://linux-hardware.org/?probe=bec735d800) | Aug 20, 2023 |
| Lenovo        | ThinkPad L430 24662W2       | Notebook    | [10b7d76c38](https://linux-hardware.org/?probe=10b7d76c38) | Aug 20, 2023 |
| Lenovo        | V320-17ISK 81B6             | Notebook    | [cc96bcc8d9](https://linux-hardware.org/?probe=cc96bcc8d9) | Aug 19, 2023 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | Notebook    | [41b00dc8b3](https://linux-hardware.org/?probe=41b00dc8b3) | Aug 18, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [e0a9b4c86f](https://linux-hardware.org/?probe=e0a9b4c86f) | Aug 18, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [b80142953c](https://linux-hardware.org/?probe=b80142953c) | Aug 17, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [1ba4da3bec](https://linux-hardware.org/?probe=1ba4da3bec) | Aug 17, 2023 |
| Raspberry ... | Raspberry Pi Model B Plu... | Soc         | [6ed8f5fce9](https://linux-hardware.org/?probe=6ed8f5fce9) | Aug 16, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [b2377a274f](https://linux-hardware.org/?probe=b2377a274f) | Aug 16, 2023 |
| Intel         | X99                         | Desktop     | [64c64eec64](https://linux-hardware.org/?probe=64c64eec64) | Aug 16, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [2412623eac](https://linux-hardware.org/?probe=2412623eac) | Aug 15, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [d7f0d8e9cd](https://linux-hardware.org/?probe=d7f0d8e9cd) | Aug 15, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [48ae062db8](https://linux-hardware.org/?probe=48ae062db8) | Aug 15, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [88056b62e3](https://linux-hardware.org/?probe=88056b62e3) | Aug 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0c0df32662](https://linux-hardware.org/?probe=0c0df32662) | Aug 12, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [90816726b0](https://linux-hardware.org/?probe=90816726b0) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | Desktop     | [8903899ce9](https://linux-hardware.org/?probe=8903899ce9) | Aug 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [ee1a7cb0aa](https://linux-hardware.org/?probe=ee1a7cb0aa) | Aug 11, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [cec1060cd6](https://linux-hardware.org/?probe=cec1060cd6) | Aug 10, 2023 |
| ASRock        | H77M-ITX                    | Desktop     | [01dc3bfc4b](https://linux-hardware.org/?probe=01dc3bfc4b) | Aug 09, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [33beb40ea6](https://linux-hardware.org/?probe=33beb40ea6) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [5fe9a17769](https://linux-hardware.org/?probe=5fe9a17769) | Aug 07, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [9f230de889](https://linux-hardware.org/?probe=9f230de889) | Aug 07, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f529a830c](https://linux-hardware.org/?probe=2f529a830c) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [9d00f10bab](https://linux-hardware.org/?probe=9d00f10bab) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [24dc4f34a2](https://linux-hardware.org/?probe=24dc4f34a2) | Aug 05, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [87fc943eb1](https://linux-hardware.org/?probe=87fc943eb1) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [f7354ee466](https://linux-hardware.org/?probe=f7354ee466) | Aug 04, 2023 |
| HP            | 8620                        | Mini pc     | [3203f90412](https://linux-hardware.org/?probe=3203f90412) | Aug 04, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [4077d11575](https://linux-hardware.org/?probe=4077d11575) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [31d1c3bfbc](https://linux-hardware.org/?probe=31d1c3bfbc) | Aug 03, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ec5ec88e59](https://linux-hardware.org/?probe=ec5ec88e59) | Aug 02, 2023 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [ab8efe91ea](https://linux-hardware.org/?probe=ab8efe91ea) | Jul 30, 2023 |
| ASUSTek       | UX461UN                     | Convertible | [8f48f3562c](https://linux-hardware.org/?probe=8f48f3562c) | Jul 30, 2023 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [30784ff697](https://linux-hardware.org/?probe=30784ff697) | Jul 30, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [edf7fd3a91](https://linux-hardware.org/?probe=edf7fd3a91) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [a5467c396a](https://linux-hardware.org/?probe=a5467c396a) | Jul 28, 2023 |
| HP            | ZBook 15u G5                | Notebook    | [1b0bb754bc](https://linux-hardware.org/?probe=1b0bb754bc) | Jul 28, 2023 |
| HP            | ZBook 15u G5                | Notebook    | [54684f905d](https://linux-hardware.org/?probe=54684f905d) | Jul 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [aac37c9ed6](https://linux-hardware.org/?probe=aac37c9ed6) | Jul 27, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [9b1ae569c1](https://linux-hardware.org/?probe=9b1ae569c1) | Jul 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f3cc428da8](https://linux-hardware.org/?probe=f3cc428da8) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6c03bf1d0d](https://linux-hardware.org/?probe=6c03bf1d0d) | Jul 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7ee6422d01](https://linux-hardware.org/?probe=7ee6422d01) | Jul 25, 2023 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [405387be09](https://linux-hardware.org/?probe=405387be09) | Jul 23, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [62efe51727](https://linux-hardware.org/?probe=62efe51727) | Jul 23, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ecce500445](https://linux-hardware.org/?probe=ecce500445) | Jul 22, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [f4e52f14b5](https://linux-hardware.org/?probe=f4e52f14b5) | Jul 22, 2023 |
| MSI           | GL72 6QF                    | Notebook    | [0484bc209c](https://linux-hardware.org/?probe=0484bc209c) | Jul 21, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [c81d7372fb](https://linux-hardware.org/?probe=c81d7372fb) | Jul 21, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [a05f11a6b4](https://linux-hardware.org/?probe=a05f11a6b4) | Jul 20, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [2e18524ef0](https://linux-hardware.org/?probe=2e18524ef0) | Jul 20, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [e0303e4012](https://linux-hardware.org/?probe=e0303e4012) | Jul 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [15ef7f9ce4](https://linux-hardware.org/?probe=15ef7f9ce4) | Jul 16, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [abf1be3307](https://linux-hardware.org/?probe=abf1be3307) | Jul 16, 2023 |
| Supermicro    | X9DRT                       | Server      | [b95f28343e](https://linux-hardware.org/?probe=b95f28343e) | Jul 14, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [e7898eacb6](https://linux-hardware.org/?probe=e7898eacb6) | Jul 13, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e241cdbe45](https://linux-hardware.org/?probe=e241cdbe45) | Jul 12, 2023 |
| Lenovo        | ThinkPad 8 20BN001RMN       | Tablet      | [6801265f9f](https://linux-hardware.org/?probe=6801265f9f) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f99bab3454](https://linux-hardware.org/?probe=f99bab3454) | Jul 12, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [2c4a8d9d63](https://linux-hardware.org/?probe=2c4a8d9d63) | Jul 12, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [333813fa10](https://linux-hardware.org/?probe=333813fa10) | Jul 11, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [66fb93438f](https://linux-hardware.org/?probe=66fb93438f) | Jul 11, 2023 |
| Dell          | Precision 5680              | Notebook    | [e1363522ee](https://linux-hardware.org/?probe=e1363522ee) | Jul 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [0fbc8ca097](https://linux-hardware.org/?probe=0fbc8ca097) | Jul 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [fddbab0cf6](https://linux-hardware.org/?probe=fddbab0cf6) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [d7209e7141](https://linux-hardware.org/?probe=d7209e7141) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [33aa3fcdbc](https://linux-hardware.org/?probe=33aa3fcdbc) | Jul 10, 2023 |
| Dell          | Latitude 7370               | Notebook    | [d47bb47c61](https://linux-hardware.org/?probe=d47bb47c61) | Jul 10, 2023 |
| MSI           | GL72 6QF                    | Notebook    | [487fd6cc0e](https://linux-hardware.org/?probe=487fd6cc0e) | Jul 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [30658f7ab7](https://linux-hardware.org/?probe=30658f7ab7) | Jul 09, 2023 |
| Acer          | Swift SF514-51              | Notebook    | [74c43ecd5c](https://linux-hardware.org/?probe=74c43ecd5c) | Jul 08, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [220629a068](https://linux-hardware.org/?probe=220629a068) | Jul 08, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f86f946540](https://linux-hardware.org/?probe=f86f946540) | Jul 08, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ee299280f8](https://linux-hardware.org/?probe=ee299280f8) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [cbc100e6b1](https://linux-hardware.org/?probe=cbc100e6b1) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [3177785c7f](https://linux-hardware.org/?probe=3177785c7f) | Jul 07, 2023 |
| Dell          | Latitude 7480               | Notebook    | [4c07c7b04a](https://linux-hardware.org/?probe=4c07c7b04a) | Jul 07, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [2fa3986e67](https://linux-hardware.org/?probe=2fa3986e67) | Jul 05, 2023 |
| ASUSTek       | X556UR                      | Notebook    | [79d8c96e3c](https://linux-hardware.org/?probe=79d8c96e3c) | Jul 05, 2023 |
| Multicom N... | Multicom Talisa U235        | Tablet      | [155825a56a](https://linux-hardware.org/?probe=155825a56a) | Jul 04, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [156f923a72](https://linux-hardware.org/?probe=156f923a72) | Jul 04, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [205dfa0056](https://linux-hardware.org/?probe=205dfa0056) | Jul 03, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [40ca2e97cc](https://linux-hardware.org/?probe=40ca2e97cc) | Jul 03, 2023 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | Notebook    | [18230f7c64](https://linux-hardware.org/?probe=18230f7c64) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [69c34bf001](https://linux-hardware.org/?probe=69c34bf001) | Jul 02, 2023 |
| Multicom N... | Multicom Talisa U235        | Tablet      | [6b9216eef4](https://linux-hardware.org/?probe=6b9216eef4) | Jul 02, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [8f6145f929](https://linux-hardware.org/?probe=8f6145f929) | Jul 02, 2023 |
| Multicom N... | Multicom Talisa U235        | Tablet      | [dba19e3fa3](https://linux-hardware.org/?probe=dba19e3fa3) | Jul 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [556867d0f2](https://linux-hardware.org/?probe=556867d0f2) | Jul 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [b36612c9e4](https://linux-hardware.org/?probe=b36612c9e4) | Jul 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c2b529a2ee](https://linux-hardware.org/?probe=c2b529a2ee) | Jul 02, 2023 |
| Dell          | Latitude 7390               | Notebook    | [ef05796af7](https://linux-hardware.org/?probe=ef05796af7) | Jul 01, 2023 |
| Dell          | Latitude 7390               | Notebook    | [ea8982e574](https://linux-hardware.org/?probe=ea8982e574) | Jul 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d7efa66a54](https://linux-hardware.org/?probe=d7efa66a54) | Jul 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8ea4c888cf](https://linux-hardware.org/?probe=8ea4c888cf) | Jul 01, 2023 |
| MSI           | Katana GF66 11UG            | Notebook    | [e9f98cc102](https://linux-hardware.org/?probe=e9f98cc102) | Jun 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [77e6b09eb9](https://linux-hardware.org/?probe=77e6b09eb9) | Jun 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [bb8a8eac46](https://linux-hardware.org/?probe=bb8a8eac46) | Jun 30, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [c44fba1fa2](https://linux-hardware.org/?probe=c44fba1fa2) | Jun 29, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [69cb8803e1](https://linux-hardware.org/?probe=69cb8803e1) | Jun 29, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ff560998d8](https://linux-hardware.org/?probe=ff560998d8) | Jun 28, 2023 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [fee1e04033](https://linux-hardware.org/?probe=fee1e04033) | Jun 28, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [0294ef5e1f](https://linux-hardware.org/?probe=0294ef5e1f) | Jun 28, 2023 |
| Supermicro    | X9DRT                       | Server      | [807e745cb1](https://linux-hardware.org/?probe=807e745cb1) | Jun 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [ef2e8da48a](https://linux-hardware.org/?probe=ef2e8da48a) | Jun 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a974c1b82e](https://linux-hardware.org/?probe=a974c1b82e) | Jun 26, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [31fc00f1ac](https://linux-hardware.org/?probe=31fc00f1ac) | Jun 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1c648f1f3e](https://linux-hardware.org/?probe=1c648f1f3e) | Jun 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [684000f2c5](https://linux-hardware.org/?probe=684000f2c5) | Jun 25, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [6cb0af7fea](https://linux-hardware.org/?probe=6cb0af7fea) | Jun 24, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [703e12843e](https://linux-hardware.org/?probe=703e12843e) | Jun 23, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [7ce8bcbc26](https://linux-hardware.org/?probe=7ce8bcbc26) | Jun 23, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [fed92425f3](https://linux-hardware.org/?probe=fed92425f3) | Jun 23, 2023 |
| Dell          | Latitude E7240              | Notebook    | [f8b3fce80b](https://linux-hardware.org/?probe=f8b3fce80b) | Jun 21, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [8d35565fd3](https://linux-hardware.org/?probe=8d35565fd3) | Jun 20, 2023 |
| Supermicro    | X9DRT                       | Server      | [5b25db1cae](https://linux-hardware.org/?probe=5b25db1cae) | Jun 20, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [d4470db5d3](https://linux-hardware.org/?probe=d4470db5d3) | Jun 20, 2023 |
| Lenovo        | ThinkPad L490 20Q5001YMX    | Notebook    | [c04ebf8de3](https://linux-hardware.org/?probe=c04ebf8de3) | Jun 20, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [058b2ea405](https://linux-hardware.org/?probe=058b2ea405) | Jun 20, 2023 |
| MSI           | X299 TOMAHAWK               | Desktop     | [aa2a65c324](https://linux-hardware.org/?probe=aa2a65c324) | Jun 19, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [00e6086d35](https://linux-hardware.org/?probe=00e6086d35) | Jun 19, 2023 |
| Supermicro    | X9DRT                       | Server      | [7efb88b5d7](https://linux-hardware.org/?probe=7efb88b5d7) | Jun 19, 2023 |
| Multicom N... | Multicom Talisa U235        | Tablet      | [50d54b5967](https://linux-hardware.org/?probe=50d54b5967) | Jun 18, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [3dc796f9d3](https://linux-hardware.org/?probe=3dc796f9d3) | Jun 18, 2023 |
| Multicom N... | Multicom Talisa U235        | Tablet      | [cb5806fefc](https://linux-hardware.org/?probe=cb5806fefc) | Jun 18, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [b61d1afa3c](https://linux-hardware.org/?probe=b61d1afa3c) | Jun 17, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [1bb6017aaa](https://linux-hardware.org/?probe=1bb6017aaa) | Jun 17, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [87cd6547ad](https://linux-hardware.org/?probe=87cd6547ad) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [4fac659113](https://linux-hardware.org/?probe=4fac659113) | Jun 13, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [785b0849fd](https://linux-hardware.org/?probe=785b0849fd) | Jun 13, 2023 |
| MSI           | P67A-C45                    | Desktop     | [4f3aa2017f](https://linux-hardware.org/?probe=4f3aa2017f) | Jun 13, 2023 |
| Lenovo        | G565 4385                   | Notebook    | [2fd61f3fc5](https://linux-hardware.org/?probe=2fd61f3fc5) | Jun 11, 2023 |
| ASUSTek       | GX501VIK                    | Notebook    | [e54a895262](https://linux-hardware.org/?probe=e54a895262) | Jun 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [1fd265b6d8](https://linux-hardware.org/?probe=1fd265b6d8) | Jun 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1c5e1b092a](https://linux-hardware.org/?probe=1c5e1b092a) | Jun 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [4ab556e4b8](https://linux-hardware.org/?probe=4ab556e4b8) | Jun 10, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [212c44c43f](https://linux-hardware.org/?probe=212c44c43f) | Jun 10, 2023 |
| Dell          | Latitude E7240              | Notebook    | [e21cc2151b](https://linux-hardware.org/?probe=e21cc2151b) | Jun 08, 2023 |
| MSI           | P67A-C45                    | Desktop     | [673f3774bc](https://linux-hardware.org/?probe=673f3774bc) | Jun 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d70fe31101](https://linux-hardware.org/?probe=d70fe31101) | Jun 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [3c3708dcec](https://linux-hardware.org/?probe=3c3708dcec) | Jun 06, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [0763f751ac](https://linux-hardware.org/?probe=0763f751ac) | Jun 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [79b80daf83](https://linux-hardware.org/?probe=79b80daf83) | Jun 05, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [36173d5a42](https://linux-hardware.org/?probe=36173d5a42) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [a39c2e8d55](https://linux-hardware.org/?probe=a39c2e8d55) | Jun 04, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [d09ba05086](https://linux-hardware.org/?probe=d09ba05086) | Jun 03, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [9f13a5184c](https://linux-hardware.org/?probe=9f13a5184c) | Jun 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [58f688ebc5](https://linux-hardware.org/?probe=58f688ebc5) | Jun 02, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [02d5f4b511](https://linux-hardware.org/?probe=02d5f4b511) | Jun 01, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [835a44b010](https://linux-hardware.org/?probe=835a44b010) | Jun 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b951e6223c](https://linux-hardware.org/?probe=b951e6223c) | Jun 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [df9086deb4](https://linux-hardware.org/?probe=df9086deb4) | Jun 01, 2023 |
| Sony          | SVT1121B2EW                 | Notebook    | [67819a243c](https://linux-hardware.org/?probe=67819a243c) | May 31, 2023 |
| ASUSTek       | ROG Strix G513RS_G513RS     | Notebook    | [69b1782cce](https://linux-hardware.org/?probe=69b1782cce) | May 31, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3404cb6c67](https://linux-hardware.org/?probe=3404cb6c67) | May 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a908da319](https://linux-hardware.org/?probe=4a908da319) | May 31, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [b4b6bfda0c](https://linux-hardware.org/?probe=b4b6bfda0c) | May 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8b96413dfd](https://linux-hardware.org/?probe=8b96413dfd) | May 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [ffe895debc](https://linux-hardware.org/?probe=ffe895debc) | May 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [0b7f7fb99a](https://linux-hardware.org/?probe=0b7f7fb99a) | May 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [38936854c8](https://linux-hardware.org/?probe=38936854c8) | May 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [439a2f1c9e](https://linux-hardware.org/?probe=439a2f1c9e) | May 28, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [7e895c167b](https://linux-hardware.org/?probe=7e895c167b) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [526503fef7](https://linux-hardware.org/?probe=526503fef7) | May 27, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [f7fddb36e8](https://linux-hardware.org/?probe=f7fddb36e8) | May 26, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [362ad8bcaf](https://linux-hardware.org/?probe=362ad8bcaf) | May 23, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | Notebook    | [cc966f1ede](https://linux-hardware.org/?probe=cc966f1ede) | May 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ec7d8d12e1](https://linux-hardware.org/?probe=ec7d8d12e1) | May 23, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [1b7089a58b](https://linux-hardware.org/?probe=1b7089a58b) | May 23, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [1fd2d41164](https://linux-hardware.org/?probe=1fd2d41164) | May 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ecc77ee7a9](https://linux-hardware.org/?probe=ecc77ee7a9) | May 22, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [5534aabaf1](https://linux-hardware.org/?probe=5534aabaf1) | May 21, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [3f5a6968d4](https://linux-hardware.org/?probe=3f5a6968d4) | May 21, 2023 |
| Dell          | Latitude 7370               | Notebook    | [756455c062](https://linux-hardware.org/?probe=756455c062) | May 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a100e90e0b](https://linux-hardware.org/?probe=a100e90e0b) | May 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [9b29aafd95](https://linux-hardware.org/?probe=9b29aafd95) | May 16, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [9ed74f5d63](https://linux-hardware.org/?probe=9ed74f5d63) | May 15, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [b4ffbbf7d3](https://linux-hardware.org/?probe=b4ffbbf7d3) | May 15, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d4344603b6](https://linux-hardware.org/?probe=d4344603b6) | May 15, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [14928b0276](https://linux-hardware.org/?probe=14928b0276) | May 15, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [36f918cce7](https://linux-hardware.org/?probe=36f918cce7) | May 15, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [1ba0adc2ba](https://linux-hardware.org/?probe=1ba0adc2ba) | May 15, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [903ece310a](https://linux-hardware.org/?probe=903ece310a) | May 14, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [2d942e3436](https://linux-hardware.org/?probe=2d942e3436) | May 14, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [6bfe747b4d](https://linux-hardware.org/?probe=6bfe747b4d) | May 13, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [a15b90ff4b](https://linux-hardware.org/?probe=a15b90ff4b) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1d4c35daa6](https://linux-hardware.org/?probe=1d4c35daa6) | May 13, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [2e2b57870b](https://linux-hardware.org/?probe=2e2b57870b) | May 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4243b6a57b](https://linux-hardware.org/?probe=4243b6a57b) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2a1dfd0d0c](https://linux-hardware.org/?probe=2a1dfd0d0c) | May 12, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | Notebook    | [795e44d159](https://linux-hardware.org/?probe=795e44d159) | May 12, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [08adc44b64](https://linux-hardware.org/?probe=08adc44b64) | May 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e985d1beac](https://linux-hardware.org/?probe=e985d1beac) | May 12, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [184f099d28](https://linux-hardware.org/?probe=184f099d28) | May 10, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [1fe1a8fcd2](https://linux-hardware.org/?probe=1fe1a8fcd2) | May 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [727163d7b9](https://linux-hardware.org/?probe=727163d7b9) | May 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [96d3be3118](https://linux-hardware.org/?probe=96d3be3118) | May 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [dfdc7713b6](https://linux-hardware.org/?probe=dfdc7713b6) | May 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e2bbbffe45](https://linux-hardware.org/?probe=e2bbbffe45) | May 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [bc30b63ce3](https://linux-hardware.org/?probe=bc30b63ce3) | May 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [53c03d6942](https://linux-hardware.org/?probe=53c03d6942) | May 08, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [e40d8038da](https://linux-hardware.org/?probe=e40d8038da) | May 07, 2023 |
| ASUSTek       | E3 PRO GAMING V5            | Desktop     | [507036954e](https://linux-hardware.org/?probe=507036954e) | May 07, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [98008481eb](https://linux-hardware.org/?probe=98008481eb) | May 07, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ca84298b9d](https://linux-hardware.org/?probe=ca84298b9d) | May 05, 2023 |
| MSI           | X299 SLI PLUS               | Desktop     | [db983da641](https://linux-hardware.org/?probe=db983da641) | May 04, 2023 |
| Lenovo        | ThinkPad X230 23252CG       | Notebook    | [00ff147a9a](https://linux-hardware.org/?probe=00ff147a9a) | May 03, 2023 |
| Dell          | Precision 7510              | Notebook    | [1e73564cf9](https://linux-hardware.org/?probe=1e73564cf9) | May 03, 2023 |
| MSI           | MS-7025                     | Desktop     | [a15dc17cfc](https://linux-hardware.org/?probe=a15dc17cfc) | May 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [513f1e9efb](https://linux-hardware.org/?probe=513f1e9efb) | May 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [51c2405640](https://linux-hardware.org/?probe=51c2405640) | May 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f2c73a1fbb](https://linux-hardware.org/?probe=f2c73a1fbb) | May 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [be8b69e1b4](https://linux-hardware.org/?probe=be8b69e1b4) | May 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c33288abe2](https://linux-hardware.org/?probe=c33288abe2) | Apr 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [606b173cab](https://linux-hardware.org/?probe=606b173cab) | Apr 30, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | Notebook    | [3f6a89023c](https://linux-hardware.org/?probe=3f6a89023c) | Apr 28, 2023 |
| ASUSTek       | P9D-M Series                | Server      | [44b55b4721](https://linux-hardware.org/?probe=44b55b4721) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [e9f8ff6596](https://linux-hardware.org/?probe=e9f8ff6596) | Apr 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [853016bfe3](https://linux-hardware.org/?probe=853016bfe3) | Apr 27, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d6bf052a2f](https://linux-hardware.org/?probe=d6bf052a2f) | Apr 27, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [e14205d01a](https://linux-hardware.org/?probe=e14205d01a) | Apr 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [909ad37ab0](https://linux-hardware.org/?probe=909ad37ab0) | Apr 26, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [71983d0574](https://linux-hardware.org/?probe=71983d0574) | Apr 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [517a694a82](https://linux-hardware.org/?probe=517a694a82) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e7b20d71b7](https://linux-hardware.org/?probe=e7b20d71b7) | Apr 25, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [1d6082efe8](https://linux-hardware.org/?probe=1d6082efe8) | Apr 25, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [d86639089a](https://linux-hardware.org/?probe=d86639089a) | Apr 25, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [6f3f14d26d](https://linux-hardware.org/?probe=6f3f14d26d) | Apr 23, 2023 |
| Dell          | Latitude E6520              | Notebook    | [a8b5c5c3ad](https://linux-hardware.org/?probe=a8b5c5c3ad) | Apr 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [620334c0fc](https://linux-hardware.org/?probe=620334c0fc) | Apr 23, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | Notebook    | [2aa36b9cfd](https://linux-hardware.org/?probe=2aa36b9cfd) | Apr 22, 2023 |
| Dell          | Latitude 7420               | Notebook    | [480290fd34](https://linux-hardware.org/?probe=480290fd34) | Apr 19, 2023 |
| Xunlong       | Orange Pi One               | Soc         | [5542de4f04](https://linux-hardware.org/?probe=5542de4f04) | Apr 19, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [79029817b8](https://linux-hardware.org/?probe=79029817b8) | Apr 17, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [c622c73721](https://linux-hardware.org/?probe=c622c73721) | Apr 16, 2023 |
| HP            | Mini 210-1000               | Notebook    | [e8b0b26e10](https://linux-hardware.org/?probe=e8b0b26e10) | Apr 15, 2023 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [b66c208e18](https://linux-hardware.org/?probe=b66c208e18) | Apr 15, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [0f678c5ded](https://linux-hardware.org/?probe=0f678c5ded) | Apr 15, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [ee48e89e45](https://linux-hardware.org/?probe=ee48e89e45) | Apr 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [57cc389eff](https://linux-hardware.org/?probe=57cc389eff) | Apr 14, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [0d0a704eae](https://linux-hardware.org/?probe=0d0a704eae) | Apr 12, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [6d04c51285](https://linux-hardware.org/?probe=6d04c51285) | Apr 11, 2023 |
| MSI           | P67A-C45                    | Desktop     | [25a90d2595](https://linux-hardware.org/?probe=25a90d2595) | Apr 10, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [35d855a901](https://linux-hardware.org/?probe=35d855a901) | Apr 10, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6fe9dfd9a6](https://linux-hardware.org/?probe=6fe9dfd9a6) | Apr 10, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [332f3ed32f](https://linux-hardware.org/?probe=332f3ed32f) | Apr 09, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [d6cbe10f95](https://linux-hardware.org/?probe=d6cbe10f95) | Apr 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3f8d1c6a26](https://linux-hardware.org/?probe=3f8d1c6a26) | Apr 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [87f9a72b18](https://linux-hardware.org/?probe=87f9a72b18) | Apr 09, 2023 |
| HP            | 83E9                        | Desktop     | [4e62f72ee2](https://linux-hardware.org/?probe=4e62f72ee2) | Apr 08, 2023 |
| HP            | 83E9                        | Desktop     | [36fdd064cc](https://linux-hardware.org/?probe=36fdd064cc) | Apr 08, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0844c71fd0](https://linux-hardware.org/?probe=0844c71fd0) | Apr 07, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [7f55348e8b](https://linux-hardware.org/?probe=7f55348e8b) | Apr 05, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [c77ef60bcc](https://linux-hardware.org/?probe=c77ef60bcc) | Apr 05, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [3f750a4d82](https://linux-hardware.org/?probe=3f750a4d82) | Apr 05, 2023 |
| Dell          | Latitude E7240              | Notebook    | [fce3da8380](https://linux-hardware.org/?probe=fce3da8380) | Apr 04, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [edb2f4188e](https://linux-hardware.org/?probe=edb2f4188e) | Apr 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [94df0605ae](https://linux-hardware.org/?probe=94df0605ae) | Apr 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d6f7c92fc7](https://linux-hardware.org/?probe=d6f7c92fc7) | Apr 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a9aebc7f0](https://linux-hardware.org/?probe=4a9aebc7f0) | Apr 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [50e745e72a](https://linux-hardware.org/?probe=50e745e72a) | Apr 01, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [c76f4f4354](https://linux-hardware.org/?probe=c76f4f4354) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [3a74487ae8](https://linux-hardware.org/?probe=3a74487ae8) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [8bc61e0fcd](https://linux-hardware.org/?probe=8bc61e0fcd) | Mar 31, 2023 |
| ASRock        | Z87 Extreme11/ac            | Desktop     | [283593a105](https://linux-hardware.org/?probe=283593a105) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [0f26b74917](https://linux-hardware.org/?probe=0f26b74917) | Mar 30, 2023 |
| HP            | ProBook 6360b               | Notebook    | [cf027e03de](https://linux-hardware.org/?probe=cf027e03de) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [21515b7373](https://linux-hardware.org/?probe=21515b7373) | Mar 30, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [455ce69724](https://linux-hardware.org/?probe=455ce69724) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [080e22fdb2](https://linux-hardware.org/?probe=080e22fdb2) | Mar 30, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [493cabf3f8](https://linux-hardware.org/?probe=493cabf3f8) | Mar 29, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [aebe1aa0af](https://linux-hardware.org/?probe=aebe1aa0af) | Mar 29, 2023 |
| Acer          | Predator G3-605             | Desktop     | [8a1a55a1da](https://linux-hardware.org/?probe=8a1a55a1da) | Mar 29, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [0bc21ff162](https://linux-hardware.org/?probe=0bc21ff162) | Mar 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [df27b06a95](https://linux-hardware.org/?probe=df27b06a95) | Mar 28, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [761f7d71db](https://linux-hardware.org/?probe=761f7d71db) | Mar 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6b00de6bed](https://linux-hardware.org/?probe=6b00de6bed) | Mar 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [878fa94b87](https://linux-hardware.org/?probe=878fa94b87) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [a4f4013e4e](https://linux-hardware.org/?probe=a4f4013e4e) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [af88fa64c6](https://linux-hardware.org/?probe=af88fa64c6) | Mar 26, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | Desktop     | [0730a39a3a](https://linux-hardware.org/?probe=0730a39a3a) | Mar 26, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [dd6b3f7e44](https://linux-hardware.org/?probe=dd6b3f7e44) | Mar 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a607ac616d](https://linux-hardware.org/?probe=a607ac616d) | Mar 26, 2023 |
| Dell          | Latitude E7240              | Notebook    | [3d91b46fda](https://linux-hardware.org/?probe=3d91b46fda) | Mar 26, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [d1eea40764](https://linux-hardware.org/?probe=d1eea40764) | Mar 25, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [1f7c1bfa41](https://linux-hardware.org/?probe=1f7c1bfa41) | Mar 24, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | Notebook    | [640a9ac505](https://linux-hardware.org/?probe=640a9ac505) | Mar 24, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [aff8d829e0](https://linux-hardware.org/?probe=aff8d829e0) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [af60ed4cde](https://linux-hardware.org/?probe=af60ed4cde) | Mar 22, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B8M... | Notebook    | [4cb81db618](https://linux-hardware.org/?probe=4cb81db618) | Mar 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [93ff9f0891](https://linux-hardware.org/?probe=93ff9f0891) | Mar 19, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8892fdfdf9](https://linux-hardware.org/?probe=8892fdfdf9) | Mar 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [280e67175b](https://linux-hardware.org/?probe=280e67175b) | Mar 18, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f842840cc9](https://linux-hardware.org/?probe=f842840cc9) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [ac3bb4cdf4](https://linux-hardware.org/?probe=ac3bb4cdf4) | Mar 18, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [c20318c7c0](https://linux-hardware.org/?probe=c20318c7c0) | Mar 18, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d4ed345a47](https://linux-hardware.org/?probe=d4ed345a47) | Mar 14, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | Notebook    | [4853be01f6](https://linux-hardware.org/?probe=4853be01f6) | Mar 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [4a7d442938](https://linux-hardware.org/?probe=4a7d442938) | Mar 14, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [2d722aa2b5](https://linux-hardware.org/?probe=2d722aa2b5) | Mar 13, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | Notebook    | [41cee24fa8](https://linux-hardware.org/?probe=41cee24fa8) | Mar 13, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [b3c4766473](https://linux-hardware.org/?probe=b3c4766473) | Mar 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5434188010](https://linux-hardware.org/?probe=5434188010) | Mar 12, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c919e2da37](https://linux-hardware.org/?probe=c919e2da37) | Mar 12, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [e101a1c94c](https://linux-hardware.org/?probe=e101a1c94c) | Mar 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [089cafb799](https://linux-hardware.org/?probe=089cafb799) | Mar 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0f9de03c50](https://linux-hardware.org/?probe=0f9de03c50) | Mar 11, 2023 |
| HP            | Presario CQ57               | Notebook    | [87bbd773ac](https://linux-hardware.org/?probe=87bbd773ac) | Mar 09, 2023 |
| HP            | Presario CQ57               | Notebook    | [ffa117dde1](https://linux-hardware.org/?probe=ffa117dde1) | Mar 08, 2023 |
| HP            | Pavilion g7                 | Notebook    | [c5c1815bc8](https://linux-hardware.org/?probe=c5c1815bc8) | Mar 08, 2023 |
| MSI           | P67A-C45                    | Desktop     | [52e013338c](https://linux-hardware.org/?probe=52e013338c) | Mar 07, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [c3476001d3](https://linux-hardware.org/?probe=c3476001d3) | Mar 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [2246ef48c8](https://linux-hardware.org/?probe=2246ef48c8) | Mar 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bac7bd817d](https://linux-hardware.org/?probe=bac7bd817d) | Mar 07, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [73a3777352](https://linux-hardware.org/?probe=73a3777352) | Mar 06, 2023 |
| Dell          | Latitude 3510               | Notebook    | [983c57e386](https://linux-hardware.org/?probe=983c57e386) | Mar 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d725cc57f0](https://linux-hardware.org/?probe=d725cc57f0) | Mar 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [46d39caf5c](https://linux-hardware.org/?probe=46d39caf5c) | Mar 06, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [779113ef3c](https://linux-hardware.org/?probe=779113ef3c) | Mar 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b4110d0e0b](https://linux-hardware.org/?probe=b4110d0e0b) | Mar 04, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b20cfbdfa1](https://linux-hardware.org/?probe=b20cfbdfa1) | Mar 04, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [87cdc5bd5a](https://linux-hardware.org/?probe=87cdc5bd5a) | Mar 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ca004eceae](https://linux-hardware.org/?probe=ca004eceae) | Mar 03, 2023 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [2ac4801793](https://linux-hardware.org/?probe=2ac4801793) | Mar 03, 2023 |
| Unknown       | Rev.00                      | Desktop     | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [989eed6d5f](https://linux-hardware.org/?probe=989eed6d5f) | Mar 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [7efed287ee](https://linux-hardware.org/?probe=7efed287ee) | Mar 03, 2023 |
| GMKtec        | NucBox5                     | Notebook    | [fc11280fe6](https://linux-hardware.org/?probe=fc11280fe6) | Mar 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [833b6835b6](https://linux-hardware.org/?probe=833b6835b6) | Mar 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [ba4afa4d3b](https://linux-hardware.org/?probe=ba4afa4d3b) | Mar 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [7b7df086e0](https://linux-hardware.org/?probe=7b7df086e0) | Feb 28, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1b5fd0df61](https://linux-hardware.org/?probe=1b5fd0df61) | Feb 28, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f27314deb8](https://linux-hardware.org/?probe=f27314deb8) | Feb 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [97192c0aef](https://linux-hardware.org/?probe=97192c0aef) | Feb 26, 2023 |
| HP            | 3397                        | Desktop     | [a1840ee53d](https://linux-hardware.org/?probe=a1840ee53d) | Feb 26, 2023 |
| MSI           | B85M-E45                    | Desktop     | [a7748c0e8b](https://linux-hardware.org/?probe=a7748c0e8b) | Feb 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [87c5af58f5](https://linux-hardware.org/?probe=87c5af58f5) | Feb 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d6c6778bb7](https://linux-hardware.org/?probe=d6c6778bb7) | Feb 25, 2023 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [b101883e65](https://linux-hardware.org/?probe=b101883e65) | Feb 24, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7b4981d722](https://linux-hardware.org/?probe=7b4981d722) | Feb 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6e57f3a472](https://linux-hardware.org/?probe=6e57f3a472) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [142a12ded0](https://linux-hardware.org/?probe=142a12ded0) | Feb 23, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7f8278ff44](https://linux-hardware.org/?probe=7f8278ff44) | Feb 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [06138e952c](https://linux-hardware.org/?probe=06138e952c) | Feb 22, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [48817e62c6](https://linux-hardware.org/?probe=48817e62c6) | Feb 21, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [31d92eed57](https://linux-hardware.org/?probe=31d92eed57) | Feb 21, 2023 |
| MSI           | Z77A-GD65                   | Desktop     | [b5aebe4c92](https://linux-hardware.org/?probe=b5aebe4c92) | Feb 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5b33608a35](https://linux-hardware.org/?probe=5b33608a35) | Feb 20, 2023 |
| HP            | 0AECh D                     | Desktop     | [e844a614ec](https://linux-hardware.org/?probe=e844a614ec) | Feb 19, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [22fdba9212](https://linux-hardware.org/?probe=22fdba9212) | Feb 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f14a791491](https://linux-hardware.org/?probe=f14a791491) | Feb 18, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8dabbaa31c](https://linux-hardware.org/?probe=8dabbaa31c) | Feb 18, 2023 |
| Dell          | Latitude E7240              | Notebook    | [461873da2d](https://linux-hardware.org/?probe=461873da2d) | Feb 18, 2023 |
| Lenovo        | ThinkPad T520 4243W83       | Notebook    | [e6abb63f33](https://linux-hardware.org/?probe=e6abb63f33) | Feb 17, 2023 |
| Acer          | Aspire XC-230               | Desktop     | [e01d812902](https://linux-hardware.org/?probe=e01d812902) | Feb 17, 2023 |
| Acer          | Aspire XC-230               | Desktop     | [52b4d00a5a](https://linux-hardware.org/?probe=52b4d00a5a) | Feb 17, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [991b8b4361](https://linux-hardware.org/?probe=991b8b4361) | Feb 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8c3926e125](https://linux-hardware.org/?probe=8c3926e125) | Feb 17, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [014bf5276e](https://linux-hardware.org/?probe=014bf5276e) | Feb 17, 2023 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | Desktop     | [a370fca217](https://linux-hardware.org/?probe=a370fca217) | Feb 15, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bdb6e585b0](https://linux-hardware.org/?probe=bdb6e585b0) | Feb 15, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [387ec47efe](https://linux-hardware.org/?probe=387ec47efe) | Feb 14, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [139b92595a](https://linux-hardware.org/?probe=139b92595a) | Feb 12, 2023 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [b96dc1b089](https://linux-hardware.org/?probe=b96dc1b089) | Feb 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a5469c55ac](https://linux-hardware.org/?probe=a5469c55ac) | Feb 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6474c43d80](https://linux-hardware.org/?probe=6474c43d80) | Feb 11, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [49b463f14c](https://linux-hardware.org/?probe=49b463f14c) | Feb 10, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [79266ec6c7](https://linux-hardware.org/?probe=79266ec6c7) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [9a2b8045de](https://linux-hardware.org/?probe=9a2b8045de) | Feb 10, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [dcb244db8e](https://linux-hardware.org/?probe=dcb244db8e) | Feb 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [81a3a141ba](https://linux-hardware.org/?probe=81a3a141ba) | Feb 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5c5d5d4304](https://linux-hardware.org/?probe=5c5d5d4304) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [30db5b00f4](https://linux-hardware.org/?probe=30db5b00f4) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [e9fac81aa1](https://linux-hardware.org/?probe=e9fac81aa1) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [0e4bbcc317](https://linux-hardware.org/?probe=0e4bbcc317) | Feb 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d91fe3e151](https://linux-hardware.org/?probe=d91fe3e151) | Feb 07, 2023 |
| HP            | 3397                        | Desktop     | [2fb7638874](https://linux-hardware.org/?probe=2fb7638874) | Feb 06, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [a096de92f6](https://linux-hardware.org/?probe=a096de92f6) | Feb 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [3633683d62](https://linux-hardware.org/?probe=3633683d62) | Feb 04, 2023 |
| Dell          | Latitude E7240              | Notebook    | [da54499919](https://linux-hardware.org/?probe=da54499919) | Feb 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5e9c75d478](https://linux-hardware.org/?probe=5e9c75d478) | Feb 03, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c91d5b265b](https://linux-hardware.org/?probe=c91d5b265b) | Feb 02, 2023 |
| Dell          | Precision 3571              | Notebook    | [8ee8f6f768](https://linux-hardware.org/?probe=8ee8f6f768) | Feb 02, 2023 |
| Dell          | Precision 3571              | Notebook    | [9453f26568](https://linux-hardware.org/?probe=9453f26568) | Feb 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9b8d82dfcd](https://linux-hardware.org/?probe=9b8d82dfcd) | Feb 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [79c11af9ac](https://linux-hardware.org/?probe=79c11af9ac) | Feb 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [73bc9212a3](https://linux-hardware.org/?probe=73bc9212a3) | Jan 31, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a1f713f6e3](https://linux-hardware.org/?probe=a1f713f6e3) | Jan 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [24402e3d42](https://linux-hardware.org/?probe=24402e3d42) | Jan 30, 2023 |
| Dell          | Precision 5530              | Notebook    | [92399ea8dc](https://linux-hardware.org/?probe=92399ea8dc) | Jan 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f9a823cb38](https://linux-hardware.org/?probe=f9a823cb38) | Jan 29, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [d8de82d8c4](https://linux-hardware.org/?probe=d8de82d8c4) | Jan 29, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [327e2d4e3e](https://linux-hardware.org/?probe=327e2d4e3e) | Jan 28, 2023 |
| Dell          | Precision 5530              | Notebook    | [a9a54c5b7f](https://linux-hardware.org/?probe=a9a54c5b7f) | Jan 28, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [e5abc7fae4](https://linux-hardware.org/?probe=e5abc7fae4) | Jan 28, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d88cdedff3](https://linux-hardware.org/?probe=d88cdedff3) | Jan 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [415b96672b](https://linux-hardware.org/?probe=415b96672b) | Jan 26, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [293a308d86](https://linux-hardware.org/?probe=293a308d86) | Jan 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [82c3a80b93](https://linux-hardware.org/?probe=82c3a80b93) | Jan 25, 2023 |
| Dell          | Latitude E7240              | Notebook    | [2d488752b6](https://linux-hardware.org/?probe=2d488752b6) | Jan 25, 2023 |
| HP            | 8597                        | Desktop     | [8cc851783e](https://linux-hardware.org/?probe=8cc851783e) | Jan 24, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [10f149abb7](https://linux-hardware.org/?probe=10f149abb7) | Jan 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [43c26544a9](https://linux-hardware.org/?probe=43c26544a9) | Jan 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [9d44efa2f9](https://linux-hardware.org/?probe=9d44efa2f9) | Jan 24, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [a9b7912b52](https://linux-hardware.org/?probe=a9b7912b52) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R500... | Convertible | [7f5181d202](https://linux-hardware.org/?probe=7f5181d202) | Jan 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [279452d293](https://linux-hardware.org/?probe=279452d293) | Jan 23, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [eb10e25652](https://linux-hardware.org/?probe=eb10e25652) | Jan 23, 2023 |
| HP            | Notebook                    | Notebook    | [57bf6826ef](https://linux-hardware.org/?probe=57bf6826ef) | Jan 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b3d64d2496](https://linux-hardware.org/?probe=b3d64d2496) | Jan 22, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [8c4a855d8e](https://linux-hardware.org/?probe=8c4a855d8e) | Jan 21, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [e8a0c0066b](https://linux-hardware.org/?probe=e8a0c0066b) | Jan 21, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [20c0f69bb7](https://linux-hardware.org/?probe=20c0f69bb7) | Jan 21, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [0ea26f4af6](https://linux-hardware.org/?probe=0ea26f4af6) | Jan 20, 2023 |
| HP            | 3397                        | Desktop     | [39391f23c4](https://linux-hardware.org/?probe=39391f23c4) | Jan 20, 2023 |
| HP            | 3397                        | Desktop     | [7b05c1fdf9](https://linux-hardware.org/?probe=7b05c1fdf9) | Jan 20, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5f1447f874](https://linux-hardware.org/?probe=5f1447f874) | Jan 20, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7f36411ac1](https://linux-hardware.org/?probe=7f36411ac1) | Jan 20, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a4e01b187f](https://linux-hardware.org/?probe=a4e01b187f) | Jan 20, 2023 |
| Dell          | Latitude E7240              | Notebook    | [475187029d](https://linux-hardware.org/?probe=475187029d) | Jan 19, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8da5286795](https://linux-hardware.org/?probe=8da5286795) | Jan 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ec05dd5768](https://linux-hardware.org/?probe=ec05dd5768) | Jan 18, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [859d3c1b58](https://linux-hardware.org/?probe=859d3c1b58) | Jan 18, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [a8fbe01fc5](https://linux-hardware.org/?probe=a8fbe01fc5) | Jan 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [aeb9ac591c](https://linux-hardware.org/?probe=aeb9ac591c) | Jan 17, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [9f280d24f5](https://linux-hardware.org/?probe=9f280d24f5) | Jan 17, 2023 |
| ASUSTek       | K55VM                       | Notebook    | [5b8deec807](https://linux-hardware.org/?probe=5b8deec807) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [cc16045ed3](https://linux-hardware.org/?probe=cc16045ed3) | Jan 16, 2023 |
| Dell          | Latitude E7240              | Notebook    | [dc47f005d6](https://linux-hardware.org/?probe=dc47f005d6) | Jan 16, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [79eb90321f](https://linux-hardware.org/?probe=79eb90321f) | Jan 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [ab26ff36b1](https://linux-hardware.org/?probe=ab26ff36b1) | Jan 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [76f54ae84c](https://linux-hardware.org/?probe=76f54ae84c) | Jan 14, 2023 |
| Dell          | Latitude 3350               | Notebook    | [d7ca8710c2](https://linux-hardware.org/?probe=d7ca8710c2) | Jan 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [9eed89d744](https://linux-hardware.org/?probe=9eed89d744) | Jan 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [03f0709b21](https://linux-hardware.org/?probe=03f0709b21) | Jan 14, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7e67b2b3a0](https://linux-hardware.org/?probe=7e67b2b3a0) | Jan 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ed7ff7569c](https://linux-hardware.org/?probe=ed7ff7569c) | Jan 14, 2023 |
| MSI           | P67A-C45                    | Desktop     | [625a573f22](https://linux-hardware.org/?probe=625a573f22) | Jan 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d4b0530f79](https://linux-hardware.org/?probe=d4b0530f79) | Jan 13, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3128a21a3a](https://linux-hardware.org/?probe=3128a21a3a) | Jan 13, 2023 |
| HP            | 8299                        | Desktop     | [e4e0920f71](https://linux-hardware.org/?probe=e4e0920f71) | Jan 12, 2023 |
| Dell          | Latitude E7240              | Notebook    | [93d832d08f](https://linux-hardware.org/?probe=93d832d08f) | Jan 11, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [1dba72668b](https://linux-hardware.org/?probe=1dba72668b) | Jan 10, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [e6d3982bc0](https://linux-hardware.org/?probe=e6d3982bc0) | Jan 10, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [e14b3158f3](https://linux-hardware.org/?probe=e14b3158f3) | Jan 10, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ec34483710](https://linux-hardware.org/?probe=ec34483710) | Jan 09, 2023 |
| Dell          | Latitude 7490               | Notebook    | [0780580a38](https://linux-hardware.org/?probe=0780580a38) | Jan 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d7820d12e5](https://linux-hardware.org/?probe=d7820d12e5) | Jan 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [9eac6e2b97](https://linux-hardware.org/?probe=9eac6e2b97) | Jan 09, 2023 |
| Dell          | Latitude E7240              | Notebook    | [c191d76ac2](https://linux-hardware.org/?probe=c191d76ac2) | Jan 09, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [69b46423cb](https://linux-hardware.org/?probe=69b46423cb) | Jan 08, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e43de3e94e](https://linux-hardware.org/?probe=e43de3e94e) | Jan 08, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [2b8c216e1a](https://linux-hardware.org/?probe=2b8c216e1a) | Jan 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b0a36f054e](https://linux-hardware.org/?probe=b0a36f054e) | Jan 08, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b8ac11cfd3](https://linux-hardware.org/?probe=b8ac11cfd3) | Jan 08, 2023 |
| Cepter        | N530-01                     | Notebook    | [2b5d455bfd](https://linux-hardware.org/?probe=2b5d455bfd) | Jan 07, 2023 |
| Dell          | Latitude E7240              | Notebook    | [c7cf2afdd9](https://linux-hardware.org/?probe=c7cf2afdd9) | Jan 07, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7018e90a09](https://linux-hardware.org/?probe=7018e90a09) | Jan 07, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [5187413460](https://linux-hardware.org/?probe=5187413460) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [82052bbfcb](https://linux-hardware.org/?probe=82052bbfcb) | Jan 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c8a281879a](https://linux-hardware.org/?probe=c8a281879a) | Jan 07, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d4dc080444](https://linux-hardware.org/?probe=d4dc080444) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bcc4cba81a](https://linux-hardware.org/?probe=bcc4cba81a) | Jan 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [94d61ca559](https://linux-hardware.org/?probe=94d61ca559) | Jan 06, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b00208bba7](https://linux-hardware.org/?probe=b00208bba7) | Jan 06, 2023 |
| Dell          | Latitude E7240              | Notebook    | [6eae9dc932](https://linux-hardware.org/?probe=6eae9dc932) | Jan 05, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [01b93cba09](https://linux-hardware.org/?probe=01b93cba09) | Jan 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1964dbc8e7](https://linux-hardware.org/?probe=1964dbc8e7) | Jan 05, 2023 |
| Dell          | Latitude 9330               | Convertible | [66c7c42eea](https://linux-hardware.org/?probe=66c7c42eea) | Jan 04, 2023 |
| Dell          | Latitude 9330               | Convertible | [fad0f6ab61](https://linux-hardware.org/?probe=fad0f6ab61) | Jan 04, 2023 |
| Dell          | Latitude E5520              | Notebook    | [fd30377f05](https://linux-hardware.org/?probe=fd30377f05) | Jan 04, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [854bee8efb](https://linux-hardware.org/?probe=854bee8efb) | Jan 02, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ccf48432e0](https://linux-hardware.org/?probe=ccf48432e0) | Jan 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [178dcba2a5](https://linux-hardware.org/?probe=178dcba2a5) | Jan 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [54089a466b](https://linux-hardware.org/?probe=54089a466b) | Jan 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8582096251](https://linux-hardware.org/?probe=8582096251) | Dec 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c45e0f54fd](https://linux-hardware.org/?probe=c45e0f54fd) | Dec 31, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [6f61aac097](https://linux-hardware.org/?probe=6f61aac097) | Dec 31, 2022 |
| MSI           | GE60 2OC\2OE                | Notebook    | [c307379c36](https://linux-hardware.org/?probe=c307379c36) | Dec 30, 2022 |
| Dell          | Latitude E7240              | Notebook    | [5f83c8f4ad](https://linux-hardware.org/?probe=5f83c8f4ad) | Dec 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8289d108fb](https://linux-hardware.org/?probe=8289d108fb) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [3b0d4e8973](https://linux-hardware.org/?probe=3b0d4e8973) | Dec 30, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [ea9aef1e8d](https://linux-hardware.org/?probe=ea9aef1e8d) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [12c052156c](https://linux-hardware.org/?probe=12c052156c) | Dec 29, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [daf7777113](https://linux-hardware.org/?probe=daf7777113) | Dec 29, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [728793a92a](https://linux-hardware.org/?probe=728793a92a) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f5ac2a0028](https://linux-hardware.org/?probe=f5ac2a0028) | Dec 28, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2d572d06d7](https://linux-hardware.org/?probe=2d572d06d7) | Dec 28, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [78c6c15502](https://linux-hardware.org/?probe=78c6c15502) | Dec 27, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [593969da1f](https://linux-hardware.org/?probe=593969da1f) | Dec 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8d1181c71b](https://linux-hardware.org/?probe=8d1181c71b) | Dec 26, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [cbe4c82d15](https://linux-hardware.org/?probe=cbe4c82d15) | Dec 26, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [90bb379f4e](https://linux-hardware.org/?probe=90bb379f4e) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b6def743ea](https://linux-hardware.org/?probe=b6def743ea) | Dec 25, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8636b69474](https://linux-hardware.org/?probe=8636b69474) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f5fa069144](https://linux-hardware.org/?probe=f5fa069144) | Dec 24, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [a375cc62c7](https://linux-hardware.org/?probe=a375cc62c7) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [88df914367](https://linux-hardware.org/?probe=88df914367) | Dec 23, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [c36553b2b8](https://linux-hardware.org/?probe=c36553b2b8) | Dec 23, 2022 |
| Dell          | Latitude E7240              | Notebook    | [918223cece](https://linux-hardware.org/?probe=918223cece) | Dec 23, 2022 |
| Dell          | Latitude E7240              | Notebook    | [7bd2309063](https://linux-hardware.org/?probe=7bd2309063) | Dec 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d7b8ef01e2](https://linux-hardware.org/?probe=d7b8ef01e2) | Dec 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [23f2e15649](https://linux-hardware.org/?probe=23f2e15649) | Dec 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6eb006d2d4](https://linux-hardware.org/?probe=6eb006d2d4) | Dec 22, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [bfe7b1ec1d](https://linux-hardware.org/?probe=bfe7b1ec1d) | Dec 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [d81efafde1](https://linux-hardware.org/?probe=d81efafde1) | Dec 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [545294a23a](https://linux-hardware.org/?probe=545294a23a) | Dec 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bd7ed31b20](https://linux-hardware.org/?probe=bd7ed31b20) | Dec 21, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [3832e7e0af](https://linux-hardware.org/?probe=3832e7e0af) | Dec 21, 2022 |
| Dell          | Latitude E7240              | Notebook    | [a368a7be00](https://linux-hardware.org/?probe=a368a7be00) | Dec 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [17630a4351](https://linux-hardware.org/?probe=17630a4351) | Dec 20, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [30eb665688](https://linux-hardware.org/?probe=30eb665688) | Dec 20, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8a7ee1147b](https://linux-hardware.org/?probe=8a7ee1147b) | Dec 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9451dc3035](https://linux-hardware.org/?probe=9451dc3035) | Dec 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [6a731c5c9b](https://linux-hardware.org/?probe=6a731c5c9b) | Dec 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c7b01f9875](https://linux-hardware.org/?probe=c7b01f9875) | Dec 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [cc8dd14279](https://linux-hardware.org/?probe=cc8dd14279) | Dec 19, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [24affad285](https://linux-hardware.org/?probe=24affad285) | Dec 18, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [b4d6964157](https://linux-hardware.org/?probe=b4d6964157) | Dec 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [561aa4411a](https://linux-hardware.org/?probe=561aa4411a) | Dec 18, 2022 |
| Google        | Cyan                        | Notebook    | [df6e213ea7](https://linux-hardware.org/?probe=df6e213ea7) | Dec 17, 2022 |
| Google        | Cyan                        | Notebook    | [b0872d0327](https://linux-hardware.org/?probe=b0872d0327) | Dec 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [88d55eced8](https://linux-hardware.org/?probe=88d55eced8) | Dec 17, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [be93cca77c](https://linux-hardware.org/?probe=be93cca77c) | Dec 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [04bbc083d7](https://linux-hardware.org/?probe=04bbc083d7) | Dec 16, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [9caae58821](https://linux-hardware.org/?probe=9caae58821) | Dec 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [226bab8281](https://linux-hardware.org/?probe=226bab8281) | Dec 15, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [544e464dab](https://linux-hardware.org/?probe=544e464dab) | Dec 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2e9fac9df4](https://linux-hardware.org/?probe=2e9fac9df4) | Dec 15, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [5a071587fb](https://linux-hardware.org/?probe=5a071587fb) | Dec 15, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [3326c90617](https://linux-hardware.org/?probe=3326c90617) | Dec 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b20a4554c5](https://linux-hardware.org/?probe=b20a4554c5) | Dec 14, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [c8ffea5473](https://linux-hardware.org/?probe=c8ffea5473) | Dec 14, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [7924d2f347](https://linux-hardware.org/?probe=7924d2f347) | Dec 12, 2022 |
| Dell          | Latitude E7240              | Notebook    | [d6dddd9632](https://linux-hardware.org/?probe=d6dddd9632) | Dec 11, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [37b8d2824f](https://linux-hardware.org/?probe=37b8d2824f) | Dec 11, 2022 |
| Dell          | 0KG317                      | Desktop     | [cf7f697a0a](https://linux-hardware.org/?probe=cf7f697a0a) | Dec 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bcb55a7e4c](https://linux-hardware.org/?probe=bcb55a7e4c) | Dec 09, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [ea91fc57ae](https://linux-hardware.org/?probe=ea91fc57ae) | Dec 09, 2022 |
| Acer          | Aspire E1-572               | Notebook    | [7a6c67f095](https://linux-hardware.org/?probe=7a6c67f095) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [ead8cc9c0a](https://linux-hardware.org/?probe=ead8cc9c0a) | Dec 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e40a7efd61](https://linux-hardware.org/?probe=e40a7efd61) | Dec 08, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2d35fb5bbb](https://linux-hardware.org/?probe=2d35fb5bbb) | Dec 08, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [6bb486dbb5](https://linux-hardware.org/?probe=6bb486dbb5) | Dec 07, 2022 |
| MSI           | P67A-C45                    | Desktop     | [44c8da681d](https://linux-hardware.org/?probe=44c8da681d) | Dec 07, 2022 |
| ASRock        | AB350M                      | Desktop     | [95a14fd558](https://linux-hardware.org/?probe=95a14fd558) | Dec 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d655b34178](https://linux-hardware.org/?probe=d655b34178) | Dec 07, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [68fa42c5f5](https://linux-hardware.org/?probe=68fa42c5f5) | Dec 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a6763bdd89](https://linux-hardware.org/?probe=a6763bdd89) | Dec 05, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [3caa213ecf](https://linux-hardware.org/?probe=3caa213ecf) | Dec 04, 2022 |
| Dell          | Latitude E7240              | Notebook    | [6f34110d45](https://linux-hardware.org/?probe=6f34110d45) | Dec 04, 2022 |
| ASRock        | H77M-ITX                    | Desktop     | [b2b1b1649a](https://linux-hardware.org/?probe=b2b1b1649a) | Dec 03, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8b85688e36](https://linux-hardware.org/?probe=8b85688e36) | Dec 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [0e87a76042](https://linux-hardware.org/?probe=0e87a76042) | Dec 01, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [b2bba919b2](https://linux-hardware.org/?probe=b2bba919b2) | Nov 30, 2022 |
| Dell          | Latitude E7240              | Notebook    | [8b0b984870](https://linux-hardware.org/?probe=8b0b984870) | Nov 29, 2022 |
| Dell          | Latitude E7240              | Notebook    | [831ec54e18](https://linux-hardware.org/?probe=831ec54e18) | Nov 26, 2022 |
| HP            | Presario CQ56               | Notebook    | [919fad0653](https://linux-hardware.org/?probe=919fad0653) | Nov 25, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [1c648060f6](https://linux-hardware.org/?probe=1c648060f6) | Nov 25, 2022 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [7917cbbd8c](https://linux-hardware.org/?probe=7917cbbd8c) | Nov 24, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [c1e62a557c](https://linux-hardware.org/?probe=c1e62a557c) | Nov 24, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [50c2b71615](https://linux-hardware.org/?probe=50c2b71615) | Nov 23, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [71c464a407](https://linux-hardware.org/?probe=71c464a407) | Nov 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d3412020ec](https://linux-hardware.org/?probe=d3412020ec) | Nov 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [0278a1f18d](https://linux-hardware.org/?probe=0278a1f18d) | Nov 18, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [5d1e2af2ea](https://linux-hardware.org/?probe=5d1e2af2ea) | Nov 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4c86f7c670](https://linux-hardware.org/?probe=4c86f7c670) | Nov 17, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [8ce9402aad](https://linux-hardware.org/?probe=8ce9402aad) | Nov 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2eb90688b5](https://linux-hardware.org/?probe=2eb90688b5) | Nov 16, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [620dbe0a8f](https://linux-hardware.org/?probe=620dbe0a8f) | Nov 16, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [5a76aee400](https://linux-hardware.org/?probe=5a76aee400) | Nov 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [6677ca6be8](https://linux-hardware.org/?probe=6677ca6be8) | Nov 12, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [dffde21ad4](https://linux-hardware.org/?probe=dffde21ad4) | Nov 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5006a2d188](https://linux-hardware.org/?probe=5006a2d188) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [aec286073d](https://linux-hardware.org/?probe=aec286073d) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [3884507df6](https://linux-hardware.org/?probe=3884507df6) | Nov 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [d6644079ac](https://linux-hardware.org/?probe=d6644079ac) | Nov 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a311d2c018](https://linux-hardware.org/?probe=a311d2c018) | Nov 11, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [b7d21d229b](https://linux-hardware.org/?probe=b7d21d229b) | Nov 11, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [a06fb78621](https://linux-hardware.org/?probe=a06fb78621) | Nov 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d6fd1a5ecd](https://linux-hardware.org/?probe=d6fd1a5ecd) | Nov 10, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [3408fb4c36](https://linux-hardware.org/?probe=3408fb4c36) | Nov 07, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [5264f28363](https://linux-hardware.org/?probe=5264f28363) | Nov 07, 2022 |
| HP            | Pavilion dv6                | Notebook    | [f715c6e15c](https://linux-hardware.org/?probe=f715c6e15c) | Nov 07, 2022 |
| Dell          | Latitude 3340               | Notebook    | [2c6380f259](https://linux-hardware.org/?probe=2c6380f259) | Nov 06, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2db569e056](https://linux-hardware.org/?probe=2db569e056) | Nov 06, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [e2cadc512e](https://linux-hardware.org/?probe=e2cadc512e) | Nov 05, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [95fb6a845e](https://linux-hardware.org/?probe=95fb6a845e) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [36e78b1c17](https://linux-hardware.org/?probe=36e78b1c17) | Nov 05, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [b3eefc89d6](https://linux-hardware.org/?probe=b3eefc89d6) | Nov 04, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Norway/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 133       | 9.73%   |
| Ubuntu 22.04                 | 92        | 6.73%   |
| Ubuntu 18.04                 | 61        | 4.46%   |
| Pop!_OS 22.04                | 54        | 3.95%   |
| Debian 11                    | 41        | 3%      |
| Arch Rolling                 | 37        | 2.71%   |
| Zorin 16                     | 31        | 2.27%   |
| Debian 12                    | 28        | 2.05%   |
| ArcoLinux Rolling            | 26        | 1.9%    |
| Ubuntu 23.04                 | 22        | 1.61%   |
| Ubuntu 20.10                 | 20        | 1.46%   |
| OpenMandriva 4.2             | 20        | 1.46%   |
| Fedora 38                    | 20        | 1.46%   |
| Fedora 35                    | 20        | 1.46%   |
| OpenMandriva 4.3             | 19        | 1.39%   |
| Fedora 39                    | 18        | 1.32%   |
| openSUSE Tumbleweed-XXXXXXXX | 17        | 1.24%   |
| Manjaro                      | 17        | 1.24%   |
| Fedora 36                    | 17        | 1.24%   |
| Arch                         | 17        | 1.24%   |
| Ubuntu 23.10                 | 16        | 1.17%   |
| Pop!_OS 21.04                | 15        | 1.1%    |
| Pop!_OS 21.10                | 14        | 1.02%   |
| KDE neon 20.04               | 14        | 1.02%   |
| Fedora 37                    | 14        | 1.02%   |
| Fedora 34                    | 14        | 1.02%   |
| Fedora 31                    | 14        | 1.02%   |
| Ubuntu 22.10                 | 13        | 0.95%   |
| Ubuntu 19.10                 | 13        | 0.95%   |
| Ubuntu 19.04                 | 13        | 0.95%   |
| KDE neon 22.04               | 13        | 0.95%   |
| Ubuntu 18.10                 | 12        | 0.88%   |
| Pop!_OS 20.10                | 12        | 0.88%   |
| Pop!_OS 20.04                | 12        | 0.88%   |
| Linux Mint 20.2              | 12        | 0.88%   |
| Linux Mint 21.1              | 11        | 0.8%    |
| Linux Mint 20.3              | 11        | 0.8%    |
| OpenMandriva 23.03           | 10        | 0.73%   |
| Ubuntu 21.10                 | 9         | 0.66%   |
| Linux Mint 20.1              | 9         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 399       | 30.83%  |
| Fedora        | 123       | 9.51%   |
| Pop!_OS       | 100       | 7.73%   |
| Debian        | 88        | 6.8%    |
| Linux Mint    | 75        | 5.8%    |
| OpenMandriva  | 73        | 5.64%   |
| Arch          | 53        | 4.1%    |
| Manjaro       | 52        | 4.02%   |
| Zorin         | 46        | 3.55%   |
| KDE neon      | 30        | 2.32%   |
| ArcoLinux     | 27        | 2.09%   |
| Kubuntu       | 26        | 2.01%   |
| openSUSE      | 23        | 1.78%   |
| Xubuntu       | 17        | 1.31%   |
| Kali          | 14        | 1.08%   |
| Elementary    | 13        | 1%      |
| Gentoo        | 11        | 0.85%   |
| Ubuntu MATE   | 9         | 0.7%    |
| ROSA          | 9         | 0.7%    |
| EndeavourOS   | 9         | 0.7%    |
| Clear Linux   | 8         | 0.62%   |
| CentOS        | 8         | 0.62%   |
| RHEL          | 7         | 0.54%   |
| Ubuntu Budgie | 6         | 0.46%   |
| Nobara        | 6         | 0.46%   |
| Xero          | 4         | 0.31%   |
| Ubuntu Unity  | 4         | 0.31%   |
| Solus         | 4         | 0.31%   |
| NixOS         | 4         | 0.31%   |
| Lubuntu       | 4         | 0.31%   |
| Ubuntu Studio | 3         | 0.23%   |
| MX            | 3         | 0.23%   |
| LMDE          | 3         | 0.23%   |
| Garuda Linux  | 3         | 0.23%   |
| Alpine        | 3         | 0.23%   |
| Void Linux    | 2         | 0.15%   |
| TUXEDO OS     | 2         | 0.15%   |
| Rocky Linux   | 2         | 0.15%   |
| Raspbian      | 2         | 0.15%   |
| Parrot        | 2         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002    | 19        | 1.23%   |
| 5.16.7-desktop-1omv4003     | 18        | 1.17%   |
| 5.4.0-42-generic            | 14        | 0.91%   |
| 6.2.0-39-generic            | 11        | 0.71%   |
| 6.5.0-28-generic            | 10        | 0.65%   |
| 6.2.6-desktop-1omv2390      | 10        | 0.65%   |
| 5.19.0-76051900-generic     | 10        | 0.65%   |
| 5.15.0-46-generic           | 10        | 0.65%   |
| 6.5.6-76060506-generic      | 9         | 0.58%   |
| 5.4.0-58-generic            | 9         | 0.58%   |
| 5.3.0-46-generic            | 9         | 0.58%   |
| 5.15.0-76-generic           | 9         | 0.58%   |
| 4.18.0-16-generic           | 9         | 0.58%   |
| 3.10.0-1062.12.1.el7.x86_64 | 9         | 0.58%   |
| 6.6.2-desktop-1omv2390      | 8         | 0.52%   |
| 6.2.0-26-generic            | 8         | 0.52%   |
| 6.2.0-20-generic            | 8         | 0.52%   |
| 6.1.1-desktop-1omv2290      | 8         | 0.52%   |
| 5.4.0-74-generic            | 8         | 0.52%   |
| 5.4.0-48-generic            | 8         | 0.52%   |
| 5.11.0-40-generic           | 8         | 0.52%   |
| 5.11.0-38-generic           | 8         | 0.52%   |
| 6.2.6-76060206-generic      | 7         | 0.45%   |
| 6.0.12-76060006-generic     | 7         | 0.45%   |
| 5.8.0-7630-generic          | 7         | 0.45%   |
| 5.8.0-44-generic            | 7         | 0.45%   |
| 5.8.0-43-generic            | 7         | 0.45%   |
| 5.4.0-91-generic            | 7         | 0.45%   |
| 5.4.0-26-generic            | 7         | 0.45%   |
| 5.3.0-40-generic            | 7         | 0.45%   |
| 5.15.0-58-generic           | 7         | 0.45%   |
| 5.15.0-56-generic           | 7         | 0.45%   |
| 5.15.0-48-generic           | 7         | 0.45%   |
| 5.11.0-7620-generic         | 7         | 0.45%   |
| 6.5.0-27-generic            | 6         | 0.39%   |
| 6.5.0-17-generic            | 6         | 0.39%   |
| 6.5.0-10-generic            | 6         | 0.39%   |
| 6.1.0-10-amd64              | 6         | 0.39%   |
| 5.4.0-47-generic            | 6         | 0.39%   |
| 5.4.0-45-generic            | 6         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 165       | 11.34%  |
| 5.15.0  | 100       | 6.87%   |
| 6.2.0   | 57        | 3.92%   |
| 5.11.0  | 55        | 3.78%   |
| 6.5.0   | 54        | 3.71%   |
| 5.8.0   | 54        | 3.71%   |
| 5.19.0  | 51        | 3.51%   |
| 5.3.0   | 42        | 2.89%   |
| 5.13.0  | 39        | 2.68%   |
| 5.10.0  | 38        | 2.61%   |
| 4.15.0  | 38        | 2.61%   |
| 4.18.0  | 30        | 2.06%   |
| 6.1.0   | 29        | 1.99%   |
| 5.0.0   | 25        | 1.72%   |
| 6.2.6   | 19        | 1.31%   |
| 5.10.14 | 19        | 1.31%   |
| 5.16.7  | 18        | 1.24%   |
| 6.5.6   | 11        | 0.76%   |
| 3.10.0  | 10        | 0.69%   |
| 4.19.0  | 9         | 0.62%   |
| 6.6.2   | 8         | 0.55%   |
| 6.1.1   | 8         | 0.55%   |
| 6.0.12  | 8         | 0.55%   |
| 5.17.5  | 8         | 0.55%   |
| 6.8.0   | 7         | 0.48%   |
| 5.16.0  | 7         | 0.48%   |
| 6.7.4   | 6         | 0.41%   |
| 6.4.6   | 6         | 0.41%   |
| 6.4.12  | 6         | 0.41%   |
| 6.0.0   | 6         | 0.41%   |
| 5.17.0  | 6         | 0.41%   |
| 5.16.11 | 6         | 0.41%   |
| 5.12.4  | 6         | 0.41%   |
| 6.5.3   | 5         | 0.34%   |
| 6.4.0   | 5         | 0.34%   |
| 5.9.16  | 5         | 0.34%   |
| 5.5.5   | 5         | 0.34%   |
| 5.18.10 | 5         | 0.34%   |
| 5.18.0  | 5         | 0.34%   |
| 5.14.0  | 5         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 182       | 12.73%  |
| 5.15    | 143       | 10%     |
| 6.2     | 92        | 6.43%   |
| 6.5     | 81        | 5.66%   |
| 5.10    | 71        | 4.97%   |
| 5.8     | 70        | 4.9%    |
| 5.19    | 70        | 4.9%    |
| 6.1     | 65        | 4.55%   |
| 5.11    | 64        | 4.48%   |
| 5.13    | 61        | 4.27%   |
| 5.3     | 51        | 3.57%   |
| 5.16    | 50        | 3.5%    |
| 4.15    | 38        | 2.66%   |
| 6.4     | 34        | 2.38%   |
| 6.6     | 33        | 2.31%   |
| 4.18    | 33        | 2.31%   |
| 5.17    | 31        | 2.17%   |
| 6.0     | 30        | 2.1%    |
| 5.0     | 27        | 1.89%   |
| 5.14    | 23        | 1.61%   |
| 5.9     | 21        | 1.47%   |
| 6.8     | 19        | 1.33%   |
| 6.7     | 19        | 1.33%   |
| 6.3     | 19        | 1.33%   |
| 5.18    | 18        | 1.26%   |
| 5.12    | 16        | 1.12%   |
| 5.5     | 12        | 0.84%   |
| 5.7     | 11        | 0.77%   |
| 4.19    | 11        | 0.77%   |
| 3.10    | 10        | 0.7%    |
| 5.6     | 8         | 0.56%   |
| 4.9     | 4         | 0.28%   |
| 5.1     | 3         | 0.21%   |
| 5.2     | 2         | 0.14%   |
| 4.4     | 2         | 0.14%   |
| 6.9     | 1         | 0.07%   |
| 4.8     | 1         | 0.07%   |
| 4.20    | 1         | 0.07%   |
| 4.12    | 1         | 0.07%   |
| 4.10    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1216      | 97.59%  |
| i686    | 14        | 1.12%   |
| aarch64 | 12        | 0.96%   |
| armv7l  | 3         | 0.24%   |
| armv6l  | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 604       | 46.57%  |
| KDE5              | 218       | 16.81%  |
| Unknown           | 165       | 12.72%  |
| XFCE              | 99        | 7.63%   |
| X-Cinnamon        | 56        | 4.32%   |
| MATE              | 29        | 2.24%   |
| KDE               | 25        | 1.93%   |
| i3                | 16        | 1.23%   |
| Pantheon          | 12        | 0.93%   |
| Cinnamon          | 12        | 0.93%   |
| Budgie            | 10        | 0.77%   |
| GNOME Flashback   | 8         | 0.62%   |
| KDE6              | 7         | 0.54%   |
| LXQt              | 6         | 0.46%   |
| LXDE              | 6         | 0.46%   |
| Unity             | 4         | 0.31%   |
| Hyprland          | 4         | 0.31%   |
| KDE4              | 3         | 0.23%   |
| i3-with-shmlog    | 2         | 0.15%   |
| dwm               | 2         | 0.15%   |
| Yaru:ubuntu:GNOME | 1         | 0.08%   |
| xinit-compat      | 1         | 0.08%   |
| qtile             | 1         | 0.08%   |
| LeftWM            | 1         | 0.08%   |
| GNOME:Phosh       | 1         | 0.08%   |
| GNOME-Classic     | 1         | 0.08%   |
| Deepin            | 1         | 0.08%   |
| bspwm             | 1         | 0.08%   |
| AWESOME           | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 873       | 67.36%  |
| Wayland | 286       | 22.07%  |
| Unknown | 88        | 6.79%   |
| Tty     | 49        | 3.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 608       | 46.52%  |
| GDM3    | 196       | 15%     |
| SDDM    | 190       | 14.54%  |
| GDM     | 149       | 11.4%   |
| LightDM | 128       | 9.79%   |
| TDM     | 28        | 2.14%   |
| KDM     | 4         | 0.31%   |
| XDM     | 2         | 0.15%   |
| SLiM    | 1         | 0.08%   |
| Ly      | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 678       | 52.93%  |
| nb_NO       | 285       | 22.25%  |
| Unknown     | 115       | 8.98%   |
| en_GB       | 85        | 6.64%   |
| C           | 31        | 2.42%   |
| nn_NO       | 20        | 1.56%   |
| pl_PL       | 14        | 1.09%   |
| en_DK       | 14        | 1.09%   |
| de_DE       | 10        | 0.78%   |
| en_IE       | 4         | 0.31%   |
| ru_RU       | 3         | 0.23%   |
| POSIX       | 3         | 0.23%   |
| it_IT       | 3         | 0.23%   |
| fr_FR       | 3         | 0.23%   |
| pt_PT       | 2         | 0.16%   |
| sv_SE       | 1         | 0.08%   |
| fi_FI       | 1         | 0.08%   |
| es_ES       | 1         | 0.08%   |
| en_US.utf-8 | 1         | 0.08%   |
| en_NZ       | 1         | 0.08%   |
| en_CA       | 1         | 0.08%   |
| en_AG       | 1         | 0.08%   |
| en_150      | 1         | 0.08%   |
| en_001      | 1         | 0.08%   |
| el_GR       | 1         | 0.08%   |
| da_DK       | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 701       | 55.11%  |
| BIOS | 571       | 44.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 918       | 71.66%  |
| Btrfs   | 156       | 12.18%  |
| Overlay | 72        | 5.62%   |
| Tmpfs   | 58        | 4.53%   |
| Xfs     | 34        | 2.65%   |
| Unknown | 24        | 1.87%   |
| Zfs     | 10        | 0.78%   |
| Ext2    | 5         | 0.39%   |
| Ext3    | 2         | 0.16%   |
| F2fs    | 1         | 0.08%   |
| Aufs    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 600       | 46.66%  |
| Unknown | 583       | 45.33%  |
| MBR     | 103       | 8.01%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1087      | 85.12%  |
| Yes       | 190       | 14.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 948       | 74.7%   |
| Yes       | 321       | 25.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 265       | 21.27%  |
| Lenovo                  | 250       | 20.06%  |
| Hewlett-Packard         | 187       | 15.01%  |
| Dell                    | 144       | 11.56%  |
| MSI                     | 75        | 6.02%   |
| Acer                    | 61        | 4.9%    |
| Gigabyte Technology     | 59        | 4.74%   |
| Apple                   | 39        | 3.13%   |
| ASRock                  | 30        | 2.41%   |
| Samsung Electronics     | 14        | 1.12%   |
| HUAWEI                  | 14        | 1.12%   |
| Raspberry Pi Foundation | 12        | 0.96%   |
| Intel                   | 11        | 0.88%   |
| Toshiba                 | 9         | 0.72%   |
| Unknown                 | 8         | 0.64%   |
| Packard Bell            | 7         | 0.56%   |
| Notebook                | 7         | 0.56%   |
| Google                  | 5         | 0.4%    |
| Clevo                   | 5         | 0.4%    |
| Microsoft               | 4         | 0.32%   |
| Supermicro              | 3         | 0.24%   |
| Pegatron                | 3         | 0.24%   |
| ASRockRack              | 3         | 0.24%   |
| Panasonic               | 2         | 0.16%   |
| ZOTAC                   | 1         | 0.08%   |
| Xunlong                 | 1         | 0.08%   |
| Wibtek                  | 1         | 0.08%   |
| TYAN Computer           | 1         | 0.08%   |
| TUXEDO                  | 1         | 0.08%   |
| Teclast                 | 1         | 0.08%   |
| Star Labs               | 1         | 0.08%   |
| Sony                    | 1         | 0.08%   |
| Shuttle                 | 1         | 0.08%   |
| Razer                   | 1         | 0.08%   |
| Radxa                   | 1         | 0.08%   |
| Nokia                   | 1         | 0.08%   |
| Multicom Norge AS       | 1         | 0.08%   |
| Lenovo Product          | 1         | 0.08%   |
| LAMINA                  | 1         | 0.08%   |
| Intel Client Systems    | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS All Series                       | 15        | 1.2%    |
| Unknown                               | 9         | 0.72%   |
| HP Z440 Workstation                   | 8         | 0.64%   |
| ASUS KomplettPC                       | 8         | 0.64%   |
| Apple MacBookPro12,1                  | 7         | 0.56%   |
| HUAWEI MACH-WX9                       | 6         | 0.48%   |
| HP EliteBook 840 G6                   | 6         | 0.48%   |
| Dell Precision 5530                   | 6         | 0.48%   |
| ASUS ROG STRIX B360-F GAMING          | 6         | 0.48%   |
| Dell PowerEdge R230                   | 5         | 0.4%    |
| Dell OptiPlex 9020                    | 5         | 0.4%    |
| MSI MS-7885                           | 4         | 0.32%   |
| Lenovo Yoga Slim 7 14ARE05 82A2       | 4         | 0.32%   |
| HP ProBook 430 G2                     | 4         | 0.32%   |
| Gigabyte GA-970A-UD3                  | 4         | 0.32%   |
| Dell XPS 15 9570                      | 4         | 0.32%   |
| Dell Latitude E7240                   | 4         | 0.32%   |
| ASUS SABERTOOTH P67                   | 4         | 0.32%   |
| ASUS ROG STRIX X570-F GAMING          | 4         | 0.32%   |
| ASUS ROG STRIX B550-E GAMING          | 4         | 0.32%   |
| ASUS ROG STRIX B450-F GAMING          | 4         | 0.32%   |
| ASUS ROG CROSSHAIR VIII HERO          | 4         | 0.32%   |
| ASUS PC                               | 4         | 0.32%   |
| ASUS M2R-FVM                          | 4         | 0.32%   |
| Samsung 950XCJ/951XCJ/950XCR          | 3         | 0.24%   |
| MSI MS-7B86                           | 3         | 0.24%   |
| Lenovo Yoga Slim 7 Pro 14IAH7 82UT    | 3         | 0.24%   |
| Lenovo Yoga Slim 7 Carbon 14ACN6 82L0 | 3         | 0.24%   |
| HUAWEI WRT-WX9                        | 3         | 0.24%   |
| HP ProBook 450 G2                     | 3         | 0.24%   |
| HP Pavilion Notebook                  | 3         | 0.24%   |
| HP OMEN by Laptop                     | 3         | 0.24%   |
| HP EliteBook 8470p                    | 3         | 0.24%   |
| HP EliteBook 840 G5                   | 3         | 0.24%   |
| HP EliteBook 830 G6                   | 3         | 0.24%   |
| HP Compaq Elite 8300 SFF              | 3         | 0.24%   |
| Dell XPS 15 9500                      | 3         | 0.24%   |
| Dell XPS 13 9380                      | 3         | 0.24%   |
| Dell OptiPlex 7010                    | 3         | 0.24%   |
| Dell Latitude E5470                   | 3         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 153       | 12.28%  |
| ASUS ROG              | 58        | 4.65%   |
| HP EliteBook          | 53        | 4.25%   |
| Dell Latitude         | 50        | 4.01%   |
| Acer Aspire           | 37        | 2.97%   |
| HP ProBook            | 31        | 2.49%   |
| ASUS PRIME            | 30        | 2.41%   |
| Dell Precision        | 27        | 2.17%   |
| Dell XPS              | 26        | 2.09%   |
| Lenovo Yoga           | 23        | 1.85%   |
| Lenovo IdeaPad        | 19        | 1.52%   |
| Dell OptiPlex         | 18        | 1.44%   |
| HP Pavilion           | 16        | 1.28%   |
| ASUS VivoBook         | 16        | 1.28%   |
| ASUS TUF              | 15        | 1.2%    |
| ASUS All              | 15        | 1.2%    |
| Lenovo ThinkCentre    | 14        | 1.12%   |
| Dell PowerEdge        | 13        | 1.04%   |
| RPi Raspberry         | 12        | 0.96%   |
| HP ZBook              | 11        | 0.88%   |
| Lenovo Legion         | 10        | 0.8%    |
| HP EliteDesk          | 10        | 0.8%    |
| Gigabyte X570         | 9         | 0.72%   |
| Unknown               | 9         | 0.72%   |
| HP Z440               | 8         | 0.64%   |
| Dell Inspiron         | 8         | 0.64%   |
| ASUS KomplettPC       | 8         | 0.64%   |
| Toshiba Satellite     | 7         | 0.56%   |
| HP Compaq             | 7         | 0.56%   |
| ASUS SABERTOOTH       | 7         | 0.56%   |
| Apple MacBookPro12    | 7         | 0.56%   |
| Acer Swift            | 7         | 0.56%   |
| HUAWEI MACH-WX9       | 6         | 0.48%   |
| HP Spectre            | 6         | 0.48%   |
| HP Laptop             | 6         | 0.48%   |
| Gigabyte B550         | 6         | 0.48%   |
| ASUS ZenBook          | 6         | 0.48%   |
| Packard Bell EasyNote | 5         | 0.4%    |
| HP OMEN               | 5         | 0.4%    |
| HP ENVY               | 5         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 130       | 10.43%  |
| 2019    | 128       | 10.27%  |
| 2020    | 116       | 9.31%   |
| 2012    | 93        | 7.46%   |
| 2017    | 90        | 7.22%   |
| 2021    | 88        | 7.06%   |
| 2015    | 88        | 7.06%   |
| 2013    | 77        | 6.18%   |
| 2014    | 75        | 6.02%   |
| 2011    | 71        | 5.7%    |
| 2016    | 70        | 5.62%   |
| 2022    | 57        | 4.57%   |
| 2010    | 41        | 3.29%   |
| 2023    | 29        | 2.33%   |
| 2009    | 27        | 2.17%   |
| 2008    | 21        | 1.69%   |
| 2007    | 16        | 1.28%   |
| Unknown | 14        | 1.12%   |
| 2006    | 8         | 0.64%   |
| 2005    | 4         | 0.32%   |
| 2024    | 2         | 0.16%   |
| 2001    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 685       | 54.98%  |
| Desktop        | 443       | 35.55%  |
| Convertible    | 36        | 2.89%   |
| Mini pc        | 21        | 1.69%   |
| Server         | 21        | 1.69%   |
| System on chip | 15        | 1.2%    |
| All in one     | 14        | 1.12%   |
| Tablet         | 11        | 0.88%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1137      | 90.67%  |
| Enabled  | 117       | 9.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1239      | 99.44%  |
| Yes  | 7         | 0.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 311       | 24.53%  |
| 4.01-8.0        | 278       | 21.92%  |
| 32.01-64.0      | 220       | 17.35%  |
| 8.01-16.0       | 192       | 15.14%  |
| 3.01-4.0        | 137       | 10.8%   |
| 64.01-256.0     | 72        | 5.68%   |
| 24.01-32.0      | 22        | 1.74%   |
| 1.01-2.0        | 20        | 1.58%   |
| 2.01-3.0        | 5         | 0.39%   |
| 0.51-1.0        | 4         | 0.32%   |
| 0.01-0.5        | 4         | 0.32%   |
| More than 256.0 | 3         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 365       | 25.74%  |
| 2.01-3.0    | 325       | 22.92%  |
| 4.01-8.0    | 303       | 21.37%  |
| 3.01-4.0    | 222       | 15.66%  |
| 8.01-16.0   | 92        | 6.49%   |
| 0.51-1.0    | 59        | 4.16%   |
| 0.01-0.5    | 19        | 1.34%   |
| 16.01-24.0  | 17        | 1.2%    |
| 24.01-32.0  | 10        | 0.71%   |
| 32.01-64.0  | 5         | 0.35%   |
| 64.01-256.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 771       | 59.49%  |
| 2      | 251       | 19.37%  |
| 3      | 113       | 8.72%   |
| 4      | 63        | 4.86%   |
| 5      | 34        | 2.62%   |
| 6      | 25        | 1.93%   |
| 0      | 18        | 1.39%   |
| 7      | 8         | 0.62%   |
| 11     | 4         | 0.31%   |
| 8      | 4         | 0.31%   |
| 9      | 3         | 0.23%   |
| 10     | 2         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 930       | 74.16%  |
| Yes       | 324       | 25.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1055      | 84.4%   |
| No        | 195       | 15.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 989       | 79.06%  |
| No        | 262       | 20.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 828       | 65.51%  |
| No        | 436       | 34.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Norway  | 1246      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Oslo                 | 369       | 27.64%  |
| Trondheim            | 90        | 6.74%   |
| Bergen               | 56        | 4.19%   |
| Stavanger            | 35        | 2.62%   |
| Kristiansand         | 34        | 2.55%   |
| Ålesund             | 20        | 1.5%    |
| Skien                | 18        | 1.35%   |
| Tromsø              | 16        | 1.2%    |
| Sandefjord           | 16        | 1.2%    |
| Fornebu              | 13        | 0.97%   |
| Drammen              | 13        | 0.97%   |
| Lillehammer          | 11        | 0.82%   |
| Kongsberg            | 11        | 0.82%   |
| Fredrikstad          | 11        | 0.82%   |
| Asker                | 11        | 0.82%   |
| Sarpsborg            | 10        | 0.75%   |
| Sandnes              | 10        | 0.75%   |
| Haugesund            | 10        | 0.75%   |
| Røyken Municipality | 9         | 0.67%   |
| Porsgrunn            | 9         | 0.67%   |
| Moss                 | 9         | 0.67%   |
| Bodø                | 9         | 0.67%   |
| Arendal              | 9         | 0.67%   |
| Nesttun              | 8         | 0.6%    |
| Levanger             | 8         | 0.6%    |
| Honefoss             | 7         | 0.52%   |
| Bo                   | 7         | 0.52%   |
| Tønsberg            | 6         | 0.45%   |
| Stjordal             | 6         | 0.45%   |
| Ski                  | 6         | 0.45%   |
| Harstad              | 6         | 0.45%   |
| Hamar                | 6         | 0.45%   |
| Fetsund              | 6         | 0.45%   |
| Drobak               | 6         | 0.45%   |
| Voll                 | 5         | 0.37%   |
| Vennesla             | 5         | 0.37%   |
| Sandnessjøen        | 5         | 0.37%   |
| Notodden             | 5         | 0.37%   |
| Mo i Rana            | 5         | 0.37%   |
| Mjondalen            | 5         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 443       | 744    | 23.8%   |
| Seagate                        | 234       | 429    | 12.57%  |
| WDC                            | 195       | 409    | 10.48%  |
| Kingston                       | 132       | 197    | 7.09%   |
| Toshiba                        | 107       | 159    | 5.75%   |
| SanDisk                        | 99        | 128    | 5.32%   |
| Intel                          | 69        | 94     | 3.71%   |
| SK hynix                       | 62        | 80     | 3.33%   |
| Unknown                        | 58        | 71     | 3.12%   |
| Crucial                        | 56        | 88     | 3.01%   |
| Hitachi                        | 47        | 67     | 2.53%   |
| Micron Technology              | 46        | 58     | 2.47%   |
| HGST                           | 33        | 46     | 1.77%   |
| Corsair                        | 28        | 42     | 1.5%    |
| Apple                          | 26        | 32     | 1.4%    |
| PNY                            | 20        | 29     | 1.07%   |
| OCZ                            | 19        | 22     | 1.02%   |
| Phison                         | 18        | 24     | 0.97%   |
| LITEON                         | 18        | 22     | 0.97%   |
| Phison Electronics             | 15        | 22     | 0.81%   |
| KIOXIA                         | 13        | 21     | 0.7%    |
| LITEONIT                       | 12        | 21     | 0.64%   |
| A-DATA Technology              | 12        | 15     | 0.64%   |
| Kingston Technology Company    | 11        | 14     | 0.59%   |
| Lenovo                         | 6         | 6      | 0.32%   |
| JMicron Technology             | 6         | 6      | 0.32%   |
| Unknown                        | 6         | 9      | 0.32%   |
| Intenso                        | 5         | 9      | 0.27%   |
| Fujitsu                        | 5         | 5      | 0.27%   |
| China                          | 5         | 6      | 0.27%   |
| XPG                            | 2         | 2      | 0.11%   |
| Union Memory                   | 2         | 2      | 0.11%   |
| Transcend                      | 2         | 2      | 0.11%   |
| Solid State Storage Technology | 2         | 2      | 0.11%   |
| Silicon Motion                 | 2         | 3      | 0.11%   |
| Patriot                        | 2         | 2      | 0.11%   |
| Netac                          | 2         | 2      | 0.11%   |
| Lexar                          | 2         | 2      | 0.11%   |
| LaCie                          | 2         | 2      | 0.11%   |
| Hewlett-Packard                | 2         | 5      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 22        | 1.03%   |
| Samsung SSD 850 EVO 250GB                          | 20        | 0.94%   |
| Samsung SSD 860 EVO 1TB                            | 17        | 0.8%    |
| Samsung SSD 840 EVO 250GB                          | 17        | 0.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 17        | 0.8%    |
| Kingston SV300S37A120G 120GB SSD                   | 17        | 0.8%    |
| Samsung SSD 850 EVO 500GB                          | 16        | 0.75%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 15        | 0.7%    |
| Seagate ST500DM002-1BD142 500GB                    | 15        | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB  | 14        | 0.66%   |
| Samsung SSD 860 EVO 500GB                          | 13        | 0.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 13        | 0.61%   |
| Samsung NVMe SSD Drive 500GB                       | 11        | 0.52%   |
| Seagate ST4000DM004-2CV104 4TB                     | 10        | 0.47%   |
| Seagate Expansion 2TB                              | 10        | 0.47%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 10        | 0.47%   |
| PNY ELITE PSSD 480GB                               | 10        | 0.47%   |
| Kingston SA400S37240G 240GB SSD                    | 10        | 0.47%   |
| Toshiba NVMe SSD Drive 256GB                       | 9         | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                       | 9         | 0.42%   |
| Samsung SSD 860 EVO 250GB                          | 9         | 0.42%   |
| Samsung NVMe SSD Drive 512GB                       | 9         | 0.42%   |
| Samsung NVMe SSD Drive 1TB                         | 9         | 0.42%   |
| HGST HTS721010A9E630 1TB                           | 9         | 0.42%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 8         | 0.37%   |
| Seagate ST1000DM010-2EP102 1TB                     | 8         | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB                     | 8         | 0.37%   |
| Samsung SSD 840 EVO 120GB                          | 8         | 0.37%   |
| Kingston SV300S37A240G 240GB SSD                   | 8         | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB                     | 7         | 0.33%   |
| Seagate ST2000DM001-1ER164 2TB                     | 7         | 0.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 7         | 0.33%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD               | 7         | 0.33%   |
| Phison E12 NVMe Controller 2TB                     | 7         | 0.33%   |
| Kingston NVMe SSD Drive 1TB                        | 7         | 0.33%   |
| Apple SSD SM0128G 121GB                            | 7         | 0.33%   |
| Unknown MMC Card  64GB                             | 6         | 0.28%   |
| Seagate ST4000VN008-2DR166 4TB                     | 6         | 0.28%   |
| Seagate ST2000DM008-2FR102 2TB                     | 6         | 0.28%   |
| Seagate Backup+ Hub BK 8TB                         | 6         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 226       | 418    | 40.94%  |
| WDC                 | 134       | 303    | 24.28%  |
| Toshiba             | 53        | 92     | 9.6%    |
| Hitachi             | 47        | 67     | 8.51%   |
| HGST                | 33        | 46     | 5.98%   |
| Samsung Electronics | 31        | 59     | 5.62%   |
| Apple               | 7         | 8      | 1.27%   |
| Fujitsu             | 5         | 5      | 0.91%   |
| Unknown             | 4         | 4      | 0.72%   |
| Intenso             | 3         | 7      | 0.54%   |
| JMicron Technology  | 2         | 3      | 0.36%   |
| STEC                | 1         | 1      | 0.18%   |
| SABRENT             | 1         | 1      | 0.18%   |
| LaCie               | 1         | 1      | 0.18%   |
| IET                 | 1         | 2      | 0.18%   |
| Hewlett-Packard     | 1         | 2      | 0.18%   |
| ASMT                | 1         | 2      | 0.18%   |
| Unknown             | 1         | 1      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 241       | 359    | 36.02%  |
| Kingston            | 87        | 119    | 13%     |
| Crucial             | 49        | 81     | 7.32%   |
| SanDisk             | 43        | 53     | 6.43%   |
| Intel               | 37        | 51     | 5.53%   |
| WDC                 | 30        | 63     | 4.48%   |
| PNY                 | 20        | 29     | 2.99%   |
| OCZ                 | 19        | 22     | 2.84%   |
| Micron Technology   | 19        | 25     | 2.84%   |
| Apple               | 17        | 20     | 2.54%   |
| Corsair             | 16        | 22     | 2.39%   |
| SK hynix            | 15        | 17     | 2.24%   |
| LITEON              | 15        | 19     | 2.24%   |
| Toshiba             | 12        | 16     | 1.79%   |
| LITEONIT            | 12        | 21     | 1.79%   |
| A-DATA Technology   | 10        | 13     | 1.49%   |
| China               | 5         | 6      | 0.75%   |
| Transcend           | 2         | 2      | 0.3%    |
| Patriot             | 2         | 2      | 0.3%    |
| Goodram             | 2         | 2      | 0.3%    |
| Verbatim            | 1         | 1      | 0.15%   |
| Teclast             | 1         | 1      | 0.15%   |
| Team                | 1         | 1      | 0.15%   |
| SPCC                | 1         | 1      | 0.15%   |
| Seagate             | 1         | 1      | 0.15%   |
| SandForce           | 1         | 2      | 0.15%   |
| Radeon              | 1         | 1      | 0.15%   |
| Phison              | 1         | 2      | 0.15%   |
| Netac               | 1         | 1      | 0.15%   |
| LDLC                | 1         | 1      | 0.15%   |
| KingSpec            | 1         | 2      | 0.15%   |
| KingFast            | 1         | 1      | 0.15%   |
| Intenso             | 1         | 1      | 0.15%   |
| BIWIN               | 1         | 1      | 0.15%   |
| ASMT                | 1         | 1      | 0.15%   |
| Unknown             | 1         | 2      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 575       | 962    | 34.58%  |
| NVMe    | 556       | 857    | 33.43%  |
| HDD     | 453       | 1022   | 27.24%  |
| MMC     | 57        | 73     | 3.43%   |
| Unknown | 22        | 26     | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 796       | 1868   | 53%     |
| NVMe | 555       | 853    | 36.95%  |
| SAS  | 94        | 146    | 6.26%   |
| MMC  | 57        | 73     | 3.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 633       | 1062   | 56.27%  |
| 0.51-1.0   | 261       | 390    | 23.2%   |
| 1.01-2.0   | 100       | 209    | 8.89%   |
| 3.01-4.0   | 46        | 83     | 4.09%   |
| 2.01-3.0   | 39        | 100    | 3.47%   |
| 4.01-10.0  | 35        | 124    | 3.11%   |
| 10.01-20.0 | 11        | 16     | 0.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 371       | 27.89%  |
| 251-500        | 279       | 20.98%  |
| 501-1000       | 184       | 13.83%  |
| 1001-2000      | 113       | 8.5%    |
| More than 3000 | 111       | 8.35%   |
| 1-20           | 96        | 7.22%   |
| 51-100         | 54        | 4.06%   |
| 2001-3000      | 49        | 3.68%   |
| Unknown        | 39        | 2.93%   |
| 21-50          | 34        | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 496       | 35.45%  |
| 21-50          | 215       | 15.37%  |
| 101-250        | 171       | 12.22%  |
| 51-100         | 153       | 10.94%  |
| 251-500        | 113       | 8.08%   |
| 501-1000       | 85        | 6.08%   |
| 1001-2000      | 61        | 4.36%   |
| More than 3000 | 46        | 3.29%   |
| Unknown        | 39        | 2.79%   |
| 2001-3000      | 18        | 1.29%   |
| 0              | 2         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 3         | 4      | 2.88%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 2         | 2      | 1.92%   |
| WDC WD5000AAKS-00UU3A0 500GB          | 2         | 5      | 1.92%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2         | 2      | 1.92%   |
| Seagate ST31000528AS 1TB              | 2         | 2      | 1.92%   |
| Seagate ST31000524AS 1TB              | 2         | 2      | 1.92%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 2      | 1.92%   |
| Samsung Electronics HD501LJ 500GB     | 2         | 2      | 1.92%   |
| Hitachi HTS543216L9SA00 160GB         | 2         | 2      | 1.92%   |
| Hitachi HDS722020ALA330 2TB           | 2         | 2      | 1.92%   |
| WDC WD800JB-00CRA1 80GB               | 1         | 1      | 0.96%   |
| WDC WD800BB-00CAA1 80GB               | 1         | 1      | 0.96%   |
| WDC WD6400AAKS-75A7B0 640GB           | 1         | 2      | 0.96%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1         | 1      | 0.96%   |
| WDC WD5000AAJS-00YFA0 500GB           | 1         | 1      | 0.96%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1         | 4      | 0.96%   |
| WDC WD3200AAKS-00V1A0 320GB           | 1         | 1      | 0.96%   |
| WDC WD30EZRX-00AZ6B0 3TB              | 1         | 1      | 0.96%   |
| WDC WD2002FAEX-007BA0 2TB             | 1         | 1      | 0.96%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 0.96%   |
| WDC WD10EALX-009BA0 1TB               | 1         | 1      | 0.96%   |
| WDC WD10EADS-114BB1 1TB               | 1         | 1      | 0.96%   |
| WDC WD1002FBYS-18W8B1 1TB             | 1         | 2      | 0.96%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1         | 1      | 0.96%   |
| WDC WD Blue SA510 M.2 2280 1000GB     | 1         | 1      | 0.96%   |
| Toshiba MK5055GSX 500GB               | 1         | 3      | 0.96%   |
| Toshiba HDWD110 1TB                   | 1         | 1      | 0.96%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 0.96%   |
| SK hynix SH920 2.5 7MM 128GB SSD      | 1         | 1      | 0.96%   |
| SK hynix SC210 2.5 7MM 256GB SSD      | 1         | 1      | 0.96%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 0.96%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 0.96%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 0.96%   |
| Seagate ST9320320AS 320GB             | 1         | 1      | 0.96%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 0.96%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 0.96%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 0.96%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 1      | 0.96%   |
| Seagate ST4000VN008-2DR166 4TB        | 1         | 1      | 0.96%   |
| Seagate ST4000LM024-2AN17V 4TB        | 1         | 1      | 0.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 47     | 26.47%  |
| WDC                 | 20        | 29     | 19.61%  |
| Hitachi             | 9         | 10     | 8.82%   |
| Samsung Electronics | 8         | 8      | 7.84%   |
| Intel               | 7         | 9      | 6.86%   |
| SK hynix            | 4         | 4      | 3.92%   |
| Kingston            | 4         | 5      | 3.92%   |
| Toshiba             | 3         | 5      | 2.94%   |
| Micron Technology   | 3         | 6      | 2.94%   |
| LITEON              | 3         | 3      | 2.94%   |
| HGST                | 3         | 4      | 2.94%   |
| Corsair             | 3         | 4      | 2.94%   |
| SanDisk             | 2         | 2      | 1.96%   |
| OCZ                 | 2         | 2      | 1.96%   |
| Crucial             | 2         | 2      | 1.96%   |
| Lenovo              | 1         | 1      | 0.98%   |
| Apple               | 1         | 1      | 0.98%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 47     | 42.19%  |
| WDC                 | 19        | 28     | 29.69%  |
| Hitachi             | 9         | 10     | 14.06%  |
| Toshiba             | 3         | 5      | 4.69%   |
| Samsung Electronics | 3         | 3      | 4.69%   |
| HGST                | 3         | 4      | 4.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 60        | 97     | 61.22%  |
| SSD  | 29        | 34     | 29.59%  |
| NVMe | 9         | 11     | 9.18%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB    | 3         | 3      | 75%     |
| Kingston SV300S37A120G 120GB SSD | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Apple    | 3         | 3      | 75%     |
| Kingston | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 727       | 1627   | 53.1%   |
| Works    | 543       | 1167   | 39.66%  |
| Malfunc  | 95        | 142    | 6.94%   |
| Failed   | 4         | 4      | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 772       | 45.44%  |
| AMD                              | 236       | 13.89%  |
| Samsung Electronics              | 234       | 13.77%  |
| SanDisk                          | 93        | 5.47%   |
| Kingston Technology Company      | 61        | 3.59%   |
| SK hynix                         | 46        | 2.71%   |
| Toshiba America Info Systems     | 43        | 2.53%   |
| Phison Electronics               | 42        | 2.47%   |
| Micron Technology                | 27        | 1.59%   |
| ASMedia Technology               | 27        | 1.59%   |
| Nvidia                           | 13        | 0.77%   |
| Marvell Technology Group         | 13        | 0.77%   |
| Broadcom / LSI                   | 13        | 0.77%   |
| LSI Logic / Symbios Logic        | 12        | 0.71%   |
| KIOXIA                           | 12        | 0.71%   |
| JMicron Technology               | 10        | 0.59%   |
| Micron/Crucial Technology        | 7         | 0.41%   |
| Lenovo                           | 6         | 0.35%   |
| ADATA Technology                 | 5         | 0.29%   |
| Seagate Technology               | 4         | 0.24%   |
| Lite-On Technology               | 4         | 0.24%   |
| Union Memory (Shenzhen)          | 3         | 0.18%   |
| Silicon Motion                   | 3         | 0.18%   |
| Solid State Storage Technology   | 2         | 0.12%   |
| Hewlett-Packard                  | 2         | 0.12%   |
| Apple                            | 2         | 0.12%   |
| Solidigm                         | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |
| Silicon Image                    | 1         | 0.06%   |
| Realtek Semiconductor            | 1         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.06%   |
| Adaptec                          | 1         | 0.06%   |
| 3ware                            | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 149       | 7.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 104       | 5.48%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 66        | 3.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 62        | 3.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 50        | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 43        | 2.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 43        | 2.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 39        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 39        | 2.05%   |
| Intel Volume Management Device NVMe RAID Controller                            | 37        | 1.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 35        | 1.84%   |
| AMD 400 Series Chipset SATA Controller                                         | 32        | 1.69%   |
| AMD 500 Series Chipset SATA Controller                                         | 29        | 1.53%   |
| Intel SATA Controller [RAID mode]                                              | 28        | 1.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 27        | 1.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 26        | 1.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 26        | 1.37%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 25        | 1.32%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 25        | 1.32%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 25        | 1.32%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 22        | 1.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 22        | 1.16%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 22        | 1.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 22        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 22        | 1.16%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 21        | 1.11%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 21        | 1.11%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 20        | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 1.05%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 19        | 1%      |
| Phison E16 PCIe4 NVMe Controller                                               | 18        | 0.95%   |
| Phison E12 NVMe Controller                                                     | 18        | 0.95%   |
| Intel SSD 660P Series                                                          | 18        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 17        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 17        | 0.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 15        | 0.79%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 13        | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 13        | 0.68%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 12        | 0.63%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 12        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 886       | 53.15%  |
| NVMe | 555       | 33.29%  |
| RAID | 130       | 7.8%    |
| IDE  | 81        | 4.86%   |
| SAS  | 9         | 0.54%   |
| SCSI | 6         | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 937       | 75.2%   |
| AMD      | 293       | 23.52%  |
| ARM      | 15        | 1.2%    |
| QUALCOMM | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 24        | 1.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 17        | 1.36%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 16        | 1.28%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 15        | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 14        | 1.12%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 14        | 1.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 12        | 0.96%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 12        | 0.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 11        | 0.88%   |
| ARM Processor                           | 11        | 0.88%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 10        | 0.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 10        | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 10        | 0.8%    |
| AMD Ryzen 7 2700X Eight-Core Processor  | 10        | 0.8%    |
| AMD Ryzen 5 3600 6-Core Processor       | 10        | 0.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 9         | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 0.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 9         | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 9         | 0.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 9         | 0.72%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 9         | 0.72%   |
| Intel Xeon CPU E5-1630 v3 @ 3.70GHz     | 8         | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 8         | 0.64%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 8         | 0.64%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 8         | 0.64%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 8         | 0.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 8         | 0.64%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 8         | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 7         | 0.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 7         | 0.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 7         | 0.56%   |
| Intel Core i5-5257U CPU @ 2.70GHz       | 7         | 0.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 7         | 0.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 7         | 0.56%   |
| Intel 12th Gen Core i5-12500H           | 7         | 0.56%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 7         | 0.56%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 7         | 0.56%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 7         | 0.56%   |
| AMD Ryzen 5 4500U with Radeon Graphics  | 7         | 0.56%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 6         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 321       | 25.7%   |
| Intel Core i5           | 285       | 22.82%  |
| Other                   | 116       | 9.29%   |
| AMD Ryzen 7             | 73        | 5.84%   |
| AMD Ryzen 5             | 65        | 5.2%    |
| Intel Core i3           | 52        | 4.16%   |
| AMD Ryzen 9             | 45        | 3.6%    |
| Intel Xeon              | 44        | 3.52%   |
| Intel Celeron           | 31        | 2.48%   |
| Intel Core i9           | 23        | 1.84%   |
| Intel Pentium           | 19        | 1.52%   |
| Intel Core 2 Duo        | 16        | 1.28%   |
| AMD FX                  | 12        | 0.96%   |
| Intel Atom              | 11        | 0.88%   |
| AMD A8                  | 9         | 0.72%   |
| AMD A10                 | 8         | 0.64%   |
| AMD Ryzen 7 PRO         | 7         | 0.56%   |
| AMD Ryzen 3             | 7         | 0.56%   |
| AMD Athlon 64 X2        | 7         | 0.56%   |
| Intel Core 2            | 6         | 0.48%   |
| AMD A6                  | 6         | 0.48%   |
| Intel Pentium Dual-Core | 5         | 0.4%    |
| Intel Genuine           | 5         | 0.4%    |
| AMD Ryzen 5 PRO         | 5         | 0.4%    |
| AMD Phenom II X4        | 5         | 0.4%    |
| Intel Core 2 Quad       | 4         | 0.32%   |
| Intel Xeon Silver       | 3         | 0.24%   |
| AMD Ryzen Threadripper  | 3         | 0.24%   |
| AMD E2                  | 3         | 0.24%   |
| AMD E1                  | 3         | 0.24%   |
| AMD E                   | 3         | 0.24%   |
| AMD Athlon              | 3         | 0.24%   |
| AMD A4                  | 3         | 0.24%   |
| Intel Pentium Silver    | 2         | 0.16%   |
| Intel Pentium Gold      | 2         | 0.16%   |
| Intel Core m7           | 2         | 0.16%   |
| ARM BCM                 | 2         | 0.16%   |
| AMD Turion 64 X2 Mobile | 2         | 0.16%   |
| AMD Ryzen 3 PRO         | 2         | 0.16%   |
| AMD Phenom II           | 2         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 442       | 35.28%  |
| 2       | 383       | 30.57%  |
| 6       | 155       | 12.37%  |
| 8       | 122       | 9.74%   |
| 12      | 49        | 3.91%   |
| 10      | 21        | 1.68%   |
| 1       | 20        | 1.6%    |
| 16      | 17        | 1.36%   |
| 14      | 12        | 0.96%   |
| 20      | 7         | 0.56%   |
| 3       | 7         | 0.56%   |
| 24      | 5         | 0.4%    |
| 28      | 4         | 0.32%   |
| Unknown | 3         | 0.24%   |
| 40      | 2         | 0.16%   |
| 32      | 2         | 0.16%   |
| 18      | 2         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1220      | 97.83%  |
| 2       | 23        | 1.84%   |
| Unknown | 3         | 0.24%   |
| 4       | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 952       | 75.92%  |
| 1       | 297       | 23.68%  |
| Unknown | 3         | 0.24%   |
| 8       | 2         | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1218      | 97.67%  |
| Unknown        | 21        | 1.68%   |
| 32-bit         | 6         | 0.48%   |
| 64-bit         | 2         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 504       | 38.5%   |
| 0x306a9    | 49        | 3.74%   |
| 0x306c3    | 42        | 3.21%   |
| 0x206a7    | 42        | 3.21%   |
| 0x906ea    | 38        | 2.9%    |
| 0x806ea    | 33        | 2.52%   |
| 0x506e3    | 33        | 2.52%   |
| 0x406e3    | 29        | 2.22%   |
| 0x40651    | 28        | 2.14%   |
| 0x806ec    | 23        | 1.76%   |
| 0x906e9    | 22        | 1.68%   |
| 0x806e9    | 22        | 1.68%   |
| 0x08701021 | 21        | 1.6%    |
| 0x306d4    | 20        | 1.53%   |
| 0x306f2    | 18        | 1.38%   |
| 0x806c1    | 15        | 1.15%   |
| 0x1067a    | 15        | 1.15%   |
| 0x20655    | 13        | 0.99%   |
| 0x08600106 | 13        | 0.99%   |
| 0xa0652    | 11        | 0.84%   |
| 0x906a3    | 11        | 0.84%   |
| 0x08701013 | 9         | 0.69%   |
| 0x010000c8 | 9         | 0.69%   |
| 0x906ed    | 8         | 0.61%   |
| 0x806eb    | 8         | 0.61%   |
| 0x806d1    | 8         | 0.61%   |
| 0x0a601203 | 8         | 0.61%   |
| 0x0a50000c | 8         | 0.61%   |
| 0x0a201016 | 8         | 0.61%   |
| 0x0800820d | 8         | 0.61%   |
| 0x06001119 | 7         | 0.53%   |
| 0x20652    | 6         | 0.46%   |
| 0x0a20120a | 6         | 0.46%   |
| 0x0a201009 | 6         | 0.46%   |
| 0x08108109 | 6         | 0.46%   |
| 0x06000852 | 6         | 0.46%   |
| 0x706e5    | 5         | 0.38%   |
| 0x506c9    | 5         | 0.38%   |
| 0x406f1    | 5         | 0.38%   |
| 0x30678    | 5         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 240       | 19.18%  |
| Haswell          | 133       | 10.63%  |
| Skylake          | 110       | 8.79%   |
| IvyBridge        | 80        | 6.39%   |
| Zen 2            | 74        | 5.92%   |
| SandyBridge      | 69        | 5.52%   |
| Unknown          | 61        | 4.88%   |
| Zen 3            | 60        | 4.8%    |
| Alderlake Hybrid | 44        | 3.52%   |
| Broadwell        | 41        | 3.28%   |
| Zen+             | 32        | 2.56%   |
| TigerLake        | 31        | 2.48%   |
| Westmere         | 30        | 2.4%    |
| CometLake        | 28        | 2.24%   |
| Penryn           | 26        | 2.08%   |
| Icelake          | 22        | 1.76%   |
| Zen              | 21        | 1.68%   |
| Piledriver       | 21        | 1.68%   |
| K10              | 16        | 1.28%   |
| Silvermont       | 15        | 1.2%    |
| K8 Hammer        | 15        | 1.2%    |
| Core             | 12        | 0.96%   |
| Goldmont plus    | 10        | 0.8%    |
| Nehalem          | 8         | 0.64%   |
| Goldmont         | 7         | 0.56%   |
| Excavator        | 7         | 0.56%   |
| Bonnell          | 7         | 0.56%   |
| Bulldozer        | 5         | 0.4%    |
| Bobcat           | 5         | 0.4%    |
| Steamroller      | 4         | 0.32%   |
| Puma             | 4         | 0.32%   |
| P6               | 4         | 0.32%   |
| K10 Llano        | 3         | 0.24%   |
| Jaguar           | 3         | 0.24%   |
| Tremont          | 2         | 0.16%   |
| NetBurst         | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 702       | 47.95%  |
| Nvidia                     | 440       | 30.05%  |
| AMD                        | 301       | 20.56%  |
| Matrox Electronics Systems | 17        | 1.16%   |
| ASPEED Technology          | 4         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 49        | 3.28%   |
| Intel UHD Graphics 620                                                      | 46        | 3.08%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 45        | 3.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 39        | 2.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 38        | 2.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 36        | 2.41%   |
| Intel HD Graphics 620                                                       | 32        | 2.14%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 32        | 2.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 29        | 1.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 29        | 1.94%   |
| Intel HD Graphics 530                                                       | 28        | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 25        | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 24        | 1.61%   |
| Intel HD Graphics 5500                                                      | 23        | 1.54%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 23        | 1.54%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 19        | 1.27%   |
| Intel Core Processor Integrated Graphics Controller                         | 17        | 1.14%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 16        | 1.07%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 16        | 1.07%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 16        | 1.07%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 15        | 1%      |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 15        | 1%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 14        | 0.94%   |
| Intel HD Graphics 630                                                       | 14        | 0.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 14        | 0.94%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 14        | 0.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 13        | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 13        | 0.87%   |
| Nvidia GP108M [GeForce MX150]                                               | 12        | 0.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 12        | 0.8%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 10        | 0.67%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 10        | 0.67%   |
| AMD Raphael                                                                 | 10        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 9         | 0.6%    |
| Matrox Electronics Systems G200eR2                                          | 9         | 0.6%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9         | 0.6%    |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 9         | 0.6%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 9         | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 8         | 0.54%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 8         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 498       | 39.74%  |
| 1 x Nvidia           | 241       | 19.23%  |
| 1 x AMD              | 236       | 18.83%  |
| Intel + Nvidia       | 171       | 13.65%  |
| Intel + AMD          | 25        | 2%      |
| 2 x AMD              | 19        | 1.52%   |
| AMD + Nvidia         | 19        | 1.52%   |
| Other                | 18        | 1.44%   |
| 1 x Matrox           | 15        | 1.2%    |
| 2 x Nvidia           | 3         | 0.24%   |
| Nvidia + Matrox      | 2         | 0.16%   |
| AMD + ASPEED         | 2         | 0.16%   |
| 3 x Nvidia           | 1         | 0.08%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.08%   |
| Nvidia + ASPEED      | 1         | 0.08%   |
| 1 x ASPEED           | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 939       | 73.82%  |
| Proprietary | 271       | 21.31%  |
| Unknown     | 62        | 4.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 781       | 61.16%  |
| 1.01-2.0   | 120       | 9.4%    |
| 0.01-0.5   | 95        | 7.44%   |
| 3.01-4.0   | 79        | 6.19%   |
| 7.01-8.0   | 76        | 5.95%   |
| 0.51-1.0   | 46        | 3.6%    |
| 5.01-6.0   | 30        | 2.35%   |
| 8.01-16.0  | 30        | 2.35%   |
| 2.01-3.0   | 11        | 0.86%   |
| 16.01-24.0 | 7         | 0.55%   |
| 4.01-5.0   | 2         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 205       | 14.22%  |
| AU Optronics            | 152       | 10.54%  |
| LG Display              | 127       | 8.81%   |
| Dell                    | 108       | 7.49%   |
| Chimei Innolux          | 108       | 7.49%   |
| BOE                     | 87        | 6.03%   |
| BenQ                    | 61        | 4.23%   |
| AOC                     | 57        | 3.95%   |
| Hewlett-Packard         | 51        | 3.54%   |
| Acer                    | 50        | 3.47%   |
| Lenovo                  | 43        | 2.98%   |
| Philips                 | 41        | 2.84%   |
| Ancor Communications    | 41        | 2.84%   |
| Sharp                   | 40        | 2.77%   |
| Apple                   | 30        | 2.08%   |
| InfoVision              | 23        | 1.6%    |
| ASUSTek Computer        | 22        | 1.53%   |
| Goldstar                | 19        | 1.32%   |
| NEC Computers           | 14        | 0.97%   |
| Chi Mei Optoelectronics | 14        | 0.97%   |
| CSO                     | 11        | 0.76%   |
| Sony                    | 9         | 0.62%   |
| Panasonic               | 9         | 0.62%   |
| Eizo                    | 8         | 0.55%   |
| PANDA                   | 7         | 0.49%   |
| JDI                     | 7         | 0.49%   |
| Grundig                 | 6         | 0.42%   |
| Unknown                 | 5         | 0.35%   |
| MSI                     | 5         | 0.35%   |
| LG Electronics          | 4         | 0.28%   |
| Iiyama                  | 4         | 0.28%   |
| HVR                     | 4         | 0.28%   |
| Fujitsu Siemens         | 4         | 0.28%   |
| VOXICON                 | 3         | 0.21%   |
| ViewSonic               | 3         | 0.21%   |
| Vestel Elektronik       | 3         | 0.21%   |
| Gigabyte Technology     | 3         | 0.21%   |
| Denver                  | 3         | 0.21%   |
| AUS                     | 3         | 0.21%   |
| Toshiba                 | 2         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 8         | 0.53%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 7         | 0.46%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 509x286mm 23.0-inch         | 7         | 0.46%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 7         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch     | 7         | 0.46%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 6         | 0.4%    |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                | 6         | 0.4%    |
| Grundig WXGA GRU4448 1600x1200                                       | 6         | 0.4%    |
| Dell U2713HM DEL4080 2560x1440 600x340mm 27.2-inch                   | 6         | 0.4%    |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                   | 6         | 0.4%    |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 6         | 0.4%    |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch    | 5         | 0.33%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch   | 5         | 0.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch         | 5         | 0.33%   |
| Hewlett-Packard Z32x HWP3275 3840x2160 697x392mm 31.5-inch           | 5         | 0.33%   |
| Dell U2717D DEL40EA 2560x1440 597x336mm 27.0-inch                    | 5         | 0.33%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                   | 5         | 0.33%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                   | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch       | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 5         | 0.33%   |
| Acer XB271HU ACR0490 2560x1440 598x336mm 27.0-inch                   | 5         | 0.33%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch              | 4         | 0.27%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch | 4         | 0.27%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch     | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3859 1366x768 293x165mm 13.2-inch | 4         | 0.27%   |
| Samsung Electronics C34H89x SAM0E26 3440x1440 797x333mm 34.0-inch    | 4         | 0.27%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch         | 4         | 0.27%   |
| NEC Computers P403 NEC692B 1920x1080 886x498mm 40.0-inch             | 4         | 0.27%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 4         | 0.27%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 4         | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 4         | 0.27%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                       | 4         | 0.27%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                    | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch     | 4         | 0.27%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch       | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 4         | 0.27%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch         | 4         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 635       | 46.01%  |
| 3840x2160 (4K)     | 142       | 10.29%  |
| 1366x768 (WXGA)    | 132       | 9.57%   |
| 2560x1440 (QHD)    | 110       | 7.97%   |
| 1920x1200 (WUXGA)  | 67        | 4.86%   |
| 1600x900 (HD+)     | 38        | 2.75%   |
| 3440x1440          | 36        | 2.61%   |
| 2880x1800          | 19        | 1.38%   |
| 1680x1050 (WSXGA+) | 19        | 1.38%   |
| 3840x1080          | 18        | 1.3%    |
| 2560x1600          | 17        | 1.23%   |
| 1280x800 (WXGA)    | 17        | 1.23%   |
| Unknown            | 17        | 1.23%   |
| 1280x1024 (SXGA)   | 14        | 1.01%   |
| 3840x2400          | 9         | 0.65%   |
| 1440x900 (WXGA+)   | 8         | 0.58%   |
| 3840x1600          | 7         | 0.51%   |
| 3000x2000          | 7         | 0.51%   |
| 2160x1440          | 7         | 0.51%   |
| 1600x1200          | 7         | 0.51%   |
| 2560x1080          | 6         | 0.43%   |
| 1360x768           | 5         | 0.36%   |
| 2160x1200          | 4         | 0.29%   |
| 1280x720 (HD)      | 4         | 0.29%   |
| 1024x600           | 4         | 0.29%   |
| 2288x1287          | 3         | 0.22%   |
| 1920x540           | 3         | 0.22%   |
| 5120x1440          | 2         | 0.14%   |
| 4480x1440          | 2         | 0.14%   |
| 3200x1800 (QHD+)   | 2         | 0.14%   |
| 2736x1824          | 2         | 0.14%   |
| 9600x2160          | 1         | 0.07%   |
| 7680x1440          | 1         | 0.07%   |
| 7680x1080          | 1         | 0.07%   |
| 6880x1440          | 1         | 0.07%   |
| 5760x2160          | 1         | 0.07%   |
| 5520x1080          | 1         | 0.07%   |
| 5360x1440          | 1         | 0.07%   |
| 3840x1200          | 1         | 0.07%   |
| 3840x1100          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 263       | 18.33%  |
| 27      | 178       | 12.4%   |
| 24      | 161       | 11.22%  |
| 13      | 157       | 10.94%  |
| 14      | 150       | 10.45%  |
| Unknown | 72        | 5.02%   |
| 23      | 64        | 4.46%   |
| 17      | 55        | 3.83%   |
| 12      | 41        | 2.86%   |
| 31      | 38        | 2.65%   |
| 34      | 37        | 2.58%   |
| 21      | 20        | 1.39%   |
| 84      | 17        | 1.18%   |
| 40      | 17        | 1.18%   |
| 22      | 16        | 1.11%   |
| 16      | 14        | 0.98%   |
| 48      | 12        | 0.84%   |
| 54      | 11        | 0.77%   |
| 25      | 10        | 0.7%    |
| 19      | 10        | 0.7%    |
| 20      | 9         | 0.63%   |
| 32      | 8         | 0.56%   |
| 72      | 7         | 0.49%   |
| 37      | 7         | 0.49%   |
| 11      | 7         | 0.49%   |
| 49      | 5         | 0.35%   |
| 43      | 4         | 0.28%   |
| 39      | 4         | 0.28%   |
| 142     | 3         | 0.21%   |
| 55      | 3         | 0.21%   |
| 42      | 3         | 0.21%   |
| 35      | 3         | 0.21%   |
| 33      | 3         | 0.21%   |
| 26      | 3         | 0.21%   |
| 18      | 3         | 0.21%   |
| 10      | 3         | 0.21%   |
| 65      | 2         | 0.14%   |
| 60      | 2         | 0.14%   |
| 46      | 2         | 0.14%   |
| 36      | 2         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 489       | 35.18%  |
| 501-600        | 350       | 25.18%  |
| 201-300        | 138       | 9.93%   |
| 351-400        | 76        | 5.47%   |
| Unknown        | 72        | 5.18%   |
| 601-700        | 64        | 4.6%    |
| 701-800        | 49        | 3.53%   |
| 401-500        | 45        | 3.24%   |
| 1001-1500      | 38        | 2.73%   |
| 801-900        | 33        | 2.37%   |
| 1501-2000      | 25        | 1.8%    |
| 901-1000       | 7         | 0.5%    |
| More than 2000 | 3         | 0.22%   |
| 101-200        | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 935       | 74.03%  |
| 16/10   | 159       | 12.59%  |
| Unknown | 56        | 4.43%   |
| 21/9    | 48        | 3.8%    |
| 3/2     | 23        | 1.82%   |
| 32/9    | 16        | 1.27%   |
| 5/4     | 14        | 1.11%   |
| 4/3     | 5         | 0.4%    |
| 1.00    | 3         | 0.24%   |
| 6/5     | 1         | 0.08%   |
| 3.76    | 1         | 0.08%   |
| 3.40    | 1         | 0.08%   |
| 0.80    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 259       | 18.23%  |
| 81-90          | 235       | 16.54%  |
| 201-250        | 190       | 13.37%  |
| 301-350        | 179       | 12.6%   |
| 351-500        | 90        | 6.33%   |
| 71-80          | 72        | 5.07%   |
| Unknown        | 72        | 5.07%   |
| 251-300        | 68        | 4.79%   |
| 501-1000       | 54        | 3.8%    |
| More than 1000 | 49        | 3.45%   |
| 121-130        | 49        | 3.45%   |
| 61-70          | 38        | 2.67%   |
| 151-200        | 26        | 1.83%   |
| 111-120        | 15        | 1.06%   |
| 51-60          | 8         | 0.56%   |
| 131-140        | 7         | 0.49%   |
| 41-50          | 3         | 0.21%   |
| 141-150        | 3         | 0.21%   |
| 91-100         | 3         | 0.21%   |
| 1-40           | 1         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 423       | 30.52%  |
| 51-100        | 417       | 30.09%  |
| 101-120       | 266       | 19.19%  |
| 161-240       | 112       | 8.08%   |
| Unknown       | 72        | 5.19%   |
| More than 240 | 60        | 4.33%   |
| 1-50          | 36        | 2.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 919       | 71.19%  |
| 2     | 258       | 19.98%  |
| 0     | 64        | 4.96%   |
| 3     | 46        | 3.56%   |
| 4     | 4         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 797       | 42.8%   |
| Realtek Semiconductor                  | 500       | 26.85%  |
| Qualcomm Atheros                       | 134       | 7.2%    |
| Broadcom                               | 112       | 6.02%   |
| MediaTek                               | 26        | 1.4%    |
| Broadcom Limited                       | 25        | 1.34%   |
| Sierra Wireless                        | 18        | 0.97%   |
| Ralink Technology                      | 17        | 0.91%   |
| Ericsson Business Mobile Networks      | 17        | 0.91%   |
| NetGear                                | 16        | 0.86%   |
| Ralink                                 | 15        | 0.81%   |
| Dell                                   | 14        | 0.75%   |
| ASUSTek Computer                       | 14        | 0.75%   |
| TP-Link                                | 13        | 0.7%    |
| Nvidia                                 | 11        | 0.59%   |
| Microsoft                              | 11        | 0.59%   |
| Hewlett-Packard                        | 10        | 0.54%   |
| Marvell Technology Group               | 9         | 0.48%   |
| Lenovo                                 | 9         | 0.48%   |
| D-Link                                 | 8         | 0.43%   |
| Samsung Electronics                    | 7         | 0.38%   |
| Aquantia                               | 7         | 0.38%   |
| Qualcomm Atheros Communications        | 6         | 0.32%   |
| DisplayLink                            | 6         | 0.32%   |
| Linksys                                | 5         | 0.27%   |
| Motorola PCS                           | 4         | 0.21%   |
| Microchip Technology                   | 4         | 0.21%   |
| FIBOCOM                                | 4         | 0.21%   |
| Qualcomm                               | 3         | 0.16%   |
| Huawei Technologies                    | 3         | 0.16%   |
| Chu Yuen Enterprise                    | 3         | 0.16%   |
| ASIX Electronics                       | 3         | 0.16%   |
| Wacom                                  | 2         | 0.11%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.11%   |
| Sigma Designs                          | 2         | 0.11%   |
| Raspberry Pi                           | 2         | 0.11%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.11%   |
| Mellanox Technologies                  | 2         | 0.11%   |
| JMicron Technology                     | 2         | 0.11%   |
| Arduino SA                             | 2         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 320       | 14.01%  |
| Intel Wi-Fi 6 AX200                                                    | 88        | 3.85%   |
| Intel Wireless 8265 / 8275                                             | 71        | 3.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 63        | 2.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 59        | 2.58%   |
| Intel I211 Gigabit Network Connection                                  | 56        | 2.45%   |
| Realtek RTL8125 2.5GbE Controller                                      | 43        | 1.88%   |
| Intel Wireless 8260                                                    | 42        | 1.84%   |
| Intel Wireless 7265                                                    | 39        | 1.71%   |
| Intel Ethernet Controller I225-V                                       | 35        | 1.53%   |
| Intel Wireless 7260                                                    | 32        | 1.4%    |
| Intel Ethernet Connection (2) I219-V                                   | 29        | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 26        | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 25        | 1.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 24        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 23        | 1.01%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 22        | 0.96%   |
| Intel Ethernet Connection I217-LM                                      | 22        | 0.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21        | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 20        | 0.88%   |
| Intel Ethernet Connection (7) I219-V                                   | 20        | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 20        | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                   | 19        | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                  | 19        | 0.83%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 18        | 0.79%   |
| Intel Wi-Fi 6 AX201                                                    | 18        | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 17        | 0.74%   |
| Intel Ethernet Connection (6) I219-V                                   | 17        | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 17        | 0.74%   |
| Intel Centrino Ultimate-N 6300                                         | 16        | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                                  | 15        | 0.66%   |
| Intel 82579V Gigabit Network Connection                                | 15        | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 14        | 0.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 14        | 0.61%   |
| Intel Ethernet Connection I219-LM                                      | 14        | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 14        | 0.61%   |
| Intel Centrino Advanced-N 6235                                         | 14        | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 13        | 0.57%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]            | 13        | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 13        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 600       | 56.02%  |
| Qualcomm Atheros                | 105       | 9.8%    |
| Realtek Semiconductor           | 100       | 9.34%   |
| Broadcom                        | 77        | 7.19%   |
| MediaTek                        | 25        | 2.33%   |
| Broadcom Limited                | 21        | 1.96%   |
| Sierra Wireless                 | 18        | 1.68%   |
| Ralink Technology               | 17        | 1.59%   |
| NetGear                         | 16        | 1.49%   |
| Ralink                          | 15        | 1.4%    |
| ASUSTek Computer                | 14        | 1.31%   |
| TP-Link                         | 13        | 1.21%   |
| Microsoft                       | 9         | 0.84%   |
| Dell                            | 8         | 0.75%   |
| D-Link                          | 7         | 0.65%   |
| Qualcomm Atheros Communications | 6         | 0.56%   |
| Linksys                         | 4         | 0.37%   |
| FIBOCOM                         | 4         | 0.37%   |
| Qualcomm                        | 3         | 0.28%   |
| Hewlett-Packard                 | 3         | 0.28%   |
| Chu Yuen Enterprise             | 3         | 0.28%   |
| Wacom                           | 2         | 0.19%   |
| Wilocity                        | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 88        | 8.2%    |
| Intel Wireless 8265 / 8275                                     | 71        | 6.62%   |
| Intel Wireless 8260                                            | 42        | 3.91%   |
| Intel Wireless 7265                                            | 39        | 3.63%   |
| Intel Wireless 7260                                            | 32        | 2.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 26        | 2.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 25        | 2.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 24        | 2.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 23        | 2.14%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 22        | 2.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 20        | 1.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 20        | 1.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 18        | 1.68%   |
| Intel Wi-Fi 6 AX201                                            | 18        | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 1.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 17        | 1.58%   |
| Intel Centrino Ultimate-N 6300                                 | 16        | 1.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 14        | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 14        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 14        | 1.3%    |
| Intel Centrino Advanced-N 6235                                 | 14        | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13        | 1.21%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 13        | 1.21%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 13        | 1.21%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 13        | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 12        | 1.12%   |
| Sierra Wireless EM7455                                         | 11        | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 11        | 1.03%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 11        | 1.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 10        | 0.93%   |
| Intel Wireless 3165                                            | 10        | 0.93%   |
| Intel Wireless 3160                                            | 10        | 0.93%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 10        | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9         | 0.84%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 8         | 0.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 0.75%   |
| Intel WiFi Link 5100                                           | 8         | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 8         | 0.75%   |
| Intel Centrino Wireless-N 2230                                 | 8         | 0.75%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 8         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 486       | 42.93%  |
| Realtek Semiconductor                  | 452       | 39.93%  |
| Broadcom                               | 56        | 4.95%   |
| Qualcomm Atheros                       | 51        | 4.51%   |
| Nvidia                                 | 11        | 0.97%   |
| Marvell Technology Group               | 9         | 0.8%    |
| Lenovo                                 | 9         | 0.8%    |
| Samsung Electronics                    | 7         | 0.62%   |
| Aquantia                               | 7         | 0.62%   |
| DisplayLink                            | 6         | 0.53%   |
| Broadcom Limited                       | 6         | 0.53%   |
| Huawei Technologies                    | 3         | 0.27%   |
| ASIX Electronics                       | 3         | 0.27%   |
| Raspberry Pi                           | 2         | 0.18%   |
| Microsoft                              | 2         | 0.18%   |
| Mellanox Technologies                  | 2         | 0.18%   |
| JMicron Technology                     | 2         | 0.18%   |
| Hewlett-Packard                        | 2         | 0.18%   |
| T & A Mobile Phones                    | 1         | 0.09%   |
| Standard Microsystems                  | 1         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.09%   |
| OPPO Electronics                       | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.09%   |
| NetXen Incorporated                    | 1         | 0.09%   |
| Microchip Technology                   | 1         | 0.09%   |
| Linksys                                | 1         | 0.09%   |
| Google                                 | 1         | 0.09%   |
| Dell                                   | 1         | 0.09%   |
| D-Link                                 | 1         | 0.09%   |
| Cisco Systems                          | 1         | 0.09%   |
| ATEN International                     | 1         | 0.09%   |
| Apple                                  | 1         | 0.09%   |
| American Megatrends                    | 1         | 0.09%   |
| 3Com                                   | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 320       | 27.44%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 63        | 5.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 59        | 5.06%   |
| Intel I211 Gigabit Network Connection                                  | 56        | 4.8%    |
| Realtek RTL8125 2.5GbE Controller                                      | 43        | 3.69%   |
| Intel Ethernet Controller I225-V                                       | 35        | 3%      |
| Intel Ethernet Connection (2) I219-V                                   | 29        | 2.49%   |
| Intel Ethernet Connection I217-LM                                      | 22        | 1.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21        | 1.8%    |
| Intel Ethernet Connection (7) I219-V                                   | 20        | 1.72%   |
| Intel Ethernet Connection (4) I219-V                                   | 19        | 1.63%   |
| Intel Ethernet Connection (4) I219-LM                                  | 19        | 1.63%   |
| Intel Ethernet Connection (6) I219-V                                   | 17        | 1.46%   |
| Intel Ethernet Connection (2) I219-LM                                  | 15        | 1.29%   |
| Intel 82579V Gigabit Network Connection                                | 15        | 1.29%   |
| Intel Ethernet Connection I219-LM                                      | 14        | 1.2%    |
| Intel Ethernet Connection (2) I218-V                                   | 13        | 1.11%   |
| Intel Ethernet Connection I219-V                                       | 12        | 1.03%   |
| Intel Ethernet Connection I218-LM                                      | 12        | 1.03%   |
| Intel I210 Gigabit Network Connection                                  | 11        | 0.94%   |
| Intel Ethernet Connection (3) I218-LM                                  | 11        | 0.94%   |
| Intel Ethernet Connection (2) I218-LM                                  | 10        | 0.86%   |
| Intel 82577LM Gigabit Network Connection                               | 10        | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 9         | 0.77%   |
| Intel Ethernet Connection (7) I219-LM                                  | 9         | 0.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 8         | 0.69%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 7         | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 7         | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.51%   |
| Intel I350 Gigabit Network Connection                                  | 6         | 0.51%   |
| Intel Ethernet Connection I217-V                                       | 6         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                                  | 6         | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                                  | 6         | 0.51%   |
| Intel Ethernet Connection (13) I219-V                                  | 6         | 0.51%   |
| Intel 82574L Gigabit Network Connection                                | 6         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 5         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 5         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5         | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5         | 0.43%   |
| Intel Ethernet Connection (10) I219-V                                  | 5         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1047      | 50.31%  |
| WiFi     | 988       | 47.48%  |
| Modem    | 35        | 1.68%   |
| Unknown  | 11        | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 773       | 59.6%   |
| Ethernet | 523       | 40.32%  |
| Unknown  | 1         | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 696       | 55.59%  |
| 1     | 477       | 38.1%   |
| 3     | 44        | 3.51%   |
| 0     | 25        | 2%      |
| 4     | 7         | 0.56%   |
| 6     | 3         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1086      | 84.91%  |
| Yes  | 193       | 15.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 485       | 58.15%  |
| Broadcom                        | 55        | 6.59%   |
| Realtek Semiconductor           | 47        | 5.64%   |
| Qualcomm Atheros Communications | 34        | 4.08%   |
| Apple                           | 32        | 3.84%   |
| Cambridge Silicon Radio         | 31        | 3.72%   |
| Foxconn / Hon Hai               | 28        | 3.36%   |
| IMC Networks                    | 27        | 3.24%   |
| ASUSTek Computer                | 25        | 3%      |
| Lite-On Technology              | 20        | 2.4%    |
| Hewlett-Packard                 | 13        | 1.56%   |
| Dell                            | 10        | 1.2%    |
| MediaTek                        | 6         | 0.72%   |
| HTC (High Tech Computer)        | 4         | 0.48%   |
| Belkin Components               | 4         | 0.48%   |
| TP-Link                         | 2         | 0.24%   |
| Realtek                         | 2         | 0.24%   |
| Marvell Semiconductor           | 2         | 0.24%   |
| Integrated System Solution      | 2         | 0.24%   |
| Toshiba                         | 1         | 0.12%   |
| Ralink Technology               | 1         | 0.12%   |
| Ralink                          | 1         | 0.12%   |
| Edimax Technology               | 1         | 0.12%   |
| Actions                         | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                               | 102       | 12.19%  |
| Intel Bluetooth wireless interface                                   | 81        | 9.68%   |
| Intel AX200 Bluetooth                                                | 81        | 9.68%   |
| Intel AX201 Bluetooth                                                | 71        | 8.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 49        | 5.85%   |
| Intel AX211 Bluetooth                                                | 39        | 4.66%   |
| Realtek Bluetooth Radio                                              | 33        | 3.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 31        | 3.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 21        | 2.51%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 18        | 2.15%   |
| Intel AX210 Bluetooth                                                | 16        | 1.91%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 15        | 1.79%   |
| IMC Networks Bluetooth Radio                                         | 13        | 1.55%   |
| Apple Bluetooth USB Host Controller                                  | 13        | 1.55%   |
| Apple Bluetooth Host Controller                                      | 13        | 1.55%   |
| Lite-On Bluetooth Device                                             | 10        | 1.19%   |
| HP Broadcom 2070 Bluetooth Combo                                     | 10        | 1.19%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 10        | 1.19%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 10        | 1.19%   |
| Qualcomm Atheros  Bluetooth Device                                   | 9         | 1.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 9         | 1.08%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 9         | 1.08%   |
| Foxconn / Hon Hai Wireless_Device                                    | 9         | 1.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 9         | 1.08%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 7         | 0.84%   |
| Realtek 802.11ac WLAN Adapter                                        | 5         | 0.6%    |
| MediaTek Wireless_Device                                             | 5         | 0.6%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 5         | 0.6%    |
| IMC Networks Bluetooth Device                                        | 5         | 0.6%    |
| ASUS ASUS USB-BT500                                                  | 5         | 0.6%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 5         | 0.6%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 0.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 4         | 0.48%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4         | 0.48%   |
| Dell BCM20702A0 Bluetooth Module                                     | 4         | 0.48%   |
| Broadcom HP Portable SoftSailing                                     | 4         | 0.48%   |
| Broadcom BCM20702A0                                                  | 4         | 0.48%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 4         | 0.48%   |
| Qualcomm Atheros AR3012 Bluetooth                                    | 3         | 0.36%   |
| IMC Networks Wireless_Device                                         | 3         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 897       | 47.74%  |
| AMD                                          | 357       | 19%     |
| Nvidia                                       | 330       | 17.56%  |
| C-Media Electronics                          | 36        | 1.92%   |
| SteelSeries ApS                              | 23        | 1.22%   |
| Logitech                                     | 22        | 1.17%   |
| Realtek Semiconductor                        | 20        | 1.06%   |
| Kingston Technology                          | 16        | 0.85%   |
| Lenovo                                       | 14        | 0.75%   |
| GN Netcom                                    | 11        | 0.59%   |
| Focusrite-Novation                           | 10        | 0.53%   |
| ASUSTek Computer                             | 10        | 0.53%   |
| Blue Microphones                             | 9         | 0.48%   |
| Corsair                                      | 8         | 0.43%   |
| Razer USA                                    | 7         | 0.37%   |
| Creative Labs                                | 7         | 0.37%   |
| SAVITECH                                     | 6         | 0.32%   |
| Texas Instruments                            | 5         | 0.27%   |
| Sony                                         | 5         | 0.27%   |
| Hewlett-Packard                              | 5         | 0.27%   |
| Plantronics                                  | 4         | 0.21%   |
| FiiO Electronics Technology                  | 4         | 0.21%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.16%   |
| XMOS                                         | 3         | 0.16%   |
| RODE Microphones                             | 3         | 0.16%   |
| M-Audio                                      | 3         | 0.16%   |
| JMTek                                        | 3         | 0.16%   |
| DSEA A/S                                     | 3         | 0.16%   |
| DCMT Technology                              | 3         | 0.16%   |
| Creative Technology                          | 3         | 0.16%   |
| Yamaha                                       | 2         | 0.11%   |
| Samson Technologies                          | 2         | 0.11%   |
| Roland                                       | 2         | 0.11%   |
| ROCCAT                                       | 2         | 0.11%   |
| Musical Fidelity                             | 2         | 0.11%   |
| Micro Star International                     | 2         | 0.11%   |
| GYROCOM C&C                                  | 2         | 0.11%   |
| Elgato Systems                               | 2         | 0.11%   |
| Asahi Kasei Microsystems                     | 2         | 0.11%   |
| ZOOM                                         | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 128       | 5.82%   |
| AMD Family 17h/19h HD Audio Controller                                     | 97        | 4.41%   |
| AMD Starship/Matisse HD Audio Controller                                   | 80        | 3.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 79        | 3.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 64        | 2.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 60        | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 60        | 2.73%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 52        | 2.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 49        | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 47        | 2.14%   |
| Intel Haswell-ULT HD Audio Controller                                      | 41        | 1.86%   |
| Intel 8 Series HD Audio Controller                                         | 40        | 1.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 39        | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 35        | 1.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 32        | 1.45%   |
| Intel Broadwell-U Audio Controller                                         | 32        | 1.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 31        | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 31        | 1.41%   |
| AMD FCH Azalia Controller                                                  | 30        | 1.36%   |
| Nvidia GP104 High Definition Audio Controller                              | 29        | 1.32%   |
| Intel 200 Series PCH HD Audio                                              | 28        | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 28        | 1.27%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 27        | 1.23%   |
| Nvidia GA104 High Definition Audio Controller                              | 26        | 1.18%   |
| Nvidia GP106 High Definition Audio Controller                              | 25        | 1.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 25        | 1.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 24        | 1.09%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 21        | 0.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 21        | 0.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 20        | 0.91%   |
| Nvidia GM204 High Definition Audio Controller                              | 19        | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 19        | 0.86%   |
| Intel Comet Lake PCH cAVS                                                  | 19        | 0.86%   |
| Realtek Semiconductor USB Audio                                            | 18        | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 18        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 17        | 0.77%   |
| Intel Comet Lake PCH-LP cAVS                                               | 17        | 0.77%   |
| AMD Navi 10 HDMI Audio                                                     | 17        | 0.77%   |
| Nvidia GP107GL High Definition Audio Controller                            | 16        | 0.73%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 15        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 192       | 23.85%  |
| SK hynix            | 174       | 21.61%  |
| Kingston            | 110       | 13.66%  |
| Micron Technology   | 76        | 9.44%   |
| Corsair             | 71        | 8.82%   |
| Crucial             | 46        | 5.71%   |
| Unknown             | 42        | 5.22%   |
| G.Skill             | 28        | 3.48%   |
| Ramaxel Technology  | 11        | 1.37%   |
| Elpida              | 11        | 1.37%   |
| A-DATA Technology   | 8         | 0.99%   |
| Unknown             | 6         | 0.75%   |
| Nanya Technology    | 4         | 0.5%    |
| Unknown (ABCD)      | 2         | 0.25%   |
| Team                | 2         | 0.25%   |
| Patriot             | 2         | 0.25%   |
| Transcend           | 1         | 0.12%   |
| Toshiba             | 1         | 0.12%   |
| Timetec             | 1         | 0.12%   |
| SK_Hynix            | 1         | 0.12%   |
| Samsung / Micron    | 1         | 0.12%   |
| Hewlett-Packard     | 1         | 0.12%   |
| GSkill              | 1         | 0.12%   |
| GeIL                | 1         | 0.12%   |
| fef5                | 1         | 0.12%   |
| ASint Technology    | 1         | 0.12%   |
| Apacer              | 1         | 0.12%   |
| 98000817752EA5DF    | 1         | 0.12%   |
| 98000817752E90DE    | 1         | 0.12%   |
| 98000817752E75DE    | 1         | 0.12%   |
| 98000817702EBEDE    | 1         | 0.12%   |
| 98000817702EBDDE    | 1         | 0.12%   |
| 98000817702EBBDF    | 1         | 0.12%   |
| 98000817702E73DE    | 1         | 0.12%   |
| 98000817702E65DE    | 1         | 0.12%   |
| 48spaces            | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s        | 11        | 1.3%    |
| SK hynix RAM HMA41GR7MFR4N-TF 8GB DIMM DDR4 2133MT/s          | 8         | 0.94%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s         | 8         | 0.94%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 7         | 0.82%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 7         | 0.82%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 7         | 0.82%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s        | 6         | 0.71%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 6         | 0.71%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 6         | 0.71%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s             | 6         | 0.71%   |
| Unknown                                                       | 6         | 0.71%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                     | 5         | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                      | 5         | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 5         | 0.59%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8192MB DIMM DDR4 2400MT/s       | 5         | 0.59%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 5         | 0.59%   |
| Samsung RAM Module 4GB SODIMM DDR3 1867MT/s                   | 5         | 0.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 5         | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 5         | 0.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 5         | 0.59%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 5         | 0.59%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s         | 5         | 0.59%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s      | 5         | 0.59%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s              | 5         | 0.59%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3866MT/s        | 5         | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 4         | 0.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 4         | 0.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 4         | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 4         | 0.47%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 4         | 0.47%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s     | 4         | 0.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 4         | 0.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 4         | 0.47%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s        | 4         | 0.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 4         | 0.47%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s  | 4         | 0.47%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s    | 4         | 0.47%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s        | 4         | 0.47%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s             | 4         | 0.47%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s         | 4         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 372       | 52.99%  |
| DDR3    | 182       | 25.93%  |
| LPDDR3  | 37        | 5.27%   |
| LPDDR4  | 30        | 4.27%   |
| DDR5    | 26        | 3.7%    |
| DDR2    | 17        | 2.42%   |
| LPDDR5  | 13        | 1.85%   |
| Unknown | 11        | 1.57%   |
| SDRAM   | 9         | 1.28%   |
| DRAM    | 3         | 0.43%   |
| DDR     | 2         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 359       | 50.92%  |
| DIMM         | 247       | 35.04%  |
| Row Of Chips | 80        | 11.35%  |
| Chip         | 12        | 1.7%    |
| Unknown      | 5         | 0.71%   |
| FB-DIMM      | 2         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 322       | 42.88%  |
| 4096  | 173       | 23.04%  |
| 16384 | 170       | 22.64%  |
| 2048  | 40        | 5.33%   |
| 32768 | 36        | 4.79%   |
| 1024  | 8         | 1.07%   |
| 512   | 1         | 0.13%   |
| 128   | 1         | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 121       | 15.96%  |
| 2667    | 107       | 14.12%  |
| 3200    | 105       | 13.85%  |
| 2133    | 76        | 10.03%  |
| 2400    | 59        | 7.78%   |
| 1333    | 29        | 3.83%   |
| 3600    | 27        | 3.56%   |
| 1867    | 23        | 3.03%   |
| 1334    | 15        | 1.98%   |
| 667     | 15        | 1.98%   |
| 6400    | 14        | 1.85%   |
| 4267    | 14        | 1.85%   |
| 3800    | 13        | 1.72%   |
| 6000    | 9         | 1.19%   |
| 4800    | 9         | 1.19%   |
| 3866    | 8         | 1.06%   |
| 3733    | 8         | 1.06%   |
| 1800    | 8         | 1.06%   |
| 3400    | 7         | 0.92%   |
| 3000    | 7         | 0.92%   |
| 3466    | 6         | 0.79%   |
| 2666    | 6         | 0.79%   |
| 1067    | 6         | 0.79%   |
| 1066    | 5         | 0.66%   |
| 4199    | 4         | 0.53%   |
| 2933    | 4         | 0.53%   |
| 2800    | 4         | 0.53%   |
| 800     | 4         | 0.53%   |
| 8400    | 3         | 0.4%    |
| 5600    | 3         | 0.4%    |
| 4266    | 3         | 0.4%    |
| 3333    | 3         | 0.4%    |
| 3100    | 3         | 0.4%    |
| Unknown | 3         | 0.4%    |
| 5900    | 2         | 0.26%   |
| 4000    | 2         | 0.26%   |
| 3266    | 2         | 0.26%   |
| 3151    | 2         | 0.26%   |
| 3066    | 2         | 0.26%   |
| 2733    | 2         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 31.58%  |
| Brother Industries  | 6         | 31.58%  |
| Samsung Electronics | 2         | 10.53%  |
| Canon               | 2         | 10.53%  |
| Seiko Epson         | 1         | 5.26%   |
| Pantum              | 1         | 5.26%   |
| Kyocera             | 1         | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP ENVY Photo 6200 series            | 2         | 10.53%  |
| Seiko Epson L3250 Series             | 1         | 5.26%   |
| Samsung ML-216x Series Laser Printer | 1         | 5.26%   |
| Samsung M2020 Series                 | 1         | 5.26%   |
| Pantum P2500W series                 | 1         | 5.26%   |
| Kyocera ECOSYS P2235dn               | 1         | 5.26%   |
| HP Printing Support                  | 1         | 5.26%   |
| HP LaserJet Professional P 1102w     | 1         | 5.26%   |
| HP DeskJet F300 series               | 1         | 5.26%   |
| HP Deskjet 2540 series               | 1         | 5.26%   |
| Canon TS5300 series                  | 1         | 5.26%   |
| Canon PIXMA MX530 Series             | 1         | 5.26%   |
| Brother QL-800 P-touch Label Printer | 1         | 5.26%   |
| Brother QL-550 printer               | 1         | 5.26%   |
| Brother PT-2450DX                    | 1         | 5.26%   |
| Brother MFC-L2710DW series           | 1         | 5.26%   |
| Brother HL-1210W series              | 1         | 5.26%   |
| Brother DCP-8085DN                   | 1         | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 6         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| Canon CanoScan LiDE 110      | 2         | 33.33%  |
| Canon CanoScan 9000F Mark II | 2         | 33.33%  |
| Canon CanoScan LiDE 200      | 1         | 16.67%  |
| Canon CanoScan 8800F         | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 171       | 21.43%  |
| IMC Networks                           | 80        | 10.03%  |
| Logitech                               | 72        | 9.02%   |
| Bison Electronics                      | 56        | 7.02%   |
| Microdia                               | 50        | 6.27%   |
| Sunplus Innovation Technology          | 48        | 6.02%   |
| Realtek Semiconductor                  | 42        | 5.26%   |
| Apple                                  | 32        | 4.01%   |
| Lite-On Technology                     | 29        | 3.63%   |
| Cheng Uei Precision Industry (Foxlink) | 29        | 3.63%   |
| Quanta                                 | 28        | 3.51%   |
| Acer                                   | 21        | 2.63%   |
| Suyin                                  | 16        | 2.01%   |
| Luxvisions Innotech Limited            | 13        | 1.63%   |
| Lenovo                                 | 12        | 1.5%    |
| Microsoft                              | 11        | 1.38%   |
| Samsung Electronics                    | 9         | 1.13%   |
| Creative Technology                    | 8         | 1%      |
| Alcor Micro                            | 8         | 1%      |
| Silicon Motion                         | 6         | 0.75%   |
| Syntek                                 | 5         | 0.63%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.63%   |
| Razer USA                              | 5         | 0.63%   |
| Primax Electronics                     | 5         | 0.63%   |
| Z-Star Microelectronics                | 3         | 0.38%   |
| Omnivision                             | 3         | 0.38%   |
| MacroSilicon                           | 3         | 0.38%   |
| Sunplus Technology                     | 2         | 0.25%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.25%   |
| Sonix Technology                       | 2         | 0.25%   |
| ShineTech                              | 2         | 0.25%   |
| Ricoh                                  | 2         | 0.25%   |
| Generalplus Technology                 | 2         | 0.25%   |
| Cubeternet                             | 2         | 0.25%   |
| ALi                                    | 2         | 0.25%   |
| Y Media                                | 1         | 0.13%   |
| Technologies                           | 1         | 0.13%   |
| TANDBERG                               | 1         | 0.13%   |
| Owon                                   | 1         | 0.13%   |
| Novatek Microelectronics               | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 57        | 7.03%   |
| IMC Networks Integrated Camera                      | 31        | 3.82%   |
| Microdia Integrated_Webcam_HD                       | 27        | 3.33%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 24        | 2.96%   |
| Chicony HP HD Camera                                | 16        | 1.97%   |
| Chicony HD WebCam                                   | 14        | 1.73%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 14        | 1.73%   |
| Realtek Integrated_Webcam_HD                        | 13        | 1.6%    |
| Lite-On Integrated Camera                           | 13        | 1.6%    |
| Chicony HP HD Webcam                                | 13        | 1.6%    |
| Bison Integrated Camera                             | 13        | 1.6%    |
| Sunplus Integrated_Webcam_HD                        | 12        | 1.48%   |
| Logitech HD Pro Webcam C920                         | 11        | 1.36%   |
| Logitech C922 Pro Stream Webcam                     | 11        | 1.36%   |
| Lite-On HP HD Camera                                | 10        | 1.23%   |
| Samsung Galaxy series, misc. (MTP mode)             | 9         | 1.11%   |
| Bison SunplusIT Integrated Camera                   | 9         | 1.11%   |
| Bison HD Webcam                                     | 8         | 0.99%   |
| Quanta HP HD Camera                                 | 7         | 0.86%   |
| Logitech Webcam C270                                | 7         | 0.86%   |
| Lenovo Integrated Webcam [R5U877]                   | 7         | 0.86%   |
| Chicony Integrated HP HD Webcam                     | 7         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 7         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 7         | 0.86%   |
| Apple FaceTime HD Camera (Built-in)                 | 7         | 0.86%   |
| Sunplus HD WebCam                                   | 6         | 0.74%   |
| Realtek USB2.0 HD UVC WebCam                        | 6         | 0.74%   |
| Quanta HD User Facing                               | 6         | 0.74%   |
| Acer Integrated Camera                              | 6         | 0.74%   |
| Sunplus Laptop Integrated Webcam HD                 | 5         | 0.62%   |
| Sunplus ASUS Webcam                                 | 5         | 0.62%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera     | 5         | 0.62%   |
| Quanta HP TrueVision HD Camera                      | 5         | 0.62%   |
| Microsoft LifeCam Cinema                            | 5         | 0.62%   |
| Microdia Integrated Webcam                          | 5         | 0.62%   |
| Luxvisions Innotech Limited Integrated Camera       | 5         | 0.62%   |
| Logitech Webcam C925e                               | 5         | 0.62%   |
| Lite-On HP HD Webcam                                | 5         | 0.62%   |
| Chicony Lenovo EasyCamera                           | 5         | 0.62%   |
| Chicony HP Wide Vision HD Camera                    | 5         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 78        | 41.05%  |
| Synaptics                          | 63        | 33.16%  |
| Upek                               | 18        | 9.47%   |
| Shenzhen Goodix Technology         | 13        | 6.84%   |
| Elan Microelectronics              | 6         | 3.16%   |
| Samsung Electronics                | 3         | 1.58%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 1.58%   |
| LighTuning Technology              | 3         | 1.58%   |
| AuthenTec                          | 3         | 1.58%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 23        | 12.11%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 17        | 8.95%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 8.95%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 7.37%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 5.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 4.74%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 4.74%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 3.68%   |
| Validity Sensors VFS491                                                    | 6         | 3.16%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 3.16%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 3.16%   |
| Elan ELAN:Fingerprint                                                      | 6         | 3.16%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 2.63%   |
| Synaptics WBDI                                                             | 5         | 2.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.11%   |
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 2.11%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.58%   |
| Synaptics UWP WBDI Device                                                  | 3         | 1.58%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.58%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.58%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.58%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.58%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 1.58%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 1.58%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 1.05%   |
| Synaptics UWP WBDI                                                         | 2         | 1.05%   |
| Synaptics  WBDI                                                            | 2         | 1.05%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.05%   |
| AuthenTec AES2810                                                          | 2         | 1.05%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.53%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.53%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.53%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.53%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.53%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.53%   |
| AuthenTec AES1600                                                          | 1         | 0.53%   |
| Unknown                                                                    | 1         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 41        | 43.16%  |
| Broadcom              | 35        | 36.84%  |
| Upek                  | 9         | 9.47%   |
| Lenovo                | 5         | 5.26%   |
| OmniKey               | 2         | 2.11%   |
| Yubico.com            | 1         | 1.05%   |
| Hewlett-Packard       | 1         | 1.05%   |
| Gemalto (was Gemplus) | 1         | 1.05%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 41        | 43.16%  |
| Broadcom 58200                                                               | 11        | 11.58%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 10.53%  |
| Broadcom 5880                                                                | 10        | 10.53%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 9.47%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 4.21%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 2.11%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 1.05%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.05%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.05%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 807       | 62.9%   |
| 1     | 365       | 28.45%  |
| 2     | 85        | 6.63%   |
| 3     | 20        | 1.56%   |
| 5     | 3         | 0.23%   |
| 4     | 2         | 0.16%   |
| 7     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 189       | 32.25%  |
| Graphics card            | 99        | 16.89%  |
| Chipcard                 | 79        | 13.48%  |
| Net/wireless             | 71        | 12.12%  |
| Unassigned class         | 35        | 5.97%   |
| Multimedia controller    | 31        | 5.29%   |
| Camera                   | 19        | 3.24%   |
| Communication controller | 16        | 2.73%   |
| Bluetooth                | 10        | 1.71%   |
| Sound                    | 9         | 1.54%   |
| Card reader              | 9         | 1.54%   |
| Storage                  | 5         | 0.85%   |
| Net/ethernet             | 5         | 0.85%   |
| Wireless                 | 4         | 0.68%   |
| Storage/raid             | 2         | 0.34%   |
| Modem                    | 2         | 0.34%   |
| Dvb card                 | 1         | 0.17%   |

