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

Total: 33

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | ThinkPad T14 Gen 4 21HD0... | [db370ffb35](https://linux-hardware.org/?probe=db370ffb35) | May 05, 2024 |
| Acer      | Swift SFX14-41G             | [47966edb56](https://linux-hardware.org/?probe=47966edb56) | Apr 09, 2024 |
| Lenovo    | ThinkPad E14 Gen 2 20TAA... | [de970e3adc](https://linux-hardware.org/?probe=de970e3adc) | Mar 21, 2024 |
| HUAWEI    | CREM-WXX9                   | [cf753bfc89](https://linux-hardware.org/?probe=cf753bfc89) | Dec 05, 2023 |
| HUAWEI    | KLVDZ-WXX9                  | [d6486c4e50](https://linux-hardware.org/?probe=d6486c4e50) | Oct 27, 2023 |
| ASUSTek   | TUF Gaming FX505GT          | [a5fde2a0ed](https://linux-hardware.org/?probe=a5fde2a0ed) | Oct 24, 2023 |
| Dell      | Vostro 3350                 | [1034a53a9d](https://linux-hardware.org/?probe=1034a53a9d) | Sep 30, 2023 |
| Lenovo    | Legion R9000P2021H 82JQ     | [5168f99a06](https://linux-hardware.org/?probe=5168f99a06) | Sep 26, 2023 |
| ASUSTek   | ROG Strix G713PV_G713PV     | [0d1c562190](https://linux-hardware.org/?probe=0d1c562190) | Sep 08, 2023 |
| Apple     | MacBookPro12,1              | [4a1def29d3](https://linux-hardware.org/?probe=4a1def29d3) | Aug 09, 2023 |
| ASUSTek   | UX31LA                      | [0695e3bb09](https://linux-hardware.org/?probe=0695e3bb09) | Aug 08, 2023 |
| HUAWEI    | QingYun L420 KLVV-W5821     | [e3227788f6](https://linux-hardware.org/?probe=e3227788f6) | Jul 08, 2023 |
| Lenovo    | ThinkBook 16 G5+ ARP 21J... | [211f5e5cf1](https://linux-hardware.org/?probe=211f5e5cf1) | Jul 02, 2023 |
| Lenovo    | ThinkPad X1 Extreme Gen ... | [80b6536a46](https://linux-hardware.org/?probe=80b6536a46) | Jun 28, 2023 |
| HUAWEI    | MACH-WX9                    | [016268562d](https://linux-hardware.org/?probe=016268562d) | Jun 21, 2023 |
| HUAWEI    | MACH-WX9                    | [25bc3b1533](https://linux-hardware.org/?probe=25bc3b1533) | Jun 21, 2023 |
| Dell      | Inspiron 5468               | [b16aeda09e](https://linux-hardware.org/?probe=b16aeda09e) | Jun 02, 2023 |
| Lenovo    | ThinkPad X200 74574AC       | [e770387a34](https://linux-hardware.org/?probe=e770387a34) | May 25, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K550... | [cacfc4dacd](https://linux-hardware.org/?probe=cacfc4dacd) | May 16, 2023 |
| HP        | ZHAN 99 Mobile Workstati... | [3dcc7ab043](https://linux-hardware.org/?probe=3dcc7ab043) | Apr 12, 2023 |
| Lenovo    | Legion Y9000P IAH7H 82RF    | [30d91acf27](https://linux-hardware.org/?probe=30d91acf27) | Mar 07, 2023 |
| Lenovo    | Legion Y9000P IAH7H 82RF    | [97925534c2](https://linux-hardware.org/?probe=97925534c2) | Mar 02, 2023 |
| Lenovo    | ThinkPad X1 Carbon Gen 1... | [cc10e54ab9](https://linux-hardware.org/?probe=cc10e54ab9) | Feb 20, 2023 |
| Lenovo    | XiaoXinPro 14ACH 2021 82... | [29326a6340](https://linux-hardware.org/?probe=29326a6340) | Feb 11, 2023 |
| Lenovo    | ThinkPad T480s 20L7A00HH... | [801c1bad94](https://linux-hardware.org/?probe=801c1bad94) | Jan 02, 2023 |
| THTF      | CR F860-T1                  | [9f0a52783f](https://linux-hardware.org/?probe=9f0a52783f) | Oct 27, 2022 |
| HUAWEI    | L410 KLVU-WDU0              | [00edb23106](https://linux-hardware.org/?probe=00edb23106) | Oct 07, 2022 |
| GreatWall | Unknown                     | [12ee24a7c7](https://linux-hardware.org/?probe=12ee24a7c7) | Sep 20, 2022 |
| Timi      | TM1612                      | [fe85c2d733](https://linux-hardware.org/?probe=fe85c2d733) | Feb 05, 2022 |
| Lenovo    | ThinkPad X13 Gen 1 20T2A... | [0c261084db](https://linux-hardware.org/?probe=0c261084db) | Oct 16, 2021 |
| HP        | EliteBook 840 G7 Noteboo... | [ebe2901cc8](https://linux-hardware.org/?probe=ebe2901cc8) | Apr 30, 2021 |
| Lenovo    | IdeaPad 710S-13ISK 80SW     | [55b2402c28](https://linux-hardware.org/?probe=55b2402c28) | Feb 25, 2021 |
| Lenovo    | IdeaPad 710S-13ISK 80SW     | [44013b0bb4](https://linux-hardware.org/?probe=44013b0bb4) | Feb 23, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Kylin V10   | 28        | 93.33%  |
| Kylin V10.1 | 2         | 6.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Kylin | 30        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.1.0-13-amd64          | 3         | 10%     |
| 5.19.0-32-generic       | 3         | 10%     |
| 5.4.18-35-generic       | 2         | 6.67%   |
| 5.4.18-15-generic       | 2         | 6.67%   |
| 5.19.0-45-generic       | 2         | 6.67%   |
| 6.7.12-rt-amd64         | 1         | 3.33%   |
| 6.6.9-amd64             | 1         | 3.33%   |
| 6.2.0-33-generic        | 1         | 3.33%   |
| 6.2.0-32-generic        | 1         | 3.33%   |
| 6.2.0-23-generic        | 1         | 3.33%   |
| 6.2.0-21-generic        | 1         | 3.33%   |
| 6.1.0-18-amd64          | 1         | 3.33%   |
| 5.4.96-7-kr9a0          | 1         | 3.33%   |
| 5.4.18-27-generic       | 1         | 3.33%   |
| 5.4.0-155-generic       | 1         | 3.33%   |
| 5.19.0-46-generic       | 1         | 3.33%   |
| 5.19.0-41-generic       | 1         | 3.33%   |
| 5.15.0-73-generic       | 1         | 3.33%   |
| 5.15.0-69-generic       | 1         | 3.33%   |
| 5.10.0-23-amd64         | 1         | 3.33%   |
| 5.10.0-20-amd64         | 1         | 3.33%   |
| 5.10.0-0.bpo.9-rt-amd64 | 1         | 3.33%   |
| 4.19.71-14-kr990        | 1         | 3.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.0  | 7         | 23.33%  |
| 5.4.18  | 5         | 16.67%  |
| 6.2.0   | 4         | 13.33%  |
| 6.1.0   | 4         | 13.33%  |
| 5.10.0  | 3         | 10%     |
| 5.15.0  | 2         | 6.67%   |
| 6.7.12  | 1         | 3.33%   |
| 6.6.9   | 1         | 3.33%   |
| 5.4.96  | 1         | 3.33%   |
| 5.4.0   | 1         | 3.33%   |
| 4.19.71 | 1         | 3.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 7         | 23.33%  |
| 5.19    | 7         | 23.33%  |
| 6.2     | 4         | 13.33%  |
| 6.1     | 4         | 13.33%  |
| 5.10    | 3         | 10%     |
| 5.15    | 2         | 6.67%   |
| 6.7     | 1         | 3.33%   |
| 6.6     | 1         | 3.33%   |
| 4.19    | 1         | 3.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 26        | 86.67%  |
| aarch64 | 4         | 13.33%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 15        | 50%     |
| UKUI            | 7         | 23.33%  |
| XFCE            | 4         | 13.33%  |
| KDE5            | 2         | 6.67%   |
| X-Cinnamon      | 1         | 3.33%   |
| GNOME Flashback | 1         | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 19        | 63.33%  |
| Wayland | 11        | 36.67%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 15        | 50%     |
| LightDM | 10        | 33.33%  |
| TDM     | 2         | 6.67%   |
| SDDM    | 2         | 6.67%   |
| GDM     | 1         | 3.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| zh_CN | 21        | 70%     |
| en_US | 6         | 20%     |
| C     | 2         | 6.67%   |
| en_HK | 1         | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 25        | 83.33%  |
| BIOS | 5         | 16.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 26        | 86.67%  |
| Tmpfs   | 2         | 6.67%   |
| Xfs     | 1         | 3.33%   |
| Overlay | 1         | 3.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 29        | 96.67%  |
| MBR  | 1         | 3.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 80%     |
| Yes       | 6         | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 60%     |
| Yes       | 12        | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 12        | 40%     |
| HUAWEI           | 5         | 16.67%  |
| ASUSTek Computer | 4         | 13.33%  |
| Hewlett-Packard  | 2         | 6.67%   |
| Dell             | 2         | 6.67%   |
| Timi             | 1         | 3.33%   |
| THTF             | 1         | 3.33%   |
| GreatWall        | 1         | 3.33%   |
| Apple            | 1         | 3.33%   |
| Acer             | 1         | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Timi TM1612                                  | 1         | 3.33%   |
| THTF CR F860-T1                              | 1         | 3.33%   |
| Lenovo XiaoXinPro 14ACH 2021 82MS            | 1         | 3.33%   |
| Lenovo ThinkPad X200 74574AC                 | 1         | 3.33%   |
| Lenovo ThinkPad X13 Gen 1 20T2A003CD         | 1         | 3.33%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y6S00400 | 1         | 3.33%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBA002CD  | 1         | 3.33%   |
| Lenovo ThinkPad T480s 20L7A00HHK             | 1         | 3.33%   |
| Lenovo ThinkPad T14 Gen 4 21HD0078CD         | 1         | 3.33%   |
| Lenovo ThinkPad E14 Gen 2 20TAA006CD         | 1         | 3.33%   |
| Lenovo ThinkBook 16 G5+ ARP 21J0             | 1         | 3.33%   |
| Lenovo Legion Y9000P IAH7H 82RF              | 1         | 3.33%   |
| Lenovo Legion R9000P2021H 82JQ               | 1         | 3.33%   |
| Lenovo IdeaPad 710S-13ISK 80SW               | 1         | 3.33%   |
| HUAWEI QingYun L420 KLVV-W5821               | 1         | 3.33%   |
| HUAWEI MACH-WX9                              | 1         | 3.33%   |
| HUAWEI L410 KLVU-WDU0                        | 1         | 3.33%   |
| HUAWEI KLVDZ-WXX9                            | 1         | 3.33%   |
| HUAWEI CREM-WXX9                             | 1         | 3.33%   |
| HP ZHAN 99 Mobile Workstation G3             | 1         | 3.33%   |
| HP EliteBook 840 G7 Notebook PC              | 1         | 3.33%   |
| Dell Vostro 3350                             | 1         | 3.33%   |
| Dell Inspiron 5468                           | 1         | 3.33%   |
| ASUS VivoBook_ASUSLaptop K5504VA_K5504VA     | 1         | 3.33%   |
| ASUS UX31LA                                  | 1         | 3.33%   |
| ASUS TUF Gaming FX505GT                      | 1         | 3.33%   |
| ASUS ROG Strix G713PV_G713PV                 | 1         | 3.33%   |
| Apple MacBookPro12,1                         | 1         | 3.33%   |
| Acer Swift SFX14-41G                         | 1         | 3.33%   |
| Unknown                                      | 1         | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 7         | 23.33%  |
| Lenovo Legion      | 2         | 6.67%   |
| Timi TM1612        | 1         | 3.33%   |
| THTF CR            | 1         | 3.33%   |
| Lenovo XiaoXinPro  | 1         | 3.33%   |
| Lenovo ThinkBook   | 1         | 3.33%   |
| Lenovo IdeaPad     | 1         | 3.33%   |
| HUAWEI QingYun     | 1         | 3.33%   |
| HUAWEI MACH-WX9    | 1         | 3.33%   |
| HUAWEI L410        | 1         | 3.33%   |
| HUAWEI KLVDZ-WXX9  | 1         | 3.33%   |
| HUAWEI CREM-WXX9   | 1         | 3.33%   |
| HP ZHAN            | 1         | 3.33%   |
| HP EliteBook       | 1         | 3.33%   |
| Dell Vostro        | 1         | 3.33%   |
| Dell Inspiron      | 1         | 3.33%   |
| ASUS VivoBook      | 1         | 3.33%   |
| ASUS UX31LA        | 1         | 3.33%   |
| ASUS TUF           | 1         | 3.33%   |
| ASUS ROG           | 1         | 3.33%   |
| Apple MacBookPro12 | 1         | 3.33%   |
| Acer Swift         | 1         | 3.33%   |
| Unknown            | 1         | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 9         | 30%     |
| 2022    | 4         | 13.33%  |
| 2020    | 3         | 10%     |
| 2016    | 3         | 10%     |
| 2023    | 2         | 6.67%   |
| 2018    | 2         | 6.67%   |
| 2014    | 2         | 6.67%   |
| 2015    | 1         | 3.33%   |
| 2012    | 1         | 3.33%   |
| 2011    | 1         | 3.33%   |
| 2008    | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 30        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 26        | 86.67%  |
| Enabled  | 4         | 13.33%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 11        | 36.67%  |
| 4.01-8.0    | 6         | 20%     |
| 3.01-4.0    | 5         | 16.67%  |
| 16.01-24.0  | 5         | 16.67%  |
| 32.01-64.0  | 1         | 3.33%   |
| 24.01-32.0  | 1         | 3.33%   |
| 64.01-256.0 | 1         | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 10        | 33.33%  |
| 2.01-3.0  | 7         | 23.33%  |
| 1.01-2.0  | 6         | 20%     |
| 4.01-8.0  | 4         | 13.33%  |
| 8.01-16.0 | 2         | 6.67%   |
| 0.51-1.0  | 1         | 3.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 63.33%  |
| 2      | 8         | 26.67%  |
| 4      | 2         | 6.67%   |
| 3      | 1         | 3.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 93.33%  |
| Yes       | 2         | 6.67%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 66.67%  |
| No        | 10        | 33.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 90%     |
| No        | 3         | 10%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 90%     |
| No        | 3         | 10%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| China     | 25        | 83.33%  |
| Hong Kong | 3         | 10%     |
| USA       | 1         | 3.33%   |
| Taiwan    | 1         | 3.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Notebooks | Percent |
|-------------|-----------|---------|
| Tianjin     | 3         | 10%     |
| Shenzhen    | 2         | 6.67%   |
| Jinrongjie  | 2         | 6.67%   |
| Haidian     | 2         | 6.67%   |
| Central     | 2         | 6.67%   |
| Zhongshan   | 1         | 3.33%   |
| Xiaolou     | 1         | 3.33%   |
| Xi'an       | 1         | 3.33%   |
| Shizishan   | 1         | 3.33%   |
| Shanghai    | 1         | 3.33%   |
| Putuo       | 1         | 3.33%   |
| Mong Kok    | 1         | 3.33%   |
| Los Angeles | 1         | 3.33%   |
| Kunming     | 1         | 3.33%   |
| Jinan       | 1         | 3.33%   |
| Hefei       | 1         | 3.33%   |
| Harbin      | 1         | 3.33%   |
| Haikou      | 1         | 3.33%   |
| Guangzhou   | 1         | 3.33%   |
| Chengdu     | 1         | 3.33%   |
| Changsha    | 1         | 3.33%   |
| Chancheng   | 1         | 3.33%   |
| Beijing     | 1         | 3.33%   |
| Banqiao     | 1         | 3.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 15     | 28.95%  |
| WDC                 | 3         | 3      | 7.89%   |
| Toshiba             | 3         | 3      | 7.89%   |
| Micron Technology   | 3         | 3      | 7.89%   |
| SanDisk             | 2         | 2      | 5.26%   |
| Phison              | 2         | 2      | 5.26%   |
| ZX1 1TB             | 1         | 1      | 2.63%   |
| ZHITAI              | 1         | 1      | 2.63%   |
| Unknown             | 1         | 1      | 2.63%   |
| SK hynix            | 1         | 1      | 2.63%   |
| Seagate             | 1         | 1      | 2.63%   |
| Lenovo              | 1         | 1      | 2.63%   |
| KIOXIA              | 1         | 1      | 2.63%   |
| Kingston            | 1         | 1      | 2.63%   |
| Kingchuxing         | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| HISI                | 1         | 4      | 2.63%   |
| Hewlett-Packard     | 1         | 1      | 2.63%   |
| Fanxiang            | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 5.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2         | 5.13%   |
| Micron MTFDKBA512TFH 512GB                         | 2         | 5.13%   |
| ZX1 1TB Disk 1TB                                   | 1         | 2.56%   |
| ZHITAI TiPlus7100 2TB                              | 1         | 2.56%   |
| WDC PC SN730 SDBPNTY-512G                          | 1         | 2.56%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB               | 1         | 2.56%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB               | 1         | 2.56%   |
| Unknown NVMe SSD Drive 256GB                       | 1         | 2.56%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 2.56%   |
| Toshiba MK3261GSYN 320GB                           | 1         | 2.56%   |
| Toshiba KXG60ZNV512G KIOXIA 512GB                  | 1         | 2.56%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB             | 1         | 2.56%   |
| Seagate ST9500325AS 500GB                          | 1         | 2.56%   |
| SanDisk SD6SP1M256G1102 256GB SSD                  | 1         | 2.56%   |
| SanDisk NVMe SSD Drive 1TB                         | 1         | 2.56%   |
| Samsung MZVLW256HEHP-000L2 256GB                   | 1         | 2.56%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 1         | 2.56%   |
| Samsung MZVLB512HAJQ-00000 512GB                   | 1         | 2.56%   |
| Samsung MZVL2512HCJQ-00BL7 512GB                   | 1         | 2.56%   |
| Samsung MZVL2512HCJQ-00B00 512GB                   | 1         | 2.56%   |
| Samsung MZNTY128HDHP-00000 128GB SSD               | 1         | 2.56%   |
| Samsung KLUFG8RHDA-B2D1 512GB                      | 1         | 2.56%   |
| Samsung KLUFG8RHDA-B2D1 1GB                        | 1         | 2.56%   |
| Phison ThinkPlus ST8000 PCI-E M.2 256G             | 1         | 2.56%   |
| Phison 511BS0512HB 512GB                           | 1         | 2.56%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                      | 1         | 2.56%   |
| Lenovo SSD SL500 240G                              | 1         | 2.56%   |
| KIOXIA KXG8AZNV512G LA 512GB                       | 1         | 2.56%   |
| Kingston SA2000M81000G 1TB                         | 1         | 2.56%   |
| Kingchuxing SSD 128GB                              | 1         | 2.56%   |
| Intel SSDPEKNW512G8 512GB                          | 1         | 2.56%   |
| HISI THR920GFCV100HAE 256GB                        | 1         | 2.56%   |
| HP SSD EX950 1TB                                   | 1         | 2.56%   |
| Fanxiang S690 2TB                                  | 1         | 2.56%   |
| Apple SSD SM0256G 256GB                            | 1         | 2.56%   |

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
| Samsung Electronics | 2         | 5      | 28.57%  |
| SanDisk             | 1         | 1      | 14.29%  |
| Lenovo              | 1         | 1      | 14.29%  |
| Kingchuxing         | 1         | 1      | 14.29%  |
| HISI                | 1         | 4      | 14.29%  |
| Apple               | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 22        | 28     | 66.67%  |
| SSD     | 7         | 13     | 21.21%  |
| HDD     | 3         | 3      | 9.09%   |
| Unknown | 1         | 1      | 3.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 22        | 27     | 64.71%  |
| SATA | 10        | 16     | 29.41%  |
| SAS  | 2         | 2      | 5.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 14     | 81.82%  |
| 0.51-1.0   | 2         | 2      | 18.18%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 12        | 40%     |
| 101-250    | 6         | 20%     |
| 51-100     | 5         | 16.67%  |
| 501-1000   | 4         | 13.33%  |
| 1001-2000  | 2         | 6.67%   |
| 2001-3000  | 1         | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 7         | 23.33%  |
| 51-100   | 7         | 23.33%  |
| 1-20     | 6         | 20%     |
| 101-250  | 5         | 16.67%  |
| 251-500  | 3         | 10%     |
| 501-1000 | 2         | 6.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

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
| HDD  | 1         | 1      | 100%    |

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
| Works    | 23        | 27     | 71.88%  |
| Detected | 8         | 17     | 25%     |
| Malfunc  | 1         | 1      | 3.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung Electronics             | 10        | 26.32%  |
| Intel                           | 8         | 21.05%  |
| SanDisk                         | 4         | 10.53%  |
| AMD                             | 4         | 10.53%  |
| Micron Technology               | 3         | 7.89%   |
| Phison Electronics              | 2         | 5.26%   |
| Yangtze Memory Technologies     | 1         | 2.63%   |
| Toshiba America Info Systems    | 1         | 2.63%   |
| SK hynix                        | 1         | 2.63%   |
| Silicon Motion                  | 1         | 2.63%   |
| KIOXIA                          | 1         | 2.63%   |
| Kingston Technology Company     | 1         | 2.63%   |
| Hefei DATANG Storage Technology | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 4         | 10%     |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 4         | 10%     |
| AMD FCH SATA Controller [AHCI mode]                                          | 4         | 10%     |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 3         | 7.5%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                    | 2         | 5%      |
| Micron 3400 NVMe SSD [Hendrix]                                               | 2         | 5%      |
| Yangtze Memory ZHITAI TiPlus7100                                             | 1         | 2.5%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 2.5%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 2.5%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 2.5%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD      | 1         | 2.5%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 1         | 2.5%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                   | 1         | 2.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 2.5%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 1         | 2.5%    |
| Phison E12 NVMe Controller                                                   | 1         | 2.5%    |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 1         | 2.5%    |
| KIOXIA NVMe SSD Controller XG8                                               | 1         | 2.5%    |
| Kingston Company A2000 NVMe SSD SM2263EN                                     | 1         | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation        | 1         | 2.5%    |
| Intel SSD 660P Series                                                        | 1         | 2.5%    |
| Intel Mobile 4 Series Chipset PT IDER Controller                             | 1         | 2.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 2.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 2.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 2.5%    |
| Hefei DATANG Storage NVMe SSD Controller 300A                                | 1         | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 22        | 61.11%  |
| SATA | 12        | 33.33%  |
| RAID | 1         | 2.78%   |
| IDE  | 1         | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 19        | 63.33%  |
| AMD     | 7         | 23.33%  |
| Phytium | 2         | 6.67%   |
| ARM     | 2         | 6.67%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 10%     |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 6.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 6.67%   |
| ARM Processor                           | 2         | 6.67%   |
| Phytium FT-2000/4                       | 1         | 3.33%   |
| Phytium D2000/8 E8C                     | 1         | 3.33%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 3.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 3.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 3.33%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 3.33%   |
| Intel Core i7-6560U CPU @ 2.20GHz       | 1         | 3.33%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 3.33%   |
| Intel Core i5-5257U CPU @ 2.70GHz       | 1         | 3.33%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 3.33%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 1         | 3.33%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 1         | 3.33%   |
| Intel 13th Gen Core i9-13900H           | 1         | 3.33%   |
| Intel 13th Gen Core i5-1340P            | 1         | 3.33%   |
| Intel 12th Gen Core i7-12700H           | 1         | 3.33%   |
| Intel 12th Gen Core i5-1240P            | 1         | 3.33%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 3.33%   |
| AMD Ryzen 9 7845HX with Radeon Graphics | 1         | 3.33%   |
| AMD Ryzen 7 7735H with Radeon Graphics  | 1         | 3.33%   |
| AMD Ryzen 7 5800U with Radeon Graphics  | 1         | 3.33%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 1         | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 11        | 36.67%  |
| Intel Core i5    | 5         | 16.67%  |
| AMD Ryzen 7      | 5         | 16.67%  |
| Intel Core i7    | 4         | 13.33%  |
| Intel Core m3    | 1         | 3.33%   |
| Intel Core i3    | 1         | 3.33%   |
| Intel Core 2 Duo | 1         | 3.33%   |
| AMD Ryzen 9      | 1         | 3.33%   |
| AMD Ryzen 5      | 1         | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 8      | 7         | 23.33%  |
| 4      | 7         | 23.33%  |
| 2      | 7         | 23.33%  |
| 6      | 4         | 13.33%  |
| 12     | 3         | 10%     |
| 14     | 2         | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 93.33%  |
| 3      | 2         | 6.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 24        | 80%     |
| 1      | 6         | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 30        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 40%     |
| 0x806ec    | 2         | 6.67%   |
| 0x406e3    | 2         | 6.67%   |
| 0x0a50000d | 2         | 6.67%   |
| 0x906ea    | 1         | 3.33%   |
| 0x906a3    | 1         | 3.33%   |
| 0x806ea    | 1         | 3.33%   |
| 0x806e9    | 1         | 3.33%   |
| 0x806c1    | 1         | 3.33%   |
| 0x40651    | 1         | 3.33%   |
| 0x306d4    | 1         | 3.33%   |
| 0x1067a    | 1         | 3.33%   |
| 0x0a601203 | 1         | 3.33%   |
| 0x0a50000c | 1         | 3.33%   |
| 0x0a50000b | 1         | 3.33%   |
| 0x0a404102 | 1         | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 8         | 26.67%  |
| KabyLake         | 6         | 20%     |
| Zen 3            | 5         | 16.67%  |
| Alderlake Hybrid | 3         | 10%     |
| TigerLake        | 2         | 6.67%   |
| Skylake          | 2         | 6.67%   |
| SandyBridge      | 1         | 3.33%   |
| Penryn           | 1         | 3.33%   |
| Haswell          | 1         | 3.33%   |
| Broadwell        | 1         | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 50%     |
| AMD    | 10        | 26.32%  |
| Nvidia | 9         | 23.68%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 5         | 13.16%  |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 7.89%   |
| Intel UHD Graphics 620                                                                | 2         | 5.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 5.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 5.26%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 2         | 5.26%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 5.26%   |
| Nvidia TU117M [GeForce MX450]                                                         | 1         | 2.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 2.63%   |
| Nvidia TU117GLM [T600 Mobile]                                                         | 1         | 2.63%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 2.63%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 2.63%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 1         | 2.63%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 2.63%   |
| Intel Raptor Lake-P [UHD Graphics]                                                    | 1         | 2.63%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 1         | 2.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 2.63%   |
| Intel Iris Graphics 6100                                                              | 1         | 2.63%   |
| Intel Iris Graphics 540                                                               | 1         | 2.63%   |
| Intel HD Graphics 620                                                                 | 1         | 2.63%   |
| Intel HD Graphics 515                                                                 | 1         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 2.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 2.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 2.63%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.63%   |
| AMD Rembrandt [Radeon 680M]                                                           | 1         | 2.63%   |
| AMD Raphael                                                                           | 1         | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 43.33%  |
| Intel + Nvidia | 5         | 16.67%  |
| 1 x AMD        | 5         | 16.67%  |
| AMD + Nvidia   | 4         | 13.33%  |
| Other          | 2         | 6.67%   |
| Intel + AMD    | 1         | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 22        | 73.33%  |
| Proprietary | 6         | 20%     |
| Unknown     | 2         | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 66.67%  |
| 1.01-2.0   | 5         | 16.67%  |
| 0.01-0.5   | 3         | 10%     |
| 3.01-4.0   | 2         | 6.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 9         | 26.47%  |
| CSO                 | 4         | 11.76%  |
| Chimei Innolux      | 4         | 11.76%  |
| LG Display          | 3         | 8.82%   |
| Lenovo              | 2         | 5.88%   |
| AU Optronics        | 2         | 5.88%   |
| AOC                 | 2         | 5.88%   |
| Xiaomi              | 1         | 2.94%   |
| Samsung Electronics | 1         | 2.94%   |
| PANDA               | 1         | 2.94%   |
| KIG                 | 1         | 2.94%   |
| JDI                 | 1         | 2.94%   |
| Dell                | 1         | 2.94%   |
| CPT                 | 1         | 2.94%   |
| Apple               | 1         | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0AC9 2240x1400 302x189mm 14.0-inch                 | 2         | 5.88%   |
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                     | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 1         | 2.94%   |
| PANDA LCD Monitor NCP0042 1920x1080 344x194mm 15.5-inch               | 1         | 2.94%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 2.94%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 2.94%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 2.94%   |
| Lenovo X24i-10 LEN61AA 1920x1080 527x296mm 23.8-inch                  | 1         | 2.94%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 2.94%   |
| KIG KKTV KIG2700 1920x1080 598x336mm 27.0-inch                        | 1         | 2.94%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 2.94%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 1         | 2.94%   |
| CSO MNH301CA3-1 CSO1702 2560x1440 381x214mm 17.2-inch                 | 1         | 2.94%   |
| CSO LCD Monitor CSO1612 2560x1600 345x215mm 16.0-inch                 | 1         | 2.94%   |
| CSO LCD Monitor CSO1609 2560x1600 345x215mm 16.0-inch                 | 1         | 2.94%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 1         | 2.94%   |
| CPT LCD Monitor CPT17DB 1600x900 293x164mm 13.2-inch                  | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN153A 1920x1080 344x193mm 15.5-inch      | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 1         | 2.94%   |
| BOE LCD Monitor BOE0AC1 2560x1600 344x215mm 16.0-inch                 | 1         | 2.94%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                 | 1         | 2.94%   |
| BOE LCD Monitor BOE08DA 1920x1080 309x174mm 14.0-inch                 | 1         | 2.94%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 1         | 2.94%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                 | 1         | 2.94%   |
| BOE LCD Monitor BOE06B6 1366x768 309x173mm 13.9-inch                  | 1         | 2.94%   |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                 | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 1         | 2.94%   |
| Apple Color LCD APPA02A 2560x1600 286x179mm 13.3-inch                 | 1         | 2.94%   |
| AOC 27V3 AOC2703 1920x1080 598x336mm 27.0-inch                        | 1         | 2.94%   |
| AOC 23E1WX AOC2301 1920x1080 488x297mm 22.5-inch                      | 1         | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 13        | 40.63%  |
| 2560x1600       | 4         | 12.5%   |
| 3840x2160 (4K)  | 2         | 6.25%   |
| 2240x1400       | 2         | 6.25%   |
| 1366x768 (WXGA) | 2         | 6.25%   |
| 3840x2400       | 1         | 3.13%   |
| 3000x2000       | 1         | 3.13%   |
| 2880x1800       | 1         | 3.13%   |
| 2880x1620       | 1         | 3.13%   |
| 2560x1440 (QHD) | 1         | 3.13%   |
| 2520x1680       | 1         | 3.13%   |
| 2160x1440       | 1         | 3.13%   |
| 1600x900 (HD+)  | 1         | 3.13%   |
| 1280x800 (WXGA) | 1         | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 10        | 29.41%  |
| 14     | 7         | 20.59%  |
| 16     | 5         | 14.71%  |
| 27     | 3         | 8.82%   |
| 15     | 3         | 8.82%   |
| 12     | 2         | 5.88%   |
| 65     | 1         | 2.94%   |
| 23     | 1         | 2.94%   |
| 22     | 1         | 2.94%   |
| 17     | 1         | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 52.94%  |
| 201-300     | 9         | 26.47%  |
| 501-600     | 4         | 11.76%  |
| 401-500     | 1         | 2.94%   |
| 351-400     | 1         | 2.94%   |
| 1001-1500   | 1         | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 18        | 60%     |
| 16/10 | 9         | 30%     |
| 3/2   | 3         | 10%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 38.24%  |
| 71-80          | 5         | 14.71%  |
| 111-120        | 5         | 14.71%  |
| 301-350        | 3         | 8.82%   |
| 101-110        | 3         | 8.82%   |
| 201-250        | 2         | 5.88%   |
| More than 1000 | 1         | 2.94%   |
| 61-70          | 1         | 2.94%   |
| 121-130        | 1         | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 161-240       | 13        | 39.39%  |
| 121-160       | 10        | 30.3%   |
| 51-100        | 4         | 12.12%  |
| More than 240 | 3         | 9.09%   |
| 101-120       | 2         | 6.06%   |
| 1-50          | 1         | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 22        | 73.33%  |
| 2     | 6         | 20%     |
| 0     | 2         | 6.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 18        | 40%     |
| Intel                      | 18        | 40%     |
| MediaTek                   | 3         | 6.67%   |
| Huawei Technologies        | 2         | 4.44%   |
| Quectel Wireless Solutions | 1         | 2.22%   |
| ICS Advent                 | 1         | 2.22%   |
| Broadcom                   | 1         | 2.22%   |
| ASIX Electronics           | 1         | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12        | 23.08%  |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 2         | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 3.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 3.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 2         | 3.85%   |
| Intel Wireless 8265 / 8275                                             | 2         | 3.85%   |
| Intel Wireless 8260                                                    | 2         | 3.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 3.85%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 3.85%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 2         | 3.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 3.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 3.85%   |
| Huawei Network controller                                              | 2         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 1.92%   |
| Quectel Wireless Solutions Quectel EM05-CE                             | 1         | 1.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 1.92%   |
| Intel Wireless 7260                                                    | 1         | 1.92%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 1         | 1.92%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.92%   |
| Intel Ethernet Connection (23) I219-LM                                 | 1         | 1.92%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 1.92%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                          | 1         | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 1         | 1.92%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.92%   |
| ICS Advent 10/100M LAN                                                 | 1         | 1.92%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 1         | 1.92%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 1.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 18        | 64.29%  |
| Realtek Semiconductor      | 5         | 17.86%  |
| MediaTek                   | 3         | 10.71%  |
| Quectel Wireless Solutions | 1         | 3.57%   |
| Broadcom                   | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 7.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 7.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 7.14%   |
| Intel Wireless 8265 / 8275                                    | 2         | 7.14%   |
| Intel Wireless 8260                                           | 2         | 7.14%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 2         | 7.14%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 7.14%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 2         | 7.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 7.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 7.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.57%   |
| Quectel Wireless Solutions Quectel EM05-CE                    | 1         | 3.57%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 3.57%   |
| Intel Wireless 7260                                           | 1         | 3.57%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection       | 1         | 3.57%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                 | 1         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 3.57%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 1         | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 16        | 72.73%  |
| Intel                 | 4         | 18.18%  |
| ICS Advent            | 1         | 4.55%   |
| ASIX Electronics      | 1         | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12        | 54.55%  |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 9.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 4.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 4.55%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 4.55%   |
| Intel Ethernet Connection (23) I219-LM                                 | 1         | 4.55%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 4.55%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 4.55%   |
| ICS Advent 10/100M LAN                                                 | 1         | 4.55%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 55.1%   |
| Ethernet | 20        | 40.82%  |
| Unknown  | 2         | 4.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 80.65%  |
| Ethernet | 6         | 19.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 16        | 53.33%  |
| 1     | 14        | 46.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 24        | 80%     |
| Yes  | 6         | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 62.96%  |
| Foxconn / Hon Hai               | 3         | 11.11%  |
| Realtek Semiconductor           | 2         | 7.41%   |
| Realtek                         | 1         | 3.7%    |
| Qualcomm Atheros Communications | 1         | 3.7%    |
| IMC Networks                    | 1         | 3.7%    |
| Broadcom                        | 1         | 3.7%    |
| Apple                           | 1         | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                             | 4         | 14.81%  |
| Intel AX211 Bluetooth                              | 4         | 14.81%  |
| Intel AX201 Bluetooth                              | 4         | 14.81%  |
| Realtek Bluetooth Radio                            | 2         | 7.41%   |
| Intel AX210 Bluetooth                              | 2         | 7.41%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter       | 2         | 7.41%   |
| Realtek Bluetooth Radio                            | 1         | 3.7%    |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 3.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter   | 1         | 3.7%    |
| Intel Bluetooth wireless interface                 | 1         | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 1         | 3.7%    |
| IMC Networks Bluetooth Radio                       | 1         | 3.7%    |
| Foxconn / Hon Hai Wireless_Device                  | 1         | 3.7%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 3.7%    |
| Apple Bluetooth Host Controller                    | 1         | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 55.88%  |
| AMD    | 9         | 26.47%  |
| Nvidia | 6         | 17.65%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 17.5%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 12.5%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 7.5%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 7.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 5%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 5%      |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 5%      |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 5%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 5%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 5%      |
| Nvidia Audio device                                                        | 1         | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.5%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.5%    |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.5%    |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.5%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 2.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 8         | 29.63%  |
| Samsung Electronics | 8         | 29.63%  |
| Micron Technology   | 6         | 22.22%  |
| Elpida              | 2         | 7.41%   |
| UNILC               | 1         | 3.7%    |
| Nanya Technology    | 1         | 3.7%    |
| A-DATA Technology   | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| UNILC RAM 6478545886 8192MB SODIMM DDR4 2400MT/s                 | 1         | 3.57%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                     | 1         | 3.57%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 3.57%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 3.57%   |
| SK hynix RAM HMAA1GS6DMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 3.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 3.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 3.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 3.57%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 3.57%   |
| SK hynix RAM H9HKNNNFBMBUDR 8192MB Row Of Chips LPDDR4 4266MT/s  | 1         | 3.57%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 3.57%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s                 | 1         | 3.57%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.57%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 3.57%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 3.57%   |
| Samsung RAM M425R1GB4DB0-CWMOL 16GB SODIMM DDR5 5600MT/s         | 1         | 3.57%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s           | 1         | 3.57%   |
| Samsung RAM K3UH7H70AM 8192MB Row Of Chips LPDDR4 4266MT/s       | 1         | 3.57%   |
| Nanya RAM M2N2G64CB8HA5N-BE 2GB SODIMM 1066MT/s                  | 1         | 3.57%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 3.57%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB Row Of Chips LPDDR5 6400MT/s | 1         | 3.57%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 1         | 3.57%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 3.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 3.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 3.57%   |
| Elpida RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 1         | 3.57%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 3.57%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 11        | 40.74%  |
| LPDDR4  | 4         | 14.81%  |
| LPDDR5  | 3         | 11.11%  |
| LPDDR3  | 3         | 11.11%  |
| DDR3    | 3         | 11.11%  |
| DDR5    | 2         | 7.41%   |
| Unknown | 1         | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 16        | 64%     |
| Row Of Chips | 9         | 36%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 17        | 68%     |
| 4096  | 3         | 12%     |
| 2048  | 3         | 12%     |
| 32768 | 1         | 4%      |
| 16384 | 1         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 6         | 23.08%  |
| 2667  | 4         | 15.38%  |
| 6400  | 3         | 11.54%  |
| 4266  | 3         | 11.54%  |
| 1867  | 3         | 11.54%  |
| 5600  | 1         | 3.85%   |
| 4800  | 1         | 3.85%   |
| 2400  | 1         | 3.85%   |
| 2133  | 1         | 3.85%   |
| 1600  | 1         | 3.85%   |
| 1067  | 1         | 3.85%   |
| 1066  | 1         | 3.85%   |

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
| IMC Networks                           | 6         | 21.43%  |
| Chicony Electronics                    | 6         | 21.43%  |
| Luxvisions Innotech Limited            | 3         | 10.71%  |
| Unknown (0000066029)                   | 2         | 7.14%   |
| Quanta                                 | 2         | 7.14%   |
| Microdia                               | 2         | 7.14%   |
| Syntek                                 | 1         | 3.57%   |
| Sonix Technology                       | 1         | 3.57%   |
| ShineTech                              | 1         | 3.57%   |
| Realtek Semiconductor                  | 1         | 3.57%   |
| Lenovo                                 | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.57%   |
| Acer                                   | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 3         | 10.71%  |
| Unknown (0000066029) HD Camera                      | 2         | 7.14%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 7.14%   |
| Syntek Integrated Camera                            | 1         | 3.57%   |
| Sonix USB2.0 FHD UVC WebCam                         | 1         | 3.57%   |
| ShineTech HD Camera                                 | 1         | 3.57%   |
| Realtek Integrated_Webcam_HD                        | 1         | 3.57%   |
| Quanta ov9734_techfront_camera                      | 1         | 3.57%   |
| Quanta HD User Facing                               | 1         | 3.57%   |
| Microdia USB2.0 Camera                              | 1         | 3.57%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 3.57%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 1         | 3.57%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 3.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.57%   |
| Lenovo Integrated Webcam                            | 1         | 3.57%   |
| IMC Networks Integrated RGB Camera                  | 1         | 3.57%   |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 3.57%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 3.57%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 3.57%   |
| Chicony Integrated Camera                           | 1         | 3.57%   |
| Chicony HP HD Camera                                | 1         | 3.57%   |
| Chicony EasyCamera                                  | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 3.57%   |
| Acer Integrated Camera                              | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 50%     |
| Shenzhen Goodix Technology | 2         | 25%     |
| Validity Sensors           | 1         | 12.5%   |
| AuthenTec                  | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                       | 2         | 25%     |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 12.5%   |
| Synaptics UWP WBDI Device                                 | 1         | 12.5%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 12.5%   |
| AuthenTec AES2810                                         | 1         | 12.5%   |

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
| 0     | 18        | 60%     |
| 1     | 11        | 36.67%  |
| 2     | 1         | 3.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 61.54%  |
| Multimedia controller | 2         | 15.38%  |
| Graphics card         | 2         | 15.38%  |
| Camera                | 1         | 7.69%   |

