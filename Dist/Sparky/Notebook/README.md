Sparky - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Sparky.

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

Total: 40

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Fujitsu Si... | STYLISTIC ST5112            | [c343cec0c8](https://linux-hardware.org/?probe=c343cec0c8) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | [8bf37cf82d](https://linux-hardware.org/?probe=8bf37cf82d) | Dec 26, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [54273f1267](https://linux-hardware.org/?probe=54273f1267) | Dec 22, 2022 |
| Apple         | MacBook1,1                  | [6945006338](https://linux-hardware.org/?probe=6945006338) | Nov 15, 2022 |
| Google        | Swanky                      | [1a0a358398](https://linux-hardware.org/?probe=1a0a358398) | Nov 15, 2022 |
| ASUSTek       | M70Vn                       | [236d8cb74e](https://linux-hardware.org/?probe=236d8cb74e) | Aug 29, 2022 |
| HUAWEI        | HVY-WXX9                    | [b4006730ce](https://linux-hardware.org/?probe=b4006730ce) | Jul 17, 2022 |
| HP            | Stream Notebook PC 13       | [47b55dbb68](https://linux-hardware.org/?probe=47b55dbb68) | Jun 06, 2022 |
| HP            | EliteBook 745 G3            | [fac15b2640](https://linux-hardware.org/?probe=fac15b2640) | May 18, 2022 |
| HP            | EliteBook 8770w             | [4fa8e91f6d](https://linux-hardware.org/?probe=4fa8e91f6d) | Apr 26, 2022 |
| Lenovo        | G50-30 80G0                 | [c7ea70f7ba](https://linux-hardware.org/?probe=c7ea70f7ba) | Apr 25, 2022 |
| HP            | Pavilion dv5                | [22ae3dae3d](https://linux-hardware.org/?probe=22ae3dae3d) | Mar 22, 2022 |
| ASUSTek       | 1000HE                      | [5dd6246e59](https://linux-hardware.org/?probe=5dd6246e59) | Feb 08, 2022 |
| ASUSTek       | S101                        | [a850549e73](https://linux-hardware.org/?probe=a850549e73) | Feb 04, 2022 |
| HP            | EliteBook 8770w             | [9a2052fc8c](https://linux-hardware.org/?probe=9a2052fc8c) | Nov 25, 2021 |
| HP            | Pavilion g7                 | [6cebc99fe6](https://linux-hardware.org/?probe=6cebc99fe6) | Nov 22, 2021 |
| Dell          | Inspiron N5010              | [df5e66431b](https://linux-hardware.org/?probe=df5e66431b) | Nov 20, 2021 |
| HP            | EliteBook Folio 9480m       | [dae2e04d45](https://linux-hardware.org/?probe=dae2e04d45) | Oct 04, 2021 |
| Google        | Banon                       | [764debedcd](https://linux-hardware.org/?probe=764debedcd) | Sep 25, 2021 |
| Lenovo        | ThinkPad E15 20RES0GF00     | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Apple         | MacBook1,1                  | [cc415ab6c7](https://linux-hardware.org/?probe=cc415ab6c7) | Mar 15, 2021 |
| Samsung       | NC10                        | [b5909af616](https://linux-hardware.org/?probe=b5909af616) | Mar 11, 2021 |
| Samsung       | NC10                        | [3b8de5559e](https://linux-hardware.org/?probe=3b8de5559e) | Feb 27, 2021 |
| Lenovo        | ThinkPad T61 7659AB7        | [43f03346c5](https://linux-hardware.org/?probe=43f03346c5) | Feb 19, 2021 |
| Beelink       | BT3 PRO                     | [8dbfa4dacd](https://linux-hardware.org/?probe=8dbfa4dacd) | Jan 06, 2021 |
| Beelink       | BT3 PRO                     | [d85a392e02](https://linux-hardware.org/?probe=d85a392e02) | Jan 06, 2021 |
| Samsung       | NC10                        | [8c878860a7](https://linux-hardware.org/?probe=8c878860a7) | Jan 03, 2021 |
| Dell          | Inspiron 5720               | [d360a61780](https://linux-hardware.org/?probe=d360a61780) | Dec 08, 2020 |
| eMachines     | E525                        | [0c11b6b4dc](https://linux-hardware.org/?probe=0c11b6b4dc) | Nov 25, 2020 |
| Lenovo        | IdeaPad S206 20154          | [393f27acf7](https://linux-hardware.org/?probe=393f27acf7) | Nov 18, 2020 |
| Dell          | Inspiron 5720               | [787263a0c6](https://linux-hardware.org/?probe=787263a0c6) | Oct 10, 2020 |
| HP            | Laptop 17z-ca100            | [2217d0703c](https://linux-hardware.org/?probe=2217d0703c) | Oct 05, 2020 |
| HP            | Laptop 17z-ca100            | [1927ffc179](https://linux-hardware.org/?probe=1927ffc179) | Oct 05, 2020 |
| Apple         | MacBook1,1                  | [73b04f9de4](https://linux-hardware.org/?probe=73b04f9de4) | Aug 26, 2020 |
| Acer          | Aspire 5742G                | [a90fb35c67](https://linux-hardware.org/?probe=a90fb35c67) | May 01, 2020 |
| Lenovo        | ThinkPad T60 2007FUG        | [d552e50d7e](https://linux-hardware.org/?probe=d552e50d7e) | Mar 12, 2020 |
| Dell          | Latitude XT3                | [0944e88882](https://linux-hardware.org/?probe=0944e88882) | Mar 09, 2020 |
| Dell          | Inspiron 5770               | [a3dd71465d](https://linux-hardware.org/?probe=a3dd71465d) | Jan 06, 2020 |
| HP            | Pavilion dv9000 (GA359UA... | [db4a924be0](https://linux-hardware.org/?probe=db4a924be0) | Sep 07, 2019 |
| HP            | Pavilion dv9000 (GA359UA... | [6f024c0dd0](https://linux-hardware.org/?probe=6f024c0dd0) | Sep 03, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Sparky 6    | 8         | 24.24%  |
| Sparky 7    | 5         | 15.15%  |
| Sparky 6.5  | 4         | 12.12%  |
| Sparky 6.1  | 4         | 12.12%  |
| Sparky 5.14 | 3         | 9.09%   |
| Sparky 6.0  | 2         | 6.06%   |
| Sparky 5.13 | 2         | 6.06%   |
| Sparky 5.12 | 2         | 6.06%   |
| Sparky 5.10 | 2         | 6.06%   |
| Sparky 6.3  | 1         | 3.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Sparky | 30        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.10.0-11-686       | 3         | 8.57%   |
| 5.17.0-1-amd64      | 2         | 5.71%   |
| 5.10.0-9-amd64      | 2         | 5.71%   |
| 5.10.0-8-amd64      | 2         | 5.71%   |
| 4.19.0-8-amd64      | 2         | 5.71%   |
| 4.19.0-13-686       | 2         | 5.71%   |
| 4.19.0-12-amd64     | 2         | 5.71%   |
| 5.9.0-4-amd64       | 1         | 2.86%   |
| 5.8.13-sparky-amd64 | 1         | 2.86%   |
| 5.8.0-2-amd64       | 1         | 2.86%   |
| 5.5.0-2-amd64       | 1         | 2.86%   |
| 5.4.7-sparky-amd64  | 1         | 2.86%   |
| 5.2.0-2-amd64       | 1         | 2.86%   |
| 5.18.0-4-amd64      | 1         | 2.86%   |
| 5.18.0-2-amd64      | 1         | 2.86%   |
| 5.16.0-5-amd64      | 1         | 2.86%   |
| 5.15.0-3-amd64      | 1         | 2.86%   |
| 5.14.0-4-amd64      | 1         | 2.86%   |
| 5.10.4-sparky-amd64 | 1         | 2.86%   |
| 5.10.0-6-amd64      | 1         | 2.86%   |
| 5.10.0-3-amd64      | 1         | 2.86%   |
| 5.10.0-21-amd64     | 1         | 2.86%   |
| 5.10.0-20-amd64     | 1         | 2.86%   |
| 5.10.0-19-amd64     | 1         | 2.86%   |
| 5.10.0-14-amd64     | 1         | 2.86%   |
| 4.19.0-14-686       | 1         | 2.86%   |
| 4.19.0-10-686       | 1         | 2.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 13        | 39.39%  |
| 4.19.0  | 6         | 18.18%  |
| 5.18.0  | 2         | 6.06%   |
| 5.17.0  | 2         | 6.06%   |
| 5.9.0   | 1         | 3.03%   |
| 5.8.13  | 1         | 3.03%   |
| 5.8.0   | 1         | 3.03%   |
| 5.5.0   | 1         | 3.03%   |
| 5.4.7   | 1         | 3.03%   |
| 5.2.0   | 1         | 3.03%   |
| 5.16.0  | 1         | 3.03%   |
| 5.15.0  | 1         | 3.03%   |
| 5.14.0  | 1         | 3.03%   |
| 5.10.4  | 1         | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 14        | 42.42%  |
| 4.19    | 6         | 18.18%  |
| 5.8     | 2         | 6.06%   |
| 5.18    | 2         | 6.06%   |
| 5.17    | 2         | 6.06%   |
| 5.9     | 1         | 3.03%   |
| 5.5     | 1         | 3.03%   |
| 5.4     | 1         | 3.03%   |
| 5.2     | 1         | 3.03%   |
| 5.16    | 1         | 3.03%   |
| 5.15    | 1         | 3.03%   |
| 5.14    | 1         | 3.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 26        | 86.67%  |
| i686   | 4         | 13.33%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 9         | 29.03%  |
| LXQt          | 8         | 25.81%  |
| Unknown       | 7         | 22.58%  |
| openbox       | 2         | 6.45%   |
| MATE          | 2         | 6.45%   |
| KDE5          | 1         | 3.23%   |
| GNOME Classic | 1         | 3.23%   |
| GNOME         | 1         | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 27        | 87.1%   |
| Tty  | 4         | 12.9%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 9         | 30%     |
| Unknown | 9         | 30%     |
| TDM     | 6         | 20%     |
| SDDM    | 4         | 13.33%  |
| XDM     | 1         | 3.33%   |
| GDM     | 1         | 3.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 10        | 33.33%  |
| pl_PL   | 3         | 10%     |
| en_GB   | 3         | 10%     |
| de_DE   | 3         | 10%     |
| fr_FR   | 2         | 6.67%   |
| Unknown | 2         | 6.67%   |
| ja_JP   | 1         | 3.33%   |
| es_MX   | 1         | 3.33%   |
| es_ES   | 1         | 3.33%   |
| es_CL   | 1         | 3.33%   |
| en_PH   | 1         | 3.33%   |
| en_IN   | 1         | 3.33%   |
| en_CA   | 1         | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 20        | 66.67%  |
| EFI  | 10        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 26        | 86.67%  |
| Overlay | 2         | 6.67%   |
| Ext2    | 1         | 3.33%   |
| Btrfs   | 1         | 3.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 11        | 36.67%  |
| GPT     | 10        | 33.33%  |
| Unknown | 9         | 30%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 86.67%  |
| Yes       | 4         | 13.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 66.67%  |
| Yes       | 10        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 26.67%  |
| Lenovo              | 5         | 16.67%  |
| Dell                | 4         | 13.33%  |
| ASUSTek Computer    | 3         | 10%     |
| Google              | 2         | 6.67%   |
| Acer                | 2         | 6.67%   |
| Samsung Electronics | 1         | 3.33%   |
| HUAWEI              | 1         | 3.33%   |
| Fujitsu Siemens     | 1         | 3.33%   |
| eMachines           | 1         | 3.33%   |
| Beelink             | 1         | 3.33%   |
| Apple               | 1         | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Samsung NC10                     | 1         | 3.33%   |
| Lenovo ThinkPad T61 7659AB7      | 1         | 3.33%   |
| Lenovo ThinkPad T60 2007FUG      | 1         | 3.33%   |
| Lenovo ThinkPad E15 20RES0GF00   | 1         | 3.33%   |
| Lenovo IdeaPad S206 20154        | 1         | 3.33%   |
| Lenovo G50-30 80G0               | 1         | 3.33%   |
| HUAWEI HVY-WXX9                  | 1         | 3.33%   |
| HP Stream Notebook PC 13         | 1         | 3.33%   |
| HP Pavilion g7                   | 1         | 3.33%   |
| HP Pavilion dv9000 (GA359UA#ABA) | 1         | 3.33%   |
| HP Pavilion dv5                  | 1         | 3.33%   |
| HP Laptop 17z-ca100              | 1         | 3.33%   |
| HP EliteBook Folio 9480m         | 1         | 3.33%   |
| HP EliteBook 8770w               | 1         | 3.33%   |
| HP EliteBook 745 G3              | 1         | 3.33%   |
| Google Swanky                    | 1         | 3.33%   |
| Google Banon                     | 1         | 3.33%   |
| Fujitsu Siemens STYLISTIC ST5112 | 1         | 3.33%   |
| eMachines E525                   | 1         | 3.33%   |
| Dell Latitude XT3                | 1         | 3.33%   |
| Dell Inspiron N5010              | 1         | 3.33%   |
| Dell Inspiron 5770               | 1         | 3.33%   |
| Dell Inspiron 5720               | 1         | 3.33%   |
| Beelink BT3 PRO                  | 1         | 3.33%   |
| ASUS S101                        | 1         | 3.33%   |
| ASUS M70Vn                       | 1         | 3.33%   |
| ASUS 1000HE                      | 1         | 3.33%   |
| Apple MacBook1,1                 | 1         | 3.33%   |
| Acer Aspire E1-522               | 1         | 3.33%   |
| Acer Aspire 5742G                | 1         | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 3         | 10%     |
| HP Pavilion               | 3         | 10%     |
| HP EliteBook              | 3         | 10%     |
| Dell Inspiron             | 3         | 10%     |
| Acer Aspire               | 2         | 6.67%   |
| Samsung NC10              | 1         | 3.33%   |
| Lenovo IdeaPad            | 1         | 3.33%   |
| Lenovo G50-30             | 1         | 3.33%   |
| HUAWEI HVY-WXX9           | 1         | 3.33%   |
| HP Stream                 | 1         | 3.33%   |
| HP Laptop                 | 1         | 3.33%   |
| Google Swanky             | 1         | 3.33%   |
| Google Banon              | 1         | 3.33%   |
| Fujitsu Siemens STYLISTIC | 1         | 3.33%   |
| eMachines E525            | 1         | 3.33%   |
| Dell Latitude             | 1         | 3.33%   |
| Beelink BT3               | 1         | 3.33%   |
| ASUS S101                 | 1         | 3.33%   |
| ASUS M70Vn                | 1         | 3.33%   |
| ASUS 1000HE               | 1         | 3.33%   |
| Apple MacBook1            | 1         | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2008 | 5         | 16.67%  |
| 2014 | 3         | 10%     |
| 2012 | 3         | 10%     |
| 2009 | 3         | 10%     |
| 2020 | 2         | 6.67%   |
| 2011 | 2         | 6.67%   |
| 2010 | 2         | 6.67%   |
| 2006 | 2         | 6.67%   |
| 2022 | 1         | 3.33%   |
| 2021 | 1         | 3.33%   |
| 2019 | 1         | 3.33%   |
| 2018 | 1         | 3.33%   |
| 2017 | 1         | 3.33%   |
| 2016 | 1         | 3.33%   |
| 2013 | 1         | 3.33%   |
| 2007 | 1         | 3.33%   |

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
| Disabled | 30        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 28        | 93.33%  |
| Yes  | 2         | 6.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 11        | 36.67%  |
| 4.01-8.0   | 6         | 20%     |
| 2.01-3.0   | 4         | 13.33%  |
| 1.01-2.0   | 4         | 13.33%  |
| 32.01-64.0 | 1         | 3.33%   |
| 24.01-32.0 | 1         | 3.33%   |
| 16.01-24.0 | 1         | 3.33%   |
| 8.01-16.0  | 1         | 3.33%   |
| 0.51-1.0   | 1         | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 9         | 28.13%  |
| 1.01-2.0 | 8         | 25%     |
| 2.01-3.0 | 6         | 18.75%  |
| 4.01-8.0 | 3         | 9.38%   |
| 3.01-4.0 | 3         | 9.38%   |
| 0.01-0.5 | 3         | 9.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 76.67%  |
| 2      | 5         | 16.67%  |
| 5      | 1         | 3.33%   |
| 4      | 1         | 3.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 56.67%  |
| Yes       | 13        | 43.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 86.67%  |
| No        | 4         | 13.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 93.33%  |
| No        | 2         | 6.67%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 66.67%  |
| No        | 10        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 26.67%  |
| Germany     | 5         | 16.67%  |
| UK          | 3         | 10%     |
| Poland      | 3         | 10%     |
| France      | 2         | 6.67%   |
| Canada      | 2         | 6.67%   |
| Spain       | 1         | 3.33%   |
| Philippines | 1         | 3.33%   |
| New Zealand | 1         | 3.33%   |
| Mexico      | 1         | 3.33%   |
| Japan       | 1         | 3.33%   |
| India       | 1         | 3.33%   |
| Chile       | 1         | 3.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Leipzig        | 2         | 6.06%   |
| Wenatchee      | 1         | 3.03%   |
| Tucson         | 1         | 3.03%   |
| Tauranga       | 1         | 3.03%   |
| Takahama       | 1         | 3.03%   |
| Spokane        | 1         | 3.03%   |
| San Antonio    | 1         | 3.03%   |
| Salina Cruz    | 1         | 3.03%   |
| Sainte-Julie   | 1         | 3.03%   |
| Quezon City    | 1         | 3.03%   |
| Pujaudran      | 1         | 3.03%   |
| Puente Alto    | 1         | 3.03%   |
| Pompano Beach  | 1         | 3.03%   |
| Munich         | 1         | 3.03%   |
| Montreuil      | 1         | 3.03%   |
| Montreal       | 1         | 3.03%   |
| Miekoszyn      | 1         | 3.03%   |
| Mannheim       | 1         | 3.03%   |
| Madrid         | 1         | 3.03%   |
| Liverpool      | 1         | 3.03%   |
| Koło          | 1         | 3.03%   |
| Houston        | 1         | 3.03%   |
| Hamburg        | 1         | 3.03%   |
| Gmina Bolków  | 1         | 3.03%   |
| Glasgow        | 1         | 3.03%   |
| East Wenatchee | 1         | 3.03%   |
| Dunoon         | 1         | 3.03%   |
| Dobrzen Wielki | 1         | 3.03%   |
| Dehradun       | 1         | 3.03%   |
| Chicago        | 1         | 3.03%   |
| Birmingham     | 1         | 3.03%   |
| Barnsley       | 1         | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 13     | 20.51%  |
| WDC                 | 5         | 7      | 12.82%  |
| Unknown             | 4         | 4      | 10.26%  |
| Samsung Electronics | 4         | 4      | 10.26%  |
| Hitachi             | 4         | 6      | 10.26%  |
| Intel               | 2         | 2      | 5.13%   |
| GOODRAM             | 2         | 4      | 5.13%   |
| SPCC                | 1         | 2      | 2.56%   |
| Silicon Motion      | 1         | 1      | 2.56%   |
| ORICO               | 1         | 1      | 2.56%   |
| Netac               | 1         | 1      | 2.56%   |
| Micron Technology   | 1         | 1      | 2.56%   |
| Fujitsu             | 1         | 2      | 2.56%   |
| Crucial             | 1         | 1      | 2.56%   |
| ASUS-JM             | 1         | 1      | 2.56%   |
| ASMedia             | 1         | 1      | 2.56%   |
| A-DATA Technology   | 1         | 1      | 2.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Seagate Backup+ Hub BK 8TB               | 2         | 4.88%   |
| Hitachi HTS545025B9A300 250GB            | 2         | 4.88%   |
| WDC WD7500BPVX-22JC3T0 752GB             | 1         | 2.44%   |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 2.44%   |
| WDC WD3200BPVT-75ZEST0 320GB             | 1         | 2.44%   |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 2.44%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB     | 1         | 2.44%   |
| Unknown MMC Card  64GB                   | 1         | 2.44%   |
| Unknown MMC Card  32GB                   | 1         | 2.44%   |
| Unknown HBG4a2  32GB                     | 1         | 2.44%   |
| Unknown 016GE2  16GB                     | 1         | 2.44%   |
| SPCC Solid State Disk 256GB              | 1         | 2.44%   |
| Silicon Motion PCIe-8 SSD 512GB          | 1         | 2.44%   |
| Seagate ST9500325AS 500GB                | 1         | 2.44%   |
| Seagate ST9250320AS 250GB                | 1         | 2.44%   |
| Seagate ST9160310AS 160GB                | 1         | 2.44%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 2.44%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 2.44%   |
| Seagate Backup+ Desk 5TB                 | 1         | 2.44%   |
| Samsung SSD 840 Series 120GB             | 1         | 2.44%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB   | 1         | 2.44%   |
| Samsung MZALQ512HALU-000L1 512GB         | 1         | 2.44%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD     | 1         | 2.44%   |
| ORICO M200 1TB SSD                       | 1         | 2.44%   |
| Netac SSD 256GB                          | 1         | 2.44%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 2.44%   |
| Intel SSDSC2CW060A3 64GB                 | 1         | 2.44%   |
| Intel SSDMAEXC024G3H 24GB                | 1         | 2.44%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 2.44%   |
| Hitachi HTS541080G9SA00 80GB             | 1         | 2.44%   |
| GOODRAM SSDPR-CX400-256-G2 256GB         | 1         | 2.44%   |
| GOODRAM SSDPR-CL100-240-G3 240GB         | 1         | 2.44%   |
| Goodram IR-SSDPR-S25A-120 120GB          | 1         | 2.44%   |
| Fujitsu MHW2120BH 120GB                  | 1         | 2.44%   |
| Crucial CT250MX500SSD1 250GB             | 1         | 2.44%   |
| ASUS-JM S41 SSD 16GB                     | 1         | 2.44%   |
| ASMedia ASMT1153e 1TB                    | 1         | 2.44%   |
| A-DATA SX8200NP 480GB                    | 1         | 2.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 12     | 44.44%  |
| WDC     | 4         | 6      | 22.22%  |
| Hitachi | 4         | 6      | 22.22%  |
| Fujitsu | 1         | 2      | 5.56%   |
| ASMedia | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 16.67%  |
| Intel               | 2         | 2      | 16.67%  |
| GOODRAM             | 2         | 4      | 16.67%  |
| SPCC                | 1         | 2      | 8.33%   |
| ORICO               | 1         | 1      | 8.33%   |
| Netac               | 1         | 1      | 8.33%   |
| Micron Technology   | 1         | 1      | 8.33%   |
| Crucial             | 1         | 1      | 8.33%   |
| ASUS-JM             | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 17        | 27     | 45.95%  |
| SSD     | 10        | 15     | 27.03%  |
| NVMe    | 5         | 5      | 13.51%  |
| MMC     | 4         | 4      | 10.81%  |
| Unknown | 1         | 1      | 2.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 37     | 65.71%  |
| NVMe | 5         | 5      | 14.29%  |
| MMC  | 4         | 4      | 11.43%  |
| SAS  | 3         | 6      | 8.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 31     | 73.08%  |
| 0.51-1.0   | 5         | 7      | 19.23%  |
| 4.01-10.0  | 2         | 4      | 7.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 11        | 36.67%  |
| 501-1000       | 5         | 16.67%  |
| 21-50          | 4         | 13.33%  |
| 1-20           | 4         | 13.33%  |
| More than 3000 | 2         | 6.67%   |
| 251-500        | 2         | 6.67%   |
| 1001-2000      | 1         | 3.33%   |
| Unknown        | 1         | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 14        | 43.75%  |
| 21-50          | 5         | 15.63%  |
| 101-250        | 3         | 9.38%   |
| 51-100         | 3         | 9.38%   |
| 251-500        | 2         | 6.25%   |
| 501-1000       | 2         | 6.25%   |
| More than 3000 | 1         | 3.13%   |
| 1001-2000      | 1         | 3.13%   |
| Unknown        | 1         | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 16.67%  |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 16.67%  |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 16.67%  |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 16.67%  |
| Intel SSDSC2CW060A3 64GB                            | 1         | 1      | 16.67%  |
| ASMedia ASMT1153e 1TB                               | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 2         | 2      | 33.33%  |
| Seagate           | 1         | 1      | 16.67%  |
| Micron Technology | 1         | 1      | 16.67%  |
| Intel             | 1         | 1      | 16.67%  |
| ASMedia           | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 50%     |
| Seagate | 1         | 1      | 25%     |
| ASMedia | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 66.67%  |
| SSD  | 2         | 2      | 33.33%  |

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
| Works    | 15        | 25     | 44.12%  |
| Detected | 13        | 21     | 38.24%  |
| Malfunc  | 6         | 6      | 17.65%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 20        | 68.97%  |
| AMD                 | 3         | 10.34%  |
| Silicon Motion      | 2         | 6.9%    |
| Samsung Electronics | 2         | 6.9%    |
| Nvidia              | 1         | 3.45%   |
| JMicron Technology  | 1         | 3.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 3         | 8.82%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 3         | 8.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 3         | 8.82%   |
| Samsung NVMe SSD Controller 980                                              | 2         | 5.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 5.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 2         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 5.88%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 2         | 5.88%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 2.94%   |
| Silicon Motion Non-Volatile memory controller                                | 1         | 2.94%   |
| Nvidia MCP51 Serial ATA Controller                                           | 1         | 2.94%   |
| Nvidia MCP51 IDE                                                             | 1         | 2.94%   |
| JMicron JMB360 AHCI Controller                                               | 1         | 2.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 1         | 2.94%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 2.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 2.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 1         | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 2.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 2.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 2.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 2.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 19        | 59.38%  |
| IDE  | 9         | 28.13%  |
| NVMe | 4         | 12.5%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 80%     |
| AMD    | 6         | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 10%     |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 2         | 6.67%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 6.67%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 3.33%   |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 3.33%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 3.33%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 3.33%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 3.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.33%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 3.33%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.33%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 3.33%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 3.33%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 3.33%   |
| Intel Core 2 CPU U7600 @ 1.20GHz              | 1         | 3.33%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 3.33%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 3.33%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 1         | 3.33%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 3.33%   |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 3.33%   |
| AMD Turion 64 X2 Mobile Technology TL-64      | 1         | 3.33%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 3.33%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.33%   |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G  | 1         | 3.33%   |
| AMD C-50 Processor                            | 1         | 3.33%   |
| AMD A4-5000 APU with Radeon HD Graphics       | 1         | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 5         | 16.67%  |
| Intel Core i5           | 4         | 13.33%  |
| Intel Atom              | 4         | 13.33%  |
| Intel Core i7           | 3         | 10%     |
| Intel Core 2 Duo        | 3         | 10%     |
| Intel Core 2            | 2         | 6.67%   |
| AMD Ryzen 5             | 2         | 6.67%   |
| Intel Pentium           | 1         | 3.33%   |
| Intel Genuine           | 1         | 3.33%   |
| Intel Core i3           | 1         | 3.33%   |
| AMD Turion 64 X2 Mobile | 1         | 3.33%   |
| AMD PRO A10             | 1         | 3.33%   |
| AMD C-50                | 1         | 3.33%   |
| AMD A4                  | 1         | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 17        | 56.67%  |
| 4      | 8         | 26.67%  |
| 1      | 4         | 13.33%  |
| 6      | 1         | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 30        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 16        | 53.33%  |
| 2      | 14        | 46.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 26        | 86.67%  |
| 32-bit         | 4         | 13.33%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 13.33%  |
| 0x30678    | 3         | 10%     |
| 0x6f2      | 2         | 6.67%   |
| 0x406c4    | 2         | 6.67%   |
| 0x306a9    | 2         | 6.67%   |
| 0x206a7    | 2         | 6.67%   |
| 0x20655    | 2         | 6.67%   |
| 0x106c2    | 2         | 6.67%   |
| 0x10676    | 2         | 6.67%   |
| 0x806ec    | 1         | 3.33%   |
| 0x806ea    | 1         | 3.33%   |
| 0x40651    | 1         | 3.33%   |
| 0x1067a    | 1         | 3.33%   |
| 0x08600106 | 1         | 3.33%   |
| 0x08108109 | 1         | 3.33%   |
| 0x0700010f | 1         | 3.33%   |
| 0x0600611a | 1         | 3.33%   |
| 0x05000029 | 1         | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Silvermont  | 5         | 16.67%  |
| Penryn      | 3         | 10%     |
| Core        | 3         | 10%     |
| Bonnell     | 3         | 10%     |
| Westmere    | 2         | 6.67%   |
| SandyBridge | 2         | 6.67%   |
| KabyLake    | 2         | 6.67%   |
| IvyBridge   | 2         | 6.67%   |
| Zen+        | 1         | 3.33%   |
| Zen 2       | 1         | 3.33%   |
| P6          | 1         | 3.33%   |
| K8 Hammer   | 1         | 3.33%   |
| Jaguar      | 1         | 3.33%   |
| Haswell     | 1         | 3.33%   |
| Excavator   | 1         | 3.33%   |
| Bobcat      | 1         | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 63.33%  |
| AMD    | 6         | 20%     |
| Nvidia | 5         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 13.89%  |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 8.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 8.33%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 5.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 5.56%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 2.78%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 2.78%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 2.78%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 2.78%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 2.78%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.78%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.78%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.78%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 2.78%   |
| AMD Renoir                                                                               | 1         | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.78%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 2.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| 1 x Intel  | 19        | 63.33%  |
| 1 x AMD    | 6         | 20%     |
| 1 x Nvidia | 5         | 16.67%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 29        | 96.67%  |
| Proprietary | 1         | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 70%     |
| 0.01-0.5   | 6         | 20%     |
| 1.01-2.0   | 2         | 6.67%   |
| 0.51-1.0   | 1         | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 7         | 24.14%  |
| AU Optronics        | 5         | 17.24%  |
| Chimei Innolux      | 3         | 10.34%  |
| Samsung Electronics | 2         | 6.9%    |
| Lenovo              | 2         | 6.9%    |
| CPT                 | 2         | 6.9%    |
| BOE                 | 2         | 6.9%    |
| Medion              | 1         | 3.45%   |
| LG Philips          | 1         | 3.45%   |
| Insignia            | 1         | 3.45%   |
| Hitachi             | 1         | 3.45%   |
| HannStar            | 1         | 3.45%   |
| Apple               | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D330 SAM0D93 1920x1080 530x300mm 24.0-inch    | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 1         | 3.33%   |
| Medion MD 20310 MED3645 1920x1080 521x293mm 23.5-inch                | 1         | 3.33%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 3.33%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 3.33%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 3.33%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 3.33%   |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch              | 1         | 3.33%   |
| Lenovo LCD Monitor LEN4022 1400x1050 286x214mm 14.1-inch             | 1         | 3.33%   |
| Insignia NS-19E320A13 BBY0032 1680x1050 640x384mm 29.4-inch          | 1         | 3.33%   |
| Hitachi HDMI HEC0088 1920x540                                        | 1         | 3.33%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 3.33%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 3.33%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch     | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch      | 1         | 3.33%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                | 1         | 3.33%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch        | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO139E 1600x900 380x210mm 17.1-inch        | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO132C 1366x768 293x164mm 13.2-inch        | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 380x210mm 17.1-inch       | 1         | 3.33%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 1         | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 9         | 30%     |
| 1366x768 (WXGA)  | 8         | 26.67%  |
| 1600x900 (HD+)   | 3         | 10%     |
| 1024x600         | 3         | 10%     |
| 1920x540         | 2         | 6.67%   |
| 1440x900 (WXGA+) | 2         | 6.67%   |
| 1280x800 (WXGA)  | 2         | 6.67%   |
| 1400x1050        | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 8         | 26.67%  |
| 17     | 6         | 20%     |
| 13     | 5         | 16.67%  |
| 14     | 3         | 10%     |
| 10     | 3         | 10%     |
| 48     | 2         | 6.67%   |
| 24     | 1         | 3.33%   |
| 23     | 1         | 3.33%   |
| 16     | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 36.67%  |
| 201-300     | 8         | 26.67%  |
| 351-400     | 7         | 23.33%  |
| 501-600     | 2         | 6.67%   |
| 1001-1500   | 2         | 6.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 23        | 76.67%  |
| 16/10 | 4         | 13.33%  |
| 1.96  | 2         | 6.67%   |
| 4/3   | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 30%     |
| 121-130        | 5         | 16.67%  |
| 71-80          | 4         | 13.33%  |
| 81-90          | 3         | 10%     |
| 41-50          | 3         | 10%     |
| 201-250        | 2         | 6.67%   |
| 501-1000       | 2         | 6.67%   |
| 131-140        | 1         | 3.33%   |
| 91-100         | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 13        | 44.83%  |
| 121-160 | 10        | 34.48%  |
| 51-100  | 4         | 13.79%  |
| 1-50    | 2         | 6.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 28        | 93.33%  |
| 2     | 1         | 3.33%   |
| 0     | 1         | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 14        | 31.11%  |
| Realtek Semiconductor    | 11        | 24.44%  |
| Qualcomm Atheros         | 8         | 17.78%  |
| Marvell Technology Group | 3         | 6.67%   |
| Broadcom                 | 3         | 6.67%   |
| Broadcom Limited         | 2         | 4.44%   |
| TP-Link                  | 1         | 2.22%   |
| Samsung Electronics      | 1         | 2.22%   |
| Ralink                   | 1         | 2.22%   |
| Nvidia                   | 1         | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 6         | 10.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 7.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 3.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 3.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.64%   |
| Intel Wireless 7265                                                     | 2         | 3.64%   |
| Intel Wireless 7260                                                     | 2         | 3.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 3.64%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 1.82%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.82%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 1.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 1.82%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 1.82%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 1.82%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 1.82%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 1.82%   |
| Intel WiFi Link 5100                                                    | 1         | 1.82%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.82%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.82%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.82%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.82%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.82%   |
| Intel 82573L Gigabit Ethernet Controller                                | 1         | 1.82%   |
| Intel 82566MM Gigabit Network Connection                                | 1         | 1.82%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                        | 1         | 1.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 1         | 1.82%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 1.82%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 48.28%  |
| Qualcomm Atheros      | 7         | 24.14%  |
| Realtek Semiconductor | 3         | 10.34%  |
| Broadcom Limited      | 2         | 6.9%    |
| TP-Link               | 1         | 3.45%   |
| Ralink                | 1         | 3.45%   |
| Broadcom              | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 6.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 6.9%    |
| Intel Wireless 7265                                                     | 2         | 6.9%    |
| Intel Wireless 7260                                                     | 2         | 6.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 6.9%    |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 3.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 3.45%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 3.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 3.45%   |
| Intel WiFi Link 5100                                                    | 1         | 3.45%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 3.45%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 3.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 3.45%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 3.45%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 3.45%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 3.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 3.45%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 3.45%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 3.45%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 10        | 38.46%  |
| Intel                    | 5         | 19.23%  |
| Qualcomm Atheros         | 4         | 15.38%  |
| Marvell Technology Group | 3         | 11.54%  |
| Broadcom                 | 2         | 7.69%   |
| Samsung Electronics      | 1         | 3.85%   |
| Nvidia                   | 1         | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 23.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 15.38%  |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 7.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 3.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 3.85%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 3.85%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 3.85%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 3.85%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 3.85%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 3.85%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 3.85%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 3.85%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 3.85%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 3.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 51.85%  |
| Ethernet | 26        | 48.15%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 68.75%  |
| Ethernet | 10        | 31.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 23        | 76.67%  |
| 1     | 7         | 23.33%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 24        | 75%     |
| Yes  | 8         | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 30%     |
| Broadcom                        | 4         | 20%     |
| Realtek Semiconductor           | 2         | 10%     |
| Taiyo Yuden                     | 1         | 5%      |
| Realtek                         | 1         | 5%      |
| Qualcomm Atheros Communications | 1         | 5%      |
| Foxconn / Hon Hai               | 1         | 5%      |
| Dell                            | 1         | 5%      |
| Cambridge Silicon Radio         | 1         | 5%      |
| ASUSTek Computer                | 1         | 5%      |
| Apple                           | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 20%     |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 5%      |
| Realtek RTL8723B Bluetooth                          | 1         | 5%      |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 5%      |
| Realtek Bluetooth Radio                             | 1         | 5%      |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 5%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 5%      |
| Intel Bluetooth Device                              | 1         | 5%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 5%      |
| Dell Wireless 365 Bluetooth                         | 1         | 5%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5%      |
| Broadcom HP Portable SoftSailing                    | 1         | 5%      |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 5%      |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 5%      |
| Broadcom BCM2045 Bluetooth                          | 1         | 5%      |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 5%      |
| Apple Bluetooth HCI                                 | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 23        | 67.65%  |
| AMD                 | 5         | 14.71%  |
| Nvidia              | 3         | 8.82%   |
| Native Instruments  | 1         | 2.94%   |
| Focusrite-Novation  | 1         | 2.94%   |
| C-Media Electronics | 1         | 2.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 15.38%  |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 7.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 7.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 5.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 5.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 5.13%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 2.56%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 2.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.56%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 2.56%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 2.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.56%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.56%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.56%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 2.56%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 2.56%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.56%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.56%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 2.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 29.17%  |
| Unknown             | 4         | 16.67%  |
| SK hynix            | 3         | 12.5%   |
| Micron Technology   | 3         | 12.5%   |
| Nanya Technology    | 2         | 8.33%   |
| Kingston            | 2         | 8.33%   |
| GOODRAM             | 1         | 4.17%   |
| G.Skill             | 1         | 4.17%   |
| Corsair             | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s      | 2         | 7.41%   |
| Unknown RAM Module 2GB SODIMM SDRAM                        | 1         | 3.7%    |
| Unknown RAM Module 2GB SODIMM DDR2 266MT/s                 | 1         | 3.7%    |
| Unknown RAM Module 2048MB SODIMM 800MT/s                   | 1         | 3.7%    |
| Unknown RAM Module 1024MB SODIMM DDR2                      | 1         | 3.7%    |
| Unknown RAM Module 1024MB SODIMM 800MT/s                   | 1         | 3.7%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s               | 1         | 3.7%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1         | 3.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s  | 1         | 3.7%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 3.7%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 1         | 3.7%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 1         | 3.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 3.7%    |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s      | 1         | 3.7%    |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s            | 1         | 3.7%    |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s       | 1         | 3.7%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 3.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s | 1         | 3.7%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 3.7%    |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s     | 1         | 3.7%    |
| Kingston RAM Module 4GB SODIMM DDR3 800MT/s                | 1         | 3.7%    |
| Kingston RAM ACR16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s     | 1         | 3.7%    |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s   | 1         | 3.7%    |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s     | 1         | 3.7%    |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s     | 1         | 3.7%    |
| Corsair RAM CMSA4GX3M1A1333C9 4GB SODIMM DDR3 1333MT/s     | 1         | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 13        | 59.09%  |
| DDR4    | 3         | 13.64%  |
| SDRAM   | 2         | 9.09%   |
| DDR2    | 2         | 9.09%   |
| LPDDR3  | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 19        | 90.48%  |
| Row Of Chips | 1         | 4.76%   |
| Unknown      | 1         | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 9         | 34.62%  |
| 2048  | 8         | 30.77%  |
| 8192  | 4         | 15.38%  |
| 1024  | 3         | 11.54%  |
| 16384 | 2         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 9         | 37.5%   |
| 2667    | 2         | 8.33%   |
| 1334    | 2         | 8.33%   |
| 1333    | 2         | 8.33%   |
| 800     | 2         | 8.33%   |
| Unknown | 2         | 8.33%   |
| 4199    | 1         | 4.17%   |
| 3200    | 1         | 4.17%   |
| 1867    | 1         | 4.17%   |
| 1066    | 1         | 4.17%   |
| 266     | 1         | 4.17%   |

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
| Chicony Electronics                    | 9         | 37.5%   |
| Microdia                               | 4         | 16.67%  |
| Suyin                                  | 3         | 12.5%   |
| Sunplus Innovation Technology          | 2         | 8.33%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 8.33%   |
| Acer                                   | 2         | 8.33%   |
| Z-Star Microelectronics                | 1         | 4.17%   |
| Microsoft                              | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                           | 2         | 8.33%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 4.17%   |
| Suyin USB2.0 UVC 1.3M WebCam                                | 1         | 4.17%   |
| Suyin HP Truevision HD                                      | 1         | 4.17%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 4.17%   |
| Sunplus Integrated Webcam                                   | 1         | 4.17%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 4.17%   |
| Microsoft LifeCam Cinema                                    | 1         | 4.17%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 4.17%   |
| Microdia Lenovo EasyCamera                                  | 1         | 4.17%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 4.17%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 4.17%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 4.17%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 4.17%   |
| Chicony HP TrueVision HD Camera                             | 1         | 4.17%   |
| Chicony HP Integrated Webcam                                | 1         | 4.17%   |
| Chicony HP HD Webcam                                        | 1         | 4.17%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 4.17%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera            | 1         | 4.17%   |
| Acer Lenovo EasyCamera                                      | 1         | 4.17%   |
| Acer HP Webcam                                              | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 42.86%  |
| AuthenTec                  | 2         | 28.57%  |
| STMicroelectronics         | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 14.29%  |
| Validity Sensors VFS491                    | 1         | 14.29%  |
| Validity Sensors VFS101 Fingerprint Reader | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader      | 1         | 14.29%  |
| Shenzhen Goodix  Fingerprint Device        | 1         | 14.29%  |
| AuthenTec AES2501 Fingerprint Sensor       | 1         | 14.29%  |
| AuthenTec AES1600                          | 1         | 14.29%  |

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


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 17        | 56.67%  |
| 1     | 10        | 33.33%  |
| 2     | 3         | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 7         | 38.89%  |
| Net/wireless          | 4         | 22.22%  |
| Multimedia controller | 3         | 16.67%  |
| Graphics card         | 3         | 16.67%  |
| Chipcard              | 1         | 5.56%   |

