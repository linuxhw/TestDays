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
| 5.11.0-27-generic     | 25        | 45.45%  |
| 5.11.0-25-generic     | 14        | 25.45%  |
| 5.8.0-50-generic      | 5         | 9.09%   |
| 5.8.0-55-generic      | 3         | 5.45%   |
| 5.8.0-63-generic      | 2         | 3.64%   |
| 5.8.0-53-generic      | 1         | 1.82%   |
| 5.8.0-44-generic      | 1         | 1.82%   |
| 5.4.0-58-generic      | 1         | 1.82%   |
| 5.4.0-56-generic      | 1         | 1.82%   |
| 5.11.0-27-lowlatency  | 1         | 1.82%   |
| 5.11.0-051100-generic | 1         | 1.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 41        | 74.55%  |
| 5.8.0   | 12        | 21.82%  |
| 5.4.0   | 2         | 3.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 41        | 74.55%  |
| 5.8     | 12        | 21.82%  |
| 5.4     | 2         | 3.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 55        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Pantheon   | 46        | 83.64%  |
| Unknown    | 5         | 9.09%   |
| GNOME      | 2         | 3.64%   |
| X-Cinnamon | 1         | 1.82%   |
| MATE       | 1         | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 55        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 44        | 80%     |
| TDM     | 7         | 12.73%  |
| LightDM | 2         | 3.64%   |
| GDM     | 2         | 3.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 28        | 50.91%  |
| es_ES | 5         | 9.09%   |
| de_DE | 5         | 9.09%   |
| pt_BR | 3         | 5.45%   |
| zh_CN | 2         | 3.64%   |
| fr_FR | 2         | 3.64%   |
| en_GB | 2         | 3.64%   |
| en_CA | 2         | 3.64%   |
| ru_RU | 1         | 1.82%   |
| it_IT | 1         | 1.82%   |
| fr_BE | 1         | 1.82%   |
| es_MX | 1         | 1.82%   |
| en_AU | 1         | 1.82%   |
| ca_ES | 1         | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 34        | 61.82%  |
| BIOS | 21        | 38.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 51        | 92.73%  |
| Overlay | 2         | 3.64%   |
| Btrfs   | 2         | 3.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 44        | 80%     |
| GPT     | 8         | 14.55%  |
| MBR     | 3         | 5.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 94.55%  |
| Yes       | 3         | 5.45%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 83.64%  |
| Yes       | 9         | 16.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 16        | 29.09%  |
| ASUSTek Computer    | 8         | 14.55%  |
| Acer                | 6         | 10.91%  |
| Gigabyte Technology | 4         | 7.27%   |
| Apple               | 4         | 7.27%   |
| Lenovo              | 3         | 5.45%   |
| Dell                | 3         | 5.45%   |
| Microsoft           | 2         | 3.64%   |
| ASRock              | 2         | 3.64%   |
| Toshiba             | 1         | 1.82%   |
| Sony                | 1         | 1.82%   |
| MSI                 | 1         | 1.82%   |
| Medion              | 1         | 1.82%   |
| Gateway             | 1         | 1.82%   |
| eMachines           | 1         | 1.82%   |
| Acidanthera         | 1         | 1.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Apple MacBookPro9,1                 | 2         | 3.64%   |
| Toshiba Satellite L500              | 1         | 1.82%   |
| Sony Serie VJC14                    | 1         | 1.82%   |
| MSI MS-7B79                         | 1         | 1.82%   |
| Microsoft Surface Pro 4             | 1         | 1.82%   |
| Microsoft Surface Laptop Go         | 1         | 1.82%   |
| Medion AKOYA THE TOUCH 10           | 1         | 1.82%   |
| Lenovo V330-15IKB 81AX              | 1         | 1.82%   |
| Lenovo ThinkPad X201 3249CTO        | 1         | 1.82%   |
| Lenovo IdeaPad 330-15IKB 81FE       | 1         | 1.82%   |
| HP Stream Laptop 14-cb1xxx          | 1         | 1.82%   |
| HP ProBook 450 G8 Notebook PC       | 1         | 1.82%   |
| HP ProBook 4320s                    | 1         | 1.82%   |
| HP Pavilion Gaming Laptop 15-ec0xxx | 1         | 1.82%   |
| HP Pavilion g6                      | 1         | 1.82%   |
| HP Pavilion Desktop 590-p0xxx       | 1         | 1.82%   |
| HP Pavilion All-in-One 24-k0xxx     | 1         | 1.82%   |
| HP Pavilion Aero Laptop 13-be0xxx   | 1         | 1.82%   |
| HP Notebook                         | 1         | 1.82%   |
| HP Laptop 15-bs1xx                  | 1         | 1.82%   |
| HP Laptop 15-bs0xx                  | 1         | 1.82%   |
| HP Laptop 14-dq1xxx                 | 1         | 1.82%   |
| HP ENVY x360 Convertible 15-ee0xxx  | 1         | 1.82%   |
| HP ENVY x360 Convertible 13-ag0xxx  | 1         | 1.82%   |
| HP EliteBook Folio 9470m            | 1         | 1.82%   |
| HP EliteBook 840 G3                 | 1         | 1.82%   |
| Gigabyte X570 I AORUS PRO WIFI      | 1         | 1.82%   |
| Gigabyte H310M M.2 2.0              | 1         | 1.82%   |
| Gigabyte F2A55M-HD2                 | 1         | 1.82%   |
| Gigabyte B450M DS3H V2              | 1         | 1.82%   |
| Gateway NV54 Series                 | 1         | 1.82%   |
| eMachines G525                      | 1         | 1.82%   |
| Dell XPS L321X                      | 1         | 1.82%   |
| Dell Precision 5760                 | 1         | 1.82%   |
| Dell Latitude 3580                  | 1         | 1.82%   |
| ASUS TUF GAMING B550M-PLUS          | 1         | 1.82%   |
| ASUS TUF GAMING B450M-PRO II        | 1         | 1.82%   |
| ASUS ROG STRIX Z590-F GAMING WIFI   | 1         | 1.82%   |
| ASUS ROG STRIX B450-I GAMING        | 1         | 1.82%   |
| ASUS P6X58D-E                       | 1         | 1.82%   |
| ASUS P5KPL-AM SE                    | 1         | 1.82%   |
| ASUS M5A99X EVO R2.0                | 1         | 1.82%   |
| ASUS M5A78L-M LX/BR                 | 1         | 1.82%   |
| ASRock H81TM-ITX R2.0               | 1         | 1.82%   |
| ASRock B450 Pro4                    | 1         | 1.82%   |
| Apple MacBookPro8,2                 | 1         | 1.82%   |
| Apple MacBookPro8,1                 | 1         | 1.82%   |
| Acidanthera iMacPro1,1              | 1         | 1.82%   |
| Acer Swift SF315-41                 | 1         | 1.82%   |
| Acer Swift SF314-55G                | 1         | 1.82%   |
| Acer ConceptD CN315-71P             | 1         | 1.82%   |
| Acer Aspire F5-573G                 | 1         | 1.82%   |
| Acer Aspire A515-51G                | 1         | 1.82%   |
| Acer Aspire A514-54                 | 1         | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| HP Pavilion          | 5         | 9.09%   |
| HP Laptop            | 3         | 5.45%   |
| Acer Aspire          | 3         | 5.45%   |
| Microsoft Surface    | 2         | 3.64%   |
| HP ProBook           | 2         | 3.64%   |
| HP ENVY              | 2         | 3.64%   |
| HP EliteBook         | 2         | 3.64%   |
| ASUS TUF             | 2         | 3.64%   |
| ASUS ROG             | 2         | 3.64%   |
| Apple MacBookPro9    | 2         | 3.64%   |
| Apple MacBookPro8    | 2         | 3.64%   |
| Acer Swift           | 2         | 3.64%   |
| Toshiba Satellite    | 1         | 1.82%   |
| Sony Serie           | 1         | 1.82%   |
| MSI MS-7B79          | 1         | 1.82%   |
| Medion AKOYA         | 1         | 1.82%   |
| Lenovo V330-15IKB    | 1         | 1.82%   |
| Lenovo ThinkPad      | 1         | 1.82%   |
| Lenovo IdeaPad       | 1         | 1.82%   |
| HP Stream            | 1         | 1.82%   |
| HP Notebook          | 1         | 1.82%   |
| Gigabyte X570        | 1         | 1.82%   |
| Gigabyte H310M       | 1         | 1.82%   |
| Gigabyte F2A55M-HD2  | 1         | 1.82%   |
| Gigabyte B450M       | 1         | 1.82%   |
| Gateway NV54         | 1         | 1.82%   |
| eMachines G525       | 1         | 1.82%   |
| Dell XPS             | 1         | 1.82%   |
| Dell Precision       | 1         | 1.82%   |
| Dell Latitude        | 1         | 1.82%   |
| ASUS P6X58D-E        | 1         | 1.82%   |
| ASUS P5KPL-AM        | 1         | 1.82%   |
| ASUS M5A99X          | 1         | 1.82%   |
| ASUS M5A78L-M        | 1         | 1.82%   |
| ASRock H81TM-ITX     | 1         | 1.82%   |
| ASRock B450          | 1         | 1.82%   |
| Acidanthera iMacPro1 | 1         | 1.82%   |
| Acer ConceptD        | 1         | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 16        | 29.09%  |
| 2019 | 9         | 16.36%  |
| 2020 | 7         | 12.73%  |
| 2018 | 5         | 9.09%   |
| 2013 | 5         | 9.09%   |
| 2012 | 3         | 5.45%   |
| 2010 | 3         | 5.45%   |
| 2017 | 2         | 3.64%   |
| 2015 | 2         | 3.64%   |
| 2009 | 2         | 3.64%   |
| 2014 | 1         | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 33        | 60%     |
| Desktop     | 16        | 29.09%  |
| Tablet      | 2         | 3.64%   |
| Convertible | 2         | 3.64%   |
| All in one  | 2         | 3.64%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 44        | 80%     |
| Enabled  | 11        | 20%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 55        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 17        | 30.91%  |
| 16.01-24.0 | 11        | 20%     |
| 32.01-64.0 | 10        | 18.18%  |
| 3.01-4.0   | 10        | 18.18%  |
| 8.01-16.0  | 6         | 10.91%  |
| 1.01-2.0   | 1         | 1.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 19        | 33.93%  |
| 1.01-2.0  | 19        | 33.93%  |
| 3.01-4.0  | 10        | 17.86%  |
| 4.01-8.0  | 7         | 12.5%   |
| 8.01-16.0 | 1         | 1.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 35        | 63.64%  |
| 2      | 14        | 25.45%  |
| 3      | 3         | 5.45%   |
| 6      | 1         | 1.82%   |
| 5      | 1         | 1.82%   |
| 4      | 1         | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 80%     |
| Yes       | 11        | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 83.64%  |
| No        | 9         | 16.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 80%     |
| No        | 11        | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 75%     |
| No        | 14        | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 8         | 14.55%  |
| India        | 5         | 9.09%   |
| Germany      | 4         | 7.27%   |
| Argentina    | 4         | 7.27%   |
| UK           | 3         | 5.45%   |
| Brazil       | 3         | 5.45%   |
| Russia       | 2         | 3.64%   |
| Netherlands  | 2         | 3.64%   |
| Mexico       | 2         | 3.64%   |
| Canada       | 2         | 3.64%   |
| Belgium      | 2         | 3.64%   |
| Switzerland  | 1         | 1.82%   |
| Spain        | 1         | 1.82%   |
| South Africa | 1         | 1.82%   |
| Serbia       | 1         | 1.82%   |
| Myanmar      | 1         | 1.82%   |
| Kenya        | 1         | 1.82%   |
| Kazakhstan   | 1         | 1.82%   |
| Japan        | 1         | 1.82%   |
| Italy        | 1         | 1.82%   |
| Indonesia    | 1         | 1.82%   |
| Guyana       | 1         | 1.82%   |
| Guatemala    | 1         | 1.82%   |
| France       | 1         | 1.82%   |
| Finland      | 1         | 1.82%   |
| Czechia      | 1         | 1.82%   |
| China        | 1         | 1.82%   |
| Austria      | 1         | 1.82%   |
| Australia    | 1         | 1.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Znojmo                   | 1         | 1.79%   |
| Yuma                     | 1         | 1.79%   |
| Vienna                   | 1         | 1.79%   |
| Vernon                   | 1         | 1.79%   |
| Toledo                   | 1         | 1.79%   |
| Tokyo                    | 1         | 1.79%   |
| Thousand Oaks            | 1         | 1.79%   |
| Stevenage                | 1         | 1.79%   |
| Staropyshminsk           | 1         | 1.79%   |
| Sinop                    | 1         | 1.79%   |
| S??o Pedro               | 1         | 1.79%   |
| S??o Paulo               | 1         | 1.79%   |
| Santa Monica             | 1         | 1.79%   |
| Sant Carles de la Rapita | 1         | 1.79%   |
| Sakai                    | 1         | 1.79%   |
| Sacramento               | 1         | 1.79%   |
| Rosario                  | 1         | 1.79%   |
| Roermond                 | 1         | 1.79%   |
| Rheinberg                | 1         | 1.79%   |
| Quer?©taro City          | 1         | 1.79%   |
| Potsdam                  | 1         | 1.79%   |
| Perth                    | 1         | 1.79%   |
| Peekskill                | 1         | 1.79%   |
| Patna                    | 1         | 1.79%   |
| Paris                    | 1         | 1.79%   |
| Nairobi                  | 1         | 1.79%   |
| Naaldwijk                | 1         | 1.79%   |
| Moscow                   | 1         | 1.79%   |
| Morelia                  | 1         | 1.79%   |
| Montreal                 | 1         | 1.79%   |
| Monheim am Rhein         | 1         | 1.79%   |
| Milan                    | 1         | 1.79%   |
| Medan                    | 1         | 1.79%   |
| Mandalay                 | 1         | 1.79%   |
| Lucknow                  | 1         | 1.79%   |
| Len?«nskoe               | 1         | 1.79%   |
| Lausanne                 | 1         | 1.79%   |
| Lanaken                  | 1         | 1.79%   |
| Kovin                    | 1         | 1.79%   |
| Koraput                  | 1         | 1.79%   |
| Klaukkala                | 1         | 1.79%   |
| Johannesburg             | 1         | 1.79%   |
| Jalandhar                | 1         | 1.79%   |
| Hollern                  | 1         | 1.79%   |
| Hephzibah                | 1         | 1.79%   |
| Guatemala City           | 1         | 1.79%   |
| Georgetown               | 1         | 1.79%   |
| Chattanooga              | 1         | 1.79%   |
| C??rdoba                 | 1         | 1.79%   |
| Buenos Aires             | 1         | 1.79%   |
| Brussels                 | 1         | 1.79%   |
| Bonnybridge              | 1         | 1.79%   |
| Bhopal                   | 1         | 1.79%   |
| Berazategui              | 1         | 1.79%   |
| Beijing                  | 1         | 1.79%   |
| Bathgate                 | 1         | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 15        | 18     | 19.48%  |
| Samsung Electronics       | 11        | 15     | 14.29%  |
| Seagate                   | 8         | 11     | 10.39%  |
| Kingston                  | 6         | 6      | 7.79%   |
| Toshiba                   | 5         | 5      | 6.49%   |
| Sandisk                   | 5         | 5      | 6.49%   |
| Unknown                   | 3         | 3      | 3.9%    |
| Hitachi                   | 3         | 3      | 3.9%    |
| Crucial                   | 3         | 3      | 3.9%    |
| Phison                    | 2         | 2      | 2.6%    |
| Micron/Crucial Technology | 2         | 3      | 2.6%    |
| Micron Technology         | 2         | 2      | 2.6%    |
| Gigabyte Technology       | 2         | 2      | 2.6%    |
| USB3.1                    | 1         | 1      | 1.3%    |
| Transcend                 | 1         | 2      | 1.3%    |
| StoreJet                  | 1         | 1      | 1.3%    |
| SK Hynix                  | 1         | 1      | 1.3%    |
| OCZ                       | 1         | 1      | 1.3%    |
| Mercury                   | 1         | 1      | 1.3%    |
| LITEONIT                  | 1         | 1      | 1.3%    |
| KIOXIA                    | 1         | 1      | 1.3%    |
| Intel                     | 1         | 1      | 1.3%    |
| CLOVER                    | 1         | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 3         | 3.53%   |
| WDC WD10SPZX-21Z10T0 1TB             | 2         | 2.35%   |
| Toshiba NVMe SSD Drive 256GB         | 2         | 2.35%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 2.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 1.18%   |
| WDC WD5000AAKX-001CA0 500GB          | 1         | 1.18%   |
| WDC WD3200AAJS-56B4A0 320GB          | 1         | 1.18%   |
| WDC WD20SPZX-21UA7T0 2TB             | 1         | 1.18%   |
| WDC WD20EARX-00PASB0 2TB             | 1         | 1.18%   |
| WDC WD10SPZX-24Z10T0 1TB             | 1         | 1.18%   |
| WDC WD10SPZX-22Z10T1 1TB             | 1         | 1.18%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 1.18%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1.18%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 1.18%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 1.18%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 1.18%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1         | 1.18%   |
| WDC PC SN720 SDAPNTW-256G-1014 256GB | 1         | 1.18%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB | 1         | 1.18%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB | 1         | 1.18%   |
| USB3.1 Disk 500GB                    | 1         | 1.18%   |
| Unknown xD/SD/M.S.                   | 1         | 1.18%   |
| Unknown TA2964  64GB                 | 1         | 1.18%   |
| Unknown MMC Card  500GB              | 1         | 1.18%   |
| Transcend TS256GSSD230S 256GB        | 1         | 1.18%   |
| Toshiba MQ01ABD100V -63 1TB          | 1         | 1.18%   |
| Toshiba MQ01ABD100 1TB               | 1         | 1.18%   |
| Toshiba MK5065GSXF 500GB             | 1         | 1.18%   |
| StoreJet Transcend 512GB             | 1         | 1.18%   |
| SK Hynix NVMe SSD Drive 512GB        | 1         | 1.18%   |
| Seagate ST940210AS 40GB              | 1         | 1.18%   |
| Seagate ST9250315AS 250GB            | 1         | 1.18%   |
| Seagate ST3000DM008-2DM166 3TB       | 1         | 1.18%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 1.18%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 1.18%   |
| Seagate ST1000DX001-1CM162 1TB       | 1         | 1.18%   |
| Seagate NVMe SSD Drive 2TB           | 1         | 1.18%   |
| SanDisk SDSSDA480G 480GB             | 1         | 1.18%   |
| SanDisk SDSSDA-1T00 1TB              | 1         | 1.18%   |
| Sandisk NVMe SSD Drive 500GB         | 1         | 1.18%   |
| Sandisk NVMe SSD Drive 256GB         | 1         | 1.18%   |
| Sandisk NVMe SSD Drive 1TB           | 1         | 1.18%   |
| Samsung SSD 980 PRO 1TB              | 1         | 1.18%   |
| Samsung SSD 960 EVO 500GB            | 1         | 1.18%   |
| Samsung SSD 870 QVO 1TB              | 1         | 1.18%   |
| Samsung SSD 860 EVO 2TB              | 1         | 1.18%   |
| Samsung SSD 860 EVO 250GB            | 1         | 1.18%   |
| Samsung SSD 850 EVO 250GB            | 1         | 1.18%   |
| Samsung SSD 840 Series 500GB         | 1         | 1.18%   |
| Samsung Portable SSD T5 500GB        | 1         | 1.18%   |
| Samsung NVMe SSD Drive 512GB         | 1         | 1.18%   |
| Samsung NVMe SSD Drive 500GB         | 1         | 1.18%   |
| Samsung NVMe SSD Drive 256GB         | 1         | 1.18%   |
| Samsung NVMe SSD Drive 1TB           | 1         | 1.18%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD | 1         | 1.18%   |
| Samsung HM321HI 320GB                | 1         | 1.18%   |
| Samsung HD154UI 1TB                  | 1         | 1.18%   |
| Phison NVMe SSD Drive 2TB            | 1         | 1.18%   |
| Phison NVMe SSD Drive 256GB          | 1         | 1.18%   |
| OCZ AGILITY3 240GB SSD               | 1         | 1.18%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 14     | 44.44%  |
| Seagate             | 7         | 10     | 25.93%  |
| Toshiba             | 3         | 3      | 11.11%  |
| Hitachi             | 3         | 3      | 11.11%  |
| Samsung Electronics | 2         | 2      | 7.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 28.57%  |
| Kingston            | 4         | 4      | 19.05%  |
| Crucial             | 3         | 3      | 14.29%  |
| SanDisk             | 2         | 2      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| Transcend           | 1         | 2      | 4.76%   |
| StoreJet            | 1         | 1      | 4.76%   |
| OCZ                 | 1         | 1      | 4.76%   |
| Mercury             | 1         | 1      | 4.76%   |
| LITEONIT            | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 27        | 32     | 38.03%  |
| NVMe    | 21        | 29     | 29.58%  |
| SSD     | 18        | 23     | 25.35%  |
| Unknown | 3         | 3      | 4.23%   |
| MMC     | 2         | 2      | 2.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 54     | 60%     |
| NVMe | 21        | 29     | 32.31%  |
| SAS  | 3         | 4      | 4.62%   |
| MMC  | 2         | 2      | 3.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 29     | 53.19%  |
| 0.51-1.0   | 18        | 21     | 38.3%   |
| 1.01-2.0   | 3         | 3      | 6.38%   |
| 2.01-3.0   | 1         | 2      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 19        | 34.55%  |
| 101-250    | 17        | 30.91%  |
| 1001-2000  | 5         | 9.09%   |
| 501-1000   | 5         | 9.09%   |
| 21-50      | 3         | 5.45%   |
| 51-100     | 3         | 5.45%   |
| 1-20       | 2         | 3.64%   |
| 2001-3000  | 1         | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 33        | 60%     |
| 51-100    | 7         | 12.73%  |
| 21-50     | 6         | 10.91%  |
| 101-250   | 4         | 7.27%   |
| 251-500   | 2         | 3.64%   |
| 1001-2000 | 2         | 3.64%   |
| 501-1000  | 1         | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD3200AAJS-56B4A0 320GB | 1         | 1      | 50%     |
| WDC WD10EZEX-00KUWA0 1TB    | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 46        | 69     | 77.97%  |
| Works    | 11        | 18     | 18.64%  |
| Malfunc  | 2         | 2      | 3.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 36        | 45.57%  |
| AMD                          | 14        | 17.72%  |
| Sandisk                      | 6         | 7.59%   |
| Samsung Electronics          | 5         | 6.33%   |
| Phison Electronics           | 3         | 3.8%    |
| Toshiba America Info Systems | 2         | 2.53%   |
| Micron/Crucial Technology    | 2         | 2.53%   |
| Micron Technology            | 2         | 2.53%   |
| Marvell Technology Group     | 2         | 2.53%   |
| Kingston Technology Company  | 2         | 2.53%   |
| ASMedia Technology           | 2         | 2.53%   |
| SK Hynix                     | 1         | 1.27%   |
| Seagate Technology           | 1         | 1.27%   |
| KIOXIA                       | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 9         | 10%     |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 8         | 8.89%   |
| AMD 400 Series Chipset SATA Controller                                                 | 4         | 4.44%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 3.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 3.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 3.33%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 2         | 2.22%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 2         | 2.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 2.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 2.22%   |
| Phison PS5013 E13 NVMe Controller                                                      | 2         | 2.22%   |
| Micron Non-Volatile memory controller                                                  | 2         | 2.22%   |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 2.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 2         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 2.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 2.22%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 2         | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 2.22%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 1         | 1.11%   |
| Toshiba America Info Systems NVMe Controller                                           | 1         | 1.11%   |
| SK Hynix NVMe SSD Controller                                                           | 1         | 1.11%   |
| Seagate FireCuda 510 SSD                                                               | 1         | 1.11%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 1.11%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.11%   |
| Samsung NVMe Controller                                                                | 1         | 1.11%   |
| Phison E12 NVMe Controller                                                             | 1         | 1.11%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 1.11%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 1.11%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                             | 1         | 1.11%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                           | 1         | 1.11%   |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 1.11%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 1.11%   |
| Intel SATA Controller [RAID mode]                                                      | 1         | 1.11%   |
| Intel Non-Volatile memory controller                                                   | 1         | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.11%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                              | 1         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.11%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                             | 1         | 1.11%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                             | 1         | 1.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 1         | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.11%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 1         | 1.11%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                               | 1         | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 1         | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 1.11%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 1.11%   |
| AMD FCH IDE Controller                                                                 | 1         | 1.11%   |
| AMD 300 Series Chipset SATA Controller                                                 | 1         | 1.11%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 38        | 52.05%  |
| NVMe | 21        | 28.77%  |
| RAID | 7         | 9.59%   |
| IDE  | 7         | 9.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 38        | 69.09%  |
| AMD    | 17        | 30.91%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor             | 4         | 7.27%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz    | 2         | 3.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 2         | 3.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz              | 2         | 3.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 2         | 3.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 2         | 3.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 2         | 3.64%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2         | 3.64%   |
| Intel Xeon W-11855M CPU @ 3.20GHz              | 1         | 1.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 1         | 1.82%   |
| Intel Core i7-4930K CPU @ 3.40GHz              | 1         | 1.82%   |
| Intel Core i7-3720QM CPU @ 2.60GHz             | 1         | 1.82%   |
| Intel Core i7-3687U CPU @ 2.10GHz              | 1         | 1.82%   |
| Intel Core i7-3615QM CPU @ 2.30GHz             | 1         | 1.82%   |
| Intel Core i7-2637M CPU @ 1.70GHz              | 1         | 1.82%   |
| Intel Core i7-2635QM CPU @ 2.00GHz             | 1         | 1.82%   |
| Intel Core i7 CPU 950 @ 3.07GHz                | 1         | 1.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 1         | 1.82%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1         | 1.82%   |
| Intel Core i5-2435M CPU @ 2.40GHz              | 1         | 1.82%   |
| Intel Core i5-10400T CPU @ 2.00GHz             | 1         | 1.82%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz             | 1         | 1.82%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 1         | 1.82%   |
| Intel Core i5 CPU M 520 @ 2.40GHz              | 1         | 1.82%   |
| Intel Core i3 CPU M 350 @ 2.27GHz              | 1         | 1.82%   |
| Intel Core 2 Quad CPU Q9500 @ 2.83GHz          | 1         | 1.82%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz           | 1         | 1.82%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 1         | 1.82%   |
| Intel Celeron G4930 CPU @ 3.20GHz              | 1         | 1.82%   |
| Intel Celeron CPU N3050 @ 1.60GHz              | 1         | 1.82%   |
| Intel Celeron CPU N2807 @ 1.58GHz              | 1         | 1.82%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 1         | 1.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 1         | 1.82%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz        | 1         | 1.82%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 1         | 1.82%   |
| AMD Ryzen 7 2700U with Radeon Vega Mobile Gfx  | 1         | 1.82%   |
| AMD Ryzen 5 5600U with Radeon Graphics         | 1         | 1.82%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx  | 1         | 1.82%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1         | 1.82%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx  | 1         | 1.82%   |
| AMD Phenom II N660 Dual-Core Processor         | 1         | 1.82%   |
| AMD FX-8320 Eight-Core Processor               | 1         | 1.82%   |
| AMD FX-6100 Six-Core Processor                 | 1         | 1.82%   |
| AMD A4-4000 APU with Radeon HD Graphics        | 1         | 1.82%   |
| AMD A10-9700 RADEON R7, 10 COMPUTE CORES 4C+6G | 1         | 1.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 15        | 27.27%  |
| Intel Core i7           | 10        | 18.18%  |
| AMD Ryzen 7             | 6         | 10.91%  |
| AMD Ryzen 5             | 6         | 10.91%  |
| Intel Celeron           | 4         | 7.27%   |
| Other                   | 3         | 5.45%   |
| Intel Pentium Dual-Core | 2         | 3.64%   |
| AMD FX                  | 2         | 3.64%   |
| Intel Xeon              | 1         | 1.82%   |
| Intel Core i3           | 1         | 1.82%   |
| Intel Core 2 Quad       | 1         | 1.82%   |
| Intel Core 2 Duo        | 1         | 1.82%   |
| AMD Phenom II           | 1         | 1.82%   |
| AMD A4                  | 1         | 1.82%   |
| AMD A10                 | 1         | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 21        | 38.18%  |
| 4      | 18        | 32.73%  |
| 6      | 8         | 14.55%  |
| 8      | 6         | 10.91%  |
| 3      | 1         | 1.82%   |
| 1      | 1         | 1.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 55        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 44        | 80%     |
| 1      | 11        | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 55        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 10.91%  |
| 0x08701021 | 4         | 7.27%   |
| 0x806ea    | 3         | 5.45%   |
| 0x406e3    | 3         | 5.45%   |
| 0x306a9    | 3         | 5.45%   |
| 0x1067a    | 3         | 5.45%   |
| 0x806e9    | 2         | 3.64%   |
| 0x806c1    | 2         | 3.64%   |
| 0x706e5    | 2         | 3.64%   |
| 0x206a7    | 2         | 3.64%   |
| 0x20652    | 2         | 3.64%   |
| 0x08701013 | 2         | 3.64%   |
| 0xa0671    | 1         | 1.82%   |
| 0xa0653    | 1         | 1.82%   |
| 0x906eb    | 1         | 1.82%   |
| 0x806eb    | 1         | 1.82%   |
| 0x706a8    | 1         | 1.82%   |
| 0x6fd      | 1         | 1.82%   |
| 0x406c3    | 1         | 1.82%   |
| 0x306e4    | 1         | 1.82%   |
| 0x306c3    | 1         | 1.82%   |
| 0x30678    | 1         | 1.82%   |
| 0x106a5    | 1         | 1.82%   |
| 0x0a50000c | 1         | 1.82%   |
| 0x08600104 | 1         | 1.82%   |
| 0x0810100b | 1         | 1.82%   |
| 0x08101007 | 1         | 1.82%   |
| 0x0800820d | 1         | 1.82%   |
| 0x0600611a | 1         | 1.82%   |
| 0x06001119 | 1         | 1.82%   |
| 0x06000852 | 1         | 1.82%   |
| 0x0600063e | 1         | 1.82%   |
| 0x010000c8 | 1         | 1.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 16.36%  |
| Zen 2         | 7         | 12.73%  |
| Skylake       | 4         | 7.27%   |
| IvyBridge     | 4         | 7.27%   |
| SandyBridge   | 3         | 5.45%   |
| Penryn        | 3         | 5.45%   |
| IceLake       | 3         | 5.45%   |
| Zen+          | 2         | 3.64%   |
| Zen           | 2         | 3.64%   |
| Westmere      | 2         | 3.64%   |
| TigerLake     | 2         | 3.64%   |
| Silvermont    | 2         | 3.64%   |
| Piledriver    | 2         | 3.64%   |
| Zen 3         | 1         | 1.82%   |
| Nehalem       | 1         | 1.82%   |
| K10           | 1         | 1.82%   |
| Haswell       | 1         | 1.82%   |
| Goldmont plus | 1         | 1.82%   |
| Excavator     | 1         | 1.82%   |
| Core          | 1         | 1.82%   |
| CometLake     | 1         | 1.82%   |
| Bulldozer     | 1         | 1.82%   |
| Unknown       | 1         | 1.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 34        | 51.52%  |
| Nvidia | 17        | 25.76%  |
| AMD    | 15        | 22.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 4         | 5.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 5.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 4.48%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.48%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 4.48%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 2.99%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 2.99%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2         | 2.99%   |
| Intel HD Graphics 620                                                                    | 2         | 2.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.99%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 2.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 2.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.49%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 1.49%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 1.49%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 1.49%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 1.49%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 1.49%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 1.49%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.49%   |
| Nvidia GK104 [GeForce GTX 770]                                                           | 1         | 1.49%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1         | 1.49%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                                       | 1         | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.49%   |
| Intel VGA compatible controller                                                          | 1         | 1.49%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.49%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 1.49%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 1.49%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.49%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.49%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 1.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.49%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.49%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.49%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1         | 1.49%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.49%   |
| AMD Renoir                                                                               | 1         | 1.49%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                               | 1         | 1.49%   |
| AMD Picasso                                                                              | 1         | 1.49%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 1.49%   |
| AMD Cezanne                                                                              | 1         | 1.49%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1         | 1.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 45.45%  |
| 1 x AMD        | 12        | 21.82%  |
| Intel + Nvidia | 9         | 16.36%  |
| 1 x Nvidia     | 6         | 10.91%  |
| AMD + Nvidia   | 2         | 3.64%   |
| 2 x AMD        | 1         | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 47        | 85.45%  |
| Proprietary | 8         | 14.55%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 60%     |
| 1.01-2.0   | 6         | 10.91%  |
| 0.51-1.0   | 5         | 9.09%   |
| 0.01-0.5   | 4         | 7.27%   |
| 7.01-8.0   | 3         | 5.45%   |
| 3.01-4.0   | 3         | 5.45%   |
| 8.01-16.0  | 1         | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 11        | 19.3%   |
| Samsung Electronics     | 7         | 12.28%  |
| LG Display              | 6         | 10.53%  |
| BOE                     | 6         | 10.53%  |
| Goldstar                | 5         | 8.77%   |
| AU Optronics            | 4         | 7.02%   |
| Apple                   | 4         | 7.02%   |
| AOC                     | 3         | 5.26%   |
| Hewlett-Packard         | 2         | 3.51%   |
| Dell                    | 2         | 3.51%   |
| SKY                     | 1         | 1.75%   |
| Sharp                   | 1         | 1.75%   |
| Lenovo                  | 1         | 1.75%   |
| Chi Mei Optoelectronics | 1         | 1.75%   |
| BenQ                    | 1         | 1.75%   |
| Ancor Communications    | 1         | 1.75%   |
| Acer                    | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 2         | 3.33%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 2         | 3.33%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                     | 1         | 1.67%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 1.67%   |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch        | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 890x500mm 40.2-inch    | 1         | 1.67%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1200x340mm 49.1-inch       | 1         | 1.67%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch        | 1         | 1.67%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 1         | 1.67%   |
| LG Display LCD Monitor LGD06AD 2560x1600 286x179mm 13.3-inch             | 1         | 1.67%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch             | 1         | 1.67%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 1         | 1.67%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch              | 1         | 1.67%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.67%   |
| Hewlett-Packard ALL-in-One HPN4032 1920x1080 527x296mm 23.8-inch         | 1         | 1.67%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch               | 1         | 1.67%   |
| Goldstar TV SSCR GSMC0C8 3840x2160 1600x900mm 72.3-inch                  | 1         | 1.67%   |
| Goldstar MP59HT GSM5B44 1920x1080 480x270mm 21.7-inch                    | 1         | 1.67%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                    | 1         | 1.67%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                   | 1         | 1.67%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                   | 1         | 1.67%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 1         | 1.67%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                        | 1         | 1.67%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                        | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15E0 1920x1080 344x193mm 15.5-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1477 1366x768 309x174mm 14.0-inch          | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1338 1366x768 293x164mm 13.2-inch          | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO1711 1600x900 382x215mm 17.3-inch | 1         | 1.67%   |
| BOE LCD Monitor BOE07B8 1920x1080 294x165mm 13.3-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 1         | 1.67%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 1.67%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 1         | 1.67%   |
| BenQ LCD Monitor PD2700U 3840x2160                                       | 1         | 1.67%   |
| AU Optronics LCD Monitor AUOA08B 1920x1080 344x193mm 15.5-inch           | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x173mm 13.9-inch           | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO12D4 1280x800 216x135mm 10.0-inch            | 1         | 1.67%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                     | 1         | 1.67%   |
| Apple Color LCD APP9CB7 1680x1050 331x207mm 15.4-inch                    | 1         | 1.67%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                      | 1         | 1.67%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                         | 1         | 1.67%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch    | 1         | 1.67%   |
| Acer LCD Monitor XV270U 5120x1440                                        | 1         | 1.67%   |
| Acer LCD Monitor VG272U                                                  | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 22        | 40%     |
| 1366x768 (WXGA)    | 13        | 23.64%  |
| 3840x2160 (4K)     | 4         | 7.27%   |
| 1280x800 (WXGA)    | 3         | 5.45%   |
| 2736x1824          | 2         | 3.64%   |
| 1440x900 (WXGA+)   | 2         | 3.64%   |
| 5120x1440          | 1         | 1.82%   |
| 3840x2400          | 1         | 1.82%   |
| 3840x1080          | 1         | 1.82%   |
| 2560x1600          | 1         | 1.82%   |
| 2560x1440 (QHD)    | 1         | 1.82%   |
| 2560x1080          | 1         | 1.82%   |
| 1680x1050 (WSXGA+) | 1         | 1.82%   |
| 1600x900 (HD+)     | 1         | 1.82%   |
| Unknown            | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 31.03%  |
| 13      | 10        | 17.24%  |
| 21      | 5         | 8.62%   |
| 23      | 4         | 6.9%    |
| 27      | 3         | 5.17%   |
| 14      | 3         | 5.17%   |
| 12      | 3         | 5.17%   |
| 40      | 2         | 3.45%   |
| 17      | 2         | 3.45%   |
| Unknown | 2         | 3.45%   |
| 72      | 1         | 1.72%   |
| 49      | 1         | 1.72%   |
| 33      | 1         | 1.72%   |
| 28      | 1         | 1.72%   |
| 24      | 1         | 1.72%   |
| 10      | 1         | 1.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 43.86%  |
| 201-300     | 9         | 15.79%  |
| 501-600     | 7         | 12.28%  |
| 401-500     | 5         | 8.77%   |
| 351-400     | 3         | 5.26%   |
| 801-900     | 2         | 3.51%   |
| Unknown     | 2         | 3.51%   |
| 701-800     | 1         | 1.75%   |
| 601-700     | 1         | 1.75%   |
| 1501-2000   | 1         | 1.75%   |
| 1001-1500   | 1         | 1.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 39        | 73.58%  |
| 16/10   | 7         | 13.21%  |
| 3/2     | 3         | 5.66%   |
| Unknown | 2         | 3.77%   |
| 32/9    | 1         | 1.89%   |
| 21/9    | 1         | 1.89%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 31.58%  |
| 81-90          | 9         | 15.79%  |
| 201-250        | 7         | 12.28%  |
| 71-80          | 5         | 8.77%   |
| 301-350        | 3         | 5.26%   |
| 501-1000       | 3         | 5.26%   |
| 61-70          | 2         | 3.51%   |
| 151-200        | 2         | 3.51%   |
| Unknown        | 2         | 3.51%   |
| More than 1000 | 1         | 1.75%   |
| 351-500        | 1         | 1.75%   |
| 41-50          | 1         | 1.75%   |
| 251-300        | 1         | 1.75%   |
| 131-140        | 1         | 1.75%   |
| 121-130        | 1         | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 21        | 37.5%   |
| 121-160       | 16        | 28.57%  |
| 51-100        | 11        | 19.64%  |
| 161-240       | 3         | 5.36%   |
| More than 240 | 2         | 3.57%   |
| Unknown       | 2         | 3.57%   |
| 1-50          | 1         | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 50        | 90.91%  |
| 2     | 3         | 5.45%   |
| 3     | 2         | 3.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 36        | 43.37%  |
| Intel                    | 21        | 25.3%   |
| Broadcom                 | 8         | 9.64%   |
| Qualcomm Atheros         | 6         | 7.23%   |
| Xiaomi                   | 2         | 2.41%   |
| MediaTek                 | 2         | 2.41%   |
| Marvell Technology Group | 2         | 2.41%   |
| Samsung Electronics      | 1         | 1.2%    |
| realme                   | 1         | 1.2%    |
| Ralink Technology        | 1         | 1.2%    |
| Qualcomm                 | 1         | 1.2%    |
| NEC Computers            | 1         | 1.2%    |
| DisplayLink              | 1         | 1.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 24.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 4.04%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 4.04%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 4.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 4.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 3.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.02%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 2.02%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 2         | 2.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.02%   |
| Intel Wireless 3165                                               | 2         | 2.02%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.02%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.01%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.01%   |
| realme SDM665-IDP _SN:18689828                                    | 1         | 1.01%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.01%   |
| Qualcomm Redmi Note 8T                                            | 1         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.01%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 1.01%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.01%   |
| NEC Computers WiMAX Mobile Router                                 | 1         | 1.01%   |
| MediaTek Titan                                                    | 1         | 1.01%   |
| MEDIATEK Network controller                                       | 1         | 1.01%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 1.01%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.01%   |
| Intel Wireless 8260                                               | 1         | 1.01%   |
| Intel Wireless 3160                                               | 1         | 1.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.01%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.01%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.01%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.01%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.01%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.01%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 1.01%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.01%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 1.01%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.01%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.01%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 1         | 1.01%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 17        | 37.78%  |
| Realtek Semiconductor    | 12        | 26.67%  |
| Broadcom                 | 7         | 15.56%  |
| Qualcomm Atheros         | 6         | 13.33%  |
| Ralink Technology        | 1         | 2.22%   |
| MEDIATEK                 | 1         | 2.22%   |
| Marvell Technology Group | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 4         | 8.89%   |
| Broadcom BCM4331 802.11a/b/g/n                             | 4         | 8.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 3         | 6.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 4.44%   |
| Realtek RTL8723DE Wireless Network Adapter                 | 2         | 4.44%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 2         | 4.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 4.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 4.44%   |
| Intel Wireless 3165                                        | 2         | 4.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1         | 2.22%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 2.22%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1         | 2.22%   |
| MEDIATEK Network controller                                | 1         | 2.22%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless          | 1         | 2.22%   |
| Intel Wireless 8260                                        | 1         | 2.22%   |
| Intel Wireless 3160                                        | 1         | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 2.22%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 2.22%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 1         | 2.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 2.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 2.22%   |
| Intel Centrino Wireless-N 2230                             | 1         | 2.22%   |
| Intel Centrino Advanced-N 6235                             | 1         | 2.22%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]              | 1         | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 1         | 2.22%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1         | 2.22%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 2.22%   |
| Broadcom BCM4312 802.11b/g LP-PHY                          | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 31        | 58.49%  |
| Intel                    | 8         | 15.09%  |
| Broadcom                 | 5         | 9.43%   |
| Xiaomi                   | 2         | 3.77%   |
| Samsung Electronics      | 1         | 1.89%   |
| realme                   | 1         | 1.89%   |
| Qualcomm Atheros         | 1         | 1.89%   |
| Qualcomm                 | 1         | 1.89%   |
| MediaTek                 | 1         | 1.89%   |
| Marvell Technology Group | 1         | 1.89%   |
| DisplayLink              | 1         | 1.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 45.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 7.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 7.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 3.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.77%   |
| Intel I211 Gigabit Network Connection                             | 2         | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.77%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.89%   |
| realme SDM665-IDP _SN:18689828                                    | 1         | 1.89%   |
| Qualcomm Redmi Note 8T                                            | 1         | 1.89%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.89%   |
| MediaTek Titan                                                    | 1         | 1.89%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.89%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.89%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.89%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.89%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 1.89%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 50.55%  |
| WiFi     | 44        | 48.35%  |
| Unknown  | 1         | 1.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 42        | 53.16%  |
| WiFi     | 37        | 46.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 31        | 56.36%  |
| 1     | 24        | 43.64%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 74.55%  |
| Yes  | 14        | 25.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 39.02%  |
| Realtek Semiconductor           | 9         | 21.95%  |
| Lite-On Technology              | 4         | 9.76%   |
| Apple                           | 4         | 9.76%   |
| Cambridge Silicon Radio         | 2         | 4.88%   |
| Broadcom                        | 2         | 4.88%   |
| Qualcomm Atheros Communications | 1         | 2.44%   |
| Marvell Semiconductor           | 1         | 2.44%   |
| Foxconn / Hon Hai               | 1         | 2.44%   |
| ASUSTek Computer                | 1         | 2.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 11        | 26.83%  |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 12.2%   |
| Realtek Bluetooth Radio                             | 4         | 9.76%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 4.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4.88%   |
| Apple Bluetooth USB Host Controller                 | 2         | 4.88%   |
| Apple Bluetooth Host Controller                     | 2         | 4.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.44%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 2.44%   |
| Lite-On Wireless_Device                             | 1         | 2.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.44%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 2.44%   |
| Lite-On Bluetooth Device                            | 1         | 2.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.44%   |
| Intel Bluetooth wireless interface                  | 1         | 2.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.44%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.44%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 2.44%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 2.44%   |
| ASUS Bluetooth Radio                                | 1         | 2.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 37        | 48.05%  |
| AMD                                  | 19        | 24.68%  |
| Nvidia                               | 13        | 16.88%  |
| Thesycon Systemsoftware & Consulting | 1         | 1.3%    |
| TEAC                                 | 1         | 1.3%    |
| Razer USA                            | 1         | 1.3%    |
| JMTek                                | 1         | 1.3%    |
| Creative Technology                  | 1         | 1.3%    |
| Creative Labs                        | 1         | 1.3%    |
| C-Media Electronics                  | 1         | 1.3%    |
| ASUSTek Computer                     | 1         | 1.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 11.11%  |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 6.67%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 5         | 5.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 3.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 3.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.22%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 2.22%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 2.22%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.22%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 2.22%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.22%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 2.22%   |
| Thesycon Systemsoftware & Consulting E30                                                          | 1         | 1.11%   |
| TEAC TASCAM iXR                                                                                   | 1         | 1.11%   |
| Razer USA Kraken Tournament Edition                                                               | 1         | 1.11%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 1.11%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 1.11%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.11%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.11%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 1.11%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 1.11%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.11%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 1.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.11%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.11%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.11%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.11%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.11%   |
| Creative Technology Sound BlasterX Kratos S5                                                      | 1         | 1.11%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 1         | 1.11%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.11%   |
| ASUSTek Computer USB Audio                                                                        | 1         | 1.11%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.11%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.11%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.11%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.11%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 1.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.11%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.11%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 24%     |
| Micron Technology   | 4         | 16%     |
| Kingston            | 3         | 12%     |
| Crucial             | 3         | 12%     |
| SK Hynix            | 2         | 8%      |
| Corsair             | 2         | 8%      |
| Unknown             | 1         | 4%      |
| Toshiba             | 1         | 4%      |
| Ramaxel Technology  | 1         | 4%      |
| Qimonda             | 1         | 4%      |
| G.Skill             | 1         | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 2         | 7.69%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s      | 2         | 7.69%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                   | 1         | 3.85%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s            | 1         | 3.85%   |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s             | 1         | 3.85%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                | 1         | 3.85%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s      | 1         | 3.85%   |
| Samsung RAM M4 70T5663EH3-CF7 2048MB SODIMM DDR2 2048MT/s     | 1         | 3.85%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s           | 1         | 3.85%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s     | 1         | 3.85%   |
| Qimonda RAM 64T256020EDL2.5C2 2048MB SODIMM DDR2 2048MT/s     | 1         | 3.85%   |
| Micron RAM MT41K256M16LY 2GB SODIMM DDR3 1600MT/s             | 1         | 3.85%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s         | 1         | 3.85%   |
| Micron RAM 16JSF25664HZ-1G4F1 2GB SODIMM DDR3 1334MT/s        | 1         | 3.85%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16384MB SODIMM DDR4 3200MT/s     | 1         | 3.85%   |
| Kingston RAM 99U5471-052.A 8GB DIMM DDR3 1333MT/s             | 1         | 3.85%   |
| Kingston RAM 9905700-070.A01G 16GB SODIMM DDR4 2667MT/s       | 1         | 3.85%   |
| Kingston RAM 9905700-026.A00G 8GB SODIMM DDR4 2667MT/s        | 1         | 3.85%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s        | 1         | 3.85%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s    | 1         | 3.85%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16384MB SODIMM DDR4 2400MT/s | 1         | 3.85%   |
| Crucial RAM BLS8G4D26BFSCK.8FD 8GB DIMM DDR4                  | 1         | 3.85%   |
| Corsair RAM CMK4GX4M1A2400C14 4GB DIMM DDR4 3007MT/s          | 1         | 3.85%   |
| Corsair RAM CMH32GX4M2D3600C18 16GB DIMM DDR4 2133MT/s        | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR4  | 12        | 66.67%  |
| DDR3  | 3         | 16.67%  |
| DDR2  | 2         | 11.11%  |
| SDRAM | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 12        | 66.67%  |
| DIMM   | 6         | 33.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 8         | 40%     |
| 16384 | 5         | 25%     |
| 2048  | 4         | 20%     |
| 8192  | 3         | 15%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 7         | 31.82%  |
| 3200  | 3         | 13.64%  |
| 2133  | 2         | 9.09%   |
| 3600  | 1         | 4.55%   |
| 3007  | 1         | 4.55%   |
| 3000  | 1         | 4.55%   |
| 2400  | 1         | 4.55%   |
| 2048  | 1         | 4.55%   |
| 1600  | 1         | 4.55%   |
| 1334  | 1         | 4.55%   |
| 1333  | 1         | 4.55%   |
| 1066  | 1         | 4.55%   |
| 800   | 1         | 4.55%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 22.86%  |
| Quanta                                 | 5         | 14.29%  |
| Apple                                  | 5         | 14.29%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 8.57%   |
| Suyin                                  | 2         | 5.71%   |
| Luxvisions Innotech Limited            | 2         | 5.71%   |
| webcam                                 | 1         | 2.86%   |
| Syntek                                 | 1         | 2.86%   |
| Sunplus Innovation Technology          | 1         | 2.86%   |
| Realtek Semiconductor                  | 1         | 2.86%   |
| Primax Electronics                     | 1         | 2.86%   |
| Microsoft                              | 1         | 2.86%   |
| Microdia                               | 1         | 2.86%   |
| Logitech                               | 1         | 2.86%   |
| Importek                               | 1         | 2.86%   |
| Acer                                   | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Apple FaceTime HD Camera                                        | 4         | 11.11%  |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 2         | 5.56%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 5.56%   |
| Chicony HP Wide Vision HD Camera                                | 2         | 5.56%   |
| Chicony HD WebCam                                               | 2         | 5.56%   |
| webcam webcam                                                   | 1         | 2.78%   |
| Syntek EasyCamera                                               | 1         | 2.78%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                           | 1         | 2.78%   |
| Realtek HD WebCam                                               | 1         | 2.78%   |
| Quanta HP Webcam                                                | 1         | 2.78%   |
| Quanta HP 5M Camera                                             | 1         | 2.78%   |
| Quanta HD User Facing                                           | 1         | 2.78%   |
| Primax Villem                                                   | 1         | 2.78%   |
| Microsoft LifeCam HD-3000                                       | 1         | 2.78%   |
| Microdia Integrated Camera                                      | 1         | 2.78%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 2.78%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1         | 2.78%   |
| Logitech BRIO 4K Stream Edition                                 | 1         | 2.78%   |
| Importek Webcam HD                                              | 1         | 2.78%   |
| Chicony HP Webcam                                               | 1         | 2.78%   |
| Chicony HP IR Camera                                            | 1         | 2.78%   |
| Chicony HP Integrated Webcam                                    | 1         | 2.78%   |
| Chicony HP HD Webcam [Fixed]                                    | 1         | 2.78%   |
| Chicony HD User Facing                                          | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 1         | 2.78%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 1         | 2.78%   |
| Acer Integrated Camera                                          | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 3         | 60%     |
| Validity Sensors      | 1         | 20%     |
| Synaptics             | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor | 3         | 60%     |
| Validity Sensors VFS495 Fingerprint Reader  | 1         | 20%     |
| Synaptics  WBDI                             | 1         | 20%     |

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
| 0     | 42        | 76.36%  |
| 1     | 11        | 20%     |
| 2     | 2         | 3.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 6         | 37.5%   |
| Fingerprint reader    | 5         | 31.25%  |
| Graphics card         | 3         | 18.75%  |
| Sound                 | 1         | 6.25%   |
| Multimedia controller | 1         | 6.25%   |

