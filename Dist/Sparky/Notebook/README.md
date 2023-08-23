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

Total: 49

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A315-58              | [d7383d2980](https://linux-hardware.org/?probe=d7383d2980) | Jul 20, 2023 |
| HP            | EliteBook 8440p             | [f7a66609af](https://linux-hardware.org/?probe=f7a66609af) | Jul 13, 2023 |
| Panasonic     | CFSZ5-2                     | [d5b1455382](https://linux-hardware.org/?probe=d5b1455382) | May 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [37dab045c7](https://linux-hardware.org/?probe=37dab045c7) | May 21, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [24aaf9e627](https://linux-hardware.org/?probe=24aaf9e627) | May 13, 2023 |
| Apple         | MacBook1,1                  | [002929e495](https://linux-hardware.org/?probe=002929e495) | Mar 26, 2023 |
| MSI           | Alpha 15 A3DDK              | [c4ef9294ef](https://linux-hardware.org/?probe=c4ef9294ef) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [219483f968](https://linux-hardware.org/?probe=219483f968) | Feb 23, 2023 |
| Positivo      | CHT14B                      | [49eff89b98](https://linux-hardware.org/?probe=49eff89b98) | Feb 16, 2023 |
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
| Sparky 6    | 8         | 19.51%  |
| Sparky 7    | 7         | 17.07%  |
| Sparky 6.5  | 4         | 9.76%   |
| Sparky 6.1  | 4         | 9.76%   |
| Sparky 5.14 | 3         | 7.32%   |
| Sparky 6.7  | 2         | 4.88%   |
| Sparky 6.6  | 2         | 4.88%   |
| Sparky 6.3  | 2         | 4.88%   |
| Sparky 6.0  | 2         | 4.88%   |
| Sparky 5.13 | 2         | 4.88%   |
| Sparky 5.12 | 2         | 4.88%   |
| Sparky 5.10 | 2         | 4.88%   |
| Sparky 8    | 1         | 2.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Sparky | 37        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-11-686          | 3         | 6.98%   |
| 5.17.0-1-amd64         | 2         | 4.65%   |
| 5.10.0-9-amd64         | 2         | 4.65%   |
| 5.10.0-8-amd64         | 2         | 4.65%   |
| 5.10.0-21-amd64        | 2         | 4.65%   |
| 4.19.0-8-amd64         | 2         | 4.65%   |
| 4.19.0-13-686          | 2         | 4.65%   |
| 4.19.0-12-amd64        | 2         | 4.65%   |
| 6.4.4-sparky8-amd64    | 1         | 2.33%   |
| 6.3.3-1-liquorix-amd64 | 1         | 2.33%   |
| 6.2.0-sparky-amd64     | 1         | 2.33%   |
| 5.9.0-4-amd64          | 1         | 2.33%   |
| 5.8.13-sparky-amd64    | 1         | 2.33%   |
| 5.8.0-2-amd64          | 1         | 2.33%   |
| 5.5.0-2-amd64          | 1         | 2.33%   |
| 5.4.7-sparky-amd64     | 1         | 2.33%   |
| 5.2.0-2-amd64          | 1         | 2.33%   |
| 5.18.0-4-amd64         | 1         | 2.33%   |
| 5.18.0-2-amd64         | 1         | 2.33%   |
| 5.16.0-5-amd64         | 1         | 2.33%   |
| 5.15.0-3-amd64         | 1         | 2.33%   |
| 5.14.0-4-amd64         | 1         | 2.33%   |
| 5.10.4-sparky-amd64    | 1         | 2.33%   |
| 5.10.0-6-amd64         | 1         | 2.33%   |
| 5.10.0-3-amd64         | 1         | 2.33%   |
| 5.10.0-23-amd64        | 1         | 2.33%   |
| 5.10.0-22-amd64        | 1         | 2.33%   |
| 5.10.0-21-686          | 1         | 2.33%   |
| 5.10.0-20-amd64        | 1         | 2.33%   |
| 5.10.0-19-amd64        | 1         | 2.33%   |
| 5.10.0-16-amd64        | 1         | 2.33%   |
| 5.10.0-14-amd64        | 1         | 2.33%   |
| 4.19.0-14-686          | 1         | 2.33%   |
| 4.19.0-10-686          | 1         | 2.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 17        | 42.5%   |
| 4.19.0  | 6         | 15%     |
| 5.18.0  | 2         | 5%      |
| 5.17.0  | 2         | 5%      |
| 6.4.4   | 1         | 2.5%    |
| 6.3.3   | 1         | 2.5%    |
| 6.2.0   | 1         | 2.5%    |
| 5.9.0   | 1         | 2.5%    |
| 5.8.13  | 1         | 2.5%    |
| 5.8.0   | 1         | 2.5%    |
| 5.5.0   | 1         | 2.5%    |
| 5.4.7   | 1         | 2.5%    |
| 5.2.0   | 1         | 2.5%    |
| 5.16.0  | 1         | 2.5%    |
| 5.15.0  | 1         | 2.5%    |
| 5.14.0  | 1         | 2.5%    |
| 5.10.4  | 1         | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 18        | 45%     |
| 4.19    | 6         | 15%     |
| 5.8     | 2         | 5%      |
| 5.18    | 2         | 5%      |
| 5.17    | 2         | 5%      |
| 6.4     | 1         | 2.5%    |
| 6.3     | 1         | 2.5%    |
| 6.2     | 1         | 2.5%    |
| 5.9     | 1         | 2.5%    |
| 5.5     | 1         | 2.5%    |
| 5.4     | 1         | 2.5%    |
| 5.2     | 1         | 2.5%    |
| 5.16    | 1         | 2.5%    |
| 5.15    | 1         | 2.5%    |
| 5.14    | 1         | 2.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 33        | 89.19%  |
| i686   | 4         | 10.81%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 11        | 28.95%  |
| LXQt          | 9         | 23.68%  |
| Unknown       | 7         | 18.42%  |
| KDE5          | 4         | 10.53%  |
| openbox       | 3         | 7.89%   |
| MATE          | 2         | 5.26%   |
| GNOME Classic | 1         | 2.63%   |
| GNOME         | 1         | 2.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 34        | 89.47%  |
| Tty  | 4         | 10.53%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 11        | 29.73%  |
| Unknown | 10        | 27.03%  |
| SDDM    | 8         | 21.62%  |
| TDM     | 6         | 16.22%  |
| XDM     | 1         | 2.7%    |
| GDM     | 1         | 2.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 12        | 32.43%  |
| pl_PL   | 3         | 8.11%   |
| en_GB   | 3         | 8.11%   |
| de_DE   | 3         | 8.11%   |
| pt_BR   | 2         | 5.41%   |
| fr_FR   | 2         | 5.41%   |
| es_ES   | 2         | 5.41%   |
| Unknown | 2         | 5.41%   |
| ru_RU   | 1         | 2.7%    |
| ja_JP   | 1         | 2.7%    |
| it_IT   | 1         | 2.7%    |
| es_MX   | 1         | 2.7%    |
| es_CL   | 1         | 2.7%    |
| en_PH   | 1         | 2.7%    |
| en_IN   | 1         | 2.7%    |
| en_CA   | 1         | 2.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 22        | 59.46%  |
| EFI  | 15        | 40.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 32        | 86.49%  |
| Overlay | 2         | 5.41%   |
| Btrfs   | 2         | 5.41%   |
| Ext2    | 1         | 2.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 15        | 40.54%  |
| MBR     | 12        | 32.43%  |
| Unknown | 10        | 27.03%  |

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
| No        | 24        | 64.86%  |
| Yes       | 13        | 35.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 24.32%  |
| Lenovo              | 5         | 13.51%  |
| Dell                | 4         | 10.81%  |
| ASUSTek Computer    | 4         | 10.81%  |
| Acer                | 3         | 8.11%   |
| Google              | 2         | 5.41%   |
| Samsung Electronics | 1         | 2.7%    |
| Positivo            | 1         | 2.7%    |
| Panasonic           | 1         | 2.7%    |
| MSI                 | 1         | 2.7%    |
| Mediacom            | 1         | 2.7%    |
| HUAWEI              | 1         | 2.7%    |
| Fujitsu Siemens     | 1         | 2.7%    |
| eMachines           | 1         | 2.7%    |
| Beelink             | 1         | 2.7%    |
| Apple               | 1         | 2.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NC10                            | 1         | 2.7%    |
| Positivo CHT14B                         | 1         | 2.7%    |
| Panasonic CFSZ5-2                       | 1         | 2.7%    |
| MSI Alpha 15 A3DDK                      | 1         | 2.7%    |
| Mediacom SmartBook 14 FullHD - SB14UC   | 1         | 2.7%    |
| Lenovo ThinkPad T61 7659AB7             | 1         | 2.7%    |
| Lenovo ThinkPad T60 2007FUG             | 1         | 2.7%    |
| Lenovo ThinkPad E15 20RES0GF00          | 1         | 2.7%    |
| Lenovo IdeaPad S206 20154               | 1         | 2.7%    |
| Lenovo G50-30 80G0                      | 1         | 2.7%    |
| HUAWEI HVY-WXX9                         | 1         | 2.7%    |
| HP Stream Notebook PC 13                | 1         | 2.7%    |
| HP Pavilion g7                          | 1         | 2.7%    |
| HP Pavilion dv9000 (GA359UA#ABA)        | 1         | 2.7%    |
| HP Pavilion dv5                         | 1         | 2.7%    |
| HP Laptop 17z-ca100                     | 1         | 2.7%    |
| HP EliteBook Folio 9480m                | 1         | 2.7%    |
| HP EliteBook 8770w                      | 1         | 2.7%    |
| HP EliteBook 8440p                      | 1         | 2.7%    |
| HP EliteBook 745 G3                     | 1         | 2.7%    |
| Google Swanky                           | 1         | 2.7%    |
| Google Banon                            | 1         | 2.7%    |
| Fujitsu Siemens STYLISTIC ST5112        | 1         | 2.7%    |
| eMachines E525                          | 1         | 2.7%    |
| Dell Latitude XT3                       | 1         | 2.7%    |
| Dell Inspiron N5010                     | 1         | 2.7%    |
| Dell Inspiron 5770                      | 1         | 2.7%    |
| Dell Inspiron 5720                      | 1         | 2.7%    |
| Beelink BT3 PRO                         | 1         | 2.7%    |
| ASUS VivoBook_ASUSLaptop E410MAB_E410MA | 1         | 2.7%    |
| ASUS S101                               | 1         | 2.7%    |
| ASUS M70Vn                              | 1         | 2.7%    |
| ASUS 1000HE                             | 1         | 2.7%    |
| Apple MacBook1,1                        | 1         | 2.7%    |
| Acer Aspire E1-522                      | 1         | 2.7%    |
| Acer Aspire A315-58                     | 1         | 2.7%    |
| Acer Aspire 5742G                       | 1         | 2.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| HP EliteBook              | 4         | 10.81%  |
| Lenovo ThinkPad           | 3         | 8.11%   |
| HP Pavilion               | 3         | 8.11%   |
| Dell Inspiron             | 3         | 8.11%   |
| Acer Aspire               | 3         | 8.11%   |
| Samsung NC10              | 1         | 2.7%    |
| Positivo CHT14B           | 1         | 2.7%    |
| Panasonic CFSZ5-2         | 1         | 2.7%    |
| MSI Alpha                 | 1         | 2.7%    |
| Mediacom SmartBook        | 1         | 2.7%    |
| Lenovo IdeaPad            | 1         | 2.7%    |
| Lenovo G50-30             | 1         | 2.7%    |
| HUAWEI HVY-WXX9           | 1         | 2.7%    |
| HP Stream                 | 1         | 2.7%    |
| HP Laptop                 | 1         | 2.7%    |
| Google Swanky             | 1         | 2.7%    |
| Google Banon              | 1         | 2.7%    |
| Fujitsu Siemens STYLISTIC | 1         | 2.7%    |
| eMachines E525            | 1         | 2.7%    |
| Dell Latitude             | 1         | 2.7%    |
| Beelink BT3               | 1         | 2.7%    |
| ASUS VivoBook             | 1         | 2.7%    |
| ASUS S101                 | 1         | 2.7%    |
| ASUS M70Vn                | 1         | 2.7%    |
| ASUS 1000HE               | 1         | 2.7%    |
| Apple MacBook1            | 1         | 2.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2008 | 5         | 13.51%  |
| 2021 | 3         | 8.11%   |
| 2014 | 3         | 8.11%   |
| 2012 | 3         | 8.11%   |
| 2010 | 3         | 8.11%   |
| 2009 | 3         | 8.11%   |
| 2020 | 2         | 5.41%   |
| 2019 | 2         | 5.41%   |
| 2018 | 2         | 5.41%   |
| 2017 | 2         | 5.41%   |
| 2016 | 2         | 5.41%   |
| 2011 | 2         | 5.41%   |
| 2006 | 2         | 5.41%   |
| 2022 | 1         | 2.7%    |
| 2013 | 1         | 2.7%    |
| 2007 | 1         | 2.7%    |

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
| Disabled | 37        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 94.59%  |
| Yes  | 2         | 5.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 35.14%  |
| 4.01-8.0   | 7         | 18.92%  |
| 1.01-2.0   | 6         | 16.22%  |
| 2.01-3.0   | 4         | 10.81%  |
| 8.01-16.0  | 3         | 8.11%   |
| 32.01-64.0 | 1         | 2.7%    |
| 24.01-32.0 | 1         | 2.7%    |
| 16.01-24.0 | 1         | 2.7%    |
| 0.51-1.0   | 1         | 2.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 10        | 25.64%  |
| 1.01-2.0 | 10        | 25.64%  |
| 0.51-1.0 | 10        | 25.64%  |
| 4.01-8.0 | 3         | 7.69%   |
| 3.01-4.0 | 3         | 7.69%   |
| 0.01-0.5 | 3         | 7.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 72.97%  |
| 2      | 8         | 21.62%  |
| 5      | 1         | 2.7%    |
| 4      | 1         | 2.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 62.16%  |
| Yes       | 14        | 37.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 83.78%  |
| No        | 6         | 16.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 91.89%  |
| No        | 3         | 8.11%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 67.57%  |
| No        | 12        | 32.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 9         | 24.32%  |
| Germany     | 5         | 13.51%  |
| UK          | 3         | 8.11%   |
| Poland      | 3         | 8.11%   |
| Spain       | 2         | 5.41%   |
| France      | 2         | 5.41%   |
| Canada      | 2         | 5.41%   |
| Brazil      | 2         | 5.41%   |
| Uzbekistan  | 1         | 2.7%    |
| Philippines | 1         | 2.7%    |
| New Zealand | 1         | 2.7%    |
| Mexico      | 1         | 2.7%    |
| Japan       | 1         | 2.7%    |
| Italy       | 1         | 2.7%    |
| Indonesia   | 1         | 2.7%    |
| India       | 1         | 2.7%    |
| Chile       | 1         | 2.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Leipzig        | 2         | 5%      |
| Wenatchee      | 1         | 2.5%    |
| Tucson         | 1         | 2.5%    |
| Tauranga       | 1         | 2.5%    |
| Takahama       | 1         | 2.5%    |
| Spokane        | 1         | 2.5%    |
| Santo André   | 1         | 2.5%    |
| San Antonio    | 1         | 2.5%    |
| Salina Cruz    | 1         | 2.5%    |
| Sainte-Julie   | 1         | 2.5%    |
| Rio de Janeiro | 1         | 2.5%    |
| Quezon City    | 1         | 2.5%    |
| Pujaudran      | 1         | 2.5%    |
| Puente Alto    | 1         | 2.5%    |
| Pompano Beach  | 1         | 2.5%    |
| Munich         | 1         | 2.5%    |
| Montreuil      | 1         | 2.5%    |
| Montreal       | 1         | 2.5%    |
| Milano         | 1         | 2.5%    |
| Miekoszyn      | 1         | 2.5%    |
| Mannheim       | 1         | 2.5%    |
| Madrid         | 1         | 2.5%    |
| Liverpool      | 1         | 2.5%    |
| Koło          | 1         | 2.5%    |
| Jakarta        | 1         | 2.5%    |
| Houston        | 1         | 2.5%    |
| Hamburg        | 1         | 2.5%    |
| Gmina Bolków  | 1         | 2.5%    |
| Glasgow        | 1         | 2.5%    |
| Framingham     | 1         | 2.5%    |
| East Wenatchee | 1         | 2.5%    |
| Dunoon         | 1         | 2.5%    |
| Dobrzen Wielki | 1         | 2.5%    |
| Dehradun       | 1         | 2.5%    |
| Chicago        | 1         | 2.5%    |
| Bukhara        | 1         | 2.5%    |
| Birmingham     | 1         | 2.5%    |
| Barnsley       | 1         | 2.5%    |
| Amorebieta     | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 14     | 18.37%  |
| Unknown             | 7         | 7      | 14.29%  |
| WDC                 | 6         | 8      | 12.24%  |
| Samsung Electronics | 5         | 5      | 10.2%   |
| Hitachi             | 4         | 7      | 8.16%   |
| Intel               | 2         | 2      | 4.08%   |
| Goodram             | 2         | 4      | 4.08%   |
| Toshiba             | 1         | 1      | 2.04%   |
| SPCC                | 1         | 2      | 2.04%   |
| SK hynix            | 1         | 1      | 2.04%   |
| Silicon Motion      | 1         | 1      | 2.04%   |
| ORICO               | 1         | 1      | 2.04%   |
| Netac               | 1         | 1      | 2.04%   |
| Micron Technology   | 1         | 1      | 2.04%   |
| HGST                | 1         | 1      | 2.04%   |
| Fujitsu             | 1         | 2      | 2.04%   |
| Crucial             | 1         | 1      | 2.04%   |
| ASUS-JM             | 1         | 1      | 2.04%   |
| ASMedia             | 1         | 1      | 2.04%   |
| A-DATA Technology   | 1         | 1      | 2.04%   |
| Unknown             | 1         | 1      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                   | 2         | 3.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 2         | 3.92%   |
| Seagate Backup+ Hub BK 8TB               | 2         | 3.92%   |
| Hitachi HTS545025B9A300 250GB            | 2         | 3.92%   |
| WDC WD7500BPVX-22JC3T0 752GB             | 1         | 1.96%   |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 1.96%   |
| WDC WD50 00LPCX-21VHAT0 500GB            | 1         | 1.96%   |
| WDC WD3200BPVT-75ZEST0 320GB             | 1         | 1.96%   |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 1.96%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB     | 1         | 1.96%   |
| Unknown SDC  8GB                         | 1         | 1.96%   |
| Unknown NCard  32GB                      | 1         | 1.96%   |
| Unknown MMC Card  64GB                   | 1         | 1.96%   |
| Unknown HBG4a2  32GB                     | 1         | 1.96%   |
| Unknown 016GE2  16GB                     | 1         | 1.96%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1.96%   |
| SPCC Solid State Disk 256GB              | 1         | 1.96%   |
| SK hynix BC711 HFM256GD3JX013N 256GB     | 1         | 1.96%   |
| Silicon Motion PCIe-8 SSD 512GB          | 1         | 1.96%   |
| Seagate ST9500325AS 500GB                | 1         | 1.96%   |
| Seagate ST9250320AS 250GB                | 1         | 1.96%   |
| Seagate ST9160310AS 160GB                | 1         | 1.96%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 1.96%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 1.96%   |
| Seagate Backup+ Desk 4TB                 | 1         | 1.96%   |
| Samsung SSD 840 Series 120GB             | 1         | 1.96%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 1.96%   |
| Samsung MZVLB512HAJQ-00000 512GB         | 1         | 1.96%   |
| Samsung MZALQ512HALU-000L1 512GB         | 1         | 1.96%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD     | 1         | 1.96%   |
| ORICO M200 1TB SSD                       | 1         | 1.96%   |
| Netac SSD 256GB                          | 1         | 1.96%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1.96%   |
| Intel SSDSC2CW060A3 64GB                 | 1         | 1.96%   |
| Intel SSDMAEXC024G3H 24GB                | 1         | 1.96%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 1.96%   |
| Hitachi HTS541080G9SA00 80GB             | 1         | 1.96%   |
| HGST HTS545032A7E680 320GB               | 1         | 1.96%   |
| GOODRAM SSDPR-CX400-256-G2 256GB         | 1         | 1.96%   |
| GOODRAM SSDPR-CL100-240-G3 240GB         | 1         | 1.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 13     | 40.91%  |
| WDC     | 5         | 7      | 22.73%  |
| Hitachi | 4         | 7      | 18.18%  |
| Toshiba | 1         | 1      | 4.55%   |
| HGST    | 1         | 1      | 4.55%   |
| Fujitsu | 1         | 2      | 4.55%   |
| ASMedia | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 16.67%  |
| Intel               | 2         | 2      | 16.67%  |
| Goodram             | 2         | 4      | 16.67%  |
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
| HDD     | 20        | 32     | 43.48%  |
| SSD     | 10        | 15     | 21.74%  |
| MMC     | 8         | 8      | 17.39%  |
| NVMe    | 7         | 7      | 15.22%  |
| Unknown | 1         | 1      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 26        | 41     | 57.78%  |
| MMC  | 8         | 8      | 17.78%  |
| NVMe | 7         | 7      | 15.56%  |
| SAS  | 4         | 7      | 8.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 34     | 66.67%  |
| 0.51-1.0   | 7         | 8      | 23.33%  |
| 4.01-10.0  | 2         | 4      | 6.67%   |
| 2.01-3.0   | 1         | 1      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 11        | 29.73%  |
| 501-1000       | 8         | 21.62%  |
| 21-50          | 6         | 16.22%  |
| 1-20           | 5         | 13.51%  |
| 251-500        | 3         | 8.11%   |
| More than 3000 | 2         | 5.41%   |
| 1001-2000      | 1         | 2.7%    |
| Unknown        | 1         | 2.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 18        | 46.15%  |
| 21-50          | 6         | 15.38%  |
| 251-500        | 3         | 7.69%   |
| 101-250        | 3         | 7.69%   |
| 501-1000       | 3         | 7.69%   |
| 51-100         | 3         | 7.69%   |
| More than 3000 | 1         | 2.56%   |
| 1001-2000      | 1         | 2.56%   |
| Unknown        | 1         | 2.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 14.29%  |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 14.29%  |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 14.29%  |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 14.29%  |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 14.29%  |
| Intel SSDSC2CW060A3 64GB                            | 1         | 1      | 14.29%  |
| ASMedia ASMT1153E 3TB                               | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 2         | 2      | 28.57%  |
| Seagate           | 2         | 2      | 28.57%  |
| Micron Technology | 1         | 1      | 14.29%  |
| Intel             | 1         | 1      | 14.29%  |
| ASMedia           | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| Seagate | 2         | 2      | 40%     |
| ASMedia | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 71.43%  |
| SSD  | 2         | 2      | 28.57%  |

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
| Detected | 18        | 28     | 42.86%  |
| Works    | 17        | 28     | 40.48%  |
| Malfunc  | 7         | 7      | 16.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 24        | 68.57%  |
| Samsung Electronics | 3         | 8.57%   |
| AMD                 | 3         | 8.57%   |
| Silicon Motion      | 2         | 5.71%   |
| SK hynix            | 1         | 2.86%   |
| Nvidia              | 1         | 2.86%   |
| JMicron Technology  | 1         | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 3         | 7.5%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 3         | 7.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 3         | 7.5%    |
| Samsung NVMe SSD Controller 980                                              | 2         | 5%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 5%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 5%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 2         | 5%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 5%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 5%      |
| AMD FCH SATA Controller [AHCI mode]                                          | 2         | 5%      |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 2.5%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 2.5%    |
| Silicon Motion Non-Volatile memory controller                                | 1         | 2.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 2.5%    |
| Nvidia MCP51 Serial ATA Controller                                           | 1         | 2.5%    |
| Nvidia MCP51 IDE                                                             | 1         | 2.5%    |
| JMicron JMB360 AHCI Controller                                               | 1         | 2.5%    |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 2.5%    |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 2.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 2.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 2.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 1         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 2.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 23        | 60.53%  |
| IDE  | 9         | 23.68%  |
| NVMe | 6         | 15.79%  |

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


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 8.11%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 2         | 5.41%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 5.41%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 5.41%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 2.7%    |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 2.7%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 2.7%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2.7%    |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 2.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.7%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 2.7%    |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.7%    |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 2.7%    |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 2.7%    |
| Intel Core 2 CPU U7600 @ 1.20GHz              | 1         | 2.7%    |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 2.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.7%    |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 2.7%    |
| Intel Celeron CPU 900 @ 2.20GHz               | 1         | 2.7%    |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 1         | 2.7%    |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 2.7%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 2.7%    |
| AMD Turion 64 X2 Mobile Technology TL-64      | 1         | 2.7%    |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 2.7%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.7%    |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G  | 1         | 2.7%    |
| AMD C-50 Processor                            | 1         | 2.7%    |
| AMD A4-5000 APU with Radeon HD Graphics       | 1         | 2.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 6         | 16.22%  |
| Intel Celeron           | 6         | 16.22%  |
| Intel Atom              | 6         | 16.22%  |
| Intel Core i7           | 3         | 8.11%   |
| Intel Core 2 Duo        | 3         | 8.11%   |
| Intel Core 2            | 2         | 5.41%   |
| AMD Ryzen 5             | 2         | 5.41%   |
| Other                   | 1         | 2.7%    |
| Intel Pentium           | 1         | 2.7%    |
| Intel Genuine           | 1         | 2.7%    |
| Intel Core i3           | 1         | 2.7%    |
| AMD Turion 64 X2 Mobile | 1         | 2.7%    |
| AMD Ryzen 7             | 1         | 2.7%    |
| AMD PRO A10             | 1         | 2.7%    |
| AMD C-50                | 1         | 2.7%    |
| AMD A4                  | 1         | 2.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 21        | 56.76%  |
| 4      | 11        | 29.73%  |
| 1      | 4         | 10.81%  |
| 6      | 1         | 2.7%    |

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
| 1      | 19        | 51.35%  |
| 2      | 18        | 48.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 89.19%  |
| 32-bit         | 4         | 10.81%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 16.22%  |
| 0x406c4    | 3         | 8.11%   |
| 0x30678    | 3         | 8.11%   |
| 0x20655    | 3         | 8.11%   |
| 0x6f2      | 2         | 5.41%   |
| 0x306a9    | 2         | 5.41%   |
| 0x206a7    | 2         | 5.41%   |
| 0x106c2    | 2         | 5.41%   |
| 0x10676    | 2         | 5.41%   |
| 0x08108109 | 2         | 5.41%   |
| 0x806ec    | 1         | 2.7%    |
| 0x806ea    | 1         | 2.7%    |
| 0x706a8    | 1         | 2.7%    |
| 0x406c3    | 1         | 2.7%    |
| 0x40651    | 1         | 2.7%    |
| 0x1067a    | 1         | 2.7%    |
| 0x08600106 | 1         | 2.7%    |
| 0x0700010f | 1         | 2.7%    |
| 0x0600611a | 1         | 2.7%    |
| 0x05000029 | 1         | 2.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 7         | 18.92%  |
| Westmere      | 3         | 8.11%   |
| Penryn        | 3         | 8.11%   |
| Core          | 3         | 8.11%   |
| Bonnell       | 3         | 8.11%   |
| Zen+          | 2         | 5.41%   |
| SandyBridge   | 2         | 5.41%   |
| KabyLake      | 2         | 5.41%   |
| IvyBridge     | 2         | 5.41%   |
| Zen 2         | 1         | 2.7%    |
| TigerLake     | 1         | 2.7%    |
| Skylake       | 1         | 2.7%    |
| P6            | 1         | 2.7%    |
| K8 Hammer     | 1         | 2.7%    |
| Jaguar        | 1         | 2.7%    |
| Haswell       | 1         | 2.7%    |
| Goldmont plus | 1         | 2.7%    |
| Excavator     | 1         | 2.7%    |
| Bobcat        | 1         | 2.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 67.57%  |
| AMD    | 7         | 18.92%  |
| Nvidia | 5         | 13.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 11.36%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 9.09%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 6.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 6.82%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 4.55%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 4.55%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 2.27%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 2.27%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 2.27%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 2.27%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 2.27%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.27%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 2.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.27%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.27%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.27%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 2.27%   |
| AMD Renoir                                                                               | 1         | 2.27%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 2.27%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 2.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| 1 x Intel  | 25        | 67.57%  |
| 1 x AMD    | 6         | 16.22%  |
| 1 x Nvidia | 5         | 13.51%  |
| 2 x AMD    | 1         | 2.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 36        | 97.3%   |
| Proprietary | 1         | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 72.97%  |
| 0.01-0.5   | 6         | 16.22%  |
| 1.01-2.0   | 3         | 8.11%   |
| 0.51-1.0   | 1         | 2.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 8         | 21.62%  |
| AU Optronics        | 6         | 16.22%  |
| BOE                 | 5         | 13.51%  |
| CPT                 | 3         | 8.11%   |
| Chimei Innolux      | 3         | 8.11%   |
| Samsung Electronics | 2         | 5.41%   |
| Lenovo              | 2         | 5.41%   |
| Sony                | 1         | 2.7%    |
| PANDA               | 1         | 2.7%    |
| Medion              | 1         | 2.7%    |
| LG Philips          | 1         | 2.7%    |
| Insignia            | 1         | 2.7%    |
| Hitachi             | 1         | 2.7%    |
| HannStar            | 1         | 2.7%    |
| Apple               | 1         | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sony TV SNY2A03 1920x1080                                            | 1         | 2.63%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch    | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 1         | 2.63%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch              | 1         | 2.63%   |
| Medion MD 20310 MED3645 1920x1080 521x293mm 23.5-inch                | 1         | 2.63%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 2.63%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 2.63%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 2.63%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 2.63%   |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch              | 1         | 2.63%   |
| Lenovo LCD Monitor LEN4022 1400x1050 286x214mm 14.1-inch             | 1         | 2.63%   |
| Insignia BBY LCD BBY0032 1920x540                                    | 1         | 2.63%   |
| Hitachi HDMI HEC0088 1920x540                                        | 1         | 2.63%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 1         | 2.63%   |
| CPT LCD Monitor CPT37D5 1920x1200 260x160mm 12.0-inch                | 1         | 2.63%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 2.63%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch      | 1         | 2.63%   |
| BOE LCD Monitor BOE08B2 1366x768 309x174mm 14.0-inch                 | 1         | 2.63%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                | 1         | 2.63%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 1         | 2.63%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 1         | 2.63%   |
| BOE LCD Monitor BOE0635 1920x1080 309x173mm 13.9-inch                | 1         | 2.63%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO132C 1366x768 293x164mm 13.2-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch       | 1         | 2.63%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 13        | 34.21%  |
| 1366x768 (WXGA)   | 11        | 28.95%  |
| 1600x900 (HD+)    | 3         | 7.89%   |
| 1024x600          | 3         | 7.89%   |
| 1920x540          | 2         | 5.26%   |
| 1440x900 (WXGA+)  | 2         | 5.26%   |
| 1280x800 (WXGA)   | 2         | 5.26%   |
| 1920x1200 (WUXGA) | 1         | 2.63%   |
| 1400x1050         | 1         | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 10        | 26.32%  |
| 13     | 7         | 18.42%  |
| 17     | 6         | 15.79%  |
| 14     | 5         | 13.16%  |
| 10     | 3         | 7.89%   |
| 48     | 2         | 5.26%   |
| 72     | 1         | 2.63%   |
| 24     | 1         | 2.63%   |
| 23     | 1         | 2.63%   |
| 16     | 1         | 2.63%   |
| 12     | 1         | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 44.74%  |
| 201-300     | 9         | 23.68%  |
| 351-400     | 7         | 18.42%  |
| 501-600     | 2         | 5.26%   |
| 1001-1500   | 2         | 5.26%   |
| 1501-2000   | 1         | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 29        | 78.38%  |
| 16/10 | 5         | 13.51%  |
| 1.96  | 2         | 5.41%   |
| 4/3   | 1         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 11        | 28.95%  |
| 81-90          | 7         | 18.42%  |
| 121-130        | 5         | 13.16%  |
| 71-80          | 4         | 10.53%  |
| 41-50          | 3         | 7.89%   |
| 201-250        | 2         | 5.26%   |
| 501-1000       | 2         | 5.26%   |
| More than 1000 | 1         | 2.63%   |
| 61-70          | 1         | 2.63%   |
| 131-140        | 1         | 2.63%   |
| 91-100         | 1         | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 16        | 43.24%  |
| 121-160 | 13        | 35.14%  |
| 51-100  | 4         | 10.81%  |
| 1-50    | 3         | 8.11%   |
| 161-240 | 1         | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 34        | 91.89%  |
| 2     | 2         | 5.41%   |
| 0     | 1         | 2.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 17        | 31.48%  |
| Realtek Semiconductor    | 15        | 27.78%  |
| Qualcomm Atheros         | 8         | 14.81%  |
| Marvell Technology Group | 3         | 5.56%   |
| Broadcom                 | 3         | 5.56%   |
| Broadcom Limited         | 2         | 3.7%    |
| TP-Link                  | 1         | 1.85%   |
| Samsung Electronics      | 1         | 1.85%   |
| Ralink                   | 1         | 1.85%   |
| OPPO Electronics         | 1         | 1.85%   |
| Nvidia                   | 1         | 1.85%   |
| Edimax Technology        | 1         | 1.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 7         | 10.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 5.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.99%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 2.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.99%   |
| Intel Wireless 7265                                                     | 2         | 2.99%   |
| Intel Wireless 7260                                                     | 2         | 2.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 2.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 2.99%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 1.49%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 1.49%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 1.49%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 1.49%   |
| OPPO SM6375-QRD _SN:F4A23F05                                            | 1         | 1.49%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 1.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 1.49%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 1.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 1.49%   |
| Intel Wireless 8260                                                     | 1         | 1.49%   |
| Intel WiFi Link 5100                                                    | 1         | 1.49%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.49%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.49%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.49%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 1.49%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.49%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.49%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.49%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.49%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 47.22%  |
| Qualcomm Atheros      | 7         | 19.44%  |
| Realtek Semiconductor | 6         | 16.67%  |
| Broadcom Limited      | 2         | 5.56%   |
| TP-Link               | 1         | 2.78%   |
| Ralink                | 1         | 2.78%   |
| Edimax Technology     | 1         | 2.78%   |
| Broadcom              | 1         | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 5.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 5.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 5.56%   |
| Intel Wireless 7265                                                     | 2         | 5.56%   |
| Intel Wireless 7260                                                     | 2         | 5.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 5.56%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 2.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 2.78%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 2.78%   |
| Intel Wireless 8260                                                     | 1         | 2.78%   |
| Intel WiFi Link 5100                                                    | 1         | 2.78%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 2.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 2.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 2.78%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 2.78%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.78%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.78%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 2.78%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 2.78%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 2.78%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2.78%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 12        | 38.71%  |
| Intel                    | 7         | 22.58%  |
| Qualcomm Atheros         | 4         | 12.9%   |
| Marvell Technology Group | 3         | 9.68%   |
| Broadcom                 | 2         | 6.45%   |
| Samsung Electronics      | 1         | 3.23%   |
| OPPO Electronics         | 1         | 3.23%   |
| Nvidia                   | 1         | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 22.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 12.9%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 6.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 6.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 3.23%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 3.23%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 3.23%   |
| OPPO SM6375-QRD _SN:F4A23F05                                      | 1         | 3.23%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 3.23%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 3.23%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 3.23%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 3.23%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.23%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 3.23%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.23%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 3.23%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 3.23%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 3.23%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 52.31%  |
| Ethernet | 31        | 47.69%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 69.23%  |
| Ethernet | 12        | 30.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 26        | 70.27%  |
| 1     | 8         | 21.62%  |
| 0     | 2         | 5.41%   |
| 3     | 1         | 2.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 74.36%  |
| Yes  | 10        | 25.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 32%     |
| Broadcom                        | 4         | 16%     |
| Realtek Semiconductor           | 2         | 8%      |
| IMC Networks                    | 2         | 8%      |
| Taiyo Yuden                     | 1         | 4%      |
| Realtek                         | 1         | 4%      |
| Qualcomm Atheros Communications | 1         | 4%      |
| Hewlett-Packard                 | 1         | 4%      |
| Foxconn / Hon Hai               | 1         | 4%      |
| Dell                            | 1         | 4%      |
| Cambridge Silicon Radio         | 1         | 4%      |
| ASUSTek Computer                | 1         | 4%      |
| Apple                           | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 20%     |
| IMC Networks Bluetooth Radio                        | 2         | 8%      |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 4%      |
| Realtek RTL8723B Bluetooth                          | 1         | 4%      |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 4%      |
| Realtek 802.11ac WLAN Adapter                       | 1         | 4%      |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 4%      |
| Intel AX201 Bluetooth                               | 1         | 4%      |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 4%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 4%      |
| Dell Wireless 365 Bluetooth                         | 1         | 4%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4%      |
| Broadcom HP Portable SoftSailing                    | 1         | 4%      |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 4%      |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 4%      |
| Broadcom BCM2045 Bluetooth                          | 1         | 4%      |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 4%      |
| Apple Bluetooth HCI                                 | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 27        | 67.5%   |
| AMD                 | 6         | 15%     |
| Nvidia              | 3         | 7.5%    |
| Native Instruments  | 1         | 2.5%    |
| Focusrite-Novation  | 1         | 2.5%    |
| C-Media Electronics | 1         | 2.5%    |
| ASUSTek Computer    | 1         | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 13.04%  |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 6.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 6.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 6.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 4.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 4.35%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 4.35%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 2.17%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 2.17%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.17%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 2.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.17%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.17%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.17%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 2.17%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 2.17%   |
| ASUSTek Computer C-Media Audio                                                                    | 1         | 2.17%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.17%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 2.17%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.17%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 31.25%  |
| Unknown             | 6         | 18.75%  |
| SK hynix            | 4         | 12.5%   |
| Micron Technology   | 3         | 9.38%   |
| Nanya Technology    | 2         | 6.25%   |
| Kingston            | 2         | 6.25%   |
| High Bridge         | 1         | 3.13%   |
| GOODRAM             | 1         | 3.13%   |
| G.Skill             | 1         | 3.13%   |
| Crucial             | 1         | 3.13%   |
| Corsair             | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                 | 2         | 5.71%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s       | 2         | 5.71%   |
| Unknown RAM Module 2GB SODIMM SDRAM                         | 1         | 2.86%   |
| Unknown RAM Module 2GB SODIMM DDR2 266MT/s                  | 1         | 2.86%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                    | 1         | 2.86%   |
| Unknown RAM Module 1024MB SODIMM DDR2                       | 1         | 2.86%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                    | 1         | 2.86%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                | 1         | 2.86%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 1         | 2.86%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 1         | 2.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 1         | 2.86%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 2.86%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s            | 1         | 2.86%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s    | 1         | 2.86%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s       | 1         | 2.86%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 2.86%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s       | 1         | 2.86%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 1         | 2.86%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 1         | 2.86%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s             | 1         | 2.86%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s        | 1         | 2.86%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s        | 1         | 2.86%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s  | 1         | 2.86%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s       | 1         | 2.86%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s      | 1         | 2.86%   |
| Kingston RAM Module 4GB SODIMM DDR3 800MT/s                 | 1         | 2.86%   |
| Kingston RAM ACR16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s      | 1         | 2.86%   |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s    | 1         | 2.86%   |
| High Bridge RAM HB3SU004GFM8MML33. 4GB SODIMM DDR3 1333MT/s | 1         | 2.86%   |
| GOODRAM RAM GR1600S3V64L11/8G 8192MB SODIMM DDR3 1600MT/s   | 1         | 2.86%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s      | 1         | 2.86%   |
| Crucial RAM CB8GS2666.C8RT 8GB SODIMM DDR4 2667MT/s         | 1         | 2.86%   |
| Corsair RAM CMSA4GX3M1A1333C9 4GB SODIMM DDR3 1333MT/s      | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 16        | 57.14%  |
| DDR4    | 6         | 21.43%  |
| SDRAM   | 2         | 7.14%   |
| DDR2    | 2         | 7.14%   |
| LPDDR3  | 1         | 3.57%   |
| Unknown | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 25        | 92.59%  |
| Row Of Chips | 1         | 3.7%    |
| Unknown      | 1         | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 11        | 33.33%  |
| 4096  | 10        | 30.3%   |
| 8192  | 6         | 18.18%  |
| 16384 | 3         | 9.09%   |
| 1024  | 3         | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 9         | 29.03%  |
| 2667    | 4         | 12.9%   |
| 1334    | 3         | 9.68%   |
| 1333    | 3         | 9.68%   |
| 1066    | 3         | 9.68%   |
| 3200    | 2         | 6.45%   |
| 800     | 2         | 6.45%   |
| Unknown | 2         | 6.45%   |
| 4199    | 1         | 3.23%   |
| 1867    | 1         | 3.23%   |
| 266     | 1         | 3.23%   |

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
| Chicony Electronics                    | 10        | 32.26%  |
| Microdia                               | 4         | 12.9%   |
| Suyin                                  | 3         | 9.68%   |
| Bison Electronics                      | 3         | 9.68%   |
| Sunplus Innovation Technology          | 2         | 6.45%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.45%   |
| Alcor Micro                            | 2         | 6.45%   |
| Z-Star Microelectronics                | 1         | 3.23%   |
| Sonix Technology                       | 1         | 3.23%   |
| Quanta                                 | 1         | 3.23%   |
| Microsoft                              | 1         | 3.23%   |
| Acer                                   | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                           | 2         | 6.45%   |
| Alcor Micro USB 2.0 Camera                                  | 2         | 6.45%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 3.23%   |
| Suyin USB2.0 UVC 1.3M WebCam                                | 1         | 3.23%   |
| Suyin HP Truevision HD                                      | 1         | 3.23%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 3.23%   |
| Sunplus Integrated Webcam                                   | 1         | 3.23%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 3.23%   |
| Sonix USB2.0 HD UVC WebCam                                  | 1         | 3.23%   |
| Quanta HD User Facing                                       | 1         | 3.23%   |
| Microsoft LifeCam Cinema                                    | 1         | 3.23%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 3.23%   |
| Microdia Lenovo EasyCamera                                  | 1         | 3.23%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 3.23%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 3.23%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 3.23%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 3.23%   |
| Chicony HP Webcam [2 MP Macro]                              | 1         | 3.23%   |
| Chicony HP TrueVision HD Camera                             | 1         | 3.23%   |
| Chicony HP Integrated Webcam                                | 1         | 3.23%   |
| Chicony HP HD Webcam                                        | 1         | 3.23%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 3.23%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera            | 1         | 3.23%   |
| Bison USB HD Webcam                                         | 1         | 3.23%   |
| Bison HP Webcam                                             | 1         | 3.23%   |
| Bison HD Webcam                                             | 1         | 3.23%   |
| Acer Lenovo EasyCamera                                      | 1         | 3.23%   |

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
| 0     | 23        | 62.16%  |
| 1     | 11        | 29.73%  |
| 2     | 3         | 8.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 7         | 36.84%  |
| Net/wireless          | 4         | 21.05%  |
| Multimedia controller | 4         | 21.05%  |
| Graphics card         | 3         | 15.79%  |
| Chipcard              | 1         | 5.26%   |

