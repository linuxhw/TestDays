TUXEDO OS - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for TUXEDO OS.

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

Total: 54

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | ThinkPad P1 Gen 3 20TJS1... | [c47936b50c](https://linux-hardware.org/?probe=c47936b50c) | Jun 09, 2023 |
| Dell     | Venue 11 Pro 7130 vPro      | [c16266c1c9](https://linux-hardware.org/?probe=c16266c1c9) | Jun 04, 2023 |
| Apple    | MacBookAir7,2               | [f75fb35204](https://linux-hardware.org/?probe=f75fb35204) | May 28, 2023 |
| ASUSTek  | K55VJ                       | [66c9773a5f](https://linux-hardware.org/?probe=66c9773a5f) | May 26, 2023 |
| ASUSTek  | K55VJ                       | [65cc5e45b0](https://linux-hardware.org/?probe=65cc5e45b0) | May 26, 2023 |
| Lenovo   | G580 20150                  | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| TUXEDO   | Polaris 15 AMD Gen1         | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| Lenovo   | IdeaPad N581 7505           | [5d340c1aa2](https://linux-hardware.org/?probe=5d340c1aa2) | May 04, 2023 |
| HP       | Pavilion dv6                | [be01072653](https://linux-hardware.org/?probe=be01072653) | May 03, 2023 |
| TUXEDO   | Stellaris/Polaris AMD Ge... | [756500f10b](https://linux-hardware.org/?probe=756500f10b) | May 03, 2023 |
| HP       | Pavilion dv6                | [87f0c054fa](https://linux-hardware.org/?probe=87f0c054fa) | May 03, 2023 |
| TUXEDO   | InfinityBook Pro 14 Gen6    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| Dell     | Inspiron 16 5630            | [7bfe5bb892](https://linux-hardware.org/?probe=7bfe5bb892) | Apr 27, 2023 |
| Dell     | Latitude 7530               | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| TUXEDO   | Pulse 15 Gen2               | [fd2ad16b59](https://linux-hardware.org/?probe=fd2ad16b59) | Apr 22, 2023 |
| Dell     | Vostro 3550                 | [3b77631ed6](https://linux-hardware.org/?probe=3b77631ed6) | Apr 04, 2023 |
| Unknown  | Unknown                     | [22c0e4cdec](https://linux-hardware.org/?probe=22c0e4cdec) | Apr 02, 2023 |
| Lenovo   | ThinkPad T490 20N3SBU219    | [b8e8125150](https://linux-hardware.org/?probe=b8e8125150) | Mar 27, 2023 |
| TUXEDO   | InfinityBook Pro Gen7 (M... | [885b757cdc](https://linux-hardware.org/?probe=885b757cdc) | Mar 24, 2023 |
| TUXEDO   | InfinityBook Pro Gen7 (M... | [5e01f2c134](https://linux-hardware.org/?probe=5e01f2c134) | Mar 22, 2023 |
| TUXEDO   | Polaris AMD Gen3 (CZN)      | [0db668b5ec](https://linux-hardware.org/?probe=0db668b5ec) | Mar 18, 2023 |
| TUXEDO   | InfinityBook S 15/17 Gen... | [094b530ce7](https://linux-hardware.org/?probe=094b530ce7) | Mar 18, 2023 |
| TUXEDO   | Pulse 15 Gen1               | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO   | Pulse 15 Gen1               | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| TUXEDO   | InfinityBook Pro 14 Gen6    | [3fcbfecb5a](https://linux-hardware.org/?probe=3fcbfecb5a) | Mar 14, 2023 |
| Dell     | Precision 7720              | [dbe0d4c5c4](https://linux-hardware.org/?probe=dbe0d4c5c4) | Mar 12, 2023 |
| Dell     | Vostro 3550                 | [40a0328a5f](https://linux-hardware.org/?probe=40a0328a5f) | Mar 11, 2023 |
| TUXEDO   | XMG FUSION 15 (XFU15L19)    | [3cde6f345c](https://linux-hardware.org/?probe=3cde6f345c) | Mar 10, 2023 |
| Fujitsu  | LIFEBOOK U7412              | [980dd72471](https://linux-hardware.org/?probe=980dd72471) | Mar 06, 2023 |
| TUXEDO   | Pulse 15 Gen2               | [7a21cf8349](https://linux-hardware.org/?probe=7a21cf8349) | Mar 05, 2023 |
| TUXEDO   | InfinityBook Pro Gen7 (M... | [20d14c7576](https://linux-hardware.org/?probe=20d14c7576) | Mar 04, 2023 |
| Lenovo   | G50-80 80E5                 | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| Dell     | Vostro 3550                 | [1e1da6a575](https://linux-hardware.org/?probe=1e1da6a575) | Feb 24, 2023 |
| Dell     | Vostro 3550                 | [497a8d66e5](https://linux-hardware.org/?probe=497a8d66e5) | Feb 22, 2023 |
| Dell     | Precision 7720              | [2f7837d5b6](https://linux-hardware.org/?probe=2f7837d5b6) | Feb 21, 2023 |
| TUXEDO   | Stellaris/Polaris AMD Ge... | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| HP       | EliteBook 2570p             | [ed14b057dd](https://linux-hardware.org/?probe=ed14b057dd) | Feb 09, 2023 |
| TUXEDO   | InfinityBook Pro Gen7 (M... | [4a2fcb6bd0](https://linux-hardware.org/?probe=4a2fcb6bd0) | Jan 31, 2023 |
| HP       | OMEN Laptop 15-en0xxx       | [e163d98802](https://linux-hardware.org/?probe=e163d98802) | Jan 28, 2023 |
| ASUSTek  | Zephyrus G GU502DU_GA502... | [fa53a29f7e](https://linux-hardware.org/?probe=fa53a29f7e) | Jan 01, 2023 |
| ASUSTek  | ROG Strix G713RW_G713RW     | [731b31c845](https://linux-hardware.org/?probe=731b31c845) | Dec 02, 2022 |
| TUXEDO   | N13xWU                      | [55935f091d](https://linux-hardware.org/?probe=55935f091d) | Dec 01, 2022 |
| TUXEDO   | Unknown                     | [fd06ca029c](https://linux-hardware.org/?probe=fd06ca029c) | Nov 29, 2022 |
| Lenovo   | ThinkPad T460 20FMS07000    | [5043f6c54e](https://linux-hardware.org/?probe=5043f6c54e) | Nov 20, 2022 |
| HP       | EliteBook 820 G2            | [5d82e9f6ac](https://linux-hardware.org/?probe=5d82e9f6ac) | Nov 19, 2022 |
| HP       | EliteBook 820 G2            | [9d20af2c30](https://linux-hardware.org/?probe=9d20af2c30) | Nov 19, 2022 |
| Lenovo   | ThinkPad X200 Tablet 745... | [d58eb8b2f0](https://linux-hardware.org/?probe=d58eb8b2f0) | Oct 30, 2022 |
| Lenovo   | ThinkPad X200 Tablet 745... | [032bc01698](https://linux-hardware.org/?probe=032bc01698) | Oct 30, 2022 |
| TUXEDO   | Unknown                     | [99555fc4eb](https://linux-hardware.org/?probe=99555fc4eb) | Oct 28, 2022 |
| Lenovo   | Legion 5 15ACH6H 82JU       | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| ASUSTek  | BU201LAV                    | [9d1fe7cb6f](https://linux-hardware.org/?probe=9d1fe7cb6f) | Oct 19, 2022 |
| Apple    | MacBookPro8,1               | [36e033aa01](https://linux-hardware.org/?probe=36e033aa01) | Oct 09, 2022 |
| Notebook | W65_W67RB                   | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| Acer     | TravelMate 8572T            | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| TUXEDO OS 22.04 | 41        | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 41        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 6.1.0-1009-tuxedo   | 12        | 27.27%  |
| 6.2.0-10005-tuxedo  | 9         | 20.45%  |
| 6.2.0-10007-tuxedo  | 4         | 9.09%   |
| 5.15.0-10058-tuxedo | 4         | 9.09%   |
| 5.15.0-10048-tuxedo | 4         | 9.09%   |
| 5.15.0-10053-tuxedo | 3         | 6.82%   |
| 5.15.0-10052-tuxedo | 3         | 6.82%   |
| 5.15.0-10050-tuxedo | 2         | 4.55%   |
| 6.0.0-1010-oem      | 1         | 2.27%   |
| 5.15.0-10057-tuxedo | 1         | 2.27%   |
| 5.15.0-10056-tuxedo | 1         | 2.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 18        | 40.91%  |
| 6.2.0   | 13        | 29.55%  |
| 6.1.0   | 12        | 27.27%  |
| 6.0.0   | 1         | 2.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 18        | 40.91%  |
| 6.2     | 13        | 29.55%  |
| 6.1     | 12        | 27.27%  |
| 6.0     | 1         | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 41        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| KDE5 | 41        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 41        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 33        | 78.57%  |
| SDDM    | 9         | 21.43%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| de_DE | 22        | 53.66%  |
| en_US | 10        | 24.39%  |
| en_GB | 3         | 7.32%   |
| pt_PT | 1         | 2.44%   |
| pl_PL | 1         | 2.44%   |
| fr_FR | 1         | 2.44%   |
| es_ES | 1         | 2.44%   |
| en_DK | 1         | 2.44%   |
| en_AU | 1         | 2.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 33        | 80.49%  |
| EFI  | 8         | 19.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 36        | 87.8%   |
| Btrfs | 4         | 9.76%   |
| Tmpfs | 1         | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 33        | 78.57%  |
| GPT     | 8         | 19.05%  |
| MBR     | 1         | 2.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 95.24%  |
| Yes       | 2         | 4.76%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 92.86%  |
| Yes       | 3         | 7.14%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| TUXEDO           | 16        | 39.02%  |
| Lenovo           | 6         | 14.63%  |
| Dell             | 5         | 12.2%   |
| Hewlett-Packard  | 4         | 9.76%   |
| ASUSTek Computer | 4         | 9.76%   |
| Apple            | 2         | 4.88%   |
| Notebook         | 1         | 2.44%   |
| Fujitsu          | 1         | 2.44%   |
| Acer             | 1         | 2.44%   |
| Unknown          | 1         | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 3         | 7.32%   |
| TUXEDO Stellaris/Polaris AMD Gen4   | 2         | 4.88%   |
| TUXEDO Pulse 15 Gen2                | 2         | 4.88%   |
| TUXEDO InfinityBook Pro 14 Gen6     | 2         | 4.88%   |
| TUXEDO XMG FUSION 15 (XFU15L19)     | 1         | 2.44%   |
| TUXEDO Pulse 15 Gen1                | 1         | 2.44%   |
| TUXEDO Polaris AMD Gen3 (CZN)       | 1         | 2.44%   |
| TUXEDO Polaris 15 AMD Gen1          | 1         | 2.44%   |
| TUXEDO N13xWU                       | 1         | 2.44%   |
| TUXEDO InfinityBook S 15/17 Gen7    | 1         | 2.44%   |
| TUXEDO InfinityBook Pro Gen7 (MK2)  | 1         | 2.44%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 1         | 2.44%   |
| Notebook W65_W67RB                  | 1         | 2.44%   |
| Lenovo ThinkPad X200 Tablet 7450WN9 | 1         | 2.44%   |
| Lenovo ThinkPad T490 20N3SBU219     | 1         | 2.44%   |
| Lenovo ThinkPad P1 Gen 3 20TJS1W700 | 1         | 2.44%   |
| Lenovo Legion 5 15ACH6H 82JU        | 1         | 2.44%   |
| Lenovo IdeaPad N581 7505            | 1         | 2.44%   |
| Lenovo G50-80 80E5                  | 1         | 2.44%   |
| HP Pavilion dv6                     | 1         | 2.44%   |
| HP OMEN Laptop 15-en0xxx            | 1         | 2.44%   |
| HP EliteBook 820 G2                 | 1         | 2.44%   |
| HP EliteBook 2570p                  | 1         | 2.44%   |
| Fujitsu LIFEBOOK U7412              | 1         | 2.44%   |
| Dell Vostro 3550                    | 1         | 2.44%   |
| Dell Venue 11 Pro 7130 vPro         | 1         | 2.44%   |
| Dell Precision 7720                 | 1         | 2.44%   |
| Dell Latitude 7530                  | 1         | 2.44%   |
| Dell Inspiron 16 5630               | 1         | 2.44%   |
| ASUS Zephyrus G GU502DU_GA502DU     | 1         | 2.44%   |
| ASUS ROG Strix G713RW_G713RW        | 1         | 2.44%   |
| ASUS K55VJ                          | 1         | 2.44%   |
| ASUS BU201LAV                       | 1         | 2.44%   |
| Apple MacBookPro8,1                 | 1         | 2.44%   |
| Apple MacBookAir7,2                 | 1         | 2.44%   |
| Acer TravelMate 8572T               | 1         | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| TUXEDO InfinityBook | 5         | 12.2%   |
| TUXEDO Pulse        | 3         | 7.32%   |
| Lenovo ThinkPad     | 3         | 7.32%   |
| Unknown             | 3         | 7.32%   |
| TUXEDO Stellaris    | 2         | 4.88%   |
| TUXEDO Polaris      | 2         | 4.88%   |
| HP EliteBook        | 2         | 4.88%   |
| TUXEDO XMG          | 1         | 2.44%   |
| TUXEDO N13xWU       | 1         | 2.44%   |
| Notebook W65        | 1         | 2.44%   |
| Lenovo Legion       | 1         | 2.44%   |
| Lenovo IdeaPad      | 1         | 2.44%   |
| Lenovo G50-80       | 1         | 2.44%   |
| HP Pavilion         | 1         | 2.44%   |
| HP OMEN             | 1         | 2.44%   |
| Fujitsu LIFEBOOK    | 1         | 2.44%   |
| Dell Vostro         | 1         | 2.44%   |
| Dell Venue          | 1         | 2.44%   |
| Dell Precision      | 1         | 2.44%   |
| Dell Latitude       | 1         | 2.44%   |
| Dell Inspiron       | 1         | 2.44%   |
| ASUS Zephyrus       | 1         | 2.44%   |
| ASUS ROG            | 1         | 2.44%   |
| ASUS K55VJ          | 1         | 2.44%   |
| ASUS BU201LAV       | 1         | 2.44%   |
| Apple MacBookPro8   | 1         | 2.44%   |
| Apple MacBookAir7   | 1         | 2.44%   |
| Acer TravelMate     | 1         | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 9         | 21.95%  |
| 2021 | 5         | 12.2%   |
| 2015 | 5         | 12.2%   |
| 2020 | 4         | 9.76%   |
| 2019 | 4         | 9.76%   |
| 2012 | 3         | 7.32%   |
| 2023 | 2         | 4.88%   |
| 2017 | 2         | 4.88%   |
| 2014 | 2         | 4.88%   |
| 2011 | 2         | 4.88%   |
| 2010 | 1         | 2.44%   |
| 2009 | 1         | 2.44%   |
| 2008 | 1         | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 41        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 41        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 41        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 11        | 26.83%  |
| 32.01-64.0  | 9         | 21.95%  |
| 16.01-24.0  | 6         | 14.63%  |
| 4.01-8.0    | 5         | 12.2%   |
| 3.01-4.0    | 4         | 9.76%   |
| 64.01-256.0 | 4         | 9.76%   |
| 24.01-32.0  | 2         | 4.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 38.1%   |
| 2.01-3.0   | 9         | 21.43%  |
| 1.01-2.0   | 9         | 21.43%  |
| 3.01-4.0   | 5         | 11.9%   |
| 16.01-24.0 | 2         | 4.76%   |
| 8.01-16.0  | 1         | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 24        | 57.14%  |
| 2      | 16        | 38.1%   |
| 3      | 2         | 4.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 78.05%  |
| Yes       | 9         | 21.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 80.49%  |
| No        | 8         | 19.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 97.56%  |
| No        | 1         | 2.44%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 87.8%   |
| No        | 5         | 12.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 22        | 53.66%  |
| USA         | 5         | 12.2%   |
| UK          | 2         | 4.88%   |
| Switzerland | 2         | 4.88%   |
| Portugal    | 2         | 4.88%   |
| Turkey      | 1         | 2.44%   |
| Spain       | 1         | 2.44%   |
| Poland      | 1         | 2.44%   |
| France      | 1         | 2.44%   |
| Denmark     | 1         | 2.44%   |
| Czechia     | 1         | 2.44%   |
| Austria     | 1         | 2.44%   |
| Australia   | 1         | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Schweinfurt        | 2         | 4.88%   |
| Munich             | 2         | 4.88%   |
| Zurich             | 1         | 2.44%   |
| Zabrze             | 1         | 2.44%   |
| Watertown          | 1         | 2.44%   |
| Walsall            | 1         | 2.44%   |
| Vienna             | 1         | 2.44%   |
| Stuttgart          | 1         | 2.44%   |
| Stockstadt am Main | 1         | 2.44%   |
| Seattle            | 1         | 2.44%   |
| Rio Maior          | 1         | 2.44%   |
| Reno               | 1         | 2.44%   |
| Redcar             | 1         | 2.44%   |
| Prague             | 1         | 2.44%   |
| Paris              | 1         | 2.44%   |
| Neuwied            | 1         | 2.44%   |
| Mannheim           | 1         | 2.44%   |
| Lucerne            | 1         | 2.44%   |
| Lippstadt          | 1         | 2.44%   |
| Leipzig            | 1         | 2.44%   |
| Langenhagen        | 1         | 2.44%   |
| Laage              | 1         | 2.44%   |
| Jessen             | 1         | 2.44%   |
| Istanbul           | 1         | 2.44%   |
| Husum              | 1         | 2.44%   |
| Herzberg           | 1         | 2.44%   |
| Heilbronn          | 1         | 2.44%   |
| Hamburg            | 1         | 2.44%   |
| Friedrichstadt     | 1         | 2.44%   |
| Ethridge           | 1         | 2.44%   |
| Ehringshausen      | 1         | 2.44%   |
| Coswig             | 1         | 2.44%   |
| Bronshoj           | 1         | 2.44%   |
| Brisbane           | 1         | 2.44%   |
| Berlin             | 1         | 2.44%   |
| Barcelona          | 1         | 2.44%   |
| Augsburg           | 1         | 2.44%   |
| Arlington          | 1         | 2.44%   |
| Amora              | 1         | 2.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 25     | 37.04%  |
| Sandisk             | 5         | 6      | 9.26%   |
| Seagate             | 4         | 4      | 7.41%   |
| Hitachi             | 4         | 6      | 7.41%   |
| WDC                 | 2         | 2      | 3.7%    |
| SPCC                | 2         | 2      | 3.7%    |
| SK hynix            | 2         | 3      | 3.7%    |
| Phison Electronics  | 2         | 2      | 3.7%    |
| Micron Technology   | 2         | 2      | 3.7%    |
| USB3.0              | 1         | 1      | 1.85%   |
| Unknown             | 1         | 1      | 1.85%   |
| Toshiba             | 1         | 1      | 1.85%   |
| OWC                 | 1         | 1      | 1.85%   |
| LITEONIT            | 1         | 1      | 1.85%   |
| Kingchuxing         | 1         | 1      | 1.85%   |
| Intenso             | 1         | 1      | 1.85%   |
| Intel               | 1         | 1      | 1.85%   |
| CT1000BX            | 1         | 1      | 1.85%   |
| Crucial             | 1         | 1      | 1.85%   |
| Apple               | 1         | 1      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 5         | 8.93%   |
| Samsung SSD 980 1TB                                 | 4         | 7.14%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 2         | 3.57%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 3.57%   |
| Samsung SSD 980 500GB                               | 2         | 3.57%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2         | 3.57%   |
| Hitachi HTS727550A9E364 500GB                       | 2         | 3.57%   |
| WDC WD3200BPVT-24JJ5T0 320GB                        | 1         | 1.79%   |
| WDC WD Elements SE SSD 1TB                          | 1         | 1.79%   |
| USB3.0 Super Speed 1TB                              | 1         | 1.79%   |
| Unknown MMC Card  2GB                               | 1         | 1.79%   |
| Toshiba XG4 NVMe SSD Controller 256GB               | 1         | 1.79%   |
| SPCC M.2 SSD 256GB                                  | 1         | 1.79%   |
| SPCC M.2 PCIe SSD 1TB                               | 1         | 1.79%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB             | 1         | 1.79%   |
| SK hynix SC311 SATA 256GB SSD                       | 1         | 1.79%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1.79%   |
| Seagate ST500LM034-2GH17A 500GB                     | 1         | 1.79%   |
| Seagate Expansion 1TB                               | 1         | 1.79%   |
| Seagate BarraCuda Q5 ZP500CV30001 500GB             | 1         | 1.79%   |
| Sandisk WD PC SN735 SDBPNHH-1T00-1002 1TB           | 1         | 1.79%   |
| Sandisk WD Black SN850 500GB                        | 1         | 1.79%   |
| SanDisk SDSSDA240G 240GB                            | 1         | 1.79%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD                 | 1         | 1.79%   |
| Samsung SSD 980 PRO 500GB                           | 1         | 1.79%   |
| Samsung SSD 860 PRO 512GB                           | 1         | 1.79%   |
| Samsung SSD 860 EVO M.2 250GB                       | 1         | 1.79%   |
| Samsung SSD 850 EVO 500GB                           | 1         | 1.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 1         | 1.79%   |
| Samsung MZALQ256HBJD-00BL1 256GB                    | 1         | 1.79%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 1         | 1.79%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 1         | 1.79%   |
| OWC Mercury Electra 3G SSD                          | 1         | 1.79%   |
| Micron MTFDKBA256TFK-1BC15ABFA 256GB                | 1         | 1.79%   |
| Micron MTFDDAK128MBF-1AN1ZABHA 128GB SSD            | 1         | 1.79%   |
| LITEONIT LJT-128L6G-11 M.2 2260 128GB SSD           | 1         | 1.79%   |
| Kingchuxing 512GB                                   | 1         | 1.79%   |
| Intenso SSD SATAIII 120GB                           | 1         | 1.79%   |
| Intel SSD 660P Series 512GB                         | 1         | 1.79%   |
| Hitachi HTS547575A9E384 752GB                       | 1         | 1.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 4         | 6      | 44.44%  |
| Seagate | 3         | 3      | 33.33%  |
| WDC     | 1         | 1      | 11.11%  |
| USB3.0  | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 20%     |
| SanDisk             | 2         | 2      | 13.33%  |
| WDC                 | 1         | 1      | 6.67%   |
| SPCC                | 1         | 1      | 6.67%   |
| SK hynix            | 1         | 2      | 6.67%   |
| OWC                 | 1         | 1      | 6.67%   |
| Micron Technology   | 1         | 1      | 6.67%   |
| LITEONIT            | 1         | 1      | 6.67%   |
| Intenso             | 1         | 1      | 6.67%   |
| CT1000BX            | 1         | 1      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |
| Apple               | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 24        | 34     | 48.98%  |
| SSD     | 14        | 16     | 28.57%  |
| HDD     | 9         | 11     | 18.37%  |
| MMC     | 1         | 1      | 2.04%   |
| Unknown | 1         | 1      | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 24        | 34     | 50%     |
| SATA | 19        | 24     | 39.58%  |
| SAS  | 4         | 4      | 8.33%   |
| MMC  | 1         | 1      | 2.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 20     | 68.18%  |
| 0.51-1.0   | 7         | 7      | 31.82%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 13        | 31.71%  |
| 101-250        | 9         | 21.95%  |
| 251-500        | 8         | 19.51%  |
| 1001-2000      | 4         | 9.76%   |
| 2001-3000      | 2         | 4.88%   |
| More than 3000 | 1         | 2.44%   |
| 21-50          | 1         | 2.44%   |
| 1-20           | 1         | 2.44%   |
| 51-100         | 1         | 2.44%   |
| Unknown        | 1         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 13        | 30.23%  |
| 1-20      | 12        | 27.91%  |
| 101-250   | 8         | 18.6%   |
| 251-500   | 3         | 6.98%   |
| 51-100    | 3         | 6.98%   |
| 501-1000  | 2         | 4.65%   |
| 1001-2000 | 1         | 2.33%   |
| Unknown   | 1         | 2.33%   |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 33        | 51     | 78.57%  |
| Works    | 9         | 12     | 21.43%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 21        | 40.38%  |
| Samsung Electronics          | 18        | 34.62%  |
| SanDisk                      | 3         | 5.77%   |
| AMD                          | 3         | 5.77%   |
| Phison Electronics           | 2         | 3.85%   |
| Toshiba America Info Systems | 1         | 1.92%   |
| SK hynix                     | 1         | 1.92%   |
| Silicon Motion               | 1         | 1.92%   |
| Seagate Technology           | 1         | 1.92%   |
| Micron Technology            | 1         | 1.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 8         | 15.09%  |
| Samsung NVMe SSD Controller 980                                              | 6         | 11.32%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 7.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 3         | 5.66%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 3         | 5.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 5.66%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 3         | 5.66%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 2         | 3.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 3.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 3.77%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                         | 1         | 1.89%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 1         | 1.89%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 1.89%   |
| Seagate Non-Volatile memory controller                                       | 1         | 1.89%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                   | 1         | 1.89%   |
| SanDisk Non-Volatile memory controller                                       | 1         | 1.89%   |
| Samsung Electronics SATA controller                                          | 1         | 1.89%   |
| Phison PS5013 E13 NVMe Controller                                            | 1         | 1.89%   |
| Phison E16 PCIe4 NVMe Controller                                             | 1         | 1.89%   |
| Micron NVMe Storage Controller                                               | 1         | 1.89%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation        | 1         | 1.89%   |
| Intel SSD 660P Series                                                        | 1         | 1.89%   |
| Intel SATA Controller [RAID mode]                                            | 1         | 1.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 1.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 1         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 1.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 24        | 50%     |
| SATA | 21        | 43.75%  |
| RAID | 3         | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 30        | 73.17%  |
| AMD    | 11        | 26.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 4.88%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 4.88%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 2         | 4.88%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 2         | 4.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 4.88%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 4.88%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 2.44%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 2.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.44%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 2.44%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 2.44%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 2.44%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 2.44%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 2.44%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 2.44%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2.44%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 2.44%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 2.44%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 2.44%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 2.44%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 2.44%   |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1         | 2.44%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 2.44%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 2.44%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz          | 1         | 2.44%   |
| Intel Celeron CPU 1037U @ 1.80GHz             | 1         | 2.44%   |
| Intel 13th Gen Core i7-1360P                  | 1         | 2.44%   |
| Intel 12th Gen Core i7-1260P                  | 1         | 2.44%   |
| Intel 12th Gen Core i7-1255U                  | 1         | 2.44%   |
| Intel 12th Gen Core i3-1215U                  | 1         | 2.44%   |
| AMD Ryzen 9 6900HX with Radeon Graphics       | 1         | 2.44%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 2.44%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 2.44%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 2.44%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 12        | 29.27%  |
| Other            | 8         | 19.51%  |
| AMD Ryzen 7      | 7         | 17.07%  |
| Intel Core i5    | 6         | 14.63%  |
| AMD Ryzen 5      | 3         | 7.32%   |
| Intel Xeon       | 1         | 2.44%   |
| Intel Pentium    | 1         | 2.44%   |
| Intel Core 2 Duo | 1         | 2.44%   |
| Intel Celeron    | 1         | 2.44%   |
| AMD Ryzen 9      | 1         | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 11        | 26.83%  |
| 2      | 11        | 26.83%  |
| 8      | 7         | 17.07%  |
| 6      | 7         | 17.07%  |
| 14     | 2         | 4.88%   |
| 12     | 2         | 4.88%   |
| 10     | 1         | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 41        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 38        | 92.68%  |
| 1      | 3         | 7.32%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 41        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 36        | 85.71%  |
| 0x906ea | 1         | 2.38%   |
| 0x906e9 | 1         | 2.38%   |
| 0x906a4 | 1         | 2.38%   |
| 0x906a3 | 1         | 2.38%   |
| 0x806c1 | 1         | 2.38%   |
| 0x306d4 | 1         | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 8         | 19.51%  |
| KabyLake         | 6         | 14.63%  |
| IvyBridge        | 4         | 9.76%   |
| Zen 2            | 3         | 7.32%   |
| SandyBridge      | 3         | 7.32%   |
| Broadwell        | 3         | 7.32%   |
| Alderlake Hybrid | 3         | 7.32%   |
| Zen 3            | 2         | 4.88%   |
| TigerLake        | 2         | 4.88%   |
| Haswell          | 2         | 4.88%   |
| Zen+             | 1         | 2.44%   |
| Westmere         | 1         | 2.44%   |
| Skylake          | 1         | 2.44%   |
| Penryn           | 1         | 2.44%   |
| CometLake        | 1         | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 29        | 50%     |
| Nvidia | 15        | 25.86%  |
| AMD    | 14        | 24.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 4         | 6.9%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 4         | 6.9%    |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 6.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 3         | 5.17%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 3         | 5.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 5.17%   |
| AMD Renoir                                                                    | 3         | 5.17%   |
| AMD Rembrandt [Radeon 680M]                                                   | 3         | 5.17%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                 | 2         | 3.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 3.45%   |
| Intel HD Graphics 5500                                                        | 2         | 3.45%   |
| AMD Lucienne                                                                  | 2         | 3.45%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 3.45%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 1.72%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 1.72%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 1.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.72%   |
| Nvidia GF108M [GeForce GT 635M]                                               | 1         | 1.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.72%   |
| Intel UHD Graphics 620                                                        | 1         | 1.72%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 1         | 1.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.72%   |
| Intel HD Graphics 630                                                         | 1         | 1.72%   |
| Intel HD Graphics 6000                                                        | 1         | 1.72%   |
| Intel HD Graphics 530                                                         | 1         | 1.72%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                | 1         | 1.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.72%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 1         | 1.72%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                       | 1         | 1.72%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                 | 1         | 1.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 1.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.72%   |
| AMD Baffin [Radeon Pro WX 4130/4150]                                          | 1         | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 47.62%  |
| AMD + Nvidia   | 8         | 19.05%  |
| Intel + Nvidia | 6         | 14.29%  |
| 1 x AMD        | 4         | 9.52%   |
| Intel + AMD    | 3         | 7.14%   |
| 1 x Nvidia     | 1         | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 28        | 68.29%  |
| Proprietary | 13        | 31.71%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 69.05%  |
| 5.01-6.0   | 8         | 19.05%  |
| 7.01-8.0   | 2         | 4.76%   |
| 1.01-2.0   | 2         | 4.76%   |
| 3.01-4.0   | 1         | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 13        | 25.49%  |
| AU Optronics        | 8         | 15.69%  |
| Samsung Electronics | 5         | 9.8%    |
| LG Display          | 5         | 9.8%    |
| CSO                 | 3         | 5.88%   |
| Chimei Innolux      | 2         | 3.92%   |
| Apple               | 2         | 3.92%   |
| AOC                 | 2         | 3.92%   |
| Acer                | 2         | 3.92%   |
| Yamaha              | 1         | 1.96%   |
| Sharp               | 1         | 1.96%   |
| SGT                 | 1         | 1.96%   |
| RTK                 | 1         | 1.96%   |
| PANDA               | 1         | 1.96%   |
| Lenovo              | 1         | 1.96%   |
| Dell                | 1         | 1.96%   |
| BenQ                | 1         | 1.96%   |
| ASUSTek Computer    | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 3         | 5.66%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 3         | 5.66%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 2         | 3.77%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 3.77%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 1.89%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 1.89%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 1.89%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 376x301mm 19.0-inch       | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch   | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch   | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch   | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 1.89%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 1.89%   |
| RTK Wimaxit FHD RTK5A5B 1920x1080 344x195mm 15.6-inch                   | 1         | 1.89%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 1.89%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch            | 1         | 1.89%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 1         | 1.89%   |
| LG Display LCD Monitor LGD0545 3200x1800 293x165mm 13.2-inch            | 1         | 1.89%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch            | 1         | 1.89%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 1.89%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                 | 1         | 1.89%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 355x199mm 16.0-inch        | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch         | 1         | 1.89%   |
| BOE LCD Monitor BOE0A94 1920x1080 309x174mm 14.0-inch                   | 1         | 1.89%   |
| BOE LCD Monitor BOE0A67 2560x1440 344x194mm 15.5-inch                   | 1         | 1.89%   |
| BOE LCD Monitor BOE0A59 1920x1200 345x215mm 16.0-inch                   | 1         | 1.89%   |
| BOE LCD Monitor BOE0A3B 2560x1600 344x215mm 16.0-inch                   | 1         | 1.89%   |
| BOE LCD Monitor BOE0A00 1920x1080 382x215mm 17.3-inch                   | 1         | 1.89%   |
| BOE LCD Monitor BOE0977 2560x1440 381x214mm 17.2-inch                   | 1         | 1.89%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                   | 1         | 1.89%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                   | 1         | 1.89%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                      | 1         | 1.89%   |
| AU Optronics LCD Monitor AUOB69B 1920x1080 344x193mm 15.5-inch          | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO4599 1920x1080 344x194mm 15.5-inch          | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch           | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch           | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch           | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch          | 1         | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 40.82%  |
| 1366x768 (WXGA)    | 8         | 16.33%  |
| 2560x1440 (QHD)    | 6         | 12.24%  |
| 3840x2160 (4K)     | 3         | 6.12%   |
| 2880x1800          | 3         | 6.12%   |
| 1280x800 (WXGA)    | 2         | 4.08%   |
| 3200x1800 (QHD+)   | 1         | 2.04%   |
| 2560x1600          | 1         | 2.04%   |
| 1920x540           | 1         | 2.04%   |
| 1920x1200 (WUXGA)  | 1         | 2.04%   |
| 1680x1050 (WSXGA+) | 1         | 2.04%   |
| 1440x900 (WXGA+)   | 1         | 2.04%   |
| 1280x1024 (SXGA)   | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 21        | 40.38%  |
| 17      | 4         | 7.69%   |
| 14      | 4         | 7.69%   |
| 13      | 4         | 7.69%   |
| 12      | 4         | 7.69%   |
| 16      | 3         | 5.77%   |
| 40      | 2         | 3.85%   |
| 27      | 2         | 3.85%   |
| 22      | 2         | 3.85%   |
| 84      | 1         | 1.92%   |
| 31      | 1         | 1.92%   |
| 21      | 1         | 1.92%   |
| 19      | 1         | 1.92%   |
| 18      | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 52.94%  |
| 201-300     | 7         | 13.73%  |
| 351-400     | 6         | 11.76%  |
| 401-500     | 4         | 7.84%   |
| 801-900     | 2         | 3.92%   |
| 501-600     | 2         | 3.92%   |
| 601-700     | 1         | 1.96%   |
| 1501-2000   | 1         | 1.96%   |
| Unknown     | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 34        | 73.91%  |
| 16/10 | 9         | 19.57%  |
| 5/4   | 1         | 2.17%   |
| 32/9  | 1         | 2.17%   |
| 3/2   | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 40.38%  |
| 81-90          | 7         | 13.46%  |
| 61-70          | 4         | 7.69%   |
| 121-130        | 4         | 7.69%   |
| 111-120        | 3         | 5.77%   |
| 301-350        | 2         | 3.85%   |
| 201-250        | 2         | 3.85%   |
| 151-200        | 2         | 3.85%   |
| 501-1000       | 2         | 3.85%   |
| More than 1000 | 1         | 1.92%   |
| 71-80          | 1         | 1.92%   |
| 351-500        | 1         | 1.92%   |
| 141-150        | 1         | 1.92%   |
| Unknown        | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 40%     |
| 101-120       | 10        | 20%     |
| 161-240       | 7         | 14%     |
| 51-100        | 7         | 14%     |
| More than 240 | 5         | 10%     |
| Unknown       | 1         | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 29        | 70.73%  |
| 2     | 11        | 26.83%  |
| 3     | 1         | 2.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 31        | 43.06%  |
| Realtek Semiconductor             | 21        | 29.17%  |
| Qualcomm Atheros                  | 4         | 5.56%   |
| Ralink Technology                 | 3         | 4.17%   |
| Broadcom Limited                  | 3         | 4.17%   |
| Huawei Technologies               | 2         | 2.78%   |
| DisplayLink                       | 2         | 2.78%   |
| Broadcom                          | 2         | 2.78%   |
| TP-Link                           | 1         | 1.39%   |
| MediaTek                          | 1         | 1.39%   |
| Ericsson Business Mobile Networks | 1         | 1.39%   |
| ASIX Electronics                  | 1         | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 21.25%  |
| Intel Wi-Fi 6 AX200                                               | 10        | 12.5%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 5%      |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 5%      |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.5%    |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.25%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.25%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.25%   |
| Intel Wireless-AC 9260                                            | 1         | 1.25%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.25%   |
| Intel Wireless 7260                                               | 1         | 1.25%   |
| Intel Wireless 3165                                               | 1         | 1.25%   |
| Intel Wireless 3160                                               | 1         | 1.25%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 1.25%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.25%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.25%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.25%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.25%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.25%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 1.25%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.25%   |
| Intel Alder Lake-U CNVi: Wireless-AC                              | 1         | 1.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.25%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.25%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.25%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                  | 1         | 1.25%   |
| Huawei ME909u-521 mPCIe LTE/GPS card                              | 1         | 1.25%   |
| Ericsson Business Mobile Networks F3507g Mobile Broadband Module  | 1         | 1.25%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 1.25%   |
| DisplayLink Plugable UD-3900H                                     | 1         | 1.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 66.67%  |
| Ralink Technology     | 3         | 7.14%   |
| Qualcomm Atheros      | 3         | 7.14%   |
| Realtek Semiconductor | 2         | 4.76%   |
| Broadcom Limited      | 2         | 4.76%   |
| Broadcom              | 2         | 4.76%   |
| TP-Link               | 1         | 2.38%   |
| MediaTek              | 1         | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 10        | 23.81%  |
| Intel Alder Lake-P PCH CNVi WiFi                              | 4         | 9.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 2         | 4.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2         | 4.76%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 4.76%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 2.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.38%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 2.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 2.38%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 2.38%   |
| Intel Wireless-AC 9260                                        | 1         | 2.38%   |
| Intel Wireless 8265 / 8275                                    | 1         | 2.38%   |
| Intel Wireless 7260                                           | 1         | 2.38%   |
| Intel Wireless 3165                                           | 1         | 2.38%   |
| Intel Wireless 3160                                           | 1         | 2.38%   |
| Intel Ultimate N WiFi Link 5300                               | 1         | 2.38%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 2.38%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                 | 1         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 1         | 2.38%   |
| Intel Centrino Advanced-N 6200                                | 1         | 2.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 2.38%   |
| Intel Alder Lake-U CNVi: Wireless-AC                          | 1         | 2.38%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 1         | 2.38%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter   | 1         | 2.38%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 1         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 60%     |
| Intel                 | 8         | 22.86%  |
| DisplayLink           | 2         | 5.71%   |
| Qualcomm Atheros      | 1         | 2.86%   |
| Broadcom Limited      | 1         | 2.86%   |
| Broadcom              | 1         | 2.86%   |
| ASIX Electronics      | 1         | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 48.57%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 11.43%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.86%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.86%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.86%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.86%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.86%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.86%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.86%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.86%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 2.86%   |
| DisplayLink Plugable UD-3900H                                     | 1         | 2.86%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.86%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 2.86%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 52.63%  |
| Ethernet | 33        | 43.42%  |
| Modem    | 3         | 3.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 75.61%  |
| Ethernet | 10        | 24.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 29        | 70.73%  |
| 1     | 10        | 24.39%  |
| 3     | 1         | 2.44%   |
| 0     | 1         | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| Yes  | 22        | 53.66%  |
| No   | 19        | 46.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 70.27%  |
| Foxconn / Hon Hai               | 3         | 8.11%   |
| Apple                           | 2         | 5.41%   |
| Realtek Semiconductor           | 1         | 2.7%    |
| Qualcomm Atheros Communications | 1         | 2.7%    |
| IMC Networks                    | 1         | 2.7%    |
| Cambridge Silicon Radio         | 1         | 2.7%    |
| Broadcom                        | 1         | 2.7%    |
| ASUSTek Computer                | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 10        | 27.03%  |
| Intel Bluetooth wireless interface                  | 5         | 13.51%  |
| Intel AX201 Bluetooth                               | 5         | 13.51%  |
| Intel Bluetooth Device                              | 4         | 10.81%  |
| Realtek Bluetooth Radio                             | 1         | 2.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.7%    |
| IMC Networks Bluetooth Radio                        | 1         | 2.7%    |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 2.7%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 2.7%    |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 2.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.7%    |
| Broadcom HP Portable SoftSailing                    | 1         | 2.7%    |
| ASUS ASUS USB-BT500                                 | 1         | 2.7%    |
| Apple Bluetooth USB Host Controller                 | 1         | 2.7%    |
| Apple Bluetooth Host Controller                     | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 29        | 50.88%  |
| Nvidia                                 | 13        | 22.81%  |
| AMD                                    | 12        | 21.05%  |
| Sony Ericsson Mobile Communications AB | 1         | 1.75%   |
| Kingston Technology                    | 1         | 1.75%   |
| GN Netcom                              | 1         | 1.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 16.67%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 7.58%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 6.06%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 6.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 6.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 4.55%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 4.55%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 4.55%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 3.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 3.03%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 3.03%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 3.03%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.03%   |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 1.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.52%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.52%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.52%   |
| Kingston Technology HyperX QuadCast S                                      | 1         | 1.52%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.52%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.52%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.52%   |
| Intel Alder Lake-U cAVS (Audio, Voice, Speech)                             | 1         | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.52%   |
| GN Netcom Jabra Link 380                                                   | 1         | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.52%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 5         | 35.71%  |
| Samsung Electronics | 5         | 35.71%  |
| Unknown             | 2         | 14.29%  |
| Elpida              | 1         | 7.14%   |
| ASint Technology    | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s    | 2         | 14.29%  |
| Unknown                                                   | 2         | 14.29%  |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 7.14%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 7.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 7.14%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s | 1         | 7.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 1         | 7.14%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s    | 1         | 7.14%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s    | 1         | 7.14%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 1         | 7.14%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s     | 1         | 7.14%   |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s        | 1         | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 7         | 58.33%  |
| DDR3   | 4         | 33.33%  |
| LPDDR5 | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 91.67%  |
| Row Of Chips | 1         | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 4         | 28.57%  |
| 16384 | 3         | 21.43%  |
| 2048  | 3         | 21.43%  |
| 32768 | 2         | 14.29%  |
| 4096  | 2         | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 5         | 41.67%  |
| 1600  | 3         | 25%     |
| 8400  | 1         | 8.33%   |
| 6400  | 1         | 8.33%   |
| 2667  | 1         | 8.33%   |
| 1067  | 1         | 8.33%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 17        | 51.52%  |
| Bison Electronics             | 3         | 9.09%   |
| Suyin                         | 2         | 6.06%   |
| Sunplus Innovation Technology | 2         | 6.06%   |
| IMC Networks                  | 2         | 6.06%   |
| Ricoh                         | 1         | 3.03%   |
| Realtek Semiconductor         | 1         | 3.03%   |
| Microdia                      | 1         | 3.03%   |
| Luxvisions Innotech Limited   | 1         | 3.03%   |
| Generalplus Technology        | 1         | 3.03%   |
| Apple                         | 1         | 3.03%   |
| Alpha Imaging Technology      | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated IR Camera                         | 5         | 15.15%  |
| Chicony HD Webcam                                    | 3         | 9.09%   |
| Chicony FHD Webcam                                   | 3         | 9.09%   |
| IMC Networks Integrated Camera                       | 2         | 6.06%   |
| Suyin RGBIR Camera                                   | 1         | 3.03%   |
| Suyin HP TrueVision HD                               | 1         | 3.03%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 3.03%   |
| Sunplus Asus Webcam                                  | 1         | 3.03%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 3.03%   |
| Realtek Integrated Webcam                            | 1         | 3.03%   |
| Microdia Integrated_Webcam_FHD                       | 1         | 3.03%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 3.03%   |
| Generalplus GENERAL WEBCAM                           | 1         | 3.03%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 3.03%   |
| Chicony USB2.0 Camera                                | 1         | 3.03%   |
| Chicony USB 2.0 Camera                               | 1         | 3.03%   |
| Chicony Integrated Camera                            | 1         | 3.03%   |
| Chicony FJ Camera                                    | 1         | 3.03%   |
| Chicony 1.3M Webcam                                  | 1         | 3.03%   |
| Bison Lenovo Integrated Webcam                       | 1         | 3.03%   |
| Bison Lenovo EasyCamera                              | 1         | 3.03%   |
| Bison HD Webcam                                      | 1         | 3.03%   |
| Apple FaceTime HD Camera                             | 1         | 3.03%   |
| Alpha Imaging Integrated_Webcam_8M                   | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 50%     |
| Synaptics             | 3         | 37.5%   |
| LighTuning Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 12.5%   |
| Validity Sensors VFS491                           | 1         | 12.5%   |
| Validity Sensors VFS Fingerprint sensor           | 1         | 12.5%   |
| Validity Sensors Fingerprint scanner              | 1         | 12.5%   |
| Synaptics UWP WBDI                                | 1         | 12.5%   |
| LighTuning Fingerprint Reader                     | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| Alcor Micro | 2         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 2         | 50%     |
| Broadcom 5880                       | 1         | 25%     |
| Broadcom 58200                      | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 22        | 53.66%  |
| 1     | 18        | 43.9%   |
| 3     | 1         | 2.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 36.36%  |
| Multimedia controller | 6         | 27.27%  |
| Chipcard              | 4         | 18.18%  |
| Graphics card         | 2         | 9.09%   |
| Net/wireless          | 1         | 4.55%   |
| Modem                 | 1         | 4.55%   |

