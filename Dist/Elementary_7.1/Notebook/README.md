Elementary 7.1 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Elementary 7.1.

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

Total: 114

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [fdc21a05c2](https://linux-hardware.org/?probe=fdc21a05c2) | Feb 02, 2024 |
| Acer          | AOD255                      | [43304c651c](https://linux-hardware.org/?probe=43304c651c) | Feb 01, 2024 |
| HUAWEI        | BOD-WXX9                    | [d1a7f0cddb](https://linux-hardware.org/?probe=d1a7f0cddb) | Jan 31, 2024 |
| HP            | Pavilion g6                 | [acd0ae9c04](https://linux-hardware.org/?probe=acd0ae9c04) | Jan 31, 2024 |
| Apple         | MacBookPro7,1               | [973c263365](https://linux-hardware.org/?probe=973c263365) | Jan 30, 2024 |
| Fujitsu       | LIFEBOOK E734               | [7b3a60ae2d](https://linux-hardware.org/?probe=7b3a60ae2d) | Jan 30, 2024 |
| Acer          | Aspire E5-571               | [6ebe6ae5be](https://linux-hardware.org/?probe=6ebe6ae5be) | Jan 28, 2024 |
| Lenovo        | ThinkPad L440 20AT0030MD    | [1c0f2e8a2f](https://linux-hardware.org/?probe=1c0f2e8a2f) | Jan 26, 2024 |
| Dell          | Latitude E7240              | [d8e5d4a8da](https://linux-hardware.org/?probe=d8e5d4a8da) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [81338699ce](https://linux-hardware.org/?probe=81338699ce) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [9f021a2102](https://linux-hardware.org/?probe=9f021a2102) | Jan 25, 2024 |
| Samsung       | RC410/RC510/RC710           | [34369cc7eb](https://linux-hardware.org/?probe=34369cc7eb) | Jan 25, 2024 |
| Samsung       | RC410/RC510/RC710           | [d48bdbaec0](https://linux-hardware.org/?probe=d48bdbaec0) | Jan 24, 2024 |
| Acer          | Aspire E5-573G              | [14eec10d5e](https://linux-hardware.org/?probe=14eec10d5e) | Jan 24, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3361cf9ae9](https://linux-hardware.org/?probe=3361cf9ae9) | Jan 23, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED18    | [63d8796a60](https://linux-hardware.org/?probe=63d8796a60) | Jan 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [86d22c9b40](https://linux-hardware.org/?probe=86d22c9b40) | Jan 17, 2024 |
| Apple         | MacBook6,1                  | [641df770ba](https://linux-hardware.org/?probe=641df770ba) | Jan 17, 2024 |
| Apple         | MacBookPro9,2               | [7cf8b59aee](https://linux-hardware.org/?probe=7cf8b59aee) | Jan 10, 2024 |
| Apple         | MacBook5,1                  | [75835b3764](https://linux-hardware.org/?probe=75835b3764) | Jan 09, 2024 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [c3a6a2da37](https://linux-hardware.org/?probe=c3a6a2da37) | Jan 09, 2024 |
| Apple         | MacBook5,1                  | [3a4a960ff8](https://linux-hardware.org/?probe=3a4a960ff8) | Jan 06, 2024 |
| Apple         | MacBookPro7,1               | [75fc0fa74a](https://linux-hardware.org/?probe=75fc0fa74a) | Jan 06, 2024 |
| TECNO Mobi... | MEGABOOK T14TA              | [deadd2cf3d](https://linux-hardware.org/?probe=deadd2cf3d) | Jan 05, 2024 |
| HP            | Laptop 17-by3xxx            | [32486bf070](https://linux-hardware.org/?probe=32486bf070) | Jan 04, 2024 |
| Dell          | Latitude E7440              | [75ba78537c](https://linux-hardware.org/?probe=75ba78537c) | Jan 03, 2024 |
| Positivo      | C4128A-15                   | [52bd86685b](https://linux-hardware.org/?probe=52bd86685b) | Jan 03, 2024 |
| Medion        | E11202                      | [cb45690620](https://linux-hardware.org/?probe=cb45690620) | Jan 01, 2024 |
| HP            | EliteBook 840 G1            | [9ab6343dd7](https://linux-hardware.org/?probe=9ab6343dd7) | Jan 01, 2024 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [0120368c3a](https://linux-hardware.org/?probe=0120368c3a) | Jan 01, 2024 |
| Positivo      | C4128A-15                   | [6416d967b8](https://linux-hardware.org/?probe=6416d967b8) | Dec 30, 2023 |
| Positivo      | C4128A-15                   | [bd9afc6d73](https://linux-hardware.org/?probe=bd9afc6d73) | Dec 30, 2023 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [a55f917cf6](https://linux-hardware.org/?probe=a55f917cf6) | Dec 29, 2023 |
| Medion        | E11202                      | [9db140d63c](https://linux-hardware.org/?probe=9db140d63c) | Dec 28, 2023 |
| HP            | Laptop 15-dw3xxx            | [76305a2c98](https://linux-hardware.org/?probe=76305a2c98) | Dec 28, 2023 |
| Acer          | Swift SFX14-41G             | [d39de69e1b](https://linux-hardware.org/?probe=d39de69e1b) | Dec 27, 2023 |
| THTF          | WUJIE 14                    | [c402523a2c](https://linux-hardware.org/?probe=c402523a2c) | Dec 25, 2023 |
| THTF          | WUJIE 14                    | [39ee354a27](https://linux-hardware.org/?probe=39ee354a27) | Dec 25, 2023 |
| Medion        | E11202                      | [af0c7baf03](https://linux-hardware.org/?probe=af0c7baf03) | Dec 22, 2023 |
| ASUSTek       | X555LAB                     | [8a8a35c616](https://linux-hardware.org/?probe=8a8a35c616) | Dec 21, 2023 |
| Acer          | Aspire 4736Z                | [38866fae79](https://linux-hardware.org/?probe=38866fae79) | Dec 17, 2023 |
| Dell          | Precision 7560              | [0f83098df3](https://linux-hardware.org/?probe=0f83098df3) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [abc0a9283d](https://linux-hardware.org/?probe=abc0a9283d) | Dec 14, 2023 |
| ASUSTek       | X75A1                       | [e7d274ca96](https://linux-hardware.org/?probe=e7d274ca96) | Dec 13, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [4d416a35fa](https://linux-hardware.org/?probe=4d416a35fa) | Dec 12, 2023 |
| Sony          | SVE11115ELW                 | [68fa8c6081](https://linux-hardware.org/?probe=68fa8c6081) | Dec 10, 2023 |
| Sony          | SVE11115ELW                 | [567787c7d3](https://linux-hardware.org/?probe=567787c7d3) | Dec 10, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5a75d4827a](https://linux-hardware.org/?probe=5a75d4827a) | Dec 10, 2023 |
| Lenovo        | ThinkPad P51s 20HBCTO1WW    | [4c18329d9d](https://linux-hardware.org/?probe=4c18329d9d) | Dec 09, 2023 |
| HP            | Laptop 15-dw3xxx            | [8167f60069](https://linux-hardware.org/?probe=8167f60069) | Dec 05, 2023 |
| Dell          | Inspiron 15-3552            | [8ca2d01e7c](https://linux-hardware.org/?probe=8ca2d01e7c) | Dec 05, 2023 |
| Acer          | Aspire 4736Z                | [844b16d408](https://linux-hardware.org/?probe=844b16d408) | Dec 03, 2023 |
| HP            | EliteBook 840 G3            | [fa8d37e46b](https://linux-hardware.org/?probe=fa8d37e46b) | Nov 30, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [a0d4963838](https://linux-hardware.org/?probe=a0d4963838) | Nov 28, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [cf1e883f11](https://linux-hardware.org/?probe=cf1e883f11) | Nov 25, 2023 |
| Samsung       | RF510/RF410/RF710           | [a642075264](https://linux-hardware.org/?probe=a642075264) | Nov 25, 2023 |
| Apple         | MacBookPro5,5               | [a2d556bc01](https://linux-hardware.org/?probe=a2d556bc01) | Nov 20, 2023 |
| Apple         | MacBookPro5,5               | [cdc6379993](https://linux-hardware.org/?probe=cdc6379993) | Nov 19, 2023 |
| Apple         | MacBookPro5,5               | [840adf8528](https://linux-hardware.org/?probe=840adf8528) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | [886c5bc9a6](https://linux-hardware.org/?probe=886c5bc9a6) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | [bcd7007cde](https://linux-hardware.org/?probe=bcd7007cde) | Nov 19, 2023 |
| Fujitsu       | LIFEBOOK E780               | [d3a64f5368](https://linux-hardware.org/?probe=d3a64f5368) | Nov 16, 2023 |
| Unknown       | Unknown                     | [66296a4edd](https://linux-hardware.org/?probe=66296a4edd) | Nov 12, 2023 |
| Alienware     | 15 R3                       | [c920563c0b](https://linux-hardware.org/?probe=c920563c0b) | Nov 12, 2023 |
| HP            | 245 G8                      | [0b471d312a](https://linux-hardware.org/?probe=0b471d312a) | Nov 11, 2023 |
| HP            | 245 G8                      | [b29efc88ec](https://linux-hardware.org/?probe=b29efc88ec) | Nov 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [9b881d355c](https://linux-hardware.org/?probe=9b881d355c) | Nov 09, 2023 |
| Dell          | Vostro 3500                 | [860fc63d0d](https://linux-hardware.org/?probe=860fc63d0d) | Nov 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [5c39f44ed5](https://linux-hardware.org/?probe=5c39f44ed5) | Nov 08, 2023 |
| Dell          | G7 7500                     | [91adca1093](https://linux-hardware.org/?probe=91adca1093) | Nov 07, 2023 |
| Timi          | Redmi G 2022                | [f8cecbac55](https://linux-hardware.org/?probe=f8cecbac55) | Nov 07, 2023 |
| ASUSTek       | X555LAB                     | [2d3d09097d](https://linux-hardware.org/?probe=2d3d09097d) | Nov 06, 2023 |
| Dell          | G7 7500                     | [3678c5437b](https://linux-hardware.org/?probe=3678c5437b) | Nov 06, 2023 |
| Apple         | MacBookPro11,1              | [2d84377719](https://linux-hardware.org/?probe=2d84377719) | Nov 06, 2023 |
| HP            | 245 G8                      | [e9c1cc78b8](https://linux-hardware.org/?probe=e9c1cc78b8) | Nov 06, 2023 |
| HP            | ProBook 6545b               | [a81427fffa](https://linux-hardware.org/?probe=a81427fffa) | Nov 05, 2023 |
| Acer          | Aspire E5-551G              | [f8e737dbde](https://linux-hardware.org/?probe=f8e737dbde) | Nov 03, 2023 |
| HONOR         | NMH-WDX9                    | [11e32e2482](https://linux-hardware.org/?probe=11e32e2482) | Nov 03, 2023 |
| Alienware     | 14                          | [3d3be9ce75](https://linux-hardware.org/?probe=3d3be9ce75) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [e25974d32d](https://linux-hardware.org/?probe=e25974d32d) | Oct 31, 2023 |
| Dell          | Inspiron 1545               | [5a1d90c1a7](https://linux-hardware.org/?probe=5a1d90c1a7) | Oct 30, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [300d56f39e](https://linux-hardware.org/?probe=300d56f39e) | Oct 29, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [29a362f501](https://linux-hardware.org/?probe=29a362f501) | Oct 29, 2023 |
| Apple         | MacBook7,1                  | [61b133ac1e](https://linux-hardware.org/?probe=61b133ac1e) | Oct 27, 2023 |
| Dell          | Latitude E6520              | [dbbca588de](https://linux-hardware.org/?probe=dbbca588de) | Oct 26, 2023 |
| ASUSTek       | X555LAB                     | [a8b1ad0f53](https://linux-hardware.org/?probe=a8b1ad0f53) | Oct 25, 2023 |
| Dell          | Latitude E6400              | [250c9ddcfe](https://linux-hardware.org/?probe=250c9ddcfe) | Oct 24, 2023 |
| Apple         | MacBookPro6,2               | [89f29afb19](https://linux-hardware.org/?probe=89f29afb19) | Oct 24, 2023 |
| Dell          | Latitude E6520              | [c2fd0014ab](https://linux-hardware.org/?probe=c2fd0014ab) | Oct 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3431e88cbe](https://linux-hardware.org/?probe=3431e88cbe) | Oct 22, 2023 |
| Google        | Cave                        | [287887d308](https://linux-hardware.org/?probe=287887d308) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [b11aafb048](https://linux-hardware.org/?probe=b11aafb048) | Oct 20, 2023 |
| HP            | Pavilion 17                 | [855c6109eb](https://linux-hardware.org/?probe=855c6109eb) | Oct 20, 2023 |
| Apple         | MacBookPro6,2               | [036b6067b8](https://linux-hardware.org/?probe=036b6067b8) | Oct 18, 2023 |
| Apple         | MacBookPro5,3               | [1e3660c797](https://linux-hardware.org/?probe=1e3660c797) | Oct 17, 2023 |
| Apple         | MacBookPro5,3               | [3dde86d447](https://linux-hardware.org/?probe=3dde86d447) | Oct 17, 2023 |
| Dell          | Inspiron 1545               | [87edaec977](https://linux-hardware.org/?probe=87edaec977) | Oct 17, 2023 |
| Acer          | Nitro AN517-54              | [2f6c2f44d3](https://linux-hardware.org/?probe=2f6c2f44d3) | Oct 15, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [de2f74b12a](https://linux-hardware.org/?probe=de2f74b12a) | Oct 13, 2023 |
| Lenovo        | B570 1068FRG                | [e912de748b](https://linux-hardware.org/?probe=e912de748b) | Oct 11, 2023 |
| Dell          | Vostro 1510                 | [6324053514](https://linux-hardware.org/?probe=6324053514) | Oct 10, 2023 |
| HP            | EliteBook 2570p             | [c41bac6f71](https://linux-hardware.org/?probe=c41bac6f71) | Oct 09, 2023 |
| HP            | Pavilion 15                 | [0c8f955052](https://linux-hardware.org/?probe=0c8f955052) | Oct 08, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [ccc23328e5](https://linux-hardware.org/?probe=ccc23328e5) | Oct 07, 2023 |
| Dell          | Vostro 1510                 | [39ee83fbf5](https://linux-hardware.org/?probe=39ee83fbf5) | Oct 06, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a49cef1179](https://linux-hardware.org/?probe=a49cef1179) | Oct 04, 2023 |
| Apple         | MacBookPro7,1               | [d88817f79c](https://linux-hardware.org/?probe=d88817f79c) | Oct 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [d91dd7bed6](https://linux-hardware.org/?probe=d91dd7bed6) | Oct 02, 2023 |
| Dell          | Latitude E7270              | [bf1def4fc3](https://linux-hardware.org/?probe=bf1def4fc3) | Oct 01, 2023 |
| Apple         | MacBookAir7,2               | [0a667d66b7](https://linux-hardware.org/?probe=0a667d66b7) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | [15f8d0107f](https://linux-hardware.org/?probe=15f8d0107f) | Sep 26, 2023 |
| Apple         | MacBookPro11,1              | [e9478deeae](https://linux-hardware.org/?probe=e9478deeae) | Sep 23, 2023 |
| HP            | EliteBook 8570p             | [ca346761d3](https://linux-hardware.org/?probe=ca346761d3) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [c8bbae1068](https://linux-hardware.org/?probe=c8bbae1068) | Sep 20, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 6.2.0-33-generic    | 23        | 26.74%  |
| 6.2.0-39-generic    | 11        | 12.79%  |
| 6.2.0-36-generic    | 10        | 11.63%  |
| 6.2.0-37-generic    | 9         | 10.47%  |
| 6.2.0-34-generic    | 9         | 10.47%  |
| 6.5.0-14-generic    | 7         | 8.14%   |
| 6.2.0-35-generic    | 7         | 8.14%   |
| 6.5.0-15-generic    | 6         | 6.98%   |
| 6.2.0-26-generic    | 2         | 2.33%   |
| 6.5.5-x64v3-xanmod1 | 1         | 1.16%   |
| 5.15.0-58-generic   | 1         | 1.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 69        | 82.14%  |
| 6.5.0   | 13        | 15.48%  |
| 6.5.5   | 1         | 1.19%   |
| 5.15.0  | 1         | 1.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 69        | 82.14%  |
| 6.5     | 14        | 16.67%  |
| 5.15    | 1         | 1.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 83        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 83        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 83        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 63        | 75.9%   |
| LightDM | 20        | 24.1%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 31        | 37.35%  |
| ru_RU | 11        | 13.25%  |
| de_DE | 11        | 13.25%  |
| it_IT | 7         | 8.43%   |
| es_ES | 7         | 8.43%   |
| fr_FR | 3         | 3.61%   |
| tr_TR | 2         | 2.41%   |
| pt_BR | 2         | 2.41%   |
| fi_FI | 2         | 2.41%   |
| pl_PL | 1         | 1.2%    |
| fr_CA | 1         | 1.2%    |
| en_GB | 1         | 1.2%    |
| de_CH | 1         | 1.2%    |
| da_DK | 1         | 1.2%    |
| cs_CZ | 1         | 1.2%    |
| ar_EG | 1         | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 71        | 85.54%  |
| EFI  | 12        | 14.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 73        | 87.95%  |
| Tmpfs   | 7         | 8.43%   |
| Btrfs   | 2         | 2.41%   |
| Overlay | 1         | 1.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 63        | 75.9%   |
| GPT     | 15        | 18.07%  |
| MBR     | 5         | 6.02%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 98.8%   |
| Yes       | 1         | 1.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 76        | 91.57%  |
| Yes       | 7         | 8.43%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Apple                | 14        | 16.87%  |
| Hewlett-Packard      | 13        | 15.66%  |
| Lenovo               | 12        | 14.46%  |
| Dell                 | 11        | 13.25%  |
| ASUSTek Computer     | 8         | 9.64%   |
| Acer                 | 7         | 8.43%   |
| Samsung Electronics  | 2         | 2.41%   |
| HUAWEI               | 2         | 2.41%   |
| Fujitsu              | 2         | 2.41%   |
| Alienware            | 2         | 2.41%   |
| UMAX                 | 1         | 1.2%    |
| Timi                 | 1         | 1.2%    |
| THTF                 | 1         | 1.2%    |
| TECNO Mobile Limited | 1         | 1.2%    |
| Sony                 | 1         | 1.2%    |
| Positivo             | 1         | 1.2%    |
| Medion               | 1         | 1.2%    |
| HONOR                | 1         | 1.2%    |
| Google               | 1         | 1.2%    |
| Unknown              | 1         | 1.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Apple MacBookPro7,1                      | 3         | 3.61%   |
| Apple MacBookPro6,2                      | 2         | 2.41%   |
| Apple MacBookPro11,1                     | 2         | 2.41%   |
| UMAX VisionBook 14Wr Plus                | 1         | 1.2%    |
| Timi Redmi G 2022                        | 1         | 1.2%    |
| THTF WUJIE 14                            | 1         | 1.2%    |
| TECNO Mobile Limited MEGABOOK T14TA      | 1         | 1.2%    |
| Sony SVE11115ELW                         | 1         | 1.2%    |
| Samsung RF510/RF410/RF710                | 1         | 1.2%    |
| Samsung RC410/RC510/RC710                | 1         | 1.2%    |
| Positivo C4128A-15                       | 1         | 1.2%    |
| Medion E11202                            | 1         | 1.2%    |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S2G103 | 1         | 1.2%    |
| Lenovo ThinkPad T480 20L6S3ED18          | 1         | 1.2%    |
| Lenovo ThinkPad T470 20JNS08H00          | 1         | 1.2%    |
| Lenovo ThinkPad T440p 20AN0069US         | 1         | 1.2%    |
| Lenovo ThinkPad T14s Gen 2i 20WM01SCUS   | 1         | 1.2%    |
| Lenovo ThinkPad P51s 20HBCTO1WW          | 1         | 1.2%    |
| Lenovo ThinkPad L440 20AT0030MD          | 1         | 1.2%    |
| Lenovo IdeaPad 5 14ITL05 82FE            | 1         | 1.2%    |
| Lenovo IdeaPad 330S-15IKB 81F5           | 1         | 1.2%    |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 1.2%    |
| Lenovo IdeaPad 110-14ISK 80UC            | 1         | 1.2%    |
| Lenovo B570 1068FRG                      | 1         | 1.2%    |
| HUAWEI NBLK-WAX9X                        | 1         | 1.2%    |
| HUAWEI BOD-WXX9                          | 1         | 1.2%    |
| HONOR NMH-WDX9                           | 1         | 1.2%    |
| HP ProBook 6545b                         | 1         | 1.2%    |
| HP Pavilion Sleekbook 15 PC              | 1         | 1.2%    |
| HP Pavilion g6                           | 1         | 1.2%    |
| HP Pavilion 17                           | 1         | 1.2%    |
| HP Pavilion 15                           | 1         | 1.2%    |
| HP OMEN by Laptop                        | 1         | 1.2%    |
| HP Laptop 17-by3xxx                      | 1         | 1.2%    |
| HP EliteBook 8570p                       | 1         | 1.2%    |
| HP EliteBook 845 G7 Notebook PC          | 1         | 1.2%    |
| HP EliteBook 840 G3                      | 1         | 1.2%    |
| HP EliteBook 840 G1                      | 1         | 1.2%    |
| HP EliteBook 2570p                       | 1         | 1.2%    |
| HP 245 G8                                | 1         | 1.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 7         | 8.43%   |
| HP EliteBook                  | 5         | 6.02%   |
| Dell Latitude                 | 5         | 6.02%   |
| Lenovo IdeaPad                | 4         | 4.82%   |
| HP Pavilion                   | 4         | 4.82%   |
| Acer Aspire                   | 4         | 4.82%   |
| ASUS VivoBook                 | 3         | 3.61%   |
| Apple MacBookPro7             | 3         | 3.61%   |
| Fujitsu LIFEBOOK              | 2         | 2.41%   |
| Dell Vostro                   | 2         | 2.41%   |
| Dell Inspiron                 | 2         | 2.41%   |
| ASUS Zenbook                  | 2         | 2.41%   |
| Apple MacBookPro6             | 2         | 2.41%   |
| Apple MacBookPro5             | 2         | 2.41%   |
| Apple MacBookPro11            | 2         | 2.41%   |
| UMAX VisionBook               | 1         | 1.2%    |
| Timi Redmi                    | 1         | 1.2%    |
| THTF WUJIE                    | 1         | 1.2%    |
| TECNO Mobile Limited MEGABOOK | 1         | 1.2%    |
| Sony SVE11115ELW              | 1         | 1.2%    |
| Samsung RF510                 | 1         | 1.2%    |
| Samsung RC410                 | 1         | 1.2%    |
| Positivo C4128A-15            | 1         | 1.2%    |
| Medion E11202                 | 1         | 1.2%    |
| Lenovo B570                   | 1         | 1.2%    |
| HUAWEI NBLK-WAX9X             | 1         | 1.2%    |
| HUAWEI BOD-WXX9               | 1         | 1.2%    |
| HONOR NMH-WDX9                | 1         | 1.2%    |
| HP ProBook                    | 1         | 1.2%    |
| HP OMEN                       | 1         | 1.2%    |
| HP Laptop                     | 1         | 1.2%    |
| HP 245                        | 1         | 1.2%    |
| Google Cave                   | 1         | 1.2%    |
| Dell Precision                | 1         | 1.2%    |
| Dell G7                       | 1         | 1.2%    |
| ASUS X75A1                    | 1         | 1.2%    |
| ASUS X555LAB                  | 1         | 1.2%    |
| ASUS TUF                      | 1         | 1.2%    |
| Apple MacBookPro9             | 1         | 1.2%    |
| Apple MacBookAir7             | 1         | 1.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2010 | 10        | 12.05%  |
| 2021 | 8         | 9.64%   |
| 2014 | 8         | 9.64%   |
| 2013 | 7         | 8.43%   |
| 2023 | 6         | 7.23%   |
| 2020 | 6         | 7.23%   |
| 2012 | 6         | 7.23%   |
| 2009 | 6         | 7.23%   |
| 2022 | 4         | 4.82%   |
| 2016 | 4         | 4.82%   |
| 2011 | 4         | 4.82%   |
| 2018 | 3         | 3.61%   |
| 2017 | 3         | 3.61%   |
| 2008 | 3         | 3.61%   |
| 2019 | 2         | 2.41%   |
| 2015 | 2         | 2.41%   |
| 2007 | 1         | 1.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 83        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 80        | 96.39%  |
| Enabled  | 3         | 3.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 82        | 98.8%   |
| Yes  | 1         | 1.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 31        | 37.35%  |
| 3.01-4.0    | 20        | 24.1%   |
| 16.01-24.0  | 16        | 19.28%  |
| 8.01-16.0   | 8         | 9.64%   |
| 2.01-3.0    | 3         | 3.61%   |
| 32.01-64.0  | 2         | 2.41%   |
| 1.01-2.0    | 2         | 2.41%   |
| 64.01-256.0 | 1         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 31        | 36.05%  |
| 3.01-4.0  | 21        | 24.42%  |
| 1.01-2.0  | 17        | 19.77%  |
| 4.01-8.0  | 11        | 12.79%  |
| 8.01-16.0 | 3         | 3.49%   |
| 0.51-1.0  | 3         | 3.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 68.67%  |
| 2      | 26        | 31.33%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 67.47%  |
| Yes       | 27        | 32.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 77.11%  |
| No        | 19        | 22.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 98.8%   |
| No        | 1         | 1.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 83.13%  |
| No        | 14        | 16.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 11        | 13.25%  |
| Germany     | 9         | 10.84%  |
| Russia      | 8         | 9.64%   |
| Italy       | 7         | 8.43%   |
| Brazil      | 5         | 6.02%   |
| Mexico      | 4         | 4.82%   |
| France      | 4         | 4.82%   |
| Turkey      | 2         | 2.41%   |
| Switzerland | 2         | 2.41%   |
| Netherlands | 2         | 2.41%   |
| Greece      | 2         | 2.41%   |
| Finland     | 2         | 2.41%   |
| Canada      | 2         | 2.41%   |
| Belarus     | 2         | 2.41%   |
| Austria     | 2         | 2.41%   |
| Ukraine     | 1         | 1.2%    |
| Thailand    | 1         | 1.2%    |
| Sweden      | 1         | 1.2%    |
| Spain       | 1         | 1.2%    |
| Slovakia    | 1         | 1.2%    |
| Romania     | 1         | 1.2%    |
| Puerto Rico | 1         | 1.2%    |
| Poland      | 1         | 1.2%    |
| Morocco     | 1         | 1.2%    |
| Kazakhstan  | 1         | 1.2%    |
| India       | 1         | 1.2%    |
| Ecuador     | 1         | 1.2%    |
| Denmark     | 1         | 1.2%    |
| Czechia     | 1         | 1.2%    |
| Colombia    | 1         | 1.2%    |
| Chile       | 1         | 1.2%    |
| Armenia     | 1         | 1.2%    |
| Argentina   | 1         | 1.2%    |
| Algeria     | 1         | 1.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 3         | 3.53%   |
| Vienna            | 2         | 2.35%   |
| Zhodzina          | 1         | 1.18%   |
| Zamora            | 1         | 1.18%   |
| Yuzhno-Sakhalinsk | 1         | 1.18%   |
| Yerevan           | 1         | 1.18%   |
| Yekaterinburg     | 1         | 1.18%   |
| Vitebsk           | 1         | 1.18%   |
| Valby             | 1         | 1.18%   |
| Turku             | 1         | 1.18%   |
| Staten Island     | 1         | 1.18%   |
| Sohlde            | 1         | 1.18%   |
| Sochi             | 1         | 1.18%   |
| Savannah          | 1         | 1.18%   |
| Sainte-Therese    | 1         | 1.18%   |
| Saint-Lambert     | 1         | 1.18%   |
| Rostock           | 1         | 1.18%   |
| Rio Grande        | 1         | 1.18%   |
| Puebla City       | 1         | 1.18%   |
| Prague            | 1         | 1.18%   |
| Phoenix           | 1         | 1.18%   |
| Pátrai           | 1         | 1.18%   |
| Parma             | 1         | 1.18%   |
| Paris             | 1         | 1.18%   |
| Nowy Sącz        | 1         | 1.18%   |
| Nîmes            | 1         | 1.18%   |
| Naples            | 1         | 1.18%   |
| Murcia            | 1         | 1.18%   |
| Munich            | 1         | 1.18%   |
| Mundelein         | 1         | 1.18%   |
| Mumbai            | 1         | 1.18%   |
| Monza             | 1         | 1.18%   |
| Minneapolis       | 1         | 1.18%   |
| Milton            | 1         | 1.18%   |
| Milano            | 1         | 1.18%   |
| Milan             | 1         | 1.18%   |
| Meknes            | 1         | 1.18%   |
| Lviv              | 1         | 1.18%   |
| Loja              | 1         | 1.18%   |
| Linhares          | 1         | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 15        | 17     | 14.42%  |
| WDC                          | 9         | 11     | 8.65%   |
| Toshiba                      | 7         | 9      | 6.73%   |
| Sandisk                      | 6         | 8      | 5.77%   |
| Unknown                      | 5         | 8      | 4.81%   |
| Seagate                      | 5         | 5      | 4.81%   |
| Kingston                     | 5         | 7      | 4.81%   |
| Intel                        | 5         | 5      | 4.81%   |
| Hitachi                      | 5         | 5      | 4.81%   |
| Apple                        | 5         | 5      | 4.81%   |
| Crucial                      | 4         | 4      | 3.85%   |
| SK hynix                     | 3         | 3      | 2.88%   |
| KIOXIA                       | 3         | 3      | 2.88%   |
| HGST                         | 3         | 3      | 2.88%   |
| Transcend                    | 2         | 3      | 1.92%   |
| Fanxiang                     | 2         | 2      | 1.92%   |
| China                        | 2         | 2      | 1.92%   |
| A-DATA Technology            | 2         | 2      | 1.92%   |
| XrayDisk                     | 1         | 2      | 0.96%   |
| TS-RDF2                      | 1         | 1      | 0.96%   |
| SPCC                         | 1         | 1      | 0.96%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.96%   |
| PNY                          | 1         | 1      | 0.96%   |
| Phison Electronics           | 1         | 1      | 0.96%   |
| NGFF                         | 1         | 1      | 0.96%   |
| Micron Technology            | 1         | 1      | 0.96%   |
| MAXIO Technology (Hangzhou)  | 1         | 1      | 0.96%   |
| LS                           | 1         | 1      | 0.96%   |
| LITEON                       | 1         | 1      | 0.96%   |
| Lite-On Technology           | 1         | 1      | 0.96%   |
| Kingston Technology Company  | 1         | 1      | 0.96%   |
| Hewlett-Packard              | 1         | 1      | 0.96%   |
| Gigabyte Technology          | 1         | 1      | 0.96%   |
| Unknown                      | 1         | 2      | 0.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                            | 3         | 2.8%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 2         | 1.87%   |
| Seagate ST500LT012-1DG142 500GB                   | 2         | 1.87%   |
| Samsung SSD 860 EVO 500GB                         | 2         | 1.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 1.87%   |
| Samsung MZVL4512HBLU-00BTW 512GB                  | 2         | 1.87%   |
| Kingston SUV500MS480G 480GB SSD                   | 2         | 1.87%   |
| HGST HTS721010A9E630 1TB                          | 2         | 1.87%   |
| XrayDisk 256GB SSD                                | 1         | 0.93%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 1         | 0.93%   |
| WDC WD6400BPVT-22HXZT3 640GB                      | 1         | 0.93%   |
| WDC WD5000LPVX-00V0TT0 500GB                      | 1         | 0.93%   |
| WDC WD5000BPVT-24HXZT3 500GB                      | 1         | 0.93%   |
| WDC WD2500BEKT-60PVMT0 250GB                      | 1         | 0.93%   |
| WDC WD1600BEKT-08PVMT1 160GB                      | 1         | 0.93%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 1         | 0.93%   |
| Unknown NVMe SSD Drive 512GB                      | 1         | 0.93%   |
| Unknown MMC Card  512GB                           | 1         | 0.93%   |
| Unknown MMC Card  128GB                           | 1         | 0.93%   |
| TS-RDF2 Transcend 128GB                           | 1         | 0.93%   |
| Transcend TS64GMTS400S 64GB SSD                   | 1         | 0.93%   |
| Transcend TS256GMTS430S 256GB SSD                 | 1         | 0.93%   |
| Toshiba MQ04ABF100 1TB                            | 1         | 0.93%   |
| Toshiba MQ01ABF032 320GB                          | 1         | 0.93%   |
| Toshiba MQ01ABD100 1TB                            | 1         | 0.93%   |
| Toshiba MK3275GSX 320GB                           | 1         | 0.93%   |
| Toshiba MK1655GSXF 160GB                          | 1         | 0.93%   |
| Toshiba MK1646GSX 160GB                           | 1         | 0.93%   |
| Toshiba KXG60ZNV512G 512GB                        | 1         | 0.93%   |
| SPCC Solid State Disk 512GB                       | 1         | 0.93%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB            | 1         | 0.93%   |
| SK hynix PC611 NVMe 1TB                           | 1         | 0.93%   |
| SK hynix BC501 NVMe Solid State Drive 512GB       | 1         | 0.93%   |
| Shenzhen Longsys FORESEE XP1000F512G 512GB        | 1         | 0.93%   |
| Seagate ST9250315AS 250GB                         | 1         | 0.93%   |
| Seagate ST1000LX015-1U7172 1TB                    | 1         | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB                    | 1         | 0.93%   |
| SanDisk X400 M.2 2280 128GB SSD                   | 1         | 0.93%   |
| Sandisk WD_BLACK SN770 2TB                        | 1         | 0.93%   |
| Sandisk WD_BLACK SN770 1TB                        | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 22.22%  |
| Toshiba             | 6         | 8      | 22.22%  |
| Seagate             | 5         | 5      | 18.52%  |
| Hitachi             | 5         | 5      | 18.52%  |
| HGST                | 3         | 3      | 11.11%  |
| Samsung Electronics | 1         | 1      | 3.7%    |
| Apple               | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 18.6%   |
| Kingston            | 5         | 7      | 11.63%  |
| SanDisk             | 4         | 5      | 9.3%    |
| Crucial             | 4         | 4      | 9.3%    |
| Apple               | 4         | 4      | 9.3%    |
| WDC                 | 3         | 5      | 6.98%   |
| Intel               | 3         | 3      | 6.98%   |
| Transcend           | 2         | 3      | 4.65%   |
| China               | 2         | 2      | 4.65%   |
| XrayDisk            | 1         | 2      | 2.33%   |
| SPCC                | 1         | 1      | 2.33%   |
| PNY                 | 1         | 1      | 2.33%   |
| NGFF                | 1         | 1      | 2.33%   |
| LS                  | 1         | 1      | 2.33%   |
| LITEON              | 1         | 1      | 2.33%   |
| Hewlett-Packard     | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 41        | 51     | 41.41%  |
| HDD     | 27        | 29     | 27.27%  |
| NVMe    | 24        | 28     | 24.24%  |
| MMC     | 4         | 9      | 4.04%   |
| Unknown | 3         | 3      | 3.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 61        | 82     | 67.78%  |
| NVMe | 24        | 28     | 26.67%  |
| MMC  | 4         | 9      | 4.44%   |
| SAS  | 1         | 1      | 1.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 64     | 79.1%   |
| 0.51-1.0   | 14        | 16     | 20.9%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 35        | 41.67%  |
| 251-500        | 21        | 25%     |
| 501-1000       | 12        | 14.29%  |
| 51-100         | 8         | 9.52%   |
| 1001-2000      | 4         | 4.76%   |
| 21-50          | 2         | 2.38%   |
| More than 3000 | 1         | 1.19%   |
| 1-20           | 1         | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 38        | 45.24%  |
| 21-50     | 30        | 35.71%  |
| 251-500   | 6         | 7.14%   |
| 51-100    | 5         | 5.95%   |
| 101-250   | 4         | 4.76%   |
| 2001-3000 | 1         | 1.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| LS 128GB M300 SSD           | 1         | 1      | 50%     |
| Crucial CT240M500SSD3 240GB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| LS      | 1         | 1      | 50%     |
| Crucial | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 100%    |

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
| Detected | 70        | 103    | 83.33%  |
| Works    | 12        | 15     | 14.29%  |
| Malfunc  | 2         | 2      | 2.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 54        | 56.25%  |
| Samsung Electronics          | 9         | 9.38%   |
| Nvidia                       | 8         | 8.33%   |
| AMD                          | 8         | 8.33%   |
| SK hynix                     | 3         | 3.13%   |
| KIOXIA                       | 3         | 3.13%   |
| SanDisk                      | 2         | 2.08%   |
| Phison Electronics           | 2         | 2.08%   |
| Toshiba America Info Systems | 1         | 1.04%   |
| Shenzhen Longsys Electronics | 1         | 1.04%   |
| Micron Technology            | 1         | 1.04%   |
| MAXIO Technology (Hangzhou)  | 1         | 1.04%   |
| Lite-On Technology           | 1         | 1.04%   |
| Kingston Technology Company  | 1         | 1.04%   |
| ADATA Technology             | 1         | 1.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                                                | 7         | 7%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 6         | 6%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 5         | 5%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 5         | 5%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 5         | 5%      |
| Nvidia MCP89 SATA Controller (AHCI mode)                                                                           | 4         | 4%      |
| Nvidia MCP79 AHCI Controller                                                                                       | 4         | 4%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 4         | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 3         | 3%      |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                                                                 | 2         | 2%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 2         | 2%      |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                                                      | 2         | 2%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 2         | 2%      |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 2         | 2%      |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 2         | 2%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 2         | 2%      |
| Intel Tiger Lake-LP SATA Controller                                                                                | 2         | 2%      |
| Intel SSD 670p Series [Keystone Harbor]                                                                            | 2         | 2%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                                                             | 2         | 2%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 2         | 2%      |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                                               | 1         | 1%      |
| SK hynix PC611 NVMe Solid State Drive                                                                              | 1         | 1%      |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                                               | 1         | 1%      |
| SK hynix BC501 NVMe Solid State Drive                                                                              | 1         | 1%      |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 1%      |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                                            | 1         | 1%      |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                                                          | 1         | 1%      |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                                                         | 1         | 1%      |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                                                        | 1         | 1%      |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                                           | 1         | 1%      |
| Lite-On CX2-8B256, CX2-8B512 NVMe SSD                                                                              | 1         | 1%      |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                                                         | 1         | 1%      |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                                                                 | 1         | 1%      |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                                              | 1         | 1%      |
| Intel Volume Management Device NVMe RAID Controller                                                                | 1         | 1%      |
| Intel Tiger Lake SATA AHCI Controller                                                                              | 1         | 1%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]                                      | 1         | 1%      |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                                                 | 1         | 1%      |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                                                      | 1         | 1%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                                              | 1         | 1%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 62        | 63.92%  |
| NVMe | 24        | 24.74%  |
| RAID | 7         | 7.22%   |
| IDE  | 4         | 4.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 83.13%  |
| AMD    | 14        | 16.87%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 4.82%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 3.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 2.41%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 2.41%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 2.41%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 2.41%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 2.41%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 2         | 2.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 2.41%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 2.41%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.41%   |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 1.2%    |
| Intel Pentium CPU B980 @ 2.40GHz              | 1         | 1.2%    |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 1.2%    |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 1.2%    |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 1.2%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.2%    |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.2%    |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 1.2%    |
| Intel Core i7-4712MQ CPU @ 2.30GHz            | 1         | 1.2%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.2%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.2%    |
| Intel Core i5-5350U CPU @ 1.80GHz             | 1         | 1.2%    |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 1.2%    |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 1.2%    |
| Intel Core i5-4308U CPU @ 2.80GHz             | 1         | 1.2%    |
| Intel Core i5-4278U CPU @ 2.60GHz             | 1         | 1.2%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.2%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.2%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.2%    |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 1         | 1.2%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.2%    |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.2%    |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 1         | 1.2%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.2%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.2%    |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 1.2%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 24        | 28.92%  |
| Intel Core 2 Duo        | 11        | 13.25%  |
| Intel Core i7           | 10        | 12.05%  |
| Other                   | 8         | 9.64%   |
| AMD Ryzen 5             | 6         | 7.23%   |
| Intel Core i3           | 5         | 6.02%   |
| Intel Celeron           | 4         | 4.82%   |
| Intel Pentium           | 3         | 3.61%   |
| AMD Ryzen 7             | 2         | 2.41%   |
| Intel Xeon              | 1         | 1.2%    |
| Intel Core m3           | 1         | 1.2%    |
| Intel Celeron Dual-Core | 1         | 1.2%    |
| Intel Atom              | 1         | 1.2%    |
| AMD Turion II Dual-Core | 1         | 1.2%    |
| AMD Ryzen 5 PRO         | 1         | 1.2%    |
| AMD FX                  | 1         | 1.2%    |
| AMD E2                  | 1         | 1.2%    |
| AMD A6                  | 1         | 1.2%    |
| AMD A4                  | 1         | 1.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 53        | 63.86%  |
| 4      | 17        | 20.48%  |
| 6      | 8         | 9.64%   |
| 8      | 3         | 3.61%   |
| 12     | 1         | 1.2%    |
| 1      | 1         | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 83        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 60        | 72.29%  |
| 1      | 23        | 27.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 83        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 95.18%  |
| 0x0a404102 | 1         | 1.2%    |
| 0x08608104 | 1         | 1.2%    |
| 0x08108109 | 1         | 1.2%    |
| 0x05000119 | 1         | 1.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Haswell          | 13        | 15.66%  |
| Penryn           | 12        | 14.46%  |
| KabyLake         | 6         | 7.23%   |
| Westmere         | 5         | 6.02%   |
| TigerLake        | 5         | 6.02%   |
| Skylake          | 5         | 6.02%   |
| SandyBridge      | 5         | 6.02%   |
| Unknown          | 5         | 6.02%   |
| Zen 3            | 3         | 3.61%   |
| IvyBridge        | 3         | 3.61%   |
| Icelake          | 3         | 3.61%   |
| Broadwell        | 3         | 3.61%   |
| Zen+             | 2         | 2.41%   |
| Goldmont plus    | 2         | 2.41%   |
| Zen 2            | 1         | 1.2%    |
| Steamroller      | 1         | 1.2%    |
| Silvermont       | 1         | 1.2%    |
| K10              | 1         | 1.2%    |
| Jaguar           | 1         | 1.2%    |
| Goldmont         | 1         | 1.2%    |
| Excavator        | 1         | 1.2%    |
| CometLake        | 1         | 1.2%    |
| Bonnell          | 1         | 1.2%    |
| Bobcat           | 1         | 1.2%    |
| Alderlake Hybrid | 1         | 1.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 57.43%  |
| Nvidia | 27        | 26.73%  |
| AMD    | 16        | 15.84%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 9         | 8.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 4.81%   |
| Nvidia MCP89 [GeForce 320M]                                               | 4         | 3.85%   |
| Nvidia C79 [GeForce 9400M]                                                | 4         | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 3.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 3.85%   |
| Intel Core Processor Integrated Graphics Controller                       | 4         | 3.85%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 3         | 2.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 2.88%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 2.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.92%   |
| Intel UHD Graphics 620                                                    | 2         | 1.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 1.92%   |
| Intel HD Graphics 630                                                     | 2         | 1.92%   |
| Intel HD Graphics 6000                                                    | 2         | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.92%   |
| AMD Lucienne                                                              | 2         | 1.92%   |
| AMD Barcelo                                                               | 2         | 1.92%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.96%   |
| Nvidia GT218M [GeForce 315M]                                              | 1         | 0.96%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.96%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                              | 1         | 0.96%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 0.96%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.96%   |
| Nvidia GM108GLM [Quadro M520 Mobile]                                      | 1         | 0.96%   |
| Nvidia GK106M [GeForce GTX 765M]                                          | 1         | 0.96%   |
| Nvidia GF119M [NVS 4200M]                                                 | 1         | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 0.96%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.96%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.96%   |
| Nvidia G98M [Quadro NVS 160M]                                             | 1         | 0.96%   |
| Nvidia G96CM [GeForce 9600M GT]                                           | 1         | 0.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 0.96%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 1         | 0.96%   |
| Intel Tiger Lake-H GT1 [UHD Graphics]                                     | 1         | 0.96%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 1         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 42        | 50.6%   |
| Intel + Nvidia | 13        | 15.66%  |
| 1 x Nvidia     | 11        | 13.25%  |
| 1 x AMD        | 11        | 13.25%  |
| Intel + AMD    | 2         | 2.41%   |
| AMD + Nvidia   | 2         | 2.41%   |
| 2 x Nvidia     | 1         | 1.2%    |
| 2 x AMD        | 1         | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 74        | 89.16%  |
| Proprietary | 6         | 7.23%   |
| Unknown     | 3         | 3.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 92.77%  |
| 0.01-0.5   | 5         | 6.02%   |
| 0.51-1.0   | 1         | 1.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 21        | 23.86%  |
| Apple                   | 13        | 14.77%  |
| Samsung Electronics     | 12        | 13.64%  |
| LG Display              | 10        | 11.36%  |
| Chimei Innolux          | 9         | 10.23%  |
| BOE                     | 9         | 10.23%  |
| Mi                      | 2         | 2.27%   |
| HKC                     | 2         | 2.27%   |
| TMX                     | 1         | 1.14%   |
| PANDA                   | 1         | 1.14%   |
| KDB                     | 1         | 1.14%   |
| Hewlett-Packard         | 1         | 1.14%   |
| Goldstar                | 1         | 1.14%   |
| Fujitsu Siemens         | 1         | 1.14%   |
| Dell                    | 1         | 1.14%   |
| CTO                     | 1         | 1.14%   |
| Chi Mei Optoelectronics | 1         | 1.14%   |
| Acer                    | 1         | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 2.27%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 2.27%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch          | 2         | 2.27%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 2         | 2.27%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 2         | 2.27%   |
| TMX TL160ADMP11-0 TMX1601 2560x1600 345x215mm 16.0-inch               | 1         | 1.14%   |
| Samsung Electronics SyncMaster SAM0247 1280x1024 376x301mm 19.0-inch  | 1         | 1.14%   |
| Samsung Electronics LS27A600U SAM7172 2560x1440 600x340mm 27.2-inch   | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch  | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch  | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC3659 1600x900 344x194mm 15.5-inch  | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch  | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch  | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 1.14%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 1.14%   |
| Mi Monitor XMI3447 3440x1440 797x334mm 34.0-inch                      | 1         | 1.14%   |
| Mi 27 NFGL XMIB004 1920x1080 598x336mm 27.0-inch                      | 1         | 1.14%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD03DC 1366x768 277x156mm 12.5-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD02D1 1600x900 382x215mm 17.3-inch           | 1         | 1.14%   |
| KDB LCD Monitor KDB1130 1366x768 256x144mm 11.6-inch                  | 1         | 1.14%   |
| HKC LCD Monitor HKC3CFB 1920x1080 344x194mm 15.5-inch                 | 1         | 1.14%   |
| HKC LCD Monitor HKC0200 1920x1200 302x188mm 14.0-inch                 | 1         | 1.14%   |
| Hewlett-Packard 23cw HWP3188 1920x1080 509x286mm 23.0-inch            | 1         | 1.14%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.14%   |
| Fujitsu Siemens E19-5 FUS07CD 1280x1024 376x301mm 19.0-inch           | 1         | 1.14%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                     | 1         | 1.14%   |
| CTO LCD Monitor CTO1115 3840x2160 344x194mm 15.5-inch                 | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch      | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch      | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch      | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1541 1366x768 344x193mm 15.5-inch       | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN142C 1366x768 309x173mm 13.9-inch       | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 1         | 1.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 26        | 30.23%  |
| 1366x768 (WXGA)    | 26        | 30.23%  |
| 1280x800 (WXGA)    | 8         | 9.3%    |
| 1600x900 (HD+)     | 4         | 4.65%   |
| 1440x900 (WXGA+)   | 4         | 4.65%   |
| 2560x1600          | 3         | 3.49%   |
| 3840x2160 (4K)     | 2         | 2.33%   |
| 2880x1800          | 2         | 2.33%   |
| 2560x1440 (QHD)    | 2         | 2.33%   |
| 1920x1200 (WUXGA)  | 2         | 2.33%   |
| 1680x1050 (WSXGA+) | 2         | 2.33%   |
| 1280x1024 (SXGA)   | 2         | 2.33%   |
| 3440x1440          | 1         | 1.16%   |
| 2560x1080          | 1         | 1.16%   |
| 1024x600           | 1         | 1.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 31        | 35.23%  |
| 13     | 20        | 22.73%  |
| 14     | 13        | 14.77%  |
| 17     | 5         | 5.68%   |
| 12     | 5         | 5.68%   |
| 34     | 2         | 2.27%   |
| 27     | 2         | 2.27%   |
| 23     | 2         | 2.27%   |
| 19     | 2         | 2.27%   |
| 16     | 2         | 2.27%   |
| 11     | 2         | 2.27%   |
| 22     | 1         | 1.14%   |
| 10     | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 61.36%  |
| 201-300     | 18        | 20.45%  |
| 351-400     | 9         | 10.23%  |
| 501-600     | 4         | 4.55%   |
| 701-800     | 2         | 2.27%   |
| 401-500     | 1         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 60        | 70.59%  |
| 16/10 | 21        | 24.71%  |
| 5/4   | 2         | 2.35%   |
| 21/9  | 2         | 2.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 31        | 35.23%  |
| 81-90          | 29        | 32.95%  |
| 61-70          | 5         | 5.68%   |
| 121-130        | 4         | 4.55%   |
| 71-80          | 3         | 3.41%   |
| 201-250        | 3         | 3.41%   |
| 51-60          | 2         | 2.27%   |
| 351-500        | 2         | 2.27%   |
| 301-350        | 2         | 2.27%   |
| 151-200        | 2         | 2.27%   |
| 111-120        | 2         | 2.27%   |
| 41-50          | 1         | 1.14%   |
| 131-140        | 1         | 1.14%   |
| 91-100         | 1         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 34        | 39.08%  |
| 101-120       | 31        | 35.63%  |
| 51-100        | 12        | 13.79%  |
| 161-240       | 6         | 6.9%    |
| More than 240 | 4         | 4.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 72        | 85.71%  |
| 2     | 9         | 10.71%  |
| 0     | 3         | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 32        | 25.4%   |
| Realtek Semiconductor             | 28        | 22.22%  |
| Broadcom                          | 20        | 15.87%  |
| Qualcomm Atheros                  | 12        | 9.52%   |
| Nvidia                            | 5         | 3.97%   |
| MediaTek                          | 5         | 3.97%   |
| Samsung Electronics               | 4         | 3.17%   |
| Broadcom Limited                  | 4         | 3.17%   |
| Marvell Technology Group          | 3         | 2.38%   |
| Hewlett-Packard                   | 3         | 2.38%   |
| Qualcomm Atheros Communications   | 2         | 1.59%   |
| Xiaomi                            | 1         | 0.79%   |
| TP-Link                           | 1         | 0.79%   |
| Sierra Wireless                   | 1         | 0.79%   |
| Ralink Technology                 | 1         | 0.79%   |
| Qualcomm                          | 1         | 0.79%   |
| Ericsson Business Mobile Networks | 1         | 0.79%   |
| Dell                              | 1         | 0.79%   |
| D-Link System                     | 1         | 0.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 13        | 8.13%   |
| Intel Wireless 7260                                                    | 7         | 4.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 3.75%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 6         | 3.75%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 5         | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 2.5%    |
| Nvidia MCP79 Ethernet                                                  | 4         | 2.5%    |
| Intel Wireless 7265                                                    | 4         | 2.5%    |
| Intel Ethernet Connection I218-LM                                      | 4         | 2.5%    |
| Broadcom BCM43224 802.11a/b/g/n                                        | 4         | 2.5%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 1.88%   |
| Intel Wireless 8265 / 8275                                             | 3         | 1.88%   |
| Intel Wireless 8260                                                    | 3         | 1.88%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.88%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3         | 1.88%   |
| Broadcom BCM43142 802.11b/g/n                                          | 3         | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.25%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 1.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 1.25%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 2         | 1.25%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 1.25%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.25%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.25%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 1.25%   |
| HP un2430 Mobile Broadband Module                                      | 2         | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 1.25%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 2         | 1.25%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1         | 0.63%   |
| Sierra Wireless EM7305 Modem                                           | 1         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.63%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.63%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.63%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 31        | 33.7%   |
| Broadcom                          | 20        | 21.74%  |
| Realtek Semiconductor             | 11        | 11.96%  |
| Qualcomm Atheros                  | 11        | 11.96%  |
| MediaTek                          | 5         | 5.43%   |
| Broadcom Limited                  | 4         | 4.35%   |
| Qualcomm Atheros Communications   | 2         | 2.17%   |
| TP-Link                           | 1         | 1.09%   |
| Sierra Wireless                   | 1         | 1.09%   |
| Ralink Technology                 | 1         | 1.09%   |
| Qualcomm                          | 1         | 1.09%   |
| Hewlett-Packard                   | 1         | 1.09%   |
| Ericsson Business Mobile Networks | 1         | 1.09%   |
| Dell                              | 1         | 1.09%   |
| D-Link System                     | 1         | 1.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                           | 7         | 7.53%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 6         | 6.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4         | 4.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 4         | 4.3%    |
| Intel Wireless 7265                                                           | 4         | 4.3%    |
| Broadcom BCM43224 802.11a/b/g/n                                               | 4         | 4.3%    |
| Intel Wireless 8265 / 8275                                                    | 3         | 3.23%   |
| Intel Wireless 8260                                                           | 3         | 3.23%   |
| Intel Wi-Fi 6 AX201                                                           | 3         | 3.23%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter          | 3         | 3.23%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 3         | 3.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 2.15%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 2         | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 2.15%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                             | 2         | 2.15%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 2         | 2.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 2.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 2         | 2.15%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 2         | 2.15%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 1.08%   |
| Sierra Wireless EM7305 Modem                                                  | 1         | 1.08%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1         | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 1.08%   |
| Realtek 802.11n WLAN Adapter                                                  | 1         | 1.08%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 1.08%   |
| Qualcomm QCNFA765 Wireless Network Adapter                                    | 1         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 1.08%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.08%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 1.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1         | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 1         | 1.08%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                           | 1         | 1.08%   |
| Intel Wi-Fi 6 AX200                                                           | 1         | 1.08%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 1.08%   |
| Intel Raptor Lake PCH CNVi WiFi                                               | 1         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 1.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 33.85%  |
| Intel                    | 19        | 29.23%  |
| Broadcom                 | 6         | 9.23%   |
| Qualcomm Atheros         | 5         | 7.69%   |
| Nvidia                   | 5         | 7.69%   |
| Samsung Electronics      | 4         | 6.15%   |
| Marvell Technology Group | 3         | 4.62%   |
| Xiaomi                   | 1         | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 13        | 20%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 9.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 5         | 7.69%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 6.15%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 6.15%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 4.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 4.62%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 3.08%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 3.08%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 3.08%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 1.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.54%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 1.54%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 1.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 1.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 1.54%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 1.54%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 1.54%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.54%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 1.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 1.54%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.54%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.54%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.54%   |
| Intel Ethernet Connection (13) I219-LM                                         | 1         | 1.54%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.54%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 55.41%  |
| Ethernet | 64        | 43.24%  |
| Modem    | 2         | 1.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 82.14%  |
| Ethernet | 15        | 17.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 58        | 69.88%  |
| 1     | 23        | 27.71%  |
| 3     | 1         | 1.2%    |
| 0     | 1         | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 58        | 69.88%  |
| Yes  | 25        | 30.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 36.23%  |
| Apple                           | 14        | 20.29%  |
| Realtek Semiconductor           | 7         | 10.14%  |
| Foxconn / Hon Hai               | 4         | 5.8%    |
| Broadcom                        | 4         | 5.8%    |
| Qualcomm Atheros Communications | 3         | 4.35%   |
| IMC Networks                    | 3         | 4.35%   |
| Lite-On Technology              | 2         | 2.9%    |
| Cambridge Silicon Radio         | 2         | 2.9%    |
| Toshiba                         | 1         | 1.45%   |
| Realtek                         | 1         | 1.45%   |
| Opticis                         | 1         | 1.45%   |
| Hewlett-Packard                 | 1         | 1.45%   |
| Dell                            | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 15        | 21.74%  |
| Apple Bluetooth Host Controller                     | 12        | 17.39%  |
| Realtek Bluetooth Radio                             | 6         | 8.7%    |
| Intel AX201 Bluetooth                               | 4         | 5.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.9%    |
| Intel AX210 Bluetooth                               | 2         | 2.9%    |
| IMC Networks Wireless_Device                        | 2         | 2.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.9%    |
| Broadcom HP Portable SoftSailing                    | 2         | 2.9%    |
| Apple Bluetooth USB Host Controller                 | 2         | 2.9%    |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 1.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.45%   |
| Realtek Bluetooth Radio                             | 1         | 1.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.45%   |
| Opticis Bluetooth Radio                             | 1         | 1.45%   |
| Lite-On Wireless_Device                             | 1         | 1.45%   |
| Lite-On BCM43142A0                                  | 1         | 1.45%   |
| Intel Bluetooth Device                              | 1         | 1.45%   |
| Intel AX200 Bluetooth                               | 1         | 1.45%   |
| IMC Networks BCM20702A0                             | 1         | 1.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.45%   |
| Foxconn / Hon Hai BT                                | 1         | 1.45%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.45%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 1.45%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.45%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1.45%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 61        | 59.8%   |
| Nvidia                               | 21        | 20.59%  |
| AMD                                  | 15        | 14.71%  |
| Thesycon Systemsoftware & Consulting | 1         | 0.98%   |
| Kingston Technology                  | 1         | 0.98%   |
| JBL                                  | 1         | 0.98%   |
| Huawei Technologies                  | 1         | 0.98%   |
| Guillemot                            | 1         | 0.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 6.87%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 6.87%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 6.87%   |
| Intel Sunrise Point-LP HD Audio                                            | 8         | 6.11%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 4.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 3.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 3.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 3.82%   |
| Nvidia MCP89 High Definition Audio                                         | 4         | 3.05%   |
| Nvidia MCP79 High Definition Audio                                         | 4         | 3.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 3.05%   |
| Nvidia GT216 HDMI Audio Controller                                         | 3         | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.29%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 2.29%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.53%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.53%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.53%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.53%   |
| Thesycon Systemsoftware & Consulting D50s                                  | 1         | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.76%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.76%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.76%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.76%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.76%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.76%   |
| Nvidia Audio device                                                        | 1         | 0.76%   |
| Kingston Technology HyperX SoloCast                                        | 1         | 0.76%   |
| JBL Quantum 400                                                            | 1         | 0.76%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 0.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.76%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 25%     |
| SK hynix            | 3         | 15%     |
| Micron Technology   | 2         | 10%     |
| Kingston            | 2         | 10%     |
| Elpida              | 2         | 10%     |
| Crucial             | 2         | 10%     |
| Unknown (ABCD)      | 1         | 5%      |
| Unknown             | 1         | 5%      |
| Ramaxel Technology  | 1         | 5%      |
| Corsair             | 1         | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 4.76%   |
| Unknown RAM Module 1GB SODIMM DDR3                                  | 1         | 4.76%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 4.76%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 4.76%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 1         | 4.76%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 4.76%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                         | 1         | 4.76%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 4.76%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 4.76%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM DDR5 4800MT/s             | 1         | 4.76%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s                | 1         | 4.76%   |
| Ramaxel RAM RMN1740EC48D8W-800 2GB SODIMM DDR2 800MT/s              | 1         | 4.76%   |
| Micron RAM MT62F1G32D4DR-031 8GB Row Of Chips LPDDR5 6400MT/s       | 1         | 4.76%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 1         | 4.76%   |
| Kingston RAM HX316LS9IB/8 8GB SODIMM DDR3 1600MT/s                  | 1         | 4.76%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 2667MT/s             | 1         | 4.76%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                          | 1         | 4.76%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s               | 1         | 4.76%   |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s              | 1         | 4.76%   |
| Crucial RAM CT102464BF832B 16GB SODIMM DDR4 3200MT/s                | 1         | 4.76%   |
| Corsair RAM Module 4GB SODIMM DDR3 1067MT/s                         | 1         | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 8         | 42.11%  |
| DDR4   | 6         | 31.58%  |
| SDRAM  | 1         | 5.26%   |
| LPDDR5 | 1         | 5.26%   |
| LPDDR4 | 1         | 5.26%   |
| DDR5   | 1         | 5.26%   |
| DDR2   | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 16        | 88.89%  |
| Row Of Chips | 2         | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 8         | 40%     |
| 4096  | 4         | 20%     |
| 2048  | 4         | 20%     |
| 16384 | 3         | 15%     |
| 1024  | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 5         | 26.32%  |
| 3200    | 3         | 15.79%  |
| 2667    | 3         | 15.79%  |
| 1067    | 2         | 10.53%  |
| 6400    | 1         | 5.26%   |
| 4800    | 1         | 5.26%   |
| 2400    | 1         | 5.26%   |
| 2048    | 1         | 5.26%   |
| 800     | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

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
| Chicony Electronics                    | 14        | 18.92%  |
| Apple                                  | 10        | 13.51%  |
| Microdia                               | 8         | 10.81%  |
| IMC Networks                           | 7         | 9.46%   |
| Realtek Semiconductor                  | 4         | 5.41%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.41%   |
| Suyin                                  | 3         | 4.05%   |
| Sunplus Innovation Technology          | 3         | 4.05%   |
| Quanta                                 | 3         | 4.05%   |
| Sonix Technology                       | 2         | 2.7%    |
| Ricoh                                  | 2         | 2.7%    |
| Bison Electronics                      | 2         | 2.7%    |
| SunplusIT                              | 1         | 1.35%   |
| Silicon Motion                         | 1         | 1.35%   |
| ShineTech                              | 1         | 1.35%   |
| Samsung Electronics                    | 1         | 1.35%   |
| OYT Tech                               | 1         | 1.35%   |
| MacroSilicon                           | 1         | 1.35%   |
| Luxvisions Innotech Limited            | 1         | 1.35%   |
| Lite-On Technology                     | 1         | 1.35%   |
| GEMBIRD                                | 1         | 1.35%   |
| ALi                                    | 1         | 1.35%   |
| Acer                                   | 1         | 1.35%   |
| Unknown                                | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Apple Built-in iSight                             | 9         | 12.16%  |
| IMC Networks USB2.0 HD UVC WebCam                 | 5         | 6.76%   |
| Microdia Integrated Webcam                        | 4         | 5.41%   |
| Realtek Integrated_Webcam_HD                      | 2         | 2.7%    |
| Quanta HD User Facing                             | 2         | 2.7%    |
| Chicony Integrated Camera                         | 2         | 2.7%    |
| Chicony HP TrueVision HD Camera                   | 2         | 2.7%    |
| Chicony HD WebCam                                 | 2         | 2.7%    |
| Chicony EasyCamera                                | 2         | 2.7%    |
| Suyin HP Truevision HD                            | 1         | 1.35%   |
| Suyin HD WebCam                                   | 1         | 1.35%   |
| Suyin Acer/HP Integrated Webcam [CN0314]          | 1         | 1.35%   |
| SunplusIT XiaoMi Webcam                           | 1         | 1.35%   |
| Sunplus Laptop Integrated Webcam FHD              | 1         | 1.35%   |
| Sunplus FHD Camera Microphone                     | 1         | 1.35%   |
| Sunplus Asus Webcam                               | 1         | 1.35%   |
| Sonix USB2.0 FHD UVC WebCam                       | 1         | 1.35%   |
| Sonix Usb Camera                                  | 1         | 1.35%   |
| Silicon Motion WebCam SCB-0370N                   | 1         | 1.35%   |
| ShineTech USB2.0 HD UVC WebCam                    | 1         | 1.35%   |
| Samsung Galaxy series, misc. (MTP mode)           | 1         | 1.35%   |
| Ricoh USB2.0 Camera                               | 1         | 1.35%   |
| Ricoh Laptop_Integrated_Webcam_FHD                | 1         | 1.35%   |
| Realtek USB Camera                                | 1         | 1.35%   |
| Realtek Integrated Webcam HD                      | 1         | 1.35%   |
| Quanta HD Camera                                  | 1         | 1.35%   |
| OYT Tech OYV1RDFF1                                | 1         | 1.35%   |
| Microdia USB 2.0 Camera                           | 1         | 1.35%   |
| Microdia Sonix USB 2.0 Camera                     | 1         | 1.35%   |
| Microdia Sonix Integrated Webcam                  | 1         | 1.35%   |
| Microdia Integrated_Webcam_HD                     | 1         | 1.35%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]     | 1         | 1.35%   |
| Luxvisions Innotech Limited HP HD Camera          | 1         | 1.35%   |
| Lite-On Integrated Camera                         | 1         | 1.35%   |
| IMC Networks ov9734_azurewave_camera              | 1         | 1.35%   |
| IMC Networks Integrated Camera                    | 1         | 1.35%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1         | 1.35%   |
| Chicony Lenovo EasyCamera                         | 1         | 1.35%   |
| Chicony Integrated RGB Camera                     | 1         | 1.35%   |
| Chicony Integrated HP HD Webcam                   | 1         | 1.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 40%     |
| Synaptics                  | 3         | 30%     |
| Shenzhen Goodix Technology | 2         | 20%     |
| LighTuning Technology      | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                       | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 10%     |
| Validity Sensors VFS491                                   | 1         | 10%     |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 10%     |
| Synaptics UWP WBDI Device                                 | 1         | 10%     |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 10%     |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 10%     |

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


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 28.57%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 14.29%  |
| Broadcom 58200                                                               | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 47        | 56.63%  |
| 1     | 26        | 31.33%  |
| 2     | 9         | 10.84%  |
| 3     | 1         | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 11        | 23.91%  |
| Fingerprint reader    | 10        | 21.74%  |
| Multimedia controller | 7         | 15.22%  |
| Chipcard              | 7         | 15.22%  |
| Graphics card         | 5         | 10.87%  |
| Storage               | 3         | 6.52%   |
| Network               | 1         | 2.17%   |
| Camera                | 1         | 2.17%   |
| Bluetooth             | 1         | 2.17%   |

