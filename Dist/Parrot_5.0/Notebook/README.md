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

Total: 107

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.16.0-12parrot1-amd64 | 31        | 39.24%  |
| 5.14.0-9parrot1-amd64  | 27        | 34.18%  |
| 5.18.0-1parrot1-amd64  | 11        | 13.92%  |
| 5.14.0-2parrot1-amd64  | 6         | 7.59%   |
| 5.15.0-15parrot1-amd64 | 3         | 3.8%    |
| 5.15.0-5parrot1-amd64  | 1         | 1.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 32        | 41.03%  |
| 5.16.0  | 31        | 39.74%  |
| 5.18.0  | 11        | 14.1%   |
| 5.15.0  | 4         | 5.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 32        | 41.03%  |
| 5.16    | 31        | 39.74%  |
| 5.18    | 11        | 14.1%   |
| 5.15    | 4         | 5.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 77        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 51        | 66.23%  |
| KDE5    | 22        | 28.57%  |
| Unknown | 2         | 2.6%    |
| XFCE    | 1         | 1.3%    |
| KDE     | 1         | 1.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 74        | 96.1%   |
| Tty     | 2         | 2.6%    |
| Wayland | 1         | 1.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 45        | 58.44%  |
| Unknown | 31        | 40.26%  |
| SDDM    | 1         | 1.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 39        | 50.65%  |
| en_GB | 8         | 10.39%  |
| es_ES | 5         | 6.49%   |
| fr_FR | 3         | 3.9%    |
| en_IN | 3         | 3.9%    |
| ru_RU | 2         | 2.6%    |
| pt_BR | 2         | 2.6%    |
| pl_PL | 2         | 2.6%    |
| en_AU | 2         | 2.6%    |
| de_DE | 2         | 2.6%    |
| pt_PT | 1         | 1.3%    |
| it_IT | 1         | 1.3%    |
| fi_FI | 1         | 1.3%    |
| es_PE | 1         | 1.3%    |
| es_MX | 1         | 1.3%    |
| es_AR | 1         | 1.3%    |
| en_ZA | 1         | 1.3%    |
| en_CA | 1         | 1.3%    |
| cs_CZ | 1         | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 47        | 61.04%  |
| EFI  | 30        | 38.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 67        | 87.01%  |
| Ext4    | 7         | 9.09%   |
| Overlay | 3         | 3.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 36        | 46.75%  |
| GPT     | 29        | 37.66%  |
| MBR     | 12        | 15.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 67        | 87.01%  |
| Yes       | 10        | 12.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 66.67%  |
| Yes       | 26        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 16        | 20.78%  |
| Hewlett-Packard     | 14        | 18.18%  |
| Dell                | 13        | 16.88%  |
| ASUSTek Computer    | 6         | 7.79%   |
| MSI                 | 5         | 6.49%   |
| Acer                | 5         | 6.49%   |
| Apple               | 4         | 5.19%   |
| Toshiba             | 3         | 3.9%    |
| HUAWEI              | 2         | 2.6%    |
| Sony                | 1         | 1.3%    |
| Samsung Electronics | 1         | 1.3%    |
| Razer               | 1         | 1.3%    |
| Metabox             | 1         | 1.3%    |
| Jumper              | 1         | 1.3%    |
| Fujitsu             | 1         | 1.3%    |
| Chuwi               | 1         | 1.3%    |
| Alienware           | 1         | 1.3%    |
| Unknown             | 1         | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 3.9%    |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 2         | 2.6%    |
| HP Notebook                                        | 2         | 2.6%    |
| Dell Latitude E6410                                | 2         | 2.6%    |
| Toshiba Satellite-L845                             | 1         | 1.3%    |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 1.3%    |
| Toshiba Satellite C75D-B                           | 1         | 1.3%    |
| Sony VPCSB1C5E                                     | 1         | 1.3%    |
| Samsung 550P5C/550P7C                              | 1         | 1.3%    |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 1.3%    |
| MSI GE62 6QE                                       | 1         | 1.3%    |
| MSI Creator Z16 Hiroshi F A11UE                    | 1         | 1.3%    |
| Metabox Edge-Pro NS50MU                            | 1         | 1.3%    |
| Lenovo Z40-70 80E6                                 | 1         | 1.3%    |
| Lenovo V330-15IKB 81AX                             | 1         | 1.3%    |
| Lenovo ThinkPad X230 2325N66                       | 1         | 1.3%    |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS        | 1         | 1.3%    |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW           | 1         | 1.3%    |
| Lenovo ThinkPad T480 20L6SCYP00                    | 1         | 1.3%    |
| Lenovo ThinkPad T470p 20J7S0CF00                   | 1         | 1.3%    |
| Lenovo ThinkPad L430 2465C32                       | 1         | 1.3%    |
| Lenovo ThinkPad E14 20RA0016GE                     | 1         | 1.3%    |
| Lenovo Legion 5 15ACH6 82JW                        | 1         | 1.3%    |
| Lenovo IdeaPad Y580                                | 1         | 1.3%    |
| Lenovo IdeaPad L340-17API 81LY                     | 1         | 1.3%    |
| Lenovo IdeaPad 320S-14IKB 80X4                     | 1         | 1.3%    |
| Lenovo B50-80 80EW                                 | 1         | 1.3%    |
| Jumper EZbook                                      | 1         | 1.3%    |
| HUAWEI HVY-WXX9                                    | 1         | 1.3%    |
| HUAWEI BOHK-WAX9X                                  | 1         | 1.3%    |
| HP ZBook Firefly 14 G7 Mobile Workstation          | 1         | 1.3%    |
| HP ProBook 4535s                                   | 1         | 1.3%    |
| HP ProBook 440 G5                                  | 1         | 1.3%    |
| HP Pavilion Laptop 14-ec0xxx                       | 1         | 1.3%    |
| HP Pavilion g7                                     | 1         | 1.3%    |
| HP Pavilion dv6                                    | 1         | 1.3%    |
| HP Laptop 15q-dy0xxx                               | 1         | 1.3%    |
| HP Laptop 15-dy2xxx                                | 1         | 1.3%    |
| HP Laptop 15-bs2xx                                 | 1         | 1.3%    |
| HP EliteBook 8470p                                 | 1         | 1.3%    |
| HP EliteBook 840 G3                                | 1         | 1.3%    |
| HP 250 G2                                          | 1         | 1.3%    |
| Fujitsu LIFEBOOK AH532/G21                         | 1         | 1.3%    |
| Dell Latitude XT2                                  | 1         | 1.3%    |
| Dell Latitude E7450                                | 1         | 1.3%    |
| Dell Latitude E6540                                | 1         | 1.3%    |
| Dell Latitude E6420                                | 1         | 1.3%    |
| Dell Latitude 7480                                 | 1         | 1.3%    |
| Dell Latitude 5400                                 | 1         | 1.3%    |
| Dell Inspiron N5110                                | 1         | 1.3%    |
| Dell Inspiron MM061                                | 1         | 1.3%    |
| Dell Inspiron 5580                                 | 1         | 1.3%    |
| Dell Inspiron 5570                                 | 1         | 1.3%    |
| Dell Inspiron 15-3567                              | 1         | 1.3%    |
| Chuwi GemiBook                                     | 1         | 1.3%    |
| ASUS X75VC                                         | 1         | 1.3%    |
| ASUS X540SAA                                       | 1         | 1.3%    |
| ASUS VivoBook 15_ASUS Laptop X540UAR               | 1         | 1.3%    |
| ASUS TUF Gaming FX504GD_FX80GD                     | 1         | 1.3%    |
| ASUS ROG Strix G733ZX_G733ZX                       | 1         | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell Latitude          | 8         | 10.39%  |
| Lenovo ThinkPad        | 7         | 9.09%   |
| Lenovo IdeaPad         | 5         | 6.49%   |
| Dell Inspiron          | 5         | 6.49%   |
| MSI Modern             | 3         | 3.9%    |
| HP Pavilion            | 3         | 3.9%    |
| HP Laptop              | 3         | 3.9%    |
| Toshiba Satellite      | 2         | 2.6%    |
| HP ProBook             | 2         | 2.6%    |
| HP Notebook            | 2         | 2.6%    |
| HP EliteBook           | 2         | 2.6%    |
| Acer Nitro             | 2         | 2.6%    |
| Toshiba Satellite-L845 | 1         | 1.3%    |
| Sony VPCSB1C5E         | 1         | 1.3%    |
| Samsung 550P5C         | 1         | 1.3%    |
| Razer Blade            | 1         | 1.3%    |
| MSI GE62               | 1         | 1.3%    |
| MSI Creator            | 1         | 1.3%    |
| Metabox Edge-Pro       | 1         | 1.3%    |
| Lenovo Z40-70          | 1         | 1.3%    |
| Lenovo V330-15IKB      | 1         | 1.3%    |
| Lenovo Legion          | 1         | 1.3%    |
| Lenovo B50-80          | 1         | 1.3%    |
| Jumper EZbook          | 1         | 1.3%    |
| HUAWEI HVY-WXX9        | 1         | 1.3%    |
| HUAWEI BOHK-WAX9X      | 1         | 1.3%    |
| HP ZBook               | 1         | 1.3%    |
| HP 250                 | 1         | 1.3%    |
| Fujitsu LIFEBOOK       | 1         | 1.3%    |
| Chuwi GemiBook         | 1         | 1.3%    |
| ASUS X75VC             | 1         | 1.3%    |
| ASUS X540SAA           | 1         | 1.3%    |
| ASUS VivoBook          | 1         | 1.3%    |
| ASUS TUF               | 1         | 1.3%    |
| ASUS ROG               | 1         | 1.3%    |
| ASUS ASUS              | 1         | 1.3%    |
| Apple MacBookPro5      | 1         | 1.3%    |
| Apple MacBookPro15     | 1         | 1.3%    |
| Apple MacBookAir3      | 1         | 1.3%    |
| Apple MacBook7         | 1         | 1.3%    |
| Alienware M14xR1       | 1         | 1.3%    |
| Acer TravelMate        | 1         | 1.3%    |
| Acer Predator          | 1         | 1.3%    |
| Acer Aspire            | 1         | 1.3%    |
| Unknown                | 1         | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 11        | 14.29%  |
| 2020 | 9         | 11.69%  |
| 2012 | 9         | 11.69%  |
| 2017 | 8         | 10.39%  |
| 2019 | 6         | 7.79%   |
| 2018 | 6         | 7.79%   |
| 2011 | 6         | 7.79%   |
| 2016 | 5         | 6.49%   |
| 2014 | 4         | 5.19%   |
| 2010 | 4         | 5.19%   |
| 2013 | 3         | 3.9%    |
| 2022 | 1         | 1.3%    |
| 2015 | 1         | 1.3%    |
| 2009 | 1         | 1.3%    |
| 2008 | 1         | 1.3%    |
| 2007 | 1         | 1.3%    |
| 2006 | 1         | 1.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 77        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 77        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 24        | 31.17%  |
| 8.01-16.0   | 13        | 16.88%  |
| 3.01-4.0    | 12        | 15.58%  |
| 32.01-64.0  | 11        | 14.29%  |
| 16.01-24.0  | 11        | 14.29%  |
| 64.01-256.0 | 3         | 3.9%    |
| 24.01-32.0  | 2         | 2.6%    |
| 1.01-2.0    | 1         | 1.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 28        | 35.9%   |
| 1.01-2.0  | 27        | 34.62%  |
| 4.01-8.0  | 13        | 16.67%  |
| 3.01-4.0  | 6         | 7.69%   |
| 8.01-16.0 | 2         | 2.56%   |
| 0.51-1.0  | 2         | 2.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 49        | 63.64%  |
| 2      | 26        | 33.77%  |
| 3      | 1         | 1.3%    |
| 0      | 1         | 1.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 67.53%  |
| Yes       | 25        | 32.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 80.77%  |
| No        | 15        | 19.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 98.7%   |
| No        | 1         | 1.3%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 83.12%  |
| No        | 13        | 16.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 26        | 33.33%  |
| UK           | 5         | 6.41%   |
| Spain        | 5         | 6.41%   |
| Germany      | 4         | 5.13%   |
| India        | 3         | 3.85%   |
| Brazil       | 3         | 3.85%   |
| South Africa | 2         | 2.56%   |
| Russia       | 2         | 2.56%   |
| Mexico       | 2         | 2.56%   |
| Italy        | 2         | 2.56%   |
| France       | 2         | 2.56%   |
| Denmark      | 2         | 2.56%   |
| Canada       | 2         | 2.56%   |
| Australia    | 2         | 2.56%   |
| Sweden       | 1         | 1.28%   |
| Puerto Rico  | 1         | 1.28%   |
| Portugal     | 1         | 1.28%   |
| Peru         | 1         | 1.28%   |
| Netherlands  | 1         | 1.28%   |
| Nepal        | 1         | 1.28%   |
| Morocco      | 1         | 1.28%   |
| Kenya        | 1         | 1.28%   |
| Georgia      | 1         | 1.28%   |
| Finland      | 1         | 1.28%   |
| Czechia      | 1         | 1.28%   |
| Bulgaria     | 1         | 1.28%   |
| Benin        | 1         | 1.28%   |
| Austria      | 1         | 1.28%   |
| Argentina    | 1         | 1.28%   |
| Algeria      | 1         | 1.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Seattle                | 3         | 3.8%    |
| Ruskin                 | 2         | 2.53%   |
| Camden                 | 2         | 2.53%   |
| Villa Carlos Paz       | 1         | 1.27%   |
| Vienna                 | 1         | 1.27%   |
| Ts'khinvali            | 1         | 1.27%   |
| Trivandrum             | 1         | 1.27%   |
| Tangier                | 1         | 1.27%   |
| Tampere                | 1         | 1.27%   |
| Sydney                 | 1         | 1.27%   |
| Sumaré                | 1         | 1.27%   |
| St Petersburg          | 1         | 1.27%   |
| Spotsylvania           | 1         | 1.27%   |
| South Hamilton         | 1         | 1.27%   |
| Skive                  | 1         | 1.27%   |
| Sao Bernardo do Campo  | 1         | 1.27%   |
| San Juan               | 1         | 1.27%   |
| Saint Paul             | 1         | 1.27%   |
| Rho                    | 1         | 1.27%   |
| Pretoria               | 1         | 1.27%   |
| Prague                 | 1         | 1.27%   |
| Plovdiv                | 1         | 1.27%   |
| Phoenix                | 1         | 1.27%   |
| Orofino                | 1         | 1.27%   |
| Opelousas              | 1         | 1.27%   |
| Nairobi                | 1         | 1.27%   |
| Mt. Pleasant           | 1         | 1.27%   |
| Mostoles               | 1         | 1.27%   |
| Moscow                 | 1         | 1.27%   |
| Montigny-le-Bretonneux | 1         | 1.27%   |
| Melbourne              | 1         | 1.27%   |
| Mazatlán              | 1         | 1.27%   |
| Mata de Sao Joao       | 1         | 1.27%   |
| Mangalagiri            | 1         | 1.27%   |
| Madrid                 | 1         | 1.27%   |
| Lynwood                | 1         | 1.27%   |
| Los Angeles            | 1         | 1.27%   |
| London                 | 1         | 1.27%   |
| Lisbon                 | 1         | 1.27%   |
| Leduc                  | 1         | 1.27%   |
| La Magdalena           | 1         | 1.27%   |
| Kelowna                | 1         | 1.27%   |
| Islington              | 1         | 1.27%   |
| Houston                | 1         | 1.27%   |
| Herne                  | 1         | 1.27%   |
| Haßfurt               | 1         | 1.27%   |
| Gothenburg             | 1         | 1.27%   |
| Garden City            | 1         | 1.27%   |
| Eugene                 | 1         | 1.27%   |
| Esplugues de Llobregat | 1         | 1.27%   |
| East China Township    | 1         | 1.27%   |
| Durban                 | 1         | 1.27%   |
| Dublin                 | 1         | 1.27%   |
| Dresden                | 1         | 1.27%   |
| Dillon                 | 1         | 1.27%   |
| Dickson                | 1         | 1.27%   |
| Cotonou                | 1         | 1.27%   |
| Copenhagen             | 1         | 1.27%   |
| Compton                | 1         | 1.27%   |
| City of Saint Peters   | 1         | 1.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 17     | 15.46%  |
| Toshiba             | 11        | 12     | 11.34%  |
| WDC                 | 9         | 10     | 9.28%   |
| Seagate             | 7         | 7      | 7.22%   |
| Kingston            | 7         | 7      | 7.22%   |
| Unknown             | 5         | 7      | 5.15%   |
| Hitachi             | 5         | 6      | 5.15%   |
| SanDisk             | 4         | 5      | 4.12%   |
| China               | 4         | 4      | 4.12%   |
| Micron Technology   | 3         | 3      | 3.09%   |
| SK hynix            | 2         | 2      | 2.06%   |
| Intel               | 2         | 3      | 2.06%   |
| HGST                | 2         | 2      | 2.06%   |
| Crucial             | 2         | 2      | 2.06%   |
| Apple               | 2         | 2      | 2.06%   |
| YMTC                | 1         | 1      | 1.03%   |
| Team                | 1         | 1      | 1.03%   |
| S3+                 | 1         | 1      | 1.03%   |
| RZX                 | 1         | 1      | 1.03%   |
| PNY                 | 1         | 1      | 1.03%   |
| Phison              | 1         | 1      | 1.03%   |
| Netac               | 1         | 1      | 1.03%   |
| LITEON              | 1         | 1      | 1.03%   |
| KingSpec            | 1         | 1      | 1.03%   |
| KingFast            | 1         | 2      | 1.03%   |
| Intenso             | 1         | 2      | 1.03%   |
| HUAWEI              | 1         | 1      | 1.03%   |
| BR                  | 1         | 1      | 1.03%   |
| BHT                 | 1         | 1      | 1.03%   |
| ASMT                | 1         | 1      | 1.03%   |
| ASMedia             | 1         | 1      | 1.03%   |
| A-DATA Technology   | 1         | 1      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                       | 5         | 4.81%   |
| Kingston NVMe SSD Drive 512GB                | 3         | 2.88%   |
| Unknown MMC Card  32GB                       | 2         | 1.92%   |
| Toshiba MQ01ABD075 752GB                     | 2         | 1.92%   |
| SanDisk NVMe SSD Drive 1TB                   | 2         | 1.92%   |
| Samsung NVMe SSD Drive 1024GB                | 2         | 1.92%   |
| Kingston SV300S37A120G 120GB SSD             | 2         | 1.92%   |
| YMTC PC005 512GB                             | 1         | 0.96%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 0.96%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 0.96%   |
| WDC WDS120G2G0A-00JH30 120GB SSD             | 1         | 0.96%   |
| WDC WDBNCE2500PNC 250GB SSD                  | 1         | 0.96%   |
| WDC WD6400BPVT-75HXZT1 640GB                 | 1         | 0.96%   |
| WDC WD5000LPCX-60VHAT1 500GB                 | 1         | 0.96%   |
| WDC WD3200BPVT-00JJ5T0 320GB                 | 1         | 0.96%   |
| WDC WD10SPZX-75Z10T2 1TB                     | 1         | 0.96%   |
| WDC WD10SPZX-24Z10 1TB                       | 1         | 0.96%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB           | 1         | 0.96%   |
| Unknown SE32G  32GB                          | 1         | 0.96%   |
| Unknown SD/MMC/MS PRO 64GB                   | 1         | 0.96%   |
| Unknown SD  128GB                            | 1         | 0.96%   |
| Unknown ISOCOM  64GB                         | 1         | 0.96%   |
| Toshiba MQ01ACF050 500GB                     | 1         | 0.96%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 0.96%   |
| Toshiba MK2555GSXF 250GB                     | 1         | 0.96%   |
| Toshiba MK2533GSGF 250GB                     | 1         | 0.96%   |
| Team TM8PS7512G 512GB SSD                    | 1         | 0.96%   |
| SK hynix NVMe SSD Drive 1024GB               | 1         | 0.96%   |
| SK hynix HFS128G32TNF-N3A0A 128GB SSD        | 1         | 0.96%   |
| Seagate ST9250315AS 250GB                    | 1         | 0.96%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 0.96%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 0.96%   |
| Seagate ST320LM001 HN-M320MBB 320GB          | 1         | 0.96%   |
| Seagate ST2000LM003 HN-M201RAD 2TB           | 1         | 0.96%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 0.96%   |
| Seagate BUP Slim BK 1TB                      | 1         | 0.96%   |
| SanDisk SDSSDH3 2T00 2TB                     | 1         | 0.96%   |
| SanDisk NVMe SSD Drive 256GB                 | 1         | 0.96%   |
| SanDisk NVMe SSD Drive 1024GB                | 1         | 0.96%   |
| Samsung SSD 980 1TB                          | 1         | 0.96%   |
| Samsung SSD 970 EVO Plus 1TB                 | 1         | 0.96%   |
| Samsung SSD 850 EVO 250GB                    | 1         | 0.96%   |
| Samsung NVMe SSD Drive 500GB                 | 1         | 0.96%   |
| Samsung NVMe SSD Drive 256GB                 | 1         | 0.96%   |
| Samsung MZVLB512HBJQ-000H1 512GB             | 1         | 0.96%   |
| Samsung MZVLB512HAJQ-000L7 512GB             | 1         | 0.96%   |
| Samsung MZVLB512HAJQ-00000 512GB             | 1         | 0.96%   |
| Samsung MZVLB256HAHQ-00000 256GB             | 1         | 0.96%   |
| Samsung MZVLB1T0HBLR-000L7 1TB               | 1         | 0.96%   |
| Samsung MZVL22T0HBLB-00B00 2TB               | 1         | 0.96%   |
| Samsung MZNLN256HMHQ-000H1 256GB SSD         | 1         | 0.96%   |
| Samsung MZMPC032HBCD-000L1 32GB SSD          | 1         | 0.96%   |
| Samsung MZALQ128HBHQ-000L2 128GB             | 1         | 0.96%   |
| Samsung MZ7LN256HAJQ-000L2 256GB SSD         | 1         | 0.96%   |
| S3+ S3SSDC480 480GB                          | 1         | 0.96%   |
| RZX 19SSD6G/480G 480GB                       | 1         | 0.96%   |
| PNY CS900 240GB SSD                          | 1         | 0.96%   |
| Phison Metabox Performance 2TB PCIe NVME SSD | 1         | 0.96%   |
| Netac S535N8/256 256GB                       | 1         | 0.96%   |
| Micron MTFDHBA512QFD-1AX1AABHA 512GB         | 1         | 0.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 11        | 12     | 34.38%  |
| Seagate | 7         | 7      | 21.88%  |
| WDC     | 5         | 5      | 15.63%  |
| Hitachi | 5         | 6      | 15.63%  |
| HGST    | 2         | 2      | 6.25%   |
| Unknown | 1         | 2      | 3.13%   |
| ASMedia | 1         | 1      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 12.12%  |
| Samsung Electronics | 4         | 4      | 12.12%  |
| China               | 4         | 4      | 12.12%  |
| Kingston            | 3         | 3      | 9.09%   |
| Crucial             | 2         | 2      | 6.06%   |
| Team                | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 1      | 3.03%   |
| SanDisk             | 1         | 1      | 3.03%   |
| S3+                 | 1         | 1      | 3.03%   |
| RZX                 | 1         | 1      | 3.03%   |
| PNY                 | 1         | 1      | 3.03%   |
| Netac               | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| LITEON              | 1         | 1      | 3.03%   |
| KingSpec            | 1         | 1      | 3.03%   |
| KingFast            | 1         | 1      | 3.03%   |
| Intenso             | 1         | 2      | 3.03%   |
| BR                  | 1         | 1      | 3.03%   |
| BHT                 | 1         | 1      | 3.03%   |
| ASMT                | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 31        | 34     | 33.33%  |
| HDD     | 30        | 35     | 32.26%  |
| NVMe    | 26        | 32     | 27.96%  |
| MMC     | 4         | 5      | 4.3%    |
| Unknown | 2         | 2      | 2.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 54        | 65     | 60.67%  |
| NVMe | 26        | 32     | 29.21%  |
| SAS  | 5         | 6      | 5.62%   |
| MMC  | 4         | 5      | 4.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 43     | 60.66%  |
| 0.51-1.0   | 21        | 23     | 34.43%  |
| 1.01-2.0   | 3         | 3      | 4.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 21        | 26.92%  |
| 501-1000   | 15        | 19.23%  |
| 1001-2000  | 12        | 15.38%  |
| Unknown    | 12        | 15.38%  |
| 251-500    | 11        | 14.1%   |
| 1-20       | 3         | 3.85%   |
| 2001-3000  | 2         | 2.56%   |
| 21-50      | 1         | 1.28%   |
| 51-100     | 1         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 26        | 33.33%  |
| 51-100   | 13        | 16.67%  |
| Unknown  | 12        | 15.38%  |
| 1-20     | 10        | 12.82%  |
| 251-500  | 8         | 10.26%  |
| 101-250  | 6         | 7.69%   |
| 501-1000 | 3         | 3.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-00JJ5T0 320GB        | 1         | 1      | 25%     |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 25%     |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 25%     |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Toshiba | 1         | 1      | 25%     |

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
| HDD  | 4         | 4      | 100%    |

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
| Detected | 40        | 56     | 47.62%  |
| Works    | 40        | 48     | 47.62%  |
| Malfunc  | 4         | 4      | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 53        | 57.61%  |
| Samsung Electronics         | 12        | 13.04%  |
| AMD                         | 9         | 9.78%   |
| SanDisk                     | 4         | 4.35%   |
| Kingston Technology Company | 4         | 4.35%   |
| Nvidia                      | 3         | 3.26%   |
| Micron Technology           | 2         | 2.17%   |
| Yangtze Memory Technologies | 1         | 1.09%   |
| SK hynix                    | 1         | 1.09%   |
| Phison Electronics          | 1         | 1.09%   |
| Apple                       | 1         | 1.09%   |
| ADATA Technology            | 1         | 1.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 8.82%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 8.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 7.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 6.86%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 5         | 4.9%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 5         | 4.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 4.9%    |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 3.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 3.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 2.94%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 2.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 2.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.96%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.96%   |
| Micron Non-Volatile memory controller                                            | 2         | 1.96%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.96%   |
| Yangtze Memory Non-Volatile memory controller                                    | 1         | 0.98%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.98%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.98%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.98%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.98%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.98%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.98%   |
| Nvidia MCP89 SATA Controller                                                     | 1         | 0.98%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.98%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 0.98%   |
| Intel SSD 660P Series                                                            | 1         | 0.98%   |
| Intel SSD 600P Series                                                            | 1         | 0.98%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.98%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.98%   |
| Intel Comet Lake PCH-H RAID                                                      | 1         | 0.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.98%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.98%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.98%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.98%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.98%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 0.98%   |
| Apple ANS2 NVMe Controller                                                       | 1         | 0.98%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 0.98%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 44        | 47.83%  |
| NVMe | 26        | 28.26%  |
| RAID | 13        | 14.13%  |
| IDE  | 9         | 9.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 80.52%  |
| AMD    | 15        | 19.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 3.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.6%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 2.6%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 2.6%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 2.6%    |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 2.6%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 2.6%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 2.6%    |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 1.3%    |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 1.3%    |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 1.3%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.3%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.3%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 1.3%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.3%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.3%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.3%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 1.3%    |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 1.3%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.3%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.3%    |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.3%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.3%    |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 1.3%    |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 1.3%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.3%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.3%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.3%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.3%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.3%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.3%    |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.3%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.3%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.3%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.3%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.3%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.3%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1.3%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.3%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.3%    |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.3%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.3%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.3%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.3%    |
| Intel Core i3-2348M CPU @ 2.30GHz             | 1         | 1.3%    |
| Intel Core 2 Duo CPU U9600 @ 1.60GHz          | 1         | 1.3%    |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz          | 1         | 1.3%    |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 1         | 1.3%    |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 1.3%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 1.3%    |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 1.3%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 1.3%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.3%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.3%    |
| Intel Celeron CPU B830 @ 1.80GHz              | 1         | 1.3%    |
| Intel 12th Gen Core i9-12900H                 | 1         | 1.3%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.3%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 1.3%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 19        | 24.68%  |
| Intel Core i5    | 17        | 22.08%  |
| Intel Core i3    | 7         | 9.09%   |
| AMD Ryzen 7      | 7         | 9.09%   |
| Other            | 6         | 7.79%   |
| Intel Celeron    | 6         | 7.79%   |
| Intel Core 2 Duo | 5         | 6.49%   |
| AMD Ryzen 5      | 3         | 3.9%    |
| Intel Pentium    | 2         | 2.6%    |
| AMD A6           | 2         | 2.6%    |
| Intel Core 2     | 1         | 1.3%    |
| AMD E2           | 1         | 1.3%    |
| AMD A4           | 1         | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 38        | 49.35%  |
| 4      | 25        | 32.47%  |
| 8      | 8         | 10.39%  |
| 6      | 5         | 6.49%   |
| 14     | 1         | 1.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 77        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 58        | 75.32%  |
| 1      | 19        | 24.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 77        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 46.75%  |
| 0x806e9    | 5         | 6.49%   |
| 0x306a9    | 4         | 5.19%   |
| 0x206a7    | 4         | 5.19%   |
| 0xa0652    | 2         | 2.6%    |
| 0x706e5    | 2         | 2.6%    |
| 0x706a8    | 2         | 2.6%    |
| 0x406e3    | 2         | 2.6%    |
| 0x1067a    | 2         | 2.6%    |
| 0x07030105 | 2         | 2.6%    |
| 0x906ed    | 1         | 1.3%    |
| 0x906ea    | 1         | 1.3%    |
| 0x906e9    | 1         | 1.3%    |
| 0x906a3    | 1         | 1.3%    |
| 0x806ec    | 1         | 1.3%    |
| 0x806eb    | 1         | 1.3%    |
| 0x806ea    | 1         | 1.3%    |
| 0x806d1    | 1         | 1.3%    |
| 0x806c1    | 1         | 1.3%    |
| 0x6f6      | 1         | 1.3%    |
| 0x506c9    | 1         | 1.3%    |
| 0x40651    | 1         | 1.3%    |
| 0x306c3    | 1         | 1.3%    |
| 0x08600106 | 1         | 1.3%    |
| 0x08108109 | 1         | 1.3%    |
| 0x03000027 | 1         | 1.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 17        | 22.08%  |
| SandyBridge      | 8         | 10.39%  |
| IvyBridge        | 7         | 9.09%   |
| Penryn           | 5         | 6.49%   |
| Unknown          | 5         | 6.49%   |
| Skylake          | 3         | 3.9%    |
| IceLake          | 3         | 3.9%    |
| Goldmont plus    | 3         | 3.9%    |
| Zen+             | 2         | 2.6%    |
| Zen 3            | 2         | 2.6%    |
| Zen 2            | 2         | 2.6%    |
| Westmere         | 2         | 2.6%    |
| TigerLake        | 2         | 2.6%    |
| Silvermont       | 2         | 2.6%    |
| Puma             | 2         | 2.6%    |
| Haswell          | 2         | 2.6%    |
| Excavator        | 2         | 2.6%    |
| CometLake        | 2         | 2.6%    |
| Broadwell        | 2         | 2.6%    |
| K10 Llano        | 1         | 1.3%    |
| Goldmont         | 1         | 1.3%    |
| Core             | 1         | 1.3%    |
| Alderlake Hybrid | 1         | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 53.85%  |
| Nvidia | 24        | 23.08%  |
| AMD    | 24        | 23.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 7.48%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 5.61%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.74%   |
| Intel HD Graphics 620                                                                    | 4         | 3.74%   |
| AMD Lucienne                                                                             | 4         | 3.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 2.8%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 1.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.87%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.87%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.87%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.87%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.87%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.87%   |
| AMD Renoir                                                                               | 2         | 1.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.87%   |
| AMD Cezanne                                                                              | 2         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.93%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.93%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.93%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.93%   |
| Nvidia GM206M [GeForce GTX 965M]                                                         | 1         | 0.93%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.93%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.93%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.93%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.93%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.93%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 0.93%   |
| Nvidia GF108M [GeForce GT 620M]                                                          | 1         | 0.93%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                              | 1         | 0.93%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.93%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 0.93%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.93%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                               | 1         | 0.93%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.93%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.93%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1         | 0.93%   |
| Intel HD Graphics 630                                                                    | 1         | 0.93%   |
| Intel HD Graphics 530                                                                    | 1         | 0.93%   |
| Intel HD Graphics 500                                                                    | 1         | 0.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.93%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 0.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 0.93%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.93%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.93%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 41.56%  |
| Intel + Nvidia | 18        | 23.38%  |
| 1 x AMD        | 14        | 18.18%  |
| Intel + AMD    | 6         | 7.79%   |
| AMD + Nvidia   | 3         | 3.9%    |
| 1 x Nvidia     | 2         | 2.6%    |
| 2 x Nvidia     | 1         | 1.3%    |
| 2 x AMD        | 1         | 1.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 70        | 90.91%  |
| Proprietary | 6         | 7.79%   |
| Unknown     | 1         | 1.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 61        | 79.22%  |
| 1.01-2.0   | 6         | 7.79%   |
| 0.01-0.5   | 5         | 6.49%   |
| 3.01-4.0   | 3         | 3.9%    |
| 0.51-1.0   | 2         | 2.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 22        | 26.19%  |
| BOE                     | 18        | 21.43%  |
| LG Display              | 11        | 13.1%   |
| Chimei Innolux          | 10        | 11.9%   |
| Samsung Electronics     | 6         | 7.14%   |
| Apple                   | 4         | 4.76%   |
| Chi Mei Optoelectronics | 3         | 3.57%   |
| Lenovo                  | 2         | 2.38%   |
| Unknown (AAA)           | 1         | 1.19%   |
| PANDA                   | 1         | 1.19%   |
| ONN                     | 1         | 1.19%   |
| NEC Computers           | 1         | 1.19%   |
| Kogan                   | 1         | 1.19%   |
| Goldstar                | 1         | 1.19%   |
| CSO                     | 1         | 1.19%   |
| AOC                     | 1         | 1.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 3         | 3.57%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch                 | 1         | 1.19%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch      | 1         | 1.19%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch        | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch     | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch     | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch     | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 890x500mm 40.2-inch    | 1         | 1.19%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                  | 1         | 1.19%   |
| ONN ONA24HB19T01 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1         | 1.19%   |
| NEC Computers EA243WM NEC6863 1920x1200 519x324mm 24.1-inch              | 1         | 1.19%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 1         | 1.19%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch             | 1         | 1.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 1.19%   |
| LG Display LCD Monitor LGD045A 1366x768 293x165mm 13.2-inch              | 1         | 1.19%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch              | 1         | 1.19%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch              | 1         | 1.19%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 1         | 1.19%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch              | 1         | 1.19%   |
| LG Display LCD Monitor LGD0292 1366x768 309x174mm 14.0-inch              | 1         | 1.19%   |
| LG Display LCD Monitor LGD0257 1440x900 304x190mm 14.1-inch              | 1         | 1.19%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch             | 1         | 1.19%   |
| Lenovo LCD Monitor LEN1144 1920x1200 518x324mm 24.1-inch                 | 1         | 1.19%   |
| Lenovo D27-30 LEN66B8 1920x1080 597x336mm 27.0-inch                      | 1         | 1.19%   |
| Kogan KAMN27F7TA KGN0270 1920x1080 600x330mm 27.0-inch                   | 1         | 1.19%   |
| Goldstar TV GSM0002 1920x1080 1150x650mm 52.0-inch                       | 1         | 1.19%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 1.19%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN1736 1600x900 382x214mm 17.2-inch          | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN1526 1920x1080 344x193mm 15.5-inch         | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch          | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch          | 1         | 1.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 1         | 1.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 1         | 1.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 1         | 1.19%   |
| BOE LCD Monitor BOE0A1C 1920x1080 344x194mm 15.5-inch                    | 1         | 1.19%   |
| BOE LCD Monitor BOE0990 2560x1600 344x215mm 16.0-inch                    | 1         | 1.19%   |
| BOE LCD Monitor BOE08E5 1366x768 344x194mm 15.5-inch                     | 1         | 1.19%   |
| BOE LCD Monitor BOE08DA 1920x1080 309x174mm 14.0-inch                    | 1         | 1.19%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 1         | 1.19%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 1         | 1.19%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                    | 1         | 1.19%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                    | 1         | 1.19%   |
| BOE LCD Monitor BOE07E8 1366x768 309x173mm 13.9-inch                     | 1         | 1.19%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                    | 1         | 1.19%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 1         | 1.19%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 1.19%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 1         | 1.19%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 1         | 1.19%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 1.19%   |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                     | 1         | 1.19%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                     | 1         | 1.19%   |
| BOE LCD Monitor BOE05F9 1920x1080 309x173mm 13.9-inch                    | 1         | 1.19%   |
| AU Optronics LCD Monitor AUODB95 2560x1600 344x215mm 16.0-inch           | 1         | 1.19%   |
| AU Optronics LCD Monitor AUOA114 1280x800 261x163mm 12.1-inch            | 1         | 1.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 38.46%  |
| 1366x768 (WXGA)    | 29        | 37.18%  |
| 1600x900 (HD+)     | 6         | 7.69%   |
| 1280x800 (WXGA)    | 4         | 5.13%   |
| 2560x1600          | 2         | 2.56%   |
| 1440x900 (WXGA+)   | 2         | 2.56%   |
| 3840x2160 (4K)     | 1         | 1.28%   |
| 2880x1800          | 1         | 1.28%   |
| 2160x1440          | 1         | 1.28%   |
| 1920x1200 (WUXGA)  | 1         | 1.28%   |
| 1680x1050 (WSXGA+) | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 34        | 40.96%  |
| 14     | 14        | 16.87%  |
| 13     | 9         | 10.84%  |
| 17     | 7         | 8.43%   |
| 24     | 3         | 3.61%   |
| 16     | 3         | 3.61%   |
| 12     | 3         | 3.61%   |
| 27     | 2         | 2.41%   |
| 11     | 2         | 2.41%   |
| 52     | 1         | 1.2%    |
| 48     | 1         | 1.2%    |
| 40     | 1         | 1.2%    |
| 31     | 1         | 1.2%    |
| 23     | 1         | 1.2%    |
| 21     | 1         | 1.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 57        | 68.67%  |
| 351-400     | 8         | 9.64%   |
| 201-300     | 7         | 8.43%   |
| 501-600     | 6         | 7.23%   |
| 1001-1500   | 2         | 2.41%   |
| 801-900     | 1         | 1.2%    |
| 601-700     | 1         | 1.2%    |
| 401-500     | 1         | 1.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 63        | 84%     |
| 16/10 | 11        | 14.67%  |
| 3/2   | 1         | 1.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 42.17%  |
| 81-90          | 21        | 25.3%   |
| 121-130        | 6         | 7.23%   |
| 61-70          | 3         | 3.61%   |
| 201-250        | 3         | 3.61%   |
| More than 1000 | 2         | 2.41%   |
| 71-80          | 2         | 2.41%   |
| 51-60          | 2         | 2.41%   |
| 301-350        | 2         | 2.41%   |
| 251-300        | 2         | 2.41%   |
| 111-120        | 2         | 2.41%   |
| 351-500        | 1         | 1.2%    |
| 131-140        | 1         | 1.2%    |
| 501-1000       | 1         | 1.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 33        | 39.76%  |
| 101-120       | 33        | 39.76%  |
| 51-100        | 9         | 10.84%  |
| 161-240       | 4         | 4.82%   |
| 1-50          | 3         | 3.61%   |
| More than 240 | 1         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 65        | 84.42%  |
| 2     | 10        | 12.99%  |
| 3     | 1         | 1.3%    |
| 0     | 1         | 1.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 44        | 33.08%  |
| Intel                           | 41        | 30.83%  |
| Qualcomm Atheros                | 15        | 11.28%  |
| Broadcom                        | 8         | 6.02%   |
| MediaTek                        | 5         | 3.76%   |
| TP-Link                         | 3         | 2.26%   |
| Samsung Electronics             | 2         | 1.5%    |
| Nvidia                          | 2         | 1.5%    |
| NetGear                         | 2         | 1.5%    |
| Huawei Technologies             | 2         | 1.5%    |
| ASUSTek Computer                | 2         | 1.5%    |
| Apple                           | 2         | 1.5%    |
| Ralink                          | 1         | 0.75%   |
| Qualcomm Atheros Communications | 1         | 0.75%   |
| Linksys                         | 1         | 0.75%   |
| Broadcom Limited                | 1         | 0.75%   |
| ASIX Electronics                | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 20        | 12.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 6.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.13%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.13%   |
| Realtek 802.11ac NIC                                                    | 4         | 2.5%    |
| Intel Wireless 3165                                                     | 4         | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.88%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 1.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 1.88%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.88%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 1.25%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 1.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 1.25%   |
| NetGear A6210                                                           | 2         | 1.25%   |
| Intel Wireless 3160                                                     | 2         | 1.25%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.25%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.25%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.25%   |
| Intel Centrino Wireless-N 2200                                          | 2         | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.25%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.25%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 1.25%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.25%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.63%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.63%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.63%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 1         | 0.63%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.63%   |
| Nvidia MCP89 Ethernet                                                   | 1         | 0.63%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.63%   |
| MediaTek moto e(6) plus                                                 | 1         | 0.63%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 0.63%   |
| Intel Wireless 8260                                                     | 1         | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.63%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 43.48%  |
| Realtek Semiconductor           | 20        | 21.74%  |
| Qualcomm Atheros                | 11        | 11.96%  |
| Broadcom                        | 6         | 6.52%   |
| MediaTek                        | 4         | 4.35%   |
| TP-Link                         | 3         | 3.26%   |
| NetGear                         | 2         | 2.17%   |
| ASUSTek Computer                | 2         | 2.17%   |
| Ralink                          | 1         | 1.09%   |
| Qualcomm Atheros Communications | 1         | 1.09%   |
| Linksys                         | 1         | 1.09%   |
| Broadcom Limited                | 1         | 1.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 5.43%   |
| Intel Wireless 8265 / 8275                                              | 5         | 5.43%   |
| Realtek 802.11ac NIC                                                    | 4         | 4.35%   |
| Intel Wireless 3165                                                     | 4         | 4.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.26%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 3.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 3.26%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 3.26%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.17%   |
| NetGear A6210                                                           | 2         | 2.17%   |
| Intel Wireless 3160                                                     | 2         | 2.17%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.17%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.17%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 2.17%   |
| Intel Centrino Wireless-N 2200                                          | 2         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 2.17%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 2.17%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 2.17%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 1.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.09%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.09%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.09%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 1.09%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 1.09%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.09%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.09%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.09%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.09%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 1.09%   |
| Intel Wireless 8260                                                     | 1         | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.09%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.09%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.09%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.09%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.09%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 1         | 1.09%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 1         | 1.09%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.09%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]     | 1         | 1.09%   |
| ASUS 802.11ac NIC                                                       | 1         | 1.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 34        | 52.31%  |
| Intel                 | 14        | 21.54%  |
| Qualcomm Atheros      | 5         | 7.69%   |
| Broadcom              | 3         | 4.62%   |
| Samsung Electronics   | 2         | 3.08%   |
| Nvidia                | 2         | 3.08%   |
| Apple                 | 2         | 3.08%   |
| MediaTek              | 1         | 1.54%   |
| Huawei Technologies   | 1         | 1.54%   |
| ASIX Electronics      | 1         | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 29.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 14.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 2.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.99%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.99%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.49%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.49%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.49%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.49%   |
| MediaTek moto e(6) plus                                           | 1         | 1.49%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.49%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.49%   |
| Huawei Ideos (tethering mode)                                     | 1         | 1.49%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.49%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.49%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.49%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.49%   |
| Apple iPad 4/Mini1                                                | 1         | 1.49%   |
| Apple iBridge                                                     | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 54.68%  |
| Ethernet | 62        | 44.6%   |
| Modem    | 1         | 0.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 75%     |
| Ethernet | 20        | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 54        | 70.13%  |
| 1     | 21        | 27.27%  |
| 3     | 1         | 1.3%    |
| 0     | 1         | 1.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 58        | 74.36%  |
| Yes  | 20        | 25.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 47.69%  |
| Qualcomm Atheros Communications | 7         | 10.77%  |
| Realtek Semiconductor           | 6         | 9.23%   |
| MediaTek                        | 3         | 4.62%   |
| IMC Networks                    | 3         | 4.62%   |
| Apple                           | 3         | 4.62%   |
| Toshiba                         | 2         | 3.08%   |
| Lite-On Technology              | 2         | 3.08%   |
| Foxconn / Hon Hai               | 2         | 3.08%   |
| Broadcom                        | 2         | 3.08%   |
| Realtek                         | 1         | 1.54%   |
| Ralink                          | 1         | 1.54%   |
| Dell                            | 1         | 1.54%   |
| Cambridge Silicon Radio         | 1         | 1.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 13        | 20%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 9.23%   |
| Intel AX201 Bluetooth                                                               | 6         | 9.23%   |
| Realtek Bluetooth Radio                                                             | 5         | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 6.15%   |
| MediaTek Wireless_Device                                                            | 3         | 4.62%   |
| Intel Bluetooth Device                                                              | 2         | 3.08%   |
| Intel AX200 Bluetooth                                                               | 2         | 3.08%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 3.08%   |
| Apple Bluetooth Host Controller                                                     | 2         | 3.08%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 1.54%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.54%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.54%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.54%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.54%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.54%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.54%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.54%   |
| Lite-On Wireless_Device                                                             | 1         | 1.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.54%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.54%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.54%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.54%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.54%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 1.54%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.54%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 1.54%   |
| Broadcom BCM20702A0                                                                 | 1         | 1.54%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 64.44%  |
| AMD    | 17        | 18.89%  |
| Nvidia | 14        | 15.56%  |
| Apple  | 1         | 1.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 10.38%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 8.49%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 8.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 5.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 5.66%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.83%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.89%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 1.89%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 1.89%   |
| Nvidia Audio device                                                                               | 2         | 1.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.89%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.89%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.89%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.89%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.89%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.89%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.94%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.94%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.94%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.94%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.94%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.94%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.94%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 0.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.94%   |
| Apple Audio Device                                                                                | 1         | 0.94%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.94%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 25.45%  |
| Micron Technology   | 11        | 20%     |
| SK hynix            | 9         | 16.36%  |
| Crucial             | 5         | 9.09%   |
| Kingston            | 4         | 7.27%   |
| Unknown (ABCD)      | 3         | 5.45%   |
| Ramaxel Technology  | 3         | 5.45%   |
| Elpida              | 3         | 5.45%   |
| Teikon              | 1         | 1.82%   |
| Smart               | 1         | 1.82%   |
| Saikano             | 1         | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 3         | 5.26%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.51%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 3.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 3.51%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 3.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.51%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s   | 2         | 3.51%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 3.51%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 1         | 1.75%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.75%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.75%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 1.75%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 1.75%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.75%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.75%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1         | 1.75%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.75%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.75%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s        | 1         | 1.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.75%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s             | 1         | 1.75%   |
| Samsung RAM M378B2873CZ0-CF7 1GB SODIMM DDR3 800MT/s             | 1         | 1.75%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.75%   |
| Saikano RAM Memory 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.75%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.75%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.75%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.75%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s               | 1         | 1.75%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s         | 1         | 1.75%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s             | 1         | 1.75%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.75%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.75%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 1.75%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.75%   |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.75%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.75%   |
| Kingston RAM KF3200C20S4/16GX 16GB SODIMM DDR4 3200MT/s          | 1         | 1.75%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s             | 1         | 1.75%   |
| Kingston RAM HP594908-HR1-ELD 2GB SODIMM DDR3 1333MT/s           | 1         | 1.75%   |
| Kingston RAM 9905711-007.A00G 4GB SODIMM DDR4 2400MT/s           | 1         | 1.75%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.75%   |
| Elpida RAM Module 1GB SODIMM DDR3 1067MT/s                       | 1         | 1.75%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 1         | 1.75%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s           | 1         | 1.75%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16384MB SODIMM DDR4 3200MT/s      | 1         | 1.75%   |
| Crucial RAM CT16G4SFRA266.C8FE 16GB SODIMM DDR4 2667MT/s         | 1         | 1.75%   |
| Crucial RAM CT16G4SFD832A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 1         | 1.75%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 1         | 1.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 21        | 47.73%  |
| DDR3   | 15        | 34.09%  |
| LPDDR4 | 5         | 11.36%  |
| SDRAM  | 1         | 2.27%   |
| LPDDR3 | 1         | 2.27%   |
| DDR5   | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 88.64%  |
| Row Of Chips | 5         | 11.36%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 25        | 51.02%  |
| 8192  | 10        | 20.41%  |
| 16384 | 7         | 14.29%  |
| 2048  | 4         | 8.16%   |
| 1024  | 2         | 4.08%   |
| 32768 | 1         | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 12        | 24%     |
| 1600  | 12        | 24%     |
| 3200  | 10        | 20%     |
| 2400  | 5         | 10%     |
| 1334  | 3         | 6%      |
| 1333  | 2         | 4%      |
| 4800  | 1         | 2%      |
| 3266  | 1         | 2%      |
| 2048  | 1         | 2%      |
| 1867  | 1         | 2%      |
| 1067  | 1         | 2%      |
| 800   | 1         | 2%      |

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
| Chicony Electronics                    | 18        | 25%     |
| IMC Networks                           | 9         | 12.5%   |
| Acer                                   | 8         | 11.11%  |
| Microdia                               | 7         | 9.72%   |
| Apple                                  | 6         | 8.33%   |
| Realtek Semiconductor                  | 4         | 5.56%   |
| Quanta                                 | 4         | 5.56%   |
| Sunplus Innovation Technology          | 3         | 4.17%   |
| Syntek                                 | 2         | 2.78%   |
| Suyin                                  | 1         | 1.39%   |
| Silicon Motion                         | 1         | 1.39%   |
| Ricoh                                  | 1         | 1.39%   |
| Primax Electronics                     | 1         | 1.39%   |
| Luxvisions Innotech Limited            | 1         | 1.39%   |
| Lite-On Technology                     | 1         | 1.39%   |
| Importek                               | 1         | 1.39%   |
| icSpring                               | 1         | 1.39%   |
| Goertek Electronics                    | 1         | 1.39%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.39%   |
| Alcor Micro                            | 1         | 1.39%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                         | 3         | 4.17%   |
| Chicony HP Truevision HD                             | 3         | 4.17%   |
| Acer HD Webcam                                       | 3         | 4.17%   |
| Quanta HP TrueVision HD Camera                       | 2         | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 2         | 2.78%   |
| IMC Networks Integrated Camera                       | 2         | 2.78%   |
| Chicony USB2.0 Camera                                | 2         | 2.78%   |
| Chicony TOSHIBA Web Camera - HD                      | 2         | 2.78%   |
| Chicony Integrated Camera [ThinkPad]                 | 2         | 2.78%   |
| Chicony Integrated Camera                            | 2         | 2.78%   |
| Chicony HD User Facing                               | 2         | 2.78%   |
| Apple iPhone 5/5C/5S/6/SE                            | 2         | 2.78%   |
| Apple Built-in iSight                                | 2         | 2.78%   |
| Acer SunplusIT Integrated Camera                     | 2         | 2.78%   |
| Syntek Lenovo EasyCamera                             | 1         | 1.39%   |
| Syntek Integrated Camera                             | 1         | 1.39%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 1.39%   |
| Silicon Motion WebCam SC-13HDL11939N                 | 1         | 1.39%   |
| Ricoh HD Webcam                                      | 1         | 1.39%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.39%   |
| Realtek Integrated Webcam                            | 1         | 1.39%   |
| Realtek Integrated Camera                            | 1         | 1.39%   |
| Realtek HP Webcam                                    | 1         | 1.39%   |
| Quanta VGA WebCam                                    | 1         | 1.39%   |
| Quanta HD User Facing                                | 1         | 1.39%   |
| Primax HP HD Webcam [Fixed]                          | 1         | 1.39%   |
| Microdia PC Microscope camera                        | 1         | 1.39%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 1.39%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.39%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.39%   |
| Microdia Integrated Webcam                           | 1         | 1.39%   |
| Microdia HP Integrated Webcam                        | 1         | 1.39%   |
| Microdia Amcrest AWC2198 USB Webcam                  | 1         | 1.39%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.39%   |
| Lite-On HP HD Camera                                 | 1         | 1.39%   |
| Importek TOSHIBA Web Camera - HD                     | 1         | 1.39%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 1.39%   |
| IMC Networks USB Camera                              | 1         | 1.39%   |
| IMC Networks ov9734_azurewave_camera                 | 1         | 1.39%   |
| IMC Networks Lenovo EasyCamera                       | 1         | 1.39%   |
| IMC Networks HD Camera                               | 1         | 1.39%   |
| icSpring camera                                      | 1         | 1.39%   |
| Goertek USB2.0 VGA UVC WebCam                        | 1         | 1.39%   |
| Chicony Integrated HP HD Webcam                      | 1         | 1.39%   |
| Chicony Integrated Camera (1280x720@30)              | 1         | 1.39%   |
| Chicony HP HD Camera                                 | 1         | 1.39%   |
| Chicony FJ Camera                                    | 1         | 1.39%   |
| Chicony EasyCamera                                   | 1         | 1.39%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 1         | 1.39%   |
| Apple FaceTime HD Camera (Built-in)                  | 1         | 1.39%   |
| Apple FaceTime Camera                                | 1         | 1.39%   |
| Alcor Micro USB 2.0 PC cam                           | 1         | 1.39%   |
| Acer Lenovo EasyCamera                               | 1         | 1.39%   |
| Acer HP TrueVision HD Webcam                         | 1         | 1.39%   |
| Acer HD Camera                                       | 1         | 1.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 40%     |
| Synaptics                  | 4         | 26.67%  |
| Shenzhen Goodix Technology | 3         | 20%     |
| Elan Microelectronics      | 1         | 6.67%   |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 13.33%  |
| Shenzhen Goodix  Fingerprint Device                       | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 6.67%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 6.67%   |
| Validity Sensors Synaptics WBDI                           | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                      | 1         | 6.67%   |
| Synaptics  WBDI                                           | 1         | 6.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 6.67%   |
| Elan ELAN:ARM-M4                                          | 1         | 6.67%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 1         | 6.67%   |

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
| 0     | 41        | 53.25%  |
| 1     | 31        | 40.26%  |
| 2     | 4         | 5.19%   |
| 3     | 1         | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 37.5%   |
| Net/wireless          | 9         | 22.5%   |
| Chipcard              | 6         | 15%     |
| Graphics card         | 5         | 12.5%   |
| Multimedia controller | 2         | 5%      |
| Storage               | 1         | 2.5%    |
| Network               | 1         | 2.5%    |
| Bluetooth             | 1         | 2.5%    |

