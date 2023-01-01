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

Total: 58

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell     | Vostro 1000                 | [d1fae6443d](https://linux-hardware.org/?probe=d1fae6443d) | May 17, 2022 |
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
| Acer     | Aspire E1-731               | [747dbbb54d](https://linux-hardware.org/?probe=747dbbb54d) | Mar 07, 2021 |
| Acer     | Aspire E1-731               | [1b82018148](https://linux-hardware.org/?probe=1b82018148) | Mar 02, 2021 |
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
| Acer     | Makalu                      | [1519ec67b5](https://linux-hardware.org/?probe=1519ec67b5) | Sep 07, 2020 |
| Acer     | Makalu                      | [51b6611d94](https://linux-hardware.org/?probe=51b6611d94) | Sep 06, 2020 |
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
| 5.4.0-72-generic            | 6         | 15.38%  |
| 5.6.15-windowsfx-10-generic | 5         | 12.82%  |
| 5.4.0-52-generic            | 4         | 10.26%  |
| 5.7.15-050715-generic       | 3         | 7.69%   |
| 5.4.0-73-generic            | 3         | 7.69%   |
| 5.4.0-65-generic            | 3         | 7.69%   |
| 5.4.0-42-generic            | 3         | 7.69%   |
| 5.4.0-29-generic            | 3         | 7.69%   |
| 5.7.8-windowsfx-generic     | 2         | 5.13%   |
| 5.5.19-050519-generic       | 2         | 5.13%   |
| 5.4.0-90-generic            | 1         | 2.56%   |
| 5.4.0-67-generic            | 1         | 2.56%   |
| 5.4.0-66-generic            | 1         | 2.56%   |
| 5.4.0-54-generic            | 1         | 2.56%   |
| 5.10.2-051002-generic       | 1         | 2.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 26        | 66.67%  |
| 5.6.15  | 5         | 12.82%  |
| 5.7.15  | 3         | 7.69%   |
| 5.7.8   | 2         | 5.13%   |
| 5.5.19  | 2         | 5.13%   |
| 5.10.2  | 1         | 2.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 26        | 66.67%  |
| 5.7     | 5         | 12.82%  |
| 5.6     | 5         | 12.82%  |
| 5.5     | 2         | 5.13%   |
| 5.10    | 1         | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 39        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 32        | 82.05%  |
| KDE        | 3         | 7.69%   |
| Cinnamon   | 3         | 7.69%   |
| Unknown    | 1         | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 39        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 22        | 56.41%  |
| SDDM    | 10        | 25.64%  |
| TDM     | 7         | 17.95%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| pt_BR | 13        | 33.33%  |
| en_US | 5         | 12.82%  |
| pl_PL | 3         | 7.69%   |
| it_IT | 3         | 7.69%   |
| fr_FR | 2         | 5.13%   |
| es_ES | 2         | 5.13%   |
| es_AR | 2         | 5.13%   |
| en_AU | 2         | 5.13%   |
| ro_RO | 1         | 2.56%   |
| es_MX | 1         | 2.56%   |
| es_CL | 1         | 2.56%   |
| en_ZA | 1         | 2.56%   |
| en_CA | 1         | 2.56%   |
| de_DE | 1         | 2.56%   |
| C     | 1         | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 27        | 69.23%  |
| EFI  | 12        | 30.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 39        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 35        | 89.74%  |
| MBR     | 2         | 5.13%   |
| GPT     | 2         | 5.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 89.74%  |
| Yes       | 4         | 10.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 82.05%  |
| Yes       | 7         | 17.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 9         | 23.08%  |
| Hewlett-Packard     | 8         | 20.51%  |
| Acer                | 6         | 15.38%  |
| Lenovo              | 5         | 12.82%  |
| ASUSTek Computer    | 3         | 7.69%   |
| Samsung Electronics | 2         | 5.13%   |
| Toshiba             | 1         | 2.56%   |
| Positivo            | 1         | 2.56%   |
| Pegatron            | 1         | 2.56%   |
| Olivetti            | 1         | 2.56%   |
| Medion              | 1         | 2.56%   |
| Gigabyte Technology | 1         | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Vostro 1000                         | 2         | 5.13%   |
| Toshiba Satellite C50D-A-12R             | 1         | 2.56%   |
| Samsung 340XAA/350XAA/550XAA             | 1         | 2.56%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 2.56%   |
| Positivo Mobile                          | 1         | 2.56%   |
| Pegatron B34C                            | 1         | 2.56%   |
| Olivetti P55-AEU-323-4G320               | 1         | 2.56%   |
| Medion S4216                             | 1         | 2.56%   |
| Lenovo Y70-70 Touch 80DU                 | 1         | 2.56%   |
| Lenovo ThinkPad X1 Carbon 2nd F2G3H4J    | 1         | 2.56%   |
| Lenovo ThinkPad T450s 20BWS0YF00         | 1         | 2.56%   |
| Lenovo G550 2958                         | 1         | 2.56%   |
| Lenovo G505 20240                        | 1         | 2.56%   |
| HP ProBook 6560b                         | 1         | 2.56%   |
| HP Pavilion dv6700                       | 1         | 2.56%   |
| HP Mini 210-1000                         | 1         | 2.56%   |
| HP G42                                   | 1         | 2.56%   |
| HP EliteBook Folio 9470m                 | 1         | 2.56%   |
| HP Compaq Presario CQ50                  | 1         | 2.56%   |
| HP 250 G7 Notebook PC                    | 1         | 2.56%   |
| HP 250 G6 Notebook PC                    | 1         | 2.56%   |
| Gigabyte P57V6                           | 1         | 2.56%   |
| Dell Latitude E6420                      | 1         | 2.56%   |
| Dell Inspiron 5423                       | 1         | 2.56%   |
| Dell Inspiron 3520                       | 1         | 2.56%   |
| Dell Inspiron 3421                       | 1         | 2.56%   |
| Dell Inspiron 1525                       | 1         | 2.56%   |
| Dell Inspiron 1501                       | 1         | 2.56%   |
| Dell Inspiron 15-3567                    | 1         | 2.56%   |
| ASUS K72Jr                               | 1         | 2.56%   |
| ASUS K50C                                | 1         | 2.56%   |
| ASUS ASUS TUF Gaming F15 FX506LI_FX506LI | 1         | 2.56%   |
| Acer Aspire ES1-512                      | 1         | 2.56%   |
| Acer Aspire E5-551                       | 1         | 2.56%   |
| Acer Aspire E1-731                       | 1         | 2.56%   |
| Acer Aspire E1-531                       | 1         | 2.56%   |
| Acer Aspire A515-51G                     | 1         | 2.56%   |
| Acer Aspire 5720Z                        | 1         | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Inspiron              | 6         | 15.38%  |
| Acer Aspire                | 6         | 15.38%  |
| Lenovo ThinkPad            | 2         | 5.13%   |
| HP 250                     | 2         | 5.13%   |
| Dell Vostro                | 2         | 5.13%   |
| Toshiba Satellite          | 1         | 2.56%   |
| Samsung 340XAA             | 1         | 2.56%   |
| Samsung 305E4A             | 1         | 2.56%   |
| Positivo Mobile            | 1         | 2.56%   |
| Pegatron B34C              | 1         | 2.56%   |
| Olivetti P55-AEU-323-4G320 | 1         | 2.56%   |
| Medion S4216               | 1         | 2.56%   |
| Lenovo Y70-70              | 1         | 2.56%   |
| Lenovo G550                | 1         | 2.56%   |
| Lenovo G505                | 1         | 2.56%   |
| HP ProBook                 | 1         | 2.56%   |
| HP Pavilion                | 1         | 2.56%   |
| HP Mini                    | 1         | 2.56%   |
| HP G42                     | 1         | 2.56%   |
| HP EliteBook               | 1         | 2.56%   |
| HP Compaq                  | 1         | 2.56%   |
| Gigabyte P57V6             | 1         | 2.56%   |
| Dell Latitude              | 1         | 2.56%   |
| ASUS K72Jr                 | 1         | 2.56%   |
| ASUS K50C                  | 1         | 2.56%   |
| ASUS ASUS                  | 1         | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 6         | 15.38%  |
| 2014    | 5         | 12.82%  |
| 2013    | 4         | 10.26%  |
| 2009    | 4         | 10.26%  |
| 2018    | 3         | 7.69%   |
| 2011    | 3         | 7.69%   |
| 2006    | 3         | 7.69%   |
| 2017    | 2         | 5.13%   |
| 2008    | 2         | 5.13%   |
| 2007    | 2         | 5.13%   |
| 2020    | 1         | 2.56%   |
| 2016    | 1         | 2.56%   |
| 2015    | 1         | 2.56%   |
| 2010    | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 39        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 38        | 95%     |
| Enabled  | 2         | 5%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 17        | 43.59%  |
| 4.01-8.0   | 12        | 30.77%  |
| 2.01-3.0   | 3         | 7.69%   |
| 16.01-24.0 | 3         | 7.69%   |
| 1.01-2.0   | 2         | 5.13%   |
| 8.01-16.0  | 2         | 5.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 25        | 62.5%   |
| 3.01-4.0 | 7         | 17.5%   |
| 2.01-3.0 | 5         | 12.5%   |
| 4.01-8.0 | 2         | 5%      |
| 0.51-1.0 | 1         | 2.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 34        | 87.18%  |
| 2      | 4         | 10.26%  |
| 3      | 1         | 2.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 71.79%  |
| No        | 11        | 28.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 53.85%  |
| No        | 18        | 46.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Brazil       | 13        | 33.33%  |
| USA          | 4         | 10.26%  |
| Poland       | 3         | 7.69%   |
| Italy        | 3         | 7.69%   |
| Spain        | 2         | 5.13%   |
| Canada       | 2         | 5.13%   |
| Australia    | 2         | 5.13%   |
| Argentina    | 2         | 5.13%   |
| South Africa | 1         | 2.56%   |
| Russia       | 1         | 2.56%   |
| Romania      | 1         | 2.56%   |
| Mexico       | 1         | 2.56%   |
| Germany      | 1         | 2.56%   |
| France       | 1         | 2.56%   |
| Chile        | 1         | 2.56%   |
| Cameroon     | 1         | 2.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Zacatecas City             | 1         | 2.5%    |
| Winston-Salem              | 1         | 2.5%    |
| Warsaw                     | 1         | 2.5%    |
| Vila Velha                 | 1         | 2.5%    |
| Val-d'Or                   | 1         | 2.5%    |
| Sydney                     | 1         | 2.5%    |
| Savona                     | 1         | 2.5%    |
| Sao Paulo                  | 1         | 2.5%    |
| Santa Quiteria do Maranhao | 1         | 2.5%    |
| Salerno                    | 1         | 2.5%    |
| Rosario                    | 1         | 2.5%    |
| Recife                     | 1         | 2.5%    |
| Porto Alegre               | 1         | 2.5%    |
| Piraquara                  | 1         | 2.5%    |
| Moscow Oblast              | 1         | 2.5%    |
| Massy                      | 1         | 2.5%    |
| Madrid                     | 1         | 2.5%    |
| Londrina                   | 1         | 2.5%    |
| Lipova                     | 1         | 2.5%    |
| Krakow                     | 1         | 2.5%    |
| Katowice                   | 1         | 2.5%    |
| Johannesburg               | 1         | 2.5%    |
| Itatiba                    | 1         | 2.5%    |
| Hobart                     | 1         | 2.5%    |
| Grand Falls                | 1         | 2.5%    |
| Eureka                     | 1         | 2.5%    |
| Embu                       | 1         | 2.5%    |
| East Stroudsburg           | 1         | 2.5%    |
| Curitiba                   | 1         | 2.5%    |
| Cincinnati                 | 1         | 2.5%    |
| Central                    | 1         | 2.5%    |
| Carbonia                   | 1         | 2.5%    |
| Cabo Frio                  | 1         | 2.5%    |
| Bueu                       | 1         | 2.5%    |
| Bonabeerie                 | 1         | 2.5%    |
| Belo Horizonte             | 1         | 2.5%    |
| Bella Vista                | 1         | 2.5%    |
| Belém                     | 1         | 2.5%    |
| Barcelona                  | 1         | 2.5%    |
| Augsburg                   | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 20.45%  |
| WDC                 | 8         | 9      | 18.18%  |
| Toshiba             | 5         | 5      | 11.36%  |
| Kingston            | 5         | 5      | 11.36%  |
| Samsung Electronics | 3         | 3      | 6.82%   |
| Hitachi             | 3         | 4      | 6.82%   |
| Unknown             | 2         | 3      | 4.55%   |
| LITEONIT            | 2         | 2      | 4.55%   |
| HGST                | 2         | 3      | 4.55%   |
| A-DATA Technology   | 2         | 2      | 4.55%   |
| SanDisk             | 1         | 1      | 2.27%   |
| GOODRAM             | 1         | 1      | 2.27%   |
| Crucial             | 1         | 1      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                 | 2         | 4.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 4.55%   |
| WDC WD5000LPVX-22V0TT0 500GB             | 1         | 2.27%   |
| WDC WD5000LPVT-24G33T1 500GB             | 1         | 2.27%   |
| WDC WD3200BPVT-22JJ5T0 320GB             | 1         | 2.27%   |
| WDC WD3200BEVT-80A0RT0 320GB             | 1         | 2.27%   |
| WDC WD1200BEVS-75UST0 120GB              | 1         | 2.27%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 2.27%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 2.27%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB SSD | 1         | 2.27%   |
| Unknown NVMe SSD Drive 512GB             | 1         | 2.27%   |
| Unknown MMC Card  8GB                    | 1         | 2.27%   |
| Toshiba MQ01ABF032 320GB                 | 1         | 2.27%   |
| Toshiba MK5059GSXP 500GB                 | 1         | 2.27%   |
| Toshiba MK2561GSYN 250GB                 | 1         | 2.27%   |
| Seagate ST9320325AS 320GB                | 1         | 2.27%   |
| Seagate ST9160827AS 160GB                | 1         | 2.27%   |
| Seagate ST9160821AS 160GB                | 1         | 2.27%   |
| Seagate ST9160314AS 160GB                | 1         | 2.27%   |
| Seagate ST500LT012-9WS142 500GB          | 1         | 2.27%   |
| Seagate ST500LM021-1KJ152 500GB          | 1         | 2.27%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 2.27%   |
| SanDisk SSD PLUS 1000GB                  | 1         | 2.27%   |
| Samsung SSD 850 EVO 250GB                | 1         | 2.27%   |
| Samsung MZMPC032HBCD-000D1 32GB SSD      | 1         | 2.27%   |
| Samsung HM321HI 320GB                    | 1         | 2.27%   |
| LITEONIT LMT-256M6M-HP 256GB SSD         | 1         | 2.27%   |
| LITEONIT LGT-256M6G 256GB SSD            | 1         | 2.27%   |
| Kingston SV300S37A120G 120GB SSD         | 1         | 2.27%   |
| Kingston SUV400S37120G 120GB SSD         | 1         | 2.27%   |
| Kingston SA400S37240G 240GB SSD          | 1         | 2.27%   |
| Kingston SA400S37120G 120GB SSD          | 1         | 2.27%   |
| Kingston NVMe SSD Drive 512GB            | 1         | 2.27%   |
| Hitachi HTS722080K9A300 80GB             | 1         | 2.27%   |
| Hitachi HTS722012K9A300 120GB            | 1         | 2.27%   |
| Hitachi HTS545050B9A300 500GB            | 1         | 2.27%   |
| HGST HTS721010A9E630 1TB                 | 1         | 2.27%   |
| HGST HTS545025A7E380 250GB               | 1         | 2.27%   |
| GOODRAM SSDPR-CX300-240 240GB            | 1         | 2.27%   |
| Crucial CT250MX500SSD1 250GB             | 1         | 2.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 33.33%  |
| WDC                 | 7         | 7      | 25.93%  |
| Toshiba             | 5         | 5      | 18.52%  |
| Hitachi             | 3         | 4      | 11.11%  |
| HGST                | 2         | 3      | 7.41%   |
| Samsung Electronics | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 4      | 28.57%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| LITEONIT            | 2         | 2      | 14.29%  |
| A-DATA Technology   | 2         | 2      | 14.29%  |
| WDC                 | 1         | 2      | 7.14%   |
| SanDisk             | 1         | 1      | 7.14%   |
| GOODRAM             | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 29     | 60.47%  |
| SSD  | 14        | 15     | 32.56%  |
| NVMe | 2         | 3      | 4.65%   |
| MMC  | 1         | 1      | 2.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 44     | 92.86%  |
| NVMe | 2         | 3      | 4.76%   |
| MMC  | 1         | 1      | 2.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 38     | 87.5%   |
| 0.51-1.0   | 5         | 6      | 12.5%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 18        | 45%     |
| 251-500    | 12        | 30%     |
| 501-1000   | 3         | 7.5%    |
| 21-50      | 2         | 5%      |
| 1001-2000  | 2         | 5%      |
| 51-100     | 2         | 5%      |
| 1-20       | 1         | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 21        | 52.5%   |
| 21-50    | 14        | 35%     |
| 501-1000 | 2         | 5%      |
| 251-500  | 1         | 2.5%    |
| 101-250  | 1         | 2.5%    |
| 51-100   | 1         | 2.5%    |

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
| Detected | 36        | 43     | 87.8%   |
| Works    | 3         | 3      | 7.32%   |
| Malfunc  | 2         | 2      | 4.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 29        | 70.73%  |
| AMD                              | 8         | 19.51%  |
| Silicon Integrated Systems [SiS] | 2         | 4.88%   |
| Kingston Technology Company      | 1         | 2.44%   |
| ADATA Technology                 | 1         | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 11.54%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 7.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 5.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 5.77%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 3         | 5.77%   |
| AMD SB600 IDE                                                                  | 3         | 5.77%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 3.85%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 3.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.85%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 3.85%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 3.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 3.85%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.92%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.92%   |
| AMD FCH SATA Controller [IDE mode]                                             | 1         | 1.92%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 34        | 70.83%  |
| IDE  | 10        | 20.83%  |
| RAID | 2         | 4.17%   |
| NVMe | 2         | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 31        | 79.49%  |
| AMD    | 8         | 20.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| AMD A4-5000 APU with Radeon HD Graphics        | 3         | 7.69%   |
| Intel Core i3 CPU M 370 @ 2.40GHz              | 2         | 5.13%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 1         | 2.56%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz         | 1         | 2.56%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz         | 1         | 2.56%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 1         | 2.56%   |
| Intel Pentium CPU B960 @ 2.20GHz               | 1         | 2.56%   |
| Intel Pentium CPU 2020M @ 2.40GHz              | 1         | 2.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 1         | 2.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 1         | 2.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 1         | 2.56%   |
| Intel Core i7-5600U CPU @ 2.60GHz              | 1         | 2.56%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz             | 1         | 2.56%   |
| Intel Core i7-4600U CPU @ 2.10GHz              | 1         | 2.56%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 1         | 2.56%   |
| Intel Core i5-3437U CPU @ 1.90GHz              | 1         | 2.56%   |
| Intel Core i5-3337U CPU @ 1.80GHz              | 1         | 2.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 1         | 2.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 1         | 2.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 1         | 2.56%   |
| Intel Core i5-2410M CPU @ 2.30GHz              | 1         | 2.56%   |
| Intel Core i5-10300H CPU @ 2.50GHz             | 1         | 2.56%   |
| Intel Core i3-7020U CPU @ 2.30GHz              | 1         | 2.56%   |
| Intel Core i3-3227U CPU @ 1.90GHz              | 1         | 2.56%   |
| Intel Core i3-3217U CPU @ 1.80GHz              | 1         | 2.56%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz           | 1         | 2.56%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz           | 1         | 2.56%   |
| Intel Celeron N4000 CPU @ 1.10GHz              | 1         | 2.56%   |
| Intel Celeron D CPU 220 @ 1.20GHz              | 1         | 2.56%   |
| Intel Celeron CPU N2940 @ 1.83GHz              | 1         | 2.56%   |
| Intel Atom CPU N450 @ 1.66GHz                  | 1         | 2.56%   |
| AMD Turion 64 X2 Mobile Technology TL-60       | 1         | 2.56%   |
| AMD Turion 64 X2 Mobile Technology TL-56       | 1         | 2.56%   |
| AMD Athlon 64 X2 Dual-Core Processor TK-55     | 1         | 2.56%   |
| AMD A6-3420M APU with Radeon HD Graphics       | 1         | 2.56%   |
| AMD A10-7300 Radeon R6, 10 Compute Cores 4C+6G | 1         | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 8         | 20.51%  |
| Intel Core i7           | 6         | 15.38%  |
| Intel Core i3           | 5         | 12.82%  |
| Intel Pentium Dual      | 3         | 7.69%   |
| AMD A4                  | 3         | 7.69%   |
| Intel Pentium           | 2         | 5.13%   |
| Intel Core 2 Duo        | 2         | 5.13%   |
| Intel Celeron           | 2         | 5.13%   |
| AMD Turion 64 X2 Mobile | 2         | 5.13%   |
| Intel Pentium Dual-Core | 1         | 2.56%   |
| Intel Celeron D         | 1         | 2.56%   |
| Intel Atom              | 1         | 2.56%   |
| AMD Athlon 64 X2        | 1         | 2.56%   |
| AMD A6                  | 1         | 2.56%   |
| AMD A10                 | 1         | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 27        | 69.23%  |
| 4      | 9         | 23.08%  |
| 1      | 3         | 7.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 51.28%  |
| 2      | 19        | 48.72%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 39        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 7         | 17.95%  |
| Unknown    | 6         | 15.38%  |
| 0x6fd      | 4         | 10.26%  |
| 0x806e9    | 3         | 7.69%   |
| 0x206a7    | 3         | 7.69%   |
| 0x20655    | 2         | 5.13%   |
| 0x0700010f | 2         | 5.13%   |
| 0xa0652    | 1         | 2.56%   |
| 0x806ea    | 1         | 2.56%   |
| 0x706a1    | 1         | 2.56%   |
| 0x506e3    | 1         | 2.56%   |
| 0x40651    | 1         | 2.56%   |
| 0x306d4    | 1         | 2.56%   |
| 0x30678    | 1         | 2.56%   |
| 0x1067a    | 1         | 2.56%   |
| 0x10661    | 1         | 2.56%   |
| 0x07000106 | 1         | 2.56%   |
| 0x06003106 | 1         | 2.56%   |
| 0x03000027 | 1         | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 7         | 17.95%  |
| Core          | 5         | 12.82%  |
| KabyLake      | 4         | 10.26%  |
| SandyBridge   | 3         | 7.69%   |
| K8 Hammer     | 3         | 7.69%   |
| Jaguar        | 3         | 7.69%   |
| Westmere      | 2         | 5.13%   |
| Penryn        | 2         | 5.13%   |
| Haswell       | 2         | 5.13%   |
| Steamroller   | 1         | 2.56%   |
| Skylake       | 1         | 2.56%   |
| Silvermont    | 1         | 2.56%   |
| K10 Llano     | 1         | 2.56%   |
| Goldmont plus | 1         | 2.56%   |
| CometLake     | 1         | 2.56%   |
| Broadwell     | 1         | 2.56%   |
| Bonnell       | 1         | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 28        | 60.87%  |
| AMD                              | 9         | 19.57%  |
| Nvidia                           | 7         | 15.22%  |
| Silicon Integrated Systems [SiS] | 2         | 4.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 14.29%  |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 3         | 6.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 3         | 6.12%   |
| Intel HD Graphics 620                                                     | 3         | 6.12%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 6.12%   |
| AMD Kabini [Radeon HD 8330]                                               | 3         | 6.12%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 2         | 4.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 4.08%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                   | 2         | 4.08%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 2.04%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 2.04%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 2.04%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 2.04%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 2.04%   |
| Nvidia GF119M [NVS 4200M]                                                 | 1         | 2.04%   |
| Nvidia G84M [GeForce 8600M GT]                                            | 1         | 2.04%   |
| Intel UHD Graphics 620                                                    | 1         | 2.04%   |
| Intel HD Graphics 5500                                                    | 1         | 2.04%   |
| Intel HD Graphics 530                                                     | 1         | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 2.04%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 2.04%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 2.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 2.04%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1         | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 2.04%   |
| AMD Sumo [Radeon HD 6520G]                                                | 1         | 2.04%   |
| AMD RS482/RS485 [Radeon Xpress 1100/1150]                                 | 1         | 2.04%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                              | 1         | 2.04%   |
| AMD Kaveri [Radeon R6 Graphics]                                           | 1         | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 56.41%  |
| 1 x AMD        | 9         | 23.08%  |
| Intel + Nvidia | 6         | 15.38%  |
| 1 x SiS        | 2         | 5.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 34        | 87.18%  |
| Unknown     | 4         | 10.26%  |
| Proprietary | 1         | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 70%     |
| 0.01-0.5   | 6         | 15%     |
| 1.01-2.0   | 2         | 5%      |
| 0.51-1.0   | 2         | 5%      |
| 5.01-6.0   | 1         | 2.5%    |
| 3.01-4.0   | 1         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 11        | 30.56%  |
| LG Display              | 8         | 22.22%  |
| Chimei Innolux          | 6         | 16.67%  |
| Samsung Electronics     | 5         | 13.89%  |
| BOE                     | 2         | 5.56%   |
| LG Philips              | 1         | 2.78%   |
| CPT                     | 1         | 2.78%   |
| Chi Mei Optoelectronics | 1         | 2.78%   |
| Ancor Communications    | 1         | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 5.56%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 5.56%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 5.56%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 5.56%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch     | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 1         | 2.78%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD03B7 1366x768 309x174mm 14.0-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD03B3 1366x768 310x174mm 14.0-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD0251 1366x768 310x174mm 14.0-inch              | 1         | 2.78%   |
| CPT LCD Monitor CPT13B1 1280x800 331x207mm 15.4-inch                     | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch          | 1         | 2.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 222x125mm 10.0-inch | 1         | 2.78%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 1         | 2.78%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO253C 1366x768 309x173mm 13.9-inch            | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO2374 1280x800 331x207mm 15.4-inch            | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 1         | 2.78%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch    | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 20        | 55.56%  |
| 1920x1080 (FHD) | 6         | 16.67%  |
| 1280x800 (WXGA) | 6         | 16.67%  |
| 1600x900 (HD+)  | 3         | 8.33%   |
| 1024x600        | 1         | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 21        | 58.33%  |
| 14     | 8         | 22.22%  |
| 17     | 3         | 8.33%   |
| 13     | 2         | 5.56%   |
| 21     | 1         | 2.78%   |
| 10     | 1         | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 86.11%  |
| 351-400     | 3         | 8.33%   |
| 401-500     | 1         | 2.78%   |
| 201-300     | 1         | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 29        | 82.86%  |
| 16/10 | 6         | 17.14%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 58.33%  |
| 81-90          | 10        | 27.78%  |
| 121-130        | 3         | 8.33%   |
| 41-50          | 1         | 2.78%   |
| 201-250        | 1         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 22        | 62.86%  |
| 121-160 | 7         | 20%     |
| 51-100  | 6         | 17.14%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 35        | 89.74%  |
| 0     | 3         | 7.69%   |
| 2     | 1         | 2.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 22        | 33.33%  |
| Qualcomm Atheros                  | 15        | 22.73%  |
| Intel                             | 10        | 15.15%  |
| Broadcom                          | 8         | 12.12%  |
| Broadcom Limited                  | 4         | 6.06%   |
| Silicon Integrated Systems [SiS]  | 1         | 1.52%   |
| Samsung Electronics               | 1         | 1.52%   |
| Ralink                            | 1         | 1.52%   |
| NetGear                           | 1         | 1.52%   |
| Marvell Technology Group          | 1         | 1.52%   |
| Ericsson Business Mobile Networks | 1         | 1.52%   |
| ASIX Electronics                  | 1         | 1.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 12        | 14.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 10.84%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 6.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 4.82%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 3.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 2         | 2.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.41%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 2.41%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                  | 2         | 2.41%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 2.41%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 1.2%    |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.2%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.2%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.2%    |
| Realtek 802.11ac NIC                                                    | 1         | 1.2%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.2%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 1.2%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 1.2%    |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                     | 1         | 1.2%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 1.2%    |
| Intel Wireless 8260                                                     | 1         | 1.2%    |
| Intel Wireless 7265                                                     | 1         | 1.2%    |
| Intel Wireless 7260                                                     | 1         | 1.2%    |
| Intel Wireless 3165                                                     | 1         | 1.2%    |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.2%    |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.2%    |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.2%    |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.2%    |
| Intel 82579V Gigabit Network Connection                                 | 1         | 1.2%    |
| Ericsson Business Mobile Networks N5321 gw                              | 1         | 1.2%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 1         | 1.2%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 1         | 1.2%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 15        | 36.59%  |
| Intel                 | 10        | 24.39%  |
| Broadcom              | 6         | 14.63%  |
| Realtek Semiconductor | 5         | 12.2%   |
| Broadcom Limited      | 3         | 7.32%   |
| Ralink                | 1         | 2.44%   |
| NetGear               | 1         | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 12.2%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 9.76%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 7.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 4.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 4.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 4.88%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 4.88%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 4.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.44%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 2.44%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 2.44%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 2.44%   |
| Realtek 802.11ac NIC                                                    | 1         | 2.44%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.44%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                     | 1         | 2.44%   |
| Intel Wireless 8260                                                     | 1         | 2.44%   |
| Intel Wireless 7265                                                     | 1         | 2.44%   |
| Intel Wireless 7260                                                     | 1         | 2.44%   |
| Intel Wireless 3165                                                     | 1         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 2.44%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 2.44%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 2.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.44%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 2.44%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 1         | 2.44%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2.44%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 21        | 51.22%  |
| Qualcomm Atheros                 | 5         | 12.2%   |
| Intel                            | 5         | 12.2%   |
| Broadcom                         | 4         | 9.76%   |
| Broadcom Limited                 | 2         | 4.88%   |
| Silicon Integrated Systems [SiS] | 1         | 2.44%   |
| Samsung Electronics              | 1         | 2.44%   |
| Marvell Technology Group         | 1         | 2.44%   |
| ASIX Electronics                 | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 29.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 21.95%  |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 4.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.88%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 4.88%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.44%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.44%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.44%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 2.44%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.44%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 2.44%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 49.37%  |
| Ethernet | 39        | 49.37%  |
| Modem    | 1         | 1.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 67.5%   |
| Ethernet | 13        | 32.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 38        | 97.44%  |
| 1     | 1         | 2.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 34        | 87.18%  |
| Yes  | 5         | 12.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 6         | 26.09%  |
| Intel                           | 6         | 26.09%  |
| Lite-On Technology              | 3         | 13.04%  |
| Realtek Semiconductor           | 2         | 8.7%    |
| Hewlett-Packard                 | 2         | 8.7%    |
| Cambridge Silicon Radio         | 2         | 8.7%    |
| Ralink Technology               | 1         | 4.35%   |
| Foxconn / Hon Hai               | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 13.04%  |
| Intel Bluetooth wireless interface                          | 3         | 13.04%  |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 8.7%    |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 8.7%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 8.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 8.7%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                | 1         | 4.35%   |
| Qualcomm Atheros  Bluetooth Device                          | 1         | 4.35%   |
| Qualcomm Atheros Bluetooth USB Host Controller              | 1         | 4.35%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 4.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 4.35%   |
| Intel AX201 Bluetooth                                       | 1         | 4.35%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 4.35%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 4.35%   |
| Foxconn / Hon Hai BCM20702A0                                | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 29        | 67.44%  |
| AMD                              | 9         | 20.93%  |
| Nvidia                           | 3         | 6.98%   |
| Silicon Integrated Systems [SiS] | 2         | 4.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 15.69%  |
| AMD FCH Azalia Controller                                                  | 5         | 9.8%    |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 7.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 5.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 5.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 5.88%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 3.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 3.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 3.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.96%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.96%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.96%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.96%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.96%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.96%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 1.96%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 1.96%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 1.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 2         | 33.33%  |
| Unknown             | 1         | 16.67%  |
| Smart               | 1         | 16.67%  |
| Samsung Electronics | 1         | 16.67%  |
| Kingston            | 1         | 16.67%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM SDRAM                      | 1         | 16.67%  |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s    | 1         | 16.67%  |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1         | 16.67%  |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s | 1         | 16.67%  |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s     | 1         | 16.67%  |
| Kingston RAM 9905428-026.A00LF 2GB SODIMM DDR3 1066MT/s  | 1         | 16.67%  |

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
| 8192 | 2         | 33.33%  |
| 4096 | 2         | 33.33%  |
| 2048 | 2         | 33.33%  |

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
| Chicony Electronics                    | 6         | 20%     |
| Suyin                                  | 5         | 16.67%  |
| Realtek Semiconductor                  | 4         | 13.33%  |
| IMC Networks                           | 3         | 10%     |
| Cheng Uei Precision Industry (Foxlink) | 3         | 10%     |
| Silicon Motion                         | 2         | 6.67%   |
| Microdia                               | 2         | 6.67%   |
| Syntek                                 | 1         | 3.33%   |
| Sunplus Innovation Technology          | 1         | 3.33%   |
| Ricoh                                  | 1         | 3.33%   |
| Quanta                                 | 1         | 3.33%   |
| Lite-On Technology                     | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                           | 2         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 6.67%   |
| Syntek Lenovo EasyCamera                                    | 1         | 3.33%   |
| Suyin HP Webcam-50                                          | 1         | 3.33%   |
| Suyin HP Webcam-101                                         | 1         | 3.33%   |
| Suyin HP Integrated Webcam                                  | 1         | 3.33%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 3.33%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 3.33%   |
| Sunplus HD WebCam                                           | 1         | 3.33%   |
| Silicon Motion WebCam SCB-1100N                             | 1         | 3.33%   |
| Silicon Motion Web Camera                                   | 1         | 3.33%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 3.33%   |
| Realtek Lenovo EasyCamera                                   | 1         | 3.33%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 3.33%   |
| Realtek Integrated_Webcam_HD                                | 1         | 3.33%   |
| Realtek Acer 640 x 480 laptop camera                        | 1         | 3.33%   |
| Quanta HD Webcam                                            | 1         | 3.33%   |
| Microdia USB 2.0 Camera                                     | 1         | 3.33%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 3.33%   |
| Lite-On Integrated Camera                                   | 1         | 3.33%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 1         | 3.33%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 3.33%   |
| IMC Networks Integrated Webcam                              | 1         | 3.33%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 3.33%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 3.33%   |
| Chicony Integrated Camera                                   | 1         | 3.33%   |
| Chicony HP TrueVision HD Camera                             | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 3.33%   |

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
| 0     | 25        | 62.5%   |
| 1     | 14        | 35%     |
| 2     | 1         | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 6         | 37.5%   |
| Net/wireless       | 4         | 25%     |
| Fingerprint reader | 2         | 12.5%   |
| Chipcard           | 2         | 12.5%   |
| Storage            | 1         | 6.25%   |
| Network            | 1         | 6.25%   |

