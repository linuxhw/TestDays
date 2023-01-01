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

Total: 195

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Google        | Candy                       | Notebook    | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | Notebook    | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| ASUSTek       | K72F                        | Notebook    | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [a9c1fc9fbd](https://linux-hardware.org/?probe=a9c1fc9fbd) | Dec 28, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [fd1cdfc132](https://linux-hardware.org/?probe=fd1cdfc132) | Dec 28, 2022 |
| Acer          | Aspire SW3-013              | Notebook    | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| ZOTAC         | NM10                        | Desktop     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| HP            | 2000                        | Notebook    | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | Notebook    | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
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
| 5.15.0-43-generic           | 24        | 14.81%  |
| 5.15.0-25-generic           | 12        | 7.41%   |
| 5.15.0-47-generic           | 11        | 6.79%   |
| 5.15.0-30-generic           | 10        | 6.17%   |
| 5.15.0-56-generic           | 9         | 5.56%   |
| 5.15.0-46-generic           | 9         | 5.56%   |
| 5.15.0-41-generic           | 9         | 5.56%   |
| 5.15.0-27-generic           | 9         | 5.56%   |
| 5.15.0-52-generic           | 8         | 4.94%   |
| 5.15.0-53-generic           | 7         | 4.32%   |
| 5.15.0-50-generic           | 6         | 3.7%    |
| 5.15.0-48-generic           | 6         | 3.7%    |
| 5.15.0-40-generic           | 6         | 3.7%    |
| 5.15.0-39-generic           | 4         | 2.47%   |
| 5.15.0-35-generic           | 4         | 2.47%   |
| 5.15.0-33-generic           | 4         | 2.47%   |
| 5.15.0-57-generic           | 3         | 1.85%   |
| 5.15.0-37-generic           | 2         | 1.23%   |
| 5.15.0-23-generic           | 2         | 1.23%   |
| 5.15.0-18-generic           | 2         | 1.23%   |
| 6.1.0-custom                | 1         | 0.62%   |
| 6.0.8-060008-generic        | 1         | 0.62%   |
| 6.0.12-x64v2-xanmod1        | 1         | 0.62%   |
| 6.0.10-rockchip64           | 1         | 0.62%   |
| 5.19.8-xanmod1              | 1         | 0.62%   |
| 5.19.11-ux360cak            | 1         | 0.62%   |
| 5.19.0-16.2-liquorix-amd64  | 1         | 0.62%   |
| 5.19.0-051900-generic       | 1         | 0.62%   |
| 5.18.0-051800-generic       | 1         | 0.62%   |
| 5.15.0-54-generic           | 1         | 0.62%   |
| 5.15.0-41-lowlatency        | 1         | 0.62%   |
| 5.15.0-362206031516-generic | 1         | 0.62%   |
| 5.15.0-28-generic           | 1         | 0.62%   |
| 5.15.0-1017-raspi           | 1         | 0.62%   |
| 5.14.0-1040-oem             | 1         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 144       | 93.51%  |
| 5.19.0  | 2         | 1.3%    |
| 6.1.0   | 1         | 0.65%   |
| 6.0.8   | 1         | 0.65%   |
| 6.0.12  | 1         | 0.65%   |
| 6.0.10  | 1         | 0.65%   |
| 5.19.8  | 1         | 0.65%   |
| 5.19.11 | 1         | 0.65%   |
| 5.18.0  | 1         | 0.65%   |
| 5.14.0  | 1         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 144       | 93.51%  |
| 5.19    | 4         | 2.6%    |
| 6.0     | 3         | 1.95%   |
| 6.1     | 1         | 0.65%   |
| 5.18    | 1         | 0.65%   |
| 5.14    | 1         | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 148       | 98.67%  |
| aarch64 | 2         | 1.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 145       | 96.67%  |
| LXDE       | 3         | 2%      |
| X-Cinnamon | 2         | 1.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 144       | 94.74%  |
| Tty         | 6         | 3.95%   |
| Wayland     | 1         | 0.66%   |
| Unspecified | 1         | 0.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 130       | 86.09%  |
| Unknown | 9         | 5.96%   |
| LightDM | 7         | 4.64%   |
| GDM3    | 2         | 1.32%   |
| XDM     | 1         | 0.66%   |
| SLiM    | 1         | 0.66%   |
| LXDM    | 1         | 0.66%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 42        | 27.81%  |
| fr_FR | 13        | 8.61%   |
| it_IT | 12        | 7.95%   |
| en_GB | 10        | 6.62%   |
| de_DE | 10        | 6.62%   |
| C     | 8         | 5.3%    |
| pl_PL | 7         | 4.64%   |
| pt_BR | 6         | 3.97%   |
| es_CR | 4         | 2.65%   |
| es_AR | 4         | 2.65%   |
| en_AG | 4         | 2.65%   |
| nl_BE | 3         | 1.99%   |
| es_MX | 3         | 1.99%   |
| es_ES | 3         | 1.99%   |
| en_AU | 3         | 1.99%   |
| ru_RU | 2         | 1.32%   |
| en_CA | 2         | 1.32%   |
| el_GR | 2         | 1.32%   |
| tr_TR | 1         | 0.66%   |
| sv_SE | 1         | 0.66%   |
| ru_UA | 1         | 0.66%   |
| ja_JP | 1         | 0.66%   |
| fr_CA | 1         | 0.66%   |
| fi_FI | 1         | 0.66%   |
| es_CO | 1         | 0.66%   |
| es_CL | 1         | 0.66%   |
| en_ZA | 1         | 0.66%   |
| en_PH | 1         | 0.66%   |
| en_DE | 1         | 0.66%   |
| cv_RU | 1         | 0.66%   |
| aa_DJ | 1         | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 96        | 63.58%  |
| EFI  | 55        | 36.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 138       | 91.39%  |
| Overlay | 9         | 5.96%   |
| Btrfs   | 3         | 1.99%   |
| Ext2    | 1         | 0.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 70        | 45.75%  |
| Unknown | 46        | 30.07%  |
| MBR     | 37        | 24.18%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 131       | 86.75%  |
| Yes       | 20        | 13.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 110       | 72.85%  |
| Yes       | 41        | 27.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 21        | 14%     |
| Dell                    | 21        | 14%     |
| Hewlett-Packard         | 17        | 11.33%  |
| ASUSTek Computer        | 16        | 10.67%  |
| Acer                    | 9         | 6%      |
| MSI                     | 6         | 4%      |
| Google                  | 6         | 4%      |
| Apple                   | 6         | 4%      |
| Unknown                 | 6         | 4%      |
| Fujitsu                 | 5         | 3.33%   |
| ASRock                  | 4         | 2.67%   |
| AMI                     | 4         | 2.67%   |
| Sony                    | 3         | 2%      |
| Gigabyte Technology     | 3         | 2%      |
| Toshiba                 | 2         | 1.33%   |
| Mediacom                | 2         | 1.33%   |
| Intel                   | 2         | 1.33%   |
| Gateway                 | 2         | 1.33%   |
| ZOTAC                   | 1         | 0.67%   |
| SGIN                    | 1         | 0.67%   |
| Samsung Electronics     | 1         | 0.67%   |
| Rockchip                | 1         | 0.67%   |
| Raspberry Pi Foundation | 1         | 0.67%   |
| Pretech                 | 1         | 0.67%   |
| Prestigio               | 1         | 0.67%   |
| Positivo                | 1         | 0.67%   |
| Pegatron                | 1         | 0.67%   |
| Packard Bell            | 1         | 0.67%   |
| OEM                     | 1         | 0.67%   |
| Kiano                   | 1         | 0.67%   |
| IFSA                    | 1         | 0.67%   |
| GPU Company             | 1         | 0.67%   |
| Chuwi                   | 1         | 0.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 4.67%   |
| Apple MacBookPro8,1                        | 3         | 2%      |
| Mediacom WinPad 11,6 FullHD- WPU11         | 2         | 1.33%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 1.33%   |
| HP Pavilion g6                             | 2         | 1.33%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 1.33%   |
| Dell Dimension 9100                        | 2         | 1.33%   |
| ZOTAC NM10                                 | 1         | 0.67%   |
| Toshiba Satellite Pro S500                 | 1         | 0.67%   |
| Toshiba Satellite L40                      | 1         | 0.67%   |
| Sony VPCEB15FM                             | 1         | 0.67%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.67%   |
| Sony SVE14A2V1EW                           | 1         | 0.67%   |
| SGIN laptop                                | 1         | 0.67%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.67%   |
| Rockchip RK3318 BOX                        | 1         | 0.67%   |
| RPi Raspberry Pi                           | 1         | 0.67%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.67%   |
| Prestigio PSB141C01BFH                     | 1         | 0.67%   |
| Positivo i500pro                           | 1         | 0.67%   |
| Pegatron AY748AA-ABA p6320y                | 1         | 0.67%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.67%   |
| MSI MS-7D09                                | 1         | 0.67%   |
| MSI MS-7C96                                | 1         | 0.67%   |
| MSI MS-7C37                                | 1         | 0.67%   |
| MSI MS-7B86                                | 1         | 0.67%   |
| MSI MS-7978                                | 1         | 0.67%   |
| MSI MS-7641                                | 1         | 0.67%   |
| Lenovo Z70-80 80FG                         | 1         | 0.67%   |
| Lenovo Yoga C940-14IIL 81Q9                | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0WE02   | 1         | 0.67%   |
| Lenovo ThinkPad T430 2342A19               | 1         | 0.67%   |
| Lenovo ThinkPad T410 2537CS0               | 1         | 0.67%   |
| Lenovo ThinkPad SL510 2847CXG              | 1         | 0.67%   |
| Lenovo ThinkPad E550 20DF00CUFR            | 1         | 0.67%   |
| Lenovo ThinkCentre M83 10ANCTO1WW          | 1         | 0.67%   |
| Lenovo ThinkCentre M600 10KGS09S00         | 1         | 0.67%   |
| Lenovo MIIX 310-10ICR 80SG                 | 1         | 0.67%   |
| Lenovo IdeaPad S145-15IGM 81MX             | 1         | 0.67%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK      | 1         | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Unknown                | 7         | 4.67%   |
| Lenovo IdeaPad         | 6         | 4%      |
| Dell Latitude          | 6         | 4%      |
| Lenovo ThinkPad        | 5         | 3.33%   |
| Acer Aspire            | 5         | 3.33%   |
| HP Pavilion            | 4         | 2.67%   |
| Fujitsu LIFEBOOK       | 4         | 2.67%   |
| HP ProBook             | 3         | 2%      |
| Dell OptiPlex          | 3         | 2%      |
| Apple MacBookPro8      | 3         | 2%      |
| Toshiba Satellite      | 2         | 1.33%   |
| Mediacom WinPad        | 2         | 1.33%   |
| Lenovo ThinkCentre     | 2         | 1.33%   |
| Dell XPS               | 2         | 1.33%   |
| Dell Vostro            | 2         | 1.33%   |
| Dell Studio            | 2         | 1.33%   |
| Dell Precision         | 2         | 1.33%   |
| Dell Dimension         | 2         | 1.33%   |
| ASUS PRIME             | 2         | 1.33%   |
| ZOTAC NM10             | 1         | 0.67%   |
| Sony VPCEB15FM         | 1         | 0.67%   |
| Sony VGN-SZ71WN        | 1         | 0.67%   |
| Sony SVE14A2V1EW       | 1         | 0.67%   |
| SGIN laptop            | 1         | 0.67%   |
| Samsung 300V3A         | 1         | 0.67%   |
| Rockchip RK3318        | 1         | 0.67%   |
| RPi Raspberry          | 1         | 0.67%   |
| Pretech EVE            | 1         | 0.67%   |
| Prestigio PSB141C01BFH | 1         | 0.67%   |
| Positivo i500pro       | 1         | 0.67%   |
| Pegatron AY748AA-ABA   | 1         | 0.67%   |
| Packard Bell EasyNote  | 1         | 0.67%   |
| MSI MS-7D09            | 1         | 0.67%   |
| MSI MS-7C96            | 1         | 0.67%   |
| MSI MS-7C37            | 1         | 0.67%   |
| MSI MS-7B86            | 1         | 0.67%   |
| MSI MS-7978            | 1         | 0.67%   |
| MSI MS-7641            | 1         | 0.67%   |
| Lenovo Z70-80          | 1         | 0.67%   |
| Lenovo Yoga            | 1         | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 17        | 11.33%  |
| 2020    | 12        | 8%      |
| 2019    | 11        | 7.33%   |
| 2014    | 11        | 7.33%   |
| 2013    | 11        | 7.33%   |
| 2015    | 10        | 6.67%   |
| 2008    | 10        | 6.67%   |
| 2021    | 9         | 6%      |
| 2016    | 9         | 6%      |
| 2012    | 9         | 6%      |
| 2010    | 9         | 6%      |
| 2017    | 8         | 5.33%   |
| 2009    | 8         | 5.33%   |
| 2022    | 5         | 3.33%   |
| 2007    | 5         | 3.33%   |
| 2018    | 2         | 1.33%   |
| 2006    | 2         | 1.33%   |
| Unknown | 2         | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 92        | 61.33%  |
| Desktop        | 47        | 31.33%  |
| Convertible    | 4         | 2.67%   |
| System on chip | 2         | 1.33%   |
| Tablet         | 2         | 1.33%   |
| Mini pc        | 2         | 1.33%   |
| All in one     | 1         | 0.67%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 145       | 96.67%  |
| Enabled  | 5         | 3.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 143       | 95.33%  |
| Yes  | 7         | 4.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 52        | 34.44%  |
| 4.01-8.0    | 36        | 23.84%  |
| 8.01-16.0   | 18        | 11.92%  |
| 1.01-2.0    | 16        | 10.6%   |
| 16.01-24.0  | 15        | 9.93%   |
| 32.01-64.0  | 6         | 3.97%   |
| 2.01-3.0    | 5         | 3.31%   |
| 0.51-1.0    | 2         | 1.32%   |
| 64.01-256.0 | 1         | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 75        | 48.7%   |
| 0.51-1.0 | 38        | 24.68%  |
| 2.01-3.0 | 29        | 18.83%  |
| 4.01-8.0 | 7         | 4.55%   |
| 3.01-4.0 | 4         | 2.6%    |
| 0.01-0.5 | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 108       | 71.52%  |
| 2      | 33        | 21.85%  |
| 3      | 3         | 1.99%   |
| 0      | 3         | 1.99%   |
| 5      | 2         | 1.32%   |
| 7      | 1         | 0.66%   |
| 6      | 1         | 0.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 90        | 60%     |
| Yes       | 60        | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 78.67%  |
| No        | 32        | 21.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 74.67%  |
| No        | 38        | 25.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 51.66%  |
| No        | 73        | 48.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 26        | 17.33%  |
| Germany      | 15        | 10%     |
| Italy        | 14        | 9.33%   |
| France       | 13        | 8.67%   |
| Poland       | 9         | 6%      |
| UK           | 7         | 4.67%   |
| Brazil       | 7         | 4.67%   |
| Belgium      | 5         | 3.33%   |
| Spain        | 4         | 2.67%   |
| Costa Rica   | 4         | 2.67%   |
| Canada       | 4         | 2.67%   |
| Argentina    | 4         | 2.67%   |
| Russia       | 3         | 2%      |
| Mexico       | 3         | 2%      |
| Australia    | 3         | 2%      |
| Vietnam      | 2         | 1.33%   |
| Ukraine      | 2         | 1.33%   |
| Turkey       | 2         | 1.33%   |
| Sweden       | 2         | 1.33%   |
| Indonesia    | 2         | 1.33%   |
| Hungary      | 2         | 1.33%   |
| Greece       | 2         | 1.33%   |
| South Africa | 1         | 0.67%   |
| Saudi Arabia | 1         | 0.67%   |
| Romania      | 1         | 0.67%   |
| Portugal     | 1         | 0.67%   |
| Philippines  | 1         | 0.67%   |
| Netherlands  | 1         | 0.67%   |
| Latvia       | 1         | 0.67%   |
| Kenya        | 1         | 0.67%   |
| Japan        | 1         | 0.67%   |
| Ireland      | 1         | 0.67%   |
| Finland      | 1         | 0.67%   |
| Colombia     | 1         | 0.67%   |
| Chile        | 1         | 0.67%   |
| Bulgaria     | 1         | 0.67%   |
| Belarus      | 1         | 0.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Paris                     | 5         | 3.25%   |
| Heredia                   | 4         | 2.6%    |
| Melbourne                 | 3         | 1.95%   |
| Sarospatak                | 2         | 1.3%    |
| Porto Alegre              | 2         | 1.3%    |
| Novo Gama                 | 2         | 1.3%    |
| Largo                     | 2         | 1.3%    |
| Kyiv                      | 2         | 1.3%    |
| Ghent                     | 2         | 1.3%    |
| Zizur Mayor               | 1         | 0.65%   |
| Zawiercie                 | 1         | 0.65%   |
| Yoshkar-Ola               | 1         | 0.65%   |
| Yorkville                 | 1         | 0.65%   |
| Wolfhagen                 | 1         | 0.65%   |
| Wetteren                  | 1         | 0.65%   |
| Washington                | 1         | 0.65%   |
| Warsaw                    | 1         | 0.65%   |
| Volzhskiy                 | 1         | 0.65%   |
| Verona                    | 1         | 0.65%   |
| Varna                     | 1         | 0.65%   |
| Valentigney               | 1         | 0.65%   |
| Valencia                  | 1         | 0.65%   |
| Tychy                     | 1         | 0.65%   |
| Thornton Heath            | 1         | 0.65%   |
| Thessaloniki              | 1         | 0.65%   |
| Texas City                | 1         | 0.65%   |
| Taylorsville              | 1         | 0.65%   |
| Tandil                    | 1         | 0.65%   |
| Surabaya                  | 1         | 0.65%   |
| Stuttgart                 | 1         | 0.65%   |
| Strzyzow                  | 1         | 0.65%   |
| Stockholm                 | 1         | 0.65%   |
| Southampton               | 1         | 0.65%   |
| South Burlington          | 1         | 0.65%   |
| Sonico                    | 1         | 0.65%   |
| Sao Paulo                 | 1         | 0.65%   |
| Santiago                  | 1         | 0.65%   |
| Saint-Raymond-de-Portneuf | 1         | 0.65%   |
| Roswell                   | 1         | 0.65%   |
| Rossano Veneto            | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 32     | 14.75%  |
| Unknown             | 21        | 29     | 11.48%  |
| WDC                 | 19        | 25     | 10.38%  |
| Samsung Electronics | 19        | 25     | 10.38%  |
| Toshiba             | 12        | 13     | 6.56%   |
| Hitachi             | 11        | 13     | 6.01%   |
| SanDisk             | 9         | 9      | 4.92%   |
| Kingston            | 8         | 9      | 4.37%   |
| Crucial             | 5         | 5      | 2.73%   |
| Micron Technology   | 4         | 4      | 2.19%   |
| Intel               | 3         | 4      | 1.64%   |
| GOODRAM             | 3         | 3      | 1.64%   |
| Apacer              | 3         | 3      | 1.64%   |
| SPCC                | 2         | 3      | 1.09%   |
| HGST                | 2         | 2      | 1.09%   |
| A-DATA Technology   | 2         | 2      | 1.09%   |
| WD MediaMax         | 1         | 1      | 0.55%   |
| W800S               | 1         | 1      | 0.55%   |
| UMIS                | 1         | 1      | 0.55%   |
| Transcend           | 1         | 1      | 0.55%   |
| TO Exter            | 1         | 1      | 0.55%   |
| Teclast             | 1         | 1      | 0.55%   |
| Team                | 1         | 1      | 0.55%   |
| T-FORCE             | 1         | 1      | 0.55%   |
| SK hynix            | 1         | 1      | 0.55%   |
| RSH-319             | 1         | 1      | 0.55%   |
| Rogueware           | 1         | 1      | 0.55%   |
| PNY                 | 1         | 1      | 0.55%   |
| Patriot             | 1         | 1      | 0.55%   |
| NGFF                | 1         | 1      | 0.55%   |
| Maxtor              | 1         | 1      | 0.55%   |
| LITEONIT            | 1         | 1      | 0.55%   |
| Lexar               | 1         | 1      | 0.55%   |
| Leqixiang           | 1         | 1      | 0.55%   |
| Lenovo              | 1         | 1      | 0.55%   |
| Kston               | 1         | 3      | 0.55%   |
| KIOXIA              | 1         | 1      | 0.55%   |
| KINGPOWER           | 1         | 1      | 0.55%   |
| Intenso             | 1         | 1      | 0.55%   |
| HUSKY               | 1         | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seagate ST9500325AS 500GB        | 4         | 1.98%   |
| Seagate ST500DM002-1BD142 500GB  | 4         | 1.98%   |
| Unknown MMC Card  64GB           | 3         | 1.49%   |
| SanDisk DF4032  32GB             | 3         | 1.49%   |
| Unknown SD/MMC/MS PRO 64GB       | 2         | 0.99%   |
| Unknown SC64G  64GB              | 2         | 0.99%   |
| Unknown NCard  32GB              | 2         | 0.99%   |
| Unknown MMC64G  64GB             | 2         | 0.99%   |
| Unknown MMC Card  32GB           | 2         | 0.99%   |
| Unknown DA4032  32GB             | 2         | 0.99%   |
| Toshiba MQ01ABF050 500GB         | 2         | 0.99%   |
| Toshiba DT01ACA100 1TB           | 2         | 0.99%   |
| SPCC Solid State Disk 120GB      | 2         | 0.99%   |
| Seagate ST3120213AS 120GB        | 2         | 0.99%   |
| Samsung HD502HJ 500GB            | 2         | 0.99%   |
| Kingston SA400S37240G 240GB SSD  | 2         | 0.99%   |
| Crucial CT240BX500SSD1 240GB     | 2         | 0.99%   |
| Apacer 16GB SATA Flash Drive SSD | 2         | 0.99%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 0.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1         | 0.5%    |
| WDC WDS500G2B0A 500GB SSD        | 1         | 0.5%    |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 0.5%    |
| WDC WDS100T1X0E-00AFY0 1TB       | 1         | 0.5%    |
| WDC WD800BB-00CAA1 80GB          | 1         | 0.5%    |
| WDC WD5000LPCX-60VHAT0 500GB     | 1         | 0.5%    |
| WDC WD5000LPCX-24C6HT0 500GB     | 1         | 0.5%    |
| WDC WD5000AAKX-75U6AA0 500GB     | 1         | 0.5%    |
| WDC WD3200BPVT-22JJ5T0 320GB     | 1         | 0.5%    |
| WDC WD3200BPVT-00HXZT3 320GB     | 1         | 0.5%    |
| WDC WD3200BEKT-75PVMT1 320GB     | 1         | 0.5%    |
| WDC WD30EZRZ-00GXCB0 3TB         | 1         | 0.5%    |
| WDC WD2500AAJS-07M0A0 250GB      | 1         | 0.5%    |
| WDC WD20EZRX-00D8PB0 2TB         | 1         | 0.5%    |
| WDC WD20EZBX-00AYRA0 2TB         | 1         | 0.5%    |
| WDC WD10SPZX-24Z10T0 1TB         | 1         | 0.5%    |
| WDC WD10SPZX-24Z10 1TB           | 1         | 0.5%    |
| WDC WD10SPZX-21Z10T0 1TB         | 1         | 0.5%    |
| WDC WD10JPVX-75JC3T0 1TB         | 1         | 0.5%    |
| WDC WD10EZRZ-00Z5HB0 1TB         | 1         | 0.5%    |
| WDC WD10EURX-63C57Y0 1TB         | 1         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 31     | 34.18%  |
| WDC                 | 15        | 17     | 18.99%  |
| Hitachi             | 11        | 13     | 13.92%  |
| Toshiba             | 10        | 11     | 12.66%  |
| Samsung Electronics | 6         | 9      | 7.59%   |
| Unknown             | 2         | 2      | 2.53%   |
| HGST                | 2         | 2      | 2.53%   |
| WD MediaMax         | 1         | 1      | 1.27%   |
| RSH-319             | 1         | 1      | 1.27%   |
| Maxtor              | 1         | 1      | 1.27%   |
| Fujitsu             | 1         | 1      | 1.27%   |
| External            | 1         | 1      | 1.27%   |
| Apricorn            | 1         | 1      | 1.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 13     | 19.05%  |
| Kingston            | 6         | 7      | 9.52%   |
| SanDisk             | 4         | 4      | 6.35%   |
| Crucial             | 4         | 4      | 6.35%   |
| WDC                 | 3         | 4      | 4.76%   |
| GOODRAM             | 3         | 3      | 4.76%   |
| Apacer              | 3         | 3      | 4.76%   |
| Toshiba             | 2         | 2      | 3.17%   |
| SPCC                | 2         | 3      | 3.17%   |
| Micron Technology   | 2         | 2      | 3.17%   |
| Intel               | 2         | 2      | 3.17%   |
| A-DATA Technology   | 2         | 2      | 3.17%   |
| W800S               | 1         | 1      | 1.59%   |
| Transcend           | 1         | 1      | 1.59%   |
| TO Exter            | 1         | 1      | 1.59%   |
| Teclast             | 1         | 1      | 1.59%   |
| Team                | 1         | 1      | 1.59%   |
| Rogueware           | 1         | 1      | 1.59%   |
| PNY                 | 1         | 1      | 1.59%   |
| Patriot             | 1         | 1      | 1.59%   |
| NGFF                | 1         | 1      | 1.59%   |
| LITEONIT            | 1         | 1      | 1.59%   |
| Lexar               | 1         | 1      | 1.59%   |
| Leqixiang           | 1         | 1      | 1.59%   |
| Lenovo              | 1         | 1      | 1.59%   |
| Kston               | 1         | 3      | 1.59%   |
| KINGPOWER           | 1         | 1      | 1.59%   |
| HUSKY               | 1         | 1      | 1.59%   |
| Gigabyte Technology | 1         | 1      | 1.59%   |
| 2.5"                | 1         | 2      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 66        | 91     | 38.37%  |
| SSD     | 61        | 70     | 35.47%  |
| MMC     | 25        | 33     | 14.53%  |
| NVMe    | 17        | 20     | 9.88%   |
| Unknown | 3         | 5      | 1.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 111       | 154    | 68.52%  |
| MMC  | 25        | 33     | 15.43%  |
| NVMe | 17        | 20     | 10.49%  |
| SAS  | 9         | 12     | 5.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 91        | 116    | 70.54%  |
| 0.51-1.0   | 25        | 29     | 19.38%  |
| 1.01-2.0   | 6         | 7      | 4.65%   |
| 3.01-4.0   | 3         | 3      | 2.33%   |
| 2.01-3.0   | 3         | 4      | 2.33%   |
| 4.01-10.0  | 1         | 2      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 44        | 28.95%  |
| 251-500        | 35        | 23.03%  |
| 51-100         | 16        | 10.53%  |
| 21-50          | 15        | 9.87%   |
| 1-20           | 15        | 9.87%   |
| 501-1000       | 13        | 8.55%   |
| 2001-3000      | 5         | 3.29%   |
| More than 3000 | 4         | 2.63%   |
| 1001-2000      | 4         | 2.63%   |
| Unknown        | 1         | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 84        | 54.55%  |
| 21-50          | 28        | 18.18%  |
| 101-250        | 13        | 8.44%   |
| 51-100         | 11        | 7.14%   |
| 251-500        | 6         | 3.9%    |
| 501-1000       | 4         | 2.6%    |
| More than 3000 | 3         | 1.95%   |
| 1001-2000      | 3         | 1.95%   |
| 2001-3000      | 1         | 0.65%   |
| Unknown        | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                 | 2         | 2      | 9.09%   |
| Apacer 16GB SATA Flash Drive SSD          | 2         | 2      | 9.09%   |
| WDC WD10SPZX-24Z10T0 1TB                  | 1         | 1      | 4.55%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1      | 4.55%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD050 500GB                  | 1         | 1      | 4.55%   |
| Toshiba MK6465GSX 640GB                   | 1         | 1      | 4.55%   |
| Seagate ST9320325AS 320GB                 | 1         | 1      | 4.55%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 4.55%   |
| Seagate ST4000DM004-2CV104 4TB            | 1         | 1      | 4.55%   |
| Seagate ST320LT020-9YG142 320GB           | 1         | 1      | 4.55%   |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 4.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1      | 4.55%   |
| Seagate ST1000DM003-1SB102 1TB            | 1         | 1      | 4.55%   |
| Samsung Electronics HM121HI 120GB         | 1         | 4      | 4.55%   |
| Samsung Electronics HD161HJ 160GB         | 1         | 1      | 4.55%   |
| NGFF 2280 512GB SSD                       | 1         | 1      | 4.55%   |
| Micron Technology MTFDDAV256TBN 256GB SSD | 1         | 1      | 4.55%   |
| Hitachi HTS545050A7E380 500GB             | 1         | 1      | 4.55%   |
| Fujitsu MHY2120BH 120GB                   | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 40.91%  |
| Toshiba             | 3         | 3      | 13.64%  |
| WDC                 | 2         | 2      | 9.09%   |
| Samsung Electronics | 2         | 5      | 9.09%   |
| Apacer              | 2         | 2      | 9.09%   |
| NGFF                | 1         | 1      | 4.55%   |
| Micron Technology   | 1         | 1      | 4.55%   |
| Hitachi             | 1         | 1      | 4.55%   |
| Fujitsu             | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 50%     |
| Toshiba             | 3         | 3      | 16.67%  |
| WDC                 | 2         | 2      | 11.11%  |
| Samsung Electronics | 2         | 5      | 11.11%  |
| Hitachi             | 1         | 1      | 5.56%   |
| Fujitsu             | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 21     | 81.82%  |
| SSD  | 4         | 4      | 18.18%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 81        | 122    | 51.92%  |
| Works    | 52        | 71     | 33.33%  |
| Malfunc  | 22        | 25     | 14.1%   |
| Failed   | 1         | 1      | 0.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 95        | 64.63%  |
| AMD                         | 26        | 17.69%  |
| Nvidia                      | 6         | 4.08%   |
| SanDisk                     | 4         | 2.72%   |
| Samsung Electronics         | 3         | 2.04%   |
| Micron Technology           | 2         | 1.36%   |
| Kingston Technology Company | 2         | 1.36%   |
| JMicron Technology          | 2         | 1.36%   |
| Union Memory (Shenzhen)     | 1         | 0.68%   |
| SK hynix                    | 1         | 0.68%   |
| Seagate Technology          | 1         | 0.68%   |
| Micron/Crucial Technology   | 1         | 0.68%   |
| Marvell Technology Group    | 1         | 0.68%   |
| KIOXIA                      | 1         | 0.68%   |
| ASMedia Technology          | 1         | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 8%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 6.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 4.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 4%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6         | 3.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 3.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6         | 3.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 2.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 2.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 2.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 2.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.29%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 1.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 1.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 1.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.14%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.14%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 1.14%   |
| Micron Non-Volatile memory controller                                            | 2         | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.14%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 1.14%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.14%   |
| AMD FCH IDE Controller                                                           | 2         | 1.14%   |
| AMD 400 Series Chipset SATA Controller                                           | 2         | 1.14%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.57%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.57%   |
| Seagate FireCuda 520 SSD                                                         | 1         | 0.57%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.57%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.57%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.57%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 107       | 68.15%  |
| IDE  | 28        | 17.83%  |
| NVMe | 16        | 10.19%  |
| RAID | 6         | 3.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 120       | 80%     |
| AMD    | 28        | 18.67%  |
| ARM    | 2         | 1.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 2.67%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 2.67%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 4         | 2.67%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 2%      |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 2%      |
| Intel Atom CPU Z3735F @ 1.33GHz               | 3         | 2%      |
| Intel Pentium D CPU 2.80GHz                   | 2         | 1.33%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 1.33%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.33%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.33%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.33%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.33%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.33%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 1.33%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.33%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.33%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 1.33%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 2         | 1.33%   |
| ARM Processor                                 | 2         | 1.33%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 1.33%   |
| AMD E-450 APU with Radeon HD Graphics         | 2         | 1.33%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 1.33%   |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 0.67%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz           | 1         | 0.67%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.67%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.67%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.67%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.67%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.67%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.67%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.67%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.67%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.67%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 0.67%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 0.67%   |
| Intel Core i7-2635QM CPU @ 2.00GHz            | 1         | 0.67%   |
| Intel Core i7 CPU 920 @ 2.67GHz               | 1         | 0.67%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 1         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 25        | 16.67%  |
| Intel Celeron      | 23        | 15.33%  |
| Intel Atom         | 15        | 10%     |
| Intel Core i3      | 14        | 9.33%   |
| Intel Core 2 Duo   | 14        | 9.33%   |
| Intel Core i7      | 13        | 8.67%   |
| Intel Pentium      | 5         | 3.33%   |
| AMD Ryzen 5        | 5         | 3.33%   |
| AMD A6             | 3         | 2%      |
| Other              | 2         | 1.33%   |
| Intel Xeon         | 2         | 1.33%   |
| Intel Pentium Dual | 2         | 1.33%   |
| Intel Pentium D    | 2         | 1.33%   |
| Intel Core 2 Quad  | 2         | 1.33%   |
| AMD Ryzen 7        | 2         | 1.33%   |
| AMD FX             | 2         | 1.33%   |
| AMD E1             | 2         | 1.33%   |
| AMD E              | 2         | 1.33%   |
| AMD Athlon 64 X2   | 2         | 1.33%   |
| Intel Core m3      | 1         | 0.67%   |
| Intel Core i9      | 1         | 0.67%   |
| Intel Core 2       | 1         | 0.67%   |
| AMD Ryzen 9        | 1         | 0.67%   |
| AMD Phenom II X6   | 1         | 0.67%   |
| AMD Phenom II X4   | 1         | 0.67%   |
| AMD GX             | 1         | 0.67%   |
| AMD G              | 1         | 0.67%   |
| AMD C-60           | 1         | 0.67%   |
| AMD Athlon II X2   | 1         | 0.67%   |
| AMD A8             | 1         | 0.67%   |
| AMD A4             | 1         | 0.67%   |
| AMD A10            | 1         | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 85        | 56.67%  |
| 4       | 48        | 32%     |
| 6       | 6         | 4%      |
| 1       | 4         | 2.67%   |
| 8       | 3         | 2%      |
| 3       | 2         | 1.33%   |
| 10      | 1         | 0.67%   |
| Unknown | 1         | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 149       | 99.33%  |
| Unknown | 1         | 0.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 87        | 58%     |
| 2       | 62        | 41.33%  |
| Unknown | 1         | 0.67%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 149       | 99.33%  |
| 64-bit         | 1         | 0.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 37.09%  |
| 0x206a7    | 9         | 5.96%   |
| 0x406c4    | 8         | 5.3%    |
| 0x306a9    | 6         | 3.97%   |
| 0x1067a    | 5         | 3.31%   |
| 0x706e5    | 4         | 2.65%   |
| 0x406c3    | 4         | 2.65%   |
| 0x806ec    | 3         | 1.99%   |
| 0x706a8    | 3         | 1.99%   |
| 0x40651    | 3         | 1.99%   |
| 0x306c3    | 3         | 1.99%   |
| 0x106ca    | 3         | 1.99%   |
| 0x05000119 | 3         | 1.99%   |
| 0x906c0    | 2         | 1.32%   |
| 0x806ea    | 2         | 1.32%   |
| 0x806e9    | 2         | 1.32%   |
| 0x6fd      | 2         | 1.32%   |
| 0x6fb      | 2         | 1.32%   |
| 0x506e3    | 2         | 1.32%   |
| 0x20655    | 2         | 1.32%   |
| 0x0a50000c | 2         | 1.32%   |
| 0x0700010f | 2         | 1.32%   |
| 0x06006705 | 2         | 1.32%   |
| 0xa0653    | 1         | 0.66%   |
| 0x906ed    | 1         | 0.66%   |
| 0x806eb    | 1         | 0.66%   |
| 0x706a1    | 1         | 0.66%   |
| 0x6fa      | 1         | 0.66%   |
| 0x6f6      | 1         | 0.66%   |
| 0x506c9    | 1         | 0.66%   |
| 0x406e3    | 1         | 0.66%   |
| 0x30679    | 1         | 0.66%   |
| 0x30678    | 1         | 0.66%   |
| 0x106a5    | 1         | 0.66%   |
| 0x10676    | 1         | 0.66%   |
| 0x0a50000b | 1         | 0.66%   |
| 0x0a201009 | 1         | 0.66%   |
| 0x08701021 | 1         | 0.66%   |
| 0x08001138 | 1         | 0.66%   |
| 0x06003106 | 1         | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 24        | 16%     |
| SandyBridge   | 15        | 10%     |
| Penryn        | 11        | 7.33%   |
| IvyBridge     | 10        | 6.67%   |
| KabyLake      | 9         | 6%      |
| Haswell       | 9         | 6%      |
| Goldmont plus | 8         | 5.33%   |
| Core          | 8         | 5.33%   |
| Zen 3         | 4         | 2.67%   |
| Westmere      | 4         | 2.67%   |
| Skylake       | 4         | 2.67%   |
| Piledriver    | 4         | 2.67%   |
| IceLake       | 4         | 2.67%   |
| Bobcat        | 4         | 2.67%   |
| K10           | 3         | 2%      |
| Bonnell       | 3         | 2%      |
| Zen+          | 2         | 1.33%   |
| Tremont       | 2         | 1.33%   |
| NetBurst      | 2         | 1.33%   |
| Nehalem       | 2         | 1.33%   |
| K8 Hammer     | 2         | 1.33%   |
| Jaguar        | 2         | 1.33%   |
| Excavator     | 2         | 1.33%   |
| CometLake     | 2         | 1.33%   |
| Broadwell     | 2         | 1.33%   |
| Unknown       | 2         | 1.33%   |
| Zen 2         | 1         | 0.67%   |
| Zen           | 1         | 0.67%   |
| Steamroller   | 1         | 0.67%   |
| Puma          | 1         | 0.67%   |
| K10 Llano     | 1         | 0.67%   |
| Goldmont      | 1         | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 98        | 61.25%  |
| AMD    | 37        | 23.13%  |
| Nvidia | 25        | 15.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 9.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 8.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 4.68%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 4.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 4.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 2.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 2.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.34%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.75%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 1.75%   |
| Nvidia GT218 [ION]                                                                       | 2         | 1.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.17%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.17%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.17%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.17%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.17%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.17%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 1.17%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 1.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.17%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.17%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2         | 1.17%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2         | 1.17%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2         | 1.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.17%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1         | 0.58%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.58%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.58%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.58%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.58%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.58%   |
| Nvidia GM200GL [Tesla M40]                                                               | 1         | 0.58%   |
| Nvidia GM200GL [Quadro M6000]                                                            | 1         | 0.58%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 85        | 56.67%  |
| 1 x AMD            | 26        | 17.33%  |
| 1 x Nvidia         | 19        | 12.67%  |
| Intel + AMD        | 5         | 3.33%   |
| Other              | 4         | 2.67%   |
| 2 x AMD            | 4         | 2.67%   |
| Intel + Nvidia     | 4         | 2.67%   |
| Intel + 2 x Nvidia | 1         | 0.67%   |
| Intel + 2 x AMD    | 1         | 0.67%   |
| AMD + Nvidia       | 1         | 0.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 136       | 90.67%  |
| Proprietary | 8         | 5.33%   |
| Unknown     | 6         | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 117       | 77.48%  |
| 0.01-0.5   | 14        | 9.27%   |
| 1.01-2.0   | 6         | 3.97%   |
| 0.51-1.0   | 5         | 3.31%   |
| 7.01-8.0   | 4         | 2.65%   |
| 2.01-3.0   | 2         | 1.32%   |
| 8.01-16.0  | 2         | 1.32%   |
| 3.01-4.0   | 1         | 0.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 20        | 14.08%  |
| Samsung Electronics     | 18        | 12.68%  |
| LG Display              | 18        | 12.68%  |
| Chimei Innolux          | 15        | 10.56%  |
| BOE                     | 10        | 7.04%   |
| Dell                    | 7         | 4.93%   |
| Hewlett-Packard         | 6         | 4.23%   |
| Goldstar                | 6         | 4.23%   |
| Apple                   | 6         | 4.23%   |
| Philips                 | 3         | 2.11%   |
| CPT                     | 3         | 2.11%   |
| Ancor Communications    | 3         | 2.11%   |
| Acer                    | 3         | 2.11%   |
| Sharp                   | 2         | 1.41%   |
| Lenovo                  | 2         | 1.41%   |
| Eizo                    | 2         | 1.41%   |
| Chi Mei Optoelectronics | 2         | 1.41%   |
| BenQ                    | 2         | 1.41%   |
| ViewSonic               | 1         | 0.7%    |
| Unknown                 | 1         | 0.7%    |
| Toshiba                 | 1         | 0.7%    |
| Sony                    | 1         | 0.7%    |
| SNC                     | 1         | 0.7%    |
| Sampo                   | 1         | 0.7%    |
| MSI                     | 1         | 0.7%    |
| LG Philips              | 1         | 0.7%    |
| LG Electronics          | 1         | 0.7%    |
| JVC                     | 1         | 0.7%    |
| JDI                     | 1         | 0.7%    |
| InfoVision              | 1         | 0.7%    |
| HannStar                | 1         | 0.7%    |
| Daewoo                  | 1         | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 4         | 2.8%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.4%    |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.4%    |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 1.4%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 1.4%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 1.4%    |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch         | 1         | 0.7%    |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1         | 0.7%    |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch              | 1         | 0.7%    |
| Sony TV SNY9C01 1920x1080                                             | 1         | 0.7%    |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 1         | 0.7%    |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 0.7%    |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch              | 1         | 0.7%    |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.7%    |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1         | 0.7%    |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch  | 1         | 0.7%    |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch  | 1         | 0.7%    |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch   | 1         | 0.7%    |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 0.7%    |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1         | 0.7%    |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch  | 1         | 0.7%    |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch    | 1         | 0.7%    |
| Sampo 800S STC0800 800x600 170x127mm 8.4-inch                         | 1         | 0.7%    |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 1         | 0.7%    |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch             | 1         | 0.7%    |
| Philips 191EL PHLC050 1366x768 410x230mm 18.5-inch                    | 1         | 0.7%    |
| MSI MAG272CQR MSI3CA6 2560x1440 598x336mm 27.0-inch                   | 1         | 0.7%    |
| LG Philips LCD Monitor LPLEC00 1280x800 331x207mm 15.4-inch           | 1         | 0.7%    |
| LG Electronics LCD Monitor E2241 1920x1080                            | 1         | 0.7%    |
| LG Display LCD Monitor LGD0680 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 51        | 36.96%  |
| 1920x1080 (FHD)    | 35        | 25.36%  |
| 1280x800 (WXGA)    | 11        | 7.97%   |
| 1600x900 (HD+)     | 10        | 7.25%   |
| 1680x1050 (WSXGA+) | 6         | 4.35%   |
| 1280x1024 (SXGA)   | 5         | 3.62%   |
| 2560x1440 (QHD)    | 4         | 2.9%    |
| 1440x900 (WXGA+)   | 3         | 2.17%   |
| 1360x768           | 2         | 1.45%   |
| 800x600            | 1         | 0.72%   |
| 3840x2160 (4K)     | 1         | 0.72%   |
| 3200x1800 (QHD+)   | 1         | 0.72%   |
| 3000x2000          | 1         | 0.72%   |
| 2560x1600          | 1         | 0.72%   |
| 2560x1080          | 1         | 0.72%   |
| 2160x1440          | 1         | 0.72%   |
| 1920x1200 (WUXGA)  | 1         | 0.72%   |
| 1528x1222          | 1         | 0.72%   |
| 1280x768           | 1         | 0.72%   |
| 1280x720 (HD)      | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 22.7%   |
| 13      | 20        | 14.18%  |
| 14      | 16        | 11.35%  |
| 11      | 11        | 7.8%    |
| 17      | 8         | 5.67%   |
| 23      | 7         | 4.96%   |
| 18      | 6         | 4.26%   |
| 22      | 5         | 3.55%   |
| 19      | 5         | 3.55%   |
| Unknown | 5         | 3.55%   |
| 27      | 4         | 2.84%   |
| 24      | 4         | 2.84%   |
| 21      | 4         | 2.84%   |
| 20      | 4         | 2.84%   |
| 72      | 1         | 0.71%   |
| 49      | 1         | 0.71%   |
| 43      | 1         | 0.71%   |
| 34      | 1         | 0.71%   |
| 28      | 1         | 0.71%   |
| 16      | 1         | 0.71%   |
| 12      | 1         | 0.71%   |
| 10      | 1         | 0.71%   |
| 9       | 1         | 0.71%   |
| 8       | 1         | 0.71%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 57        | 40.43%  |
| 201-300     | 26        | 18.44%  |
| 401-500     | 23        | 16.31%  |
| 501-600     | 14        | 9.93%   |
| 351-400     | 8         | 5.67%   |
| Unknown     | 5         | 3.55%   |
| 601-700     | 2         | 1.42%   |
| 101-200     | 2         | 1.42%   |
| 701-800     | 1         | 0.71%   |
| 1501-2000   | 1         | 0.71%   |
| 1001-1500   | 1         | 0.71%   |
| 901-1000    | 1         | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 101       | 74.81%  |
| 16/10   | 21        | 15.56%  |
| Unknown | 4         | 2.96%   |
| 5/4     | 3         | 2.22%   |
| 4/3     | 3         | 2.22%   |
| 3/2     | 2         | 1.48%   |
| 21/9    | 1         | 0.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 31        | 22.14%  |
| 81-90          | 30        | 21.43%  |
| 201-250        | 17        | 12.14%  |
| 51-60          | 11        | 7.86%   |
| 151-200        | 10        | 7.14%   |
| 141-150        | 8         | 5.71%   |
| 71-80          | 6         | 4.29%   |
| 121-130        | 6         | 4.29%   |
| Unknown        | 5         | 3.57%   |
| 301-350        | 4         | 2.86%   |
| More than 1000 | 2         | 1.43%   |
| 41-50          | 2         | 1.43%   |
| 251-300        | 2         | 1.43%   |
| 501-1000       | 2         | 1.43%   |
| 61-70          | 1         | 0.71%   |
| 1-40           | 1         | 0.71%   |
| 131-140        | 1         | 0.71%   |
| 111-120        | 1         | 0.71%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 51        | 36.69%  |
| 51-100        | 42        | 30.22%  |
| 121-160       | 27        | 19.42%  |
| 161-240       | 8         | 5.76%   |
| Unknown       | 5         | 3.6%    |
| 1-50          | 4         | 2.88%   |
| More than 240 | 2         | 1.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 136       | 90.67%  |
| 2     | 9         | 6%      |
| 0     | 4         | 2.67%   |
| 3     | 1         | 0.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 72        | 33.49%  |
| Intel                           | 59        | 27.44%  |
| Qualcomm Atheros                | 31        | 14.42%  |
| Broadcom                        | 15        | 6.98%   |
| TP-Link                         | 5         | 2.33%   |
| Samsung Electronics             | 5         | 2.33%   |
| Marvell Technology Group        | 5         | 2.33%   |
| Nvidia                          | 4         | 1.86%   |
| Qualcomm Atheros Communications | 3         | 1.4%    |
| Broadcom Limited                | 3         | 1.4%    |
| MediaTek                        | 2         | 0.93%   |
| Trident Microsystems            | 1         | 0.47%   |
| Sierra Wireless                 | 1         | 0.47%   |
| Ralink Technology               | 1         | 0.47%   |
| Ralink                          | 1         | 0.47%   |
| Qualcomm                        | 1         | 0.47%   |
| NetGear                         | 1         | 0.47%   |
| Microsoft                       | 1         | 0.47%   |
| ICS Advent                      | 1         | 0.47%   |
| Belkin Components               | 1         | 0.47%   |
| ASUSTek Computer                | 1         | 0.47%   |
| ASIX Electronics                | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 44        | 17.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 10        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 7         | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 6         | 2.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 6         | 2.4%    |
| Intel Wireless 7265                                                 | 6         | 2.4%    |
| Intel Wireless 7260                                                 | 6         | 2.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 5         | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 5         | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 4         | 1.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 4         | 1.6%    |
| Samsung Galaxy series, misc. (tethering mode)                       | 3         | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 3         | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 3         | 1.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 3         | 1.2%    |
| Intel Ethernet Controller I225-V                                    | 3         | 1.2%    |
| Intel Centrino Wireless-N 2230                                      | 3         | 1.2%    |
| Intel Centrino Advanced-N 6235                                      | 3         | 1.2%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                   | 3         | 1.2%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 2         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2         | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 2         | 0.8%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2         | 0.8%    |
| Realtek 802.11n WLAN Adapter                                        | 2         | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                     | 2         | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 2         | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2         | 0.8%    |
| Nvidia MCP77 Ethernet                                               | 2         | 0.8%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller             | 2         | 0.8%    |
| Intel Wireless 8260                                                 | 2         | 0.8%    |
| Intel Wireless 3160                                                 | 2         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection               | 2         | 0.8%    |
| Intel NM10/ICH7 Family LAN Controller                               | 2         | 0.8%    |
| Intel Ethernet Connection I218-LM                                   | 2         | 0.8%    |
| Intel Ethernet Connection I217-LM                                   | 2         | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 0.8%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                     | 2         | 0.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                      | 2         | 0.8%    |
| Broadcom BCM43228 802.11a/b/g/n                                     | 2         | 0.8%    |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2         | 0.8%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 36.59%  |
| Qualcomm Atheros                | 28        | 22.76%  |
| Realtek Semiconductor           | 23        | 18.7%   |
| Broadcom                        | 9         | 7.32%   |
| TP-Link                         | 4         | 3.25%   |
| Qualcomm Atheros Communications | 3         | 2.44%   |
| MediaTek                        | 2         | 1.63%   |
| Broadcom Limited                | 2         | 1.63%   |
| Sierra Wireless                 | 1         | 0.81%   |
| Ralink Technology               | 1         | 0.81%   |
| Ralink                          | 1         | 0.81%   |
| NetGear                         | 1         | 0.81%   |
| Microsoft                       | 1         | 0.81%   |
| Belkin Components               | 1         | 0.81%   |
| ASUSTek Computer                | 1         | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 6         | 4.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 6         | 4.88%   |
| Intel Wireless 7265                                                 | 6         | 4.88%   |
| Intel Wireless 7260                                                 | 6         | 4.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 5         | 4.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 5         | 4.07%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 4         | 3.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 3         | 2.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 3         | 2.44%   |
| Intel Centrino Wireless-N 2230                                      | 3         | 2.44%   |
| Intel Centrino Advanced-N 6235                                      | 3         | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2         | 1.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 2         | 1.63%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2         | 1.63%   |
| Realtek 802.11n WLAN Adapter                                        | 2         | 1.63%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2         | 1.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 2         | 1.63%   |
| Intel Wireless 8260                                                 | 2         | 1.63%   |
| Intel Wireless 3160                                                 | 2         | 1.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection               | 2         | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 1.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 2         | 1.63%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 2         | 1.63%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2         | 1.63%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1         | 0.81%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1         | 0.81%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1         | 0.81%   |
| TP-Link 802.11ac NIC                                                | 1         | 0.81%   |
| Sierra Wireless EM7305 Modem                                        | 1         | 0.81%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 1         | 0.81%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 1         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 1         | 0.81%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1         | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1         | 0.81%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1         | 0.81%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1         | 0.81%   |
| Realtek Realtek Network controller                                  | 1         | 0.81%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                   | 1         | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                           | 1         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 61        | 48.41%  |
| Intel                    | 27        | 21.43%  |
| Qualcomm Atheros         | 9         | 7.14%   |
| Broadcom                 | 9         | 7.14%   |
| Samsung Electronics      | 5         | 3.97%   |
| Marvell Technology Group | 5         | 3.97%   |
| Nvidia                   | 4         | 3.17%   |
| Trident Microsystems     | 1         | 0.79%   |
| TP-Link                  | 1         | 0.79%   |
| Qualcomm                 | 1         | 0.79%   |
| ICS Advent               | 1         | 0.79%   |
| Broadcom Limited         | 1         | 0.79%   |
| ASIX Electronics         | 1         | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 44        | 34.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 7.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 5.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 3.15%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 2.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 2.36%   |
| Intel Ethernet Controller I225-V                                               | 3         | 2.36%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 2.36%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 1.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.57%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 1.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.57%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 2         | 1.57%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.57%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.57%   |
| Trident Microsystems 4DWave DX                                                 | 1         | 0.79%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.79%   |
| Realtek RTL8150 Fast Ethernet Adapter                                          | 1         | 0.79%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.79%   |
| Qualcomm MegaFon M150-4                                                        | 1         | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.79%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.79%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.79%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.79%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.79%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1         | 0.79%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 0.79%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.79%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.79%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.79%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 117       | 51.09%  |
| WiFi     | 112       | 48.91%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 84        | 57.53%  |
| Ethernet | 62        | 42.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 73        | 48.67%  |
| 1     | 59        | 39.33%  |
| 0     | 15        | 10%     |
| 3     | 2         | 1.33%   |
| 4     | 1         | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 117       | 77.48%  |
| Yes  | 34        | 22.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 42.31%  |
| Realtek Semiconductor           | 11        | 14.1%   |
| Qualcomm Atheros Communications | 7         | 8.97%   |
| Apple                           | 5         | 6.41%   |
| Broadcom                        | 4         | 5.13%   |
| IMC Networks                    | 3         | 3.85%   |
| Foxconn / Hon Hai               | 3         | 3.85%   |
| Dell                            | 3         | 3.85%   |
| MediaTek                        | 2         | 2.56%   |
| Cambridge Silicon Radio         | 2         | 2.56%   |
| Toshiba                         | 1         | 1.28%   |
| Syntek                          | 1         | 1.28%   |
| Logitech                        | 1         | 1.28%   |
| Lite-On Technology              | 1         | 1.28%   |
| Alps Electric                   | 1         | 1.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 18        | 23.08%  |
| Realtek Bluetooth Radio                                                             | 7         | 8.97%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 6.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 6.41%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 3.85%   |
| Intel AX201 Bluetooth                                                               | 3         | 3.85%   |
| Apple Bluetooth Host Controller                                                     | 3         | 3.85%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 2.56%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 2.56%   |
| MediaTek Wireless_Device                                                            | 2         | 2.56%   |
| IMC Networks Bluetooth Device                                                       | 2         | 2.56%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 2.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 2.56%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 1.28%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 1.28%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 1.28%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.28%   |
| Logitech BT Mini-Receiver (HCI mode)                                                | 1         | 1.28%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.28%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.28%   |
| Intel AX200 Bluetooth                                                               | 1         | 1.28%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 1.28%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.28%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 1.28%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 1.28%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.28%   |
| Broadcom HP Portable Valentine                                                      | 1         | 1.28%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 1.28%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.28%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.28%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.28%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.28%   |
| Alps Electric Bluetooth Adapter                                                     | 1         | 1.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 105       | 61.76%  |
| AMD                                          | 33        | 19.41%  |
| Nvidia                                       | 21        | 12.35%  |
| C-Media Electronics                          | 3         | 1.76%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.59%   |
| Razer USA                                    | 1         | 0.59%   |
| MosArt Semiconductor                         | 1         | 0.59%   |
| Logitech                                     | 1         | 0.59%   |
| JMTek                                        | 1         | 0.59%   |
| Ensoniq                                      | 1         | 0.59%   |
| Creative Labs                                | 1         | 0.59%   |
| ASUSTek Computer                             | 1         | 0.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 6.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 5.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 4.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 4.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 3.98%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 3.98%   |
| AMD FCH Azalia Controller                                                                         | 7         | 3.48%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 2.49%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 2.49%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.49%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.99%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.99%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 4         | 1.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.49%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.49%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 1.49%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.49%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.49%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.49%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 1%      |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 1%      |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1%      |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1%      |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 1%      |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 1%      |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1%      |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1%      |
| AMD High Definition Audio Controller                                                              | 2         | 1%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 20.91%  |
| SK hynix            | 18        | 16.36%  |
| Unknown             | 17        | 15.45%  |
| Micron Technology   | 17        | 15.45%  |
| Kingston            | 7         | 6.36%   |
| Nanya Technology    | 4         | 3.64%   |
| Elpida              | 4         | 3.64%   |
| Corsair             | 4         | 3.64%   |
| G.Skill             | 3         | 2.73%   |
| Unknown             | 3         | 2.73%   |
| Unknown (ABCD)      | 2         | 1.82%   |
| Smart               | 2         | 1.82%   |
| Ramaxel Technology  | 1         | 0.91%   |
| Novatech            | 1         | 0.91%   |
| Kllisre             | 1         | 0.91%   |
| HMD                 | 1         | 0.91%   |
| AMD                 | 1         | 0.91%   |
| A-DATA Technology   | 1         | 0.91%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 2.5%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.5%    |
| Unknown                                                          | 3         | 2.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 1.67%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1.67%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 2         | 1.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.67%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 1.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.67%   |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 1.67%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.83%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.83%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.83%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.83%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.83%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.83%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.83%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 0.83%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s         | 1         | 0.83%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.83%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.83%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                     | 1         | 0.83%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 0.83%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.83%   |
| SK hynix RAM HT5SMRAP 2GB SODIMM DDR3 1600MT/s                   | 1         | 0.83%   |
| SK hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 1         | 0.83%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s             | 1         | 0.83%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1333MT/s           | 1         | 0.83%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 48        | 48.98%  |
| DDR4    | 26        | 26.53%  |
| DDR2    | 9         | 9.18%   |
| LPDDR4  | 7         | 7.14%   |
| SDRAM   | 3         | 3.06%   |
| LPDDR3  | 3         | 3.06%   |
| Unknown | 2         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 69.39%  |
| DIMM         | 19        | 19.39%  |
| Row Of Chips | 8         | 8.16%   |
| Unknown      | 3         | 3.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 36        | 32.14%  |
| 2048  | 33        | 29.46%  |
| 8192  | 27        | 24.11%  |
| 16384 | 6         | 5.36%   |
| 1024  | 6         | 5.36%   |
| 32768 | 2         | 1.79%   |
| 6144  | 1         | 0.89%   |
| 512   | 1         | 0.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 30        | 29.41%  |
| 3200    | 11        | 10.78%  |
| 1333    | 11        | 10.78%  |
| 2667    | 6         | 5.88%   |
| 667     | 6         | 5.88%   |
| 2400    | 4         | 3.92%   |
| 1334    | 4         | 3.92%   |
| 1066    | 4         | 3.92%   |
| 1067    | 3         | 2.94%   |
| Unknown | 3         | 2.94%   |
| 4267    | 2         | 1.96%   |
| 3266    | 2         | 1.96%   |
| 2133    | 2         | 1.96%   |
| 2048    | 2         | 1.96%   |
| 1867    | 2         | 1.96%   |
| 1866    | 2         | 1.96%   |
| 4199    | 1         | 0.98%   |
| 3733    | 1         | 0.98%   |
| 3666    | 1         | 0.98%   |
| 3400    | 1         | 0.98%   |
| 3066    | 1         | 0.98%   |
| 2800    | 1         | 0.98%   |
| 975     | 1         | 0.98%   |
| 800     | 1         | 0.98%   |

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
| Chicony Electronics                    | 23        | 26.14%  |
| Microdia                               | 11        | 12.5%   |
| Sunplus Innovation Technology          | 7         | 7.95%   |
| Realtek Semiconductor                  | 6         | 6.82%   |
| Apple                                  | 5         | 5.68%   |
| Syntek                                 | 4         | 4.55%   |
| IMC Networks                           | 4         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.41%   |
| Alcor Micro                            | 3         | 3.41%   |
| Silicon Motion                         | 2         | 2.27%   |
| Quanta                                 | 2         | 2.27%   |
| Logitech                               | 2         | 2.27%   |
| Lenovo                                 | 2         | 2.27%   |
| ALi                                    | 2         | 2.27%   |
| Acer                                   | 2         | 2.27%   |
| WaveRider Communications               | 1         | 1.14%   |
| USB Camera CS                          | 1         | 1.14%   |
| Suyin                                  | 1         | 1.14%   |
| SunplusIT                              | 1         | 1.14%   |
| Ricoh                                  | 1         | 1.14%   |
| Pixart Imaging                         | 1         | 1.14%   |
| Microsoft                              | 1         | 1.14%   |
| Lite-On Technology                     | 1         | 1.14%   |
| Cubeternet                             | 1         | 1.14%   |
| AVerMedia Technologies                 | 1         | 1.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 6         | 6.74%   |
| Realtek Integrated_Webcam_HD                        | 3         | 3.37%   |
| Chicony HD WebCam                                   | 3         | 3.37%   |
| Alcor Micro USB 2.0 Camera                          | 3         | 3.37%   |
| Sunplus HD WebCam                                   | 2         | 2.25%   |
| Microdia Lenovo EasyCamera                          | 2         | 2.25%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.25%   |
| Microdia Integrated Webcam                          | 2         | 2.25%   |
| Microdia HP Webcam-50                               | 2         | 2.25%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 2.25%   |
| Chicony FJ Camera                                   | 2         | 2.25%   |
| Chicony EasyCamera                                  | 2         | 2.25%   |
| Apple FaceTime HD Camera                            | 2         | 2.25%   |
| ALi WebCam                                          | 2         | 2.25%   |
| WaveRider USB 2.0 Camera                            | 1         | 1.12%   |
| USB Camera CS USB Camera CS                         | 1         | 1.12%   |
| Syntek USB2.0 Camera                                | 1         | 1.12%   |
| Syntek USB Camera Device                            | 1         | 1.12%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.12%   |
| Syntek HD WebCam                                    | 1         | 1.12%   |
| Suyin 1.3M Front                                    | 1         | 1.12%   |
| SunplusIT MTD camera                                | 1         | 1.12%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 1.12%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.12%   |
| Sunplus HD User Facing                              | 1         | 1.12%   |
| Sunplus Dell Integrated HD Webcam                   | 1         | 1.12%   |
| Sunplus Asus Webcam                                 | 1         | 1.12%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 1.12%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 1.12%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 1.12%   |
| Realtek USB Camera                                  | 1         | 1.12%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.12%   |
| Realtek EasyCamera                                  | 1         | 1.12%   |
| Quanta HP Webcam                                    | 1         | 1.12%   |
| Quanta Chromebook HD Camera                         | 1         | 1.12%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                | 1         | 1.12%   |
| Microsoft LifeCam VX-800                            | 1         | 1.12%   |
| Microdia Webcam Vitade AF                           | 1         | 1.12%   |
| Microdia Webcam                                     | 1         | 1.12%   |
| Microdia 1.3 MPixel Integrated Webcam               | 1         | 1.12%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 31.25%  |
| Upek                  | 3         | 18.75%  |
| Synaptics             | 2         | 12.5%   |
| STMicroelectronics    | 2         | 12.5%   |
| AuthenTec             | 2         | 12.5%   |
| LighTuning Technology | 1         | 6.25%   |
| Elan Microelectronics | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 18.75%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 12.5%   |
| Unknown                                                | 2         | 12.5%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 6.25%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 6.25%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 6.25%   |
| Elan ELAN:Fingerprint                                  | 1         | 6.25%   |
| AuthenTec Fingerprint Sensor                           | 1         | 6.25%   |
| AuthenTec AES2810                                      | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 4         | 66.67%  |
| O2 Micro | 1         | 16.67%  |
| Cherry   | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 16.67%  |
| Cherry SmartCard Reader Keyboard KC 1000 SC    | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 118       | 78.15%  |
| 1     | 32        | 21.19%  |
| 2     | 1         | 0.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 16        | 47.06%  |
| Graphics card      | 5         | 14.71%  |
| Chipcard           | 5         | 14.71%  |
| Net/wireless       | 3         | 8.82%   |
| Camera             | 2         | 5.88%   |
| Storage            | 1         | 2.94%   |
| Network            | 1         | 2.94%   |
| Bluetooth          | 1         | 2.94%   |

