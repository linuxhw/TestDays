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

Total: 54

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-ef2xxx            | [b0dbfa8a76](https://linux-hardware.org/?probe=b0dbfa8a76) | Aug 26, 2023 |
| HP            | Laptop 15-ef2xxx            | [da3f894af1](https://linux-hardware.org/?probe=da3f894af1) | Aug 26, 2023 |
| Apple         | MacBookPro9,2               | [4006007a76](https://linux-hardware.org/?probe=4006007a76) | Aug 20, 2023 |
| Acer          | Aspire 5920                 | [31447ef238](https://linux-hardware.org/?probe=31447ef238) | Aug 17, 2023 |
| Acer          | Aspire 5920                 | [8c57c50f82](https://linux-hardware.org/?probe=8c57c50f82) | Aug 17, 2023 |
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
| Sparky 6    | 8         | 18.18%  |
| Sparky 7    | 7         | 15.91%  |
| Sparky 8    | 4         | 9.09%   |
| Sparky 6.5  | 4         | 9.09%   |
| Sparky 6.1  | 4         | 9.09%   |
| Sparky 5.14 | 3         | 6.82%   |
| Sparky 6.7  | 2         | 4.55%   |
| Sparky 6.6  | 2         | 4.55%   |
| Sparky 6.3  | 2         | 4.55%   |
| Sparky 6.0  | 2         | 4.55%   |
| Sparky 5.13 | 2         | 4.55%   |
| Sparky 5.12 | 2         | 4.55%   |
| Sparky 5.10 | 2         | 4.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Sparky | 40        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-11-686          | 3         | 6.52%   |
| 5.17.0-1-amd64         | 2         | 4.35%   |
| 5.10.0-9-amd64         | 2         | 4.35%   |
| 5.10.0-8-amd64         | 2         | 4.35%   |
| 5.10.0-21-amd64        | 2         | 4.35%   |
| 4.19.0-8-amd64         | 2         | 4.35%   |
| 4.19.0-13-686          | 2         | 4.35%   |
| 4.19.0-12-amd64        | 2         | 4.35%   |
| 6.4.4-sparky8-amd64    | 1         | 2.17%   |
| 6.4.12-x64v3-xanmod1   | 1         | 2.17%   |
| 6.4.0-2-amd64          | 1         | 2.17%   |
| 6.3.3-1-liquorix-amd64 | 1         | 2.17%   |
| 6.3.0-1-amd64          | 1         | 2.17%   |
| 6.2.0-sparky-amd64     | 1         | 2.17%   |
| 5.9.0-4-amd64          | 1         | 2.17%   |
| 5.8.13-sparky-amd64    | 1         | 2.17%   |
| 5.8.0-2-amd64          | 1         | 2.17%   |
| 5.5.0-2-amd64          | 1         | 2.17%   |
| 5.4.7-sparky-amd64     | 1         | 2.17%   |
| 5.2.0-2-amd64          | 1         | 2.17%   |
| 5.18.0-4-amd64         | 1         | 2.17%   |
| 5.18.0-2-amd64         | 1         | 2.17%   |
| 5.16.0-5-amd64         | 1         | 2.17%   |
| 5.15.0-3-amd64         | 1         | 2.17%   |
| 5.14.0-4-amd64         | 1         | 2.17%   |
| 5.10.4-sparky-amd64    | 1         | 2.17%   |
| 5.10.0-6-amd64         | 1         | 2.17%   |
| 5.10.0-3-amd64         | 1         | 2.17%   |
| 5.10.0-23-amd64        | 1         | 2.17%   |
| 5.10.0-22-amd64        | 1         | 2.17%   |
| 5.10.0-21-686          | 1         | 2.17%   |
| 5.10.0-20-amd64        | 1         | 2.17%   |
| 5.10.0-19-amd64        | 1         | 2.17%   |
| 5.10.0-16-amd64        | 1         | 2.17%   |
| 5.10.0-14-amd64        | 1         | 2.17%   |
| 4.19.0-14-686          | 1         | 2.17%   |
| 4.19.0-10-686          | 1         | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 17        | 39.53%  |
| 4.19.0  | 6         | 13.95%  |
| 5.18.0  | 2         | 4.65%   |
| 5.17.0  | 2         | 4.65%   |
| 6.4.4   | 1         | 2.33%   |
| 6.4.12  | 1         | 2.33%   |
| 6.4.0   | 1         | 2.33%   |
| 6.3.3   | 1         | 2.33%   |
| 6.3.0   | 1         | 2.33%   |
| 6.2.0   | 1         | 2.33%   |
| 5.9.0   | 1         | 2.33%   |
| 5.8.13  | 1         | 2.33%   |
| 5.8.0   | 1         | 2.33%   |
| 5.5.0   | 1         | 2.33%   |
| 5.4.7   | 1         | 2.33%   |
| 5.2.0   | 1         | 2.33%   |
| 5.16.0  | 1         | 2.33%   |
| 5.15.0  | 1         | 2.33%   |
| 5.14.0  | 1         | 2.33%   |
| 5.10.4  | 1         | 2.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 18        | 41.86%  |
| 4.19    | 6         | 13.95%  |
| 6.4     | 3         | 6.98%   |
| 6.3     | 2         | 4.65%   |
| 5.8     | 2         | 4.65%   |
| 5.18    | 2         | 4.65%   |
| 5.17    | 2         | 4.65%   |
| 6.2     | 1         | 2.33%   |
| 5.9     | 1         | 2.33%   |
| 5.5     | 1         | 2.33%   |
| 5.4     | 1         | 2.33%   |
| 5.2     | 1         | 2.33%   |
| 5.16    | 1         | 2.33%   |
| 5.15    | 1         | 2.33%   |
| 5.14    | 1         | 2.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 36        | 90%     |
| i686   | 4         | 10%     |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| XFCE             | 12        | 29.27%  |
| LXQt             | 9         | 21.95%  |
| Unknown          | 7         | 17.07%  |
| KDE5             | 5         | 12.2%   |
| openbox          | 3         | 7.32%   |
| MATE             | 2         | 4.88%   |
| lightdm-xsession | 1         | 2.44%   |
| GNOME Classic    | 1         | 2.44%   |
| GNOME            | 1         | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 37        | 90.24%  |
| Tty  | 4         | 9.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 12        | 30%     |
| Unknown | 12        | 30%     |
| SDDM    | 8         | 20%     |
| TDM     | 6         | 15%     |
| XDM     | 1         | 2.5%    |
| GDM     | 1         | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 13        | 32.5%   |
| pl_PL   | 3         | 7.5%    |
| en_GB   | 3         | 7.5%    |
| de_DE   | 3         | 7.5%    |
| pt_BR   | 2         | 5%      |
| fr_FR   | 2         | 5%      |
| es_ES   | 2         | 5%      |
| Unknown | 2         | 5%      |
| ru_RU   | 1         | 2.5%    |
| ja_JP   | 1         | 2.5%    |
| it_IT   | 1         | 2.5%    |
| es_MX   | 1         | 2.5%    |
| es_CO   | 1         | 2.5%    |
| es_CL   | 1         | 2.5%    |
| en_PH   | 1         | 2.5%    |
| en_IN   | 1         | 2.5%    |
| en_CA   | 1         | 2.5%    |
| ar_EG   | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 25        | 62.5%   |
| EFI  | 15        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 35        | 87.5%   |
| Overlay | 2         | 5%      |
| Btrfs   | 2         | 5%      |
| Ext2    | 1         | 2.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 15        | 37.5%   |
| MBR     | 13        | 32.5%   |
| Unknown | 12        | 30%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 90%     |
| Yes       | 4         | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 67.5%   |
| Yes       | 13        | 32.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 25%     |
| Lenovo              | 5         | 12.5%   |
| Dell                | 4         | 10%     |
| ASUSTek Computer    | 4         | 10%     |
| Acer                | 4         | 10%     |
| Google              | 2         | 5%      |
| Apple               | 2         | 5%      |
| Samsung Electronics | 1         | 2.5%    |
| Positivo            | 1         | 2.5%    |
| Panasonic           | 1         | 2.5%    |
| MSI                 | 1         | 2.5%    |
| Mediacom            | 1         | 2.5%    |
| HUAWEI              | 1         | 2.5%    |
| Fujitsu Siemens     | 1         | 2.5%    |
| eMachines           | 1         | 2.5%    |
| Beelink             | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NC10                            | 1         | 2.5%    |
| Positivo CHT14B                         | 1         | 2.5%    |
| Panasonic CFSZ5-2                       | 1         | 2.5%    |
| MSI Alpha 15 A3DDK                      | 1         | 2.5%    |
| Mediacom SmartBook 14 FullHD - SB14UC   | 1         | 2.5%    |
| Lenovo ThinkPad T61 7659AB7             | 1         | 2.5%    |
| Lenovo ThinkPad T60 2007FUG             | 1         | 2.5%    |
| Lenovo ThinkPad E15 20RES0GF00          | 1         | 2.5%    |
| Lenovo IdeaPad S206 20154               | 1         | 2.5%    |
| Lenovo G50-30 80G0                      | 1         | 2.5%    |
| HUAWEI HVY-WXX9                         | 1         | 2.5%    |
| HP Stream Notebook PC 13                | 1         | 2.5%    |
| HP Pavilion g7                          | 1         | 2.5%    |
| HP Pavilion dv9000 (GA359UA#ABA)        | 1         | 2.5%    |
| HP Pavilion dv5                         | 1         | 2.5%    |
| HP Laptop 17z-ca100                     | 1         | 2.5%    |
| HP Laptop 15-ef2xxx                     | 1         | 2.5%    |
| HP EliteBook Folio 9480m                | 1         | 2.5%    |
| HP EliteBook 8770w                      | 1         | 2.5%    |
| HP EliteBook 8440p                      | 1         | 2.5%    |
| HP EliteBook 745 G3                     | 1         | 2.5%    |
| Google Swanky                           | 1         | 2.5%    |
| Google Banon                            | 1         | 2.5%    |
| Fujitsu Siemens STYLISTIC ST5112        | 1         | 2.5%    |
| eMachines E525                          | 1         | 2.5%    |
| Dell Latitude XT3                       | 1         | 2.5%    |
| Dell Inspiron N5010                     | 1         | 2.5%    |
| Dell Inspiron 5770                      | 1         | 2.5%    |
| Dell Inspiron 5720                      | 1         | 2.5%    |
| Beelink BT3 PRO                         | 1         | 2.5%    |
| ASUS VivoBook_ASUSLaptop E410MAB_E410MA | 1         | 2.5%    |
| ASUS S101                               | 1         | 2.5%    |
| ASUS M70Vn                              | 1         | 2.5%    |
| ASUS 1000HE                             | 1         | 2.5%    |
| Apple MacBookPro9,2                     | 1         | 2.5%    |
| Apple MacBook1,1                        | 1         | 2.5%    |
| Acer Aspire E1-522                      | 1         | 2.5%    |
| Acer Aspire A315-58                     | 1         | 2.5%    |
| Acer Aspire 5920                        | 1         | 2.5%    |
| Acer Aspire 5742G                       | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| HP EliteBook              | 4         | 10%     |
| Acer Aspire               | 4         | 10%     |
| Lenovo ThinkPad           | 3         | 7.5%    |
| HP Pavilion               | 3         | 7.5%    |
| Dell Inspiron             | 3         | 7.5%    |
| HP Laptop                 | 2         | 5%      |
| Samsung NC10              | 1         | 2.5%    |
| Positivo CHT14B           | 1         | 2.5%    |
| Panasonic CFSZ5-2         | 1         | 2.5%    |
| MSI Alpha                 | 1         | 2.5%    |
| Mediacom SmartBook        | 1         | 2.5%    |
| Lenovo IdeaPad            | 1         | 2.5%    |
| Lenovo G50-30             | 1         | 2.5%    |
| HUAWEI HVY-WXX9           | 1         | 2.5%    |
| HP Stream                 | 1         | 2.5%    |
| Google Swanky             | 1         | 2.5%    |
| Google Banon              | 1         | 2.5%    |
| Fujitsu Siemens STYLISTIC | 1         | 2.5%    |
| eMachines E525            | 1         | 2.5%    |
| Dell Latitude             | 1         | 2.5%    |
| Beelink BT3               | 1         | 2.5%    |
| ASUS VivoBook             | 1         | 2.5%    |
| ASUS S101                 | 1         | 2.5%    |
| ASUS M70Vn                | 1         | 2.5%    |
| ASUS 1000HE               | 1         | 2.5%    |
| Apple MacBookPro9         | 1         | 2.5%    |
| Apple MacBook1            | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2008 | 5         | 12.5%   |
| 2021 | 4         | 10%     |
| 2012 | 4         | 10%     |
| 2014 | 3         | 7.5%    |
| 2010 | 3         | 7.5%    |
| 2009 | 3         | 7.5%    |
| 2020 | 2         | 5%      |
| 2019 | 2         | 5%      |
| 2018 | 2         | 5%      |
| 2017 | 2         | 5%      |
| 2016 | 2         | 5%      |
| 2011 | 2         | 5%      |
| 2007 | 2         | 5%      |
| 2006 | 2         | 5%      |
| 2022 | 1         | 2.5%    |
| 2013 | 1         | 2.5%    |

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
| Disabled | 40        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 95%     |
| Yes  | 2         | 5%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 32.5%   |
| 4.01-8.0   | 7         | 17.5%   |
| 1.01-2.0   | 7         | 17.5%   |
| 2.01-3.0   | 4         | 10%     |
| 8.01-16.0  | 3         | 7.5%    |
| 32.01-64.0 | 2         | 5%      |
| 16.01-24.0 | 2         | 5%      |
| 24.01-32.0 | 1         | 2.5%    |
| 0.51-1.0   | 1         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 11        | 26.19%  |
| 0.51-1.0 | 11        | 26.19%  |
| 1.01-2.0 | 10        | 23.81%  |
| 4.01-8.0 | 4         | 9.52%   |
| 3.01-4.0 | 3         | 7.14%   |
| 0.01-0.5 | 3         | 7.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 72.5%   |
| 2      | 9         | 22.5%   |
| 5      | 1         | 2.5%    |
| 4      | 1         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 62.5%   |
| Yes       | 15        | 37.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 82.5%   |
| No        | 7         | 17.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 92.5%   |
| No        | 3         | 7.5%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 70%     |
| No        | 12        | 30%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 10        | 25%     |
| Germany     | 5         | 12.5%   |
| UK          | 3         | 7.5%    |
| Poland      | 3         | 7.5%    |
| Canada      | 3         | 7.5%    |
| Spain       | 2         | 5%      |
| France      | 2         | 5%      |
| Brazil      | 2         | 5%      |
| Uzbekistan  | 1         | 2.5%    |
| Philippines | 1         | 2.5%    |
| New Zealand | 1         | 2.5%    |
| Mexico      | 1         | 2.5%    |
| Japan       | 1         | 2.5%    |
| Italy       | 1         | 2.5%    |
| Indonesia   | 1         | 2.5%    |
| India       | 1         | 2.5%    |
| Colombia    | 1         | 2.5%    |
| Chile       | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Montreal       | 2         | 4.65%   |
| Leipzig        | 2         | 4.65%   |
| Wenatchee      | 1         | 2.33%   |
| Tucson         | 1         | 2.33%   |
| Tauranga       | 1         | 2.33%   |
| Takahama       | 1         | 2.33%   |
| Spokane        | 1         | 2.33%   |
| Santo André   | 1         | 2.33%   |
| San Antonio    | 1         | 2.33%   |
| Salina Cruz    | 1         | 2.33%   |
| Sainte-Julie   | 1         | 2.33%   |
| Rio de Janeiro | 1         | 2.33%   |
| Quezon City    | 1         | 2.33%   |
| Pujaudran      | 1         | 2.33%   |
| Puente Alto    | 1         | 2.33%   |
| Pompano Beach  | 1         | 2.33%   |
| Munich         | 1         | 2.33%   |
| Montreuil      | 1         | 2.33%   |
| Milano         | 1         | 2.33%   |
| Miekoszyn      | 1         | 2.33%   |
| Mannheim       | 1         | 2.33%   |
| Madrid         | 1         | 2.33%   |
| Liverpool      | 1         | 2.33%   |
| Koło          | 1         | 2.33%   |
| Jakarta        | 1         | 2.33%   |
| Jacksonville   | 1         | 2.33%   |
| Houston        | 1         | 2.33%   |
| Hamburg        | 1         | 2.33%   |
| Gmina Bolków  | 1         | 2.33%   |
| Glasgow        | 1         | 2.33%   |
| Framingham     | 1         | 2.33%   |
| East Wenatchee | 1         | 2.33%   |
| Dunoon         | 1         | 2.33%   |
| Dobrzen Wielki | 1         | 2.33%   |
| Dehradun       | 1         | 2.33%   |
| Chicago        | 1         | 2.33%   |
| Bukhara        | 1         | 2.33%   |
| Bogotá        | 1         | 2.33%   |
| Birmingham     | 1         | 2.33%   |
| Barnsley       | 1         | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 14     | 16.67%  |
| Unknown             | 7         | 7      | 12.96%  |
| WDC                 | 6         | 8      | 11.11%  |
| Samsung Electronics | 5         | 5      | 9.26%   |
| Hitachi             | 5         | 8      | 9.26%   |
| SPCC                | 3         | 4      | 5.56%   |
| Silicon Motion      | 2         | 2      | 3.7%    |
| Intel               | 2         | 2      | 3.7%    |
| Goodram             | 2         | 4      | 3.7%    |
| Toshiba             | 1         | 1      | 1.85%   |
| SK hynix            | 1         | 1      | 1.85%   |
| ORICO               | 1         | 1      | 1.85%   |
| Netac               | 1         | 1      | 1.85%   |
| Micron Technology   | 1         | 1      | 1.85%   |
| HGST                | 1         | 1      | 1.85%   |
| Fujitsu             | 1         | 2      | 1.85%   |
| Crucial             | 1         | 1      | 1.85%   |
| ASUS-JM             | 1         | 1      | 1.85%   |
| ASMedia             | 1         | 1      | 1.85%   |
| Apple               | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 1      | 1.85%   |
| Unknown             | 1         | 1      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                                | 2         | 3.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 2         | 3.57%   |
| Seagate Backup+ Hub BK 8TB                            | 2         | 3.57%   |
| Hitachi HTS545025B9A300 250GB                         | 2         | 3.57%   |
| WDC WD7500BPVX-22JC3T0 752GB                          | 1         | 1.79%   |
| WDC WD5000BEVT-22ZAT0 500GB                           | 1         | 1.79%   |
| WDC WD50 00LPCX-21VHAT0 500GB                         | 1         | 1.79%   |
| WDC WD3200BPVT-75ZEST0 320GB                          | 1         | 1.79%   |
| WDC WD1600BEVT-22ZCT0 160GB                           | 1         | 1.79%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB                  | 1         | 1.79%   |
| Unknown SDC  8GB                                      | 1         | 1.79%   |
| Unknown NCard  32GB                                   | 1         | 1.79%   |
| Unknown MMC Card  64GB                                | 1         | 1.79%   |
| Unknown HBG4a2  32GB                                  | 1         | 1.79%   |
| Unknown 016GE2  16GB                                  | 1         | 1.79%   |
| Toshiba MQ04ABF100 1TB                                | 1         | 1.79%   |
| SPCC Solid State Disk 512GB                           | 1         | 1.79%   |
| SPCC Solid State Disk 256GB                           | 1         | 1.79%   |
| SPCC M.2 PCIe SSD 512GB                               | 1         | 1.79%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                  | 1         | 1.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 1         | 1.79%   |
| Silicon Motion PCIe-8 SSD 512GB                       | 1         | 1.79%   |
| Seagate ST9500325AS 500GB                             | 1         | 1.79%   |
| Seagate ST9250320AS 250GB                             | 1         | 1.79%   |
| Seagate ST9160310AS 160GB                             | 1         | 1.79%   |
| Seagate ST1000LM048-2E7172 1TB                        | 1         | 1.79%   |
| Seagate ST1000LM035-1RK172 1TB                        | 1         | 1.79%   |
| Seagate Backup+ Desk 8TB                              | 1         | 1.79%   |
| Samsung SSD 840 Series 120GB                          | 1         | 1.79%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 1         | 1.79%   |
| Samsung MZVLB512HAJQ-00000 512GB                      | 1         | 1.79%   |
| Samsung MZALQ512HALU-000L1 512GB                      | 1         | 1.79%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD                  | 1         | 1.79%   |
| ORICO M200 1TB SSD                                    | 1         | 1.79%   |
| Netac SSD 256GB                                       | 1         | 1.79%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD              | 1         | 1.79%   |
| Intel SSDSC2CW060A3 64GB                              | 1         | 1.79%   |
| Intel SSDMAEXC024G3H 24GB                             | 1         | 1.79%   |
| Hitachi HTS545025B9SA02 250GB                         | 1         | 1.79%   |
| Hitachi HTS542516K9SA00 160GB                         | 1         | 1.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 13     | 37.5%   |
| WDC     | 5         | 7      | 20.83%  |
| Hitachi | 5         | 8      | 20.83%  |
| Toshiba | 1         | 1      | 4.17%   |
| HGST    | 1         | 1      | 4.17%   |
| Fujitsu | 1         | 2      | 4.17%   |
| ASMedia | 1         | 1      | 4.17%   |
| Apple   | 1         | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SPCC                | 2         | 3      | 15.38%  |
| Samsung Electronics | 2         | 2      | 15.38%  |
| Intel               | 2         | 2      | 15.38%  |
| Goodram             | 2         | 4      | 15.38%  |
| ORICO               | 1         | 1      | 7.69%   |
| Netac               | 1         | 1      | 7.69%   |
| Micron Technology   | 1         | 1      | 7.69%   |
| Crucial             | 1         | 1      | 7.69%   |
| ASUS-JM             | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 22        | 34     | 44%     |
| SSD     | 11        | 16     | 22%     |
| MMC     | 8         | 8      | 16%     |
| NVMe    | 8         | 9      | 16%     |
| Unknown | 1         | 1      | 2%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 44     | 58.33%  |
| NVMe | 8         | 9      | 16.67%  |
| MMC  | 8         | 8      | 16.67%  |
| SAS  | 4         | 7      | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 36     | 66.67%  |
| 0.51-1.0   | 8         | 9      | 24.24%  |
| 4.01-10.0  | 2         | 4      | 6.06%   |
| 2.01-3.0   | 1         | 1      | 3.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 12        | 30%     |
| 501-1000       | 9         | 22.5%   |
| 21-50          | 6         | 15%     |
| 1-20           | 5         | 12.5%   |
| 251-500        | 4         | 10%     |
| More than 3000 | 2         | 5%      |
| 1001-2000      | 1         | 2.5%    |
| Unknown        | 1         | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 20        | 47.62%  |
| 21-50          | 6         | 14.29%  |
| 251-500        | 4         | 9.52%   |
| 101-250        | 3         | 7.14%   |
| 501-1000       | 3         | 7.14%   |
| 51-100         | 3         | 7.14%   |
| More than 3000 | 1         | 2.38%   |
| 1001-2000      | 1         | 2.38%   |
| Unknown        | 1         | 2.38%   |

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
| Detected | 20        | 31     | 43.48%  |
| Works    | 19        | 30     | 41.3%   |
| Malfunc  | 7         | 7      | 15.22%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 26        | 68.42%  |
| Silicon Motion      | 3         | 7.89%   |
| Samsung Electronics | 3         | 7.89%   |
| AMD                 | 3         | 7.89%   |
| SK hynix            | 1         | 2.63%   |
| Nvidia              | 1         | 2.63%   |
| JMicron Technology  | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 3         | 6.82%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 3         | 6.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 3         | 6.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 6.82%   |
| Samsung NVMe SSD Controller 980                                              | 2         | 4.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 4.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 4.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 2         | 4.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 4.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 4.55%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 2         | 4.55%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 2.27%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers            | 1         | 2.27%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 2.27%   |
| Silicon Motion Non-Volatile memory controller                                | 1         | 2.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 2.27%   |
| Nvidia MCP51 Serial ATA Controller                                           | 1         | 2.27%   |
| Nvidia MCP51 IDE                                                             | 1         | 2.27%   |
| JMicron JMB360 AHCI Controller                                               | 1         | 2.27%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 2.27%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 2.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 2.27%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 2.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 1         | 2.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 2.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 2.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 25        | 59.52%  |
| IDE  | 10        | 23.81%  |
| NVMe | 7         | 16.67%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 32        | 80%     |
| AMD    | 8         | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 7.5%    |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 5%      |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 2         | 5%      |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 5%      |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 5%      |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 2.5%    |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 2.5%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 2.5%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2.5%    |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 2.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2.5%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 2.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.5%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 2.5%    |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.5%    |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 2.5%    |
| Intel Core 2 CPU U7600 @ 1.20GHz              | 1         | 2.5%    |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 2.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.5%    |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 2.5%    |
| Intel Celeron CPU 900 @ 2.20GHz               | 1         | 2.5%    |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 1         | 2.5%    |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 2.5%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 2.5%    |
| AMD Turion 64 X2 Mobile Technology TL-64      | 1         | 2.5%    |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 2.5%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.5%    |
| AMD Ryzen 3 5300U with Radeon Graphics        | 1         | 2.5%    |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G  | 1         | 2.5%    |
| AMD C-50 Processor                            | 1         | 2.5%    |
| AMD A4-5000 APU with Radeon HD Graphics       | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 7         | 17.5%   |
| Intel Celeron           | 6         | 15%     |
| Intel Atom              | 6         | 15%     |
| Intel Core 2 Duo        | 4         | 10%     |
| Intel Core i7           | 3         | 7.5%    |
| Intel Core 2            | 2         | 5%      |
| AMD Ryzen 5             | 2         | 5%      |
| Other                   | 1         | 2.5%    |
| Intel Pentium           | 1         | 2.5%    |
| Intel Genuine           | 1         | 2.5%    |
| Intel Core i3           | 1         | 2.5%    |
| AMD Turion 64 X2 Mobile | 1         | 2.5%    |
| AMD Ryzen 7             | 1         | 2.5%    |
| AMD Ryzen 3             | 1         | 2.5%    |
| AMD PRO A10             | 1         | 2.5%    |
| AMD C-50                | 1         | 2.5%    |
| AMD A4                  | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 57.5%   |
| 4      | 12        | 30%     |
| 1      | 4         | 10%     |
| 6      | 1         | 2.5%    |

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
| 2      | 20        | 50%     |
| 1      | 20        | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 36        | 90%     |
| 32-bit         | 4         | 10%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 20%     |
| 0x406c4    | 3         | 7.5%    |
| 0x30678    | 3         | 7.5%    |
| 0x20655    | 3         | 7.5%    |
| 0x6f2      | 2         | 5%      |
| 0x306a9    | 2         | 5%      |
| 0x206a7    | 2         | 5%      |
| 0x106c2    | 2         | 5%      |
| 0x10676    | 2         | 5%      |
| 0x08108109 | 2         | 5%      |
| 0x806ec    | 1         | 2.5%    |
| 0x806ea    | 1         | 2.5%    |
| 0x706a8    | 1         | 2.5%    |
| 0x406c3    | 1         | 2.5%    |
| 0x40651    | 1         | 2.5%    |
| 0x1067a    | 1         | 2.5%    |
| 0x08608103 | 1         | 2.5%    |
| 0x08600106 | 1         | 2.5%    |
| 0x0700010f | 1         | 2.5%    |
| 0x0600611a | 1         | 2.5%    |
| 0x05000029 | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 7         | 17.5%   |
| Core          | 4         | 10%     |
| Westmere      | 3         | 7.5%    |
| Penryn        | 3         | 7.5%    |
| IvyBridge     | 3         | 7.5%    |
| Bonnell       | 3         | 7.5%    |
| Zen+          | 2         | 5%      |
| SandyBridge   | 2         | 5%      |
| KabyLake      | 2         | 5%      |
| Zen 2         | 1         | 2.5%    |
| TigerLake     | 1         | 2.5%    |
| Skylake       | 1         | 2.5%    |
| P6            | 1         | 2.5%    |
| K8 Hammer     | 1         | 2.5%    |
| Jaguar        | 1         | 2.5%    |
| Haswell       | 1         | 2.5%    |
| Goldmont plus | 1         | 2.5%    |
| Excavator     | 1         | 2.5%    |
| Bobcat        | 1         | 2.5%    |
| Unknown       | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 27        | 67.5%   |
| AMD    | 8         | 20%     |
| Nvidia | 5         | 12.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 10.42%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 8.33%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 6.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 6.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 4.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 4.17%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 4.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 4.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 4.17%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 2.08%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 2.08%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 2.08%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 2.08%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 2.08%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.08%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.08%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.08%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.08%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 2.08%   |
| AMD Renoir                                                                               | 1         | 2.08%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 2.08%   |
| AMD Lucienne                                                                             | 1         | 2.08%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| 1 x Intel  | 26        | 65%     |
| 1 x AMD    | 7         | 17.5%   |
| 1 x Nvidia | 5         | 12.5%   |
| 2 x Intel  | 1         | 2.5%    |
| 2 x AMD    | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 39        | 97.5%   |
| Proprietary | 1         | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 75%     |
| 0.01-0.5   | 6         | 15%     |
| 1.01-2.0   | 3         | 7.5%    |
| 0.51-1.0   | 1         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 8         | 20%     |
| AU Optronics        | 6         | 15%     |
| BOE                 | 5         | 12.5%   |
| Chimei Innolux      | 4         | 10%     |
| Samsung Electronics | 3         | 7.5%    |
| CPT                 | 3         | 7.5%    |
| Lenovo              | 2         | 5%      |
| Apple               | 2         | 5%      |
| Sony                | 1         | 2.5%    |
| PANDA               | 1         | 2.5%    |
| Medion              | 1         | 2.5%    |
| LG Philips          | 1         | 2.5%    |
| Insignia            | 1         | 2.5%    |
| Hitachi             | 1         | 2.5%    |
| HannStar            | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sony TV SNY2A03 1920x1080                                            | 1         | 2.44%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch    | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch | 1         | 2.44%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch              | 1         | 2.44%   |
| Medion MD 20310 MED3645 1920x1080 521x293mm 23.5-inch                | 1         | 2.44%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 2.44%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 2.44%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 2.44%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 2.44%   |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch              | 1         | 2.44%   |
| Lenovo LCD Monitor LEN4022 1400x1050 286x214mm 14.1-inch             | 1         | 2.44%   |
| Insignia BBY LCD BBY0032 1920x540                                    | 1         | 2.44%   |
| Hitachi HDMI HEC0088 1920x540                                        | 1         | 2.44%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 1         | 2.44%   |
| CPT LCD Monitor CPT37D5 1920x1200 260x160mm 12.0-inch                | 1         | 2.44%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 2.44%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch     | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch     | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch      | 1         | 2.44%   |
| BOE LCD Monitor BOE08B2 1366x768 309x174mm 14.0-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                | 1         | 2.44%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 1         | 2.44%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE0635 1920x1080 309x173mm 13.9-inch                | 1         | 2.44%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO132C 1366x768 293x164mm 13.2-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch       | 1         | 2.44%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 1         | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 14        | 34.15%  |
| 1366x768 (WXGA)   | 11        | 26.83%  |
| 1280x800 (WXGA)   | 4         | 9.76%   |
| 1600x900 (HD+)    | 3         | 7.32%   |
| 1024x600          | 3         | 7.32%   |
| 1920x540          | 2         | 4.88%   |
| 1440x900 (WXGA+)  | 2         | 4.88%   |
| 1920x1200 (WUXGA) | 1         | 2.44%   |
| 1400x1050         | 1         | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 29.27%  |
| 13     | 8         | 19.51%  |
| 17     | 6         | 14.63%  |
| 14     | 5         | 12.2%   |
| 10     | 3         | 7.32%   |
| 48     | 2         | 4.88%   |
| 72     | 1         | 2.44%   |
| 24     | 1         | 2.44%   |
| 23     | 1         | 2.44%   |
| 16     | 1         | 2.44%   |
| 12     | 1         | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 46.34%  |
| 201-300     | 10        | 24.39%  |
| 351-400     | 7         | 17.07%  |
| 501-600     | 2         | 4.88%   |
| 1001-1500   | 2         | 4.88%   |
| 1501-2000   | 1         | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 30        | 75%     |
| 16/10 | 7         | 17.5%   |
| 1.96  | 2         | 5%      |
| 4/3   | 1         | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 31.71%  |
| 81-90          | 8         | 19.51%  |
| 121-130        | 5         | 12.2%   |
| 71-80          | 4         | 9.76%   |
| 41-50          | 3         | 7.32%   |
| 201-250        | 2         | 4.88%   |
| 501-1000       | 2         | 4.88%   |
| More than 1000 | 1         | 2.44%   |
| 61-70          | 1         | 2.44%   |
| 131-140        | 1         | 2.44%   |
| 91-100         | 1         | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 17        | 42.5%   |
| 121-160 | 14        | 35%     |
| 51-100  | 5         | 12.5%   |
| 1-50    | 3         | 7.5%    |
| 161-240 | 1         | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 37        | 92.5%   |
| 2     | 2         | 5%      |
| 0     | 1         | 2.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 19        | 32.76%  |
| Realtek Semiconductor    | 15        | 25.86%  |
| Qualcomm Atheros         | 8         | 13.79%  |
| Broadcom                 | 5         | 8.62%   |
| Marvell Technology Group | 3         | 5.17%   |
| Broadcom Limited         | 2         | 3.45%   |
| TP-Link                  | 1         | 1.72%   |
| Samsung Electronics      | 1         | 1.72%   |
| Ralink                   | 1         | 1.72%   |
| OPPO Electronics         | 1         | 1.72%   |
| Nvidia                   | 1         | 1.72%   |
| Edimax Technology        | 1         | 1.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 7         | 9.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 5.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 4.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.78%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 2.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.78%   |
| Intel Wireless 7265                                                     | 2         | 2.78%   |
| Intel Wireless 7260                                                     | 2         | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 2.78%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 1.39%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 1.39%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 1.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 1.39%   |
| OPPO OnePlus Nord                                                       | 1         | 1.39%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 1.39%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 1.39%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 1.39%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 1.39%   |
| Intel Wireless 8260                                                     | 1         | 1.39%   |
| Intel WiFi Link 5100                                                    | 1         | 1.39%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.39%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.39%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.39%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.39%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 1.39%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.39%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.39%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.39%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 48.72%  |
| Qualcomm Atheros      | 7         | 17.95%  |
| Realtek Semiconductor | 6         | 15.38%  |
| Broadcom Limited      | 2         | 5.13%   |
| Broadcom              | 2         | 5.13%   |
| TP-Link               | 1         | 2.56%   |
| Ralink                | 1         | 2.56%   |
| Edimax Technology     | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 7.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 5.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 5.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 5.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 5.13%   |
| Intel Wireless 7265                                                     | 2         | 5.13%   |
| Intel Wireless 7260                                                     | 2         | 5.13%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 2.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 2.56%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 2.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 2.56%   |
| Intel Wireless 8260                                                     | 1         | 2.56%   |
| Intel WiFi Link 5100                                                    | 1         | 2.56%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 2.56%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 2.56%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 2.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 2.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 2.56%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 2.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.56%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.56%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 2.56%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 2.56%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 2.56%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 2.56%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 12        | 36.36%  |
| Intel                    | 7         | 21.21%  |
| Qualcomm Atheros         | 4         | 12.12%  |
| Broadcom                 | 4         | 12.12%  |
| Marvell Technology Group | 3         | 9.09%   |
| Samsung Electronics      | 1         | 3.03%   |
| OPPO Electronics         | 1         | 3.03%   |
| Nvidia                   | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 21.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 12.12%  |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 6.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 6.06%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 3.03%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 3.03%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 3.03%   |
| OPPO OnePlus Nord                                                 | 1         | 3.03%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 3.03%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 3.03%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 3.03%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 3.03%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.03%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 3.03%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.03%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 3.03%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 3.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 3.03%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 3.03%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 52.86%  |
| Ethernet | 33        | 47.14%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 71.43%  |
| Ethernet | 12        | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 28        | 70%     |
| 1     | 9         | 22.5%   |
| 0     | 2         | 5%      |
| 3     | 1         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 32        | 76.19%  |
| Yes  | 10        | 23.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 32.14%  |
| Broadcom                        | 5         | 17.86%  |
| Realtek Semiconductor           | 2         | 7.14%   |
| IMC Networks                    | 2         | 7.14%   |
| Apple                           | 2         | 7.14%   |
| Taiyo Yuden                     | 1         | 3.57%   |
| Realtek                         | 1         | 3.57%   |
| Qualcomm Atheros Communications | 1         | 3.57%   |
| Hewlett-Packard                 | 1         | 3.57%   |
| Foxconn / Hon Hai               | 1         | 3.57%   |
| Dell                            | 1         | 3.57%   |
| Cambridge Silicon Radio         | 1         | 3.57%   |
| ASUSTek Computer                | 1         | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 17.86%  |
| IMC Networks Bluetooth Radio                        | 2         | 7.14%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 7.14%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 3.57%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.57%   |
| Realtek Bluetooth Radio                             | 1         | 3.57%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 3.57%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.57%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.57%   |
| Intel AX201 Bluetooth                               | 1         | 3.57%   |
| Intel AX200 Bluetooth                               | 1         | 3.57%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 3.57%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 3.57%   |
| Dell Wireless 365 Bluetooth                         | 1         | 3.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.57%   |
| Broadcom HP Portable SoftSailing                    | 1         | 3.57%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 3.57%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 3.57%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 3.57%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.57%   |
| Apple Bluetooth HCI                                 | 1         | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 29        | 67.44%  |
| AMD                 | 7         | 16.28%  |
| Nvidia              | 3         | 6.98%   |
| Native Instruments  | 1         | 2.33%   |
| Focusrite-Novation  | 1         | 2.33%   |
| C-Media Electronics | 1         | 2.33%   |
| ASUSTek Computer    | 1         | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 12%     |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 6%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 6%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 6%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 6%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 6%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 4%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 4%      |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 4%      |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 2%      |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 2%      |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2%      |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 2%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2%      |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2%      |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 2%      |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 2%      |
| ASUSTek Computer C-Media Audio                                                                    | 1         | 2%      |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2%      |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 2%      |
| AMD FCH Azalia Controller                                                                         | 1         | 2%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 28.57%  |
| Unknown             | 7         | 20%     |
| SK hynix            | 4         | 11.43%  |
| Micron Technology   | 3         | 8.57%   |
| Nanya Technology    | 2         | 5.71%   |
| Kingston            | 2         | 5.71%   |
| Team                | 1         | 2.86%   |
| High Bridge         | 1         | 2.86%   |
| GOODRAM             | 1         | 2.86%   |
| G.Skill             | 1         | 2.86%   |
| Crucial             | 1         | 2.86%   |
| Corsair             | 1         | 2.86%   |
| Unknown             | 1         | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                 | 2         | 5.26%   |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s    | 2         | 5.26%   |
| Unknown RAM Module 2GB SODIMM SDRAM                         | 1         | 2.63%   |
| Unknown RAM Module 2GB SODIMM DDR2 266MT/s                  | 1         | 2.63%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                    | 1         | 2.63%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                  | 1         | 2.63%   |
| Unknown RAM Module 1024MB SODIMM DDR2                       | 1         | 2.63%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                    | 1         | 2.63%   |
| Team RAM TEAMGROUP-SD4-3200 8192MB SODIMM DDR4 3200MT/s     | 1         | 2.63%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                | 1         | 2.63%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 1         | 2.63%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 1         | 2.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 1         | 2.63%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 2.63%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 1         | 2.63%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s    | 1         | 2.63%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s       | 1         | 2.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 2.63%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s       | 1         | 2.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 1         | 2.63%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 1         | 2.63%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s             | 1         | 2.63%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s        | 1         | 2.63%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s        | 1         | 2.63%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s  | 1         | 2.63%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s       | 1         | 2.63%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s   | 1         | 2.63%   |
| Kingston RAM Module 4GB SODIMM DDR3 800MT/s                 | 1         | 2.63%   |
| Kingston RAM ACR16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s      | 1         | 2.63%   |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s    | 1         | 2.63%   |
| High Bridge RAM HB3SU004GFM8MML33. 4GB SODIMM DDR3 1333MT/s | 1         | 2.63%   |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s      | 1         | 2.63%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s      | 1         | 2.63%   |
| Crucial RAM CB8GS2666.C8RT 8GB SODIMM DDR4 2667MT/s         | 1         | 2.63%   |
| Corsair RAM CMSA4GX3M1A1333C9 4GB SODIMM DDR3 1333MT/s      | 1         | 2.63%   |
| Unknown                                                     | 1         | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 16        | 53.33%  |
| DDR4    | 7         | 23.33%  |
| DDR2    | 3         | 10%     |
| SDRAM   | 2         | 6.67%   |
| LPDDR3  | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 93.1%   |
| Row Of Chips | 1         | 3.45%   |
| Unknown      | 1         | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 11        | 30.56%  |
| 4096  | 10        | 27.78%  |
| 8192  | 6         | 16.67%  |
| 1024  | 4         | 11.11%  |
| 16384 | 3         | 8.33%   |
| 32768 | 1         | 2.78%   |
| 256   | 1         | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 9         | 27.27%  |
| 2667    | 4         | 12.12%  |
| 3200    | 3         | 9.09%   |
| 1334    | 3         | 9.09%   |
| 1333    | 3         | 9.09%   |
| 1066    | 3         | 9.09%   |
| 800     | 2         | 6.06%   |
| Unknown | 2         | 6.06%   |
| 4199    | 1         | 3.03%   |
| 1867    | 1         | 3.03%   |
| 533     | 1         | 3.03%   |
| 266     | 1         | 3.03%   |

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
| Chicony Electronics                    | 10        | 29.41%  |
| Suyin                                  | 4         | 11.76%  |
| Microdia                               | 4         | 11.76%  |
| Sunplus Innovation Technology          | 2         | 5.88%   |
| Quanta                                 | 2         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.88%   |
| Bison Electronics                      | 2         | 5.88%   |
| Alcor Micro                            | 2         | 5.88%   |
| Acer                                   | 2         | 5.88%   |
| Z-Star Microelectronics                | 1         | 2.94%   |
| Sonix Technology                       | 1         | 2.94%   |
| Microsoft                              | 1         | 2.94%   |
| Apple                                  | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                           | 2         | 5.88%   |
| Alcor Micro USB 2.0 PC cam                                  | 2         | 5.88%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 2.94%   |
| Suyin USB2.0 UVC 1.3M WebCam                                | 1         | 2.94%   |
| Suyin HP Truevision HD                                      | 1         | 2.94%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 2.94%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 2.94%   |
| Sunplus Integrated Webcam                                   | 1         | 2.94%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 2.94%   |
| Sonix USB2.0 HD UVC WebCam                                  | 1         | 2.94%   |
| Quanta HP TrueVision HD Camera                              | 1         | 2.94%   |
| Quanta HD User Facing                                       | 1         | 2.94%   |
| Microsoft LifeCam Cinema                                    | 1         | 2.94%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 2.94%   |
| Microdia Lenovo EasyCamera                                  | 1         | 2.94%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 2.94%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 2.94%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 2.94%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 2.94%   |
| Chicony HP Webcam [2 MP Macro]                              | 1         | 2.94%   |
| Chicony HP TrueVision HD Camera                             | 1         | 2.94%   |
| Chicony HP Integrated Webcam                                | 1         | 2.94%   |
| Chicony HP HD Webcam                                        | 1         | 2.94%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 2.94%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera            | 1         | 2.94%   |
| Bison USB HD Webcam                                         | 1         | 2.94%   |
| Bison HD Webcam                                             | 1         | 2.94%   |
| Apple FaceTime HD Camera                                    | 1         | 2.94%   |
| Acer Lenovo EasyCamera                                      | 1         | 2.94%   |
| Acer HP Webcam                                              | 1         | 2.94%   |

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
| 0     | 23        | 57.5%   |
| 1     | 14        | 35%     |
| 2     | 3         | 7.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 7         | 31.82%  |
| Graphics card         | 5         | 22.73%  |
| Net/wireless          | 4         | 18.18%  |
| Multimedia controller | 4         | 18.18%  |
| Chipcard              | 1         | 4.55%   |
| Bluetooth             | 1         | 4.55%   |

