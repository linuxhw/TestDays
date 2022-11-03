MX 21 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for MX 21.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 50

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| MSI      | X570-A PRO               | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Biostar  | H61MH                    | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| Lenovo   | 318E NOK                 | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| Pegatron | NARRA3                   | [1588e60c57](https://linux-hardware.org/?probe=1588e60c57) | Oct 12, 2022 |
| ASUSTek  | Z170-P                   | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek  | P5GC-MX/CKD/SI           | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| ASUSTek  | P5G41T-M LX              | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| ASUSTek  | PRIME B450M-A            | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| HP       | 1632                     | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Medion   | H110H4-EM                | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| Gigabyte | B560M DS3H V2            | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Biostar  | A780L3B                  | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| Intel    | DH55TC AAE70932-303      | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| MP       | MS-7848                  | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI      | MAG B550 TOMAHAWK        | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek  | P8H61/USB3 R2.0          | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| AOpen    | D1009 A1A4               | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell     | 0DR845                   | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| MSI      | B350 TOMAHAWK            | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI      | Z77A-G41                 | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell     | 0200DY A01               | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell     | 0DR845                   | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Gigabyte | H410M S2H V3             | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| ASUSTek  | SABERTOOTH X99           | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Intel    | V1.3                     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| ASUSTek  | SABERTOOTH X99           | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| Gigabyte | B550M S2H                | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock   | N3150M                   | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte | B550M S2H                | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Dell     | 0YXT71 A01               | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo   | 1046 NO DPK              | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte | Z390 UD                  | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| HP       | 3647h                    | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek  | P5GC-MX/MEDION/SI        | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI      | MS-7091                  | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI      | MS-7091                  | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| ASUSTek  | ROG Maximus XIII HERO    | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan   | X99-F8 V2.0              | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan   | X99-F8 V2.0              | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| MSI      | Z97 GAMING 5             | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| ASUSTek  | X99-DELUXE               | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| HP       | 0B4Ch D                  | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| Fujitsu  | D3221-A1 S26361-D3221-A1 | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| GALAX    | B550M                    | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo   | SHARKBAY NO DPK          | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo   | SHARKBAY NO DPK          | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| ASRock   | X570 Steel Legend        | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Gigabyte | X570 AORUS PRO           | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| Gigabyte | B550M DS3H               | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Gigabyte | A320M-S2H V2-CF          | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.10.0-13-amd64            | 5        | 11.9%   |
| 5.14.0-4mx-amd64           | 4        | 9.52%   |
| 5.10.0-16-amd64            | 4        | 9.52%   |
| 5.10.0-15-amd64            | 4        | 9.52%   |
| 5.10.0-18-amd64            | 3        | 7.14%   |
| 5.16.0-5mx-amd64           | 2        | 4.76%   |
| 5.14.0-3mx-amd64           | 2        | 4.76%   |
| 5.10.0-9-amd64             | 2        | 4.76%   |
| 5.10.0-11-amd64            | 2        | 4.76%   |
| 6.0.5-x64v1-xanmod1        | 1        | 2.38%   |
| 5.19.0-4.2-liquorix-amd64  | 1        | 2.38%   |
| 5.19.0-17.2-liquorix-amd64 | 1        | 2.38%   |
| 5.16.0-rc5-hwmon-next+     | 1        | 2.38%   |
| 5.16.0-6mx-amd64           | 1        | 2.38%   |
| 5.15.0-2-amd64             | 1        | 2.38%   |
| 5.15.0-0.bpo.2-amd64       | 1        | 2.38%   |
| 5.14.0-2mx-amd64           | 1        | 2.38%   |
| 5.10.52-antix.1-amd64-smp  | 1        | 2.38%   |
| 5.10.111-tkg-cfs           | 1        | 2.38%   |
| 5.10.0-19-amd64            | 1        | 2.38%   |
| 5.10.0-18-686-pae          | 1        | 2.38%   |
| 5.10.0-17-amd64            | 1        | 2.38%   |
| 5.10.0-10-amd64            | 1        | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 24       | 57.14%  |
| 5.14.0   | 7        | 16.67%  |
| 5.16.0   | 4        | 9.52%   |
| 5.19.0   | 2        | 4.76%   |
| 5.15.0   | 2        | 4.76%   |
| 6.0.5    | 1        | 2.38%   |
| 5.10.52  | 1        | 2.38%   |
| 5.10.111 | 1        | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 26       | 61.9%   |
| 5.14    | 7        | 16.67%  |
| 5.16    | 4        | 9.52%   |
| 5.19    | 2        | 4.76%   |
| 5.15    | 2        | 4.76%   |
| 6.0     | 1        | 2.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 41       | 97.62%  |
| i686   | 1        | 2.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 32       | 76.19%  |
| KDE5             | 7        | 16.67%  |
| lightdm-xsession | 2        | 4.76%   |
| Unknown          | 1        | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 42       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 33       | 78.57%  |
| SDDM    | 7        | 16.67%  |
| SLiM    | 1        | 2.38%   |
| GDM     | 1        | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 16       | 38.1%   |
| de_DE | 9        | 21.43%  |
| pl_PL | 2        | 4.76%   |
| it_IT | 2        | 4.76%   |
| en_GB | 2        | 4.76%   |
| de_CH | 2        | 4.76%   |
| sv_SE | 1        | 2.38%   |
| pt_BR | 1        | 2.38%   |
| hu_HU | 1        | 2.38%   |
| fr_FR | 1        | 2.38%   |
| fi_FI | 1        | 2.38%   |
| es_MX | 1        | 2.38%   |
| es_ES | 1        | 2.38%   |
| es_CO | 1        | 2.38%   |
| en_NZ | 1        | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 25       | 59.52%  |
| EFI  | 17       | 40.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 35       | 83.33%  |
| Overlay  | 3        | 7.14%   |
| Xfs      | 1        | 2.38%   |
| Reiserfs | 1        | 2.38%   |
| Ext3     | 1        | 2.38%   |
| Btrfs    | 1        | 2.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 26       | 61.9%   |
| MBR  | 16       | 38.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 54.76%  |
| Yes       | 19       | 45.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 57.14%  |
| No        | 18       | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 21.43%  |
| Gigabyte Technology | 6        | 14.29%  |
| MSI                 | 5        | 11.9%   |
| Dell                | 4        | 9.52%   |
| Lenovo              | 3        | 7.14%   |
| Intel               | 2        | 4.76%   |
| Hewlett-Packard     | 2        | 4.76%   |
| Biostar             | 2        | 4.76%   |
| ASRock              | 2        | 4.76%   |
| Pegatron            | 1        | 2.38%   |
| MP                  | 1        | 2.38%   |
| Medion              | 1        | 2.38%   |
| Huanan              | 1        | 2.38%   |
| GALAX               | 1        | 2.38%   |
| Fujitsu             | 1        | 2.38%   |
| AOpen               | 1        | 2.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| Dell OptiPlex 755                        | 2        | 4.76%   |
| ASUS All Series                          | 2        | 4.76%   |
| Pegatron FQ425AA-ABA a6655f              | 1        | 2.38%   |
| MSI MS-7C91                              | 1        | 2.38%   |
| MSI MS-7C37                              | 1        | 2.38%   |
| MSI MS-7A34                              | 1        | 2.38%   |
| MSI MS-7917                              | 1        | 2.38%   |
| MSI MS-7758                              | 1        | 2.38%   |
| MP MS-7848                               | 1        | 2.38%   |
| Medion Akoya P5330 E MD8876/2458         | 1        | 2.38%   |
| Lenovo ThinkStation P620 30E0CTO1WW      | 1        | 2.38%   |
| Lenovo ThinkCentre M75s Gen 2 11JAS0CJ00 | 1        | 2.38%   |
| Lenovo 10AAS1QB0B                        | 1        | 2.38%   |
| Intel V1.3                               | 1        | 2.38%   |
| Intel DH55TC AAE70932-303                | 1        | 2.38%   |
| Huanan X99-F8                            | 1        | 2.38%   |
| HP Z400 Workstation                      | 1        | 2.38%   |
| HP Compaq 8000 Elite CMT PC              | 1        | 2.38%   |
| Gigabyte Z390 UD                         | 1        | 2.38%   |
| Gigabyte X570 AORUS PRO                  | 1        | 2.38%   |
| Gigabyte H410M S2H V3                    | 1        | 2.38%   |
| Gigabyte B560M DS3H V2                   | 1        | 2.38%   |
| Gigabyte B550M S2H                       | 1        | 2.38%   |
| Gigabyte B550M DS3H                      | 1        | 2.38%   |
| GALAX B550M                              | 1        | 2.38%   |
| Fujitsu ESPRIMO P720                     | 1        | 2.38%   |
| Dell OptiPlex 780                        | 1        | 2.38%   |
| Dell OptiPlex 7010                       | 1        | 2.38%   |
| Biostar H61MH                            | 1        | 2.38%   |
| Biostar A780L3B                          | 1        | 2.38%   |
| ASUS Z170-P                              | 1        | 2.38%   |
| ASUS ROG Maximus XIII HERO               | 1        | 2.38%   |
| ASUS PRIME B450M-A                       | 1        | 2.38%   |
| ASUS P8H61/USB3 R2.0                     | 1        | 2.38%   |
| ASUS P5GC-MX/MEDION/SI                   | 1        | 2.38%   |
| ASUS P5GC-MX/CKD/SI                      | 1        | 2.38%   |
| ASUS P5G41T-M LX                         | 1        | 2.38%   |
| ASRock X570 Steel Legend                 | 1        | 2.38%   |
| ASRock N3150M                            | 1        | 2.38%   |
| AOpen ESPRIMO Q900                       | 1        | 2.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 4        | 9.52%   |
| Gigabyte B550M       | 2        | 4.76%   |
| ASUS P5GC-MX         | 2        | 4.76%   |
| ASUS All             | 2        | 4.76%   |
| Pegatron FQ425AA-ABA | 1        | 2.38%   |
| MSI MS-7C91          | 1        | 2.38%   |
| MSI MS-7C37          | 1        | 2.38%   |
| MSI MS-7A34          | 1        | 2.38%   |
| MSI MS-7917          | 1        | 2.38%   |
| MSI MS-7758          | 1        | 2.38%   |
| MP MS-7848           | 1        | 2.38%   |
| Medion Akoya         | 1        | 2.38%   |
| Lenovo ThinkStation  | 1        | 2.38%   |
| Lenovo ThinkCentre   | 1        | 2.38%   |
| Lenovo 10AAS1QB0B    | 1        | 2.38%   |
| Intel V1.3           | 1        | 2.38%   |
| Intel DH55TC         | 1        | 2.38%   |
| Huanan X99-F8        | 1        | 2.38%   |
| HP Z400              | 1        | 2.38%   |
| HP Compaq            | 1        | 2.38%   |
| Gigabyte Z390        | 1        | 2.38%   |
| Gigabyte X570        | 1        | 2.38%   |
| Gigabyte H410M       | 1        | 2.38%   |
| Gigabyte B560M       | 1        | 2.38%   |
| GALAX B550M          | 1        | 2.38%   |
| Fujitsu ESPRIMO      | 1        | 2.38%   |
| Biostar H61MH        | 1        | 2.38%   |
| Biostar A780L3B      | 1        | 2.38%   |
| ASUS Z170-P          | 1        | 2.38%   |
| ASUS ROG             | 1        | 2.38%   |
| ASUS PRIME           | 1        | 2.38%   |
| ASUS P8H61           | 1        | 2.38%   |
| ASUS P5G41T-M        | 1        | 2.38%   |
| ASRock X570          | 1        | 2.38%   |
| ASRock N3150M        | 1        | 2.38%   |
| AOpen ESPRIMO        | 1        | 2.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 6        | 14.29%  |
| 2021 | 4        | 9.52%   |
| 2018 | 4        | 9.52%   |
| 2007 | 4        | 9.52%   |
| 2019 | 3        | 7.14%   |
| 2014 | 3        | 7.14%   |
| 2012 | 3        | 7.14%   |
| 2010 | 3        | 7.14%   |
| 2016 | 2        | 4.76%   |
| 2015 | 2        | 4.76%   |
| 2013 | 2        | 4.76%   |
| 2011 | 2        | 4.76%   |
| 2009 | 2        | 4.76%   |
| 2017 | 1        | 2.38%   |
| 2008 | 1        | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 42       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 42       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 42       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 12       | 28.57%  |
| 8.01-16.0   | 11       | 26.19%  |
| 4.01-8.0    | 8        | 19.05%  |
| 3.01-4.0    | 6        | 14.29%  |
| 16.01-24.0  | 2        | 4.76%   |
| 24.01-32.0  | 1        | 2.38%   |
| 2.01-3.0    | 1        | 2.38%   |
| 64.01-256.0 | 1        | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 18       | 42.86%  |
| 2.01-3.0   | 10       | 23.81%  |
| 3.01-4.0   | 6        | 14.29%  |
| 4.01-8.0   | 3        | 7.14%   |
| 8.01-16.0  | 3        | 7.14%   |
| 16.01-24.0 | 1        | 2.38%   |
| 0.51-1.0   | 1        | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 12       | 28.57%  |
| 1      | 12       | 28.57%  |
| 3      | 11       | 26.19%  |
| 4      | 4        | 9.52%   |
| 5      | 2        | 4.76%   |
| 8      | 1        | 2.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 21       | 50%     |
| No        | 21       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 42       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 59.52%  |
| Yes       | 17       | 40.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 85.71%  |
| Yes       | 6        | 14.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 11       | 26.19%  |
| Germany     | 7        | 16.67%  |
| Switzerland | 2        | 4.76%   |
| Poland      | 2        | 4.76%   |
| Italy       | 2        | 4.76%   |
| India       | 2        | 4.76%   |
| Venezuela   | 1        | 2.38%   |
| UK          | 1        | 2.38%   |
| Sweden      | 1        | 2.38%   |
| Spain       | 1        | 2.38%   |
| New Zealand | 1        | 2.38%   |
| Netherlands | 1        | 2.38%   |
| Mexico      | 1        | 2.38%   |
| Indonesia   | 1        | 2.38%   |
| Hungary     | 1        | 2.38%   |
| Greece      | 1        | 2.38%   |
| France      | 1        | 2.38%   |
| Finland     | 1        | 2.38%   |
| Estonia     | 1        | 2.38%   |
| Colombia    | 1        | 2.38%   |
| Brazil      | 1        | 2.38%   |
| Australia   | 1        | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Ettingen            | 2        | 4.76%   |
| Volos               | 1        | 2.38%   |
| Voghera             | 1        | 2.38%   |
| Vilhelmina          | 1        | 2.38%   |
| Vasco da Gama       | 1        | 2.38%   |
| Vaidasoo            | 1        | 2.38%   |
| Stevens Point       | 1        | 2.38%   |
| Seelbach            | 1        | 2.38%   |
| San Diego           | 1        | 2.38%   |
| Rzeszów            | 1        | 2.38%   |
| Rosporden           | 1        | 2.38%   |
| Rathenow            | 1        | 2.38%   |
| Puebla City         | 1        | 2.38%   |
| Portland            | 1        | 2.38%   |
| Pompano Beach       | 1        | 2.38%   |
| Pila                | 1        | 2.38%   |
| Piedmont            | 1        | 2.38%   |
| Normal              | 1        | 2.38%   |
| Milwaukee           | 1        | 2.38%   |
| Maringá            | 1        | 2.38%   |
| Katonah             | 1        | 2.38%   |
| Kamiah              | 1        | 2.38%   |
| Houston             | 1        | 2.38%   |
| Herzogenrath        | 1        | 2.38%   |
| Helsinki            | 1        | 2.38%   |
| Granadilla de Abona | 1        | 2.38%   |
| Gouda               | 1        | 2.38%   |
| Göttingen          | 1        | 2.38%   |
| Freital             | 1        | 2.38%   |
| Dieburg             | 1        | 2.38%   |
| Denpasar            | 1        | 2.38%   |
| Chingford           | 1        | 2.38%   |
| Cambridge           | 1        | 2.38%   |
| Budapest            | 1        | 2.38%   |
| Brisbane            | 1        | 2.38%   |
| Bozzolo             | 1        | 2.38%   |
| Bogotá             | 1        | 2.38%   |
| Berlin              | 1        | 2.38%   |
| Bengaluru           | 1        | 2.38%   |
| Belmont             | 1        | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 18       | 31     | 22.78%  |
| Seagate             | 16       | 23     | 20.25%  |
| WDC                 | 11       | 15     | 13.92%  |
| Kingston            | 7        | 7      | 8.86%   |
| Toshiba             | 4        | 4      | 5.06%   |
| Hitachi             | 3        | 4      | 3.8%    |
| Crucial             | 3        | 3      | 3.8%    |
| Corsair             | 3        | 3      | 3.8%    |
| PNY                 | 2        | 3      | 2.53%   |
| GOODRAM             | 2        | 2      | 2.53%   |
| Transcend           | 1        | 1      | 1.27%   |
| SPCC                | 1        | 1      | 1.27%   |
| SanDisk             | 1        | 1      | 1.27%   |
| OCZ                 | 1        | 1      | 1.27%   |
| Micron Technology   | 1        | 1      | 1.27%   |
| Maxtor              | 1        | 1      | 1.27%   |
| Avant               | 1        | 1      | 1.27%   |
| Apacer              | 1        | 1      | 1.27%   |
| Acer                | 1        | 1      | 1.27%   |
| A-DATA Technology   | 1        | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD     | 4        | 4.04%   |
| Seagate ST2000DM008-2FR102 2TB      | 3        | 3.03%   |
| Samsung SSD 850 EVO 250GB           | 3        | 3.03%   |
| Toshiba DT01ACA100 1TB              | 2        | 2.02%   |
| Seagate ST3500413AS 500GB           | 2        | 2.02%   |
| Samsung SSD 970 EVO Plus 1TB        | 2        | 2.02%   |
| Samsung SSD 850 EVO 1TB             | 2        | 2.02%   |
| Corsair MP400 2TB                   | 2        | 2.02%   |
| WDC WDS500G2B0C-00PXH0 500GB        | 1        | 1.01%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 1.01%   |
| WDC WD800AAJS-60M0A0 80GB           | 1        | 1.01%   |
| WDC WD60EZRZ-00RWYB1 6TB            | 1        | 1.01%   |
| WDC WD60EFRX-68L0BN1 6TB            | 1        | 1.01%   |
| WDC WD5002AALX-00J37A0 500GB        | 1        | 1.01%   |
| WDC WD5000AVCS-632DY1 500GB         | 1        | 1.01%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 1.01%   |
| WDC WD30EFRX-68AX9N0 3TB            | 1        | 1.01%   |
| WDC WD20EZRX-22D8PB0 2TB            | 1        | 1.01%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 1.01%   |
| WDC WD10EVDS-63U8B1 1TB             | 1        | 1.01%   |
| WDC WD10EADS-98M2B0 1TB             | 1        | 1.01%   |
| WDC WD10EADS-00M2B0 1TB             | 1        | 1.01%   |
| Transcend TS128GSSD370S 128GB       | 1        | 1.01%   |
| Toshiba MQ01ABF050 500GB            | 1        | 1.01%   |
| Toshiba DT01ACA100 LENOVO 1TB       | 1        | 1.01%   |
| SPCC Solid State Disk 256GB         | 1        | 1.01%   |
| Seagate ST500LT012-9WS142 500GB     | 1        | 1.01%   |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 1.01%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 1.01%   |
| Seagate ST380815AS 80GB             | 1        | 1.01%   |
| Seagate ST3360320AS 360GB           | 1        | 1.01%   |
| Seagate ST320LT020-9YG142 320GB     | 1        | 1.01%   |
| Seagate ST320LT012-1DG14C 320GB     | 1        | 1.01%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1        | 1.01%   |
| Seagate ST3160815AS 160GB           | 1        | 1.01%   |
| Seagate ST31000524NS 1TB            | 1        | 1.01%   |
| Seagate ST250DM000-1BD141 250GB     | 1        | 1.01%   |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 1.01%   |
| Seagate ST2000DL004 HD204UI 2TB     | 1        | 1.01%   |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 1.01%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 23     | 44.44%  |
| WDC                 | 9        | 13     | 25%     |
| Toshiba             | 4        | 4      | 11.11%  |
| Samsung Electronics | 3        | 3      | 8.33%   |
| Hitachi             | 3        | 4      | 8.33%   |
| Maxtor              | 1        | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 14       | 18     | 38.89%  |
| Kingston            | 7        | 7      | 19.44%  |
| GOODRAM             | 2        | 2      | 5.56%   |
| Crucial             | 2        | 2      | 5.56%   |
| WDC                 | 1        | 1      | 2.78%   |
| Transcend           | 1        | 1      | 2.78%   |
| SPCC                | 1        | 1      | 2.78%   |
| SanDisk             | 1        | 1      | 2.78%   |
| PNY                 | 1        | 1      | 2.78%   |
| OCZ                 | 1        | 1      | 2.78%   |
| Micron Technology   | 1        | 1      | 2.78%   |
| Avant               | 1        | 1      | 2.78%   |
| Apacer              | 1        | 1      | 2.78%   |
| Acer                | 1        | 1      | 2.78%   |
| A-DATA Technology   | 1        | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 31       | 48     | 41.89%  |
| SSD  | 29       | 40     | 39.19%  |
| NVMe | 14       | 17     | 18.92%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 41       | 86     | 73.21%  |
| NVMe | 14       | 17     | 25%     |
| SAS  | 1        | 2      | 1.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 33       | 54     | 55%     |
| 0.51-1.0   | 16       | 18     | 26.67%  |
| 1.01-2.0   | 7        | 10     | 11.67%  |
| 3.01-4.0   | 2        | 2      | 3.33%   |
| 2.01-3.0   | 1        | 1      | 1.67%   |
| 4.01-10.0  | 1        | 3      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 10       | 23.81%  |
| 101-250        | 9        | 21.43%  |
| 1001-2000      | 7        | 16.67%  |
| More than 3000 | 5        | 11.9%   |
| 501-1000       | 5        | 11.9%   |
| 51-100         | 3        | 7.14%   |
| 2001-3000      | 2        | 4.76%   |
| 1-20           | 1        | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 10       | 23.26%  |
| 21-50          | 8        | 18.6%   |
| 1-20           | 7        | 16.28%  |
| 51-100         | 6        | 13.95%  |
| 251-500        | 4        | 9.3%    |
| 1001-2000      | 4        | 9.3%    |
| More than 3000 | 2        | 4.65%   |
| 2001-3000      | 1        | 2.33%   |
| 501-1000       | 1        | 2.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 5%      |
| WDC WD10EADS-98M2B0 1TB                  | 1        | 1      | 5%      |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 5%      |
| Toshiba MQ01ABF050 500GB                 | 1        | 1      | 5%      |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 5%      |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 5%      |
| Seagate ST380815AS 80GB                  | 1        | 1      | 5%      |
| Seagate ST3500413AS 500GB                | 1        | 1      | 5%      |
| Seagate ST3360320AS 360GB                | 1        | 1      | 5%      |
| Seagate ST320LT020-9YG142 320GB          | 1        | 1      | 5%      |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 2      | 5%      |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 5%      |
| Seagate ST2000DM001-1ER164 2TB           | 1        | 1      | 5%      |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 5%      |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 5%      |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 5%      |
| Maxtor 4K040H2 40GB                      | 1        | 1      | 5%      |
| Hitachi HTS545050A7E380 500GB            | 1        | 1      | 5%      |
| Hitachi HDS721050CLA362 500GB            | 1        | 1      | 5%      |
| GOODRAM SSDPR-CL100-480-G3 480GB         | 1        | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 10     | 47.37%  |
| WDC                 | 3        | 3      | 15.79%  |
| Samsung Electronics | 3        | 4      | 15.79%  |
| Toshiba             | 1        | 1      | 5.26%   |
| Maxtor              | 1        | 1      | 5.26%   |
| Hitachi             | 1        | 2      | 5.26%   |
| GOODRAM             | 1        | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 9        | 10     | 64.29%  |
| WDC     | 2        | 2      | 14.29%  |
| Toshiba | 1        | 1      | 7.14%   |
| Maxtor  | 1        | 1      | 7.14%   |
| Hitachi | 1        | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 16     | 72.22%  |
| SSD  | 5        | 6      | 27.78%  |

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
| Works    | 37       | 81     | 66.07%  |
| Malfunc  | 18       | 22     | 32.14%  |
| Detected | 1        | 2      | 1.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 29       | 47.54%  |
| AMD                       | 12       | 19.67%  |
| Samsung Electronics       | 8        | 13.11%  |
| Phison Electronics        | 4        | 6.56%   |
| ASMedia Technology        | 4        | 6.56%   |
| ULi Electronics           | 1        | 1.64%   |
| SanDisk                   | 1        | 1.64%   |
| Nvidia                    | 1        | 1.64%   |
| Micron/Crucial Technology | 1        | 1.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 6.33%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 6.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 5.06%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 5.06%   |
| Phison E12 NVMe Controller                                                              | 3        | 3.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 3.8%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 3.8%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 3.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 3.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 3.8%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 3.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 2.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 2.53%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 2.53%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 2.53%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 2.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 2.53%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 2.53%   |
| ULi M5229 IDE                                                                           | 1        | 1.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.27%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 1.27%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.27%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.27%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.27%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 1.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.27%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 1.27%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 1.27%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.27%   |
| AMD RS690 PCI to PCI Bridge (PCI Express Port 2)                                        | 1        | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 33       | 54.1%   |
| NVMe | 14       | 22.95%  |
| IDE  | 11       | 18.03%  |
| RAID | 3        | 4.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 29       | 69.05%  |
| AMD    | 13       | 30.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 3        | 7.14%   |
| Intel Core i7-5820K CPU @ 3.30GHz               | 2        | 4.76%   |
| Intel Core i5-3350P CPU @ 3.10GHz               | 2        | 4.76%   |
| Intel Xeon CPU W3565 @ 3.20GHz                  | 1        | 2.38%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz             | 1        | 2.38%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz     | 1        | 2.38%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz          | 1        | 2.38%   |
| Intel Core i9-10850K CPU @ 3.60GHz              | 1        | 2.38%   |
| Intel Core i5-9600K CPU @ 3.70GHz               | 1        | 2.38%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1        | 2.38%   |
| Intel Core i5-6402P CPU @ 2.80GHz               | 1        | 2.38%   |
| Intel Core i5-4690K CPU @ 3.50GHz               | 1        | 2.38%   |
| Intel Core i5-4570T CPU @ 2.90GHz               | 1        | 2.38%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 2.38%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 1        | 2.38%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1        | 2.38%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 1        | 2.38%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 1        | 2.38%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 1        | 2.38%   |
| Intel Core i3-10100 CPU @ 3.60GHz               | 1        | 2.38%   |
| Intel Core i3 CPU 550 @ 3.20GHz                 | 1        | 2.38%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz            | 1        | 2.38%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz            | 1        | 2.38%   |
| Intel Celeron CPU N3150 @ 1.60GHz               | 1        | 2.38%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz          | 1        | 2.38%   |
| AMD Ryzen Threadripper PRO 3945WX 12-Cores      | 1        | 2.38%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 2.38%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 2.38%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 2.38%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1        | 2.38%   |
| AMD Ryzen 7 1800X Eight-Core Processor          | 1        | 2.38%   |
| AMD Ryzen 5 PRO 3400G with Radeon Vega Graphics | 1        | 2.38%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 1        | 2.38%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 2.38%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 1        | 2.38%   |
| AMD Ryzen 3 3100 4-Core Processor               | 1        | 2.38%   |
| AMD Phenom II X4 925 Processor                  | 1        | 2.38%   |
| AMD Phenom 9150e Quad-Core Processor            | 1        | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 9        | 21.43%  |
| Intel Core i3           | 6        | 14.29%  |
| Intel Core 2 Duo        | 5        | 11.9%   |
| AMD Ryzen 7             | 4        | 9.52%   |
| AMD Ryzen 5             | 3        | 7.14%   |
| Intel Xeon              | 2        | 4.76%   |
| Intel Core i7           | 2        | 4.76%   |
| Other                   | 1        | 2.38%   |
| Intel Pentium Dual-Core | 1        | 2.38%   |
| Intel Pentium Dual      | 1        | 2.38%   |
| Intel Core i9           | 1        | 2.38%   |
| Intel Celeron           | 1        | 2.38%   |
| AMD Ryzen Threadripper  | 1        | 2.38%   |
| AMD Ryzen 9             | 1        | 2.38%   |
| AMD Ryzen 5 PRO         | 1        | 2.38%   |
| AMD Ryzen 3             | 1        | 2.38%   |
| AMD Phenom II X4        | 1        | 2.38%   |
| AMD Phenom              | 1        | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 14       | 33.33%  |
| 4      | 13       | 30.95%  |
| 6      | 6        | 14.29%  |
| 8      | 5        | 11.9%   |
| 12     | 3        | 7.14%   |
| 10     | 1        | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 42       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 24       | 57.14%  |
| 1      | 18       | 42.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 42       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 5        | 11.9%   |
| 0x1067a    | 4        | 9.52%   |
| 0x306a9    | 3        | 7.14%   |
| 0x08701021 | 3        | 7.14%   |
| 0x6fd      | 2        | 4.76%   |
| 0x506e3    | 2        | 4.76%   |
| 0x306f2    | 2        | 4.76%   |
| 0x306c3    | 2        | 4.76%   |
| 0x206a7    | 2        | 4.76%   |
| 0x20655    | 2        | 4.76%   |
| 0x0800820d | 2        | 4.76%   |
| 0xa0671    | 1        | 2.38%   |
| 0xa0655    | 1        | 2.38%   |
| 0xa0653    | 1        | 2.38%   |
| 0x906ed    | 1        | 2.38%   |
| 0x406c3    | 1        | 2.38%   |
| 0x10676    | 1        | 2.38%   |
| 0x0a201016 | 1        | 2.38%   |
| 0x0a201009 | 1        | 2.38%   |
| 0x08301039 | 1        | 2.38%   |
| 0x08108109 | 1        | 2.38%   |
| 0x08001138 | 1        | 2.38%   |
| 0x010000db | 1        | 2.38%   |
| 0x01000083 | 1        | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 7        | 16.67%  |
| Penryn      | 5        | 11.9%   |
| Zen 2       | 4        | 9.52%   |
| Zen+        | 3        | 7.14%   |
| Zen 3       | 3        | 7.14%   |
| IvyBridge   | 3        | 7.14%   |
| Westmere    | 2        | 4.76%   |
| Skylake     | 2        | 4.76%   |
| SandyBridge | 2        | 4.76%   |
| K10         | 2        | 4.76%   |
| Core        | 2        | 4.76%   |
| CometLake   | 2        | 4.76%   |
| Zen         | 1        | 2.38%   |
| Silvermont  | 1        | 2.38%   |
| Nehalem     | 1        | 2.38%   |
| KabyLake    | 1        | 2.38%   |
| Icelake     | 1        | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 17       | 37.78%  |
| Intel  | 16       | 35.56%  |
| AMD    | 12       | 26.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3        | 6.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 4.44%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 4.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 4.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 4.44%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 4.44%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 4.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 4.44%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2        | 4.44%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 2.22%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 2.22%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 2.22%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 2.22%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 2.22%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 2.22%   |
| Nvidia GK208 [GeForce GT 635]                                                            | 1        | 2.22%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1        | 2.22%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1        | 2.22%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 2.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 2.22%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 2.22%   |
| Intel HD Graphics 530                                                                    | 1        | 2.22%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 2.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.22%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 2.22%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                                        | 1        | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 2.22%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1        | 2.22%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                                         | 1        | 2.22%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1        | 2.22%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 1        | 2.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 2.22%   |
| AMD Cezanne                                                                              | 1        | 2.22%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                                 | 1        | 2.22%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 2.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 17       | 40.48%  |
| 1 x Intel   | 13       | 30.95%  |
| 1 x AMD     | 11       | 26.19%  |
| Intel + AMD | 1        | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 26       | 61.9%   |
| Proprietary | 13       | 30.95%  |
| Unknown     | 3        | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 38.1%   |
| 7.01-8.0   | 7        | 16.67%  |
| 1.01-2.0   | 6        | 14.29%  |
| 3.01-4.0   | 5        | 11.9%   |
| 0.51-1.0   | 4        | 9.52%   |
| 8.01-16.0  | 2        | 4.76%   |
| 0.01-0.5   | 2        | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 7        | 15.22%  |
| Acer                 | 5        | 10.87%  |
| Hewlett-Packard      | 4        | 8.7%    |
| Fujitsu Siemens      | 4        | 8.7%    |
| Dell                 | 4        | 8.7%    |
| Goldstar             | 3        | 6.52%   |
| AOC                  | 3        | 6.52%   |
| Medion               | 2        | 4.35%   |
| Iiyama               | 2        | 4.35%   |
| Ancor Communications | 2        | 4.35%   |
| Vizio                | 1        | 2.17%   |
| Vestel Elektronik    | 1        | 2.17%   |
| SAC                  | 1        | 2.17%   |
| Philips              | 1        | 2.17%   |
| NEC Computers        | 1        | 2.17%   |
| MiTAC                | 1        | 2.17%   |
| Lenovo               | 1        | 2.17%   |
| Grundig              | 1        | 2.17%   |
| Gigabyte Technology  | 1        | 2.17%   |
| Eizo                 | 1        | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                   | 2        | 4.17%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch       | 2        | 4.17%   |
| Vizio M220MV VIZ0062 1920x1080 509x286mm 23.0-inch                     | 1        | 2.08%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch    | 1        | 2.08%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch       | 1        | 2.08%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1        | 2.08%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x290mm 23.1-inch      | 1        | 2.08%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch      | 1        | 2.08%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                  | 1        | 2.08%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch               | 1        | 2.08%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch            | 1        | 2.08%   |
| MiTAC KOGAN TV MTC6306 1366x768 700x400mm 31.7-inch                    | 1        | 2.08%   |
| Lenovo E24-20 LEN62A5 1920x1080 527x296mm 23.8-inch                    | 1        | 2.08%   |
| Iiyama PLE430 IVM46B4 1280x1024 340x270mm 17.1-inch                    | 1        | 2.08%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                  | 1        | 2.08%   |
| Hewlett-Packard X27q HPN3725 2560x1440 600x340mm 27.2-inch             | 1        | 2.08%   |
| Hewlett-Packard X27q HPN3724 2560x1440 600x340mm 27.2-inch             | 1        | 2.08%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch            | 1        | 2.08%   |
| Hewlett-Packard w17e HWP26E0 1440x900 408x255mm 18.9-inch              | 1        | 2.08%   |
| Hewlett-Packard 27es HWP3325 1920x1080 598x336mm 27.0-inch             | 1        | 2.08%   |
| Grundig WXGA GRU4448 1600x1200                                         | 1        | 2.08%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch               | 1        | 2.08%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 1        | 2.08%   |
| Goldstar E2350 GSM578F 1920x1080 510x290mm 23.1-inch                   | 1        | 2.08%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 800x330mm 34.1-inch       | 1        | 2.08%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch           | 1        | 2.08%   |
| Fujitsu Siemens B22W-5 ECO FUS07C3 1680x1050 474x296mm 22.0-inch       | 1        | 2.08%   |
| Eizo EV2333W ENC2069 1920x1080 510x287mm 23.0-inch                     | 1        | 2.08%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                      | 1        | 2.08%   |
| Dell SR2320L DELF03A 1920x1080 510x290mm 23.1-inch                     | 1        | 2.08%   |
| Dell S3422DW DELD103 3440x1440 800x330mm 34.1-inch                     | 1        | 2.08%   |
| Dell E190S DELA04B 1280x1024 380x300mm 19.1-inch                       | 1        | 2.08%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                      | 1        | 2.08%   |
| AOC L32W961 AOC3296 1360x768 700x390mm 31.5-inch                       | 1        | 2.08%   |
| AOC 2790 AOC2790 1920x1080 598x336mm 27.0-inch                         | 1        | 2.08%   |
| AOC 1621w AOC1621 1366x768 340x190mm 15.3-inch                         | 1        | 2.08%   |
| Ancor Communications BE24A ACI24AB 1920x1200 518x324mm 24.1-inch       | 1        | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 15       | 33.33%  |
| 2560x1440 (QHD)    | 6        | 13.33%  |
| 1680x1050 (WSXGA+) | 6        | 13.33%  |
| 3840x2160 (4K)     | 4        | 8.89%   |
| 1280x1024 (SXGA)   | 3        | 6.67%   |
| 3440x1440          | 2        | 4.44%   |
| 1920x1200 (WUXGA)  | 2        | 4.44%   |
| 1366x768 (WXGA)    | 2        | 4.44%   |
| 2560x1080          | 1        | 2.22%   |
| 1600x900 (HD+)     | 1        | 2.22%   |
| 1440x900 (WXGA+)   | 1        | 2.22%   |
| 1360x768           | 1        | 2.22%   |
| 1280x720 (HD)      | 1        | 2.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 8        | 18.18%  |
| 27      | 7        | 15.91%  |
| 22      | 6        | 13.64%  |
| 31      | 5        | 11.36%  |
| 34      | 3        | 6.82%   |
| 24      | 2        | 4.55%   |
| 21      | 2        | 4.55%   |
| 17      | 2        | 4.55%   |
| 84      | 1        | 2.27%   |
| 54      | 1        | 2.27%   |
| 26      | 1        | 2.27%   |
| 20      | 1        | 2.27%   |
| 19      | 1        | 2.27%   |
| 18      | 1        | 2.27%   |
| 16      | 1        | 2.27%   |
| 15      | 1        | 2.27%   |
| Unknown | 1        | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 39.53%  |
| 401-500     | 10       | 23.26%  |
| 601-700     | 5        | 11.63%  |
| 701-800     | 3        | 6.98%   |
| 301-350     | 3        | 6.98%   |
| 351-400     | 2        | 4.65%   |
| 1501-2000   | 1        | 2.33%   |
| 1001-1500   | 1        | 2.33%   |
| Unknown     | 1        | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 28       | 65.12%  |
| 16/10 | 9        | 20.93%  |
| 5/4   | 3        | 6.98%   |
| 21/9  | 3        | 6.98%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 34.09%  |
| 351-500        | 8        | 18.18%  |
| 301-350        | 7        | 15.91%  |
| 151-200        | 4        | 9.09%   |
| 251-300        | 3        | 6.82%   |
| More than 1000 | 2        | 4.55%   |
| 141-150        | 2        | 4.55%   |
| 121-130        | 1        | 2.27%   |
| 91-100         | 1        | 2.27%   |
| Unknown        | 1        | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 31       | 73.81%  |
| 101-120 | 8        | 19.05%  |
| 1-50    | 2        | 4.76%   |
| Unknown | 1        | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 31       | 73.81%  |
| 2     | 7        | 16.67%  |
| 3     | 2        | 4.76%   |
| 0     | 2        | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 25       | 42.37%  |
| Intel                 | 15       | 25.42%  |
| Qualcomm Atheros      | 4        | 6.78%   |
| TP-Link               | 3        | 5.08%   |
| Ralink Technology     | 3        | 5.08%   |
| Broadcom              | 2        | 3.39%   |
| Xiaomi                | 1        | 1.69%   |
| Nvidia                | 1        | 1.69%   |
| Mercucys              | 1        | 1.69%   |
| Edimax Technology     | 1        | 1.69%   |
| Broadcom Limited      | 1        | 1.69%   |
| AVM                   | 1        | 1.69%   |
| Aquantia              | 1        | 1.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 29.23%  |
| Intel I211 Gigabit Network Connection                             | 3        | 4.62%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 3.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 3.08%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 3.08%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 3.08%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 3.08%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 3.08%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 3.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.54%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 1.54%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 1.54%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 1.54%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 1.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.54%   |
| Realtek B1690189192                                               | 1        | 1.54%   |
| Realtek 802.11ac NIC                                              | 1        | 1.54%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 1.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.54%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.54%   |
| Mercucys MW300UM RTL8192EU wifi                                   | 1        | 1.54%   |
| Intel Wireless 8260                                               | 1        | 1.54%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.54%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.54%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.54%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.54%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.54%   |
| Edimax RTL8192S WLAN Adapter                                      | 1        | 1.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.54%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1        | 1.54%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 1.54%   |
| AVM FRITZ!WLAN AC 860                                             | 1        | 1.54%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 36.84%  |
| TP-Link               | 3        | 15.79%  |
| Ralink Technology     | 3        | 15.79%  |
| Mercucys              | 1        | 5.26%   |
| Intel                 | 1        | 5.26%   |
| Edimax Technology     | 1        | 5.26%   |
| Broadcom Limited      | 1        | 5.26%   |
| Broadcom              | 1        | 5.26%   |
| AVM                   | 1        | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 2        | 10.53%  |
| Ralink MT7601U Wireless Adapter                            | 2        | 10.53%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 5.26%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 1        | 5.26%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 1        | 5.26%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1        | 5.26%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 5.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1        | 5.26%   |
| Realtek B1690189192                                        | 1        | 5.26%   |
| Realtek 802.11ac NIC                                       | 1        | 5.26%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 5.26%   |
| Mercucys MW300UM RTL8192EU wifi                            | 1        | 5.26%   |
| Intel Wireless 8260                                        | 1        | 5.26%   |
| Edimax RTL8192S WLAN Adapter                               | 1        | 5.26%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1        | 5.26%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1        | 5.26%   |
| AVM FRITZ!WLAN AC 860                                      | 1        | 5.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 21       | 47.73%  |
| Intel                 | 15       | 34.09%  |
| Qualcomm Atheros      | 4        | 9.09%   |
| Xiaomi                | 1        | 2.27%   |
| Nvidia                | 1        | 2.27%   |
| Broadcom              | 1        | 2.27%   |
| Aquantia              | 1        | 2.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 41.3%   |
| Intel I211 Gigabit Network Connection                             | 3        | 6.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 4.35%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 4.35%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 4.35%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 4.35%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 4.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 2.17%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.17%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.17%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.17%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.17%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.17%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 2.17%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.17%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 42       | 71.19%  |
| WiFi     | 17       | 28.81%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 30       | 68.18%  |
| WiFi     | 14       | 31.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 35       | 83.33%  |
| 2     | 6        | 14.29%  |
| 3     | 1        | 2.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 30       | 71.43%  |
| Yes  | 12       | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 3        | 50%     |
| ASUSTek Computer        | 2        | 33.33%  |
| Apple                   | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 3        | 50%     |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 16.67%  |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 16.67%  |
| Apple Bluetooth USB Host Controller                   | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 28       | 38.36%  |
| AMD                     | 16       | 21.92%  |
| Nvidia                  | 15       | 20.55%  |
| C-Media Electronics     | 3        | 4.11%   |
| ROCCAT                  | 2        | 2.74%   |
| Creative Labs           | 2        | 2.74%   |
| Unknown                 | 1        | 1.37%   |
| TerraTec Electronic     | 1        | 1.37%   |
| Schiit Audio            | 1        | 1.37%   |
| Razer USA               | 1        | 1.37%   |
| JMTek                   | 1        | 1.37%   |
| GN Netcom               | 1        | 1.37%   |
| BEHRINGER International | 1        | 1.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                          | 5        | 5.95%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4        | 4.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4        | 4.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 3.57%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3        | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3        | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3        | 3.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3        | 3.57%   |
| ROCCAT Khan AIMO                                                                                  | 2        | 2.38%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 2.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 2.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2        | 2.38%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 2.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2        | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2        | 2.38%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 2        | 2.38%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 2.38%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2        | 2.38%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2        | 2.38%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 2.38%   |
| Unknown Realtek USB Audio Rear                                                                    | 1        | 1.19%   |
| Unknown Realtek USB Audio Front                                                                   | 1        | 1.19%   |
| TerraTec Electronic Aureon Dual USB                                                               | 1        | 1.19%   |
| Schiit Audio I'm Fulla Schiit                                                                     | 1        | 1.19%   |
| Razer USA Kraken Tournament Edition                                                               | 1        | 1.19%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 1.19%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 1.19%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 1.19%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 1.19%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 1.19%   |
| JMTek USB PnP Audio Device                                                                        | 1        | 1.19%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 1.19%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 1.19%   |
| Intel Audio device                                                                                | 1        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.19%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1        | 1.19%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 1.19%   |
| GN Netcom Jabra BIZ 2300                                                                          | 1        | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 9        | 20%     |
| Corsair             | 7        | 15.56%  |
| Unknown             | 6        | 13.33%  |
| G.Skill             | 5        | 11.11%  |
| Samsung Electronics | 4        | 8.89%   |
| SK hynix            | 3        | 6.67%   |
| Nanya Technology    | 2        | 4.44%   |
| Micron Technology   | 2        | 4.44%   |
| A-DATA Technology   | 2        | 4.44%   |
| Transcend           | 1        | 2.22%   |
| Ramaxel Technology  | 1        | 2.22%   |
| Elpida              | 1        | 2.22%   |
| Crucial             | 1        | 2.22%   |
| Unknown             | 1        | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                 | 2        | 4.26%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 2        | 4.26%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 2        | 4.26%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 2.13%   |
| Unknown RAM Module 4GB DIMM 667MT/s                      | 1        | 2.13%   |
| Unknown RAM Module 4GB DIMM                              | 1        | 2.13%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 2.13%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s         | 1        | 2.13%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 2.13%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 2.13%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s     | 1        | 2.13%   |
| SK hynix RAM HMT125U6DFR8C-H9 2048MB DIMM DDR3 1333MT/s  | 1        | 2.13%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s     | 1        | 2.13%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s     | 1        | 2.13%   |
| Samsung RAM M378A1G43DB0-CPB 8GB DIMM DDR4 2133MT/s      | 1        | 2.13%   |
| Samsung RAM DDR3 1600 8G 8GB DIMM DDR3 1333MT/s          | 1        | 2.13%   |
| Ramaxel RAM RMUA5200ME78HAF-3200 8GB DIMM DDR4 3200MT/s  | 1        | 2.13%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR 2048MT/s        | 1        | 2.13%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s       | 1        | 2.13%   |
| Micron RAM Module 8GB SODIMM DDR3 1333MT/s               | 1        | 2.13%   |
| Micron RAM Module 4GB SODIMM DDR3 1333MT/s               | 1        | 2.13%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 2.13%   |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s                | 1        | 2.13%   |
| Kingston RAM KHX3200C16D4/4GX 4GB DIMM DDR4 3600MT/s     | 1        | 2.13%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 1        | 2.13%   |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 3200MT/s      | 1        | 2.13%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s      | 1        | 2.13%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s    | 1        | 2.13%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 2.13%   |
| Kingston RAM 99U5471-033.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 2.13%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 2.13%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s    | 1        | 2.13%   |
| G.Skill RAM F4-3600C19-16GSXWB 16GB DIMM DDR4 3600MT/s   | 1        | 2.13%   |
| G.Skill RAM F3-2133C11-8GAR 8GB DIMM DDR3 2133MT/s       | 1        | 2.13%   |
| G.Skill RAM F3-12800CL9-4GBRL 4GB DIMM DDR3 1866MT/s     | 1        | 2.13%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s     | 1        | 2.13%   |
| Elpida RAM EBE10UE8ACWA-8G-E 1GB DIMM DDR 800MT/s        | 1        | 2.13%   |
| Crucial RAM BLS4G4D26BFSB.8FE 4GB DIMM DDR4 2667MT/s     | 1        | 2.13%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s    | 1        | 2.13%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 1        | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 20       | 48.78%  |
| DDR3    | 13       | 31.71%  |
| DDR2    | 5        | 12.2%   |
| Unknown | 2        | 4.88%   |
| SDRAM   | 1        | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 39       | 95.12%  |
| SODIMM | 2        | 4.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 15       | 34.09%  |
| 8192  | 10       | 22.73%  |
| 16384 | 8        | 18.18%  |
| 2048  | 7        | 15.91%  |
| 32768 | 2        | 4.55%   |
| 1024  | 2        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 6        | 13.64%  |
| 3600    | 5        | 11.36%  |
| 3200    | 4        | 9.09%   |
| 2133    | 4        | 9.09%   |
| 1600    | 4        | 9.09%   |
| 2667    | 3        | 6.82%   |
| 3400    | 2        | 4.55%   |
| 2666    | 2        | 4.55%   |
| 2048    | 2        | 4.55%   |
| 800     | 2        | 4.55%   |
| 667     | 2        | 4.55%   |
| 333     | 2        | 4.55%   |
| Unknown | 2        | 4.55%   |
| 3466    | 1        | 2.27%   |
| 2933    | 1        | 2.27%   |
| 1866    | 1        | 2.27%   |
| 1800    | 1        | 2.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Canon MF641C     | 1        | 50%     |
| Brother MFC-7340 | 1        | 50%     |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 5        | 50%     |
| Microsoft                     | 2        | 20%     |
| Sunplus Innovation Technology | 1        | 10%     |
| Generalplus Technology        | 1        | 10%     |
| Arkmicro Technologies         | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Microsoft LifeCam HD-3000  | 2        | 20%     |
| Logitech Webcam C930e      | 2        | 20%     |
| Logitech Webcam C270       | 2        | 20%     |
| Sunplus HD 720P webcam     | 1        | 10%     |
| Logitech HD Webcam C615    | 1        | 10%     |
| Generalplus GENERAL WEBCAM | 1        | 10%     |
| Arkmicro USB2.0 PC CAMERA  | 1        | 10%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Microsoft Fingerprint Reader | 1        | 100%    |

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
| 0     | 34       | 80.95%  |
| 1     | 7        | 16.67%  |
| 2     | 1        | 2.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Desktops | Percent |
|--------------------|----------|---------|
| Unassigned class   | 3        | 33.33%  |
| Graphics card      | 3        | 33.33%  |
| Net/wireless       | 1        | 11.11%  |
| Fingerprint reader | 1        | 11.11%  |
| Dvb card           | 1        | 11.11%  |

