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

Total: 43

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Sparky 6    | 8         | 22.86%  |
| Sparky 7    | 6         | 17.14%  |
| Sparky 6.5  | 4         | 11.43%  |
| Sparky 6.1  | 4         | 11.43%  |
| Sparky 5.14 | 3         | 8.57%   |
| Sparky 6.0  | 2         | 5.71%   |
| Sparky 5.13 | 2         | 5.71%   |
| Sparky 5.12 | 2         | 5.71%   |
| Sparky 5.10 | 2         | 5.71%   |
| Sparky 6.6  | 1         | 2.86%   |
| Sparky 6.3  | 1         | 2.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Sparky | 32        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.10.0-11-686       | 3         | 8.11%   |
| 5.17.0-1-amd64      | 2         | 5.41%   |
| 5.10.0-9-amd64      | 2         | 5.41%   |
| 5.10.0-8-amd64      | 2         | 5.41%   |
| 5.10.0-21-amd64     | 2         | 5.41%   |
| 4.19.0-8-amd64      | 2         | 5.41%   |
| 4.19.0-13-686       | 2         | 5.41%   |
| 4.19.0-12-amd64     | 2         | 5.41%   |
| 6.2.0-sparky-amd64  | 1         | 2.7%    |
| 5.9.0-4-amd64       | 1         | 2.7%    |
| 5.8.13-sparky-amd64 | 1         | 2.7%    |
| 5.8.0-2-amd64       | 1         | 2.7%    |
| 5.5.0-2-amd64       | 1         | 2.7%    |
| 5.4.7-sparky-amd64  | 1         | 2.7%    |
| 5.2.0-2-amd64       | 1         | 2.7%    |
| 5.18.0-4-amd64      | 1         | 2.7%    |
| 5.18.0-2-amd64      | 1         | 2.7%    |
| 5.16.0-5-amd64      | 1         | 2.7%    |
| 5.15.0-3-amd64      | 1         | 2.7%    |
| 5.14.0-4-amd64      | 1         | 2.7%    |
| 5.10.4-sparky-amd64 | 1         | 2.7%    |
| 5.10.0-6-amd64      | 1         | 2.7%    |
| 5.10.0-3-amd64      | 1         | 2.7%    |
| 5.10.0-20-amd64     | 1         | 2.7%    |
| 5.10.0-19-amd64     | 1         | 2.7%    |
| 5.10.0-14-amd64     | 1         | 2.7%    |
| 4.19.0-14-686       | 1         | 2.7%    |
| 4.19.0-10-686       | 1         | 2.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 14        | 40%     |
| 4.19.0  | 6         | 17.14%  |
| 5.18.0  | 2         | 5.71%   |
| 5.17.0  | 2         | 5.71%   |
| 6.2.0   | 1         | 2.86%   |
| 5.9.0   | 1         | 2.86%   |
| 5.8.13  | 1         | 2.86%   |
| 5.8.0   | 1         | 2.86%   |
| 5.5.0   | 1         | 2.86%   |
| 5.4.7   | 1         | 2.86%   |
| 5.2.0   | 1         | 2.86%   |
| 5.16.0  | 1         | 2.86%   |
| 5.15.0  | 1         | 2.86%   |
| 5.14.0  | 1         | 2.86%   |
| 5.10.4  | 1         | 2.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 15        | 42.86%  |
| 4.19    | 6         | 17.14%  |
| 5.8     | 2         | 5.71%   |
| 5.18    | 2         | 5.71%   |
| 5.17    | 2         | 5.71%   |
| 6.2     | 1         | 2.86%   |
| 5.9     | 1         | 2.86%   |
| 5.5     | 1         | 2.86%   |
| 5.4     | 1         | 2.86%   |
| 5.2     | 1         | 2.86%   |
| 5.16    | 1         | 2.86%   |
| 5.15    | 1         | 2.86%   |
| 5.14    | 1         | 2.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 28        | 87.5%   |
| i686   | 4         | 12.5%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 9         | 27.27%  |
| LXQt          | 8         | 24.24%  |
| Unknown       | 7         | 21.21%  |
| KDE5          | 3         | 9.09%   |
| openbox       | 2         | 6.06%   |
| MATE          | 2         | 6.06%   |
| GNOME Classic | 1         | 3.03%   |
| GNOME         | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 29        | 87.88%  |
| Tty  | 4         | 12.12%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 9         | 28.13%  |
| Unknown | 9         | 28.13%  |
| TDM     | 6         | 18.75%  |
| SDDM    | 6         | 18.75%  |
| XDM     | 1         | 3.13%   |
| GDM     | 1         | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 10        | 31.25%  |
| pl_PL   | 3         | 9.38%   |
| en_GB   | 3         | 9.38%   |
| de_DE   | 3         | 9.38%   |
| fr_FR   | 2         | 6.25%   |
| es_ES   | 2         | 6.25%   |
| Unknown | 2         | 6.25%   |
| pt_BR   | 1         | 3.13%   |
| ja_JP   | 1         | 3.13%   |
| es_MX   | 1         | 3.13%   |
| es_CL   | 1         | 3.13%   |
| en_PH   | 1         | 3.13%   |
| en_IN   | 1         | 3.13%   |
| en_CA   | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 20        | 62.5%   |
| EFI  | 12        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 28        | 87.5%   |
| Overlay | 2         | 6.25%   |
| Ext2    | 1         | 3.13%   |
| Btrfs   | 1         | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 12        | 37.5%   |
| MBR     | 11        | 34.38%  |
| Unknown | 9         | 28.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 87.5%   |
| Yes       | 4         | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 65.63%  |
| Yes       | 11        | 34.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 25%     |
| Lenovo              | 5         | 15.63%  |
| Dell                | 4         | 12.5%   |
| ASUSTek Computer    | 3         | 9.38%   |
| Google              | 2         | 6.25%   |
| Acer                | 2         | 6.25%   |
| Samsung Electronics | 1         | 3.13%   |
| Positivo            | 1         | 3.13%   |
| MSI                 | 1         | 3.13%   |
| HUAWEI              | 1         | 3.13%   |
| Fujitsu Siemens     | 1         | 3.13%   |
| eMachines           | 1         | 3.13%   |
| Beelink             | 1         | 3.13%   |
| Apple               | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Samsung NC10                     | 1         | 3.13%   |
| Positivo CHT14B                  | 1         | 3.13%   |
| MSI Alpha 15 A3DDK               | 1         | 3.13%   |
| Lenovo ThinkPad T61 7659AB7      | 1         | 3.13%   |
| Lenovo ThinkPad T60 2007FUG      | 1         | 3.13%   |
| Lenovo ThinkPad E15 20RES0GF00   | 1         | 3.13%   |
| Lenovo IdeaPad S206 20154        | 1         | 3.13%   |
| Lenovo G50-30 80G0               | 1         | 3.13%   |
| HUAWEI HVY-WXX9                  | 1         | 3.13%   |
| HP Stream Notebook PC 13         | 1         | 3.13%   |
| HP Pavilion g7                   | 1         | 3.13%   |
| HP Pavilion dv9000 (GA359UA#ABA) | 1         | 3.13%   |
| HP Pavilion dv5                  | 1         | 3.13%   |
| HP Laptop 17z-ca100              | 1         | 3.13%   |
| HP EliteBook Folio 9480m         | 1         | 3.13%   |
| HP EliteBook 8770w               | 1         | 3.13%   |
| HP EliteBook 745 G3              | 1         | 3.13%   |
| Google Swanky                    | 1         | 3.13%   |
| Google Banon                     | 1         | 3.13%   |
| Fujitsu Siemens STYLISTIC ST5112 | 1         | 3.13%   |
| eMachines E525                   | 1         | 3.13%   |
| Dell Latitude XT3                | 1         | 3.13%   |
| Dell Inspiron N5010              | 1         | 3.13%   |
| Dell Inspiron 5770               | 1         | 3.13%   |
| Dell Inspiron 5720               | 1         | 3.13%   |
| Beelink BT3 PRO                  | 1         | 3.13%   |
| ASUS S101                        | 1         | 3.13%   |
| ASUS M70Vn                       | 1         | 3.13%   |
| ASUS 1000HE                      | 1         | 3.13%   |
| Apple MacBook1,1                 | 1         | 3.13%   |
| Acer Aspire E1-522               | 1         | 3.13%   |
| Acer Aspire 5742G                | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 3         | 9.38%   |
| HP Pavilion               | 3         | 9.38%   |
| HP EliteBook              | 3         | 9.38%   |
| Dell Inspiron             | 3         | 9.38%   |
| Acer Aspire               | 2         | 6.25%   |
| Samsung NC10              | 1         | 3.13%   |
| Positivo CHT14B           | 1         | 3.13%   |
| MSI Alpha                 | 1         | 3.13%   |
| Lenovo IdeaPad            | 1         | 3.13%   |
| Lenovo G50-30             | 1         | 3.13%   |
| HUAWEI HVY-WXX9           | 1         | 3.13%   |
| HP Stream                 | 1         | 3.13%   |
| HP Laptop                 | 1         | 3.13%   |
| Google Swanky             | 1         | 3.13%   |
| Google Banon              | 1         | 3.13%   |
| Fujitsu Siemens STYLISTIC | 1         | 3.13%   |
| eMachines E525            | 1         | 3.13%   |
| Dell Latitude             | 1         | 3.13%   |
| Beelink BT3               | 1         | 3.13%   |
| ASUS S101                 | 1         | 3.13%   |
| ASUS M70Vn                | 1         | 3.13%   |
| ASUS 1000HE               | 1         | 3.13%   |
| Apple MacBook1            | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2008 | 5         | 15.63%  |
| 2014 | 3         | 9.38%   |
| 2012 | 3         | 9.38%   |
| 2009 | 3         | 9.38%   |
| 2020 | 2         | 6.25%   |
| 2019 | 2         | 6.25%   |
| 2017 | 2         | 6.25%   |
| 2011 | 2         | 6.25%   |
| 2010 | 2         | 6.25%   |
| 2006 | 2         | 6.25%   |
| 2022 | 1         | 3.13%   |
| 2021 | 1         | 3.13%   |
| 2018 | 1         | 3.13%   |
| 2016 | 1         | 3.13%   |
| 2013 | 1         | 3.13%   |
| 2007 | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 32        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 32        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 93.75%  |
| Yes  | 2         | 6.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 11        | 34.38%  |
| 4.01-8.0   | 6         | 18.75%  |
| 1.01-2.0   | 5         | 15.63%  |
| 2.01-3.0   | 4         | 12.5%   |
| 8.01-16.0  | 2         | 6.25%   |
| 32.01-64.0 | 1         | 3.13%   |
| 24.01-32.0 | 1         | 3.13%   |
| 16.01-24.0 | 1         | 3.13%   |
| 0.51-1.0   | 1         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 10        | 29.41%  |
| 1.01-2.0 | 8         | 23.53%  |
| 2.01-3.0 | 7         | 20.59%  |
| 4.01-8.0 | 3         | 8.82%   |
| 3.01-4.0 | 3         | 8.82%   |
| 0.01-0.5 | 3         | 8.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 78.13%  |
| 2      | 5         | 15.63%  |
| 5      | 1         | 3.13%   |
| 4      | 1         | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 59.38%  |
| Yes       | 13        | 40.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 84.38%  |
| No        | 5         | 15.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 93.75%  |
| No        | 2         | 6.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 65.63%  |
| No        | 11        | 34.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 25%     |
| Germany     | 5         | 15.63%  |
| UK          | 3         | 9.38%   |
| Poland      | 3         | 9.38%   |
| Spain       | 2         | 6.25%   |
| France      | 2         | 6.25%   |
| Canada      | 2         | 6.25%   |
| Philippines | 1         | 3.13%   |
| New Zealand | 1         | 3.13%   |
| Mexico      | 1         | 3.13%   |
| Japan       | 1         | 3.13%   |
| India       | 1         | 3.13%   |
| Chile       | 1         | 3.13%   |
| Brazil      | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Leipzig        | 2         | 5.71%   |
| Wenatchee      | 1         | 2.86%   |
| Tucson         | 1         | 2.86%   |
| Tauranga       | 1         | 2.86%   |
| Takahama       | 1         | 2.86%   |
| Spokane        | 1         | 2.86%   |
| Santo André   | 1         | 2.86%   |
| San Antonio    | 1         | 2.86%   |
| Salina Cruz    | 1         | 2.86%   |
| Sainte-Julie   | 1         | 2.86%   |
| Quezon City    | 1         | 2.86%   |
| Pujaudran      | 1         | 2.86%   |
| Puente Alto    | 1         | 2.86%   |
| Pompano Beach  | 1         | 2.86%   |
| Munich         | 1         | 2.86%   |
| Montreuil      | 1         | 2.86%   |
| Montreal       | 1         | 2.86%   |
| Miekoszyn      | 1         | 2.86%   |
| Mannheim       | 1         | 2.86%   |
| Madrid         | 1         | 2.86%   |
| Liverpool      | 1         | 2.86%   |
| Koło          | 1         | 2.86%   |
| Houston        | 1         | 2.86%   |
| Hamburg        | 1         | 2.86%   |
| Gmina Bolków  | 1         | 2.86%   |
| Glasgow        | 1         | 2.86%   |
| East Wenatchee | 1         | 2.86%   |
| Dunoon         | 1         | 2.86%   |
| Dobrzen Wielki | 1         | 2.86%   |
| Dehradun       | 1         | 2.86%   |
| Chicago        | 1         | 2.86%   |
| Birmingham     | 1         | 2.86%   |
| Barnsley       | 1         | 2.86%   |
| Amorebieta     | 1         | 2.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 13     | 19.51%  |
| WDC                 | 5         | 7      | 12.2%   |
| Unknown             | 5         | 5      | 12.2%   |
| Samsung Electronics | 5         | 5      | 12.2%   |
| Hitachi             | 4         | 6      | 9.76%   |
| Intel               | 2         | 2      | 4.88%   |
| GOODRAM             | 2         | 4      | 4.88%   |
| SPCC                | 1         | 2      | 2.44%   |
| Silicon Motion      | 1         | 1      | 2.44%   |
| ORICO               | 1         | 1      | 2.44%   |
| Netac               | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| Fujitsu             | 1         | 2      | 2.44%   |
| Crucial             | 1         | 1      | 2.44%   |
| ASUS-JM             | 1         | 1      | 2.44%   |
| ASMedia             | 1         | 1      | 2.44%   |
| A-DATA Technology   | 1         | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                   | 2         | 4.65%   |
| Seagate Backup+ Hub BK 8TB               | 2         | 4.65%   |
| Hitachi HTS545025B9A300 250GB            | 2         | 4.65%   |
| WDC WD7500BPVX-22JC3T0 752GB             | 1         | 2.33%   |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 2.33%   |
| WDC WD3200BPVT-75ZEST0 320GB             | 1         | 2.33%   |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 2.33%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB     | 1         | 2.33%   |
| Unknown MMC Card  64GB                   | 1         | 2.33%   |
| Unknown HBG4a2  32GB                     | 1         | 2.33%   |
| Unknown 016GE2  16GB                     | 1         | 2.33%   |
| SPCC Solid State Disk 256GB              | 1         | 2.33%   |
| Silicon Motion PCIe-8 SSD 512GB          | 1         | 2.33%   |
| Seagate ST9500325AS 500GB                | 1         | 2.33%   |
| Seagate ST9250320AS 250GB                | 1         | 2.33%   |
| Seagate ST9160310AS 160GB                | 1         | 2.33%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 2.33%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 2.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 2.33%   |
| Seagate Backup+ Desk 8TB                 | 1         | 2.33%   |
| Samsung SSD 840 Series 120GB             | 1         | 2.33%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB   | 1         | 2.33%   |
| Samsung MZVLB512HAJQ-00000 512GB         | 1         | 2.33%   |
| Samsung MZALQ512HALU-000L1 512GB         | 1         | 2.33%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD     | 1         | 2.33%   |
| ORICO M200 1TB SSD                       | 1         | 2.33%   |
| Netac SSD 256GB                          | 1         | 2.33%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 2.33%   |
| Intel SSDSC2CW060A3 64GB                 | 1         | 2.33%   |
| Intel SSDMAEXC024G3H 24GB                | 1         | 2.33%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 2.33%   |
| Hitachi HTS541080G9SA00 80GB             | 1         | 2.33%   |
| GOODRAM SSDPR-CX400-256-G2 256GB         | 1         | 2.33%   |
| GOODRAM SSDPR-CL100-240-G3 240GB         | 1         | 2.33%   |
| Goodram IR-SSDPR-S25A-120 120GB          | 1         | 2.33%   |
| Fujitsu MHW2120BH 120GB                  | 1         | 2.33%   |
| Crucial CT250MX500SSD1 250GB             | 1         | 2.33%   |
| ASUS-JM S41 SSD 16GB                     | 1         | 2.33%   |
| ASMedia ASMT1153e 1TB                    | 1         | 2.33%   |
| A-DATA SX8200NP 480GB                    | 1         | 2.33%   |

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
| HDD     | 17        | 27     | 43.59%  |
| SSD     | 10        | 15     | 25.64%  |
| NVMe    | 6         | 6      | 15.38%  |
| MMC     | 5         | 5      | 12.82%  |
| Unknown | 1         | 1      | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 37     | 62.16%  |
| NVMe | 6         | 6      | 16.22%  |
| MMC  | 5         | 5      | 13.51%  |
| SAS  | 3         | 6      | 8.11%   |

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
| 101-250        | 11        | 34.38%  |
| 21-50          | 5         | 15.63%  |
| 501-1000       | 5         | 15.63%  |
| 1-20           | 4         | 12.5%   |
| 251-500        | 3         | 9.38%   |
| More than 3000 | 2         | 6.25%   |
| 1001-2000      | 1         | 3.13%   |
| Unknown        | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 15        | 44.12%  |
| 21-50          | 5         | 14.71%  |
| 251-500        | 3         | 8.82%   |
| 101-250        | 3         | 8.82%   |
| 51-100         | 3         | 8.82%   |
| 501-1000       | 2         | 5.88%   |
| More than 3000 | 1         | 2.94%   |
| 1001-2000      | 1         | 2.94%   |
| Unknown        | 1         | 2.94%   |

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
| Works    | 16        | 26     | 44.44%  |
| Detected | 14        | 22     | 38.89%  |
| Malfunc  | 6         | 6      | 16.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 20        | 66.67%  |
| Samsung Electronics | 3         | 10%     |
| AMD                 | 3         | 10%     |
| Silicon Motion      | 2         | 6.67%   |
| Nvidia              | 1         | 3.33%   |
| JMicron Technology  | 1         | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 3         | 8.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 3         | 8.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 3         | 8.57%   |
| Samsung NVMe SSD Controller 980                                              | 2         | 5.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 5.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 2         | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 5.71%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 2         | 5.71%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 2.86%   |
| Silicon Motion Non-Volatile memory controller                                | 1         | 2.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 2.86%   |
| Nvidia MCP51 Serial ATA Controller                                           | 1         | 2.86%   |
| Nvidia MCP51 IDE                                                             | 1         | 2.86%   |
| JMicron JMB360 AHCI Controller                                               | 1         | 2.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 1         | 2.86%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 2.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 2.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 1         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 2.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 2.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 2.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 19        | 57.58%  |
| IDE  | 9         | 27.27%  |
| NVMe | 5         | 15.15%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 78.13%  |
| AMD    | 7         | 21.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 9.38%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 2         | 6.25%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 6.25%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 6.25%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 3.13%   |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 3.13%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 3.13%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 3.13%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 3.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.13%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 3.13%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.13%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 3.13%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 3.13%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 3.13%   |
| Intel Core 2 CPU U7600 @ 1.20GHz              | 1         | 3.13%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 3.13%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 3.13%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 1         | 3.13%   |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 3.13%   |
| AMD Turion 64 X2 Mobile Technology TL-64      | 1         | 3.13%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 3.13%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 3.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.13%   |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G  | 1         | 3.13%   |
| AMD C-50 Processor                            | 1         | 3.13%   |
| AMD A4-5000 APU with Radeon HD Graphics       | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 5         | 15.63%  |
| Intel Atom              | 5         | 15.63%  |
| Intel Core i5           | 4         | 12.5%   |
| Intel Core i7           | 3         | 9.38%   |
| Intel Core 2 Duo        | 3         | 9.38%   |
| Intel Core 2            | 2         | 6.25%   |
| AMD Ryzen 5             | 2         | 6.25%   |
| Intel Pentium           | 1         | 3.13%   |
| Intel Genuine           | 1         | 3.13%   |
| Intel Core i3           | 1         | 3.13%   |
| AMD Turion 64 X2 Mobile | 1         | 3.13%   |
| AMD Ryzen 7             | 1         | 3.13%   |
| AMD PRO A10             | 1         | 3.13%   |
| AMD C-50                | 1         | 3.13%   |
| AMD A4                  | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 17        | 53.13%  |
| 4      | 10        | 31.25%  |
| 1      | 4         | 12.5%   |
| 6      | 1         | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 32        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 17        | 53.13%  |
| 2      | 15        | 46.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 28        | 87.5%   |
| 32-bit         | 4         | 12.5%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 12.5%   |
| 0x406c4    | 3         | 9.38%   |
| 0x30678    | 3         | 9.38%   |
| 0x6f2      | 2         | 6.25%   |
| 0x306a9    | 2         | 6.25%   |
| 0x206a7    | 2         | 6.25%   |
| 0x20655    | 2         | 6.25%   |
| 0x106c2    | 2         | 6.25%   |
| 0x10676    | 2         | 6.25%   |
| 0x08108109 | 2         | 6.25%   |
| 0x806ec    | 1         | 3.13%   |
| 0x806ea    | 1         | 3.13%   |
| 0x40651    | 1         | 3.13%   |
| 0x1067a    | 1         | 3.13%   |
| 0x08600106 | 1         | 3.13%   |
| 0x0700010f | 1         | 3.13%   |
| 0x0600611a | 1         | 3.13%   |
| 0x05000029 | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Silvermont  | 6         | 18.75%  |
| Penryn      | 3         | 9.38%   |
| Core        | 3         | 9.38%   |
| Bonnell     | 3         | 9.38%   |
| Zen+        | 2         | 6.25%   |
| Westmere    | 2         | 6.25%   |
| SandyBridge | 2         | 6.25%   |
| KabyLake    | 2         | 6.25%   |
| IvyBridge   | 2         | 6.25%   |
| Zen 2       | 1         | 3.13%   |
| P6          | 1         | 3.13%   |
| K8 Hammer   | 1         | 3.13%   |
| Jaguar      | 1         | 3.13%   |
| Haswell     | 1         | 3.13%   |
| Excavator   | 1         | 3.13%   |
| Bobcat      | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 62.5%   |
| AMD    | 7         | 21.88%  |
| Nvidia | 5         | 15.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 12.82%  |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 7.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 7.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 7.69%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 5.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 5.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 5.13%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 2.56%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 2.56%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 2.56%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 2.56%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 2.56%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.56%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.56%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.56%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 2.56%   |
| AMD Renoir                                                                               | 1         | 2.56%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 2.56%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| 1 x Intel  | 20        | 62.5%   |
| 1 x AMD    | 6         | 18.75%  |
| 1 x Nvidia | 5         | 15.63%  |
| 2 x AMD    | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 31        | 96.88%  |
| Proprietary | 1         | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 68.75%  |
| 0.01-0.5   | 6         | 18.75%  |
| 1.01-2.0   | 3         | 9.38%   |
| 0.51-1.0   | 1         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 7         | 22.58%  |
| AU Optronics        | 6         | 19.35%  |
| Chimei Innolux      | 3         | 9.68%   |
| BOE                 | 3         | 9.68%   |
| Samsung Electronics | 2         | 6.45%   |
| Lenovo              | 2         | 6.45%   |
| CPT                 | 2         | 6.45%   |
| Medion              | 1         | 3.23%   |
| LG Philips          | 1         | 3.23%   |
| Insignia            | 1         | 3.23%   |
| Hitachi             | 1         | 3.23%   |
| HannStar            | 1         | 3.23%   |
| Apple               | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D330 SAM0D93 1920x1080 530x300mm 24.0-inch    | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 1         | 3.13%   |
| Medion MD 20310 MED3645 1920x1080 521x293mm 23.5-inch                | 1         | 3.13%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 3.13%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 3.13%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 3.13%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch          | 1         | 3.13%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch          | 1         | 3.13%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 3.13%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 3.13%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 3.13%   |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch              | 1         | 3.13%   |
| Lenovo LCD Monitor LEN4022 1400x1050 286x214mm 14.1-inch             | 1         | 3.13%   |
| Insignia NS24ED200NA14 BBY0032 1360x768 640x384mm 29.4-inch          | 1         | 3.13%   |
| Hitachi HDMI HEC0088 1920x540                                        | 1         | 3.13%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 1         | 3.13%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 3.13%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch     | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch      | 1         | 3.13%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                | 1         | 3.13%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 1         | 3.13%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 1         | 3.13%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch       | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch        | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO132C 1366x768 293x164mm 13.2-inch        | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch       | 1         | 3.13%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 1         | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 10        | 31.25%  |
| 1366x768 (WXGA)  | 9         | 28.13%  |
| 1600x900 (HD+)   | 3         | 9.38%   |
| 1024x600         | 3         | 9.38%   |
| 1920x540         | 2         | 6.25%   |
| 1440x900 (WXGA+) | 2         | 6.25%   |
| 1280x800 (WXGA)  | 2         | 6.25%   |
| 1400x1050        | 1         | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 9         | 28.13%  |
| 17     | 6         | 18.75%  |
| 13     | 6         | 18.75%  |
| 14     | 3         | 9.38%   |
| 10     | 3         | 9.38%   |
| 48     | 2         | 6.25%   |
| 24     | 1         | 3.13%   |
| 23     | 1         | 3.13%   |
| 16     | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 40.63%  |
| 201-300     | 8         | 25%     |
| 351-400     | 7         | 21.88%  |
| 501-600     | 2         | 6.25%   |
| 1001-1500   | 2         | 6.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 78.13%  |
| 16/10 | 4         | 12.5%   |
| 1.96  | 2         | 6.25%   |
| 4/3   | 1         | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 31.25%  |
| 121-130        | 5         | 15.63%  |
| 81-90          | 4         | 12.5%   |
| 71-80          | 4         | 12.5%   |
| 41-50          | 3         | 9.38%   |
| 201-250        | 2         | 6.25%   |
| 501-1000       | 2         | 6.25%   |
| 131-140        | 1         | 3.13%   |
| 91-100         | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 14        | 45.16%  |
| 121-160 | 11        | 35.48%  |
| 51-100  | 4         | 12.9%   |
| 1-50    | 2         | 6.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 30        | 93.75%  |
| 2     | 1         | 3.13%   |
| 0     | 1         | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 14        | 29.79%  |
| Realtek Semiconductor    | 13        | 27.66%  |
| Qualcomm Atheros         | 8         | 17.02%  |
| Marvell Technology Group | 3         | 6.38%   |
| Broadcom                 | 3         | 6.38%   |
| Broadcom Limited         | 2         | 4.26%   |
| TP-Link                  | 1         | 2.13%   |
| Samsung Electronics      | 1         | 2.13%   |
| Ralink                   | 1         | 2.13%   |
| Nvidia                   | 1         | 2.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 6         | 10.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 6.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 3.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 3.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.45%   |
| Intel Wireless 7265                                                     | 2         | 3.45%   |
| Intel Wireless 7260                                                     | 2         | 3.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 3.45%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 1.72%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 1.72%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 1.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 1.72%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 1.72%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 1.72%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 1.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 1.72%   |
| Intel WiFi Link 5100                                                    | 1         | 1.72%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.72%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.72%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.72%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.72%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.72%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.72%   |
| Intel 82573L Gigabit Ethernet Controller                                | 1         | 1.72%   |
| Intel 82566MM Gigabit Network Connection                                | 1         | 1.72%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                        | 1         | 1.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 1         | 1.72%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 1.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 45.16%  |
| Qualcomm Atheros      | 7         | 22.58%  |
| Realtek Semiconductor | 5         | 16.13%  |
| Broadcom Limited      | 2         | 6.45%   |
| TP-Link               | 1         | 3.23%   |
| Ralink                | 1         | 3.23%   |
| Broadcom              | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 6.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 6.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 6.45%   |
| Intel Wireless 7265                                                     | 2         | 6.45%   |
| Intel Wireless 7260                                                     | 2         | 6.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 6.45%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 3.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 3.23%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 3.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 3.23%   |
| Intel WiFi Link 5100                                                    | 1         | 3.23%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 3.23%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 3.23%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 3.23%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 3.23%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 3.23%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 3.23%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 3.23%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 11        | 40.74%  |
| Intel                    | 5         | 18.52%  |
| Qualcomm Atheros         | 4         | 14.81%  |
| Marvell Technology Group | 3         | 11.11%  |
| Broadcom                 | 2         | 7.41%   |
| Samsung Electronics      | 1         | 3.7%    |
| Nvidia                   | 1         | 3.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 22.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 14.81%  |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 7.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 7.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 3.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 3.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 3.7%    |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 3.7%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 3.7%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 3.7%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 3.7%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 3.7%    |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 3.7%    |
| Intel 82566MM Gigabit Network Connection                          | 1         | 3.7%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 3.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 52.63%  |
| Ethernet | 27        | 47.37%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 69.7%   |
| Ethernet | 10        | 30.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 23        | 71.88%  |
| 1     | 7         | 21.88%  |
| 3     | 1         | 3.13%   |
| 0     | 1         | 3.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 73.53%  |
| Yes  | 9         | 26.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 28.57%  |
| Broadcom                        | 4         | 19.05%  |
| Realtek Semiconductor           | 2         | 9.52%   |
| Taiyo Yuden                     | 1         | 4.76%   |
| Realtek                         | 1         | 4.76%   |
| Qualcomm Atheros Communications | 1         | 4.76%   |
| IMC Networks                    | 1         | 4.76%   |
| Foxconn / Hon Hai               | 1         | 4.76%   |
| Dell                            | 1         | 4.76%   |
| Cambridge Silicon Radio         | 1         | 4.76%   |
| ASUSTek Computer                | 1         | 4.76%   |
| Apple                           | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 19.05%  |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 4.76%   |
| Realtek RTL8723B Bluetooth                          | 1         | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 4.76%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 4.76%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4.76%   |
| Intel AX201 Bluetooth                               | 1         | 4.76%   |
| IMC Networks Bluetooth Radio                        | 1         | 4.76%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 4.76%   |
| Dell Wireless 365 Bluetooth                         | 1         | 4.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.76%   |
| Broadcom HP Portable SoftSailing                    | 1         | 4.76%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 4.76%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 4.76%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 4.76%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 4.76%   |
| Apple Bluetooth HCI                                 | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 23        | 65.71%  |
| AMD                 | 6         | 17.14%  |
| Nvidia              | 3         | 8.57%   |
| Native Instruments  | 1         | 2.86%   |
| Focusrite-Novation  | 1         | 2.86%   |
| C-Media Electronics | 1         | 2.86%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 14.63%  |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 7.32%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 7.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 4.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 4.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 4.88%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 2.44%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 2.44%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.44%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 2.44%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 2.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.44%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.44%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.44%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 2.44%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 2.44%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.44%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 2.44%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 30.77%  |
| Unknown             | 5         | 19.23%  |
| SK hynix            | 3         | 11.54%  |
| Micron Technology   | 3         | 11.54%  |
| Nanya Technology    | 2         | 7.69%   |
| Kingston            | 2         | 7.69%   |
| GOODRAM             | 1         | 3.85%   |
| G.Skill             | 1         | 3.85%   |
| Corsair             | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s      | 2         | 6.9%    |
| Unknown RAM Module 2GB SODIMM SDRAM                        | 1         | 3.45%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                | 1         | 3.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 266MT/s                 | 1         | 3.45%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                   | 1         | 3.45%   |
| Unknown RAM Module 1024MB SODIMM DDR2                      | 1         | 3.45%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                   | 1         | 3.45%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s               | 1         | 3.45%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1         | 3.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 3.45%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 3.45%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 1         | 3.45%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 1         | 3.45%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 3.45%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s      | 1         | 3.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 3.45%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s            | 1         | 3.45%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s       | 1         | 3.45%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 3.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s | 1         | 3.45%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 3.45%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s     | 1         | 3.45%   |
| Kingston RAM Module 4GB SODIMM DDR3 800MT/s                | 1         | 3.45%   |
| Kingston RAM ACR16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s     | 1         | 3.45%   |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s   | 1         | 3.45%   |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s     | 1         | 3.45%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s     | 1         | 3.45%   |
| Corsair RAM CMSA4GX3M1A1333C9 4GB SODIMM DDR3 1333MT/s     | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 14        | 58.33%  |
| DDR4    | 4         | 16.67%  |
| SDRAM   | 2         | 8.33%   |
| DDR2    | 2         | 8.33%   |
| LPDDR3  | 1         | 4.17%   |
| Unknown | 1         | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 21        | 91.3%   |
| Row Of Chips | 1         | 4.35%   |
| Unknown      | 1         | 4.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 9         | 32.14%  |
| 2048  | 9         | 32.14%  |
| 8192  | 5         | 17.86%  |
| 1024  | 3         | 10.71%  |
| 16384 | 2         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 9         | 34.62%  |
| 2667    | 3         | 11.54%  |
| 1334    | 2         | 7.69%   |
| 1333    | 2         | 7.69%   |
| 1066    | 2         | 7.69%   |
| 800     | 2         | 7.69%   |
| Unknown | 2         | 7.69%   |
| 4199    | 1         | 3.85%   |
| 3200    | 1         | 3.85%   |
| 1867    | 1         | 3.85%   |
| 266     | 1         | 3.85%   |

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
| Chicony Electronics                    | 9         | 34.62%  |
| Microdia                               | 4         | 15.38%  |
| Suyin                                  | 3         | 11.54%  |
| Acer                                   | 3         | 11.54%  |
| Sunplus Innovation Technology          | 2         | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.69%   |
| Z-Star Microelectronics                | 1         | 3.85%   |
| Microsoft                              | 1         | 3.85%   |
| Alcor Micro                            | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                           | 2         | 7.69%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 3.85%   |
| Suyin USB2.0 UVC 1.3M WebCam                                | 1         | 3.85%   |
| Suyin HP Truevision HD                                      | 1         | 3.85%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 3.85%   |
| Sunplus Integrated Webcam                                   | 1         | 3.85%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 3.85%   |
| Microsoft LifeCam Cinema                                    | 1         | 3.85%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 3.85%   |
| Microdia Lenovo EasyCamera                                  | 1         | 3.85%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 3.85%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 3.85%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 3.85%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 3.85%   |
| Chicony HP TrueVision HD Camera                             | 1         | 3.85%   |
| Chicony HP Integrated Webcam                                | 1         | 3.85%   |
| Chicony HP HD Webcam                                        | 1         | 3.85%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 3.85%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera            | 1         | 3.85%   |
| Alcor Micro USB Camera                                      | 1         | 3.85%   |
| Acer Lenovo EasyCamera                                      | 1         | 3.85%   |
| Acer HP Webcam                                              | 1         | 3.85%   |
| Acer HD Webcam                                              | 1         | 3.85%   |

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
| 0     | 19        | 59.38%  |
| 1     | 10        | 31.25%  |
| 2     | 3         | 9.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 7         | 38.89%  |
| Net/wireless          | 4         | 22.22%  |
| Multimedia controller | 4         | 22.22%  |
| Graphics card         | 2         | 11.11%  |
| Chipcard              | 1         | 5.56%   |

