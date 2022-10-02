Linux in UAE - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Linux in UAE.

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

Total: 30

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| MSI      | Z97 PC Mate              | [512c793b51](https://linux-hardware.org/?probe=512c793b51) | Sep 06, 2022 |
| Dell     | 0MGK50 A02               | [eca7a31c46](https://linux-hardware.org/?probe=eca7a31c46) | Jun 23, 2022 |
| Dell     | 0MGK50 A02               | [134bf128f7](https://linux-hardware.org/?probe=134bf128f7) | Jun 23, 2022 |
| Dell     | 0CRH6C A02               | [f014fcba4f](https://linux-hardware.org/?probe=f014fcba4f) | Feb 14, 2022 |
| Biostar  | TZ77XE4                  | [081c3be70e](https://linux-hardware.org/?probe=081c3be70e) | Feb 07, 2022 |
| ASUSTek  | PRIME B250M-PLUS         | [7b77d5463d](https://linux-hardware.org/?probe=7b77d5463d) | Nov 13, 2021 |
| ECS      | GeForce6100PM-M2         | [e1f91ca6de](https://linux-hardware.org/?probe=e1f91ca6de) | Sep 02, 2021 |
| ASUSTek  | ROG ZENITH EXTREME       | [e25c41c312](https://linux-hardware.org/?probe=e25c41c312) | Jul 03, 2021 |
| Dell     | OptiPlex 980             | [1fe360b027](https://linux-hardware.org/?probe=1fe360b027) | May 26, 2021 |
| Lenovo   | 3098 NOK                 | [d0ccf5266d](https://linux-hardware.org/?probe=d0ccf5266d) | Jan 27, 2021 |
| ASUSTek  | PRIME B460M-A            | [54531ec292](https://linux-hardware.org/?probe=54531ec292) | Oct 21, 2020 |
| Intel    | D865PERL AAC27648-207    | [387171a87d](https://linux-hardware.org/?probe=387171a87d) | Oct 08, 2020 |
| HP       | 2AA2                     | [ceebc6a90b](https://linux-hardware.org/?probe=ceebc6a90b) | Oct 04, 2020 |
| Intel    | D865PERL AAC27648-207    | [7d3672caff](https://linux-hardware.org/?probe=7d3672caff) | Oct 04, 2020 |
| Intel    | D865PERL AAC27648-207    | [2a18eaa0ab](https://linux-hardware.org/?probe=2a18eaa0ab) | Oct 04, 2020 |
| ASUSTek  | X99-DELUXE               | [18778a34f2](https://linux-hardware.org/?probe=18778a34f2) | Sep 10, 2020 |
| ASUSTek  | X99-DELUXE               | [ff1f32c975](https://linux-hardware.org/?probe=ff1f32c975) | Sep 10, 2020 |
| ASUSTek  | PRIME B450-PLUS          | [19af27b191](https://linux-hardware.org/?probe=19af27b191) | Aug 20, 2020 |
| Intel    | DH67CL AAG10212-210      | [f555bad747](https://linux-hardware.org/?probe=f555bad747) | Aug 14, 2020 |
| HP       | 2AA2                     | [f20932c5c3](https://linux-hardware.org/?probe=f20932c5c3) | Aug 09, 2020 |
| HP       | 2AA2                     | [424f0397a7](https://linux-hardware.org/?probe=424f0397a7) | Jul 16, 2020 |
| ASUSTek  | P7P55 LX                 | [dc74d7b188](https://linux-hardware.org/?probe=dc74d7b188) | Jun 25, 2020 |
| Intel    | DH67CL AAG10212-210      | [fdbf1ae7da](https://linux-hardware.org/?probe=fdbf1ae7da) | Jun 19, 2020 |
| Intel    | DH67CL AAG10212-210      | [0d398d9227](https://linux-hardware.org/?probe=0d398d9227) | Jun 14, 2020 |
| HP       | 2AA2                     | [24c07d9d0d](https://linux-hardware.org/?probe=24c07d9d0d) | Jun 11, 2020 |
| Gigabyte | Z77X-UD5H                | [aac474f532](https://linux-hardware.org/?probe=aac474f532) | Apr 18, 2020 |
| Dell     | 0NK70N A03               | [8aa5224a4a](https://linux-hardware.org/?probe=8aa5224a4a) | Aug 01, 2019 |
| ASUSTek  | Rampage V EXTREME        | [309f371381](https://linux-hardware.org/?probe=309f371381) | May 27, 2019 |
| ASUSTek  | ROG STRIX X299-XE GAMING | [c8fdc5e958](https://linux-hardware.org/?probe=c8fdc5e958) | Dec 25, 2018 |
| Lenovo   | SHARKBAY SDK0E50510 WIN  | [c48aa05e74](https://linux-hardware.org/?probe=c48aa05e74) | Oct 08, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu 18.04     | 7        | 33.33%  |
| Ubuntu 20.04     | 4        | 19.05%  |
| Debian 10        | 2        | 9.52%   |
| Xubuntu 16.04    | 1        | 4.76%   |
| Ubuntu 22.04     | 1        | 4.76%   |
| OpenMandriva 4.3 | 1        | 4.76%   |
| Manjaro 20.1     | 1        | 4.76%   |
| Linux Mint 20.3  | 1        | 4.76%   |
| Fedora 34        | 1        | 4.76%   |
| Endless 3.5.3    | 1        | 4.76%   |
| Debian 11        | 1        | 4.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 12       | 57.14%  |
| Debian       | 3        | 14.29%  |
| Xubuntu      | 1        | 4.76%   |
| OpenMandriva | 1        | 4.76%   |
| Manjaro      | 1        | 4.76%   |
| Linux Mint   | 1        | 4.76%   |
| Fedora       | 1        | 4.76%   |
| Endless      | 1        | 4.76%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.8.0-40-generic        | 1        | 4%      |
| 5.8.0-0.bpo.2-amd64     | 1        | 4%      |
| 5.7.14-1-MANJARO        | 1        | 4%      |
| 5.4.0-81-generic        | 1        | 4%      |
| 5.4.0-48-generic        | 1        | 4%      |
| 5.4.0-47-generic        | 1        | 4%      |
| 5.4.0-42-generic        | 1        | 4%      |
| 5.4.0-40-generic        | 1        | 4%      |
| 5.4.0-37-generic        | 1        | 4%      |
| 5.4.0-125-generic       | 1        | 4%      |
| 5.3.0-28-generic        | 1        | 4%      |
| 5.16.7-desktop-1omv4003 | 1        | 4%      |
| 5.15.0-40-generic       | 1        | 4%      |
| 5.12.13-300.fc34.x86_64 | 1        | 4%      |
| 5.11.0-40-generic       | 1        | 4%      |
| 5.10.0-11-amd64         | 1        | 4%      |
| 5.0.0-23-generic        | 1        | 4%      |
| 4.19.0-16-amd64         | 1        | 4%      |
| 4.18.0-11-generic       | 1        | 4%      |
| 4.15.0-55-generic       | 1        | 4%      |
| 4.15.0-50-generic       | 1        | 4%      |
| 4.15.0-36-generic       | 1        | 4%      |
| 4.15.0-118-generic      | 1        | 4%      |
| 4.15.0-112-generic      | 1        | 4%      |
| 4.15.0-101-generic      | 1        | 4%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.15.0  | 5        | 23.81%  |
| 5.4.0   | 4        | 19.05%  |
| 5.8.0   | 2        | 9.52%   |
| 5.7.14  | 1        | 4.76%   |
| 5.3.0   | 1        | 4.76%   |
| 5.16.7  | 1        | 4.76%   |
| 5.15.0  | 1        | 4.76%   |
| 5.12.13 | 1        | 4.76%   |
| 5.11.0  | 1        | 4.76%   |
| 5.10.0  | 1        | 4.76%   |
| 5.0.0   | 1        | 4.76%   |
| 4.19.0  | 1        | 4.76%   |
| 4.18.0  | 1        | 4.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.15    | 5        | 23.81%  |
| 5.4     | 4        | 19.05%  |
| 5.8     | 2        | 9.52%   |
| 5.7     | 1        | 4.76%   |
| 5.3     | 1        | 4.76%   |
| 5.16    | 1        | 4.76%   |
| 5.15    | 1        | 4.76%   |
| 5.12    | 1        | 4.76%   |
| 5.11    | 1        | 4.76%   |
| 5.10    | 1        | 4.76%   |
| 5.0     | 1        | 4.76%   |
| 4.19    | 1        | 4.76%   |
| 4.18    | 1        | 4.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 20       | 95.24%  |
| i686   | 1        | 4.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 13       | 61.9%   |
| Unknown    | 4        | 19.05%  |
| XFCE       | 1        | 4.76%   |
| X-Cinnamon | 1        | 4.76%   |
| KDE5       | 1        | 4.76%   |
| bspwm      | 1        | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 17       | 80.95%  |
| Unknown | 3        | 14.29%  |
| Wayland | 1        | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 66.67%  |
| LightDM | 2        | 9.52%   |
| GDM3    | 2        | 9.52%   |
| GDM     | 2        | 9.52%   |
| SDDM    | 1        | 4.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 14       | 66.67%  |
| Unknown | 4        | 19.05%  |
| en_GB   | 2        | 9.52%   |
| C       | 1        | 4.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 11       | 50%     |
| EFI  | 11       | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 17       | 80.95%  |
| Xfs     | 1        | 4.76%   |
| Overlay | 1        | 4.76%   |
| Btrfs   | 1        | 4.76%   |
| Unknown | 1        | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 76.19%  |
| GPT     | 4        | 19.05%  |
| MBR     | 1        | 4.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 81.82%  |
| Yes       | 4        | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 72.73%  |
| Yes       | 6        | 27.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 8        | 38.1%   |
| Dell                | 4        | 19.05%  |
| Lenovo              | 2        | 9.52%   |
| Intel               | 2        | 9.52%   |
| MSI                 | 1        | 4.76%   |
| Hewlett-Packard     | 1        | 4.76%   |
| Gigabyte Technology | 1        | 4.76%   |
| ECS                 | 1        | 4.76%   |
| Biostar             | 1        | 4.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 2        | 9.52%   |
| MSI MS-7850                       | 1        | 4.76%   |
| Lenovo ThinkCentre E93 10AR004LAX | 1        | 4.76%   |
| Lenovo ThinkCentre E73 10AS0041AX | 1        | 4.76%   |
| Intel DH67CL AAG10212-210         | 1        | 4.76%   |
| Intel D865PERL AAC27648-207       | 1        | 4.76%   |
| HP 200-5120me                     | 1        | 4.76%   |
| Gigabyte Z77X-UD5H                | 1        | 4.76%   |
| ECS GeForce6100PM-M2              | 1        | 4.76%   |
| Dell Precision WorkStation T5500  | 1        | 4.76%   |
| Dell Precision T7610              | 1        | 4.76%   |
| Dell OptiPlex 980                 | 1        | 4.76%   |
| Dell OptiPlex 3040                | 1        | 4.76%   |
| Biostar TZ77XE4                   | 1        | 4.76%   |
| ASUS ROG ZENITH EXTREME           | 1        | 4.76%   |
| ASUS ROG STRIX X299-XE GAMING     | 1        | 4.76%   |
| ASUS PRIME B460M-A                | 1        | 4.76%   |
| ASUS PRIME B450-PLUS              | 1        | 4.76%   |
| ASUS PRIME B250M-PLUS             | 1        | 4.76%   |
| ASUS P7P55 LX                     | 1        | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 3        | 14.29%  |
| Lenovo ThinkCentre   | 2        | 9.52%   |
| Dell Precision       | 2        | 9.52%   |
| Dell OptiPlex        | 2        | 9.52%   |
| ASUS ROG             | 2        | 9.52%   |
| ASUS All             | 2        | 9.52%   |
| MSI MS-7850          | 1        | 4.76%   |
| Intel DH67CL         | 1        | 4.76%   |
| Intel D865PERL       | 1        | 4.76%   |
| HP 200-5120me        | 1        | 4.76%   |
| Gigabyte Z77X-UD5H   | 1        | 4.76%   |
| ECS GeForce6100PM-M2 | 1        | 4.76%   |
| Biostar TZ77XE4      | 1        | 4.76%   |
| ASUS P7P55           | 1        | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 3        | 14.29%  |
| 2014 | 3        | 14.29%  |
| 2018 | 2        | 9.52%   |
| 2012 | 2        | 9.52%   |
| 2011 | 2        | 9.52%   |
| 2010 | 2        | 9.52%   |
| 2020 | 1        | 4.76%   |
| 2016 | 1        | 4.76%   |
| 2015 | 1        | 4.76%   |
| 2013 | 1        | 4.76%   |
| 2009 | 1        | 4.76%   |
| 2007 | 1        | 4.76%   |
| 2005 | 1        | 4.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 21       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 20       | 95.24%  |
| Enabled  | 1        | 4.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 7        | 33.33%  |
| 4.01-8.0    | 3        | 14.29%  |
| 64.01-256.0 | 3        | 14.29%  |
| 32.01-64.0  | 2        | 9.52%   |
| 3.01-4.0    | 2        | 9.52%   |
| 8.01-16.0   | 2        | 9.52%   |
| 0.51-1.0    | 2        | 9.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 7        | 31.82%  |
| 4.01-8.0  | 5        | 22.73%  |
| 1.01-2.0  | 4        | 18.18%  |
| 3.01-4.0  | 2        | 9.09%   |
| 8.01-16.0 | 2        | 9.09%   |
| 0.51-1.0  | 1        | 4.55%   |
| 0.01-0.5  | 1        | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 47.62%  |
| 2      | 4        | 19.05%  |
| 4      | 3        | 14.29%  |
| 3      | 3        | 14.29%  |
| 8      | 1        | 4.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 76.19%  |
| Yes       | 5        | 23.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 21       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 61.9%   |
| Yes       | 8        | 38.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 63.64%  |
| Yes       | 8        | 36.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| UAE     | 21       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Dubai            | 11       | 52.38%  |
| Abu Dhabi        | 7        | 33.33%  |
| Sharjah          | 1        | 4.76%   |
| Al Fujairah City | 1        | 4.76%   |
| Al Ain City      | 1        | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 15     | 29.27%  |
| Seagate             | 7        | 11     | 17.07%  |
| Samsung Electronics | 7        | 9      | 17.07%  |
| Toshiba             | 3        | 3      | 7.32%   |
| Lexar               | 2        | 2      | 4.88%   |
| Kingston            | 2        | 2      | 4.88%   |
| Crucial             | 2        | 2      | 4.88%   |
| Transcend           | 1        | 1      | 2.44%   |
| Maxtor              | 1        | 1      | 2.44%   |
| Hitachi             | 1        | 1      | 2.44%   |
| HGST                | 1        | 1      | 2.44%   |
| Gigabyte Technology | 1        | 1      | 2.44%   |
| Corsair             | 1        | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD   | 2        | 4.55%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 2        | 4.55%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 4.55%   |
| Samsung SSD 850 PRO 1TB            | 2        | 4.55%   |
| Crucial CT500MX500SSD1 500GB       | 2        | 4.55%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1        | 2.27%   |
| WDC WD800BB-55JHC0 80GB            | 1        | 2.27%   |
| WDC WD6400AAKS-22A7B0 640GB        | 1        | 2.27%   |
| WDC WD5000AAKS-65V0A0 500GB        | 1        | 2.27%   |
| WDC WD40EFRX-68N32N0 4TB           | 1        | 2.27%   |
| WDC WD2500AAJS-75M0A0 250GB        | 1        | 2.27%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 2.27%   |
| WDC WD1600AAJS-60B4A0 160GB        | 1        | 2.27%   |
| WDC WD10EZEX-08M2NA0 1TB           | 1        | 2.27%   |
| Transcend TS256GSSD370S 256GB      | 1        | 2.27%   |
| Toshiba MK3275GSX 320GB            | 1        | 2.27%   |
| Toshiba HDWE160 6TB                | 1        | 2.27%   |
| Toshiba DT01ACA200 2TB             | 1        | 2.27%   |
| Seagate ST500VT000-1DK142 500GB    | 1        | 2.27%   |
| Seagate ST4000DM001-1FK17N 4TB     | 1        | 2.27%   |
| Seagate ST31000528AS 1TB           | 1        | 2.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 2.27%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 2.27%   |
| Samsung SSD 980 1TB                | 1        | 2.27%   |
| Samsung SSD 970 EVO Plus 500GB     | 1        | 2.27%   |
| Samsung SSD 860 EVO 500GB          | 1        | 2.27%   |
| Samsung SSD 850 EVO 250GB          | 1        | 2.27%   |
| Samsung SSD 840 EVO 1TB            | 1        | 2.27%   |
| Samsung SSD 840 EVO 120GB          | 1        | 2.27%   |
| Samsung NVMe SSD Drive 1024GB      | 1        | 2.27%   |
| Maxtor STM3160215AS 160GB          | 1        | 2.27%   |
| Lexar 512GB SSD                    | 1        | 2.27%   |
| Lexar 500GB SSD                    | 1        | 2.27%   |
| Kingston SH103S3240G 240GB SSD     | 1        | 2.27%   |
| Kingston SA400S37240G 240GB SSD    | 1        | 2.27%   |
| Hitachi HDS5C3020ALA632 2TB        | 1        | 2.27%   |
| HGST HTS725050A7E630 500GB         | 1        | 2.27%   |
| Gigabyte GP-GSTFS31120GNTD 120GB   | 1        | 2.27%   |
| Corsair Force GS 480GB SSD         | 1        | 2.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 9        | 12     | 40.91%  |
| Seagate | 7        | 11     | 31.82%  |
| Toshiba | 3        | 3      | 13.64%  |
| Maxtor  | 1        | 1      | 4.55%   |
| Hitachi | 1        | 1      | 4.55%   |
| HGST    | 1        | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 6      | 31.25%  |
| WDC                 | 3        | 3      | 18.75%  |
| Kingston            | 2        | 2      | 12.5%   |
| Crucial             | 2        | 2      | 12.5%   |
| Transcend           | 1        | 1      | 6.25%   |
| Lexar               | 1        | 1      | 6.25%   |
| Gigabyte Technology | 1        | 1      | 6.25%   |
| Corsair             | 1        | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 29     | 53.13%  |
| SSD  | 11       | 17     | 34.38%  |
| NVMe | 4        | 4      | 12.5%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 20       | 45     | 80%     |
| NVMe | 4        | 4      | 16%     |
| SAS  | 1        | 1      | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 18       | 26     | 56.25%  |
| 0.51-1.0   | 8        | 10     | 25%     |
| 1.01-2.0   | 4        | 4      | 12.5%   |
| 3.01-4.0   | 1        | 5      | 3.13%   |
| 4.01-10.0  | 1        | 1      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 6        | 27.27%  |
| 101-250        | 4        | 18.18%  |
| 1001-2000      | 4        | 18.18%  |
| 2001-3000      | 3        | 13.64%  |
| 501-1000       | 2        | 9.09%   |
| More than 3000 | 1        | 4.55%   |
| 51-100         | 1        | 4.55%   |
| Unknown        | 1        | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 8        | 33.33%  |
| 21-50     | 5        | 20.83%  |
| 101-250   | 4        | 16.67%  |
| 501-1000  | 2        | 8.33%   |
| 51-100    | 2        | 8.33%   |
| 251-500   | 1        | 4.17%   |
| 2001-3000 | 1        | 4.17%   |
| Unknown   | 1        | 4.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 16       | 33     | 76.19%  |
| Works    | 5        | 17     | 23.81%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 18       | 60%     |
| Samsung Electronics      | 3        | 10%     |
| ASMedia Technology       | 2        | 6.67%   |
| AMD                      | 2        | 6.67%   |
| VIA Technologies         | 1        | 3.33%   |
| Silicon Motion           | 1        | 3.33%   |
| Nvidia                   | 1        | 3.33%   |
| Marvell Technology Group | 1        | 3.33%   |
| Broadcom / LSI           | 1        | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 5.26%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 5.26%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2        | 5.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 5.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 5.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2        | 5.26%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2        | 5.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 5.26%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 5.26%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2        | 5.26%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 2.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 2.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 2.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 2.63%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 2.63%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 2.63%   |
| Nvidia MCP61 IDE                                                               | 1        | 2.63%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.63%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1        | 2.63%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 2.63%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                   | 1        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 2.63%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                          | 1        | 2.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1        | 2.63%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                            | 1        | 2.63%   |
| AMD X399 Series Chipset SATA Controller                                        | 1        | 2.63%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 17       | 65.38%  |
| NVMe | 4        | 15.38%  |
| IDE  | 4        | 15.38%  |
| SAS  | 1        | 3.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 18       | 85.71%  |
| AMD    | 3        | 14.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-3770K CPU @ 3.50GHz              | 2        | 9.52%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1        | 4.76%   |
| Intel Xeon CPU E5-2609 v2 @ 2.50GHz            | 1        | 4.76%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz    | 1        | 4.76%   |
| Intel Pentium 4 CPU 2.80GHz                    | 1        | 4.76%   |
| Intel Core i7-7740X CPU @ 4.30GHz              | 1        | 4.76%   |
| Intel Core i7-5960X CPU @ 3.00GHz              | 1        | 4.76%   |
| Intel Core i7-5820K CPU @ 3.30GHz              | 1        | 4.76%   |
| Intel Core i7-4790S CPU @ 3.20GHz              | 1        | 4.76%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 4.76%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 1        | 4.76%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 4.76%   |
| Intel Core i7 CPU 860 @ 2.80GHz                | 1        | 4.76%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 4.76%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 4.76%   |
| Intel Core i5-3470T CPU @ 2.90GHz              | 1        | 4.76%   |
| Intel Core i5 CPU 650 @ 3.20GHz                | 1        | 4.76%   |
| AMD Sempron Processor LE-1150                  | 1        | 4.76%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 4.76%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1        | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 10       | 47.62%  |
| Intel Core i5           | 4        | 19.05%  |
| Intel Xeon              | 2        | 9.52%   |
| Intel Pentium Dual-Core | 1        | 4.76%   |
| Intel Pentium 4         | 1        | 4.76%   |
| AMD Sempron             | 1        | 4.76%   |
| AMD Ryzen Threadripper  | 1        | 4.76%   |
| AMD Ryzen 5             | 1        | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 10       | 47.62%  |
| 8      | 3        | 14.29%  |
| 2      | 3        | 14.29%  |
| 6      | 2        | 9.52%   |
| 1      | 2        | 9.52%   |
| 16     | 1        | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 95.24%  |
| 2      | 1        | 4.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 15       | 71.43%  |
| 1      | 6        | 28.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 19       | 90.48%  |
| 32-bit         | 1        | 4.76%   |
| Unknown        | 1        | 4.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 18.18%  |
| 0x306c3    | 3        | 13.64%  |
| 0x306a9    | 3        | 13.64%  |
| 0x906e9    | 2        | 9.09%   |
| 0x306f2    | 2        | 9.09%   |
| 0xf29      | 1        | 4.55%   |
| 0xa0655    | 1        | 4.55%   |
| 0x306e4    | 1        | 4.55%   |
| 0x206c2    | 1        | 4.55%   |
| 0x106e5    | 1        | 4.55%   |
| 0x1067a    | 1        | 4.55%   |
| 0x0800820d | 1        | 4.55%   |
| 0x08001137 | 1        | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Haswell   | 5        | 23.81%  |
| IvyBridge | 4        | 19.05%  |
| Westmere  | 2        | 9.52%   |
| KabyLake  | 2        | 9.52%   |
| Zen+      | 1        | 4.76%   |
| Zen       | 1        | 4.76%   |
| Skylake   | 1        | 4.76%   |
| Penryn    | 1        | 4.76%   |
| NetBurst  | 1        | 4.76%   |
| Nehalem   | 1        | 4.76%   |
| K8 Hammer | 1        | 4.76%   |
| CometLake | 1        | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 13       | 54.17%  |
| Intel  | 8        | 33.33%  |
| AMD    | 3        | 12.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 8.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 8.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 8.33%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 4.17%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 4.17%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                        | 1        | 4.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 4.17%   |
| Nvidia GP102 [TITAN Xp]                                                     | 1        | 4.17%   |
| Nvidia GK110GL [Quadro K5200]                                               | 1        | 4.17%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 4.17%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 4.17%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 4.17%   |
| Nvidia G98 [GeForce 9300 GS]                                                | 1        | 4.17%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 4.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 4.17%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 4.17%   |
| Intel HD Graphics 530                                                       | 1        | 4.17%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 4.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 4.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 4.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 11       | 52.38%  |
| 1 x Intel          | 5        | 23.81%  |
| 1 x AMD            | 2        | 9.52%   |
| Intel + 2 x Nvidia | 1        | 4.76%   |
| Intel + Nvidia     | 1        | 4.76%   |
| Intel + AMD        | 1        | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 57.14%  |
| Proprietary | 6        | 28.57%  |
| Unknown     | 3        | 14.29%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 33.33%  |
| 7.01-8.0   | 5        | 23.81%  |
| 1.01-2.0   | 3        | 14.29%  |
| 0.01-0.5   | 3        | 14.29%  |
| 3.01-4.0   | 1        | 4.76%   |
| 2.01-3.0   | 1        | 4.76%   |
| 0.51-1.0   | 1        | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| BenQ                 | 3        | 15.79%  |
| Ancor Communications | 3        | 15.79%  |
| Samsung Electronics  | 2        | 10.53%  |
| Goldstar             | 2        | 10.53%  |
| Dell                 | 2        | 10.53%  |
| Panasonic            | 1        | 5.26%   |
| Mi                   | 1        | 5.26%   |
| LG Electronics       | 1        | 5.26%   |
| Lenovo               | 1        | 5.26%   |
| Hewlett-Packard      | 1        | 5.26%   |
| Gigabyte Technology  | 1        | 5.26%   |
| AOC                  | 1        | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 1        | 5%      |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1        | 5%      |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 1        | 5%      |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                     | 1        | 5%      |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                    | 1        | 5%      |
| Lenovo L24e-30 LEN66BC 1920x1080 527x296mm 23.8-inch                 | 1        | 5%      |
| Hewlett-Packard LCD Monitor HWP4101 1920x1080 470x270mm 21.3-inch    | 1        | 5%      |
| Goldstar LG HDR 4K GSM7750 3840x2160 700x400mm 31.7-inch             | 1        | 5%      |
| Goldstar 24MP76 GSM5A28 1920x1080 530x300mm 24.0-inch                | 1        | 5%      |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch       | 1        | 5%      |
| Dell E1914H DELD03A 1366x768 410x230mm 18.5-inch                     | 1        | 5%      |
| Dell 2407WFP DELA017 1920x1200 520x330mm 24.2-inch                   | 1        | 5%      |
| BenQ XL2720Z BNQ7F29 1920x1080 597x336mm 27.0-inch                   | 1        | 5%      |
| BenQ RL2455 BNQ7F1C 1920x1080 531x298mm 24.0-inch                    | 1        | 5%      |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 1        | 5%      |
| BenQ GW2406Z BNQ78E1 1920x1080 527x296mm 23.8-inch                   | 1        | 5%      |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                      | 1        | 5%      |
| Ancor Communications VG248 ACI24A4 1920x1080 530x300mm 24.0-inch     | 1        | 5%      |
| Ancor Communications LCD Monitor ASUS PB287 3840x2160                | 1        | 5%      |
| Ancor Communications ASUS VT207 ACI20F4 1600x900 458x256mm 20.7-inch | 1        | 5%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 8        | 42.11%  |
| 3840x2160 (4K)    | 3        | 15.79%  |
| 2560x1440 (QHD)   | 2        | 10.53%  |
| 1366x768 (WXGA)   | 2        | 10.53%  |
| 3440x1440         | 1        | 5.26%   |
| 2560x1080         | 1        | 5.26%   |
| 1920x1200 (WUXGA) | 1        | 5.26%   |
| 1600x900 (HD+)    | 1        | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 6        | 31.58%  |
| 31      | 2        | 10.53%  |
| 23      | 2        | 10.53%  |
| 18      | 2        | 10.53%  |
| Unknown | 2        | 10.53%  |
| 84      | 1        | 5.26%   |
| 34      | 1        | 5.26%   |
| 27      | 1        | 5.26%   |
| 21      | 1        | 5.26%   |
| 20      | 1        | 5.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 47.37%  |
| 401-500     | 4        | 21.05%  |
| 601-700     | 2        | 10.53%  |
| Unknown     | 2        | 10.53%  |
| 701-800     | 1        | 5.26%   |
| 1501-2000   | 1        | 5.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 12       | 70.59%  |
| 16/10   | 2        | 11.76%  |
| Unknown | 2        | 11.76%  |
| 21/9    | 1        | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 31.58%  |
| 351-500        | 3        | 15.79%  |
| 251-300        | 2        | 10.53%  |
| 151-200        | 2        | 10.53%  |
| 141-150        | 2        | 10.53%  |
| Unknown        | 2        | 10.53%  |
| More than 1000 | 1        | 5.26%   |
| 301-350        | 1        | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 13       | 72.22%  |
| 101-120 | 2        | 11.11%  |
| Unknown | 2        | 11.11%  |
| 121-160 | 1        | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 71.43%  |
| 0     | 3        | 14.29%  |
| 2     | 2        | 9.52%   |
| 3     | 1        | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 12       | 35.29%  |
| Realtek Semiconductor    | 10       | 29.41%  |
| Broadcom                 | 3        | 8.82%   |
| Qualcomm Atheros         | 2        | 5.88%   |
| Wilocity                 | 1        | 2.94%   |
| VIA Technologies         | 1        | 2.94%   |
| SILICON Laboratories     | 1        | 2.94%   |
| Sigma Designs            | 1        | 2.94%   |
| Nvidia                   | 1        | 2.94%   |
| Marvell Technology Group | 1        | 2.94%   |
| D-Link                   | 1        | 2.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 8        | 21.62%  |
| Intel I211 Gigabit Network Connection                                   | 2        | 5.41%   |
| Intel Ethernet Connection (2) I219-V                                    | 2        | 5.41%   |
| Intel Ethernet Connection (2) I218-V                                    | 2        | 5.41%   |
| Intel 82579V Gigabit Network Connection                                 | 2        | 5.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2        | 5.41%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                      | 1        | 2.7%    |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1        | 2.7%    |
| SILICON Laboratories Intel 537 [Winmodem]                               | 1        | 2.7%    |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                         | 1        | 2.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 2.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1        | 2.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 2.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1        | 2.7%    |
| Nvidia MCP61 Ethernet                                                   | 1        | 2.7%    |
| Marvell Group 88E8070 based Ethernet Controller                         | 1        | 2.7%    |
| Intel Wireless 8260                                                     | 1        | 2.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 2.7%    |
| Intel I350 Gigabit Network Connection                                   | 1        | 2.7%    |
| Intel I210 Gigabit Network Connection                                   | 1        | 2.7%    |
| Intel Ethernet Connection I217-V                                        | 1        | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 1        | 2.7%    |
| Intel 82578DM Gigabit Network Connection                                | 1        | 2.7%    |
| D-Link DWA-127 Wireless N 150 High-Gain Adapter(rev.A1) [Ralink RT3070] | 1        | 2.7%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                        | 1        | 2.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 22.22%  |
| Intel                 | 2        | 22.22%  |
| Broadcom              | 2        | 22.22%  |
| Wilocity              | 1        | 11.11%  |
| Qualcomm Atheros      | 1        | 11.11%  |
| D-Link                | 1        | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2        | 22.22%  |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                      | 1        | 11.11%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 11.11%  |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1        | 11.11%  |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 11.11%  |
| Intel Wireless 8260                                                     | 1        | 11.11%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 11.11%  |
| D-Link DWA-127 Wireless N 150 High-Gain Adapter(rev.A1) [Ralink RT3070] | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 10       | 43.48%  |
| Realtek Semiconductor    | 8        | 34.78%  |
| VIA Technologies         | 1        | 4.35%   |
| Qualcomm Atheros         | 1        | 4.35%   |
| Nvidia                   | 1        | 4.35%   |
| Marvell Technology Group | 1        | 4.35%   |
| Broadcom                 | 1        | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 30.77%  |
| Intel I211 Gigabit Network Connection                             | 2        | 7.69%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 7.69%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 7.69%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 7.69%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 3.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 3.85%   |
| Nvidia MCP61 Ethernet                                             | 1        | 3.85%   |
| Marvell Group 88E8070 based Ethernet Controller                   | 1        | 3.85%   |
| Intel I350 Gigabit Network Connection                             | 1        | 3.85%   |
| Intel I210 Gigabit Network Connection                             | 1        | 3.85%   |
| Intel Ethernet Connection I217-V                                  | 1        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 3.85%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 3.85%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 21       | 67.74%  |
| WiFi     | 8        | 25.81%  |
| Modem    | 2        | 6.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 79.17%  |
| WiFi     | 5        | 20.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 57.14%  |
| 2     | 6        | 28.57%  |
| 3     | 2        | 9.52%   |
| 4     | 1        | 4.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 80.95%  |
| Yes  | 4        | 19.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 4        | 50%     |
| Intel                   | 2        | 25%     |
| Cambridge Silicon Radio | 2        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2        | 25%     |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2        | 25%     |
| Intel Bluetooth wireless interface                    | 1        | 12.5%   |
| Intel AX210 Bluetooth                                 | 1        | 12.5%   |
| ASUS Bluetooth Radio                                  | 1        | 12.5%   |
| ASUS Bluetooth Device                                 | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Intel              | 18       | 48.65%  |
| Nvidia             | 11       | 29.73%  |
| AMD                | 4        | 10.81%  |
| SteelSeries ApS    | 1        | 2.7%    |
| JMTek              | 1        | 2.7%    |
| Griffin Technology | 1        | 2.7%    |
| Apogee Electronics | 1        | 2.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 5%      |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 5%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 5%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 5%      |
| Intel 200 Series PCH HD Audio                                              | 2        | 5%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 5%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 5%      |
| SteelSeries ApS SteelSeries Arctis 5                                       | 1        | 2.5%    |
| Nvidia TU104 HD Audio Controller                                           | 1        | 2.5%    |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 2.5%    |
| Nvidia MCP61 High Definition Audio                                         | 1        | 2.5%    |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 2.5%    |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 2.5%    |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 2.5%    |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 2.5%    |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 2.5%    |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 2.5%    |
| JMTek USB PnP Audio Device(EEPROM)                                         | 1        | 2.5%    |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 2.5%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 2.5%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 2.5%    |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                       | 1        | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 2.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.5%    |
| Griffin Technology iMic                                                    | 1        | 2.5%    |
| Apogee Electronics Groove                                                  | 1        | 2.5%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 2.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 3        | 37.5%   |
| Crucial             | 2        | 25%     |
| Samsung Electronics | 1        | 12.5%   |
| Micron Technology   | 1        | 12.5%   |
| Kingston            | 1        | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Samsung RAM M393B1K70DH0-YH9 8GB DIMM DDR3 1333MT/s      | 1        | 12.5%   |
| Micron RAM 36JSZF51272PZ1G4F1 4096MB DIMM DDR3 1333MT/s  | 1        | 12.5%   |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 2667MT/s   | 1        | 12.5%   |
| Crucial RAM BLT8G3D1608DT2TXOB 8192MB DIMM DDR3 1600MT/s | 1        | 12.5%   |
| Crucial RAM BLS8G4D30BESBK.8FD 8GB DIMM DDR4 3000MT/s    | 1        | 12.5%   |
| Corsair RAM CMZ8GX3M1A1600C10 8192MB DIMM DDR3 1600MT/s  | 1        | 12.5%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s    | 1        | 12.5%   |
| Corsair RAM CMD32GX4M4A2800C16 8192MB DIMM DDR4 2133MT/s | 1        | 12.5%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 4        | 57.14%  |
| DDR3 | 3        | 42.86%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 7        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 6        | 75%     |
| 16384 | 1        | 12.5%   |
| 4096  | 1        | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 2        | 28.57%  |
| 3400  | 1        | 14.29%  |
| 3000  | 1        | 14.29%  |
| 2667  | 1        | 14.29%  |
| 2133  | 1        | 14.29%  |
| 1333  | 1        | 14.29%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP Deskjet F2280 series | 1        | 50%     |
| Brother MFC-9330CDW     | 1        | 50%     |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Samsung Electronics         | 1        | 14.29%  |
| Logitech                    | 1        | 14.29%  |
| LG Electronics              | 1        | 14.29%  |
| KYE Systems (Mouse Systems) | 1        | 14.29%  |
| Creative Technology         | 1        | 14.29%  |
| Chicony Electronics         | 1        | 14.29%  |
| Apple                       | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)                               | 1        | 14.29%  |
| Logitech Webcam C270                                  | 1        | 14.29%  |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 14.29%  |
| KYE Systems (Mouse Systems) WideCam 1050              | 1        | 14.29%  |
| Creative Live! Cam Socialize HD 1080 [VF0680]         | 1        | 14.29%  |
| Chicony HP Webcam                                     | 1        | 14.29%  |
| Apple iPhone5/5C/5S/6                                 | 1        | 14.29%  |

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 16       | 76.19%  |
| 1     | 3        | 14.29%  |
| 2     | 2        | 9.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Graphics card    | 3        | 42.86%  |
| Unassigned class | 2        | 28.57%  |
| Modem            | 1        | 14.29%  |
| Camera           | 1        | 14.29%  |

