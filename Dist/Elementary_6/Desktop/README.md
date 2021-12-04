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
| 5.11.0-40-generic    | 15       | 26.32%  |
| 5.11.0-27-generic    | 10       | 17.54%  |
| 5.11.0-37-generic    | 6        | 10.53%  |
| 5.11.0-38-generic    | 5        | 8.77%   |
| 5.11.0-25-generic    | 5        | 8.77%   |
| 5.11.0-41-generic    | 4        | 7.02%   |
| 5.8.0-50-generic     | 3        | 5.26%   |
| 5.11.0-36-generic    | 2        | 3.51%   |
| 5.11.0-34-generic    | 2        | 3.51%   |
| 5.8.0-63-generic     | 1        | 1.75%   |
| 5.8.0-55-generic     | 1        | 1.75%   |
| 5.4.0-58-generic     | 1        | 1.75%   |
| 5.4.0-56-generic     | 1        | 1.75%   |
| 5.11.0-41-lowlatency | 1        | 1.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 49       | 87.5%   |
| 5.8.0   | 5        | 8.93%   |
| 5.4.0   | 2        | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 49       | 87.5%   |
| 5.8     | 5        | 8.93%   |
| 5.4     | 2        | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 56       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 50       | 89.29%  |
| Unknown  | 4        | 7.14%   |
| MATE     | 1        | 1.79%   |
| GNOME    | 1        | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 56       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 49       | 87.5%   |
| LightDM | 4        | 7.14%   |
| TDM     | 3        | 5.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 26       | 46.43%  |
| de_DE | 8        | 14.29%  |
| es_ES | 6        | 10.71%  |
| ru_RU | 4        | 7.14%   |
| pt_BR | 2        | 3.57%   |
| en_GB | 2        | 3.57%   |
| zh_CN | 1        | 1.79%   |
| tr_TR | 1        | 1.79%   |
| it_IT | 1        | 1.79%   |
| fr_FR | 1        | 1.79%   |
| es_MX | 1        | 1.79%   |
| en_AU | 1        | 1.79%   |
| de_CH | 1        | 1.79%   |
| ca_ES | 1        | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 31       | 55.36%  |
| BIOS | 25       | 44.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 53       | 94.64%  |
| Btrfs | 3        | 5.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 89.29%  |
| MBR     | 3        | 5.36%   |
| GPT     | 3        | 5.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 92.86%  |
| Yes       | 4        | 7.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 82.14%  |
| Yes       | 10       | 17.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 13       | 23.21%  |
| ASUSTek Computer    | 13       | 23.21%  |
| Hewlett-Packard     | 8        | 14.29%  |
| ASRock              | 6        | 10.71%  |
| MSI                 | 5        | 8.93%   |
| Intel               | 2        | 3.57%   |
| Dell                | 2        | 3.57%   |
| Biostar             | 2        | 3.57%   |
| Shuttle             | 1        | 1.79%   |
| Pegatron            | 1        | 1.79%   |
| Chuwi               | 1        | 1.79%   |
| Apple               | 1        | 1.79%   |
| Acer                | 1        | 1.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Shuttle DS61                         | 1        | 1.79%   |
| Pegatron KJ379AA-ABA a6400f          | 1        | 1.79%   |
| MSI MS-7C83                          | 1        | 1.79%   |
| MSI MS-7B79                          | 1        | 1.79%   |
| MSI MS-7817                          | 1        | 1.79%   |
| MSI MS-7693                          | 1        | 1.79%   |
| MSI Elite 7100 Microtower PC         | 1        | 1.79%   |
| Intel X64                            | 1        | 1.79%   |
| Intel H61                            | 1        | 1.79%   |
| HP Z820 Workstation                  | 1        | 1.79%   |
| HP Z800 Workstation                  | 1        | 1.79%   |
| HP Pavilion Gaming Desktop TG01-1xxx | 1        | 1.79%   |
| HP Pavilion Desktop 590-p0xxx        | 1        | 1.79%   |
| HP ENVY TE01-0xxx                    | 1        | 1.79%   |
| HP EliteDesk 800 G1 DM               | 1        | 1.79%   |
| HP Compaq 6200 Pro MT PC             | 1        | 1.79%   |
| HP 339A                              | 1        | 1.79%   |
| Gigabyte Z390 GAMING X               | 1        | 1.79%   |
| Gigabyte Z270X-Gaming 5              | 1        | 1.79%   |
| Gigabyte X570 I AORUS PRO WIFI       | 1        | 1.79%   |
| Gigabyte H81M-H                      | 1        | 1.79%   |
| Gigabyte H310M M.2 2.0               | 1        | 1.79%   |
| Gigabyte F2A55M-HD2                  | 1        | 1.79%   |
| Gigabyte EP43T-USB3                  | 1        | 1.79%   |
| Gigabyte B85M-DS3H-A                 | 1        | 1.79%   |
| Gigabyte B85M-D3V-A                  | 1        | 1.79%   |
| Gigabyte B450M DS3H V2               | 1        | 1.79%   |
| Gigabyte B450 I AORUS PRO WIFI       | 1        | 1.79%   |
| Gigabyte AX370-Gaming                | 1        | 1.79%   |
| Gigabyte AB350-Gaming 3              | 1        | 1.79%   |
| Dell OptiPlex 9020M                  | 1        | 1.79%   |
| Dell OptiPlex 9010                   | 1        | 1.79%   |
| Chuwi LarkBox Pro                    | 1        | 1.79%   |
| Biostar TH55XE                       | 1        | 1.79%   |
| Biostar TA790GXE 128M                | 1        | 1.79%   |
| ASUS TUF GAMING B560M-PLUS           | 1        | 1.79%   |
| ASUS TUF GAMING B550M-PLUS           | 1        | 1.79%   |
| ASUS TUF GAMING B450M-PRO II         | 1        | 1.79%   |
| ASUS ROG STRIX Z590-F GAMING WIFI    | 1        | 1.79%   |
| ASUS ROG STRIX B450-I GAMING         | 1        | 1.79%   |
| ASUS PRIME B365M-A                   | 1        | 1.79%   |
| ASUS P8H61-MX R2.0                   | 1        | 1.79%   |
| ASUS P7H55-M                         | 1        | 1.79%   |
| ASUS P6X58D-E                        | 1        | 1.79%   |
| ASUS P5KPL-AM SE                     | 1        | 1.79%   |
| ASUS M5A99X EVO R2.0                 | 1        | 1.79%   |
| ASUS M5A78L-M LX/BR                  | 1        | 1.79%   |
| ASUS M4N78-AM                        | 1        | 1.79%   |
| ASRock X570 Extreme4                 | 1        | 1.79%   |
| ASRock P67 Extreme4                  | 1        | 1.79%   |
| ASRock M3A790GXH/128M                | 1        | 1.79%   |
| ASRock H81TM-ITX R2.0                | 1        | 1.79%   |
| ASRock B450 Pro4                     | 1        | 1.79%   |
| ASRock A320M-HDV                     | 1        | 1.79%   |
| Apple MacPro5,1                      | 1        | 1.79%   |
| Acer Aspire X3990                    | 1        | 1.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS TUF              | 3        | 5.36%   |
| HP Pavilion           | 2        | 3.57%   |
| Dell OptiPlex         | 2        | 3.57%   |
| ASUS ROG              | 2        | 3.57%   |
| Shuttle DS61          | 1        | 1.79%   |
| Pegatron KJ379AA-ABA  | 1        | 1.79%   |
| MSI MS-7C83           | 1        | 1.79%   |
| MSI MS-7B79           | 1        | 1.79%   |
| MSI MS-7817           | 1        | 1.79%   |
| MSI MS-7693           | 1        | 1.79%   |
| MSI Elite             | 1        | 1.79%   |
| Intel X64             | 1        | 1.79%   |
| Intel H61             | 1        | 1.79%   |
| HP Z820               | 1        | 1.79%   |
| HP Z800               | 1        | 1.79%   |
| HP ENVY               | 1        | 1.79%   |
| HP EliteDesk          | 1        | 1.79%   |
| HP Compaq             | 1        | 1.79%   |
| HP 339A               | 1        | 1.79%   |
| Gigabyte Z390         | 1        | 1.79%   |
| Gigabyte Z270X-Gaming | 1        | 1.79%   |
| Gigabyte X570         | 1        | 1.79%   |
| Gigabyte H81M-H       | 1        | 1.79%   |
| Gigabyte H310M        | 1        | 1.79%   |
| Gigabyte F2A55M-HD2   | 1        | 1.79%   |
| Gigabyte EP43T-USB3   | 1        | 1.79%   |
| Gigabyte B85M-DS3H-A  | 1        | 1.79%   |
| Gigabyte B85M-D3V-A   | 1        | 1.79%   |
| Gigabyte B450M        | 1        | 1.79%   |
| Gigabyte B450         | 1        | 1.79%   |
| Gigabyte AX370-Gaming | 1        | 1.79%   |
| Gigabyte AB350-Gaming | 1        | 1.79%   |
| Chuwi LarkBox         | 1        | 1.79%   |
| Biostar TH55XE        | 1        | 1.79%   |
| Biostar TA790GXE      | 1        | 1.79%   |
| ASUS PRIME            | 1        | 1.79%   |
| ASUS P8H61-MX         | 1        | 1.79%   |
| ASUS P7H55-M          | 1        | 1.79%   |
| ASUS P6X58D-E         | 1        | 1.79%   |
| ASUS P5KPL-AM         | 1        | 1.79%   |
| ASUS M5A99X           | 1        | 1.79%   |
| ASUS M5A78L-M         | 1        | 1.79%   |
| ASUS M4N78-AM         | 1        | 1.79%   |
| ASRock X570           | 1        | 1.79%   |
| ASRock P67            | 1        | 1.79%   |
| ASRock M3A790GXH      | 1        | 1.79%   |
| ASRock H81TM-ITX      | 1        | 1.79%   |
| ASRock B450           | 1        | 1.79%   |
| ASRock A320M-HDV      | 1        | 1.79%   |
| Apple MacPro5         | 1        | 1.79%   |
| Acer Aspire           | 1        | 1.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 10       | 17.86%  |
| 2020 | 8        | 14.29%  |
| 2015 | 6        | 10.71%  |
| 2018 | 5        | 8.93%   |
| 2019 | 4        | 7.14%   |
| 2013 | 4        | 7.14%   |
| 2011 | 4        | 7.14%   |
| 2010 | 4        | 7.14%   |
| 2014 | 3        | 5.36%   |
| 2017 | 2        | 3.57%   |
| 2012 | 2        | 3.57%   |
| 2009 | 2        | 3.57%   |
| 2016 | 1        | 1.79%   |
| 2008 | 1        | 1.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 56       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 53       | 94.64%  |
| Enabled  | 3        | 5.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 56       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 17       | 30.36%  |
| 4.01-8.0    | 14       | 25%     |
| 32.01-64.0  | 14       | 25%     |
| 3.01-4.0    | 5        | 8.93%   |
| 8.01-16.0   | 5        | 8.93%   |
| 64.01-256.0 | 1        | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 24       | 42.11%  |
| 2.01-3.0  | 18       | 31.58%  |
| 3.01-4.0  | 10       | 17.54%  |
| 4.01-8.0  | 4        | 7.02%   |
| 8.01-16.0 | 1        | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 21       | 37.5%   |
| 1      | 19       | 33.93%  |
| 3      | 9        | 16.07%  |
| 4      | 5        | 8.93%   |
| 5      | 2        | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 67.86%  |
| Yes       | 18       | 32.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 55       | 98.21%  |
| No        | 1        | 1.79%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 29       | 51.79%  |
| No        | 27       | 48.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 60.71%  |
| Yes       | 22       | 39.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 6        | 10.71%  |
| Germany     | 6        | 10.71%  |
| Russia      | 4        | 7.14%   |
| UK          | 3        | 5.36%   |
| Mexico      | 3        | 5.36%   |
| Indonesia   | 3        | 5.36%   |
| Canada      | 3        | 5.36%   |
| Brazil      | 3        | 5.36%   |
| Argentina   | 3        | 5.36%   |
| Spain       | 2        | 3.57%   |
| Finland     | 2        | 3.57%   |
| Austria     | 2        | 3.57%   |
| Vietnam     | 1        | 1.79%   |
| Ukraine     | 1        | 1.79%   |
| Turkey      | 1        | 1.79%   |
| Sri Lanka   | 1        | 1.79%   |
| Poland      | 1        | 1.79%   |
| Netherlands | 1        | 1.79%   |
| Kenya       | 1        | 1.79%   |
| Italy       | 1        | 1.79%   |
| Greece      | 1        | 1.79%   |
| France      | 1        | 1.79%   |
| Denmark     | 1        | 1.79%   |
| Czechia     | 1        | 1.79%   |
| Colombia    | 1        | 1.79%   |
| China       | 1        | 1.79%   |
| Australia   | 1        | 1.79%   |
| Albania     | 1        | 1.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Vienna                  | 2        | 3.51%   |
| Znojmo                  | 1        | 1.75%   |
| Xicheng District        | 1        | 1.75%   |
| Wriezen                 | 1        | 1.75%   |
| Wigan                   | 1        | 1.75%   |
| Wattala                 | 1        | 1.75%   |
| Vit??ria                | 1        | 1.75%   |
| Vantaa                  | 1        | 1.75%   |
| Vancouver               | 1        | 1.75%   |
| Ullastrell              | 1        | 1.75%   |
| Tucson                  | 1        | 1.75%   |
| Tolyatti                | 1        | 1.75%   |
| Toluca                  | 1        | 1.75%   |
| Sukabumi                | 1        | 1.75%   |
| Staropyshminsk          | 1        | 1.75%   |
| Sparti                  | 1        | 1.75%   |
| Simferopol              | 1        | 1.75%   |
| S??o Paulo              | 1        | 1.75%   |
| Saskatoon               | 1        | 1.75%   |
| Rosario                 | 1        | 1.75%   |
| Roermond                | 1        | 1.75%   |
| Rio de Janeiro          | 1        | 1.75%   |
| Riesweiler              | 1        | 1.75%   |
| Rheinberg               | 1        | 1.75%   |
| Providence Forge        | 1        | 1.75%   |
| Potsdam                 | 1        | 1.75%   |
| Pleiku                  | 1        | 1.75%   |
| Paris                   | 1        | 1.75%   |
| Pargolovo Tretye        | 1        | 1.75%   |
| Nairobi                 | 1        | 1.75%   |
| Morelia                 | 1        | 1.75%   |
| Montreal                | 1        | 1.75%   |
| Milan                   | 1        | 1.75%   |
| Mexico City             | 1        | 1.75%   |
| Medan                   | 1        | 1.75%   |
| Landshut                | 1        | 1.75%   |
| Krakow                  | 1        | 1.75%   |
| Klaukkala               | 1        | 1.75%   |
| Kediri                  | 1        | 1.75%   |
| Kazan?ˆ™                | 1        | 1.75%   |
| Kam?«z                  | 1        | 1.75%   |
| Izmir                   | 1        | 1.75%   |
| Granollers              | 1        | 1.75%   |
| Fredersdorf             | 1        | 1.75%   |
| Fort Lauderdale         | 1        | 1.75%   |
| East Malvern            | 1        | 1.75%   |
| Copenhagen              | 1        | 1.75%   |
| Concepci??n del Uruguay | 1        | 1.75%   |
| Brooklyn                | 1        | 1.75%   |
| Bonnybridge             | 1        | 1.75%   |
| Bernau bei Berlin       | 1        | 1.75%   |
| Berazategui             | 1        | 1.75%   |
| Bathgate                | 1        | 1.75%   |
| Barranquilla            | 1        | 1.75%   |
| Augusta                 | 1        | 1.75%   |
| Ames                    | 1        | 1.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 22       | 30     | 22.92%  |
| Samsung Electronics       | 13       | 20     | 13.54%  |
| Seagate                   | 12       | 14     | 12.5%   |
| Kingston                  | 10       | 12     | 10.42%  |
| Sandisk                   | 7        | 8      | 7.29%   |
| Crucial                   | 6        | 7      | 6.25%   |
| OCZ                       | 3        | 3      | 3.13%   |
| Hitachi                   | 3        | 3      | 3.13%   |
| Patriot                   | 2        | 2      | 2.08%   |
| Intel                     | 2        | 2      | 2.08%   |
| USB3.1                    | 1        | 1      | 1.04%   |
| Unknown                   | 1        | 1      | 1.04%   |
| Transcend                 | 1        | 1      | 1.04%   |
| Toshiba                   | 1        | 1      | 1.04%   |
| Team                      | 1        | 1      | 1.04%   |
| SK Hynix                  | 1        | 1      | 1.04%   |
| Phison                    | 1        | 1      | 1.04%   |
| OCZ-VERTEX2               | 1        | 1      | 1.04%   |
| Micron/Crucial Technology | 1        | 2      | 1.04%   |
| Micron Technology         | 1        | 1      | 1.04%   |
| LITEON                    | 1        | 1      | 1.04%   |
| Kingmax                   | 1        | 1      | 1.04%   |
| Gigabyte Technology       | 1        | 1      | 1.04%   |
| GALAX                     | 1        | 1      | 1.04%   |
| China                     | 1        | 1      | 1.04%   |
| Apacer                    | 1        | 1      | 1.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB      | 4        | 3.57%   |
| Kingston SA400S37240G 240GB SSD   | 4        | 3.57%   |
| Kingston SA400S37480G 480GB SSD   | 3        | 2.68%   |
| WDC WD10EZEX-60WN4A0 1TB          | 2        | 1.79%   |
| WDC WD10EZEX-08WN4A0 1TB          | 2        | 1.79%   |
| Samsung SSD 850 EVO 250GB         | 2        | 1.79%   |
| Samsung NVMe SSD Drive 1TB        | 2        | 1.79%   |
| Intel NVMe SSD Drive 512GB        | 2        | 1.79%   |
| Crucial CT240BX500SSD1 240GB      | 2        | 1.79%   |
| Crucial CT240BX200SSD1 240GB      | 2        | 1.79%   |
| WDC WDS500G2B0A 500GB SSD         | 1        | 0.89%   |
| WDC WD6401AALS-00J7B0 640GB       | 1        | 0.89%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 0.89%   |
| WDC WD5000AAKX-603CA0 500GB       | 1        | 0.89%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 0.89%   |
| WDC WD5000AAKX-003CA0 500GB       | 1        | 0.89%   |
| WDC WD5000AAKX-001CA0 500GB       | 1        | 0.89%   |
| WDC WD50 00LUCT-61C26Y0 500GB     | 1        | 0.89%   |
| WDC WD40EZRZ-00GXCB0 4TB          | 1        | 0.89%   |
| WDC WD40EZAZ-00SF3B0 4TB          | 1        | 0.89%   |
| WDC WD3200AAJS-56B4A0 320GB       | 1        | 0.89%   |
| WDC WD2500AAKS-00B3A0 250GB       | 1        | 0.89%   |
| WDC WD20EZRX-00D8PB0 2TB          | 1        | 0.89%   |
| WDC WD20EARX-00PASB0 2TB          | 1        | 0.89%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 0.89%   |
| WDC WD15EARX-00PASB0 1TB          | 1        | 0.89%   |
| WDC WD10EZRX-00L4HB0 1TB          | 1        | 0.89%   |
| WDC WD10EZRX-00A8LB0 1TB          | 1        | 0.89%   |
| WDC WD10EZEX-75ZF5A0 1TB          | 1        | 0.89%   |
| WDC WD10EZEX-22MFCA0 1TB          | 1        | 0.89%   |
| WDC WD10EZEX-00RKKA0 1TB          | 1        | 0.89%   |
| WDC WD10EZEX-00KUWA0 1TB          | 1        | 0.89%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 0.89%   |
| WDC WD10EURX-63UY4Y0 1TB          | 1        | 0.89%   |
| USB3.1 Disk 500GB                 | 1        | 0.89%   |
| Unknown MMC Card  128GB           | 1        | 0.89%   |
| Transcend TS512GMTS430S 512GB SSD | 1        | 0.89%   |
| Toshiba DT01ACA100 1TB            | 1        | 0.89%   |
| Team L5 LITE SSD 120GB            | 1        | 0.89%   |
| SK Hynix SH920 2.5 7MM 256GB SSD  | 1        | 0.89%   |
| Seagate ST940210AS 40GB           | 1        | 0.89%   |
| Seagate ST3808110AS 80GB          | 1        | 0.89%   |
| Seagate ST3500312CS 500GB         | 1        | 0.89%   |
| Seagate ST3160815AS 160GB         | 1        | 0.89%   |
| Seagate ST3160813AS 160GB         | 1        | 0.89%   |
| Seagate ST3160023AS 160GB         | 1        | 0.89%   |
| Seagate ST250DM001 HD253GJ 250GB  | 1        | 0.89%   |
| Seagate ST250DM000-1BD141 250GB   | 1        | 0.89%   |
| Seagate ST2000DL003-9VT166 2TB    | 1        | 0.89%   |
| Seagate ST1000NM0053-1C1173 1TB   | 1        | 0.89%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 0.89%   |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 0.89%   |
| Seagate NVMe SSD Drive 2TB        | 1        | 0.89%   |
| Seagate Backup+ BK 1TB            | 1        | 0.89%   |
| SanDisk SDSSDRC032G 32GB          | 1        | 0.89%   |
| SanDisk SDSSDHII480G 480GB        | 1        | 0.89%   |
| SanDisk SDSSDA240G 240GB          | 1        | 0.89%   |
| SanDisk SDSSDA-1T00 1TB           | 1        | 0.89%   |
| Sandisk NVMe SSD Drive 512GB      | 1        | 0.89%   |
| Sandisk NVMe SSD Drive 500GB      | 1        | 0.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 29     | 56.41%  |
| Seagate             | 11       | 12     | 28.21%  |
| Hitachi             | 3        | 3      | 7.69%   |
| Samsung Electronics | 2        | 2      | 5.13%   |
| Toshiba             | 1        | 1      | 2.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 8        | 9      | 20%     |
| Samsung Electronics | 7        | 9      | 17.5%   |
| Crucial             | 6        | 7      | 15%     |
| SanDisk             | 4        | 4      | 10%     |
| OCZ                 | 3        | 3      | 7.5%    |
| Patriot             | 2        | 2      | 5%      |
| WDC                 | 1        | 1      | 2.5%    |
| Transcend           | 1        | 1      | 2.5%    |
| Team                | 1        | 1      | 2.5%    |
| SK Hynix            | 1        | 1      | 2.5%    |
| OCZ-VERTEX2         | 1        | 1      | 2.5%    |
| LITEON              | 1        | 1      | 2.5%    |
| Kingmax             | 1        | 1      | 2.5%    |
| GALAX               | 1        | 1      | 2.5%    |
| China               | 1        | 1      | 2.5%    |
| Apacer              | 1        | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 33       | 44     | 38.82%  |
| HDD     | 33       | 47     | 38.82%  |
| NVMe    | 16       | 24     | 18.82%  |
| Unknown | 2        | 2      | 2.35%   |
| MMC     | 1        | 1      | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 50       | 89     | 71.43%  |
| NVMe | 16       | 24     | 22.86%  |
| SAS  | 3        | 4      | 4.29%   |
| MMC  | 1        | 1      | 1.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 41       | 60     | 61.19%  |
| 0.51-1.0   | 20       | 25     | 29.85%  |
| 1.01-2.0   | 4        | 4      | 5.97%   |
| 3.01-4.0   | 2        | 2      | 2.99%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 16       | 28.57%  |
| 251-500        | 15       | 26.79%  |
| 21-50          | 7        | 12.5%   |
| 501-1000       | 7        | 12.5%   |
| 1001-2000      | 4        | 7.14%   |
| 2001-3000      | 3        | 5.36%   |
| More than 3000 | 2        | 3.57%   |
| 51-100         | 2        | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 28       | 50%     |
| 21-50     | 10       | 17.86%  |
| 51-100    | 6        | 10.71%  |
| 251-500   | 4        | 7.14%   |
| 101-250   | 4        | 7.14%   |
| 501-1000  | 2        | 3.57%   |
| 2001-3000 | 1        | 1.79%   |
| 1001-2000 | 1        | 1.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 16.67%  |
| WDC WD3200AAJS-56B4A0 320GB       | 1        | 1      | 16.67%  |
| WDC WD10EZEX-00KUWA0 1TB          | 1        | 1      | 16.67%  |
| Seagate ST3160813AS 160GB         | 1        | 1      | 16.67%  |
| Samsung Electronics HD160JJ 160GB | 1        | 1      | 16.67%  |
| Hitachi HTS542525K9SA00 250GB     | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 50%     |
| Seagate             | 1        | 1      | 16.67%  |
| Samsung Electronics | 1        | 1      | 16.67%  |
| Hitachi             | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 50%     |
| Seagate             | 1        | 1      | 16.67%  |
| Samsung Electronics | 1        | 1      | 16.67%  |
| Hitachi             | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 6      | 100%    |

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
| Detected | 50       | 102    | 84.75%  |
| Works    | 5        | 10     | 8.47%   |
| Malfunc  | 4        | 6      | 6.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 36       | 44.44%  |
| AMD                         | 18       | 22.22%  |
| Samsung Electronics         | 7        | 8.64%   |
| Sandisk                     | 4        | 4.94%   |
| Marvell Technology Group    | 2        | 2.47%   |
| Kingston Technology Company | 2        | 2.47%   |
| JMicron Technology          | 2        | 2.47%   |
| ASMedia Technology          | 2        | 2.47%   |
| VIA Technologies            | 1        | 1.23%   |
| Seagate Technology          | 1        | 1.23%   |
| Phison Electronics          | 1        | 1.23%   |
| Nvidia                      | 1        | 1.23%   |
| Micron/Crucial Technology   | 1        | 1.23%   |
| Micron Technology           | 1        | 1.23%   |
| LSI Logic / Symbios Logic   | 1        | 1.23%   |
| Broadcom / LSI              | 1        | 1.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11       | 10.38%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 6.6%    |
| Intel SATA Controller [RAID mode]                                                       | 5        | 4.72%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 4.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 3.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.83%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 2.83%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 2.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 2.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 2.83%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.89%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 1.89%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.89%   |
| JMicron JMB368 IDE controller                                                           | 2        | 1.89%   |
| Intel SSD 660P Series                                                                   | 2        | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.89%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.89%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.89%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.89%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.89%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.94%   |
| Seagate FireCuda 510 SSD                                                                | 1        | 0.94%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.94%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.94%   |
| Sandisk WD Black NVMe SSD                                                               | 1        | 0.94%   |
| Sandisk Non-Volatile memory controller                                                  | 1        | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.94%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.94%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 0.94%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.94%   |
| Micron Non-Volatile memory controller                                                   | 1        | 0.94%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.94%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1        | 0.94%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 0.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 0.94%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.94%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.94%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.94%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 0.94%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 0.94%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1        | 0.94%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 0.94%   |
| AMD FCH SATA Controller D                                                               | 1        | 0.94%   |
| AMD FCH IDE Controller                                                                  | 1        | 0.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 41       | 53.25%  |
| NVMe | 16       | 20.78%  |
| IDE  | 12       | 15.58%  |
| RAID | 6        | 7.79%   |
| SAS  | 1        | 1.3%    |
| SCSI | 1        | 1.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 36       | 64.29%  |
| AMD    | 20       | 35.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor             | 4        | 7.14%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 2        | 3.57%   |
| Intel Core i3 CPU 530 @ 2.93GHz                | 2        | 3.57%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 3.57%   |
| Intel Xeon CPU X5660 @ 2.80GHz                 | 1        | 1.79%   |
| Intel Xeon CPU E5520 @ 2.27GHz                 | 1        | 1.79%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz             | 1        | 1.79%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz             | 1        | 1.79%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz         | 1        | 1.79%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 1.79%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 1.79%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 1.79%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 1.79%   |
| Intel Core i7-4785T CPU @ 2.20GHz              | 1        | 1.79%   |
| Intel Core i7-10700F CPU @ 2.90GHz             | 1        | 1.79%   |
| Intel Core i7 CPU 950 @ 3.07GHz                | 1        | 1.79%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 1.79%   |
| Intel Core i5-9400F CPU @ 2.90GHz              | 1        | 1.79%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1        | 1.79%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 1        | 1.79%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.79%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 1.79%   |
| Intel Core i5-3550 CPU @ 3.30GHz               | 1        | 1.79%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 1        | 1.79%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 1.79%   |
| Intel Core i5-2320 CPU @ 3.00GHz               | 1        | 1.79%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1        | 1.79%   |
| Intel Core i5 CPU 750 @ 2.67GHz                | 1        | 1.79%   |
| Intel Core 2 Quad CPU Q9500 @ 2.83GHz          | 1        | 1.79%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz           | 1        | 1.79%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1        | 1.79%   |
| Intel Celeron G4930 CPU @ 3.20GHz              | 1        | 1.79%   |
| Intel Celeron CPU G530 @ 2.40GHz               | 1        | 1.79%   |
| Intel Celeron CPU G1610 @ 2.60GHz              | 1        | 1.79%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 1        | 1.79%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz         | 1        | 1.79%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 1.79%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 1.79%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 1        | 1.79%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1        | 1.79%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 1.79%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1        | 1.79%   |
| AMD Phenom II X4 925 Processor                 | 1        | 1.79%   |
| AMD Phenom 9850 Quad-Core Processor            | 1        | 1.79%   |
| AMD FX-8350 Eight-Core Processor               | 1        | 1.79%   |
| AMD FX-8320 Eight-Core Processor               | 1        | 1.79%   |
| AMD FX-6100 Six-Core Processor                 | 1        | 1.79%   |
| AMD Athlon II X4 620 Processor                 | 1        | 1.79%   |
| AMD A4-4000 APU with Radeon HD Graphics        | 1        | 1.79%   |
| AMD A10-9700 RADEON R7, 10 COMPUTE CORES 4C+6G | 1        | 1.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 12       | 21.43%  |
| Intel Core i7      | 7        | 12.5%   |
| AMD Ryzen 7        | 6        | 10.71%  |
| Intel Xeon         | 4        | 7.14%   |
| Intel Core i3      | 4        | 7.14%   |
| Intel Celeron      | 4        | 7.14%   |
| AMD Ryzen 5        | 4        | 7.14%   |
| AMD FX             | 3        | 5.36%   |
| Other              | 2        | 3.57%   |
| Intel Pentium Dual | 1        | 1.79%   |
| Intel Core 2 Quad  | 1        | 1.79%   |
| Intel Core 2 Duo   | 1        | 1.79%   |
| AMD Ryzen 9        | 1        | 1.79%   |
| AMD Ryzen 3        | 1        | 1.79%   |
| AMD Phenom II X4   | 1        | 1.79%   |
| AMD Phenom         | 1        | 1.79%   |
| AMD Athlon II X4   | 1        | 1.79%   |
| AMD A4             | 1        | 1.79%   |
| AMD A10            | 1        | 1.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 22       | 39.29%  |
| 8      | 11       | 19.64%  |
| 2      | 10       | 17.86%  |
| 6      | 8        | 14.29%  |
| 12     | 3        | 5.36%   |
| 3      | 1        | 1.79%   |
| 1      | 1        | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 94.64%  |
| 2      | 3        | 5.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 34       | 60.71%  |
| 1      | 22       | 39.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 56       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 7        | 12.28%  |
| 0x206a7    | 6        | 10.53%  |
| 0x08701021 | 4        | 7.02%   |
| 0x0800820d | 3        | 5.26%   |
| 0xa0671    | 2        | 3.51%   |
| 0x906ea    | 2        | 3.51%   |
| 0x306a9    | 2        | 3.51%   |
| 0x206d7    | 2        | 3.51%   |
| 0x20652    | 2        | 3.51%   |
| 0x106a5    | 2        | 3.51%   |
| 0x08701013 | 2        | 3.51%   |
| 0x06000852 | 2        | 3.51%   |
| Unknown    | 2        | 3.51%   |
| 0xa0655    | 1        | 1.75%   |
| 0xa0653    | 1        | 1.75%   |
| 0x906ed    | 1        | 1.75%   |
| 0x906eb    | 1        | 1.75%   |
| 0x906e9    | 1        | 1.75%   |
| 0x706a8    | 1        | 1.75%   |
| 0x6fd      | 1        | 1.75%   |
| 0x6fb      | 1        | 1.75%   |
| 0x206c2    | 1        | 1.75%   |
| 0x106e5    | 1        | 1.75%   |
| 0x1067a    | 1        | 1.75%   |
| 0x0a201016 | 1        | 1.75%   |
| 0x08101007 | 1        | 1.75%   |
| 0x0800111c | 1        | 1.75%   |
| 0x0600611a | 1        | 1.75%   |
| 0x06001119 | 1        | 1.75%   |
| 0x0600063e | 1        | 1.75%   |
| 0x010000db | 1        | 1.75%   |
| 0x01000095 | 1        | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 8        | 14.29%  |
| Haswell       | 7        | 12.5%   |
| Zen 2         | 6        | 10.71%  |
| KabyLake      | 5        | 8.93%   |
| Zen+          | 3        | 5.36%   |
| Westmere      | 3        | 5.36%   |
| Piledriver    | 3        | 5.36%   |
| Nehalem       | 3        | 5.36%   |
| K10           | 3        | 5.36%   |
| Zen           | 2        | 3.57%   |
| IvyBridge     | 2        | 3.57%   |
| Icelake       | 2        | 3.57%   |
| Core          | 2        | 3.57%   |
| CometLake     | 2        | 3.57%   |
| Zen 3         | 1        | 1.79%   |
| Penryn        | 1        | 1.79%   |
| Goldmont plus | 1        | 1.79%   |
| Excavator     | 1        | 1.79%   |
| Bulldozer     | 1        | 1.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| AMD              | 24       | 39.34%  |
| Nvidia           | 22       | 36.07%  |
| Intel            | 14       | 22.95%  |
| Conexant Systems | 1        | 1.64%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 11.29%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 6.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 4.84%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 3.23%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 3.23%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 3.23%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 3.23%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 3.23%   |
| AMD RS780D [Radeon HD 3300]                                                 | 2        | 3.23%   |
| AMD Oland PRO [Radeon R7 240/340]                                           | 2        | 3.23%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 2        | 3.23%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.61%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.61%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.61%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.61%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.61%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.61%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.61%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.61%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.61%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.61%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.61%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 1.61%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 1.61%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.61%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.61%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.61%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.61%   |
| Conexant Systems Conexant Display controller                                | 1        | 1.61%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.61%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.61%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 1.61%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 1.61%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 1        | 1.61%   |
| AMD RV770 [Radeon HD 4850]                                                  | 1        | 1.61%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 1        | 1.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.61%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 1.61%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                            | 1        | 1.61%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.61%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| 1 x AMD                        | 21       | 37.5%   |
| 1 x Nvidia                     | 20       | 35.71%  |
| 1 x Intel                      | 11       | 19.64%  |
| 2 x AMD + 1 x Conexant Systems | 1        | 1.79%   |
| Intel + Nvidia                 | 1        | 1.79%   |
| Intel + AMD                    | 1        | 1.79%   |
| AMD + Nvidia                   | 1        | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 45       | 78.95%  |
| Proprietary | 11       | 19.3%   |
| Unknown     | 1        | 1.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 26.32%  |
| 1.01-2.0   | 12       | 21.05%  |
| 3.01-4.0   | 9        | 15.79%  |
| 7.01-8.0   | 8        | 14.04%  |
| 0.51-1.0   | 6        | 10.53%  |
| 5.01-6.0   | 2        | 3.51%   |
| 8.01-16.0  | 2        | 3.51%   |
| 0.01-0.5   | 2        | 3.51%   |
| 2.01-3.0   | 1        | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 18.97%  |
| Hewlett-Packard      | 9        | 15.52%  |
| Goldstar             | 7        | 12.07%  |
| BenQ                 | 6        | 10.34%  |
| Dell                 | 4        | 6.9%    |
| AOC                  | 4        | 6.9%    |
| Acer                 | 4        | 6.9%    |
| Ancor Communications | 2        | 3.45%   |
| Vizio                | 1        | 1.72%   |
| ViewSonic            | 1        | 1.72%   |
| TBD                  | 1        | 1.72%   |
| SKY                  | 1        | 1.72%   |
| LG Electronics       | 1        | 1.72%   |
| Lenovo Group Limited | 1        | 1.72%   |
| HOP                  | 1        | 1.72%   |
| Grundig              | 1        | 1.72%   |
| Denver               | 1        | 1.72%   |
| AUS                  | 1        | 1.72%   |
| Unknown              | 1        | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                        | 2        | 3.13%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                      | 1        | 1.56%   |
| ViewSonic LCD Monitor VSC732E 1920x1080 520x290mm 23.4-inch            | 1        | 1.56%   |
| TBD HDMI TBD3148 1600x900 344x193mm 15.5-inch                          | 1        | 1.56%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                   | 1        | 1.56%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch      | 1        | 1.56%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch      | 1        | 1.56%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch   | 1        | 1.56%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch      | 1        | 1.56%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 1        | 1.56%   |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch      | 1        | 1.56%   |
| Samsung Electronics LCD Monitor SAM705B 1920x1080 1210x680mm 54.6-inch | 1        | 1.56%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 890x500mm 40.2-inch  | 1        | 1.56%   |
| Samsung Electronics LCD Monitor S24F350 5760x1080                      | 1        | 1.56%   |
| Samsung Electronics LCD Monitor S24F350                                | 1        | 1.56%   |
| Samsung Electronics LCD Monitor C24F390 1920x1080                      | 1        | 1.56%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch     | 1        | 1.56%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1200x340mm 49.1-inch     | 1        | 1.56%   |
| LG Electronics LCD Monitor LG IPS FULLHD                               | 1        | 1.56%   |
| Lenovo Group Limited LCD Monitor LEN D32q-20B 4480x1440                | 1        | 1.56%   |
| HOP DVI HOP2700 1920x1080 597x336mm 27.0-inch                          | 1        | 1.56%   |
| Hewlett-Packard P204v HPN3634 1600x900 432x240mm 19.5-inch             | 1        | 1.56%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 546x352mm 25.6-inch          | 1        | 1.56%   |
| Hewlett-Packard LE2002x HWP2964 1600x900 443x249mm 20.0-inch           | 1        | 1.56%   |
| Hewlett-Packard LCD Monitor LA2306 4480x1440                           | 1        | 1.56%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch             | 1        | 1.56%   |
| Hewlett-Packard Compaq WF1907 HWP26A4 1440x900 408x255mm 18.9-inch     | 1        | 1.56%   |
| Hewlett-Packard 27f HPN354C 1920x1080 598x336mm 27.0-inch              | 1        | 1.56%   |
| Hewlett-Packard 24x HPN3635 1920x1080 527x297mm 23.8-inch              | 1        | 1.56%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch             | 1        | 1.56%   |
| Grundig G2 1080p dig GRU4448 1920x1080 1600x900mm 72.3-inch            | 1        | 1.56%   |
| Goldstar W2253 GSM56DC 1920x1080 477x268mm 21.5-inch                   | 1        | 1.56%   |
| Goldstar W2043 GSM4E9E 1600x900 443x249mm 20.0-inch                    | 1        | 1.56%   |
| Goldstar TV SSCR GSMC0C8 3840x2160 1600x900mm 72.3-inch                | 1        | 1.56%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 1        | 1.56%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 1        | 1.56%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 1        | 1.56%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                 | 1        | 1.56%   |
| Denver UXGA-100-C LHC2900 2560x1080 681x287mm 29.1-inch                | 1        | 1.56%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                      | 1        | 1.56%   |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                      | 1        | 1.56%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                      | 1        | 1.56%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                      | 1        | 1.56%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                      | 1        | 1.56%   |
| Dell 1707FPV DEL4021 1280x1024 338x270mm 17.0-inch                     | 1        | 1.56%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch                | 1        | 1.56%   |
| BenQ LCD Monitor ZOWIE XL LCD 3840x1080                                | 1        | 1.56%   |
| BenQ LCD Monitor PD2700U 3840x2160                                     | 1        | 1.56%   |
| BenQ LCD BNQ8024 2560x1440 597x336mm 27.0-inch                         | 1        | 1.56%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 1        | 1.56%   |
| BenQ GC2870 BNQ78DD 1920x1080 621x341mm 27.9-inch                      | 1        | 1.56%   |
| AUS LCD Monitor VG27AQL1A 2560x1440                                    | 1        | 1.56%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 1        | 1.56%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 1        | 1.56%   |
| AOC 22V2WG5 AOC2202 1920x1080 476x268mm 21.5-inch                      | 1        | 1.56%   |
| Ancor Communications LCD Monitor ASUS VE278 1920x1080                  | 1        | 1.56%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 1        | 1.56%   |
| Acer XB321HK ACR049C 1920x1080 710x400mm 32.1-inch                     | 1        | 1.56%   |
| Acer X223W ACR0050 1680x1050 474x296mm 22.0-inch                       | 1        | 1.56%   |
| Acer LCD Monitor XV270U 5120x1440                                      | 1        | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 25       | 44.64%  |
| 3840x2160 (4K)     | 6        | 10.71%  |
| 1600x900 (HD+)     | 4        | 7.14%   |
| Unknown            | 4        | 7.14%   |
| 3840x1080          | 3        | 5.36%   |
| 2560x1440 (QHD)    | 3        | 5.36%   |
| 2560x1080          | 3        | 5.36%   |
| 1680x1050 (WSXGA+) | 2        | 3.57%   |
| 5760x1080          | 1        | 1.79%   |
| 5120x1440          | 1        | 1.79%   |
| 4480x1440          | 1        | 1.79%   |
| 1920x1200 (WUXGA)  | 1        | 1.79%   |
| 1440x900 (WXGA+)   | 1        | 1.79%   |
| 1280x1024 (SXGA)   | 1        | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 9        | 16.07%  |
| 21      | 8        | 14.29%  |
| 23      | 7        | 12.5%   |
| 27      | 6        | 10.71%  |
| 24      | 5        | 8.93%   |
| 72      | 2        | 3.57%   |
| 49      | 2        | 3.57%   |
| 40      | 2        | 3.57%   |
| 20      | 2        | 3.57%   |
| 19      | 2        | 3.57%   |
| 54      | 1        | 1.79%   |
| 34      | 1        | 1.79%   |
| 33      | 1        | 1.79%   |
| 32      | 1        | 1.79%   |
| 31      | 1        | 1.79%   |
| 29      | 1        | 1.79%   |
| 28      | 1        | 1.79%   |
| 25      | 1        | 1.79%   |
| 22      | 1        | 1.79%   |
| 17      | 1        | 1.79%   |
| 15      | 1        | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 29.09%  |
| 401-500     | 13       | 23.64%  |
| Unknown     | 9        | 16.36%  |
| 601-700     | 5        | 9.09%   |
| 701-800     | 3        | 5.45%   |
| 1001-1500   | 3        | 5.45%   |
| 801-900     | 2        | 3.64%   |
| 301-350     | 2        | 3.64%   |
| 1501-2000   | 2        | 3.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 32       | 62.75%  |
| Unknown | 9        | 17.65%  |
| 21/9    | 3        | 5.88%   |
| 16/10   | 3        | 5.88%   |
| 32/9    | 2        | 3.92%   |
| 5/4     | 1        | 1.96%   |
| 3/2     | 1        | 1.96%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 17       | 30.91%  |
| Unknown        | 9        | 16.36%  |
| 301-350        | 7        | 12.73%  |
| 151-200        | 7        | 12.73%  |
| 351-500        | 4        | 7.27%   |
| 501-1000       | 4        | 7.27%   |
| More than 1000 | 3        | 5.45%   |
| 251-300        | 2        | 3.64%   |
| 141-150        | 1        | 1.82%   |
| 101-110        | 1        | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 56.6%   |
| 101-120 | 9        | 16.98%  |
| Unknown | 9        | 16.98%  |
| 1-50    | 4        | 7.55%   |
| 121-160 | 1        | 1.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 44       | 77.19%  |
| 2     | 9        | 15.79%  |
| 3     | 2        | 3.51%   |
| 0     | 2        | 3.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 37       | 45.68%  |
| Intel                    | 19       | 23.46%  |
| TP-Link                  | 6        | 7.41%   |
| Ralink Technology        | 4        | 4.94%   |
| Xiaomi                   | 3        | 3.7%    |
| Qualcomm Atheros         | 2        | 2.47%   |
| Broadcom                 | 2        | 2.47%   |
| Ralink                   | 1        | 1.23%   |
| Nvidia                   | 1        | 1.23%   |
| NetGear                  | 1        | 1.23%   |
| Mercucys                 | 1        | 1.23%   |
| MediaTek                 | 1        | 1.23%   |
| Marvell Technology Group | 1        | 1.23%   |
| Edimax Technology        | 1        | 1.23%   |
| ASUSTek Computer         | 1        | 1.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 32.61%  |
| Intel I211 Gigabit Network Connection                             | 4        | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 4.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 3.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 3.26%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 3.26%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 3.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 2.17%   |
| TP-Link 802.11ac NIC                                              | 2        | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.17%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.17%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 1.09%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 1.09%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 1.09%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 1.09%   |
| Ralink RT5592 PCIe Wireless Network Adapter                       | 1        | 1.09%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 1.09%   |
| Nvidia MCP77 Ethernet                                             | 1        | 1.09%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]            | 1        | 1.09%   |
| Mercucys 802.11n NIC                                              | 1        | 1.09%   |
| MediaTek REVVL V+ 5G                                              | 1        | 1.09%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.09%   |
| Intel Wireless-AC 9260                                            | 1        | 1.09%   |
| Intel Wireless 7260                                               | 1        | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 1.09%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.09%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1        | 1.09%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.09%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.09%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 1.09%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.09%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 1        | 1.09%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.09%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 1.09%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]    | 1        | 1.09%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 22.58%  |
| Intel                 | 7        | 22.58%  |
| TP-Link               | 6        | 19.35%  |
| Ralink Technology     | 4        | 12.9%   |
| Ralink                | 1        | 3.23%   |
| Qualcomm Atheros      | 1        | 3.23%   |
| NetGear               | 1        | 3.23%   |
| Mercucys              | 1        | 3.23%   |
| Edimax Technology     | 1        | 3.23%   |
| Broadcom              | 1        | 3.23%   |
| ASUSTek Computer      | 1        | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                | 3        | 9.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2        | 6.45%   |
| TP-Link 802.11ac NIC                                           | 2        | 6.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 6.45%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 3.23%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1        | 3.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 3.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 3.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 3.23%   |
| Realtek RTL8187 Wireless Adapter                               | 1        | 3.23%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 3.23%   |
| Ralink RT5592 PCIe Wireless Network Adapter                    | 1        | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 3.23%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]         | 1        | 3.23%   |
| Mercucys 802.11n NIC                                           | 1        | 3.23%   |
| Intel Wireless-AC 9260                                         | 1        | 3.23%   |
| Intel Wireless 7260                                            | 1        | 3.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 3.23%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 3.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1        | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 3.23%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1        | 3.23%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 3.23%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1        | 3.23%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072] | 1        | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 35       | 59.32%  |
| Intel                    | 16       | 27.12%  |
| Xiaomi                   | 3        | 5.08%   |
| Qualcomm Atheros         | 1        | 1.69%   |
| Nvidia                   | 1        | 1.69%   |
| MediaTek                 | 1        | 1.69%   |
| Marvell Technology Group | 1        | 1.69%   |
| Broadcom                 | 1        | 1.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 49.18%  |
| Intel I211 Gigabit Network Connection                             | 4        | 6.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 6.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 4.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 4.92%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 4.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 3.28%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 3.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.64%   |
| Nvidia MCP77 Ethernet                                             | 1        | 1.64%   |
| MediaTek REVVL V+ 5G                                              | 1        | 1.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.64%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.64%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.64%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.64%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.64%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 55       | 65.48%  |
| WiFi     | 29       | 34.52%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 53       | 68.83%  |
| WiFi     | 24       | 31.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 36       | 64.29%  |
| 2     | 19       | 33.93%  |
| 0     | 1        | 1.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 73.21%  |
| Yes  | 15       | 26.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 9        | 40.91%  |
| Intel                   | 7        | 31.82%  |
| Realtek Semiconductor   | 2        | 9.09%   |
| Broadcom                | 1        | 4.55%   |
| Belkin Components       | 1        | 4.55%   |
| ASUSTek Computer        | 1        | 4.55%   |
| Apple                   | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 40.91%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 9.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 4.55%   |
| Intel Bluetooth wireless interface                  | 1        | 4.55%   |
| Intel Bluetooth Device                              | 1        | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 4.55%   |
| Intel AX210 Bluetooth                               | 1        | 4.55%   |
| Intel AX200 Bluetooth                               | 1        | 4.55%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1        | 4.55%   |
| Belkin Components Bluetooth Mini Dongle             | 1        | 4.55%   |
| ASUS Bluetooth Radio                                | 1        | 4.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 34       | 34%     |
| AMD                                  | 30       | 30%     |
| Nvidia                               | 21       | 21%     |
| Creative Labs                        | 3        | 3%      |
| Generalplus Technology               | 2        | 2%      |
| C-Media Electronics                  | 2        | 2%      |
| Thesycon Systemsoftware & Consulting | 1        | 1%      |
| Razer USA                            | 1        | 1%      |
| Logitech                             | 1        | 1%      |
| JMTek                                | 1        | 1%      |
| Focusrite-Novation                   | 1        | 1%      |
| Creative Technology                  | 1        | 1%      |
| BY EDIFIER                           | 1        | 1%      |
| ASUSTek Computer                     | 1        | 1%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 7        | 5.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 7        | 5.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6        | 5.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6        | 5.08%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5        | 4.24%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 3.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 2.54%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 2.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 2.54%   |
| Intel 200 Series PCH HD Audio                                                     | 3        | 2.54%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 3        | 2.54%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 3        | 2.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 1.69%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2        | 1.69%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 1.69%   |
| Nvidia GA102 High Definition Audio Controller                                     | 2        | 1.69%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 1.69%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 1.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2        | 1.69%   |
| Generalplus Technology USB Audio Device                                           | 2        | 1.69%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                        | 2        | 1.69%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 2        | 1.69%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.69%   |
| Thesycon Systemsoftware & Consulting DX3 Pro                                      | 1        | 0.85%   |
| Razer USA Kraken Tournament Edition                                               | 1        | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 0.85%   |
| Nvidia TU104 HD Audio Controller                                                  | 1        | 0.85%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 0.85%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 0.85%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1        | 0.85%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 0.85%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.85%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 0.85%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1        | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1        | 0.85%   |
| Nvidia GF104 High Definition Audio Controller                                     | 1        | 0.85%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 0.85%   |
| Logitech G930                                                                     | 1        | 0.85%   |
| JMTek USB PnP Audio Device                                                        | 1        | 0.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1        | 0.85%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 0.85%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 0.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 0.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 0.85%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                 | 1        | 0.85%   |
| Creative Technology Sound BlasterX Kratos S5                                      | 1        | 0.85%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]         | 1        | 0.85%   |
| C-Media Electronics Multimedia Headset [Gigaware by Ignition L.P.]                | 1        | 0.85%   |
| C-Media Electronics Blue Snowball                                                 | 1        | 0.85%   |
| BY EDIFIER EDIFIER G2 II GAMING HEADSET                                           | 1        | 0.85%   |
| ASUSTek Computer USB Audio                                                        | 1        | 0.85%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 1        | 0.85%   |
| AMD Trinity HDMI Audio Controller                                                 | 1        | 0.85%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                          | 1        | 0.85%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 1        | 0.85%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                        | 1        | 0.85%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 1        | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 5        | 29.41%  |
| G.Skill             | 3        | 17.65%  |
| Samsung Electronics | 2        | 11.76%  |
| Corsair             | 2        | 11.76%  |
| Unknown             | 1        | 5.88%   |
| SK Hynix            | 1        | 5.88%   |
| Neo Forza           | 1        | 5.88%   |
| Nanya Technology    | 1        | 5.88%   |
| Crucial             | 1        | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1        | 5.56%   |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s      | 1        | 5.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s     | 1        | 5.56%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s       | 1        | 5.56%   |
| Neo Forza RAM NMUD380D81-1600D 8GB DIMM DDR3 1333MT/s     | 1        | 5.56%   |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                   | 1        | 5.56%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3                | 1        | 5.56%   |
| Kingston RAM 99U5471-052.A 8GB DIMM DDR3 1333MT/s         | 1        | 5.56%   |
| Kingston RAM 99U5458-001.A00LF 2GB DIMM DDR3 1600MT/s     | 1        | 5.56%   |
| Kingston RAM 99U5403-159.A01LF 8192MB DIMM DDR3 1333MT/s  | 1        | 5.56%   |
| Kingston RAM 9965516-069.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 5.56%   |
| Kingston RAM 9965516-003.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 5.56%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s    | 1        | 5.56%   |
| G.Skill RAM F3-1866C11-8GRSL 8GB SODIMM DDR3 1867MT/s     | 1        | 5.56%   |
| G.Skill RAM F3-14900CL9-4GBSR 4096MB DIMM DDR3 1600MT/s   | 1        | 5.56%   |
| Crucial RAM BLS8G4D26BFSCK.8FD 8GB DIMM DDR4 2133MT/s     | 1        | 5.56%   |
| Corsair RAM CMK4GX4M1A2400C14 4GB DIMM DDR4 3007MT/s      | 1        | 5.56%   |
| Corsair RAM CMH32GX4M2D3600C18 16384MB DIMM DDR4 2133MT/s | 1        | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 7        | 58.33%  |
| DDR4 | 4        | 33.33%  |
| DDR2 | 1        | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 11       | 91.67%  |
| SODIMM | 1        | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 6        | 46.15%  |
| 4096  | 3        | 23.08%  |
| 16384 | 2        | 15.38%  |
| 2048  | 2        | 15.38%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 4        | 25%     |
| 1333  | 4        | 25%     |
| 2133  | 2        | 12.5%   |
| 3600  | 1        | 6.25%   |
| 3200  | 1        | 6.25%   |
| 3007  | 1        | 6.25%   |
| 3000  | 1        | 6.25%   |
| 1867  | 1        | 6.25%   |
| 800   | 1        | 6.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| HP LaserJet M101-M106 | 1        | 100%    |

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
| Logitech                      | 7        | 41.18%  |
| Microdia                      | 3        | 17.65%  |
| Microsoft                     | 2        | 11.76%  |
| Z-Star Microelectronics       | 1        | 5.88%   |
| Sunplus Innovation Technology | 1        | 5.88%   |
| Generalplus Technology        | 1        | 5.88%   |
| Creative Technology           | 1        | 5.88%   |
| Apple                         | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech Webcam C270            | 2        | 11.76%  |
| Z-Star Sirius USB2.0 Camera     | 1        | 5.88%   |
| Sunplus FHD Camera Microphone   | 1        | 5.88%   |
| Microsoft Xbox NUI Camera       | 1        | 5.88%   |
| Microsoft LifeCam HD-3000       | 1        | 5.88%   |
| Microdia Webcam Vitade AF       | 1        | 5.88%   |
| Microdia USB Live camera        | 1        | 5.88%   |
| Microdia Integrated Camera      | 1        | 5.88%   |
| Logitech HD Webcam C615         | 1        | 5.88%   |
| Logitech HD Pro Webcam C920     | 1        | 5.88%   |
| Logitech C505 HD Webcam         | 1        | 5.88%   |
| Logitech BRIO 4K Stream Edition | 1        | 5.88%   |
| Logitech B525 HD Webcam         | 1        | 5.88%   |
| Generalplus GENERAL WEBCAM      | 1        | 5.88%   |
| Creative Live! Cam Sync 1080p   | 1        | 5.88%   |
| Apple iPhone 5/5C/5S/6/SE       | 1        | 5.88%   |

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
| 0     | 51       | 89.47%  |
| 1     | 6        | 10.53%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 4        | 66.67%  |
| Graphics card            | 1        | 16.67%  |
| Communication controller | 1        | 16.67%  |

