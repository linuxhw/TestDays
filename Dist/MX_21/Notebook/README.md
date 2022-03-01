MX 21 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for MX 21.

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
| Dell          | Latitude 3190               | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | Latitude 3190               | [9637b88602](https://linux-hardware.org/?probe=9637b88602) | Feb 21, 2022 |
| Dell          | XPS 17 9710                 | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| Dell          | Latitude 3190               | [6340f68567](https://linux-hardware.org/?probe=6340f68567) | Feb 14, 2022 |
| Sony          | SVE1513Q1ESI                | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude 3190               | [90df65f573](https://linux-hardware.org/?probe=90df65f573) | Feb 07, 2022 |
| Dell          | Latitude E4310              | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Dell          | Latitude 3190               | [2e81dc022b](https://linux-hardware.org/?probe=2e81dc022b) | Jan 31, 2022 |
| Dell          | Latitude 3190               | [9b8e8549fd](https://linux-hardware.org/?probe=9b8e8549fd) | Jan 24, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| Dell          | Latitude 3190               | [3bb6a6428f](https://linux-hardware.org/?probe=3bb6a6428f) | Jan 10, 2022 |
| HP            | EliteBook 840 G3            | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Dell          | Latitude 3190               | [2c483dc59d](https://linux-hardware.org/?probe=2c483dc59d) | Jan 03, 2022 |
| Gigabyte      | P15FV5                      | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| Dell          | Latitude 3190               | [67cba6d321](https://linux-hardware.org/?probe=67cba6d321) | Dec 27, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| ASUSTek       | X550CC                      | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Dell          | Latitude 3190               | [1a96380872](https://linux-hardware.org/?probe=1a96380872) | Dec 20, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Dell          | Latitude 3190               | [5321909b8c](https://linux-hardware.org/?probe=5321909b8c) | Dec 13, 2021 |
| Dell          | Latitude 3190               | [9c532278f1](https://linux-hardware.org/?probe=9c532278f1) | Dec 06, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| Lenovo        | B590 20208                  | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Dell          | Latitude 3190               | [700dd2459e](https://linux-hardware.org/?probe=700dd2459e) | Nov 29, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Dell          | Latitude 3190               | [7f020f1d1f](https://linux-hardware.org/?probe=7f020f1d1f) | Nov 22, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Dell          | Latitude 3190               | [f24ac635ba](https://linux-hardware.org/?probe=f24ac635ba) | Nov 15, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| ASUSTek       | E402MA                      | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.10.0-9-amd64    | 14        | 40%     |
| 5.14.0-4mx-amd64  | 6         | 17.14%  |
| 5.10.0-11-amd64   | 6         | 17.14%  |
| 5.10.0-10-amd64   | 3         | 8.57%   |
| 5.10.0-8-amd64    | 2         | 5.71%   |
| 5.10.0-11-686-pae | 2         | 5.71%   |
| 5.10.0-5mx-amd64  | 1         | 2.86%   |
| 5.10.0-11-686     | 1         | 2.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 27        | 81.82%  |
| 5.14.0  | 6         | 18.18%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 27        | 81.82%  |
| 5.14    | 6         | 18.18%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 30        | 90.91%  |
| i686   | 3         | 9.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| XFCE   | 22        | 66.67%  |
| KDE5   | 9         | 27.27%  |
| GNOME  | 1         | 3.03%   |
| Budgie | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 32        | 96.97%  |
| Tty  | 1         | 3.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 23        | 69.7%   |
| SDDM    | 9         | 27.27%  |
| Unknown | 1         | 3.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 15        | 45.45%  |
| it_IT   | 3         | 9.09%   |
| de_DE   | 3         | 9.09%   |
| ru_RU   | 2         | 6.06%   |
| pt_BR   | 2         | 6.06%   |
| Unknown | 2         | 6.06%   |
| sk_SK   | 1         | 3.03%   |
| fr_FR   | 1         | 3.03%   |
| es_PE   | 1         | 3.03%   |
| es_ES   | 1         | 3.03%   |
| en_GB   | 1         | 3.03%   |
| de_CH   | 1         | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 22        | 66.67%  |
| BIOS | 11        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 26        | 78.79%  |
| Overlay | 4         | 12.12%  |
| Btrfs   | 2         | 6.06%   |
| F2fs    | 1         | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 23        | 69.7%   |
| MBR  | 10        | 30.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 63.64%  |
| Yes       | 12        | 36.36%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 51.52%  |
| No        | 16        | 48.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 6         | 18.18%  |
| ASUSTek Computer    | 6         | 18.18%  |
| Sony                | 4         | 12.12%  |
| Hewlett-Packard     | 4         | 12.12%  |
| Dell                | 3         | 9.09%   |
| Samsung Electronics | 2         | 6.06%   |
| Fujitsu Siemens     | 2         | 6.06%   |
| MSI                 | 1         | 3.03%   |
| Gigabyte Technology | 1         | 3.03%   |
| efirstview          | 1         | 3.03%   |
| Chuwi               | 1         | 3.03%   |
| Apple               | 1         | 3.03%   |
| Alienware           | 1         | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Sony VPCF119FX                            | 1         | 3.03%   |
| Sony VPCEH2N1E                            | 1         | 3.03%   |
| Sony VPCEC3S1E                            | 1         | 3.03%   |
| Sony SVE1513Q1ESI                         | 1         | 3.03%   |
| Samsung 350V5C/351V5C/3540VC/3440VC       | 1         | 3.03%   |
| Samsung 340XAA/350XAA/550XAA              | 1         | 3.03%   |
| MSI Alpha 15 B5EEK                        | 1         | 3.03%   |
| Lenovo ThinkPad W541 20EG0005MS           | 1         | 3.03%   |
| Lenovo ThinkPad E15 Gen 3 20YG008CUS      | 1         | 3.03%   |
| Lenovo ThinkBook 13s-IWL 20R9             | 1         | 3.03%   |
| Lenovo IdeaPad Y700-15ISK 80NV            | 1         | 3.03%   |
| Lenovo G400s VILG1                        | 1         | 3.03%   |
| Lenovo B590 20208                         | 1         | 3.03%   |
| HP EliteBook 850 G3                       | 1         | 3.03%   |
| HP EliteBook 8440p                        | 1         | 3.03%   |
| HP EliteBook 840 G3                       | 1         | 3.03%   |
| HP Compaq Presario CQ60                   | 1         | 3.03%   |
| Gigabyte P15FV5                           | 1         | 3.03%   |
| Fujitsu Siemens LIFEBOOK E8010            | 1         | 3.03%   |
| Fujitsu Siemens ESPRIMO Mobile D9500      | 1         | 3.03%   |
| efirstview v01099                         | 1         | 3.03%   |
| Dell XPS 17 9710                          | 1         | 3.03%   |
| Dell Latitude E4310                       | 1         | 3.03%   |
| Dell Latitude 3190                        | 1         | 3.03%   |
| Chuwi GemiBook Pro                        | 1         | 3.03%   |
| ASUS X550CC                               | 1         | 3.03%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 1         | 3.03%   |
| ASUS N53SN                                | 1         | 3.03%   |
| ASUS E402MA                               | 1         | 3.03%   |
| ASUS ASUS TUF Gaming A15 FA506QE_TUF506QE | 1         | 3.03%   |
| ASUS 1101HA                               | 1         | 3.03%   |
| Apple MacBook3,1                          | 1         | 3.03%   |
| Alienware 13 R2                           | 1         | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP EliteBook             | 3         | 9.09%   |
| Lenovo ThinkPad          | 2         | 6.06%   |
| Dell Latitude            | 2         | 6.06%   |
| Sony VPCF119FX           | 1         | 3.03%   |
| Sony VPCEH2N1E           | 1         | 3.03%   |
| Sony VPCEC3S1E           | 1         | 3.03%   |
| Sony SVE1513Q1ESI        | 1         | 3.03%   |
| Samsung 350V5C           | 1         | 3.03%   |
| Samsung 340XAA           | 1         | 3.03%   |
| MSI Alpha                | 1         | 3.03%   |
| Lenovo ThinkBook         | 1         | 3.03%   |
| Lenovo IdeaPad           | 1         | 3.03%   |
| Lenovo G400s             | 1         | 3.03%   |
| Lenovo B590              | 1         | 3.03%   |
| HP Compaq                | 1         | 3.03%   |
| Gigabyte P15FV5          | 1         | 3.03%   |
| Fujitsu Siemens LIFEBOOK | 1         | 3.03%   |
| Fujitsu Siemens ESPRIMO  | 1         | 3.03%   |
| efirstview v01099        | 1         | 3.03%   |
| Dell XPS                 | 1         | 3.03%   |
| Chuwi GemiBook           | 1         | 3.03%   |
| ASUS X550CC              | 1         | 3.03%   |
| ASUS TUF                 | 1         | 3.03%   |
| ASUS N53SN               | 1         | 3.03%   |
| ASUS E402MA              | 1         | 3.03%   |
| ASUS ASUS                | 1         | 3.03%   |
| ASUS 1101HA              | 1         | 3.03%   |
| Apple MacBook3           | 1         | 3.03%   |
| Alienware 13             | 1         | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 5         | 15.15%  |
| 2015    | 5         | 15.15%  |
| 2010    | 4         | 12.12%  |
| 2016    | 3         | 9.09%   |
| 2013    | 3         | 9.09%   |
| 2019    | 2         | 6.06%   |
| 2011    | 2         | 6.06%   |
| 2008    | 2         | 6.06%   |
| 2018    | 1         | 3.03%   |
| 2014    | 1         | 3.03%   |
| 2012    | 1         | 3.03%   |
| 2009    | 1         | 3.03%   |
| 2007    | 1         | 3.03%   |
| 2005    | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 33        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 33        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 14        | 42.42%  |
| 8.01-16.0  | 7         | 21.21%  |
| 16.01-24.0 | 4         | 12.12%  |
| 3.01-4.0   | 3         | 9.09%   |
| 2.01-3.0   | 2         | 6.06%   |
| 24.01-32.0 | 1         | 3.03%   |
| 1.01-2.0   | 1         | 3.03%   |
| 0.51-1.0   | 1         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 12        | 35.29%  |
| 2.01-3.0  | 8         | 23.53%  |
| 0.51-1.0  | 5         | 14.71%  |
| 4.01-8.0  | 4         | 11.76%  |
| 3.01-4.0  | 4         | 11.76%  |
| 8.01-16.0 | 1         | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 69.7%   |
| 2      | 8         | 24.24%  |
| 3      | 1         | 3.03%   |
| 0      | 1         | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 63.64%  |
| Yes       | 12        | 36.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 81.82%  |
| No        | 6         | 18.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 90.91%  |
| No        | 3         | 9.09%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 78.79%  |
| No        | 7         | 21.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 7         | 21.21%  |
| Italy       | 5         | 15.15%  |
| Germany     | 4         | 12.12%  |
| Canada      | 2         | 6.06%   |
| Brazil      | 2         | 6.06%   |
| Belgium     | 2         | 6.06%   |
| Switzerland | 1         | 3.03%   |
| Spain       | 1         | 3.03%   |
| Slovakia    | 1         | 3.03%   |
| Serbia      | 1         | 3.03%   |
| Russia      | 1         | 3.03%   |
| Poland      | 1         | 3.03%   |
| Peru        | 1         | 3.03%   |
| Netherlands | 1         | 3.03%   |
| France      | 1         | 3.03%   |
| Belarus     | 1         | 3.03%   |
| Azerbaijan  | 1         | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Zurich         | 1         | 3.03%   |
| Warsaw         | 1         | 3.03%   |
| Udine          | 1         | 3.03%   |
| Taggia         | 1         | 3.03%   |
| St Petersburg  | 1         | 3.03%   |
| Saskatoon      | 1         | 3.03%   |
| Saarlouis      | 1         | 3.03%   |
| Roseville      | 1         | 3.03%   |
| Powder Springs | 1         | 3.03%   |
| Portland       | 1         | 3.03%   |
| Ottawa         | 1         | 3.03%   |
| Osasco         | 1         | 3.03%   |
| Mussolente     | 1         | 3.03%   |
| Munich         | 1         | 3.03%   |
| Minsk          | 1         | 3.03%   |
| Milan          | 1         | 3.03%   |
| Lima           | 1         | 3.03%   |
| Lannion        | 1         | 3.03%   |
| Kent           | 1         | 3.03%   |
| Huercal Overa  | 1         | 3.03%   |
| Graniteville   | 1         | 3.03%   |
| Glendale       | 1         | 3.03%   |
| Gilmer         | 1         | 3.03%   |
| Florence       | 1         | 3.03%   |
| Colfontaine    | 1         | 3.03%   |
| Brussels       | 1         | 3.03%   |
| Bratislava     | 1         | 3.03%   |
| Bindlach       | 1         | 3.03%   |
| Berlin         | 1         | 3.03%   |
| Belo Horizonte | 1         | 3.03%   |
| Belgrade       | 1         | 3.03%   |
| Baku           | 1         | 3.03%   |
| Amsterdam      | 1         | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 14.29%  |
| Samsung Electronics | 6         | 6      | 14.29%  |
| Seagate             | 5         | 5      | 11.9%   |
| Kingston            | 4         | 4      | 9.52%   |
| Crucial             | 3         | 6      | 7.14%   |
| Transcend           | 2         | 2      | 4.76%   |
| SK Hynix            | 2         | 2      | 4.76%   |
| LITEON              | 2         | 2      | 4.76%   |
| DOGFISH             | 2         | 2      | 4.76%   |
| Unknown             | 1         | 1      | 2.38%   |
| Toshiba             | 1         | 1      | 2.38%   |
| SanDisk             | 1         | 1      | 2.38%   |
| PNY                 | 1         | 1      | 2.38%   |
| Netac               | 1         | 1      | 2.38%   |
| Intel               | 1         | 1      | 2.38%   |
| Gigabyte Technology | 1         | 1      | 2.38%   |
| GeIL                | 1         | 1      | 2.38%   |
| Fujitsu             | 1         | 1      | 2.38%   |
| Unknown             | 1         | 1      | 2.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 3         | 7.14%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 2.38%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 2.38%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 2.38%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 2.38%   |
| WDC PC SN730 NVMe 1024GB             | 1         | 2.38%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB | 1         | 2.38%   |
| Unknown SDW32G  32GB                 | 1         | 2.38%   |
| Transcend TS256GSSD370S 256GB        | 1         | 2.38%   |
| Transcend TS128GMTS800 128GB SSD     | 1         | 2.38%   |
| Toshiba MQ01ABD075 752GB             | 1         | 2.38%   |
| SK Hynix HFM512GD3JX013N 512GB       | 1         | 2.38%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 2.38%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 2.38%   |
| Seagate ST500LM000-1EJ162 500GB      | 1         | 2.38%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 2.38%   |
| SanDisk SD8SN8U-512G-1006 512GB SSD  | 1         | 2.38%   |
| Samsung SSD 970 EVO 1TB              | 1         | 2.38%   |
| Samsung SSD 860 EVO M.2 1TB          | 1         | 2.38%   |
| Samsung SSD 860 EVO 500GB            | 1         | 2.38%   |
| Samsung SSD 860 EVO 1TB              | 1         | 2.38%   |
| Samsung SSD 840 PRO Series 256GB     | 1         | 2.38%   |
| Samsung HM500JI 500GB                | 1         | 2.38%   |
| PNY CS900 500GB SSD                  | 1         | 2.38%   |
| Netac SSD 256GB                      | 1         | 2.38%   |
| LITEON CV1-8B512-HP 512GB SSD        | 1         | 2.38%   |
| LITEON CV1-8B256 256GB SSD           | 1         | 2.38%   |
| Kingston OM8PCP3512F-AI1 512GB       | 1         | 2.38%   |
| Intel SSDSA2BW120G3H 120GB           | 1         | 2.38%   |
| Gigabyte GP-GSTFS31256GTND 256GB SSD | 1         | 2.38%   |
| GeIL R3_128GB SSD                    | 1         | 2.38%   |
| Fujitsu MHT2080AH 80GB               | 1         | 2.38%   |
| DOGFISH SSD 512GB                    | 1         | 2.38%   |
| Dogfish SSD 128GB                    | 1         | 2.38%   |
| Crucial CT500MX500SSD1 500GB         | 1         | 2.38%   |
| Crucial CT1000MX500SSD4 1TB          | 1         | 2.38%   |
| Crucial CT1000MX500SSD1 1TB          | 1         | 2.38%   |
| Unknown                              | 1         | 2.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 45.45%  |
| WDC                 | 3         | 3      | 27.27%  |
| Toshiba             | 1         | 1      | 9.09%   |
| Samsung Electronics | 1         | 1      | 9.09%   |
| Fujitsu             | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 17.39%  |
| Kingston            | 3         | 3      | 13.04%  |
| Crucial             | 3         | 6      | 13.04%  |
| Transcend           | 2         | 2      | 8.7%    |
| LITEON              | 2         | 2      | 8.7%    |
| Dogfish             | 2         | 2      | 8.7%    |
| WDC                 | 1         | 1      | 4.35%   |
| SanDisk             | 1         | 1      | 4.35%   |
| PNY                 | 1         | 1      | 4.35%   |
| Netac               | 1         | 1      | 4.35%   |
| Intel               | 1         | 1      | 4.35%   |
| Gigabyte Technology | 1         | 1      | 4.35%   |
| GeIL                | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 20        | 26     | 51.28%  |
| HDD  | 11        | 11     | 28.21%  |
| NVMe | 6         | 6      | 15.38%  |
| MMC  | 2         | 2      | 5.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 25        | 37     | 75.76%  |
| NVMe | 6         | 6      | 18.18%  |
| MMC  | 2         | 2      | 6.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 21     | 61.29%  |
| 0.51-1.0   | 11        | 15     | 35.48%  |
| 1.01-2.0   | 1         | 1      | 3.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 9         | 27.27%  |
| 251-500    | 7         | 21.21%  |
| 501-1000   | 5         | 15.15%  |
| 21-50      | 4         | 12.12%  |
| 1-20       | 3         | 9.09%   |
| 51-100     | 3         | 9.09%   |
| 2001-3000  | 1         | 3.03%   |
| 1001-2000  | 1         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 17        | 51.52%  |
| 251-500   | 4         | 12.12%  |
| 21-50     | 4         | 12.12%  |
| 101-250   | 3         | 9.09%   |
| 51-100    | 3         | 9.09%   |
| 1001-2000 | 1         | 3.03%   |
| 501-1000  | 1         | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 50%     |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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
| Works    | 31        | 41     | 88.57%  |
| Detected | 2         | 2      | 5.71%   |
| Malfunc  | 2         | 2      | 5.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 25        | 75.76%  |
| SK Hynix                    | 2         | 6.06%   |
| Sandisk                     | 2         | 6.06%   |
| Silicon Image               | 1         | 3.03%   |
| Samsung Electronics         | 1         | 3.03%   |
| Nvidia                      | 1         | 3.03%   |
| Kingston Technology Company | 1         | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 13.89%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 8.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 5.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 5.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 5.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 5.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 5.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 5.56%   |
| SK Hynix Gold P31 SSD                                                          | 1         | 2.78%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1         | 2.78%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 2.78%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 2.78%   |
| Sandisk Non-Volatile memory controller                                         | 1         | 2.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2.78%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                   | 1         | 2.78%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 1         | 2.78%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 2.78%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 1         | 2.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 2.78%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 2.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 21        | 60%     |
| NVMe | 6         | 17.14%  |
| IDE  | 5         | 14.29%  |
| RAID | 3         | 8.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 84.85%  |
| AMD    | 5         | 15.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 6.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 6.06%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 6.06%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 6.06%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 3.03%   |
| Intel Pentium M processor 1.80GHz             | 1         | 3.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 3.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.03%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 3.03%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 3.03%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 3.03%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 3.03%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 3.03%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 3.03%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 3.03%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 3.03%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 3.03%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 3.03%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 3.03%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 3.03%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 3.03%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 3.03%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 3.03%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 3.03%   |
| Intel Atom CPU Z3735G @ 1.33GHz               | 1         | 3.03%   |
| Intel 11th Gen Core i9-11980HK @ 2.60GHz      | 1         | 3.03%   |
| AMD Sempron SI-42                             | 1         | 3.03%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 10        | 30.3%   |
| Intel Core i5        | 7         | 21.21%  |
| AMD Ryzen 7          | 4         | 12.12%  |
| Intel Core i3        | 2         | 6.06%   |
| Intel Core 2 Duo     | 2         | 6.06%   |
| Intel Celeron        | 2         | 6.06%   |
| Intel Atom           | 2         | 6.06%   |
| Other                | 1         | 3.03%   |
| Intel Pentium Silver | 1         | 3.03%   |
| Intel Pentium M      | 1         | 3.03%   |
| AMD Sempron          | 1         | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 14        | 42.42%  |
| 4      | 12        | 36.36%  |
| 8      | 4         | 12.12%  |
| 1      | 3         | 9.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 33        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 25        | 75.76%  |
| 1      | 8         | 24.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 31        | 93.94%  |
| 32-bit         | 2         | 6.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 4         | 12.12%  |
| 0x406e3    | 3         | 9.09%   |
| 0x506e3    | 2         | 6.06%   |
| 0x30678    | 2         | 6.06%   |
| 0x206a7    | 2         | 6.06%   |
| 0x20655    | 2         | 6.06%   |
| 0x0a50000c | 2         | 6.06%   |
| Unknown    | 2         | 6.06%   |
| 0x806eb    | 1         | 3.03%   |
| 0x806ea    | 1         | 3.03%   |
| 0x806d1    | 1         | 3.03%   |
| 0x706a8    | 1         | 3.03%   |
| 0x706a1    | 1         | 3.03%   |
| 0x6fd      | 1         | 3.03%   |
| 0x6fb      | 1         | 3.03%   |
| 0x6d6      | 1         | 3.03%   |
| 0x306c3    | 1         | 3.03%   |
| 0x106e5    | 1         | 3.03%   |
| 0x106c2    | 1         | 3.03%   |
| 0x08608103 | 1         | 3.03%   |
| 0x08108102 | 1         | 3.03%   |
| 0x02000057 | 1         | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Skylake         | 5         | 15.15%  |
| IvyBridge       | 4         | 12.12%  |
| Westmere        | 3         | 9.09%   |
| SandyBridge     | 3         | 9.09%   |
| Zen 3           | 2         | 6.06%   |
| Silvermont      | 2         | 6.06%   |
| KabyLake        | 2         | 6.06%   |
| Goldmont plus   | 2         | 6.06%   |
| Core            | 2         | 6.06%   |
| Zen+            | 1         | 3.03%   |
| P6              | 1         | 3.03%   |
| Nehalem         | 1         | 3.03%   |
| K8 & K10 hybrid | 1         | 3.03%   |
| Icelake         | 1         | 3.03%   |
| Haswell         | 1         | 3.03%   |
| Bonnell         | 1         | 3.03%   |
| Unknown         | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 56.82%  |
| Nvidia | 12        | 27.27%  |
| AMD    | 7         | 15.91%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 8.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 6.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 6.38%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 2         | 4.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 4.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 4.26%   |
| Intel HD Graphics 530                                                     | 2         | 4.26%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 4.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 4.26%   |
| AMD Cezanne                                                               | 2         | 4.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 2.13%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 2.13%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 2.13%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 2.13%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 1         | 2.13%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 2.13%   |
| Nvidia GF108M [GeForce GT 550M]                                           | 1         | 2.13%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 2.13%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 2.13%   |
| Nvidia C77 [GeForce 8200M G]                                              | 1         | 2.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 2.13%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                       | 1         | 2.13%   |
| Intel UHD Graphics 620                                                    | 1         | 2.13%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 2.13%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 1         | 2.13%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 2.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 2.13%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                 | 1         | 2.13%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]             | 1         | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 2.13%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                | 1         | 2.13%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                  | 1         | 2.13%   |
| AMD Lucienne                                                              | 1         | 2.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 48.48%  |
| Intel + Nvidia | 8         | 24.24%  |
| 1 x AMD        | 3         | 9.09%   |
| 1 x Nvidia     | 2         | 6.06%   |
| AMD + Nvidia   | 2         | 6.06%   |
| 2 x AMD        | 1         | 3.03%   |
| Intel + AMD    | 1         | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 28        | 84.85%  |
| Proprietary | 5         | 15.15%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 75.76%  |
| 0.51-1.0   | 3         | 9.09%   |
| 0.01-0.5   | 3         | 9.09%   |
| 7.01-8.0   | 1         | 3.03%   |
| 3.01-4.0   | 1         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 6         | 15.79%  |
| Samsung Electronics     | 5         | 13.16%  |
| LG Display              | 5         | 13.16%  |
| AU Optronics            | 5         | 13.16%  |
| Sony                    | 2         | 5.26%   |
| Sharp                   | 2         | 5.26%   |
| Chi Mei Optoelectronics | 2         | 5.26%   |
| BOE                     | 2         | 5.26%   |
| Ancor Communications    | 2         | 5.26%   |
| Philips                 | 1         | 2.63%   |
| PANDA                   | 1         | 2.63%   |
| Panasonic               | 1         | 2.63%   |
| Lenovo                  | 1         | 2.63%   |
| Goldstar                | 1         | 2.63%   |
| CPT                     | 1         | 2.63%   |
| Apple                   | 1         | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 5.26%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 5.26%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                            | 1         | 2.63%   |
| Sony LCD Monitor MS_0025 1920x1080 340x190mm 15.3-inch                   | 1         | 2.63%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 2.63%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 2.63%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 2.63%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 2.63%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 2.63%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 2.63%   |
| Panasonic VVX10T025J00 MEI96A2 2560x1600 223x125mm 10.1-inch             | 1         | 2.63%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 2.63%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD024D 1366x768 294x166mm 13.3-inch              | 1         | 2.63%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 527x296mm 23.8-inch                 | 1         | 2.63%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 1         | 2.63%   |
| CPT LCD Monitor CPT1C21 1366x768 256x144mm 11.6-inch                     | 1         | 2.63%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 2.63%   |
| BOE LCD Monitor BOE0714 1920x1080 344x193mm 15.5-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 1         | 2.63%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO123E 1600x900 309x174mm 14.0-inch            | 1         | 2.63%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 1         | 2.63%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch         | 1         | 2.63%   |
| Ancor Communications ASUS VW193S ACI19D4 1440x900 408x255mm 18.9-inch    | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 13        | 37.14%  |
| 1366x768 (WXGA)  | 11        | 31.43%  |
| 3840x2160 (4K)   | 3         | 8.57%   |
| 1600x900 (HD+)   | 2         | 5.71%   |
| 1280x800 (WXGA)  | 2         | 5.71%   |
| 3840x2400        | 1         | 2.86%   |
| 2560x1080        | 1         | 2.86%   |
| 2160x1440        | 1         | 2.86%   |
| 1440x900 (WXGA+) | 1         | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 17        | 44.74%  |
| 14     | 4         | 10.53%  |
| 24     | 3         | 7.89%   |
| 17     | 3         | 7.89%   |
| 13     | 3         | 7.89%   |
| 27     | 2         | 5.26%   |
| 23     | 2         | 5.26%   |
| 11     | 2         | 5.26%   |
| 34     | 1         | 2.63%   |
| 19     | 1         | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 50%     |
| 501-600     | 7         | 18.42%  |
| 201-300     | 6         | 15.79%  |
| 351-400     | 4         | 10.53%  |
| 701-800     | 1         | 2.63%   |
| 401-500     | 1         | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 79.41%  |
| 16/10 | 5         | 14.71%  |
| 3/2   | 1         | 2.94%   |
| 21/9  | 1         | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 44.74%  |
| 81-90          | 5         | 13.16%  |
| 201-250        | 4         | 10.53%  |
| 121-130        | 3         | 7.89%   |
| 71-80          | 2         | 5.26%   |
| 51-60          | 2         | 5.26%   |
| 301-350        | 2         | 5.26%   |
| 351-500        | 1         | 2.63%   |
| 251-300        | 1         | 2.63%   |
| 151-200        | 1         | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 11        | 30.56%  |
| 51-100        | 11        | 30.56%  |
| 101-120       | 8         | 22.22%  |
| More than 240 | 3         | 8.33%   |
| 161-240       | 3         | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 24        | 72.73%  |
| 2     | 8         | 24.24%  |
| 3     | 1         | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 16        | 31.37%  |
| Realtek Semiconductor    | 14        | 27.45%  |
| Qualcomm Atheros         | 10        | 19.61%  |
| Marvell Technology Group | 4         | 7.84%   |
| TP-Link                  | 2         | 3.92%   |
| Ralink Technology        | 1         | 1.96%   |
| Nvidia                   | 1         | 1.96%   |
| MEDIATEK                 | 1         | 1.96%   |
| Dell                     | 1         | 1.96%   |
| Broadcom                 | 1         | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 12        | 19.05%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 3         | 4.76%   |
| Intel Wireless 8260                                                            | 3         | 4.76%   |
| Intel Wi-Fi 6 AX200                                                            | 3         | 4.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 3.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 3.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 3.17%   |
| Intel Ethernet Connection I219-V                                               | 2         | 3.17%   |
| Intel Centrino Advanced-N 6200                                                 | 2         | 3.17%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 3.17%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.59%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1         | 1.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.59%   |
| Ralink RT2070 Wireless Adapter                                                 | 1         | 1.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 1.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 1.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 1.59%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 1.59%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 1.59%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 1.59%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.59%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.59%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 1.59%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.59%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 1.59%   |
| Intel Wireless 7260                                                            | 1         | 1.59%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1         | 1.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 1.59%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 1.59%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 1.59%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 1.59%   |
| Intel Centrino Advanced-N 6235                                                 | 1         | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 1.59%   |
| Dell F3607gw v2 Mobile Broadband Module                                        | 1         | 1.59%   |
| Broadcom BCM4321 802.11a/b/g/n                                                 | 1         | 1.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 48.48%  |
| Qualcomm Atheros      | 9         | 27.27%  |
| Realtek Semiconductor | 4         | 12.12%  |
| TP-Link               | 1         | 3.03%   |
| Ralink Technology     | 1         | 3.03%   |
| MEDIATEK              | 1         | 3.03%   |
| Broadcom              | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 9.09%   |
| Intel Wireless 8260                                                     | 3         | 9.09%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 9.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 6.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 6.06%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 6.06%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 3.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 3.03%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 3.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 3.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 3.03%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 3.03%   |
| Intel Wireless 8265 / 8275                                              | 1         | 3.03%   |
| Intel Wireless 7260                                                     | 1         | 3.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 3.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 3.03%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 3.03%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 3.03%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 3.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 3.03%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 14        | 50%     |
| Intel                    | 5         | 17.86%  |
| Marvell Technology Group | 4         | 14.29%  |
| Qualcomm Atheros         | 3         | 10.71%  |
| TP-Link                  | 1         | 3.57%   |
| Nvidia                   | 1         | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 12        | 41.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 6.9%    |
| Intel Ethernet Connection I219-V                                               | 2         | 6.9%    |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 6.9%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 3.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 3.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 3.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 3.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 3.45%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 3.45%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 3.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 3.45%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 3.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 3.45%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 51.72%  |
| Ethernet | 27        | 46.55%  |
| Modem    | 1         | 1.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 66.67%  |
| Ethernet | 11        | 30.56%  |
| Modem    | 1         | 2.78%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 25        | 75.76%  |
| 1     | 7         | 21.21%  |
| 0     | 1         | 3.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 81.82%  |
| Yes  | 6         | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 37.04%  |
| Qualcomm Atheros Communications | 3         | 11.11%  |
| Foxconn / Hon Hai               | 3         | 11.11%  |
| Realtek Semiconductor           | 2         | 7.41%   |
| IMC Networks                    | 2         | 7.41%   |
| Cambridge Silicon Radio         | 2         | 7.41%   |
| Qualcomm Atheros                | 1         | 3.7%    |
| Hewlett-Packard                 | 1         | 3.7%    |
| Dell                            | 1         | 3.7%    |
| ASUSTek Computer                | 1         | 3.7%    |
| Apple                           | 1         | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 5         | 18.52%  |
| Intel AX200 Bluetooth                                                               | 3         | 11.11%  |
| Realtek Bluetooth Radio                                                             | 2         | 7.41%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 7.41%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 7.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 7.41%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 3.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 3.7%    |
| Intel Bluetooth wireless interface                                                  | 1         | 3.7%    |
| Intel AX201 Bluetooth                                                               | 1         | 3.7%    |
| IMC Networks Wireless_Device                                                        | 1         | 3.7%    |
| IMC Networks Bluetooth Radio                                                        | 1         | 3.7%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 3.7%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 3.7%    |
| Dell DW375 Bluetooth Module                                                         | 1         | 3.7%    |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 3.7%    |
| Apple Bluetooth HCI                                                                 | 1         | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 27        | 62.79%  |
| Nvidia              | 8         | 18.6%   |
| AMD                 | 5         | 11.63%  |
| Plantronics         | 1         | 2.33%   |
| C-Media Electronics | 1         | 2.33%   |
| Unknown             | 1         | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 10.42%  |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 8.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 8.33%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 8.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 6.25%   |
| Nvidia Audio device                                                        | 2         | 4.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 4.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 4.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 4.17%   |
| Plantronics BT600                                                          | 1         | 2.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.08%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1         | 2.08%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 2.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 2.08%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 2.08%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.08%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 2.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 2.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.08%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1         | 2.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.08%   |
| C-Media Electronics USB Advanced Audio Device                              | 1         | 2.08%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 2.08%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 1         | 2.08%   |
| Unknown                                                                    | 1         | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 10        | 26.32%  |
| SK Hynix            | 9         | 23.68%  |
| Samsung Electronics | 8         | 21.05%  |
| Micron Technology   | 3         | 7.89%   |
| Smart               | 2         | 5.26%   |
| Kingston            | 2         | 5.26%   |
| Unknown (ABCD)      | 1         | 2.63%   |
| PNY                 | 1         | 2.63%   |
| Crucial             | 1         | 2.63%   |
| Unknown             | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 6.98%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 4.65%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 4.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 4.65%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 2.33%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 2.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 2.33%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 2.33%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 2.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 2.33%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 2.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 2.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2.33%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 2.33%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s            | 1         | 2.33%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 2.33%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 2.33%   |
| SK Hynix RAM HMT351S6EFR8A 4096MB SODIMM DDR3 1600MT/s           | 1         | 2.33%   |
| SK Hynix RAM HMT351S6AFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2.33%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s        | 1         | 2.33%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 2.33%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 2.33%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 2.33%   |
| SK Hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 1         | 2.33%   |
| Samsung RAM Module 4GB SODIMM DDR2 667MT/s                       | 1         | 2.33%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 2.33%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 2.33%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.33%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.33%   |
| PNY RAM Module 8GB SODIMM DDR3 1333MT/s                          | 1         | 2.33%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s        | 1         | 2.33%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 2.33%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 1         | 2.33%   |
| Kingston RAM HP594908-HR1-ELD 2GB SODIMM DDR3 1333MT/s           | 1         | 2.33%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 2.33%   |
| Kingston RAM 99U5428-041.A01LF 4GB SODIMM DDR3 1067MT/s          | 1         | 2.33%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 1         | 2.33%   |
| Unknown                                                          | 1         | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 15        | 45.45%  |
| DDR4   | 11        | 33.33%  |
| DDR2   | 3         | 9.09%   |
| SDRAM  | 1         | 3.03%   |
| LPDDR4 | 1         | 3.03%   |
| DRAM   | 1         | 3.03%   |
| DDR    | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 32        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 15        | 40.54%  |
| 4096 | 11        | 29.73%  |
| 2048 | 8         | 21.62%  |
| 1024 | 3         | 8.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 6         | 17.14%  |
| 1333    | 5         | 14.29%  |
| Unknown | 5         | 14.29%  |
| 3200    | 4         | 11.43%  |
| 2400    | 3         | 8.57%   |
| 2133    | 3         | 8.57%   |
| 667     | 3         | 8.57%   |
| 2667    | 2         | 5.71%   |
| 4199    | 1         | 2.86%   |
| 1334    | 1         | 2.86%   |
| 1067    | 1         | 2.86%   |
| 166     | 1         | 2.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P2055 series | 1         | 100%    |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 7         | 26.92%  |
| Realtek Semiconductor         | 3         | 11.54%  |
| Microdia                      | 3         | 11.54%  |
| Lite-On Technology            | 2         | 7.69%   |
| IMC Networks                  | 2         | 7.69%   |
| Z-Star Microelectronics       | 1         | 3.85%   |
| Suyin                         | 1         | 3.85%   |
| Sunplus Innovation Technology | 1         | 3.85%   |
| Silicon Motion                | 1         | 3.85%   |
| Ricoh                         | 1         | 3.85%   |
| Primax Electronics            | 1         | 3.85%   |
| Logitech                      | 1         | 3.85%   |
| Goodong Industry              | 1         | 3.85%   |
| 8SSC20F27145V1SR18P0H10       | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Z-Star Venus USB2.0 Camera                 | 1         | 3.85%   |
| Suyin Sony Visual Communication Camera     | 1         | 3.85%   |
| Sunplus Integrated_Webcam_HD               | 1         | 3.85%   |
| Silicon Motion Web Camera                  | 1         | 3.85%   |
| Ricoh USB2.0 Camera                        | 1         | 3.85%   |
| Realtek USB Camera                         | 1         | 3.85%   |
| Realtek Lenovo EasyCamera                  | 1         | 3.85%   |
| Realtek Integrated Webcam                  | 1         | 3.85%   |
| Primax Dell Laptop Integrated Webcam 2Mpix | 1         | 3.85%   |
| Microdia Webcam Vitade AF                  | 1         | 3.85%   |
| Microdia WebCam SC-13HDL12639P             | 1         | 3.85%   |
| Microdia Webcam                            | 1         | 3.85%   |
| Logitech StreamCam                         | 1         | 3.85%   |
| Lite-On HP HD Webcam                       | 1         | 3.85%   |
| Lite-On HP HD Camera                       | 1         | 3.85%   |
| IMC Networks USB2.0 UVC 1.3M WebCam        | 1         | 3.85%   |
| IMC Networks USB2.0 HD UVC WebCam          | 1         | 3.85%   |
| Goodong Industry USB2.0 HD UVC WebCam      | 1         | 3.85%   |
| Chicony USB2.0 HD UVC WebCam               | 1         | 3.85%   |
| Chicony USB 2.0 Camera                     | 1         | 3.85%   |
| Chicony Sony Visual Communication Camera   | 1         | 3.85%   |
| Chicony Lenovo EasyCamera                  | 1         | 3.85%   |
| Chicony Integrated Camera                  | 1         | 3.85%   |
| Chicony HP Webcam [2 MP Macro]             | 1         | 3.85%   |
| Chicony 2.0M UVC WebCam                    | 1         | 3.85%   |
| 8SSC20F27145V1SR18P0H10 Integrated Camera  | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 50%     |
| Shenzhen Goodix Technology | 2         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device          | 2         | 50%     |
| Validity Sensors VFS495 Fingerprint Reader   | 1         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 21        | 63.64%  |
| 1     | 10        | 30.3%   |
| 2     | 2         | 6.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 7         | 58.33%  |
| Fingerprint reader | 4         | 33.33%  |
| Chipcard           | 1         | 8.33%   |

