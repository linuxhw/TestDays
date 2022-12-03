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

Total: 55

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| HP       | 304Ah                    | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| ASRock   | B365M Pro4               | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| Foxconn  | 2ABF                     | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| ASUSTek  | TUF Gaming B450-PLUS II  | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| ASRock   | B365M Pro4               | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
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
| 5.10.0-13-amd64            | 5        | 10.87%  |
| 5.14.0-4mx-amd64           | 4        | 8.7%    |
| 5.10.0-19-amd64            | 4        | 8.7%    |
| 5.10.0-16-amd64            | 4        | 8.7%    |
| 5.10.0-15-amd64            | 4        | 8.7%    |
| 5.10.0-18-amd64            | 3        | 6.52%   |
| 5.16.0-5mx-amd64           | 2        | 4.35%   |
| 5.14.0-3mx-amd64           | 2        | 4.35%   |
| 5.10.0-9-amd64             | 2        | 4.35%   |
| 5.10.0-11-amd64            | 2        | 4.35%   |
| 6.0.5-x64v1-xanmod1        | 1        | 2.17%   |
| 6.0.0-4mx-rt-amd64         | 1        | 2.17%   |
| 5.19.0-4.2-liquorix-amd64  | 1        | 2.17%   |
| 5.19.0-17.2-liquorix-amd64 | 1        | 2.17%   |
| 5.16.0-rc5-hwmon-next+     | 1        | 2.17%   |
| 5.16.0-6mx-amd64           | 1        | 2.17%   |
| 5.15.0-2-amd64             | 1        | 2.17%   |
| 5.15.0-0.bpo.2-amd64       | 1        | 2.17%   |
| 5.14.0-2mx-amd64           | 1        | 2.17%   |
| 5.10.52-antix.1-amd64-smp  | 1        | 2.17%   |
| 5.10.111-tkg-cfs           | 1        | 2.17%   |
| 5.10.0-18-686-pae          | 1        | 2.17%   |
| 5.10.0-17-amd64            | 1        | 2.17%   |
| 5.10.0-10-amd64            | 1        | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 27       | 58.7%   |
| 5.14.0   | 7        | 15.22%  |
| 5.16.0   | 4        | 8.7%    |
| 5.19.0   | 2        | 4.35%   |
| 5.15.0   | 2        | 4.35%   |
| 6.0.5    | 1        | 2.17%   |
| 6.0.0    | 1        | 2.17%   |
| 5.10.52  | 1        | 2.17%   |
| 5.10.111 | 1        | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 29       | 63.04%  |
| 5.14    | 7        | 15.22%  |
| 5.16    | 4        | 8.7%    |
| 6.0     | 2        | 4.35%   |
| 5.19    | 2        | 4.35%   |
| 5.15    | 2        | 4.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 45       | 97.83%  |
| i686   | 1        | 2.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 35       | 76.09%  |
| KDE5             | 8        | 17.39%  |
| lightdm-xsession | 2        | 4.35%   |
| Unknown          | 1        | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 46       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 36       | 78.26%  |
| SDDM    | 8        | 17.39%  |
| SLiM    | 1        | 2.17%   |
| GDM     | 1        | 2.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 17       | 36.96%  |
| de_DE | 9        | 19.57%  |
| pl_PL | 3        | 6.52%   |
| it_IT | 3        | 6.52%   |
| en_GB | 2        | 4.35%   |
| de_CH | 2        | 4.35%   |
| sv_SE | 1        | 2.17%   |
| ru_RU | 1        | 2.17%   |
| pt_BR | 1        | 2.17%   |
| hu_HU | 1        | 2.17%   |
| fr_FR | 1        | 2.17%   |
| fi_FI | 1        | 2.17%   |
| es_MX | 1        | 2.17%   |
| es_ES | 1        | 2.17%   |
| es_CO | 1        | 2.17%   |
| en_NZ | 1        | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 29       | 63.04%  |
| EFI  | 17       | 36.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 39       | 84.78%  |
| Overlay  | 3        | 6.52%   |
| Xfs      | 1        | 2.17%   |
| Reiserfs | 1        | 2.17%   |
| Ext3     | 1        | 2.17%   |
| Btrfs    | 1        | 2.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 26       | 56.52%  |
| MBR  | 20       | 43.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 56.52%  |
| Yes       | 20       | 43.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 27       | 58.7%   |
| No        | 19       | 41.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 10       | 21.74%  |
| Gigabyte Technology | 6        | 13.04%  |
| MSI                 | 5        | 10.87%  |
| Dell                | 4        | 8.7%    |
| Lenovo              | 3        | 6.52%   |
| Hewlett-Packard     | 3        | 6.52%   |
| ASRock              | 3        | 6.52%   |
| Intel               | 2        | 4.35%   |
| Biostar             | 2        | 4.35%   |
| Pegatron            | 1        | 2.17%   |
| MP                  | 1        | 2.17%   |
| Medion              | 1        | 2.17%   |
| Huanan              | 1        | 2.17%   |
| GALAX               | 1        | 2.17%   |
| Fujitsu             | 1        | 2.17%   |
| Foxconn             | 1        | 2.17%   |
| AOpen               | 1        | 2.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| Dell OptiPlex 755                        | 2        | 4.35%   |
| ASUS All Series                          | 2        | 4.35%   |
| Pegatron FQ425AA-ABA a6655f              | 1        | 2.17%   |
| MSI MS-7C91                              | 1        | 2.17%   |
| MSI MS-7C37                              | 1        | 2.17%   |
| MSI MS-7A34                              | 1        | 2.17%   |
| MSI MS-7917                              | 1        | 2.17%   |
| MSI MS-7758                              | 1        | 2.17%   |
| MP MS-7848                               | 1        | 2.17%   |
| Medion Akoya P5330 E MD8876/2458         | 1        | 2.17%   |
| Lenovo ThinkStation P620 30E0CTO1WW      | 1        | 2.17%   |
| Lenovo ThinkCentre M75s Gen 2 11JAS0CJ00 | 1        | 2.17%   |
| Lenovo 10AAS1QB0B                        | 1        | 2.17%   |
| Intel V1.3                               | 1        | 2.17%   |
| Intel DH55TC AAE70932-303                | 1        | 2.17%   |
| Huanan X99-F8                            | 1        | 2.17%   |
| HP Z400 Workstation                      | 1        | 2.17%   |
| HP Compaq 8100 Elite SFF PC              | 1        | 2.17%   |
| HP Compaq 8000 Elite CMT PC              | 1        | 2.17%   |
| Gigabyte Z390 UD                         | 1        | 2.17%   |
| Gigabyte X570 AORUS PRO                  | 1        | 2.17%   |
| Gigabyte H410M S2H V3                    | 1        | 2.17%   |
| Gigabyte B560M DS3H V2                   | 1        | 2.17%   |
| Gigabyte B550M S2H                       | 1        | 2.17%   |
| Gigabyte B550M DS3H                      | 1        | 2.17%   |
| GALAX B550M                              | 1        | 2.17%   |
| Fujitsu ESPRIMO P720                     | 1        | 2.17%   |
| Foxconn Pro3500 Series                   | 1        | 2.17%   |
| Dell OptiPlex 780                        | 1        | 2.17%   |
| Dell OptiPlex 7010                       | 1        | 2.17%   |
| Biostar H61MH                            | 1        | 2.17%   |
| Biostar A780L3B                          | 1        | 2.17%   |
| ASUS Z170-P                              | 1        | 2.17%   |
| ASUS TUF Gaming B450-PLUS II             | 1        | 2.17%   |
| ASUS ROG Maximus XIII HERO               | 1        | 2.17%   |
| ASUS PRIME B450M-A                       | 1        | 2.17%   |
| ASUS P8H61/USB3 R2.0                     | 1        | 2.17%   |
| ASUS P5GC-MX/MEDION/SI                   | 1        | 2.17%   |
| ASUS P5GC-MX/CKD/SI                      | 1        | 2.17%   |
| ASUS P5G41T-M LX                         | 1        | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 4        | 8.7%    |
| HP Compaq            | 2        | 4.35%   |
| Gigabyte B550M       | 2        | 4.35%   |
| ASUS P5GC-MX         | 2        | 4.35%   |
| ASUS All             | 2        | 4.35%   |
| Pegatron FQ425AA-ABA | 1        | 2.17%   |
| MSI MS-7C91          | 1        | 2.17%   |
| MSI MS-7C37          | 1        | 2.17%   |
| MSI MS-7A34          | 1        | 2.17%   |
| MSI MS-7917          | 1        | 2.17%   |
| MSI MS-7758          | 1        | 2.17%   |
| MP MS-7848           | 1        | 2.17%   |
| Medion Akoya         | 1        | 2.17%   |
| Lenovo ThinkStation  | 1        | 2.17%   |
| Lenovo ThinkCentre   | 1        | 2.17%   |
| Lenovo 10AAS1QB0B    | 1        | 2.17%   |
| Intel V1.3           | 1        | 2.17%   |
| Intel DH55TC         | 1        | 2.17%   |
| Huanan X99-F8        | 1        | 2.17%   |
| HP Z400              | 1        | 2.17%   |
| Gigabyte Z390        | 1        | 2.17%   |
| Gigabyte X570        | 1        | 2.17%   |
| Gigabyte H410M       | 1        | 2.17%   |
| Gigabyte B560M       | 1        | 2.17%   |
| GALAX B550M          | 1        | 2.17%   |
| Fujitsu ESPRIMO      | 1        | 2.17%   |
| Foxconn Pro3500      | 1        | 2.17%   |
| Biostar H61MH        | 1        | 2.17%   |
| Biostar A780L3B      | 1        | 2.17%   |
| ASUS Z170-P          | 1        | 2.17%   |
| ASUS TUF             | 1        | 2.17%   |
| ASUS ROG             | 1        | 2.17%   |
| ASUS PRIME           | 1        | 2.17%   |
| ASUS P8H61           | 1        | 2.17%   |
| ASUS P5G41T-M        | 1        | 2.17%   |
| ASRock X570          | 1        | 2.17%   |
| ASRock N3150M        | 1        | 2.17%   |
| ASRock B365M         | 1        | 2.17%   |
| AOpen ESPRIMO        | 1        | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 7        | 15.22%  |
| 2021 | 4        | 8.7%    |
| 2019 | 4        | 8.7%    |
| 2018 | 4        | 8.7%    |
| 2007 | 4        | 8.7%    |
| 2014 | 3        | 6.52%   |
| 2013 | 3        | 6.52%   |
| 2012 | 3        | 6.52%   |
| 2010 | 3        | 6.52%   |
| 2009 | 3        | 6.52%   |
| 2016 | 2        | 4.35%   |
| 2015 | 2        | 4.35%   |
| 2011 | 2        | 4.35%   |
| 2017 | 1        | 2.17%   |
| 2008 | 1        | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 46       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 46       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 46       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 13       | 28.26%  |
| 32.01-64.0  | 12       | 26.09%  |
| 4.01-8.0    | 8        | 17.39%  |
| 3.01-4.0    | 6        | 13.04%  |
| 16.01-24.0  | 4        | 8.7%    |
| 24.01-32.0  | 1        | 2.17%   |
| 2.01-3.0    | 1        | 2.17%   |
| 64.01-256.0 | 1        | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 18       | 39.13%  |
| 2.01-3.0   | 12       | 26.09%  |
| 3.01-4.0   | 6        | 13.04%  |
| 4.01-8.0   | 5        | 10.87%  |
| 8.01-16.0  | 3        | 6.52%   |
| 16.01-24.0 | 1        | 2.17%   |
| 0.51-1.0   | 1        | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 14       | 30.43%  |
| 1      | 13       | 28.26%  |
| 3      | 12       | 26.09%  |
| 4      | 4        | 8.7%    |
| 5      | 2        | 4.35%   |
| 8      | 1        | 2.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 52.17%  |
| Yes       | 22       | 47.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 46       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 60.87%  |
| Yes       | 18       | 39.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 86.96%  |
| Yes       | 6        | 13.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 11       | 23.91%  |
| Germany     | 7        | 15.22%  |
| Poland      | 3        | 6.52%   |
| Italy       | 3        | 6.52%   |
| Switzerland | 2        | 4.35%   |
| India       | 2        | 4.35%   |
| Venezuela   | 1        | 2.17%   |
| UK          | 1        | 2.17%   |
| Sweden      | 1        | 2.17%   |
| Spain       | 1        | 2.17%   |
| Russia      | 1        | 2.17%   |
| New Zealand | 1        | 2.17%   |
| Netherlands | 1        | 2.17%   |
| Mexico      | 1        | 2.17%   |
| Indonesia   | 1        | 2.17%   |
| Hungary     | 1        | 2.17%   |
| Greece      | 1        | 2.17%   |
| France      | 1        | 2.17%   |
| Finland     | 1        | 2.17%   |
| Estonia     | 1        | 2.17%   |
| Colombia    | 1        | 2.17%   |
| Canada      | 1        | 2.17%   |
| Brazil      | 1        | 2.17%   |
| Australia   | 1        | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Ettingen            | 2        | 4.35%   |
| Volos               | 1        | 2.17%   |
| Voghera             | 1        | 2.17%   |
| Vilhelmina          | 1        | 2.17%   |
| Vasco da Gama       | 1        | 2.17%   |
| Vaidasoo            | 1        | 2.17%   |
| Stevens Point       | 1        | 2.17%   |
| St Petersburg       | 1        | 2.17%   |
| Seelbach            | 1        | 2.17%   |
| San Diego           | 1        | 2.17%   |
| Rzeszów            | 1        | 2.17%   |
| Rosporden           | 1        | 2.17%   |
| Rathenow            | 1        | 2.17%   |
| Puebla City         | 1        | 2.17%   |
| Portland            | 1        | 2.17%   |
| Pompano Beach       | 1        | 2.17%   |
| Pila                | 1        | 2.17%   |
| Piedmont            | 1        | 2.17%   |
| Normal              | 1        | 2.17%   |
| Milwaukee           | 1        | 2.17%   |
| Maringá            | 1        | 2.17%   |
| Lodi                | 1        | 2.17%   |
| Krakow              | 1        | 2.17%   |
| Katonah             | 1        | 2.17%   |
| Kamiah              | 1        | 2.17%   |
| Houston             | 1        | 2.17%   |
| Herzogenrath        | 1        | 2.17%   |
| Helsinki            | 1        | 2.17%   |
| Granadilla de Abona | 1        | 2.17%   |
| Gouda               | 1        | 2.17%   |
| Göttingen          | 1        | 2.17%   |
| Freital             | 1        | 2.17%   |
| Dieburg             | 1        | 2.17%   |
| Denpasar            | 1        | 2.17%   |
| Chingford           | 1        | 2.17%   |
| Cambridge           | 1        | 2.17%   |
| Budapest            | 1        | 2.17%   |
| Brisbane            | 1        | 2.17%   |
| Bozzolo             | 1        | 2.17%   |
| Bogotá             | 1        | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 20       | 33     | 22.73%  |
| Seagate             | 17       | 24     | 19.32%  |
| WDC                 | 12       | 16     | 13.64%  |
| Kingston            | 9        | 9      | 10.23%  |
| Toshiba             | 4        | 4      | 4.55%   |
| Hitachi             | 3        | 4      | 3.41%   |
| Crucial             | 3        | 3      | 3.41%   |
| Corsair             | 3        | 3      | 3.41%   |
| PNY                 | 2        | 3      | 2.27%   |
| GOODRAM             | 2        | 2      | 2.27%   |
| Apacer              | 2        | 2      | 2.27%   |
| A-DATA Technology   | 2        | 2      | 2.27%   |
| Transcend           | 1        | 1      | 1.14%   |
| SPCC                | 1        | 1      | 1.14%   |
| SanDisk             | 1        | 1      | 1.14%   |
| OCZ                 | 1        | 1      | 1.14%   |
| Micron Technology   | 1        | 1      | 1.14%   |
| Maxtor              | 1        | 1      | 1.14%   |
| JMicron Technology  | 1        | 1      | 1.14%   |
| Avant               | 1        | 1      | 1.14%   |
| Acer                | 1        | 1      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD     | 4        | 3.7%    |
| Seagate ST2000DM008-2FR102 2TB      | 3        | 2.78%   |
| Samsung SSD 850 EVO 250GB           | 3        | 2.78%   |
| Toshiba DT01ACA100 1TB              | 2        | 1.85%   |
| Seagate ST3500413AS 500GB           | 2        | 1.85%   |
| Samsung SSD 970 EVO Plus 1TB        | 2        | 1.85%   |
| Samsung SSD 850 EVO 500GB           | 2        | 1.85%   |
| Samsung SSD 850 EVO 1TB             | 2        | 1.85%   |
| Kingston SV300S37A240G 240GB SSD    | 2        | 1.85%   |
| Corsair MP400 2TB                   | 2        | 1.85%   |
| WDC WDS500G2B0C-00PXH0 500GB        | 1        | 0.93%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 0.93%   |
| WDC WD800AAJS-60M0A0 80GB           | 1        | 0.93%   |
| WDC WD60EZRZ-00RWYB1 6TB            | 1        | 0.93%   |
| WDC WD60EFRX-68L0BN1 6TB            | 1        | 0.93%   |
| WDC WD5002AALX-00J37A0 500GB        | 1        | 0.93%   |
| WDC WD5000AVCS-632DY1 500GB         | 1        | 0.93%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 0.93%   |
| WDC WD30EFRX-68AX9N0 3TB            | 1        | 0.93%   |
| WDC WD20EZRX-22D8PB0 2TB            | 1        | 0.93%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 0.93%   |
| WDC WD10EZEX-00BBHA0 1TB            | 1        | 0.93%   |
| WDC WD10EVDS-63U8B1 1TB             | 1        | 0.93%   |
| WDC WD10EADS-98M2B0 1TB             | 1        | 0.93%   |
| WDC WD10EADS-00M2B0 1TB             | 1        | 0.93%   |
| Transcend TS128GSSD370S 128GB       | 1        | 0.93%   |
| Toshiba MQ01ABF050 500GB            | 1        | 0.93%   |
| Toshiba DT01ACA100 LENOVO 1TB       | 1        | 0.93%   |
| SPCC Solid State Disk 256GB         | 1        | 0.93%   |
| Seagate ST500LT012-9WS142 500GB     | 1        | 0.93%   |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 0.93%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 0.93%   |
| Seagate ST380815AS 80GB             | 1        | 0.93%   |
| Seagate ST3360320AS 360GB           | 1        | 0.93%   |
| Seagate ST320LT020-9YG142 320GB     | 1        | 0.93%   |
| Seagate ST320LT012-1DG14C 320GB     | 1        | 0.93%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1        | 0.93%   |
| Seagate ST3160815AS 160GB           | 1        | 0.93%   |
| Seagate ST31000524NS 1TB            | 1        | 0.93%   |
| Seagate ST250DM000-1BD141 250GB     | 1        | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 24     | 44.74%  |
| WDC                 | 10       | 14     | 26.32%  |
| Toshiba             | 4        | 4      | 10.53%  |
| Samsung Electronics | 3        | 3      | 7.89%   |
| Hitachi             | 3        | 4      | 7.89%   |
| Maxtor              | 1        | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 15       | 19     | 37.5%   |
| Kingston            | 9        | 9      | 22.5%   |
| GOODRAM             | 2        | 2      | 5%      |
| Crucial             | 2        | 2      | 5%      |
| A-DATA Technology   | 2        | 2      | 5%      |
| WDC                 | 1        | 1      | 2.5%    |
| Transcend           | 1        | 1      | 2.5%    |
| SPCC                | 1        | 1      | 2.5%    |
| SanDisk             | 1        | 1      | 2.5%    |
| PNY                 | 1        | 1      | 2.5%    |
| OCZ                 | 1        | 1      | 2.5%    |
| Micron Technology   | 1        | 1      | 2.5%    |
| Avant               | 1        | 1      | 2.5%    |
| Apacer              | 1        | 1      | 2.5%    |
| Acer                | 1        | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 33       | 50     | 40.24%  |
| SSD     | 32       | 44     | 39.02%  |
| NVMe    | 16       | 19     | 19.51%  |
| Unknown | 1        | 1      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 45       | 92     | 71.43%  |
| NVMe | 16       | 19     | 25.4%   |
| SAS  | 2        | 3      | 3.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 36       | 58     | 55.38%  |
| 0.51-1.0   | 18       | 20     | 27.69%  |
| 1.01-2.0   | 7        | 10     | 10.77%  |
| 3.01-4.0   | 2        | 2      | 3.08%   |
| 2.01-3.0   | 1        | 1      | 1.54%   |
| 4.01-10.0  | 1        | 3      | 1.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 11       | 23.91%  |
| 251-500        | 10       | 21.74%  |
| 1001-2000      | 8        | 17.39%  |
| More than 3000 | 5        | 10.87%  |
| 501-1000       | 5        | 10.87%  |
| 51-100         | 4        | 8.7%    |
| 2001-3000      | 2        | 4.35%   |
| 1-20           | 1        | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 11       | 23.4%   |
| 21-50          | 8        | 17.02%  |
| 1-20           | 8        | 17.02%  |
| 51-100         | 7        | 14.89%  |
| 251-500        | 4        | 8.51%   |
| 1001-2000      | 4        | 8.51%   |
| More than 3000 | 2        | 4.26%   |
| 501-1000       | 2        | 4.26%   |
| 2001-3000      | 1        | 2.13%   |

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
| Works    | 41       | 89     | 67.21%  |
| Malfunc  | 18       | 22     | 29.51%  |
| Detected | 2        | 3      | 3.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 32       | 47.76%  |
| AMD                       | 13       | 19.4%   |
| Samsung Electronics       | 9        | 13.43%  |
| Phison Electronics        | 5        | 7.46%   |
| ASMedia Technology        | 4        | 5.97%   |
| ULi Electronics           | 1        | 1.49%   |
| SanDisk                   | 1        | 1.49%   |
| Nvidia                    | 1        | 1.49%   |
| Micron/Crucial Technology | 1        | 1.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 5.88%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 5.88%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 5.88%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 4.71%   |
| Phison E12 NVMe Controller                                                              | 3        | 3.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 3.53%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 3.53%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 3.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 3.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 3.53%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 3.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 2.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 2.35%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 2.35%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 2.35%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 2.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 2.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 2.35%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 2.35%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 2.35%   |
| ULi M5229 IDE                                                                           | 1        | 1.18%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.18%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 1.18%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 1.18%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.18%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.18%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.18%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 1.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.18%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1        | 1.18%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 1.18%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.18%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 37       | 55.22%  |
| NVMe | 16       | 23.88%  |
| IDE  | 11       | 16.42%  |
| RAID | 3        | 4.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 32       | 69.57%  |
| AMD    | 14       | 30.43%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 3        | 6.52%   |
| Intel Core i7-5820K CPU @ 3.30GHz               | 2        | 4.35%   |
| Intel Core i5-9600K CPU @ 3.70GHz               | 2        | 4.35%   |
| Intel Core i5-3350P CPU @ 3.10GHz               | 2        | 4.35%   |
| Intel Xeon CPU W3565 @ 3.20GHz                  | 1        | 2.17%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz             | 1        | 2.17%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz     | 1        | 2.17%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz          | 1        | 2.17%   |
| Intel Core i9-10850K CPU @ 3.60GHz              | 1        | 2.17%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 2.17%   |
| Intel Core i7 CPU 870 @ 2.93GHz                 | 1        | 2.17%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1        | 2.17%   |
| Intel Core i5-6402P CPU @ 2.80GHz               | 1        | 2.17%   |
| Intel Core i5-4690K CPU @ 3.50GHz               | 1        | 2.17%   |
| Intel Core i5-4570T CPU @ 2.90GHz               | 1        | 2.17%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 2.17%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 1        | 2.17%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1        | 2.17%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 1        | 2.17%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 1        | 2.17%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 1        | 2.17%   |
| Intel Core i3-10100 CPU @ 3.60GHz               | 1        | 2.17%   |
| Intel Core i3 CPU 550 @ 3.20GHz                 | 1        | 2.17%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz            | 1        | 2.17%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz            | 1        | 2.17%   |
| Intel Celeron CPU N3150 @ 1.60GHz               | 1        | 2.17%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz          | 1        | 2.17%   |
| AMD Ryzen Threadripper PRO 3945WX 12-Cores      | 1        | 2.17%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 2.17%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 2.17%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 2.17%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1        | 2.17%   |
| AMD Ryzen 7 1800X Eight-Core Processor          | 1        | 2.17%   |
| AMD Ryzen 5 PRO 3400G with Radeon Vega Graphics | 1        | 2.17%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 1        | 2.17%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 2.17%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 1        | 2.17%   |
| AMD Ryzen 3 3100 4-Core Processor               | 1        | 2.17%   |
| AMD Phenom II X4 925 Processor                  | 1        | 2.17%   |
| AMD Phenom 9150e Quad-Core Processor            | 1        | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 10       | 21.74%  |
| Intel Core i3           | 6        | 13.04%  |
| Intel Core 2 Duo        | 5        | 10.87%  |
| Intel Core i7           | 4        | 8.7%    |
| AMD Ryzen 7             | 4        | 8.7%    |
| AMD Ryzen 5             | 3        | 6.52%   |
| Intel Xeon              | 2        | 4.35%   |
| Other                   | 1        | 2.17%   |
| Intel Pentium Dual-Core | 1        | 2.17%   |
| Intel Pentium Dual      | 1        | 2.17%   |
| Intel Core i9           | 1        | 2.17%   |
| Intel Celeron           | 1        | 2.17%   |
| AMD Ryzen Threadripper  | 1        | 2.17%   |
| AMD Ryzen 9             | 1        | 2.17%   |
| AMD Ryzen 5 PRO         | 1        | 2.17%   |
| AMD Ryzen 3             | 1        | 2.17%   |
| AMD Phenom II X4        | 1        | 2.17%   |
| AMD Phenom              | 1        | 2.17%   |
| AMD Athlon              | 1        | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 15       | 32.61%  |
| 2      | 15       | 32.61%  |
| 6      | 7        | 15.22%  |
| 8      | 5        | 10.87%  |
| 12     | 3        | 6.52%   |
| 10     | 1        | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 58.7%   |
| 1      | 19       | 41.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 46       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 5        | 10.87%  |
| 0x306a9    | 4        | 8.7%    |
| 0x1067a    | 4        | 8.7%    |
| 0x08701021 | 3        | 6.52%   |
| 0x906ed    | 2        | 4.35%   |
| 0x6fd      | 2        | 4.35%   |
| 0x506e3    | 2        | 4.35%   |
| 0x306f2    | 2        | 4.35%   |
| 0x306c3    | 2        | 4.35%   |
| 0x206a7    | 2        | 4.35%   |
| 0x20655    | 2        | 4.35%   |
| 0x0800820d | 2        | 4.35%   |
| 0xa0671    | 1        | 2.17%   |
| 0xa0655    | 1        | 2.17%   |
| 0xa0653    | 1        | 2.17%   |
| 0x406c3    | 1        | 2.17%   |
| 0x106e5    | 1        | 2.17%   |
| 0x10676    | 1        | 2.17%   |
| 0x0a201016 | 1        | 2.17%   |
| 0x0a201009 | 1        | 2.17%   |
| 0x08301039 | 1        | 2.17%   |
| 0x08108109 | 1        | 2.17%   |
| 0x08101016 | 1        | 2.17%   |
| 0x08001138 | 1        | 2.17%   |
| 0x010000db | 1        | 2.17%   |
| 0x01000083 | 1        | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 7        | 15.22%  |
| Penryn      | 5        | 10.87%  |
| Zen 2       | 4        | 8.7%    |
| IvyBridge   | 4        | 8.7%    |
| Zen+        | 3        | 6.52%   |
| Zen 3       | 3        | 6.52%   |
| Zen         | 2        | 4.35%   |
| Westmere    | 2        | 4.35%   |
| Skylake     | 2        | 4.35%   |
| SandyBridge | 2        | 4.35%   |
| Nehalem     | 2        | 4.35%   |
| KabyLake    | 2        | 4.35%   |
| K10         | 2        | 4.35%   |
| Core        | 2        | 4.35%   |
| CometLake   | 2        | 4.35%   |
| Silvermont  | 1        | 2.17%   |
| Icelake     | 1        | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 18       | 35.29%  |
| Intel  | 18       | 35.29%  |
| AMD    | 15       | 29.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3        | 5.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 3.92%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 3.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 3.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 3.92%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 3.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.92%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2        | 3.92%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 1.96%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 1.96%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 1.96%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.96%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.96%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.96%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.96%   |
| Nvidia GK208 [GeForce GT 635]                                                            | 1        | 1.96%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1        | 1.96%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1        | 1.96%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 1.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.96%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 1.96%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.96%   |
| Intel HD Graphics 530                                                                    | 1        | 1.96%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.96%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 1.96%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                                        | 1        | 1.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 1.96%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1        | 1.96%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1        | 1.96%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                                         | 1        | 1.96%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1        | 1.96%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 1        | 1.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 1.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1        | 1.96%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                                 | 1        | 1.96%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 1.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 18       | 39.13%  |
| 1 x AMD     | 14       | 30.43%  |
| 1 x Intel   | 13       | 28.26%  |
| Intel + AMD | 1        | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 29       | 63.04%  |
| Proprietary | 14       | 30.43%  |
| Unknown     | 3        | 6.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 34.78%  |
| 7.01-8.0   | 8        | 17.39%  |
| 1.01-2.0   | 7        | 15.22%  |
| 0.51-1.0   | 6        | 13.04%  |
| 3.01-4.0   | 5        | 10.87%  |
| 8.01-16.0  | 2        | 4.35%   |
| 0.01-0.5   | 2        | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 15.69%  |
| Hewlett-Packard      | 5        | 9.8%    |
| Dell                 | 5        | 9.8%    |
| Acer                 | 5        | 9.8%    |
| Fujitsu Siemens      | 4        | 7.84%   |
| Goldstar             | 3        | 5.88%   |
| AOC                  | 3        | 5.88%   |
| Medion               | 2        | 3.92%   |
| Lenovo               | 2        | 3.92%   |
| Iiyama               | 2        | 3.92%   |
| Ancor Communications | 2        | 3.92%   |
| Vizio                | 1        | 1.96%   |
| Vestel Elektronik    | 1        | 1.96%   |
| SAC                  | 1        | 1.96%   |
| Philips              | 1        | 1.96%   |
| NEC Computers        | 1        | 1.96%   |
| MSI                  | 1        | 1.96%   |
| MiTAC                | 1        | 1.96%   |
| Grundig              | 1        | 1.96%   |
| Gigabyte Technology  | 1        | 1.96%   |
| Eizo                 | 1        | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                   | 2        | 3.7%    |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch       | 2        | 3.7%    |
| Vizio M220MV VIZ0062 1920x1080 509x286mm 23.0-inch                     | 1        | 1.85%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 1.85%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 1        | 1.85%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 1        | 1.85%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch    | 1        | 1.85%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch       | 1        | 1.85%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1        | 1.85%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x290mm 23.1-inch      | 1        | 1.85%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch      | 1        | 1.85%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1        | 1.85%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                  | 1        | 1.85%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch               | 1        | 1.85%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch            | 1        | 1.85%   |
| MSI G27C6 MSI5CA9 1920x1080 600x340mm 27.2-inch                        | 1        | 1.85%   |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                        | 1        | 1.85%   |
| MiTAC KOGAN TV MTC6306 1366x768 700x400mm 31.7-inch                    | 1        | 1.85%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch             | 1        | 1.85%   |
| Lenovo E24-20 LEN62A5 1920x1080 527x296mm 23.8-inch                    | 1        | 1.85%   |
| Iiyama PLE430 IVM46B4 1280x1024 340x270mm 17.1-inch                    | 1        | 1.85%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                  | 1        | 1.85%   |
| Hewlett-Packard ZR2330w HWP3069 1920x1080 509x286mm 23.0-inch          | 1        | 1.85%   |
| Hewlett-Packard X27q HPN3725 2560x1440 600x340mm 27.2-inch             | 1        | 1.85%   |
| Hewlett-Packard X27q HPN3724 2560x1440 597x336mm 27.0-inch             | 1        | 1.85%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch            | 1        | 1.85%   |
| Hewlett-Packard w17e HWP26E0 1440x900 408x255mm 18.9-inch              | 1        | 1.85%   |
| Hewlett-Packard 27es HWP3325 1920x1080 598x336mm 27.0-inch             | 1        | 1.85%   |
| Grundig WXGA GRU4448 1600x1200                                         | 1        | 1.85%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch               | 1        | 1.85%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 1        | 1.85%   |
| Goldstar E2350 GSM578F 1920x1080 510x290mm 23.1-inch                   | 1        | 1.85%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 797x334mm 34.0-inch       | 1        | 1.85%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch           | 1        | 1.85%   |
| Fujitsu Siemens B22W-5 ECO FUS07C3 1680x1050 474x296mm 22.0-inch       | 1        | 1.85%   |
| Eizo EV2333W ENC2069 1920x1080 510x287mm 23.0-inch                     | 1        | 1.85%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                      | 1        | 1.85%   |
| Dell SR2320L DELF03A 1920x1080 509x286mm 23.0-inch                     | 1        | 1.85%   |
| Dell S3422DW DELD103 3440x1440 800x330mm 34.1-inch                     | 1        | 1.85%   |
| Dell S2319H DELD0CA 1920x1080 509x286mm 23.0-inch                      | 1        | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 19       | 38.78%  |
| 2560x1440 (QHD)    | 6        | 12.24%  |
| 1680x1050 (WSXGA+) | 6        | 12.24%  |
| 3840x2160 (4K)     | 4        | 8.16%   |
| 1280x1024 (SXGA)   | 3        | 6.12%   |
| 3440x1440          | 2        | 4.08%   |
| 1920x1200 (WUXGA)  | 2        | 4.08%   |
| 1366x768 (WXGA)    | 2        | 4.08%   |
| 2560x1080          | 1        | 2.04%   |
| 1600x900 (HD+)     | 1        | 2.04%   |
| 1440x900 (WXGA+)   | 1        | 2.04%   |
| 1360x768           | 1        | 2.04%   |
| 1280x720 (HD)      | 1        | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 10       | 20.41%  |
| 27      | 9        | 18.37%  |
| 22      | 6        | 12.24%  |
| 31      | 5        | 10.2%   |
| 34      | 3        | 6.12%   |
| 24      | 3        | 6.12%   |
| 21      | 2        | 4.08%   |
| 17      | 2        | 4.08%   |
| 84      | 1        | 2.04%   |
| 54      | 1        | 2.04%   |
| 26      | 1        | 2.04%   |
| 20      | 1        | 2.04%   |
| 19      | 1        | 2.04%   |
| 18      | 1        | 2.04%   |
| 16      | 1        | 2.04%   |
| 15      | 1        | 2.04%   |
| Unknown | 1        | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 21       | 44.68%  |
| 401-500     | 10       | 21.28%  |
| 601-700     | 5        | 10.64%  |
| 701-800     | 3        | 6.38%   |
| 301-350     | 3        | 6.38%   |
| 351-400     | 2        | 4.26%   |
| 1501-2000   | 1        | 2.13%   |
| 1001-1500   | 1        | 2.13%   |
| Unknown     | 1        | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 32       | 66.67%  |
| 16/10 | 10       | 20.83%  |
| 5/4   | 3        | 6.25%   |
| 21/9  | 3        | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 17       | 34.69%  |
| 301-350        | 9        | 18.37%  |
| 351-500        | 8        | 16.33%  |
| 251-300        | 4        | 8.16%   |
| 151-200        | 4        | 8.16%   |
| More than 1000 | 2        | 4.08%   |
| 141-150        | 2        | 4.08%   |
| 121-130        | 1        | 2.04%   |
| 91-100         | 1        | 2.04%   |
| Unknown        | 1        | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 35       | 76.09%  |
| 101-120 | 8        | 17.39%  |
| 1-50    | 2        | 4.35%   |
| Unknown | 1        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 73.91%  |
| 2     | 8        | 17.39%  |
| 3     | 2        | 4.35%   |
| 0     | 2        | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 27       | 42.19%  |
| Intel                 | 17       | 26.56%  |
| Qualcomm Atheros      | 4        | 6.25%   |
| TP-Link               | 3        | 4.69%   |
| Ralink Technology     | 3        | 4.69%   |
| Broadcom              | 2        | 3.13%   |
| Xiaomi                | 1        | 1.56%   |
| Nvidia                | 1        | 1.56%   |
| Mercucys              | 1        | 1.56%   |
| Linksys               | 1        | 1.56%   |
| Edimax Technology     | 1        | 1.56%   |
| Broadcom Limited      | 1        | 1.56%   |
| AVM                   | 1        | 1.56%   |
| Aquantia              | 1        | 1.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 30%     |
| Intel I211 Gigabit Network Connection                             | 3        | 4.29%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.86%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 2.86%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 2.86%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.86%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.86%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 2.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.43%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 1.43%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 1.43%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 1.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 1.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 1.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.43%   |
| Realtek B1690189192                                               | 1        | 1.43%   |
| Realtek 802.11n                                                   | 1        | 1.43%   |
| Realtek 802.11ac NIC                                              | 1        | 1.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 1.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.43%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.43%   |
| Mercucys MW300UM RTL8192EU wifi                                   | 1        | 1.43%   |
| Linksys WUSB6300 V2                                               | 1        | 1.43%   |
| Intel Wireless 8260                                               | 1        | 1.43%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.43%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.43%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.43%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.43%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.43%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.43%   |
| Edimax RTL8192S WLAN Adapter                                      | 1        | 1.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.43%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1        | 1.43%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 1.43%   |
| AVM FRITZ!WLAN AC 860                                             | 1        | 1.43%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 35%     |
| TP-Link               | 3        | 15%     |
| Ralink Technology     | 3        | 15%     |
| Mercucys              | 1        | 5%      |
| Linksys               | 1        | 5%      |
| Intel                 | 1        | 5%      |
| Edimax Technology     | 1        | 5%      |
| Broadcom Limited      | 1        | 5%      |
| Broadcom              | 1        | 5%      |
| AVM                   | 1        | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 2        | 10%     |
| Ralink MT7601U Wireless Adapter                            | 2        | 10%     |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 5%      |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 1        | 5%      |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 1        | 5%      |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1        | 5%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1        | 5%      |
| Realtek B1690189192                                        | 1        | 5%      |
| Realtek 802.11n                                            | 1        | 5%      |
| Realtek 802.11ac NIC                                       | 1        | 5%      |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 5%      |
| Mercucys MW300UM RTL8192EU wifi                            | 1        | 5%      |
| Linksys WUSB6300 V2                                        | 1        | 5%      |
| Intel Wireless 8260                                        | 1        | 5%      |
| Edimax RTL8192S WLAN Adapter                               | 1        | 5%      |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1        | 5%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1        | 5%      |
| AVM FRITZ!WLAN AC 860                                      | 1        | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 23       | 47.92%  |
| Intel                 | 17       | 35.42%  |
| Qualcomm Atheros      | 4        | 8.33%   |
| Xiaomi                | 1        | 2.08%   |
| Nvidia                | 1        | 2.08%   |
| Broadcom              | 1        | 2.08%   |
| Aquantia              | 1        | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 42%     |
| Intel I211 Gigabit Network Connection                             | 3        | 6%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 4%      |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 4%      |
| Intel Ethernet Connection (2) I218-V                              | 2        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 4%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 4%      |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 4%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 2%      |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 2%      |
| Nvidia MCP61 Ethernet                                             | 1        | 2%      |
| Intel Ethernet Controller I225-V                                  | 1        | 2%      |
| Intel Ethernet Connection I217-V                                  | 1        | 2%      |
| Intel Ethernet Connection I217-LM                                 | 1        | 2%      |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2%      |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2%      |
| Intel 82578DM Gigabit Network Connection                          | 1        | 2%      |
| Intel 82578DC Gigabit Network Connection                          | 1        | 2%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2%      |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 46       | 71.88%  |
| WiFi     | 18       | 28.13%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 70.21%  |
| WiFi     | 14       | 29.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 84.78%  |
| 2     | 6        | 13.04%  |
| 3     | 1        | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 34       | 73.91%  |
| Yes  | 12       | 26.09%  |

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
| Intel                   | 31       | 38.27%  |
| AMD                     | 19       | 23.46%  |
| Nvidia                  | 16       | 19.75%  |
| C-Media Electronics     | 3        | 3.7%    |
| ROCCAT                  | 2        | 2.47%   |
| Creative Labs           | 2        | 2.47%   |
| Unknown                 | 1        | 1.23%   |
| TerraTec Electronic     | 1        | 1.23%   |
| Schiit Audio            | 1        | 1.23%   |
| Razer USA               | 1        | 1.23%   |
| JMTek                   | 1        | 1.23%   |
| GYROCOM C&C             | 1        | 1.23%   |
| GN Netcom               | 1        | 1.23%   |
| BEHRINGER International | 1        | 1.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                          | 5        | 5.38%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4        | 4.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4        | 4.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4        | 4.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 3.23%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3        | 3.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3        | 3.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3        | 3.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 3.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3        | 3.23%   |
| ROCCAT Khan AIMO                                                                                  | 2        | 2.15%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 2.15%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 2.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2        | 2.15%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 2.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 2.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2        | 2.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2        | 2.15%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 2        | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 2.15%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 2.15%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2        | 2.15%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 2.15%   |
| Unknown Realtek USB Audio Rear                                                                    | 1        | 1.08%   |
| Unknown Realtek USB Audio Front                                                                   | 1        | 1.08%   |
| TerraTec Electronic Aureon Dual USB                                                               | 1        | 1.08%   |
| Schiit Audio I'm Fulla Schiit                                                                     | 1        | 1.08%   |
| Razer USA Kraken Tournament Edition                                                               | 1        | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1        | 1.08%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 1.08%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 1.08%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 1.08%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 1.08%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 1.08%   |
| JMTek USB PnP Audio Device                                                                        | 1        | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 1.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 1.08%   |
| Intel Audio device                                                                                | 1        | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1        | 1.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 9        | 18%     |
| Corsair             | 8        | 16%     |
| Unknown             | 6        | 12%     |
| G.Skill             | 5        | 10%     |
| SK hynix            | 4        | 8%      |
| Samsung Electronics | 4        | 8%      |
| Ramaxel Technology  | 2        | 4%      |
| Nanya Technology    | 2        | 4%      |
| Micron Technology   | 2        | 4%      |
| A-DATA Technology   | 2        | 4%      |
| Transcend           | 1        | 2%      |
| Patriot             | 1        | 2%      |
| Elpida              | 1        | 2%      |
| Crucial             | 1        | 2%      |
| Apacer              | 1        | 2%      |
| Unknown             | 1        | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 3        | 5.56%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                 | 2        | 3.7%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 2        | 3.7%    |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 1.85%   |
| Unknown RAM Module 4GB DIMM 667MT/s                      | 1        | 1.85%   |
| Unknown RAM Module 4GB DIMM                              | 1        | 1.85%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 1.85%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s         | 1        | 1.85%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 1.85%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 1.85%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s     | 1        | 1.85%   |
| SK hynix RAM HMT125U6DFR8C-H9 2048MB DIMM DDR3 1333MT/s  | 1        | 1.85%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s     | 1        | 1.85%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s     | 1        | 1.85%   |
| Samsung RAM M378A1G43DB0-CPB 8GB DIMM DDR4 2133MT/s      | 1        | 1.85%   |
| Samsung RAM DDR3 1600 8G 8GB DIMM DDR3 1333MT/s          | 1        | 1.85%   |
| Ramaxel RAM RMUA5200ME78HAF-3200 8GB DIMM DDR4 3200MT/s  | 1        | 1.85%   |
| Ramaxel RAM RMR5030MN68F9F160 4GB DIMM DDR3 1333MT/s     | 1        | 1.85%   |
| Ramaxel RAM RMR5030ME68F9F160 4GB DIMM DDR3 1333MT/s     | 1        | 1.85%   |
| Ramaxel RAM RMR5030KD68F9F160 4GB DIMM DDR3 1333MT/s     | 1        | 1.85%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s      | 1        | 1.85%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s       | 1        | 1.85%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s       | 1        | 1.85%   |
| Micron RAM Module 8GB SODIMM DDR3 1333MT/s               | 1        | 1.85%   |
| Micron RAM Module 4GB SODIMM DDR3 1333MT/s               | 1        | 1.85%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 1.85%   |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s                | 1        | 1.85%   |
| Kingston RAM KHX3200C16D4/4GX 4GB DIMM DDR4 3600MT/s     | 1        | 1.85%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 1        | 1.85%   |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 3200MT/s      | 1        | 1.85%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s      | 1        | 1.85%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s    | 1        | 1.85%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 1.85%   |
| Kingston RAM 99U5471-033.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 1.85%   |
| Kingston RAM 9905471-006.A00LF 4096MB DIMM DDR3 1333MT/s | 1        | 1.85%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s    | 1        | 1.85%   |
| G.Skill RAM F4-3600C19-16GSXWB 16GB DIMM DDR4 3600MT/s   | 1        | 1.85%   |
| G.Skill RAM F3-2133C11-8GAR 8GB DIMM DDR3 2133MT/s       | 1        | 1.85%   |
| G.Skill RAM F3-12800CL9-4GBRL 4GB DIMM DDR3 1866MT/s     | 1        | 1.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 22       | 48.89%  |
| DDR3    | 15       | 33.33%  |
| DDR2    | 5        | 11.11%  |
| Unknown | 2        | 4.44%   |
| SDRAM   | 1        | 2.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 43       | 95.56%  |
| SODIMM | 2        | 4.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 17       | 34.69%  |
| 8192  | 12       | 24.49%  |
| 16384 | 8        | 16.33%  |
| 2048  | 7        | 14.29%  |
| 32768 | 3        | 6.12%   |
| 1024  | 2        | 4.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 7        | 14.58%  |
| 3600    | 6        | 12.5%   |
| 3200    | 5        | 10.42%  |
| 1600    | 5        | 10.42%  |
| 2133    | 4        | 8.33%   |
| 2667    | 3        | 6.25%   |
| 3400    | 2        | 4.17%   |
| 2666    | 2        | 4.17%   |
| 2048    | 2        | 4.17%   |
| 800     | 2        | 4.17%   |
| 667     | 2        | 4.17%   |
| 333     | 2        | 4.17%   |
| Unknown | 2        | 4.17%   |
| 3466    | 1        | 2.08%   |
| 2933    | 1        | 2.08%   |
| 1866    | 1        | 2.08%   |
| 1800    | 1        | 2.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 2        | 66.67%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| Canon MG5700 series | 1        | 33.33%  |
| Canon MF641C        | 1        | 33.33%  |
| Brother MFC-7340    | 1        | 33.33%  |

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
| 0     | 37       | 80.43%  |
| 1     | 8        | 17.39%  |
| 2     | 1        | 2.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Desktops | Percent |
|--------------------|----------|---------|
| Unassigned class   | 3        | 30%     |
| Graphics card      | 3        | 30%     |
| Net/wireless       | 2        | 20%     |
| Fingerprint reader | 1        | 10%     |
| Dvb card           | 1        | 10%     |

