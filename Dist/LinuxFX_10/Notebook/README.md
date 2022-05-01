LinuxFX 10 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for LinuxFX 10.

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

Total: 55

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Samsung  | 340XAA/350XAA/550XAA        | [cd93e2fd82](https://linux-hardware.org/?probe=cd93e2fd82) | Apr 08, 2022 |
| Toshiba  | Satellite C660              | [47b40007ee](https://linux-hardware.org/?probe=47b40007ee) | Dec 04, 2021 |
| Dell     | Inspiron 1501               | [94ca9e7f47](https://linux-hardware.org/?probe=94ca9e7f47) | Nov 12, 2021 |
| Dell     | Latitude E6420              | [dc9a1e9c1b](https://linux-hardware.org/?probe=dc9a1e9c1b) | Oct 18, 2021 |
| HP       | 250 G7 Notebook PC          | [7368bcaf0a](https://linux-hardware.org/?probe=7368bcaf0a) | Oct 04, 2021 |
| HP       | 250 G7 Notebook PC          | [c7ae2849cc](https://linux-hardware.org/?probe=c7ae2849cc) | Sep 30, 2021 |
| Medion   | S4216                       | [677bd3ecb4](https://linux-hardware.org/?probe=677bd3ecb4) | Aug 27, 2021 |
| Medion   | S4216                       | [a0ae7753cf](https://linux-hardware.org/?probe=a0ae7753cf) | Aug 26, 2021 |
| Dell     | Inspiron 3421               | [06a0a6486b](https://linux-hardware.org/?probe=06a0a6486b) | Aug 26, 2021 |
| Dell     | Latitude E5520              | [cae8dd2173](https://linux-hardware.org/?probe=cae8dd2173) | Jul 27, 2021 |
| Dell     | Latitude E5520              | [0112c3a302](https://linux-hardware.org/?probe=0112c3a302) | Jul 22, 2021 |
| Samsung  | 305E4A/305E5A/305E7A        | [3db60d4f9a](https://linux-hardware.org/?probe=3db60d4f9a) | Jun 01, 2021 |
| HP       | Pavilion dv6700             | [4e93c68985](https://linux-hardware.org/?probe=4e93c68985) | May 26, 2021 |
| HP       | Pavilion dv6700             | [a114e32ffb](https://linux-hardware.org/?probe=a114e32ffb) | May 26, 2021 |
| Lenovo   | ThinkPad T450s 20BWS0YF0... | [7b1e0f2693](https://linux-hardware.org/?probe=7b1e0f2693) | May 11, 2021 |
| Acer     | Aspire E5-551               | [9f023d545c](https://linux-hardware.org/?probe=9f023d545c) | Mar 23, 2021 |
| Acer     | Aspire 5755G                | [0984c7aebc](https://linux-hardware.org/?probe=0984c7aebc) | Mar 18, 2021 |
| Acer     | Aspire 5755G                | [861fb95171](https://linux-hardware.org/?probe=861fb95171) | Mar 09, 2021 |
| ASUSTek  | K50C                        | [d6ac6b2de1](https://linux-hardware.org/?probe=d6ac6b2de1) | Feb 18, 2021 |
| ASUSTek  | K50C                        | [a899af5e96](https://linux-hardware.org/?probe=a899af5e96) | Feb 18, 2021 |
| Dell     | Inspiron 1525               | [30d9ab855e](https://linux-hardware.org/?probe=30d9ab855e) | Feb 16, 2021 |
| Dell     | Inspiron 1525               | [a37ef6324c](https://linux-hardware.org/?probe=a37ef6324c) | Feb 16, 2021 |
| Lenovo   | ThinkPad X1 Carbon 2nd F... | [799c301ad6](https://linux-hardware.org/?probe=799c301ad6) | Feb 08, 2021 |
| Pegatron | B34C                        | [4c3a4f9ad1](https://linux-hardware.org/?probe=4c3a4f9ad1) | Feb 05, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | [a22da47202](https://linux-hardware.org/?probe=a22da47202) | Jan 30, 2021 |
| Acer     | Aspire A515-51G             | [3300b2bb9d](https://linux-hardware.org/?probe=3300b2bb9d) | Jan 22, 2021 |
| Lenovo   | Y70-70 Touch 80DU           | [023b353ca8](https://linux-hardware.org/?probe=023b353ca8) | Dec 22, 2020 |
| Acer     | Aspire 5720Z                | [38045109f8](https://linux-hardware.org/?probe=38045109f8) | Nov 29, 2020 |
| Toshiba  | Satellite C50D-A-12R        | [2b5e2b26b2](https://linux-hardware.org/?probe=2b5e2b26b2) | Nov 23, 2020 |
| Gigabyte | P57V6                       | [ec76a0907c](https://linux-hardware.org/?probe=ec76a0907c) | Nov 15, 2020 |
| Acer     | Aspire ES1-512              | [328c13ce38](https://linux-hardware.org/?probe=328c13ce38) | Oct 25, 2020 |
| Acer     | Aspire ES1-512              | [59368b9e58](https://linux-hardware.org/?probe=59368b9e58) | Oct 24, 2020 |
| Acer     | Aspire 6930G                | [1519ec67b5](https://linux-hardware.org/?probe=1519ec67b5) | Sep 07, 2020 |
| Acer     | Aspire 6930G                | [51b6611d94](https://linux-hardware.org/?probe=51b6611d94) | Sep 06, 2020 |
| Dell     | Inspiron 15-3567            | [d7fbcdbfbe](https://linux-hardware.org/?probe=d7fbcdbfbe) | Sep 03, 2020 |
| HP       | Compaq Presario CQ50        | [b82778b925](https://linux-hardware.org/?probe=b82778b925) | Sep 01, 2020 |
| Gigabyte | P57V6                       | [7f8d44d28e](https://linux-hardware.org/?probe=7f8d44d28e) | Aug 30, 2020 |
| HP       | ProBook 6560b               | [99a7a9817b](https://linux-hardware.org/?probe=99a7a9817b) | Aug 26, 2020 |
| HP       | ProBook 6560b               | [b9893a704d](https://linux-hardware.org/?probe=b9893a704d) | Aug 26, 2020 |
| Olivetti | P55-AEU-323-4G320           | [c08737d73c](https://linux-hardware.org/?probe=c08737d73c) | Aug 23, 2020 |
| Lenovo   | G505 20240                  | [aa6a5c7462](https://linux-hardware.org/?probe=aa6a5c7462) | Aug 22, 2020 |
| ASUSTek  | K72Jr                       | [51cd547219](https://linux-hardware.org/?probe=51cd547219) | Aug 18, 2020 |
| ASUSTek  | K72Jr                       | [d68a58547e](https://linux-hardware.org/?probe=d68a58547e) | Aug 15, 2020 |
| Dell     | Inspiron 5423               | [1f3e63e601](https://linux-hardware.org/?probe=1f3e63e601) | Jul 24, 2020 |
| Acer     | Aspire E1-531               | [6104770d46](https://linux-hardware.org/?probe=6104770d46) | Jul 23, 2020 |
| Dell     | Vostro 1000                 | [ffb49e4b86](https://linux-hardware.org/?probe=ffb49e4b86) | Jul 22, 2020 |
| Positivo | Mobile                      | [7ac9083ae4](https://linux-hardware.org/?probe=7ac9083ae4) | Jul 21, 2020 |
| HP       | Mini 210-1000               | [d1e83a2d9b](https://linux-hardware.org/?probe=d1e83a2d9b) | Jul 19, 2020 |
| HP       | 250 G6 Notebook PC          | [bc9d23a74c](https://linux-hardware.org/?probe=bc9d23a74c) | Jul 02, 2020 |
| HP       | 250 G6 Notebook PC          | [b1757b232f](https://linux-hardware.org/?probe=b1757b232f) | Jul 02, 2020 |
| Lenovo   | G550 2958                   | [6cfc44a819](https://linux-hardware.org/?probe=6cfc44a819) | Jun 11, 2020 |
| Lenovo   | G550 2958                   | [95b68a8144](https://linux-hardware.org/?probe=95b68a8144) | Jun 11, 2020 |
| Dell     | Inspiron 3520               | [c78c5e6395](https://linux-hardware.org/?probe=c78c5e6395) | May 16, 2020 |
| HP       | EliteBook Folio 9470m       | [f0b4ebc551](https://linux-hardware.org/?probe=f0b4ebc551) | May 16, 2020 |
| HP       | G42                         | [5c1017a089](https://linux-hardware.org/?probe=5c1017a089) | May 11, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.6.15-windowsfx-10-generic | 5         | 13.51%  |
| 5.4.0-72-generic            | 5         | 13.51%  |
| 5.4.0-52-generic            | 4         | 10.81%  |
| 5.7.15-050715-generic       | 3         | 8.11%   |
| 5.4.0-73-generic            | 3         | 8.11%   |
| 5.4.0-65-generic            | 3         | 8.11%   |
| 5.4.0-42-generic            | 3         | 8.11%   |
| 5.4.0-29-generic            | 3         | 8.11%   |
| 5.7.8-windowsfx-generic     | 2         | 5.41%   |
| 5.5.19-050519-generic       | 2         | 5.41%   |
| 5.4.0-90-generic            | 1         | 2.7%    |
| 5.4.0-67-generic            | 1         | 2.7%    |
| 5.4.0-54-generic            | 1         | 2.7%    |
| 5.10.2-051002-generic       | 1         | 2.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 24        | 64.86%  |
| 5.6.15  | 5         | 13.51%  |
| 5.7.15  | 3         | 8.11%   |
| 5.7.8   | 2         | 5.41%   |
| 5.5.19  | 2         | 5.41%   |
| 5.10.2  | 1         | 2.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 24        | 64.86%  |
| 5.7     | 5         | 13.51%  |
| 5.6     | 5         | 13.51%  |
| 5.5     | 2         | 5.41%   |
| 5.10    | 1         | 2.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 37        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 30        | 81.08%  |
| KDE        | 3         | 8.11%   |
| Cinnamon   | 3         | 8.11%   |
| Unknown    | 1         | 2.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 37        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 56.76%  |
| SDDM    | 9         | 24.32%  |
| LightDM | 6         | 16.22%  |
| TDM     | 1         | 2.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| pt_BR | 13        | 35.14%  |
| en_US | 4         | 10.81%  |
| pl_PL | 3         | 8.11%   |
| it_IT | 3         | 8.11%   |
| fr_FR | 2         | 5.41%   |
| es_ES | 2         | 5.41%   |
| es_AR | 2         | 5.41%   |
| en_AU | 2         | 5.41%   |
| ro_RO | 1         | 2.7%    |
| es_MX | 1         | 2.7%    |
| es_CL | 1         | 2.7%    |
| en_ZA | 1         | 2.7%    |
| en_CA | 1         | 2.7%    |
| C     | 1         | 2.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 25        | 67.57%  |
| EFI  | 12        | 32.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 37        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 33        | 89.19%  |
| MBR     | 2         | 5.41%   |
| GPT     | 2         | 5.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 89.19%  |
| Yes       | 4         | 10.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 83.78%  |
| Yes       | 6         | 16.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 21.62%  |
| Dell                | 8         | 21.62%  |
| Lenovo              | 5         | 13.51%  |
| Acer                | 5         | 13.51%  |
| ASUSTek Computer    | 3         | 8.11%   |
| Samsung Electronics | 2         | 5.41%   |
| Toshiba             | 1         | 2.7%    |
| Positivo            | 1         | 2.7%    |
| Pegatron            | 1         | 2.7%    |
| Olivetti            | 1         | 2.7%    |
| Medion              | 1         | 2.7%    |
| Gigabyte Technology | 1         | 2.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba Satellite C50D-A-12R             | 1         | 2.7%    |
| Samsung 340XAA/350XAA/550XAA             | 1         | 2.7%    |
| Samsung 305E4A/305E5A/305E7A             | 1         | 2.7%    |
| Positivo Mobile                          | 1         | 2.7%    |
| Pegatron B34C                            | 1         | 2.7%    |
| Olivetti P55-AEU-323-4G320               | 1         | 2.7%    |
| Medion S4216                             | 1         | 2.7%    |
| Lenovo Y70-70 Touch 80DU                 | 1         | 2.7%    |
| Lenovo ThinkPad X1 Carbon 2nd F2G3H4J    | 1         | 2.7%    |
| Lenovo ThinkPad T450s 20BWS0YF00         | 1         | 2.7%    |
| Lenovo G550 2958                         | 1         | 2.7%    |
| Lenovo G505 20240                        | 1         | 2.7%    |
| HP ProBook 6560b                         | 1         | 2.7%    |
| HP Pavilion dv6700                       | 1         | 2.7%    |
| HP Mini 210-1000                         | 1         | 2.7%    |
| HP G42                                   | 1         | 2.7%    |
| HP EliteBook Folio 9470m                 | 1         | 2.7%    |
| HP Compaq Presario CQ50                  | 1         | 2.7%    |
| HP 250 G7 Notebook PC                    | 1         | 2.7%    |
| HP 250 G6 Notebook PC                    | 1         | 2.7%    |
| Gigabyte P57V6                           | 1         | 2.7%    |
| Dell Vostro 1000                         | 1         | 2.7%    |
| Dell Latitude E6420                      | 1         | 2.7%    |
| Dell Inspiron 5423                       | 1         | 2.7%    |
| Dell Inspiron 3520                       | 1         | 2.7%    |
| Dell Inspiron 3421                       | 1         | 2.7%    |
| Dell Inspiron 1525                       | 1         | 2.7%    |
| Dell Inspiron 1501                       | 1         | 2.7%    |
| Dell Inspiron 15-3567                    | 1         | 2.7%    |
| ASUS K72Jr                               | 1         | 2.7%    |
| ASUS K50C                                | 1         | 2.7%    |
| ASUS ASUS TUF Gaming F15 FX506LI_FX506LI | 1         | 2.7%    |
| Acer Aspire ES1-512                      | 1         | 2.7%    |
| Acer Aspire E5-551                       | 1         | 2.7%    |
| Acer Aspire E1-531                       | 1         | 2.7%    |
| Acer Aspire A515-51G                     | 1         | 2.7%    |
| Acer Aspire 5720Z                        | 1         | 2.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Inspiron              | 6         | 16.22%  |
| Acer Aspire                | 5         | 13.51%  |
| Lenovo ThinkPad            | 2         | 5.41%   |
| HP 250                     | 2         | 5.41%   |
| Toshiba Satellite          | 1         | 2.7%    |
| Samsung 340XAA             | 1         | 2.7%    |
| Samsung 305E4A             | 1         | 2.7%    |
| Positivo Mobile            | 1         | 2.7%    |
| Pegatron B34C              | 1         | 2.7%    |
| Olivetti P55-AEU-323-4G320 | 1         | 2.7%    |
| Medion S4216               | 1         | 2.7%    |
| Lenovo Y70-70              | 1         | 2.7%    |
| Lenovo G550                | 1         | 2.7%    |
| Lenovo G505                | 1         | 2.7%    |
| HP ProBook                 | 1         | 2.7%    |
| HP Pavilion                | 1         | 2.7%    |
| HP Mini                    | 1         | 2.7%    |
| HP G42                     | 1         | 2.7%    |
| HP EliteBook               | 1         | 2.7%    |
| HP Compaq                  | 1         | 2.7%    |
| Gigabyte P57V6             | 1         | 2.7%    |
| Dell Vostro                | 1         | 2.7%    |
| Dell Latitude              | 1         | 2.7%    |
| ASUS K72Jr                 | 1         | 2.7%    |
| ASUS K50C                  | 1         | 2.7%    |
| ASUS ASUS                  | 1         | 2.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 6         | 16.22%  |
| 2014    | 5         | 13.51%  |
| 2009    | 4         | 10.81%  |
| 2018    | 3         | 8.11%   |
| 2013    | 3         | 8.11%   |
| 2011    | 3         | 8.11%   |
| 2017    | 2         | 5.41%   |
| 2008    | 2         | 5.41%   |
| 2007    | 2         | 5.41%   |
| 2006    | 2         | 5.41%   |
| 2020    | 1         | 2.7%    |
| 2016    | 1         | 2.7%    |
| 2015    | 1         | 2.7%    |
| 2010    | 1         | 2.7%    |
| Unknown | 1         | 2.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 37        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 36        | 94.74%  |
| Enabled  | 2         | 5.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 37        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 17        | 45.95%  |
| 4.01-8.0   | 11        | 29.73%  |
| 16.01-24.0 | 3         | 8.11%   |
| 2.01-3.0   | 2         | 5.41%   |
| 1.01-2.0   | 2         | 5.41%   |
| 8.01-16.0  | 2         | 5.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 23        | 60.53%  |
| 3.01-4.0 | 7         | 18.42%  |
| 2.01-3.0 | 5         | 13.16%  |
| 4.01-8.0 | 2         | 5.26%   |
| 0.51-1.0 | 1         | 2.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 32        | 86.49%  |
| 2      | 4         | 10.81%  |
| 3      | 1         | 2.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 70.27%  |
| No        | 11        | 29.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 54.05%  |
| No        | 17        | 45.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Brazil       | 13        | 35.14%  |
| USA          | 3         | 8.11%   |
| Poland       | 3         | 8.11%   |
| Italy        | 3         | 8.11%   |
| Spain        | 2         | 5.41%   |
| Canada       | 2         | 5.41%   |
| Australia    | 2         | 5.41%   |
| Argentina    | 2         | 5.41%   |
| South Africa | 1         | 2.7%    |
| Russia       | 1         | 2.7%    |
| Romania      | 1         | 2.7%    |
| Mexico       | 1         | 2.7%    |
| France       | 1         | 2.7%    |
| Chile        | 1         | 2.7%    |
| Cameroon     | 1         | 2.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Krakow         | 2         | 5.13%   |
| Curitiba       | 2         | 5.13%   |
| Zielonka       | 1         | 2.56%   |
| Winston-Salem  | 1         | 2.56%   |
| Villemomble    | 1         | 2.56%   |
| Vila Velha     | 1         | 2.56%   |
| Val-d'Or       | 1         | 2.56%   |
| Sydney         | 1         | 2.56%   |
| Sao Paulo      | 1         | 2.56%   |
| Sao Bernardo   | 1         | 2.56%   |
| Salerno        | 1         | 2.56%   |
| Saladas        | 1         | 2.56%   |
| Rosario        | 1         | 2.56%   |
| Rio Grande     | 1         | 2.56%   |
| Recife         | 1         | 2.56%   |
| Ramenskoye     | 1         | 2.56%   |
| Porto Alegre   | 1         | 2.56%   |
| Pontevedra     | 1         | 2.56%   |
| Pietra Ligure  | 1         | 2.56%   |
| Monserrato     | 1         | 2.56%   |
| Madrid         | 1         | 2.56%   |
| Londrina       | 1         | 2.56%   |
| Launceston     | 1         | 2.56%   |
| Johannesburg   | 1         | 2.56%   |
| Itatiba        | 1         | 2.56%   |
| Hobart         | 1         | 2.56%   |
| Eureka         | 1         | 2.56%   |
| Embu           | 1         | 2.56%   |
| Edmundston     | 1         | 2.56%   |
| Douala         | 1         | 2.56%   |
| Cincinnati     | 1         | 2.56%   |
| Central        | 1         | 2.56%   |
| Cabo Frio      | 1         | 2.56%   |
| Belo Horizonte | 1         | 2.56%   |
| BelÃ©m       | 1         | 2.56%   |
| Barcelona      | 1         | 2.56%   |
| Arad           | 1         | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 19.05%  |
| Seagate             | 8         | 8      | 19.05%  |
| Toshiba             | 5         | 5      | 11.9%   |
| Kingston            | 4         | 4      | 9.52%   |
| Samsung Electronics | 3         | 3      | 7.14%   |
| Hitachi             | 3         | 4      | 7.14%   |
| Unknown             | 2         | 3      | 4.76%   |
| LITEONIT            | 2         | 2      | 4.76%   |
| HGST                | 2         | 3      | 4.76%   |
| A-DATA Technology   | 2         | 2      | 4.76%   |
| SanDisk             | 1         | 1      | 2.38%   |
| GOODRAM             | 1         | 1      | 2.38%   |
| Crucial             | 1         | 1      | 2.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 2         | 4.76%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 2.38%   |
| WDC WD5000LPVT-24G33T1 500GB         | 1         | 2.38%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 2.38%   |
| WDC WD3200BEVT-80A0RT0 320GB         | 1         | 2.38%   |
| WDC WD1200BEVS-75UST0 120GB          | 1         | 2.38%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 2.38%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 2.38%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB | 1         | 2.38%   |
| Unknown NVMe SSD Drive 512GB         | 1         | 2.38%   |
| Unknown MMC Card  8GB                | 1         | 2.38%   |
| Toshiba MQ01ABF032 320GB             | 1         | 2.38%   |
| Toshiba MK5059GSXP 500GB             | 1         | 2.38%   |
| Toshiba MK2561GSYN 250GB             | 1         | 2.38%   |
| Seagate ST9320325AS 320GB            | 1         | 2.38%   |
| Seagate ST9160827AS 160GB            | 1         | 2.38%   |
| Seagate ST9160821AS 160GB            | 1         | 2.38%   |
| Seagate ST9160314AS 160GB            | 1         | 2.38%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 2.38%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 2.38%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 1         | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 2.38%   |
| SanDisk SSD PLUS 1000GB              | 1         | 2.38%   |
| Samsung SSD 850 EVO 250GB            | 1         | 2.38%   |
| Samsung MZMPC032HBCD-000D1 32GB SSD  | 1         | 2.38%   |
| Samsung HM321HI 320GB                | 1         | 2.38%   |
| LITEONIT LMT-256M6M-HP 256GB SSD     | 1         | 2.38%   |
| LITEONIT LGT-256M6G 256GB SSD        | 1         | 2.38%   |
| Kingston SV300S37A120G 120GB SSD     | 1         | 2.38%   |
| Kingston SUV400S37120G 120GB SSD     | 1         | 2.38%   |
| Kingston SA400S37240G 240GB SSD      | 1         | 2.38%   |
| Kingston NVMe SSD Drive 512GB        | 1         | 2.38%   |
| Hitachi HTS722080K9A300 80GB         | 1         | 2.38%   |
| Hitachi HTS722012K9A300 120GB        | 1         | 2.38%   |
| Hitachi HTS545050B9A300 500GB        | 1         | 2.38%   |
| HGST HTS721010A9E630 1TB             | 1         | 2.38%   |
| HGST HTS545025A7E380 250GB           | 1         | 2.38%   |
| GOODRAM SSDPR-CX300-240 240GB        | 1         | 2.38%   |
| Crucial CT250MX500SSD1 250GB         | 1         | 2.38%   |
| A-DATA SU750 256GB SSD               | 1         | 2.38%   |
| A-DATA SU630 480GB SSD               | 1         | 2.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 30.77%  |
| WDC                 | 7         | 7      | 26.92%  |
| Toshiba             | 5         | 5      | 19.23%  |
| Hitachi             | 3         | 4      | 11.54%  |
| HGST                | 2         | 3      | 7.69%   |
| Samsung Electronics | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 3         | 3      | 23.08%  |
| Samsung Electronics | 2         | 2      | 15.38%  |
| LITEONIT            | 2         | 2      | 15.38%  |
| A-DATA Technology   | 2         | 2      | 15.38%  |
| WDC                 | 1         | 2      | 7.69%   |
| SanDisk             | 1         | 1      | 7.69%   |
| GOODRAM             | 1         | 1      | 7.69%   |
| Crucial             | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 28     | 60.98%  |
| SSD  | 13        | 14     | 31.71%  |
| NVMe | 2         | 3      | 4.88%   |
| MMC  | 1         | 1      | 2.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 42     | 92.5%   |
| NVMe | 2         | 3      | 5%      |
| MMC  | 1         | 1      | 2.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 36     | 86.84%  |
| 0.51-1.0   | 5         | 6      | 13.16%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 16        | 42.11%  |
| 251-500    | 12        | 31.58%  |
| 501-1000   | 3         | 7.89%   |
| 21-50      | 2         | 5.26%   |
| 1001-2000  | 2         | 5.26%   |
| 51-100     | 2         | 5.26%   |
| 1-20       | 1         | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 20        | 52.63%  |
| 21-50    | 13        | 34.21%  |
| 501-1000 | 2         | 5.26%   |
| 251-500  | 1         | 2.63%   |
| 101-250  | 1         | 2.63%   |
| 51-100   | 1         | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 50%     |
| Hitachi HTS722012K9A300 120GB   | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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
| Detected | 34        | 41     | 87.18%  |
| Works    | 3         | 3      | 7.69%   |
| Malfunc  | 2         | 2      | 5.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 28        | 71.79%  |
| AMD                              | 7         | 17.95%  |
| Silicon Integrated Systems [SiS] | 2         | 5.13%   |
| Kingston Technology Company      | 1         | 2.56%   |
| ADATA Technology                 | 1         | 2.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 10.2%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 8.16%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 8.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 6.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 6.12%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 4.08%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 4.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 4.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 4.08%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 4.08%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 4.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 4.08%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 2         | 4.08%   |
| AMD SB600 IDE                                                                  | 2         | 4.08%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 2.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.04%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 2.04%   |
| AMD FCH SATA Controller [IDE mode]                                             | 1         | 2.04%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 2.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 32        | 71.11%  |
| IDE  | 9         | 20%     |
| RAID | 2         | 4.44%   |
| NVMe | 2         | 4.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 30        | 81.08%  |
| AMD    | 7         | 18.92%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| AMD A4-5000 APU with Radeon HD Graphics        | 3         | 8.11%   |
| Intel Core i3 CPU M 370 @ 2.40GHz              | 2         | 5.41%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 1         | 2.7%    |
| Intel Pentium Dual CPU T3200 @ 2.00GHz         | 1         | 2.7%    |
| Intel Pentium Dual CPU T2390 @ 1.86GHz         | 1         | 2.7%    |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 1         | 2.7%    |
| Intel Pentium CPU B960 @ 2.20GHz               | 1         | 2.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz              | 1         | 2.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz              | 1         | 2.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 1         | 2.7%    |
| Intel Core i7-5600U CPU @ 2.60GHz              | 1         | 2.7%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz             | 1         | 2.7%    |
| Intel Core i7-4600U CPU @ 2.10GHz              | 1         | 2.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz              | 1         | 2.7%    |
| Intel Core i5-3437U CPU @ 1.90GHz              | 1         | 2.7%    |
| Intel Core i5-3337U CPU @ 1.80GHz              | 1         | 2.7%    |
| Intel Core i5-3230M CPU @ 2.60GHz              | 1         | 2.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz              | 1         | 2.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz              | 1         | 2.7%    |
| Intel Core i5-2410M CPU @ 2.30GHz              | 1         | 2.7%    |
| Intel Core i5-10300H CPU @ 2.50GHz             | 1         | 2.7%    |
| Intel Core i3-7020U CPU @ 2.30GHz              | 1         | 2.7%    |
| Intel Core i3-3227U CPU @ 1.90GHz              | 1         | 2.7%    |
| Intel Core i3-3217U CPU @ 1.80GHz              | 1         | 2.7%    |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz           | 1         | 2.7%    |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz           | 1         | 2.7%    |
| Intel Celeron N4000 CPU @ 1.10GHz              | 1         | 2.7%    |
| Intel Celeron D CPU 220 @ 1.20GHz              | 1         | 2.7%    |
| Intel Celeron CPU N2940 @ 1.83GHz              | 1         | 2.7%    |
| Intel Atom CPU N450 @ 1.66GHz                  | 1         | 2.7%    |
| AMD Turion 64 X2 Mobile Technology TL-56       | 1         | 2.7%    |
| AMD Athlon 64 X2 Dual-Core Processor TK-55     | 1         | 2.7%    |
| AMD A6-3420M APU with Radeon HD Graphics       | 1         | 2.7%    |
| AMD A10-7300 Radeon R6, 10 Compute Cores 4C+6G | 1         | 2.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 8         | 21.62%  |
| Intel Core i7           | 6         | 16.22%  |
| Intel Core i3           | 5         | 13.51%  |
| Intel Pentium Dual      | 3         | 8.11%   |
| AMD A4                  | 3         | 8.11%   |
| Intel Core 2 Duo        | 2         | 5.41%   |
| Intel Celeron           | 2         | 5.41%   |
| Intel Pentium Dual-Core | 1         | 2.7%    |
| Intel Pentium           | 1         | 2.7%    |
| Intel Celeron D         | 1         | 2.7%    |
| Intel Atom              | 1         | 2.7%    |
| AMD Turion 64 X2 Mobile | 1         | 2.7%    |
| AMD Athlon 64 X2        | 1         | 2.7%    |
| AMD A6                  | 1         | 2.7%    |
| AMD A10                 | 1         | 2.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 25        | 67.57%  |
| 4      | 9         | 24.32%  |
| 1      | 3         | 8.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 19        | 51.35%  |
| 1      | 18        | 48.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 37        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 6         | 16.22%  |
| Unknown    | 5         | 13.51%  |
| 0x6fd      | 4         | 10.81%  |
| 0x806e9    | 3         | 8.11%   |
| 0x206a7    | 3         | 8.11%   |
| 0x20655    | 2         | 5.41%   |
| 0x0700010f | 2         | 5.41%   |
| 0xa0652    | 1         | 2.7%    |
| 0x806ea    | 1         | 2.7%    |
| 0x706a1    | 1         | 2.7%    |
| 0x506e3    | 1         | 2.7%    |
| 0x40651    | 1         | 2.7%    |
| 0x306d4    | 1         | 2.7%    |
| 0x30678    | 1         | 2.7%    |
| 0x1067a    | 1         | 2.7%    |
| 0x10661    | 1         | 2.7%    |
| 0x07000106 | 1         | 2.7%    |
| 0x06003106 | 1         | 2.7%    |
| 0x03000027 | 1         | 2.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 6         | 16.22%  |
| Core          | 5         | 13.51%  |
| KabyLake      | 4         | 10.81%  |
| SandyBridge   | 3         | 8.11%   |
| Jaguar        | 3         | 8.11%   |
| Westmere      | 2         | 5.41%   |
| Penryn        | 2         | 5.41%   |
| K8 Hammer     | 2         | 5.41%   |
| Haswell       | 2         | 5.41%   |
| Steamroller   | 1         | 2.7%    |
| Skylake       | 1         | 2.7%    |
| Silvermont    | 1         | 2.7%    |
| K10 Llano     | 1         | 2.7%    |
| Goldmont plus | 1         | 2.7%    |
| CometLake     | 1         | 2.7%    |
| Broadwell     | 1         | 2.7%    |
| Bonnell       | 1         | 2.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 27        | 61.36%  |
| AMD                              | 8         | 18.18%  |
| Nvidia                           | 7         | 15.91%  |
| Silicon Integrated Systems [SiS] | 2         | 4.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 12.77%  |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 3         | 6.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 3         | 6.38%   |
| Intel HD Graphics 620                                                     | 3         | 6.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 6.38%   |
| AMD Kabini [Radeon HD 8330]                                               | 3         | 6.38%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 2         | 4.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 4.26%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                   | 2         | 4.26%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 2.13%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 2.13%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 2.13%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 2.13%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 2.13%   |
| Nvidia GF119M [NVS 4200M]                                                 | 1         | 2.13%   |
| Nvidia G84M [GeForce 8600M GT]                                            | 1         | 2.13%   |
| Intel UHD Graphics 620                                                    | 1         | 2.13%   |
| Intel HD Graphics 5500                                                    | 1         | 2.13%   |
| Intel HD Graphics 530                                                     | 1         | 2.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 2.13%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 2.13%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 2.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 2.13%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1         | 2.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 2.13%   |
| AMD Sumo [Radeon HD 6520G]                                                | 1         | 2.13%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                              | 1         | 2.13%   |
| AMD Kaveri [Radeon R6 Graphics]                                           | 1         | 2.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 56.76%  |
| 1 x AMD        | 8         | 21.62%  |
| Intel + Nvidia | 6         | 16.22%  |
| 1 x SiS        | 2         | 5.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 33        | 89.19%  |
| Unknown     | 3         | 8.11%   |
| Proprietary | 1         | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 68.42%  |
| 0.01-0.5   | 6         | 15.79%  |
| 1.01-2.0   | 2         | 5.26%   |
| 0.51-1.0   | 2         | 5.26%   |
| 5.01-6.0   | 1         | 2.63%   |
| 3.01-4.0   | 1         | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 10        | 28.57%  |
| LG Display              | 8         | 22.86%  |
| Chimei Innolux          | 6         | 17.14%  |
| Samsung Electronics     | 5         | 14.29%  |
| BOE                     | 2         | 5.71%   |
| LG Philips              | 1         | 2.86%   |
| CPT                     | 1         | 2.86%   |
| Chi Mei Optoelectronics | 1         | 2.86%   |
| Ancor Communications    | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 5.71%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 5.71%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 5.71%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 5.71%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch     | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 1         | 2.86%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 2.86%   |
| LG Display LCD Monitor LGD03B7 1366x768 309x174mm 14.0-inch              | 1         | 2.86%   |
| LG Display LCD Monitor LGD03B3 1366x768 309x174mm 14.0-inch              | 1         | 2.86%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch              | 1         | 2.86%   |
| LG Display LCD Monitor LGD0251 1366x768 310x174mm 14.0-inch              | 1         | 2.86%   |
| CPT LCD Monitor CPT13B1 1280x800 331x207mm 15.4-inch                     | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch          | 1         | 2.86%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 222x125mm 10.0-inch | 1         | 2.86%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 1         | 2.86%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO253C 1366x768 309x173mm 13.9-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO2374 1280x800 331x207mm 15.4-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 1         | 2.86%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch    | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 20        | 57.14%  |
| 1920x1080 (FHD) | 6         | 17.14%  |
| 1280x800 (WXGA) | 6         | 17.14%  |
| 1600x900 (HD+)  | 2         | 5.71%   |
| 1024x600        | 1         | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 21        | 60%     |
| 14     | 8         | 22.86%  |
| 17     | 2         | 5.71%   |
| 13     | 2         | 5.71%   |
| 21     | 1         | 2.86%   |
| 10     | 1         | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 88.57%  |
| 351-400     | 2         | 5.71%   |
| 401-500     | 1         | 2.86%   |
| 201-300     | 1         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 28        | 82.35%  |
| 16/10 | 6         | 17.65%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 60%     |
| 81-90          | 10        | 28.57%  |
| 121-130        | 2         | 5.71%   |
| 41-50          | 1         | 2.86%   |
| 201-250        | 1         | 2.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 21        | 61.76%  |
| 121-160 | 7         | 20.59%  |
| 51-100  | 6         | 17.65%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 34        | 91.89%  |
| 0     | 2         | 5.41%   |
| 2     | 1         | 2.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 22        | 34.38%  |
| Qualcomm Atheros                  | 14        | 21.88%  |
| Intel                             | 10        | 15.63%  |
| Broadcom                          | 8         | 12.5%   |
| Broadcom Limited                  | 3         | 4.69%   |
| Silicon Integrated Systems [SiS]  | 1         | 1.56%   |
| Samsung Electronics               | 1         | 1.56%   |
| Ralink                            | 1         | 1.56%   |
| NetGear                           | 1         | 1.56%   |
| Marvell Technology Group          | 1         | 1.56%   |
| Ericsson Business Mobile Networks | 1         | 1.56%   |
| ASIX Electronics                  | 1         | 1.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 12        | 15.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 11.39%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 5.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 5.06%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 3.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 2         | 2.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.53%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 2.53%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 2.53%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 1.27%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.27%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.27%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.27%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.27%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.27%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.27%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 1.27%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 1.27%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                     | 1         | 1.27%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 1.27%   |
| Intel Wireless 8260                                                     | 1         | 1.27%   |
| Intel Wireless 7265                                                     | 1         | 1.27%   |
| Intel Wireless 7260                                                     | 1         | 1.27%   |
| Intel Wireless 3165                                                     | 1         | 1.27%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.27%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.27%   |
| Intel 82579V Gigabit Network Connection                                 | 1         | 1.27%   |
| Ericsson Business Mobile Networks N5321 gw                              | 1         | 1.27%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 1         | 1.27%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 1         | 1.27%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 1         | 1.27%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                  | 1         | 1.27%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 1.27%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.27%   |
| Broadcom BCM4401-B0 100Base-TX                                          | 1         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.27%   |
| ASIX AX88179 Gigabit Ethernet                                           | 1         | 1.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 14        | 35.9%   |
| Intel                 | 10        | 25.64%  |
| Broadcom              | 6         | 15.38%  |
| Realtek Semiconductor | 5         | 12.82%  |
| Broadcom Limited      | 2         | 5.13%   |
| Ralink                | 1         | 2.56%   |
| NetGear               | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 10.26%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 10.26%  |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 7.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 5.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 5.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 5.13%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 5.13%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 5.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.56%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 2.56%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 2.56%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 2.56%   |
| Realtek 802.11ac NIC                                                    | 1         | 2.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.56%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                     | 1         | 2.56%   |
| Intel Wireless 8260                                                     | 1         | 2.56%   |
| Intel Wireless 7265                                                     | 1         | 2.56%   |
| Intel Wireless 7260                                                     | 1         | 2.56%   |
| Intel Wireless 3165                                                     | 1         | 2.56%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 2.56%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 2.56%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.56%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 2.56%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2.56%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 21        | 53.85%  |
| Intel                            | 5         | 12.82%  |
| Qualcomm Atheros                 | 4         | 10.26%  |
| Broadcom                         | 4         | 10.26%  |
| Silicon Integrated Systems [SiS] | 1         | 2.56%   |
| Samsung Electronics              | 1         | 2.56%   |
| Marvell Technology Group         | 1         | 2.56%   |
| Broadcom Limited                 | 1         | 2.56%   |
| ASIX Electronics                 | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 30.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 23.08%  |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 5.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.13%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.56%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.56%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 2.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.56%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 2.56%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 2.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 49.33%  |
| Ethernet | 37        | 49.33%  |
| Modem    | 1         | 1.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 57.14%  |
| Ethernet | 21        | 42.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 36        | 97.3%   |
| 1     | 1         | 2.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 89.19%  |
| Yes  | 4         | 10.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 27.27%  |
| Qualcomm Atheros Communications | 5         | 22.73%  |
| Lite-On Technology              | 3         | 13.64%  |
| Realtek Semiconductor           | 2         | 9.09%   |
| Hewlett-Packard                 | 2         | 9.09%   |
| Cambridge Silicon Radio         | 2         | 9.09%   |
| Ralink Technology               | 1         | 4.55%   |
| Foxconn / Hon Hai               | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 3         | 13.64%  |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 9.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 9.09%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 9.09%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 9.09%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                | 1         | 4.55%   |
| Qualcomm Atheros  Bluetooth Device                          | 1         | 4.55%   |
| Qualcomm Atheros Bluetooth USB Host Controller              | 1         | 4.55%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 4.55%   |
| Lite-On Bluetooth Device                                    | 1         | 4.55%   |
| Intel Bluetooth Device                                      | 1         | 4.55%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 4.55%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 4.55%   |
| Foxconn / Hon Hai BCM20702A0                                | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 28        | 68.29%  |
| AMD                              | 8         | 19.51%  |
| Nvidia                           | 3         | 7.32%   |
| Silicon Integrated Systems [SiS] | 2         | 4.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 14.29%  |
| AMD FCH Azalia Controller                                                  | 5         | 10.2%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 8.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 6.12%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 6.12%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 4.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 4.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 4.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 4.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.04%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 2.04%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.04%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.04%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.04%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.04%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 2.04%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 2.04%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 2         | 33.33%  |
| Unknown             | 1         | 16.67%  |
| Smart               | 1         | 16.67%  |
| Samsung Electronics | 1         | 16.67%  |
| Kingston            | 1         | 16.67%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM SDRAM                       | 1         | 16.67%  |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s     | 1         | 16.67%  |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 1         | 16.67%  |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s | 1         | 16.67%  |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s      | 1         | 16.67%  |
| Kingston RAM 9905428-026.A00LF 2GB SODIMM DDR3 1066MT/s   | 1         | 16.67%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 2         | 40%     |
| SDRAM  | 1         | 20%     |
| LPDDR4 | 1         | 20%     |
| DDR4   | 1         | 20%     |

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


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 3         | 50%     |
| 2048 | 2         | 33.33%  |
| 8192 | 1         | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 1         | 20%     |
| 2133    | 1         | 20%     |
| 1600    | 1         | 20%     |
| 1066    | 1         | 20%     |
| Unknown | 1         | 20%     |

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
| Chicony Electronics                    | 6         | 20.69%  |
| Suyin                                  | 5         | 17.24%  |
| Realtek Semiconductor                  | 4         | 13.79%  |
| IMC Networks                           | 3         | 10.34%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 10.34%  |
| Silicon Motion                         | 2         | 6.9%    |
| Microdia                               | 2         | 6.9%    |
| Syntek                                 | 1         | 3.45%   |
| Ricoh                                  | 1         | 3.45%   |
| Quanta                                 | 1         | 3.45%   |
| Lite-On Technology                     | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                           | 2         | 6.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 6.9%    |
| Syntek Lenovo EasyCamera                                    | 1         | 3.45%   |
| Suyin HP Webcam-50                                          | 1         | 3.45%   |
| Suyin HP Webcam-101                                         | 1         | 3.45%   |
| Suyin HP Integrated Webcam                                  | 1         | 3.45%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 3.45%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 3.45%   |
| Silicon Motion WebCam SCB-1100N                             | 1         | 3.45%   |
| Silicon Motion Web Camera                                   | 1         | 3.45%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 3.45%   |
| Realtek Lenovo EasyCamera                                   | 1         | 3.45%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 3.45%   |
| Realtek Integrated_Webcam_HD                                | 1         | 3.45%   |
| Realtek Acer 640 x 480 laptop camera                        | 1         | 3.45%   |
| Quanta HD WebCam                                            | 1         | 3.45%   |
| Microdia USB 2.0 Camera                                     | 1         | 3.45%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 3.45%   |
| Lite-On Integrated Camera                                   | 1         | 3.45%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 1         | 3.45%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 3.45%   |
| IMC Networks Integrated Webcam                              | 1         | 3.45%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 3.45%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 3.45%   |
| Chicony Integrated Camera                                   | 1         | 3.45%   |
| Chicony HP TrueVision HD Camera                             | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS491                      | 1         | 50%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 25        | 65.79%  |
| 1     | 12        | 31.58%  |
| 2     | 1         | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Net/wireless       | 4         | 28.57%  |
| Graphics card      | 4         | 28.57%  |
| Fingerprint reader | 2         | 14.29%  |
| Chipcard           | 2         | 14.29%  |
| Storage            | 1         | 7.14%   |
| Network            | 1         | 7.14%   |

