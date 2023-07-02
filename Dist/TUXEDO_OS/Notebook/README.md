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

Total: 61

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| TUXEDO        | Pulse 15 Gen1               | [b15b3b6025](https://linux-hardware.org/?probe=b15b3b6025) | Jun 30, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [ed4a581e3e](https://linux-hardware.org/?probe=ed4a581e3e) | Jun 28, 2023 |
| MSI           | GE75 Raider 10SF            | [c2a5aeb291](https://linux-hardware.org/?probe=c2a5aeb291) | Jun 28, 2023 |
| TUXEDO        | P64_HJ,HK1                  | [4c542d50e7](https://linux-hardware.org/?probe=4c542d50e7) | Jun 27, 2023 |
| BESSTAR Te... | X400                        | [8e98b345cf](https://linux-hardware.org/?probe=8e98b345cf) | Jun 26, 2023 |
| Acer          | Swift SFX14-51G             | [c8f3981a52](https://linux-hardware.org/?probe=c8f3981a52) | Jun 23, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [6fb60cf84a](https://linux-hardware.org/?probe=6fb60cf84a) | Jun 18, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [c47936b50c](https://linux-hardware.org/?probe=c47936b50c) | Jun 09, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [c16266c1c9](https://linux-hardware.org/?probe=c16266c1c9) | Jun 04, 2023 |
| Apple         | MacBookAir7,2               | [f75fb35204](https://linux-hardware.org/?probe=f75fb35204) | May 28, 2023 |
| ASUSTek       | K55VJ                       | [66c9773a5f](https://linux-hardware.org/?probe=66c9773a5f) | May 26, 2023 |
| ASUSTek       | K55VJ                       | [65cc5e45b0](https://linux-hardware.org/?probe=65cc5e45b0) | May 26, 2023 |
| Lenovo        | G580 20150                  | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| Lenovo        | IdeaPad N581 7505           | [5d340c1aa2](https://linux-hardware.org/?probe=5d340c1aa2) | May 04, 2023 |
| HP            | Pavilion dv6                | [be01072653](https://linux-hardware.org/?probe=be01072653) | May 03, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | [756500f10b](https://linux-hardware.org/?probe=756500f10b) | May 03, 2023 |
| HP            | Pavilion dv6                | [87f0c054fa](https://linux-hardware.org/?probe=87f0c054fa) | May 03, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| Dell          | Inspiron 16 5630            | [7bfe5bb892](https://linux-hardware.org/?probe=7bfe5bb892) | Apr 27, 2023 |
| Dell          | Latitude 7530               | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [fd2ad16b59](https://linux-hardware.org/?probe=fd2ad16b59) | Apr 22, 2023 |
| Dell          | Vostro 3550                 | [3b77631ed6](https://linux-hardware.org/?probe=3b77631ed6) | Apr 04, 2023 |
| Unknown       | Unknown                     | [22c0e4cdec](https://linux-hardware.org/?probe=22c0e4cdec) | Apr 02, 2023 |
| Lenovo        | ThinkPad T490 20N3SBU219    | [b8e8125150](https://linux-hardware.org/?probe=b8e8125150) | Mar 27, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [885b757cdc](https://linux-hardware.org/?probe=885b757cdc) | Mar 24, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [5e01f2c134](https://linux-hardware.org/?probe=5e01f2c134) | Mar 22, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [0db668b5ec](https://linux-hardware.org/?probe=0db668b5ec) | Mar 18, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [094b530ce7](https://linux-hardware.org/?probe=094b530ce7) | Mar 18, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [3fcbfecb5a](https://linux-hardware.org/?probe=3fcbfecb5a) | Mar 14, 2023 |
| Dell          | Precision 7720              | [dbe0d4c5c4](https://linux-hardware.org/?probe=dbe0d4c5c4) | Mar 12, 2023 |
| Dell          | Vostro 3550                 | [40a0328a5f](https://linux-hardware.org/?probe=40a0328a5f) | Mar 11, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [3cde6f345c](https://linux-hardware.org/?probe=3cde6f345c) | Mar 10, 2023 |
| Fujitsu       | LIFEBOOK U7412              | [980dd72471](https://linux-hardware.org/?probe=980dd72471) | Mar 06, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [7a21cf8349](https://linux-hardware.org/?probe=7a21cf8349) | Mar 05, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [20d14c7576](https://linux-hardware.org/?probe=20d14c7576) | Mar 04, 2023 |
| Lenovo        | G50-80 80E5                 | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| Dell          | Vostro 3550                 | [1e1da6a575](https://linux-hardware.org/?probe=1e1da6a575) | Feb 24, 2023 |
| Dell          | Vostro 3550                 | [497a8d66e5](https://linux-hardware.org/?probe=497a8d66e5) | Feb 22, 2023 |
| Dell          | Precision 7720              | [2f7837d5b6](https://linux-hardware.org/?probe=2f7837d5b6) | Feb 21, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| HP            | EliteBook 2570p             | [ed14b057dd](https://linux-hardware.org/?probe=ed14b057dd) | Feb 09, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [4a2fcb6bd0](https://linux-hardware.org/?probe=4a2fcb6bd0) | Jan 31, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [e163d98802](https://linux-hardware.org/?probe=e163d98802) | Jan 28, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [fa53a29f7e](https://linux-hardware.org/?probe=fa53a29f7e) | Jan 01, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [731b31c845](https://linux-hardware.org/?probe=731b31c845) | Dec 02, 2022 |
| TUXEDO        | N13xWU                      | [55935f091d](https://linux-hardware.org/?probe=55935f091d) | Dec 01, 2022 |
| TUXEDO        | Unknown                     | [fd06ca029c](https://linux-hardware.org/?probe=fd06ca029c) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [5043f6c54e](https://linux-hardware.org/?probe=5043f6c54e) | Nov 20, 2022 |
| HP            | EliteBook 820 G2            | [5d82e9f6ac](https://linux-hardware.org/?probe=5d82e9f6ac) | Nov 19, 2022 |
| HP            | EliteBook 820 G2            | [9d20af2c30](https://linux-hardware.org/?probe=9d20af2c30) | Nov 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | [d58eb8b2f0](https://linux-hardware.org/?probe=d58eb8b2f0) | Oct 30, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | [032bc01698](https://linux-hardware.org/?probe=032bc01698) | Oct 30, 2022 |
| TUXEDO        | Unknown                     | [99555fc4eb](https://linux-hardware.org/?probe=99555fc4eb) | Oct 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| ASUSTek       | BU201LAV                    | [9d1fe7cb6f](https://linux-hardware.org/?probe=9d1fe7cb6f) | Oct 19, 2022 |
| Apple         | MacBookPro8,1               | [36e033aa01](https://linux-hardware.org/?probe=36e033aa01) | Oct 09, 2022 |
| Notebook      | W65_W67RB                   | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| Acer          | TravelMate 8572T            | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| TUXEDO OS 22.04 | 48        | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 48        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 6.1.0-1009-tuxedo   | 12        | 23.53%  |
| 6.2.0-10005-tuxedo  | 9         | 17.65%  |
| 6.2.0-10007-tuxedo  | 7         | 13.73%  |
| 6.2.0-10010-tuxedo  | 4         | 7.84%   |
| 5.15.0-10058-tuxedo | 4         | 7.84%   |
| 5.15.0-10048-tuxedo | 4         | 7.84%   |
| 5.15.0-10053-tuxedo | 3         | 5.88%   |
| 5.15.0-10052-tuxedo | 3         | 5.88%   |
| 5.15.0-10050-tuxedo | 2         | 3.92%   |
| 6.0.0-1010-oem      | 1         | 1.96%   |
| 5.15.0-10057-tuxedo | 1         | 1.96%   |
| 5.15.0-10056-tuxedo | 1         | 1.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 20        | 39.22%  |
| 5.15.0  | 18        | 35.29%  |
| 6.1.0   | 12        | 23.53%  |
| 6.0.0   | 1         | 1.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 20        | 39.22%  |
| 5.15    | 18        | 35.29%  |
| 6.1     | 12        | 23.53%  |
| 6.0     | 1         | 1.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 48        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| KDE5 | 48        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 48        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 39        | 79.59%  |
| SDDM    | 10        | 20.41%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| de_DE | 26        | 54.17%  |
| en_US | 12        | 25%     |
| en_GB | 3         | 6.25%   |
| fr_FR | 2         | 4.17%   |
| pt_PT | 1         | 2.08%   |
| pl_PL | 1         | 2.08%   |
| es_ES | 1         | 2.08%   |
| en_DK | 1         | 2.08%   |
| en_AU | 1         | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 39        | 81.25%  |
| EFI  | 9         | 18.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 42        | 87.5%   |
| Btrfs | 5         | 10.42%  |
| Tmpfs | 1         | 2.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 39        | 79.59%  |
| GPT     | 9         | 18.37%  |
| MBR     | 1         | 2.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 95.92%  |
| Yes       | 2         | 4.08%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 93.88%  |
| Yes       | 3         | 6.12%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| TUXEDO           | 19        | 39.58%  |
| Lenovo           | 7         | 14.58%  |
| Dell             | 5         | 10.42%  |
| Hewlett-Packard  | 4         | 8.33%   |
| ASUSTek Computer | 4         | 8.33%   |
| Apple            | 2         | 4.17%   |
| Acer             | 2         | 4.17%   |
| Notebook         | 1         | 2.08%   |
| MSI              | 1         | 2.08%   |
| Fujitsu          | 1         | 2.08%   |
| BESSTAR Tech     | 1         | 2.08%   |
| Unknown          | 1         | 2.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 3         | 6.25%   |
| TUXEDO Stellaris/Polaris AMD Gen4   | 2         | 4.17%   |
| TUXEDO Pulse 15 Gen2                | 2         | 4.17%   |
| TUXEDO Pulse 15 Gen1                | 2         | 4.17%   |
| TUXEDO InfinityBook S 15/17 Gen7    | 2         | 4.17%   |
| TUXEDO InfinityBook Pro 14 Gen6     | 2         | 4.17%   |
| TUXEDO XMG FUSION 15 (XFU15L19)     | 1         | 2.08%   |
| TUXEDO Polaris AMD Gen3 (CZN)       | 1         | 2.08%   |
| TUXEDO Polaris 15 AMD Gen1          | 1         | 2.08%   |
| TUXEDO P64_HJ,HK1                   | 1         | 2.08%   |
| TUXEDO N13xWU                       | 1         | 2.08%   |
| TUXEDO InfinityBook Pro Gen7 (MK2)  | 1         | 2.08%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 1         | 2.08%   |
| Notebook W65_W67RB                  | 1         | 2.08%   |
| MSI GE75 Raider 10SF                | 1         | 2.08%   |
| Lenovo Yoga S740-15IRH 81NX         | 1         | 2.08%   |
| Lenovo ThinkPad X200 Tablet 7450WN9 | 1         | 2.08%   |
| Lenovo ThinkPad T490 20N3SBU219     | 1         | 2.08%   |
| Lenovo ThinkPad P1 Gen 3 20TJS1W700 | 1         | 2.08%   |
| Lenovo Legion 5 15ACH6H 82JU        | 1         | 2.08%   |
| Lenovo IdeaPad N581 7505            | 1         | 2.08%   |
| Lenovo G50-80 80E5                  | 1         | 2.08%   |
| HP Pavilion dv6                     | 1         | 2.08%   |
| HP OMEN Laptop 15-en0xxx            | 1         | 2.08%   |
| HP EliteBook 820 G2                 | 1         | 2.08%   |
| HP EliteBook 2570p                  | 1         | 2.08%   |
| Fujitsu LIFEBOOK U7412              | 1         | 2.08%   |
| Dell Vostro 3550                    | 1         | 2.08%   |
| Dell Venue 11 Pro 7130 vPro         | 1         | 2.08%   |
| Dell Precision 7720                 | 1         | 2.08%   |
| Dell Latitude 7530                  | 1         | 2.08%   |
| Dell Inspiron 16 5630               | 1         | 2.08%   |
| BESSTAR Tech X400                   | 1         | 2.08%   |
| ASUS Zephyrus G GU502DU_GA502DU     | 1         | 2.08%   |
| ASUS ROG Strix G713RW_G713RW        | 1         | 2.08%   |
| ASUS K55VJ                          | 1         | 2.08%   |
| ASUS BU201LAV                       | 1         | 2.08%   |
| Apple MacBookPro8,1                 | 1         | 2.08%   |
| Apple MacBookAir7,2                 | 1         | 2.08%   |
| Acer TravelMate 8572T               | 1         | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| TUXEDO InfinityBook | 6         | 12.5%   |
| TUXEDO Pulse        | 4         | 8.33%   |
| Lenovo ThinkPad     | 3         | 6.25%   |
| Unknown             | 3         | 6.25%   |
| TUXEDO Stellaris    | 2         | 4.17%   |
| TUXEDO Polaris      | 2         | 4.17%   |
| HP EliteBook        | 2         | 4.17%   |
| TUXEDO XMG          | 1         | 2.08%   |
| TUXEDO P64          | 1         | 2.08%   |
| TUXEDO N13xWU       | 1         | 2.08%   |
| Notebook W65        | 1         | 2.08%   |
| MSI GE75            | 1         | 2.08%   |
| Lenovo Yoga         | 1         | 2.08%   |
| Lenovo Legion       | 1         | 2.08%   |
| Lenovo IdeaPad      | 1         | 2.08%   |
| Lenovo G50-80       | 1         | 2.08%   |
| HP Pavilion         | 1         | 2.08%   |
| HP OMEN             | 1         | 2.08%   |
| Fujitsu LIFEBOOK    | 1         | 2.08%   |
| Dell Vostro         | 1         | 2.08%   |
| Dell Venue          | 1         | 2.08%   |
| Dell Precision      | 1         | 2.08%   |
| Dell Latitude       | 1         | 2.08%   |
| Dell Inspiron       | 1         | 2.08%   |
| BESSTAR Tech X400   | 1         | 2.08%   |
| ASUS Zephyrus       | 1         | 2.08%   |
| ASUS ROG            | 1         | 2.08%   |
| ASUS K55VJ          | 1         | 2.08%   |
| ASUS BU201LAV       | 1         | 2.08%   |
| Apple MacBookPro8   | 1         | 2.08%   |
| Apple MacBookAir7   | 1         | 2.08%   |
| Acer TravelMate     | 1         | 2.08%   |
| Acer Swift          | 1         | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 11        | 22.92%  |
| 2021 | 6         | 12.5%   |
| 2020 | 6         | 12.5%   |
| 2019 | 5         | 10.42%  |
| 2015 | 5         | 10.42%  |
| 2017 | 3         | 6.25%   |
| 2012 | 3         | 6.25%   |
| 2023 | 2         | 4.17%   |
| 2014 | 2         | 4.17%   |
| 2011 | 2         | 4.17%   |
| 2010 | 1         | 2.08%   |
| 2009 | 1         | 2.08%   |
| 2008 | 1         | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 48        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 48        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 12        | 25%     |
| 8.01-16.0   | 12        | 25%     |
| 16.01-24.0  | 8         | 16.67%  |
| 4.01-8.0    | 6         | 12.5%   |
| 3.01-4.0    | 4         | 8.33%   |
| 64.01-256.0 | 4         | 8.33%   |
| 24.01-32.0  | 2         | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 18        | 36.73%  |
| 2.01-3.0   | 11        | 22.45%  |
| 1.01-2.0   | 9         | 18.37%  |
| 3.01-4.0   | 7         | 14.29%  |
| 16.01-24.0 | 2         | 4.08%   |
| 8.01-16.0  | 2         | 4.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 55.1%   |
| 2      | 20        | 40.82%  |
| 3      | 2         | 4.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 81.25%  |
| Yes       | 9         | 18.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 81.25%  |
| No        | 9         | 18.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 97.92%  |
| No        | 1         | 2.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 89.58%  |
| No        | 5         | 10.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 26        | 54.17%  |
| USA         | 7         | 14.58%  |
| UK          | 2         | 4.17%   |
| Switzerland | 2         | 4.17%   |
| Portugal    | 2         | 4.17%   |
| France      | 2         | 4.17%   |
| Turkey      | 1         | 2.08%   |
| Spain       | 1         | 2.08%   |
| Poland      | 1         | 2.08%   |
| Denmark     | 1         | 2.08%   |
| Czechia     | 1         | 2.08%   |
| Austria     | 1         | 2.08%   |
| Australia   | 1         | 2.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Schweinfurt        | 2         | 4.17%   |
| Munich             | 2         | 4.17%   |
| Zurich             | 1         | 2.08%   |
| Zabrze             | 1         | 2.08%   |
| Watertown          | 1         | 2.08%   |
| Walsall            | 1         | 2.08%   |
| Vienna             | 1         | 2.08%   |
| Stuttgart          | 1         | 2.08%   |
| Stockstadt am Main | 1         | 2.08%   |
| Seattle            | 1         | 2.08%   |
| Rio Maior          | 1         | 2.08%   |
| Reno               | 1         | 2.08%   |
| Rennes             | 1         | 2.08%   |
| Redcar             | 1         | 2.08%   |
| Prague             | 1         | 2.08%   |
| Perrysburg         | 1         | 2.08%   |
| Paris              | 1         | 2.08%   |
| Nuremberg          | 1         | 2.08%   |
| Neuwied            | 1         | 2.08%   |
| Mannheim           | 1         | 2.08%   |
| Lucerne            | 1         | 2.08%   |
| Lippstadt          | 1         | 2.08%   |
| Leipzig            | 1         | 2.08%   |
| Langenhagen        | 1         | 2.08%   |
| Laage              | 1         | 2.08%   |
| Jessen             | 1         | 2.08%   |
| Istanbul           | 1         | 2.08%   |
| Husum              | 1         | 2.08%   |
| Herzberg           | 1         | 2.08%   |
| Heilbronn          | 1         | 2.08%   |
| Hamburg            | 1         | 2.08%   |
| Gainesville        | 1         | 2.08%   |
| Friedrichstadt     | 1         | 2.08%   |
| Ethridge           | 1         | 2.08%   |
| Ehringshausen      | 1         | 2.08%   |
| Düren             | 1         | 2.08%   |
| Coswig             | 1         | 2.08%   |
| Chemnitz           | 1         | 2.08%   |
| Bronshoj           | 1         | 2.08%   |
| Brisbane           | 1         | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 25        | 30     | 38.46%  |
| Seagate                     | 6         | 6      | 9.23%   |
| Sandisk                     | 6         | 7      | 9.23%   |
| Hitachi                     | 4         | 6      | 6.15%   |
| WDC                         | 2         | 2      | 3.08%   |
| Toshiba                     | 2         | 2      | 3.08%   |
| SPCC                        | 2         | 2      | 3.08%   |
| SK hynix                    | 2         | 3      | 3.08%   |
| Phison Electronics          | 2         | 2      | 3.08%   |
| Micron Technology           | 2         | 2      | 3.08%   |
| USB3.0                      | 1         | 1      | 1.54%   |
| Unknown                     | 1         | 1      | 1.54%   |
| OWC                         | 1         | 1      | 1.54%   |
| LITEONIT                    | 1         | 1      | 1.54%   |
| Kingston Technology Company | 1         | 1      | 1.54%   |
| Kingston                    | 1         | 1      | 1.54%   |
| Kingchuxing                 | 1         | 1      | 1.54%   |
| Intenso                     | 1         | 1      | 1.54%   |
| Intel                       | 1         | 1      | 1.54%   |
| CT1000BX                    | 1         | 1      | 1.54%   |
| Crucial                     | 1         | 1      | 1.54%   |
| Apple                       | 1         | 1      | 1.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 6         | 8.96%   |
| Samsung SSD 980 1TB                                 | 4         | 5.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 4         | 5.97%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 2         | 2.99%   |
| Samsung SSD 980 PRO 500GB                           | 2         | 2.99%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 2.99%   |
| Samsung SSD 980 500GB                               | 2         | 2.99%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2         | 2.99%   |
| Hitachi HTS727550A9E364 500GB                       | 2         | 2.99%   |
| WDC WD3200BPVT-24JJ5T0 320GB                        | 1         | 1.49%   |
| WDC WD Elements SE SSD 1TB                          | 1         | 1.49%   |
| USB3.0 Super Speed 1TB                              | 1         | 1.49%   |
| Unknown MMC Card  2GB                               | 1         | 1.49%   |
| Toshiba XG4 NVMe SSD Controller 256GB               | 1         | 1.49%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1.49%   |
| SPCC M.2 SSD 256GB                                  | 1         | 1.49%   |
| SPCC M.2 PCIe SSD 1TB                               | 1         | 1.49%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB             | 1         | 1.49%   |
| SK hynix SC311 SATA 256GB SSD                       | 1         | 1.49%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1.49%   |
| Seagate ST500LM034-2GH17A 500GB                     | 1         | 1.49%   |
| Seagate ST2000LM015-2E8174 2TB                      | 1         | 1.49%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 1.49%   |
| Seagate Expansion 1TB                               | 1         | 1.49%   |
| Seagate BarraCuda Q5 ZP500CV30001 500GB             | 1         | 1.49%   |
| Sandisk WD PC SN735 SDBPNHH-1T00-1002 1024GB        | 1         | 1.49%   |
| Sandisk WD Black SN850 1TB                          | 1         | 1.49%   |
| Sandisk Ultra 3D NVMe 1TB                           | 1         | 1.49%   |
| SanDisk SDSSDA240G 240GB                            | 1         | 1.49%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD                 | 1         | 1.49%   |
| Samsung SSD 860 PRO 512GB                           | 1         | 1.49%   |
| Samsung SSD 860 EVO M.2 250GB                       | 1         | 1.49%   |
| Samsung SSD 850 EVO 500GB                           | 1         | 1.49%   |
| Samsung MZALQ256HBJD-00BL1 256GB                    | 1         | 1.49%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 1         | 1.49%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 1         | 1.49%   |
| OWC Mercury Electra 3G SSD                          | 1         | 1.49%   |
| Micron MTFDKBA256TFK-1BC15ABFA 256GB                | 1         | 1.49%   |
| Micron MTFDDAK128MBF-1AN1ZABHA 128GB SSD            | 1         | 1.49%   |
| LITEONIT LJT-128L6G-11 M.2 2260 128GB SSD           | 1         | 1.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 41.67%  |
| Hitachi | 4         | 6      | 33.33%  |
| WDC     | 1         | 1      | 8.33%   |
| USB3.0  | 1         | 1      | 8.33%   |
| Toshiba | 1         | 1      | 8.33%   |

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
| NVMe    | 31        | 42     | 52.54%  |
| SSD     | 14        | 16     | 23.73%  |
| HDD     | 12        | 14     | 20.34%  |
| MMC     | 1         | 1      | 1.69%   |
| Unknown | 1         | 1      | 1.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 31        | 42     | 53.45%  |
| SATA | 22        | 27     | 37.93%  |
| SAS  | 4         | 4      | 6.9%    |
| MMC  | 1         | 1      | 1.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 19     | 56%     |
| 0.51-1.0   | 10        | 10     | 40%     |
| 1.01-2.0   | 1         | 1      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 15        | 31.25%  |
| 251-500        | 11        | 22.92%  |
| 101-250        | 9         | 18.75%  |
| 1001-2000      | 4         | 8.33%   |
| 2001-3000      | 3         | 6.25%   |
| Unknown        | 2         | 4.17%   |
| More than 3000 | 1         | 2.08%   |
| 21-50          | 1         | 2.08%   |
| 1-20           | 1         | 2.08%   |
| 51-100         | 1         | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 15        | 30%     |
| 1-20      | 14        | 28%     |
| 101-250   | 9         | 18%     |
| 51-100    | 4         | 8%      |
| 251-500   | 3         | 6%      |
| 501-1000  | 2         | 4%      |
| Unknown   | 2         | 4%      |
| 1001-2000 | 1         | 2%      |

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
| Detected | 39        | 61     | 79.59%  |
| Works    | 10        | 13     | 20.41%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 24        | 36.92%  |
| Samsung Electronics          | 23        | 35.38%  |
| AMD                          | 5         | 7.69%   |
| SanDisk                      | 4         | 6.15%   |
| Phison Electronics           | 2         | 3.08%   |
| Kingston Technology Company  | 2         | 3.08%   |
| Toshiba America Info Systems | 1         | 1.54%   |
| SK hynix                     | 1         | 1.54%   |
| Silicon Motion               | 1         | 1.54%   |
| Seagate Technology           | 1         | 1.54%   |
| Micron Technology            | 1         | 1.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 10        | 15.15%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 6         | 9.09%   |
| Samsung NVMe SSD Controller 980                                              | 6         | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 5         | 7.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 6.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 3         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 4.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 2         | 3.03%   |
| Kingston Company Company Non-Volatile memory controller                      | 2         | 3.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 3.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 3.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 3.03%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                         | 1         | 1.52%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 1.52%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 1.52%   |
| Seagate Non-Volatile memory controller                                       | 1         | 1.52%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                   | 1         | 1.52%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                           | 1         | 1.52%   |
| SanDisk Non-Volatile memory controller                                       | 1         | 1.52%   |
| Samsung Electronics SATA controller                                          | 1         | 1.52%   |
| Phison PS5013 E13 NVMe Controller                                            | 1         | 1.52%   |
| Phison E16 PCIe4 NVMe Controller                                             | 1         | 1.52%   |
| Micron 2450 NVMe SSD (DRAM-less)                                             | 1         | 1.52%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation        | 1         | 1.52%   |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 1.52%   |
| Intel SSD 660P Series                                                        | 1         | 1.52%   |
| Intel SATA Controller [RAID mode]                                            | 1         | 1.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 1.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 1         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 1.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 1         | 1.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 31        | 51.67%  |
| SATA | 25        | 41.67%  |
| RAID | 4         | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 35        | 72.92%  |
| AMD    | 13        | 27.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 4.17%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 4.17%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 4.17%   |
| Intel 12th Gen Core i5-1240P                  | 2         | 4.17%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 2         | 4.17%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 2         | 4.17%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 4.17%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 4.17%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 4.17%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 2.08%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 2.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.08%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 2.08%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.08%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 2.08%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 2.08%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 2.08%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 2.08%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 2.08%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2.08%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 2.08%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 2.08%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 2.08%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 2.08%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 2.08%   |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1         | 2.08%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 2.08%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 2.08%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz          | 1         | 2.08%   |
| Intel Celeron CPU 1037U @ 1.80GHz             | 1         | 2.08%   |
| Intel 13th Gen Core i7-1360P                  | 1         | 2.08%   |
| Intel 12th Gen Core i7-1260P                  | 1         | 2.08%   |
| Intel 12th Gen Core i7-1255U                  | 1         | 2.08%   |
| Intel 12th Gen Core i3-1215U                  | 1         | 2.08%   |
| AMD Ryzen 9 6900HX with Radeon Graphics       | 1         | 2.08%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 2.08%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 2.08%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics    | 1         | 2.08%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 14        | 29.17%  |
| Other            | 10        | 20.83%  |
| AMD Ryzen 7      | 8         | 16.67%  |
| Intel Core i5    | 7         | 14.58%  |
| AMD Ryzen 5      | 3         | 6.25%   |
| Intel Xeon       | 1         | 2.08%   |
| Intel Pentium    | 1         | 2.08%   |
| Intel Core 2 Duo | 1         | 2.08%   |
| Intel Celeron    | 1         | 2.08%   |
| AMD Ryzen 9      | 1         | 2.08%   |
| AMD Ryzen 5 PRO  | 1         | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 13        | 27.08%  |
| 2      | 11        | 22.92%  |
| 6      | 9         | 18.75%  |
| 8      | 8         | 16.67%  |
| 12     | 4         | 8.33%   |
| 14     | 2         | 4.17%   |
| 10     | 1         | 2.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 45        | 93.75%  |
| 1      | 3         | 6.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 48        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 43        | 87.76%  |
| 0x906ea | 1         | 2.04%   |
| 0x906e9 | 1         | 2.04%   |
| 0x906a4 | 1         | 2.04%   |
| 0x906a3 | 1         | 2.04%   |
| 0x806c1 | 1         | 2.04%   |
| 0x306d4 | 1         | 2.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 10        | 20.83%  |
| KabyLake         | 8         | 16.67%  |
| Zen 2            | 5         | 10.42%  |
| IvyBridge        | 4         | 8.33%   |
| SandyBridge      | 3         | 6.25%   |
| Broadwell        | 3         | 6.25%   |
| Alderlake Hybrid | 3         | 6.25%   |
| Zen 3            | 2         | 4.17%   |
| TigerLake        | 2         | 4.17%   |
| Haswell          | 2         | 4.17%   |
| CometLake        | 2         | 4.17%   |
| Zen+             | 1         | 2.08%   |
| Westmere         | 1         | 2.08%   |
| Skylake          | 1         | 2.08%   |
| Penryn           | 1         | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 49.28%  |
| Nvidia | 19        | 27.54%  |
| AMD    | 16        | 23.19%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P Integrated Graphics Controller                             | 5         | 7.25%   |
| AMD Renoir                                                                    | 5         | 7.25%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 4         | 5.8%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 4         | 5.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 4         | 5.8%    |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 5.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 4.35%   |
| AMD Rembrandt [Radeon 680M]                                                   | 3         | 4.35%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                 | 2         | 2.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 2.9%    |
| Intel HD Graphics 630                                                         | 2         | 2.9%    |
| Intel HD Graphics 5500                                                        | 2         | 2.9%    |
| AMD Lucienne                                                                  | 2         | 2.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 2.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.45%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 1.45%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 1.45%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 1.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.45%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 1.45%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.45%   |
| Nvidia GF108M [GeForce GT 635M]                                               | 1         | 1.45%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 1.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.45%   |
| Intel UHD Graphics 620                                                        | 1         | 1.45%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 1         | 1.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.45%   |
| Intel HD Graphics 6000                                                        | 1         | 1.45%   |
| Intel HD Graphics 530                                                         | 1         | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                | 1         | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 1.45%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 1         | 1.45%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                       | 1         | 1.45%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                 | 1         | 1.45%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 1.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.45%   |
| AMD Baffin [Radeon Pro WX 4130/4150]                                          | 1         | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 42.86%  |
| Intel + Nvidia | 10        | 20.41%  |
| AMD + Nvidia   | 8         | 16.33%  |
| 1 x AMD        | 6         | 12.24%  |
| Intel + AMD    | 3         | 6.12%   |
| 1 x Nvidia     | 1         | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 31        | 64.58%  |
| Proprietary | 17        | 35.42%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 67.35%  |
| 5.01-6.0   | 8         | 16.33%  |
| 7.01-8.0   | 3         | 6.12%   |
| 3.01-4.0   | 3         | 6.12%   |
| 1.01-2.0   | 2         | 4.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 16        | 26.23%  |
| AU Optronics        | 10        | 16.39%  |
| Samsung Electronics | 6         | 9.84%   |
| LG Display          | 5         | 8.2%    |
| CSO                 | 3         | 4.92%   |
| Chimei Innolux      | 3         | 4.92%   |
| Dell                | 2         | 3.28%   |
| Apple               | 2         | 3.28%   |
| AOC                 | 2         | 3.28%   |
| Acer                | 2         | 3.28%   |
| Yamaha              | 1         | 1.64%   |
| Sharp               | 1         | 1.64%   |
| SGT                 | 1         | 1.64%   |
| RTK                 | 1         | 1.64%   |
| PANDA               | 1         | 1.64%   |
| Lenovo              | 1         | 1.64%   |
| Iiyama              | 1         | 1.64%   |
| Goldstar            | 1         | 1.64%   |
| BenQ                | 1         | 1.64%   |
| ASUSTek Computer    | 1         | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 3         | 4.76%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 3         | 4.76%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 2         | 3.17%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                   | 2         | 3.17%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 3.17%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 1.59%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 1.59%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 1.59%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 376x301mm 19.0-inch       | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch   | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch   | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch   | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 1.59%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 1.59%   |
| RTK Wimaxit FHD RTK5A5B 1920x1080 344x195mm 15.6-inch                   | 1         | 1.59%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 1.59%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch            | 1         | 1.59%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 1         | 1.59%   |
| LG Display LCD Monitor LGD0545 3200x1800 293x165mm 13.2-inch            | 1         | 1.59%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch            | 1         | 1.59%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 1.59%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                 | 1         | 1.59%   |
| Iiyama PL3466WQ IVM7627 3440x1440 795x334mm 33.9-inch                   | 1         | 1.59%   |
| Goldstar W2261 GSM56CF 1920x1080 477x268mm 21.5-inch                    | 1         | 1.59%   |
| Dell U2715H DELD066 2560x1440 597x336mm 27.0-inch                       | 1         | 1.59%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch        | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 355x199mm 16.0-inch        | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch         | 1         | 1.59%   |
| BOE LCD Monitor BOE0A94 1920x1080 309x174mm 14.0-inch                   | 1         | 1.59%   |
| BOE LCD Monitor BOE0A67 2560x1440 344x194mm 15.5-inch                   | 1         | 1.59%   |
| BOE LCD Monitor BOE0A59 1920x1200 345x215mm 16.0-inch                   | 1         | 1.59%   |
| BOE LCD Monitor BOE0A3B 2560x1600 344x215mm 16.0-inch                   | 1         | 1.59%   |
| BOE LCD Monitor BOE0A00 1920x1080 382x215mm 17.3-inch                   | 1         | 1.59%   |
| BOE LCD Monitor BOE0977 2560x1440 381x214mm 17.2-inch                   | 1         | 1.59%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                   | 1         | 1.59%   |
| BOE LCD Monitor BOE0847 1920x1080 344x194mm 15.5-inch                   | 1         | 1.59%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                   | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 25        | 43.1%   |
| 1366x768 (WXGA)    | 8         | 13.79%  |
| 2560x1440 (QHD)    | 7         | 12.07%  |
| 3840x2160 (4K)     | 4         | 6.9%    |
| 2880x1800          | 3         | 5.17%   |
| 1280x800 (WXGA)    | 2         | 3.45%   |
| 3440x1440          | 1         | 1.72%   |
| 3200x1800 (QHD+)   | 1         | 1.72%   |
| 2560x1600          | 1         | 1.72%   |
| 2240x1400          | 1         | 1.72%   |
| 1920x540           | 1         | 1.72%   |
| 1920x1200 (WUXGA)  | 1         | 1.72%   |
| 1680x1050 (WSXGA+) | 1         | 1.72%   |
| 1440x900 (WXGA+)   | 1         | 1.72%   |
| 1280x1024 (SXGA)   | 1         | 1.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 24        | 38.71%  |
| 13      | 6         | 9.68%   |
| 17      | 5         | 8.06%   |
| 14      | 4         | 6.45%   |
| 12      | 4         | 6.45%   |
| 27      | 3         | 4.84%   |
| 16      | 3         | 4.84%   |
| 40      | 2         | 3.23%   |
| 22      | 2         | 3.23%   |
| 84      | 1         | 1.61%   |
| 43      | 1         | 1.61%   |
| 33      | 1         | 1.61%   |
| 31      | 1         | 1.61%   |
| 24      | 1         | 1.61%   |
| 21      | 1         | 1.61%   |
| 19      | 1         | 1.61%   |
| 18      | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 50.82%  |
| 201-300     | 8         | 13.11%  |
| 351-400     | 7         | 11.48%  |
| 501-600     | 4         | 6.56%   |
| 401-500     | 4         | 6.56%   |
| 801-900     | 2         | 3.28%   |
| 701-800     | 1         | 1.64%   |
| 601-700     | 1         | 1.64%   |
| 1501-2000   | 1         | 1.64%   |
| 901-1000    | 1         | 1.64%   |
| Unknown     | 1         | 1.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 40        | 74.07%  |
| 16/10 | 10        | 18.52%  |
| 5/4   | 1         | 1.85%   |
| 32/9  | 1         | 1.85%   |
| 3/2   | 1         | 1.85%   |
| 21/9  | 1         | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 38.71%  |
| 81-90          | 9         | 14.52%  |
| 121-130        | 5         | 8.06%   |
| 61-70          | 4         | 6.45%   |
| 301-350        | 3         | 4.84%   |
| 201-250        | 3         | 4.84%   |
| 111-120        | 3         | 4.84%   |
| 501-1000       | 3         | 4.84%   |
| 351-500        | 2         | 3.23%   |
| 151-200        | 2         | 3.23%   |
| More than 1000 | 1         | 1.61%   |
| 71-80          | 1         | 1.61%   |
| 141-150        | 1         | 1.61%   |
| Unknown        | 1         | 1.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 25        | 41.67%  |
| 101-120       | 13        | 21.67%  |
| 161-240       | 8         | 13.33%  |
| 51-100        | 8         | 13.33%  |
| More than 240 | 5         | 8.33%   |
| Unknown       | 1         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 33        | 68.75%  |
| 2     | 14        | 29.17%  |
| 3     | 1         | 2.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 38        | 44.19%  |
| Realtek Semiconductor             | 26        | 30.23%  |
| Qualcomm Atheros                  | 5         | 5.81%   |
| Ralink Technology                 | 3         | 3.49%   |
| Huawei Technologies               | 3         | 3.49%   |
| Broadcom Limited                  | 3         | 3.49%   |
| DisplayLink                       | 2         | 2.33%   |
| Broadcom                          | 2         | 2.33%   |
| TP-Link                           | 1         | 1.16%   |
| MediaTek                          | 1         | 1.16%   |
| Ericsson Business Mobile Networks | 1         | 1.16%   |
| ASIX Electronics                  | 1         | 1.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 22.34%  |
| Intel Wi-Fi 6 AX200                                               | 13        | 13.83%  |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 5.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 4.26%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.13%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.13%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.13%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 2.13%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                  | 2         | 2.13%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.06%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.06%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.06%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.06%   |
| Intel Wireless-AC 9260                                            | 1         | 1.06%   |
| Intel Wireless 7260                                               | 1         | 1.06%   |
| Intel Wireless 3165                                               | 1         | 1.06%   |
| Intel Wireless 3160                                               | 1         | 1.06%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 1.06%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.06%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.06%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.06%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.06%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 1.06%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.06%   |
| Intel Alder Lake-U CNVi: Wireless-AC                              | 1         | 1.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.06%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.06%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.06%   |
| Huawei ME909u-521 mPCIe LTE/GPS card                              | 1         | 1.06%   |
| Ericsson Business Mobile Networks F3507g Mobile Broadband Module  | 1         | 1.06%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 71.43%  |
| Ralink Technology     | 3         | 6.12%   |
| Qualcomm Atheros      | 3         | 6.12%   |
| Realtek Semiconductor | 2         | 4.08%   |
| Broadcom Limited      | 2         | 4.08%   |
| Broadcom              | 2         | 4.08%   |
| TP-Link               | 1         | 2.04%   |
| MediaTek              | 1         | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 13        | 26.53%  |
| Intel Alder Lake-P PCH CNVi WiFi                              | 5         | 10.2%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 2         | 4.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2         | 4.08%   |
| Intel Wireless 8265 / 8275                                    | 2         | 4.08%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 4.08%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 4.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.04%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 2.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 2.04%   |
| Intel Wireless-AC 9260                                        | 1         | 2.04%   |
| Intel Wireless 7260                                           | 1         | 2.04%   |
| Intel Wireless 3165                                           | 1         | 2.04%   |
| Intel Wireless 3160                                           | 1         | 2.04%   |
| Intel Ultimate N WiFi Link 5300                               | 1         | 2.04%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                 | 1         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 1         | 2.04%   |
| Intel Centrino Advanced-N 6200                                | 1         | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 2.04%   |
| Intel Alder Lake-U CNVi: Wireless-AC                          | 1         | 2.04%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 1         | 2.04%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter   | 1         | 2.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 1         | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 26        | 63.41%  |
| Intel                 | 8         | 19.51%  |
| Qualcomm Atheros      | 2         | 4.88%   |
| DisplayLink           | 2         | 4.88%   |
| Broadcom Limited      | 1         | 2.44%   |
| Broadcom              | 1         | 2.44%   |
| ASIX Electronics      | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 51.22%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 9.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.44%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.44%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.44%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.44%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 2.44%   |
| DisplayLink Plugable UD-3900                                      | 1         | 2.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.44%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 2.44%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 52.22%  |
| Ethernet | 39        | 43.33%  |
| Modem    | 4         | 4.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 77.08%  |
| Ethernet | 11        | 22.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 33        | 68.75%  |
| 1     | 12        | 25%     |
| 3     | 2         | 4.17%   |
| 0     | 1         | 2.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| Yes  | 28        | 58.33%  |
| No   | 20        | 41.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 75%     |
| Foxconn / Hon Hai               | 3         | 6.82%   |
| Apple                           | 2         | 4.55%   |
| Realtek Semiconductor           | 1         | 2.27%   |
| Qualcomm Atheros Communications | 1         | 2.27%   |
| IMC Networks                    | 1         | 2.27%   |
| Cambridge Silicon Radio         | 1         | 2.27%   |
| Broadcom                        | 1         | 2.27%   |
| ASUSTek Computer                | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 13        | 29.55%  |
| Intel Bluetooth wireless interface                  | 6         | 13.64%  |
| Intel AX201 Bluetooth                               | 6         | 13.64%  |
| Intel Bluetooth Device                              | 4         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 4.55%   |
| Realtek Bluetooth Radio                             | 1         | 2.27%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.27%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.27%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.27%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 2.27%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 2.27%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 2.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.27%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.27%   |
| ASUS ASUS USB-BT500                                 | 1         | 2.27%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.27%   |
| Apple Bluetooth Host Controller                     | 1         | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 34        | 51.52%  |
| Nvidia                                 | 15        | 22.73%  |
| AMD                                    | 14        | 21.21%  |
| Sony Ericsson Mobile Communications AB | 1         | 1.52%   |
| Kingston Technology                    | 1         | 1.52%   |
| GN Netcom                              | 1         | 1.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 16.88%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 9.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 6.49%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 5.19%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 5.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 5.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 3.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 3.9%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 3.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.9%    |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 2.6%    |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 2.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 2.6%    |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.6%    |
| Intel Comet Lake PCH cAVS                                                  | 2         | 2.6%    |
| Intel CM238 HD Audio Controller                                            | 2         | 2.6%    |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.6%    |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 1.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.3%    |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.3%    |
| Kingston Technology HyperX QuadCast S                                      | 1         | 1.3%    |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.3%    |
| Intel Alder Lake-U cAVS (Audio, Voice, Speech)                             | 1         | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.3%    |
| GN Netcom Jabra Link 380                                                   | 1         | 1.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.3%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 40%     |
| SK hynix            | 5         | 33.33%  |
| Unknown             | 2         | 13.33%  |
| Elpida              | 1         | 6.67%   |
| ASint Technology    | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s | 2         | 13.33%  |
| Unknown                                                | 2         | 13.33%  |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s           | 1         | 6.67%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s | 1         | 6.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s | 1         | 6.67%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 6.67%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s | 1         | 6.67%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s | 1         | 6.67%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s | 1         | 6.67%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s | 1         | 6.67%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s  | 1         | 6.67%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s  | 1         | 6.67%   |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s     | 1         | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 8         | 61.54%  |
| DDR3   | 4         | 30.77%  |
| LPDDR5 | 1         | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 12        | 92.31%  |
| Row Of Chips | 1         | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 4         | 26.67%  |
| 8192  | 4         | 26.67%  |
| 2048  | 3         | 20%     |
| 32768 | 2         | 13.33%  |
| 4096  | 2         | 13.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 6         | 46.15%  |
| 1600  | 3         | 23.08%  |
| 8400  | 1         | 7.69%   |
| 6400  | 1         | 7.69%   |
| 2667  | 1         | 7.69%   |
| 1067  | 1         | 7.69%   |

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
| Chicony Electronics           | 20        | 54.05%  |
| Suyin                         | 2         | 5.41%   |
| Sunplus Innovation Technology | 2         | 5.41%   |
| IMC Networks                  | 2         | 5.41%   |
| Bison Electronics             | 2         | 5.41%   |
| Acer                          | 2         | 5.41%   |
| Ricoh                         | 1         | 2.7%    |
| Realtek Semiconductor         | 1         | 2.7%    |
| Microdia                      | 1         | 2.7%    |
| Luxvisions Innotech Limited   | 1         | 2.7%    |
| Generalplus Technology        | 1         | 2.7%    |
| Apple                         | 1         | 2.7%    |
| Alpha Imaging Technology      | 1         | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated IR Camera                         | 5         | 13.51%  |
| Chicony HD Webcam                                    | 3         | 8.11%   |
| Chicony FHD Webcam                                   | 3         | 8.11%   |
| IMC Networks Integrated Camera                       | 2         | 5.41%   |
| Chicony USB2.0 Camera                                | 2         | 5.41%   |
| Chicony Integrated Camera                            | 2         | 5.41%   |
| Suyin RGBIR Camera                                   | 1         | 2.7%    |
| Suyin HP TrueVision HD                               | 1         | 2.7%    |
| Sunplus Integrated_Webcam_HD                         | 1         | 2.7%    |
| Sunplus Asus Webcam                                  | 1         | 2.7%    |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 2.7%    |
| Realtek Integrated Webcam                            | 1         | 2.7%    |
| Microdia Integrated_Webcam_FHD                       | 1         | 2.7%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 2.7%    |
| Generalplus WEB CAM                                  | 1         | 2.7%    |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 2.7%    |
| Chicony USB 2.0 Camera                               | 1         | 2.7%    |
| Chicony FJ Camera                                    | 1         | 2.7%    |
| Chicony ACER FHD User Facing                         | 1         | 2.7%    |
| Chicony 1.3M Webcam                                  | 1         | 2.7%    |
| Bison Lenovo EasyCamera                              | 1         | 2.7%    |
| Bison HD Webcam                                      | 1         | 2.7%    |
| Apple FaceTime HD Camera                             | 1         | 2.7%    |
| Alpha Imaging Integrated_Webcam_8M                   | 1         | 2.7%    |
| Acer Lenovo Integrated Webcam                        | 1         | 2.7%    |
| Acer HD Webcam                                       | 1         | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 44.44%  |
| Synaptics             | 4         | 44.44%  |
| LighTuning Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 11.11%  |
| Validity Sensors VFS491                           | 1         | 11.11%  |
| Validity Sensors VFS Fingerprint sensor           | 1         | 11.11%  |
| Validity Sensors Fingerprint scanner              | 1         | 11.11%  |
| Synaptics WBDI                                    | 1         | 11.11%  |
| Synaptics UWP WBDI                                | 1         | 11.11%  |
| LighTuning Fingerprint Reader                     | 1         | 11.11%  |

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
| 0     | 26        | 54.17%  |
| 1     | 21        | 43.75%  |
| 3     | 1         | 2.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 36%     |
| Multimedia controller | 8         | 32%     |
| Chipcard              | 4         | 16%     |
| Graphics card         | 2         | 8%      |
| Net/wireless          | 1         | 4%      |
| Modem                 | 1         | 4%      |

