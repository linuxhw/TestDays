Elementary 6 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=elementary-6

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

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Alienware | 17                          | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Acer      | Aspire V3-572G              | [addf12cb05](https://linux-hardware.org/?probe=addf12cb05) | Sep 16, 2021 |
| TUXEDO    | InfinityBook S 14 Gen6      | [0c206818b9](https://linux-hardware.org/?probe=0c206818b9) | Sep 15, 2021 |
| Acer      | Aspire VX5-591G             | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| Dell      | Latitude E7440              | [fc9f25eecb](https://linux-hardware.org/?probe=fc9f25eecb) | Sep 14, 2021 |
| Toshiba   | Satellite P100              | [bc5b605920](https://linux-hardware.org/?probe=bc5b605920) | Sep 13, 2021 |
| HP        | Pavilion Notebook           | [591ba7a77c](https://linux-hardware.org/?probe=591ba7a77c) | Sep 12, 2021 |
| Dell      | Inspiron 3583               | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| ASUSTek   | UX303LA                     | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| HP        | Pavilion Notebook           | [f373a049e2](https://linux-hardware.org/?probe=f373a049e2) | Sep 10, 2021 |
| HP        | Pavilion Notebook           | [6e97abfd44](https://linux-hardware.org/?probe=6e97abfd44) | Sep 09, 2021 |
| Lenovo    | ThinkPad X201 3249CTO       | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| HP        | Laptop 14-dq1xxx            | [0614925ee7](https://linux-hardware.org/?probe=0614925ee7) | Sep 08, 2021 |
| Gateway   | NV54 Series                 | [fcf57528ed](https://linux-hardware.org/?probe=fcf57528ed) | Sep 08, 2021 |
| Sony      | Serie VJC14                 | [27828e1dfb](https://linux-hardware.org/?probe=27828e1dfb) | Sep 07, 2021 |
| Sony      | Serie VJC14                 | [4c1200e7cf](https://linux-hardware.org/?probe=4c1200e7cf) | Sep 07, 2021 |
| Lenovo    | V330-15IKB 81AX             | [797db05baf](https://linux-hardware.org/?probe=797db05baf) | Sep 06, 2021 |
| HP        | Laptop 15-bs1xx             | [91ecd39f66](https://linux-hardware.org/?probe=91ecd39f66) | Sep 05, 2021 |
| Medion    | AKOYA THE TOUCH 10          | [d49d62a2f5](https://linux-hardware.org/?probe=d49d62a2f5) | Sep 04, 2021 |
| Apple     | MacBookPro8,1               | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| HP        | EliteBook Folio 9470m       | [adbb6a690a](https://linux-hardware.org/?probe=adbb6a690a) | Sep 01, 2021 |
| Dell      | Latitude 3580               | [2befbbba9e](https://linux-hardware.org/?probe=2befbbba9e) | Aug 31, 2021 |
| HP        | Pavilion g6                 | [7dba3c201c](https://linux-hardware.org/?probe=7dba3c201c) | Aug 31, 2021 |
| HP        | Pavilion Aero Laptop 13-... | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| HP        | ProBook 4320s               | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| eMachines | G525                        | [d64e29475f](https://linux-hardware.org/?probe=d64e29475f) | Aug 29, 2021 |
| Lenovo    | ThinkPad X201 3249CTO       | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| Acer      | Aspire A515-51G             | [df0d3e8ac4](https://linux-hardware.org/?probe=df0d3e8ac4) | Aug 26, 2021 |
| HP        | Laptop 15-bs0xx             | [fae546f5cb](https://linux-hardware.org/?probe=fae546f5cb) | Aug 20, 2021 |
| Apple     | MacBookPro9,1               | [e9bec90506](https://linux-hardware.org/?probe=e9bec90506) | Aug 19, 2021 |
| Acer      | Aspire F5-573G              | [9d7628068c](https://linux-hardware.org/?probe=9d7628068c) | Aug 19, 2021 |
| Dell      | XPS L321X                   | [34d7fb6cbb](https://linux-hardware.org/?probe=34d7fb6cbb) | Aug 18, 2021 |
| HP        | ProBook 450 G8 Notebook ... | [f30480d463](https://linux-hardware.org/?probe=f30480d463) | Aug 17, 2021 |
| HP        | Notebook                    | [a3058005e3](https://linux-hardware.org/?probe=a3058005e3) | Aug 16, 2021 |
| HP        | Notebook                    | [7800ef9623](https://linux-hardware.org/?probe=7800ef9623) | Aug 16, 2021 |
| Lenovo    | IdeaPad 330-15IKB 81FE      | [fa6c69671f](https://linux-hardware.org/?probe=fa6c69671f) | Aug 16, 2021 |
| Apple     | MacBookPro9,1               | [a6b2c12401](https://linux-hardware.org/?probe=a6b2c12401) | Aug 14, 2021 |
| Dell      | Precision 5760              | [824e5e7dad](https://linux-hardware.org/?probe=824e5e7dad) | Aug 14, 2021 |
| Acer      | Aspire A514-54              | [dcfc87a32f](https://linux-hardware.org/?probe=dcfc87a32f) | Aug 14, 2021 |
| Acer      | Aspire A514-54              | [e354646c04](https://linux-hardware.org/?probe=e354646c04) | Aug 13, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [4e6f050b43](https://linux-hardware.org/?probe=4e6f050b43) | Aug 10, 2021 |
| Toshiba   | Satellite L500              | [76a8d2c20a](https://linux-hardware.org/?probe=76a8d2c20a) | Jul 29, 2021 |
| Google    | Cave                        | [e2617f0c2d](https://linux-hardware.org/?probe=e2617f0c2d) | Jul 25, 2021 |
| Toshiba   | Satellite L500              | [7124417642](https://linux-hardware.org/?probe=7124417642) | Jul 22, 2021 |
| HP        | Stream Laptop 14-cb1xxx     | [0447155931](https://linux-hardware.org/?probe=0447155931) | Jul 02, 2021 |
| Acer      | Swift SF314-55G             | [c371b46cbe](https://linux-hardware.org/?probe=c371b46cbe) | Jun 30, 2021 |
| Acer      | Swift SF315-41              | [8df5e13fc0](https://linux-hardware.org/?probe=8df5e13fc0) | Jun 18, 2021 |
| Acer      | Swift SF314-55G             | [4e5cf8aa1e](https://linux-hardware.org/?probe=4e5cf8aa1e) | Jun 13, 2021 |
| Acer      | ConceptD CN315-71P          | [5ecea84320](https://linux-hardware.org/?probe=5ecea84320) | May 15, 2021 |
| Apple     | MacBookPro8,2               | [e87a073ae8](https://linux-hardware.org/?probe=e87a073ae8) | Mar 18, 2021 |
| HP        | EliteBook 840 G3            | [1e31858e51](https://linux-hardware.org/?probe=1e31858e51) | Mar 09, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.11.0-27-generic     | 22        | 51.16%  |
| 5.11.0-25-generic     | 10        | 23.26%  |
| 5.11.0-34-generic     | 4         | 9.3%    |
| 5.8.0-55-generic      | 2         | 4.65%   |
| 5.8.0-63-generic      | 1         | 2.33%   |
| 5.8.0-53-generic      | 1         | 2.33%   |
| 5.8.0-50-generic      | 1         | 2.33%   |
| 5.8.0-44-generic      | 1         | 2.33%   |
| 5.11.0-051100-generic | 1         | 2.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 37        | 86.05%  |
| 5.8.0   | 6         | 13.95%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 37        | 86.05%  |
| 5.8     | 6         | 13.95%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 43        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Pantheon   | 36        | 83.72%  |
| Unknown    | 5         | 11.63%  |
| X-Cinnamon | 1         | 2.33%   |
| GNOME      | 1         | 2.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 43        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 32        | 74.42%  |
| LightDM | 5         | 11.63%  |
| TDM     | 4         | 9.3%    |
| GDM     | 2         | 4.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 25        | 58.14%  |
| es_ES | 4         | 9.3%    |
| zh_CN | 2         | 4.65%   |
| pt_BR | 2         | 4.65%   |
| en_GB | 2         | 4.65%   |
| en_CA | 2         | 4.65%   |
| de_DE | 2         | 4.65%   |
| ru_RU | 1         | 2.33%   |
| fr_FR | 1         | 2.33%   |
| en_AU | 1         | 2.33%   |
| cs_CZ | 1         | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 27        | 62.79%  |
| BIOS | 16        | 37.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 39        | 90.7%   |
| Overlay | 3         | 6.98%   |
| Btrfs   | 1         | 2.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 32        | 74.42%  |
| GPT     | 9         | 20.93%  |
| MBR     | 2         | 4.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 95.35%  |
| Yes       | 2         | 4.65%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 88.37%  |
| Yes       | 5         | 11.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 14        | 32.56%  |
| Acer             | 8         | 18.6%   |
| Dell             | 5         | 11.63%  |
| Apple            | 4         | 9.3%    |
| Lenovo           | 3         | 6.98%   |
| Toshiba          | 2         | 4.65%   |
| TUXEDO           | 1         | 2.33%   |
| Sony             | 1         | 2.33%   |
| Medion           | 1         | 2.33%   |
| Gateway          | 1         | 2.33%   |
| eMachines        | 1         | 2.33%   |
| ASUSTek Computer | 1         | 2.33%   |
| Alienware        | 1         | 2.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| HP Pavilion Notebook                | 2         | 4.65%   |
| Apple MacBookPro9,1                 | 2         | 4.65%   |
| TUXEDO InfinityBook S 14 Gen6       | 1         | 2.33%   |
| Toshiba Satellite P100              | 1         | 2.33%   |
| Toshiba Satellite L500              | 1         | 2.33%   |
| Sony Serie VJC14                    | 1         | 2.33%   |
| Medion AKOYA THE TOUCH 10           | 1         | 2.33%   |
| Lenovo V330-15IKB 81AX              | 1         | 2.33%   |
| Lenovo ThinkPad X201 3249CTO        | 1         | 2.33%   |
| Lenovo IdeaPad 330-15IKB 81FE       | 1         | 2.33%   |
| HP Stream Laptop 14-cb1xxx          | 1         | 2.33%   |
| HP ProBook 450 G8 Notebook PC       | 1         | 2.33%   |
| HP ProBook 4320s                    | 1         | 2.33%   |
| HP Pavilion Gaming Laptop 15-ec0xxx | 1         | 2.33%   |
| HP Pavilion g6                      | 1         | 2.33%   |
| HP Pavilion Aero Laptop 13-be0xxx   | 1         | 2.33%   |
| HP Notebook                         | 1         | 2.33%   |
| HP Laptop 15-bs1xx                  | 1         | 2.33%   |
| HP Laptop 15-bs0xx                  | 1         | 2.33%   |
| HP Laptop 14-dq1xxx                 | 1         | 2.33%   |
| HP EliteBook Folio 9470m            | 1         | 2.33%   |
| HP EliteBook 840 G3                 | 1         | 2.33%   |
| Gateway NV54 Series                 | 1         | 2.33%   |
| eMachines G525                      | 1         | 2.33%   |
| Dell XPS L321X                      | 1         | 2.33%   |
| Dell Precision 5760                 | 1         | 2.33%   |
| Dell Latitude E7440                 | 1         | 2.33%   |
| Dell Latitude 3580                  | 1         | 2.33%   |
| Dell Inspiron 3583                  | 1         | 2.33%   |
| ASUS UX303LA                        | 1         | 2.33%   |
| Apple MacBookPro8,2                 | 1         | 2.33%   |
| Apple MacBookPro8,1                 | 1         | 2.33%   |
| Alienware 17                        | 1         | 2.33%   |
| Acer Swift SF315-41                 | 1         | 2.33%   |
| Acer Swift SF314-55G                | 1         | 2.33%   |
| Acer ConceptD CN315-71P             | 1         | 2.33%   |
| Acer Aspire VX5-591G                | 1         | 2.33%   |
| Acer Aspire V3-572G                 | 1         | 2.33%   |
| Acer Aspire F5-573G                 | 1         | 2.33%   |
| Acer Aspire A515-51G                | 1         | 2.33%   |
| Acer Aspire A514-54                 | 1         | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| HP Pavilion         | 5         | 11.63%  |
| Acer Aspire         | 5         | 11.63%  |
| HP Laptop           | 3         | 6.98%   |
| Toshiba Satellite   | 2         | 4.65%   |
| HP ProBook          | 2         | 4.65%   |
| HP EliteBook        | 2         | 4.65%   |
| Dell Latitude       | 2         | 4.65%   |
| Apple MacBookPro9   | 2         | 4.65%   |
| Apple MacBookPro8   | 2         | 4.65%   |
| Acer Swift          | 2         | 4.65%   |
| TUXEDO InfinityBook | 1         | 2.33%   |
| Sony Serie          | 1         | 2.33%   |
| Medion AKOYA        | 1         | 2.33%   |
| Lenovo V330-15IKB   | 1         | 2.33%   |
| Lenovo ThinkPad     | 1         | 2.33%   |
| Lenovo IdeaPad      | 1         | 2.33%   |
| HP Stream           | 1         | 2.33%   |
| HP Notebook         | 1         | 2.33%   |
| Gateway NV54        | 1         | 2.33%   |
| eMachines G525      | 1         | 2.33%   |
| Dell XPS            | 1         | 2.33%   |
| Dell Precision      | 1         | 2.33%   |
| Dell Inspiron       | 1         | 2.33%   |
| ASUS UX303LA        | 1         | 2.33%   |
| Alienware 17        | 1         | 2.33%   |
| Acer ConceptD       | 1         | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 8         | 18.6%   |
| 2018    | 8         | 18.6%   |
| 2019    | 6         | 13.95%  |
| 2020    | 5         | 11.63%  |
| 2015    | 3         | 6.98%   |
| 2010    | 3         | 6.98%   |
| 2017    | 2         | 4.65%   |
| 2014    | 2         | 4.65%   |
| 2013    | 2         | 4.65%   |
| 2012    | 2         | 4.65%   |
| 2009    | 1         | 2.33%   |
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
| Disabled | 32        | 74.42%  |
| Enabled  | 11        | 25.58%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 43        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 15        | 34.88%  |
| 3.01-4.0   | 9         | 20.93%  |
| 16.01-24.0 | 9         | 20.93%  |
| 8.01-16.0  | 5         | 11.63%  |
| 32.01-64.0 | 3         | 6.98%   |
| 24.01-32.0 | 1         | 2.33%   |
| 1.01-2.0   | 1         | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 15        | 34.09%  |
| 1.01-2.0 | 14        | 31.82%  |
| 3.01-4.0 | 8         | 18.18%  |
| 4.01-8.0 | 7         | 15.91%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 30        | 69.77%  |
| 2      | 11        | 25.58%  |
| 4      | 1         | 2.33%   |
| 3      | 1         | 2.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 74.42%  |
| Yes       | 11        | 25.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 81.4%   |
| No        | 8         | 18.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 97.67%  |
| No        | 1         | 2.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 88.64%  |
| No        | 5         | 11.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 18.6%   |
| India       | 5         | 11.63%  |
| Germany     | 3         | 6.98%   |
| Brazil      | 3         | 6.98%   |
| UK          | 2         | 4.65%   |
| Guatemala   | 2         | 4.65%   |
| Canada      | 2         | 4.65%   |
| Argentina   | 2         | 4.65%   |
| Serbia      | 1         | 2.33%   |
| Russia      | 1         | 2.33%   |
| Netherlands | 1         | 2.33%   |
| Myanmar     | 1         | 2.33%   |
| Mexico      | 1         | 2.33%   |
| Latvia      | 1         | 2.33%   |
| Kazakhstan  | 1         | 2.33%   |
| Japan       | 1         | 2.33%   |
| Guyana      | 1         | 2.33%   |
| France      | 1         | 2.33%   |
| Estonia     | 1         | 2.33%   |
| Denmark     | 1         | 2.33%   |
| Czechia     | 1         | 2.33%   |
| China       | 1         | 2.33%   |
| Belgium     | 1         | 2.33%   |
| Australia   | 1         | 2.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Guatemala City   | 2         | 4.55%   |
| Vernon           | 1         | 2.27%   |
| Toledo           | 1         | 2.27%   |
| Tokyo            | 1         | 2.27%   |
| Thousand Oaks    | 1         | 2.27%   |
| Tallinn          | 1         | 2.27%   |
| Stevenage        | 1         | 2.27%   |
| Sinop            | 1         | 2.27%   |
| S??o Pedro       | 1         | 2.27%   |
| Santa Monica     | 1         | 2.27%   |
| Sakai            | 1         | 2.27%   |
| Sacramento       | 1         | 2.27%   |
| Quer?©taro City  | 1         | 2.27%   |
| Perth            | 1         | 2.27%   |
| Peekskill        | 1         | 2.27%   |
| Patna            | 1         | 2.27%   |
| Paris            | 1         | 2.27%   |
| Odense           | 1         | 2.27%   |
| Northridge       | 1         | 2.27%   |
| Naaldwijk        | 1         | 2.27%   |
| Moss Point       | 1         | 2.27%   |
| Moscow           | 1         | 2.27%   |
| Montreal         | 1         | 2.27%   |
| Monheim am Rhein | 1         | 2.27%   |
| Mandalay         | 1         | 2.27%   |
| Lucknow          | 1         | 2.27%   |
| Len?«nskoe       | 1         | 2.27%   |
| Lanaken          | 1         | 2.27%   |
| Kovin            | 1         | 2.27%   |
| Koraput          | 1         | 2.27%   |
| Jaunmarupe       | 1         | 2.27%   |
| Jalandhar        | 1         | 2.27%   |
| Horovice         | 1         | 2.27%   |
| Hollern          | 1         | 2.27%   |
| Georgetown       | 1         | 2.27%   |
| Curitiba         | 1         | 2.27%   |
| Chattanooga      | 1         | 2.27%   |
| C??rdoba         | 1         | 2.27%   |
| Camberwell       | 1         | 2.27%   |
| Buenos Aires     | 1         | 2.27%   |
| Bhopal           | 1         | 2.27%   |
| Berlin           | 1         | 2.27%   |
| Beijing          | 1         | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 14        | 15     | 23.73%  |
| Samsung Electronics       | 11        | 11     | 18.64%  |
| Seagate                   | 5         | 6      | 8.47%   |
| Sandisk                   | 4         | 4      | 6.78%   |
| Unknown                   | 3         | 3      | 5.08%   |
| Toshiba                   | 3         | 3      | 5.08%   |
| Kingston                  | 3         | 3      | 5.08%   |
| Hitachi                   | 3         | 3      | 5.08%   |
| Crucial                   | 3         | 3      | 5.08%   |
| HGST                      | 2         | 2      | 3.39%   |
| SK Hynix                  | 1         | 1      | 1.69%   |
| Phison                    | 1         | 1      | 1.69%   |
| Micron/Crucial Technology | 1         | 1      | 1.69%   |
| Micron Technology         | 1         | 1      | 1.69%   |
| Mercury                   | 1         | 1      | 1.69%   |
| LITEONIT                  | 1         | 1      | 1.69%   |
| Gigabyte Technology       | 1         | 1      | 1.69%   |
| CLOVER                    | 1         | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| WDC WDS500G2B0A-00SM50 500GB SSD         | 2         | 3.33%   |
| WDC WD10SPZX-21Z10T0 1TB                 | 2         | 3.33%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 2         | 3.33%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 3.33%   |
| Kingston SA400S37240G 240GB SSD          | 2         | 3.33%   |
| WDC WD5000LPVX-22V0TT0 500GB             | 1         | 1.67%   |
| WDC WD5000BPKT-75PK4T0 500GB             | 1         | 1.67%   |
| WDC WD20SPZX-21UA7T0 2TB                 | 1         | 1.67%   |
| WDC WD10SPZX-24Z10T0 1TB                 | 1         | 1.67%   |
| WDC WD10SPZX-22Z10T1 1TB                 | 1         | 1.67%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1.67%   |
| WDC PC SN720 SDAPNTW-256G-1014 256GB     | 1         | 1.67%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB     | 1         | 1.67%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB     | 1         | 1.67%   |
| Unknown xD/SD/M.S.                       | 1         | 1.67%   |
| Unknown TA2964  64GB                     | 1         | 1.67%   |
| Unknown MMC Card  128GB                  | 1         | 1.67%   |
| Toshiba MQ01ABD100V -63 1TB              | 1         | 1.67%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1.67%   |
| Toshiba MK5065GSXF 500GB                 | 1         | 1.67%   |
| SK Hynix NVMe SSD Drive 512GB            | 1         | 1.67%   |
| Seagate ST9250315AS 250GB                | 1         | 1.67%   |
| Seagate ST1000LM049-2GH172 1TB           | 1         | 1.67%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 1.67%   |
| SanDisk SDSSDA480G 480GB                 | 1         | 1.67%   |
| SanDisk SD7SB3Q256G1002 256GB SSD        | 1         | 1.67%   |
| SanDisk SD7SB3Q128G1001 128GB SSD        | 1         | 1.67%   |
| Sandisk NVMe SSD Drive 256GB             | 1         | 1.67%   |
| Samsung SSD SM841 mSATA 128GB            | 1         | 1.67%   |
| Samsung SSD 970 EVO Plus 250GB           | 1         | 1.67%   |
| Samsung SSD 860 EVO 2TB                  | 1         | 1.67%   |
| Samsung SSD 860 EVO 250GB                | 1         | 1.67%   |
| Samsung SSD 840 EVO 120GB mSATA          | 1         | 1.67%   |
| Samsung NVMe SSD Drive 500GB             | 1         | 1.67%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 1.67%   |
| Samsung MZVLW256HEHP-000L2 256GB         | 1         | 1.67%   |
| Samsung MZNTY128HDHP-000H1 128GB SSD     | 1         | 1.67%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD     | 1         | 1.67%   |
| Samsung HM321HI 320GB                    | 1         | 1.67%   |
| Phison NVMe SSD Drive 2TB                | 1         | 1.67%   |
| Micron/Crucial NVMe SSD Drive 500GB      | 1         | 1.67%   |
| Micron NVMe SSD Drive 512GB              | 1         | 1.67%   |
| Mercury Electra 3G SSD                   | 1         | 1.67%   |
| LITEONIT LMT-256M3M 256GB SSD            | 1         | 1.67%   |
| Kingston SA400S37120G 120GB SSD          | 1         | 1.67%   |
| Hitachi HTS725025A9A364 250GB            | 1         | 1.67%   |
| Hitachi HTS545050B9A300 500GB            | 1         | 1.67%   |
| Hitachi HTS542512K9SA00 120GB            | 1         | 1.67%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1.67%   |
| HGST HTS541010A9E680 1TB                 | 1         | 1.67%   |
| Gigabyte GP-GSM2NE3100TNTD 1TB           | 1         | 1.67%   |
| Crucial CT500MX500SSD4 500GB             | 1         | 1.67%   |
| Crucial CT480BX500SSD1 480GB             | 1         | 1.67%   |
| Crucial CT120BX500SSD1 120GB             | 1         | 1.67%   |
| CLOVER CN-M640MBB G267M8B640G7W122 640GB | 1         | 1.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 10     | 41.67%  |
| Seagate             | 5         | 6      | 20.83%  |
| Toshiba             | 3         | 3      | 12.5%   |
| Hitachi             | 3         | 3      | 12.5%   |
| HGST                | 2         | 2      | 8.33%   |
| Samsung Electronics | 1         | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 31.58%  |
| SanDisk             | 3         | 3      | 15.79%  |
| Kingston            | 3         | 3      | 15.79%  |
| Crucial             | 3         | 3      | 15.79%  |
| WDC                 | 2         | 2      | 10.53%  |
| Mercury             | 1         | 1      | 5.26%   |
| LITEONIT            | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 24        | 25     | 43.64%  |
| SSD     | 16        | 19     | 29.09%  |
| NVMe    | 11        | 13     | 20%     |
| MMC     | 2         | 2      | 3.64%   |
| Unknown | 2         | 2      | 3.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 35        | 45     | 71.43%  |
| NVMe | 11        | 13     | 22.45%  |
| MMC  | 2         | 2      | 4.08%   |
| SAS  | 1         | 1      | 2.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 27     | 55.26%  |
| 0.51-1.0   | 15        | 15     | 39.47%  |
| 1.01-2.0   | 2         | 2      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 17        | 39.53%  |
| 251-500    | 9         | 20.93%  |
| 501-1000   | 7         | 16.28%  |
| 1001-2000  | 4         | 9.3%    |
| 51-100     | 3         | 6.98%   |
| 1-20       | 2         | 4.65%   |
| 2001-3000  | 1         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 24        | 55.81%  |
| 51-100    | 8         | 18.6%   |
| 21-50     | 5         | 11.63%  |
| 251-500   | 2         | 4.65%   |
| 1001-2000 | 2         | 4.65%   |
| 101-250   | 1         | 2.33%   |
| 501-1000  | 1         | 2.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPKT-75PK4T0 500GB      | 1         | 1      | 50%     |
| SanDisk SD7SB3Q256G1002 256GB SSD | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

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
| Detected | 34        | 47     | 75.56%  |
| Works    | 9         | 12     | 20%     |
| Malfunc  | 2         | 2      | 4.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 37        | 69.81%  |
| Sandisk                   | 4         | 7.55%   |
| Samsung Electronics       | 4         | 7.55%   |
| AMD                       | 3         | 5.66%   |
| Phison Electronics        | 2         | 3.77%   |
| SK Hynix                  | 1         | 1.89%   |
| Micron/Crucial Technology | 1         | 1.89%   |
| Micron Technology         | 1         | 1.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 9         | 16.67%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 4         | 7.41%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 5.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 5.56%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 2         | 3.7%    |
| Samsung NVMe SSD Controller 980                                                        | 2         | 3.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 3.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 2         | 3.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 3.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 3.7%    |
| AMD FCH SATA Controller [AHCI mode]                                                    | 2         | 3.7%    |
| SK Hynix NVMe SSD Controller                                                           | 1         | 1.85%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 1         | 1.85%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 1.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.85%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.85%   |
| Phison E12 NVMe Controller                                                             | 1         | 1.85%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 1.85%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.85%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 1.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 1         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 30        | 57.69%  |
| NVMe | 11        | 21.15%  |
| RAID | 7         | 13.46%  |
| IDE  | 4         | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 90.7%   |
| AMD    | 4         | 9.3%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 6.98%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 4.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 4.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 4.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 4.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 4.65%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 4.65%   |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 2.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 2.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2.33%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 2.33%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 2.33%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 2.33%   |
| Intel Core i7-3687U CPU @ 2.10GHz             | 1         | 2.33%   |
| Intel Core i7-3615QM CPU @ 2.30GHz            | 1         | 2.33%   |
| Intel Core i7-2637M CPU @ 1.70GHz             | 1         | 2.33%   |
| Intel Core i7-2635QM CPU @ 2.00GHz            | 1         | 2.33%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 2.33%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.33%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 2.33%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.33%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 2.33%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 1         | 2.33%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 2.33%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 1         | 2.33%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 1         | 2.33%   |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 1         | 2.33%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.33%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2.33%   |
| Intel Celeron CPU N2807 @ 1.58GHz             | 1         | 2.33%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 2.33%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 1         | 2.33%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 2.33%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 2.33%   |
| AMD Phenom II N660 Dual-Core Processor        | 1         | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 14        | 32.56%  |
| Intel Core i7           | 13        | 30.23%  |
| Other                   | 3         | 6.98%   |
| Intel Celeron           | 3         | 6.98%   |
| AMD Ryzen 5             | 3         | 6.98%   |
| Intel Pentium Dual-Core | 2         | 4.65%   |
| Intel Xeon              | 1         | 2.33%   |
| Intel Core i3           | 1         | 2.33%   |
| Intel Core 2 Duo        | 1         | 2.33%   |
| Intel Core 2            | 1         | 2.33%   |
| AMD Phenom II           | 1         | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 53.49%  |
| 4      | 17        | 39.53%  |
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
| 2      | 35        | 81.4%   |
| 1      | 8         | 18.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 43        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 16.28%  |
| 0x806ea    | 3         | 6.98%   |
| 0x806c1    | 3         | 6.98%   |
| 0x406e3    | 3         | 6.98%   |
| 0x40651    | 3         | 6.98%   |
| 0x306a9    | 3         | 6.98%   |
| 0x906e9    | 2         | 4.65%   |
| 0x806eb    | 2         | 4.65%   |
| 0x806e9    | 2         | 4.65%   |
| 0x206a7    | 2         | 4.65%   |
| 0x20652    | 2         | 4.65%   |
| 0x1067a    | 2         | 4.65%   |
| 0x706e5    | 1         | 2.33%   |
| 0x706a8    | 1         | 2.33%   |
| 0x6fd      | 1         | 2.33%   |
| 0x406c3    | 1         | 2.33%   |
| 0x306c3    | 1         | 2.33%   |
| 0x30678    | 1         | 2.33%   |
| 0x0a50000c | 1         | 2.33%   |
| 0x08101007 | 1         | 2.33%   |
| 0x010000c8 | 1         | 2.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 25.58%  |
| Skylake       | 4         | 9.3%    |
| Haswell       | 4         | 9.3%    |
| TigerLake     | 3         | 6.98%   |
| SandyBridge   | 3         | 6.98%   |
| IvyBridge     | 3         | 6.98%   |
| Westmere      | 2         | 4.65%   |
| Silvermont    | 2         | 4.65%   |
| Penryn        | 2         | 4.65%   |
| Core          | 2         | 4.65%   |
| Zen+          | 1         | 2.33%   |
| Zen 3         | 1         | 2.33%   |
| Zen           | 1         | 2.33%   |
| K10           | 1         | 2.33%   |
| IceLake       | 1         | 2.33%   |
| Goldmont plus | 1         | 2.33%   |
| Unknown       | 1         | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 36        | 64.29%  |
| Nvidia | 14        | 25%     |
| AMD    | 6         | 10.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 4         | 7.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 7.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 5.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 5.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 5.26%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 3.51%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 3.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 3.51%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.51%   |
| Intel HD Graphics 630                                                                    | 2         | 3.51%   |
| Intel HD Graphics 620                                                                    | 2         | 3.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 3.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.51%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 3.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.75%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 1.75%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 1.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.75%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.75%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.75%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 1.75%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                                       | 1         | 1.75%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 1.75%   |
| Intel VGA compatible controller                                                          | 1         | 1.75%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 1.75%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 1.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.75%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.75%   |
| AMD Picasso                                                                              | 1         | 1.75%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 1.75%   |
| AMD Cezanne                                                                              | 1         | 1.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 55.81%  |
| Intel + Nvidia | 11        | 25.58%  |
| 1 x AMD        | 3         | 6.98%   |
| 1 x Nvidia     | 2         | 4.65%   |
| 2 x AMD        | 1         | 2.33%   |
| Intel + AMD    | 1         | 2.33%   |
| AMD + Nvidia   | 1         | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 36        | 83.72%  |
| Proprietary | 6         | 13.95%  |
| Unknown     | 1         | 2.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 76.74%  |
| 1.01-2.0   | 3         | 6.98%   |
| 0.01-0.5   | 3         | 6.98%   |
| 0.51-1.0   | 2         | 4.65%   |
| 3.01-4.0   | 1         | 2.33%   |
| 2.01-3.0   | 1         | 2.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 14        | 31.11%  |
| LG Display              | 6         | 13.33%  |
| BOE                     | 6         | 13.33%  |
| AU Optronics            | 5         | 11.11%  |
| Samsung Electronics     | 4         | 8.89%   |
| Apple                   | 4         | 8.89%   |
| Sharp                   | 1         | 2.22%   |
| Seiko/Epson             | 1         | 2.22%   |
| Lenovo                  | 1         | 2.22%   |
| Goldstar                | 1         | 2.22%   |
| Chi Mei Optoelectronics | 1         | 2.22%   |
| AOC                     | 1         | 2.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch         | 2         | 4.44%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 2         | 4.44%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 2         | 4.44%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 2.22%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch     | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch     | 1         | 2.22%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch        | 1         | 2.22%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 1         | 2.22%   |
| LG Display LCD Monitor LGD06AD 2560x1600 286x179mm 13.3-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 1         | 2.22%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 1         | 2.22%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch              | 1         | 2.22%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 2.22%   |
| Goldstar MP59HT GSM5B44 1920x1080 480x270mm 21.7-inch                    | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15E0 1920x1080 344x193mm 15.5-inch         | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch         | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1477 1366x768 309x174mm 14.0-inch          | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1361 1920x1080 290x170mm 13.2-inch         | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1338 1366x768 293x164mm 13.2-inch          | 1         | 2.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1711 1600x900 382x215mm 17.3-inch | 1         | 2.22%   |
| BOE LCD Monitor BOE0726 1920x1080 344x193mm 15.5-inch                    | 1         | 2.22%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 1         | 2.22%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 1         | 2.22%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 2.22%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 1         | 2.22%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x173mm 13.9-inch           | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO12D4 1280x800 216x135mm 10.0-inch            | 1         | 2.22%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                     | 1         | 2.22%   |
| Apple Color LCD APP9CB7 1680x1050 331x207mm 15.4-inch                    | 1         | 2.22%   |
| AOC 22V2WG5 AOC2202 1920x1080 476x268mm 21.5-inch                        | 1         | 2.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 18        | 42.86%  |
| 1366x768 (WXGA)    | 15        | 35.71%  |
| 1280x800 (WXGA)    | 3         | 7.14%   |
| 1440x900 (WXGA+)   | 2         | 4.76%   |
| 3840x2400          | 1         | 2.38%   |
| 2560x1600          | 1         | 2.38%   |
| 1680x1050 (WSXGA+) | 1         | 2.38%   |
| 1600x900 (HD+)     | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 23        | 51.11%  |
| 13      | 10        | 22.22%  |
| 14      | 4         | 8.89%   |
| 21      | 2         | 4.44%   |
| 17      | 2         | 4.44%   |
| 27      | 1         | 2.22%   |
| 12      | 1         | 2.22%   |
| 10      | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 68.89%  |
| 201-300     | 7         | 15.56%  |
| 351-400     | 3         | 6.67%   |
| 401-500     | 2         | 4.44%   |
| 501-600     | 1         | 2.22%   |
| Unknown     | 1         | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 33        | 78.57%  |
| 16/10   | 7         | 16.67%  |
| 3/2     | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 51.11%  |
| 81-90          | 10        | 22.22%  |
| 71-80          | 4         | 8.89%   |
| 61-70          | 1         | 2.22%   |
| 41-50          | 1         | 2.22%   |
| 301-350        | 1         | 2.22%   |
| 201-250        | 1         | 2.22%   |
| 151-200        | 1         | 2.22%   |
| 131-140        | 1         | 2.22%   |
| 121-130        | 1         | 2.22%   |
| Unknown        | 1         | 2.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 20        | 44.44%  |
| 121-160       | 19        | 42.22%  |
| 161-240       | 2         | 4.44%   |
| 51-100        | 2         | 4.44%   |
| More than 240 | 1         | 2.22%   |
| Unknown       | 1         | 2.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 40        | 93.02%  |
| 3     | 1         | 2.33%   |
| 2     | 1         | 2.33%   |
| 0     | 1         | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 26        | 36.11%  |
| Intel                 | 20        | 27.78%  |
| Broadcom              | 10        | 13.89%  |
| Qualcomm Atheros      | 8         | 11.11%  |
| MediaTek              | 2         | 2.78%   |
| TP-Link               | 1         | 1.39%   |
| Samsung Electronics   | 1         | 1.39%   |
| realme                | 1         | 1.39%   |
| Qualcomm              | 1         | 1.39%   |
| NEC Computers         | 1         | 1.39%   |
| DisplayLink           | 1         | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 20%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.88%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 4.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 4.71%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 4.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 3.53%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 2.35%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 2         | 2.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.35%   |
| Intel Wireless 7260                                               | 2         | 2.35%   |
| Intel Wireless 3165                                               | 2         | 2.35%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 2.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 1.18%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.18%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.18%   |
| realme SDM665-IDP _SN:18689828                                    | 1         | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.18%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.18%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 1.18%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.18%   |
| Qualcomm Android                                                  | 1         | 1.18%   |
| NEC Computers WiMAX Mobile Router                                 | 1         | 1.18%   |
| MediaTek TECNO Camon CX                                           | 1         | 1.18%   |
| MEDIATEK Network controller                                       | 1         | 1.18%   |
| Intel Wireless 8260                                               | 1         | 1.18%   |
| Intel Wireless 7265                                               | 1         | 1.18%   |
| Intel Wireless 3160                                               | 1         | 1.18%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.18%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.18%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.18%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.18%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.18%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.18%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.18%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 1.18%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.18%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.18%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 1.18%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.18%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1         | 1.18%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 1.18%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 1         | 1.18%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 43.18%  |
| Broadcom              | 9         | 20.45%  |
| Realtek Semiconductor | 7         | 15.91%  |
| Qualcomm Atheros      | 7         | 15.91%  |
| TP-Link               | 1         | 2.27%   |
| MEDIATEK              | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 4         | 9.09%   |
| Broadcom BCM4331 802.11a/b/g/n                             | 4         | 9.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 3         | 6.82%   |
| Realtek RTL8723DE Wireless Network Adapter                 | 2         | 4.55%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 2         | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 4.55%   |
| Intel Wireless 7260                                        | 2         | 4.55%   |
| Intel Wireless 3165                                        | 2         | 4.55%   |
| Broadcom BCM43142 802.11b/g/n                              | 2         | 4.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1         | 2.27%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1         | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 2.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1         | 2.27%   |
| MEDIATEK Network controller                                | 1         | 2.27%   |
| Intel Wireless 8260                                        | 1         | 2.27%   |
| Intel Wireless 7265                                        | 1         | 2.27%   |
| Intel Wireless 3160                                        | 1         | 2.27%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 2.27%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 1         | 2.27%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 2.27%   |
| Intel Centrino Wireless-N 2230                             | 1         | 2.27%   |
| Intel Centrino Advanced-N 6235                             | 1         | 2.27%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]              | 1         | 2.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 1         | 2.27%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1         | 2.27%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 1         | 2.27%   |
| Broadcom BCM4312 802.11b/g LP-PHY                          | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 57.5%   |
| Intel                 | 5         | 12.5%   |
| Broadcom              | 5         | 12.5%   |
| Qualcomm Atheros      | 2         | 5%      |
| Samsung Electronics   | 1         | 2.5%    |
| realme                | 1         | 2.5%    |
| Qualcomm              | 1         | 2.5%    |
| MediaTek              | 1         | 2.5%    |
| DisplayLink           | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 42.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 12.5%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 10%     |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 2.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.5%    |
| realme SDM665-IDP _SN:18689828                                    | 1         | 2.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.5%    |
| Qualcomm Android                                                  | 1         | 2.5%    |
| MediaTek TECNO Camon CX                                           | 1         | 2.5%    |
| Intel PRO/100 VE Network Connection                               | 1         | 2.5%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.5%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.5%    |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 2.5%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 42        | 53.85%  |
| Ethernet | 35        | 44.87%  |
| Unknown  | 1         | 1.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 54.41%  |
| Ethernet | 31        | 45.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 33        | 76.74%  |
| 1     | 10        | 23.26%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 76.74%  |
| Yes  | 10        | 23.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 47.37%  |
| Realtek Semiconductor           | 5         | 13.16%  |
| Lite-On Technology              | 4         | 10.53%  |
| Apple                           | 4         | 10.53%  |
| Qualcomm Atheros Communications | 2         | 5.26%   |
| Foxconn / Hon Hai               | 2         | 5.26%   |
| Broadcom                        | 2         | 5.26%   |
| IMC Networks                    | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 7         | 18.42%  |
| Intel Bluetooth Device                         | 4         | 10.53%  |
| Intel AX200 Bluetooth                          | 4         | 10.53%  |
| Realtek  Bluetooth 4.2 Adapter                 | 3         | 7.89%   |
| Realtek Bluetooth Radio                        | 2         | 5.26%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 5.26%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 2         | 5.26%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 2         | 5.26%   |
| Apple Bluetooth USB Host Controller            | 2         | 5.26%   |
| Apple Bluetooth Host Controller                | 2         | 5.26%   |
| Lite-On Wireless_Device                        | 1         | 2.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 2.63%   |
| Lite-On Qualcomm Atheros Bluetooth             | 1         | 2.63%   |
| Lite-On Bluetooth Device                       | 1         | 2.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 2.63%   |
| IMC Networks BCM20702A0                        | 1         | 2.63%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 2.63%   |
| Foxconn / Hon Hai BCM20702A0                   | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 73.58%  |
| Nvidia | 8         | 15.09%  |
| AMD    | 5         | 9.43%   |
| TEAC   | 1         | 1.89%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 16.67%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 5%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 5%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 5%      |
| Intel 8 Series HD Audio Controller                                                                | 3         | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 5%      |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 3         | 5%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 3.33%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 3.33%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 3.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 3.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 3.33%   |
| TEAC TASCAM iXR                                                                                   | 1         | 1.67%   |
| Nvidia stereo controller                                                                          | 1         | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.67%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 1.67%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.67%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.67%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.67%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 24%     |
| Micron Technology   | 5         | 20%     |
| SK Hynix            | 4         | 16%     |
| Kingston            | 4         | 16%     |
| Ramaxel Technology  | 2         | 8%      |
| Crucial             | 2         | 8%      |
| Toshiba             | 1         | 4%      |
| Qimonda             | 1         | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 2         | 7.69%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 2         | 7.69%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s            | 1         | 3.85%   |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s             | 1         | 3.85%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 3.85%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s     | 1         | 3.85%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                | 1         | 3.85%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 3.85%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s      | 1         | 3.85%   |
| Samsung RAM M4 70T5663EH3-CF7 2048MB SODIMM DDR2 2048MT/s     | 1         | 3.85%   |
| Ramaxel RAM RMT3170EF68F9W1600 4096MB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s     | 1         | 3.85%   |
| Qimonda RAM 64T256020EDL2.5C2 2048MB SODIMM DDR2 2048MT/s     | 1         | 3.85%   |
| Micron RAM MT41K256M16LY 2GB SODIMM DDR3 1600MT/s             | 1         | 3.85%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 1         | 3.85%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s         | 1         | 3.85%   |
| Micron RAM 16JSF25664HZ-1G4F1 2GB SODIMM DDR3 1334MT/s        | 1         | 3.85%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16384MB SODIMM DDR4 3200MT/s     | 1         | 3.85%   |
| Kingston RAM KHX2666C15S4/8G 8192MB SODIMM DDR4 2667MT/s      | 1         | 3.85%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s        | 1         | 3.85%   |
| Kingston RAM 9905700-070.A01G 16GB SODIMM DDR4 2667MT/s       | 1         | 3.85%   |
| Kingston RAM 9905700-026.A00G 8GB SODIMM DDR4 2667MT/s        | 1         | 3.85%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s    | 1         | 3.85%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16384MB SODIMM DDR4 2400MT/s | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR4  | 10        | 58.82%  |
| DDR3  | 5         | 29.41%  |
| SDRAM | 1         | 5.88%   |
| DDR2  | 1         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 17        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 9         | 47.37%  |
| 8192  | 4         | 21.05%  |
| 16384 | 3         | 15.79%  |
| 2048  | 3         | 15.79%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 9         | 45%     |
| 1600  | 4         | 20%     |
| 3200  | 2         | 10%     |
| 2400  | 1         | 5%      |
| 2133  | 1         | 5%      |
| 2048  | 1         | 5%      |
| 1334  | 1         | 5%      |
| 1066  | 1         | 5%      |

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


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| Brother MFC-T800W | 1         | 100%    |

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
| Chicony Electronics                    | 9         | 23.68%  |
| Apple                                  | 5         | 13.16%  |
| Quanta                                 | 4         | 10.53%  |
| Suyin                                  | 3         | 7.89%   |
| Realtek Semiconductor                  | 3         | 7.89%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 7.89%   |
| Sunplus Innovation Technology          | 2         | 5.26%   |
| Microdia                               | 2         | 5.26%   |
| Luxvisions Innotech Limited            | 2         | 5.26%   |
| webcam                                 | 1         | 2.63%   |
| Syntek                                 | 1         | 2.63%   |
| Primax Electronics                     | 1         | 2.63%   |
| Importek                               | 1         | 2.63%   |
| Acer                                   | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Apple FaceTime HD Camera                                        | 4         | 10.53%  |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 2         | 5.26%   |
| Realtek HD WebCam                                               | 2         | 5.26%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 5.26%   |
| Chicony HD WebCam                                               | 2         | 5.26%   |
| webcam webcam                                                   | 1         | 2.63%   |
| Syntek EasyCamera                                               | 1         | 2.63%   |
| Suyin Asus Integrated Webcam                                    | 1         | 2.63%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                           | 1         | 2.63%   |
| Sunplus Laptop Integrated WebCam HD                             | 1         | 2.63%   |
| Realtek Integrated_Webcam_HD                                    | 1         | 2.63%   |
| Quanta HP Webcam                                                | 1         | 2.63%   |
| Quanta HD User Facing                                           | 1         | 2.63%   |
| Primax Villem                                                   | 1         | 2.63%   |
| Microdia Laptop_Integrated_Webcam_FHD                           | 1         | 2.63%   |
| Microdia Integrated Webcam                                      | 1         | 2.63%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 2.63%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1         | 2.63%   |
| Importek Webcam HD                                              | 1         | 2.63%   |
| Chicony USB2.0 Camera                                           | 1         | 2.63%   |
| Chicony HP Wide Vision HD                                       | 1         | 2.63%   |
| Chicony HP Webcam                                               | 1         | 2.63%   |
| Chicony HP Truevision HD                                        | 1         | 2.63%   |
| Chicony HP Integrated Webcam                                    | 1         | 2.63%   |
| Chicony HP HD Webcam [Fixed]                                    | 1         | 2.63%   |
| Chicony HD User Facing                                          | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 1         | 2.63%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 1         | 2.63%   |
| Acer SunplusIT Integrated Camera                                | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 3         | 50%     |
| Validity Sensors      | 1         | 16.67%  |
| Synaptics             | 1         | 16.67%  |
| STMicroelectronics    | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor | 3         | 50%     |
| Validity Sensors VFS495 Fingerprint Reader  | 1         | 16.67%  |
| Synaptics  WBDI                             | 1         | 16.67%  |
| STMicroelectronics Fingerprint Reader       | 1         | 16.67%  |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 29        | 67.44%  |
| 1     | 11        | 25.58%  |
| 2     | 3         | 6.98%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 33.33%  |
| Net/wireless          | 5         | 27.78%  |
| Graphics card         | 5         | 27.78%  |
| Sound                 | 1         | 5.56%   |
| Multimedia controller | 1         | 5.56%   |

