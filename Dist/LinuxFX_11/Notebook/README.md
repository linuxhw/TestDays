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

Total: 98

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.11.0-37-generic | 8         | 13.11%  |
| 5.13.0-27-generic | 7         | 11.48%  |
| 5.11.0-38-generic | 7         | 11.48%  |
| 5.11.0-43-generic | 6         | 9.84%   |
| 5.11.0-40-generic | 6         | 9.84%   |
| 5.13.0-28-generic | 5         | 8.2%    |
| 5.11.0-36-generic | 5         | 8.2%    |
| 5.11.0-41-generic | 4         | 6.56%   |
| 5.13.0-30-generic | 3         | 4.92%   |
| 5.11.0-46-generic | 3         | 4.92%   |
| 5.13.0-39-generic | 2         | 3.28%   |
| 5.13.0-35-generic | 1         | 1.64%   |
| 5.13.0-25-generic | 1         | 1.64%   |
| 5.11.0-44-generic | 1         | 1.64%   |
| 5.11.0-42-generic | 1         | 1.64%   |
| 5.11.0-34-generic | 1         | 1.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 39        | 67.24%  |
| 5.13.0  | 19        | 32.76%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 39        | 67.24%  |
| 5.13    | 19        | 32.76%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 57        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 55        | 96.49%  |
| X-Cinnamon | 1         | 1.75%   |
| KDE        | 1         | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 56        | 98.25%  |
| Wayland | 1         | 1.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 49        | 85.96%  |
| SDDM    | 8         | 14.04%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 12        | 21.05%  |
| de_DE | 8         | 14.04%  |
| pt_BR | 7         | 12.28%  |
| it_IT | 3         | 5.26%   |
| fr_FR | 3         | 5.26%   |
| en_AU | 3         | 5.26%   |
| pl_PL | 2         | 3.51%   |
| nl_NL | 2         | 3.51%   |
| en_IN | 2         | 3.51%   |
| el_GR | 2         | 3.51%   |
| cs_CZ | 2         | 3.51%   |
| ru_UA | 1         | 1.75%   |
| pt_PT | 1         | 1.75%   |
| nl_BE | 1         | 1.75%   |
| hr_BA | 1         | 1.75%   |
| fi_FI | 1         | 1.75%   |
| es_MX | 1         | 1.75%   |
| es_HN | 1         | 1.75%   |
| es_CO | 1         | 1.75%   |
| en_NG | 1         | 1.75%   |
| en_GB | 1         | 1.75%   |
| da_DK | 1         | 1.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 39        | 68.42%  |
| EFI  | 18        | 31.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 57        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 55        | 96.49%  |
| MBR     | 1         | 1.75%   |
| GPT     | 1         | 1.75%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 98.25%  |
| Yes       | 1         | 1.75%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 96.49%  |
| Yes       | 2         | 3.51%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 16        | 28.07%  |
| Dell                | 8         | 14.04%  |
| Acer                | 8         | 14.04%  |
| Lenovo              | 6         | 10.53%  |
| Samsung Electronics | 4         | 7.02%   |
| Toshiba             | 3         | 5.26%   |
| ASUSTek Computer    | 3         | 5.26%   |
| Positivo            | 2         | 3.51%   |
| Apple               | 2         | 3.51%   |
| GPU Company         | 1         | 1.75%   |
| Google              | 1         | 1.75%   |
| Fujitsu Siemens     | 1         | 1.75%   |
| Fujitsu             | 1         | 1.75%   |
| Alienware           | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| HP 255 G6 Notebook PC                                                                    | 2         | 3.51%   |
| Toshiba TECRA R850                                                                       | 1         | 1.75%   |
| Toshiba Satellite P300                                                                   | 1         | 1.75%   |
| Toshiba Satellite C660                                                                   | 1         | 1.75%   |
| Samsung RV415/RV515/E3415                                                                | 1         | 1.75%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411                                              | 1         | 1.75%   |
| Samsung RF511/RF411/RF711                                                                | 1         | 1.75%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1.75%   |
| Positivo Smash3                                                                          | 1         | 1.75%   |
| Positivo Smash                                                                           | 1         | 1.75%   |
| Lenovo ThinkPad L380 20M6S4E000                                                          | 1         | 1.75%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                                                         | 1         | 1.75%   |
| Lenovo IdeaPad Y510P 20217                                                               | 1         | 1.75%   |
| Lenovo G550 2958                                                                         | 1         | 1.75%   |
| Lenovo G50-80 80R0                                                                       | 1         | 1.75%   |
| Lenovo G50-80 80E5                                                                       | 1         | 1.75%   |
| HP ProBook 640 G1                                                                        | 1         | 1.75%   |
| HP ProBook 4720s                                                                         | 1         | 1.75%   |
| HP ProBook 440 G1                                                                        | 1         | 1.75%   |
| HP Pavilion g6                                                                           | 1         | 1.75%   |
| HP Pavilion dv6700                                                                       | 1         | 1.75%   |
| HP Pavilion 14                                                                           | 1         | 1.75%   |
| HP Laptop 15-da0xxx                                                                      | 1         | 1.75%   |
| HP Laptop 15-bw0xx                                                                       | 1         | 1.75%   |
| HP Laptop 14-dk1xxx                                                                      | 1         | 1.75%   |
| HP G62                                                                                   | 1         | 1.75%   |
| HP EliteBook 8570w                                                                       | 1         | 1.75%   |
| HP EliteBook 8440p                                                                       | 1         | 1.75%   |
| HP Compaq CQ45                                                                           | 1         | 1.75%   |
| HP Compaq 6730b (NA373UC#ABA)                                                            | 1         | 1.75%   |
| GPU Company GWTN116-3                                                                    | 1         | 1.75%   |
| Google Peppy                                                                             | 1         | 1.75%   |
| Fujitsu Siemens AMILO Xi 1526                                                            | 1         | 1.75%   |
| Fujitsu CELSIUS H700                                                                     | 1         | 1.75%   |
| Dell System XPS L502X                                                                    | 1         | 1.75%   |
| Dell Precision M6400                                                                     | 1         | 1.75%   |
| Dell Latitude E6540                                                                      | 1         | 1.75%   |
| Dell Latitude E6420                                                                      | 1         | 1.75%   |
| Dell Latitude E6400                                                                      | 1         | 1.75%   |
| Dell Latitude E5400                                                                      | 1         | 1.75%   |
| Dell Inspiron N5050                                                                      | 1         | 1.75%   |
| Dell G5 5590                                                                             | 1         | 1.75%   |
| ASUS X751LAB                                                                             | 1         | 1.75%   |
| ASUS N71Vg                                                                               | 1         | 1.75%   |
| ASUS K95VM                                                                               | 1         | 1.75%   |
| Apple MacBookPro5,5                                                                      | 1         | 1.75%   |
| Apple MacBookPro5,2                                                                      | 1         | 1.75%   |
| Alienware M17xR3                                                                         | 1         | 1.75%   |
| Acer TravelMate 5744                                                                     | 1         | 1.75%   |
| Acer One S1002                                                                           | 1         | 1.75%   |
| Acer Extensa 5220                                                                        | 1         | 1.75%   |
| Acer Aspire XXXX                                                                         | 1         | 1.75%   |
| Acer Aspire E1-570                                                                       | 1         | 1.75%   |
| Acer Aspire 5741                                                                         | 1         | 1.75%   |
| Acer Aspire 5738                                                                         | 1         | 1.75%   |
| Acer Aspire 5735                                                                         | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 5         | 8.77%   |
| Dell Latitude         | 4         | 7.02%   |
| HP ProBook            | 3         | 5.26%   |
| HP Pavilion           | 3         | 5.26%   |
| HP Laptop             | 3         | 5.26%   |
| Toshiba Satellite     | 2         | 3.51%   |
| Lenovo G50-80         | 2         | 3.51%   |
| HP EliteBook          | 2         | 3.51%   |
| HP Compaq             | 2         | 3.51%   |
| HP 255                | 2         | 3.51%   |
| Apple MacBookPro5     | 2         | 3.51%   |
| Toshiba TECRA         | 1         | 1.75%   |
| Samsung RV415         | 1         | 1.75%   |
| Samsung RV411         | 1         | 1.75%   |
| Samsung RF511         | 1         | 1.75%   |
| Samsung 355V4C        | 1         | 1.75%   |
| Positivo Smash3       | 1         | 1.75%   |
| Positivo Smash        | 1         | 1.75%   |
| Lenovo ThinkPad       | 1         | 1.75%   |
| Lenovo Legion         | 1         | 1.75%   |
| Lenovo IdeaPad        | 1         | 1.75%   |
| Lenovo G550           | 1         | 1.75%   |
| HP G62                | 1         | 1.75%   |
| GPU Company GWTN116-3 | 1         | 1.75%   |
| Google Peppy          | 1         | 1.75%   |
| Fujitsu Siemens AMILO | 1         | 1.75%   |
| Fujitsu CELSIUS       | 1         | 1.75%   |
| Dell System           | 1         | 1.75%   |
| Dell Precision        | 1         | 1.75%   |
| Dell Inspiron         | 1         | 1.75%   |
| Dell G5               | 1         | 1.75%   |
| ASUS X751LAB          | 1         | 1.75%   |
| ASUS N71Vg            | 1         | 1.75%   |
| ASUS K95VM            | 1         | 1.75%   |
| Alienware M17xR3      | 1         | 1.75%   |
| Acer TravelMate       | 1         | 1.75%   |
| Acer One              | 1         | 1.75%   |
| Acer Extensa          | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 12        | 21.05%  |
| 2013 | 6         | 10.53%  |
| 2009 | 6         | 10.53%  |
| 2010 | 5         | 8.77%   |
| 2019 | 4         | 7.02%   |
| 2008 | 4         | 7.02%   |
| 2021 | 3         | 5.26%   |
| 2017 | 3         | 5.26%   |
| 2015 | 3         | 5.26%   |
| 2012 | 3         | 5.26%   |
| 2007 | 3         | 5.26%   |
| 2018 | 2         | 3.51%   |
| 2014 | 2         | 3.51%   |
| 2016 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 57        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 54        | 94.74%  |
| Enabled  | 3         | 5.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 56        | 98.25%  |
| Yes  | 1         | 1.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 19        | 33.33%  |
| 4.01-8.0   | 15        | 26.32%  |
| 8.01-16.0  | 12        | 21.05%  |
| 16.01-24.0 | 4         | 7.02%   |
| 1.01-2.0   | 3         | 5.26%   |
| 2.01-3.0   | 2         | 3.51%   |
| 32.01-64.0 | 1         | 1.75%   |
| 24.01-32.0 | 1         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 33        | 55.93%  |
| 2.01-3.0 | 16        | 27.12%  |
| 3.01-4.0 | 5         | 8.47%   |
| 0.51-1.0 | 5         | 8.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 75.86%  |
| 2      | 12        | 20.69%  |
| 3      | 2         | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 75.44%  |
| No        | 14        | 24.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 92.98%  |
| No        | 4         | 7.02%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 92.98%  |
| No        | 4         | 7.02%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 66.67%  |
| No        | 19        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 9         | 15.79%  |
| Germany     | 8         | 14.04%  |
| Brazil      | 7         | 12.28%  |
| Italy       | 3         | 5.26%   |
| France      | 3         | 5.26%   |
| Australia   | 3         | 5.26%   |
| Poland      | 2         | 3.51%   |
| Netherlands | 2         | 3.51%   |
| India       | 2         | 3.51%   |
| Greece      | 2         | 3.51%   |
| Czechia     | 2         | 3.51%   |
| Ukraine     | 1         | 1.75%   |
| UK          | 1         | 1.75%   |
| Portugal    | 1         | 1.75%   |
| Pakistan    | 1         | 1.75%   |
| Nigeria     | 1         | 1.75%   |
| Mexico      | 1         | 1.75%   |
| Jamaica     | 1         | 1.75%   |
| Honduras    | 1         | 1.75%   |
| Finland     | 1         | 1.75%   |
| Denmark     | 1         | 1.75%   |
| Croatia     | 1         | 1.75%   |
| Colombia    | 1         | 1.75%   |
| Canada      | 1         | 1.75%   |
| Belgium     | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Warsaw           | 2         | 3.39%   |
| Lutjegast        | 2         | 3.39%   |
| Hobart           | 2         | 3.39%   |
| Zaventem         | 1         | 1.69%   |
| Zagreb           | 1         | 1.69%   |
| Wabern           | 1         | 1.69%   |
| Vivian           | 1         | 1.69%   |
| Vicksburg        | 1         | 1.69%   |
| Toluca           | 1         | 1.69%   |
| Temple Hills     | 1         | 1.69%   |
| Tegucigalpa      | 1         | 1.69%   |
| Spicheren        | 1         | 1.69%   |
| Shamrock         | 1         | 1.69%   |
| Senas            | 1         | 1.69%   |
| Sao Paulo        | 1         | 1.69%   |
| Sankt Augustin   | 1         | 1.69%   |
| Rome             | 1         | 1.69%   |
| Rio de Janeiro   | 1         | 1.69%   |
| Rio das Ostras   | 1         | 1.69%   |
| Ringgold         | 1         | 1.69%   |
| Reims            | 1         | 1.69%   |
| Prague           | 1         | 1.69%   |
| Porto            | 1         | 1.69%   |
| Oswego           | 1         | 1.69%   |
| Oshawa           | 1         | 1.69%   |
| Odense           | 1         | 1.69%   |
| Northwich        | 1         | 1.69%   |
| North Plains     | 1         | 1.69%   |
| Naples           | 1         | 1.69%   |
| Mandi            | 1         | 1.69%   |
| Lohja            | 1         | 1.69%   |
| Lagos            | 1         | 1.69%   |
| Kladno           | 1         | 1.69%   |
| Kingston         | 1         | 1.69%   |
| Karachi          | 1         | 1.69%   |
| JoÃ£o Pessoa   | 1         | 1.69%   |
| Itaperuna        | 1         | 1.69%   |
| Ibipitanga       | 1         | 1.69%   |
| Hoyerswerda      | 1         | 1.69%   |
| HÃ¶xter        | 1         | 1.69%   |
| Grossenhain      | 1         | 1.69%   |
| GÃ¼tersloh     | 1         | 1.69%   |
| Garbsen          | 1         | 1.69%   |
| East Stroudsburg | 1         | 1.69%   |
| Corinth          | 1         | 1.69%   |
| ChapecÃ³       | 1         | 1.69%   |
| Chandigarh       | 1         | 1.69%   |
| Catanduva        | 1         | 1.69%   |
| Brussels         | 1         | 1.69%   |
| Brisbane         | 1         | 1.69%   |
| Bologna          | 1         | 1.69%   |
| BogotÃ¡        | 1         | 1.69%   |
| Bila Tserkva     | 1         | 1.69%   |
| Berlin           | 1         | 1.69%   |
| Athens           | 1         | 1.69%   |
| Allen Park       | 1         | 1.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 11        | 11     | 16.67%  |
| WDC                 | 9         | 9      | 13.64%  |
| Seagate             | 8         | 10     | 12.12%  |
| Unknown             | 5         | 9      | 7.58%   |
| SanDisk             | 4         | 4      | 6.06%   |
| Hitachi             | 3         | 3      | 4.55%   |
| Crucial             | 3         | 4      | 4.55%   |
| SK Hynix            | 2         | 3      | 3.03%   |
| PNY                 | 2         | 2      | 3.03%   |
| Patriot             | 2         | 2      | 3.03%   |
| Kingston            | 2         | 2      | 3.03%   |
| JMicron             | 2         | 2      | 3.03%   |
| HGST                | 2         | 2      | 3.03%   |
| Samsung Electronics | 1         | 1      | 1.52%   |
| Micron_1            | 1         | 2      | 1.52%   |
| LITEON              | 1         | 1      | 1.52%   |
| Lenovo              | 1         | 1      | 1.52%   |
| I/OMAGIC            | 1         | 1      | 1.52%   |
| HEORIADY            | 1         | 1      | 1.52%   |
| DOGFISH             | 1         | 1      | 1.52%   |
| AMD                 | 1         | 1      | 1.52%   |
| ALERTSEAL           | 1         | 1      | 1.52%   |
| A-DATA Technology   | 1         | 1      | 1.52%   |
| Unknown             | 1         | 1      | 1.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  64GB              | 3         | 4.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 4.35%   |
| Toshiba MQ04ABF100 1TB              | 2         | 2.9%    |
| Toshiba MK2552GSX 250GB             | 2         | 2.9%    |
| Patriot Burst 120GB SSD             | 2         | 2.9%    |
| Kingston SA400S37240G 240GB SSD     | 2         | 2.9%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1         | 1.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 1.45%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1.45%   |
| WDC WD5000BPVT-60HXZT1 500GB        | 1         | 1.45%   |
| WDC WD5000BPVT-22HXZT3 500GB        | 1         | 1.45%   |
| WDC WD3200BEKT-00PVMT0 320GB        | 1         | 1.45%   |
| WDC WD2500BEVT-24A23T0 250GB        | 1         | 1.45%   |
| WDC WD1600BEVT-75ZCT1 160GB         | 1         | 1.45%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1.45%   |
| Unknown SD  128GB                   | 1         | 1.45%   |
| Unknown MMC Card  7GB               | 1         | 1.45%   |
| Unknown MMC Card  32GB              | 1         | 1.45%   |
| Unknown BJTD4R  32GB                | 1         | 1.45%   |
| Toshiba MQ01ACF032 320GB            | 1         | 1.45%   |
| Toshiba MQ01ABF032 320GB            | 1         | 1.45%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1.45%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1.45%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1.45%   |
| Toshiba MQ01ABD032 320GB            | 1         | 1.45%   |
| Toshiba MK1656GSYF 160GB            | 1         | 1.45%   |
| SK Hynix NVMe SSD Drive 512GB       | 1         | 1.45%   |
| SK Hynix NVMe SSD Drive 1024GB      | 1         | 1.45%   |
| SK Hynix BC511 NVMe 512GB           | 1         | 1.45%   |
| Seagate ST9250410AS 250GB           | 1         | 1.45%   |
| Seagate ST9250315AS 250GB           | 1         | 1.45%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1.45%   |
| Seagate ST320LT007-9ZV142 320GB     | 1         | 1.45%   |
| Seagate ST1000DM003-9YN162 1TB      | 1         | 1.45%   |
| SanDisk SSD PLUS 1000GB             | 1         | 1.45%   |
| SanDisk SDSSDX240GG25 240GB         | 1         | 1.45%   |
| SanDisk SDSSDH3 500G                | 1         | 1.45%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1.45%   |
| Samsung SSD 850 EVO 1TB             | 1         | 1.45%   |
| PNY CS900 480GB SSD                 | 1         | 1.45%   |
| PNY CS900 120GB SSD                 | 1         | 1.45%   |
| Micron_1 100_MTFDDAV256TB 256GB SSD | 1         | 1.45%   |
| LITEON CV1-8B256 256GB SSD          | 1         | 1.45%   |
| Lenovo NVMe SSD Drive 256GB         | 1         | 1.45%   |
| JMicron Tech 250GB                  | 1         | 1.45%   |
| JMicron Generic 2TB                 | 1         | 1.45%   |
| I/OMAGIC BLACK DIAMOND 256GB        | 1         | 1.45%   |
| Hitachi HTS725032A9A364 320GB       | 1         | 1.45%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1.45%   |
| Hitachi HTS545025B9A300 250GB       | 1         | 1.45%   |
| HGST HTS545050A7E680 500GB          | 1         | 1.45%   |
| HGST HTS545032A7E680 320GB          | 1         | 1.45%   |
| HEORIADY SSD HX-001 E 128G          | 1         | 1.45%   |
| DOGFISH SSD 512GB                   | 1         | 1.45%   |
| Crucial CT250MX500SSD1 250GB        | 1         | 1.45%   |
| Crucial CT120BX500SSD1 120GB        | 1         | 1.45%   |
| Crucial CT1000MX500SSD1 1TB         | 1         | 1.45%   |
| AMD R3SL240G 240GB SSD              | 1         | 1.45%   |
| ALERTSEAL SSD 48GB                  | 1         | 1.45%   |
| A-DATA SU750 512GB SSD              | 1         | 1.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 11        | 11     | 35.48%  |
| Seagate | 8         | 10     | 25.81%  |
| WDC     | 7         | 7      | 22.58%  |
| Hitachi | 3         | 3      | 9.68%   |
| HGST    | 2         | 2      | 6.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 4         | 4      | 16.67%  |
| Crucial             | 3         | 4      | 12.5%   |
| WDC                 | 2         | 2      | 8.33%   |
| PNY                 | 2         | 2      | 8.33%   |
| Patriot             | 2         | 2      | 8.33%   |
| Kingston            | 2         | 2      | 8.33%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| Micron_1            | 1         | 2      | 4.17%   |
| LITEON              | 1         | 1      | 4.17%   |
| JMicron             | 1         | 1      | 4.17%   |
| HEORIADY            | 1         | 1      | 4.17%   |
| DOGFISH             | 1         | 1      | 4.17%   |
| AMD                 | 1         | 1      | 4.17%   |
| ALERTSEAL           | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 31        | 33     | 47.69%  |
| SSD     | 23        | 26     | 35.38%  |
| MMC     | 6         | 10     | 9.23%   |
| NVMe    | 3         | 4      | 4.62%   |
| Unknown | 2         | 2      | 3.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 51        | 56     | 79.69%  |
| MMC  | 6         | 10     | 9.38%   |
| SAS  | 4         | 5      | 6.25%   |
| NVMe | 3         | 4      | 4.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 41     | 69.81%  |
| 0.51-1.0   | 15        | 17     | 28.3%   |
| 1.01-2.0   | 1         | 1      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 18        | 31.03%  |
| 251-500        | 13        | 22.41%  |
| 501-1000       | 11        | 18.97%  |
| 21-50          | 8         | 13.79%  |
| 51-100         | 6         | 10.34%  |
| More than 3000 | 1         | 1.72%   |
| 1001-2000      | 1         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 21-50   | 29        | 50%     |
| 1-20    | 18        | 31.03%  |
| 51-100  | 6         | 10.34%  |
| 101-250 | 5         | 8.62%   |

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
| Detected | 56        | 73     | 96.55%  |
| Works    | 2         | 2      | 3.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 43        | 75.44%  |
| AMD              | 8         | 14.04%  |
| SK Hynix         | 2         | 3.51%   |
| Nvidia           | 2         | 3.51%   |
| VIA Technologies | 1         | 1.75%   |
| Lenovo           | 1         | 1.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 8         | 12.5%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 7         | 10.94%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 5         | 7.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 7.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 6.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 4.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 4.69%   |
| Nvidia MCP79 AHCI Controller                                                           | 2         | 3.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 3.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 3.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 3.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 2         | 3.13%   |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 1.56%   |
| SK Hynix Gold P31 SSD                                                                  | 1         | 1.56%   |
| SK Hynix BC511                                                                         | 1         | 1.56%   |
| Lenovo Non-Volatile memory controller                                                  | 1         | 1.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.56%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 1.56%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 1         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                  | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 43        | 72.88%  |
| IDE  | 7         | 11.86%  |
| RAID | 6         | 10.17%  |
| NVMe | 3         | 5.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 49        | 85.96%  |
| AMD    | 8         | 14.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 3         | 5.26%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 3.51%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 3.51%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 3.51%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 2         | 3.51%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 3.51%   |
| AMD A6-9220 RADEON R4, 5 COMPUTE CORES 2C+3G  | 2         | 3.51%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 1.75%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 1.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.75%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.75%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 1.75%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.75%   |
| Intel Core i7-2820QM CPU @ 2.30GHz            | 1         | 1.75%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 1.75%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.75%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.75%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.75%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 1.75%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 1.75%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.75%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.75%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 1.75%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 1.75%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.75%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.75%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 1.75%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 1.75%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 1         | 1.75%   |
| Intel Core 2 Extreme CPU Q9300 @ 2.53GHz      | 1         | 1.75%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz          | 1         | 1.75%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 1         | 1.75%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz          | 1         | 1.75%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 1         | 1.75%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 1.75%   |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 1         | 1.75%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 1.75%   |
| Intel Celeron Dual-Core CPU T3500 @ 2.10GHz   | 1         | 1.75%   |
| Intel Celeron CPU 3215U @ 1.70GHz             | 1         | 1.75%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 1.75%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 1         | 1.75%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 1.75%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 1         | 1.75%   |
| AMD E-450 APU with Radeon HD Graphics         | 1         | 1.75%   |
| AMD E-300 APU with Radeon HD Graphics         | 1         | 1.75%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 1         | 1.75%   |
| AMD A6-4400M APU with Radeon HD Graphics      | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 19.3%   |
| Intel Core 2 Duo        | 10        | 17.54%  |
| Intel Core i7           | 9         | 15.79%  |
| Intel Core i3           | 8         | 14.04%  |
| Intel Celeron           | 3         | 5.26%   |
| Intel Atom              | 3         | 5.26%   |
| AMD A6                  | 3         | 5.26%   |
| AMD E                   | 2         | 3.51%   |
| Intel Pentium Dual-Core | 1         | 1.75%   |
| Intel Pentium Dual      | 1         | 1.75%   |
| Intel Core 2 Extreme    | 1         | 1.75%   |
| Intel Core 2            | 1         | 1.75%   |
| Intel Celeron Dual-Core | 1         | 1.75%   |
| AMD Ryzen 7             | 1         | 1.75%   |
| AMD E2                  | 1         | 1.75%   |
| AMD Athlon              | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 77.19%  |
| 4      | 10        | 17.54%  |
| 8      | 1         | 1.75%   |
| 6      | 1         | 1.75%   |
| 1      | 1         | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 30        | 52.63%  |
| 1      | 27        | 47.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x1067a    | 11        | 19.3%   |
| 0x206a7    | 7         | 12.28%  |
| 0x306c3    | 4         | 7.02%   |
| 0x20652    | 4         | 7.02%   |
| 0x306d4    | 3         | 5.26%   |
| 0x306a9    | 3         | 5.26%   |
| 0x806ea    | 2         | 3.51%   |
| 0x6fd      | 2         | 3.51%   |
| 0x406c4    | 2         | 3.51%   |
| 0x40651    | 2         | 3.51%   |
| 0x20655    | 2         | 3.51%   |
| 0x06006705 | 2         | 3.51%   |
| 0x05000119 | 2         | 3.51%   |
| 0x906ea    | 1         | 1.75%   |
| 0x706a8    | 1         | 1.75%   |
| 0x6f6      | 1         | 1.75%   |
| 0x506e3    | 1         | 1.75%   |
| 0x30678    | 1         | 1.75%   |
| 0x106e5    | 1         | 1.75%   |
| 0x10676    | 1         | 1.75%   |
| 0x0a50000c | 1         | 1.75%   |
| 0x08108109 | 1         | 1.75%   |
| 0x06006704 | 1         | 1.75%   |
| 0x06001119 | 1         | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Penryn        | 12        | 21.05%  |
| SandyBridge   | 7         | 12.28%  |
| Westmere      | 6         | 10.53%  |
| Haswell       | 6         | 10.53%  |
| Silvermont    | 3         | 5.26%   |
| KabyLake      | 3         | 5.26%   |
| IvyBridge     | 3         | 5.26%   |
| Excavator     | 3         | 5.26%   |
| Core          | 3         | 5.26%   |
| Broadwell     | 3         | 5.26%   |
| Bobcat        | 2         | 3.51%   |
| Zen+          | 1         | 1.75%   |
| Zen 3         | 1         | 1.75%   |
| Skylake       | 1         | 1.75%   |
| Piledriver    | 1         | 1.75%   |
| Nehalem       | 1         | 1.75%   |
| Goldmont plus | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 57.35%  |
| Nvidia | 18        | 26.47%  |
| AMD    | 11        | 16.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 9.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 9.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 7.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 5.63%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 4.23%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 2.82%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.82%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 2.82%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.41%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.41%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.41%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.41%   |
| Nvidia GK107M [GeForce GT 755M]                                                          | 1         | 1.41%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.41%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 1.41%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.41%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.41%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.41%   |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 1.41%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.41%   |
| Nvidia G96CM [GeForce GT 220M]                                                           | 1         | 1.41%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.41%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 1.41%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 1.41%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.41%   |
| Intel HD Graphics 530                                                                    | 1         | 1.41%   |
| Intel HD Graphics                                                                        | 1         | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.41%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.41%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 1.41%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.41%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.41%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.41%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                             | 1         | 1.41%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 1.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.41%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 49.12%  |
| Intel + Nvidia | 9         | 15.79%  |
| 1 x Nvidia     | 8         | 14.04%  |
| 1 x AMD        | 8         | 14.04%  |
| Intel + AMD    | 2         | 3.51%   |
| 2 x Nvidia     | 1         | 1.75%   |
| 2 x AMD        | 1         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 51        | 89.47%  |
| Unknown     | 4         | 7.02%   |
| Proprietary | 2         | 3.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 59.65%  |
| 0.01-0.5   | 11        | 19.3%   |
| 0.51-1.0   | 7         | 12.28%  |
| 1.01-2.0   | 3         | 5.26%   |
| 5.01-6.0   | 1         | 1.75%   |
| 3.01-4.0   | 1         | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 15        | 27.78%  |
| Samsung Electronics     | 13        | 24.07%  |
| AU Optronics            | 10        | 18.52%  |
| Chimei Innolux          | 6         | 11.11%  |
| LG Philips              | 2         | 3.7%    |
| BOE                     | 2         | 3.7%    |
| PANDA                   | 1         | 1.85%   |
| Lenovo                  | 1         | 1.85%   |
| Goldstar                | 1         | 1.85%   |
| Dell                    | 1         | 1.85%   |
| Chi Mei Optoelectronics | 1         | 1.85%   |
| Apple                   | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch      | 2         | 3.7%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch      | 2         | 3.7%    |
| Samsung Electronics LCD Monitor SAM03D3 1360x768 410x256mm 19.0-inch      | 2         | 3.7%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch             | 2         | 3.7%    |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch      | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 256x144mm 11.6-inch      | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch      | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch      | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch      | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch      | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch      | 1         | 1.85%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                   | 1         | 1.85%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch               | 1         | 1.85%   |
| LG Philips LCD Monitor LPL012B 1280x800 304x190mm 14.1-inch               | 1         | 1.85%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch             | 1         | 1.85%   |
| LG Display LCD Monitor LGD7001 1366x768 344x194mm 15.5-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD03DD 1366x768 344x194mm 15.5-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD03B3 1366x768 310x174mm 14.0-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD02A6 1366x768 345x194mm 15.6-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD01AF 1680x1050 331x207mm 15.4-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD018E 1920x1200 367x230mm 17.1-inch              | 1         | 1.85%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                   | 1         | 1.85%   |
| Goldstar 32LG7000 GSM765E 1920x1080 700x390mm 31.5-inch                   | 1         | 1.85%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                          | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN14E3 1366x768 309x173mm 13.9-inch           | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch           | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1808 1920x1080 408x230mm 18.4-inch | 1         | 1.85%   |
| BOE LCD Monitor BOE097F 1366x768 256x144mm 11.6-inch                      | 1         | 1.85%   |
| BOE LCD Monitor BOE0827 1366x768 309x174mm 14.0-inch                      | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO162C 1366x768 293x164mm 13.2-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO1101 1440x900 367x230mm 17.1-inch             | 1         | 1.85%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch                    | 1         | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 28        | 52.83%  |
| 1920x1080 (FHD)    | 6         | 11.32%  |
| 1600x900 (HD+)     | 6         | 11.32%  |
| 1440x900 (WXGA+)   | 4         | 7.55%   |
| 1280x800 (WXGA)    | 3         | 5.66%   |
| 3840x2160 (4K)     | 2         | 3.77%   |
| 1360x768           | 2         | 3.77%   |
| 1920x1200 (WUXGA)  | 1         | 1.89%   |
| 1680x1050 (WSXGA+) | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 27        | 50%     |
| 17     | 9         | 16.67%  |
| 14     | 7         | 12.96%  |
| 13     | 4         | 7.41%   |
| 31     | 2         | 3.7%    |
| 19     | 2         | 3.7%    |
| 11     | 2         | 3.7%    |
| 18     | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 35        | 64.81%  |
| 351-400     | 10        | 18.52%  |
| 201-300     | 4         | 7.41%   |
| 401-500     | 3         | 5.56%   |
| 601-700     | 2         | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 40        | 75.47%  |
| 16/10 | 13        | 24.53%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 50%     |
| 81-90          | 9         | 16.67%  |
| 131-140        | 6         | 11.11%  |
| 121-130        | 3         | 5.56%   |
| 71-80          | 2         | 3.7%    |
| 51-60          | 2         | 3.7%    |
| 351-500        | 2         | 3.7%    |
| 151-200        | 2         | 3.7%    |
| 141-150        | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 31        | 57.41%  |
| 121-160 | 11        | 20.37%  |
| 51-100  | 11        | 20.37%  |
| 1-50    | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 49        | 85.96%  |
| 2     | 4         | 7.02%   |
| 0     | 4         | 7.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 29.59%  |
| Intel                    | 23        | 23.47%  |
| Broadcom                 | 15        | 15.31%  |
| Qualcomm Atheros         | 13        | 13.27%  |
| Broadcom Limited         | 6         | 6.12%   |
| Samsung Electronics      | 2         | 2.04%   |
| Nvidia                   | 2         | 2.04%   |
| MEDIATEK                 | 2         | 2.04%   |
| Marvell Technology Group | 2         | 2.04%   |
| Toshiba                  | 1         | 1.02%   |
| Ralink Technology        | 1         | 1.02%   |
| Ralink                   | 1         | 1.02%   |
| Lenovo                   | 1         | 1.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 16.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 6.25%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 4         | 3.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 2.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 2.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 2.68%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 2.68%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.79%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.79%   |
| Intel Wireless 3160                                               | 2         | 1.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.79%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.79%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.79%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 2         | 1.79%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 1.79%   |
| Toshiba F5521gw                                                   | 1         | 0.89%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.89%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.89%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.89%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.89%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.89%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.89%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.89%   |
| MediaTek 802.11 n WLAN                                            | 1         | 0.89%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.89%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.89%   |
| Lenovo Thinkpad USB LAN                                           | 1         | 0.89%   |
| Intel Wireless 8265 / 8275                                        | 1         | 0.89%   |
| Intel Wireless 7260                                               | 1         | 0.89%   |
| Intel WiFi Link 5100                                              | 1         | 0.89%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 0.89%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.89%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.89%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 0.89%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 0.89%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.89%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.89%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.89%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.89%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.89%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.89%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.89%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 0.89%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.89%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 1         | 0.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 36.36%  |
| Broadcom              | 13        | 23.64%  |
| Qualcomm Atheros      | 11        | 20%     |
| Realtek Semiconductor | 5         | 9.09%   |
| MediaTek              | 2         | 3.64%   |
| Broadcom Limited      | 2         | 3.64%   |
| Ralink Technology     | 1         | 1.82%   |
| Ralink                | 1         | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 4         | 7.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 7.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 5.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 5.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 5.45%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 5.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.64%   |
| Intel Wireless 3160                                            | 2         | 3.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 3.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 3.64%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 3.64%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 3.64%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.82%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.82%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 1.82%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.82%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.82%   |
| MediaTek 802.11 n WLAN                                         | 1         | 1.82%   |
| Intel Wireless 8265 / 8275                                     | 1         | 1.82%   |
| Intel Wireless 7260                                            | 1         | 1.82%   |
| Intel WiFi Link 5100                                           | 1         | 1.82%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.82%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.82%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.82%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.82%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 1         | 1.82%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 1.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 1.82%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 1.82%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 49.09%  |
| Intel                    | 9         | 16.36%  |
| Broadcom                 | 5         | 9.09%   |
| Broadcom Limited         | 4         | 7.27%   |
| Qualcomm Atheros         | 3         | 5.45%   |
| Samsung Electronics      | 2         | 3.64%   |
| Nvidia                   | 2         | 3.64%   |
| Marvell Technology Group | 2         | 3.64%   |
| Lenovo                   | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 32.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 12.5%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 3.57%   |
| Nvidia MCP79 Ethernet                                             | 2         | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.57%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 3.57%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 2         | 3.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.79%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 1.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.79%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.79%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 1.79%   |
| Lenovo Thinkpad USB LAN                                           | 1         | 1.79%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.79%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.79%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.79%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.79%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.79%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.79%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.79%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.79%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.79%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 49.53%  |
| Ethernet | 53        | 49.53%  |
| Modem    | 1         | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 50        | 51.55%  |
| WiFi     | 47        | 48.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 50        | 87.72%  |
| 0     | 4         | 7.02%   |
| 1     | 3         | 5.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 61.4%   |
| Yes  | 22        | 38.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 23.68%  |
| Dell                            | 4         | 10.53%  |
| Broadcom                        | 4         | 10.53%  |
| Realtek Semiconductor           | 3         | 7.89%   |
| Qualcomm Atheros Communications | 3         | 7.89%   |
| Foxconn / Hon Hai               | 3         | 7.89%   |
| Cambridge Silicon Radio         | 3         | 7.89%   |
| Lite-On Technology              | 2         | 5.26%   |
| Hewlett-Packard                 | 2         | 5.26%   |
| Apple                           | 2         | 5.26%   |
| Toshiba                         | 1         | 2.63%   |
| IMC Networks                    | 1         | 2.63%   |
| Askey Computer                  | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 10.53%  |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 7.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 7.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 5.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 5.26%   |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 5.26%   |
| Dell DW375 Bluetooth Module                         | 2         | 5.26%   |
| Toshiba Askey Bluetooth Module                      | 1         | 2.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.63%   |
| Lite-On Atheros Bluetooth                           | 1         | 2.63%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.63%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.63%   |
| IMC Networks Bluetooth Device                       | 1         | 2.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 2.63%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 2.63%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.63%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 2.63%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.63%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.63%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 2.63%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.63%   |
| Askey Bluetooth Device                              | 1         | 2.63%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.63%   |
| Apple Bluetooth Host Controller                     | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 44        | 63.77%  |
| Nvidia                | 12        | 17.39%  |
| AMD                   | 11        | 15.94%  |
| Realtek Semiconductor | 1         | 1.45%   |
| GN Netcom             | 1         | 1.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 10        | 11.76%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7         | 8.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 7         | 8.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4         | 4.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 4         | 4.71%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3         | 3.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 3.53%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 3.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3         | 3.53%   |
| AMD High Definition Audio Controller                                              | 3         | 3.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 3         | 3.53%   |
| Nvidia MCP79 High Definition Audio                                                | 2         | 2.35%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2         | 2.35%   |
| Intel Sunrise Point-LP HD Audio                                                   | 2         | 2.35%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 2.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 2.35%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 2.35%   |
| AMD FCH Azalia Controller                                                         | 2         | 2.35%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2         | 2.35%   |
| Realtek Semiconductor Realtek USB audio                                           | 1         | 1.18%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1         | 1.18%   |
| Nvidia GT216 HDMI Audio Controller                                                | 1         | 1.18%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1         | 1.18%   |
| Nvidia GF106 High Definition Audio Controller                                     | 1         | 1.18%   |
| Nvidia Audio device                                                               | 1         | 1.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1         | 1.18%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1         | 1.18%   |
| Intel Cannon Lake PCH cAVS                                                        | 1         | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1         | 1.18%   |
| GN Netcom Jabra EVOLVE 30 II                                                      | 1         | 1.18%   |
| AMD Wrestler HDMI Audio                                                           | 1         | 1.18%   |
| AMD Trinity HDMI Audio Controller                                                 | 1         | 1.18%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 1.18%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 1         | 1.18%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                   | 1         | 1.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 1.18%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 1         | 1.18%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.18%   |

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
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s   | 1         | 14.29%  |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 14.29%  |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s    | 1         | 14.29%  |
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
| Chicony Electronics                    | 10        | 21.28%  |
| Cheng Uei Precision Industry (Foxlink) | 5         | 10.64%  |
| Silicon Motion                         | 4         | 8.51%   |
| Acer                                   | 4         | 8.51%   |
| Quanta                                 | 3         | 6.38%   |
| Microdia                               | 3         | 6.38%   |
| Suyin                                  | 2         | 4.26%   |
| Sunplus Innovation Technology          | 2         | 4.26%   |
| Ricoh                                  | 2         | 4.26%   |
| Realtek Semiconductor                  | 2         | 4.26%   |
| Primax Electronics                     | 2         | 4.26%   |
| Apple                                  | 2         | 4.26%   |
| Z-Star Microelectronics                | 1         | 2.13%   |
| USB Camera                             | 1         | 2.13%   |
| Syntek                                 | 1         | 2.13%   |
| Samsung Electronics                    | 1         | 2.13%   |
| ALi                                    | 1         | 2.13%   |
| Alcor Micro                            | 1         | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus HD WebCam                                              | 2         | 4.26%   |
| Realtek USB Camera                                             | 2         | 4.26%   |
| Quanta HP Webcam                                               | 2         | 4.26%   |
| Chicony HD WebCam                                              | 2         | 4.26%   |
| Chicony CNF9055 Toshiba Webcam                                 | 2         | 4.26%   |
| Apple Built-in iSight                                          | 2         | 4.26%   |
| Acer Lenovo EasyCamera                                         | 2         | 4.26%   |
| Z-Star WebCam SC-03FFL11739P                                   | 1         | 2.13%   |
| USB Camera USB Camera                                          | 1         | 2.13%   |
| Syntek Lenovo EasyCamera                                       | 1         | 2.13%   |
| Suyin UVC HD Webcam                                            | 1         | 2.13%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 2.13%   |
| Silicon Motion WebCam SCB-1100N                                | 1         | 2.13%   |
| Silicon Motion WebCam SCB-0385N                                | 1         | 2.13%   |
| Silicon Motion WebCam SC-0311139N                              | 1         | 2.13%   |
| Silicon Motion 300k Pixel Camera                               | 1         | 2.13%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 2.13%   |
| Ricoh Laptop_Integrated_Webcam_3M                              | 1         | 2.13%   |
| Ricoh Integrated Webcam                                        | 1         | 2.13%   |
| Quanta Laptop_Integrated_Webcam_2HDM                           | 1         | 2.13%   |
| Primax HP Webcam-101                                           | 1         | 2.13%   |
| Primax HP HD Webcam [Fixed]                                    | 1         | 2.13%   |
| Microdia Lenovo EasyCamera                                     | 1         | 2.13%   |
| Microdia Laptop_Integrated_Webcam_0.3M                         | 1         | 2.13%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 2.13%   |
| Chicony USB 2.0 Camera                                         | 1         | 2.13%   |
| Chicony HP Webcam                                              | 1         | 2.13%   |
| Chicony HP TrueVision HD Camera                                | 1         | 2.13%   |
| Chicony HP HD Webcam                                           | 1         | 2.13%   |
| Chicony FJ Camera                                              | 1         | 2.13%   |
| Chicony 2.0M UVC Webcam / CNF7129                              | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 1         | 2.13%   |
| ALi Gateway Webcam                                             | 1         | 2.13%   |
| Alcor Micro USB 2.0 PC cam                                     | 1         | 2.13%   |
| Acer SunplusIT Integrated Camera                               | 1         | 2.13%   |
| Acer Crystal Eye webcam                                        | 1         | 2.13%   |

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
| 0     | 38        | 66.67%  |
| 1     | 14        | 24.56%  |
| 2     | 5         | 8.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 7         | 31.82%  |
| Fingerprint reader    | 6         | 27.27%  |
| Storage               | 3         | 13.64%  |
| Chipcard              | 3         | 13.64%  |
| Multimedia controller | 2         | 9.09%   |
| Net/wireless          | 1         | 4.55%   |

