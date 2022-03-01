LinuxFX 11 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for LinuxFX 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Samsung       | 355V4C/355V4X/355V5C/355... | [f3ec55a392](https://linux-hardware.org/?probe=f3ec55a392) | Feb 25, 2022 |
| Positivo      | Smash                       | [68fd957c2e](https://linux-hardware.org/?probe=68fd957c2e) | Feb 21, 2022 |
| Apple         | MacBookPro5,5               | [2ef0397f90](https://linux-hardware.org/?probe=2ef0397f90) | Feb 20, 2022 |
| Apple         | MacBookPro5,5               | [33c341d85e](https://linux-hardware.org/?probe=33c341d85e) | Feb 20, 2022 |
| HP            | EliteBook Folio 9470m       | [8f3df927df](https://linux-hardware.org/?probe=8f3df927df) | Feb 18, 2022 |
| ASUSTek       | X751LAB                     | [10ea8f6500](https://linux-hardware.org/?probe=10ea8f6500) | Feb 17, 2022 |
| HP            | Compaq CQ45                 | [51144497b2](https://linux-hardware.org/?probe=51144497b2) | Feb 16, 2022 |
| Apple         | MacBookPro5,5               | [75ee9c8a17](https://linux-hardware.org/?probe=75ee9c8a17) | Feb 10, 2022 |
| Apple         | MacBookPro5,5               | [d849fe0859](https://linux-hardware.org/?probe=d849fe0859) | Feb 10, 2022 |
| Apple         | MacBookPro5,5               | [403c9202cf](https://linux-hardware.org/?probe=403c9202cf) | Feb 09, 2022 |
| Dell          | Latitude E6420              | [85d1f4fe0a](https://linux-hardware.org/?probe=85d1f4fe0a) | Feb 09, 2022 |
| Apple         | MacBookPro5,5               | [6942d0b7dc](https://linux-hardware.org/?probe=6942d0b7dc) | Feb 07, 2022 |
| Apple         | MacBookPro5,5               | [cc840b5085](https://linux-hardware.org/?probe=cc840b5085) | Feb 05, 2022 |
| HP            | ProBook 4720s               | [aa5c35966f](https://linux-hardware.org/?probe=aa5c35966f) | Feb 04, 2022 |
| Acer          | Aspire 5741                 | [175d1e66d3](https://linux-hardware.org/?probe=175d1e66d3) | Feb 02, 2022 |
| Apple         | MacBookPro5,5               | [4e66f349b5](https://linux-hardware.org/?probe=4e66f349b5) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | [caa91028ac](https://linux-hardware.org/?probe=caa91028ac) | Jan 30, 2022 |
| Dell          | Latitude E6540              | [fe6720f0de](https://linux-hardware.org/?probe=fe6720f0de) | Jan 30, 2022 |
| Dell          | Latitude E6540              | [7c972de545](https://linux-hardware.org/?probe=7c972de545) | Jan 30, 2022 |
| HP            | Laptop 14-dk1xxx            | [5204867d35](https://linux-hardware.org/?probe=5204867d35) | Jan 30, 2022 |
| HP            | Pavilion dv6700             | [1fea9d48e2](https://linux-hardware.org/?probe=1fea9d48e2) | Jan 26, 2022 |
| Lenovo        | G550 2958                   | [506ee71418](https://linux-hardware.org/?probe=506ee71418) | Jan 23, 2022 |
| ASUSTek       | K95VM                       | [8345888a5e](https://linux-hardware.org/?probe=8345888a5e) | Jan 23, 2022 |
| ASUSTek       | K95VM                       | [fb24768fa2](https://linux-hardware.org/?probe=fb24768fa2) | Jan 23, 2022 |
| HP            | Laptop 15-bw0xx             | [6326f72eff](https://linux-hardware.org/?probe=6326f72eff) | Jan 21, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c76a20872b](https://linux-hardware.org/?probe=c76a20872b) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [11d1f56125](https://linux-hardware.org/?probe=11d1f56125) | Jan 18, 2022 |
| Apple         | MacBookPro5,5               | [6c57abcd85](https://linux-hardware.org/?probe=6c57abcd85) | Jan 16, 2022 |
| Apple         | MacBookPro5,5               | [05a41ad625](https://linux-hardware.org/?probe=05a41ad625) | Jan 16, 2022 |
| HP            | Compaq 6730b (NA373UC#AB... | [0a2913bd14](https://linux-hardware.org/?probe=0a2913bd14) | Jan 16, 2022 |
| Toshiba       | TECRA R850                  | [cd13f4b4ab](https://linux-hardware.org/?probe=cd13f4b4ab) | Jan 15, 2022 |
| Toshiba       | TECRA R850                  | [445c000697](https://linux-hardware.org/?probe=445c000697) | Jan 15, 2022 |
| HP            | Compaq 6730b (NA373UC#AB... | [dff23d9e2e](https://linux-hardware.org/?probe=dff23d9e2e) | Jan 13, 2022 |
| Acer          | Aspire E1-570               | [2ff1ed4b2c](https://linux-hardware.org/?probe=2ff1ed4b2c) | Jan 05, 2022 |
| Toshiba       | Satellite P300              | [7540ebe059](https://linux-hardware.org/?probe=7540ebe059) | Jan 02, 2022 |
| Samsung       | RF511/RF411/RF711           | [7c247b0c9f](https://linux-hardware.org/?probe=7c247b0c9f) | Dec 29, 2021 |
| Samsung       | RF511/RF411/RF711           | [5cff8b82d5](https://linux-hardware.org/?probe=5cff8b82d5) | Dec 28, 2021 |
| Dell          | Inspiron N5050              | [f08b82f201](https://linux-hardware.org/?probe=f08b82f201) | Dec 22, 2021 |
| Dell          | Latitude E6400              | [74586d9c77](https://linux-hardware.org/?probe=74586d9c77) | Dec 21, 2021 |
| Fujitsu       | CELSIUS H700                | [63c35d8f1d](https://linux-hardware.org/?probe=63c35d8f1d) | Dec 19, 2021 |
| Lenovo        | ThinkPad L380 20M6S4E000    | [745c4f6a79](https://linux-hardware.org/?probe=745c4f6a79) | Dec 16, 2021 |
| Alienware     | M17xR3                      | [d8c0a193cd](https://linux-hardware.org/?probe=d8c0a193cd) | Dec 14, 2021 |
| Dell          | G5 5590                     | [d68d926208](https://linux-hardware.org/?probe=d68d926208) | Dec 13, 2021 |
| Dell          | G5 5590                     | [88f9dfa75d](https://linux-hardware.org/?probe=88f9dfa75d) | Dec 13, 2021 |
| Lenovo        | G50-80 80E5                 | [77ee4f08a8](https://linux-hardware.org/?probe=77ee4f08a8) | Dec 10, 2021 |
| Dell          | Latitude E5400              | [3ce40a821b](https://linux-hardware.org/?probe=3ce40a821b) | Dec 09, 2021 |
| Acer          | Extensa 5220                | [2572d3336d](https://linux-hardware.org/?probe=2572d3336d) | Dec 09, 2021 |
| Acer          | Extensa 5220                | [524256971b](https://linux-hardware.org/?probe=524256971b) | Dec 09, 2021 |
| Toshiba       | Satellite C660              | [2799629c61](https://linux-hardware.org/?probe=2799629c61) | Nov 28, 2021 |
| Toshiba       | Satellite C660              | [1e80d1c181](https://linux-hardware.org/?probe=1e80d1c181) | Nov 28, 2021 |
| Acer          | One S1002                   | [8ae39c3aaf](https://linux-hardware.org/?probe=8ae39c3aaf) | Nov 23, 2021 |
| GPU Compan... | GWTN116-3                   | [5534b12f2d](https://linux-hardware.org/?probe=5534b12f2d) | Nov 21, 2021 |
| HP            | ProBook 440 G1              | [6159b4aa5a](https://linux-hardware.org/?probe=6159b4aa5a) | Nov 20, 2021 |
| HP            | ProBook 440 G1              | [42d0889355](https://linux-hardware.org/?probe=42d0889355) | Nov 20, 2021 |
| Lenovo        | G50-80 80E5                 | [947e251d2c](https://linux-hardware.org/?probe=947e251d2c) | Nov 18, 2021 |
| Acer          | Aspire 5735                 | [9b2574c5be](https://linux-hardware.org/?probe=9b2574c5be) | Nov 17, 2021 |
| Samsung       | RV415/RV515/E3415           | [2a9002ab69](https://linux-hardware.org/?probe=2a9002ab69) | Nov 10, 2021 |
| Lenovo        | G50-80 80R0                 | [a24e6b4e38](https://linux-hardware.org/?probe=a24e6b4e38) | Nov 06, 2021 |
| Lenovo        | G50-80 80R0                 | [94d7421e0c](https://linux-hardware.org/?probe=94d7421e0c) | Nov 06, 2021 |
| Acer          | Aspire XXXX                 | [2e486fd092](https://linux-hardware.org/?probe=2e486fd092) | Nov 05, 2021 |
| ASUSTek       | N71Vg                       | [4fee4d2ffc](https://linux-hardware.org/?probe=4fee4d2ffc) | Nov 03, 2021 |
| Google        | Peppy                       | [6408d61aa6](https://linux-hardware.org/?probe=6408d61aa6) | Nov 03, 2021 |
| Google        | Peppy                       | [894676acea](https://linux-hardware.org/?probe=894676acea) | Nov 03, 2021 |
| HP            | Pavilion g6                 | [d954a6ba33](https://linux-hardware.org/?probe=d954a6ba33) | Oct 31, 2021 |
| Lenovo        | G50-80 80E5                 | [2ecc44141a](https://linux-hardware.org/?probe=2ecc44141a) | Oct 30, 2021 |
| HP            | Pavilion g6                 | [1bfea4f4f9](https://linux-hardware.org/?probe=1bfea4f4f9) | Oct 28, 2021 |
| Lenovo        | G50-80 80E5                 | [a2c515584f](https://linux-hardware.org/?probe=a2c515584f) | Oct 27, 2021 |
| Lenovo        | G50-80 80E5                 | [b05ed4eff3](https://linux-hardware.org/?probe=b05ed4eff3) | Oct 24, 2021 |
| Lenovo        | G50-80 80E5                 | [5fbb62218c](https://linux-hardware.org/?probe=5fbb62218c) | Oct 24, 2021 |
| HP            | Pavilion g6                 | [2dfb826827](https://linux-hardware.org/?probe=2dfb826827) | Oct 24, 2021 |
| HP            | Pavilion g6                 | [7be969965e](https://linux-hardware.org/?probe=7be969965e) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | [c53ba56444](https://linux-hardware.org/?probe=c53ba56444) | Oct 23, 2021 |
| Lenovo        | G50-80 80E5                 | [edf703fb1c](https://linux-hardware.org/?probe=edf703fb1c) | Oct 23, 2021 |
| Lenovo        | G50-80 80E5                 | [7075439e69](https://linux-hardware.org/?probe=7075439e69) | Oct 17, 2021 |
| Positivo      | Smash3                      | [3c9fe4acb8](https://linux-hardware.org/?probe=3c9fe4acb8) | Oct 14, 2021 |
| Positivo      | Smash3                      | [ab60c4e746](https://linux-hardware.org/?probe=ab60c4e746) | Oct 14, 2021 |
| HP            | EliteBook 8440p             | [b3bd1860ac](https://linux-hardware.org/?probe=b3bd1860ac) | Oct 11, 2021 |
| HP            | G62                         | [6cbed79ca9](https://linux-hardware.org/?probe=6cbed79ca9) | Oct 05, 2021 |
| HP            | 255 G6 Notebook PC          | [6ae274321c](https://linux-hardware.org/?probe=6ae274321c) | Oct 03, 2021 |
| Dell          | Precision M6400             | [5f6ec9333e](https://linux-hardware.org/?probe=5f6ec9333e) | Oct 03, 2021 |
| HP            | 255 G6 Notebook PC          | [1e1bf5e8e0](https://linux-hardware.org/?probe=1e1bf5e8e0) | Oct 03, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [60fe11ee00](https://linux-hardware.org/?probe=60fe11ee00) | Sep 30, 2021 |
| Positivo      | Smash3                      | [fe185c2e3f](https://linux-hardware.org/?probe=fe185c2e3f) | Sep 29, 2021 |
| Dell          | System XPS L502X            | [437cc938df](https://linux-hardware.org/?probe=437cc938df) | Sep 28, 2021 |
| Acer          | Aspire 5738                 | [171fc1cb46](https://linux-hardware.org/?probe=171fc1cb46) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | [f9373d8ba5](https://linux-hardware.org/?probe=f9373d8ba5) | Sep 27, 2021 |
| Dell          | System XPS L502X            | [763d21b747](https://linux-hardware.org/?probe=763d21b747) | Sep 26, 2021 |
| HP            | Pavilion 14                 | [2ab5781fef](https://linux-hardware.org/?probe=2ab5781fef) | Sep 25, 2021 |
| Positivo      | Smash3                      | [ee8284c509](https://linux-hardware.org/?probe=ee8284c509) | Sep 24, 2021 |
| Fujitsu Si... | AMILO Xi 1526               | [aab9c46556](https://linux-hardware.org/?probe=aab9c46556) | Sep 23, 2021 |
| Acer          | TravelMate 5744             | [63142c25a5](https://linux-hardware.org/?probe=63142c25a5) | Sep 20, 2021 |
| Acer          | TravelMate 5744             | [0bdce8f695](https://linux-hardware.org/?probe=0bdce8f695) | Sep 20, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.11.0-37-generic | 8         | 14.29%  |
| 5.11.0-38-generic | 7         | 12.5%   |
| 5.11.0-43-generic | 6         | 10.71%  |
| 5.11.0-40-generic | 6         | 10.71%  |
| 5.13.0-28-generic | 5         | 8.93%   |
| 5.13.0-27-generic | 5         | 8.93%   |
| 5.11.0-36-generic | 5         | 8.93%   |
| 5.11.0-41-generic | 4         | 7.14%   |
| 5.13.0-30-generic | 3         | 5.36%   |
| 5.11.0-46-generic | 3         | 5.36%   |
| 5.13.0-25-generic | 1         | 1.79%   |
| 5.11.0-44-generic | 1         | 1.79%   |
| 5.11.0-42-generic | 1         | 1.79%   |
| 5.11.0-34-generic | 1         | 1.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 39        | 73.58%  |
| 5.13.0  | 14        | 26.42%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 39        | 73.58%  |
| 5.13    | 14        | 26.42%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 52        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 50        | 96.15%  |
| X-Cinnamon | 1         | 1.92%   |
| KDE        | 1         | 1.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 51        | 98.08%  |
| Wayland | 1         | 1.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 45        | 86.54%  |
| SDDM    | 7         | 13.46%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 11        | 21.15%  |
| pt_BR | 7         | 13.46%  |
| de_DE | 7         | 13.46%  |
| fr_FR | 3         | 5.77%   |
| en_AU | 3         | 5.77%   |
| pl_PL | 2         | 3.85%   |
| it_IT | 2         | 3.85%   |
| en_IN | 2         | 3.85%   |
| el_GR | 2         | 3.85%   |
| cs_CZ | 2         | 3.85%   |
| ru_UA | 1         | 1.92%   |
| pt_PT | 1         | 1.92%   |
| nl_NL | 1         | 1.92%   |
| nl_BE | 1         | 1.92%   |
| fi_FI | 1         | 1.92%   |
| es_MX | 1         | 1.92%   |
| es_HN | 1         | 1.92%   |
| es_CO | 1         | 1.92%   |
| en_NG | 1         | 1.92%   |
| en_GB | 1         | 1.92%   |
| da_DK | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 37        | 71.15%  |
| EFI  | 15        | 28.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 52        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 50        | 96.15%  |
| MBR     | 1         | 1.92%   |
| GPT     | 1         | 1.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 51        | 98.08%  |
| Yes       | 1         | 1.92%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 96.15%  |
| Yes       | 2         | 3.85%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 13        | 25%     |
| Dell                | 8         | 15.38%  |
| Acer                | 8         | 15.38%  |
| Lenovo              | 5         | 9.62%   |
| Samsung Electronics | 4         | 7.69%   |
| Toshiba             | 3         | 5.77%   |
| ASUSTek Computer    | 3         | 5.77%   |
| Positivo            | 2         | 3.85%   |
| GPU Company         | 1         | 1.92%   |
| Google              | 1         | 1.92%   |
| Fujitsu Siemens     | 1         | 1.92%   |
| Fujitsu             | 1         | 1.92%   |
| Apple               | 1         | 1.92%   |
| Alienware           | 1         | 1.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| HP 255 G6 Notebook PC                                                                    | 2         | 3.85%   |
| Toshiba TECRA R850                                                                       | 1         | 1.92%   |
| Toshiba Satellite P300                                                                   | 1         | 1.92%   |
| Toshiba Satellite C660                                                                   | 1         | 1.92%   |
| Samsung RV415/RV515/E3415                                                                | 1         | 1.92%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411                                              | 1         | 1.92%   |
| Samsung RF511/RF411/RF711                                                                | 1         | 1.92%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1.92%   |
| Positivo Smash3                                                                          | 1         | 1.92%   |
| Positivo Smash                                                                           | 1         | 1.92%   |
| Lenovo ThinkPad L380 20M6S4E000                                                          | 1         | 1.92%   |
| Lenovo IdeaPad Y510P 20217                                                               | 1         | 1.92%   |
| Lenovo G550 2958                                                                         | 1         | 1.92%   |
| Lenovo G50-80 80R0                                                                       | 1         | 1.92%   |
| Lenovo G50-80 80E5                                                                       | 1         | 1.92%   |
| HP ProBook 4720s                                                                         | 1         | 1.92%   |
| HP ProBook 440 G1                                                                        | 1         | 1.92%   |
| HP Pavilion g6                                                                           | 1         | 1.92%   |
| HP Pavilion dv6700                                                                       | 1         | 1.92%   |
| HP Pavilion 14                                                                           | 1         | 1.92%   |
| HP Laptop 15-bw0xx                                                                       | 1         | 1.92%   |
| HP Laptop 14-dk1xxx                                                                      | 1         | 1.92%   |
| HP G62                                                                                   | 1         | 1.92%   |
| HP EliteBook 8440p                                                                       | 1         | 1.92%   |
| HP Compaq CQ45                                                                           | 1         | 1.92%   |
| HP Compaq 6730b (NA373UC#ABA)                                                            | 1         | 1.92%   |
| GPU Company GWTN116-3                                                                    | 1         | 1.92%   |
| Google Peppy                                                                             | 1         | 1.92%   |
| Fujitsu Siemens AMILO Xi 1526                                                            | 1         | 1.92%   |
| Fujitsu CELSIUS H700                                                                     | 1         | 1.92%   |
| Dell System XPS L502X                                                                    | 1         | 1.92%   |
| Dell Precision M6400                                                                     | 1         | 1.92%   |
| Dell Latitude E6540                                                                      | 1         | 1.92%   |
| Dell Latitude E6420                                                                      | 1         | 1.92%   |
| Dell Latitude E6400                                                                      | 1         | 1.92%   |
| Dell Latitude E5400                                                                      | 1         | 1.92%   |
| Dell Inspiron N5050                                                                      | 1         | 1.92%   |
| Dell G5 5590                                                                             | 1         | 1.92%   |
| ASUS X751LAB                                                                             | 1         | 1.92%   |
| ASUS N71Vg                                                                               | 1         | 1.92%   |
| ASUS K95VM                                                                               | 1         | 1.92%   |
| Apple MacBookPro5,5                                                                      | 1         | 1.92%   |
| Alienware M17xR3                                                                         | 1         | 1.92%   |
| Acer TravelMate 5744                                                                     | 1         | 1.92%   |
| Acer One S1002                                                                           | 1         | 1.92%   |
| Acer Extensa 5220                                                                        | 1         | 1.92%   |
| Acer Aspire XXXX                                                                         | 1         | 1.92%   |
| Acer Aspire E1-570                                                                       | 1         | 1.92%   |
| Acer Aspire 5741                                                                         | 1         | 1.92%   |
| Acer Aspire 5738                                                                         | 1         | 1.92%   |
| Acer Aspire 5735                                                                         | 1         | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 5         | 9.62%   |
| Dell Latitude         | 4         | 7.69%   |
| HP Pavilion           | 3         | 5.77%   |
| Toshiba Satellite     | 2         | 3.85%   |
| Lenovo G50-80         | 2         | 3.85%   |
| HP ProBook            | 2         | 3.85%   |
| HP Laptop             | 2         | 3.85%   |
| HP Compaq             | 2         | 3.85%   |
| HP 255                | 2         | 3.85%   |
| Toshiba TECRA         | 1         | 1.92%   |
| Samsung RV415         | 1         | 1.92%   |
| Samsung RV411         | 1         | 1.92%   |
| Samsung RF511         | 1         | 1.92%   |
| Samsung 355V4C        | 1         | 1.92%   |
| Positivo Smash3       | 1         | 1.92%   |
| Positivo Smash        | 1         | 1.92%   |
| Lenovo ThinkPad       | 1         | 1.92%   |
| Lenovo IdeaPad        | 1         | 1.92%   |
| Lenovo G550           | 1         | 1.92%   |
| HP G62                | 1         | 1.92%   |
| HP EliteBook          | 1         | 1.92%   |
| GPU Company GWTN116-3 | 1         | 1.92%   |
| Google Peppy          | 1         | 1.92%   |
| Fujitsu Siemens AMILO | 1         | 1.92%   |
| Fujitsu CELSIUS       | 1         | 1.92%   |
| Dell System           | 1         | 1.92%   |
| Dell Precision        | 1         | 1.92%   |
| Dell Inspiron         | 1         | 1.92%   |
| Dell G5               | 1         | 1.92%   |
| ASUS X751LAB          | 1         | 1.92%   |
| ASUS N71Vg            | 1         | 1.92%   |
| ASUS K95VM            | 1         | 1.92%   |
| Apple MacBookPro5     | 1         | 1.92%   |
| Alienware M17xR3      | 1         | 1.92%   |
| Acer TravelMate       | 1         | 1.92%   |
| Acer One              | 1         | 1.92%   |
| Acer Extensa          | 1         | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 12        | 23.08%  |
| 2013 | 5         | 9.62%   |
| 2010 | 5         | 9.62%   |
| 2009 | 5         | 9.62%   |
| 2019 | 4         | 7.69%   |
| 2008 | 4         | 7.69%   |
| 2017 | 3         | 5.77%   |
| 2015 | 3         | 5.77%   |
| 2007 | 3         | 5.77%   |
| 2021 | 2         | 3.85%   |
| 2014 | 2         | 3.85%   |
| 2012 | 2         | 3.85%   |
| 2018 | 1         | 1.92%   |
| 2016 | 1         | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 52        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 49        | 94.23%  |
| Enabled  | 3         | 5.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 51        | 98.08%  |
| Yes  | 1         | 1.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 18        | 34.62%  |
| 4.01-8.0   | 14        | 26.92%  |
| 8.01-16.0  | 11        | 21.15%  |
| 1.01-2.0   | 3         | 5.77%   |
| 2.01-3.0   | 2         | 3.85%   |
| 16.01-24.0 | 2         | 3.85%   |
| 32.01-64.0 | 1         | 1.92%   |
| 24.01-32.0 | 1         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 31        | 57.41%  |
| 2.01-3.0 | 13        | 24.07%  |
| 3.01-4.0 | 5         | 9.26%   |
| 0.51-1.0 | 5         | 9.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 73.58%  |
| 2      | 12        | 22.64%  |
| 3      | 2         | 3.77%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 76.92%  |
| No        | 12        | 23.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 92.31%  |
| No        | 4         | 7.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 92.31%  |
| No        | 4         | 7.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 63.46%  |
| No        | 19        | 36.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 15.38%  |
| Germany     | 7         | 13.46%  |
| Brazil      | 7         | 13.46%  |
| France      | 3         | 5.77%   |
| Australia   | 3         | 5.77%   |
| Poland      | 2         | 3.85%   |
| Italy       | 2         | 3.85%   |
| India       | 2         | 3.85%   |
| Greece      | 2         | 3.85%   |
| Czechia     | 2         | 3.85%   |
| Ukraine     | 1         | 1.92%   |
| UK          | 1         | 1.92%   |
| Portugal    | 1         | 1.92%   |
| Pakistan    | 1         | 1.92%   |
| Nigeria     | 1         | 1.92%   |
| Netherlands | 1         | 1.92%   |
| Mexico      | 1         | 1.92%   |
| Jamaica     | 1         | 1.92%   |
| Honduras    | 1         | 1.92%   |
| Finland     | 1         | 1.92%   |
| Denmark     | 1         | 1.92%   |
| Colombia    | 1         | 1.92%   |
| Canada      | 1         | 1.92%   |
| Belgium     | 1         | 1.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Warsaw           | 2         | 3.7%    |
| Hobart           | 2         | 3.7%    |
| Zaventem         | 1         | 1.85%   |
| Wabern           | 1         | 1.85%   |
| Vivian           | 1         | 1.85%   |
| Vicksburg        | 1         | 1.85%   |
| Toluca           | 1         | 1.85%   |
| Tegucigalpa      | 1         | 1.85%   |
| Spicheren        | 1         | 1.85%   |
| Shamrock         | 1         | 1.85%   |
| Senas            | 1         | 1.85%   |
| SÃ£o Paulo     | 1         | 1.85%   |
| Sankt Augustin   | 1         | 1.85%   |
| Rome             | 1         | 1.85%   |
| Rio de Janeiro   | 1         | 1.85%   |
| Rio das Ostras   | 1         | 1.85%   |
| Ringgold         | 1         | 1.85%   |
| Reims            | 1         | 1.85%   |
| Prague           | 1         | 1.85%   |
| Porto            | 1         | 1.85%   |
| Oswego           | 1         | 1.85%   |
| Oshawa           | 1         | 1.85%   |
| Odense           | 1         | 1.85%   |
| Northwich        | 1         | 1.85%   |
| North Plains     | 1         | 1.85%   |
| Naples           | 1         | 1.85%   |
| Mandi            | 1         | 1.85%   |
| Lutjegast        | 1         | 1.85%   |
| Lohja            | 1         | 1.85%   |
| Lagos            | 1         | 1.85%   |
| Kladno           | 1         | 1.85%   |
| Kingston         | 1         | 1.85%   |
| Karachi          | 1         | 1.85%   |
| JoÃ£o Pessoa   | 1         | 1.85%   |
| Itaperuna        | 1         | 1.85%   |
| Ibipitanga       | 1         | 1.85%   |
| HÃ¶xter        | 1         | 1.85%   |
| Grossenhain      | 1         | 1.85%   |
| GÃ¼tersloh     | 1         | 1.85%   |
| Garbsen          | 1         | 1.85%   |
| East Stroudsburg | 1         | 1.85%   |
| Corinth          | 1         | 1.85%   |
| ChapecÃ³       | 1         | 1.85%   |
| Chandigarh       | 1         | 1.85%   |
| Catanduva        | 1         | 1.85%   |
| Brussels         | 1         | 1.85%   |
| Brisbane         | 1         | 1.85%   |
| BogotÃ¡        | 1         | 1.85%   |
| Bila Tserkva     | 1         | 1.85%   |
| Berlin           | 1         | 1.85%   |
| Athens           | 1         | 1.85%   |
| Allen Park       | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 14.75%  |
| Toshiba             | 9         | 9      | 14.75%  |
| Seagate             | 8         | 10     | 13.11%  |
| Unknown             | 5         | 9      | 8.2%    |
| SanDisk             | 3         | 3      | 4.92%   |
| Hitachi             | 3         | 3      | 4.92%   |
| Crucial             | 3         | 4      | 4.92%   |
| PNY                 | 2         | 2      | 3.28%   |
| Patriot             | 2         | 2      | 3.28%   |
| JMicron             | 2         | 2      | 3.28%   |
| HGST                | 2         | 2      | 3.28%   |
| SK Hynix            | 1         | 2      | 1.64%   |
| Samsung Electronics | 1         | 1      | 1.64%   |
| Micron_1            | 1         | 2      | 1.64%   |
| LITEON              | 1         | 1      | 1.64%   |
| Lenovo              | 1         | 1      | 1.64%   |
| Kingston            | 1         | 1      | 1.64%   |
| I/OMAGIC            | 1         | 1      | 1.64%   |
| HEORIADY            | 1         | 1      | 1.64%   |
| DOGFISH             | 1         | 1      | 1.64%   |
| AMD                 | 1         | 1      | 1.64%   |
| ALERTSEAL           | 1         | 1      | 1.64%   |
| A-DATA Technology   | 1         | 1      | 1.64%   |
| Unknown             | 1         | 1      | 1.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  64GB              | 3         | 4.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 4.69%   |
| Toshiba MK2552GSX 250GB             | 2         | 3.13%   |
| Patriot Burst 120GB SSD             | 2         | 3.13%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1         | 1.56%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 1.56%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1.56%   |
| WDC WD5000BPVT-60HXZT1 500GB        | 1         | 1.56%   |
| WDC WD5000BPVT-22HXZT3 500GB        | 1         | 1.56%   |
| WDC WD3200BEKT-00PVMT0 320GB        | 1         | 1.56%   |
| WDC WD2500BEVT-24A23T0 250GB        | 1         | 1.56%   |
| WDC WD1600BEVT-75ZCT1 160GB         | 1         | 1.56%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1.56%   |
| Unknown SD  128GB                   | 1         | 1.56%   |
| Unknown MMC Card  7GB               | 1         | 1.56%   |
| Unknown MMC Card  32GB              | 1         | 1.56%   |
| Unknown BJTD4R  32GB                | 1         | 1.56%   |
| Toshiba MQ04ABF100 1TB              | 1         | 1.56%   |
| Toshiba MQ01ACF032 320GB            | 1         | 1.56%   |
| Toshiba MQ01ABF032 320GB            | 1         | 1.56%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1.56%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1.56%   |
| Toshiba MQ01ABD032 320GB            | 1         | 1.56%   |
| Toshiba MK1656GSYF 160GB            | 1         | 1.56%   |
| SK Hynix NVMe SSD Drive 512GB       | 1         | 1.56%   |
| SK Hynix BC511 NVMe 512GB           | 1         | 1.56%   |
| Seagate ST9250410AS 250GB           | 1         | 1.56%   |
| Seagate ST9250315AS 250GB           | 1         | 1.56%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1.56%   |
| Seagate ST320LT007-9ZV142 320GB     | 1         | 1.56%   |
| Seagate ST1000DM003-9YN162 1TB      | 1         | 1.56%   |
| SanDisk SDSSDX240GG25 240GB         | 1         | 1.56%   |
| SanDisk SDSSDH3 500G                | 1         | 1.56%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1.56%   |
| Samsung SSD 850 EVO 1TB             | 1         | 1.56%   |
| PNY CS900 480GB SSD                 | 1         | 1.56%   |
| PNY CS900 120GB SSD                 | 1         | 1.56%   |
| Micron_1 100_MTFDDAV256TB 256GB SSD | 1         | 1.56%   |
| LITEON CV1-8B256 256GB SSD          | 1         | 1.56%   |
| Lenovo NVMe SSD Drive 256GB         | 1         | 1.56%   |
| Kingston SA400S37240G 240GB SSD     | 1         | 1.56%   |
| JMicron Tech 250GB                  | 1         | 1.56%   |
| JMicron Generic 2TB                 | 1         | 1.56%   |
| I/OMAGIC BLACK DIAMOND 256GB        | 1         | 1.56%   |
| Hitachi HTS725032A9A364 320GB       | 1         | 1.56%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1.56%   |
| Hitachi HTS545025B9A300 250GB       | 1         | 1.56%   |
| HGST HTS545050A7E680 500GB          | 1         | 1.56%   |
| HGST HTS545032A7E680 320GB          | 1         | 1.56%   |
| HEORIADY SSD HX-001 E 128G          | 1         | 1.56%   |
| DOGFISH SSD 512GB                   | 1         | 1.56%   |
| Crucial CT250MX500SSD1 250GB        | 1         | 1.56%   |
| Crucial CT120BX500SSD1 120GB        | 1         | 1.56%   |
| Crucial CT1000MX500SSD1 1TB         | 1         | 1.56%   |
| AMD R3SL240G 240GB SSD              | 1         | 1.56%   |
| ALERTSEAL SSD 48GB                  | 1         | 1.56%   |
| A-DATA SU750 512GB SSD              | 1         | 1.56%   |
| Unknown                             | 1         | 1.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 9         | 9      | 31.03%  |
| Seagate | 8         | 10     | 27.59%  |
| WDC     | 7         | 7      | 24.14%  |
| Hitachi | 3         | 3      | 10.34%  |
| HGST    | 2         | 2      | 6.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 14.29%  |
| Crucial             | 3         | 4      | 14.29%  |
| WDC                 | 2         | 2      | 9.52%   |
| PNY                 | 2         | 2      | 9.52%   |
| Patriot             | 2         | 2      | 9.52%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| Micron_1            | 1         | 2      | 4.76%   |
| LITEON              | 1         | 1      | 4.76%   |
| Kingston            | 1         | 1      | 4.76%   |
| HEORIADY            | 1         | 1      | 4.76%   |
| DOGFISH             | 1         | 1      | 4.76%   |
| AMD                 | 1         | 1      | 4.76%   |
| ALERTSEAL           | 1         | 1      | 4.76%   |
| A-DATA Technology   | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 29        | 31     | 48.33%  |
| SSD     | 20        | 23     | 33.33%  |
| MMC     | 6         | 10     | 10%     |
| NVMe    | 3         | 4      | 5%      |
| Unknown | 2         | 2      | 3.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 52     | 79.66%  |
| MMC  | 6         | 10     | 10.17%  |
| SAS  | 4         | 5      | 6.78%   |
| NVMe | 2         | 3      | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 39     | 72.92%  |
| 0.51-1.0   | 13        | 15     | 27.08%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 17        | 32.08%  |
| 251-500    | 12        | 22.64%  |
| 501-1000   | 9         | 16.98%  |
| 21-50      | 8         | 15.09%  |
| 51-100     | 6         | 11.32%  |
| 1001-2000  | 1         | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 21-50   | 25        | 47.17%  |
| 1-20    | 17        | 32.08%  |
| 51-100  | 6         | 11.32%  |
| 101-250 | 5         | 9.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 51        | 68     | 96.23%  |
| Works    | 2         | 2      | 3.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 40        | 78.43%  |
| AMD              | 7         | 13.73%  |
| VIA Technologies | 1         | 1.96%   |
| SK Hynix         | 1         | 1.96%   |
| Nvidia           | 1         | 1.96%   |
| Lenovo           | 1         | 1.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 8         | 14.04%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 10.53%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 8.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 4         | 7.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 7.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 5.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 3.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 3.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 3.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 3.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 2         | 3.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 2         | 3.51%   |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 1.75%   |
| SK Hynix BC511                                                                         | 1         | 1.75%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.75%   |
| Lenovo Non-Volatile memory controller                                                  | 1         | 1.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.75%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.75%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                  | 1         | 1.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 1         | 1.75%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 40        | 75.47%  |
| IDE  | 6         | 11.32%  |
| RAID | 5         | 9.43%   |
| NVMe | 2         | 3.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 86.54%  |
| AMD    | 7         | 13.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 3         | 5.77%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 3.85%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 3.85%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 3.85%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 3.85%   |
| AMD A6-9220 RADEON R4, 5 COMPUTE CORES 2C+3G  | 2         | 3.85%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 1.92%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 1.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.92%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.92%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 1.92%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.92%   |
| Intel Core i7-2820QM CPU @ 2.30GHz            | 1         | 1.92%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 1.92%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.92%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.92%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.92%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.92%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.92%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 1.92%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.92%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.92%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 1.92%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 1.92%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 1         | 1.92%   |
| Intel Core 2 Extreme CPU Q9300 @ 2.53GHz      | 1         | 1.92%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 1.92%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz          | 1         | 1.92%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 1         | 1.92%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz          | 1         | 1.92%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 1         | 1.92%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 1.92%   |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 1         | 1.92%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 1.92%   |
| Intel Celeron Dual-Core CPU T3500 @ 2.10GHz   | 1         | 1.92%   |
| Intel Celeron CPU 3215U @ 1.70GHz             | 1         | 1.92%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 1.92%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 1         | 1.92%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 1         | 1.92%   |
| AMD E-450 APU with Radeon HD Graphics         | 1         | 1.92%   |
| AMD E-300 APU with Radeon HD Graphics         | 1         | 1.92%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 1         | 1.92%   |
| AMD A6-4400M APU with Radeon HD Graphics      | 1         | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 9         | 17.31%  |
| Intel Core i5           | 9         | 17.31%  |
| Intel Core 2 Duo        | 9         | 17.31%  |
| Intel Core i3           | 7         | 13.46%  |
| Intel Celeron           | 3         | 5.77%   |
| Intel Atom              | 3         | 5.77%   |
| AMD A6                  | 3         | 5.77%   |
| AMD E                   | 2         | 3.85%   |
| Intel Pentium Dual-Core | 1         | 1.92%   |
| Intel Pentium Dual      | 1         | 1.92%   |
| Intel Core 2 Extreme    | 1         | 1.92%   |
| Intel Core 2            | 1         | 1.92%   |
| Intel Celeron Dual-Core | 1         | 1.92%   |
| AMD E2                  | 1         | 1.92%   |
| AMD Athlon              | 1         | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 40        | 76.92%  |
| 4      | 10        | 19.23%  |
| 6      | 1         | 1.92%   |
| 1      | 1         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 52        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 26        | 50%     |
| 1      | 26        | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 52        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x1067a    | 10        | 19.23%  |
| 0x206a7    | 7         | 13.46%  |
| 0x20652    | 4         | 7.69%   |
| 0x306d4    | 3         | 5.77%   |
| 0x306c3    | 3         | 5.77%   |
| 0x6fd      | 2         | 3.85%   |
| 0x406c4    | 2         | 3.85%   |
| 0x40651    | 2         | 3.85%   |
| 0x306a9    | 2         | 3.85%   |
| 0x20655    | 2         | 3.85%   |
| 0x06006705 | 2         | 3.85%   |
| 0x05000119 | 2         | 3.85%   |
| 0x906ea    | 1         | 1.92%   |
| 0x806ea    | 1         | 1.92%   |
| 0x706a8    | 1         | 1.92%   |
| 0x6f6      | 1         | 1.92%   |
| 0x506e3    | 1         | 1.92%   |
| 0x30678    | 1         | 1.92%   |
| 0x106e5    | 1         | 1.92%   |
| 0x10676    | 1         | 1.92%   |
| 0x08108109 | 1         | 1.92%   |
| 0x06006704 | 1         | 1.92%   |
| 0x06001119 | 1         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Penryn        | 11        | 21.15%  |
| SandyBridge   | 7         | 13.46%  |
| Westmere      | 6         | 11.54%  |
| Haswell       | 5         | 9.62%   |
| Silvermont    | 3         | 5.77%   |
| Excavator     | 3         | 5.77%   |
| Core          | 3         | 5.77%   |
| Broadwell     | 3         | 5.77%   |
| KabyLake      | 2         | 3.85%   |
| IvyBridge     | 2         | 3.85%   |
| Bobcat        | 2         | 3.85%   |
| Zen+          | 1         | 1.92%   |
| Skylake       | 1         | 1.92%   |
| Piledriver    | 1         | 1.92%   |
| Nehalem       | 1         | 1.92%   |
| Goldmont plus | 1         | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 58.73%  |
| Nvidia | 15        | 23.81%  |
| AMD    | 11        | 17.46%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 10.77%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 10.77%  |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 7.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 4.62%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 4.62%   |
| Intel HD Graphics 5500                                                                   | 2         | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 3.08%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.54%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.54%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.54%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.54%   |
| Nvidia GK107M [GeForce GT 755M]                                                          | 1         | 1.54%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 1.54%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.54%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.54%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.54%   |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 1.54%   |
| Nvidia G96CM [GeForce GT 220M]                                                           | 1         | 1.54%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 1.54%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 1.54%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 1.54%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.54%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.54%   |
| Intel HD Graphics 530                                                                    | 1         | 1.54%   |
| Intel HD Graphics                                                                        | 1         | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.54%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.54%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 1.54%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.54%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.54%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.54%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                             | 1         | 1.54%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 1.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.54%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 50%     |
| Intel + Nvidia | 9         | 17.31%  |
| 1 x AMD        | 8         | 15.38%  |
| 1 x Nvidia     | 6         | 11.54%  |
| Intel + AMD    | 2         | 3.85%   |
| 2 x AMD        | 1         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 48        | 92.31%  |
| Unknown     | 3         | 5.77%   |
| Proprietary | 1         | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 57.69%  |
| 0.01-0.5   | 11        | 21.15%  |
| 0.51-1.0   | 7         | 13.46%  |
| 1.01-2.0   | 2         | 3.85%   |
| 5.01-6.0   | 1         | 1.92%   |
| 3.01-4.0   | 1         | 1.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 14        | 28%     |
| Samsung Electronics     | 12        | 24%     |
| AU Optronics            | 10        | 20%     |
| Chimei Innolux          | 4         | 8%      |
| LG Philips              | 2         | 4%      |
| BOE                     | 2         | 4%      |
| PANDA                   | 1         | 2%      |
| Lenovo                  | 1         | 2%      |
| Goldstar                | 1         | 2%      |
| Dell                    | 1         | 2%      |
| Chi Mei Optoelectronics | 1         | 2%      |
| Apple                   | 1         | 2%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch      | 2         | 4%      |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch      | 2         | 4%      |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch             | 2         | 4%      |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch      | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch      | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch      | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch      | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch      | 1         | 2%      |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch      | 1         | 2%      |
| Samsung Electronics LCD Monitor SAM03D3 1360x768 410x256mm 19.0-inch      | 1         | 2%      |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch                   | 1         | 2%      |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch               | 1         | 2%      |
| LG Philips LCD Monitor LPL012B 1280x800 304x190mm 14.1-inch               | 1         | 2%      |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch             | 1         | 2%      |
| LG Display LCD Monitor LGD7001 1366x768 344x194mm 15.5-inch               | 1         | 2%      |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 1         | 2%      |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 1         | 2%      |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch               | 1         | 2%      |
| LG Display LCD Monitor LGD03DD 1366x768 344x194mm 15.5-inch               | 1         | 2%      |
| LG Display LCD Monitor LGD03B3 1366x768 310x174mm 14.0-inch               | 1         | 2%      |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch               | 1         | 2%      |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 2%      |
| LG Display LCD Monitor LGD02D9 1920x1080 345x194mm 15.6-inch              | 1         | 2%      |
| LG Display LCD Monitor LGD02A6 1366x768 345x194mm 15.6-inch               | 1         | 2%      |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch               | 1         | 2%      |
| LG Display LCD Monitor LGD01AF 1680x1050 331x207mm 15.4-inch              | 1         | 2%      |
| LG Display LCD Monitor LGD018E 1920x1200 367x230mm 17.1-inch              | 1         | 2%      |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                   | 1         | 2%      |
| Goldstar 32LG7000 GSM765E 1920x1080 700x390mm 31.5-inch                   | 1         | 2%      |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                          | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN14E3 1366x768 309x173mm 13.9-inch           | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 1         | 2%      |
| Chi Mei Optoelectronics LCD Monitor CMO1808 1920x1080 408x230mm 18.4-inch | 1         | 2%      |
| BOE LCD Monitor BOE097F 1366x768 256x144mm 11.6-inch                      | 1         | 2%      |
| BOE LCD Monitor BOE0827 1366x768 309x174mm 14.0-inch                      | 1         | 2%      |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 1         | 2%      |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 1         | 2%      |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 1         | 2%      |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 1         | 2%      |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 1         | 2%      |
| AU Optronics LCD Monitor AUO162C 1366x768 293x164mm 13.2-inch             | 1         | 2%      |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 1         | 2%      |
| AU Optronics LCD Monitor AUO1101 1440x900 367x230mm 17.1-inch             | 1         | 2%      |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch                    | 1         | 2%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 27        | 55.1%   |
| 1920x1080 (FHD)    | 5         | 10.2%   |
| 1600x900 (HD+)     | 5         | 10.2%   |
| 1440x900 (WXGA+)   | 4         | 8.16%   |
| 1280x800 (WXGA)    | 3         | 6.12%   |
| 3840x2160 (4K)     | 2         | 4.08%   |
| 1920x1200 (WUXGA)  | 1         | 2.04%   |
| 1680x1050 (WSXGA+) | 1         | 2.04%   |
| 1360x768           | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 25        | 50%     |
| 17     | 9         | 18%     |
| 14     | 6         | 12%     |
| 13     | 4         | 8%      |
| 31     | 2         | 4%      |
| 11     | 2         | 4%      |
| 19     | 1         | 2%      |
| 18     | 1         | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 64%     |
| 351-400     | 10        | 20%     |
| 201-300     | 4         | 8%      |
| 601-700     | 2         | 4%      |
| 401-500     | 2         | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 37        | 75.51%  |
| 16/10 | 12        | 24.49%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 50%     |
| 81-90          | 8         | 16%     |
| 131-140        | 6         | 12%     |
| 121-130        | 3         | 6%      |
| 71-80          | 2         | 4%      |
| 51-60          | 2         | 4%      |
| 351-500        | 2         | 4%      |
| 151-200        | 1         | 2%      |
| 141-150        | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 30        | 60%     |
| 51-100  | 10        | 20%     |
| 121-160 | 9         | 18%     |
| 1-50    | 1         | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 47        | 90.38%  |
| 2     | 3         | 5.77%   |
| 0     | 2         | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 30%     |
| Intel                    | 21        | 23.33%  |
| Qualcomm Atheros         | 13        | 14.44%  |
| Broadcom                 | 13        | 14.44%  |
| Broadcom Limited         | 6         | 6.67%   |
| Samsung Electronics      | 2         | 2.22%   |
| Marvell Technology Group | 2         | 2.22%   |
| Toshiba                  | 1         | 1.11%   |
| Ralink Technology        | 1         | 1.11%   |
| Ralink                   | 1         | 1.11%   |
| Nvidia                   | 1         | 1.11%   |
| MediaTek                 | 1         | 1.11%   |
| Lenovo                   | 1         | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 15.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 6.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 3.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 2.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 2.94%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 2.94%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 2.94%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.96%   |
| Intel Wireless 3160                                               | 2         | 1.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.96%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.96%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 2         | 1.96%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 1.96%   |
| Toshiba F5521gw                                                   | 1         | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.98%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.98%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.98%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.98%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.98%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.98%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.98%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.98%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.98%   |
| MediaTek 802.11 n WLAN                                            | 1         | 0.98%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.98%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.98%   |
| Lenovo Thinkpad USB LAN                                           | 1         | 0.98%   |
| Intel Wireless 8265 / 8275                                        | 1         | 0.98%   |
| Intel Wireless 7260                                               | 1         | 0.98%   |
| Intel WiFi Link 5100                                              | 1         | 0.98%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 0.98%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 0.98%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.98%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 0.98%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 0.98%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 0.98%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.98%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.98%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.98%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.98%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.98%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.98%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.98%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 0.98%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.98%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 1         | 0.98%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 1         | 0.98%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 0.98%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 38%     |
| Qualcomm Atheros      | 11        | 22%     |
| Broadcom              | 11        | 22%     |
| Realtek Semiconductor | 4         | 8%      |
| Broadcom Limited      | 2         | 4%      |
| Ralink Technology     | 1         | 2%      |
| Ralink                | 1         | 2%      |
| MediaTek              | 1         | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 8%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 6%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 6%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 6%      |
| Intel Centrino Advanced-N 6200                                 | 3         | 6%      |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 6%      |
| Intel Wireless 3160                                            | 2         | 4%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 4%      |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2%      |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 2%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 2%      |
| Realtek 802.11n WLAN Adapter                                   | 1         | 2%      |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 2%      |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 2%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 2%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2%      |
| MediaTek 802.11 n WLAN                                         | 1         | 2%      |
| Intel Wireless 8265 / 8275                                     | 1         | 2%      |
| Intel Wireless 7260                                            | 1         | 2%      |
| Intel WiFi Link 5100                                           | 1         | 2%      |
| Intel Ultimate N WiFi Link 5300                                | 1         | 2%      |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 2%      |
| Intel Centrino Wireless-N 2230                                 | 1         | 2%      |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2%      |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 2%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2%      |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 1         | 2%      |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 2%      |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 2%      |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 25        | 50%     |
| Intel                    | 7         | 14%     |
| Broadcom                 | 5         | 10%     |
| Broadcom Limited         | 4         | 8%      |
| Qualcomm Atheros         | 3         | 6%      |
| Samsung Electronics      | 2         | 4%      |
| Marvell Technology Group | 2         | 4%      |
| Nvidia                   | 1         | 2%      |
| Lenovo                   | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 31.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 13.73%  |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 3.92%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 3.92%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 2         | 3.92%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.96%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 1.96%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.96%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.96%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.96%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.96%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 1.96%   |
| Lenovo Thinkpad USB LAN                                           | 1         | 1.96%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.96%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.96%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.96%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.96%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.96%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.96%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.96%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.96%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.96%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 49.48%  |
| Ethernet | 48        | 49.48%  |
| Modem    | 1         | 1.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 47        | 52.22%  |
| WiFi     | 43        | 47.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 45        | 86.54%  |
| 0     | 4         | 7.69%   |
| 1     | 3         | 5.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 63.46%  |
| Yes  | 19        | 36.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 27.27%  |
| Dell                            | 4         | 12.12%  |
| Cambridge Silicon Radio         | 3         | 9.09%   |
| Realtek Semiconductor           | 2         | 6.06%   |
| Qualcomm Atheros                | 2         | 6.06%   |
| Lite-On Technology              | 2         | 6.06%   |
| Hewlett-Packard                 | 2         | 6.06%   |
| Foxconn / Hon Hai               | 2         | 6.06%   |
| Broadcom                        | 2         | 6.06%   |
| Toshiba                         | 1         | 3.03%   |
| Qualcomm Atheros Communications | 1         | 3.03%   |
| IMC Networks                    | 1         | 3.03%   |
| Askey Computer                  | 1         | 3.03%   |
| Apple                           | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 9.09%   |
| Intel Bluetooth Device                              | 3         | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 6.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 6.06%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 6.06%   |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 6.06%   |
| Dell DW375 Bluetooth Module                         | 2         | 6.06%   |
| Toshiba Askey Bluetooth Module                      | 1         | 3.03%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 3.03%   |
| Lite-On Atheros Bluetooth                           | 1         | 3.03%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.03%   |
| IMC Networks Bluetooth Device                       | 1         | 3.03%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 3.03%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 3.03%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 3.03%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 3.03%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 3.03%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 3.03%   |
| Askey Bluetooth Device                              | 1         | 3.03%   |
| Apple Bluetooth Host Controller                     | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 66.13%  |
| AMD                   | 10        | 16.13%  |
| Nvidia                | 9         | 14.52%  |
| Realtek Semiconductor | 1         | 1.61%   |
| GN Netcom             | 1         | 1.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 10        | 12.99%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7         | 9.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 7         | 9.09%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3         | 3.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3         | 3.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 3.9%    |
| Intel Broadwell-U Audio Controller                                                | 3         | 3.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3         | 3.9%    |
| AMD High Definition Audio Controller                                              | 3         | 3.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 3         | 3.9%    |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 2.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 2.6%    |
| Intel 8 Series HD Audio Controller                                                | 2         | 2.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2         | 2.6%    |
| AMD FCH Azalia Controller                                                         | 2         | 2.6%    |
| Realtek Semiconductor Realtek USB audio                                           | 1         | 1.3%    |
| Nvidia TU106 High Definition Audio Controller                                     | 1         | 1.3%    |
| Nvidia MCP79 High Definition Audio                                                | 1         | 1.3%    |
| Nvidia GT216 HDMI Audio Controller                                                | 1         | 1.3%    |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 1.3%    |
| Nvidia GF119 HDMI Audio Controller                                                | 1         | 1.3%    |
| Nvidia GF106 High Definition Audio Controller                                     | 1         | 1.3%    |
| Intel Sunrise Point-LP HD Audio                                                   | 1         | 1.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1         | 1.3%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1         | 1.3%    |
| Intel Cannon Lake PCH cAVS                                                        | 1         | 1.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1         | 1.3%    |
| GN Netcom Jabra EVOLVE 30 II                                                      | 1         | 1.3%    |
| AMD Wrestler HDMI Audio                                                           | 1         | 1.3%    |
| AMD Trinity HDMI Audio Controller                                                 | 1         | 1.3%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 1.3%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 1         | 1.3%    |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                   | 1         | 1.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 1.3%    |
| AMD Family 17h/19h HD Audio Controller                                            | 1         | 1.3%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 1         | 1.3%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 33.33%  |
| Kingston            | 2         | 33.33%  |
| Unknown             | 1         | 16.67%  |
| SK Hynix            | 1         | 16.67%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 533MT/s              | 1         | 14.29%  |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s              | 1         | 14.29%  |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1066MT/s            | 1         | 14.29%  |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 1         | 14.29%  |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 14.29%  |
| Kingston RAM KHX2666C15S4/16G 16384MB SODIMM DDR4 2667MT/s | 1         | 14.29%  |
| Kingston RAM 9905428-020.A00LF 4096MB SODIMM DDR3 1067MT/s | 1         | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR3 | 3         | 60%     |
| DDR4 | 1         | 20%     |
| DDR2 | 1         | 20%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 5         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 3         | 50%     |
| 16384 | 1         | 16.67%  |
| 2048  | 1         | 16.67%  |
| 1024  | 1         | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 1         | 16.67%  |
| 1600  | 1         | 16.67%  |
| 1334  | 1         | 16.67%  |
| 1067  | 1         | 16.67%  |
| 1066  | 1         | 16.67%  |
| 533   | 1         | 16.67%  |

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
| Chicony Electronics                    | 9         | 20.93%  |
| Silicon Motion                         | 4         | 9.3%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 9.3%    |
| Acer                                   | 4         | 9.3%    |
| Quanta                                 | 3         | 6.98%   |
| Microdia                               | 3         | 6.98%   |
| Suyin                                  | 2         | 4.65%   |
| Sunplus Innovation Technology          | 2         | 4.65%   |
| Ricoh                                  | 2         | 4.65%   |
| Realtek Semiconductor                  | 2         | 4.65%   |
| Z-Star Microelectronics                | 1         | 2.33%   |
| Syntek                                 | 1         | 2.33%   |
| Samsung Electronics                    | 1         | 2.33%   |
| Primax Electronics                     | 1         | 2.33%   |
| icSpring                               | 1         | 2.33%   |
| Apple                                  | 1         | 2.33%   |
| ALi                                    | 1         | 2.33%   |
| Alcor Micro                            | 1         | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Sunplus HD WebCam                                       | 2         | 4.65%   |
| Realtek USB Camera                                      | 2         | 4.65%   |
| Quanta HP Webcam                                        | 2         | 4.65%   |
| Chicony HD WebCam                                       | 2         | 4.65%   |
| Chicony CNF9055 Toshiba Webcam                          | 2         | 4.65%   |
| Acer Lenovo EasyCamera                                  | 2         | 4.65%   |
| Z-Star WebCam SC-03FFL11739P                            | 1         | 2.33%   |
| Syntek Lenovo EasyCamera                                | 1         | 2.33%   |
| Suyin UVC HD Webcam                                     | 1         | 2.33%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 2.33%   |
| Silicon Motion WebCam SCB-1100N                         | 1         | 2.33%   |
| Silicon Motion WebCam SCB-0385N                         | 1         | 2.33%   |
| Silicon Motion WebCam SC-0311139N                       | 1         | 2.33%   |
| Silicon Motion 300k Pixel Camera                        | 1         | 2.33%   |
| Samsung Galaxy A5 (MTP)                                 | 1         | 2.33%   |
| Ricoh Laptop_Integrated_Webcam_3M                       | 1         | 2.33%   |
| Ricoh Integrated Webcam                                 | 1         | 2.33%   |
| Quanta Laptop_Integrated_Webcam_2HDM                    | 1         | 2.33%   |
| Primax HP Webcam-101                                    | 1         | 2.33%   |
| Microdia Lenovo EasyCamera                              | 1         | 2.33%   |
| Microdia Laptop_Integrated_Webcam_0.3M                  | 1         | 2.33%   |
| Microdia Integrated_Webcam_HD                           | 1         | 2.33%   |
| icSpring camera                                         | 1         | 2.33%   |
| Chicony USB 2.0 Camera                                  | 1         | 2.33%   |
| Chicony HP Webcam                                       | 1         | 2.33%   |
| Chicony HP TrueVision HD Camera                         | 1         | 2.33%   |
| Chicony FJ Camera                                       | 1         | 2.33%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 1         | 2.33%   |
| Apple Built-in iSight                                   | 1         | 2.33%   |
| ALi Gateway Webcam                                      | 1         | 2.33%   |
| Alcor Micro USB 2.0 Camera                              | 1         | 2.33%   |
| Acer SunplusIT Integrated Camera                        | 1         | 2.33%   |
| Acer Crystal Eye webcam                                 | 1         | 2.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 50%     |
| AuthenTec        | 2         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS451 Fingerprint Reader | 2         | 50%     |
| AuthenTec Fingerprint Sensor               | 1         | 25%     |
| AuthenTec AES2550 Fingerprint Sensor       | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 37        | 71.15%  |
| 1     | 11        | 21.15%  |
| 2     | 4         | 7.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 6         | 33.33%  |
| Fingerprint reader    | 4         | 22.22%  |
| Storage               | 3         | 16.67%  |
| Chipcard              | 3         | 16.67%  |
| Net/wireless          | 1         | 5.56%   |
| Multimedia controller | 1         | 5.56%   |

