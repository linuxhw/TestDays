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

Total: 121

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.15.0-43-generic     | 16        | 15.84%  |
| 5.15.0-30-generic     | 8         | 7.92%   |
| 5.15.0-56-generic     | 7         | 6.93%   |
| 5.15.0-46-generic     | 7         | 6.93%   |
| 5.15.0-25-generic     | 7         | 6.93%   |
| 5.15.0-52-generic     | 6         | 5.94%   |
| 5.15.0-47-generic     | 6         | 5.94%   |
| 5.15.0-27-generic     | 6         | 5.94%   |
| 5.15.0-53-generic     | 5         | 4.95%   |
| 5.15.0-50-generic     | 4         | 3.96%   |
| 5.15.0-41-generic     | 4         | 3.96%   |
| 5.15.0-48-generic     | 3         | 2.97%   |
| 5.15.0-40-generic     | 3         | 2.97%   |
| 5.15.0-35-generic     | 3         | 2.97%   |
| 5.15.0-57-generic     | 2         | 1.98%   |
| 5.15.0-37-generic     | 2         | 1.98%   |
| 5.15.0-33-generic     | 2         | 1.98%   |
| 6.0.12-x64v2-xanmod1  | 1         | 0.99%   |
| 5.19.8-xanmod1        | 1         | 0.99%   |
| 5.19.0-051900-generic | 1         | 0.99%   |
| 5.18.0-051800-generic | 1         | 0.99%   |
| 5.15.0-54-generic     | 1         | 0.99%   |
| 5.15.0-39-generic     | 1         | 0.99%   |
| 5.15.0-28-generic     | 1         | 0.99%   |
| 5.15.0-23-generic     | 1         | 0.99%   |
| 5.15.0-18-generic     | 1         | 0.99%   |
| 5.14.0-1040-oem       | 1         | 0.99%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 90        | 94.74%  |
| 6.0.12  | 1         | 1.05%   |
| 5.19.8  | 1         | 1.05%   |
| 5.19.0  | 1         | 1.05%   |
| 5.18.0  | 1         | 1.05%   |
| 5.14.0  | 1         | 1.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 90        | 94.74%  |
| 5.19    | 2         | 2.11%   |
| 6.0     | 1         | 1.05%   |
| 5.18    | 1         | 1.05%   |
| 5.14    | 1         | 1.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 92        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXQt       | 90        | 97.83%  |
| X-Cinnamon | 2         | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 90        | 97.83%  |
| Tty  | 2         | 2.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 82        | 88.17%  |
| Unknown | 6         | 6.45%   |
| LightDM | 4         | 4.3%    |
| GDM3    | 1         | 1.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 24        | 25.81%  |
| it_IT | 8         | 8.6%    |
| pt_BR | 6         | 6.45%   |
| pl_PL | 6         | 6.45%   |
| fr_FR | 6         | 6.45%   |
| C     | 6         | 6.45%   |
| en_GB | 5         | 5.38%   |
| de_DE | 4         | 4.3%    |
| en_AG | 3         | 3.23%   |
| ru_RU | 2         | 2.15%   |
| nl_BE | 2         | 2.15%   |
| es_MX | 2         | 2.15%   |
| es_CR | 2         | 2.15%   |
| es_AR | 2         | 2.15%   |
| en_CA | 2         | 2.15%   |
| tr_TR | 1         | 1.08%   |
| ja_JP | 1         | 1.08%   |
| fr_CA | 1         | 1.08%   |
| fi_FI | 1         | 1.08%   |
| es_ES | 1         | 1.08%   |
| es_CO | 1         | 1.08%   |
| es_CL | 1         | 1.08%   |
| en_ZA | 1         | 1.08%   |
| en_PH | 1         | 1.08%   |
| en_DE | 1         | 1.08%   |
| en_AU | 1         | 1.08%   |
| el_GR | 1         | 1.08%   |
| aa_DJ | 1         | 1.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 57        | 61.29%  |
| EFI  | 36        | 38.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 83        | 89.25%  |
| Overlay | 7         | 7.53%   |
| Btrfs   | 2         | 2.15%   |
| Ext2    | 1         | 1.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 44        | 46.32%  |
| Unknown | 27        | 28.42%  |
| MBR     | 24        | 25.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 83        | 89.25%  |
| Yes       | 10        | 10.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75        | 80.65%  |
| Yes       | 18        | 19.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 17        | 18.48%  |
| Hewlett-Packard     | 12        | 13.04%  |
| Dell                | 12        | 13.04%  |
| Acer                | 7         | 7.61%   |
| Google              | 6         | 6.52%   |
| ASUSTek Computer    | 5         | 5.43%   |
| Apple               | 5         | 5.43%   |
| Fujitsu             | 4         | 4.35%   |
| Sony                | 3         | 3.26%   |
| Unknown             | 3         | 3.26%   |
| Toshiba             | 2         | 2.17%   |
| Mediacom            | 2         | 2.17%   |
| Gateway             | 2         | 2.17%   |
| SGIN                | 1         | 1.09%   |
| Samsung Electronics | 1         | 1.09%   |
| Pretech             | 1         | 1.09%   |
| Prestigio           | 1         | 1.09%   |
| Positivo            | 1         | 1.09%   |
| Packard Bell        | 1         | 1.09%   |
| OEM                 | 1         | 1.09%   |
| Kiano               | 1         | 1.09%   |
| Intel               | 1         | 1.09%   |
| IFSA                | 1         | 1.09%   |
| GPU Company         | 1         | 1.09%   |
| Chuwi               | 1         | 1.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 4         | 4.35%   |
| Apple MacBookPro8,1                        | 3         | 3.26%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 2         | 2.17%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 2.17%   |
| HP Pavilion g6                             | 2         | 2.17%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 2.17%   |
| Toshiba Satellite Pro S500                 | 1         | 1.09%   |
| Toshiba Satellite L40                      | 1         | 1.09%   |
| Sony VPCEB15FM                             | 1         | 1.09%   |
| Sony VGN-SZ71WN_C                          | 1         | 1.09%   |
| Sony SVE14A2V1EW                           | 1         | 1.09%   |
| SGIN laptop                                | 1         | 1.09%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 1.09%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 1.09%   |
| Prestigio PSB141C01BFH                     | 1         | 1.09%   |
| Positivo i500pro                           | 1         | 1.09%   |
| Packard Bell EasyNote TS44HR               | 1         | 1.09%   |
| Lenovo Z70-80 80FG                         | 1         | 1.09%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0WE02   | 1         | 1.09%   |
| Lenovo ThinkPad T430 2342A19               | 1         | 1.09%   |
| Lenovo ThinkPad T410 2537CS0               | 1         | 1.09%   |
| Lenovo ThinkPad SL510 2847CXG              | 1         | 1.09%   |
| Lenovo ThinkPad E550 20DF00CUFR            | 1         | 1.09%   |
| Lenovo IdeaPad S145-15IGM 81MX             | 1         | 1.09%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK      | 1         | 1.09%   |
| Lenovo IdeaPad 5 14ABA7 82SE               | 1         | 1.09%   |
| Lenovo IdeaPad 330-15IKB Touch 81DJ        | 1         | 1.09%   |
| Lenovo G500 20236                          | 1         | 1.09%   |
| Lenovo G50-70 20351                        | 1         | 1.09%   |
| Lenovo G50-45 80E3                         | 1         | 1.09%   |
| Lenovo G50-30 80G0                         | 1         | 1.09%   |
| Lenovo B590 20208                          | 1         | 1.09%   |
| Kiano SlimNote 14.1                        | 1         | 1.09%   |
| Intel Infoway                              | 1         | 1.09%   |
| IFSA Positivo BGH                          | 1         | 1.09%   |
| HP ProBook 640 G1                          | 1         | 1.09%   |
| HP ProBook 4730s                           | 1         | 1.09%   |
| HP ProBook 430 G7                          | 1         | 1.09%   |
| HP Pavilion Sleekbook 15 PC                | 1         | 1.09%   |
| HP Pavilion dv4                            | 1         | 1.09%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 6         | 6.52%   |
| Lenovo ThinkPad        | 5         | 5.43%   |
| Dell Latitude          | 5         | 5.43%   |
| HP Pavilion            | 4         | 4.35%   |
| Fujitsu LIFEBOOK       | 4         | 4.35%   |
| Acer Aspire            | 4         | 4.35%   |
| Unknown                | 4         | 4.35%   |
| HP ProBook             | 3         | 3.26%   |
| Apple MacBookPro8      | 3         | 3.26%   |
| Toshiba Satellite      | 2         | 2.17%   |
| Mediacom WinPad        | 2         | 2.17%   |
| Dell XPS               | 2         | 2.17%   |
| Sony VPCEB15FM         | 1         | 1.09%   |
| Sony VGN-SZ71WN        | 1         | 1.09%   |
| Sony SVE14A2V1EW       | 1         | 1.09%   |
| SGIN laptop            | 1         | 1.09%   |
| Samsung 300V3A         | 1         | 1.09%   |
| Pretech EVE            | 1         | 1.09%   |
| Prestigio PSB141C01BFH | 1         | 1.09%   |
| Positivo i500pro       | 1         | 1.09%   |
| Packard Bell EasyNote  | 1         | 1.09%   |
| Lenovo Z70-80          | 1         | 1.09%   |
| Lenovo G500            | 1         | 1.09%   |
| Lenovo G50-70          | 1         | 1.09%   |
| Lenovo G50-45          | 1         | 1.09%   |
| Lenovo G50-30          | 1         | 1.09%   |
| Lenovo B590            | 1         | 1.09%   |
| Kiano SlimNote         | 1         | 1.09%   |
| Intel Infoway          | 1         | 1.09%   |
| IFSA Positivo          | 1         | 1.09%   |
| HP Laptop              | 1         | 1.09%   |
| HP 250                 | 1         | 1.09%   |
| HP 245                 | 1         | 1.09%   |
| HP 2000                | 1         | 1.09%   |
| HP 15                  | 1         | 1.09%   |
| GPU Company GWTC116-2  | 1         | 1.09%   |
| Google Terra           | 1         | 1.09%   |
| Google Relm            | 1         | 1.09%   |
| Google Celes           | 1         | 1.09%   |
| Google Candy           | 1         | 1.09%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 14        | 15.22%  |
| 2013 | 9         | 9.78%   |
| 2012 | 9         | 9.78%   |
| 2020 | 7         | 7.61%   |
| 2021 | 6         | 6.52%   |
| 2019 | 6         | 6.52%   |
| 2016 | 6         | 6.52%   |
| 2014 | 6         | 6.52%   |
| 2015 | 5         | 5.43%   |
| 2008 | 5         | 5.43%   |
| 2022 | 4         | 4.35%   |
| 2010 | 4         | 4.35%   |
| 2009 | 4         | 4.35%   |
| 2007 | 3         | 3.26%   |
| 2018 | 2         | 2.17%   |
| 2017 | 2         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 92        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 89        | 96.74%  |
| Enabled  | 3         | 3.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 85        | 92.39%  |
| Yes  | 7         | 7.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 37        | 39.78%  |
| 4.01-8.0   | 24        | 25.81%  |
| 1.01-2.0   | 13        | 13.98%  |
| 8.01-16.0  | 10        | 10.75%  |
| 2.01-3.0   | 4         | 4.3%    |
| 16.01-24.0 | 4         | 4.3%    |
| 32.01-64.0 | 1         | 1.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 46        | 48.42%  |
| 0.51-1.0 | 26        | 27.37%  |
| 2.01-3.0 | 18        | 18.95%  |
| 4.01-8.0 | 3         | 3.16%   |
| 3.01-4.0 | 2         | 2.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 77        | 82.8%   |
| 2      | 13        | 13.98%  |
| 3      | 2         | 2.15%   |
| 0      | 1         | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 56.52%  |
| Yes       | 40        | 43.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 75%     |
| No        | 23        | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 91.3%   |
| No        | 8         | 8.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 67.39%  |
| No        | 30        | 32.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 13        | 14.13%  |
| Italy        | 10        | 10.87%  |
| Poland       | 7         | 7.61%   |
| Germany      | 7         | 7.61%   |
| France       | 6         | 6.52%   |
| Brazil       | 6         | 6.52%   |
| UK           | 4         | 4.35%   |
| Canada       | 4         | 4.35%   |
| Belgium      | 4         | 4.35%   |
| Russia       | 3         | 3.26%   |
| Vietnam      | 2         | 2.17%   |
| Turkey       | 2         | 2.17%   |
| Mexico       | 2         | 2.17%   |
| Hungary      | 2         | 2.17%   |
| Costa Rica   | 2         | 2.17%   |
| Argentina    | 2         | 2.17%   |
| Ukraine      | 1         | 1.09%   |
| Sweden       | 1         | 1.09%   |
| Spain        | 1         | 1.09%   |
| South Africa | 1         | 1.09%   |
| Portugal     | 1         | 1.09%   |
| Philippines  | 1         | 1.09%   |
| Netherlands  | 1         | 1.09%   |
| Kenya        | 1         | 1.09%   |
| Japan        | 1         | 1.09%   |
| Indonesia    | 1         | 1.09%   |
| Greece       | 1         | 1.09%   |
| Finland      | 1         | 1.09%   |
| Colombia     | 1         | 1.09%   |
| Chile        | 1         | 1.09%   |
| Belarus      | 1         | 1.09%   |
| Australia    | 1         | 1.09%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Paris                     | 4         | 4.21%   |
| Sarospatak                | 2         | 2.11%   |
| Porto Alegre              | 2         | 2.11%   |
| Heredia                   | 2         | 2.11%   |
| Ghent                     | 2         | 2.11%   |
| Zizur Mayor               | 1         | 1.05%   |
| Zawiercie                 | 1         | 1.05%   |
| Yoshkar-Ola               | 1         | 1.05%   |
| Yorkville                 | 1         | 1.05%   |
| Wolfhagen                 | 1         | 1.05%   |
| Warsaw                    | 1         | 1.05%   |
| Volzhskiy                 | 1         | 1.05%   |
| Verona                    | 1         | 1.05%   |
| Tychy                     | 1         | 1.05%   |
| Thornton Heath            | 1         | 1.05%   |
| Thessaloniki              | 1         | 1.05%   |
| Surabaya                  | 1         | 1.05%   |
| Stuttgart                 | 1         | 1.05%   |
| Strzyzow                  | 1         | 1.05%   |
| Stockholm                 | 1         | 1.05%   |
| Southampton               | 1         | 1.05%   |
| South Burlington          | 1         | 1.05%   |
| Sao Paulo                 | 1         | 1.05%   |
| Santiago                  | 1         | 1.05%   |
| Saint-Raymond-de-Portneuf | 1         | 1.05%   |
| Roswell                   | 1         | 1.05%   |
| Rossano Veneto            | 1         | 1.05%   |
| Rio de Janeiro            | 1         | 1.05%   |
| Quezon City               | 1         | 1.05%   |
| Pretoria                  | 1         | 1.05%   |
| Pontypool                 | 1         | 1.05%   |
| Plan-dAups-Sainte-Baume   | 1         | 1.05%   |
| Pisa                      | 1         | 1.05%   |
| Perth Amboy               | 1         | 1.05%   |
| Palermo                   | 1         | 1.05%   |
| Novo Gama                 | 1         | 1.05%   |
| Novi                      | 1         | 1.05%   |
| Newtown                   | 1         | 1.05%   |
| New York                  | 1         | 1.05%   |
| Naples                    | 1         | 1.05%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 17        | 24     | 17.35%  |
| Seagate             | 12        | 15     | 12.24%  |
| WDC                 | 11        | 13     | 11.22%  |
| Toshiba             | 9         | 10     | 9.18%   |
| Samsung Electronics | 8         | 11     | 8.16%   |
| Hitachi             | 5         | 6      | 5.1%    |
| SanDisk             | 3         | 3      | 3.06%   |
| SPCC                | 2         | 3      | 2.04%   |
| Micron Technology   | 2         | 2      | 2.04%   |
| Kingston            | 2         | 2      | 2.04%   |
| GOODRAM             | 2         | 2      | 2.04%   |
| Crucial             | 2         | 2      | 2.04%   |
| Apacer              | 2         | 2      | 2.04%   |
| A-DATA Technology   | 2         | 2      | 2.04%   |
| W800S               | 1         | 1      | 1.02%   |
| UMIS                | 1         | 1      | 1.02%   |
| Transcend           | 1         | 1      | 1.02%   |
| Teclast             | 1         | 1      | 1.02%   |
| SK hynix            | 1         | 1      | 1.02%   |
| Rogueware           | 1         | 1      | 1.02%   |
| NGFF                | 1         | 1      | 1.02%   |
| Lexar               | 1         | 1      | 1.02%   |
| Leqixiang           | 1         | 1      | 1.02%   |
| Lenovo              | 1         | 1      | 1.02%   |
| KINGPOWER           | 1         | 1      | 1.02%   |
| Intenso             | 1         | 1      | 1.02%   |
| Intel               | 1         | 1      | 1.02%   |
| HUSKY               | 1         | 1      | 1.02%   |
| HGST                | 1         | 1      | 1.02%   |
| Fujitsu             | 1         | 1      | 1.02%   |
| China               | 1         | 1      | 1.02%   |
| Apple               | 1         | 2      | 1.02%   |
| Unknown             | 1         | 1      | 1.02%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST9500325AS 500GB            | 4         | 3.74%   |
| Unknown SD/MMC/MS PRO 64GB           | 2         | 1.87%   |
| Unknown SC64G  64GB                  | 2         | 1.87%   |
| Unknown NCard  32GB                  | 2         | 1.87%   |
| Unknown MMC64G  64GB                 | 2         | 1.87%   |
| Unknown MMC Card  32GB               | 2         | 1.87%   |
| Unknown DA4032  32GB                 | 2         | 1.87%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.87%   |
| SPCC Solid State Disk 120GB          | 2         | 1.87%   |
| SanDisk DF4032  32GB                 | 2         | 1.87%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.93%   |
| WDC WDS500G2B0A 500GB SSD            | 1         | 0.93%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.93%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.93%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.93%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.93%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.93%   |
| WDC WD10SPZX-24Z10T0 1TB             | 1         | 0.93%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.93%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.93%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.93%   |
| WDC PC SN730 SDBQNTY-256G-1006 256GB | 1         | 0.93%   |
| W800S 256GB SSD                      | 1         | 0.93%   |
| Unknown SF64G  64GB                  | 1         | 0.93%   |
| Unknown MMC Card  64GB               | 1         | 0.93%   |
| Unknown MMC Card  16GB               | 1         | 0.93%   |
| Unknown ISOCOM  64GB                 | 1         | 0.93%   |
| Unknown HAG4a2  16GB                 | 1         | 0.93%   |
| Unknown ED2S5  128GB                 | 1         | 0.93%   |
| Unknown DA4064  64GB                 | 1         | 0.93%   |
| Unknown CGND3R  64GB                 | 1         | 0.93%   |
| Unknown BJNB4R  32GB                 | 1         | 0.93%   |
| Unknown ASTC  8GB                    | 1         | 0.93%   |
| Unknown ASTC  32GB                   | 1         | 0.93%   |
| UMIS RPFTJ256PDD2MWX 256GB           | 1         | 0.93%   |
| Transcend TS512GMTS800 512GB SSD     | 1         | 0.93%   |
| Toshiba THNSNJ128GCSY 128GB SSD      | 1         | 0.93%   |
| Toshiba THNSNH128GBST SSD            | 1         | 0.93%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.93%   |
| Toshiba MQ01ABD050 500GB             | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 15     | 32.43%  |
| WDC                 | 8         | 8      | 21.62%  |
| Toshiba             | 7         | 8      | 18.92%  |
| Hitachi             | 5         | 6      | 13.51%  |
| Unknown             | 2         | 2      | 5.41%   |
| Samsung Electronics | 1         | 4      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |
| Fujitsu             | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 15.15%  |
| WDC                 | 2         | 3      | 6.06%   |
| Toshiba             | 2         | 2      | 6.06%   |
| SPCC                | 2         | 3      | 6.06%   |
| GOODRAM             | 2         | 2      | 6.06%   |
| Crucial             | 2         | 2      | 6.06%   |
| Apacer              | 2         | 2      | 6.06%   |
| A-DATA Technology   | 2         | 2      | 6.06%   |
| W800S               | 1         | 1      | 3.03%   |
| Transcend           | 1         | 1      | 3.03%   |
| Teclast             | 1         | 1      | 3.03%   |
| SanDisk             | 1         | 1      | 3.03%   |
| Rogueware           | 1         | 1      | 3.03%   |
| NGFF                | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Lexar               | 1         | 1      | 3.03%   |
| Leqixiang           | 1         | 1      | 3.03%   |
| Lenovo              | 1         | 1      | 3.03%   |
| Kingston            | 1         | 1      | 3.03%   |
| KINGPOWER           | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| HUSKY               | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 37        | 45     | 37%     |
| SSD     | 33        | 35     | 33%     |
| MMC     | 19        | 25     | 19%     |
| NVMe    | 9         | 10     | 9%      |
| Unknown | 2         | 2      | 2%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 77     | 66.67%  |
| MMC  | 19        | 25     | 19.19%  |
| NVMe | 9         | 10     | 9.09%   |
| SAS  | 5         | 5      | 5.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 62     | 76.81%  |
| 0.51-1.0   | 15        | 17     | 21.74%  |
| 3.01-4.0   | 1         | 1      | 1.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 30.85%  |
| 251-500        | 27        | 28.72%  |
| 1-20           | 11        | 11.7%   |
| 501-1000       | 9         | 9.57%   |
| 51-100         | 8         | 8.51%   |
| 21-50          | 7         | 7.45%   |
| More than 3000 | 1         | 1.06%   |
| 2001-3000      | 1         | 1.06%   |
| Unknown        | 1         | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 54        | 56.84%  |
| 21-50          | 20        | 21.05%  |
| 101-250        | 7         | 7.37%   |
| 51-100         | 7         | 7.37%   |
| 251-500        | 3         | 3.16%   |
| More than 3000 | 1         | 1.05%   |
| 1001-2000      | 1         | 1.05%   |
| 501-1000       | 1         | 1.05%   |
| Unknown        | 1         | 1.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 2         | 2      | 12.5%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 6.25%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 6.25%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD050 500GB           | 1         | 1      | 6.25%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 6.25%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 6.25%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 6.25%   |
| Seagate ST1000DM003-1SB102 1TB     | 1         | 1      | 6.25%   |
| Samsung Electronics HM121HI 120GB  | 1         | 4      | 6.25%   |
| NGFF 2280 512GB SSD                | 1         | 1      | 6.25%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 6.25%   |
| Fujitsu MHY2120BH 120GB            | 1         | 1      | 6.25%   |
| Apacer 16GB SATA Flash Drive SSD   | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 43.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| Toshiba             | 2         | 2      | 12.5%   |
| Samsung Electronics | 1         | 4      | 6.25%   |
| NGFF                | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |
| Fujitsu             | 1         | 1      | 6.25%   |
| Apacer              | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 50%     |
| WDC                 | 2         | 2      | 14.29%  |
| Toshiba             | 2         | 2      | 14.29%  |
| Samsung Electronics | 1         | 4      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |
| Fujitsu             | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 17     | 87.5%   |
| SSD  | 2         | 2      | 12.5%   |

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
| Detected | 54        | 71     | 56.25%  |
| Works    | 26        | 27     | 27.08%  |
| Malfunc  | 16        | 19     | 16.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 66        | 76.74%  |
| AMD                         | 10        | 11.63%  |
| SanDisk                     | 2         | 2.33%   |
| Samsung Electronics         | 2         | 2.33%   |
| Nvidia                      | 2         | 2.33%   |
| Union Memory (Shenzhen)     | 1         | 1.16%   |
| SK hynix                    | 1         | 1.16%   |
| Micron Technology           | 1         | 1.16%   |
| Kingston Technology Company | 1         | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 11        | 11.7%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 7.45%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 6.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 5         | 5.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 5         | 5.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 4.26%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 4         | 4.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 4         | 4.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 3.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 3.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 3.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 3.19%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 2.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 2         | 2.13%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 2         | 2.13%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 2.13%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 2.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 2.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 2.13%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 1.06%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 1.06%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 1         | 1.06%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.06%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 1.06%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.06%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.06%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 1.06%   |
| Intel SATA Controller [RAID mode]                                                      | 1         | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 1         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 1.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 1.06%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 1         | 1.06%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 1.06%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 1         | 1.06%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 71        | 78.02%  |
| IDE  | 9         | 9.89%   |
| NVMe | 8         | 8.79%   |
| RAID | 3         | 3.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 83        | 90.22%  |
| AMD    | 9         | 9.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 4.35%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 3.26%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 3.26%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 3         | 3.26%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 2.17%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 2.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2.17%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 2.17%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 2.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 2.17%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 2.17%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 2.17%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 2.17%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 2.17%   |
| AMD E-450 APU with Radeon HD Graphics         | 2         | 2.17%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 2.17%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 1.09%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.09%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 1.09%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.09%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.09%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.09%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 1.09%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 1.09%   |
| Intel Core i7-2635QM CPU @ 2.00GHz            | 1         | 1.09%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 1         | 1.09%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.09%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.09%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.09%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.09%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1.09%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 1.09%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 1.09%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.09%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.09%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.09%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.09%   |
| Intel Core i3-2367M CPU @ 1.40GHz             | 1         | 1.09%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 1.09%   |
| Intel Core i3-2348M CPU @ 2.30GHz             | 1         | 1.09%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 19        | 20.65%  |
| Intel Celeron      | 19        | 20.65%  |
| Intel Core i3      | 11        | 11.96%  |
| Intel Core i7      | 10        | 10.87%  |
| Intel Core 2 Duo   | 10        | 10.87%  |
| Intel Atom         | 7         | 7.61%   |
| Intel Pentium      | 5         | 5.43%   |
| AMD A6             | 3         | 3.26%   |
| AMD E1             | 2         | 2.17%   |
| AMD E              | 2         | 2.17%   |
| Intel Pentium Dual | 1         | 1.09%   |
| Intel Core 2       | 1         | 1.09%   |
| AMD Ryzen 5        | 1         | 1.09%   |
| AMD C-60           | 1         | 1.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 66        | 71.74%  |
| 4      | 23        | 25%     |
| 1      | 2         | 2.17%   |
| 6      | 1         | 1.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 92        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 54.35%  |
| 2      | 42        | 45.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 92        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 32.26%  |
| 0x206a7    | 8         | 8.6%    |
| 0x306a9    | 6         | 6.45%   |
| 0x406c4    | 4         | 4.3%    |
| 0x406c3    | 4         | 4.3%    |
| 0x40651    | 3         | 3.23%   |
| 0x1067a    | 3         | 3.23%   |
| 0x05000119 | 3         | 3.23%   |
| 0x906c0    | 2         | 2.15%   |
| 0x806ec    | 2         | 2.15%   |
| 0x806ea    | 2         | 2.15%   |
| 0x706e5    | 2         | 2.15%   |
| 0x706a8    | 2         | 2.15%   |
| 0x6fd      | 2         | 2.15%   |
| 0x20655    | 2         | 2.15%   |
| 0x06006705 | 2         | 2.15%   |
| 0x906ed    | 1         | 1.08%   |
| 0x806eb    | 1         | 1.08%   |
| 0x806e9    | 1         | 1.08%   |
| 0x706a1    | 1         | 1.08%   |
| 0x6fa      | 1         | 1.08%   |
| 0x6f6      | 1         | 1.08%   |
| 0x506e3    | 1         | 1.08%   |
| 0x506c9    | 1         | 1.08%   |
| 0x406e3    | 1         | 1.08%   |
| 0x306c3    | 1         | 1.08%   |
| 0x30678    | 1         | 1.08%   |
| 0x106ca    | 1         | 1.08%   |
| 0x10676    | 1         | 1.08%   |
| 0x0a50000c | 1         | 1.08%   |
| 0x0700010f | 1         | 1.08%   |
| 0x06001116 | 1         | 1.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 17        | 18.48%  |
| SandyBridge   | 13        | 14.13%  |
| IvyBridge     | 8         | 8.7%    |
| Penryn        | 7         | 7.61%   |
| KabyLake      | 7         | 7.61%   |
| Haswell       | 6         | 6.52%   |
| Goldmont plus | 6         | 6.52%   |
| Core          | 5         | 5.43%   |
| Westmere      | 4         | 4.35%   |
| Bobcat        | 3         | 3.26%   |
| Tremont       | 2         | 2.17%   |
| Skylake       | 2         | 2.17%   |
| IceLake       | 2         | 2.17%   |
| Excavator     | 2         | 2.17%   |
| Broadwell     | 2         | 2.17%   |
| Zen 3         | 1         | 1.09%   |
| Puma          | 1         | 1.09%   |
| Piledriver    | 1         | 1.09%   |
| Jaguar        | 1         | 1.09%   |
| Goldmont      | 1         | 1.09%   |
| Bonnell       | 1         | 1.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 77        | 76.24%  |
| AMD    | 16        | 15.84%  |
| Nvidia | 8         | 7.92%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 12.04%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 11.11%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 7.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 5.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 4.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 4.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 4.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 4.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.7%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 2.78%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.85%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.85%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.85%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 1.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.85%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.85%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.93%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.93%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.93%   |
| Nvidia GF119M [GeForce GT 520MX]                                                         | 1         | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.93%   |
| Nvidia G96CM [GeForce GT 120M]                                                           | 1         | 0.93%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 0.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 0.93%   |
| Intel HD Graphics 620                                                                    | 1         | 0.93%   |
| Intel HD Graphics 530                                                                    | 1         | 0.93%   |
| Intel HD Graphics 500                                                                    | 1         | 0.93%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 0.93%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1         | 0.93%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 0.93%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 0.93%   |
| AMD RS600M [Radeon Xpress 1250]                                                          | 1         | 0.93%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                                  | 1         | 0.93%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 66        | 71.74%  |
| 1 x AMD        | 9         | 9.78%   |
| Intel + AMD    | 5         | 5.43%   |
| 1 x Nvidia     | 4         | 4.35%   |
| Intel + Nvidia | 4         | 4.35%   |
| Other          | 2         | 2.17%   |
| 2 x AMD        | 2         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 91        | 98.91%  |
| Proprietary | 1         | 1.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 84.95%  |
| 0.01-0.5   | 7         | 7.53%   |
| 1.01-2.0   | 5         | 5.38%   |
| 2.01-3.0   | 1         | 1.08%   |
| 0.51-1.0   | 1         | 1.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 18        | 19.57%  |
| LG Display              | 17        | 18.48%  |
| Chimei Innolux          | 15        | 16.3%   |
| Samsung Electronics     | 10        | 10.87%  |
| BOE                     | 10        | 10.87%  |
| Apple                   | 6         | 6.52%   |
| CPT                     | 3         | 3.26%   |
| Lenovo                  | 2         | 2.17%   |
| Chi Mei Optoelectronics | 2         | 2.17%   |
| ViewSonic               | 1         | 1.09%   |
| Toshiba                 | 1         | 1.09%   |
| Sharp                   | 1         | 1.09%   |
| LG Philips              | 1         | 1.09%   |
| JVC                     | 1         | 1.09%   |
| JDI                     | 1         | 1.09%   |
| Goldstar                | 1         | 1.09%   |
| BenQ                    | 1         | 1.09%   |
| Acer                    | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 4         | 4.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 2.17%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 2         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 2.17%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 2.17%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 2.17%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 2.17%   |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch         | 1         | 1.09%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch              | 1         | 1.09%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 1.09%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch  | 1         | 1.09%   |
| LG Philips LCD Monitor LPLEC00 1280x800 331x207mm 15.4-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0680 1920x1080 344x194mm 15.5-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x174mm 14.0-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD03E9 1366x768 345x194mm 15.6-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 1.09%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch               | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 1.09%   |
| JVC FPDEUFY2 JVC221F 1920x1080                                        | 1         | 1.09%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 47        | 52.22%  |
| 1920x1080 (FHD)    | 16        | 17.78%  |
| 1280x800 (WXGA)    | 11        | 12.22%  |
| 1600x900 (HD+)     | 5         | 5.56%   |
| 2560x1440 (QHD)    | 2         | 2.22%   |
| 3840x2160 (4K)     | 1         | 1.11%   |
| 3200x1800 (QHD+)   | 1         | 1.11%   |
| 3000x2000          | 1         | 1.11%   |
| 2560x1080          | 1         | 1.11%   |
| 2160x1440          | 1         | 1.11%   |
| 1680x1050 (WSXGA+) | 1         | 1.11%   |
| 1528x1222          | 1         | 1.11%   |
| 1440x900 (WXGA+)   | 1         | 1.11%   |
| 1360x768           | 1         | 1.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 31        | 33.7%   |
| 13      | 17        | 18.48%  |
| 14      | 15        | 16.3%   |
| 11      | 11        | 11.96%  |
| 17      | 6         | 6.52%   |
| 23      | 2         | 2.17%   |
| 28      | 1         | 1.09%   |
| 27      | 1         | 1.09%   |
| 21      | 1         | 1.09%   |
| 19      | 1         | 1.09%   |
| 18      | 1         | 1.09%   |
| 16      | 1         | 1.09%   |
| 12      | 1         | 1.09%   |
| 10      | 1         | 1.09%   |
| 9       | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 53        | 57.61%  |
| 201-300     | 23        | 25%     |
| 351-400     | 7         | 7.61%   |
| 401-500     | 3         | 3.26%   |
| 601-700     | 2         | 2.17%   |
| 501-600     | 2         | 2.17%   |
| 101-200     | 1         | 1.09%   |
| Unknown     | 1         | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 70        | 79.55%  |
| 16/10 | 14        | 15.91%  |
| 3/2   | 2         | 2.27%   |
| 4/3   | 1         | 1.14%   |
| 21/9  | 1         | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 31        | 33.7%   |
| 81-90          | 29        | 31.52%  |
| 51-60          | 11        | 11.96%  |
| 121-130        | 6         | 6.52%   |
| 71-80          | 3         | 3.26%   |
| 201-250        | 3         | 3.26%   |
| 41-50          | 2         | 2.17%   |
| 61-70          | 1         | 1.09%   |
| 301-350        | 1         | 1.09%   |
| 251-300        | 1         | 1.09%   |
| 151-200        | 1         | 1.09%   |
| 141-150        | 1         | 1.09%   |
| 131-140        | 1         | 1.09%   |
| Unknown        | 1         | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 45        | 48.91%  |
| 121-160       | 26        | 28.26%  |
| 51-100        | 13        | 14.13%  |
| 161-240       | 5         | 5.43%   |
| More than 240 | 2         | 2.17%   |
| Unknown       | 1         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 86        | 93.48%  |
| 2     | 5         | 5.43%   |
| 3     | 1         | 1.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 43        | 31.16%  |
| Intel                           | 39        | 28.26%  |
| Qualcomm Atheros                | 23        | 16.67%  |
| Broadcom                        | 12        | 8.7%    |
| Marvell Technology Group        | 4         | 2.9%    |
| Samsung Electronics             | 3         | 2.17%   |
| Qualcomm Atheros Communications | 2         | 1.45%   |
| Broadcom Limited                | 2         | 1.45%   |
| TP-Link                         | 1         | 0.72%   |
| Sierra Wireless                 | 1         | 0.72%   |
| Ralink Technology               | 1         | 0.72%   |
| Ralink                          | 1         | 0.72%   |
| Qualcomm                        | 1         | 0.72%   |
| Nvidia                          | 1         | 0.72%   |
| NetGear                         | 1         | 0.72%   |
| Microsoft                       | 1         | 0.72%   |
| ICS Advent                      | 1         | 0.72%   |
| ASIX Electronics                | 1         | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 12.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 4.82%   |
| Intel Wireless 7265                                               | 6         | 3.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 3.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 3.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 3.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 3.01%   |
| Intel Wireless 7260                                               | 5         | 3.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.81%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 1.81%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.2%    |
| Realtek 802.11n WLAN Adapter                                      | 2         | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.2%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.2%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.2%    |
| Intel Wireless 3160                                               | 2         | 1.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.2%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.2%    |
| Intel Centrino Advanced-N 6235                                    | 2         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.2%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 1.2%    |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.2%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.6%    |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.6%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.6%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.6%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.6%    |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 40.66%  |
| Qualcomm Atheros                | 22        | 24.18%  |
| Realtek Semiconductor           | 17        | 18.68%  |
| Broadcom                        | 7         | 7.69%   |
| Qualcomm Atheros Communications | 2         | 2.2%    |
| Sierra Wireless                 | 1         | 1.1%    |
| Ralink Technology               | 1         | 1.1%    |
| Ralink                          | 1         | 1.1%    |
| NetGear                         | 1         | 1.1%    |
| Microsoft                       | 1         | 1.1%    |
| Broadcom Limited                | 1         | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 6         | 6.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 5.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 5.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 5.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 5.49%   |
| Intel Wireless 7260                                                     | 5         | 5.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 3.3%    |
| Intel Centrino Wireless-N 2230                                          | 3         | 3.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.2%    |
| Realtek 802.11n WLAN Adapter                                            | 2         | 2.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.2%    |
| Intel Wireless 3160                                                     | 2         | 2.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 2.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 2.2%    |
| Intel Centrino Advanced-N 6235                                          | 2         | 2.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 2.2%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.2%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 2.2%    |
| Sierra Wireless EM7305 Modem                                            | 1         | 1.1%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.1%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.1%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.1%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.1%    |
| Realtek Realtek Network controller                                      | 1         | 1.1%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 1.1%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.1%    |
| Qualcomm Atheros UB94                                                   | 1         | 1.1%    |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.1%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.1%    |
| NetGear A6210                                                           | 1         | 1.1%    |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 1.1%    |
| Intel Wireless 8265 / 8275                                              | 1         | 1.1%    |
| Intel Wireless 8260                                                     | 1         | 1.1%    |
| Intel Wireless 3165                                                     | 1         | 1.1%    |
| Intel WiFi Link 5100                                                    | 1         | 1.1%    |
| Intel PRODUCT_MODEM                                                     | 1         | 1.1%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 33        | 44.59%  |
| Intel                    | 14        | 18.92%  |
| Broadcom                 | 8         | 10.81%  |
| Qualcomm Atheros         | 6         | 8.11%   |
| Marvell Technology Group | 4         | 5.41%   |
| Samsung Electronics      | 3         | 4.05%   |
| TP-Link                  | 1         | 1.35%   |
| Qualcomm                 | 1         | 1.35%   |
| Nvidia                   | 1         | 1.35%   |
| ICS Advent               | 1         | 1.35%   |
| Broadcom Limited         | 1         | 1.35%   |
| ASIX Electronics         | 1         | 1.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 20        | 26.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 10.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 5.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 4%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 4%      |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 2.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 2.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 2.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 2.67%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 2.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 2.67%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.33%   |
| Realtek RTL8150 Fast Ethernet Adapter                                          | 1         | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.33%   |
| Qualcomm MegaFon M150-4                                                        | 1         | 1.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.33%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 1.33%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.33%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.33%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.33%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.33%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.33%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.33%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.33%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 1.33%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 1.33%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 1.33%   |
| Broadcom NetXtreme BCM5756ME Gigabit Ethernet PCI Express                      | 1         | 1.33%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 1.33%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 84        | 55.26%  |
| Ethernet | 68        | 44.74%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 70.79%  |
| Ethernet | 26        | 29.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 60        | 65.22%  |
| 1     | 22        | 23.91%  |
| 0     | 10        | 10.87%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 74        | 79.57%  |
| Yes  | 19        | 20.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 41.94%  |
| Realtek Semiconductor           | 10        | 16.13%  |
| Qualcomm Atheros Communications | 7         | 11.29%  |
| Apple                           | 4         | 6.45%   |
| Dell                            | 3         | 4.84%   |
| Broadcom                        | 3         | 4.84%   |
| IMC Networks                    | 2         | 3.23%   |
| Foxconn / Hon Hai               | 2         | 3.23%   |
| Toshiba                         | 1         | 1.61%   |
| Syntek                          | 1         | 1.61%   |
| Lite-On Technology              | 1         | 1.61%   |
| Cambridge Silicon Radio         | 1         | 1.61%   |
| Alps Electric                   | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 16        | 25.81%  |
| Realtek Bluetooth Radio                                                             | 7         | 11.29%  |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 6.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 6.45%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 4.84%   |
| Apple Bluetooth Host Controller                                                     | 3         | 4.84%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 3.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 3.23%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 1.61%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 1.61%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.61%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 1.61%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.61%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.61%   |
| Intel AX201 Bluetooth                                                               | 1         | 1.61%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.61%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 1.61%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.61%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.61%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 1.61%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 1.61%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.61%   |
| Broadcom HP Portable Valentine                                                      | 1         | 1.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.61%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.61%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.61%   |
| Alps Electric Bluetooth Adapter                                                     | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 74        | 81.32%  |
| AMD                  | 11        | 12.09%  |
| Nvidia               | 4         | 4.4%    |
| MosArt Semiconductor | 1         | 1.1%    |
| JMTek                | 1         | 1.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 12.15%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 7.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 7.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 5.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 4.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 4.67%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 4.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 3.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 3.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 3.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 2.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.8%    |
| AMD FCH Azalia Controller                                                                         | 3         | 2.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.87%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1.87%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.87%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.87%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.87%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.87%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.87%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.87%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.93%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.93%   |
| MosArt Semiconductor MosArt USB Audio Device                                                      | 1         | 0.93%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.93%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.93%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.93%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.93%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 0.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.93%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 25.68%  |
| SK hynix            | 14        | 18.92%  |
| Micron Technology   | 11        | 14.86%  |
| Unknown             | 9         | 12.16%  |
| Nanya Technology    | 3         | 4.05%   |
| Elpida              | 3         | 4.05%   |
| Unknown (ABCD)      | 2         | 2.7%    |
| Smart               | 2         | 2.7%    |
| Kingston            | 2         | 2.7%    |
| Corsair             | 2         | 2.7%    |
| Ramaxel Technology  | 1         | 1.35%   |
| Novatech            | 1         | 1.35%   |
| Kllisre             | 1         | 1.35%   |
| HMD                 | 1         | 1.35%   |
| AMD                 | 1         | 1.35%   |
| A-DATA Technology   | 1         | 1.35%   |
| Unknown             | 1         | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 2.53%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 2         | 2.53%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 2.53%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.53%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 2.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.53%   |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 2.53%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.27%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.27%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 1.27%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.27%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1.27%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.27%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.27%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.27%   |
| SK hynix RAM HT5SMRAP 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.27%   |
| SK hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.27%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.27%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.27%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.27%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.27%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.27%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 1         | 1.27%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1333MT/s           | 1         | 1.27%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.27%   |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s              | 1         | 1.27%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                     | 1         | 1.27%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.27%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.27%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.27%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.27%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 1.27%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.27%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.27%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.27%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.27%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.27%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 1.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 35        | 54.69%  |
| DDR4   | 15        | 23.44%  |
| LPDDR4 | 5         | 7.81%   |
| DDR2   | 5         | 7.81%   |
| SDRAM  | 2         | 3.13%   |
| LPDDR3 | 2         | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 56        | 87.5%   |
| Row Of Chips | 5         | 7.81%   |
| Unknown      | 3         | 4.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 24        | 32.43%  |
| 2048  | 24        | 32.43%  |
| 8192  | 16        | 21.62%  |
| 1024  | 5         | 6.76%   |
| 16384 | 2         | 2.7%    |
| 32768 | 1         | 1.35%   |
| 6144  | 1         | 1.35%   |
| 512   | 1         | 1.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 21        | 30.88%  |
| 1333    | 7         | 10.29%  |
| 3200    | 6         | 8.82%   |
| 2667    | 6         | 8.82%   |
| 1334    | 4         | 5.88%   |
| 667     | 4         | 5.88%   |
| 2400    | 3         | 4.41%   |
| 1066    | 3         | 4.41%   |
| 3266    | 2         | 2.94%   |
| 1866    | 2         | 2.94%   |
| 1067    | 2         | 2.94%   |
| Unknown | 2         | 2.94%   |
| 4199    | 1         | 1.47%   |
| 3733    | 1         | 1.47%   |
| 2133    | 1         | 1.47%   |
| 2048    | 1         | 1.47%   |
| 1867    | 1         | 1.47%   |
| 975     | 1         | 1.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 21        | 27.27%  |
| Microdia                               | 10        | 12.99%  |
| Sunplus Innovation Technology          | 7         | 9.09%   |
| Realtek Semiconductor                  | 6         | 7.79%   |
| Syntek                                 | 4         | 5.19%   |
| IMC Networks                           | 4         | 5.19%   |
| Apple                                  | 4         | 5.19%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.9%    |
| Alcor Micro                            | 3         | 3.9%    |
| Silicon Motion                         | 2         | 2.6%    |
| Quanta                                 | 2         | 2.6%    |
| Lenovo                                 | 2         | 2.6%    |
| ALi                                    | 2         | 2.6%    |
| USB Camera CS                          | 1         | 1.3%    |
| Suyin                                  | 1         | 1.3%    |
| SunplusIT                              | 1         | 1.3%    |
| Ricoh                                  | 1         | 1.3%    |
| Lite-On Technology                     | 1         | 1.3%    |
| Cubeternet                             | 1         | 1.3%    |
| Acer                                   | 1         | 1.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 6         | 7.69%   |
| Realtek Integrated_Webcam_HD                        | 3         | 3.85%   |
| Chicony HD WebCam                                   | 3         | 3.85%   |
| Alcor Micro USB 2.0 Camera                          | 3         | 3.85%   |
| Sunplus HD WebCam                                   | 2         | 2.56%   |
| Microdia Lenovo EasyCamera                          | 2         | 2.56%   |
| Microdia Integrated Webcam                          | 2         | 2.56%   |
| Microdia HP Webcam-50                               | 2         | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 2.56%   |
| Chicony FJ Camera                                   | 2         | 2.56%   |
| Chicony EasyCamera                                  | 2         | 2.56%   |
| Apple FaceTime HD Camera                            | 2         | 2.56%   |
| ALi WebCam                                          | 2         | 2.56%   |
| USB Camera CS USB Camera CS                         | 1         | 1.28%   |
| Syntek USB2.0 Camera                                | 1         | 1.28%   |
| Syntek USB Camera Device                            | 1         | 1.28%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.28%   |
| Syntek HD WebCam                                    | 1         | 1.28%   |
| Suyin 1.3M Front                                    | 1         | 1.28%   |
| SunplusIT MTD camera                                | 1         | 1.28%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 1.28%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.28%   |
| Sunplus HD User Facing                              | 1         | 1.28%   |
| Sunplus Dell Integrated HD Webcam                   | 1         | 1.28%   |
| Sunplus Asus Webcam                                 | 1         | 1.28%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 1.28%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 1.28%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 1.28%   |
| Realtek USB Camera                                  | 1         | 1.28%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.28%   |
| Realtek EasyCamera                                  | 1         | 1.28%   |
| Quanta HP Webcam                                    | 1         | 1.28%   |
| Quanta Chromebook HD Camera                         | 1         | 1.28%   |
| Microdia Webcam Vitade AF                           | 1         | 1.28%   |
| Microdia Webcam                                     | 1         | 1.28%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.28%   |
| Microdia 1.3 MPixel Integrated Webcam               | 1         | 1.28%   |
| Lite-On HP Webcam                                   | 1         | 1.28%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 1.28%   |
| Lenovo Integrated Webcam                            | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 38.46%  |
| Upek                  | 3         | 23.08%  |
| STMicroelectronics    | 2         | 15.38%  |
| AuthenTec             | 2         | 15.38%  |
| LighTuning Technology | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 23.08%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 15.38%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 7.69%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.69%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 7.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 7.69%   |
| AuthenTec Fingerprint Sensor                           | 1         | 7.69%   |
| AuthenTec AES2810                                      | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 4         | 80%     |
| O2 Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 60%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 69        | 75%     |
| 1     | 22        | 23.91%  |
| 2     | 1         | 1.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 13        | 54.17%  |
| Chipcard           | 5         | 20.83%  |
| Camera             | 2         | 8.33%   |
| Storage            | 1         | 4.17%   |
| Network            | 1         | 4.17%   |
| Graphics card      | 1         | 4.17%   |
| Bluetooth          | 1         | 4.17%   |

