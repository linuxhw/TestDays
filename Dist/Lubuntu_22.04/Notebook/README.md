Lubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 149

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | powered classmate PC        | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| Dell          | Latitude E6410              | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Toshiba       | Satellite Pro S500          | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| Acer          | Aspire ES1-711              | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Toshiba       | Satellite Pro S500          | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| ASUSTek       | F50SV                       | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Google        | Celes                       | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| Acer          | Aspire SW3-013              | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| Google        | Candy                       | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| ASUSTek       | K72F                        | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Acer          | Aspire SW3-013              | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Acer          | Swift SF314-54G             | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| Dell          | Latitude E7470              | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| HP            | 2000                        | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| Apple         | MacBookPro8,1               | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Toshiba       | Satellite Pro S500          | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| GPU Compan... | GWTC116-2                   | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| ASUSTek       | K70IO                       | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| ASUSTek       | K70IO                       | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Acer          | AO722                       | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| Unknown       | Unknown                     | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| HP            | Pavilion g6                 | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| HP            | Pavilion g6                 | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Toshiba       | Satellite Pro S500          | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| Lenovo        | G50-45 80E3                 | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| Acer          | Aspire E1-571               | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Google        | Apel                        | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| Lenovo        | G50-70 20351                | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Fujitsu       | LIFEBOOK U904               | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Packard Be... | EasyNote TS44HR             | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Gateway       | NE46R                       | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| Dell          | Inspiron 11-3168            | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| HP            | ProBook 4730s               | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Lenovo        | B590 20208                  | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Acer          | Aspire 7250G                | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| Dell          | Vostro 3360                 | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| OEM           | Unknown                     | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Dell          | Precision 3510              | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Google        | Celes                       | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Dell          | XPS M1330                   | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Sony          | VPCEB15FM                   | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| HP            | 245 G2                      | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| HP            | 245 G2                      | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| Lenovo        | G50-30 80G0                 | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| Google        | Bobba360                    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Gateway       | Sonic-C                     | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Dell          | Latitude XT                 | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| Intel         | W7650                       | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| Apple         | MacBookPro8,1               | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | Pavilion g6                 | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| HP            | Pavilion g6                 | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| Toshiba       | Satellite L40               | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Acer          | Aspire V5-573G              | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Intel         | W7650                       | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Apple         | MacBookPro14,1              | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Apple         | MacBookPro14,1              | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S751               | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Google        | Bobba360                    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Dell          | Latitude 7480               | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| HP            | Pavilion dv4                | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| Intel         | W7650                       | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Intel         | W7650                       | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-43-generic     | 19        | 16.1%   |
| 5.15.0-56-generic     | 11        | 9.32%   |
| 5.15.0-30-generic     | 8         | 6.78%   |
| 5.15.0-25-generic     | 8         | 6.78%   |
| 5.15.0-47-generic     | 7         | 5.93%   |
| 5.15.0-46-generic     | 7         | 5.93%   |
| 5.15.0-58-generic     | 6         | 5.08%   |
| 5.15.0-52-generic     | 6         | 5.08%   |
| 5.15.0-27-generic     | 6         | 5.08%   |
| 5.15.0-53-generic     | 5         | 4.24%   |
| 5.15.0-57-generic     | 4         | 3.39%   |
| 5.15.0-50-generic     | 4         | 3.39%   |
| 5.15.0-41-generic     | 4         | 3.39%   |
| 5.15.0-48-generic     | 3         | 2.54%   |
| 5.15.0-40-generic     | 3         | 2.54%   |
| 5.15.0-35-generic     | 3         | 2.54%   |
| 5.15.0-37-generic     | 2         | 1.69%   |
| 5.15.0-33-generic     | 2         | 1.69%   |
| 6.0.12-x64v2-xanmod1  | 1         | 0.85%   |
| 5.19.8-xanmod1        | 1         | 0.85%   |
| 5.19.0-051900-generic | 1         | 0.85%   |
| 5.18.0-051800-generic | 1         | 0.85%   |
| 5.15.0-54-generic     | 1         | 0.85%   |
| 5.15.0-39-generic     | 1         | 0.85%   |
| 5.15.0-28-generic     | 1         | 0.85%   |
| 5.15.0-23-generic     | 1         | 0.85%   |
| 5.15.0-18-generic     | 1         | 0.85%   |
| 5.14.0-1040-oem       | 1         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 105       | 95.45%  |
| 6.0.12  | 1         | 0.91%   |
| 5.19.8  | 1         | 0.91%   |
| 5.19.0  | 1         | 0.91%   |
| 5.18.0  | 1         | 0.91%   |
| 5.14.0  | 1         | 0.91%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 105       | 95.45%  |
| 5.19    | 2         | 1.82%   |
| 6.0     | 1         | 0.91%   |
| 5.18    | 1         | 0.91%   |
| 5.14    | 1         | 0.91%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 107       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXQt       | 104       | 97.2%   |
| X-Cinnamon | 2         | 1.87%   |
| LXDE       | 1         | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 105       | 98.13%  |
| Tty  | 2         | 1.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 95        | 87.96%  |
| Unknown | 7         | 6.48%   |
| LightDM | 5         | 4.63%   |
| GDM3    | 1         | 0.93%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Notebooks | Percent |
|--------|-----------|---------|
| en_US  | 25        | 23.15%  |
| it_IT  | 9         | 8.33%   |
| fr_FR  | 8         | 7.41%   |
| C      | 7         | 6.48%   |
| pt_BR  | 6         | 5.56%   |
| pl_PL  | 6         | 5.56%   |
| de_DE  | 6         | 5.56%   |
| en_GB  | 5         | 4.63%   |
| en_AG  | 5         | 4.63%   |
| ru_RU  | 3         | 2.78%   |
| nl_BE  | 3         | 2.78%   |
| es_MX  | 2         | 1.85%   |
| es_ES  | 2         | 1.85%   |
| es_CR  | 2         | 1.85%   |
| es_AR  | 2         | 1.85%   |
| en_CA  | 2         | 1.85%   |
| tr_TR  | 1         | 0.93%   |
| lzh_TW | 1         | 0.93%   |
| ja_JP  | 1         | 0.93%   |
| hu_HU  | 1         | 0.93%   |
| fr_CA  | 1         | 0.93%   |
| fi_FI  | 1         | 0.93%   |
| es_EC  | 1         | 0.93%   |
| es_CO  | 1         | 0.93%   |
| es_CL  | 1         | 0.93%   |
| en_ZA  | 1         | 0.93%   |
| en_PH  | 1         | 0.93%   |
| en_DE  | 1         | 0.93%   |
| en_AU  | 1         | 0.93%   |
| el_GR  | 1         | 0.93%   |
| aa_DJ  | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 70        | 64.81%  |
| EFI  | 38        | 35.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 98        | 89.91%  |
| Overlay | 8         | 7.34%   |
| Btrfs   | 2         | 1.83%   |
| Ext2    | 1         | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 49        | 44.55%  |
| MBR     | 33        | 30%     |
| Unknown | 28        | 25.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 89.81%  |
| Yes       | 11        | 10.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 86        | 79.63%  |
| Yes       | 22        | 20.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 21        | 19.63%  |
| Hewlett-Packard     | 13        | 12.15%  |
| Dell                | 13        | 12.15%  |
| Acer                | 9         | 8.41%   |
| ASUSTek Computer    | 8         | 7.48%   |
| Google              | 6         | 5.61%   |
| Apple               | 5         | 4.67%   |
| Fujitsu             | 4         | 3.74%   |
| Sony                | 3         | 2.8%    |
| Unknown             | 3         | 2.8%    |
| Toshiba             | 2         | 1.87%   |
| Mediacom            | 2         | 1.87%   |
| Intel               | 2         | 1.87%   |
| Gateway             | 2         | 1.87%   |
| Thomson             | 1         | 0.93%   |
| SGIN                | 1         | 0.93%   |
| Samsung Electronics | 1         | 0.93%   |
| Pretech             | 1         | 0.93%   |
| Prestigio           | 1         | 0.93%   |
| Positivo            | 1         | 0.93%   |
| Packard Bell        | 1         | 0.93%   |
| OEM                 | 1         | 0.93%   |
| Kiano               | 1         | 0.93%   |
| IFSA                | 1         | 0.93%   |
| GPU Company         | 1         | 0.93%   |
| Fujitsu Siemens     | 1         | 0.93%   |
| Chuwi               | 1         | 0.93%   |
| Alienware           | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 4         | 3.74%   |
| Apple MacBookPro8,1                        | 3         | 2.8%    |
| Mediacom WinPad 11,6 FullHD- WPU11         | 2         | 1.87%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 1.87%   |
| Lenovo G50-30 80G0                         | 2         | 1.87%   |
| HP Pavilion g6                             | 2         | 1.87%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 1.87%   |
| Toshiba Satellite Pro S500                 | 1         | 0.93%   |
| Toshiba Satellite L40                      | 1         | 0.93%   |
| Thomson N14C4WH64                          | 1         | 0.93%   |
| Sony VPCEB15FM                             | 1         | 0.93%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.93%   |
| Sony SVE14A2V1EW                           | 1         | 0.93%   |
| SGIN laptop                                | 1         | 0.93%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.93%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.93%   |
| Prestigio PSB141C01BFH                     | 1         | 0.93%   |
| Positivo i500pro                           | 1         | 0.93%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.93%   |
| Lenovo Z70-80 80FG                         | 1         | 0.93%   |
| Lenovo ThinkPad X220 4291H82               | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0WE02   | 1         | 0.93%   |
| Lenovo ThinkPad T430 2342A19               | 1         | 0.93%   |
| Lenovo ThinkPad T410 2537CS0               | 1         | 0.93%   |
| Lenovo ThinkPad SL510 2847CXG              | 1         | 0.93%   |
| Lenovo ThinkPad P14s Gen 2a 21A1S00D00     | 1         | 0.93%   |
| Lenovo ThinkPad E550 20DF00CUFR            | 1         | 0.93%   |
| Lenovo IdeaPad S145-15IGM 81MX             | 1         | 0.93%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK      | 1         | 0.93%   |
| Lenovo IdeaPad 5 14ABA7 82SE               | 1         | 0.93%   |
| Lenovo IdeaPad 330-15IKB Touch 81DJ        | 1         | 0.93%   |
| Lenovo G505s 20255                         | 1         | 0.93%   |
| Lenovo G500 20236                          | 1         | 0.93%   |
| Lenovo G50-70 20351                        | 1         | 0.93%   |
| Lenovo G50-45 80E3                         | 1         | 0.93%   |
| Lenovo B590 20208                          | 1         | 0.93%   |
| Kiano SlimNote 14.1                        | 1         | 0.93%   |
| Intel powered classmate PC                 | 1         | 0.93%   |
| Intel Infoway                              | 1         | 0.93%   |
| IFSA Positivo BGH                          | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 7         | 6.54%   |
| Lenovo IdeaPad         | 6         | 5.61%   |
| Dell Latitude          | 6         | 5.61%   |
| Acer Aspire            | 6         | 5.61%   |
| HP Pavilion            | 4         | 3.74%   |
| Fujitsu LIFEBOOK       | 4         | 3.74%   |
| Unknown                | 4         | 3.74%   |
| HP ProBook             | 3         | 2.8%    |
| Apple MacBookPro8      | 3         | 2.8%    |
| Toshiba Satellite      | 2         | 1.87%   |
| Mediacom WinPad        | 2         | 1.87%   |
| Lenovo G50-30          | 2         | 1.87%   |
| Dell XPS               | 2         | 1.87%   |
| Thomson N14C4WH64      | 1         | 0.93%   |
| Sony VPCEB15FM         | 1         | 0.93%   |
| Sony VGN-SZ71WN        | 1         | 0.93%   |
| Sony SVE14A2V1EW       | 1         | 0.93%   |
| SGIN laptop            | 1         | 0.93%   |
| Samsung 300V3A         | 1         | 0.93%   |
| Pretech EVE            | 1         | 0.93%   |
| Prestigio PSB141C01BFH | 1         | 0.93%   |
| Positivo i500pro       | 1         | 0.93%   |
| Packard Bell EasyNote  | 1         | 0.93%   |
| Lenovo Z70-80          | 1         | 0.93%   |
| Lenovo G505s           | 1         | 0.93%   |
| Lenovo G500            | 1         | 0.93%   |
| Lenovo G50-70          | 1         | 0.93%   |
| Lenovo G50-45          | 1         | 0.93%   |
| Lenovo B590            | 1         | 0.93%   |
| Kiano SlimNote         | 1         | 0.93%   |
| Intel powered          | 1         | 0.93%   |
| Intel Infoway          | 1         | 0.93%   |
| IFSA Positivo          | 1         | 0.93%   |
| HP Laptop              | 1         | 0.93%   |
| HP Compaq              | 1         | 0.93%   |
| HP 250                 | 1         | 0.93%   |
| HP 245                 | 1         | 0.93%   |
| HP 2000                | 1         | 0.93%   |
| HP 15                  | 1         | 0.93%   |
| GPU Company GWTC116-2  | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 16        | 14.95%  |
| 2013 | 10        | 9.35%   |
| 2012 | 9         | 8.41%   |
| 2021 | 8         | 7.48%   |
| 2014 | 8         | 7.48%   |
| 2020 | 7         | 6.54%   |
| 2016 | 7         | 6.54%   |
| 2008 | 7         | 6.54%   |
| 2019 | 6         | 5.61%   |
| 2015 | 6         | 5.61%   |
| 2009 | 6         | 5.61%   |
| 2010 | 5         | 4.67%   |
| 2022 | 4         | 3.74%   |
| 2007 | 4         | 3.74%   |
| 2018 | 2         | 1.87%   |
| 2017 | 2         | 1.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 107       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 104       | 97.2%   |
| Enabled  | 3         | 2.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 100       | 93.46%  |
| Yes  | 7         | 6.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 45        | 41.67%  |
| 4.01-8.0   | 25        | 23.15%  |
| 1.01-2.0   | 15        | 13.89%  |
| 8.01-16.0  | 11        | 10.19%  |
| 2.01-3.0   | 5         | 4.63%   |
| 16.01-24.0 | 5         | 4.63%   |
| 32.01-64.0 | 2         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 54        | 47.79%  |
| 0.51-1.0 | 31        | 27.43%  |
| 2.01-3.0 | 20        | 17.7%   |
| 3.01-4.0 | 5         | 4.42%   |
| 4.01-8.0 | 3         | 2.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 90        | 82.57%  |
| 2      | 16        | 14.68%  |
| 3      | 2         | 1.83%   |
| 0      | 1         | 0.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 57        | 53.27%  |
| Yes       | 50        | 46.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 76.64%  |
| No        | 25        | 23.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 92.52%  |
| No        | 8         | 7.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 66.36%  |
| No        | 36        | 33.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 13        | 12.15%  |
| Italy        | 11        | 10.28%  |
| Germany      | 10        | 9.35%   |
| France       | 8         | 7.48%   |
| Poland       | 7         | 6.54%   |
| Brazil       | 6         | 5.61%   |
| Belgium      | 5         | 4.67%   |
| UK           | 4         | 3.74%   |
| Russia       | 4         | 3.74%   |
| Canada       | 4         | 3.74%   |
| Ukraine      | 3         | 2.8%    |
| Vietnam      | 2         | 1.87%   |
| Turkey       | 2         | 1.87%   |
| Spain        | 2         | 1.87%   |
| Mexico       | 2         | 1.87%   |
| Hungary      | 2         | 1.87%   |
| Costa Rica   | 2         | 1.87%   |
| Argentina    | 2         | 1.87%   |
| Taiwan       | 1         | 0.93%   |
| Sweden       | 1         | 0.93%   |
| South Africa | 1         | 0.93%   |
| Portugal     | 1         | 0.93%   |
| Philippines  | 1         | 0.93%   |
| Netherlands  | 1         | 0.93%   |
| Latvia       | 1         | 0.93%   |
| Kenya        | 1         | 0.93%   |
| Japan        | 1         | 0.93%   |
| Indonesia    | 1         | 0.93%   |
| Greece       | 1         | 0.93%   |
| Finland      | 1         | 0.93%   |
| Ecuador      | 1         | 0.93%   |
| Colombia     | 1         | 0.93%   |
| Chile        | 1         | 0.93%   |
| Belarus      | 1         | 0.93%   |
| Australia    | 1         | 0.93%   |
| Armenia      | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Paris                     | 4         | 3.57%   |
| Ghent                     | 3         | 2.68%   |
| Sarospatak                | 2         | 1.79%   |
| Porto Alegre              | 2         | 1.79%   |
| Milan                     | 2         | 1.79%   |
| Kyiv                      | 2         | 1.79%   |
| Heredia                   | 2         | 1.79%   |
| Zizur Mayor               | 1         | 0.89%   |
| Zawiercie                 | 1         | 0.89%   |
| Yoshkar-Ola               | 1         | 0.89%   |
| Yorkville                 | 1         | 0.89%   |
| Yerevan                   | 1         | 0.89%   |
| Wolfhagen                 | 1         | 0.89%   |
| West Stockbridge          | 1         | 0.89%   |
| Warsaw                    | 1         | 0.89%   |
| Warendorf                 | 1         | 0.89%   |
| Volzhskiy                 | 1         | 0.89%   |
| Verona                    | 1         | 0.89%   |
| Tychy                     | 1         | 0.89%   |
| Thornton Heath            | 1         | 0.89%   |
| Thessaloniki              | 1         | 0.89%   |
| Taipei                    | 1         | 0.89%   |
| Surabaya                  | 1         | 0.89%   |
| Stuttgart                 | 1         | 0.89%   |
| Strzyzow                  | 1         | 0.89%   |
| Stockholm                 | 1         | 0.89%   |
| Southampton               | 1         | 0.89%   |
| South Burlington          | 1         | 0.89%   |
| Sao Paulo                 | 1         | 0.89%   |
| Santiago de Compostela    | 1         | 0.89%   |
| Santiago                  | 1         | 0.89%   |
| Saint-Raymond-de-Portneuf | 1         | 0.89%   |
| Saint-Martin-Lacaussade   | 1         | 0.89%   |
| Roswell                   | 1         | 0.89%   |
| Rossano Veneto            | 1         | 0.89%   |
| Rio de Janeiro            | 1         | 0.89%   |
| Riga                      | 1         | 0.89%   |
| Quito                     | 1         | 0.89%   |
| Quezon City               | 1         | 0.89%   |
| Pretoria                  | 1         | 0.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Unknown                   | 18        | 27     | 15.79%  |
| Seagate                   | 16        | 19     | 14.04%  |
| WDC                       | 13        | 17     | 11.4%   |
| Toshiba                   | 11        | 12     | 9.65%   |
| Samsung Electronics       | 8         | 11     | 7.02%   |
| Hitachi                   | 6         | 8      | 5.26%   |
| Kingston                  | 4         | 4      | 3.51%   |
| SanDisk                   | 3         | 3      | 2.63%   |
| A-DATA Technology         | 3         | 3      | 2.63%   |
| SPCC                      | 2         | 3      | 1.75%   |
| SK hynix                  | 2         | 2      | 1.75%   |
| Micron Technology         | 2         | 2      | 1.75%   |
| HGST                      | 2         | 2      | 1.75%   |
| GOODRAM                   | 2         | 2      | 1.75%   |
| Crucial                   | 2         | 2      | 1.75%   |
| Apacer                    | 2         | 2      | 1.75%   |
| W800S                     | 1         | 1      | 0.88%   |
| UMIS                      | 1         | 1      | 0.88%   |
| Transcend                 | 1         | 1      | 0.88%   |
| Teclast                   | 1         | 1      | 0.88%   |
| Rogueware                 | 1         | 1      | 0.88%   |
| NGFF                      | 1         | 1      | 0.88%   |
| Micron/Crucial Technology | 1         | 1      | 0.88%   |
| Lexar                     | 1         | 1      | 0.88%   |
| Leqixiang                 | 1         | 1      | 0.88%   |
| Lenovo                    | 1         | 1      | 0.88%   |
| KINGPOWER                 | 1         | 1      | 0.88%   |
| Intenso                   | 1         | 1      | 0.88%   |
| Intel                     | 1         | 1      | 0.88%   |
| HUSKY                     | 1         | 1      | 0.88%   |
| Fujitsu                   | 1         | 1      | 0.88%   |
| China                     | 1         | 1      | 0.88%   |
| Apple                     | 1         | 2      | 0.88%   |
| Unknown                   | 1         | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST9500325AS 500GB            | 5         | 4.07%   |
| Unknown SD/MMC/MS PRO 2GB            | 2         | 1.63%   |
| Unknown SC64G  64GB                  | 2         | 1.63%   |
| Unknown NCard  32GB                  | 2         | 1.63%   |
| Unknown MMC64G  64GB                 | 2         | 1.63%   |
| Unknown MMC Card  64GB               | 2         | 1.63%   |
| Unknown MMC Card  32GB               | 2         | 1.63%   |
| Unknown DA4032  32GB                 | 2         | 1.63%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.63%   |
| Toshiba MQ01ABD050 500GB             | 2         | 1.63%   |
| SPCC Solid State Disk 120GB          | 2         | 1.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.63%   |
| SanDisk DF4032  32GB                 | 2         | 1.63%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 1.63%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.81%   |
| WDC WDS500G2B0A 500GB SSD            | 1         | 0.81%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.81%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.81%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.81%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.81%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.81%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.81%   |
| WDC WD2500BEVS-22UST0 250GB          | 1         | 0.81%   |
| WDC WD10SPZX-24Z10T0 1TB             | 1         | 0.81%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.81%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.81%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.81%   |
| WDC PC SN730 SDBQNTY-256G-1006 256GB | 1         | 0.81%   |
| W800S 256GB SSD                      | 1         | 0.81%   |
| Unknown SF64G  64GB                  | 1         | 0.81%   |
| Unknown MMC Card  16GB               | 1         | 0.81%   |
| Unknown ISOCOM  64GB                 | 1         | 0.81%   |
| Unknown HAG4a2  16GB                 | 1         | 0.81%   |
| Unknown ED2S5  128GB                 | 1         | 0.81%   |
| Unknown DA4064  64GB                 | 1         | 0.81%   |
| Unknown CGND3R  64GB                 | 1         | 0.81%   |
| Unknown BJNB4R  32GB                 | 1         | 0.81%   |
| Unknown ASTC  8GB                    | 1         | 0.81%   |
| Unknown ASTC  32GB                   | 1         | 0.81%   |
| UMIS RPFTJ256PDD2MWX 256GB           | 1         | 0.81%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 19     | 34.04%  |
| WDC                 | 10        | 11     | 21.28%  |
| Toshiba             | 9         | 10     | 19.15%  |
| Hitachi             | 6         | 8      | 12.77%  |
| Unknown             | 2         | 2      | 4.26%   |
| HGST                | 2         | 2      | 4.26%   |
| Samsung Electronics | 1         | 4      | 2.13%   |
| Fujitsu             | 1         | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 13.89%  |
| Kingston            | 3         | 3      | 8.33%   |
| A-DATA Technology   | 3         | 3      | 8.33%   |
| WDC                 | 2         | 3      | 5.56%   |
| Toshiba             | 2         | 2      | 5.56%   |
| SPCC                | 2         | 3      | 5.56%   |
| GOODRAM             | 2         | 2      | 5.56%   |
| Crucial             | 2         | 2      | 5.56%   |
| Apacer              | 2         | 2      | 5.56%   |
| W800S               | 1         | 1      | 2.78%   |
| Transcend           | 1         | 1      | 2.78%   |
| Teclast             | 1         | 1      | 2.78%   |
| SanDisk             | 1         | 1      | 2.78%   |
| Rogueware           | 1         | 1      | 2.78%   |
| NGFF                | 1         | 1      | 2.78%   |
| Micron Technology   | 1         | 1      | 2.78%   |
| Lexar               | 1         | 1      | 2.78%   |
| Leqixiang           | 1         | 1      | 2.78%   |
| Lenovo              | 1         | 1      | 2.78%   |
| KINGPOWER           | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| HUSKY               | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 47        | 57     | 40.52%  |
| SSD     | 36        | 38     | 31.03%  |
| MMC     | 20        | 28     | 17.24%  |
| NVMe    | 11        | 13     | 9.48%   |
| Unknown | 2         | 2      | 1.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 79        | 92     | 68.7%   |
| MMC  | 20        | 28     | 17.39%  |
| NVMe | 11        | 13     | 9.57%   |
| SAS  | 5         | 5      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 63        | 73     | 76.83%  |
| 0.51-1.0   | 18        | 21     | 21.95%  |
| 4.01-10.0  | 1         | 1      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 36        | 32.73%  |
| 251-500        | 32        | 29.09%  |
| 1-20           | 12        | 10.91%  |
| 501-1000       | 10        | 9.09%   |
| 51-100         | 10        | 9.09%   |
| 21-50          | 7         | 6.36%   |
| More than 3000 | 1         | 0.91%   |
| 2001-3000      | 1         | 0.91%   |
| Unknown        | 1         | 0.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 63        | 56.76%  |
| 21-50          | 22        | 19.82%  |
| 51-100         | 10        | 9.01%   |
| 101-250        | 8         | 7.21%   |
| 251-500        | 4         | 3.6%    |
| More than 3000 | 1         | 0.9%    |
| 1001-2000      | 1         | 0.9%    |
| 501-1000       | 1         | 0.9%    |
| Unknown        | 1         | 0.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 2         | 2      | 10.53%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 10.53%  |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 5.26%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 5.26%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD050 500GB           | 1         | 1      | 5.26%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 5.26%   |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 5.26%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 5.26%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 5.26%   |
| Seagate ST1000DM003-1SB102 1TB     | 1         | 1      | 5.26%   |
| Samsung Electronics HM121HI 120GB  | 1         | 4      | 5.26%   |
| NGFF 2280 512GB SSD                | 1         | 1      | 5.26%   |
| Hitachi HTS722080K9SA00 80GB       | 1         | 1      | 5.26%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 5.26%   |
| Fujitsu MHY2120BH 120GB            | 1         | 1      | 5.26%   |
| Apacer 16GB SATA Flash Drive SSD   | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 47.37%  |
| WDC                 | 2         | 2      | 10.53%  |
| Toshiba             | 2         | 2      | 10.53%  |
| Hitachi             | 2         | 2      | 10.53%  |
| Samsung Electronics | 1         | 4      | 5.26%   |
| NGFF                | 1         | 1      | 5.26%   |
| Fujitsu             | 1         | 1      | 5.26%   |
| Apacer              | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 52.94%  |
| WDC                 | 2         | 2      | 11.76%  |
| Toshiba             | 2         | 2      | 11.76%  |
| Hitachi             | 2         | 2      | 11.76%  |
| Samsung Electronics | 1         | 4      | 5.88%   |
| Fujitsu             | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 20     | 89.47%  |
| SSD  | 2         | 2      | 10.53%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 62        | 82     | 55.36%  |
| Works    | 31        | 34     | 27.68%  |
| Malfunc  | 19        | 22     | 16.96%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 78        | 75.73%  |
| AMD                              | 11        | 10.68%  |
| SK hynix                         | 2         | 1.94%   |
| SanDisk                          | 2         | 1.94%   |
| Samsung Electronics              | 2         | 1.94%   |
| Nvidia                           | 2         | 1.94%   |
| Union Memory (Shenzhen)          | 1         | 0.97%   |
| Silicon Integrated Systems [SiS] | 1         | 0.97%   |
| Silicon Image                    | 1         | 0.97%   |
| Micron/Crucial Technology        | 1         | 0.97%   |
| Micron Technology                | 1         | 0.97%   |
| Kingston Technology Company      | 1         | 0.97%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 9.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 6.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 6.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 6.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 5.17%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 5.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 3.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 3.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 2.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 2.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 2.59%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.72%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.72%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.72%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 1.72%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.72%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 1.72%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.86%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.86%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.86%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.86%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.86%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 0.86%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.86%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.86%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.86%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 1         | 0.86%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.86%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.86%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 0.86%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 82        | 73.87%  |
| IDE  | 14        | 12.61%  |
| NVMe | 10        | 9.01%   |
| RAID | 5         | 4.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 96        | 89.72%  |
| AMD    | 11        | 10.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 3.74%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 2.8%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 2.8%    |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 3         | 2.8%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 1.87%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.87%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.87%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.87%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.87%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 1.87%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.87%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 1.87%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.87%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 1.87%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.87%   |
| AMD E-450 APU with Radeon HD Graphics         | 2         | 1.87%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 1.87%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.93%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.93%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.93%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.93%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.93%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.93%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 0.93%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 0.93%   |
| Intel Core i7-2635QM CPU @ 2.00GHz            | 1         | 0.93%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 1         | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 0.93%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 0.93%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 0.93%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 0.93%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Celeron      | 22        | 20.56%  |
| Intel Core i5      | 21        | 19.63%  |
| Intel Core 2 Duo   | 14        | 13.08%  |
| Intel Core i3      | 12        | 11.21%  |
| Intel Core i7      | 11        | 10.28%  |
| Intel Atom         | 8         | 7.48%   |
| Intel Pentium      | 5         | 4.67%   |
| AMD A6             | 3         | 2.8%    |
| Intel Core 2       | 2         | 1.87%   |
| AMD E1             | 2         | 1.87%   |
| AMD E              | 2         | 1.87%   |
| Intel Pentium Dual | 1         | 0.93%   |
| AMD Ryzen 7 PRO    | 1         | 0.93%   |
| AMD Ryzen 5        | 1         | 0.93%   |
| AMD C-60           | 1         | 0.93%   |
| AMD A8             | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 77        | 71.96%  |
| 4      | 25        | 23.36%  |
| 1      | 3         | 2.8%    |
| 8      | 1         | 0.93%   |
| 6      | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 107       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 58        | 54.21%  |
| 2      | 49        | 45.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 107       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 36.11%  |
| 0x206a7    | 8         | 7.41%   |
| 0x306a9    | 6         | 5.56%   |
| 0x6fd      | 4         | 3.7%    |
| 0x406c4    | 4         | 3.7%    |
| 0x406c3    | 4         | 3.7%    |
| 0x40651    | 3         | 2.78%   |
| 0x20655    | 3         | 2.78%   |
| 0x1067a    | 3         | 2.78%   |
| 0x05000119 | 3         | 2.78%   |
| 0x906c0    | 2         | 1.85%   |
| 0x806ec    | 2         | 1.85%   |
| 0x806ea    | 2         | 1.85%   |
| 0x706e5    | 2         | 1.85%   |
| 0x706a8    | 2         | 1.85%   |
| 0x30678    | 2         | 1.85%   |
| 0x0a50000c | 2         | 1.85%   |
| 0x06006705 | 2         | 1.85%   |
| 0x906ed    | 1         | 0.93%   |
| 0x806eb    | 1         | 0.93%   |
| 0x806e9    | 1         | 0.93%   |
| 0x706a1    | 1         | 0.93%   |
| 0x6fa      | 1         | 0.93%   |
| 0x6f6      | 1         | 0.93%   |
| 0x506e3    | 1         | 0.93%   |
| 0x506c9    | 1         | 0.93%   |
| 0x406e3    | 1         | 0.93%   |
| 0x306c3    | 1         | 0.93%   |
| 0x106ca    | 1         | 0.93%   |
| 0x10676    | 1         | 0.93%   |
| 0x0700010f | 1         | 0.93%   |
| 0x06001119 | 1         | 0.93%   |
| 0x06001116 | 1         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 19        | 17.76%  |
| SandyBridge   | 14        | 13.08%  |
| Penryn        | 9         | 8.41%   |
| KabyLake      | 8         | 7.48%   |
| IvyBridge     | 8         | 7.48%   |
| Core          | 8         | 7.48%   |
| Haswell       | 7         | 6.54%   |
| Goldmont plus | 6         | 5.61%   |
| Westmere      | 5         | 4.67%   |
| Bobcat        | 3         | 2.8%    |
| Zen 3         | 2         | 1.87%   |
| Tremont       | 2         | 1.87%   |
| Skylake       | 2         | 1.87%   |
| Piledriver    | 2         | 1.87%   |
| IceLake       | 2         | 1.87%   |
| Goldmont      | 2         | 1.87%   |
| Excavator     | 2         | 1.87%   |
| Broadwell     | 2         | 1.87%   |
| Bonnell       | 2         | 1.87%   |
| Puma          | 1         | 0.93%   |
| Jaguar        | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 87        | 74.36%  |
| AMD    | 18        | 15.38%  |
| Nvidia | 12        | 10.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 10.94%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 9.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 6.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 5.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 5.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 5.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 4.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 4.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.13%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 2.34%   |
| Nvidia G96CM [GeForce GT 120M]                                                           | 2         | 1.56%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.56%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.56%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.56%   |
| Intel HD Graphics 500                                                                    | 2         | 1.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.56%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 1.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.56%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.56%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.78%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.78%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.78%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 0.78%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.78%   |
| Nvidia GF119M [GeForce GT 520MX]                                                         | 1         | 0.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.78%   |
| Nvidia G86M [GeForce 9300M G]                                                            | 1         | 0.78%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 0.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 0.78%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.78%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.78%   |
| Intel HD Graphics 630                                                                    | 1         | 0.78%   |
| Intel HD Graphics 620                                                                    | 1         | 0.78%   |
| Intel HD Graphics 530                                                                    | 1         | 0.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 75        | 70.09%  |
| 1 x AMD        | 10        | 9.35%   |
| 1 x Nvidia     | 8         | 7.48%   |
| Intel + AMD    | 5         | 4.67%   |
| Intel + Nvidia | 4         | 3.74%   |
| 2 x AMD        | 3         | 2.8%    |
| Other          | 2         | 1.87%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 104       | 97.2%   |
| Proprietary | 2         | 1.87%   |
| Unknown     | 1         | 0.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 83.33%  |
| 0.01-0.5   | 8         | 7.41%   |
| 1.01-2.0   | 5         | 4.63%   |
| 0.51-1.0   | 2         | 1.85%   |
| 5.01-6.0   | 1         | 0.93%   |
| 3.01-4.0   | 1         | 0.93%   |
| 2.01-3.0   | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 21        | 19.27%  |
| AU Optronics            | 21        | 19.27%  |
| Chimei Innolux          | 15        | 13.76%  |
| BOE                     | 11        | 10.09%  |
| Samsung Electronics     | 10        | 9.17%   |
| Apple                   | 6         | 5.5%    |
| CPT                     | 5         | 4.59%   |
| Lenovo                  | 3         | 2.75%   |
| Chi Mei Optoelectronics | 3         | 2.75%   |
| LG Philips              | 2         | 1.83%   |
| Goldstar                | 2         | 1.83%   |
| ViewSonic               | 1         | 0.92%   |
| Toshiba                 | 1         | 0.92%   |
| Sharp                   | 1         | 0.92%   |
| JVC                     | 1         | 0.92%   |
| JDI                     | 1         | 0.92%   |
| Hewlett-Packard         | 1         | 0.92%   |
| CS_                     | 1         | 0.92%   |
| BenQ                    | 1         | 0.92%   |
| AOC                     | 1         | 0.92%   |
| Acer                    | 1         | 0.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 4         | 3.67%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.83%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 2         | 1.83%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.83%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 1.83%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 1.83%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 1.83%   |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch         | 1         | 0.92%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch              | 1         | 0.92%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 0.92%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.92%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch  | 1         | 0.92%   |
| LG Philips LCD Monitor LPLEC00 1280x800 331x207mm 15.4-inch           | 1         | 0.92%   |
| LG Philips LCD Monitor LPL1101 1280x800 304x190mm 14.1-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0680 1920x1080 344x194mm 15.5-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0469 1920x1080 380x210mm 17.1-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x174mm 14.0-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD03E9 1366x768 345x194mm 15.6-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 52        | 48.6%   |
| 1920x1080 (FHD)    | 20        | 18.69%  |
| 1280x800 (WXGA)    | 15        | 14.02%  |
| 1600x900 (HD+)     | 7         | 6.54%   |
| 2560x1440 (QHD)    | 3         | 2.8%    |
| 1440x900 (WXGA+)   | 2         | 1.87%   |
| 3840x2160 (4K)     | 1         | 0.93%   |
| 3200x1800 (QHD+)   | 1         | 0.93%   |
| 3000x2000          | 1         | 0.93%   |
| 2560x1080          | 1         | 0.93%   |
| 2160x1440          | 1         | 0.93%   |
| 1680x1050 (WSXGA+) | 1         | 0.93%   |
| 1528x1222          | 1         | 0.93%   |
| 1360x768           | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 35        | 32.11%  |
| 14      | 20        | 18.35%  |
| 13      | 17        | 15.6%   |
| 11      | 11        | 10.09%  |
| 17      | 7         | 6.42%   |
| 12      | 3         | 2.75%   |
| 24      | 2         | 1.83%   |
| 23      | 2         | 1.83%   |
| 21      | 2         | 1.83%   |
| 19      | 2         | 1.83%   |
| 10      | 2         | 1.83%   |
| 28      | 1         | 0.92%   |
| 27      | 1         | 0.92%   |
| 18      | 1         | 0.92%   |
| 16      | 1         | 0.92%   |
| 9       | 1         | 0.92%   |
| Unknown | 1         | 0.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 62        | 56.88%  |
| 201-300     | 26        | 23.85%  |
| 351-400     | 8         | 7.34%   |
| 401-500     | 5         | 4.59%   |
| 501-600     | 4         | 3.67%   |
| 601-700     | 2         | 1.83%   |
| 101-200     | 1         | 0.92%   |
| Unknown     | 1         | 0.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 78        | 76.47%  |
| 16/10 | 20        | 19.61%  |
| 3/2   | 2         | 1.96%   |
| 4/3   | 1         | 0.98%   |
| 21/9  | 1         | 0.98%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 32.11%  |
| 81-90          | 34        | 31.19%  |
| 51-60          | 11        | 10.09%  |
| 121-130        | 7         | 6.42%   |
| 201-250        | 5         | 4.59%   |
| 71-80          | 3         | 2.75%   |
| 61-70          | 3         | 2.75%   |
| 41-50          | 3         | 2.75%   |
| 251-300        | 2         | 1.83%   |
| 151-200        | 2         | 1.83%   |
| 301-350        | 1         | 0.92%   |
| 141-150        | 1         | 0.92%   |
| 131-140        | 1         | 0.92%   |
| Unknown        | 1         | 0.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 52        | 48.15%  |
| 121-160       | 32        | 29.63%  |
| 51-100        | 16        | 14.81%  |
| 161-240       | 5         | 4.63%   |
| More than 240 | 2         | 1.85%   |
| Unknown       | 1         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 97        | 90.65%  |
| 2     | 8         | 7.48%   |
| 3     | 1         | 0.93%   |
| 0     | 1         | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 50        | 31.06%  |
| Intel                           | 44        | 27.33%  |
| Qualcomm Atheros                | 28        | 17.39%  |
| Broadcom                        | 12        | 7.45%   |
| Marvell Technology Group        | 5         | 3.11%   |
| Samsung Electronics             | 3         | 1.86%   |
| Broadcom Limited                | 3         | 1.86%   |
| TP-Link                         | 2         | 1.24%   |
| Qualcomm Atheros Communications | 2         | 1.24%   |
| Qualcomm                        | 2         | 1.24%   |
| ASIX Electronics                | 2         | 1.24%   |
| Sierra Wireless                 | 1         | 0.62%   |
| Ralink Technology               | 1         | 0.62%   |
| Ralink                          | 1         | 0.62%   |
| Nvidia                          | 1         | 0.62%   |
| NetGear                         | 1         | 0.62%   |
| Microsoft                       | 1         | 0.62%   |
| JMicron Technology              | 1         | 0.62%   |
| ICS Advent                      | 1         | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 12.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 4.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 3.06%   |
| Intel Wireless 7265                                               | 6         | 3.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 2.55%   |
| Intel Wireless 7260                                               | 5         | 2.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.53%   |
| Realtek 802.11n WLAN Adapter                                      | 3         | 1.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 1.53%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 1.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 1.53%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 1.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.02%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.02%   |
| Intel Wireless 3160                                               | 2         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.02%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 1.02%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.02%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.02%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 1.02%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.02%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.02%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.51%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.51%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 39.62%  |
| Qualcomm Atheros                | 27        | 25.47%  |
| Realtek Semiconductor           | 21        | 19.81%  |
| Broadcom                        | 7         | 6.6%    |
| Qualcomm Atheros Communications | 2         | 1.89%   |
| TP-Link                         | 1         | 0.94%   |
| Sierra Wireless                 | 1         | 0.94%   |
| Ralink Technology               | 1         | 0.94%   |
| Ralink                          | 1         | 0.94%   |
| NetGear                         | 1         | 0.94%   |
| Microsoft                       | 1         | 0.94%   |
| Broadcom Limited                | 1         | 0.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 5.66%   |
| Intel Wireless 7265                                                     | 6         | 5.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 4.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 4.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 4.72%   |
| Intel Wireless 7260                                                     | 5         | 4.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 3.77%   |
| Realtek 802.11n WLAN Adapter                                            | 3         | 2.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 2.83%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 2.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.83%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 2.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 2.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.89%   |
| Intel Wireless 3160                                                     | 2         | 1.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.89%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.89%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.89%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.89%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.94%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.94%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.94%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.94%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.94%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.94%   |
| Realtek Realtek Network controller                                      | 1         | 0.94%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 0.94%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.94%   |
| Qualcomm Atheros UB94                                                   | 1         | 0.94%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.94%   |
| NetGear A6210                                                           | 1         | 0.94%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 39        | 43.82%  |
| Intel                    | 16        | 17.98%  |
| Qualcomm Atheros         | 8         | 8.99%   |
| Broadcom                 | 8         | 8.99%   |
| Marvell Technology Group | 5         | 5.62%   |
| Samsung Electronics      | 3         | 3.37%   |
| Qualcomm                 | 2         | 2.25%   |
| Broadcom Limited         | 2         | 2.25%   |
| ASIX Electronics         | 2         | 2.25%   |
| TP-Link                  | 1         | 1.12%   |
| Nvidia                   | 1         | 1.12%   |
| JMicron Technology       | 1         | 1.12%   |
| ICS Advent               | 1         | 1.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 25        | 27.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 8.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 3.33%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 3         | 3.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 3.33%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 2.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 2.22%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 2.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 2.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 2.22%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 2.22%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 2.22%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 2.22%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.11%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.11%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.11%   |
| Realtek RTL8150 Fast Ethernet Adapter                                          | 1         | 1.11%   |
| Qualcomm FP3                                                                   | 1         | 1.11%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.11%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.11%   |
| Qualcomm Android                                                               | 1         | 1.11%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 1.11%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.11%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.11%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 1.11%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.11%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.11%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.11%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.11%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 1.11%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 1.11%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 1.11%   |
| Broadcom NetXtreme BCM5756ME Gigabit Ethernet PCI Express                      | 1         | 1.11%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 1.11%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.11%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 1.11%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 99        | 54.7%   |
| Ethernet | 82        | 45.3%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 70.75%  |
| Ethernet | 31        | 29.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 71        | 66.36%  |
| 1     | 24        | 22.43%  |
| 0     | 11        | 10.28%  |
| 3     | 1         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 88        | 81.48%  |
| Yes  | 20        | 18.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 36.62%  |
| Realtek Semiconductor           | 13        | 18.31%  |
| Qualcomm Atheros Communications | 9         | 12.68%  |
| Broadcom                        | 4         | 5.63%   |
| Apple                           | 4         | 5.63%   |
| Dell                            | 3         | 4.23%   |
| Lite-On Technology              | 2         | 2.82%   |
| IMC Networks                    | 2         | 2.82%   |
| Foxconn / Hon Hai               | 2         | 2.82%   |
| Toshiba                         | 1         | 1.41%   |
| Syntek                          | 1         | 1.41%   |
| Hewlett-Packard                 | 1         | 1.41%   |
| Cambridge Silicon Radio         | 1         | 1.41%   |
| ASUSTek Computer                | 1         | 1.41%   |
| Alps Electric                   | 1         | 1.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 16        | 22.54%  |
| Realtek Bluetooth Radio                                                             | 9         | 12.68%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 5.63%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 5.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 5.63%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 4.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 4.23%   |
| Apple Bluetooth Host Controller                                                     | 3         | 4.23%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 2.82%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 1.41%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 1.41%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.41%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 1.41%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.41%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.41%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.41%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.41%   |
| Intel Bluetooth Device                                                              | 1         | 1.41%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.41%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 1.41%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.41%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.41%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.41%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 1.41%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 1.41%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.41%   |
| Broadcom HP Portable Valentine                                                      | 1         | 1.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.41%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 1.41%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.41%   |
| Alps Electric Bluetooth Adapter                                                     | 1         | 1.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 86        | 79.63%  |
| AMD                  | 13        | 12.04%  |
| Nvidia               | 6         | 5.56%   |
| MosArt Semiconductor | 1         | 0.93%   |
| JMTek                | 1         | 0.93%   |
| EGO SYStems          | 1         | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 10.24%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 7.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 6.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 6.3%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 4.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 4.72%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 4.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 3.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 3.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 3.15%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 3.15%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.57%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1.57%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.57%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.57%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.57%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.57%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.57%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.57%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 1.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.57%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.79%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.79%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.79%   |
| MosArt Semiconductor MosArt USB Audio Device                                                      | 1         | 0.79%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 21        | 25.93%  |
| SK hynix            | 15        | 18.52%  |
| Micron Technology   | 11        | 13.58%  |
| Unknown             | 10        | 12.35%  |
| Nanya Technology    | 4         | 4.94%   |
| Kingston            | 3         | 3.7%    |
| Elpida              | 3         | 3.7%    |
| Unknown (ABCD)      | 2         | 2.47%   |
| Smart               | 2         | 2.47%   |
| Corsair             | 2         | 2.47%   |
| Transcend           | 1         | 1.23%   |
| Ramaxel Technology  | 1         | 1.23%   |
| Novatech            | 1         | 1.23%   |
| Kllisre             | 1         | 1.23%   |
| HMD                 | 1         | 1.23%   |
| AMD                 | 1         | 1.23%   |
| A-DATA Technology   | 1         | 1.23%   |
| Unknown             | 1         | 1.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 2.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 2         | 2.3%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 2.3%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 2.3%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.3%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 2.3%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 2.3%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.3%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.3%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.3%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 2.3%    |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 2.3%    |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.15%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.15%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 1.15%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1.15%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s                | 1         | 1.15%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 1.15%   |
| SK hynix RAM HT5SMRAP 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.15%   |
| SK hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.15%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1333MT/s           | 1         | 1.15%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.15%   |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s              | 1         | 1.15%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                     | 1         | 1.15%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.15%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.15%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.15%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.15%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.15%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 39        | 54.93%  |
| DDR4   | 16        | 22.54%  |
| DDR2   | 6         | 8.45%   |
| LPDDR4 | 5         | 7.04%   |
| SDRAM  | 3         | 4.23%   |
| LPDDR3 | 2         | 2.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 63        | 88.73%  |
| Row Of Chips | 5         | 7.04%   |
| Unknown      | 3         | 4.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 27        | 32.93%  |
| 4096  | 26        | 31.71%  |
| 8192  | 18        | 21.95%  |
| 1024  | 6         | 7.32%   |
| 16384 | 3         | 3.66%   |
| 32768 | 1         | 1.22%   |
| 512   | 1         | 1.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 24        | 32%     |
| 3200    | 7         | 9.33%   |
| 1333    | 7         | 9.33%   |
| 2667    | 6         | 8%      |
| 1334    | 5         | 6.67%   |
| 667     | 5         | 6.67%   |
| 2400    | 3         | 4%      |
| 1066    | 3         | 4%      |
| 3266    | 2         | 2.67%   |
| 1866    | 2         | 2.67%   |
| 1067    | 2         | 2.67%   |
| 975     | 2         | 2.67%   |
| Unknown | 2         | 2.67%   |
| 4199    | 1         | 1.33%   |
| 3733    | 1         | 1.33%   |
| 2133    | 1         | 1.33%   |
| 2048    | 1         | 1.33%   |
| 1867    | 1         | 1.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| HP LaserJet P1102 | 1         | 50%     |
| Canon MF3110      | 1         | 50%     |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 28.09%  |
| Microdia                               | 10        | 11.24%  |
| Sunplus Innovation Technology          | 8         | 8.99%   |
| Realtek Semiconductor                  | 8         | 8.99%   |
| Syntek                                 | 5         | 5.62%   |
| IMC Networks                           | 4         | 4.49%   |
| Apple                                  | 4         | 4.49%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.37%   |
| Alcor Micro                            | 3         | 3.37%   |
| Suyin                                  | 2         | 2.25%   |
| Silicon Motion                         | 2         | 2.25%   |
| Quanta                                 | 2         | 2.25%   |
| Lenovo                                 | 2         | 2.25%   |
| ALi                                    | 2         | 2.25%   |
| Acer                                   | 2         | 2.25%   |
| Y Media                                | 1         | 1.12%   |
| USB Camera CS                          | 1         | 1.12%   |
| SunplusIT                              | 1         | 1.12%   |
| Ricoh                                  | 1         | 1.12%   |
| Logitech                               | 1         | 1.12%   |
| Lite-On Technology                     | 1         | 1.12%   |
| Cubeternet                             | 1         | 1.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 7         | 7.78%   |
| Sunplus HD WebCam                                   | 3         | 3.33%   |
| Chicony HD WebCam                                   | 3         | 3.33%   |
| Realtek Lenovo EasyCamera                           | 2         | 2.22%   |
| Realtek Integrated_Webcam_HD                        | 2         | 2.22%   |
| Realtek Integrated Webcam HD                        | 2         | 2.22%   |
| Microdia Lenovo EasyCamera                          | 2         | 2.22%   |
| Microdia Integrated Webcam                          | 2         | 2.22%   |
| Microdia HP Webcam-50                               | 2         | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 2.22%   |
| Chicony FJ Camera                                   | 2         | 2.22%   |
| Chicony EasyCamera                                  | 2         | 2.22%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 2         | 2.22%   |
| Apple FaceTime HD Camera                            | 2         | 2.22%   |
| ALi WebCam                                          | 2         | 2.22%   |
| Alcor Micro HD Webcam                               | 2         | 2.22%   |
| Y Media USB Camera                                  | 1         | 1.11%   |
| USB Camera CS USB Camera CS                         | 1         | 1.11%   |
| Syntek USB2.0 Camera                                | 1         | 1.11%   |
| Syntek USB Camera Device                            | 1         | 1.11%   |
| Syntek Sonix USB 2.0 Camera                         | 1         | 1.11%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.11%   |
| Syntek HD WebCam                                    | 1         | 1.11%   |
| Suyin Intel Webcam                                  | 1         | 1.11%   |
| Suyin 1.3M HD WebCam                                | 1         | 1.11%   |
| SunplusIT USB 2.0 Camera                            | 1         | 1.11%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 1.11%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.11%   |
| Sunplus HD User Facing                              | 1         | 1.11%   |
| Sunplus Dell Integrated HD Webcam                   | 1         | 1.11%   |
| Sunplus Asus Webcam                                 | 1         | 1.11%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 1.11%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 1.11%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 1.11%   |
| Realtek USB Camera                                  | 1         | 1.11%   |
| Realtek EasyCamera                                  | 1         | 1.11%   |
| Quanta HP Webcam                                    | 1         | 1.11%   |
| Quanta Chromebook HD Camera                         | 1         | 1.11%   |
| Microdia Webcam Vitade AF                           | 1         | 1.11%   |
| Microdia Webcam                                     | 1         | 1.11%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 31.25%  |
| Upek                  | 4         | 25%     |
| AuthenTec             | 4         | 25%     |
| STMicroelectronics    | 2         | 12.5%   |
| LighTuning Technology | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 25%     |
| STMicroelectronics Fingerprint Reader                  | 2         | 12.5%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 6.25%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 6.25%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 6.25%   |
| AuthenTec Fingerprint Sensor                           | 1         | 6.25%   |
| AuthenTec AES2810                                      | 1         | 6.25%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 6.25%   |
| AuthenTec AES1600                                      | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 71.43%  |
| O2 Micro    | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 42.86%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 28.57%  |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 77        | 71.96%  |
| 1     | 27        | 25.23%  |
| 2     | 3         | 2.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 16        | 48.48%  |
| Chipcard           | 7         | 21.21%  |
| Graphics card      | 3         | 9.09%   |
| Camera             | 3         | 9.09%   |
| Storage            | 1         | 3.03%   |
| Network            | 1         | 3.03%   |
| Dvb card           | 1         | 3.03%   |
| Bluetooth          | 1         | 3.03%   |

