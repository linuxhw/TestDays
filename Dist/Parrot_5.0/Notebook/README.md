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
| Lenovo    | IdeaPad 3 15IIL05 81WE      | [7615eb5b46](https://linux-hardware.org/?probe=7615eb5b46) | Jul 20, 2022 |
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
| Lenovo    | IdeaPad 3 15IIL05 81WE      | [39351344b4](https://linux-hardware.org/?probe=39351344b4) | Jun 14, 2022 |
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
| 5.16.0-12parrot1-amd64 | 32        | 39.02%  |
| 5.14.0-9parrot1-amd64  | 27        | 32.93%  |
| 5.18.0-1parrot1-amd64  | 13        | 15.85%  |
| 5.14.0-2parrot1-amd64  | 6         | 7.32%   |
| 5.15.0-15parrot1-amd64 | 3         | 3.66%   |
| 5.15.0-5parrot1-amd64  | 1         | 1.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16.0  | 32        | 39.51%  |
| 5.14.0  | 32        | 39.51%  |
| 5.18.0  | 13        | 16.05%  |
| 5.15.0  | 4         | 4.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 32        | 39.51%  |
| 5.14    | 32        | 39.51%  |
| 5.18    | 13        | 16.05%  |
| 5.15    | 4         | 4.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 80        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 53        | 65.43%  |
| KDE5    | 24        | 29.63%  |
| Unknown | 2         | 2.47%   |
| XFCE    | 1         | 1.23%   |
| KDE     | 1         | 1.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 77        | 96.25%  |
| Tty     | 2         | 2.5%    |
| Wayland | 1         | 1.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 47        | 58.75%  |
| Unknown | 32        | 40%     |
| SDDM    | 1         | 1.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 42        | 52.5%   |
| en_GB | 8         | 10%     |
| es_ES | 5         | 6.25%   |
| fr_FR | 3         | 3.75%   |
| en_IN | 3         | 3.75%   |
| ru_RU | 2         | 2.5%    |
| pt_BR | 2         | 2.5%    |
| pl_PL | 2         | 2.5%    |
| en_AU | 2         | 2.5%    |
| de_DE | 2         | 2.5%    |
| pt_PT | 1         | 1.25%   |
| it_IT | 1         | 1.25%   |
| fi_FI | 1         | 1.25%   |
| es_PE | 1         | 1.25%   |
| es_MX | 1         | 1.25%   |
| es_AR | 1         | 1.25%   |
| en_ZA | 1         | 1.25%   |
| en_CA | 1         | 1.25%   |
| cs_CZ | 1         | 1.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 50        | 61.73%  |
| EFI  | 31        | 38.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 70        | 87.5%   |
| Ext4    | 7         | 8.75%   |
| Overlay | 3         | 3.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 38        | 46.91%  |
| GPT     | 30        | 37.04%  |
| MBR     | 13        | 16.05%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 71        | 87.65%  |
| Yes       | 10        | 12.35%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 67.07%  |
| Yes       | 27        | 32.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 17        | 21.25%  |
| Hewlett-Packard     | 15        | 18.75%  |
| Dell                | 13        | 16.25%  |
| ASUSTek Computer    | 6         | 7.5%    |
| MSI                 | 5         | 6.25%   |
| Acer                | 5         | 6.25%   |
| Apple               | 4         | 5%      |
| Toshiba             | 3         | 3.75%   |
| HUAWEI              | 2         | 2.5%    |
| Sony                | 1         | 1.25%   |
| Samsung Electronics | 1         | 1.25%   |
| Razer               | 1         | 1.25%   |
| Panasonic           | 1         | 1.25%   |
| Metabox             | 1         | 1.25%   |
| Jumper              | 1         | 1.25%   |
| Fujitsu             | 1         | 1.25%   |
| Chuwi               | 1         | 1.25%   |
| Alienware           | 1         | 1.25%   |
| Unknown             | 1         | 1.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 3.75%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 2         | 2.5%    |
| HP Notebook                                        | 2         | 2.5%    |
| Dell Latitude E6410                                | 2         | 2.5%    |
| Toshiba Satellite-L845                             | 1         | 1.25%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 1.25%   |
| Toshiba Satellite C75D-B                           | 1         | 1.25%   |
| Sony VPCSB1C5E                                     | 1         | 1.25%   |
| Samsung 550P5C/550P7C                              | 1         | 1.25%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 1.25%   |
| Panasonic CF-31JBGNNDM                             | 1         | 1.25%   |
| MSI GE62 6QE                                       | 1         | 1.25%   |
| MSI Creator Z16 Hiroshi F A11UE                    | 1         | 1.25%   |
| Metabox Edge-Pro NS50MU                            | 1         | 1.25%   |
| Lenovo Z40-70 80E6                                 | 1         | 1.25%   |
| Lenovo V330-15IKB 81AX                             | 1         | 1.25%   |
| Lenovo ThinkPad X230 2325N66                       | 1         | 1.25%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS        | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW           | 1         | 1.25%   |
| Lenovo ThinkPad T480 20L6SCYP00                    | 1         | 1.25%   |
| Lenovo ThinkPad T470p 20J7S0CF00                   | 1         | 1.25%   |
| Lenovo ThinkPad T420 4180MNU                       | 1         | 1.25%   |
| Lenovo ThinkPad L430 2465C32                       | 1         | 1.25%   |
| Lenovo ThinkPad E14 20RA0016GE                     | 1         | 1.25%   |
| Lenovo Legion 5 15ACH6 82JW                        | 1         | 1.25%   |
| Lenovo IdeaPad Y580                                | 1         | 1.25%   |
| Lenovo IdeaPad L340-17API 81LY                     | 1         | 1.25%   |
| Lenovo IdeaPad 320S-14IKB 80X4                     | 1         | 1.25%   |
| Lenovo B50-80 80EW                                 | 1         | 1.25%   |
| Jumper EZbook                                      | 1         | 1.25%   |
| HUAWEI HVY-WXX9                                    | 1         | 1.25%   |
| HUAWEI BOHK-WAX9X                                  | 1         | 1.25%   |
| HP ZBook Firefly 14 G7 Mobile Workstation          | 1         | 1.25%   |
| HP ProBook 4535s                                   | 1         | 1.25%   |
| HP ProBook 440 G5                                  | 1         | 1.25%   |
| HP Pavilion Laptop 14-ec0xxx                       | 1         | 1.25%   |
| HP Pavilion g7                                     | 1         | 1.25%   |
| HP Pavilion dv6                                    | 1         | 1.25%   |
| HP Laptop 15q-dy0xxx                               | 1         | 1.25%   |
| HP Laptop 15-dy2xxx                                | 1         | 1.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 8         | 10%     |
| Dell Latitude          | 8         | 10%     |
| Lenovo IdeaPad         | 5         | 6.25%   |
| Dell Inspiron          | 5         | 6.25%   |
| MSI Modern             | 3         | 3.75%   |
| HP Pavilion            | 3         | 3.75%   |
| HP Laptop              | 3         | 3.75%   |
| HP EliteBook           | 3         | 3.75%   |
| Toshiba Satellite      | 2         | 2.5%    |
| HP ProBook             | 2         | 2.5%    |
| HP Notebook            | 2         | 2.5%    |
| Acer Nitro             | 2         | 2.5%    |
| Toshiba Satellite-L845 | 1         | 1.25%   |
| Sony VPCSB1C5E         | 1         | 1.25%   |
| Samsung 550P5C         | 1         | 1.25%   |
| Razer Blade            | 1         | 1.25%   |
| Panasonic CF-31JBGNNDM | 1         | 1.25%   |
| MSI GE62               | 1         | 1.25%   |
| MSI Creator            | 1         | 1.25%   |
| Metabox Edge-Pro       | 1         | 1.25%   |
| Lenovo Z40-70          | 1         | 1.25%   |
| Lenovo V330-15IKB      | 1         | 1.25%   |
| Lenovo Legion          | 1         | 1.25%   |
| Lenovo B50-80          | 1         | 1.25%   |
| Jumper EZbook          | 1         | 1.25%   |
| HUAWEI HVY-WXX9        | 1         | 1.25%   |
| HUAWEI BOHK-WAX9X      | 1         | 1.25%   |
| HP ZBook               | 1         | 1.25%   |
| HP 250                 | 1         | 1.25%   |
| Fujitsu LIFEBOOK       | 1         | 1.25%   |
| Chuwi GemiBook         | 1         | 1.25%   |
| ASUS X75VC             | 1         | 1.25%   |
| ASUS X540SAA           | 1         | 1.25%   |
| ASUS VivoBook          | 1         | 1.25%   |
| ASUS TUF               | 1         | 1.25%   |
| ASUS ROG               | 1         | 1.25%   |
| ASUS ASUS              | 1         | 1.25%   |
| Apple MacBookPro5      | 1         | 1.25%   |
| Apple MacBookPro15     | 1         | 1.25%   |
| Apple MacBookAir3      | 1         | 1.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 11        | 13.75%  |
| 2020 | 10        | 12.5%   |
| 2012 | 9         | 11.25%  |
| 2017 | 8         | 10%     |
| 2011 | 8         | 10%     |
| 2019 | 6         | 7.5%    |
| 2018 | 6         | 7.5%    |
| 2016 | 5         | 6.25%   |
| 2014 | 4         | 5%      |
| 2010 | 4         | 5%      |
| 2013 | 3         | 3.75%   |
| 2022 | 1         | 1.25%   |
| 2015 | 1         | 1.25%   |
| 2009 | 1         | 1.25%   |
| 2008 | 1         | 1.25%   |
| 2007 | 1         | 1.25%   |
| 2006 | 1         | 1.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 80        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 80        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 80        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 25        | 31.25%  |
| 16.01-24.0  | 13        | 16.25%  |
| 8.01-16.0   | 13        | 16.25%  |
| 3.01-4.0    | 12        | 15%     |
| 32.01-64.0  | 11        | 13.75%  |
| 64.01-256.0 | 3         | 3.75%   |
| 24.01-32.0  | 2         | 2.5%    |
| 1.01-2.0    | 1         | 1.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 30        | 37.04%  |
| 1.01-2.0  | 28        | 34.57%  |
| 4.01-8.0  | 13        | 16.05%  |
| 3.01-4.0  | 6         | 7.41%   |
| 8.01-16.0 | 2         | 2.47%   |
| 0.51-1.0  | 2         | 2.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 51        | 63.75%  |
| 2      | 27        | 33.75%  |
| 3      | 1         | 1.25%   |
| 0      | 1         | 1.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 67.5%   |
| Yes       | 26        | 32.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 80.25%  |
| No        | 16        | 19.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 98.75%  |
| No        | 1         | 1.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 83.75%  |
| No        | 13        | 16.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 28        | 34.57%  |
| UK           | 5         | 6.17%   |
| Spain        | 5         | 6.17%   |
| Germany      | 4         | 4.94%   |
| India        | 3         | 3.7%    |
| Brazil       | 3         | 3.7%    |
| South Africa | 2         | 2.47%   |
| Russia       | 2         | 2.47%   |
| Mexico       | 2         | 2.47%   |
| Italy        | 2         | 2.47%   |
| France       | 2         | 2.47%   |
| Denmark      | 2         | 2.47%   |
| Canada       | 2         | 2.47%   |
| Australia    | 2         | 2.47%   |
| Switzerland  | 1         | 1.23%   |
| Sweden       | 1         | 1.23%   |
| Puerto Rico  | 1         | 1.23%   |
| Portugal     | 1         | 1.23%   |
| Peru         | 1         | 1.23%   |
| Netherlands  | 1         | 1.23%   |
| Nepal        | 1         | 1.23%   |
| Morocco      | 1         | 1.23%   |
| Kenya        | 1         | 1.23%   |
| Georgia      | 1         | 1.23%   |
| Finland      | 1         | 1.23%   |
| Czechia      | 1         | 1.23%   |
| Bulgaria     | 1         | 1.23%   |
| Benin        | 1         | 1.23%   |
| Austria      | 1         | 1.23%   |
| Argentina    | 1         | 1.23%   |
| Algeria      | 1         | 1.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Seattle                | 3         | 3.61%   |
| Ruskin                 | 2         | 2.41%   |
| Dublin                 | 2         | 2.41%   |
| Camden                 | 2         | 2.41%   |
| Zurich                 | 1         | 1.2%    |
| Villa Carlos Paz       | 1         | 1.2%    |
| Vienna                 | 1         | 1.2%    |
| Ts'khinvali            | 1         | 1.2%    |
| Trivandrum             | 1         | 1.2%    |
| Tangier                | 1         | 1.2%    |
| Tampere                | 1         | 1.2%    |
| Sydney                 | 1         | 1.2%    |
| Sumaré                | 1         | 1.2%    |
| St Petersburg          | 1         | 1.2%    |
| Spotsylvania           | 1         | 1.2%    |
| South Hamilton         | 1         | 1.2%    |
| Skive                  | 1         | 1.2%    |
| Sao Bernardo do Campo  | 1         | 1.2%    |
| San Juan               | 1         | 1.2%    |
| Saint Paul             | 1         | 1.2%    |
| Rho                    | 1         | 1.2%    |
| Pretoria               | 1         | 1.2%    |
| Prague                 | 1         | 1.2%    |
| Plovdiv                | 1         | 1.2%    |
| Phoenix                | 1         | 1.2%    |
| Orofino                | 1         | 1.2%    |
| Opelousas              | 1         | 1.2%    |
| Nairobi                | 1         | 1.2%    |
| Mt. Pleasant           | 1         | 1.2%    |
| Mostoles               | 1         | 1.2%    |
| Moscow                 | 1         | 1.2%    |
| Montigny-le-Bretonneux | 1         | 1.2%    |
| Melbourne              | 1         | 1.2%    |
| Mazatlán              | 1         | 1.2%    |
| Mata de Sao Joao       | 1         | 1.2%    |
| Mangalagiri            | 1         | 1.2%    |
| Madrid                 | 1         | 1.2%    |
| Lynwood                | 1         | 1.2%    |
| Los Angeles            | 1         | 1.2%    |
| London                 | 1         | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 18     | 16%     |
| Toshiba             | 12        | 13     | 12%     |
| WDC                 | 9         | 10     | 9%      |
| Seagate             | 7         | 7      | 7%      |
| Kingston            | 7         | 7      | 7%      |
| Unknown             | 5         | 7      | 5%      |
| Hitachi             | 5         | 6      | 5%      |
| SanDisk             | 4         | 5      | 4%      |
| China               | 4         | 4      | 4%      |
| Micron Technology   | 3         | 3      | 3%      |
| Intel               | 3         | 6      | 3%      |
| SK hynix            | 2         | 2      | 2%      |
| HGST                | 2         | 2      | 2%      |
| Crucial             | 2         | 2      | 2%      |
| Apple               | 2         | 2      | 2%      |
| YMTC                | 1         | 1      | 1%      |
| Team                | 1         | 1      | 1%      |
| S3+                 | 1         | 1      | 1%      |
| RZX                 | 1         | 1      | 1%      |
| PNY                 | 1         | 1      | 1%      |
| Phison              | 1         | 1      | 1%      |
| Netac               | 1         | 1      | 1%      |
| LITEON              | 1         | 1      | 1%      |
| KingSpec            | 1         | 1      | 1%      |
| KingFast            | 1         | 2      | 1%      |
| Intenso             | 1         | 2      | 1%      |
| HUAWEI              | 1         | 1      | 1%      |
| BR                  | 1         | 1      | 1%      |
| BHT                 | 1         | 1      | 1%      |
| ASMT                | 1         | 1      | 1%      |
| ASMedia             | 1         | 1      | 1%      |
| A-DATA Technology   | 1         | 1      | 1%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                | 5         | 4.63%   |
| Kingston NVMe SSD Drive 512GB         | 3         | 2.78%   |
| Unknown MMC Card  32GB                | 2         | 1.85%   |
| Toshiba MQ01ABD075 752GB              | 2         | 1.85%   |
| SanDisk NVMe SSD Drive 1TB            | 2         | 1.85%   |
| Samsung NVMe SSD Drive 1024GB         | 2         | 1.85%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 1.85%   |
| YMTC PC005 512GB                      | 1         | 0.93%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 1         | 0.93%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 0.93%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 0.93%   |
| WDC WDBNCE2500PNC 250GB SSD           | 1         | 0.93%   |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 0.93%   |
| WDC WD5000LPCX-60VHAT1 500GB          | 1         | 0.93%   |
| WDC WD3200BPVT-00JJ5T0 320GB          | 1         | 0.93%   |
| WDC WD10SPZX-75Z10T2 1TB              | 1         | 0.93%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.93%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB    | 1         | 0.93%   |
| Unknown SE32G  32GB                   | 1         | 0.93%   |
| Unknown SD/MMC/MS PRO 2GB             | 1         | 0.93%   |
| Unknown SD  128GB                     | 1         | 0.93%   |
| Unknown ISOCOM  64GB                  | 1         | 0.93%   |
| Toshiba MQ01ACF050 500GB              | 1         | 0.93%   |
| Toshiba MQ01ABF050 500GB              | 1         | 0.93%   |
| Toshiba MQ01ABD100 1TB                | 1         | 0.93%   |
| Toshiba MK2555GSXF 250GB              | 1         | 0.93%   |
| Toshiba MK2533GSGF 250GB              | 1         | 0.93%   |
| Team TM8PS7512G 512GB SSD             | 1         | 0.93%   |
| SK hynix NVMe SSD Drive 1024GB        | 1         | 0.93%   |
| SK hynix HFS128G32TNF-N3A0A 128GB SSD | 1         | 0.93%   |
| Seagate ST9250315AS 250GB             | 1         | 0.93%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 0.93%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 0.93%   |
| Seagate ST320LM001 HN-M320MBB 320GB   | 1         | 0.93%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 1         | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 0.93%   |
| Seagate BUP Slim BK 500GB             | 1         | 0.93%   |
| SanDisk SDSSDH3 2T00 2TB              | 1         | 0.93%   |
| SanDisk NVMe SSD Drive 256GB          | 1         | 0.93%   |
| SanDisk NVMe SSD Drive 1024GB         | 1         | 0.93%   |

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
| Samsung Electronics | 5         | 5      | 14.71%  |
| WDC                 | 4         | 4      | 11.76%  |
| China               | 4         | 4      | 11.76%  |
| Kingston            | 3         | 3      | 8.82%   |
| Crucial             | 2         | 2      | 5.88%   |
| Team                | 1         | 1      | 2.94%   |
| SK hynix            | 1         | 1      | 2.94%   |
| SanDisk             | 1         | 1      | 2.94%   |
| S3+                 | 1         | 1      | 2.94%   |
| RZX                 | 1         | 1      | 2.94%   |
| PNY                 | 1         | 1      | 2.94%   |
| Netac               | 1         | 1      | 2.94%   |
| Micron Technology   | 1         | 1      | 2.94%   |
| LITEON              | 1         | 1      | 2.94%   |
| KingSpec            | 1         | 1      | 2.94%   |
| KingFast            | 1         | 1      | 2.94%   |
| Intenso             | 1         | 2      | 2.94%   |
| BR                  | 1         | 1      | 2.94%   |
| BHT                 | 1         | 1      | 2.94%   |
| ASMT                | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 32        | 35     | 33.33%  |
| HDD     | 31        | 36     | 32.29%  |
| NVMe    | 27        | 35     | 28.13%  |
| MMC     | 4         | 5      | 4.17%   |
| Unknown | 2         | 2      | 2.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 67     | 60.87%  |
| NVMe | 27        | 35     | 29.35%  |
| SAS  | 5         | 6      | 5.43%   |
| MMC  | 4         | 5      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 41        | 48     | 65.08%  |
| 0.51-1.0   | 20        | 21     | 31.75%  |
| 1.01-2.0   | 2         | 2      | 3.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 21        | 25.93%  |
| 501-1000   | 16        | 19.75%  |
| 251-500    | 13        | 16.05%  |
| 1001-2000  | 12        | 14.81%  |
| Unknown    | 12        | 14.81%  |
| 1-20       | 3         | 3.7%    |
| 2001-3000  | 2         | 2.47%   |
| 21-50      | 1         | 1.23%   |
| 51-100     | 1         | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 28        | 34.57%  |
| 51-100   | 14        | 17.28%  |
| Unknown  | 12        | 14.81%  |
| 1-20     | 10        | 12.35%  |
| 251-500  | 8         | 9.88%   |
| 101-250  | 6         | 7.41%   |
| 501-1000 | 3         | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-00JJ5T0 320GB        | 1         | 1      | 20%     |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 20%     |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 20%     |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 20%     |
| Intel HBRPEKNX0202AHO 32GB          | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |
| Intel   | 1         | 1      | 20%     |

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
| HDD  | 4         | 4      | 80%     |
| NVMe | 1         | 1      | 20%     |

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
| Works    | 42        | 50     | 47.73%  |
| Detected | 41        | 58     | 46.59%  |
| Malfunc  | 5         | 5      | 5.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 56        | 58.95%  |
| Samsung Electronics         | 12        | 12.63%  |
| AMD                         | 9         | 9.47%   |
| SanDisk                     | 4         | 4.21%   |
| Kingston Technology Company | 4         | 4.21%   |
| Nvidia                      | 3         | 3.16%   |
| Micron Technology           | 2         | 2.11%   |
| Yangtze Memory Technologies | 1         | 1.05%   |
| SK hynix                    | 1         | 1.05%   |
| Phison Electronics          | 1         | 1.05%   |
| Apple                       | 1         | 1.05%   |
| ADATA Technology            | 1         | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 9         | 8.33%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 9         | 8.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 8         | 7.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 7         | 6.48%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 5         | 4.63%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 5         | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 4.63%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 3.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 3.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 3         | 2.78%   |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 2.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 2.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 1.85%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 1.85%   |
| Micron Non-Volatile memory controller                                                  | 2         | 1.85%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 1.85%   |
| Yangtze Memory Non-Volatile memory controller                                          | 1         | 0.93%   |
| SK hynix Gold P31 SSD                                                                  | 1         | 0.93%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.93%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 0.93%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.93%   |
| Phison E12 NVMe Controller                                                             | 1         | 0.93%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.93%   |
| Nvidia MCP89 SATA Controller                                                           | 1         | 0.93%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 0.93%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 0.93%   |
| Intel SSD 660P Series                                                                  | 1         | 0.93%   |
| Intel SSD 600P Series                                                                  | 1         | 0.93%   |
| Intel Non-Volatile memory controller                                                   | 1         | 0.93%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.93%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                                   | 1         | 0.93%   |
| Intel Comet Lake PCH-H RAID                                                            | 1         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 44        | 45.83%  |
| NVMe | 27        | 28.13%  |
| RAID | 14        | 14.58%  |
| IDE  | 11        | 11.46%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 81.25%  |
| AMD    | 15        | 18.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 3.75%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 3.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 2.5%    |
| Intel Core i5-2430M CPU @ 2.40GHz       | 2         | 2.5%    |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 2         | 2.5%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 2         | 2.5%    |
| Intel Celeron J4125 CPU @ 2.00GHz       | 2         | 2.5%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 2         | 2.5%    |
| AMD Ryzen 7 5800H with Radeon Graphics  | 2         | 2.5%    |
| Intel Pentium CPU N3530 @ 2.16GHz       | 1         | 1.25%   |
| Intel Pentium CPU 4415U @ 2.30GHz       | 1         | 1.25%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 1         | 1.25%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 1.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.25%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 1.25%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 1.25%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.25%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 1.25%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.25%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 1.25%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 1         | 1.25%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 1.25%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 1.25%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 1.25%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 1.25%   |
| Intel Core i7-10850H CPU @ 2.70GHz      | 1         | 1.25%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.25%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 1         | 1.25%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.25%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 1         | 1.25%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 1.25%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.25%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.25%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.25%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.25%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.25%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 1         | 1.25%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 1         | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 20        | 25%     |
| Intel Core i5    | 19        | 23.75%  |
| Intel Core i3    | 7         | 8.75%   |
| AMD Ryzen 7      | 7         | 8.75%   |
| Other            | 6         | 7.5%    |
| Intel Celeron    | 6         | 7.5%    |
| Intel Core 2 Duo | 5         | 6.25%   |
| AMD Ryzen 5      | 3         | 3.75%   |
| Intel Pentium    | 2         | 2.5%    |
| AMD A6           | 2         | 2.5%    |
| Intel Core 2     | 1         | 1.25%   |
| AMD E2           | 1         | 1.25%   |
| AMD A4           | 1         | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 40        | 50%     |
| 4      | 26        | 32.5%   |
| 8      | 8         | 10%     |
| 6      | 5         | 6.25%   |
| 14     | 1         | 1.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 80        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 61        | 76.25%  |
| 1      | 19        | 23.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 80        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 46.91%  |
| 0x806e9    | 5         | 6.17%   |
| 0x206a7    | 5         | 6.17%   |
| 0x306a9    | 4         | 4.94%   |
| 0xa0652    | 2         | 2.47%   |
| 0x806ec    | 2         | 2.47%   |
| 0x706e5    | 2         | 2.47%   |
| 0x706a8    | 2         | 2.47%   |
| 0x406e3    | 2         | 2.47%   |
| 0x1067a    | 2         | 2.47%   |
| 0x07030105 | 2         | 2.47%   |
| 0x906ed    | 1         | 1.23%   |
| 0x906ea    | 1         | 1.23%   |
| 0x906e9    | 1         | 1.23%   |
| 0x906a3    | 1         | 1.23%   |
| 0x806eb    | 1         | 1.23%   |
| 0x806ea    | 1         | 1.23%   |
| 0x806d1    | 1         | 1.23%   |
| 0x806c1    | 1         | 1.23%   |
| 0x6f6      | 1         | 1.23%   |
| 0x506c9    | 1         | 1.23%   |
| 0x40651    | 1         | 1.23%   |
| 0x306c3    | 1         | 1.23%   |
| 0x08600106 | 1         | 1.23%   |
| 0x08108109 | 1         | 1.23%   |
| 0x03000027 | 1         | 1.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 18        | 22.5%   |
| SandyBridge      | 10        | 12.5%   |
| IvyBridge        | 7         | 8.75%   |
| Penryn           | 5         | 6.25%   |
| Unknown          | 5         | 6.25%   |
| Skylake          | 3         | 3.75%   |
| IceLake          | 3         | 3.75%   |
| Goldmont plus    | 3         | 3.75%   |
| Zen+             | 2         | 2.5%    |
| Zen 3            | 2         | 2.5%    |
| Zen 2            | 2         | 2.5%    |
| Westmere         | 2         | 2.5%    |
| TigerLake        | 2         | 2.5%    |
| Silvermont       | 2         | 2.5%    |
| Puma             | 2         | 2.5%    |
| Haswell          | 2         | 2.5%    |
| Excavator        | 2         | 2.5%    |
| CometLake        | 2         | 2.5%    |
| Broadwell        | 2         | 2.5%    |
| K10 Llano        | 1         | 1.25%   |
| Goldmont         | 1         | 1.25%   |
| Core             | 1         | 1.25%   |
| Alderlake Hybrid | 1         | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 59        | 55.14%  |
| Nvidia | 24        | 22.43%  |
| AMD    | 24        | 22.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 10        | 9.09%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 5.45%   |
| Intel UHD Graphics 620                                                    | 4         | 3.64%   |
| Intel HD Graphics 620                                                     | 4         | 3.64%   |
| AMD Lucienne                                                              | 4         | 3.64%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 2.73%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 2.73%   |
| Nvidia MCP89 [GeForce 320M]                                               | 2         | 1.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 1.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.82%   |
| Intel HD Graphics 5500                                                    | 2         | 1.82%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 1.82%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 2         | 1.82%   |
| AMD Renoir                                                                | 2         | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.82%   |
| AMD Cezanne                                                               | 2         | 1.82%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.91%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.91%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.91%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.91%   |
| Nvidia GP108GLM [Quadro P520]                                             | 1         | 0.91%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.91%   |
| Nvidia GM206M [GeForce GTX 965M]                                          | 1         | 0.91%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.91%   |
| Nvidia GM108M [GeForce 930MX]                                             | 1         | 0.91%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.91%   |
| Nvidia GK107M [GeForce GTX 660M]                                          | 1         | 0.91%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.91%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                      | 1         | 0.91%   |
| Nvidia GF108M [GeForce GT 620M]                                           | 1         | 0.91%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                               | 1         | 0.91%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.91%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 43.75%  |
| Intel + Nvidia | 18        | 22.5%   |
| 1 x AMD        | 14        | 17.5%   |
| Intel + AMD    | 6         | 7.5%    |
| AMD + Nvidia   | 3         | 3.75%   |
| 1 x Nvidia     | 2         | 2.5%    |
| 2 x Nvidia     | 1         | 1.25%   |
| 2 x AMD        | 1         | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 73        | 91.25%  |
| Proprietary | 6         | 7.5%    |
| Unknown     | 1         | 1.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 80%     |
| 1.01-2.0   | 6         | 7.5%    |
| 0.01-0.5   | 5         | 6.25%   |
| 3.01-4.0   | 3         | 3.75%   |
| 0.51-1.0   | 2         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 22        | 25.58%  |
| BOE                     | 18        | 20.93%  |
| LG Display              | 11        | 12.79%  |
| Chimei Innolux          | 10        | 11.63%  |
| Samsung Electronics     | 7         | 8.14%   |
| Apple                   | 4         | 4.65%   |
| Chi Mei Optoelectronics | 3         | 3.49%   |
| Lenovo                  | 2         | 2.33%   |
| Unknown (AAA)           | 1         | 1.16%   |
| PANDA                   | 1         | 1.16%   |
| ONN                     | 1         | 1.16%   |
| NEC Computers           | 1         | 1.16%   |
| Kogan                   | 1         | 1.16%   |
| InfoVision              | 1         | 1.16%   |
| Goldstar                | 1         | 1.16%   |
| CSO                     | 1         | 1.16%   |
| AOC                     | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 3         | 3.49%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch                 | 1         | 1.16%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch      | 1         | 1.16%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch        | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 480x270mm 21.7-inch    | 1         | 1.16%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                  | 1         | 1.16%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                      | 1         | 1.16%   |
| NEC Computers EA243WM NEC6863 1920x1200 519x324mm 24.1-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD045A 1366x768 293x165mm 13.2-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD0292 1366x768 309x174mm 14.0-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD0257 1440x900 304x190mm 14.1-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch             | 1         | 1.16%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch               | 1         | 1.16%   |
| Lenovo D27-30 LEN66B8 1920x1080 597x336mm 27.0-inch                      | 1         | 1.16%   |
| Kogan KAMN27F7TA KGN0270 1920x1080 600x330mm 27.0-inch                   | 1         | 1.16%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch             | 1         | 1.16%   |
| Goldstar SIGNAGE GSM0002 3840x2160 1215x686mm 54.9-inch                  | 1         | 1.16%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 1.16%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1736 1600x900 382x214mm 17.2-inch          | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1526 1920x1080 344x193mm 15.5-inch         | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch          | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch          | 1         | 1.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 1         | 1.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 31        | 38.75%  |
| 1366x768 (WXGA)    | 29        | 36.25%  |
| 1600x900 (HD+)     | 6         | 7.5%    |
| 1280x800 (WXGA)    | 4         | 5%      |
| 3840x2160 (4K)     | 2         | 2.5%    |
| 2560x1600          | 2         | 2.5%    |
| 1440x900 (WXGA+)   | 2         | 2.5%    |
| 2880x1800          | 1         | 1.25%   |
| 2160x1440          | 1         | 1.25%   |
| 1920x1200 (WUXGA)  | 1         | 1.25%   |
| 1680x1050 (WSXGA+) | 1         | 1.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 35        | 41.18%  |
| 14     | 15        | 17.65%  |
| 13     | 9         | 10.59%  |
| 17     | 7         | 8.24%   |
| 24     | 3         | 3.53%   |
| 16     | 3         | 3.53%   |
| 12     | 3         | 3.53%   |
| 27     | 2         | 2.35%   |
| 11     | 2         | 2.35%   |
| 54     | 1         | 1.18%   |
| 48     | 1         | 1.18%   |
| 40     | 1         | 1.18%   |
| 31     | 1         | 1.18%   |
| 23     | 1         | 1.18%   |
| 21     | 1         | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 58        | 68.24%  |
| 351-400     | 9         | 10.59%  |
| 201-300     | 7         | 8.24%   |
| 501-600     | 6         | 7.06%   |
| 1001-1500   | 2         | 2.35%   |
| 801-900     | 1         | 1.18%   |
| 601-700     | 1         | 1.18%   |
| 401-500     | 1         | 1.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 65        | 84.42%  |
| 16/10 | 11        | 14.29%  |
| 3/2   | 1         | 1.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 42.35%  |
| 81-90          | 22        | 25.88%  |
| 121-130        | 6         | 7.06%   |
| 61-70          | 3         | 3.53%   |
| 201-250        | 3         | 3.53%   |
| More than 1000 | 2         | 2.35%   |
| 71-80          | 2         | 2.35%   |
| 51-60          | 2         | 2.35%   |
| 301-350        | 2         | 2.35%   |
| 251-300        | 2         | 2.35%   |
| 111-120        | 2         | 2.35%   |
| 351-500        | 1         | 1.18%   |
| 131-140        | 1         | 1.18%   |
| 501-1000       | 1         | 1.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 34        | 40%     |
| 101-120       | 33        | 38.82%  |
| 51-100        | 11        | 12.94%  |
| 161-240       | 4         | 4.71%   |
| 1-50          | 2         | 2.35%   |
| More than 240 | 1         | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 69        | 85.19%  |
| 2     | 10        | 12.35%  |
| 3     | 1         | 1.23%   |
| 0     | 1         | 1.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 44        | 32.35%  |
| Intel                           | 44        | 32.35%  |
| Qualcomm Atheros                | 15        | 11.03%  |
| Broadcom                        | 8         | 5.88%   |
| MediaTek                        | 5         | 3.68%   |
| TP-Link                         | 3         | 2.21%   |
| Samsung Electronics             | 2         | 1.47%   |
| Nvidia                          | 2         | 1.47%   |
| NetGear                         | 2         | 1.47%   |
| Huawei Technologies             | 2         | 1.47%   |
| ASUSTek Computer                | 2         | 1.47%   |
| Apple                           | 2         | 1.47%   |
| Ralink                          | 1         | 0.74%   |
| Qualcomm Atheros Communications | 1         | 0.74%   |
| Linksys                         | 1         | 0.74%   |
| Broadcom Limited                | 1         | 0.74%   |
| ASIX Electronics                | 1         | 0.74%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 12.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 6.06%   |
| Realtek 802.11ac NIC                                              | 5         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 3.03%   |
| Intel Wireless 8265 / 8275                                        | 5         | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 3.03%   |
| Intel Wireless 3165                                               | 4         | 2.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.82%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 3         | 1.82%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.82%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.21%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.21%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.21%   |
| NetGear A6210                                                     | 2         | 1.21%   |
| Intel Wireless 3160                                               | 2         | 1.21%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.21%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.21%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.21%   |
| Intel Centrino Wireless-N 2200                                    | 2         | 1.21%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.21%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.21%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 2         | 1.21%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.61%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1         | 0.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 45.26%  |
| Realtek Semiconductor           | 20        | 21.05%  |
| Qualcomm Atheros                | 11        | 11.58%  |
| Broadcom                        | 6         | 6.32%   |
| MediaTek                        | 4         | 4.21%   |
| TP-Link                         | 3         | 3.16%   |
| NetGear                         | 2         | 2.11%   |
| ASUSTek Computer                | 2         | 2.11%   |
| Ralink                          | 1         | 1.05%   |
| Qualcomm Atheros Communications | 1         | 1.05%   |
| Linksys                         | 1         | 1.05%   |
| Broadcom Limited                | 1         | 1.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek 802.11ac NIC                                                    | 5         | 5.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 5.26%   |
| Intel Wireless 8265 / 8275                                              | 5         | 5.26%   |
| Intel Wireless 3165                                                     | 4         | 4.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 4.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.16%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 3.16%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 3.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 3.16%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 3.16%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 2.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.11%   |
| NetGear A6210                                                           | 2         | 2.11%   |
| Intel Wireless 3160                                                     | 2         | 2.11%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 2.11%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 2.11%   |
| Intel Centrino Wireless-N 2200                                          | 2         | 2.11%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 2.11%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 2.11%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 1.05%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.05%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 1.05%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.05%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 1.05%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.05%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.05%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 1.05%   |
| Intel Wireless 8260                                                     | 1         | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 34        | 50.75%  |
| Intel                 | 16        | 23.88%  |
| Qualcomm Atheros      | 5         | 7.46%   |
| Broadcom              | 3         | 4.48%   |
| Samsung Electronics   | 2         | 2.99%   |
| Nvidia                | 2         | 2.99%   |
| Apple                 | 2         | 2.99%   |
| MediaTek              | 1         | 1.49%   |
| Huawei Technologies   | 1         | 1.49%   |
| ASIX Electronics      | 1         | 1.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 28.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 14.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 7.25%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 2.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.9%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.9%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.45%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.45%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.45%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.45%   |
| MediaTek Nokia 5.1 Plus                                           | 1         | 1.45%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.45%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.45%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.45%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.45%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.45%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.45%   |
| Huawei Ideos (tethering mode)                                     | 1         | 1.45%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.45%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.45%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.45%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.45%   |
| Apple iPad 4/Mini1                                                | 1         | 1.45%   |
| Apple iBridge                                                     | 1         | 1.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 54.86%  |
| Ethernet | 64        | 44.44%  |
| Modem    | 1         | 0.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 75.9%   |
| Ethernet | 20        | 24.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 56        | 70%     |
| 1     | 22        | 27.5%   |
| 3     | 1         | 1.25%   |
| 0     | 1         | 1.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 60        | 74.07%  |
| Yes  | 21        | 25.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 47.06%  |
| Qualcomm Atheros Communications | 7         | 10.29%  |
| Realtek Semiconductor           | 6         | 8.82%   |
| MediaTek                        | 3         | 4.41%   |
| IMC Networks                    | 3         | 4.41%   |
| Broadcom                        | 3         | 4.41%   |
| Apple                           | 3         | 4.41%   |
| Toshiba                         | 2         | 2.94%   |
| Lite-On Technology              | 2         | 2.94%   |
| Foxconn / Hon Hai               | 2         | 2.94%   |
| Realtek                         | 1         | 1.47%   |
| Ralink                          | 1         | 1.47%   |
| Dell                            | 1         | 1.47%   |
| Cambridge Silicon Radio         | 1         | 1.47%   |
| Alps Electric                   | 1         | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 13        | 19.12%  |
| Intel AX201 Bluetooth                                                               | 7         | 10.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 8.82%   |
| Realtek Bluetooth Radio                                                             | 5         | 7.35%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 4.41%   |
| MediaTek Wireless_Device                                                            | 3         | 4.41%   |
| Intel AX200 Bluetooth                                                               | 2         | 2.94%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.94%   |
| Apple Bluetooth Host Controller                                                     | 2         | 2.94%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 1.47%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.47%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.47%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.47%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.47%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.47%   |
| Lite-On Wireless_Device                                                             | 1         | 1.47%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.47%   |
| Intel Bluetooth Device                                                              | 1         | 1.47%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.47%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.47%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.47%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 1.47%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.47%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 1.47%   |
| Broadcom BCM20702A0                                                                 | 1         | 1.47%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.47%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.47%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 61        | 65.59%  |
| AMD    | 17        | 18.28%  |
| Nvidia | 14        | 15.05%  |
| Apple  | 1         | 1.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 10.09%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 8.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 8.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 7.34%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 5.5%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 2.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.75%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.83%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 1.83%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 1.83%   |
| Nvidia Audio device                                                                               | 2         | 1.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.83%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.83%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.83%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.83%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.83%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.83%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.92%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.92%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.92%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.92%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.92%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.92%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 24.56%  |
| Micron Technology   | 12        | 21.05%  |
| SK hynix            | 9         | 15.79%  |
| Crucial             | 5         | 8.77%   |
| Kingston            | 4         | 7.02%   |
| Unknown (ABCD)      | 3         | 5.26%   |
| Ramaxel Technology  | 3         | 5.26%   |
| Elpida              | 3         | 5.26%   |
| Unknown             | 1         | 1.75%   |
| Teikon              | 1         | 1.75%   |
| Smart               | 1         | 1.75%   |
| Saikano             | 1         | 1.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 3         | 5.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.39%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 3.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 3.39%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 3.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.39%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 3.39%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 3.39%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.69%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.69%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.69%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.69%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 1.69%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 1.69%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.69%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.69%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.69%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.69%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 1         | 1.69%   |
| Samsung RAM M378B2873CZ0-CF7 1GB SODIMM DDR3 800MT/s             | 1         | 1.69%   |
| Samsung RAM K4EBE304EB-EGCF 8192MB Row Of Chips LPDDR3 1867MT/s  | 1         | 1.69%   |
| Saikano RAM Memory 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.69%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.69%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.69%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.69%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s               | 1         | 1.69%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 1.69%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 1         | 1.69%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s             | 1         | 1.69%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 1.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 1         | 1.69%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.69%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.69%   |
| Kingston RAM KF3200C20S4/16GX 16384MB SODIMM DDR4 3200MT/s       | 1         | 1.69%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s             | 1         | 1.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 22        | 47.83%  |
| DDR3   | 16        | 34.78%  |
| LPDDR4 | 5         | 10.87%  |
| SDRAM  | 1         | 2.17%   |
| LPDDR3 | 1         | 2.17%   |
| DDR5   | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 89.13%  |
| Row Of Chips | 5         | 10.87%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 23        | 46%     |
| 8192  | 12        | 24%     |
| 16384 | 8         | 16%     |
| 2048  | 4         | 8%      |
| 1024  | 2         | 4%      |
| 32768 | 1         | 2%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 13        | 25%     |
| 2667  | 12        | 23.08%  |
| 3200  | 11        | 21.15%  |
| 2400  | 5         | 9.62%   |
| 1334  | 3         | 5.77%   |
| 1333  | 2         | 3.85%   |
| 4800  | 1         | 1.92%   |
| 3266  | 1         | 1.92%   |
| 2048  | 1         | 1.92%   |
| 1867  | 1         | 1.92%   |
| 1067  | 1         | 1.92%   |
| 800   | 1         | 1.92%   |

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
| Chicony Electronics                    | 19        | 25.68%  |
| IMC Networks                           | 9         | 12.16%  |
| Acer                                   | 8         | 10.81%  |
| Microdia                               | 7         | 9.46%   |
| Apple                                  | 6         | 8.11%   |
| Realtek Semiconductor                  | 4         | 5.41%   |
| Quanta                                 | 4         | 5.41%   |
| Sunplus Innovation Technology          | 3         | 4.05%   |
| Syntek                                 | 2         | 2.7%    |
| Luxvisions Innotech Limited            | 2         | 2.7%    |
| Suyin                                  | 1         | 1.35%   |
| Silicon Motion                         | 1         | 1.35%   |
| Ricoh                                  | 1         | 1.35%   |
| Primax Electronics                     | 1         | 1.35%   |
| Lite-On Technology                     | 1         | 1.35%   |
| Importek                               | 1         | 1.35%   |
| icSpring                               | 1         | 1.35%   |
| Goertek Electronics                    | 1         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.35%   |
| Alcor Micro                            | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony integrated camera                            | 3         | 4.05%   |
| Chicony HP Truevision HD                             | 3         | 4.05%   |
| Acer HD Webcam                                       | 3         | 4.05%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 2.7%    |
| Quanta HP TrueVision HD Camera                       | 2         | 2.7%    |
| IMC Networks USB2.0 HD UVC WebCam                    | 2         | 2.7%    |
| IMC Networks Integrated Camera                       | 2         | 2.7%    |
| Chicony USB2.0 Camera                                | 2         | 2.7%    |
| Chicony TOSHIBA Web Camera - HD                      | 2         | 2.7%    |
| Chicony Integrated Camera [ThinkPad]                 | 2         | 2.7%    |
| Chicony HD User Facing                               | 2         | 2.7%    |
| Apple iPhone5/5C/5S/6                                | 2         | 2.7%    |
| Apple Built-in iSight                                | 2         | 2.7%    |
| Acer SunplusIT Integrated Camera                     | 2         | 2.7%    |
| Syntek Lenovo EasyCamera                             | 1         | 1.35%   |
| Syntek Integrated Camera                             | 1         | 1.35%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 1.35%   |
| Sunplus HK 1080P K20Pro                              | 1         | 1.35%   |
| Silicon Motion WebCam SC-13HDL11939N                 | 1         | 1.35%   |
| Ricoh HD Webcam                                      | 1         | 1.35%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.35%   |
| Realtek Integrated Webcam                            | 1         | 1.35%   |
| Realtek Integrated Camera                            | 1         | 1.35%   |
| Realtek HP Webcam                                    | 1         | 1.35%   |
| Quanta VGA WebCam                                    | 1         | 1.35%   |
| Quanta HD User Facing                                | 1         | 1.35%   |
| Primax HP HD Webcam [Fixed]                          | 1         | 1.35%   |
| Microdia Webcam Vitade AF                            | 1         | 1.35%   |
| Microdia PC Microscope camera                        | 1         | 1.35%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 1.35%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.35%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.35%   |
| Microdia Integrated Webcam                           | 1         | 1.35%   |
| Microdia HP Integrated Webcam                        | 1         | 1.35%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.35%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 1.35%   |
| Lite-On HP HD Camera                                 | 1         | 1.35%   |
| Importek TOSHIBA Web Camera - HD                     | 1         | 1.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 1.35%   |
| IMC Networks USB Camera                              | 1         | 1.35%   |

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
| 0     | 42        | 52.5%   |
| 1     | 32        | 40%     |
| 2     | 5         | 6.25%   |
| 3     | 1         | 1.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 17        | 40.48%  |
| Net/wireless          | 9         | 21.43%  |
| Chipcard              | 6         | 14.29%  |
| Graphics card         | 5         | 11.9%   |
| Multimedia controller | 2         | 4.76%   |
| Storage               | 1         | 2.38%   |
| Network               | 1         | 2.38%   |
| Bluetooth             | 1         | 2.38%   |

