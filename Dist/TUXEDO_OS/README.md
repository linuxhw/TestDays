TUXEDO OS - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for TUXEDO OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/TUXEDO_OS/Desktop/README.md) and [notebooks](/Dist/TUXEDO_OS/Notebook/README.md).

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

Total: 70

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [c47936b50c](https://linux-hardware.org/?probe=c47936b50c) | Jun 09, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [c16266c1c9](https://linux-hardware.org/?probe=c16266c1c9) | Jun 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [f75fb35204](https://linux-hardware.org/?probe=f75fb35204) | May 28, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [66c9773a5f](https://linux-hardware.org/?probe=66c9773a5f) | May 26, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [65cc5e45b0](https://linux-hardware.org/?probe=65cc5e45b0) | May 26, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [7332acbb0e](https://linux-hardware.org/?probe=7332acbb0e) | May 15, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [6142fe7fbd](https://linux-hardware.org/?probe=6142fe7fbd) | May 14, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| Lenovo        | IdeaPad N581 7505           | Notebook    | [5d340c1aa2](https://linux-hardware.org/?probe=5d340c1aa2) | May 04, 2023 |
| HP            | Pavilion dv6                | Notebook    | [be01072653](https://linux-hardware.org/?probe=be01072653) | May 03, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [756500f10b](https://linux-hardware.org/?probe=756500f10b) | May 03, 2023 |
| HP            | Pavilion dv6                | Notebook    | [87f0c054fa](https://linux-hardware.org/?probe=87f0c054fa) | May 03, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| Dell          | Inspiron 16 5630            | Notebook    | [7bfe5bb892](https://linux-hardware.org/?probe=7bfe5bb892) | Apr 27, 2023 |
| Dell          | Latitude 7530               | Notebook    | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [fd2ad16b59](https://linux-hardware.org/?probe=fd2ad16b59) | Apr 22, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [04a458482b](https://linux-hardware.org/?probe=04a458482b) | Apr 19, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [3b77631ed6](https://linux-hardware.org/?probe=3b77631ed6) | Apr 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [22c0e4cdec](https://linux-hardware.org/?probe=22c0e4cdec) | Apr 02, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aabb4d79b8](https://linux-hardware.org/?probe=aabb4d79b8) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490 20N3SBU219    | Notebook    | [b8e8125150](https://linux-hardware.org/?probe=b8e8125150) | Mar 27, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [885b757cdc](https://linux-hardware.org/?probe=885b757cdc) | Mar 24, 2023 |
| HP            | 2B3E                        | All in one  | [c6dd260a92](https://linux-hardware.org/?probe=c6dd260a92) | Mar 22, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [5e01f2c134](https://linux-hardware.org/?probe=5e01f2c134) | Mar 22, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [8aaef31933](https://linux-hardware.org/?probe=8aaef31933) | Mar 19, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [0db668b5ec](https://linux-hardware.org/?probe=0db668b5ec) | Mar 18, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [094b530ce7](https://linux-hardware.org/?probe=094b530ce7) | Mar 18, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [3fcbfecb5a](https://linux-hardware.org/?probe=3fcbfecb5a) | Mar 14, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [4c5eee300d](https://linux-hardware.org/?probe=4c5eee300d) | Mar 13, 2023 |
| Dell          | Precision 7720              | Notebook    | [dbe0d4c5c4](https://linux-hardware.org/?probe=dbe0d4c5c4) | Mar 12, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [40a0328a5f](https://linux-hardware.org/?probe=40a0328a5f) | Mar 11, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [3cde6f345c](https://linux-hardware.org/?probe=3cde6f345c) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [769cd87ebd](https://linux-hardware.org/?probe=769cd87ebd) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [e1846f2a68](https://linux-hardware.org/?probe=e1846f2a68) | Mar 07, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [886aa04456](https://linux-hardware.org/?probe=886aa04456) | Mar 07, 2023 |
| Fujitsu       | LIFEBOOK U7412              | Notebook    | [980dd72471](https://linux-hardware.org/?probe=980dd72471) | Mar 06, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [9088ef4d11](https://linux-hardware.org/?probe=9088ef4d11) | Mar 06, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [7a21cf8349](https://linux-hardware.org/?probe=7a21cf8349) | Mar 05, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [20d14c7576](https://linux-hardware.org/?probe=20d14c7576) | Mar 04, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [01f7386d8c](https://linux-hardware.org/?probe=01f7386d8c) | Mar 02, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [1e1da6a575](https://linux-hardware.org/?probe=1e1da6a575) | Feb 24, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [497a8d66e5](https://linux-hardware.org/?probe=497a8d66e5) | Feb 22, 2023 |
| Dell          | Precision 7720              | Notebook    | [2f7837d5b6](https://linux-hardware.org/?probe=2f7837d5b6) | Feb 21, 2023 |
| ASRock        | Z270M-ITX/ac                | Desktop     | [4f507f4e5a](https://linux-hardware.org/?probe=4f507f4e5a) | Feb 20, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [7cc71e6021](https://linux-hardware.org/?probe=7cc71e6021) | Feb 12, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [ed14b057dd](https://linux-hardware.org/?probe=ed14b057dd) | Feb 09, 2023 |
| HP            | 2B34                        | Desktop     | [3376fc38b3](https://linux-hardware.org/?probe=3376fc38b3) | Feb 05, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [4a2fcb6bd0](https://linux-hardware.org/?probe=4a2fcb6bd0) | Jan 31, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [e163d98802](https://linux-hardware.org/?probe=e163d98802) | Jan 28, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [fa53a29f7e](https://linux-hardware.org/?probe=fa53a29f7e) | Jan 01, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [aeb826326b](https://linux-hardware.org/?probe=aeb826326b) | Dec 20, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [731b31c845](https://linux-hardware.org/?probe=731b31c845) | Dec 02, 2022 |
| TUXEDO        | N13xWU                      | Notebook    | [55935f091d](https://linux-hardware.org/?probe=55935f091d) | Dec 01, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [fd06ca029c](https://linux-hardware.org/?probe=fd06ca029c) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [5043f6c54e](https://linux-hardware.org/?probe=5043f6c54e) | Nov 20, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [5d82e9f6ac](https://linux-hardware.org/?probe=5d82e9f6ac) | Nov 19, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [9d20af2c30](https://linux-hardware.org/?probe=9d20af2c30) | Nov 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | Notebook    | [d58eb8b2f0](https://linux-hardware.org/?probe=d58eb8b2f0) | Oct 30, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | Notebook    | [032bc01698](https://linux-hardware.org/?probe=032bc01698) | Oct 30, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [99555fc4eb](https://linux-hardware.org/?probe=99555fc4eb) | Oct 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| ASUSTek       | BU201LAV                    | Notebook    | [9d1fe7cb6f](https://linux-hardware.org/?probe=9d1fe7cb6f) | Oct 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [36e033aa01](https://linux-hardware.org/?probe=36e033aa01) | Oct 09, 2022 |
| Notebook      | W65_W67RB                   | Notebook    | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| TUXEDO OS 22.04 | 54        | 100%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 54        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 6.1.0-1009-tuxedo   | 16        | 28.07%  |
| 6.2.0-10005-tuxedo  | 11        | 19.3%   |
| 5.15.0-10058-tuxedo | 7         | 12.28%  |
| 6.2.0-10007-tuxedo  | 6         | 10.53%  |
| 5.15.0-10048-tuxedo | 4         | 7.02%   |
| 5.15.0-10053-tuxedo | 3         | 5.26%   |
| 5.15.0-10052-tuxedo | 3         | 5.26%   |
| 5.15.0-10057-tuxedo | 2         | 3.51%   |
| 5.15.0-10056-tuxedo | 2         | 3.51%   |
| 5.15.0-10050-tuxedo | 2         | 3.51%   |
| 6.0.0-1010-oem      | 1         | 1.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 23        | 40.35%  |
| 6.2.0   | 17        | 29.82%  |
| 6.1.0   | 16        | 28.07%  |
| 6.0.0   | 1         | 1.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 23        | 40.35%  |
| 6.2     | 17        | 29.82%  |
| 6.1     | 16        | 28.07%  |
| 6.0     | 1         | 1.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 54        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| KDE5 | 54        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 53        | 98.15%  |
| Wayland | 1         | 1.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 44        | 80%     |
| SDDM    | 11        | 20%     |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| de_DE | 26        | 48.15%  |
| en_US | 12        | 22.22%  |
| en_GB | 4         | 7.41%   |
| pl_PL | 2         | 3.7%    |
| en_ZA | 2         | 3.7%    |
| pt_PT | 1         | 1.85%   |
| fr_FR | 1         | 1.85%   |
| es_ES | 1         | 1.85%   |
| en_DK | 1         | 1.85%   |
| en_AU | 1         | 1.85%   |
| en_AG | 1         | 1.85%   |
| de_CH | 1         | 1.85%   |
| de_AT | 1         | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 44        | 81.48%  |
| EFI  | 10        | 18.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 48        | 88.89%  |
| Btrfs   | 4         | 7.41%   |
| Tmpfs   | 1         | 1.85%   |
| Overlay | 1         | 1.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 44        | 80%     |
| GPT     | 10        | 18.18%  |
| MBR     | 1         | 1.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 51        | 92.73%  |
| Yes       | 4         | 7.27%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 51        | 92.73%  |
| Yes       | 4         | 7.27%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| TUXEDO              | 16        | 29.63%  |
| Lenovo              | 7         | 12.96%  |
| Hewlett-Packard     | 7         | 12.96%  |
| ASUSTek Computer    | 7         | 12.96%  |
| Dell                | 6         | 11.11%  |
| MSI                 | 2         | 3.7%    |
| Apple               | 2         | 3.7%    |
| Notebook            | 1         | 1.85%   |
| Gigabyte Technology | 1         | 1.85%   |
| Fujitsu             | 1         | 1.85%   |
| Fanless Mini PC     | 1         | 1.85%   |
| ASRock              | 1         | 1.85%   |
| Acer                | 1         | 1.85%   |
| Unknown             | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 3         | 5.56%   |
| TUXEDO Stellaris/Polaris AMD Gen4    | 2         | 3.7%    |
| TUXEDO Pulse 15 Gen2                 | 2         | 3.7%    |
| TUXEDO InfinityBook Pro 14 Gen6      | 2         | 3.7%    |
| TUXEDO XMG FUSION 15 (XFU15L19)      | 1         | 1.85%   |
| TUXEDO Pulse 15 Gen1                 | 1         | 1.85%   |
| TUXEDO Polaris AMD Gen3 (CZN)        | 1         | 1.85%   |
| TUXEDO Polaris 15 AMD Gen1           | 1         | 1.85%   |
| TUXEDO N13xWU                        | 1         | 1.85%   |
| TUXEDO InfinityBook S 15/17 Gen7     | 1         | 1.85%   |
| TUXEDO InfinityBook Pro Gen7 (MK2)   | 1         | 1.85%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)   | 1         | 1.85%   |
| Notebook W65_W67RB                   | 1         | 1.85%   |
| MSI MS-7D25                          | 1         | 1.85%   |
| MSI MS-7D17                          | 1         | 1.85%   |
| Lenovo ThinkPad X200 Tablet 7450WN9  | 1         | 1.85%   |
| Lenovo ThinkPad T490 20N3SBU219      | 1         | 1.85%   |
| Lenovo ThinkPad P1 Gen 3 20TJS1W700  | 1         | 1.85%   |
| Lenovo ThinkCentre M700 10GSS05X48   | 1         | 1.85%   |
| Lenovo Legion 5 15ACH6H 82JU         | 1         | 1.85%   |
| Lenovo IdeaPad N581 7505             | 1         | 1.85%   |
| Lenovo G50-80 80E5                   | 1         | 1.85%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 1         | 1.85%   |
| HP Pavilion dv6                      | 1         | 1.85%   |
| HP OMEN Laptop 15-en0xxx             | 1         | 1.85%   |
| HP ENVY x360 Convertible 13-ar0xxx   | 1         | 1.85%   |
| HP EliteBook 820 G2                  | 1         | 1.85%   |
| HP EliteBook 2570p                   | 1         | 1.85%   |
| HP 280 G1 MT                         | 1         | 1.85%   |
| Gigabyte H81M-HD3                    | 1         | 1.85%   |
| Fujitsu LIFEBOOK U7412               | 1         | 1.85%   |
| Fanless Mini PC PCG35 GLK            | 1         | 1.85%   |
| Dell Vostro 3550                     | 1         | 1.85%   |
| Dell Venue 11 Pro 7130 vPro          | 1         | 1.85%   |
| Dell Precision 7720                  | 1         | 1.85%   |
| Dell OptiPlex 9010                   | 1         | 1.85%   |
| Dell Latitude 7530                   | 1         | 1.85%   |
| Dell Inspiron 16 5630                | 1         | 1.85%   |
| ASUS Zephyrus G GU502DU_GA502DU      | 1         | 1.85%   |
| ASUS TUF Gaming H470-PRO             | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| TUXEDO InfinityBook   | 5         | 9.26%   |
| TUXEDO Pulse          | 3         | 5.56%   |
| Lenovo ThinkPad       | 3         | 5.56%   |
| Unknown               | 3         | 5.56%   |
| TUXEDO Stellaris      | 2         | 3.7%    |
| TUXEDO Polaris        | 2         | 3.7%    |
| HP Pavilion           | 2         | 3.7%    |
| HP EliteBook          | 2         | 3.7%    |
| TUXEDO XMG            | 1         | 1.85%   |
| TUXEDO N13xWU         | 1         | 1.85%   |
| Notebook W65          | 1         | 1.85%   |
| MSI MS-7D25           | 1         | 1.85%   |
| MSI MS-7D17           | 1         | 1.85%   |
| Lenovo ThinkCentre    | 1         | 1.85%   |
| Lenovo Legion         | 1         | 1.85%   |
| Lenovo IdeaPad        | 1         | 1.85%   |
| Lenovo G50-80         | 1         | 1.85%   |
| HP OMEN               | 1         | 1.85%   |
| HP ENVY               | 1         | 1.85%   |
| HP 280                | 1         | 1.85%   |
| Gigabyte H81M-HD3     | 1         | 1.85%   |
| Fujitsu LIFEBOOK      | 1         | 1.85%   |
| Fanless Mini PC PCG35 | 1         | 1.85%   |
| Dell Vostro           | 1         | 1.85%   |
| Dell Venue            | 1         | 1.85%   |
| Dell Precision        | 1         | 1.85%   |
| Dell OptiPlex         | 1         | 1.85%   |
| Dell Latitude         | 1         | 1.85%   |
| Dell Inspiron         | 1         | 1.85%   |
| ASUS Zephyrus         | 1         | 1.85%   |
| ASUS TUF              | 1         | 1.85%   |
| ASUS ROG              | 1         | 1.85%   |
| ASUS PRIME            | 1         | 1.85%   |
| ASUS P8H61-M          | 1         | 1.85%   |
| ASUS K55VJ            | 1         | 1.85%   |
| ASUS BU201LAV         | 1         | 1.85%   |
| ASRock Z270M-ITX      | 1         | 1.85%   |
| Apple MacBookPro8     | 1         | 1.85%   |
| Apple MacBookAir7     | 1         | 1.85%   |
| Acer TravelMate       | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 10        | 18.52%  |
| 2021 | 8         | 14.81%  |
| 2020 | 6         | 11.11%  |
| 2015 | 6         | 11.11%  |
| 2019 | 5         | 9.26%   |
| 2012 | 3         | 5.56%   |
| 2011 | 3         | 5.56%   |
| 2023 | 2         | 3.7%    |
| 2017 | 2         | 3.7%    |
| 2016 | 2         | 3.7%    |
| 2014 | 2         | 3.7%    |
| 2013 | 2         | 3.7%    |
| 2010 | 1         | 1.85%   |
| 2009 | 1         | 1.85%   |
| 2008 | 1         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 41        | 75.93%  |
| Desktop     | 11        | 20.37%  |
| Convertible | 1         | 1.85%   |
| Mini pc     | 1         | 1.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 54        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 12        | 22.22%  |
| 32.01-64.0  | 10        | 18.52%  |
| 16.01-24.0  | 9         | 16.67%  |
| 4.01-8.0    | 8         | 14.81%  |
| 3.01-4.0    | 7         | 12.96%  |
| 64.01-256.0 | 5         | 9.26%   |
| 24.01-32.0  | 3         | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 29.09%  |
| 1.01-2.0   | 15        | 27.27%  |
| 2.01-3.0   | 14        | 25.45%  |
| 3.01-4.0   | 7         | 12.73%  |
| 16.01-24.0 | 2         | 3.64%   |
| 8.01-16.0  | 1         | 1.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 50.91%  |
| 2      | 21        | 38.18%  |
| 4      | 3         | 5.45%   |
| 3      | 2         | 3.64%   |
| 5      | 1         | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 75.93%  |
| Yes       | 13        | 24.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 83.33%  |
| No        | 9         | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 90.74%  |
| No        | 5         | 9.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 81.48%  |
| No        | 10        | 18.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 26        | 48.15%  |
| USA          | 5         | 9.26%   |
| UK           | 3         | 5.56%   |
| Switzerland  | 3         | 5.56%   |
| South Africa | 2         | 3.7%    |
| Portugal     | 2         | 3.7%    |
| Poland       | 2         | 3.7%    |
| Austria      | 2         | 3.7%    |
| Turkey       | 1         | 1.85%   |
| Spain        | 1         | 1.85%   |
| Romania      | 1         | 1.85%   |
| Netherlands  | 1         | 1.85%   |
| France       | 1         | 1.85%   |
| Egypt        | 1         | 1.85%   |
| Denmark      | 1         | 1.85%   |
| Czechia      | 1         | 1.85%   |
| Australia    | 1         | 1.85%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Zurich             | 2         | 3.7%    |
| Vienna             | 2         | 3.7%    |
| Schweinfurt        | 2         | 3.7%    |
| Munich             | 2         | 3.7%    |
| Leipzig            | 2         | 3.7%    |
| Zalău             | 1         | 1.85%   |
| Zabrze             | 1         | 1.85%   |
| Watertown          | 1         | 1.85%   |
| Walsall            | 1         | 1.85%   |
| Stuttgart          | 1         | 1.85%   |
| Stockstadt am Main | 1         | 1.85%   |
| Seattle            | 1         | 1.85%   |
| Rio Maior          | 1         | 1.85%   |
| Reno               | 1         | 1.85%   |
| Redcar             | 1         | 1.85%   |
| Prague             | 1         | 1.85%   |
| Paris              | 1         | 1.85%   |
| Neuwied            | 1         | 1.85%   |
| Mannheim           | 1         | 1.85%   |
| Lucerne            | 1         | 1.85%   |
| Lublin             | 1         | 1.85%   |
| Lippstadt          | 1         | 1.85%   |
| Langenhagen        | 1         | 1.85%   |
| Laage              | 1         | 1.85%   |
| Johannesburg       | 1         | 1.85%   |
| Jessen             | 1         | 1.85%   |
| Istanbul           | 1         | 1.85%   |
| Husum              | 1         | 1.85%   |
| Herzberg           | 1         | 1.85%   |
| Heilbronn          | 1         | 1.85%   |
| Hamburg            | 1         | 1.85%   |
| Gorebridge         | 1         | 1.85%   |
| Friedrichstadt     | 1         | 1.85%   |
| Frankfurt am Main  | 1         | 1.85%   |
| Ethridge           | 1         | 1.85%   |
| Ehringshausen      | 1         | 1.85%   |
| Coswig             | 1         | 1.85%   |
| Cairo              | 1         | 1.85%   |
| Bronshoj           | 1         | 1.85%   |
| Brisbane           | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 33     | 31.25%  |
| Seagate             | 9         | 10     | 11.25%  |
| Sandisk             | 7         | 8      | 8.75%   |
| WDC                 | 4         | 5      | 5%      |
| Hitachi             | 4         | 6      | 5%      |
| SPCC                | 2         | 2      | 2.5%    |
| SK hynix            | 2         | 3      | 2.5%    |
| Phison Electronics  | 2         | 2      | 2.5%    |
| Micron Technology   | 2         | 2      | 2.5%    |
| GOODRAM             | 2         | 2      | 2.5%    |
| USB3.0              | 1         | 1      | 1.25%   |
| Unknown             | 1         | 1      | 1.25%   |
| Toshiba             | 1         | 1      | 1.25%   |
| Silicon Motion      | 1         | 2      | 1.25%   |
| OWC                 | 1         | 1      | 1.25%   |
| LITEONIT            | 1         | 1      | 1.25%   |
| Lite-On Technology  | 1         | 1      | 1.25%   |
| Kingston            | 1         | 1      | 1.25%   |
| Kingchuxing         | 1         | 1      | 1.25%   |
| Intenso             | 1         | 1      | 1.25%   |
| Intel               | 1         | 1      | 1.25%   |
| HS-SSD-E100         | 1         | 1      | 1.25%   |
| Hikvision           | 1         | 2      | 1.25%   |
| HGST HTS            | 1         | 1      | 1.25%   |
| CT1000BX            | 1         | 1      | 1.25%   |
| Crucial             | 1         | 1      | 1.25%   |
| China               | 1         | 1      | 1.25%   |
| ASMT                | 1         | 1      | 1.25%   |
| Apple               | 1         | 1      | 1.25%   |
| Apacer              | 1         | 1      | 1.25%   |
| Unknown             | 1         | 1      | 1.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 980 1TB                                 | 5         | 5.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 5         | 5.81%   |
| Samsung SSD 980 500GB                               | 4         | 4.65%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 3         | 3.49%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 2.33%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2         | 2.33%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 2.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 2.33%   |
| Hitachi HTS727550A9E364 500GB                       | 2         | 2.33%   |
| WDC WD80EAZZ-00BKLB0 8TB                            | 1         | 1.16%   |
| WDC WD3200BPVT-24JJ5T0 320GB                        | 1         | 1.16%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1         | 1.16%   |
| WDC WD10JPVX-11JC3T0 1TB                            | 1         | 1.16%   |
| WDC WD Elements SE SSD 1TB                          | 1         | 1.16%   |
| USB3.0 Super Speed 1TB                              | 1         | 1.16%   |
| Unknown MMC Card  2GB                               | 1         | 1.16%   |
| Toshiba XG4 NVMe SSD Controller 256GB               | 1         | 1.16%   |
| SPCC M.2 SSD 256GB                                  | 1         | 1.16%   |
| SPCC M.2 PCIe SSD 1TB                               | 1         | 1.16%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB             | 1         | 1.16%   |
| SK hynix SC311 SATA 256GB SSD                       | 1         | 1.16%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB   | 1         | 1.16%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1.16%   |
| Seagate ST500LM034-2GH17A 500GB                     | 1         | 1.16%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 1.16%   |
| Seagate ST3500413AS 500GB                           | 1         | 1.16%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1.16%   |
| Seagate ST1000DX001-1NS162-SSHD 1TB                 | 1         | 1.16%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1.16%   |
| Seagate Expansion 1TB                               | 1         | 1.16%   |
| Seagate BarraCuda Q5 ZP500CV30001 500GB             | 1         | 1.16%   |
| Sandisk WD PC SN735 SDBPNHH-1T00-1002 1TB           | 1         | 1.16%   |
| Sandisk WD Black SN850 500GB                        | 1         | 1.16%   |
| SanDisk SDSSDA240G 240GB                            | 1         | 1.16%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD                 | 1         | 1.16%   |
| SanDisk NVMe SSD Drive 500GB                        | 1         | 1.16%   |
| Samsung SSD 980 PRO 500GB                           | 1         | 1.16%   |
| Samsung SSD 860 QVO 1TB                             | 1         | 1.16%   |
| Samsung SSD 860 PRO 512GB                           | 1         | 1.16%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 8         | 9      | 47.06%  |
| Hitachi  | 4         | 6      | 23.53%  |
| WDC      | 3         | 4      | 17.65%  |
| USB3.0   | 1         | 1      | 5.88%   |
| HGST HTS | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 21.74%  |
| SanDisk             | 2         | 2      | 8.7%    |
| GOODRAM             | 2         | 2      | 8.7%    |
| WDC                 | 1         | 1      | 4.35%   |
| SPCC                | 1         | 1      | 4.35%   |
| SK hynix            | 1         | 2      | 4.35%   |
| OWC                 | 1         | 1      | 4.35%   |
| Micron Technology   | 1         | 1      | 4.35%   |
| LITEONIT            | 1         | 1      | 4.35%   |
| Kingston            | 1         | 1      | 4.35%   |
| Intenso             | 1         | 1      | 4.35%   |
| CT1000BX            | 1         | 1      | 4.35%   |
| Crucial             | 1         | 1      | 4.35%   |
| China               | 1         | 1      | 4.35%   |
| ASMT                | 1         | 1      | 4.35%   |
| Apple               | 1         | 1      | 4.35%   |
| Apacer              | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 32        | 46     | 43.84%  |
| SSD     | 20        | 25     | 27.4%   |
| HDD     | 17        | 21     | 23.29%  |
| MMC     | 2         | 2      | 2.74%   |
| Unknown | 2         | 2      | 2.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 32        | 46     | 47.06%  |
| SATA | 29        | 42     | 42.65%  |
| SAS  | 5         | 6      | 7.35%   |
| MMC  | 2         | 2      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 28     | 56.76%  |
| 0.51-1.0   | 13        | 15     | 35.14%  |
| 1.01-2.0   | 2         | 2      | 5.41%   |
| 4.01-10.0  | 1         | 1      | 2.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 17        | 31.48%  |
| 101-250        | 13        | 24.07%  |
| 251-500        | 9         | 16.67%  |
| 1001-2000      | 6         | 11.11%  |
| 21-50          | 2         | 3.7%    |
| 2001-3000      | 2         | 3.7%    |
| 1-20           | 2         | 3.7%    |
| More than 3000 | 1         | 1.85%   |
| 51-100         | 1         | 1.85%   |
| Unknown        | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 18        | 32.14%  |
| 21-50     | 16        | 28.57%  |
| 101-250   | 9         | 16.07%  |
| 251-500   | 5         | 8.93%   |
| 51-100    | 4         | 7.14%   |
| 501-1000  | 2         | 3.57%   |
| 1001-2000 | 1         | 1.79%   |
| Unknown   | 1         | 1.79%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 45        | 78     | 80.36%  |
| Works    | 11        | 18     | 19.64%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 32        | 44.44%  |
| Samsung Electronics          | 22        | 30.56%  |
| SanDisk                      | 5         | 6.94%   |
| AMD                          | 4         | 5.56%   |
| Silicon Motion               | 2         | 2.78%   |
| Phison Electronics           | 2         | 2.78%   |
| Toshiba America Info Systems | 1         | 1.39%   |
| SK hynix                     | 1         | 1.39%   |
| Seagate Technology           | 1         | 1.39%   |
| Micron Technology            | 1         | 1.39%   |
| Lite-On Technology           | 1         | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980                                                         | 9         | 12%     |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 8         | 10.67%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 5.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 5.33%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4         | 5.33%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 4%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 4%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 4%      |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2         | 2.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 2.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2         | 2.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 2.67%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 1.33%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1         | 1.33%   |
| Seagate Non-Volatile memory controller                                                  | 1         | 1.33%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1         | 1.33%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 1         | 1.33%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 1.33%   |
| Samsung Electronics SATA controller                                                     | 1         | 1.33%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 1.33%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 1.33%   |
| Micron NVMe Storage Controller                                                          | 1         | 1.33%   |
| Lite-On Non-Volatile memory controller                                                  | 1         | 1.33%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                   | 1         | 1.33%   |
| Intel SSD 660P Series                                                                   | 1         | 1.33%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 1.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 1.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 1.33%   |
| Intel Comet Lake PCH-H RAID                                                             | 1         | 1.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.33%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1         | 1.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 1.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 1.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 1.33%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 1.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 32        | 47.06%  |
| SATA | 31        | 45.59%  |
| RAID | 4         | 5.88%   |
| IDE  | 1         | 1.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 75.93%  |
| AMD    | 13        | 24.07%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 3.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz        | 2         | 3.7%    |
| Intel 12th Gen Core i7-12700H           | 2         | 3.7%    |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 2         | 3.7%    |
| AMD Ryzen 7 6800H with Radeon Graphics  | 2         | 3.7%    |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 3.7%    |
| AMD Ryzen 5 4600H with Radeon Graphics  | 2         | 3.7%    |
| Intel Xeon W-10855M CPU @ 2.80GHz       | 1         | 1.85%   |
| Intel Pentium CPU G3420 @ 3.20GHz       | 1         | 1.85%   |
| Intel Pentium CPU 2020M @ 2.40GHz       | 1         | 1.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.85%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 1.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.85%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.85%   |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 1.85%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 1.85%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 1.85%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 1.85%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 1         | 1.85%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 1         | 1.85%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 1         | 1.85%   |
| Intel Core i5-7600T CPU @ 2.80GHz       | 1         | 1.85%   |
| Intel Core i5-5250U CPU @ 1.60GHz       | 1         | 1.85%   |
| Intel Core i5-4590S CPU @ 3.00GHz       | 1         | 1.85%   |
| Intel Core i5-4300Y CPU @ 1.60GHz       | 1         | 1.85%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 1         | 1.85%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1         | 1.85%   |
| Intel Core i5-10400 CPU @ 2.90GHz       | 1         | 1.85%   |
| Intel Core i5 CPU M 540 @ 2.53GHz       | 1         | 1.85%   |
| Intel Core i3-6300 CPU @ 3.80GHz        | 1         | 1.85%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz    | 1         | 1.85%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 1         | 1.85%   |
| Intel Celeron CPU 1037U @ 1.80GHz       | 1         | 1.85%   |
| Intel 13th Gen Core i7-1360P            | 1         | 1.85%   |
| Intel 12th Gen Core i9-12900KS          | 1         | 1.85%   |
| Intel 12th Gen Core i7-1260P            | 1         | 1.85%   |
| Intel 12th Gen Core i7-1255U            | 1         | 1.85%   |
| Intel 12th Gen Core i3-1215U            | 1         | 1.85%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz  | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 12        | 22.22%  |
| Intel Core i5    | 12        | 22.22%  |
| Other            | 10        | 18.52%  |
| AMD Ryzen 7      | 8         | 14.81%  |
| AMD Ryzen 5      | 4         | 7.41%   |
| Intel Pentium    | 2         | 3.7%    |
| Intel Celeron    | 2         | 3.7%    |
| Intel Xeon       | 1         | 1.85%   |
| Intel Core i3    | 1         | 1.85%   |
| Intel Core 2 Duo | 1         | 1.85%   |
| AMD Ryzen 9      | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 17        | 31.48%  |
| 2      | 13        | 24.07%  |
| 8      | 9         | 16.67%  |
| 6      | 9         | 16.67%  |
| 14     | 2         | 3.7%    |
| 12     | 2         | 3.7%    |
| 16     | 1         | 1.85%   |
| 10     | 1         | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 45        | 83.33%  |
| 1      | 9         | 16.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 54        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 85.45%  |
| 0xa0653    | 1         | 1.82%   |
| 0x906ea    | 1         | 1.82%   |
| 0x906e9    | 1         | 1.82%   |
| 0x906a4    | 1         | 1.82%   |
| 0x906a3    | 1         | 1.82%   |
| 0x806c1    | 1         | 1.82%   |
| 0x306d4    | 1         | 1.82%   |
| 0x0a50000d | 1         | 1.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 10        | 18.52%  |
| KabyLake         | 7         | 12.96%  |
| IvyBridge        | 6         | 11.11%  |
| Haswell          | 4         | 7.41%   |
| Zen 3            | 3         | 5.56%   |
| Zen 2            | 3         | 5.56%   |
| SandyBridge      | 3         | 5.56%   |
| CometLake        | 3         | 5.56%   |
| Broadwell        | 3         | 5.56%   |
| Alderlake Hybrid | 3         | 5.56%   |
| Zen+             | 2         | 3.7%    |
| TigerLake        | 2         | 3.7%    |
| Skylake          | 2         | 3.7%    |
| Westmere         | 1         | 1.85%   |
| Penryn           | 1         | 1.85%   |
| Goldmont plus    | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 37        | 52.11%  |
| Nvidia | 18        | 25.35%  |
| AMD    | 16        | 22.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 4         | 5.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 4         | 5.63%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 5.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 3         | 4.23%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 3         | 4.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 4.23%   |
| AMD Renoir                                                                    | 3         | 4.23%   |
| AMD Rembrandt [Radeon 680M]                                                   | 3         | 4.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 3         | 4.23%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                 | 2         | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 2         | 2.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 2         | 2.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 2.82%   |
| Intel HD Graphics 630                                                         | 2         | 2.82%   |
| Intel HD Graphics 5500                                                        | 2         | 2.82%   |
| Intel HD Graphics 530                                                         | 2         | 2.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 2.82%   |
| AMD Lucienne                                                                  | 2         | 2.82%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 1.41%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 1.41%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 1         | 1.41%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 1.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1         | 1.41%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 1.41%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.41%   |
| Nvidia GF108M [GeForce GT 635M]                                               | 1         | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.41%   |
| Intel UHD Graphics 620                                                        | 1         | 1.41%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 1         | 1.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.41%   |
| Intel HD Graphics 6000                                                        | 1         | 1.41%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                | 1         | 1.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.41%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.41%   |
| Intel AlderLake-S GT1                                                         | 1         | 1.41%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 1         | 1.41%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                       | 1         | 1.41%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                 | 1         | 1.41%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 50.91%  |
| AMD + Nvidia   | 8         | 14.55%  |
| Intel + Nvidia | 6         | 10.91%  |
| 1 x AMD        | 6         | 10.91%  |
| 1 x Nvidia     | 4         | 7.27%   |
| Intel + AMD    | 3         | 5.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 38        | 70.37%  |
| Proprietary | 16        | 29.63%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 69.09%  |
| 5.01-6.0   | 9         | 16.36%  |
| 7.01-8.0   | 3         | 5.45%   |
| 1.01-2.0   | 3         | 5.45%   |
| 3.01-4.0   | 1         | 1.82%   |
| 0.01-0.5   | 1         | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 13        | 20.97%  |
| AU Optronics        | 8         | 12.9%   |
| Samsung Electronics | 7         | 11.29%  |
| LG Display          | 5         | 8.06%   |
| CSO                 | 3         | 4.84%   |
| Acer                | 3         | 4.84%   |
| Dell                | 2         | 3.23%   |
| Chimei Innolux      | 2         | 3.23%   |
| BenQ                | 2         | 3.23%   |
| Apple               | 2         | 3.23%   |
| AOC                 | 2         | 3.23%   |
| Yamaha              | 1         | 1.61%   |
| Sharp               | 1         | 1.61%   |
| SGT                 | 1         | 1.61%   |
| RTK                 | 1         | 1.61%   |
| Philips             | 1         | 1.61%   |
| PANDA               | 1         | 1.61%   |
| Lenovo              | 1         | 1.61%   |
| InfoVision          | 1         | 1.61%   |
| Iiyama              | 1         | 1.61%   |
| Hewlett-Packard     | 1         | 1.61%   |
| Goldstar            | 1         | 1.61%   |
| Eizo                | 1         | 1.61%   |
| ASUSTek Computer    | 1         | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 3         | 4.62%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 3         | 4.62%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 2         | 3.08%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 3.08%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 1.54%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 1.54%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 1.54%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 376x301mm 19.0-inch       | 1         | 1.54%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch   | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch   | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch   | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 1.54%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 1.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 1.54%   |
| RTK Wimaxit FHD RTK5A5B 1920x1080 344x195mm 15.6-inch                   | 1         | 1.54%   |
| Philips 170S4 PHL0818 1280x1024 338x270mm 17.0-inch                     | 1         | 1.54%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 1.54%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch            | 1         | 1.54%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 1         | 1.54%   |
| LG Display LCD Monitor LGD0545 3200x1800 293x165mm 13.2-inch            | 1         | 1.54%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch            | 1         | 1.54%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 1.54%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                 | 1         | 1.54%   |
| InfoVision LCD Monitor IVO3414 1920x1080 294x165mm 13.3-inch            | 1         | 1.54%   |
| Iiyama PL2290 IVM562C 1920x1080 476x268mm 21.5-inch                     | 1         | 1.54%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch            | 1         | 1.54%   |
| Goldstar E2041 GSM4EC9 1600x900 443x249mm 20.0-inch                     | 1         | 1.54%   |
| Eizo EV2736W ENC2383 2560x1440 597x336mm 27.0-inch                      | 1         | 1.54%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 1.54%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                     | 1         | 1.54%   |
| Dell S2421HN DEL41F2 1920x1080 527x296mm 23.8-inch                      | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 355x199mm 16.0-inch        | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch         | 1         | 1.54%   |
| BOE LCD Monitor BOE0A94 1920x1080 309x174mm 14.0-inch                   | 1         | 1.54%   |
| BOE LCD Monitor BOE0A67 2560x1440 344x194mm 15.5-inch                   | 1         | 1.54%   |
| BOE LCD Monitor BOE0A59 1920x1200 345x215mm 16.0-inch                   | 1         | 1.54%   |
| BOE LCD Monitor BOE0A3B 2560x1600 344x215mm 16.0-inch                   | 1         | 1.54%   |
| BOE LCD Monitor BOE0A00 1920x1080 382x215mm 17.3-inch                   | 1         | 1.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 26        | 43.33%  |
| 2560x1440 (QHD)    | 8         | 13.33%  |
| 1366x768 (WXGA)    | 8         | 13.33%  |
| 3840x2160 (4K)     | 3         | 5%      |
| 2880x1800          | 3         | 5%      |
| 1920x1200 (WUXGA)  | 2         | 3.33%   |
| 1280x800 (WXGA)    | 2         | 3.33%   |
| 1280x1024 (SXGA)   | 2         | 3.33%   |
| 3200x1800 (QHD+)   | 1         | 1.67%   |
| 2560x1600          | 1         | 1.67%   |
| 1920x540           | 1         | 1.67%   |
| 1680x1050 (WSXGA+) | 1         | 1.67%   |
| 1600x900 (HD+)     | 1         | 1.67%   |
| 1440x900 (WXGA+)   | 1         | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 32.81%  |
| 27      | 5         | 7.81%   |
| 17      | 5         | 7.81%   |
| 13      | 5         | 7.81%   |
| 14      | 4         | 6.25%   |
| 12      | 4         | 6.25%   |
| 24      | 3         | 4.69%   |
| 16      | 3         | 4.69%   |
| 40      | 2         | 3.13%   |
| 23      | 2         | 3.13%   |
| 22      | 2         | 3.13%   |
| 21      | 2         | 3.13%   |
| 84      | 1         | 1.56%   |
| 31      | 1         | 1.56%   |
| 20      | 1         | 1.56%   |
| 19      | 1         | 1.56%   |
| 18      | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 45.16%  |
| 501-600     | 9         | 14.52%  |
| 201-300     | 8         | 12.9%   |
| 401-500     | 6         | 9.68%   |
| 351-400     | 6         | 9.68%   |
| 801-900     | 2         | 3.23%   |
| 601-700     | 1         | 1.61%   |
| 1501-2000   | 1         | 1.61%   |
| Unknown     | 1         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 43        | 75.44%  |
| 16/10 | 10        | 17.54%  |
| 5/4   | 2         | 3.51%   |
| 32/9  | 1         | 1.75%   |
| 3/2   | 1         | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 33.33%  |
| 81-90          | 7         | 11.11%  |
| 301-350        | 5         | 7.94%   |
| 201-250        | 5         | 7.94%   |
| 61-70          | 4         | 6.35%   |
| 151-200        | 4         | 6.35%   |
| 121-130        | 4         | 6.35%   |
| 111-120        | 3         | 4.76%   |
| 71-80          | 2         | 3.17%   |
| 141-150        | 2         | 3.17%   |
| 501-1000       | 2         | 3.17%   |
| More than 1000 | 1         | 1.59%   |
| 351-500        | 1         | 1.59%   |
| 251-300        | 1         | 1.59%   |
| Unknown        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 32.79%  |
| 51-100        | 14        | 22.95%  |
| 101-120       | 13        | 21.31%  |
| 161-240       | 8         | 13.11%  |
| More than 240 | 5         | 8.2%    |
| Unknown       | 1         | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 40        | 74.07%  |
| 2     | 13        | 24.07%  |
| 3     | 1         | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 37        | 41.11%  |
| Realtek Semiconductor             | 31        | 34.44%  |
| Qualcomm Atheros                  | 5         | 5.56%   |
| Ralink Technology                 | 3         | 3.33%   |
| Broadcom Limited                  | 3         | 3.33%   |
| Huawei Technologies               | 2         | 2.22%   |
| DisplayLink                       | 2         | 2.22%   |
| Broadcom                          | 2         | 2.22%   |
| TP-Link                           | 1         | 1.11%   |
| MediaTek                          | 1         | 1.11%   |
| Ericsson Business Mobile Networks | 1         | 1.11%   |
| D-Link                            | 1         | 1.11%   |
| ASIX Electronics                  | 1         | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 23.53%  |
| Intel Wi-Fi 6 AX200                                               | 10        | 9.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 4.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 3.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.96%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.96%   |
| Intel Wireless 3165                                               | 2         | 1.96%   |
| Intel Wireless 3160                                               | 2         | 1.96%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.96%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.98%   |
| Realtek 802.11ac NIC                                              | 1         | 0.98%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.98%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.98%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.98%   |
| Intel Wireless-AC 9260                                            | 1         | 0.98%   |
| Intel Wireless 8265 / 8275                                        | 1         | 0.98%   |
| Intel Wireless 7260                                               | 1         | 0.98%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.98%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 0.98%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.98%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.98%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.98%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.98%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.98%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.98%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.98%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.98%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 0.98%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 0.98%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.98%   |
| Intel Alder Lake-U CNVi: Wireless-AC                              | 1         | 0.98%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 62.75%  |
| Realtek Semiconductor | 5         | 9.8%    |
| Qualcomm Atheros      | 4         | 7.84%   |
| Ralink Technology     | 3         | 5.88%   |
| Broadcom Limited      | 2         | 3.92%   |
| Broadcom              | 2         | 3.92%   |
| TP-Link               | 1         | 1.96%   |
| MediaTek              | 1         | 1.96%   |
| D-Link                | 1         | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 10        | 19.61%  |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 7.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 3.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 3.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 3.92%   |
| Intel Wireless 3165                                                  | 2         | 3.92%   |
| Intel Wireless 3160                                                  | 2         | 3.92%   |
| Intel Wi-Fi 6 AX201                                                  | 2         | 3.92%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.96%   |
| Realtek 802.11ac NIC                                                 | 1         | 1.96%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 1.96%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1         | 1.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 1         | 1.96%   |
| Intel Wireless-AC 9260                                               | 1         | 1.96%   |
| Intel Wireless 8265 / 8275                                           | 1         | 1.96%   |
| Intel Wireless 7260                                                  | 1         | 1.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1         | 1.96%   |
| Intel Ultimate N WiFi Link 5300                                      | 1         | 1.96%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 1.96%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 1         | 1.96%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 1.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 1.96%   |
| Intel Alder Lake-U CNVi: Wireless-AC                                 | 1         | 1.96%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1         | 1.96%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1         | 1.96%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter           | 1         | 1.96%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 1         | 1.96%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 1         | 1.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 1.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 29        | 61.7%   |
| Intel                 | 12        | 25.53%  |
| DisplayLink           | 2         | 4.26%   |
| Qualcomm Atheros      | 1         | 2.13%   |
| Broadcom Limited      | 1         | 2.13%   |
| Broadcom              | 1         | 2.13%   |
| ASIX Electronics      | 1         | 2.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 50%     |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 10.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.17%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.08%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.08%   |
| Intel Ethernet Controller I225-V                                  | 1         | 2.08%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.08%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.08%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 2.08%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 2.08%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.08%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.08%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 2.08%   |
| DisplayLink Plugable UD-3900H                                     | 1         | 2.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.08%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 2.08%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 50.52%  |
| Ethernet | 45        | 46.39%  |
| Modem    | 3         | 3.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 35        | 63.64%  |
| Ethernet | 20        | 36.36%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 34        | 62.96%  |
| 1     | 17        | 31.48%  |
| 3     | 2         | 3.7%    |
| 0     | 1         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| Yes  | 27        | 50%     |
| No   | 27        | 50%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 66.67%  |
| Realtek Semiconductor           | 3         | 6.67%   |
| Foxconn / Hon Hai               | 3         | 6.67%   |
| Cambridge Silicon Radio         | 3         | 6.67%   |
| Apple                           | 2         | 4.44%   |
| Qualcomm Atheros Communications | 1         | 2.22%   |
| IMC Networks                    | 1         | 2.22%   |
| Broadcom                        | 1         | 2.22%   |
| ASUSTek Computer                | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 10        | 22.22%  |
| Intel Bluetooth wireless interface                  | 7         | 15.56%  |
| Intel Bluetooth Device                              | 5         | 11.11%  |
| Intel AX201 Bluetooth                               | 5         | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 6.67%   |
| Realtek Bluetooth Radio                             | 2         | 4.44%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.22%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.22%   |
| Intel AX210 Bluetooth                               | 1         | 2.22%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.22%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 2.22%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 2.22%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 2.22%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.22%   |
| ASUS ASUS USB-BT500                                 | 1         | 2.22%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.22%   |
| Apple Bluetooth Host Controller                     | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 40        | 54.05%  |
| Nvidia                                 | 16        | 21.62%  |
| AMD                                    | 14        | 18.92%  |
| Sony Ericsson Mobile Communications AB | 1         | 1.35%   |
| Kingston Technology                    | 1         | 1.35%   |
| JMTek                                  | 1         | 1.35%   |
| GN Netcom                              | 1         | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 15.12%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 5.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 5.81%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 4.65%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 4.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 4.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 3.49%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 3.49%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 2.33%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 2.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.33%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.33%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.33%   |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.16%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.16%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.16%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.16%   |
| Kingston Technology HyperX QuadCast S                                      | 1         | 1.16%   |
| JMTek SADES Audio Device                                                   | 1         | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.16%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.16%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 1.16%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.16%   |
| Intel Alder Lake-U cAVS (Audio, Voice, Speech)                             | 1         | 1.16%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.16%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 1.16%   |
| GN Netcom Jabra Link 380                                                   | 1         | 1.16%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.16%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 5         | 27.78%  |
| Samsung Electronics | 5         | 27.78%  |
| Unknown             | 2         | 11.11%  |
| Unknown (ABCD)      | 1         | 5.56%   |
| Micron Technology   | 1         | 5.56%   |
| KLEVV               | 1         | 5.56%   |
| Elpida              | 1         | 5.56%   |
| Crucial             | 1         | 5.56%   |
| ASint Technology    | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 2         | 11.11%  |
| Unknown                                                        | 2         | 11.11%  |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 5.56%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 5.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 5.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 5.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s      | 1         | 5.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 5.56%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 5.56%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s         | 1         | 5.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 5.56%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s            | 1         | 5.56%   |
| KLEVV RAM KD48GU880-32A160X 8GB DIMM DDR4 2666MT/s             | 1         | 5.56%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s          | 1         | 5.56%   |
| Crucial RAM CT16G4DFRA32A.C8FE 16GB DIMM DDR4 3200MT/s         | 1         | 5.56%   |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s             | 1         | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 60%     |
| DDR3   | 4         | 26.67%  |
| LPDDR5 | 1         | 6.67%   |
| LPDDR4 | 1         | 6.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 73.33%  |
| DIMM         | 3         | 20%     |
| Row Of Chips | 1         | 6.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 5         | 29.41%  |
| 8192  | 5         | 29.41%  |
| 2048  | 3         | 17.65%  |
| 32768 | 2         | 11.76%  |
| 4096  | 2         | 11.76%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 6         | 40%     |
| 1600  | 3         | 20%     |
| 8400  | 1         | 6.67%   |
| 6400  | 1         | 6.67%   |
| 2667  | 1         | 6.67%   |
| 2666  | 1         | 6.67%   |
| 2400  | 1         | 6.67%   |
| 1067  | 1         | 6.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 100%    |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 17        | 47.22%  |
| Bison Electronics                      | 3         | 8.33%   |
| Suyin                                  | 2         | 5.56%   |
| Sunplus Innovation Technology          | 2         | 5.56%   |
| Microdia                               | 2         | 5.56%   |
| IMC Networks                           | 2         | 5.56%   |
| Sony Ericsson Mobile Communications AB | 1         | 2.78%   |
| Ricoh                                  | 1         | 2.78%   |
| Realtek Semiconductor                  | 1         | 2.78%   |
| Luxvisions Innotech Limited            | 1         | 2.78%   |
| Lite-On Technology                     | 1         | 2.78%   |
| Generalplus Technology                 | 1         | 2.78%   |
| Apple                                  | 1         | 2.78%   |
| Alpha Imaging Technology               | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated IR Camera                         | 5         | 13.89%  |
| Chicony HD Webcam                                    | 3         | 8.33%   |
| Chicony FHD Webcam                                   | 3         | 8.33%   |
| IMC Networks Integrated Camera                       | 2         | 5.56%   |
| Suyin RGBIR Camera                                   | 1         | 2.78%   |
| Suyin HP TrueVision HD                               | 1         | 2.78%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 2.78%   |
| Sunplus Asus Webcam                                  | 1         | 2.78%   |
| Sony Ericsson Mobile AB XQ-CC54                      | 1         | 2.78%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 2.78%   |
| Realtek Integrated Webcam                            | 1         | 2.78%   |
| Microdia Sonix USB 2.0 Camera                        | 1         | 2.78%   |
| Microdia Integrated_Webcam_FHD                       | 1         | 2.78%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 2.78%   |
| Lite-On HP Wide Vision HD Camera                     | 1         | 2.78%   |
| Generalplus GENERAL WEBCAM                           | 1         | 2.78%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 2.78%   |
| Chicony USB2.0 Camera                                | 1         | 2.78%   |
| Chicony USB 2.0 Camera                               | 1         | 2.78%   |
| Chicony Integrated Camera                            | 1         | 2.78%   |
| Chicony FJ Camera                                    | 1         | 2.78%   |
| Chicony 1.3M Webcam                                  | 1         | 2.78%   |
| Bison Lenovo Integrated Webcam                       | 1         | 2.78%   |
| Bison Lenovo EasyCamera                              | 1         | 2.78%   |
| Bison HD Webcam                                      | 1         | 2.78%   |
| Apple FaceTime HD Camera                             | 1         | 2.78%   |
| Alpha Imaging Integrated_Webcam_8M                   | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 44.44%  |
| Synaptics             | 4         | 44.44%  |
| LighTuning Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics UWP WBDI                                | 2         | 22.22%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 11.11%  |
| Validity Sensors VFS491                           | 1         | 11.11%  |
| Validity Sensors VFS Fingerprint sensor           | 1         | 11.11%  |
| Validity Sensors Fingerprint scanner              | 1         | 11.11%  |
| LighTuning Fingerprint Reader                     | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| Alcor Micro | 2         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 2         | 50%     |
| Broadcom 5880                       | 1         | 25%     |
| Broadcom 58200                      | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 32        | 59.26%  |
| 1     | 21        | 38.89%  |
| 3     | 1         | 1.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 36%     |
| Multimedia controller | 6         | 24%     |
| Chipcard              | 4         | 16%     |
| Net/wireless          | 2         | 8%      |
| Graphics card         | 2         | 8%      |
| Modem                 | 1         | 4%      |
| Camera                | 1         | 4%      |

