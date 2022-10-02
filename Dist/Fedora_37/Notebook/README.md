Fedora 37 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 37.

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

Total: 46

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Timi          | A35S                        | [c46c820c25](https://linux-hardware.org/?probe=c46c820c25) | Oct 01, 2022 |
| Lenovo        | ThinkPad T470s 20HGS09L0... | [7c384e5578](https://linux-hardware.org/?probe=7c384e5578) | Sep 30, 2022 |
| A-DATA Tec... | XENIA 14                    | [251f390772](https://linux-hardware.org/?probe=251f390772) | Sep 30, 2022 |
| Dell          | Latitude 7430               | [2151370437](https://linux-hardware.org/?probe=2151370437) | Sep 29, 2022 |
| A-DATA Tec... | XENIA 14                    | [e819e5dc14](https://linux-hardware.org/?probe=e819e5dc14) | Sep 29, 2022 |
| HP            | ZBook 15 G3                 | [1d612b997a](https://linux-hardware.org/?probe=1d612b997a) | Sep 29, 2022 |
| ASUSTek       | X550CL                      | [ded047597e](https://linux-hardware.org/?probe=ded047597e) | Sep 28, 2022 |
| Timi          | A35S                        | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [7c62f5131f](https://linux-hardware.org/?probe=7c62f5131f) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [d8b270de2b](https://linux-hardware.org/?probe=d8b270de2b) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9f37c7c4fa](https://linux-hardware.org/?probe=9f37c7c4fa) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0d790a94fa](https://linux-hardware.org/?probe=0d790a94fa) | Sep 25, 2022 |
| Dell          | XPS 15 9520                 | [fab5b34402](https://linux-hardware.org/?probe=fab5b34402) | Sep 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [2e96ddfdd1](https://linux-hardware.org/?probe=2e96ddfdd1) | Sep 25, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [96f4499ec5](https://linux-hardware.org/?probe=96f4499ec5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [91bd22b430](https://linux-hardware.org/?probe=91bd22b430) | Sep 25, 2022 |
| Dell          | XPS 13 9380                 | [332540a4c8](https://linux-hardware.org/?probe=332540a4c8) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| Lenovo        | ThinkPad T440s 20ARA0YL0... | [93eedc638b](https://linux-hardware.org/?probe=93eedc638b) | Sep 24, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [b7f6ab8ad0](https://linux-hardware.org/?probe=b7f6ab8ad0) | Sep 23, 2022 |
| Timi          | A35S                        | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Dell          | XPS 9320                    | [959d1406dd](https://linux-hardware.org/?probe=959d1406dd) | Sep 23, 2022 |
| Acer          | Nitro AN517-51              | [7bd22a5e38](https://linux-hardware.org/?probe=7bd22a5e38) | Sep 20, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1da95a964b](https://linux-hardware.org/?probe=1da95a964b) | Sep 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [be279328b1](https://linux-hardware.org/?probe=be279328b1) | Sep 19, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [3615e82cb6](https://linux-hardware.org/?probe=3615e82cb6) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Irbis         | NB264                       | [e9361bf1c8](https://linux-hardware.org/?probe=e9361bf1c8) | Sep 17, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [9497f1e17f](https://linux-hardware.org/?probe=9497f1e17f) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [ec8f0a9ebf](https://linux-hardware.org/?probe=ec8f0a9ebf) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [8fab790c57](https://linux-hardware.org/?probe=8fab790c57) | Sep 14, 2022 |
| System76      | Lemur Pro                   | [d6682a260a](https://linux-hardware.org/?probe=d6682a260a) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [c05d80959b](https://linux-hardware.org/?probe=c05d80959b) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7326474aae](https://linux-hardware.org/?probe=7326474aae) | Sep 13, 2022 |
| AXDIA Inte... | WINPAD V10                  | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [681486095a](https://linux-hardware.org/?probe=681486095a) | Aug 27, 2022 |
| Lenovo        | ThinkPad W510 4391F66       | [a92e3ba61f](https://linux-hardware.org/?probe=a92e3ba61f) | Aug 19, 2022 |
| HP            | EliteBook 820 G1            | [1bdfc2f218](https://linux-hardware.org/?probe=1bdfc2f218) | Aug 09, 2022 |
| Samsung       | 270E5G/270E5U               | [d1f2245fb4](https://linux-hardware.org/?probe=d1f2245fb4) | Jul 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [43098a1f34](https://linux-hardware.org/?probe=43098a1f34) | Apr 23, 2022 |
| HP            | Laptop 14-dq2xxx            | [2477951c04](https://linux-hardware.org/?probe=2477951c04) | Apr 15, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                             | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| 5.19.8-300.fc37.x86_64                              | 10        | 24.39%  |
| 5.19.11-300.fc37.x86_64                             | 6         | 14.63%  |
| 5.19.10-300.fc37.x86_64                             | 6         | 14.63%  |
| 5.19.9-300.fc37.x86_64                              | 5         | 12.2%   |
| 5.19.7-300.fc37.x86_64                              | 4         | 9.76%   |
| 5.19.12-300.fc37.x86_64                             | 2         | 4.88%   |
| 5.18.0-0.rc2.23.fc37.x86_64                         | 2         | 4.88%   |
| 6.0.0-0.rc6.41.fc38.x86_64                          | 1         | 2.44%   |
| 5.19.4-300.fc37.x86_64                              | 1         | 2.44%   |
| 5.19.10-602.inttf.fc37.x86_64                       | 1         | 2.44%   |
| 5.19.0-xm2.0.fc37.x86_64                            | 1         | 2.44%   |
| 5.19.0-65.fc37.x86_64                               | 1         | 2.44%   |
| 5.19.0-0.rc6.20220714git4a57a8400075.49.fc37.x86_64 | 1         | 2.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.8  | 10        | 24.39%  |
| 5.19.10 | 7         | 17.07%  |
| 5.19.11 | 6         | 14.63%  |
| 5.19.9  | 5         | 12.2%   |
| 5.19.7  | 4         | 9.76%   |
| 5.19.0  | 3         | 7.32%   |
| 5.19.12 | 2         | 4.88%   |
| 5.18.0  | 2         | 4.88%   |
| 6.0.0   | 1         | 2.44%   |
| 5.19.4  | 1         | 2.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19    | 37        | 92.5%   |
| 5.18    | 2         | 5%      |
| 6.0     | 1         | 2.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 40        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 34        | 85%     |
| KDE5  | 5         | 12.5%   |
| XFCE  | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 33        | 82.5%   |
| X11     | 6         | 15%     |
| Tty     | 1         | 2.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 52.5%   |
| GDM     | 14        | 35%     |
| SDDM    | 3         | 7.5%    |
| LightDM | 2         | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 21        | 52.5%   |
| en_GB | 4         | 10%     |
| pt_BR | 3         | 7.5%    |
| fr_FR | 3         | 7.5%    |
| ru_RU | 2         | 5%      |
| ro_RO | 1         | 2.5%    |
| es_GT | 1         | 2.5%    |
| es_AR | 1         | 2.5%    |
| en_ZA | 1         | 2.5%    |
| en_CA | 1         | 2.5%    |
| en_AU | 1         | 2.5%    |
| de_DE | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 34        | 85%     |
| BIOS | 6         | 15%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 35        | 87.5%   |
| Ext4    | 4         | 10%     |
| Overlay | 1         | 2.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 52.5%   |
| GPT     | 18        | 45%     |
| MBR     | 1         | 2.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 92.5%   |
| Yes       | 3         | 7.5%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 87.5%   |
| Yes       | 5         | 12.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 16        | 40%     |
| ASUSTek Computer    | 6         | 15%     |
| Dell                | 5         | 12.5%   |
| Hewlett-Packard     | 4         | 10%     |
| HUAWEI              | 2         | 5%      |
| TUXEDO              | 1         | 2.5%    |
| Timi                | 1         | 2.5%    |
| System76            | 1         | 2.5%    |
| Samsung Electronics | 1         | 2.5%    |
| Irbis               | 1         | 2.5%    |
| Acer                | 1         | 2.5%    |
| A-DATA Technology   | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HUAWEI HVY-WXX9                            | 2         | 5%      |
| TUXEDO InfinityBook S 15/17 Gen7           | 1         | 2.5%    |
| Timi A35S                                  | 1         | 2.5%    |
| System76 Lemur Pro                         | 1         | 2.5%    |
| Samsung 270E5G/270E5U                      | 1         | 2.5%    |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 2.5%    |
| Lenovo ThinkPad X1 Carbon Gen 8 20UAS0X800 | 1         | 2.5%    |
| Lenovo ThinkPad W510 4391F66               | 1         | 2.5%    |
| Lenovo ThinkPad T470s 20HGS09L0K           | 1         | 2.5%    |
| Lenovo ThinkPad T440s 20ARA0YL00           | 1         | 2.5%    |
| Lenovo ThinkPad T14 Gen 2a 20XK000YSP      | 1         | 2.5%    |
| Lenovo ThinkPad T14 Gen 1 20UES08Q15       | 1         | 2.5%    |
| Lenovo ThinkPad Edge E540 20C600AKZA       | 1         | 2.5%    |
| Lenovo ThinkPad E495 20NE001RTX            | 1         | 2.5%    |
| Lenovo ThinkBook 14-IIL 20SL               | 1         | 2.5%    |
| Lenovo ThinkBook 13s G3 ACN 20YA           | 1         | 2.5%    |
| Lenovo Legion 5 Pro 16ITH6H 82JD           | 1         | 2.5%    |
| Lenovo IdeaPad 5 Pro 14ARH7 82SJ           | 1         | 2.5%    |
| Lenovo IdeaPad 5 15ALC05 82LN              | 1         | 2.5%    |
| Lenovo IdeaPad 320-15IAP 80XR              | 1         | 2.5%    |
| Lenovo IdeaPad 310-14ISK 80UG              | 1         | 2.5%    |
| Irbis NB264                                | 1         | 2.5%    |
| HP ZBook 15 G3                             | 1         | 2.5%    |
| HP Laptop 17-cp0xxx                        | 1         | 2.5%    |
| HP Laptop 14-dq2xxx                        | 1         | 2.5%    |
| HP EliteBook 820 G1                        | 1         | 2.5%    |
| Dell XPS 9320                              | 1         | 2.5%    |
| Dell XPS 15 9520                           | 1         | 2.5%    |
| Dell XPS 13 9380                           | 1         | 2.5%    |
| Dell Latitude 7430                         | 1         | 2.5%    |
| Dell Inspiron 15 7000 Gaming               | 1         | 2.5%    |
| ASUS ZenBook UX425IA_UM425IA               | 1         | 2.5%    |
| ASUS X550CL                                | 1         | 2.5%    |
| ASUS ROG Zephyrus M16 GU603ZX_GU603ZX      | 1         | 2.5%    |
| ASUS ROG Zephyrus G14 GA401IH_GA401IH      | 1         | 2.5%    |
| ASUS ROG Strix G513QY_G513QY               | 1         | 2.5%    |
| ASUS ASUS TUF Gaming F15 FX506LI_FX506LI   | 1         | 2.5%    |
| Acer Nitro AN517-51                        | 1         | 2.5%    |
| A-DATA XENIA 14                            | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 9         | 22.5%   |
| Lenovo IdeaPad      | 4         | 10%     |
| Dell XPS            | 3         | 7.5%    |
| ASUS ROG            | 3         | 7.5%    |
| Lenovo ThinkBook    | 2         | 5%      |
| HUAWEI HVY-WXX9     | 2         | 5%      |
| HP Laptop           | 2         | 5%      |
| TUXEDO InfinityBook | 1         | 2.5%    |
| Timi A35S           | 1         | 2.5%    |
| System76 Lemur      | 1         | 2.5%    |
| Samsung 270E5G      | 1         | 2.5%    |
| Lenovo Legion       | 1         | 2.5%    |
| Irbis NB264         | 1         | 2.5%    |
| HP ZBook            | 1         | 2.5%    |
| HP EliteBook        | 1         | 2.5%    |
| Dell Latitude       | 1         | 2.5%    |
| Dell Inspiron       | 1         | 2.5%    |
| ASUS ZenBook        | 1         | 2.5%    |
| ASUS X550CL         | 1         | 2.5%    |
| ASUS ASUS           | 1         | 2.5%    |
| Acer Nitro          | 1         | 2.5%    |
| A-DATA XENIA        | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 12        | 30%     |
| 2020 | 7         | 17.5%   |
| 2022 | 6         | 15%     |
| 2013 | 5         | 12.5%   |
| 2019 | 3         | 7.5%    |
| 2017 | 3         | 7.5%    |
| 2016 | 2         | 5%      |
| 2018 | 1         | 2.5%    |
| 2010 | 1         | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 40        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 33        | 82.5%   |
| Enabled  | 7         | 17.5%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 97.5%   |
| Yes  | 1         | 2.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 14        | 35%     |
| 4.01-8.0   | 7         | 17.5%   |
| 32.01-64.0 | 7         | 17.5%   |
| 16.01-24.0 | 7         | 17.5%   |
| 3.01-4.0   | 3         | 7.5%    |
| 24.01-32.0 | 2         | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 14        | 34.15%  |
| 3.01-4.0  | 11        | 26.83%  |
| 2.01-3.0  | 10        | 24.39%  |
| 8.01-16.0 | 4         | 9.76%   |
| 1.01-2.0  | 2         | 4.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 36        | 90%     |
| 2      | 3         | 7.5%    |
| 3      | 1         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 87.5%   |
| Yes       | 5         | 12.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 57.5%   |
| No        | 17        | 42.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 90%     |
| No        | 4         | 10%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 6         | 15%     |
| Poland              | 3         | 7.5%    |
| Germany             | 3         | 7.5%    |
| France              | 3         | 7.5%    |
| Brazil              | 3         | 7.5%    |
| UK                  | 2         | 5%      |
| Norway              | 2         | 5%      |
| Japan               | 2         | 5%      |
| Turkey              | 1         | 2.5%    |
| Trinidad and Tobago | 1         | 2.5%    |
| Spain               | 1         | 2.5%    |
| South Africa        | 1         | 2.5%    |
| Russia              | 1         | 2.5%    |
| Moldova             | 1         | 2.5%    |
| Mexico              | 1         | 2.5%    |
| Kazakhstan          | 1         | 2.5%    |
| Italy               | 1         | 2.5%    |
| Indonesia           | 1         | 2.5%    |
| India               | 1         | 2.5%    |
| Czechia             | 1         | 2.5%    |
| Canada              | 1         | 2.5%    |
| Austria             | 1         | 2.5%    |
| Australia           | 1         | 2.5%    |
| Argentina           | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Warsaw                        | 3         | 7.5%    |
| Sao Paulo                     | 2         | 5%      |
| Oslo                          | 2         | 5%      |
| Wytheville                    | 1         | 2.5%    |
| Wellington                    | 1         | 2.5%    |
| Udaipur                       | 1         | 2.5%    |
| Tokyo                         | 1         | 2.5%    |
| Surabaya                      | 1         | 2.5%    |
| Shymkent                      | 1         | 2.5%    |
| Shinagawa                     | 1         | 2.5%    |
| Scarborough                   | 1         | 2.5%    |
| San Andres Cholula            | 1         | 2.5%    |
| Rosario                       | 1         | 2.5%    |
| Queens                        | 1         | 2.5%    |
| Plancher-les-Mines            | 1         | 2.5%    |
| Palaiseau                     | 1         | 2.5%    |
| Orekhovo-Zuyevo               | 1         | 2.5%    |
| New York                      | 1         | 2.5%    |
| Matzendorf                    | 1         | 2.5%    |
| Manchester                    | 1         | 2.5%    |
| Málaga                       | 1         | 2.5%    |
| Lynchburg                     | 1         | 2.5%    |
| Langenhagen                   | 1         | 2.5%    |
| Hukvaldy                      | 1         | 2.5%    |
| Fonsorbes                     | 1         | 2.5%    |
| Eberswalde                    | 1         | 2.5%    |
| Denton                        | 1         | 2.5%    |
| Coesfeld                      | 1         | 2.5%    |
| Chaguanas                     | 1         | 2.5%    |
| Cape Town                     | 1         | 2.5%    |
| Caldaro sulla Strada del Vino | 1         | 2.5%    |
| Brisbane                      | 1         | 2.5%    |
| Bracknell                     | 1         | 2.5%    |
| Bălţi                       | 1         | 2.5%    |
| Antakya                       | 1         | 2.5%    |
| Unknown                       | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 13        | 13     | 28.26%  |
| WDC                         | 4         | 5      | 8.7%    |
| Kingston                    | 4         | 4      | 8.7%    |
| Unknown                     | 3         | 4      | 6.52%   |
| SK hynix                    | 3         | 3      | 6.52%   |
| Toshiba                     | 2         | 2      | 4.35%   |
| Seagate                     | 2         | 2      | 4.35%   |
| Sandisk                     | 2         | 2      | 4.35%   |
| Micron Technology           | 2         | 2      | 4.35%   |
| Intel                       | 2         | 2      | 4.35%   |
| YMTC                        | 1         | 1      | 2.17%   |
| Yangtze Memory Technologies | 1         | 1      | 2.17%   |
| XPG                         | 1         | 1      | 2.17%   |
| Team                        | 1         | 1      | 2.17%   |
| Micron/Crucial Technology   | 1         | 1      | 2.17%   |
| KIOXIA                      | 1         | 2      | 2.17%   |
| Kingston Technology Company | 1         | 1      | 2.17%   |
| HGST                        | 1         | 1      | 2.17%   |
| ADATA Technology            | 1         | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB                            | 2         | 4.17%   |
| Kingston OM8PCP3512F-AB 512GB                         | 2         | 4.17%   |
| YMTC PC005 512GB                                      | 1         | 2.08%   |
| Yangtze Memory NVMe SSD Drive 512GB                   | 1         | 2.08%   |
| XPG GAMMIX S50 Lite 512GB                             | 1         | 2.08%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                      | 1         | 2.08%   |
| WDC WD5000LPCX-24VHAT0 500GB                          | 1         | 2.08%   |
| WDC WD10SPZX-08Z10 1TB                                | 1         | 2.08%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB                  | 1         | 2.08%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB                  | 1         | 2.08%   |
| Unknown SL64G  64GB                                   | 1         | 2.08%   |
| Unknown SD256  249GB                                  | 1         | 2.08%   |
| Unknown MMC Card  128GB                               | 1         | 2.08%   |
| Unknown 032GE4  32GB                                  | 1         | 2.08%   |
| Toshiba NVMe SSD Drive 256GB                          | 1         | 2.08%   |
| Toshiba MQ02ABD100H 1TB                               | 1         | 2.08%   |
| Team TM8PS7128G 128GB SSD                             | 1         | 2.08%   |
| SK hynix SHGP31-1000GM-2 1TB                          | 1         | 2.08%   |
| SK hynix SHGP31-1000GM 1TB                            | 1         | 2.08%   |
| SK hynix PC801 NVMe 1TB                               | 1         | 2.08%   |
| Seagate ST2000LX001-1RG174 2TB                        | 1         | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB                        | 1         | 2.08%   |
| Sandisk WD Blue SN570 1TB                             | 1         | 2.08%   |
| Sandisk WD Black SN850 500GB                          | 1         | 2.08%   |
| Samsung SSD 970 EVO Plus 500GB                        | 1         | 2.08%   |
| Samsung SSD 840 Series 250GB                          | 1         | 2.08%   |
| Samsung PM9A1 NVMe 1024GB                             | 1         | 2.08%   |
| Samsung NVMe SSD Drive 1024GB                         | 1         | 2.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 1         | 2.08%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                      | 1         | 2.08%   |
| Samsung MZVLQ1T0HBLB-00B00 1TB                        | 1         | 2.08%   |
| Samsung MZVLB512HBJQ-000L7 512GB                      | 1         | 2.08%   |
| Samsung MZVLB1T0HBLR-000L7 1TB                        | 1         | 2.08%   |
| Samsung MZVL2512HCJQ-00BL2 512GB                      | 1         | 2.08%   |
| Samsung MZALQ512HBLU-00BL2 512GB                      | 1         | 2.08%   |
| Micron/Crucial NVMe SSD Drive 500GB                   | 1         | 2.08%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD              | 1         | 2.08%   |
| Micron 3400_MTFDKBA1T0TFH 1TB                         | 1         | 2.08%   |
| KIOXIA KBG40ZNV512G 512GB                             | 1         | 2.08%   |
| Kingston Company U-SNS8154P3 NVMe SSD 512GB           | 1         | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 33.33%  |
| Seagate | 2         | 2      | 33.33%  |
| Toshiba | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 2         | 2      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Team                | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Micron Technology   | 1         | 1      | 14.29%  |
| Intel               | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 29        | 32     | 64.44%  |
| SSD  | 7         | 7      | 15.56%  |
| HDD  | 6         | 6      | 13.33%  |
| MMC  | 3         | 4      | 6.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 29        | 32     | 65.91%  |
| SATA | 12        | 13     | 27.27%  |
| MMC  | 3         | 4      | 6.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 8         | 8      | 61.54%  |
| 0.51-1.0   | 4         | 4      | 30.77%  |
| 1.01-2.0   | 1         | 1      | 7.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1001-2000  | 10        | 24.39%  |
| 501-1000   | 9         | 21.95%  |
| 251-500    | 8         | 19.51%  |
| 1-20       | 6         | 14.63%  |
| Unknown    | 3         | 7.32%   |
| 101-250    | 2         | 4.88%   |
| 21-50      | 1         | 2.44%   |
| 2001-3000  | 1         | 2.44%   |
| 51-100     | 1         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 13        | 31.71%  |
| 101-250  | 7         | 17.07%  |
| 501-1000 | 6         | 14.63%  |
| 251-500  | 5         | 12.2%   |
| 21-50    | 5         | 12.2%   |
| Unknown  | 3         | 7.32%   |
| 51-100   | 2         | 4.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Micron Technology | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 100%    |

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
| Detected | 22        | 28     | 52.38%  |
| Works    | 19        | 20     | 45.24%  |
| Malfunc  | 1         | 1      | 2.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 20        | 37.04%  |
| Samsung Electronics          | 12        | 22.22%  |
| AMD                          | 5         | 9.26%   |
| SanDisk                      | 4         | 7.41%   |
| SK hynix                     | 3         | 5.56%   |
| Kingston Technology Company  | 3         | 5.56%   |
| Yangtze Memory Technologies  | 2         | 3.7%    |
| Toshiba America Info Systems | 1         | 1.85%   |
| Micron/Crucial Technology    | 1         | 1.85%   |
| Micron Technology            | 1         | 1.85%   |
| KIOXIA                       | 1         | 1.85%   |
| ADATA Technology             | 1         | 1.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 9.26%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 9.26%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 7.41%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 7.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 5.56%   |
| Yangtze Memory Non-Volatile memory controller                                  | 2         | 3.7%    |
| SK hynix Gold P31 SSD                                                          | 2         | 3.7%    |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 3.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 3.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 3.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.85%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 1.85%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.85%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 1.85%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 1.85%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.85%   |
| Micron/Crucial Non-Volatile memory controller                                  | 1         | 1.85%   |
| Micron Non-Volatile memory controller                                          | 1         | 1.85%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.85%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 1.85%   |
| Intel SSD 600P Series                                                          | 1         | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.85%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 1.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.85%   |
| ADATA A Non-Volatile memory controller                                         | 1         | 1.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 29        | 54.72%  |
| SATA | 20        | 37.74%  |
| RAID | 4         | 7.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 27        | 67.5%   |
| AMD    | 13        | 32.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 5%      |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 5%      |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 5%      |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.5%    |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 2.5%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 2.5%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 2.5%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 2.5%    |
| Intel Core i5-4310U CPU @ 2.00GHz             | 1         | 2.5%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 2.5%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 2.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2.5%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 2.5%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 2.5%    |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 2.5%    |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 2.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.5%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 2.5%    |
| Intel 12th Gen Core i9-12900H                 | 1         | 2.5%    |
| Intel 12th Gen Core i7-12700H                 | 1         | 2.5%    |
| Intel 12th Gen Core i7-1265U                  | 1         | 2.5%    |
| Intel 12th Gen Core i7-1260P                  | 1         | 2.5%    |
| Intel 12th Gen Core i5-1240P                  | 1         | 2.5%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 2.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 2.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 2.5%    |
| Intel 11th Gen Core i3-1125G4 @ 2.00GHz       | 1         | 2.5%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 2.5%    |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 1         | 2.5%    |
| AMD Ryzen 7 6800HS Creator Edition            | 1         | 2.5%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 2.5%    |
| AMD Ryzen 7 4800HS with Radeon Graphics       | 1         | 2.5%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 2.5%    |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics    | 1         | 2.5%    |
| AMD Ryzen 5 5600U with Radeon Graphics        | 1         | 2.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Other           | 9         | 22.5%   |
| Intel Core i5   | 9         | 22.5%   |
| AMD Ryzen 5     | 6         | 15%     |
| Intel Core i7   | 5         | 12.5%   |
| AMD Ryzen 7     | 4         | 10%     |
| Intel Core i3   | 2         | 5%      |
| Intel Celeron   | 2         | 5%      |
| AMD Ryzen 9     | 1         | 2.5%    |
| AMD Ryzen 7 PRO | 1         | 2.5%    |
| AMD Ryzen 5 PRO | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 13        | 32.5%   |
| 2      | 9         | 22.5%   |
| 8      | 7         | 17.5%   |
| 6      | 6         | 15%     |
| 14     | 2         | 5%      |
| 12     | 2         | 5%      |
| 10     | 1         | 2.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 40        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 37        | 92.5%   |
| 1      | 3         | 7.5%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 40        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x906a3    | 4         | 10%     |
| 0x0a50000c | 4         | 10%     |
| 0x806ec    | 3         | 7.5%    |
| 0x08600106 | 3         | 7.5%    |
| 0x806c1    | 2         | 5%      |
| 0x40651    | 2         | 5%      |
| 0x306a9    | 2         | 5%      |
| 0x08600104 | 2         | 5%      |
| Unknown    | 2         | 5%      |
| 0xa0652    | 1         | 2.5%    |
| 0x906ea    | 1         | 2.5%    |
| 0x906e9    | 1         | 2.5%    |
| 0x906a4    | 1         | 2.5%    |
| 0x806e9    | 1         | 2.5%    |
| 0x806d1    | 1         | 2.5%    |
| 0x706e5    | 1         | 2.5%    |
| 0x706a8    | 1         | 2.5%    |
| 0x506e3    | 1         | 2.5%    |
| 0x506c9    | 1         | 2.5%    |
| 0x406e3    | 1         | 2.5%    |
| 0x306c3    | 1         | 2.5%    |
| 0x0a404102 | 1         | 2.5%    |
| 0x08608103 | 1         | 2.5%    |
| 0x08608102 | 1         | 2.5%    |
| 0x08108102 | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 6         | 15%     |
| Zen 2            | 5         | 12.5%   |
| Alderlake Hybrid | 5         | 12.5%   |
| Zen 3            | 4         | 10%     |
| TigerLake        | 3         | 7.5%    |
| Haswell          | 3         | 7.5%    |
| Unknown          | 3         | 7.5%    |
| Skylake          | 2         | 5%      |
| IvyBridge        | 2         | 5%      |
| Icelake          | 2         | 5%      |
| Zen+             | 1         | 2.5%    |
| Nehalem          | 1         | 2.5%    |
| Goldmont plus    | 1         | 2.5%    |
| Goldmont         | 1         | 2.5%    |
| CometLake        | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 52.08%  |
| AMD    | 13        | 27.08%  |
| Nvidia | 10        | 20.83%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                           | 5         | 10.2%   |
| Intel Alder Lake-P Integrated Graphics Controller                    | 4         | 8.16%   |
| AMD Cezanne                                                          | 4         | 8.16%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M] | 2         | 4.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 2         | 4.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                     | 2         | 4.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 2         | 4.08%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 2         | 4.08%   |
| AMD Lucienne                                                         | 2         | 4.08%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 1         | 2.04%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                      | 1         | 2.04%   |
| Nvidia GT216GLM [Quadro FX 880M]                                     | 1         | 2.04%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 2.04%   |
| Nvidia GM107GLM [Quadro M1000M]                                      | 1         | 2.04%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                           | 1         | 2.04%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 2.04%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                           | 1         | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 2.04%   |
| Intel VGA compatible controller                                      | 1         | 2.04%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 1         | 2.04%   |
| Intel Tiger Lake UHD Graphics                                        | 1         | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                  | 1         | 2.04%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                               | 1         | 2.04%   |
| Intel HD Graphics 630                                                | 1         | 2.04%   |
| Intel HD Graphics 620                                                | 1         | 2.04%   |
| Intel HD Graphics 500                                                | 1         | 2.04%   |
| Intel GeminiLake [UHD Graphics 600]                                  | 1         | 2.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 1         | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 1         | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 1         | 2.04%   |
| AMD Rembrandt [Radeon 680M]                                          | 1         | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 2.04%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                 | 1         | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 42.5%   |
| 1 x AMD        | 12        | 30%     |
| Intel + Nvidia | 8         | 20%     |
| 1 x Nvidia     | 2         | 5%      |
| 2 x AMD        | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 36        | 90%     |
| Proprietary | 4         | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 57.5%   |
| 0.01-0.5   | 8         | 20%     |
| 1.01-2.0   | 4         | 10%     |
| 3.01-4.0   | 2         | 5%      |
| 0.51-1.0   | 2         | 5%      |
| 8.01-16.0  | 1         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 14        | 28.57%  |
| Chimei Innolux          | 6         | 12.24%  |
| AU Optronics            | 5         | 10.2%   |
| LG Display              | 3         | 6.12%   |
| Sharp                   | 2         | 4.08%   |
| Samsung Electronics     | 2         | 4.08%   |
| PANDA                   | 2         | 4.08%   |
| Lenovo                  | 2         | 4.08%   |
| InfoVision              | 2         | 4.08%   |
| Hewlett-Packard         | 2         | 4.08%   |
| Dell                    | 2         | 4.08%   |
| CSO                     | 2         | 4.08%   |
| Chi Mei Optoelectronics | 2         | 4.08%   |
| Vestel Elektronik       | 1         | 2.04%   |
| Goldstar                | 1         | 2.04%   |
| BenQ                    | 1         | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 3.92%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 2         | 3.92%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch       | 1         | 1.96%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch                  | 1         | 1.96%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                  | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch    | 1         | 1.96%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch       | 1         | 1.96%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 1         | 1.96%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                  | 1         | 1.96%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 1.96%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch                 | 1         | 1.96%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 1         | 1.96%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch             | 1         | 1.96%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 1         | 1.96%   |
| Hewlett-Packard OMEN by HP 27 HPN3422 2560x1440 598x336mm 27.0-inch      | 1         | 1.96%   |
| Hewlett-Packard E271i HWP3106 1920x1080 600x340mm 27.2-inch              | 1         | 1.96%   |
| Goldstar W2252 GSM567D 1680x1050 490x320mm 23.0-inch                     | 1         | 1.96%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                        | 1         | 1.96%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 1         | 1.96%   |
| Dell P2714H DELD05E 1920x1080 600x340mm 27.2-inch                        | 1         | 1.96%   |
| CSO LCD Monitor CSO1606 2560x1600 345x215mm 16.0-inch                    | 1         | 1.96%   |
| CSO LCD Monitor CSO140C 2880x1800 302x188mm 14.0-inch                    | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15B4 1366x768 344x193mm 15.5-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch         | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 1.96%   |
| BOE LCD Monitor BOE0A0B 2560x1600 344x215mm 16.0-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE0961 1920x1200 302x188mm 14.0-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE0953 1920x1080 382x215mm 17.3-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE0839 1920x1080 382x215mm 17.3-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE07C8 3840x2160 309x174mm 14.0-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE06F2 1920x1080 309x173mm 13.9-inch                    | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 23        | 47.92%  |
| 1920x1200 (WUXGA)  | 7         | 14.58%  |
| 1366x768 (WXGA)    | 6         | 12.5%   |
| 2560x1440 (QHD)    | 3         | 6.25%   |
| 3840x2160 (4K)     | 2         | 4.17%   |
| 2560x1600          | 2         | 4.17%   |
| 3840x2400          | 1         | 2.08%   |
| 3456x2160          | 1         | 2.08%   |
| 2880x1800          | 1         | 2.08%   |
| 1680x1050 (WSXGA+) | 1         | 2.08%   |
| 1600x900 (HD+)     | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 16        | 31.37%  |
| 13     | 11        | 21.57%  |
| 14     | 7         | 13.73%  |
| 16     | 4         | 7.84%   |
| 27     | 3         | 5.88%   |
| 24     | 3         | 5.88%   |
| 23     | 2         | 3.92%   |
| 17     | 2         | 3.92%   |
| 84     | 1         | 1.96%   |
| 31     | 1         | 1.96%   |
| 12     | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 65.31%  |
| 501-600     | 6         | 12.24%  |
| 351-400     | 4         | 8.16%   |
| 201-300     | 4         | 8.16%   |
| 601-700     | 1         | 2.04%   |
| 401-500     | 1         | 2.04%   |
| 1501-2000   | 1         | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 31        | 72.09%  |
| 16/10 | 11        | 25.58%  |
| 3/2   | 1         | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 33.33%  |
| 81-90          | 15        | 29.41%  |
| 71-80          | 3         | 5.88%   |
| 301-350        | 3         | 5.88%   |
| 201-250        | 3         | 5.88%   |
| 111-120        | 3         | 5.88%   |
| 251-300        | 2         | 3.92%   |
| 121-130        | 2         | 3.92%   |
| More than 1000 | 1         | 1.96%   |
| 61-70          | 1         | 1.96%   |
| 351-500        | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 21        | 44.68%  |
| 51-100        | 9         | 19.15%  |
| 161-240       | 8         | 17.02%  |
| 101-120       | 5         | 10.64%  |
| More than 240 | 4         | 8.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 31        | 77.5%   |
| 2     | 7         | 17.5%   |
| 3     | 2         | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 45.61%  |
| Realtek Semiconductor | 20        | 35.09%  |
| Qualcomm Atheros      | 4         | 7.02%   |
| Sierra Wireless       | 2         | 3.51%   |
| MediaTek              | 2         | 3.51%   |
| Ralink                | 1         | 1.75%   |
| Lenovo                | 1         | 1.75%   |
| Hewlett-Packard       | 1         | 1.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 19.12%  |
| Intel Wi-Fi 6 AX200                                               | 8         | 11.76%  |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 5.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 2.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 2.94%   |
| Intel Wireless 7260                                               | 2         | 2.94%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.94%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.94%   |
| Sierra Wireless EM7455                                            | 1         | 1.47%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.47%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.47%   |
| Realtek Realtek Network controller                                | 1         | 1.47%   |
| Realtek 802.11ac NIC                                              | 1         | 1.47%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.47%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.47%   |
| Intel Wireless-AC 9260                                            | 1         | 1.47%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.47%   |
| Intel Wireless 8260                                               | 1         | 1.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.47%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.47%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.47%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.47%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.47%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.47%   |
| HP lt4112 Gobi 4G Module Network Device                           | 1         | 1.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 59.09%  |
| Realtek Semiconductor | 8         | 18.18%  |
| Qualcomm Atheros      | 4         | 9.09%   |
| Sierra Wireless       | 2         | 4.55%   |
| MediaTek              | 2         | 4.55%   |
| Ralink                | 1         | 2.27%   |
| Hewlett-Packard       | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 8         | 18.18%  |
| Intel Alder Lake-P PCH CNVi WiFi                              | 4         | 9.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 4.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 4.55%   |
| Intel Wireless 7260                                           | 2         | 4.55%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 4.55%   |
| Sierra Wireless EM7455                                        | 1         | 2.27%   |
| Sierra Wireless EM7345 4G LTE                                 | 1         | 2.27%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.27%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 1         | 2.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 2.27%   |
| Realtek Realtek Network controller                            | 1         | 2.27%   |
| Realtek 802.11ac NIC                                          | 1         | 2.27%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                     | 1         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 2.27%   |
| Intel Wireless-AC 9260                                        | 1         | 2.27%   |
| Intel Wireless 8265 / 8275                                    | 1         | 2.27%   |
| Intel Wireless 8260                                           | 1         | 2.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 2.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 2.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 2.27%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 2.27%   |
| HP lt4112 Gobi 4G Module Network Device                       | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 16        | 69.57%  |
| Intel                 | 6         | 26.09%  |
| Lenovo                | 1         | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 54.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 8.33%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 8.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 4.17%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 4.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 4.17%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 4.17%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 63.49%  |
| Ethernet | 23        | 36.51%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 83.72%  |
| Ethernet | 7         | 16.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 50%     |
| 1     | 17        | 42.5%   |
| 3     | 2         | 5%      |
| 0     | 1         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 77.5%   |
| Yes  | 9         | 22.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 69.44%  |
| Realtek Semiconductor           | 5         | 13.89%  |
| Qualcomm Atheros Communications | 3         | 8.33%   |
| Foxconn / Hon Hai               | 2         | 5.56%   |
| IMC Networks                    | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                          | 8         | 22.22%  |
| Intel AX201 Bluetooth                          | 5         | 13.89%  |
| Realtek Bluetooth Radio                        | 4         | 11.11%  |
| Intel Bluetooth wireless interface             | 4         | 11.11%  |
| Intel Bluetooth Device                         | 4         | 11.11%  |
| Qualcomm Atheros  Bluetooth Device             | 2         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 5.56%   |
| Realtek RTL8723B Bluetooth                     | 1         | 2.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 2.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 2.78%   |
| Intel AX210 Bluetooth                          | 1         | 2.78%   |
| IMC Networks Wireless_Device                   | 1         | 2.78%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 2.78%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 27        | 52.94%  |
| AMD                                  | 13        | 25.49%  |
| Nvidia                               | 7         | 13.73%  |
| Lenovo                               | 2         | 3.92%   |
| Thesycon Systemsoftware & Consulting | 1         | 1.96%   |
| C-Media Electronics                  | 1         | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Renoir Radeon High Definition Audio Controller                  | 11        | 16.67%  |
| AMD Family 17h/19h HD Audio Controller                              | 11        | 16.67%  |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 5         | 7.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 3         | 4.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 2         | 3.03%   |
| Intel Sunrise Point-LP HD Audio                                     | 2         | 3.03%   |
| Intel Haswell-ULT HD Audio Controller                               | 2         | 3.03%   |
| Intel Comet Lake PCH-LP cAVS                                        | 2         | 3.03%   |
| Intel 8 Series HD Audio Controller                                  | 2         | 3.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2         | 3.03%   |
| Thesycon Systemsoftware & Consulting D50s                           | 1         | 1.52%   |
| Nvidia GT216 HDMI Audio Controller                                  | 1         | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 1.52%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 1         | 1.52%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 1.52%   |
| Nvidia Audio device                                                 | 1         | 1.52%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                           | 1         | 1.52%   |
| Lenovo ThinkPad Dock USB Audio                                      | 1         | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 1.52%   |
| Intel Tiger Lake-H HD Audio Controller                              | 1         | 1.52%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 1         | 1.52%   |
| Intel Comet Lake PCH cAVS                                           | 1         | 1.52%   |
| Intel CM238 HD Audio Controller                                     | 1         | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1         | 1.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 1.52%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 1.52%   |
| Intel Cannon Lake PCH cAVS                                          | 1         | 1.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1         | 1.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 1         | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 1         | 1.52%   |
| C-Media Electronics USB MICROPHONE                                  | 1         | 1.52%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 1         | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 1.52%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 1         | 1.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 39.29%  |
| SK hynix            | 5         | 17.86%  |
| Micron Technology   | 4         | 14.29%  |
| Kingston            | 2         | 7.14%   |
| A-DATA Technology   | 2         | 7.14%   |
| Goldkey             | 1         | 3.57%   |
| G.Skill             | 1         | 3.57%   |
| Crucial             | 1         | 3.57%   |
| Unknown             | 1         | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 7.14%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 7.14%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 3.57%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 3.57%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 3.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 3.57%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 3.57%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 3.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 3.57%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 1         | 3.57%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 3.57%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.57%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB SODIMM LPDDR4 4266MT/s           | 1         | 3.57%   |
| Samsung RAM K4AAG165WA-BCTD 8GB SODIMM DDR4 2667MT/s             | 1         | 3.57%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s               | 1         | 3.57%   |
| Micron RAM MT53E512M32D2NP-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 3.57%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 3.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 3.57%   |
| Kingston RAM 9905624-008.A00G 8GB SODIMM DDR4 2133MT/s           | 1         | 3.57%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 3.57%   |
| Goldkey RAM GKE160SO102408-2666 16GB SODIMM DDR4 2667MT/s        | 1         | 3.57%   |
| G.Skill RAM Module 16GB SODIMM DDR4 2133MT/s                     | 1         | 3.57%   |
| Crucial RAM CB8GS2400.C8D 8GB SODIMM DDR4 2400MT/s               | 1         | 3.57%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 3.57%   |
| A-DATA RAM AO1P26KC8T1-BXPS 8GB SODIMM DDR4 2667MT/s             | 1         | 3.57%   |
| Unknown                                                          | 1         | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 12        | 60%     |
| LPDDR5 | 2         | 10%     |
| LPDDR4 | 2         | 10%     |
| DDR5   | 2         | 10%     |
| LPDDR3 | 1         | 5%      |
| DDR3   | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 14        | 70%     |
| Row Of Chips | 6         | 30%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 11        | 47.83%  |
| 16384 | 6         | 26.09%  |
| 4096  | 5         | 21.74%  |
| 32768 | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 8         | 33.33%  |
| 2667  | 4         | 16.67%  |
| 2133  | 3         | 12.5%   |
| 6400  | 2         | 8.33%   |
| 4800  | 2         | 8.33%   |
| 2400  | 2         | 8.33%   |
| 4267  | 1         | 4.17%   |
| 4266  | 1         | 4.17%   |
| 1600  | 1         | 4.17%   |

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
| Chicony Electronics                    | 13        | 35.14%  |
| IMC Networks                           | 4         | 10.81%  |
| Microdia                               | 3         | 8.11%   |
| Acer                                   | 3         | 8.11%   |
| Syntek                                 | 2         | 5.41%   |
| Quanta                                 | 2         | 5.41%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.41%   |
| USB Camera CS                          | 1         | 2.7%    |
| Sunplus Innovation Technology          | 1         | 2.7%    |
| Silicon Motion                         | 1         | 2.7%    |
| Luxvisions Innotech Limited            | 1         | 2.7%    |
| Logitech                               | 1         | 2.7%    |
| Lite-On Technology                     | 1         | 2.7%    |
| Lenovo                                 | 1         | 2.7%    |
| Goodong Industry                       | 1         | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 7         | 18.92%  |
| Acer Integrated Camera                                          | 3         | 8.11%   |
| Syntek EasyCamera                                               | 2         | 5.41%   |
| Microdia Integrated_Webcam_HD                                   | 2         | 5.41%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 2         | 5.41%   |
| Chicony USB2.0 Camera                                           | 2         | 5.41%   |
| USB Camera CS USB Camera CS                                     | 1         | 2.7%    |
| Sunplus Integrated Webcam                                       | 1         | 2.7%    |
| Silicon Motion WebCam SC-10HDD12636N                            | 1         | 2.7%    |
| Quanta HP TrueVision HD Camera                                  | 1         | 2.7%    |
| Quanta HD Webcam                                                | 1         | 2.7%    |
| Microdia Integrated_Webcam_FHD                                  | 1         | 2.7%    |
| Luxvisions Innotech Limited Integrated RGB Camera               | 1         | 2.7%    |
| Logitech Webcam C310                                            | 1         | 2.7%    |
| Lite-On Integrated Camera                                       | 1         | 2.7%    |
| Lenovo Integrated Webcam [R5U877]                               | 1         | 2.7%    |
| IMC Networks XiaoMi Webcam                                      | 1         | 2.7%    |
| IMC Networks HD Camera                                          | 1         | 2.7%    |
| Goodong Industry USB2.0 HD UVC WebCam                           | 1         | 2.7%    |
| Chicony USB2.0 HD UVC WebCam                                    | 1         | 2.7%    |
| Chicony HP HD Webcam                                            | 1         | 2.7%    |
| Chicony HP HD Camera                                            | 1         | 2.7%    |
| Chicony HD Webcam                                               | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 1         | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 30%     |
| Synaptics                  | 3         | 30%     |
| Shenzhen Goodix Technology | 3         | 30%     |
| Elan Microelectronics      | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 30%     |
| Shenzhen Goodix  FingerPrint Device               | 3         | 30%     |
| Validity Sensors VFS495 Fingerprint Reader        | 2         | 20%     |
| Validity Sensors Synaptics WBDI                   | 1         | 10%     |
| Elan ELAN:ARM-M4                                  | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 33.33%  |
| Broadcom 58200                      | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 21        | 52.5%   |
| 1     | 16        | 40%     |
| 2     | 3         | 7.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 47.62%  |
| Graphics card            | 3         | 14.29%  |
| Multimedia controller    | 2         | 9.52%   |
| Card reader              | 2         | 9.52%   |
| Net/wireless             | 1         | 4.76%   |
| Communication controller | 1         | 4.76%   |
| Chipcard                 | 1         | 4.76%   |
| Camera                   | 1         | 4.76%   |

