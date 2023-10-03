Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

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

Total: 5382

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [e0cdb74f25](https://linux-hardware.org/?probe=e0cdb74f25) | Oct 01, 2023 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [d9750c9040](https://linux-hardware.org/?probe=d9750c9040) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| Acer          | Predator G3610              | Desktop     | [cddfa514ba](https://linux-hardware.org/?probe=cddfa514ba) | Sep 30, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [c93af00811](https://linux-hardware.org/?probe=c93af00811) | Sep 30, 2023 |
| MP            | MS-7848                     | Desktop     | [63d5662351](https://linux-hardware.org/?probe=63d5662351) | Sep 30, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [237492c356](https://linux-hardware.org/?probe=237492c356) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [145f7eccd3](https://linux-hardware.org/?probe=145f7eccd3) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | Notebook    | [e9dd0291e0](https://linux-hardware.org/?probe=e9dd0291e0) | Sep 29, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [8ba160ee59](https://linux-hardware.org/?probe=8ba160ee59) | Sep 29, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [4aa521a31f](https://linux-hardware.org/?probe=4aa521a31f) | Sep 29, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | Notebook    | [4f74530d68](https://linux-hardware.org/?probe=4f74530d68) | Sep 28, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | Notebook    | [5fb1e549ea](https://linux-hardware.org/?probe=5fb1e549ea) | Sep 28, 2023 |
| HP            | 2B35                        | Desktop     | [2f63f14724](https://linux-hardware.org/?probe=2f63f14724) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ce3a9f8960](https://linux-hardware.org/?probe=ce3a9f8960) | Sep 28, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [c717c1ab13](https://linux-hardware.org/?probe=c717c1ab13) | Sep 28, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f6c6bfc3fe](https://linux-hardware.org/?probe=f6c6bfc3fe) | Sep 27, 2023 |
| Lenovo        | ThinkPad E14 20RA0050US     | Notebook    | [097539dde8](https://linux-hardware.org/?probe=097539dde8) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | Notebook    | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| Intel         | X79G V2.x                   | Desktop     | [3d001a09ab](https://linux-hardware.org/?probe=3d001a09ab) | Sep 27, 2023 |
| HP            | Notebook                    | Notebook    | [4690fda15e](https://linux-hardware.org/?probe=4690fda15e) | Sep 27, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [811818acb8](https://linux-hardware.org/?probe=811818acb8) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [e7e87a1269](https://linux-hardware.org/?probe=e7e87a1269) | Sep 26, 2023 |
| Dell          | Inspiron 5459               | Notebook    | [1095c770f0](https://linux-hardware.org/?probe=1095c770f0) | Sep 26, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [0c8a57738d](https://linux-hardware.org/?probe=0c8a57738d) | Sep 25, 2023 |
| AZW           | SER                         | Mini pc     | [8e73904b3c](https://linux-hardware.org/?probe=8e73904b3c) | Sep 25, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a778013e21](https://linux-hardware.org/?probe=a778013e21) | Sep 25, 2023 |
| Intel         | W7645                       | Notebook    | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [29feb62e32](https://linux-hardware.org/?probe=29feb62e32) | Sep 25, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [863dfa9b96](https://linux-hardware.org/?probe=863dfa9b96) | Sep 25, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [1bee981c70](https://linux-hardware.org/?probe=1bee981c70) | Sep 25, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [7c901ae7fd](https://linux-hardware.org/?probe=7c901ae7fd) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | Notebook    | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| Alienware     | M17x                        | Notebook    | [5c6b700486](https://linux-hardware.org/?probe=5c6b700486) | Sep 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [6d75f2f29b](https://linux-hardware.org/?probe=6d75f2f29b) | Sep 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [f2a543d0dd](https://linux-hardware.org/?probe=f2a543d0dd) | Sep 24, 2023 |
| Sary          | Tab2                        | Tablet      | [7078e2b899](https://linux-hardware.org/?probe=7078e2b899) | Sep 23, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [fdfd7f2e50](https://linux-hardware.org/?probe=fdfd7f2e50) | Sep 23, 2023 |
| Sary          | Tab2                        | Tablet      | [913ec00764](https://linux-hardware.org/?probe=913ec00764) | Sep 23, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [6897fc6f5a](https://linux-hardware.org/?probe=6897fc6f5a) | Sep 23, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [fd3ce44501](https://linux-hardware.org/?probe=fd3ce44501) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [e2c17f3a64](https://linux-hardware.org/?probe=e2c17f3a64) | Sep 23, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [58b289a69d](https://linux-hardware.org/?probe=58b289a69d) | Sep 23, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | Notebook    | [8b5a2354c5](https://linux-hardware.org/?probe=8b5a2354c5) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e513362f71](https://linux-hardware.org/?probe=e513362f71) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | Notebook    | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [81bf9d5194](https://linux-hardware.org/?probe=81bf9d5194) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [7ecfb9c56f](https://linux-hardware.org/?probe=7ecfb9c56f) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [47e5429752](https://linux-hardware.org/?probe=47e5429752) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [a35f78cead](https://linux-hardware.org/?probe=a35f78cead) | Sep 21, 2023 |
| AZW           | MINI S 10                   | Desktop     | [e393d95960](https://linux-hardware.org/?probe=e393d95960) | Sep 21, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [cc25c24fa5](https://linux-hardware.org/?probe=cc25c24fa5) | Sep 21, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d92a4fb2af](https://linux-hardware.org/?probe=d92a4fb2af) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | Notebook    | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| Acer          | Aspire VN7-572G             | Notebook    | [8936ef0637](https://linux-hardware.org/?probe=8936ef0637) | Sep 21, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [e57a830f9c](https://linux-hardware.org/?probe=e57a830f9c) | Sep 21, 2023 |
| Lenovo        | ThinkPad T570 20HAS1PC00    | Notebook    | [218325e9e3](https://linux-hardware.org/?probe=218325e9e3) | Sep 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | Notebook    | [85a0203a02](https://linux-hardware.org/?probe=85a0203a02) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [dd7f2cf2b2](https://linux-hardware.org/?probe=dd7f2cf2b2) | Sep 20, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | Notebook    | [c96d3bf498](https://linux-hardware.org/?probe=c96d3bf498) | Sep 20, 2023 |
| Lenovo        | H320 10044                  | Desktop     | [bf4ffce3e9](https://linux-hardware.org/?probe=bf4ffce3e9) | Sep 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [776633dd59](https://linux-hardware.org/?probe=776633dd59) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [fcdaf47870](https://linux-hardware.org/?probe=fcdaf47870) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4dc880c6f](https://linux-hardware.org/?probe=e4dc880c6f) | Sep 20, 2023 |
| Dell          | 0RW199                      | Desktop     | [2857c6ada1](https://linux-hardware.org/?probe=2857c6ada1) | Sep 20, 2023 |
| Gigabyte      | Z790 UD AC                  | Desktop     | [83af285806](https://linux-hardware.org/?probe=83af285806) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [3d4f35cc26](https://linux-hardware.org/?probe=3d4f35cc26) | Sep 19, 2023 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [fcd8ef31df](https://linux-hardware.org/?probe=fcd8ef31df) | Sep 19, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [9fb8b99e70](https://linux-hardware.org/?probe=9fb8b99e70) | Sep 19, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [ca70cb035f](https://linux-hardware.org/?probe=ca70cb035f) | Sep 19, 2023 |
| Biostar       | H61MLC                      | Desktop     | [154ead8447](https://linux-hardware.org/?probe=154ead8447) | Sep 19, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [f45c7732e3](https://linux-hardware.org/?probe=f45c7732e3) | Sep 19, 2023 |
| AZW           | GTR V21                     | Desktop     | [5066e153f8](https://linux-hardware.org/?probe=5066e153f8) | Sep 19, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [5ec304bdb6](https://linux-hardware.org/?probe=5ec304bdb6) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [d03b8c1860](https://linux-hardware.org/?probe=d03b8c1860) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [202375fbb7](https://linux-hardware.org/?probe=202375fbb7) | Sep 18, 2023 |
| HP            | 3047h                       | Desktop     | [a955e9b6c6](https://linux-hardware.org/?probe=a955e9b6c6) | Sep 17, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [9e7069cdc3](https://linux-hardware.org/?probe=9e7069cdc3) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | Notebook    | [065988c338](https://linux-hardware.org/?probe=065988c338) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | Notebook    | [1a9e79b92e](https://linux-hardware.org/?probe=1a9e79b92e) | Sep 17, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [08ed0347db](https://linux-hardware.org/?probe=08ed0347db) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [d4d891ca35](https://linux-hardware.org/?probe=d4d891ca35) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [e639402c30](https://linux-hardware.org/?probe=e639402c30) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [b42ad40603](https://linux-hardware.org/?probe=b42ad40603) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [3a230dc10f](https://linux-hardware.org/?probe=3a230dc10f) | Sep 16, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3774dfea8e](https://linux-hardware.org/?probe=3774dfea8e) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [87f26cde55](https://linux-hardware.org/?probe=87f26cde55) | Sep 16, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [8913a6c47f](https://linux-hardware.org/?probe=8913a6c47f) | Sep 16, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [72503b214c](https://linux-hardware.org/?probe=72503b214c) | Sep 16, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [16c14700d3](https://linux-hardware.org/?probe=16c14700d3) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [00fd2287c0](https://linux-hardware.org/?probe=00fd2287c0) | Sep 16, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [f6be487f38](https://linux-hardware.org/?probe=f6be487f38) | Sep 16, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2fa5c8bb34](https://linux-hardware.org/?probe=2fa5c8bb34) | Sep 16, 2023 |
| ASUSTek       | K54C                        | Notebook    | [23a000c4d4](https://linux-hardware.org/?probe=23a000c4d4) | Sep 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [5cd83bcad9](https://linux-hardware.org/?probe=5cd83bcad9) | Sep 15, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2c412a10ca](https://linux-hardware.org/?probe=2c412a10ca) | Sep 15, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [def911de73](https://linux-hardware.org/?probe=def911de73) | Sep 14, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [83cb90361c](https://linux-hardware.org/?probe=83cb90361c) | Sep 14, 2023 |
| Itautec       | Infoway                     | Notebook    | [d4a8bc6420](https://linux-hardware.org/?probe=d4a8bc6420) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| HP            | Notebook                    | Notebook    | [29f1834722](https://linux-hardware.org/?probe=29f1834722) | Sep 14, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [bba9e61120](https://linux-hardware.org/?probe=bba9e61120) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [40aee3739e](https://linux-hardware.org/?probe=40aee3739e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [9bbec30b2f](https://linux-hardware.org/?probe=9bbec30b2f) | Sep 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [3cba209625](https://linux-hardware.org/?probe=3cba209625) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [4dcd4e8234](https://linux-hardware.org/?probe=4dcd4e8234) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [cbfa4c2641](https://linux-hardware.org/?probe=cbfa4c2641) | Sep 13, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [b94c2a0420](https://linux-hardware.org/?probe=b94c2a0420) | Sep 13, 2023 |
| Acer          | Aspire 5750ZG               | Notebook    | [c9ce4cde54](https://linux-hardware.org/?probe=c9ce4cde54) | Sep 13, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [32b69241bf](https://linux-hardware.org/?probe=32b69241bf) | Sep 13, 2023 |
| Sony          | VPCEB1E1E                   | Notebook    | [cbd095ee01](https://linux-hardware.org/?probe=cbd095ee01) | Sep 12, 2023 |
| Acer          | Aspire 5750ZG               | Notebook    | [9029730ffb](https://linux-hardware.org/?probe=9029730ffb) | Sep 12, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [8ddb560fdc](https://linux-hardware.org/?probe=8ddb560fdc) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [5358fa25ef](https://linux-hardware.org/?probe=5358fa25ef) | Sep 12, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | Desktop     | [e4f73d159c](https://linux-hardware.org/?probe=e4f73d159c) | Sep 12, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [8ddbf6665f](https://linux-hardware.org/?probe=8ddbf6665f) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [9fc04871b0](https://linux-hardware.org/?probe=9fc04871b0) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [a80cffbabe](https://linux-hardware.org/?probe=a80cffbabe) | Sep 11, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [5907e59551](https://linux-hardware.org/?probe=5907e59551) | Sep 11, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [21baf66690](https://linux-hardware.org/?probe=21baf66690) | Sep 11, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | Desktop     | [c57a3a012d](https://linux-hardware.org/?probe=c57a3a012d) | Sep 11, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e7c7395c7b](https://linux-hardware.org/?probe=e7c7395c7b) | Sep 11, 2023 |
| ASUSTek       | PRIME H370-A                | Desktop     | [c757d0e2c3](https://linux-hardware.org/?probe=c757d0e2c3) | Sep 11, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [39a15ba0ca](https://linux-hardware.org/?probe=39a15ba0ca) | Sep 10, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [26fc33cb75](https://linux-hardware.org/?probe=26fc33cb75) | Sep 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| ASUSTek       | X541UA                      | Notebook    | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [a8db1b43ce](https://linux-hardware.org/?probe=a8db1b43ce) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [26b9818094](https://linux-hardware.org/?probe=26b9818094) | Sep 09, 2023 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [3ee6c9a460](https://linux-hardware.org/?probe=3ee6c9a460) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [6f66e35ec3](https://linux-hardware.org/?probe=6f66e35ec3) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [9306917366](https://linux-hardware.org/?probe=9306917366) | Sep 09, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [382cd978ab](https://linux-hardware.org/?probe=382cd978ab) | Sep 08, 2023 |
| HP            | 8523 A01                    | Mini pc     | [b050702ce4](https://linux-hardware.org/?probe=b050702ce4) | Sep 08, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [c936953cf7](https://linux-hardware.org/?probe=c936953cf7) | Sep 08, 2023 |
| Lenovo        | ThinkPad T430 2349H2G       | Notebook    | [1d9d7c7f78](https://linux-hardware.org/?probe=1d9d7c7f78) | Sep 08, 2023 |
| HP            | 8299                        | Desktop     | [df4048bcc4](https://linux-hardware.org/?probe=df4048bcc4) | Sep 08, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [97d9faccab](https://linux-hardware.org/?probe=97d9faccab) | Sep 07, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [3112302ff6](https://linux-hardware.org/?probe=3112302ff6) | Sep 07, 2023 |
| Acer          | Aspire X1470                | Desktop     | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | Desktop     | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [002bdcd34d](https://linux-hardware.org/?probe=002bdcd34d) | Sep 07, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [125a7f7c0d](https://linux-hardware.org/?probe=125a7f7c0d) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [6bb77310bf](https://linux-hardware.org/?probe=6bb77310bf) | Sep 06, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [0428af4d14](https://linux-hardware.org/?probe=0428af4d14) | Sep 06, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [415ba1cfc1](https://linux-hardware.org/?probe=415ba1cfc1) | Sep 06, 2023 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [a7e1067ce7](https://linux-hardware.org/?probe=a7e1067ce7) | Sep 06, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [5e6e5cd047](https://linux-hardware.org/?probe=5e6e5cd047) | Sep 06, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [53bfbec77e](https://linux-hardware.org/?probe=53bfbec77e) | Sep 06, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3227a8a6bc](https://linux-hardware.org/?probe=3227a8a6bc) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Toshiba       | Satellite A210              | Notebook    | [54f5fb9c03](https://linux-hardware.org/?probe=54f5fb9c03) | Sep 06, 2023 |
| Alienware     | 0446JC A01                  | Desktop     | [d0c3088707](https://linux-hardware.org/?probe=d0c3088707) | Sep 06, 2023 |
| Framework     | Laptop                      | Notebook    | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| HP            | 0B54h D                     | Desktop     | [6fc93ef4ee](https://linux-hardware.org/?probe=6fc93ef4ee) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [f8ec276ea3](https://linux-hardware.org/?probe=f8ec276ea3) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [788841792b](https://linux-hardware.org/?probe=788841792b) | Sep 04, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [7f0254a775](https://linux-hardware.org/?probe=7f0254a775) | Sep 04, 2023 |
| Toshiba       | Satellite C70D-A            | Notebook    | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [371c148953](https://linux-hardware.org/?probe=371c148953) | Sep 04, 2023 |
| Dell          | Latitude E6530              | Notebook    | [e1aa22b8b9](https://linux-hardware.org/?probe=e1aa22b8b9) | Sep 04, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [78a354984d](https://linux-hardware.org/?probe=78a354984d) | Sep 04, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [ae79e6a689](https://linux-hardware.org/?probe=ae79e6a689) | Sep 04, 2023 |
| Dell          | G15 5511                    | Notebook    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [2c9b64c445](https://linux-hardware.org/?probe=2c9b64c445) | Sep 03, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [f4c15b0551](https://linux-hardware.org/?probe=f4c15b0551) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | Notebook    | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [9845368fc2](https://linux-hardware.org/?probe=9845368fc2) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [eee58fd067](https://linux-hardware.org/?probe=eee58fd067) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6215db2c5a](https://linux-hardware.org/?probe=6215db2c5a) | Sep 02, 2023 |
| AMI           | Intel                       | Convertible | [dd24abacfc](https://linux-hardware.org/?probe=dd24abacfc) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [f05f130786](https://linux-hardware.org/?probe=f05f130786) | Sep 02, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [7f9db7db99](https://linux-hardware.org/?probe=7f9db7db99) | Sep 01, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [027ceec09f](https://linux-hardware.org/?probe=027ceec09f) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Intel         | X79M-S                      | Desktop     | [a6952c68e4](https://linux-hardware.org/?probe=a6952c68e4) | Sep 01, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [24743bf01d](https://linux-hardware.org/?probe=24743bf01d) | Sep 01, 2023 |
| Dell          | Latitude 5400               | Notebook    | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | Notebook    | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| HP            | ProBook 4740s               | Notebook    | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [be8b002a45](https://linux-hardware.org/?probe=be8b002a45) | Aug 31, 2023 |
| HP            | 15                          | Notebook    | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| HP            | Pavilion dv4                | Notebook    | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Sony          | VPCEE23FX                   | Notebook    | [65714e4d48](https://linux-hardware.org/?probe=65714e4d48) | Aug 30, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [035f2909a1](https://linux-hardware.org/?probe=035f2909a1) | Aug 30, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [d963970016](https://linux-hardware.org/?probe=d963970016) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| HP            | 8054                        | Desktop     | [f73271d96e](https://linux-hardware.org/?probe=f73271d96e) | Aug 30, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [3fb03adafb](https://linux-hardware.org/?probe=3fb03adafb) | Aug 29, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [01701d7ab0](https://linux-hardware.org/?probe=01701d7ab0) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [6da5e2d119](https://linux-hardware.org/?probe=6da5e2d119) | Aug 29, 2023 |
| Dell          | Precision 7710              | Notebook    | [9b92626f63](https://linux-hardware.org/?probe=9b92626f63) | Aug 29, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [eba7f74017](https://linux-hardware.org/?probe=eba7f74017) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | Notebook    | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [fffbca3973](https://linux-hardware.org/?probe=fffbca3973) | Aug 28, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [8e13da67ed](https://linux-hardware.org/?probe=8e13da67ed) | Aug 28, 2023 |
| Intel         | H61                         | Desktop     | [9e5ed4db62](https://linux-hardware.org/?probe=9e5ed4db62) | Aug 28, 2023 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [5268d75df2](https://linux-hardware.org/?probe=5268d75df2) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | Notebook    | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | Notebook    | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [cb2419d3df](https://linux-hardware.org/?probe=cb2419d3df) | Aug 27, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4357727561](https://linux-hardware.org/?probe=4357727561) | Aug 27, 2023 |
| TERRA         | TERRAPC                     | Notebook    | [2031fd343b](https://linux-hardware.org/?probe=2031fd343b) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [929efec703](https://linux-hardware.org/?probe=929efec703) | Aug 27, 2023 |
| eMachines     | EL1352                      | Desktop     | [5f9258beb2](https://linux-hardware.org/?probe=5f9258beb2) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [e212f5bc28](https://linux-hardware.org/?probe=e212f5bc28) | Aug 25, 2023 |
| Google        | Rammus                      | Notebook    | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| GuoGuang      | IC2M1028N                   | Desktop     | [ffcd5b9fa5](https://linux-hardware.org/?probe=ffcd5b9fa5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| Samsung       | 960QFG                      | Convertible | [400b83d634](https://linux-hardware.org/?probe=400b83d634) | Aug 24, 2023 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [42d3a714ac](https://linux-hardware.org/?probe=42d3a714ac) | Aug 24, 2023 |
| TERRA         | TERRAPC                     | Notebook    | [b33c6ce6e8](https://linux-hardware.org/?probe=b33c6ce6e8) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | ProBook 4740s               | Notebook    | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| AZW           | MINI S                      | Desktop     | [7712e558c5](https://linux-hardware.org/?probe=7712e558c5) | Aug 24, 2023 |
| AZW           | MINI S                      | Desktop     | [6296a4f71d](https://linux-hardware.org/?probe=6296a4f71d) | Aug 24, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [64859dd75d](https://linux-hardware.org/?probe=64859dd75d) | Aug 24, 2023 |
| HP            | 8299                        | Desktop     | [aa27bed4f1](https://linux-hardware.org/?probe=aa27bed4f1) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [82c63f13d1](https://linux-hardware.org/?probe=82c63f13d1) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [1aee954611](https://linux-hardware.org/?probe=1aee954611) | Aug 22, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | Notebook    | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [9b52370ec1](https://linux-hardware.org/?probe=9b52370ec1) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [51e91dd03e](https://linux-hardware.org/?probe=51e91dd03e) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [a440d57d28](https://linux-hardware.org/?probe=a440d57d28) | Aug 21, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [409855b61b](https://linux-hardware.org/?probe=409855b61b) | Aug 21, 2023 |
| Dell          | Precision M4700             | Notebook    | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7a206bdd57](https://linux-hardware.org/?probe=7a206bdd57) | Aug 21, 2023 |
| HP            | Notebook                    | Notebook    | [5b7ff7f278](https://linux-hardware.org/?probe=5b7ff7f278) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Dell          | Latitude 3350               | Notebook    | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | Unknown                     | Notebook    | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | Notebook    | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Alienware     | 17                          | Notebook    | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [2ac06099d8](https://linux-hardware.org/?probe=2ac06099d8) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [f97c8a25c5](https://linux-hardware.org/?probe=f97c8a25c5) | Aug 19, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [f06dbc1b8c](https://linux-hardware.org/?probe=f06dbc1b8c) | Aug 19, 2023 |
| HP            | 3047h                       | Desktop     | [91d9eaa1de](https://linux-hardware.org/?probe=91d9eaa1de) | Aug 19, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [d109b04177](https://linux-hardware.org/?probe=d109b04177) | Aug 19, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| ASUSTek       | X550ZA                      | Notebook    | [7f23195701](https://linux-hardware.org/?probe=7f23195701) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| HP            | 3047h                       | Desktop     | [a4aa888c24](https://linux-hardware.org/?probe=a4aa888c24) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [d14c477dc9](https://linux-hardware.org/?probe=d14c477dc9) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [7092a32ce5](https://linux-hardware.org/?probe=7092a32ce5) | Aug 17, 2023 |
| Dell          | G3 3579                     | Notebook    | [58866ca1fb](https://linux-hardware.org/?probe=58866ca1fb) | Aug 17, 2023 |
| HP            | 3032h                       | Desktop     | [34a300f540](https://linux-hardware.org/?probe=34a300f540) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | Notebook    | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | Notebook    | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Intel         | X79M-S                      | Desktop     | [d79895d82c](https://linux-hardware.org/?probe=d79895d82c) | Aug 17, 2023 |
| Google        | Coral                       | Notebook    | [f8ed9b3bda](https://linux-hardware.org/?probe=f8ed9b3bda) | Aug 17, 2023 |
| Lenovo        | ThinkPad T480 20L5S04F00    | Notebook    | [7eb670d219](https://linux-hardware.org/?probe=7eb670d219) | Aug 17, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [de9a1cb848](https://linux-hardware.org/?probe=de9a1cb848) | Aug 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [7c1a42d442](https://linux-hardware.org/?probe=7c1a42d442) | Aug 17, 2023 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [78e12f014e](https://linux-hardware.org/?probe=78e12f014e) | Aug 17, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [50731e7c54](https://linux-hardware.org/?probe=50731e7c54) | Aug 16, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [50b5957370](https://linux-hardware.org/?probe=50b5957370) | Aug 16, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [b31bf50c6e](https://linux-hardware.org/?probe=b31bf50c6e) | Aug 16, 2023 |
| Dell          | Latitude D630               | Notebook    | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3da24e6a41](https://linux-hardware.org/?probe=3da24e6a41) | Aug 15, 2023 |
| HP            | 15                          | Notebook    | [645730bff3](https://linux-hardware.org/?probe=645730bff3) | Aug 15, 2023 |
| HP            | 15                          | Notebook    | [08fc74cb7b](https://linux-hardware.org/?probe=08fc74cb7b) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | Notebook    | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| Biostar       | H410MH                      | Desktop     | [abe98ae584](https://linux-hardware.org/?probe=abe98ae584) | Aug 15, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [bb4bf558dd](https://linux-hardware.org/?probe=bb4bf558dd) | Aug 15, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [e79cdd0ba3](https://linux-hardware.org/?probe=e79cdd0ba3) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | Notebook    | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Medion        | E15301                      | Notebook    | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [102a6b136f](https://linux-hardware.org/?probe=102a6b136f) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f09f15784f](https://linux-hardware.org/?probe=f09f15784f) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [dea6e2f8b8](https://linux-hardware.org/?probe=dea6e2f8b8) | Aug 13, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [7e47b7128b](https://linux-hardware.org/?probe=7e47b7128b) | Aug 13, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [777c4f7fb8](https://linux-hardware.org/?probe=777c4f7fb8) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [1034423357](https://linux-hardware.org/?probe=1034423357) | Aug 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [c692882ce4](https://linux-hardware.org/?probe=c692882ce4) | Aug 13, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [ff8bec8b75](https://linux-hardware.org/?probe=ff8bec8b75) | Aug 12, 2023 |
| AMI           | Unknown                     | Notebook    | [326999bd6b](https://linux-hardware.org/?probe=326999bd6b) | Aug 12, 2023 |
| AMI           | Unknown                     | Notebook    | [614b443c5c](https://linux-hardware.org/?probe=614b443c5c) | Aug 12, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [17179d26d5](https://linux-hardware.org/?probe=17179d26d5) | Aug 12, 2023 |
| HP            | 350 G2                      | Notebook    | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| MSI           | 2AE0                        | Desktop     | [b8a2a0eb5c](https://linux-hardware.org/?probe=b8a2a0eb5c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [71f554fd2c](https://linux-hardware.org/?probe=71f554fd2c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [edd42a9a6d](https://linux-hardware.org/?probe=edd42a9a6d) | Aug 12, 2023 |
| Lenovo        | IdeaPad Duet 3 11IAN8 82... | Tablet      | [b61e23d1ec](https://linux-hardware.org/?probe=b61e23d1ec) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Acer          | One Z1402                   | Notebook    | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [d35bac0620](https://linux-hardware.org/?probe=d35bac0620) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [fb7d0009fd](https://linux-hardware.org/?probe=fb7d0009fd) | Aug 12, 2023 |
| Dell          | 0XKD8M A00                  | All in one  | [6cbd6d691c](https://linux-hardware.org/?probe=6cbd6d691c) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [b68d99fd89](https://linux-hardware.org/?probe=b68d99fd89) | Aug 11, 2023 |
| HP            | 3032h                       | Desktop     | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [48a0f64b34](https://linux-hardware.org/?probe=48a0f64b34) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| HP            | 350 G2                      | Notebook    | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [a2756bd55e](https://linux-hardware.org/?probe=a2756bd55e) | Aug 10, 2023 |
| Intel         | DZ68BC AAG30742-401         | Desktop     | [9bf37df045](https://linux-hardware.org/?probe=9bf37df045) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | 350 G2                      | Notebook    | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [6e9ca3c833](https://linux-hardware.org/?probe=6e9ca3c833) | Aug 09, 2023 |
| HP            | 3032h                       | Desktop     | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| HP            | Presario CQ56               | Notebook    | [cf373b9083](https://linux-hardware.org/?probe=cf373b9083) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [7c59be984f](https://linux-hardware.org/?probe=7c59be984f) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [9c789edd52](https://linux-hardware.org/?probe=9c789edd52) | Aug 08, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [2e30c62b25](https://linux-hardware.org/?probe=2e30c62b25) | Aug 08, 2023 |
| Intel         | X79M-S                      | Desktop     | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | Notebook    | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | Notebook    | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c95daf7007](https://linux-hardware.org/?probe=c95daf7007) | Aug 06, 2023 |
| Pegatron      | IPMMB-MQ1                   | Desktop     | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [c40308638c](https://linux-hardware.org/?probe=c40308638c) | Aug 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [1af709c14e](https://linux-hardware.org/?probe=1af709c14e) | Aug 05, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [3bc330734d](https://linux-hardware.org/?probe=3bc330734d) | Aug 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [5d998a099e](https://linux-hardware.org/?probe=5d998a099e) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [e57d71e056](https://linux-hardware.org/?probe=e57d71e056) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [8ee9cccace](https://linux-hardware.org/?probe=8ee9cccace) | Aug 05, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [7ffb6822e6](https://linux-hardware.org/?probe=7ffb6822e6) | Aug 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| Itautec       | Infoway                     | Notebook    | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [3793d876eb](https://linux-hardware.org/?probe=3793d876eb) | Aug 04, 2023 |
| GPD           | G1621-02                    | Notebook    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [cf6d77d650](https://linux-hardware.org/?probe=cf6d77d650) | Aug 04, 2023 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [9f27152a86](https://linux-hardware.org/?probe=9f27152a86) | Aug 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [955c961132](https://linux-hardware.org/?probe=955c961132) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f27f9b2a7f](https://linux-hardware.org/?probe=f27f9b2a7f) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [8193f810ab](https://linux-hardware.org/?probe=8193f810ab) | Aug 03, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [35cf0fd859](https://linux-hardware.org/?probe=35cf0fd859) | Aug 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| HP            | 89B5 A                      | Desktop     | [cb6f36f32c](https://linux-hardware.org/?probe=cb6f36f32c) | Aug 02, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| HP            | Pavilion dv7                | Notebook    | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [ee5b34b232](https://linux-hardware.org/?probe=ee5b34b232) | Aug 02, 2023 |
| ASUSTek       | K54C                        | Notebook    | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [731a8b0e31](https://linux-hardware.org/?probe=731a8b0e31) | Aug 02, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| AZW           | GTR V01                     | Mini pc     | [f3f9a4366b](https://linux-hardware.org/?probe=f3f9a4366b) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [957e1805d3](https://linux-hardware.org/?probe=957e1805d3) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [a522e7336c](https://linux-hardware.org/?probe=a522e7336c) | Aug 01, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| HP            | 1496                        | Desktop     | [24863488f0](https://linux-hardware.org/?probe=24863488f0) | Aug 01, 2023 |
| MSI           | GE72MVR 7RG                 | Notebook    | [d935650def](https://linux-hardware.org/?probe=d935650def) | Jul 31, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [d1651e3e43](https://linux-hardware.org/?probe=d1651e3e43) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [90dce7a9cf](https://linux-hardware.org/?probe=90dce7a9cf) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | Notebook    | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [b1125cd76c](https://linux-hardware.org/?probe=b1125cd76c) | Jul 29, 2023 |
| HP            | Pavilion dv4                | Notebook    | [47e9cba85c](https://linux-hardware.org/?probe=47e9cba85c) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| ASUSTek       | K53U                        | Notebook    | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [bc92202f16](https://linux-hardware.org/?probe=bc92202f16) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [310207e0fd](https://linux-hardware.org/?probe=310207e0fd) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [7583695051](https://linux-hardware.org/?probe=7583695051) | Jul 28, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [fe7c4fd681](https://linux-hardware.org/?probe=fe7c4fd681) | Jul 28, 2023 |
| Google        | Edgar                       | Notebook    | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [9e892612ab](https://linux-hardware.org/?probe=9e892612ab) | Jul 28, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| HP            | 3397                        | Desktop     | [e61ccd6dbf](https://linux-hardware.org/?probe=e61ccd6dbf) | Jul 27, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [b7ce548e5b](https://linux-hardware.org/?probe=b7ce548e5b) | Jul 27, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [e7fdf45ff0](https://linux-hardware.org/?probe=e7fdf45ff0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2f12124bed](https://linux-hardware.org/?probe=2f12124bed) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| MP            | MS-7848                     | Desktop     | [3dd9f22548](https://linux-hardware.org/?probe=3dd9f22548) | Jul 26, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [238c98ee81](https://linux-hardware.org/?probe=238c98ee81) | Jul 26, 2023 |
| Lenovo        | No DPK                      | All in one  | [1b1fa8ccec](https://linux-hardware.org/?probe=1b1fa8ccec) | Jul 26, 2023 |
| Acer          | Elena                       | Desktop     | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [1b062f3c31](https://linux-hardware.org/?probe=1b062f3c31) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [bca4424b5d](https://linux-hardware.org/?probe=bca4424b5d) | Jul 26, 2023 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [1355a4f2f4](https://linux-hardware.org/?probe=1355a4f2f4) | Jul 25, 2023 |
| Acer          | TravelMate B113             | Notebook    | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [7eda84257a](https://linux-hardware.org/?probe=7eda84257a) | Jul 25, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [47fec524e4](https://linux-hardware.org/?probe=47fec524e4) | Jul 25, 2023 |
| Dell          | Inspiron 3721               | Notebook    | [a0874e626b](https://linux-hardware.org/?probe=a0874e626b) | Jul 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [431abc64d1](https://linux-hardware.org/?probe=431abc64d1) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | Notebook    | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Microtech     | ebookPro                    | Notebook    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| HP            | 8350                        | Desktop     | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |
| Acer          | AO756                       | Notebook    | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c271fa70b8](https://linux-hardware.org/?probe=c271fa70b8) | Jul 23, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [19356a725e](https://linux-hardware.org/?probe=19356a725e) | Jul 22, 2023 |
| HP            | Pavilion dv4                | Notebook    | [4854c4b18c](https://linux-hardware.org/?probe=4854c4b18c) | Jul 22, 2023 |
| Dell          | 0MN1TX A04                  | Desktop     | [4ff31f4185](https://linux-hardware.org/?probe=4ff31f4185) | Jul 22, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [b8cf03e7b7](https://linux-hardware.org/?probe=b8cf03e7b7) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [87b85c2e28](https://linux-hardware.org/?probe=87b85c2e28) | Jul 22, 2023 |
| Medion        | E15301                      | Notebook    | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| ASRock        | B85M                        | Desktop     | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| AMI           | Cherry Trail CR             | Notebook    | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| HP            | 3048h                       | Desktop     | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| Dell          | Latitude E6440              | Notebook    | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| HP            | 3047h                       | Desktop     | [07de35877b](https://linux-hardware.org/?probe=07de35877b) | Jul 21, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [9afd0f1d0f](https://linux-hardware.org/?probe=9afd0f1d0f) | Jul 21, 2023 |
| Dell          | Latitude 3520               | Notebook    | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| HP            | 15                          | Notebook    | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [35c4e6ad97](https://linux-hardware.org/?probe=35c4e6ad97) | Jul 20, 2023 |
| HP            | 8767 A                      | Desktop     | [d5275f1025](https://linux-hardware.org/?probe=d5275f1025) | Jul 20, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [3832c8f626](https://linux-hardware.org/?probe=3832c8f626) | Jul 20, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [71f9656ab2](https://linux-hardware.org/?probe=71f9656ab2) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | Notebook    | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [da1c963814](https://linux-hardware.org/?probe=da1c963814) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [02008985ce](https://linux-hardware.org/?probe=02008985ce) | Jul 19, 2023 |
| Sony          | VPCEE23FX                   | Notebook    | [2cb9bf9d50](https://linux-hardware.org/?probe=2cb9bf9d50) | Jul 18, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [8e01cf8f1e](https://linux-hardware.org/?probe=8e01cf8f1e) | Jul 17, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [9be017a8a3](https://linux-hardware.org/?probe=9be017a8a3) | Jul 16, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [71c4faf60f](https://linux-hardware.org/?probe=71c4faf60f) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Dell          | 04075X A00                  | All in one  | [46795bfa31](https://linux-hardware.org/?probe=46795bfa31) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [21bef8253a](https://linux-hardware.org/?probe=21bef8253a) | Jul 15, 2023 |
| Dell          | Latitude E4300              | Notebook    | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | Notebook    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [57b17e7ae1](https://linux-hardware.org/?probe=57b17e7ae1) | Jul 15, 2023 |
| Gigabyte      | Z370M AORUS Gaming-CF       | Desktop     | [64a0d52846](https://linux-hardware.org/?probe=64a0d52846) | Jul 15, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [d32668cf0c](https://linux-hardware.org/?probe=d32668cf0c) | Jul 15, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2f5c2842c2](https://linux-hardware.org/?probe=2f5c2842c2) | Jul 14, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [4155214585](https://linux-hardware.org/?probe=4155214585) | Jul 14, 2023 |
| Alienware     | M11xR3                      | Notebook    | [9397339221](https://linux-hardware.org/?probe=9397339221) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [35399aae18](https://linux-hardware.org/?probe=35399aae18) | Jul 14, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [622890c12a](https://linux-hardware.org/?probe=622890c12a) | Jul 14, 2023 |
| AZW           | SER                         | Mini pc     | [8fdb4e6f42](https://linux-hardware.org/?probe=8fdb4e6f42) | Jul 14, 2023 |
| AZW           | SER                         | Mini pc     | [537e7c9c94](https://linux-hardware.org/?probe=537e7c9c94) | Jul 13, 2023 |
| HP            | 15                          | Notebook    | [215a87518e](https://linux-hardware.org/?probe=215a87518e) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [81f693b5b0](https://linux-hardware.org/?probe=81f693b5b0) | Jul 12, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [b690698c10](https://linux-hardware.org/?probe=b690698c10) | Jul 12, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [d347a1b82e](https://linux-hardware.org/?probe=d347a1b82e) | Jul 12, 2023 |
| Lenovo        | ThinkPad 8 20BN001RMN       | Tablet      | [6801265f9f](https://linux-hardware.org/?probe=6801265f9f) | Jul 12, 2023 |
| HP            | 8299                        | Desktop     | [763cebf303](https://linux-hardware.org/?probe=763cebf303) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [7190b16550](https://linux-hardware.org/?probe=7190b16550) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7c6ad4407b](https://linux-hardware.org/?probe=7c6ad4407b) | Jul 11, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [c81c5855d4](https://linux-hardware.org/?probe=c81c5855d4) | Jul 11, 2023 |
| HP            | Compaq 2510p                | Notebook    | [a7cb1d43fb](https://linux-hardware.org/?probe=a7cb1d43fb) | Jul 11, 2023 |
| HP            | Pavilion g4                 | Notebook    | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ab81f36697](https://linux-hardware.org/?probe=ab81f36697) | Jul 11, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [8e5774c497](https://linux-hardware.org/?probe=8e5774c497) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| HP            | Compaq 2510p                | Notebook    | [98d500c68c](https://linux-hardware.org/?probe=98d500c68c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | Notebook    | [621eaf410c](https://linux-hardware.org/?probe=621eaf410c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | Notebook    | [3631291aa8](https://linux-hardware.org/?probe=3631291aa8) | Jul 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [2ed1092e31](https://linux-hardware.org/?probe=2ed1092e31) | Jul 10, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [6eb4d71389](https://linux-hardware.org/?probe=6eb4d71389) | Jul 10, 2023 |
| HP            | Notebook                    | Notebook    | [7d4bc75f38](https://linux-hardware.org/?probe=7d4bc75f38) | Jul 09, 2023 |
| ASUSTek       | K54C                        | Notebook    | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [213c80bbee](https://linux-hardware.org/?probe=213c80bbee) | Jul 09, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [938e9efd55](https://linux-hardware.org/?probe=938e9efd55) | Jul 09, 2023 |
| Unknown       | SLR-0308                    | Notebook    | [d5b0d30e8d](https://linux-hardware.org/?probe=d5b0d30e8d) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [be65f2aa45](https://linux-hardware.org/?probe=be65f2aa45) | Jul 08, 2023 |
| OTVOC         | N1                          | Notebook    | [1b4d619110](https://linux-hardware.org/?probe=1b4d619110) | Jul 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [7b62ed78d1](https://linux-hardware.org/?probe=7b62ed78d1) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | Notebook    | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [203ffa97b4](https://linux-hardware.org/?probe=203ffa97b4) | Jul 06, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [24a4044173](https://linux-hardware.org/?probe=24a4044173) | Jul 06, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [8a9c93e501](https://linux-hardware.org/?probe=8a9c93e501) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | Notebook    | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| Dell          | 0GFYJR A00                  | Server      | [573c8bd5bd](https://linux-hardware.org/?probe=573c8bd5bd) | Jul 06, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [774ebec1d8](https://linux-hardware.org/?probe=774ebec1d8) | Jul 05, 2023 |
| ASRock        | FP6D4-P1                    | Desktop     | [42b5bdcdd7](https://linux-hardware.org/?probe=42b5bdcdd7) | Jul 05, 2023 |
| Positivo      | POS-EIH61CE SIM             | Desktop     | [48b35c757d](https://linux-hardware.org/?probe=48b35c757d) | Jul 05, 2023 |
| Intel         | H55                         | Desktop     | [8f8ff68380](https://linux-hardware.org/?probe=8f8ff68380) | Jul 04, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [9bca67bb40](https://linux-hardware.org/?probe=9bca67bb40) | Jul 04, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| HP            | 21F5 0A                     | Desktop     | [bc7304ba1c](https://linux-hardware.org/?probe=bc7304ba1c) | Jul 04, 2023 |
| HP            | 2B3E                        | All in one  | [bfa310e490](https://linux-hardware.org/?probe=bfa310e490) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [452fe27c46](https://linux-hardware.org/?probe=452fe27c46) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [168d5b0b7b](https://linux-hardware.org/?probe=168d5b0b7b) | Jul 04, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [21adb87fbd](https://linux-hardware.org/?probe=21adb87fbd) | Jul 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7672f159bf](https://linux-hardware.org/?probe=7672f159bf) | Jul 03, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| HP            | 2B3E                        | All in one  | [c6f01baa52](https://linux-hardware.org/?probe=c6f01baa52) | Jul 03, 2023 |
| OTVOC         | N1                          | Notebook    | [833ed0c86b](https://linux-hardware.org/?probe=833ed0c86b) | Jul 02, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [729dbec695](https://linux-hardware.org/?probe=729dbec695) | Jul 02, 2023 |
| HP            | ENVY m6                     | Notebook    | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [2bc4b36c94](https://linux-hardware.org/?probe=2bc4b36c94) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | Desktop     | [c787bf91c3](https://linux-hardware.org/?probe=c787bf91c3) | Jul 02, 2023 |
| Unknown       | V00                         | Mini pc     | [ab56e54ced](https://linux-hardware.org/?probe=ab56e54ced) | Jul 01, 2023 |
| Unknown       | V00                         | Mini pc     | [36483eddb0](https://linux-hardware.org/?probe=36483eddb0) | Jul 01, 2023 |
| HP            | Compaq 6830s                | Notebook    | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| TrekStor      | YOURBOOK C11B               | Convertible | [8c2340f01f](https://linux-hardware.org/?probe=8c2340f01f) | Jul 01, 2023 |
| Win Elemen... | M9                          | Desktop     | [2e5ea821f1](https://linux-hardware.org/?probe=2e5ea821f1) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | Desktop     | [a4e29f77e5](https://linux-hardware.org/?probe=a4e29f77e5) | Jul 01, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [e47898dc3d](https://linux-hardware.org/?probe=e47898dc3d) | Jun 29, 2023 |
| MSI           | H61M-P31                    | Desktop     | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | Desktop     | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| HP            | ENVY m6                     | Notebook    | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| Dell          | Latitude E6400              | Notebook    | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [663ce69f30](https://linux-hardware.org/?probe=663ce69f30) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [73eab89788](https://linux-hardware.org/?probe=73eab89788) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | Notebook    | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DA50... | Notebook    | [b756e54029](https://linux-hardware.org/?probe=b756e54029) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [0a35c3c750](https://linux-hardware.org/?probe=0a35c3c750) | Jun 27, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [18ab778722](https://linux-hardware.org/?probe=18ab778722) | Jun 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [da86501858](https://linux-hardware.org/?probe=da86501858) | Jun 26, 2023 |
| Dell          | Latitude 3189               | Notebook    | [ad7c98c905](https://linux-hardware.org/?probe=ad7c98c905) | Jun 26, 2023 |
| Dell          | Latitude 3189               | Notebook    | [8547503af5](https://linux-hardware.org/?probe=8547503af5) | Jun 25, 2023 |
| Dell          | Latitude 3189               | Notebook    | [3f44430a36](https://linux-hardware.org/?probe=3f44430a36) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | Notebook    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [23134d6c71](https://linux-hardware.org/?probe=23134d6c71) | Jun 24, 2023 |
| Dell          | Latitude E6400              | Notebook    | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| ASUSTek       | P5B                         | Desktop     | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| Acer          | AOD270                      | Notebook    | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | Notebook    | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [1773c81302](https://linux-hardware.org/?probe=1773c81302) | Jun 23, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [80b535ff26](https://linux-hardware.org/?probe=80b535ff26) | Jun 23, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [177d2fe509](https://linux-hardware.org/?probe=177d2fe509) | Jun 22, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| Google        | Kefka                       | Notebook    | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [ae8c13c6fd](https://linux-hardware.org/?probe=ae8c13c6fd) | Jun 22, 2023 |
| Dell          | 0G9322                      | Desktop     | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| AZW           | SER                         | Mini pc     | [9ef166eb46](https://linux-hardware.org/?probe=9ef166eb46) | Jun 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [3d558ea9aa](https://linux-hardware.org/?probe=3d558ea9aa) | Jun 21, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [b28f58f09e](https://linux-hardware.org/?probe=b28f58f09e) | Jun 20, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [0d3af8114b](https://linux-hardware.org/?probe=0d3af8114b) | Jun 20, 2023 |
| HP            | ENVY m6                     | Notebook    | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [72ef7ff0aa](https://linux-hardware.org/?probe=72ef7ff0aa) | Jun 20, 2023 |
| Dell          | G7 7588                     | Notebook    | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [88d7f8992f](https://linux-hardware.org/?probe=88d7f8992f) | Jun 19, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [93587f51a9](https://linux-hardware.org/?probe=93587f51a9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | Notebook    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| AZW           | GTR V02                     | Desktop     | [f9bee18426](https://linux-hardware.org/?probe=f9bee18426) | Jun 19, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [46bd956cbf](https://linux-hardware.org/?probe=46bd956cbf) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [7546cac791](https://linux-hardware.org/?probe=7546cac791) | Jun 19, 2023 |
| ASUSTek       | P5LD2                       | Desktop     | [7038963b77](https://linux-hardware.org/?probe=7038963b77) | Jun 18, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | Notebook    | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [bb6859a141](https://linux-hardware.org/?probe=bb6859a141) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [1d158627b0](https://linux-hardware.org/?probe=1d158627b0) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [7d9f25dc5f](https://linux-hardware.org/?probe=7d9f25dc5f) | Jun 17, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| Haier         | Y11B                        | Notebook    | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [9c53e4cd72](https://linux-hardware.org/?probe=9c53e4cd72) | Jun 17, 2023 |
| HP            | G62                         | Notebook    | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | Notebook    | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| ASRock        | B85M                        | Desktop     | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [c503081708](https://linux-hardware.org/?probe=c503081708) | Jun 15, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [b00d413241](https://linux-hardware.org/?probe=b00d413241) | Jun 14, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [1d487a1ed5](https://linux-hardware.org/?probe=1d487a1ed5) | Jun 14, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [eab79964fb](https://linux-hardware.org/?probe=eab79964fb) | Jun 14, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b737ce6557](https://linux-hardware.org/?probe=b737ce6557) | Jun 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [f46f1000c0](https://linux-hardware.org/?probe=f46f1000c0) | Jun 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [535d3d42b7](https://linux-hardware.org/?probe=535d3d42b7) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| ASUSTek       | P5B                         | Desktop     | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| HP            | ENVY m6                     | Notebook    | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| MSI           | GL62M 7RDX                  | Notebook    | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9cb593e9e1](https://linux-hardware.org/?probe=9cb593e9e1) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [9ea7188339](https://linux-hardware.org/?probe=9ea7188339) | Jun 11, 2023 |
| HP            | 8350                        | Desktop     | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| ASUSTek       | P5B                         | Desktop     | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| MP            | MS-7848                     | Desktop     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Google        | Pirika                      | Notebook    | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Precision 7520              | Notebook    | [c52fb2f851](https://linux-hardware.org/?probe=c52fb2f851) | Jun 10, 2023 |
| Nvidia        | MCP79                       | Desktop     | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [e1ff6f4e2f](https://linux-hardware.org/?probe=e1ff6f4e2f) | Jun 08, 2023 |
| ASUSTek       | P5B                         | Desktop     | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [74cf1d0b63](https://linux-hardware.org/?probe=74cf1d0b63) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [88cbeea389](https://linux-hardware.org/?probe=88cbeea389) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2ad7aefc45](https://linux-hardware.org/?probe=2ad7aefc45) | Jun 07, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [2ad409f60a](https://linux-hardware.org/?probe=2ad409f60a) | Jun 07, 2023 |
| HP            | 8350                        | Desktop     | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| Dell          | 0G9322                      | Desktop     | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Nvidia        | MCP79                       | Desktop     | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [79f63dcf8e](https://linux-hardware.org/?probe=79f63dcf8e) | Jun 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [d48dc73993](https://linux-hardware.org/?probe=d48dc73993) | Jun 06, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [a98deb1f54](https://linux-hardware.org/?probe=a98deb1f54) | Jun 06, 2023 |
| ASUSTek       | CM1730,CM1830               | Desktop     | [2cc76d0cd9](https://linux-hardware.org/?probe=2cc76d0cd9) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | Desktop     | [7dc46d923e](https://linux-hardware.org/?probe=7dc46d923e) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| Dell          | 00010C A00                  | Desktop     | [fb12198605](https://linux-hardware.org/?probe=fb12198605) | Jun 05, 2023 |
| Dell          | 00010C A00                  | Desktop     | [d94442285c](https://linux-hardware.org/?probe=d94442285c) | Jun 05, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [e3b8e1a109](https://linux-hardware.org/?probe=e3b8e1a109) | Jun 04, 2023 |
| Dell          | Latitude E5250              | Notebook    | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | Notebook    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [a20f9c3365](https://linux-hardware.org/?probe=a20f9c3365) | Jun 03, 2023 |
| Dell          | 0G9322                      | Desktop     | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [01387c3030](https://linux-hardware.org/?probe=01387c3030) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [20260fb3b3](https://linux-hardware.org/?probe=20260fb3b3) | Jun 03, 2023 |
| HP            | 339A                        | Desktop     | [bb4619f4eb](https://linux-hardware.org/?probe=bb4619f4eb) | Jun 02, 2023 |
| Gateway       | SX2851                      | Desktop     | [262ddffda9](https://linux-hardware.org/?probe=262ddffda9) | Jun 02, 2023 |
| IPASON        | P3                          | Notebook    | [bd9e0660a4](https://linux-hardware.org/?probe=bd9e0660a4) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | Notebook    | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| MSI           | H81M-E34                    | Desktop     | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| MSI           | H81M-E34                    | Desktop     | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | Desktop     | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| HP            | 82B5                        | All in one  | [77ecbfa91c](https://linux-hardware.org/?probe=77ecbfa91c) | Jun 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [a7af6cac2c](https://linux-hardware.org/?probe=a7af6cac2c) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [0198d67a15](https://linux-hardware.org/?probe=0198d67a15) | May 31, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [449b742c95](https://linux-hardware.org/?probe=449b742c95) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Sony          | SVF14214CXW                 | Notebook    | [51568ce56e](https://linux-hardware.org/?probe=51568ce56e) | May 30, 2023 |
| Dell          | Latitude 3480               | Notebook    | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| Sony          | SVF14214CXW                 | Notebook    | [6cf7c2d7f2](https://linux-hardware.org/?probe=6cf7c2d7f2) | May 30, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [db28d8f731](https://linux-hardware.org/?probe=db28d8f731) | May 28, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [36bd3a5288](https://linux-hardware.org/?probe=36bd3a5288) | May 28, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | Notebook    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Acer          | Predator G3-605             | Desktop     | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [8c51cdf4ef](https://linux-hardware.org/?probe=8c51cdf4ef) | May 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9f96328490](https://linux-hardware.org/?probe=9f96328490) | May 27, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [48a2156205](https://linux-hardware.org/?probe=48a2156205) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 21D0                        | Desktop     | [7f83859a91](https://linux-hardware.org/?probe=7f83859a91) | May 27, 2023 |
| HP            | 81BA                        | All in one  | [d41186191f](https://linux-hardware.org/?probe=d41186191f) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | Desktop     | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| HP            | ProBook 4740s               | Notebook    | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [53d45d0d79](https://linux-hardware.org/?probe=53d45d0d79) | May 26, 2023 |
| ASUSTek       | G50VT                       | Notebook    | [6e4a2588b1](https://linux-hardware.org/?probe=6e4a2588b1) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [8d7ce86449](https://linux-hardware.org/?probe=8d7ce86449) | May 26, 2023 |
| HP            | 18E5                        | Desktop     | [23e2edb1fe](https://linux-hardware.org/?probe=23e2edb1fe) | May 26, 2023 |
| Dell          | 0K095G A02                  | Desktop     | [f11b8418c9](https://linux-hardware.org/?probe=f11b8418c9) | May 26, 2023 |
| HP            | 21D0                        | Desktop     | [8e52c2613c](https://linux-hardware.org/?probe=8e52c2613c) | May 26, 2023 |
| Google        | Lars                        | Notebook    | [25cc6549c3](https://linux-hardware.org/?probe=25cc6549c3) | May 25, 2023 |
| HP            | ProBook 6440b               | Notebook    | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [61dc4c5620](https://linux-hardware.org/?probe=61dc4c5620) | May 25, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [d25345cb25](https://linux-hardware.org/?probe=d25345cb25) | May 25, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [81c0b82d6c](https://linux-hardware.org/?probe=81c0b82d6c) | May 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f6fbdf57b5](https://linux-hardware.org/?probe=f6fbdf57b5) | May 24, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [933989a15b](https://linux-hardware.org/?probe=933989a15b) | May 24, 2023 |
| HP            | Stream Notebook             | Notebook    | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [ca3ed99a5c](https://linux-hardware.org/?probe=ca3ed99a5c) | May 24, 2023 |
| Pegatron      | 2AC2A                       | Desktop     | [f9e504a430](https://linux-hardware.org/?probe=f9e504a430) | May 24, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [8c7d3913b8](https://linux-hardware.org/?probe=8c7d3913b8) | May 24, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| HP            | 21EF                        | Desktop     | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [08746538f6](https://linux-hardware.org/?probe=08746538f6) | May 23, 2023 |
| Dell          | Latitude E5450              | Notebook    | [642802d511](https://linux-hardware.org/?probe=642802d511) | May 23, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4d0edc38d5](https://linux-hardware.org/?probe=4d0edc38d5) | May 23, 2023 |
| HP            | 21EF                        | Desktop     | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| Packard Be... | EasyNote MH35               | Notebook    | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| ASRock        | H77M                        | Desktop     | [7f173e0b75](https://linux-hardware.org/?probe=7f173e0b75) | May 22, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| HP            | EliteBook Folio G1          | Notebook    | [81477cd76f](https://linux-hardware.org/?probe=81477cd76f) | May 22, 2023 |
| HP            | EliteBook Folio G1          | Notebook    | [73d4310fa2](https://linux-hardware.org/?probe=73d4310fa2) | May 22, 2023 |
| HP            | 18E5                        | Desktop     | [d1bc34770d](https://linux-hardware.org/?probe=d1bc34770d) | May 22, 2023 |
| Microsoft     | Surface Book                | Tablet      | [01c76b5ed7](https://linux-hardware.org/?probe=01c76b5ed7) | May 21, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b6465d2950](https://linux-hardware.org/?probe=b6465d2950) | May 21, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [b9de7bf2f3](https://linux-hardware.org/?probe=b9de7bf2f3) | May 21, 2023 |
| Dell          | 0FGCC7 A01                  | Server      | [3900d6a330](https://linux-hardware.org/?probe=3900d6a330) | May 21, 2023 |
| Dell          | 02N3WF A01                  | Desktop     | [8d0096c040](https://linux-hardware.org/?probe=8d0096c040) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [6bef224193](https://linux-hardware.org/?probe=6bef224193) | May 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d11ecdffaf](https://linux-hardware.org/?probe=d11ecdffaf) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [b76cb7567c](https://linux-hardware.org/?probe=b76cb7567c) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [8a6ad6c590](https://linux-hardware.org/?probe=8a6ad6c590) | May 19, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [514fe06c9e](https://linux-hardware.org/?probe=514fe06c9e) | May 19, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aae519e65d](https://linux-hardware.org/?probe=aae519e65d) | May 19, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [31568d83f7](https://linux-hardware.org/?probe=31568d83f7) | May 18, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [754dc9d1fc](https://linux-hardware.org/?probe=754dc9d1fc) | May 18, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0608bc6ac3](https://linux-hardware.org/?probe=0608bc6ac3) | May 18, 2023 |
| Philco        | PHN14C                      | Notebook    | [4efea72b8f](https://linux-hardware.org/?probe=4efea72b8f) | May 18, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [e096b3a75c](https://linux-hardware.org/?probe=e096b3a75c) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [ee37475637](https://linux-hardware.org/?probe=ee37475637) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [68406e2c40](https://linux-hardware.org/?probe=68406e2c40) | May 18, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [cadb0eb363](https://linux-hardware.org/?probe=cadb0eb363) | May 17, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [cd3c24c6a2](https://linux-hardware.org/?probe=cd3c24c6a2) | May 17, 2023 |
| Acer          | Revo 70                     | Desktop     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [e18deba45b](https://linux-hardware.org/?probe=e18deba45b) | May 17, 2023 |
| HP            | 2B02                        | Desktop     | [a6bf09d51c](https://linux-hardware.org/?probe=a6bf09d51c) | May 17, 2023 |
| Pegatron      | Benicia                     | Desktop     | [e6ee1c66f6](https://linux-hardware.org/?probe=e6ee1c66f6) | May 17, 2023 |
| Framework     | Laptop                      | Notebook    | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d3c3cc9f96](https://linux-hardware.org/?probe=d3c3cc9f96) | May 15, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [7b95691784](https://linux-hardware.org/?probe=7b95691784) | May 15, 2023 |
| Intel         | Tiger Hill                  | Desktop     | [fdbe67045c](https://linux-hardware.org/?probe=fdbe67045c) | May 15, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [03c67bbed5](https://linux-hardware.org/?probe=03c67bbed5) | May 15, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [dd8c6c3811](https://linux-hardware.org/?probe=dd8c6c3811) | May 15, 2023 |
| HP            | 18E5                        | Desktop     | [7d5ceb9f5d](https://linux-hardware.org/?probe=7d5ceb9f5d) | May 15, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [d27a3510ed](https://linux-hardware.org/?probe=d27a3510ed) | May 14, 2023 |
| HP            | Presario CQ61               | Notebook    | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Google        | Bluebird                    | Notebook    | [c10880ed1b](https://linux-hardware.org/?probe=c10880ed1b) | May 14, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [24c81ddf59](https://linux-hardware.org/?probe=24c81ddf59) | May 14, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [89fbcb7903](https://linux-hardware.org/?probe=89fbcb7903) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [83e208da09](https://linux-hardware.org/?probe=83e208da09) | May 14, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [2b11351f94](https://linux-hardware.org/?probe=2b11351f94) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| Dell          | Latitude 3340               | Notebook    | [59d83d9cef](https://linux-hardware.org/?probe=59d83d9cef) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| ASUSTek       | K8N-DRE                     | Desktop     | [395dc0cfb3](https://linux-hardware.org/?probe=395dc0cfb3) | May 13, 2023 |
| ASUSTek       | K8N-DRE                     | Desktop     | [f55a0c735f](https://linux-hardware.org/?probe=f55a0c735f) | May 13, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [19f095fc02](https://linux-hardware.org/?probe=19f095fc02) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [e844f3a6fe](https://linux-hardware.org/?probe=e844f3a6fe) | May 13, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [bd9eca79bb](https://linux-hardware.org/?probe=bd9eca79bb) | May 13, 2023 |
| Acer          | Predator G3-605             | Desktop     | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [53b6692944](https://linux-hardware.org/?probe=53b6692944) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [297921aabf](https://linux-hardware.org/?probe=297921aabf) | May 13, 2023 |
| Acer          | Predator G3-605             | Desktop     | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [080f1c13d8](https://linux-hardware.org/?probe=080f1c13d8) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [e2c57c80fc](https://linux-hardware.org/?probe=e2c57c80fc) | May 13, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [135675c3ad](https://linux-hardware.org/?probe=135675c3ad) | May 13, 2023 |
| Google        | Kled                        | Notebook    | [f4e834ff36](https://linux-hardware.org/?probe=f4e834ff36) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d041d35517](https://linux-hardware.org/?probe=d041d35517) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d3ab5dcb5d](https://linux-hardware.org/?probe=d3ab5dcb5d) | May 12, 2023 |
| Dell          | Precision M2800             | Notebook    | [571407d9a3](https://linux-hardware.org/?probe=571407d9a3) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [e13fe43842](https://linux-hardware.org/?probe=e13fe43842) | May 12, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [c86f346e1d](https://linux-hardware.org/?probe=c86f346e1d) | May 12, 2023 |
| HP            | ProBook 4535s               | Notebook    | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [5a1484127d](https://linux-hardware.org/?probe=5a1484127d) | May 12, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [730cce9495](https://linux-hardware.org/?probe=730cce9495) | May 12, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [381ca3ca78](https://linux-hardware.org/?probe=381ca3ca78) | May 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [40b6afc886](https://linux-hardware.org/?probe=40b6afc886) | May 11, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [2c8128a196](https://linux-hardware.org/?probe=2c8128a196) | May 11, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | Desktop     | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [719d80a236](https://linux-hardware.org/?probe=719d80a236) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [b25b524237](https://linux-hardware.org/?probe=b25b524237) | May 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [22778449cc](https://linux-hardware.org/?probe=22778449cc) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [ffd84ff48e](https://linux-hardware.org/?probe=ffd84ff48e) | May 09, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [ba75f23f44](https://linux-hardware.org/?probe=ba75f23f44) | May 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [abf6d2bf1d](https://linux-hardware.org/?probe=abf6d2bf1d) | May 09, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d45b33c736](https://linux-hardware.org/?probe=d45b33c736) | May 09, 2023 |
| ASUSTek       | GL702VI                     | Notebook    | [3598875ef3](https://linux-hardware.org/?probe=3598875ef3) | May 09, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [372fa59e86](https://linux-hardware.org/?probe=372fa59e86) | May 09, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [9ac068efc7](https://linux-hardware.org/?probe=9ac068efc7) | May 09, 2023 |
| Dell          | Latitude E6520              | Notebook    | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | Laptop 15                   | Notebook    | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [d48affb6b2](https://linux-hardware.org/?probe=d48affb6b2) | May 08, 2023 |
| HP            | 655                         | Notebook    | [be3dec1f65](https://linux-hardware.org/?probe=be3dec1f65) | May 08, 2023 |
| Positivo      | S14CT01                     | Notebook    | [63a129c031](https://linux-hardware.org/?probe=63a129c031) | May 08, 2023 |
| Dell          | Latitude 5520               | Notebook    | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [d6085d9a0b](https://linux-hardware.org/?probe=d6085d9a0b) | May 07, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [8b646a0fa1](https://linux-hardware.org/?probe=8b646a0fa1) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [e23aaae239](https://linux-hardware.org/?probe=e23aaae239) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [a6da9a31d7](https://linux-hardware.org/?probe=a6da9a31d7) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| ASRockRack    | D1521D4I2                   | Desktop     | [136a9303c0](https://linux-hardware.org/?probe=136a9303c0) | May 06, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [7b0b45831c](https://linux-hardware.org/?probe=7b0b45831c) | May 06, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [b7bf9f8683](https://linux-hardware.org/?probe=b7bf9f8683) | May 06, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [480e352bf8](https://linux-hardware.org/?probe=480e352bf8) | May 05, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [2d5ecba977](https://linux-hardware.org/?probe=2d5ecba977) | May 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9a0649d500](https://linux-hardware.org/?probe=9a0649d500) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [d8582f94de](https://linux-hardware.org/?probe=d8582f94de) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [4ac4356e10](https://linux-hardware.org/?probe=4ac4356e10) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [37fd24fab6](https://linux-hardware.org/?probe=37fd24fab6) | May 05, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [b9ef1562db](https://linux-hardware.org/?probe=b9ef1562db) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | Notebook    | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [02fa09745c](https://linux-hardware.org/?probe=02fa09745c) | May 05, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [d571b75547](https://linux-hardware.org/?probe=d571b75547) | May 05, 2023 |
| Unknown       | X133                        | Notebook    | [b38ee0b3cc](https://linux-hardware.org/?probe=b38ee0b3cc) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [cf49833602](https://linux-hardware.org/?probe=cf49833602) | May 04, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [5b46ed614a](https://linux-hardware.org/?probe=5b46ed614a) | May 04, 2023 |
| Unknown       | E450                        | Notebook    | [a3261aab47](https://linux-hardware.org/?probe=a3261aab47) | May 04, 2023 |
| Gigabyte      | Z590 VISION G               | Desktop     | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [15160b0649](https://linux-hardware.org/?probe=15160b0649) | May 04, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [60e11bdf11](https://linux-hardware.org/?probe=60e11bdf11) | May 04, 2023 |
| KUU           | Andes II                    | Notebook    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [c9c14a6da2](https://linux-hardware.org/?probe=c9c14a6da2) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [bf515886ac](https://linux-hardware.org/?probe=bf515886ac) | May 03, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [d8c61ad691](https://linux-hardware.org/?probe=d8c61ad691) | May 02, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d3757c615f](https://linux-hardware.org/?probe=d3757c615f) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| Dell          | Latitude E6540              | Notebook    | [e6f334c91c](https://linux-hardware.org/?probe=e6f334c91c) | May 01, 2023 |
| Intel         | H55                         | Desktop     | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [83abb6a8e0](https://linux-hardware.org/?probe=83abb6a8e0) | May 01, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| ASUSTek       | K53U                        | Notebook    | [0745a61353](https://linux-hardware.org/?probe=0745a61353) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [e316615297](https://linux-hardware.org/?probe=e316615297) | May 01, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [bcd38374a3](https://linux-hardware.org/?probe=bcd38374a3) | May 01, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [99d3eca719](https://linux-hardware.org/?probe=99d3eca719) | May 01, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [1a00a1321e](https://linux-hardware.org/?probe=1a00a1321e) | Apr 30, 2023 |
| MSI           | IONA                        | Desktop     | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6987a21849](https://linux-hardware.org/?probe=6987a21849) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f1faff33de](https://linux-hardware.org/?probe=f1faff33de) | Apr 30, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [8b89ffd983](https://linux-hardware.org/?probe=8b89ffd983) | Apr 30, 2023 |
| HP            | Pavilion dv7                | Notebook    | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| Positivo      | S14CT01                     | Notebook    | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Toshiba       | Satellite C650D             | Notebook    | [472dedd62a](https://linux-hardware.org/?probe=472dedd62a) | Apr 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [6bad65ad2d](https://linux-hardware.org/?probe=6bad65ad2d) | Apr 29, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [25bc3aa225](https://linux-hardware.org/?probe=25bc3aa225) | Apr 29, 2023 |
| Sony          | VPCF215FX                   | Notebook    | [49c7606269](https://linux-hardware.org/?probe=49c7606269) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [58b09d7887](https://linux-hardware.org/?probe=58b09d7887) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [7d91fe30f7](https://linux-hardware.org/?probe=7d91fe30f7) | Apr 29, 2023 |
| Positivo      | S14CT01                     | Notebook    | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a984eefe43](https://linux-hardware.org/?probe=a984eefe43) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [d9010fa8d0](https://linux-hardware.org/?probe=d9010fa8d0) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Lenovo        | IdeaPad Y470                | Notebook    | [58c809428e](https://linux-hardware.org/?probe=58c809428e) | Apr 28, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [896574c24a](https://linux-hardware.org/?probe=896574c24a) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [71c860d51c](https://linux-hardware.org/?probe=71c860d51c) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | Notebook    | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Lenovo        | 3000 N200 0769A97           | Notebook    | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [4fbbe6e603](https://linux-hardware.org/?probe=4fbbe6e603) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Desktop     | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [0355cb4e69](https://linux-hardware.org/?probe=0355cb4e69) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| HP            | EliteBook 2730p             | Notebook    | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 230       | 5.7%    |
| 5.11.0-38-generic | 180       | 4.46%   |
| 5.11.0-27-generic | 156       | 3.87%   |
| 5.15.0-46-generic | 152       | 3.77%   |
| 5.15.0-58-generic | 151       | 3.74%   |
| 5.15.0-52-generic | 151       | 3.74%   |
| 5.15.0-67-generic | 142       | 3.52%   |
| 5.15.0-69-generic | 136       | 3.37%   |
| 5.13.0-30-generic | 126       | 3.12%   |
| 5.11.0-40-generic | 124       | 3.07%   |
| 5.13.0-39-generic | 121       | 3%      |
| 5.15.0-60-generic | 109       | 2.7%    |
| 5.15.0-78-generic | 108       | 2.68%   |
| 5.11.0-41-generic | 108       | 2.68%   |
| 5.11.0-37-generic | 107       | 2.65%   |
| 5.15.0-76-generic | 104       | 2.58%   |
| 5.15.0-71-generic | 102       | 2.53%   |
| 5.11.0-43-generic | 101       | 2.5%    |
| 5.15.0-48-generic | 95        | 2.35%   |
| 5.11.0-34-generic | 94        | 2.33%   |
| 5.13.0-40-generic | 90        | 2.23%   |
| 5.15.0-53-generic | 81        | 2.01%   |
| 5.15.0-41-generic | 77        | 1.91%   |
| 5.13.0-44-generic | 76        | 1.88%   |
| 5.13.0-35-generic | 74        | 1.83%   |
| 5.13.0-28-generic | 73        | 1.81%   |
| 5.15.0-73-generic | 68        | 1.69%   |
| 5.15.0-72-generic | 59        | 1.46%   |
| 5.13.0-52-generic | 59        | 1.46%   |
| 5.13.0-27-generic | 59        | 1.46%   |
| 5.15.0-83-generic | 56        | 1.39%   |
| 5.15.0-79-generic | 55        | 1.36%   |
| 5.13.0-41-generic | 54        | 1.34%   |
| 5.15.0-84-generic | 49        | 1.21%   |
| 5.13.0-51-generic | 42        | 1.04%   |
| 5.15.0-43-generic | 40        | 0.99%   |
| 5.11.0-36-generic | 39        | 0.97%   |
| 5.15.0-75-generic | 38        | 0.94%   |
| 5.15.0-57-generic | 35        | 0.87%   |
| 5.11.0-46-generic | 35        | 0.87%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 1821      | 49.89%  |
| 5.11.0  | 951       | 26.05%  |
| 5.13.0  | 768       | 21.04%  |
| 5.8.0   | 53        | 1.45%   |
| 5.14.0  | 10        | 0.27%   |
| 5.4.0   | 4         | 0.11%   |
| 6.3.2   | 2         | 0.05%   |
| 6.3.13  | 2         | 0.05%   |
| 5.19.12 | 2         | 0.05%   |
| 5.18.15 | 2         | 0.05%   |
| 5.17.5  | 2         | 0.05%   |
| 5.17.1  | 2         | 0.05%   |
| 5.16.0  | 2         | 0.05%   |
| 5.10.0  | 2         | 0.05%   |
| 6.3.1   | 1         | 0.03%   |
| 6.2.7   | 1         | 0.03%   |
| 6.2.16  | 1         | 0.03%   |
| 6.2.14  | 1         | 0.03%   |
| 6.1.8   | 1         | 0.03%   |
| 6.1.7   | 1         | 0.03%   |
| 6.0.9   | 1         | 0.03%   |
| 6.0.8   | 1         | 0.03%   |
| 6.0.19  | 1         | 0.03%   |
| 6.0.0   | 1         | 0.03%   |
| 5.4.180 | 1         | 0.03%   |
| 5.19.9  | 1         | 0.03%   |
| 5.19.6  | 1         | 0.03%   |
| 5.19.2  | 1         | 0.03%   |
| 5.19.14 | 1         | 0.03%   |
| 5.19.1  | 1         | 0.03%   |
| 5.19.0  | 1         | 0.03%   |
| 5.18.6  | 1         | 0.03%   |
| 5.18.19 | 1         | 0.03%   |
| 5.17.9  | 1         | 0.03%   |
| 5.16.5  | 1         | 0.03%   |
| 5.16.14 | 1         | 0.03%   |
| 5.16.12 | 1         | 0.03%   |
| 5.15.49 | 1         | 0.03%   |
| 5.15.24 | 1         | 0.03%   |
| 5.15.13 | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1824      | 49.99%  |
| 5.11    | 951       | 26.06%  |
| 5.13    | 769       | 21.07%  |
| 5.8     | 53        | 1.45%   |
| 5.14    | 10        | 0.27%   |
| 5.19    | 8         | 0.22%   |
| 6.3     | 5         | 0.14%   |
| 5.4     | 5         | 0.14%   |
| 5.17    | 5         | 0.14%   |
| 5.16    | 5         | 0.14%   |
| 6.0     | 4         | 0.11%   |
| 5.18    | 4         | 0.11%   |
| 6.2     | 3         | 0.08%   |
| 5.10    | 2         | 0.05%   |
| 6.1     | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 3496      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 3002      | 85.24%  |
| XFCE       | 476       | 13.52%  |
| Unknown    | 21        | 0.6%    |
| KDE5       | 6         | 0.17%   |
| X-Cinnamon | 4         | 0.11%   |
| Cinnamon   | 3         | 0.09%   |
| Budgie     | 3         | 0.09%   |
| Unity      | 2         | 0.06%   |
| i3         | 2         | 0.06%   |
| MATE       | 1         | 0.03%   |
| LXDE       | 1         | 0.03%   |
| KDE        | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3448      | 98.01%  |
| Wayland | 61        | 1.73%   |
| Unknown | 7         | 0.2%    |
| Tty     | 2         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2730      | 77.03%  |
| GDM     | 364       | 10.27%  |
| GDM3    | 319       | 9%      |
| LightDM | 127       | 3.58%   |
| SDDM    | 2         | 0.06%   |
| TDM     | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 1393      | 39.65%  |
| de_DE | 326       | 9.28%   |
| en_GB | 243       | 6.92%   |
| pt_BR | 203       | 5.78%   |
| fr_FR | 123       | 3.5%    |
| it_IT | 111       | 3.16%   |
| es_ES | 109       | 3.1%    |
| en_CA | 93        | 2.65%   |
| en_IN | 90        | 2.56%   |
| pl_PL | 85        | 2.42%   |
| en_AU | 69        | 1.96%   |
| nl_NL | 59        | 1.68%   |
| es_MX | 50        | 1.42%   |
| ru_RU | 45        | 1.28%   |
| en_ZA | 36        | 1.02%   |
| pt_PT | 31        | 0.88%   |
| es_AR | 30        | 0.85%   |
| cs_CZ | 29        | 0.83%   |
| hu_HU | 26        | 0.74%   |
| sv_SE | 22        | 0.63%   |
| tr_TR | 20        | 0.57%   |
| en_NZ | 20        | 0.57%   |
| nl_BE | 18        | 0.51%   |
| fr_BE | 17        | 0.48%   |
| es_CL | 16        | 0.46%   |
| de_CH | 16        | 0.46%   |
| fr_CA | 13        | 0.37%   |
| de_AT | 12        | 0.34%   |
| ja_JP | 11        | 0.31%   |
| es_CO | 11        | 0.31%   |
| fi_FI | 10        | 0.28%   |
| en_PH | 10        | 0.28%   |
| nb_NO | 9         | 0.26%   |
| el_GR | 9         | 0.26%   |
| sk_SK | 8         | 0.23%   |
| es_VE | 8         | 0.23%   |
| ar_EG | 8         | 0.23%   |
| es_CR | 7         | 0.2%    |
| da_DK | 7         | 0.2%    |
| zh_CN | 6         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2037      | 57.53%  |
| BIOS | 1504      | 42.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3263      | 92.73%  |
| Tmpfs    | 73        | 2.07%   |
| Zfs      | 65        | 1.85%   |
| Overlay  | 58        | 1.65%   |
| Btrfs    | 36        | 1.02%   |
| Xfs      | 9         | 0.26%   |
| Ext2     | 8         | 0.23%   |
| Ext3     | 5         | 0.14%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2906      | 82.11%  |
| GPT     | 487       | 13.76%  |
| MBR     | 146       | 4.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3408      | 97.23%  |
| Yes       | 97        | 2.77%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3165      | 90.22%  |
| Yes       | 343       | 9.78%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 579       | 16.56%  |
| ASUSTek Computer    | 504       | 14.42%  |
| Dell                | 468       | 13.39%  |
| Lenovo              | 449       | 12.84%  |
| Gigabyte Technology | 201       | 5.75%   |
| Acer                | 177       | 5.06%   |
| MSI                 | 170       | 4.86%   |
| Apple               | 131       | 3.75%   |
| ASRock              | 89        | 2.55%   |
| Toshiba             | 80        | 2.29%   |
| Intel               | 60        | 1.72%   |
| Samsung Electronics | 39        | 1.12%   |
| Unknown             | 39        | 1.12%   |
| Google              | 32        | 0.92%   |
| Sony                | 30        | 0.86%   |
| Fujitsu             | 26        | 0.74%   |
| Microsoft           | 24        | 0.69%   |
| Biostar             | 20        | 0.57%   |
| Packard Bell        | 19        | 0.54%   |
| Positivo            | 17        | 0.49%   |
| Pegatron            | 17        | 0.49%   |
| HUAWEI              | 16        | 0.46%   |
| Foxconn             | 15        | 0.43%   |
| AZW                 | 14        | 0.4%    |
| Alienware           | 14        | 0.4%    |
| Medion              | 12        | 0.34%   |
| Chuwi               | 11        | 0.31%   |
| AMI                 | 9         | 0.26%   |
| Notebook            | 8         | 0.23%   |
| GPU Company         | 7         | 0.2%    |
| Multilaser          | 6         | 0.17%   |
| Gateway             | 6         | 0.17%   |
| Fujitsu Siemens     | 6         | 0.17%   |
| BESSTAR Tech        | 6         | 0.17%   |
| LG Electronics      | 5         | 0.14%   |
| Thomson             | 4         | 0.11%   |
| Razer               | 4         | 0.11%   |
| OEM                 | 4         | 0.11%   |
| Microtech           | 4         | 0.11%   |
| Jumper              | 4         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 51        | 1.46%   |
| ASUS All Series                  | 31        | 0.89%   |
| HP Notebook                      | 21        | 0.6%    |
| HP Pavilion Notebook             | 14        | 0.4%    |
| Dell OptiPlex 7010               | 13        | 0.37%   |
| HP 15                            | 12        | 0.34%   |
| HP Pavilion dv7                  | 9         | 0.26%   |
| MSI MS-7817                      | 8         | 0.23%   |
| HP Pavilion dv6                  | 8         | 0.23%   |
| HP Pavilion 15                   | 8         | 0.23%   |
| Dell OptiPlex 790                | 8         | 0.23%   |
| Apple MacBookPro8,1              | 8         | 0.23%   |
| Apple iMac12,1                   | 8         | 0.23%   |
| Lenovo MIIX 320-10ICR 80XF       | 7         | 0.2%    |
| Dell OptiPlex 780                | 7         | 0.2%    |
| Dell OptiPlex 380                | 7         | 0.2%    |
| ASUS M5A78L-M/USB3               | 7         | 0.2%    |
| Apple iMac12,2                   | 7         | 0.2%    |
| Apple iMac10,1                   | 7         | 0.2%    |
| MSI MS-7C02                      | 6         | 0.17%   |
| Microsoft Surface Pro 4          | 6         | 0.17%   |
| Microsoft Surface Pro            | 6         | 0.17%   |
| Gigabyte A320M-S2H               | 6         | 0.17%   |
| Dell Latitude E6540              | 6         | 0.17%   |
| ASUS M5A97 R2.0                  | 6         | 0.17%   |
| MSI MS-7C37                      | 5         | 0.14%   |
| Intel H61                        | 5         | 0.14%   |
| HP ProBook 640 G1                | 5         | 0.14%   |
| HP Pavilion g6                   | 5         | 0.14%   |
| HP EliteBook 2570p               | 5         | 0.14%   |
| HP Compaq Pro 6300 SFF           | 5         | 0.14%   |
| GPU Company GWTC116-2            | 5         | 0.14%   |
| Gigabyte B450 AORUS M            | 5         | 0.14%   |
| Dell Precision WorkStation T3500 | 5         | 0.14%   |
| Dell OptiPlex 990                | 5         | 0.14%   |
| Dell OptiPlex 3020               | 5         | 0.14%   |
| Dell OptiPlex 3010               | 5         | 0.14%   |
| Dell Latitude E6520              | 5         | 0.14%   |
| Dell Inspiron 15-3567            | 5         | 0.14%   |
| AZW GTR                          | 5         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 143       | 4.09%   |
| Dell Inspiron         | 124       | 3.55%   |
| Dell Latitude         | 123       | 3.52%   |
| HP Pavilion           | 119       | 3.4%    |
| Acer Aspire           | 119       | 3.4%    |
| Lenovo IdeaPad        | 112       | 3.2%    |
| Dell OptiPlex         | 91        | 2.6%    |
| Toshiba Satellite     | 65        | 1.86%   |
| HP EliteBook          | 63        | 1.8%    |
| HP Compaq             | 53        | 1.52%   |
| Unknown               | 51        | 1.46%   |
| ASUS ROG              | 49        | 1.4%    |
| HP ProBook            | 47        | 1.34%   |
| ASUS PRIME            | 45        | 1.29%   |
| HP Laptop             | 43        | 1.23%   |
| Lenovo ThinkCentre    | 39        | 1.12%   |
| ASUS VivoBook         | 37        | 1.06%   |
| ASUS TUF              | 35        | 1%      |
| Dell Precision        | 33        | 0.94%   |
| ASUS All              | 31        | 0.89%   |
| Dell XPS              | 30        | 0.86%   |
| HP ENVY               | 29        | 0.83%   |
| Lenovo Yoga           | 28        | 0.8%    |
| Dell Vostro           | 28        | 0.8%    |
| Microsoft Surface     | 24        | 0.69%   |
| HP Notebook           | 21        | 0.6%    |
| HP Stream             | 18        | 0.51%   |
| HP EliteDesk          | 17        | 0.49%   |
| Packard Bell EasyNote | 15        | 0.43%   |
| ASUS ZenBook          | 15        | 0.43%   |
| Apple iMac12          | 15        | 0.43%   |
| HP 15                 | 14        | 0.4%    |
| Lenovo Legion         | 13        | 0.37%   |
| HP ProDesk            | 12        | 0.34%   |
| HP OMEN               | 12        | 0.34%   |
| Gigabyte B450         | 12        | 0.34%   |
| Fujitsu ESPRIMO       | 12        | 0.34%   |
| ASUS ASUS             | 12        | 0.34%   |
| Lenovo MIIX           | 11        | 0.31%   |
| Dell Studio           | 11        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 300       | 8.58%   |
| 2011    | 292       | 8.35%   |
| 2021    | 289       | 8.27%   |
| 2013    | 285       | 8.15%   |
| 2018    | 270       | 7.72%   |
| 2020    | 266       | 7.61%   |
| 2019    | 248       | 7.09%   |
| 2014    | 239       | 6.84%   |
| 2017    | 225       | 6.44%   |
| 2010    | 199       | 5.69%   |
| 2016    | 189       | 5.41%   |
| 2015    | 177       | 5.06%   |
| 2008    | 147       | 4.2%    |
| 2009    | 125       | 3.58%   |
| 2022    | 100       | 2.86%   |
| 2007    | 81        | 2.32%   |
| 2023    | 31        | 0.89%   |
| 2006    | 23        | 0.66%   |
| 2005    | 6         | 0.17%   |
| Unknown | 4         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1915      | 54.78%  |
| Desktop     | 1271      | 36.36%  |
| Convertible | 93        | 2.66%   |
| All in one  | 87        | 2.49%   |
| Tablet      | 62        | 1.77%   |
| Mini pc     | 59        | 1.69%   |
| Server      | 9         | 0.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3085      | 87.44%  |
| Enabled  | 443       | 12.56%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3460      | 98.97%  |
| Yes  | 36        | 1.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 962       | 27.26%  |
| 3.01-4.0        | 768       | 21.76%  |
| 16.01-24.0      | 607       | 17.2%   |
| 8.01-16.0       | 589       | 16.69%  |
| 32.01-64.0      | 273       | 7.74%   |
| 1.01-2.0        | 162       | 4.59%   |
| 64.01-256.0     | 68        | 1.93%   |
| 2.01-3.0        | 47        | 1.33%   |
| 24.01-32.0      | 45        | 1.28%   |
| 0.51-1.0        | 7         | 0.2%    |
| More than 256.0 | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1438      | 37.71%  |
| 2.01-3.0   | 1257      | 32.97%  |
| 3.01-4.0   | 523       | 13.72%  |
| 4.01-8.0   | 444       | 11.64%  |
| 0.51-1.0   | 67        | 1.76%   |
| 8.01-16.0  | 66        | 1.73%   |
| 16.01-24.0 | 10        | 0.26%   |
| 24.01-32.0 | 5         | 0.13%   |
| 32.01-64.0 | 2         | 0.05%   |
| 0.01-0.5   | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2279      | 63.78%  |
| 2      | 854       | 23.9%   |
| 3      | 215       | 6.02%   |
| 4      | 106       | 2.97%   |
| 5      | 50        | 1.4%    |
| 6      | 32        | 0.9%    |
| 0      | 15        | 0.42%   |
| 7      | 11        | 0.31%   |
| 8      | 8         | 0.22%   |
| 51     | 1         | 0.03%   |
| 30     | 1         | 0.03%   |
| 11     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2023      | 57.55%  |
| Yes       | 1492      | 42.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2916      | 83.24%  |
| No        | 587       | 16.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2792      | 79.52%  |
| No        | 719       | 20.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2076      | 58.81%  |
| No        | 1454      | 41.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 832       | 23.72%  |
| Germany      | 354       | 10.09%  |
| Brazil       | 226       | 6.44%   |
| UK           | 220       | 6.27%   |
| Italy        | 122       | 3.48%   |
| Canada       | 120       | 3.42%   |
| Spain        | 118       | 3.36%   |
| France       | 114       | 3.25%   |
| Netherlands  | 100       | 2.85%   |
| India        | 94        | 2.68%   |
| Poland       | 82        | 2.34%   |
| Australia    | 70        | 2%      |
| Mexico       | 67        | 1.91%   |
| Belgium      | 48        | 1.37%   |
| Russia       | 45        | 1.28%   |
| Sweden       | 40        | 1.14%   |
| South Africa | 40        | 1.14%   |
| Portugal     | 38        | 1.08%   |
| Argentina    | 38        | 1.08%   |
| Turkey       | 32        | 0.91%   |
| Switzerland  | 32        | 0.91%   |
| Hungary      | 32        | 0.91%   |
| Czechia      | 32        | 0.91%   |
| Austria      | 32        | 0.91%   |
| Norway       | 28        | 0.8%    |
| Romania      | 27        | 0.77%   |
| Greece       | 25        | 0.71%   |
| New Zealand  | 22        | 0.63%   |
| Japan        | 22        | 0.63%   |
| Egypt        | 20        | 0.57%   |
| Denmark      | 20        | 0.57%   |
| Chile        | 20        | 0.57%   |
| Finland      | 18        | 0.51%   |
| Colombia     | 18        | 0.51%   |
| Indonesia    | 17        | 0.48%   |
| Bulgaria     | 15        | 0.43%   |
| Philippines  | 12        | 0.34%   |
| Malaysia     | 12        | 0.34%   |
| Venezuela    | 11        | 0.31%   |
| Slovakia     | 11        | 0.31%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 31        | 0.85%   |
| Munich            | 26        | 0.71%   |
| Madrid            | 20        | 0.55%   |
| Athens            | 20        | 0.55%   |
| Rome              | 19        | 0.52%   |
| Sydney            | 18        | 0.49%   |
| Sao Paulo         | 17        | 0.46%   |
| Vienna            | 16        | 0.44%   |
| New York          | 16        | 0.44%   |
| Rio de Janeiro    | 15        | 0.41%   |
| Montreal          | 15        | 0.41%   |
| Milan             | 15        | 0.41%   |
| Hamburg           | 15        | 0.41%   |
| Paris             | 14        | 0.38%   |
| Dallas            | 14        | 0.38%   |
| London            | 13        | 0.35%   |
| Denver            | 13        | 0.35%   |
| Amsterdam         | 13        | 0.35%   |
| Johannesburg      | 12        | 0.33%   |
| Cape Town         | 12        | 0.33%   |
| Salt Lake City    | 11        | 0.3%    |
| Mexico City       | 11        | 0.3%    |
| Melbourne         | 11        | 0.3%    |
| Frankfurt am Main | 11        | 0.3%    |
| Delhi             | 11        | 0.3%    |
| Valencia          | 10        | 0.27%   |
| Stockholm         | 10        | 0.27%   |
| Seattle           | 10        | 0.27%   |
| Phoenix           | 10        | 0.27%   |
| Perth             | 10        | 0.27%   |
| Moscow            | 10        | 0.27%   |
| Istanbul          | 10        | 0.27%   |
| Houston           | 10        | 0.27%   |
| Buenos Aires      | 10        | 0.27%   |
| Bucharest         | 10        | 0.27%   |
| Bengaluru         | 10        | 0.27%   |
| Stuttgart         | 9         | 0.25%   |
| Krakow            | 9         | 0.25%   |
| Jakarta           | 9         | 0.25%   |
| Copenhagen        | 9         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 737       | 1057   | 14.9%   |
| Samsung Electronics         | 652       | 935    | 13.18%  |
| WDC                         | 634       | 876    | 12.82%  |
| Toshiba                     | 346       | 442    | 6.99%   |
| SanDisk                     | 305       | 379    | 6.17%   |
| Unknown                     | 293       | 401    | 5.92%   |
| Kingston                    | 260       | 364    | 5.26%   |
| Crucial                     | 179       | 218    | 3.62%   |
| Hitachi                     | 153       | 202    | 3.09%   |
| Intel                       | 102       | 134    | 2.06%   |
| SK hynix                    | 101       | 118    | 2.04%   |
| HGST                        | 83        | 103    | 1.68%   |
| A-DATA Technology           | 71        | 90     | 1.44%   |
| Micron Technology           | 66        | 77     | 1.33%   |
| China                       | 66        | 79     | 1.33%   |
| Apple                       | 60        | 69     | 1.21%   |
| Intenso                     | 41        | 44     | 0.83%   |
| Silicon Motion              | 36        | 47     | 0.73%   |
| Phison                      | 34        | 39     | 0.69%   |
| KIOXIA                      | 34        | 39     | 0.69%   |
| PNY                         | 30        | 38     | 0.61%   |
| SPCC                        | 28        | 41     | 0.57%   |
| Patriot                     | 28        | 37     | 0.57%   |
| Netac                       | 27        | 30     | 0.55%   |
| Unknown                     | 26        | 30     | 0.53%   |
| Micron/Crucial Technology   | 23        | 27     | 0.46%   |
| GOODRAM                     | 22        | 26     | 0.44%   |
| JMicron Technology          | 20        | 25     | 0.4%    |
| Phison Electronics          | 18        | 21     | 0.36%   |
| OCZ                         | 18        | 21     | 0.36%   |
| LITEON                      | 16        | 18     | 0.32%   |
| Lexar                       | 16        | 16     | 0.32%   |
| Team                        | 15        | 18     | 0.3%    |
| KingSpec                    | 14        | 16     | 0.28%   |
| Hewlett-Packard             | 14        | 18     | 0.28%   |
| Transcend                   | 13        | 30     | 0.26%   |
| Realtek Semiconductor       | 13        | 14     | 0.26%   |
| Maxtor                      | 12        | 16     | 0.24%   |
| MAXIO Technology (Hangzhou) | 12        | 12     | 0.24%   |
| LITEONIT                    | 12        | 14     | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 89        | 1.64%   |
| Unknown MMC Card  64GB                              | 86        | 1.58%   |
| Kingston SA400S37240G 240GB SSD                     | 63        | 1.16%   |
| Seagate ST500DM002-1BD142 500GB                     | 45        | 0.83%   |
| Seagate ST1000LM035-1RK172 1TB                      | 44        | 0.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 43        | 0.79%   |
| Toshiba MQ01ABD100 1TB                              | 39        | 0.72%   |
| Unknown MMC Card  128GB                             | 37        | 0.68%   |
| Samsung SSD 860 EVO 500GB                           | 37        | 0.68%   |
| Crucial CT240BX500SSD1 240GB                        | 37        | 0.68%   |
| Kingston SA400S37480G 480GB SSD                     | 35        | 0.64%   |
| Kingston SA400S37120G 120GB SSD                     | 33        | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 32        | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB                      | 29        | 0.53%   |
| Toshiba MQ01ABF050 500GB                            | 28        | 0.52%   |
| Unknown SD/MMC/MS PRO 128GB                         | 27        | 0.5%    |
| Toshiba MQ04ABF100 1TB                              | 27        | 0.5%    |
| Seagate ST500LT012-1DG142 500GB                     | 26        | 0.48%   |
| Samsung SSD 850 EVO 250GB                           | 26        | 0.48%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 26        | 0.48%   |
| Unknown                                             | 26        | 0.48%   |
| Samsung NVMe SSD Drive 512GB                        | 25        | 0.46%   |
| Samsung NVMe SSD Drive 1TB                          | 25        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                        | 25        | 0.46%   |
| Seagate ST9500325AS 500GB                           | 23        | 0.42%   |
| Samsung SSD 850 EVO 500GB                           | 23        | 0.42%   |
| Seagate ST1000DM003-1CH162 1TB                      | 21        | 0.39%   |
| SanDisk NVMe SSD Drive 256GB                        | 21        | 0.39%   |
| Samsung SSD 870 EVO 1TB                             | 21        | 0.39%   |
| Samsung NVMe SSD Drive 500GB                        | 21        | 0.39%   |
| Seagate Expansion 1TB                               | 20        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB                         | 20        | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 19        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD                    | 19        | 0.35%   |
| Unknown MMC Card  16GB                              | 18        | 0.33%   |
| Toshiba HDWD110 1TB                                 | 18        | 0.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 18        | 0.33%   |
| HGST HTS721010A9E630 1TB                            | 18        | 0.33%   |
| Seagate ST3500418AS 500GB                           | 17        | 0.31%   |
| SanDisk NVMe SSD Drive 1TB                          | 17        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 728       | 1033   | 36.97%  |
| WDC                 | 545       | 743    | 27.68%  |
| Toshiba             | 269       | 350    | 13.66%  |
| Hitachi             | 153       | 202    | 7.77%   |
| HGST                | 83        | 103    | 4.22%   |
| Samsung Electronics | 82        | 101    | 4.16%   |
| Unknown             | 28        | 35     | 1.42%   |
| Apple               | 28        | 31     | 1.42%   |
| Maxtor              | 12        | 16     | 0.61%   |
| Fujitsu             | 12        | 14     | 0.61%   |
| SABRENT             | 9         | 10     | 0.46%   |
| Hewlett-Packard     | 4         | 7      | 0.2%    |
| USB3.0              | 3         | 4      | 0.15%   |
| Intenso             | 3         | 3      | 0.15%   |
| SSK                 | 2         | 2      | 0.1%    |
| JMicron Technology  | 2         | 2      | 0.1%    |
| TDAS                | 1         | 3      | 0.05%   |
| QUANTUM             | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| External            | 1         | 1      | 0.05%   |
| ACASIS              | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 332       | 467    | 19.39%  |
| Kingston            | 218       | 295    | 12.73%  |
| Crucial             | 172       | 209    | 10.05%  |
| SanDisk             | 166       | 205    | 9.7%    |
| WDC                 | 73        | 96     | 4.26%   |
| China               | 65        | 78     | 3.8%    |
| A-DATA Technology   | 62        | 81     | 3.62%   |
| Toshiba             | 39        | 46     | 2.28%   |
| Intel               | 39        | 46     | 2.28%   |
| SK hynix            | 31        | 31     | 1.81%   |
| PNY                 | 30        | 38     | 1.75%   |
| Micron Technology   | 30        | 34     | 1.75%   |
| SPCC                | 27        | 40     | 1.58%   |
| Patriot             | 27        | 36     | 1.58%   |
| Netac               | 27        | 29     | 1.58%   |
| Intenso             | 27        | 29     | 1.58%   |
| Apple               | 26        | 30     | 1.52%   |
| GOODRAM             | 20        | 24     | 1.17%   |
| OCZ                 | 17        | 20     | 0.99%   |
| LITEON              | 16        | 18     | 0.93%   |
| Team                | 15        | 18     | 0.88%   |
| Lexar               | 15        | 15     | 0.88%   |
| Transcend           | 13        | 30     | 0.76%   |
| KingSpec            | 13        | 15     | 0.76%   |
| LITEONIT            | 12        | 14     | 0.7%    |
| JMicron Technology  | 12        | 14     | 0.7%    |
| Unknown             | 12        | 15     | 0.7%    |
| Apacer              | 10        | 13     | 0.58%   |
| Hewlett-Packard     | 9         | 10     | 0.53%   |
| Gigabyte Technology | 9         | 10     | 0.53%   |
| Leven               | 6         | 7      | 0.35%   |
| Plextor             | 5         | 6      | 0.29%   |
| Mushkin             | 5         | 5      | 0.29%   |
| FORESEE             | 5         | 6      | 0.29%   |
| Verbatim            | 4         | 4      | 0.23%   |
| Teclast             | 4         | 4      | 0.23%   |
| Super Talent        | 4         | 5      | 0.23%   |
| NGFF                | 4         | 4      | 0.23%   |
| KIOXIA-EXCERIA      | 4         | 8      | 0.23%   |
| Corsair             | 4         | 9      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1691      | 2664   | 37.62%  |
| SSD     | 1534      | 2200   | 34.13%  |
| NVMe    | 893       | 1210   | 19.87%  |
| MMC     | 275       | 365    | 6.12%   |
| Unknown | 102       | 128    | 2.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2728      | 4703   | 66.6%   |
| NVMe | 892       | 1208   | 21.78%  |
| MMC  | 275       | 365    | 6.71%   |
| SAS  | 201       | 291    | 4.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2021      | 2960   | 60.76%  |
| 0.51-1.0   | 934       | 1307   | 28.08%  |
| 1.01-2.0   | 229       | 327    | 6.89%   |
| 3.01-4.0   | 54        | 120    | 1.62%   |
| 4.01-10.0  | 46        | 66     | 1.38%   |
| 2.01-3.0   | 35        | 60     | 1.05%   |
| 10.01-20.0 | 7         | 24     | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1169      | 32.25%  |
| 251-500        | 886       | 24.44%  |
| 501-1000       | 548       | 15.12%  |
| 51-100         | 302       | 8.33%   |
| 1001-2000      | 219       | 6.04%   |
| 21-50          | 175       | 4.83%   |
| More than 3000 | 123       | 3.39%   |
| 1-20           | 89        | 2.46%   |
| 2001-3000      | 70        | 1.93%   |
| Unknown        | 44        | 1.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1432      | 37.8%   |
| 21-50          | 1060      | 27.98%  |
| 51-100         | 452       | 11.93%  |
| 101-250        | 371       | 9.79%   |
| 251-500        | 189       | 4.99%   |
| 501-1000       | 116       | 3.06%   |
| More than 3000 | 59        | 1.56%   |
| 1001-2000      | 47        | 1.24%   |
| Unknown        | 44        | 1.16%   |
| 2001-3000      | 18        | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                   | 4         | 4      | 3.81%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 2.86%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.86%   |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2      | 1.9%    |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 1.9%    |
| Seagate ST9500420AS 500GB                | 2         | 2      | 1.9%    |
| Seagate ST9500325AS 500GB                | 2         | 2      | 1.9%    |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 1.9%    |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 1.9%    |
| Kingston SUV400S37240G 240GB SSD         | 2         | 2      | 1.9%    |
| HGST HTS545050A7E380 500GB               | 2         | 3      | 1.9%    |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.95%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 0.95%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.95%   |
| WDC WD5000BEVT-24A0RT0 500GB             | 1         | 1      | 0.95%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 0.95%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 0.95%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 1      | 0.95%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 0.95%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 1      | 0.95%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 0.95%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 1      | 0.95%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1         | 2      | 0.95%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1         | 1      | 0.95%   |
| WDC WD Green 2.5 1000GB                  | 1         | 1      | 0.95%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.95%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.95%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 0.95%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1      | 0.95%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 0.95%   |
| Toshiba MK8046GSX 80GB                   | 1         | 1      | 0.95%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1      | 0.95%   |
| Toshiba MG03ACA200 2TB                   | 1         | 1      | 0.95%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 0.95%   |
| Teclast 128GB NS550-2242 SSD             | 1         | 1      | 0.95%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1         | 1      | 0.95%   |
| Seagate ST9320310AS 320GB                | 1         | 1      | 0.95%   |
| Seagate ST9250315AS 250GB                | 1         | 1      | 0.95%   |
| Seagate ST9200420ASG 200GB               | 1         | 1      | 0.95%   |
| Seagate ST9160411ASG 160GB               | 1         | 1      | 0.95%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 35     | 32.69%  |
| Toshiba             | 15        | 15     | 14.42%  |
| WDC                 | 14        | 15     | 13.46%  |
| HGST                | 10        | 11     | 9.62%   |
| Kingston            | 6         | 6      | 5.77%   |
| Samsung Electronics | 5         | 5      | 4.81%   |
| Hitachi             | 3         | 3      | 2.88%   |
| SK hynix            | 2         | 2      | 1.92%   |
| Intel               | 2         | 2      | 1.92%   |
| A-DATA Technology   | 2         | 2      | 1.92%   |
| Teclast             | 1         | 1      | 0.96%   |
| Silicon Motion      | 1         | 1      | 0.96%   |
| POLION              | 1         | 1      | 0.96%   |
| OCZ                 | 1         | 1      | 0.96%   |
| Netac               | 1         | 1      | 0.96%   |
| Maxtor              | 1         | 1      | 0.96%   |
| LITEONIT            | 1         | 1      | 0.96%   |
| Hewlett-Packard     | 1         | 1      | 0.96%   |
| Drevo               | 1         | 1      | 0.96%   |
| China               | 1         | 1      | 0.96%   |
| Unknown             | 1         | 1      | 0.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 35     | 44.74%  |
| WDC                 | 13        | 14     | 17.11%  |
| Toshiba             | 12        | 12     | 15.79%  |
| HGST                | 10        | 11     | 13.16%  |
| Samsung Electronics | 3         | 3      | 3.95%   |
| Hitachi             | 3         | 3      | 3.95%   |
| Maxtor              | 1         | 1      | 1.32%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 72        | 79     | 72%     |
| SSD  | 24        | 24     | 24%     |
| NVMe | 4         | 4      | 4%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3097      | 5800   | 85.81%  |
| Works    | 411       | 657    | 11.39%  |
| Malfunc  | 98        | 107    | 2.72%   |
| Failed   | 2         | 2      | 0.06%   |
| Fixed    | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2371      | 56.97%  |
| AMD                              | 665       | 15.98%  |
| Samsung Electronics              | 301       | 7.23%   |
| SanDisk                          | 154       | 3.7%    |
| SK hynix                         | 66        | 1.59%   |
| Nvidia                           | 63        | 1.51%   |
| Kingston Technology Company      | 59        | 1.42%   |
| ASMedia Technology               | 55        | 1.32%   |
| Phison Electronics               | 54        | 1.3%    |
| Silicon Motion                   | 41        | 0.99%   |
| Toshiba America Info Systems     | 38        | 0.91%   |
| Micron Technology                | 37        | 0.89%   |
| KIOXIA                           | 36        | 0.86%   |
| JMicron Technology               | 32        | 0.77%   |
| Micron/Crucial Technology        | 30        | 0.72%   |
| Marvell Technology Group         | 30        | 0.72%   |
| ADATA Technology                 | 21        | 0.5%    |
| Realtek Semiconductor            | 14        | 0.34%   |
| MAXIO Technology (Hangzhou)      | 14        | 0.34%   |
| VIA Technologies                 | 9         | 0.22%   |
| Silicon Image                    | 8         | 0.19%   |
| Seagate Technology               | 8         | 0.19%   |
| Union Memory (Shenzhen)          | 6         | 0.14%   |
| Solid State Storage Technology   | 6         | 0.14%   |
| Lite-On Technology               | 6         | 0.14%   |
| Apple                            | 5         | 0.12%   |
| LSI Logic / Symbios Logic        | 4         | 0.1%    |
| INNOGRIT                         | 4         | 0.1%    |
| Broadcom / LSI                   | 4         | 0.1%    |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| Shenzhen Longsys Electronics     | 3         | 0.07%   |
| Yangtze Memory Technologies      | 2         | 0.05%   |
| OCZ Technology Group             | 2         | 0.05%   |
| Netac Technology                 | 2         | 0.05%   |
| Lenovo                           | 2         | 0.05%   |
| TenaFe                           | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Dell                             | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 448       | 9.34%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 180       | 3.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 174       | 3.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 165       | 3.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 132       | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 129       | 2.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 120       | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 95        | 1.98%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 91        | 1.9%    |
| AMD 400 Series Chipset SATA Controller                                                  | 81        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 80        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 79        | 1.65%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 78        | 1.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 74        | 1.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 73        | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 73        | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 68        | 1.42%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 68        | 1.42%   |
| Samsung NVMe SSD Controller 980                                                         | 67        | 1.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 66        | 1.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 66        | 1.38%   |
| Intel SATA Controller [RAID mode]                                                       | 61        | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 58        | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 57        | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 51        | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 51        | 1.06%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 50        | 1.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 48        | 1%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 46        | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 45        | 0.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 41        | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 40        | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 40        | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 38        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 37        | 0.77%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 36        | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 33        | 0.69%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 32        | 0.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 31        | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 31        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2604      | 60.69%  |
| NVMe | 891       | 20.76%  |
| IDE  | 474       | 11.05%  |
| RAID | 312       | 7.27%   |
| SAS  | 7         | 0.16%   |
| SCSI | 3         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2723      | 77.89%  |
| AMD    | 773       | 22.11%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 51        | 1.46%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 38        | 1.09%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 37        | 1.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 30        | 0.86%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 28        | 0.8%    |
| AMD Ryzen 5 3600 6-Core Processor             | 27        | 0.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 26        | 0.74%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 26        | 0.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 24        | 0.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 24        | 0.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 23        | 0.66%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 22        | 0.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 21        | 0.6%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 21        | 0.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 21        | 0.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 0.57%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 20        | 0.57%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 19        | 0.54%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 19        | 0.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 18        | 0.51%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 18        | 0.51%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.51%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 17        | 0.49%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 16        | 0.46%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 16        | 0.46%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 15        | 0.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 15        | 0.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 15        | 0.43%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 15        | 0.43%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 15        | 0.43%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 15        | 0.43%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 14        | 0.4%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.4%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 14        | 0.4%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 14        | 0.4%    |
| Intel Core i3-4160 CPU @ 3.60GHz              | 14        | 0.4%    |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 14        | 0.4%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 13        | 0.37%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 13        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 817       | 23.35%  |
| Intel Core i7           | 499       | 14.26%  |
| Intel Core i3           | 324       | 9.26%   |
| Intel Celeron           | 236       | 6.74%   |
| Other                   | 191       | 5.46%   |
| AMD Ryzen 5             | 182       | 5.2%    |
| Intel Core 2 Duo        | 175       | 5%      |
| AMD Ryzen 7             | 116       | 3.32%   |
| Intel Atom              | 114       | 3.26%   |
| Intel Pentium           | 103       | 2.94%   |
| Intel Xeon              | 74        | 2.11%   |
| AMD FX                  | 52        | 1.49%   |
| AMD Ryzen 9             | 51        | 1.46%   |
| Intel Pentium Dual-Core | 48        | 1.37%   |
| AMD A6                  | 44        | 1.26%   |
| AMD Ryzen 3             | 35        | 1%      |
| Intel Core 2 Quad       | 32        | 0.91%   |
| AMD A4                  | 32        | 0.91%   |
| AMD A8                  | 31        | 0.89%   |
| AMD A10                 | 31        | 0.89%   |
| Intel Pentium Dual      | 29        | 0.83%   |
| AMD Athlon II X2        | 23        | 0.66%   |
| Intel Core 2            | 20        | 0.57%   |
| AMD E1                  | 16        | 0.46%   |
| Intel Pentium Silver    | 15        | 0.43%   |
| Intel Core i9           | 14        | 0.4%    |
| AMD Phenom II X4        | 14        | 0.4%    |
| Intel Pentium Gold      | 11        | 0.31%   |
| Intel Core M            | 11        | 0.31%   |
| AMD Phenom II X6        | 11        | 0.31%   |
| AMD E                   | 11        | 0.31%   |
| AMD Athlon 64 X2        | 11        | 0.31%   |
| AMD Athlon              | 11        | 0.31%   |
| AMD Turion 64 X2 Mobile | 8         | 0.23%   |
| Intel Pentium 4         | 7         | 0.2%    |
| AMD E2                  | 7         | 0.2%    |
| AMD Athlon II X4        | 7         | 0.2%    |
| AMD Athlon II           | 6         | 0.17%   |
| Intel Core m5           | 5         | 0.14%   |
| AMD Athlon II X3        | 5         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1633      | 46.66%  |
| 4      | 1261      | 36.03%  |
| 6      | 267       | 7.63%   |
| 8      | 185       | 5.29%   |
| 1      | 47        | 1.34%   |
| 12     | 37        | 1.06%   |
| 3      | 22        | 0.63%   |
| 16     | 19        | 0.54%   |
| 10     | 19        | 0.54%   |
| 14     | 7         | 0.2%    |
| 40     | 1         | 0.03%   |
| 28     | 1         | 0.03%   |
| 24     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 3483      | 99.63%  |
| 2      | 13        | 0.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2105      | 60.19%  |
| 1      | 1392      | 39.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3496      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 273       | 7.69%   |
| 0x306a9    | 262       | 7.38%   |
| Unknown    | 245       | 6.9%    |
| 0x306c3    | 200       | 5.63%   |
| 0x1067a    | 166       | 4.67%   |
| 0x40651    | 103       | 2.9%    |
| 0x806c1    | 96        | 2.7%    |
| 0x406e3    | 90        | 2.53%   |
| 0x20655    | 88        | 2.48%   |
| 0x806e9    | 87        | 2.45%   |
| 0x306d4    | 82        | 2.31%   |
| 0x406c4    | 79        | 2.22%   |
| 0x506e3    | 77        | 2.17%   |
| 0x30678    | 72        | 2.03%   |
| 0x906ea    | 67        | 1.89%   |
| 0x806ea    | 65        | 1.83%   |
| 0x806ec    | 62        | 1.75%   |
| 0x906e9    | 58        | 1.63%   |
| 0x6fd      | 54        | 1.52%   |
| 0x706a8    | 50        | 1.41%   |
| 0x08701021 | 50        | 1.41%   |
| 0x08108109 | 43        | 1.21%   |
| 0x706e5    | 41        | 1.15%   |
| 0x506c9    | 40        | 1.13%   |
| 0x10676    | 38        | 1.07%   |
| 0x20652    | 37        | 1.04%   |
| 0x06000852 | 36        | 1.01%   |
| 0x010000c8 | 34        | 0.96%   |
| 0x406c3    | 31        | 0.87%   |
| 0x6fb      | 30        | 0.84%   |
| 0x0a50000c | 30        | 0.84%   |
| 0x06001119 | 26        | 0.73%   |
| 0x07030105 | 25        | 0.7%    |
| 0x0800820d | 24        | 0.68%   |
| 0x06006705 | 24        | 0.68%   |
| 0xa0653    | 23        | 0.65%   |
| 0x08600106 | 22        | 0.62%   |
| 0x0700010f | 21        | 0.59%   |
| 0xa0655    | 20        | 0.56%   |
| 0xa0652    | 20        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 412       | 11.78%  |
| Haswell          | 333       | 9.52%   |
| SandyBridge      | 295       | 8.44%   |
| IvyBridge        | 279       | 7.98%   |
| Penryn           | 210       | 6.01%   |
| Silvermont       | 197       | 5.63%   |
| Skylake          | 175       | 5%      |
| Westmere         | 136       | 3.89%   |
| Core             | 119       | 3.4%    |
| Zen 2            | 112       | 3.2%    |
| TigerLake        | 107       | 3.06%   |
| Zen 3            | 101       | 2.89%   |
| Zen+             | 92        | 2.63%   |
| Broadwell        | 88        | 2.52%   |
| K10              | 78        | 2.23%   |
| Unknown          | 74        | 2.12%   |
| Goldmont plus    | 72        | 2.06%   |
| CometLake        | 70        | 2%      |
| Piledriver       | 68        | 1.94%   |
| Icelake          | 65        | 1.86%   |
| Excavator        | 60        | 1.72%   |
| Zen              | 50        | 1.43%   |
| Goldmont         | 43        | 1.23%   |
| Puma             | 40        | 1.14%   |
| Nehalem          | 34        | 0.97%   |
| Alderlake Hybrid | 29        | 0.83%   |
| K8 Hammer        | 26        | 0.74%   |
| Jaguar           | 25        | 0.71%   |
| Bobcat           | 21        | 0.6%    |
| K10 Llano        | 18        | 0.51%   |
| Tremont          | 14        | 0.4%    |
| Steamroller      | 13        | 0.37%   |
| Bulldozer        | 13        | 0.37%   |
| Bonnell          | 13        | 0.37%   |
| NetBurst         | 10        | 0.29%   |
| K8 & K10 hybrid  | 5         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2117      | 52.9%   |
| Nvidia                           | 957       | 23.91%  |
| AMD                              | 914       | 22.84%  |
| Matrox Electronics Systems       | 5         | 0.12%   |
| VIA Technologies                 | 4         | 0.1%    |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| ASPEED Technology                | 2         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 224       | 5.46%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 166       | 4.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 112       | 2.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 104       | 2.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 87        | 2.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 86        | 2.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 83        | 2.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 79        | 1.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 77        | 1.88%   |
| Intel HD Graphics 620                                                                    | 71        | 1.73%   |
| Intel UHD Graphics 620                                                                   | 64        | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 64        | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 64        | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 62        | 1.51%   |
| Intel HD Graphics 5500                                                                   | 53        | 1.29%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 48        | 1.17%   |
| Intel HD Graphics 630                                                                    | 47        | 1.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 44        | 1.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 44        | 1.07%   |
| Intel HD Graphics 530                                                                    | 43        | 1.05%   |
| AMD Renoir                                                                               | 43        | 1.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 38        | 0.93%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 38        | 0.93%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 37        | 0.9%    |
| Intel HD Graphics 500                                                                    | 36        | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 36        | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 33        | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 33        | 0.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 33        | 0.8%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 32        | 0.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 31        | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 31        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 29        | 0.71%   |
| AMD Lucienne                                                                             | 29        | 0.71%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 25        | 0.61%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 25        | 0.61%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 22        | 0.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 22        | 0.54%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 21        | 0.51%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 21        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 1682      | 47.87%  |
| 1 x AMD              | 739       | 21.03%  |
| 1 x Nvidia           | 595       | 16.93%  |
| Intel + Nvidia       | 296       | 8.42%   |
| Intel + AMD          | 85        | 2.42%   |
| AMD + Nvidia         | 47        | 1.34%   |
| 2 x AMD              | 42        | 1.2%    |
| 2 x Nvidia           | 7         | 0.2%    |
| Other                | 5         | 0.14%   |
| 1 x VIA              | 4         | 0.11%   |
| 1 x SiS              | 3         | 0.09%   |
| 1 x Matrox           | 3         | 0.09%   |
| 1 x ASPEED           | 2         | 0.06%   |
| 2 x Intel            | 1         | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.03%   |
| Nvidia + Matrox      | 1         | 0.03%   |
| AMD + Matrox         | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2843      | 80.74%  |
| Proprietary | 567       | 16.1%   |
| Unknown     | 111       | 3.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2096      | 58.86%  |
| 0.01-0.5   | 429       | 12.05%  |
| 1.01-2.0   | 334       | 9.38%   |
| 0.51-1.0   | 293       | 8.23%   |
| 3.01-4.0   | 167       | 4.69%   |
| 7.01-8.0   | 118       | 3.31%   |
| 5.01-6.0   | 52        | 1.46%   |
| 8.01-16.0  | 39        | 1.1%    |
| 2.01-3.0   | 29        | 0.81%   |
| 16.01-24.0 | 4         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 443       | 12.46%  |
| AU Optronics            | 409       | 11.51%  |
| Chimei Innolux          | 312       | 8.78%   |
| BOE                     | 312       | 8.78%   |
| LG Display              | 305       | 8.58%   |
| Dell                    | 172       | 4.84%   |
| Goldstar                | 164       | 4.61%   |
| Hewlett-Packard         | 124       | 3.49%   |
| Apple                   | 114       | 3.21%   |
| Acer                    | 100       | 2.81%   |
| AOC                     | 82        | 2.31%   |
| Philips                 | 79        | 2.22%   |
| Lenovo                  | 62        | 1.74%   |
| Chi Mei Optoelectronics | 62        | 1.74%   |
| Ancor Communications    | 61        | 1.72%   |
| BenQ                    | 60        | 1.69%   |
| Sharp                   | 47        | 1.32%   |
| LG Electronics          | 31        | 0.87%   |
| LG Philips              | 29        | 0.82%   |
| Sony                    | 28        | 0.79%   |
| Unknown                 | 28        | 0.79%   |
| PANDA                   | 26        | 0.73%   |
| InfoVision              | 26        | 0.73%   |
| ViewSonic               | 25        | 0.7%    |
| Vizio                   | 22        | 0.62%   |
| Unknown                 | 22        | 0.62%   |
| Iiyama                  | 20        | 0.56%   |
| ASUSTek Computer        | 20        | 0.56%   |
| Fujitsu Siemens         | 15        | 0.42%   |
| Panasonic               | 13        | 0.37%   |
| Sceptre Tech            | 12        | 0.34%   |
| NEC Computers           | 12        | 0.34%   |
| Eizo                    | 12        | 0.34%   |
| CPT                     | 12        | 0.34%   |
| Toshiba                 | 11        | 0.31%   |
| MSI                     | 11        | 0.31%   |
| HPN                     | 10        | 0.28%   |
| HannStar                | 9         | 0.25%   |
| Microstep               | 6         | 0.17%   |
| LGD                     | 6         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 28        | 0.77%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 20        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 17        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 15        | 0.41%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 15        | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 15        | 0.41%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 14        | 0.38%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 13        | 0.36%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 13        | 0.36%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 12        | 0.33%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 11        | 0.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.3%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 11        | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.3%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 10        | 0.27%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 9         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 9         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 9         | 0.25%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 9         | 0.25%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 8         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 8         | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.22%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 8         | 0.22%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 8         | 0.22%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                         | 8         | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 7         | 0.19%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 7         | 0.19%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 6         | 0.16%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 6         | 0.16%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 6         | 0.16%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 6         | 0.16%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 6         | 0.16%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 6         | 0.16%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 6         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1292      | 37.27%  |
| 1366x768 (WXGA)    | 872       | 25.15%  |
| 3840x2160 (4K)     | 187       | 5.39%   |
| 1600x900 (HD+)     | 181       | 5.22%   |
| 1280x800 (WXGA)    | 103       | 2.97%   |
| 2560x1440 (QHD)    | 101       | 2.91%   |
| 1680x1050 (WSXGA+) | 97        | 2.8%    |
| 1440x900 (WXGA+)   | 92        | 2.65%   |
| 1280x1024 (SXGA)   | 83        | 2.39%   |
| Unknown            | 65        | 1.87%   |
| 1920x1200 (WUXGA)  | 53        | 1.53%   |
| 1360x768           | 39        | 1.12%   |
| 3440x1440          | 37        | 1.07%   |
| 3840x1080          | 30        | 0.87%   |
| 2560x1080          | 28        | 0.81%   |
| 2560x1600          | 25        | 0.72%   |
| 2736x1824          | 16        | 0.46%   |
| 1920x540           | 16        | 0.46%   |
| 2880x1800          | 12        | 0.35%   |
| 2160x1440          | 12        | 0.35%   |
| 3200x1800 (QHD+)   | 10        | 0.29%   |
| 2256x1504          | 10        | 0.29%   |
| 1024x768 (XGA)     | 9         | 0.26%   |
| 1600x1200          | 7         | 0.2%    |
| 3840x2400          | 6         | 0.17%   |
| 1280x720 (HD)      | 6         | 0.17%   |
| 5760x1080          | 4         | 0.12%   |
| 3840x1600          | 4         | 0.12%   |
| 1920x1280          | 4         | 0.12%   |
| 1024x600           | 4         | 0.12%   |
| 4480x1440          | 3         | 0.09%   |
| 3600x1080          | 3         | 0.09%   |
| 2880x1920          | 3         | 0.09%   |
| 1920x515           | 3         | 0.09%   |
| 5760x2160          | 2         | 0.06%   |
| 5120x1440          | 2         | 0.06%   |
| 4480x1600          | 2         | 0.06%   |
| 4480x1080          | 2         | 0.06%   |
| 3360x1080          | 2         | 0.06%   |
| 3200x1200          | 2         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 906       | 25.75%  |
| 13      | 339       | 9.63%   |
| Unknown | 281       | 7.99%   |
| 14      | 262       | 7.45%   |
| 27      | 199       | 5.66%   |
| 17      | 198       | 5.63%   |
| 24      | 172       | 4.89%   |
| 21      | 160       | 4.55%   |
| 23      | 150       | 4.26%   |
| 19      | 93        | 2.64%   |
| 11      | 90        | 2.56%   |
| 31      | 84        | 2.39%   |
| 12      | 79        | 2.24%   |
| 20      | 74        | 2.1%    |
| 18      | 73        | 2.07%   |
| 22      | 65        | 1.85%   |
| 34      | 49        | 1.39%   |
| 40      | 23        | 0.65%   |
| 54      | 22        | 0.63%   |
| 84      | 21        | 0.6%    |
| 16      | 21        | 0.6%    |
| 72      | 16        | 0.45%   |
| 32      | 16        | 0.45%   |
| 26      | 14        | 0.4%    |
| 10      | 13        | 0.37%   |
| 25      | 12        | 0.34%   |
| 52      | 8         | 0.23%   |
| 36      | 7         | 0.2%    |
| 49      | 6         | 0.17%   |
| 65      | 5         | 0.14%   |
| 48      | 5         | 0.14%   |
| 28      | 5         | 0.14%   |
| 37      | 4         | 0.11%   |
| 35      | 4         | 0.11%   |
| 29      | 4         | 0.11%   |
| 74      | 3         | 0.09%   |
| 64      | 3         | 0.09%   |
| 58      | 3         | 0.09%   |
| 46      | 3         | 0.09%   |
| 42      | 3         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1363      | 39.27%  |
| 501-600     | 492       | 14.17%  |
| 401-500     | 415       | 11.96%  |
| 201-300     | 346       | 9.97%   |
| Unknown     | 281       | 8.1%    |
| 351-400     | 235       | 6.77%   |
| 601-700     | 116       | 3.34%   |
| 701-800     | 75        | 2.16%   |
| 1001-1500   | 63        | 1.82%   |
| 1501-2000   | 43        | 1.24%   |
| 801-900     | 34        | 0.98%   |
| 901-1000    | 6         | 0.17%   |
| 101-200     | 2         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2403      | 73.62%  |
| 16/10   | 382       | 11.7%   |
| Unknown | 253       | 7.75%   |
| 5/4     | 74        | 2.27%   |
| 21/9    | 58        | 1.78%   |
| 3/2     | 51        | 1.56%   |
| 4/3     | 25        | 0.77%   |
| 32/9    | 8         | 0.25%   |
| 6/5     | 4         | 0.12%   |
| 3.73    | 3         | 0.09%   |
| 0.62    | 2         | 0.06%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 899       | 25.72%  |
| 81-90          | 486       | 13.9%   |
| 201-250        | 438       | 12.53%  |
| Unknown        | 281       | 8.04%   |
| 151-200        | 227       | 6.49%   |
| 301-350        | 206       | 5.89%   |
| 351-500        | 161       | 4.61%   |
| 121-130        | 136       | 3.89%   |
| 71-80          | 125       | 3.58%   |
| More than 1000 | 99        | 2.83%   |
| 141-150        | 97        | 2.77%   |
| 51-60          | 92        | 2.63%   |
| 61-70          | 67        | 1.92%   |
| 251-300        | 65        | 1.86%   |
| 501-1000       | 50        | 1.43%   |
| 131-140        | 23        | 0.66%   |
| 111-120        | 22        | 0.63%   |
| 41-50          | 11        | 0.31%   |
| 91-100         | 9         | 0.26%   |
| 1-40           | 2         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1038      | 30.34%  |
| 51-100        | 1003      | 29.32%  |
| 121-160       | 769       | 22.48%  |
| Unknown       | 281       | 8.21%   |
| 161-240       | 175       | 5.12%   |
| 1-50          | 97        | 2.84%   |
| More than 240 | 58        | 1.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2982      | 83.91%  |
| 2     | 425       | 11.96%  |
| 0     | 114       | 3.21%   |
| 3     | 29        | 0.82%   |
| 4     | 3         | 0.08%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1863      | 35.05%  |
| Intel                             | 1514      | 28.48%  |
| Qualcomm Atheros                  | 648       | 12.19%  |
| Broadcom                          | 392       | 7.37%   |
| Broadcom Limited                  | 109       | 2.05%   |
| Ralink Technology                 | 81        | 1.52%   |
| Marvell Technology Group          | 74        | 1.39%   |
| TP-Link                           | 73        | 1.37%   |
| Ralink                            | 62        | 1.17%   |
| MediaTek                          | 60        | 1.13%   |
| Nvidia                            | 55        | 1.03%   |
| Samsung Electronics               | 36        | 0.68%   |
| ASIX Electronics                  | 29        | 0.55%   |
| NetGear                           | 22        | 0.41%   |
| Dell                              | 22        | 0.41%   |
| Xiaomi                            | 19        | 0.36%   |
| Qualcomm Atheros Communications   | 16        | 0.3%    |
| DisplayLink                       | 15        | 0.28%   |
| Microsoft                         | 14        | 0.26%   |
| Huawei Technologies               | 14        | 0.26%   |
| Sierra Wireless                   | 12        | 0.23%   |
| JMicron Technology                | 11        | 0.21%   |
| Hewlett-Packard                   | 11        | 0.21%   |
| D-Link System                     | 11        | 0.21%   |
| D-Link                            | 11        | 0.21%   |
| Edimax Technology                 | 10        | 0.19%   |
| OPPO Electronics                  | 9         | 0.17%   |
| ASUSTek Computer                  | 9         | 0.17%   |
| Qualcomm                          | 7         | 0.13%   |
| Motorola PCS                      | 7         | 0.13%   |
| Linksys                           | 6         | 0.11%   |
| Ericsson Business Mobile Networks | 6         | 0.11%   |
| T & A Mobile Phones               | 5         | 0.09%   |
| Google                            | 5         | 0.09%   |
| Aquantia                          | 5         | 0.09%   |
| VIA Technologies                  | 4         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.08%   |
| Belkin Components                 | 4         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.06%   |
| Lenovo                            | 3         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1179      | 19.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 276       | 4.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 161       | 2.6%    |
| Intel Wi-Fi 6 AX200                                               | 112       | 1.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 108       | 1.75%   |
| Intel Wireless 7265                                               | 102       | 1.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 93        | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 86        | 1.39%   |
| Intel Wireless 8265 / 8275                                        | 82        | 1.33%   |
| Intel Wireless 7260                                               | 82        | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 76        | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 74        | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 73        | 1.18%   |
| Intel Wi-Fi 6 AX201                                               | 73        | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 66        | 1.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 59        | 0.95%   |
| Intel Wireless 3165                                               | 59        | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                     | 58        | 0.94%   |
| Intel I211 Gigabit Network Connection                             | 57        | 0.92%   |
| Intel Wireless 8260                                               | 56        | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 56        | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 50        | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 45        | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 43        | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 43        | 0.7%    |
| Realtek 802.11ac NIC                                              | 43        | 0.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 43        | 0.7%    |
| Intel Ethernet Connection (2) I219-V                              | 40        | 0.65%   |
| Intel Ethernet Controller I225-V                                  | 39        | 0.63%   |
| Ralink MT7601U Wireless Adapter                                   | 36        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 35        | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 35        | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 34        | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 34        | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 34        | 0.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 33        | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 32        | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 31        | 0.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 31        | 0.5%    |
| Realtek 802.11n WLAN Adapter                                      | 30        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1156      | 38.71%  |
| Realtek Semiconductor                 | 554       | 18.55%  |
| Qualcomm Atheros                      | 514       | 17.21%  |
| Broadcom                              | 272       | 9.11%   |
| Ralink Technology                     | 81        | 2.71%   |
| Broadcom Limited                      | 71        | 2.38%   |
| TP-Link                               | 63        | 2.11%   |
| Ralink                                | 62        | 2.08%   |
| MediaTek                              | 53        | 1.77%   |
| NetGear                               | 22        | 0.74%   |
| Marvell Technology Group              | 20        | 0.67%   |
| Qualcomm Atheros Communications       | 16        | 0.54%   |
| Sierra Wireless                       | 12        | 0.4%    |
| Microsoft                             | 11        | 0.37%   |
| D-Link                                | 11        | 0.37%   |
| Edimax Technology                     | 10        | 0.33%   |
| Dell                                  | 10        | 0.33%   |
| D-Link System                         | 9         | 0.3%    |
| ASUSTek Computer                      | 8         | 0.27%   |
| Linksys                               | 6         | 0.2%    |
| Belkin Components                     | 4         | 0.13%   |
| ZyDAS                                 | 2         | 0.07%   |
| TRENDnet                              | 2         | 0.07%   |
| Gemtek                                | 2         | 0.07%   |
| Fibocom                               | 2         | 0.07%   |
| AVM                                   | 2         | 0.07%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Xiaomi                                | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Qualcomm                              | 1         | 0.03%   |
| Panasonic (Matsushita)                | 1         | 0.03%   |
| Ovislink                              | 1         | 0.03%   |
| Mercucys                              | 1         | 0.03%   |
| Hewlett-Packard                       | 1         | 0.03%   |
| Askey Computer                        | 1         | 0.03%   |
| ADMtek                                | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 112       | 3.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 108       | 3.58%   |
| Intel Wireless 7265                                            | 102       | 3.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 93        | 3.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 86        | 2.85%   |
| Intel Wireless 8265 / 8275                                     | 82        | 2.72%   |
| Intel Wireless 7260                                            | 82        | 2.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 76        | 2.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 73        | 2.42%   |
| Intel Wi-Fi 6 AX201                                            | 73        | 2.42%   |
| Intel Wireless 3165                                            | 59        | 1.96%   |
| Broadcom BCM43142 802.11b/g/n                                  | 58        | 1.92%   |
| Intel Wireless 8260                                            | 56        | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 56        | 1.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 50        | 1.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 45        | 1.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 43        | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 43        | 1.43%   |
| Realtek 802.11ac NIC                                           | 43        | 1.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 43        | 1.43%   |
| Ralink MT7601U Wireless Adapter                                | 36        | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 34        | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 34        | 1.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 34        | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 33        | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 32        | 1.06%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 31        | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 31        | 1.03%   |
| Realtek 802.11n WLAN Adapter                                   | 30        | 1%      |
| Intel WiFi Link 5100                                           | 27        | 0.9%    |
| Intel Wireless-AC 9260                                         | 25        | 0.83%   |
| Intel Centrino Ultimate-N 6300                                 | 25        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 24        | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 23        | 0.76%   |
| Intel Wireless 3160                                            | 22        | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 22        | 0.73%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 22        | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 21        | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 21        | 0.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 20        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1618      | 52.7%   |
| Intel                             | 743       | 24.2%   |
| Qualcomm Atheros                  | 185       | 6.03%   |
| Broadcom                          | 174       | 5.67%   |
| Nvidia                            | 55        | 1.79%   |
| Marvell Technology Group          | 54        | 1.76%   |
| Broadcom Limited                  | 40        | 1.3%    |
| Samsung Electronics               | 35        | 1.14%   |
| ASIX Electronics                  | 29        | 0.94%   |
| Xiaomi                            | 18        | 0.59%   |
| DisplayLink                       | 15        | 0.49%   |
| JMicron Technology                | 11        | 0.36%   |
| Huawei Technologies               | 11        | 0.36%   |
| TP-Link                           | 10        | 0.33%   |
| OPPO Electronics                  | 9         | 0.29%   |
| MediaTek                          | 7         | 0.23%   |
| Qualcomm                          | 6         | 0.2%    |
| Google                            | 5         | 0.16%   |
| Aquantia                          | 5         | 0.16%   |
| VIA Technologies                  | 4         | 0.13%   |
| Motorola PCS                      | 4         | 0.13%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.1%    |
| Hewlett-Packard                   | 3         | 0.1%    |
| Sundance Technology Inc / IC Plus | 2         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.07%   |
| Microsoft                         | 2         | 0.07%   |
| Lenovo                            | 2         | 0.07%   |
| ICS Advent                        | 2         | 0.07%   |
| HMD Global                        | 2         | 0.07%   |
| D-Link System                     | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| T & A Mobile Phones               | 1         | 0.03%   |
| Sun Microsystems                  | 1         | 0.03%   |
| Research In Motion                | 1         | 0.03%   |
| Novatel Wireless                  | 1         | 0.03%   |
| Motorola BCS                      | 1         | 0.03%   |
| LG Electronics                    | 1         | 0.03%   |
| HTC (High Tech Computer)          | 1         | 0.03%   |
| GoPro                             | 1         | 0.03%   |
| Dell                              | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1179      | 37.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 276       | 8.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 161       | 5.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 74        | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 66        | 2.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 59        | 1.9%    |
| Intel I211 Gigabit Network Connection                             | 57        | 1.83%   |
| Intel Ethernet Connection (2) I219-V                              | 40        | 1.29%   |
| Intel Ethernet Controller I225-V                                  | 39        | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 35        | 1.12%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 35        | 1.12%   |
| Intel Ethernet Connection I219-LM                                 | 24        | 0.77%   |
| Intel Ethernet Connection I217-V                                  | 24        | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 24        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 24        | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 22        | 0.71%   |
| Nvidia MCP79 Ethernet                                             | 22        | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 21        | 0.67%   |
| Intel 82577LM Gigabit Network Connection                          | 21        | 0.67%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 21        | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 20        | 0.64%   |
| Nvidia MCP61 Ethernet                                             | 18        | 0.58%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 16        | 0.51%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 0.51%   |
| Intel 82579V Gigabit Network Connection                           | 16        | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 16        | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15        | 0.48%   |
| Intel Ethernet Connection I219-V                                  | 15        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14        | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 14        | 0.45%   |
| Intel Ethernet Connection (7) I219-V                              | 14        | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 13        | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.42%   |
| Intel Ethernet Connection (2) I218-V                              | 13        | 0.42%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 13        | 0.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 12        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2908      | 50.47%  |
| WiFi     | 2795      | 48.51%  |
| Modem    | 47        | 0.82%   |
| Unknown  | 12        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2185      | 60.11%  |
| Ethernet | 1446      | 39.78%  |
| Modem    | 2         | 0.06%   |
| Unknown  | 2         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1892      | 53.9%   |
| 1     | 1436      | 40.91%  |
| 0     | 117       | 3.33%   |
| 3     | 59        | 1.68%   |
| 5     | 3         | 0.09%   |
| 4     | 2         | 0.06%   |
| 7     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2427      | 68.31%  |
| Yes  | 1126      | 31.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 884       | 41.96%  |
| Realtek Semiconductor           | 250       | 11.87%  |
| Qualcomm Atheros Communications | 190       | 9.02%   |
| Broadcom                        | 122       | 5.79%   |
| Apple                           | 121       | 5.74%   |
| Cambridge Silicon Radio         | 108       | 5.13%   |
| IMC Networks                    | 91        | 4.32%   |
| Foxconn / Hon Hai               | 57        | 2.71%   |
| Lite-On Technology              | 51        | 2.42%   |
| Dell                            | 37        | 1.76%   |
| ASUSTek Computer                | 32        | 1.52%   |
| Hewlett-Packard                 | 31        | 1.47%   |
| Toshiba                         | 25        | 1.19%   |
| Marvell Semiconductor           | 18        | 0.85%   |
| Ralink                          | 17        | 0.81%   |
| MediaTek                        | 16        | 0.76%   |
| Realtek                         | 8         | 0.38%   |
| TP-Link                         | 7         | 0.33%   |
| Integrated System Solution      | 6         | 0.28%   |
| Foxconn International           | 6         | 0.28%   |
| Dynex                           | 5         | 0.24%   |
| Alps Electric                   | 5         | 0.24%   |
| Belkin Components               | 4         | 0.19%   |
| Unknown                         | 3         | 0.14%   |
| Askey Computer                  | 2         | 0.09%   |
| Actions                         | 2         | 0.09%   |
| Sitecom Europe                  | 1         | 0.05%   |
| Ralink Technology               | 1         | 0.05%   |
| Qcom                            | 1         | 0.05%   |
| National Semiconductor          | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| D-Link System                   | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 384       | 18.2%   |
| Realtek Bluetooth Radio                             | 173       | 8.2%    |
| Intel AX201 Bluetooth                               | 131       | 6.21%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 108       | 5.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 108       | 5.12%   |
| Intel AX200 Bluetooth                               | 98        | 4.64%   |
| Qualcomm Atheros  Bluetooth Device                  | 81        | 3.84%   |
| Realtek  Bluetooth 4.2 Adapter                      | 54        | 2.56%   |
| Apple Bluetooth Host Controller                     | 54        | 2.56%   |
| Intel AX210 Bluetooth                               | 46        | 2.18%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 34        | 1.61%   |
| IMC Networks Bluetooth Device                       | 33        | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 32        | 1.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 32        | 1.52%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 28        | 1.33%   |
| IMC Networks Bluetooth Radio                        | 28        | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 26        | 1.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 26        | 1.23%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 25        | 1.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 1%      |
| Apple Bluetooth USB Host Controller                 | 21        | 1%      |
| Qualcomm Atheros AR9462 Bluetooth                   | 19        | 0.9%    |
| Marvell Bluetooth and Wireless LAN Composite        | 18        | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 18        | 0.85%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 18        | 0.85%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.81%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.76%   |
| Foxconn / Hon Hai Bluetooth Device                  | 16        | 0.76%   |
| MediaTek Wireless_Device                            | 15        | 0.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 15        | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 14        | 0.66%   |
| IMC Networks Wireless_Device                        | 14        | 0.66%   |
| Apple Bluetooth HCI                                 | 14        | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 0.62%   |
| Dell DW375 Bluetooth Module                         | 13        | 0.62%   |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 0.62%   |
| Intel Bluetooth Device                              | 12        | 0.57%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 12        | 0.57%   |
| Lite-On Bluetooth Device                            | 10        | 0.47%   |
| Toshiba Bluetooth Device                            | 9         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2567      | 54.86%  |
| AMD                                          | 975       | 20.84%  |
| Nvidia                                       | 760       | 16.24%  |
| C-Media Electronics                          | 57        | 1.22%   |
| Creative Labs                                | 22        | 0.47%   |
| Logitech                                     | 20        | 0.43%   |
| Texas Instruments                            | 17        | 0.36%   |
| Kingston Technology                          | 16        | 0.34%   |
| JMTek                                        | 16        | 0.34%   |
| ASUSTek Computer                             | 15        | 0.32%   |
| Generalplus Technology                       | 14        | 0.3%    |
| Realtek Semiconductor                        | 12        | 0.26%   |
| Plantronics                                  | 11        | 0.24%   |
| Razer USA                                    | 10        | 0.21%   |
| VIA Technologies                             | 9         | 0.19%   |
| Creative Technology                          | 9         | 0.19%   |
| GN Netcom                                    | 8         | 0.17%   |
| Tenx Technology                              | 6         | 0.13%   |
| SteelSeries ApS                              | 6         | 0.13%   |
| Lenovo                                       | 6         | 0.13%   |
| Focusrite-Novation                           | 6         | 0.13%   |
| DCMT Technology                              | 5         | 0.11%   |
| Micro Star International                     | 4         | 0.09%   |
| Corsair                                      | 4         | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.06%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.06%   |
| RODE Microphones                             | 3         | 0.06%   |
| PreSonus Audio Electronics                   | 3         | 0.06%   |
| KTMicro                                      | 3         | 0.06%   |
| DSEA A/S                                     | 3         | 0.06%   |
| BR23                                         | 3         | 0.06%   |
| BEHRINGER International                      | 3         | 0.06%   |
| Astro Gaming                                 | 3         | 0.06%   |
| Yamaha                                       | 2         | 0.04%   |
| XMOS                                         | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.04%   |
| Sony                                         | 2         | 0.04%   |
| SAVITECH                                     | 2         | 0.04%   |
| Samsung Electronics                          | 2         | 0.04%   |
| Numark                                       | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 284       | 5.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 274       | 4.93%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 255       | 4.58%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 235       | 4.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 197       | 3.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 148       | 2.66%   |
| AMD FCH Azalia Controller                                                                         | 136       | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 134       | 2.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 134       | 2.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 115       | 2.07%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 112       | 2.01%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 110       | 1.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 107       | 1.92%   |
| Intel 8 Series HD Audio Controller                                                                | 106       | 1.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 102       | 1.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 96        | 1.73%   |
| Intel Cannon Lake PCH cAVS                                                                        | 85        | 1.53%   |
| Intel Broadwell-U Audio Controller                                                                | 84        | 1.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 82        | 1.47%   |
| AMD Kabini HDMI/DP Audio                                                                          | 82        | 1.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 78        | 1.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 76        | 1.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 72        | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 68        | 1.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 63        | 1.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 60        | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 57        | 1.02%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 57        | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 53        | 0.95%   |
| Intel 200 Series PCH HD Audio                                                                     | 51        | 0.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 50        | 0.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 48        | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 43        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 43        | 0.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 43        | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 42        | 0.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 40        | 0.72%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 39        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 39        | 0.7%    |
| Nvidia High Definition Audio Controller                                                           | 38        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 185       | 23.96%  |
| SK hynix               | 144       | 18.65%  |
| Micron Technology      | 81        | 10.49%  |
| Unknown                | 71        | 9.2%    |
| Kingston               | 59        | 7.64%   |
| Crucial                | 39        | 5.05%   |
| Unknown (ABCD)         | 21        | 2.72%   |
| G.Skill                | 21        | 2.72%   |
| Corsair                | 21        | 2.72%   |
| A-DATA Technology      | 16        | 2.07%   |
| Elpida                 | 13        | 1.68%   |
| Ramaxel Technology     | 12        | 1.55%   |
| Team                   | 11        | 1.42%   |
| Unknown                | 9         | 1.17%   |
| Nanya Technology       | 8         | 1.04%   |
| Smart                  | 7         | 0.91%   |
| Patriot                | 5         | 0.65%   |
| Timetec                | 3         | 0.39%   |
| Avant                  | 3         | 0.39%   |
| Wilk                   | 2         | 0.26%   |
| Unifosa                | 2         | 0.26%   |
| Transcend              | 2         | 0.26%   |
| Teikon                 | 2         | 0.26%   |
| Qimonda                | 2         | 0.26%   |
| ff                     | 2         | 0.26%   |
| fef5                   | 2         | 0.26%   |
| Apacer                 | 2         | 0.26%   |
| 4ea5                   | 2         | 0.26%   |
| Unknown (08B5)         | 1         | 0.13%   |
| Unknown (07F7)         | 1         | 0.13%   |
| Unknown (000080B30080) | 1         | 0.13%   |
| SUPER KINGSTEK         | 1         | 0.13%   |
| Strontium              | 1         | 0.13%   |
| Smart Brazil           | 1         | 0.13%   |
| Silicon Power          | 1         | 0.13%   |
| SHARETRONIC            | 1         | 0.13%   |
| PUSKILL                | 1         | 0.13%   |
| ProMos/Mosel Vitelic   | 1         | 0.13%   |
| pqi                    | 1         | 0.13%   |
| PNY                    | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 19        | 2.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 1.09%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 1.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 1.09%   |
| Unknown                                                          | 9         | 1.09%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.73%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.73%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.73%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 5         | 0.61%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.61%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 5         | 0.61%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 4         | 0.49%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.49%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 4         | 0.49%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s    | 4         | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.49%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 4         | 0.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.49%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.49%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.36%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 3         | 0.36%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s              | 3         | 0.36%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 3         | 0.36%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 3         | 0.36%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 3         | 0.36%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 3         | 0.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.36%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 277       | 41.41%  |
| DDR3    | 241       | 36.02%  |
| LPDDR4  | 49        | 7.32%   |
| LPDDR3  | 28        | 4.19%   |
| DDR2    | 28        | 4.19%   |
| SDRAM   | 17        | 2.54%   |
| Unknown | 16        | 2.39%   |
| DDR5    | 5         | 0.75%   |
| LPDDR5  | 4         | 0.6%    |
| DDR     | 4         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 417       | 62.52%  |
| DIMM         | 169       | 25.34%  |
| Row Of Chips | 66        | 9.9%    |
| Unknown      | 8         | 1.2%    |
| Chip         | 6         | 0.9%    |
| FB-DIMM      | 1         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 275       | 36.96%  |
| 4096  | 233       | 31.32%  |
| 2048  | 113       | 15.19%  |
| 16384 | 77        | 10.35%  |
| 1024  | 23        | 3.09%   |
| 32768 | 21        | 2.82%   |
| 512   | 2         | 0.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 155       | 21.47%  |
| 3200    | 111       | 15.37%  |
| 2667    | 95        | 13.16%  |
| 2400    | 63        | 8.73%   |
| 1333    | 44        | 6.09%   |
| 2133    | 27        | 3.74%   |
| 1334    | 26        | 3.6%    |
| 1867    | 18        | 2.49%   |
| 4267    | 17        | 2.35%   |
| 3600    | 14        | 1.94%   |
| 667     | 14        | 1.94%   |
| Unknown | 14        | 1.94%   |
| 800     | 13        | 1.8%    |
| 1066    | 11        | 1.52%   |
| 3266    | 10        | 1.39%   |
| 2048    | 7         | 0.97%   |
| 4800    | 6         | 0.83%   |
| 3000    | 6         | 0.83%   |
| 1866    | 6         | 0.83%   |
| 6400    | 5         | 0.69%   |
| 1800    | 5         | 0.69%   |
| 1067    | 5         | 0.69%   |
| 2933    | 4         | 0.55%   |
| 975     | 4         | 0.55%   |
| 8400    | 3         | 0.42%   |
| 4266    | 3         | 0.42%   |
| 3733    | 3         | 0.42%   |
| 4199    | 2         | 0.28%   |
| 3866    | 2         | 0.28%   |
| 3800    | 2         | 0.28%   |
| 3666    | 2         | 0.28%   |
| 3500    | 2         | 0.28%   |
| 3466    | 2         | 0.28%   |
| 3400    | 2         | 0.28%   |
| 2666    | 2         | 0.28%   |
| 400     | 2         | 0.28%   |
| 5354    | 1         | 0.14%   |
| 5200    | 1         | 0.14%   |
| 4000    | 1         | 0.14%   |
| 3933    | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 24        | 28.57%  |
| Canon                 | 17        | 20.24%  |
| Brother Industries    | 14        | 16.67%  |
| Seiko Epson           | 13        | 15.48%  |
| Samsung Electronics   | 9         | 10.71%  |
| Lexmark International | 3         | 3.57%   |
| Zebra                 | 1         | 1.19%   |
| Ricoh                 | 1         | 1.19%   |
| QinHeng Electronics   | 1         | 1.19%   |
| Konica Minolta        | 1         | 1.19%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                     | 3         | 3.57%   |
| Samsung C460 Series                          | 2         | 2.38%   |
| HP OfficeJet 6950                            | 2         | 2.38%   |
| HP LaserJet Professional P1102w              | 2         | 2.38%   |
| HP ENVY Photo 6200 series                    | 2         | 2.38%   |
| HP DeskJet 2700 series                       | 2         | 2.38%   |
| HP DeskJet 2130 series                       | 2         | 2.38%   |
| Canon TS3100 series                          | 2         | 2.38%   |
| Canon LiDE 400                               | 2         | 2.38%   |
| Brother HL-2140 series                       | 2         | 2.38%   |
| Zebra ZP 450 Printer                         | 1         | 1.19%   |
| Seiko Epson XP-7100 Series                   | 1         | 1.19%   |
| Seiko Epson XP-200 Series                    | 1         | 1.19%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 1.19%   |
| Seiko Epson L805 Series                      | 1         | 1.19%   |
| Seiko Epson L355 Series                      | 1         | 1.19%   |
| Seiko Epson ET-3850 Series                   | 1         | 1.19%   |
| Seiko Epson ET-2820 Series                   | 1         | 1.19%   |
| Seiko Epson ET-2810 Series                   | 1         | 1.19%   |
| Seiko Epson ET-2710 Series                   | 1         | 1.19%   |
| Seiko Epson AcuLaser C1700                   | 1         | 1.19%   |
| Samsung SCX-483x 5x3x Series                 | 1         | 1.19%   |
| Samsung SCX-4623 Series                      | 1         | 1.19%   |
| Samsung SCX-4200 series                      | 1         | 1.19%   |
| Samsung SCX-3400 Series                      | 1         | 1.19%   |
| Samsung ML-2950 Series                       | 1         | 1.19%   |
| Samsung ML-216x Series Laser Printer         | 1         | 1.19%   |
| Samsung M2020 Series                         | 1         | 1.19%   |
| Ricoh SP 112SU                               | 1         | 1.19%   |
| QinHeng CH340S                               | 1         | 1.19%   |
| Lexmark International MX317dn                | 1         | 1.19%   |
| Lexmark International Laser Printer E232     | 1         | 1.19%   |
| Lexmark International 2400 series            | 1         | 1.19%   |
| Konica Minolta PagePro 1380MF                | 1         | 1.19%   |
| HP Smart Tank 510 series                     | 1         | 1.19%   |
| HP PSC 1100 series                           | 1         | 1.19%   |
| HP OfficeJet Pro 9010 series                 | 1         | 1.19%   |
| HP Officejet 6600                            | 1         | 1.19%   |
| HP OfficeJet 5600 (USBHUB)                   | 1         | 1.19%   |
| HP OfficeJet 4650 series                     | 1         | 1.19%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 8         | 61.54%  |
| Seiko Epson     | 3         | 23.08%  |
| Hewlett-Packard | 2         | 15.38%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 14.29%  |
| Seiko Epson Scanner                         | 1         | 7.14%   |
| HP ScanJet 2400c                            | 1         | 7.14%   |
| HP PSC 1200                                 | 1         | 7.14%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 7.14%   |
| Canon CanoScan LiDE 90                      | 1         | 7.14%   |
| Canon CanoScan LiDE 60                      | 1         | 7.14%   |
| Canon CanoScan LIDE 25                      | 1         | 7.14%   |
| Canon CanoScan LiDE 220                     | 1         | 7.14%   |
| Canon CanoScan LiDE 110                     | 1         | 7.14%   |
| Canon CanoScan LiDE 100                     | 1         | 7.14%   |
| Canon CanoScan D660U                        | 1         | 7.14%   |
| Canon CanoScan 8800F                        | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 423       | 20.69%  |
| Microdia                               | 191       | 9.34%   |
| Realtek Semiconductor                  | 170       | 8.32%   |
| IMC Networks                           | 145       | 7.09%   |
| Sunplus Innovation Technology          | 115       | 5.63%   |
| Apple                                  | 109       | 5.33%   |
| Bison Electronics                      | 96        | 4.7%    |
| Cheng Uei Precision Industry (Foxlink) | 93        | 4.55%   |
| Logitech                               | 83        | 4.06%   |
| Quanta                                 | 78        | 3.82%   |
| Suyin                                  | 70        | 3.42%   |
| Syntek                                 | 54        | 2.64%   |
| Lite-On Technology                     | 36        | 1.76%   |
| Acer                                   | 36        | 1.76%   |
| Alcor Micro                            | 33        | 1.61%   |
| Silicon Motion                         | 32        | 1.57%   |
| Samsung Electronics                    | 21        | 1.03%   |
| Luxvisions Innotech Limited            | 21        | 1.03%   |
| Microsoft                              | 19        | 0.93%   |
| Ricoh                                  | 17        | 0.83%   |
| icSpring                               | 14        | 0.68%   |
| Sonix Technology                       | 13        | 0.64%   |
| Z-Star Microelectronics                | 11        | 0.54%   |
| Primax Electronics                     | 11        | 0.54%   |
| Generalplus Technology                 | 11        | 0.54%   |
| ARC International                      | 10        | 0.49%   |
| Lenovo                                 | 9         | 0.44%   |
| GEMBIRD                                | 9         | 0.44%   |
| ALi                                    | 8         | 0.39%   |
| SunplusIT                              | 7         | 0.34%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.24%   |
| Jieli Technology                       | 5         | 0.24%   |
| Importek                               | 5         | 0.24%   |
| Y Media                                | 4         | 0.2%    |
| Sunplus Technology                     | 4         | 0.2%    |
| Razer USA                              | 4         | 0.2%    |
| Intel                                  | 4         | 0.2%    |
| Genesys Logic                          | 4         | 0.2%    |
| Tobii Technology AB                    | 3         | 0.15%   |
| OmniVision Technologies                | 3         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 71        | 3.45%   |
| Microdia Integrated_Webcam_HD                    | 44        | 2.14%   |
| Apple FaceTime HD Camera (Built-in)              | 40        | 1.94%   |
| IMC Networks USB2.0 HD UVC WebCam                | 38        | 1.85%   |
| Realtek Integrated_Webcam_HD                     | 36        | 1.75%   |
| Syntek Integrated Camera                         | 34        | 1.65%   |
| Chicony HD WebCam                                | 33        | 1.6%    |
| Bison Integrated Camera                          | 30        | 1.46%   |
| Apple Built-in iSight                            | 28        | 1.36%   |
| IMC Networks Integrated Camera                   | 27        | 1.31%   |
| Microdia Integrated Webcam                       | 26        | 1.26%   |
| Chicony HP TrueVision HD                         | 26        | 1.26%   |
| Sunplus Integrated_Webcam_HD                     | 25        | 1.21%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR               | 22        | 1.07%   |
| Samsung Galaxy series, misc. (MTP mode)          | 21        | 1.02%   |
| Logitech HD Pro Webcam C920                      | 20        | 0.97%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 20        | 0.97%   |
| Sunplus HD WebCam                                | 18        | 0.87%   |
| Logitech Webcam C270                             | 18        | 0.87%   |
| Realtek USB Camera                               | 17        | 0.83%   |
| Microdia Webcam Vitade AF                        | 17        | 0.83%   |
| Bison Lenovo EasyCamera                          | 17        | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 16        | 0.78%   |
| Chicony EasyCamera                               | 15        | 0.73%   |
| Apple FaceTime HD Camera                         | 15        | 0.73%   |
| Alcor Micro USB 2.0 Web Camera                   | 15        | 0.73%   |
| Realtek Integrated Webcam                        | 14        | 0.68%   |
| Realtek HP Truevision HD                         | 14        | 0.68%   |
| Lite-On HP HD Camera                             | 14        | 0.68%   |
| icSpring camera                                  | 14        | 0.68%   |
| Chicony TOSHIBA Web Camera - HD                  | 14        | 0.68%   |
| Microdia USB 2.0 Camera                          | 13        | 0.63%   |
| Chicony USB2.0 VGA UVC WebCam                    | 13        | 0.63%   |
| Chicony Lenovo EasyCamera                        | 13        | 0.63%   |
| Chicony HP Wide Vision HD Camera                 | 13        | 0.63%   |
| Chicony HP TrueVision HD Camera                  | 13        | 0.63%   |
| Chicony HP HD Camera                             | 13        | 0.63%   |
| Realtek Integrated Webcam HD                     | 12        | 0.58%   |
| Quanta HP Wide Vision HD Camera                  | 12        | 0.58%   |
| Acer Integrated Camera                           | 12        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 133       | 40.43%  |
| Synaptics                          | 51        | 15.5%   |
| Shenzhen Goodix Technology         | 45        | 13.68%  |
| AuthenTec                          | 30        | 9.12%   |
| Upek                               | 24        | 7.29%   |
| Elan Microelectronics              | 20        | 6.08%   |
| LighTuning Technology              | 12        | 3.65%   |
| STMicroelectronics                 | 7         | 2.13%   |
| Samsung Electronics                | 2         | 0.61%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.61%   |
| Next Biometrics                    | 1         | 0.3%    |
| HOLTEK                             | 1         | 0.3%    |
| Focal-systems.Corp                 | 1         | 0.3%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 25        | 7.6%    |
| Shenzhen Goodix  Fingerprint Device                                        | 25        | 7.6%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 6.69%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 5.17%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 4.56%   |
| Validity Sensors VFS491                                                    | 14        | 4.26%   |
| Elan ELAN:ARM-M4                                                           | 14        | 4.26%   |
| Validity Sensors Fingerprint scanner                                       | 11        | 3.34%   |
| AuthenTec AES2810                                                          | 11        | 3.34%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 3.04%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 3.04%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 10        | 3.04%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.74%   |
| Synaptics  WBDI                                                            | 9         | 2.74%   |
| Synaptics UWP WBDI                                                         | 8         | 2.43%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 2.13%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 2.13%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.13%   |
| Synaptics WBDI                                                             | 6         | 1.82%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 1.82%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.52%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.52%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 1.52%   |
| LighTuning Fingerprint Sensor                                              | 5         | 1.52%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.52%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.22%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.22%   |
| AuthenTec AES1600                                                          | 4         | 1.22%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.91%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.91%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.91%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.61%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.61%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.61%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.61%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.61%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.61%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 72        | 52.17%  |
| Alcor Micro                       | 23        | 16.67%  |
| O2 Micro                          | 14        | 10.14%  |
| Upek                              | 6         | 4.35%   |
| Lenovo                            | 6         | 4.35%   |
| Realtek Semiconductor             | 3         | 2.17%   |
| Yubico.com                        | 2         | 1.45%   |
| VASCO Data Security International | 2         | 1.45%   |
| SCM Microsystems                  | 2         | 1.45%   |
| Fujitsu Siemens Computers         | 2         | 1.45%   |
| Advanced Card Systems             | 2         | 1.45%   |
| Reiner SCT Kartensysteme          | 1         | 0.72%   |
| OmniKey                           | 1         | 0.72%   |
| Jing-Mold Enterprise              | 1         | 0.72%   |
| Chicony Electronics               | 1         | 0.72%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 29        | 21.01%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 23        | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 13.04%  |
| Broadcom 5880                                                                | 17        | 12.32%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 13        | 9.42%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 4.35%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 4.35%   |
| Broadcom 58200                                                               | 6         | 4.35%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 2.17%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.45%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 2         | 1.45%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.45%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.72%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.72%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.72%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.72%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.72%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.72%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.72%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 0.72%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.72%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.72%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.72%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2537      | 71.24%  |
| 1     | 828       | 23.25%  |
| 2     | 175       | 4.91%   |
| 3     | 19        | 0.53%   |
| 8     | 1         | 0.03%   |
| 4     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 323       | 26.85%  |
| Graphics card            | 248       | 20.62%  |
| Net/wireless             | 211       | 17.54%  |
| Multimedia controller    | 144       | 11.97%  |
| Chipcard                 | 127       | 10.56%  |
| Bluetooth                | 26        | 2.16%   |
| Storage                  | 24        | 2%      |
| Communication controller | 24        | 2%      |
| Sound                    | 13        | 1.08%   |
| Unassigned class         | 9         | 0.75%   |
| Camera                   | 9         | 0.75%   |
| Net/ethernet             | 8         | 0.67%   |
| Modem                    | 7         | 0.58%   |
| Network                  | 6         | 0.5%    |
| Storage/raid             | 5         | 0.42%   |
| Dvb card                 | 5         | 0.42%   |
| Card reader              | 5         | 0.42%   |
| Storage/ide              | 4         | 0.33%   |
| Storage/nvme             | 2         | 0.17%   |
| Flash memory             | 2         | 0.17%   |
| Unclassified device      | 1         | 0.08%   |

