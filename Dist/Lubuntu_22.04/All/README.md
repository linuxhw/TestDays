Lubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Lubuntu_22.04/Notebook/README.md).

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

Total: 171

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Acer          | AO722                       | Notebook    | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2d8e324570](https://linux-hardware.org/?probe=2d8e324570) | Nov 26, 2022 |
| Intel         | BTC-T37                     | Desktop     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [2574454ebe](https://linux-hardware.org/?probe=2574454ebe) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [3b7077c5ab](https://linux-hardware.org/?probe=3b7077c5ab) | Nov 19, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a922f68180](https://linux-hardware.org/?probe=a922f68180) | Nov 03, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | Notebook    | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Google        | Apel                        | Notebook    | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | Notebook    | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | Desktop     | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | Notebook    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Dell          | 0R849J A00                  | Desktop     | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| ASUSTek       | UX360CAK                    | Convertible | [015df11bc4](https://linux-hardware.org/?probe=015df11bc4) | Sep 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c45724d6d3](https://linux-hardware.org/?probe=c45724d6d3) | Sep 20, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [2f9ab4273a](https://linux-hardware.org/?probe=2f9ab4273a) | Sep 20, 2022 |
| Gateway       | NE46R                       | Notebook    | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | Notebook    | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Dell          | 0J584C A00                  | Desktop     | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | Notebook    | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | Notebook    | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| OEM           | Unknown                     | Notebook    | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 8768 A                      | Desktop     | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | Desktop     | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | Desktop     | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Dell          | Precision 3510              | Notebook    | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | Notebook    | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Google        | Celes                       | Notebook    | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Dell          | XPS M1330                   | Notebook    | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| Dell          | 0X8582                      | Desktop     | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| Sony          | VPCEB15FM                   | Notebook    | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | 0X8582                      | Desktop     | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | Desktop     | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| HP            | 1495                        | Desktop     | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| HP            | 1495                        | Desktop     | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Gateway       | Sonic-C                     | Notebook    | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| Dell          | Latitude XT                 | Notebook    | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | Notebook    | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| ASUSTek       | PRIME X370-A                | Desktop     | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Intel         | W7650                       | Notebook    | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [8fe291470d](https://linux-hardware.org/?probe=8fe291470d) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [63ccee44b1](https://linux-hardware.org/?probe=63ccee44b1) | May 28, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [c77f0f6328](https://linux-hardware.org/?probe=c77f0f6328) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | Notebook    | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | Desktop     | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | Notebook    | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | Notebook    | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Intel         | W7650                       | Notebook    | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [727b677ecb](https://linux-hardware.org/?probe=727b677ecb) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| HP            | Pavilion dv4                | Notebook    | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Intel         | W7650                       | Notebook    | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Intel         | W7650                       | Notebook    | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.15.0-43-generic           | 19        | 13.57%  |
| 5.15.0-25-generic           | 11        | 7.86%   |
| 5.15.0-47-generic           | 10        | 7.14%   |
| 5.15.0-30-generic           | 10        | 7.14%   |
| 5.15.0-46-generic           | 9         | 6.43%   |
| 5.15.0-41-generic           | 9         | 6.43%   |
| 5.15.0-27-generic           | 9         | 6.43%   |
| 5.15.0-52-generic           | 8         | 5.71%   |
| 5.15.0-53-generic           | 7         | 5%      |
| 5.15.0-50-generic           | 6         | 4.29%   |
| 5.15.0-48-generic           | 6         | 4.29%   |
| 5.15.0-40-generic           | 6         | 4.29%   |
| 5.15.0-39-generic           | 4         | 2.86%   |
| 5.15.0-35-generic           | 4         | 2.86%   |
| 5.15.0-33-generic           | 4         | 2.86%   |
| 5.15.0-37-generic           | 2         | 1.43%   |
| 5.15.0-23-generic           | 2         | 1.43%   |
| 5.15.0-18-generic           | 2         | 1.43%   |
| 6.0.8-060008-generic        | 1         | 0.71%   |
| 5.19.8-xanmod1              | 1         | 0.71%   |
| 5.19.11-ux360cak            | 1         | 0.71%   |
| 5.19.0-16.2-liquorix-amd64  | 1         | 0.71%   |
| 5.19.0-051900-generic       | 1         | 0.71%   |
| 5.18.0-051800-generic       | 1         | 0.71%   |
| 5.15.0-54-generic           | 1         | 0.71%   |
| 5.15.0-41-lowlatency        | 1         | 0.71%   |
| 5.15.0-362206031516-generic | 1         | 0.71%   |
| 5.15.0-28-generic           | 1         | 0.71%   |
| 5.15.0-1017-raspi           | 1         | 0.71%   |
| 5.14.0-1040-oem             | 1         | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 128       | 94.81%  |
| 5.19.0  | 2         | 1.48%   |
| 6.0.8   | 1         | 0.74%   |
| 5.19.8  | 1         | 0.74%   |
| 5.19.11 | 1         | 0.74%   |
| 5.18.0  | 1         | 0.74%   |
| 5.14.0  | 1         | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 128       | 94.81%  |
| 5.19    | 4         | 2.96%   |
| 6.0     | 1         | 0.74%   |
| 5.18    | 1         | 0.74%   |
| 5.14    | 1         | 0.74%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 131       | 99.24%  |
| aarch64 | 1         | 0.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 127       | 96.21%  |
| LXDE       | 3         | 2.27%   |
| X-Cinnamon | 2         | 1.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 126       | 94.03%  |
| Tty         | 6         | 4.48%   |
| Wayland     | 1         | 0.75%   |
| Unspecified | 1         | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 115       | 87.12%  |
| LightDM | 6         | 4.55%   |
| Unknown | 6         | 4.55%   |
| GDM3    | 2         | 1.52%   |
| XDM     | 1         | 0.76%   |
| SLiM    | 1         | 0.76%   |
| LXDM    | 1         | 0.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 36        | 27.07%  |
| fr_FR | 12        | 9.02%   |
| it_IT | 11        | 8.27%   |
| en_GB | 9         | 6.77%   |
| de_DE | 9         | 6.77%   |
| C     | 7         | 5.26%   |
| pt_BR | 6         | 4.51%   |
| pl_PL | 6         | 4.51%   |
| es_CR | 4         | 3.01%   |
| es_AR | 4         | 3.01%   |
| en_AG | 4         | 3.01%   |
| nl_BE | 3         | 2.26%   |
| en_AU | 3         | 2.26%   |
| es_MX | 2         | 1.5%    |
| en_CA | 2         | 1.5%    |
| el_GR | 2         | 1.5%    |
| tr_TR | 1         | 0.75%   |
| sv_SE | 1         | 0.75%   |
| ru_UA | 1         | 0.75%   |
| ru_RU | 1         | 0.75%   |
| ja_JP | 1         | 0.75%   |
| fr_CA | 1         | 0.75%   |
| fi_FI | 1         | 0.75%   |
| es_ES | 1         | 0.75%   |
| es_CL | 1         | 0.75%   |
| en_ZA | 1         | 0.75%   |
| en_PH | 1         | 0.75%   |
| cv_RU | 1         | 0.75%   |
| aa_DJ | 1         | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 89        | 66.92%  |
| EFI  | 44        | 33.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 122       | 91.73%  |
| Overlay | 8         | 6.02%   |
| Btrfs   | 2         | 1.5%    |
| Ext2    | 1         | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 58        | 43.61%  |
| Unknown | 43        | 32.33%  |
| MBR     | 32        | 24.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 113       | 84.96%  |
| Yes       | 20        | 15.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 95        | 71.43%  |
| Yes       | 38        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 20        | 15.15%  |
| Lenovo                  | 19        | 14.39%  |
| Hewlett-Packard         | 15        | 11.36%  |
| ASUSTek Computer        | 13        | 9.85%   |
| MSI                     | 6         | 4.55%   |
| Acer                    | 6         | 4.55%   |
| Unknown                 | 6         | 4.55%   |
| Google                  | 5         | 3.79%   |
| Fujitsu                 | 5         | 3.79%   |
| ASRock                  | 4         | 3.03%   |
| AMI                     | 4         | 3.03%   |
| Sony                    | 3         | 2.27%   |
| Gigabyte Technology     | 3         | 2.27%   |
| Apple                   | 3         | 2.27%   |
| Toshiba                 | 2         | 1.52%   |
| Mediacom                | 2         | 1.52%   |
| Intel                   | 2         | 1.52%   |
| Gateway                 | 2         | 1.52%   |
| ZOTAC                   | 1         | 0.76%   |
| Samsung Electronics     | 1         | 0.76%   |
| Raspberry Pi Foundation | 1         | 0.76%   |
| Pretech                 | 1         | 0.76%   |
| Prestigio               | 1         | 0.76%   |
| Positivo                | 1         | 0.76%   |
| Pegatron                | 1         | 0.76%   |
| Packard Bell            | 1         | 0.76%   |
| OEM                     | 1         | 0.76%   |
| Kiano                   | 1         | 0.76%   |
| IFSA                    | 1         | 0.76%   |
| Chuwi                   | 1         | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 5.3%    |
| Mediacom WinPad 11,6 FullHD- WPU11         | 2         | 1.52%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 1.52%   |
| HP Pavilion g6                             | 2         | 1.52%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 1.52%   |
| Dell Dimension 9100                        | 2         | 1.52%   |
| Apple MacBookPro8,1                        | 2         | 1.52%   |
| ZOTAC NM10                                 | 1         | 0.76%   |
| Toshiba Satellite Pro S500                 | 1         | 0.76%   |
| Toshiba Satellite L40                      | 1         | 0.76%   |
| Sony VPCEB15FM                             | 1         | 0.76%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.76%   |
| Sony SVE14A2V1EW                           | 1         | 0.76%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.76%   |
| RPi Raspberry Pi                           | 1         | 0.76%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.76%   |
| Prestigio PSB141C01BFH                     | 1         | 0.76%   |
| Positivo i500pro                           | 1         | 0.76%   |
| Pegatron AY748AA-ABA p6320y                | 1         | 0.76%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.76%   |
| MSI MS-7D09                                | 1         | 0.76%   |
| MSI MS-7C96                                | 1         | 0.76%   |
| MSI MS-7C37                                | 1         | 0.76%   |
| MSI MS-7B86                                | 1         | 0.76%   |
| MSI MS-7978                                | 1         | 0.76%   |
| MSI MS-7641                                | 1         | 0.76%   |
| Lenovo Z70-80 80FG                         | 1         | 0.76%   |
| Lenovo Yoga C940-14IIL 81Q9                | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0WE02   | 1         | 0.76%   |
| Lenovo ThinkPad T430 2342A19               | 1         | 0.76%   |
| Lenovo ThinkPad T410 2537CS0               | 1         | 0.76%   |
| Lenovo ThinkPad SL510 2847CXG              | 1         | 0.76%   |
| Lenovo ThinkPad E550 20DF00CUFR            | 1         | 0.76%   |
| Lenovo ThinkCentre M83 10ANCTO1WW          | 1         | 0.76%   |
| Lenovo ThinkCentre M600 10KGS09S00         | 1         | 0.76%   |
| Lenovo MIIX 310-10ICR 80SG                 | 1         | 0.76%   |
| Lenovo IdeaPad S145-15IGM 81MX             | 1         | 0.76%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK      | 1         | 0.76%   |
| Lenovo IdeaPad 330-15IKB Touch 81DJ        | 1         | 0.76%   |
| Lenovo G50-70 20351                        | 1         | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Unknown                | 7         | 5.3%    |
| Lenovo ThinkPad        | 5         | 3.79%   |
| Lenovo IdeaPad         | 5         | 3.79%   |
| Dell Latitude          | 5         | 3.79%   |
| HP Pavilion            | 4         | 3.03%   |
| Fujitsu LIFEBOOK       | 4         | 3.03%   |
| Acer Aspire            | 4         | 3.03%   |
| HP ProBook             | 3         | 2.27%   |
| Dell OptiPlex          | 3         | 2.27%   |
| Toshiba Satellite      | 2         | 1.52%   |
| Mediacom WinPad        | 2         | 1.52%   |
| Lenovo ThinkCentre     | 2         | 1.52%   |
| Dell XPS               | 2         | 1.52%   |
| Dell Vostro            | 2         | 1.52%   |
| Dell Studio            | 2         | 1.52%   |
| Dell Precision         | 2         | 1.52%   |
| Dell Dimension         | 2         | 1.52%   |
| ASUS PRIME             | 2         | 1.52%   |
| Apple MacBookPro8      | 2         | 1.52%   |
| ZOTAC NM10             | 1         | 0.76%   |
| Sony VPCEB15FM         | 1         | 0.76%   |
| Sony VGN-SZ71WN        | 1         | 0.76%   |
| Sony SVE14A2V1EW       | 1         | 0.76%   |
| Samsung 300V3A         | 1         | 0.76%   |
| RPi Raspberry          | 1         | 0.76%   |
| Pretech EVE            | 1         | 0.76%   |
| Prestigio PSB141C01BFH | 1         | 0.76%   |
| Positivo i500pro       | 1         | 0.76%   |
| Pegatron AY748AA-ABA   | 1         | 0.76%   |
| Packard Bell EasyNote  | 1         | 0.76%   |
| MSI MS-7D09            | 1         | 0.76%   |
| MSI MS-7C96            | 1         | 0.76%   |
| MSI MS-7C37            | 1         | 0.76%   |
| MSI MS-7B86            | 1         | 0.76%   |
| MSI MS-7978            | 1         | 0.76%   |
| MSI MS-7641            | 1         | 0.76%   |
| Lenovo Z70-80          | 1         | 0.76%   |
| Lenovo Yoga            | 1         | 0.76%   |
| Lenovo MIIX            | 1         | 0.76%   |
| Lenovo G50-70          | 1         | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 15        | 11.36%  |
| 2020    | 10        | 7.58%   |
| 2019    | 10        | 7.58%   |
| 2014    | 10        | 7.58%   |
| 2013    | 10        | 7.58%   |
| 2012    | 9         | 6.82%   |
| 2010    | 9         | 6.82%   |
| 2008    | 9         | 6.82%   |
| 2017    | 8         | 6.06%   |
| 2016    | 8         | 6.06%   |
| 2015    | 8         | 6.06%   |
| 2021    | 7         | 5.3%    |
| 2009    | 5         | 3.79%   |
| 2007    | 5         | 3.79%   |
| 2022    | 4         | 3.03%   |
| 2018    | 2         | 1.52%   |
| 2006    | 2         | 1.52%   |
| Unknown | 1         | 0.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 79        | 59.85%  |
| Desktop        | 44        | 33.33%  |
| Convertible    | 4         | 3.03%   |
| Tablet         | 2         | 1.52%   |
| Mini pc        | 2         | 1.52%   |
| System on chip | 1         | 0.76%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 128       | 96.97%  |
| Enabled  | 4         | 3.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 127       | 96.21%  |
| Yes  | 5         | 3.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 46        | 34.59%  |
| 4.01-8.0    | 31        | 23.31%  |
| 8.01-16.0   | 15        | 11.28%  |
| 1.01-2.0    | 14        | 10.53%  |
| 16.01-24.0  | 13        | 9.77%   |
| 32.01-64.0  | 6         | 4.51%   |
| 2.01-3.0    | 5         | 3.76%   |
| 0.51-1.0    | 2         | 1.5%    |
| 64.01-256.0 | 1         | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 65        | 48.51%  |
| 0.51-1.0 | 33        | 24.63%  |
| 2.01-3.0 | 26        | 19.4%   |
| 4.01-8.0 | 5         | 3.73%   |
| 3.01-4.0 | 4         | 2.99%   |
| 0.01-0.5 | 1         | 0.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 93        | 70.45%  |
| 2      | 31        | 23.48%  |
| 0      | 3         | 2.27%   |
| 5      | 2         | 1.52%   |
| 7      | 1         | 0.76%   |
| 6      | 1         | 0.76%   |
| 3      | 1         | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 58.33%  |
| Yes       | 55        | 41.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 81.06%  |
| No        | 25        | 18.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 74.24%  |
| No        | 34        | 25.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 51.13%  |
| No        | 65        | 48.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 23        | 17.42%  |
| Germany      | 13        | 9.85%   |
| Italy        | 12        | 9.09%   |
| France       | 12        | 9.09%   |
| Poland       | 8         | 6.06%   |
| UK           | 7         | 5.3%    |
| Brazil       | 7         | 5.3%    |
| Costa Rica   | 4         | 3.03%   |
| Belgium      | 4         | 3.03%   |
| Argentina    | 4         | 3.03%   |
| Russia       | 3         | 2.27%   |
| Canada       | 3         | 2.27%   |
| Australia    | 3         | 2.27%   |
| Vietnam      | 2         | 1.52%   |
| Ukraine      | 2         | 1.52%   |
| Turkey       | 2         | 1.52%   |
| Sweden       | 2         | 1.52%   |
| Spain        | 2         | 1.52%   |
| Mexico       | 2         | 1.52%   |
| Hungary      | 2         | 1.52%   |
| Greece       | 2         | 1.52%   |
| South Africa | 1         | 0.76%   |
| Saudi Arabia | 1         | 0.76%   |
| Romania      | 1         | 0.76%   |
| Portugal     | 1         | 0.76%   |
| Philippines  | 1         | 0.76%   |
| Netherlands  | 1         | 0.76%   |
| Latvia       | 1         | 0.76%   |
| Kenya        | 1         | 0.76%   |
| Japan        | 1         | 0.76%   |
| Indonesia    | 1         | 0.76%   |
| Finland      | 1         | 0.76%   |
| Chile        | 1         | 0.76%   |
| Bulgaria     | 1         | 0.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Paris                     | 4         | 3.03%   |
| Heredia                   | 4         | 3.03%   |
| Melbourne                 | 3         | 2.27%   |
| Sarospatak                | 2         | 1.52%   |
| Porto Alegre              | 2         | 1.52%   |
| Novo Gama                 | 2         | 1.52%   |
| Largo                     | 2         | 1.52%   |
| Kyiv                      | 2         | 1.52%   |
| Zawiercie                 | 1         | 0.76%   |
| Yoshkar-Ola               | 1         | 0.76%   |
| Yorkville                 | 1         | 0.76%   |
| Wolfhagen                 | 1         | 0.76%   |
| Wetteren                  | 1         | 0.76%   |
| Washington                | 1         | 0.76%   |
| Warsaw                    | 1         | 0.76%   |
| Volzhskiy                 | 1         | 0.76%   |
| Verona                    | 1         | 0.76%   |
| Varna                     | 1         | 0.76%   |
| Valentigney               | 1         | 0.76%   |
| Valencia                  | 1         | 0.76%   |
| Tychy                     | 1         | 0.76%   |
| Thessaloniki              | 1         | 0.76%   |
| Texas City                | 1         | 0.76%   |
| Taylorsville              | 1         | 0.76%   |
| Tandil                    | 1         | 0.76%   |
| Surabaya                  | 1         | 0.76%   |
| Stuttgart                 | 1         | 0.76%   |
| Strzyzow                  | 1         | 0.76%   |
| Stockholm                 | 1         | 0.76%   |
| Southampton               | 1         | 0.76%   |
| South Burlington          | 1         | 0.76%   |
| Sonico                    | 1         | 0.76%   |
| Sao Paulo                 | 1         | 0.76%   |
| Santiago                  | 1         | 0.76%   |
| Saint-Raymond-de-Portneuf | 1         | 0.76%   |
| Roswell                   | 1         | 0.76%   |
| Rossano Veneto            | 1         | 0.76%   |
| Riyadh                    | 1         | 0.76%   |
| Riverenert                | 1         | 0.76%   |
| Rio de Janeiro            | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 26     | 14.81%  |
| Unknown             | 18        | 26     | 11.11%  |
| Samsung Electronics | 18        | 23     | 11.11%  |
| WDC                 | 16        | 20     | 9.88%   |
| Toshiba             | 11        | 12     | 6.79%   |
| Hitachi             | 11        | 12     | 6.79%   |
| SanDisk             | 8         | 8      | 4.94%   |
| Kingston            | 7         | 8      | 4.32%   |
| Crucial             | 5         | 5      | 3.09%   |
| Micron Technology   | 3         | 3      | 1.85%   |
| Intel               | 3         | 4      | 1.85%   |
| Apacer              | 3         | 3      | 1.85%   |
| SPCC                | 2         | 3      | 1.23%   |
| HGST                | 2         | 2      | 1.23%   |
| GOODRAM             | 2         | 2      | 1.23%   |
| WD MediaMax         | 1         | 1      | 0.62%   |
| W800S               | 1         | 1      | 0.62%   |
| UMIS                | 1         | 1      | 0.62%   |
| Transcend           | 1         | 1      | 0.62%   |
| TO Exter            | 1         | 1      | 0.62%   |
| Teclast             | 1         | 1      | 0.62%   |
| T-FORCE             | 1         | 1      | 0.62%   |
| SK hynix            | 1         | 1      | 0.62%   |
| RSH-319             | 1         | 1      | 0.62%   |
| Rogueware           | 1         | 1      | 0.62%   |
| PNY                 | 1         | 1      | 0.62%   |
| Patriot             | 1         | 1      | 0.62%   |
| Maxtor              | 1         | 1      | 0.62%   |
| LITEONIT            | 1         | 1      | 0.62%   |
| Leqixiang           | 1         | 1      | 0.62%   |
| Lenovo              | 1         | 1      | 0.62%   |
| Kston               | 1         | 3      | 0.62%   |
| KIOXIA              | 1         | 1      | 0.62%   |
| KINGPOWER           | 1         | 1      | 0.62%   |
| HUSKY               | 1         | 1      | 0.62%   |
| HGST HUS            | 1         | 2      | 0.62%   |
| Gigabyte Technology | 1         | 1      | 0.62%   |
| Fujitsu             | 1         | 1      | 0.62%   |
| External            | 1         | 1      | 0.62%   |
| China               | 1         | 1      | 0.62%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST9500325AS 500GB            | 4         | 2.23%   |
| Seagate ST500DM002-1BD142 500GB      | 4         | 2.23%   |
| SanDisk DF4032  32GB                 | 3         | 1.68%   |
| Unknown SD/MMC/MS PRO 8GB            | 2         | 1.12%   |
| Unknown SC64G  64GB                  | 2         | 1.12%   |
| Unknown NCard  32GB                  | 2         | 1.12%   |
| Unknown MMC64G  64GB                 | 2         | 1.12%   |
| Unknown MMC Card  64GB               | 2         | 1.12%   |
| Unknown DA4032  32GB                 | 2         | 1.12%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.12%   |
| Toshiba DT01ACA100 1TB               | 2         | 1.12%   |
| SPCC Solid State Disk 120GB          | 2         | 1.12%   |
| Seagate ST3120213AS 120GB            | 2         | 1.12%   |
| Samsung HD502HJ 500GB                | 2         | 1.12%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 1.12%   |
| Apacer 16GB SATA Flash Drive SSD     | 2         | 1.12%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.56%   |
| WDC WDS500G2B0A 500GB SSD            | 1         | 0.56%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.56%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.56%   |
| WDC WD800BB-00CAA1 80GB              | 1         | 0.56%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.56%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.56%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1         | 0.56%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.56%   |
| WDC WD3200BPVT-00HXZT3 320GB         | 1         | 0.56%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.56%   |
| WDC WD30EZRZ-00GXCB0 3TB             | 1         | 0.56%   |
| WDC WD2500AAJS-07M0A0 250GB          | 1         | 0.56%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 0.56%   |
| WDC WD20EZBX-00AYRA0 2TB             | 1         | 0.56%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.56%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.56%   |
| WDC WD10EZRZ-00Z5HB0 1TB             | 1         | 0.56%   |
| WDC WD10EURX-63C57Y0 1TB             | 1         | 0.56%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.56%   |
| WD MediaMax WL250GSA872 250GB        | 1         | 0.56%   |
| W800S 256GB SSD                      | 1         | 0.56%   |
| Unknown SF64G  64GB                  | 1         | 0.56%   |
| Unknown SD  32GB                     | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 25     | 32.43%  |
| WDC                 | 13        | 15     | 17.57%  |
| Hitachi             | 11        | 12     | 14.86%  |
| Toshiba             | 10        | 11     | 13.51%  |
| Samsung Electronics | 6         | 9      | 8.11%   |
| Unknown             | 2         | 2      | 2.7%    |
| HGST                | 2         | 2      | 2.7%    |
| WD MediaMax         | 1         | 1      | 1.35%   |
| RSH-319             | 1         | 1      | 1.35%   |
| Maxtor              | 1         | 1      | 1.35%   |
| Fujitsu             | 1         | 1      | 1.35%   |
| External            | 1         | 1      | 1.35%   |
| Apricorn            | 1         | 1      | 1.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 11     | 20.37%  |
| Kingston            | 5         | 6      | 9.26%   |
| Crucial             | 4         | 4      | 7.41%   |
| WDC                 | 3         | 3      | 5.56%   |
| SanDisk             | 3         | 3      | 5.56%   |
| Apacer              | 3         | 3      | 5.56%   |
| SPCC                | 2         | 3      | 3.7%    |
| Micron Technology   | 2         | 2      | 3.7%    |
| Intel               | 2         | 2      | 3.7%    |
| GOODRAM             | 2         | 2      | 3.7%    |
| W800S               | 1         | 1      | 1.85%   |
| Transcend           | 1         | 1      | 1.85%   |
| Toshiba             | 1         | 1      | 1.85%   |
| TO Exter            | 1         | 1      | 1.85%   |
| Teclast             | 1         | 1      | 1.85%   |
| Rogueware           | 1         | 1      | 1.85%   |
| PNY                 | 1         | 1      | 1.85%   |
| Patriot             | 1         | 1      | 1.85%   |
| LITEONIT            | 1         | 1      | 1.85%   |
| Leqixiang           | 1         | 1      | 1.85%   |
| Lenovo              | 1         | 1      | 1.85%   |
| Kston               | 1         | 3      | 1.85%   |
| KINGPOWER           | 1         | 1      | 1.85%   |
| HUSKY               | 1         | 1      | 1.85%   |
| Gigabyte Technology | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 1      | 1.85%   |
| 2.5"                | 1         | 2      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 61        | 82     | 40.67%  |
| SSD     | 52        | 59     | 34.67%  |
| MMC     | 21        | 29     | 14%     |
| NVMe    | 14        | 17     | 9.33%   |
| Unknown | 2         | 4      | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 99        | 136    | 70.71%  |
| MMC  | 21        | 29     | 15%     |
| NVMe | 14        | 17     | 10%     |
| SAS  | 6         | 9      | 4.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 85        | 105    | 73.91%  |
| 0.51-1.0   | 20        | 22     | 17.39%  |
| 1.01-2.0   | 5         | 6      | 4.35%   |
| 2.01-3.0   | 3         | 5      | 2.61%   |
| 3.01-4.0   | 1         | 1      | 0.87%   |
| 4.01-10.0  | 1         | 2      | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 30.08%  |
| 251-500        | 33        | 24.81%  |
| 51-100         | 15        | 11.28%  |
| 21-50          | 13        | 9.77%   |
| 1-20           | 13        | 9.77%   |
| 501-1000       | 7         | 5.26%   |
| 2001-3000      | 4         | 3.01%   |
| 1001-2000      | 4         | 3.01%   |
| More than 3000 | 3         | 2.26%   |
| Unknown        | 1         | 0.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 75        | 56.39%  |
| 21-50          | 26        | 19.55%  |
| 101-250        | 10        | 7.52%   |
| 51-100         | 8         | 6.02%   |
| 251-500        | 5         | 3.76%   |
| 501-1000       | 3         | 2.26%   |
| More than 3000 | 2         | 1.5%    |
| 1001-2000      | 2         | 1.5%    |
| 2001-3000      | 1         | 0.75%   |
| Unknown        | 1         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                 | 2         | 2      | 10.53%  |
| Apacer 16GB SATA Flash Drive SSD          | 2         | 2      | 10.53%  |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1      | 5.26%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD050 500GB                  | 1         | 1      | 5.26%   |
| Toshiba MK6465GSX 640GB                   | 1         | 1      | 5.26%   |
| Seagate ST9320325AS 320GB                 | 1         | 1      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 5.26%   |
| Seagate ST4000DM004-2CV104 4TB            | 1         | 1      | 5.26%   |
| Seagate ST320LT020-9YG142 320GB           | 1         | 1      | 5.26%   |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1      | 5.26%   |
| Samsung Electronics HM121HI 120GB         | 1         | 4      | 5.26%   |
| Samsung Electronics HD161HJ 160GB         | 1         | 1      | 5.26%   |
| Micron Technology MTFDDAV256TBN 256GB SSD | 1         | 1      | 5.26%   |
| Hitachi HTS545050A7E380 500GB             | 1         | 1      | 5.26%   |
| Fujitsu MHY2120BH 120GB                   | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 42.11%  |
| Toshiba             | 3         | 3      | 15.79%  |
| Samsung Electronics | 2         | 5      | 10.53%  |
| Apacer              | 2         | 2      | 10.53%  |
| WDC                 | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| Hitachi             | 1         | 1      | 5.26%   |
| Fujitsu             | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 50%     |
| Toshiba             | 3         | 3      | 18.75%  |
| Samsung Electronics | 2         | 5      | 12.5%   |
| WDC                 | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |
| Fujitsu             | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 19     | 84.21%  |
| SSD  | 3         | 3      | 15.79%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 73        | 109    | 54.07%  |
| Works    | 43        | 60     | 31.85%  |
| Malfunc  | 19        | 22     | 14.07%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 86        | 66.67%  |
| AMD                         | 21        | 16.28%  |
| Nvidia                      | 5         | 3.88%   |
| Samsung Electronics         | 3         | 2.33%   |
| SanDisk                     | 2         | 1.55%   |
| Kingston Technology Company | 2         | 1.55%   |
| JMicron Technology          | 2         | 1.55%   |
| Union Memory (Shenzhen)     | 1         | 0.78%   |
| SK hynix                    | 1         | 0.78%   |
| Seagate Technology          | 1         | 0.78%   |
| Micron/Crucial Technology   | 1         | 0.78%   |
| Micron Technology           | 1         | 0.78%   |
| Marvell Technology Group    | 1         | 0.78%   |
| KIOXIA                      | 1         | 0.78%   |
| ASMedia Technology          | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 12        | 7.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 4.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6         | 3.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6         | 3.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 3.87%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 3.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 3.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 3.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 2.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 1.94%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 1.94%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.29%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.29%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.29%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 1.29%   |
| AMD FCH IDE Controller                                                           | 2         | 1.29%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.65%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.65%   |
| Seagate FireCuda 520 SSD                                                         | 1         | 0.65%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.65%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.65%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.65%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.65%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.65%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                     | 1         | 0.65%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.65%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.65%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 92        | 67.15%  |
| IDE  | 26        | 18.98%  |
| NVMe | 13        | 9.49%   |
| RAID | 6         | 4.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 108       | 81.82%  |
| AMD    | 23        | 17.42%  |
| ARM    | 1         | 0.76%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 3.03%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 3.03%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 4         | 3.03%   |
| Intel Pentium D CPU 2.80GHz                   | 2         | 1.52%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 1.52%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 1.52%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.52%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 1.52%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.52%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.52%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.52%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 1.52%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.52%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 2         | 1.52%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 1.52%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 1.52%   |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 0.76%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz           | 1         | 0.76%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.76%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.76%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.76%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.76%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.76%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.76%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.76%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 0.76%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.76%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 0.76%   |
| Intel Core i7 CPU 920 @ 2.67GHz               | 1         | 0.76%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 1         | 0.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.76%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 1         | 0.76%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 0.76%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 1         | 0.76%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1         | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 24        | 18.18%  |
| Intel Celeron      | 20        | 15.15%  |
| Intel Core i3      | 14        | 10.61%  |
| Intel Atom         | 14        | 10.61%  |
| Intel Core 2 Duo   | 12        | 9.09%   |
| Intel Core i7      | 10        | 7.58%   |
| Intel Pentium      | 3         | 2.27%   |
| AMD Ryzen 5        | 3         | 2.27%   |
| AMD A6             | 3         | 2.27%   |
| Intel Xeon         | 2         | 1.52%   |
| Intel Pentium Dual | 2         | 1.52%   |
| Intel Pentium D    | 2         | 1.52%   |
| Intel Core 2 Quad  | 2         | 1.52%   |
| AMD Ryzen 7        | 2         | 1.52%   |
| AMD FX             | 2         | 1.52%   |
| AMD E1             | 2         | 1.52%   |
| AMD Athlon 64 X2   | 2         | 1.52%   |
| Other              | 1         | 0.76%   |
| Intel Core m3      | 1         | 0.76%   |
| Intel Core i9      | 1         | 0.76%   |
| Intel Core 2       | 1         | 0.76%   |
| AMD Ryzen 9        | 1         | 0.76%   |
| AMD Phenom II X6   | 1         | 0.76%   |
| AMD Phenom II X4   | 1         | 0.76%   |
| AMD G              | 1         | 0.76%   |
| AMD E              | 1         | 0.76%   |
| AMD C-60           | 1         | 0.76%   |
| AMD A8             | 1         | 0.76%   |
| AMD A4             | 1         | 0.76%   |
| AMD A10            | 1         | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 76        | 57.58%  |
| 4      | 42        | 31.82%  |
| 6      | 4         | 3.03%   |
| 1      | 4         | 3.03%   |
| 8      | 3         | 2.27%   |
| 3      | 2         | 1.52%   |
| 10     | 1         | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 132       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 74        | 56.06%  |
| 2      | 58        | 43.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 132       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 38.64%  |
| 0x206a7    | 8         | 6.06%   |
| 0x406c4    | 7         | 5.3%    |
| 0x306a9    | 5         | 3.79%   |
| 0x706e5    | 4         | 3.03%   |
| 0x406c3    | 4         | 3.03%   |
| 0x1067a    | 4         | 3.03%   |
| 0x806ec    | 3         | 2.27%   |
| 0x40651    | 3         | 2.27%   |
| 0x306c3    | 3         | 2.27%   |
| 0x106ca    | 3         | 2.27%   |
| 0x806e9    | 2         | 1.52%   |
| 0x706a8    | 2         | 1.52%   |
| 0x6fd      | 2         | 1.52%   |
| 0x6fb      | 2         | 1.52%   |
| 0x506e3    | 2         | 1.52%   |
| 0x20655    | 2         | 1.52%   |
| 0x06006705 | 2         | 1.52%   |
| 0x05000119 | 2         | 1.52%   |
| 0xa0653    | 1         | 0.76%   |
| 0x906ed    | 1         | 0.76%   |
| 0x906c0    | 1         | 0.76%   |
| 0x806eb    | 1         | 0.76%   |
| 0x806ea    | 1         | 0.76%   |
| 0x706a1    | 1         | 0.76%   |
| 0x6fa      | 1         | 0.76%   |
| 0x6f6      | 1         | 0.76%   |
| 0x506c9    | 1         | 0.76%   |
| 0x30679    | 1         | 0.76%   |
| 0x30678    | 1         | 0.76%   |
| 0x106a5    | 1         | 0.76%   |
| 0x0a50000c | 1         | 0.76%   |
| 0x0a50000b | 1         | 0.76%   |
| 0x0a201009 | 1         | 0.76%   |
| 0x08001138 | 1         | 0.76%   |
| 0x0700010f | 1         | 0.76%   |
| 0x06003106 | 1         | 0.76%   |
| 0x06001119 | 1         | 0.76%   |
| 0x06001116 | 1         | 0.76%   |
| 0x06000852 | 1         | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 21        | 15.91%  |
| SandyBridge   | 14        | 10.61%  |
| Penryn        | 9         | 6.82%   |
| IvyBridge     | 9         | 6.82%   |
| Haswell       | 9         | 6.82%   |
| KabyLake      | 8         | 6.06%   |
| Core          | 8         | 6.06%   |
| Goldmont plus | 7         | 5.3%    |
| Piledriver    | 4         | 3.03%   |
| IceLake       | 4         | 3.03%   |
| Zen 3         | 3         | 2.27%   |
| Westmere      | 3         | 2.27%   |
| Skylake       | 3         | 2.27%   |
| Bonnell       | 3         | 2.27%   |
| Bobcat        | 3         | 2.27%   |
| Zen+          | 2         | 1.52%   |
| NetBurst      | 2         | 1.52%   |
| Nehalem       | 2         | 1.52%   |
| K8 Hammer     | 2         | 1.52%   |
| K10           | 2         | 1.52%   |
| Excavator     | 2         | 1.52%   |
| CometLake     | 2         | 1.52%   |
| Broadwell     | 2         | 1.52%   |
| Zen           | 1         | 0.76%   |
| Tremont       | 1         | 0.76%   |
| Steamroller   | 1         | 0.76%   |
| Puma          | 1         | 0.76%   |
| K10 Llano     | 1         | 0.76%   |
| Jaguar        | 1         | 0.76%   |
| Goldmont      | 1         | 0.76%   |
| Unknown       | 1         | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 87        | 61.27%  |
| AMD    | 31        | 21.83%  |
| Nvidia | 24        | 16.9%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 10.53%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 8.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 4.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 3.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 2.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.97%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.97%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 1.97%   |
| Nvidia GT218 [ION]                                                                       | 2         | 1.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.32%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.32%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.32%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.32%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.32%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 1.32%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.32%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.32%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2         | 1.32%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2         | 1.32%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2         | 1.32%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.32%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1         | 0.66%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.66%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.66%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.66%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.66%   |
| Nvidia GM200GL [Tesla M40]                                                               | 1         | 0.66%   |
| Nvidia GM200GL [Quadro M6000]                                                            | 1         | 0.66%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1         | 0.66%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1         | 0.66%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.66%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1         | 0.66%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 75        | 56.82%  |
| 1 x AMD            | 20        | 15.15%  |
| 1 x Nvidia         | 19        | 14.39%  |
| Intel + AMD        | 5         | 3.79%   |
| 2 x AMD            | 4         | 3.03%   |
| Other              | 3         | 2.27%   |
| Intel + Nvidia     | 3         | 2.27%   |
| Intel + 2 x Nvidia | 1         | 0.76%   |
| Intel + 2 x AMD    | 1         | 0.76%   |
| AMD + Nvidia       | 1         | 0.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 120       | 90.91%  |
| Proprietary | 8         | 6.06%   |
| Unknown     | 4         | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 78.79%  |
| 0.01-0.5   | 11        | 8.33%   |
| 0.51-1.0   | 5         | 3.79%   |
| 1.01-2.0   | 4         | 3.03%   |
| 7.01-8.0   | 3         | 2.27%   |
| 2.01-3.0   | 2         | 1.52%   |
| 8.01-16.0  | 2         | 1.52%   |
| 3.01-4.0   | 1         | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 18        | 14.4%   |
| LG Display              | 17        | 13.6%   |
| Chimei Innolux          | 14        | 11.2%   |
| Samsung Electronics     | 13        | 10.4%   |
| BOE                     | 7         | 5.6%    |
| Hewlett-Packard         | 6         | 4.8%    |
| Goldstar                | 6         | 4.8%    |
| Dell                    | 6         | 4.8%    |
| Apple                   | 4         | 3.2%    |
| Philips                 | 3         | 2.4%    |
| CPT                     | 3         | 2.4%    |
| Ancor Communications    | 3         | 2.4%    |
| Acer                    | 3         | 2.4%    |
| Sharp                   | 2         | 1.6%    |
| Lenovo                  | 2         | 1.6%    |
| Eizo                    | 2         | 1.6%    |
| BenQ                    | 2         | 1.6%    |
| ViewSonic               | 1         | 0.8%    |
| Unknown                 | 1         | 0.8%    |
| Toshiba                 | 1         | 0.8%    |
| Sony                    | 1         | 0.8%    |
| SNC                     | 1         | 0.8%    |
| Sampo                   | 1         | 0.8%    |
| MSI                     | 1         | 0.8%    |
| LG Philips              | 1         | 0.8%    |
| LG Electronics          | 1         | 0.8%    |
| JVC                     | 1         | 0.8%    |
| JDI                     | 1         | 0.8%    |
| InfoVision              | 1         | 0.8%    |
| HannStar                | 1         | 0.8%    |
| Chi Mei Optoelectronics | 1         | 0.8%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 3         | 2.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.59%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 2         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.59%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 1.59%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 1.59%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 1.59%   |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch         | 1         | 0.79%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1         | 0.79%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch              | 1         | 0.79%   |
| Sony TV SNY9C01 1920x1080                                             | 1         | 0.79%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 1         | 0.79%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 0.79%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch              | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch  | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch  | 1         | 0.79%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1         | 0.79%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch  | 1         | 0.79%   |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch    | 1         | 0.79%   |
| Sampo 800S STC0800 800x600 170x127mm 8.4-inch                         | 1         | 0.79%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 1         | 0.79%   |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch             | 1         | 0.79%   |
| Philips 191EL PHLC050 1366x768 410x230mm 18.5-inch                    | 1         | 0.79%   |
| MSI MAG272CQR MSI3CA6 2560x1440 598x336mm 27.0-inch                   | 1         | 0.79%   |
| LG Philips LCD Monitor LPLEC00 1280x800 331x207mm 15.4-inch           | 1         | 0.79%   |
| LG Electronics LCD Monitor E2241 1920x1080                            | 1         | 0.79%   |
| LG Display LCD Monitor LGD0680 1920x1080 344x194mm 15.5-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD061F 1920x1080 309x174mm 14.0-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x174mm 14.0-inch          | 1         | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 46        | 38.02%  |
| 1920x1080 (FHD)    | 30        | 24.79%  |
| 1280x800 (WXGA)    | 10        | 8.26%   |
| 1600x900 (HD+)     | 9         | 7.44%   |
| 1680x1050 (WSXGA+) | 5         | 4.13%   |
| 1280x1024 (SXGA)   | 5         | 4.13%   |
| 2560x1440 (QHD)    | 3         | 2.48%   |
| 1360x768           | 2         | 1.65%   |
| 800x600            | 1         | 0.83%   |
| 3200x1800 (QHD+)   | 1         | 0.83%   |
| 3000x2000          | 1         | 0.83%   |
| 2560x1600          | 1         | 0.83%   |
| 2560x1080          | 1         | 0.83%   |
| 2160x1440          | 1         | 0.83%   |
| 1920x1200 (WUXGA)  | 1         | 0.83%   |
| 1528x1222          | 1         | 0.83%   |
| 1440x900 (WXGA+)   | 1         | 0.83%   |
| 1280x768           | 1         | 0.83%   |
| 1280x720 (HD)      | 1         | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 29        | 23.39%  |
| 13      | 18        | 14.52%  |
| 14      | 13        | 10.48%  |
| 11      | 8         | 6.45%   |
| 23      | 7         | 5.65%   |
| 17      | 7         | 5.65%   |
| 18      | 6         | 4.84%   |
| Unknown | 5         | 4.03%   |
| 22      | 4         | 3.23%   |
| 20      | 4         | 3.23%   |
| 19      | 4         | 3.23%   |
| 27      | 3         | 2.42%   |
| 24      | 3         | 2.42%   |
| 21      | 3         | 2.42%   |
| 72      | 1         | 0.81%   |
| 49      | 1         | 0.81%   |
| 43      | 1         | 0.81%   |
| 34      | 1         | 0.81%   |
| 28      | 1         | 0.81%   |
| 16      | 1         | 0.81%   |
| 12      | 1         | 0.81%   |
| 10      | 1         | 0.81%   |
| 9       | 1         | 0.81%   |
| 8       | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 40.32%  |
| 201-300     | 22        | 17.74%  |
| 401-500     | 20        | 16.13%  |
| 501-600     | 13        | 10.48%  |
| 351-400     | 7         | 5.65%   |
| Unknown     | 5         | 4.03%   |
| 101-200     | 2         | 1.61%   |
| 701-800     | 1         | 0.81%   |
| 601-700     | 1         | 0.81%   |
| 1501-2000   | 1         | 0.81%   |
| 1001-1500   | 1         | 0.81%   |
| 901-1000    | 1         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 88        | 74.58%  |
| 16/10   | 17        | 14.41%  |
| Unknown | 4         | 3.39%   |
| 5/4     | 3         | 2.54%   |
| 4/3     | 3         | 2.54%   |
| 3/2     | 2         | 1.69%   |
| 21/9    | 1         | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 22.76%  |
| 81-90          | 25        | 20.33%  |
| 201-250        | 15        | 12.2%   |
| 51-60          | 8         | 6.5%    |
| 151-200        | 8         | 6.5%    |
| 141-150        | 8         | 6.5%    |
| 71-80          | 6         | 4.88%   |
| 121-130        | 5         | 4.07%   |
| Unknown        | 5         | 4.07%   |
| 301-350        | 3         | 2.44%   |
| More than 1000 | 2         | 1.63%   |
| 41-50          | 2         | 1.63%   |
| 251-300        | 2         | 1.63%   |
| 501-1000       | 2         | 1.63%   |
| 61-70          | 1         | 0.81%   |
| 1-40           | 1         | 0.81%   |
| 131-140        | 1         | 0.81%   |
| 111-120        | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 46        | 37.7%   |
| 51-100        | 37        | 30.33%  |
| 121-160       | 21        | 17.21%  |
| 161-240       | 7         | 5.74%   |
| Unknown       | 5         | 4.1%    |
| 1-50          | 4         | 3.28%   |
| More than 240 | 2         | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 120       | 90.91%  |
| 2     | 8         | 6.06%   |
| 0     | 3         | 2.27%   |
| 3     | 1         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 65        | 33.85%  |
| Intel                           | 53        | 27.6%   |
| Qualcomm Atheros                | 28        | 14.58%  |
| Broadcom                        | 13        | 6.77%   |
| TP-Link                         | 5         | 2.6%    |
| Samsung Electronics             | 5         | 2.6%    |
| Marvell Technology Group        | 4         | 2.08%   |
| Qualcomm Atheros Communications | 3         | 1.56%   |
| Nvidia                          | 3         | 1.56%   |
| Broadcom Limited                | 3         | 1.56%   |
| MediaTek                        | 2         | 1.04%   |
| Trident Microsystems            | 1         | 0.52%   |
| Sierra Wireless                 | 1         | 0.52%   |
| Ralink Technology               | 1         | 0.52%   |
| Qualcomm                        | 1         | 0.52%   |
| Microsoft                       | 1         | 0.52%   |
| ICS Advent                      | 1         | 0.52%   |
| Belkin Components               | 1         | 0.52%   |
| ASUSTek Computer                | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 42        | 18.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 9         | 4.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 7         | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 5         | 2.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 5         | 2.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 5         | 2.23%   |
| Intel Wireless 7260                                                 | 5         | 2.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 4         | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 4         | 1.79%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 4         | 1.79%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 3         | 1.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 3         | 1.34%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 3         | 1.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 3         | 1.34%   |
| Intel Wireless 7265                                                 | 3         | 1.34%   |
| Intel Ethernet Controller I225-V                                    | 3         | 1.34%   |
| Intel Centrino Wireless-N 2230                                      | 3         | 1.34%   |
| Intel Centrino Advanced-N 6235                                      | 3         | 1.34%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 2         | 0.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2         | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 2         | 0.89%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2         | 0.89%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2         | 0.89%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2         | 0.89%   |
| Nvidia MCP77 Ethernet                                               | 2         | 0.89%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller             | 2         | 0.89%   |
| Intel Wireless 8260                                                 | 2         | 0.89%   |
| Intel Wireless 3160                                                 | 2         | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection               | 2         | 0.89%   |
| Intel NM10/ICH7 Family LAN Controller                               | 2         | 0.89%   |
| Intel Ethernet Connection I218-LM                                   | 2         | 0.89%   |
| Intel Ethernet Connection I217-LM                                   | 2         | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 0.89%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                   | 2         | 0.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                     | 2         | 0.89%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 2         | 0.89%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 2         | 0.89%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2         | 0.89%   |
| Trident Microsystems 4DWave DX                                      | 1         | 0.45%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 37.04%  |
| Qualcomm Atheros                | 25        | 23.15%  |
| Realtek Semiconductor           | 19        | 17.59%  |
| Broadcom                        | 8         | 7.41%   |
| TP-Link                         | 4         | 3.7%    |
| Qualcomm Atheros Communications | 3         | 2.78%   |
| MediaTek                        | 2         | 1.85%   |
| Broadcom Limited                | 2         | 1.85%   |
| Sierra Wireless                 | 1         | 0.93%   |
| Ralink Technology               | 1         | 0.93%   |
| Microsoft                       | 1         | 0.93%   |
| Belkin Components               | 1         | 0.93%   |
| ASUSTek Computer                | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 5         | 4.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 5         | 4.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 5         | 4.63%   |
| Intel Wireless 7260                                                 | 5         | 4.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 4         | 3.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 4         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 3         | 2.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 3         | 2.78%   |
| Intel Wireless 7265                                                 | 3         | 2.78%   |
| Intel Centrino Wireless-N 2230                                      | 3         | 2.78%   |
| Intel Centrino Advanced-N 6235                                      | 3         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 2         | 1.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2         | 1.85%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2         | 1.85%   |
| Intel Wireless 8260                                                 | 2         | 1.85%   |
| Intel Wireless 3160                                                 | 2         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection               | 2         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 1.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 2         | 1.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 2         | 1.85%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2         | 1.85%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1         | 0.93%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1         | 0.93%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1         | 0.93%   |
| TP-Link 802.11ac NIC                                                | 1         | 0.93%   |
| Sierra Wireless EM7305 Modem                                        | 1         | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 1         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 1         | 0.93%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1         | 0.93%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1         | 0.93%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1         | 0.93%   |
| Realtek 802.11n WLAN Adapter                                        | 1         | 0.93%   |
| Realtek 802.11n                                                     | 1         | 0.93%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                   | 1         | 0.93%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter     | 1         | 0.93%   |
| Qualcomm Atheros UB94                                               | 1         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 58        | 50.43%  |
| Intel                    | 25        | 21.74%  |
| Broadcom                 | 8         | 6.96%   |
| Qualcomm Atheros         | 7         | 6.09%   |
| Samsung Electronics      | 5         | 4.35%   |
| Marvell Technology Group | 4         | 3.48%   |
| Nvidia                   | 3         | 2.61%   |
| Trident Microsystems     | 1         | 0.87%   |
| TP-Link                  | 1         | 0.87%   |
| Qualcomm                 | 1         | 0.87%   |
| ICS Advent               | 1         | 0.87%   |
| Broadcom Limited         | 1         | 0.87%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 42        | 36.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 7.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 6.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 3.45%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 2.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 2.59%   |
| Intel Ethernet Controller I225-V                                               | 3         | 2.59%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 1.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.72%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 1.72%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.72%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 2         | 1.72%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.72%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.72%   |
| Trident Microsystems 4DWave DX                                                 | 1         | 0.86%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.86%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.86%   |
| Realtek RTL8150 Fast Ethernet Adapter                                          | 1         | 0.86%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.86%   |
| Qualcomm Redmi Note 8                                                          | 1         | 0.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.86%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.86%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.86%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.86%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1         | 0.86%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.86%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.86%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.86%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.86%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.86%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.86%   |
| Intel 82567LF-2 Gigabit Network Connection                                     | 1         | 0.86%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.86%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 0.86%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 0.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 106       | 51.96%  |
| WiFi     | 98        | 48.04%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 57.36%  |
| Ethernet | 55        | 42.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 65        | 49.24%  |
| 1     | 52        | 39.39%  |
| 0     | 12        | 9.09%   |
| 3     | 2         | 1.52%   |
| 4     | 1         | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 99        | 74.44%  |
| Yes  | 34        | 25.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 42.65%  |
| Realtek Semiconductor           | 9         | 13.24%  |
| Qualcomm Atheros Communications | 7         | 10.29%  |
| Broadcom                        | 4         | 5.88%   |
| IMC Networks                    | 3         | 4.41%   |
| Foxconn / Hon Hai               | 3         | 4.41%   |
| Dell                            | 3         | 4.41%   |
| Apple                           | 3         | 4.41%   |
| MediaTek                        | 2         | 2.94%   |
| Toshiba                         | 1         | 1.47%   |
| Syntek                          | 1         | 1.47%   |
| Logitech                        | 1         | 1.47%   |
| Cambridge Silicon Radio         | 1         | 1.47%   |
| Alps Electric                   | 1         | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 14        | 20.59%  |
| Realtek Bluetooth Radio                                                             | 5         | 7.35%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 7.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 7.35%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 4.41%   |
| Intel AX201 Bluetooth                                                               | 3         | 4.41%   |
| Apple Bluetooth Host Controller                                                     | 3         | 4.41%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 2.94%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 2.94%   |
| MediaTek Wireless_Device                                                            | 2         | 2.94%   |
| IMC Networks Bluetooth Device                                                       | 2         | 2.94%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 2.94%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 1.47%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 1.47%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.47%   |
| Logitech BT Mini-Receiver (HCI mode)                                                | 1         | 1.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.47%   |
| Intel AX200 Bluetooth                                                               | 1         | 1.47%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 1.47%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.47%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 1.47%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 1.47%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.47%   |
| Broadcom HP Portable Valentine                                                      | 1         | 1.47%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 1.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.47%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.47%   |
| Alps Electric Bluetooth Adapter                                                     | 1         | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 95        | 62.91%  |
| AMD                                          | 27        | 17.88%  |
| Nvidia                                       | 20        | 13.25%  |
| C-Media Electronics                          | 2         | 1.32%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.66%   |
| Razer USA                                    | 1         | 0.66%   |
| Logitech                                     | 1         | 0.66%   |
| JMTek                                        | 1         | 0.66%   |
| Ensoniq                                      | 1         | 0.66%   |
| Creative Labs                                | 1         | 0.66%   |
| ASUSTek Computer                             | 1         | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 7.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 6.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 5.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 4.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 3.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 3.37%   |
| AMD FCH Azalia Controller                                                                         | 6         | 3.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.81%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.81%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.25%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 2.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 2.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.25%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 4         | 2.25%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.69%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.69%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 1.12%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 1.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.12%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.12%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.12%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 1.12%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1.12%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.12%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.12%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 1.12%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.12%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 0.56%   |
| Razer USA Razer Kraken X USB                                                                      | 1         | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 19.79%  |
| Unknown             | 16        | 16.67%  |
| SK hynix            | 15        | 15.63%  |
| Micron Technology   | 15        | 15.63%  |
| Kingston            | 7         | 7.29%   |
| Elpida              | 4         | 4.17%   |
| Corsair             | 4         | 4.17%   |
| Nanya Technology    | 3         | 3.13%   |
| Unknown             | 3         | 3.13%   |
| Smart               | 2         | 2.08%   |
| G.Skill             | 2         | 2.08%   |
| Unknown (ABCD)      | 1         | 1.04%   |
| Ramaxel Technology  | 1         | 1.04%   |
| Novatech            | 1         | 1.04%   |
| HMD                 | 1         | 1.04%   |
| AMD                 | 1         | 1.04%   |
| A-DATA Technology   | 1         | 1.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 2.86%   |
| Unknown                                                          | 3         | 2.86%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 1.9%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1.9%    |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 2         | 1.9%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.9%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.9%    |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 1.9%    |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.95%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.95%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.95%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.95%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.95%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.95%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.95%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.95%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 0.95%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s         | 1         | 0.95%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.95%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.95%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.95%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.95%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 0.95%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 800MT/s          | 1         | 0.95%   |
| SK hynix RAM HT5SMRAP 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.95%   |
| SK hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 1         | 0.95%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s             | 1         | 0.95%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.95%   |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s              | 1         | 0.95%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                     | 1         | 0.95%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.95%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 42        | 50%     |
| DDR4    | 22        | 26.19%  |
| DDR2    | 8         | 9.52%   |
| LPDDR4  | 5         | 5.95%   |
| SDRAM   | 3         | 3.57%   |
| LPDDR3  | 3         | 3.57%   |
| Unknown | 1         | 1.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 58        | 69.05%  |
| DIMM         | 17        | 20.24%  |
| Row Of Chips | 6         | 7.14%   |
| Unknown      | 3         | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 33        | 33.67%  |
| 2048  | 29        | 29.59%  |
| 8192  | 22        | 22.45%  |
| 16384 | 6         | 6.12%   |
| 1024  | 5         | 5.1%    |
| 32768 | 2         | 2.04%   |
| 512   | 1         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 27        | 30.68%  |
| 3200    | 10        | 11.36%  |
| 1333    | 9         | 10.23%  |
| 667     | 5         | 5.68%   |
| 2667    | 4         | 4.55%   |
| 1066    | 4         | 4.55%   |
| 2400    | 3         | 3.41%   |
| 1334    | 3         | 3.41%   |
| Unknown | 3         | 3.41%   |
| 4267    | 2         | 2.27%   |
| 3266    | 2         | 2.27%   |
| 2133    | 2         | 2.27%   |
| 2048    | 2         | 2.27%   |
| 1867    | 2         | 2.27%   |
| 1866    | 2         | 2.27%   |
| 1067    | 2         | 2.27%   |
| 4199    | 1         | 1.14%   |
| 3600    | 1         | 1.14%   |
| 3400    | 1         | 1.14%   |
| 2800    | 1         | 1.14%   |
| 975     | 1         | 1.14%   |
| 800     | 1         | 1.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 300 | 1         | 50%     |
| Brother DCP-7055W       | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21        | 27.27%  |
| Microdia                               | 11        | 14.29%  |
| Sunplus Innovation Technology          | 5         | 6.49%   |
| Realtek Semiconductor                  | 5         | 6.49%   |
| Syntek                                 | 4         | 5.19%   |
| IMC Networks                           | 3         | 3.9%    |
| Apple                                  | 3         | 3.9%    |
| Alcor Micro                            | 3         | 3.9%    |
| Silicon Motion                         | 2         | 2.6%    |
| Quanta                                 | 2         | 2.6%    |
| Logitech                               | 2         | 2.6%    |
| Lenovo                                 | 2         | 2.6%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.6%    |
| ALi                                    | 2         | 2.6%    |
| Acer                                   | 2         | 2.6%    |
| WaveRider Communications               | 1         | 1.3%    |
| Suyin                                  | 1         | 1.3%    |
| Ricoh                                  | 1         | 1.3%    |
| Pixart Imaging                         | 1         | 1.3%    |
| Microsoft                              | 1         | 1.3%    |
| Lite-On Technology                     | 1         | 1.3%    |
| Cubeternet                             | 1         | 1.3%    |
| AVerMedia Technologies                 | 1         | 1.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 6.41%   |
| Alcor Micro USB 2.0 Camera                          | 3         | 3.85%   |
| Sunplus HD WebCam                                   | 2         | 2.56%   |
| Microdia Lenovo EasyCamera                          | 2         | 2.56%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.56%   |
| Microdia Integrated Webcam                          | 2         | 2.56%   |
| Microdia HP Webcam-50                               | 2         | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 2.56%   |
| Chicony HD WebCam                                   | 2         | 2.56%   |
| Chicony FJ Camera                                   | 2         | 2.56%   |
| Chicony EasyCamera                                  | 2         | 2.56%   |
| Apple FaceTime HD Camera                            | 2         | 2.56%   |
| ALi WebCam                                          | 2         | 2.56%   |
| WaveRider USB 2.0 Camera                            | 1         | 1.28%   |
| Syntek USB2.0 Camera                                | 1         | 1.28%   |
| Syntek USB Camera Device                            | 1         | 1.28%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.28%   |
| Syntek HD WebCam                                    | 1         | 1.28%   |
| Suyin 1.3M HD WebCam                                | 1         | 1.28%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 1.28%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.28%   |
| Sunplus Asus Webcam                                 | 1         | 1.28%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 1.28%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 1.28%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 1.28%   |
| Realtek USB Camera                                  | 1         | 1.28%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.28%   |
| Realtek Lenovo easy camera                          | 1         | 1.28%   |
| Realtek Integrated_Webcam_HD                        | 1         | 1.28%   |
| Realtek Integrated Webcam HD                        | 1         | 1.28%   |
| Quanta HP Webcam                                    | 1         | 1.28%   |
| Quanta Chromebook HD Camera                         | 1         | 1.28%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                | 1         | 1.28%   |
| Microsoft LifeCam VX-800                            | 1         | 1.28%   |
| Microdia Webcam Vitade AF                           | 1         | 1.28%   |
| Microdia Webcam                                     | 1         | 1.28%   |
| Microdia 1.3 MPixel Integrated Webcam               | 1         | 1.28%   |
| Logitech Webcam C270                                | 1         | 1.28%   |
| Logitech HD Webcam C615                             | 1         | 1.28%   |
| Lite-On HP Webcam                                   | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 33.33%  |
| Upek                  | 3         | 20%     |
| Synaptics             | 2         | 13.33%  |
| STMicroelectronics    | 2         | 13.33%  |
| AuthenTec             | 2         | 13.33%  |
| Elan Microelectronics | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 20%     |
| STMicroelectronics Fingerprint Reader                  | 2         | 13.33%  |
| Unknown                                                | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 6.67%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 6.67%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 6.67%   |
| Elan ELAN:Fingerprint                                  | 1         | 6.67%   |
| AuthenTec Fingerprint Sensor                           | 1         | 6.67%   |
| AuthenTec AES2810                                      | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 60%     |
| O2 Micro | 1         | 20%     |
| Cherry   | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 2         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 20%     |
| Cherry SmartCard Reader Keyboard KC 1000 SC    | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 105       | 78.95%  |
| 1     | 27        | 20.3%   |
| 2     | 1         | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 15        | 51.72%  |
| Graphics card      | 4         | 13.79%  |
| Chipcard           | 4         | 13.79%  |
| Net/wireless       | 3         | 10.34%  |
| Storage            | 1         | 3.45%   |
| Camera             | 1         | 3.45%   |
| Bluetooth          | 1         | 3.45%   |

