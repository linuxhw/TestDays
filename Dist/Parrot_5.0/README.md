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

Total: 167

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Acer          | Predator PT516-51s          | Notebook    | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [fc35a0726c](https://linux-hardware.org/?probe=fc35a0726c) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| Samsung       | 930QDB                      | Convertible | [e022aed2bc](https://linux-hardware.org/?probe=e022aed2bc) | Jun 28, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8b55dcfd2d](https://linux-hardware.org/?probe=8b55dcfd2d) | Jun 28, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d4969dd4f5](https://linux-hardware.org/?probe=d4969dd4f5) | Jun 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [d1b8d3ff84](https://linux-hardware.org/?probe=d1b8d3ff84) | Jun 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6348a01f19](https://linux-hardware.org/?probe=6348a01f19) | Jun 23, 2022 |
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
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
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
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
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
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Jumper        | EZbook                      | Notebook    | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
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
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
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
| 5.16.0-12parrot1-amd64   | 48        | 41.03%  |
| 5.14.0-9parrot1-amd64    | 39        | 33.33%  |
| 5.18.0-1parrot1-amd64    | 14        | 11.97%  |
| 5.15.0-15parrot1-amd64   | 7         | 5.98%   |
| 5.14.0-2parrot1-amd64    | 7         | 5.98%   |
| 5.16.0-12parrot1-686-pae | 1         | 0.85%   |
| 5.15.0-5parrot1-amd64    | 1         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.0  | 49        | 42.61%  |
| 5.14.0  | 44        | 38.26%  |
| 5.18.0  | 14        | 12.17%  |
| 5.15.0  | 8         | 6.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 49        | 42.61%  |
| 5.14    | 44        | 38.26%  |
| 5.18    | 14        | 12.17%  |
| 5.15    | 8         | 6.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 111       | 99.11%  |
| i686   | 1         | 0.89%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 78        | 68.42%  |
| KDE5    | 26        | 22.81%  |
| Unknown | 5         | 4.39%   |
| XFCE    | 3         | 2.63%   |
| KDE     | 1         | 0.88%   |
| GNOME   | 1         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 107       | 95.54%  |
| Wayland | 3         | 2.68%   |
| Tty     | 2         | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 68        | 60.71%  |
| Unknown | 41        | 36.61%  |
| SDDM    | 2         | 1.79%   |
| GDM     | 1         | 0.89%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 61        | 54.46%  |
| en_GB | 10        | 8.93%   |
| es_ES | 6         | 5.36%   |
| pt_BR | 5         | 4.46%   |
| en_IN | 5         | 4.46%   |
| fr_FR | 4         | 3.57%   |
| ru_RU | 3         | 2.68%   |
| pl_PL | 3         | 2.68%   |
| en_AU | 2         | 1.79%   |
| de_DE | 2         | 1.79%   |
| cs_CZ | 2         | 1.79%   |
| pt_PT | 1         | 0.89%   |
| it_IT | 1         | 0.89%   |
| fi_FI | 1         | 0.89%   |
| es_PE | 1         | 0.89%   |
| es_MX | 1         | 0.89%   |
| es_AR | 1         | 0.89%   |
| en_ZA | 1         | 0.89%   |
| en_DK | 1         | 0.89%   |
| en_CA | 1         | 0.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 66        | 58.93%  |
| EFI  | 46        | 41.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 96        | 85.71%  |
| Ext4    | 11        | 9.82%   |
| Overlay | 5         | 4.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 50        | 44.25%  |
| GPT     | 47        | 41.59%  |
| MBR     | 16        | 14.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 88.39%  |
| Yes       | 13        | 11.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 67.26%  |
| Yes       | 37        | 32.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 23        | 20.54%  |
| Lenovo              | 19        | 16.96%  |
| Dell                | 15        | 13.39%  |
| ASUSTek Computer    | 13        | 11.61%  |
| MSI                 | 7         | 6.25%   |
| Acer                | 5         | 4.46%   |
| Apple               | 4         | 3.57%   |
| Toshiba             | 3         | 2.68%   |
| Gigabyte Technology | 3         | 2.68%   |
| Samsung Electronics | 2         | 1.79%   |
| Microsoft           | 2         | 1.79%   |
| HUAWEI              | 2         | 1.79%   |
| Unknown             | 2         | 1.79%   |
| Sony                | 1         | 0.89%   |
| SLIMBOOK            | 1         | 0.89%   |
| Razer               | 1         | 0.89%   |
| Metabox             | 1         | 0.89%   |
| Jumper              | 1         | 0.89%   |
| Gateway             | 1         | 0.89%   |
| Fujitsu             | 1         | 0.89%   |
| ECS                 | 1         | 0.89%   |
| Daewoo Lucoms       | 1         | 0.89%   |
| Chuwi               | 1         | 0.89%   |
| ASRock              | 1         | 0.89%   |
| Alienware           | 1         | 0.89%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                               | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 2.68%   |
| HP ENVY x360 Convertible 13-bd0xxx                 | 3         | 2.68%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 2         | 1.79%   |
| HP ProDesk 600 G1 SFF                              | 2         | 1.79%   |
| HP Notebook                                        | 2         | 1.79%   |
| Dell Latitude E6410                                | 2         | 1.79%   |
| Unknown                                            | 2         | 1.79%   |
| Toshiba Satellite-L845                             | 1         | 0.89%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 0.89%   |
| Toshiba Satellite C75D-B                           | 1         | 0.89%   |
| Sony VPCSB1C5E                                     | 1         | 0.89%   |
| SLIMBOOK ONE-AMD-M4                                | 1         | 0.89%   |
| Samsung 930QDB                                     | 1         | 0.89%   |
| Samsung 550P5C/550P7C                              | 1         | 0.89%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.89%   |
| MSI MS-7A34                                        | 1         | 0.89%   |
| MSI MS-7529                                        | 1         | 0.89%   |
| MSI GE62 6QE                                       | 1         | 0.89%   |
| MSI Creator Z16 Hiroshi F A11UE                    | 1         | 0.89%   |
| Microsoft Surface Pro 3                            | 1         | 0.89%   |
| Microsoft Surface Book                             | 1         | 0.89%   |
| Metabox Edge-Pro NS50MU                            | 1         | 0.89%   |
| Lenovo Z40-70 80E6                                 | 1         | 0.89%   |
| Lenovo Yoga C930-13IKB 81C4                        | 1         | 0.89%   |
| Lenovo V330-15IKB 81AX                             | 1         | 0.89%   |
| Lenovo ThinkPad X230 2325N66                       | 1         | 0.89%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS        | 1         | 0.89%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW           | 1         | 0.89%   |
| Lenovo ThinkPad T480 20L6SCYP00                    | 1         | 0.89%   |
| Lenovo ThinkPad T470p 20J7S0CF00                   | 1         | 0.89%   |
| Lenovo ThinkPad L430 2465C32                       | 1         | 0.89%   |
| Lenovo ThinkPad E14 20RA0016GE                     | 1         | 0.89%   |
| Lenovo Legion 5 15ACH6 82JW                        | 1         | 0.89%   |
| Lenovo IdeaPad Y580                                | 1         | 0.89%   |
| Lenovo IdeaPad L340-17API 81LY                     | 1         | 0.89%   |
| Lenovo IdeaPad 320S-14IKB 80X4                     | 1         | 0.89%   |
| Lenovo H535 10117                                  | 1         | 0.89%   |
| Lenovo H530 10130                                  | 1         | 0.89%   |
| Lenovo B50-80 80EW                                 | 1         | 0.89%   |
| Jumper EZbook                                      | 1         | 0.89%   |
| HUAWEI HVY-WXX9                                    | 1         | 0.89%   |
| HUAWEI BOHK-WAX9X                                  | 1         | 0.89%   |
| HP ZBook Firefly 14 G7 Mobile Workstation          | 1         | 0.89%   |
| HP ProBook 4535s                                   | 1         | 0.89%   |
| HP ProBook 440 G5                                  | 1         | 0.89%   |
| HP Pavilion x360 Convertible 14-ba0xx              | 1         | 0.89%   |
| HP Pavilion Laptop 14-ec0xxx                       | 1         | 0.89%   |
| HP Pavilion g7                                     | 1         | 0.89%   |
| HP Pavilion dv6                                    | 1         | 0.89%   |
| HP Laptop 15q-dy0xxx                               | 1         | 0.89%   |
| HP Laptop 15-dy2xxx                                | 1         | 0.89%   |
| HP Laptop 15-bs2xx                                 | 1         | 0.89%   |
| HP ENVY x360 m6 Convertible                        | 1         | 0.89%   |
| HP ENVY x360 Convertible 15m-es0xxx                | 1         | 0.89%   |
| HP EliteBook 8470p                                 | 1         | 0.89%   |
| HP EliteBook 840 G3                                | 1         | 0.89%   |
| HP Compaq 8200 Elite SFF PC                        | 1         | 0.89%   |
| HP 250 G2                                          | 1         | 0.89%   |
| Gigabyte H61M-USB3H                                | 1         | 0.89%   |
| Gigabyte B450M DS3H                                | 1         | 0.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Latitude          | 8         | 7.14%   |
| Lenovo ThinkPad        | 7         | 6.25%   |
| Lenovo IdeaPad         | 5         | 4.46%   |
| HP ENVY                | 5         | 4.46%   |
| Dell Inspiron          | 5         | 4.46%   |
| HP Pavilion            | 4         | 3.57%   |
| MSI Modern             | 3         | 2.68%   |
| HP Laptop              | 3         | 2.68%   |
| Toshiba Satellite      | 2         | 1.79%   |
| Microsoft Surface      | 2         | 1.79%   |
| HP ProDesk             | 2         | 1.79%   |
| HP ProBook             | 2         | 1.79%   |
| HP Notebook            | 2         | 1.79%   |
| HP EliteBook           | 2         | 1.79%   |
| Dell OptiPlex          | 2         | 1.79%   |
| ASUS ROG               | 2         | 1.79%   |
| ASUS PRIME             | 2         | 1.79%   |
| Acer Nitro             | 2         | 1.79%   |
| Unknown                | 2         | 1.79%   |
| Toshiba Satellite-L845 | 1         | 0.89%   |
| Sony VPCSB1C5E         | 1         | 0.89%   |
| SLIMBOOK ONE-AMD-M4    | 1         | 0.89%   |
| Samsung 930QDB         | 1         | 0.89%   |
| Samsung 550P5C         | 1         | 0.89%   |
| Razer Blade            | 1         | 0.89%   |
| MSI MS-7A34            | 1         | 0.89%   |
| MSI MS-7529            | 1         | 0.89%   |
| MSI GE62               | 1         | 0.89%   |
| MSI Creator            | 1         | 0.89%   |
| Metabox Edge-Pro       | 1         | 0.89%   |
| Lenovo Z40-70          | 1         | 0.89%   |
| Lenovo Yoga            | 1         | 0.89%   |
| Lenovo V330-15IKB      | 1         | 0.89%   |
| Lenovo Legion          | 1         | 0.89%   |
| Lenovo H535            | 1         | 0.89%   |
| Lenovo H530            | 1         | 0.89%   |
| Lenovo B50-80          | 1         | 0.89%   |
| Jumper EZbook          | 1         | 0.89%   |
| HUAWEI HVY-WXX9        | 1         | 0.89%   |
| HUAWEI BOHK-WAX9X      | 1         | 0.89%   |
| HP ZBook               | 1         | 0.89%   |
| HP Compaq              | 1         | 0.89%   |
| HP 250                 | 1         | 0.89%   |
| Gigabyte H61M-USB3H    | 1         | 0.89%   |
| Gigabyte B450M         | 1         | 0.89%   |
| Gigabyte A320M-S2H     | 1         | 0.89%   |
| Gateway SX2855         | 1         | 0.89%   |
| Fujitsu LIFEBOOK       | 1         | 0.89%   |
| ECS GV460AA-ABA        | 1         | 0.89%   |
| Daewoo Lucoms OEM      | 1         | 0.89%   |
| Chuwi GemiBook         | 1         | 0.89%   |
| ASUS X75VC             | 1         | 0.89%   |
| ASUS X540SAA           | 1         | 0.89%   |
| ASUS VivoBook          | 1         | 0.89%   |
| ASUS TUF               | 1         | 0.89%   |
| ASUS H170M-E           | 1         | 0.89%   |
| ASUS H110M-K           | 1         | 0.89%   |
| ASUS CROSSHAIR         | 1         | 0.89%   |
| ASUS Basic             | 1         | 0.89%   |
| ASUS ASUS              | 1         | 0.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 19        | 16.96%  |
| 2017 | 11        | 9.82%   |
| 2012 | 11        | 9.82%   |
| 2020 | 10        | 8.93%   |
| 2013 | 10        | 8.93%   |
| 2018 | 9         | 8.04%   |
| 2011 | 8         | 7.14%   |
| 2019 | 7         | 6.25%   |
| 2016 | 7         | 6.25%   |
| 2010 | 5         | 4.46%   |
| 2015 | 4         | 3.57%   |
| 2014 | 4         | 3.57%   |
| 2009 | 2         | 1.79%   |
| 2007 | 2         | 1.79%   |
| 2022 | 1         | 0.89%   |
| 2008 | 1         | 0.89%   |
| 2006 | 1         | 0.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 77        | 68.75%  |
| Desktop     | 25        | 22.32%  |
| Convertible | 8         | 7.14%   |
| Tablet      | 2         | 1.79%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 112       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 112       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 33        | 29.2%   |
| 16.01-24.0  | 20        | 17.7%   |
| 8.01-16.0   | 20        | 17.7%   |
| 3.01-4.0    | 17        | 15.04%  |
| 32.01-64.0  | 16        | 14.16%  |
| 64.01-256.0 | 3         | 2.65%   |
| 24.01-32.0  | 2         | 1.77%   |
| 1.01-2.0    | 2         | 1.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 43        | 37.07%  |
| 1.01-2.0   | 36        | 31.03%  |
| 4.01-8.0   | 17        | 14.66%  |
| 3.01-4.0   | 12        | 10.34%  |
| 0.51-1.0   | 5         | 4.31%   |
| 8.01-16.0  | 2         | 1.72%   |
| 16.01-24.0 | 1         | 0.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 65        | 58.04%  |
| 2      | 40        | 35.71%  |
| 4      | 2         | 1.79%   |
| 3      | 2         | 1.79%   |
| 6      | 1         | 0.89%   |
| 5      | 1         | 0.89%   |
| 0      | 1         | 0.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 72.57%  |
| Yes       | 31        | 27.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 79.82%  |
| No        | 23        | 20.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 94.64%  |
| No        | 6         | 5.36%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 69.64%  |
| No        | 34        | 30.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 40        | 35.09%  |
| UK           | 7         | 6.14%   |
| Spain        | 6         | 5.26%   |
| Brazil       | 6         | 5.26%   |
| India        | 5         | 4.39%   |
| Mexico       | 4         | 3.51%   |
| Germany      | 4         | 3.51%   |
| Russia       | 3         | 2.63%   |
| Netherlands  | 3         | 2.63%   |
| France       | 3         | 2.63%   |
| Denmark      | 3         | 2.63%   |
| Canada       | 3         | 2.63%   |
| South Africa | 2         | 1.75%   |
| Morocco      | 2         | 1.75%   |
| Italy        | 2         | 1.75%   |
| Czechia      | 2         | 1.75%   |
| Austria      | 2         | 1.75%   |
| Australia    | 2         | 1.75%   |
| Sweden       | 1         | 0.88%   |
| Romania      | 1         | 0.88%   |
| Puerto Rico  | 1         | 0.88%   |
| Portugal     | 1         | 0.88%   |
| Peru         | 1         | 0.88%   |
| Nepal        | 1         | 0.88%   |
| Mongolia     | 1         | 0.88%   |
| Kenya        | 1         | 0.88%   |
| Georgia      | 1         | 0.88%   |
| Finland      | 1         | 0.88%   |
| Egypt        | 1         | 0.88%   |
| Bulgaria     | 1         | 0.88%   |
| Benin        | 1         | 0.88%   |
| Argentina    | 1         | 0.88%   |
| Algeria      | 1         | 0.88%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Seattle                | 3         | 2.61%   |
| Vienna                 | 2         | 1.74%   |
| Tangier                | 2         | 1.74%   |
| Ruskin                 | 2         | 1.74%   |
| Pensacola              | 2         | 1.74%   |
| Camden                 | 2         | 1.74%   |
| Amsterdam              | 2         | 1.74%   |
| Villa Carlos Paz       | 1         | 0.87%   |
| Viby J                 | 1         | 0.87%   |
| Vapi                   | 1         | 0.87%   |
| Ulan Bator             | 1         | 0.87%   |
| Uherské Hradiště    | 1         | 0.87%   |
| Ts'khinvali            | 1         | 0.87%   |
| Trivandrum             | 1         | 0.87%   |
| Tampere                | 1         | 0.87%   |
| Sydney                 | 1         | 0.87%   |
| Sumaré                | 1         | 0.87%   |
| St Petersburg          | 1         | 0.87%   |
| Springfield            | 1         | 0.87%   |
| Spotsylvania           | 1         | 0.87%   |
| South Hamilton         | 1         | 0.87%   |
| Skive                  | 1         | 0.87%   |
| Sao Paulo              | 1         | 0.87%   |
| Sao Joao de Meriti     | 1         | 0.87%   |
| Sao Bernardo do Campo  | 1         | 0.87%   |
| Santa Maria            | 1         | 0.87%   |
| San Juan               | 1         | 0.87%   |
| Saint Paul             | 1         | 0.87%   |
| Rho                    | 1         | 0.87%   |
| Pretoria               | 1         | 0.87%   |
| Prague                 | 1         | 0.87%   |
| Point Pleasant Beach   | 1         | 0.87%   |
| Plovdiv                | 1         | 0.87%   |
| Pittsburgh             | 1         | 0.87%   |
| Phoenix                | 1         | 0.87%   |
| Orofino                | 1         | 0.87%   |
| Opelousas              | 1         | 0.87%   |
| Nairobi                | 1         | 0.87%   |
| Mt. Pleasant           | 1         | 0.87%   |
| Mostoles               | 1         | 0.87%   |
| Moscow                 | 1         | 0.87%   |
| Montreal               | 1         | 0.87%   |
| Montigny-le-Bretonneux | 1         | 0.87%   |
| Milton                 | 1         | 0.87%   |
| Mexicali               | 1         | 0.87%   |
| Melbourne              | 1         | 0.87%   |
| Mazatlán              | 1         | 0.87%   |
| Mata de Sao Joao       | 1         | 0.87%   |
| Maricopa               | 1         | 0.87%   |
| Mangalagiri            | 1         | 0.87%   |
| Madrid                 | 1         | 0.87%   |
| Lynwood                | 1         | 0.87%   |
| Los Angeles            | 1         | 0.87%   |
| Long Eaton             | 1         | 0.87%   |
| London                 | 1         | 0.87%   |
| Lisbon                 | 1         | 0.87%   |
| Lille                  | 1         | 0.87%   |
| Leduc                  | 1         | 0.87%   |
| La Paz                 | 1         | 0.87%   |
| La Magdalena           | 1         | 0.87%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 33     | 16.34%  |
| WDC                 | 21        | 24     | 13.73%  |
| Seagate             | 21        | 26     | 13.73%  |
| Toshiba             | 15        | 16     | 9.8%    |
| Kingston            | 9         | 10     | 5.88%   |
| Unknown             | 6         | 8      | 3.92%   |
| SanDisk             | 6         | 10     | 3.92%   |
| Intel               | 5         | 15     | 3.27%   |
| Hitachi             | 5         | 6      | 3.27%   |
| China               | 5         | 6      | 3.27%   |
| Micron Technology   | 3         | 3      | 1.96%   |
| HGST                | 3         | 3      | 1.96%   |
| SK hynix            | 2         | 2      | 1.31%   |
| PNY                 | 2         | 2      | 1.31%   |
| Crucial             | 2         | 2      | 1.31%   |
| Apple               | 2         | 2      | 1.31%   |
| A-DATA Technology   | 2         | 2      | 1.31%   |
| YMTC                | 1         | 1      | 0.65%   |
| Team                | 1         | 1      | 0.65%   |
| SPCC                | 1         | 1      | 0.65%   |
| Silicon Motion      | 1         | 1      | 0.65%   |
| S3+                 | 1         | 1      | 0.65%   |
| RZX                 | 1         | 1      | 0.65%   |
| Plextor             | 1         | 1      | 0.65%   |
| Phison              | 1         | 1      | 0.65%   |
| Netac               | 1         | 1      | 0.65%   |
| LITEON              | 1         | 1      | 0.65%   |
| KingSpec            | 1         | 1      | 0.65%   |
| KingFast            | 1         | 2      | 0.65%   |
| Intenso             | 1         | 2      | 0.65%   |
| HUAWEI              | 1         | 1      | 0.65%   |
| BR                  | 1         | 1      | 0.65%   |
| BHT                 | 1         | 1      | 0.65%   |
| ASMT                | 1         | 1      | 0.65%   |
| ASMedia             | 1         | 1      | 0.65%   |
| Apacer              | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                | 5         | 2.91%   |
| Kingston NVMe SSD Drive 512GB         | 3         | 1.74%   |
| Intel HBRPEKNX0202AH 512GB            | 3         | 1.74%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 2         | 1.16%   |
| WDC WD5000AADS-00S9B0 500GB           | 2         | 1.16%   |
| Unknown MMC Card  32GB                | 2         | 1.16%   |
| Toshiba MQ01ABD075 752GB              | 2         | 1.16%   |
| Toshiba DT01ACA200 2TB                | 2         | 1.16%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 1.16%   |
| Seagate ST250DM000-1BD141 250GB       | 2         | 1.16%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 2         | 1.16%   |
| SanDisk NVMe SSD Drive 1TB            | 2         | 1.16%   |
| Samsung SSD 970 EVO Plus 1TB          | 2         | 1.16%   |
| Samsung SSD 850 EVO 250GB             | 2         | 1.16%   |
| Samsung NVMe SSD Drive 1024GB         | 2         | 1.16%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 1.16%   |
| Intel NVMe SSD Drive 512GB            | 2         | 1.16%   |
| Intel NVMe SSD Drive 32GB             | 2         | 1.16%   |
| Intel HBRPEKNX0202AHO 32GB            | 2         | 1.16%   |
| HGST HTS721010A9E630 1TB              | 2         | 1.16%   |
| YMTC PC005 512GB                      | 1         | 0.58%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 0.58%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 0.58%   |
| WDC WDBRPG5000ANC-WRSN 500GB          | 1         | 0.58%   |
| WDC WDBNCE2500PNC 250GB SSD           | 1         | 0.58%   |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 0.58%   |
| WDC WD5000LPCX-60VHAT1 500GB          | 1         | 0.58%   |
| WDC WD3200BPVT-00JJ5T0 320GB          | 1         | 0.58%   |
| WDC WD20EZAZ-00GGJB0 2TB              | 1         | 0.58%   |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1         | 0.58%   |
| WDC WD10SPZX-75Z10T2 1TB              | 1         | 0.58%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.58%   |
| WDC WD10PURX-64E5EY0 1TB              | 1         | 0.58%   |
| WDC WD10EZRX-00L4HB0 1TB              | 1         | 0.58%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1         | 0.58%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 0.58%   |
| WDC WD10EADX-22TDHB0 1TB              | 1         | 0.58%   |
| WDC PC SN720 SDAPNTW-512G-1101 512GB  | 1         | 0.58%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB    | 1         | 0.58%   |
| Unknown SE32G  32GB                   | 1         | 0.58%   |
| Unknown SD/MMC/MS PRO 64GB            | 1         | 0.58%   |
| Unknown SD  128GB                     | 1         | 0.58%   |
| Unknown ISOCOM  64GB                  | 1         | 0.58%   |
| Unknown 256GB PCS 2.5" S              | 1         | 0.58%   |
| Toshiba MQ01ACF050 500GB              | 1         | 0.58%   |
| Toshiba MQ01ABD100 1TB                | 1         | 0.58%   |
| Toshiba MK2555GSXF 250GB              | 1         | 0.58%   |
| Toshiba MK2533GSGF 250GB              | 1         | 0.58%   |
| Toshiba HDWD105 500GB                 | 1         | 0.58%   |
| Toshiba DT01ACA050 500GB              | 1         | 0.58%   |
| Team TM8PS7512G 512GB SSD             | 1         | 0.58%   |
| SPCC Solid State Disk 240GB           | 1         | 0.58%   |
| SK hynix NVMe SSD Drive 1024GB        | 1         | 0.58%   |
| SK hynix HFS128G32TNF-N3A0A 128GB SSD | 1         | 0.58%   |
| Silicon Motion NVMe SSD Drive 128GB   | 1         | 0.58%   |
| Seagate ST9500325AS 500GB             | 1         | 0.58%   |
| Seagate ST9250315AS 250GB             | 1         | 0.58%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 0.58%   |
| Seagate ST500LM030-1RK17D 500GB       | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 26     | 34.43%  |
| Toshiba             | 15        | 16     | 24.59%  |
| WDC                 | 13        | 15     | 21.31%  |
| Hitachi             | 5         | 6      | 8.2%    |
| HGST                | 3         | 3      | 4.92%   |
| Samsung Electronics | 2         | 2      | 3.28%   |
| Unknown             | 1         | 2      | 1.64%   |
| ASMedia             | 1         | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 13     | 18.37%  |
| WDC                 | 6         | 6      | 12.24%  |
| Kingston            | 5         | 6      | 10.2%   |
| China               | 5         | 6      | 10.2%   |
| SanDisk             | 2         | 2      | 4.08%   |
| PNY                 | 2         | 2      | 4.08%   |
| Crucial             | 2         | 2      | 4.08%   |
| Unknown             | 1         | 1      | 2.04%   |
| Team                | 1         | 1      | 2.04%   |
| SPCC                | 1         | 1      | 2.04%   |
| SK hynix            | 1         | 1      | 2.04%   |
| S3+                 | 1         | 1      | 2.04%   |
| RZX                 | 1         | 1      | 2.04%   |
| Plextor             | 1         | 1      | 2.04%   |
| Netac               | 1         | 1      | 2.04%   |
| Micron Technology   | 1         | 1      | 2.04%   |
| LITEON              | 1         | 1      | 2.04%   |
| KingSpec            | 1         | 1      | 2.04%   |
| KingFast            | 1         | 1      | 2.04%   |
| Intenso             | 1         | 2      | 2.04%   |
| BR                  | 1         | 1      | 2.04%   |
| BHT                 | 1         | 1      | 2.04%   |
| ASMT                | 1         | 1      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |
| Apacer              | 1         | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 52        | 71     | 36.88%  |
| SSD     | 46        | 56     | 32.62%  |
| NVMe    | 37        | 57     | 26.24%  |
| MMC     | 4         | 5      | 2.84%   |
| Unknown | 2         | 2      | 1.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 80        | 122    | 62.99%  |
| NVMe | 37        | 57     | 29.13%  |
| SAS  | 6         | 7      | 4.72%   |
| MMC  | 4         | 5      | 3.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 82     | 60.42%  |
| 0.51-1.0   | 30        | 34     | 31.25%  |
| 1.01-2.0   | 8         | 11     | 8.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 27        | 23.89%  |
| 501-1000   | 24        | 21.24%  |
| 251-500    | 20        | 17.7%   |
| Unknown    | 16        | 14.16%  |
| 1001-2000  | 15        | 13.27%  |
| 1-20       | 4         | 3.54%   |
| 2001-3000  | 3         | 2.65%   |
| 21-50      | 2         | 1.77%   |
| 51-100     | 2         | 1.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 38        | 33.04%  |
| 51-100    | 19        | 16.52%  |
| Unknown   | 16        | 13.91%  |
| 101-250   | 12        | 10.43%  |
| 1-20      | 12        | 10.43%  |
| 251-500   | 11        | 9.57%   |
| 501-1000  | 6         | 5.22%   |
| 1001-2000 | 1         | 0.87%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-00JJ5T0 320GB        | 1         | 1      | 7.69%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1         | 1      | 7.69%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 7.69%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 7.69%   |
| Seagate ST3320418AS 320GB           | 1         | 1      | 7.69%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 7.69%   |
| Seagate ST250DM000-1BD141 250GB     | 1         | 1      | 7.69%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 1         | 1      | 7.69%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 7.69%   |
| SanDisk SD6SF1M128G1022I 128GB SSD  | 1         | 1      | 7.69%   |
| Samsung Electronics HM500JI 500GB   | 1         | 1      | 7.69%   |
| Plextor PX-512M6Pro 512GB SSD       | 1         | 1      | 7.69%   |
| A-DATA Technology SX7000NP 128GB    | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 41.67%  |
| WDC                 | 2         | 2      | 16.67%  |
| Toshiba             | 1         | 1      | 8.33%   |
| SanDisk             | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |
| Plextor             | 1         | 1      | 8.33%   |
| A-DATA Technology   | 1         | 1      | 8.33%   |

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
| HDD  | 8         | 10     | 72.73%  |
| SSD  | 2         | 2      | 18.18%  |
| NVMe | 1         | 1      | 9.09%   |

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
| Works    | 62        | 79     | 48.82%  |
| Detected | 56        | 98     | 44.09%  |
| Malfunc  | 8         | 13     | 6.3%    |
| Failed   | 1         | 1      | 0.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 75        | 56.39%  |
| AMD                         | 18        | 13.53%  |
| Samsung Electronics         | 16        | 12.03%  |
| SanDisk                     | 7         | 5.26%   |
| Nvidia                      | 4         | 3.01%   |
| Kingston Technology Company | 4         | 3.01%   |
| Micron Technology           | 2         | 1.5%    |
| Yangtze Memory Technologies | 1         | 0.75%   |
| SK hynix                    | 1         | 0.75%   |
| Silicon Motion              | 1         | 0.75%   |
| Phison Electronics          | 1         | 0.75%   |
| ASMedia Technology          | 1         | 0.75%   |
| Apple                       | 1         | 0.75%   |
| ADATA Technology            | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16        | 10.46%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9         | 5.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 9         | 5.88%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 5.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8         | 5.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 3.27%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 5         | 3.27%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 5         | 3.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 3.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 2.61%   |
| Samsung NVMe SSD Controller 980                                                         | 4         | 2.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.61%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 1.96%   |
| Intel Non-Volatile memory controller                                                    | 3         | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.96%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 1.31%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 1.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 1.31%   |
| Micron Non-Volatile memory controller                                                   | 2         | 1.31%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.31%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.31%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 1.31%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 1.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.31%   |
| Yangtze Memory Non-Volatile memory controller                                           | 1         | 0.65%   |
| SK hynix Gold P31 SSD                                                                   | 1         | 0.65%   |
| Silicon Motion Non-Volatile memory controller                                           | 1         | 0.65%   |
| SanDisk PC SN520 NVMe SSD                                                               | 1         | 0.65%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.65%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.65%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                                | 1         | 0.65%   |
| Nvidia MCP89 SATA Controller                                                            | 1         | 0.65%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.65%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.65%   |
| Nvidia MCP61 IDE                                                                        | 1         | 0.65%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 0.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.65%   |
| Intel SSD 660P Series                                                                   | 1         | 0.65%   |
| Intel SSD 600P Series                                                                   | 1         | 0.65%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 0.65%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 0.65%   |
| Intel Comet Lake PCH-H RAID                                                             | 1         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1         | 0.65%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 0.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 0.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 0.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 0.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 0.65%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1         | 0.65%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 0.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 0.65%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 0.65%   |
| Apple ANS2 NVMe Controller                                                              | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 66        | 48.89%  |
| NVMe | 37        | 27.41%  |
| RAID | 17        | 12.59%  |
| IDE  | 15        | 11.11%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 87        | 77.68%  |
| AMD    | 25        | 22.32%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 4.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 2.68%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 2.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 2         | 1.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 1.79%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 2         | 1.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 2         | 1.79%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 2         | 1.79%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 2         | 1.79%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 2         | 1.79%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 2         | 1.79%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 2         | 1.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.79%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 2         | 1.79%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 1.79%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz     | 1         | 0.89%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz  | 1         | 0.89%   |
| Intel Pentium CPU N3530 @ 2.16GHz       | 1         | 0.89%   |
| Intel Pentium CPU G630 @ 2.70GHz        | 1         | 0.89%   |
| Intel Pentium CPU G3260 @ 3.30GHz       | 1         | 0.89%   |
| Intel Pentium CPU 4415U @ 2.30GHz       | 1         | 0.89%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 1         | 0.89%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 0.89%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 0.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 0.89%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 0.89%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 0.89%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 0.89%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 0.89%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 1         | 0.89%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 0.89%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 0.89%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 0.89%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 0.89%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1         | 0.89%   |
| Intel Core i7-10850H CPU @ 2.70GHz      | 1         | 0.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 0.89%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 0.89%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 1         | 0.89%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 0.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 0.89%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 1         | 0.89%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 0.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 0.89%   |
| Intel Core i5-4670S CPU @ 3.10GHz       | 1         | 0.89%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1         | 0.89%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 1         | 0.89%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 0.89%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 0.89%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 0.89%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1         | 0.89%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 1         | 0.89%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 1         | 0.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 0.89%   |
| Intel Core i3-9100F CPU @ 3.60GHz       | 1         | 0.89%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 0.89%   |
| Intel Core i3-7100 CPU @ 3.90GHz        | 1         | 0.89%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 1         | 0.89%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 0.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 23        | 20.54%  |
| Intel Core i7      | 22        | 19.64%  |
| Intel Core i3      | 13        | 11.61%  |
| Other              | 11        | 9.82%   |
| AMD Ryzen 7        | 8         | 7.14%   |
| Intel Core 2 Duo   | 6         | 5.36%   |
| Intel Celeron      | 6         | 5.36%   |
| AMD Ryzen 5        | 6         | 5.36%   |
| Intel Pentium      | 4         | 3.57%   |
| AMD FX             | 2         | 1.79%   |
| AMD A6             | 2         | 1.79%   |
| Intel Xeon         | 1         | 0.89%   |
| Intel Pentium Dual | 1         | 0.89%   |
| Intel Core 2       | 1         | 0.89%   |
| AMD Ryzen 9        | 1         | 0.89%   |
| AMD Ryzen 3        | 1         | 0.89%   |
| AMD E2             | 1         | 0.89%   |
| AMD Athlon 64 X2   | 1         | 0.89%   |
| AMD A8             | 1         | 0.89%   |
| AMD A4             | 1         | 0.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 53        | 47.32%  |
| 4      | 41        | 36.61%  |
| 8      | 9         | 8.04%   |
| 6      | 7         | 6.25%   |
| 14     | 1         | 0.89%   |
| 12     | 1         | 0.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 112       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 81        | 72.32%  |
| 1      | 31        | 27.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 112       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 46.43%  |
| 0x206a7    | 7         | 6.25%   |
| 0x806e9    | 6         | 5.36%   |
| 0x806c1    | 5         | 4.46%   |
| 0x306a9    | 4         | 3.57%   |
| 0x406e3    | 3         | 2.68%   |
| 0x1067a    | 3         | 2.68%   |
| 0xa0652    | 2         | 1.79%   |
| 0x906e9    | 2         | 1.79%   |
| 0x806ea    | 2         | 1.79%   |
| 0x706e5    | 2         | 1.79%   |
| 0x706a8    | 2         | 1.79%   |
| 0x40651    | 2         | 1.79%   |
| 0x306c3    | 2         | 1.79%   |
| 0x08001138 | 2         | 1.79%   |
| 0x07030105 | 2         | 1.79%   |
| 0x906ed    | 1         | 0.89%   |
| 0x906ea    | 1         | 0.89%   |
| 0x906a3    | 1         | 0.89%   |
| 0x806ec    | 1         | 0.89%   |
| 0x806eb    | 1         | 0.89%   |
| 0x806d1    | 1         | 0.89%   |
| 0x6f6      | 1         | 0.89%   |
| 0x506c9    | 1         | 0.89%   |
| 0x08701021 | 1         | 0.89%   |
| 0x08600106 | 1         | 0.89%   |
| 0x08108109 | 1         | 0.89%   |
| 0x06006113 | 1         | 0.89%   |
| 0x06001119 | 1         | 0.89%   |
| 0x03000027 | 1         | 0.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 23        | 20.54%  |
| SandyBridge      | 12        | 10.71%  |
| Haswell          | 9         | 8.04%   |
| TigerLake        | 7         | 6.25%   |
| IvyBridge        | 7         | 6.25%   |
| Penryn           | 6         | 5.36%   |
| Zen 2            | 5         | 4.46%   |
| Unknown          | 5         | 4.46%   |
| Skylake          | 4         | 3.57%   |
| Zen              | 3         | 2.68%   |
| IceLake          | 3         | 2.68%   |
| Goldmont plus    | 3         | 2.68%   |
| Excavator        | 3         | 2.68%   |
| Zen+             | 2         | 1.79%   |
| Zen 3            | 2         | 1.79%   |
| Westmere         | 2         | 1.79%   |
| Silvermont       | 2         | 1.79%   |
| Puma             | 2         | 1.79%   |
| Piledriver       | 2         | 1.79%   |
| Core             | 2         | 1.79%   |
| CometLake        | 2         | 1.79%   |
| Broadwell        | 2         | 1.79%   |
| K8 Hammer        | 1         | 0.89%   |
| K10 Llano        | 1         | 0.89%   |
| Goldmont         | 1         | 0.89%   |
| Alderlake Hybrid | 1         | 0.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 80        | 55.56%  |
| Nvidia | 32        | 22.22%  |
| AMD    | 32        | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12        | 8.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 7         | 4.76%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 4.08%   |
| Intel UHD Graphics 620                                                      | 5         | 3.4%    |
| Intel HD Graphics 620                                                       | 5         | 3.4%    |
| AMD Lucienne                                                                | 4         | 2.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 3         | 2.04%   |
| Intel HD Graphics 630                                                       | 3         | 2.04%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 2.04%   |
| AMD Renoir                                                                  | 3         | 2.04%   |
| Nvidia MCP89 [GeForce 320M]                                                 | 2         | 1.36%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 1.36%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 2         | 1.36%   |
| Intel HD Graphics 5500                                                      | 2         | 1.36%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.36%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 1.36%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 2         | 1.36%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 1.36%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 2         | 1.36%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                  | 2         | 1.36%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.36%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.36%   |
| AMD Cezanne                                                                 | 2         | 1.36%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.68%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 1         | 0.68%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.68%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.68%   |
| Nvidia GP108GLM [Quadro P520]                                               | 1         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.68%   |
| Nvidia GM206M [GeForce GTX 965M]                                            | 1         | 0.68%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1         | 0.68%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 0.68%   |
| Nvidia GM108M [GeForce 930MX]                                               | 1         | 0.68%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 0.68%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 0.68%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.68%   |
| Nvidia GK107M [GeForce GTX 660M]                                            | 1         | 0.68%   |
| Nvidia GK107M [GeForce GT 650M]                                             | 1         | 0.68%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1         | 0.68%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 0.68%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                        | 1         | 0.68%   |
| Nvidia GF108M [GeForce GT 620M]                                             | 1         | 0.68%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1         | 0.68%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                 | 1         | 0.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 0.68%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                    | 1         | 0.68%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 1         | 0.68%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                  | 1         | 0.68%   |
| Nvidia G96CM [GeForce 9600M GT]                                             | 1         | 0.68%   |
| Nvidia C79 [GeForce 9400M]                                                  | 1         | 0.68%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1         | 0.68%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1         | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 51        | 45.54%  |
| 1 x AMD        | 21        | 18.75%  |
| Intel + Nvidia | 18        | 16.07%  |
| 1 x Nvidia     | 10        | 8.93%   |
| Intel + AMD    | 7         | 6.25%   |
| AMD + Nvidia   | 3         | 2.68%   |
| 2 x Nvidia     | 1         | 0.89%   |
| 2 x AMD        | 1         | 0.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 101       | 89.38%  |
| Proprietary | 10        | 8.85%   |
| Unknown     | 2         | 1.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 86        | 76.11%  |
| 1.01-2.0   | 10        | 8.85%   |
| 0.01-0.5   | 7         | 6.19%   |
| 3.01-4.0   | 5         | 4.42%   |
| 0.51-1.0   | 4         | 3.54%   |
| 7.01-8.0   | 1         | 0.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 22        | 18.33%  |
| BOE                     | 19        | 15.83%  |
| LG Display              | 13        | 10.83%  |
| Samsung Electronics     | 11        | 9.17%   |
| Chimei Innolux          | 10        | 8.33%   |
| Goldstar                | 4         | 3.33%   |
| Apple                   | 4         | 3.33%   |
| AOC                     | 4         | 3.33%   |
| Lenovo                  | 3         | 2.5%    |
| InfoVision              | 3         | 2.5%    |
| Chi Mei Optoelectronics | 3         | 2.5%    |
| Acer                    | 3         | 2.5%    |
| Toshiba                 | 2         | 1.67%   |
| NEC Computers           | 2         | 1.67%   |
| Dell                    | 2         | 1.67%   |
| BenQ                    | 2         | 1.67%   |
| Vizio                   | 1         | 0.83%   |
| Unknown (AAA)           | 1         | 0.83%   |
| Unknown                 | 1         | 0.83%   |
| STD                     | 1         | 0.83%   |
| Plain Tree Systems      | 1         | 0.83%   |
| Philips                 | 1         | 0.83%   |
| PANDA                   | 1         | 0.83%   |
| Panasonic               | 1         | 0.83%   |
| ONN                     | 1         | 0.83%   |
| Kogan                   | 1         | 0.83%   |
| CSO                     | 1         | 0.83%   |
| Ativa                   | 1         | 0.83%   |
| Ancor Communications    | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch          | 3         | 2.46%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 2.46%   |
| Lenovo LCD Monitor LEN1144 1920x1200 518x324mm 24.1-inch              | 2         | 1.64%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1         | 0.82%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                 | 1         | 0.82%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch              | 1         | 0.82%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                      | 1         | 0.82%   |
| Toshiba TSB-TV TSB0205 1920x1080 708x398mm 32.0-inch                  | 1         | 0.82%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                         | 1         | 0.82%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch  | 1         | 0.82%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch   | 1         | 0.82%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch     | 1         | 0.82%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SDC4156 1920x1080 294x165mm 13.3-inch | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 890x500mm 40.2-inch | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 890x500mm 40.2-inch | 1         | 0.82%   |
| Plain Tree Systems LCD Monitor PTS0899 1680x1050 474x296mm 22.0-inch  | 1         | 0.82%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1         | 0.82%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch               | 1         | 0.82%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 1         | 0.82%   |
| ONN ONA24HB19T01 ONN0101 1920x1080 517x323mm 24.0-inch                | 1         | 0.82%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 1         | 0.82%   |
| NEC Computers EA243WM NEC6863 1920x1200 519x324mm 24.1-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD05BC 3840x2160 309x174mm 14.0-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD0574 1920x1080 309x175mm 14.0-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD045A 1366x768 293x165mm 13.2-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD0292 1366x768 309x174mm 14.0-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD0257 1440x900 304x190mm 14.1-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 1         | 0.82%   |
| Lenovo L200pwD LEN1156 1680x1050 430x270mm 20.0-inch                  | 1         | 0.82%   |
| Lenovo D27-30 LEN66B8 1920x1080 597x336mm 27.0-inch                   | 1         | 0.82%   |
| Kogan KAMN27F7TA KGN0270 1920x1080 600x330mm 27.0-inch                | 1         | 0.82%   |
| Goldstar TV GSM0002 1920x1080 1150x650mm 52.0-inch                    | 1         | 0.82%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch            | 1         | 0.82%   |
| Goldstar L1742 GSM449B 1280x1024 338x270mm 17.0-inch                  | 1         | 0.82%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                 | 1         | 0.82%   |
| Dell P2412H DELA07D 1920x1080 530x300mm 24.0-inch                     | 1         | 0.82%   |
| Dell LCD Monitor P2417H                                               | 1         | 0.82%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                 | 1         | 0.82%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 1         | 0.82%   |
| Chimei Innolux LCD Monitor CMN1736 1600x900 382x214mm 17.2-inch       | 1         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 1         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 0.82%   |
| Chimei Innolux LCD Monitor CMN1526 1920x1080 344x193mm 15.5-inch      | 1         | 0.82%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 1         | 0.82%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 1         | 0.82%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 1         | 0.82%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 1         | 0.82%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch       | 1         | 0.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 48        | 42.48%  |
| 1366x768 (WXGA)    | 29        | 25.66%  |
| 1680x1050 (WSXGA+) | 6         | 5.31%   |
| 1600x900 (HD+)     | 6         | 5.31%   |
| 3840x2160 (4K)     | 5         | 4.42%   |
| 1280x800 (WXGA)    | 4         | 3.54%   |
| 2560x1600          | 2         | 1.77%   |
| 2560x1440 (QHD)    | 2         | 1.77%   |
| 2160x1440          | 2         | 1.77%   |
| 1920x1200 (WUXGA)  | 2         | 1.77%   |
| 1440x900 (WXGA+)   | 2         | 1.77%   |
| 1280x1024 (SXGA)   | 2         | 1.77%   |
| 3840x1080          | 1         | 0.88%   |
| 2880x1800          | 1         | 0.88%   |
| Unknown            | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 36        | 30.25%  |
| 14      | 16        | 13.45%  |
| 13      | 13        | 10.92%  |
| 17      | 10        | 8.4%    |
| 27      | 6         | 5.04%   |
| 24      | 6         | 5.04%   |
| 23      | 4         | 3.36%   |
| 22      | 4         | 3.36%   |
| 21      | 4         | 3.36%   |
| 16      | 3         | 2.52%   |
| 12      | 3         | 2.52%   |
| Unknown | 3         | 2.52%   |
| 11      | 2         | 1.68%   |
| 84      | 1         | 0.84%   |
| 72      | 1         | 0.84%   |
| 52      | 1         | 0.84%   |
| 48      | 1         | 0.84%   |
| 41      | 1         | 0.84%   |
| 40      | 1         | 0.84%   |
| 32      | 1         | 0.84%   |
| 31      | 1         | 0.84%   |
| 20      | 1         | 0.84%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 63        | 53.39%  |
| 501-600     | 15        | 12.71%  |
| 201-300     | 11        | 9.32%   |
| 401-500     | 9         | 7.63%   |
| 351-400     | 9         | 7.63%   |
| Unknown     | 3         | 2.54%   |
| 1501-2000   | 2         | 1.69%   |
| 1001-1500   | 2         | 1.69%   |
| 801-900     | 1         | 0.85%   |
| 701-800     | 1         | 0.85%   |
| 601-700     | 1         | 0.85%   |
| 901-1000    | 1         | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 87        | 79.82%  |
| 16/10   | 16        | 14.68%  |
| Unknown | 3         | 2.75%   |
| 5/4     | 2         | 1.83%   |
| 3/2     | 1         | 0.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 37        | 30.83%  |
| 81-90          | 23        | 19.17%  |
| 201-250        | 14        | 11.67%  |
| 121-130        | 7         | 5.83%   |
| 71-80          | 6         | 5%      |
| 301-350        | 6         | 5%      |
| More than 1000 | 4         | 3.33%   |
| 251-300        | 4         | 3.33%   |
| 61-70          | 3         | 2.5%    |
| Unknown        | 3         | 2.5%    |
| 51-60          | 2         | 1.67%   |
| 351-500        | 2         | 1.67%   |
| 151-200        | 2         | 1.67%   |
| 141-150        | 2         | 1.67%   |
| 111-120        | 2         | 1.67%   |
| 501-1000       | 2         | 1.67%   |
| 131-140        | 1         | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 38        | 32.48%  |
| 121-160       | 35        | 29.91%  |
| 51-100        | 25        | 21.37%  |
| 161-240       | 9         | 7.69%   |
| 1-50          | 4         | 3.42%   |
| More than 240 | 3         | 2.56%   |
| Unknown       | 3         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 94        | 82.46%  |
| 2     | 15        | 13.16%  |
| 0     | 3         | 2.63%   |
| 3     | 2         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 69        | 33.82%  |
| Intel                           | 57        | 27.94%  |
| Qualcomm Atheros                | 18        | 8.82%   |
| Broadcom                        | 10        | 4.9%    |
| TP-Link                         | 6         | 2.94%   |
| MediaTek                        | 6         | 2.94%   |
| Samsung Electronics             | 5         | 2.45%   |
| Ralink Technology               | 4         | 1.96%   |
| Qualcomm Atheros Communications | 3         | 1.47%   |
| Nvidia                          | 3         | 1.47%   |
| ASUSTek Computer                | 3         | 1.47%   |
| NetGear                         | 2         | 0.98%   |
| Microsoft                       | 2         | 0.98%   |
| Marvell Technology Group        | 2         | 0.98%   |
| Huawei Technologies             | 2         | 0.98%   |
| Apple                           | 2         | 0.98%   |
| vivo                            | 1         | 0.49%   |
| Ralink                          | 1         | 0.49%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.49%   |
| Mercucys                        | 1         | 0.49%   |
| Linksys                         | 1         | 0.49%   |
| ICS Advent                      | 1         | 0.49%   |
| Gemtek                          | 1         | 0.49%   |
| D-Link System                   | 1         | 0.49%   |
| Broadcom Limited                | 1         | 0.49%   |
| ASIX Electronics                | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 14.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 4.66%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 6         | 2.54%   |
| Realtek 802.11ac NIC                                              | 5         | 2.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.12%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.12%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 2.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.12%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 4         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.69%   |
| Intel Wireless 3165                                               | 4         | 1.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 1.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.27%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 1.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 1.27%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.27%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.27%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.27%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.85%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.85%   |
| NetGear A6210                                                     | 2         | 0.85%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 2         | 0.85%   |
| Intel Wireless 3160                                               | 2         | 0.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.85%   |
| Intel Centrino Wireless-N 2200                                    | 2         | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.85%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.85%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 2         | 0.85%   |
| vivo 1806                                                         | 1         | 0.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.42%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.42%   |
| TP-Link 802.11ac NIC                                              | 1         | 0.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.42%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.42%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1         | 0.42%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.42%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.42%   |
| Ralink RT5572 Wireless Adapter                                    | 1         | 0.42%   |
| Ralink RT5372 Wireless Adapter                                    | 1         | 0.42%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.42%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.42%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 36.36%  |
| Realtek Semiconductor           | 30        | 22.73%  |
| Qualcomm Atheros                | 14        | 10.61%  |
| Broadcom                        | 8         | 6.06%   |
| TP-Link                         | 6         | 4.55%   |
| Ralink Technology               | 4         | 3.03%   |
| MediaTek                        | 4         | 3.03%   |
| Qualcomm Atheros Communications | 3         | 2.27%   |
| ASUSTek Computer                | 3         | 2.27%   |
| NetGear                         | 2         | 1.52%   |
| Microsoft                       | 2         | 1.52%   |
| Marvell Technology Group        | 2         | 1.52%   |
| Ralink                          | 1         | 0.76%   |
| Mercucys                        | 1         | 0.76%   |
| Linksys                         | 1         | 0.76%   |
| Gemtek                          | 1         | 0.76%   |
| D-Link System                   | 1         | 0.76%   |
| Broadcom Limited                | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 6         | 4.55%   |
| Realtek 802.11ac NIC                                                    | 5         | 3.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.79%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.79%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 3.79%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 4         | 3.03%   |
| Intel Wireless 3165                                                     | 4         | 3.03%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.27%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 2.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 2.27%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.27%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 2.27%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.52%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.52%   |
| NetGear A6210                                                           | 2         | 1.52%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 2         | 1.52%   |
| Intel Wireless 3160                                                     | 2         | 1.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.52%   |
| Intel Centrino Wireless-N 2200                                          | 2         | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.52%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.52%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.52%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.76%   |
| TP-Link 802.11ac NIC                                                    | 1         | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.76%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.76%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.76%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 0.76%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.76%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.76%   |
| Microsoft Xbox360 Wireless N Networking Adapter [Atheros AR7010+AR9280] | 1         | 0.76%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 0.76%   |
| Mercucys 802.11n NIC                                                    | 1         | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.76%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 0.76%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.76%   |
| Intel Wireless 8260                                                     | 1         | 0.76%   |
| Intel Wireless 7265                                                     | 1         | 0.76%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 0.76%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.76%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 54        | 54%     |
| Intel                 | 22        | 22%     |
| Samsung Electronics   | 5         | 5%      |
| Qualcomm Atheros      | 5         | 5%      |
| Nvidia                | 3         | 3%      |
| Broadcom              | 3         | 3%      |
| MediaTek              | 2         | 2%      |
| Apple                 | 2         | 2%      |
| vivo                  | 1         | 1%      |
| ICS Advent            | 1         | 1%      |
| Huawei Technologies   | 1         | 1%      |
| ASIX Electronics      | 1         | 1%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 34.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 10.78%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 3.92%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 2.94%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.94%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.96%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.96%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.96%   |
| vivo 1806                                                         | 1         | 0.98%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.98%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.98%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.98%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.98%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.98%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.98%   |
| MediaTek RMX3085                                                  | 1         | 0.98%   |
| MediaTek moto e(6) plus                                           | 1         | 0.98%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.98%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.98%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.98%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.98%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.98%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.98%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 0.98%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.98%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.98%   |
| ICS Advent 10/100M LAN                                            | 1         | 0.98%   |
| Huawei Ideos (tethering mode)                                     | 1         | 0.98%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.98%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.98%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.98%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 0.98%   |
| Apple iPad 4/Mini1                                                | 1         | 0.98%   |
| Apple iBridge                                                     | 1         | 0.98%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 106       | 53.54%  |
| Ethernet | 90        | 45.45%  |
| Modem    | 1         | 0.51%   |
| Unknown  | 1         | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 80        | 70.18%  |
| Ethernet | 34        | 29.82%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 63        | 56.25%  |
| 1     | 47        | 41.96%  |
| 3     | 1         | 0.89%   |
| 0     | 1         | 0.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 81        | 71.68%  |
| Yes  | 32        | 28.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 49.37%  |
| Qualcomm Atheros Communications | 8         | 10.13%  |
| Realtek Semiconductor           | 7         | 8.86%   |
| Toshiba                         | 3         | 3.8%    |
| MediaTek                        | 3         | 3.8%    |
| IMC Networks                    | 3         | 3.8%    |
| Apple                           | 3         | 3.8%    |
| Marvell Semiconductor           | 2         | 2.53%   |
| Lite-On Technology              | 2         | 2.53%   |
| Foxconn / Hon Hai               | 2         | 2.53%   |
| Cambridge Silicon Radio         | 2         | 2.53%   |
| Broadcom                        | 2         | 2.53%   |
| Realtek                         | 1         | 1.27%   |
| Ralink                          | 1         | 1.27%   |
| Dell                            | 1         | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 14        | 17.72%  |
| Intel AX201 Bluetooth                                                               | 10        | 12.66%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 7.59%   |
| Realtek Bluetooth Radio                                                             | 5         | 6.33%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 6.33%   |
| MediaTek Wireless_Device                                                            | 3         | 3.8%    |
| Intel Bluetooth Device                                                              | 3         | 3.8%    |
| Intel AX200 Bluetooth                                                               | 3         | 3.8%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.53%   |
| Intel AX210 Bluetooth                                                               | 2         | 2.53%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 2.53%   |
| Apple Bluetooth Host Controller                                                     | 2         | 2.53%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 1.27%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.27%   |
| Toshiba Atheros AR3012 Bluetooth                                                    | 1         | 1.27%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.27%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.27%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.27%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.27%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 1.27%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 1.27%   |
| Lite-On Wireless_Device                                                             | 1         | 1.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.27%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.27%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.27%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.27%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 1.27%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.27%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 1.27%   |
| Broadcom BCM20702A0                                                                 | 1         | 1.27%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 83        | 60.58%  |
| AMD                    | 28        | 20.44%  |
| Nvidia                 | 22        | 16.06%  |
| SteelSeries ApS        | 1         | 0.73%   |
| Generalplus Technology | 1         | 0.73%   |
| C-Media Electronics    | 1         | 0.73%   |
| Apple                  | 1         | 0.73%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 8.38%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 6.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 5.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 5.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 4.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 4.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 4.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 4.19%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.8%    |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.2%    |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 1.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.2%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 1.2%    |
| Nvidia Audio device                                                                               | 2         | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.2%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.2%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.2%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.2%    |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.2%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.2%    |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.2%    |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.2%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.2%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 1.2%    |
| AMD High Definition Audio Controller                                                              | 2         | 1.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.2%    |
| SteelSeries ApS SteelSeries GameDAC                                                               | 1         | 0.6%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.6%    |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.6%    |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.6%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.6%    |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Intel USB PnP Sound Device                                                                        | 1         | 0.6%    |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.6%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.6%    |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.6%    |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.6%    |
| C-Media Electronics Audio Adapter                                                                 | 1         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 28.05%  |
| Micron Technology   | 12        | 14.63%  |
| SK hynix            | 11        | 13.41%  |
| Kingston            | 7         | 8.54%   |
| Crucial             | 7         | 8.54%   |
| Unknown             | 5         | 6.1%    |
| Unknown (ABCD)      | 3         | 3.66%   |
| Ramaxel Technology  | 3         | 3.66%   |
| Elpida              | 3         | 3.66%   |
| Unifosa             | 1         | 1.22%   |
| Teikon              | 1         | 1.22%   |
| Smart               | 1         | 1.22%   |
| Silicon Power       | 1         | 1.22%   |
| Saikano             | 1         | 1.22%   |
| G.Skill             | 1         | 1.22%   |
| Corsair             | 1         | 1.22%   |
| A-DATA Technology   | 1         | 1.22%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 3         | 3.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.35%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 2.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 2.35%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.35%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s   | 2         | 2.35%   |
| Samsung RAM K4AAG165WA-BCWE 8GB SODIMM DDR4 3200MT/s             | 2         | 2.35%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 2.35%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 1.18%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 1.18%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                        | 1         | 1.18%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 1.18%   |
| Unknown RAM Module 2GB DIMM                                      | 1         | 1.18%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 1.18%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 1.18%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.18%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                           | 1         | 1.18%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 1.18%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 1.18%   |
| Silicon Power RAM SP016GBLFU266B02 16GB DIMM DDR4 2667MT/s       | 1         | 1.18%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.18%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 1.18%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471A5644EB0-CRC 2GB SODIMM DDR4 2400MT/s            | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.18%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s        | 1         | 1.18%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s             | 1         | 1.18%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s              | 1         | 1.18%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s              | 1         | 1.18%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 1         | 1.18%   |
| Samsung RAM M378B2873CZ0-CF7 1GB SODIMM DDR3 800MT/s             | 1         | 1.18%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.18%   |
| Saikano RAM Memory 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.18%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.18%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s               | 1         | 1.18%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s         | 1         | 1.18%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s             | 1         | 1.18%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.18%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.18%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 1.18%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s              | 1         | 1.18%   |
| Kingston RAM KF3200C20S4/16GX 16GB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s             | 1         | 1.18%   |
| Kingston RAM HP594908-HR1-ELD 2GB SODIMM DDR3 1333MT/s           | 1         | 1.18%   |
| Kingston RAM HP24D4S7S8MB-4 4GB SODIMM DDR4 2400MT/s             | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 32        | 47.06%  |
| DDR3    | 23        | 33.82%  |
| LPDDR4  | 6         | 8.82%   |
| SDRAM   | 3         | 4.41%   |
| LPDDR3  | 2         | 2.94%   |
| DDR5    | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 68.66%  |
| DIMM         | 14        | 20.9%   |
| Row Of Chips | 7         | 10.45%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 32        | 42.11%  |
| 8192  | 19        | 25%     |
| 16384 | 11        | 14.47%  |
| 2048  | 10        | 13.16%  |
| 1024  | 3         | 3.95%   |
| 32768 | 1         | 1.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 16        | 21.33%  |
| 1600    | 16        | 21.33%  |
| 3200    | 13        | 17.33%  |
| 2400    | 8         | 10.67%  |
| 1333    | 4         | 5.33%   |
| 1334    | 3         | 4%      |
| 3600    | 2         | 2.67%   |
| 1867    | 2         | 2.67%   |
| 1067    | 2         | 2.67%   |
| Unknown | 2         | 2.67%   |
| 4800    | 1         | 1.33%   |
| 4267    | 1         | 1.33%   |
| 3266    | 1         | 1.33%   |
| 2200    | 1         | 1.33%   |
| 2133    | 1         | 1.33%   |
| 2048    | 1         | 1.33%   |
| 800     | 1         | 1.33%   |

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
| Chicony Electronics                    | 18        | 21.69%  |
| IMC Networks                           | 10        | 12.05%  |
| Acer                                   | 9         | 10.84%  |
| Microdia                               | 7         | 8.43%   |
| Realtek Semiconductor                  | 6         | 7.23%   |
| Apple                                  | 6         | 7.23%   |
| Quanta                                 | 5         | 6.02%   |
| Sunplus Innovation Technology          | 3         | 3.61%   |
| Syntek                                 | 2         | 2.41%   |
| Logitech                               | 2         | 2.41%   |
| Teslong Camera                         | 1         | 1.2%    |
| Suyin                                  | 1         | 1.2%    |
| Silicon Motion                         | 1         | 1.2%    |
| Ricoh                                  | 1         | 1.2%    |
| Primax Electronics                     | 1         | 1.2%    |
| Microsoft                              | 1         | 1.2%    |
| Luxvisions Innotech Limited            | 1         | 1.2%    |
| Lite-On Technology                     | 1         | 1.2%    |
| Jieli Technology                       | 1         | 1.2%    |
| Importek                               | 1         | 1.2%    |
| icSpring                               | 1         | 1.2%    |
| Goertek Electronics                    | 1         | 1.2%    |
| Creative Technology                    | 1         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.2%    |
| Alcor Micro                            | 1         | 1.2%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                         | 3         | 3.57%   |
| IMC Networks Integrated Camera                       | 3         | 3.57%   |
| Chicony HP Truevision HD                             | 3         | 3.57%   |
| Acer HD Webcam                                       | 3         | 3.57%   |
| Quanta HP TrueVision HD Camera                       | 2         | 2.38%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 2         | 2.38%   |
| Chicony USB2.0 Camera                                | 2         | 2.38%   |
| Chicony TOSHIBA Web Camera - HD                      | 2         | 2.38%   |
| Chicony Integrated Camera [ThinkPad]                 | 2         | 2.38%   |
| Chicony Integrated Camera                            | 2         | 2.38%   |
| Chicony HD User Facing                               | 2         | 2.38%   |
| Apple iPhone 5/5C/5S/6/SE                            | 2         | 2.38%   |
| Apple Built-in iSight                                | 2         | 2.38%   |
| Acer SunplusIT Integrated Camera                     | 2         | 2.38%   |
| Teslong Camera                                       | 1         | 1.19%   |
| Syntek Lenovo EasyCamera                             | 1         | 1.19%   |
| Syntek Integrated Camera                             | 1         | 1.19%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 1.19%   |
| Silicon Motion WebCam SC-13HDL11939N                 | 1         | 1.19%   |
| Ricoh HD Webcam                                      | 1         | 1.19%   |
| Realtek USB Camera                                   | 1         | 1.19%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.19%   |
| Realtek Integrated Webcam                            | 1         | 1.19%   |
| Realtek Integrated Camera                            | 1         | 1.19%   |
| Realtek HP Wide Vision HD Camera                     | 1         | 1.19%   |
| Realtek HP Webcam                                    | 1         | 1.19%   |
| Quanta VGA WebCam                                    | 1         | 1.19%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.19%   |
| Quanta HD User Facing                                | 1         | 1.19%   |
| Primax HP HD Webcam [Fixed]                          | 1         | 1.19%   |
| Microsoft LifeCam Rear                               | 1         | 1.19%   |
| Microsoft LifeCam Front                              | 1         | 1.19%   |
| Microdia PC Microscope camera                        | 1         | 1.19%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 1.19%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.19%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.19%   |
| Microdia Integrated Webcam                           | 1         | 1.19%   |
| Microdia HP Integrated Webcam                        | 1         | 1.19%   |
| Microdia Amcrest AWC2198 USB Webcam                  | 1         | 1.19%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.19%   |
| Logitech HD Webcam C615                              | 1         | 1.19%   |
| Logitech C922 Pro Stream Webcam                      | 1         | 1.19%   |
| Lite-On HP HD Camera                                 | 1         | 1.19%   |
| Jieli USB PHY 2.0                                    | 1         | 1.19%   |
| Importek TOSHIBA Web Camera - HD                     | 1         | 1.19%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 1.19%   |
| IMC Networks USB Camera                              | 1         | 1.19%   |
| IMC Networks ov9734_azurewave_camera                 | 1         | 1.19%   |
| IMC Networks Lenovo EasyCamera                       | 1         | 1.19%   |
| IMC Networks HD Camera                               | 1         | 1.19%   |
| icSpring camera                                      | 1         | 1.19%   |
| Goertek USB2.0 VGA UVC WebCam                        | 1         | 1.19%   |
| Creative Live! Cam Sync HD [VF0770]                  | 1         | 1.19%   |
| Chicony Integrated HP HD Webcam                      | 1         | 1.19%   |
| Chicony Integrated Camera (1280x720@30)              | 1         | 1.19%   |
| Chicony HP HD Camera                                 | 1         | 1.19%   |
| Chicony FJ Camera                                    | 1         | 1.19%   |
| Chicony EasyCamera                                   | 1         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 1         | 1.19%   |
| Apple FaceTime HD Camera (Built-in)                  | 1         | 1.19%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 42.11%  |
| Validity Sensors           | 6         | 31.58%  |
| Shenzhen Goodix Technology | 3         | 15.79%  |
| Elan Microelectronics      | 1         | 5.26%   |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown                                                   | 3         | 15.79%  |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 10.53%  |
| Synaptics  WBDI                                           | 2         | 10.53%  |
| Shenzhen Goodix  Fingerprint Device                       | 2         | 10.53%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 5.26%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 5.26%   |
| Validity Sensors Synaptics WBDI                           | 1         | 5.26%   |
| Validity Sensors Fingerprint scanner                      | 1         | 5.26%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 5.26%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 5.26%   |
| Elan ELAN:ARM-M4                                          | 1         | 5.26%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 1         | 5.26%   |

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
| 0     | 62        | 54.39%  |
| 1     | 44        | 38.6%   |
| 2     | 7         | 6.14%   |
| 3     | 1         | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 33.93%  |
| Net/wireless             | 15        | 26.79%  |
| Graphics card            | 8         | 14.29%  |
| Chipcard                 | 6         | 10.71%  |
| Multimedia controller    | 4         | 7.14%   |
| Storage                  | 1         | 1.79%   |
| Network                  | 1         | 1.79%   |
| Communication controller | 1         | 1.79%   |
| Bluetooth                | 1         | 1.79%   |

