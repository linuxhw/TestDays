Elementary 6.1 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

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
| ASUSTek  | M4N72-E                     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek  | H81-PLUS                    | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| Gigabyte | X470 AORUS ULTRA GAMING-... | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| Gigabyte | Z390 UD                     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| MSI      | B85I                        | [24674e9e3a](https://linux-hardware.org/?probe=24674e9e3a) | Feb 20, 2022 |
| Intel    | DH61BE AAG14062-210         | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| MSI      | B85I                        | [633f6bf495](https://linux-hardware.org/?probe=633f6bf495) | Feb 19, 2022 |
| ASUSTek  | M11AD                       | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| ASUSTek  | P5B                         | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel    | H61                         | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| ASUSTek  | PRIME Z590-A                | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar  | A68MD PRO                   | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| MSI      | B85I                        | [28c1f1b8ae](https://linux-hardware.org/?probe=28c1f1b8ae) | Feb 13, 2022 |
| ASUSTek  | PRIME Z590-A                | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| MSI      | B85I                        | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Gigabyte | F2A68HM-H                   | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Gigabyte | F2A68HM-H                   | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| ASUSTek  | PRIME A320M-K               | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek  | PRIME B360M-K               | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| ASUSTek  | H110M-C                     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| MSI      | B450I GAMING PLUS AC        | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| ECS      | H55H-M                      | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| ASUSTek  | ROG STRIX B360-H GAMING     | [92d9fdcc97](https://linux-hardware.org/?probe=92d9fdcc97) | Feb 07, 2022 |
| Lenovo   | NO DPK                      | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| HP       | 802E                        | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| ASUSTek  | H110M-C                     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek  | P5B                         | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn  | NETBOX nT-435/535 Ver       | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn  | NETBOX nT-435/535 Ver       | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP       | ProLiant ML110 G7           | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| ASUSTek  | H110M-C                     | [4d2233f824](https://linux-hardware.org/?probe=4d2233f824) | Feb 03, 2022 |
| HP       | 339A                        | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| Unknown  | Unknown                     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| HP       | 805D                        | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| ASUSTek  | H110I-PLUS                  | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte | B75M-D3H                    | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| MSI      | Z270 KRAIT GAMING           | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Gigabyte | H61M-DS2                    | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| ASRock   | H61M-HVS                    | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock   | H61M-HVS                    | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer     | ConceptD CM100-51A V:1.1    | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| FIRICH   | J1900                       | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| ASUSTek  | ROG STRIX B360-H GAMING     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| ASUSTek  | ROG STRIX X570-E GAMING     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| ASUSTek  | TUF B365M-PLUS GAMING       | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI      | B450 TOMAHAWK MAX II        | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| MSI      | B450M-A PRO MAX             | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| ASUSTek  | H61M-CS                     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| Unknown  | T3 MRD                      | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI      | X470 GAMING PLUS MAX        | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek  | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Foxconn  | 2AB1                        | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| Foxconn  | 2AB1                        | [de61623232](https://linux-hardware.org/?probe=de61623232) | Jan 11, 2022 |
| ASUSTek  | H110M-C                     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Gigabyte | X570 AORUS ELITE            | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| HP       | 8597                        | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte | GA-970A-D3                  | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock   | Z370 Pro4                   | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| ASRock   | B450M-HDV R4.0              | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Gigabyte | B85M-DS3H-A                 | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| MSI      | 2A9C                        | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| HP       | 3397                        | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek  | X79-DELUXE                  | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| HP       | 1589                        | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn  | 2AB1                        | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Gigabyte | Z390 UD                     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| Apple    | Mac-F42C88C8 Proto1         | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| ASUSTek  | H97-PLUS                    | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| MSI      | B450-A PRO MAX              | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte | H310M S2P                   | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Foxconn  | 2AB1                        | [d9077a5d94](https://linux-hardware.org/?probe=d9077a5d94) | Dec 18, 2021 |
| Foxconn  | 2AB1                        | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Gigabyte | Z590 AORUS ELITE AX         | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| ASUSTek  | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.11.0-43-generic    | 18       | 28.57%  |
| 5.13.0-28-generic    | 15       | 23.81%  |
| 5.13.0-27-generic    | 8        | 12.7%   |
| 5.11.0-41-generic    | 5        | 7.94%   |
| 5.13.0-30-generic    | 4        | 6.35%   |
| 5.11.0-44-generic    | 4        | 6.35%   |
| 5.13.0-25-generic    | 2        | 3.17%   |
| 5.11.0-46-generic    | 2        | 3.17%   |
| 5.13.0-28-lowlatency | 1        | 1.59%   |
| 5.13.0-22-generic    | 1        | 1.59%   |
| 5.11.0-43-lowlatency | 1        | 1.59%   |
| 5.11.0-40-generic    | 1        | 1.59%   |
| 5.11.0-37-generic    | 1        | 1.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 30       | 50%     |
| 5.11.0  | 30       | 50%     |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 30       | 50%     |
| 5.11    | 30       | 50%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 59       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 59       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 59       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 84.75%  |
| LightDM | 9        | 15.25%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 19       | 32.2%   |
| de_DE | 9        | 15.25%  |
| fr_FR | 6        | 10.17%  |
| es_ES | 6        | 10.17%  |
| en_GB | 5        | 8.47%   |
| ru_RU | 3        | 5.08%   |
| pl_PL | 2        | 3.39%   |
| tr_TR | 1        | 1.69%   |
| sr_RS | 1        | 1.69%   |
| pt_PT | 1        | 1.69%   |
| pt_BR | 1        | 1.69%   |
| ja_JP | 1        | 1.69%   |
| it_IT | 1        | 1.69%   |
| fr_CA | 1        | 1.69%   |
| en_CA | 1        | 1.69%   |
| en_AU | 1        | 1.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 32       | 54.24%  |
| BIOS | 27       | 45.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 56       | 94.92%  |
| Btrfs | 2        | 3.39%   |
| Xfs   | 1        | 1.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 52       | 88.14%  |
| GPT     | 5        | 8.47%   |
| MBR     | 2        | 3.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 96.61%  |
| Yes       | 2        | 3.39%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 94.92%  |
| Yes       | 3        | 5.08%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 18       | 30.51%  |
| Gigabyte Technology | 11       | 18.64%  |
| MSI                 | 8        | 13.56%  |
| Hewlett-Packard     | 7        | 11.86%  |
| ASRock              | 3        | 5.08%   |
| Intel               | 2        | 3.39%   |
| Foxconn             | 2        | 3.39%   |
| Unknown             | 2        | 3.39%   |
| Lenovo              | 1        | 1.69%   |
| FIRICH              | 1        | 1.69%   |
| ECS                 | 1        | 1.69%   |
| Biostar             | 1        | 1.69%   |
| Apple               | 1        | 1.69%   |
| Acer                | 1        | 1.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Gigabyte Z390 UD                 | 2        | 3.39%   |
| ASUS TUF GAMING B550M-PLUS       | 2        | 3.39%   |
| ASUS All Series                  | 2        | 3.39%   |
| Unknown                          | 2        | 3.39%   |
| MSI PPPPP-CCC#MMMMMMMM           | 1        | 1.69%   |
| MSI MS-7C52                      | 1        | 1.69%   |
| MSI MS-7C02                      | 1        | 1.69%   |
| MSI MS-7B86                      | 1        | 1.69%   |
| MSI MS-7B79                      | 1        | 1.69%   |
| MSI MS-7A59                      | 1        | 1.69%   |
| MSI MS-7A40                      | 1        | 1.69%   |
| MSI MS-7851                      | 1        | 1.69%   |
| Lenovo ThinkCentre M72e 3664AD7  | 1        | 1.69%   |
| Intel H61                        | 1        | 1.69%   |
| Intel DH61BE AAG14062-210        | 1        | 1.69%   |
| HP Z420 Workstation              | 1        | 1.69%   |
| HP Z240 SFF Workstation          | 1        | 1.69%   |
| HP ProLiant ML110 G7             | 1        | 1.69%   |
| HP ProDesk 600 G5 SFF            | 1        | 1.69%   |
| HP ProDesk 600 G2 SFF            | 1        | 1.69%   |
| HP Compaq Pro 6300 MT            | 1        | 1.69%   |
| HP Compaq Elite 8300 SFF         | 1        | 1.69%   |
| Gigabyte Z590 AORUS ELITE AX     | 1        | 1.69%   |
| Gigabyte X570 AORUS ELITE        | 1        | 1.69%   |
| Gigabyte X470 AORUS ULTRA GAMING | 1        | 1.69%   |
| Gigabyte H61M-DS2                | 1        | 1.69%   |
| Gigabyte H310M S2P 2.0           | 1        | 1.69%   |
| Gigabyte GA-970A-D3              | 1        | 1.69%   |
| Gigabyte F2A68HM-H               | 1        | 1.69%   |
| Gigabyte B85M-DS3H-A             | 1        | 1.69%   |
| Gigabyte B75M-D3H                | 1        | 1.69%   |
| Foxconn p6616f                   | 1        | 1.69%   |
| Foxconn nT435/nT535              | 1        | 1.69%   |
| FIRICH J1900                     | 1        | 1.69%   |
| ECS H55H-M                       | 1        | 1.69%   |
| Biostar A68MD PRO                | 1        | 1.69%   |
| ASUS X79-DELUXE                  | 1        | 1.69%   |
| ASUS TUF B365M-PLUS GAMING       | 1        | 1.69%   |
| ASUS ROG STRIX X570-E GAMING     | 1        | 1.69%   |
| ASUS ROG STRIX B360-H GAMING     | 1        | 1.69%   |
| ASUS PRIME Z590-A                | 1        | 1.69%   |
| ASUS PRIME B450M-GAMING/BR       | 1        | 1.69%   |
| ASUS PRIME B360M-K               | 1        | 1.69%   |
| ASUS P5B                         | 1        | 1.69%   |
| ASUS M5A78L-M LX3                | 1        | 1.69%   |
| ASUS M4N72-E                     | 1        | 1.69%   |
| ASUS M11AD                       | 1        | 1.69%   |
| ASUS H61M-CS                     | 1        | 1.69%   |
| ASUS H110M-C                     | 1        | 1.69%   |
| ASUS H110I-PLUS                  | 1        | 1.69%   |
| ASRock Z370 Pro4                 | 1        | 1.69%   |
| ASRock H61M-HVS                  | 1        | 1.69%   |
| ASRock B450M-HDV R4.0            | 1        | 1.69%   |
| Apple MacPro3,1                  | 1        | 1.69%   |
| Acer ConceptD CM100-51A          | 1        | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS TUF               | 3        | 5.08%   |
| ASUS PRIME             | 3        | 5.08%   |
| HP ProDesk             | 2        | 3.39%   |
| HP Compaq              | 2        | 3.39%   |
| Gigabyte Z390          | 2        | 3.39%   |
| ASUS ROG               | 2        | 3.39%   |
| ASUS All               | 2        | 3.39%   |
| Unknown                | 2        | 3.39%   |
| MSI PPPPP-CCC#MMMMMMMM | 1        | 1.69%   |
| MSI MS-7C52            | 1        | 1.69%   |
| MSI MS-7C02            | 1        | 1.69%   |
| MSI MS-7B86            | 1        | 1.69%   |
| MSI MS-7B79            | 1        | 1.69%   |
| MSI MS-7A59            | 1        | 1.69%   |
| MSI MS-7A40            | 1        | 1.69%   |
| MSI MS-7851            | 1        | 1.69%   |
| Lenovo ThinkCentre     | 1        | 1.69%   |
| Intel H61              | 1        | 1.69%   |
| Intel DH61BE           | 1        | 1.69%   |
| HP Z420                | 1        | 1.69%   |
| HP Z240                | 1        | 1.69%   |
| HP ProLiant            | 1        | 1.69%   |
| Gigabyte Z590          | 1        | 1.69%   |
| Gigabyte X570          | 1        | 1.69%   |
| Gigabyte X470          | 1        | 1.69%   |
| Gigabyte H61M-DS2      | 1        | 1.69%   |
| Gigabyte H310M         | 1        | 1.69%   |
| Gigabyte GA-970A-D3    | 1        | 1.69%   |
| Gigabyte F2A68HM-H     | 1        | 1.69%   |
| Gigabyte B85M-DS3H-A   | 1        | 1.69%   |
| Gigabyte B75M-D3H      | 1        | 1.69%   |
| Foxconn p6616f         | 1        | 1.69%   |
| Foxconn nT435          | 1        | 1.69%   |
| FIRICH J1900           | 1        | 1.69%   |
| ECS H55H-M             | 1        | 1.69%   |
| Biostar A68MD          | 1        | 1.69%   |
| ASUS X79-DELUXE        | 1        | 1.69%   |
| ASUS P5B               | 1        | 1.69%   |
| ASUS M5A78L-M          | 1        | 1.69%   |
| ASUS M4N72-E           | 1        | 1.69%   |
| ASUS M11AD             | 1        | 1.69%   |
| ASUS H61M-CS           | 1        | 1.69%   |
| ASUS H110M-C           | 1        | 1.69%   |
| ASUS H110I-PLUS        | 1        | 1.69%   |
| ASRock Z370            | 1        | 1.69%   |
| ASRock H61M-HVS        | 1        | 1.69%   |
| ASRock B450M-HDV       | 1        | 1.69%   |
| Apple MacPro3          | 1        | 1.69%   |
| Acer ConceptD          | 1        | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 9        | 15.25%  |
| 2012 | 8        | 13.56%  |
| 2019 | 7        | 11.86%  |
| 2020 | 6        | 10.17%  |
| 2015 | 5        | 8.47%   |
| 2011 | 5        | 8.47%   |
| 2013 | 4        | 6.78%   |
| 2021 | 3        | 5.08%   |
| 2016 | 3        | 5.08%   |
| 2010 | 3        | 5.08%   |
| 2017 | 2        | 3.39%   |
| 2014 | 2        | 3.39%   |
| 2008 | 1        | 1.69%   |
| 2006 | 1        | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 59       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 59       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 59       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 14       | 23.73%  |
| 16.01-24.0  | 14       | 23.73%  |
| 8.01-16.0   | 10       | 16.95%  |
| 4.01-8.0    | 9        | 15.25%  |
| 3.01-4.0    | 8        | 13.56%  |
| 24.01-32.0  | 2        | 3.39%   |
| 2.01-3.0    | 1        | 1.69%   |
| 64.01-256.0 | 1        | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 25       | 40.32%  |
| 2.01-3.0  | 16       | 25.81%  |
| 4.01-8.0  | 10       | 16.13%  |
| 3.01-4.0  | 8        | 12.9%   |
| 8.01-16.0 | 3        | 4.84%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 23       | 38.98%  |
| 1      | 16       | 27.12%  |
| 3      | 10       | 16.95%  |
| 4      | 5        | 8.47%   |
| 7      | 2        | 3.39%   |
| 5      | 2        | 3.39%   |
| 6      | 1        | 1.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 59.32%  |
| Yes       | 24       | 40.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 59       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 52.54%  |
| Yes       | 28       | 47.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 67.8%   |
| Yes       | 19       | 32.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 10       | 16.95%  |
| USA          | 6        | 10.17%  |
| UK           | 5        | 8.47%   |
| Spain        | 5        | 8.47%   |
| France       | 5        | 8.47%   |
| Russia       | 2        | 3.39%   |
| Poland       | 2        | 3.39%   |
| Iran         | 2        | 3.39%   |
| India        | 2        | 3.39%   |
| Canada       | 2        | 3.39%   |
| Brazil       | 2        | 3.39%   |
| Argentina    | 2        | 3.39%   |
| Turkey       | 1        | 1.69%   |
| Thailand     | 1        | 1.69%   |
| Switzerland  | 1        | 1.69%   |
| Sweden       | 1        | 1.69%   |
| Sri Lanka    | 1        | 1.69%   |
| South Africa | 1        | 1.69%   |
| Serbia       | 1        | 1.69%   |
| Lithuania    | 1        | 1.69%   |
| Japan        | 1        | 1.69%   |
| Italy        | 1        | 1.69%   |
| Indonesia    | 1        | 1.69%   |
| Hong Kong    | 1        | 1.69%   |
| Czechia      | 1        | 1.69%   |
| Australia    | 1        | 1.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Warsaw                  | 2        | 3.28%   |
| Hamburg                 | 2        | 3.28%   |
| Znojmo                  | 1        | 1.64%   |
| Woolloongabba           | 1        | 1.64%   |
| Wolgast                 | 1        | 1.64%   |
| Wattala                 | 1        | 1.64%   |
| Vilanova i la GeltrÃº | 1        | 1.64%   |
| Uppsala                 | 1        | 1.64%   |
| Thrissur                | 1        | 1.64%   |
| Tehran                  | 1        | 1.64%   |
| Tangerang               | 1        | 1.64%   |
| Suresnes                | 1        | 1.64%   |
| Southampton             | 1        | 1.64%   |
| Sornay                  | 1        | 1.64%   |
| SÃ£o Paulo            | 1        | 1.64%   |
| Saguenay                | 1        | 1.64%   |
| Russell                 | 1        | 1.64%   |
| Rueso                   | 1        | 1.64%   |
| Pune                    | 1        | 1.64%   |
| Paris                   | 1        | 1.64%   |
| Oldham                  | 1        | 1.64%   |
| Oldenburg               | 1        | 1.64%   |
| Novi Sad                | 1        | 1.64%   |
| Neubrandenburg          | 1        | 1.64%   |
| Muralto                 | 1        | 1.64%   |
| Moscow                  | 1        | 1.64%   |
| Monmouth                | 1        | 1.64%   |
| Milan                   | 1        | 1.64%   |
| McKinney                | 1        | 1.64%   |
| MÃ¡laga               | 1        | 1.64%   |
| Madrid                  | 1        | 1.64%   |
| MaÅ¾eikiai            | 1        | 1.64%   |
| London                  | 1        | 1.64%   |
| Lauterbach              | 1        | 1.64%   |
| Larnage                 | 1        | 1.64%   |
| La Plata                | 1        | 1.64%   |
| Kobe                    | 1        | 1.64%   |
| Kingston                | 1        | 1.64%   |
| Khimki                  | 1        | 1.64%   |
| Johannesburg            | 1        | 1.64%   |
| Hennef                  | 1        | 1.64%   |
| Garin                   | 1        | 1.64%   |
| Edmonton                | 1        | 1.64%   |
| Dresden                 | 1        | 1.64%   |
| Dortmund                | 1        | 1.64%   |
| Denver                  | 1        | 1.64%   |
| Colorado Springs        | 1        | 1.64%   |
| Chana                   | 1        | 1.64%   |
| Central                 | 1        | 1.64%   |
| Campo Limpo Paulista    | 1        | 1.64%   |
| Brownfield              | 1        | 1.64%   |
| Berlin                  | 1        | 1.64%   |
| Bergenfield             | 1        | 1.64%   |
| Behshahr                | 1        | 1.64%   |
| Barnsley                | 1        | 1.64%   |
| Barcelona               | 1        | 1.64%   |
| Barakaldo               | 1        | 1.64%   |
| Ã‰pinay-sur-Seine    | 1        | 1.64%   |
| Ankara                  | 1        | 1.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 20       | 31     | 17.24%  |
| Seagate               | 17       | 20     | 14.66%  |
| Samsung Electronics   | 17       | 23     | 14.66%  |
| Kingston              | 10       | 11     | 8.62%   |
| Toshiba               | 7        | 8      | 6.03%   |
| Crucial               | 7        | 7      | 6.03%   |
| Unknown               | 4        | 8      | 3.45%   |
| SanDisk               | 3        | 4      | 2.59%   |
| PNY                   | 3        | 3      | 2.59%   |
| Phison                | 3        | 3      | 2.59%   |
| Intel                 | 3        | 3      | 2.59%   |
| ASMT                  | 3        | 3      | 2.59%   |
| A-DATA Technology     | 3        | 3      | 2.59%   |
| Hitachi               | 2        | 2      | 1.72%   |
| Transcend             | 1        | 1      | 0.86%   |
| Team                  | 1        | 1      | 0.86%   |
| Realtek Semiconductor | 1        | 1      | 0.86%   |
| OCZ                   | 1        | 1      | 0.86%   |
| Netac                 | 1        | 1      | 0.86%   |
| Micron Technology     | 1        | 1      | 0.86%   |
| MAXTOR                | 1        | 1      | 0.86%   |
| Leven                 | 1        | 1      | 0.86%   |
| JMicron               | 1        | 1      | 0.86%   |
| Intenso               | 1        | 1      | 0.86%   |
| Hewlett-Packard       | 1        | 1      | 0.86%   |
| GOODRAM               | 1        | 1      | 0.86%   |
| Gigabyte Technology   | 1        | 1      | 0.86%   |
| Corsair               | 1        | 1      | 0.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB       | 4        | 3.08%   |
| Crucial CT240BX500SSD1 240GB       | 3        | 2.31%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 2        | 1.54%   |
| Unknown SD/MMC 16GB                | 2        | 1.54%   |
| Unknown M.S./M.S.Pro/HG 16GB       | 2        | 1.54%   |
| Toshiba HDWD110 1TB                | 2        | 1.54%   |
| Toshiba DT01ACA050 500GB           | 2        | 1.54%   |
| Seagate ST1000DM003-1ER162 1TB     | 2        | 1.54%   |
| Samsung HD322HJ 320GB              | 2        | 1.54%   |
| PNY CS900 480GB SSD                | 2        | 1.54%   |
| Phison NVMe SSD Drive 1TB          | 2        | 1.54%   |
| Kingston SA400S37240G 240GB SSD    | 2        | 1.54%   |
| Kingston SA400S37120G 120GB SSD    | 2        | 1.54%   |
| Kingston NVMe SSD Drive 1TB        | 2        | 1.54%   |
| Crucial CT1000MX500SSD1 1TB        | 2        | 1.54%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.77%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD   | 1        | 0.77%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.77%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1        | 0.77%   |
| WDC WD6401AALS-00L3B2 640GB        | 1        | 0.77%   |
| WDC WD5000AAKX-001CA0 500GB        | 1        | 0.77%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 1        | 0.77%   |
| WDC WD5000AAKS-00A7B2 500GB        | 1        | 0.77%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1        | 0.77%   |
| WDC WD40EFRX-68N32N0 4TB           | 1        | 0.77%   |
| WDC WD3200AAJS-00L7A0 320GB        | 1        | 0.77%   |
| WDC WD30PURX-64P6ZY0 3TB           | 1        | 0.77%   |
| WDC WD3003FZEX-00Z4SA0 3TB         | 1        | 0.77%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1        | 0.77%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 0.77%   |
| WDC WD1600JS-55NCB1 160GB          | 1        | 0.77%   |
| WDC WD15EARX-00PASB0 1TB           | 1        | 0.77%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1        | 0.77%   |
| WDC WD10EZEX-08M2NA0 1TB           | 1        | 0.77%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 0.77%   |
| WDC WD10EADS-00L5B1 1TB            | 1        | 0.77%   |
| WDC SSC-D0064SC-2100 64GB          | 1        | 0.77%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB | 1        | 0.77%   |
| Unknown SD/MMC/MS PRO 64GB         | 1        | 0.77%   |
| Unknown SD/MMC/M.S.PRO 32GB        | 1        | 0.77%   |
| Unknown 128G32  128GB              | 1        | 0.77%   |
| Transcend TS512GSSD370S 512GB      | 1        | 0.77%   |
| Toshiba TR150 480GB SSD            | 1        | 0.77%   |
| Toshiba HDWE160 6TB                | 1        | 0.77%   |
| Toshiba HDWE140 4TB                | 1        | 0.77%   |
| Toshiba HDWD120 2TB                | 1        | 0.77%   |
| Team T253X1120G 120GB SSD          | 1        | 0.77%   |
| Seagate ST9500325AS 500GB          | 1        | 0.77%   |
| Seagate ST93205620AS 320GB         | 1        | 0.77%   |
| Seagate ST4000DX001-1CE168 4TB     | 1        | 0.77%   |
| Seagate ST3750528AS 752GB          | 1        | 0.77%   |
| Seagate ST3500418AS 500GB          | 1        | 0.77%   |
| Seagate ST3500312CS 500GB          | 1        | 0.77%   |
| Seagate ST3320620AS 320GB          | 1        | 0.77%   |
| Seagate ST3250310AS 250GB          | 1        | 0.77%   |
| Seagate ST3160811AS 160GB          | 1        | 0.77%   |
| Seagate ST2000DX002-2DV164 2TB     | 1        | 0.77%   |
| Seagate ST2000DM001-9YN164 2TB     | 1        | 0.77%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 0.77%   |
| Seagate ST1000DM003-1CH162 1TB     | 1        | 0.77%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 21     | 34.78%  |
| Seagate             | 16       | 19     | 34.78%  |
| Toshiba             | 6        | 7      | 13.04%  |
| Samsung Electronics | 2        | 3      | 4.35%   |
| Hitachi             | 2        | 2      | 4.35%   |
| ASMT                | 2        | 2      | 4.35%   |
| Unknown             | 1        | 1      | 2.17%   |
| Hewlett-Packard     | 1        | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 13     | 22.45%  |
| Crucial             | 7        | 7      | 14.29%  |
| Kingston            | 6        | 7      | 12.24%  |
| WDC                 | 4        | 8      | 8.16%   |
| SanDisk             | 3        | 4      | 6.12%   |
| PNY                 | 3        | 3      | 6.12%   |
| Intel               | 2        | 2      | 4.08%   |
| A-DATA Technology   | 2        | 2      | 4.08%   |
| Transcend           | 1        | 1      | 2.04%   |
| Toshiba             | 1        | 1      | 2.04%   |
| Team                | 1        | 1      | 2.04%   |
| OCZ                 | 1        | 1      | 2.04%   |
| Micron Technology   | 1        | 1      | 2.04%   |
| MAXTOR              | 1        | 1      | 2.04%   |
| Leven               | 1        | 1      | 2.04%   |
| Intenso             | 1        | 1      | 2.04%   |
| GOODRAM             | 1        | 1      | 2.04%   |
| Gigabyte Technology | 1        | 1      | 2.04%   |
| Corsair             | 1        | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 43       | 57     | 41.35%  |
| HDD     | 38       | 56     | 36.54%  |
| NVMe    | 16       | 19     | 15.38%  |
| Unknown | 6        | 10     | 5.77%   |
| MMC     | 1        | 1      | 0.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 55       | 110    | 67.9%   |
| NVMe | 16       | 19     | 19.75%  |
| SAS  | 9        | 13     | 11.11%  |
| MMC  | 1        | 1      | 1.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 41       | 67     | 54.67%  |
| 0.51-1.0   | 17       | 27     | 22.67%  |
| 1.01-2.0   | 7        | 8      | 9.33%   |
| 3.01-4.0   | 5        | 5      | 6.67%   |
| 4.01-10.0  | 3        | 3      | 4%      |
| 2.01-3.0   | 2        | 3      | 2.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 20       | 33.33%  |
| 251-500        | 16       | 26.67%  |
| 501-1000       | 9        | 15%     |
| More than 3000 | 5        | 8.33%   |
| 51-100         | 4        | 6.67%   |
| 1001-2000      | 3        | 5%      |
| 21-50          | 2        | 3.33%   |
| 2001-3000      | 1        | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 25       | 39.68%  |
| 21-50          | 11       | 17.46%  |
| 101-250        | 9        | 14.29%  |
| 51-100         | 6        | 9.52%   |
| 251-500        | 4        | 6.35%   |
| 1001-2000      | 3        | 4.76%   |
| 501-1000       | 3        | 4.76%   |
| More than 3000 | 1        | 1.59%   |
| 2001-3000      | 1        | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3500312CS 500GB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

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
| HDD  | 1        | 1      | 100%    |

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
| Detected | 54       | 126    | 88.52%  |
| Works    | 6        | 16     | 9.84%   |
| Malfunc  | 1        | 1      | 1.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 40       | 49.38%  |
| AMD                         | 17       | 20.99%  |
| Samsung Electronics         | 7        | 8.64%   |
| Kingston Technology Company | 4        | 4.94%   |
| Phison Electronics          | 3        | 3.7%    |
| Realtek Semiconductor       | 2        | 2.47%   |
| Marvell Technology Group    | 2        | 2.47%   |
| ASMedia Technology          | 2        | 2.47%   |
| Seagate Technology          | 1        | 1.23%   |
| Sandisk                     | 1        | 1.23%   |
| Nvidia                      | 1        | 1.23%   |
| JMicron Technology          | 1        | 1.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 8.42%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 7.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 6.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 5.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 4.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 4.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 4.21%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 3.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 3.16%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.11%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 2.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 2.11%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.11%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2        | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 2.11%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 2.11%   |
| Seagate FireCuda 530 SSD                                                                | 1        | 1.05%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.05%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 1.05%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 1.05%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 1.05%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.05%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 1.05%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 1.05%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 1.05%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 1.05%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                      | 1        | 1.05%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.05%   |
| Intel SSD 660P Series                                                                   | 1        | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.05%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.05%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 1.05%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 1.05%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 1.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.05%   |
| Intel 82801HB (ICH8) 4 port SATA Controller [AHCI mode]                                 | 1        | 1.05%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 1        | 1.05%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.05%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 54       | 66.67%  |
| NVMe | 16       | 19.75%  |
| IDE  | 9        | 11.11%  |
| RAID | 1        | 1.23%   |
| SAS  | 1        | 1.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 41       | 69.49%  |
| AMD    | 18       | 30.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-9700 CPU @ 3.00GHz               | 2        | 3.39%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 2        | 3.39%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 2        | 3.39%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 2        | 3.39%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 2        | 3.39%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 2        | 3.39%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 2        | 3.39%   |
| Intel Xeon CPU E5462 @ 2.80GHz                 | 1        | 1.69%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz             | 1        | 1.69%   |
| Intel Xeon CPU E31240 @ 3.30GHz                | 1        | 1.69%   |
| Intel Pentium CPU G630 @ 2.70GHz               | 1        | 1.69%   |
| Intel Core i7-9700K CPU @ 3.60GHz              | 1        | 1.69%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 1.69%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 1        | 1.69%   |
| Intel Core i7-4930K CPU @ 3.40GHz              | 1        | 1.69%   |
| Intel Core i7-4790S CPU @ 3.20GHz              | 1        | 1.69%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 1.69%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 1        | 1.69%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 1.69%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 1.69%   |
| Intel Core i5-9400F CPU @ 2.90GHz              | 1        | 1.69%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 1.69%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1        | 1.69%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 1        | 1.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 1.69%   |
| Intel Core i3-9100F CPU @ 3.60GHz              | 1        | 1.69%   |
| Intel Core i3-8100 CPU @ 3.60GHz               | 1        | 1.69%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1        | 1.69%   |
| Intel Core i3-4160 CPU @ 3.60GHz               | 1        | 1.69%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 1        | 1.69%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1        | 1.69%   |
| Intel Core i3 CPU 550 @ 3.20GHz                | 1        | 1.69%   |
| Intel Core i3 CPU 530 @ 2.93GHz                | 1        | 1.69%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz          | 1        | 1.69%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1        | 1.69%   |
| Intel Celeron CPU J1900 @ 1.99GHz              | 1        | 1.69%   |
| Intel Celeron CPU G530 @ 2.40GHz               | 1        | 1.69%   |
| Intel Celeron CPU G440 @ 1.60GHz               | 1        | 1.69%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 1        | 1.69%   |
| Intel Atom CPU D525 @ 1.80GHz                  | 1        | 1.69%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 1.69%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 1        | 1.69%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 1.69%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1        | 1.69%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1        | 1.69%   |
| AMD Phenom II X4 B55 Processor                 | 1        | 1.69%   |
| AMD Phenom II X4 955 Processor                 | 1        | 1.69%   |
| AMD Phenom II X4 820 Processor                 | 1        | 1.69%   |
| AMD FX-4100 Quad-Core Processor                | 1        | 1.69%   |
| AMD Athlon 200GE with Radeon Vega Graphics     | 1        | 1.69%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G  | 1        | 1.69%   |
| AMD A10-8750 Radeon R7, 12 Compute Cores 4C+8G | 1        | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i7     | 10       | 16.95%  |
| Intel Core i5     | 10       | 16.95%  |
| Intel Core i3     | 8        | 13.56%  |
| Intel Celeron     | 4        | 6.78%   |
| AMD Ryzen 7       | 4        | 6.78%   |
| AMD Ryzen 5       | 4        | 6.78%   |
| Intel Xeon        | 3        | 5.08%   |
| AMD Phenom II X4  | 3        | 5.08%   |
| Other             | 2        | 3.39%   |
| Intel Atom        | 2        | 3.39%   |
| AMD Ryzen 9       | 2        | 3.39%   |
| Intel Pentium     | 1        | 1.69%   |
| Intel Core 2 Quad | 1        | 1.69%   |
| AMD Ryzen 3       | 1        | 1.69%   |
| AMD FX            | 1        | 1.69%   |
| AMD Athlon        | 1        | 1.69%   |
| AMD A8            | 1        | 1.69%   |
| AMD A10           | 1        | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 23       | 38.98%  |
| 2      | 13       | 22.03%  |
| 8      | 11       | 18.64%  |
| 6      | 9        | 15.25%  |
| 12     | 2        | 3.39%   |
| 1      | 1        | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 58       | 98.31%  |
| 2      | 1        | 1.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 32       | 54.24%  |
| 1      | 27       | 45.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 59       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 7        | 11.86%  |
| 0x306c3    | 5        | 8.47%   |
| 0x08701021 | 4        | 6.78%   |
| 0x906ea    | 3        | 5.08%   |
| 0x506e3    | 3        | 5.08%   |
| 0x306a9    | 3        | 5.08%   |
| Unknown    | 3        | 5.08%   |
| 0xa0671    | 2        | 3.39%   |
| 0x906ed    | 2        | 3.39%   |
| 0x906eb    | 2        | 3.39%   |
| 0x906e9    | 2        | 3.39%   |
| 0x0800820d | 2        | 3.39%   |
| 0x06003106 | 2        | 3.39%   |
| 0x010000c8 | 2        | 3.39%   |
| 0x906ec    | 1        | 1.69%   |
| 0x706a8    | 1        | 1.69%   |
| 0x406c4    | 1        | 1.69%   |
| 0x306e4    | 1        | 1.69%   |
| 0x30678    | 1        | 1.69%   |
| 0x206d7    | 1        | 1.69%   |
| 0x20655    | 1        | 1.69%   |
| 0x20652    | 1        | 1.69%   |
| 0x106ca    | 1        | 1.69%   |
| 0x1067a    | 1        | 1.69%   |
| 0x10676    | 1        | 1.69%   |
| 0x0a201009 | 1        | 1.69%   |
| 0x08701013 | 1        | 1.69%   |
| 0x08108109 | 1        | 1.69%   |
| 0x08101016 | 1        | 1.69%   |
| 0x0600063e | 1        | 1.69%   |
| 0x010000db | 1        | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 11       | 18.64%  |
| SandyBridge   | 8        | 13.56%  |
| Zen 2         | 6        | 10.17%  |
| Haswell       | 5        | 8.47%   |
| Zen+          | 4        | 6.78%   |
| IvyBridge     | 4        | 6.78%   |
| Skylake       | 3        | 5.08%   |
| K10           | 3        | 5.08%   |
| Westmere      | 2        | 3.39%   |
| Steamroller   | 2        | 3.39%   |
| Silvermont    | 2        | 3.39%   |
| Penryn        | 2        | 3.39%   |
| Icelake       | 2        | 3.39%   |
| Zen 3         | 1        | 1.69%   |
| Zen           | 1        | 1.69%   |
| Goldmont plus | 1        | 1.69%   |
| Bulldozer     | 1        | 1.69%   |
| Bonnell       | 1        | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 25       | 40.98%  |
| Intel  | 18       | 29.51%  |
| AMD    | 18       | 29.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 7.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 4.69%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2        | 3.13%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 3.13%   |
| Intel HD Graphics 530                                                                    | 2        | 3.13%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 3.13%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 3.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 3.13%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2        | 3.13%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 1.56%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 1.56%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 1.56%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1        | 1.56%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1        | 1.56%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 1.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 1.56%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 1.56%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.56%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.56%   |
| Nvidia GK104 [GeForce GTX 670]                                                           | 1        | 1.56%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                                        | 1        | 1.56%   |
| Nvidia GF110 [GeForce GTX 580]                                                           | 1        | 1.56%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 1.56%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1        | 1.56%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1        | 1.56%   |
| Nvidia GF100 [GeForce GTX 470]                                                           | 1        | 1.56%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1        | 1.56%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 1        | 1.56%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 1.56%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1        | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 1.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.56%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 1.56%   |
| Intel HD Graphics 630                                                                    | 1        | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 1.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 1.56%   |
| AMD RV730 PRO [Radeon HD 4650]                                                           | 1        | 1.56%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                                         | 1        | 1.56%   |
| AMD RS880 [Radeon HD 4200]                                                               | 1        | 1.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.56%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1        | 1.56%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1        | 1.56%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 1        | 1.56%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                              | 1        | 1.56%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 1        | 1.56%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 1.56%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 1        | 1.56%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 25       | 42.37%  |
| 1 x Intel   | 16       | 27.12%  |
| 1 x AMD     | 15       | 25.42%  |
| 2 x AMD     | 2        | 3.39%   |
| Intel + AMD | 1        | 1.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 44       | 73.33%  |
| Proprietary | 16       | 26.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 28.33%  |
| 3.01-4.0   | 11       | 18.33%  |
| 1.01-2.0   | 11       | 18.33%  |
| 0.51-1.0   | 7        | 11.67%  |
| 7.01-8.0   | 5        | 8.33%   |
| 5.01-6.0   | 3        | 5%      |
| 0.01-0.5   | 3        | 5%      |
| 8.01-16.0  | 2        | 3.33%   |
| 2.01-3.0   | 1        | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 16.42%  |
| Acer                 | 9        | 13.43%  |
| Goldstar             | 7        | 10.45%  |
| Hewlett-Packard      | 5        | 7.46%   |
| Philips              | 4        | 5.97%   |
| Dell                 | 4        | 5.97%   |
| BenQ                 | 4        | 5.97%   |
| AOC                  | 3        | 4.48%   |
| Ancor Communications | 3        | 4.48%   |
| AUS                  | 2        | 2.99%   |
| ViewSonic            | 1        | 1.49%   |
| Vestel               | 1        | 1.49%   |
| MSI                  | 1        | 1.49%   |
| Mi                   | 1        | 1.49%   |
| LG Electronics       | 1        | 1.49%   |
| Lenovo               | 1        | 1.49%   |
| IOD                  | 1        | 1.49%   |
| Iiyama               | 1        | 1.49%   |
| HPN                  | 1        | 1.49%   |
| Element              | 1        | 1.49%   |
| Eizo                 | 1        | 1.49%   |
| CHR                  | 1        | 1.49%   |
| CHD                  | 1        | 1.49%   |
| BOE                  | 1        | 1.49%   |
| Unknown              | 1        | 1.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2        | 2.78%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                  | 2        | 2.78%   |
| ViewSonic LCD Monitor VX2260WM 3840x1080                               | 1        | 1.39%   |
| ViewSonic LCD Monitor VX2260WM                                         | 1        | 1.39%   |
| Vestel LCD Monitor 49FHD_LCD_TV 1920x1080                              | 1        | 1.39%   |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch      | 1        | 1.39%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch   | 1        | 1.39%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch   | 1        | 1.39%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch      | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch   | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch   | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SAM0530 1360x768                       | 1        | 1.39%   |
| Samsung Electronics LCD Monitor S22D300                                | 1        | 1.39%   |
| Samsung Electronics LC32G5xT SAM7088 2560x1440 700x400mm 31.7-inch     | 1        | 1.39%   |
| Philips PHL 275E1 PHLC20C 2560x1440 597x336mm 27.0-inch                | 1        | 1.39%   |
| Philips PHL 203V5 PHLC0CE 1600x900 434x236mm 19.4-inch                 | 1        | 1.39%   |
| Philips LCD Monitor PHL 276E8V 7680x2160                               | 1        | 1.39%   |
| Philips LCD Monitor PHL 276E8V                                         | 1        | 1.39%   |
| Philips LCD Monitor 19B 1280x1024                                      | 1        | 1.39%   |
| MSI MAG341CQ MSI1462 3440x1440 800x330mm 34.1-inch                     | 1        | 1.39%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                       | 1        | 1.39%   |
| LG Electronics LCD Monitor 2D FHD LG TV 3840x1080                      | 1        | 1.39%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                   | 1        | 1.39%   |
| IOD LCD-AD221F-T IOD1687 1920x1080 477x268mm 21.5-inch                 | 1        | 1.39%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                 | 1        | 1.39%   |
| HPN LCD Monitor HP 27fw 1920x1080                                      | 1        | 1.39%   |
| Hewlett-Packard OMEN by HP 32 HPN3378 2560x1440 708x399mm 32.0-inch    | 1        | 1.39%   |
| Hewlett-Packard LCD Monitor w17e 1440x900                              | 1        | 1.39%   |
| Hewlett-Packard 27q HPN3564 2560x1440 597x336mm 27.0-inch              | 1        | 1.39%   |
| Hewlett-Packard 24es HWP3320 1920x1080 527x296mm 23.8-inch             | 1        | 1.39%   |
| Hewlett-Packard 2010 HWP2889 1600x900 443x250mm 20.0-inch              | 1        | 1.39%   |
| Goldstar QHD GSM772A 2560x1440 697x392mm 31.5-inch                     | 1        | 1.39%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 1.39%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 1        | 1.39%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                 | 1        | 1.39%   |
| Goldstar 2D HD TV GSM59C8 1366x768 509x286mm 23.0-inch                 | 1        | 1.39%   |
| Element ELEFW328C ELE3553 1680x1050 690x390mm 31.2-inch                | 1        | 1.39%   |
| Eizo EV2455 ENC2533 1920x1200 519x324mm 24.1-inch                      | 1        | 1.39%   |
| Dell U2414H DELA0B2 1920x1080 527x296mm 23.8-inch                      | 1        | 1.39%   |
| Dell SE2216H DELF071 1920x1080 476x268mm 21.5-inch                     | 1        | 1.39%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                      | 1        | 1.39%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                      | 1        | 1.39%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                      | 1        | 1.39%   |
| CHR FULL-HD-00 CHR7511 1920x1080                                       | 1        | 1.39%   |
| CHD GDM-225JN CHD0220 1920x1080 490x270mm 22.0-inch                    | 1        | 1.39%   |
| BOE LCD Monitor BOE07B0 1920x1080 340x190mm 15.3-inch                  | 1        | 1.39%   |
| BenQ LCD Monitor PD2700U 3840x2160                                     | 1        | 1.39%   |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                      | 1        | 1.39%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                     | 1        | 1.39%   |
| BenQ BL2411 BNQ8011 1920x1200 518x324mm 24.1-inch                      | 1        | 1.39%   |
| AUS LCD Monitor VG27AQL1A 2560x1440                                    | 1        | 1.39%   |
| AUS LCD Monitor ASUS XG32V 1920x1080                                   | 1        | 1.39%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                         | 1        | 1.39%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                        | 1        | 1.39%   |
| AOC 2343 AOC2343 1920x1080 510x290mm 23.1-inch                         | 1        | 1.39%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                         | 1        | 1.39%   |
| Ancor Communications VW222 ACI22A2 1680x1050 473x296mm 22.0-inch       | 1        | 1.39%   |
| Ancor Communications LCD Monitor ASUS VS239 1920x1080                  | 1        | 1.39%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 1        | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 27       | 40.3%   |
| 2560x1440 (QHD)    | 10       | 14.93%  |
| 3840x2160 (4K)     | 6        | 8.96%   |
| 1366x768 (WXGA)    | 5        | 7.46%   |
| 1680x1050 (WSXGA+) | 3        | 4.48%   |
| 1600x900 (HD+)     | 3        | 4.48%   |
| Unknown            | 3        | 4.48%   |
| 3840x1080          | 2        | 2.99%   |
| 1920x1200 (WUXGA)  | 2        | 2.99%   |
| 1360x768           | 2        | 2.99%   |
| 7680x2160          | 1        | 1.49%   |
| 3440x1440          | 1        | 1.49%   |
| 1440x900 (WXGA+)   | 1        | 1.49%   |
| 1280x1024 (SXGA)   | 1        | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 20.31%  |
| 24      | 9        | 14.06%  |
| 21      | 9        | 14.06%  |
| 23      | 7        | 10.94%  |
| 27      | 6        | 9.38%   |
| 22      | 4        | 6.25%   |
| 32      | 3        | 4.69%   |
| 31      | 3        | 4.69%   |
| 20      | 2        | 3.13%   |
| 19      | 2        | 3.13%   |
| 15      | 2        | 3.13%   |
| 55      | 1        | 1.56%   |
| 48      | 1        | 1.56%   |
| 34      | 1        | 1.56%   |
| 26      | 1        | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 32.26%  |
| 401-500     | 16       | 25.81%  |
| Unknown     | 13       | 20.97%  |
| 601-700     | 5        | 8.06%   |
| 701-800     | 4        | 6.45%   |
| 301-350     | 2        | 3.23%   |
| 1001-1500   | 2        | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 38       | 64.41%  |
| Unknown | 12       | 20.34%  |
| 16/10   | 8        | 13.56%  |
| 21/9    | 1        | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 33.33%  |
| Unknown        | 13       | 20.63%  |
| 351-500        | 7        | 11.11%  |
| 301-350        | 6        | 9.52%   |
| 251-300        | 6        | 9.52%   |
| 151-200        | 6        | 9.52%   |
| More than 1000 | 2        | 3.17%   |
| 101-110        | 1        | 1.59%   |
| 91-100         | 1        | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 28       | 45.16%  |
| 101-120 | 15       | 24.19%  |
| Unknown | 13       | 20.97%  |
| 1-50    | 3        | 4.84%   |
| 121-160 | 3        | 4.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 47       | 79.66%  |
| 2     | 11       | 18.64%  |
| 3     | 1        | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 42       | 47.19%  |
| Intel                    | 25       | 28.09%  |
| Samsung Electronics      | 3        | 3.37%   |
| Ralink Technology        | 3        | 3.37%   |
| Broadcom                 | 3        | 3.37%   |
| TP-Link                  | 2        | 2.25%   |
| Qualcomm Atheros         | 2        | 2.25%   |
| Xiaomi                   | 1        | 1.12%   |
| Ralink                   | 1        | 1.12%   |
| Motorola PCS             | 1        | 1.12%   |
| Microsoft                | 1        | 1.12%   |
| Marvell Technology Group | 1        | 1.12%   |
| Linksys                  | 1        | 1.12%   |
| LG Electronics           | 1        | 1.12%   |
| D-Link System            | 1        | 1.12%   |
| AVM                      | 1        | 1.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 32.99%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 4.12%   |
| Intel Wi-Fi 6 AX200                                               | 4        | 4.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 3.09%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 3.09%   |
| Intel I211 Gigabit Network Connection                             | 3        | 3.09%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.09%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 2.06%   |
| Realtek 802.11ac NIC                                              | 2        | 2.06%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.06%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.06%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 2        | 2.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.03%   |
| TP-Link Archer T4U ver.3                                          | 1        | 1.03%   |
| TP-Link 802.11ac NIC                                              | 1        | 1.03%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.03%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.03%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1        | 1.03%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 1.03%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 1.03%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 1.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.03%   |
| Motorola PCS motorola edge                                        | 1        | 1.03%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 1.03%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless               | 1        | 1.03%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                         | 1        | 1.03%   |
| LG AN-WF100 802.11abgn Wireless Adapter [Broadcom BCM4323]        | 1        | 1.03%   |
| Intel Wireless-AC 9260                                            | 1        | 1.03%   |
| Intel Wireless 3165                                               | 1        | 1.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1        | 1.03%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 1.03%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.03%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 1.03%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W] | 1        | 1.03%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1        | 1.03%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                              | 1        | 1.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 9        | 28.13%  |
| Realtek Semiconductor    | 8        | 25%     |
| Ralink Technology        | 3        | 9.38%   |
| Broadcom                 | 3        | 9.38%   |
| TP-Link                  | 2        | 6.25%   |
| Ralink                   | 1        | 3.13%   |
| Microsoft                | 1        | 3.13%   |
| Marvell Technology Group | 1        | 3.13%   |
| Linksys                  | 1        | 3.13%   |
| LG Electronics           | 1        | 3.13%   |
| D-Link System            | 1        | 3.13%   |
| AVM                      | 1        | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                               | 4        | 12.5%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 9.38%   |
| Realtek 802.11ac NIC                                              | 2        | 6.25%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 2        | 6.25%   |
| TP-Link Archer T4U ver.3                                          | 1        | 3.13%   |
| TP-Link 802.11ac NIC                                              | 1        | 3.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 3.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 3.13%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 3.13%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1        | 3.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 3.13%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 3.13%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 3.13%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 3.13%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless               | 1        | 3.13%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                         | 1        | 3.13%   |
| LG AN-WF100 802.11abgn Wireless Adapter [Broadcom BCM4323]        | 1        | 3.13%   |
| Intel Wireless-AC 9260                                            | 1        | 3.13%   |
| Intel Wireless 3165                                               | 1        | 3.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1        | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 3.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 3.13%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W] | 1        | 3.13%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1        | 3.13%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                              | 1        | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 39       | 60%     |
| Intel                 | 19       | 29.23%  |
| Samsung Electronics   | 3        | 4.62%   |
| Qualcomm Atheros      | 2        | 3.08%   |
| Xiaomi                | 1        | 1.54%   |
| Motorola PCS          | 1        | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 49.23%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 6.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 4.62%   |
| Intel I211 Gigabit Network Connection                             | 3        | 4.62%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 4.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 4.62%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 3.08%   |
| Intel Ethernet Controller I225-V                                  | 2        | 3.08%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 3.08%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 3.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.54%   |
| Motorola PCS motorola edge                                        | 1        | 1.54%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.54%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.54%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 1.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 59       | 67.05%  |
| WiFi     | 29       | 32.95%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 57       | 71.25%  |
| WiFi     | 23       | 28.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 66.1%   |
| 2     | 16       | 27.12%  |
| 3     | 3        | 5.08%   |
| 0     | 1        | 1.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 43       | 71.67%  |
| Yes  | 17       | 28.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 8        | 42.11%  |
| Cambridge Silicon Radio | 7        | 36.84%  |
| Realtek Semiconductor   | 1        | 5.26%   |
| IMC Networks            | 1        | 5.26%   |
| ASUSTek Computer        | 1        | 5.26%   |
| Apple                   | 1        | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 36.84%  |
| Intel AX200 Bluetooth                               | 3        | 15.79%  |
| Realtek Bluetooth Radio                             | 1        | 5.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 5.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5.26%   |
| Intel Bluetooth wireless interface                  | 1        | 5.26%   |
| Intel Bluetooth Device                              | 1        | 5.26%   |
| Intel AX201 Bluetooth                               | 1        | 5.26%   |
| IMC Networks BCM20702A0                             | 1        | 5.26%   |
| ASUS BCM20702A0                                     | 1        | 5.26%   |
| Apple Bluetooth HCI                                 | 1        | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 37       | 37.37%  |
| Nvidia              | 24       | 24.24%  |
| AMD                 | 24       | 24.24%  |
| C-Media Electronics | 5        | 5.05%   |
| Creative Labs       | 4        | 4.04%   |
| Razer USA           | 1        | 1.01%   |
| Logitech            | 1        | 1.01%   |
| GN Netcom           | 1        | 1.01%   |
| Focusrite-Novation  | 1        | 1.01%   |
| Corsair             | 1        | 1.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH cAVS                                                        | 6        | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6        | 5.41%   |
| AMD Starship/Matisse HD Audio Controller                                          | 5        | 4.5%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 5        | 4.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 3.6%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 4        | 3.6%    |
| Nvidia TU104 HD Audio Controller                                                  | 3        | 2.7%    |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 2.7%    |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 2.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3        | 2.7%    |
| Intel 200 Series PCH HD Audio                                                     | 3        | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 2.7%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 3        | 2.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 2.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 1.8%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 1.8%    |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 1.8%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 1.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 1.8%    |
| AMD Kaveri HDMI/DP Audio Controller                                               | 2        | 1.8%    |
| AMD FCH Azalia Controller                                                         | 2        | 1.8%    |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 1.8%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 1.8%    |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver]        | 1        | 0.9%    |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.9%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 0.9%    |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.9%    |
| Nvidia GM204 High Definition Audio Controller                                     | 1        | 0.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 0.9%    |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.9%    |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 0.9%    |
| Nvidia GF110 High Definition Audio Controller                                     | 1        | 0.9%    |
| Nvidia GF100 High Definition Audio Controller                                     | 1        | 0.9%    |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 0.9%    |
| Nvidia GA102 High Definition Audio Controller                                     | 1        | 0.9%    |
| Logitech G733 Gaming Headset                                                      | 1        | 0.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 0.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1        | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 0.9%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1        | 0.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 1        | 0.9%    |
| Intel 631xESB/632xESB High Definition Audio Controller                            | 1        | 0.9%    |
| GN Netcom Jabra SPEAK 510 USB                                                     | 1        | 0.9%    |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                 | 1        | 0.9%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 1        | 0.9%    |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                        | 1        | 0.9%    |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                | 1        | 0.9%    |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                        | 1        | 0.9%    |
| Corsair VOID PRO Wireless Gaming Headset                                          | 1        | 0.9%    |
| C-Media Electronics SADES Hammer                                                  | 1        | 0.9%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 1        | 0.9%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1        | 0.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 0.9%    |
| AMD Navi 10 HDMI Audio                                                            | 1        | 0.9%    |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                             | 1        | 0.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 1        | 0.9%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 2        | 22.22%  |
| Corsair             | 2        | 22.22%  |
| Unknown             | 1        | 11.11%  |
| Samsung Electronics | 1        | 11.11%  |
| Ramaxel Technology  | 1        | 11.11%  |
| PNY                 | 1        | 11.11%  |
| Patriot             | 1        | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s              | 1        | 11.11%  |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s              | 1        | 11.11%  |
| Ramaxel RAM RMUA5090KB78HAF2133 8192MB DIMM DDR4 2133MT/s | 1        | 11.11%  |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 3200MT/s    | 1        | 11.11%  |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s        | 1        | 11.11%  |
| Kingston RAM 9905625-030.A00G 8192MB DIMM DDR4 2133MT/s   | 1        | 11.11%  |
| Kingston RAM 9905471-015.A00LF 4096MB DIMM DDR3 1333MT/s  | 1        | 11.11%  |
| Corsair RAM CMX8GX3M1A1600C11 8192MB DIMM DDR3 1600MT/s   | 1        | 11.11%  |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s      | 1        | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 5        | 62.5%   |
| DDR3 | 3        | 37.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 8        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 6        | 75%     |
| 32768 | 1        | 12.5%   |
| 4096  | 1        | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 2        | 25%     |
| 2800  | 1        | 12.5%   |
| 2666  | 1        | 12.5%   |
| 2133  | 1        | 12.5%   |
| 1600  | 1        | 12.5%   |
| 1333  | 1        | 12.5%   |
| 1066  | 1        | 12.5%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Canon PIXMA MG3600 Series | 1        | 100%    |

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


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 2        | 25%     |
| Logitech  | 2        | 25%     |
| Apple     | 2        | 25%     |
| Microdia  | 1        | 12.5%   |
| ANYKA     | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Apple iPhone 5/5C/5S/6/SE       | 2        | 25%     |
| Microsoft LifeCam VX-800        | 1        | 12.5%   |
| Microsoft LifeCam HD-3000       | 1        | 12.5%   |
| Microdia USB 2.0 Camera         | 1        | 12.5%   |
| Logitech Logi 4K Stream Edition | 1        | 12.5%   |
| Logitech B525 HD Webcam         | 1        | 12.5%   |
| ANYKA V380 FHD Camera           | 1        | 12.5%   |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Chicony Electronics | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 54       | 91.53%  |
| 1     | 5        | 8.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 5        | 83.33%  |
| Multimedia controller | 1        | 16.67%  |

