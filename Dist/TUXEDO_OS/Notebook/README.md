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

Total: 82

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| TUXEDO        | InfinityBook S 15 Gen6      | [c53e992822](https://linux-hardware.org/?probe=c53e992822) | Aug 26, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [b6e2112ccb](https://linux-hardware.org/?probe=b6e2112ccb) | Aug 13, 2023 |
| Dell          | Precision 7750              | [cebb7f5165](https://linux-hardware.org/?probe=cebb7f5165) | Aug 06, 2023 |
| TUXEDO        | N7x0WU                      | [1c2cb06178](https://linux-hardware.org/?probe=1c2cb06178) | Aug 06, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [64e640ff2b](https://linux-hardware.org/?probe=64e640ff2b) | Aug 04, 2023 |
| TUXEDO        | Aura 15 Gen2                | [07d668ee3d](https://linux-hardware.org/?probe=07d668ee3d) | Aug 03, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [c6078d0836](https://linux-hardware.org/?probe=c6078d0836) | Aug 02, 2023 |
| Lenovo        | ThinkPad E580 20KS003SUS    | [9b8485b740](https://linux-hardware.org/?probe=9b8485b740) | Aug 01, 2023 |
| HP            | Notebook                    | [beef8e7fce](https://linux-hardware.org/?probe=beef8e7fce) | Jul 25, 2023 |
| HP            | Notebook                    | [4746f66332](https://linux-hardware.org/?probe=4746f66332) | Jul 23, 2023 |
| Lenovo        | G580 20150                  | [bcd1c01ad6](https://linux-hardware.org/?probe=bcd1c01ad6) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | [390008fe3c](https://linux-hardware.org/?probe=390008fe3c) | Jul 15, 2023 |
| HP            | Laptop 15-dw3xxx            | [fd0926d15b](https://linux-hardware.org/?probe=fd0926d15b) | Jul 14, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [26fda3b894](https://linux-hardware.org/?probe=26fda3b894) | Jul 14, 2023 |
| Dell          | Latitude E6530              | [25cbd87821](https://linux-hardware.org/?probe=25cbd87821) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | [29a9ad60a6](https://linux-hardware.org/?probe=29a9ad60a6) | Jul 13, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [2015dd83cb](https://linux-hardware.org/?probe=2015dd83cb) | Jul 12, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [54ac55c49e](https://linux-hardware.org/?probe=54ac55c49e) | Jul 07, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [296474a1b1](https://linux-hardware.org/?probe=296474a1b1) | Jul 07, 2023 |
| TUXEDO        | Book XUX7 Gen13             | [e480e61359](https://linux-hardware.org/?probe=e480e61359) | Jul 06, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [3d599df965](https://linux-hardware.org/?probe=3d599df965) | Jul 02, 2023 |
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
| TUXEDO OS 22.04 | 63        | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 63        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 6.1.0-1009-tuxedo   | 12        | 17.39%  |
| 6.2.0-10005-tuxedo  | 9         | 13.04%  |
| 6.2.0-10011-tuxedo  | 8         | 11.59%  |
| 6.2.0-10007-tuxedo  | 8         | 11.59%  |
| 6.2.0-10018-tuxedo  | 6         | 8.7%    |
| 6.2.0-10010-tuxedo  | 6         | 8.7%    |
| 5.15.0-10058-tuxedo | 4         | 5.8%    |
| 5.15.0-10048-tuxedo | 4         | 5.8%    |
| 5.15.0-10053-tuxedo | 3         | 4.35%   |
| 5.15.0-10052-tuxedo | 3         | 4.35%   |
| 5.15.0-10050-tuxedo | 2         | 2.9%    |
| 6.2.0-10014-tuxedo  | 1         | 1.45%   |
| 6.0.0-1010-oem      | 1         | 1.45%   |
| 5.15.0-10057-tuxedo | 1         | 1.45%   |
| 5.15.0-10056-tuxedo | 1         | 1.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 38        | 55.07%  |
| 5.15.0  | 18        | 26.09%  |
| 6.1.0   | 12        | 17.39%  |
| 6.0.0   | 1         | 1.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 38        | 55.07%  |
| 5.15    | 18        | 26.09%  |
| 6.1     | 12        | 17.39%  |
| 6.0     | 1         | 1.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 63        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| KDE5 | 63        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 63        | 98.44%  |
| Wayland | 1         | 1.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 53        | 81.54%  |
| SDDM    | 12        | 18.46%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| de_DE | 31        | 49.21%  |
| en_US | 15        | 23.81%  |
| en_GB | 5         | 7.94%   |
| pl_PL | 2         | 3.17%   |
| fr_FR | 2         | 3.17%   |
| pt_PT | 1         | 1.59%   |
| pt_BR | 1         | 1.59%   |
| hu_HU | 1         | 1.59%   |
| es_ES | 1         | 1.59%   |
| en_ZA | 1         | 1.59%   |
| en_DK | 1         | 1.59%   |
| en_AU | 1         | 1.59%   |
| en_AG | 1         | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 54        | 84.38%  |
| EFI  | 10        | 15.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 54        | 85.71%  |
| Btrfs   | 5         | 7.94%   |
| Tmpfs   | 3         | 4.76%   |
| Overlay | 1         | 1.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 53        | 81.54%  |
| GPT     | 11        | 16.92%  |
| MBR     | 1         | 1.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 61        | 95.31%  |
| Yes       | 3         | 4.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 93.75%  |
| Yes       | 4         | 6.25%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| TUXEDO           | 27        | 42.86%  |
| Lenovo           | 9         | 14.29%  |
| Dell             | 7         | 11.11%  |
| Hewlett-Packard  | 6         | 9.52%   |
| ASUSTek Computer | 4         | 6.35%   |
| Apple            | 3         | 4.76%   |
| Acer             | 2         | 3.17%   |
| Notebook         | 1         | 1.59%   |
| MSI              | 1         | 1.59%   |
| Fujitsu          | 1         | 1.59%   |
| BESSTAR Tech     | 1         | 1.59%   |
| Unknown          | 1         | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| TUXEDO InfinityBook S 15/17 Gen7    | 4         | 6.35%   |
| Unknown                             | 3         | 4.76%   |
| TUXEDO Stellaris/Polaris AMD Gen4   | 2         | 3.17%   |
| TUXEDO Pulse 15 Gen2                | 2         | 3.17%   |
| TUXEDO Pulse 15 Gen1                | 2         | 3.17%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 2         | 3.17%   |
| TUXEDO InfinityBook Pro 14 Gen6     | 2         | 3.17%   |
| Apple MacBookPro8,1                 | 2         | 3.17%   |
| TUXEDO XMG FUSION 15 (XFU15L19)     | 1         | 1.59%   |
| TUXEDO Stellaris AMD Gen3 (CZN)     | 1         | 1.59%   |
| TUXEDO Polaris AMD Gen3 (CZN)       | 1         | 1.59%   |
| TUXEDO Polaris 15 AMD Gen1          | 1         | 1.59%   |
| TUXEDO P64_HJ,HK1                   | 1         | 1.59%   |
| TUXEDO N7x0WU                       | 1         | 1.59%   |
| TUXEDO N13xWU                       | 1         | 1.59%   |
| TUXEDO InfinityBook S 15 Gen6       | 1         | 1.59%   |
| TUXEDO InfinityBook Pro Gen7 (MK2)  | 1         | 1.59%   |
| TUXEDO Book XUX7 Gen13              | 1         | 1.59%   |
| TUXEDO Aura 15 Gen2                 | 1         | 1.59%   |
| Notebook W65_W67RB                  | 1         | 1.59%   |
| MSI GE75 Raider 10SF                | 1         | 1.59%   |
| Lenovo Yoga S740-15IRH 81NX         | 1         | 1.59%   |
| Lenovo ThinkPad X200 Tablet 7450WN9 | 1         | 1.59%   |
| Lenovo ThinkPad T490 20N3SBU219     | 1         | 1.59%   |
| Lenovo ThinkPad P1 Gen 3 20TJS1W700 | 1         | 1.59%   |
| Lenovo ThinkPad E580 20KS003SUS     | 1         | 1.59%   |
| Lenovo Legion 5 15ACH6H 82JU        | 1         | 1.59%   |
| Lenovo IdeaPad N581 7505            | 1         | 1.59%   |
| Lenovo G580 20150                   | 1         | 1.59%   |
| Lenovo G50-80 80E5                  | 1         | 1.59%   |
| HP Pavilion dv6                     | 1         | 1.59%   |
| HP OMEN Laptop 15-en0xxx            | 1         | 1.59%   |
| HP Notebook                         | 1         | 1.59%   |
| HP Laptop 15-dw3xxx                 | 1         | 1.59%   |
| HP EliteBook 820 G2                 | 1         | 1.59%   |
| HP EliteBook 2570p                  | 1         | 1.59%   |
| Fujitsu LIFEBOOK U7412              | 1         | 1.59%   |
| Dell Vostro 3550                    | 1         | 1.59%   |
| Dell Venue 11 Pro 7130 vPro         | 1         | 1.59%   |
| Dell Precision 7750                 | 1         | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| TUXEDO InfinityBook | 10        | 15.87%  |
| TUXEDO Pulse        | 4         | 6.35%   |
| Lenovo ThinkPad     | 4         | 6.35%   |
| TUXEDO Stellaris    | 3         | 4.76%   |
| Unknown             | 3         | 4.76%   |
| TUXEDO Polaris      | 2         | 3.17%   |
| HP EliteBook        | 2         | 3.17%   |
| Dell Precision      | 2         | 3.17%   |
| Dell Latitude       | 2         | 3.17%   |
| Apple MacBookPro8   | 2         | 3.17%   |
| TUXEDO XMG          | 1         | 1.59%   |
| TUXEDO P64          | 1         | 1.59%   |
| TUXEDO N7x0WU       | 1         | 1.59%   |
| TUXEDO N13xWU       | 1         | 1.59%   |
| TUXEDO Book         | 1         | 1.59%   |
| TUXEDO Aura         | 1         | 1.59%   |
| Notebook W65        | 1         | 1.59%   |
| MSI GE75            | 1         | 1.59%   |
| Lenovo Yoga         | 1         | 1.59%   |
| Lenovo Legion       | 1         | 1.59%   |
| Lenovo IdeaPad      | 1         | 1.59%   |
| Lenovo G580         | 1         | 1.59%   |
| Lenovo G50-80       | 1         | 1.59%   |
| HP Pavilion         | 1         | 1.59%   |
| HP OMEN             | 1         | 1.59%   |
| HP Notebook         | 1         | 1.59%   |
| HP Laptop           | 1         | 1.59%   |
| Fujitsu LIFEBOOK    | 1         | 1.59%   |
| Dell Vostro         | 1         | 1.59%   |
| Dell Venue          | 1         | 1.59%   |
| Dell Inspiron       | 1         | 1.59%   |
| BESSTAR Tech X400   | 1         | 1.59%   |
| ASUS Zephyrus       | 1         | 1.59%   |
| ASUS ROG            | 1         | 1.59%   |
| ASUS K55VJ          | 1         | 1.59%   |
| ASUS BU201LAV       | 1         | 1.59%   |
| Apple MacBookAir7   | 1         | 1.59%   |
| Acer TravelMate     | 1         | 1.59%   |
| Acer Swift          | 1         | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 16        | 25.4%   |
| 2020 | 9         | 14.29%  |
| 2021 | 7         | 11.11%  |
| 2015 | 6         | 9.52%   |
| 2019 | 5         | 7.94%   |
| 2012 | 5         | 7.94%   |
| 2017 | 4         | 6.35%   |
| 2011 | 3         | 4.76%   |
| 2023 | 2         | 3.17%   |
| 2014 | 2         | 3.17%   |
| 2018 | 1         | 1.59%   |
| 2010 | 1         | 1.59%   |
| 2009 | 1         | 1.59%   |
| 2008 | 1         | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 63        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 63        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 14        | 22.22%  |
| 32.01-64.0  | 13        | 20.63%  |
| 8.01-16.0   | 13        | 20.63%  |
| 4.01-8.0    | 10        | 15.87%  |
| 64.01-256.0 | 7         | 11.11%  |
| 3.01-4.0    | 4         | 6.35%   |
| 24.01-32.0  | 2         | 3.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 24        | 35.82%  |
| 1.01-2.0   | 14        | 20.9%   |
| 2.01-3.0   | 13        | 19.4%   |
| 3.01-4.0   | 10        | 14.93%  |
| 8.01-16.0  | 4         | 5.97%   |
| 16.01-24.0 | 2         | 2.99%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 34        | 53.13%  |
| 2      | 26        | 40.63%  |
| 3      | 3         | 4.69%   |
| 4      | 1         | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 82.54%  |
| Yes       | 11        | 17.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 84.13%  |
| No        | 10        | 15.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 98.41%  |
| No        | 1         | 1.59%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 90.48%  |
| No        | 6         | 9.52%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 33        | 52.38%  |
| USA          | 9         | 14.29%  |
| UK           | 4         | 6.35%   |
| Switzerland  | 2         | 3.17%   |
| Portugal     | 2         | 3.17%   |
| Poland       | 2         | 3.17%   |
| France       | 2         | 3.17%   |
| Turkey       | 1         | 1.59%   |
| Spain        | 1         | 1.59%   |
| South Africa | 1         | 1.59%   |
| Denmark      | 1         | 1.59%   |
| Czechia      | 1         | 1.59%   |
| Bulgaria     | 1         | 1.59%   |
| Brazil       | 1         | 1.59%   |
| Austria      | 1         | 1.59%   |
| Australia    | 1         | 1.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Schweinfurt        | 2         | 3.13%   |
| Munich             | 2         | 3.13%   |
| Berlin             | 2         | 3.13%   |
| Zurich             | 1         | 1.56%   |
| Zabrze             | 1         | 1.56%   |
| Wembley            | 1         | 1.56%   |
| Watertown          | 1         | 1.56%   |
| Warsaw             | 1         | 1.56%   |
| Walsall            | 1         | 1.56%   |
| Vienna             | 1         | 1.56%   |
| Stuttgart          | 1         | 1.56%   |
| Stockstadt am Main | 1         | 1.56%   |
| Solingen           | 1         | 1.56%   |
| Sistov             | 1         | 1.56%   |
| Seattle            | 1         | 1.56%   |
| Rio Maior          | 1         | 1.56%   |
| Reno               | 1         | 1.56%   |
| Rennes             | 1         | 1.56%   |
| Redcar             | 1         | 1.56%   |
| Pruem              | 1         | 1.56%   |
| Prague             | 1         | 1.56%   |
| Perrysburg         | 1         | 1.56%   |
| Paris              | 1         | 1.56%   |
| Nuremberg          | 1         | 1.56%   |
| Neuwied            | 1         | 1.56%   |
| Nashville          | 1         | 1.56%   |
| Melton Mowbray     | 1         | 1.56%   |
| Mannheim           | 1         | 1.56%   |
| Lucerne            | 1         | 1.56%   |
| Lippstadt          | 1         | 1.56%   |
| Leipzig            | 1         | 1.56%   |
| Lehre              | 1         | 1.56%   |
| Langenhagen        | 1         | 1.56%   |
| Laage              | 1         | 1.56%   |
| Kiel               | 1         | 1.56%   |
| Johannesburg       | 1         | 1.56%   |
| Jessen             | 1         | 1.56%   |
| Itajaí            | 1         | 1.56%   |
| Istanbul           | 1         | 1.56%   |
| Husum              | 1         | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 35        | 48     | 40.23%  |
| Sandisk                     | 8         | 9      | 9.2%    |
| Seagate                     | 7         | 7      | 8.05%   |
| Kingston                    | 5         | 5      | 5.75%   |
| Hitachi                     | 4         | 6      | 4.6%    |
| WDC                         | 3         | 3      | 3.45%   |
| Unknown                     | 2         | 2      | 2.3%    |
| Toshiba                     | 2         | 2      | 2.3%    |
| SPCC                        | 2         | 2      | 2.3%    |
| SK hynix                    | 2         | 3      | 2.3%    |
| Phison Electronics          | 2         | 2      | 2.3%    |
| Micron Technology           | 2         | 2      | 2.3%    |
| USB3.0                      | 1         | 1      | 1.15%   |
| Transcend                   | 1         | 1      | 1.15%   |
| OWC                         | 1         | 1      | 1.15%   |
| Netac                       | 1         | 1      | 1.15%   |
| LITEONIT                    | 1         | 1      | 1.15%   |
| Lenovo                      | 1         | 1      | 1.15%   |
| Kingston Technology Company | 1         | 1      | 1.15%   |
| Kingchuxing                 | 1         | 1      | 1.15%   |
| Intenso                     | 1         | 1      | 1.15%   |
| Intel                       | 1         | 1      | 1.15%   |
| CT1000BX                    | 1         | 1      | 1.15%   |
| Crucial                     | 1         | 1      | 1.15%   |
| Apple                       | 1         | 1      | 1.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 9         | 9.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 7         | 7.69%   |
| Samsung SSD 980 1TB                                   | 5         | 5.49%   |
| Samsung SSD 980 500GB                                 | 4         | 4.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 3         | 3.3%    |
| Samsung SSD 980 PRO 500GB                             | 2         | 2.2%    |
| Samsung SSD 980 PRO 1TB                               | 2         | 2.2%    |
| Samsung SSD 970 EVO Plus 1TB                          | 2         | 2.2%    |
| Kingston SA400S37240G 240GB SSD                       | 2         | 2.2%    |
| Hitachi HTS727550A9E364 500GB                         | 2         | 2.2%    |
| WDC WD3200BPVT-24JJ5T0 320GB                          | 1         | 1.1%    |
| WDC WD10JPVX-22JC3T0 1TB                              | 1         | 1.1%    |
| WDC WD Elements SE SSD 1TB                            | 1         | 1.1%    |
| USB3.0 Super Speed 128GB                              | 1         | 1.1%    |
| Unknown MMC Card  64GB                                | 1         | 1.1%    |
| Unknown MMC Card  2GB                                 | 1         | 1.1%    |
| Transcend TS512GSSD230S 512GB                         | 1         | 1.1%    |
| Toshiba XG4 NVMe SSD Controller 256GB                 | 1         | 1.1%    |
| Toshiba MQ01ABD100 1TB                                | 1         | 1.1%    |
| SPCC M.2 SSD 256GB                                    | 1         | 1.1%    |
| SPCC M.2 PCIe SSD 1TB                                 | 1         | 1.1%    |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                  | 1         | 1.1%    |
| SK hynix SC311 SATA 256GB SSD                         | 1         | 1.1%    |
| Seagate ST500LT012-1DG142 500GB                       | 1         | 1.1%    |
| Seagate ST500LM034-2GH17A 500GB                       | 1         | 1.1%    |
| Seagate ST250LT003-9YG14C 250GB                       | 1         | 1.1%    |
| Seagate ST2000LM015-2E8174 2TB                        | 1         | 1.1%    |
| Seagate ST1000LM048-2E7172 1TB                        | 1         | 1.1%    |
| Seagate Expansion 2TB                                 | 1         | 1.1%    |
| Seagate BarraCuda Q5 ZP500CV30001 500GB               | 1         | 1.1%    |
| Sandisk WD PC SN735 SDBPNHH-1T00-1002 1TB             | 1         | 1.1%    |
| Sandisk WD Blue SN570 1TB                             | 1         | 1.1%    |
| Sandisk WD Black SN850 256GB                          | 1         | 1.1%    |
| Sandisk Ultra 3D NVMe 1TB                             | 1         | 1.1%    |
| SanDisk SDSSDA240G 240GB                              | 1         | 1.1%    |
| SanDisk SD6SB1M-128G-1006 128GB SSD                   | 1         | 1.1%    |
| Samsung SSD 970 PRO 512GB                             | 1         | 1.1%    |
| Samsung SSD 860 PRO 512GB                             | 1         | 1.1%    |
| Samsung SSD 860 EVO M.2 250GB                         | 1         | 1.1%    |
| Samsung SSD 860 EVO 250GB                             | 1         | 1.1%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 42.86%  |
| Hitachi | 4         | 6      | 28.57%  |
| WDC     | 2         | 2      | 14.29%  |
| USB3.0  | 1         | 1      | 7.14%   |
| Toshiba | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 22.73%  |
| Kingston            | 3         | 3      | 13.64%  |
| SanDisk             | 2         | 2      | 9.09%   |
| WDC                 | 1         | 1      | 4.55%   |
| Transcend           | 1         | 1      | 4.55%   |
| SPCC                | 1         | 1      | 4.55%   |
| SK hynix            | 1         | 2      | 4.55%   |
| OWC                 | 1         | 1      | 4.55%   |
| Netac               | 1         | 1      | 4.55%   |
| Micron Technology   | 1         | 1      | 4.55%   |
| LITEONIT            | 1         | 1      | 4.55%   |
| Intenso             | 1         | 1      | 4.55%   |
| CT1000BX            | 1         | 1      | 4.55%   |
| Crucial             | 1         | 1      | 4.55%   |
| Apple               | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 41        | 62     | 53.25%  |
| SSD     | 19        | 23     | 24.68%  |
| HDD     | 14        | 16     | 18.18%  |
| MMC     | 2         | 2      | 2.6%    |
| Unknown | 1         | 1      | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 41        | 62     | 54.67%  |
| SATA | 28        | 36     | 37.33%  |
| SAS  | 4         | 4      | 5.33%   |
| MMC  | 2         | 2      | 2.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 27     | 63.64%  |
| 0.51-1.0   | 10        | 10     | 30.3%   |
| 1.01-2.0   | 2         | 2      | 6.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 17        | 26.98%  |
| 251-500        | 14        | 22.22%  |
| 101-250        | 14        | 22.22%  |
| 1001-2000      | 6         | 9.52%   |
| 2001-3000      | 3         | 4.76%   |
| 1-20           | 3         | 4.76%   |
| More than 3000 | 2         | 3.17%   |
| Unknown        | 2         | 3.17%   |
| 21-50          | 1         | 1.59%   |
| 51-100         | 1         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 20        | 30.77%  |
| 1-20      | 18        | 27.69%  |
| 101-250   | 12        | 18.46%  |
| 51-100    | 5         | 7.69%   |
| 251-500   | 4         | 6.15%   |
| 1001-2000 | 2         | 3.08%   |
| 501-1000  | 2         | 3.08%   |
| Unknown   | 2         | 3.08%   |

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
| Detected | 53        | 87     | 80.3%   |
| Works    | 13        | 17     | 19.7%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 31        | 36.05%  |
| Intel                        | 31        | 36.05%  |
| AMD                          | 7         | 8.14%   |
| SanDisk                      | 6         | 6.98%   |
| Kingston Technology Company  | 3         | 3.49%   |
| Phison Electronics           | 2         | 2.33%   |
| Toshiba America Info Systems | 1         | 1.16%   |
| SK hynix                     | 1         | 1.16%   |
| Silicon Motion               | 1         | 1.16%   |
| Seagate Technology           | 1         | 1.16%   |
| Micron Technology            | 1         | 1.16%   |
| Lenovo                       | 1         | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 12        | 13.64%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 9         | 10.23%  |
| Samsung NVMe SSD Controller 980                                              | 9         | 10.23%  |
| AMD FCH SATA Controller [AHCI mode]                                          | 7         | 7.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 6         | 6.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 4         | 4.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 3         | 3.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 3         | 3.41%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                           | 2         | 2.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 2.27%   |
| Intel Volume Management Device NVMe RAID Controller                          | 2         | 2.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 2.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 2.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 2.27%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                         | 1         | 1.14%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 1.14%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 1.14%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                    | 1         | 1.14%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                   | 1         | 1.14%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                        | 1         | 1.14%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                   | 1         | 1.14%   |
| Phison PS5013 E13 NVMe Controller                                            | 1         | 1.14%   |
| Phison E16 PCIe4 NVMe Controller                                             | 1         | 1.14%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 1         | 1.14%   |
| Lenovo LENSE30256GMSP34MEAT3TA                                               | 1         | 1.14%   |
| Kingston Company Company Non-Volatile memory controller                      | 1         | 1.14%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                | 1         | 1.14%   |
| Kingston Company NVMe Controller                                             | 1         | 1.14%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation        | 1         | 1.14%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 1.14%   |
| Intel SSD 660P Series                                                        | 1         | 1.14%   |
| Intel SATA Controller [RAID mode]                                            | 1         | 1.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 1.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 1         | 1.14%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                         | 1         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 1.14%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 1         | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 41        | 51.25%  |
| SATA | 34        | 42.5%   |
| RAID | 5         | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 74.6%   |
| AMD    | 16        | 25.4%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H           | 3         | 4.76%   |
| Intel 12th Gen Core i7-1260P            | 3         | 4.76%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 3         | 4.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 3.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 3.17%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 2         | 3.17%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 3.17%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 3.17%   |
| Intel 12th Gen Core i5-1240P            | 2         | 3.17%   |
| AMD Ryzen 7 6800H with Radeon Graphics  | 2         | 3.17%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 3.17%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 3.17%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 2         | 3.17%   |
| Intel Xeon W-10855M CPU @ 2.80GHz       | 1         | 1.59%   |
| Intel Pentium CPU 2020M @ 2.40GHz       | 1         | 1.59%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 1.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.59%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.59%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.59%   |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 1.59%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 1.59%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 1.59%   |
| Intel Core i7-10850H CPU @ 2.70GHz      | 1         | 1.59%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.59%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 1         | 1.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.59%   |
| Intel Core i5-5250U CPU @ 1.60GHz       | 1         | 1.59%   |
| Intel Core i5-4300Y CPU @ 1.60GHz       | 1         | 1.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.59%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 1         | 1.59%   |
| Intel Core i5 CPU M 540 @ 2.53GHz       | 1         | 1.59%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz    | 1         | 1.59%   |
| Intel Celeron CPU 1037U @ 1.80GHz       | 1         | 1.59%   |
| Intel 13th Gen Core i7-1360P            | 1         | 1.59%   |
| Intel 12th Gen Core i7-1255U            | 1         | 1.59%   |
| Intel 12th Gen Core i3-1215U            | 1         | 1.59%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz | 1         | 1.59%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 1         | 1.59%   |
| AMD Ryzen 9 6900HX with Radeon Graphics | 1         | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 18        | 28.57%  |
| Other            | 16        | 25.4%   |
| Intel Core i5    | 9         | 14.29%  |
| AMD Ryzen 7      | 8         | 12.7%   |
| AMD Ryzen 5      | 3         | 4.76%   |
| AMD Ryzen 9      | 2         | 3.17%   |
| Intel Xeon       | 1         | 1.59%   |
| Intel Pentium    | 1         | 1.59%   |
| Intel Core 2 Duo | 1         | 1.59%   |
| Intel Celeron    | 1         | 1.59%   |
| AMD Ryzen 5 PRO  | 1         | 1.59%   |
| AMD Ryzen 3      | 1         | 1.59%   |
| AMD A8           | 1         | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 20        | 31.75%  |
| 2      | 13        | 20.63%  |
| 8      | 10        | 15.87%  |
| 6      | 10        | 15.87%  |
| 12     | 6         | 9.52%   |
| 14     | 3         | 4.76%   |
| 10     | 1         | 1.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 63        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 59        | 93.65%  |
| 1      | 4         | 6.35%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 63        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 87.69%  |
| 0x906ea    | 1         | 1.54%   |
| 0x906e9    | 1         | 1.54%   |
| 0x906a4    | 1         | 1.54%   |
| 0x906a3    | 1         | 1.54%   |
| 0x806c1    | 1         | 1.54%   |
| 0x306d4    | 1         | 1.54%   |
| 0x0a50000c | 1         | 1.54%   |
| 0x08608103 | 1         | 1.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 15        | 23.81%  |
| KabyLake         | 10        | 15.87%  |
| IvyBridge        | 6         | 9.52%   |
| Zen 2            | 5         | 7.94%   |
| TigerLake        | 4         | 6.35%   |
| SandyBridge      | 4         | 6.35%   |
| Zen 3            | 3         | 4.76%   |
| CometLake        | 3         | 4.76%   |
| Broadwell        | 3         | 4.76%   |
| Alderlake Hybrid | 3         | 4.76%   |
| Haswell          | 2         | 3.17%   |
| Zen+             | 1         | 1.59%   |
| Westmere         | 1         | 1.59%   |
| Skylake          | 1         | 1.59%   |
| Puma             | 1         | 1.59%   |
| Penryn           | 1         | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 51.72%  |
| Nvidia | 24        | 27.59%  |
| AMD    | 18        | 20.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P Integrated Graphics Controller                             | 8         | 9.2%    |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 6.9%    |
| AMD Renoir                                                                    | 5         | 5.75%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 4         | 4.6%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 4         | 4.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 4.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 4         | 4.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 4.6%    |
| Intel UHD Graphics 620                                                        | 3         | 3.45%   |
| AMD Rembrandt [Radeon 680M]                                                   | 3         | 3.45%   |
| AMD Lucienne                                                                  | 3         | 3.45%   |
| Nvidia GF108M [GeForce GT 635M]                                               | 2         | 2.3%    |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                      | 2         | 2.3%    |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                 | 2         | 2.3%    |
| Intel HD Graphics 630                                                         | 2         | 2.3%    |
| Intel HD Graphics 5500                                                        | 2         | 2.3%    |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 2.3%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 2.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.15%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 1.15%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 1.15%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 1.15%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                              | 1         | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.15%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 1.15%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 1         | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.15%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 1         | 1.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.15%   |
| Intel HD Graphics 6000                                                        | 1         | 1.15%   |
| Intel HD Graphics 530                                                         | 1         | 1.15%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                | 1         | 1.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 1.15%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.15%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 1         | 1.15%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                       | 1         | 1.15%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                 | 1         | 1.15%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 1.15%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 45.31%  |
| Intel + Nvidia | 13        | 20.31%  |
| AMD + Nvidia   | 8         | 12.5%   |
| 1 x AMD        | 8         | 12.5%   |
| 1 x Nvidia     | 3         | 4.69%   |
| Intel + AMD    | 3         | 4.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 42        | 66.67%  |
| Proprietary | 20        | 31.75%  |
| Unknown     | 1         | 1.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 68.75%  |
| 5.01-6.0   | 9         | 14.06%  |
| 3.01-4.0   | 4         | 6.25%   |
| 7.01-8.0   | 3         | 4.69%   |
| 1.01-2.0   | 2         | 3.13%   |
| 8.01-16.0  | 1         | 1.56%   |
| 0.01-0.5   | 1         | 1.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 22        | 28.21%  |
| AU Optronics        | 12        | 15.38%  |
| Samsung Electronics | 8         | 10.26%  |
| LG Display          | 5         | 6.41%   |
| Chimei Innolux      | 5         | 6.41%   |
| CSO                 | 4         | 5.13%   |
| Dell                | 3         | 3.85%   |
| Apple               | 3         | 3.85%   |
| Lenovo              | 2         | 2.56%   |
| AOC                 | 2         | 2.56%   |
| Acer                | 2         | 2.56%   |
| Yamaha              | 1         | 1.28%   |
| Sharp               | 1         | 1.28%   |
| SGT                 | 1         | 1.28%   |
| RTK                 | 1         | 1.28%   |
| PANDA               | 1         | 1.28%   |
| Iiyama              | 1         | 1.28%   |
| Hewlett-Packard     | 1         | 1.28%   |
| Goldstar            | 1         | 1.28%   |
| BenQ                | 1         | 1.28%   |
| ASUSTek Computer    | 1         | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                   | 5         | 6.25%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 4         | 5%      |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 4         | 5%      |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 2         | 2.5%    |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 2.5%    |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 1.25%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 1.25%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 1.25%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 1.25%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch       | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch    | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch    | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 1.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 1.25%   |
| RTK Wimaxit FHD RTK5A5B 1920x1080 344x195mm 15.6-inch                   | 1         | 1.25%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 1.25%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD0545 3200x1800 293x165mm 13.2-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch            | 1         | 1.25%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 1.25%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                | 1         | 1.25%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                 | 1         | 1.25%   |
| Iiyama PL3466WQ IVM7627 3440x1440 795x334mm 33.9-inch                   | 1         | 1.25%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch              | 1         | 1.25%   |
| Goldstar W2261 GSM56CF 1920x1080 477x268mm 21.5-inch                    | 1         | 1.25%   |
| Dell U2715H DELD066 2560x1440 597x336mm 27.0-inch                       | 1         | 1.25%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 1.25%   |
| Dell AW2521HFA DELA160 1920x1080 544x303mm 24.5-inch                    | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch        | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 355x199mm 16.0-inch        | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch         | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 344x194mm 15.5-inch        | 1         | 1.25%   |
| BOE LCD Monitor BOE0A94 1920x1080 309x174mm 14.0-inch                   | 1         | 1.25%   |
| BOE LCD Monitor BOE0A67 2560x1440 344x194mm 15.5-inch                   | 1         | 1.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 33        | 44.59%  |
| 1366x768 (WXGA)    | 11        | 14.86%  |
| 2560x1440 (QHD)    | 8         | 10.81%  |
| 3840x2160 (4K)     | 5         | 6.76%   |
| 2880x1800          | 4         | 5.41%   |
| 1280x800 (WXGA)    | 3         | 4.05%   |
| 3440x1440          | 1         | 1.35%   |
| 3200x1800 (QHD+)   | 1         | 1.35%   |
| 2560x1600          | 1         | 1.35%   |
| 2240x1400          | 1         | 1.35%   |
| 1920x540           | 1         | 1.35%   |
| 1920x1200 (WUXGA)  | 1         | 1.35%   |
| 1680x1050 (WSXGA+) | 1         | 1.35%   |
| 1600x900 (HD+)     | 1         | 1.35%   |
| 1440x900 (WXGA+)   | 1         | 1.35%   |
| 1280x1024 (SXGA)   | 1         | 1.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 34        | 43.04%  |
| 17      | 7         | 8.86%   |
| 13      | 7         | 8.86%   |
| 14      | 5         | 6.33%   |
| 12      | 4         | 5.06%   |
| 27      | 3         | 3.8%    |
| 16      | 3         | 3.8%    |
| 40      | 2         | 2.53%   |
| 31      | 2         | 2.53%   |
| 24      | 2         | 2.53%   |
| 22      | 2         | 2.53%   |
| 84      | 1         | 1.27%   |
| 43      | 1         | 1.27%   |
| 33      | 1         | 1.27%   |
| 21      | 1         | 1.27%   |
| 20      | 1         | 1.27%   |
| 19      | 1         | 1.27%   |
| 18      | 1         | 1.27%   |
| Unknown | 1         | 1.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 53.85%  |
| 351-400     | 9         | 11.54%  |
| 201-300     | 9         | 11.54%  |
| 501-600     | 5         | 6.41%   |
| 401-500     | 5         | 6.41%   |
| 801-900     | 2         | 2.56%   |
| 601-700     | 2         | 2.56%   |
| 701-800     | 1         | 1.28%   |
| 1501-2000   | 1         | 1.28%   |
| 901-1000    | 1         | 1.28%   |
| Unknown     | 1         | 1.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 53        | 76.81%  |
| 16/10 | 12        | 17.39%  |
| 5/4   | 1         | 1.45%   |
| 32/9  | 1         | 1.45%   |
| 3/2   | 1         | 1.45%   |
| 21/9  | 1         | 1.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 43.04%  |
| 81-90          | 11        | 13.92%  |
| 121-130        | 7         | 8.86%   |
| 61-70          | 4         | 5.06%   |
| 351-500        | 3         | 3.8%    |
| 301-350        | 3         | 3.8%    |
| 201-250        | 3         | 3.8%    |
| 151-200        | 3         | 3.8%    |
| 111-120        | 3         | 3.8%    |
| 501-1000       | 3         | 3.8%    |
| More than 1000 | 1         | 1.27%   |
| 71-80          | 1         | 1.27%   |
| 251-300        | 1         | 1.27%   |
| 141-150        | 1         | 1.27%   |
| Unknown        | 1         | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 34        | 44.16%  |
| 101-120       | 17        | 22.08%  |
| 51-100        | 10        | 12.99%  |
| 161-240       | 9         | 11.69%  |
| More than 240 | 6         | 7.79%   |
| Unknown       | 1         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 44        | 69.84%  |
| 2     | 17        | 26.98%  |
| 3     | 1         | 1.59%   |
| 0     | 1         | 1.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 48        | 42.86%  |
| Realtek Semiconductor             | 36        | 32.14%  |
| Qualcomm Atheros                  | 6         | 5.36%   |
| Ralink Technology                 | 4         | 3.57%   |
| Broadcom Limited                  | 4         | 3.57%   |
| Broadcom                          | 4         | 3.57%   |
| Huawei Technologies               | 3         | 2.68%   |
| DisplayLink                       | 2         | 1.79%   |
| TP-Link                           | 1         | 0.89%   |
| MediaTek                          | 1         | 0.89%   |
| Ericsson Business Mobile Networks | 1         | 0.89%   |
| Dell                              | 1         | 0.89%   |
| ASIX Electronics                  | 1         | 0.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 22.22%  |
| Intel Wi-Fi 6 AX200                                               | 18        | 14.29%  |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 4.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 3.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3         | 2.38%   |
| Intel Wireless 8265 / 8275                                        | 3         | 2.38%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 2.38%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 2.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.59%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                  | 2         | 1.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.59%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 1.59%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 1.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.79%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.79%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.79%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.79%   |
| Intel Wireless-AC 9260                                            | 1         | 0.79%   |
| Intel Wireless 7260                                               | 1         | 0.79%   |
| Intel Wireless 3165                                               | 1         | 0.79%   |
| Intel Wireless 3160                                               | 1         | 0.79%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 0.79%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1         | 0.79%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.79%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.79%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 69.23%  |
| Realtek Semiconductor | 4         | 6.15%   |
| Ralink Technology     | 4         | 6.15%   |
| Broadcom              | 4         | 6.15%   |
| Qualcomm Atheros      | 3         | 4.62%   |
| Broadcom Limited      | 3         | 4.62%   |
| TP-Link               | 1         | 1.54%   |
| MediaTek              | 1         | 1.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 18        | 27.69%  |
| Intel Alder Lake-P PCH CNVi WiFi                              | 6         | 9.23%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 3         | 4.62%   |
| Intel Wireless 8265 / 8275                                    | 3         | 4.62%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 4.62%   |
| Intel Comet Lake PCH CNVi WiFi                                | 3         | 4.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 3.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2         | 3.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 3.08%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter   | 2         | 3.08%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 2         | 3.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 1.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 1.54%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 1.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 1.54%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 1.54%   |
| Intel Wireless-AC 9260                                        | 1         | 1.54%   |
| Intel Wireless 7260                                           | 1         | 1.54%   |
| Intel Wireless 3165                                           | 1         | 1.54%   |
| Intel Wireless 3160                                           | 1         | 1.54%   |
| Intel Ultimate N WiFi Link 5300                               | 1         | 1.54%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 1         | 1.54%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                 | 1         | 1.54%   |
| Intel Centrino Advanced-N 6200                                | 1         | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 1.54%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 1         | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                 | 1         | 1.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 1         | 1.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 36        | 65.45%  |
| Intel                 | 10        | 18.18%  |
| Qualcomm Atheros      | 3         | 5.45%   |
| DisplayLink           | 2         | 3.64%   |
| Broadcom              | 2         | 3.64%   |
| Broadcom Limited      | 1         | 1.82%   |
| ASIX Electronics      | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 50%     |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 8.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 3.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.79%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.79%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.79%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.79%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.79%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.79%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.79%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.79%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.79%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.79%   |
| DisplayLink USB 3.0 Dual 4K Displayport adapter                   | 1         | 1.79%   |
| DisplayLink Plugable UD-3900                                      | 1         | 1.79%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 1.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 51.67%  |
| Ethernet | 53        | 44.17%  |
| Modem    | 5         | 4.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 71.43%  |
| Ethernet | 18        | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 47        | 74.6%   |
| 1     | 13        | 20.63%  |
| 3     | 2         | 3.17%   |
| 0     | 1         | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| Yes  | 35        | 55.56%  |
| No   | 28        | 44.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 72.41%  |
| Realtek Semiconductor           | 3         | 5.17%   |
| Foxconn / Hon Hai               | 3         | 5.17%   |
| Apple                           | 3         | 5.17%   |
| Broadcom                        | 2         | 3.45%   |
| Qualcomm Atheros Communications | 1         | 1.72%   |
| IMC Networks                    | 1         | 1.72%   |
| Dell                            | 1         | 1.72%   |
| Cambridge Silicon Radio         | 1         | 1.72%   |
| ASUSTek Computer                | 1         | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 18        | 31.03%  |
| Intel AX201 Bluetooth                               | 9         | 15.52%  |
| Intel Bluetooth wireless interface                  | 7         | 12.07%  |
| Intel Bluetooth Device                              | 4         | 6.9%    |
| Realtek Bluetooth Radio                             | 2         | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 3.45%   |
| Apple Bluetooth Host Controller                     | 2         | 3.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.72%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.72%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.72%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.72%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.72%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.72%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.72%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.72%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.72%   |
| ASUS ASUS USB-BT500                                 | 1         | 1.72%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 45        | 52.94%  |
| Nvidia                                 | 19        | 22.35%  |
| AMD                                    | 17        | 20%     |
| Sony Ericsson Mobile Communications AB | 1         | 1.18%   |
| Logitech                               | 1         | 1.18%   |
| Kingston Technology                    | 1         | 1.18%   |
| GN Netcom                              | 1         | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 15.31%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 10        | 10.2%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 6.12%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 6.12%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 4.08%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 4.08%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 4.08%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 3.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 3.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 3.06%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 3.06%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 3.06%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 3.06%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 3.06%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.04%   |
| Intel CM238 HD Audio Controller                                            | 2         | 2.04%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.04%   |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 1.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.02%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1         | 1.02%   |
| Kingston Technology HyperX QuadCast S                                      | 1         | 1.02%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.02%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.02%   |
| GN Netcom Jabra Link 380                                                   | 1         | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.02%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.02%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.02%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 44.44%  |
| SK hynix            | 6         | 33.33%  |
| Unknown             | 2         | 11.11%  |
| Elpida              | 1         | 5.56%   |
| ASint Technology    | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s    | 3         | 15.79%  |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 10.53%  |
| Unknown                                                   | 2         | 10.53%  |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 5.26%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 1         | 5.26%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 5.26%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 5.26%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 5.26%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 5.26%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 1         | 5.26%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s    | 1         | 5.26%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s    | 1         | 5.26%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s    | 1         | 5.26%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM 1067MT/s          | 1         | 5.26%   |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s        | 1         | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 11        | 68.75%  |
| DDR3   | 4         | 25%     |
| LPDDR5 | 1         | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 15        | 93.75%  |
| Row Of Chips | 1         | 6.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 6         | 33.33%  |
| 16384 | 4         | 22.22%  |
| 32768 | 3         | 16.67%  |
| 2048  | 3         | 16.67%  |
| 4096  | 2         | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 8         | 50%     |
| 1600  | 3         | 18.75%  |
| 2667  | 2         | 12.5%   |
| 8400  | 1         | 6.25%   |
| 6400  | 1         | 6.25%   |
| 1067  | 1         | 6.25%   |

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
| Chicony Electronics           | 27        | 52.94%  |
| Bison Electronics             | 7         | 13.73%  |
| Microdia                      | 3         | 5.88%   |
| Suyin                         | 2         | 3.92%   |
| Sunplus Innovation Technology | 2         | 3.92%   |
| IMC Networks                  | 2         | 3.92%   |
| Apple                         | 2         | 3.92%   |
| Ricoh                         | 1         | 1.96%   |
| Realtek Semiconductor         | 1         | 1.96%   |
| Luxvisions Innotech Limited   | 1         | 1.96%   |
| Generalplus Technology        | 1         | 1.96%   |
| Alpha Imaging Technology      | 1         | 1.96%   |
| Acer                          | 1         | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated IR Camera                         | 6         | 11.76%  |
| Chicony USB2.0 Camera                                | 5         | 9.8%    |
| Chicony FHD Webcam                                   | 4         | 7.84%   |
| Chicony HD Webcam                                    | 3         | 5.88%   |
| IMC Networks Integrated Camera                       | 2         | 3.92%   |
| Chicony Integrated Camera                            | 2         | 3.92%   |
| Bison HD Webcam                                      | 2         | 3.92%   |
| Bison BisonCam,NB Pro                                | 2         | 3.92%   |
| Apple FaceTime HD Camera                             | 2         | 3.92%   |
| Suyin RGBIR Camera                                   | 1         | 1.96%   |
| Suyin HP TrueVision HD                               | 1         | 1.96%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.96%   |
| Sunplus Asus Webcam                                  | 1         | 1.96%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 1.96%   |
| Realtek Integrated Webcam                            | 1         | 1.96%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 1.96%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.96%   |
| Microdia Integrated_Webcam_FHD                       | 1         | 1.96%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.96%   |
| Generalplus WEB CAM                                  | 1         | 1.96%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 1.96%   |
| Chicony USB 2.0 Camera                               | 1         | 1.96%   |
| Chicony HP TrueVision HD Camera                      | 1         | 1.96%   |
| Chicony HP Truevision HD                             | 1         | 1.96%   |
| Chicony FJ Camera                                    | 1         | 1.96%   |
| Chicony ACER FHD User Facing                         | 1         | 1.96%   |
| Chicony 1.3M Webcam                                  | 1         | 1.96%   |
| Bison SunplusIT Integrated Camera                    | 1         | 1.96%   |
| Bison Lenovo Integrated Webcam                       | 1         | 1.96%   |
| Bison Lenovo EasyCamera                              | 1         | 1.96%   |
| Alpha Imaging Integrated_Webcam_8M                   | 1         | 1.96%   |
| Acer Lenovo EasyCamera                               | 1         | 1.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 6         | 54.55%  |
| Validity Sensors      | 4         | 36.36%  |
| LighTuning Technology | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 18.18%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors VFS491                           | 1         | 9.09%   |
| Validity Sensors VFS Fingerprint sensor           | 1         | 9.09%   |
| Validity Sensors Fingerprint scanner              | 1         | 9.09%   |
| Synaptics WBDI                                    | 1         | 9.09%   |
| Synaptics UWP WBDI                                | 1         | 9.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader  | 1         | 9.09%   |
| LighTuning Fingerprint Reader                     | 1         | 9.09%   |
| Unknown                                           | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 66.67%  |
| Alcor Micro | 2         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 2         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 33        | 52.38%  |
| 1     | 28        | 44.44%  |
| 3     | 1         | 1.59%   |
| 2     | 1         | 1.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 32.35%  |
| Multimedia controller | 9         | 26.47%  |
| Chipcard              | 6         | 17.65%  |
| Graphics card         | 5         | 14.71%  |
| Net/wireless          | 2         | 5.88%   |
| Modem                 | 1         | 2.94%   |

