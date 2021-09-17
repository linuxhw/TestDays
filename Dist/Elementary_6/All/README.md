Elementary 6 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Elementary 6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_6/Desktop/README.md) and [notebooks](/Dist/Elementary_6/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Alienware     | 17                          | Notebook    | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Acer          | Aspire V3-572G              | Notebook    | [addf12cb05](https://linux-hardware.org/?probe=addf12cb05) | Sep 16, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [0c206818b9](https://linux-hardware.org/?probe=0c206818b9) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| Dell          | Latitude E7440              | Notebook    | [fc9f25eecb](https://linux-hardware.org/?probe=fc9f25eecb) | Sep 14, 2021 |
| Toshiba       | Satellite P100              | Notebook    | [bc5b605920](https://linux-hardware.org/?probe=bc5b605920) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [591ba7a77c](https://linux-hardware.org/?probe=591ba7a77c) | Sep 12, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| Lenovo        | 371C No DPK                 | All in one  | [cd0d01d653](https://linux-hardware.org/?probe=cd0d01d653) | Sep 11, 2021 |
| ASUSTek       | UX303LA                     | Notebook    | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| Intel         | H61                         | Desktop     | [0010dbcb5e](https://linux-hardware.org/?probe=0010dbcb5e) | Sep 10, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [f373a049e2](https://linux-hardware.org/?probe=f373a049e2) | Sep 10, 2021 |
| HP            | 8767 A                      | Desktop     | [7f022c67ac](https://linux-hardware.org/?probe=7f022c67ac) | Sep 09, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [6e97abfd44](https://linux-hardware.org/?probe=6e97abfd44) | Sep 09, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [0614925ee7](https://linux-hardware.org/?probe=0614925ee7) | Sep 08, 2021 |
| Gateway       | NV54 Series                 | Notebook    | [fcf57528ed](https://linux-hardware.org/?probe=fcf57528ed) | Sep 08, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [dfb9789af2](https://linux-hardware.org/?probe=dfb9789af2) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | Notebook    | [27828e1dfb](https://linux-hardware.org/?probe=27828e1dfb) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | Notebook    | [4c1200e7cf](https://linux-hardware.org/?probe=4c1200e7cf) | Sep 07, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [797db05baf](https://linux-hardware.org/?probe=797db05baf) | Sep 06, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [ebd997cb1a](https://linux-hardware.org/?probe=ebd997cb1a) | Sep 05, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [a5d7b5a10e](https://linux-hardware.org/?probe=a5d7b5a10e) | Sep 05, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [91ecd39f66](https://linux-hardware.org/?probe=91ecd39f66) | Sep 05, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [633441bc2b](https://linux-hardware.org/?probe=633441bc2b) | Sep 05, 2021 |
| Medion        | AKOYA THE TOUCH 10          | Notebook    | [d49d62a2f5](https://linux-hardware.org/?probe=d49d62a2f5) | Sep 04, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c9476d5d06](https://linux-hardware.org/?probe=c9476d5d06) | Sep 02, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| HP            | 86ED A01                    | All in one  | [78778f22a2](https://linux-hardware.org/?probe=78778f22a2) | Sep 01, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [adbb6a690a](https://linux-hardware.org/?probe=adbb6a690a) | Sep 01, 2021 |
| Dell          | Latitude 3580               | Notebook    | [2befbbba9e](https://linux-hardware.org/?probe=2befbbba9e) | Aug 31, 2021 |
| HP            | Pavilion g6                 | Notebook    | [7dba3c201c](https://linux-hardware.org/?probe=7dba3c201c) | Aug 31, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [0c05ab5b21](https://linux-hardware.org/?probe=0c05ab5b21) | Aug 30, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| ASRock        | H81TM-ITX R2.0              | Desktop     | [4f04e7309e](https://linux-hardware.org/?probe=4f04e7309e) | Aug 30, 2021 |
| HP            | ProBook 4320s               | Notebook    | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| eMachines     | G525                        | Notebook    | [d64e29475f](https://linux-hardware.org/?probe=d64e29475f) | Aug 29, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [aeec497ed8](https://linux-hardware.org/?probe=aeec497ed8) | Aug 28, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [df0d3e8ac4](https://linux-hardware.org/?probe=df0d3e8ac4) | Aug 26, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [d0ff1c6977](https://linux-hardware.org/?probe=d0ff1c6977) | Aug 25, 2021 |
| HP            | 86ED A01                    | All in one  | [402a8e492c](https://linux-hardware.org/?probe=402a8e492c) | Aug 24, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [db1ef28e92](https://linux-hardware.org/?probe=db1ef28e92) | Aug 20, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [fae546f5cb](https://linux-hardware.org/?probe=fae546f5cb) | Aug 20, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [e9bec90506](https://linux-hardware.org/?probe=e9bec90506) | Aug 19, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [1176a287c7](https://linux-hardware.org/?probe=1176a287c7) | Aug 19, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [9d7628068c](https://linux-hardware.org/?probe=9d7628068c) | Aug 19, 2021 |
| Dell          | XPS L321X                   | Notebook    | [34d7fb6cbb](https://linux-hardware.org/?probe=34d7fb6cbb) | Aug 18, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [f30480d463](https://linux-hardware.org/?probe=f30480d463) | Aug 17, 2021 |
| HP            | Notebook                    | Notebook    | [a3058005e3](https://linux-hardware.org/?probe=a3058005e3) | Aug 16, 2021 |
| HP            | Notebook                    | Notebook    | [7800ef9623](https://linux-hardware.org/?probe=7800ef9623) | Aug 16, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [fa6c69671f](https://linux-hardware.org/?probe=fa6c69671f) | Aug 16, 2021 |
| ASUSTek       | TUF GAMING B450M-PRO II     | Desktop     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [a8d4959fde](https://linux-hardware.org/?probe=a8d4959fde) | Aug 14, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [a6b2c12401](https://linux-hardware.org/?probe=a6b2c12401) | Aug 14, 2021 |
| Dell          | Precision 5760              | Notebook    | [824e5e7dad](https://linux-hardware.org/?probe=824e5e7dad) | Aug 14, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | Notebook    | [dcfc87a32f](https://linux-hardware.org/?probe=dcfc87a32f) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | Notebook    | [e354646c04](https://linux-hardware.org/?probe=e354646c04) | Aug 13, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4e6f050b43](https://linux-hardware.org/?probe=4e6f050b43) | Aug 10, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [76a8d2c20a](https://linux-hardware.org/?probe=76a8d2c20a) | Jul 29, 2021 |
| Google        | Cave                        | Notebook    | [e2617f0c2d](https://linux-hardware.org/?probe=e2617f0c2d) | Jul 25, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [7124417642](https://linux-hardware.org/?probe=7124417642) | Jul 22, 2021 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [0447155931](https://linux-hardware.org/?probe=0447155931) | Jul 02, 2021 |
| Acer          | Swift SF314-55G             | Notebook    | [c371b46cbe](https://linux-hardware.org/?probe=c371b46cbe) | Jun 30, 2021 |
| Acer          | Swift SF315-41              | Notebook    | [8df5e13fc0](https://linux-hardware.org/?probe=8df5e13fc0) | Jun 18, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [c5d0611f79](https://linux-hardware.org/?probe=c5d0611f79) | Jun 13, 2021 |
| Acer          | Swift SF314-55G             | Notebook    | [4e5cf8aa1e](https://linux-hardware.org/?probe=4e5cf8aa1e) | Jun 13, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| Acer          | ConceptD CN315-71P          | Notebook    | [5ecea84320](https://linux-hardware.org/?probe=5ecea84320) | May 15, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e177523d81](https://linux-hardware.org/?probe=e177523d81) | May 03, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [a208e8a358](https://linux-hardware.org/?probe=a208e8a358) | May 01, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [e87a073ae8](https://linux-hardware.org/?probe=e87a073ae8) | Mar 18, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [1e31858e51](https://linux-hardware.org/?probe=1e31858e51) | Mar 09, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [f7d949f5a7](https://linux-hardware.org/?probe=f7d949f5a7) | Dec 23, 2020 |
| HP            | 8433 11                     | Desktop     | [691ef58a05](https://linux-hardware.org/?probe=691ef58a05) | Dec 09, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.11.0-27-generic     | 31        | 46.27%  |
| 5.11.0-25-generic     | 15        | 22.39%  |
| 5.11.0-34-generic     | 6         | 8.96%   |
| 5.8.0-50-generic      | 5         | 7.46%   |
| 5.8.0-55-generic      | 3         | 4.48%   |
| 5.8.0-63-generic      | 2         | 2.99%   |
| 5.8.0-53-generic      | 1         | 1.49%   |
| 5.8.0-44-generic      | 1         | 1.49%   |
| 5.4.0-58-generic      | 1         | 1.49%   |
| 5.4.0-56-generic      | 1         | 1.49%   |
| 5.11.0-051100-generic | 1         | 1.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 53        | 79.1%   |
| 5.8.0   | 12        | 17.91%  |
| 5.4.0   | 2         | 2.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 53        | 79.1%   |
| 5.8     | 12        | 17.91%  |
| 5.4     | 2         | 2.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 67        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Pantheon   | 57        | 85.07%  |
| Unknown    | 6         | 8.96%   |
| GNOME      | 2         | 2.99%   |
| X-Cinnamon | 1         | 1.49%   |
| MATE       | 1         | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 67        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 51        | 76.12%  |
| TDM     | 7         | 10.45%  |
| LightDM | 7         | 10.45%  |
| GDM     | 2         | 2.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 34        | 50.75%  |
| es_ES | 6         | 8.96%   |
| de_DE | 5         | 7.46%   |
| pt_BR | 4         | 5.97%   |
| en_GB | 3         | 4.48%   |
| zh_CN | 2         | 2.99%   |
| fr_FR | 2         | 2.99%   |
| en_CA | 2         | 2.99%   |
| ca_ES | 2         | 2.99%   |
| ru_RU | 1         | 1.49%   |
| it_IT | 1         | 1.49%   |
| hr_HR | 1         | 1.49%   |
| fr_BE | 1         | 1.49%   |
| es_MX | 1         | 1.49%   |
| en_AU | 1         | 1.49%   |
| cs_CZ | 1         | 1.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 43        | 64.18%  |
| BIOS | 24        | 35.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 62        | 92.54%  |
| Overlay | 3         | 4.48%   |
| Btrfs   | 2         | 2.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 51        | 76.12%  |
| GPT     | 12        | 17.91%  |
| MBR     | 4         | 5.97%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 92.54%  |
| Yes       | 5         | 7.46%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 82.09%  |
| Yes       | 12        | 17.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 19        | 28.36%  |
| ASUSTek Computer    | 9         | 13.43%  |
| Acer                | 8         | 11.94%  |
| Dell                | 5         | 7.46%   |
| Lenovo              | 4         | 5.97%   |
| Gigabyte Technology | 4         | 5.97%   |
| Apple               | 4         | 5.97%   |
| Toshiba             | 2         | 2.99%   |
| ASRock              | 2         | 2.99%   |
| TUXEDO              | 1         | 1.49%   |
| Sony                | 1         | 1.49%   |
| MSI                 | 1         | 1.49%   |
| Microsoft           | 1         | 1.49%   |
| Medion              | 1         | 1.49%   |
| Intel               | 1         | 1.49%   |
| Gateway             | 1         | 1.49%   |
| eMachines           | 1         | 1.49%   |
| Alienware           | 1         | 1.49%   |
| Acidanthera         | 1         | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| HP Pavilion Notebook                       | 2         | 2.99%   |
| Apple MacBookPro9,1                        | 2         | 2.99%   |
| TUXEDO InfinityBook S 14 Gen6              | 1         | 1.49%   |
| Toshiba Satellite P100                     | 1         | 1.49%   |
| Toshiba Satellite L500                     | 1         | 1.49%   |
| Sony Serie VJC14                           | 1         | 1.49%   |
| MSI MS-7B79                                | 1         | 1.49%   |
| Microsoft Surface Pro 4                    | 1         | 1.49%   |
| Medion AKOYA THE TOUCH 10                  | 1         | 1.49%   |
| Lenovo V330-15IKB 81AX                     | 1         | 1.49%   |
| Lenovo ThinkPad X201 3249CTO               | 1         | 1.49%   |
| Lenovo IdeaPad 330-15IKB 81FE              | 1         | 1.49%   |
| Lenovo IdeaCentre AIO 3 24ARE05 F0EW00FLSC | 1         | 1.49%   |
| Intel H61                                  | 1         | 1.49%   |
| HP Stream Laptop 14-cb1xxx                 | 1         | 1.49%   |
| HP ProBook 450 G8 Notebook PC              | 1         | 1.49%   |
| HP ProBook 4320s                           | 1         | 1.49%   |
| HP Pavilion Gaming Laptop 15-ec0xxx        | 1         | 1.49%   |
| HP Pavilion Gaming Desktop TG01-1xxx       | 1         | 1.49%   |
| HP Pavilion g6                             | 1         | 1.49%   |
| HP Pavilion Desktop 590-p0xxx              | 1         | 1.49%   |
| HP Pavilion All-in-One 24-k0xxx            | 1         | 1.49%   |
| HP Pavilion Aero Laptop 13-be0xxx          | 1         | 1.49%   |
| HP Notebook                                | 1         | 1.49%   |
| HP Laptop 15-bs1xx                         | 1         | 1.49%   |
| HP Laptop 15-bs0xx                         | 1         | 1.49%   |
| HP Laptop 14-dq1xxx                        | 1         | 1.49%   |
| HP ENVY x360 Convertible 15-ee0xxx         | 1         | 1.49%   |
| HP ENVY x360 Convertible 13-ag0xxx         | 1         | 1.49%   |
| HP EliteBook Folio 9470m                   | 1         | 1.49%   |
| HP EliteBook 840 G3                        | 1         | 1.49%   |
| Gigabyte X570 I AORUS PRO WIFI             | 1         | 1.49%   |
| Gigabyte H310M M.2 2.0                     | 1         | 1.49%   |
| Gigabyte F2A55M-HD2                        | 1         | 1.49%   |
| Gigabyte B450M DS3H V2                     | 1         | 1.49%   |
| Gateway NV54 Series                        | 1         | 1.49%   |
| eMachines G525                             | 1         | 1.49%   |
| Dell XPS L321X                             | 1         | 1.49%   |
| Dell Precision 5760                        | 1         | 1.49%   |
| Dell Latitude E7440                        | 1         | 1.49%   |
| Dell Latitude 3580                         | 1         | 1.49%   |
| Dell Inspiron 3583                         | 1         | 1.49%   |
| ASUS UX303LA                               | 1         | 1.49%   |
| ASUS TUF GAMING B550M-PLUS                 | 1         | 1.49%   |
| ASUS TUF GAMING B450M-PRO II               | 1         | 1.49%   |
| ASUS ROG STRIX Z590-F GAMING WIFI          | 1         | 1.49%   |
| ASUS ROG STRIX B450-I GAMING               | 1         | 1.49%   |
| ASUS P6X58D-E                              | 1         | 1.49%   |
| ASUS P5KPL-AM SE                           | 1         | 1.49%   |
| ASUS M5A99X EVO R2.0                       | 1         | 1.49%   |
| ASUS M5A78L-M LX/BR                        | 1         | 1.49%   |
| ASRock H81TM-ITX R2.0                      | 1         | 1.49%   |
| ASRock B450 Pro4                           | 1         | 1.49%   |
| Apple MacBookPro8,2                        | 1         | 1.49%   |
| Apple MacBookPro8,1                        | 1         | 1.49%   |
| Alienware 17                               | 1         | 1.49%   |
| Acidanthera iMacPro1,1                     | 1         | 1.49%   |
| Acer Swift SF315-41                        | 1         | 1.49%   |
| Acer Swift SF314-55G                       | 1         | 1.49%   |
| Acer ConceptD CN315-71P                    | 1         | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| HP Pavilion          | 8         | 11.94%  |
| Acer Aspire          | 5         | 7.46%   |
| HP Laptop            | 3         | 4.48%   |
| Toshiba Satellite    | 2         | 2.99%   |
| HP ProBook           | 2         | 2.99%   |
| HP ENVY              | 2         | 2.99%   |
| HP EliteBook         | 2         | 2.99%   |
| Dell Latitude        | 2         | 2.99%   |
| ASUS TUF             | 2         | 2.99%   |
| ASUS ROG             | 2         | 2.99%   |
| Apple MacBookPro9    | 2         | 2.99%   |
| Apple MacBookPro8    | 2         | 2.99%   |
| Acer Swift           | 2         | 2.99%   |
| TUXEDO InfinityBook  | 1         | 1.49%   |
| Sony Serie           | 1         | 1.49%   |
| MSI MS-7B79          | 1         | 1.49%   |
| Microsoft Surface    | 1         | 1.49%   |
| Medion AKOYA         | 1         | 1.49%   |
| Lenovo V330-15IKB    | 1         | 1.49%   |
| Lenovo ThinkPad      | 1         | 1.49%   |
| Lenovo IdeaPad       | 1         | 1.49%   |
| Lenovo IdeaCentre    | 1         | 1.49%   |
| Intel H61            | 1         | 1.49%   |
| HP Stream            | 1         | 1.49%   |
| HP Notebook          | 1         | 1.49%   |
| Gigabyte X570        | 1         | 1.49%   |
| Gigabyte H310M       | 1         | 1.49%   |
| Gigabyte F2A55M-HD2  | 1         | 1.49%   |
| Gigabyte B450M       | 1         | 1.49%   |
| Gateway NV54         | 1         | 1.49%   |
| eMachines G525       | 1         | 1.49%   |
| Dell XPS             | 1         | 1.49%   |
| Dell Precision       | 1         | 1.49%   |
| Dell Inspiron        | 1         | 1.49%   |
| ASUS UX303LA         | 1         | 1.49%   |
| ASUS P6X58D-E        | 1         | 1.49%   |
| ASUS P5KPL-AM        | 1         | 1.49%   |
| ASUS M5A99X          | 1         | 1.49%   |
| ASUS M5A78L-M        | 1         | 1.49%   |
| ASRock H81TM-ITX     | 1         | 1.49%   |
| ASRock B450          | 1         | 1.49%   |
| Alienware 17         | 1         | 1.49%   |
| Acidanthera iMacPro1 | 1         | 1.49%   |
| Acer ConceptD        | 1         | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 16        | 23.88%  |
| 2020    | 10        | 14.93%  |
| 2019    | 10        | 14.93%  |
| 2018    | 8         | 11.94%  |
| 2013    | 5         | 7.46%   |
| 2015    | 4         | 5.97%   |
| 2017    | 3         | 4.48%   |
| 2012    | 3         | 4.48%   |
| 2010    | 3         | 4.48%   |
| 2014    | 2         | 2.99%   |
| 2009    | 2         | 2.99%   |
| Unknown | 1         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 43        | 64.18%  |
| Desktop     | 18        | 26.87%  |
| All in one  | 3         | 4.48%   |
| Convertible | 2         | 2.99%   |
| Tablet      | 1         | 1.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 53        | 79.1%   |
| Enabled  | 14        | 20.9%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 67        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 20        | 29.85%  |
| 16.01-24.0 | 15        | 22.39%  |
| 3.01-4.0   | 11        | 16.42%  |
| 32.01-64.0 | 10        | 14.93%  |
| 8.01-16.0  | 9         | 13.43%  |
| 24.01-32.0 | 1         | 1.49%   |
| 1.01-2.0   | 1         | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 23        | 33.82%  |
| 1.01-2.0  | 21        | 30.88%  |
| 3.01-4.0  | 14        | 20.59%  |
| 4.01-8.0  | 9         | 13.24%  |
| 8.01-16.0 | 1         | 1.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 61.19%  |
| 2      | 19        | 28.36%  |
| 3      | 3         | 4.48%   |
| 4      | 2         | 2.99%   |
| 6      | 1         | 1.49%   |
| 5      | 1         | 1.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 79.1%   |
| Yes       | 14        | 20.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 83.58%  |
| No        | 11        | 16.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 83.58%  |
| No        | 11        | 16.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 77.94%  |
| No        | 15        | 22.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 9         | 13.43%  |
| India        | 5         | 7.46%   |
| Germany      | 5         | 7.46%   |
| Brazil       | 5         | 7.46%   |
| UK           | 4         | 5.97%   |
| Argentina    | 4         | 5.97%   |
| Spain        | 2         | 2.99%   |
| Russia       | 2         | 2.99%   |
| Netherlands  | 2         | 2.99%   |
| Mexico       | 2         | 2.99%   |
| Guatemala    | 2         | 2.99%   |
| Czechia      | 2         | 2.99%   |
| Canada       | 2         | 2.99%   |
| Belgium      | 2         | 2.99%   |
| Switzerland  | 1         | 1.49%   |
| South Africa | 1         | 1.49%   |
| Serbia       | 1         | 1.49%   |
| Myanmar      | 1         | 1.49%   |
| Latvia       | 1         | 1.49%   |
| Kenya        | 1         | 1.49%   |
| Kazakhstan   | 1         | 1.49%   |
| Japan        | 1         | 1.49%   |
| Italy        | 1         | 1.49%   |
| Indonesia    | 1         | 1.49%   |
| Guyana       | 1         | 1.49%   |
| France       | 1         | 1.49%   |
| Finland      | 1         | 1.49%   |
| Estonia      | 1         | 1.49%   |
| Denmark      | 1         | 1.49%   |
| Croatia      | 1         | 1.49%   |
| China        | 1         | 1.49%   |
| Austria      | 1         | 1.49%   |
| Australia    | 1         | 1.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Guatemala City           | 2         | 2.94%   |
| Znojmo                   | 1         | 1.47%   |
| Vienna                   | 1         | 1.47%   |
| Vernon                   | 1         | 1.47%   |
| Ullastrell               | 1         | 1.47%   |
| Toledo                   | 1         | 1.47%   |
| Tokyo                    | 1         | 1.47%   |
| Thousand Oaks            | 1         | 1.47%   |
| Tallinn                  | 1         | 1.47%   |
| Stevenage                | 1         | 1.47%   |
| Staropyshminsk           | 1         | 1.47%   |
| Sinop                    | 1         | 1.47%   |
| S??o Pedro               | 1         | 1.47%   |
| S??o Paulo               | 1         | 1.47%   |
| Santa Monica             | 1         | 1.47%   |
| Sant Carles de la Rapita | 1         | 1.47%   |
| Samobor                  | 1         | 1.47%   |
| Sakai                    | 1         | 1.47%   |
| Sacramento               | 1         | 1.47%   |
| Rosario                  | 1         | 1.47%   |
| Roermond                 | 1         | 1.47%   |
| Rio de Janeiro           | 1         | 1.47%   |
| Rheinberg                | 1         | 1.47%   |
| Quer?©taro City          | 1         | 1.47%   |
| Potsdam                  | 1         | 1.47%   |
| Perth                    | 1         | 1.47%   |
| Peekskill                | 1         | 1.47%   |
| Patna                    | 1         | 1.47%   |
| Paris                    | 1         | 1.47%   |
| Odense                   | 1         | 1.47%   |
| Northridge               | 1         | 1.47%   |
| Nairobi                  | 1         | 1.47%   |
| Naaldwijk                | 1         | 1.47%   |
| Moss Point               | 1         | 1.47%   |
| Moscow                   | 1         | 1.47%   |
| Morelia                  | 1         | 1.47%   |
| Montreal                 | 1         | 1.47%   |
| Monheim am Rhein         | 1         | 1.47%   |
| Milan                    | 1         | 1.47%   |
| Medan                    | 1         | 1.47%   |
| Mandalay                 | 1         | 1.47%   |
| Lucknow                  | 1         | 1.47%   |
| Len?«nskoe               | 1         | 1.47%   |
| Lausanne                 | 1         | 1.47%   |
| Lanaken                  | 1         | 1.47%   |
| Kovin                    | 1         | 1.47%   |
| Koraput                  | 1         | 1.47%   |
| Klaukkala                | 1         | 1.47%   |
| Johannesburg             | 1         | 1.47%   |
| Jaunmarupe               | 1         | 1.47%   |
| Jalandhar                | 1         | 1.47%   |
| Horovice                 | 1         | 1.47%   |
| Hollern                  | 1         | 1.47%   |
| Hephzibah                | 1         | 1.47%   |
| Georgetown               | 1         | 1.47%   |
| Curitiba                 | 1         | 1.47%   |
| Chattanooga              | 1         | 1.47%   |
| C??rdoba                 | 1         | 1.47%   |
| Camberwell               | 1         | 1.47%   |
| Buenos Aires             | 1         | 1.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 20        | 23     | 20.41%  |
| Samsung Electronics       | 18        | 22     | 18.37%  |
| Seagate                   | 8         | 11     | 8.16%   |
| Kingston                  | 8         | 8      | 8.16%   |
| Sandisk                   | 7         | 7      | 7.14%   |
| Toshiba                   | 6         | 6      | 6.12%   |
| Unknown                   | 4         | 4      | 4.08%   |
| Hitachi                   | 3         | 3      | 3.06%   |
| Crucial                   | 3         | 3      | 3.06%   |
| Phison                    | 2         | 2      | 2.04%   |
| Micron/Crucial Technology | 2         | 3      | 2.04%   |
| Micron Technology         | 2         | 2      | 2.04%   |
| Intel                     | 2         | 2      | 2.04%   |
| HGST                      | 2         | 2      | 2.04%   |
| Gigabyte Technology       | 2         | 2      | 2.04%   |
| USB3.1                    | 1         | 1      | 1.02%   |
| Transcend                 | 1         | 2      | 1.02%   |
| StoreJet                  | 1         | 1      | 1.02%   |
| SK Hynix                  | 1         | 1      | 1.02%   |
| OCZ                       | 1         | 1      | 1.02%   |
| Mercury                   | 1         | 1      | 1.02%   |
| LITEONIT                  | 1         | 1      | 1.02%   |
| KIOXIA                    | 1         | 1      | 1.02%   |
| CLOVER                    | 1         | 1      | 1.02%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 4         | 3.77%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 1.89%   |
| WDC WD10SPZX-21Z10T0 1TB             | 2         | 1.89%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 1.89%   |
| Toshiba NVMe SSD Drive 256GB         | 2         | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.89%   |
| Samsung NVMe SSD Drive 500GB         | 2         | 1.89%   |
| Intel NVMe SSD Drive 512GB           | 2         | 1.89%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.94%   |
| WDC WD5000BPKT-75PK4T0 500GB         | 1         | 0.94%   |
| WDC WD5000AAKX-001CA0 500GB          | 1         | 0.94%   |
| WDC WD3200AAJS-56B4A0 320GB          | 1         | 0.94%   |
| WDC WD20SPZX-21UA7T0 2TB             | 1         | 0.94%   |
| WDC WD20EARX-00PASB0 2TB             | 1         | 0.94%   |
| WDC WD10SPZX-24Z10T0 1TB             | 1         | 0.94%   |
| WDC WD10SPZX-22Z10T1 1TB             | 1         | 0.94%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.94%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 0.94%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 0.94%   |
| WDC WD10EZEX-22MFCA0 1TB             | 1         | 0.94%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.94%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1         | 0.94%   |
| WDC PC SN720 SDAPNTW-256G-1014 256GB | 1         | 0.94%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB | 1         | 0.94%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB | 1         | 0.94%   |
| USB3.1 Disk 500GB                    | 1         | 0.94%   |
| Unknown xD/SD/M.S.                   | 1         | 0.94%   |
| Unknown TA2964  64GB                 | 1         | 0.94%   |
| Unknown MMC Card  500GB              | 1         | 0.94%   |
| Unknown MMC Card  128GB              | 1         | 0.94%   |
| Transcend TS256GSSD230S 256GB        | 1         | 0.94%   |
| Toshiba MQ01ABD100V -63 1TB          | 1         | 0.94%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.94%   |
| Toshiba MK5065GSXF 500GB             | 1         | 0.94%   |
| Toshiba DT01ACA100 1TB               | 1         | 0.94%   |
| StoreJet Transcend 512GB             | 1         | 0.94%   |
| SK Hynix NVMe SSD Drive 512GB        | 1         | 0.94%   |
| Seagate ST940210AS 40GB              | 1         | 0.94%   |
| Seagate ST9250315AS 250GB            | 1         | 0.94%   |
| Seagate ST3000DM008-2DM166 3TB       | 1         | 0.94%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 0.94%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 0.94%   |
| Seagate ST1000DX001-1CM162 1TB       | 1         | 0.94%   |
| Seagate NVMe SSD Drive 2TB           | 1         | 0.94%   |
| SanDisk SDSSDA480G 480GB             | 1         | 0.94%   |
| SanDisk SDSSDA-1T00 1TB              | 1         | 0.94%   |
| SanDisk SD7SB3Q256G1002 256GB SSD    | 1         | 0.94%   |
| SanDisk SD7SB3Q128G1001 128GB SSD    | 1         | 0.94%   |
| Sandisk NVMe SSD Drive 500GB         | 1         | 0.94%   |
| Sandisk NVMe SSD Drive 256GB         | 1         | 0.94%   |
| Sandisk NVMe SSD Drive 1TB           | 1         | 0.94%   |
| Samsung SSD SM841 mSATA 128GB        | 1         | 0.94%   |
| Samsung SSD 980 PRO 1TB              | 1         | 0.94%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 0.94%   |
| Samsung SSD 960 EVO 500GB            | 1         | 0.94%   |
| Samsung SSD 870 QVO 1TB              | 1         | 0.94%   |
| Samsung SSD 860 EVO 2TB              | 1         | 0.94%   |
| Samsung SSD 860 EVO 250GB            | 1         | 0.94%   |
| Samsung SSD 850 EVO 250GB            | 1         | 0.94%   |
| Samsung SSD 840 Series 500GB         | 1         | 0.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 18     | 47.06%  |
| Seagate             | 7         | 10     | 20.59%  |
| Toshiba             | 4         | 4      | 11.76%  |
| Hitachi             | 3         | 3      | 8.82%   |
| Samsung Electronics | 2         | 2      | 5.88%   |
| HGST                | 2         | 2      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 31.03%  |
| Kingston            | 6         | 6      | 20.69%  |
| SanDisk             | 4         | 4      | 13.79%  |
| Crucial             | 3         | 3      | 10.34%  |
| WDC                 | 2         | 2      | 6.9%    |
| Transcend           | 1         | 2      | 3.45%   |
| StoreJet            | 1         | 1      | 3.45%   |
| OCZ                 | 1         | 1      | 3.45%   |
| Mercury             | 1         | 1      | 3.45%   |
| LITEONIT            | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 34        | 39     | 37.78%  |
| NVMe    | 26        | 34     | 28.89%  |
| SSD     | 24        | 31     | 26.67%  |
| MMC     | 3         | 3      | 3.33%   |
| Unknown | 3         | 3      | 3.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 49        | 69     | 60.49%  |
| NVMe | 26        | 34     | 32.1%   |
| SAS  | 3         | 4      | 3.7%    |
| MMC  | 3         | 3      | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 39     | 54.24%  |
| 0.51-1.0   | 23        | 26     | 38.98%  |
| 1.01-2.0   | 3         | 3      | 5.08%   |
| 2.01-3.0   | 1         | 2      | 1.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 22        | 32.84%  |
| 251-500    | 20        | 29.85%  |
| 501-1000   | 8         | 11.94%  |
| 1001-2000  | 7         | 10.45%  |
| 21-50      | 3         | 4.48%   |
| 1-20       | 3         | 4.48%   |
| 51-100     | 3         | 4.48%   |
| 2001-3000  | 1         | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 37        | 55.22%  |
| 21-50     | 10        | 14.93%  |
| 51-100    | 10        | 14.93%  |
| 101-250   | 4         | 5.97%   |
| 251-500   | 3         | 4.48%   |
| 1001-2000 | 2         | 2.99%   |
| 501-1000  | 1         | 1.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPKT-75PK4T0 500GB      | 1         | 1      | 25%     |
| WDC WD3200AAJS-56B4A0 320GB       | 1         | 1      | 25%     |
| WDC WD10EZEX-00KUWA0 1TB          | 1         | 1      | 25%     |
| SanDisk SD7SB3Q256G1002 256GB SSD | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 75%     |
| SanDisk | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 3         | 3      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 75%     |
| SSD  | 1         | 1      | 25%     |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 54        | 83     | 73.97%  |
| Works    | 15        | 23     | 20.55%  |
| Malfunc  | 4         | 4      | 5.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 47        | 49.47%  |
| AMD                          | 15        | 15.79%  |
| Samsung Electronics          | 9         | 9.47%   |
| Sandisk                      | 6         | 6.32%   |
| Phison Electronics           | 3         | 3.16%   |
| Toshiba America Info Systems | 2         | 2.11%   |
| Micron/Crucial Technology    | 2         | 2.11%   |
| Micron Technology            | 2         | 2.11%   |
| Marvell Technology Group     | 2         | 2.11%   |
| Kingston Technology Company  | 2         | 2.11%   |
| ASMedia Technology           | 2         | 2.11%   |
| SK Hynix                     | 1         | 1.05%   |
| Seagate Technology           | 1         | 1.05%   |
| KIOXIA                       | 1         | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 10        | 9.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 9         | 8.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 4         | 3.74%   |
| AMD 400 Series Chipset SATA Controller                                                 | 4         | 3.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 2.8%    |
| Samsung NVMe SSD Controller 980                                                        | 3         | 2.8%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 2.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 2.8%    |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 2         | 1.87%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 2         | 1.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 1.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 1.87%   |
| Phison PS5013 E13 NVMe Controller                                                      | 2         | 1.87%   |
| Micron Non-Volatile memory controller                                                  | 2         | 1.87%   |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 1.87%   |
| Intel SATA Controller [RAID mode]                                                      | 2         | 1.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 2         | 1.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 1.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.87%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 2         | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 1.87%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 1         | 0.93%   |
| Toshiba America Info Systems NVMe Controller                                           | 1         | 0.93%   |
| SK Hynix NVMe SSD Controller                                                           | 1         | 0.93%   |
| Seagate FireCuda 510 SSD                                                               | 1         | 0.93%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.93%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.93%   |
| Phison E12 NVMe Controller                                                             | 1         | 0.93%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 0.93%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 0.93%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                             | 1         | 0.93%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                           | 1         | 0.93%   |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 0.93%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 0.93%   |
| Intel SSD 660P Series                                                                  | 1         | 0.93%   |
| Intel Non-Volatile memory controller                                                   | 1         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 0.93%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                              | 1         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.93%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                             | 1         | 0.93%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                             | 1         | 0.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 0.93%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 1         | 0.93%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                               | 1         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 1         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 0.93%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 0.93%   |
| AMD FCH IDE Controller                                                                 | 1         | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                                 | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 47        | 52.22%  |
| NVMe | 26        | 28.89%  |
| RAID | 9         | 10%     |
| IDE  | 8         | 8.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 49        | 73.13%  |
| AMD    | 18        | 26.87%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor             | 4         | 5.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 3         | 4.48%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz    | 2         | 2.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 2         | 2.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 2         | 2.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz              | 2         | 2.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 2         | 2.99%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 2         | 2.99%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 2.99%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2         | 2.99%   |
| Intel Xeon W-11855M CPU @ 3.20GHz              | 1         | 1.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 1         | 1.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 1.49%   |
| Intel Core i7-4930K CPU @ 3.40GHz              | 1         | 1.49%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz             | 1         | 1.49%   |
| Intel Core i7-4510U CPU @ 2.00GHz              | 1         | 1.49%   |
| Intel Core i7-3720QM CPU @ 2.60GHz             | 1         | 1.49%   |
| Intel Core i7-3687U CPU @ 2.10GHz              | 1         | 1.49%   |
| Intel Core i7-3615QM CPU @ 2.30GHz             | 1         | 1.49%   |
| Intel Core i7-2637M CPU @ 1.70GHz              | 1         | 1.49%   |
| Intel Core i7-2635QM CPU @ 2.00GHz             | 1         | 1.49%   |
| Intel Core i7-10700F CPU @ 2.90GHz             | 1         | 1.49%   |
| Intel Core i7 CPU 950 @ 3.07GHz                | 1         | 1.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 1         | 1.49%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1         | 1.49%   |
| Intel Core i5-4300U CPU @ 1.90GHz              | 1         | 1.49%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 1         | 1.49%   |
| Intel Core i5-2435M CPU @ 2.40GHz              | 1         | 1.49%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1         | 1.49%   |
| Intel Core i5-10400T CPU @ 2.00GHz             | 1         | 1.49%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz             | 1         | 1.49%   |
| Intel Core i5 CPU M 520 @ 2.40GHz              | 1         | 1.49%   |
| Intel Core i3 CPU M 350 @ 2.27GHz              | 1         | 1.49%   |
| Intel Core 2 Quad CPU Q9500 @ 2.83GHz          | 1         | 1.49%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz           | 1         | 1.49%   |
| Intel Core 2 CPU T5500 @ 1.66GHz               | 1         | 1.49%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 1         | 1.49%   |
| Intel Celeron G4930 CPU @ 3.20GHz              | 1         | 1.49%   |
| Intel Celeron CPU N3050 @ 1.60GHz              | 1         | 1.49%   |
| Intel Celeron CPU N2807 @ 1.58GHz              | 1         | 1.49%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 1         | 1.49%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz        | 1         | 1.49%   |
| AMD Ryzen 7 4800U with Radeon Graphics         | 1         | 1.49%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 1         | 1.49%   |
| AMD Ryzen 7 2700U with Radeon Vega Mobile Gfx  | 1         | 1.49%   |
| AMD Ryzen 5 5600U with Radeon Graphics         | 1         | 1.49%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx  | 1         | 1.49%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1         | 1.49%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx  | 1         | 1.49%   |
| AMD Phenom II N660 Dual-Core Processor         | 1         | 1.49%   |
| AMD FX-8320 Eight-Core Processor               | 1         | 1.49%   |
| AMD FX-6100 Six-Core Processor                 | 1         | 1.49%   |
| AMD A4-4000 APU with Radeon HD Graphics        | 1         | 1.49%   |
| AMD A10-9700 RADEON R7, 10 COMPUTE CORES 4C+6G | 1         | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 18        | 26.87%  |
| Intel Core i7           | 16        | 23.88%  |
| AMD Ryzen 7             | 7         | 10.45%  |
| AMD Ryzen 5             | 6         | 8.96%   |
| Other                   | 4         | 5.97%   |
| Intel Celeron           | 4         | 5.97%   |
| Intel Pentium Dual-Core | 2         | 2.99%   |
| AMD FX                  | 2         | 2.99%   |
| Intel Xeon              | 1         | 1.49%   |
| Intel Core i3           | 1         | 1.49%   |
| Intel Core 2 Quad       | 1         | 1.49%   |
| Intel Core 2 Duo        | 1         | 1.49%   |
| Intel Core 2            | 1         | 1.49%   |
| AMD Phenom II           | 1         | 1.49%   |
| AMD A4                  | 1         | 1.49%   |
| AMD A10                 | 1         | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 26        | 38.81%  |
| 4      | 23        | 34.33%  |
| 8      | 8         | 11.94%  |
| 6      | 8         | 11.94%  |
| 3      | 1         | 1.49%   |
| 1      | 1         | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 67        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 80.6%   |
| 1      | 13        | 19.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 67        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 10.45%  |
| 0x406e3    | 4         | 5.97%   |
| 0x08701021 | 4         | 5.97%   |
| 0x806ea    | 3         | 4.48%   |
| 0x806c1    | 3         | 4.48%   |
| 0x40651    | 3         | 4.48%   |
| 0x306a9    | 3         | 4.48%   |
| 0x206a7    | 3         | 4.48%   |
| 0x1067a    | 3         | 4.48%   |
| 0x906e9    | 2         | 2.99%   |
| 0x806eb    | 2         | 2.99%   |
| 0x806e9    | 2         | 2.99%   |
| 0x306c3    | 2         | 2.99%   |
| 0x20652    | 2         | 2.99%   |
| 0x08701013 | 2         | 2.99%   |
| 0x08600104 | 2         | 2.99%   |
| 0xa0671    | 1         | 1.49%   |
| 0xa0655    | 1         | 1.49%   |
| 0xa0653    | 1         | 1.49%   |
| 0x906eb    | 1         | 1.49%   |
| 0x706e5    | 1         | 1.49%   |
| 0x706a8    | 1         | 1.49%   |
| 0x6fd      | 1         | 1.49%   |
| 0x406c3    | 1         | 1.49%   |
| 0x306e4    | 1         | 1.49%   |
| 0x30678    | 1         | 1.49%   |
| 0x106a5    | 1         | 1.49%   |
| 0x0a50000c | 1         | 1.49%   |
| 0x0810100b | 1         | 1.49%   |
| 0x08101007 | 1         | 1.49%   |
| 0x0800820d | 1         | 1.49%   |
| 0x0600611a | 1         | 1.49%   |
| 0x06001119 | 1         | 1.49%   |
| 0x06000852 | 1         | 1.49%   |
| 0x0600063e | 1         | 1.49%   |
| 0x010000c8 | 1         | 1.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 17.91%  |
| Zen 2         | 8         | 11.94%  |
| Skylake       | 5         | 7.46%   |
| Haswell       | 5         | 7.46%   |
| SandyBridge   | 4         | 5.97%   |
| IvyBridge     | 4         | 5.97%   |
| TigerLake     | 3         | 4.48%   |
| Penryn        | 3         | 4.48%   |
| Zen+          | 2         | 2.99%   |
| Zen           | 2         | 2.99%   |
| Westmere      | 2         | 2.99%   |
| Silvermont    | 2         | 2.99%   |
| Piledriver    | 2         | 2.99%   |
| Icelake       | 2         | 2.99%   |
| Core          | 2         | 2.99%   |
| CometLake     | 2         | 2.99%   |
| Zen 3         | 1         | 1.49%   |
| Nehalem       | 1         | 1.49%   |
| K10           | 1         | 1.49%   |
| Goldmont plus | 1         | 1.49%   |
| Excavator     | 1         | 1.49%   |
| Bulldozer     | 1         | 1.49%   |
| Unknown       | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 50%     |
| Nvidia | 24        | 29.27%  |
| AMD    | 17        | 20.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 6.02%   |
| Intel UHD Graphics 620                                                                   | 4         | 4.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.61%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 3.61%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 2.41%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 2.41%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2         | 2.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.41%   |
| Intel HD Graphics 630                                                                    | 2         | 2.41%   |
| Intel HD Graphics 620                                                                    | 2         | 2.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.41%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 2.41%   |
| AMD Renoir                                                                               | 2         | 2.41%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 2.41%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.2%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 1.2%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 1.2%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 1.2%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 1.2%    |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 1.2%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 1.2%    |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.2%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 1.2%    |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.2%    |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.2%    |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 1.2%    |
| Nvidia GK104 [GeForce GTX 770]                                                           | 1         | 1.2%    |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1         | 1.2%    |
| Nvidia GA104GLM [RTX A3000 Mobile]                                                       | 1         | 1.2%    |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.2%    |
| Intel VGA compatible controller                                                          | 1         | 1.2%    |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 1.2%    |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.2%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.2%    |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 1.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.2%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.2%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.2%    |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1         | 1.2%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.2%    |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                               | 1         | 1.2%    |
| AMD Picasso                                                                              | 1         | 1.2%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 1.2%    |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 1.2%    |
| AMD Cezanne                                                                              | 1         | 1.2%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1         | 1.2%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 41.79%  |
| 1 x AMD        | 13        | 19.4%   |
| Intel + Nvidia | 12        | 17.91%  |
| 1 x Nvidia     | 10        | 14.93%  |
| AMD + Nvidia   | 2         | 2.99%   |
| 2 x AMD        | 1         | 1.49%   |
| Intel + AMD    | 1         | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 57        | 85.07%  |
| Proprietary | 9         | 13.43%  |
| Unknown     | 1         | 1.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 56.72%  |
| 1.01-2.0   | 9         | 13.43%  |
| 0.51-1.0   | 6         | 8.96%   |
| 3.01-4.0   | 4         | 5.97%   |
| 0.01-0.5   | 4         | 5.97%   |
| 7.01-8.0   | 3         | 4.48%   |
| 5.01-6.0   | 1         | 1.49%   |
| 2.01-3.0   | 1         | 1.49%   |
| 8.01-16.0  | 1         | 1.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 14        | 20%     |
| Samsung Electronics     | 9         | 12.86%  |
| BOE                     | 7         | 10%     |
| LG Display              | 6         | 8.57%   |
| AU Optronics            | 6         | 8.57%   |
| Goldstar                | 5         | 7.14%   |
| Apple                   | 4         | 5.71%   |
| AOC                     | 4         | 5.71%   |
| Hewlett-Packard         | 3         | 4.29%   |
| Lenovo                  | 2         | 2.86%   |
| Dell                    | 2         | 2.86%   |
| TBD                     | 1         | 1.43%   |
| SKY                     | 1         | 1.43%   |
| Sharp                   | 1         | 1.43%   |
| Seiko/Epson             | 1         | 1.43%   |
| Chi Mei Optoelectronics | 1         | 1.43%   |
| BenQ                    | 1         | 1.43%   |
| Ancor Communications    | 1         | 1.43%   |
| Acer                    | 1         | 1.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch         | 2         | 2.74%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 2         | 2.74%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 2         | 2.74%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 2         | 2.74%   |
| TBD HDMI TBD3148 1600x900 344x193mm 15.5-inch                            | 1         | 1.37%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                     | 1         | 1.37%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 1.37%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 1.37%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch        | 1         | 1.37%   |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch        | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 890x500mm 40.2-inch    | 1         | 1.37%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1200x340mm 49.1-inch       | 1         | 1.37%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch        | 1         | 1.37%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 1         | 1.37%   |
| LG Display LCD Monitor LGD06AD 2560x1600 286x179mm 13.3-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 1         | 1.37%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 1         | 1.37%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch              | 1         | 1.37%   |
| Lenovo LEN-A340C-B-A LENF908 1920x1080 527x296mm 23.8-inch               | 1         | 1.37%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.37%   |
| Hewlett-Packard ALL-in-One HPN4032 1920x1080 527x296mm 23.8-inch         | 1         | 1.37%   |
| Hewlett-Packard 24x HPN3635 1920x1080 527x297mm 23.8-inch                | 1         | 1.37%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch               | 1         | 1.37%   |
| Goldstar TV SSCR GSMC0C8 3840x2160 1600x900mm 72.3-inch                  | 1         | 1.37%   |
| Goldstar MP59HT GSM5B44 1920x1080 480x270mm 21.7-inch                    | 1         | 1.37%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                    | 1         | 1.37%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                   | 1         | 1.37%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                   | 1         | 1.37%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 1         | 1.37%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                        | 1         | 1.37%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                        | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15E0 1920x1080 344x193mm 15.5-inch         | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch         | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1477 1366x768 309x174mm 14.0-inch          | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1361 1920x1080 290x170mm 13.2-inch         | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1338 1366x768 293x164mm 13.2-inch          | 1         | 1.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1711 1600x900 382x215mm 17.3-inch | 1         | 1.37%   |
| BOE LCD Monitor BOE07B8 1920x1080 294x165mm 13.3-inch                    | 1         | 1.37%   |
| BOE LCD Monitor BOE0726 1920x1080 344x193mm 15.5-inch                    | 1         | 1.37%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 1         | 1.37%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 1         | 1.37%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 1.37%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 1         | 1.37%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 1         | 1.37%   |
| BenQ LCD Monitor PD2700U 3840x2160                                       | 1         | 1.37%   |
| AU Optronics LCD Monitor AUOA08B 1920x1080 344x193mm 15.5-inch           | 1         | 1.37%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 1         | 1.37%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x173mm 13.9-inch           | 1         | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 47.76%  |
| 1366x768 (WXGA)    | 15        | 22.39%  |
| 3840x2160 (4K)     | 4         | 5.97%   |
| 1280x800 (WXGA)    | 3         | 4.48%   |
| 1600x900 (HD+)     | 2         | 2.99%   |
| 1440x900 (WXGA+)   | 2         | 2.99%   |
| 5120x1440          | 1         | 1.49%   |
| 3840x2400          | 1         | 1.49%   |
| 3840x1080          | 1         | 1.49%   |
| 2736x1824          | 1         | 1.49%   |
| 2560x1600          | 1         | 1.49%   |
| 2560x1440 (QHD)    | 1         | 1.49%   |
| 2560x1080          | 1         | 1.49%   |
| 1680x1050 (WSXGA+) | 1         | 1.49%   |
| Unknown            | 1         | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 25        | 35.21%  |
| 13      | 11        | 15.49%  |
| 23      | 6         | 8.45%   |
| 21      | 6         | 8.45%   |
| 14      | 4         | 5.63%   |
| 27      | 3         | 4.23%   |
| Unknown | 3         | 4.23%   |
| 40      | 2         | 2.82%   |
| 24      | 2         | 2.82%   |
| 17      | 2         | 2.82%   |
| 12      | 2         | 2.82%   |
| 72      | 1         | 1.41%   |
| 49      | 1         | 1.41%   |
| 33      | 1         | 1.41%   |
| 28      | 1         | 1.41%   |
| 10      | 1         | 1.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 47.14%  |
| 501-600     | 10        | 14.29%  |
| 201-300     | 9         | 12.86%  |
| 401-500     | 6         | 8.57%   |
| 351-400     | 3         | 4.29%   |
| Unknown     | 3         | 4.29%   |
| 801-900     | 2         | 2.86%   |
| 701-800     | 1         | 1.43%   |
| 601-700     | 1         | 1.43%   |
| 1501-2000   | 1         | 1.43%   |
| 1001-1500   | 1         | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 50        | 78.13%  |
| 16/10   | 7         | 10.94%  |
| Unknown | 3         | 4.69%   |
| 3/2     | 2         | 3.13%   |
| 32/9    | 1         | 1.56%   |
| 21/9    | 1         | 1.56%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 35.71%  |
| 81-90          | 10        | 14.29%  |
| 201-250        | 10        | 14.29%  |
| 71-80          | 5         | 7.14%   |
| 301-350        | 3         | 4.29%   |
| 151-200        | 3         | 4.29%   |
| 501-1000       | 3         | 4.29%   |
| Unknown        | 3         | 4.29%   |
| 61-70          | 2         | 2.86%   |
| More than 1000 | 1         | 1.43%   |
| 351-500        | 1         | 1.43%   |
| 41-50          | 1         | 1.43%   |
| 251-300        | 1         | 1.43%   |
| 131-140        | 1         | 1.43%   |
| 121-130        | 1         | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 25        | 36.23%  |
| 121-160       | 20        | 28.99%  |
| 51-100        | 14        | 20.29%  |
| 161-240       | 4         | 5.8%    |
| Unknown       | 3         | 4.35%   |
| More than 240 | 2         | 2.9%    |
| 1-50          | 1         | 1.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 59        | 88.06%  |
| 2     | 5         | 7.46%   |
| 3     | 2         | 2.99%   |
| 0     | 1         | 1.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 44        | 42.72%  |
| Intel                    | 27        | 26.21%  |
| Broadcom                 | 11        | 10.68%  |
| Qualcomm Atheros         | 8         | 7.77%   |
| Xiaomi                   | 2         | 1.94%   |
| MEDIATEK                 | 2         | 1.94%   |
| Marvell Technology Group | 2         | 1.94%   |
| TP-Link                  | 1         | 0.97%   |
| Samsung Electronics      | 1         | 0.97%   |
| realme                   | 1         | 0.97%   |
| Ralink Technology        | 1         | 0.97%   |
| Qualcomm                 | 1         | 0.97%   |
| NEC Computers            | 1         | 0.97%   |
| DisplayLink              | 1         | 0.97%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 23.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 5.69%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 4.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 3.25%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 3.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 2.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 2.44%   |
| Xiaomi SDM660-MTP _SN:6C524624                                    | 2         | 1.63%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 1.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 2         | 1.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.63%   |
| Intel Wireless 7260                                               | 2         | 1.63%   |
| Intel Wireless 3165                                               | 2         | 1.63%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.63%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.81%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.81%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.81%   |
| realme SDM665-IDP _SN:18689828                                    | 1         | 0.81%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.81%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.81%   |
| Qualcomm Android                                                  | 1         | 0.81%   |
| NEC Computers WiMAX Mobile Router                                 | 1         | 0.81%   |
| MediaTek TECNO Camon CX                                           | 1         | 0.81%   |
| MEDIATEK Network controller                                       | 1         | 0.81%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 0.81%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.81%   |
| Intel Wireless 8260                                               | 1         | 0.81%   |
| Intel Wireless 7265                                               | 1         | 0.81%   |
| Intel Wireless 3160                                               | 1         | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.81%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 0.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.81%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.81%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.81%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.81%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 0.81%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 0.81%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 0.81%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.81%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 0.81%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.81%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 0.81%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 23        | 39.66%  |
| Realtek Semiconductor    | 14        | 24.14%  |
| Broadcom                 | 10        | 17.24%  |
| Qualcomm Atheros         | 7         | 12.07%  |
| TP-Link                  | 1         | 1.72%   |
| Ralink Technology        | 1         | 1.72%   |
| MEDIATEK                 | 1         | 1.72%   |
| Marvell Technology Group | 1         | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 6         | 10.34%  |
| Broadcom BCM4331 802.11a/b/g/n                             | 4         | 6.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 3         | 5.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 3         | 5.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 3         | 5.17%   |
| Realtek RTL8723DE Wireless Network Adapter                 | 2         | 3.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 2         | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 3.45%   |
| Intel Wireless 7260                                        | 2         | 3.45%   |
| Intel Wireless 3165                                        | 2         | 3.45%   |
| Broadcom BCM43142 802.11b/g/n                              | 2         | 3.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1         | 1.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1         | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.72%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1         | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1         | 1.72%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 1.72%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1         | 1.72%   |
| MEDIATEK Network controller                                | 1         | 1.72%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless          | 1         | 1.72%   |
| Intel Wireless 8260                                        | 1         | 1.72%   |
| Intel Wireless 7265                                        | 1         | 1.72%   |
| Intel Wireless 3160                                        | 1         | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 1.72%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 1.72%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 1         | 1.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 1         | 1.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 1.72%   |
| Intel Centrino Wireless-N 2230                             | 1         | 1.72%   |
| Intel Centrino Advanced-N 6235                             | 1         | 1.72%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]              | 1         | 1.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 1         | 1.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1         | 1.72%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1         | 1.72%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 1         | 1.72%   |
| Broadcom BCM4312 802.11b/g LP-PHY                          | 1         | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 39        | 60.94%  |
| Intel                    | 10        | 15.63%  |
| Broadcom                 | 5         | 7.81%   |
| Xiaomi                   | 2         | 3.13%   |
| Qualcomm Atheros         | 2         | 3.13%   |
| Samsung Electronics      | 1         | 1.56%   |
| realme                   | 1         | 1.56%   |
| Qualcomm                 | 1         | 1.56%   |
| MediaTek                 | 1         | 1.56%   |
| Marvell Technology Group | 1         | 1.56%   |
| DisplayLink              | 1         | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 45.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 10.94%  |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 6.25%   |
| Xiaomi SDM660-MTP _SN:6C524624                                    | 2         | 3.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.13%   |
| Intel I211 Gigabit Network Connection                             | 2         | 3.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.13%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.56%   |
| realme SDM665-IDP _SN:18689828                                    | 1         | 1.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.56%   |
| Qualcomm Android                                                  | 1         | 1.56%   |
| MediaTek TECNO Camon CX                                           | 1         | 1.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.56%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.56%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.56%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.56%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.56%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.56%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 1.56%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 57        | 50%     |
| WiFi     | 56        | 49.12%  |
| Unknown  | 1         | 0.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 52        | 52%     |
| WiFi     | 48        | 48%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 42        | 62.69%  |
| 1     | 25        | 37.31%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 50        | 74.63%  |
| Yes  | 17        | 25.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 42.31%  |
| Realtek Semiconductor           | 10        | 19.23%  |
| Lite-On Technology              | 4         | 7.69%   |
| Apple                           | 4         | 7.69%   |
| Broadcom                        | 3         | 5.77%   |
| Qualcomm Atheros Communications | 2         | 3.85%   |
| Foxconn / Hon Hai               | 2         | 3.85%   |
| Cambridge Silicon Radio         | 2         | 3.85%   |
| Marvell Semiconductor           | 1         | 1.92%   |
| IMC Networks                    | 1         | 1.92%   |
| ASUSTek Computer                | 1         | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 13.46%  |
| Intel AX200 Bluetooth                               | 6         | 11.54%  |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 9.62%   |
| Realtek Bluetooth Radio                             | 5         | 9.62%   |
| Intel Bluetooth Device                              | 5         | 9.62%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.85%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 3.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 3.85%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 3.85%   |
| Apple Bluetooth USB Host Controller                 | 2         | 3.85%   |
| Apple Bluetooth Host Controller                     | 2         | 3.85%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.92%   |
| Lite-On Wireless_Device                             | 1         | 1.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.92%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 1.92%   |
| Lite-On Bluetooth Device                            | 1         | 1.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.92%   |
| Intel AX210 Bluetooth                               | 1         | 1.92%   |
| IMC Networks BCM20702A0                             | 1         | 1.92%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.92%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.92%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 1.92%   |
| ASUS Bluetooth Radio                                | 1         | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 48        | 51.06%  |
| AMD                                  | 20        | 21.28%  |
| Nvidia                               | 17        | 18.09%  |
| Thesycon Systemsoftware & Consulting | 1         | 1.06%   |
| TEAC                                 | 1         | 1.06%   |
| Razer USA                            | 1         | 1.06%   |
| JMTek                                | 1         | 1.06%   |
| Generalplus Technology               | 1         | 1.06%   |
| Creative Technology                  | 1         | 1.06%   |
| Creative Labs                        | 1         | 1.06%   |
| C-Media Electronics                  | 1         | 1.06%   |
| ASUSTek Computer                     | 1         | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 9.82%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 5.36%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 6         | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 3.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.68%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 2.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 2.68%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.68%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 2.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.79%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 1.79%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.79%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.79%   |
| Thesycon Systemsoftware & Consulting E30                                                          | 1         | 0.89%   |
| TEAC TASCAM iXR                                                                                   | 1         | 0.89%   |
| Razer USA Kraken Tournament Edition                                                               | 1         | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.89%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.89%   |
| Nvidia stereo controller                                                                          | 1         | 0.89%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.89%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.89%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.89%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.89%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.89%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.89%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.89%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.89%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.89%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.89%   |
| Creative Technology Sound BlasterX Kratos S5                                                      | 1         | 0.89%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 1         | 0.89%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.89%   |
| ASUSTek Computer USB Audio                                                                        | 1         | 0.89%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.89%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.89%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.89%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 20%     |
| Kingston            | 6         | 17.14%  |
| SK Hynix            | 5         | 14.29%  |
| Micron Technology   | 5         | 14.29%  |
| Crucial             | 3         | 8.57%   |
| Ramaxel Technology  | 2         | 5.71%   |
| Corsair             | 2         | 5.71%   |
| Unknown             | 1         | 2.86%   |
| Toshiba             | 1         | 2.86%   |
| Qimonda             | 1         | 2.86%   |
| Neo Forza           | 1         | 2.86%   |
| G.Skill             | 1         | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 2         | 5.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 2         | 5.56%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                   | 1         | 2.78%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s            | 1         | 2.78%   |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s             | 1         | 2.78%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 2.78%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s     | 1         | 2.78%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 2.78%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                | 1         | 2.78%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 2.78%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s      | 1         | 2.78%   |
| Samsung RAM M4 70T5663EH3-CF7 2048MB SODIMM DDR2 2048MT/s     | 1         | 2.78%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s        | 1         | 2.78%   |
| Ramaxel RAM RMT3170EF68F9W1600 4096MB SODIMM DDR3 1600MT/s    | 1         | 2.78%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s     | 1         | 2.78%   |
| Qimonda RAM 64T256020EDL2.5C2 2048MB SODIMM DDR2 2048MT/s     | 1         | 2.78%   |
| Neo Forza RAM NMUD380D81-1600D 8192MB DIMM DDR3               | 1         | 2.78%   |
| Micron RAM MT41K256M16LY 2GB SODIMM DDR3 1600MT/s             | 1         | 2.78%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 1         | 2.78%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s         | 1         | 2.78%   |
| Micron RAM 16JSF25664HZ-1G4F1 2GB SODIMM DDR3 1334MT/s        | 1         | 2.78%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16384MB SODIMM DDR4 3200MT/s     | 1         | 2.78%   |
| Kingston RAM KHX2666C15S4/8G 8192MB SODIMM DDR4 2667MT/s      | 1         | 2.78%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s        | 1         | 2.78%   |
| Kingston RAM 99U5471-052.A 8GB DIMM DDR3 1333MT/s             | 1         | 2.78%   |
| Kingston RAM 99U5403-159.A01LF 8192MB DIMM DDR3               | 1         | 2.78%   |
| Kingston RAM 9905700-070.A01G 16GB SODIMM DDR4 2667MT/s       | 1         | 2.78%   |
| Kingston RAM 9905700-026.A00G 8GB SODIMM DDR4 2667MT/s        | 1         | 2.78%   |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s     | 1         | 2.78%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s    | 1         | 2.78%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16384MB SODIMM DDR4 2400MT/s | 1         | 2.78%   |
| Crucial RAM BLS8G4D26BFSCK.8FD 8GB DIMM DDR4 2133MT/s         | 1         | 2.78%   |
| Corsair RAM CMK4GX4M1A2400C14 4GB DIMM DDR4 3007MT/s          | 1         | 2.78%   |
| Corsair RAM CMH32GX4M2D3600C18 16GB DIMM DDR4 2133MT/s        | 1         | 2.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR4  | 15        | 60%     |
| DDR3  | 7         | 28%     |
| DDR2  | 2         | 8%      |
| SDRAM | 1         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 18        | 72%     |
| DIMM   | 7         | 28%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 10        | 37.04%  |
| 8192  | 8         | 29.63%  |
| 16384 | 5         | 18.52%  |
| 2048  | 4         | 14.81%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 9         | 30%     |
| 1600    | 5         | 16.67%  |
| 3200    | 4         | 13.33%  |
| 2133    | 2         | 6.67%   |
| 3600    | 1         | 3.33%   |
| 3007    | 1         | 3.33%   |
| 3000    | 1         | 3.33%   |
| 2400    | 1         | 3.33%   |
| 2048    | 1         | 3.33%   |
| 1334    | 1         | 3.33%   |
| 1333    | 1         | 3.33%   |
| 1066    | 1         | 3.33%   |
| 800     | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model             | Computers | Percent |
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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 23.91%  |
| Quanta                                 | 5         | 10.87%  |
| Apple                                  | 5         | 10.87%  |
| Microdia                               | 4         | 8.7%    |
| Suyin                                  | 3         | 6.52%   |
| Realtek Semiconductor                  | 3         | 6.52%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.52%   |
| Syntek                                 | 2         | 4.35%   |
| Sunplus Innovation Technology          | 2         | 4.35%   |
| Luxvisions Innotech Limited            | 2         | 4.35%   |
| webcam                                 | 1         | 2.17%   |
| Primax Electronics                     | 1         | 2.17%   |
| Microsoft                              | 1         | 2.17%   |
| Logitech                               | 1         | 2.17%   |
| Importek                               | 1         | 2.17%   |
| Acer                                   | 1         | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Apple FaceTime HD Camera                                        | 4         | 8.51%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 2         | 4.26%   |
| Realtek HD WebCam                                               | 2         | 4.26%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 4.26%   |
| Chicony HP Wide Vision HD Camera                                | 2         | 4.26%   |
| Chicony HD WebCam                                               | 2         | 4.26%   |
| webcam webcam                                                   | 1         | 2.13%   |
| Syntek Integrated Camera                                        | 1         | 2.13%   |
| Syntek EasyCamera                                               | 1         | 2.13%   |
| Suyin Asus Integrated Webcam                                    | 1         | 2.13%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                           | 1         | 2.13%   |
| Sunplus Laptop Integrated WebCam HD                             | 1         | 2.13%   |
| Realtek Integrated_Webcam_HD                                    | 1         | 2.13%   |
| Quanta HP Webcam                                                | 1         | 2.13%   |
| Quanta HP 5M Camera                                             | 1         | 2.13%   |
| Quanta HD User Facing                                           | 1         | 2.13%   |
| Primax Villem                                                   | 1         | 2.13%   |
| Microsoft LifeCam HD-3000                                       | 1         | 2.13%   |
| Microdia Laptop_Integrated_Webcam_FHD                           | 1         | 2.13%   |
| Microdia Integrated Webcam                                      | 1         | 2.13%   |
| Microdia Integrated Camera                                      | 1         | 2.13%   |
| Microdia HD USB Camera                                          | 1         | 2.13%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 2.13%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1         | 2.13%   |
| Logitech BRIO 4K Stream Edition                                 | 1         | 2.13%   |
| Importek Webcam HD                                              | 1         | 2.13%   |
| Chicony USB2.0 Camera                                           | 1         | 2.13%   |
| Chicony HP Wide Vision HD                                       | 1         | 2.13%   |
| Chicony HP Webcam                                               | 1         | 2.13%   |
| Chicony HP Truevision HD                                        | 1         | 2.13%   |
| Chicony HP IR Camera                                            | 1         | 2.13%   |
| Chicony HP Integrated Webcam                                    | 1         | 2.13%   |
| Chicony HP HD Webcam [Fixed]                                    | 1         | 2.13%   |
| Chicony HD User Facing                                          | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 1         | 2.13%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 1         | 2.13%   |
| Acer SunplusIT Integrated Camera                                | 1         | 2.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 3         | 50%     |
| Validity Sensors      | 1         | 16.67%  |
| Synaptics             | 1         | 16.67%  |
| STMicroelectronics    | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 51        | 76.12%  |
| 1     | 13        | 19.4%   |
| 2     | 3         | 4.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 7         | 35%     |
| Fingerprint reader    | 6         | 30%     |
| Graphics card         | 5         | 25%     |
| Sound                 | 1         | 5%      |
| Multimedia controller | 1         | 5%      |

