Elementary 6 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.

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

Total: 81

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Inventec | D CLASS A02                 | [d00d37285b](https://linux-hardware.org/?probe=d00d37285b) | Apr 19, 2022 |
| Gigabyte | B450M DS3H-CF               | [0bc837ffef](https://linux-hardware.org/?probe=0bc837ffef) | Apr 06, 2022 |
| ASUSTek  | PRIME B250-PRO              | [be377c733e](https://linux-hardware.org/?probe=be377c733e) | Feb 14, 2022 |
| ASRock   | AB350M Pro4                 | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| ASRock   | Z590 Phantom Gaming 4/ac    | [b52ca671f7](https://linux-hardware.org/?probe=b52ca671f7) | Dec 24, 2021 |
| Pegatron | IPMH61P1                    | [1ba6ea2ee9](https://linux-hardware.org/?probe=1ba6ea2ee9) | Dec 14, 2021 |
| Acer     | ConceptD CM100-51A V:1.1    | [0b3e5753fc](https://linux-hardware.org/?probe=0b3e5753fc) | Dec 13, 2021 |
| ASUSTek  | TUF GAMING B560M-PLUS       | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek  | PRIME A320M-K               | [fc49eed81d](https://linux-hardware.org/?probe=fc49eed81d) | Dec 09, 2021 |
| ASUSTek  | H81M-C                      | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| Dell     | 0MGK50 A02                  | [df4bb96e67](https://linux-hardware.org/?probe=df4bb96e67) | Dec 08, 2021 |
| ASUSTek  | M5A78L-M LX/BR              | [5c46f5e832](https://linux-hardware.org/?probe=5c46f5e832) | Dec 07, 2021 |
| Gigabyte | AX370-Gaming-CF se1         | [7cb1ebd6c9](https://linux-hardware.org/?probe=7cb1ebd6c9) | Dec 07, 2021 |
| Gigabyte | X570 AORUS PRO WIFI         | [a8e4016566](https://linux-hardware.org/?probe=a8e4016566) | Dec 06, 2021 |
| Gigabyte | X570 AORUS PRO WIFI         | [ebfed157e7](https://linux-hardware.org/?probe=ebfed157e7) | Dec 06, 2021 |
| Acer     | Aspire X3990                | [e291d06394](https://linux-hardware.org/?probe=e291d06394) | Dec 05, 2021 |
| MSI      | Z370 KRAIT GAMING           | [b213dc07b8](https://linux-hardware.org/?probe=b213dc07b8) | Dec 04, 2021 |
| MSI      | Z370 KRAIT GAMING           | [b562e90f75](https://linux-hardware.org/?probe=b562e90f75) | Dec 04, 2021 |
| Pegatron | Benicia                     | [51dae15bcd](https://linux-hardware.org/?probe=51dae15bcd) | Dec 03, 2021 |
| Gigabyte | AX370-Gaming-CF se1         | [313d4d0bd8](https://linux-hardware.org/?probe=313d4d0bd8) | Dec 03, 2021 |
| HP       | 8653 A                      | [85d1730019](https://linux-hardware.org/?probe=85d1730019) | Dec 01, 2021 |
| Gigabyte | B85M-DS3H-A                 | [fbe4820444](https://linux-hardware.org/?probe=fbe4820444) | Dec 01, 2021 |
| ASUSTek  | ROG STRIX Z490-F GAMING     | [500f9c8851](https://linux-hardware.org/?probe=500f9c8851) | Dec 01, 2021 |
| ASUSTek  | PRIME B365M-A               | [c7cbb50843](https://linux-hardware.org/?probe=c7cbb50843) | Nov 30, 2021 |
| Chuwi    | LarkBox Pro                 | [4af62a6057](https://linux-hardware.org/?probe=4af62a6057) | Nov 29, 2021 |
| Biostar  | TH55XE                      | [9e420cc495](https://linux-hardware.org/?probe=9e420cc495) | Nov 28, 2021 |
| MSI      | H81M-P33                    | [8812103632](https://linux-hardware.org/?probe=8812103632) | Nov 28, 2021 |
| HP       | 1497                        | [6f042fb99c](https://linux-hardware.org/?probe=6f042fb99c) | Nov 28, 2021 |
| Acer     | Aspire X3990                | [5559b2d988](https://linux-hardware.org/?probe=5559b2d988) | Nov 27, 2021 |
| HP       | 1825                        | [3648c360a9](https://linux-hardware.org/?probe=3648c360a9) | Nov 26, 2021 |
| Gigabyte | B450 I AORUS PRO WIFI-CF    | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Gigabyte | Z390 GAMING X-CF            | [34e71f1e27](https://linux-hardware.org/?probe=34e71f1e27) | Nov 25, 2021 |
| Gigabyte | B450M DS3H-CF               | [0fccfea38c](https://linux-hardware.org/?probe=0fccfea38c) | Nov 25, 2021 |
| ASUSTek  | P8H61-MX R2.0               | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| Biostar  | TA790GXE 128M               | [93ff10a9c2](https://linux-hardware.org/?probe=93ff10a9c2) | Nov 21, 2021 |
| Gigabyte | B85M-D3V-A                  | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| MSI      | X470 GAMING PLUS MAX        | [9e7d926319](https://linux-hardware.org/?probe=9e7d926319) | Nov 19, 2021 |
| HP       | 0AECh D                     | [c81bcc92ca](https://linux-hardware.org/?probe=c81bcc92ca) | Nov 19, 2021 |
| Gigabyte | EP43T-USB3                  | [a24bb09910](https://linux-hardware.org/?probe=a24bb09910) | Nov 15, 2021 |
| Gigabyte | H81M-H                      | [a895ed29e0](https://linux-hardware.org/?probe=a895ed29e0) | Nov 14, 2021 |
| ASRock   | X570 Extreme4               | [e49fdf2db4](https://linux-hardware.org/?probe=e49fdf2db4) | Nov 13, 2021 |
| MSI      | 970A-G43                    | [19714dd1a0](https://linux-hardware.org/?probe=19714dd1a0) | Nov 08, 2021 |
| Gigabyte | Z270X-Gaming 5              | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| ASRock   | P67 Extreme4                | [a70eb2d3f8](https://linux-hardware.org/?probe=a70eb2d3f8) | Oct 29, 2021 |
| ASRock   | P67 Extreme4                | [0a07f4c735](https://linux-hardware.org/?probe=0a07f4c735) | Oct 29, 2021 |
| MSI      | 2A9Ch                       | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| HP       | 158B                        | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| HP       | 339A                        | [d9c6208191](https://linux-hardware.org/?probe=d9c6208191) | Oct 16, 2021 |
| Dell     | 0M9KCM A02                  | [a925b0f3d1](https://linux-hardware.org/?probe=a925b0f3d1) | Oct 12, 2021 |
| Gigabyte | AB350-Gaming 3-CF           | [f6e75d0258](https://linux-hardware.org/?probe=f6e75d0258) | Oct 09, 2021 |
| MSI      | B460M PRO-VDH WIFI          | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASUSTek  | TUF GAMING B560M-PLUS       | [de0f051658](https://linux-hardware.org/?probe=de0f051658) | Oct 02, 2021 |
| Shuttle  | FS61                        | [b25047a516](https://linux-hardware.org/?probe=b25047a516) | Oct 01, 2021 |
| Apple    | Mac-F221BEC8                | [1754c64091](https://linux-hardware.org/?probe=1754c64091) | Sep 27, 2021 |
| ASUSTek  | P7H55-M                     | [3367bc011a](https://linux-hardware.org/?probe=3367bc011a) | Sep 25, 2021 |
| Dell     | 0Y5DDC A00                  | [df95ea94b8](https://linux-hardware.org/?probe=df95ea94b8) | Sep 25, 2021 |
| Dell     | 0Y5DDC A00                  | [10ee1abc07](https://linux-hardware.org/?probe=10ee1abc07) | Sep 25, 2021 |
| ASRock   | M3A790GXH/128M              | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| Intel    | X79 V1.x                    | [19223e911c](https://linux-hardware.org/?probe=19223e911c) | Sep 22, 2021 |
| ASUSTek  | M4N78-AM                    | [3d8e0efc00](https://linux-hardware.org/?probe=3d8e0efc00) | Sep 21, 2021 |
| ASRock   | A320M-HDV                   | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Intel    | H61                         | [0010dbcb5e](https://linux-hardware.org/?probe=0010dbcb5e) | Sep 10, 2021 |
| HP       | 8767 A                      | [7f022c67ac](https://linux-hardware.org/?probe=7f022c67ac) | Sep 09, 2021 |
| Gigabyte | B450M DS3H V2               | [633441bc2b](https://linux-hardware.org/?probe=633441bc2b) | Sep 05, 2021 |
| ASUSTek  | ROG STRIX Z590-F GAMING ... | [c9476d5d06](https://linux-hardware.org/?probe=c9476d5d06) | Sep 02, 2021 |
| Gigabyte | F2A55M-HD2                  | [0c05ab5b21](https://linux-hardware.org/?probe=0c05ab5b21) | Aug 30, 2021 |
| ASRock   | H81TM-ITX R2.0              | [4f04e7309e](https://linux-hardware.org/?probe=4f04e7309e) | Aug 30, 2021 |
| ASUSTek  | M5A78L-M LX/BR              | [d0ff1c6977](https://linux-hardware.org/?probe=d0ff1c6977) | Aug 25, 2021 |
| ASUSTek  | P6X58D-E                    | [db1ef28e92](https://linux-hardware.org/?probe=db1ef28e92) | Aug 20, 2021 |
| MSI      | X470 GAMING PLUS MAX        | [1176a287c7](https://linux-hardware.org/?probe=1176a287c7) | Aug 19, 2021 |
| ASUSTek  | TUF GAMING B450M-PRO II     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| Gigabyte | X570 I AORUS PRO WIFI       | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Gigabyte | H310M M.2 x.x               | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte | H310M M.2 x.x               | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| ASUSTek  | P5KPL-AM SE                 | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| ASRock   | B450 Pro4                   | [c5d0611f79](https://linux-hardware.org/?probe=c5d0611f79) | Jun 13, 2021 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
| ASUSTek  | ROG STRIX B450-I GAMING     | [a208e8a358](https://linux-hardware.org/?probe=a208e8a358) | May 01, 2021 |
| ASUSTek  | M5A99X EVO R2.0             | [f7d949f5a7](https://linux-hardware.org/?probe=f7d949f5a7) | Dec 23, 2020 |
| HP       | 8433 11                     | [691ef58a05](https://linux-hardware.org/?probe=691ef58a05) | Dec 09, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.11.0-40-generic    | 17       | 23.61%  |
| 5.11.0-41-generic    | 15       | 20.83%  |
| 5.11.0-27-generic    | 10       | 13.89%  |
| 5.11.0-37-generic    | 6        | 8.33%   |
| 5.11.0-25-generic    | 6        | 8.33%   |
| 5.11.0-38-generic    | 5        | 6.94%   |
| 5.8.0-50-generic     | 3        | 4.17%   |
| 5.11.0-36-generic    | 2        | 2.78%   |
| 5.11.0-34-generic    | 2        | 2.78%   |
| 5.8.0-63-generic     | 1        | 1.39%   |
| 5.8.0-55-generic     | 1        | 1.39%   |
| 5.4.0-58-generic     | 1        | 1.39%   |
| 5.4.0-56-generic     | 1        | 1.39%   |
| 5.15.1-xanmod1       | 1        | 1.39%   |
| 5.11.0-41-lowlatency | 1        | 1.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 60       | 88.24%  |
| 5.8.0   | 5        | 7.35%   |
| 5.4.0   | 2        | 2.94%   |
| 5.15.1  | 1        | 1.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 60       | 88.24%  |
| 5.8     | 5        | 7.35%   |
| 5.4     | 2        | 2.94%   |
| 5.15    | 1        | 1.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 68       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 63       | 91.3%   |
| Unknown  | 4        | 5.8%    |
| MATE     | 1        | 1.45%   |
| GNOME    | 1        | 1.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 68       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 57       | 83.82%  |
| LightDM | 8        | 11.76%  |
| TDM     | 3        | 4.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 34       | 50%     |
| de_DE | 10       | 14.71%  |
| es_ES | 7        | 10.29%  |
| ru_RU | 4        | 5.88%   |
| pt_BR | 3        | 4.41%   |
| en_GB | 2        | 2.94%   |
| zh_CN | 1        | 1.47%   |
| tr_TR | 1        | 1.47%   |
| it_IT | 1        | 1.47%   |
| fr_FR | 1        | 1.47%   |
| es_MX | 1        | 1.47%   |
| en_AU | 1        | 1.47%   |
| de_CH | 1        | 1.47%   |
| ca_ES | 1        | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 40       | 58.82%  |
| BIOS | 28       | 41.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 65       | 95.59%  |
| Btrfs | 3        | 4.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 60       | 88.24%  |
| GPT     | 5        | 7.35%   |
| MBR     | 3        | 4.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 94.12%  |
| Yes       | 4        | 5.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 82.35%  |
| Yes       | 12       | 17.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 16       | 23.53%  |
| Gigabyte Technology | 15       | 22.06%  |
| Hewlett-Packard     | 8        | 11.76%  |
| ASRock              | 8        | 11.76%  |
| MSI                 | 6        | 8.82%   |
| Dell                | 3        | 4.41%   |
| Pegatron            | 2        | 2.94%   |
| Intel               | 2        | 2.94%   |
| Biostar             | 2        | 2.94%   |
| Acer                | 2        | 2.94%   |
| Shuttle             | 1        | 1.47%   |
| Inventec            | 1        | 1.47%   |
| Chuwi               | 1        | 1.47%   |
| Apple               | 1        | 1.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Shuttle DS61                         | 1        | 1.47%   |
| Pegatron KJ379AA-ABA a6400f          | 1        | 1.47%   |
| Pegatron IPMH61P1                    | 1        | 1.47%   |
| MSI MS-7C83                          | 1        | 1.47%   |
| MSI MS-7B79                          | 1        | 1.47%   |
| MSI MS-7B46                          | 1        | 1.47%   |
| MSI MS-7817                          | 1        | 1.47%   |
| MSI MS-7693                          | 1        | 1.47%   |
| MSI Elite 7100 Microtower PC         | 1        | 1.47%   |
| Inventec D CLASS                     | 1        | 1.47%   |
| Intel X64                            | 1        | 1.47%   |
| Intel H61                            | 1        | 1.47%   |
| HP Z820 Workstation                  | 1        | 1.47%   |
| HP Z800 Workstation                  | 1        | 1.47%   |
| HP Pavilion Gaming Desktop TG01-1xxx | 1        | 1.47%   |
| HP Pavilion Desktop 590-p0xxx        | 1        | 1.47%   |
| HP ENVY TE01-0xxx                    | 1        | 1.47%   |
| HP EliteDesk 800 G1 DM               | 1        | 1.47%   |
| HP Compaq 6200 Pro MT PC             | 1        | 1.47%   |
| HP 339A                              | 1        | 1.47%   |
| Gigabyte Z390 GAMING X               | 1        | 1.47%   |
| Gigabyte Z270X-Gaming 5              | 1        | 1.47%   |
| Gigabyte X570 I AORUS PRO WIFI       | 1        | 1.47%   |
| Gigabyte X570 AORUS PRO WIFI         | 1        | 1.47%   |
| Gigabyte H81M-H                      | 1        | 1.47%   |
| Gigabyte H310M M.2 2.0               | 1        | 1.47%   |
| Gigabyte F2A55M-HD2                  | 1        | 1.47%   |
| Gigabyte EP43T-USB3                  | 1        | 1.47%   |
| Gigabyte B85M-DS3H-A                 | 1        | 1.47%   |
| Gigabyte B85M-D3V-A                  | 1        | 1.47%   |
| Gigabyte B450M DS3H V2               | 1        | 1.47%   |
| Gigabyte B450M DS3H                  | 1        | 1.47%   |
| Gigabyte B450 I AORUS PRO WIFI       | 1        | 1.47%   |
| Gigabyte AX370-Gaming                | 1        | 1.47%   |
| Gigabyte AB350-Gaming 3              | 1        | 1.47%   |
| Dell OptiPlex 9020M                  | 1        | 1.47%   |
| Dell OptiPlex 9010                   | 1        | 1.47%   |
| Dell OptiPlex 3040                   | 1        | 1.47%   |
| Chuwi LarkBox Pro                    | 1        | 1.47%   |
| Biostar TH55XE                       | 1        | 1.47%   |
| Biostar TA790GXE 128M                | 1        | 1.47%   |
| ASUS TUF GAMING B560M-PLUS           | 1        | 1.47%   |
| ASUS TUF GAMING B550M-PLUS           | 1        | 1.47%   |
| ASUS TUF GAMING B450M-PRO II         | 1        | 1.47%   |
| ASUS ROG STRIX Z590-F GAMING WIFI    | 1        | 1.47%   |
| ASUS ROG STRIX B450-I GAMING         | 1        | 1.47%   |
| ASUS PRIME B365M-A                   | 1        | 1.47%   |
| ASUS PRIME B250-PRO                  | 1        | 1.47%   |
| ASUS PRIME A320M-K                   | 1        | 1.47%   |
| ASUS P8H61-MX R2.0                   | 1        | 1.47%   |
| ASUS P7H55-M                         | 1        | 1.47%   |
| ASUS P6X58D-E                        | 1        | 1.47%   |
| ASUS P5KPL-AM SE                     | 1        | 1.47%   |
| ASUS M5A99X EVO R2.0                 | 1        | 1.47%   |
| ASUS M5A78L-M LX/BR                  | 1        | 1.47%   |
| ASUS M4N78-AM                        | 1        | 1.47%   |
| ASUS All Series                      | 1        | 1.47%   |
| ASRock Z590 Phantom Gaming 4/ac      | 1        | 1.47%   |
| ASRock X570 Extreme4                 | 1        | 1.47%   |
| ASRock P67 Extreme4                  | 1        | 1.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 3        | 4.41%   |
| ASUS TUF              | 3        | 4.41%   |
| ASUS PRIME            | 3        | 4.41%   |
| HP Pavilion           | 2        | 2.94%   |
| Gigabyte X570         | 2        | 2.94%   |
| Gigabyte B450M        | 2        | 2.94%   |
| ASUS ROG              | 2        | 2.94%   |
| Shuttle DS61          | 1        | 1.47%   |
| Pegatron KJ379AA-ABA  | 1        | 1.47%   |
| Pegatron IPMH61P1     | 1        | 1.47%   |
| MSI MS-7C83           | 1        | 1.47%   |
| MSI MS-7B79           | 1        | 1.47%   |
| MSI MS-7B46           | 1        | 1.47%   |
| MSI MS-7817           | 1        | 1.47%   |
| MSI MS-7693           | 1        | 1.47%   |
| MSI Elite             | 1        | 1.47%   |
| Inventec D            | 1        | 1.47%   |
| Intel X64             | 1        | 1.47%   |
| Intel H61             | 1        | 1.47%   |
| HP Z820               | 1        | 1.47%   |
| HP Z800               | 1        | 1.47%   |
| HP ENVY               | 1        | 1.47%   |
| HP EliteDesk          | 1        | 1.47%   |
| HP Compaq             | 1        | 1.47%   |
| HP 339A               | 1        | 1.47%   |
| Gigabyte Z390         | 1        | 1.47%   |
| Gigabyte Z270X-Gaming | 1        | 1.47%   |
| Gigabyte H81M-H       | 1        | 1.47%   |
| Gigabyte H310M        | 1        | 1.47%   |
| Gigabyte F2A55M-HD2   | 1        | 1.47%   |
| Gigabyte EP43T-USB3   | 1        | 1.47%   |
| Gigabyte B85M-DS3H-A  | 1        | 1.47%   |
| Gigabyte B85M-D3V-A   | 1        | 1.47%   |
| Gigabyte B450         | 1        | 1.47%   |
| Gigabyte AX370-Gaming | 1        | 1.47%   |
| Gigabyte AB350-Gaming | 1        | 1.47%   |
| Chuwi LarkBox         | 1        | 1.47%   |
| Biostar TH55XE        | 1        | 1.47%   |
| Biostar TA790GXE      | 1        | 1.47%   |
| ASUS P8H61-MX         | 1        | 1.47%   |
| ASUS P7H55-M          | 1        | 1.47%   |
| ASUS P6X58D-E         | 1        | 1.47%   |
| ASUS P5KPL-AM         | 1        | 1.47%   |
| ASUS M5A99X           | 1        | 1.47%   |
| ASUS M5A78L-M         | 1        | 1.47%   |
| ASUS M4N78-AM         | 1        | 1.47%   |
| ASUS All              | 1        | 1.47%   |
| ASRock Z590           | 1        | 1.47%   |
| ASRock X570           | 1        | 1.47%   |
| ASRock P67            | 1        | 1.47%   |
| ASRock M3A790GXH      | 1        | 1.47%   |
| ASRock H81TM-ITX      | 1        | 1.47%   |
| ASRock B450           | 1        | 1.47%   |
| ASRock AB350M         | 1        | 1.47%   |
| ASRock A320M-HDV      | 1        | 1.47%   |
| Apple MacPro5         | 1        | 1.47%   |
| Acer ConceptD         | 1        | 1.47%   |
| Acer Aspire           | 1        | 1.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 9        | 13.24%  |
| 2020 | 8        | 11.76%  |
| 2010 | 8        | 11.76%  |
| 2017 | 7        | 10.29%  |
| 2018 | 6        | 8.82%   |
| 2013 | 6        | 8.82%   |
| 2012 | 6        | 8.82%   |
| 2015 | 4        | 5.88%   |
| 2011 | 4        | 5.88%   |
| 2021 | 3        | 4.41%   |
| 2016 | 2        | 2.94%   |
| 2009 | 2        | 2.94%   |
| 2008 | 2        | 2.94%   |
| 2014 | 1        | 1.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 68       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 64       | 94.12%  |
| Enabled  | 4        | 5.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 68       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 21       | 30.88%  |
| 4.01-8.0    | 17       | 25%     |
| 32.01-64.0  | 16       | 23.53%  |
| 8.01-16.0   | 6        | 8.82%   |
| 3.01-4.0    | 5        | 7.35%   |
| 64.01-256.0 | 2        | 2.94%   |
| 1.01-2.0    | 1        | 1.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 29       | 40.85%  |
| 2.01-3.0   | 21       | 29.58%  |
| 3.01-4.0   | 11       | 15.49%  |
| 4.01-8.0   | 8        | 11.27%  |
| 32.01-64.0 | 1        | 1.41%   |
| 8.01-16.0  | 1        | 1.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 26       | 37.68%  |
| 1      | 23       | 33.33%  |
| 3      | 11       | 15.94%  |
| 4      | 7        | 10.14%  |
| 5      | 2        | 2.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 64.71%  |
| Yes       | 24       | 35.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 67       | 98.53%  |
| No        | 1        | 1.47%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 50%     |
| No        | 34       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 60.29%  |
| Yes       | 27       | 39.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Germany     | 9        | 13.04%  |
| USA         | 7        | 10.14%  |
| UK          | 4        | 5.8%    |
| Russia      | 4        | 5.8%    |
| Mexico      | 4        | 5.8%    |
| Brazil      | 4        | 5.8%    |
| Indonesia   | 3        | 4.35%   |
| Canada      | 3        | 4.35%   |
| Argentina   | 3        | 4.35%   |
| Turkey      | 2        | 2.9%    |
| Spain       | 2        | 2.9%    |
| Finland     | 2        | 2.9%    |
| Austria     | 2        | 2.9%    |
| Vietnam     | 1        | 1.45%   |
| Ukraine     | 1        | 1.45%   |
| Sri Lanka   | 1        | 1.45%   |
| Poland      | 1        | 1.45%   |
| Netherlands | 1        | 1.45%   |
| Kenya       | 1        | 1.45%   |
| Italy       | 1        | 1.45%   |
| Greece      | 1        | 1.45%   |
| France      | 1        | 1.45%   |
| Estonia     | 1        | 1.45%   |
| Denmark     | 1        | 1.45%   |
| Czechia     | 1        | 1.45%   |
| Costa Rica  | 1        | 1.45%   |
| Colombia    | 1        | 1.45%   |
| China       | 1        | 1.45%   |
| Chile       | 1        | 1.45%   |
| Belgium     | 1        | 1.45%   |
| Belarus     | 1        | 1.45%   |
| Australia   | 1        | 1.45%   |
| Albania     | 1        | 1.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Vienna                    | 2        | 2.86%   |
| Znojmo                    | 1        | 1.43%   |
| Xicheng District          | 1        | 1.43%   |
| Wriezen                   | 1        | 1.43%   |
| Wigan                     | 1        | 1.43%   |
| Wattala                   | 1        | 1.43%   |
| VitÃ³ria                | 1        | 1.43%   |
| Villahermosa              | 1        | 1.43%   |
| Vantaa                    | 1        | 1.43%   |
| Vancouver                 | 1        | 1.43%   |
| Ullastrell                | 1        | 1.43%   |
| Tucson                    | 1        | 1.43%   |
| Tolyatti                  | 1        | 1.43%   |
| Toluca                    | 1        | 1.43%   |
| Tallinn                   | 1        | 1.43%   |
| Sukabumi                  | 1        | 1.43%   |
| Staropyshminsk            | 1        | 1.43%   |
| Sparti                    | 1        | 1.43%   |
| Simferopol                | 1        | 1.43%   |
| Saskatoon                 | 1        | 1.43%   |
| Sao Paulo                 | 1        | 1.43%   |
| Santiago                  | 1        | 1.43%   |
| San JosÃ©               | 1        | 1.43%   |
| Rosario                   | 1        | 1.43%   |
| Roermond                  | 1        | 1.43%   |
| Rio de Janeiro            | 1        | 1.43%   |
| Riesweiler                | 1        | 1.43%   |
| Rheinberg                 | 1        | 1.43%   |
| Providence Forge          | 1        | 1.43%   |
| Potsdam                   | 1        | 1.43%   |
| Pleiku                    | 1        | 1.43%   |
| Paris                     | 1        | 1.43%   |
| Pargolovo Tretye          | 1        | 1.43%   |
| Oldenburg                 | 1        | 1.43%   |
| Nairobi                   | 1        | 1.43%   |
| Morelia                   | 1        | 1.43%   |
| Montreal                  | 1        | 1.43%   |
| Minsk                     | 1        | 1.43%   |
| Milan                     | 1        | 1.43%   |
| Mexico City               | 1        | 1.43%   |
| Medan                     | 1        | 1.43%   |
| Landshut                  | 1        | 1.43%   |
| Krakow                    | 1        | 1.43%   |
| Klaukkala                 | 1        | 1.43%   |
| Kediri                    | 1        | 1.43%   |
| Kazanâ€™             | 1        | 1.43%   |
| Kamenz                    | 1        | 1.43%   |
| KamÃ«z                  | 1        | 1.43%   |
| Izmir                     | 1        | 1.43%   |
| Itanhem                   | 1        | 1.43%   |
| Istanbul                  | 1        | 1.43%   |
| Islington                 | 1        | 1.43%   |
| Granollers                | 1        | 1.43%   |
| Fredersdorf               | 1        | 1.43%   |
| Fort Lauderdale           | 1        | 1.43%   |
| Espelkamp                 | 1        | 1.43%   |
| East Malvern              | 1        | 1.43%   |
| Copenhagen                | 1        | 1.43%   |
| ConcepciÃ³n del Uruguay | 1        | 1.43%   |
| Cocoa                     | 1        | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 26       | 35     | 21.67%  |
| Samsung Electronics       | 18       | 27     | 15%     |
| Seagate                   | 17       | 21     | 14.17%  |
| SanDisk                   | 10       | 11     | 8.33%   |
| Kingston                  | 10       | 13     | 8.33%   |
| Crucial                   | 7        | 10     | 5.83%   |
| OCZ                       | 3        | 3      | 2.5%    |
| Hitachi                   | 3        | 3      | 2.5%    |
| Unknown                   | 2        | 2      | 1.67%   |
| Toshiba                   | 2        | 2      | 1.67%   |
| Phison                    | 2        | 3      | 1.67%   |
| Patriot                   | 2        | 2      | 1.67%   |
| Intel                     | 2        | 2      | 1.67%   |
| USB3.1                    | 1        | 1      | 0.83%   |
| Transcend                 | 1        | 1      | 0.83%   |
| Team                      | 1        | 1      | 0.83%   |
| SK Hynix                  | 1        | 1      | 0.83%   |
| OCZ-VERTEX2               | 1        | 1      | 0.83%   |
| Micron/Crucial Technology | 1        | 2      | 0.83%   |
| Micron Technology         | 1        | 1      | 0.83%   |
| LITEON                    | 1        | 1      | 0.83%   |
| Kingmax                   | 1        | 1      | 0.83%   |
| Intenso                   | 1        | 1      | 0.83%   |
| HGST                      | 1        | 1      | 0.83%   |
| Gigabyte Technology       | 1        | 1      | 0.83%   |
| GALAX                     | 1        | 1      | 0.83%   |
| China                     | 1        | 1      | 0.83%   |
| Apacer                    | 1        | 1      | 0.83%   |
| A-DATA Technology         | 1        | 1      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB       | 5        | 3.6%    |
| Kingston SA400S37240G 240GB SSD    | 4        | 2.88%   |
| Samsung NVMe SSD Drive 1TB         | 3        | 2.16%   |
| Kingston SA400S37480G 480GB SSD    | 3        | 2.16%   |
| WDC WD5000AAKX-003CA0 500GB        | 2        | 1.44%   |
| WDC WD10EZEX-60WN4A0 1TB           | 2        | 1.44%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 1.44%   |
| Seagate ST250DM000-1BD141 250GB    | 2        | 1.44%   |
| Sandisk NVMe SSD Drive 500GB       | 2        | 1.44%   |
| Samsung SSD 850 EVO 250GB          | 2        | 1.44%   |
| Intel NVMe SSD Drive 512GB         | 2        | 1.44%   |
| Crucial CT240BX500SSD1 240GB       | 2        | 1.44%   |
| Crucial CT240BX200SSD1 240GB       | 2        | 1.44%   |
| WDC WDS500G2B0A 500GB SSD          | 1        | 0.72%   |
| WDC WD6401AALS-00J7B0 640GB        | 1        | 0.72%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 1        | 0.72%   |
| WDC WD5000AAKX-603CA0 500GB        | 1        | 0.72%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 0.72%   |
| WDC WD5000AAKX-001CA0 500GB        | 1        | 0.72%   |
| WDC WD50 00LUCT-61C26Y0 500GB      | 1        | 0.72%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1        | 0.72%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1        | 0.72%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 0.72%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1        | 0.72%   |
| WDC WD2500AAKS-00B3A0 250GB        | 1        | 0.72%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 0.72%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 0.72%   |
| WDC WD20EARS-00MVWB0 2TB           | 1        | 0.72%   |
| WDC WD15EARX-00PASB0 1TB           | 1        | 0.72%   |
| WDC WD10EZRX-00L4HB0 1TB           | 1        | 0.72%   |
| WDC WD10EZRX-00A8LB0 1TB           | 1        | 0.72%   |
| WDC WD10EZEX-75ZF5A0 1TB           | 1        | 0.72%   |
| WDC WD10EZEX-22MFCA0 1TB           | 1        | 0.72%   |
| WDC WD10EZEX-00RKKA0 1TB           | 1        | 0.72%   |
| WDC WD10EZEX-00KUWA0 1TB           | 1        | 0.72%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 0.72%   |
| WDC WD10EURX-63UY4Y0 1TB           | 1        | 0.72%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 1        | 0.72%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB | 1        | 0.72%   |
| USB3.1 Disk 1TB                    | 1        | 0.72%   |
| Unknown SD/MMC/MS PRO 16GB         | 1        | 0.72%   |
| Unknown MMC Card  128GB            | 1        | 0.72%   |
| Transcend TS512GMTS430S 512GB SSD  | 1        | 0.72%   |
| Toshiba MQ01ABD100 1TB             | 1        | 0.72%   |
| Toshiba DT01ACA100 1TB             | 1        | 0.72%   |
| Team L5 LITE SSD 120GB             | 1        | 0.72%   |
| SK Hynix SH920 2.5 7MM 256GB SSD   | 1        | 0.72%   |
| Seagate ST940210AS 40GB            | 1        | 0.72%   |
| Seagate ST500DM002-1BC142 500GB    | 1        | 0.72%   |
| Seagate ST380815AS 80GB            | 1        | 0.72%   |
| Seagate ST3808110AS 80GB           | 1        | 0.72%   |
| Seagate ST3500312CS 500GB          | 1        | 0.72%   |
| Seagate ST3160815AS 160GB          | 1        | 0.72%   |
| Seagate ST3160813AS 160GB          | 1        | 0.72%   |
| Seagate ST3160023AS 160GB          | 1        | 0.72%   |
| Seagate ST3000DM001-9YN166 3TB     | 1        | 0.72%   |
| Seagate ST250DM001 HD253GJ 250GB   | 1        | 0.72%   |
| Seagate ST2000NM0033 2TB           | 1        | 0.72%   |
| Seagate ST2000DM008-2FR102 2TB     | 1        | 0.72%   |
| Seagate ST2000DL003-9VT166 2TB     | 1        | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 25       | 33     | 49.02%  |
| Seagate             | 16       | 19     | 31.37%  |
| Samsung Electronics | 3        | 3      | 5.88%   |
| Hitachi             | 3        | 3      | 5.88%   |
| Toshiba             | 2        | 2      | 3.92%   |
| Unknown             | 1        | 1      | 1.96%   |
| HGST                | 1        | 1      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 11     | 17.39%  |
| Kingston            | 8        | 10     | 17.39%  |
| Crucial             | 7        | 10     | 15.22%  |
| SanDisk             | 6        | 6      | 13.04%  |
| OCZ                 | 3        | 3      | 6.52%   |
| Patriot             | 2        | 2      | 4.35%   |
| WDC                 | 1        | 1      | 2.17%   |
| Transcend           | 1        | 1      | 2.17%   |
| Team                | 1        | 1      | 2.17%   |
| SK Hynix            | 1        | 1      | 2.17%   |
| OCZ-VERTEX2         | 1        | 1      | 2.17%   |
| LITEON              | 1        | 1      | 2.17%   |
| Kingmax             | 1        | 1      | 2.17%   |
| Intenso             | 1        | 1      | 2.17%   |
| GALAX               | 1        | 1      | 2.17%   |
| China               | 1        | 1      | 2.17%   |
| Apacer              | 1        | 1      | 2.17%   |
| A-DATA Technology   | 1        | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 42       | 62     | 40%     |
| SSD     | 38       | 54     | 36.19%  |
| NVMe    | 22       | 32     | 20.95%  |
| Unknown | 2        | 2      | 1.9%    |
| MMC     | 1        | 1      | 0.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 60       | 112    | 68.97%  |
| NVMe | 22       | 32     | 25.29%  |
| SAS  | 4        | 6      | 4.6%    |
| MMC  | 1        | 1      | 1.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 50       | 74     | 58.82%  |
| 0.51-1.0   | 26       | 32     | 30.59%  |
| 1.01-2.0   | 5        | 6      | 5.88%   |
| 3.01-4.0   | 2        | 2      | 2.35%   |
| 2.01-3.0   | 2        | 2      | 2.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 18       | 26.47%  |
| 101-250        | 18       | 26.47%  |
| 501-1000       | 9        | 13.24%  |
| 21-50          | 7        | 10.29%  |
| More than 3000 | 4        | 5.88%   |
| 2001-3000      | 4        | 5.88%   |
| 1001-2000      | 4        | 5.88%   |
| 51-100         | 3        | 4.41%   |
| 1-20           | 1        | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 34       | 48.57%  |
| 21-50     | 11       | 15.71%  |
| 51-100    | 9        | 12.86%  |
| 101-250   | 5        | 7.14%   |
| 251-500   | 4        | 5.71%   |
| 501-1000  | 3        | 4.29%   |
| 2001-3000 | 2        | 2.86%   |
| 1001-2000 | 2        | 2.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 12.5%   |
| WDC WD3200AAJS-56B4A0 320GB       | 1        | 1      | 12.5%   |
| WDC WD10EZEX-00KUWA0 1TB          | 1        | 1      | 12.5%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 1      | 12.5%   |
| Seagate ST3160813AS 160GB         | 1        | 1      | 12.5%   |
| Samsung Electronics HD160JJ 160GB | 1        | 1      | 12.5%   |
| Hitachi HTS542525K9SA00 250GB     | 1        | 1      | 12.5%   |
| Crucial CT256M550SSD1 256GB       | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 50%     |
| Seagate             | 1        | 1      | 12.5%   |
| Samsung Electronics | 1        | 1      | 12.5%   |
| Hitachi             | 1        | 1      | 12.5%   |
| Crucial             | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 57.14%  |
| Seagate             | 1        | 1      | 14.29%  |
| Samsung Electronics | 1        | 1      | 14.29%  |
| Hitachi             | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 7      | 83.33%  |
| SSD  | 1        | 1      | 16.67%  |

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
| Detected | 61       | 130    | 83.56%  |
| Works    | 7        | 13     | 9.59%   |
| Malfunc  | 5        | 8      | 6.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 43       | 43.43%  |
| AMD                         | 23       | 23.23%  |
| Samsung Electronics         | 10       | 10.1%   |
| Sandisk                     | 6        | 6.06%   |
| Phison Electronics          | 2        | 2.02%   |
| Marvell Technology Group    | 2        | 2.02%   |
| Kingston Technology Company | 2        | 2.02%   |
| JMicron Technology          | 2        | 2.02%   |
| ASMedia Technology          | 2        | 2.02%   |
| VIA Technologies            | 1        | 1.01%   |
| Seagate Technology          | 1        | 1.01%   |
| Nvidia                      | 1        | 1.01%   |
| Micron/Crucial Technology   | 1        | 1.01%   |
| Micron Technology           | 1        | 1.01%   |
| LSI Logic / Symbios Logic   | 1        | 1.01%   |
| Broadcom / LSI              | 1        | 1.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 11.02%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 6.3%    |
| Intel SATA Controller [RAID mode]                                                       | 6        | 4.72%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 4.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 3.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 3.15%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 2.36%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 2.36%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 2.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 2.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 2.36%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 2.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 2.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.36%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.36%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 2.36%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.57%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.57%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.57%   |
| JMicron JMB368 IDE controller                                                           | 2        | 1.57%   |
| Intel SSD 660P Series                                                                   | 2        | 1.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 1.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.57%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.57%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.57%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.57%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.79%   |
| Seagate FireCuda 510 SSD                                                                | 1        | 0.79%   |
| Sandisk WD Black NVMe SSD                                                               | 1        | 0.79%   |
| Sandisk Non-Volatile memory controller                                                  | 1        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.79%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.79%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.79%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.79%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 0.79%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.79%   |
| Micron Non-Volatile memory controller                                                   | 1        | 0.79%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.79%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1        | 0.79%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.79%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.79%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.79%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 0.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.79%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 0.79%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 0.79%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 0.79%   |
| AMD FCH IDE Controller                                                                  | 1        | 0.79%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 51       | 53.68%  |
| NVMe | 22       | 23.16%  |
| IDE  | 13       | 13.68%  |
| RAID | 7        | 7.37%   |
| SAS  | 1        | 1.05%   |
| SCSI | 1        | 1.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 43       | 63.24%  |
| AMD    | 25       | 36.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor             | 4        | 5.88%   |
| AMD Ryzen 5 3600 6-Core Processor              | 3        | 4.41%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 2        | 2.94%   |
| Intel Core i3 CPU 530 @ 2.93GHz                | 2        | 2.94%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 2        | 2.94%   |
| Intel Xeon CPU X5660 @ 2.80GHz                 | 1        | 1.47%   |
| Intel Xeon CPU E5520 @ 2.27GHz                 | 1        | 1.47%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz             | 1        | 1.47%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz             | 1        | 1.47%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz         | 1        | 1.47%   |
| Intel Pentium CPU G620 @ 2.60GHz               | 1        | 1.47%   |
| Intel Pentium CPU G3260 @ 3.30GHz              | 1        | 1.47%   |
| Intel Core i7-9700 CPU @ 3.00GHz               | 1        | 1.47%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 1.47%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 1.47%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 1.47%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 1.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 1.47%   |
| Intel Core i7-4785T CPU @ 2.20GHz              | 1        | 1.47%   |
| Intel Core i7-10700F CPU @ 2.90GHz             | 1        | 1.47%   |
| Intel Core i7 CPU 950 @ 3.07GHz                | 1        | 1.47%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 1.47%   |
| Intel Core i5-9400F CPU @ 2.90GHz              | 1        | 1.47%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 1        | 1.47%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1        | 1.47%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 1        | 1.47%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.47%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 1.47%   |
| Intel Core i5-3550 CPU @ 3.30GHz               | 1        | 1.47%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 1        | 1.47%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 1.47%   |
| Intel Core i5-2320 CPU @ 3.00GHz               | 1        | 1.47%   |
| Intel Core i5-10600K CPU @ 4.10GHz             | 1        | 1.47%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1        | 1.47%   |
| Intel Core i5 CPU 750 @ 2.67GHz                | 1        | 1.47%   |
| Intel Core i3-6100T CPU @ 3.20GHz              | 1        | 1.47%   |
| Intel Core 2 Quad CPU Q9500 @ 2.83GHz          | 1        | 1.47%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz           | 1        | 1.47%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1        | 1.47%   |
| Intel Celeron G4930 CPU @ 3.20GHz              | 1        | 1.47%   |
| Intel Celeron CPU G530 @ 2.40GHz               | 1        | 1.47%   |
| Intel Celeron CPU G1610 @ 2.60GHz              | 1        | 1.47%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 1        | 1.47%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz         | 1        | 1.47%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 1.47%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 1.47%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 1        | 1.47%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1        | 1.47%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 1.47%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1        | 1.47%   |
| AMD Phenom II X4 925 Processor                 | 1        | 1.47%   |
| AMD Phenom 9850 Quad-Core Processor            | 1        | 1.47%   |
| AMD G-T48E Processor                           | 1        | 1.47%   |
| AMD FX-8350 Eight-Core Processor               | 1        | 1.47%   |
| AMD FX-8320 Eight-Core Processor               | 1        | 1.47%   |
| AMD FX-6100 Six-Core Processor                 | 1        | 1.47%   |
| AMD Athlon II X4 620 Processor                 | 1        | 1.47%   |
| AMD A6-9500E RADEON R5, 6 COMPUTE CORES 2C+4G  | 1        | 1.47%   |
| AMD A4-4000 APU with Radeon HD Graphics        | 1        | 1.47%   |
| AMD A10-9700 RADEON R7, 10 COMPUTE CORES 4C+6G | 1        | 1.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 14       | 20.59%  |
| Intel Core i7      | 9        | 13.24%  |
| AMD Ryzen 7        | 7        | 10.29%  |
| Intel Core i3      | 5        | 7.35%   |
| AMD Ryzen 5        | 5        | 7.35%   |
| Intel Xeon         | 4        | 5.88%   |
| Intel Celeron      | 4        | 5.88%   |
| AMD FX             | 3        | 4.41%   |
| Other              | 2        | 2.94%   |
| Intel Pentium      | 2        | 2.94%   |
| AMD Ryzen 9        | 2        | 2.94%   |
| Intel Pentium Dual | 1        | 1.47%   |
| Intel Core 2 Quad  | 1        | 1.47%   |
| Intel Core 2 Duo   | 1        | 1.47%   |
| AMD Ryzen 3        | 1        | 1.47%   |
| AMD Phenom II X4   | 1        | 1.47%   |
| AMD Phenom         | 1        | 1.47%   |
| AMD G              | 1        | 1.47%   |
| AMD Athlon II X4   | 1        | 1.47%   |
| AMD A6             | 1        | 1.47%   |
| AMD A4             | 1        | 1.47%   |
| AMD A10            | 1        | 1.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 23       | 33.82%  |
| 2      | 14       | 20.59%  |
| 8      | 13       | 19.12%  |
| 6      | 11       | 16.18%  |
| 12     | 4        | 5.88%   |
| 1      | 2        | 2.94%   |
| 3      | 1        | 1.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 65       | 95.59%  |
| 2      | 3        | 4.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 41       | 60.29%  |
| 1      | 27       | 39.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 68       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 8        | 11.59%  |
| 0x206a7    | 6        | 8.7%    |
| 0x08701021 | 6        | 8.7%    |
| 0x0800820d | 4        | 5.8%    |
| Unknown    | 4        | 5.8%    |
| 0x906ea    | 3        | 4.35%   |
| 0xa0671    | 2        | 2.9%    |
| 0xa0655    | 2        | 2.9%    |
| 0x906e9    | 2        | 2.9%    |
| 0x306a9    | 2        | 2.9%    |
| 0x206d7    | 2        | 2.9%    |
| 0x20652    | 2        | 2.9%    |
| 0x106a5    | 2        | 2.9%    |
| 0x08701013 | 2        | 2.9%    |
| 0x0600611a | 2        | 2.9%    |
| 0x06000852 | 2        | 2.9%    |
| 0xa0653    | 1        | 1.45%   |
| 0x906ed    | 1        | 1.45%   |
| 0x906eb    | 1        | 1.45%   |
| 0x706a8    | 1        | 1.45%   |
| 0x6fd      | 1        | 1.45%   |
| 0x6fb      | 1        | 1.45%   |
| 0x506e3    | 1        | 1.45%   |
| 0x206c2    | 1        | 1.45%   |
| 0x106e5    | 1        | 1.45%   |
| 0x1067a    | 1        | 1.45%   |
| 0x0a201016 | 1        | 1.45%   |
| 0x08101007 | 1        | 1.45%   |
| 0x0800111c | 1        | 1.45%   |
| 0x06001119 | 1        | 1.45%   |
| 0x0600063e | 1        | 1.45%   |
| 0x05000119 | 1        | 1.45%   |
| 0x010000db | 1        | 1.45%   |
| 0x01000095 | 1        | 1.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 9        | 13.24%  |
| Zen 2         | 8        | 11.76%  |
| KabyLake      | 8        | 11.76%  |
| Haswell       | 8        | 11.76%  |
| Zen+          | 4        | 5.88%   |
| Westmere      | 3        | 4.41%   |
| Piledriver    | 3        | 4.41%   |
| Nehalem       | 3        | 4.41%   |
| K10           | 3        | 4.41%   |
| CometLake     | 3        | 4.41%   |
| Zen           | 2        | 2.94%   |
| IvyBridge     | 2        | 2.94%   |
| Icelake       | 2        | 2.94%   |
| Excavator     | 2        | 2.94%   |
| Core          | 2        | 2.94%   |
| Zen 3         | 1        | 1.47%   |
| Skylake       | 1        | 1.47%   |
| Penryn        | 1        | 1.47%   |
| Goldmont plus | 1        | 1.47%   |
| Bulldozer     | 1        | 1.47%   |
| Bobcat        | 1        | 1.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| AMD              | 28       | 37.84%  |
| Nvidia           | 26       | 35.14%  |
| Intel            | 18       | 24.32%  |
| Conexant Systems | 1        | 1.35%   |
| ATI Technologies | 1        | 1.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 9.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 6.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 5.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 2.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.67%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 2.67%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 2.67%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 2.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.67%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 2.67%   |
| AMD RS780D [Radeon HD 3300]                                                 | 2        | 2.67%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 2.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 2.67%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 2        | 2.67%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.33%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.33%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.33%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.33%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 1.33%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.33%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.33%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.33%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.33%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.33%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.33%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 1.33%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.33%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 1.33%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.33%   |
| Intel HD Graphics 630                                                       | 1        | 1.33%   |
| Intel HD Graphics 530                                                       | 1        | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.33%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.33%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.33%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.33%   |
| Conexant Systems Conexant Display controller                                | 1        | 1.33%   |
| ATI Technologies Wani [Radeon R5/R6/R7 Graphics]                            | 1        | 1.33%   |
| AMD Wrestler [Radeon HD 6250]                                               | 1        | 1.33%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.33%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 1.33%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 1.33%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 1        | 1.33%   |
| AMD RV770 [Radeon HD 4850]                                                  | 1        | 1.33%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 1        | 1.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.33%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 1.33%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                            | 1        | 1.33%   |
| AMD Cypress LE [Radeon HD 5830]                                             | 1        | 1.33%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| 1 x Nvidia                     | 24       | 35.29%  |
| 1 x AMD                        | 24       | 35.29%  |
| 1 x Intel                      | 15       | 22.06%  |
| 2 x AMD + 1 x Conexant Systems | 1        | 1.47%   |
| 2 x AMD                        | 1        | 1.47%   |
| Intel + Nvidia                 | 1        | 1.47%   |
| Intel + AMD                    | 1        | 1.47%   |
| AMD + Nvidia                   | 1        | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 56       | 80%     |
| Proprietary | 13       | 18.57%  |
| Unknown     | 1        | 1.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 27.54%  |
| 1.01-2.0   | 13       | 18.84%  |
| 7.01-8.0   | 11       | 15.94%  |
| 3.01-4.0   | 10       | 14.49%  |
| 0.51-1.0   | 6        | 8.7%    |
| 0.01-0.5   | 4        | 5.8%    |
| 5.01-6.0   | 3        | 4.35%   |
| 8.01-16.0  | 2        | 2.9%    |
| 2.01-3.0   | 1        | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 17.33%  |
| Hewlett-Packard      | 11       | 14.67%  |
| Goldstar             | 8        | 10.67%  |
| BenQ                 | 6        | 8%      |
| Acer                 | 6        | 8%      |
| Dell                 | 5        | 6.67%   |
| AOC                  | 4        | 5.33%   |
| Ancor Communications | 4        | 5.33%   |
| Vizio                | 2        | 2.67%   |
| ViewSonic            | 2        | 2.67%   |
| LG Electronics       | 2        | 2.67%   |
| TBD                  | 1        | 1.33%   |
| SKY                  | 1        | 1.33%   |
| Philips              | 1        | 1.33%   |
| MSI                  | 1        | 1.33%   |
| Lenovo Group Limited | 1        | 1.33%   |
| Lenovo               | 1        | 1.33%   |
| HOP                  | 1        | 1.33%   |
| Grundig              | 1        | 1.33%   |
| Denver               | 1        | 1.33%   |
| AUS                  | 1        | 1.33%   |
| ASUSTek Computer     | 1        | 1.33%   |
| Unknown              | 1        | 1.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| AOC 2369 AOC2369 1920x1080 509x286mm 23.0-inch                         | 2        | 2.47%   |
| Vizio M260VA VIZ0067 1360x768 575x323mm 26.0-inch                      | 1        | 1.23%   |
| Vizio E321VL VIZ0083 1920x1080 700x400mm 31.7-inch                     | 1        | 1.23%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch          | 1        | 1.23%   |
| ViewSonic VA2055 Series VSC3C31 1920x1080 435x239mm 19.5-inch          | 1        | 1.23%   |
| TBD HDMI TBD3148 1600x900 344x193mm 15.5-inch                          | 1        | 1.23%   |
| SKY TV Monitor SKY0001 1920x1080 885x498mm 40.0-inch                   | 1        | 1.23%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch      | 1        | 1.23%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 610x350mm 27.7-inch      | 1        | 1.23%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch      | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch   | 1        | 1.23%   |
| Samsung Electronics S27H85x SAM0E0E 2560x1440 597x336mm 27.0-inch      | 1        | 1.23%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 530x300mm 24.0-inch      | 1        | 1.23%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 1        | 1.23%   |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch      | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SAM705B 1920x1080 1210x680mm 54.6-inch | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1        | 1.23%   |
| Samsung Electronics LCD Monitor S24F350 5760x1080                      | 1        | 1.23%   |
| Samsung Electronics LCD Monitor S24F350                                | 1        | 1.23%   |
| Samsung Electronics LCD Monitor C24F390 1920x1080                      | 1        | 1.23%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch     | 1        | 1.23%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch     | 1        | 1.23%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch                | 1        | 1.23%   |
| MSI Optix G27C2 MSI1462 1920x1080 600x340mm 27.2-inch                  | 1        | 1.23%   |
| LG Electronics LCD Monitor LG IPS FULLHD                               | 1        | 1.23%   |
| LG Electronics LCD Monitor 25UM58G 2560x1080                           | 1        | 1.23%   |
| Lenovo LEN LS1922wA LEN0A14 1366x768 410x230mm 18.5-inch               | 1        | 1.23%   |
| Lenovo Group Limited LCD Monitor LEN D32q-20B 4480x1440                | 1        | 1.23%   |
| HOP DVI HOP2700 1920x1080 597x336mm 27.0-inch                          | 1        | 1.23%   |
| Hewlett-Packard P204v HPN3634 1600x900 432x240mm 19.5-inch             | 1        | 1.23%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 546x352mm 25.6-inch          | 1        | 1.23%   |
| Hewlett-Packard LE2002x HWP2964 1600x900 443x249mm 20.0-inch           | 1        | 1.23%   |
| Hewlett-Packard LCD Monitor LA2306 4480x1440                           | 1        | 1.23%   |
| Hewlett-Packard E243m HPN3466 1920x1080 527x296mm 23.8-inch            | 1        | 1.23%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch             | 1        | 1.23%   |
| Hewlett-Packard Compaq WF1907 HWP26A4 1440x900 408x255mm 18.9-inch     | 1        | 1.23%   |
| Hewlett-Packard 27fw HPN354B 1920x1080 598x336mm 27.0-inch             | 1        | 1.23%   |
| Hewlett-Packard 27f HPN354C 1920x1080 598x336mm 27.0-inch              | 1        | 1.23%   |
| Hewlett-Packard 24x HPN3635 1920x1080 527x297mm 23.8-inch              | 1        | 1.23%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch             | 1        | 1.23%   |
| Grundig UHD GRU4448 3840x2160 1210x680mm 54.6-inch                     | 1        | 1.23%   |
| Goldstar W2253 GSM56DC 1920x1080 480x270mm 21.7-inch                   | 1        | 1.23%   |
| Goldstar W2043 GSM4E9E 1600x900 443x249mm 20.0-inch                    | 1        | 1.23%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                    | 1        | 1.23%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch               | 1        | 1.23%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 1        | 1.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 1        | 1.23%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 1        | 1.23%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                 | 1        | 1.23%   |
| Denver CS2900 LHC2900 2560x1080 681x287mm 29.1-inch                    | 1        | 1.23%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                      | 1        | 1.23%   |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                      | 1        | 1.23%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                     | 1        | 1.23%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                      | 1        | 1.23%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                      | 1        | 1.23%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                      | 1        | 1.23%   |
| Dell 1707FPV DEL4021 1280x1024 338x270mm 17.0-inch                     | 1        | 1.23%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                     | 1        | 1.23%   |
| BenQ LCD Monitor ZOWIE XL LCD 3840x1080                                | 1        | 1.23%   |
| BenQ LCD Monitor PD2700U 3840x2160                                     | 1        | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 32       | 45.71%  |
| 3840x2160 (4K)     | 7        | 10%     |
| 2560x1440 (QHD)    | 5        | 7.14%   |
| 1600x900 (HD+)     | 4        | 5.71%   |
| Unknown            | 4        | 5.71%   |
| 3840x1080          | 3        | 4.29%   |
| 2560x1080          | 3        | 4.29%   |
| 1440x900 (WXGA+)   | 3        | 4.29%   |
| 1680x1050 (WSXGA+) | 2        | 2.86%   |
| 5760x1080          | 1        | 1.43%   |
| 5120x1440          | 1        | 1.43%   |
| 4480x1440          | 1        | 1.43%   |
| 3440x1440          | 1        | 1.43%   |
| 1920x1200 (WUXGA)  | 1        | 1.43%   |
| 1366x768 (WXGA)    | 1        | 1.43%   |
| 1280x1024 (SXGA)   | 1        | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 10       | 13.7%   |
| 21      | 10       | 13.7%   |
| Unknown | 10       | 13.7%   |
| 23      | 9        | 12.33%  |
| 24      | 6        | 8.22%   |
| 19      | 4        | 5.48%   |
| 54      | 3        | 4.11%   |
| 31      | 3        | 4.11%   |
| 49      | 2        | 2.74%   |
| 34      | 2        | 2.74%   |
| 20      | 2        | 2.74%   |
| 17      | 2        | 2.74%   |
| 72      | 1        | 1.37%   |
| 40      | 1        | 1.37%   |
| 33      | 1        | 1.37%   |
| 32      | 1        | 1.37%   |
| 29      | 1        | 1.37%   |
| 28      | 1        | 1.37%   |
| 25      | 1        | 1.37%   |
| 22      | 1        | 1.37%   |
| 18      | 1        | 1.37%   |
| 15      | 1        | 1.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 22       | 31.43%  |
| 401-500     | 17       | 24.29%  |
| Unknown     | 10       | 14.29%  |
| 601-700     | 7        | 10%     |
| 1001-1500   | 5        | 7.14%   |
| 701-800     | 4        | 5.71%   |
| 301-350     | 2        | 2.86%   |
| 801-900     | 1        | 1.43%   |
| 351-400     | 1        | 1.43%   |
| 1501-2000   | 1        | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 42       | 65.63%  |
| Unknown | 10       | 15.63%  |
| 21/9    | 4        | 6.25%   |
| 16/10   | 4        | 6.25%   |
| 32/9    | 2        | 3.13%   |
| 5/4     | 1        | 1.56%   |
| 3/2     | 1        | 1.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 30.56%  |
| 301-350        | 11       | 15.28%  |
| Unknown        | 10       | 13.89%  |
| 151-200        | 9        | 12.5%   |
| 351-500        | 7        | 9.72%   |
| More than 1000 | 4        | 5.56%   |
| 501-1000       | 3        | 4.17%   |
| 251-300        | 2        | 2.78%   |
| 141-150        | 2        | 2.78%   |
| 131-140        | 1        | 1.39%   |
| 101-110        | 1        | 1.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 40       | 57.97%  |
| 101-120 | 13       | 18.84%  |
| Unknown | 10       | 14.49%  |
| 1-50    | 4        | 5.8%    |
| 121-160 | 2        | 2.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 53       | 76.81%  |
| 2     | 11       | 15.94%  |
| 3     | 3        | 4.35%   |
| 0     | 2        | 2.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 45       | 46.39%  |
| Intel                    | 23       | 23.71%  |
| TP-Link                  | 7        | 7.22%   |
| Ralink Technology        | 4        | 4.12%   |
| Xiaomi                   | 3        | 3.09%   |
| Qualcomm Atheros         | 3        | 3.09%   |
| Broadcom                 | 3        | 3.09%   |
| Samsung Electronics      | 1        | 1.03%   |
| Ralink                   | 1        | 1.03%   |
| Nvidia                   | 1        | 1.03%   |
| NetGear                  | 1        | 1.03%   |
| Mercucys                 | 1        | 1.03%   |
| MediaTek                 | 1        | 1.03%   |
| Marvell Technology Group | 1        | 1.03%   |
| Edimax Technology        | 1        | 1.03%   |
| ASUSTek Computer         | 1        | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38       | 34.23%  |
| Intel I211 Gigabit Network Connection                             | 5        | 4.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 3.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.7%    |
| Ralink MT7601U Wireless Adapter                                   | 3        | 2.7%    |
| Intel 82574L Gigabit Network Connection                           | 3        | 2.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 1.8%    |
| TP-Link 802.11ac NIC                                              | 2        | 1.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.8%    |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.8%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.8%    |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.8%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 1.8%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                             | 1        | 0.9%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.9%    |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 0.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 0.9%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.9%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.9%    |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 0.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.9%    |
| Ralink RT5592 PCIe Wireless Network Adapter                       | 1        | 0.9%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.9%    |
| Nvidia MCP77 Ethernet                                             | 1        | 0.9%    |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]            | 1        | 0.9%    |
| Mercucys 802.11n NIC                                              | 1        | 0.9%    |
| MediaTek NOA N2                                                   | 1        | 0.9%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.9%    |
| Intel Wireless-AC 9260                                            | 1        | 0.9%    |
| Intel Wireless 7260                                               | 1        | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1        | 0.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1        | 0.9%    |
| Intel Ethernet Controller I225-V                                  | 1        | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.9%    |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.9%    |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 0.9%    |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.9%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 1        | 0.9%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.9%    |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]    | 1        | 0.9%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 10       | 27.03%  |
| Realtek Semiconductor | 8        | 21.62%  |
| TP-Link               | 7        | 18.92%  |
| Ralink Technology     | 4        | 10.81%  |
| Broadcom              | 2        | 5.41%   |
| Ralink                | 1        | 2.7%    |
| Qualcomm Atheros      | 1        | 2.7%    |
| NetGear               | 1        | 2.7%    |
| Mercucys              | 1        | 2.7%    |
| Edimax Technology     | 1        | 2.7%    |
| ASUSTek Computer      | 1        | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                | 3        | 8.11%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2        | 5.41%   |
| TP-Link 802.11ac NIC                                           | 2        | 5.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 5.41%   |
| Intel Wi-Fi 6 AX200                                            | 2        | 5.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2        | 5.41%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1        | 2.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 2.7%    |
| TP-Link 802.11ac WLAN Adapter                                  | 1        | 2.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 2.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 2.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 2.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 2.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 2.7%    |
| Realtek RTL8187 Wireless Adapter                               | 1        | 2.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 2.7%    |
| Ralink RT5592 PCIe Wireless Network Adapter                    | 1        | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 2.7%    |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]         | 1        | 2.7%    |
| Mercucys 802.11n NIC                                           | 1        | 2.7%    |
| Intel Wireless-AC 9260                                         | 1        | 2.7%    |
| Intel Wireless 7260                                            | 1        | 2.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 2.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 2.7%    |
| Intel Gemini Lake PCH CNVi WiFi                                | 1        | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 2.7%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 1        | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 1        | 2.7%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 2.7%    |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072] | 1        | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 43       | 59.72%  |
| Intel                    | 19       | 26.39%  |
| Xiaomi                   | 3        | 4.17%   |
| Qualcomm Atheros         | 2        | 2.78%   |
| Samsung Electronics      | 1        | 1.39%   |
| Nvidia                   | 1        | 1.39%   |
| MediaTek                 | 1        | 1.39%   |
| Marvell Technology Group | 1        | 1.39%   |
| Broadcom                 | 1        | 1.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38       | 51.35%  |
| Intel I211 Gigabit Network Connection                             | 5        | 6.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 5.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 4.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 4.05%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 4.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.7%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.7%    |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.35%   |
| Nvidia MCP77 Ethernet                                             | 1        | 1.35%   |
| MediaTek NOA N2                                                   | 1        | 1.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.35%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.35%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.35%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.35%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.35%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.35%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 67       | 66.34%  |
| WiFi     | 34       | 33.66%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 65       | 69.89%  |
| WiFi     | 28       | 30.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 45       | 66.18%  |
| 2     | 21       | 30.88%  |
| 3     | 1        | 1.47%   |
| 0     | 1        | 1.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 50       | 72.46%  |
| Yes  | 19       | 27.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 11       | 39.29%  |
| Intel                   | 10       | 35.71%  |
| Realtek Semiconductor   | 2        | 7.14%   |
| Apple                   | 2        | 7.14%   |
| Broadcom                | 1        | 3.57%   |
| Belkin Components       | 1        | 3.57%   |
| ASUSTek Computer        | 1        | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 39.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 10.71%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 7.14%   |
| Intel AX200 Bluetooth                               | 2        | 7.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.57%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.57%   |
| Intel Bluetooth wireless interface                  | 1        | 3.57%   |
| Intel Bluetooth Device                              | 1        | 3.57%   |
| Intel AX210 Bluetooth                               | 1        | 3.57%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1        | 3.57%   |
| Belkin Components Bluetooth Mini Dongle             | 1        | 3.57%   |
| ASUS Bluetooth Radio                                | 1        | 3.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 3.57%   |
| Apple Bluetooth USB Host Controller                 | 1        | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 41       | 33.61%  |
| AMD                                  | 35       | 28.69%  |
| Nvidia                               | 25       | 20.49%  |
| C-Media Electronics                  | 6        | 4.92%   |
| Creative Labs                        | 3        | 2.46%   |
| Logitech                             | 2        | 1.64%   |
| Generalplus Technology               | 2        | 1.64%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.82%   |
| Razer USA                            | 1        | 0.82%   |
| JMTek                                | 1        | 0.82%   |
| Focusrite-Novation                   | 1        | 0.82%   |
| Creative Technology                  | 1        | 0.82%   |
| BY EDIFIER                           | 1        | 0.82%   |
| ATI Technologies                     | 1        | 0.82%   |
| ASUSTek Computer                     | 1        | 0.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 9        | 6.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 7        | 4.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7        | 4.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 7        | 4.9%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6        | 4.2%    |
| Intel 200 Series PCH HD Audio                                                     | 5        | 3.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 2.8%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 4        | 2.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 2.1%    |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 2.1%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 2.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 2.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 3        | 2.1%    |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 1.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 1.4%    |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 1.4%    |
| Nvidia GM206 High Definition Audio Controller                                     | 2        | 1.4%    |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 1.4%    |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 1.4%    |
| Nvidia GA102 High Definition Audio Controller                                     | 2        | 1.4%    |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 1.4%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 1.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2        | 1.4%    |
| Generalplus Technology USB Audio Device                                           | 2        | 1.4%    |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                        | 2        | 1.4%    |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 2        | 1.4%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 2        | 1.4%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 2        | 1.4%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.4%    |
| Thesycon Systemsoftware & Consulting D10s                                         | 1        | 0.7%    |
| Razer USA Kraken Tournament Edition                                               | 1        | 0.7%    |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 0.7%    |
| Nvidia TU104 HD Audio Controller                                                  | 1        | 0.7%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 0.7%    |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 0.7%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 0.7%    |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 0.7%    |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.7%    |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 0.7%    |
| Nvidia GF116 High Definition Audio Controller                                     | 1        | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                                     | 1        | 0.7%    |
| Nvidia GF104 High Definition Audio Controller                                     | 1        | 0.7%    |
| Logitech G930                                                                     | 1        | 0.7%    |
| Logitech G733 Gaming Headset                                                      | 1        | 0.7%    |
| JMTek USB PnP Audio Device                                                        | 1        | 0.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1        | 0.7%    |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 0.7%    |
| Intel Comet Lake PCH cAVS                                                         | 1        | 0.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 0.7%    |
| Intel Audio device                                                                | 1        | 0.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 0.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 0.7%    |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                 | 1        | 0.7%    |
| Creative Technology Sound BlasterX Kratos S5                                      | 1        | 0.7%    |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]         | 1        | 0.7%    |
| C-Media Electronics Multimedia Headset [Gigaware by Ignition L.P.]                | 1        | 0.7%    |
| C-Media Electronics CM6631A Audio Processor                                       | 1        | 0.7%    |
| C-Media Electronics CM102-A+/102S+ Audio Controller                               | 1        | 0.7%    |
| C-Media Electronics Blue Snowball                                                 | 1        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 6        | 31.58%  |
| Samsung Electronics | 3        | 15.79%  |
| G.Skill             | 3        | 15.79%  |
| Corsair             | 2        | 10.53%  |
| Unknown             | 1        | 5.26%   |
| SK Hynix            | 1        | 5.26%   |
| Neo Forza           | 1        | 5.26%   |
| Nanya Technology    | 1        | 5.26%   |
| Crucial             | 1        | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1        | 5%      |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s      | 1        | 5%      |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s              | 1        | 5%      |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s  | 1        | 5%      |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s       | 1        | 5%      |
| Neo Forza RAM NMUD380D81-1600D 8GB DIMM DDR3 1333MT/s     | 1        | 5%      |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                   | 1        | 5%      |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 1        | 5%      |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s       | 1        | 5%      |
| Kingston RAM 99U5471-052.A 8GB DIMM DDR3 1333MT/s         | 1        | 5%      |
| Kingston RAM 99U5458-001.A00LF 2GB DIMM DDR3 1600MT/s     | 1        | 5%      |
| Kingston RAM 99U5403-159.A01LF 8GB DIMM DDR3 1333MT/s     | 1        | 5%      |
| Kingston RAM 9965516-069.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 5%      |
| Kingston RAM 9965516-003.A00LF 8GB DIMM 1333MT/s          | 1        | 5%      |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s    | 1        | 5%      |
| G.Skill RAM F3-1866C11-8GRSL 8GB SODIMM DDR3 1867MT/s     | 1        | 5%      |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1867MT/s      | 1        | 5%      |
| Crucial RAM BLS8G4D26BFSCK.8FD 8GB DIMM DDR4 2400MT/s     | 1        | 5%      |
| Corsair RAM CMK4GX4M1A2400C14 4GB DIMM DDR4 3007MT/s      | 1        | 5%      |
| Corsair RAM CMH32GX4M2D3600C18 16384MB DIMM DDR4 3600MT/s | 1        | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 7        | 50%     |
| DDR4 | 6        | 42.86%  |
| DDR2 | 1        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 13       | 92.86%  |
| SODIMM | 1        | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 46.67%  |
| 16384 | 3        | 20%     |
| 4096  | 3        | 20%     |
| 2048  | 2        | 13.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 4        | 22.22%  |
| 1600  | 3        | 16.67%  |
| 3600  | 2        | 11.11%  |
| 3200  | 2        | 11.11%  |
| 1867  | 2        | 11.11%  |
| 3007  | 1        | 5.56%   |
| 3000  | 1        | 5.56%   |
| 2666  | 1        | 5.56%   |
| 2133  | 1        | 5.56%   |
| 800   | 1        | 5.56%   |

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


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| HP LaserJet M101-M106    | 1        | 50%     |
| Brother HL-4140CN series | 1        | 50%     |

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
| Logitech                      | 8        | 42.11%  |
| Microdia                      | 3        | 15.79%  |
| Sunplus Innovation Technology | 2        | 10.53%  |
| Microsoft                     | 2        | 10.53%  |
| Z-Star Microelectronics       | 1        | 5.26%   |
| Generalplus Technology        | 1        | 5.26%   |
| Creative Technology           | 1        | 5.26%   |
| Apple                         | 1        | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 2        | 10.53%  |
| Z-Star Sirius USB2.0 Camera           | 1        | 5.26%   |
| Sunplus Integrated_Webcam_HD          | 1        | 5.26%   |
| Sunplus Aukey-PC-LM1E Camera          | 1        | 5.26%   |
| Microsoft Xbox NUI Camera             | 1        | 5.26%   |
| Microsoft LifeCam HD-3000             | 1        | 5.26%   |
| Microdia Webcam Vitade AF             | 1        | 5.26%   |
| Microdia Laptop_Integrated_Webcam_FHD | 1        | 5.26%   |
| Microdia JP001                        | 1        | 5.26%   |
| Logitech Webcam C310                  | 1        | 5.26%   |
| Logitech HD Webcam C615               | 1        | 5.26%   |
| Logitech HD Pro Webcam C920           | 1        | 5.26%   |
| Logitech C505 HD Webcam               | 1        | 5.26%   |
| Logitech BRIO 4K Stream Edition       | 1        | 5.26%   |
| Logitech B525 HD Webcam               | 1        | 5.26%   |
| Generalplus GENERAL WEBCAM            | 1        | 5.26%   |
| Creative Live! Cam Sync 1080p         | 1        | 5.26%   |
| Apple iPhone 5/5C/5S/6/SE             | 1        | 5.26%   |

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
| 0     | 63       | 91.3%   |
| 1     | 6        | 8.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 4        | 66.67%  |
| Graphics card            | 1        | 16.67%  |
| Communication controller | 1        | 16.67%  |

