Parrot - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Parrot.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot/Desktop/README.md) and [notebooks](/Dist/Parrot/Notebook/README.md).

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

Total: 467

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b50b1adb0f](https://linux-hardware.org/?probe=b50b1adb0f) | Sep 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1d04855f84](https://linux-hardware.org/?probe=1d04855f84) | Aug 29, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7439a7400d](https://linux-hardware.org/?probe=7439a7400d) | Aug 27, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [fa26302bd8](https://linux-hardware.org/?probe=fa26302bd8) | Aug 27, 2022 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| Standard      | Unknown                     | Notebook    | [782f229d6c](https://linux-hardware.org/?probe=782f229d6c) | Aug 17, 2022 |
| Panasonic     | CF-31JBGNNDM                | Notebook    | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [437387fdc3](https://linux-hardware.org/?probe=437387fdc3) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [47608d95ea](https://linux-hardware.org/?probe=47608d95ea) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [0bd14e553d](https://linux-hardware.org/?probe=0bd14e553d) | Aug 10, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [dae7cc7b69](https://linux-hardware.org/?probe=dae7cc7b69) | Aug 08, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [1a13c37dce](https://linux-hardware.org/?probe=1a13c37dce) | Aug 08, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a7e9a050ea](https://linux-hardware.org/?probe=a7e9a050ea) | Aug 02, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [1dca756b58](https://linux-hardware.org/?probe=1dca756b58) | Jul 31, 2022 |
| Dell          | Latitude E6420              | Notebook    | [a6b2ee6088](https://linux-hardware.org/?probe=a6b2ee6088) | Jul 30, 2022 |
| Gateway       | SX2855                      | Desktop     | [a896e3b0f7](https://linux-hardware.org/?probe=a896e3b0f7) | Jul 30, 2022 |
| HP            | 250 G2                      | Notebook    | [5650fd3dd6](https://linux-hardware.org/?probe=5650fd3dd6) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [26be63e8a0](https://linux-hardware.org/?probe=26be63e8a0) | Jul 25, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [0bacf44374](https://linux-hardware.org/?probe=0bacf44374) | Jul 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [007eeacf86](https://linux-hardware.org/?probe=007eeacf86) | Jul 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8ce974e537](https://linux-hardware.org/?probe=8ce974e537) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | Notebook    | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [4d3cf557ba](https://linux-hardware.org/?probe=4d3cf557ba) | Jul 23, 2022 |
| Lenovo        | Z40-70 80E6                 | Notebook    | [e77b84e593](https://linux-hardware.org/?probe=e77b84e593) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [90cf247d2d](https://linux-hardware.org/?probe=90cf247d2d) | Jul 20, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [7615eb5b46](https://linux-hardware.org/?probe=7615eb5b46) | Jul 20, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2d31c995c8](https://linux-hardware.org/?probe=2d31c995c8) | Jul 19, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [9e9ca5b39a](https://linux-hardware.org/?probe=9e9ca5b39a) | Jul 19, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0b20cb5b2f](https://linux-hardware.org/?probe=0b20cb5b2f) | Jul 18, 2022 |
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
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [8a96de43eb](https://linux-hardware.org/?probe=8a96de43eb) | Jul 08, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [fc35a0726c](https://linux-hardware.org/?probe=fc35a0726c) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| Samsung       | 930QDB                      | Convertible | [e022aed2bc](https://linux-hardware.org/?probe=e022aed2bc) | Jun 28, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8b55dcfd2d](https://linux-hardware.org/?probe=8b55dcfd2d) | Jun 28, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d4969dd4f5](https://linux-hardware.org/?probe=d4969dd4f5) | Jun 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [d1b8d3ff84](https://linux-hardware.org/?probe=d1b8d3ff84) | Jun 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6f3036d638](https://linux-hardware.org/?probe=6f3036d638) | Jun 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6348a01f19](https://linux-hardware.org/?probe=6348a01f19) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [656a452bc6](https://linux-hardware.org/?probe=656a452bc6) | Jun 21, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| Toshiba       | Satellite-L845              | Notebook    | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [39351344b4](https://linux-hardware.org/?probe=39351344b4) | Jun 14, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ffb41db26d](https://linux-hardware.org/?probe=ffb41db26d) | Jun 07, 2022 |
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
| Timi          | TM1613                      | Notebook    | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | Notebook    | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| HP            | 1495                        | Desktop     | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| HP            | 18E7                        | Desktop     | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cee28f4953](https://linux-hardware.org/?probe=cee28f4953) | Apr 12, 2022 |
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
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| Wistron       | JIG31B3                     | Desktop     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Positivo      | Q232A                       | Notebook    | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [36d17e4fdb](https://linux-hardware.org/?probe=36d17e4fdb) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [453d0816b3](https://linux-hardware.org/?probe=453d0816b3) | Mar 13, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | Notebook    | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | Notebook    | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| Dell          | Latitude XT2                | Notebook    | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
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
| Sony          | SVP1321L1EBI                | Notebook    | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| HP            | ProBook 4535s               | Notebook    | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | Notebook    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Unknown       | TB-4000                     | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | Notebook    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
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
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Precision M4600             | Notebook    | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | Notebook    | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| Toxic         | GM7MQ8P                     | Notebook    | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock        | Z87 Killer                  | Desktop     | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| Dell          | Latitude E6410              | Notebook    | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | Notebook    | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | Notebook    | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | Notebook    | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| HP            | Laptop 15q-dy0xxx           | Notebook    | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| Dell          | 0T2HR0 A00                  | Desktop     | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [eafc16e86f](https://linux-hardware.org/?probe=eafc16e86f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3eac62e012](https://linux-hardware.org/?probe=3eac62e012) | Sep 24, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| Dell          | Vostro 5470                 | Notebook    | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | Notebook    | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | Notebook    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b741d2ab2b](https://linux-hardware.org/?probe=b741d2ab2b) | Aug 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | Notebook    | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [f0f33cb33a](https://linux-hardware.org/?probe=f0f33cb33a) | Aug 06, 2021 |
| Dell          | Latitude E6420              | Notebook    | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [57037eb714](https://linux-hardware.org/?probe=57037eb714) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [89852ab731](https://linux-hardware.org/?probe=89852ab731) | Aug 05, 2021 |
| HP            | Pavilion dv7                | Notebook    | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | Notebook    | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| HP            | 1850                        | Desktop     | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell          | Latitude E7440              | Notebook    | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Dell          | Precision M6400             | Notebook    | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | Notebook    | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| HP            | 1850                        | Desktop     | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| MSI           | GE73 Raider RGB 8RE         | Notebook    | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | Notebook    | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | Notebook    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Intel         | NUC8i7HVB J68196-601        | Mini pc     | [d186af4ee3](https://linux-hardware.org/?probe=d186af4ee3) | May 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | Notebook    | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| Dell          | 0C1R19 A02                  | Desktop     | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| HP            | 8430 1000                   | All in one  | [5c5adcc248](https://linux-hardware.org/?probe=5c5adcc248) | Apr 24, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | Notebook    | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | Notebook    | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [a4bf4bb64c](https://linux-hardware.org/?probe=a4bf4bb64c) | Mar 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [489ed0f996](https://linux-hardware.org/?probe=489ed0f996) | Feb 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [a357eb71e0](https://linux-hardware.org/?probe=a357eb71e0) | Feb 22, 2021 |
| HP            | 339A                        | Desktop     | [b105e94284](https://linux-hardware.org/?probe=b105e94284) | Feb 20, 2021 |
| HP            | 339A                        | Desktop     | [3dfdd6aa5e](https://linux-hardware.org/?probe=3dfdd6aa5e) | Feb 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c337c59497](https://linux-hardware.org/?probe=c337c59497) | Feb 13, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284fd25f3e](https://linux-hardware.org/?probe=284fd25f3e) | Feb 11, 2021 |
| MSI           | B250M MORTAR                | Desktop     | [be8a65f362](https://linux-hardware.org/?probe=be8a65f362) | Feb 02, 2021 |
| Dell          | 0CU409                      | Desktop     | [64c8a84081](https://linux-hardware.org/?probe=64c8a84081) | Jan 29, 2021 |
| HP            | ENVY 15                     | Notebook    | [c39474b63f](https://linux-hardware.org/?probe=c39474b63f) | Jan 23, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [ea1a80dc34](https://linux-hardware.org/?probe=ea1a80dc34) | Jan 21, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [80dc10f323](https://linux-hardware.org/?probe=80dc10f323) | Jan 21, 2021 |
| Acer          | Aspire X3990                | Desktop     | [a3e9301c7f](https://linux-hardware.org/?probe=a3e9301c7f) | Jan 16, 2021 |
| Acer          | Aspire X3990                | Desktop     | [1660d13b44](https://linux-hardware.org/?probe=1660d13b44) | Jan 12, 2021 |
| HP            | 3047h                       | Desktop     | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| Dell          | Latitude 7390               | Notebook    | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| Medion        | MS-7621                     | Desktop     | [74c49730d1](https://linux-hardware.org/?probe=74c49730d1) | Dec 27, 2020 |
| Positivo      | POS-PIG43BC                 | Desktop     | [146c7d86bb](https://linux-hardware.org/?probe=146c7d86bb) | Dec 27, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [ab17ca4eef](https://linux-hardware.org/?probe=ab17ca4eef) | Dec 25, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | Notebook    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [33960a08de](https://linux-hardware.org/?probe=33960a08de) | Dec 20, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [748a6b0b09](https://linux-hardware.org/?probe=748a6b0b09) | Dec 16, 2020 |
| Dell          | Latitude E5440              | Notebook    | [7befb8e28b](https://linux-hardware.org/?probe=7befb8e28b) | Nov 29, 2020 |
| Dell          | Latitude E5440              | Notebook    | [3064211887](https://linux-hardware.org/?probe=3064211887) | Nov 28, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | Notebook    | [ce89f09531](https://linux-hardware.org/?probe=ce89f09531) | Nov 26, 2020 |
| HP            | 3047h                       | Desktop     | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [11f670b6b1](https://linux-hardware.org/?probe=11f670b6b1) | Nov 23, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [82be91a50a](https://linux-hardware.org/?probe=82be91a50a) | Nov 20, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [f86087eece](https://linux-hardware.org/?probe=f86087eece) | Nov 20, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [7918687a8b](https://linux-hardware.org/?probe=7918687a8b) | Nov 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [f95c24897c](https://linux-hardware.org/?probe=f95c24897c) | Oct 30, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [f7a2b660d8](https://linux-hardware.org/?probe=f7a2b660d8) | Oct 29, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [c687805b04](https://linux-hardware.org/?probe=c687805b04) | Oct 29, 2020 |
| ASUSTek       | X540YA                      | Notebook    | [501ca10eeb](https://linux-hardware.org/?probe=501ca10eeb) | Oct 25, 2020 |
| ECS           | A740GM-M                    | Desktop     | [423f49affd](https://linux-hardware.org/?probe=423f49affd) | Oct 25, 2020 |
| Dell          | Vostro 3558                 | Notebook    | [8f4f321359](https://linux-hardware.org/?probe=8f4f321359) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [8ce3caa35a](https://linux-hardware.org/?probe=8ce3caa35a) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [b2d5b6eb69](https://linux-hardware.org/?probe=b2d5b6eb69) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | Notebook    | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| HP            | Pavilion 17                 | Notebook    | [2a0d11caf1](https://linux-hardware.org/?probe=2a0d11caf1) | Oct 09, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [f06ac6483c](https://linux-hardware.org/?probe=f06ac6483c) | Oct 06, 2020 |
| Razer         | Blade Stealth               | Notebook    | [564265e066](https://linux-hardware.org/?probe=564265e066) | Oct 01, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [2bc8fbe372](https://linux-hardware.org/?probe=2bc8fbe372) | Sep 27, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [bb1615dd63](https://linux-hardware.org/?probe=bb1615dd63) | Sep 24, 2020 |
| System76      | Gazelle                     | Notebook    | [d96d5e60ae](https://linux-hardware.org/?probe=d96d5e60ae) | Sep 20, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [4ad16b3038](https://linux-hardware.org/?probe=4ad16b3038) | Sep 20, 2020 |
| Alienware     | 17 R4                       | Notebook    | [d58b082d72](https://linux-hardware.org/?probe=d58b082d72) | Sep 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d77bb0aa31](https://linux-hardware.org/?probe=d77bb0aa31) | Sep 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [951e2d1aa6](https://linux-hardware.org/?probe=951e2d1aa6) | Sep 18, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [f88025bc71](https://linux-hardware.org/?probe=f88025bc71) | Sep 16, 2020 |
| Dell          | Latitude 3400               | Notebook    | [f7d1872e51](https://linux-hardware.org/?probe=f7d1872e51) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [090d50eec1](https://linux-hardware.org/?probe=090d50eec1) | Sep 12, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [1e512df642](https://linux-hardware.org/?probe=1e512df642) | Sep 12, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Dell          | Latitude 3400               | Notebook    | [825d226ad5](https://linux-hardware.org/?probe=825d226ad5) | Sep 10, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [fc23c05e20](https://linux-hardware.org/?probe=fc23c05e20) | Sep 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS4MH00    | Notebook    | [3e6177e73c](https://linux-hardware.org/?probe=3e6177e73c) | Sep 01, 2020 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [affb4f7587](https://linux-hardware.org/?probe=affb4f7587) | Aug 29, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [c87fcab7c7](https://linux-hardware.org/?probe=c87fcab7c7) | Aug 26, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [608ad8477d](https://linux-hardware.org/?probe=608ad8477d) | Aug 22, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [dbf4ca0908](https://linux-hardware.org/?probe=dbf4ca0908) | Aug 10, 2020 |
| Sony          | VPCCB15FG                   | Notebook    | [4d93dfd9c0](https://linux-hardware.org/?probe=4d93dfd9c0) | Aug 09, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [c4ba9dc0dc](https://linux-hardware.org/?probe=c4ba9dc0dc) | Aug 05, 2020 |
| HP            | Notebook                    | Notebook    | [989b6b7d5d](https://linux-hardware.org/?probe=989b6b7d5d) | Aug 04, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [359a7266e5](https://linux-hardware.org/?probe=359a7266e5) | Aug 03, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [bfffb28472](https://linux-hardware.org/?probe=bfffb28472) | Jul 27, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [53b70e68df](https://linux-hardware.org/?probe=53b70e68df) | Jul 27, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f032f63f3a](https://linux-hardware.org/?probe=f032f63f3a) | Jul 26, 2020 |
| HP            | Notebook                    | Notebook    | [ee51b68070](https://linux-hardware.org/?probe=ee51b68070) | Jul 23, 2020 |
| HP            | Notebook                    | Notebook    | [87cfa4c37e](https://linux-hardware.org/?probe=87cfa4c37e) | Jul 23, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [3177a50194](https://linux-hardware.org/?probe=3177a50194) | Jul 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Acer          | Aspire V5-122P              | Notebook    | [a362dee702](https://linux-hardware.org/?probe=a362dee702) | Jul 10, 2020 |
| Dell          | Latitude 7480               | Notebook    | [aab5a5b50a](https://linux-hardware.org/?probe=aab5a5b50a) | Jul 07, 2020 |
| eMachines     | eME728                      | Notebook    | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [3c48dbb383](https://linux-hardware.org/?probe=3c48dbb383) | Jul 05, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [1d8d1db67e](https://linux-hardware.org/?probe=1d8d1db67e) | Jul 04, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [06e9599063](https://linux-hardware.org/?probe=06e9599063) | Jul 04, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [dda8536e62](https://linux-hardware.org/?probe=dda8536e62) | Jun 11, 2020 |
| Dell          | G7 7790                     | Notebook    | [506d29b806](https://linux-hardware.org/?probe=506d29b806) | Jun 02, 2020 |
| Dell          | G7 7790                     | Notebook    | [0551762cbb](https://linux-hardware.org/?probe=0551762cbb) | Jun 02, 2020 |
| Biostar       | H77MU3                      | Desktop     | [048ffba01b](https://linux-hardware.org/?probe=048ffba01b) | May 24, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [7c05b67968](https://linux-hardware.org/?probe=7c05b67968) | May 22, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [fc8bf8a5a6](https://linux-hardware.org/?probe=fc8bf8a5a6) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [d417dd63dd](https://linux-hardware.org/?probe=d417dd63dd) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [88d722fa1b](https://linux-hardware.org/?probe=88d722fa1b) | May 22, 2020 |
| ASUSTek       | X75VB                       | Notebook    | [f41d9b003f](https://linux-hardware.org/?probe=f41d9b003f) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [96ec25db7c](https://linux-hardware.org/?probe=96ec25db7c) | May 21, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [b2ecb833ba](https://linux-hardware.org/?probe=b2ecb833ba) | May 21, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5e5d0a24f3](https://linux-hardware.org/?probe=5e5d0a24f3) | May 15, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [0d48c76bfd](https://linux-hardware.org/?probe=0d48c76bfd) | May 11, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5a56c30293](https://linux-hardware.org/?probe=5a56c30293) | May 06, 2020 |
| ASUSTek       | X442URR                     | Notebook    | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| HP            | ProBook 6475b               | Notebook    | [c9ee4e6614](https://linux-hardware.org/?probe=c9ee4e6614) | May 03, 2020 |
| HP            | ProBook 6475b               | Notebook    | [06da2207cd](https://linux-hardware.org/?probe=06da2207cd) | May 02, 2020 |
| HP            | ProBook 6475b               | Notebook    | [b2ff4072ce](https://linux-hardware.org/?probe=b2ff4072ce) | May 02, 2020 |
| Toshiba       | Satellite L300D             | Notebook    | [5a320c4b78](https://linux-hardware.org/?probe=5a320c4b78) | May 02, 2020 |
| Dell          | 05DN3X A00                  | Desktop     | [7424c0caba](https://linux-hardware.org/?probe=7424c0caba) | May 02, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [3dc6534b5f](https://linux-hardware.org/?probe=3dc6534b5f) | May 01, 2020 |
| Dell          | Latitude E6420              | Notebook    | [ae3ade27d7](https://linux-hardware.org/?probe=ae3ade27d7) | Apr 29, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6835f4fe95](https://linux-hardware.org/?probe=6835f4fe95) | Apr 28, 2020 |
| Dell          | Latitude E6420              | Notebook    | [83380135bc](https://linux-hardware.org/?probe=83380135bc) | Apr 27, 2020 |
| Dell          | Latitude E6420              | Notebook    | [12c77f16d5](https://linux-hardware.org/?probe=12c77f16d5) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [6e636c5fd2](https://linux-hardware.org/?probe=6e636c5fd2) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [d19700bc2d](https://linux-hardware.org/?probe=d19700bc2d) | Apr 27, 2020 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [72dcfa02ca](https://linux-hardware.org/?probe=72dcfa02ca) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [37c314650f](https://linux-hardware.org/?probe=37c314650f) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [9a9b368a7c](https://linux-hardware.org/?probe=9a9b368a7c) | Apr 26, 2020 |
| Dell          | XPS 12-9Q33                 | Notebook    | [f831495ef5](https://linux-hardware.org/?probe=f831495ef5) | Apr 25, 2020 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [6bf9d537a8](https://linux-hardware.org/?probe=6bf9d537a8) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [c54d518ca7](https://linux-hardware.org/?probe=c54d518ca7) | Apr 15, 2020 |
| ASUSTek       | K31CD-K                     | Desktop     | [b4ad316fa2](https://linux-hardware.org/?probe=b4ad316fa2) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [661761d2ca](https://linux-hardware.org/?probe=661761d2ca) | Apr 14, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [100d4bacdc](https://linux-hardware.org/?probe=100d4bacdc) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [5512733c4a](https://linux-hardware.org/?probe=5512733c4a) | Apr 14, 2020 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [93da68c7fb](https://linux-hardware.org/?probe=93da68c7fb) | Apr 12, 2020 |
| Dell          | Inspiron 5721               | Notebook    | [23d5dff3bd](https://linux-hardware.org/?probe=23d5dff3bd) | Apr 11, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| Samsung       | RV415/RV515                 | Notebook    | [3b9248b95f](https://linux-hardware.org/?probe=3b9248b95f) | Mar 31, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [224ebfd9b3](https://linux-hardware.org/?probe=224ebfd9b3) | Mar 30, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [79e98a64cf](https://linux-hardware.org/?probe=79e98a64cf) | Mar 30, 2020 |
| Lenovo        | ThinkPad T440s 20ARS01C0... | Notebook    | [aa9f421079](https://linux-hardware.org/?probe=aa9f421079) | Mar 23, 2020 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [cf7e8cd869](https://linux-hardware.org/?probe=cf7e8cd869) | Mar 16, 2020 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [05f8c8eef4](https://linux-hardware.org/?probe=05f8c8eef4) | Feb 29, 2020 |
| HP            | Laptop 17-by0xxx            | Notebook    | [21c7ac4323](https://linux-hardware.org/?probe=21c7ac4323) | Feb 17, 2020 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [dd543cf29b](https://linux-hardware.org/?probe=dd543cf29b) | Feb 09, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [2bfc7eae61](https://linux-hardware.org/?probe=2bfc7eae61) | Feb 06, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [1e8ccbe5b9](https://linux-hardware.org/?probe=1e8ccbe5b9) | Feb 04, 2020 |
| Notebook      | W510TU                      | Notebook    | [987d9232fe](https://linux-hardware.org/?probe=987d9232fe) | Jan 31, 2020 |
| Notebook      | W510TU                      | Notebook    | [4556eb747b](https://linux-hardware.org/?probe=4556eb747b) | Jan 31, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [8b7c621317](https://linux-hardware.org/?probe=8b7c621317) | Jan 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [38658290e2](https://linux-hardware.org/?probe=38658290e2) | Jan 19, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [05e5552eea](https://linux-hardware.org/?probe=05e5552eea) | Jan 19, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [375040e90b](https://linux-hardware.org/?probe=375040e90b) | Jan 05, 2020 |
| Notebook      | W510TU                      | Notebook    | [aa2e59fd60](https://linux-hardware.org/?probe=aa2e59fd60) | Dec 25, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [1a26d7b485](https://linux-hardware.org/?probe=1a26d7b485) | Dec 21, 2019 |
| Notebook      | W510TU                      | Notebook    | [f2102dfe5b](https://linux-hardware.org/?probe=f2102dfe5b) | Dec 09, 2019 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [51389e5c4a](https://linux-hardware.org/?probe=51389e5c4a) | Dec 07, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [73a28279bc](https://linux-hardware.org/?probe=73a28279bc) | Dec 05, 2019 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [7bc298d7af](https://linux-hardware.org/?probe=7bc298d7af) | Nov 10, 2019 |
| HP            | 630                         | Notebook    | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| Acer          | Aspire E5-475               | Notebook    | [3e3fad10fe](https://linux-hardware.org/?probe=3e3fad10fe) | Aug 18, 2019 |
| Gateway       | NE-522                      | Notebook    | [d562b598e5](https://linux-hardware.org/?probe=d562b598e5) | Aug 10, 2019 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [c0c73d01ba](https://linux-hardware.org/?probe=c0c73d01ba) | Jun 08, 2019 |
| Apple         | MacBookPro11,4              | Notebook    | [49a28f87b9](https://linux-hardware.org/?probe=49a28f87b9) | May 21, 2019 |
| Acer          | Swift SF314-54              | Notebook    | [89013e65ec](https://linux-hardware.org/?probe=89013e65ec) | Apr 26, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| Dell          | Latitude E7440              | Notebook    | [ce392df9c0](https://linux-hardware.org/?probe=ce392df9c0) | Dec 26, 2018 |
| HP            | Pavilion 15                 | Notebook    | [921bec751d](https://linux-hardware.org/?probe=921bec751d) | Oct 13, 2018 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [597e65c2a4](https://linux-hardware.org/?probe=597e65c2a4) | Jan 07, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Parrot 5.0   | 116       | 34.83%  |
| Parrot 4.11  | 87        | 26.13%  |
| Parrot 4.10  | 59        | 17.72%  |
| Parrot 4.8   | 23        | 6.91%   |
| Parrot 4.9   | 22        | 6.61%   |
| Parrot 4.7   | 13        | 3.9%    |
| Parrot 5.1   | 7         | 2.1%    |
| Parrot 4.6   | 2         | 0.6%    |
| Parrot 4.5   | 1         | 0.3%    |
| Parrot 4.4   | 1         | 0.3%    |
| Parrot 4.2.2 | 1         | 0.3%    |
| Parrot 3.10  | 1         | 0.3%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Parrot | 317       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.0-12parrot1-amd64   | 53        | 15.54%  |
| 5.14.0-9parrot1-amd64    | 52        | 15.25%  |
| 5.7.0-2parrot2-amd64     | 33        | 9.68%   |
| 5.10.0-6parrot1-amd64    | 32        | 9.38%   |
| 5.5.0-1parrot1-amd64     | 24        | 7.04%   |
| 5.10.0-8parrot1-amd64    | 18        | 5.28%   |
| 5.18.0-1parrot1-amd64    | 17        | 4.99%   |
| 5.4.0-4parrot1-amd64     | 16        | 4.69%   |
| 5.15.0-15parrot1-amd64   | 11        | 3.23%   |
| 5.6.0-2parrot1-amd64     | 10        | 2.93%   |
| 5.14.0-2parrot1-amd64    | 10        | 2.93%   |
| 5.9.0-2parrot1-amd64     | 9         | 2.64%   |
| 5.18.0-14parrot1-amd64   | 6         | 1.76%   |
| 5.8.0-2parrot1-amd64     | 5         | 1.47%   |
| 5.4.0-2parrot1-amd64     | 5         | 1.47%   |
| 5.10.0-3parrot1-amd64    | 5         | 1.47%   |
| 5.8.0-1parrot1-amd64     | 4         | 1.17%   |
| 5.10.0-5parrot1-amd64    | 4         | 1.17%   |
| 5.4.0-3parrot1-amd64     | 3         | 0.88%   |
| 5.3.0-3parrot3-amd64     | 3         | 0.88%   |
| 5.2.0-2parrot1-amd64     | 3         | 0.88%   |
| 4.19.0-parrot4-28t-amd64 | 3         | 0.88%   |
| 4.18.0-parrot10-amd64    | 2         | 0.59%   |
| 5.7.0-rc6-galliumos      | 1         | 0.29%   |
| 5.4.0-2parrot1-686-pae   | 1         | 0.29%   |
| 5.4.0-1parrot1-amd64     | 1         | 0.29%   |
| 5.3.0-3parrot3-686-pae   | 1         | 0.29%   |
| 5.3.0-1parrot1-amd64     | 1         | 0.29%   |
| 5.16.0-12parrot1-686-pae | 1         | 0.29%   |
| 5.15.0-5parrot1-amd64    | 1         | 0.29%   |
| 5.10.0-kali6-amd64       | 1         | 0.29%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 0.29%   |
| 5.1.0-parrot1-3t-amd64   | 1         | 0.29%   |
| 4.19.0-parrot1-13t-amd64 | 1         | 0.29%   |
| 4.14.0-parrot7-amd64     | 1         | 0.29%   |
| Unknown                  | 1         | 0.29%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 61        | 18.05%  |
| 5.14.0  | 60        | 17.75%  |
| 5.16.0  | 54        | 15.98%  |
| 5.7.0   | 34        | 10.06%  |
| 5.4.0   | 26        | 7.69%   |
| 5.5.0   | 24        | 7.1%    |
| 5.18.0  | 22        | 6.51%   |
| 5.15.0  | 12        | 3.55%   |
| 5.6.0   | 10        | 2.96%   |
| 5.9.0   | 9         | 2.66%   |
| 5.8.0   | 9         | 2.66%   |
| 5.3.0   | 5         | 1.48%   |
| 4.19.0  | 4         | 1.18%   |
| 5.2.0   | 3         | 0.89%   |
| 4.18.0  | 2         | 0.59%   |
| 5.1.0   | 1         | 0.3%    |
| 4.14.0  | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 61        | 18.05%  |
| 5.14    | 60        | 17.75%  |
| 5.16    | 54        | 15.98%  |
| 5.7     | 34        | 10.06%  |
| 5.4     | 26        | 7.69%   |
| 5.5     | 24        | 7.1%    |
| 5.18    | 22        | 6.51%   |
| 5.15    | 12        | 3.55%   |
| 5.6     | 10        | 2.96%   |
| 5.9     | 9         | 2.66%   |
| 5.8     | 9         | 2.66%   |
| 5.3     | 5         | 1.48%   |
| 4.19    | 4         | 1.18%   |
| 5.2     | 3         | 0.89%   |
| 4.18    | 2         | 0.59%   |
| 5.1     | 1         | 0.3%    |
| 4.14    | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 315       | 99.37%  |
| i686   | 2         | 0.63%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| MATE          | 208       | 63.8%   |
| KDE5          | 63        | 19.33%  |
| Unknown       | 21        | 6.44%   |
| KDE           | 20        | 6.13%   |
| XFCE          | 9         | 2.76%   |
| GNOME         | 2         | 0.61%   |
| LXDE          | 1         | 0.31%   |
| GNOME Classic | 1         | 0.31%   |
| Cinnamon      | 1         | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 311       | 98.11%  |
| Wayland | 3         | 0.95%   |
| Tty     | 2         | 0.63%   |
| Unknown | 1         | 0.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 127       | 39.08%  |
| Unknown | 115       | 35.38%  |
| TDM     | 71        | 21.85%  |
| GDM     | 7         | 2.15%   |
| SDDM    | 5         | 1.54%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 169       | 53.14%  |
| en_GB   | 23        | 7.23%   |
| fr_FR   | 15        | 4.72%   |
| Unknown | 14        | 4.4%    |
| ru_RU   | 11        | 3.46%   |
| es_ES   | 11        | 3.46%   |
| de_DE   | 10        | 3.14%   |
| pt_BR   | 9         | 2.83%   |
| pl_PL   | 9         | 2.83%   |
| en_IN   | 7         | 2.2%    |
| en_AU   | 7         | 2.2%    |
| it_IT   | 4         | 1.26%   |
| cs_CZ   | 3         | 0.94%   |
| es_MX   | 2         | 0.63%   |
| en_HK   | 2         | 0.63%   |
| en_DK   | 2         | 0.63%   |
| en_CA   | 2         | 0.63%   |
| tr_TR   | 1         | 0.31%   |
| ru_UA   | 1         | 0.31%   |
| pt_PT   | 1         | 0.31%   |
| nl_BE   | 1         | 0.31%   |
| mk_MK   | 1         | 0.31%   |
| id_ID   | 1         | 0.31%   |
| fr_CA   | 1         | 0.31%   |
| fi_FI   | 1         | 0.31%   |
| es_PE   | 1         | 0.31%   |
| es_CO   | 1         | 0.31%   |
| es_CL   | 1         | 0.31%   |
| es_AR   | 1         | 0.31%   |
| en_ZA   | 1         | 0.31%   |
| en_NZ   | 1         | 0.31%   |
| en_NG   | 1         | 0.31%   |
| de_AT   | 1         | 0.31%   |
| C       | 1         | 0.31%   |
| an_ES   | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 206       | 63.98%  |
| EFI  | 116       | 36.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 242       | 75.16%  |
| Ext4    | 54        | 16.77%  |
| Xfs     | 10        | 3.11%   |
| Overlay | 9         | 2.8%    |
| Unknown | 7         | 2.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 148       | 45.68%  |
| GPT     | 118       | 36.42%  |
| MBR     | 58        | 17.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 279       | 86.38%  |
| Yes       | 44        | 13.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 211       | 65.94%  |
| Yes       | 109       | 34.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 62        | 19.56%  |
| Dell                  | 48        | 15.14%  |
| Lenovo                | 46        | 14.51%  |
| ASUSTek Computer      | 44        | 13.88%  |
| Acer                  | 19        | 5.99%   |
| MSI                   | 13        | 4.1%    |
| Apple                 | 10        | 3.15%   |
| Gigabyte Technology   | 9         | 2.84%   |
| Toshiba               | 7         | 2.21%   |
| Samsung Electronics   | 5         | 1.58%   |
| Sony                  | 3         | 0.95%   |
| Microsoft             | 3         | 0.95%   |
| HUAWEI                | 3         | 0.95%   |
| Gateway               | 3         | 0.95%   |
| Fujitsu               | 3         | 0.95%   |
| Foxconn               | 3         | 0.95%   |
| ASRock                | 3         | 0.95%   |
| Alienware             | 3         | 0.95%   |
| Unknown               | 3         | 0.95%   |
| Razer                 | 2         | 0.63%   |
| Positivo              | 2         | 0.63%   |
| ECS                   | 2         | 0.63%   |
| ZOTAC                 | 1         | 0.32%   |
| Wortmann AG           | 1         | 0.32%   |
| Wistron               | 1         | 0.32%   |
| Toxic                 | 1         | 0.32%   |
| Timi                  | 1         | 0.32%   |
| System76              | 1         | 0.32%   |
| Standard              | 1         | 0.32%   |
| Positivo Bahia - VAIO | 1         | 0.32%   |
| Panasonic             | 1         | 0.32%   |
| Notebook              | 1         | 0.32%   |
| Metabox               | 1         | 0.32%   |
| Jumper                | 1         | 0.32%   |
| Intel                 | 1         | 0.32%   |
| GPU Company           | 1         | 0.32%   |
| Google                | 1         | 0.32%   |
| eMachines             | 1         | 0.32%   |
| Eluktronics           | 1         | 0.32%   |
| Digma                 | 1         | 0.32%   |
| Daewoo Lucoms         | 1         | 0.32%   |
| Chuwi                 | 1         | 0.32%   |
| Biostar               | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                               | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown                                            | 5         | 1.58%   |
| MSI Modern 15 A5M                                  | 3         | 0.95%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 3         | 0.95%   |
| HP Notebook                                        | 3         | 0.95%   |
| HP ENVY x360 Convertible 13-bd0xxx                 | 3         | 0.95%   |
| HP EliteBook 8470p                                 | 3         | 0.95%   |
| Dell Latitude E6420                                | 3         | 0.95%   |
| Dell Inspiron MM061                                | 3         | 0.95%   |
| Microsoft Surface Pro 3                            | 2         | 0.63%   |
| HP ProDesk 600 G1 SFF                              | 2         | 0.63%   |
| HP ProBook 650 G1                                  | 2         | 0.63%   |
| HP Pavilion dv6                                    | 2         | 0.63%   |
| HP Pavilion 15                                     | 2         | 0.63%   |
| Gigabyte AX370-Gaming                              | 2         | 0.63%   |
| Foxconn s5710t                                     | 2         | 0.63%   |
| Dell Latitude E7440                                | 2         | 0.63%   |
| Dell Latitude E6410                                | 2         | 0.63%   |
| Dell Inspiron 5676                                 | 2         | 0.63%   |
| ASUS Q524UQ                                        | 2         | 0.63%   |
| ASUS M5A78L-M/USB3                                 | 2         | 0.63%   |
| ASUS H110I-PLUS                                    | 2         | 0.63%   |
| ASUS Basic 3221BM                                  | 2         | 0.63%   |
| Apple MacBookPro8,1                                | 2         | 0.63%   |
| Acer Nitro AN515-54                                | 2         | 0.63%   |
| Wortmann AG TERRA_MOBILE_1542                      | 1         | 0.32%   |
| Wistron FMVDD2A0H0                                 | 1         | 0.32%   |
| Toxic GM7MQ8P                                      | 1         | 0.32%   |
| Toshiba Satellite-L845                             | 1         | 0.32%   |
| Toshiba Satellite L775D                            | 1         | 0.32%   |
| Toshiba Satellite L750                             | 1         | 0.32%   |
| Toshiba Satellite L655                             | 1         | 0.32%   |
| Toshiba Satellite L300D                            | 1         | 0.32%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 0.32%   |
| Toshiba Satellite C75D-B                           | 1         | 0.32%   |
| Timi TM1613                                        | 1         | 0.32%   |
| System76 Gazelle                                   | 1         | 0.32%   |
| Sony VPCSB1C5E                                     | 1         | 0.32%   |
| Sony VPCCB15FG                                     | 1         | 0.32%   |
| Sony SVP1321L1EBI                                  | 1         | 0.32%   |
| Samsung RV415/RV515                                | 1         | 0.32%   |
| Samsung 930QDB                                     | 1         | 0.32%   |
| Samsung 550P5C/550P7C                              | 1         | 0.32%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                | 1         | 0.32%   |
| Samsung 300E4C/300E5C/300E7C                       | 1         | 0.32%   |
| Razer Blade Stealth                                | 1         | 0.32%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.32%   |
| Positivo Q232A                                     | 1         | 0.32%   |
| Positivo POS-PIG43BC                               | 1         | 0.32%   |
| Positivo Bahia - VAIO VJFE51F11X-B0111H            | 1         | 0.32%   |
| Panasonic CF-31JBGNNDM                             | 1         | 0.32%   |
| Notebook W510TU                                    | 1         | 0.32%   |
| MSI MS-7C02                                        | 1         | 0.32%   |
| MSI MS-7A69                                        | 1         | 0.32%   |
| MSI MS-7A34                                        | 1         | 0.32%   |
| MSI MS-7529                                        | 1         | 0.32%   |
| MSI GT60 2OC/2OD                                   | 1         | 0.32%   |
| MSI GE75 Raider 10SF                               | 1         | 0.32%   |
| MSI GE73 Raider RGB 8RE                            | 1         | 0.32%   |
| MSI GE63 Raider RGB 8RE                            | 1         | 0.32%   |
| MSI GE62 6QE                                       | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo ThinkPad                         | 20        | 6.31%   |
| Dell Inspiron                           | 17        | 5.36%   |
| Dell Latitude                           | 16        | 5.05%   |
| HP Pavilion                             | 15        | 4.73%   |
| Lenovo IdeaPad                          | 11        | 3.47%   |
| HP ENVY                                 | 9         | 2.84%   |
| HP EliteBook                            | 9         | 2.84%   |
| Acer Aspire                             | 9         | 2.84%   |
| HP Laptop                               | 7         | 2.21%   |
| Toshiba Satellite                       | 6         | 1.89%   |
| HP ProBook                              | 5         | 1.58%   |
| HP Compaq                               | 5         | 1.58%   |
| Dell OptiPlex                           | 5         | 1.58%   |
| Unknown                                 | 5         | 1.58%   |
| ASUS VivoBook                           | 4         | 1.26%   |
| Acer Nitro                              | 4         | 1.26%   |
| MSI Modern                              | 3         | 0.95%   |
| Microsoft Surface                       | 3         | 0.95%   |
| HP Notebook                             | 3         | 0.95%   |
| Fujitsu LIFEBOOK                        | 3         | 0.95%   |
| Dell Vostro                             | 3         | 0.95%   |
| ASUS ROG                                | 3         | 0.95%   |
| ASUS PRIME                              | 3         | 0.95%   |
| Acer Predator                           | 3         | 0.95%   |
| Razer Blade                             | 2         | 0.63%   |
| Lenovo Yoga                             | 2         | 0.63%   |
| HP ZBook                                | 2         | 0.63%   |
| HP ProDesk                              | 2         | 0.63%   |
| HP 250                                  | 2         | 0.63%   |
| Gigabyte AX370-Gaming                   | 2         | 0.63%   |
| Foxconn s5710t                          | 2         | 0.63%   |
| Dell XPS                                | 2         | 0.63%   |
| Dell Precision                          | 2         | 0.63%   |
| ASUS TUF                                | 2         | 0.63%   |
| ASUS Q524UQ                             | 2         | 0.63%   |
| ASUS M5A78L-M                           | 2         | 0.63%   |
| ASUS H110I-PLUS                         | 2         | 0.63%   |
| ASUS Basic                              | 2         | 0.63%   |
| Apple MacBookPro8                       | 2         | 0.63%   |
| Apple MacBookPro11                      | 2         | 0.63%   |
| Acer Swift                              | 2         | 0.63%   |
| Wortmann AG TERRA                       | 1         | 0.32%   |
| Wistron FMVDD2A0H0                      | 1         | 0.32%   |
| Toxic GM7MQ8P                           | 1         | 0.32%   |
| Toshiba Satellite-L845                  | 1         | 0.32%   |
| Timi TM1613                             | 1         | 0.32%   |
| System76 Gazelle                        | 1         | 0.32%   |
| Sony VPCSB1C5E                          | 1         | 0.32%   |
| Sony VPCCB15FG                          | 1         | 0.32%   |
| Sony SVP1321L1EBI                       | 1         | 0.32%   |
| Samsung RV415                           | 1         | 0.32%   |
| Samsung 930QDB                          | 1         | 0.32%   |
| Samsung 550P5C                          | 1         | 0.32%   |
| Samsung 350V5C                          | 1         | 0.32%   |
| Samsung 300E4C                          | 1         | 0.32%   |
| Positivo Q232A                          | 1         | 0.32%   |
| Positivo POS-PIG43BC                    | 1         | 0.32%   |
| Positivo Bahia - VAIO VJFE51F11X-B0111H | 1         | 0.32%   |
| Panasonic CF-31JBGNNDM                  | 1         | 0.32%   |
| Notebook W510TU                         | 1         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 38        | 11.99%  |
| 2019 | 34        | 10.73%  |
| 2013 | 33        | 10.41%  |
| 2018 | 29        | 9.15%   |
| 2021 | 26        | 8.2%    |
| 2020 | 24        | 7.57%   |
| 2016 | 23        | 7.26%   |
| 2012 | 22        | 6.94%   |
| 2017 | 21        | 6.62%   |
| 2014 | 15        | 4.73%   |
| 2010 | 14        | 4.42%   |
| 2015 | 13        | 4.1%    |
| 2007 | 7         | 2.21%   |
| 2008 | 6         | 1.89%   |
| 2009 | 5         | 1.58%   |
| 2006 | 4         | 1.26%   |
| 2022 | 3         | 0.95%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 223       | 70.35%  |
| Desktop     | 75        | 23.66%  |
| Convertible | 13        | 4.1%    |
| Tablet      | 4         | 1.26%   |
| Mini pc     | 1         | 0.32%   |
| All in one  | 1         | 0.32%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 317       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 316       | 99.68%  |
| Yes  | 1         | 0.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 80        | 25%     |
| 8.01-16.0   | 69        | 21.56%  |
| 16.01-24.0  | 68        | 21.25%  |
| 3.01-4.0    | 55        | 17.19%  |
| 32.01-64.0  | 24        | 7.5%    |
| 1.01-2.0    | 10        | 3.13%   |
| 64.01-256.0 | 7         | 2.19%   |
| 24.01-32.0  | 4         | 1.25%   |
| 2.01-3.0    | 3         | 0.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 111       | 33.13%  |
| 2.01-3.0   | 110       | 32.84%  |
| 3.01-4.0   | 48        | 14.33%  |
| 4.01-8.0   | 42        | 12.54%  |
| 0.51-1.0   | 15        | 4.48%   |
| 8.01-16.0  | 7         | 2.09%   |
| 16.01-24.0 | 1         | 0.3%    |
| 0.01-0.5   | 1         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 187       | 57.89%  |
| 2      | 104       | 32.2%   |
| 3      | 22        | 6.81%   |
| 4      | 5         | 1.55%   |
| 5      | 3         | 0.93%   |
| 6      | 1         | 0.31%   |
| 0      | 1         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 215       | 67.19%  |
| Yes       | 105       | 32.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 263       | 82.45%  |
| No        | 56        | 17.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 293       | 91.85%  |
| No        | 26        | 8.15%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 220       | 68.54%  |
| No        | 101       | 31.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 106       | 33.02%  |
| Germany         | 21        | 6.54%   |
| Spain           | 15        | 4.67%   |
| France          | 13        | 4.05%   |
| Brazil          | 13        | 4.05%   |
| UK              | 12        | 3.74%   |
| Russia          | 11        | 3.43%   |
| Netherlands     | 11        | 3.43%   |
| India           | 9         | 2.8%    |
| Mexico          | 7         | 2.18%   |
| Italy           | 7         | 2.18%   |
| Canada          | 7         | 2.18%   |
| Australia       | 6         | 1.87%   |
| Sweden          | 4         | 1.25%   |
| Poland          | 4         | 1.25%   |
| Kenya           | 4         | 1.25%   |
| Indonesia       | 4         | 1.25%   |
| Denmark         | 4         | 1.25%   |
| Czechia         | 4         | 1.25%   |
| South Africa    | 3         | 0.93%   |
| Iraq            | 3         | 0.93%   |
| Bangladesh      | 3         | 0.93%   |
| Austria         | 3         | 0.93%   |
| Algeria         | 3         | 0.93%   |
| Turkey          | 2         | 0.62%   |
| Switzerland     | 2         | 0.62%   |
| Puerto Rico     | 2         | 0.62%   |
| Portugal        | 2         | 0.62%   |
| Pakistan        | 2         | 0.62%   |
| Nepal           | 2         | 0.62%   |
| Morocco         | 2         | 0.62%   |
| Hong Kong       | 2         | 0.62%   |
| Finland         | 2         | 0.62%   |
| Belgium         | 2         | 0.62%   |
| Vietnam         | 1         | 0.31%   |
| Ukraine         | 1         | 0.31%   |
| Romania         | 1         | 0.31%   |
| Peru            | 1         | 0.31%   |
| North Macedonia | 1         | 0.31%   |
| Nigeria         | 1         | 0.31%   |
| New Zealand     | 1         | 0.31%   |
| Myanmar         | 1         | 0.31%   |
| Mongolia        | 1         | 0.31%   |
| Latvia          | 1         | 0.31%   |
| Hungary         | 1         | 0.31%   |
| Greece          | 1         | 0.31%   |
| Georgia         | 1         | 0.31%   |
| Egypt           | 1         | 0.31%   |
| Croatia         | 1         | 0.31%   |
| Costa Rica      | 1         | 0.31%   |
| Colombia        | 1         | 0.31%   |
| Chile           | 1         | 0.31%   |
| Bulgaria        | 1         | 0.31%   |
| Benin           | 1         | 0.31%   |
| Belarus         | 1         | 0.31%   |
| Azerbaijan      | 1         | 0.31%   |
| Argentina       | 1         | 0.31%   |
| Unknown         | 1         | 0.31%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Amsterdam           | 5         | 1.5%    |
| Nairobi             | 4         | 1.2%    |
| Madrid              | 4         | 1.2%    |
| Dallas              | 4         | 1.2%    |
| Vienna              | 3         | 0.9%    |
| Sydney              | 3         | 0.9%    |
| Seattle             | 3         | 0.9%    |
| Melbourne           | 3         | 0.9%    |
| Los Angeles         | 3         | 0.9%    |
| Indianapolis        | 3         | 0.9%    |
| Eugene              | 3         | 0.9%    |
| Chicago             | 3         | 0.9%    |
| Berlin              | 3         | 0.9%    |
| Barcelona           | 3         | 0.9%    |
| Atlanta             | 3         | 0.9%    |
| Zurich              | 2         | 0.6%    |
| Warsaw              | 2         | 0.6%    |
| Uherské Hradiště | 2         | 0.6%    |
| Tangier             | 2         | 0.6%    |
| Stockholm           | 2         | 0.6%    |
| St Petersburg       | 2         | 0.6%    |
| Sao Paulo           | 2         | 0.6%    |
| Saint Paul          | 2         | 0.6%    |
| Ruskin              | 2         | 0.6%    |
| Pretoria            | 2         | 0.6%    |
| Pensacola           | 2         | 0.6%    |
| Paris               | 2         | 0.6%    |
| Orange Park         | 2         | 0.6%    |
| Ngau Wu Tok         | 2         | 0.6%    |
| Newburgh            | 2         | 0.6%    |
| New York            | 2         | 0.6%    |
| Mostoles            | 2         | 0.6%    |
| Moscow              | 2         | 0.6%    |
| Maricopa            | 2         | 0.6%    |
| Lyon                | 2         | 0.6%    |
| London              | 2         | 0.6%    |
| Khabarovsk          | 2         | 0.6%    |
| Houston             | 2         | 0.6%    |
| Dublin              | 2         | 0.6%    |
| Dhaka               | 2         | 0.6%    |
| Camden              | 2         | 0.6%    |
| Bussum              | 2         | 0.6%    |
| Baghdad             | 2         | 0.6%    |
| Zagreb              | 1         | 0.3%    |
| West Jordan         | 1         | 0.3%    |
| West Chester        | 1         | 0.3%    |
| Washington          | 1         | 0.3%    |
| Waren               | 1         | 0.3%    |
| Volgograd           | 1         | 0.3%    |
| Visalia             | 1         | 0.3%    |
| Villa Carlos Paz    | 1         | 0.3%    |
| Vila Nova de Gaia   | 1         | 0.3%    |
| Viby J              | 1         | 0.3%    |
| Veitsbronn          | 1         | 0.3%    |
| Västerås          | 1         | 0.3%    |
| Vapi                | 1         | 0.3%    |
| Ulan Bator          | 1         | 0.3%    |
| Tulare              | 1         | 0.3%    |
| Ts'khinvali         | 1         | 0.3%    |
| Trivandrum          | 1         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 69        | 89     | 15.3%   |
| Samsung Electronics | 64        | 82     | 14.19%  |
| Seagate             | 57        | 72     | 12.64%  |
| Toshiba             | 52        | 56     | 11.53%  |
| Unknown             | 29        | 31     | 6.43%   |
| Kingston            | 26        | 28     | 5.76%   |
| SanDisk             | 20        | 25     | 4.43%   |
| Hitachi             | 16        | 19     | 3.55%   |
| Crucial             | 14        | 19     | 3.1%    |
| SK hynix            | 9         | 9      | 2%      |
| HGST                | 9         | 11     | 2%      |
| Micron Technology   | 8         | 8      | 1.77%   |
| Intel               | 8         | 21     | 1.77%   |
| China               | 8         | 11     | 1.77%   |
| A-DATA Technology   | 6         | 6      | 1.33%   |
| Apple               | 5         | 5      | 1.11%   |
| Team                | 3         | 4      | 0.67%   |
| PNY                 | 3         | 3      | 0.67%   |
| LITEONIT            | 3         | 3      | 0.67%   |
| LITEON              | 3         | 3      | 0.67%   |
| JMicron Technology  | 3         | 3      | 0.67%   |
| Fujitsu             | 3         | 3      | 0.67%   |
| SPCC                | 2         | 2      | 0.44%   |
| Silicon Motion      | 2         | 2      | 0.44%   |
| Phison              | 2         | 2      | 0.44%   |
| KIOXIA              | 2         | 2      | 0.44%   |
| Intenso             | 2         | 3      | 0.44%   |
| HUAWEI              | 2         | 2      | 0.44%   |
| YMTC                | 1         | 1      | 0.22%   |
| W800SH              | 1         | 1      | 0.22%   |
| Transcend           | 1         | 1      | 0.22%   |
| S3+                 | 1         | 1      | 0.22%   |
| RZX                 | 1         | 1      | 0.22%   |
| ROG                 | 1         | 1      | 0.22%   |
| Plextor             | 1         | 1      | 0.22%   |
| Patriot             | 1         | 1      | 0.22%   |
| OCZ                 | 1         | 1      | 0.22%   |
| Netac               | 1         | 1      | 0.22%   |
| Lexar               | 1         | 1      | 0.22%   |
| KingSpec            | 1         | 2      | 0.22%   |
| KingFast            | 1         | 2      | 0.22%   |
| Hikvision           | 1         | 1      | 0.22%   |
| FORESEE             | 1         | 1      | 0.22%   |
| Corsair             | 1         | 2      | 0.22%   |
| BR                  | 1         | 1      | 0.22%   |
| BHT                 | 1         | 1      | 0.22%   |
| ASMT                | 1         | 1      | 0.22%   |
| ASMedia             | 1         | 1      | 0.22%   |
| Apacer              | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                  | 10        | 2.02%   |
| Toshiba MQ01ABF050 500GB                | 7         | 1.42%   |
| Samsung SSD 860 EVO 500GB               | 7         | 1.42%   |
| Unknown SD/MMC/MS PRO 128GB             | 6         | 1.21%   |
| Toshiba MQ01ABD100 1TB                  | 5         | 1.01%   |
| Toshiba DT01ACA200 2TB                  | 5         | 1.01%   |
| Seagate ST2000LM003 HN-M201RAD 2TB      | 5         | 1.01%   |
| Kingston NVMe SSD Drive 512GB           | 5         | 1.01%   |
| Unknown MMC Card  32GB                  | 4         | 0.81%   |
| SanDisk SSD PLUS 1000GB                 | 4         | 0.81%   |
| Samsung SSD 850 EVO 250GB               | 4         | 0.81%   |
| Kingston SA400S37240G 240GB SSD         | 4         | 0.81%   |
| Intel HBRPEKNX0202AH 512GB              | 4         | 0.81%   |
| HGST HTS721010A9E630 1TB                | 4         | 0.81%   |
| HGST HTS541010A9E680 1TB                | 4         | 0.81%   |
| WDC WD10SPZX-75Z10T2 1TB                | 3         | 0.61%   |
| Toshiba MQ01ABD075 752GB                | 3         | 0.61%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 0.61%   |
| Seagate ST320LT007-9ZV142 320GB         | 3         | 0.61%   |
| Seagate ST31000528AS 1TB                | 3         | 0.61%   |
| Seagate ST250DM000-1BD141 250GB         | 3         | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 0.61%   |
| Seagate Expansion 500GB                 | 3         | 0.61%   |
| Samsung SSD 860 EVO 250GB               | 3         | 0.61%   |
| Samsung HM500JI 500GB                   | 3         | 0.61%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 0.61%   |
| JMicron Generic 160GB                   | 3         | 0.61%   |
| Intel HBRPEKNX0202AHO 32GB              | 3         | 0.61%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 2         | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 2         | 0.4%    |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 2         | 0.4%    |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 0.4%    |
| WDC WD5000AADS-00S9B0 500GB             | 2         | 0.4%    |
| WDC WD2500JS-75MHB0 250GB               | 2         | 0.4%    |
| WDC WD2500AAKX-753CA1 250GB             | 2         | 0.4%    |
| WDC WD10SPZX-60Z10T0 1TB                | 2         | 0.4%    |
| WDC WD10EZRX-00L4HB0 1TB                | 2         | 0.4%    |
| WDC WD10EARS-00Y5B1 1TB                 | 2         | 0.4%    |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB    | 2         | 0.4%    |
| Toshiba DT01ACA100 1TB                  | 2         | 0.4%    |
| Toshiba DT01ACA050 500GB                | 2         | 0.4%    |
| Team TM8PS7512G 512GB SSD               | 2         | 0.4%    |
| Seagate ST9250315AS 250GB               | 2         | 0.4%    |
| Seagate ST500VT000-1DK142 500GB         | 2         | 0.4%    |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 0.4%    |
| Seagate ST500LM000-SSHD-8GB             | 2         | 0.4%    |
| SanDisk SD6SF1M128G1022I 128GB SSD      | 2         | 0.4%    |
| SanDisk NVMe SSD Drive 256GB            | 2         | 0.4%    |
| SanDisk NVMe SSD Drive 1TB              | 2         | 0.4%    |
| Samsung SSD 980 1TB                     | 2         | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 0.4%    |
| Samsung SSD 840 Series 250GB            | 2         | 0.4%    |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB | 2         | 0.4%    |
| Samsung MZVLB1T0HBLR-000L2 1TB          | 2         | 0.4%    |
| Kingston SV300S37A240G 240GB SSD        | 2         | 0.4%    |
| Kingston SV300S37A120G 120GB SSD        | 2         | 0.4%    |
| Intenso SSD SATAIII 256GB               | 2         | 0.4%    |
| Intel NVMe SSD Drive 512GB              | 2         | 0.4%    |
| Intel NVMe SSD Drive 32GB               | 2         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 72     | 29.53%  |
| WDC                 | 51        | 66     | 26.42%  |
| Toshiba             | 45        | 48     | 23.32%  |
| Hitachi             | 16        | 19     | 8.29%   |
| HGST                | 9         | 11     | 4.66%   |
| Samsung Electronics | 7         | 9      | 3.63%   |
| Unknown             | 6         | 7      | 3.11%   |
| Fujitsu             | 1         | 1      | 0.52%   |
| ASMedia             | 1         | 1      | 0.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 41     | 21.48%  |
| Kingston            | 17        | 19     | 11.41%  |
| Crucial             | 13        | 18     | 8.72%   |
| SanDisk             | 12        | 13     | 8.05%   |
| WDC                 | 11        | 12     | 7.38%   |
| China               | 8         | 11     | 5.37%   |
| Toshiba             | 4         | 5      | 2.68%   |
| Micron Technology   | 4         | 4      | 2.68%   |
| Apple               | 4         | 4      | 2.68%   |
| Team                | 3         | 4      | 2.01%   |
| PNY                 | 3         | 3      | 2.01%   |
| LITEONIT            | 3         | 3      | 2.01%   |
| LITEON              | 3         | 3      | 2.01%   |
| JMicron Technology  | 3         | 3      | 2.01%   |
| Unknown             | 2         | 2      | 1.34%   |
| SPCC                | 2         | 2      | 1.34%   |
| Intenso             | 2         | 3      | 1.34%   |
| Intel               | 2         | 2      | 1.34%   |
| Fujitsu             | 2         | 2      | 1.34%   |
| A-DATA Technology   | 2         | 2      | 1.34%   |
| W800SH              | 1         | 1      | 0.67%   |
| Transcend           | 1         | 1      | 0.67%   |
| SK hynix            | 1         | 1      | 0.67%   |
| S3+                 | 1         | 1      | 0.67%   |
| RZX                 | 1         | 1      | 0.67%   |
| Plextor             | 1         | 1      | 0.67%   |
| Patriot             | 1         | 1      | 0.67%   |
| OCZ                 | 1         | 1      | 0.67%   |
| Netac               | 1         | 1      | 0.67%   |
| KingSpec            | 1         | 2      | 0.67%   |
| KingFast            | 1         | 1      | 0.67%   |
| FORESEE             | 1         | 1      | 0.67%   |
| Corsair             | 1         | 2      | 0.67%   |
| BR                  | 1         | 1      | 0.67%   |
| BHT                 | 1         | 1      | 0.67%   |
| ASMT                | 1         | 1      | 0.67%   |
| Apacer              | 1         | 1      | 0.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 169       | 234    | 41.32%  |
| SSD     | 131       | 175    | 32.03%  |
| NVMe    | 84        | 111    | 20.54%  |
| MMC     | 20        | 23     | 4.89%   |
| Unknown | 5         | 5      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 247       | 387    | 65.87%  |
| NVMe | 84        | 111    | 22.4%   |
| SAS  | 24        | 27     | 6.4%    |
| MMC  | 20        | 23     | 5.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 183       | 272    | 60%     |
| 0.51-1.0   | 99        | 110    | 32.46%  |
| 1.01-2.0   | 18        | 22     | 5.9%    |
| 3.01-4.0   | 3         | 3      | 0.98%   |
| 2.01-3.0   | 1         | 1      | 0.33%   |
| 4.01-10.0  | 1         | 1      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 88        | 26.99%  |
| 101-250        | 70        | 21.47%  |
| 501-1000       | 56        | 17.18%  |
| 1001-2000      | 37        | 11.35%  |
| Unknown        | 25        | 7.67%   |
| 51-100         | 16        | 4.91%   |
| 21-50          | 14        | 4.29%   |
| 2001-3000      | 9         | 2.76%   |
| 1-20           | 7         | 2.15%   |
| More than 3000 | 4         | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 96        | 28.83%  |
| 51-100         | 55        | 16.52%  |
| 1-20           | 54        | 16.22%  |
| 101-250        | 48        | 14.41%  |
| 251-500        | 35        | 10.51%  |
| Unknown        | 25        | 7.51%   |
| 501-1000       | 14        | 4.2%    |
| 1001-2000      | 3         | 0.9%    |
| More than 3000 | 2         | 0.6%    |
| 0              | 1         | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JI 500GB                   | 3         | 3      | 6.67%   |
| SanDisk SD6SF1M128G1022I 128GB SSD                  | 2         | 2      | 4.44%   |
| WDC WD5000AAKS-75V0A0 500GB                         | 1         | 1      | 2.22%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 1      | 2.22%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 2.22%   |
| WDC WD2003FZEX-00Z4SA0 2TB                          | 1         | 1      | 2.22%   |
| WDC WD10JUCX-63WPNY0 1TB                            | 1         | 1      | 2.22%   |
| WDC WD10EZRX-00L4HB0 1TB                            | 1         | 1      | 2.22%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 2.22%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.22%   |
| Toshiba MK3265GSXF 320GB                            | 1         | 1      | 2.22%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 2.22%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 2.22%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 2.22%   |
| Seagate ST500NM0011 500GB                           | 1         | 1      | 2.22%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 2.22%   |
| Seagate ST3320418AS 320GB                           | 1         | 1      | 2.22%   |
| Seagate ST320LT007-9ZV142 320GB                     | 1         | 1      | 2.22%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 2.22%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 2.22%   |
| Seagate ST250DM000-1BD141 250GB                     | 1         | 1      | 2.22%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 2.22%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 1         | 1      | 2.22%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.22%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 2.22%   |
| SanDisk SSD PLUS 480GB                              | 1         | 1      | 2.22%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 1      | 2.22%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 2.22%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 2.22%   |
| Plextor PX-512M6Pro 512GB SSD                       | 1         | 1      | 2.22%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 2.22%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 2.22%   |
| Intel HBRPEKNX0202AHO 32GB                          | 1         | 1      | 2.22%   |
| Hitachi HUA722020ALA331 2TB                         | 1         | 1      | 2.22%   |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 2.22%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 2.22%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 2.22%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.22%   |
| Fujitsu MHY2160BH 160GB                             | 1         | 1      | 2.22%   |
| A-DATA Technology SX7000NP 128GB                    | 1         | 1      | 2.22%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 2.22%   |
| A-DATA Technology SU700 120GB SSD                   | 1         | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 13     | 25.58%  |
| WDC                 | 6         | 6      | 13.95%  |
| Samsung Electronics | 5         | 5      | 11.63%  |
| SanDisk             | 4         | 4      | 9.3%    |
| Hitachi             | 4         | 4      | 9.3%    |
| Toshiba             | 3         | 3      | 6.98%   |
| A-DATA Technology   | 3         | 3      | 6.98%   |
| SK hynix            | 1         | 1      | 2.33%   |
| Plextor             | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| LITEON              | 1         | 1      | 2.33%   |
| Intel               | 1         | 1      | 2.33%   |
| HGST                | 1         | 1      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 13     | 36.67%  |
| WDC                 | 6         | 6      | 20%     |
| Samsung Electronics | 4         | 4      | 13.33%  |
| Hitachi             | 4         | 4      | 13.33%  |
| Toshiba             | 3         | 3      | 10%     |
| HGST                | 1         | 1      | 3.33%   |
| Fujitsu             | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 32     | 68.29%  |
| SSD  | 9         | 9      | 21.95%  |
| NVMe | 4         | 4      | 9.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB | 1         | 1      | 50%     |
| Intenso SSD SATAIII 256GB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Intenso | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 170       | 294    | 46.2%   |
| Works    | 159       | 207    | 43.21%  |
| Malfunc  | 37        | 45     | 10.05%  |
| Failed   | 2         | 2      | 0.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 225       | 60.65%  |
| AMD                          | 52        | 14.02%  |
| Samsung Electronics          | 30        | 8.09%   |
| SanDisk                      | 17        | 4.58%   |
| Kingston Technology Company  | 9         | 2.43%   |
| SK hynix                     | 8         | 2.16%   |
| Nvidia                       | 5         | 1.35%   |
| Silicon Motion               | 4         | 1.08%   |
| Micron Technology            | 4         | 1.08%   |
| Toshiba America Info Systems | 3         | 0.81%   |
| Phison Electronics           | 2         | 0.54%   |
| KIOXIA                       | 2         | 0.54%   |
| ASMedia Technology           | 2         | 0.54%   |
| ADATA Technology             | 2         | 0.54%   |
| Yangtze Memory Technologies  | 1         | 0.27%   |
| VIA Technologies             | 1         | 0.27%   |
| Realtek Semiconductor        | 1         | 0.27%   |
| Micron/Crucial Technology    | 1         | 0.27%   |
| JMicron Technology           | 1         | 0.27%   |
| Apple                        | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 37        | 8.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 22        | 5.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 20        | 4.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 17        | 3.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 16        | 3.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 16        | 3.75%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 13        | 3.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 12        | 2.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 10        | 2.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10        | 2.34%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 9         | 2.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 9         | 2.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 2.11%   |
| Samsung NVMe SSD Controller 980                                                         | 7         | 1.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 1.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 1.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 1.17%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 1.17%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 5         | 1.17%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 5         | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 5         | 1.17%   |
| SK hynix BC511                                                                          | 4         | 0.94%   |
| Micron Non-Volatile memory controller                                                   | 4         | 0.94%   |
| Intel Non-Volatile memory controller                                                    | 4         | 0.94%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 4         | 0.94%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 4         | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 4         | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 0.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4         | 0.94%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4         | 0.94%   |
| SK hynix Gold P31 SSD                                                                   | 3         | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 0.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3         | 0.7%    |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3         | 0.7%    |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 0.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 0.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 3         | 0.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 0.7%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2         | 0.47%   |
| SanDisk Non-Volatile memory controller                                                  | 2         | 0.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.47%   |
| Samsung Electronics SATA controller                                                     | 2         | 0.47%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.47%   |
| Nvidia MCP61 IDE                                                                        | 2         | 0.47%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 2         | 0.47%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2         | 0.47%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 2         | 0.47%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 0.47%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 0.47%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.47%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 0.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 219       | 57.03%  |
| NVMe | 84        | 21.88%  |
| IDE  | 43        | 11.2%   |
| RAID | 38        | 9.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 255       | 80.44%  |
| AMD    | 62        | 19.56%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 2.52%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 2.21%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 1.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.89%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.26%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.26%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 1.26%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 1.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.95%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.95%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.95%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 3         | 0.95%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.95%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.95%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 0.95%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 0.95%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 3         | 0.95%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.95%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.95%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 0.95%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.95%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 2         | 0.63%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 2         | 0.63%   |
| Intel Pentium CPU G3260 @ 3.30GHz             | 2         | 0.63%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.63%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.63%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.63%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.63%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.63%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 0.63%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 0.63%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.63%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.63%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 0.63%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 2         | 0.63%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.63%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 2         | 0.63%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.63%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.63%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.63%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.63%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.63%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 0.63%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2         | 0.63%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 0.63%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 2         | 0.63%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.63%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 0.63%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 0.63%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.63%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 2         | 0.63%   |
| AMD Ryzen 7 1700X Eight-Core Processor        | 2         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 84        | 26.5%   |
| Intel Core i7           | 74        | 23.34%  |
| Intel Core i3           | 27        | 8.52%   |
| Other                   | 23        | 7.26%   |
| AMD Ryzen 7             | 14        | 4.42%   |
| Intel Celeron           | 11        | 3.47%   |
| Intel Core 2 Duo        | 10        | 3.15%   |
| AMD Ryzen 5             | 10        | 3.15%   |
| Intel Pentium           | 6         | 1.89%   |
| AMD A6                  | 6         | 1.89%   |
| AMD FX                  | 5         | 1.58%   |
| Intel Xeon              | 4         | 1.26%   |
| Intel Pentium Dual-Core | 4         | 1.26%   |
| Intel Core 2            | 4         | 1.26%   |
| Intel Atom              | 3         | 0.95%   |
| AMD Ryzen 3             | 3         | 0.95%   |
| AMD E1                  | 3         | 0.95%   |
| AMD A4                  | 3         | 0.95%   |
| Intel Pentium Silver    | 2         | 0.63%   |
| Intel Core 2 Quad       | 2         | 0.63%   |
| AMD Athlon II X2        | 2         | 0.63%   |
| AMD A8                  | 2         | 0.63%   |
| AMD A10                 | 2         | 0.63%   |
| Intel Pentium Dual      | 1         | 0.32%   |
| Intel Core M            | 1         | 0.32%   |
| Intel Core 2 Extreme    | 1         | 0.32%   |
| AMD Ryzen Threadripper  | 1         | 0.32%   |
| AMD Ryzen 9             | 1         | 0.32%   |
| AMD Phenom II X4        | 1         | 0.32%   |
| AMD Phenom              | 1         | 0.32%   |
| AMD E2                  | 1         | 0.32%   |
| AMD E                   | 1         | 0.32%   |
| AMD C-50                | 1         | 0.32%   |
| AMD Athlon X2           | 1         | 0.32%   |
| AMD Athlon 64 X2        | 1         | 0.32%   |
| AMD Athlon 64           | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 154       | 48.58%  |
| 4      | 109       | 34.38%  |
| 6      | 24        | 7.57%   |
| 8      | 19        | 5.99%   |
| 1      | 4         | 1.26%   |
| 12     | 3         | 0.95%   |
| 3      | 2         | 0.63%   |
| 14     | 1         | 0.32%   |
| 10     | 1         | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 316       | 99.68%  |
| 2      | 1         | 0.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 226       | 71.29%  |
| 1      | 91        | 28.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 312       | 98.42%  |
| Unknown        | 5         | 1.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 154       | 47.24%  |
| 0x206a7    | 22        | 6.75%   |
| 0x306a9    | 12        | 3.68%   |
| 0x806c1    | 10        | 3.07%   |
| 0x806ec    | 9         | 2.76%   |
| 0x806e9    | 8         | 2.45%   |
| 0x906ea    | 7         | 2.15%   |
| 0x406e3    | 7         | 2.15%   |
| 0x306c3    | 7         | 2.15%   |
| 0x906e9    | 6         | 1.84%   |
| 0x806ea    | 6         | 1.84%   |
| 0x40651    | 6         | 1.84%   |
| 0x1067a    | 6         | 1.84%   |
| 0xa0652    | 5         | 1.53%   |
| 0x706e5    | 4         | 1.23%   |
| 0x6f6      | 4         | 1.23%   |
| 0x706a8    | 3         | 0.92%   |
| 0x406c4    | 3         | 0.92%   |
| 0x08600106 | 3         | 0.92%   |
| 0x07030105 | 3         | 0.92%   |
| 0x06006705 | 3         | 0.92%   |
| 0x906ed    | 2         | 0.61%   |
| 0x906a3    | 2         | 0.61%   |
| 0x806d1    | 2         | 0.61%   |
| 0x306d4    | 2         | 0.61%   |
| 0x08701021 | 2         | 0.61%   |
| 0x08108109 | 2         | 0.61%   |
| 0x08001138 | 2         | 0.61%   |
| 0x06001119 | 2         | 0.61%   |
| 0x06000852 | 2         | 0.61%   |
| 0x03000027 | 2         | 0.61%   |
| 0x906a4    | 1         | 0.31%   |
| 0x806eb    | 1         | 0.31%   |
| 0x806c2    | 1         | 0.31%   |
| 0x706a1    | 1         | 0.31%   |
| 0x6fd      | 1         | 0.31%   |
| 0x506e3    | 1         | 0.31%   |
| 0x506c9    | 1         | 0.31%   |
| 0x40661    | 1         | 0.31%   |
| 0x20655    | 1         | 0.31%   |
| 0x106a5    | 1         | 0.31%   |
| 0x0a201016 | 1         | 0.31%   |
| 0x08108102 | 1         | 0.31%   |
| 0x0810100b | 1         | 0.31%   |
| 0x0800820d | 1         | 0.31%   |
| 0x06006113 | 1         | 0.31%   |
| 0x0600111f | 1         | 0.31%   |
| 0x05000029 | 1         | 0.31%   |
| 0x01000095 | 1         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 61        | 19.24%  |
| SandyBridge      | 34        | 10.73%  |
| Haswell          | 30        | 9.46%   |
| IvyBridge        | 22        | 6.94%   |
| Skylake          | 19        | 5.99%   |
| Penryn           | 15        | 4.73%   |
| TigerLake        | 14        | 4.42%   |
| Broadwell        | 11        | 3.47%   |
| Silvermont       | 9         | 2.84%   |
| Piledriver       | 9         | 2.84%   |
| Core             | 9         | 2.84%   |
| Zen 2            | 8         | 2.52%   |
| Zen+             | 7         | 2.21%   |
| Zen              | 7         | 2.21%   |
| IceLake          | 7         | 2.21%   |
| CometLake        | 7         | 2.21%   |
| Excavator        | 6         | 1.89%   |
| Unknown          | 6         | 1.89%   |
| Westmere         | 5         | 1.58%   |
| Goldmont plus    | 5         | 1.58%   |
| K10              | 4         | 1.26%   |
| Zen 3            | 3         | 0.95%   |
| Puma             | 3         | 0.95%   |
| Jaguar           | 3         | 0.95%   |
| Alderlake Hybrid | 3         | 0.95%   |
| K8 Hammer        | 2         | 0.63%   |
| K10 Llano        | 2         | 0.63%   |
| Bobcat           | 2         | 0.63%   |
| Steamroller      | 1         | 0.32%   |
| Nehalem          | 1         | 0.32%   |
| K8 & K10 hybrid  | 1         | 0.32%   |
| Goldmont         | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 220       | 54.46%  |
| Nvidia | 101       | 25%     |
| AMD    | 83        | 20.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 28        | 6.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 4.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 3.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 3.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 3.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 2.68%   |
| Intel UHD Graphics 620                                                                   | 10        | 2.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.44%   |
| Intel HD Graphics 5500                                                                   | 9         | 2.2%    |
| Intel HD Graphics 620                                                                    | 8         | 1.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.71%   |
| Intel HD Graphics 630                                                                    | 6         | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.46%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.22%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.22%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.22%   |
| AMD Renoir                                                                               | 5         | 1.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.22%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.98%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 0.98%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 0.98%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.98%   |
| Intel HD Graphics 530                                                                    | 4         | 0.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.98%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 0.98%   |
| AMD Lucienne                                                                             | 4         | 0.98%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.73%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.73%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.73%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 3         | 0.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.73%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.73%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 3         | 0.73%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.73%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 3         | 0.73%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.49%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.49%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.49%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.49%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.49%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.49%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.49%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 0.49%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 2         | 0.49%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.49%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.49%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.49%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.49%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 0.49%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 138       | 43.53%  |
| 1 x AMD        | 61        | 19.24%  |
| Intel + Nvidia | 59        | 18.61%  |
| 1 x Nvidia     | 36        | 11.36%  |
| Intel + AMD    | 16        | 5.05%   |
| AMD + Nvidia   | 5         | 1.58%   |
| 2 x Nvidia     | 1         | 0.32%   |
| 2 x AMD        | 1         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 280       | 88.05%  |
| Proprietary | 35        | 11.01%  |
| Unknown     | 3         | 0.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 237       | 73.6%   |
| 1.01-2.0   | 25        | 7.76%   |
| 0.51-1.0   | 18        | 5.59%   |
| 0.01-0.5   | 17        | 5.28%   |
| 3.01-4.0   | 16        | 4.97%   |
| 7.01-8.0   | 5         | 1.55%   |
| 5.01-6.0   | 3         | 0.93%   |
| 2.01-3.0   | 1         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 56        | 15.95%  |
| LG Display              | 46        | 13.11%  |
| Samsung Electronics     | 41        | 11.68%  |
| BOE                     | 40        | 11.4%   |
| Chimei Innolux          | 34        | 9.69%   |
| Dell                    | 13        | 3.7%    |
| Apple                   | 10        | 2.85%   |
| Acer                    | 9         | 2.56%   |
| Hewlett-Packard         | 7         | 1.99%   |
| Goldstar                | 7         | 1.99%   |
| Chi Mei Optoelectronics | 7         | 1.99%   |
| Philips                 | 6         | 1.71%   |
| BenQ                    | 6         | 1.71%   |
| AOC                     | 6         | 1.71%   |
| Unknown                 | 5         | 1.42%   |
| Lenovo                  | 5         | 1.42%   |
| Ancor Communications    | 5         | 1.42%   |
| Sharp                   | 4         | 1.14%   |
| Panasonic               | 4         | 1.14%   |
| InfoVision              | 4         | 1.14%   |
| Toshiba                 | 3         | 0.85%   |
| PANDA                   | 3         | 0.85%   |
| NEC Computers           | 3         | 0.85%   |
| AUS                     | 3         | 0.85%   |
| Vizio                   | 2         | 0.57%   |
| ViewSonic               | 2         | 0.57%   |
| Sceptre Tech            | 2         | 0.57%   |
| Eizo                    | 2         | 0.57%   |
| ___                     | 1         | 0.28%   |
| Unknown (AAA)           | 1         | 0.28%   |
| STD                     | 1         | 0.28%   |
| STA                     | 1         | 0.28%   |
| Sony                    | 1         | 0.28%   |
| Sceptre                 | 1         | 0.28%   |
| SANYO                   | 1         | 0.28%   |
| RIS                     | 1         | 0.28%   |
| Plain Tree Systems      | 1         | 0.28%   |
| ONN                     | 1         | 0.28%   |
| Kogan                   | 1         | 0.28%   |
| Insignia                | 1         | 0.28%   |
| Iiyama                  | 1         | 0.28%   |
| CSO                     | 1         | 0.28%   |
| Ativa                   | 1         | 0.28%   |
| AGO                     | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 3         | 0.84%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch          | 3         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.84%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 3         | 0.84%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.84%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 0.84%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 2         | 0.56%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                      | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 2         | 0.56%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 2         | 0.56%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 2         | 0.56%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.56%   |
| Panasonic TV MEIA08F 1920x540                                         | 2         | 0.56%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 382x215mm 17.3-inch           | 2         | 0.56%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 2         | 0.56%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 2         | 0.56%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.56%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 2         | 0.56%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 2         | 0.56%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 2         | 0.56%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 0.56%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 0.56%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                     | 2         | 0.56%   |
| AUS LCD Monitor VG245 1920x1080                                       | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch         | 2         | 0.56%   |
| Acer X223W ACR0011 1680x1050 473x296mm 22.0-inch                      | 2         | 0.56%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.28%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1         | 0.28%   |
| Vizio E220VA VIZ0070 1920x1080 476x268mm 21.5-inch                    | 1         | 0.28%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch         | 1         | 0.28%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch         | 1         | 0.28%   |
| Unknown PHILCO 9000 1360x768 1600x900mm 72.3-inch                     | 1         | 0.28%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                 | 1         | 0.28%   |
| Unknown LCD Monitor HRX 32H4030 1920x1080                             | 1         | 0.28%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch              | 1         | 0.28%   |
| Toshiba TSB-TV TSB0205 1920x1080 708x398mm 32.0-inch                  | 1         | 0.28%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                         | 1         | 0.28%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                    | 1         | 0.28%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                   | 1         | 0.28%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.28%   |
| Sharp LCD Monitor SHP14A2 1920x1080 309x174mm 14.0-inch               | 1         | 0.28%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.28%   |
| Sharp LCD Monitor SHP143A 3840x2160 346x194mm 15.6-inch               | 1         | 0.28%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 522x293mm 23.6-inch        | 1         | 0.28%   |
| Sceptre Tech Sceptre B30 SPT0BC2 2560x1080 690x291mm 29.5-inch        | 1         | 0.28%   |
| Sceptre LCD Monitor P30 2560x1080                                     | 1         | 0.28%   |
| SANYO LCD SAN0B51 1920x540                                            | 1         | 0.28%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 0.28%   |
| Samsung Electronics SyncMaster SAM064F 1920x1080 510x290mm 23.1-inch  | 1         | 0.28%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch  | 1         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 153       | 45.54%  |
| 1366x768 (WXGA)    | 84        | 25%     |
| 1600x900 (HD+)     | 15        | 4.46%   |
| 1680x1050 (WSXGA+) | 12        | 3.57%   |
| 1280x800 (WXGA)    | 10        | 2.98%   |
| 3840x2160 (4K)     | 8         | 2.38%   |
| 1440x900 (WXGA+)   | 8         | 2.38%   |
| 1280x1024 (SXGA)   | 8         | 2.38%   |
| 2560x1440 (QHD)    | 5         | 1.49%   |
| 1920x1200 (WUXGA)  | 5         | 1.49%   |
| 1360x768           | 5         | 1.49%   |
| 2160x1440          | 4         | 1.19%   |
| 2560x1600          | 3         | 0.89%   |
| 2560x1080          | 3         | 0.89%   |
| 1920x540           | 3         | 0.89%   |
| 3840x1080          | 2         | 0.6%    |
| 2880x1800          | 2         | 0.6%    |
| 1024x768 (XGA)     | 2         | 0.6%    |
| Unknown            | 2         | 0.6%    |
| 3200x1080          | 1         | 0.3%    |
| 1280x720 (HD)      | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 108       | 30.77%  |
| 14      | 39        | 11.11%  |
| 13      | 37        | 10.54%  |
| 17      | 30        | 8.55%   |
| 24      | 19        | 5.41%   |
| Unknown | 17        | 4.84%   |
| 27      | 15        | 4.27%   |
| 23      | 15        | 4.27%   |
| 12      | 11        | 3.13%   |
| 21      | 10        | 2.85%   |
| 22      | 9         | 2.56%   |
| 31      | 8         | 2.28%   |
| 19      | 6         | 1.71%   |
| 11      | 5         | 1.42%   |
| 32      | 3         | 0.85%   |
| 16      | 3         | 0.85%   |
| 72      | 2         | 0.57%   |
| 48      | 2         | 0.57%   |
| 40      | 2         | 0.57%   |
| 18      | 2         | 0.57%   |
| 84      | 1         | 0.28%   |
| 52      | 1         | 0.28%   |
| 42      | 1         | 0.28%   |
| 41      | 1         | 0.28%   |
| 34      | 1         | 0.28%   |
| 29      | 1         | 0.28%   |
| 25      | 1         | 0.28%   |
| 20      | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 174       | 50.29%  |
| 501-600     | 44        | 12.72%  |
| 351-400     | 31        | 8.96%   |
| 201-300     | 31        | 8.96%   |
| 401-500     | 25        | 7.23%   |
| Unknown     | 17        | 4.91%   |
| 601-700     | 10        | 2.89%   |
| 701-800     | 4         | 1.16%   |
| 1501-2000   | 3         | 0.87%   |
| 1001-1500   | 3         | 0.87%   |
| 801-900     | 2         | 0.58%   |
| 901-1000    | 2         | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 254       | 78.64%  |
| 16/10   | 37        | 11.46%  |
| Unknown | 12        | 3.72%   |
| 5/4     | 7         | 2.17%   |
| 32/9    | 4         | 1.24%   |
| 4/3     | 3         | 0.93%   |
| 3/2     | 3         | 0.93%   |
| 21/9    | 2         | 0.62%   |
| 6/5     | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 109       | 31.05%  |
| 81-90          | 63        | 17.95%  |
| 201-250        | 43        | 12.25%  |
| 121-130        | 22        | 6.27%   |
| Unknown        | 17        | 4.84%   |
| 301-350        | 16        | 4.56%   |
| 71-80          | 14        | 3.99%   |
| 351-500        | 12        | 3.42%   |
| 61-70          | 10        | 2.85%   |
| 151-200        | 10        | 2.85%   |
| 251-300        | 8         | 2.28%   |
| 141-150        | 7         | 1.99%   |
| More than 1000 | 5         | 1.42%   |
| 51-60          | 5         | 1.42%   |
| 501-1000       | 5         | 1.42%   |
| 131-140        | 3         | 0.85%   |
| 111-120        | 2         | 0.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 109       | 32.15%  |
| 101-120       | 95        | 28.02%  |
| 51-100        | 84        | 24.78%  |
| 161-240       | 20        | 5.9%    |
| Unknown       | 17        | 5.01%   |
| 1-50          | 9         | 2.65%   |
| More than 240 | 5         | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 265       | 82.3%   |
| 2     | 47        | 14.6%   |
| 3     | 6         | 1.86%   |
| 0     | 4         | 1.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 181       | 33.27%  |
| Intel                                  | 159       | 29.23%  |
| Qualcomm Atheros                       | 57        | 10.48%  |
| Broadcom                               | 31        | 5.7%    |
| Ralink Technology                      | 14        | 2.57%   |
| TP-Link                                | 10        | 1.84%   |
| Samsung Electronics                    | 9         | 1.65%   |
| Qualcomm Atheros Communications        | 9         | 1.65%   |
| Broadcom Limited                       | 9         | 1.65%   |
| MediaTek                               | 8         | 1.47%   |
| Huawei Technologies                    | 6         | 1.1%    |
| NetGear                                | 5         | 0.92%   |
| ASUSTek Computer                       | 5         | 0.92%   |
| Nvidia                                 | 4         | 0.74%   |
| Microsoft                              | 4         | 0.74%   |
| Xiaomi                                 | 3         | 0.55%   |
| Ralink                                 | 3         | 0.55%   |
| Marvell Technology Group               | 3         | 0.55%   |
| D-Link System                          | 3         | 0.55%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.37%   |
| Linksys                                | 2         | 0.37%   |
| ASIX Electronics                       | 2         | 0.37%   |
| Apple                                  | 2         | 0.37%   |
| ZyXEL Communications                   | 1         | 0.18%   |
| vivo                                   | 1         | 0.18%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.18%   |
| Sagem                                  | 1         | 0.18%   |
| Qualcomm                               | 1         | 0.18%   |
| Mercucys                               | 1         | 0.18%   |
| Lenovo                                 | 1         | 0.18%   |
| ICS Advent                             | 1         | 0.18%   |
| Gemtek                                 | 1         | 0.18%   |
| Ericsson Business Mobile Networks      | 1         | 0.18%   |
| Davicom Semiconductor                  | 1         | 0.18%   |
| D-Link                                 | 1         | 0.18%   |
| Arduino SA                             | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 104       | 16.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 4.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 2.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 12        | 1.87%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 1.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.4%    |
| Qualcomm Atheros AR9271 802.11n                                   | 9         | 1.4%    |
| Intel Wireless 8265 / 8275                                        | 9         | 1.4%    |
| Intel Wireless 7265                                               | 9         | 1.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 9         | 1.4%    |
| TP-Link TL-WN722N v2                                              | 7         | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.09%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 7         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.09%   |
| Intel Wireless 7260                                               | 7         | 1.09%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 6         | 0.93%   |
| Intel Wireless 3165                                               | 6         | 0.93%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 0.78%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 5         | 0.78%   |
| Realtek 802.11ac NIC                                              | 5         | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.78%   |
| Intel Wireless 8260                                               | 5         | 0.78%   |
| Intel Wireless 3160                                               | 5         | 0.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4         | 0.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.62%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.62%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.62%   |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.62%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.47%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 3         | 0.47%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 3         | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.47%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.47%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 0.47%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 3         | 0.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.47%   |
| Intel I211 Gigabit Network Connection                             | 3         | 0.47%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.47%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 137       | 39.37%  |
| Realtek Semiconductor             | 68        | 19.54%  |
| Qualcomm Atheros                  | 44        | 12.64%  |
| Broadcom                          | 25        | 7.18%   |
| Ralink Technology                 | 14        | 4.02%   |
| TP-Link                           | 10        | 2.87%   |
| Qualcomm Atheros Communications   | 9         | 2.59%   |
| Broadcom Limited                  | 7         | 2.01%   |
| NetGear                           | 5         | 1.44%   |
| MediaTek                          | 5         | 1.44%   |
| ASUSTek Computer                  | 5         | 1.44%   |
| Microsoft                         | 4         | 1.15%   |
| Ralink                            | 3         | 0.86%   |
| Marvell Technology Group          | 3         | 0.86%   |
| Linksys                           | 2         | 0.57%   |
| ZyXEL Communications              | 1         | 0.29%   |
| Sagem                             | 1         | 0.29%   |
| Mercucys                          | 1         | 0.29%   |
| Gemtek                            | 1         | 0.29%   |
| Ericsson Business Mobile Networks | 1         | 0.29%   |
| D-Link System                     | 1         | 0.29%   |
| D-Link                            | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 3.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 3.44%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 3.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.58%   |
| Qualcomm Atheros AR9271 802.11n                                         | 9         | 2.58%   |
| Intel Wireless 8265 / 8275                                              | 9         | 2.58%   |
| Intel Wireless 7265                                                     | 9         | 2.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 2.58%   |
| TP-Link TL-WN722N v2                                                    | 7         | 2.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.01%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 7         | 2.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 2.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.01%   |
| Intel Wireless 7260                                                     | 7         | 2.01%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 2.01%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 2.01%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 6         | 1.72%   |
| Intel Wireless 3165                                                     | 6         | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 5         | 1.43%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 5         | 1.43%   |
| Realtek 802.11ac NIC                                                    | 5         | 1.43%   |
| Intel Wireless 8260                                                     | 5         | 1.43%   |
| Intel Wireless 3160                                                     | 5         | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.15%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.15%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.15%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.15%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.86%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 3         | 0.86%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 3         | 0.86%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.86%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.86%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 0.86%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 3         | 0.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 0.86%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.86%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 3         | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.57%   |
| Realtek RTL8187 Wireless Adapter                                        | 2         | 0.57%   |
| Ralink RT5372 Wireless Adapter                                          | 2         | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.57%   |
| NetGear A6210                                                           | 2         | 0.57%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 2         | 0.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.57%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.57%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 155       | 54.96%  |
| Intel                 | 62        | 21.99%  |
| Qualcomm Atheros      | 21        | 7.45%   |
| Broadcom              | 10        | 3.55%   |
| Samsung Electronics   | 9         | 3.19%   |
| Nvidia                | 4         | 1.42%   |
| Xiaomi                | 3         | 1.06%   |
| MediaTek              | 3         | 1.06%   |
| Huawei Technologies   | 2         | 0.71%   |
| D-Link System         | 2         | 0.71%   |
| Broadcom Limited      | 2         | 0.71%   |
| ASIX Electronics      | 2         | 0.71%   |
| Apple                 | 2         | 0.71%   |
| vivo                  | 1         | 0.35%   |
| Qualcomm              | 1         | 0.35%   |
| Lenovo                | 1         | 0.35%   |
| ICS Advent            | 1         | 0.35%   |
| Davicom Semiconductor | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 104       | 36.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 11.19%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 6.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 3.15%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.1%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 1.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 1.75%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4         | 1.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 1.4%    |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.05%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 1.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.05%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.05%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.05%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.05%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.7%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.7%    |
| Nvidia MCP61 Ethernet                                             | 2         | 0.7%    |
| MediaTek moto e6s                                                 | 2         | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.7%    |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.7%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.7%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 0.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.7%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.35%   |
| vivo 1806                                                         | 1         | 0.35%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.35%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.35%   |
| Qualcomm Nokia X100                                               | 1         | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.35%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.35%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.35%   |
| MediaTek Infinix HOT 9                                            | 1         | 0.35%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.35%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.35%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.35%   |
| Intel Ethernet controller                                         | 1         | 0.35%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.35%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.35%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.35%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.35%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.35%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.35%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.35%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 0.35%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.35%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.35%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 0.35%   |
| Huawei JNY-LX1                                                    | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 294       | 52.13%  |
| Ethernet | 262       | 46.45%  |
| Modem    | 4         | 0.71%   |
| Unknown  | 4         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 234       | 69.03%  |
| Ethernet | 103       | 30.38%  |
| Unknown  | 2         | 0.59%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 187       | 58.81%  |
| 1     | 121       | 38.05%  |
| 3     | 5         | 1.57%   |
| 0     | 5         | 1.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 264       | 81.99%  |
| Yes     | 57        | 17.7%   |
| Unknown | 1         | 0.31%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 107       | 48.42%  |
| Qualcomm Atheros Communications | 23        | 10.41%  |
| Realtek Semiconductor           | 21        | 9.5%    |
| Broadcom                        | 14        | 6.33%   |
| Cambridge Silicon Radio         | 11        | 4.98%   |
| Apple                           | 8         | 3.62%   |
| Lite-On Technology              | 7         | 3.17%   |
| Foxconn / Hon Hai               | 7         | 3.17%   |
| IMC Networks                    | 6         | 2.71%   |
| Dell                            | 4         | 1.81%   |
| Toshiba                         | 3         | 1.36%   |
| MediaTek                        | 3         | 1.36%   |
| Marvell Semiconductor           | 3         | 1.36%   |
| Realtek                         | 1         | 0.45%   |
| Ralink                          | 1         | 0.45%   |
| Dynex                           | 1         | 0.45%   |
| Alps Electric                   | 1         | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 41        | 18.55%  |
| Intel AX201 Bluetooth                                                               | 24        | 10.86%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 9.5%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 5.88%   |
| Realtek Bluetooth Radio                                                             | 11        | 4.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 11        | 4.98%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 3.17%   |
| Intel AX200 Bluetooth                                                               | 7         | 3.17%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.26%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.81%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.81%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 1.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.36%   |
| MediaTek Wireless_Device                                                            | 3         | 1.36%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 1.36%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 1.36%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.9%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.9%    |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 2         | 0.9%    |
| Lite-On Wireless_Device                                                             | 2         | 0.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 0.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.9%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.9%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.9%    |
| Intel Bluetooth Device                                                              | 2         | 0.9%    |
| Intel AX210 Bluetooth                                                               | 2         | 0.9%    |
| IMC Networks Bluetooth Radio                                                        | 2         | 0.9%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.9%    |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.9%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.9%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 0.9%    |
| Apple Bluetooth USB Host Controller                                                 | 2         | 0.9%    |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.45%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.45%   |
| Toshiba Atheros AR3012 Bluetooth                                                    | 1         | 0.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.45%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.45%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.45%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.45%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.45%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.45%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.45%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.45%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.45%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.45%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.45%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.45%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.45%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.45%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 247       | 61.29%  |
| AMD                    | 76        | 18.86%  |
| Nvidia                 | 67        | 16.63%  |
| C-Media Electronics    | 4         | 0.99%   |
| Yamaha                 | 1         | 0.25%   |
| SteelSeries ApS        | 1         | 0.25%   |
| Logitech               | 1         | 0.25%   |
| Lenovo                 | 1         | 0.25%   |
| GYROCOM C&C            | 1         | 0.25%   |
| Guillemot              | 1         | 0.25%   |
| GN Netcom              | 1         | 0.25%   |
| Generalplus Technology | 1         | 0.25%   |
| Apple                  | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 32        | 6.53%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 31        | 6.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 4.9%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 3.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 15        | 3.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 3.06%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 3.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 14        | 2.86%   |
| AMD FCH Azalia Controller                                                                         | 14        | 2.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 13        | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 2.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 2.24%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 2.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 2.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 2.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 1.84%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 1.84%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 1.63%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.43%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.43%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 1.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 1.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.22%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 1.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 1.02%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.02%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 1.02%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.02%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.82%   |
| Nvidia Audio device                                                                               | 4         | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 0.82%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.61%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.61%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.61%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.61%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.61%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.61%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.61%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.61%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.61%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.61%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.41%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.41%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.41%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.41%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.41%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.41%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 64        | 28.07%  |
| SK hynix            | 35        | 15.35%  |
| Micron Technology   | 32        | 14.04%  |
| Unknown             | 20        | 8.77%   |
| Crucial             | 17        | 7.46%   |
| Kingston            | 16        | 7.02%   |
| Corsair             | 8         | 3.51%   |
| Ramaxel Technology  | 7         | 3.07%   |
| Elpida              | 7         | 3.07%   |
| G.Skill             | 4         | 1.75%   |
| Unknown (ABCD)      | 3         | 1.32%   |
| Nanya Technology    | 3         | 1.32%   |
| A-DATA Technology   | 3         | 1.32%   |
| Team                | 2         | 0.88%   |
| Unifosa             | 1         | 0.44%   |
| Teikon              | 1         | 0.44%   |
| Smart               | 1         | 0.44%   |
| Silicon Power       | 1         | 0.44%   |
| Saikano             | 1         | 0.44%   |
| S                   | 1         | 0.44%   |
| PNY                 | 1         | 0.44%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 6         | 2.52%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 6         | 2.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 1.68%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 1.68%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 1.26%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 1.26%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 1.26%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 3         | 1.26%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 3         | 1.26%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 3         | 1.26%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 2         | 0.84%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 2         | 0.84%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 2         | 0.84%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.84%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 2         | 0.84%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 0.84%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s      | 2         | 0.84%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.84%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.84%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 2         | 0.84%   |
| Samsung RAM M4 70T2953CZ3-CE6 1GB SODIMM DDR 667MT/s                | 2         | 0.84%   |
| Samsung RAM K4AAG165WA-BCWE 8GB SODIMM DDR4 3200MT/s                | 2         | 0.84%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 2         | 0.84%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.84%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 2         | 0.84%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s           | 2         | 0.84%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 2         | 0.84%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s               | 2         | 0.84%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                           | 1         | 0.42%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                        | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                           | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                           | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM                                         | 1         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                         | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM DDR2                                 | 1         | 0.42%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 0.42%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 0.42%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                           | 1         | 0.42%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.42%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 0.42%   |
| Team RAM TEAMGROUP-SD3-1600 8192MB SODIMM DDR3 1600MT/s             | 1         | 0.42%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 1         | 0.42%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                | 1         | 0.42%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.42%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1066MT/s                     | 1         | 0.42%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                        | 1         | 0.42%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                        | 1         | 0.42%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                       | 1         | 0.42%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                              | 1         | 0.42%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s                 | 1         | 0.42%   |
| SK hynix RAM HMT851S6AMR6R-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.42%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                | 1         | 0.42%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 85        | 43.37%  |
| DDR3    | 79        | 40.31%  |
| LPDDR4  | 10        | 5.1%    |
| LPDDR3  | 7         | 3.57%   |
| DDR2    | 7         | 3.57%   |
| SDRAM   | 3         | 1.53%   |
| Unknown | 3         | 1.53%   |
| DDR5    | 1         | 0.51%   |
| DDR     | 1         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 145       | 74.36%  |
| DIMM         | 34        | 17.44%  |
| Row Of Chips | 14        | 7.18%   |
| Chip         | 1         | 0.51%   |
| Unknown      | 1         | 0.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 83        | 39.15%  |
| 8192  | 69        | 32.55%  |
| 16384 | 24        | 11.32%  |
| 2048  | 23        | 10.85%  |
| 1024  | 9         | 4.25%   |
| 32768 | 4         | 1.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 53        | 24.77%  |
| 2667    | 46        | 21.5%   |
| 3200    | 26        | 12.15%  |
| 2400    | 18        | 8.41%   |
| 1334    | 13        | 6.07%   |
| 2133    | 10        | 4.67%   |
| 1333    | 10        | 4.67%   |
| Unknown | 5         | 2.34%   |
| 1867    | 4         | 1.87%   |
| 1067    | 4         | 1.87%   |
| 3600    | 3         | 1.4%    |
| 3266    | 3         | 1.4%    |
| 1066    | 3         | 1.4%    |
| 667     | 3         | 1.4%    |
| 4267    | 2         | 0.93%   |
| 800     | 2         | 0.93%   |
| 8400    | 1         | 0.47%   |
| 4800    | 1         | 0.47%   |
| 3466    | 1         | 0.47%   |
| 2666    | 1         | 0.47%   |
| 2200    | 1         | 0.47%   |
| 2048    | 1         | 0.47%   |
| 1866    | 1         | 0.47%   |
| 533     | 1         | 0.47%   |
| 400     | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| HP OfficeJet Pro 7720 series | 1         | 50%     |
| Brother HL-1210W series      | 1         | 50%     |

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
| Chicony Electronics                    | 65        | 28.51%  |
| Acer                                   | 24        | 10.53%  |
| IMC Networks                           | 20        | 8.77%   |
| Microdia                               | 19        | 8.33%   |
| Sunplus Innovation Technology          | 13        | 5.7%    |
| Realtek Semiconductor                  | 13        | 5.7%    |
| Quanta                                 | 12        | 5.26%   |
| Apple                                  | 10        | 4.39%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.63%   |
| Ricoh                                  | 5         | 2.19%   |
| Syntek                                 | 4         | 1.75%   |
| Luxvisions Innotech Limited            | 4         | 1.75%   |
| Logitech                               | 4         | 1.75%   |
| Suyin                                  | 3         | 1.32%   |
| Silicon Motion                         | 3         | 1.32%   |
| Samsung Electronics                    | 3         | 1.32%   |
| Lite-On Technology                     | 3         | 1.32%   |
| Alcor Micro                            | 3         | 1.32%   |
| Microsoft                              | 2         | 0.88%   |
| LG Electronics                         | 2         | 0.88%   |
| Creative Technology                    | 2         | 0.88%   |
| Teslong Camera                         | 1         | 0.44%   |
| Razer USA                              | 1         | 0.44%   |
| Primax Electronics                     | 1         | 0.44%   |
| Jieli Technology                       | 1         | 0.44%   |
| Importek                               | 1         | 0.44%   |
| icSpring                               | 1         | 0.44%   |
| Goertek Electronics                    | 1         | 0.44%   |
| ALi                                    | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 9         | 3.91%   |
| Realtek Integrated_Webcam_HD                        | 6         | 2.61%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 6         | 2.61%   |
| Chicony HD Webcam                                   | 6         | 2.61%   |
| Chicony HD User Facing                              | 6         | 2.61%   |
| Acer HD Webcam                                      | 6         | 2.61%   |
| IMC Networks Integrated Camera                      | 5         | 2.17%   |
| Chicony HP Truevision HD                            | 5         | 2.17%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 1.74%   |
| Microdia Webcam Vitade AF                           | 4         | 1.74%   |
| Microdia Integrated_Webcam_HD                       | 4         | 1.74%   |
| Chicony USB2.0 Camera                               | 4         | 1.74%   |
| Apple iPhone 5/5C/5S/6/SE                           | 4         | 1.74%   |
| Acer EasyCamera                                     | 4         | 1.74%   |
| Syntek Integrated Camera                            | 3         | 1.3%    |
| Samsung Galaxy series, misc. (MTP mode)             | 3         | 1.3%    |
| Quanta HP TrueVision HD Camera                      | 3         | 1.3%    |
| Microdia PC Microscope camera                       | 3         | 1.3%    |
| Microdia Integrated Webcam                          | 3         | 1.3%    |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.3%    |
| Chicony EasyCamera                                  | 3         | 1.3%    |
| Alcor Micro USB 2.0 Camera                          | 3         | 1.3%    |
| Acer SunplusIT Integrated Camera                    | 3         | 1.3%    |
| Acer Integrated Camera                              | 3         | 1.3%    |
| Sunplus HD WebCam                                   | 2         | 0.87%   |
| Realtek Integrated Webcam                           | 2         | 0.87%   |
| Quanta HD User Facing                               | 2         | 0.87%   |
| Microsoft LifeCam Rear                              | 2         | 0.87%   |
| Microsoft LifeCam Front                             | 2         | 0.87%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 0.87%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.87%   |
| Logitech HD Webcam C615                             | 2         | 0.87%   |
| Lite-On HP Wide Vision HD Camera                    | 2         | 0.87%   |
| IMC Networks HD Camera                              | 2         | 0.87%   |
| Creative Live! Cam Sync HD [VF0770]                 | 2         | 0.87%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 0.87%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 0.87%   |
| Chicony Integrated HP HD Webcam                     | 2         | 0.87%   |
| Chicony Integrated Camera [ThinkPad]                | 2         | 0.87%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 0.87%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 0.87%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 0.87%   |
| Chicony HP HD Camera                                | 2         | 0.87%   |
| Chicony FJ Camera                                   | 2         | 0.87%   |
| Apple FaceTime HD Camera                            | 2         | 0.87%   |
| Apple Built-in iSight                               | 2         | 0.87%   |
| Acer Lenovo EasyCamera                              | 2         | 0.87%   |
| Acer HD Camera                                      | 2         | 0.87%   |
| Teslong Camera                                      | 1         | 0.43%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.43%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.43%   |
| Suyin HP Truevision HD                              | 1         | 0.43%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.43%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 0.43%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.43%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 0.43%   |
| Sunplus Integrated Camera                           | 1         | 0.43%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 0.43%   |
| Sunplus Depstech webcam MIC                         | 1         | 0.43%   |
| Sunplus ASUS USB2.0 Webcam                          | 1         | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 41.46%  |
| Synaptics                  | 13        | 31.71%  |
| Shenzhen Goodix Technology | 3         | 7.32%   |
| Elan Microelectronics      | 3         | 7.32%   |
| LighTuning Technology      | 2         | 4.88%   |
| AuthenTec                  | 2         | 4.88%   |
| Upek                       | 1         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 4         | 9.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 7.32%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 7.32%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 7.32%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 4.88%   |
| Validity Sensors VFS491                                                    | 2         | 4.88%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.88%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.88%   |
| Synaptics  WBDI                                                            | 2         | 4.88%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 4.88%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 4.88%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.88%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.44%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.44%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.44%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.44%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.44%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.44%   |
| Elan ELAN:ARM-M4                                                           | 1         | 2.44%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.44%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 9         | 56.25%  |
| Alcor Micro      | 4         | 25%     |
| SCM Microsystems | 1         | 6.25%   |
| OmniKey          | 1         | 6.25%   |
| O2 Micro         | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 37.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 12.5%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 6.25%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 6.25%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.25%   |
| Broadcom 5880                                                                | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 205       | 63.47%  |
| 1     | 97        | 30.03%  |
| 2     | 19        | 5.88%   |
| 3     | 2         | 0.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 42        | 31.34%  |
| Net/wireless             | 25        | 18.66%  |
| Graphics card            | 20        | 14.93%  |
| Chipcard                 | 14        | 10.45%  |
| Multimedia controller    | 12        | 8.96%   |
| Camera                   | 7         | 5.22%   |
| Storage                  | 5         | 3.73%   |
| Network                  | 3         | 2.24%   |
| Storage/raid             | 1         | 0.75%   |
| Net/ethernet             | 1         | 0.75%   |
| Modem                    | 1         | 0.75%   |
| Communication controller | 1         | 0.75%   |
| Card reader              | 1         | 0.75%   |
| Bluetooth                | 1         | 0.75%   |

