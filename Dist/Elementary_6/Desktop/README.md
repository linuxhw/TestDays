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

Total: 80

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Inventec | D CLASS A02                 | [d00d37285b](https://linux-hardware.org/?probe=d00d37285b) | Apr 19, 2022 |
| Gigabyte | B450M DS3H-CF               | [0bc837ffef](https://linux-hardware.org/?probe=0bc837ffef) | Apr 06, 2022 |
| ASUSTek  | PRIME B250-PRO              | [be377c733e](https://linux-hardware.org/?probe=be377c733e) | Feb 14, 2022 |
| ASRock   | AB350M Pro4                 | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| ASRock   | Z590 Phantom Gaming 4/ac    | [b52ca671f7](https://linux-hardware.org/?probe=b52ca671f7) | Dec 24, 2021 |
| Pegatron | IPMH61P1                    | [1ba6ea2ee9](https://linux-hardware.org/?probe=1ba6ea2ee9) | Dec 14, 2021 |
| Acer     | ConceptD CM100-51A V:1.1    | [0b3e5753fc](https://linux-hardware.org/?probe=0b3e5753fc) | Dec 13, 2021 |
| ASUSTek  | TUF Gaming B560M-PLUS       | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
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
| ASUSTek  | TUF Gaming B560M-PLUS       | [de0f051658](https://linux-hardware.org/?probe=de0f051658) | Oct 02, 2021 |
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
| ASUSTek  | TUF Gaming B450M-PRO II     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| Gigabyte | X570 I AORUS PRO WIFI       | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Gigabyte | H310M M.2 x.x               | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte | H310M M.2 x.x               | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| ASUSTek  | P5KPL-AM SE                 | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| ASRock   | B450 Pro4                   | [c5d0611f79](https://linux-hardware.org/?probe=c5d0611f79) | Jun 13, 2021 |
| ASUSTek  | TUF Gaming B550M-PLUS       | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| ASUSTek  | TUF Gaming B550M-PLUS       | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
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
| 5.11.0-40-generic    | 16       | 22.54%  |
| 5.11.0-41-generic    | 15       | 21.13%  |
| 5.11.0-27-generic    | 10       | 14.08%  |
| 5.11.0-37-generic    | 6        | 8.45%   |
| 5.11.0-25-generic    | 6        | 8.45%   |
| 5.11.0-38-generic    | 5        | 7.04%   |
| 5.8.0-50-generic     | 3        | 4.23%   |
| 5.11.0-36-generic    | 2        | 2.82%   |
| 5.11.0-34-generic    | 2        | 2.82%   |
| 5.8.0-63-generic     | 1        | 1.41%   |
| 5.8.0-55-generic     | 1        | 1.41%   |
| 5.4.0-58-generic     | 1        | 1.41%   |
| 5.4.0-56-generic     | 1        | 1.41%   |
| 5.15.1-xanmod1       | 1        | 1.41%   |
| 5.11.0-41-lowlatency | 1        | 1.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 59       | 88.06%  |
| 5.8.0   | 5        | 7.46%   |
| 5.4.0   | 2        | 2.99%   |
| 5.15.1  | 1        | 1.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 59       | 88.06%  |
| 5.8     | 5        | 7.46%   |
| 5.4     | 2        | 2.99%   |
| 5.15    | 1        | 1.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 67       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 62       | 91.18%  |
| Unknown  | 4        | 5.88%   |
| MATE     | 1        | 1.47%   |
| GNOME    | 1        | 1.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 67       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 56       | 83.58%  |
| LightDM | 8        | 11.94%  |
| TDM     | 3        | 4.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 33       | 49.25%  |
| de_DE | 10       | 14.93%  |
| es_ES | 7        | 10.45%  |
| ru_RU | 4        | 5.97%   |
| pt_BR | 3        | 4.48%   |
| en_GB | 2        | 2.99%   |
| zh_CN | 1        | 1.49%   |
| tr_TR | 1        | 1.49%   |
| it_IT | 1        | 1.49%   |
| fr_FR | 1        | 1.49%   |
| es_MX | 1        | 1.49%   |
| en_AU | 1        | 1.49%   |
| de_CH | 1        | 1.49%   |
| ca_ES | 1        | 1.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 39       | 58.21%  |
| BIOS | 28       | 41.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 64       | 95.52%  |
| Btrfs | 3        | 4.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 59       | 88.06%  |
| GPT     | 5        | 7.46%   |
| MBR     | 3        | 4.48%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 94.03%  |
| Yes       | 4        | 5.97%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 82.09%  |
| Yes       | 12       | 17.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 16       | 23.88%  |
| Gigabyte Technology | 15       | 22.39%  |
| Hewlett-Packard     | 8        | 11.94%  |
| ASRock              | 8        | 11.94%  |
| MSI                 | 6        | 8.96%   |
| Dell                | 3        | 4.48%   |
| Pegatron            | 2        | 2.99%   |
| Intel               | 2        | 2.99%   |
| Biostar             | 2        | 2.99%   |
| Acer                | 2        | 2.99%   |
| Shuttle             | 1        | 1.49%   |
| Inventec            | 1        | 1.49%   |
| Apple               | 1        | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Shuttle DS61                         | 1        | 1.49%   |
| Pegatron KJ379AA-ABA a6400f          | 1        | 1.49%   |
| Pegatron IPMH61P1                    | 1        | 1.49%   |
| MSI MS-7C83                          | 1        | 1.49%   |
| MSI MS-7B79                          | 1        | 1.49%   |
| MSI MS-7B46                          | 1        | 1.49%   |
| MSI MS-7817                          | 1        | 1.49%   |
| MSI MS-7693                          | 1        | 1.49%   |
| MSI Elite 7100 Microtower PC         | 1        | 1.49%   |
| Inventec D CLASS                     | 1        | 1.49%   |
| Intel X64                            | 1        | 1.49%   |
| Intel H61                            | 1        | 1.49%   |
| HP Z820 Workstation                  | 1        | 1.49%   |
| HP Z800 Workstation                  | 1        | 1.49%   |
| HP Pavilion Gaming Desktop TG01-1xxx | 1        | 1.49%   |
| HP Pavilion Desktop 590-p0xxx        | 1        | 1.49%   |
| HP ENVY TE01-0xxx                    | 1        | 1.49%   |
| HP EliteDesk 800 G1 DM               | 1        | 1.49%   |
| HP Compaq 6200 Pro MT PC             | 1        | 1.49%   |
| HP 339A                              | 1        | 1.49%   |
| Gigabyte Z390 GAMING X               | 1        | 1.49%   |
| Gigabyte Z270X-Gaming 5              | 1        | 1.49%   |
| Gigabyte X570 I AORUS PRO WIFI       | 1        | 1.49%   |
| Gigabyte X570 AORUS PRO WIFI         | 1        | 1.49%   |
| Gigabyte H81M-H                      | 1        | 1.49%   |
| Gigabyte H310M M.2 2.0               | 1        | 1.49%   |
| Gigabyte F2A55M-HD2                  | 1        | 1.49%   |
| Gigabyte EP43T-USB3                  | 1        | 1.49%   |
| Gigabyte B85M-DS3H-A                 | 1        | 1.49%   |
| Gigabyte B85M-D3V-A                  | 1        | 1.49%   |
| Gigabyte B450M DS3H V2               | 1        | 1.49%   |
| Gigabyte B450M DS3H                  | 1        | 1.49%   |
| Gigabyte B450 I AORUS PRO WIFI       | 1        | 1.49%   |
| Gigabyte AX370-Gaming                | 1        | 1.49%   |
| Gigabyte AB350-Gaming 3              | 1        | 1.49%   |
| Dell OptiPlex 9020M                  | 1        | 1.49%   |
| Dell OptiPlex 9010                   | 1        | 1.49%   |
| Dell OptiPlex 3040                   | 1        | 1.49%   |
| Biostar TH55XE                       | 1        | 1.49%   |
| Biostar TA790GXE 128M                | 1        | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 3        | 4.48%   |
| ASUS TUF              | 3        | 4.48%   |
| ASUS PRIME            | 3        | 4.48%   |
| HP Pavilion           | 2        | 2.99%   |
| Gigabyte X570         | 2        | 2.99%   |
| Gigabyte B450M        | 2        | 2.99%   |
| ASUS ROG              | 2        | 2.99%   |
| Shuttle DS61          | 1        | 1.49%   |
| Pegatron KJ379AA-ABA  | 1        | 1.49%   |
| Pegatron IPMH61P1     | 1        | 1.49%   |
| MSI MS-7C83           | 1        | 1.49%   |
| MSI MS-7B79           | 1        | 1.49%   |
| MSI MS-7B46           | 1        | 1.49%   |
| MSI MS-7817           | 1        | 1.49%   |
| MSI MS-7693           | 1        | 1.49%   |
| MSI Elite             | 1        | 1.49%   |
| Inventec D            | 1        | 1.49%   |
| Intel X64             | 1        | 1.49%   |
| Intel H61             | 1        | 1.49%   |
| HP Z820               | 1        | 1.49%   |
| HP Z800               | 1        | 1.49%   |
| HP ENVY               | 1        | 1.49%   |
| HP EliteDesk          | 1        | 1.49%   |
| HP Compaq             | 1        | 1.49%   |
| HP 339A               | 1        | 1.49%   |
| Gigabyte Z390         | 1        | 1.49%   |
| Gigabyte Z270X-Gaming | 1        | 1.49%   |
| Gigabyte H81M-H       | 1        | 1.49%   |
| Gigabyte H310M        | 1        | 1.49%   |
| Gigabyte F2A55M-HD2   | 1        | 1.49%   |
| Gigabyte EP43T-USB3   | 1        | 1.49%   |
| Gigabyte B85M-DS3H-A  | 1        | 1.49%   |
| Gigabyte B85M-D3V-A   | 1        | 1.49%   |
| Gigabyte B450         | 1        | 1.49%   |
| Gigabyte AX370-Gaming | 1        | 1.49%   |
| Gigabyte AB350-Gaming | 1        | 1.49%   |
| Biostar TH55XE        | 1        | 1.49%   |
| Biostar TA790GXE      | 1        | 1.49%   |
| ASUS P8H61-MX         | 1        | 1.49%   |
| ASUS P7H55-M          | 1        | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 9        | 13.43%  |
| 2010 | 8        | 11.94%  |
| 2020 | 7        | 10.45%  |
| 2017 | 7        | 10.45%  |
| 2018 | 6        | 8.96%   |
| 2013 | 6        | 8.96%   |
| 2012 | 6        | 8.96%   |
| 2015 | 4        | 5.97%   |
| 2011 | 4        | 5.97%   |
| 2021 | 3        | 4.48%   |
| 2016 | 2        | 2.99%   |
| 2009 | 2        | 2.99%   |
| 2008 | 2        | 2.99%   |
| 2014 | 1        | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 67       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 63       | 94.03%  |
| Enabled  | 4        | 5.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 67       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 21       | 31.34%  |
| 4.01-8.0    | 16       | 23.88%  |
| 32.01-64.0  | 16       | 23.88%  |
| 8.01-16.0   | 6        | 8.96%   |
| 3.01-4.0    | 5        | 7.46%   |
| 64.01-256.0 | 2        | 2.99%   |
| 1.01-2.0    | 1        | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 28       | 40%     |
| 2.01-3.0   | 21       | 30%     |
| 3.01-4.0   | 11       | 15.71%  |
| 4.01-8.0   | 8        | 11.43%  |
| 32.01-64.0 | 1        | 1.43%   |
| 8.01-16.0  | 1        | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 25       | 36.76%  |
| 1      | 23       | 33.82%  |
| 3      | 11       | 16.18%  |
| 4      | 7        | 10.29%  |
| 5      | 2        | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 64.18%  |
| Yes       | 24       | 35.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 67       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 50.75%  |
| Yes       | 33       | 49.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 61.19%  |
| Yes       | 26       | 38.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Germany     | 9        | 13.24%  |
| USA         | 6        | 8.82%   |
| UK          | 4        | 5.88%   |
| Russia      | 4        | 5.88%   |
| Mexico      | 4        | 5.88%   |
| Brazil      | 4        | 5.88%   |
| Indonesia   | 3        | 4.41%   |
| Canada      | 3        | 4.41%   |
| Argentina   | 3        | 4.41%   |
| Turkey      | 2        | 2.94%   |
| Spain       | 2        | 2.94%   |
| Finland     | 2        | 2.94%   |
| Austria     | 2        | 2.94%   |
| Vietnam     | 1        | 1.47%   |
| Ukraine     | 1        | 1.47%   |
| Sri Lanka   | 1        | 1.47%   |
| Poland      | 1        | 1.47%   |
| Netherlands | 1        | 1.47%   |
| Kenya       | 1        | 1.47%   |
| Italy       | 1        | 1.47%   |
| Greece      | 1        | 1.47%   |
| France      | 1        | 1.47%   |
| Estonia     | 1        | 1.47%   |
| Denmark     | 1        | 1.47%   |
| Czechia     | 1        | 1.47%   |
| Costa Rica  | 1        | 1.47%   |
| Colombia    | 1        | 1.47%   |
| China       | 1        | 1.47%   |
| Chile       | 1        | 1.47%   |
| Belgium     | 1        | 1.47%   |
| Belarus     | 1        | 1.47%   |
| Australia   | 1        | 1.47%   |
| Albania     | 1        | 1.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Vienna                 | 2        | 2.9%    |
| Xicheng District       | 1        | 1.45%   |
| Wigan                  | 1        | 1.45%   |
| Vitória               | 1        | 1.45%   |
| Villahermosa           | 1        | 1.45%   |
| Vancouver              | 1        | 1.45%   |
| Tucson                 | 1        | 1.45%   |
| Tolyatti               | 1        | 1.45%   |
| Tallinn                | 1        | 1.45%   |
| Sukabumi               | 1        | 1.45%   |
| Sparti                 | 1        | 1.45%   |
| Simferopol             | 1        | 1.45%   |
| Sassnitz               | 1        | 1.45%   |
| Saskatoon              | 1        | 1.45%   |
| Sao Paulo              | 1        | 1.45%   |
| Santiago               | 1        | 1.45%   |
| Sant Quinti de Mediona | 1        | 1.45%   |
| San José              | 1        | 1.45%   |
| Rosario                | 1        | 1.45%   |
| Rio de Janeiro         | 1        | 1.45%   |
| Ragama                 | 1        | 1.45%   |
| Paris                  | 1        | 1.45%   |
| Pargolovo Tretye       | 1        | 1.45%   |
| Oudenbosch             | 1        | 1.45%   |
| Oldenburg              | 1        | 1.45%   |
| Nizhny Tagil           | 1        | 1.45%   |
| Nairobi                | 1        | 1.45%   |
| Musselburgh            | 1        | 1.45%   |
| Morelia                | 1        | 1.45%   |
| Montreal               | 1        | 1.45%   |
| Moers                  | 1        | 1.45%   |
| Minsk                  | 1        | 1.45%   |
| Milan                  | 1        | 1.45%   |
| Mexico City            | 1        | 1.45%   |
| Melbourne              | 1        | 1.45%   |
| les Masies de Voltrega | 1        | 1.45%   |
| Lerma de Villada       | 1        | 1.45%   |
| Landshut               | 1        | 1.45%   |
| Kucharovice            | 1        | 1.45%   |
| Krakow                 | 1        | 1.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 26       | 35     | 22.03%  |
| Samsung Electronics       | 18       | 27     | 15.25%  |
| Seagate                   | 17       | 21     | 14.41%  |
| SanDisk                   | 10       | 11     | 8.47%   |
| Kingston                  | 10       | 13     | 8.47%   |
| Crucial                   | 7        | 10     | 5.93%   |
| OCZ                       | 3        | 3      | 2.54%   |
| Hitachi                   | 3        | 3      | 2.54%   |
| Toshiba                   | 2        | 2      | 1.69%   |
| Phison                    | 2        | 3      | 1.69%   |
| Patriot                   | 2        | 2      | 1.69%   |
| Intel                     | 2        | 2      | 1.69%   |
| USB3.1                    | 1        | 1      | 0.85%   |
| Unknown                   | 1        | 1      | 0.85%   |
| Team                      | 1        | 1      | 0.85%   |
| SK hynix                  | 1        | 1      | 0.85%   |
| OCZ-VERTEX2               | 1        | 1      | 0.85%   |
| Micron/Crucial Technology | 1        | 2      | 0.85%   |
| Micron Technology         | 1        | 1      | 0.85%   |
| LITEON                    | 1        | 1      | 0.85%   |
| Kingmax                   | 1        | 1      | 0.85%   |
| Intenso                   | 1        | 1      | 0.85%   |
| HGST                      | 1        | 1      | 0.85%   |
| Gigabyte Technology       | 1        | 1      | 0.85%   |
| GALAX                     | 1        | 1      | 0.85%   |
| China                     | 1        | 1      | 0.85%   |
| Apacer                    | 1        | 1      | 0.85%   |
| A-DATA Technology         | 1        | 1      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB       | 5        | 3.65%   |
| Kingston SA400S37240G 240GB SSD    | 4        | 2.92%   |
| Samsung NVMe SSD Drive 1TB         | 3        | 2.19%   |
| Kingston SA400S37480G 480GB SSD    | 3        | 2.19%   |
| WDC WD5000AAKX-003CA0 500GB        | 2        | 1.46%   |
| WDC WD10EZEX-60WN4A0 1TB           | 2        | 1.46%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 1.46%   |
| Seagate ST250DM000-1BD141 250GB    | 2        | 1.46%   |
| SanDisk NVMe SSD Drive 500GB       | 2        | 1.46%   |
| Samsung SSD 850 EVO 250GB          | 2        | 1.46%   |
| Intel NVMe SSD Drive 512GB         | 2        | 1.46%   |
| Crucial CT240BX500SSD1 240GB       | 2        | 1.46%   |
| Crucial CT240BX200SSD1 240GB       | 2        | 1.46%   |
| WDC WDS500G2B0A 500GB SSD          | 1        | 0.73%   |
| WDC WD6401AALS-00J7B0 640GB        | 1        | 0.73%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 1        | 0.73%   |
| WDC WD5000AAKX-603CA0 500GB        | 1        | 0.73%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 0.73%   |
| WDC WD5000AAKX-001CA0 500GB        | 1        | 0.73%   |
| WDC WD50 00LUCT-61C26Y0 500GB      | 1        | 0.73%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1        | 0.73%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1        | 0.73%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 0.73%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1        | 0.73%   |
| WDC WD2500AAKS-00B3A0 250GB        | 1        | 0.73%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 0.73%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 0.73%   |
| WDC WD20EARS-00MVWB0 2TB           | 1        | 0.73%   |
| WDC WD15EARX-00PASB0 1TB           | 1        | 0.73%   |
| WDC WD10EZRX-00L4HB0 1TB           | 1        | 0.73%   |
| WDC WD10EZRX-00A8LB0 1TB           | 1        | 0.73%   |
| WDC WD10EZEX-75ZF5A0 1TB           | 1        | 0.73%   |
| WDC WD10EZEX-22MFCA0 1TB           | 1        | 0.73%   |
| WDC WD10EZEX-00RKKA0 1TB           | 1        | 0.73%   |
| WDC WD10EZEX-00KUWA0 1TB           | 1        | 0.73%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 0.73%   |
| WDC WD10EURX-63UY4Y0 1TB           | 1        | 0.73%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 1        | 0.73%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB | 1        | 0.73%   |
| USB3.1 Disk 1TB                    | 1        | 0.73%   |

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
| Samsung Electronics | 8        | 11     | 17.78%  |
| Kingston            | 8        | 10     | 17.78%  |
| Crucial             | 7        | 10     | 15.56%  |
| SanDisk             | 6        | 6      | 13.33%  |
| OCZ                 | 3        | 3      | 6.67%   |
| Patriot             | 2        | 2      | 4.44%   |
| WDC                 | 1        | 1      | 2.22%   |
| Team                | 1        | 1      | 2.22%   |
| SK hynix            | 1        | 1      | 2.22%   |
| OCZ-VERTEX2         | 1        | 1      | 2.22%   |
| LITEON              | 1        | 1      | 2.22%   |
| Kingmax             | 1        | 1      | 2.22%   |
| Intenso             | 1        | 1      | 2.22%   |
| GALAX               | 1        | 1      | 2.22%   |
| China               | 1        | 1      | 2.22%   |
| Apacer              | 1        | 1      | 2.22%   |
| A-DATA Technology   | 1        | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 42       | 62     | 40.78%  |
| SSD     | 37       | 53     | 35.92%  |
| NVMe    | 22       | 32     | 21.36%  |
| Unknown | 2        | 2      | 1.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 59       | 111    | 69.41%  |
| NVMe | 22       | 32     | 25.88%  |
| SAS  | 4        | 6      | 4.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 50       | 74     | 59.52%  |
| 0.51-1.0   | 25       | 31     | 29.76%  |
| 1.01-2.0   | 5        | 6      | 5.95%   |
| 3.01-4.0   | 2        | 2      | 2.38%   |
| 2.01-3.0   | 2        | 2      | 2.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 18       | 26.87%  |
| 101-250        | 18       | 26.87%  |
| 501-1000       | 8        | 11.94%  |
| 21-50          | 7        | 10.45%  |
| More than 3000 | 4        | 5.97%   |
| 2001-3000      | 4        | 5.97%   |
| 1001-2000      | 4        | 5.97%   |
| 51-100         | 3        | 4.48%   |
| 1-20           | 1        | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 33       | 47.83%  |
| 21-50     | 11       | 15.94%  |
| 51-100    | 9        | 13.04%  |
| 101-250   | 5        | 7.25%   |
| 251-500   | 4        | 5.8%    |
| 501-1000  | 3        | 4.35%   |
| 2001-3000 | 2        | 2.9%    |
| 1001-2000 | 2        | 2.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 1      | 12.5%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 1      | 12.5%   |
| WDC WD10EZEX-00KUWA0 1TB           | 1        | 1      | 12.5%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 1        | 1      | 12.5%   |
| Seagate ST3160813AS 160GB          | 1        | 1      | 12.5%   |
| Samsung Electronics HD160JJ/ 160GB | 1        | 1      | 12.5%   |
| Hitachi HTS542525K9SA00 250GB      | 1        | 1      | 12.5%   |
| Crucial CT256M550SSD1 256GB        | 1        | 1      | 12.5%   |

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
| Detected | 60       | 128    | 83.33%  |
| Works    | 7        | 13     | 9.72%   |
| Malfunc  | 5        | 8      | 6.94%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 42       | 42.86%  |
| AMD                         | 23       | 23.47%  |
| Samsung Electronics         | 10       | 10.2%   |
| SanDisk                     | 6        | 6.12%   |
| Phison Electronics          | 2        | 2.04%   |
| Marvell Technology Group    | 2        | 2.04%   |
| Kingston Technology Company | 2        | 2.04%   |
| JMicron Technology          | 2        | 2.04%   |
| ASMedia Technology          | 2        | 2.04%   |
| VIA Technologies            | 1        | 1.02%   |
| Seagate Technology          | 1        | 1.02%   |
| Nvidia                      | 1        | 1.02%   |
| Micron/Crucial Technology   | 1        | 1.02%   |
| Micron Technology           | 1        | 1.02%   |
| LSI Logic / Symbios Logic   | 1        | 1.02%   |
| Broadcom / LSI              | 1        | 1.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 11.11%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 6.35%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 4.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 3.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 3.17%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 2.38%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 2.38%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 2.38%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.38%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 2.38%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.59%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.59%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.59%   |
| JMicron JMB368 IDE controller                                                           | 2        | 1.59%   |
| Intel SSD 660P Series                                                                   | 2        | 1.59%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.59%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.59%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.59%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.79%   |
| Seagate FireCuda 510 SSD                                                                | 1        | 0.79%   |
| SanDisk WD Black NVMe SSD                                                               | 1        | 0.79%   |
| SanDisk Non-Volatile memory controller                                                  | 1        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.79%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.79%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.79%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.79%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 0.79%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.79%   |
| Micron Non-Volatile memory controller                                                   | 1        | 0.79%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 50       | 53.19%  |
| NVMe | 22       | 23.4%   |
| IDE  | 13       | 13.83%  |
| RAID | 7        | 7.45%   |
| SAS  | 1        | 1.06%   |
| SCSI | 1        | 1.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 42       | 62.69%  |
| AMD    | 25       | 37.31%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor     | 4        | 5.97%   |
| AMD Ryzen 5 3600 6-Core Processor      | 3        | 4.48%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 2        | 2.99%   |
| Intel Core i3 CPU 530 @ 2.93GHz        | 2        | 2.99%   |
| AMD Ryzen 7 2700 Eight-Core Processor  | 2        | 2.99%   |
| Intel Xeon CPU X5660 @ 2.80GHz         | 1        | 1.49%   |
| Intel Xeon CPU E5520 @ 2.27GHz         | 1        | 1.49%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz     | 1        | 1.49%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz     | 1        | 1.49%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz | 1        | 1.49%   |
| Intel Pentium CPU G620 @ 2.60GHz       | 1        | 1.49%   |
| Intel Pentium CPU G3260 @ 3.30GHz      | 1        | 1.49%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 1        | 1.49%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 1        | 1.49%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 1.49%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 1        | 1.49%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 1        | 1.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 1        | 1.49%   |
| Intel Core i7-4785T CPU @ 2.20GHz      | 1        | 1.49%   |
| Intel Core i7-10700F CPU @ 2.90GHz     | 1        | 1.49%   |
| Intel Core i7 CPU 950 @ 3.07GHz        | 1        | 1.49%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 1        | 1.49%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 1        | 1.49%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 1        | 1.49%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 1        | 1.49%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 1        | 1.49%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 1        | 1.49%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1        | 1.49%   |
| Intel Core i5-3550 CPU @ 3.30GHz       | 1        | 1.49%   |
| Intel Core i5-2500K CPU @ 3.30GHz      | 1        | 1.49%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 1        | 1.49%   |
| Intel Core i5-2320 CPU @ 3.00GHz       | 1        | 1.49%   |
| Intel Core i5-10600K CPU @ 4.10GHz     | 1        | 1.49%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 1.49%   |
| Intel Core i5 CPU 750 @ 2.67GHz        | 1        | 1.49%   |
| Intel Core i3-6100T CPU @ 3.20GHz      | 1        | 1.49%   |
| Intel Core 2 Quad CPU Q9500 @ 2.83GHz  | 1        | 1.49%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz   | 1        | 1.49%   |
| Intel Celeron G4930 CPU @ 3.20GHz      | 1        | 1.49%   |
| Intel Celeron CPU G530 @ 2.40GHz       | 1        | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 14       | 20.9%   |
| Intel Core i7      | 9        | 13.43%  |
| AMD Ryzen 7        | 7        | 10.45%  |
| Intel Core i3      | 5        | 7.46%   |
| AMD Ryzen 5        | 5        | 7.46%   |
| Intel Xeon         | 4        | 5.97%   |
| Intel Celeron      | 3        | 4.48%   |
| AMD FX             | 3        | 4.48%   |
| Other              | 2        | 2.99%   |
| Intel Pentium      | 2        | 2.99%   |
| AMD Ryzen 9        | 2        | 2.99%   |
| Intel Pentium Dual | 1        | 1.49%   |
| Intel Core 2 Quad  | 1        | 1.49%   |
| Intel Core 2 Duo   | 1        | 1.49%   |
| AMD Ryzen 3        | 1        | 1.49%   |
| AMD Phenom II X4   | 1        | 1.49%   |
| AMD Phenom         | 1        | 1.49%   |
| AMD G              | 1        | 1.49%   |
| AMD Athlon II X4   | 1        | 1.49%   |
| AMD A6             | 1        | 1.49%   |
| AMD A4             | 1        | 1.49%   |
| AMD A10            | 1        | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 22       | 32.84%  |
| 2      | 14       | 20.9%   |
| 8      | 13       | 19.4%   |
| 6      | 11       | 16.42%  |
| 12     | 4        | 5.97%   |
| 1      | 2        | 2.99%   |
| 3      | 1        | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 64       | 95.52%  |
| 2      | 3        | 4.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 41       | 61.19%  |
| 1      | 26       | 38.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 67       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 8        | 11.76%  |
| 0x206a7    | 6        | 8.82%   |
| 0x08701021 | 6        | 8.82%   |
| 0x0800820d | 4        | 5.88%   |
| Unknown    | 4        | 5.88%   |
| 0x906ea    | 3        | 4.41%   |
| 0xa0671    | 2        | 2.94%   |
| 0xa0655    | 2        | 2.94%   |
| 0x906e9    | 2        | 2.94%   |
| 0x306a9    | 2        | 2.94%   |
| 0x206d7    | 2        | 2.94%   |
| 0x20652    | 2        | 2.94%   |
| 0x106a5    | 2        | 2.94%   |
| 0x08701013 | 2        | 2.94%   |
| 0x0600611a | 2        | 2.94%   |
| 0x06000852 | 2        | 2.94%   |
| 0xa0653    | 1        | 1.47%   |
| 0x906ed    | 1        | 1.47%   |
| 0x906eb    | 1        | 1.47%   |
| 0x6fd      | 1        | 1.47%   |
| 0x6fb      | 1        | 1.47%   |
| 0x506e3    | 1        | 1.47%   |
| 0x206c2    | 1        | 1.47%   |
| 0x106e5    | 1        | 1.47%   |
| 0x1067a    | 1        | 1.47%   |
| 0x0a201016 | 1        | 1.47%   |
| 0x08101007 | 1        | 1.47%   |
| 0x0800111c | 1        | 1.47%   |
| 0x06001119 | 1        | 1.47%   |
| 0x0600063e | 1        | 1.47%   |
| 0x05000119 | 1        | 1.47%   |
| 0x010000db | 1        | 1.47%   |
| 0x01000095 | 1        | 1.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 9        | 13.43%  |
| Zen 2       | 8        | 11.94%  |
| KabyLake    | 8        | 11.94%  |
| Haswell     | 8        | 11.94%  |
| Zen+        | 4        | 5.97%   |
| Westmere    | 3        | 4.48%   |
| Piledriver  | 3        | 4.48%   |
| Nehalem     | 3        | 4.48%   |
| K10         | 3        | 4.48%   |
| CometLake   | 3        | 4.48%   |
| Zen         | 2        | 2.99%   |
| IvyBridge   | 2        | 2.99%   |
| Icelake     | 2        | 2.99%   |
| Excavator   | 2        | 2.99%   |
| Core        | 2        | 2.99%   |
| Zen 3       | 1        | 1.49%   |
| Skylake     | 1        | 1.49%   |
| Penryn      | 1        | 1.49%   |
| Bulldozer   | 1        | 1.49%   |
| Bobcat      | 1        | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| AMD              | 28       | 38.36%  |
| Nvidia           | 26       | 35.62%  |
| Intel            | 17       | 23.29%  |
| Conexant Systems | 1        | 1.37%   |
| ATI Technologies | 1        | 1.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 9.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 6.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 5.41%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 2.7%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.7%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 2.7%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 2.7%    |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 2.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.7%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 2.7%    |
| AMD RS780D [Radeon HD 3300]                                                 | 2        | 2.7%    |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 2.7%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 2.7%    |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 2        | 2.7%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.35%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.35%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.35%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.35%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.35%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 1.35%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.35%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.35%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.35%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.35%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.35%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.35%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 1.35%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.35%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 1.35%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.35%   |
| Intel HD Graphics 630                                                       | 1        | 1.35%   |
| Intel HD Graphics 530                                                       | 1        | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.35%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.35%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.35%   |
| Conexant Systems Conexant Display controller                                | 1        | 1.35%   |
| ATI Technologies Wani [Radeon R5/R6/R7 Graphics]                            | 1        | 1.35%   |
| AMD Wrestler [Radeon HD 6250]                                               | 1        | 1.35%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| 1 x Nvidia                     | 24       | 35.82%  |
| 1 x AMD                        | 24       | 35.82%  |
| 1 x Intel                      | 14       | 20.9%   |
| 2 x AMD + 1 x Conexant Systems | 1        | 1.49%   |
| 2 x AMD                        | 1        | 1.49%   |
| Intel + Nvidia                 | 1        | 1.49%   |
| Intel + AMD                    | 1        | 1.49%   |
| AMD + Nvidia                   | 1        | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 55       | 79.71%  |
| Proprietary | 13       | 18.84%  |
| Unknown     | 1        | 1.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 26.47%  |
| 1.01-2.0   | 13       | 19.12%  |
| 7.01-8.0   | 11       | 16.18%  |
| 3.01-4.0   | 10       | 14.71%  |
| 0.51-1.0   | 6        | 8.82%   |
| 0.01-0.5   | 4        | 5.88%   |
| 5.01-6.0   | 3        | 4.41%   |
| 8.01-16.0  | 2        | 2.94%   |
| 2.01-3.0   | 1        | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 17.57%  |
| Hewlett-Packard      | 11       | 14.86%  |
| Goldstar             | 8        | 10.81%  |
| BenQ                 | 6        | 8.11%   |
| Acer                 | 6        | 8.11%   |
| Dell                 | 5        | 6.76%   |
| AOC                  | 4        | 5.41%   |
| Ancor Communications | 4        | 5.41%   |
| ViewSonic            | 2        | 2.7%    |
| LG Electronics       | 2        | 2.7%    |
| Vizio                | 1        | 1.35%   |
| TBD                  | 1        | 1.35%   |
| SKY                  | 1        | 1.35%   |
| Philips              | 1        | 1.35%   |
| MSI                  | 1        | 1.35%   |
| Lenovo Group Limited | 1        | 1.35%   |
| Lenovo               | 1        | 1.35%   |
| HOP                  | 1        | 1.35%   |
| Grundig              | 1        | 1.35%   |
| Denver               | 1        | 1.35%   |
| AUS                  | 1        | 1.35%   |
| ASUSTek Computer     | 1        | 1.35%   |
| Unknown              | 1        | 1.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                        | 2        | 2.5%    |
| Vizio E320VT VIZ0067 1920x1080 698x392mm 31.5-inch                     | 1        | 1.25%   |
| ViewSonic VA2446 Series VSC732E 1920x1080 521x293mm 23.5-inch          | 1        | 1.25%   |
| ViewSonic VA2055 Series VSC3C31 1920x1080 435x239mm 19.5-inch          | 1        | 1.25%   |
| TBD HDMI TBD3148 1600x900 344x193mm 15.5-inch                          | 1        | 1.25%   |
| SKY SKYWORTH SKY0001 1920x1080 885x498mm 40.0-inch                     | 1        | 1.25%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch      | 1        | 1.25%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch      | 1        | 1.25%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch      | 1        | 1.25%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch   | 1        | 1.25%   |
| Samsung Electronics S27H85x SAM0E0E 2560x1440 597x336mm 27.0-inch      | 1        | 1.25%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch      | 1        | 1.25%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 1        | 1.25%   |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch      | 1        | 1.25%   |
| Samsung Electronics LCD Monitor SAM705B 1920x1080 1210x680mm 54.6-inch | 1        | 1.25%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1        | 1.25%   |
| Samsung Electronics LCD Monitor S24F350 5760x1080                      | 1        | 1.25%   |
| Samsung Electronics LCD Monitor S24F350                                | 1        | 1.25%   |
| Samsung Electronics LCD Monitor C24F390 1920x1080                      | 1        | 1.25%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch     | 1        | 1.25%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch     | 1        | 1.25%   |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch                | 1        | 1.25%   |
| MSI Optix MAG27C MSI1462 1920x1080 590x350mm 27.0-inch                 | 1        | 1.25%   |
| LG Electronics LCD Monitor LG IPS FULLHD                               | 1        | 1.25%   |
| LG Electronics LCD Monitor 25UM58G 2560x1080                           | 1        | 1.25%   |
| Lenovo LEN LS1922wA LEN0A14 1366x768 410x230mm 18.5-inch               | 1        | 1.25%   |
| Lenovo Group Limited LCD Monitor LEN D32q-20B 4480x1440                | 1        | 1.25%   |
| HOP DVI HOP2700 1920x1080 597x336mm 27.0-inch                          | 1        | 1.25%   |
| Hewlett-Packard P204v HPN3634 1600x900 432x240mm 19.5-inch             | 1        | 1.25%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 546x352mm 25.6-inch          | 1        | 1.25%   |
| Hewlett-Packard LE2002x HWP2964 1600x900 443x249mm 20.0-inch           | 1        | 1.25%   |
| Hewlett-Packard LCD Monitor LA2306 4480x1440                           | 1        | 1.25%   |
| Hewlett-Packard E243m HPN3466 1920x1080 527x296mm 23.8-inch            | 1        | 1.25%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch             | 1        | 1.25%   |
| Hewlett-Packard Compaq WF1907 HWP26A4 1440x900 408x255mm 18.9-inch     | 1        | 1.25%   |
| Hewlett-Packard 27f HPN354C 1920x1080 598x336mm 27.0-inch              | 1        | 1.25%   |
| Hewlett-Packard 27f HPN354B 1920x1080 598x336mm 27.0-inch              | 1        | 1.25%   |
| Hewlett-Packard 24x HPN3635 1920x1080 527x297mm 23.8-inch              | 1        | 1.25%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch             | 1        | 1.25%   |
| Grundig WXGA GRU4448 1600x1200                                         | 1        | 1.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 31       | 44.93%  |
| 3840x2160 (4K)     | 7        | 10.14%  |
| 2560x1440 (QHD)    | 5        | 7.25%   |
| 1600x900 (HD+)     | 4        | 5.8%    |
| Unknown            | 4        | 5.8%    |
| 3840x1080          | 3        | 4.35%   |
| 2560x1080          | 3        | 4.35%   |
| 1440x900 (WXGA+)   | 3        | 4.35%   |
| 1680x1050 (WSXGA+) | 2        | 2.9%    |
| 5760x1080          | 1        | 1.45%   |
| 5120x1440          | 1        | 1.45%   |
| 4480x1440          | 1        | 1.45%   |
| 3440x1440          | 1        | 1.45%   |
| 1920x1200 (WUXGA)  | 1        | 1.45%   |
| 1366x768 (WXGA)    | 1        | 1.45%   |
| 1280x1024 (SXGA)   | 1        | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 10       | 13.89%  |
| 21      | 10       | 13.89%  |
| Unknown | 10       | 13.89%  |
| 23      | 9        | 12.5%   |
| 24      | 6        | 8.33%   |
| 19      | 4        | 5.56%   |
| 54      | 3        | 4.17%   |
| 49      | 2        | 2.78%   |
| 34      | 2        | 2.78%   |
| 31      | 2        | 2.78%   |
| 20      | 2        | 2.78%   |
| 17      | 2        | 2.78%   |
| 72      | 1        | 1.39%   |
| 40      | 1        | 1.39%   |
| 33      | 1        | 1.39%   |
| 32      | 1        | 1.39%   |
| 29      | 1        | 1.39%   |
| 28      | 1        | 1.39%   |
| 25      | 1        | 1.39%   |
| 22      | 1        | 1.39%   |
| 18      | 1        | 1.39%   |
| 15      | 1        | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 22       | 31.88%  |
| 401-500     | 17       | 24.64%  |
| Unknown     | 10       | 14.49%  |
| 601-700     | 6        | 8.7%    |
| 1001-1500   | 5        | 7.25%   |
| 701-800     | 4        | 5.8%    |
| 301-350     | 2        | 2.9%    |
| 801-900     | 1        | 1.45%   |
| 351-400     | 1        | 1.45%   |
| 1501-2000   | 1        | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 41       | 65.08%  |
| Unknown | 10       | 15.87%  |
| 21/9    | 4        | 6.35%   |
| 16/10   | 4        | 6.35%   |
| 32/9    | 2        | 3.17%   |
| 5/4     | 1        | 1.59%   |
| 3/2     | 1        | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 23       | 32.39%  |
| 301-350        | 11       | 15.49%  |
| Unknown        | 10       | 14.08%  |
| 151-200        | 8        | 11.27%  |
| 351-500        | 6        | 8.45%   |
| More than 1000 | 4        | 5.63%   |
| 501-1000       | 3        | 4.23%   |
| 251-300        | 2        | 2.82%   |
| 141-150        | 2        | 2.82%   |
| 131-140        | 1        | 1.41%   |
| 101-110        | 1        | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 40       | 58.82%  |
| 101-120 | 13       | 19.12%  |
| Unknown | 10       | 14.71%  |
| 1-50    | 3        | 4.41%   |
| 121-160 | 2        | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 52       | 76.47%  |
| 2     | 11       | 16.18%  |
| 3     | 3        | 4.41%   |
| 0     | 2        | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 45       | 46.88%  |
| Intel                    | 22       | 22.92%  |
| TP-Link                  | 7        | 7.29%   |
| Ralink Technology        | 4        | 4.17%   |
| Xiaomi                   | 3        | 3.13%   |
| Qualcomm Atheros         | 3        | 3.13%   |
| Broadcom                 | 3        | 3.13%   |
| Samsung Electronics      | 1        | 1.04%   |
| Ralink                   | 1        | 1.04%   |
| Nvidia                   | 1        | 1.04%   |
| NetGear                  | 1        | 1.04%   |
| Mercucys                 | 1        | 1.04%   |
| MediaTek                 | 1        | 1.04%   |
| Marvell Technology Group | 1        | 1.04%   |
| Edimax Technology        | 1        | 1.04%   |
| ASUSTek Computer         | 1        | 1.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38       | 34.55%  |
| Intel I211 Gigabit Network Connection                             | 5        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 3.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 2.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.73%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 2.73%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 2.73%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 1.82%   |
| TP-Link 802.11ac NIC                                              | 2        | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.82%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.82%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.82%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 1.82%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                             | 1        | 0.91%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.91%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 0.91%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.91%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.91%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 0.91%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.91%   |
| Ralink RT5592 PCIe Wireless Network Adapter                       | 1        | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.91%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.91%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.91%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]            | 1        | 0.91%   |
| Mercucys 802.11n NIC                                              | 1        | 0.91%   |
| MediaTek Infinix NOTE 11                                          | 1        | 0.91%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.91%   |
| Intel Wireless-AC 9260                                            | 1        | 0.91%   |
| Intel Wireless 7260                                               | 1        | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.91%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1        | 0.91%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.91%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 9        | 25%     |
| Realtek Semiconductor | 8        | 22.22%  |
| TP-Link               | 7        | 19.44%  |
| Ralink Technology     | 4        | 11.11%  |
| Broadcom              | 2        | 5.56%   |
| Ralink                | 1        | 2.78%   |
| Qualcomm Atheros      | 1        | 2.78%   |
| NetGear               | 1        | 2.78%   |
| Mercucys              | 1        | 2.78%   |
| Edimax Technology     | 1        | 2.78%   |
| ASUSTek Computer      | 1        | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                | 3        | 8.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2        | 5.56%   |
| TP-Link 802.11ac NIC                                           | 2        | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 5.56%   |
| Intel Wi-Fi 6 AX200                                            | 2        | 5.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2        | 5.56%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1        | 2.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 2.78%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1        | 2.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 2.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 2.78%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 2.78%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 2.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 2.78%   |
| Realtek RTL8187 Wireless Adapter                               | 1        | 2.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 2.78%   |
| Ralink RT5592 PCIe Wireless Network Adapter                    | 1        | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 2.78%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]         | 1        | 2.78%   |
| Mercucys 802.11n NIC                                           | 1        | 2.78%   |
| Intel Wireless-AC 9260                                         | 1        | 2.78%   |
| Intel Wireless 7260                                            | 1        | 2.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 2.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 2.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 2.78%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1        | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1        | 2.78%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 2.78%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072] | 1        | 2.78%   |

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
| MediaTek Infinix NOTE 11                                          | 1        | 1.35%   |
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
| Ethernet | 67       | 67%     |
| WiFi     | 33       | 33%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 70.59%  |
| WiFi     | 20       | 29.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 44       | 65.67%  |
| 2     | 21       | 31.34%  |
| 3     | 1        | 1.49%   |
| 0     | 1        | 1.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 50       | 73.53%  |
| Yes  | 18       | 26.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 11       | 40.74%  |
| Intel                   | 9        | 33.33%  |
| Realtek Semiconductor   | 2        | 7.41%   |
| Apple                   | 2        | 7.41%   |
| Broadcom                | 1        | 3.7%    |
| Belkin Components       | 1        | 3.7%    |
| ASUSTek Computer        | 1        | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 40.74%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 7.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 7.41%   |
| Intel AX200 Bluetooth                               | 2        | 7.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.7%    |
| Intel Bluetooth wireless interface                  | 1        | 3.7%    |
| Intel AX210 Bluetooth                               | 1        | 3.7%    |
| Intel AX201 Bluetooth                               | 1        | 3.7%    |
| Broadcom Bluetooth 3.0 Dongle                       | 1        | 3.7%    |
| Belkin Components Bluetooth Mini Dongle             | 1        | 3.7%    |
| ASUS Bluetooth Radio                                | 1        | 3.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 3.7%    |
| Apple Bluetooth USB Host Controller                 | 1        | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 40       | 33.06%  |
| AMD                                  | 35       | 28.93%  |
| Nvidia                               | 25       | 20.66%  |
| C-Media Electronics                  | 6        | 4.96%   |
| Creative Labs                        | 3        | 2.48%   |
| Logitech                             | 2        | 1.65%   |
| Generalplus Technology               | 2        | 1.65%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.83%   |
| Razer USA                            | 1        | 0.83%   |
| JMTek                                | 1        | 0.83%   |
| Focusrite-Novation                   | 1        | 0.83%   |
| Creative Technology                  | 1        | 0.83%   |
| BY EDIFIER                           | 1        | 0.83%   |
| ATI Technologies                     | 1        | 0.83%   |
| ASUSTek Computer                     | 1        | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 9        | 6.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 7        | 4.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7        | 4.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 7        | 4.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6        | 4.23%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 3.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 2.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 4        | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 2.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 2.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 2.11%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 3        | 2.11%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 1.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 1.41%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 1.41%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2        | 1.41%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 1.41%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 1.41%   |
| Nvidia GA102 High Definition Audio Controller                                     | 2        | 1.41%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 1.41%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 1.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2        | 1.41%   |
| Generalplus Technology USB Audio Device                                           | 2        | 1.41%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                        | 2        | 1.41%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 2        | 1.41%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 2        | 1.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 2        | 1.41%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.41%   |
| Thesycon Systemsoftware & Consulting MX5                                          | 1        | 0.7%    |
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
| SK hynix            | 1        | 5.26%   |
| Neo Forza           | 1        | 5.26%   |
| Nanya Technology    | 1        | 5.26%   |
| Crucial             | 1        | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 5%      |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s     | 1        | 5%      |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s             | 1        | 5%      |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s    | 1        | 5%      |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s      | 1        | 5%      |
| Neo Forza RAM NMUD380D81-1600D 8GB DIMM DDR3 1333MT/s    | 1        | 5%      |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 5%      |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s      | 1        | 5%      |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 1        | 5%      |
| Kingston RAM 99U5471-052.A 8GB DIMM DDR3 1333MT/s        | 1        | 5%      |
| Kingston RAM 99U5458-001.A00LF 2048MB DIMM DDR3 1600MT/s | 1        | 5%      |
| Kingston RAM 99U5403-159.A01LF 8GB DIMM 800MT/s          | 1        | 5%      |
| Kingston RAM 9965516-069.A00LF 8192MB DIMM DDR3 1333MT/s | 1        | 5%      |
| Kingston RAM 9965516-003.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 5%      |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 1        | 5%      |
| G.Skill RAM F3-1866C11-8GRSL 8GB SODIMM DDR3 1867MT/s    | 1        | 5%      |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1867MT/s     | 1        | 5%      |
| Crucial RAM BLS8G4D26BFSCK.8FD 8GB DIMM DDR4 3000MT/s    | 1        | 5%      |
| Corsair RAM CMK4GX4M1A2400C14 4GB DIMM DDR4 3007MT/s     | 1        | 5%      |
| Corsair RAM CMH32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s   | 1        | 5%      |

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


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech Webcam C270            | 2        | 10.53%  |
| Z-Star Sirius USB2.0 Camera     | 1        | 5.26%   |
| Sunplus SPCA2650 AV Camera      | 1        | 5.26%   |
| Sunplus Aukey-PC-LM1E Camera    | 1        | 5.26%   |
| Microsoft Xbox NUI Camera       | 1        | 5.26%   |
| Microsoft LifeCam HD-3000       | 1        | 5.26%   |
| Microdia Webcam Vitade AF       | 1        | 5.26%   |
| Microdia USB 2.0 Camera         | 1        | 5.26%   |
| Microdia Integrated Camera      | 1        | 5.26%   |
| Logitech Webcam C310            | 1        | 5.26%   |
| Logitech Logi 4K Stream Edition | 1        | 5.26%   |
| Logitech HD Webcam C615         | 1        | 5.26%   |
| Logitech HD Pro Webcam C920     | 1        | 5.26%   |
| Logitech C505 HD Webcam         | 1        | 5.26%   |
| Logitech B525 HD Webcam         | 1        | 5.26%   |
| Generalplus GENERAL WEBCAM      | 1        | 5.26%   |
| Creative Live! Cam Sync 1080p   | 1        | 5.26%   |
| Apple iPhone5/5C/5S/6           | 1        | 5.26%   |

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
| 0     | 62       | 91.18%  |
| 1     | 6        | 8.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 4        | 66.67%  |
| Graphics card            | 1        | 16.67%  |
| Communication controller | 1        | 16.67%  |

