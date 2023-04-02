Parrot 5.0 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Parrot 5.0.

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

Total: 112

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | ThinkPad X230 23253Z5       | [1237b75ae4](https://linux-hardware.org/?probe=1237b75ae4) | Feb 24, 2023 |
| ASUSTek   | ASUSPRO P1440FAC_P1440FA    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| HP        | EliteBook 840 G7 Noteboo... | [b50b1adb0f](https://linux-hardware.org/?probe=b50b1adb0f) | Sep 01, 2022 |
| Panasonic | CF-31JBGNNDM                | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo    | ThinkPad T420 4180MNU       | [437387fdc3](https://linux-hardware.org/?probe=437387fdc3) | Aug 10, 2022 |
| Lenovo    | ThinkPad T420 4180MNU       | [dae7cc7b69](https://linux-hardware.org/?probe=dae7cc7b69) | Aug 08, 2022 |
| HP        | Laptop 15-dy2xxx            | [a7e9a050ea](https://linux-hardware.org/?probe=a7e9a050ea) | Aug 02, 2022 |
| Dell      | Latitude E6420              | [a6b2ee6088](https://linux-hardware.org/?probe=a6b2ee6088) | Jul 30, 2022 |
| HP        | 250 G2                      | [5650fd3dd6](https://linux-hardware.org/?probe=5650fd3dd6) | Jul 28, 2022 |
| Fujitsu   | LIFEBOOK AH532/G21          | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu   | LIFEBOOK AH532/G21          | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| Sony      | VPCSB1C5E                   | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| Lenovo    | Z40-70 80E6                 | [e77b84e593](https://linux-hardware.org/?probe=e77b84e593) | Jul 22, 2022 |
| Acer      | Predator PT516-51s          | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Lenovo    | IdeaPad 3 15IIL05 81WE      | [90cf247d2d](https://linux-hardware.org/?probe=90cf247d2d) | Jul 20, 2022 |
| HP        | Laptop 15-dy2xxx            | [2d31c995c8](https://linux-hardware.org/?probe=2d31c995c8) | Jul 19, 2022 |
| HP        | Laptop 15-dy2xxx            | [2c55e11e85](https://linux-hardware.org/?probe=2c55e11e85) | Jul 18, 2022 |
| Unknown   | Unknown                     | [a7de2e1421](https://linux-hardware.org/?probe=a7de2e1421) | Jul 14, 2022 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [713bd9f4b0](https://linux-hardware.org/?probe=713bd9f4b0) | Jul 14, 2022 |
| Dell      | Inspiron MM061              | [49e71e9dc1](https://linux-hardware.org/?probe=49e71e9dc1) | Jul 13, 2022 |
| ASUSTek   | TUF Gaming FX504GD_FX80G... | [2ffa772ac9](https://linux-hardware.org/?probe=2ffa772ac9) | Jul 10, 2022 |
| Apple     | MacBookPro5,1               | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Lenovo    | ThinkPad L430 2465C32       | [f088c4ae11](https://linux-hardware.org/?probe=f088c4ae11) | Jul 09, 2022 |
| ASUSTek   | TUF Gaming FX504GD_FX80G... | [48aa7eac9f](https://linux-hardware.org/?probe=48aa7eac9f) | Jul 09, 2022 |
| Acer      | Predator PT516-51s          | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| HP        | Laptop 15-bs2xx             | [fc35a0726c](https://linux-hardware.org/?probe=fc35a0726c) | Jul 03, 2022 |
| HP        | Pavilion dv6                | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| HP        | ProBook 440 G5              | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Toshiba   | Satellite-L845              | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo    | IdeaPad 3 15IIL05 81WE      | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo    | IdeaPad 3 15IIL05 81WE      | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo    | ThinkPad T470p 20J7S0CF0... | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo    | ThinkPad T470p 20J7S0CF0... | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Dell      | Inspiron 15-3567            | [fd246079ad](https://linux-hardware.org/?probe=fd246079ad) | Jun 04, 2022 |
| HUAWEI    | BOHK-WAX9X                  | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo    | ThinkPad X230 2325N66       | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell      | Latitude E6540              | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell      | Latitude E6540              | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo    | Legion 5 15ACH6 82JW        | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo    | Legion 5 15ACH6 82JW        | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell      | Latitude 5400               | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo    | IdeaPad 320S-14IKB 80X4     | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Dell      | Latitude E6410              | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI       | GE62 6QE                    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| Lenovo    | V330-15IKB 81AX             | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| ASUSTek   | ROG Strix G733ZX_G733ZX     | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI    | HVY-WXX9                    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP        | EliteBook 8470p             | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Lenovo    | IdeaPad L340-17API 81LY     | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| MSI       | Modern 15 A5M               | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple     | MacBookPro15,1              | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI       | Modern 15 A5M               | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Razer     | Blade 15 Base Model (Ear... | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| ASUSTek   | X540SAA                     | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo    | IdeaPad L340-17API 81LY     | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| Toshiba   | Satellite Click 2 L35W-B    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI       | Modern 15 A5M               | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI       | Modern 15 A5M               | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI       | Modern 15 A5M               | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware | M14xR1                      | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP        | Notebook                    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ASUSTek   | X540SAA                     | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| MSI       | Modern 15 A5M               | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| ASUSTek   | X75VC                       | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper    | EZbook                      | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple     | MacBookAir3,1               | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox   | Edge-Pro NS50MU             | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Apple     | MacBookPro11,4              | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell      | Inspiron 5570               | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| Dell      | Latitude XT2                | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Jumper    | EZbook                      | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple     | MacBookPro11,4              | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Jumper    | EZbook                      | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi     | GemiBook                    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Samsung   | 550P5C/550P7C               | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Toshiba   | Satellite C75D-B            | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer      | Nitro AN517-41              | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi     | GemiBook                    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer      | Nitro AN515-54              | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| HP        | ProBook 4535s               | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP        | Notebook                    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple     | MacBook7,1                  | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple     | MacBook7,1                  | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Dell      | Inspiron N5110              | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo    | ThinkPad T480 20L6SCYP00    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| Acer      | Aspire A315-21              | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Dell      | Latitude 7480               | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP        | Pavilion Laptop 14-ec0xx... | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP        | Pavilion Laptop 14-ec0xx... | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell      | Inspiron 5580               | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo    | ThinkPad E14 20RA0016GE     | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo    | ThinkPad X1 Extreme Gen ... | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| Lenovo    | IdeaPad Y580                | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| Lenovo    | IdeaPad Y580                | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Lenovo    | IdeaPad 3 15IIL05 81WE      | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo    | IdeaPad 3 15IIL05 81WE      | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| MSI       | Creator Z16 Hiroshi F A1... | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP        | ZBook Firefly 14 G7 Mobi... | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Dell      | Latitude E6410              | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| Acer      | TravelMate 5720             | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP        | Pavilion g7                 | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Lenovo    | B50-80 80EW                 | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo    | B50-80 80EW                 | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell      | Latitude E7450              | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell      | Latitude E7450              | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| HP        | Laptop 15q-dy0xxx           | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| HP        | Pavilion g7                 | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP        | Pavilion g7                 | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP        | Pavilion g7                 | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| HP        | EliteBook 840 G3            | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.16.0-12parrot1-amd64 | 34        | 40.48%  |
| 5.14.0-9parrot1-amd64  | 27        | 32.14%  |
| 5.18.0-1parrot1-amd64  | 13        | 15.48%  |
| 5.14.0-2parrot1-amd64  | 6         | 7.14%   |
| 5.15.0-15parrot1-amd64 | 3         | 3.57%   |
| 5.15.0-5parrot1-amd64  | 1         | 1.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16.0  | 34        | 40.96%  |
| 5.14.0  | 32        | 38.55%  |
| 5.18.0  | 13        | 15.66%  |
| 5.15.0  | 4         | 4.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 34        | 40.96%  |
| 5.14    | 32        | 38.55%  |
| 5.18    | 13        | 15.66%  |
| 5.15    | 4         | 4.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 82        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 55        | 66.27%  |
| KDE5    | 24        | 28.92%  |
| Unknown | 2         | 2.41%   |
| XFCE    | 1         | 1.2%    |
| KDE     | 1         | 1.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 79        | 96.34%  |
| Tty     | 2         | 2.44%   |
| Wayland | 1         | 1.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 49        | 59.76%  |
| Unknown | 32        | 39.02%  |
| SDDM    | 1         | 1.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 44        | 53.66%  |
| en_GB | 8         | 9.76%   |
| es_ES | 5         | 6.1%    |
| fr_FR | 3         | 3.66%   |
| en_IN | 3         | 3.66%   |
| ru_RU | 2         | 2.44%   |
| pt_BR | 2         | 2.44%   |
| pl_PL | 2         | 2.44%   |
| en_AU | 2         | 2.44%   |
| de_DE | 2         | 2.44%   |
| pt_PT | 1         | 1.22%   |
| it_IT | 1         | 1.22%   |
| fi_FI | 1         | 1.22%   |
| es_PE | 1         | 1.22%   |
| es_MX | 1         | 1.22%   |
| es_AR | 1         | 1.22%   |
| en_ZA | 1         | 1.22%   |
| en_CA | 1         | 1.22%   |
| cs_CZ | 1         | 1.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 50        | 60.24%  |
| EFI  | 33        | 39.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 72        | 87.8%   |
| Ext4    | 7         | 8.54%   |
| Overlay | 3         | 3.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 38        | 45.78%  |
| GPT     | 32        | 38.55%  |
| MBR     | 13        | 15.66%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 87.95%  |
| Yes       | 10        | 12.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 66.67%  |
| Yes       | 28        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 18        | 21.95%  |
| Hewlett-Packard     | 15        | 18.29%  |
| Dell                | 13        | 15.85%  |
| ASUSTek Computer    | 7         | 8.54%   |
| MSI                 | 5         | 6.1%    |
| Acer                | 5         | 6.1%    |
| Apple               | 4         | 4.88%   |
| Toshiba             | 3         | 3.66%   |
| HUAWEI              | 2         | 2.44%   |
| Sony                | 1         | 1.22%   |
| Samsung Electronics | 1         | 1.22%   |
| Razer               | 1         | 1.22%   |
| Panasonic           | 1         | 1.22%   |
| Metabox             | 1         | 1.22%   |
| Jumper              | 1         | 1.22%   |
| Fujitsu             | 1         | 1.22%   |
| Chuwi               | 1         | 1.22%   |
| Alienware           | 1         | 1.22%   |
| Unknown             | 1         | 1.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 3.66%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 2         | 2.44%   |
| HP Notebook                                        | 2         | 2.44%   |
| Dell Latitude E6410                                | 2         | 2.44%   |
| Toshiba Satellite-L845                             | 1         | 1.22%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 1.22%   |
| Toshiba Satellite C75D-B                           | 1         | 1.22%   |
| Sony VPCSB1C5E                                     | 1         | 1.22%   |
| Samsung 550P5C/550P7C                              | 1         | 1.22%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 1.22%   |
| Panasonic CF-31JBGNNDM                             | 1         | 1.22%   |
| MSI GE62 6QE                                       | 1         | 1.22%   |
| MSI Creator Z16 Hiroshi F A11UE                    | 1         | 1.22%   |
| Metabox Edge-Pro NS50MU                            | 1         | 1.22%   |
| Lenovo Z40-70 80E6                                 | 1         | 1.22%   |
| Lenovo V330-15IKB 81AX                             | 1         | 1.22%   |
| Lenovo ThinkPad X230 2325N66                       | 1         | 1.22%   |
| Lenovo ThinkPad X230 23253Z5                       | 1         | 1.22%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS        | 1         | 1.22%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW           | 1         | 1.22%   |
| Lenovo ThinkPad T480 20L6SCYP00                    | 1         | 1.22%   |
| Lenovo ThinkPad T470p 20J7S0CF00                   | 1         | 1.22%   |
| Lenovo ThinkPad T420 4180MNU                       | 1         | 1.22%   |
| Lenovo ThinkPad L430 2465C32                       | 1         | 1.22%   |
| Lenovo ThinkPad E14 20RA0016GE                     | 1         | 1.22%   |
| Lenovo Legion 5 15ACH6 82JW                        | 1         | 1.22%   |
| Lenovo IdeaPad Y580                                | 1         | 1.22%   |
| Lenovo IdeaPad L340-17API 81LY                     | 1         | 1.22%   |
| Lenovo IdeaPad 320S-14IKB 80X4                     | 1         | 1.22%   |
| Lenovo B50-80 80EW                                 | 1         | 1.22%   |
| Jumper EZbook                                      | 1         | 1.22%   |
| HUAWEI HVY-WXX9                                    | 1         | 1.22%   |
| HUAWEI BOHK-WAX9X                                  | 1         | 1.22%   |
| HP ZBook Firefly 14 G7 Mobile Workstation          | 1         | 1.22%   |
| HP ProBook 4535s                                   | 1         | 1.22%   |
| HP ProBook 440 G5                                  | 1         | 1.22%   |
| HP Pavilion Laptop 14-ec0xxx                       | 1         | 1.22%   |
| HP Pavilion g7                                     | 1         | 1.22%   |
| HP Pavilion dv6                                    | 1         | 1.22%   |
| HP Laptop 15q-dy0xxx                               | 1         | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 9         | 10.98%  |
| Dell Latitude          | 8         | 9.76%   |
| Lenovo IdeaPad         | 5         | 6.1%    |
| Dell Inspiron          | 5         | 6.1%    |
| MSI Modern             | 3         | 3.66%   |
| HP Pavilion            | 3         | 3.66%   |
| HP Laptop              | 3         | 3.66%   |
| HP EliteBook           | 3         | 3.66%   |
| Toshiba Satellite      | 2         | 2.44%   |
| HP ProBook             | 2         | 2.44%   |
| HP Notebook            | 2         | 2.44%   |
| Acer Nitro             | 2         | 2.44%   |
| Toshiba Satellite-L845 | 1         | 1.22%   |
| Sony VPCSB1C5E         | 1         | 1.22%   |
| Samsung 550P5C         | 1         | 1.22%   |
| Razer Blade            | 1         | 1.22%   |
| Panasonic CF-31JBGNNDM | 1         | 1.22%   |
| MSI GE62               | 1         | 1.22%   |
| MSI Creator            | 1         | 1.22%   |
| Metabox Edge-Pro       | 1         | 1.22%   |
| Lenovo Z40-70          | 1         | 1.22%   |
| Lenovo V330-15IKB      | 1         | 1.22%   |
| Lenovo Legion          | 1         | 1.22%   |
| Lenovo B50-80          | 1         | 1.22%   |
| Jumper EZbook          | 1         | 1.22%   |
| HUAWEI HVY-WXX9        | 1         | 1.22%   |
| HUAWEI BOHK-WAX9X      | 1         | 1.22%   |
| HP ZBook               | 1         | 1.22%   |
| HP 250                 | 1         | 1.22%   |
| Fujitsu LIFEBOOK       | 1         | 1.22%   |
| Chuwi GemiBook         | 1         | 1.22%   |
| ASUS X75VC             | 1         | 1.22%   |
| ASUS X540SAA           | 1         | 1.22%   |
| ASUS VivoBook          | 1         | 1.22%   |
| ASUS TUF               | 1         | 1.22%   |
| ASUS ROG               | 1         | 1.22%   |
| ASUS ASUSPRO           | 1         | 1.22%   |
| ASUS ASUS              | 1         | 1.22%   |
| Apple MacBookPro5      | 1         | 1.22%   |
| Apple MacBookPro15     | 1         | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 11        | 13.41%  |
| 2020 | 10        | 12.2%   |
| 2012 | 10        | 12.2%   |
| 2017 | 8         | 9.76%   |
| 2011 | 8         | 9.76%   |
| 2019 | 7         | 8.54%   |
| 2018 | 6         | 7.32%   |
| 2016 | 5         | 6.1%    |
| 2014 | 4         | 4.88%   |
| 2010 | 4         | 4.88%   |
| 2013 | 3         | 3.66%   |
| 2022 | 1         | 1.22%   |
| 2015 | 1         | 1.22%   |
| 2009 | 1         | 1.22%   |
| 2008 | 1         | 1.22%   |
| 2007 | 1         | 1.22%   |
| 2006 | 1         | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 82        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 82        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 82        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 26        | 31.71%  |
| 3.01-4.0    | 13        | 15.85%  |
| 16.01-24.0  | 13        | 15.85%  |
| 8.01-16.0   | 13        | 15.85%  |
| 32.01-64.0  | 11        | 13.41%  |
| 64.01-256.0 | 3         | 3.66%   |
| 24.01-32.0  | 2         | 2.44%   |
| 1.01-2.0    | 1         | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 30        | 36.14%  |
| 1.01-2.0  | 29        | 34.94%  |
| 4.01-8.0  | 14        | 16.87%  |
| 3.01-4.0  | 6         | 7.23%   |
| 8.01-16.0 | 2         | 2.41%   |
| 0.51-1.0  | 2         | 2.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 64.63%  |
| 2      | 27        | 32.93%  |
| 3      | 1         | 1.22%   |
| 0      | 1         | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 68.29%  |
| Yes       | 26        | 31.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 81.93%  |
| No        | 15        | 18.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 98.78%  |
| No        | 1         | 1.22%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 84.15%  |
| No        | 13        | 15.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 29        | 34.94%  |
| UK           | 5         | 6.02%   |
| Spain        | 5         | 6.02%   |
| Germany      | 4         | 4.82%   |
| India        | 3         | 3.61%   |
| Brazil       | 3         | 3.61%   |
| South Africa | 2         | 2.41%   |
| Russia       | 2         | 2.41%   |
| Mexico       | 2         | 2.41%   |
| Italy        | 2         | 2.41%   |
| France       | 2         | 2.41%   |
| Denmark      | 2         | 2.41%   |
| Canada       | 2         | 2.41%   |
| Australia    | 2         | 2.41%   |
| Switzerland  | 1         | 1.2%    |
| Sweden       | 1         | 1.2%    |
| Puerto Rico  | 1         | 1.2%    |
| Portugal     | 1         | 1.2%    |
| Peru         | 1         | 1.2%    |
| Netherlands  | 1         | 1.2%    |
| Nepal        | 1         | 1.2%    |
| Morocco      | 1         | 1.2%    |
| Kenya        | 1         | 1.2%    |
| Georgia      | 1         | 1.2%    |
| Finland      | 1         | 1.2%    |
| Egypt        | 1         | 1.2%    |
| Czechia      | 1         | 1.2%    |
| Bulgaria     | 1         | 1.2%    |
| Benin        | 1         | 1.2%    |
| Austria      | 1         | 1.2%    |
| Argentina    | 1         | 1.2%    |
| Algeria      | 1         | 1.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Seattle                | 3         | 3.53%   |
| Ruskin                 | 2         | 2.35%   |
| Los Angeles            | 2         | 2.35%   |
| Dublin                 | 2         | 2.35%   |
| Camden                 | 2         | 2.35%   |
| Zurich                 | 1         | 1.18%   |
| Villa Carlos Paz       | 1         | 1.18%   |
| Vienna                 | 1         | 1.18%   |
| Ts'khinvali            | 1         | 1.18%   |
| Trivandrum             | 1         | 1.18%   |
| Tangier                | 1         | 1.18%   |
| Tampere                | 1         | 1.18%   |
| Sydney                 | 1         | 1.18%   |
| Sumaré                | 1         | 1.18%   |
| St Petersburg          | 1         | 1.18%   |
| Spotsylvania           | 1         | 1.18%   |
| South Hamilton         | 1         | 1.18%   |
| Skive                  | 1         | 1.18%   |
| Sao Bernardo do Campo  | 1         | 1.18%   |
| San Juan               | 1         | 1.18%   |
| Saint Paul             | 1         | 1.18%   |
| Rho                    | 1         | 1.18%   |
| Pretoria               | 1         | 1.18%   |
| Prague                 | 1         | 1.18%   |
| Plovdiv                | 1         | 1.18%   |
| Phoenix                | 1         | 1.18%   |
| Orofino                | 1         | 1.18%   |
| Opelousas              | 1         | 1.18%   |
| Nairobi                | 1         | 1.18%   |
| Mt. Pleasant           | 1         | 1.18%   |
| Mostoles               | 1         | 1.18%   |
| Moscow                 | 1         | 1.18%   |
| Montigny-le-Bretonneux | 1         | 1.18%   |
| Melbourne              | 1         | 1.18%   |
| Mazatlán              | 1         | 1.18%   |
| Mata de Sao Joao       | 1         | 1.18%   |
| Mangalagiri            | 1         | 1.18%   |
| Madrid                 | 1         | 1.18%   |
| Lynwood                | 1         | 1.18%   |
| London                 | 1         | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 18     | 15.69%  |
| Toshiba             | 12        | 13     | 11.76%  |
| WDC                 | 10        | 11     | 9.8%    |
| Kingston            | 8         | 8      | 7.84%   |
| Seagate             | 7         | 7      | 6.86%   |
| Unknown             | 5         | 7      | 4.9%    |
| Hitachi             | 5         | 6      | 4.9%    |
| SanDisk             | 4         | 5      | 3.92%   |
| China               | 4         | 4      | 3.92%   |
| Micron Technology   | 3         | 3      | 2.94%   |
| Intel               | 3         | 6      | 2.94%   |
| SK hynix            | 2         | 2      | 1.96%   |
| HGST                | 2         | 2      | 1.96%   |
| Crucial             | 2         | 2      | 1.96%   |
| Apple               | 2         | 2      | 1.96%   |
| YMTC                | 1         | 1      | 0.98%   |
| Team                | 1         | 1      | 0.98%   |
| S3+                 | 1         | 1      | 0.98%   |
| RZX                 | 1         | 1      | 0.98%   |
| PNY                 | 1         | 1      | 0.98%   |
| Phison              | 1         | 1      | 0.98%   |
| Netac               | 1         | 1      | 0.98%   |
| LITEON              | 1         | 1      | 0.98%   |
| KingSpec            | 1         | 1      | 0.98%   |
| KingFast            | 1         | 2      | 0.98%   |
| Intenso             | 1         | 2      | 0.98%   |
| HUAWEI              | 1         | 1      | 0.98%   |
| BR                  | 1         | 1      | 0.98%   |
| BHT                 | 1         | 1      | 0.98%   |
| ASMT                | 1         | 1      | 0.98%   |
| ASMedia             | 1         | 1      | 0.98%   |
| A-DATA Technology   | 1         | 1      | 0.98%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                | 5         | 4.55%   |
| Kingston NVMe SSD Drive 512GB         | 3         | 2.73%   |
| Unknown MMC Card  32GB                | 2         | 1.82%   |
| Toshiba MQ01ABD075 752GB              | 2         | 1.82%   |
| SanDisk NVMe SSD Drive 1TB            | 2         | 1.82%   |
| Samsung NVMe SSD Drive 1024GB         | 2         | 1.82%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 1.82%   |
| YMTC PC005 512GB                      | 1         | 0.91%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 1         | 0.91%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 0.91%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 0.91%   |
| WDC WDBNCE2500PNC 250GB SSD           | 1         | 0.91%   |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 0.91%   |
| WDC WD5000LPCX-60VHAT1 500GB          | 1         | 0.91%   |
| WDC WD3200BPVT-00JJ5T0 320GB          | 1         | 0.91%   |
| WDC WD10SPZX-75Z10T2 1TB              | 1         | 0.91%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.91%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB  | 1         | 0.91%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB    | 1         | 0.91%   |
| Unknown SE32G  32GB                   | 1         | 0.91%   |
| Unknown SD/MMC/MS PRO 64GB            | 1         | 0.91%   |
| Unknown SD  128GB                     | 1         | 0.91%   |
| Unknown ISOCOM  64GB                  | 1         | 0.91%   |
| Toshiba MQ01ACF050 500GB              | 1         | 0.91%   |
| Toshiba MQ01ABF050 500GB              | 1         | 0.91%   |
| Toshiba MQ01ABD100 1TB                | 1         | 0.91%   |
| Toshiba MK2555GSXF 250GB              | 1         | 0.91%   |
| Toshiba MK2533GSGF 250GB              | 1         | 0.91%   |
| Team TM8PS7512G 512GB SSD             | 1         | 0.91%   |
| SK hynix NVMe SSD Drive 1024GB        | 1         | 0.91%   |
| SK hynix HFS128G32TNF-N3A0A 128GB SSD | 1         | 0.91%   |
| Seagate ST9250315AS 250GB             | 1         | 0.91%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 0.91%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 0.91%   |
| Seagate ST320LM001 HN-M320MBB 320GB   | 1         | 0.91%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 1         | 0.91%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 0.91%   |
| Seagate BUP Slim BK 2TB               | 1         | 0.91%   |
| SanDisk SDSSDH3 2T00 2TB              | 1         | 0.91%   |
| SanDisk NVMe SSD Drive 256GB          | 1         | 0.91%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 12        | 13     | 36.36%  |
| Seagate | 7         | 7      | 21.21%  |
| WDC     | 5         | 5      | 15.15%  |
| Hitachi | 5         | 6      | 15.15%  |
| HGST    | 2         | 2      | 6.06%   |
| Unknown | 1         | 2      | 3.03%   |
| ASMedia | 1         | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 14.29%  |
| WDC                 | 4         | 4      | 11.43%  |
| Kingston            | 4         | 4      | 11.43%  |
| China               | 4         | 4      | 11.43%  |
| Crucial             | 2         | 2      | 5.71%   |
| Team                | 1         | 1      | 2.86%   |
| SK hynix            | 1         | 1      | 2.86%   |
| SanDisk             | 1         | 1      | 2.86%   |
| S3+                 | 1         | 1      | 2.86%   |
| RZX                 | 1         | 1      | 2.86%   |
| PNY                 | 1         | 1      | 2.86%   |
| Netac               | 1         | 1      | 2.86%   |
| Micron Technology   | 1         | 1      | 2.86%   |
| LITEON              | 1         | 1      | 2.86%   |
| KingSpec            | 1         | 1      | 2.86%   |
| KingFast            | 1         | 1      | 2.86%   |
| Intenso             | 1         | 2      | 2.86%   |
| BR                  | 1         | 1      | 2.86%   |
| BHT                 | 1         | 1      | 2.86%   |
| ASMT                | 1         | 1      | 2.86%   |
| Apple               | 1         | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 33        | 36     | 33.67%  |
| HDD     | 31        | 36     | 31.63%  |
| NVMe    | 28        | 36     | 28.57%  |
| MMC     | 4         | 5      | 4.08%   |
| Unknown | 2         | 2      | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 68     | 60.64%  |
| NVMe | 28        | 36     | 29.79%  |
| SAS  | 5         | 6      | 5.32%   |
| MMC  | 4         | 5      | 4.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 46     | 62.5%   |
| 0.51-1.0   | 21        | 23     | 32.81%  |
| 1.01-2.0   | 3         | 3      | 4.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 22        | 26.51%  |
| 501-1000   | 16        | 19.28%  |
| 251-500    | 13        | 15.66%  |
| Unknown    | 13        | 15.66%  |
| 1001-2000  | 12        | 14.46%  |
| 1-20       | 3         | 3.61%   |
| 2001-3000  | 2         | 2.41%   |
| 21-50      | 1         | 1.2%    |
| 51-100     | 1         | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 28        | 33.73%  |
| 51-100   | 14        | 16.87%  |
| Unknown  | 13        | 15.66%  |
| 1-20     | 11        | 13.25%  |
| 251-500  | 8         | 9.64%   |
| 101-250  | 6         | 7.23%   |
| 501-1000 | 3         | 3.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-00JJ5T0 320GB        | 1         | 1      | 16.67%  |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 16.67%  |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 16.67%  |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 16.67%  |
| Kingston SUV400S37480G 480GB SSD    | 1         | 1      | 16.67%  |
| Intel HBRPEKNX0202AHO 32GB          | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 2         | 2      | 33.33%  |
| WDC      | 1         | 1      | 16.67%  |
| Toshiba  | 1         | 1      | 16.67%  |
| Kingston | 1         | 1      | 16.67%  |
| Intel    | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Toshiba | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 66.67%  |
| NVMe | 1         | 1      | 16.67%  |
| SSD  | 1         | 1      | 16.67%  |

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
| Works    | 43        | 51     | 47.78%  |
| Detected | 41        | 58     | 45.56%  |
| Malfunc  | 6         | 6      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 58        | 59.18%  |
| Samsung Electronics         | 12        | 12.24%  |
| AMD                         | 9         | 9.18%   |
| SanDisk                     | 5         | 5.1%    |
| Kingston Technology Company | 4         | 4.08%   |
| Nvidia                      | 3         | 3.06%   |
| Micron Technology           | 2         | 2.04%   |
| Yangtze Memory Technologies | 1         | 1.02%   |
| SK hynix                    | 1         | 1.02%   |
| Phison Electronics          | 1         | 1.02%   |
| Apple                       | 1         | 1.02%   |
| ADATA Technology            | 1         | 1.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 9         | 8.11%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 9         | 8.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 8         | 7.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 7         | 6.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 4.5%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 5         | 4.5%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 5         | 4.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 4.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 4         | 3.6%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 3.6%    |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 2.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 2.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 1.8%    |
| Samsung NVMe SSD Controller 980                                                        | 2         | 1.8%    |
| Micron NVMe Storage Controller                                                         | 2         | 1.8%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1.8%    |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 1.8%    |
| Yangtze Memory Non-Volatile memory controller                                          | 1         | 0.9%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                         | 1         | 0.9%    |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.9%    |
| SanDisk NVMe Controller                                                                | 1         | 0.9%    |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.9%    |
| Phison E12 NVMe Controller                                                             | 1         | 0.9%    |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.9%    |
| Nvidia MCP89 SATA Controller                                                           | 1         | 0.9%    |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 0.9%    |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 0.9%    |
| Intel SSD 660P Series                                                                  | 1         | 0.9%    |
| Intel SSD 600P Series                                                                  | 1         | 0.9%    |
| Intel NVMe Controller                                                                  | 1         | 0.9%    |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 0.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 0.9%    |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                                   | 1         | 0.9%    |
| Intel Comet Lake PCH-H RAID                                                            | 1         | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.9%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 45        | 45.45%  |
| NVMe | 28        | 28.28%  |
| RAID | 15        | 15.15%  |
| IDE  | 11        | 11.11%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 67        | 81.71%  |
| AMD    | 15        | 18.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 3.66%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 3.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 2.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 2.44%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 2         | 2.44%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 2         | 2.44%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 2         | 2.44%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 2         | 2.44%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 2         | 2.44%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 2         | 2.44%   |
| Intel Pentium CPU N3530 @ 2.16GHz       | 1         | 1.22%   |
| Intel Pentium CPU 4415U @ 2.30GHz       | 1         | 1.22%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 1         | 1.22%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 1.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.22%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 1.22%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 1.22%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.22%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 1.22%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.22%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 1.22%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 1         | 1.22%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 1.22%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 1.22%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 1.22%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 1.22%   |
| Intel Core i7-10850H CPU @ 2.70GHz      | 1         | 1.22%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.22%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 1         | 1.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.22%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 1         | 1.22%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 1.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.22%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 1.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.22%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.22%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 1         | 1.22%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 1         | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 20        | 24.39%  |
| Intel Core i5    | 20        | 24.39%  |
| Intel Core i3    | 8         | 9.76%   |
| AMD Ryzen 7      | 7         | 8.54%   |
| Other            | 6         | 7.32%   |
| Intel Celeron    | 6         | 7.32%   |
| Intel Core 2 Duo | 5         | 6.1%    |
| AMD Ryzen 5      | 3         | 3.66%   |
| Intel Pentium    | 2         | 2.44%   |
| AMD A6           | 2         | 2.44%   |
| Intel Core 2     | 1         | 1.22%   |
| AMD E2           | 1         | 1.22%   |
| AMD A4           | 1         | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 42        | 51.22%  |
| 4      | 26        | 31.71%  |
| 8      | 8         | 9.76%   |
| 6      | 5         | 6.1%    |
| 14     | 1         | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 63        | 76.83%  |
| 1      | 19        | 23.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 82        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 45.78%  |
| 0x806e9    | 5         | 6.02%   |
| 0x306a9    | 5         | 6.02%   |
| 0x206a7    | 5         | 6.02%   |
| 0x806ec    | 3         | 3.61%   |
| 0xa0652    | 2         | 2.41%   |
| 0x706e5    | 2         | 2.41%   |
| 0x706a8    | 2         | 2.41%   |
| 0x406e3    | 2         | 2.41%   |
| 0x1067a    | 2         | 2.41%   |
| 0x07030105 | 2         | 2.41%   |
| 0x906ed    | 1         | 1.2%    |
| 0x906ea    | 1         | 1.2%    |
| 0x906e9    | 1         | 1.2%    |
| 0x906a3    | 1         | 1.2%    |
| 0x806eb    | 1         | 1.2%    |
| 0x806ea    | 1         | 1.2%    |
| 0x806d1    | 1         | 1.2%    |
| 0x806c1    | 1         | 1.2%    |
| 0x6f6      | 1         | 1.2%    |
| 0x506c9    | 1         | 1.2%    |
| 0x40651    | 1         | 1.2%    |
| 0x306c3    | 1         | 1.2%    |
| 0x08600106 | 1         | 1.2%    |
| 0x08108109 | 1         | 1.2%    |
| 0x03000027 | 1         | 1.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 19        | 23.17%  |
| SandyBridge      | 10        | 12.2%   |
| IvyBridge        | 8         | 9.76%   |
| Penryn           | 5         | 6.1%    |
| Unknown          | 5         | 6.1%    |
| Skylake          | 3         | 3.66%   |
| IceLake          | 3         | 3.66%   |
| Goldmont plus    | 3         | 3.66%   |
| Zen+             | 2         | 2.44%   |
| Zen 3            | 2         | 2.44%   |
| Zen 2            | 2         | 2.44%   |
| Westmere         | 2         | 2.44%   |
| TigerLake        | 2         | 2.44%   |
| Silvermont       | 2         | 2.44%   |
| Puma             | 2         | 2.44%   |
| Haswell          | 2         | 2.44%   |
| Excavator        | 2         | 2.44%   |
| CometLake        | 2         | 2.44%   |
| Broadwell        | 2         | 2.44%   |
| K10 Llano        | 1         | 1.22%   |
| Goldmont         | 1         | 1.22%   |
| Core             | 1         | 1.22%   |
| Alderlake Hybrid | 1         | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 61        | 55.96%  |
| Nvidia | 24        | 22.02%  |
| AMD    | 24        | 22.02%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 10        | 8.93%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 6.25%   |
| Intel UHD Graphics 620                                                    | 4         | 3.57%   |
| Intel HD Graphics 620                                                     | 4         | 3.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 3.57%   |
| AMD Lucienne                                                              | 4         | 3.57%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 2.68%   |
| Nvidia MCP89 [GeForce 320M]                                               | 2         | 1.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1.79%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 1.79%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.79%   |
| Intel HD Graphics 5500                                                    | 2         | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.79%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 1.79%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 2         | 1.79%   |
| AMD Renoir                                                                | 2         | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.79%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.79%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.89%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.89%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.89%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.89%   |
| Nvidia GP108GLM [Quadro P520]                                             | 1         | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.89%   |
| Nvidia GM206M [GeForce GTX 965M]                                          | 1         | 0.89%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.89%   |
| Nvidia GM108M [GeForce 930MX]                                             | 1         | 0.89%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.89%   |
| Nvidia GK107M [GeForce GTX 660M]                                          | 1         | 0.89%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.89%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                      | 1         | 0.89%   |
| Nvidia GF108M [GeForce GT 620M]                                           | 1         | 0.89%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                               | 1         | 0.89%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 45.12%  |
| Intel + Nvidia | 18        | 21.95%  |
| 1 x AMD        | 14        | 17.07%  |
| Intel + AMD    | 6         | 7.32%   |
| AMD + Nvidia   | 3         | 3.66%   |
| 1 x Nvidia     | 2         | 2.44%   |
| 2 x Nvidia     | 1         | 1.22%   |
| 2 x AMD        | 1         | 1.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 75        | 91.46%  |
| Proprietary | 6         | 7.32%   |
| Unknown     | 1         | 1.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 80.49%  |
| 1.01-2.0   | 6         | 7.32%   |
| 0.01-0.5   | 5         | 6.1%    |
| 3.01-4.0   | 3         | 3.66%   |
| 0.51-1.0   | 2         | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 23        | 26.14%  |
| BOE                     | 18        | 20.45%  |
| LG Display              | 12        | 13.64%  |
| Chimei Innolux          | 10        | 11.36%  |
| Samsung Electronics     | 7         | 7.95%   |
| Apple                   | 4         | 4.55%   |
| Chi Mei Optoelectronics | 3         | 3.41%   |
| Lenovo                  | 2         | 2.27%   |
| Unknown (AAA)           | 1         | 1.14%   |
| PANDA                   | 1         | 1.14%   |
| ONN                     | 1         | 1.14%   |
| NEC Computers           | 1         | 1.14%   |
| Kogan                   | 1         | 1.14%   |
| InfoVision              | 1         | 1.14%   |
| Goldstar                | 1         | 1.14%   |
| CSO                     | 1         | 1.14%   |
| AOC                     | 1         | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch         | 3         | 3.41%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch               | 1         | 1.14%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch    | 1         | 1.14%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 598x336mm 27.0-inch      | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch   | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch   | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch   | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch   | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 1         | 1.14%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                | 1         | 1.14%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                    | 1         | 1.14%   |
| NEC Computers EA243WM NEC6863 1920x1200 519x324mm 24.1-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD045A 1366x768 293x165mm 13.2-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD0292 1366x768 309x174mm 14.0-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD0257 1440x900 304x190mm 14.1-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch           | 1         | 1.14%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch             | 1         | 1.14%   |
| Lenovo D27-30 LEN66B8 1920x1080 597x336mm 27.0-inch                    | 1         | 1.14%   |
| Kogan KAMN27QF7TA KGN0270 2560x1440 698x393mm 31.5-inch                | 1         | 1.14%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch           | 1         | 1.14%   |
| Goldstar SIGNAGE GSM0002 3840x2160 1215x686mm 54.9-inch                | 1         | 1.14%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                  | 1         | 1.14%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch       | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1736 1600x900 382x214mm 17.2-inch        | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1526 1920x1080 344x193mm 15.5-inch       | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch        | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch        | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch        | 1         | 1.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 31        | 37.35%  |
| 1366x768 (WXGA)    | 31        | 37.35%  |
| 1600x900 (HD+)     | 6         | 7.23%   |
| 1280x800 (WXGA)    | 4         | 4.82%   |
| 3840x2160 (4K)     | 2         | 2.41%   |
| 2560x1600          | 2         | 2.41%   |
| 1440x900 (WXGA+)   | 2         | 2.41%   |
| 2880x1800          | 1         | 1.2%    |
| 2560x1440 (QHD)    | 1         | 1.2%    |
| 2160x1440          | 1         | 1.2%    |
| 1920x1200 (WUXGA)  | 1         | 1.2%    |
| 1680x1050 (WSXGA+) | 1         | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 35        | 39.77%  |
| 14     | 15        | 17.05%  |
| 13     | 10        | 11.36%  |
| 17     | 7         | 7.95%   |
| 12     | 4         | 4.55%   |
| 24     | 3         | 3.41%   |
| 16     | 3         | 3.41%   |
| 31     | 2         | 2.27%   |
| 27     | 2         | 2.27%   |
| 11     | 2         | 2.27%   |
| 54     | 1         | 1.14%   |
| 48     | 1         | 1.14%   |
| 40     | 1         | 1.14%   |
| 23     | 1         | 1.14%   |
| 21     | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 59        | 67.05%  |
| 351-400     | 9         | 10.23%  |
| 201-300     | 8         | 9.09%   |
| 501-600     | 6         | 6.82%   |
| 601-700     | 2         | 2.27%   |
| 1001-1500   | 2         | 2.27%   |
| 801-900     | 1         | 1.14%   |
| 401-500     | 1         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 67        | 84.81%  |
| 16/10 | 11        | 13.92%  |
| 3/2   | 1         | 1.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 40.91%  |
| 81-90          | 23        | 26.14%  |
| 121-130        | 6         | 6.82%   |
| 61-70          | 4         | 4.55%   |
| 201-250        | 3         | 3.41%   |
| More than 1000 | 2         | 2.27%   |
| 71-80          | 2         | 2.27%   |
| 51-60          | 2         | 2.27%   |
| 351-500        | 2         | 2.27%   |
| 301-350        | 2         | 2.27%   |
| 251-300        | 2         | 2.27%   |
| 111-120        | 2         | 2.27%   |
| 131-140        | 1         | 1.14%   |
| 501-1000       | 1         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 35        | 40.23%  |
| 101-120       | 34        | 39.08%  |
| 51-100        | 11        | 12.64%  |
| 161-240       | 4         | 4.6%    |
| 1-50          | 2         | 2.3%    |
| More than 240 | 1         | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 71        | 85.54%  |
| 2     | 10        | 12.05%  |
| 3     | 1         | 1.2%    |
| 0     | 1         | 1.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 46        | 32.62%  |
| Realtek Semiconductor             | 45        | 31.91%  |
| Qualcomm Atheros                  | 15        | 10.64%  |
| Broadcom                          | 8         | 5.67%   |
| MediaTek                          | 5         | 3.55%   |
| TP-Link                           | 3         | 2.13%   |
| Samsung Electronics               | 2         | 1.42%   |
| Nvidia                            | 2         | 1.42%   |
| NetGear                           | 2         | 1.42%   |
| Huawei Technologies               | 2         | 1.42%   |
| ASUSTek Computer                  | 2         | 1.42%   |
| Apple                             | 2         | 1.42%   |
| Ralink                            | 1         | 0.71%   |
| Qualcomm Atheros Communications   | 1         | 0.71%   |
| Linksys                           | 1         | 0.71%   |
| Ericsson Business Mobile Networks | 1         | 0.71%   |
| DisplayLink                       | 1         | 0.71%   |
| Broadcom Limited                  | 1         | 0.71%   |
| ASIX Electronics                  | 1         | 0.71%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 12.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 5.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.91%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 2.91%   |
| Realtek 802.11ac NIC                                              | 4         | 2.33%   |
| Intel Wireless 3165                                               | 4         | 2.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.74%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 3         | 1.74%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 1.74%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.16%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.16%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.16%   |
| NetGear A6210                                                     | 2         | 1.16%   |
| Intel Wireless 3160                                               | 2         | 1.16%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.16%   |
| Intel Centrino Wireless-N 2200                                    | 2         | 1.16%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.16%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.16%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 2         | 1.16%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.58%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.58%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.58%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.58%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1         | 0.58%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1         | 0.58%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 45.92%  |
| Realtek Semiconductor           | 21        | 21.43%  |
| Qualcomm Atheros                | 11        | 11.22%  |
| Broadcom                        | 6         | 6.12%   |
| MediaTek                        | 4         | 4.08%   |
| TP-Link                         | 3         | 3.06%   |
| NetGear                         | 2         | 2.04%   |
| ASUSTek Computer                | 2         | 2.04%   |
| Ralink                          | 1         | 1.02%   |
| Qualcomm Atheros Communications | 1         | 1.02%   |
| Linksys                         | 1         | 1.02%   |
| Broadcom Limited                | 1         | 1.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 5.1%    |
| Intel Wireless 8265 / 8275                                              | 5         | 5.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 5.1%    |
| Realtek 802.11ac NIC                                                    | 4         | 4.08%   |
| Intel Wireless 3165                                                     | 4         | 4.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 4.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.06%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 3.06%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 3.06%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 3.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.04%   |
| NetGear A6210                                                           | 2         | 2.04%   |
| Intel Wireless 3160                                                     | 2         | 2.04%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 2.04%   |
| Intel Centrino Wireless-N 2200                                          | 2         | 2.04%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 2.04%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 2.04%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 1.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.02%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 1.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.02%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.02%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 1.02%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 1.02%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 1.02%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.02%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.02%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 35        | 50%     |
| Intel                 | 17        | 24.29%  |
| Qualcomm Atheros      | 5         | 7.14%   |
| Broadcom              | 3         | 4.29%   |
| Samsung Electronics   | 2         | 2.86%   |
| Nvidia                | 2         | 2.86%   |
| Apple                 | 2         | 2.86%   |
| MediaTek              | 1         | 1.43%   |
| Huawei Technologies   | 1         | 1.43%   |
| DisplayLink           | 1         | 1.43%   |
| ASIX Electronics      | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 29.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 13.89%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 8.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 2.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.78%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.39%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.39%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.39%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.39%   |
| MediaTek U318AA                                                   | 1         | 1.39%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.39%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.39%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.39%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.39%   |
| Huawei Ideos (tethering mode)                                     | 1         | 1.39%   |
| DisplayLink USB3.0 UHD Dual Video Dock                            | 1         | 1.39%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.39%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.39%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.39%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.39%   |
| Apple iPad 4/Mini1                                                | 1         | 1.39%   |
| Apple iBridge                                                     | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 81        | 54%     |
| Ethernet | 67        | 44.67%  |
| Modem    | 2         | 1.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 65        | 76.47%  |
| Ethernet | 20        | 23.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 58        | 70.73%  |
| 1     | 22        | 26.83%  |
| 3     | 1         | 1.22%   |
| 0     | 1         | 1.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 62        | 74.7%   |
| Yes  | 21        | 25.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 47.14%  |
| Qualcomm Atheros Communications | 7         | 10%     |
| Realtek Semiconductor           | 6         | 8.57%   |
| Broadcom                        | 4         | 5.71%   |
| MediaTek                        | 3         | 4.29%   |
| IMC Networks                    | 3         | 4.29%   |
| Apple                           | 3         | 4.29%   |
| Toshiba                         | 2         | 2.86%   |
| Lite-On Technology              | 2         | 2.86%   |
| Foxconn / Hon Hai               | 2         | 2.86%   |
| Realtek                         | 1         | 1.43%   |
| Ralink                          | 1         | 1.43%   |
| Dell                            | 1         | 1.43%   |
| Cambridge Silicon Radio         | 1         | 1.43%   |
| Alps Electric                   | 1         | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 13        | 18.57%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 10%     |
| Intel AX201 Bluetooth                                                               | 7         | 10%     |
| Realtek Bluetooth Radio                                                             | 5         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 4.29%   |
| MediaTek Wireless_Device                                                            | 3         | 4.29%   |
| Intel AX200 Bluetooth                                                               | 2         | 2.86%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.86%   |
| Apple Bluetooth Host Controller                                                     | 2         | 2.86%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 1.43%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.43%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.43%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.43%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.43%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.43%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.43%   |
| Lite-On Wireless_Device                                                             | 1         | 1.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.43%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.43%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.43%   |
| Intel Bluetooth Device                                                              | 1         | 1.43%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.43%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.43%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.43%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 1.43%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.43%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 1.43%   |
| Broadcom BCM20702A0                                                                 | 1         | 1.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.43%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.43%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.43%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 63        | 66.32%  |
| AMD    | 17        | 17.89%  |
| Nvidia | 14        | 14.74%  |
| Apple  | 1         | 1.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 9.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 9.01%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 8.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 7.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 5.41%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 3.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.7%    |
| AMD FCH Azalia Controller                                                                         | 3         | 2.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.8%    |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 1.8%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 1.8%    |
| Nvidia Audio device                                                                               | 2         | 1.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.8%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.8%    |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.8%    |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.8%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.8%    |
| AMD High Definition Audio Controller                                                              | 2         | 1.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.8%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.9%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.9%    |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.9%    |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.9%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.9%    |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 23.73%  |
| Micron Technology   | 13        | 22.03%  |
| SK hynix            | 9         | 15.25%  |
| Crucial             | 5         | 8.47%   |
| Kingston            | 4         | 6.78%   |
| Unknown (ABCD)      | 3         | 5.08%   |
| Ramaxel Technology  | 3         | 5.08%   |
| Elpida              | 3         | 5.08%   |
| Unknown             | 1         | 1.69%   |
| Transcend           | 1         | 1.69%   |
| Teikon              | 1         | 1.69%   |
| Smart               | 1         | 1.69%   |
| Saikano             | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 4.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.28%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 3.28%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 3.28%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 3.28%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.28%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 3.28%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 3.28%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 3.28%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.64%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 1         | 1.64%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.64%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 1.64%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s             | 1         | 1.64%   |
| Samsung RAM M378B2873CZ0-CF7 1GB SODIMM DDR3 800MT/s             | 1         | 1.64%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.64%   |
| Saikano RAM Memory 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.64%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.64%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.64%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.64%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s               | 1         | 1.64%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 1.64%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 1         | 1.64%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s             | 1         | 1.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 1.64%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Kingston RAM KF3200C20S4/16GX 16GB SODIMM DDR4 3200MT/s          | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 23        | 47.92%  |
| DDR3   | 17        | 35.42%  |
| LPDDR4 | 5         | 10.42%  |
| SDRAM  | 1         | 2.08%   |
| LPDDR3 | 1         | 2.08%   |
| DDR5   | 1         | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 43        | 89.58%  |
| Row Of Chips | 5         | 10.42%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 22        | 42.31%  |
| 8192  | 15        | 28.85%  |
| 16384 | 8         | 15.38%  |
| 2048  | 4         | 7.69%   |
| 1024  | 2         | 3.85%   |
| 32768 | 1         | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 13        | 24.07%  |
| 1600  | 13        | 24.07%  |
| 3200  | 11        | 20.37%  |
| 2400  | 5         | 9.26%   |
| 1334  | 4         | 7.41%   |
| 1333  | 2         | 3.7%    |
| 4800  | 1         | 1.85%   |
| 3266  | 1         | 1.85%   |
| 2048  | 1         | 1.85%   |
| 1867  | 1         | 1.85%   |
| 1067  | 1         | 1.85%   |
| 800   | 1         | 1.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Brother HL-1210W series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 26.32%  |
| IMC Networks                           | 10        | 13.16%  |
| Acer                                   | 8         | 10.53%  |
| Microdia                               | 7         | 9.21%   |
| Apple                                  | 6         | 7.89%   |
| Realtek Semiconductor                  | 4         | 5.26%   |
| Quanta                                 | 4         | 5.26%   |
| Sunplus Innovation Technology          | 3         | 3.95%   |
| Syntek                                 | 2         | 2.63%   |
| Luxvisions Innotech Limited            | 2         | 2.63%   |
| USB Camera                             | 1         | 1.32%   |
| Suyin                                  | 1         | 1.32%   |
| Silicon Motion                         | 1         | 1.32%   |
| Ricoh                                  | 1         | 1.32%   |
| Primax Electronics                     | 1         | 1.32%   |
| Lite-On Technology                     | 1         | 1.32%   |
| Importek                               | 1         | 1.32%   |
| Goertek Electronics                    | 1         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.32%   |
| Alcor Micro                            | 1         | 1.32%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 4         | 5.26%   |
| Chicony HP Truevision HD                             | 3         | 3.95%   |
| Acer HD Webcam                                       | 3         | 3.95%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 2.63%   |
| Quanta HP TrueVision HD Camera                       | 2         | 2.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 2.63%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 2         | 2.63%   |
| IMC Networks Integrated Camera                       | 2         | 2.63%   |
| Chicony USB2.0 Camera                                | 2         | 2.63%   |
| Chicony TOSHIBA Web Camera - HD                      | 2         | 2.63%   |
| Chicony Integrated Camera [ThinkPad]                 | 2         | 2.63%   |
| Chicony HD User Facing                               | 2         | 2.63%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 2         | 2.63%   |
| Apple Built-in iSight                                | 2         | 2.63%   |
| Acer SunplusIT Integrated Camera                     | 2         | 2.63%   |
| USB Camera USB Camera                                | 1         | 1.32%   |
| Syntek Lenovo EasyCamera                             | 1         | 1.32%   |
| Syntek Integrated Camera                             | 1         | 1.32%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 1.32%   |
| Sunplus WEMISS CM-A1                                 | 1         | 1.32%   |
| Silicon Motion WebCam SC-13HDL11939N                 | 1         | 1.32%   |
| Ricoh HD Webcam                                      | 1         | 1.32%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.32%   |
| Realtek Integrated Webcam                            | 1         | 1.32%   |
| Realtek Integrated Camera                            | 1         | 1.32%   |
| Realtek HP Webcam                                    | 1         | 1.32%   |
| Quanta VGA WebCam                                    | 1         | 1.32%   |
| Quanta HD User Facing                                | 1         | 1.32%   |
| Primax HP HD Webcam [Fixed]                          | 1         | 1.32%   |
| Microdia Webcam Vitade AF                            | 1         | 1.32%   |
| Microdia PC Microscope camera                        | 1         | 1.32%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 1.32%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.32%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.32%   |
| Microdia Integrated Webcam                           | 1         | 1.32%   |
| Microdia HP Integrated Webcam                        | 1         | 1.32%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.32%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 1.32%   |
| Lite-On HP HD Camera                                 | 1         | 1.32%   |
| Importek TOSHIBA Web Camera - HD                     | 1         | 1.32%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 35.29%  |
| Synaptics                  | 5         | 29.41%  |
| Shenzhen Goodix Technology | 3         | 17.65%  |
| Upek                       | 1         | 5.88%   |
| Elan Microelectronics      | 1         | 5.88%   |
| AuthenTec                  | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 11.76%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 11.76%  |
| Shenzhen Goodix  Fingerprint Device                       | 2         | 11.76%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 5.88%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 5.88%   |
| Validity Sensors Synaptics WBDI                           | 1         | 5.88%   |
| Validity Sensors Fingerprint scanner                      | 1         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 1         | 5.88%   |
| Synaptics  WBDI                                           | 1         | 5.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 5.88%   |
| Elan ELAN:ARM-M4                                          | 1         | 5.88%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 71.43%  |
| OmniKey     | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 28.57%  |
| OmniKey CardMan Smart@Link                                                   | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 43        | 52.44%  |
| 1     | 33        | 40.24%  |
| 2     | 5         | 6.1%    |
| 3     | 1         | 1.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 17        | 39.53%  |
| Net/wireless          | 9         | 20.93%  |
| Graphics card         | 6         | 13.95%  |
| Chipcard              | 6         | 13.95%  |
| Multimedia controller | 2         | 4.65%   |
| Storage               | 1         | 2.33%   |
| Network               | 1         | 2.33%   |
| Bluetooth             | 1         | 2.33%   |

