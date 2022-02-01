Elementary 6 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.

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
| 5.11.0-40-generic    | 16       | 23.19%  |
| 5.11.0-41-generic    | 14       | 20.29%  |
| 5.11.0-27-generic    | 10       | 14.49%  |
| 5.11.0-37-generic    | 6        | 8.7%    |
| 5.11.0-38-generic    | 5        | 7.25%   |
| 5.11.0-25-generic    | 5        | 7.25%   |
| 5.8.0-50-generic     | 3        | 4.35%   |
| 5.11.0-36-generic    | 2        | 2.9%    |
| 5.11.0-34-generic    | 2        | 2.9%    |
| 5.8.0-63-generic     | 1        | 1.45%   |
| 5.8.0-55-generic     | 1        | 1.45%   |
| 5.4.0-58-generic     | 1        | 1.45%   |
| 5.4.0-56-generic     | 1        | 1.45%   |
| 5.15.1-xanmod1       | 1        | 1.45%   |
| 5.11.0-41-lowlatency | 1        | 1.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 57       | 87.69%  |
| 5.8.0   | 5        | 7.69%   |
| 5.4.0   | 2        | 3.08%   |
| 5.15.1  | 1        | 1.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 57       | 87.69%  |
| 5.8     | 5        | 7.69%   |
| 5.4     | 2        | 3.08%   |
| 5.15    | 1        | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 65       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 60       | 90.91%  |
| Unknown  | 4        | 6.06%   |
| MATE     | 1        | 1.52%   |
| GNOME    | 1        | 1.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 65       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 55       | 84.62%  |
| LightDM | 7        | 10.77%  |
| TDM     | 3        | 4.62%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 33       | 50.77%  |
| de_DE | 8        | 12.31%  |
| es_ES | 7        | 10.77%  |
| ru_RU | 4        | 6.15%   |
| pt_BR | 3        | 4.62%   |
| en_GB | 2        | 3.08%   |
| zh_CN | 1        | 1.54%   |
| tr_TR | 1        | 1.54%   |
| it_IT | 1        | 1.54%   |
| fr_FR | 1        | 1.54%   |
| es_MX | 1        | 1.54%   |
| en_AU | 1        | 1.54%   |
| de_CH | 1        | 1.54%   |
| ca_ES | 1        | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 39       | 60%     |
| BIOS | 26       | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 62       | 95.38%  |
| Btrfs | 3        | 4.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 57       | 87.69%  |
| GPT     | 5        | 7.69%   |
| MBR     | 3        | 4.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 93.85%  |
| Yes       | 4        | 6.15%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 83.08%  |
| Yes       | 11       | 16.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 15       | 23.08%  |
| Gigabyte Technology | 14       | 21.54%  |
| Hewlett-Packard     | 8        | 12.31%  |
| ASRock              | 8        | 12.31%  |
| MSI                 | 6        | 9.23%   |
| Dell                | 3        | 4.62%   |
| Pegatron            | 2        | 3.08%   |
| Intel               | 2        | 3.08%   |
| Biostar             | 2        | 3.08%   |
| Acer                | 2        | 3.08%   |
| Shuttle             | 1        | 1.54%   |
| Chuwi               | 1        | 1.54%   |
| Apple               | 1        | 1.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Shuttle DS61                         | 1        | 1.54%   |
| Pegatron KJ379AA-ABA a6400f          | 1        | 1.54%   |
| Pegatron IPMH61P1                    | 1        | 1.54%   |
| MSI MS-7C83                          | 1        | 1.54%   |
| MSI MS-7B79                          | 1        | 1.54%   |
| MSI MS-7B46                          | 1        | 1.54%   |
| MSI MS-7817                          | 1        | 1.54%   |
| MSI MS-7693                          | 1        | 1.54%   |
| MSI Elite 7100 Microtower PC         | 1        | 1.54%   |
| Intel X64                            | 1        | 1.54%   |
| Intel H61                            | 1        | 1.54%   |
| HP Z820 Workstation                  | 1        | 1.54%   |
| HP Z800 Workstation                  | 1        | 1.54%   |
| HP Pavilion Gaming Desktop TG01-1xxx | 1        | 1.54%   |
| HP Pavilion Desktop 590-p0xxx        | 1        | 1.54%   |
| HP ENVY TE01-0xxx                    | 1        | 1.54%   |
| HP EliteDesk 800 G1 DM               | 1        | 1.54%   |
| HP Compaq 6200 Pro MT PC             | 1        | 1.54%   |
| HP 339A                              | 1        | 1.54%   |
| Gigabyte Z390 GAMING X               | 1        | 1.54%   |
| Gigabyte Z270X-Gaming 5              | 1        | 1.54%   |
| Gigabyte X570 I AORUS PRO WIFI       | 1        | 1.54%   |
| Gigabyte X570 AORUS PRO WIFI         | 1        | 1.54%   |
| Gigabyte H81M-H                      | 1        | 1.54%   |
| Gigabyte H310M M.2 2.0               | 1        | 1.54%   |
| Gigabyte F2A55M-HD2                  | 1        | 1.54%   |
| Gigabyte EP43T-USB3                  | 1        | 1.54%   |
| Gigabyte B85M-DS3H-A                 | 1        | 1.54%   |
| Gigabyte B85M-D3V-A                  | 1        | 1.54%   |
| Gigabyte B450M DS3H V2               | 1        | 1.54%   |
| Gigabyte B450 I AORUS PRO WIFI       | 1        | 1.54%   |
| Gigabyte AX370-Gaming                | 1        | 1.54%   |
| Gigabyte AB350-Gaming 3              | 1        | 1.54%   |
| Dell OptiPlex 9020M                  | 1        | 1.54%   |
| Dell OptiPlex 9010                   | 1        | 1.54%   |
| Dell OptiPlex 3040                   | 1        | 1.54%   |
| Chuwi LarkBox Pro                    | 1        | 1.54%   |
| Biostar TH55XE                       | 1        | 1.54%   |
| Biostar TA790GXE 128M                | 1        | 1.54%   |
| ASUS TUF GAMING B560M-PLUS           | 1        | 1.54%   |
| ASUS TUF GAMING B550M-PLUS           | 1        | 1.54%   |
| ASUS TUF GAMING B450M-PRO II         | 1        | 1.54%   |
| ASUS ROG STRIX Z590-F GAMING WIFI    | 1        | 1.54%   |
| ASUS ROG STRIX B450-I GAMING         | 1        | 1.54%   |
| ASUS PRIME B365M-A                   | 1        | 1.54%   |
| ASUS PRIME A320M-K                   | 1        | 1.54%   |
| ASUS P8H61-MX R2.0                   | 1        | 1.54%   |
| ASUS P7H55-M                         | 1        | 1.54%   |
| ASUS P6X58D-E                        | 1        | 1.54%   |
| ASUS P5KPL-AM SE                     | 1        | 1.54%   |
| ASUS M5A99X EVO R2.0                 | 1        | 1.54%   |
| ASUS M5A78L-M LX/BR                  | 1        | 1.54%   |
| ASUS M4N78-AM                        | 1        | 1.54%   |
| ASUS All Series                      | 1        | 1.54%   |
| ASRock Z590 Phantom Gaming 4/ac      | 1        | 1.54%   |
| ASRock X570 Extreme4                 | 1        | 1.54%   |
| ASRock P67 Extreme4                  | 1        | 1.54%   |
| ASRock M3A790GXH/128M                | 1        | 1.54%   |
| ASRock H81TM-ITX R2.0                | 1        | 1.54%   |
| ASRock B450 Pro4                     | 1        | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 3        | 4.62%   |
| ASUS TUF              | 3        | 4.62%   |
| HP Pavilion           | 2        | 3.08%   |
| Gigabyte X570         | 2        | 3.08%   |
| ASUS ROG              | 2        | 3.08%   |
| ASUS PRIME            | 2        | 3.08%   |
| Shuttle DS61          | 1        | 1.54%   |
| Pegatron KJ379AA-ABA  | 1        | 1.54%   |
| Pegatron IPMH61P1     | 1        | 1.54%   |
| MSI MS-7C83           | 1        | 1.54%   |
| MSI MS-7B79           | 1        | 1.54%   |
| MSI MS-7B46           | 1        | 1.54%   |
| MSI MS-7817           | 1        | 1.54%   |
| MSI MS-7693           | 1        | 1.54%   |
| MSI Elite             | 1        | 1.54%   |
| Intel X64             | 1        | 1.54%   |
| Intel H61             | 1        | 1.54%   |
| HP Z820               | 1        | 1.54%   |
| HP Z800               | 1        | 1.54%   |
| HP ENVY               | 1        | 1.54%   |
| HP EliteDesk          | 1        | 1.54%   |
| HP Compaq             | 1        | 1.54%   |
| HP 339A               | 1        | 1.54%   |
| Gigabyte Z390         | 1        | 1.54%   |
| Gigabyte Z270X-Gaming | 1        | 1.54%   |
| Gigabyte H81M-H       | 1        | 1.54%   |
| Gigabyte H310M        | 1        | 1.54%   |
| Gigabyte F2A55M-HD2   | 1        | 1.54%   |
| Gigabyte EP43T-USB3   | 1        | 1.54%   |
| Gigabyte B85M-DS3H-A  | 1        | 1.54%   |
| Gigabyte B85M-D3V-A   | 1        | 1.54%   |
| Gigabyte B450M        | 1        | 1.54%   |
| Gigabyte B450         | 1        | 1.54%   |
| Gigabyte AX370-Gaming | 1        | 1.54%   |
| Gigabyte AB350-Gaming | 1        | 1.54%   |
| Chuwi LarkBox         | 1        | 1.54%   |
| Biostar TH55XE        | 1        | 1.54%   |
| Biostar TA790GXE      | 1        | 1.54%   |
| ASUS P8H61-MX         | 1        | 1.54%   |
| ASUS P7H55-M          | 1        | 1.54%   |
| ASUS P6X58D-E         | 1        | 1.54%   |
| ASUS P5KPL-AM         | 1        | 1.54%   |
| ASUS M5A99X           | 1        | 1.54%   |
| ASUS M5A78L-M         | 1        | 1.54%   |
| ASUS M4N78-AM         | 1        | 1.54%   |
| ASUS All              | 1        | 1.54%   |
| ASRock Z590           | 1        | 1.54%   |
| ASRock X570           | 1        | 1.54%   |
| ASRock P67            | 1        | 1.54%   |
| ASRock M3A790GXH      | 1        | 1.54%   |
| ASRock H81TM-ITX      | 1        | 1.54%   |
| ASRock B450           | 1        | 1.54%   |
| ASRock AB350M         | 1        | 1.54%   |
| ASRock A320M-HDV      | 1        | 1.54%   |
| Apple MacPro5         | 1        | 1.54%   |
| Acer ConceptD         | 1        | 1.54%   |
| Acer Aspire           | 1        | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 9        | 13.85%  |
| 2020 | 8        | 12.31%  |
| 2010 | 8        | 12.31%  |
| 2017 | 7        | 10.77%  |
| 2012 | 6        | 9.23%   |
| 2018 | 5        | 7.69%   |
| 2013 | 5        | 7.69%   |
| 2015 | 4        | 6.15%   |
| 2011 | 4        | 6.15%   |
| 2021 | 3        | 4.62%   |
| 2009 | 2        | 3.08%   |
| 2008 | 2        | 3.08%   |
| 2016 | 1        | 1.54%   |
| 2014 | 1        | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 65       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 61       | 93.85%  |
| Enabled  | 4        | 6.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 65       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 19       | 29.23%  |
| 4.01-8.0    | 16       | 24.62%  |
| 32.01-64.0  | 16       | 24.62%  |
| 8.01-16.0   | 6        | 9.23%   |
| 3.01-4.0    | 5        | 7.69%   |
| 64.01-256.0 | 2        | 3.08%   |
| 1.01-2.0    | 1        | 1.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 28       | 41.18%  |
| 2.01-3.0   | 21       | 30.88%  |
| 3.01-4.0   | 10       | 14.71%  |
| 4.01-8.0   | 7        | 10.29%  |
| 32.01-64.0 | 1        | 1.47%   |
| 8.01-16.0  | 1        | 1.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 25       | 37.88%  |
| 1      | 22       | 33.33%  |
| 3      | 9        | 13.64%  |
| 4      | 8        | 12.12%  |
| 5      | 2        | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 66.15%  |
| Yes       | 22       | 33.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 64       | 98.46%  |
| No        | 1        | 1.54%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 52.31%  |
| No        | 31       | 47.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 61.54%  |
| Yes       | 25       | 38.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 7        | 10.61%  |
| Germany     | 7        | 10.61%  |
| UK          | 4        | 6.06%   |
| Russia      | 4        | 6.06%   |
| Mexico      | 4        | 6.06%   |
| Brazil      | 4        | 6.06%   |
| Indonesia   | 3        | 4.55%   |
| Canada      | 3        | 4.55%   |
| Argentina   | 3        | 4.55%   |
| Spain       | 2        | 3.03%   |
| Finland     | 2        | 3.03%   |
| Austria     | 2        | 3.03%   |
| Vietnam     | 1        | 1.52%   |
| Ukraine     | 1        | 1.52%   |
| Turkey      | 1        | 1.52%   |
| Sri Lanka   | 1        | 1.52%   |
| Poland      | 1        | 1.52%   |
| Netherlands | 1        | 1.52%   |
| Kenya       | 1        | 1.52%   |
| Italy       | 1        | 1.52%   |
| Greece      | 1        | 1.52%   |
| France      | 1        | 1.52%   |
| Estonia     | 1        | 1.52%   |
| Denmark     | 1        | 1.52%   |
| Czechia     | 1        | 1.52%   |
| Costa Rica  | 1        | 1.52%   |
| Colombia    | 1        | 1.52%   |
| China       | 1        | 1.52%   |
| Chile       | 1        | 1.52%   |
| Belgium     | 1        | 1.52%   |
| Belarus     | 1        | 1.52%   |
| Australia   | 1        | 1.52%   |
| Albania     | 1        | 1.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Vienna                  | 2        | 2.99%   |
| Znojmo                  | 1        | 1.49%   |
| Xicheng District        | 1        | 1.49%   |
| Wriezen                 | 1        | 1.49%   |
| Wigan                   | 1        | 1.49%   |
| Wattala                 | 1        | 1.49%   |
| Vit??ria                | 1        | 1.49%   |
| Villahermosa            | 1        | 1.49%   |
| Vantaa                  | 1        | 1.49%   |
| Vancouver               | 1        | 1.49%   |
| Ullastrell              | 1        | 1.49%   |
| Tucson                  | 1        | 1.49%   |
| Tolyatti                | 1        | 1.49%   |
| Toluca                  | 1        | 1.49%   |
| Tallinn                 | 1        | 1.49%   |
| Sukabumi                | 1        | 1.49%   |
| Staropyshminsk          | 1        | 1.49%   |
| Sparti                  | 1        | 1.49%   |
| Simferopol              | 1        | 1.49%   |
| S??o Paulo              | 1        | 1.49%   |
| Saskatoon               | 1        | 1.49%   |
| Santiago                | 1        | 1.49%   |
| San Jos?©               | 1        | 1.49%   |
| Rosario                 | 1        | 1.49%   |
| Roermond                | 1        | 1.49%   |
| Rio de Janeiro          | 1        | 1.49%   |
| Riesweiler              | 1        | 1.49%   |
| Rheinberg               | 1        | 1.49%   |
| Providence Forge        | 1        | 1.49%   |
| Potsdam                 | 1        | 1.49%   |
| Pleiku                  | 1        | 1.49%   |
| Paris                   | 1        | 1.49%   |
| Pargolovo Tretye        | 1        | 1.49%   |
| Oldenburg               | 1        | 1.49%   |
| Nairobi                 | 1        | 1.49%   |
| Morelia                 | 1        | 1.49%   |
| Montreal                | 1        | 1.49%   |
| Minsk                   | 1        | 1.49%   |
| Milan                   | 1        | 1.49%   |
| Mexico City             | 1        | 1.49%   |
| Medan                   | 1        | 1.49%   |
| Landshut                | 1        | 1.49%   |
| Krakow                  | 1        | 1.49%   |
| Klaukkala               | 1        | 1.49%   |
| Kediri                  | 1        | 1.49%   |
| Kazan?ˆ™                | 1        | 1.49%   |
| Kam?«z                  | 1        | 1.49%   |
| Izmir                   | 1        | 1.49%   |
| Itanhem                 | 1        | 1.49%   |
| Islington               | 1        | 1.49%   |
| Granollers              | 1        | 1.49%   |
| Fredersdorf             | 1        | 1.49%   |
| Fort Lauderdale         | 1        | 1.49%   |
| East Malvern            | 1        | 1.49%   |
| Copenhagen              | 1        | 1.49%   |
| Concepci??n del Uruguay | 1        | 1.49%   |
| Cocoa                   | 1        | 1.49%   |
| Brussels                | 1        | 1.49%   |
| Brooklyn                | 1        | 1.49%   |
| Bonnybridge             | 1        | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 25       | 34     | 21.74%  |
| Seagate                   | 17       | 21     | 14.78%  |
| Samsung Electronics       | 17       | 25     | 14.78%  |
| Kingston                  | 10       | 13     | 8.7%    |
| SanDisk                   | 9        | 10     | 7.83%   |
| Crucial                   | 7        | 10     | 6.09%   |
| OCZ                       | 3        | 3      | 2.61%   |
| Hitachi                   | 3        | 3      | 2.61%   |
| Unknown                   | 2        | 2      | 1.74%   |
| Toshiba                   | 2        | 2      | 1.74%   |
| Phison                    | 2        | 3      | 1.74%   |
| Patriot                   | 2        | 2      | 1.74%   |
| Intel                     | 2        | 2      | 1.74%   |
| USB3.1                    | 1        | 1      | 0.87%   |
| Transcend                 | 1        | 1      | 0.87%   |
| Team                      | 1        | 1      | 0.87%   |
| SK Hynix                  | 1        | 1      | 0.87%   |
| OCZ-VERTEX2               | 1        | 1      | 0.87%   |
| Micron/Crucial Technology | 1        | 2      | 0.87%   |
| Micron Technology         | 1        | 1      | 0.87%   |
| LITEON                    | 1        | 1      | 0.87%   |
| Kingmax                   | 1        | 1      | 0.87%   |
| Gigabyte Technology       | 1        | 1      | 0.87%   |
| GALAX                     | 1        | 1      | 0.87%   |
| China                     | 1        | 1      | 0.87%   |
| Apacer                    | 1        | 1      | 0.87%   |
| A-DATA Technology         | 1        | 1      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB       | 5        | 3.76%   |
| Kingston SA400S37240G 240GB SSD    | 4        | 3.01%   |
| Samsung NVMe SSD Drive 1TB         | 3        | 2.26%   |
| Kingston SA400S37480G 480GB SSD    | 3        | 2.26%   |
| WDC WD5000AAKX-003CA0 500GB        | 2        | 1.5%    |
| WDC WD10EZEX-60WN4A0 1TB           | 2        | 1.5%    |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 1.5%    |
| Seagate ST250DM000-1BD141 250GB    | 2        | 1.5%    |
| Samsung SSD 850 EVO 250GB          | 2        | 1.5%    |
| Intel NVMe SSD Drive 512GB         | 2        | 1.5%    |
| Crucial CT240BX500SSD1 240GB       | 2        | 1.5%    |
| Crucial CT240BX200SSD1 240GB       | 2        | 1.5%    |
| WDC WDS500G2B0A 500GB SSD          | 1        | 0.75%   |
| WDC WD6401AALS-00J7B0 640GB        | 1        | 0.75%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 1        | 0.75%   |
| WDC WD5000AAKX-603CA0 500GB        | 1        | 0.75%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 0.75%   |
| WDC WD5000AAKX-001CA0 500GB        | 1        | 0.75%   |
| WDC WD50 00LUCT-61C26Y0 500GB      | 1        | 0.75%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1        | 0.75%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1        | 0.75%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 0.75%   |
| WDC WD2500AAKS-00B3A0 250GB        | 1        | 0.75%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 0.75%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 0.75%   |
| WDC WD20EARS-00MVWB0 2TB           | 1        | 0.75%   |
| WDC WD15EARX-00PASB0 1TB           | 1        | 0.75%   |
| WDC WD10EZRX-00L4HB0 1TB           | 1        | 0.75%   |
| WDC WD10EZRX-00A8LB0 1TB           | 1        | 0.75%   |
| WDC WD10EZEX-75ZF5A0 1TB           | 1        | 0.75%   |
| WDC WD10EZEX-22MFCA0 1TB           | 1        | 0.75%   |
| WDC WD10EZEX-00RKKA0 1TB           | 1        | 0.75%   |
| WDC WD10EZEX-00KUWA0 1TB           | 1        | 0.75%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 0.75%   |
| WDC WD10EURX-63UY4Y0 1TB           | 1        | 0.75%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 1        | 0.75%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB | 1        | 0.75%   |
| USB3.1 Disk 500GB                  | 1        | 0.75%   |
| Unknown SD/MMC/MS PRO 128GB        | 1        | 0.75%   |
| Unknown MMC Card  128GB            | 1        | 0.75%   |
| Transcend TS512GMTS430S 512GB SSD  | 1        | 0.75%   |
| Toshiba MQ01ABD100 1TB             | 1        | 0.75%   |
| Toshiba DT01ACA100 1TB             | 1        | 0.75%   |
| Team L5 LITE SSD 120GB             | 1        | 0.75%   |
| SK Hynix SH920 2.5 7MM 256GB SSD   | 1        | 0.75%   |
| Seagate ST940210AS 40GB            | 1        | 0.75%   |
| Seagate ST500DM002-1BC142 500GB    | 1        | 0.75%   |
| Seagate ST380815AS 80GB            | 1        | 0.75%   |
| Seagate ST3808110AS 80GB           | 1        | 0.75%   |
| Seagate ST3500312CS 500GB          | 1        | 0.75%   |
| Seagate ST3160815AS 160GB          | 1        | 0.75%   |
| Seagate ST3160813AS 160GB          | 1        | 0.75%   |
| Seagate ST3160023AS 160GB          | 1        | 0.75%   |
| Seagate ST3000DM001-9YN166 3TB     | 1        | 0.75%   |
| Seagate ST250DM001 HD253GJ 250GB   | 1        | 0.75%   |
| Seagate ST2000NM0033 2TB           | 1        | 0.75%   |
| Seagate ST2000DM008-2FR102 2TB     | 1        | 0.75%   |
| Seagate ST2000DL003-9VT166 2TB     | 1        | 0.75%   |
| Seagate ST1000NM0053-1C1173 1TB    | 1        | 0.75%   |
| Seagate ST1000NM0011 1TB           | 1        | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 32     | 48.98%  |
| Seagate             | 16       | 19     | 32.65%  |
| Samsung Electronics | 3        | 3      | 6.12%   |
| Hitachi             | 3        | 3      | 6.12%   |
| Toshiba             | 2        | 2      | 4.08%   |
| Unknown             | 1        | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 8        | 10     | 18.18%  |
| Samsung Electronics | 7        | 9      | 15.91%  |
| Crucial             | 7        | 10     | 15.91%  |
| SanDisk             | 6        | 6      | 13.64%  |
| OCZ                 | 3        | 3      | 6.82%   |
| Patriot             | 2        | 2      | 4.55%   |
| WDC                 | 1        | 1      | 2.27%   |
| Transcend           | 1        | 1      | 2.27%   |
| Team                | 1        | 1      | 2.27%   |
| SK Hynix            | 1        | 1      | 2.27%   |
| OCZ-VERTEX2         | 1        | 1      | 2.27%   |
| LITEON              | 1        | 1      | 2.27%   |
| Kingmax             | 1        | 1      | 2.27%   |
| GALAX               | 1        | 1      | 2.27%   |
| China               | 1        | 1      | 2.27%   |
| Apacer              | 1        | 1      | 2.27%   |
| A-DATA Technology   | 1        | 1      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 40       | 60     | 40%     |
| SSD     | 36       | 51     | 36%     |
| NVMe    | 21       | 31     | 21%     |
| Unknown | 2        | 2      | 2%      |
| MMC     | 1        | 1      | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 57       | 107    | 68.67%  |
| NVMe | 21       | 31     | 25.3%   |
| SAS  | 4        | 6      | 4.82%   |
| MMC  | 1        | 1      | 1.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 48       | 72     | 60%     |
| 0.51-1.0   | 24       | 30     | 30%     |
| 1.01-2.0   | 5        | 6      | 6.25%   |
| 3.01-4.0   | 2        | 2      | 2.5%    |
| 2.01-3.0   | 1        | 1      | 1.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 18       | 27.69%  |
| 101-250        | 17       | 26.15%  |
| 501-1000       | 9        | 13.85%  |
| 21-50          | 7        | 10.77%  |
| 2001-3000      | 4        | 6.15%   |
| 1001-2000      | 4        | 6.15%   |
| More than 3000 | 3        | 4.62%   |
| 51-100         | 3        | 4.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 32       | 47.76%  |
| 21-50     | 11       | 16.42%  |
| 51-100    | 9        | 13.43%  |
| 101-250   | 5        | 7.46%   |
| 251-500   | 4        | 5.97%   |
| 2001-3000 | 2        | 2.99%   |
| 1001-2000 | 2        | 2.99%   |
| 501-1000  | 2        | 2.99%   |

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
| Detected | 58       | 124    | 82.86%  |
| Works    | 7        | 13     | 10%     |
| Malfunc  | 5        | 8      | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 42       | 44.21%  |
| AMD                         | 21       | 22.11%  |
| Samsung Electronics         | 10       | 10.53%  |
| Sandisk                     | 5        | 5.26%   |
| Phison Electronics          | 2        | 2.11%   |
| Marvell Technology Group    | 2        | 2.11%   |
| Kingston Technology Company | 2        | 2.11%   |
| JMicron Technology          | 2        | 2.11%   |
| ASMedia Technology          | 2        | 2.11%   |
| VIA Technologies            | 1        | 1.05%   |
| Seagate Technology          | 1        | 1.05%   |
| Nvidia                      | 1        | 1.05%   |
| Micron/Crucial Technology   | 1        | 1.05%   |
| Micron Technology           | 1        | 1.05%   |
| LSI Logic / Symbios Logic   | 1        | 1.05%   |
| Broadcom / LSI              | 1        | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 11.38%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 6.5%    |
| Intel SATA Controller [RAID mode]                                                       | 5        | 4.07%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 4.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 3.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 3.25%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 2.44%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 2.44%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 2.44%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.44%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 2.44%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.63%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.63%   |
| JMicron JMB368 IDE controller                                                           | 2        | 1.63%   |
| Intel SSD 660P Series                                                                   | 2        | 1.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 1.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.63%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.63%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.63%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.63%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.81%   |
| Seagate FireCuda 510 SSD                                                                | 1        | 0.81%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.81%   |
| Sandisk WD Black NVMe SSD                                                               | 1        | 0.81%   |
| Sandisk Non-Volatile memory controller                                                  | 1        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.81%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.81%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.81%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.81%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 0.81%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.81%   |
| Micron Non-Volatile memory controller                                                   | 1        | 0.81%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.81%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1        | 0.81%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.81%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.81%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.81%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 0.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.81%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.81%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 0.81%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 0.81%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1        | 0.81%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 0.81%   |
| AMD FCH IDE Controller                                                                  | 1        | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 49       | 53.85%  |
| NVMe | 21       | 23.08%  |
| IDE  | 13       | 14.29%  |
| RAID | 6        | 6.59%   |
| SAS  | 1        | 1.1%    |
| SCSI | 1        | 1.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 42       | 64.62%  |
| AMD    | 23       | 35.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor             | 4        | 6.15%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 2        | 3.08%   |
| Intel Core i3 CPU 530 @ 2.93GHz                | 2        | 3.08%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 2        | 3.08%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 3.08%   |
| Intel Xeon CPU X5660 @ 2.80GHz                 | 1        | 1.54%   |
| Intel Xeon CPU E5520 @ 2.27GHz                 | 1        | 1.54%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz             | 1        | 1.54%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz             | 1        | 1.54%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz         | 1        | 1.54%   |
| Intel Pentium CPU G620 @ 2.60GHz               | 1        | 1.54%   |
| Intel Pentium CPU G3260 @ 3.30GHz              | 1        | 1.54%   |
| Intel Core i7-9700 CPU @ 3.00GHz               | 1        | 1.54%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 1.54%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 1.54%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 1.54%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 1.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 1.54%   |
| Intel Core i7-4785T CPU @ 2.20GHz              | 1        | 1.54%   |
| Intel Core i7-10700F CPU @ 2.90GHz             | 1        | 1.54%   |
| Intel Core i7 CPU 950 @ 3.07GHz                | 1        | 1.54%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 1.54%   |
| Intel Core i5-9400F CPU @ 2.90GHz              | 1        | 1.54%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1        | 1.54%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 1        | 1.54%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.54%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 1.54%   |
| Intel Core i5-3550 CPU @ 3.30GHz               | 1        | 1.54%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 1        | 1.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 1.54%   |
| Intel Core i5-2320 CPU @ 3.00GHz               | 1        | 1.54%   |
| Intel Core i5-10600K CPU @ 4.10GHz             | 1        | 1.54%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1        | 1.54%   |
| Intel Core i5 CPU 750 @ 2.67GHz                | 1        | 1.54%   |
| Intel Core i3-6100T CPU @ 3.20GHz              | 1        | 1.54%   |
| Intel Core 2 Quad CPU Q9500 @ 2.83GHz          | 1        | 1.54%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz           | 1        | 1.54%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1        | 1.54%   |
| Intel Celeron G4930 CPU @ 3.20GHz              | 1        | 1.54%   |
| Intel Celeron CPU G530 @ 2.40GHz               | 1        | 1.54%   |
| Intel Celeron CPU G1610 @ 2.60GHz              | 1        | 1.54%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 1        | 1.54%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz         | 1        | 1.54%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 1.54%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 1.54%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 1        | 1.54%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1        | 1.54%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 1.54%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1        | 1.54%   |
| AMD Phenom II X4 925 Processor                 | 1        | 1.54%   |
| AMD Phenom 9850 Quad-Core Processor            | 1        | 1.54%   |
| AMD FX-8350 Eight-Core Processor               | 1        | 1.54%   |
| AMD FX-8320 Eight-Core Processor               | 1        | 1.54%   |
| AMD FX-6100 Six-Core Processor                 | 1        | 1.54%   |
| AMD Athlon II X4 620 Processor                 | 1        | 1.54%   |
| AMD A6-9500E RADEON R5, 6 COMPUTE CORES 2C+4G  | 1        | 1.54%   |
| AMD A4-4000 APU with Radeon HD Graphics        | 1        | 1.54%   |
| AMD A10-9700 RADEON R7, 10 COMPUTE CORES 4C+6G | 1        | 1.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 13       | 20%     |
| Intel Core i7      | 9        | 13.85%  |
| AMD Ryzen 7        | 7        | 10.77%  |
| Intel Core i3      | 5        | 7.69%   |
| Intel Xeon         | 4        | 6.15%   |
| Intel Celeron      | 4        | 6.15%   |
| AMD Ryzen 5        | 4        | 6.15%   |
| AMD FX             | 3        | 4.62%   |
| Other              | 2        | 3.08%   |
| Intel Pentium      | 2        | 3.08%   |
| AMD Ryzen 9        | 2        | 3.08%   |
| Intel Pentium Dual | 1        | 1.54%   |
| Intel Core 2 Quad  | 1        | 1.54%   |
| Intel Core 2 Duo   | 1        | 1.54%   |
| AMD Ryzen 3        | 1        | 1.54%   |
| AMD Phenom II X4   | 1        | 1.54%   |
| AMD Phenom         | 1        | 1.54%   |
| AMD Athlon II X4   | 1        | 1.54%   |
| AMD A6             | 1        | 1.54%   |
| AMD A4             | 1        | 1.54%   |
| AMD A10            | 1        | 1.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 22       | 33.85%  |
| 8      | 13       | 20%     |
| 2      | 13       | 20%     |
| 6      | 10       | 15.38%  |
| 12     | 4        | 6.15%   |
| 1      | 2        | 3.08%   |
| 3      | 1        | 1.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 95.38%  |
| 2      | 3        | 4.62%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 40       | 61.54%  |
| 1      | 25       | 38.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 65       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 8        | 12.12%  |
| 0x206a7    | 6        | 9.09%   |
| 0x08701021 | 5        | 7.58%   |
| 0x0800820d | 4        | 6.06%   |
| Unknown    | 4        | 6.06%   |
| 0x906ea    | 3        | 4.55%   |
| 0xa0671    | 2        | 3.03%   |
| 0xa0655    | 2        | 3.03%   |
| 0x306a9    | 2        | 3.03%   |
| 0x206d7    | 2        | 3.03%   |
| 0x20652    | 2        | 3.03%   |
| 0x106a5    | 2        | 3.03%   |
| 0x08701013 | 2        | 3.03%   |
| 0x0600611a | 2        | 3.03%   |
| 0x06000852 | 2        | 3.03%   |
| 0xa0653    | 1        | 1.52%   |
| 0x906ed    | 1        | 1.52%   |
| 0x906eb    | 1        | 1.52%   |
| 0x906e9    | 1        | 1.52%   |
| 0x706a8    | 1        | 1.52%   |
| 0x6fd      | 1        | 1.52%   |
| 0x6fb      | 1        | 1.52%   |
| 0x506e3    | 1        | 1.52%   |
| 0x206c2    | 1        | 1.52%   |
| 0x106e5    | 1        | 1.52%   |
| 0x1067a    | 1        | 1.52%   |
| 0x0a201016 | 1        | 1.52%   |
| 0x08101007 | 1        | 1.52%   |
| 0x0800111c | 1        | 1.52%   |
| 0x06001119 | 1        | 1.52%   |
| 0x0600063e | 1        | 1.52%   |
| 0x010000db | 1        | 1.52%   |
| 0x01000095 | 1        | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 9        | 13.85%  |
| Haswell       | 8        | 12.31%  |
| Zen 2         | 7        | 10.77%  |
| KabyLake      | 7        | 10.77%  |
| Zen+          | 4        | 6.15%   |
| Westmere      | 3        | 4.62%   |
| Piledriver    | 3        | 4.62%   |
| Nehalem       | 3        | 4.62%   |
| K10           | 3        | 4.62%   |
| CometLake     | 3        | 4.62%   |
| Zen           | 2        | 3.08%   |
| IvyBridge     | 2        | 3.08%   |
| Icelake       | 2        | 3.08%   |
| Excavator     | 2        | 3.08%   |
| Core          | 2        | 3.08%   |
| Zen 3         | 1        | 1.54%   |
| Skylake       | 1        | 1.54%   |
| Penryn        | 1        | 1.54%   |
| Goldmont plus | 1        | 1.54%   |
| Bulldozer     | 1        | 1.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| AMD              | 27       | 38.03%  |
| Nvidia           | 25       | 35.21%  |
| Intel            | 17       | 23.94%  |
| Conexant Systems | 1        | 1.41%   |
| ATI Technologies | 1        | 1.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 9.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 6.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 5.56%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 2.78%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.78%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 2.78%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 2.78%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 2.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.78%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 2.78%   |
| AMD RS780D [Radeon HD 3300]                                                 | 2        | 2.78%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 2.78%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 2.78%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 2        | 2.78%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.39%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.39%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.39%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.39%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 1.39%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.39%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.39%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.39%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.39%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.39%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.39%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 1.39%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.39%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 1.39%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.39%   |
| Intel HD Graphics 530                                                       | 1        | 1.39%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.39%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.39%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.39%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.39%   |
| Conexant Systems Conexant Display controller                                | 1        | 1.39%   |
| ATI Technologies Wani [Radeon R5/R6/R7 Graphics]                            | 1        | 1.39%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.39%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 1.39%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 1.39%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 1        | 1.39%   |
| AMD RV770 [Radeon HD 4850]                                                  | 1        | 1.39%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 1        | 1.39%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.39%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 1.39%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                            | 1        | 1.39%   |
| AMD Cypress LE [Radeon HD 5830]                                             | 1        | 1.39%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| 1 x Nvidia                     | 23       | 35.38%  |
| 1 x AMD                        | 23       | 35.38%  |
| 1 x Intel                      | 14       | 21.54%  |
| 2 x AMD + 1 x Conexant Systems | 1        | 1.54%   |
| 2 x AMD                        | 1        | 1.54%   |
| Intel + Nvidia                 | 1        | 1.54%   |
| Intel + AMD                    | 1        | 1.54%   |
| AMD + Nvidia                   | 1        | 1.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 53       | 79.1%   |
| Proprietary | 13       | 19.4%   |
| Unknown     | 1        | 1.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 27.27%  |
| 1.01-2.0   | 13       | 19.7%   |
| 7.01-8.0   | 11       | 16.67%  |
| 3.01-4.0   | 10       | 15.15%  |
| 0.51-1.0   | 6        | 9.09%   |
| 0.01-0.5   | 3        | 4.55%   |
| 5.01-6.0   | 2        | 3.03%   |
| 8.01-16.0  | 2        | 3.03%   |
| 2.01-3.0   | 1        | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 18.06%  |
| Hewlett-Packard      | 9        | 12.5%   |
| Goldstar             | 8        | 11.11%  |
| BenQ                 | 6        | 8.33%   |
| Acer                 | 6        | 8.33%   |
| Dell                 | 5        | 6.94%   |
| AOC                  | 4        | 5.56%   |
| Ancor Communications | 4        | 5.56%   |
| Vizio                | 2        | 2.78%   |
| ViewSonic            | 2        | 2.78%   |
| LG Electronics       | 2        | 2.78%   |
| TBD                  | 1        | 1.39%   |
| SKY                  | 1        | 1.39%   |
| Philips              | 1        | 1.39%   |
| MSI                  | 1        | 1.39%   |
| Lenovo Group Limited | 1        | 1.39%   |
| Lenovo               | 1        | 1.39%   |
| HOP                  | 1        | 1.39%   |
| Grundig              | 1        | 1.39%   |
| Denver               | 1        | 1.39%   |
| AUS                  | 1        | 1.39%   |
| Unknown              | 1        | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                        | 2        | 2.56%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                      | 1        | 1.28%   |
| Vizio E190VA VIZ0067 1360x768 410x230mm 18.5-inch                      | 1        | 1.28%   |
| ViewSonic VA2055 Series VSC3C31 1920x1080 435x239mm 19.5-inch          | 1        | 1.28%   |
| ViewSonic LCD Monitor VSC732E 1920x1080 520x290mm 23.4-inch            | 1        | 1.28%   |
| TBD HDMI TBD3148 1600x900 344x193mm 15.5-inch                          | 1        | 1.28%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                   | 1        | 1.28%   |
| Samsung Electronics U32J59x SAM0F33 1920x2160 700x390mm 31.5-inch      | 1        | 1.28%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch      | 1        | 1.28%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch      | 1        | 1.28%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch   | 1        | 1.28%   |
| Samsung Electronics S27H85x SAM0E0E 2560x1440 597x336mm 27.0-inch      | 1        | 1.28%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch      | 1        | 1.28%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 1        | 1.28%   |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch      | 1        | 1.28%   |
| Samsung Electronics LCD Monitor SAM705B 1920x1080 1210x680mm 54.6-inch | 1        | 1.28%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1        | 1.28%   |
| Samsung Electronics LCD Monitor S24F350 5760x1080                      | 1        | 1.28%   |
| Samsung Electronics LCD Monitor S24F350                                | 1        | 1.28%   |
| Samsung Electronics LCD Monitor C24F390 1920x1080                      | 1        | 1.28%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch     | 1        | 1.28%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch     | 1        | 1.28%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch                | 1        | 1.28%   |
| MSI MAG341CQ MSI1462 3440x1440 800x330mm 34.1-inch                     | 1        | 1.28%   |
| LG Electronics LCD Monitor LG IPS FULLHD                               | 1        | 1.28%   |
| LG Electronics LCD Monitor 25UM58G 2560x1080                           | 1        | 1.28%   |
| Lenovo LEN LS1922wA LEN0A14 1366x768 410x230mm 18.5-inch               | 1        | 1.28%   |
| Lenovo Group Limited LCD Monitor LEN D32q-20B 4480x1440                | 1        | 1.28%   |
| HOP DVI HOP2700 1920x1080 597x336mm 27.0-inch                          | 1        | 1.28%   |
| Hewlett-Packard P204v HPN3634 1600x900 432x240mm 19.5-inch             | 1        | 1.28%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 546x352mm 25.6-inch          | 1        | 1.28%   |
| Hewlett-Packard LE2002x HWP2964 1600x900 443x249mm 20.0-inch           | 1        | 1.28%   |
| Hewlett-Packard LCD Monitor LA2306 4480x1440                           | 1        | 1.28%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch             | 1        | 1.28%   |
| Hewlett-Packard Compaq WF1907 HWP26A4 1440x900 408x255mm 18.9-inch     | 1        | 1.28%   |
| Hewlett-Packard 27f HPN354C 1920x1080 598x336mm 27.0-inch              | 1        | 1.28%   |
| Hewlett-Packard 24x HPN3635 1920x1080 527x297mm 23.8-inch              | 1        | 1.28%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch             | 1        | 1.28%   |
| Grundig UHD GRU4448 3840x2160 1210x680mm 54.6-inch                     | 1        | 1.28%   |
| Goldstar W2253 GSM56DC 1920x1080 510x290mm 23.1-inch                   | 1        | 1.28%   |
| Goldstar W2043 GSM4E9E 1600x900 443x249mm 20.0-inch                    | 1        | 1.28%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                    | 1        | 1.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch               | 1        | 1.28%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                 | 1        | 1.28%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 1.28%   |
| Goldstar LG FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch              | 1        | 1.28%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                 | 1        | 1.28%   |
| Denver UXGA-100-C LHC2900 2560x1080 681x287mm 29.1-inch                | 1        | 1.28%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                      | 1        | 1.28%   |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                      | 1        | 1.28%   |
| Dell U2312HM DEL4073 1920x1080 510x290mm 23.1-inch                     | 1        | 1.28%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                      | 1        | 1.28%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                      | 1        | 1.28%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                      | 1        | 1.28%   |
| Dell 1707FPV DEL4021 1280x1024 338x270mm 17.0-inch                     | 1        | 1.28%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                     | 1        | 1.28%   |
| BenQ LCD Monitor ZOWIE XL LCD 3840x1080                                | 1        | 1.28%   |
| BenQ LCD Monitor PD2700U 3840x2160                                     | 1        | 1.28%   |
| BenQ LCD BNQ8024 2560x1440 600x340mm 27.2-inch                         | 1        | 1.28%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 1        | 1.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 29       | 43.28%  |
| 3840x2160 (4K)     | 7        | 10.45%  |
| 2560x1440 (QHD)    | 5        | 7.46%   |
| 1600x900 (HD+)     | 4        | 5.97%   |
| Unknown            | 4        | 5.97%   |
| 3840x1080          | 3        | 4.48%   |
| 2560x1080          | 3        | 4.48%   |
| 1440x900 (WXGA+)   | 3        | 4.48%   |
| 1680x1050 (WSXGA+) | 2        | 2.99%   |
| 5760x1080          | 1        | 1.49%   |
| 5120x1440          | 1        | 1.49%   |
| 4480x1440          | 1        | 1.49%   |
| 3440x1440          | 1        | 1.49%   |
| 1920x1200 (WUXGA)  | 1        | 1.49%   |
| 1366x768 (WXGA)    | 1        | 1.49%   |
| 1280x1024 (SXGA)   | 1        | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 10       | 14.29%  |
| Unknown | 10       | 14.29%  |
| 27      | 9        | 12.86%  |
| 23      | 8        | 11.43%  |
| 24      | 5        | 7.14%   |
| 19      | 4        | 5.71%   |
| 31      | 3        | 4.29%   |
| 54      | 2        | 2.86%   |
| 49      | 2        | 2.86%   |
| 40      | 2        | 2.86%   |
| 34      | 2        | 2.86%   |
| 20      | 2        | 2.86%   |
| 17      | 2        | 2.86%   |
| 72      | 1        | 1.43%   |
| 33      | 1        | 1.43%   |
| 32      | 1        | 1.43%   |
| 29      | 1        | 1.43%   |
| 28      | 1        | 1.43%   |
| 25      | 1        | 1.43%   |
| 22      | 1        | 1.43%   |
| 18      | 1        | 1.43%   |
| 15      | 1        | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 19       | 28.36%  |
| 401-500     | 17       | 25.37%  |
| Unknown     | 10       | 14.93%  |
| 601-700     | 7        | 10.45%  |
| 701-800     | 4        | 5.97%   |
| 1001-1500   | 4        | 5.97%   |
| 801-900     | 2        | 2.99%   |
| 301-350     | 2        | 2.99%   |
| 351-400     | 1        | 1.49%   |
| 1501-2000   | 1        | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 39       | 63.93%  |
| Unknown | 10       | 16.39%  |
| 21/9    | 4        | 6.56%   |
| 16/10   | 4        | 6.56%   |
| 32/9    | 2        | 3.28%   |
| 5/4     | 1        | 1.64%   |
| 3/2     | 1        | 1.64%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 19       | 27.54%  |
| 301-350        | 10       | 14.49%  |
| 151-200        | 10       | 14.49%  |
| Unknown        | 10       | 14.49%  |
| 351-500        | 7        | 10.14%  |
| 501-1000       | 4        | 5.8%    |
| More than 1000 | 3        | 4.35%   |
| 251-300        | 2        | 2.9%    |
| 141-150        | 2        | 2.9%    |
| 131-140        | 1        | 1.45%   |
| 101-110        | 1        | 1.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 37       | 56.92%  |
| 101-120 | 13       | 20%     |
| Unknown | 10       | 15.38%  |
| 1-50    | 3        | 4.62%   |
| 121-160 | 2        | 3.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 50       | 75.76%  |
| 2     | 11       | 16.67%  |
| 3     | 3        | 4.55%   |
| 0     | 2        | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 42       | 44.68%  |
| Intel                    | 23       | 24.47%  |
| TP-Link                  | 7        | 7.45%   |
| Ralink Technology        | 4        | 4.26%   |
| Xiaomi                   | 3        | 3.19%   |
| Qualcomm Atheros         | 3        | 3.19%   |
| Broadcom                 | 3        | 3.19%   |
| Samsung Electronics      | 1        | 1.06%   |
| Ralink                   | 1        | 1.06%   |
| Nvidia                   | 1        | 1.06%   |
| NetGear                  | 1        | 1.06%   |
| Mercucys                 | 1        | 1.06%   |
| MediaTek                 | 1        | 1.06%   |
| Marvell Technology Group | 1        | 1.06%   |
| Edimax Technology        | 1        | 1.06%   |
| ASUSTek Computer         | 1        | 1.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35       | 32.41%  |
| Intel I211 Gigabit Network Connection                             | 5        | 4.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 3.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.78%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 2.78%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 2.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 1.85%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2        | 1.85%   |
| TP-Link 802.11ac NIC                                              | 2        | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.85%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.85%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.85%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 1.85%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                             | 1        | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 0.93%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.93%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.93%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 0.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.93%   |
| Ralink RT5592 PCIe Wireless Network Adapter                       | 1        | 0.93%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.93%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.93%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]            | 1        | 0.93%   |
| Mercucys 802.11n NIC                                              | 1        | 0.93%   |
| MediaTek Infinix HOT 10T                                          | 1        | 0.93%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.93%   |
| Intel Wireless-AC 9260                                            | 1        | 0.93%   |
| Intel Wireless 7260                                               | 1        | 0.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1        | 0.93%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1        | 0.93%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.93%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.93%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.93%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 1        | 0.93%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.93%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]    | 1        | 0.93%   |

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
| TP-Link 802.11ac WLAN Adapter                                  | 2        | 5.41%   |
| TP-Link 802.11ac NIC                                           | 2        | 5.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 5.41%   |
| Intel Wi-Fi 6 AX200                                            | 2        | 5.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2        | 5.41%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1        | 2.7%    |
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
| Realtek Semiconductor    | 40       | 57.97%  |
| Intel                    | 19       | 27.54%  |
| Xiaomi                   | 3        | 4.35%   |
| Qualcomm Atheros         | 2        | 2.9%    |
| Samsung Electronics      | 1        | 1.45%   |
| Nvidia                   | 1        | 1.45%   |
| MediaTek                 | 1        | 1.45%   |
| Marvell Technology Group | 1        | 1.45%   |
| Broadcom                 | 1        | 1.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35       | 49.3%   |
| Intel I211 Gigabit Network Connection                             | 5        | 7.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 5.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 4.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 4.23%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 4.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.82%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.82%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.41%   |
| Nvidia MCP77 Ethernet                                             | 1        | 1.41%   |
| MediaTek Infinix HOT 10T                                          | 1        | 1.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.41%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.41%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.41%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.41%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.41%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 64       | 65.31%  |
| WiFi     | 34       | 34.69%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 62       | 68.89%  |
| WiFi     | 28       | 31.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 42       | 64.62%  |
| 2     | 21       | 32.31%  |
| 3     | 1        | 1.54%   |
| 0     | 1        | 1.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 49       | 74.24%  |
| Yes  | 17       | 25.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 10       | 38.46%  |
| Cambridge Silicon Radio | 9        | 34.62%  |
| Realtek Semiconductor   | 2        | 7.69%   |
| Apple                   | 2        | 7.69%   |
| Broadcom                | 1        | 3.85%   |
| Belkin Components       | 1        | 3.85%   |
| ASUSTek Computer        | 1        | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 34.62%  |
| Intel Bluetooth Device                              | 4        | 15.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 11.54%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 7.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.85%   |
| Intel AX210 Bluetooth                               | 1        | 3.85%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1        | 3.85%   |
| Belkin Components Bluetooth Mini Dongle             | 1        | 3.85%   |
| ASUS Bluetooth Radio                                | 1        | 3.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 3.85%   |
| Apple Bluetooth USB Host Controller                 | 1        | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 40       | 33.9%   |
| AMD                                  | 33       | 27.97%  |
| Nvidia                               | 24       | 20.34%  |
| C-Media Electronics                  | 6        | 5.08%   |
| Creative Labs                        | 3        | 2.54%   |
| Logitech                             | 2        | 1.69%   |
| Generalplus Technology               | 2        | 1.69%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.85%   |
| Razer USA                            | 1        | 0.85%   |
| JMTek                                | 1        | 0.85%   |
| HECATE G2 GAMING HEADSET             | 1        | 0.85%   |
| Focusrite-Novation                   | 1        | 0.85%   |
| Creative Technology                  | 1        | 0.85%   |
| ATI Technologies                     | 1        | 0.85%   |
| ASUSTek Computer                     | 1        | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 8        | 5.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 7        | 5.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7        | 5.07%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 7        | 5.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5        | 3.62%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 2.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 2.9%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 4        | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 2.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 2.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 3        | 2.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 1.45%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 1.45%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2        | 1.45%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 1.45%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 1.45%   |
| Nvidia GA102 High Definition Audio Controller                                     | 2        | 1.45%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 1.45%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 1.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2        | 1.45%   |
| Generalplus Technology Usb Audio Device                                           | 2        | 1.45%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                        | 2        | 1.45%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 2        | 1.45%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 2        | 1.45%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 2        | 1.45%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.45%   |
| Thesycon Systemsoftware & Consulting E30                                          | 1        | 0.72%   |
| Razer USA Razer USB Audio Controller                                              | 1        | 0.72%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.72%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 0.72%   |
| Nvidia TU104 HD Audio Controller                                                  | 1        | 0.72%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 0.72%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 0.72%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 0.72%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 0.72%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.72%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 0.72%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1        | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1        | 0.72%   |
| Nvidia GF104 High Definition Audio Controller                                     | 1        | 0.72%   |
| Logitech G930                                                                     | 1        | 0.72%   |
| Logitech G733 Gaming Headset                                                      | 1        | 0.72%   |
| JMTek USB PnP Audio Device                                                        | 1        | 0.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1        | 0.72%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 0.72%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 0.72%   |
| Intel Audio device                                                                | 1        | 0.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 0.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 0.72%   |
| HECATE G2 GAMING HEADSET HECATE G2 GAMING HEADSET                                 | 1        | 0.72%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                 | 1        | 0.72%   |
| Creative Technology Sound BlasterX Kratos S5                                      | 1        | 0.72%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]         | 1        | 0.72%   |
| C-Media Electronics TONOR TC-777 Audio Device                                     | 1        | 0.72%   |
| C-Media Electronics SABAJ D3                                                      | 1        | 0.72%   |
| C-Media Electronics Multimedia Headset [Gigaware by Ignition L.P.]                | 1        | 0.72%   |

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


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 5%      |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s     | 1        | 5%      |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s             | 1        | 5%      |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s | 1        | 5%      |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s   | 1        | 5%      |
| Neo Forza RAM NMUD380D81-1600D 8GB DIMM DDR3 1333MT/s    | 1        | 5%      |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 5%      |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s      | 1        | 5%      |
| Kingston RAM KHX1866C10D3/4G 4096MB DIMM DDR3 1867MT/s   | 1        | 5%      |
| Kingston RAM 99U5471-052.A 8GB DIMM DDR3 1333MT/s        | 1        | 5%      |
| Kingston RAM 99U5458-001.A00LF 2048MB DIMM DDR3 1600MT/s | 1        | 5%      |
| Kingston RAM 99U5403-159.A01LF 8192MB DIMM DDR3 1333MT/s | 1        | 5%      |
| Kingston RAM 9965516-069.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 5%      |
| Kingston RAM 9965516-003.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 5%      |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 1        | 5%      |
| G.Skill RAM F3-1866C11-8GRSL 8GB SODIMM DDR3 1867MT/s    | 1        | 5%      |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1800MT/s     | 1        | 5%      |
| Crucial RAM BLS8G4D26BFSCK.8FD 8GB DIMM DDR4 2400MT/s    | 1        | 5%      |
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
| 3007  | 1        | 5.56%   |
| 3000  | 1        | 5.56%   |
| 2666  | 1        | 5.56%   |
| 2133  | 1        | 5.56%   |
| 1867  | 1        | 5.56%   |
| 1800  | 1        | 5.56%   |
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
| Sunplus FHD Camera Microphone   | 1        | 5.26%   |
| Sunplus Aukey-PC-LM1E Camera    | 1        | 5.26%   |
| Microsoft Xbox NUI Camera       | 1        | 5.26%   |
| Microsoft LifeCam HD-3000       | 1        | 5.26%   |
| Microdia Webcam Vitade AF       | 1        | 5.26%   |
| Microdia USB Live camera        | 1        | 5.26%   |
| Microdia Integrated Camera      | 1        | 5.26%   |
| Logitech Webcam C310            | 1        | 5.26%   |
| Logitech HD Webcam C615         | 1        | 5.26%   |
| Logitech HD Pro Webcam C920     | 1        | 5.26%   |
| Logitech C505 HD Webcam         | 1        | 5.26%   |
| Logitech BRIO 4K Stream Edition | 1        | 5.26%   |
| Logitech B525 HD Webcam         | 1        | 5.26%   |
| Generalplus GENERAL WEBCAM      | 1        | 5.26%   |
| Creative Live! Cam Sync 1080p   | 1        | 5.26%   |
| Apple iPhone 5/5C/5S/6/SE       | 1        | 5.26%   |

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
| 0     | 60       | 90.91%  |
| 1     | 6        | 9.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 4        | 66.67%  |
| Graphics card            | 1        | 16.67%  |
| Communication controller | 1        | 16.67%  |

