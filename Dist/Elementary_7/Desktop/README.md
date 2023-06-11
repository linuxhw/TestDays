Elementary 7 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Elementary 7.

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

Total: 58

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | ROG STRIX B350-F GAMING     | [08114e8a97](https://linux-hardware.org/?probe=08114e8a97) | Jun 10, 2023 |
| ASUSTek   | PRIME B450-PLUS             | [93555cfd25](https://linux-hardware.org/?probe=93555cfd25) | Jun 10, 2023 |
| ASUSTek   | PRIME B450-PLUS             | [2e6d82c14f](https://linux-hardware.org/?probe=2e6d82c14f) | Jun 10, 2023 |
| MSI       | MPG Z390 GAMING PRO CARB... | [ddefeff960](https://linux-hardware.org/?probe=ddefeff960) | Jun 08, 2023 |
| MSI       | MPG Z390 GAMING PRO CARB... | [77fe6db865](https://linux-hardware.org/?probe=77fe6db865) | Jun 06, 2023 |
| Gigabyte  | GA-E6010N                   | [563074319d](https://linux-hardware.org/?probe=563074319d) | May 31, 2023 |
| Lenovo    | 36C5 SDK0Q55724 WIN 3273... | [01076d8e8b](https://linux-hardware.org/?probe=01076d8e8b) | May 30, 2023 |
| ASUSTek   | ROG STRIX B350-F GAMING     | [16b9dfbbe0](https://linux-hardware.org/?probe=16b9dfbbe0) | May 29, 2023 |
| ASUSTek   | PRIME B450-PLUS             | [e29fb14e81](https://linux-hardware.org/?probe=e29fb14e81) | May 26, 2023 |
| ASUSTek   | PRIME B450-PLUS             | [84d0d9807f](https://linux-hardware.org/?probe=84d0d9807f) | May 26, 2023 |
| ASUSTek   | P8H61-MX R2.0               | [3776285fc1](https://linux-hardware.org/?probe=3776285fc1) | May 16, 2023 |
| HP        | 1998                        | [b806151d9f](https://linux-hardware.org/?probe=b806151d9f) | May 12, 2023 |
| Intel     | JSL MRD                     | [76ff5c3bd7](https://linux-hardware.org/?probe=76ff5c3bd7) | May 05, 2023 |
| Dell      | 02N3WF A02                  | [3f10b3ca43](https://linux-hardware.org/?probe=3f10b3ca43) | May 04, 2023 |
| HP        | 1998                        | [6f816ac95a](https://linux-hardware.org/?probe=6f816ac95a) | Apr 29, 2023 |
| HP        | 8055                        | [a897208085](https://linux-hardware.org/?probe=a897208085) | Apr 26, 2023 |
| ASRock    | B660M-C                     | [849fc5d462](https://linux-hardware.org/?probe=849fc5d462) | Apr 25, 2023 |
| Gigabyte  | H410M H V3                  | [8fd18554d1](https://linux-hardware.org/?probe=8fd18554d1) | Apr 24, 2023 |
| MACHINIST | E5-MR9A PRO V1.1            | [eebce73217](https://linux-hardware.org/?probe=eebce73217) | Apr 23, 2023 |
| ASUSTek   | PRIME Z390-A                | [50a18b5e94](https://linux-hardware.org/?probe=50a18b5e94) | Apr 19, 2023 |
| Foxconn   | A76GMV                      | [bafa62c759](https://linux-hardware.org/?probe=bafa62c759) | Apr 18, 2023 |
| Foxconn   | A76GMV                      | [f129cb2de1](https://linux-hardware.org/?probe=f129cb2de1) | Apr 18, 2023 |
| ASUSTek   | PRIME Z390-A                | [e311d21def](https://linux-hardware.org/?probe=e311d21def) | Apr 13, 2023 |
| Lenovo    | 36F7 SDK0J40700 WIN 3258... | [8e05a5e529](https://linux-hardware.org/?probe=8e05a5e529) | Apr 13, 2023 |
| Gigabyte  | Z270-Gaming K3              | [0c03014734](https://linux-hardware.org/?probe=0c03014734) | Apr 12, 2023 |
| MSI       | B450M PRO-M2 MAX            | [5a83c18a3e](https://linux-hardware.org/?probe=5a83c18a3e) | Apr 01, 2023 |
| MSI       | B450M PRO-M2 MAX            | [94f75ee798](https://linux-hardware.org/?probe=94f75ee798) | Apr 01, 2023 |
| Unknown   | Unknown                     | [fb22157f03](https://linux-hardware.org/?probe=fb22157f03) | Mar 28, 2023 |
| AZW       | U59                         | [7674bb8dc9](https://linux-hardware.org/?probe=7674bb8dc9) | Mar 27, 2023 |
| ASUSTek   | M4A785TD-V EVO              | [1674c37cf9](https://linux-hardware.org/?probe=1674c37cf9) | Mar 16, 2023 |
| HP        | 805A                        | [5401e12606](https://linux-hardware.org/?probe=5401e12606) | Mar 14, 2023 |
| HP        | 3033h                       | [ab5e388ea9](https://linux-hardware.org/?probe=ab5e388ea9) | Mar 14, 2023 |
| HP        | 3033h                       | [38ac77726b](https://linux-hardware.org/?probe=38ac77726b) | Mar 13, 2023 |
| MSI       | B450 TOMAHAWK MAX           | [39d0e8595c](https://linux-hardware.org/?probe=39d0e8595c) | Mar 12, 2023 |
| MSI       | B365M PRO-VH                | [023f42d6d1](https://linux-hardware.org/?probe=023f42d6d1) | Mar 12, 2023 |
| Inventec  | Z CLASS A02                 | [c45e770987](https://linux-hardware.org/?probe=c45e770987) | Mar 06, 2023 |
| ASUSTek   | BT6130                      | [dabd3e0232](https://linux-hardware.org/?probe=dabd3e0232) | Mar 01, 2023 |
| Unknown   | Unknown                     | [1c5f8fef49](https://linux-hardware.org/?probe=1c5f8fef49) | Feb 28, 2023 |
| ASUSTek   | ROG STRIX Z690-A GAMING ... | [216ad20179](https://linux-hardware.org/?probe=216ad20179) | Feb 28, 2023 |
| Acer      | Predator G3620              | [72f3382b60](https://linux-hardware.org/?probe=72f3382b60) | Feb 27, 2023 |
| Gigabyte  | Z77X-UD5H                   | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte  | Z77X-UD5H                   | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell      | 07PR60 A01                  | [c071b7ef1c](https://linux-hardware.org/?probe=c071b7ef1c) | Feb 27, 2023 |
| ASUSTek   | TUF X470-PLUS GAMING        | [ce9dda227f](https://linux-hardware.org/?probe=ce9dda227f) | Feb 25, 2023 |
| Gigabyte  | B550 AORUS ELITE            | [13a132516b](https://linux-hardware.org/?probe=13a132516b) | Feb 18, 2023 |
| ASUSTek   | TUF X470-PLUS GAMING        | [76ab936a75](https://linux-hardware.org/?probe=76ab936a75) | Feb 16, 2023 |
| ASUSTek   | H110M-A/M.2                 | [68f0415788](https://linux-hardware.org/?probe=68f0415788) | Feb 16, 2023 |
| ASUSTek   | H110M-A/M.2                 | [2560ba7644](https://linux-hardware.org/?probe=2560ba7644) | Feb 16, 2023 |
| Foxconn   | 2ADA                        | [e0f89bbca1](https://linux-hardware.org/?probe=e0f89bbca1) | Feb 16, 2023 |
| HP        | 805D                        | [217784712c](https://linux-hardware.org/?probe=217784712c) | Feb 14, 2023 |
| MSI       | B85-G43 GAMING              | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| ASUSTek   | TUF X470-PLUS GAMING        | [f0899499e5](https://linux-hardware.org/?probe=f0899499e5) | Feb 13, 2023 |
| ASUSTek   | H110M-A/M.2                 | [76711a4e32](https://linux-hardware.org/?probe=76711a4e32) | Feb 10, 2023 |
| ASUSTek   | H110M-A/M.2                 | [73b3c1c661](https://linux-hardware.org/?probe=73b3c1c661) | Feb 06, 2023 |
| Gigabyte  | F2A88XM-DS2                 | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| ASUSTek   | P7P55 LX                    | [3786e7a211](https://linux-hardware.org/?probe=3786e7a211) | Feb 04, 2023 |
| ASUSTek   | Z170 PRO GAMING             | [c2a4529e33](https://linux-hardware.org/?probe=c2a4529e33) | Jan 30, 2023 |
| Unknown   | HX90                        | [af144f98b6](https://linux-hardware.org/?probe=af144f98b6) | Jan 05, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.19.0-32-generic | 9        | 20.93%  |
| 5.15.0-58-generic | 8        | 18.6%   |
| 5.19.0-35-generic | 6        | 13.95%  |
| 5.19.0-38-generic | 5        | 11.63%  |
| 5.15.0-60-generic | 4        | 9.3%    |
| 5.19.0-43-generic | 3        | 6.98%   |
| 5.19.0-41-generic | 3        | 6.98%   |
| 5.19.0-42-generic | 2        | 4.65%   |
| 5.19.0-40-generic | 2        | 4.65%   |
| 5.15.0-56-generic | 1        | 2.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.19.0  | 28       | 68.29%  |
| 5.15.0  | 13       | 31.71%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.19    | 28       | 68.29%  |
| 5.15    | 13       | 31.71%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 41       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 41       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 41       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 34       | 82.93%  |
| LightDM | 7        | 17.07%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 16       | 38.1%   |
| de_DE | 6        | 14.29%  |
| es_ES | 4        | 9.52%   |
| ru_RU | 2        | 4.76%   |
| pt_BR | 2        | 4.76%   |
| it_IT | 2        | 4.76%   |
| sv_SE | 1        | 2.38%   |
| pt_PT | 1        | 2.38%   |
| pl_PL | 1        | 2.38%   |
| nl_NL | 1        | 2.38%   |
| ja_JP | 1        | 2.38%   |
| fr_FR | 1        | 2.38%   |
| fi_FI | 1        | 2.38%   |
| en_CA | 1        | 2.38%   |
| en_AU | 1        | 2.38%   |
| cs_CZ | 1        | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 38       | 92.68%  |
| EFI  | 3        | 7.32%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 37       | 90.24%  |
| Btrfs | 2        | 4.88%   |
| Xfs   | 1        | 2.44%   |
| Tmpfs | 1        | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 34       | 82.93%  |
| GPT     | 5        | 12.2%   |
| MBR     | 2        | 4.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 97.56%  |
| Yes       | 1        | 2.44%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 95.12%  |
| Yes       | 2        | 4.88%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 12       | 29.27%  |
| Gigabyte Technology | 6        | 14.63%  |
| MSI                 | 5        | 12.2%   |
| Hewlett-Packard     | 5        | 12.2%   |
| Foxconn             | 2        | 4.88%   |
| Dell                | 2        | 4.88%   |
| Unknown             | 2        | 4.88%   |
| MACHINIST           | 1        | 2.44%   |
| Lenovo              | 1        | 2.44%   |
| Inventec            | 1        | 2.44%   |
| Intel               | 1        | 2.44%   |
| AZW                 | 1        | 2.44%   |
| ASRock              | 1        | 2.44%   |
| Acer                | 1        | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS H110M-A/M.2                        | 2        | 4.88%   |
| Unknown                                 | 2        | 4.88%   |
| MSI MS-7C31                             | 1        | 2.44%   |
| MSI MS-7C02                             | 1        | 2.44%   |
| MSI MS-7B84                             | 1        | 2.44%   |
| MSI MS-7B17                             | 1        | 2.44%   |
| MSI MS-7816                             | 1        | 2.44%   |
| MACHINIST E5-MR9A PRO V1.1              | 1        | 2.44%   |
| Lenovo IdeaCentre 510S-08IKL 90GB00E3IN | 1        | 2.44%   |
| Inventec Z CLASS                        | 1        | 2.44%   |
| Intel Jasper Lake Client Platform       | 1        | 2.44%   |
| HP ProDesk 600 G2 SFF                   | 1        | 2.44%   |
| HP EliteDesk 800 G2 DM 35W              | 1        | 2.44%   |
| HP EliteDesk 705 G2 MT                  | 1        | 2.44%   |
| HP Compaq dc7900 Ultra-Slim Desktop     | 1        | 2.44%   |
| HP 1998                                 | 1        | 2.44%   |
| Gigabyte Z77X-UD5H                      | 1        | 2.44%   |
| Gigabyte Z270-Gaming K3                 | 1        | 2.44%   |
| Gigabyte H410M H V3                     | 1        | 2.44%   |
| Gigabyte GA-E6010N                      | 1        | 2.44%   |
| Gigabyte F2A88XM-DS2                    | 1        | 2.44%   |
| Gigabyte B550 AORUS ELITE               | 1        | 2.44%   |
| Foxconn A76GMV                          | 1        | 2.44%   |
| Foxconn 400-034                         | 1        | 2.44%   |
| Dell OptiPlex 3070                      | 1        | 2.44%   |
| Dell Inspiron 5675                      | 1        | 2.44%   |
| AZW U59                                 | 1        | 2.44%   |
| ASUS Z170 PRO GAMING                    | 1        | 2.44%   |
| ASUS TUF X470-PLUS GAMING               | 1        | 2.44%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4    | 1        | 2.44%   |
| ASUS ROG STRIX B350-F GAMING            | 1        | 2.44%   |
| ASUS PRIME Z390-A                       | 1        | 2.44%   |
| ASUS PRIME B450-PLUS                    | 1        | 2.44%   |
| ASUS P8H61-MX R2.0                      | 1        | 2.44%   |
| ASUS P7P55 LX                           | 1        | 2.44%   |
| ASUS M4A785TD-V EVO                     | 1        | 2.44%   |
| ASUS BT6130-8                           | 1        | 2.44%   |
| ASRock B660M-C                          | 1        | 2.44%   |
| Acer Predator G3620                     | 1        | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP EliteDesk         | 2        | 4.88%   |
| ASUS ROG             | 2        | 4.88%   |
| ASUS PRIME           | 2        | 4.88%   |
| ASUS H110M-A         | 2        | 4.88%   |
| Unknown              | 2        | 4.88%   |
| MSI MS-7C31          | 1        | 2.44%   |
| MSI MS-7C02          | 1        | 2.44%   |
| MSI MS-7B84          | 1        | 2.44%   |
| MSI MS-7B17          | 1        | 2.44%   |
| MSI MS-7816          | 1        | 2.44%   |
| MACHINIST E5-MR9A    | 1        | 2.44%   |
| Lenovo IdeaCentre    | 1        | 2.44%   |
| Inventec Z           | 1        | 2.44%   |
| Intel Jasper         | 1        | 2.44%   |
| HP ProDesk           | 1        | 2.44%   |
| HP Compaq            | 1        | 2.44%   |
| HP 1998              | 1        | 2.44%   |
| Gigabyte Z77X-UD5H   | 1        | 2.44%   |
| Gigabyte Z270-Gaming | 1        | 2.44%   |
| Gigabyte H410M       | 1        | 2.44%   |
| Gigabyte GA-E6010N   | 1        | 2.44%   |
| Gigabyte F2A88XM-DS2 | 1        | 2.44%   |
| Gigabyte B550        | 1        | 2.44%   |
| Foxconn A76GMV       | 1        | 2.44%   |
| Foxconn 400-034      | 1        | 2.44%   |
| Dell OptiPlex        | 1        | 2.44%   |
| Dell Inspiron        | 1        | 2.44%   |
| AZW U59              | 1        | 2.44%   |
| ASUS Z170            | 1        | 2.44%   |
| ASUS TUF             | 1        | 2.44%   |
| ASUS P8H61-MX        | 1        | 2.44%   |
| ASUS P7P55           | 1        | 2.44%   |
| ASUS M4A785TD-V      | 1        | 2.44%   |
| ASUS BT6130-8        | 1        | 2.44%   |
| ASRock B660M-C       | 1        | 2.44%   |
| Acer Predator        | 1        | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 5        | 12.2%   |
| 2012 | 5        | 12.2%   |
| 2021 | 4        | 9.76%   |
| 2018 | 4        | 9.76%   |
| 2016 | 4        | 9.76%   |
| 2020 | 3        | 7.32%   |
| 2019 | 3        | 7.32%   |
| 2015 | 3        | 7.32%   |
| 2022 | 2        | 4.88%   |
| 2017 | 2        | 4.88%   |
| 2009 | 2        | 4.88%   |
| 2008 | 2        | 4.88%   |
| 2023 | 1        | 2.44%   |
| 2010 | 1        | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 41       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 41       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 11       | 26.83%  |
| 16.01-24.0  | 10       | 24.39%  |
| 8.01-16.0   | 7        | 17.07%  |
| 32.01-64.0  | 6        | 14.63%  |
| 3.01-4.0    | 5        | 12.2%   |
| 24.01-32.0  | 1        | 2.44%   |
| 64.01-256.0 | 1        | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 22       | 51.16%  |
| 1.01-2.0  | 10       | 23.26%  |
| 3.01-4.0  | 7        | 16.28%  |
| 4.01-8.0  | 3        | 6.98%   |
| 8.01-16.0 | 1        | 2.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 41.46%  |
| 2      | 14       | 34.15%  |
| 3      | 5        | 12.2%   |
| 5      | 3        | 7.32%   |
| 4      | 2        | 4.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 68.29%  |
| Yes       | 13       | 31.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 41       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 53.66%  |
| Yes       | 19       | 46.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 51.22%  |
| Yes       | 20       | 48.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Germany     | 8        | 19.51%  |
| USA         | 7        | 17.07%  |
| Spain       | 3        | 7.32%   |
| Russia      | 3        | 7.32%   |
| Brazil      | 3        | 7.32%   |
| Netherlands | 2        | 4.88%   |
| Italy       | 2        | 4.88%   |
| India       | 2        | 4.88%   |
| Sweden      | 1        | 2.44%   |
| Portugal    | 1        | 2.44%   |
| Mexico      | 1        | 2.44%   |
| Japan       | 1        | 2.44%   |
| Greece      | 1        | 2.44%   |
| France      | 1        | 2.44%   |
| Finland     | 1        | 2.44%   |
| Czechia     | 1        | 2.44%   |
| Chile       | 1        | 2.44%   |
| Canada      | 1        | 2.44%   |
| Australia   | 1        | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| West Jordan       | 1        | 2.38%   |
| Viareggio         | 1        | 2.38%   |
| Valencia          | 1        | 2.38%   |
| Tucson            | 1        | 2.38%   |
| Stuttgart         | 1        | 2.38%   |
| Stockholm         | 1        | 2.38%   |
| Steti             | 1        | 2.38%   |
| St Petersburg     | 1        | 2.38%   |
| Sao Paulo         | 1        | 2.38%   |
| Santiago          | 1        | 2.38%   |
| Sandim            | 1        | 2.38%   |
| San Marcos        | 1        | 2.38%   |
| Piea              | 1        | 2.38%   |
| Ojicho            | 1        | 2.38%   |
| Nossen            | 1        | 2.38%   |
| New York          | 1        | 2.38%   |
| Munich            | 1        | 2.38%   |
| Mumbai            | 1        | 2.38%   |
| Moscow            | 1        | 2.38%   |
| Morehead City     | 1        | 2.38%   |
| Monsummano Terme  | 1        | 2.38%   |
| Melbourne         | 1        | 2.38%   |
| Madrid            | 1        | 2.38%   |
| Los Montesinos    | 1        | 2.38%   |
| Las Vegas         | 1        | 2.38%   |
| Lagerdorf         | 1        | 2.38%   |
| Laberweinting     | 1        | 2.38%   |
| Juazeiro do Norte | 1        | 2.38%   |
| Irvine            | 1        | 2.38%   |
| Hürth            | 1        | 2.38%   |
| Helsinki          | 1        | 2.38%   |
| Hamm              | 1        | 2.38%   |
| Faridabad         | 1        | 2.38%   |
| Cuernavaca        | 1        | 2.38%   |
| Cheboksary        | 1        | 2.38%   |
| Casteljaloux      | 1        | 2.38%   |
| Brampton          | 1        | 2.38%   |
| Braganca          | 1        | 2.38%   |
| Augsburg          | 1        | 2.38%   |
| Athens            | 1        | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 13       | 13     | 17.57%  |
| Seagate                     | 9        | 14     | 12.16%  |
| Samsung Electronics         | 8        | 12     | 10.81%  |
| Toshiba                     | 4        | 5      | 5.41%   |
| SanDisk                     | 4        | 5      | 5.41%   |
| Kingston                    | 4        | 4      | 5.41%   |
| Hitachi                     | 3        | 4      | 4.05%   |
| Team                        | 2        | 3      | 2.7%    |
| PNY                         | 2        | 2      | 2.7%    |
| Netac                       | 2        | 3      | 2.7%    |
| Micron/Crucial Technology   | 2        | 2      | 2.7%    |
| Crucial                     | 2        | 3      | 2.7%    |
| China                       | 2        | 2      | 2.7%    |
| Yeestor                     | 1        | 1      | 1.35%   |
| XrayDisk                    | 1        | 1      | 1.35%   |
| Silicon Motion              | 1        | 1      | 1.35%   |
| SD                          | 1        | 1      | 1.35%   |
| NGFF                        | 1        | 1      | 1.35%   |
| Micron Technology           | 1        | 1      | 1.35%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 1.35%   |
| LuminouTek                  | 1        | 1      | 1.35%   |
| LITEONIT                    | 1        | 1      | 1.35%   |
| KingDian                    | 1        | 2      | 1.35%   |
| Intenso                     | 1        | 2      | 1.35%   |
| HS-SSD-E100                 | 1        | 2      | 1.35%   |
| Hewlett-Packard             | 1        | 1      | 1.35%   |
| Corsair                     | 1        | 1      | 1.35%   |
| Apacer                      | 1        | 1      | 1.35%   |
| A-DATA Technology           | 1        | 1      | 1.35%   |
| Unknown                     | 1        | 1      | 1.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| WDC WD10EZEX-60WN4A0 1TB                            | 3        | 3.66%   |
| Kingston SA400S37240G 240GB SSD                     | 3        | 3.66%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2        | 2.44%   |
| Samsung SSD 850 EVO 250GB                           | 2        | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2        | 2.44%   |
| Yeestor 512GB                                       | 1        | 1.22%   |
| XrayDisk 512GB SSD                                  | 1        | 1.22%   |
| WDC WDS480G2G0C-00AJM0 480GB                        | 1        | 1.22%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1        | 1.22%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 1.22%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 1        | 1.22%   |
| WDC WD2500JB-55GVA0 250GB                           | 1        | 1.22%   |
| WDC WD10EZEX-60ZF5A0 1TB                            | 1        | 1.22%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1        | 1.22%   |
| WDC WD10EZEX-00BBHA0 1TB                            | 1        | 1.22%   |
| Toshiba MQ01ABD100 1TB                              | 1        | 1.22%   |
| Toshiba DT01ACA200 2TB                              | 1        | 1.22%   |
| Toshiba DT01ACA100 1TB                              | 1        | 1.22%   |
| Toshiba DT01ACA050 500GB                            | 1        | 1.22%   |
| Team T253X2001T 1024GB SSD                          | 1        | 1.22%   |
| Team T253X1480G 480GB SSD                           | 1        | 1.22%   |
| Team L3 SSD 240GB                                   | 1        | 1.22%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1TB | 1        | 1.22%   |
| Seagate ST9500325AS 500GB                           | 1        | 1.22%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1        | 1.22%   |
| Seagate ST4000DM004-2CV104 4TB                      | 1        | 1.22%   |
| Seagate ST3500418AS 500GB                           | 1        | 1.22%   |
| Seagate ST31000528AS 1TB                            | 1        | 1.22%   |
| Seagate ST2000DM008-2FR102 2TB                      | 1        | 1.22%   |
| Seagate ST1000VT001-1RE172 1TB                      | 1        | 1.22%   |
| Seagate ST1000DM003-9YN162 1TB                      | 1        | 1.22%   |
| Seagate ST1000DM003-1ER162 1TB                      | 1        | 1.22%   |
| Seagate M3 1TB                                      | 1        | 1.22%   |
| Seagate BarraCuda Q1 SSD ZA960CV10001 960GB         | 1        | 1.22%   |
| Seagate BarraCuda 120 SSD ZA500CM10003 500GB        | 1        | 1.22%   |
| SD Ultra 3D 1TB                                     | 1        | 1.22%   |
| Sandisk WD_BLACK SN750 SE 500GB                     | 1        | 1.22%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 1        | 1.22%   |
| SanDisk SSD PLUS 120GB                              | 1        | 1.22%   |
| SanDisk SD7TB3Q-256G-1006 256GB SSD                 | 1        | 1.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 10     | 38.46%  |
| Seagate             | 8        | 11     | 30.77%  |
| Toshiba             | 4        | 5      | 15.38%  |
| Hitachi             | 3        | 4      | 11.54%  |
| Samsung Electronics | 1        | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 7      | 14.29%  |
| Kingston            | 4        | 4      | 11.43%  |
| WDC                 | 2        | 2      | 5.71%   |
| Team                | 2        | 3      | 5.71%   |
| Seagate             | 2        | 2      | 5.71%   |
| SanDisk             | 2        | 3      | 5.71%   |
| PNY                 | 2        | 2      | 5.71%   |
| Crucial             | 2        | 3      | 5.71%   |
| China               | 2        | 2      | 5.71%   |
| XrayDisk            | 1        | 1      | 2.86%   |
| NGFF                | 1        | 1      | 2.86%   |
| Netac               | 1        | 1      | 2.86%   |
| Micron Technology   | 1        | 1      | 2.86%   |
| LITEONIT            | 1        | 1      | 2.86%   |
| KingDian            | 1        | 2      | 2.86%   |
| Intenso             | 1        | 2      | 2.86%   |
| HS-SSD-E100         | 1        | 1      | 2.86%   |
| Hewlett-Packard     | 1        | 1      | 2.86%   |
| Corsair             | 1        | 1      | 2.86%   |
| Apacer              | 1        | 1      | 2.86%   |
| A-DATA Technology   | 1        | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 32       | 42     | 47.06%  |
| HDD     | 20       | 31     | 29.41%  |
| NVMe    | 9        | 11     | 13.24%  |
| Unknown | 7        | 8      | 10.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 40       | 79     | 78.43%  |
| NVMe | 9        | 11     | 17.65%  |
| SAS  | 2        | 2      | 3.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 30       | 44     | 58.82%  |
| 0.51-1.0   | 16       | 23     | 31.37%  |
| 1.01-2.0   | 3        | 4      | 5.88%   |
| 3.01-4.0   | 2        | 2      | 3.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 19       | 46.34%  |
| 501-1000   | 11       | 26.83%  |
| 251-500    | 7        | 17.07%  |
| 21-50      | 1        | 2.44%   |
| 2001-3000  | 1        | 2.44%   |
| 1001-2000  | 1        | 2.44%   |
| 51-100     | 1        | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 17       | 41.46%  |
| 21-50     | 10       | 24.39%  |
| 51-100    | 7        | 17.07%  |
| 101-250   | 5        | 12.2%   |
| 251-500   | 1        | 2.44%   |
| 1001-2000 | 1        | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| Hitachi HTS725050A7E630 500GB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 1        | 1      | 100%    |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 36       | 83     | 83.72%  |
| Works    | 6        | 8      | 13.95%  |
| Malfunc  | 1        | 1      | 2.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 27       | 49.09%  |
| AMD                         | 14       | 25.45%  |
| SanDisk                     | 3        | 5.45%   |
| Samsung Electronics         | 3        | 5.45%   |
| Micron/Crucial Technology   | 2        | 3.64%   |
| Marvell Technology Group    | 2        | 3.64%   |
| ASMedia Technology          | 2        | 3.64%   |
| Silicon Motion              | 1        | 1.82%   |
| MAXIO Technology (Hangzhou) | 1        | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10       | 14.93%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 7.46%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 5.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 4.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 4.48%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 4.48%   |
| SanDisk Non-Volatile memory controller                                                  | 2        | 2.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 2.99%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 2.99%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 2.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 2.99%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.99%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 2.99%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.49%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.49%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.49%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 1.49%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1        | 1.49%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 1.49%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 1.49%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 1.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.49%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.49%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.49%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.49%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.49%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.49%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 1.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 40       | 74.07%  |
| NVMe | 9        | 16.67%  |
| IDE  | 4        | 7.41%   |
| RAID | 1        | 1.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 27       | 65.85%  |
| AMD    | 14       | 34.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i9-9900K CPU @ 3.60GHz             | 2        | 4.88%   |
| Intel Celeron N5105 @ 2.00GHz                 | 2        | 4.88%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz           | 1        | 2.44%   |
| Intel Pentium CPU G2020 @ 2.90GHz             | 1        | 2.44%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1        | 2.44%   |
| Intel Core i7-6700T CPU @ 2.80GHz             | 1        | 2.44%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1        | 2.44%   |
| Intel Core i7-3770S CPU @ 3.10GHz             | 1        | 2.44%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1        | 2.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1        | 2.44%   |
| Intel Core i5-9400T CPU @ 1.80GHz             | 1        | 2.44%   |
| Intel Core i5-7500T CPU @ 2.70GHz             | 1        | 2.44%   |
| Intel Core i5-6600 CPU @ 3.30GHz              | 1        | 2.44%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1        | 2.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1        | 2.44%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1        | 2.44%   |
| Intel Core i5 CPU 760 @ 2.80GHz               | 1        | 2.44%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 1        | 2.44%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 1        | 2.44%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 1        | 2.44%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 1        | 2.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1        | 2.44%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1        | 2.44%   |
| Intel 12th Gen Core i7-12700K                 | 1        | 2.44%   |
| Intel 12th Gen Core i7-12700F                 | 1        | 2.44%   |
| AMD Sempron 145 Processor                     | 1        | 2.44%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1        | 2.44%   |
| AMD Ryzen 7 1700X Eight-Core Processor        | 1        | 2.44%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics    | 1        | 2.44%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 1        | 2.44%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1        | 2.44%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 1        | 2.44%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 1        | 2.44%   |
| AMD PRO A6-8550B R5, 6 Compute Cores 2C+4G    | 1        | 2.44%   |
| AMD Phenom II X6 1055T Processor              | 1        | 2.44%   |
| AMD G-T56N Processor                          | 1        | 2.44%   |
| AMD E1-6010 APU with AMD Radeon R2 Graphics   | 1        | 2.44%   |
| AMD Athlon 3000G with Radeon Vega Graphics    | 1        | 2.44%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 1        | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i5    | 7        | 17.07%  |
| Intel Core i7    | 6        | 14.63%  |
| Intel Core i3    | 4        | 9.76%   |
| Other            | 3        | 7.32%   |
| Intel Celeron    | 3        | 7.32%   |
| AMD Ryzen 5      | 3        | 7.32%   |
| Intel Core i9    | 2        | 4.88%   |
| Intel Xeon       | 1        | 2.44%   |
| Intel Pentium    | 1        | 2.44%   |
| Intel Core 2 Duo | 1        | 2.44%   |
| AMD Sempron      | 1        | 2.44%   |
| AMD Ryzen 9      | 1        | 2.44%   |
| AMD Ryzen 7      | 1        | 2.44%   |
| AMD Ryzen 5 PRO  | 1        | 2.44%   |
| AMD Ryzen 3      | 1        | 2.44%   |
| AMD Phenom II X6 | 1        | 2.44%   |
| AMD G            | 1        | 2.44%   |
| AMD E1           | 1        | 2.44%   |
| AMD Athlon       | 1        | 2.44%   |
| AMD A8           | 1        | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 16       | 38.1%   |
| 2      | 8        | 19.05%  |
| 6      | 7        | 16.67%  |
| 8      | 4        | 9.52%   |
| 12     | 3        | 7.14%   |
| 1      | 3        | 7.14%   |
| 5      | 1        | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 41       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 24       | 58.54%  |
| 1      | 17       | 41.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 41       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 34       | 82.93%  |
| 0x306a9    | 2        | 4.88%   |
| 0x906e9    | 1        | 2.44%   |
| 0x906c0    | 1        | 2.44%   |
| 0x08108109 | 1        | 2.44%   |
| 0x07030106 | 1        | 2.44%   |
| 0x010000c8 | 1        | 2.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 7        | 17.07%  |
| IvyBridge     | 5        | 12.2%   |
| Skylake       | 4        | 9.76%   |
| Haswell       | 3        | 7.32%   |
| Unknown       | 3        | 7.32%   |
| Zen+          | 2        | 4.88%   |
| Zen 3         | 2        | 4.88%   |
| Zen 2         | 2        | 4.88%   |
| Zen           | 2        | 4.88%   |
| Steamroller   | 2        | 4.88%   |
| K10           | 2        | 4.88%   |
| Tremont       | 1        | 2.44%   |
| Puma          | 1        | 2.44%   |
| Penryn        | 1        | 2.44%   |
| Nehalem       | 1        | 2.44%   |
| Goldmont plus | 1        | 2.44%   |
| CometLake     | 1        | 2.44%   |
| Bobcat        | 1        | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 16       | 38.1%   |
| Nvidia | 13       | 30.95%  |
| Intel  | 13       | 30.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK107 [GeForce GT 640]                                               | 2        | 4.65%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 4.65%   |
| Intel HD Graphics 630                                                       | 2        | 4.65%   |
| Intel HD Graphics 530                                                       | 2        | 4.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 4.65%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 4.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 4.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 4.65%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 2.33%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 2.33%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 2.33%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.33%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 2.33%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 2.33%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 2.33%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 2.33%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 2.33%   |
| Nvidia GA103 [GeForce RTX 3060 Ti]                                          | 1        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 2.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 2.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 2.33%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 2.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 2.33%   |
| AMD Wrestler [Radeon HD 6320]                                               | 1        | 2.33%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 2.33%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 2.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.33%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 2.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 2.33%   |
| AMD Mullins [Radeon R2 Graphics]                                            | 1        | 2.33%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 2.33%   |
| AMD Kaveri [Radeon R5 Graphics]                                             | 1        | 2.33%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 15       | 36.59%  |
| 1 x Nvidia     | 12       | 29.27%  |
| 1 x Intel      | 12       | 29.27%  |
| 2 x AMD        | 1        | 2.44%   |
| Intel + Nvidia | 1        | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 36       | 87.8%   |
| Proprietary | 5        | 12.2%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 85.37%  |
| 7.01-8.0   | 2        | 4.88%   |
| 0.51-1.0   | 2        | 4.88%   |
| 1.01-2.0   | 1        | 2.44%   |
| 0.01-0.5   | 1        | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 6        | 13.33%  |
| Goldstar             | 6        | 13.33%  |
| Hewlett-Packard      | 3        | 6.67%   |
| Dell                 | 3        | 6.67%   |
| Acer                 | 3        | 6.67%   |
| Sceptre Tech         | 2        | 4.44%   |
| Philips              | 2        | 4.44%   |
| BenQ                 | 2        | 4.44%   |
| ___                  | 1        | 2.22%   |
| Vizio                | 1        | 2.22%   |
| Unknown              | 1        | 2.22%   |
| Sony                 | 1        | 2.22%   |
| Positivo             | 1        | 2.22%   |
| NSL                  | 1        | 2.22%   |
| MYS                  | 1        | 2.22%   |
| MSI                  | 1        | 2.22%   |
| Lenovo               | 1        | 2.22%   |
| Kogan                | 1        | 2.22%   |
| Hitachi              | 1        | 2.22%   |
| HannStar             | 1        | 2.22%   |
| Fujitsu Siemens      | 1        | 2.22%   |
| Eizo                 | 1        | 2.22%   |
| CVT                  | 1        | 2.22%   |
| ASUSTek Computer     | 1        | 2.22%   |
| AOC                  | 1        | 2.22%   |
| Ancor Communications | 1        | 2.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ___ LCDTV16 ___3393 1366x768                                         | 1        | 2.13%   |
| Vizio E221VA VIZ0070 1920x1080 476x268mm 21.5-inch                   | 1        | 2.13%   |
| Unknown LCDTV16 3393 1920x1080 1600x900mm 72.3-inch                  | 1        | 2.13%   |
| Sony TV SNY7A02 1360x768 708x398mm 32.0-inch                         | 1        | 2.13%   |
| Sceptre Tech Sceptre Q27 SPT0AD2 2560x1440 597x336mm 27.0-inch       | 1        | 2.13%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch               | 1        | 2.13%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch | 1        | 2.13%   |
| Samsung Electronics SMB2030HD SAM0709 1600x900 443x249mm 20.0-inch   | 1        | 2.13%   |
| Samsung Electronics S27A950D SAM079F 1920x1080 598x336mm 27.0-inch   | 1        | 2.13%   |
| Samsung Electronics S24E450 SAM0C7F 1920x1080 521x293mm 23.5-inch    | 1        | 2.13%   |
| Samsung Electronics LS27AG55x SAM71E0 2560x1440 597x336mm 27.0-inch  | 1        | 2.13%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch    | 1        | 2.13%   |
| Positivo MC35120QWQHD NON3503 3440x1440 819x346mm 35.0-inch          | 1        | 2.13%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 1        | 2.13%   |
| Philips 220TS PHLC06B 1920x1080 477x268mm 21.5-inch                  | 1        | 2.13%   |
| NSL RGB-27QHD NSL2711 2560x1440 597x336mm 27.0-inch                  | 1        | 2.13%   |
| MYS LCD Monitor MYS1700 1280x1024 360x240mm 17.0-inch                | 1        | 2.13%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                       | 1        | 2.13%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                | 1        | 2.13%   |
| Kogan KAMN27QF7TA KGN0270 2560x1440 698x393mm 31.5-inch              | 1        | 2.13%   |
| Hitachi HISENSE HEC0030 1920x1080 580x330mm 26.3-inch                | 1        | 2.13%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch          | 1        | 2.13%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch         | 1        | 2.13%   |
| Hewlett-Packard E231 HWP3063 1920x1080 509x286mm 23.0-inch           | 1        | 2.13%   |
| HannStar HSG1074 HSP0019 1920x1080 543x305mm 24.5-inch               | 1        | 2.13%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch             | 1        | 2.13%   |
| Goldstar HDR WFHD GSM5BA0 2560x1080 798x334mm 34.1-inch              | 1        | 2.13%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch               | 1        | 2.13%   |
| Goldstar E2260 GSM57E0 1920x1080 477x268mm 21.5-inch                 | 1        | 2.13%   |
| Goldstar 27MP35 GSM5A86 1920x1080 598x337mm 27.0-inch                | 1        | 2.13%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                | 1        | 2.13%   |
| Fujitsu Siemens B27T-7 LED FUS083D 1920x1080 598x336mm 27.0-inch     | 1        | 2.13%   |
| Eizo LCD Monitor EV2456 1920x1200                                    | 1        | 2.13%   |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                     | 1        | 2.13%   |
| Dell P2213 DELF043 1680x1050 473x296mm 22.0-inch                     | 1        | 2.13%   |
| Dell LCD Monitor LNK0001 1920x1080 256x192mm 12.6-inch               | 1        | 2.13%   |
| Dell E1914H DELD03A 1366x768 410x230mm 18.5-inch                     | 1        | 2.13%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                    | 1        | 2.13%   |
| CVT CVTE TV CVT0003 1360x768 575x323mm 26.0-inch                     | 1        | 2.13%   |
| BenQ GW2406Z BNQ78E1 1920x1080 527x296mm 23.8-inch                   | 1        | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 25       | 55.56%  |
| 2560x1440 (QHD)    | 6        | 13.33%  |
| 3440x1440          | 2        | 4.44%   |
| 1920x1200 (WUXGA)  | 2        | 4.44%   |
| 1366x768 (WXGA)    | 2        | 4.44%   |
| 1280x1024 (SXGA)   | 2        | 4.44%   |
| 3840x2160 (4K)     | 1        | 2.22%   |
| 2560x1600          | 1        | 2.22%   |
| 2560x1080          | 1        | 2.22%   |
| 1680x1050 (WSXGA+) | 1        | 2.22%   |
| 1600x900 (HD+)     | 1        | 2.22%   |
| 1360x768           | 1        | 2.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 9        | 19.15%  |
| 27      | 7        | 14.89%  |
| 21      | 6        | 12.77%  |
| 23      | 4        | 8.51%   |
| 31      | 3        | 6.38%   |
| 34      | 2        | 4.26%   |
| 18      | 2        | 4.26%   |
| Unknown | 2        | 4.26%   |
| 84      | 1        | 2.13%   |
| 72      | 1        | 2.13%   |
| 42      | 1        | 2.13%   |
| 35      | 1        | 2.13%   |
| 32      | 1        | 2.13%   |
| 29      | 1        | 2.13%   |
| 26      | 1        | 2.13%   |
| 22      | 1        | 2.13%   |
| 20      | 1        | 2.13%   |
| 19      | 1        | 2.13%   |
| 17      | 1        | 2.13%   |
| 14      | 1        | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 19       | 42.22%  |
| 401-500     | 10       | 22.22%  |
| 601-700     | 4        | 8.89%   |
| 701-800     | 3        | 6.67%   |
| 351-400     | 2        | 4.44%   |
| 1501-2000   | 2        | 4.44%   |
| Unknown     | 2        | 4.44%   |
| 801-900     | 1        | 2.22%   |
| 201-300     | 1        | 2.22%   |
| 901-1000    | 1        | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 33       | 75%     |
| 16/10   | 4        | 9.09%   |
| 21/9    | 3        | 6.82%   |
| 6/5     | 1        | 2.27%   |
| 4/3     | 1        | 2.27%   |
| 3/2     | 1        | 2.27%   |
| Unknown | 1        | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 32.61%  |
| 351-500        | 8        | 17.39%  |
| 301-350        | 7        | 15.22%  |
| 151-200        | 4        | 8.7%    |
| 251-300        | 3        | 6.52%   |
| More than 1000 | 2        | 4.35%   |
| 141-150        | 2        | 4.35%   |
| Unknown        | 2        | 4.35%   |
| 131-140        | 1        | 2.17%   |
| 101-110        | 1        | 2.17%   |
| 501-1000       | 1        | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 26       | 61.9%   |
| 101-120 | 11       | 26.19%  |
| 1-50    | 2        | 4.76%   |
| Unknown | 2        | 4.76%   |
| 121-160 | 1        | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 82.93%  |
| 2     | 7        | 17.07%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 21       | 35%     |
| Intel                    | 19       | 31.67%  |
| Qualcomm Atheros         | 6        | 10%     |
| Broadcom                 | 3        | 5%      |
| TP-Link                  | 2        | 3.33%   |
| Xiaomi                   | 1        | 1.67%   |
| Samsung Electronics      | 1        | 1.67%   |
| Ralink                   | 1        | 1.67%   |
| Qualcomm                 | 1        | 1.67%   |
| MediaTek                 | 1        | 1.67%   |
| Marvell Technology Group | 1        | 1.67%   |
| Linksys                  | 1        | 1.67%   |
| Huawei Technologies      | 1        | 1.67%   |
| ASUSTek Computer         | 1        | 1.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 27.94%  |
| Intel Ethernet Controller I225-V                                  | 3        | 4.41%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 4.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 2.94%   |
| Intel Wireless 3165                                               | 2        | 2.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 2.94%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 2.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.94%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 2.94%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.47%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 1.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 1.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 1.47%   |
| Qualcomm Fairphone 4 5G                                           | 1        | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 1.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.47%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 1.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.47%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 1.47%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless               | 1        | 1.47%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]     | 1        | 1.47%   |
| Intel Wireless 8260                                               | 1        | 1.47%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.47%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.47%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 1.47%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.47%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.47%   |
| Huawei ANE-LX1                                                    | 1        | 1.47%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                    | 1        | 1.47%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 1.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 1.47%   |
| ASUS 802.11ac WLAN Adapter                                        | 1        | 1.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 8        | 38.1%   |
| Realtek Semiconductor    | 3        | 14.29%  |
| Qualcomm Atheros         | 3        | 14.29%  |
| TP-Link                  | 1        | 4.76%   |
| Ralink                   | 1        | 4.76%   |
| MediaTek                 | 1        | 4.76%   |
| Marvell Technology Group | 1        | 4.76%   |
| Linksys                  | 1        | 4.76%   |
| Broadcom                 | 1        | 4.76%   |
| ASUSTek Computer         | 1        | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2        | 9.52%   |
| Intel Wireless 3165                                           | 2        | 9.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2        | 9.52%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 2        | 9.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1        | 4.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1        | 4.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1        | 4.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1        | 4.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1        | 4.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 1        | 4.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1        | 4.76%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless           | 1        | 4.76%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235] | 1        | 4.76%   |
| Intel Wireless 8260                                           | 1        | 4.76%   |
| Intel Wi-Fi 6 AX200                                           | 1        | 4.76%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 1        | 4.76%   |
| ASUS 802.11ac WLAN Adapter                                    | 1        | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 43.48%  |
| Intel                 | 17       | 36.96%  |
| Qualcomm Atheros      | 3        | 6.52%   |
| Broadcom              | 2        | 4.35%   |
| Xiaomi                | 1        | 2.17%   |
| TP-Link               | 1        | 2.17%   |
| Qualcomm              | 1        | 2.17%   |
| Huawei Technologies   | 1        | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 41.3%   |
| Intel Ethernet Controller I225-V                                  | 3        | 6.52%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 6.52%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 4.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 4.35%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 4.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 2.17%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.17%   |
| Qualcomm Fairphone 4 5G                                           | 1        | 2.17%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 2.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.17%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 2.17%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.17%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.17%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 2.17%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.17%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.17%   |
| Huawei ANE-LX1                                                    | 1        | 2.17%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                    | 1        | 2.17%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 41       | 67.21%  |
| WiFi     | 19       | 31.15%  |
| Modem    | 1        | 1.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 77.5%   |
| WiFi     | 9        | 22.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 53.66%  |
| 2     | 15       | 36.59%  |
| 3     | 3        | 7.32%   |
| 0     | 1        | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 24       | 58.54%  |
| Yes  | 17       | 41.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 40%     |
| Cambridge Silicon Radio         | 4        | 20%     |
| Realtek Semiconductor           | 2        | 10%     |
| Qualcomm Atheros Communications | 2        | 10%     |
| ASUSTek Computer                | 2        | 10%     |
| MediaTek                        | 1        | 5%      |
| Broadcom                        | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 20%     |
| Intel Bluetooth wireless interface                  | 3        | 15%     |
| Realtek Bluetooth Radio                             | 2        | 10%     |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 10%     |
| Intel AX210 Bluetooth                               | 2        | 10%     |
| MediaTek Wireless_Device                            | 1        | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 5%      |
| Intel AX201 Bluetooth                               | 1        | 5%      |
| Intel AX200 Bluetooth                               | 1        | 5%      |
| Broadcom Bluetooth 3.0 Dongle                       | 1        | 5%      |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 5%      |
| ASUS ASUS USB-BT500                                 | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 27       | 37.5%   |
| AMD                      | 18       | 25%     |
| Nvidia                   | 13       | 18.06%  |
| C-Media Electronics      | 5        | 6.94%   |
| Logitech                 | 3        | 4.17%   |
| Razer USA                | 1        | 1.39%   |
| Nordic Semiconductor ASA | 1        | 1.39%   |
| KTMicro                  | 1        | 1.39%   |
| Goldvish                 | 1        | 1.39%   |
| Creative Labs            | 1        | 1.39%   |
| ASUSTek Computer         | 1        | 1.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 5        | 6.02%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 4        | 4.82%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 4        | 4.82%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 3        | 3.61%   |
| Intel Cannon Lake PCH cAVS                                                                      | 3        | 3.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 3        | 3.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 3        | 3.61%   |
| Intel 200 Series PCH HD Audio                                                                   | 3        | 3.61%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 3        | 3.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 3        | 3.61%   |
| AMD FCH Azalia Controller                                                                       | 3        | 3.61%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 2        | 2.41%   |
| Intel Jasper Lake HD Audio                                                                      | 2        | 2.41%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 2        | 2.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 2        | 2.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 2        | 2.41%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 2        | 2.41%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 2        | 2.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 2        | 2.41%   |
| Razer USA Razer Barracuda X                                                                     | 1        | 1.2%    |
| Nvidia TU116 High Definition Audio Controller                                                   | 1        | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                  | 1        | 1.2%    |
| Nvidia TU104 HD Audio Controller                                                                | 1        | 1.2%    |
| Nvidia High Definition Audio Controller                                                         | 1        | 1.2%    |
| Nvidia GP108 High Definition Audio Controller                                                   | 1        | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                                                 | 1        | 1.2%    |
| Nvidia GP104 High Definition Audio Controller                                                   | 1        | 1.2%    |
| Nvidia Audio device                                                                             | 1        | 1.2%    |
| Nordic Semiconductor ASA USB Composite Device                                                   | 1        | 1.2%    |
| Logitech [G533 Wireless Headset Dongle]                                                         | 1        | 1.2%    |
| Logitech Logi Z407                                                                              | 1        | 1.2%    |
| Logitech G432 Gaming Headset                                                                    | 1        | 1.2%    |
| KTMicro KT USB Audio                                                                            | 1        | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 1        | 1.2%    |
| Intel Smart Sound Technology (SST) Audio Controller                                             | 1        | 1.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                    | 1        | 1.2%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 1        | 1.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 1        | 1.2%    |
| Goldvish H210                                                                                   | 1        | 1.2%    |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1        | 1.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 3        | 30%     |
| Unknown (0x5846)    | 1        | 10%     |
| Samsung Electronics | 1        | 10%     |
| CSX                 | 1        | 10%     |
| Corsair             | 1        | 10%     |
| Apacer              | 1        | 10%     |
| A-DATA Technology   | 1        | 10%     |
| Unknown             | 1        | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s | 1        | 10%     |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s           | 1        | 10%     |
| Kingston RAM HX426C16FB/4 4GB DIMM DDR4 2800MT/s              | 1        | 10%     |
| Kingston RAM HX318C10F/8 8GB DIMM DDR3 1600MT/s               | 1        | 10%     |
| Kingston RAM ASU16D3LU1KBG/4G 4GB DIMM DDR3 3200MT/s          | 1        | 10%     |
| CSX RAM V01D3L82GB26826813 2GB DIMM 1066MT/s                  | 1        | 10%     |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s          | 1        | 10%     |
| Apacer RAM 78.CAGP7.C7Z0B 8GB DIMM DDR4 2400MT/s              | 1        | 10%     |
| A-DATA RAM Module 4GB DIMM DDR3 1600MT/s                      | 1        | 10%     |
| Unknown                                                       | 1        | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 3        | 37.5%   |
| DDR3    | 3        | 37.5%   |
| SDRAM   | 1        | 12.5%   |
| Unknown | 1        | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 6        | 85.71%  |
| SODIMM | 1        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 4        | 50%     |
| 4096 | 3        | 37.5%   |
| 2048 | 1        | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2800  | 2        | 20%     |
| 1600  | 2        | 20%     |
| 3200  | 1        | 10%     |
| 2667  | 1        | 10%     |
| 2400  | 1        | 10%     |
| 2000  | 1        | 10%     |
| 1066  | 1        | 10%     |
| 533   | 1        | 10%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 50%     |
| Canon               | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Samsung M2020 Series | 1        | 50%     |
| Canon MF4320-4350    | 1        | 50%     |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Sunplus Innovation Technology | 1        | 33.33%  |
| Generalplus Technology        | 1        | 33.33%  |
| Apple                         | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Sunplus FHD Camera Microphone   | 1        | 33.33%  |
| Generalplus GENERAL WEBCAM      | 1        | 33.33%  |
| Apple iPhone 5/5C/5S/6/SE/7/8/X | 1        | 33.33%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 34       | 82.93%  |
| 1     | 7        | 17.07%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 4        | 57.14%  |
| Net/ethernet          | 1        | 14.29%  |
| Multimedia controller | 1        | 14.29%  |
| Graphics card         | 1        | 14.29%  |

