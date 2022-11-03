Ubuntu MATE 22.04 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 22.04.

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

Total: 72

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook      | NJx0MU                      | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| Dell          | Precision 7760              | [b8fce270db](https://linux-hardware.org/?probe=b8fce270db) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Toshiba       | Satellite C50D-A-133        | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| Apple         | MacBookAir6,1               | [4785b7f6f6](https://linux-hardware.org/?probe=4785b7f6f6) | Oct 25, 2022 |
| HP            | ENVY Sleekbook 6            | [a197375e26](https://linux-hardware.org/?probe=a197375e26) | Oct 19, 2022 |
| Acer          | Aspire 7750G                | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| Chuwi         | GemiBook Pro                | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| Chuwi         | GemiBook Pro                | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | UX32VD                      | [0bea9d8673](https://linux-hardware.org/?probe=0bea9d8673) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| Dell          | Latitude 7300               | [d9acb6ec9c](https://linux-hardware.org/?probe=d9acb6ec9c) | Oct 03, 2022 |
| Sony          | VGN-SZ3XP_C                 | [6e9671dd1a](https://linux-hardware.org/?probe=6e9671dd1a) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [ccf9b69093](https://linux-hardware.org/?probe=ccf9b69093) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [7b89b5d0cf](https://linux-hardware.org/?probe=7b89b5d0cf) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | [ac14cbda52](https://linux-hardware.org/?probe=ac14cbda52) | Oct 02, 2022 |
| Intel         | H81U                        | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| Dell          | Precision 7760              | [f6600a1244](https://linux-hardware.org/?probe=f6600a1244) | Sep 22, 2022 |
| Intel         | Kabylake Platform           | [8b1c5eb5bf](https://linux-hardware.org/?probe=8b1c5eb5bf) | Sep 21, 2022 |
| Acer          | Aspire 5050                 | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [64b8914cb2](https://linux-hardware.org/?probe=64b8914cb2) | Sep 12, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| Dell          | Precision 7760              | [e920197599](https://linux-hardware.org/?probe=e920197599) | Sep 05, 2022 |
| HP            | Pavilion 15                 | [194bb33f3d](https://linux-hardware.org/?probe=194bb33f3d) | Sep 04, 2022 |
| Dell          | Inspiron 7720               | [0749c352d0](https://linux-hardware.org/?probe=0749c352d0) | Sep 03, 2022 |
| HP            | Notebook                    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| HP            | 15 Notebook PC              | [1109650747](https://linux-hardware.org/?probe=1109650747) | Aug 31, 2022 |
| LincPlus      | LINNCPLUS P1                | [516427e0e9](https://linux-hardware.org/?probe=516427e0e9) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| Notebook      | NJx0MU                      | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| Dell          | Latitude 7420               | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [4efd818377](https://linux-hardware.org/?probe=4efd818377) | Aug 19, 2022 |
| HP            | EliteBook 745 G5            | [7e8d33a07f](https://linux-hardware.org/?probe=7e8d33a07f) | Aug 16, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| Dell          | Latitude E7470              | [61d0b104e9](https://linux-hardware.org/?probe=61d0b104e9) | Aug 13, 2022 |
| HP            | 15 Notebook PC              | [46aa83aeb4](https://linux-hardware.org/?probe=46aa83aeb4) | Aug 07, 2022 |
| HONOR         | BOHK-WAX9X                  | [3d426cb1de](https://linux-hardware.org/?probe=3d426cb1de) | Aug 04, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| Dell          | Latitude E4200              | [6cc0415a8a](https://linux-hardware.org/?probe=6cc0415a8a) | Jul 21, 2022 |
| Compaq        | Presario CQ-23              | [589a41e629](https://linux-hardware.org/?probe=589a41e629) | Jul 14, 2022 |
| MicroByte     | ezbook                      | [91b1fc169b](https://linux-hardware.org/?probe=91b1fc169b) | Jun 28, 2022 |
| Dell          | XPS 17 9710                 | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| ASUSTek       | S550CM                      | [c7262ada04](https://linux-hardware.org/?probe=c7262ada04) | Jun 25, 2022 |
| HUAWEI        | KLVD-WXX9                   | [a8c98b76b4](https://linux-hardware.org/?probe=a8c98b76b4) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| Google        | Kled                        | [5f47e6d3e3](https://linux-hardware.org/?probe=5f47e6d3e3) | Jun 16, 2022 |
| Google        | Kled                        | [6a566134c4](https://linux-hardware.org/?probe=6a566134c4) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| HP            | EliteBook 8560p             | [9bfdb902ce](https://linux-hardware.org/?probe=9bfdb902ce) | Jun 08, 2022 |
| Intel         | Kabylake Platform           | [074fd90c6a](https://linux-hardware.org/?probe=074fd90c6a) | Jun 06, 2022 |
| TrekStor      | Surfbook A13B               | [a42b3de31a](https://linux-hardware.org/?probe=a42b3de31a) | Jun 05, 2022 |
| Dell          | Precision M6500             | [1b68d2ca74](https://linux-hardware.org/?probe=1b68d2ca74) | Jun 01, 2022 |
| Apple         | MacBook5,1                  | [74e6dbe9af](https://linux-hardware.org/?probe=74e6dbe9af) | May 23, 2022 |
| Apple         | MacBook5,1                  | [a53d746d08](https://linux-hardware.org/?probe=a53d746d08) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Sony          | VPCEA36FG                   | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HONOR         | BOHK-WAX9X                  | [e6c4aaa3d8](https://linux-hardware.org/?probe=e6c4aaa3d8) | May 12, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e99cdba363](https://linux-hardware.org/?probe=e99cdba363) | May 07, 2022 |
| HP            | EliteBook 840 G5            | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HYPERPC       | PLAY                        | [408e86d04f](https://linux-hardware.org/?probe=408e86d04f) | May 06, 2022 |
| Apple         | MacBookPro6,2               | [ebaaf4a69b](https://linux-hardware.org/?probe=ebaaf4a69b) | May 01, 2022 |
| Apple         | MacBookPro9,1               | [35b3b3ae30](https://linux-hardware.org/?probe=35b3b3ae30) | Apr 26, 2022 |
| Apple         | MacBookPro9,1               | [faf447a067](https://linux-hardware.org/?probe=faf447a067) | Apr 24, 2022 |
| IPASON        | MaxBook P1                  | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [b746a25ff1](https://linux-hardware.org/?probe=b746a25ff1) | Jan 28, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-47-generic     | 6         | 11.32%  |
| 5.15.0-46-generic     | 6         | 11.32%  |
| 5.15.0-25-generic     | 6         | 11.32%  |
| 5.15.0-48-generic     | 5         | 9.43%   |
| 5.15.0-43-generic     | 4         | 7.55%   |
| 5.15.0-40-generic     | 4         | 7.55%   |
| 5.15.0-52-generic     | 3         | 5.66%   |
| 5.15.0-30-generic     | 3         | 5.66%   |
| 5.15.0-27-generic     | 3         | 5.66%   |
| 5.15.0-41-generic     | 2         | 3.77%   |
| 5.18.0-051800-generic | 1         | 1.89%   |
| 5.17.1-051701-generic | 1         | 1.89%   |
| 5.17.0-1003-oem       | 1         | 1.89%   |
| 5.15.0-52-lowlatency  | 1         | 1.89%   |
| 5.15.0-50-generic     | 1         | 1.89%   |
| 5.15.0-46-lowlatency  | 1         | 1.89%   |
| 5.15.0-39-generic     | 1         | 1.89%   |
| 5.15.0-37-generic     | 1         | 1.89%   |
| 5.15.0-35-generic     | 1         | 1.89%   |
| 5.15.0-33-generic     | 1         | 1.89%   |
| 5.15.0-18-generic     | 1         | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 46        | 93.88%  |
| 5.18.0  | 1         | 2.04%   |
| 5.17.1  | 1         | 2.04%   |
| 5.17.0  | 1         | 2.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 46        | 93.88%  |
| 5.17    | 2         | 4.08%   |
| 5.18    | 1         | 2.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 49        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MATE | 49        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 48        | 97.96%  |
| Wayland | 1         | 2.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 40        | 80%     |
| Unknown | 7         | 14%     |
| GDM3    | 3         | 6%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 21        | 42.86%  |
| fr_FR | 6         | 12.24%  |
| it_IT | 5         | 10.2%   |
| de_DE | 5         | 10.2%   |
| ru_RU | 4         | 8.16%   |
| pt_BR | 2         | 4.08%   |
| zh_CN | 1         | 2.04%   |
| pl_PL | 1         | 2.04%   |
| fi_FI | 1         | 2.04%   |
| es_ES | 1         | 2.04%   |
| en_GB | 1         | 2.04%   |
| en_AU | 1         | 2.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 30        | 57.69%  |
| BIOS | 22        | 42.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 41        | 83.67%  |
| Zfs     | 3         | 6.12%   |
| Overlay | 3         | 6.12%   |
| Jfs     | 1         | 2.04%   |
| Btrfs   | 1         | 2.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 33        | 66%     |
| Unknown | 14        | 28%     |
| MBR     | 3         | 6%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 81.63%  |
| Yes       | 9         | 18.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 62%     |
| Yes       | 19        | 38%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 10        | 20.41%  |
| Hewlett-Packard  | 8         | 16.33%  |
| Dell             | 6         | 12.24%  |
| ASUSTek Computer | 4         | 8.16%   |
| Apple            | 4         | 8.16%   |
| Intel            | 2         | 4.08%   |
| TrekStor         | 1         | 2.04%   |
| Toshiba          | 1         | 2.04%   |
| Sony             | 1         | 2.04%   |
| Notebook         | 1         | 2.04%   |
| MicroByte        | 1         | 2.04%   |
| LincPlus         | 1         | 2.04%   |
| LG Electronics   | 1         | 2.04%   |
| IPASON           | 1         | 2.04%   |
| HYPERPC          | 1         | 2.04%   |
| HUAWEI           | 1         | 2.04%   |
| HONOR            | 1         | 2.04%   |
| Google           | 1         | 2.04%   |
| Compaq           | 1         | 2.04%   |
| Chuwi            | 1         | 2.04%   |
| Acer             | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| TrekStor Surfbook A13B               | 1         | 2.04%   |
| Toshiba Satellite C50D-A-133         | 1         | 2.04%   |
| Sony VPCEA36FG                       | 1         | 2.04%   |
| Notebook NJx0MU                      | 1         | 2.04%   |
| MicroByte ezbook                     | 1         | 2.04%   |
| LincPlus LINNCPLUS P1                | 1         | 2.04%   |
| LG 17Z990-R.AAS8U1                   | 1         | 2.04%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 2.04%   |
| Lenovo ThinkPad X230 2325Y5L         | 1         | 2.04%   |
| Lenovo ThinkPad T460p 20FW002CPB     | 1         | 2.04%   |
| Lenovo ThinkPad SL500 27463ZG        | 1         | 2.04%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0T500 | 1         | 2.04%   |
| Lenovo ThinkBook 16p Gen 2 20YM      | 1         | 2.04%   |
| Lenovo ThinkBook 14 G2 ITL 20VD      | 1         | 2.04%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 1         | 2.04%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 1         | 2.04%   |
| Lenovo IdeaPad 3 15ALC6 82KU         | 1         | 2.04%   |
| IPASON MaxBook P1                    | 1         | 2.04%   |
| Intel Kabylake Platform              | 1         | 2.04%   |
| Intel H81U                           | 1         | 2.04%   |
| HYPERPC PLAY                         | 1         | 2.04%   |
| HUAWEI KLVD-WXX9                     | 1         | 2.04%   |
| HONOR BOHK-WAX9X                     | 1         | 2.04%   |
| HP ZBook 14 G2                       | 1         | 2.04%   |
| HP Pavilion 15                       | 1         | 2.04%   |
| HP Notebook                          | 1         | 2.04%   |
| HP ENVY Sleekbook 6                  | 1         | 2.04%   |
| HP EliteBook 8560p                   | 1         | 2.04%   |
| HP EliteBook 840 G5                  | 1         | 2.04%   |
| HP EliteBook 745 G5                  | 1         | 2.04%   |
| HP 15 Notebook PC                    | 1         | 2.04%   |
| Google Kled                          | 1         | 2.04%   |
| Dell XPS 17 9710                     | 1         | 2.04%   |
| Dell Precision M6500                 | 1         | 2.04%   |
| Dell Precision 7760                  | 1         | 2.04%   |
| Dell Latitude E4200                  | 1         | 2.04%   |
| Dell Latitude 7420                   | 1         | 2.04%   |
| Dell Inspiron 7720                   | 1         | 2.04%   |
| Compaq Presario CQ-23                | 1         | 2.04%   |
| Chuwi GemiBook Pro                   | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 4         | 8.16%   |
| Lenovo IdeaPad     | 3         | 6.12%   |
| HP EliteBook       | 3         | 6.12%   |
| Lenovo ThinkBook   | 2         | 4.08%   |
| Dell Precision     | 2         | 4.08%   |
| Dell Latitude      | 2         | 4.08%   |
| ASUS VivoBook      | 2         | 4.08%   |
| TrekStor Surfbook  | 1         | 2.04%   |
| Toshiba Satellite  | 1         | 2.04%   |
| Sony VPCEA36FG     | 1         | 2.04%   |
| Notebook NJx0MU    | 1         | 2.04%   |
| MicroByte ezbook   | 1         | 2.04%   |
| LincPlus LINNCPLUS | 1         | 2.04%   |
| LG 17Z990-R.AAS8U1 | 1         | 2.04%   |
| Lenovo V15         | 1         | 2.04%   |
| IPASON MaxBook     | 1         | 2.04%   |
| Intel Kabylake     | 1         | 2.04%   |
| Intel H81U         | 1         | 2.04%   |
| HYPERPC PLAY       | 1         | 2.04%   |
| HUAWEI KLVD-WXX9   | 1         | 2.04%   |
| HONOR BOHK-WAX9X   | 1         | 2.04%   |
| HP ZBook           | 1         | 2.04%   |
| HP Pavilion        | 1         | 2.04%   |
| HP Notebook        | 1         | 2.04%   |
| HP ENVY            | 1         | 2.04%   |
| HP 15              | 1         | 2.04%   |
| Google Kled        | 1         | 2.04%   |
| Dell XPS           | 1         | 2.04%   |
| Dell Inspiron      | 1         | 2.04%   |
| Compaq Presario    | 1         | 2.04%   |
| Chuwi GemiBook     | 1         | 2.04%   |
| ASUS UX32VD        | 1         | 2.04%   |
| ASUS S550CM        | 1         | 2.04%   |
| Apple MacBookPro9  | 1         | 2.04%   |
| Apple MacBookPro6  | 1         | 2.04%   |
| Apple MacBookAir6  | 1         | 2.04%   |
| Apple MacBook5     | 1         | 2.04%   |
| Acer Aspire        | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 13        | 26.53%  |
| 2012 | 6         | 12.24%  |
| 2020 | 5         | 10.2%   |
| 2019 | 4         | 8.16%   |
| 2018 | 3         | 6.12%   |
| 2010 | 3         | 6.12%   |
| 2022 | 2         | 4.08%   |
| 2016 | 2         | 4.08%   |
| 2015 | 2         | 4.08%   |
| 2013 | 2         | 4.08%   |
| 2009 | 2         | 4.08%   |
| 2017 | 1         | 2.04%   |
| 2014 | 1         | 2.04%   |
| 2011 | 1         | 2.04%   |
| 2008 | 1         | 2.04%   |
| 2006 | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 49        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 45        | 86.54%  |
| Enabled  | 7         | 13.46%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 97.96%  |
| Yes  | 1         | 2.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 17        | 34.69%  |
| 8.01-16.0   | 10        | 20.41%  |
| 3.01-4.0    | 9         | 18.37%  |
| 16.01-24.0  | 8         | 16.33%  |
| 32.01-64.0  | 3         | 6.12%   |
| 64.01-256.0 | 2         | 4.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 18        | 33.96%  |
| 1.01-2.0  | 12        | 22.64%  |
| 3.01-4.0  | 11        | 20.75%  |
| 4.01-8.0  | 8         | 15.09%  |
| 8.01-16.0 | 3         | 5.66%   |
| 0.51-1.0  | 1         | 1.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 38        | 77.55%  |
| 2      | 9         | 18.37%  |
| 3      | 2         | 4.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 69.39%  |
| Yes       | 15        | 30.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 73.47%  |
| No        | 13        | 26.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 87.76%  |
| No        | 6         | 12.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Italy       | 7         | 14.29%  |
| Germany     | 6         | 12.24%  |
| USA         | 5         | 10.2%   |
| France      | 5         | 10.2%   |
| Russia      | 4         | 8.16%   |
| Brazil      | 4         | 8.16%   |
| Spain       | 3         | 6.12%   |
| UK          | 2         | 4.08%   |
| Turkey      | 1         | 2.04%   |
| Serbia      | 1         | 2.04%   |
| Romania     | 1         | 2.04%   |
| Poland      | 1         | 2.04%   |
| Paraguay    | 1         | 2.04%   |
| Netherlands | 1         | 2.04%   |
| India       | 1         | 2.04%   |
| Hungary     | 1         | 2.04%   |
| Georgia     | 1         | 2.04%   |
| Finland     | 1         | 2.04%   |
| Estonia     | 1         | 2.04%   |
| Colombia    | 1         | 2.04%   |
| China       | 1         | 2.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Mannheim          | 2         | 4%      |
| Xining            | 1         | 2%      |
| Warsaw            | 1         | 2%      |
| Villeurbanne      | 1         | 2%      |
| Valenciennes      | 1         | 2%      |
| Turku             | 1         | 2%      |
| Tula              | 1         | 2%      |
| Thane             | 1         | 2%      |
| Seville           | 1         | 2%      |
| Settimo Torinese  | 1         | 2%      |
| Sarospatak        | 1         | 2%      |
| Sao Paulo         | 1         | 2%      |
| Rostov-on-Don     | 1         | 2%      |
| Porto Alegre      | 1         | 2%      |
| Pärnu            | 1         | 2%      |
| Paris             | 1         | 2%      |
| Ortuella          | 1         | 2%      |
| Norwich           | 1         | 2%      |
| North Wilkesboro  | 1         | 2%      |
| Newport News      | 1         | 2%      |
| Naaldwijk         | 1         | 2%      |
| Moscow            | 1         | 2%      |
| Milan             | 1         | 2%      |
| Memphis           | 1         | 2%      |
| Medellín         | 1         | 2%      |
| Marseille         | 1         | 2%      |
| Magdeburg         | 1         | 2%      |
| Limbiate          | 1         | 2%      |
| Laubach           | 1         | 2%      |
| La Rochelle       | 1         | 2%      |
| la Nucia          | 1         | 2%      |
| K'alak'i T'bilisi | 1         | 2%      |
| Jundiaí          | 1         | 2%      |
| Iesi              | 1         | 2%      |
| Hamburg           | 1         | 2%      |
| Guarulhos         | 1         | 2%      |
| Genoa             | 1         | 2%      |
| Edinburgh         | 1         | 2%      |
| College Station   | 1         | 2%      |
| Casale Litta      | 1         | 2%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 19     | 21.31%  |
| Toshiba             | 7         | 8      | 11.48%  |
| SanDisk             | 5         | 7      | 8.2%    |
| Crucial             | 5         | 5      | 8.2%    |
| Unknown             | 2         | 2      | 3.28%   |
| Phison              | 2         | 2      | 3.28%   |
| Kingston            | 2         | 2      | 3.28%   |
| KingSpec            | 2         | 2      | 3.28%   |
| China               | 2         | 2      | 3.28%   |
| A-DATA Technology   | 2         | 2      | 3.28%   |
| WDC                 | 1         | 1      | 1.64%   |
| UMIS                | 1         | 1      | 1.64%   |
| SK hynix            | 1         | 1      | 1.64%   |
| Seagate             | 1         | 1      | 1.64%   |
| Netac               | 1         | 1      | 1.64%   |
| Micron Technology   | 1         | 1      | 1.64%   |
| LITEONIT            | 1         | 1      | 1.64%   |
| Lenovo              | 1         | 1      | 1.64%   |
| Kston               | 1         | 1      | 1.64%   |
| KIOXIA              | 1         | 1      | 1.64%   |
| JMicron Technology  | 1         | 1      | 1.64%   |
| Intenso             | 1         | 1      | 1.64%   |
| Intel               | 1         | 1      | 1.64%   |
| Hjwdz               | 1         | 1      | 1.64%   |
| Hitachi             | 1         | 1      | 1.64%   |
| HGST                | 1         | 1      | 1.64%   |
| Gigabyte Technology | 1         | 1      | 1.64%   |
| faspeed             | 1         | 1      | 1.64%   |
| Apple               | 1         | 1      | 1.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                             | 2         | 3.13%   |
| Crucial CT240BX500SSD1 240GB                         | 2         | 3.13%   |
| Crucial CT1000BX500SSD1 1TB                          | 2         | 3.13%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                   | 1         | 1.56%   |
| Unknown SLD64G  64GB                                 | 1         | 1.56%   |
| Unknown Biwin  64GB                                  | 1         | 1.56%   |
| UMIS RPJTJ256MEE1OWX 256GB                           | 1         | 1.56%   |
| Toshiba THNSNK256GVN8 256GB SSD                      | 1         | 1.56%   |
| Toshiba MQ04ABF100 1TB                               | 1         | 1.56%   |
| Toshiba MK3259GSXP 320GB                             | 1         | 1.56%   |
| Toshiba KBG40ZNT256G MEMORY 256GB                    | 1         | 1.56%   |
| Toshiba KBG30ZMV256G 256GB                           | 1         | 1.56%   |
| SK hynix HFM128GDJTNG-8310A 128GB                    | 1         | 1.56%   |
| Seagate ST2000LM015-2E8174 2TB                       | 1         | 1.56%   |
| SanDisk SSD U100 24GB                                | 1         | 1.56%   |
| SanDisk SSD i100 24GB                                | 1         | 1.56%   |
| SanDisk SD7TB3Q-256G-1006 256GB SSD                  | 1         | 1.56%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD                  | 1         | 1.56%   |
| SanDisk NVMe SSD Drive 512GB                         | 1         | 1.56%   |
| SanDisk Extreme 55AE 2TB SSD                         | 1         | 1.56%   |
| Samsung SSD PM830 mSATA 32GB                         | 1         | 1.56%   |
| Samsung SSD PM800 TM 128GB                           | 1         | 1.56%   |
| Samsung SSD 980 PRO 1TB                              | 1         | 1.56%   |
| Samsung SSD 860 EVO 250GB                            | 1         | 1.56%   |
| Samsung SSD 850 EVO 250GB                            | 1         | 1.56%   |
| Samsung SSD 830 Series 512GB                         | 1         | 1.56%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 1         | 1.56%   |
| Samsung PM9A1 NVMe 512GB                             | 1         | 1.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 1         | 1.56%   |
| Samsung MZVL2512HCJQ-00B00 512GB                     | 1         | 1.56%   |
| Samsung MZNLN512HAJQ-00000 512GB SSD                 | 1         | 1.56%   |
| Samsung MZALQ512HBLU-00BL2 512GB                     | 1         | 1.56%   |
| Samsung MZALQ512HALU-000L2 512GB                     | 1         | 1.56%   |
| Samsung MZALQ256HBJD-00BL1 256GB                     | 1         | 1.56%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD                 | 1         | 1.56%   |
| Phison HYPERPC-SSD2000GP50 2TB                       | 1         | 1.56%   |
| Phison 311CD0512GB                                   | 1         | 1.56%   |
| Netac SSD 256GB                                      | 1         | 1.56%   |
| Micron 1100 SATA 512GB SSD                           | 1         | 1.56%   |
| LITEONIT LMT-32L3M-HP 32GB SSD                       | 1         | 1.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 4      | 57.14%  |
| Seagate | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |
| HGST    | 1         | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 20%     |
| Crucial             | 5         | 5      | 16.67%  |
| SanDisk             | 4         | 5      | 13.33%  |
| Kingston            | 2         | 2      | 6.67%   |
| KingSpec            | 2         | 2      | 6.67%   |
| China               | 2         | 2      | 6.67%   |
| A-DATA Technology   | 2         | 2      | 6.67%   |
| Toshiba             | 1         | 2      | 3.33%   |
| Netac               | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| LITEONIT            | 1         | 1      | 3.33%   |
| Kston               | 1         | 1      | 3.33%   |
| Intenso             | 1         | 1      | 3.33%   |
| Apple               | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 24        | 33     | 44.44%  |
| NVMe    | 20        | 26     | 37.04%  |
| HDD     | 6         | 7      | 11.11%  |
| MMC     | 2         | 2      | 3.7%    |
| Unknown | 2         | 2      | 3.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 40     | 55.56%  |
| NVMe | 19        | 25     | 35.19%  |
| SAS  | 3         | 3      | 5.56%   |
| MMC  | 2         | 2      | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 30     | 70.59%  |
| 0.51-1.0   | 8         | 8      | 23.53%  |
| 1.01-2.0   | 2         | 2      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 38%     |
| 251-500        | 10        | 20%     |
| 1-20           | 5         | 10%     |
| 1001-2000      | 4         | 8%      |
| 21-50          | 3         | 6%      |
| 501-1000       | 3         | 6%      |
| 2001-3000      | 2         | 4%      |
| 51-100         | 2         | 4%      |
| More than 3000 | 1         | 2%      |
| Unknown        | 1         | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 15        | 29.41%  |
| 21-50     | 10        | 19.61%  |
| 101-250   | 8         | 15.69%  |
| 51-100    | 8         | 15.69%  |
| 1001-2000 | 3         | 5.88%   |
| 501-1000  | 3         | 5.88%   |
| 251-500   | 2         | 3.92%   |
| 2001-3000 | 1         | 1.96%   |
| Unknown   | 1         | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model           | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| Netac SSD 256GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| Netac  | 1         | 1      | 100%    |

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
| SSD  | 1         | 1      | 100%    |

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
| Works    | 34        | 44     | 61.82%  |
| Detected | 20        | 25     | 36.36%  |
| Malfunc  | 1         | 1      | 1.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 34        | 54.84%  |
| Samsung Electronics          | 7         | 11.29%  |
| AMD                          | 7         | 11.29%  |
| Phison Electronics           | 3         | 4.84%   |
| Toshiba America Info Systems | 2         | 3.23%   |
| SanDisk                      | 2         | 3.23%   |
| KIOXIA                       | 2         | 3.23%   |
| Union Memory (Shenzhen)      | 1         | 1.61%   |
| SK hynix                     | 1         | 1.61%   |
| Nvidia                       | 1         | 1.61%   |
| Marvell Technology Group     | 1         | 1.61%   |
| Lenovo                       | 1         | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 8.96%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 8.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 5         | 7.46%   |
| Samsung NVMe SSD Controller 980                                                        | 4         | 5.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 4.48%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 4.48%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 4.48%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 2.99%   |
| Phison E16 PCIe4 NVMe Controller                                                       | 2         | 2.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 2.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 2.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 2.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 2.99%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 1.49%   |
| Toshiba America Info Systems Toshiba America Info SATA controller                      | 1         | 1.49%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 1.49%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 1.49%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.49%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.49%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 1         | 1.49%   |
| Lenovo Non-Volatile memory controller                                                  | 1         | 1.49%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 1.49%   |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 1.49%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 1         | 1.49%   |
| Intel SSD 660P Series                                                                  | 1         | 1.49%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 1         | 1.49%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 1.49%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.49%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.49%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.49%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.49%   |
| AMD IXP SB4x0 Serial ATA Controller                                                    | 1         | 1.49%   |
| AMD IXP SB4x0 IDE Controller                                                           | 1         | 1.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 35        | 54.69%  |
| NVMe | 19        | 29.69%  |
| RAID | 8         | 12.5%   |
| IDE  | 2         | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 40        | 81.63%  |
| AMD    | 9         | 18.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-3517U CPU @ 1.90GHz               | 3         | 6.12%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 3         | 6.12%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 1         | 2.04%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 2.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 2.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 2.04%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 2.04%   |
| Intel Core i7-3720QM CPU @ 2.60GHz              | 1         | 2.04%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 1         | 2.04%   |
| Intel Core i7 CPU X 920 @ 2.00GHz               | 1         | 2.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 2.04%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz              | 1         | 2.04%   |
| Intel Core i5-4300Y CPU @ 1.60GHz               | 1         | 2.04%   |
| Intel Core i5-4250U CPU @ 1.30GHz               | 1         | 2.04%   |
| Intel Core i5-3380M CPU @ 2.90GHz               | 1         | 2.04%   |
| Intel Core i5-2540M CPU @ 2.60GHz               | 1         | 2.04%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1         | 2.04%   |
| Intel Core i5 CPU M 560 @ 2.67GHz               | 1         | 2.04%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 1         | 2.04%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 1         | 2.04%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 1         | 2.04%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 1         | 2.04%   |
| Intel Core 2 Duo CPU U9600 @ 1.60GHz            | 1         | 2.04%   |
| Intel Core 2 Duo CPU T9550 @ 2.66GHz            | 1         | 2.04%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 1         | 2.04%   |
| Intel Celeron N5100 @ 1.10GHz                   | 1         | 2.04%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 1         | 2.04%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 2.04%   |
| Intel Celeron CPU N3450 @ 1.10GHz               | 1         | 2.04%   |
| Intel Celeron CPU N2830 @ 2.16GHz               | 1         | 2.04%   |
| Intel 11th Gen Core i9-11980HK @ 2.60GHz        | 1         | 2.04%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz         | 1         | 2.04%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 1         | 2.04%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz         | 1         | 2.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 2.04%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 1         | 2.04%   |
| AMD Turion 64 Mobile Technology MK-38           | 1         | 2.04%   |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 1         | 2.04%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 1         | 2.04%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Other                | 9         | 18.37%  |
| Intel Core i7        | 9         | 18.37%  |
| Intel Core i5        | 9         | 18.37%  |
| Intel Celeron        | 5         | 10.2%   |
| Intel Core i3        | 3         | 6.12%   |
| Intel Core 2 Duo     | 3         | 6.12%   |
| Intel Pentium        | 2         | 4.08%   |
| AMD Turion 64 Mobile | 1         | 2.04%   |
| AMD Ryzen 9          | 1         | 2.04%   |
| AMD Ryzen 7 PRO      | 1         | 2.04%   |
| AMD Ryzen 7          | 1         | 2.04%   |
| AMD Ryzen 5          | 1         | 2.04%   |
| AMD Ryzen 3          | 1         | 2.04%   |
| AMD E1               | 1         | 2.04%   |
| AMD A8               | 1         | 2.04%   |
| AMD A4               | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 44.9%   |
| 4      | 21        | 42.86%  |
| 8      | 4         | 8.16%   |
| 6      | 1         | 2.04%   |
| 1      | 1         | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 49        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 34        | 69.39%  |
| 1      | 15        | 30.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 49        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 34.62%  |
| 0x806c1    | 4         | 7.69%   |
| 0x306a9    | 4         | 7.69%   |
| 0x806d1    | 3         | 5.77%   |
| 0x706e5    | 2         | 3.85%   |
| 0x706a8    | 2         | 3.85%   |
| 0x506c9    | 2         | 3.85%   |
| 0x1067a    | 2         | 3.85%   |
| 0x906c0    | 1         | 1.92%   |
| 0x806ec    | 1         | 1.92%   |
| 0x806eb    | 1         | 1.92%   |
| 0x806ea    | 1         | 1.92%   |
| 0x806e9    | 1         | 1.92%   |
| 0x506e3    | 1         | 1.92%   |
| 0x40651    | 1         | 1.92%   |
| 0x206a7    | 1         | 1.92%   |
| 0x20655    | 1         | 1.92%   |
| 0x0a50000c | 1         | 1.92%   |
| 0x08608103 | 1         | 1.92%   |
| 0x08108109 | 1         | 1.92%   |
| 0x08101016 | 1         | 1.92%   |
| 0x07030105 | 1         | 1.92%   |
| 0x0700010f | 1         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 7         | 14%     |
| TigerLake     | 6         | 12%     |
| IceLake       | 5         | 10%     |
| KabyLake      | 4         | 8%      |
| Penryn        | 3         | 6%      |
| Unknown       | 3         | 6%      |
| Westmere      | 2         | 4%      |
| Silvermont    | 2         | 4%      |
| Haswell       | 2         | 4%      |
| Goldmont plus | 2         | 4%      |
| Goldmont      | 2         | 4%      |
| Zen+          | 1         | 2%      |
| Zen 3         | 1         | 2%      |
| Zen 2         | 1         | 2%      |
| Zen           | 1         | 2%      |
| Skylake       | 1         | 2%      |
| SandyBridge   | 1         | 2%      |
| Puma          | 1         | 2%      |
| Nehalem       | 1         | 2%      |
| K8 Hammer     | 1         | 2%      |
| Jaguar        | 1         | 2%      |
| Excavator     | 1         | 2%      |
| Broadwell     | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 35        | 59.32%  |
| Nvidia | 12        | 20.34%  |
| AMD    | 12        | 20.34%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                              | Notebooks | Percent |
|------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                   | 6         | 10.17%  |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                          | 5         | 8.47%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                    | 2         | 3.39%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                               | 2         | 3.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                       | 2         | 3.39%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                             | 2         | 3.39%   |
| Intel GeminiLake [UHD Graphics 600]                                                | 2         | 3.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                       | 2         | 3.39%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                         | 1         | 1.69%   |
| Nvidia GT216M [GeForce GT 330M]                                                    | 1         | 1.69%   |
| Nvidia GK107M [GeForce GT 650M]                                                    | 1         | 1.69%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                        | 1         | 1.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]               | 1         | 1.69%   |
| Nvidia GF108M [GeForce GT 635M]                                                    | 1         | 1.69%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                           | 1         | 1.69%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                                 | 1         | 1.69%   |
| Nvidia G92GLM [Quadro FX 2800M]                                                    | 1         | 1.69%   |
| Nvidia C79 [GeForce 9400M]                                                         | 1         | 1.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                         | 1         | 1.69%   |
| Intel UHD Graphics 620                                                             | 1         | 1.69%   |
| Intel Tiger Lake UHD Graphics                                                      | 1         | 1.69%   |
| Intel JasperLake [UHD Graphics]                                                    | 1         | 1.69%   |
| Intel HD Graphics 620                                                              | 1         | 1.69%   |
| Intel HD Graphics 5500                                                             | 1         | 1.69%   |
| Intel HD Graphics 530                                                              | 1         | 1.69%   |
| Intel HD Graphics 500                                                              | 1         | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                   | 1         | 1.69%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                   | 1         | 1.69%   |
| Intel Core Processor Integrated Graphics Controller                                | 1         | 1.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                               | 1         | 1.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller | 1         | 1.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller          | 1         | 1.69%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]      | 1         | 1.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                           | 1         | 1.69%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                            | 1         | 1.69%   |
| AMD Renoir                                                                         | 1         | 1.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                   | 1         | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]               | 1         | 1.69%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                | 1         | 1.69%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                   | 1         | 1.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 55.1%   |
| 1 x AMD        | 8         | 16.33%  |
| Intel + Nvidia | 6         | 12.24%  |
| 1 x Nvidia     | 4         | 8.16%   |
| Intel + AMD    | 2         | 4.08%   |
| AMD + Nvidia   | 2         | 4.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 43        | 87.76%  |
| Proprietary | 6         | 12.24%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 76%     |
| 0.51-1.0   | 4         | 8%      |
| 0.01-0.5   | 4         | 8%      |
| 1.01-2.0   | 3         | 6%      |
| 5.01-6.0   | 1         | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 10        | 17.86%  |
| BOE                     | 9         | 16.07%  |
| Samsung Electronics     | 6         | 10.71%  |
| LG Display              | 6         | 10.71%  |
| AU Optronics            | 4         | 7.14%   |
| Apple                   | 4         | 7.14%   |
| Chi Mei Optoelectronics | 2         | 3.57%   |
| AOC                     | 2         | 3.57%   |
| ViewSonic               | 1         | 1.79%   |
| Toshiba                 | 1         | 1.79%   |
| Sony                    | 1         | 1.79%   |
| Sharp                   | 1         | 1.79%   |
| Sceptre Tech            | 1         | 1.79%   |
| Philips                 | 1         | 1.79%   |
| PANDA                   | 1         | 1.79%   |
| Lenovo                  | 1         | 1.79%   |
| Iiyama                  | 1         | 1.79%   |
| Hitachi                 | 1         | 1.79%   |
| HannStar                | 1         | 1.79%   |
| CS_                     | 1         | 1.79%   |
| BenQ                    | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 2         | 3.57%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                   | 2         | 3.57%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 598x336mm 27.0-inch            | 1         | 1.79%   |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch                 | 1         | 1.79%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 1         | 1.79%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 1.79%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                   | 1         | 1.79%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 480x270mm 21.7-inch       | 1         | 1.79%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC5044 1920x1080 382x215mm 17.3-inch    | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 1         | 1.79%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                      | 1         | 1.79%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 1         | 1.79%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch              | 1         | 1.79%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 1         | 1.79%   |
| Iiyama PL2773H IVM660A 1920x1080 600x340mm 27.2-inch                     | 1         | 1.79%   |
| Hitachi HISENSE HEC0030 3840x2160 1095x616mm 49.5-inch                   | 1         | 1.79%   |
| HannStar Hanns.G Hi221 HSD2469 1680x1050 474x297mm 22.0-inch             | 1         | 1.79%   |
| CS_ LCD Monitor CS_5211 1366x768 518x333mm 24.2-inch                     | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN174A 1920x1080 381x214mm 17.2-inch         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch          | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x193mm 15.5-inch          | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN14E8 1920x1080 309x173mm 13.9-inch         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 282x165mm 12.9-inch         | 1         | 1.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 1         | 1.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO1409 1280x800 303x190mm 14.1-inch | 1         | 1.79%   |
| BOE LCD Monitor BOE09BA 2560x1600 345x215mm 16.0-inch                    | 1         | 1.79%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                    | 1         | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 24        | 44.44%  |
| 1366x768 (WXGA)    | 12        | 22.22%  |
| 1280x800 (WXGA)    | 4         | 7.41%   |
| 1440x900 (WXGA+)   | 3         | 5.56%   |
| 3840x2160 (4K)     | 2         | 3.7%    |
| 2560x1600          | 2         | 3.7%    |
| 2560x1440 (QHD)    | 2         | 3.7%    |
| 2160x1440          | 2         | 3.7%    |
| 3840x2400          | 1         | 1.85%   |
| 1680x1050 (WSXGA+) | 1         | 1.85%   |
| 1600x900 (HD+)     | 1         | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 20        | 35.71%  |
| 13     | 8         | 14.29%  |
| 17     | 7         | 12.5%   |
| 14     | 5         | 8.93%   |
| 27     | 3         | 5.36%   |
| 24     | 2         | 3.57%   |
| 23     | 2         | 3.57%   |
| 21     | 2         | 3.57%   |
| 12     | 2         | 3.57%   |
| 84     | 1         | 1.79%   |
| 25     | 1         | 1.79%   |
| 22     | 1         | 1.79%   |
| 16     | 1         | 1.79%   |
| 11     | 1         | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 51.79%  |
| 501-600     | 8         | 14.29%  |
| 201-300     | 8         | 14.29%  |
| 351-400     | 7         | 12.5%   |
| 401-500     | 3         | 5.36%   |
| 1501-2000   | 1         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 37        | 72.55%  |
| 16/10 | 12        | 23.53%  |
| 3/2   | 2         | 3.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 34.55%  |
| 81-90          | 10        | 18.18%  |
| 121-130        | 6         | 10.91%  |
| 201-250        | 5         | 9.09%   |
| 71-80          | 3         | 5.45%   |
| 301-350        | 3         | 5.45%   |
| 61-70          | 2         | 3.64%   |
| 251-300        | 2         | 3.64%   |
| More than 1000 | 1         | 1.82%   |
| 51-60          | 1         | 1.82%   |
| 131-140        | 1         | 1.82%   |
| 111-120        | 1         | 1.82%   |
| 91-100         | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 19        | 35.19%  |
| 101-120       | 17        | 31.48%  |
| 51-100        | 10        | 18.52%  |
| 161-240       | 7         | 12.96%  |
| More than 240 | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 41        | 83.67%  |
| 2     | 7         | 14.29%  |
| 3     | 1         | 2.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 31        | 43.66%  |
| Realtek Semiconductor             | 22        | 30.99%  |
| Qualcomm Atheros                  | 4         | 5.63%   |
| Broadcom                          | 4         | 5.63%   |
| Ericsson Business Mobile Networks | 2         | 2.82%   |
| Broadcom Limited                  | 2         | 2.82%   |
| ASIX Electronics                  | 2         | 2.82%   |
| Qualcomm Atheros Communications   | 1         | 1.41%   |
| Nvidia                            | 1         | 1.41%   |
| Microchip Technology              | 1         | 1.41%   |
| Marvell Technology Group          | 1         | 1.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 11        | 12.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 4.4%    |
| Intel Wi-Fi 6 AX201                                                            | 4         | 4.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 3.3%    |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3         | 3.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 2.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 2.2%    |
| Intel Wireless 8265 / 8275                                                     | 2         | 2.2%    |
| Intel Wireless 3165                                                            | 2         | 2.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 2.2%    |
| Intel Wi-Fi 6 AX200                                                            | 2         | 2.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2         | 2.2%    |
| Intel Centrino Wireless-N 2230                                                 | 2         | 2.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 2.2%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 2.2%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                        | 1         | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1         | 1.1%    |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.1%    |
| Realtek 802.11ac NIC                                                           | 1         | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1         | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 1.1%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 1.1%    |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 1.1%    |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.1%    |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 1.1%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.1%    |
| Intel Wireless 8260                                                            | 1         | 1.1%    |
| Intel Wireless 7265                                                            | 1         | 1.1%    |
| Intel Wireless 7260                                                            | 1         | 1.1%    |
| Intel Wireless 3160                                                            | 1         | 1.1%    |
| Intel WiFi Link 5100                                                           | 1         | 1.1%    |
| Intel Wi-Fi 6 AX201 160MHz                                                     | 1         | 1.1%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 1         | 1.1%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 1.1%    |
| Intel I210 Gigabit Network Connection                                          | 1         | 1.1%    |
| Intel Gemini Lake PCH CNVi WiFi                                                | 1         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.1%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 59.62%  |
| Realtek Semiconductor           | 11        | 21.15%  |
| Qualcomm Atheros                | 4         | 7.69%   |
| Broadcom                        | 3         | 5.77%   |
| Broadcom Limited                | 2         | 3.85%   |
| Qualcomm Atheros Communications | 1         | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 4         | 7.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 5.77%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 5.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.85%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.85%   |
| Intel Wireless 3165                                                     | 2         | 3.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 3.85%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 3.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 3.85%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 3.85%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.92%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.92%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.92%   |
| Intel Wireless 8260                                                     | 1         | 1.92%   |
| Intel Wireless 7265                                                     | 1         | 1.92%   |
| Intel Wireless 7260                                                     | 1         | 1.92%   |
| Intel Wireless 3160                                                     | 1         | 1.92%   |
| Intel WiFi Link 5100                                                    | 1         | 1.92%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.92%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.92%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.92%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.92%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.92%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 1.92%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 1.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 1.92%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 18        | 50%     |
| Intel                    | 9         | 25%     |
| Broadcom                 | 3         | 8.33%   |
| ASIX Electronics         | 2         | 5.56%   |
| Qualcomm Atheros         | 1         | 2.78%   |
| Nvidia                   | 1         | 2.78%   |
| Microchip Technology     | 1         | 2.78%   |
| Marvell Technology Group | 1         | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 11        | 29.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 10.81%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 5.41%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 5.41%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 2.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 2.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 2.7%    |
| Nvidia MCP79 Ethernet                                                          | 1         | 2.7%    |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 2.7%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 2.7%    |
| Intel I210 Gigabit Network Connection                                          | 1         | 2.7%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 2.7%    |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 2.7%    |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 2.7%    |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 2.7%    |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 2.7%    |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 2.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 2.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 2.7%    |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 56.32%  |
| Ethernet | 36        | 41.38%  |
| Modem    | 2         | 2.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 75.44%  |
| Ethernet | 14        | 24.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 32        | 65.31%  |
| 1     | 17        | 34.69%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 59.18%  |
| Yes  | 20        | 40.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 54.55%  |
| Realtek Semiconductor           | 6         | 13.64%  |
| Apple                           | 4         | 9.09%   |
| Broadcom                        | 3         | 6.82%   |
| IMC Networks                    | 2         | 4.55%   |
| Toshiba                         | 1         | 2.27%   |
| Qualcomm Atheros Communications | 1         | 2.27%   |
| Hewlett-Packard                 | 1         | 2.27%   |
| Foxconn / Hon Hai               | 1         | 2.27%   |
| Cambridge Silicon Radio         | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 8         | 18.18%  |
| Realtek Bluetooth Radio                                                             | 6         | 13.64%  |
| Intel Bluetooth wireless interface                                                  | 6         | 13.64%  |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 6.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 6.82%   |
| Intel AX210 Bluetooth                                                               | 2         | 4.55%   |
| Intel AX200 Bluetooth                                                               | 2         | 4.55%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 4.55%   |
| Apple Bluetooth Host Controller                                                     | 2         | 4.55%   |
| Toshiba Bluetooth Device                                                            | 1         | 2.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 2.27%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 2.27%   |
| IMC Networks Bluetooth Device                                                       | 1         | 2.27%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 2.27%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 2.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 2.27%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 2.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 2.27%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 39        | 61.9%   |
| Nvidia                 | 10        | 15.87%  |
| AMD                    | 10        | 15.87%  |
| C-Media Electronics    | 2         | 3.17%   |
| Meizu                  | 1         | 1.59%   |
| Generalplus Technology | 1         | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 9.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 8.22%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5         | 6.85%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 4.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 4.11%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 2.74%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 2.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 2.74%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.74%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 2.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.74%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.74%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 2.74%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.37%   |
| Nvidia stereo controller                                                   | 1         | 1.37%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.37%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.37%   |
| Meizu HiFi DAC Headphone Amplifier                                         | 1         | 1.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.37%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.37%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.37%   |
| Generalplus Technology USB Audio Device                                    | 1         | 1.37%   |
| C-Media Electronics USB Advanced Audio Device                              | 1         | 1.37%   |
| C-Media Electronics Audio Adapter                                          | 1         | 1.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.37%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.37%   |
| AMD IXP SB4x0 High Definition Audio Controller                             | 1         | 1.37%   |
| AMD High Definition Audio Controller                                       | 1         | 1.37%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 12        | 26.09%  |
| Samsung Electronics | 10        | 21.74%  |
| Micron Technology   | 6         | 13.04%  |
| Kingston            | 5         | 10.87%  |
| Unknown (ABCD)      | 4         | 8.7%    |
| Unknown             | 4         | 8.7%    |
| G.Skill             | 2         | 4.35%   |
| Crucial             | 2         | 4.35%   |
| Nanya Technology    | 1         | 2.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 8%      |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 6%      |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 4%      |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 2%      |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 2%      |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 2%      |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 2%      |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 2%      |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 2%      |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 2%      |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2%      |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2%      |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2%      |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 2%      |
| SK hynix RAM HMT351S6BFR8C-G7 4GB SODIMM DDR3 1067MT/s           | 1         | 2%      |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 2%      |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 2%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2%      |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 2%      |
| Samsung RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 2%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2%      |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2%      |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2%      |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 2%      |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 1         | 2%      |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2%      |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2%      |
| Nanya RAM NT4GC64B8HB0NS-CG 4096MB SODIMM DDR3 1334MT/s          | 1         | 2%      |
| Micron RAM Module 8GB SODIMM DDR4 2400MT/s                       | 1         | 2%      |
| Micron RAM 8ATF2G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 2%      |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 1         | 2%      |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s   | 1         | 2%      |
| Micron RAM 53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 3200MT/s   | 1         | 2%      |
| Micron RAM 16ATF1G64HZ-2G1A2 8GB Chip DDR4 2133MT/s              | 1         | 2%      |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 2%      |
| Kingston RAM KP6FH5-MIE 32GB SODIMM DDR4 3200MT/s                | 1         | 2%      |
| Kingston RAM KF3200C20S4/16GX 16GB SODIMM DDR4 3200MT/s          | 1         | 2%      |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s          | 1         | 2%      |
| Kingston RAM 9905700-104.A00G 8GB SODIMM DDR4 3200MT/s           | 1         | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 19        | 51.35%  |
| DDR3   | 11        | 29.73%  |
| LPDDR4 | 6         | 16.22%  |
| DDR2   | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 32        | 78.05%  |
| Row Of Chips | 8         | 19.51%  |
| Chip         | 1         | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 19        | 44.19%  |
| 8192  | 15        | 34.88%  |
| 16384 | 4         | 9.3%    |
| 32768 | 2         | 4.65%   |
| 2048  | 2         | 4.65%   |
| 1024  | 1         | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 13        | 31.71%  |
| 2400    | 8         | 19.51%  |
| 1600    | 7         | 17.07%  |
| 2667    | 5         | 12.2%   |
| Unknown | 2         | 4.88%   |
| 4267    | 1         | 2.44%   |
| 2133    | 1         | 2.44%   |
| 1867    | 1         | 2.44%   |
| 1334    | 1         | 2.44%   |
| 1067    | 1         | 2.44%   |
| 1066    | 1         | 2.44%   |

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
| Chicony Electronics                    | 12        | 27.27%  |
| Realtek Semiconductor                  | 5         | 11.36%  |
| Syntek                                 | 3         | 6.82%   |
| Microdia                               | 3         | 6.82%   |
| Apple                                  | 3         | 6.82%   |
| Sunplus Innovation Technology          | 2         | 4.55%   |
| Quanta                                 | 2         | 4.55%   |
| Luxvisions Innotech Limited            | 2         | 4.55%   |
| IMC Networks                           | 2         | 4.55%   |
| Acer                                   | 2         | 4.55%   |
| U0AS01A-0                              | 1         | 2.27%   |
| Suyin                                  | 1         | 2.27%   |
| Ricoh                                  | 1         | 2.27%   |
| Lite-On Technology                     | 1         | 2.27%   |
| Lenovo                                 | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.27%   |
| ARC International                      | 1         | 2.27%   |
| Alcor Micro                            | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                | 3         | 6.82%   |
| Realtek MTD camera                                      | 2         | 4.55%   |
| Microdia Webcam Vitade AF                               | 2         | 4.55%   |
| Luxvisions Innotech Limited Integrated Camera           | 2         | 4.55%   |
| Apple Built-in iSight                                   | 2         | 4.55%   |
| U0AS01A-0 U0AS01A-0                                     | 1         | 2.27%   |
| Suyin USB 2.0 Camera                                    | 1         | 2.27%   |
| Sunplus Integrated_Webcam_FHD                           | 1         | 2.27%   |
| Sunplus HP Truevision HD                                | 1         | 2.27%   |
| Ricoh Dell Laptop Integrated Webcam                     | 1         | 2.27%   |
| Realtek USB Camera                                      | 1         | 2.27%   |
| Realtek Laptop_Integrated_Webcam_HD                     | 1         | 2.27%   |
| Realtek Integrated_Webcam_HD                            | 1         | 2.27%   |
| Quanta ov9734_techfront_camera                          | 1         | 2.27%   |
| Quanta HD User Facing                                   | 1         | 2.27%   |
| Microdia Integrated_Webcam_2M                           | 1         | 2.27%   |
| Lite-On HP HD Webcam                                    | 1         | 2.27%   |
| Lenovo CNF7237&CNF7238                                  | 1         | 2.27%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 1         | 2.27%   |
| IMC Networks Integrated Camera                          | 1         | 2.27%   |
| Chicony USB2.0 VGA UVC WebCam                           | 1         | 2.27%   |
| Chicony USB2.0 Camera                                   | 1         | 2.27%   |
| Chicony USB 2.0 Camera                                  | 1         | 2.27%   |
| Chicony TOSHIBA Web Camera - HD                         | 1         | 2.27%   |
| Chicony LG Camera                                       | 1         | 2.27%   |
| Chicony Integrated HP HD Webcam                         | 1         | 2.27%   |
| Chicony Integrated Camera [ThinkPad]                    | 1         | 2.27%   |
| Chicony Integrated Camera                               | 1         | 2.27%   |
| Chicony HP Webcam                                       | 1         | 2.27%   |
| Chicony HP Truevision HD                                | 1         | 2.27%   |
| Chicony HP HD Camera                                    | 1         | 2.27%   |
| Chicony HD Webcam                                       | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 1         | 2.27%   |
| ARC International Camera                                | 1         | 2.27%   |
| Apple FaceTime HD Camera                                | 1         | 2.27%   |
| Alcor Micro USB 2.0 WebCamera                           | 1         | 2.27%   |
| Acer Orbicam                                            | 1         | 2.27%   |
| Acer Integrated Camera                                  | 1         | 2.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 50%     |
| Validity Sensors           | 3         | 37.5%   |
| Upek                       | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                    | 4         | 50%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 12.5%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 4         | 57.14%  |
| SCM Microsystems      | 1         | 14.29%  |
| Alcor Micro           | 1         | 14.29%  |
| Advanced Card Systems | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 28.57%  |
| Broadcom 58200                                                               | 2         | 28.57%  |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 14.29%  |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 32        | 64%     |
| 1     | 13        | 26%     |
| 2     | 4         | 8%      |
| 3     | 1         | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 38.1%   |
| Chipcard              | 7         | 33.33%  |
| Net/wireless          | 1         | 4.76%   |
| Multimedia controller | 1         | 4.76%   |
| Graphics card         | 1         | 4.76%   |
| Flash memory          | 1         | 4.76%   |
| Camera                | 1         | 4.76%   |
| Bluetooth             | 1         | 4.76%   |

