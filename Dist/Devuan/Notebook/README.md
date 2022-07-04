Devuan - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Devuan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 55

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T430 2349I46       | [3a7df4ea17](https://linux-hardware.org/?probe=3a7df4ea17) | Jun 20, 2022 |
| HP            | Laptop 17-cp0xxx            | [001634b95b](https://linux-hardware.org/?probe=001634b95b) | Jun 17, 2022 |
| Dell          | Latitude E6430              | [95b7617708](https://linux-hardware.org/?probe=95b7617708) | Jun 05, 2022 |
| Acer          | Aspire E5-553G              | [2d4c950e2f](https://linux-hardware.org/?probe=2d4c950e2f) | May 25, 2022 |
| Acer          | Aspire E5-553G              | [73139cdb17](https://linux-hardware.org/?probe=73139cdb17) | May 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [2717caa7f5](https://linux-hardware.org/?probe=2717caa7f5) | Apr 25, 2022 |
| HP            | Notebook                    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Lenovo        | ThinkPad T470s 20HGS00P0... | [2c9878c68b](https://linux-hardware.org/?probe=2c9878c68b) | Apr 13, 2022 |
| Dell          | Latitude E5540              | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [a3aed9d375](https://linux-hardware.org/?probe=a3aed9d375) | Mar 03, 2022 |
| ASUSTek       | K55VJ                       | [562262b9eb](https://linux-hardware.org/?probe=562262b9eb) | Jan 22, 2022 |
| ASUSTek       | X555LJ                      | [9fbdf4dfc2](https://linux-hardware.org/?probe=9fbdf4dfc2) | Jan 17, 2022 |
| Lenovo        | ThinkPad T420 4180AG3       | [2c3cd27ad2](https://linux-hardware.org/?probe=2c3cd27ad2) | Jan 16, 2022 |
| Notebook      | W230ST                      | [3dacf0aea8](https://linux-hardware.org/?probe=3dacf0aea8) | Jan 15, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [899cb98778](https://linux-hardware.org/?probe=899cb98778) | Dec 06, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK U7510              | [d43a6a6bb8](https://linux-hardware.org/?probe=d43a6a6bb8) | Nov 29, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [55689e67b3](https://linux-hardware.org/?probe=55689e67b3) | Oct 27, 2021 |
| Lenovo        | ThinkPad X230 2325DE0       | [991007e92a](https://linux-hardware.org/?probe=991007e92a) | Oct 13, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [7f1b3371a9](https://linux-hardware.org/?probe=7f1b3371a9) | Oct 03, 2021 |
| Toshiba       | Satellite M40X              | [61fea93e97](https://linux-hardware.org/?probe=61fea93e97) | Oct 01, 2021 |
| Acer          | Aspire 5250                 | [ae41600fd9](https://linux-hardware.org/?probe=ae41600fd9) | Sep 24, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | [04747e3df4](https://linux-hardware.org/?probe=04747e3df4) | Sep 19, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | [134b90f474](https://linux-hardware.org/?probe=134b90f474) | Sep 18, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | [04256a6e0a](https://linux-hardware.org/?probe=04256a6e0a) | Aug 25, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | [dffbcc492c](https://linux-hardware.org/?probe=dffbcc492c) | Aug 25, 2021 |
| ASUSTek       | K52F                        | [643e3cc4b3](https://linux-hardware.org/?probe=643e3cc4b3) | Aug 13, 2021 |
| MSI           | MS-1688                     | [0ae772d66b](https://linux-hardware.org/?probe=0ae772d66b) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 429053G       | [5f553465bf](https://linux-hardware.org/?probe=5f553465bf) | Jul 29, 2021 |
| Acer          | Extensa 215-51K             | [1c49c2f4d0](https://linux-hardware.org/?probe=1c49c2f4d0) | Jul 26, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | [fc77801294](https://linux-hardware.org/?probe=fc77801294) | Jun 07, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [aef4e323e2](https://linux-hardware.org/?probe=aef4e323e2) | Jun 06, 2021 |
| ASUSTek       | K55VJ                       | [6fa86f9d25](https://linux-hardware.org/?probe=6fa86f9d25) | Apr 27, 2021 |
| ASUSTek       | K55VJ                       | [aef1b6c71f](https://linux-hardware.org/?probe=aef1b6c71f) | Apr 17, 2021 |
| HP            | ProBook 6475b               | [74b0fa77b5](https://linux-hardware.org/?probe=74b0fa77b5) | Apr 14, 2021 |
| Fujitsu Si... | AMILO Xi 1546               | [22a53eeb74](https://linux-hardware.org/?probe=22a53eeb74) | Apr 03, 2021 |
| Teclast       | F6 Plus                     | [26ac25681a](https://linux-hardware.org/?probe=26ac25681a) | Jan 08, 2021 |
| Dell          | Precision 7530              | [8e0ee186a3](https://linux-hardware.org/?probe=8e0ee186a3) | Dec 04, 2020 |
| Lenovo        | ThinkPad X60 1707YF8        | [bcdd451de1](https://linux-hardware.org/?probe=bcdd451de1) | Oct 31, 2020 |
| Nokia         | N900                        | [7960cb48cc](https://linux-hardware.org/?probe=7960cb48cc) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| Dell          | Precision 7530              | [e6c6dd2734](https://linux-hardware.org/?probe=e6c6dd2734) | Sep 26, 2020 |
| Dell          | Precision 7530              | [81e9306141](https://linux-hardware.org/?probe=81e9306141) | Sep 26, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3d241c321f](https://linux-hardware.org/?probe=3d241c321f) | Sep 20, 2020 |
| ASUSTek       | K52F                        | [cef5147eeb](https://linux-hardware.org/?probe=cef5147eeb) | Aug 30, 2020 |
| Acer          | Aspire 5732Z                | [c4cb936b69](https://linux-hardware.org/?probe=c4cb936b69) | Aug 30, 2020 |
| Toshiba       | Satellite L655              | [6251a9111f](https://linux-hardware.org/?probe=6251a9111f) | Aug 30, 2020 |
| HP            | Pavilion 11 x360 PC         | [0c85729a27](https://linux-hardware.org/?probe=0c85729a27) | Aug 30, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [358be6b820](https://linux-hardware.org/?probe=358be6b820) | Jul 28, 2020 |
| Lenovo        | IdeaPad Z370                | [51e3108708](https://linux-hardware.org/?probe=51e3108708) | Jun 28, 2020 |
| Dell          | Latitude 5501               | [94ec8d2a1d](https://linux-hardware.org/?probe=94ec8d2a1d) | Jun 28, 2020 |
| Lenovo        | IdeaPad Z370                | [76c985ed75](https://linux-hardware.org/?probe=76c985ed75) | Jun 27, 2020 |
| Dell          | Latitude E7250              | [c2ca61e7bf](https://linux-hardware.org/?probe=c2ca61e7bf) | Jun 23, 2020 |
| Dell          | Inspiron 1564               | [b80e556643](https://linux-hardware.org/?probe=b80e556643) | Feb 02, 2020 |
| MTC           | Montara-GML                 | [227bf1ba1d](https://linux-hardware.org/?probe=227bf1ba1d) | Dec 07, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Devuan 4                | 18        | 38.3%   |
| Devuan 3                | 14        | 29.79%  |
| Devuan Testing/unstable | 8         | 17.02%  |
| Devuan 5                | 3         | 6.38%   |
| Devuan                  | 2         | 4.26%   |
| Devuan 3.0              | 1         | 2.13%   |
| Devuan 2.1              | 1         | 2.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Devuan | 43        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.10.0-13-amd64           | 4         | 8.16%   |
| 4.19.0-9-amd64            | 4         | 8.16%   |
| 5.7.0-2-amd64             | 3         | 6.12%   |
| 5.10.0-9-amd64            | 3         | 6.12%   |
| 5.10.0-8-amd64            | 3         | 6.12%   |
| 5.10.0-10-amd64           | 3         | 6.12%   |
| 5.10.0-11-amd64           | 2         | 4.08%   |
| 4.19.0-17-amd64           | 2         | 4.08%   |
| 4.19.0-16-amd64           | 2         | 4.08%   |
| 4.19.0-14-amd64           | 2         | 4.08%   |
| 5.9.0-4-amd64             | 1         | 2.04%   |
| 5.8.0-1-amd64             | 1         | 2.04%   |
| 5.7.0-0.bpo.2-amd64       | 1         | 2.04%   |
| 5.6.0-2-amd64             | 1         | 2.04%   |
| 5.18.0-1-amd64            | 1         | 2.04%   |
| 5.15.5-xanmod1            | 1         | 2.04%   |
| 5.15.0-2-amd64            | 1         | 2.04%   |
| 5.14.0-4-amd64            | 1         | 2.04%   |
| 5.10.0-7-amd64            | 1         | 2.04%   |
| 5.10.0-4-amd64            | 1         | 2.04%   |
| 5.10.0-14-amd64           | 1         | 2.04%   |
| 5.10.0-1-amd64            | 1         | 2.04%   |
| 5.1.21                    | 1         | 2.04%   |
| 4.9.0-14-amd64            | 1         | 2.04%   |
| 4.9.0-11-amd64            | 1         | 2.04%   |
| 4.9.0-11-686              | 1         | 2.04%   |
| 4.9.0-0.bpo.4-686-pae     | 1         | 2.04%   |
| 4.4.195-antix.1-amd64-smp | 1         | 2.04%   |
| 4.19.0-17-686-pae         | 1         | 2.04%   |
| 4.19.0-12-amd64           | 1         | 2.04%   |
| 4.19.0-10-amd64           | 1         | 2.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 18        | 37.5%   |
| 4.19.0  | 13        | 27.08%  |
| 5.7.0   | 4         | 8.33%   |
| 4.9.0   | 4         | 8.33%   |
| 5.9.0   | 1         | 2.08%   |
| 5.8.0   | 1         | 2.08%   |
| 5.6.0   | 1         | 2.08%   |
| 5.18.0  | 1         | 2.08%   |
| 5.15.5  | 1         | 2.08%   |
| 5.15.0  | 1         | 2.08%   |
| 5.14.0  | 1         | 2.08%   |
| 5.1.21  | 1         | 2.08%   |
| 4.4.195 | 1         | 2.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 18        | 37.5%   |
| 4.19    | 13        | 27.08%  |
| 5.7     | 4         | 8.33%   |
| 4.9     | 4         | 8.33%   |
| 5.15    | 2         | 4.17%   |
| 5.9     | 1         | 2.08%   |
| 5.8     | 1         | 2.08%   |
| 5.6     | 1         | 2.08%   |
| 5.18    | 1         | 2.08%   |
| 5.14    | 1         | 2.08%   |
| 5.1     | 1         | 2.08%   |
| 4.4     | 1         | 2.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 39        | 90.7%   |
| i686   | 3         | 6.98%   |
| armv7l | 1         | 2.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| XFCE     | 17        | 36.96%  |
| KDE5     | 9         | 19.57%  |
| MATE     | 6         | 13.04%  |
| Unknown  | 6         | 13.04%  |
| i3       | 3         | 6.52%   |
| LXDE     | 2         | 4.35%   |
| Openbox  | 1         | 2.17%   |
| LXQt     | 1         | 2.17%   |
| Cinnamon | 1         | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 41        | 93.18%  |
| Unknown | 2         | 4.55%   |
| Tty     | 1         | 2.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 14        | 30.43%  |
| SLiM    | 13        | 28.26%  |
| LightDM | 13        | 28.26%  |
| SDDM    | 5         | 10.87%  |
| XDM     | 1         | 2.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 16        | 36.36%  |
| en_GB       | 11        | 25%     |
| ru_RU       | 6         | 13.64%  |
| pt_BR       | 2         | 4.55%   |
| Unknown     | 2         | 4.55%   |
| pl_PL       | 1         | 2.27%   |
| it_IT       | 1         | 2.27%   |
| fr_BE       | 1         | 2.27%   |
| es_SV       | 1         | 2.27%   |
| en_US.utf-8 | 1         | 2.27%   |
| de_AT       | 1         | 2.27%   |
| C           | 1         | 2.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 24        | 54.55%  |
| EFI  | 20        | 45.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 36        | 83.72%  |
| Unknown | 3         | 6.98%   |
| Btrfs   | 2         | 4.65%   |
| OveXlay | 1         | 2.33%   |
| Ext2    | 1         | 2.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 21        | 46.67%  |
| MBR     | 17        | 37.78%  |
| Unknown | 7         | 15.56%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 86.05%  |
| Yes       | 6         | 13.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 77.27%  |
| Yes       | 10        | 22.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 14        | 32.56%  |
| Dell                | 6         | 13.95%  |
| Hewlett-Packard     | 4         | 9.3%    |
| Acer                | 4         | 9.3%    |
| ASUSTek Computer    | 3         | 6.98%   |
| Toshiba             | 2         | 4.65%   |
| Fujitsu Siemens     | 2         | 4.65%   |
| Teclast             | 1         | 2.33%   |
| Samsung Electronics | 1         | 2.33%   |
| Notebook            | 1         | 2.33%   |
| Nokia               | 1         | 2.33%   |
| MTC                 | 1         | 2.33%   |
| MSI                 | 1         | 2.33%   |
| IBM                 | 1         | 2.33%   |
| Fujitsu             | 1         | 2.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite M40X                                                                   | 1         | 2.33%   |
| Toshiba Satellite L655                                                                   | 1         | 2.33%   |
| Teclast F6 Plus                                                                          | 1         | 2.33%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 2.33%   |
| Notebook W230ST                                                                          | 1         | 2.33%   |
| Nokia N900                                                                               | 1         | 2.33%   |
| MTC Montara-GML                                                                          | 1         | 2.33%   |
| MSI MS-1688                                                                              | 1         | 2.33%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 2.33%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 2.33%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 2.33%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 2.33%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 2.33%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 2.33%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 2.33%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 2.33%   |
| Lenovo ThinkPad T470s 20HGS00P00                                                         | 1         | 2.33%   |
| Lenovo ThinkPad T430 2349I46                                                             | 1         | 2.33%   |
| Lenovo ThinkPad T420 4180AG3                                                             | 1         | 2.33%   |
| Lenovo IdeaPad Z370                                                                      | 1         | 2.33%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                                                    | 1         | 2.33%   |
| Lenovo IdeaPad 130-15AST 81H5                                                            | 1         | 2.33%   |
| IBM ThinkPad T41p 2373GHG                                                                | 1         | 2.33%   |
| HP ProBook 6475b                                                                         | 1         | 2.33%   |
| HP Pavilion 11 x360 PC                                                                   | 1         | 2.33%   |
| HP Notebook                                                                              | 1         | 2.33%   |
| HP Laptop 17-cp0xxx                                                                      | 1         | 2.33%   |
| Fujitsu Siemens ESPRIMO Mobile V6535                                                     | 1         | 2.33%   |
| Fujitsu Siemens AMILO Xi 1546                                                            | 1         | 2.33%   |
| Fujitsu LIFEBOOK U7510                                                                   | 1         | 2.33%   |
| Dell Precision 7530                                                                      | 1         | 2.33%   |
| Dell Latitude E7250                                                                      | 1         | 2.33%   |
| Dell Latitude E6430                                                                      | 1         | 2.33%   |
| Dell Latitude E5540                                                                      | 1         | 2.33%   |
| Dell Latitude 5501                                                                       | 1         | 2.33%   |
| Dell Inspiron 1564                                                                       | 1         | 2.33%   |
| ASUS X555LJ                                                                              | 1         | 2.33%   |
| ASUS K55VJ                                                                               | 1         | 2.33%   |
| ASUS K52F                                                                                | 1         | 2.33%   |
| Acer Extensa 215-51K                                                                     | 1         | 2.33%   |
| Acer Aspire E5-553G                                                                      | 1         | 2.33%   |
| Acer Aspire 5732Z                                                                        | 1         | 2.33%   |
| Acer Aspire 5250                                                                         | 1         | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 11        | 25.58%  |
| Dell Latitude           | 4         | 9.3%    |
| Lenovo IdeaPad          | 3         | 6.98%   |
| Acer Aspire             | 3         | 6.98%   |
| Toshiba Satellite       | 2         | 4.65%   |
| Teclast F6              | 1         | 2.33%   |
| Samsung 355V4C          | 1         | 2.33%   |
| Notebook W230ST         | 1         | 2.33%   |
| Nokia N900              | 1         | 2.33%   |
| MTC Montara-GML         | 1         | 2.33%   |
| MSI MS-1688             | 1         | 2.33%   |
| IBM ThinkPad            | 1         | 2.33%   |
| HP ProBook              | 1         | 2.33%   |
| HP Pavilion             | 1         | 2.33%   |
| HP Notebook             | 1         | 2.33%   |
| HP Laptop               | 1         | 2.33%   |
| Fujitsu Siemens ESPRIMO | 1         | 2.33%   |
| Fujitsu Siemens AMILO   | 1         | 2.33%   |
| Fujitsu LIFEBOOK        | 1         | 2.33%   |
| Dell Precision          | 1         | 2.33%   |
| Dell Inspiron           | 1         | 2.33%   |
| ASUS X555LJ             | 1         | 2.33%   |
| ASUS K55VJ              | 1         | 2.33%   |
| ASUS K52F               | 1         | 2.33%   |
| Acer Extensa            | 1         | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 7         | 16.28%  |
| 2019    | 5         | 11.63%  |
| 2015    | 4         | 9.3%    |
| 2011    | 4         | 9.3%    |
| 2009    | 3         | 6.98%   |
| 2018    | 2         | 4.65%   |
| 2017    | 2         | 4.65%   |
| 2014    | 2         | 4.65%   |
| 2010    | 2         | 4.65%   |
| 2008    | 2         | 4.65%   |
| 2006    | 2         | 4.65%   |
| 2005    | 2         | 4.65%   |
| 2021    | 1         | 2.33%   |
| 2020    | 1         | 2.33%   |
| 2016    | 1         | 2.33%   |
| 2013    | 1         | 2.33%   |
| 2007    | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 43        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 42        | 97.67%  |
| Enabled  | 1         | 2.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 42        | 97.67%  |
| Yes  | 1         | 2.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 25.58%  |
| 3.01-4.0    | 9         | 20.93%  |
| 8.01-16.0   | 9         | 20.93%  |
| 16.01-24.0  | 5         | 11.63%  |
| 1.01-2.0    | 3         | 6.98%   |
| 2.01-3.0    | 2         | 4.65%   |
| 0.01-0.5    | 2         | 4.65%   |
| 32.01-64.0  | 1         | 2.33%   |
| 64.01-256.0 | 1         | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 18        | 36.73%  |
| 4.01-8.0   | 10        | 20.41%  |
| 2.01-3.0   | 8         | 16.33%  |
| 0.51-1.0   | 5         | 10.2%   |
| 3.01-4.0   | 3         | 6.12%   |
| 0.01-0.5   | 3         | 6.12%   |
| 32.01-64.0 | 1         | 2.04%   |
| 8.01-16.0  | 1         | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 72.09%  |
| 2      | 10        | 23.26%  |
| 3      | 2         | 4.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 59.09%  |
| Yes       | 18        | 40.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 90.7%   |
| No        | 4         | 9.3%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 95.35%  |
| No        | 2         | 4.65%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 55.81%  |
| No        | 19        | 44.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Russia      | 5         | 11.63%  |
| Germany     | 5         | 11.63%  |
| USA         | 4         | 9.3%    |
| Brazil      | 4         | 9.3%    |
| Ukraine     | 3         | 6.98%   |
| Grenada     | 3         | 6.98%   |
| Poland      | 2         | 4.65%   |
| Hungary     | 2         | 4.65%   |
| Finland     | 2         | 4.65%   |
| Vietnam     | 1         | 2.33%   |
| UK          | 1         | 2.33%   |
| Portugal    | 1         | 2.33%   |
| Norway      | 1         | 2.33%   |
| Netherlands | 1         | 2.33%   |
| Mexico      | 1         | 2.33%   |
| Italy       | 1         | 2.33%   |
| Israel      | 1         | 2.33%   |
| Greece      | 1         | 2.33%   |
| France      | 1         | 2.33%   |
| El Salvador | 1         | 2.33%   |
| Belarus     | 1         | 2.33%   |
| Austria     | 1         | 2.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Saint George's     | 3         | 6.98%   |
| Nadudvar           | 2         | 4.65%   |
| Kyiv               | 2         | 4.65%   |
| Yakutsk            | 1         | 2.33%   |
| Wroclaw            | 1         | 2.33%   |
| Trubchëvsk        | 1         | 2.33%   |
| Thessaloniki       | 1         | 2.33%   |
| Tel Aviv           | 1         | 2.33%   |
| Staunton           | 1         | 2.33%   |
| St Petersburg      | 1         | 2.33%   |
| Sao Paulo          | 1         | 2.33%   |
| San Salvador       | 1         | 2.33%   |
| Rio de Janeiro     | 1         | 2.33%   |
| Praia Grande       | 1         | 2.33%   |
| Oslo               | 1         | 2.33%   |
| Novopskov          | 1         | 2.33%   |
| Muenster-Sarmsheim | 1         | 2.33%   |
| Moscow             | 1         | 2.33%   |
| Milan              | 1         | 2.33%   |
| Maladzyechna       | 1         | 2.33%   |
| Leonding           | 1         | 2.33%   |
| Leipzig            | 1         | 2.33%   |
| Kouvola            | 1         | 2.33%   |
| Katzenbach         | 1         | 2.33%   |
| Katowice           | 1         | 2.33%   |
| Jyväskylä        | 1         | 2.33%   |
| Hermosillo         | 1         | 2.33%   |
| Hayden             | 1         | 2.33%   |
| Hanoi              | 1         | 2.33%   |
| Fulham             | 1         | 2.33%   |
| Forest Grove       | 1         | 2.33%   |
| Cologne            | 1         | 2.33%   |
| Cherepovets        | 1         | 2.33%   |
| Belém             | 1         | 2.33%   |
| Bairrada           | 1         | 2.33%   |
| Bagnolet           | 1         | 2.33%   |
| Atlanta            | 1         | 2.33%   |
| Amsterdam          | 1         | 2.33%   |
| Aidlingen          | 1         | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 14.81%  |
| Unknown             | 5         | 6      | 9.26%   |
| Samsung Electronics | 5         | 10     | 9.26%   |
| SanDisk             | 3         | 3      | 5.56%   |
| Kingston            | 3         | 3      | 5.56%   |
| Hitachi             | 3         | 3      | 5.56%   |
| Seagate             | 2         | 2      | 3.7%    |
| PNY                 | 2         | 2      | 3.7%    |
| HGST                | 2         | 2      | 3.7%    |
| Fujitsu             | 2         | 2      | 3.7%    |
| Crucial             | 2         | 2      | 3.7%    |
| Union Memory        | 1         | 2      | 1.85%   |
| UMIS                | 1         | 1      | 1.85%   |
| Toshiba             | 1         | 1      | 1.85%   |
| Teclast             | 1         | 1      | 1.85%   |
| Team                | 1         | 1      | 1.85%   |
| Smart               | 1         | 1      | 1.85%   |
| SK hynix            | 1         | 1      | 1.85%   |
| SABRENT             | 1         | 2      | 1.85%   |
| Patriot             | 1         | 1      | 1.85%   |
| Mushkin             | 1         | 1      | 1.85%   |
| LITEONIT            | 1         | 1      | 1.85%   |
| LITEON              | 1         | 3      | 1.85%   |
| KIOXIA              | 1         | 1      | 1.85%   |
| KingFast            | 1         | 1      | 1.85%   |
| Intel               | 1         | 1      | 1.85%   |
| HXY                 | 1         | 1      | 1.85%   |
| Hewlett-Packard     | 1         | 1      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| PNY CS900 240GB SSD                   | 2         | 3.57%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 3.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1.79%   |
| WDC WD7500BPKX-00HPJT0 752GB          | 1         | 1.79%   |
| WDC WD5000BPVT-24HXZT3 500GB          | 1         | 1.79%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1         | 1.79%   |
| WDC WD3200BEVT-22A23T0 320GB          | 1         | 1.79%   |
| WDC WD3200BEVE-00A0HT0 320GB          | 1         | 1.79%   |
| WDC WD2500BEKT-00A25T0 250GB          | 1         | 1.79%   |
| WDC WD10SPZX-21Z10T0 1TB              | 1         | 1.79%   |
| Unknown SD04G  4GB                    | 1         | 1.79%   |
| Unknown SD  8GB                       | 1         | 1.79%   |
| Unknown MMC32G  32GB                  | 1         | 1.79%   |
| Unknown MMC Card  32GB                | 1         | 1.79%   |
| Unknown MMC Card  16GB                | 1         | 1.79%   |
| Unknown MMC Card  128GB               | 1         | 1.79%   |
| Union Memory RTOTJ128VGD2EYX 128GB    | 1         | 1.79%   |
| UMIS RPFTJ256PDD2MWX 256GB            | 1         | 1.79%   |
| Toshiba MK1252GSX 120GB               | 1         | 1.79%   |
| Teclast 256GB NS550-2242 SSD          | 1         | 1.79%   |
| Team T253X1120G 120GB SSD             | 1         | 1.79%   |
| Smart SSD SZ9MSE mSATA 256GB          | 1         | 1.79%   |
| SK hynix PC611 NVMe 1TB               | 1         | 1.79%   |
| Seagate ST9250410AS 250GB             | 1         | 1.79%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1.79%   |
| SanDisk X300 MSATA 256GB SSD          | 1         | 1.79%   |
| SanDisk SSD PLUS 480GB                | 1         | 1.79%   |
| SanDisk SDSSDHII240G 240GB            | 1         | 1.79%   |
| Samsung SSD 980 1TB                   | 1         | 1.79%   |
| Samsung SSD 970 PRO 1TB               | 1         | 1.79%   |
| Samsung SSD 970 EVO Plus 500GB        | 1         | 1.79%   |
| Samsung SSD 850 PRO 2TB               | 1         | 1.79%   |
| Samsung SSD 850 EVO 500GB             | 1         | 1.79%   |
| Samsung MZVLW512HMJP-000L7 512GB      | 1         | 1.79%   |
| SABRENT Disk 1TB                      | 1         | 1.79%   |
| Patriot Burst 960GB SSD               | 1         | 1.79%   |
| Mushkin MKNSSDRE2TB                   | 1         | 1.79%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB SSD | 1         | 1.79%   |
| LITEON LCH-512V2S 512GB SSD           | 1         | 1.79%   |
| KIOXIA KBG40ZNV256G 256GB             | 1         | 1.79%   |
| Kingston SA400S37480G 480GB SSD       | 1         | 1.79%   |
| KingFast 128GB                        | 1         | 1.79%   |
| Intel SSDPEKKF512G8L 512GB            | 1         | 1.79%   |
| HXY SSD 120G                          | 1         | 1.79%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1.79%   |
| Hitachi HTS726060M9AT00 56GB          | 1         | 1.79%   |
| Hitachi HTS547550A9E384 500GB         | 1         | 1.79%   |
| HGST HTS725032A7E630 320GB            | 1         | 1.79%   |
| HGST HTS721010A9E630 1TB              | 1         | 1.79%   |
| HP SSD S700 250GB                     | 1         | 1.79%   |
| Fujitsu MHV2120BH 120GB               | 1         | 1.79%   |
| Fujitsu MHT2030AT 32GB                | 1         | 1.79%   |
| Crucial CT250MX500SSD1 250GB          | 1         | 1.79%   |
| Crucial CT1000MX500SSD1 1TB           | 1         | 1.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 7         | 7      | 41.18%  |
| Hitachi | 3         | 3      | 17.65%  |
| Seagate | 2         | 2      | 11.76%  |
| HGST    | 2         | 2      | 11.76%  |
| Fujitsu | 2         | 2      | 11.76%  |
| Toshiba | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 13.04%  |
| Kingston            | 3         | 3      | 13.04%  |
| Samsung Electronics | 2         | 2      | 8.7%    |
| PNY                 | 2         | 2      | 8.7%    |
| Crucial             | 2         | 2      | 8.7%    |
| WDC                 | 1         | 2      | 4.35%   |
| Union Memory        | 1         | 2      | 4.35%   |
| Teclast             | 1         | 1      | 4.35%   |
| Team                | 1         | 1      | 4.35%   |
| Smart               | 1         | 1      | 4.35%   |
| Patriot             | 1         | 1      | 4.35%   |
| Mushkin             | 1         | 1      | 4.35%   |
| LITEONIT            | 1         | 1      | 4.35%   |
| LITEON              | 1         | 3      | 4.35%   |
| HXY                 | 1         | 1      | 4.35%   |
| Hewlett-Packard     | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 22        | 27     | 41.51%  |
| HDD     | 17        | 17     | 32.08%  |
| NVMe    | 8         | 14     | 15.09%  |
| MMC     | 5         | 6      | 9.43%   |
| Unknown | 1         | 1      | 1.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 45     | 73.47%  |
| NVMe | 7         | 12     | 14.29%  |
| MMC  | 5         | 6      | 10.2%   |
| SAS  | 1         | 2      | 2.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 33     | 78.38%  |
| 0.51-1.0   | 6         | 9      | 16.22%  |
| 1.01-2.0   | 2         | 2      | 5.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 11        | 24.44%  |
| 101-250    | 10        | 22.22%  |
| 51-100     | 6         | 13.33%  |
| 1001-2000  | 4         | 8.89%   |
| 501-1000   | 4         | 8.89%   |
| 21-50      | 3         | 6.67%   |
| Unknown    | 3         | 6.67%   |
| 2001-3000  | 2         | 4.44%   |
| 1-20       | 2         | 4.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 13        | 28.89%  |
| 101-250   | 8         | 17.78%  |
| 51-100    | 8         | 17.78%  |
| 21-50     | 5         | 11.11%  |
| 251-500   | 3         | 6.67%   |
| 1001-2000 | 3         | 6.67%   |
| Unknown   | 3         | 6.67%   |
| 501-1000  | 2         | 4.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB  | 1         | 1      | 25%     |
| WDC WD3200BEVT-22A23T0 320GB  | 1         | 1      | 25%     |
| Hitachi HTS727575A9E364 752GB | 1         | 1      | 25%     |
| Hitachi HTS726060M9AT00 56GB  | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 50%     |
| Hitachi | 2         | 2      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 50%     |
| Hitachi | 2         | 2      | 50%     |

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
| Works    | 34        | 46     | 69.39%  |
| Detected | 11        | 15     | 22.45%  |
| Malfunc  | 4         | 4      | 8.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 33        | 70.21%  |
| AMD                     | 7         | 14.89%  |
| Samsung Electronics     | 3         | 6.38%   |
| VIA Technologies        | 1         | 2.13%   |
| Union Memory (Shenzhen) | 1         | 2.13%   |
| SK hynix                | 1         | 2.13%   |
| KIOXIA                  | 1         | 2.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 11.76%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 9.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 7.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 5.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 5.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 5.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 3.92%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 3.92%   |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 1.96%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 1.96%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.96%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.96%   |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 1.96%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.96%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.96%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.96%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 1         | 1.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 1         | 1.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 1         | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 32        | 66.67%  |
| NVMe | 7         | 14.58%  |
| IDE  | 7         | 14.58%  |
| RAID | 2         | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 35        | 81.4%   |
| AMD    | 7         | 16.28%  |
| ARM    | 1         | 2.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz               | 3         | 6.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 3         | 6.98%   |
| Intel Pentium M processor 1700MHz               | 1         | 2.33%   |
| Intel Pentium M processor 1.60GHz               | 1         | 2.33%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 2.33%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz          | 1         | 2.33%   |
| Intel Pentium CPU P6100 @ 2.00GHz               | 1         | 2.33%   |
| Intel Core i9-8950HK CPU @ 2.90GHz              | 1         | 2.33%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 2.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 2.33%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 2.33%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 2.33%   |
| Intel Core i7-3610QM CPU @ 2.30GHz              | 1         | 2.33%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 1         | 2.33%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 1         | 2.33%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 2.33%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 2.33%   |
| Intel Core i5-10310U CPU @ 1.70GHz              | 1         | 2.33%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 2.33%   |
| Intel Core i3-4010U CPU @ 1.70GHz               | 1         | 2.33%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 1         | 2.33%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 1         | 2.33%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 1         | 2.33%   |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 1         | 2.33%   |
| Intel Core i3 CPU M 330 @ 2.13GHz               | 1         | 2.33%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 1         | 2.33%   |
| Intel Core 2 CPU T5600 @ 1.83GHz                | 1         | 2.33%   |
| Intel Core 2 CPU P8600 @ 2.40GHz                | 1         | 2.33%   |
| Intel Celeron N4100 CPU @ 1.10GHz               | 1         | 2.33%   |
| Intel Celeron M processor 1.40GHz               | 1         | 2.33%   |
| Intel Celeron CPU N2830 @ 2.16GHz               | 1         | 2.33%   |
| ARM Nokia RX-51 board Processor                 | 1         | 2.33%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 2.33%   |
| AMD E2-1800 APU with Radeon HD Graphics         | 1         | 2.33%   |
| AMD E-300 APU with Radeon HD Graphics           | 1         | 2.33%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G    | 1         | 2.33%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.33%   |
| AMD A6-4400M APU with Radeon HD Graphics        | 1         | 2.33%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 10        | 23.26%  |
| Intel Core i3           | 7         | 16.28%  |
| Intel Core i7           | 6         | 13.95%  |
| Intel Core 2            | 3         | 6.98%   |
| Other                   | 2         | 4.65%   |
| Intel Pentium M         | 2         | 4.65%   |
| Intel Celeron           | 2         | 4.65%   |
| Intel Pentium Dual-Core | 1         | 2.33%   |
| Intel Pentium Dual      | 1         | 2.33%   |
| Intel Pentium           | 1         | 2.33%   |
| Intel Core i9           | 1         | 2.33%   |
| Intel Celeron M         | 1         | 2.33%   |
| AMD Ryzen 5             | 1         | 2.33%   |
| AMD E2                  | 1         | 2.33%   |
| AMD E                   | 1         | 2.33%   |
| AMD A8                  | 1         | 2.33%   |
| AMD A6                  | 1         | 2.33%   |
| AMD A10                 | 1         | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 28        | 65.12%  |
| 4      | 7         | 16.28%  |
| 1      | 5         | 11.63%  |
| 6      | 3         | 6.98%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 43        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 25        | 58.14%  |
| 1      | 18        | 41.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 38        | 88.37%  |
| 32-bit         | 3         | 6.98%   |
| Unknown        | 2         | 4.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 25%     |
| 0x306d4    | 3         | 6.82%   |
| 0x306a9    | 3         | 6.82%   |
| 0x206a7    | 3         | 6.82%   |
| 0x906ea    | 2         | 4.55%   |
| 0x806ec    | 2         | 4.55%   |
| 0x6f6      | 2         | 4.55%   |
| 0x20655    | 2         | 4.55%   |
| 0x1067a    | 2         | 4.55%   |
| 0x906ed    | 1         | 2.27%   |
| 0x706a1    | 1         | 2.27%   |
| 0x6d8      | 1         | 2.27%   |
| 0x695      | 1         | 2.27%   |
| 0x406e3    | 1         | 2.27%   |
| 0x40651    | 1         | 2.27%   |
| 0x306c3    | 1         | 2.27%   |
| 0x30678    | 1         | 2.27%   |
| 0x20652    | 1         | 2.27%   |
| 0x08608103 | 1         | 2.27%   |
| 0x07030105 | 1         | 2.27%   |
| 0x0600611a | 1         | 2.27%   |
| 0x05000119 | 1         | 2.27%   |
| 0x05000101 | 1         | 2.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 13.95%  |
| IvyBridge     | 5         | 11.63%  |
| Westmere      | 4         | 9.3%    |
| Broadwell     | 4         | 9.3%    |
| SandyBridge   | 3         | 6.98%   |
| P6            | 3         | 6.98%   |
| Core          | 3         | 6.98%   |
| Penryn        | 2         | 4.65%   |
| Haswell       | 2         | 4.65%   |
| Excavator     | 2         | 4.65%   |
| Bobcat        | 2         | 4.65%   |
| Unknown       | 2         | 4.65%   |
| Skylake       | 1         | 2.33%   |
| Silvermont    | 1         | 2.33%   |
| Puma          | 1         | 2.33%   |
| Piledriver    | 1         | 2.33%   |
| Goldmont plus | 1         | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 31        | 63.27%  |
| AMD    | 12        | 24.49%  |
| Nvidia | 6         | 12.24%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 9.62%   |
| Intel HD Graphics 5500                                                                | 4         | 7.69%   |
| Intel Core Processor Integrated Graphics Controller                                   | 4         | 7.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 3         | 5.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 5.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 2         | 3.85%   |
| Nvidia GP107M [GeForce MX150]                                                         | 1         | 1.92%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 1.92%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 1.92%   |
| Nvidia GK106M [GeForce GTX 765M]                                                      | 1         | 1.92%   |
| Nvidia GF108M [NVS 5400M]                                                             | 1         | 1.92%   |
| Nvidia GF108M [GeForce GT 635M]                                                       | 1         | 1.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 1         | 1.92%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 1         | 1.92%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.92%   |
| Intel HD Graphics 620                                                                 | 1         | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 1.92%   |
| Intel 82852/855GM Integrated Graphics Device                                          | 1         | 1.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 1         | 1.92%   |
| AMD Wrestler [Radeon HD 7340]                                                         | 1         | 1.92%   |
| AMD Wrestler [Radeon HD 6310]                                                         | 1         | 1.92%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 1         | 1.92%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                       | 1         | 1.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.92%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 1.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 1         | 1.92%   |
| AMD RV380/M24 [Mobility Radeon X600]                                                  | 1         | 1.92%   |
| AMD RV350/M10 GL [Mobility FireGL T2]                                                 | 1         | 1.92%   |
| AMD R520/M58 [Mobility Radeon X1800]                                                  | 1         | 1.92%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                          | 1         | 1.92%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 1         | 1.92%   |
| AMD Lucienne                                                                          | 1         | 1.92%   |
| AMD Baffin [Radeon Pro WX 4130/4150]                                                  | 1         | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 51.16%  |
| 1 x AMD        | 9         | 20.93%  |
| Intel + Nvidia | 6         | 13.95%  |
| Other          | 2         | 4.65%   |
| 2 x AMD        | 2         | 4.65%   |
| 2 x Intel      | 1         | 2.33%   |
| Intel + AMD    | 1         | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 39        | 90.7%   |
| Proprietary | 2         | 4.65%   |
| Unknown     | 2         | 4.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 70.45%  |
| 0.01-0.5   | 6         | 13.64%  |
| 1.01-2.0   | 3         | 6.82%   |
| 0.51-1.0   | 3         | 6.82%   |
| 3.01-4.0   | 1         | 2.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 11        | 23.4%   |
| AU Optronics            | 8         | 17.02%  |
| Chimei Innolux          | 5         | 10.64%  |
| Samsung Electronics     | 4         | 8.51%   |
| BOE                     | 3         | 6.38%   |
| PANDA                   | 2         | 4.26%   |
| Lenovo                  | 2         | 4.26%   |
| Goldstar                | 2         | 4.26%   |
| Chi Mei Optoelectronics | 2         | 4.26%   |
| Unknown                 | 1         | 2.13%   |
| STD                     | 1         | 2.13%   |
| MStar                   | 1         | 2.13%   |
| InnoLux Display         | 1         | 2.13%   |
| InfoVision              | 1         | 2.13%   |
| Hisense                 | 1         | 2.13%   |
| Dell                    | 1         | 2.13%   |
| AOC                     | 1         | 2.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 4.26%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 1         | 2.13%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                        | 1         | 2.13%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 530x300mm 24.0-inch        | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch     | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch     | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch     | 1         | 2.13%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                  | 1         | 2.13%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch                  | 1         | 2.13%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                         | 1         | 2.13%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 2.13%   |
| LG Display LCD Monitor LGD0540 1920x1080 340x190mm 15.3-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD02C0 1366x768 293x165mm 13.2-inch              | 1         | 2.13%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                  | 1         | 2.13%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x184mm 12.1-inch                  | 1         | 2.13%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch         | 1         | 2.13%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 2.13%   |
| Hisense Hisense HSE4000 1920x1080 591x355mm 27.1-inch                    | 1         | 2.13%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 1         | 2.13%   |
| Goldstar E2260 GSM57E0 1920x1080 477x268mm 21.5-inch                     | 1         | 2.13%   |
| Dell P2415Q DELA0BE 3840x2160 530x300mm 24.0-inch                        | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch          | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 282x165mm 12.9-inch         | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1118 1366x768 256x144mm 11.6-inch          | 1         | 2.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 2.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 2.13%   |
| BOE LCD Monitor BOE0953 1920x1080 382x215mm 17.3-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO1101 1440x900 367x230mm 17.1-inch            | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 1         | 2.13%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 1         | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 23        | 50%     |
| 1920x1080 (FHD)  | 15        | 32.61%  |
| 3840x2160 (4K)   | 3         | 6.52%   |
| 1280x800 (WXGA)  | 2         | 4.35%   |
| 2288x1287        | 1         | 2.17%   |
| 1600x900 (HD+)   | 1         | 2.17%   |
| 1440x900 (WXGA+) | 1         | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 19        | 40.43%  |
| 12     | 6         | 12.77%  |
| 14     | 5         | 10.64%  |
| 13     | 4         | 8.51%   |
| 24     | 2         | 4.26%   |
| 23     | 2         | 4.26%   |
| 21     | 2         | 4.26%   |
| 17     | 2         | 4.26%   |
| 142    | 1         | 2.13%   |
| 52     | 1         | 2.13%   |
| 31     | 1         | 2.13%   |
| 27     | 1         | 2.13%   |
| 11     | 1         | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 25        | 53.19%  |
| 201-300        | 10        | 21.28%  |
| 501-600        | 5         | 10.64%  |
| 401-500        | 2         | 4.26%   |
| 351-400        | 2         | 4.26%   |
| More than 2000 | 1         | 2.13%   |
| 601-700        | 1         | 2.13%   |
| 1001-1500      | 1         | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 89.74%  |
| 16/10 | 3         | 7.69%   |
| 1.00  | 1         | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 40.43%  |
| 81-90          | 6         | 12.77%  |
| 61-70          | 6         | 12.77%  |
| 201-250        | 5         | 10.64%  |
| 71-80          | 3         | 6.38%   |
| More than 1000 | 2         | 4.26%   |
| 51-60          | 1         | 2.13%   |
| 351-500        | 1         | 2.13%   |
| 301-350        | 1         | 2.13%   |
| 151-200        | 1         | 2.13%   |
| 131-140        | 1         | 2.13%   |
| 121-130        | 1         | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 17        | 36.96%  |
| 121-160 | 16        | 34.78%  |
| 51-100  | 8         | 17.39%  |
| 161-240 | 3         | 6.52%   |
| 1-50    | 2         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 36        | 80%     |
| 2     | 7         | 15.56%  |
| 3     | 1         | 2.22%   |
| 0     | 1         | 2.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 21        | 30.43%  |
| Realtek Semiconductor      | 20        | 28.99%  |
| Qualcomm Atheros           | 17        | 24.64%  |
| ZTE WCDMA Technologies MSM | 1         | 1.45%   |
| VIA Technologies           | 1         | 1.45%   |
| TP-Link                    | 1         | 1.45%   |
| Sierra Wireless            | 1         | 1.45%   |
| Ralink Technology          | 1         | 1.45%   |
| Ralink                     | 1         | 1.45%   |
| NetGear                    | 1         | 1.45%   |
| MediaTek                   | 1         | 1.45%   |
| JMicron Technology         | 1         | 1.45%   |
| Broadcom Limited           | 1         | 1.45%   |
| Broadcom                   | 1         | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 10        | 11.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 6.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 5.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 4.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 4.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 3.45%   |
| Intel Wireless 7265                                                     | 3         | 3.45%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.3%    |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 2.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.3%    |
| Intel Wireless 7260                                                     | 2         | 2.3%    |
| Intel Ethernet Connection (7) I219-LM                                   | 2         | 2.3%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 2.3%    |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                          | 1         | 1.15%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 1.15%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 1.15%   |
| Sierra Wireless EM7455                                                  | 1         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.15%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 1.15%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.15%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 1.15%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 1.15%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 1.15%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 1         | 1.15%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 1.15%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 1.15%   |
| Intel Wireless 8260                                                     | 1         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.15%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.15%   |
| Intel Ethernet Connection (6) I219-V                                    | 1         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                                   | 1         | 1.15%   |
| Intel Ethernet Connection (10) I219-LM                                  | 1         | 1.15%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.15%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 1         | 1.15%   |
| Intel 82573L Gigabit Ethernet Controller                                | 1         | 1.15%   |
| Intel 82567LM Gigabit Network Connection                                | 1         | 1.15%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                      | 1         | 1.15%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.15%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.15%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 16        | 38.1%   |
| Intel                 | 14        | 33.33%  |
| Realtek Semiconductor | 5         | 11.9%   |
| Sierra Wireless       | 1         | 2.38%   |
| Ralink Technology     | 1         | 2.38%   |
| Ralink                | 1         | 2.38%   |
| NetGear               | 1         | 2.38%   |
| MediaTek              | 1         | 2.38%   |
| Broadcom Limited      | 1         | 2.38%   |
| Broadcom              | 1         | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 9.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 9.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 7.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 7.14%   |
| Intel Wireless 7265                                                     | 3         | 7.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 4.76%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 4.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 4.76%   |
| Intel Wireless 7260                                                     | 2         | 4.76%   |
| Sierra Wireless EM7455                                                  | 1         | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 2.38%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 2.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 2.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 2.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 2.38%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 1         | 2.38%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 2.38%   |
| Intel Wireless 8260                                                     | 1         | 2.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 2.38%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 2.38%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 2.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 2.38%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2.38%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 18        | 42.86%  |
| Intel                      | 17        | 40.48%  |
| Qualcomm Atheros           | 3         | 7.14%   |
| ZTE WCDMA Technologies MSM | 1         | 2.38%   |
| VIA Technologies           | 1         | 2.38%   |
| TP-Link                    | 1         | 2.38%   |
| JMicron Technology         | 1         | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 23.81%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 14.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 11.9%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 7.14%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 4.76%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                    | 1         | 2.38%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 2.38%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 2.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.38%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 2.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.38%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.38%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 2.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.38%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 2.38%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 2.38%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.38%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 41        | 49.4%   |
| Ethernet | 39        | 46.99%  |
| Modem    | 3         | 3.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 63.83%  |
| Ethernet | 17        | 36.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 37        | 86.05%  |
| 1     | 4         | 9.3%    |
| 0     | 2         | 4.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 88.37%  |
| Yes  | 5         | 11.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 24%     |
| Realtek Semiconductor           | 4         | 16%     |
| Broadcom                        | 4         | 16%     |
| Qualcomm Atheros Communications | 3         | 12%     |
| Lite-On Technology              | 2         | 8%      |
| Cambridge Silicon Radio         | 2         | 8%      |
| Ralink                          | 1         | 4%      |
| IMC Networks                    | 1         | 4%      |
| Foxconn / Hon Hai               | 1         | 4%      |
| Dell                            | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 20%     |
| Realtek Bluetooth Radio                             | 4         | 16%     |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 8%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 8%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 8%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 8%      |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 8%      |
| Ralink RT3290 Bluetooth                             | 1         | 4%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 4%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 4%      |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 4%      |
| Foxconn / Hon Hai BT                                | 1         | 4%      |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 67.31%  |
| AMD                   | 9         | 17.31%  |
| Nvidia                | 4         | 7.69%   |
| Realtek Semiconductor | 1         | 1.92%   |
| GYROCOM C&C           | 1         | 1.92%   |
| C-Media Electronics   | 1         | 1.92%   |
| Blue Microphones      | 1         | 1.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 7.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 6.25%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 6.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 6.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 4.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 4.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 4.69%   |
| AMD FCH Azalia Controller                                                  | 3         | 4.69%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 3.13%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 3.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 3.13%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 3.13%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 3.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 3.13%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.56%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.56%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.56%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.56%   |
| GYROCOM C&C Fiio E10                                                       | 1         | 1.56%   |
| C-Media Electronics CM106 Like Sound Device                                | 1         | 1.56%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1         | 1.56%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.56%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.56%   |
| AMD High Definition Audio Controller                                       | 1         | 1.56%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 1.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 1.56%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 31.71%  |
| Unknown             | 5         | 12.2%   |
| SK hynix            | 5         | 12.2%   |
| Crucial             | 4         | 9.76%   |
| A-DATA Technology   | 4         | 9.76%   |
| Kingston            | 3         | 7.32%   |
| G.Skill             | 2         | 4.88%   |
| Unknown (ABCD)      | 1         | 2.44%   |
| Smart               | 1         | 2.44%   |
| Nanya Technology    | 1         | 2.44%   |
| Micron Technology   | 1         | 2.44%   |
| Apacer              | 1         | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                               | 2         | 4.17%   |
| Unknown RAM Module 1024MB SODIMM DDR                                | 2         | 4.17%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 4.17%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s             | 2         | 4.17%   |
| Unknown RAM Module 512MB SODIMM DDR                                 | 1         | 2.08%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                            | 1         | 2.08%   |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 1         | 2.08%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 2.08%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 1         | 2.08%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s               | 1         | 2.08%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s             | 1         | 2.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.08%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 2.08%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 2.08%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 2.08%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 2.08%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 1         | 2.08%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 1         | 2.08%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 1         | 2.08%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 2.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 2.08%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 2.08%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 2.08%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 2.08%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 2.08%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 2.08%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 2.08%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 1         | 2.08%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 2.08%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 1         | 2.08%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 1         | 2.08%   |
| Kingston RAM TSB1600D3S1ELD/4GE 4096MB SODIMM DDR3 1067MT/s         | 1         | 2.08%   |
| Kingston RAM KHYXPX-MIE 8GB SODIMM DDR4 2667MT/s                    | 1         | 2.08%   |
| Kingston RAM ACR16D3LS1NGG/2G 2GB SODIMM DDR3 1333MT/s              | 1         | 2.08%   |
| Kingston RAM 9905428-426.A00LF 8GB SODIMM DDR3 1600MT/s             | 1         | 2.08%   |
| G.Skill RAM FA-1333C9-8GSQ 8GB SODIMM DDR3 1333MT/s                 | 1         | 2.08%   |
| G.Skill RAM F4-2133C15-8GRS 8GB SODIMM DDR4 2667MT/s                | 1         | 2.08%   |
| Crucial RAM CT8G4SFRA266.C8FE 8192MB SODIMM DDR4 2667MT/s           | 1         | 2.08%   |
| Crucial RAM BLS4G3N169ES4.16FE 4096MB SODIMM DDR3 1600MT/s          | 1         | 2.08%   |
| Apacer RAM 76.A302G.C4D0B 2048MB SODIMM DDR3 1600MT/s               | 1         | 2.08%   |
| A-DATA RAM Module 8GB SODIMM DDR4 1200MT/s                          | 1         | 2.08%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2400MT/s                         | 1         | 2.08%   |
| A-DATA RAM HY73I1B1672ZMT 2GB SODIMM DDR3 1067MT/s                  | 1         | 2.08%   |
| A-DATA RAM AO1P26KCST2-BZISHC 16384MB SODIMM DDR4 2667MT/s          | 1         | 2.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 18        | 50%     |
| DDR4    | 9         | 25%     |
| SDRAM   | 2         | 5.56%   |
| DDR2    | 2         | 5.56%   |
| DDR     | 2         | 5.56%   |
| LPDDR4  | 1         | 2.78%   |
| LPDDR3  | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 34        | 97.14%  |
| Row Of Chips | 1         | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 15        | 34.09%  |
| 4096  | 12        | 27.27%  |
| 2048  | 10        | 22.73%  |
| 1024  | 3         | 6.82%   |
| 16384 | 2         | 4.55%   |
| 32768 | 1         | 2.27%   |
| 512   | 1         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 12        | 31.58%  |
| 2667    | 7         | 18.42%  |
| Unknown | 4         | 10.53%  |
| 1333    | 3         | 7.89%   |
| 1067    | 3         | 7.89%   |
| 4199    | 2         | 5.26%   |
| 2400    | 2         | 5.26%   |
| 3200    | 1         | 2.63%   |
| 2133    | 1         | 2.63%   |
| 1334    | 1         | 2.63%   |
| 1200    | 1         | 2.63%   |
| 800     | 1         | 2.63%   |

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
| Chicony Electronics                    | 15        | 44.12%  |
| Acer                                   | 4         | 11.76%  |
| Sunplus Innovation Technology          | 3         | 8.82%   |
| Microdia                               | 3         | 8.82%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 8.82%   |
| Suyin                                  | 2         | 5.88%   |
| Samsung Electronics                    | 1         | 2.94%   |
| Mustek Systems                         | 1         | 2.94%   |
| Logitech                               | 1         | 2.94%   |
| IMC Networks                           | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 6         | 17.65%  |
| Acer BisonCam, NB Pro                                           | 2         | 5.88%   |
| Suyin Acer/Lenovo Webcam [CN0316]                               | 1         | 2.94%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 1         | 2.94%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 2.94%   |
| Sunplus FHD Camera Microphone                                   | 1         | 2.94%   |
| Sunplus Asus Webcam                                             | 1         | 2.94%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1         | 2.94%   |
| Mustek Systems USB 2.0 PC Camera                                | 1         | 2.94%   |
| Microdia WebCam SC-13HDL12639P                                  | 1         | 2.94%   |
| Microdia Dell Integrated HD Webcam                              | 1         | 2.94%   |
| Microdia 1.3 MPixel Integrated Webcam                           | 1         | 2.94%   |
| Logitech HD Pro Webcam C920                                     | 1         | 2.94%   |
| IMC Networks Integrated Webcam                                  | 1         | 2.94%   |
| Chicony WebCam                                                  | 1         | 2.94%   |
| Chicony VGA WebCam                                              | 1         | 2.94%   |
| Chicony Thinkpad T430 camera                                    | 1         | 2.94%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 1         | 2.94%   |
| Chicony Lenovo EasyCamera                                       | 1         | 2.94%   |
| Chicony HP TrueVision HD                                        | 1         | 2.94%   |
| Chicony HD WebCam                                               | 1         | 2.94%   |
| Chicony EasyCamera                                              | 1         | 2.94%   |
| Chicony CNF9055 Toshiba Webcam                                  | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-82                | 1         | 2.94%   |
| Acer ThinkPad Integrated Camera                                 | 1         | 2.94%   |
| Acer Integrated Camera                                          | 1         | 2.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 1         | 25%     |
| Upek               | 1         | 25%     |
| Synaptics          | 1         | 25%     |
| STMicroelectronics | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 1         | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 25%     |
| STMicroelectronics Fingerprint Reader                  | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 57.14%  |
| Alcor Micro | 2         | 28.57%  |
| Lenovo      | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 28.57%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |
| Broadcom 58200                                                               | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 29        | 64.44%  |
| 1     | 11        | 24.44%  |
| 2     | 4         | 8.89%   |
| 3     | 1         | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Chipcard                 | 5         | 27.78%  |
| Fingerprint reader       | 4         | 22.22%  |
| Net/wireless             | 2         | 11.11%  |
| Graphics card            | 2         | 11.11%  |
| Camera                   | 2         | 11.11%  |
| Bluetooth                | 2         | 11.11%  |
| Communication controller | 1         | 5.56%   |

