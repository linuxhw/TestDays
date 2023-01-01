Parrot 5.0 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Parrot 5.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot_5.0/Desktop/README.md) and [notebooks](/Dist/Parrot_5.0/Notebook/README.md).

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

Total: 168

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b50b1adb0f](https://linux-hardware.org/?probe=b50b1adb0f) | Sep 01, 2022 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| Panasonic     | CF-31JBGNNDM                | Notebook    | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [437387fdc3](https://linux-hardware.org/?probe=437387fdc3) | Aug 10, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [dae7cc7b69](https://linux-hardware.org/?probe=dae7cc7b69) | Aug 08, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a7e9a050ea](https://linux-hardware.org/?probe=a7e9a050ea) | Aug 02, 2022 |
| Dell          | Latitude E6420              | Notebook    | [a6b2ee6088](https://linux-hardware.org/?probe=a6b2ee6088) | Jul 30, 2022 |
| Gateway       | SX2855                      | Desktop     | [a896e3b0f7](https://linux-hardware.org/?probe=a896e3b0f7) | Jul 30, 2022 |
| HP            | 250 G2                      | Notebook    | [5650fd3dd6](https://linux-hardware.org/?probe=5650fd3dd6) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [007eeacf86](https://linux-hardware.org/?probe=007eeacf86) | Jul 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8ce974e537](https://linux-hardware.org/?probe=8ce974e537) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | Notebook    | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| Lenovo        | Z40-70 80E6                 | Notebook    | [e77b84e593](https://linux-hardware.org/?probe=e77b84e593) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [90cf247d2d](https://linux-hardware.org/?probe=90cf247d2d) | Jul 20, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2d31c995c8](https://linux-hardware.org/?probe=2d31c995c8) | Jul 19, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [9e9ca5b39a](https://linux-hardware.org/?probe=9e9ca5b39a) | Jul 19, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [0539efedb2](https://linux-hardware.org/?probe=0539efedb2) | Jul 18, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2c55e11e85](https://linux-hardware.org/?probe=2c55e11e85) | Jul 18, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [0e0a7a2fbc](https://linux-hardware.org/?probe=0e0a7a2fbc) | Jul 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [a7de2e1421](https://linux-hardware.org/?probe=a7de2e1421) | Jul 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [623281f994](https://linux-hardware.org/?probe=623281f994) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [713bd9f4b0](https://linux-hardware.org/?probe=713bd9f4b0) | Jul 14, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [49e71e9dc1](https://linux-hardware.org/?probe=49e71e9dc1) | Jul 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f6c3c6f86e](https://linux-hardware.org/?probe=f6c3c6f86e) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [2ffa772ac9](https://linux-hardware.org/?probe=2ffa772ac9) | Jul 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c680f5f212](https://linux-hardware.org/?probe=c680f5f212) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Lenovo        | ThinkPad L430 2465C32       | Notebook    | [f088c4ae11](https://linux-hardware.org/?probe=f088c4ae11) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [48aa7eac9f](https://linux-hardware.org/?probe=48aa7eac9f) | Jul 09, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [fc35a0726c](https://linux-hardware.org/?probe=fc35a0726c) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| Samsung       | 930QDB                      | Convertible | [e022aed2bc](https://linux-hardware.org/?probe=e022aed2bc) | Jun 28, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8b55dcfd2d](https://linux-hardware.org/?probe=8b55dcfd2d) | Jun 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [d1b8d3ff84](https://linux-hardware.org/?probe=d1b8d3ff84) | Jun 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6348a01f19](https://linux-hardware.org/?probe=6348a01f19) | Jun 23, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [656a452bc6](https://linux-hardware.org/?probe=656a452bc6) | Jun 21, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| Toshiba       | Satellite-L845              | Notebook    | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Unknown       | TB-4000                     | Desktop     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [fd246079ad](https://linux-hardware.org/?probe=fd246079ad) | Jun 04, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [7e3fc5fe06](https://linux-hardware.org/?probe=7e3fc5fe06) | Jun 02, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [02ace99875](https://linux-hardware.org/?probe=02ace99875) | Jun 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [449fc46111](https://linux-hardware.org/?probe=449fc46111) | Jun 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | Notebook    | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell          | Latitude 5400               | Notebook    | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [cb4959b996](https://linux-hardware.org/?probe=cb4959b996) | May 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fb7cb376e9](https://linux-hardware.org/?probe=fb7cb376e9) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| MSI           | GE62 6QE                    | Notebook    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| HP            | 1495                        | Desktop     | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| HP            | 18E7                        | Desktop     | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b3afe4ff08](https://linux-hardware.org/?probe=b3afe4ff08) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [320ae25dbf](https://linux-hardware.org/?probe=320ae25dbf) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | Notebook    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | Notebook    | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                        | Desktop     | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | Notebook    | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | Notebook    | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| Dell          | Latitude XT2                | Notebook    | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Jumper        | EZbook                      | Notebook    | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Unknown       | TB-4000                     | Desktop     | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Jumper        | EZbook                      | Notebook    | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Unknown       | TB-4000                     | Desktop     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| HP            | ProBook 4535s               | Notebook    | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | Notebook    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Unknown       | TB-4000                     | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | Notebook    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Microsoft     | Surface Book                | Tablet      | [327a2ec07f](https://linux-hardware.org/?probe=327a2ec07f) | Jan 22, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [1e5331da8c](https://linux-hardware.org/?probe=1e5331da8c) | Jan 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [bccc675fea](https://linux-hardware.org/?probe=bccc675fea) | Jan 08, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [8f4b5410ad](https://linux-hardware.org/?probe=8f4b5410ad) | Jan 06, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Dell          | Latitude E6410              | Notebook    | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | Notebook    | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | Notebook    | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| HP            | Laptop 15q-dy0xxx           | Notebook    | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.0-12parrot1-amd64   | 51        | 41.8%   |
| 5.14.0-9parrot1-amd64    | 39        | 31.97%  |
| 5.18.0-1parrot1-amd64    | 16        | 13.11%  |
| 5.15.0-15parrot1-amd64   | 7         | 5.74%   |
| 5.14.0-2parrot1-amd64    | 7         | 5.74%   |
| 5.16.0-12parrot1-686-pae | 1         | 0.82%   |
| 5.15.0-5parrot1-amd64    | 1         | 0.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.0  | 52        | 43.33%  |
| 5.14.0  | 44        | 36.67%  |
| 5.18.0  | 16        | 13.33%  |
| 5.15.0  | 8         | 6.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 52        | 43.33%  |
| 5.14    | 44        | 36.67%  |
| 5.18    | 16        | 13.33%  |
| 5.15    | 8         | 6.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 116       | 99.15%  |
| i686   | 1         | 0.85%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 81        | 67.5%   |
| KDE5    | 29        | 24.17%  |
| Unknown | 5         | 4.17%   |
| XFCE    | 3         | 2.5%    |
| KDE     | 1         | 0.83%   |
| GNOME   | 1         | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 112       | 95.73%  |
| Wayland | 3         | 2.56%   |
| Tty     | 2         | 1.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 71        | 60.68%  |
| Unknown | 43        | 36.75%  |
| SDDM    | 2         | 1.71%   |
| GDM     | 1         | 0.85%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 66        | 56.41%  |
| en_GB | 10        | 8.55%   |
| es_ES | 6         | 5.13%   |
| pt_BR | 5         | 4.27%   |
| en_IN | 5         | 4.27%   |
| fr_FR | 4         | 3.42%   |
| ru_RU | 3         | 2.56%   |
| pl_PL | 3         | 2.56%   |
| en_AU | 2         | 1.71%   |
| de_DE | 2         | 1.71%   |
| cs_CZ | 2         | 1.71%   |
| pt_PT | 1         | 0.85%   |
| it_IT | 1         | 0.85%   |
| fi_FI | 1         | 0.85%   |
| es_PE | 1         | 0.85%   |
| es_MX | 1         | 0.85%   |
| es_AR | 1         | 0.85%   |
| en_ZA | 1         | 0.85%   |
| en_DK | 1         | 0.85%   |
| en_CA | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 70        | 58.82%  |
| EFI  | 49        | 41.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 101       | 86.32%  |
| Ext4    | 11        | 9.4%    |
| Overlay | 5         | 4.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 53        | 44.17%  |
| GPT     | 50        | 41.67%  |
| MBR     | 17        | 14.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 105       | 88.98%  |
| Yes       | 13        | 11.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 67.23%  |
| Yes       | 39        | 32.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 24        | 20.51%  |
| Lenovo              | 20        | 17.09%  |
| Dell                | 15        | 12.82%  |
| ASUSTek Computer    | 14        | 11.97%  |
| MSI                 | 7         | 5.98%   |
| Acer                | 5         | 4.27%   |
| Gigabyte Technology | 4         | 3.42%   |
| Apple               | 4         | 3.42%   |
| Toshiba             | 3         | 2.56%   |
| Unknown             | 3         | 2.56%   |
| Samsung Electronics | 2         | 1.71%   |
| Microsoft           | 2         | 1.71%   |
| HUAWEI              | 2         | 1.71%   |
| Sony                | 1         | 0.85%   |
| Razer               | 1         | 0.85%   |
| Panasonic           | 1         | 0.85%   |
| Metabox             | 1         | 0.85%   |
| Jumper              | 1         | 0.85%   |
| Gateway             | 1         | 0.85%   |
| Fujitsu             | 1         | 0.85%   |
| ECS                 | 1         | 0.85%   |
| Daewoo Lucoms       | 1         | 0.85%   |
| Chuwi               | 1         | 0.85%   |
| ASRock              | 1         | 0.85%   |
| Alienware           | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                               | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 2.56%   |
| HP ENVY x360 Convertible 13-bd0xxx                 | 3         | 2.56%   |
| Unknown                                            | 3         | 2.56%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 2         | 1.71%   |
| HP ProDesk 600 G1 SFF                              | 2         | 1.71%   |
| HP Notebook                                        | 2         | 1.71%   |
| Dell Latitude E6410                                | 2         | 1.71%   |
| Toshiba Satellite-L845                             | 1         | 0.85%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 0.85%   |
| Toshiba Satellite C75D-B                           | 1         | 0.85%   |
| Sony VPCSB1C5E                                     | 1         | 0.85%   |
| Samsung 930QDB                                     | 1         | 0.85%   |
| Samsung 550P5C/550P7C                              | 1         | 0.85%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.85%   |
| Panasonic CF-31JBGNNDM                             | 1         | 0.85%   |
| MSI MS-7A34                                        | 1         | 0.85%   |
| MSI MS-7529                                        | 1         | 0.85%   |
| MSI GE62 6QE                                       | 1         | 0.85%   |
| MSI Creator Z16 Hiroshi F A11UE                    | 1         | 0.85%   |
| Microsoft Surface Pro 3                            | 1         | 0.85%   |
| Microsoft Surface Book                             | 1         | 0.85%   |
| Metabox Edge-Pro NS50MU                            | 1         | 0.85%   |
| Lenovo Z40-70 80E6                                 | 1         | 0.85%   |
| Lenovo Yoga C930-13IKB 81C4                        | 1         | 0.85%   |
| Lenovo V330-15IKB 81AX                             | 1         | 0.85%   |
| Lenovo ThinkPad X230 2325N66                       | 1         | 0.85%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS        | 1         | 0.85%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW           | 1         | 0.85%   |
| Lenovo ThinkPad T480 20L6SCYP00                    | 1         | 0.85%   |
| Lenovo ThinkPad T470p 20J7S0CF00                   | 1         | 0.85%   |
| Lenovo ThinkPad T420 4180MNU                       | 1         | 0.85%   |
| Lenovo ThinkPad L430 2465C32                       | 1         | 0.85%   |
| Lenovo ThinkPad E14 20RA0016GE                     | 1         | 0.85%   |
| Lenovo Legion 5 15ACH6 82JW                        | 1         | 0.85%   |
| Lenovo IdeaPad Y580                                | 1         | 0.85%   |
| Lenovo IdeaPad L340-17API 81LY                     | 1         | 0.85%   |
| Lenovo IdeaPad 320S-14IKB 80X4                     | 1         | 0.85%   |
| Lenovo H535 10117                                  | 1         | 0.85%   |
| Lenovo H530 10130                                  | 1         | 0.85%   |
| Lenovo B50-80 80EW                                 | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 8         | 6.84%   |
| Dell Latitude          | 8         | 6.84%   |
| Lenovo IdeaPad         | 5         | 4.27%   |
| HP ENVY                | 5         | 4.27%   |
| Dell Inspiron          | 5         | 4.27%   |
| HP Pavilion            | 4         | 3.42%   |
| MSI Modern             | 3         | 2.56%   |
| HP Laptop              | 3         | 2.56%   |
| HP EliteBook           | 3         | 2.56%   |
| Unknown                | 3         | 2.56%   |
| Toshiba Satellite      | 2         | 1.71%   |
| Microsoft Surface      | 2         | 1.71%   |
| HP ProDesk             | 2         | 1.71%   |
| HP ProBook             | 2         | 1.71%   |
| HP Notebook            | 2         | 1.71%   |
| Dell OptiPlex          | 2         | 1.71%   |
| ASUS ROG               | 2         | 1.71%   |
| ASUS PRIME             | 2         | 1.71%   |
| Acer Nitro             | 2         | 1.71%   |
| Toshiba Satellite-L845 | 1         | 0.85%   |
| Sony VPCSB1C5E         | 1         | 0.85%   |
| Samsung 930QDB         | 1         | 0.85%   |
| Samsung 550P5C         | 1         | 0.85%   |
| Razer Blade            | 1         | 0.85%   |
| Panasonic CF-31JBGNNDM | 1         | 0.85%   |
| MSI MS-7A34            | 1         | 0.85%   |
| MSI MS-7529            | 1         | 0.85%   |
| MSI GE62               | 1         | 0.85%   |
| MSI Creator            | 1         | 0.85%   |
| Metabox Edge-Pro       | 1         | 0.85%   |
| Lenovo Z40-70          | 1         | 0.85%   |
| Lenovo Yoga            | 1         | 0.85%   |
| Lenovo V330-15IKB      | 1         | 0.85%   |
| Lenovo Legion          | 1         | 0.85%   |
| Lenovo H535            | 1         | 0.85%   |
| Lenovo H530            | 1         | 0.85%   |
| Lenovo B50-80          | 1         | 0.85%   |
| Jumper EZbook          | 1         | 0.85%   |
| HUAWEI HVY-WXX9        | 1         | 0.85%   |
| HUAWEI BOHK-WAX9X      | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 19        | 16.24%  |
| 2020 | 11        | 9.4%    |
| 2017 | 11        | 9.4%    |
| 2013 | 11        | 9.4%    |
| 2012 | 11        | 9.4%    |
| 2011 | 10        | 8.55%   |
| 2018 | 9         | 7.69%   |
| 2019 | 8         | 6.84%   |
| 2016 | 7         | 5.98%   |
| 2010 | 5         | 4.27%   |
| 2015 | 4         | 3.42%   |
| 2014 | 4         | 3.42%   |
| 2009 | 2         | 1.71%   |
| 2007 | 2         | 1.71%   |
| 2022 | 1         | 0.85%   |
| 2008 | 1         | 0.85%   |
| 2006 | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 81        | 69.23%  |
| Desktop     | 26        | 22.22%  |
| Convertible | 8         | 6.84%   |
| Tablet      | 2         | 1.71%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 117       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 117       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 35        | 29.66%  |
| 16.01-24.0  | 22        | 18.64%  |
| 8.01-16.0   | 20        | 16.95%  |
| 3.01-4.0    | 18        | 15.25%  |
| 32.01-64.0  | 16        | 13.56%  |
| 64.01-256.0 | 3         | 2.54%   |
| 24.01-32.0  | 2         | 1.69%   |
| 1.01-2.0    | 2         | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 45        | 37.19%  |
| 1.01-2.0   | 39        | 32.23%  |
| 4.01-8.0   | 17        | 14.05%  |
| 3.01-4.0   | 12        | 9.92%   |
| 0.51-1.0   | 5         | 4.13%   |
| 8.01-16.0  | 2         | 1.65%   |
| 16.01-24.0 | 1         | 0.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 68        | 58.12%  |
| 2      | 42        | 35.9%   |
| 4      | 2         | 1.71%   |
| 3      | 2         | 1.71%   |
| 6      | 1         | 0.85%   |
| 5      | 1         | 0.85%   |
| 0      | 1         | 0.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 86        | 73.5%   |
| Yes       | 31        | 26.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 80.51%  |
| No        | 23        | 19.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 94.02%  |
| No        | 7         | 5.98%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 70.09%  |
| No        | 35        | 29.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 42        | 35.29%  |
| UK           | 7         | 5.88%   |
| Spain        | 6         | 5.04%   |
| Brazil       | 6         | 5.04%   |
| India        | 5         | 4.2%    |
| Mexico       | 4         | 3.36%   |
| Germany      | 4         | 3.36%   |
| Russia       | 3         | 2.52%   |
| Netherlands  | 3         | 2.52%   |
| France       | 3         | 2.52%   |
| Denmark      | 3         | 2.52%   |
| Canada       | 3         | 2.52%   |
| South Africa | 2         | 1.68%   |
| Morocco      | 2         | 1.68%   |
| Italy        | 2         | 1.68%   |
| Egypt        | 2         | 1.68%   |
| Czechia      | 2         | 1.68%   |
| Austria      | 2         | 1.68%   |
| Australia    | 2         | 1.68%   |
| Algeria      | 2         | 1.68%   |
| Switzerland  | 1         | 0.84%   |
| Sweden       | 1         | 0.84%   |
| Romania      | 1         | 0.84%   |
| Puerto Rico  | 1         | 0.84%   |
| Portugal     | 1         | 0.84%   |
| Peru         | 1         | 0.84%   |
| Nepal        | 1         | 0.84%   |
| Mongolia     | 1         | 0.84%   |
| Kenya        | 1         | 0.84%   |
| Georgia      | 1         | 0.84%   |
| Finland      | 1         | 0.84%   |
| Bulgaria     | 1         | 0.84%   |
| Benin        | 1         | 0.84%   |
| Argentina    | 1         | 0.84%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Seattle               | 3         | 2.48%   |
| Vienna                | 2         | 1.65%   |
| Tangier               | 2         | 1.65%   |
| Ruskin                | 2         | 1.65%   |
| Pensacola             | 2         | 1.65%   |
| Dublin                | 2         | 1.65%   |
| Camden                | 2         | 1.65%   |
| Amsterdam             | 2         | 1.65%   |
| Zurich                | 1         | 0.83%   |
| Villa Carlos Paz      | 1         | 0.83%   |
| Viby J                | 1         | 0.83%   |
| Vapi                  | 1         | 0.83%   |
| Ulan Bator            | 1         | 0.83%   |
| Uherské Hradiště   | 1         | 0.83%   |
| Ts'khinvali           | 1         | 0.83%   |
| Trivandrum            | 1         | 0.83%   |
| Tampere               | 1         | 0.83%   |
| Sydney                | 1         | 0.83%   |
| Sumaré               | 1         | 0.83%   |
| St Petersburg         | 1         | 0.83%   |
| Springfield           | 1         | 0.83%   |
| Spotsylvania          | 1         | 0.83%   |
| South Hamilton        | 1         | 0.83%   |
| Skive                 | 1         | 0.83%   |
| Sao Paulo             | 1         | 0.83%   |
| Sao Joao de Meriti    | 1         | 0.83%   |
| Sao Bernardo do Campo | 1         | 0.83%   |
| Santa Maria           | 1         | 0.83%   |
| San Juan              | 1         | 0.83%   |
| Saint Paul            | 1         | 0.83%   |
| Rho                   | 1         | 0.83%   |
| Pretoria              | 1         | 0.83%   |
| Prague                | 1         | 0.83%   |
| Point Pleasant Beach  | 1         | 0.83%   |
| Plovdiv               | 1         | 0.83%   |
| Pittsburgh            | 1         | 0.83%   |
| Phoenix               | 1         | 0.83%   |
| Orofino               | 1         | 0.83%   |
| Opelousas             | 1         | 0.83%   |
| Nairobi               | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 34     | 16.46%  |
| WDC                 | 22        | 25     | 13.92%  |
| Seagate             | 22        | 28     | 13.92%  |
| Toshiba             | 16        | 17     | 10.13%  |
| Kingston            | 9         | 10     | 5.7%    |
| Unknown             | 6         | 8      | 3.8%    |
| SanDisk             | 6         | 10     | 3.8%    |
| Intel               | 6         | 16     | 3.8%    |
| Hitachi             | 5         | 6      | 3.16%   |
| China               | 5         | 6      | 3.16%   |
| Micron Technology   | 3         | 3      | 1.9%    |
| HGST                | 3         | 3      | 1.9%    |
| SK hynix            | 2         | 2      | 1.27%   |
| PNY                 | 2         | 2      | 1.27%   |
| Crucial             | 2         | 2      | 1.27%   |
| Apple               | 2         | 2      | 1.27%   |
| A-DATA Technology   | 2         | 2      | 1.27%   |
| YMTC                | 1         | 1      | 0.63%   |
| Team                | 1         | 1      | 0.63%   |
| SPCC                | 1         | 1      | 0.63%   |
| Silicon Motion      | 1         | 1      | 0.63%   |
| S3+                 | 1         | 1      | 0.63%   |
| RZX                 | 1         | 1      | 0.63%   |
| Plextor             | 1         | 1      | 0.63%   |
| Phison              | 1         | 1      | 0.63%   |
| Netac               | 1         | 1      | 0.63%   |
| LITEON              | 1         | 1      | 0.63%   |
| KingSpec            | 1         | 1      | 0.63%   |
| KingFast            | 1         | 2      | 0.63%   |
| Intenso             | 1         | 2      | 0.63%   |
| HUAWEI              | 1         | 1      | 0.63%   |
| BR                  | 1         | 1      | 0.63%   |
| BHT                 | 1         | 1      | 0.63%   |
| ASMT                | 1         | 1      | 0.63%   |
| ASMedia             | 1         | 1      | 0.63%   |
| Apacer              | 1         | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB               | 5         | 2.79%   |
| Intel HBRPEKNX0202AH 512GB           | 4         | 2.23%   |
| Kingston NVMe SSD Drive 512GB        | 3         | 1.68%   |
| Intel HBRPEKNX0202AHO 32GB           | 3         | 1.68%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 1.12%   |
| WDC WD5000AADS-00S9B0 500GB          | 2         | 1.12%   |
| Unknown MMC Card  32GB               | 2         | 1.12%   |
| Toshiba MQ01ABD075 752GB             | 2         | 1.12%   |
| Toshiba DT01ACA200 2TB               | 2         | 1.12%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 1.12%   |
| Seagate ST250DM000-1BD141 250GB      | 2         | 1.12%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 2         | 1.12%   |
| SanDisk NVMe SSD Drive 1TB           | 2         | 1.12%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.12%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.12%   |
| Samsung NVMe SSD Drive 1024GB        | 2         | 1.12%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 1.12%   |
| Intel NVMe SSD Drive 512GB           | 2         | 1.12%   |
| Intel NVMe SSD Drive 32GB            | 2         | 1.12%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.12%   |
| YMTC PC005 512GB                     | 1         | 0.56%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.56%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.56%   |
| WDC WDBRPG5000ANC-WRSN 500GB         | 1         | 0.56%   |
| WDC WDBNCE2500PNC 250GB SSD          | 1         | 0.56%   |
| WDC WD6400BPVT-75HXZT1 640GB         | 1         | 0.56%   |
| WDC WD5000LPCX-60VHAT1 500GB         | 1         | 0.56%   |
| WDC WD3200BPVT-00JJ5T0 320GB         | 1         | 0.56%   |
| WDC WD20EZAZ-00GGJB0 2TB             | 1         | 0.56%   |
| WDC WD2003FZEX-00Z4SA0 2TB           | 1         | 0.56%   |
| WDC WD10SPZX-75Z10T2 1TB             | 1         | 0.56%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.56%   |
| WDC WD10PURX-64E5EY0 1TB             | 1         | 0.56%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 0.56%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 0.56%   |
| WDC WD10EARS-00Y5B1 1TB              | 1         | 0.56%   |
| WDC WD10EADX-22TDHB0 1TB             | 1         | 0.56%   |
| WDC PC SN720 SDAPNTW-512G-1101 512GB | 1         | 0.56%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 28     | 34.92%  |
| Toshiba             | 16        | 17     | 25.4%   |
| WDC                 | 13        | 15     | 20.63%  |
| Hitachi             | 5         | 6      | 7.94%   |
| HGST                | 3         | 3      | 4.76%   |
| Samsung Electronics | 2         | 2      | 3.17%   |
| Unknown             | 1         | 2      | 1.59%   |
| ASMedia             | 1         | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 14     | 20%     |
| WDC                 | 6         | 6      | 12%     |
| Kingston            | 5         | 6      | 10%     |
| China               | 5         | 6      | 10%     |
| SanDisk             | 2         | 2      | 4%      |
| PNY                 | 2         | 2      | 4%      |
| Crucial             | 2         | 2      | 4%      |
| Unknown             | 1         | 1      | 2%      |
| Team                | 1         | 1      | 2%      |
| SPCC                | 1         | 1      | 2%      |
| SK hynix            | 1         | 1      | 2%      |
| S3+                 | 1         | 1      | 2%      |
| RZX                 | 1         | 1      | 2%      |
| Plextor             | 1         | 1      | 2%      |
| Netac               | 1         | 1      | 2%      |
| Micron Technology   | 1         | 1      | 2%      |
| LITEON              | 1         | 1      | 2%      |
| KingSpec            | 1         | 1      | 2%      |
| KingFast            | 1         | 1      | 2%      |
| Intenso             | 1         | 2      | 2%      |
| BR                  | 1         | 1      | 2%      |
| BHT                 | 1         | 1      | 2%      |
| ASMT                | 1         | 1      | 2%      |
| Apple               | 1         | 1      | 2%      |
| Apacer              | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 54        | 74     | 36.99%  |
| SSD     | 47        | 57     | 32.19%  |
| NVMe    | 39        | 59     | 26.71%  |
| MMC     | 4         | 5      | 2.74%   |
| Unknown | 2         | 2      | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 83        | 126    | 62.88%  |
| NVMe | 39        | 59     | 29.55%  |
| SAS  | 6         | 7      | 4.55%   |
| MMC  | 4         | 5      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 88     | 62.63%  |
| 0.51-1.0   | 30        | 33     | 30.3%   |
| 1.01-2.0   | 7         | 10     | 7.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 28        | 23.73%  |
| 501-1000   | 26        | 22.03%  |
| 251-500    | 22        | 18.64%  |
| Unknown    | 16        | 13.56%  |
| 1001-2000  | 15        | 12.71%  |
| 1-20       | 4         | 3.39%   |
| 2001-3000  | 3         | 2.54%   |
| 21-50      | 2         | 1.69%   |
| 51-100     | 2         | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 40        | 33.33%  |
| 51-100    | 20        | 16.67%  |
| Unknown   | 16        | 13.33%  |
| 1-20      | 13        | 10.83%  |
| 101-250   | 12        | 10%     |
| 251-500   | 11        | 9.17%   |
| 501-1000  | 7         | 5.83%   |
| 1001-2000 | 1         | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-00JJ5T0 320GB        | 1         | 1      | 7.14%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1         | 1      | 7.14%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 7.14%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 7.14%   |
| Seagate ST3320418AS 320GB           | 1         | 1      | 7.14%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 7.14%   |
| Seagate ST250DM000-1BD141 250GB     | 1         | 1      | 7.14%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 1         | 1      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 7.14%   |
| SanDisk SD6SF1M128G1022I 128GB SSD  | 1         | 1      | 7.14%   |
| Samsung Electronics HM500JI 500GB   | 1         | 1      | 7.14%   |
| Plextor PX-512M6Pro 512GB SSD       | 1         | 1      | 7.14%   |
| Intel HBRPEKNX0202AHO 32GB          | 1         | 1      | 7.14%   |
| A-DATA Technology SX7000NP 128GB    | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 38.46%  |
| WDC                 | 2         | 2      | 15.38%  |
| Toshiba             | 1         | 1      | 7.69%   |
| SanDisk             | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Plextor             | 1         | 1      | 7.69%   |
| Intel               | 1         | 1      | 7.69%   |
| A-DATA Technology   | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 55.56%  |
| WDC                 | 2         | 2      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 10     | 66.67%  |
| NVMe | 2         | 2      | 16.67%  |
| SSD  | 2         | 2      | 16.67%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 65        | 83     | 48.87%  |
| Detected | 58        | 99     | 43.61%  |
| Malfunc  | 9         | 14     | 6.77%   |
| Failed   | 1         | 1      | 0.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 80        | 57.55%  |
| AMD                         | 18        | 12.95%  |
| Samsung Electronics         | 16        | 11.51%  |
| SanDisk                     | 8         | 5.76%   |
| Nvidia                      | 4         | 2.88%   |
| Kingston Technology Company | 4         | 2.88%   |
| Micron Technology           | 2         | 1.44%   |
| Yangtze Memory Technologies | 1         | 0.72%   |
| SK hynix                    | 1         | 0.72%   |
| Silicon Motion              | 1         | 0.72%   |
| Phison Electronics          | 1         | 0.72%   |
| ASMedia Technology          | 1         | 0.72%   |
| Apple                       | 1         | 0.72%   |
| ADATA Technology            | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16        | 9.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9         | 5.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 9         | 5.52%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 4.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8         | 4.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 5         | 3.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 3.07%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 5         | 3.07%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 5         | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 3.07%   |
| Samsung NVMe SSD Controller 980                                                         | 4         | 2.45%   |
| Intel Non-Volatile memory controller                                                    | 4         | 2.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.45%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 1.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.84%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 1.23%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 1.23%   |
| Micron Non-Volatile memory controller                                                   | 2         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.23%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 1.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 2         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 2         | 1.23%   |
| Yangtze Memory Non-Volatile memory controller                                           | 1         | 0.61%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1         | 0.61%   |
| Silicon Motion Non-Volatile memory controller                                           | 1         | 0.61%   |
| SanDisk PC SN520 NVMe SSD                                                               | 1         | 0.61%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.61%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.61%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                                | 1         | 0.61%   |
| Nvidia MCP89 SATA Controller                                                            | 1         | 0.61%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.61%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.61%   |
| Nvidia MCP61 IDE                                                                        | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 66        | 46.48%  |
| NVMe | 39        | 27.46%  |
| RAID | 19        | 13.38%  |
| IDE  | 18        | 12.68%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 92        | 78.63%  |
| AMD    | 25        | 21.37%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 4.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 2.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 2.56%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 2.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 2         | 1.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 1.71%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 2         | 1.71%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 2         | 1.71%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 2         | 1.71%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 2         | 1.71%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 2         | 1.71%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 2         | 1.71%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 2         | 1.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.71%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 2         | 1.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 1.71%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz     | 1         | 0.85%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz  | 1         | 0.85%   |
| Intel Pentium CPU N3530 @ 2.16GHz       | 1         | 0.85%   |
| Intel Pentium CPU G630 @ 2.70GHz        | 1         | 0.85%   |
| Intel Pentium CPU G3260 @ 3.30GHz       | 1         | 0.85%   |
| Intel Pentium CPU 4415U @ 2.30GHz       | 1         | 0.85%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 1         | 0.85%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 0.85%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 0.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 0.85%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 0.85%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 0.85%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 1         | 0.85%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 0.85%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 0.85%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 0.85%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 0.85%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1         | 0.85%   |
| Intel Core i7-10850H CPU @ 2.70GHz      | 1         | 0.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 0.85%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 1         | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 25        | 21.37%  |
| Intel Core i7      | 23        | 19.66%  |
| Intel Core i3      | 15        | 12.82%  |
| Other              | 11        | 9.4%    |
| AMD Ryzen 7        | 8         | 6.84%   |
| Intel Core 2 Duo   | 6         | 5.13%   |
| Intel Celeron      | 6         | 5.13%   |
| AMD Ryzen 5        | 6         | 5.13%   |
| Intel Pentium      | 4         | 3.42%   |
| AMD FX             | 2         | 1.71%   |
| AMD A6             | 2         | 1.71%   |
| Intel Xeon         | 1         | 0.85%   |
| Intel Pentium Dual | 1         | 0.85%   |
| Intel Core 2       | 1         | 0.85%   |
| AMD Ryzen 9        | 1         | 0.85%   |
| AMD Ryzen 3        | 1         | 0.85%   |
| AMD E2             | 1         | 0.85%   |
| AMD Athlon 64 X2   | 1         | 0.85%   |
| AMD A8             | 1         | 0.85%   |
| AMD A4             | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 57        | 48.72%  |
| 4      | 42        | 35.9%   |
| 8      | 9         | 7.69%   |
| 6      | 7         | 5.98%   |
| 14     | 1         | 0.85%   |
| 12     | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 117       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 86        | 73.5%   |
| 1      | 31        | 26.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 117       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 46.61%  |
| 0x206a7    | 8         | 6.78%   |
| 0x806e9    | 6         | 5.08%   |
| 0x806c1    | 5         | 4.24%   |
| 0x306a9    | 4         | 3.39%   |
| 0x806ec    | 3         | 2.54%   |
| 0x406e3    | 3         | 2.54%   |
| 0x1067a    | 3         | 2.54%   |
| 0xa0652    | 2         | 1.69%   |
| 0x906e9    | 2         | 1.69%   |
| 0x806ea    | 2         | 1.69%   |
| 0x706e5    | 2         | 1.69%   |
| 0x706a8    | 2         | 1.69%   |
| 0x40651    | 2         | 1.69%   |
| 0x306c3    | 2         | 1.69%   |
| 0x08001138 | 2         | 1.69%   |
| 0x07030105 | 2         | 1.69%   |
| 0x906ed    | 1         | 0.85%   |
| 0x906ea    | 1         | 0.85%   |
| 0x906a3    | 1         | 0.85%   |
| 0x806eb    | 1         | 0.85%   |
| 0x806d1    | 1         | 0.85%   |
| 0x6f6      | 1         | 0.85%   |
| 0x506c9    | 1         | 0.85%   |
| 0x08701021 | 1         | 0.85%   |
| 0x08600106 | 1         | 0.85%   |
| 0x08108109 | 1         | 0.85%   |
| 0x06006113 | 1         | 0.85%   |
| 0x06001119 | 1         | 0.85%   |
| 0x03000027 | 1         | 0.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 25        | 21.37%  |
| SandyBridge      | 15        | 12.82%  |
| Haswell          | 9         | 7.69%   |
| TigerLake        | 7         | 5.98%   |
| IvyBridge        | 7         | 5.98%   |
| Penryn           | 6         | 5.13%   |
| Zen 2            | 5         | 4.27%   |
| Unknown          | 5         | 4.27%   |
| Skylake          | 4         | 3.42%   |
| Zen              | 3         | 2.56%   |
| IceLake          | 3         | 2.56%   |
| Goldmont plus    | 3         | 2.56%   |
| Excavator        | 3         | 2.56%   |
| Zen+             | 2         | 1.71%   |
| Zen 3            | 2         | 1.71%   |
| Westmere         | 2         | 1.71%   |
| Silvermont       | 2         | 1.71%   |
| Puma             | 2         | 1.71%   |
| Piledriver       | 2         | 1.71%   |
| Core             | 2         | 1.71%   |
| CometLake        | 2         | 1.71%   |
| Broadwell        | 2         | 1.71%   |
| K8 Hammer        | 1         | 0.85%   |
| K10 Llano        | 1         | 0.85%   |
| Goldmont         | 1         | 0.85%   |
| Alderlake Hybrid | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 85        | 57.05%  |
| Nvidia | 32        | 21.48%  |
| AMD    | 32        | 21.48%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 15        | 9.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 7         | 4.61%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 3.95%   |
| Intel UHD Graphics 620                                                      | 5         | 3.29%   |
| Intel HD Graphics 620                                                       | 5         | 3.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 4         | 2.63%   |
| AMD Lucienne                                                                | 4         | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 1.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 3         | 1.97%   |
| Intel HD Graphics 630                                                       | 3         | 1.97%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 1.97%   |
| AMD Renoir                                                                  | 3         | 1.97%   |
| Nvidia MCP89 [GeForce 320M]                                                 | 2         | 1.32%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 1.32%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 2         | 1.32%   |
| Intel HD Graphics 5500                                                      | 2         | 1.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 2         | 1.32%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 1.32%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 2         | 1.32%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                  | 2         | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.32%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.32%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2         | 1.32%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.66%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.66%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 1         | 0.66%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.66%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.66%   |
| Nvidia GP108GLM [Quadro P520]                                               | 1         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.66%   |
| Nvidia GM206M [GeForce GTX 965M]                                            | 1         | 0.66%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1         | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 0.66%   |
| Nvidia GM108M [GeForce 930MX]                                               | 1         | 0.66%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 56        | 47.86%  |
| 1 x AMD        | 21        | 17.95%  |
| Intel + Nvidia | 18        | 15.38%  |
| 1 x Nvidia     | 10        | 8.55%   |
| Intel + AMD    | 7         | 5.98%   |
| AMD + Nvidia   | 3         | 2.56%   |
| 2 x Nvidia     | 1         | 0.85%   |
| 2 x AMD        | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 106       | 89.83%  |
| Proprietary | 10        | 8.47%   |
| Unknown     | 2         | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 91        | 77.12%  |
| 1.01-2.0   | 10        | 8.47%   |
| 0.01-0.5   | 7         | 5.93%   |
| 3.01-4.0   | 5         | 4.24%   |
| 0.51-1.0   | 4         | 3.39%   |
| 7.01-8.0   | 1         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 23        | 18.7%   |
| BOE                     | 19        | 15.45%  |
| LG Display              | 13        | 10.57%  |
| Samsung Electronics     | 12        | 9.76%   |
| Chimei Innolux          | 10        | 8.13%   |
| InfoVision              | 4         | 3.25%   |
| Goldstar                | 4         | 3.25%   |
| Apple                   | 4         | 3.25%   |
| AOC                     | 4         | 3.25%   |
| Lenovo                  | 3         | 2.44%   |
| Chi Mei Optoelectronics | 3         | 2.44%   |
| Acer                    | 3         | 2.44%   |
| Toshiba                 | 2         | 1.63%   |
| NEC Computers           | 2         | 1.63%   |
| Dell                    | 2         | 1.63%   |
| BenQ                    | 2         | 1.63%   |
| Vizio                   | 1         | 0.81%   |
| Unknown (AAA)           | 1         | 0.81%   |
| Unknown                 | 1         | 0.81%   |
| STD                     | 1         | 0.81%   |
| Plain Tree Systems      | 1         | 0.81%   |
| Philips                 | 1         | 0.81%   |
| PANDA                   | 1         | 0.81%   |
| Panasonic               | 1         | 0.81%   |
| ONN                     | 1         | 0.81%   |
| Kogan                   | 1         | 0.81%   |
| CSO                     | 1         | 0.81%   |
| Ativa                   | 1         | 0.81%   |
| Ancor Communications    | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch            | 3         | 2.4%    |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch          | 3         | 2.4%    |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch              | 2         | 1.6%    |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch               | 1         | 0.8%    |
| Unknown LCD Monitor SAMSUNG 3840x1080                                   | 1         | 0.8%    |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch                | 1         | 0.8%    |
| Toshiba TV TSB0105 1920x540 708x398mm 32.0-inch                         | 1         | 0.8%    |
| Toshiba TSB-TV TSB0205 1920x1080 531x398mm 26.1-inch                    | 1         | 0.8%    |
| STD LCD Monitor STD0001 1920x1080                                       | 1         | 0.8%    |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch    | 1         | 0.8%    |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 530x300mm 24.0-inch     | 1         | 0.8%    |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 598x336mm 27.0-inch       | 1         | 0.8%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch       | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC4145 1366x768 310x170mm 13.9-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch   | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SDC4156 1920x1080 294x165mm 13.3-inch   | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch  | 1         | 0.8%    |
| Plain Tree Systems Monitor PTS0899 1680x1050 474x296mm 22.0-inch        | 1         | 0.8%    |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                | 1         | 0.8%    |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                 | 1         | 0.8%    |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch             | 1         | 0.8%    |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                    | 1         | 0.8%    |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch             | 1         | 0.8%    |
| NEC Computers EA243WM NEC6863 1920x1200 519x324mm 24.1-inch             | 1         | 0.8%    |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch            | 1         | 0.8%    |
| LG Display LCD Monitor LGD05BC 3840x2160 309x174mm 14.0-inch            | 1         | 0.8%    |
| LG Display LCD Monitor LGD0574 1920x1080 309x175mm 14.0-inch            | 1         | 0.8%    |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch            | 1         | 0.8%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 1         | 0.8%    |
| LG Display LCD Monitor LGD045A 1366x768 293x165mm 13.2-inch             | 1         | 0.8%    |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch             | 1         | 0.8%    |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch             | 1         | 0.8%    |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch             | 1         | 0.8%    |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch             | 1         | 0.8%    |
| LG Display LCD Monitor LGD0292 1366x768 309x174mm 14.0-inch             | 1         | 0.8%    |
| LG Display LCD Monitor LGD0257 1440x900 304x190mm 14.1-inch             | 1         | 0.8%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 49        | 42.24%  |
| 1366x768 (WXGA)    | 30        | 25.86%  |
| 3840x2160 (4K)     | 6         | 5.17%   |
| 1680x1050 (WSXGA+) | 6         | 5.17%   |
| 1600x900 (HD+)     | 6         | 5.17%   |
| 1280x800 (WXGA)    | 4         | 3.45%   |
| 2560x1600          | 2         | 1.72%   |
| 2560x1440 (QHD)    | 2         | 1.72%   |
| 2160x1440          | 2         | 1.72%   |
| 1920x1200 (WUXGA)  | 2         | 1.72%   |
| 1440x900 (WXGA+)   | 2         | 1.72%   |
| 1280x1024 (SXGA)   | 2         | 1.72%   |
| 3840x1080          | 1         | 0.86%   |
| 2880x1800          | 1         | 0.86%   |
| Unknown            | 1         | 0.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 37        | 30.33%  |
| 14      | 17        | 13.93%  |
| 13      | 14        | 11.48%  |
| 17      | 10        | 8.2%    |
| 27      | 6         | 4.92%   |
| 24      | 6         | 4.92%   |
| 23      | 4         | 3.28%   |
| 22      | 4         | 3.28%   |
| 21      | 4         | 3.28%   |
| 16      | 3         | 2.46%   |
| 12      | 3         | 2.46%   |
| Unknown | 3         | 2.46%   |
| 11      | 2         | 1.64%   |
| 84      | 1         | 0.82%   |
| 72      | 1         | 0.82%   |
| 54      | 1         | 0.82%   |
| 48      | 1         | 0.82%   |
| 41      | 1         | 0.82%   |
| 40      | 1         | 0.82%   |
| 32      | 1         | 0.82%   |
| 31      | 1         | 0.82%   |
| 20      | 1         | 0.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 65        | 53.72%  |
| 501-600     | 15        | 12.4%   |
| 201-300     | 11        | 9.09%   |
| 351-400     | 10        | 8.26%   |
| 401-500     | 9         | 7.44%   |
| Unknown     | 3         | 2.48%   |
| 1501-2000   | 2         | 1.65%   |
| 1001-1500   | 2         | 1.65%   |
| 801-900     | 1         | 0.83%   |
| 701-800     | 1         | 0.83%   |
| 601-700     | 1         | 0.83%   |
| 901-1000    | 1         | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 90        | 80.36%  |
| 16/10   | 16        | 14.29%  |
| Unknown | 3         | 2.68%   |
| 5/4     | 2         | 1.79%   |
| 3/2     | 1         | 0.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 38        | 30.89%  |
| 81-90          | 25        | 20.33%  |
| 201-250        | 14        | 11.38%  |
| 121-130        | 7         | 5.69%   |
| 71-80          | 6         | 4.88%   |
| 301-350        | 6         | 4.88%   |
| More than 1000 | 4         | 3.25%   |
| 251-300        | 4         | 3.25%   |
| 61-70          | 3         | 2.44%   |
| Unknown        | 3         | 2.44%   |
| 51-60          | 2         | 1.63%   |
| 351-500        | 2         | 1.63%   |
| 151-200        | 2         | 1.63%   |
| 141-150        | 2         | 1.63%   |
| 111-120        | 2         | 1.63%   |
| 501-1000       | 2         | 1.63%   |
| 131-140        | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 39        | 32.5%   |
| 121-160       | 36        | 30%     |
| 51-100        | 27        | 22.5%   |
| 161-240       | 9         | 7.5%    |
| More than 240 | 3         | 2.5%    |
| 1-50          | 3         | 2.5%    |
| Unknown       | 3         | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 100       | 83.33%  |
| 2     | 15        | 12.5%   |
| 0     | 3         | 2.5%    |
| 3     | 2         | 1.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 71        | 33.65%  |
| Intel                           | 61        | 28.91%  |
| Qualcomm Atheros                | 18        | 8.53%   |
| Broadcom                        | 10        | 4.74%   |
| TP-Link                         | 6         | 2.84%   |
| MediaTek                        | 6         | 2.84%   |
| Samsung Electronics             | 5         | 2.37%   |
| Ralink Technology               | 4         | 1.9%    |
| Qualcomm Atheros Communications | 3         | 1.42%   |
| Nvidia                          | 3         | 1.42%   |
| ASUSTek Computer                | 3         | 1.42%   |
| NetGear                         | 2         | 0.95%   |
| Microsoft                       | 2         | 0.95%   |
| Marvell Technology Group        | 2         | 0.95%   |
| Huawei Technologies             | 2         | 0.95%   |
| Apple                           | 2         | 0.95%   |
| vivo                            | 1         | 0.47%   |
| Ralink                          | 1         | 0.47%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.47%   |
| Mercucys                        | 1         | 0.47%   |
| Linksys                         | 1         | 0.47%   |
| ICS Advent                      | 1         | 0.47%   |
| Gemtek                          | 1         | 0.47%   |
| DisplayLink                     | 1         | 0.47%   |
| D-Link System                   | 1         | 0.47%   |
| Broadcom Limited                | 1         | 0.47%   |
| ASIX Electronics                | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 15.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 4.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 6         | 2.44%   |
| Realtek 802.11ac NIC                                              | 5         | 2.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.03%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.03%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 2.03%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 4         | 1.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.63%   |
| Intel Wireless 3165                                               | 4         | 1.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 1.22%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.22%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 1.22%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 1.22%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.22%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.22%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.22%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.81%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.81%   |
| NetGear A6210                                                     | 2         | 0.81%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 2         | 0.81%   |
| Intel Wireless 3160                                               | 2         | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.81%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.81%   |
| Intel Centrino Wireless-N 2200                                    | 2         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 37.96%  |
| Realtek Semiconductor           | 31        | 22.63%  |
| Qualcomm Atheros                | 14        | 10.22%  |
| Broadcom                        | 8         | 5.84%   |
| TP-Link                         | 6         | 4.38%   |
| Ralink Technology               | 4         | 2.92%   |
| MediaTek                        | 4         | 2.92%   |
| Qualcomm Atheros Communications | 3         | 2.19%   |
| ASUSTek Computer                | 3         | 2.19%   |
| NetGear                         | 2         | 1.46%   |
| Microsoft                       | 2         | 1.46%   |
| Marvell Technology Group        | 2         | 1.46%   |
| Ralink                          | 1         | 0.73%   |
| Mercucys                        | 1         | 0.73%   |
| Linksys                         | 1         | 0.73%   |
| Gemtek                          | 1         | 0.73%   |
| D-Link System                   | 1         | 0.73%   |
| Broadcom Limited                | 1         | 0.73%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 6         | 4.38%   |
| Realtek 802.11ac NIC                                       | 5         | 3.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 5         | 3.65%   |
| Intel Wireless 8265 / 8275                                 | 5         | 3.65%   |
| Intel Wi-Fi 6 AX201                                        | 5         | 3.65%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 4         | 2.92%   |
| Intel Wireless 3165                                        | 4         | 2.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 4         | 2.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 4         | 2.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 3         | 2.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 3         | 2.19%   |
| Qualcomm Atheros AR9271 802.11n                            | 3         | 2.19%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 3         | 2.19%   |
| Intel Wi-Fi 6 AX200                                        | 3         | 2.19%   |
| Intel Centrino Advanced-N 6235                             | 3         | 2.19%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 2         | 1.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 1.46%   |
| Realtek RTL8723DE Wireless Network Adapter                 | 2         | 1.46%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 2         | 1.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 2         | 1.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 1.46%   |
| NetGear A6210                                              | 2         | 1.46%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless          | 2         | 1.46%   |
| Intel Wireless 3160                                        | 2         | 1.46%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 2         | 1.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 2         | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                             | 2         | 1.46%   |
| Intel Centrino Wireless-N 2200                             | 2         | 1.46%   |
| Intel Centrino Advanced-N 6200                             | 2         | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 1.46%   |
| Broadcom BCM43224 802.11a/b/g/n                            | 2         | 1.46%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1         | 0.73%   |
| TP-Link Archer T4U ver.3                                   | 1         | 0.73%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1         | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 0.73%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 1         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1         | 0.73%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1         | 0.73%   |
| Realtek RTL8191SEvA Wireless LAN Controller                | 1         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 56        | 53.33%  |
| Intel                 | 24        | 22.86%  |
| Samsung Electronics   | 5         | 4.76%   |
| Qualcomm Atheros      | 5         | 4.76%   |
| Nvidia                | 3         | 2.86%   |
| Broadcom              | 3         | 2.86%   |
| MediaTek              | 2         | 1.9%    |
| Apple                 | 2         | 1.9%    |
| vivo                  | 1         | 0.95%   |
| ICS Advent            | 1         | 0.95%   |
| Huawei Technologies   | 1         | 0.95%   |
| DisplayLink           | 1         | 0.95%   |
| ASIX Electronics      | 1         | 0.95%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 34.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 10.28%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 6.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 3.74%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 2.8%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.8%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.87%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.87%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.87%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.87%   |
| vivo 1806                                                         | 1         | 0.93%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.93%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.93%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.93%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.93%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.93%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.93%   |
| MediaTek TECNO CAMON 18P                                          | 1         | 0.93%   |
| MediaTek Infinix NOTE 11                                          | 1         | 0.93%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.93%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.93%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.93%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.93%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 0.93%   |
| Huawei Ideos (tethering mode)                                     | 1         | 0.93%   |
| DisplayLink USB3.0 UHD Dual Video Dock                            | 1         | 0.93%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.93%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.93%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.93%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 110       | 53.14%  |
| Ethernet | 95        | 45.89%  |
| Modem    | 1         | 0.48%   |
| Unknown  | 1         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 84        | 70.59%  |
| Ethernet | 35        | 29.41%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 66        | 56.41%  |
| 1     | 49        | 41.88%  |
| 3     | 1         | 0.85%   |
| 0     | 1         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 85        | 72.03%  |
| Yes  | 33        | 27.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 49.4%   |
| Qualcomm Atheros Communications | 8         | 9.64%   |
| Realtek Semiconductor           | 7         | 8.43%   |
| Toshiba                         | 3         | 3.61%   |
| MediaTek                        | 3         | 3.61%   |
| IMC Networks                    | 3         | 3.61%   |
| Broadcom                        | 3         | 3.61%   |
| Apple                           | 3         | 3.61%   |
| Marvell Semiconductor           | 2         | 2.41%   |
| Lite-On Technology              | 2         | 2.41%   |
| Foxconn / Hon Hai               | 2         | 2.41%   |
| Cambridge Silicon Radio         | 2         | 2.41%   |
| Realtek                         | 1         | 1.2%    |
| Ralink                          | 1         | 1.2%    |
| Dell                            | 1         | 1.2%    |
| Alps Electric                   | 1         | 1.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 14        | 16.87%  |
| Intel AX201 Bluetooth                                                               | 11        | 13.25%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 8.43%   |
| Realtek Bluetooth Radio                                                             | 5         | 6.02%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 4.82%   |
| MediaTek Wireless_Device                                                            | 3         | 3.61%   |
| Intel AX200 Bluetooth                                                               | 3         | 3.61%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.41%   |
| Intel AX210 Bluetooth                                                               | 2         | 2.41%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 2.41%   |
| Apple Bluetooth Host Controller                                                     | 2         | 2.41%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 1.2%    |
| Toshiba BCM43142A0                                                                  | 1         | 1.2%    |
| Toshiba Atheros AR3012 Bluetooth                                                    | 1         | 1.2%    |
| Realtek Bluetooth Radio                                                             | 1         | 1.2%    |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.2%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.2%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.2%    |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 1.2%    |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 1.2%    |
| Lite-On Wireless_Device                                                             | 1         | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.2%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.2%    |
| Intel Bluetooth Device                                                              | 1         | 1.2%    |
| IMC Networks Bluetooth Device                                                       | 1         | 1.2%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.2%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 1.2%    |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.2%    |
| Broadcom HP Portable SoftSailing                                                    | 1         | 1.2%    |
| Broadcom BCM20702A0                                                                 | 1         | 1.2%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.2%    |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.2%    |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 1.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 88        | 61.97%  |
| AMD                    | 28        | 19.72%  |
| Nvidia                 | 22        | 15.49%  |
| SteelSeries ApS        | 1         | 0.7%    |
| Generalplus Technology | 1         | 0.7%    |
| C-Media Electronics    | 1         | 0.7%    |
| Apple                  | 1         | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 14        | 8.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 6.98%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 6.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 5.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 4.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 4.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 4.07%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 4.07%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 2.33%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.74%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.16%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 1.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.16%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.16%   |
| Nvidia Audio device                                                        | 2         | 1.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.16%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.16%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.16%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.16%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.16%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.16%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.16%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.16%   |
| AMD High Definition Audio Controller                                       | 2         | 1.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.16%   |
| SteelSeries ApS SteelSeries GameDAC                                        | 1         | 0.58%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.58%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.58%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 27.06%  |
| Micron Technology   | 14        | 16.47%  |
| SK hynix            | 11        | 12.94%  |
| Kingston            | 7         | 8.24%   |
| Crucial             | 7         | 8.24%   |
| Unknown             | 6         | 7.06%   |
| Unknown (ABCD)      | 3         | 3.53%   |
| Ramaxel Technology  | 3         | 3.53%   |
| Elpida              | 3         | 3.53%   |
| Unifosa             | 1         | 1.18%   |
| Teikon              | 1         | 1.18%   |
| Smart               | 1         | 1.18%   |
| Silicon Power       | 1         | 1.18%   |
| Saikano             | 1         | 1.18%   |
| G.Skill             | 1         | 1.18%   |
| Corsair             | 1         | 1.18%   |
| A-DATA Technology   | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 3.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.27%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 2.27%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 2         | 2.27%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 2.27%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.27%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 2.27%   |
| Samsung RAM K4AAG165WA-BCWE 8GB SODIMM DDR4 3200MT/s             | 2         | 2.27%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 2.27%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 2.27%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.14%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 1.14%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 1.14%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                        | 1         | 1.14%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 1.14%   |
| Unknown RAM Module 2GB DIMM                                      | 1         | 1.14%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 1.14%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 1         | 1.14%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.14%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 1.14%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.14%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                           | 1         | 1.14%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.14%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 1.14%   |
| Silicon Power RAM SP016GBLFU266B02 16GB DIMM DDR4 2667MT/s       | 1         | 1.14%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.14%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 1.14%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.14%   |
| Samsung RAM M471A5644EB0-CRC 2GB SODIMM DDR4 2400MT/s            | 1         | 1.14%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.14%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.14%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.14%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.14%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.14%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.14%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.14%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.14%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 1         | 1.14%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s              | 1         | 1.14%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s           | 1         | 1.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 34        | 47.89%  |
| DDR3    | 24        | 33.8%   |
| LPDDR4  | 6         | 8.45%   |
| SDRAM   | 3         | 4.23%   |
| LPDDR3  | 2         | 2.82%   |
| DDR5    | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 49        | 70%     |
| DIMM         | 14        | 20%     |
| Row Of Chips | 7         | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 27        | 35.06%  |
| 8192  | 24        | 31.17%  |
| 16384 | 12        | 15.58%  |
| 2048  | 10        | 12.99%  |
| 1024  | 3         | 3.9%    |
| 32768 | 1         | 1.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 17        | 21.79%  |
| 1600    | 17        | 21.79%  |
| 3200    | 14        | 17.95%  |
| 2400    | 8         | 10.26%  |
| 1333    | 4         | 5.13%   |
| 1334    | 3         | 3.85%   |
| 3600    | 2         | 2.56%   |
| 1867    | 2         | 2.56%   |
| 1067    | 2         | 2.56%   |
| Unknown | 2         | 2.56%   |
| 4800    | 1         | 1.28%   |
| 4267    | 1         | 1.28%   |
| 3266    | 1         | 1.28%   |
| 2200    | 1         | 1.28%   |
| 2133    | 1         | 1.28%   |
| 2048    | 1         | 1.28%   |
| 800     | 1         | 1.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Brother HL-1210W series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 19        | 22.09%  |
| IMC Networks                           | 11        | 12.79%  |
| Acer                                   | 9         | 10.47%  |
| Microdia                               | 7         | 8.14%   |
| Realtek Semiconductor                  | 6         | 6.98%   |
| Apple                                  | 6         | 6.98%   |
| Quanta                                 | 5         | 5.81%   |
| Sunplus Innovation Technology          | 3         | 3.49%   |
| Syntek                                 | 2         | 2.33%   |
| Logitech                               | 2         | 2.33%   |
| USB Camera                             | 1         | 1.16%   |
| Teslong Camera                         | 1         | 1.16%   |
| Suyin                                  | 1         | 1.16%   |
| Silicon Motion                         | 1         | 1.16%   |
| Ricoh                                  | 1         | 1.16%   |
| Primax Electronics                     | 1         | 1.16%   |
| Microsoft                              | 1         | 1.16%   |
| Luxvisions Innotech Limited            | 1         | 1.16%   |
| Lite-On Technology                     | 1         | 1.16%   |
| Jieli Technology                       | 1         | 1.16%   |
| Importek                               | 1         | 1.16%   |
| Goertek Electronics                    | 1         | 1.16%   |
| DJJHFA1BIF5595                         | 1         | 1.16%   |
| Creative Technology                    | 1         | 1.16%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.16%   |
| Alcor Micro                            | 1         | 1.16%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony integrated camera            | 3         | 3.45%   |
| Chicony HP Truevision HD             | 3         | 3.45%   |
| Acer HD Webcam                       | 3         | 3.45%   |
| Sunplus Integrated_Webcam_HD         | 2         | 2.3%    |
| Quanta HP TrueVision HD Camera       | 2         | 2.3%    |
| IMC Networks USB2.0 VGA UVC WebCam   | 2         | 2.3%    |
| IMC Networks USB2.0 HD UVC WebCam    | 2         | 2.3%    |
| IMC Networks Integrated Camera       | 2         | 2.3%    |
| Chicony USB2.0 Camera                | 2         | 2.3%    |
| Chicony TOSHIBA Web Camera - HD      | 2         | 2.3%    |
| Chicony Integrated Camera [ThinkPad] | 2         | 2.3%    |
| Chicony HD User Facing               | 2         | 2.3%    |
| Apple iPhone5/5C/5S/6                | 2         | 2.3%    |
| Apple Built-in iSight                | 2         | 2.3%    |
| Acer SunplusIT Integrated Camera     | 2         | 2.3%    |
| USB Camera USB Camera                | 1         | 1.15%   |
| Teslong Camera                       | 1         | 1.15%   |
| Syntek Lenovo EasyCamera             | 1         | 1.15%   |
| Syntek Integrated Camera             | 1         | 1.15%   |
| Suyin Acer CrystalEye Webcam         | 1         | 1.15%   |
| Sunplus SPCA2650 AV Camera           | 1         | 1.15%   |
| Silicon Motion WebCam SC-13HDL11939N | 1         | 1.15%   |
| Ricoh HD Webcam                      | 1         | 1.15%   |
| Realtek USB Camera                   | 1         | 1.15%   |
| Realtek Integrated_Webcam_HD         | 1         | 1.15%   |
| Realtek Integrated Webcam            | 1         | 1.15%   |
| Realtek Integrated Camera            | 1         | 1.15%   |
| Realtek HP Wide Vision HD Camera     | 1         | 1.15%   |
| Realtek HP Webcam                    | 1         | 1.15%   |
| Quanta VGA WebCam                    | 1         | 1.15%   |
| Quanta HP Wide Vision HD Camera      | 1         | 1.15%   |
| Quanta HD User Facing                | 1         | 1.15%   |
| Primax HP HD Webcam [Fixed]          | 1         | 1.15%   |
| Microsoft LifeCam Rear               | 1         | 1.15%   |
| Microsoft LifeCam Front              | 1         | 1.15%   |
| Microdia Webcam Vitade AF            | 1         | 1.15%   |
| Microdia USB 2.0 Camera              | 1         | 1.15%   |
| Microdia PC Microscope camera        | 1         | 1.15%   |
| Microdia Laptop_Integrated_Webcam_HD | 1         | 1.15%   |
| Microdia Laptop_Integrated_Webcam_2M | 1         | 1.15%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 42.86%  |
| Validity Sensors           | 6         | 28.57%  |
| Shenzhen Goodix Technology | 3         | 14.29%  |
| Upek                       | 1         | 4.76%   |
| Elan Microelectronics      | 1         | 4.76%   |
| AuthenTec                  | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown                                                   | 3         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 9.52%   |
| Synaptics  WBDI                                           | 2         | 9.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 9.52%   |
| Shenzhen Goodix  Fingerprint Device                       | 2         | 9.52%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 4.76%   |
| Validity Sensors Synaptics WBDI                           | 1         | 4.76%   |
| Validity Sensors Fingerprint scanner                      | 1         | 4.76%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 1         | 4.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 4.76%   |
| Elan ELAN:ARM-M4                                          | 1         | 4.76%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 5         | 62.5%   |
| SCM Microsystems | 1         | 12.5%   |
| OmniKey          | 1         | 12.5%   |
| Alcor Micro      | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 25%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 12.5%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 12.5%   |
| Broadcom 5880                                                                | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 65        | 54.62%  |
| 1     | 45        | 37.82%  |
| 2     | 8         | 6.72%   |
| 3     | 1         | 0.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 36.21%  |
| Net/wireless             | 15        | 25.86%  |
| Graphics card            | 8         | 13.79%  |
| Chipcard                 | 6         | 10.34%  |
| Multimedia controller    | 4         | 6.9%    |
| Storage                  | 1         | 1.72%   |
| Network                  | 1         | 1.72%   |
| Communication controller | 1         | 1.72%   |
| Bluetooth                | 1         | 1.72%   |

