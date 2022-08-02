MX 21 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

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

Total: 84

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3190               | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Dell          | Vostro 3550                 | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Acer          | Aspire 5520                 | [d49c27a24a](https://linux-hardware.org/?probe=d49c27a24a) | Jul 29, 2022 |
| Apple         | MacBookAir7,2               | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3190               | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| Dell          | Latitude 3190               | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| Apple         | MacBookAir7,2               | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| Dell          | Latitude 3190               | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| Acer          | Swift SF314-59              | [56424874b7](https://linux-hardware.org/?probe=56424874b7) | Jul 11, 2022 |
| Alienware     | 13 R2                       | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Dell          | Latitude 3190               | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| Dell          | Latitude 3190               | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| Dell          | Latitude 3190               | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Dell          | Latitude D520               | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| Sony          | VPCSB1V9R                   | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| Acer          | Aspire A515-56              | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Acer          | Nitro AN515-55              | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| HP            | ProBook 450 G4              | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Gigabyte      | G5 KC                       | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| ASUSTek       | 1101HA                      | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| TUXEDO        | N7x0WU                      | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Dell          | Latitude 3190               | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| Sony          | SVE1513Q1ESI                | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| ASUSTek       | X550CC                      | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| Lenovo        | B590 20208                  | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| ASUSTek       | E402MA                      | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.10.0-9-amd64            | 14        | 20%     |
| 5.10.0-13-amd64           | 10        | 14.29%  |
| 5.14.0-4mx-amd64          | 8         | 11.43%  |
| 5.10.0-14-amd64           | 6         | 8.57%   |
| 5.10.0-11-amd64           | 6         | 8.57%   |
| 5.16.0-5mx-amd64          | 4         | 5.71%   |
| 5.10.0-16-amd64           | 3         | 4.29%   |
| 5.16.0-6mx-amd64          | 2         | 2.86%   |
| 5.10.0-8-amd64            | 2         | 2.86%   |
| 5.10.0-15-amd64           | 2         | 2.86%   |
| 5.10.0-13-686-pae         | 2         | 2.86%   |
| 5.10.0-11-686-pae         | 2         | 2.86%   |
| 5.10.0-10-amd64           | 2         | 2.86%   |
| 5.17.0-5.2-liquorix-amd64 | 1         | 1.43%   |
| 5.17.0-1-amd64            | 1         | 1.43%   |
| 5.16.0-4mx-amd64          | 1         | 1.43%   |
| 5.15.0-3mx-amd64          | 1         | 1.43%   |
| 5.10.0-5mx-amd64          | 1         | 1.43%   |
| 5.10.0-12-amd64           | 1         | 1.43%   |
| 5.10.0-11-686             | 1         | 1.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 48        | 72.73%  |
| 5.14.0  | 8         | 12.12%  |
| 5.16.0  | 7         | 10.61%  |
| 5.17.0  | 2         | 3.03%   |
| 5.15.0  | 1         | 1.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 48        | 72.73%  |
| 5.14    | 8         | 12.12%  |
| 5.16    | 7         | 10.61%  |
| 5.17    | 2         | 3.03%   |
| 5.15    | 1         | 1.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 59        | 93.65%  |
| i686   | 4         | 6.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 43        | 68.25%  |
| KDE5    | 16        | 25.4%   |
| GNOME   | 2         | 3.17%   |
| Budgie  | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 61        | 96.83%  |
| Tty  | 2         | 3.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 47        | 74.6%   |
| SDDM    | 15        | 23.81%  |
| Unknown | 1         | 1.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 34        | 53.97%  |
| de_DE   | 9         | 14.29%  |
| ru_RU   | 3         | 4.76%   |
| it_IT   | 3         | 4.76%   |
| Unknown | 3         | 4.76%   |
| pt_BR   | 2         | 3.17%   |
| en_GB   | 2         | 3.17%   |
| sk_SK   | 1         | 1.59%   |
| fr_FR   | 1         | 1.59%   |
| fi_FI   | 1         | 1.59%   |
| es_PE   | 1         | 1.59%   |
| es_ES   | 1         | 1.59%   |
| en_AU   | 1         | 1.59%   |
| de_CH   | 1         | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 47        | 74.6%   |
| BIOS | 16        | 25.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 53        | 84.13%  |
| Overlay | 7         | 11.11%  |
| Btrfs   | 2         | 3.17%   |
| F2fs    | 1         | 1.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 48        | 76.19%  |
| MBR  | 15        | 23.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 71.43%  |
| Yes       | 18        | 28.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 53.13%  |
| No        | 30        | 46.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 12        | 19.05%  |
| ASUSTek Computer    | 9         | 14.29%  |
| Hewlett-Packard     | 7         | 11.11%  |
| Dell                | 6         | 9.52%   |
| Sony                | 5         | 7.94%   |
| Acer                | 4         | 6.35%   |
| Alienware           | 3         | 4.76%   |
| Samsung Electronics | 2         | 3.17%   |
| MSI                 | 2         | 3.17%   |
| Gigabyte Technology | 2         | 3.17%   |
| Fujitsu Siemens     | 2         | 3.17%   |
| Apple               | 2         | 3.17%   |
| TUXEDO              | 1         | 1.59%   |
| Toshiba             | 1         | 1.59%   |
| Medion              | 1         | 1.59%   |
| Framework           | 1         | 1.59%   |
| efirstview          | 1         | 1.59%   |
| Chuwi               | 1         | 1.59%   |
| Unknown             | 1         | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 2         | 3.17%   |
| TUXEDO N7x0WU                             | 1         | 1.59%   |
| Toshiba Satellite C845                    | 1         | 1.59%   |
| Sony VPCSB1V9R                            | 1         | 1.59%   |
| Sony VPCF119FX                            | 1         | 1.59%   |
| Sony VPCEH2N1E                            | 1         | 1.59%   |
| Sony VPCEC3S1E                            | 1         | 1.59%   |
| Sony SVE1513Q1ESI                         | 1         | 1.59%   |
| Samsung 350V5C/351V5C/3540VC/3440VC       | 1         | 1.59%   |
| Samsung 340XAA/350XAA/550XAA              | 1         | 1.59%   |
| MSI GV62 8RD                              | 1         | 1.59%   |
| MSI Alpha 15 B5EEK                        | 1         | 1.59%   |
| Medion E14304                             | 1         | 1.59%   |
| Lenovo ThinkPad W541 20EG0005MS           | 1         | 1.59%   |
| Lenovo ThinkPad T440p 20AW002VBR          | 1         | 1.59%   |
| Lenovo ThinkPad T430 23427YU              | 1         | 1.59%   |
| Lenovo ThinkPad E15 Gen 3 20YG008CUS      | 1         | 1.59%   |
| Lenovo ThinkBook 13s-IWL 20R9             | 1         | 1.59%   |
| Lenovo S130-11IGM 81J1                    | 1         | 1.59%   |
| Lenovo Legion 5 15ACH6H 82JU              | 1         | 1.59%   |
| Lenovo IdeaPad Y700-15ISK 80NV            | 1         | 1.59%   |
| Lenovo IdeaPad 3 15IIL05 81WE             | 1         | 1.59%   |
| Lenovo G400s VILG1                        | 1         | 1.59%   |
| Lenovo B590 20208                         | 1         | 1.59%   |
| HP Stream Laptop 14-cb0XX                 | 1         | 1.59%   |
| HP ProBook 450 G4                         | 1         | 1.59%   |
| HP ProBook 450 G1                         | 1         | 1.59%   |
| HP EliteBook 850 G3                       | 1         | 1.59%   |
| HP EliteBook 8440p                        | 1         | 1.59%   |
| HP EliteBook 840 G3                       | 1         | 1.59%   |
| HP Compaq Presario CQ60                   | 1         | 1.59%   |
| Gigabyte P15FV5                           | 1         | 1.59%   |
| Gigabyte G5 KC                            | 1         | 1.59%   |
| Fujitsu Siemens LIFEBOOK E8010            | 1         | 1.59%   |
| Fujitsu Siemens ESPRIMO Mobile D9500      | 1         | 1.59%   |
| Framework Laptop                          | 1         | 1.59%   |
| efirstview v01099                         | 1         | 1.59%   |
| Dell XPS 17 9710                          | 1         | 1.59%   |
| Dell Vostro 3550                          | 1         | 1.59%   |
| Dell Latitude E4310                       | 1         | 1.59%   |
| Dell Latitude D520                        | 1         | 1.59%   |
| Dell Latitude 3190                        | 1         | 1.59%   |
| Dell Inspiron 15-3552                     | 1         | 1.59%   |
| Chuwi GemiBook Pro                        | 1         | 1.59%   |
| ASUS X550CC                               | 1         | 1.59%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 1         | 1.59%   |
| ASUS ROG Strix G712LU_G712LU              | 1         | 1.59%   |
| ASUS ROG Strix G513QC_G513QC              | 1         | 1.59%   |
| ASUS N53SN                                | 1         | 1.59%   |
| ASUS K55A                                 | 1         | 1.59%   |
| ASUS E402MA                               | 1         | 1.59%   |
| ASUS ASUS TUF Gaming A15 FA506QE_TUF506QE | 1         | 1.59%   |
| ASUS 1101HA                               | 1         | 1.59%   |
| Apple MacBookAir7,2                       | 1         | 1.59%   |
| Apple MacBook3,1                          | 1         | 1.59%   |
| Alienware m15 R7                          | 1         | 1.59%   |
| Alienware m15                             | 1         | 1.59%   |
| Alienware 13 R2                           | 1         | 1.59%   |
| Acer Swift SF314-59                       | 1         | 1.59%   |
| Acer Nitro AN515-55                       | 1         | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 6.35%   |
| HP EliteBook             | 3         | 4.76%   |
| Dell Latitude            | 3         | 4.76%   |
| Lenovo IdeaPad           | 2         | 3.17%   |
| HP ProBook               | 2         | 3.17%   |
| ASUS ROG                 | 2         | 3.17%   |
| Alienware m15            | 2         | 3.17%   |
| Acer Aspire              | 2         | 3.17%   |
| Unknown                  | 2         | 3.17%   |
| TUXEDO N7x0WU            | 1         | 1.59%   |
| Toshiba Satellite        | 1         | 1.59%   |
| Sony VPCSB1V9R           | 1         | 1.59%   |
| Sony VPCF119FX           | 1         | 1.59%   |
| Sony VPCEH2N1E           | 1         | 1.59%   |
| Sony VPCEC3S1E           | 1         | 1.59%   |
| Sony SVE1513Q1ESI        | 1         | 1.59%   |
| Samsung 350V5C           | 1         | 1.59%   |
| Samsung 340XAA           | 1         | 1.59%   |
| MSI GV62                 | 1         | 1.59%   |
| MSI Alpha                | 1         | 1.59%   |
| Medion E14304            | 1         | 1.59%   |
| Lenovo ThinkBook         | 1         | 1.59%   |
| Lenovo S130-11IGM        | 1         | 1.59%   |
| Lenovo Legion            | 1         | 1.59%   |
| Lenovo G400s             | 1         | 1.59%   |
| Lenovo B590              | 1         | 1.59%   |
| HP Stream                | 1         | 1.59%   |
| HP Compaq                | 1         | 1.59%   |
| Gigabyte P15FV5          | 1         | 1.59%   |
| Gigabyte G5              | 1         | 1.59%   |
| Fujitsu Siemens LIFEBOOK | 1         | 1.59%   |
| Fujitsu Siemens ESPRIMO  | 1         | 1.59%   |
| Framework Laptop         | 1         | 1.59%   |
| efirstview v01099        | 1         | 1.59%   |
| Dell XPS                 | 1         | 1.59%   |
| Dell Vostro              | 1         | 1.59%   |
| Dell Inspiron            | 1         | 1.59%   |
| Chuwi GemiBook           | 1         | 1.59%   |
| ASUS X550CC              | 1         | 1.59%   |
| ASUS TUF                 | 1         | 1.59%   |
| ASUS N53SN               | 1         | 1.59%   |
| ASUS K55A                | 1         | 1.59%   |
| ASUS E402MA              | 1         | 1.59%   |
| ASUS ASUS                | 1         | 1.59%   |
| ASUS 1101HA              | 1         | 1.59%   |
| Apple MacBookAir7        | 1         | 1.59%   |
| Apple MacBook3           | 1         | 1.59%   |
| Alienware 13             | 1         | 1.59%   |
| Acer Swift               | 1         | 1.59%   |
| Acer Nitro               | 1         | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 11        | 17.46%  |
| 2015    | 7         | 11.11%  |
| 2020    | 5         | 7.94%   |
| 2013    | 5         | 7.94%   |
| 2018    | 4         | 6.35%   |
| 2016    | 4         | 6.35%   |
| 2012    | 4         | 6.35%   |
| 2011    | 4         | 6.35%   |
| 2010    | 4         | 6.35%   |
| 2019    | 3         | 4.76%   |
| 2022    | 2         | 3.17%   |
| 2008    | 2         | 3.17%   |
| 2007    | 2         | 3.17%   |
| 2017    | 1         | 1.59%   |
| 2014    | 1         | 1.59%   |
| 2009    | 1         | 1.59%   |
| 2006    | 1         | 1.59%   |
| 2005    | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

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
| 4.01-8.0    | 21        | 33.33%  |
| 16.01-24.0  | 12        | 19.05%  |
| 8.01-16.0   | 12        | 19.05%  |
| 3.01-4.0    | 10        | 15.87%  |
| 2.01-3.0    | 3         | 4.76%   |
| 32.01-64.0  | 1         | 1.59%   |
| 24.01-32.0  | 1         | 1.59%   |
| 64.01-256.0 | 1         | 1.59%   |
| 1.01-2.0    | 1         | 1.59%   |
| 0.51-1.0    | 1         | 1.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 23        | 33.82%  |
| 2.01-3.0  | 21        | 30.88%  |
| 3.01-4.0  | 10        | 14.71%  |
| 4.01-8.0  | 7         | 10.29%  |
| 0.51-1.0  | 5         | 7.35%   |
| 8.01-16.0 | 2         | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 60.94%  |
| 2      | 17        | 26.56%  |
| 3      | 6         | 9.38%   |
| 4      | 1         | 1.56%   |
| 0      | 1         | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 43        | 68.25%  |
| Yes       | 20        | 31.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 77.78%  |
| No        | 14        | 22.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 95.24%  |
| No        | 3         | 4.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 77.78%  |
| No        | 14        | 22.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 16        | 25%     |
| Germany     | 8         | 12.5%   |
| Canada      | 6         | 9.38%   |
| Italy       | 5         | 7.81%   |
| Brazil      | 4         | 6.25%   |
| Serbia      | 2         | 3.13%   |
| Russia      | 2         | 3.13%   |
| Netherlands | 2         | 3.13%   |
| Belgium     | 2         | 3.13%   |
| Austria     | 2         | 3.13%   |
| UK          | 1         | 1.56%   |
| Switzerland | 1         | 1.56%   |
| Spain       | 1         | 1.56%   |
| Slovakia    | 1         | 1.56%   |
| Romania     | 1         | 1.56%   |
| Poland      | 1         | 1.56%   |
| Peru        | 1         | 1.56%   |
| Malaysia    | 1         | 1.56%   |
| India       | 1         | 1.56%   |
| France      | 1         | 1.56%   |
| Finland     | 1         | 1.56%   |
| Czechia     | 1         | 1.56%   |
| Belarus     | 1         | 1.56%   |
| Azerbaijan  | 1         | 1.56%   |
| Australia   | 1         | 1.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Vienna                    | 2         | 3.03%   |
| Orange                    | 2         | 3.03%   |
| Montreal                  | 2         | 3.03%   |
| Doesburg                  | 2         | 3.03%   |
| Zurich                    | 1         | 1.52%   |
| Waycross                  | 1         | 1.52%   |
| Warsaw                    | 1         | 1.52%   |
| Vasco da Gama             | 1         | 1.52%   |
| Vancouver                 | 1         | 1.52%   |
| Uelzen                    | 1         | 1.52%   |
| Taggia                    | 1         | 1.52%   |
| Tacoma                    | 1         | 1.52%   |
| Sydney                    | 1         | 1.52%   |
| Surprise                  | 1         | 1.52%   |
| St Petersburg             | 1         | 1.52%   |
| Schaarbeek                | 1         | 1.52%   |
| Saskatoon                 | 1         | 1.52%   |
| Saarlouis                 | 1         | 1.52%   |
| Roseville                 | 1         | 1.52%   |
| Rochester                 | 1         | 1.52%   |
| Reinbek                   | 1         | 1.52%   |
| Prague                    | 1         | 1.52%   |
| Powder Springs            | 1         | 1.52%   |
| Postbauer-Heng            | 1         | 1.52%   |
| Portland                  | 1         | 1.52%   |
| Ottawa                    | 1         | 1.52%   |
| Osasco                    | 1         | 1.52%   |
| Obourg                    | 1         | 1.52%   |
| Neumarkt in der Oberpfalz | 1         | 1.52%   |
| Munich                    | 1         | 1.52%   |
| Moscow                    | 1         | 1.52%   |
| Montebelluna              | 1         | 1.52%   |
| Minsk                     | 1         | 1.52%   |
| Mestre                    | 1         | 1.52%   |
| Marion                    | 1         | 1.52%   |
| Lima                      | 1         | 1.52%   |
| Lannion                   | 1         | 1.52%   |
| Lahti                     | 1         | 1.52%   |
| Kitchener                 | 1         | 1.52%   |
| Jagodina                  | 1         | 1.52%   |
| Iasi                      | 1         | 1.52%   |
| Huercal Overa             | 1         | 1.52%   |
| Hamburg                   | 1         | 1.52%   |
| Graniteville              | 1         | 1.52%   |
| Florence                  | 1         | 1.52%   |
| Diss                      | 1         | 1.52%   |
| Diana                     | 1         | 1.52%   |
| Cyberjaya                 | 1         | 1.52%   |
| Curitiba                  | 1         | 1.52%   |
| Corsico                   | 1         | 1.52%   |
| Corona                    | 1         | 1.52%   |
| Cambui                    | 1         | 1.52%   |
| Buffalo                   | 1         | 1.52%   |
| Bratislava                | 1         | 1.52%   |
| Berlin                    | 1         | 1.52%   |
| Benton                    | 1         | 1.52%   |
| Belo Horizonte            | 1         | 1.52%   |
| Belgrade                  | 1         | 1.52%   |
| Bayreuth                  | 1         | 1.52%   |
| Baku                      | 1         | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 12     | 13.33%  |
| Samsung Electronics | 12        | 13     | 13.33%  |
| Seagate             | 10        | 11     | 11.11%  |
| Crucial             | 9         | 16     | 10%     |
| Unknown             | 6         | 7      | 6.67%   |
| SK hynix            | 6         | 7      | 6.67%   |
| Kingston            | 6         | 6      | 6.67%   |
| Transcend           | 3         | 3      | 3.33%   |
| LITEON              | 3         | 3      | 3.33%   |
| Intel               | 3         | 3      | 3.33%   |
| Dogfish             | 3         | 3      | 3.33%   |
| Toshiba             | 2         | 2      | 2.22%   |
| SanDisk             | 2         | 3      | 2.22%   |
| Netac               | 2         | 2      | 2.22%   |
| SPCC                | 1         | 1      | 1.11%   |
| SABRENT             | 1         | 1      | 1.11%   |
| PNY                 | 1         | 1      | 1.11%   |
| Phison              | 1         | 1      | 1.11%   |
| OCZ                 | 1         | 1      | 1.11%   |
| Micron Technology   | 1         | 1      | 1.11%   |
| Gigabyte Technology | 1         | 1      | 1.11%   |
| GeIL                | 1         | 1      | 1.11%   |
| Fujitsu             | 1         | 1      | 1.11%   |
| Apple               | 1         | 2      | 1.11%   |
| Unknown             | 1         | 1      | 1.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD           | 3         | 3.23%   |
| Unknown SD32G  32GB                       | 2         | 2.15%   |
| SK hynix HFM512GDJTNI-82A0A 512GB         | 2         | 2.15%   |
| Samsung SSD 860 EVO 500GB                 | 2         | 2.15%   |
| Dogfish SSD 128GB                         | 2         | 2.15%   |
| Crucial CT240BX500SSD1 240GB              | 2         | 2.15%   |
| Crucial CT120BX500SSD1 120GB              | 2         | 2.15%   |
| WDC WDS500G2B0B-00YS70 500GB SSD          | 1         | 1.08%   |
| WDC WDS100T1X0E-00AFY0 1TB                | 1         | 1.08%   |
| WDC WD5000LPVX-08V0TT5 500GB              | 1         | 1.08%   |
| WDC WD5000LPLX-08ZNTT0 500GB              | 1         | 1.08%   |
| WDC WD5000LPCX-22VHAT0 500GB              | 1         | 1.08%   |
| WDC WD3200BEVT-22ZCT0 320GB               | 1         | 1.08%   |
| WDC WD1600BEVT-60ZCT1 160GB               | 1         | 1.08%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 1.08%   |
| WDC PC SN730 NVMe 1024GB                  | 1         | 1.08%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB        | 1         | 1.08%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 1         | 1.08%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB      | 1         | 1.08%   |
| Unknown SDW32G  32GB                      | 1         | 1.08%   |
| Unknown SD08G  8GB                        | 1         | 1.08%   |
| Unknown ISOCOM  64GB                      | 1         | 1.08%   |
| Unknown DA4064  64GB                      | 1         | 1.08%   |
| Unknown BJTD4R  32GB                      | 1         | 1.08%   |
| Transcend TS256GSSD370S 256GB             | 1         | 1.08%   |
| Transcend TS1GSDOM22V 1GB SSD             | 1         | 1.08%   |
| Transcend TS128GMTS800 128GB SSD          | 1         | 1.08%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 1.08%   |
| Toshiba KBG40ZNT256G MEMORY 256GB         | 1         | 1.08%   |
| SPCC Solid State Disk 128GB               | 1         | 1.08%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 1.08%   |
| SK hynix PC601 NVMe 512GB                 | 1         | 1.08%   |
| SK hynix HFM512GD3JX013N 512GB            | 1         | 1.08%   |
| SK hynix HFM256GDJTNG-8310A 256GB         | 1         | 1.08%   |
| Seagate ST9320421AS 320GB                 | 1         | 1.08%   |
| Seagate ST9160821AS 160GB                 | 1         | 1.08%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 1.08%   |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 1.08%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 1.08%   |
| Seagate ST2000LM003 HN-M201RAD 2TB        | 1         | 1.08%   |
| Seagate ST1000LM048-2E7172 1TB            | 1         | 1.08%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.08%   |
| Seagate ST1000LM014-1EJ164 1TB            | 1         | 1.08%   |
| SanDisk SD8SNAT-256G-1006 256GB SSD       | 1         | 1.08%   |
| SanDisk SD8SN8U-512G-1006 512GB SSD       | 1         | 1.08%   |
| Samsung SSD 980 PRO 1TB                   | 1         | 1.08%   |
| Samsung SSD 970 EVO 1TB                   | 1         | 1.08%   |
| Samsung SSD 960 EVO 250GB                 | 1         | 1.08%   |
| Samsung SSD 860 EVO M.2 250GB             | 1         | 1.08%   |
| Samsung SSD 860 EVO M.2 1TB               | 1         | 1.08%   |
| Samsung SSD 860 EVO 1TB                   | 1         | 1.08%   |
| Samsung SSD 850 EVO 250GB                 | 1         | 1.08%   |
| Samsung SSD 840 PRO Series 256GB          | 1         | 1.08%   |
| Samsung PM9A1 NVMe 512GB                  | 1         | 1.08%   |
| Samsung MZNLN256HMHQ-00000 256GB SSD      | 1         | 1.08%   |
| Samsung HM500JI 500GB                     | 1         | 1.08%   |
| SABRENT Disk 1TB                          | 1         | 1.08%   |
| PNY CS900 500GB SSD                       | 1         | 1.08%   |
| Phison ESR512GTLCG-EAC-4 512GB            | 1         | 1.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 50%     |
| WDC                 | 6         | 6      | 30%     |
| Toshiba             | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| SABRENT             | 1         | 1      | 5%      |
| Fujitsu             | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 8         | 14     | 20%     |
| Samsung Electronics | 7         | 8      | 17.5%   |
| Kingston            | 4         | 4      | 10%     |
| Transcend           | 3         | 3      | 7.5%    |
| LITEON              | 3         | 3      | 7.5%    |
| Dogfish             | 3         | 3      | 7.5%    |
| SanDisk             | 2         | 3      | 5%      |
| Netac               | 2         | 2      | 5%      |
| WDC                 | 1         | 1      | 2.5%    |
| SPCC                | 1         | 1      | 2.5%    |
| PNY                 | 1         | 1      | 2.5%    |
| OCZ                 | 1         | 1      | 2.5%    |
| Intel               | 1         | 1      | 2.5%    |
| Gigabyte Technology | 1         | 1      | 2.5%    |
| GeIL                | 1         | 1      | 2.5%    |
| Apple               | 1         | 2      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 32        | 49     | 41.03%  |
| HDD  | 20        | 21     | 25.64%  |
| NVMe | 19        | 25     | 24.36%  |
| MMC  | 7         | 8      | 8.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 69     | 61.43%  |
| NVMe | 19        | 25     | 27.14%  |
| MMC  | 7         | 8      | 10%     |
| SAS  | 1         | 1      | 1.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 47     | 68.63%  |
| 0.51-1.0   | 14        | 21     | 27.45%  |
| 1.01-2.0   | 2         | 2      | 3.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 18        | 27.69%  |
| 251-500        | 13        | 20%     |
| 501-1000       | 11        | 16.92%  |
| 21-50          | 7         | 10.77%  |
| 51-100         | 5         | 7.69%   |
| 1-20           | 4         | 6.15%   |
| 1001-2000      | 3         | 4.62%   |
| More than 3000 | 2         | 3.08%   |
| 2001-3000      | 2         | 3.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 28        | 41.79%  |
| 21-50          | 14        | 20.9%   |
| 101-250        | 7         | 10.45%  |
| 251-500        | 6         | 8.96%   |
| 51-100         | 6         | 8.96%   |
| 501-1000       | 3         | 4.48%   |
| 1001-2000      | 2         | 2.99%   |
| More than 3000 | 1         | 1.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 20%     |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 20%     |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 20%     |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 20%     |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 60%     |
| WDC                 | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 75%     |
| WDC     | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 80%     |
| SSD  | 1         | 1      | 20%     |

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
| Works    | 56        | 89     | 81.16%  |
| Detected | 8         | 9      | 11.59%  |
| Malfunc  | 5         | 5      | 7.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 47        | 63.51%  |
| SK hynix                    | 6         | 8.11%   |
| SanDisk                     | 5         | 6.76%   |
| Samsung Electronics         | 5         | 6.76%   |
| Nvidia                      | 2         | 2.7%    |
| Kingston Technology Company | 2         | 2.7%    |
| AMD                         | 2         | 2.7%    |
| Silicon Image               | 1         | 1.35%   |
| Phison Electronics          | 1         | 1.35%   |
| Micron/Crucial Technology   | 1         | 1.35%   |
| Micron Technology           | 1         | 1.35%   |
| KIOXIA                      | 1         | 1.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 8         | 10%     |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 5         | 6.25%   |
| SK hynix BC511                                                                         | 3         | 3.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 3.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 3.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 3.75%   |
| SanDisk Non-Volatile memory controller                                                 | 2         | 2.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 2.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 2.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 2.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 2.5%    |
| AMD FCH SATA Controller [AHCI mode]                                                    | 2         | 2.5%    |
| SK hynix Non-Volatile memory controller                                                | 1         | 1.25%   |
| SK hynix Gold P31 SSD                                                                  | 1         | 1.25%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 1.25%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                   | 1         | 1.25%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                             | 1         | 1.25%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 1         | 1.25%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.25%   |
| Samsung Electronics SATA controller                                                    | 1         | 1.25%   |
| Phison E12 NVMe Controller                                                             | 1         | 1.25%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                           | 1         | 1.25%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                       | 1         | 1.25%   |
| Nvidia MCP67 IDE Controller                                                            | 1         | 1.25%   |
| Nvidia MCP67 AHCI Controller                                                           | 1         | 1.25%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 1.25%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.25%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 1.25%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 1.25%   |
| Kingston Company KC2000 NVMe SSD                                                       | 1         | 1.25%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 1         | 1.25%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 1.25%   |
| Intel SSD 660P Series                                                                  | 1         | 1.25%   |
| Intel Non-Volatile memory controller                                                   | 1         | 1.25%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 1.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.25%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 1         | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 41        | 56.16%  |
| NVMe | 19        | 26.03%  |
| IDE  | 8         | 10.96%  |
| RAID | 5         | 6.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 53        | 84.13%  |
| AMD    | 10        | 15.87%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 4.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.17%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 3.17%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 3.17%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 3.17%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 3.17%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 3.17%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 1.59%   |
| Intel Pentium M processor 1.80GHz             | 1         | 1.59%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 1         | 1.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.59%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.59%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 1.59%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.59%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.59%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.59%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.59%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.59%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 1         | 1.59%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1.59%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.59%   |
| Intel Core i5-10500H CPU @ 2.50GHz            | 1         | 1.59%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.59%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.59%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 1.59%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 1.59%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 1.59%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 1.59%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 1.59%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 1.59%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 1.59%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 1         | 1.59%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.59%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 1         | 1.59%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 1.59%   |
| Intel Atom CPU Z3735G @ 1.33GHz               | 1         | 1.59%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 1.59%   |
| Intel 11th Gen Core i9-11980HK @ 2.60GHz      | 1         | 1.59%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.59%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.59%   |
| AMD Turion 64 X2 Mobile Technology TL-58      | 1         | 1.59%   |
| AMD Sempron SI-42                             | 1         | 1.59%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 1.59%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 1.59%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 1.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.59%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 1         | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 15        | 23.81%  |
| Intel Core i5           | 14        | 22.22%  |
| Intel Celeron           | 7         | 11.11%  |
| Other                   | 5         | 7.94%   |
| Intel Core i3           | 5         | 7.94%   |
| AMD Ryzen 7             | 5         | 7.94%   |
| Intel Core 2 Duo        | 2         | 3.17%   |
| Intel Atom              | 2         | 3.17%   |
| Intel Pentium Silver    | 1         | 1.59%   |
| Intel Pentium M         | 1         | 1.59%   |
| Intel Genuine           | 1         | 1.59%   |
| AMD Turion 64 X2 Mobile | 1         | 1.59%   |
| AMD Sempron             | 1         | 1.59%   |
| AMD Ryzen 9             | 1         | 1.59%   |
| AMD Ryzen 5             | 1         | 1.59%   |
| AMD Ryzen 3             | 1         | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 29        | 46.03%  |
| 4      | 20        | 31.75%  |
| 8      | 6         | 9.52%   |
| 6      | 4         | 6.35%   |
| 1      | 3         | 4.76%   |
| 14     | 1         | 1.59%   |

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
| 2      | 47        | 74.6%   |
| 1      | 16        | 25.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 60        | 95.24%  |
| 32-bit         | 3         | 4.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 10.94%  |
| 0x206a7    | 6         | 9.38%   |
| 0x306a9    | 5         | 7.81%   |
| 0xa0652    | 3         | 4.69%   |
| 0x406e3    | 3         | 4.69%   |
| 0x306c3    | 3         | 4.69%   |
| 0x0a50000c | 3         | 4.69%   |
| 0x906ea    | 2         | 3.13%   |
| 0x806ea    | 2         | 3.13%   |
| 0x806c1    | 2         | 3.13%   |
| 0x706a1    | 2         | 3.13%   |
| 0x506e3    | 2         | 3.13%   |
| 0x406c4    | 2         | 3.13%   |
| 0x30678    | 2         | 3.13%   |
| 0x20655    | 2         | 3.13%   |
| 0x906a3    | 1         | 1.56%   |
| 0x806eb    | 1         | 1.56%   |
| 0x806e9    | 1         | 1.56%   |
| 0x806d1    | 1         | 1.56%   |
| 0x706a8    | 1         | 1.56%   |
| 0x6fd      | 1         | 1.56%   |
| 0x6fb      | 1         | 1.56%   |
| 0x6e8      | 1         | 1.56%   |
| 0x6d6      | 1         | 1.56%   |
| 0x506c9    | 1         | 1.56%   |
| 0x106e5    | 1         | 1.56%   |
| 0x106c2    | 1         | 1.56%   |
| 0x0a50000b | 1         | 1.56%   |
| 0x08608103 | 1         | 1.56%   |
| 0x08600106 | 1         | 1.56%   |
| 0x08108109 | 1         | 1.56%   |
| 0x08108102 | 1         | 1.56%   |
| 0x02000057 | 1         | 1.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 7         | 11.11%  |
| KabyLake         | 6         | 9.52%   |
| Skylake          | 5         | 7.94%   |
| IvyBridge        | 5         | 7.94%   |
| Zen 3            | 4         | 6.35%   |
| Silvermont       | 4         | 6.35%   |
| Westmere         | 3         | 4.76%   |
| TigerLake        | 3         | 4.76%   |
| Haswell          | 3         | 4.76%   |
| Goldmont plus    | 3         | 4.76%   |
| CometLake        | 3         | 4.76%   |
| Zen+             | 2         | 3.17%   |
| P6               | 2         | 3.17%   |
| Icelake          | 2         | 3.17%   |
| Core             | 2         | 3.17%   |
| Zen 2            | 1         | 1.59%   |
| Nehalem          | 1         | 1.59%   |
| K8 Hammer        | 1         | 1.59%   |
| K8 & K10 hybrid  | 1         | 1.59%   |
| Goldmont         | 1         | 1.59%   |
| Broadwell        | 1         | 1.59%   |
| Bonnell          | 1         | 1.59%   |
| Alderlake Hybrid | 1         | 1.59%   |
| Unknown          | 1         | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 50        | 60.24%  |
| Nvidia | 21        | 25.3%   |
| AMD    | 12        | 14.46%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 8.05%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 5.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 3.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 3.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 3.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.45%   |
| AMD Cezanne                                                                              | 3         | 3.45%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 2.3%    |
| Intel UHD Graphics 620                                                                   | 2         | 2.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.3%    |
| Intel HD Graphics 530                                                                    | 2         | 2.3%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.15%   |
| Nvidia TU117M                                                                            | 1         | 1.15%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.15%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 1.15%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.15%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.15%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.15%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 1.15%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.15%   |
| Nvidia GF108M [GeForce GT 550M]                                                          | 1         | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.15%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                              | 1         | 1.15%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 1         | 1.15%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                                 | 1         | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.15%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 1         | 1.15%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.15%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.15%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.15%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.15%   |
| Intel HD Graphics 620                                                                    | 1         | 1.15%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.15%   |
| Intel HD Graphics 500                                                                    | 1         | 1.15%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.15%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 1.15%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 1.15%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.15%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.15%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                            | 1         | 1.15%   |
| AMD Renoir                                                                               | 1         | 1.15%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 1.15%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 1         | 1.15%   |
| AMD Lucienne                                                                             | 1         | 1.15%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 52.38%  |
| Intel + Nvidia | 14        | 22.22%  |
| 1 x AMD        | 5         | 7.94%   |
| 1 x Nvidia     | 4         | 6.35%   |
| Intel + AMD    | 3         | 4.76%   |
| AMD + Nvidia   | 3         | 4.76%   |
| 2 x AMD        | 1         | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 51        | 79.69%  |
| Proprietary | 11        | 17.19%  |
| Unknown     | 2         | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 82.54%  |
| 0.01-0.5   | 5         | 7.94%   |
| 0.51-1.0   | 3         | 4.76%   |
| 7.01-8.0   | 1         | 1.59%   |
| 3.01-4.0   | 1         | 1.59%   |
| 1.01-2.0   | 1         | 1.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 12        | 17.39%  |
| AU Optronics            | 10        | 14.49%  |
| LG Display              | 9         | 13.04%  |
| Samsung Electronics     | 8         | 11.59%  |
| PANDA                   | 4         | 5.8%    |
| BOE                     | 4         | 5.8%    |
| Sharp                   | 3         | 4.35%   |
| Chi Mei Optoelectronics | 3         | 4.35%   |
| Sony                    | 2         | 2.9%    |
| Apple                   | 2         | 2.9%    |
| Ancor Communications    | 2         | 2.9%    |
| Sunplus                 | 1         | 1.45%   |
| Philips                 | 1         | 1.45%   |
| Panasonic               | 1         | 1.45%   |
| LTM                     | 1         | 1.45%   |
| Lenovo                  | 1         | 1.45%   |
| InfoVision              | 1         | 1.45%   |
| Hewlett-Packard         | 1         | 1.45%   |
| Goldstar                | 1         | 1.45%   |
| Dell                    | 1         | 1.45%   |
| CPT                     | 1         | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 2.9%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 2.9%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 2.9%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch | 2         | 2.9%    |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch                 | 1         | 1.45%   |
| Sony LCD Monitor SNY06FA 1600x900 310x170mm 13.9-inch                    | 1         | 1.45%   |
| Sony LCD Monitor MS_0025 1920x1080 340x190mm 15.3-inch                   | 1         | 1.45%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 1.45%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 1.45%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 1.45%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC4650 1400x1050 304x228mm 15.0-inch    | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch  | 1         | 1.45%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 1.45%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 1.45%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                  | 1         | 1.45%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 1         | 1.45%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                 | 1         | 1.45%   |
| LTM LCD_VGA LTM0659 1920x1080 886x498mm 40.0-inch                        | 1         | 1.45%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 1.45%   |
| LG Display LCD Monitor LGD06E2 1920x1080 344x194mm 15.5-inch             | 1         | 1.45%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 1.45%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch             | 1         | 1.45%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD024D 1366x768 294x166mm 13.3-inch              | 1         | 1.45%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 518x324mm 24.1-inch                 | 1         | 1.45%   |
| InfoVision LCD Monitor IVO048E 1366x768 256x144mm 11.6-inch              | 1         | 1.45%   |
| Hewlett-Packard LA2306 HWP294B 1920x1080 509x286mm 23.0-inch             | 1         | 1.45%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 1         | 1.45%   |
| Dell 1907FP DEL4014 1280x1024 376x301mm 19.0-inch                        | 1         | 1.45%   |
| CPT LCD Monitor CPT1C21 1366x768 256x144mm 11.6-inch                     | 1         | 1.45%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch         | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15D6 1920x1080 344x193mm 15.5-inch         | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.45%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 1.45%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 1         | 1.45%   |
| BOE LCD Monitor BOE0714 1920x1080 344x193mm 15.5-inch                    | 1         | 1.45%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 1         | 1.45%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch           | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 1         | 1.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 28        | 43.75%  |
| 1366x768 (WXGA)  | 20        | 31.25%  |
| 3840x2160 (4K)   | 4         | 6.25%   |
| 1600x900 (HD+)   | 2         | 3.13%   |
| 1440x900 (WXGA+) | 2         | 3.13%   |
| 1280x800 (WXGA)  | 2         | 3.13%   |
| 3840x2400        | 1         | 1.56%   |
| 2560x1080        | 1         | 1.56%   |
| 2256x1504        | 1         | 1.56%   |
| 2160x1440        | 1         | 1.56%   |
| 1400x1050        | 1         | 1.56%   |
| 1280x1024 (SXGA) | 1         | 1.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 32        | 46.38%  |
| 13     | 9         | 13.04%  |
| 14     | 6         | 8.7%    |
| 17     | 4         | 5.8%    |
| 11     | 4         | 5.8%    |
| 24     | 3         | 4.35%   |
| 23     | 3         | 4.35%   |
| 19     | 3         | 4.35%   |
| 27     | 2         | 2.9%    |
| 84     | 1         | 1.45%   |
| 40     | 1         | 1.45%   |
| 34     | 1         | 1.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 40        | 57.97%  |
| 201-300     | 10        | 14.49%  |
| 501-600     | 8         | 11.59%  |
| 351-400     | 7         | 10.14%  |
| 801-900     | 1         | 1.45%   |
| 701-800     | 1         | 1.45%   |
| 401-500     | 1         | 1.45%   |
| 1501-2000   | 1         | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 50        | 79.37%  |
| 16/10 | 7         | 11.11%  |
| 5/4   | 2         | 3.17%   |
| 3/2   | 2         | 3.17%   |
| 4/3   | 1         | 1.59%   |
| 21/9  | 1         | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 46.38%  |
| 81-90          | 13        | 18.84%  |
| 201-250        | 5         | 7.25%   |
| 51-60          | 4         | 5.8%    |
| 121-130        | 4         | 5.8%    |
| 151-200        | 3         | 4.35%   |
| 71-80          | 2         | 2.9%    |
| 301-350        | 2         | 2.9%    |
| More than 1000 | 1         | 1.45%   |
| 351-500        | 1         | 1.45%   |
| 251-300        | 1         | 1.45%   |
| 501-1000       | 1         | 1.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 28        | 42.42%  |
| 51-100        | 17        | 25.76%  |
| 101-120       | 14        | 21.21%  |
| 161-240       | 4         | 6.06%   |
| More than 240 | 3         | 4.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 50        | 78.13%  |
| 2     | 10        | 15.63%  |
| 3     | 2         | 3.13%   |
| 0     | 2         | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 33        | 32.67%  |
| Intel                    | 33        | 32.67%  |
| Qualcomm Atheros         | 16        | 15.84%  |
| Marvell Technology Group | 4         | 3.96%   |
| MediaTek                 | 3         | 2.97%   |
| TP-Link                  | 2         | 1.98%   |
| Nvidia                   | 2         | 1.98%   |
| Broadcom Limited         | 2         | 1.98%   |
| Broadcom                 | 2         | 1.98%   |
| Samsung Electronics      | 1         | 0.99%   |
| Ralink Technology        | 1         | 0.99%   |
| Dell                     | 1         | 0.99%   |
| ASUSTek Computer         | 1         | 0.99%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 24        | 20.51%  |
| Intel Wi-Fi 6 AX200                                                            | 5         | 4.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 4         | 3.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 3         | 2.56%   |
| Intel Wireless 8260                                                            | 3         | 2.56%   |
| Intel Wireless 7260                                                            | 3         | 2.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 2         | 1.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 1.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 1.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 1.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 2         | 1.71%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 1.71%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 1.71%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.71%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.71%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 1.71%   |
| Intel Centrino Advanced-N 6200                                                 | 2         | 1.71%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.71%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1         | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 1         | 0.85%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.85%   |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 0.85%   |
| Ralink RT2070 Wireless Adapter                                                 | 1         | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1         | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.85%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.85%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.85%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.85%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.85%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.85%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.85%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.85%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.85%   |
| Intel Wireless 7265                                                            | 1         | 0.85%   |
| Intel Wireless 3165                                                            | 1         | 0.85%   |
| Intel Wireless 3160                                                            | 1         | 0.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 0.85%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1         | 0.85%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 0.85%   |
| Intel Centrino Advanced-N 6235                                                 | 1         | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 0.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 1         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 50.77%  |
| Qualcomm Atheros      | 12        | 18.46%  |
| Realtek Semiconductor | 11        | 16.92%  |
| MediaTek              | 3         | 4.62%   |
| Broadcom Limited      | 2         | 3.08%   |
| TP-Link               | 1         | 1.54%   |
| Ralink Technology     | 1         | 1.54%   |
| Broadcom              | 1         | 1.54%   |
| ASUSTek Computer      | 1         | 1.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 5         | 7.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 6.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 4.62%   |
| Intel Wireless 8260                                                     | 3         | 4.62%   |
| Intel Wireless 7260                                                     | 3         | 4.62%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 3.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 3.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.08%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 3.08%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 3.08%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 3.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.54%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.54%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.54%   |
| Intel Wireless 7265                                                     | 1         | 1.54%   |
| Intel Wireless 3165                                                     | 1         | 1.54%   |
| Intel Wireless 3160                                                     | 1         | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.54%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.54%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.54%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.54%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.54%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 1.54%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 1.54%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 1.54%   |
| ASUS 802.11ac NIC                                                       | 1         | 1.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 28        | 56%     |
| Intel                    | 7         | 14%     |
| Qualcomm Atheros         | 6         | 12%     |
| Marvell Technology Group | 4         | 8%      |
| Nvidia                   | 2         | 4%      |
| TP-Link                  | 1         | 2%      |
| Samsung Electronics      | 1         | 2%      |
| Broadcom                 | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 24        | 47.06%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 3.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 3.92%   |
| Intel Ethernet Connection I219-V                                               | 2         | 3.92%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 3.92%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 3.92%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.96%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 1.96%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 1.96%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.96%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.96%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.96%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.96%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.96%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 1.96%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 1.96%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.96%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.96%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 1.96%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 1.96%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 54.55%  |
| Ethernet | 49        | 44.55%  |
| Modem    | 1         | 0.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 50        | 73.53%  |
| Ethernet | 18        | 26.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 45        | 71.43%  |
| 1     | 16        | 25.4%   |
| 0     | 2         | 3.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 49        | 76.56%  |
| Yes  | 15        | 23.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 48%     |
| Realtek Semiconductor           | 5         | 10%     |
| Qualcomm Atheros Communications | 5         | 10%     |
| IMC Networks                    | 3         | 6%      |
| Foxconn / Hon Hai               | 3         | 6%      |
| Cambridge Silicon Radio         | 3         | 6%      |
| Apple                           | 2         | 4%      |
| Lite-On Technology              | 1         | 2%      |
| Hewlett-Packard                 | 1         | 2%      |
| Dell                            | 1         | 2%      |
| Broadcom                        | 1         | 2%      |
| ASUSTek Computer                | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 10        | 20%     |
| Intel AX200 Bluetooth                                                               | 5         | 10%     |
| Realtek Bluetooth Radio                                                             | 4         | 8%      |
| Intel AX201 Bluetooth                                                               | 4         | 8%      |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 6%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 6%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 6%      |
| IMC Networks Wireless_Device                                                        | 2         | 4%      |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 4%      |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 2%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 2%      |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 2%      |
| Lite-On Wireless_Device                                                             | 1         | 2%      |
| Intel Bluetooth Device                                                              | 1         | 2%      |
| Intel AX210 Bluetooth                                                               | 1         | 2%      |
| IMC Networks Bluetooth Radio                                                        | 1         | 2%      |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 2%      |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 2%      |
| Dell DW375 Bluetooth Module                                                         | 1         | 2%      |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 2%      |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 2%      |
| Apple Bluetooth USB Host Controller                                                 | 1         | 2%      |
| Apple Bluetooth HCI                                                                 | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 63.41%  |
| Nvidia                | 16        | 19.51%  |
| AMD                   | 9         | 10.98%  |
| Texas Instruments     | 1         | 1.22%   |
| Realtek Semiconductor | 1         | 1.22%   |
| Plantronics           | 1         | 1.22%   |
| FIFINE 683 Microphone | 1         | 1.22%   |
| C-Media Electronics   | 1         | 1.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 8.6%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 8.6%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 6.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 5.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 4.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 4.3%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 3.23%   |
| Nvidia Audio device                                                                               | 3         | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 3.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.23%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 3.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 3.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 3.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.15%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.15%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 1.08%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.08%   |
| Plantronics BT600                                                                                 | 1         | 1.08%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.08%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 1.08%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 1.08%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 1.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.08%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.08%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.08%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.08%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.08%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.08%   |
| FIFINE 683 Microphone FIFINE 683 Microphone                                                       | 1         | 1.08%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 1         | 1.08%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 1.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.08%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1         | 1.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 16        | 21.62%  |
| Samsung Electronics | 16        | 21.62%  |
| Unknown             | 13        | 17.57%  |
| Micron Technology   | 7         | 9.46%   |
| Kingston            | 7         | 9.46%   |
| Crucial             | 4         | 5.41%   |
| Unknown (ABCD)      | 2         | 2.7%    |
| Smart               | 2         | 2.7%    |
| Corsair             | 2         | 2.7%    |
| Transcend           | 1         | 1.35%   |
| PNY                 | 1         | 1.35%   |
| Nanya Technology    | 1         | 1.35%   |
| Avant               | 1         | 1.35%   |
| Unknown             | 1         | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 4.82%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 3.61%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 2.41%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 2.41%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 2.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.41%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 2.41%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 2.41%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.41%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 2.41%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.2%    |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 1.2%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.2%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.2%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.2%    |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 1.2%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.2%    |
| Transcend RAM TS128MSQ64V6J 1GB SODIMM DDR 667MT/s               | 1         | 1.2%    |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Smart RAM SF4641G8CK8IEGKSBG 8192MB SODIMM DDR4 2400MT/s         | 1         | 1.2%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 1.2%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT351S6EFR8A 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT351S6AFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 1.2%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.2%    |
| SK hynix RAM HMCG66MEBSA095N 8GB SODIMM DDR5 4800MT/s            | 1         | 1.2%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.2%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.2%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.2%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.2%    |
| SK hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.2%    |
| SK hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 1         | 1.2%    |
| Samsung RAM Module 4GB SODIMM DDR2 667MT/s                       | 1         | 1.2%    |
| Samsung RAM M471B5773EB0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 1.2%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471B1G73DHO-CH9 8GB SODIMM DDR3 1333MT/s            | 1         | 1.2%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s   | 1         | 1.2%    |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.2%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.2%    |
| Samsung RAM K4F8E304HB-MGCj 4GB SODIMM DDR4 2400MT/s             | 1         | 1.2%    |
| PNY RAM Module 8GB SODIMM DDR3 1333MT/s                          | 1         | 1.2%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 1         | 1.2%    |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.2%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.2%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.2%    |
| Micron RAM 4ATF51264HZ-2G6E! 4096MB SODIMM DDR4 2400MT/s         | 1         | 1.2%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 1         | 1.2%    |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.2%    |
| Kingston RAM KHX2400C14S4/8G 8GB Row Of Chips DDR4 2400MT/s      | 1         | 1.2%    |
| Kingston RAM HP594908-HR1-ELD 2GB SODIMM DDR3 1333MT/s           | 1         | 1.2%    |
| Kingston RAM HP16D3LS1KEGR/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 25        | 39.06%  |
| DDR3   | 25        | 39.06%  |
| DDR2   | 5         | 7.81%   |
| LPDDR4 | 4         | 6.25%   |
| DDR    | 2         | 3.13%   |
| SDRAM  | 1         | 1.56%   |
| DRAM   | 1         | 1.56%   |
| DDR5   | 1         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 61        | 95.31%  |
| Row Of Chips | 3         | 4.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 30        | 41.67%  |
| 4096  | 25        | 34.72%  |
| 2048  | 11        | 15.28%  |
| 1024  | 4         | 5.56%   |
| 32768 | 1         | 1.39%   |
| 16384 | 1         | 1.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 13        | 19.7%   |
| 3200    | 12        | 18.18%  |
| 2400    | 7         | 10.61%  |
| Unknown | 7         | 10.61%  |
| 2667    | 6         | 9.09%   |
| 1333    | 6         | 9.09%   |
| 2133    | 4         | 6.06%   |
| 667     | 4         | 6.06%   |
| 1334    | 2         | 3.03%   |
| 4800    | 1         | 1.52%   |
| 4267    | 1         | 1.52%   |
| 4199    | 1         | 1.52%   |
| 1067    | 1         | 1.52%   |
| 166     | 1         | 1.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P2055 series | 1         | 50%     |
| HP LaserJet 1022         | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 12        | 24.49%  |
| Realtek Semiconductor                  | 5         | 10.2%   |
| Microdia                               | 4         | 8.16%   |
| Acer                                   | 4         | 8.16%   |
| Sunplus Innovation Technology          | 3         | 6.12%   |
| IMC Networks                           | 3         | 6.12%   |
| Suyin                                  | 2         | 4.08%   |
| Ricoh                                  | 2         | 4.08%   |
| Quanta                                 | 2         | 4.08%   |
| Lite-On Technology                     | 2         | 4.08%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.08%   |
| Z-Star Microelectronics                | 1         | 2.04%   |
| Y Media                                | 1         | 2.04%   |
| Silicon Motion                         | 1         | 2.04%   |
| Primax Electronics                     | 1         | 2.04%   |
| Luxvisions Innotech Limited            | 1         | 2.04%   |
| Logitech                               | 1         | 2.04%   |
| Goodong Industry                       | 1         | 2.04%   |
| Alcor Micro                            | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                        | 2         | 4.08%   |
| Quanta HD User Facing                               | 2         | 4.08%   |
| Lite-On HP HD Camera                                | 2         | 4.08%   |
| Chicony Integrated Camera                           | 2         | 4.08%   |
| Acer BisonCam, NB Pro                               | 2         | 4.08%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 2.04%   |
| Y Media USB Camera                                  | 1         | 2.04%   |
| Suyin Sony Visual Communication Camera              | 1         | 2.04%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 2.04%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 2.04%   |
| Silicon Motion Web Camera                           | 1         | 2.04%   |
| Ricoh USB2.0 Camera                                 | 1         | 2.04%   |
| Ricoh Integrated Webcam                             | 1         | 2.04%   |
| Realtek USB Camera                                  | 1         | 2.04%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.04%   |
| Realtek Integrated_Webcam_HD                        | 1         | 2.04%   |
| Realtek Integrated Webcam                           | 1         | 2.04%   |
| Realtek EasyCamera                                  | 1         | 2.04%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 2.04%   |
| Microdia WebCam SC-13HDL12639P                      | 1         | 2.04%   |
| Microdia Webcam                                     | 1         | 2.04%   |
| Microdia USB 2.0 Camera                             | 1         | 2.04%   |
| Microdia Amcrest AWC2198 USB Webcam                 | 1         | 2.04%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 2.04%   |
| Logitech StreamCam                                  | 1         | 2.04%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                 | 1         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.04%   |
| IMC Networks Integrated Camera                      | 1         | 2.04%   |
| Goodong Industry USB2.0 HD UVC WebCam               | 1         | 2.04%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 2.04%   |
| Chicony USB 2.0 Camera                              | 1         | 2.04%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 2.04%   |
| Chicony thinkpad t430s camera                       | 1         | 2.04%   |
| Chicony Sony Visual Communication Camera            | 1         | 2.04%   |
| Chicony Lenovo EasyCamera                           | 1         | 2.04%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 2.04%   |
| Chicony HP HD Webcam                                | 1         | 2.04%   |
| Chicony HD User Facing                              | 1         | 2.04%   |
| Chicony 2.0M UVC WebCam                             | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.04%   |
| Alcor Micro USB 2.0 Camera                          | 1         | 2.04%   |
| Acer SunplusIT INC. Integrated Camera               | 1         | 2.04%   |
| Acer BisonCam,NB Pro                                | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 57.14%  |
| Shenzhen Goodix Technology | 2         | 28.57%  |
| AuthenTec                  | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader   | 2         | 28.57%  |
| Validity Sensors VFS 5011 fingerprint sensor | 2         | 28.57%  |
| Shenzhen Goodix  FingerPrint Device          | 2         | 28.57%  |
| AuthenTec AES1660 Fingerprint Sensor         | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 1         | 50%     |
| Advanced Card Systems | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Advanced Card Systems ACR122U                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 44        | 67.69%  |
| 1     | 18        | 27.69%  |
| 2     | 3         | 4.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 13        | 59.09%  |
| Fingerprint reader    | 7         | 31.82%  |
| Multimedia controller | 1         | 4.55%   |
| Chipcard              | 1         | 4.55%   |

