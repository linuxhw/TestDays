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

Total: 47

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Sparky 6    | 8         | 20.51%  |
| Sparky 7    | 7         | 17.95%  |
| Sparky 6.5  | 4         | 10.26%  |
| Sparky 6.1  | 4         | 10.26%  |
| Sparky 5.14 | 3         | 7.69%   |
| Sparky 6.7  | 2         | 5.13%   |
| Sparky 6.6  | 2         | 5.13%   |
| Sparky 6.0  | 2         | 5.13%   |
| Sparky 5.13 | 2         | 5.13%   |
| Sparky 5.12 | 2         | 5.13%   |
| Sparky 5.10 | 2         | 5.13%   |
| Sparky 6.3  | 1         | 2.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Sparky | 35        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-11-686          | 3         | 7.32%   |
| 5.17.0-1-amd64         | 2         | 4.88%   |
| 5.10.0-9-amd64         | 2         | 4.88%   |
| 5.10.0-8-amd64         | 2         | 4.88%   |
| 5.10.0-21-amd64        | 2         | 4.88%   |
| 4.19.0-8-amd64         | 2         | 4.88%   |
| 4.19.0-13-686          | 2         | 4.88%   |
| 4.19.0-12-amd64        | 2         | 4.88%   |
| 6.3.3-1-liquorix-amd64 | 1         | 2.44%   |
| 6.2.0-sparky-amd64     | 1         | 2.44%   |
| 5.9.0-4-amd64          | 1         | 2.44%   |
| 5.8.13-sparky-amd64    | 1         | 2.44%   |
| 5.8.0-2-amd64          | 1         | 2.44%   |
| 5.5.0-2-amd64          | 1         | 2.44%   |
| 5.4.7-sparky-amd64     | 1         | 2.44%   |
| 5.2.0-2-amd64          | 1         | 2.44%   |
| 5.18.0-4-amd64         | 1         | 2.44%   |
| 5.18.0-2-amd64         | 1         | 2.44%   |
| 5.16.0-5-amd64         | 1         | 2.44%   |
| 5.15.0-3-amd64         | 1         | 2.44%   |
| 5.14.0-4-amd64         | 1         | 2.44%   |
| 5.10.4-sparky-amd64    | 1         | 2.44%   |
| 5.10.0-6-amd64         | 1         | 2.44%   |
| 5.10.0-3-amd64         | 1         | 2.44%   |
| 5.10.0-22-amd64        | 1         | 2.44%   |
| 5.10.0-21-686          | 1         | 2.44%   |
| 5.10.0-20-amd64        | 1         | 2.44%   |
| 5.10.0-19-amd64        | 1         | 2.44%   |
| 5.10.0-16-amd64        | 1         | 2.44%   |
| 5.10.0-14-amd64        | 1         | 2.44%   |
| 4.19.0-14-686          | 1         | 2.44%   |
| 4.19.0-10-686          | 1         | 2.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 16        | 42.11%  |
| 4.19.0  | 6         | 15.79%  |
| 5.18.0  | 2         | 5.26%   |
| 5.17.0  | 2         | 5.26%   |
| 6.3.3   | 1         | 2.63%   |
| 6.2.0   | 1         | 2.63%   |
| 5.9.0   | 1         | 2.63%   |
| 5.8.13  | 1         | 2.63%   |
| 5.8.0   | 1         | 2.63%   |
| 5.5.0   | 1         | 2.63%   |
| 5.4.7   | 1         | 2.63%   |
| 5.2.0   | 1         | 2.63%   |
| 5.16.0  | 1         | 2.63%   |
| 5.15.0  | 1         | 2.63%   |
| 5.14.0  | 1         | 2.63%   |
| 5.10.4  | 1         | 2.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 17        | 44.74%  |
| 4.19    | 6         | 15.79%  |
| 5.8     | 2         | 5.26%   |
| 5.18    | 2         | 5.26%   |
| 5.17    | 2         | 5.26%   |
| 6.3     | 1         | 2.63%   |
| 6.2     | 1         | 2.63%   |
| 5.9     | 1         | 2.63%   |
| 5.5     | 1         | 2.63%   |
| 5.4     | 1         | 2.63%   |
| 5.2     | 1         | 2.63%   |
| 5.16    | 1         | 2.63%   |
| 5.15    | 1         | 2.63%   |
| 5.14    | 1         | 2.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 31        | 88.57%  |
| i686   | 4         | 11.43%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 11        | 30.56%  |
| LXQt          | 9         | 25%     |
| Unknown       | 7         | 19.44%  |
| KDE5          | 3         | 8.33%   |
| openbox       | 2         | 5.56%   |
| MATE          | 2         | 5.56%   |
| GNOME Classic | 1         | 2.78%   |
| GNOME         | 1         | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 32        | 88.89%  |
| Tty  | 4         | 11.11%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 10        | 28.57%  |
| Unknown | 10        | 28.57%  |
| SDDM    | 7         | 20%     |
| TDM     | 6         | 17.14%  |
| XDM     | 1         | 2.86%   |
| GDM     | 1         | 2.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 12        | 34.29%  |
| pl_PL   | 3         | 8.57%   |
| en_GB   | 3         | 8.57%   |
| de_DE   | 3         | 8.57%   |
| fr_FR   | 2         | 5.71%   |
| es_ES   | 2         | 5.71%   |
| Unknown | 2         | 5.71%   |
| pt_BR   | 1         | 2.86%   |
| ja_JP   | 1         | 2.86%   |
| it_IT   | 1         | 2.86%   |
| es_MX   | 1         | 2.86%   |
| es_CL   | 1         | 2.86%   |
| en_PH   | 1         | 2.86%   |
| en_IN   | 1         | 2.86%   |
| en_CA   | 1         | 2.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 21        | 60%     |
| EFI  | 14        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 31        | 88.57%  |
| Overlay | 2         | 5.71%   |
| Ext2    | 1         | 2.86%   |
| Btrfs   | 1         | 2.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 14        | 40%     |
| MBR     | 11        | 31.43%  |
| Unknown | 10        | 28.57%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 88.57%  |
| Yes       | 4         | 11.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 65.71%  |
| Yes       | 12        | 34.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 22.86%  |
| Lenovo              | 5         | 14.29%  |
| Dell                | 4         | 11.43%  |
| ASUSTek Computer    | 4         | 11.43%  |
| Google              | 2         | 5.71%   |
| Acer                | 2         | 5.71%   |
| Samsung Electronics | 1         | 2.86%   |
| Positivo            | 1         | 2.86%   |
| Panasonic           | 1         | 2.86%   |
| MSI                 | 1         | 2.86%   |
| Mediacom            | 1         | 2.86%   |
| HUAWEI              | 1         | 2.86%   |
| Fujitsu Siemens     | 1         | 2.86%   |
| eMachines           | 1         | 2.86%   |
| Beelink             | 1         | 2.86%   |
| Apple               | 1         | 2.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NC10                            | 1         | 2.86%   |
| Positivo CHT14B                         | 1         | 2.86%   |
| Panasonic CFSZ5-2                       | 1         | 2.86%   |
| MSI Alpha 15 A3DDK                      | 1         | 2.86%   |
| Mediacom SmartBook 14 FullHD - SB14UC   | 1         | 2.86%   |
| Lenovo ThinkPad T61 7659AB7             | 1         | 2.86%   |
| Lenovo ThinkPad T60 2007FUG             | 1         | 2.86%   |
| Lenovo ThinkPad E15 20RES0GF00          | 1         | 2.86%   |
| Lenovo IdeaPad S206 20154               | 1         | 2.86%   |
| Lenovo G50-30 80G0                      | 1         | 2.86%   |
| HUAWEI HVY-WXX9                         | 1         | 2.86%   |
| HP Stream Notebook PC 13                | 1         | 2.86%   |
| HP Pavilion g7                          | 1         | 2.86%   |
| HP Pavilion dv9000 (GA359UA#ABA)        | 1         | 2.86%   |
| HP Pavilion dv5                         | 1         | 2.86%   |
| HP Laptop 17z-ca100                     | 1         | 2.86%   |
| HP EliteBook Folio 9480m                | 1         | 2.86%   |
| HP EliteBook 8770w                      | 1         | 2.86%   |
| HP EliteBook 745 G3                     | 1         | 2.86%   |
| Google Swanky                           | 1         | 2.86%   |
| Google Banon                            | 1         | 2.86%   |
| Fujitsu Siemens STYLISTIC ST5112        | 1         | 2.86%   |
| eMachines E525                          | 1         | 2.86%   |
| Dell Latitude XT3                       | 1         | 2.86%   |
| Dell Inspiron N5010                     | 1         | 2.86%   |
| Dell Inspiron 5770                      | 1         | 2.86%   |
| Dell Inspiron 5720                      | 1         | 2.86%   |
| Beelink BT3 PRO                         | 1         | 2.86%   |
| ASUS VivoBook_ASUSLaptop E410MAB_E410MA | 1         | 2.86%   |
| ASUS S101                               | 1         | 2.86%   |
| ASUS M70Vn                              | 1         | 2.86%   |
| ASUS 1000HE                             | 1         | 2.86%   |
| Apple MacBook1,1                        | 1         | 2.86%   |
| Acer Aspire E1-522                      | 1         | 2.86%   |
| Acer Aspire 5742G                       | 1         | 2.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 3         | 8.57%   |
| HP Pavilion               | 3         | 8.57%   |
| HP EliteBook              | 3         | 8.57%   |
| Dell Inspiron             | 3         | 8.57%   |
| Acer Aspire               | 2         | 5.71%   |
| Samsung NC10              | 1         | 2.86%   |
| Positivo CHT14B           | 1         | 2.86%   |
| Panasonic CFSZ5-2         | 1         | 2.86%   |
| MSI Alpha                 | 1         | 2.86%   |
| Mediacom SmartBook        | 1         | 2.86%   |
| Lenovo IdeaPad            | 1         | 2.86%   |
| Lenovo G50-30             | 1         | 2.86%   |
| HUAWEI HVY-WXX9           | 1         | 2.86%   |
| HP Stream                 | 1         | 2.86%   |
| HP Laptop                 | 1         | 2.86%   |
| Google Swanky             | 1         | 2.86%   |
| Google Banon              | 1         | 2.86%   |
| Fujitsu Siemens STYLISTIC | 1         | 2.86%   |
| eMachines E525            | 1         | 2.86%   |
| Dell Latitude             | 1         | 2.86%   |
| Beelink BT3               | 1         | 2.86%   |
| ASUS VivoBook             | 1         | 2.86%   |
| ASUS S101                 | 1         | 2.86%   |
| ASUS M70Vn                | 1         | 2.86%   |
| ASUS 1000HE               | 1         | 2.86%   |
| Apple MacBook1            | 1         | 2.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2008 | 5         | 14.29%  |
| 2014 | 3         | 8.57%   |
| 2012 | 3         | 8.57%   |
| 2009 | 3         | 8.57%   |
| 2021 | 2         | 5.71%   |
| 2020 | 2         | 5.71%   |
| 2019 | 2         | 5.71%   |
| 2018 | 2         | 5.71%   |
| 2017 | 2         | 5.71%   |
| 2016 | 2         | 5.71%   |
| 2011 | 2         | 5.71%   |
| 2010 | 2         | 5.71%   |
| 2006 | 2         | 5.71%   |
| 2022 | 1         | 2.86%   |
| 2013 | 1         | 2.86%   |
| 2007 | 1         | 2.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 35        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 35        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 94.29%  |
| Yes  | 2         | 5.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 37.14%  |
| 4.01-8.0   | 6         | 17.14%  |
| 1.01-2.0   | 6         | 17.14%  |
| 2.01-3.0   | 4         | 11.43%  |
| 8.01-16.0  | 2         | 5.71%   |
| 32.01-64.0 | 1         | 2.86%   |
| 24.01-32.0 | 1         | 2.86%   |
| 16.01-24.0 | 1         | 2.86%   |
| 0.51-1.0   | 1         | 2.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 10        | 27.03%  |
| 0.51-1.0 | 10        | 27.03%  |
| 2.01-3.0 | 8         | 21.62%  |
| 4.01-8.0 | 3         | 8.11%   |
| 3.01-4.0 | 3         | 8.11%   |
| 0.01-0.5 | 3         | 8.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 77.14%  |
| 2      | 6         | 17.14%  |
| 5      | 1         | 2.86%   |
| 4      | 1         | 2.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 62.86%  |
| Yes       | 13        | 37.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 82.86%  |
| No        | 6         | 17.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 91.43%  |
| No        | 3         | 8.57%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 65.71%  |
| No        | 12        | 34.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 9         | 25.71%  |
| Germany     | 5         | 14.29%  |
| UK          | 3         | 8.57%   |
| Poland      | 3         | 8.57%   |
| Spain       | 2         | 5.71%   |
| France      | 2         | 5.71%   |
| Canada      | 2         | 5.71%   |
| Philippines | 1         | 2.86%   |
| New Zealand | 1         | 2.86%   |
| Mexico      | 1         | 2.86%   |
| Japan       | 1         | 2.86%   |
| Italy       | 1         | 2.86%   |
| Indonesia   | 1         | 2.86%   |
| India       | 1         | 2.86%   |
| Chile       | 1         | 2.86%   |
| Brazil      | 1         | 2.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Leipzig        | 2         | 5.26%   |
| Wenatchee      | 1         | 2.63%   |
| Tucson         | 1         | 2.63%   |
| Tauranga       | 1         | 2.63%   |
| Takahama       | 1         | 2.63%   |
| Spokane        | 1         | 2.63%   |
| Santo André   | 1         | 2.63%   |
| San Antonio    | 1         | 2.63%   |
| Salina Cruz    | 1         | 2.63%   |
| Sainte-Julie   | 1         | 2.63%   |
| Quezon City    | 1         | 2.63%   |
| Pujaudran      | 1         | 2.63%   |
| Puente Alto    | 1         | 2.63%   |
| Pompano Beach  | 1         | 2.63%   |
| Munich         | 1         | 2.63%   |
| Montreuil      | 1         | 2.63%   |
| Montreal       | 1         | 2.63%   |
| Milano         | 1         | 2.63%   |
| Miekoszyn      | 1         | 2.63%   |
| Mannheim       | 1         | 2.63%   |
| Madrid         | 1         | 2.63%   |
| Liverpool      | 1         | 2.63%   |
| Koło          | 1         | 2.63%   |
| Jakarta        | 1         | 2.63%   |
| Houston        | 1         | 2.63%   |
| Hamburg        | 1         | 2.63%   |
| Gmina Bolków  | 1         | 2.63%   |
| Glasgow        | 1         | 2.63%   |
| Framingham     | 1         | 2.63%   |
| East Wenatchee | 1         | 2.63%   |
| Dunoon         | 1         | 2.63%   |
| Dobrzen Wielki | 1         | 2.63%   |
| Dehradun       | 1         | 2.63%   |
| Chicago        | 1         | 2.63%   |
| Birmingham     | 1         | 2.63%   |
| Barnsley       | 1         | 2.63%   |
| Amorebieta     | 1         | 2.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 13     | 17.78%  |
| WDC                 | 6         | 8      | 13.33%  |
| Unknown             | 6         | 6      | 13.33%  |
| Samsung Electronics | 5         | 5      | 11.11%  |
| Hitachi             | 4         | 7      | 8.89%   |
| Intel               | 2         | 2      | 4.44%   |
| Goodram             | 2         | 4      | 4.44%   |
| SPCC                | 1         | 2      | 2.22%   |
| Silicon Motion      | 1         | 1      | 2.22%   |
| ORICO               | 1         | 1      | 2.22%   |
| Netac               | 1         | 1      | 2.22%   |
| Micron Technology   | 1         | 1      | 2.22%   |
| HGST                | 1         | 1      | 2.22%   |
| Fujitsu             | 1         | 2      | 2.22%   |
| Crucial             | 1         | 1      | 2.22%   |
| ASUS-JM             | 1         | 1      | 2.22%   |
| ASMedia             | 1         | 1      | 2.22%   |
| A-DATA Technology   | 1         | 1      | 2.22%   |
| Unknown             | 1         | 1      | 2.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                   | 2         | 4.26%   |
| Seagate Backup+ Hub BK 6TB               | 2         | 4.26%   |
| Hitachi HTS545025B9A300 250GB            | 2         | 4.26%   |
| WDC WD7500BPVX-22JC3T0 752GB             | 1         | 2.13%   |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 2.13%   |
| WDC WD50 00LPCX-21VHAT0 500GB            | 1         | 2.13%   |
| WDC WD3200BPVT-75ZEST0 320GB             | 1         | 2.13%   |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 2.13%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB     | 1         | 2.13%   |
| Unknown NCard  32GB                      | 1         | 2.13%   |
| Unknown MMC Card  64GB                   | 1         | 2.13%   |
| Unknown HBG4a2  32GB                     | 1         | 2.13%   |
| Unknown 016GE2  16GB                     | 1         | 2.13%   |
| SPCC Solid State Disk 256GB              | 1         | 2.13%   |
| Silicon Motion PCIe-8 SSD 512GB          | 1         | 2.13%   |
| Seagate ST9500325AS 500GB                | 1         | 2.13%   |
| Seagate ST9250320AS 250GB                | 1         | 2.13%   |
| Seagate ST9160310AS 160GB                | 1         | 2.13%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 2.13%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 2.13%   |
| Seagate Backup+ Desk 8TB                 | 1         | 2.13%   |
| Samsung SSD 840 Series 120GB             | 1         | 2.13%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 2.13%   |
| Samsung MZVLB512HAJQ-00000 512GB         | 1         | 2.13%   |
| Samsung MZALQ512HALU-000L1 512GB         | 1         | 2.13%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD     | 1         | 2.13%   |
| ORICO M200 1TB SSD                       | 1         | 2.13%   |
| Netac SSD 256GB                          | 1         | 2.13%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 2.13%   |
| Intel SSDSC2CW060A3 64GB                 | 1         | 2.13%   |
| Intel SSDMAEXC024G3H 24GB                | 1         | 2.13%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 2.13%   |
| Hitachi HTS541080G9SA00 80GB             | 1         | 2.13%   |
| HGST HTS545032A7E680 320GB               | 1         | 2.13%   |
| GOODRAM SSDPR-CX400-256-G2 256GB         | 1         | 2.13%   |
| GOODRAM SSDPR-CL100-240-G3 240GB         | 1         | 2.13%   |
| Goodram IR-SSDPR-S25A-120 120GB          | 1         | 2.13%   |
| Fujitsu MHW2120BH 120GB                  | 1         | 2.13%   |
| Crucial CT250MX500SSD1 250GB             | 1         | 2.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 12     | 40%     |
| WDC     | 5         | 7      | 25%     |
| Hitachi | 4         | 7      | 20%     |
| HGST    | 1         | 1      | 5%      |
| Fujitsu | 1         | 2      | 5%      |
| ASMedia | 1         | 1      | 5%      |

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
| HDD     | 18        | 30     | 42.86%  |
| SSD     | 10        | 15     | 23.81%  |
| MMC     | 7         | 7      | 16.67%  |
| NVMe    | 6         | 6      | 14.29%  |
| Unknown | 1         | 1      | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 24        | 39     | 58.54%  |
| MMC  | 7         | 7      | 17.07%  |
| NVMe | 6         | 6      | 14.63%  |
| SAS  | 4         | 7      | 9.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 34     | 71.43%  |
| 0.51-1.0   | 5         | 6      | 17.86%  |
| 4.01-10.0  | 2         | 4      | 7.14%   |
| 2.01-3.0   | 1         | 1      | 3.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 11        | 31.43%  |
| 21-50          | 6         | 17.14%  |
| 501-1000       | 6         | 17.14%  |
| 1-20           | 5         | 14.29%  |
| 251-500        | 3         | 8.57%   |
| More than 3000 | 2         | 5.71%   |
| 1001-2000      | 1         | 2.86%   |
| Unknown        | 1         | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 17        | 45.95%  |
| 21-50          | 5         | 13.51%  |
| 251-500        | 3         | 8.11%   |
| 101-250        | 3         | 8.11%   |
| 501-1000       | 3         | 8.11%   |
| 51-100         | 3         | 8.11%   |
| More than 3000 | 1         | 2.7%    |
| 1001-2000      | 1         | 2.7%    |
| Unknown        | 1         | 2.7%    |

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
| ASMedia ASMT1153E 3TB                               | 1         | 1      | 16.67%  |

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
| Detected | 17        | 27     | 43.59%  |
| Works    | 16        | 26     | 41.03%  |
| Malfunc  | 6         | 6      | 15.38%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 22        | 68.75%  |
| Samsung Electronics | 3         | 9.38%   |
| AMD                 | 3         | 9.38%   |
| Silicon Motion      | 2         | 6.25%   |
| Nvidia              | 1         | 3.13%   |
| JMicron Technology  | 1         | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 3         | 8.11%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 3         | 8.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 3         | 8.11%   |
| Samsung NVMe SSD Controller 980                                              | 2         | 5.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 5.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 5.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 2         | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 5.41%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 2         | 5.41%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 2.7%    |
| Silicon Motion Non-Volatile memory controller                                | 1         | 2.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 2.7%    |
| Nvidia MCP51 Serial ATA Controller                                           | 1         | 2.7%    |
| Nvidia MCP51 IDE                                                             | 1         | 2.7%    |
| JMicron JMB360 AHCI Controller                                               | 1         | 2.7%    |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 2.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 2.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 2.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 1         | 2.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 2.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 21        | 60%     |
| IDE  | 9         | 25.71%  |
| NVMe | 5         | 14.29%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 80%     |
| AMD    | 7         | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 8.57%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 2         | 5.71%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 5.71%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 5.71%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 2.86%   |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 2.86%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 2.86%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2.86%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 2.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.86%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.86%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.86%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.86%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 2.86%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 2.86%   |
| Intel Core 2 CPU U7600 @ 1.20GHz              | 1         | 2.86%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 2.86%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.86%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 2.86%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 1         | 2.86%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 1         | 2.86%   |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 2.86%   |
| AMD Turion 64 X2 Mobile Technology TL-64      | 1         | 2.86%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 2.86%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2.86%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.86%   |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G  | 1         | 2.86%   |
| AMD C-50 Processor                            | 1         | 2.86%   |
| AMD A4-5000 APU with Radeon HD Graphics       | 1         | 2.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 6         | 17.14%  |
| Intel Atom              | 6         | 17.14%  |
| Intel Core i5           | 5         | 14.29%  |
| Intel Core i7           | 3         | 8.57%   |
| Intel Core 2 Duo        | 3         | 8.57%   |
| Intel Core 2            | 2         | 5.71%   |
| AMD Ryzen 5             | 2         | 5.71%   |
| Intel Pentium           | 1         | 2.86%   |
| Intel Genuine           | 1         | 2.86%   |
| Intel Core i3           | 1         | 2.86%   |
| AMD Turion 64 X2 Mobile | 1         | 2.86%   |
| AMD Ryzen 7             | 1         | 2.86%   |
| AMD PRO A10             | 1         | 2.86%   |
| AMD C-50                | 1         | 2.86%   |
| AMD A4                  | 1         | 2.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 19        | 54.29%  |
| 4      | 11        | 31.43%  |
| 1      | 4         | 11.43%  |
| 6      | 1         | 2.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 35        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 54.29%  |
| 2      | 16        | 45.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 31        | 88.57%  |
| 32-bit         | 4         | 11.43%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 5         | 14.29%  |
| 0x406c4    | 3         | 8.57%   |
| 0x30678    | 3         | 8.57%   |
| 0x6f2      | 2         | 5.71%   |
| 0x306a9    | 2         | 5.71%   |
| 0x206a7    | 2         | 5.71%   |
| 0x20655    | 2         | 5.71%   |
| 0x106c2    | 2         | 5.71%   |
| 0x10676    | 2         | 5.71%   |
| 0x08108109 | 2         | 5.71%   |
| 0x806ec    | 1         | 2.86%   |
| 0x806ea    | 1         | 2.86%   |
| 0x706a8    | 1         | 2.86%   |
| 0x406c3    | 1         | 2.86%   |
| 0x40651    | 1         | 2.86%   |
| 0x1067a    | 1         | 2.86%   |
| 0x08600106 | 1         | 2.86%   |
| 0x0700010f | 1         | 2.86%   |
| 0x0600611a | 1         | 2.86%   |
| 0x05000029 | 1         | 2.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 7         | 20%     |
| Penryn        | 3         | 8.57%   |
| Core          | 3         | 8.57%   |
| Bonnell       | 3         | 8.57%   |
| Zen+          | 2         | 5.71%   |
| Westmere      | 2         | 5.71%   |
| SandyBridge   | 2         | 5.71%   |
| KabyLake      | 2         | 5.71%   |
| IvyBridge     | 2         | 5.71%   |
| Zen 2         | 1         | 2.86%   |
| Skylake       | 1         | 2.86%   |
| P6            | 1         | 2.86%   |
| K8 Hammer     | 1         | 2.86%   |
| Jaguar        | 1         | 2.86%   |
| Haswell       | 1         | 2.86%   |
| Goldmont plus | 1         | 2.86%   |
| Excavator     | 1         | 2.86%   |
| Bobcat        | 1         | 2.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 65.71%  |
| AMD    | 7         | 20%     |
| Nvidia | 5         | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 11.9%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 9.52%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 7.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 7.14%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 4.76%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 2.38%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 2.38%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 2.38%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 2.38%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 2.38%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.38%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.38%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.38%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.38%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 2.38%   |
| AMD Renoir                                                                               | 1         | 2.38%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 2.38%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| 1 x Intel  | 23        | 65.71%  |
| 1 x AMD    | 6         | 17.14%  |
| 1 x Nvidia | 5         | 14.29%  |
| 2 x AMD    | 1         | 2.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 34        | 97.14%  |
| Proprietary | 1         | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 71.43%  |
| 0.01-0.5   | 6         | 17.14%  |
| 1.01-2.0   | 3         | 8.57%   |
| 0.51-1.0   | 1         | 2.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 7         | 20.59%  |
| AU Optronics        | 6         | 17.65%  |
| BOE                 | 5         | 14.71%  |
| CPT                 | 3         | 8.82%   |
| Chimei Innolux      | 3         | 8.82%   |
| Samsung Electronics | 2         | 5.88%   |
| Lenovo              | 2         | 5.88%   |
| Medion              | 1         | 2.94%   |
| LG Philips          | 1         | 2.94%   |
| Insignia            | 1         | 2.94%   |
| Hitachi             | 1         | 2.94%   |
| HannStar            | 1         | 2.94%   |
| Apple               | 1         | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch    | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 1         | 2.86%   |
| Medion MD 20310 MED3645 1920x1080 521x293mm 23.5-inch                | 1         | 2.86%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 2.86%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 2.86%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 2.86%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch          | 1         | 2.86%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch          | 1         | 2.86%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 2.86%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 2.86%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 2.86%   |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch              | 1         | 2.86%   |
| Lenovo LCD Monitor LEN4022 1400x1050 286x214mm 14.1-inch             | 1         | 2.86%   |
| Insignia NS32DD200NA14 BBY0032 1680x1050 700x390mm 31.5-inch         | 1         | 2.86%   |
| Hitachi HDMI HEC0088 1920x540                                        | 1         | 2.86%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch             | 1         | 2.86%   |
| CPT LCD Monitor CPT37D5 1920x1200 260x160mm 12.0-inch                | 1         | 2.86%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 2.86%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch     | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch      | 1         | 2.86%   |
| BOE LCD Monitor BOE08B2 1366x768 309x174mm 14.0-inch                 | 1         | 2.86%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                | 1         | 2.86%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 1         | 2.86%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 1         | 2.86%   |
| BOE LCD Monitor BOE0635 1920x1080 309x173mm 13.9-inch                | 1         | 2.86%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch        | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO132C 1366x768 293x164mm 13.2-inch        | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch       | 1         | 2.86%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 11        | 31.43%  |
| 1366x768 (WXGA)   | 10        | 28.57%  |
| 1600x900 (HD+)    | 3         | 8.57%   |
| 1024x600          | 3         | 8.57%   |
| 1920x540          | 2         | 5.71%   |
| 1440x900 (WXGA+)  | 2         | 5.71%   |
| 1280x800 (WXGA)   | 2         | 5.71%   |
| 1920x1200 (WUXGA) | 1         | 2.86%   |
| 1400x1050         | 1         | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 9         | 25.71%  |
| 13     | 7         | 20%     |
| 17     | 6         | 17.14%  |
| 14     | 4         | 11.43%  |
| 10     | 3         | 8.57%   |
| 48     | 2         | 5.71%   |
| 24     | 1         | 2.86%   |
| 23     | 1         | 2.86%   |
| 16     | 1         | 2.86%   |
| 12     | 1         | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 42.86%  |
| 201-300     | 9         | 25.71%  |
| 351-400     | 7         | 20%     |
| 501-600     | 2         | 5.71%   |
| 1001-1500   | 2         | 5.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 77.14%  |
| 16/10 | 5         | 14.29%  |
| 1.96  | 2         | 5.71%   |
| 4/3   | 1         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 28.57%  |
| 81-90          | 6         | 17.14%  |
| 121-130        | 5         | 14.29%  |
| 71-80          | 4         | 11.43%  |
| 41-50          | 3         | 8.57%   |
| 201-250        | 2         | 5.71%   |
| 501-1000       | 2         | 5.71%   |
| 61-70          | 1         | 2.86%   |
| 131-140        | 1         | 2.86%   |
| 91-100         | 1         | 2.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 15        | 44.12%  |
| 121-160 | 12        | 35.29%  |
| 51-100  | 4         | 11.76%  |
| 1-50    | 2         | 5.88%   |
| 161-240 | 1         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 33        | 94.29%  |
| 2     | 1         | 2.86%   |
| 0     | 1         | 2.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 15        | 29.41%  |
| Realtek Semiconductor    | 14        | 27.45%  |
| Qualcomm Atheros         | 8         | 15.69%  |
| Marvell Technology Group | 3         | 5.88%   |
| Broadcom                 | 3         | 5.88%   |
| Broadcom Limited         | 2         | 3.92%   |
| TP-Link                  | 1         | 1.96%   |
| Samsung Electronics      | 1         | 1.96%   |
| Ralink                   | 1         | 1.96%   |
| OPPO Electronics         | 1         | 1.96%   |
| Nvidia                   | 1         | 1.96%   |
| Edimax Technology        | 1         | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 6         | 9.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 6.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 3.17%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 3.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.17%   |
| Intel Wireless 7265                                                     | 2         | 3.17%   |
| Intel Wireless 7260                                                     | 2         | 3.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 3.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 3.17%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 1.59%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.59%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 1.59%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 1.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 1.59%   |
| OPPO CPH2411                                                            | 1         | 1.59%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 1.59%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 1.59%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 1.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 1.59%   |
| Intel Wireless 8260                                                     | 1         | 1.59%   |
| Intel WiFi Link 5100                                                    | 1         | 1.59%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.59%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 1.59%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.59%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.59%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.59%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.59%   |
| Intel 82573L Gigabit Ethernet Controller                                | 1         | 1.59%   |
| Intel 82566MM Gigabit Network Connection                                | 1         | 1.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 44.12%  |
| Qualcomm Atheros      | 7         | 20.59%  |
| Realtek Semiconductor | 6         | 17.65%  |
| Broadcom Limited      | 2         | 5.88%   |
| TP-Link               | 1         | 2.94%   |
| Ralink                | 1         | 2.94%   |
| Edimax Technology     | 1         | 2.94%   |
| Broadcom              | 1         | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 5.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 5.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 5.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 5.88%   |
| Intel Wireless 7265                                                     | 2         | 5.88%   |
| Intel Wireless 7260                                                     | 2         | 5.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 5.88%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 2.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 2.94%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 2.94%   |
| Intel Wireless 8260                                                     | 1         | 2.94%   |
| Intel WiFi Link 5100                                                    | 1         | 2.94%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 2.94%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 2.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 2.94%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 2.94%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.94%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.94%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 2.94%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 2.94%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2.94%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 11        | 37.93%  |
| Intel                    | 6         | 20.69%  |
| Qualcomm Atheros         | 4         | 13.79%  |
| Marvell Technology Group | 3         | 10.34%  |
| Broadcom                 | 2         | 6.9%    |
| Samsung Electronics      | 1         | 3.45%   |
| OPPO Electronics         | 1         | 3.45%   |
| Nvidia                   | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 20.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 13.79%  |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 6.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 6.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 3.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 3.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 3.45%   |
| OPPO CPH2411                                                      | 1         | 3.45%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 3.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 3.45%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 3.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 3.45%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.45%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 3.45%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 3.45%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 3.45%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 3.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 52.46%  |
| Ethernet | 29        | 47.54%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 69.44%  |
| Ethernet | 11        | 30.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 24        | 68.57%  |
| 1     | 8         | 22.86%  |
| 0     | 2         | 5.71%   |
| 3     | 1         | 2.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 28        | 75.68%  |
| Yes  | 9         | 24.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 30.43%  |
| Broadcom                        | 4         | 17.39%  |
| Realtek Semiconductor           | 2         | 8.7%    |
| IMC Networks                    | 2         | 8.7%    |
| Taiyo Yuden                     | 1         | 4.35%   |
| Realtek                         | 1         | 4.35%   |
| Qualcomm Atheros Communications | 1         | 4.35%   |
| Foxconn / Hon Hai               | 1         | 4.35%   |
| Dell                            | 1         | 4.35%   |
| Cambridge Silicon Radio         | 1         | 4.35%   |
| ASUSTek Computer                | 1         | 4.35%   |
| Apple                           | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 21.74%  |
| IMC Networks Bluetooth Radio                        | 2         | 8.7%    |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 4.35%   |
| Realtek RTL8723B Bluetooth                          | 1         | 4.35%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 4.35%   |
| Realtek Bluetooth Radio                             | 1         | 4.35%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 4.35%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4.35%   |
| Intel AX201 Bluetooth                               | 1         | 4.35%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 4.35%   |
| Dell Wireless 365 Bluetooth                         | 1         | 4.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.35%   |
| Broadcom HP Portable SoftSailing                    | 1         | 4.35%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 4.35%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 4.35%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 4.35%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 4.35%   |
| Apple Bluetooth HCI                                 | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 25        | 65.79%  |
| AMD                 | 6         | 15.79%  |
| Nvidia              | 3         | 7.89%   |
| Native Instruments  | 1         | 2.63%   |
| Focusrite-Novation  | 1         | 2.63%   |
| C-Media Electronics | 1         | 2.63%   |
| ASUSTek Computer    | 1         | 2.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 13.64%  |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 6.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 6.82%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 4.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 4.55%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 4.55%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 4.55%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 2.27%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 2.27%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.27%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 2.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.27%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.27%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 2.27%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 2.27%   |
| ASUSTek Computer C-Media Audio                                                                    | 1         | 2.27%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.27%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 2.27%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.27%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 32.14%  |
| Unknown             | 6         | 21.43%  |
| SK hynix            | 3         | 10.71%  |
| Micron Technology   | 3         | 10.71%  |
| Nanya Technology    | 2         | 7.14%   |
| Kingston            | 2         | 7.14%   |
| GOODRAM             | 1         | 3.57%   |
| G.Skill             | 1         | 3.57%   |
| Corsair             | 1         | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                | 2         | 6.45%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s      | 2         | 6.45%   |
| Unknown RAM Module 2GB SODIMM SDRAM                        | 1         | 3.23%   |
| Unknown RAM Module 2GB SODIMM DDR2 266MT/s                 | 1         | 3.23%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                   | 1         | 3.23%   |
| Unknown RAM Module 1024MB SODIMM DDR2                      | 1         | 3.23%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                   | 1         | 3.23%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s               | 1         | 3.23%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1         | 3.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 3.23%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 3.23%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 1         | 3.23%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 1         | 3.23%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s   | 1         | 3.23%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s      | 1         | 3.23%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1         | 3.23%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 3.23%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s            | 1         | 3.23%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s       | 1         | 3.23%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 3.23%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s | 1         | 3.23%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 3.23%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s  | 1         | 3.23%   |
| Kingston RAM Module 4GB SODIMM DDR3 800MT/s                | 1         | 3.23%   |
| Kingston RAM ACR16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s     | 1         | 3.23%   |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s   | 1         | 3.23%   |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s     | 1         | 3.23%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s     | 1         | 3.23%   |
| Corsair RAM CMSA4GX3M1A1333C9 4GB SODIMM DDR3 1333MT/s     | 1         | 3.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 15        | 57.69%  |
| DDR4    | 5         | 19.23%  |
| SDRAM   | 2         | 7.69%   |
| DDR2    | 2         | 7.69%   |
| LPDDR3  | 1         | 3.85%   |
| Unknown | 1         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 92%     |
| Row Of Chips | 1         | 4%      |
| Unknown      | 1         | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 10        | 33.33%  |
| 4096  | 9         | 30%     |
| 8192  | 5         | 16.67%  |
| 16384 | 3         | 10%     |
| 1024  | 3         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 9         | 32.14%  |
| 2667    | 3         | 10.71%  |
| 1066    | 3         | 10.71%  |
| 3200    | 2         | 7.14%   |
| 1334    | 2         | 7.14%   |
| 1333    | 2         | 7.14%   |
| 800     | 2         | 7.14%   |
| Unknown | 2         | 7.14%   |
| 4199    | 1         | 3.57%   |
| 1867    | 1         | 3.57%   |
| 266     | 1         | 3.57%   |

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
| Chicony Electronics                    | 9         | 31.03%  |
| Microdia                               | 4         | 13.79%  |
| Suyin                                  | 3         | 10.34%  |
| Sunplus Innovation Technology          | 2         | 6.9%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.9%    |
| Bison Electronics                      | 2         | 6.9%    |
| Alcor Micro                            | 2         | 6.9%    |
| Acer                                   | 2         | 6.9%    |
| Z-Star Microelectronics                | 1         | 3.45%   |
| Sonix Technology                       | 1         | 3.45%   |
| Microsoft                              | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                           | 2         | 6.9%    |
| Alcor Micro USB 2.0 Camera                                  | 2         | 6.9%    |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 3.45%   |
| Suyin USB2.0 UVC 1.3M WebCam                                | 1         | 3.45%   |
| Suyin HP Truevision HD                                      | 1         | 3.45%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 3.45%   |
| Sunplus Integrated Webcam                                   | 1         | 3.45%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 3.45%   |
| Sonix USB2.0 HD UVC WebCam                                  | 1         | 3.45%   |
| Microsoft LifeCam Cinema                                    | 1         | 3.45%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 3.45%   |
| Microdia Lenovo EasyCamera                                  | 1         | 3.45%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 3.45%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 3.45%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 3.45%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 3.45%   |
| Chicony HP TrueVision HD Camera                             | 1         | 3.45%   |
| Chicony HP Integrated Webcam                                | 1         | 3.45%   |
| Chicony HP HD Webcam                                        | 1         | 3.45%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 3.45%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera            | 1         | 3.45%   |
| Bison USB HD Webcam                                         | 1         | 3.45%   |
| Bison HP Webcam                                             | 1         | 3.45%   |
| Acer Lenovo EasyCamera                                      | 1         | 3.45%   |
| Acer HD Webcam                                              | 1         | 3.45%   |

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
| 0     | 21        | 60%     |
| 1     | 11        | 31.43%  |
| 2     | 3         | 8.57%   |

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

