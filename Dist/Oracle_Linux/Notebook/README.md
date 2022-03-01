Oracle Linux - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Oracle Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| HP       | ProBook 445 G6              | [88d8b32328](https://linux-hardware.org/?probe=88d8b32328) | Jan 26, 2022 |
| Lenovo   | ThinkPad T450 20BUS14900    | [44c8e11f02](https://linux-hardware.org/?probe=44c8e11f02) | Dec 22, 2021 |
| Lenovo   | IdeaPad 300-15ISK 80RS      | [1c9ca21f4e](https://linux-hardware.org/?probe=1c9ca21f4e) | Dec 10, 2021 |
| Dell     | Latitude 7410               | [3efa87284e](https://linux-hardware.org/?probe=3efa87284e) | Nov 18, 2021 |
| Dell     | Latitude E6420              | [b809392380](https://linux-hardware.org/?probe=b809392380) | Oct 08, 2021 |
| Dell     | Latitude 7410               | [8f1a1a4798](https://linux-hardware.org/?probe=8f1a1a4798) | Sep 06, 2021 |
| Dell     | Latitude 7410               | [b03a0e0152](https://linux-hardware.org/?probe=b03a0e0152) | Sep 06, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [2e24ad5259](https://linux-hardware.org/?probe=2e24ad5259) | Aug 19, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [32ad696b97](https://linux-hardware.org/?probe=32ad696b97) | Aug 18, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [2ccb1f7da2](https://linux-hardware.org/?probe=2ccb1f7da2) | Aug 16, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [b2d5f563dc](https://linux-hardware.org/?probe=b2d5f563dc) | Aug 15, 2021 |
| Dell     | Inspiron 3542               | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | [0225c17d79](https://linux-hardware.org/?probe=0225c17d79) | Jul 02, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| ASUSTek  | UX305FA                     | [0bf50fba2d](https://linux-hardware.org/?probe=0bf50fba2d) | Mar 15, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [ff355a9bb1](https://linux-hardware.org/?probe=ff355a9bb1) | Mar 11, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [20ac06d200](https://linux-hardware.org/?probe=20ac06d200) | Mar 06, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [9f67379954](https://linux-hardware.org/?probe=9f67379954) | Mar 04, 2021 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | [db0f24aee5](https://linux-hardware.org/?probe=db0f24aee5) | Mar 01, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [f0c8352496](https://linux-hardware.org/?probe=f0c8352496) | Mar 01, 2021 |
| Dell     | Latitude 7410               | [5b725b01aa](https://linux-hardware.org/?probe=5b725b01aa) | Feb 26, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [3145841279](https://linux-hardware.org/?probe=3145841279) | Feb 25, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Dell     | Latitude 7410               | [430ac9fa0c](https://linux-hardware.org/?probe=430ac9fa0c) | Feb 24, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [73aece12d7](https://linux-hardware.org/?probe=73aece12d7) | Feb 24, 2021 |
| Lenovo   | ThinkPad T490 20N3S77600    | [26e61c39f2](https://linux-hardware.org/?probe=26e61c39f2) | Feb 24, 2021 |
| Dell     | Latitude 7410               | [7aeb2cc674](https://linux-hardware.org/?probe=7aeb2cc674) | Feb 22, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [58cdbf1ae1](https://linux-hardware.org/?probe=58cdbf1ae1) | Feb 18, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [8af2c8d83c](https://linux-hardware.org/?probe=8af2c8d83c) | Feb 05, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [685b544c29](https://linux-hardware.org/?probe=685b544c29) | Jan 12, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [68957c71fd](https://linux-hardware.org/?probe=68957c71fd) | Jan 07, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [7d50d4e9d5](https://linux-hardware.org/?probe=7d50d4e9d5) | Jan 07, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [7ea3c87bfe](https://linux-hardware.org/?probe=7ea3c87bfe) | Jan 06, 2021 |
| Standard | BW Series                   | [1f6cf82ba8](https://linux-hardware.org/?probe=1f6cf82ba8) | Jun 13, 2020 |
| HP       | Notebook                    | [e3c242a846](https://linux-hardware.org/?probe=e3c242a846) | May 24, 2020 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | [d8b2c132c1](https://linux-hardware.org/?probe=d8b2c132c1) | Apr 09, 2020 |
| HP       | ZBook 15                    | [4723616d8c](https://linux-hardware.org/?probe=4723616d8c) | Apr 09, 2020 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | [1acbabb197](https://linux-hardware.org/?probe=1acbabb197) | Apr 06, 2020 |
| Lenovo   | ThinkPad T480 20L6S56Y2X    | [5343997520](https://linux-hardware.org/?probe=5343997520) | Feb 23, 2020 |
| ASUSTek  | X510UR                      | [914b9fbe64](https://linux-hardware.org/?probe=914b9fbe64) | Feb 04, 2020 |
| ASUSTek  | X510UR                      | [014d5ef0c8](https://linux-hardware.org/?probe=014d5ef0c8) | Jan 28, 2020 |
| ASUSTek  | X510UR                      | [9d05b420d4](https://linux-hardware.org/?probe=9d05b420d4) | Jan 28, 2020 |
| Lenovo   | ThinkPad L540 20AVCTO1WW    | [8c1dba9d6e](https://linux-hardware.org/?probe=8c1dba9d6e) | Sep 10, 2019 |
| Lenovo   | ThinkPad T480 20L6S56Y2X    | [f012a475eb](https://linux-hardware.org/?probe=f012a475eb) | Apr 11, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.17-2036.103.3.1.el8uek.x86_64  | 3         | 11.54%  |
| 5.4.17-2102.204.4.2.el8uek.x86_64  | 2         | 7.69%   |
| 5.4.17-2102.202.5.el8uek.x86_64    | 2         | 7.69%   |
| 4.18.0-147.3.1.el8_1.x86_64        | 2         | 7.69%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64  | 1         | 3.85%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64  | 1         | 3.85%   |
| 5.4.17-2102.201.3.el8uek.x86_64    | 1         | 3.85%   |
| 5.4.17-2102.200.13.el8uek.x86_64   | 1         | 3.85%   |
| 5.4.17-2036.104.4.el8uek.x86_64    | 1         | 3.85%   |
| 5.4.17-2011.0.7.el8uek.x86_64      | 1         | 3.85%   |
| 5.15.2-1.el8.elrepo.x86_64         | 1         | 3.85%   |
| 5.14.1-1.el8.elrepo.x86_64         | 1         | 3.85%   |
| 5.11.1-1.el8.elrepo.x86_64         | 1         | 3.85%   |
| 4.18.0-348.12.2.el8_5.x86_64       | 1         | 3.85%   |
| 4.18.0-240.10.1.el8_3.x86_64       | 1         | 3.85%   |
| 4.18.0-193.1.2.el8_2.x86_64        | 1         | 3.85%   |
| 4.14.35-2047.510.4.1.el7uek.x86_64 | 1         | 3.85%   |
| 4.14.35-1902.4.8.el7uek.x86_64     | 1         | 3.85%   |
| 4.14.35-1902.300.11.el7uek.x86_64  | 1         | 3.85%   |
| 4.14.35-1818.3.3.el7uek.x86_64     | 1         | 3.85%   |
| 3.10.0-1127.10.1.el7.x86_64        | 1         | 3.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.17  | 7         | 35%     |
| 4.18.0  | 5         | 25%     |
| 4.14.35 | 4         | 20%     |
| 5.15.2  | 1         | 5%      |
| 5.14.1  | 1         | 5%      |
| 5.11.1  | 1         | 5%      |
| 3.10.0  | 1         | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 7         | 35%     |
| 4.18    | 5         | 25%     |
| 4.14    | 4         | 20%     |
| 5.15    | 1         | 5%      |
| 5.14    | 1         | 5%      |
| 5.11    | 1         | 5%      |
| 3.10    | 1         | 5%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 18        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 13        | 65%     |
| XFCE    | 2         | 10%     |
| MATE    | 2         | 10%     |
| Unknown | 2         | 10%     |
| KDE4    | 1         | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 13        | 65%     |
| Wayland | 7         | 35%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 12        | 63.16%  |
| GDM     | 7         | 36.84%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 11        | 57.89%  |
| de_DE   | 3         | 15.79%  |
| Unknown | 2         | 10.53%  |
| pt_BR   | 1         | 5.26%   |
| pl_PL   | 1         | 5.26%   |
| en_GB   | 1         | 5.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 10        | 52.63%  |
| EFI  | 9         | 47.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 13        | 68.42%  |
| Ext4    | 4         | 21.05%  |
| Unknown | 2         | 10.53%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 15        | 78.95%  |
| GPT     | 3         | 15.79%  |
| MBR     | 1         | 5.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 88.89%  |
| Yes       | 2         | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 8         | 44.44%  |
| Hewlett-Packard  | 3         | 16.67%  |
| Dell             | 3         | 16.67%  |
| ASUSTek Computer | 3         | 16.67%  |
| Standard         | 1         | 5.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| ASUS X510UR                         | 2         | 11.11%  |
| Standard BW Series                  | 1         | 5.56%   |
| Lenovo ThinkPad T490 20N3S77600     | 1         | 5.56%   |
| Lenovo ThinkPad T480 20L6S56Y2X     | 1         | 5.56%   |
| Lenovo ThinkPad T450 20BUS14900     | 1         | 5.56%   |
| Lenovo ThinkPad L540 20AVCTO1WW     | 1         | 5.56%   |
| Lenovo ThinkPad L490 20Q5CTO1WW     | 1         | 5.56%   |
| Lenovo Legion 5 15IMH05 82AU        | 1         | 5.56%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS | 1         | 5.56%   |
| Lenovo IdeaPad 300-15ISK 80RS       | 1         | 5.56%   |
| HP ZBook 15                         | 1         | 5.56%   |
| HP ProBook 445 G6                   | 1         | 5.56%   |
| HP Notebook                         | 1         | 5.56%   |
| Dell Latitude E6420                 | 1         | 5.56%   |
| Dell Latitude 7410                  | 1         | 5.56%   |
| Dell Inspiron 3542                  | 1         | 5.56%   |
| ASUS UX305FA                        | 1         | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo ThinkPad | 5         | 27.78%  |
| Lenovo IdeaPad  | 2         | 11.11%  |
| Dell Latitude   | 2         | 11.11%  |
| ASUS X510UR     | 2         | 11.11%  |
| Standard BW     | 1         | 5.56%   |
| Lenovo Legion   | 1         | 5.56%   |
| HP ZBook        | 1         | 5.56%   |
| HP ProBook      | 1         | 5.56%   |
| HP Notebook     | 1         | 5.56%   |
| Dell Inspiron   | 1         | 5.56%   |
| ASUS UX305FA    | 1         | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 4         | 22.22%  |
| 2016 | 3         | 16.67%  |
| 2014 | 3         | 16.67%  |
| 2020 | 2         | 11.11%  |
| 2017 | 2         | 11.11%  |
| 2018 | 1         | 5.56%   |
| 2015 | 1         | 5.56%   |
| 2013 | 1         | 5.56%   |
| 2011 | 1         | 5.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 18        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 16        | 88.89%  |
| Enabled  | 2         | 11.11%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 18        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 5         | 26.32%  |
| 8.01-16.0  | 5         | 26.32%  |
| 32.01-64.0 | 3         | 15.79%  |
| 3.01-4.0   | 3         | 15.79%  |
| 16.01-24.0 | 3         | 15.79%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 7         | 29.17%  |
| 2.01-3.0  | 7         | 29.17%  |
| 3.01-4.0  | 3         | 12.5%   |
| 1.01-2.0  | 3         | 12.5%   |
| 8.01-16.0 | 3         | 12.5%   |
| 0.51-1.0  | 1         | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 17        | 94.44%  |
| 2      | 1         | 5.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 13        | 72.22%  |
| Yes       | 5         | 27.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 72.22%  |
| No        | 5         | 27.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 68.42%  |
| No        | 6         | 31.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 5         | 26.32%  |
| Germany     | 4         | 21.05%  |
| Netherlands | 2         | 10.53%  |
| Brazil      | 2         | 10.53%  |
| UK          | 1         | 5.26%   |
| Romania     | 1         | 5.26%   |
| Poland      | 1         | 5.26%   |
| Pakistan    | 1         | 5.26%   |
| Bulgaria    | 1         | 5.26%   |
| Argentina   | 1         | 5.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Utrecht          | 1         | 4.76%   |
| SГЈo Paulo     | 1         | 4.76%   |
| Sofia            | 1         | 4.76%   |
| Siegen           | 1         | 4.76%   |
| Santo AndrÃ©   | 1         | 4.76%   |
| Port Saint Lucie | 1         | 4.76%   |
| Polch            | 1         | 4.76%   |
| Maple Valley     | 1         | 4.76%   |
| Kreuztal         | 1         | 4.76%   |
| Karachi          | 1         | 4.76%   |
| Ituzaingo        | 1         | 4.76%   |
| Freudenberg      | 1         | 4.76%   |
| Eppelheim        | 1         | 4.76%   |
| Dallas           | 1         | 4.76%   |
| Colorado Springs | 1         | 4.76%   |
| ChorzÃ³w       | 1         | 4.76%   |
| Chicago          | 1         | 4.76%   |
| Bucharest        | 1         | 4.76%   |
| Bracknell        | 1         | 4.76%   |
| Berlin           | 1         | 4.76%   |
| Amsterdam        | 1         | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| SanDisk                 | 6         | 7      | 31.58%  |
| Samsung Electronics     | 5         | 7      | 26.32%  |
| WDC                     | 1         | 1      | 5.26%   |
| Unknown                 | 1         | 1      | 5.26%   |
| Union Memory (Shenzhen) | 1         | 2      | 5.26%   |
| Seagate                 | 1         | 1      | 5.26%   |
| Micron Technology       | 1         | 4      | 5.26%   |
| Lite-On                 | 1         | 1      | 5.26%   |
| Kingston                | 1         | 5      | 5.26%   |
| HGST                    | 1         | 1      | 5.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| SanDisk SSD PLUS 1000GB                      | 2         | 10%     |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 5%      |
| Unknown SD/MMC/MS PRO 64GB                   | 1         | 5%      |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 5%      |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 5%      |
| SanDisk SDSSDH3512G 512GB                    | 1         | 5%      |
| SanDisk SD7SN3Q256G1002 256GB SSD            | 1         | 5%      |
| SanDisk SD6SB1M-256G-1006 256GB SSD          | 1         | 5%      |
| Sandisk NVMe SSD Drive 512GB                 | 1         | 5%      |
| Samsung SSD PM830 2.5 7mm 256GB              | 1         | 5%      |
| Samsung SSD 850 PRO 256GB                    | 1         | 5%      |
| Samsung NVMe SSD Drive 512GB                 | 1         | 5%      |
| Samsung MZ7LN512HMJP-000L7 512GB SSD         | 1         | 5%      |
| Samsung MZ7LN256HCHP-000L7 256GB SSD         | 1         | 5%      |
| Micron NVMe SSD Drive 256GB                  | 1         | 5%      |
| Micron 2200S NVMe 256GB                      | 1         | 5%      |
| Lite-On NVMe SSD Drive 512GB                 | 1         | 5%      |
| Kingston NVMe SSD Drive 1TB                  | 1         | 5%      |
| HGST HTS545050A7E380 500GB                   | 1         | 5%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| Unknown | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 5         | 5      | 55.56%  |
| Samsung Electronics | 4         | 4      | 44.44%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 9         | 9      | 47.37%  |
| NVMe | 6         | 17     | 31.58%  |
| HDD  | 4         | 4      | 21.05%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 12        | 12     | 63.16%  |
| NVMe | 6         | 17     | 31.58%  |
| SAS  | 1         | 1      | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7         | 7      | 53.85%  |
| 0.51-1.0   | 6         | 6      | 46.15%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 31.58%  |
| 101-250    | 5         | 26.32%  |
| 251-500    | 4         | 21.05%  |
| 501-1000   | 2         | 10.53%  |
| 1-20       | 1         | 5.26%   |
| 51-100     | 1         | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 7         | 35%     |
| Unknown | 6         | 30%     |
| 21-50   | 3         | 15%     |
| 101-250 | 2         | 10%     |
| 251-500 | 1         | 5%      |
| 51-100  | 1         | 5%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 100%    |

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
| Detected | 14        | 25     | 73.68%  |
| Works    | 4         | 4      | 21.05%  |
| Malfunc  | 1         | 1      | 5.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 11        | 55%     |
| AMD                         | 3         | 15%     |
| Union Memory (Shenzhen)     | 1         | 5%      |
| Sandisk                     | 1         | 5%      |
| Samsung Electronics         | 1         | 5%      |
| Micron Technology           | 1         | 5%      |
| Lite-On Technology          | 1         | 5%      |
| Kingston Technology Company | 1         | 5%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 15%     |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 15%     |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 10%     |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 10%     |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 5%      |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 5%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 5%      |
| Micron Non-Volatile memory controller                                            | 1         | 5%      |
| Lite-On Non-Volatile memory controller                                           | 1         | 5%      |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 5%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 5%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 5%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 5%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 5%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 13        | 65%     |
| NVMe | 6         | 30%     |
| RAID | 1         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 83.33%  |
| AMD    | 3         | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 11.11%  |
| Intel Processor 5Y10 CPU @ 0.80GHz              | 1         | 5.56%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 1         | 5.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 5.56%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 5.56%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 5.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 5.56%   |
| Intel Core i7-10610U CPU @ 1.80GHz              | 1         | 5.56%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 5.56%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 1         | 5.56%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 1         | 5.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 5.56%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 5.56%   |
| Intel Celeron CPU N3010 @ 1.04GHz               | 1         | 5.56%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 1         | 5.56%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 5.56%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 5.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 8         | 44.44%  |
| Intel Core i5   | 5         | 27.78%  |
| Other           | 2         | 11.11%  |
| Intel Celeron   | 1         | 5.56%   |
| AMD Ryzen 7 PRO | 1         | 5.56%   |
| AMD A8          | 1         | 5.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 9         | 50%     |
| 4      | 7         | 38.89%  |
| 6      | 1         | 5.56%   |
| 1      | 1         | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 15        | 83.33%  |
| 1      | 3         | 16.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 17        | 89.47%  |
| Unknown        | 2         | 10.53%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 3         | 16.67%  |
| 0x306d4    | 2         | 11.11%  |
| 0x306c3    | 2         | 11.11%  |
| Unknown    | 2         | 11.11%  |
| 0xa0652    | 1         | 5.56%   |
| 0x806ea    | 1         | 5.56%   |
| 0x406e3    | 1         | 5.56%   |
| 0x406c4    | 1         | 5.56%   |
| 0x40651    | 1         | 5.56%   |
| 0x206a7    | 1         | 5.56%   |
| 0x0810100b | 1         | 5.56%   |
| 0x07030105 | 1         | 5.56%   |
| 0x06006705 | 1         | 5.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 6         | 33.33%  |
| Haswell     | 3         | 16.67%  |
| Broadwell   | 2         | 11.11%  |
| Zen         | 1         | 5.56%   |
| Skylake     | 1         | 5.56%   |
| Silvermont  | 1         | 5.56%   |
| SandyBridge | 1         | 5.56%   |
| Puma        | 1         | 5.56%   |
| Excavator   | 1         | 5.56%   |
| CometLake   | 1         | 5.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 14        | 58.33%  |
| Nvidia | 6         | 25%     |
| AMD    | 4         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 8.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 8.33%   |
| Intel HD Graphics 620                                                                    | 2         | 8.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 8.33%   |
| Nvidia TU117M                                                                            | 1         | 4.17%   |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 4.17%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 4.17%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 4.17%   |
| Intel UHD Graphics 620                                                                   | 1         | 4.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 4.17%   |
| Intel HD Graphics 5500                                                                   | 1         | 4.17%   |
| Intel HD Graphics 5300                                                                   | 1         | 4.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 4.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 4.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 4.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 4.17%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 4.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 4.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 4.17%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 8         | 44.44%  |
| Intel + Nvidia | 5         | 27.78%  |
| 1 x AMD        | 3         | 16.67%  |
| 1 x Nvidia     | 1         | 5.56%   |
| Intel + AMD    | 1         | 5.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 16        | 88.89%  |
| Proprietary | 1         | 5.56%   |
| Unknown     | 1         | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 42.11%  |
| 1.01-2.0   | 5         | 26.32%  |
| 3.01-4.0   | 3         | 15.79%  |
| 0.01-0.5   | 2         | 10.53%  |
| 0.51-1.0   | 1         | 5.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 7         | 31.82%  |
| AU Optronics        | 5         | 22.73%  |
| Chimei Innolux      | 2         | 9.09%   |
| BenQ                | 2         | 9.09%   |
| ViewSonic           | 1         | 4.55%   |
| Samsung Electronics | 1         | 4.55%   |
| Lenovo              | 1         | 4.55%   |
| InfoVision          | 1         | 4.55%   |
| BOE                 | 1         | 4.55%   |
| ASUSTek Computer    | 1         | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 9.09%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 9.09%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 4.55%   |
| LG Display LCD Monitor LGD0609 1920x1080 309x174mm 14.0-inch          | 1         | 4.55%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 4.55%   |
| LG Display LCD Monitor LGD047C 1366x768 310x174mm 14.0-inch           | 1         | 4.55%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 4.55%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 4.55%   |
| Lenovo T24i-10 LEN61A6 1920x1080 530x300mm 24.0-inch                  | 1         | 4.55%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN14E8 1920x1080 309x173mm 13.9-inch      | 1         | 4.55%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                 | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO212D 1920x1080 293x165mm 13.2-inch        | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 1         | 4.55%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch          | 1         | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 11        | 64.71%  |
| 1366x768 (WXGA) | 4         | 23.53%  |
| 1600x900 (HD+)  | 2         | 11.76%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 8         | 36.36%  |
| 14     | 7         | 31.82%  |
| 27     | 2         | 9.09%   |
| 24     | 2         | 9.09%   |
| 13     | 2         | 9.09%   |
| 23     | 1         | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 76.19%  |
| 501-600     | 4         | 19.05%  |
| 201-300     | 1         | 4.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 17        | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 38.1%   |
| 101-110        | 8         | 38.1%   |
| 301-350        | 2         | 9.52%   |
| 201-250        | 2         | 9.52%   |
| 71-80          | 1         | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 12        | 57.14%  |
| 101-120 | 4         | 19.05%  |
| 51-100  | 4         | 19.05%  |
| 161-240 | 1         | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 13        | 72.22%  |
| 2     | 3         | 16.67%  |
| 3     | 1         | 5.56%   |
| 0     | 1         | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 12        | 44.44%  |
| Realtek Semiconductor | 6         | 22.22%  |
| Qualcomm Atheros      | 3         | 11.11%  |
| Lenovo                | 2         | 7.41%   |
| Ralink Technology     | 1         | 3.7%    |
| NetGear               | 1         | 3.7%    |
| Fibocom               | 1         | 3.7%    |
| Broadcom              | 1         | 3.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 11.11%  |
| Intel Wireless 8265 / 8275                                        | 3         | 8.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 5.56%   |
| Intel Wireless 7265                                               | 2         | 5.56%   |
| Intel Wireless 7260                                               | 2         | 5.56%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 5.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 2.78%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 2.78%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2.78%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1         | 2.78%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 2.78%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 2.78%   |
| Intel Wireless-AC 9260                                            | 1         | 2.78%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 2.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 2.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.78%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 1         | 2.78%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 2.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 12        | 57.14%  |
| Qualcomm Atheros      | 3         | 14.29%  |
| Realtek Semiconductor | 2         | 9.52%   |
| Ralink Technology     | 1         | 4.76%   |
| NetGear               | 1         | 4.76%   |
| Fibocom               | 1         | 4.76%   |
| Broadcom              | 1         | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                 | 3         | 14.29%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 9.52%   |
| Intel Wireless 7265                                        | 2         | 9.52%   |
| Intel Wireless 7260                                        | 2         | 9.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 4.76%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 4.76%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 4.76%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]            | 1         | 4.76%   |
| Intel Wireless-AC 9260                                     | 1         | 4.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 4.76%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 4.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 1         | 4.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 1         | 4.76%   |
| Fibocom L830-EB-00 LTE WWAN Modem                          | 1         | 4.76%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 7         | 46.67%  |
| Realtek Semiconductor | 6         | 40%     |
| Lenovo                | 2         | 13.33%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 26.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 13.33%  |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 13.33%  |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 6.67%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 6.67%   |
| Intel Ethernet Connection I217-V                                  | 1         | 6.67%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 6.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 6.67%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 6.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 18        | 58.06%  |
| Ethernet | 13        | 41.94%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 62.96%  |
| Ethernet | 10        | 37.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 13        | 72.22%  |
| 1     | 5         | 27.78%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 16        | 80%     |
| Yes  | 4         | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 61.54%  |
| Qualcomm Atheros Communications | 3         | 23.08%  |
| Realtek Semiconductor           | 1         | 7.69%   |
| Broadcom                        | 1         | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface       | 3         | 23.08%  |
| Qualcomm Atheros  Bluetooth Device       | 2         | 15.38%  |
| Intel Bluetooth Device                   | 2         | 15.38%  |
| Intel AX201 Bluetooth                    | 2         | 15.38%  |
| Realtek  Bluetooth 4.2 Adapter           | 1         | 7.69%   |
| Qualcomm Atheros AR9462 Bluetooth        | 1         | 7.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter | 1         | 7.69%   |
| Broadcom BCM43142A0 Bluetooth 4.0        | 1         | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 15        | 57.69%  |
| Nvidia    | 3         | 11.54%  |
| Lenovo    | 3         | 11.54%  |
| AMD       | 3         | 11.54%  |
| Unknown   | 1         | 3.85%   |
| GN Netcom | 1         | 3.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 12.12%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 6.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 6.06%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 6.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 6.06%   |
| Unknown Definitive Sym1                                                                           | 1         | 3.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 3.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 3.03%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 3.03%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 1         | 3.03%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 3.03%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 3.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 3.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 3.03%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 3.03%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 3.03%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 3.03%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 3.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 3.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 3.03%   |
| AMD High Definition Audio Controller                                                              | 1         | 3.03%   |
| AMD FCH Azalia Controller                                                                         | 1         | 3.03%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 3.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 3.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 42.86%  |
| SK Hynix            | 2         | 28.57%  |
| Kingston            | 1         | 14.29%  |
| Avant               | 1         | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 28.57%  |
| SK Hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 14.29%  |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s | 1         | 14.29%  |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 14.29%  |
| Kingston RAM KX830D-ELC 4096MB SODIMM DDR3 1333MT/s          | 1         | 14.29%  |
| Avant RAM H6451U66G1600G 4096MB SODIMM DDR3 1600MT/s         | 1         | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR3 | 5         | 71.43%  |
| DDR4 | 2         | 28.57%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 5         | 71.43%  |
| Row Of Chips | 2         | 28.57%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 4         | 57.14%  |
| 8192 | 3         | 42.86%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 4         | 57.14%  |
| 2667  | 1         | 14.29%  |
| 1866  | 1         | 14.29%  |
| 1333  | 1         | 14.29%  |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 5         | 33.33%  |
| Suyin                 | 3         | 20%     |
| Realtek Semiconductor | 2         | 13.33%  |
| IMC Networks          | 2         | 13.33%  |
| Microdia              | 1         | 6.67%   |
| Logitech              | 1         | 6.67%   |
| Lite-On Technology    | 1         | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 4         | 26.67%  |
| IMC Networks USB2.0 VGA UVC WebCam      | 2         | 13.33%  |
| Suyin Integrated_Webcam_HD              | 1         | 6.67%   |
| Suyin HP Truevision HD                  | 1         | 6.67%   |
| Suyin Asus Integrated Webcam            | 1         | 6.67%   |
| Realtek Integrated_Webcam_HD            | 1         | 6.67%   |
| Realtek EasyCamera                      | 1         | 6.67%   |
| Microdia Webcam Vitade AF               | 1         | 6.67%   |
| Logitech Webcam C920-C                  | 1         | 6.67%   |
| Lite-On HP HD Camera                    | 1         | 6.67%   |
| Chicony Integrated Camera (1280x720@30) | 1         | 6.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Synaptics        | 3         | 60%     |
| Validity Sensors | 2         | 40%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 20%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 20%     |
| Unknown                                                                    | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Broadcom 58200                                 | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 10        | 52.63%  |
| 1     | 6         | 31.58%  |
| 2     | 2         | 10.53%  |
| 3     | 1         | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 5         | 41.67%  |
| Graphics card      | 2         | 16.67%  |
| Chipcard           | 2         | 16.67%  |
| Storage            | 1         | 8.33%   |
| Net/wireless       | 1         | 8.33%   |
| Card reader        | 1         | 8.33%   |

