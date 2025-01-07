Pardus - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Pardus.

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

Total: 36

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| Intel         | H81                      | [9b68c23190](https://linux-hardware.org/?probe=9b68c23190) | Sep 05, 2024 |
| Dell          | 0N867P A02               | [da2abdec11](https://linux-hardware.org/?probe=da2abdec11) | Jun 17, 2024 |
| MSI           | H81M-P33                 | [7847e07836](https://linux-hardware.org/?probe=7847e07836) | May 22, 2024 |
| Gigabyte      | MH310BP-R6               | [68e0a22e4d](https://linux-hardware.org/?probe=68e0a22e4d) | Apr 22, 2024 |
| Dell          | 0VNM11 A03               | [178c559906](https://linux-hardware.org/?probe=178c559906) | Mar 14, 2024 |
| Dell          | 0VNM11 A03               | [c56a91f121](https://linux-hardware.org/?probe=c56a91f121) | Mar 14, 2024 |
| Dell          | 05WXFV A02               | [9c231dbc1a](https://linux-hardware.org/?probe=9c231dbc1a) | Feb 13, 2024 |
| Fujitsu Si... | D2581-A5 S26361-D2581-A5 | [986a67391f](https://linux-hardware.org/?probe=986a67391f) | Jan 09, 2024 |
| ASUSTek       | ProArt X570-CREATOR WIFI | [a9b6f1553d](https://linux-hardware.org/?probe=a9b6f1553d) | Dec 16, 2023 |
| Intel         | H55                      | [edff4a2637](https://linux-hardware.org/?probe=edff4a2637) | Oct 25, 2023 |
| ASUSTek       | P8H61-M LX               | [10e8cc92f1](https://linux-hardware.org/?probe=10e8cc92f1) | Apr 19, 2023 |
| ASUSTek       | P8H61-M LX               | [1e59096b86](https://linux-hardware.org/?probe=1e59096b86) | Apr 19, 2023 |
| HP            | 18E6                     | [d7cf5918eb](https://linux-hardware.org/?probe=d7cf5918eb) | Apr 11, 2023 |
| Dell          | 057FFP A01               | [023591084f](https://linux-hardware.org/?probe=023591084f) | Apr 07, 2023 |
| Dell          | 057FFP A01               | [683dea4da0](https://linux-hardware.org/?probe=683dea4da0) | Apr 07, 2023 |
| Gigabyte      | H410M H V3               | [5349814c06](https://linux-hardware.org/?probe=5349814c06) | Apr 07, 2023 |
| Lenovo        | 3132 NOK                 | [787c98df69](https://linux-hardware.org/?probe=787c98df69) | Jan 20, 2023 |
| ASUSTek       | P5G41C-M LX              | [0990a5e3e8](https://linux-hardware.org/?probe=0990a5e3e8) | Jan 05, 2023 |
| ASUSTek       | P5G41C-M LX              | [78a3773180](https://linux-hardware.org/?probe=78a3773180) | Jan 05, 2023 |
| ASUSTek       | H81M-PLUS                | [ffe63e6795](https://linux-hardware.org/?probe=ffe63e6795) | Oct 25, 2022 |
| ASUSTek       | H81M-PLUS                | [b0700ec521](https://linux-hardware.org/?probe=b0700ec521) | Oct 24, 2022 |
| ASUSTek       | P7H55-M LX               | [517cb3cb75](https://linux-hardware.org/?probe=517cb3cb75) | Oct 11, 2022 |
| Acer          | Veriton ES2740G V:1.0    | [e14aeaaca3](https://linux-hardware.org/?probe=e14aeaaca3) | Jul 25, 2022 |
| MSI           | B250M GAMING PRO         | [052965926e](https://linux-hardware.org/?probe=052965926e) | Jun 26, 2022 |
| MSI           | MS-7360                  | [1ca1d835ad](https://linux-hardware.org/?probe=1ca1d835ad) | May 22, 2022 |
| MSI           | H310M PRO-VDH PLUS       | [0d897cd79c](https://linux-hardware.org/?probe=0d897cd79c) | Apr 15, 2022 |
| MSI           | MS-7360                  | [34c10f0508](https://linux-hardware.org/?probe=34c10f0508) | Apr 10, 2022 |
| MSI           | H81M-P33                 | [2b0d95df2e](https://linux-hardware.org/?probe=2b0d95df2e) | Apr 02, 2022 |
| MSI           | MS-7360                  | [8efb24e401](https://linux-hardware.org/?probe=8efb24e401) | Mar 21, 2022 |
| MSI           | MS-7360                  | [99ac168204](https://linux-hardware.org/?probe=99ac168204) | Mar 18, 2022 |
| Gigabyte      | A320M-S2H-CF             | [fcde789242](https://linux-hardware.org/?probe=fcde789242) | Jan 24, 2022 |
| Gigabyte      | A320M-S2H-CF             | [dd92029684](https://linux-hardware.org/?probe=dd92029684) | Jan 21, 2022 |
| Lenovo        | 3132 NOK                 | [9d1ef122f7](https://linux-hardware.org/?probe=9d1ef122f7) | Oct 11, 2021 |
| Lenovo        | 3132 NOK                 | [5802651f49](https://linux-hardware.org/?probe=5802651f49) | Sep 15, 2021 |
| ASUSTek       | P5G41C-M LX              | [9149be671f](https://linux-hardware.org/?probe=9149be671f) | Jan 30, 2021 |
| Gigabyte      | A320M-H-CF               | [33cdf15439](https://linux-hardware.org/?probe=33cdf15439) | Dec 15, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Pardus 21.5   | 5        | 17.86%  |
| Pardus 21.4   | 5        | 17.86%  |
| Pardus 21.2   | 5        | 17.86%  |
| Pardus 21.3   | 4        | 14.29%  |
| Pardus 23.0   | 2        | 7.14%   |
| Pardus 23.2   | 1        | 3.57%   |
| Pardus 21.1   | 1        | 3.57%   |
| Pardus 21.0   | 1        | 3.57%   |
| Pardus 19.5   | 1        | 3.57%   |
| Pardus 19.4-1 | 1        | 3.57%   |
| Pardus 19.4   | 1        | 3.57%   |
| Pardus 19.0   | 1        | 3.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Pardus | 26       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.10.0-21-amd64            | 3        | 10.71%  |
| 5.10.0-13-amd64            | 3        | 10.71%  |
| 6.1.0-13-amd64             | 2        | 7.14%   |
| 5.18.0-0.deb11.4-amd64     | 2        | 7.14%   |
| 5.10.0-20-amd64            | 2        | 7.14%   |
| 5.10.0-16-amd64            | 2        | 7.14%   |
| 6.1.0-23-amd64             | 1        | 3.57%   |
| 5.9.0-0.bpo.2-amd64        | 1        | 3.57%   |
| 5.19.0-14.1-liquorix-amd64 | 1        | 3.57%   |
| 5.10.0-8-amd64             | 1        | 3.57%   |
| 5.10.0-26-amd64            | 1        | 3.57%   |
| 5.10.0-23-amd64            | 1        | 3.57%   |
| 5.10.0-22-amd64            | 1        | 3.57%   |
| 5.10.0-19-amd64            | 1        | 3.57%   |
| 5.10.0-18-amd64            | 1        | 3.57%   |
| 5.10.0-15-amd64            | 1        | 3.57%   |
| 5.10.0-14-amd64            | 1        | 3.57%   |
| 5.10.0-12-amd64            | 1        | 3.57%   |
| 4.19.0-18-amd64            | 1        | 3.57%   |
| 4.19.0-13-amd64            | 1        | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 18       | 66.67%  |
| 6.1.0   | 3        | 11.11%  |
| 5.18.0  | 2        | 7.41%   |
| 4.19.0  | 2        | 7.41%   |
| 5.9.0   | 1        | 3.7%    |
| 5.19.0  | 1        | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 18       | 66.67%  |
| 6.1     | 3        | 11.11%  |
| 5.18    | 2        | 7.41%   |
| 4.19    | 2        | 7.41%   |
| 5.9     | 1        | 3.7%    |
| 5.19    | 1        | 3.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 26       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| XFCE  | 17       | 62.96%  |
| GNOME | 8        | 29.63%  |
| KDE5  | 2        | 7.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 23       | 88.46%  |
| Tty     | 2        | 7.69%   |
| Wayland | 1        | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 15       | 55.56%  |
| GDM     | 5        | 18.52%  |
| LightDM | 4        | 14.81%  |
| SDDM    | 2        | 7.41%   |
| GDM3    | 1        | 3.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| tr_TR | 20       | 74.07%  |
| en_US | 6        | 22.22%  |
| fr_FR | 1        | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 22       | 81.48%  |
| EFI  | 5        | 18.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 26       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 62.96%  |
| GPT     | 8        | 29.63%  |
| MBR     | 2        | 7.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 88.46%  |
| Yes       | 3        | 11.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 96.15%  |
| Yes       | 1        | 3.85%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 7        | 26.92%  |
| ASUSTek Computer    | 5        | 19.23%  |
| Gigabyte Technology | 4        | 15.38%  |
| Dell                | 4        | 15.38%  |
| Intel               | 2        | 7.69%   |
| Lenovo              | 1        | 3.85%   |
| Hewlett-Packard     | 1        | 3.85%   |
| Fujitsu Siemens     | 1        | 3.85%   |
| Acer                | 1        | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7360                         | 3        | 11.54%  |
| MSI MS-7817                         | 2        | 7.69%   |
| MSI MS-7C09                         | 1        | 3.85%   |
| MSI MS-7A65                         | 1        | 3.85%   |
| Lenovo ThinkCentre M920t 10SGS62900 | 1        | 3.85%   |
| Intel H81                           | 1        | 3.85%   |
| Intel H55                           | 1        | 3.85%   |
| HP EliteOne 800 G1 AiO              | 1        | 3.85%   |
| Gigabyte MH310BP-R6                 | 1        | 3.85%   |
| Gigabyte H410M H V3                 | 1        | 3.85%   |
| Gigabyte A320M-S2H                  | 1        | 3.85%   |
| Gigabyte A320M-H                    | 1        | 3.85%   |
| Fujitsu Siemens D2581-A5            | 1        | 3.85%   |
| Dell Vostro 320                     | 1        | 3.85%   |
| Dell OptiPlex 7000                  | 1        | 3.85%   |
| Dell OptiPlex 5000                  | 1        | 3.85%   |
| Dell OptiPlex 3000                  | 1        | 3.85%   |
| ASUS ProArt X570-CREATOR WIFI       | 1        | 3.85%   |
| ASUS P8H61-M LX                     | 1        | 3.85%   |
| ASUS P7H55-M LX                     | 1        | 3.85%   |
| ASUS P5G41C-M LX                    | 1        | 3.85%   |
| ASUS All Series                     | 1        | 3.85%   |
| Acer Veriton ES2740G                | 1        | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| MSI MS-7360              | 3        | 11.54%  |
| Dell OptiPlex            | 3        | 11.54%  |
| MSI MS-7817              | 2        | 7.69%   |
| MSI MS-7C09              | 1        | 3.85%   |
| MSI MS-7A65              | 1        | 3.85%   |
| Lenovo ThinkCentre       | 1        | 3.85%   |
| Intel H81                | 1        | 3.85%   |
| Intel H55                | 1        | 3.85%   |
| HP EliteOne              | 1        | 3.85%   |
| Gigabyte MH310BP-R6      | 1        | 3.85%   |
| Gigabyte H410M           | 1        | 3.85%   |
| Gigabyte A320M-S2H       | 1        | 3.85%   |
| Gigabyte A320M-H         | 1        | 3.85%   |
| Fujitsu Siemens D2581-A5 | 1        | 3.85%   |
| Dell Vostro              | 1        | 3.85%   |
| ASUS ProArt              | 1        | 3.85%   |
| ASUS P8H61-M             | 1        | 3.85%   |
| ASUS P7H55-M             | 1        | 3.85%   |
| ASUS P5G41C-M            | 1        | 3.85%   |
| ASUS All                 | 1        | 3.85%   |
| Acer Veriton             | 1        | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 4        | 15.38%  |
| 2018 | 3        | 11.54%  |
| 2007 | 3        | 11.54%  |
| 2022 | 2        | 7.69%   |
| 2021 | 2        | 7.69%   |
| 2019 | 2        | 7.69%   |
| 2017 | 2        | 7.69%   |
| 2010 | 2        | 7.69%   |
| 2009 | 2        | 7.69%   |
| 2023 | 1        | 3.85%   |
| 2020 | 1        | 3.85%   |
| 2014 | 1        | 3.85%   |
| 2011 | 1        | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 26       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 26       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 26       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 8        | 29.63%  |
| 4.01-8.0    | 6        | 22.22%  |
| 16.01-24.0  | 5        | 18.52%  |
| 8.01-16.0   | 5        | 18.52%  |
| 32.01-64.0  | 1        | 3.7%    |
| 2.01-3.0    | 1        | 3.7%    |
| 64.01-256.0 | 1        | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 11       | 39.29%  |
| 2.01-3.0   | 6        | 21.43%  |
| 3.01-4.0   | 5        | 17.86%  |
| 4.01-8.0   | 2        | 7.14%   |
| 24.01-32.0 | 1        | 3.57%   |
| 16.01-24.0 | 1        | 3.57%   |
| 8.01-16.0  | 1        | 3.57%   |
| 0.51-1.0   | 1        | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 65.38%  |
| 2      | 7        | 26.92%  |
| 4      | 1        | 3.85%   |
| 3      | 1        | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 57.69%  |
| Yes       | 11       | 42.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 69.23%  |
| Yes       | 8        | 30.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 88.46%  |
| Yes       | 3        | 11.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Turkey  | 24       | 92.31%  |
| USA     | 1        | 3.85%   |
| France  | 1        | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City      | Desktops | Percent |
|-----------|----------|---------|
| Aydin     | 7        | 26.92%  |
| Istanbul  | 5        | 19.23%  |
| Bursa     | 4        | 15.38%  |
| Ankara    | 4        | 15.38%  |
| Yaman     | 1        | 3.85%   |
| Soleymieu | 1        | 3.85%   |
| Niğde    | 1        | 3.85%   |
| Mugla     | 1        | 3.85%   |
| Mason     | 1        | 3.85%   |
| Konya     | 1        | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 9      | 16.22%  |
| WDC                 | 5        | 6      | 13.51%  |
| China               | 5        | 5      | 13.51%  |
| SanDisk             | 3        | 3      | 8.11%   |
| Samsung Electronics | 3        | 8      | 8.11%   |
| KIOXIA              | 3        | 3      | 8.11%   |
| A-DATA Technology   | 3        | 3      | 8.11%   |
| KIOXIA-EXCERIA      | 2        | 2      | 5.41%   |
| Corsair             | 2        | 2      | 5.41%   |
| Team                | 1        | 1      | 2.7%    |
| Phison              | 1        | 1      | 2.7%    |
| Kingston            | 1        | 1      | 2.7%    |
| 120G                | 1        | 1      | 2.7%    |
| Unknown             | 1        | 1      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| WDC WD6402AAEX-00Y9A0 640GB        | 3        | 7.69%   |
| KIOXIA KBG50ZNS256G NVMe 256GB     | 3        | 7.69%   |
| China SATA SSD 240GB               | 3        | 7.69%   |
| A-DATA SU650 120GB SSD             | 3        | 7.69%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 5.13%   |
| China SATA SSD 120GB               | 2        | 5.13%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 2.56%   |
| WDC WD3200AAJB-00WGA0 320GB        | 1        | 2.56%   |
| Team T253X1240G 240GB SSD          | 1        | 2.56%   |
| Seagate ST3160318AS 160GB          | 1        | 2.56%   |
| Seagate ST2000DM008-2UB102 2TB     | 1        | 2.56%   |
| Seagate ST2000DM008-2FR102 2TB     | 1        | 2.56%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 2.56%   |
| SanDisk Ultra II 240GB SSD         | 1        | 2.56%   |
| SanDisk SSD PLUS 240GB             | 1        | 2.56%   |
| SanDisk SDSSDA240G 240GB           | 1        | 2.56%   |
| Samsung NVMe SSD Drive 512GB       | 1        | 2.56%   |
| Samsung MZALQ512HALU-000L1 512GB   | 1        | 2.56%   |
| Samsung HD501LJ 500GB              | 1        | 2.56%   |
| Samsung HD160HJ 160GB              | 1        | 2.56%   |
| Samsung HD103SJ 1TB                | 1        | 2.56%   |
| Phison SSMP256GHV6C2-S11 256GB SSD | 1        | 2.56%   |
| KIOXIA-EXCERIA SATA SSD 480GB      | 1        | 2.56%   |
| KIOXIA-EXCERIA SATA SSD 240GB      | 1        | 2.56%   |
| Kingston SV300S37A120G 120GB SSD   | 1        | 2.56%   |
| Corsair MP600 PRO 1TB              | 1        | 2.56%   |
| Corsair Force LS SSD 64GB          | 1        | 2.56%   |
| 120G SSD 120GB                     | 1        | 2.56%   |
| Unknown                            | 1        | 2.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 9      | 46.15%  |
| WDC                 | 5        | 6      | 38.46%  |
| Samsung Electronics | 2        | 5      | 15.38%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| China             | 5        | 5      | 27.78%  |
| SanDisk           | 3        | 3      | 16.67%  |
| A-DATA Technology | 3        | 3      | 16.67%  |
| KIOXIA-EXCERIA    | 2        | 2      | 11.11%  |
| Team              | 1        | 1      | 5.56%   |
| Phison            | 1        | 1      | 5.56%   |
| Kingston          | 1        | 1      | 5.56%   |
| Corsair           | 1        | 1      | 5.56%   |
| 120G              | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 16       | 18     | 48.48%  |
| HDD     | 11       | 20     | 33.33%  |
| NVMe    | 5        | 7      | 15.15%  |
| Unknown | 1        | 1      | 3.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 24       | 39     | 82.76%  |
| NVMe | 5        | 7      | 17.24%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 20       | 28     | 74.07%  |
| 0.51-1.0   | 5        | 6      | 18.52%  |
| 1.01-2.0   | 2        | 4      | 7.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 15       | 57.69%  |
| 251-500    | 5        | 19.23%  |
| 501-1000   | 3        | 11.54%  |
| 21-50      | 1        | 3.85%   |
| 2001-3000  | 1        | 3.85%   |
| 51-100     | 1        | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 51-100   | 8        | 30.77%  |
| 1-20     | 7        | 26.92%  |
| 21-50    | 5        | 19.23%  |
| 101-250  | 3        | 11.54%  |
| 251-500  | 2        | 7.69%   |
| 501-1000 | 1        | 3.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 1        | 1      | 50%     |
| Kingston SV300S37A120G 120GB SSD | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 1        | 1      | 50%     |
| Kingston | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 1      | 50%     |
| HDD  | 1        | 1      | 50%     |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 17       | 31     | 60.71%  |
| Works    | 9        | 13     | 32.14%  |
| Malfunc  | 2        | 2      | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 23       | 67.65%  |
| Marvell Technology Group | 3        | 8.82%   |
| KIOXIA                   | 3        | 8.82%   |
| AMD                      | 3        | 8.82%   |
| Samsung Electronics      | 1        | 2.94%   |
| Phison Electronics       | 1        | 2.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 11.11%  |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 4        | 8.89%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 8.89%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 3        | 6.67%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                              | 3        | 6.67%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 6.67%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 3        | 6.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 4.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 4.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 4.44%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 4.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 4.44%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 2        | 4.44%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 2.22%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 1        | 2.22%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 2.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.22%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.22%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 17       | 53.13%  |
| IDE  | 9        | 28.13%  |
| NVMe | 5        | 15.63%  |
| RAID | 1        | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 23       | 88.46%  |
| AMD    | 3        | 11.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3        | 11.54%  |
| Intel Core i5-4440 CPU @ 3.10GHz              | 2        | 7.69%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 2        | 7.69%   |
| Intel 12th Gen Core i5-12500T                 | 2        | 7.69%   |
| Intel Pentium CPU G2010 @ 2.80GHz             | 1        | 3.85%   |
| Intel Core i9-9900 CPU @ 3.10GHz              | 1        | 3.85%   |
| Intel Core i7-4790S CPU @ 3.20GHz             | 1        | 3.85%   |
| Intel Core i5-7600 CPU @ 3.50GHz              | 1        | 3.85%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1        | 3.85%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1        | 3.85%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1        | 3.85%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1        | 3.85%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1        | 3.85%   |
| Intel Core i3-9100F CPU @ 3.60GHz             | 1        | 3.85%   |
| Intel Core i3-8100T CPU @ 3.10GHz             | 1        | 3.85%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1        | 3.85%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 1        | 3.85%   |
| Intel 12th Gen Core i7-12700                  | 1        | 3.85%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 1        | 3.85%   |
| AMD Ryzen 5 3500X 6-Core Processor            | 1        | 3.85%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 1        | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 8        | 30.77%  |
| Intel Core 2 Quad | 4        | 15.38%  |
| Other             | 3        | 11.54%  |
| Intel Core i3     | 3        | 11.54%  |
| Intel Core 2 Duo  | 2        | 7.69%   |
| Intel Pentium     | 1        | 3.85%   |
| Intel Core i9     | 1        | 3.85%   |
| Intel Core i7     | 1        | 3.85%   |
| AMD Ryzen 7       | 1        | 3.85%   |
| AMD Ryzen 5       | 1        | 3.85%   |
| AMD A8            | 1        | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 12       | 46.15%  |
| 2      | 6        | 23.08%  |
| 6      | 5        | 19.23%  |
| 8      | 2        | 7.69%   |
| 12     | 1        | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 61.54%  |
| 2      | 10       | 38.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 26       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 42.86%  |
| 0x306c3    | 3        | 10.71%  |
| 0x1067a    | 3        | 10.71%  |
| 0x906eb    | 2        | 7.14%   |
| 0x90675    | 2        | 7.14%   |
| 0x906ed    | 1        | 3.57%   |
| 0x906e9    | 1        | 3.57%   |
| 0x90672    | 1        | 3.57%   |
| 0x306a9    | 1        | 3.57%   |
| 0x20655    | 1        | 3.57%   |
| 0x0a50000d | 1        | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 5        | 19.23%  |
| KabyLake         | 4        | 15.38%  |
| Penryn           | 3        | 11.54%  |
| Core             | 3        | 11.54%  |
| Westmere         | 2        | 7.69%   |
| CometLake        | 2        | 7.69%   |
| Alderlake Hybrid | 2        | 7.69%   |
| Zen 3            | 1        | 3.85%   |
| Zen 2            | 1        | 3.85%   |
| IvyBridge        | 1        | 3.85%   |
| Excavator        | 1        | 3.85%   |
| Unknown          | 1        | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 14       | 45.16%  |
| AMD    | 9        | 29.03%  |
| Nvidia | 8        | 25.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 12.9%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 3        | 9.68%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 6.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 6.45%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 2        | 6.45%   |
| AMD RV630 PRO [Radeon HD 2600 PRO]                                          | 2        | 6.45%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 3.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.23%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 3.23%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 3.23%   |
| Intel HD Graphics 630                                                       | 1        | 3.23%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 3.23%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 3.23%   |
| Intel AlderLake-S GT1                                                       | 1        | 3.23%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 3.23%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 3.23%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                        | 1        | 3.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 3.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 1        | 3.23%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 3.23%   |
| AMD Bonaire XT [Radeon HD 7790/8770 / R7 360 / R9 260/360 OEM]              | 1        | 3.23%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Intel    | 10       | 38.46%  |
| 1 x AMD      | 8        | 30.77%  |
| 1 x Nvidia   | 7        | 26.92%  |
| AMD + Nvidia | 1        | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 24       | 92.31%  |
| Proprietary | 2        | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 70.37%  |
| 0.01-0.5   | 3        | 11.11%  |
| 1.01-2.0   | 2        | 7.41%   |
| 0.51-1.0   | 2        | 7.41%   |
| 3.01-4.0   | 1        | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 5        | 19.23%  |
| Dell                 | 4        | 15.38%  |
| Samsung Electronics  | 3        | 11.54%  |
| Philips              | 2        | 7.69%   |
| Beko                 | 2        | 7.69%   |
| Acer                 | 2        | 7.69%   |
| STD                  | 1        | 3.85%   |
| SAC                  | 1        | 3.85%   |
| Iiyama               | 1        | 3.85%   |
| HKC                  | 1        | 3.85%   |
| Hewlett-Packard      | 1        | 3.85%   |
| Casper               | 1        | 3.85%   |
| Ancor Communications | 1        | 3.85%   |
| AGO                  | 1        | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                  | 3        | 11.11%  |
| Beko BK WUXGA BEK4448 1920x1080 820x460mm 37.0-inch                   | 2        | 7.41%   |
| STD Monitor STD2023 1920x1080 600x330mm 27.0-inch                     | 1        | 3.7%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1        | 3.7%    |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch     | 1        | 3.7%    |
| Samsung Electronics SyncMaster SAM0599 1600x900 440x250mm 19.9-inch   | 1        | 3.7%    |
| Samsung Electronics S27H65x SAM0E1E 1920x1080 598x336mm 27.0-inch     | 1        | 3.7%    |
| SAC LED MONITOR SAC3219 1360x768 304x228mm 15.0-inch                  | 1        | 3.7%    |
| Philips PHL 243B9 PHL0941 1920x1080 527x296mm 23.8-inch               | 1        | 3.7%    |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1        | 3.7%    |
| Iiyama PLX2380H IVM5621 1920x1080 509x286mm 23.0-inch                 | 1        | 3.7%    |
| HKC '' HKC2160 1920x1080 360x270mm 17.7-inch                          | 1        | 3.7%    |
| Hewlett-Packard HPQ 800 AIO HWP1080 1920x1080 510x287mm 23.0-inch     | 1        | 3.7%    |
| Goldstar L1753T GSM4476 1280x1024 338x270mm 17.0-inch                 | 1        | 3.7%    |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                  | 1        | 3.7%    |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                    | 1        | 3.7%    |
| Dell P2717H DEL40F6 1920x1080 598x336mm 27.0-inch                     | 1        | 3.7%    |
| Dell E2423HN DELF144 1920x1080 527x296mm 23.8-inch                    | 1        | 3.7%    |
| Dell E2421HN DELF129 1920x1080 527x296mm 23.8-inch                    | 1        | 3.7%    |
| Casper 19CSPR CSP1900 1440x900 410x256mm 19.0-inch                    | 1        | 3.7%    |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 1        | 3.7%    |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                 | 1        | 3.7%    |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                    | 1        | 3.7%    |
| Acer G206HQL ACR0327 1600x900 430x240mm 19.4-inch                     | 1        | 3.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 50%     |
| 3840x2160 (4K)     | 3        | 12.5%   |
| 1680x1050 (WSXGA+) | 3        | 12.5%   |
| 1600x900 (HD+)     | 2        | 8.33%   |
| 1366x768 (WXGA)    | 2        | 8.33%   |
| 1440x900 (WXGA+)   | 1        | 4.17%   |
| 1280x1024 (SXGA)   | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 23     | 7        | 26.92%  |
| 21     | 5        | 19.23%  |
| 27     | 3        | 11.54%  |
| 72     | 2        | 7.69%   |
| 24     | 2        | 7.69%   |
| 19     | 2        | 7.69%   |
| 31     | 1        | 3.85%   |
| 20     | 1        | 3.85%   |
| 18     | 1        | 3.85%   |
| 17     | 1        | 3.85%   |
| 12     | 1        | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 12       | 48%     |
| 501-600     | 8        | 32%     |
| 1501-2000   | 2        | 8%      |
| 601-700     | 1        | 4%      |
| 301-350     | 1        | 4%      |
| 201-300     | 1        | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 17       | 73.91%  |
| 3/2   | 3        | 13.04%  |
| 5/4   | 1        | 4.35%   |
| 4/3   | 1        | 4.35%   |
| 16/10 | 1        | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 48%     |
| 151-200        | 4        | 16%     |
| 301-350        | 3        | 12%     |
| More than 1000 | 2        | 8%      |
| 141-150        | 2        | 8%      |
| 71-80          | 1        | 4%      |
| 351-500        | 1        | 4%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 17       | 68%     |
| 101-120 | 4        | 16%     |
| 1-50    | 2        | 8%      |
| 161-240 | 1        | 4%      |
| 121-160 | 1        | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 84.62%  |
| 2     | 3        | 11.54%  |
| 0     | 1        | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 19       | 57.58%  |
| Intel                 | 8        | 24.24%  |
| Ralink Technology     | 2        | 6.06%   |
| ZyXEL Communications  | 1        | 3.03%   |
| MediaTek              | 1        | 3.03%   |
| Broadcom              | 1        | 3.03%   |
| Aquantia              | 1        | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 18       | 50%     |
| Intel Ethernet Connection (17) I219-LM                                          | 2        | 5.56%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]                    | 1        | 2.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                          | 1        | 2.78%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                           | 1        | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 1        | 2.78%   |
| Realtek 802.11n WLAN Adapter                                                    | 1        | 2.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                                           | 1        | 2.78%   |
| Ralink MT7601U Wireless Adapter                                                 | 1        | 2.78%   |
| MediaTek WiFi                                                                   | 1        | 2.78%   |
| Intel Wi-Fi 6 AX200                                                             | 1        | 2.78%   |
| Intel Ethernet Controller I225-V                                                | 1        | 2.78%   |
| Intel Ethernet Connection I217-LM                                               | 1        | 2.78%   |
| Intel Ethernet Connection (7) I219-LM                                           | 1        | 2.78%   |
| Intel Ethernet Connection (2) I219-V                                            | 1        | 2.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                | 1        | 2.78%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                         | 1        | 2.78%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 1        | 2.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 3        | 33.33%  |
| Ralink Technology     | 2        | 22.22%  |
| Intel                 | 2        | 22.22%  |
| ZyXEL Communications  | 1        | 11.11%  |
| MediaTek              | 1        | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU] | 1        | 11.11%  |
| Realtek RTL8192CU 802.11n WLAN Adapter                       | 1        | 11.11%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter        | 1        | 11.11%  |
| Realtek 802.11n WLAN Adapter                                 | 1        | 11.11%  |
| Ralink RT2870/RT3070 Wireless Adapter                        | 1        | 11.11%  |
| Ralink MT7601U Wireless Adapter                              | 1        | 11.11%  |
| MediaTek WiFi                                                | 1        | 11.11%  |
| Intel Wi-Fi 6 AX200                                          | 1        | 11.11%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]             | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 19       | 70.37%  |
| Intel                 | 6        | 22.22%  |
| Broadcom              | 1        | 3.7%    |
| Aquantia              | 1        | 3.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 18       | 66.67%  |
| Intel Ethernet Connection (17) I219-LM                                          | 2        | 7.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 1        | 3.7%    |
| Intel Ethernet Controller I225-V                                                | 1        | 3.7%    |
| Intel Ethernet Connection I217-LM                                               | 1        | 3.7%    |
| Intel Ethernet Connection (7) I219-LM                                           | 1        | 3.7%    |
| Intel Ethernet Connection (2) I219-V                                            | 1        | 3.7%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                         | 1        | 3.7%    |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 1        | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 76.47%  |
| WiFi     | 8        | 23.53%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 22       | 78.57%  |
| WiFi     | 6        | 21.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 23       | 88.46%  |
| 2     | 3        | 11.54%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 24       | 92.31%  |
| Yes  | 2        | 7.69%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 66.67%  |
| Cambridge Silicon Radio | 1        | 33.33%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 33.33%  |
| Intel AX200 Bluetooth                               | 1        | 33.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 33.33%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 23       | 62.16%  |
| AMD                 | 9        | 24.32%  |
| Nvidia              | 4        | 10.81%  |
| Kingston Technology | 1        | 2.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 11.9%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 9.52%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 7.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 4.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 4.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 4.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 4.76%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 4.76%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 2        | 4.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 4.76%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia High Definition Audio Controller                                    | 1        | 2.38%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.38%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 2.38%   |
| Kingston Technology HyperX QuadCast S                                      | 1        | 2.38%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 2.38%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 2.38%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1        | 2.38%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 2.38%   |
| AMD Kabini HDMI/DP Audio                                                   | 1        | 2.38%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 1        | 2.38%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 2.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 2.38%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 21.43%  |
| Micron Technology   | 3        | 21.43%  |
| Kingston            | 3        | 21.43%  |
| G.Skill             | 2        | 14.29%  |
| Crucial             | 1        | 7.14%   |
| A-DATA Technology   | 1        | 7.14%   |
| Unknown             | 1        | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s     | 2        | 13.33%  |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 1        | 6.67%   |
| Samsung RAM M378A2K43DB1-CTD 16384MB DIMM DDR4 2667MT/s  | 1        | 6.67%   |
| Samsung RAM M378A1G44BB0-CWE 8GB DIMM DDR4 3200MT/s      | 1        | 6.67%   |
| Micron RAM 16HTF25664AY-667E1 2GB DIMM DDR 667MT/s       | 1        | 6.67%   |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s                | 1        | 6.67%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s     | 1        | 6.67%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s        | 1        | 6.67%   |
| Kingston RAM 99U5471-057.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 6.67%   |
| G.Skill RAM F4-3200C16-32GTZN 32GB DIMM DDR4 3200MT/s    | 1        | 6.67%   |
| G.Skill RAM F4-2133C15-4GIS 4GB DIMM DDR4 2133MT/s       | 1        | 6.67%   |
| Crucial RAM CT16G4SFS8266.C8FE 16GB SODIMM DDR4 2667MT/s | 1        | 6.67%   |
| A-DATA RAM Module 8GB DIMM DDR4 2667MT/s                 | 1        | 6.67%   |
| Unknown                                                  | 1        | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 9        | 75%     |
| DDR3 | 2        | 16.67%  |
| DDR2 | 1        | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 8        | 66.67%  |
| SODIMM | 4        | 33.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 58.33%  |
| 16384 | 2        | 16.67%  |
| 32768 | 1        | 8.33%   |
| 4096  | 1        | 8.33%   |
| 2048  | 1        | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 4        | 30.77%  |
| 2667  | 3        | 23.08%  |
| 3400  | 1        | 7.69%   |
| 2666  | 1        | 7.69%   |
| 2133  | 1        | 7.69%   |
| 1600  | 1        | 7.69%   |
| 1333  | 1        | 7.69%   |
| 667   | 1        | 7.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Zebra    | 4        | 66.67%  |
| Oki Data | 1        | 16.67%  |
| Canon    | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Zebra TLP2844                    | 3        | 50%     |
| Zebra Zebra GC420d Label Printer | 1        | 16.67%  |
| Oki Data Oki_ML3320              | 1        | 16.67%  |
| Canon LBP6000                    | 1        | 16.67%  |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 14.29%  |
| Microdia              | 1        | 14.29%  |
| MacroSilicon          | 1        | 14.29%  |
| Chicony Electronics   | 1        | 14.29%  |
| Arkmicro Technologies | 1        | 14.29%  |
| Allwinner Technology  | 1        | 14.29%  |
| Alcor Micro           | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Realtek HP 2.0MP High Definition Webcam | 1        | 14.29%  |
| Microdia Integrated Camera              | 1        | 14.29%  |
| MacroSilicon USB Video                  | 1        | 14.29%  |
| Chicony Integrated_Webcam_1.3M          | 1        | 14.29%  |
| Arkmicro USB2.0 PC CAMERA               | 1        | 14.29%  |
| Allwinner TP1005                        | 1        | 14.29%  |
| Alcor Micro USB 2.0 PC Camera           | 1        | 14.29%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Advanced Card Systems | 2        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Advanced Card Systems ACR38 SmartCard Reader | 2        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 21       | 77.78%  |
| 1     | 6        | 22.22%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Storage                  | 1        | 16.67%  |
| Net/wireless             | 1        | 16.67%  |
| Graphics card            | 1        | 16.67%  |
| Communication controller | 1        | 16.67%  |
| Chipcard                 | 1        | 16.67%  |
| Camera                   | 1        | 16.67%  |

