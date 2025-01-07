Kylin - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Kylin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 53

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [f38d8fa44e](https://linux-hardware.org/?probe=f38d8fa44e) | Nov 16, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [c8cf89df2f](https://linux-hardware.org/?probe=c8cf89df2f) | Oct 19, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [201204cf6c](https://linux-hardware.org/?probe=201204cf6c) | Oct 06, 2024 |
| Timi          | Redmi G 2022                | [115c01ddd7](https://linux-hardware.org/?probe=115c01ddd7) | Sep 29, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [28057f9ed2](https://linux-hardware.org/?probe=28057f9ed2) | Sep 23, 2024 |
| Lenovo        | Legion R9000P ARX8 82WM     | [c16aaf7f55](https://linux-hardware.org/?probe=c16aaf7f55) | Sep 12, 2024 |
| ASUSTek       | TUF Gaming FX505GE_FX86F... | [f8a5fac34e](https://linux-hardware.org/?probe=f8a5fac34e) | Aug 28, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UDA... | [2d97d245a2](https://linux-hardware.org/?probe=2d97d245a2) | Aug 10, 2024 |
| Alienware     | m15 R6                      | [12574a3dbf](https://linux-hardware.org/?probe=12574a3dbf) | Jul 21, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [d57f4d29a8](https://linux-hardware.org/?probe=d57f4d29a8) | Jul 18, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [0a947b6f0e](https://linux-hardware.org/?probe=0a947b6f0e) | Jul 17, 2024 |
| Lenovo        | ThinkPad Edge E531 68851... | [ccbb2df5c2](https://linux-hardware.org/?probe=ccbb2df5c2) | Jul 02, 2024 |
| Lenovo        | ThinkPad T460p 20FWA00PC... | [7e6b842321](https://linux-hardware.org/?probe=7e6b842321) | Jun 21, 2024 |
| Lenovo        | ThinkPad T460p 20FWA00PC... | [f214e8aea1](https://linux-hardware.org/?probe=f214e8aea1) | Jun 21, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [91141580f8](https://linux-hardware.org/?probe=91141580f8) | Jun 07, 2024 |
| HP            | ZBook Power 15.6 inch G9... | [2aef3e835d](https://linux-hardware.org/?probe=2aef3e835d) | Jun 01, 2024 |
| HASEE Comp... | GI5CN54                     | [c0c280376b](https://linux-hardware.org/?probe=c0c280376b) | May 22, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [85f843311f](https://linux-hardware.org/?probe=85f843311f) | May 18, 2024 |
| Timi          | TM1612                      | [b2a95327e3](https://linux-hardware.org/?probe=b2a95327e3) | May 17, 2024 |
| Lenovo        | Legion R9000P ARX8 82WM     | [5c9388af66](https://linux-hardware.org/?probe=5c9388af66) | May 10, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [db370ffb35](https://linux-hardware.org/?probe=db370ffb35) | May 05, 2024 |
| Acer          | Swift SFX14-41G             | [47966edb56](https://linux-hardware.org/?probe=47966edb56) | Apr 09, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TAA... | [de970e3adc](https://linux-hardware.org/?probe=de970e3adc) | Mar 21, 2024 |
| HUAWEI        | CREM-WXX9                   | [cf753bfc89](https://linux-hardware.org/?probe=cf753bfc89) | Dec 05, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [d6486c4e50](https://linux-hardware.org/?probe=d6486c4e50) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming FX505GT          | [a5fde2a0ed](https://linux-hardware.org/?probe=a5fde2a0ed) | Oct 24, 2023 |
| Dell          | Vostro 3350                 | [1034a53a9d](https://linux-hardware.org/?probe=1034a53a9d) | Sep 30, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [5168f99a06](https://linux-hardware.org/?probe=5168f99a06) | Sep 26, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [0d1c562190](https://linux-hardware.org/?probe=0d1c562190) | Sep 08, 2023 |
| Apple         | MacBookPro12,1              | [4a1def29d3](https://linux-hardware.org/?probe=4a1def29d3) | Aug 09, 2023 |
| ASUSTek       | UX31LA                      | [0695e3bb09](https://linux-hardware.org/?probe=0695e3bb09) | Aug 08, 2023 |
| HUAWEI        | QingYun L420 KLVV-W5821     | [e3227788f6](https://linux-hardware.org/?probe=e3227788f6) | Jul 08, 2023 |
| Lenovo        | ThinkBook 16 G5+ ARP 21J... | [211f5e5cf1](https://linux-hardware.org/?probe=211f5e5cf1) | Jul 02, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [80b6536a46](https://linux-hardware.org/?probe=80b6536a46) | Jun 28, 2023 |
| HUAWEI        | MACH-WX9                    | [016268562d](https://linux-hardware.org/?probe=016268562d) | Jun 21, 2023 |
| HUAWEI        | MACH-WX9                    | [25bc3b1533](https://linux-hardware.org/?probe=25bc3b1533) | Jun 21, 2023 |
| Dell          | Inspiron 5468               | [b16aeda09e](https://linux-hardware.org/?probe=b16aeda09e) | Jun 02, 2023 |
| Lenovo        | ThinkPad X200 74574AC       | [e770387a34](https://linux-hardware.org/?probe=e770387a34) | May 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | [cacfc4dacd](https://linux-hardware.org/?probe=cacfc4dacd) | May 16, 2023 |
| HP            | ZHAN 99 Mobile Workstati... | [3dcc7ab043](https://linux-hardware.org/?probe=3dcc7ab043) | Apr 12, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [30d91acf27](https://linux-hardware.org/?probe=30d91acf27) | Mar 07, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [97925534c2](https://linux-hardware.org/?probe=97925534c2) | Mar 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [cc10e54ab9](https://linux-hardware.org/?probe=cc10e54ab9) | Feb 20, 2023 |
| Lenovo        | XiaoXinPro 14ACH 2021 82... | [29326a6340](https://linux-hardware.org/?probe=29326a6340) | Feb 11, 2023 |
| Lenovo        | ThinkPad T480s 20L7A00HH... | [801c1bad94](https://linux-hardware.org/?probe=801c1bad94) | Jan 02, 2023 |
| THTF          | CR F860-T1                  | [9f0a52783f](https://linux-hardware.org/?probe=9f0a52783f) | Oct 27, 2022 |
| HUAWEI        | L410 KLVU-WDU0              | [00edb23106](https://linux-hardware.org/?probe=00edb23106) | Oct 07, 2022 |
| GreatWall     | Unknown                     | [12ee24a7c7](https://linux-hardware.org/?probe=12ee24a7c7) | Sep 20, 2022 |
| Timi          | TM1612                      | [fe85c2d733](https://linux-hardware.org/?probe=fe85c2d733) | Feb 05, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T2A... | [0c261084db](https://linux-hardware.org/?probe=0c261084db) | Oct 16, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [ebe2901cc8](https://linux-hardware.org/?probe=ebe2901cc8) | Apr 30, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [55b2402c28](https://linux-hardware.org/?probe=55b2402c28) | Feb 25, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [44013b0bb4](https://linux-hardware.org/?probe=44013b0bb4) | Feb 23, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Kylin V10   | 39        | 95.12%  |
| Kylin V10.1 | 2         | 4.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Kylin | 41        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.1.0-13-amd64          | 3         | 6.52%   |
| 5.19.0-32-generic       | 3         | 6.52%   |
| 6.8.0-31-generic        | 2         | 4.35%   |
| 5.4.18-35-generic       | 2         | 4.35%   |
| 5.4.18-15-generic       | 2         | 4.35%   |
| 5.19.0-45-generic       | 2         | 4.35%   |
| 6.9.9-rt-amd64          | 1         | 2.17%   |
| 6.8.0-47-generic        | 1         | 2.17%   |
| 6.8.0-45-generic        | 1         | 2.17%   |
| 6.8.0-38-generic        | 1         | 2.17%   |
| 6.8.0-35-generic        | 1         | 2.17%   |
| 6.7.12-rt-amd64         | 1         | 2.17%   |
| 6.6.9-amd64             | 1         | 2.17%   |
| 6.5.0-44-generic        | 1         | 2.17%   |
| 6.5.0-41-generic        | 1         | 2.17%   |
| 6.2.0-33-generic        | 1         | 2.17%   |
| 6.2.0-32-generic        | 1         | 2.17%   |
| 6.2.0-23-generic        | 1         | 2.17%   |
| 6.2.0-21-generic        | 1         | 2.17%   |
| 6.11-rt-amd64           | 1         | 2.17%   |
| 6.1.0-27-rt-amd64       | 1         | 2.17%   |
| 6.1.0-26-rt-amd64       | 1         | 2.17%   |
| 6.1.0-23-amd64          | 1         | 2.17%   |
| 6.1.0-21-rt-amd64       | 1         | 2.17%   |
| 6.1.0-18-amd64          | 1         | 2.17%   |
| 5.4.96-7-kr9a0          | 1         | 2.17%   |
| 5.4.18-27-generic       | 1         | 2.17%   |
| 5.4.0-155-generic       | 1         | 2.17%   |
| 5.19.0-46-generic       | 1         | 2.17%   |
| 5.19.0-41-generic       | 1         | 2.17%   |
| 5.15.0-73-generic       | 1         | 2.17%   |
| 5.15.0-69-generic       | 1         | 2.17%   |
| 5.15.0-119-generic      | 1         | 2.17%   |
| 5.10.0-28-amd64         | 1         | 2.17%   |
| 5.10.0-23-amd64         | 1         | 2.17%   |
| 5.10.0-20-amd64         | 1         | 2.17%   |
| 5.10.0-0.bpo.9-rt-amd64 | 1         | 2.17%   |
| 4.19.71-14-kr990        | 1         | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.0   | 7         | 15.56%  |
| 5.19.0  | 7         | 15.56%  |
| 6.8.0   | 6         | 13.33%  |
| 5.4.18  | 5         | 11.11%  |
| 6.2.0   | 4         | 8.89%   |
| 5.10.0  | 4         | 8.89%   |
| 5.15.0  | 3         | 6.67%   |
| 6.5.0   | 2         | 4.44%   |
| 6.9.9   | 1         | 2.22%   |
| 6.7.12  | 1         | 2.22%   |
| 6.6.9   | 1         | 2.22%   |
| 6.11    | 1         | 2.22%   |
| 5.4.96  | 1         | 2.22%   |
| 5.4.0   | 1         | 2.22%   |
| 4.19.71 | 1         | 2.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 7         | 15.56%  |
| 5.4     | 7         | 15.56%  |
| 5.19    | 7         | 15.56%  |
| 6.8     | 6         | 13.33%  |
| 6.2     | 4         | 8.89%   |
| 5.10    | 4         | 8.89%   |
| 5.15    | 3         | 6.67%   |
| 6.5     | 2         | 4.44%   |
| 6.9     | 1         | 2.22%   |
| 6.7     | 1         | 2.22%   |
| 6.6     | 1         | 2.22%   |
| 6       | 1         | 2.22%   |
| 4.19    | 1         | 2.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 37        | 90.24%  |
| aarch64 | 4         | 9.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 23        | 52.27%  |
| XFCE            | 7         | 15.91%  |
| UKUI            | 7         | 15.91%  |
| KDE5            | 4         | 9.09%   |
| X-Cinnamon      | 1         | 2.27%   |
| MATE            | 1         | 2.27%   |
| GNOME Flashback | 1         | 2.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 27        | 64.29%  |
| Wayland | 15        | 35.71%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 22        | 52.38%  |
| LightDM | 14        | 33.33%  |
| SDDM    | 3         | 7.14%   |
| TDM     | 2         | 4.76%   |
| GDM     | 1         | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| zh_CN | 28        | 65.12%  |
| en_US | 10        | 23.26%  |
| C     | 3         | 6.98%   |
| en_HK | 1         | 2.33%   |
| en_GB | 1         | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 35        | 85.37%  |
| BIOS | 6         | 14.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 35        | 85.37%  |
| Tmpfs   | 3         | 7.32%   |
| Xfs     | 1         | 2.44%   |
| Overlay | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 39        | 95.12%  |
| MBR  | 2         | 4.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 85.71%  |
| Yes       | 6         | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 53.66%  |
| Yes       | 19        | 46.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 17        | 41.46%  |
| ASUSTek Computer | 6         | 14.63%  |
| HUAWEI           | 5         | 12.2%   |
| Hewlett-Packard  | 3         | 7.32%   |
| Timi             | 2         | 4.88%   |
| Dell             | 2         | 4.88%   |
| THTF             | 1         | 2.44%   |
| HASEE Computer   | 1         | 2.44%   |
| GreatWall        | 1         | 2.44%   |
| Apple            | 1         | 2.44%   |
| Alienware        | 1         | 2.44%   |
| Acer             | 1         | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Lenovo Legion R9000P ARX8 82WM                    | 2         | 4.88%   |
| Timi TM1612                                       | 1         | 2.44%   |
| Timi Redmi G 2022                                 | 1         | 2.44%   |
| THTF CR F860-T1                                   | 1         | 2.44%   |
| Lenovo XiaoXinPro 14ACH 2021 82MS                 | 1         | 2.44%   |
| Lenovo ThinkPad X200 74574AC                      | 1         | 2.44%   |
| Lenovo ThinkPad X13 Gen 1 20UF000ACD              | 1         | 2.44%   |
| Lenovo ThinkPad X13 Gen 1 20T2A003CD              | 1         | 2.44%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y6S00400      | 1         | 2.44%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBA002CD       | 1         | 2.44%   |
| Lenovo ThinkPad T480s 20L7A00HHK                  | 1         | 2.44%   |
| Lenovo ThinkPad T460p 20FWA00PCD                  | 1         | 2.44%   |
| Lenovo ThinkPad T14 Gen 4 21HD0078CD              | 1         | 2.44%   |
| Lenovo ThinkPad T14 Gen 1 20UDA00MCD              | 1         | 2.44%   |
| Lenovo ThinkPad E14 Gen 2 20TAA006CD              | 1         | 2.44%   |
| Lenovo ThinkBook 16 G5+ ARP 21J0                  | 1         | 2.44%   |
| Lenovo Legion Y9000P IAH7H 82RF                   | 1         | 2.44%   |
| Lenovo Legion R9000P2021H 82JQ                    | 1         | 2.44%   |
| Lenovo IdeaPad 710S-13ISK 80SW                    | 1         | 2.44%   |
| HUAWEI QingYun L420 KLVV-W5821                    | 1         | 2.44%   |
| HUAWEI MACH-WX9                                   | 1         | 2.44%   |
| HUAWEI L410 KLVU-WDU0                             | 1         | 2.44%   |
| HUAWEI KLVDZ-WXX9                                 | 1         | 2.44%   |
| HUAWEI CREM-WXX9                                  | 1         | 2.44%   |
| HP ZHAN 99 Mobile Workstation G3                  | 1         | 2.44%   |
| HP ZBook Power 15.6 inch G9 Mobile Workstation PC | 1         | 2.44%   |
| HP EliteBook 840 G7 Notebook PC                   | 1         | 2.44%   |
| HASEE GI5CN54                                     | 1         | 2.44%   |
| Dell Vostro 3350                                  | 1         | 2.44%   |
| Dell Inspiron 5468                                | 1         | 2.44%   |
| ASUS Zenbook UX3402VA_UX3402VA                    | 1         | 2.44%   |
| ASUS VivoBook_ASUSLaptop K5504VA_K5504VA          | 1         | 2.44%   |
| ASUS UX31LA                                       | 1         | 2.44%   |
| ASUS TUF Gaming FX505GT                           | 1         | 2.44%   |
| ASUS TUF Gaming FX505GE_FX86FE                    | 1         | 2.44%   |
| ASUS ROG Strix G713PV_G713PV                      | 1         | 2.44%   |
| Apple MacBookPro12,1                              | 1         | 2.44%   |
| Alienware m15 R6                                  | 1         | 2.44%   |
| Acer Swift SFX14-41G                              | 1         | 2.44%   |
| Unknown                                           | 1         | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 10        | 24.39%  |
| Lenovo Legion      | 4         | 9.76%   |
| ASUS TUF           | 2         | 4.88%   |
| Timi TM1612        | 1         | 2.44%   |
| Timi Redmi         | 1         | 2.44%   |
| THTF CR            | 1         | 2.44%   |
| Lenovo XiaoXinPro  | 1         | 2.44%   |
| Lenovo ThinkBook   | 1         | 2.44%   |
| Lenovo IdeaPad     | 1         | 2.44%   |
| HUAWEI QingYun     | 1         | 2.44%   |
| HUAWEI MACH-WX9    | 1         | 2.44%   |
| HUAWEI L410        | 1         | 2.44%   |
| HUAWEI KLVDZ-WXX9  | 1         | 2.44%   |
| HUAWEI CREM-WXX9   | 1         | 2.44%   |
| HP ZHAN            | 1         | 2.44%   |
| HP ZBook           | 1         | 2.44%   |
| HP EliteBook       | 1         | 2.44%   |
| HASEE GI5CN54      | 1         | 2.44%   |
| Dell Vostro        | 1         | 2.44%   |
| Dell Inspiron      | 1         | 2.44%   |
| ASUS Zenbook       | 1         | 2.44%   |
| ASUS VivoBook      | 1         | 2.44%   |
| ASUS UX31LA        | 1         | 2.44%   |
| ASUS ROG           | 1         | 2.44%   |
| Apple MacBookPro12 | 1         | 2.44%   |
| Alienware m15      | 1         | 2.44%   |
| Acer Swift         | 1         | 2.44%   |
| Unknown            | 1         | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 11        | 26.83%  |
| 2022    | 7         | 17.07%  |
| 2020    | 5         | 12.2%   |
| 2023    | 4         | 9.76%   |
| 2016    | 4         | 9.76%   |
| 2018    | 3         | 7.32%   |
| 2014    | 2         | 4.88%   |
| 2015    | 1         | 2.44%   |
| 2012    | 1         | 2.44%   |
| 2011    | 1         | 2.44%   |
| 2008    | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 41        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 35        | 83.33%  |
| Enabled  | 7         | 16.67%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 41        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 16        | 39.02%  |
| 16.01-24.0  | 7         | 17.07%  |
| 4.01-8.0    | 6         | 14.63%  |
| 3.01-4.0    | 5         | 12.2%   |
| 32.01-64.0  | 4         | 9.76%   |
| 24.01-32.0  | 2         | 4.88%   |
| 64.01-256.0 | 1         | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 11        | 24.44%  |
| 3.01-4.0  | 11        | 24.44%  |
| 2.01-3.0  | 11        | 24.44%  |
| 1.01-2.0  | 8         | 17.78%  |
| 8.01-16.0 | 3         | 6.67%   |
| 0.51-1.0  | 1         | 2.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 60.98%  |
| 2      | 13        | 31.71%  |
| 4      | 2         | 4.88%   |
| 3      | 1         | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 95.12%  |
| Yes       | 2         | 4.88%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 73.17%  |
| No        | 11        | 26.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 87.8%   |
| No        | 5         | 12.2%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 92.68%  |
| No        | 3         | 7.32%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| China     | 33        | 80.49%  |
| Hong Kong | 5         | 12.2%   |
| USA       | 1         | 2.44%   |
| Taiwan    | 1         | 2.44%   |
| Japan     | 1         | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Notebooks | Percent |
|-------------|-----------|---------|
| Tianjin     | 3         | 7.14%   |
| Shenzhen    | 3         | 7.14%   |
| Shanghai    | 2         | 4.76%   |
| Mong Kok    | 2         | 4.76%   |
| Jinrongjie  | 2         | 4.76%   |
| Hefei       | 2         | 4.76%   |
| Haidian     | 2         | 4.76%   |
| Guangzhou   | 2         | 4.76%   |
| Central     | 2         | 4.76%   |
| Beijing     | 2         | 4.76%   |
| Zhongshan   | 1         | 2.38%   |
| Xiaolou     | 1         | 2.38%   |
| Xi'an       | 1         | 2.38%   |
| Wanchai     | 1         | 2.38%   |
| Tokyo       | 1         | 2.38%   |
| Taohua      | 1         | 2.38%   |
| Taizhou     | 1         | 2.38%   |
| Shizishan   | 1         | 2.38%   |
| Qinnan      | 1         | 2.38%   |
| Putuo       | 1         | 2.38%   |
| Los Angeles | 1         | 2.38%   |
| Kunming     | 1         | 2.38%   |
| Jinan       | 1         | 2.38%   |
| Harbin      | 1         | 2.38%   |
| Haikou      | 1         | 2.38%   |
| Chengdu     | 1         | 2.38%   |
| Changzhou   | 1         | 2.38%   |
| Changsha    | 1         | 2.38%   |
| Chancheng   | 1         | 2.38%   |
| Banqiao     | 1         | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 15        | 20     | 27.78%  |
| WDC                   | 5         | 5      | 9.26%   |
| Phison                | 4         | 4      | 7.41%   |
| Toshiba               | 3         | 3      | 5.56%   |
| SK hynix              | 3         | 3      | 5.56%   |
| SanDisk               | 3         | 3      | 5.56%   |
| Micron Technology     | 3         | 3      | 5.56%   |
| Lenovo                | 2         | 2      | 3.7%    |
| Intel                 | 2         | 2      | 3.7%    |
| ZX1 1TB               | 1         | 1      | 1.85%   |
| ZHITAI                | 1         | 1      | 1.85%   |
| Unknown               | 1         | 1      | 1.85%   |
| Seagate               | 1         | 1      | 1.85%   |
| Realtek Semiconductor | 1         | 1      | 1.85%   |
| KIOXIA                | 1         | 5      | 1.85%   |
| Kingston              | 1         | 1      | 1.85%   |
| Kingchuxing           | 1         | 1      | 1.85%   |
| HISI                  | 1         | 4      | 1.85%   |
| Hikvision             | 1         | 1      | 1.85%   |
| Hewlett-Packard       | 1         | 1      | 1.85%   |
| Fanxiang              | 1         | 1      | 1.85%   |
| Apple                 | 1         | 1      | 1.85%   |
| A-DATA Technology     | 1         | 1      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 3         | 5.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 2         | 3.64%   |
| Micron MTFDKBA512TFH 512GB                           | 2         | 3.64%   |
| ZX1 1TB Disk 1TB                                     | 1         | 1.82%   |
| ZHITAI TiPlus7100 2TB                                | 1         | 1.82%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB                 | 1         | 1.82%   |
| WDC PC SN730 SDBPNTY-512G                            | 1         | 1.82%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB                 | 1         | 1.82%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB                 | 1         | 1.82%   |
| WDC PC SN530 NVMe 512GB                              | 1         | 1.82%   |
| Unknown NVMe SSD Drive 256GB                         | 1         | 1.82%   |
| Toshiba MQ01ABD100 1TB                               | 1         | 1.82%   |
| Toshiba MK3261GSYN 320GB                             | 1         | 1.82%   |
| Toshiba KXG60ZNV512G KIOXIA 512GB                    | 1         | 1.82%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB               | 1         | 1.82%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB            | 1         | 1.82%   |
| SK hynix SKHynix_HFS001TEJ9X115N 1TB                 | 1         | 1.82%   |
| Seagate ST9500325AS 500GB                            | 1         | 1.82%   |
| SanDisk SSD PLUS 1000GB                              | 1         | 1.82%   |
| SanDisk SD6SP1M256G1102 256GB SSD                    | 1         | 1.82%   |
| SanDisk NVMe SSD Drive 1TB                           | 1         | 1.82%   |
| Samsung MZVLW256HEHP-000L2 256GB                     | 1         | 1.82%   |
| Samsung MZVLB512HBJQ-000L7 512GB                     | 1         | 1.82%   |
| Samsung MZVLB512HAJQ-00000 512GB                     | 1         | 1.82%   |
| Samsung MZVL4512HBLU-00BTW 512GB                     | 1         | 1.82%   |
| Samsung MZVL2512HCJQ-00BL7 512GB                     | 1         | 1.82%   |
| Samsung MZVL2512HCJQ-00BH1 512GB                     | 1         | 1.82%   |
| Samsung MZVL2512HCJQ-00B00 512GB                     | 1         | 1.82%   |
| Samsung MZVL21T0HCLR-00BL2 1TB                       | 1         | 1.82%   |
| Samsung MZNTY128HDHP-00000 128GB SSD                 | 1         | 1.82%   |
| Samsung KLUFG8RHDA-B2D1 512GB                        | 1         | 1.82%   |
| Samsung KLUFG8RHDA-B2D1 1GB                          | 1         | 1.82%   |
| Realtek NVMe SSD Drive 512GB                         | 1         | 1.82%   |
| Phison ThinkPlus ST8000 PCI-E M.2 256G               | 1         | 1.82%   |
| Phison SATA SSD 128GB                                | 1         | 1.82%   |
| Phison CFESR512GMTCT-E9C-2 512GB                     | 1         | 1.82%   |
| Phison 511BS0512HB 512GB                             | 1         | 1.82%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                        | 1         | 1.82%   |
| Lenovo SSD SL700 M.2 256G                            | 1         | 1.82%   |
| Lenovo SSD SL500 240G                                | 1         | 1.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 2         | 2      | 20%     |
| Samsung Electronics | 2         | 6      | 20%     |
| Lenovo              | 2         | 2      | 20%     |
| Phison              | 1         | 1      | 10%     |
| Kingchuxing         | 1         | 1      | 10%     |
| HISI                | 1         | 4      | 10%     |
| Apple               | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 32        | 45     | 71.11%  |
| SSD     | 9         | 17     | 20%     |
| HDD     | 3         | 3      | 6.67%   |
| Unknown | 1         | 1      | 2.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 32        | 44     | 69.57%  |
| SATA | 12        | 20     | 26.09%  |
| SAS  | 2         | 2      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 17     | 78.57%  |
| 0.51-1.0   | 3         | 3      | 21.43%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 17        | 40.48%  |
| 501-1000   | 8         | 19.05%  |
| 101-250    | 7         | 16.67%  |
| 51-100     | 5         | 11.9%   |
| 1001-2000  | 3         | 7.14%   |
| 2001-3000  | 1         | 2.38%   |
| Unknown    | 1         | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 10        | 23.81%  |
| 101-250   | 9         | 21.43%  |
| 1-20      | 7         | 16.67%  |
| 51-100    | 7         | 16.67%  |
| 251-500   | 4         | 9.52%   |
| 501-1000  | 3         | 7.14%   |
| 1001-2000 | 1         | 2.38%   |
| Unknown   | 1         | 2.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB       | 1         | 1      | 33.33%  |
| SanDisk SSD PLUS 1000GB         | 1         | 1      | 33.33%  |
| A-DATA Technology SX6000LNP 1TB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 1         | 1      | 33.33%  |
| SanDisk           | 1         | 1      | 33.33%  |
| A-DATA Technology | 1         | 1      | 33.33%  |

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
| NVMe | 1         | 1      | 33.33%  |
| SSD  | 1         | 1      | 33.33%  |
| HDD  | 1         | 1      | 33.33%  |

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
| Works    | 32        | 44     | 71.11%  |
| Detected | 10        | 19     | 22.22%  |
| Malfunc  | 3         | 3      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung Electronics             | 14        | 25.45%  |
| Intel                           | 13        | 23.64%  |
| SanDisk                         | 6         | 10.91%  |
| AMD                             | 4         | 7.27%   |
| SK hynix                        | 3         | 5.45%   |
| Phison Electronics              | 3         | 5.45%   |
| Micron Technology               | 3         | 5.45%   |
| Yangtze Memory Technologies     | 1         | 1.82%   |
| Toshiba America Info Systems    | 1         | 1.82%   |
| Silicon Motion                  | 1         | 1.82%   |
| Realtek Semiconductor           | 1         | 1.82%   |
| MAXIO Technology (Hangzhou)     | 1         | 1.82%   |
| Marvell Technology Group        | 1         | 1.82%   |
| KIOXIA                          | 1         | 1.82%   |
| Kingston Technology Company     | 1         | 1.82%   |
| Hefei DATANG Storage Technology | 1         | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 6         | 10.53%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 5         | 8.77%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 4         | 7.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 3         | 5.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 3         | 5.26%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)    | 2         | 3.51%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 2         | 3.51%   |
| Micron 3400 NVMe SSD [Hendrix]                                               | 2         | 3.51%   |
| Yangtze Memory ZHITAI TiPlus7100                                             | 1         | 1.75%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 1.75%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                           | 1         | 1.75%   |
| SK hynix PC611 NVMe Solid State Drive                                        | 1         | 1.75%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 1.75%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 1.75%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD      | 1         | 1.75%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                        | 1         | 1.75%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                   | 1         | 1.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 1.75%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                | 1         | 1.75%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                            | 1         | 1.75%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                          | 1         | 1.75%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 1         | 1.75%   |
| Phison E12 NVMe Controller                                                   | 1         | 1.75%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 1         | 1.75%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                     | 1         | 1.75%   |
| Marvell Group Marvell Non-Volatile memory controller                         | 1         | 1.75%   |
| KIOXIA NVMe SSD Controller XG8                                               | 1         | 1.75%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                   | 1         | 1.75%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation        | 1         | 1.75%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 1         | 1.75%   |
| Intel SSD 670p Series [Keystone Harbor]                                      | 1         | 1.75%   |
| Intel SSD 660P Series                                                        | 1         | 1.75%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                             | 1         | 1.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 1.75%   |
| Hefei DATANG Storage NVMe SSD Controller 300A                                | 1         | 1.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 32        | 64%     |
| SATA | 16        | 32%     |
| RAID | 1         | 2%      |
| IDE  | 1         | 2%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 25        | 60.98%  |
| AMD     | 12        | 29.27%  |
| Phytium | 2         | 4.88%   |
| ARM     | 2         | 4.88%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics     | 3         | 7.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 4.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 2         | 4.88%   |
| Intel 13th Gen Core i5-1340P               | 2         | 4.88%   |
| Intel 12th Gen Core i7-12700H              | 2         | 4.88%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 2         | 4.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 2         | 4.88%   |
| ARM Processor                              | 2         | 4.88%   |
| AMD Ryzen 9 7945HX with Radeon Graphics    | 2         | 4.88%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 4.88%   |
| Phytium FT-2000/4                          | 1         | 2.44%   |
| Phytium D2000/8 E8C                        | 1         | 2.44%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz           | 1         | 2.44%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 1         | 2.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 1         | 2.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 1         | 2.44%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 2.44%   |
| Intel Core i7-6560U CPU @ 2.20GHz          | 1         | 2.44%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 1         | 2.44%   |
| Intel Core i5-5257U CPU @ 2.70GHz          | 1         | 2.44%   |
| Intel Core i5-4200U CPU @ 1.60GHz          | 1         | 2.44%   |
| Intel Core i3-2310M CPU @ 2.10GHz          | 1         | 2.44%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz       | 1         | 2.44%   |
| Intel 13th Gen Core i9-13900H              | 1         | 2.44%   |
| Intel 12th Gen Core i5-1240P               | 1         | 2.44%   |
| AMD Ryzen 9 7845HX with Radeon Graphics    | 1         | 2.44%   |
| AMD Ryzen 7 7735H with Radeon Graphics     | 1         | 2.44%   |
| AMD Ryzen 7 5800U with Radeon Graphics     | 1         | 2.44%   |
| AMD Ryzen 5 6600H with Radeon Graphics     | 1         | 2.44%   |
| AMD Ryzen 5 5600H with Radeon Graphics     | 1         | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 14        | 34.15%  |
| Intel Core i7    | 7         | 17.07%  |
| Intel Core i5    | 5         | 12.2%   |
| AMD Ryzen 7      | 5         | 12.2%   |
| AMD Ryzen 9      | 3         | 7.32%   |
| AMD Ryzen 7 PRO  | 2         | 4.88%   |
| AMD Ryzen 5      | 2         | 4.88%   |
| Intel Core m3    | 1         | 2.44%   |
| Intel Core i3    | 1         | 2.44%   |
| Intel Core 2 Duo | 1         | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 8      | 10        | 24.39%  |
| 4      | 8         | 19.51%  |
| 6      | 7         | 17.07%  |
| 2      | 7         | 17.07%  |
| 12     | 4         | 9.76%   |
| 14     | 3         | 7.32%   |
| 16     | 2         | 4.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 95.12%  |
| 3      | 2         | 4.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 35        | 85.37%  |
| 1      | 6         | 14.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 41        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 45.24%  |
| 0x906ea    | 3         | 7.14%   |
| 0x806ec    | 2         | 4.76%   |
| 0x406e3    | 2         | 4.76%   |
| 0x0a50000d | 2         | 4.76%   |
| 0xb06a2    | 1         | 2.38%   |
| 0x906a3    | 1         | 2.38%   |
| 0x806ea    | 1         | 2.38%   |
| 0x806e9    | 1         | 2.38%   |
| 0x806c1    | 1         | 2.38%   |
| 0x40651    | 1         | 2.38%   |
| 0x306d4    | 1         | 2.38%   |
| 0x1067a    | 1         | 2.38%   |
| 0x0a601206 | 1         | 2.38%   |
| 0x0a601203 | 1         | 2.38%   |
| 0x0a50000c | 1         | 2.38%   |
| 0x0a50000b | 1         | 2.38%   |
| 0x0a404102 | 1         | 2.38%   |
| 0x0860010c | 1         | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 11        | 26.83%  |
| KabyLake         | 8         | 19.51%  |
| Zen 3            | 5         | 12.2%   |
| Alderlake Hybrid | 5         | 12.2%   |
| Skylake          | 3         | 7.32%   |
| Zen 2            | 2         | 4.88%   |
| TigerLake        | 2         | 4.88%   |
| SandyBridge      | 1         | 2.44%   |
| Penryn           | 1         | 2.44%   |
| Icelake          | 1         | 2.44%   |
| Haswell          | 1         | 2.44%   |
| Broadwell        | 1         | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 47.17%  |
| Nvidia | 15        | 28.3%   |
| AMD    | 13        | 24.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 5         | 9.43%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 4         | 7.55%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 3         | 5.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 5.66%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 2         | 3.77%   |
| Intel UHD Graphics 620                                                                | 2         | 3.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 3.77%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 2         | 3.77%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 2         | 3.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 3.77%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 2         | 3.77%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2         | 3.77%   |
| AMD Rembrandt [Radeon 680M]                                                           | 2         | 3.77%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 3.77%   |
| Nvidia TU117M [GeForce MX450]                                                         | 1         | 1.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.89%   |
| Nvidia TU117GLM [T600 Mobile]                                                         | 1         | 1.89%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 1.89%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 1.89%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 1.89%   |
| Intel Raptor Lake-P [UHD Graphics]                                                    | 1         | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.89%   |
| Intel Iris Graphics 6100                                                              | 1         | 1.89%   |
| Intel Iris Graphics 540                                                               | 1         | 1.89%   |
| Intel HD Graphics 620                                                                 | 1         | 1.89%   |
| Intel HD Graphics 530                                                                 | 1         | 1.89%   |
| Intel HD Graphics 515                                                                 | 1         | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 1.89%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 1         | 1.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 1.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.89%   |
| AMD Raphael                                                                           | 1         | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 39.02%  |
| Intel + Nvidia | 8         | 19.51%  |
| 1 x AMD        | 7         | 17.07%  |
| AMD + Nvidia   | 5         | 12.2%   |
| Other          | 2         | 4.88%   |
| 1 x Nvidia     | 2         | 4.88%   |
| Intel + AMD    | 1         | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 25        | 60.98%  |
| Proprietary | 12        | 29.27%  |
| Unknown     | 4         | 9.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 63.41%  |
| 1.01-2.0   | 6         | 14.63%  |
| 3.01-4.0   | 4         | 9.76%   |
| 0.01-0.5   | 3         | 7.32%   |
| 7.01-8.0   | 2         | 4.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 9         | 18.75%  |
| LG Display          | 6         | 12.5%   |
| CSO                 | 6         | 12.5%   |
| Chimei Innolux      | 5         | 10.42%  |
| AU Optronics        | 5         | 10.42%  |
| AOC                 | 3         | 6.25%   |
| Samsung Electronics | 2         | 4.17%   |
| Lenovo              | 2         | 4.17%   |
| Xiaomi              | 1         | 2.08%   |
| TMX                 | 1         | 2.08%   |
| STD                 | 1         | 2.08%   |
| PANDA               | 1         | 2.08%   |
| Mi                  | 1         | 2.08%   |
| KIG                 | 1         | 2.08%   |
| JDI                 | 1         | 2.08%   |
| Dell                | 1         | 2.08%   |
| CPT                 | 1         | 2.08%   |
| Apple               | 1         | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0AC9 2240x1400 302x189mm 14.0-inch                 | 2         | 4.17%   |
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                    | 1         | 2.08%   |
| TMX TL160ADMP01-0 TMX1600 2560x1600 345x215mm 16.0-inch               | 1         | 2.08%   |
| STD HDMI STD2700 1920x1080 600x330mm 27.0-inch                        | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 2.08%   |
| PANDA LCD Monitor NCP0042 1920x1080 344x194mm 15.5-inch               | 1         | 2.08%   |
| Mi P27QBB-RA XMID003 2560x1440 600x340mm 27.2-inch                    | 1         | 2.08%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 2.08%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch          | 1         | 2.08%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 2.08%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 1         | 2.08%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 2.08%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch          | 1         | 2.08%   |
| Lenovo X24i-10 LEN61AA 1920x1080 527x296mm 23.8-inch                  | 1         | 2.08%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 2.08%   |
| KIG KKTV KIG2700 1920x1080 598x336mm 27.0-inch                        | 1         | 2.08%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 2.08%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 1         | 2.08%   |
| CSO MNH301CA3-1 CSO1702 2560x1440 381x214mm 17.2-inch                 | 1         | 2.08%   |
| CSO LCD Monitor CSO161B 2560x1600 344x215mm 16.0-inch                 | 1         | 2.08%   |
| CSO LCD Monitor CSO161B 2560x1600 340x220mm 15.9-inch                 | 1         | 2.08%   |
| CSO LCD Monitor CSO1612 2560x1600 345x215mm 16.0-inch                 | 1         | 2.08%   |
| CSO LCD Monitor CSO1609 2560x1600 345x215mm 16.0-inch                 | 1         | 2.08%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 1         | 2.08%   |
| CPT LCD Monitor CPT17DB 1600x900 293x164mm 13.2-inch                  | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15F7 1920x1080 344x193mm 15.5-inch      | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN153A 1920x1080 344x193mm 15.5-inch      | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 1         | 2.08%   |
| BOE LCD Monitor BOE0AC1 2560x1600 344x215mm 16.0-inch                 | 1         | 2.08%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                 | 1         | 2.08%   |
| BOE LCD Monitor BOE08DA 1920x1080 309x174mm 14.0-inch                 | 1         | 2.08%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 1         | 2.08%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                 | 1         | 2.08%   |
| BOE LCD Monitor BOE06B6 1366x768 309x173mm 13.9-inch                  | 1         | 2.08%   |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                 | 1         | 2.08%   |
| AU Optronics LCD Monitor AUOA08B 1920x1080 344x193mm 15.5-inch        | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 1         | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 19        | 41.3%   |
| 2560x1600       | 7         | 15.22%  |
| 2560x1440 (QHD) | 4         | 8.7%    |
| 3840x2160 (4K)  | 3         | 6.52%   |
| 2880x1800       | 2         | 4.35%   |
| 2240x1400       | 2         | 4.35%   |
| 1366x768 (WXGA) | 2         | 4.35%   |
| 3840x2400       | 1         | 2.17%   |
| 3000x2000       | 1         | 2.17%   |
| 2880x1620       | 1         | 2.17%   |
| 2520x1680       | 1         | 2.17%   |
| 2160x1440       | 1         | 2.17%   |
| 1600x900 (HD+)  | 1         | 2.17%   |
| 1280x800 (WXGA) | 1         | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 11        | 22.92%  |
| 14     | 10        | 20.83%  |
| 15     | 8         | 16.67%  |
| 16     | 7         | 14.58%  |
| 27     | 6         | 12.5%   |
| 12     | 2         | 4.17%   |
| 65     | 1         | 2.08%   |
| 23     | 1         | 2.08%   |
| 22     | 1         | 2.08%   |
| 17     | 1         | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 58.33%  |
| 201-300     | 10        | 20.83%  |
| 501-600     | 7         | 14.58%  |
| 401-500     | 1         | 2.08%   |
| 351-400     | 1         | 2.08%   |
| 1001-1500   | 1         | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 62.79%  |
| 16/10 | 12        | 27.91%  |
| 3/2   | 4         | 9.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 16        | 33.33%  |
| 111-120        | 8         | 16.67%  |
| 101-110        | 7         | 14.58%  |
| 71-80          | 6         | 12.5%   |
| 301-350        | 6         | 12.5%   |
| 201-250        | 2         | 4.17%   |
| More than 1000 | 1         | 2.08%   |
| 61-70          | 1         | 2.08%   |
| 121-130        | 1         | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 161-240       | 19        | 40.43%  |
| 121-160       | 14        | 29.79%  |
| 51-100        | 6         | 12.77%  |
| More than 240 | 4         | 8.51%   |
| 101-120       | 3         | 6.38%   |
| 1-50          | 1         | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 30        | 73.17%  |
| 2     | 9         | 21.95%  |
| 0     | 2         | 4.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 26        | 40%     |
| Intel                      | 26        | 40%     |
| MediaTek                   | 6         | 9.23%   |
| Huawei Technologies        | 2         | 3.08%   |
| Xiaomi                     | 1         | 1.54%   |
| Quectel Wireless Solutions | 1         | 1.54%   |
| ICS Advent                 | 1         | 1.54%   |
| Broadcom                   | 1         | 1.54%   |
| ASIX Electronics           | 1         | 1.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 19        | 25.68%  |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3         | 4.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 4.05%   |
| Intel Wireless 8260                                                    | 3         | 4.05%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 4.05%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 3         | 4.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 4.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 4.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 2         | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 2.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 2.7%    |
| Intel Wireless 8265 / 8275                                             | 2         | 2.7%    |
| Intel Wi-Fi 6 AX201                                                    | 2         | 2.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 2.7%    |
| Huawei Network controller                                              | 2         | 2.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 1.35%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.35%   |
| Quectel Wireless Solutions Quectel EM05-CE                             | 1         | 1.35%   |
| Intel Wireless 7260                                                    | 1         | 1.35%   |
| Intel Wi-Fi 6 AX200                                                    | 1         | 1.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1         | 1.35%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 1         | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.35%   |
| Intel Ethernet Connection (23) I219-LM                                 | 1         | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.35%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 1.35%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 1.35%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                          | 1         | 1.35%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.35%   |
| ICS Advent USB 10/100 LAN                                              | 1         | 1.35%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 1         | 1.35%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 1.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 26        | 70.27%  |
| Realtek Semiconductor      | 5         | 13.51%  |
| MediaTek                   | 4         | 10.81%  |
| Quectel Wireless Solutions | 1         | 2.7%    |
| Broadcom                   | 1         | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 8.11%   |
| Intel Wireless 8260                                           | 3         | 8.11%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 3         | 8.11%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 3         | 8.11%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3         | 8.11%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 3         | 8.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 5.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 5.41%   |
| Intel Wireless 8265 / 8275                                    | 2         | 5.41%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 5.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 5.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.7%    |
| Quectel Wireless Solutions Quectel EM05-CE                    | 1         | 2.7%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 2.7%    |
| Intel Wireless 7260                                           | 1         | 2.7%    |
| Intel Wi-Fi 6 AX200                                           | 1         | 2.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 2.7%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection       | 1         | 2.7%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                 | 1         | 2.7%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 1         | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 24        | 68.57%  |
| Intel                 | 6         | 17.14%  |
| MediaTek              | 2         | 5.71%   |
| Xiaomi                | 1         | 2.86%   |
| ICS Advent            | 1         | 2.86%   |
| ASIX Electronics      | 1         | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 19        | 54.29%  |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 5.71%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 5.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 2.86%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 2.86%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 2.86%   |
| Intel Ethernet Connection (23) I219-LM                                 | 1         | 2.86%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 2.86%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 2.86%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 2.86%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 2.86%   |
| ICS Advent USB 10/100 LAN                                              | 1         | 2.86%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 52.17%  |
| Ethernet | 31        | 44.93%  |
| Unknown  | 2         | 2.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 80.95%  |
| Ethernet | 8         | 19.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 25        | 60.98%  |
| 1     | 15        | 36.59%  |
| 3     | 1         | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 80.49%  |
| Yes  | 8         | 19.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 65.79%  |
| Foxconn / Hon Hai               | 6         | 15.79%  |
| Realtek Semiconductor           | 2         | 5.26%   |
| Realtek                         | 1         | 2.63%   |
| Qualcomm Atheros Communications | 1         | 2.63%   |
| IMC Networks                    | 1         | 2.63%   |
| Broadcom                        | 1         | 2.63%   |
| Apple                           | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 6         | 15.79%  |
| Intel AX211 Bluetooth                              | 6         | 15.79%  |
| Intel AX201 Bluetooth                              | 5         | 13.16%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 3         | 7.89%   |
| Intel AX210 Bluetooth                              | 3         | 7.89%   |
| Foxconn / Hon Hai Wireless_Device                  | 3         | 7.89%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter       | 3         | 7.89%   |
| Realtek Bluetooth Radio                            | 2         | 5.26%   |
| Realtek Bluetooth Radio                            | 1         | 2.63%   |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 2.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter   | 1         | 2.63%   |
| Intel AX200 Bluetooth                              | 1         | 2.63%   |
| IMC Networks Bluetooth Radio                       | 1         | 2.63%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 2.63%   |
| Apple Bluetooth Host Controller                    | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel           | 25        | 49.02%  |
| AMD             | 14        | 27.45%  |
| Nvidia          | 11        | 21.57%  |
| TTGK Technology | 1         | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 12        | 20%     |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 8.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 8.33%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 6.67%   |
| Nvidia AD107 High Definition Audio Controller                              | 3         | 5%      |
| Intel Raptor Lake-P/U/H cAVS                                               | 3         | 5%      |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 5%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 5%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 3.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 3.33%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 3.33%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 3.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 3.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 3.33%   |
| TTGK Technology Audio                                                      | 1         | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.67%   |
| Nvidia GA107 High Definition Audio Controller                              | 1         | 1.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.67%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.67%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 31.58%  |
| SK hynix            | 10        | 26.32%  |
| Micron Technology   | 8         | 21.05%  |
| Elpida              | 2         | 5.26%   |
| Crucial             | 2         | 5.26%   |
| UNILC               | 1         | 2.63%   |
| Nanya Technology    | 1         | 2.63%   |
| A-DATA Technology   | 1         | 2.63%   |
| Unknown             | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 4.88%   |
| UNILC RAM 6478545886 8192MB SODIMM DDR4 2400MT/s                 | 1         | 2.44%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                     | 1         | 2.44%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 2.44%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 2.44%   |
| SK hynix RAM HMAA1GS6DMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 2.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.44%   |
| SK hynix RAM H9HKNNNFBMBUDR 8192MB Row Of Chips LPDDR4 4266MT/s  | 1         | 2.44%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 2.44%   |
| Samsung RAM Module 2GB SODIMM LPDDR3 1867MT/s                    | 1         | 2.44%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s                 | 1         | 2.44%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                     | 1         | 2.44%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 2.44%   |
| Samsung RAM M471A2K43BB1-CPB 16GB Chip DDR4 2133MT/s             | 1         | 2.44%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.44%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.44%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.44%   |
| Samsung RAM M425R1GB4DB0-CWMOL 16GB SODIMM DDR5 5600MT/s         | 1         | 2.44%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM DDR5 4800MT/s          | 1         | 2.44%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s           | 1         | 2.44%   |
| Samsung RAM K3UH7H70AM 8192MB Row Of Chips LPDDR4 4266MT/s       | 1         | 2.44%   |
| Nanya RAM M2N2G64CB8HA5N-BE 2GB SODIMM 1066MT/s                  | 1         | 2.44%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 2.44%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.44%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 1         | 2.44%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 2.44%   |
| Micron RAM Module 16GB SODIMM DDR4 2667MT/s                      | 1         | 2.44%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 2.44%   |
| Elpida RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 1         | 2.44%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 2.44%   |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s           | 1         | 2.44%   |
| Crucial RAM CT16G56C46S5.M8G1 16GB SODIMM DDR5 5600MT/s          | 1         | 2.44%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 2.44%   |
| Unknown                                                          | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 16        | 43.24%  |
| DDR5    | 6         | 16.22%  |
| LPDDR5  | 4         | 10.81%  |
| LPDDR4  | 4         | 10.81%  |
| LPDDR3  | 3         | 8.11%   |
| DDR3    | 3         | 8.11%   |
| Unknown | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 25        | 69.44%  |
| Row Of Chips | 10        | 27.78%  |
| Chip         | 1         | 2.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 21        | 58.33%  |
| 16384 | 6         | 16.67%  |
| 4096  | 4         | 11.11%  |
| 2048  | 3         | 8.33%   |
| 32768 | 1         | 2.78%   |
| 24576 | 1         | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 9         | 25%     |
| 2667  | 5         | 13.89%  |
| 6400  | 4         | 11.11%  |
| 5600  | 3         | 8.33%   |
| 4800  | 3         | 8.33%   |
| 4266  | 3         | 8.33%   |
| 1867  | 3         | 8.33%   |
| 2133  | 2         | 5.56%   |
| 2400  | 1         | 2.78%   |
| 1600  | 1         | 2.78%   |
| 1067  | 1         | 2.78%   |
| 1066  | 1         | 2.78%   |

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
| Chicony Electronics                    | 9         | 22.5%   |
| IMC Networks                           | 8         | 20%     |
| Luxvisions Innotech Limited            | 4         | 10%     |
| Microdia                               | 3         | 7.5%    |
| Unknown (0000066029)                   | 2         | 5%      |
| Sonix Technology                       | 2         | 5%      |
| Quanta                                 | 2         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5%      |
| Syntek                                 | 1         | 2.5%    |
| SunplusIT                              | 1         | 2.5%    |
| ShineTech                              | 1         | 2.5%    |
| Realtek Semiconductor                  | 1         | 2.5%    |
| Lenovo                                 | 1         | 2.5%    |
| Bison Electronics                      | 1         | 2.5%    |
| Apple                                  | 1         | 2.5%    |
| Acer                                   | 1         | 2.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 4         | 10%     |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 7.5%    |
| Chicony Integrated Camera                           | 3         | 7.5%    |
| Unknown (0000066029) HD Camera                      | 2         | 5%      |
| Sonix USB2.0 FHD UVC WebCam                         | 2         | 5%      |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 5%      |
| Syntek Integrated Camera                            | 1         | 2.5%    |
| SunplusIT XiaoMi Webcam                             | 1         | 2.5%    |
| ShineTech HD Camera                                 | 1         | 2.5%    |
| Realtek Integrated_Webcam_HD                        | 1         | 2.5%    |
| Quanta ov9734_techfront_camera                      | 1         | 2.5%    |
| Quanta HD User Facing                               | 1         | 2.5%    |
| Microdia USB2.0 Camera                              | 1         | 2.5%    |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 2.5%    |
| Microdia Integrated_Webcam_HD                       | 1         | 2.5%    |
| Luxvisions Innotech Limited Integrated RGB Camera   | 1         | 2.5%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 2.5%    |
| Lenovo Integrated Webcam                            | 1         | 2.5%    |
| IMC Networks Integrated RGB Camera                  | 1         | 2.5%    |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 2.5%    |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 2.5%    |
| Chicony Integrated Camera (1280x720@30)             | 1         | 2.5%    |
| Chicony HP HD Camera                                | 1         | 2.5%    |
| Chicony HD Webcam                                   | 1         | 2.5%    |
| Chicony EasyCamera                                  | 1         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 2.5%    |
| Bison Integrated Camera                             | 1         | 2.5%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 1         | 2.5%    |
| Acer Integrated Camera                              | 1         | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 53.85%  |
| Validity Sensors           | 3         | 23.08%  |
| Shenzhen Goodix Technology | 2         | 15.38%  |
| AuthenTec                  | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 3         | 23.08%  |
| Shenzhen Goodix  Fingerprint Device                       | 2         | 15.38%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 7.69%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 7.69%   |
| Synaptics UWP WBDI Device                                 | 1         | 7.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Synaptics Prometheus Fingerprint Reader                   | 1         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 7.69%   |
| AuthenTec AES2810                                         | 1         | 7.69%   |

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
| 0     | 26        | 63.41%  |
| 1     | 11        | 26.83%  |
| 2     | 4         | 9.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 12        | 63.16%  |
| Graphics card         | 3         | 15.79%  |
| Multimedia controller | 2         | 10.53%  |
| Net/wireless          | 1         | 5.26%   |
| Camera                | 1         | 5.26%   |

