OpenMandriva 4.3 - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_4.3/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_4.3/Notebook/README.md).

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

Total: 4825

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | X441BA                      | Notebook    | [04e5c55b92](https://linux-hardware.org/?probe=04e5c55b92) | Dec 23, 2023 |
| Dell          | Latitude E7240              | Notebook    | [8fc0b7d8ea](https://linux-hardware.org/?probe=8fc0b7d8ea) | Dec 16, 2023 |
| MSI           | MS-16Y1                     | Notebook    | [41ce29bec7](https://linux-hardware.org/?probe=41ce29bec7) | Dec 12, 2023 |
| Gigabyte      | 965P-S3                     | Desktop     | [b73dd61ca5](https://linux-hardware.org/?probe=b73dd61ca5) | Dec 09, 2023 |
| HP            | 18E5                        | Desktop     | [7b54dc44b4](https://linux-hardware.org/?probe=7b54dc44b4) | Dec 06, 2023 |
| Acer          | TravelMate B311-31          | Notebook    | [9611377d0c](https://linux-hardware.org/?probe=9611377d0c) | Dec 05, 2023 |
| HP            | 8265                        | Desktop     | [1faa811cf0](https://linux-hardware.org/?probe=1faa811cf0) | Dec 03, 2023 |
| Toshiba       | dynabook T552/36HR          | Notebook    | [1e3171aa0a](https://linux-hardware.org/?probe=1e3171aa0a) | Nov 30, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [16dda5c039](https://linux-hardware.org/?probe=16dda5c039) | Nov 29, 2023 |
| Lenovo        | ThinkPad T490 20N3S4VV00    | Notebook    | [1106c092a2](https://linux-hardware.org/?probe=1106c092a2) | Nov 26, 2023 |
| Dell          | Latitude E6430              | Notebook    | [a7befe7f1b](https://linux-hardware.org/?probe=a7befe7f1b) | Nov 23, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [2d0d992e3e](https://linux-hardware.org/?probe=2d0d992e3e) | Nov 22, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [40327ad292](https://linux-hardware.org/?probe=40327ad292) | Nov 20, 2023 |
| HP            | 1589                        | Desktop     | [3e5f417056](https://linux-hardware.org/?probe=3e5f417056) | Nov 20, 2023 |
| Digibras      | NH4CU53                     | Notebook    | [25fff3f773](https://linux-hardware.org/?probe=25fff3f773) | Nov 20, 2023 |
| Dell          | Vostro 1310                 | Notebook    | [bd82e2c035](https://linux-hardware.org/?probe=bd82e2c035) | Nov 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [68aadf1f9b](https://linux-hardware.org/?probe=68aadf1f9b) | Nov 17, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [199a544882](https://linux-hardware.org/?probe=199a544882) | Nov 16, 2023 |
| ASUSTek       | M50Vn                       | Notebook    | [9c35898e36](https://linux-hardware.org/?probe=9c35898e36) | Nov 16, 2023 |
| HP            | 1998                        | Desktop     | [eb9bb55c96](https://linux-hardware.org/?probe=eb9bb55c96) | Nov 16, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [fd1391a823](https://linux-hardware.org/?probe=fd1391a823) | Nov 15, 2023 |
| Foxconn       | 2A92                        | Desktop     | [6cd9ba6728](https://linux-hardware.org/?probe=6cd9ba6728) | Nov 15, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [780d61593a](https://linux-hardware.org/?probe=780d61593a) | Nov 14, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | Desktop     | [0342a78240](https://linux-hardware.org/?probe=0342a78240) | Nov 13, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [613acc55d8](https://linux-hardware.org/?probe=613acc55d8) | Nov 13, 2023 |
| ASUSTek       | X540SAA                     | Notebook    | [1c5e9077a8](https://linux-hardware.org/?probe=1c5e9077a8) | Nov 12, 2023 |
| HP            | 1850                        | Desktop     | [10595f0ac3](https://linux-hardware.org/?probe=10595f0ac3) | Nov 10, 2023 |
| ASUSTek       | PRIME Q270M-C               | Desktop     | [0fcd993247](https://linux-hardware.org/?probe=0fcd993247) | Nov 10, 2023 |
| HP            | ProBook 6470b               | Notebook    | [5b5177e5ed](https://linux-hardware.org/?probe=5b5177e5ed) | Nov 08, 2023 |
| Toshiba       | Satellite C855-10N          | Notebook    | [7afd607141](https://linux-hardware.org/?probe=7afd607141) | Nov 06, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [c3e5415128](https://linux-hardware.org/?probe=c3e5415128) | Nov 06, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [2b5c984cd8](https://linux-hardware.org/?probe=2b5c984cd8) | Nov 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [b0487db7bf](https://linux-hardware.org/?probe=b0487db7bf) | Nov 04, 2023 |
| Toshiba       | TECRA W50-A                 | Notebook    | [ad6c61de24](https://linux-hardware.org/?probe=ad6c61de24) | Nov 04, 2023 |
| ASUSTek       | X550VQ                      | Notebook    | [b6d6ff10aa](https://linux-hardware.org/?probe=b6d6ff10aa) | Nov 03, 2023 |
| Google        | Falco                       | Notebook    | [0ea6d932bf](https://linux-hardware.org/?probe=0ea6d932bf) | Nov 01, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [09d5186c37](https://linux-hardware.org/?probe=09d5186c37) | Oct 30, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [0be3861a6a](https://linux-hardware.org/?probe=0be3861a6a) | Oct 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d0b884f8e1](https://linux-hardware.org/?probe=d0b884f8e1) | Oct 27, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [6ed0863a43](https://linux-hardware.org/?probe=6ed0863a43) | Oct 27, 2023 |
| HP            | 8054                        | Desktop     | [3f9ecca91a](https://linux-hardware.org/?probe=3f9ecca91a) | Oct 26, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [cb27a04bd5](https://linux-hardware.org/?probe=cb27a04bd5) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [dc730f5631](https://linux-hardware.org/?probe=dc730f5631) | Oct 23, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [f30dc155bd](https://linux-hardware.org/?probe=f30dc155bd) | Oct 21, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [968efc7996](https://linux-hardware.org/?probe=968efc7996) | Oct 20, 2023 |
| Lenovo        | 30D0 NOK                    | Desktop     | [e67eff74dc](https://linux-hardware.org/?probe=e67eff74dc) | Oct 20, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [491538303f](https://linux-hardware.org/?probe=491538303f) | Oct 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [6e81d4f878](https://linux-hardware.org/?probe=6e81d4f878) | Oct 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [e1751f1726](https://linux-hardware.org/?probe=e1751f1726) | Oct 17, 2023 |
| HP            | 2000                        | Notebook    | [c2669ff6cb](https://linux-hardware.org/?probe=c2669ff6cb) | Oct 16, 2023 |
| Acer          | Aspire GX-281               | Desktop     | [17fad55365](https://linux-hardware.org/?probe=17fad55365) | Oct 16, 2023 |
| MSI           | GT70 0NC/GT70 0NC           | Notebook    | [24e93d9411](https://linux-hardware.org/?probe=24e93d9411) | Oct 15, 2023 |
| ACTION        | M5A78L-M lX V2              | Desktop     | [fe141a8a31](https://linux-hardware.org/?probe=fe141a8a31) | Oct 15, 2023 |
| Lenovo        | IdeaPad P500 20210          | Notebook    | [ba316cb723](https://linux-hardware.org/?probe=ba316cb723) | Oct 12, 2023 |
| HP            | 158A                        | Desktop     | [9e43d14a8e](https://linux-hardware.org/?probe=9e43d14a8e) | Oct 10, 2023 |
| Dell          | 0FDT3J A03                  | Server      | [8904f36bde](https://linux-hardware.org/?probe=8904f36bde) | Oct 09, 2023 |
| Dell          | Latitude E5440              | Notebook    | [a039ff25ef](https://linux-hardware.org/?probe=a039ff25ef) | Oct 08, 2023 |
| MSI           | MS-7235                     | Desktop     | [afb00bf553](https://linux-hardware.org/?probe=afb00bf553) | Oct 07, 2023 |
| Gigabyte      | GA-K8NE                     | Desktop     | [8cb50a99b7](https://linux-hardware.org/?probe=8cb50a99b7) | Oct 07, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [75d90cf644](https://linux-hardware.org/?probe=75d90cf644) | Oct 07, 2023 |
| Pegatron      | Benicia                     | Desktop     | [b70dfb3fc8](https://linux-hardware.org/?probe=b70dfb3fc8) | Oct 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [a3ea9b4b56](https://linux-hardware.org/?probe=a3ea9b4b56) | Oct 04, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [6ea97d511f](https://linux-hardware.org/?probe=6ea97d511f) | Oct 04, 2023 |
| Lenovo        | ThinkCentre M58p 7484ANU    | Desktop     | [edc20561a3](https://linux-hardware.org/?probe=edc20561a3) | Oct 03, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [c095e62997](https://linux-hardware.org/?probe=c095e62997) | Oct 02, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7fadaa78cd](https://linux-hardware.org/?probe=7fadaa78cd) | Oct 02, 2023 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [a8c796cebf](https://linux-hardware.org/?probe=a8c796cebf) | Oct 01, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [eb33abdaae](https://linux-hardware.org/?probe=eb33abdaae) | Sep 29, 2023 |
| OEGStone      | C4100/C5100                 | Notebook    | [0c27e50b14](https://linux-hardware.org/?probe=0c27e50b14) | Sep 29, 2023 |
| HP            | 3398                        | Desktop     | [13aa132a7d](https://linux-hardware.org/?probe=13aa132a7d) | Sep 29, 2023 |
| WesternDig... | BBC 0001                    | Desktop     | [b31e10d01b](https://linux-hardware.org/?probe=b31e10d01b) | Sep 29, 2023 |
| WesternDig... | BBC 0001                    | Desktop     | [ba340393f7](https://linux-hardware.org/?probe=ba340393f7) | Sep 29, 2023 |
| Pegatron      | Benicia                     | Desktop     | [840b02e356](https://linux-hardware.org/?probe=840b02e356) | Sep 29, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [c815d636ce](https://linux-hardware.org/?probe=c815d636ce) | Sep 28, 2023 |
| HP            | 84F5                        | Mini pc     | [ef936bc0cb](https://linux-hardware.org/?probe=ef936bc0cb) | Sep 28, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [19c07d0fca](https://linux-hardware.org/?probe=19c07d0fca) | Sep 27, 2023 |
| Dell          | Vostro 1000                 | Notebook    | [38499a1a0f](https://linux-hardware.org/?probe=38499a1a0f) | Sep 25, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [10ec627bad](https://linux-hardware.org/?probe=10ec627bad) | Sep 25, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [e74a87d3f4](https://linux-hardware.org/?probe=e74a87d3f4) | Sep 25, 2023 |
| Toshiba       | Satellite S50t-B            | Notebook    | [a574ee83ff](https://linux-hardware.org/?probe=a574ee83ff) | Sep 24, 2023 |
| Lenovo        | ThinkCentre A70z 0401B7P    | Desktop     | [21a635940f](https://linux-hardware.org/?probe=21a635940f) | Sep 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [03d461d3af](https://linux-hardware.org/?probe=03d461d3af) | Sep 22, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [05c9cbc8e5](https://linux-hardware.org/?probe=05c9cbc8e5) | Sep 22, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [3d3b14f0f9](https://linux-hardware.org/?probe=3d3b14f0f9) | Sep 21, 2023 |
| ASUSTek       | B150M-C D3                  | Desktop     | [179a66ec43](https://linux-hardware.org/?probe=179a66ec43) | Sep 19, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [b21eddb040](https://linux-hardware.org/?probe=b21eddb040) | Sep 19, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [fa9b30f699](https://linux-hardware.org/?probe=fa9b30f699) | Sep 18, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [24efefc447](https://linux-hardware.org/?probe=24efefc447) | Sep 17, 2023 |
| ASUSTek       | P52F                        | Notebook    | [6be70b4b24](https://linux-hardware.org/?probe=6be70b4b24) | Sep 17, 2023 |
| Dell          | 048DY8 A00                  | Desktop     | [3cc67a5e62](https://linux-hardware.org/?probe=3cc67a5e62) | Sep 15, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [3f55a69040](https://linux-hardware.org/?probe=3f55a69040) | Sep 11, 2023 |
| Dell          | Latitude E6410              | Notebook    | [9b57eaa1eb](https://linux-hardware.org/?probe=9b57eaa1eb) | Sep 09, 2023 |
| Toshiba       | STI 006998G                 | Desktop     | [d34aadcc92](https://linux-hardware.org/?probe=d34aadcc92) | Sep 07, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [757ebbe056](https://linux-hardware.org/?probe=757ebbe056) | Sep 06, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [19dddb0418](https://linux-hardware.org/?probe=19dddb0418) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [34fb398b78](https://linux-hardware.org/?probe=34fb398b78) | Sep 06, 2023 |
| Intel         | NUC11PABi5 M68265-501       | Mini pc     | [3266fb476d](https://linux-hardware.org/?probe=3266fb476d) | Sep 06, 2023 |
| HP            | Pavilion dv4                | Notebook    | [0b01aaddd6](https://linux-hardware.org/?probe=0b01aaddd6) | Sep 06, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [5dca7c7315](https://linux-hardware.org/?probe=5dca7c7315) | Sep 05, 2023 |
| Acer          | Aspire 4741                 | Notebook    | [2f2b673625](https://linux-hardware.org/?probe=2f2b673625) | Sep 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [02c4374b47](https://linux-hardware.org/?probe=02c4374b47) | Sep 04, 2023 |
| Foxconn       | G31MX Series                | Desktop     | [4b4c5fb5f8](https://linux-hardware.org/?probe=4b4c5fb5f8) | Sep 04, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [a3356b9a91](https://linux-hardware.org/?probe=a3356b9a91) | Sep 03, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [95b036ac9a](https://linux-hardware.org/?probe=95b036ac9a) | Sep 03, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [12894bacfb](https://linux-hardware.org/?probe=12894bacfb) | Sep 03, 2023 |
| Dell          | Studio 1735                 | Notebook    | [88cf1723e0](https://linux-hardware.org/?probe=88cf1723e0) | Sep 03, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [9651a05c1d](https://linux-hardware.org/?probe=9651a05c1d) | Sep 03, 2023 |
| Chuwi         | LapBook Pro                 | Notebook    | [4dd222efaa](https://linux-hardware.org/?probe=4dd222efaa) | Sep 01, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [f11dacb362](https://linux-hardware.org/?probe=f11dacb362) | Sep 01, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [0f9de0fdf4](https://linux-hardware.org/?probe=0f9de0fdf4) | Sep 01, 2023 |
| Foxconn       | A6VMX 0A                    | Desktop     | [338cdb7d40](https://linux-hardware.org/?probe=338cdb7d40) | Sep 01, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [ff1be33f8e](https://linux-hardware.org/?probe=ff1be33f8e) | Sep 01, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [8ee240ba0b](https://linux-hardware.org/?probe=8ee240ba0b) | Sep 01, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [b6a24176aa](https://linux-hardware.org/?probe=b6a24176aa) | Aug 31, 2023 |
| HP            | 18E5                        | Desktop     | [75c3b34f87](https://linux-hardware.org/?probe=75c3b34f87) | Aug 31, 2023 |
| ASUSTek       | S301LP                      | Notebook    | [d33b635602](https://linux-hardware.org/?probe=d33b635602) | Aug 31, 2023 |
| Gigabyte      | B450M K-CF                  | Desktop     | [2086d348b2](https://linux-hardware.org/?probe=2086d348b2) | Aug 31, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [4a2115b7ae](https://linux-hardware.org/?probe=4a2115b7ae) | Aug 31, 2023 |
| ASUSTek       | K501LX                      | Notebook    | [ca56f1b803](https://linux-hardware.org/?probe=ca56f1b803) | Aug 30, 2023 |
| ASUSTek       | P8H61 EVO                   | Desktop     | [facd465366](https://linux-hardware.org/?probe=facd465366) | Aug 30, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [23712e9380](https://linux-hardware.org/?probe=23712e9380) | Aug 28, 2023 |
| Positivo      | POS-PQ45AU                  | Desktop     | [aba45a4f14](https://linux-hardware.org/?probe=aba45a4f14) | Aug 27, 2023 |
| Dell          | XPS M1330                   | Notebook    | [ce3d41b222](https://linux-hardware.org/?probe=ce3d41b222) | Aug 27, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9f1872b5e9](https://linux-hardware.org/?probe=9f1872b5e9) | Aug 26, 2023 |
| Dell          | Latitude E6440              | Notebook    | [759a858fa1](https://linux-hardware.org/?probe=759a858fa1) | Aug 25, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [7aca2d97c0](https://linux-hardware.org/?probe=7aca2d97c0) | Aug 25, 2023 |
| GEEKOM        | GM08i3T                     | Desktop     | [36ea06968d](https://linux-hardware.org/?probe=36ea06968d) | Aug 23, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [abae84243d](https://linux-hardware.org/?probe=abae84243d) | Aug 23, 2023 |
| HP            | Compaq nc8430 (EM741AV)     | Notebook    | [02d656a746](https://linux-hardware.org/?probe=02d656a746) | Aug 22, 2023 |
| Dell          | Inspiron 1720               | Notebook    | [577e8e228f](https://linux-hardware.org/?probe=577e8e228f) | Aug 22, 2023 |
| ASRock        | 890GX Pro3                  | Desktop     | [c36b43c52a](https://linux-hardware.org/?probe=c36b43c52a) | Aug 21, 2023 |
| eMachines     | E520 V1.06                  | Notebook    | [bd63874856](https://linux-hardware.org/?probe=bd63874856) | Aug 20, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [6d8baa3226](https://linux-hardware.org/?probe=6d8baa3226) | Aug 20, 2023 |
| Gigabyte      | GA-N680SLI-DQ6              | Desktop     | [0838a31aaf](https://linux-hardware.org/?probe=0838a31aaf) | Aug 19, 2023 |
| Danew         | Dbook 131                   | Notebook    | [35ea124809](https://linux-hardware.org/?probe=35ea124809) | Aug 19, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [76dda9cde6](https://linux-hardware.org/?probe=76dda9cde6) | Aug 19, 2023 |
| Intel         | DE3815TYKH H26998-402       | Desktop     | [a2a8c567a3](https://linux-hardware.org/?probe=a2a8c567a3) | Aug 17, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [83e6c3323d](https://linux-hardware.org/?probe=83e6c3323d) | Aug 16, 2023 |
| HP            | 3031h                       | Desktop     | [2f9084013a](https://linux-hardware.org/?probe=2f9084013a) | Aug 13, 2023 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [f900ebabde](https://linux-hardware.org/?probe=f900ebabde) | Aug 13, 2023 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [2a494a04b5](https://linux-hardware.org/?probe=2a494a04b5) | Aug 12, 2023 |
| Acer          | Aspire ES1-431              | Notebook    | [171fd219cc](https://linux-hardware.org/?probe=171fd219cc) | Aug 10, 2023 |
| HP            | 18E7                        | Desktop     | [ff27f888f0](https://linux-hardware.org/?probe=ff27f888f0) | Aug 10, 2023 |
| Dell          | 040DDP A00                  | Desktop     | [13d99d66da](https://linux-hardware.org/?probe=13d99d66da) | Aug 09, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [b280ab65dd](https://linux-hardware.org/?probe=b280ab65dd) | Aug 09, 2023 |
| Dell          | 0P301D A00                  | Desktop     | [e5091194fb](https://linux-hardware.org/?probe=e5091194fb) | Aug 08, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [eab0544dc6](https://linux-hardware.org/?probe=eab0544dc6) | Aug 06, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [f5df04e0e6](https://linux-hardware.org/?probe=f5df04e0e6) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c94a18b924](https://linux-hardware.org/?probe=c94a18b924) | Aug 02, 2023 |
| Toshiba       | Satellite C850-B239         | Notebook    | [a075f60c70](https://linux-hardware.org/?probe=a075f60c70) | Aug 02, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [96e4579b7b](https://linux-hardware.org/?probe=96e4579b7b) | Aug 01, 2023 |
| HP            | 18E7                        | Desktop     | [339050cd65](https://linux-hardware.org/?probe=339050cd65) | Aug 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3a500cdb55](https://linux-hardware.org/?probe=3a500cdb55) | Aug 01, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b57f8ee5f8](https://linux-hardware.org/?probe=b57f8ee5f8) | Aug 01, 2023 |
| Dell          | 0C27VV A03                  | Desktop     | [75ff82774b](https://linux-hardware.org/?probe=75ff82774b) | Jul 31, 2023 |
| HP            | 84EE 1100                   | All in one  | [52d1413f34](https://linux-hardware.org/?probe=52d1413f34) | Jul 29, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [ee17cd82e7](https://linux-hardware.org/?probe=ee17cd82e7) | Jul 27, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [792e9db762](https://linux-hardware.org/?probe=792e9db762) | Jul 27, 2023 |
| Toshiba       | Satellite C50D-A-11G        | Notebook    | [b67508b754](https://linux-hardware.org/?probe=b67508b754) | Jul 27, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [1d4e6c23cf](https://linux-hardware.org/?probe=1d4e6c23cf) | Jul 27, 2023 |
| HP            | 212B                        | Desktop     | [8e6a290d51](https://linux-hardware.org/?probe=8e6a290d51) | Jul 25, 2023 |
| Intel         | powered classmate PC        | Notebook    | [ccbb0cb45a](https://linux-hardware.org/?probe=ccbb0cb45a) | Jul 24, 2023 |
| Dell          | 0VD92X A00                  | Desktop     | [675e646d05](https://linux-hardware.org/?probe=675e646d05) | Jul 23, 2023 |
| Intel         | JSL MRD                     | Desktop     | [4c9c765884](https://linux-hardware.org/?probe=4c9c765884) | Jul 21, 2023 |
| Dell          | 0M863N A01                  | Desktop     | [682fc212b6](https://linux-hardware.org/?probe=682fc212b6) | Jul 20, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [61fa9a2c91](https://linux-hardware.org/?probe=61fa9a2c91) | Jul 20, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [140474e198](https://linux-hardware.org/?probe=140474e198) | Jul 19, 2023 |
| Intel X79     | Unknown                     | Desktop     | [360facd1fb](https://linux-hardware.org/?probe=360facd1fb) | Jul 19, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [9853a8cf46](https://linux-hardware.org/?probe=9853a8cf46) | Jul 18, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [afb16ac821](https://linux-hardware.org/?probe=afb16ac821) | Jul 17, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [3cc36162b8](https://linux-hardware.org/?probe=3cc36162b8) | Jul 16, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [87763ca861](https://linux-hardware.org/?probe=87763ca861) | Jul 16, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [46cfd28279](https://linux-hardware.org/?probe=46cfd28279) | Jul 16, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [e302c823fc](https://linux-hardware.org/?probe=e302c823fc) | Jul 13, 2023 |
| HP            | 18E8                        | Desktop     | [b892f0dd28](https://linux-hardware.org/?probe=b892f0dd28) | Jul 12, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7a8f3c985f](https://linux-hardware.org/?probe=7a8f3c985f) | Jul 11, 2023 |
| ASUSTek       | X756UXK                     | Notebook    | [746e141543](https://linux-hardware.org/?probe=746e141543) | Jul 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [144cb029ba](https://linux-hardware.org/?probe=144cb029ba) | Jul 08, 2023 |
| Dell          | 01TKCC A01                  | Desktop     | [b3ab41fd8f](https://linux-hardware.org/?probe=b3ab41fd8f) | Jul 08, 2023 |
| Dell          | 04P1GP A01                  | All in one  | [3a9a768d92](https://linux-hardware.org/?probe=3a9a768d92) | Jul 08, 2023 |
| Lenovo        | G485 20136                  | Notebook    | [9ce1d97d02](https://linux-hardware.org/?probe=9ce1d97d02) | Jul 07, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [c9ccceb765](https://linux-hardware.org/?probe=c9ccceb765) | Jul 07, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [2cb98a7961](https://linux-hardware.org/?probe=2cb98a7961) | Jul 06, 2023 |
| ASUSTek       | TP501UA                     | Notebook    | [ee28aacdd1](https://linux-hardware.org/?probe=ee28aacdd1) | Jul 05, 2023 |
| ASUSTek       | 1015PN                      | Notebook    | [7482ea5fc2](https://linux-hardware.org/?probe=7482ea5fc2) | Jul 03, 2023 |
| ECS           | H55H-M2                     | Desktop     | [344ce5bb17](https://linux-hardware.org/?probe=344ce5bb17) | Jul 03, 2023 |
| ASUSTek       | UN45                        | Desktop     | [487845dd55](https://linux-hardware.org/?probe=487845dd55) | Jul 03, 2023 |
| Gigabyte      | 965P-S3                     | Desktop     | [7aa7550205](https://linux-hardware.org/?probe=7aa7550205) | Jul 02, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [7beeaf657d](https://linux-hardware.org/?probe=7beeaf657d) | Jul 02, 2023 |
| Acer          | Aspire E5-772               | Notebook    | [b33f11c7c9](https://linux-hardware.org/?probe=b33f11c7c9) | Jul 01, 2023 |
| ASUSTek       | N752VX                      | Notebook    | [d4fd40a9f3](https://linux-hardware.org/?probe=d4fd40a9f3) | Jul 01, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [b6be2d7f9f](https://linux-hardware.org/?probe=b6be2d7f9f) | Jun 30, 2023 |
| HP            | Notebook                    | Notebook    | [a178cbf707](https://linux-hardware.org/?probe=a178cbf707) | Jun 29, 2023 |
| Acer          | Aspire TC-705               | Desktop     | [326f873ac3](https://linux-hardware.org/?probe=326f873ac3) | Jun 29, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [d2a1351f86](https://linux-hardware.org/?probe=d2a1351f86) | Jun 28, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [2faeb24e37](https://linux-hardware.org/?probe=2faeb24e37) | Jun 27, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [90067b8232](https://linux-hardware.org/?probe=90067b8232) | Jun 27, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [a31908b24b](https://linux-hardware.org/?probe=a31908b24b) | Jun 25, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [4269ca2c0b](https://linux-hardware.org/?probe=4269ca2c0b) | Jun 25, 2023 |
| HP            | 8055                        | Desktop     | [7fac5a1354](https://linux-hardware.org/?probe=7fac5a1354) | Jun 24, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [cdc135487b](https://linux-hardware.org/?probe=cdc135487b) | Jun 24, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [9408842ffc](https://linux-hardware.org/?probe=9408842ffc) | Jun 24, 2023 |
| MSI           | MS-7360                     | Desktop     | [9a0d46b069](https://linux-hardware.org/?probe=9a0d46b069) | Jun 23, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [9d234065ed](https://linux-hardware.org/?probe=9d234065ed) | Jun 22, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0b8cf1cae7](https://linux-hardware.org/?probe=0b8cf1cae7) | Jun 22, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [4e877b9c8d](https://linux-hardware.org/?probe=4e877b9c8d) | Jun 22, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [fc54744449](https://linux-hardware.org/?probe=fc54744449) | Jun 22, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [09f4615df6](https://linux-hardware.org/?probe=09f4615df6) | Jun 22, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4560c6d34d](https://linux-hardware.org/?probe=4560c6d34d) | Jun 19, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [35de204113](https://linux-hardware.org/?probe=35de204113) | Jun 19, 2023 |
| MSI           | 2AE0                        | Desktop     | [fdfc88e5da](https://linux-hardware.org/?probe=fdfc88e5da) | Jun 18, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [651988e989](https://linux-hardware.org/?probe=651988e989) | Jun 18, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3c45e54fd2](https://linux-hardware.org/?probe=3c45e54fd2) | Jun 17, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [adc38f998a](https://linux-hardware.org/?probe=adc38f998a) | Jun 17, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [a587493314](https://linux-hardware.org/?probe=a587493314) | Jun 16, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [8571bdf994](https://linux-hardware.org/?probe=8571bdf994) | Jun 15, 2023 |
| Acer          | Veriton M6630G V:1.0        | Desktop     | [d58cd3aa7d](https://linux-hardware.org/?probe=d58cd3aa7d) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [922c598503](https://linux-hardware.org/?probe=922c598503) | Jun 14, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | Desktop     | [26e6a1f816](https://linux-hardware.org/?probe=26e6a1f816) | Jun 13, 2023 |
| Lenovo        | 103D SDK0Q40112 WIN 3305... | Desktop     | [5c2eef3678](https://linux-hardware.org/?probe=5c2eef3678) | Jun 12, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [b5b264d1e8](https://linux-hardware.org/?probe=b5b264d1e8) | Jun 12, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [d592b19e9b](https://linux-hardware.org/?probe=d592b19e9b) | Jun 10, 2023 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [eea1c44d94](https://linux-hardware.org/?probe=eea1c44d94) | Jun 10, 2023 |
| Medion        | Akoya E7226                 | Notebook    | [b46a96183b](https://linux-hardware.org/?probe=b46a96183b) | Jun 10, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [68a77b486e](https://linux-hardware.org/?probe=68a77b486e) | Jun 09, 2023 |
| Toshiba       | Satellite L635              | Notebook    | [4f124d1525](https://linux-hardware.org/?probe=4f124d1525) | Jun 09, 2023 |
| Biostar       | H610MH                      | Desktop     | [2cd4e157d4](https://linux-hardware.org/?probe=2cd4e157d4) | Jun 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [44cf28ec0e](https://linux-hardware.org/?probe=44cf28ec0e) | Jun 05, 2023 |
| HP            | Pavilion g4                 | Notebook    | [af0c33de44](https://linux-hardware.org/?probe=af0c33de44) | Jun 05, 2023 |
| Dell          | Latitude E4300              | Notebook    | [cfd95b7e5e](https://linux-hardware.org/?probe=cfd95b7e5e) | Jun 05, 2023 |
| HP            | 1850                        | Desktop     | [bddc14be8b](https://linux-hardware.org/?probe=bddc14be8b) | Jun 05, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [0564fd483d](https://linux-hardware.org/?probe=0564fd483d) | Jun 04, 2023 |
| HP            | 1495                        | Desktop     | [0cbf6bee1f](https://linux-hardware.org/?probe=0cbf6bee1f) | Jun 04, 2023 |
| MSI           | Boston                      | Desktop     | [95b4d5183d](https://linux-hardware.org/?probe=95b4d5183d) | Jun 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [1b82c0c3c8](https://linux-hardware.org/?probe=1b82c0c3c8) | Jun 02, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [7b5291c6f8](https://linux-hardware.org/?probe=7b5291c6f8) | Jun 02, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [417320253a](https://linux-hardware.org/?probe=417320253a) | May 31, 2023 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [1ac394c97c](https://linux-hardware.org/?probe=1ac394c97c) | May 30, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [528f7440b7](https://linux-hardware.org/?probe=528f7440b7) | May 29, 2023 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [e58b7bfc92](https://linux-hardware.org/?probe=e58b7bfc92) | May 29, 2023 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [bf3b702d7a](https://linux-hardware.org/?probe=bf3b702d7a) | May 28, 2023 |
| HP            | Pavilion dm4                | Notebook    | [51b921c72d](https://linux-hardware.org/?probe=51b921c72d) | May 28, 2023 |
| Sony          | VGN-FZ31Z                   | Notebook    | [31c6913c14](https://linux-hardware.org/?probe=31c6913c14) | May 26, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [6f1a19d503](https://linux-hardware.org/?probe=6f1a19d503) | May 25, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [149a19eeeb](https://linux-hardware.org/?probe=149a19eeeb) | May 24, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [f0b7bf3520](https://linux-hardware.org/?probe=f0b7bf3520) | May 23, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [f65eac842b](https://linux-hardware.org/?probe=f65eac842b) | May 23, 2023 |
| Lenovo        | ThinkPad T490 20N3S4VV00    | Notebook    | [5c190a4d57](https://linux-hardware.org/?probe=5c190a4d57) | May 22, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [c1df991f26](https://linux-hardware.org/?probe=c1df991f26) | May 19, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [39725fefa4](https://linux-hardware.org/?probe=39725fefa4) | May 19, 2023 |
| HP            | 0A54h                       | Desktop     | [76953e42f8](https://linux-hardware.org/?probe=76953e42f8) | May 18, 2023 |
| Acer          | Aspire A114-32              | Notebook    | [d17a909427](https://linux-hardware.org/?probe=d17a909427) | May 18, 2023 |
| UMAX          | VisionBook 13Wg Flex        | Convertible | [170db25383](https://linux-hardware.org/?probe=170db25383) | May 17, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [4bd367b4c7](https://linux-hardware.org/?probe=4bd367b4c7) | May 17, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [f50517b1c5](https://linux-hardware.org/?probe=f50517b1c5) | May 17, 2023 |
| HP            | 18E5                        | Desktop     | [5e25e2156a](https://linux-hardware.org/?probe=5e25e2156a) | May 16, 2023 |
| Lenovo        | ThinkPad X100e 0022CTO      | Notebook    | [842b7a3ee2](https://linux-hardware.org/?probe=842b7a3ee2) | May 14, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | Notebook    | [d697ec6804](https://linux-hardware.org/?probe=d697ec6804) | May 14, 2023 |
| ASRock        | G41M-GS3                    | Desktop     | [8859685e86](https://linux-hardware.org/?probe=8859685e86) | May 13, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [cbd408a1a6](https://linux-hardware.org/?probe=cbd408a1a6) | May 13, 2023 |
| Dell          | 0W0CHX A00                  | Desktop     | [60defd2bfe](https://linux-hardware.org/?probe=60defd2bfe) | May 12, 2023 |
| Acer          | RS880M05                    | Desktop     | [5952c105f6](https://linux-hardware.org/?probe=5952c105f6) | May 12, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [db910d4ee1](https://linux-hardware.org/?probe=db910d4ee1) | May 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [68afb54270](https://linux-hardware.org/?probe=68afb54270) | May 10, 2023 |
| HP            | 83EB                        | All in one  | [0abdbdd77b](https://linux-hardware.org/?probe=0abdbdd77b) | May 10, 2023 |
| ASUSTek       | M4A78L-M                    | Desktop     | [1a843c3a7f](https://linux-hardware.org/?probe=1a843c3a7f) | May 10, 2023 |
| HP            | Compaq Mini CQ10-500        | Notebook    | [4b9087625d](https://linux-hardware.org/?probe=4b9087625d) | May 09, 2023 |
| Sony          | VGN-FZ31Z                   | Notebook    | [6fe358200a](https://linux-hardware.org/?probe=6fe358200a) | May 09, 2023 |
| HP            | ProBook 440 G1              | Notebook    | [aea73943e8](https://linux-hardware.org/?probe=aea73943e8) | May 09, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [a0073c6ff3](https://linux-hardware.org/?probe=a0073c6ff3) | May 08, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [eeb083abcd](https://linux-hardware.org/?probe=eeb083abcd) | May 07, 2023 |
| Shuttle       | FZ77                        | Desktop     | [e4a71bcb2d](https://linux-hardware.org/?probe=e4a71bcb2d) | May 07, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [6c404ee491](https://linux-hardware.org/?probe=6c404ee491) | May 06, 2023 |
| Quanta        | JW2                         | Notebook    | [eb9ff2a263](https://linux-hardware.org/?probe=eb9ff2a263) | May 06, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [c9a5bee99d](https://linux-hardware.org/?probe=c9a5bee99d) | May 05, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [d8f78a98f2](https://linux-hardware.org/?probe=d8f78a98f2) | May 05, 2023 |
| eMachines     | eMG620                      | Notebook    | [224dc7209e](https://linux-hardware.org/?probe=224dc7209e) | May 04, 2023 |
| MSI           | 760GM-P34                   | Desktop     | [cb75fca473](https://linux-hardware.org/?probe=cb75fca473) | May 04, 2023 |
| Toshiba       | Satellite C640              | Notebook    | [20d436bfa7](https://linux-hardware.org/?probe=20d436bfa7) | May 02, 2023 |
| MSI           | MS-7025                     | Desktop     | [a15dc17cfc](https://linux-hardware.org/?probe=a15dc17cfc) | May 02, 2023 |
| MAXSUN        | MS-A86FX FS M.3             | Desktop     | [3ce20d3b05](https://linux-hardware.org/?probe=3ce20d3b05) | May 01, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [1fb0ca13ff](https://linux-hardware.org/?probe=1fb0ca13ff) | May 01, 2023 |
| Sony          | VGN-AW11M_H                 | Notebook    | [2c9f98ca31](https://linux-hardware.org/?probe=2c9f98ca31) | May 01, 2023 |
| DIEBOLD       | NM70-I                      | Desktop     | [c01a40d58c](https://linux-hardware.org/?probe=c01a40d58c) | Apr 30, 2023 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [32942be783](https://linux-hardware.org/?probe=32942be783) | Apr 29, 2023 |
| Lenovo        | Unknown                     | Notebook    | [33a55a2347](https://linux-hardware.org/?probe=33a55a2347) | Apr 29, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [3056c07eb6](https://linux-hardware.org/?probe=3056c07eb6) | Apr 29, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [e1e3261c15](https://linux-hardware.org/?probe=e1e3261c15) | Apr 29, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [8f1db96b6f](https://linux-hardware.org/?probe=8f1db96b6f) | Apr 29, 2023 |
| AZW           | MINI S 10                   | Desktop     | [12ba32f977](https://linux-hardware.org/?probe=12ba32f977) | Apr 28, 2023 |
| Acer          | Swift SF314-59              | Notebook    | [a84de33c38](https://linux-hardware.org/?probe=a84de33c38) | Apr 28, 2023 |
| Dell          | Latitude D830               | Notebook    | [2ab0772efb](https://linux-hardware.org/?probe=2ab0772efb) | Apr 28, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [a63003783d](https://linux-hardware.org/?probe=a63003783d) | Apr 27, 2023 |
| Dell          | 0XKD8M A00                  | All in one  | [1629350aa9](https://linux-hardware.org/?probe=1629350aa9) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [f549cb502c](https://linux-hardware.org/?probe=f549cb502c) | Apr 27, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [238598d9ab](https://linux-hardware.org/?probe=238598d9ab) | Apr 26, 2023 |
| Acer          | Aspire 5737Z                | Notebook    | [121eda50b8](https://linux-hardware.org/?probe=121eda50b8) | Apr 26, 2023 |
| Fujitsu       | FMVA05004                   | Notebook    | [c494a8453d](https://linux-hardware.org/?probe=c494a8453d) | Apr 26, 2023 |
| Toshiba       | dynabook TV/68KBL           | Notebook    | [19c59e3701](https://linux-hardware.org/?probe=19c59e3701) | Apr 26, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [5c79032176](https://linux-hardware.org/?probe=5c79032176) | Apr 25, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [e46f340908](https://linux-hardware.org/?probe=e46f340908) | Apr 25, 2023 |
| HP            | Pavilion g4                 | Notebook    | [5e2040a91f](https://linux-hardware.org/?probe=5e2040a91f) | Apr 25, 2023 |
| ASRock        | AB350M-HDV                  | Desktop     | [44ac797451](https://linux-hardware.org/?probe=44ac797451) | Apr 25, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [ae90303c3a](https://linux-hardware.org/?probe=ae90303c3a) | Apr 25, 2023 |
| Lenovo        | ThinkCentre A70z 0401G6G    | Desktop     | [b1b8bf3df6](https://linux-hardware.org/?probe=b1b8bf3df6) | Apr 25, 2023 |
| HP            | ProBook 5320m               | Notebook    | [7597710994](https://linux-hardware.org/?probe=7597710994) | Apr 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b72361ca9e](https://linux-hardware.org/?probe=b72361ca9e) | Apr 24, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [961a066e6b](https://linux-hardware.org/?probe=961a066e6b) | Apr 24, 2023 |
| Toshiba       | Satellite C855              | Notebook    | [b383279bda](https://linux-hardware.org/?probe=b383279bda) | Apr 23, 2023 |
| HP            | 0AA8h                       | Desktop     | [b927834a03](https://linux-hardware.org/?probe=b927834a03) | Apr 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e72f221b5b](https://linux-hardware.org/?probe=e72f221b5b) | Apr 23, 2023 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [ec36f4ada2](https://linux-hardware.org/?probe=ec36f4ada2) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [bf1dbf49a8](https://linux-hardware.org/?probe=bf1dbf49a8) | Apr 22, 2023 |
| Gigabyte      | EP45-UD3                    | Desktop     | [5d45f63468](https://linux-hardware.org/?probe=5d45f63468) | Apr 22, 2023 |
| Biostar       | A75MG                       | Desktop     | [50cb5c256e](https://linux-hardware.org/?probe=50cb5c256e) | Apr 22, 2023 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [59ad89854c](https://linux-hardware.org/?probe=59ad89854c) | Apr 22, 2023 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Notebook    | [503c99202e](https://linux-hardware.org/?probe=503c99202e) | Apr 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b3613186fa](https://linux-hardware.org/?probe=b3613186fa) | Apr 21, 2023 |
| Intel         | DB65AL AAG12530-310         | Desktop     | [c625f3747a](https://linux-hardware.org/?probe=c625f3747a) | Apr 21, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [78adec215e](https://linux-hardware.org/?probe=78adec215e) | Apr 21, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [5f1a1c6abd](https://linux-hardware.org/?probe=5f1a1c6abd) | Apr 20, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [68a7470480](https://linux-hardware.org/?probe=68a7470480) | Apr 19, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [53d3a8d066](https://linux-hardware.org/?probe=53d3a8d066) | Apr 19, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WX0W    | Notebook    | [97447a0777](https://linux-hardware.org/?probe=97447a0777) | Apr 19, 2023 |
| Lenovo        | ThinkPad T540p 20BECTO1W... | Notebook    | [ccb7f92798](https://linux-hardware.org/?probe=ccb7f92798) | Apr 19, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0244194778](https://linux-hardware.org/?probe=0244194778) | Apr 17, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [8e99149abe](https://linux-hardware.org/?probe=8e99149abe) | Apr 17, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [b825c609a9](https://linux-hardware.org/?probe=b825c609a9) | Apr 15, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [337102cd4c](https://linux-hardware.org/?probe=337102cd4c) | Apr 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [7ac461b735](https://linux-hardware.org/?probe=7ac461b735) | Apr 15, 2023 |
| Gigabyte      | P55-UD3R                    | Desktop     | [5e8538987d](https://linux-hardware.org/?probe=5e8538987d) | Apr 14, 2023 |
| Acer          | AO756                       | Notebook    | [c17d5276ec](https://linux-hardware.org/?probe=c17d5276ec) | Apr 14, 2023 |
| ASUSTek       | K73TA                       | Notebook    | [34319e673a](https://linux-hardware.org/?probe=34319e673a) | Apr 13, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [f96d907026](https://linux-hardware.org/?probe=f96d907026) | Apr 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [af4ccb91b1](https://linux-hardware.org/?probe=af4ccb91b1) | Apr 12, 2023 |
| ASRock        | M3N78D FX                   | Desktop     | [618073d9e9](https://linux-hardware.org/?probe=618073d9e9) | Apr 12, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [6a6e2f88f4](https://linux-hardware.org/?probe=6a6e2f88f4) | Apr 12, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [2cec768fe1](https://linux-hardware.org/?probe=2cec768fe1) | Apr 11, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [feb08fab62](https://linux-hardware.org/?probe=feb08fab62) | Apr 09, 2023 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [54fabc7712](https://linux-hardware.org/?probe=54fabc7712) | Apr 09, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [f2040ffb31](https://linux-hardware.org/?probe=f2040ffb31) | Apr 09, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [120f5780bd](https://linux-hardware.org/?probe=120f5780bd) | Apr 09, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [52b4a5a0f0](https://linux-hardware.org/?probe=52b4a5a0f0) | Apr 08, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [1502ff1933](https://linux-hardware.org/?probe=1502ff1933) | Apr 08, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3e49e9c541](https://linux-hardware.org/?probe=3e49e9c541) | Apr 08, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [2d355e87d7](https://linux-hardware.org/?probe=2d355e87d7) | Apr 07, 2023 |
| Lenovo        | ThinkPad W530 243852U       | Notebook    | [ea2ee391a5](https://linux-hardware.org/?probe=ea2ee391a5) | Apr 07, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | Desktop     | [10c9b38ed6](https://linux-hardware.org/?probe=10c9b38ed6) | Apr 07, 2023 |
| HP            | ProBook 4530s               | Notebook    | [efd084d9d5](https://linux-hardware.org/?probe=efd084d9d5) | Apr 07, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [8c4f851451](https://linux-hardware.org/?probe=8c4f851451) | Apr 07, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [78e2e080ea](https://linux-hardware.org/?probe=78e2e080ea) | Apr 07, 2023 |
| ASUSTek       | M4N98TD EVO                 | Desktop     | [8a2a2cf1ce](https://linux-hardware.org/?probe=8a2a2cf1ce) | Apr 07, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [e2dd28ca36](https://linux-hardware.org/?probe=e2dd28ca36) | Apr 06, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [fea5792a8b](https://linux-hardware.org/?probe=fea5792a8b) | Apr 06, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [8756f8891c](https://linux-hardware.org/?probe=8756f8891c) | Apr 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9e99b4150b](https://linux-hardware.org/?probe=9e99b4150b) | Apr 06, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [6da0293a4b](https://linux-hardware.org/?probe=6da0293a4b) | Apr 05, 2023 |
| Acer          | Aspire 3680                 | Notebook    | [b5511d9060](https://linux-hardware.org/?probe=b5511d9060) | Apr 05, 2023 |
| HP            | 245 G6                      | Notebook    | [c6a1e2951c](https://linux-hardware.org/?probe=c6a1e2951c) | Apr 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [540d1f11a6](https://linux-hardware.org/?probe=540d1f11a6) | Apr 05, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [d8dc8a37b1](https://linux-hardware.org/?probe=d8dc8a37b1) | Apr 04, 2023 |
| Lenovo        | ThinkPad T410 2537WB7       | Notebook    | [d68ffd9d0f](https://linux-hardware.org/?probe=d68ffd9d0f) | Apr 04, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [8293b6000a](https://linux-hardware.org/?probe=8293b6000a) | Apr 04, 2023 |
| Lenovo        | ThinkPad X220 4290CTO       | Notebook    | [5dd9277838](https://linux-hardware.org/?probe=5dd9277838) | Apr 04, 2023 |
| ASRock        | 990FX Extreme3              | Desktop     | [013cd9b246](https://linux-hardware.org/?probe=013cd9b246) | Apr 03, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [de861c6d3f](https://linux-hardware.org/?probe=de861c6d3f) | Apr 03, 2023 |
| Acer          | Veriton X2632G V:1.0        | Desktop     | [f5eafafc96](https://linux-hardware.org/?probe=f5eafafc96) | Apr 02, 2023 |
| ASUSTek       | G752VM                      | Notebook    | [13d6602e92](https://linux-hardware.org/?probe=13d6602e92) | Apr 02, 2023 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [5f703bfc7d](https://linux-hardware.org/?probe=5f703bfc7d) | Apr 01, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [96fcc41161](https://linux-hardware.org/?probe=96fcc41161) | Apr 01, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [f54ccba86f](https://linux-hardware.org/?probe=f54ccba86f) | Apr 01, 2023 |
| HP            | 2AFA                        | Desktop     | [d177838277](https://linux-hardware.org/?probe=d177838277) | Mar 31, 2023 |
| Dell          | XPS M1330                   | Notebook    | [46b9a5cfde](https://linux-hardware.org/?probe=46b9a5cfde) | Mar 31, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c51f53a733](https://linux-hardware.org/?probe=c51f53a733) | Mar 31, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [fc9a42e387](https://linux-hardware.org/?probe=fc9a42e387) | Mar 31, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [36c0a38885](https://linux-hardware.org/?probe=36c0a38885) | Mar 31, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c91e4d9c5a](https://linux-hardware.org/?probe=c91e4d9c5a) | Mar 30, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [6b9737a62f](https://linux-hardware.org/?probe=6b9737a62f) | Mar 30, 2023 |
| Lenovo        | ThinkPad Edge E530 3259M... | Notebook    | [9aaa97a931](https://linux-hardware.org/?probe=9aaa97a931) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [a316144991](https://linux-hardware.org/?probe=a316144991) | Mar 29, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [0bc21ff162](https://linux-hardware.org/?probe=0bc21ff162) | Mar 28, 2023 |
| HP            | 3047h                       | Desktop     | [c4f4f0c51d](https://linux-hardware.org/?probe=c4f4f0c51d) | Mar 28, 2023 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [4f523c6409](https://linux-hardware.org/?probe=4f523c6409) | Mar 28, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [220c640743](https://linux-hardware.org/?probe=220c640743) | Mar 28, 2023 |
| ASUSTek       | PRIME B450M-A II            | All in one  | [fcd01e22d7](https://linux-hardware.org/?probe=fcd01e22d7) | Mar 28, 2023 |
| Dell          | Studio 1558                 | Notebook    | [955946c74d](https://linux-hardware.org/?probe=955946c74d) | Mar 28, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [0901eb1e27](https://linux-hardware.org/?probe=0901eb1e27) | Mar 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d6ddfac9d0](https://linux-hardware.org/?probe=d6ddfac9d0) | Mar 27, 2023 |
| HP            | 250 G1                      | Notebook    | [a19b3136b7](https://linux-hardware.org/?probe=a19b3136b7) | Mar 26, 2023 |
| HP            | 8158 A01                    | Mini pc     | [8d1c60fe86](https://linux-hardware.org/?probe=8d1c60fe86) | Mar 26, 2023 |
| Medion        | Akoya E6416                 | Notebook    | [bb2e759014](https://linux-hardware.org/?probe=bb2e759014) | Mar 26, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [6fc56d2339](https://linux-hardware.org/?probe=6fc56d2339) | Mar 25, 2023 |
| MSI           | A520M PRO                   | Desktop     | [c27ea21be5](https://linux-hardware.org/?probe=c27ea21be5) | Mar 25, 2023 |
| Acer          | Aspire ES1-411              | Notebook    | [1a4caa9a83](https://linux-hardware.org/?probe=1a4caa9a83) | Mar 24, 2023 |
| HP            | 86F3 00100                  | All in one  | [4cf13e2cd3](https://linux-hardware.org/?probe=4cf13e2cd3) | Mar 24, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [178936b7f4](https://linux-hardware.org/?probe=178936b7f4) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [5c811e496f](https://linux-hardware.org/?probe=5c811e496f) | Mar 24, 2023 |
| Lenovo        | SDK0E50519 WIN              | Desktop     | [2fb6bb5874](https://linux-hardware.org/?probe=2fb6bb5874) | Mar 24, 2023 |
| ASUSTek       | M4N98TD EVO                 | Desktop     | [9cb4b84924](https://linux-hardware.org/?probe=9cb4b84924) | Mar 24, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [93bc601af0](https://linux-hardware.org/?probe=93bc601af0) | Mar 23, 2023 |
| MSI           | MS-7255                     | Desktop     | [7322068101](https://linux-hardware.org/?probe=7322068101) | Mar 23, 2023 |
| Toshiba       | T20                         | Notebook    | [a0757b47d7](https://linux-hardware.org/?probe=a0757b47d7) | Mar 22, 2023 |
| Acer          | TravelMate 5744             | Notebook    | [3ad8bf7639](https://linux-hardware.org/?probe=3ad8bf7639) | Mar 22, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [60a7dc4c2e](https://linux-hardware.org/?probe=60a7dc4c2e) | Mar 20, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [db3e17d5f1](https://linux-hardware.org/?probe=db3e17d5f1) | Mar 20, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9ee81ffe32](https://linux-hardware.org/?probe=9ee81ffe32) | Mar 20, 2023 |
| ASRock        | 970A-G                      | Desktop     | [52b0aa69ba](https://linux-hardware.org/?probe=52b0aa69ba) | Mar 20, 2023 |
| HP            | 18E7                        | Desktop     | [9e4b5010d8](https://linux-hardware.org/?probe=9e4b5010d8) | Mar 20, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [a3cee7c278](https://linux-hardware.org/?probe=a3cee7c278) | Mar 19, 2023 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [0daa99f732](https://linux-hardware.org/?probe=0daa99f732) | Mar 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [77b7fd07a4](https://linux-hardware.org/?probe=77b7fd07a4) | Mar 19, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [b637fa75c8](https://linux-hardware.org/?probe=b637fa75c8) | Mar 18, 2023 |
| Lenovo        | ThinkPad P50 20EQS1MY00     | Notebook    | [beeb327f26](https://linux-hardware.org/?probe=beeb327f26) | Mar 18, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [e90a87f6f2](https://linux-hardware.org/?probe=e90a87f6f2) | Mar 18, 2023 |
| MSI           | GP60 2OD                    | Notebook    | [a3ffd8113f](https://linux-hardware.org/?probe=a3ffd8113f) | Mar 18, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [19fd2af680](https://linux-hardware.org/?probe=19fd2af680) | Mar 18, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2a1291ac22](https://linux-hardware.org/?probe=2a1291ac22) | Mar 18, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [39d6b256fa](https://linux-hardware.org/?probe=39d6b256fa) | Mar 18, 2023 |
| MSI           | H55M-P31                    | Desktop     | [e95e62df99](https://linux-hardware.org/?probe=e95e62df99) | Mar 18, 2023 |
| Notebook      | N8xxEP6                     | Notebook    | [a4bd2c22eb](https://linux-hardware.org/?probe=a4bd2c22eb) | Mar 18, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9c24401930](https://linux-hardware.org/?probe=9c24401930) | Mar 18, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [2d7a146140](https://linux-hardware.org/?probe=2d7a146140) | Mar 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [fce879befb](https://linux-hardware.org/?probe=fce879befb) | Mar 18, 2023 |
| Medion        | H81H3-EM2 H81EM2W08.217     | Desktop     | [1e1a430355](https://linux-hardware.org/?probe=1e1a430355) | Mar 17, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [c640b09a8b](https://linux-hardware.org/?probe=c640b09a8b) | Mar 17, 2023 |
| Dell          | Latitude E7440              | Notebook    | [8a6e751b61](https://linux-hardware.org/?probe=8a6e751b61) | Mar 16, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [7ab2e7b0ab](https://linux-hardware.org/?probe=7ab2e7b0ab) | Mar 16, 2023 |
| ASUSTek       | CG5290                      | Desktop     | [e0ab58dbfe](https://linux-hardware.org/?probe=e0ab58dbfe) | Mar 16, 2023 |
| ASUSTek       | VC62B                       | Desktop     | [9bf2d226a8](https://linux-hardware.org/?probe=9bf2d226a8) | Mar 15, 2023 |
| MSI           | H61M-P20                    | Desktop     | [8129a4f5a4](https://linux-hardware.org/?probe=8129a4f5a4) | Mar 15, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7fbe857344](https://linux-hardware.org/?probe=7fbe857344) | Mar 14, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [8ff2a816b5](https://linux-hardware.org/?probe=8ff2a816b5) | Mar 13, 2023 |
| ASRock        | G31M-S                      | Desktop     | [7672cc15a2](https://linux-hardware.org/?probe=7672cc15a2) | Mar 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [9509c77e2b](https://linux-hardware.org/?probe=9509c77e2b) | Mar 13, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [7f3525f6ef](https://linux-hardware.org/?probe=7f3525f6ef) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [4265744c52](https://linux-hardware.org/?probe=4265744c52) | Mar 12, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [4247bd6835](https://linux-hardware.org/?probe=4247bd6835) | Mar 12, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [a45ebd1b85](https://linux-hardware.org/?probe=a45ebd1b85) | Mar 12, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [757a62eff0](https://linux-hardware.org/?probe=757a62eff0) | Mar 11, 2023 |
| Pegatron      | 2AC2                        | Desktop     | [a6084e8904](https://linux-hardware.org/?probe=a6084e8904) | Mar 11, 2023 |
| Toshiba       | All In One PC MP            | All in one  | [2a3a0b15f8](https://linux-hardware.org/?probe=2a3a0b15f8) | Mar 11, 2023 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [d2b402f3c0](https://linux-hardware.org/?probe=d2b402f3c0) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [1d2e721898](https://linux-hardware.org/?probe=1d2e721898) | Mar 10, 2023 |
| HP            | 0AA0h                       | Desktop     | [f86f0bc187](https://linux-hardware.org/?probe=f86f0bc187) | Mar 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [bf4c797c87](https://linux-hardware.org/?probe=bf4c797c87) | Mar 10, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [b8dffd9bd3](https://linux-hardware.org/?probe=b8dffd9bd3) | Mar 10, 2023 |
| Dell          | Vostro 1310                 | Notebook    | [a5677d37dc](https://linux-hardware.org/?probe=a5677d37dc) | Mar 09, 2023 |
| ASRock        | H61M-ITX                    | Desktop     | [ab7e81c6ca](https://linux-hardware.org/?probe=ab7e81c6ca) | Mar 09, 2023 |
| HP            | ENVY 6                      | Notebook    | [4873f7b85f](https://linux-hardware.org/?probe=4873f7b85f) | Mar 08, 2023 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | Desktop     | [b1a69ac03b](https://linux-hardware.org/?probe=b1a69ac03b) | Mar 08, 2023 |
| ECS           | MCP61PM-GM                  | Desktop     | [ac561937e3](https://linux-hardware.org/?probe=ac561937e3) | Mar 08, 2023 |
| AZW           | GT-R                        | Notebook    | [cce9cccb8f](https://linux-hardware.org/?probe=cce9cccb8f) | Mar 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c6f9f5a58d](https://linux-hardware.org/?probe=c6f9f5a58d) | Mar 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0cd8da5364](https://linux-hardware.org/?probe=0cd8da5364) | Mar 06, 2023 |
| Gigabyte      | P35-DS3L                    | Desktop     | [31aeecfcb9](https://linux-hardware.org/?probe=31aeecfcb9) | Mar 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9b72e94139](https://linux-hardware.org/?probe=9b72e94139) | Mar 06, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [c420621505](https://linux-hardware.org/?probe=c420621505) | Mar 05, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [d000dc6718](https://linux-hardware.org/?probe=d000dc6718) | Mar 04, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [9c91f76369](https://linux-hardware.org/?probe=9c91f76369) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [9b0664e4d7](https://linux-hardware.org/?probe=9b0664e4d7) | Mar 04, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [ba97297cf9](https://linux-hardware.org/?probe=ba97297cf9) | Mar 04, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [914a9990c4](https://linux-hardware.org/?probe=914a9990c4) | Mar 04, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [82ecc9ac72](https://linux-hardware.org/?probe=82ecc9ac72) | Mar 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [84e37e870d](https://linux-hardware.org/?probe=84e37e870d) | Mar 03, 2023 |
| Toshiba       | dynabook R73/BN             | Notebook    | [1d81bb5f08](https://linux-hardware.org/?probe=1d81bb5f08) | Mar 03, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [e828686fc3](https://linux-hardware.org/?probe=e828686fc3) | Mar 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [1da5b61697](https://linux-hardware.org/?probe=1da5b61697) | Mar 02, 2023 |
| Acer          | Aspire E1-532P              | Notebook    | [8a23f06db4](https://linux-hardware.org/?probe=8a23f06db4) | Mar 01, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [aa7d308d7e](https://linux-hardware.org/?probe=aa7d308d7e) | Mar 01, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [6f1de5f17c](https://linux-hardware.org/?probe=6f1de5f17c) | Feb 28, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [5a0c297e10](https://linux-hardware.org/?probe=5a0c297e10) | Feb 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a6af4042ea](https://linux-hardware.org/?probe=a6af4042ea) | Feb 28, 2023 |
| Foxconn       | G31MX Series                | Desktop     | [79ee8e5da3](https://linux-hardware.org/?probe=79ee8e5da3) | Feb 28, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a84f4dbcbb](https://linux-hardware.org/?probe=a84f4dbcbb) | Feb 28, 2023 |
| ASUSTek       | K75VJ                       | Notebook    | [7fc0fff829](https://linux-hardware.org/?probe=7fc0fff829) | Feb 27, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0335729036](https://linux-hardware.org/?probe=0335729036) | Feb 27, 2023 |
| Intel         | H61                         | Desktop     | [b61ef1ed65](https://linux-hardware.org/?probe=b61ef1ed65) | Feb 27, 2023 |
| MSI           | NF750-G55                   | Desktop     | [f279251ffa](https://linux-hardware.org/?probe=f279251ffa) | Feb 27, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [5f035002e1](https://linux-hardware.org/?probe=5f035002e1) | Feb 27, 2023 |
| Acer          | EG43M                       | Desktop     | [d533c457eb](https://linux-hardware.org/?probe=d533c457eb) | Feb 26, 2023 |
| ASUSTek       | PRIME Q270M-C               | Desktop     | [edf748dbbb](https://linux-hardware.org/?probe=edf748dbbb) | Feb 26, 2023 |
| eMachines     | eME728                      | Notebook    | [2331984fc8](https://linux-hardware.org/?probe=2331984fc8) | Feb 26, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [d9f49e98fd](https://linux-hardware.org/?probe=d9f49e98fd) | Feb 25, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [99d4efbb52](https://linux-hardware.org/?probe=99d4efbb52) | Feb 25, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [ab8247e106](https://linux-hardware.org/?probe=ab8247e106) | Feb 24, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [fad0bd20e1](https://linux-hardware.org/?probe=fad0bd20e1) | Feb 24, 2023 |
| HP            | 650                         | Notebook    | [ab0b350259](https://linux-hardware.org/?probe=ab0b350259) | Feb 24, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [91c8d45121](https://linux-hardware.org/?probe=91c8d45121) | Feb 24, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [9171567db4](https://linux-hardware.org/?probe=9171567db4) | Feb 24, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [b410c9f493](https://linux-hardware.org/?probe=b410c9f493) | Feb 24, 2023 |
| HP            | 1998                        | Desktop     | [145c009f05](https://linux-hardware.org/?probe=145c009f05) | Feb 24, 2023 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [21aa20cd64](https://linux-hardware.org/?probe=21aa20cd64) | Feb 24, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [12040fcd10](https://linux-hardware.org/?probe=12040fcd10) | Feb 24, 2023 |
| Toshiba       | Satellite C850-1GF          | Notebook    | [f568855409](https://linux-hardware.org/?probe=f568855409) | Feb 24, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [016a51a4af](https://linux-hardware.org/?probe=016a51a4af) | Feb 23, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [de05d0d3f6](https://linux-hardware.org/?probe=de05d0d3f6) | Feb 23, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [cfe5ecec44](https://linux-hardware.org/?probe=cfe5ecec44) | Feb 23, 2023 |
| Biostar       | N68S3B                      | Desktop     | [4572b3d965](https://linux-hardware.org/?probe=4572b3d965) | Feb 23, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [75b2eb9c1f](https://linux-hardware.org/?probe=75b2eb9c1f) | Feb 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [d488fc0d9a](https://linux-hardware.org/?probe=d488fc0d9a) | Feb 22, 2023 |
| Positivo      | S14SL01                     | Notebook    | [914a9e691e](https://linux-hardware.org/?probe=914a9e691e) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 23551M9      | Notebook    | [91b6a109b4](https://linux-hardware.org/?probe=91b6a109b4) | Feb 22, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [ad365efca1](https://linux-hardware.org/?probe=ad365efca1) | Feb 22, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [4803e8ee01](https://linux-hardware.org/?probe=4803e8ee01) | Feb 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [2d36b57c9c](https://linux-hardware.org/?probe=2d36b57c9c) | Feb 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [9523a0ccc2](https://linux-hardware.org/?probe=9523a0ccc2) | Feb 22, 2023 |
| Gateway       | NV53A                       | Notebook    | [1e2b4ec4d3](https://linux-hardware.org/?probe=1e2b4ec4d3) | Feb 22, 2023 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [28890c5346](https://linux-hardware.org/?probe=28890c5346) | Feb 21, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [b4288b76ee](https://linux-hardware.org/?probe=b4288b76ee) | Feb 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [526430f218](https://linux-hardware.org/?probe=526430f218) | Feb 21, 2023 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [b644019f77](https://linux-hardware.org/?probe=b644019f77) | Feb 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [80df77e6a1](https://linux-hardware.org/?probe=80df77e6a1) | Feb 21, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [bbef057c8f](https://linux-hardware.org/?probe=bbef057c8f) | Feb 21, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [d81ff5358a](https://linux-hardware.org/?probe=d81ff5358a) | Feb 20, 2023 |
| MSI           | G41M-P23                    | Desktop     | [04211b9202](https://linux-hardware.org/?probe=04211b9202) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [119e106d80](https://linux-hardware.org/?probe=119e106d80) | Feb 20, 2023 |
| ASRock        | 880GM-LE FX                 | Desktop     | [db290cd703](https://linux-hardware.org/?probe=db290cd703) | Feb 19, 2023 |
| Lenovo        | B560 43308VG                | Notebook    | [c30b594458](https://linux-hardware.org/?probe=c30b594458) | Feb 19, 2023 |
| HP            | ProBook 4520s               | Notebook    | [8192287499](https://linux-hardware.org/?probe=8192287499) | Feb 19, 2023 |
| MSI           | Z97M GAMING                 | Desktop     | [e983a3704e](https://linux-hardware.org/?probe=e983a3704e) | Feb 19, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [b0941b8ef0](https://linux-hardware.org/?probe=b0941b8ef0) | Feb 18, 2023 |
| HP            | 15                          | Notebook    | [4db2520843](https://linux-hardware.org/?probe=4db2520843) | Feb 18, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [ff9cd473da](https://linux-hardware.org/?probe=ff9cd473da) | Feb 18, 2023 |
| HP            | ProBook 4540s               | Notebook    | [cc3e78f73f](https://linux-hardware.org/?probe=cc3e78f73f) | Feb 18, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [8dd1992835](https://linux-hardware.org/?probe=8dd1992835) | Feb 18, 2023 |
| ASRock        | 880GM-LE FX                 | Desktop     | [1d45a444a3](https://linux-hardware.org/?probe=1d45a444a3) | Feb 18, 2023 |
| PC Special... | NJ50_70CU                   | Notebook    | [68dd853397](https://linux-hardware.org/?probe=68dd853397) | Feb 17, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [3ed988e135](https://linux-hardware.org/?probe=3ed988e135) | Feb 17, 2023 |
| Gigabyte      | H87M-HD3                    | Desktop     | [778b7898e3](https://linux-hardware.org/?probe=778b7898e3) | Feb 17, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [a524479b7a](https://linux-hardware.org/?probe=a524479b7a) | Feb 17, 2023 |
| Toshiba       | Satellite C70-C-18E         | Notebook    | [7642482909](https://linux-hardware.org/?probe=7642482909) | Feb 17, 2023 |
| EVGA          | 151-IB-E699                 | Desktop     | [9e975c7966](https://linux-hardware.org/?probe=9e975c7966) | Feb 17, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a48098f6fc](https://linux-hardware.org/?probe=a48098f6fc) | Feb 17, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ac458108b4](https://linux-hardware.org/?probe=ac458108b4) | Feb 17, 2023 |
| Pegatron      | IPM31G                      | Desktop     | [42d112d7e0](https://linux-hardware.org/?probe=42d112d7e0) | Feb 17, 2023 |
| ASUSTek       | K54C                        | Notebook    | [ea944628df](https://linux-hardware.org/?probe=ea944628df) | Feb 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [66c33604c4](https://linux-hardware.org/?probe=66c33604c4) | Feb 17, 2023 |
| Samsung       | R519/R719                   | Notebook    | [1dc4bc1b72](https://linux-hardware.org/?probe=1dc4bc1b72) | Feb 17, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [ffd622d65f](https://linux-hardware.org/?probe=ffd622d65f) | Feb 17, 2023 |
| HP            | 2820h                       | Desktop     | [552bdc9930](https://linux-hardware.org/?probe=552bdc9930) | Feb 17, 2023 |
| eMachines     | eMachiens G443              | Notebook    | [096a4bb9e4](https://linux-hardware.org/?probe=096a4bb9e4) | Feb 16, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [95a9115968](https://linux-hardware.org/?probe=95a9115968) | Feb 16, 2023 |
| MSI           | H61M-E33                    | Desktop     | [f0c902ce04](https://linux-hardware.org/?probe=f0c902ce04) | Feb 16, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [c6a7d3a755](https://linux-hardware.org/?probe=c6a7d3a755) | Feb 16, 2023 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [b043125d6e](https://linux-hardware.org/?probe=b043125d6e) | Feb 16, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [3ce39f40e7](https://linux-hardware.org/?probe=3ce39f40e7) | Feb 16, 2023 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [63789621e0](https://linux-hardware.org/?probe=63789621e0) | Feb 16, 2023 |
| Lenovo        | ThinkCentre M91 4518E4S     | Desktop     | [91b1fb7e03](https://linux-hardware.org/?probe=91b1fb7e03) | Feb 16, 2023 |
| Philco        | DTC-A55                     | Desktop     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [9f9cc6f9e2](https://linux-hardware.org/?probe=9f9cc6f9e2) | Feb 16, 2023 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [8e521a2efc](https://linux-hardware.org/?probe=8e521a2efc) | Feb 16, 2023 |
| ASUSTek       | H81T                        | Desktop     | [51aa090e9a](https://linux-hardware.org/?probe=51aa090e9a) | Feb 16, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [ed9bd6b127](https://linux-hardware.org/?probe=ed9bd6b127) | Feb 16, 2023 |
| Dell          | Latitude E7440              | Notebook    | [86f8d34ba7](https://linux-hardware.org/?probe=86f8d34ba7) | Feb 16, 2023 |
| HP            | 3031h                       | Desktop     | [2b0cc2bd6e](https://linux-hardware.org/?probe=2b0cc2bd6e) | Feb 16, 2023 |
| Toshiba       | dynabook R73/BN             | Notebook    | [df7e69c5c4](https://linux-hardware.org/?probe=df7e69c5c4) | Feb 16, 2023 |
| HP            | ProBook 470 G4              | Notebook    | [8730091665](https://linux-hardware.org/?probe=8730091665) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [21442c303e](https://linux-hardware.org/?probe=21442c303e) | Feb 15, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [745ae4d0fb](https://linux-hardware.org/?probe=745ae4d0fb) | Feb 15, 2023 |
| MSI           | MS-7235                     | Desktop     | [519f3742a3](https://linux-hardware.org/?probe=519f3742a3) | Feb 15, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [5455b577db](https://linux-hardware.org/?probe=5455b577db) | Feb 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [bc69f33fa2](https://linux-hardware.org/?probe=bc69f33fa2) | Feb 15, 2023 |
| ASUSTek       | K52N                        | Notebook    | [f87ece85e9](https://linux-hardware.org/?probe=f87ece85e9) | Feb 15, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [528ffce1c7](https://linux-hardware.org/?probe=528ffce1c7) | Feb 15, 2023 |
| HP            | 1000                        | Notebook    | [57de0f3103](https://linux-hardware.org/?probe=57de0f3103) | Feb 15, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [20b88dda19](https://linux-hardware.org/?probe=20b88dda19) | Feb 15, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [3ab6d305fc](https://linux-hardware.org/?probe=3ab6d305fc) | Feb 15, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [f0d6ada218](https://linux-hardware.org/?probe=f0d6ada218) | Feb 15, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [b30e6a84c8](https://linux-hardware.org/?probe=b30e6a84c8) | Feb 14, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [7ec9e518c4](https://linux-hardware.org/?probe=7ec9e518c4) | Feb 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [dddbb2d135](https://linux-hardware.org/?probe=dddbb2d135) | Feb 14, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [f9318d4390](https://linux-hardware.org/?probe=f9318d4390) | Feb 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [bf015f98c2](https://linux-hardware.org/?probe=bf015f98c2) | Feb 14, 2023 |
| ASRock        | E350M1                      | Desktop     | [ac69adceb6](https://linux-hardware.org/?probe=ac69adceb6) | Feb 13, 2023 |
| ASUSTek       | P7P55D-E EVO                | Desktop     | [f1ec250753](https://linux-hardware.org/?probe=f1ec250753) | Feb 13, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [cdc2dedbcd](https://linux-hardware.org/?probe=cdc2dedbcd) | Feb 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7623da10b8](https://linux-hardware.org/?probe=7623da10b8) | Feb 13, 2023 |
| HP            | 3031h                       | Desktop     | [f9a0848388](https://linux-hardware.org/?probe=f9a0848388) | Feb 11, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [4f99163f99](https://linux-hardware.org/?probe=4f99163f99) | Feb 11, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f0f4d31de2](https://linux-hardware.org/?probe=f0f4d31de2) | Feb 10, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e8fdc1676a](https://linux-hardware.org/?probe=e8fdc1676a) | Feb 10, 2023 |
| Medion        | TJ4105                      | Desktop     | [cd654518c0](https://linux-hardware.org/?probe=cd654518c0) | Feb 09, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [8532f05156](https://linux-hardware.org/?probe=8532f05156) | Feb 09, 2023 |
| HP            | Compaq Presario CQ61        | Notebook    | [df4d59acd5](https://linux-hardware.org/?probe=df4d59acd5) | Feb 07, 2023 |
| HP            | 1905                        | Desktop     | [a442e1de06](https://linux-hardware.org/?probe=a442e1de06) | Feb 07, 2023 |
| Lenovo        | ThinkPad X240 20AL00FMGE    | Notebook    | [0ac2678512](https://linux-hardware.org/?probe=0ac2678512) | Feb 06, 2023 |
| Acer          | Extensa 5635                | Notebook    | [8f8f4d24f9](https://linux-hardware.org/?probe=8f8f4d24f9) | Feb 06, 2023 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [a527005a2a](https://linux-hardware.org/?probe=a527005a2a) | Feb 06, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [7ca566f68b](https://linux-hardware.org/?probe=7ca566f68b) | Feb 05, 2023 |
| Dell          | 084J0R A00                  | Desktop     | [7fe633b52f](https://linux-hardware.org/?probe=7fe633b52f) | Feb 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d6adca1255](https://linux-hardware.org/?probe=d6adca1255) | Feb 04, 2023 |
| HP            | ProBook 6465b               | Notebook    | [00b2021fae](https://linux-hardware.org/?probe=00b2021fae) | Feb 04, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [87fe173b18](https://linux-hardware.org/?probe=87fe173b18) | Feb 02, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [6a440e41d7](https://linux-hardware.org/?probe=6a440e41d7) | Feb 02, 2023 |
| Dell          | Latitude E5420              | Notebook    | [ccc3ca9853](https://linux-hardware.org/?probe=ccc3ca9853) | Jan 31, 2023 |
| HP            | 3115-AEC13432GR1            | Notebook    | [98eb70341a](https://linux-hardware.org/?probe=98eb70341a) | Jan 30, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [e2fa9aa820](https://linux-hardware.org/?probe=e2fa9aa820) | Jan 29, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [e3f865cd20](https://linux-hardware.org/?probe=e3f865cd20) | Jan 28, 2023 |
| HP            | Notebook                    | Notebook    | [d38e078368](https://linux-hardware.org/?probe=d38e078368) | Jan 28, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [e00443a9cc](https://linux-hardware.org/?probe=e00443a9cc) | Jan 27, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [d87ac57c19](https://linux-hardware.org/?probe=d87ac57c19) | Jan 27, 2023 |
| HP            | 14                          | Notebook    | [53d080d83a](https://linux-hardware.org/?probe=53d080d83a) | Jan 27, 2023 |
| Dell          | Inspiron 15 3521            | Notebook    | [41f89081ff](https://linux-hardware.org/?probe=41f89081ff) | Jan 26, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [873ee647b0](https://linux-hardware.org/?probe=873ee647b0) | Jan 26, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [328dae4014](https://linux-hardware.org/?probe=328dae4014) | Jan 26, 2023 |
| HP            | 3048h                       | Desktop     | [caabf4189f](https://linux-hardware.org/?probe=caabf4189f) | Jan 25, 2023 |
| OEGStone      | C4100/C5100                 | Notebook    | [4365b7b231](https://linux-hardware.org/?probe=4365b7b231) | Jan 25, 2023 |
| AZW           | U59                         | Desktop     | [6d2b672b77](https://linux-hardware.org/?probe=6d2b672b77) | Jan 25, 2023 |
| ASRock        | 775XFire-VSTA               | Desktop     | [e80788f790](https://linux-hardware.org/?probe=e80788f790) | Jan 24, 2023 |
| Lenovo        | ThinkPad W541 20EF0020MD    | Notebook    | [fca73ad2a9](https://linux-hardware.org/?probe=fca73ad2a9) | Jan 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [95898eae6d](https://linux-hardware.org/?probe=95898eae6d) | Jan 23, 2023 |
| Packard Be... | PB56                        | Notebook    | [f26fcb7ee5](https://linux-hardware.org/?probe=f26fcb7ee5) | Jan 23, 2023 |
| Dell          | 0X2MKR A00                  | All in one  | [5b29ed7213](https://linux-hardware.org/?probe=5b29ed7213) | Jan 23, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [dcecec2239](https://linux-hardware.org/?probe=dcecec2239) | Jan 22, 2023 |
| Gigabyte      | N3050ND3H                   | Desktop     | [1663928526](https://linux-hardware.org/?probe=1663928526) | Jan 21, 2023 |
| HP            | Pavilion dv5                | Notebook    | [94ba65752b](https://linux-hardware.org/?probe=94ba65752b) | Jan 20, 2023 |
| GEEKOM        | MiniAir 11                  | Server      | [0d27879bb6](https://linux-hardware.org/?probe=0d27879bb6) | Jan 19, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [10081492a7](https://linux-hardware.org/?probe=10081492a7) | Jan 19, 2023 |
| Acer          | Iconia Tab W501             | Tablet      | [c3d132fb91](https://linux-hardware.org/?probe=c3d132fb91) | Jan 18, 2023 |
| ASUSTek       | C60M1-I                     | Desktop     | [defd3912ae](https://linux-hardware.org/?probe=defd3912ae) | Jan 18, 2023 |
| Panasonic     | CF-53JULCV1M                | Notebook    | [89c1166efc](https://linux-hardware.org/?probe=89c1166efc) | Jan 18, 2023 |
| Unknown       | HX90                        | Desktop     | [2b034e44e2](https://linux-hardware.org/?probe=2b034e44e2) | Jan 18, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [bf606ed50a](https://linux-hardware.org/?probe=bf606ed50a) | Jan 18, 2023 |
| HP            | ProBook 440 G1              | Notebook    | [035c7a4e2d](https://linux-hardware.org/?probe=035c7a4e2d) | Jan 18, 2023 |
| Medion        | MS-7621                     | Desktop     | [67b535d88f](https://linux-hardware.org/?probe=67b535d88f) | Jan 18, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b611fc6b64](https://linux-hardware.org/?probe=b611fc6b64) | Jan 18, 2023 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [74a62575d2](https://linux-hardware.org/?probe=74a62575d2) | Jan 17, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [276102bb1a](https://linux-hardware.org/?probe=276102bb1a) | Jan 16, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [33985f088a](https://linux-hardware.org/?probe=33985f088a) | Jan 16, 2023 |
| Acer          | Iconia Tab W501             | Tablet      | [9941154ca3](https://linux-hardware.org/?probe=9941154ca3) | Jan 15, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [c20a339ddb](https://linux-hardware.org/?probe=c20a339ddb) | Jan 15, 2023 |
| Lenovo        | SDK0F82993 WIN              | Desktop     | [48f294dfb4](https://linux-hardware.org/?probe=48f294dfb4) | Jan 15, 2023 |
| Acer          | Aspire 7551                 | Notebook    | [b3e5df94f4](https://linux-hardware.org/?probe=b3e5df94f4) | Jan 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [291dceb273](https://linux-hardware.org/?probe=291dceb273) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [b70eca9c43](https://linux-hardware.org/?probe=b70eca9c43) | Jan 14, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9c4aac8b46](https://linux-hardware.org/?probe=9c4aac8b46) | Jan 14, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [79d2961429](https://linux-hardware.org/?probe=79d2961429) | Jan 14, 2023 |
| HP            | 8054                        | Desktop     | [faf1c97cea](https://linux-hardware.org/?probe=faf1c97cea) | Jan 14, 2023 |
| Supermicro    | A1SA2-2750F                 | Server      | [e134d7a317](https://linux-hardware.org/?probe=e134d7a317) | Jan 14, 2023 |
| HP            | 18E5                        | Desktop     | [614faa708b](https://linux-hardware.org/?probe=614faa708b) | Jan 14, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [23a918874b](https://linux-hardware.org/?probe=23a918874b) | Jan 14, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [d60bab803e](https://linux-hardware.org/?probe=d60bab803e) | Jan 13, 2023 |
| HP            | 84EE 1100                   | All in one  | [708c21d16b](https://linux-hardware.org/?probe=708c21d16b) | Jan 13, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [12f29d53ba](https://linux-hardware.org/?probe=12f29d53ba) | Jan 13, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [72e7e2e1cf](https://linux-hardware.org/?probe=72e7e2e1cf) | Jan 11, 2023 |
| Toshiba       | Satellite C850-B561         | Notebook    | [562d6cde14](https://linux-hardware.org/?probe=562d6cde14) | Jan 11, 2023 |
| Lenovo        | ThinkPad X240 20AM001RGE    | Notebook    | [f4aafcf7a9](https://linux-hardware.org/?probe=f4aafcf7a9) | Jan 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [805d82d697](https://linux-hardware.org/?probe=805d82d697) | Jan 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [ce911686b3](https://linux-hardware.org/?probe=ce911686b3) | Jan 10, 2023 |
| Dell          | XPS M1330                   | Notebook    | [e3d66114f6](https://linux-hardware.org/?probe=e3d66114f6) | Jan 10, 2023 |
| Acer          | Iconia Tab W501             | Tablet      | [ec34a44908](https://linux-hardware.org/?probe=ec34a44908) | Jan 10, 2023 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [8064745798](https://linux-hardware.org/?probe=8064745798) | Jan 10, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [f540a5f964](https://linux-hardware.org/?probe=f540a5f964) | Jan 09, 2023 |
| Star Labs     | Lite                        | Notebook    | [6614e226df](https://linux-hardware.org/?probe=6614e226df) | Jan 09, 2023 |
| HP            | 0AA4h                       | Desktop     | [e0776de36f](https://linux-hardware.org/?probe=e0776de36f) | Jan 09, 2023 |
| HP            | 802F                        | Desktop     | [1dd3655605](https://linux-hardware.org/?probe=1dd3655605) | Jan 09, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [e2f62062de](https://linux-hardware.org/?probe=e2f62062de) | Jan 09, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [a2bce032b4](https://linux-hardware.org/?probe=a2bce032b4) | Jan 09, 2023 |
| Dell          | 0654JC A01                  | Desktop     | [c3016e1823](https://linux-hardware.org/?probe=c3016e1823) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [84aa790d17](https://linux-hardware.org/?probe=84aa790d17) | Jan 09, 2023 |
| HP            | 8265                        | Desktop     | [83897e98cf](https://linux-hardware.org/?probe=83897e98cf) | Jan 08, 2023 |
| MSI           | 990XA-GD55                  | Desktop     | [b4525a8431](https://linux-hardware.org/?probe=b4525a8431) | Jan 08, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [d94d0c7025](https://linux-hardware.org/?probe=d94d0c7025) | Jan 08, 2023 |
| Dell          | Latitude E6400              | Notebook    | [70bce3a55c](https://linux-hardware.org/?probe=70bce3a55c) | Jan 08, 2023 |
| HP            | 1489                        | All in one  | [2660a9d31d](https://linux-hardware.org/?probe=2660a9d31d) | Jan 08, 2023 |
| Dell          | Latitude E5440              | Notebook    | [91bedeb5e1](https://linux-hardware.org/?probe=91bedeb5e1) | Jan 07, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [c1c8654cde](https://linux-hardware.org/?probe=c1c8654cde) | Jan 07, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [782467ee8c](https://linux-hardware.org/?probe=782467ee8c) | Jan 07, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [d0e4567b4a](https://linux-hardware.org/?probe=d0e4567b4a) | Jan 07, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [3bc9e3b318](https://linux-hardware.org/?probe=3bc9e3b318) | Jan 07, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [3392dd3c90](https://linux-hardware.org/?probe=3392dd3c90) | Jan 07, 2023 |
| Alienware     | 04VWF2 A02                  | Desktop     | [15f4ed4e31](https://linux-hardware.org/?probe=15f4ed4e31) | Jan 07, 2023 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | Tablet      | [e6190d3469](https://linux-hardware.org/?probe=e6190d3469) | Jan 07, 2023 |
| HP            | 250 G3                      | Notebook    | [227b44bf7c](https://linux-hardware.org/?probe=227b44bf7c) | Jan 06, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0232b39536](https://linux-hardware.org/?probe=0232b39536) | Jan 06, 2023 |
| eMachines     | E725                        | Notebook    | [0655d63f70](https://linux-hardware.org/?probe=0655d63f70) | Jan 06, 2023 |
| Acer          | Spin SP513-51               | Convertible | [1fe9e7fa54](https://linux-hardware.org/?probe=1fe9e7fa54) | Jan 06, 2023 |
| Acer          | Veriton M2631G V:1.0        | Desktop     | [ddeffc27a7](https://linux-hardware.org/?probe=ddeffc27a7) | Jan 05, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [4ce129e600](https://linux-hardware.org/?probe=4ce129e600) | Jan 05, 2023 |
| ASUSTek       | K55VM                       | Notebook    | [d4d53ed49f](https://linux-hardware.org/?probe=d4d53ed49f) | Jan 04, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6cae064dc5](https://linux-hardware.org/?probe=6cae064dc5) | Jan 04, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [c64a1198cd](https://linux-hardware.org/?probe=c64a1198cd) | Jan 04, 2023 |
| HP            | ProBook 470 G2              | Notebook    | [1f62ff6417](https://linux-hardware.org/?probe=1f62ff6417) | Jan 04, 2023 |
| HP            | Compaq 15                   | Notebook    | [c282ede7c5](https://linux-hardware.org/?probe=c282ede7c5) | Jan 04, 2023 |
| HP            | EliteBook 725 G3            | Notebook    | [174e0c5f05](https://linux-hardware.org/?probe=174e0c5f05) | Jan 04, 2023 |
| Dell          | Latitude D520               | Notebook    | [7f05ddf105](https://linux-hardware.org/?probe=7f05ddf105) | Jan 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [7e445638b6](https://linux-hardware.org/?probe=7e445638b6) | Jan 04, 2023 |
| MSI           | A88X-G45 GAMING             | Desktop     | [1caf5c85d9](https://linux-hardware.org/?probe=1caf5c85d9) | Jan 04, 2023 |
| Sony          | VJF153                      | Notebook    | [f3643923cc](https://linux-hardware.org/?probe=f3643923cc) | Jan 04, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [c5bc3a8eae](https://linux-hardware.org/?probe=c5bc3a8eae) | Jan 03, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [c0e5361a69](https://linux-hardware.org/?probe=c0e5361a69) | Jan 03, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [55627fc077](https://linux-hardware.org/?probe=55627fc077) | Jan 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5f0eeeb9e7](https://linux-hardware.org/?probe=5f0eeeb9e7) | Jan 03, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [faccba61cf](https://linux-hardware.org/?probe=faccba61cf) | Jan 03, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | Desktop     | [afe5105302](https://linux-hardware.org/?probe=afe5105302) | Jan 03, 2023 |
| ASUSTek       | Berkeley                    | Desktop     | [746d7be693](https://linux-hardware.org/?probe=746d7be693) | Jan 03, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [a73ca839a1](https://linux-hardware.org/?probe=a73ca839a1) | Jan 03, 2023 |
| Dell          | 0MM599                      | Desktop     | [95763443e3](https://linux-hardware.org/?probe=95763443e3) | Jan 03, 2023 |
| Intel         | NUC5PPYB H76558-108         | Mini pc     | [e93bf27a59](https://linux-hardware.org/?probe=e93bf27a59) | Jan 02, 2023 |
| Positivo      | Z100                        | Notebook    | [58b7c4d1ff](https://linux-hardware.org/?probe=58b7c4d1ff) | Jan 02, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [df9ca70fa3](https://linux-hardware.org/?probe=df9ca70fa3) | Jan 02, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [85ad98c994](https://linux-hardware.org/?probe=85ad98c994) | Jan 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [287840d797](https://linux-hardware.org/?probe=287840d797) | Jan 02, 2023 |
| AZW           | MINI S                      | Desktop     | [ad7c4329eb](https://linux-hardware.org/?probe=ad7c4329eb) | Jan 02, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [86b79bce9e](https://linux-hardware.org/?probe=86b79bce9e) | Jan 01, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [509cc939cc](https://linux-hardware.org/?probe=509cc939cc) | Jan 01, 2023 |
| OEM           | Intel H81                   | Desktop     | [1700a7a4c7](https://linux-hardware.org/?probe=1700a7a4c7) | Jan 01, 2023 |
| Gigabyte      | B365 HD3                    | Desktop     | [195240c264](https://linux-hardware.org/?probe=195240c264) | Jan 01, 2023 |
| Dell          | System Inspiron N411Z       | Notebook    | [21f279751c](https://linux-hardware.org/?probe=21f279751c) | Jan 01, 2023 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [e2215a9d80](https://linux-hardware.org/?probe=e2215a9d80) | Jan 01, 2023 |
| Packard Be... | EasyNote TM97               | Notebook    | [fad44d67ab](https://linux-hardware.org/?probe=fad44d67ab) | Jan 01, 2023 |
| HP            | 1000                        | Notebook    | [5634ff72b1](https://linux-hardware.org/?probe=5634ff72b1) | Jan 01, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [bba53b0159](https://linux-hardware.org/?probe=bba53b0159) | Jan 01, 2023 |
| Toshiba       | Satellite A305D             | Notebook    | [b85a377462](https://linux-hardware.org/?probe=b85a377462) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [7295ec02b5](https://linux-hardware.org/?probe=7295ec02b5) | Dec 31, 2022 |
| ASUSTek       | UN45                        | Desktop     | [bde2e2efb1](https://linux-hardware.org/?probe=bde2e2efb1) | Dec 31, 2022 |
| MSI           | MS-7502 Fab D               | Desktop     | [9126e1035f](https://linux-hardware.org/?probe=9126e1035f) | Dec 31, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [b0dd8fc6b5](https://linux-hardware.org/?probe=b0dd8fc6b5) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2537BF9       | Notebook    | [f83ed1dd39](https://linux-hardware.org/?probe=f83ed1dd39) | Dec 30, 2022 |
| ASUSTek       | TP501UA                     | Notebook    | [1f2aaf8804](https://linux-hardware.org/?probe=1f2aaf8804) | Dec 30, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [e4c90250df](https://linux-hardware.org/?probe=e4c90250df) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | Notebook    | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b0bfa9530a](https://linux-hardware.org/?probe=b0bfa9530a) | Dec 29, 2022 |
| ASUSTek       | STRIKER II EXTREME          | Desktop     | [3258ffa0c1](https://linux-hardware.org/?probe=3258ffa0c1) | Dec 29, 2022 |
| ASUSTek       | G1                          | Notebook    | [1f8e426f96](https://linux-hardware.org/?probe=1f8e426f96) | Dec 29, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [1b7e70ab6e](https://linux-hardware.org/?probe=1b7e70ab6e) | Dec 29, 2022 |
| HP            | Notebook                    | Notebook    | [91bc85bf6e](https://linux-hardware.org/?probe=91bc85bf6e) | Dec 29, 2022 |
| Samsung       | NB30/N146                   | Notebook    | [7f9b976789](https://linux-hardware.org/?probe=7f9b976789) | Dec 29, 2022 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [3f0c89985c](https://linux-hardware.org/?probe=3f0c89985c) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [4734f4370b](https://linux-hardware.org/?probe=4734f4370b) | Dec 28, 2022 |
| Lenovo        | V560                        | Notebook    | [f937de4c61](https://linux-hardware.org/?probe=f937de4c61) | Dec 28, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [92ece593f5](https://linux-hardware.org/?probe=92ece593f5) | Dec 28, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [bd56ec4f01](https://linux-hardware.org/?probe=bd56ec4f01) | Dec 28, 2022 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [879a5b77ff](https://linux-hardware.org/?probe=879a5b77ff) | Dec 28, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [6e1255aa44](https://linux-hardware.org/?probe=6e1255aa44) | Dec 28, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [43a0d87199](https://linux-hardware.org/?probe=43a0d87199) | Dec 28, 2022 |
| Positivo      | Hendrix                     | Notebook    | [55aa2f92d7](https://linux-hardware.org/?probe=55aa2f92d7) | Dec 27, 2022 |
| Dell          | Latitude 7480               | Notebook    | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| Pegatron      | APX85-GS                    | Desktop     | [82db9f15c6](https://linux-hardware.org/?probe=82db9f15c6) | Dec 27, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [7a3513a2e1](https://linux-hardware.org/?probe=7a3513a2e1) | Dec 27, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [58b02cceb0](https://linux-hardware.org/?probe=58b02cceb0) | Dec 27, 2022 |
| Acer          | Aspire TC-865 V:1.1         | Desktop     | [0c8add55fe](https://linux-hardware.org/?probe=0c8add55fe) | Dec 27, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [9e6b5e5ebf](https://linux-hardware.org/?probe=9e6b5e5ebf) | Dec 27, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [8ecb7e11b3](https://linux-hardware.org/?probe=8ecb7e11b3) | Dec 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [bc68280036](https://linux-hardware.org/?probe=bc68280036) | Dec 26, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [705baed85a](https://linux-hardware.org/?probe=705baed85a) | Dec 26, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6703f01cfc](https://linux-hardware.org/?probe=6703f01cfc) | Dec 26, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [46123218f3](https://linux-hardware.org/?probe=46123218f3) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | Notebook    | [dfb555f802](https://linux-hardware.org/?probe=dfb555f802) | Dec 26, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [14611d6c99](https://linux-hardware.org/?probe=14611d6c99) | Dec 26, 2022 |
| HP            | 2AF7                        | Desktop     | [96344d97ba](https://linux-hardware.org/?probe=96344d97ba) | Dec 26, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [e012bb5bc1](https://linux-hardware.org/?probe=e012bb5bc1) | Dec 25, 2022 |
| ASUSTek       | M51Tr                       | Notebook    | [dffa412a98](https://linux-hardware.org/?probe=dffa412a98) | Dec 25, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [500abd4186](https://linux-hardware.org/?probe=500abd4186) | Dec 25, 2022 |
| ASUSTek       | NARRA3                      | Desktop     | [cc0a64d0df](https://linux-hardware.org/?probe=cc0a64d0df) | Dec 25, 2022 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [4d1a2299dc](https://linux-hardware.org/?probe=4d1a2299dc) | Dec 24, 2022 |
| Dell          | G7 7790                     | Notebook    | [da767d5fd4](https://linux-hardware.org/?probe=da767d5fd4) | Dec 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [9e269ee2a4](https://linux-hardware.org/?probe=9e269ee2a4) | Dec 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [8c835888d6](https://linux-hardware.org/?probe=8c835888d6) | Dec 24, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [08a1ad1c63](https://linux-hardware.org/?probe=08a1ad1c63) | Dec 24, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [435933801a](https://linux-hardware.org/?probe=435933801a) | Dec 24, 2022 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [11eb39826a](https://linux-hardware.org/?probe=11eb39826a) | Dec 24, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [f2e0369ba1](https://linux-hardware.org/?probe=f2e0369ba1) | Dec 24, 2022 |
| Positivo      | Mobile                      | Notebook    | [6031910e64](https://linux-hardware.org/?probe=6031910e64) | Dec 24, 2022 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [f540a3a892](https://linux-hardware.org/?probe=f540a3a892) | Dec 23, 2022 |
| Positivo      | H14BT58                     | Notebook    | [9914219613](https://linux-hardware.org/?probe=9914219613) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [beb602dcf6](https://linux-hardware.org/?probe=beb602dcf6) | Dec 23, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [f993ebb9ed](https://linux-hardware.org/?probe=f993ebb9ed) | Dec 23, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [5105f25e5e](https://linux-hardware.org/?probe=5105f25e5e) | Dec 23, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [00e62a7231](https://linux-hardware.org/?probe=00e62a7231) | Dec 23, 2022 |
| MSI           | 880GM-E41                   | Desktop     | [2880803d71](https://linux-hardware.org/?probe=2880803d71) | Dec 23, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [561b98afc3](https://linux-hardware.org/?probe=561b98afc3) | Dec 23, 2022 |
| Dell          | 0JJW8N A03                  | Desktop     | [5917cccca0](https://linux-hardware.org/?probe=5917cccca0) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| ASRock        | FM2A88M-HD+                 | Desktop     | [18b83ae613](https://linux-hardware.org/?probe=18b83ae613) | Dec 22, 2022 |
| Dell          | Latitude 5280               | Notebook    | [59002e923b](https://linux-hardware.org/?probe=59002e923b) | Dec 22, 2022 |
| HP            | Pavilion dv9000 (RR329EA... | Notebook    | [6fc7281f2f](https://linux-hardware.org/?probe=6fc7281f2f) | Dec 22, 2022 |
| ASUSTek       | 1015BXO                     | Notebook    | [7cce9a65ec](https://linux-hardware.org/?probe=7cce9a65ec) | Dec 22, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [8f81c02bbf](https://linux-hardware.org/?probe=8f81c02bbf) | Dec 21, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [003ac98d7f](https://linux-hardware.org/?probe=003ac98d7f) | Dec 21, 2022 |
| PERTOSA       | GA-H110TN-M                 | Desktop     | [048d8cca49](https://linux-hardware.org/?probe=048d8cca49) | Dec 21, 2022 |
| Dell          | 0VHWTR A01                  | Desktop     | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ec2528ae6f](https://linux-hardware.org/?probe=ec2528ae6f) | Dec 20, 2022 |
| Acer          | Aspire 5336                 | Notebook    | [9724b5d705](https://linux-hardware.org/?probe=9724b5d705) | Dec 20, 2022 |
| RM Educati... | RM                          | Notebook    | [758b521362](https://linux-hardware.org/?probe=758b521362) | Dec 20, 2022 |
| Langchao      | NF5110                      | Server      | [3578ca8ceb](https://linux-hardware.org/?probe=3578ca8ceb) | Dec 20, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | Notebook    | [215feb2d5e](https://linux-hardware.org/?probe=215feb2d5e) | Dec 20, 2022 |
| ECS           | G31T-M7                     | Desktop     | [327ac25b68](https://linux-hardware.org/?probe=327ac25b68) | Dec 20, 2022 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [3b9937e6df](https://linux-hardware.org/?probe=3b9937e6df) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| LG Electro... | 17Z90P-G.AA56F              | Notebook    | [fa43417151](https://linux-hardware.org/?probe=fa43417151) | Dec 19, 2022 |
| MSI           | H81M-E34                    | Desktop     | [3aa811568d](https://linux-hardware.org/?probe=3aa811568d) | Dec 19, 2022 |
| Toshiba       | EQUIUM A300D                | Notebook    | [ffde5ccef4](https://linux-hardware.org/?probe=ffde5ccef4) | Dec 19, 2022 |
| ASUSTek       | P5QL PRO                    | Desktop     | [5f3343c803](https://linux-hardware.org/?probe=5f3343c803) | Dec 19, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [d1d5c6a19e](https://linux-hardware.org/?probe=d1d5c6a19e) | Dec 19, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b5c4e6cf61](https://linux-hardware.org/?probe=b5c4e6cf61) | Dec 19, 2022 |
| Dell          | 0M858N A00                  | Desktop     | [e46a95080d](https://linux-hardware.org/?probe=e46a95080d) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4f41f354cd](https://linux-hardware.org/?probe=4f41f354cd) | Dec 18, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [ff287eecab](https://linux-hardware.org/?probe=ff287eecab) | Dec 18, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [71ebf721cc](https://linux-hardware.org/?probe=71ebf721cc) | Dec 17, 2022 |
| HP            | 8055                        | Desktop     | [6c7fa83dc9](https://linux-hardware.org/?probe=6c7fa83dc9) | Dec 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [ca6551bf8e](https://linux-hardware.org/?probe=ca6551bf8e) | Dec 17, 2022 |
| Notebook      | W65_67SZ                    | Notebook    | [770c00f7d9](https://linux-hardware.org/?probe=770c00f7d9) | Dec 17, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [0d7a54bc21](https://linux-hardware.org/?probe=0d7a54bc21) | Dec 16, 2022 |
| Dell          | 0RW203                      | Desktop     | [2f5bede488](https://linux-hardware.org/?probe=2f5bede488) | Dec 16, 2022 |
| Lenovo        | Yoga 2-11 20332             | Notebook    | [92a038a164](https://linux-hardware.org/?probe=92a038a164) | Dec 16, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [04cc986bf6](https://linux-hardware.org/?probe=04cc986bf6) | Dec 15, 2022 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [80358a5ba1](https://linux-hardware.org/?probe=80358a5ba1) | Dec 15, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [b2b98c19da](https://linux-hardware.org/?probe=b2b98c19da) | Dec 15, 2022 |
| Acer          | Veriton N2620G              | Desktop     | [a626bf668e](https://linux-hardware.org/?probe=a626bf668e) | Dec 15, 2022 |
| Dell          | 050Nt9 A00                  | All in one  | [075f206957](https://linux-hardware.org/?probe=075f206957) | Dec 15, 2022 |
| Toshiba       | STI 006998G                 | Desktop     | [a41e0d92a7](https://linux-hardware.org/?probe=a41e0d92a7) | Dec 15, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [ffe60f958c](https://linux-hardware.org/?probe=ffe60f958c) | Dec 15, 2022 |
| ASUSTek       | K40IJ                       | Notebook    | [191b6ded65](https://linux-hardware.org/?probe=191b6ded65) | Dec 15, 2022 |
| Dell          | 0FR6WH A01                  | Desktop     | [46d6c645fe](https://linux-hardware.org/?probe=46d6c645fe) | Dec 15, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f18234034f](https://linux-hardware.org/?probe=f18234034f) | Dec 15, 2022 |
| HP            | 2AFB                        | Desktop     | [4c57ea0ee7](https://linux-hardware.org/?probe=4c57ea0ee7) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [587fac961e](https://linux-hardware.org/?probe=587fac961e) | Dec 15, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [9feb549665](https://linux-hardware.org/?probe=9feb549665) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| Lenovo        | ThinkPad X230 23245QP       | Notebook    | [e525a77c95](https://linux-hardware.org/?probe=e525a77c95) | Dec 15, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [b76fa704f7](https://linux-hardware.org/?probe=b76fa704f7) | Dec 15, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [a9d66f9686](https://linux-hardware.org/?probe=a9d66f9686) | Dec 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [259226594a](https://linux-hardware.org/?probe=259226594a) | Dec 14, 2022 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [d5aa2c3900](https://linux-hardware.org/?probe=d5aa2c3900) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | Desktop     | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [0a564c9f0f](https://linux-hardware.org/?probe=0a564c9f0f) | Dec 14, 2022 |
| Datto         | SSD                         | Desktop     | [a9bff0a51c](https://linux-hardware.org/?probe=a9bff0a51c) | Dec 14, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [373f71370e](https://linux-hardware.org/?probe=373f71370e) | Dec 14, 2022 |
| HP            | 304Ah                       | Desktop     | [d8b600f39e](https://linux-hardware.org/?probe=d8b600f39e) | Dec 13, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [8525777743](https://linux-hardware.org/?probe=8525777743) | Dec 13, 2022 |
| Dell          | Latitude E7250              | Notebook    | [3e40466ae4](https://linux-hardware.org/?probe=3e40466ae4) | Dec 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [5d88eed564](https://linux-hardware.org/?probe=5d88eed564) | Dec 13, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| ASUSTek       | Z10PH-D16 Series            | Desktop     | [18911cf243](https://linux-hardware.org/?probe=18911cf243) | Dec 13, 2022 |
| HP            | Notebook                    | Notebook    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [651fa58fbd](https://linux-hardware.org/?probe=651fa58fbd) | Dec 12, 2022 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [074195107c](https://linux-hardware.org/?probe=074195107c) | Dec 12, 2022 |
| Gigabyte      | H310M S2V                   | Desktop     | [6895902fe7](https://linux-hardware.org/?probe=6895902fe7) | Dec 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c832b9b688](https://linux-hardware.org/?probe=c832b9b688) | Dec 12, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [ec5acc536f](https://linux-hardware.org/?probe=ec5acc536f) | Dec 12, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [260a382d54](https://linux-hardware.org/?probe=260a382d54) | Dec 12, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [4784b53f14](https://linux-hardware.org/?probe=4784b53f14) | Dec 12, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [62f6fd5f8d](https://linux-hardware.org/?probe=62f6fd5f8d) | Dec 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [9537bff125](https://linux-hardware.org/?probe=9537bff125) | Dec 11, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| Dell          | 0KG317                      | Desktop     | [cf7f697a0a](https://linux-hardware.org/?probe=cf7f697a0a) | Dec 11, 2022 |
| HP            | 650                         | Notebook    | [9bb3729969](https://linux-hardware.org/?probe=9bb3729969) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [d7ea1184a2](https://linux-hardware.org/?probe=d7ea1184a2) | Dec 10, 2022 |
| Acer          | Aspire V5-573               | Notebook    | [1d88db5ee2](https://linux-hardware.org/?probe=1d88db5ee2) | Dec 10, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [4f392d3575](https://linux-hardware.org/?probe=4f392d3575) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [344383d85d](https://linux-hardware.org/?probe=344383d85d) | Dec 10, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e0584a11c0](https://linux-hardware.org/?probe=e0584a11c0) | Dec 10, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | Desktop     | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| HP            | 18E7                        | Desktop     | [9759493e06](https://linux-hardware.org/?probe=9759493e06) | Dec 09, 2022 |
| ASRock        | 945GCM-S                    | Desktop     | [926787ea67](https://linux-hardware.org/?probe=926787ea67) | Dec 09, 2022 |
| Positivo      | Mobile                      | Notebook    | [bc5f4e6c85](https://linux-hardware.org/?probe=bc5f4e6c85) | Dec 09, 2022 |
| Acer          | TravelMate 5720             | Notebook    | [d0a54f621e](https://linux-hardware.org/?probe=d0a54f621e) | Dec 09, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [99e671f55f](https://linux-hardware.org/?probe=99e671f55f) | Dec 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| Dell          | 0P301D A02                  | Desktop     | [8ab7a916f1](https://linux-hardware.org/?probe=8ab7a916f1) | Dec 08, 2022 |
| HP            | 15                          | Notebook    | [20dfd7b8f5](https://linux-hardware.org/?probe=20dfd7b8f5) | Dec 08, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [29337f7359](https://linux-hardware.org/?probe=29337f7359) | Dec 08, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [0203e79add](https://linux-hardware.org/?probe=0203e79add) | Dec 08, 2022 |
| Packard Be... | DOT S                       | Notebook    | [753f17a658](https://linux-hardware.org/?probe=753f17a658) | Dec 08, 2022 |
| Lenovo        | ThinkPad L530 24783R8       | Notebook    | [406c066d36](https://linux-hardware.org/?probe=406c066d36) | Dec 08, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [469f0a1d1f](https://linux-hardware.org/?probe=469f0a1d1f) | Dec 07, 2022 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [dabda33265](https://linux-hardware.org/?probe=dabda33265) | Dec 07, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [3ab56a93d6](https://linux-hardware.org/?probe=3ab56a93d6) | Dec 07, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [1a35ba24c1](https://linux-hardware.org/?probe=1a35ba24c1) | Dec 07, 2022 |
| ASUSTek       | K53SV                       | Notebook    | [a745b1ead9](https://linux-hardware.org/?probe=a745b1ead9) | Dec 07, 2022 |
| Positivo      | H14BT58                     | Notebook    | [c038df5c8c](https://linux-hardware.org/?probe=c038df5c8c) | Dec 07, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | Desktop     | [c3fc86b5d4](https://linux-hardware.org/?probe=c3fc86b5d4) | Dec 06, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [741c3e22b7](https://linux-hardware.org/?probe=741c3e22b7) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [664d064b07](https://linux-hardware.org/?probe=664d064b07) | Dec 06, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b0bc15145c](https://linux-hardware.org/?probe=b0bc15145c) | Dec 06, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [13ca001c57](https://linux-hardware.org/?probe=13ca001c57) | Dec 06, 2022 |
| HP            | 15                          | Notebook    | [e5a0cdc9de](https://linux-hardware.org/?probe=e5a0cdc9de) | Dec 06, 2022 |
| Lenovo        | 0x36A017AA 31900058 STD     | Desktop     | [ccc212b757](https://linux-hardware.org/?probe=ccc212b757) | Dec 06, 2022 |
| Dell          | Latitude E6540              | Notebook    | [20786b000c](https://linux-hardware.org/?probe=20786b000c) | Dec 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [d8a4f4a923](https://linux-hardware.org/?probe=d8a4f4a923) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | Desktop     | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| ECS           | 945P/PL-A                   | Desktop     | [8db8eec28d](https://linux-hardware.org/?probe=8db8eec28d) | Dec 05, 2022 |
| HP            | Pavilion dv6000 (RV009UA... | Notebook    | [6dcd661136](https://linux-hardware.org/?probe=6dcd661136) | Dec 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [fa3aeacc17](https://linux-hardware.org/?probe=fa3aeacc17) | Dec 05, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [1bf4364f61](https://linux-hardware.org/?probe=1bf4364f61) | Dec 05, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [ee8183087b](https://linux-hardware.org/?probe=ee8183087b) | Dec 04, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [e98fcde376](https://linux-hardware.org/?probe=e98fcde376) | Dec 04, 2022 |
| Sony          | VPCEL2S1E                   | Notebook    | [0c98b9d570](https://linux-hardware.org/?probe=0c98b9d570) | Dec 04, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [af63449087](https://linux-hardware.org/?probe=af63449087) | Dec 04, 2022 |
| Lenovo        | G770 20089                  | Notebook    | [d35d60f972](https://linux-hardware.org/?probe=d35d60f972) | Dec 04, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [fd9114a304](https://linux-hardware.org/?probe=fd9114a304) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | Desktop     | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7bde8b90c7](https://linux-hardware.org/?probe=7bde8b90c7) | Dec 04, 2022 |
| Sony          | VGN-NW31JF_S                | Notebook    | [ebfbfb034a](https://linux-hardware.org/?probe=ebfbfb034a) | Dec 04, 2022 |
| ASUSTek       | K42F                        | Notebook    | [05ddce411d](https://linux-hardware.org/?probe=05ddce411d) | Dec 04, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [bfe28498bd](https://linux-hardware.org/?probe=bfe28498bd) | Dec 04, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [1dbda8e648](https://linux-hardware.org/?probe=1dbda8e648) | Dec 04, 2022 |
| Dell          | Latitude E5510              | Notebook    | [6027856ab6](https://linux-hardware.org/?probe=6027856ab6) | Dec 03, 2022 |
| Acer          | Aspire X3950                | Desktop     | [96044c1932](https://linux-hardware.org/?probe=96044c1932) | Dec 03, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [c79b15a3cf](https://linux-hardware.org/?probe=c79b15a3cf) | Dec 03, 2022 |
| HP            | ProBook 4530s               | Notebook    | [f8f94617e8](https://linux-hardware.org/?probe=f8f94617e8) | Dec 03, 2022 |
| HP            | 8648                        | Desktop     | [79673ee467](https://linux-hardware.org/?probe=79673ee467) | Dec 02, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [d9bba42204](https://linux-hardware.org/?probe=d9bba42204) | Dec 02, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [78f2f440eb](https://linux-hardware.org/?probe=78f2f440eb) | Dec 02, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [8a2aad437e](https://linux-hardware.org/?probe=8a2aad437e) | Dec 02, 2022 |
| Langchao      | NF5110                      | Server      | [ae8b7868da](https://linux-hardware.org/?probe=ae8b7868da) | Dec 02, 2022 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [b566591b3c](https://linux-hardware.org/?probe=b566591b3c) | Dec 02, 2022 |
| Dell          | Latitude E6420              | Notebook    | [011df4cb7f](https://linux-hardware.org/?probe=011df4cb7f) | Dec 02, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [63820e3937](https://linux-hardware.org/?probe=63820e3937) | Dec 01, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [929550dc41](https://linux-hardware.org/?probe=929550dc41) | Dec 01, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [97a1793680](https://linux-hardware.org/?probe=97a1793680) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | Desktop     | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| Medion        | MS-7748                     | Desktop     | [0e92aa55ca](https://linux-hardware.org/?probe=0e92aa55ca) | Nov 30, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| ASUSTek       | Z170-E                      | Desktop     | [5e68d23175](https://linux-hardware.org/?probe=5e68d23175) | Nov 30, 2022 |
| Samsung       | 550XDA                      | Notebook    | [7614fde301](https://linux-hardware.org/?probe=7614fde301) | Nov 30, 2022 |
| Medion        | MS-7800                     | Desktop     | [a5658a6933](https://linux-hardware.org/?probe=a5658a6933) | Nov 30, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [1d20e4ba6d](https://linux-hardware.org/?probe=1d20e4ba6d) | Nov 30, 2022 |
| Dell          | 0YHMCJ A01                  | Server      | [77f946c99b](https://linux-hardware.org/?probe=77f946c99b) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | Desktop     | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9505f905e8](https://linux-hardware.org/?probe=9505f905e8) | Nov 30, 2022 |
| Dell          | Inspiron 5423               | Notebook    | [db57850733](https://linux-hardware.org/?probe=db57850733) | Nov 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1a742c23df](https://linux-hardware.org/?probe=1a742c23df) | Nov 29, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [fa36933936](https://linux-hardware.org/?probe=fa36933936) | Nov 29, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [f03f3a9325](https://linux-hardware.org/?probe=f03f3a9325) | Nov 29, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [20219ca82a](https://linux-hardware.org/?probe=20219ca82a) | Nov 29, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0bd83a29f4](https://linux-hardware.org/?probe=0bd83a29f4) | Nov 29, 2022 |
| ECS           | 945P/PL-A                   | Desktop     | [ff47651dd8](https://linux-hardware.org/?probe=ff47651dd8) | Nov 29, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [d89a05dd31](https://linux-hardware.org/?probe=d89a05dd31) | Nov 29, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d20243efed](https://linux-hardware.org/?probe=d20243efed) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| Toshiba       | Satellite L875              | Notebook    | [2d5e211d72](https://linux-hardware.org/?probe=2d5e211d72) | Nov 28, 2022 |
| Toshiba       | PORTEGE Z30t-A              | Notebook    | [8af94993bd](https://linux-hardware.org/?probe=8af94993bd) | Nov 28, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [51d2b67ca3](https://linux-hardware.org/?probe=51d2b67ca3) | Nov 28, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| Medion        | E11201                      | Notebook    | [0838f9db75](https://linux-hardware.org/?probe=0838f9db75) | Nov 27, 2022 |
| Gateway       | M-1631U                     | Notebook    | [f0f0517dab](https://linux-hardware.org/?probe=f0f0517dab) | Nov 27, 2022 |
| Medion        | E2292                       | Convertible | [98818a6a22](https://linux-hardware.org/?probe=98818a6a22) | Nov 27, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c218724cb4](https://linux-hardware.org/?probe=c218724cb4) | Nov 27, 2022 |
| MSI           | Z77MA-G45                   | Desktop     | [feb165c344](https://linux-hardware.org/?probe=feb165c344) | Nov 27, 2022 |
| ASRock        | A88M-G                      | Desktop     | [323199813d](https://linux-hardware.org/?probe=323199813d) | Nov 27, 2022 |
| Lenovo        | 3000 N500 42336DS           | Notebook    | [f3d917b782](https://linux-hardware.org/?probe=f3d917b782) | Nov 26, 2022 |
| MSI           | P55-CD53                    | Desktop     | [a602949484](https://linux-hardware.org/?probe=a602949484) | Nov 26, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [06c7fdf5c9](https://linux-hardware.org/?probe=06c7fdf5c9) | Nov 26, 2022 |
| Dell          | Latitude E6220              | Notebook    | [aa8d2d2fc7](https://linux-hardware.org/?probe=aa8d2d2fc7) | Nov 26, 2022 |
| HP            | 3397                        | Desktop     | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [d70d7496df](https://linux-hardware.org/?probe=d70d7496df) | Nov 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [9419d2017e](https://linux-hardware.org/?probe=9419d2017e) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| HP            | 0AECh D                     | Desktop     | [857616948b](https://linux-hardware.org/?probe=857616948b) | Nov 26, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [3413fb7947](https://linux-hardware.org/?probe=3413fb7947) | Nov 26, 2022 |
| HP            | 1589                        | Desktop     | [077a89fb54](https://linux-hardware.org/?probe=077a89fb54) | Nov 26, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [7948a35f59](https://linux-hardware.org/?probe=7948a35f59) | Nov 25, 2022 |
| Acer          | NC-ES1-512-C3AH             | Notebook    | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| HP            | 2215                        | Desktop     | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [9f49ff06cf](https://linux-hardware.org/?probe=9f49ff06cf) | Nov 24, 2022 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [418849100f](https://linux-hardware.org/?probe=418849100f) | Nov 24, 2022 |
| HP            | 650                         | Notebook    | [15c69c43ca](https://linux-hardware.org/?probe=15c69c43ca) | Nov 24, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [e7bf51183d](https://linux-hardware.org/?probe=e7bf51183d) | Nov 24, 2022 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [7d448ab5cc](https://linux-hardware.org/?probe=7d448ab5cc) | Nov 24, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [600e3f0f09](https://linux-hardware.org/?probe=600e3f0f09) | Nov 24, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [adcb4db30d](https://linux-hardware.org/?probe=adcb4db30d) | Nov 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [9b50d75b30](https://linux-hardware.org/?probe=9b50d75b30) | Nov 24, 2022 |
| Foxconn       | 2A92                        | Desktop     | [e21715c047](https://linux-hardware.org/?probe=e21715c047) | Nov 24, 2022 |
| Supermicro    | PDSMi+                      | Desktop     | [3a70b82d42](https://linux-hardware.org/?probe=3a70b82d42) | Nov 24, 2022 |
| Intel         | B75                         | Desktop     | [a8932d4a21](https://linux-hardware.org/?probe=a8932d4a21) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | Notebook    | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| HP            | 8582 01100                  | All in one  | [4977f9d91d](https://linux-hardware.org/?probe=4977f9d91d) | Nov 23, 2022 |
| Sony          | VPCEG16EG                   | Notebook    | [ee22559858](https://linux-hardware.org/?probe=ee22559858) | Nov 23, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [ca7e5eab8d](https://linux-hardware.org/?probe=ca7e5eab8d) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| HP            | Notebook                    | Notebook    | [616c071073](https://linux-hardware.org/?probe=616c071073) | Nov 23, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [063ffbb0e8](https://linux-hardware.org/?probe=063ffbb0e8) | Nov 23, 2022 |
| Lenovo        | IdeaPad U310 Touch          | Notebook    | [09beadc5ae](https://linux-hardware.org/?probe=09beadc5ae) | Nov 22, 2022 |
| Intel         | DG41TY AAE47335-302         | Desktop     | [ae2fb8d0b3](https://linux-hardware.org/?probe=ae2fb8d0b3) | Nov 22, 2022 |
| Intel         | powered classmate PC        | Notebook    | [d74f69f66a](https://linux-hardware.org/?probe=d74f69f66a) | Nov 22, 2022 |
| Lenovo        | ThinkPad R500 2716AZJ       | Notebook    | [ecf18761e4](https://linux-hardware.org/?probe=ecf18761e4) | Nov 22, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [1c7b4c3780](https://linux-hardware.org/?probe=1c7b4c3780) | Nov 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| HP            | 3399                        | Desktop     | [bce6df1ffb](https://linux-hardware.org/?probe=bce6df1ffb) | Nov 21, 2022 |
| ASUSTek       | F1A55-M LE                  | Desktop     | [f2120128c1](https://linux-hardware.org/?probe=f2120128c1) | Nov 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [d8632e2872](https://linux-hardware.org/?probe=d8632e2872) | Nov 21, 2022 |
| ASRock        | P67 Extreme4                | Desktop     | [569fd8178d](https://linux-hardware.org/?probe=569fd8178d) | Nov 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [049f06f11d](https://linux-hardware.org/?probe=049f06f11d) | Nov 21, 2022 |
| AZW           | SEi                         | Desktop     | [a8e813c483](https://linux-hardware.org/?probe=a8e813c483) | Nov 21, 2022 |
| Dell          | 00NNT0 A00                  | Desktop     | [c25787d8b9](https://linux-hardware.org/?probe=c25787d8b9) | Nov 20, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.3/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003       | 4324      | 91.82%  |
| 5.16.13-desktop-1omv4003      | 341       | 7.24%   |
| 5.17.1-desktop-2omv4050       | 18        | 0.38%   |
| 5.14.14-desktop-1omv4050      | 7         | 0.15%   |
| 5.16.5-desktop-2omv4003       | 4         | 0.08%   |
| 5.17.1-desktop-clang-2omv4050 | 2         | 0.04%   |
| 5.16.9-desktop-1omv4003       | 2         | 0.04%   |
| 5.16.3-desktop-2omv4050       | 2         | 0.04%   |
| 5.10.14-desktop-1omv4002      | 2         | 0.04%   |
| 6.1.10                        | 1         | 0.02%   |
| 5.17.7-desktop-1omv4090       | 1         | 0.02%   |
| 5.16.9-desktop-1omv4050       | 1         | 0.02%   |
| 5.16.7-desktop-clang-1omv4003 | 1         | 0.02%   |
| 5.16.13-desktop-1omv4050      | 1         | 0.02%   |
| 5.15.14-1-lts                 | 1         | 0.02%   |
| 5.11.12-desktop-1omv4002      | 1         | 0.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.7  | 4325      | 91.85%  |
| 5.16.13 | 342       | 7.26%   |
| 5.17.1  | 20        | 0.42%   |
| 5.14.14 | 7         | 0.15%   |
| 5.16.5  | 4         | 0.08%   |
| 5.16.9  | 3         | 0.06%   |
| 5.16.3  | 2         | 0.04%   |
| 5.10.14 | 2         | 0.04%   |
| 6.1.10  | 1         | 0.02%   |
| 5.17.7  | 1         | 0.02%   |
| 5.15.14 | 1         | 0.02%   |
| 5.11.12 | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 4604      | 99.29%  |
| 5.17    | 21        | 0.45%   |
| 5.14    | 7         | 0.15%   |
| 5.10    | 2         | 0.04%   |
| 6.1     | 1         | 0.02%   |
| 5.15    | 1         | 0.02%   |
| 5.11    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 4636      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 4616      | 99.46%  |
| LXQt     | 9         | 0.19%   |
| Unknown  | 7         | 0.15%   |
| Budgie   | 5         | 0.11%   |
| Cinnamon | 4         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4608      | 99.37%  |
| Wayland | 29        | 0.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 4631      | 99.87%  |
| LightDM | 6         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 2584      | 55.32%  |
| de_DE | 402       | 8.61%   |
| fr_FR | 249       | 5.33%   |
| ru_RU | 243       | 5.2%    |
| pt_BR | 192       | 4.11%   |
| pl_PL | 143       | 3.06%   |
| it_IT | 127       | 2.72%   |
| en_GB | 101       | 2.16%   |
| es_ES | 91        | 1.95%   |
| cs_CZ | 52        | 1.11%   |
| es_MX | 46        | 0.98%   |
| es_AR | 45        | 0.96%   |
| de_AT | 41        | 0.88%   |
| en_IN | 27        | 0.58%   |
| hu_HU | 25        | 0.54%   |
| en_CA | 23        | 0.49%   |
| tr_TR | 21        | 0.45%   |
| pt_PT | 20        | 0.43%   |
| es_CO | 19        | 0.41%   |
| fr_CA | 18        | 0.39%   |
| nl_NL | 17        | 0.36%   |
| en_AU | 16        | 0.34%   |
| es_CL | 15        | 0.32%   |
| de_CH | 15        | 0.32%   |
| fr_BE | 13        | 0.28%   |
| ru_UA | 11        | 0.24%   |
| es_VE | 11        | 0.24%   |
| nl_BE | 9         | 0.19%   |
| da_DK | 9         | 0.19%   |
| es_PE | 8         | 0.17%   |
| nb_NO | 7         | 0.15%   |
| fr_CH | 6         | 0.13%   |
| ro_RO | 5         | 0.11%   |
| es_CR | 5         | 0.11%   |
| es_UY | 4         | 0.09%   |
| es_EC | 4         | 0.09%   |
| es_BO | 4         | 0.09%   |
| uk_UA | 3         | 0.06%   |
| es_SV | 3         | 0.06%   |
| es_DO | 3         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2404      | 51.75%  |
| BIOS | 2241      | 48.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Overlay  | 3701      | 78.46%  |
| Ext4     | 992       | 21.03%  |
| Btrfs    | 8         | 0.17%   |
| Xfs      | 7         | 0.15%   |
| F2fs     | 5         | 0.11%   |
| Jfs      | 2         | 0.04%   |
| Reiserfs | 1         | 0.02%   |
| Ext3     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3113      | 66.83%  |
| MBR     | 1525      | 32.74%  |
| Unknown | 20        | 0.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2550      | 54.52%  |
| No        | 2127      | 45.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2362      | 50.81%  |
| Yes       | 2287      | 49.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 736       | 15.88%  |
| Dell                | 613       | 13.22%  |
| Hewlett-Packard     | 609       | 13.14%  |
| Lenovo              | 540       | 11.65%  |
| Gigabyte Technology | 404       | 8.71%   |
| Acer                | 308       | 6.64%   |
| MSI                 | 271       | 5.85%   |
| ASRock              | 190       | 4.1%    |
| Toshiba             | 109       | 2.35%   |
| Intel               | 99        | 2.14%   |
| Apple               | 81        | 1.75%   |
| Fujitsu             | 72        | 1.55%   |
| Samsung Electronics | 51        | 1.1%    |
| Sony                | 48        | 1.04%   |
| Positivo            | 34        | 0.73%   |
| Medion              | 29        | 0.63%   |
| Foxconn             | 28        | 0.6%    |
| Pegatron            | 26        | 0.56%   |
| Packard Bell        | 25        | 0.54%   |
| Biostar             | 25        | 0.54%   |
| Unknown             | 20        | 0.43%   |
| ECS                 | 17        | 0.37%   |
| AZW                 | 14        | 0.3%    |
| Fujitsu Siemens     | 13        | 0.28%   |
| HUAWEI              | 12        | 0.26%   |
| eMachines           | 11        | 0.24%   |
| Alienware           | 11        | 0.24%   |
| TUXEDO              | 10        | 0.22%   |
| BESSTAR Tech        | 10        | 0.22%   |
| Philco              | 9         | 0.19%   |
| Chuwi               | 9         | 0.19%   |
| Shuttle             | 8         | 0.17%   |
| LG Electronics      | 8         | 0.17%   |
| Supermicro          | 7         | 0.15%   |
| Notebook            | 7         | 0.15%   |
| Compaq              | 7         | 0.15%   |
| Microsoft           | 6         | 0.13%   |
| Gateway             | 6         | 0.13%   |
| MACHINIST           | 5         | 0.11%   |
| Digibras            | 5         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell Latitude 3120             | 48        | 1.04%   |
| ASUS All Series                | 44        | 0.95%   |
| Unknown                        | 35        | 0.75%   |
| Dell Latitude 3190 2-in-1      | 34        | 0.73%   |
| Dell Latitude 3310             | 29        | 0.63%   |
| Gigabyte H410M H V3            | 27        | 0.58%   |
| HP Notebook                    | 23        | 0.5%    |
| ASUS SABERTOOTH Z77            | 19        | 0.41%   |
| Dell OptiPlex 7010             | 18        | 0.39%   |
| ASUS UX31E                     | 18        | 0.39%   |
| Lenovo IdeaPad 1 14ADA05 82GW  | 11        | 0.24%   |
| HP Pavilion g6                 | 11        | 0.24%   |
| Intel H61                      | 10        | 0.22%   |
| HP Pavilion dv6                | 10        | 0.22%   |
| Dell OptiPlex 780              | 10        | 0.22%   |
| Sony VGN-FZ31Z                 | 9         | 0.19%   |
| MSI MS-7C91                    | 9         | 0.19%   |
| Gigabyte B450M DS3H            | 9         | 0.19%   |
| ASUS PRIME B450M-A II          | 9         | 0.19%   |
| Lenovo IdeaPad S145-15AST 81N3 | 8         | 0.17%   |
| HP ProDesk 600 G1 SFF          | 8         | 0.17%   |
| Dell OptiPlex 9020             | 8         | 0.17%   |
| Dell OptiPlex 790              | 8         | 0.17%   |
| Dell OptiPlex 380              | 8         | 0.17%   |
| Dell OptiPlex 3020             | 8         | 0.17%   |
| Dell Latitude 3300             | 8         | 0.17%   |
| Acer Nitro AN515-57            | 8         | 0.17%   |
| Positivo Mobile                | 7         | 0.15%   |
| MSI MS-7A38                    | 7         | 0.15%   |
| HP EliteDesk 800 G1 SFF        | 7         | 0.15%   |
| HP 15                          | 7         | 0.15%   |
| Dell XPS 15 9530               | 7         | 0.15%   |
| Dell Latitude E7450            | 7         | 0.15%   |
| Dell Latitude E7240            | 7         | 0.15%   |
| Dell Latitude E6430            | 7         | 0.15%   |
| Dell Latitude E6420            | 7         | 0.15%   |
| Acer Aspire A515-51G           | 7         | 0.15%   |
| MSI MS-7C37                    | 6         | 0.13%   |
| MSI MS-7C02                    | 6         | 0.13%   |
| MSI MS-7B79                    | 6         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 286       | 6.17%   |
| Acer Aspire           | 206       | 4.44%   |
| Lenovo ThinkPad       | 172       | 3.71%   |
| Lenovo IdeaPad        | 139       | 3%      |
| Dell OptiPlex         | 116       | 2.5%    |
| HP Pavilion           | 107       | 2.31%   |
| HP Compaq             | 92        | 1.98%   |
| Toshiba Satellite     | 88        | 1.9%    |
| ASUS PRIME            | 87        | 1.88%   |
| Dell Inspiron         | 86        | 1.86%   |
| Lenovo ThinkCentre    | 64        | 1.38%   |
| HP Laptop             | 63        | 1.36%   |
| HP ProBook            | 55        | 1.19%   |
| ASUS VivoBook         | 44        | 0.95%   |
| ASUS All              | 44        | 0.95%   |
| ASUS TUF              | 41        | 0.88%   |
| ASUS ROG              | 38        | 0.82%   |
| HP EliteDesk          | 36        | 0.78%   |
| Unknown               | 35        | 0.75%   |
| Dell Precision        | 34        | 0.73%   |
| HP EliteBook          | 33        | 0.71%   |
| Gigabyte H410M        | 31        | 0.67%   |
| Dell Vostro           | 31        | 0.67%   |
| Fujitsu ESPRIMO       | 29        | 0.63%   |
| Dell XPS              | 29        | 0.63%   |
| Fujitsu LIFEBOOK      | 28        | 0.6%    |
| HP ProDesk            | 27        | 0.58%   |
| ASUS SABERTOOTH       | 25        | 0.54%   |
| HP Notebook           | 23        | 0.5%    |
| Acer Nitro            | 22        | 0.47%   |
| Lenovo IdeaCentre     | 21        | 0.45%   |
| Gigabyte B450M        | 19        | 0.41%   |
| ASUS M5A78L-M         | 19        | 0.41%   |
| ASUS UX31E            | 18        | 0.39%   |
| Packard Bell EasyNote | 17        | 0.37%   |
| Lenovo Yoga           | 15        | 0.32%   |
| Acer Veriton          | 14        | 0.3%    |
| Acer Swift            | 13        | 0.28%   |
| HP 250                | 12        | 0.26%   |
| Acer TravelMate       | 12        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 476       | 10.27%  |
| 2011    | 434       | 9.36%   |
| 2013    | 382       | 8.24%   |
| 2019    | 343       | 7.4%    |
| 2021    | 341       | 7.36%   |
| 2014    | 331       | 7.14%   |
| 2020    | 330       | 7.12%   |
| 2018    | 327       | 7.05%   |
| 2010    | 294       | 6.34%   |
| 2016    | 239       | 5.16%   |
| 2017    | 226       | 4.87%   |
| 2015    | 221       | 4.77%   |
| 2009    | 217       | 4.68%   |
| 2008    | 214       | 4.62%   |
| 2007    | 140       | 3.02%   |
| 2006    | 65        | 1.4%    |
| 2022    | 43        | 0.93%   |
| 2005    | 7         | 0.15%   |
| Unknown | 4         | 0.09%   |
| 2023    | 2         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2175      | 46.92%  |
| Desktop     | 2147      | 46.31%  |
| Convertible | 126       | 2.72%   |
| All in one  | 76        | 1.64%   |
| Mini pc     | 75        | 1.62%   |
| Server      | 20        | 0.43%   |
| Tablet      | 17        | 0.37%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4636      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4629      | 99.85%  |
| Yes  | 7         | 0.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1312      | 28.22%  |
| 3.01-4.0        | 1202      | 25.85%  |
| 8.01-16.0       | 821       | 17.66%  |
| 16.01-24.0      | 689       | 14.82%  |
| 32.01-64.0      | 269       | 5.78%   |
| 1.01-2.0        | 159       | 3.42%   |
| 24.01-32.0      | 62        | 1.33%   |
| 64.01-256.0     | 62        | 1.33%   |
| 2.01-3.0        | 61        | 1.31%   |
| 0.51-1.0        | 10        | 0.22%   |
| More than 256.0 | 3         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 3425      | 72.9%   |
| 0.51-1.0  | 787       | 16.75%  |
| 2.01-3.0  | 349       | 7.43%   |
| 0.01-0.5  | 75        | 1.6%    |
| 3.01-4.0  | 35        | 0.74%   |
| 4.01-8.0  | 16        | 0.34%   |
| 8.01-16.0 | 11        | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2751      | 58.95%  |
| 2      | 1126      | 24.13%  |
| 3      | 364       | 7.8%    |
| 4      | 196       | 4.2%    |
| 0      | 83        | 1.78%   |
| 5      | 78        | 1.67%   |
| 6      | 31        | 0.66%   |
| 7      | 13        | 0.28%   |
| 8      | 7         | 0.15%   |
| 9      | 6         | 0.13%   |
| 12     | 3         | 0.06%   |
| 11     | 3         | 0.06%   |
| 13     | 2         | 0.04%   |
| 25     | 1         | 0.02%   |
| 18     | 1         | 0.02%   |
| 15     | 1         | 0.02%   |
| 10     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2368      | 50.98%  |
| No        | 2277      | 49.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4178      | 90.12%  |
| No        | 458       | 9.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3188      | 68.68%  |
| No        | 1454      | 31.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2327      | 50.13%  |
| No        | 2315      | 49.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 552       | 11.89%  |
| USA         | 531       | 11.44%  |
| France      | 318       | 6.85%   |
| Brazil      | 303       | 6.53%   |
| Russia      | 299       | 6.44%   |
| Poland      | 236       | 5.08%   |
| Netherlands | 199       | 4.29%   |
| Italy       | 197       | 4.24%   |
| UK          | 146       | 3.14%   |
| Spain       | 125       | 2.69%   |
| Canada      | 121       | 2.61%   |
| Mexico      | 87        | 1.87%   |
| India       | 78        | 1.68%   |
| Australia   | 75        | 1.62%   |
| Czechia     | 71        | 1.53%   |
| Japan       | 61        | 1.31%   |
| Indonesia   | 61        | 1.31%   |
| Argentina   | 57        | 1.23%   |
| Austria     | 54        | 1.16%   |
| Romania     | 50        | 1.08%   |
| Portugal    | 50        | 1.08%   |
| Ukraine     | 48        | 1.03%   |
| Turkey      | 43        | 0.93%   |
| Switzerland | 43        | 0.93%   |
| Sweden      | 41        | 0.88%   |
| Belgium     | 40        | 0.86%   |
| Hungary     | 39        | 0.84%   |
| Colombia    | 37        | 0.8%    |
| Slovakia    | 31        | 0.67%   |
| Serbia      | 28        | 0.6%    |
| Finland     | 26        | 0.56%   |
| China       | 24        | 0.52%   |
| Chile       | 23        | 0.5%    |
| Greece      | 22        | 0.47%   |
| Bulgaria    | 22        | 0.47%   |
| Egypt       | 21        | 0.45%   |
| Peru        | 20        | 0.43%   |
| Norway      | 19        | 0.41%   |
| Venezuela   | 18        | 0.39%   |
| Israel      | 17        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Schagen        | 137       | 2.91%   |
| Moscow         | 58        | 1.23%   |
| Paris          | 40        | 0.85%   |
| Warsaw         | 39        | 0.83%   |
| Berlin         | 38        | 0.81%   |
| Sao Paulo      | 36        | 0.76%   |
| Prague         | 30        | 0.64%   |
| Vienna         | 27        | 0.57%   |
| Milan          | 26        | 0.55%   |
| Munich         | 24        | 0.51%   |
| Mexico City    | 23        | 0.49%   |
| Gonikoppal     | 22        | 0.47%   |
| Sydney         | 21        | 0.45%   |
| St Petersburg  | 18        | 0.38%   |
| Rio de Janeiro | 18        | 0.38%   |
| Istanbul       | 18        | 0.38%   |
| Strzyzow       | 17        | 0.36%   |
| Jakarta        | 17        | 0.36%   |
| Hamburg        | 17        | 0.36%   |
| Belgrade       | 17        | 0.36%   |
| Madrid         | 16        | 0.34%   |
| Krakow         | 14        | 0.3%    |
| Cairo          | 14        | 0.3%    |
| Bengaluru      | 14        | 0.3%    |
| Rome           | 13        | 0.28%   |
| Lima           | 13        | 0.28%   |
| Poznan         | 12        | 0.25%   |
| Gdansk         | 12        | 0.25%   |
| Brisbane       | 12        | 0.25%   |
| Bratislava     | 12        | 0.25%   |
| Helsinki       | 11        | 0.23%   |
| Cluj-Napoca    | 11        | 0.23%   |
| Cascais        | 11        | 0.23%   |
| Bucharest      | 11        | 0.23%   |
| Barcelona      | 11        | 0.23%   |
| Zagreb         | 10        | 0.21%   |
| Wroclaw        | 10        | 0.21%   |
| San José      | 10        | 0.21%   |
| Montreal       | 10        | 0.21%   |
| Montevideo     | 10        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1137      | 1413   | 16.92%  |
| Seagate             | 994       | 1266   | 14.8%   |
| Samsung Electronics | 864       | 1068   | 12.86%  |
| Toshiba             | 466       | 510    | 6.94%   |
| Kingston            | 392       | 430    | 5.84%   |
| Crucial             | 290       | 336    | 4.32%   |
| SanDisk             | 285       | 322    | 4.24%   |
| Hitachi             | 275       | 300    | 4.09%   |
| Unknown             | 179       | 198    | 2.66%   |
| A-DATA Technology   | 157       | 167    | 2.34%   |
| SK hynix            | 141       | 146    | 2.1%    |
| HGST                | 127       | 144    | 1.89%   |
| China               | 78        | 86     | 1.16%   |
| Intel               | 74        | 80     | 1.1%    |
| Micron Technology   | 69        | 74     | 1.03%   |
| GOODRAM             | 52        | 54     | 0.77%   |
| PNY                 | 46        | 57     | 0.68%   |
| SPCC                | 44        | 48     | 0.65%   |
| Unknown             | 44        | 46     | 0.65%   |
| Intenso             | 43        | 44     | 0.64%   |
| Patriot             | 39        | 42     | 0.58%   |
| Maxtor              | 38        | 43     | 0.57%   |
| LITEON              | 37        | 37     | 0.55%   |
| Apple               | 37        | 39     | 0.55%   |
| KIOXIA              | 36        | 36     | 0.54%   |
| JMicron Technology  | 34        | 35     | 0.51%   |
| Apacer              | 34        | 35     | 0.51%   |
| ASMT                | 33        | 40     | 0.49%   |
| Gigabyte Technology | 32        | 32     | 0.48%   |
| Fujitsu             | 29        | 30     | 0.43%   |
| OCZ                 | 26        | 26     | 0.39%   |
| Netac               | 26        | 30     | 0.39%   |
| Phison              | 25        | 28     | 0.37%   |
| Corsair             | 25        | 27     | 0.37%   |
| Transcend           | 24        | 26     | 0.36%   |
| Team                | 24        | 24     | 0.36%   |
| SSSTC               | 24        | 24     | 0.36%   |
| Hewlett-Packard     | 23        | 32     | 0.34%   |
| Silicon Motion      | 19        | 22     | 0.28%   |
| KingSpec            | 18        | 18     | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 97        | 1.32%   |
| Seagate ST500DM002-1BD142 500GB     | 75        | 1.02%   |
| Seagate ST1000DM010-2EP102 1TB      | 65        | 0.88%   |
| Samsung SSD 860 EVO 500GB           | 48        | 0.65%   |
| Kingston SA400S37480G 480GB SSD     | 48        | 0.65%   |
| Kingston SA400S37120G 120GB SSD     | 45        | 0.61%   |
| Toshiba MQ01ABF050 500GB            | 44        | 0.6%    |
| Toshiba MQ01ABD100 1TB              | 44        | 0.6%    |
| Unknown                             | 44        | 0.6%    |
| Unknown SD/MMC/MS PRO 128GB         | 43        | 0.59%   |
| Samsung SSD 860 EVO 250GB           | 43        | 0.59%   |
| Samsung SSD 850 EVO 250GB           | 43        | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB            | 42        | 0.57%   |
| Crucial CT500MX500SSD1 500GB        | 42        | 0.57%   |
| Toshiba DT01ACA100 1TB              | 40        | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 40        | 0.54%   |
| Crucial CT240BX500SSD1 240GB        | 39        | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 34        | 0.46%   |
| Seagate ST2000DM008-2FR102 2TB      | 34        | 0.46%   |
| Toshiba MQ04ABF100 1TB              | 33        | 0.45%   |
| Seagate ST500LT012-1DG142 500GB     | 33        | 0.45%   |
| Seagate ST1000LM035-1RK172 1TB      | 32        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD    | 32        | 0.44%   |
| Toshiba DT01ACA050 500GB            | 30        | 0.41%   |
| Samsung SSD 850 EVO 500GB           | 29        | 0.39%   |
| Crucial CT1000MX500SSD1 1TB         | 29        | 0.39%   |
| Crucial CT480BX500SSD1 480GB        | 28        | 0.38%   |
| Seagate ST1000DM003-1ER162 1TB      | 27        | 0.37%   |
| Seagate ST9500325AS 500GB           | 26        | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB      | 26        | 0.35%   |
| SanDisk SSD PLUS 240GB              | 25        | 0.34%   |
| HGST HTS545050A7E680 500GB          | 25        | 0.34%   |
| Seagate ST3500418AS 500GB           | 23        | 0.31%   |
| Samsung SSD 970 EVO Plus 1TB        | 23        | 0.31%   |
| Samsung HD502HJ 500GB               | 23        | 0.31%   |
| SK hynix BC711 NVMe 128GB           | 22        | 0.3%    |
| HGST HTS721010A9E630 1TB            | 22        | 0.3%    |
| A-DATA SU750 256GB SSD              | 22        | 0.3%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 21        | 0.29%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 20        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 979       | 1240   | 31.66%  |
| WDC                 | 922       | 1118   | 29.82%  |
| Toshiba             | 413       | 452    | 13.36%  |
| Hitachi             | 275       | 300    | 8.89%   |
| Samsung Electronics | 181       | 211    | 5.85%   |
| HGST                | 127       | 144    | 4.11%   |
| Unknown             | 44        | 44     | 1.42%   |
| Maxtor              | 36        | 41     | 1.16%   |
| Fujitsu             | 29        | 30     | 0.94%   |
| Apple               | 17        | 18     | 0.55%   |
| TO Exter            | 7         | 7      | 0.23%   |
| ASMT                | 7         | 14     | 0.23%   |
| USB3.0              | 6         | 6      | 0.19%   |
| Hewlett-Packard     | 5         | 11     | 0.16%   |
| WD MediaMax         | 4         | 5      | 0.13%   |
| Intenso             | 4         | 4      | 0.13%   |
| IBM/Hitachi         | 4         | 5      | 0.13%   |
| SAGE                | 3         | 3      | 0.1%    |
| Magnetic Data       | 3         | 3      | 0.1%    |
| JMicron Technology  | 3         | 3      | 0.1%    |
| Initio              | 2         | 2      | 0.06%   |
| HPE                 | 2         | 3      | 0.06%   |
| External            | 2         | 2      | 0.06%   |
| Unknown             | 2         | 2      | 0.06%   |
| USB                 | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| SSK                 | 1         | 1      | 0.03%   |
| RSH-339             | 1         | 1      | 0.03%   |
| QUANTUM             | 1         | 1      | 0.03%   |
| QC-FT-D             | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| MARSHAL             | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| ExcelStor           | 1         | 1      | 0.03%   |
| Config              | 1         | 1      | 0.03%   |
| China               | 1         | 1      | 0.03%   |
| ASMedia             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 473       | 551    | 18.61%  |
| Kingston            | 327       | 356    | 12.87%  |
| SanDisk             | 251       | 282    | 9.88%   |
| Crucial             | 247       | 284    | 9.72%   |
| WDC                 | 140       | 159    | 5.51%   |
| A-DATA Technology   | 125       | 127    | 4.92%   |
| China               | 77        | 85     | 3.03%   |
| Micron Technology   | 50        | 53     | 1.97%   |
| GOODRAM             | 50        | 50     | 1.97%   |
| PNY                 | 40        | 48     | 1.57%   |
| SK hynix            | 39        | 40     | 1.53%   |
| Toshiba             | 37        | 39     | 1.46%   |
| LITEON              | 34        | 34     | 1.34%   |
| SPCC                | 33        | 36     | 1.3%    |
| Patriot             | 33        | 36     | 1.3%    |
| Intenso             | 32        | 33     | 1.26%   |
| Intel               | 32        | 34     | 1.26%   |
| Apacer              | 31        | 31     | 1.22%   |
| OCZ                 | 26        | 26     | 1.02%   |
| Team                | 23        | 23     | 0.91%   |
| Unknown             | 23        | 24     | 0.91%   |
| Transcend           | 22        | 23     | 0.87%   |
| Netac               | 22        | 26     | 0.87%   |
| ASMT                | 22        | 22     | 0.87%   |
| JMicron Technology  | 21        | 22     | 0.83%   |
| Gigabyte Technology | 20        | 20     | 0.79%   |
| KingSpec            | 18        | 18     | 0.71%   |
| Apple               | 18        | 18     | 0.71%   |
| LITEONIT            | 14        | 16     | 0.55%   |
| Hewlett-Packard     | 13        | 15     | 0.51%   |
| Corsair             | 12        | 13     | 0.47%   |
| Lexar               | 11        | 11     | 0.43%   |
| KIOXIA-EXCERIA      | 9         | 9      | 0.35%   |
| KingDian            | 9         | 10     | 0.35%   |
| Leven               | 8         | 9      | 0.31%   |
| KingFast            | 8         | 8      | 0.31%   |
| Seagate             | 7         | 7      | 0.28%   |
| Emtec               | 6         | 6      | 0.24%   |
| Colorful            | 6         | 7      | 0.24%   |
| TCSUNBOW            | 5         | 5      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2612      | 3683   | 44.06%  |
| SSD     | 2168      | 2786   | 36.57%  |
| NVMe    | 914       | 1081   | 15.42%  |
| MMC     | 159       | 171    | 2.68%   |
| Unknown | 75        | 91     | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3962      | 6186   | 74.04%  |
| NVMe | 907       | 1063   | 16.95%  |
| SAS  | 323       | 392    | 6.04%   |
| MMC  | 159       | 171    | 2.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3152      | 4165   | 63.69%  |
| 0.51-1.0   | 1294      | 1618   | 26.15%  |
| 1.01-2.0   | 306       | 411    | 6.18%   |
| 2.01-3.0   | 63        | 82     | 1.27%   |
| 3.01-4.0   | 62        | 88     | 1.25%   |
| 4.01-10.0  | 60        | 93     | 1.21%   |
| 10.01-20.0 | 11        | 11     | 0.22%   |
| 20.01-50.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2559      | 54.19%  |
| 101-250        | 680       | 14.4%   |
| 251-500        | 404       | 8.56%   |
| Unknown        | 366       | 7.75%   |
| 501-1000       | 217       | 4.6%    |
| 51-100         | 201       | 4.26%   |
| 21-50          | 181       | 3.83%   |
| 1001-2000      | 74        | 1.57%   |
| More than 3000 | 21        | 0.44%   |
| 2001-3000      | 19        | 0.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3889      | 82.8%   |
| Unknown        | 366       | 7.79%   |
| 101-250        | 111       | 2.36%   |
| 21-50          | 107       | 2.28%   |
| 51-100         | 96        | 2.04%   |
| 251-500        | 60        | 1.28%   |
| 501-1000       | 39        | 0.83%   |
| 1001-2000      | 19        | 0.4%    |
| More than 3000 | 7         | 0.15%   |
| 2001-3000      | 3         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 34        | 35     | 2.4%    |
| HGST HTS545050A7E680 500GB          | 20        | 20     | 1.41%   |
| Seagate ST9500325AS 500GB           | 19        | 19     | 1.34%   |
| SanDisk SSD U100 256GB              | 18        | 18     | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 17        | 17     | 1.2%    |
| HGST HTS541010A9E680 1TB            | 13        | 14     | 0.92%   |
| Toshiba MQ01ABF050 500GB            | 12        | 12     | 0.85%   |
| Seagate ST9320325AS 320GB           | 11        | 11     | 0.78%   |
| Kingston SV300S37A120G 120GB SSD    | 11        | 11     | 0.78%   |
| Samsung Electronics HD322HJ 320GB   | 10        | 11     | 0.71%   |
| Hitachi HTS543232A7A384 320GB       | 10        | 11     | 0.71%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 9         | 10     | 0.64%   |
| Toshiba MQ01ABD100 1TB              | 9         | 9      | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB      | 9         | 11     | 0.64%   |
| Seagate ST1000DM003-9YN162 1TB      | 9         | 9      | 0.64%   |
| HGST HTS721010A9E630 1TB            | 9         | 11     | 0.64%   |
| Crucial CT240M500SSD1 240GB         | 9         | 9      | 0.64%   |
| Toshiba MQ01ABD050 500GB            | 8         | 8      | 0.57%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 8      | 0.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 8         | 8      | 0.57%   |
| Seagate ST3500418AS 500GB           | 8         | 9      | 0.57%   |
| Seagate ST3500413AS 500GB           | 8         | 8      | 0.57%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 8      | 0.57%   |
| SanDisk SSD PLUS 240GB              | 8         | 8      | 0.57%   |
| Seagate ST500LT012-9WS142 500GB     | 7         | 7      | 0.49%   |
| Seagate ST31000524AS 1TB            | 7         | 8      | 0.49%   |
| Samsung Electronics HD502HJ 500GB   | 7         | 7      | 0.49%   |
| Hitachi HTS725032A7E630 320GB       | 7         | 7      | 0.49%   |
| Hitachi HTS545050A7E380 500GB       | 7         | 7      | 0.49%   |
| HGST HTS545050A7E380 500GB          | 7         | 7      | 0.49%   |
| WDC WD5000AAKS-00V1A0 500GB         | 6         | 6      | 0.42%   |
| WDC WD10EARS-00Y5B1 1TB             | 6         | 7      | 0.42%   |
| WDC WD10EALX-009BA0 1TB             | 6         | 6      | 0.42%   |
| Toshiba DT01ACA050 500GB            | 6         | 7      | 0.42%   |
| Seagate ST2000DM001-1CH164 2TB      | 6         | 6      | 0.42%   |
| SanDisk SSD PLUS 480GB              | 6         | 6      | 0.42%   |
| Hitachi HTS545050B9A300 500GB       | 6         | 6      | 0.42%   |
| Hitachi HDS721050CLA362 500GB       | 6         | 7      | 0.42%   |
| HGST HTS725050A7E630 500GB          | 6         | 6      | 0.42%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 5         | 5      | 0.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 366       | 412    | 26.6%   |
| WDC                 | 290       | 318    | 21.08%  |
| Hitachi             | 147       | 156    | 10.68%  |
| Toshiba             | 120       | 123    | 8.72%   |
| Samsung Electronics | 106       | 117    | 7.7%    |
| HGST                | 71        | 75     | 5.16%   |
| SanDisk             | 48        | 48     | 3.49%   |
| Kingston            | 29        | 30     | 2.11%   |
| Maxtor              | 25        | 26     | 1.82%   |
| Crucial             | 25        | 26     | 1.82%   |
| A-DATA Technology   | 17        | 18     | 1.24%   |
| Micron Technology   | 13        | 13     | 0.94%   |
| Intel               | 12        | 12     | 0.87%   |
| Fujitsu             | 12        | 12     | 0.87%   |
| SK hynix            | 9         | 10     | 0.65%   |
| China               | 9         | 10     | 0.65%   |
| Apple               | 7         | 7      | 0.51%   |
| LITEON              | 5         | 5      | 0.36%   |
| GOODRAM             | 5         | 5      | 0.36%   |
| ASMT                | 5         | 6      | 0.36%   |
| OCZ                 | 4         | 4      | 0.29%   |
| IBM/Hitachi         | 4         | 5      | 0.29%   |
| Hewlett-Packard     | 3         | 4      | 0.22%   |
| Corsair             | 3         | 4      | 0.22%   |
| Transcend           | 2         | 2      | 0.15%   |
| SPCC                | 2         | 2      | 0.15%   |
| PNY                 | 2         | 3      | 0.15%   |
| Patriot             | 2         | 2      | 0.15%   |
| KingSpec            | 2         | 2      | 0.15%   |
| HP Phison           | 2         | 2      | 0.15%   |
| ASMedia             | 2         | 2      | 0.15%   |
| Unknown             | 2         | 2      | 0.15%   |
| WDC WDS2            | 1         | 1      | 0.07%   |
| WD MediaMax         | 1         | 1      | 0.07%   |
| Vaseky              | 1         | 1      | 0.07%   |
| USB3.0              | 1         | 1      | 0.07%   |
| TO Exter            | 1         | 1      | 0.07%   |
| TEXTORM             | 1         | 1      | 0.07%   |
| TCSUNBOW            | 1         | 1      | 0.07%   |
| RSH-339             | 1         | 1      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 366       | 412    | 32.74%  |
| WDC                 | 275       | 300    | 24.6%   |
| Hitachi             | 147       | 156    | 13.15%  |
| Toshiba             | 117       | 120    | 10.47%  |
| Samsung Electronics | 86        | 95     | 7.69%   |
| HGST                | 71        | 75     | 6.35%   |
| Maxtor              | 25        | 26     | 2.24%   |
| Fujitsu             | 12        | 12     | 1.07%   |
| IBM/Hitachi         | 4         | 5      | 0.36%   |
| Apple               | 3         | 3      | 0.27%   |
| WD MediaMax         | 1         | 1      | 0.09%   |
| USB3.0              | 1         | 1      | 0.09%   |
| TO Exter            | 1         | 1      | 0.09%   |
| RSH-339             | 1         | 1      | 0.09%   |
| Magnetic Data       | 1         | 1      | 0.09%   |
| Initio              | 1         | 1      | 0.09%   |
| HPE                 | 1         | 1      | 0.09%   |
| Hewlett-Packard     | 1         | 2      | 0.09%   |
| ExcelStor           | 1         | 1      | 0.09%   |
| ASMT                | 1         | 2      | 0.09%   |
| ASMedia             | 1         | 1      | 0.09%   |
| Unknown             | 1         | 1      | 0.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1028      | 1218   | 80.06%  |
| SSD     | 241       | 254    | 18.77%  |
| NVMe    | 14        | 16     | 1.09%   |
| Unknown | 1         | 1      | 0.08%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HD103SJ 1TB                  | 3         | 3      | 6.98%   |
| Apple HDD HTS541010A9E662 1TB                    | 3         | 3      | 6.98%   |
| WDC WD3200BEVT-11ZCT0 320GB                      | 2         | 2      | 4.65%   |
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 4.65%   |
| WDC WD5000BEVT-22ZAT0 500GB                      | 1         | 1      | 2.33%   |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 2.33%   |
| WDC WD3200BUCT-63TWBY0 320GB                     | 1         | 1      | 2.33%   |
| WDC WD3200BEKT-60KA9T0 320GB                     | 1         | 1      | 2.33%   |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1         | 1      | 2.33%   |
| WDC WD2500BEVT-60ZCT1 250GB                      | 1         | 1      | 2.33%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 1      | 2.33%   |
| WDC WD1600YS-23SHB0 160GB                        | 1         | 1      | 2.33%   |
| WDC WD1600BEVT-75A23T0 160GB                     | 1         | 1      | 2.33%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 2.33%   |
| Toshiba MQ01ABD050 500GB                         | 1         | 1      | 2.33%   |
| Toshiba MK3265GSXN 320GB                         | 1         | 1      | 2.33%   |
| Toshiba MK3259GSXP 320GB                         | 1         | 1      | 2.33%   |
| Toshiba MK3256GSY 320GB                          | 1         | 1      | 2.33%   |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 2.33%   |
| Seagate STM31000528AS 1TB                        | 1         | 1      | 2.33%   |
| Seagate ST980811AS 80GB                          | 1         | 1      | 2.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.33%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 2.33%   |
| Seagate ST3160215A 160GB                         | 1         | 1      | 2.33%   |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 2.33%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 2.33%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 2.33%   |
| Samsung Electronics HD502IJ 500GB                | 1         | 1      | 2.33%   |
| Samsung Electronics HD103UJ 1TB                  | 1         | 1      | 2.33%   |
| Intel SSDSA2BW160G3 160GB                        | 1         | 1      | 2.33%   |
| Hitachi HTS725050A7E630 500GB                    | 1         | 1      | 2.33%   |
| Hitachi HTS545050B9SA00 500GB                    | 1         | 1      | 2.33%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 2.33%   |
| Hitachi HDS721010DLE630 1TB                      | 1         | 1      | 2.33%   |
| Hitachi HDP725050GLA360 500GB                    | 1         | 1      | 2.33%   |
| GOODRAM SSDPR-PX500-256-80 256GB                 | 1         | 1      | 2.33%   |
| Apple HDD HTS545050A7E362 500GB                  | 1         | 1      | 2.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 12     | 27.91%  |
| Samsung Electronics | 8         | 8      | 18.6%   |
| Toshiba             | 7         | 7      | 16.28%  |
| Seagate             | 5         | 5      | 11.63%  |
| Hitachi             | 5         | 5      | 11.63%  |
| Apple               | 4         | 4      | 9.3%    |
| Intel               | 1         | 1      | 2.33%   |
| GOODRAM             | 1         | 1      | 2.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3639      | 5760   | 67.65%  |
| Malfunc  | 1257      | 1489   | 23.37%  |
| Detected | 441       | 520    | 8.2%    |
| Failed   | 42        | 43     | 0.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3261      | 58.19%  |
| AMD                              | 984       | 17.56%  |
| Samsung Electronics              | 277       | 4.94%   |
| SanDisk                          | 142       | 2.53%   |
| Nvidia                           | 100       | 1.78%   |
| JMicron Technology               | 96        | 1.71%   |
| SK hynix                         | 94        | 1.68%   |
| ASMedia Technology               | 85        | 1.52%   |
| Marvell Technology Group         | 76        | 1.36%   |
| Kingston Technology Company      | 71        | 1.27%   |
| Phison Electronics               | 66        | 1.18%   |
| Silicon Motion                   | 49        | 0.87%   |
| Micron/Crucial Technology        | 46        | 0.82%   |
| KIOXIA                           | 35        | 0.62%   |
| ADATA Technology                 | 30        | 0.54%   |
| Solid State Storage Technology   | 24        | 0.43%   |
| VIA Technologies                 | 23        | 0.41%   |
| Micron Technology                | 23        | 0.41%   |
| Toshiba America Info Systems     | 21        | 0.37%   |
| Realtek Semiconductor            | 19        | 0.34%   |
| Broadcom / LSI                   | 13        | 0.23%   |
| Union Memory (Shenzhen)          | 9         | 0.16%   |
| Seagate Technology               | 8         | 0.14%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.11%   |
| Lite-On Technology               | 6         | 0.11%   |
| Integrated Technology Express    | 6         | 0.11%   |
| Silicon Integrated Systems [SiS] | 5         | 0.09%   |
| Shenzhen Longsys Electronics     | 4         | 0.07%   |
| LSI Logic / Symbios Logic        | 4         | 0.07%   |
| Adaptec                          | 4         | 0.07%   |
| Silicon Image                    | 3         | 0.05%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| Promise Technology               | 2         | 0.04%   |
| Hewlett-Packard                  | 2         | 0.04%   |
| Apple                            | 2         | 0.04%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 572       | 8.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 257       | 3.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 250       | 3.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 194       | 2.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 169       | 2.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 156       | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 150       | 2.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 138       | 2.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 134       | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 133       | 2%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 132       | 1.99%   |
| AMD 400 Series Chipset SATA Controller                                                  | 119       | 1.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 118       | 1.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 115       | 1.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 107       | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 107       | 1.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 94        | 1.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 88        | 1.33%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 84        | 1.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 83        | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 83        | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 82        | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 80        | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 79        | 1.19%   |
| AMD 500 Series Chipset SATA Controller                                                  | 77        | 1.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 76        | 1.14%   |
| Intel SATA Controller [RAID mode]                                                       | 73        | 1.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 72        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 72        | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 71        | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 71        | 1.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 70        | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 68        | 1.02%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 66        | 0.99%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 65        | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 44        | 0.66%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 43        | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 41        | 0.62%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 41        | 0.62%   |
| AMD FCH IDE Controller                                                                  | 41        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3600      | 63.09%  |
| NVMe | 903       | 15.83%  |
| IDE  | 893       | 15.65%  |
| RAID | 292       | 5.12%   |
| SAS  | 9         | 0.16%   |
| SCSI | 9         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3484      | 75.15%  |
| AMD    | 1152      | 24.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Silver N6000 @ 1.10GHz          | 54        | 1.16%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 41        | 0.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 35        | 0.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 33        | 0.71%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 33        | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 31        | 0.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 31        | 0.67%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 30        | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 29        | 0.62%   |
| AMD Ryzen 5 3600 6-Core Processor             | 29        | 0.62%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 28        | 0.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 28        | 0.6%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 27        | 0.58%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 26        | 0.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 24        | 0.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 24        | 0.52%   |
| AMD FX-8350 Eight-Core Processor              | 24        | 0.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 23        | 0.5%    |
| Intel Core i3-2120 CPU @ 3.30GHz              | 23        | 0.5%    |
| Intel Core i5-3570K CPU @ 3.40GHz             | 22        | 0.47%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 22        | 0.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 21        | 0.45%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 21        | 0.45%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 21        | 0.45%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 21        | 0.45%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 21        | 0.45%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 21        | 0.45%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 21        | 0.45%   |
| AMD 3020e with Radeon Graphics                | 21        | 0.45%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 20        | 0.43%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 19        | 0.41%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 19        | 0.41%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 19        | 0.41%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 19        | 0.41%   |
| AMD FX-6300 Six-Core Processor                | 19        | 0.41%   |
| Intel Core i7-2677M CPU @ 1.80GHz             | 18        | 0.39%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 18        | 0.39%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 18        | 0.39%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 18        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1087      | 23.43%  |
| Intel Core i3           | 509       | 10.97%  |
| Intel Core i7           | 477       | 10.28%  |
| Intel Celeron           | 337       | 7.26%   |
| Intel Core 2 Duo        | 263       | 5.67%   |
| AMD Ryzen 5             | 208       | 4.48%   |
| Intel Pentium           | 182       | 3.92%   |
| AMD Ryzen 7             | 143       | 3.08%   |
| Other                   | 136       | 2.93%   |
| Intel Pentium Silver    | 102       | 2.2%    |
| AMD FX                  | 100       | 2.16%   |
| Intel Xeon              | 92        | 1.98%   |
| Intel Pentium Dual-Core | 84        | 1.81%   |
| AMD Ryzen 3             | 67        | 1.44%   |
| Intel Core 2 Quad       | 65        | 1.4%    |
| AMD A8                  | 53        | 1.14%   |
| AMD A6                  | 52        | 1.12%   |
| AMD A4                  | 45        | 0.97%   |
| AMD A10                 | 42        | 0.91%   |
| Intel Core 2            | 37        | 0.8%    |
| Intel Atom              | 35        | 0.75%   |
| Intel Pentium Dual      | 34        | 0.73%   |
| AMD Phenom II X4        | 33        | 0.71%   |
| AMD Athlon              | 33        | 0.71%   |
| AMD E1                  | 32        | 0.69%   |
| AMD Ryzen 9             | 31        | 0.67%   |
| AMD Athlon II X2        | 29        | 0.63%   |
| AMD E                   | 28        | 0.6%    |
| AMD Athlon 64 X2        | 24        | 0.52%   |
| Intel Core i9           | 18        | 0.39%   |
| Intel Genuine           | 16        | 0.34%   |
| AMD E2                  | 16        | 0.34%   |
| AMD Ryzen 5 PRO         | 13        | 0.28%   |
| Intel Pentium Gold      | 12        | 0.26%   |
| AMD Sempron             | 12        | 0.26%   |
| AMD Athlon II X4        | 12        | 0.26%   |
| AMD C-60                | 11        | 0.24%   |
| AMD Athlon X4           | 11        | 0.24%   |
| AMD Athlon II X3        | 11        | 0.24%   |
| AMD Phenom II X6        | 10        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2398      | 51.69%  |
| 4      | 1446      | 31.17%  |
| 6      | 378       | 8.15%   |
| 8      | 204       | 4.4%    |
| 1      | 106       | 2.28%   |
| 3      | 43        | 0.93%   |
| 12     | 27        | 0.58%   |
| 16     | 20        | 0.43%   |
| 10     | 10        | 0.22%   |
| 14     | 3         | 0.06%   |
| 128    | 1         | 0.02%   |
| 44     | 1         | 0.02%   |
| 28     | 1         | 0.02%   |
| 20     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4613      | 99.5%   |
| 2      | 23        | 0.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2521      | 54.36%  |
| 1      | 2105      | 45.39%  |
| 8      | 9         | 0.19%   |
| 4      | 3         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4635      | 99.96%  |
| Unknown        | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 402       | 8.65%   |
| 0x306a9    | 385       | 8.28%   |
| 0x306c3    | 315       | 6.78%   |
| 0x1067a    | 288       | 6.19%   |
| Unknown    | 125       | 2.69%   |
| 0x20655    | 119       | 2.56%   |
| 0x506e3    | 110       | 2.37%   |
| 0x906ea    | 108       | 2.32%   |
| 0x40651    | 96        | 2.06%   |
| 0x306d4    | 93        | 2%      |
| 0x406e3    | 92        | 1.98%   |
| 0x806e9    | 86        | 1.85%   |
| 0x6fd      | 81        | 1.74%   |
| 0x08108109 | 80        | 1.72%   |
| 0x806ea    | 76        | 1.63%   |
| 0x706a8    | 74        | 1.59%   |
| 0x906e9    | 73        | 1.57%   |
| 0x906c0    | 73        | 1.57%   |
| 0x08701021 | 72        | 1.55%   |
| 0x30678    | 64        | 1.38%   |
| 0x806ec    | 61        | 1.31%   |
| 0x10676    | 61        | 1.31%   |
| 0xa0655    | 50        | 1.08%   |
| 0x6fb      | 50        | 1.08%   |
| 0x706a1    | 48        | 1.03%   |
| 0x0a50000c | 48        | 1.03%   |
| 0x010000c8 | 48        | 1.03%   |
| 0x06001119 | 47        | 1.01%   |
| 0xa0653    | 42        | 0.9%    |
| 0x20652    | 42        | 0.9%    |
| 0x506c9    | 39        | 0.84%   |
| 0x0800820d | 39        | 0.84%   |
| 0x406c4    | 38        | 0.82%   |
| 0x806c1    | 36        | 0.77%   |
| 0x06006705 | 36        | 0.77%   |
| 0x106e5    | 35        | 0.75%   |
| 0x06003106 | 35        | 0.75%   |
| 0x706e5    | 34        | 0.73%   |
| 0x08600106 | 33        | 0.71%   |
| 0x07030105 | 30        | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 480       | 10.35%  |
| Haswell          | 428       | 9.23%   |
| SandyBridge      | 420       | 9.05%   |
| IvyBridge        | 401       | 8.64%   |
| Penryn           | 359       | 7.74%   |
| Skylake          | 211       | 4.55%   |
| Core             | 191       | 4.12%   |
| Westmere         | 174       | 3.75%   |
| Zen+             | 148       | 3.19%   |
| Silvermont       | 140       | 3.02%   |
| Zen 2            | 139       | 3%      |
| Piledriver       | 138       | 2.97%   |
| K10              | 132       | 2.85%   |
| Goldmont plus    | 122       | 2.63%   |
| CometLake        | 111       | 2.39%   |
| Zen 3            | 107       | 2.31%   |
| Broadwell        | 104       | 2.24%   |
| Zen              | 94        | 2.03%   |
| Tremont          | 73        | 1.57%   |
| Excavator        | 70        | 1.51%   |
| Bobcat           | 60        | 1.29%   |
| Icelake          | 59        | 1.27%   |
| Nehalem          | 52        | 1.12%   |
| K8 Hammer        | 52        | 1.12%   |
| Unknown          | 51        | 1.1%    |
| Puma             | 44        | 0.95%   |
| Steamroller      | 42        | 0.91%   |
| Goldmont         | 40        | 0.86%   |
| TigerLake        | 38        | 0.82%   |
| K10 Llano        | 32        | 0.69%   |
| Jaguar           | 31        | 0.67%   |
| Bonnell          | 28        | 0.6%    |
| Alderlake Hybrid | 20        | 0.43%   |
| NetBurst         | 18        | 0.39%   |
| Bulldozer        | 18        | 0.39%   |
| K8 & K10 hybrid  | 12        | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2596      | 50.58%  |
| Nvidia                           | 1271      | 24.77%  |
| AMD                              | 1242      | 24.2%   |
| Matrox Electronics Systems       | 8         | 0.16%   |
| ASPEED Technology                | 6         | 0.12%   |
| Silicon Integrated Systems [SiS] | 4         | 0.08%   |
| VIA Technologies                 | 3         | 0.06%   |
| Conexant Systems                 | 1         | 0.02%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 330       | 6.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 211       | 4.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 136       | 2.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 121       | 2.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 110       | 2.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 96        | 1.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 96        | 1.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 87        | 1.65%   |
| Intel HD Graphics 620                                                                    | 83        | 1.58%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 81        | 1.54%   |
| Intel HD Graphics 5500                                                                   | 76        | 1.44%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 76        | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 76        | 1.44%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 74        | 1.41%   |
| Intel JasperLake [UHD Graphics]                                                          | 73        | 1.39%   |
| Intel HD Graphics 530                                                                    | 73        | 1.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 63        | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 62        | 1.18%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 61        | 1.16%   |
| Intel UHD Graphics 620                                                                   | 60        | 1.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 59        | 1.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 59        | 1.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 58        | 1.1%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 51        | 0.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 50        | 0.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 49        | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 48        | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 48        | 0.91%   |
| Nvidia GT218 [GeForce 210]                                                               | 47        | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 46        | 0.87%   |
| Intel HD Graphics 630                                                                    | 46        | 0.87%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 46        | 0.87%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 43        | 0.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 39        | 0.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 37        | 0.7%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 32        | 0.61%   |
| Intel HD Graphics 500                                                                    | 31        | 0.59%   |
| AMD Lucienne                                                                             | 31        | 0.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 30        | 0.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 29        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2131      | 45.89%  |
| 1 x AMD                  | 1074      | 23.13%  |
| 1 x Nvidia               | 898       | 19.34%  |
| Intel + Nvidia           | 341       | 7.34%   |
| Intel + AMD              | 79        | 1.7%    |
| 2 x AMD                  | 69        | 1.49%   |
| AMD + Nvidia             | 21        | 0.45%   |
| 2 x Nvidia               | 7         | 0.15%   |
| 1 x Matrox               | 6         | 0.13%   |
| 1 x ASPEED               | 5         | 0.11%   |
| 1 x SiS                  | 4         | 0.09%   |
| 1 x VIA                  | 3         | 0.06%   |
| Nvidia + Matrox          | 2         | 0.04%   |
| 3 x AMD                  | 1         | 0.02%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |
| Intel + Conexant Systems | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4520      | 97.46%  |
| Unknown     | 111       | 2.39%   |
| Proprietary | 7         | 0.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2288      | 49.28%  |
| 0.01-0.5   | 710       | 15.29%  |
| 1.01-2.0   | 609       | 13.12%  |
| 0.51-1.0   | 515       | 11.09%  |
| 3.01-4.0   | 230       | 4.95%   |
| 7.01-8.0   | 150       | 3.23%   |
| 5.01-6.0   | 80        | 1.72%   |
| 2.01-3.0   | 33        | 0.71%   |
| 8.01-16.0  | 23        | 0.5%    |
| 16.01-24.0 | 4         | 0.09%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 629       | 13.59%  |
| AU Optronics            | 504       | 10.89%  |
| LG Display              | 414       | 8.95%   |
| Chimei Innolux          | 338       | 7.3%    |
| BOE                     | 331       | 7.15%   |
| Goldstar                | 271       | 5.86%   |
| Dell                    | 239       | 5.16%   |
| Hewlett-Packard         | 235       | 5.08%   |
| Acer                    | 173       | 3.74%   |
| AOC                     | 154       | 3.33%   |
| Philips                 | 148       | 3.2%    |
| BenQ                    | 103       | 2.23%   |
| Lenovo                  | 91        | 1.97%   |
| Chi Mei Optoelectronics | 84        | 1.82%   |
| Ancor Communications    | 77        | 1.66%   |
| ViewSonic               | 66        | 1.43%   |
| Apple                   | 66        | 1.43%   |
| Iiyama                  | 45        | 0.97%   |
| Eizo                    | 38        | 0.82%   |
| Sony                    | 36        | 0.78%   |
| Sharp                   | 35        | 0.76%   |
| LG Philips              | 31        | 0.67%   |
| InfoVision              | 29        | 0.63%   |
| ASUSTek Computer        | 29        | 0.63%   |
| CPT                     | 24        | 0.52%   |
| Toshiba                 | 23        | 0.5%    |
| NEC Computers           | 20        | 0.43%   |
| HannStar                | 19        | 0.41%   |
| Fujitsu Siemens         | 19        | 0.41%   |
| PANDA                   | 17        | 0.37%   |
| Panasonic               | 14        | 0.3%    |
| Hitachi                 | 11        | 0.24%   |
| Unknown                 | 10        | 0.22%   |
| Sceptre Tech            | 10        | 0.22%   |
| ___                     | 9         | 0.19%   |
| Vestel Elektronik       | 9         | 0.19%   |
| TCL                     | 9         | 0.19%   |
| MSI                     | 9         | 0.19%   |
| Medion                  | 9         | 0.19%   |
| Vizio                   | 8         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                     | 33        | 0.71%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 25        | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 24        | 0.51%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                         | 22        | 0.47%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch           | 20        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 18        | 0.38%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 18        | 0.38%   |
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 18        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 18        | 0.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.36%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 16        | 0.34%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 16        | 0.34%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 15        | 0.32%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 15        | 0.32%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 14        | 0.3%    |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 14        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.28%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 13        | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO7E91 1366x768 256x144mm 11.6-inch            | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 12        | 0.26%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 11        | 0.24%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 11        | 0.24%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                          | 11        | 0.24%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 10        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch | 10        | 0.21%   |
| BOE LCD Monitor BOE0744 1366x768 256x144mm 11.6-inch                     | 10        | 0.21%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 10        | 0.21%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 10        | 0.21%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch       | 9         | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 9         | 0.19%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 9         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1738      | 38.23%  |
| 1366x768 (WXGA)    | 1250      | 27.5%   |
| 1600x900 (HD+)     | 244       | 5.37%   |
| 3840x2160 (4K)     | 242       | 5.32%   |
| 1280x1024 (SXGA)   | 200       | 4.4%    |
| 2560x1440 (QHD)    | 149       | 3.28%   |
| 1440x900 (WXGA+)   | 148       | 3.26%   |
| 1680x1050 (WSXGA+) | 141       | 3.1%    |
| 1280x800 (WXGA)    | 121       | 2.66%   |
| 1920x1200 (WUXGA)  | 90        | 1.98%   |
| 1360x768           | 46        | 1.01%   |
| 3440x1440          | 28        | 0.62%   |
| 2560x1080          | 25        | 0.55%   |
| 1920x540           | 16        | 0.35%   |
| 1024x768 (XGA)     | 16        | 0.35%   |
| 2560x1600          | 14        | 0.31%   |
| 3200x1800 (QHD+)   | 12        | 0.26%   |
| 1600x1200          | 8         | 0.18%   |
| 2288x1287          | 6         | 0.13%   |
| 2160x1440          | 6         | 0.13%   |
| 1280x720 (HD)      | 6         | 0.13%   |
| 1024x600           | 5         | 0.11%   |
| 2880x1800          | 4         | 0.09%   |
| 2736x1824          | 4         | 0.09%   |
| 2048x1152          | 4         | 0.09%   |
| 1920x1280          | 4         | 0.09%   |
| 1280x960           | 4         | 0.09%   |
| 3840x1080          | 2         | 0.04%   |
| 2256x1504          | 2         | 0.04%   |
| 1680x945           | 2         | 0.04%   |
| 1280x768           | 2         | 0.04%   |
| 3840x2400          | 1         | 0.02%   |
| 3840x1600          | 1         | 0.02%   |
| 3840x1200          | 1         | 0.02%   |
| 3456x2160          | 1         | 0.02%   |
| 3200x2000          | 1         | 0.02%   |
| 1400x1050          | 1         | 0.02%   |
| Unknown            | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1048      | 22.62%  |
| 13      | 396       | 8.55%   |
| 23      | 347       | 7.49%   |
| 21      | 346       | 7.47%   |
| 27      | 324       | 6.99%   |
| 17      | 311       | 6.71%   |
| 24      | 309       | 6.67%   |
| 14      | 257       | 5.55%   |
| 19      | 200       | 4.32%   |
| 11      | 145       | 3.13%   |
| 18      | 140       | 3.02%   |
| 31      | 118       | 2.55%   |
| 22      | 105       | 2.27%   |
| 12      | 103       | 2.22%   |
| 20      | 86        | 1.86%   |
| 84      | 46        | 0.99%   |
| 34      | 46        | 0.99%   |
| 32      | 31        | 0.67%   |
| Unknown | 27        | 0.58%   |
| 40      | 26        | 0.56%   |
| 26      | 23        | 0.5%    |
| 72      | 22        | 0.47%   |
| 54      | 22        | 0.47%   |
| 25      | 18        | 0.39%   |
| 16      | 17        | 0.37%   |
| 10      | 14        | 0.3%    |
| 65      | 13        | 0.28%   |
| 52      | 12        | 0.26%   |
| 48      | 8         | 0.17%   |
| 39      | 7         | 0.15%   |
| 33      | 7         | 0.15%   |
| 46      | 6         | 0.13%   |
| 28      | 6         | 0.13%   |
| 74      | 5         | 0.11%   |
| 42      | 5         | 0.11%   |
| 142     | 4         | 0.09%   |
| 37      | 4         | 0.09%   |
| 35      | 4         | 0.09%   |
| 29      | 4         | 0.09%   |
| 55      | 3         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1575      | 34.37%  |
| 501-600        | 946       | 20.65%  |
| 401-500        | 767       | 16.74%  |
| 201-300        | 460       | 10.04%  |
| 351-400        | 365       | 7.97%   |
| 601-700        | 156       | 3.4%    |
| 701-800        | 84        | 1.83%   |
| 1501-2000      | 75        | 1.64%   |
| 1001-1500      | 75        | 1.64%   |
| 801-900        | 42        | 0.92%   |
| Unknown        | 27        | 0.59%   |
| 901-1000       | 6         | 0.13%   |
| More than 2000 | 4         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3539      | 80.01%  |
| 16/10   | 546       | 12.34%  |
| 5/4     | 195       | 4.41%   |
| 21/9    | 50        | 1.13%   |
| 4/3     | 43        | 0.97%   |
| 3/2     | 29        | 0.66%   |
| 6/5     | 6         | 0.14%   |
| 1.00    | 4         | 0.09%   |
| 32/9    | 3         | 0.07%   |
| Unknown | 3         | 0.07%   |
| 1.96    | 2         | 0.05%   |
| 3.20    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1040      | 22.58%  |
| 201-250        | 881       | 19.13%  |
| 81-90          | 485       | 10.53%  |
| 151-200        | 395       | 8.58%   |
| 301-350        | 342       | 7.43%   |
| 141-150        | 210       | 4.56%   |
| 351-500        | 208       | 4.52%   |
| 71-80          | 181       | 3.93%   |
| 121-130        | 179       | 3.89%   |
| 51-60          | 145       | 3.15%   |
| More than 1000 | 142       | 3.08%   |
| 251-300        | 142       | 3.08%   |
| 61-70          | 89        | 1.93%   |
| 501-1000       | 60        | 1.3%    |
| 131-140        | 39        | 0.85%   |
| Unknown        | 27        | 0.59%   |
| 111-120        | 19        | 0.41%   |
| 41-50          | 15        | 0.33%   |
| 91-100         | 6         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1852      | 40.96%  |
| 101-120       | 1450      | 32.07%  |
| 121-160       | 891       | 19.71%  |
| 161-240       | 159       | 3.52%   |
| 1-50          | 119       | 2.63%   |
| Unknown       | 27        | 0.6%    |
| More than 240 | 23        | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4214      | 90.82%  |
| 2     | 345       | 7.44%   |
| 0     | 58        | 1.25%   |
| 3     | 20        | 0.43%   |
| 4     | 2         | 0.04%   |
| 7     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2727      | 40.27%  |
| Intel                             | 1870      | 27.61%  |
| Qualcomm Atheros                  | 891       | 13.16%  |
| Broadcom                          | 350       | 5.17%   |
| Ralink Technology                 | 100       | 1.48%   |
| Ralink                            | 100       | 1.48%   |
| Marvell Technology Group          | 90        | 1.33%   |
| Broadcom Limited                  | 86        | 1.27%   |
| Nvidia                            | 75        | 1.11%   |
| TP-Link                           | 59        | 0.87%   |
| MediaTek                          | 39        | 0.58%   |
| Samsung Electronics               | 38        | 0.56%   |
| Qualcomm Atheros Communications   | 22        | 0.32%   |
| JMicron Technology                | 22        | 0.32%   |
| Huawei Technologies               | 22        | 0.32%   |
| Dell                              | 20        | 0.3%    |
| Ericsson Business Mobile Networks | 18        | 0.27%   |
| ASIX Electronics                  | 18        | 0.27%   |
| D-Link System                     | 17        | 0.25%   |
| NetGear                           | 15        | 0.22%   |
| D-Link                            | 14        | 0.21%   |
| Motorola PCS                      | 13        | 0.19%   |
| Sierra Wireless                   | 11        | 0.16%   |
| VIA Technologies                  | 10        | 0.15%   |
| Aquantia                          | 10        | 0.15%   |
| Hewlett-Packard                   | 9         | 0.13%   |
| Microsoft                         | 7         | 0.1%    |
| Edimax Technology                 | 7         | 0.1%    |
| Belkin Components                 | 7         | 0.1%    |
| ASUSTek Computer                  | 7         | 0.1%    |
| Xiaomi                            | 6         | 0.09%   |
| IMC Networks                      | 6         | 0.09%   |
| DisplayLink                       | 6         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.07%   |
| AVM                               | 5         | 0.07%   |
| OPPO Electronics                  | 4         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.04%   |
| vivo                              | 3         | 0.04%   |
| Spreadtrum Communications         | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1925      | 24.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 363       | 4.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 188       | 2.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 126       | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 125       | 1.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 116       | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 113       | 1.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 109       | 1.39%   |
| Intel Wi-Fi 6 AX200                                               | 106       | 1.35%   |
| Intel Wireless 8265 / 8275                                        | 97        | 1.24%   |
| Intel Wireless 7265                                               | 95        | 1.21%   |
| Intel Ethernet Connection I217-LM                                 | 95        | 1.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 84        | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 76        | 0.97%   |
| Intel Wireless 7260                                               | 75        | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 73        | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 70        | 0.89%   |
| Intel Wireless 3165                                               | 69        | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 64        | 0.82%   |
| Intel I211 Gigabit Network Connection                             | 63        | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 0.79%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 61        | 0.78%   |
| Intel 82579V Gigabit Network Connection                           | 61        | 0.78%   |
| Intel Wireless 8260                                               | 57        | 0.73%   |
| Intel Ethernet Connection (2) I219-V                              | 56        | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 56        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 54        | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 49        | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 49        | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 46        | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 45        | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 40        | 0.51%   |
| Intel Wireless 3160                                               | 40        | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 40        | 0.51%   |
| Ralink MT7601U Wireless Adapter                                   | 39        | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 37        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 36        | 0.46%   |
| Intel Ethernet Connection (7) I219-V                              | 36        | 0.46%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 35        | 0.45%   |
| Nvidia MCP61 Ethernet                                             | 34        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1288      | 38.82%  |
| Qualcomm Atheros                      | 711       | 21.43%  |
| Realtek Semiconductor                 | 640       | 19.29%  |
| Broadcom                              | 211       | 6.36%   |
| Ralink Technology                     | 100       | 3.01%   |
| Ralink                                | 100       | 3.01%   |
| TP-Link                               | 43        | 1.3%    |
| Broadcom Limited                      | 39        | 1.18%   |
| MediaTek                              | 33        | 0.99%   |
| Qualcomm Atheros Communications       | 22        | 0.66%   |
| Dell                                  | 15        | 0.45%   |
| D-Link                                | 14        | 0.42%   |
| NetGear                               | 13        | 0.39%   |
| Sierra Wireless                       | 11        | 0.33%   |
| D-Link System                         | 8         | 0.24%   |
| Microsoft                             | 7         | 0.21%   |
| Edimax Technology                     | 7         | 0.21%   |
| ASUSTek Computer                      | 7         | 0.21%   |
| IMC Networks                          | 6         | 0.18%   |
| Belkin Components                     | 6         | 0.18%   |
| Marvell Technology Group              | 5         | 0.15%   |
| AVM                                   | 5         | 0.15%   |
| Hewlett-Packard                       | 4         | 0.12%   |
| Ericsson Business Mobile Networks     | 3         | 0.09%   |
| Qcom                                  | 2         | 0.06%   |
| Mercucys                              | 2         | 0.06%   |
| Linksys                               | 2         | 0.06%   |
| Gemtek                                | 2         | 0.06%   |
| Chu Yuen Enterprise                   | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| ZyDAS                                 | 1         | 0.03%   |
| TRENDnet                              | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Logitec                               | 1         | 0.03%   |
| Guillemot                             | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 126       | 3.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 125       | 3.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 116       | 3.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 113       | 3.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 109       | 3.28%   |
| Intel Wi-Fi 6 AX200                                            | 106       | 3.19%   |
| Intel Wireless 8265 / 8275                                     | 97        | 2.92%   |
| Intel Wireless 7265                                            | 95        | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 76        | 2.28%   |
| Intel Wireless 7260                                            | 75        | 2.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 73        | 2.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 70        | 2.1%    |
| Intel Wireless 3165                                            | 69        | 2.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 64        | 1.92%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 61        | 1.83%   |
| Intel Wireless 8260                                            | 57        | 1.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 56        | 1.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 49        | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 49        | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 46        | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 45        | 1.35%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 40        | 1.2%    |
| Intel Wireless 3160                                            | 40        | 1.2%    |
| Ralink MT7601U Wireless Adapter                                | 39        | 1.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 35        | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 32        | 0.96%   |
| Intel WiFi Link 5100                                           | 32        | 0.96%   |
| Intel Centrino Wireless-N 2230                                 | 31        | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 31        | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 30        | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 30        | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 29        | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 28        | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 28        | 0.84%   |
| Intel Centrino Ultimate-N 6300                                 | 28        | 0.84%   |
| Intel Wireless-AC 9260                                         | 27        | 0.81%   |
| Intel Wi-Fi 6 AX201                                            | 26        | 0.78%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 25        | 0.75%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 24        | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 23        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2479      | 56.77%  |
| Intel                             | 1006      | 23.04%  |
| Qualcomm Atheros                  | 266       | 6.09%   |
| Broadcom                          | 190       | 4.35%   |
| Marvell Technology Group          | 85        | 1.95%   |
| Nvidia                            | 75        | 1.72%   |
| Broadcom Limited                  | 48        | 1.1%    |
| Samsung Electronics               | 36        | 0.82%   |
| JMicron Technology                | 22        | 0.5%    |
| ASIX Electronics                  | 18        | 0.41%   |
| TP-Link                           | 16        | 0.37%   |
| Huawei Technologies               | 16        | 0.37%   |
| VIA Technologies                  | 10        | 0.23%   |
| Aquantia                          | 10        | 0.23%   |
| D-Link System                     | 9         | 0.21%   |
| Motorola PCS                      | 8         | 0.18%   |
| Xiaomi                            | 6         | 0.14%   |
| MediaTek                          | 6         | 0.14%   |
| DisplayLink                       | 6         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.11%   |
| OPPO Electronics                  | 4         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.09%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.07%   |
| vivo                              | 3         | 0.07%   |
| Spreadtrum Communications         | 3         | 0.07%   |
| HTC (High Tech Computer)          | 3         | 0.07%   |
| Hewlett-Packard                   | 3         | 0.07%   |
| Google                            | 3         | 0.07%   |
| 3Com                              | 3         | 0.07%   |
| T & A Mobile Phones               | 2         | 0.05%   |
| Qualcomm                          | 2         | 0.05%   |
| NetGear                           | 2         | 0.05%   |
| Mellanox Technologies             | 2         | 0.05%   |
| ICS Advent                        | 2         | 0.05%   |
| Sundance Technology Inc / IC Plus | 1         | 0.02%   |
| Netchip Technology                | 1         | 0.02%   |
| Microchip Technology              | 1         | 0.02%   |
| Lenovo                            | 1         | 0.02%   |
| Emulex                            | 1         | 0.02%   |
| Dell                              | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1925      | 43.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 363       | 8.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 188       | 4.22%   |
| Intel Ethernet Connection I217-LM                                 | 95        | 2.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 84        | 1.88%   |
| Intel I211 Gigabit Network Connection                             | 63        | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 1.39%   |
| Intel 82579V Gigabit Network Connection                           | 61        | 1.37%   |
| Intel Ethernet Connection (2) I219-V                              | 56        | 1.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 54        | 1.21%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 40        | 0.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 37        | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 36        | 0.81%   |
| Intel Ethernet Connection (7) I219-V                              | 36        | 0.81%   |
| Nvidia MCP61 Ethernet                                             | 34        | 0.76%   |
| Intel Ethernet Controller I225-V                                  | 34        | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 33        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 32        | 0.72%   |
| Intel Ethernet Connection I218-LM                                 | 28        | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 27        | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 26        | 0.58%   |
| Intel 82577LM Gigabit Network Connection                          | 26        | 0.58%   |
| Intel Ethernet Connection I217-V                                  | 25        | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 23        | 0.52%   |
| Intel 82567LM Gigabit Network Connection                          | 22        | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 22        | 0.49%   |
| Intel Ethernet Connection I219-LM                                 | 21        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 20        | 0.45%   |
| Intel 82574L Gigabit Network Connection                           | 19        | 0.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 18        | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 18        | 0.4%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 16        | 0.36%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 16        | 0.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 0.36%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 15        | 0.34%   |
| Intel Ethernet Connection (2) I218-V                              | 15        | 0.34%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 15        | 0.34%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 14        | 0.31%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 14        | 0.31%   |
| Nvidia MCP79 Ethernet                                             | 14        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4176      | 56.38%  |
| WiFi     | 3189      | 43.05%  |
| Modem    | 33        | 0.45%   |
| Unknown  | 9         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2549      | 55.94%  |
| WiFi     | 2008      | 44.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2426      | 52.3%   |
| 1     | 2092      | 45.1%   |
| 3     | 69        | 1.49%   |
| 0     | 40        | 0.86%   |
| 4     | 9         | 0.19%   |
| 5     | 2         | 0.04%   |
| 10    | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3291      | 70.65%  |
| Yes  | 1367      | 29.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 961       | 40.95%  |
| Realtek Semiconductor           | 246       | 10.48%  |
| Qualcomm Atheros Communications | 216       | 9.2%    |
| Cambridge Silicon Radio         | 155       | 6.6%    |
| Broadcom                        | 149       | 6.35%   |
| Lite-On Technology              | 106       | 4.52%   |
| IMC Networks                    | 106       | 4.52%   |
| Apple                           | 78        | 3.32%   |
| Foxconn / Hon Hai               | 71        | 3.03%   |
| Dell                            | 46        | 1.96%   |
| Toshiba                         | 38        | 1.62%   |
| ASUSTek Computer                | 35        | 1.49%   |
| Ralink                          | 30        | 1.28%   |
| Hewlett-Packard                 | 30        | 1.28%   |
| Realtek                         | 10        | 0.43%   |
| Alps Electric                   | 9         | 0.38%   |
| MediaTek                        | 8         | 0.34%   |
| Ralink Technology               | 7         | 0.3%    |
| Marvell Semiconductor           | 5         | 0.21%   |
| Fujitsu                         | 5         | 0.21%   |
| Foxconn International           | 4         | 0.17%   |
| Edimax Technology               | 4         | 0.17%   |
| Askey Computer                  | 4         | 0.17%   |
| TP-Link                         | 3         | 0.13%   |
| Dynex                           | 3         | 0.13%   |
| Unknown                         | 3         | 0.13%   |
| Integrated System Solution      | 2         | 0.09%   |
| Chicony Electronics             | 2         | 0.09%   |
| Belkin Components               | 2         | 0.09%   |
| Accel Semiconductor             | 2         | 0.09%   |
| USI                             | 1         | 0.04%   |
| Taiyo Yuden                     | 1         | 0.04%   |
| Smart Modular Technologies      | 1         | 0.04%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Primax Electronics              | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 436       | 18.58%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 155       | 6.6%    |
| Realtek Bluetooth Radio                                                             | 137       | 5.84%   |
| Intel AX201 Bluetooth                                                               | 133       | 5.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 127       | 5.41%   |
| Intel AX200 Bluetooth                                                               | 102       | 4.35%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 84        | 3.58%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 74        | 3.15%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 53        | 2.26%   |
| IMC Networks Bluetooth Radio                                                        | 43        | 1.83%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 42        | 1.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 40        | 1.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 37        | 1.58%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 37        | 1.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 36        | 1.53%   |
| IMC Networks Bluetooth Device                                                       | 31        | 1.32%   |
| Ralink RT3290 Bluetooth                                                             | 30        | 1.28%   |
| Lite-On Bluetooth Device                                                            | 30        | 1.28%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 29        | 1.24%   |
| Apple Bluetooth Host Controller                                                     | 28        | 1.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 26        | 1.11%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 26        | 1.11%   |
| Dell DW375 Bluetooth Module                                                         | 24        | 1.02%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 22        | 0.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 22        | 0.94%   |
| Apple Bluetooth USB Host Controller                                                 | 22        | 0.94%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 20        | 0.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 20        | 0.85%   |
| Intel AX210 Bluetooth                                                               | 18        | 0.77%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 18        | 0.77%   |
| Realtek 802.11ac WLAN Adapter                                                       | 17        | 0.72%   |
| Toshiba RT Bluetooth Radio                                                          | 12        | 0.51%   |
| Realtek RTL8723B Bluetooth                                                          | 12        | 0.51%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 12        | 0.51%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 12        | 0.51%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 12        | 0.51%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 11        | 0.47%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 11        | 0.47%   |
| IMC Networks Wireless_Device                                                        | 10        | 0.43%   |
| Broadcom BCM2045 Bluetooth                                                          | 10        | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3383      | 54.92%  |
| AMD                                          | 1370      | 22.24%  |
| Nvidia                                       | 998       | 16.2%   |
| C-Media Electronics                          | 89        | 1.44%   |
| Creative Labs                                | 52        | 0.84%   |
| Logitech                                     | 37        | 0.6%    |
| Texas Instruments                            | 21        | 0.34%   |
| Creative Technology                          | 16        | 0.26%   |
| JMTek                                        | 15        | 0.24%   |
| Generalplus Technology                       | 13        | 0.21%   |
| ASUSTek Computer                             | 11        | 0.18%   |
| Plantronics                                  | 8         | 0.13%   |
| VIA Technologies                             | 7         | 0.11%   |
| GN Netcom                                    | 7         | 0.11%   |
| XMOS                                         | 5         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.08%   |
| Realtek Semiconductor                        | 5         | 0.08%   |
| Tenx Technology                              | 4         | 0.06%   |
| Samson Technologies                          | 4         | 0.06%   |
| Kingston Technology                          | 4         | 0.06%   |
| Focusrite-Novation                           | 4         | 0.06%   |
| Blue Microphones                             | 4         | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 3         | 0.05%   |
| SteelSeries ApS                              | 3         | 0.05%   |
| Sony                                         | 3         | 0.05%   |
| Razer USA                                    | 3         | 0.05%   |
| Lenovo                                       | 3         | 0.05%   |
| KTMicro                                      | 3         | 0.05%   |
| Hewlett-Packard                              | 3         | 0.05%   |
| Corsair                                      | 3         | 0.05%   |
| BEHRINGER International                      | 3         | 0.05%   |
| Apple                                        | 3         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.03%   |
| Trust                                        | 2         | 0.03%   |
| ROCCAT                                       | 2         | 0.03%   |
| QinHeng Electronics                          | 2         | 0.03%   |
| PreSonus Audio Electronics                   | 2         | 0.03%   |
| No brand                                     | 2         | 0.03%   |
| Micro Star International                     | 2         | 0.03%   |
| Medeli Electronics                           | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 407       | 5.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 387       | 5.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 317       | 4.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 280       | 3.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 259       | 3.5%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 249       | 3.37%   |
| AMD FCH Azalia Controller                                                                         | 229       | 3.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 223       | 3.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 194       | 2.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 183       | 2.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 158       | 2.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 154       | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 139       | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 131       | 1.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 121       | 1.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 117       | 1.58%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 114       | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 112       | 1.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 107       | 1.45%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 99        | 1.34%   |
| Intel 8 Series HD Audio Controller                                                                | 98        | 1.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 97        | 1.31%   |
| Intel Broadwell-U Audio Controller                                                                | 97        | 1.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 93        | 1.26%   |
| Nvidia High Definition Audio Controller                                                           | 88        | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 87        | 1.18%   |
| AMD Kabini HDMI/DP Audio                                                                          | 87        | 1.18%   |
| Intel 200 Series PCH HD Audio                                                                     | 86        | 1.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 78        | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 76        | 1.03%   |
| Intel Jasper Lake HD Audio                                                                        | 73        | 0.99%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 68        | 0.92%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 66        | 0.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 65        | 0.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 64        | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 64        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 58        | 0.78%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 52        | 0.7%    |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 50        | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 49        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1025      | 18.51%  |
| SK hynix            | 864       | 15.6%   |
| Unknown             | 713       | 12.87%  |
| Kingston            | 700       | 12.64%  |
| Micron Technology   | 454       | 8.2%    |
| Crucial             | 290       | 5.24%   |
| Corsair             | 223       | 4.03%   |
| G.Skill             | 175       | 3.16%   |
| A-DATA Technology   | 133       | 2.4%    |
| Elpida              | 109       | 1.97%   |
| Ramaxel Technology  | 108       | 1.95%   |
| Nanya Technology    | 84        | 1.52%   |
| Unknown             | 71        | 1.28%   |
| Smart               | 70        | 1.26%   |
| Unknown (ABCD)      | 48        | 0.87%   |
| Patriot             | 48        | 0.87%   |
| Team                | 41        | 0.74%   |
| GOODRAM             | 26        | 0.47%   |
| Transcend           | 24        | 0.43%   |
| Teikon              | 21        | 0.38%   |
| AMD                 | 21        | 0.38%   |
| Silicon Power       | 14        | 0.25%   |
| Apacer              | 13        | 0.23%   |
| ASint Technology    | 12        | 0.22%   |
| Qimonda             | 11        | 0.2%    |
| CSX                 | 11        | 0.2%    |
| Kingmax             | 10        | 0.18%   |
| GeIL                | 9         | 0.16%   |
| Unifosa             | 8         | 0.14%   |
| PNY                 | 8         | 0.14%   |
| Avant               | 8         | 0.14%   |
| Smart Brazil        | 7         | 0.13%   |
| High Bridge         | 7         | 0.13%   |
| Goldkey             | 7         | 0.13%   |
| Toshiba             | 6         | 0.11%   |
| Super Talent        | 5         | 0.09%   |
| Sesame              | 5         | 0.09%   |
| Multilaser          | 5         | 0.09%   |
| 48spaces            | 5         | 0.09%   |
| Timetec             | 4         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 71        | 1.18%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 53        | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 53        | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 52        | 0.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 52        | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 51        | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 48        | 0.8%    |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 44        | 0.73%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 41        | 0.68%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 38        | 0.63%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 36        | 0.6%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 36        | 0.6%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 36        | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 35        | 0.58%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 35        | 0.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 34        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 33        | 0.55%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 27        | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 26        | 0.43%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 23        | 0.38%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 23        | 0.38%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 23        | 0.38%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 23        | 0.38%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 22        | 0.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.37%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 21        | 0.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.35%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 21        | 0.35%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 20        | 0.33%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 20        | 0.33%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 20        | 0.33%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 20        | 0.33%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 19        | 0.32%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 18        | 0.3%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 18        | 0.3%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 18        | 0.3%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.3%    |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s                         | 18        | 0.3%    |
| Micron RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s             | 18        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 2123      | 45.23%  |
| DDR4    | 1532      | 32.64%  |
| DDR2    | 364       | 7.75%   |
| SDRAM   | 229       | 4.88%   |
| Unknown | 206       | 4.39%   |
| LPDDR4  | 144       | 3.07%   |
| DDR     | 40        | 0.85%   |
| LPDDR3  | 34        | 0.72%   |
| DRAM    | 14        | 0.3%    |
| DDR5    | 7         | 0.15%   |
| LPDDR5  | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2415      | 52.33%  |
| DIMM         | 2026      | 43.9%   |
| Row Of Chips | 147       | 3.19%   |
| Chip         | 14        | 0.3%    |
| Unknown      | 6         | 0.13%   |
| FB-DIMM      | 4         | 0.09%   |
| RIMM         | 3         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 1850      | 35.26%  |
| 8192  | 1654      | 31.52%  |
| 2048  | 1052      | 20.05%  |
| 16384 | 346       | 6.59%   |
| 1024  | 230       | 4.38%   |
| 32768 | 87        | 1.66%   |
| 512   | 27        | 0.51%   |
| 65536 | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1354      | 25.93%  |
| 1333    | 541       | 10.36%  |
| 2667    | 472       | 9.04%   |
| 3200    | 405       | 7.76%   |
| 2400    | 351       | 6.72%   |
| 1334    | 237       | 4.54%   |
| 800     | 197       | 3.77%   |
| 667     | 186       | 3.56%   |
| 2133    | 173       | 3.31%   |
| Unknown | 150       | 2.87%   |
| 3600    | 112       | 2.14%   |
| 1067    | 103       | 1.97%   |
| 1867    | 96        | 1.84%   |
| 1866    | 62        | 1.19%   |
| 4267    | 61        | 1.17%   |
| 2666    | 54        | 1.03%   |
| 1066    | 54        | 1.03%   |
| 4199    | 45        | 0.86%   |
| 2048    | 44        | 0.84%   |
| 3400    | 38        | 0.73%   |
| 3266    | 38        | 0.73%   |
| 533     | 36        | 0.69%   |
| 1800    | 35        | 0.67%   |
| 3000    | 32        | 0.61%   |
| 2933    | 27        | 0.52%   |
| 975     | 27        | 0.52%   |
| 3733    | 25        | 0.48%   |
| 400     | 24        | 0.46%   |
| 3866    | 17        | 0.33%   |
| 3466    | 14        | 0.27%   |
| 333     | 13        | 0.25%   |
| 8400    | 12        | 0.23%   |
| 3666    | 11        | 0.21%   |
| 2800    | 11        | 0.21%   |
| 3800    | 10        | 0.19%   |
| 1639    | 10        | 0.19%   |
| 4266    | 9         | 0.17%   |
| 2000    | 9         | 0.17%   |
| 49926   | 8         | 0.15%   |
| 3066    | 7         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 66        | 39.05%  |
| Brother Industries    | 36        | 21.3%   |
| Canon                 | 26        | 15.38%  |
| Samsung Electronics   | 13        | 7.69%   |
| Seiko Epson           | 11        | 6.51%   |
| Lexmark International | 6         | 3.55%   |
| Xerox                 | 2         | 1.18%   |
| Kyocera               | 2         | 1.18%   |
| Zebra                 | 1         | 0.59%   |
| Ricoh                 | 1         | 0.59%   |
| QinHeng Electronics   | 1         | 0.59%   |
| Prolific Technology   | 1         | 0.59%   |
| NXP Semiconductors    | 1         | 0.59%   |
| Dymo-CoStar           | 1         | 0.59%   |
| Citizen               | 1         | 0.59%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Brother DCP-7055W                            | 4         | 2.37%   |
| Samsung M2070 Series                         | 3         | 1.78%   |
| HP LaserJet 1200                             | 3         | 1.78%   |
| HP LaserJet 1020                             | 3         | 1.78%   |
| HP LaserJet 1018                             | 3         | 1.78%   |
| HP LaserJet 1010                             | 3         | 1.78%   |
| HP ENVY 4520 series                          | 3         | 1.78%   |
| HP DeskJet 2700 series                       | 3         | 1.78%   |
| Seiko Epson ET-4760 Series                   | 2         | 1.18%   |
| Samsung SCX-3400 Series                      | 2         | 1.18%   |
| Samsung M2020 Series                         | 2         | 1.18%   |
| Samsung CLP-310 Color Laser Printer          | 2         | 1.18%   |
| HP OfficeJet Pro 7740 series                 | 2         | 1.18%   |
| HP LaserJet P1005                            | 2         | 1.18%   |
| HP Ink Tank Wireless 410 series              | 2         | 1.18%   |
| HP ENVY 4500 series                          | 2         | 1.18%   |
| HP DeskJet 5550                              | 2         | 1.18%   |
| HP DeskJet 2620 All-in-One Printer           | 2         | 1.18%   |
| HP Deskjet 1050 J410                         | 2         | 1.18%   |
| Canon TS5100 series                          | 2         | 1.18%   |
| Canon PIXMA MG3600 Series                    | 2         | 1.18%   |
| Canon iP7200 series                          | 2         | 1.18%   |
| Brother MFC-L2710DW series                   | 2         | 1.18%   |
| Brother MFC-J470DW                           | 2         | 1.18%   |
| Brother DCP-T310                             | 2         | 1.18%   |
| Zebra LP2824                                 | 1         | 0.59%   |
| Xerox Phaser 6510                            | 1         | 0.59%   |
| Xerox Phaser 6010N                           | 1         | 0.59%   |
| Seiko Epson XP-2100 Series                   | 1         | 0.59%   |
| Seiko Epson WF-2510 Series                   | 1         | 0.59%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.59%   |
| Seiko Epson L6160 Series                     | 1         | 0.59%   |
| Seiko Epson L365 Series                      | 1         | 0.59%   |
| Seiko Epson L355 Series                      | 1         | 0.59%   |
| Seiko Epson L3210 Series                     | 1         | 0.59%   |
| Seiko Epson L3150 Series                     | 1         | 0.59%   |
| Seiko Epson L120 Series                      | 1         | 0.59%   |
| Samsung ML-2850 Series                       | 1         | 0.59%   |
| Samsung ML-1640 Series Laser Printer         | 1         | 0.59%   |
| Samsung M267x 287x Series                    | 1         | 0.59%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 16        | 72.73%  |
| Seiko Epson     | 3         | 13.64%  |
| Mustek Systems  | 2         | 9.09%   |
| Hewlett-Packard | 1         | 4.55%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                  | 4         | 18.18%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2         | 9.09%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 9.09%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 9.09%   |
| Canon CanoScan LiDE 120                                  | 2         | 9.09%   |
| Canon CanoScan LiDE 100                                  | 2         | 9.09%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 4.55%   |
| Mustek Systems SNAPSCAN e22                              | 1         | 4.55%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 4.55%   |
| HP ScanJet 2400c                                         | 1         | 4.55%   |
| Canon CanoScan LiDE 600F                                 | 1         | 4.55%   |
| Canon CanoScan LIDE 25                                   | 1         | 4.55%   |
| Canon CanoScan LiDE 210                                  | 1         | 4.55%   |
| Canon CanoScan 5200F                                     | 1         | 4.55%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 516       | 21.38%  |
| Realtek Semiconductor                  | 267       | 11.06%  |
| Microdia                               | 259       | 10.73%  |
| IMC Networks                           | 140       | 5.8%    |
| Sunplus Innovation Technology          | 135       | 5.59%   |
| Logitech                               | 120       | 4.97%   |
| Suyin                                  | 103       | 4.27%   |
| Bison Electronics                      | 101       | 4.18%   |
| Quanta                                 | 93        | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 91        | 3.77%   |
| Syntek                                 | 66        | 2.73%   |
| Apple                                  | 61        | 2.53%   |
| Lite-On Technology                     | 48        | 1.99%   |
| Silicon Motion                         | 45        | 1.86%   |
| Alcor Micro                            | 38        | 1.57%   |
| Ricoh                                  | 36        | 1.49%   |
| Acer                                   | 28        | 1.16%   |
| Microsoft                              | 23        | 0.95%   |
| Importek                               | 20        | 0.83%   |
| ALi                                    | 20        | 0.83%   |
| Lenovo                                 | 17        | 0.7%    |
| Z-Star Microelectronics                | 16        | 0.66%   |
| Generalplus Technology                 | 14        | 0.58%   |
| Luxvisions Innotech Limited            | 13        | 0.54%   |
| Sonix Technology                       | 11        | 0.46%   |
| Samsung Electronics                    | 11        | 0.46%   |
| Primax Electronics                     | 11        | 0.46%   |
| KYE Systems (Mouse Systems)            | 9         | 0.37%   |
| Cubeternet                             | 7         | 0.29%   |
| Aveo Technology                        | 7         | 0.29%   |
| Sunplus Technology                     | 5         | 0.21%   |
| Hewlett-Packard                        | 5         | 0.21%   |
| GEMBIRD                                | 5         | 0.21%   |
| DigiTech                               | 5         | 0.21%   |
| Trust                                  | 4         | 0.17%   |
| OmniVision Technologies                | 4         | 0.17%   |
| ARC International                      | 4         | 0.17%   |
| Unknown                                | 3         | 0.12%   |
| Jieli Technology                       | 3         | 0.12%   |
| Creative Technology                    | 3         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 101       | 4.12%   |
| Chicony Integrated Camera                               | 71        | 2.89%   |
| Realtek Integrated_Webcam_5M                            | 59        | 2.41%   |
| Sunplus Integrated_Webcam_HD                            | 52        | 2.12%   |
| Realtek Integrated_Webcam_HD                            | 51        | 2.08%   |
| Chicony HD WebCam                                       | 44        | 1.79%   |
| Microdia Integrated Webcam                              | 33        | 1.35%   |
| Syntek Integrated Camera                                | 32        | 1.3%    |
| Logitech Webcam C270                                    | 29        | 1.18%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 27        | 1.1%    |
| Realtek USB Camera                                      | 26        | 1.06%   |
| IMC Networks Integrated Camera                          | 25        | 1.02%   |
| Chicony USB 2.0 Camera                                  | 25        | 1.02%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 23        | 0.94%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 22        | 0.9%    |
| Chicony TOSHIBA Web Camera - HD                         | 22        | 0.9%    |
| Bison Integrated Camera                                 | 22        | 0.9%    |
| Chicony USB2.0 VGA UVC WebCam                           | 21        | 0.86%   |
| Chicony Lenovo EasyCamera                               | 21        | 0.86%   |
| Quanta HD User Facing                                   | 20        | 0.82%   |
| Chicony VGA Webcam                                      | 20        | 0.82%   |
| Apple Built-in iSight                                   | 20        | 0.82%   |
| Apple FaceTime HD Camera (Built-in)                     | 19        | 0.77%   |
| Sunplus HD WebCam                                       | 17        | 0.69%   |
| Microdia USB 2.0 Camera                                 | 17        | 0.69%   |
| Microdia Integrated_Webcam_5M                           | 17        | 0.69%   |
| Chicony HP Truevision HD                                | 17        | 0.69%   |
| Chicony FJ Camera                                       | 17        | 0.69%   |
| Chicony HD User Facing                                  | 16        | 0.65%   |
| Syntek Lenovo EasyCamera                                | 15        | 0.61%   |
| Realtek EasyCamera                                      | 15        | 0.61%   |
| Quanta HP TrueVision HD Camera                          | 15        | 0.61%   |
| Logitech HD Webcam C525                                 | 15        | 0.61%   |
| Chicony USB2.0 HD UVC WebCam                            | 15        | 0.61%   |
| Chicony HP TrueVision HD Camera                         | 15        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 15        | 0.61%   |
| Bison Lenovo EasyCamera                                 | 15        | 0.61%   |
| Quanta HD Webcam                                        | 14        | 0.57%   |
| Lite-On Integrated Camera                               | 14        | 0.57%   |
| Realtek Lenovo EasyCamera                               | 13        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 89        | 39.04%  |
| AuthenTec                  | 32        | 14.04%  |
| Upek                       | 25        | 10.96%  |
| Synaptics                  | 21        | 9.21%   |
| Shenzhen Goodix Technology | 19        | 8.33%   |
| Elan Microelectronics      | 18        | 7.89%   |
| LighTuning Technology      | 11        | 4.82%   |
| STMicroelectronics         | 10        | 4.39%   |
| Samsung Electronics        | 1         | 0.44%   |
| HOLTEK                     | 1         | 0.44%   |
| Focal-systems.Corp         | 1         | 0.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 10.53%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 9.65%   |
| Shenzhen Goodix  Fingerprint Device                                        | 12        | 5.26%   |
| STMicroelectronics Fingerprint Reader                                      | 10        | 4.39%   |
| Elan ELAN:Fingerprint                                                      | 10        | 4.39%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 3.95%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 3.95%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 3.51%   |
| Validity Sensors VFS491                                                    | 8         | 3.51%   |
| Elan ELAN:ARM-M4                                                           | 8         | 3.51%   |
| AuthenTec AES2810                                                          | 7         | 3.07%   |
| AuthenTec AES1600                                                          | 7         | 3.07%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.63%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 2.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 2.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 2.19%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 2.19%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 2.19%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 2.19%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.75%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 1.75%   |
| Synaptics TouchPad                                                         | 4         | 1.75%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.32%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 1.32%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 1.32%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.32%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 1.32%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.88%   |
| Synaptics  WBDI                                                            | 2         | 0.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 0.88%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.44%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.44%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.44%   |
| Synaptics WBDI Device                                                      | 1         | 0.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 86        | 53.09%  |
| O2 Micro              | 19        | 11.73%  |
| Alcor Micro           | 19        | 11.73%  |
| Upek                  | 14        | 8.64%   |
| Lenovo                | 12        | 7.41%   |
| SCM Microsystems      | 3         | 1.85%   |
| Realtek Semiconductor | 3         | 1.85%   |
| Gemalto (was Gemplus) | 3         | 1.85%   |
| BIT4ID                | 2         | 1.23%   |
| Cherry                | 1         | 0.62%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 41        | 25.31%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 24        | 14.81%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 18        | 11.11%  |
| Broadcom 5880                                                                | 15        | 9.26%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 8.64%   |
| Lenovo Integrated Smart Card Reader                                          | 12        | 7.41%   |
| Broadcom 58200                                                               | 5         | 3.09%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.85%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.23%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.23%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.62%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.62%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.62%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.62%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.62%   |
| Bit4id miniLector EVO                                                        | 1         | 0.62%   |
| BIT4ID miniLector AIR NFC v3                                                 | 1         | 0.62%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.62%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3786      | 81.54%  |
| 1     | 741       | 15.96%  |
| 2     | 102       | 2.2%    |
| 3     | 11        | 0.24%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 228       | 23.68%  |
| Graphics card            | 223       | 23.16%  |
| Chipcard                 | 157       | 16.3%   |
| Net/wireless             | 90        | 9.35%   |
| Multimedia controller    | 79        | 8.2%    |
| Bluetooth                | 63        | 6.54%   |
| Storage                  | 29        | 3.01%   |
| Communication controller | 26        | 2.7%    |
| Camera                   | 26        | 2.7%    |
| Unassigned class         | 17        | 1.77%   |
| Network                  | 8         | 0.83%   |
| Sound                    | 4         | 0.42%   |
| Wireless                 | 3         | 0.31%   |
| Flash memory             | 3         | 0.31%   |
| Storage/raid             | 2         | 0.21%   |
| Net/ethernet             | 2         | 0.21%   |
| Card reader              | 2         | 0.21%   |
| Dvb card                 | 1         | 0.1%    |

