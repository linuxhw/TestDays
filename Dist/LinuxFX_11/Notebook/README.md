LinuxFX 11 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for LinuxFX 11.

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

Total: 97

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T420 4180MY7       | [e6a930e933](https://linux-hardware.org/?probe=e6a930e933) | Sep 19, 2022 |
| Dell          | Inspiron 5567               | [740ba48457](https://linux-hardware.org/?probe=740ba48457) | Jul 03, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | [a57e4e84f8](https://linux-hardware.org/?probe=a57e4e84f8) | Jun 29, 2022 |
| Toshiba       | Satellite A215              | [f609309a08](https://linux-hardware.org/?probe=f609309a08) | Jun 19, 2022 |
| Acer          | Aspire E1-531               | [ab72c3ae3f](https://linux-hardware.org/?probe=ab72c3ae3f) | May 03, 2022 |
| Dell          | Precision M4800             | [44583b1142](https://linux-hardware.org/?probe=44583b1142) | May 02, 2022 |
| ASUSTek       | Strix 17 GL703GE            | [a7396f278d](https://linux-hardware.org/?probe=a7396f278d) | May 02, 2022 |
| ASUSTek       | Strix 17 GL703GE            | [0e0d0dd3aa](https://linux-hardware.org/?probe=0e0d0dd3aa) | Apr 30, 2022 |
| Dell          | Precision M4700             | [850dba476c](https://linux-hardware.org/?probe=850dba476c) | Apr 15, 2022 |
| Acer          | Aspire 7735                 | [e54c0831d6](https://linux-hardware.org/?probe=e54c0831d6) | Apr 07, 2022 |
| Acer          | Aspire 5750G                | [8aeaa381e8](https://linux-hardware.org/?probe=8aeaa381e8) | Apr 03, 2022 |
| Acer          | Aspire 5750G                | [722346a184](https://linux-hardware.org/?probe=722346a184) | Apr 03, 2022 |
| HP            | ProBook 640 G1              | [0834bd783c](https://linux-hardware.org/?probe=0834bd783c) | Mar 30, 2022 |
| Apple         | MacBookPro5,2               | [3f0b633075](https://linux-hardware.org/?probe=3f0b633075) | Mar 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8a6bb86ea0](https://linux-hardware.org/?probe=8a6bb86ea0) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [271852ad10](https://linux-hardware.org/?probe=271852ad10) | Mar 17, 2022 |
| HP            | Laptop 15-da0xxx            | [b43ace9110](https://linux-hardware.org/?probe=b43ace9110) | Mar 11, 2022 |
| HP            | EliteBook 8570w             | [851e340c24](https://linux-hardware.org/?probe=851e340c24) | Mar 03, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [f3ec55a392](https://linux-hardware.org/?probe=f3ec55a392) | Feb 25, 2022 |
| Positivo      | Smash                       | [68fd957c2e](https://linux-hardware.org/?probe=68fd957c2e) | Feb 21, 2022 |
| Apple         | MacBookPro5,5               | [2ef0397f90](https://linux-hardware.org/?probe=2ef0397f90) | Feb 20, 2022 |
| Apple         | MacBookPro5,5               | [33c341d85e](https://linux-hardware.org/?probe=33c341d85e) | Feb 20, 2022 |
| HP            | EliteBook Folio 9470m       | [8f3df927df](https://linux-hardware.org/?probe=8f3df927df) | Feb 18, 2022 |
| ASUSTek       | X751LAB                     | [10ea8f6500](https://linux-hardware.org/?probe=10ea8f6500) | Feb 17, 2022 |
| HP            | Compaq CQ45                 | [51144497b2](https://linux-hardware.org/?probe=51144497b2) | Feb 16, 2022 |
| Apple         | MacBookPro5,5               | [75ee9c8a17](https://linux-hardware.org/?probe=75ee9c8a17) | Feb 10, 2022 |
| Dell          | Latitude E6420              | [85d1f4fe0a](https://linux-hardware.org/?probe=85d1f4fe0a) | Feb 09, 2022 |
| Apple         | MacBookPro5,5               | [cc840b5085](https://linux-hardware.org/?probe=cc840b5085) | Feb 05, 2022 |
| HP            | ProBook 4720s               | [aa5c35966f](https://linux-hardware.org/?probe=aa5c35966f) | Feb 04, 2022 |
| Acer          | Aspire 5741                 | [175d1e66d3](https://linux-hardware.org/?probe=175d1e66d3) | Feb 02, 2022 |
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
| HP            | Pavilion g6                 | [7be969965e](https://linux-hardware.org/?probe=7be969965e) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | [c53ba56444](https://linux-hardware.org/?probe=c53ba56444) | Oct 23, 2021 |
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
| 5.13.0-27-generic | 8         | 11.43%  |
| 5.11.0-37-generic | 8         | 11.43%  |
| 5.11.0-38-generic | 7         | 10%     |
| 5.13.0-28-generic | 6         | 8.57%   |
| 5.11.0-43-generic | 6         | 8.57%   |
| 5.11.0-40-generic | 5         | 7.14%   |
| 5.11.0-36-generic | 5         | 7.14%   |
| 5.13.0-39-generic | 4         | 5.71%   |
| 5.11.0-41-generic | 4         | 5.71%   |
| 5.13.0-30-generic | 3         | 4.29%   |
| 5.11.0-46-generic | 3         | 4.29%   |
| 5.13.0-51-generic | 2         | 2.86%   |
| 5.13.0-40-generic | 2         | 2.86%   |
| 5.13.0-35-generic | 2         | 2.86%   |
| 5.15.0-46-generic | 1         | 1.43%   |
| 5.13.0-25-generic | 1         | 1.43%   |
| 5.11.0-44-generic | 1         | 1.43%   |
| 5.11.0-42-generic | 1         | 1.43%   |
| 5.11.0-34-generic | 1         | 1.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 39        | 57.35%  |
| 5.13.0  | 28        | 41.18%  |
| 5.15.0  | 1         | 1.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 39        | 57.35%  |
| 5.13    | 28        | 41.18%  |
| 5.15    | 1         | 1.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 66        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 64        | 96.97%  |
| X-Cinnamon | 1         | 1.52%   |
| KDE        | 1         | 1.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 65        | 98.48%  |
| Wayland | 1         | 1.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 57        | 86.36%  |
| SDDM    | 9         | 13.64%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 16        | 24.24%  |
| de_DE | 9         | 13.64%  |
| pt_BR | 8         | 12.12%  |
| pl_PL | 4         | 6.06%   |
| it_IT | 3         | 4.55%   |
| fr_FR | 3         | 4.55%   |
| en_AU | 3         | 4.55%   |
| nl_NL | 2         | 3.03%   |
| en_IN | 2         | 3.03%   |
| el_GR | 2         | 3.03%   |
| cs_CZ | 2         | 3.03%   |
| ru_UA | 1         | 1.52%   |
| pt_PT | 1         | 1.52%   |
| nl_BE | 1         | 1.52%   |
| hr_BA | 1         | 1.52%   |
| fr_BE | 1         | 1.52%   |
| fi_FI | 1         | 1.52%   |
| es_MX | 1         | 1.52%   |
| es_HN | 1         | 1.52%   |
| es_CO | 1         | 1.52%   |
| en_NG | 1         | 1.52%   |
| en_GB | 1         | 1.52%   |
| da_DK | 1         | 1.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 47        | 71.21%  |
| EFI  | 19        | 28.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 65        | 98.48%  |
| Overlay | 1         | 1.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 64        | 96.97%  |
| MBR     | 1         | 1.52%   |
| GPT     | 1         | 1.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 65        | 98.48%  |
| Yes       | 1         | 1.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 95.45%  |
| Yes       | 3         | 4.55%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 16        | 24.24%  |
| Dell                | 11        | 16.67%  |
| Acer                | 11        | 16.67%  |
| Lenovo              | 7         | 10.61%  |
| Toshiba             | 4         | 6.06%   |
| Samsung Electronics | 4         | 6.06%   |
| ASUSTek Computer    | 4         | 6.06%   |
| Positivo            | 2         | 3.03%   |
| Apple               | 2         | 3.03%   |
| GPU Company         | 1         | 1.52%   |
| Google              | 1         | 1.52%   |
| Fujitsu Siemens     | 1         | 1.52%   |
| Fujitsu             | 1         | 1.52%   |
| Alienware           | 1         | 1.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| HP 255 G6 Notebook PC                                                                    | 2         | 3.03%   |
| Toshiba TECRA R850                                                                       | 1         | 1.52%   |
| Toshiba Satellite P300                                                                   | 1         | 1.52%   |
| Toshiba Satellite C660                                                                   | 1         | 1.52%   |
| Toshiba Satellite A215                                                                   | 1         | 1.52%   |
| Samsung RV415/RV515/E3415                                                                | 1         | 1.52%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411                                              | 1         | 1.52%   |
| Samsung RF511/RF411/RF711                                                                | 1         | 1.52%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1.52%   |
| Positivo Smash3                                                                          | 1         | 1.52%   |
| Positivo Smash                                                                           | 1         | 1.52%   |
| Lenovo ThinkPad T420 4180MY7                                                             | 1         | 1.52%   |
| Lenovo ThinkPad L380 20M6S4E000                                                          | 1         | 1.52%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                                                         | 1         | 1.52%   |
| Lenovo IdeaPad Y510P 20217                                                               | 1         | 1.52%   |
| Lenovo G550 2958                                                                         | 1         | 1.52%   |
| Lenovo G50-80 80R0                                                                       | 1         | 1.52%   |
| Lenovo G50-80 80E5                                                                       | 1         | 1.52%   |
| HP ProBook 640 G1                                                                        | 1         | 1.52%   |
| HP ProBook 4720s                                                                         | 1         | 1.52%   |
| HP ProBook 440 G1                                                                        | 1         | 1.52%   |
| HP Pavilion g6                                                                           | 1         | 1.52%   |
| HP Pavilion dv6700                                                                       | 1         | 1.52%   |
| HP Pavilion 14                                                                           | 1         | 1.52%   |
| HP Laptop 15-da0xxx                                                                      | 1         | 1.52%   |
| HP Laptop 15-bw0xx                                                                       | 1         | 1.52%   |
| HP Laptop 14-dk1xxx                                                                      | 1         | 1.52%   |
| HP G62                                                                                   | 1         | 1.52%   |
| HP EliteBook 8570w                                                                       | 1         | 1.52%   |
| HP EliteBook 8440p                                                                       | 1         | 1.52%   |
| HP Compaq CQ45                                                                           | 1         | 1.52%   |
| HP Compaq 6730b (NA373UC#ABA)                                                            | 1         | 1.52%   |
| GPU Company GWTN116-3                                                                    | 1         | 1.52%   |
| Google Peppy                                                                             | 1         | 1.52%   |
| Fujitsu Siemens AMILO Xi 1526                                                            | 1         | 1.52%   |
| Fujitsu CELSIUS H700                                                                     | 1         | 1.52%   |
| Dell System XPS L502X                                                                    | 1         | 1.52%   |
| Dell Precision M6400                                                                     | 1         | 1.52%   |
| Dell Precision M4800                                                                     | 1         | 1.52%   |
| Dell Precision M4700                                                                     | 1         | 1.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 8         | 12.12%  |
| Dell Latitude         | 4         | 6.06%   |
| Toshiba Satellite     | 3         | 4.55%   |
| HP ProBook            | 3         | 4.55%   |
| HP Pavilion           | 3         | 4.55%   |
| HP Laptop             | 3         | 4.55%   |
| Dell Precision        | 3         | 4.55%   |
| Lenovo ThinkPad       | 2         | 3.03%   |
| Lenovo G50-80         | 2         | 3.03%   |
| HP EliteBook          | 2         | 3.03%   |
| HP Compaq             | 2         | 3.03%   |
| HP 255                | 2         | 3.03%   |
| Dell Inspiron         | 2         | 3.03%   |
| Apple MacBookPro5     | 2         | 3.03%   |
| Toshiba TECRA         | 1         | 1.52%   |
| Samsung RV415         | 1         | 1.52%   |
| Samsung RV411         | 1         | 1.52%   |
| Samsung RF511         | 1         | 1.52%   |
| Samsung 355V4C        | 1         | 1.52%   |
| Positivo Smash3       | 1         | 1.52%   |
| Positivo Smash        | 1         | 1.52%   |
| Lenovo Legion         | 1         | 1.52%   |
| Lenovo IdeaPad        | 1         | 1.52%   |
| Lenovo G550           | 1         | 1.52%   |
| HP G62                | 1         | 1.52%   |
| GPU Company GWTN116-3 | 1         | 1.52%   |
| Google Peppy          | 1         | 1.52%   |
| Fujitsu Siemens AMILO | 1         | 1.52%   |
| Fujitsu CELSIUS       | 1         | 1.52%   |
| Dell System           | 1         | 1.52%   |
| Dell G5               | 1         | 1.52%   |
| ASUS X751LAB          | 1         | 1.52%   |
| ASUS Strix            | 1         | 1.52%   |
| ASUS N71Vg            | 1         | 1.52%   |
| ASUS K95VM            | 1         | 1.52%   |
| Alienware M17xR3      | 1         | 1.52%   |
| Acer TravelMate       | 1         | 1.52%   |
| Acer One              | 1         | 1.52%   |
| Acer Extensa          | 1         | 1.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 14        | 21.21%  |
| 2013 | 7         | 10.61%  |
| 2009 | 7         | 10.61%  |
| 2012 | 5         | 7.58%   |
| 2010 | 5         | 7.58%   |
| 2019 | 4         | 6.06%   |
| 2008 | 4         | 6.06%   |
| 2007 | 4         | 6.06%   |
| 2021 | 3         | 4.55%   |
| 2018 | 3         | 4.55%   |
| 2017 | 3         | 4.55%   |
| 2015 | 3         | 4.55%   |
| 2016 | 2         | 3.03%   |
| 2014 | 2         | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 66        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 63        | 95.45%  |
| Enabled  | 3         | 4.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 65        | 98.48%  |
| Yes  | 1         | 1.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 22        | 33.33%  |
| 4.01-8.0   | 16        | 24.24%  |
| 8.01-16.0  | 12        | 18.18%  |
| 16.01-24.0 | 7         | 10.61%  |
| 2.01-3.0   | 3         | 4.55%   |
| 1.01-2.0   | 3         | 4.55%   |
| 32.01-64.0 | 2         | 3.03%   |
| 24.01-32.0 | 1         | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 36        | 52.94%  |
| 2.01-3.0 | 18        | 26.47%  |
| 3.01-4.0 | 8         | 11.76%  |
| 0.51-1.0 | 5         | 7.35%   |
| 4.01-8.0 | 1         | 1.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 52        | 76.47%  |
| 2      | 14        | 20.59%  |
| 3      | 2         | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 76.12%  |
| No        | 16        | 23.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 92.42%  |
| No        | 5         | 7.58%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 93.94%  |
| No        | 4         | 6.06%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 65.15%  |
| No        | 23        | 34.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 12        | 18.18%  |
| Germany     | 9         | 13.64%  |
| Brazil      | 8         | 12.12%  |
| Poland      | 4         | 6.06%   |
| Italy       | 3         | 4.55%   |
| Greece      | 3         | 4.55%   |
| France      | 3         | 4.55%   |
| Australia   | 3         | 4.55%   |
| Netherlands | 2         | 3.03%   |
| India       | 2         | 3.03%   |
| Czechia     | 2         | 3.03%   |
| Belgium     | 2         | 3.03%   |
| Ukraine     | 1         | 1.52%   |
| UK          | 1         | 1.52%   |
| Portugal    | 1         | 1.52%   |
| Pakistan    | 1         | 1.52%   |
| Nigeria     | 1         | 1.52%   |
| Mexico      | 1         | 1.52%   |
| Jamaica     | 1         | 1.52%   |
| Honduras    | 1         | 1.52%   |
| Finland     | 1         | 1.52%   |
| Denmark     | 1         | 1.52%   |
| Croatia     | 1         | 1.52%   |
| Colombia    | 1         | 1.52%   |
| Canada      | 1         | 1.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Warsaw             | 2         | 2.94%   |
| Sao Paulo          | 2         | 2.94%   |
| Lutjegast          | 2         | 2.94%   |
| Hobart             | 2         | 2.94%   |
| Athens             | 2         | 2.94%   |
| Zagreb             | 1         | 1.47%   |
| Wroclaw            | 1         | 1.47%   |
| Winter Springs     | 1         | 1.47%   |
| Wilsdruff          | 1         | 1.47%   |
| Vivian             | 1         | 1.47%   |
| Vicksburg          | 1         | 1.47%   |
| Toluca             | 1         | 1.47%   |
| Thungersheim       | 1         | 1.47%   |
| Temple Hills       | 1         | 1.47%   |
| Tegucigalpa        | 1         | 1.47%   |
| Tampere            | 1         | 1.47%   |
| Skarzysko-Kamienna | 1         | 1.47%   |
| Senas              | 1         | 1.47%   |
| Seelze             | 1         | 1.47%   |
| Schenectady        | 1         | 1.47%   |
| Sankt Augustin     | 1         | 1.47%   |
| Rome               | 1         | 1.47%   |
| Rio de Janeiro     | 1         | 1.47%   |
| Rio das Ostras     | 1         | 1.47%   |
| Ringgold           | 1         | 1.47%   |
| Reims              | 1         | 1.47%   |
| Prague             | 1         | 1.47%   |
| Porto              | 1         | 1.47%   |
| Ouzouer-sur-Loire  | 1         | 1.47%   |
| Oswego             | 1         | 1.47%   |
| Oshawa             | 1         | 1.47%   |
| Odense             | 1         | 1.47%   |
| North Plains       | 1         | 1.47%   |
| Nevele             | 1         | 1.47%   |
| Naples             | 1         | 1.47%   |
| Marlow             | 1         | 1.47%   |
| Lagos              | 1         | 1.47%   |
| Kyiv               | 1         | 1.47%   |
| Kladno             | 1         | 1.47%   |
| Kingston           | 1         | 1.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 11        | 11     | 14.47%  |
| WDC                 | 10        | 10     | 13.16%  |
| Seagate             | 9         | 10     | 11.84%  |
| Unknown             | 5         | 9      | 6.58%   |
| SanDisk             | 5         | 5      | 6.58%   |
| Hitachi             | 5         | 5      | 6.58%   |
| Samsung Electronics | 4         | 7      | 5.26%   |
| JMicron Technology  | 3         | 3      | 3.95%   |
| Crucial             | 3         | 4      | 3.95%   |
| SK hynix            | 2         | 3      | 2.63%   |
| PNY                 | 2         | 2      | 2.63%   |
| Patriot             | 2         | 2      | 2.63%   |
| Kingston            | 2         | 2      | 2.63%   |
| HGST                | 2         | 2      | 2.63%   |
| SPCC                | 1         | 2      | 1.32%   |
| Micron_1            | 1         | 1      | 1.32%   |
| LITEON              | 1         | 1      | 1.32%   |
| Lenovo              | 1         | 1      | 1.32%   |
| I/OMAGIC            | 1         | 1      | 1.32%   |
| HEORIADY            | 1         | 1      | 1.32%   |
| Dogfish             | 1         | 1      | 1.32%   |
| AMD                 | 1         | 1      | 1.32%   |
| ALERTSEAL           | 1         | 1      | 1.32%   |
| A-DATA Technology   | 1         | 1      | 1.32%   |
| Unknown             | 1         | 1      | 1.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 3         | 3.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3.75%   |
| Toshiba MQ04ABF100 1TB             | 2         | 2.5%    |
| Toshiba MK2552GSX 250GB            | 2         | 2.5%    |
| Patriot Burst 120GB SSD            | 2         | 2.5%    |
| Kingston SA400S37240G 240GB SSD    | 2         | 2.5%    |
| JMicron Tech 250GB                 | 2         | 2.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1         | 1.25%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 1.25%   |
| WDC WDBNCE0010PNC 1TB SSD          | 1         | 1.25%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1.25%   |
| WDC WD5000BPVT-60HXZT1 500GB       | 1         | 1.25%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 1.25%   |
| WDC WD3200BEKT-00PVMT0 320GB       | 1         | 1.25%   |
| WDC WD2500BEVT-24A23T0 250GB       | 1         | 1.25%   |
| WDC WD1600BEVT-75ZCT1 160GB        | 1         | 1.25%   |
| WDC WD10JPCX-24UE4T0 1TB           | 1         | 1.25%   |
| Unknown SD  128GB                  | 1         | 1.25%   |
| Unknown MMC Card  7GB              | 1         | 1.25%   |
| Unknown MMC Card  32GB             | 1         | 1.25%   |
| Unknown BJTD4R  32GB               | 1         | 1.25%   |
| Toshiba MQ01ACF032 320GB           | 1         | 1.25%   |
| Toshiba MQ01ABF032 320GB           | 1         | 1.25%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1.25%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1.25%   |
| Toshiba MQ01ABD050 500GB           | 1         | 1.25%   |
| Toshiba MQ01ABD032 320GB           | 1         | 1.25%   |
| Toshiba MK1656GSYF 160GB           | 1         | 1.25%   |
| SPCC Solid State Disk 512GB        | 1         | 1.25%   |
| SK hynix NVMe SSD Drive 512GB      | 1         | 1.25%   |
| SK hynix NVMe SSD Drive 1024GB     | 1         | 1.25%   |
| SK hynix BC511 NVMe 512GB          | 1         | 1.25%   |
| Seagate ST9250410AS 250GB          | 1         | 1.25%   |
| Seagate ST9250315AS 250GB          | 1         | 1.25%   |
| Seagate ST500LM021-1KJ152 500GB    | 1         | 1.25%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1.25%   |
| Seagate ST2000LM007-1R8174 2TB     | 1         | 1.25%   |
| Seagate ST1000DM003-9YN162 1TB     | 1         | 1.25%   |
| SanDisk SSD PLUS 1000GB            | 1         | 1.25%   |
| SanDisk SDSSDX240GG25 240GB        | 1         | 1.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 11        | 11     | 31.43%  |
| Seagate             | 9         | 10     | 25.71%  |
| WDC                 | 7         | 7      | 20%     |
| Hitachi             | 5         | 5      | 14.29%  |
| HGST                | 2         | 2      | 5.71%   |
| Samsung Electronics | 1         | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 5         | 5      | 17.24%  |
| WDC                 | 3         | 3      | 10.34%  |
| Samsung Electronics | 3         | 4      | 10.34%  |
| Crucial             | 3         | 4      | 10.34%  |
| PNY                 | 2         | 2      | 6.9%    |
| Patriot             | 2         | 2      | 6.9%    |
| Kingston            | 2         | 2      | 6.9%    |
| SPCC                | 1         | 2      | 3.45%   |
| Micron_1            | 1         | 1      | 3.45%   |
| LITEON              | 1         | 1      | 3.45%   |
| JMicron Technology  | 1         | 1      | 3.45%   |
| HEORIADY            | 1         | 1      | 3.45%   |
| Dogfish             | 1         | 1      | 3.45%   |
| AMD                 | 1         | 1      | 3.45%   |
| ALERTSEAL           | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 35        | 36     | 46.05%  |
| SSD     | 28        | 32     | 36.84%  |
| MMC     | 6         | 10     | 7.89%   |
| NVMe    | 4         | 6      | 5.26%   |
| Unknown | 3         | 3      | 3.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 60        | 66     | 80%     |
| MMC  | 6         | 10     | 8%      |
| SAS  | 5         | 5      | 6.67%   |
| NVMe | 4         | 6      | 5.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 47     | 69.35%  |
| 0.51-1.0   | 18        | 20     | 29.03%  |
| 1.01-2.0   | 1         | 1      | 1.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 27.94%  |
| 251-500        | 18        | 26.47%  |
| 501-1000       | 14        | 20.59%  |
| 21-50          | 8         | 11.76%  |
| 51-100         | 6         | 8.82%   |
| More than 3000 | 1         | 1.47%   |
| 1001-2000      | 1         | 1.47%   |
| 1-20           | 1         | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 21-50   | 32        | 47.06%  |
| 1-20    | 19        | 27.94%  |
| 101-250 | 8         | 11.76%  |
| 51-100  | 8         | 11.76%  |
| 251-500 | 1         | 1.47%   |

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
| Detected | 65        | 85     | 97.01%  |
| Works    | 2         | 2      | 2.99%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 51        | 76.12%  |
| AMD                 | 9         | 13.43%  |
| SK hynix            | 2         | 2.99%   |
| Nvidia              | 2         | 2.99%   |
| VIA Technologies    | 1         | 1.49%   |
| Samsung Electronics | 1         | 1.49%   |
| Lenovo              | 1         | 1.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 9         | 12%     |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 7         | 9.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 9.33%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 7         | 9.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 5.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 5.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 4%      |
| Nvidia MCP79 AHCI Controller                                                           | 2         | 2.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 2.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 2.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 2.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 2.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 2.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 2         | 2.67%   |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 1.33%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                         | 1         | 1.33%   |
| SK hynix BC511                                                                         | 1         | 1.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.33%   |
| Lenovo Non-Volatile memory controller                                                  | 1         | 1.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 1         | 1.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.33%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.33%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 1.33%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.33%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                  | 1         | 1.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 1         | 1.33%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.33%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 1         | 1.33%   |
| AMD SB600 IDE                                                                          | 1         | 1.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 50        | 71.43%  |
| RAID | 8         | 11.43%  |
| IDE  | 8         | 11.43%  |
| NVMe | 4         | 5.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 57        | 86.36%  |
| AMD    | 9         | 13.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8700 @ 2.53GHz         | 3         | 4.55%   |
| Intel Core i7-3610QM CPU @ 2.30GHz           | 2         | 3.03%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 3.03%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 2         | 3.03%   |
| Intel Core i3 CPU M 350 @ 2.27GHz            | 2         | 3.03%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz         | 2         | 3.03%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 2         | 3.03%   |
| AMD A6-9220 RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 3.03%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz  | 1         | 1.52%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz  | 1         | 1.52%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz       | 1         | 1.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 1.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 1         | 1.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 1         | 1.52%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz           | 1         | 1.52%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 1.52%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 1.52%   |
| Intel Core i7-2820QM CPU @ 2.30GHz           | 1         | 1.52%   |
| Intel Core i7-2630QM CPU @ 2.00GHz           | 1         | 1.52%   |
| Intel Core i7-2620M CPU @ 2.70GHz            | 1         | 1.52%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 1         | 1.52%   |
| Intel Core i7 CPU M 620 @ 2.67GHz            | 1         | 1.52%   |
| Intel Core i5-8350U CPU @ 1.70GHz            | 1         | 1.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 1         | 1.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 1.52%   |
| Intel Core i5-4210M CPU @ 2.60GHz            | 1         | 1.52%   |
| Intel Core i5-3360M CPU @ 2.80GHz            | 1         | 1.52%   |
| Intel Core i5-2540M CPU @ 2.60GHz            | 1         | 1.52%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 1         | 1.52%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 1.52%   |
| Intel Core i5 CPU M 430 @ 2.27GHz            | 1         | 1.52%   |
| Intel Core i3-8130U CPU @ 2.20GHz            | 1         | 1.52%   |
| Intel Core i3-5005U CPU @ 2.00GHz            | 1         | 1.52%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 1         | 1.52%   |
| Intel Core i3-2350M CPU @ 2.30GHz            | 1         | 1.52%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 1         | 1.52%   |
| Intel Core i3 CPU M 330 @ 2.13GHz            | 1         | 1.52%   |
| Intel Core 2 Extreme CPU Q9300 @ 2.53GHz     | 1         | 1.52%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz         | 1         | 1.52%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz         | 1         | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 13        | 19.7%   |
| Intel Core i5           | 13        | 19.7%   |
| Intel Core 2 Duo        | 10        | 15.15%  |
| Intel Core i3           | 8         | 12.12%  |
| Intel Celeron           | 4         | 6.06%   |
| Intel Atom              | 3         | 4.55%   |
| AMD A6                  | 3         | 4.55%   |
| Intel Pentium Dual-Core | 2         | 3.03%   |
| AMD E                   | 2         | 3.03%   |
| Intel Pentium Dual      | 1         | 1.52%   |
| Intel Core 2 Extreme    | 1         | 1.52%   |
| Intel Core 2            | 1         | 1.52%   |
| Intel Celeron Dual-Core | 1         | 1.52%   |
| AMD Ryzen 7             | 1         | 1.52%   |
| AMD E2                  | 1         | 1.52%   |
| AMD Athlon 64 X2        | 1         | 1.52%   |
| AMD Athlon              | 1         | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 49        | 74.24%  |
| 4      | 13        | 19.7%   |
| 6      | 2         | 3.03%   |
| 8      | 1         | 1.52%   |
| 1      | 1         | 1.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 66        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 36        | 54.55%  |
| 1      | 30        | 45.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 66        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x1067a    | 12        | 18.18%  |
| 0x206a7    | 10        | 15.15%  |
| 0x306c3    | 5         | 7.58%   |
| 0x306a9    | 4         | 6.06%   |
| 0x20652    | 4         | 6.06%   |
| 0x306d4    | 3         | 4.55%   |
| 0x906ea    | 2         | 3.03%   |
| 0x806ea    | 2         | 3.03%   |
| 0x6fd      | 2         | 3.03%   |
| 0x406c4    | 2         | 3.03%   |
| 0x40651    | 2         | 3.03%   |
| 0x20655    | 2         | 3.03%   |
| 0x06006705 | 2         | 3.03%   |
| 0x05000119 | 2         | 3.03%   |
| 0x806e9    | 1         | 1.52%   |
| 0x706a8    | 1         | 1.52%   |
| 0x6f6      | 1         | 1.52%   |
| 0x506e3    | 1         | 1.52%   |
| 0x30678    | 1         | 1.52%   |
| 0x106e5    | 1         | 1.52%   |
| 0x10676    | 1         | 1.52%   |
| 0x0a50000c | 1         | 1.52%   |
| 0x08108109 | 1         | 1.52%   |
| 0x06006704 | 1         | 1.52%   |
| 0x06001119 | 1         | 1.52%   |
| Unknown    | 1         | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Penryn        | 13        | 19.7%   |
| SandyBridge   | 10        | 15.15%  |
| Haswell       | 7         | 10.61%  |
| Westmere      | 6         | 9.09%   |
| KabyLake      | 5         | 7.58%   |
| IvyBridge     | 4         | 6.06%   |
| Silvermont    | 3         | 4.55%   |
| Excavator     | 3         | 4.55%   |
| Core          | 3         | 4.55%   |
| Broadwell     | 3         | 4.55%   |
| Bobcat        | 2         | 3.03%   |
| Zen+          | 1         | 1.52%   |
| Zen 3         | 1         | 1.52%   |
| Skylake       | 1         | 1.52%   |
| Piledriver    | 1         | 1.52%   |
| Nehalem       | 1         | 1.52%   |
| K8 Hammer     | 1         | 1.52%   |
| Goldmont plus | 1         | 1.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 46        | 56.1%   |
| Nvidia | 22        | 26.83%  |
| AMD    | 14        | 17.07%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 11.76%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 8.24%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 5.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 5.88%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.53%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 3.53%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 2.35%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 2.35%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.35%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.35%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.18%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.18%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.18%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.18%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.18%   |
| Nvidia GK107M [GeForce GT 755M]                                                          | 1         | 1.18%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 1.18%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.18%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 1.18%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 1.18%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.18%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.18%   |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 1.18%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.18%   |
| Nvidia G96CM [GeForce GT 220M]                                                           | 1         | 1.18%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.18%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 1.18%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 1.18%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.18%   |
| Intel HD Graphics 620                                                                    | 1         | 1.18%   |
| Intel HD Graphics 530                                                                    | 1         | 1.18%   |
| Intel HD Graphics                                                                        | 1         | 1.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.18%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 30        | 45.45%  |
| Intel + Nvidia | 13        | 19.7%   |
| 1 x AMD        | 10        | 15.15%  |
| 1 x Nvidia     | 8         | 12.12%  |
| Intel + AMD    | 3         | 4.55%   |
| 2 x Nvidia     | 1         | 1.52%   |
| 2 x AMD        | 1         | 1.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 58        | 87.88%  |
| Unknown     | 5         | 7.58%   |
| Proprietary | 3         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 56.06%  |
| 0.01-0.5   | 12        | 18.18%  |
| 0.51-1.0   | 8         | 12.12%  |
| 1.01-2.0   | 6         | 9.09%   |
| 3.01-4.0   | 2         | 3.03%   |
| 5.01-6.0   | 1         | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 20        | 31.25%  |
| Samsung Electronics     | 15        | 23.44%  |
| AU Optronics            | 12        | 18.75%  |
| Chimei Innolux          | 7         | 10.94%  |
| LG Philips              | 2         | 3.13%   |
| BOE                     | 2         | 3.13%   |
| PANDA                   | 1         | 1.56%   |
| Lenovo                  | 1         | 1.56%   |
| Goldstar                | 1         | 1.56%   |
| Dell                    | 1         | 1.56%   |
| Chi Mei Optoelectronics | 1         | 1.56%   |
| Apple                   | 1         | 1.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch    | 2         | 3.13%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch    | 2         | 3.13%   |
| Samsung Electronics LCD Monitor SAM03D3 1360x768 410x256mm 19.0-inch    | 2         | 3.13%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 2         | 3.13%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch           | 2         | 3.13%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch    | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch    | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch    | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch    | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC3645 1280x800 331x207mm 15.4-inch    | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch    | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 1872x1053mm 84.6-inch | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch    | 1         | 1.56%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                 | 1         | 1.56%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch             | 1         | 1.56%   |
| LG Philips LCD Monitor LPL012B 1280x800 304x190mm 14.1-inch             | 1         | 1.56%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch           | 1         | 1.56%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch            | 1         | 1.56%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD03DD 1366x768 344x194mm 15.5-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD03B3 1366x768 310x174mm 14.0-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch            | 1         | 1.56%   |
| LG Display LCD Monitor LGD02A6 1366x768 345x194mm 15.6-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch            | 1         | 1.56%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD01CA 1600x900 382x215mm 17.3-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD01AF 1680x1050 331x207mm 15.4-inch            | 1         | 1.56%   |
| LG Display LCD Monitor LGD018E 1920x1200 367x230mm 17.1-inch            | 1         | 1.56%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                 | 1         | 1.56%   |
| Goldstar 32LG7000 GSM765E 1920x1080 700x390mm 31.5-inch                 | 1         | 1.56%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                        | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch         | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch         | 1         | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 31        | 49.21%  |
| 1920x1080 (FHD)    | 9         | 14.29%  |
| 1600x900 (HD+)     | 8         | 12.7%   |
| 1440x900 (WXGA+)   | 4         | 6.35%   |
| 1280x800 (WXGA)    | 4         | 6.35%   |
| 3840x2160 (4K)     | 3         | 4.76%   |
| 1360x768           | 2         | 3.17%   |
| 1920x1200 (WUXGA)  | 1         | 1.59%   |
| 1680x1050 (WSXGA+) | 1         | 1.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 33        | 51.56%  |
| 17     | 11        | 17.19%  |
| 14     | 8         | 12.5%   |
| 13     | 4         | 6.25%   |
| 31     | 2         | 3.13%   |
| 19     | 2         | 3.13%   |
| 11     | 2         | 3.13%   |
| 84     | 1         | 1.56%   |
| 18     | 1         | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 65.63%  |
| 351-400     | 12        | 18.75%  |
| 201-300     | 4         | 6.25%   |
| 401-500     | 3         | 4.69%   |
| 601-700     | 2         | 3.13%   |
| 1501-2000   | 1         | 1.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 48        | 77.42%  |
| 16/10 | 14        | 22.58%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 33        | 51.56%  |
| 81-90          | 10        | 15.63%  |
| 131-140        | 6         | 9.38%   |
| 121-130        | 5         | 7.81%   |
| 71-80          | 2         | 3.13%   |
| 51-60          | 2         | 3.13%   |
| 351-500        | 2         | 3.13%   |
| 151-200        | 2         | 3.13%   |
| More than 1000 | 1         | 1.56%   |
| 141-150        | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 34        | 53.13%  |
| 121-160 | 15        | 23.44%  |
| 51-100  | 14        | 21.88%  |
| 1-50    | 1         | 1.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 57        | 86.36%  |
| 2     | 5         | 7.58%   |
| 0     | 4         | 6.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 31        | 27.43%  |
| Intel                             | 28        | 24.78%  |
| Broadcom                          | 19        | 16.81%  |
| Qualcomm Atheros                  | 16        | 14.16%  |
| Broadcom Limited                  | 6         | 5.31%   |
| Samsung Electronics               | 2         | 1.77%   |
| Nvidia                            | 2         | 1.77%   |
| MediaTek                          | 2         | 1.77%   |
| Marvell Technology Group          | 2         | 1.77%   |
| Toshiba                           | 1         | 0.88%   |
| Ralink Technology                 | 1         | 0.88%   |
| Ralink                            | 1         | 0.88%   |
| Lenovo                            | 1         | 0.88%   |
| Ericsson Business Mobile Networks | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 14.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 6.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 3.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 3.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 3.05%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 4         | 3.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 2.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 2.29%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 2.29%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 2.29%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.53%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 1.53%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.53%   |
| Intel Wireless 3160                                               | 2         | 1.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 1.53%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.53%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.53%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 1.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.53%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 2         | 1.53%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.53%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 1.53%   |
| Toshiba F5521gw                                                   | 1         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.76%   |
| Realtek RTL8187B Wireless Adapter                                 | 1         | 0.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.76%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.76%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.76%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 37.5%   |
| Qualcomm Atheros      | 14        | 21.88%  |
| Broadcom              | 14        | 21.88%  |
| Realtek Semiconductor | 6         | 9.38%   |
| MediaTek              | 2         | 3.13%   |
| Broadcom Limited      | 2         | 3.13%   |
| Ralink Technology     | 1         | 1.56%   |
| Ralink                | 1         | 1.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 7.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 6.15%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 4         | 6.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 4.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 4.62%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 4.62%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 4.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 3.08%   |
| Intel Wireless 3160                                            | 2         | 3.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 3.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 3.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 3.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 3.08%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 3.08%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.54%   |
| Realtek RTL8187B Wireless Adapter                              | 1         | 1.54%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.54%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 1.54%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.54%   |
| MediaTek 802.11 n WLAN                                         | 1         | 1.54%   |
| Intel Wireless 8265 / 8275                                     | 1         | 1.54%   |
| Intel Wireless 7260                                            | 1         | 1.54%   |
| Intel Wireless 3165                                            | 1         | 1.54%   |
| Intel WiFi Link 5100                                           | 1         | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.54%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.54%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.54%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.54%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.54%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 1         | 1.54%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 1.54%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 1.54%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 1.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 46.03%  |
| Intel                    | 12        | 19.05%  |
| Broadcom                 | 8         | 12.7%   |
| Broadcom Limited         | 4         | 6.35%   |
| Qualcomm Atheros         | 3         | 4.76%   |
| Samsung Electronics      | 2         | 3.17%   |
| Nvidia                   | 2         | 3.17%   |
| Marvell Technology Group | 2         | 3.17%   |
| Lenovo                   | 1         | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 29.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 6.25%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 3.13%   |
| Nvidia MCP79 Ethernet                                             | 2         | 3.13%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.13%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 3.13%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 3.13%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 3.13%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 2         | 3.13%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.56%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 1.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.56%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.56%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 1.56%   |
| Lenovo Thinkpad LAN                                               | 1         | 1.56%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.56%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.56%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.56%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.56%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.56%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.56%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 49.6%   |
| Ethernet | 61        | 48.8%   |
| Modem    | 2         | 1.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 44        | 66.67%  |
| Ethernet | 22        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 56        | 84.85%  |
| 1     | 5         | 7.58%   |
| 0     | 4         | 6.06%   |
| 3     | 1         | 1.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 42        | 63.64%  |
| Yes  | 24        | 36.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 25.58%  |
| Broadcom                        | 6         | 13.95%  |
| Dell                            | 4         | 9.3%    |
| Cambridge Silicon Radio         | 4         | 9.3%    |
| Realtek Semiconductor           | 3         | 6.98%   |
| Qualcomm Atheros Communications | 3         | 6.98%   |
| Foxconn / Hon Hai               | 3         | 6.98%   |
| Lite-On Technology              | 2         | 4.65%   |
| Hewlett-Packard                 | 2         | 4.65%   |
| Apple                           | 2         | 4.65%   |
| Toshiba                         | 1         | 2.33%   |
| IMC Networks                    | 1         | 2.33%   |
| Askey Computer                  | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 11.63%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 9.3%    |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 4.65%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4.65%   |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 4.65%   |
| Dell DW375 Bluetooth Module                         | 2         | 4.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 4.65%   |
| Toshiba Askey Bluetooth Module                      | 1         | 2.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.33%   |
| Lite-On Atheros Bluetooth                           | 1         | 2.33%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.33%   |
| Intel AX210 Bluetooth                               | 1         | 2.33%   |
| IMC Networks Bluetooth Device                       | 1         | 2.33%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 2.33%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 2.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.33%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 2.33%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.33%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.33%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 2.33%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.33%   |
| Askey Bluetooth Device                              | 1         | 2.33%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.33%   |
| Apple Bluetooth Host Controller                     | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 62.65%  |
| Nvidia                | 15        | 18.07%  |
| AMD                   | 13        | 15.66%  |
| Roland                | 1         | 1.2%    |
| Realtek Semiconductor | 1         | 1.2%    |
| GN Netcom             | 1         | 1.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 11        | 11%     |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 9         | 9%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 7         | 7%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 5         | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5         | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5         | 5%      |
| Nvidia GF108 High Definition Audio Controller                                     | 4         | 4%      |
| Nvidia GK107 HDMI Audio Controller                                                | 3         | 3%      |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 3%      |
| Intel Sunrise Point-LP HD Audio                                                   | 3         | 3%      |
| Intel Broadwell-U Audio Controller                                                | 3         | 3%      |
| AMD High Definition Audio Controller                                              | 3         | 3%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 3         | 3%      |
| Nvidia MCP79 High Definition Audio                                                | 2         | 2%      |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 2%      |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 2%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 2%      |
| Intel 8 Series HD Audio Controller                                                | 2         | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 2%      |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2         | 2%      |
| AMD FCH Azalia Controller                                                         | 2         | 2%      |
| AMD Family 17h/19h HD Audio Controller                                            | 2         | 2%      |
| Roland QUAD-CAPTURE                                                               | 1         | 1%      |
| Realtek Semiconductor Realtek USB audio                                           | 1         | 1%      |
| Nvidia TU106 High Definition Audio Controller                                     | 1         | 1%      |
| Nvidia GT216 HDMI Audio Controller                                                | 1         | 1%      |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 1%      |
| Nvidia GF119 HDMI Audio Controller                                                | 1         | 1%      |
| Nvidia GF106 High Definition Audio Controller                                     | 1         | 1%      |
| Nvidia GA106 High Definition Audio Controller                                     | 1         | 1%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1         | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1         | 1%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1         | 1%      |
| GN Netcom enc060:Buttons Volume up/down/mute + phone [Jabra]                      | 1         | 1%      |
| AMD Wrestler HDMI Audio                                                           | 1         | 1%      |
| AMD Trinity HDMI Audio Controller                                                 | 1         | 1%      |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                   | 1         | 1%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 1%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 1         | 1%      |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1%      |

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
| SK hynix            | 1         | 16.67%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 533MT/s           | 1         | 14.29%  |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s           | 1         | 14.29%  |
| SK hynix RAM Module 4096MB SODIMM DDR3 1066MT/s         | 1         | 14.29%  |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 1         | 14.29%  |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 14.29%  |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s | 1         | 14.29%  |
| Kingston RAM 9905428-020.A00LF 4GB SODIMM DDR3 1067MT/s | 1         | 14.29%  |

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
| Chicony Electronics                    | 12        | 22.22%  |
| Microdia                               | 5         | 9.26%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 9.26%   |
| Silicon Motion                         | 4         | 7.41%   |
| Acer                                   | 4         | 7.41%   |
| Suyin                                  | 3         | 5.56%   |
| Quanta                                 | 3         | 5.56%   |
| Sunplus Innovation Technology          | 2         | 3.7%    |
| Ricoh                                  | 2         | 3.7%    |
| Realtek Semiconductor                  | 2         | 3.7%    |
| Primax Electronics                     | 2         | 3.7%    |
| Apple                                  | 2         | 3.7%    |
| Alcor Micro                            | 2         | 3.7%    |
| Z-Star Microelectronics                | 1         | 1.85%   |
| USB Camera                             | 1         | 1.85%   |
| Syntek                                 | 1         | 1.85%   |
| Samsung Electronics                    | 1         | 1.85%   |
| IMC Networks                           | 1         | 1.85%   |
| ALi                                    | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                                     | 3         | 5.56%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                              | 2         | 3.7%    |
| Sunplus HD WebCam                                                     | 2         | 3.7%    |
| Realtek USB Camera                                                    | 2         | 3.7%    |
| Quanta HP Webcam                                                      | 2         | 3.7%    |
| Chicony CNF9055 Toshiba Webcam                                        | 2         | 3.7%    |
| Apple Built-in iSight                                                 | 2         | 3.7%    |
| Acer Lenovo EasyCamera                                                | 2         | 3.7%    |
| Z-Star WebCam SC-03FFL11739P                                          | 1         | 1.85%   |
| USB Camera USB Camera                                                 | 1         | 1.85%   |
| Syntek Lenovo EasyCamera                                              | 1         | 1.85%   |
| Suyin UVC HD Webcam                                                   | 1         | 1.85%   |
| Silicon Motion WebCam SCB-1100N                                       | 1         | 1.85%   |
| Silicon Motion WebCam SCB-0385N                                       | 1         | 1.85%   |
| Silicon Motion WebCam SC-0311139N                                     | 1         | 1.85%   |
| Silicon Motion 300k Pixel Camera                                      | 1         | 1.85%   |
| Samsung Galaxy A5 (MTP)                                               | 1         | 1.85%   |
| Ricoh Laptop_Integrated_Webcam_3M                                     | 1         | 1.85%   |
| Ricoh Integrated Webcam                                               | 1         | 1.85%   |
| Quanta Laptop_Integrated_Webcam_2HDM                                  | 1         | 1.85%   |
| Primax HP Webcam-101                                                  | 1         | 1.85%   |
| Primax HP HD Webcam [Fixed]                                           | 1         | 1.85%   |
| Microdia Lenovo EasyCamera                                            | 1         | 1.85%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 1.85%   |
| Microdia Integrated_Webcam_HD                                         | 1         | 1.85%   |
| Microdia Integrated Webcam                                            | 1         | 1.85%   |
| Microdia Dell Integrated HD Webcam                                    | 1         | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 1         | 1.85%   |
| Chicony USB 2.0 Camera                                                | 1         | 1.85%   |
| Chicony integrated camera                                             | 1         | 1.85%   |
| Chicony HP Webcam                                                     | 1         | 1.85%   |
| Chicony HP TrueVision HD Camera                                       | 1         | 1.85%   |
| Chicony HP HD Webcam                                                  | 1         | 1.85%   |
| Chicony FJ Camera                                                     | 1         | 1.85%   |
| Chicony 2.0M UVC Webcam / CNF7129                                     | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                         | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                      | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera        | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD               | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                   | 1         | 1.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 4         | 66.67%  |
| AuthenTec        | 2         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS451 Fingerprint Reader | 2         | 33.33%  |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 16.67%  |
| Validity Sensors VFS491                    | 1         | 16.67%  |
| AuthenTec Fingerprint Sensor               | 1         | 16.67%  |
| AuthenTec AES2550 Fingerprint Sensor       | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 4         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 4         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 45        | 68.18%  |
| 1     | 16        | 24.24%  |
| 2     | 5         | 7.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 8         | 33.33%  |
| Fingerprint reader    | 6         | 25%     |
| Chipcard              | 4         | 16.67%  |
| Storage               | 3         | 12.5%   |
| Multimedia controller | 2         | 8.33%   |
| Net/wireless          | 1         | 4.17%   |

