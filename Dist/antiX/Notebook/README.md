antiX - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for antiX.

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

Total: 32

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop X509... | [abaa4456ea](https://linux-hardware.org/?probe=abaa4456ea) | Jun 01, 2022 |
| Lenovo        | G550 2958                   | [af5cc85e39](https://linux-hardware.org/?probe=af5cc85e39) | May 20, 2022 |
| Acer          | Aspire 5920G                | [b2ffc81ed6](https://linux-hardware.org/?probe=b2ffc81ed6) | May 07, 2022 |
| Packard Be... | EasyNote_MX37-U-057NL       | [41760b3852](https://linux-hardware.org/?probe=41760b3852) | Apr 27, 2022 |
| Apple         | MacBook7,1                  | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| HP            | EliteBook 2570p             | [20e998c205](https://linux-hardware.org/?probe=20e998c205) | Mar 17, 2022 |
| IBM           | ThinkPad T40 237342G        | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Toshiba       | Satellite 1905              | [e72b9043c8](https://linux-hardware.org/?probe=e72b9043c8) | Jan 14, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [b2a71d3bbe](https://linux-hardware.org/?probe=b2a71d3bbe) | Dec 30, 2021 |
| ASUSTek       | X71SL                       | [42e7b57eb8](https://linux-hardware.org/?probe=42e7b57eb8) | Dec 07, 2021 |
| ASUSTek       | A3L                         | [32489f1764](https://linux-hardware.org/?probe=32489f1764) | Dec 06, 2021 |
| ASUSTek       | A3L                         | [2b01c636c2](https://linux-hardware.org/?probe=2b01c636c2) | Dec 06, 2021 |
| ASUSTek       | X51RL                       | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| Acer          | AOA150                      | [24833c6a59](https://linux-hardware.org/?probe=24833c6a59) | Oct 26, 2021 |
| Dell          | Latitude E6400              | [6b7ef9cad5](https://linux-hardware.org/?probe=6b7ef9cad5) | Oct 21, 2021 |
| MSI           | GE62 7RE                    | [9d064bcc8d](https://linux-hardware.org/?probe=9d064bcc8d) | May 21, 2021 |
| MSI           | GE62 7RE                    | [d560e067d4](https://linux-hardware.org/?probe=d560e067d4) | May 21, 2021 |
| HP            | EliteBook 8770w             | [0af42b4958](https://linux-hardware.org/?probe=0af42b4958) | Mar 17, 2021 |
| Fujitsu       | FMVS54EB                    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell          | Latitude 5480               | [c9e0b19e8b](https://linux-hardware.org/?probe=c9e0b19e8b) | Mar 07, 2021 |
| HP            | Mini 110-3700               | [33a6e65493](https://linux-hardware.org/?probe=33a6e65493) | Jan 06, 2021 |
| IBM           | ThinkPad T41 2374K50        | [c77530ec4e](https://linux-hardware.org/?probe=c77530ec4e) | Nov 19, 2020 |
| IBM           | ThinkPad T41 2374K50        | [9c27b878ae](https://linux-hardware.org/?probe=9c27b878ae) | Nov 17, 2020 |
| IBM           | ThinkPad T43 2668WEJ        | [c7508c3b5c](https://linux-hardware.org/?probe=c7508c3b5c) | Oct 02, 2020 |
| HP            | Pavilion dv2700             | [312d41f446](https://linux-hardware.org/?probe=312d41f446) | Aug 01, 2020 |
| HP            | Mini 5101                   | [c0abbe79e6](https://linux-hardware.org/?probe=c0abbe79e6) | Apr 24, 2020 |
| HP            | Mini 5101                   | [8fd41129bc](https://linux-hardware.org/?probe=8fd41129bc) | Apr 24, 2020 |
| ASUSTek       | 900A                        | [9ab5761eb1](https://linux-hardware.org/?probe=9ab5761eb1) | Apr 05, 2020 |
| ASUSTek       | 900HA                       | [39b2bfbefc](https://linux-hardware.org/?probe=39b2bfbefc) | Mar 21, 2020 |
| Medion        | WIM2170                     | [a8c4771b62](https://linux-hardware.org/?probe=a8c4771b62) | Jan 13, 2020 |
| Medion        | WIM2170                     | [c879195021](https://linux-hardware.org/?probe=c879195021) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| antiX 21       | 9         | 34.62%  |
| antiX 19.2     | 6         | 23.08%  |
| antiX 19.3     | 3         | 11.54%  |
| antiX 19.4     | 2         | 7.69%   |
| antiX 19.1     | 2         | 7.69%   |
| antiX 21-runit | 1         | 3.85%   |
| antiX 17.4.1   | 1         | 3.85%   |
| antiX 17.2.1   | 1         | 3.85%   |
| antiX 17       | 1         | 3.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 26        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 4         | 15.38%  |
| 5.10.57-antix.1-amd64-smp    | 3         | 11.54%  |
| 4.9.235-antix.1-amd64-smp    | 2         | 7.69%   |
| 4.9.212-antix.1-amd64-smp    | 2         | 7.69%   |
| 4.9.212-antix.1-486-smp      | 2         | 7.69%   |
| 4.9.200-antix.1-486-smp      | 2         | 7.69%   |
| 4.9.0-279-antix.1-amd64-smp  | 2         | 7.69%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 3.85%   |
| 5.10.88-antix.1-amd64-smp    | 1         | 3.85%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 3.85%   |
| 4.9.160-antix.2-486-smp      | 1         | 3.85%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 3.85%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 3.85%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 3.85%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 3.85%   |
| 4.10.5-antix.1-486-smp       | 1         | 3.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 7         | 26.92%  |
| 4.9.212  | 4         | 15.38%  |
| 5.10.57  | 3         | 11.54%  |
| 4.9.235  | 2         | 7.69%   |
| 4.9.200  | 2         | 7.69%   |
| 4.9.160  | 2         | 7.69%   |
| 5.14.0   | 1         | 3.85%   |
| 5.10.88  | 1         | 3.85%   |
| 5.10.27  | 1         | 3.85%   |
| 4.19.202 | 1         | 3.85%   |
| 4.19.100 | 1         | 3.85%   |
| 4.10.5   | 1         | 3.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 17        | 65.38%  |
| 5.10    | 5         | 19.23%  |
| 4.19    | 2         | 7.69%   |
| 5.14    | 1         | 3.85%   |
| 4.10    | 1         | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 13        | 50%     |
| i686   | 13        | 50%     |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 14        | 53.85%  |
| icewm   | 10        | 38.46%  |
| XFCE    | 1         | 3.85%   |
| GNOME   | 1         | 3.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 26        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 15        | 57.69%  |
| Unknown | 8         | 30.77%  |
| SLIMSKI | 1         | 3.85%   |
| SDDM    | 1         | 3.85%   |
| LightDM | 1         | 3.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 10        | 38.46%  |
| de_DE | 3         | 11.54%  |
| ru_RU | 2         | 7.69%   |
| ja_JP | 2         | 7.69%   |
| en_AU | 2         | 7.69%   |
| uk_UA | 1         | 3.85%   |
| pt_BR | 1         | 3.85%   |
| nl_NL | 1         | 3.85%   |
| it_IT | 1         | 3.85%   |
| es_VE | 1         | 3.85%   |
| es_MX | 1         | 3.85%   |
| en_GB | 1         | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 21        | 80.77%  |
| EFI  | 5         | 19.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 21        | 80.77%  |
| Overlay  | 4         | 15.38%  |
| Reiserfs | 1         | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 20        | 76.92%  |
| GPT     | 5         | 19.23%  |
| Unknown | 1         | 3.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 80.77%  |
| Yes       | 5         | 19.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 61.54%  |
| Yes       | 10        | 38.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 6         | 23.08%  |
| Hewlett-Packard  | 5         | 19.23%  |
| IBM              | 3         | 11.54%  |
| Lenovo           | 2         | 7.69%   |
| Dell             | 2         | 7.69%   |
| Acer             | 2         | 7.69%   |
| Toshiba          | 1         | 3.85%   |
| Packard Bell     | 1         | 3.85%   |
| MSI              | 1         | 3.85%   |
| Medion           | 1         | 3.85%   |
| Fujitsu          | 1         | 3.85%   |
| Apple            | 1         | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Toshiba Satellite 1905             | 1         | 3.85%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 3.85%   |
| MSI GE62 7RE                       | 1         | 3.85%   |
| Medion WIM2170                     | 1         | 3.85%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 3.85%   |
| Lenovo G550 2958                   | 1         | 3.85%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 3.85%   |
| IBM ThinkPad T41 2374K50           | 1         | 3.85%   |
| IBM ThinkPad T40 237342G           | 1         | 3.85%   |
| HP Pavilion dv2700                 | 1         | 3.85%   |
| HP Mini 5101                       | 1         | 3.85%   |
| HP Mini 110-3700                   | 1         | 3.85%   |
| HP EliteBook 8770w                 | 1         | 3.85%   |
| HP EliteBook 2570p                 | 1         | 3.85%   |
| Fujitsu FMVS54EB                   | 1         | 3.85%   |
| Dell Latitude E6400                | 1         | 3.85%   |
| Dell Latitude 5480                 | 1         | 3.85%   |
| ASUS X71SL                         | 1         | 3.85%   |
| ASUS X51RL                         | 1         | 3.85%   |
| ASUS VivoBook_ASUSLaptop X509MA    | 1         | 3.85%   |
| ASUS A3L                           | 1         | 3.85%   |
| ASUS 900HA                         | 1         | 3.85%   |
| ASUS 900A                          | 1         | 3.85%   |
| Apple MacBook7,1                   | 1         | 3.85%   |
| Acer Aspire 5920G                  | 1         | 3.85%   |
| Acer AOA150                        | 1         | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| IBM ThinkPad          | 3         | 11.54%  |
| HP Mini               | 2         | 7.69%   |
| HP EliteBook          | 2         | 7.69%   |
| Dell Latitude         | 2         | 7.69%   |
| Toshiba Satellite     | 1         | 3.85%   |
| Packard Bell EasyNote | 1         | 3.85%   |
| MSI GE62              | 1         | 3.85%   |
| Medion WIM2170        | 1         | 3.85%   |
| Lenovo ThinkPad       | 1         | 3.85%   |
| Lenovo G550           | 1         | 3.85%   |
| HP Pavilion           | 1         | 3.85%   |
| Fujitsu FMVS54EB      | 1         | 3.85%   |
| ASUS X71SL            | 1         | 3.85%   |
| ASUS X51RL            | 1         | 3.85%   |
| ASUS VivoBook         | 1         | 3.85%   |
| ASUS A3L              | 1         | 3.85%   |
| ASUS 900HA            | 1         | 3.85%   |
| ASUS 900A             | 1         | 3.85%   |
| Apple MacBook7        | 1         | 3.85%   |
| Acer Aspire           | 1         | 3.85%   |
| Acer AOA150           | 1         | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2009 | 4         | 15.38%  |
| 2008 | 4         | 15.38%  |
| 2007 | 4         | 15.38%  |
| 2013 | 2         | 7.69%   |
| 2012 | 2         | 7.69%   |
| 2005 | 2         | 7.69%   |
| 2003 | 2         | 7.69%   |
| 2020 | 1         | 3.85%   |
| 2017 | 1         | 3.85%   |
| 2016 | 1         | 3.85%   |
| 2011 | 1         | 3.85%   |
| 2010 | 1         | 3.85%   |
| 2004 | 1         | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 26        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 26        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 7         | 26.92%  |
| 0.51-1.0   | 6         | 23.08%  |
| 1.01-2.0   | 5         | 19.23%  |
| 32.01-64.0 | 2         | 7.69%   |
| 2.01-3.0   | 2         | 7.69%   |
| 8.01-16.0  | 2         | 7.69%   |
| 4.01-8.0   | 1         | 3.85%   |
| 16.01-24.0 | 1         | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 10        | 38.46%  |
| 0.01-0.5 | 9         | 34.62%  |
| 1.01-2.0 | 4         | 15.38%  |
| 2.01-3.0 | 3         | 11.54%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 84.62%  |
| 2      | 3         | 11.54%  |
| 3      | 1         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 61.54%  |
| No        | 10        | 38.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 92.31%  |
| No        | 2         | 7.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 96.15%  |
| No        | 1         | 3.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 65.38%  |
| Yes       | 9         | 34.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 5         | 19.23%  |
| Germany     | 4         | 15.38%  |
| Russia      | 3         | 11.54%  |
| Japan       | 2         | 7.69%   |
| Australia   | 2         | 7.69%   |
| Ukraine     | 1         | 3.85%   |
| Netherlands | 1         | 3.85%   |
| Mexico      | 1         | 3.85%   |
| Kenya       | 1         | 3.85%   |
| Kazakhstan  | 1         | 3.85%   |
| Italy       | 1         | 3.85%   |
| Hungary     | 1         | 3.85%   |
| Denmark     | 1         | 3.85%   |
| Chile       | 1         | 3.85%   |
| Brazil      | 1         | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Sydney                    | 2         | 7.69%   |
| Moscow                    | 2         | 7.69%   |
| Yuzhno-Sakhalinsk         | 1         | 3.85%   |
| Yokohama                  | 1         | 3.85%   |
| Toms River                | 1         | 3.85%   |
| Schloss Holte-Stukenbrock | 1         | 3.85%   |
| Santiago                  | 1         | 3.85%   |
| Salto                     | 1         | 3.85%   |
| Rotterdam                 | 1         | 3.85%   |
| Reutlingen                | 1         | 3.85%   |
| Portland                  | 1         | 3.85%   |
| Norden                    | 1         | 3.85%   |
| Neyagawa                  | 1         | 3.85%   |
| Nairobi                   | 1         | 3.85%   |
| Mittegrossefehn           | 1         | 3.85%   |
| Mechanicsburg             | 1         | 3.85%   |
| Karaganda                 | 1         | 3.85%   |
| Jonesboro                 | 1         | 3.85%   |
| Inveruno                  | 1         | 3.85%   |
| El Cerrito                | 1         | 3.85%   |
| Dnipro                    | 1         | 3.85%   |
| Copenhagen                | 1         | 3.85%   |
| Celaya                    | 1         | 3.85%   |
| Budapest                  | 1         | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 7      | 23.33%  |
| Seagate             | 6         | 6      | 20%     |
| WDC                 | 4         | 4      | 13.33%  |
| Toshiba             | 2         | 2      | 6.67%   |
| Samsung Electronics | 2         | 2      | 6.67%   |
| Kingston            | 2         | 2      | 6.67%   |
| Zheino              | 1         | 1      | 3.33%   |
| Unknown             | 1         | 1      | 3.33%   |
| OCZ                 | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |
| Hewlett-Packard     | 1         | 1      | 3.33%   |
| ASUS-PHISON         | 1         | 1      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB        | 2         | 6.67%   |
| Zheino CHN mSATAM3 128 128GB SSD | 1         | 3.33%   |
| WDC WD5000LPLX-08ZNTT0 500GB     | 1         | 3.33%   |
| WDC WD3200BEVT-60ZCT1 320GB      | 1         | 3.33%   |
| WDC WD3200BEVT-22ZCT0 320GB      | 1         | 3.33%   |
| WDC WD1200BEVE-00A0HT0 120GB     | 1         | 3.33%   |
| Unknown SR64G  64GB              | 1         | 3.33%   |
| Toshiba THNSNJ256G8NY 256GB SSD  | 1         | 3.33%   |
| Toshiba MK2576GSX 250GB          | 1         | 3.33%   |
| Seagate ST9160411AS 160GB        | 1         | 3.33%   |
| Seagate ST9160314AS 160GB        | 1         | 3.33%   |
| Seagate ST9160310AS 160GB        | 1         | 3.33%   |
| Seagate ST9160301AS 160GB        | 1         | 3.33%   |
| Seagate ST500LM030-1RK17D 500GB  | 1         | 3.33%   |
| Seagate ST500LM021-1KJ152 500GB  | 1         | 3.33%   |
| OCZ AGILITY3 120GB SSD           | 1         | 3.33%   |
| Kingston SUV500MS120G 120GB SSD  | 1         | 3.33%   |
| Kingston SUV400S37120G 120GB SSD | 1         | 3.33%   |
| Intel SSDSC2BW180A3H 180GB       | 1         | 3.33%   |
| Hitachi HTS725050A7E630 500GB    | 1         | 3.33%   |
| Hitachi HTS723232A7A364 320GB    | 1         | 3.33%   |
| Hitachi HTS721060G9AT00 64GB     | 1         | 3.33%   |
| Hitachi HTS548040M9AT00 40GB     | 1         | 3.33%   |
| Hitachi HTS545025B9A300 250GB    | 1         | 3.33%   |
| Hitachi HTS542525K9SA00 250GB    | 1         | 3.33%   |
| Hitachi HTS541612J9SA00 120GB    | 1         | 3.33%   |
| HGST HTS721010A9E630 1TB         | 1         | 3.33%   |
| HP SSD S750 512GB                | 1         | 3.33%   |
| ASUS-PHISON SSD 8GB              | 1         | 3.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 7         | 7      | 36.84%  |
| Seagate | 6         | 6      | 31.58%  |
| WDC     | 4         | 4      | 21.05%  |
| Toshiba | 1         | 1      | 5.26%   |
| HGST    | 1         | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 20%     |
| Kingston            | 2         | 2      | 20%     |
| Zheino              | 1         | 1      | 10%     |
| Toshiba             | 1         | 1      | 10%     |
| OCZ                 | 1         | 1      | 10%     |
| Intel               | 1         | 1      | 10%     |
| Hewlett-Packard     | 1         | 1      | 10%     |
| ASUS-PHISON         | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 19     | 63.33%  |
| SSD  | 10        | 10     | 33.33%  |
| MMC  | 1         | 1      | 3.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 26        | 29     | 96.3%   |
| MMC  | 1         | 1      | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 27     | 92.86%  |
| 0.51-1.0   | 2         | 2      | 7.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 10        | 38.46%  |
| 21-50      | 4         | 15.38%  |
| 1-20       | 4         | 15.38%  |
| 51-100     | 4         | 15.38%  |
| 251-500    | 2         | 7.69%   |
| 501-1000   | 1         | 3.85%   |
| Unknown    | 1         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 18        | 69.23%  |
| 21-50   | 3         | 11.54%  |
| 101-250 | 2         | 7.69%   |
| 51-100  | 2         | 7.69%   |
| Unknown | 1         | 3.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-60ZCT1 320GB   | 1         | 1      | 11.11%  |
| Seagate ST9160314AS 160GB     | 1         | 1      | 11.11%  |
| Seagate ST9160310AS 160GB     | 1         | 1      | 11.11%  |
| Hitachi HTS725050A7E630 500GB | 1         | 1      | 11.11%  |
| Hitachi HTS723232A7A364 320GB | 1         | 1      | 11.11%  |
| Hitachi HTS721060G9AT00 64GB  | 1         | 1      | 11.11%  |
| Hitachi HTS548040M9AT00 40GB  | 1         | 1      | 11.11%  |
| Hitachi HTS542525K9SA00 250GB | 1         | 1      | 11.11%  |
| Hitachi HTS541612J9SA00 120GB | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 6         | 6      | 66.67%  |
| Seagate | 2         | 2      | 22.22%  |
| WDC     | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 6         | 6      | 66.67%  |
| Seagate | 2         | 2      | 22.22%  |
| WDC     | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 100%    |

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
| Works    | 16        | 18     | 57.14%  |
| Malfunc  | 9         | 9      | 32.14%  |
| Detected | 3         | 3      | 10.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 22        | 78.57%  |
| Silicon Integrated Systems [SiS] | 2         | 7.14%   |
| Silicon Image                    | 1         | 3.57%   |
| Nvidia                           | 1         | 3.57%   |
| JMicron Technology               | 1         | 3.57%   |
| AMD                              | 1         | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 8.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 8.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 8.57%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 3         | 8.57%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 5.71%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 5.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 5.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 5.71%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 2.86%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 2.86%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.86%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 2.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 2.86%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 2.86%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.86%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 2.86%   |
| AMD SB600 IDE                                                                  | 1         | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| IDE  | 15        | 46.88%  |
| SATA | 14        | 43.75%  |
| RAID | 3         | 9.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 100%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 3         | 11.54%  |
| Intel Pentium M processor 1.60GHz           | 2         | 7.69%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 2         | 7.69%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 7.69%   |
| Intel Pentium M processor 1600MHz           | 1         | 3.85%   |
| Intel Pentium M processor 1.86GHz           | 1         | 3.85%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 3.85%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 3.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 3.85%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 3.85%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 3.85%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 3.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 3.85%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 3.85%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz        | 1         | 3.85%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz        | 1         | 3.85%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 3.85%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz | 1         | 3.85%   |
| Intel Celeron CPU 540 @ 1.86GHz             | 1         | 3.85%   |
| Intel Atom CPU N455 @ 1.66GHz               | 1         | 3.85%   |
| Intel Atom CPU N280 @ 1.66GHz               | 1         | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core 2 Duo        | 6         | 23.08%  |
| Intel Atom              | 5         | 19.23%  |
| Intel Pentium M         | 4         | 15.38%  |
| Intel Core i7           | 3         | 11.54%  |
| Intel Core i5           | 2         | 7.69%   |
| Intel Celeron           | 2         | 7.69%   |
| Intel Pentium Dual      | 1         | 3.85%   |
| Intel Pentium 4         | 1         | 3.85%   |
| Intel Core i3           | 1         | 3.85%   |
| Intel Celeron Dual-Core | 1         | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 50%     |
| 1      | 11        | 42.31%  |
| 4      | 2         | 7.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 15        | 57.69%  |
| 2      | 11        | 42.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 17        | 65.38%  |
| 32-bit         | 9         | 34.62%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 0x6fd   | 4         | 15.38%  |
| 0x106c2 | 4         | 15.38%  |
| 0x1067a | 4         | 15.38%  |
| 0x6d6   | 2         | 7.69%   |
| 0x306a9 | 2         | 7.69%   |
| 0xf24   | 1         | 3.85%   |
| 0x906e9 | 1         | 3.85%   |
| 0x806e9 | 1         | 3.85%   |
| 0x706a1 | 1         | 3.85%   |
| 0x6d8   | 1         | 3.85%   |
| 0x695   | 1         | 3.85%   |
| 0x306c3 | 1         | 3.85%   |
| 0x206a7 | 1         | 3.85%   |
| 0x106ca | 1         | 3.85%   |
| 0x10661 | 1         | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Core          | 5         | 19.23%  |
| Bonnell       | 5         | 19.23%  |
| Penryn        | 4         | 15.38%  |
| P6            | 4         | 15.38%  |
| KabyLake      | 2         | 7.69%   |
| IvyBridge     | 2         | 7.69%   |
| SandyBridge   | 1         | 3.85%   |
| NetBurst      | 1         | 3.85%   |
| Haswell       | 1         | 3.85%   |
| Goldmont plus | 1         | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 15        | 55.56%  |
| AMD                              | 6         | 22.22%  |
| Nvidia                           | 5         | 18.52%  |
| Silicon Integrated Systems [SiS] | 1         | 3.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 4         | 12.5%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 4         | 12.5%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 6.25%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 6.25%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 3.13%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 3.13%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 3.13%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 3.13%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 3.13%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 3.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 3.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 3.13%   |
| Intel HD Graphics 630                                                         | 1         | 3.13%   |
| Intel HD Graphics 620                                                         | 1         | 3.13%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 3.13%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 3.13%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 1         | 3.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 3.13%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 3.13%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 3.13%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 3.13%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 3.13%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 50%     |
| 1 x AMD        | 6         | 23.08%  |
| 1 x Nvidia     | 4         | 15.38%  |
| Other          | 1         | 3.85%   |
| 1 x SiS        | 1         | 3.85%   |
| Intel + Nvidia | 1         | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 23        | 88.46%  |
| Unknown     | 2         | 7.69%   |
| Proprietary | 1         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 15        | 57.69%  |
| Unknown    | 7         | 26.92%  |
| 1.01-2.0   | 3         | 11.54%  |
| 3.01-4.0   | 1         | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 6         | 31.58%  |
| LG Display          | 4         | 21.05%  |
| Samsung Electronics | 3         | 15.79%  |
| HannStar            | 2         | 10.53%  |
| LG Philips          | 1         | 5.26%   |
| Chimei Innolux      | 1         | 5.26%   |
| BOE                 | 1         | 5.26%   |
| Apple               | 1         | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 1         | 5.26%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 1         | 5.26%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 286x179mm 13.3-inch | 1         | 5.26%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch          | 1         | 5.26%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch        | 1         | 5.26%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 1         | 5.26%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch          | 1         | 5.26%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch          | 1         | 5.26%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 1         | 5.26%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch             | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 5.26%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch        | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch        | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch        | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch         | 1         | 5.26%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch               | 1         | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 7         | 36.84%  |
| 1280x800 (WXGA)  | 4         | 21.05%  |
| 1920x1080 (FHD)  | 3         | 15.79%  |
| 1024x600         | 3         | 15.79%  |
| 1440x900 (WXGA+) | 2         | 10.53%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 6         | 31.58%  |
| 13     | 4         | 21.05%  |
| 14     | 3         | 15.79%  |
| 17     | 2         | 10.53%  |
| 10     | 2         | 10.53%  |
| 8      | 2         | 10.53%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 10        | 52.63%  |
| 201-300     | 5         | 26.32%  |
| 351-400     | 2         | 10.53%  |
| 101-200     | 2         | 10.53%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 12        | 63.16%  |
| 16/10 | 7         | 36.84%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 6         | 31.58%  |
| 81-90          | 5         | 26.32%  |
| 71-80          | 2         | 10.53%  |
| 41-50          | 2         | 10.53%  |
| 1-40           | 2         | 10.53%  |
| 131-140        | 1         | 5.26%   |
| 121-130        | 1         | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 8         | 42.11%  |
| 121-160 | 7         | 36.84%  |
| 51-100  | 4         | 21.05%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 25        | 96.15%  |
| 0     | 1         | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Qualcomm Atheros                 | 12        | 27.27%  |
| Intel                            | 12        | 27.27%  |
| Realtek Semiconductor            | 6         | 13.64%  |
| Broadcom                         | 6         | 13.64%  |
| Silicon Integrated Systems [SiS] | 2         | 4.55%   |
| Marvell Technology Group         | 2         | 4.55%   |
| Ralink                           | 1         | 2.27%   |
| Qualcomm Atheros Communications  | 1         | 2.27%   |
| Nvidia                           | 1         | 2.27%   |
| Hewlett-Packard                  | 1         | 2.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 5         | 8.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 5.26%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 3.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 3.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 3.51%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 2         | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 3.51%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 3.51%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 3.51%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 2         | 3.51%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 1.75%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.75%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.75%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.75%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.75%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 1.75%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 1.75%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 1.75%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.75%   |
| Intel Wireless 7260                                                           | 1         | 1.75%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.75%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 1.75%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 1.75%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.75%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.75%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.75%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 1.75%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.75%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller              | 1         | 1.75%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                                  | 1         | 1.75%   |
| Intel 82801BA/BAM AC'97 Modem Controller                                      | 1         | 1.75%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 1.75%   |
| HP lt2523 Mobile Broadband Device                                             | 1         | 1.75%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                      | 1         | 1.75%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 1.75%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 1         | 1.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 10        | 37.04%  |
| Intel                           | 10        | 37.04%  |
| Broadcom                        | 4         | 14.81%  |
| Realtek Semiconductor           | 1         | 3.7%    |
| Ralink                          | 1         | 3.7%    |
| Qualcomm Atheros Communications | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 5         | 17.86%  |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 7.14%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 2         | 7.14%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 3.57%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 3.57%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 3.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 3.57%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 3.57%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 3.57%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 3.57%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 3.57%   |
| Intel Wireless 7260                                                           | 1         | 3.57%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 3.57%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 3.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 3.57%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 3.57%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 3.57%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 3.57%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 3.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8         | 33.33%  |
| Realtek Semiconductor            | 5         | 20.83%  |
| Qualcomm Atheros                 | 3         | 12.5%   |
| Broadcom                         | 3         | 12.5%   |
| Silicon Integrated Systems [SiS] | 2         | 8.33%   |
| Marvell Technology Group         | 2         | 8.33%   |
| Nvidia                           | 1         | 4.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller          | 3         | 12.5%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter  | 2         | 8.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter          | 2         | 8.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet | 2         | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)          | 2         | 8.33%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)             | 2         | 8.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller      | 1         | 4.17%   |
| Nvidia MCP89 Ethernet                                          | 1         | 4.17%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller        | 1         | 4.17%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller           | 1         | 4.17%   |
| Intel Ethernet Connection I217-LM                              | 1         | 4.17%   |
| Intel Ethernet Connection (4) I219-LM                          | 1         | 4.17%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                   | 1         | 4.17%   |
| Intel 82567LM Gigabit Network Connection                       | 1         | 4.17%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express       | 1         | 4.17%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express            | 1         | 4.17%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express         | 1         | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 46.3%   |
| Ethernet | 24        | 44.44%  |
| Modem    | 5         | 9.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 87.5%   |
| Ethernet | 3         | 12.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 23        | 88.46%  |
| 1     | 3         | 11.54%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 21        | 80.77%  |
| Yes  | 5         | 19.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Broadcom          | 3         | 33.33%  |
| Intel             | 2         | 22.22%  |
| Ralink Technology | 1         | 11.11%  |
| IMC Networks      | 1         | 11.11%  |
| ASUSTek Computer  | 1         | 11.11%  |
| Apple             | 1         | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Broadcom HP Portable SoftSailing             | 2         | 22.22%  |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter | 1         | 11.11%  |
| Intel Wireless-AC 3168 Bluetooth             | 1         | 11.11%  |
| Intel Bluetooth wireless interface           | 1         | 11.11%  |
| IMC Networks Bluetooth Device                | 1         | 11.11%  |
| Broadcom BCM20702A0 Bluetooth 4.0            | 1         | 11.11%  |
| ASUS BT-253 Bluetooth Adapter                | 1         | 11.11%  |
| Apple Bluetooth Host Controller              | 1         | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 22        | 78.57%  |
| Silicon Integrated Systems [SiS] | 2         | 7.14%   |
| Nvidia                           | 2         | 7.14%   |
| AMD                              | 2         | 7.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 17.24%  |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 10.34%  |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 3         | 10.34%  |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 6.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 6.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 6.9%    |
| Nvidia MCP89 High Definition Audio                                         | 1         | 3.45%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 3.45%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 3.45%   |
| Intel CM238 HD Audio Controller                                            | 1         | 3.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 3.45%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 3.45%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 3.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 3.45%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 3.45%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 3.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 11        | 40.74%  |
| SK Hynix            | 6         | 22.22%  |
| Samsung Electronics | 2         | 7.41%   |
| Micron Technology   | 2         | 7.41%   |
| Kingston            | 2         | 7.41%   |
| Unknown (8A02)      | 1         | 3.7%    |
| Crucial             | 1         | 3.7%    |
| Avant               | 1         | 3.7%    |
| Unknown             | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 10.34%  |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 6.9%    |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 3.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 3.45%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 3.45%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 3.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 3.45%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 3.45%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 3.45%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 3.45%   |
| SK Hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 3.45%   |
| SK Hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 3.45%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s           | 1         | 3.45%   |
| SK Hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 3.45%   |
| SK Hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 3.45%   |
| SK Hynix RAM HMT112S6BFR6C-G7 1GB SODIMM 1067MT/s              | 1         | 3.45%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 3.45%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s       | 1         | 3.45%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 3.45%   |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 3.45%   |
| Micron RAM 8HTF12864HDY-800G1 1024MB SODIMM DDR2 800MT/s       | 1         | 3.45%   |
| Kingston RAM MSI24D4S7D8MB-16 16GB SODIMM DDR4 2400MT/s        | 1         | 3.45%   |
| Kingston RAM 9905428-095.D00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 3.45%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 1         | 3.45%   |
| Avant RAM H641GU67F1600G 8GB SODIMM DDR3 1600MT/s              | 1         | 3.45%   |
| Unknown                                                        | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| SDRAM | 6         | 25%     |
| DDR3  | 6         | 25%     |
| DDR2  | 5         | 20.83%  |
| DDR   | 4         | 16.67%  |
| DDR4  | 3         | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 23        | 95.83%  |
| DIMM   | 1         | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 1024  | 9         | 33.33%  |
| 2048  | 8         | 29.63%  |
| 8192  | 4         | 14.81%  |
| 4096  | 2         | 7.41%   |
| 512   | 2         | 7.41%   |
| 16384 | 1         | 3.7%    |
| 256   | 1         | 3.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 9         | 36%     |
| 1600    | 3         | 12%     |
| 1067    | 3         | 12%     |
| 667     | 2         | 8%      |
| 3266    | 1         | 4%      |
| 2667    | 1         | 4%      |
| 2400    | 1         | 4%      |
| 1333    | 1         | 4%      |
| 975     | 1         | 4%      |
| 800     | 1         | 4%      |
| 533     | 1         | 4%      |
| 266     | 1         | 4%      |

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
| Chicony Electronics                    | 5         | 27.78%  |
| Microdia                               | 3         | 16.67%  |
| Pixart Imaging                         | 2         | 11.11%  |
| Acer                                   | 2         | 11.11%  |
| Suyin                                  | 1         | 5.56%   |
| Sunplus Innovation Technology          | 1         | 5.56%   |
| Importek                               | 1         | 5.56%   |
| IMC Networks                           | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.56%   |
| Apple                                  | 1         | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                | 2         | 11.11%  |
| Microdia Sonix USB 2.0 Camera                       | 2         | 11.11%  |
| Suyin USB2.0 UVC 1.3M WebCam                        | 1         | 5.56%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 5.56%   |
| Microdia Integrated Webcam                          | 1         | 5.56%   |
| Importek FJ Camera                                  | 1         | 5.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 5.56%   |
| Chicony VGA 30fps UVC Webcam                        | 1         | 5.56%   |
| Chicony Integrated HP HD Webcam                     | 1         | 5.56%   |
| Chicony HP HD Webcam [Fixed]                        | 1         | 5.56%   |
| Chicony CNF8243 Webcam                              | 1         | 5.56%   |
| Chicony CNF7050                                     | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC) | 1         | 5.56%   |
| Apple Built-in iSight                               | 1         | 5.56%   |
| Acer Lenovo EasyCamera                              | 1         | 5.56%   |
| Acer HP Webcam                                      | 1         | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| AuthenTec        | 2         | 66.67%  |
| Validity Sensors | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Validity Sensors VFS491              | 1         | 33.33%  |
| AuthenTec AES2501 Fingerprint Sensor | 1         | 33.33%  |
| AuthenTec AES1600                    | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 18        | 69.23%  |
| 1     | 7         | 26.92%  |
| 2     | 1         | 3.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 5         | 55.56%  |
| Fingerprint reader | 3         | 33.33%  |
| Chipcard           | 1         | 11.11%  |

