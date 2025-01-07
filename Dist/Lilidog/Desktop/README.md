Lilidog - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Lilidog.

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

Total: 35

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire XC-330               | [25b998dd59](https://linux-hardware.org/?probe=25b998dd59) | Oct 06, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [7df5552411](https://linux-hardware.org/?probe=7df5552411) | Sep 11, 2024 |
| HP            | 2B2C                        | [8cc39031cb](https://linux-hardware.org/?probe=8cc39031cb) | Aug 29, 2024 |
| ASUSTek       | M5A78L-M LX3                | [9b33f3fab6](https://linux-hardware.org/?probe=9b33f3fab6) | Jul 14, 2024 |
| HP            | 0B54h D                     | [24348ad5a4](https://linux-hardware.org/?probe=24348ad5a4) | Jun 25, 2024 |
| ASUSTek       | M5A78L-M LX3                | [1fc3d8e29b](https://linux-hardware.org/?probe=1fc3d8e29b) | Jun 03, 2024 |
| HP            | 1825                        | [3d90cc7481](https://linux-hardware.org/?probe=3d90cc7481) | Mar 31, 2024 |
| Shenzhen M... | F6BFC                       | [14060f87a1](https://linux-hardware.org/?probe=14060f87a1) | Mar 12, 2024 |
| Shenzhen M... | F6BFC                       | [207f92c903](https://linux-hardware.org/?probe=207f92c903) | Feb 18, 2024 |
| HP            | 1998                        | [b193235ba4](https://linux-hardware.org/?probe=b193235ba4) | Jan 17, 2024 |
| Dell          | 0M5DCD A00                  | [6f8ca5724f](https://linux-hardware.org/?probe=6f8ca5724f) | Aug 10, 2023 |
| Dell          | 0GM819                      | [744413006e](https://linux-hardware.org/?probe=744413006e) | Apr 20, 2023 |
| Unknown       | X79M2-Q                     | [d985b7fa11](https://linux-hardware.org/?probe=d985b7fa11) | Apr 05, 2023 |
| Foxconn       | NETBOX NT-425/525 Ver       | [dfb8c476f9](https://linux-hardware.org/?probe=dfb8c476f9) | Jan 21, 2023 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | [d50f9357b4](https://linux-hardware.org/?probe=d50f9357b4) | Jan 18, 2023 |
| Dell          | 0WMJ54 A01                  | [fece850cae](https://linux-hardware.org/?probe=fece850cae) | Jan 15, 2023 |
| Dell          | 03NVJ6 A02                  | [a16b955eed](https://linux-hardware.org/?probe=a16b955eed) | Jan 15, 2023 |
| ASUSTek       | PRIME H510M-K               | [9b1f8e9a10](https://linux-hardware.org/?probe=9b1f8e9a10) | Dec 18, 2022 |
| HP            | 805B                        | [111fb196ff](https://linux-hardware.org/?probe=111fb196ff) | Nov 16, 2022 |
| Dell          | 0DF42J A00                  | [52e8355edf](https://linux-hardware.org/?probe=52e8355edf) | Nov 12, 2022 |
| Biostar       | A320MH                      | [d01d91204f](https://linux-hardware.org/?probe=d01d91204f) | Oct 27, 2022 |
| Biostar       | A320MH                      | [768dff7065](https://linux-hardware.org/?probe=768dff7065) | Oct 27, 2022 |
| Gigabyte      | B365M DS3H                  | [603fc4f4cd](https://linux-hardware.org/?probe=603fc4f4cd) | Oct 15, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [4bc8ad9e5f](https://linux-hardware.org/?probe=4bc8ad9e5f) | Oct 12, 2022 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | [b30ac8d979](https://linux-hardware.org/?probe=b30ac8d979) | Oct 05, 2022 |
| Dell          | 0GM819                      | [7778e245a9](https://linux-hardware.org/?probe=7778e245a9) | Sep 06, 2022 |
| HP            | 805B                        | [602a9470ab](https://linux-hardware.org/?probe=602a9470ab) | Aug 22, 2022 |
| ASUSTek       | H110M-A/DP                  | [01dccaff29](https://linux-hardware.org/?probe=01dccaff29) | Jul 07, 2022 |
| ASUSTek       | H110M-A/DP                  | [356272d726](https://linux-hardware.org/?probe=356272d726) | Jul 04, 2022 |
| Gigabyte      | MZBAYAP-00                  | [f8a734d114](https://linux-hardware.org/?probe=f8a734d114) | Jun 20, 2022 |
| Gigabyte      | MZBAYAP-00                  | [8fb623d313](https://linux-hardware.org/?probe=8fb623d313) | Jun 17, 2022 |
| eMachines     | EL1352                      | [562e729c18](https://linux-hardware.org/?probe=562e729c18) | May 15, 2022 |
| HP            | 212B                        | [d6deb6ed52](https://linux-hardware.org/?probe=d6deb6ed52) | May 04, 2022 |
| HP            | 21EF                        | [f619d0dfc0](https://linux-hardware.org/?probe=f619d0dfc0) | Apr 14, 2022 |
| Dell          | 0HJ054                      | [77ae3bc631](https://linux-hardware.org/?probe=77ae3bc631) | Apr 11, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Lilidog 22 | 17       | 65.38%  |
| Lilidog 23 | 6        | 23.08%  |
| Lilidog 24 | 3        | 11.54%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Lilidog | 26       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.10.0-18-amd64           | 3        | 10.34%  |
| 5.10.0-13-amd64           | 3        | 10.34%  |
| 6.1.0-25-amd64            | 2        | 6.9%    |
| 6.0.8-x64v1-xanmod1       | 2        | 6.9%    |
| 6.7.12+bpo-amd64          | 1        | 3.45%   |
| 6.6.13+bpo-amd64          | 1        | 3.45%   |
| 6.5.0-0.deb12.4-amd64     | 1        | 3.45%   |
| 6.2.11-x64v1-xanmod1      | 1        | 3.45%   |
| 6.1.0-7.2-liquorix-amd64  | 1        | 3.45%   |
| 6.1.0-23-amd64            | 1        | 3.45%   |
| 6.1.0-21-amd64            | 1        | 3.45%   |
| 6.1.0-18-amd64            | 1        | 3.45%   |
| 6.1.0-10-amd64            | 1        | 3.45%   |
| 6.0.0-5-amd64             | 1        | 3.45%   |
| 6.0.0-0.deb11.6-amd64     | 1        | 3.45%   |
| 5.19.0-7.1-liquorix-amd64 | 1        | 3.45%   |
| 5.19.0-0.deb11.2-amd64    | 1        | 3.45%   |
| 5.18.0-1-amd64            | 1        | 3.45%   |
| 5.10.0-21-amd64           | 1        | 3.45%   |
| 5.10.0-20-amd64           | 1        | 3.45%   |
| 5.10.0-19-amd64           | 1        | 3.45%   |
| 5.10.0-16-amd64           | 1        | 3.45%   |
| 5.10.0-14-amd64           | 1        | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 11       | 37.93%  |
| 6.1.0   | 7        | 24.14%  |
| 6.0.8   | 2        | 6.9%    |
| 6.0.0   | 2        | 6.9%    |
| 5.19.0  | 2        | 6.9%    |
| 6.7.12  | 1        | 3.45%   |
| 6.6.13  | 1        | 3.45%   |
| 6.5.0   | 1        | 3.45%   |
| 6.2.11  | 1        | 3.45%   |
| 5.18.0  | 1        | 3.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 11       | 37.93%  |
| 6.1     | 7        | 24.14%  |
| 6.0     | 4        | 13.79%  |
| 5.19    | 2        | 6.9%    |
| 6.7     | 1        | 3.45%   |
| 6.6     | 1        | 3.45%   |
| 6.5     | 1        | 3.45%   |
| 6.2     | 1        | 3.45%   |
| 5.18    | 1        | 3.45%   |

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


| Name             | Desktops | Percent |
|------------------|----------|---------|
| lightdm-xsession | 20       | 71.43%  |
| openbox          | 7        | 25%     |
| XFCE             | 1        | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 26       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 26       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 19       | 73.08%  |
| es_ES | 2        | 7.69%   |
| ru_RU | 1        | 3.85%   |
| es_MX | 1        | 3.85%   |
| es_AR | 1        | 3.85%   |
| en_GB | 1        | 3.85%   |
| de_DE | 1        | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 14       | 53.85%  |
| BIOS | 12       | 46.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 19       | 70.37%  |
| Overlay | 5        | 18.52%  |
| Btrfs   | 3        | 11.11%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 20       | 76.92%  |
| MBR  | 6        | 23.08%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 53.85%  |
| Yes       | 12       | 46.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 76.92%  |
| Yes       | 6        | 23.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Hewlett-Packard                      | 6        | 23.08%  |
| Dell                                 | 6        | 23.08%  |
| ASUSTek Computer                     | 4        | 15.38%  |
| Gigabyte Technology                  | 3        | 11.54%  |
| Shenzhen Meigao Electronic Equipment | 1        | 3.85%   |
| Lenovo                               | 1        | 3.85%   |
| Foxconn                              | 1        | 3.85%   |
| eMachines                            | 1        | 3.85%   |
| Biostar                              | 1        | 3.85%   |
| Acer                                 | 1        | 3.85%   |
| Unknown                              | 1        | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Shenzhen Meigao Electronic Equipment UM560 | 1        | 3.85%   |
| Lenovo Legion T7 34IMZ5 90Q800AJMH         | 1        | 3.85%   |
| HP Z600 Workstation                        | 1        | 3.85%   |
| HP t520 Flexible Series TC                 | 1        | 3.85%   |
| HP EliteDesk 800 G1 SFF                    | 1        | 3.85%   |
| HP EliteDesk 800 G1 DM                     | 1        | 3.85%   |
| HP EliteDesk 705 G2 MINI                   | 1        | 3.85%   |
| HP 2B2C                                    | 1        | 3.85%   |
| Gigabyte PERSONAL COMPUTER                 | 1        | 3.85%   |
| Gigabyte B450 AORUS PRO                    | 1        | 3.85%   |
| Gigabyte B365M DS3H                        | 1        | 3.85%   |
| Foxconn NETBOX NT-425/525                  | 1        | 3.85%   |
| eMachines EL1352                           | 1        | 3.85%   |
| Dell XPS 8930                              | 1        | 3.85%   |
| Dell OptiPlex 780                          | 1        | 3.85%   |
| Dell OptiPlex 755                          | 1        | 3.85%   |
| Dell OptiPlex 390                          | 1        | 3.85%   |
| Dell OptiPlex 3020                         | 1        | 3.85%   |
| Dell DM051                                 | 1        | 3.85%   |
| Biostar A320MH                             | 1        | 3.85%   |
| ASUS PRIME H610M-K D4                      | 1        | 3.85%   |
| ASUS PRIME H510M-K                         | 1        | 3.85%   |
| ASUS M5A78L-M LX3                          | 1        | 3.85%   |
| ASUS H110M-A/DP                            | 1        | 3.85%   |
| Acer Aspire XC-330                         | 1        | 3.85%   |
| Unknown                                    | 1        | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 4        | 15.38%  |
| HP EliteDesk                               | 3        | 11.54%  |
| ASUS PRIME                                 | 2        | 7.69%   |
| Shenzhen Meigao Electronic Equipment UM560 | 1        | 3.85%   |
| Lenovo Legion                              | 1        | 3.85%   |
| HP Z600                                    | 1        | 3.85%   |
| HP t520                                    | 1        | 3.85%   |
| HP 2B2C                                    | 1        | 3.85%   |
| Gigabyte PERSONAL                          | 1        | 3.85%   |
| Gigabyte B450                              | 1        | 3.85%   |
| Gigabyte B365M                             | 1        | 3.85%   |
| Foxconn NETBOX                             | 1        | 3.85%   |
| eMachines EL1352                           | 1        | 3.85%   |
| Dell XPS                                   | 1        | 3.85%   |
| Dell DM051                                 | 1        | 3.85%   |
| Biostar A320MH                             | 1        | 3.85%   |
| ASUS M5A78L-M                              | 1        | 3.85%   |
| ASUS H110M-A                               | 1        | 3.85%   |
| Acer Aspire                                | 1        | 3.85%   |
| Unknown                                    | 1        | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2010 | 4        | 15.38%  |
| 2021 | 3        | 11.54%  |
| 2015 | 3        | 11.54%  |
| 2014 | 3        | 11.54%  |
| 2019 | 2        | 7.69%   |
| 2018 | 2        | 7.69%   |
| 2017 | 2        | 7.69%   |
| 2022 | 1        | 3.85%   |
| 2016 | 1        | 3.85%   |
| 2013 | 1        | 3.85%   |
| 2012 | 1        | 3.85%   |
| 2011 | 1        | 3.85%   |
| 2007 | 1        | 3.85%   |
| 2006 | 1        | 3.85%   |

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


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 8        | 30.77%  |
| 16.01-24.0 | 6        | 23.08%  |
| 3.01-4.0   | 4        | 15.38%  |
| 8.01-16.0  | 3        | 11.54%  |
| 32.01-64.0 | 2        | 7.69%   |
| 2.01-3.0   | 2        | 7.69%   |
| 0.51-1.0   | 1        | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.51-1.0  | 14       | 51.85%  |
| 1.01-2.0  | 9        | 33.33%  |
| 0.01-0.5  | 2        | 7.41%   |
| 2.01-3.0  | 1        | 3.7%    |
| 8.01-16.0 | 1        | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 37.04%  |
| 2      | 9        | 33.33%  |
| 3      | 6        | 22.22%  |
| 4      | 2        | 7.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 62.96%  |
| Yes       | 10       | 37.04%  |

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
| Yes       | 13       | 50%     |
| No        | 13       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 76.92%  |
| Yes       | 6        | 23.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 9        | 34.62%  |
| UK          | 2        | 7.69%   |
| Spain       | 2        | 7.69%   |
| Germany     | 2        | 7.69%   |
| Argentina   | 2        | 7.69%   |
| Taiwan      | 1        | 3.85%   |
| Russia      | 1        | 3.85%   |
| Romania     | 1        | 3.85%   |
| Poland      | 1        | 3.85%   |
| Netherlands | 1        | 3.85%   |
| Mexico      | 1        | 3.85%   |
| Italy       | 1        | 3.85%   |
| Indonesia   | 1        | 3.85%   |
| Austria     | 1        | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Travelers Rest              | 2        | 7.14%   |
| Fayetteville                | 2        | 7.14%   |
| Charlotte                   | 2        | 7.14%   |
| Zapopan                     | 1        | 3.57%   |
| Workum                      | 1        | 3.57%   |
| Worcester                   | 1        | 3.57%   |
| Vienna                      | 1        | 3.57%   |
| St Petersburg               | 1        | 3.57%   |
| San Nicolás de los Arroyos | 1        | 3.57%   |
| Rzeszów                    | 1        | 3.57%   |
| Rome                        | 1        | 3.57%   |
| Rincon de Soto              | 1        | 3.57%   |
| Palembang                   | 1        | 3.57%   |
| Oradea                      | 1        | 3.57%   |
| Memphis                     | 1        | 3.57%   |
| Langelsheim                 | 1        | 3.57%   |
| Idsegahuizum                | 1        | 3.57%   |
| Golden Valley               | 1        | 3.57%   |
| Fongshan District           | 1        | 3.57%   |
| Conway                      | 1        | 3.57%   |
| Burzaco                     | 1        | 3.57%   |
| Bradford                    | 1        | 3.57%   |
| Bonn                        | 1        | 3.57%   |
| Barnsley                    | 1        | 3.57%   |
| Barcelona                   | 1        | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 13     | 23.4%   |
| Kingston            | 7        | 9      | 14.89%  |
| WDC                 | 6        | 11     | 12.77%  |
| Toshiba             | 3        | 3      | 6.38%   |
| SanDisk             | 3        | 3      | 6.38%   |
| Samsung Electronics | 3        | 4      | 6.38%   |
| Crucial             | 3        | 4      | 6.38%   |
| SK hynix            | 2        | 2      | 4.26%   |
| Hitachi             | 2        | 3      | 4.26%   |
| USB30               | 1        | 1      | 2.13%   |
| Silicon Motion      | 1        | 1      | 2.13%   |
| Phison              | 1        | 2      | 2.13%   |
| OWC                 | 1        | 2      | 2.13%   |
| Micron Technology   | 1        | 1      | 2.13%   |
| Intel               | 1        | 1      | 2.13%   |
| A-DATA Technology   | 1        | 1      | 2.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD      | 3        | 6.25%   |
| Toshiba DT01ACA100 1TB               | 2        | 4.17%   |
| SK hynix C2S3T/480G 480GB SSD        | 2        | 4.17%   |
| Seagate ST500DM002-1BD142 500GB      | 2        | 4.17%   |
| Seagate ST1000DM010-2EP102 1TB       | 2        | 4.17%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1        | 2.08%   |
| WDC WD800JD-75MSA3 80GB              | 1        | 2.08%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1        | 2.08%   |
| WDC WD50 00AAKX-08U6AA0 500GB        | 1        | 2.08%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1        | 2.08%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1        | 2.08%   |
| USB30 Disk 240GB                     | 1        | 2.08%   |
| Toshiba MQ01ABF050 500GB             | 1        | 2.08%   |
| Silicon Motion NE-128 128GB          | 1        | 2.08%   |
| Seagate ST9500420AS 500GB            | 1        | 2.08%   |
| Seagate ST500VM000-1SD101 500GB      | 1        | 2.08%   |
| Seagate ST3160023AS 160GB            | 1        | 2.08%   |
| Seagate ST2000DX002-2DV164 2TB       | 1        | 2.08%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 2.08%   |
| Seagate ST1000DM003-1CH162 1TB       | 1        | 2.08%   |
| Seagate Expansion 1TB                | 1        | 2.08%   |
| Seagate BUP Slim BK 2TB              | 1        | 2.08%   |
| SanDisk SSD PLUS 480GB               | 1        | 2.08%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD   | 1        | 2.08%   |
| SanDisk SD7SB6S128G1122 128GB SSD    | 1        | 2.08%   |
| Samsung SSD 870 EVO 250GB            | 1        | 2.08%   |
| Samsung PSSD T7 1TB                  | 1        | 2.08%   |
| Samsung MZ7TE128HMGR-000L1 128GB SSD | 1        | 2.08%   |
| Phison ESO512GYLCT-EP3-2L 512GB      | 1        | 2.08%   |
| OWC Mercury EXTREME Pro 6G SSD       | 1        | 2.08%   |
| Micron CT1000X9SSD9 1TB              | 1        | 2.08%   |
| Kingston SV300S37A120G 120GB SSD     | 1        | 2.08%   |
| Kingston SUV500M8120G 120GB SSD      | 1        | 2.08%   |
| Kingston SHSS37A240G 240GB SSD       | 1        | 2.08%   |
| Kingston SA400S37240G 240GB SSD      | 1        | 2.08%   |
| Intel MEMPEK1W032GA 32GB             | 1        | 2.08%   |
| Hitachi HDS721680PLA380 80GB         | 1        | 2.08%   |
| Hitachi HDS721016CLA382 160GB        | 1        | 2.08%   |
| Crucial CT250MX500SSD1 250GB         | 1        | 2.08%   |
| Crucial CT240BX500SSD1 240GB         | 1        | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 13     | 55%     |
| WDC     | 4        | 5      | 20%     |
| Toshiba | 3        | 3      | 15%     |
| Hitachi | 2        | 3      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 7        | 9      | 30.43%  |
| SanDisk             | 3        | 3      | 13.04%  |
| Samsung Electronics | 3        | 4      | 13.04%  |
| Crucial             | 3        | 4      | 13.04%  |
| SK hynix            | 2        | 2      | 8.7%    |
| WDC                 | 1        | 2      | 4.35%   |
| USB30               | 1        | 1      | 4.35%   |
| OWC                 | 1        | 2      | 4.35%   |
| Micron Technology   | 1        | 1      | 4.35%   |
| A-DATA Technology   | 1        | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 17       | 29     | 47.22%  |
| HDD  | 15       | 24     | 41.67%  |
| NVMe | 4        | 8      | 11.11%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 26       | 46     | 74.29%  |
| SAS  | 5        | 7      | 14.29%  |
| NVMe | 4        | 8      | 11.43%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 20       | 35     | 62.5%   |
| 0.51-1.0   | 9        | 14     | 28.13%  |
| 1.01-2.0   | 3        | 4      | 9.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 11       | 40.74%  |
| 1001-2000  | 5        | 18.52%  |
| 251-500    | 4        | 14.81%  |
| 1-20       | 3        | 11.11%  |
| 501-1000   | 2        | 7.41%   |
| 21-50      | 1        | 3.7%    |
| 51-100     | 1        | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 21       | 75%     |
| 101-250   | 3        | 10.71%  |
| 51-100    | 2        | 7.14%   |
| 21-50     | 1        | 3.57%   |
| 1001-2000 | 1        | 3.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB             | 2        | 2      | 18.18%  |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1        | 2      | 9.09%   |
| WDC WD800JD-75MSA3 80GB            | 1        | 1      | 9.09%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 2      | 9.09%   |
| Seagate ST9500420AS 500GB          | 1        | 1      | 9.09%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1      | 9.09%   |
| Seagate ST1000DM003-1CH162 1TB     | 1        | 1      | 9.09%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD | 1        | 1      | 9.09%   |
| OWC Mercury EXTREME Pro 6G SSD     | 1        | 2      | 9.09%   |
| Crucial CT1000MX500SSD1 1TB        | 1        | 2      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 5      | 27.27%  |
| Seagate | 3        | 3      | 27.27%  |
| Toshiba | 2        | 2      | 18.18%  |
| SanDisk | 1        | 1      | 9.09%   |
| OWC     | 1        | 2      | 9.09%   |
| Crucial | 1        | 2      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 42.86%  |
| WDC     | 2        | 3      | 28.57%  |
| Toshiba | 2        | 2      | 28.57%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 8      | 63.64%  |
| SSD  | 4        | 7      | 36.36%  |

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
| Works    | 21       | 39     | 56.76%  |
| Malfunc  | 11       | 15     | 29.73%  |
| Detected | 5        | 7      | 13.51%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Intel              | 19       | 63.33%  |
| AMD                | 7        | 23.33%  |
| Silicon Motion     | 1        | 3.33%   |
| SanDisk            | 1        | 3.33%   |
| Phison Electronics | 1        | 3.33%   |
| Nvidia             | 1        | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 15%     |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 10%     |
| Intel SATA Controller [RAID Mode]                                                       | 2        | 5%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 5%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 5%      |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 2.5%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 1        | 2.5%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 1        | 2.5%    |
| Nvidia MCP61 SATA Controller                                                            | 1        | 2.5%    |
| Nvidia MCP61 IDE                                                                        | 1        | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 2.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 2.5%    |
| Intel NVMe Optane Memory Series                                                         | 1        | 2.5%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 2.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 2.5%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 2.5%    |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 2.5%    |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 1        | 2.5%    |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 1        | 2.5%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 2.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 2.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.5%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 2.5%    |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 1        | 2.5%    |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 20       | 58.82%  |
| IDE  | 7        | 20.59%  |
| NVMe | 4        | 11.76%  |
| RAID | 3        | 8.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 18       | 69.23%  |
| AMD    | 8        | 30.77%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 2        | 7.69%   |
| Intel Xeon CPU E5640 @ 2.67GHz                 | 1        | 3.85%   |
| Intel Xeon CPU E5-2643 0 @ 3.30GHz             | 1        | 3.85%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz         | 1        | 3.85%   |
| Intel Pentium D CPU 2.80GHz                    | 1        | 3.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 3.85%   |
| Intel Core i7-4785T CPU @ 2.20GHz              | 1        | 3.85%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 3.85%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 3.85%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 3.85%   |
| Intel Core i5-4460 CPU @ 3.20GHz               | 1        | 3.85%   |
| Intel Core i3-4160 CPU @ 3.60GHz               | 1        | 3.85%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 3.85%   |
| Intel Celeron CPU N2807 @ 1.58GHz              | 1        | 3.85%   |
| Intel Atom CPU D525 @ 1.80GHz                  | 1        | 3.85%   |
| Intel 12th Gen Core i3-12100F                  | 1        | 3.85%   |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz       | 1        | 3.85%   |
| AMD Ryzen 5 5625U with Radeon Graphics         | 1        | 3.85%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 1        | 3.85%   |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G   | 1        | 3.85%   |
| AMD GX-212JC SOC with Radeon R2E Graphics      | 1        | 3.85%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 3.85%   |
| AMD Athlon II 170u Processor                   | 1        | 3.85%   |
| AMD A4-9120 RADEON R3, 4 COMPUTE CORES 2C+2G   | 1        | 3.85%   |
| AMD A12-9800 RADEON R7, 12 COMPUTE CORES 4C+8G | 1        | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 4        | 15.38%  |
| Other              | 2        | 7.69%   |
| Intel Xeon         | 2        | 7.69%   |
| Intel Core i7      | 2        | 7.69%   |
| Intel Core i3      | 2        | 7.69%   |
| Intel Core 2 Duo   | 2        | 7.69%   |
| AMD Ryzen 5        | 2        | 7.69%   |
| Intel Pentium Gold | 1        | 3.85%   |
| Intel Pentium D    | 1        | 3.85%   |
| Intel Celeron      | 1        | 3.85%   |
| Intel Atom         | 1        | 3.85%   |
| AMD PRO A10        | 1        | 3.85%   |
| AMD GX             | 1        | 3.85%   |
| AMD FX             | 1        | 3.85%   |
| AMD Athlon II      | 1        | 3.85%   |
| AMD A4             | 1        | 3.85%   |
| AMD A12            | 1        | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 12       | 46.15%  |
| 4      | 7        | 26.92%  |
| 6      | 3        | 11.54%  |
| 8      | 2        | 7.69%   |
| 3      | 1        | 3.85%   |
| 1      | 1        | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 96.15%  |
| 2      | 1        | 3.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 15       | 57.69%  |
| 1      | 11       | 42.31%  |

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
| Unknown    | 4        | 14.81%  |
| 0x306c3    | 2        | 7.41%   |
| 0x1067a    | 2        | 7.41%   |
| 0x0600611a | 2        | 7.41%   |
| 0xf44      | 1        | 3.7%    |
| 0xa0671    | 1        | 3.7%    |
| 0xa0653    | 1        | 3.7%    |
| 0x906ed    | 1        | 3.7%    |
| 0x906ea    | 1        | 3.7%    |
| 0x906e9    | 1        | 3.7%    |
| 0x90675    | 1        | 3.7%    |
| 0x30678    | 1        | 3.7%    |
| 0x206d7    | 1        | 3.7%    |
| 0x206c2    | 1        | 3.7%    |
| 0x206a7    | 1        | 3.7%    |
| 0x106ca    | 1        | 3.7%    |
| 0x0a50000d | 1        | 3.7%    |
| 0x0810100b | 1        | 3.7%    |
| 0x07030104 | 1        | 3.7%    |
| 0x06006705 | 1        | 3.7%    |
| 0x010000c8 | 1        | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 4        | 14.81%  |
| KabyLake         | 3        | 11.11%  |
| Excavator        | 3        | 11.11%  |
| SandyBridge      | 2        | 7.41%   |
| Penryn           | 2        | 7.41%   |
| Zen 3            | 1        | 3.7%    |
| Zen              | 1        | 3.7%    |
| Westmere         | 1        | 3.7%    |
| Silvermont       | 1        | 3.7%    |
| Puma             | 1        | 3.7%    |
| Piledriver       | 1        | 3.7%    |
| NetBurst         | 1        | 3.7%    |
| K10              | 1        | 3.7%    |
| Icelake          | 1        | 3.7%    |
| CometLake        | 1        | 3.7%    |
| Bonnell          | 1        | 3.7%    |
| Alderlake Hybrid | 1        | 3.7%    |
| Unknown          | 1        | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 11       | 39.29%  |
| AMD    | 11       | 39.29%  |
| Nvidia | 6        | 21.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.9%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 6.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 6.9%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 3.45%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 3.45%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 3.45%   |
| Nvidia GF119 [GeForce GT 705]                                               | 1        | 3.45%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 3.45%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 3.45%   |
| Intel HD Graphics 630                                                       | 1        | 3.45%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 1        | 3.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 3.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 3.45%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 3.45%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 3.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 3.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 3.45%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 1        | 3.45%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                       | 1        | 3.45%   |
| AMD RV370 [Radeon X600/X600 SE]                                             | 1        | 3.45%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 3.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 3.45%   |
| AMD Mullins [Radeon R1E/R2E Graphics]                                       | 1        | 3.45%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 3.45%   |
| AMD Barcelo                                                                 | 1        | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 10       | 37.04%  |
| 1 x AMD    | 10       | 37.04%  |
| 1 x Nvidia | 6        | 22.22%  |
| 2 x AMD    | 1        | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 26       | 96.3%   |
| Proprietary | 1        | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 39.29%  |
| 0.01-0.5   | 8        | 28.57%  |
| 0.51-1.0   | 3        | 10.71%  |
| 7.01-8.0   | 2        | 7.14%   |
| 3.01-4.0   | 2        | 7.14%   |
| 1.01-2.0   | 1        | 3.57%   |
| 8.01-16.0  | 1        | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 12%     |
| Dell                | 3        | 12%     |
| Hewlett-Packard     | 2        | 8%      |
| Goldstar            | 2        | 8%      |
| Zoran               | 1        | 4%      |
| Vizio               | 1        | 4%      |
| Sony                | 1        | 4%      |
| Sceptre Tech        | 1        | 4%      |
| SAC                 | 1        | 4%      |
| Philips             | 1        | 4%      |
| Packard Bell        | 1        | 4%      |
| Mi                  | 1        | 4%      |
| MGN                 | 1        | 4%      |
| Lenovo              | 1        | 4%      |
| Insignia            | 1        | 4%      |
| eMachines           | 1        | 4%      |
| BenQ                | 1        | 4%      |
| ASUSTek Computer    | 1        | 4%      |
| Acer                | 1        | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Zoran HDMI TV ZRN0294 1360x768 500x281mm 22.6-inch                   | 1        | 4%      |
| Vizio E320-B2 VIZ0095 1360x768 477x268mm 21.5-inch                   | 1        | 4%      |
| Sony TV SNY0101 1360x768                                             | 1        | 4%      |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch        | 1        | 4%      |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch | 1        | 4%      |
| Samsung Electronics C32R50x SAM7001 1920x1080 698x393mm 31.5-inch    | 1        | 4%      |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch    | 1        | 4%      |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                | 1        | 4%      |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                   | 1        | 4%      |
| Packard Bell Maestro225DXL PKB02F2 1920x1080 477x268mm 21.5-inch     | 1        | 4%      |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                     | 1        | 4%      |
| MGN MAGNA TV MGN0021 1920x1080 575x323mm 26.0-inch                   | 1        | 4%      |
| Lenovo L24i-10 LEN65D6 1920x1080 527x296mm 23.8-inch                 | 1        | 4%      |
| Insignia DX-LCD32 BBYCD32 1360x768 709x399mm 32.0-inch               | 1        | 4%      |
| Hewlett-Packard W2271d HWP3102 1920x1080 477x268mm 21.5-inch         | 1        | 4%      |
| Hewlett-Packard 27yh HPN351C 1920x1080 598x336mm 27.0-inch           | 1        | 4%      |
| Goldstar ULTRAGEAR GSM776E 2560x1440 697x392mm 31.5-inch             | 1        | 4%      |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch               | 1        | 4%      |
| eMachines E15T4W EMA05E1 1280x800 332x207mm 15.4-inch                | 1        | 4%      |
| Dell P2415Q DELA0C0 3840x2160 527x296mm 23.8-inch                    | 1        | 4%      |
| Dell P2319H DELD0D5 1920x1080 510x290mm 23.1-inch                    | 1        | 4%      |
| Dell E152FP DELA009 1024x768 304x228mm 15.0-inch                     | 1        | 4%      |
| BenQ GW2320 BNQ78D3 1920x1080 509x286mm 23.0-inch                    | 1        | 4%      |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch         | 1        | 4%      |
| Acer EK220Q ACR0757 1920x1080 477x268mm 21.5-inch                    | 1        | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 15       | 62.5%   |
| 1360x768           | 3        | 12.5%   |
| 3840x2160 (4K)     | 1        | 4.17%   |
| 2560x1440 (QHD)    | 1        | 4.17%   |
| 1680x1050 (WSXGA+) | 1        | 4.17%   |
| 1366x768 (WXGA)    | 1        | 4.17%   |
| 1280x800 (WXGA)    | 1        | 4.17%   |
| 1024x768 (XGA)     | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 5        | 20%     |
| 31      | 4        | 16%     |
| 24      | 4        | 16%     |
| 23      | 4        | 16%     |
| 32      | 2        | 8%      |
| 15      | 2        | 8%      |
| 27      | 1        | 4%      |
| 26      | 1        | 4%      |
| 22      | 1        | 4%      |
| Unknown | 1        | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 40%     |
| 401-500     | 6        | 24%     |
| 601-700     | 4        | 16%     |
| 701-800     | 2        | 8%      |
| 301-350     | 2        | 8%      |
| Unknown     | 1        | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 20       | 86.96%  |
| 16/10 | 2        | 8.7%    |
| 4/3   | 1        | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 52%     |
| 351-500        | 6        | 24%     |
| 101-110        | 2        | 8%      |
| 301-350        | 1        | 4%      |
| 251-300        | 1        | 4%      |
| 151-200        | 1        | 4%      |
| Unknown        | 1        | 4%      |

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
| Unknown | 1        | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 25       | 92.59%  |
| 2     | 1        | 3.7%    |
| 0     | 1        | 3.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 14       | 40%     |
| Intel                           | 9        | 25.71%  |
| Qualcomm Atheros                | 3        | 8.57%   |
| Ralink Technology               | 2        | 5.71%   |
| Qualcomm Atheros Communications | 2        | 5.71%   |
| MediaTek                        | 2        | 5.71%   |
| Broadcom                        | 2        | 5.71%   |
| Nvidia                          | 1        | 2.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12       | 28.57%  |
| Realtek RTL8188EE Wireless Network Adapter                             | 3        | 7.14%   |
| Qualcomm Atheros AR9271 802.11n                                        | 2        | 4.76%   |
| Intel Ethernet Connection I217-LM                                      | 2        | 4.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 2.38%   |
| Realtek RTL8191SEvA Wireless LAN Controller                            | 1        | 2.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 2.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1        | 2.38%   |
| Ralink MT7601U Wireless Adapter                                        | 1        | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1        | 2.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 2.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 2.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 2.38%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 2.38%   |
| MediaTek TANK2                                                         | 1        | 2.38%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1        | 2.38%   |
| Intel Wireless 7260                                                    | 1        | 2.38%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 2.38%   |
| Intel I211 Gigabit Network Connection                                  | 1        | 2.38%   |
| Intel Ethernet Controller I225-V                                       | 1        | 2.38%   |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 2.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 2.38%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 2.38%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 2.38%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 2.38%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1        | 2.38%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1        | 2.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 5        | 35.71%  |
| Intel                           | 3        | 21.43%  |
| Ralink Technology               | 2        | 14.29%  |
| Qualcomm Atheros Communications | 2        | 14.29%  |
| Qualcomm Atheros                | 1        | 7.14%   |
| MediaTek                        | 1        | 7.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Realtek RTL8188EE Wireless Network Adapter                 | 3        | 21.43%  |
| Qualcomm Atheros AR9271 802.11n                            | 2        | 14.29%  |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 7.14%   |
| Realtek RTL8191SEvA Wireless LAN Controller                | 1        | 7.14%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 7.14%   |
| Ralink MT7601U Wireless Adapter                            | 1        | 7.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 7.14%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 1        | 7.14%   |
| Intel Wireless 7260                                        | 1        | 7.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 7.14%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1        | 7.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 46.43%  |
| Intel                 | 8        | 28.57%  |
| Qualcomm Atheros      | 3        | 10.71%  |
| Broadcom              | 2        | 7.14%   |
| Nvidia                | 1        | 3.57%   |
| MediaTek              | 1        | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12       | 42.86%  |
| Intel Ethernet Connection I217-LM                                      | 2        | 7.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 3.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 3.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 3.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 3.57%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 3.57%   |
| MediaTek TANK2                                                         | 1        | 3.57%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 3.57%   |
| Intel I211 Gigabit Network Connection                                  | 1        | 3.57%   |
| Intel Ethernet Controller I225-V                                       | 1        | 3.57%   |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 3.57%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 3.57%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 3.57%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1        | 3.57%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1        | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 66.67%  |
| WiFi     | 13       | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 74.07%  |
| WiFi     | 7        | 25.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 59.26%  |
| 2     | 10       | 37.04%  |
| 3     | 1        | 3.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 74.07%  |
| Yes  | 7        | 25.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 1        | 16.67%  |
| Qualcomm Atheros Communications | 1        | 16.67%  |
| MediaTek                        | 1        | 16.67%  |
| Intel                           | 1        | 16.67%  |
| IMC Networks                    | 1        | 16.67%  |
| Cambridge Silicon Radio         | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                             | 1        | 16.67%  |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 16.67%  |
| MediaTek Wireless_Device                            | 1        | 16.67%  |
| Intel AX201 Bluetooth                               | 1        | 16.67%  |
| IMC Networks Bluetooth Radio                        | 1        | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 18       | 51.43%  |
| AMD                 | 10       | 28.57%  |
| Nvidia              | 6        | 17.14%  |
| C-Media Electronics | 1        | 2.86%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 4        | 9.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 6.82%   |
| AMD Kabini HDMI/DP Audio                                                          | 3        | 6.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 3        | 6.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 4.55%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 4.55%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 2        | 4.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 4.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 2.27%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 2.27%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 2.27%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1        | 2.27%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 2.27%   |
| Nvidia GA102 High Definition Audio Controller                                     | 1        | 2.27%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 1        | 2.27%   |
| Intel HD Graphics SGPC                                                            | 1        | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 2.27%   |
| Intel Alder Lake-S HD Audio Controller                                            | 1        | 2.27%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 2.27%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 1        | 2.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 2.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1        | 2.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 2.27%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 1        | 2.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1        | 2.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1        | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 2.27%   |
| AMD High Definition Audio Controller                                              | 1        | 2.27%   |
| AMD FCH Azalia Controller                                                         | 1        | 2.27%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 2.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 5        | 14.71%  |
| Crucial             | 5        | 14.71%  |
| Unknown             | 4        | 11.76%  |
| Samsung Electronics | 4        | 11.76%  |
| Corsair             | 4        | 11.76%  |
| Micron Technology   | 3        | 8.82%   |
| Kingston            | 3        | 8.82%   |
| Unknown (08C8)      | 1        | 2.94%   |
| Team                | 1        | 2.94%   |
| Infineon            | 1        | 2.94%   |
| G.Skill             | 1        | 2.94%   |
| A-DATA Technology   | 1        | 2.94%   |
| Unknown             | 1        | 2.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 2        | 5.41%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1        | 2.7%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 1        | 2.7%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                    | 1        | 2.7%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 1        | 2.7%    |
| Unknown (08C8) RAM LMKUFG68AHFHD-32A 16GB DIMM DDR4 3200MT/s | 1        | 2.7%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s           | 1        | 2.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1        | 2.7%    |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s         | 1        | 2.7%    |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s         | 1        | 2.7%    |
| SK hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s         | 1        | 2.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 2.7%    |
| Samsung RAM M393B1K70CH0 8GB DIMM DDR3 1866MT/s              | 1        | 2.7%    |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3                   | 1        | 2.7%    |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s          | 1        | 2.7%    |
| Micron RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s         | 1        | 2.7%    |
| Micron RAM 4ATF51264AZ-2G3H1R 4GB DIMM DDR4 2400MT/s         | 1        | 2.7%    |
| Micron RAM 16HTF12864AY-53EB1 1GB DIMM DDR2 533MT/s          | 1        | 2.7%    |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                    | 1        | 2.7%    |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s                    | 1        | 2.7%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s         | 1        | 2.7%    |
| Kingston RAM HP655410-150-HYCG 4GB DIMM DDR3 1600MT/s        | 1        | 2.7%    |
| Infineon RAM 64T64000HU3.7A 512MB DIMM DDR 533MT/s           | 1        | 2.7%    |
| G.Skill RAM F2-6400CL5-2GBPQ 2GB DIMM DDR2 800MT/s           | 1        | 2.7%    |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s       | 1        | 2.7%    |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s        | 1        | 2.7%    |
| Crucial RAM CT25664AA800.C16FH 2GB DIMM DDR2 800MT/s         | 1        | 2.7%    |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s        | 1        | 2.7%    |
| Crucial RAM BLS4G4D26BFSE.8FB 4GB DIMM DDR4 2667MT/s         | 1        | 2.7%    |
| Crucial RAM BLS4G4D26BFSC.8FB 4GB DIMM DDR4 2400MT/s         | 1        | 2.7%    |
| Corsair RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                | 1        | 2.7%    |
| Corsair RAM CMV8GX4M1A2133C15 8GB DIMM DDR4 2733MT/s         | 1        | 2.7%    |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 3066MT/s         | 1        | 2.7%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 1        | 2.7%    |
| A-DATA RAM Module 8GB DIMM DDR4 3200MT/s                     | 1        | 2.7%    |
| Unknown                                                      | 1        | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 12       | 44.44%  |
| DDR4    | 10       | 37.04%  |
| DDR2    | 3        | 11.11%  |
| SDRAM   | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 21       | 80.77%  |
| SODIMM | 5        | 19.23%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 13       | 44.83%  |
| 4096  | 8        | 27.59%  |
| 1024  | 3        | 10.34%  |
| 2048  | 2        | 6.9%    |
| 32768 | 1        | 3.45%   |
| 16384 | 1        | 3.45%   |
| 512   | 1        | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 9        | 29.03%  |
| 3200  | 3        | 9.68%   |
| 3733  | 2        | 6.45%   |
| 2400  | 2        | 6.45%   |
| 1800  | 2        | 6.45%   |
| 1333  | 2        | 6.45%   |
| 667   | 2        | 6.45%   |
| 3600  | 1        | 3.23%   |
| 3066  | 1        | 3.23%   |
| 2733  | 1        | 3.23%   |
| 2667  | 1        | 3.23%   |
| 2666  | 1        | 3.23%   |
| 1866  | 1        | 3.23%   |
| 1066  | 1        | 3.23%   |
| 800   | 1        | 3.23%   |
| 533   | 1        | 3.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 2        | 66.67%  |
| Samsung Electronics | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung ML-191x/ML-252x Laser Printer | 1        | 33.33%  |
| HP DeskJet F4200 series               | 1        | 33.33%  |
| HP DeskJet 2130 series                | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 220 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech Logitech Webcam C160 | 1        | 100%    |

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
| 0     | 23       | 85.19%  |
| 1     | 4        | 14.81%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 2        | 50%     |
| Multimedia controller    | 1        | 25%     |
| Communication controller | 1        | 25%     |

