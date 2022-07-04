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

Total: 71

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.10.0-9-amd64            | 14        | 22.22%  |
| 5.10.0-13-amd64           | 10        | 15.87%  |
| 5.14.0-4mx-amd64          | 8         | 12.7%   |
| 5.10.0-11-amd64           | 6         | 9.52%   |
| 5.10.0-14-amd64           | 5         | 7.94%   |
| 5.16.0-6mx-amd64          | 2         | 3.17%   |
| 5.16.0-5mx-amd64          | 2         | 3.17%   |
| 5.10.0-8-amd64            | 2         | 3.17%   |
| 5.10.0-15-amd64           | 2         | 3.17%   |
| 5.10.0-13-686-pae         | 2         | 3.17%   |
| 5.10.0-11-686-pae         | 2         | 3.17%   |
| 5.10.0-10-amd64           | 2         | 3.17%   |
| 5.17.0-5.2-liquorix-amd64 | 1         | 1.59%   |
| 5.17.0-1-amd64            | 1         | 1.59%   |
| 5.16.0-4mx-amd64          | 1         | 1.59%   |
| 5.15.0-3mx-amd64          | 1         | 1.59%   |
| 5.10.0-5mx-amd64          | 1         | 1.59%   |
| 5.10.0-11-686             | 1         | 1.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 45        | 73.77%  |
| 5.14.0  | 8         | 13.11%  |
| 5.16.0  | 5         | 8.2%    |
| 5.17.0  | 2         | 3.28%   |
| 5.15.0  | 1         | 1.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 45        | 73.77%  |
| 5.14    | 8         | 13.11%  |
| 5.16    | 5         | 8.2%    |
| 5.17    | 2         | 3.28%   |
| 5.15    | 1         | 1.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 55        | 93.22%  |
| i686   | 4         | 6.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 40        | 67.8%   |
| KDE5    | 15        | 25.42%  |
| GNOME   | 2         | 3.39%   |
| Budgie  | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 58        | 98.31%  |
| Tty  | 1         | 1.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 43        | 72.88%  |
| SDDM    | 15        | 25.42%  |
| Unknown | 1         | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 31        | 52.54%  |
| de_DE   | 8         | 13.56%  |
| ru_RU   | 3         | 5.08%   |
| it_IT   | 3         | 5.08%   |
| Unknown | 3         | 5.08%   |
| pt_BR   | 2         | 3.39%   |
| en_GB   | 2         | 3.39%   |
| sk_SK   | 1         | 1.69%   |
| fr_FR   | 1         | 1.69%   |
| fi_FI   | 1         | 1.69%   |
| es_PE   | 1         | 1.69%   |
| es_ES   | 1         | 1.69%   |
| en_AU   | 1         | 1.69%   |
| de_CH   | 1         | 1.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 45        | 76.27%  |
| BIOS | 14        | 23.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 50        | 84.75%  |
| Overlay | 6         | 10.17%  |
| Btrfs   | 2         | 3.39%   |
| F2fs    | 1         | 1.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 46        | 77.97%  |
| MBR  | 13        | 22.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 69.49%  |
| Yes       | 18        | 30.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 50.85%  |
| No        | 29        | 49.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 12        | 20.34%  |
| ASUSTek Computer    | 9         | 15.25%  |
| Hewlett-Packard     | 7         | 11.86%  |
| Sony                | 5         | 8.47%   |
| Dell                | 5         | 8.47%   |
| Samsung Electronics | 2         | 3.39%   |
| MSI                 | 2         | 3.39%   |
| Gigabyte Technology | 2         | 3.39%   |
| Fujitsu Siemens     | 2         | 3.39%   |
| Apple               | 2         | 3.39%   |
| Alienware           | 2         | 3.39%   |
| Acer                | 2         | 3.39%   |
| TUXEDO              | 1         | 1.69%   |
| Toshiba             | 1         | 1.69%   |
| Medion              | 1         | 1.69%   |
| Framework           | 1         | 1.69%   |
| efirstview          | 1         | 1.69%   |
| Chuwi               | 1         | 1.69%   |
| Unknown             | 1         | 1.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 2         | 3.39%   |
| TUXEDO N7x0WU                             | 1         | 1.69%   |
| Toshiba Satellite C845                    | 1         | 1.69%   |
| Sony VPCSB1V9R                            | 1         | 1.69%   |
| Sony VPCF119FX                            | 1         | 1.69%   |
| Sony VPCEH2N1E                            | 1         | 1.69%   |
| Sony VPCEC3S1E                            | 1         | 1.69%   |
| Sony SVE1513Q1ESI                         | 1         | 1.69%   |
| Samsung 350V5C/351V5C/3540VC/3440VC       | 1         | 1.69%   |
| Samsung 340XAA/350XAA/550XAA              | 1         | 1.69%   |
| MSI GV62 8RD                              | 1         | 1.69%   |
| MSI Alpha 15 B5EEK                        | 1         | 1.69%   |
| Medion E14304                             | 1         | 1.69%   |
| Lenovo ThinkPad W541 20EG0005MS           | 1         | 1.69%   |
| Lenovo ThinkPad T440p 20AW002VBR          | 1         | 1.69%   |
| Lenovo ThinkPad T430 23427YU              | 1         | 1.69%   |
| Lenovo ThinkPad E15 Gen 3 20YG008CUS      | 1         | 1.69%   |
| Lenovo ThinkBook 13s-IWL 20R9             | 1         | 1.69%   |
| Lenovo S130-11IGM 81J1                    | 1         | 1.69%   |
| Lenovo Legion 5 15ACH6H 82JU              | 1         | 1.69%   |
| Lenovo IdeaPad Y700-15ISK 80NV            | 1         | 1.69%   |
| Lenovo IdeaPad 3 15IIL05 81WE             | 1         | 1.69%   |
| Lenovo G400s VILG1                        | 1         | 1.69%   |
| Lenovo B590 20208                         | 1         | 1.69%   |
| HP Stream Laptop 14-cb0XX                 | 1         | 1.69%   |
| HP ProBook 450 G4                         | 1         | 1.69%   |
| HP ProBook 450 G1                         | 1         | 1.69%   |
| HP EliteBook 850 G3                       | 1         | 1.69%   |
| HP EliteBook 8440p                        | 1         | 1.69%   |
| HP EliteBook 840 G3                       | 1         | 1.69%   |
| HP Compaq Presario CQ60                   | 1         | 1.69%   |
| Gigabyte P15FV5                           | 1         | 1.69%   |
| Gigabyte G5 KC                            | 1         | 1.69%   |
| Fujitsu Siemens LIFEBOOK E8010            | 1         | 1.69%   |
| Fujitsu Siemens ESPRIMO Mobile D9500      | 1         | 1.69%   |
| Framework Laptop                          | 1         | 1.69%   |
| efirstview v01099                         | 1         | 1.69%   |
| Dell XPS 17 9710                          | 1         | 1.69%   |
| Dell Latitude E4310                       | 1         | 1.69%   |
| Dell Latitude D520                        | 1         | 1.69%   |
| Dell Latitude 3190                        | 1         | 1.69%   |
| Dell Inspiron 15-3552                     | 1         | 1.69%   |
| Chuwi GemiBook Pro                        | 1         | 1.69%   |
| ASUS X550CC                               | 1         | 1.69%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 1         | 1.69%   |
| ASUS ROG Strix G712LU_G712LU              | 1         | 1.69%   |
| ASUS ROG Strix G513QC_G513QC              | 1         | 1.69%   |
| ASUS N53SN                                | 1         | 1.69%   |
| ASUS K55A                                 | 1         | 1.69%   |
| ASUS E402MA                               | 1         | 1.69%   |
| ASUS ASUS TUF Gaming A15 FA506QE_TUF506QE | 1         | 1.69%   |
| ASUS 1101HA                               | 1         | 1.69%   |
| Apple MacBookAir7,2                       | 1         | 1.69%   |
| Apple MacBook3,1                          | 1         | 1.69%   |
| Alienware m15 R7                          | 1         | 1.69%   |
| Alienware 13 R2                           | 1         | 1.69%   |
| Acer Nitro AN515-55                       | 1         | 1.69%   |
| Acer Aspire A515-56                       | 1         | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 6.78%   |
| HP EliteBook             | 3         | 5.08%   |
| Dell Latitude            | 3         | 5.08%   |
| Lenovo IdeaPad           | 2         | 3.39%   |
| HP ProBook               | 2         | 3.39%   |
| ASUS ROG                 | 2         | 3.39%   |
| Unknown                  | 2         | 3.39%   |
| TUXEDO N7x0WU            | 1         | 1.69%   |
| Toshiba Satellite        | 1         | 1.69%   |
| Sony VPCSB1V9R           | 1         | 1.69%   |
| Sony VPCF119FX           | 1         | 1.69%   |
| Sony VPCEH2N1E           | 1         | 1.69%   |
| Sony VPCEC3S1E           | 1         | 1.69%   |
| Sony SVE1513Q1ESI        | 1         | 1.69%   |
| Samsung 350V5C           | 1         | 1.69%   |
| Samsung 340XAA           | 1         | 1.69%   |
| MSI GV62                 | 1         | 1.69%   |
| MSI Alpha                | 1         | 1.69%   |
| Medion E14304            | 1         | 1.69%   |
| Lenovo ThinkBook         | 1         | 1.69%   |
| Lenovo S130-11IGM        | 1         | 1.69%   |
| Lenovo Legion            | 1         | 1.69%   |
| Lenovo G400s             | 1         | 1.69%   |
| Lenovo B590              | 1         | 1.69%   |
| HP Stream                | 1         | 1.69%   |
| HP Compaq                | 1         | 1.69%   |
| Gigabyte P15FV5          | 1         | 1.69%   |
| Gigabyte G5              | 1         | 1.69%   |
| Fujitsu Siemens LIFEBOOK | 1         | 1.69%   |
| Fujitsu Siemens ESPRIMO  | 1         | 1.69%   |
| Framework Laptop         | 1         | 1.69%   |
| efirstview v01099        | 1         | 1.69%   |
| Dell XPS                 | 1         | 1.69%   |
| Dell Inspiron            | 1         | 1.69%   |
| Chuwi GemiBook           | 1         | 1.69%   |
| ASUS X550CC              | 1         | 1.69%   |
| ASUS TUF                 | 1         | 1.69%   |
| ASUS N53SN               | 1         | 1.69%   |
| ASUS K55A                | 1         | 1.69%   |
| ASUS E402MA              | 1         | 1.69%   |
| ASUS ASUS                | 1         | 1.69%   |
| ASUS 1101HA              | 1         | 1.69%   |
| Apple MacBookAir7        | 1         | 1.69%   |
| Apple MacBook3           | 1         | 1.69%   |
| Alienware m15            | 1         | 1.69%   |
| Alienware 13             | 1         | 1.69%   |
| Acer Nitro               | 1         | 1.69%   |
| Acer Aspire              | 1         | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 11        | 18.64%  |
| 2015    | 6         | 10.17%  |
| 2016    | 5         | 8.47%   |
| 2013    | 5         | 8.47%   |
| 2020    | 4         | 6.78%   |
| 2012    | 4         | 6.78%   |
| 2010    | 4         | 6.78%   |
| 2019    | 3         | 5.08%   |
| 2018    | 3         | 5.08%   |
| 2011    | 3         | 5.08%   |
| 2022    | 2         | 3.39%   |
| 2008    | 2         | 3.39%   |
| 2017    | 1         | 1.69%   |
| 2014    | 1         | 1.69%   |
| 2009    | 1         | 1.69%   |
| 2007    | 1         | 1.69%   |
| 2006    | 1         | 1.69%   |
| 2005    | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 59        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 59        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 21        | 35.59%  |
| 8.01-16.0   | 12        | 20.34%  |
| 16.01-24.0  | 10        | 16.95%  |
| 3.01-4.0    | 8         | 13.56%  |
| 2.01-3.0    | 3         | 5.08%   |
| 32.01-64.0  | 1         | 1.69%   |
| 24.01-32.0  | 1         | 1.69%   |
| 64.01-256.0 | 1         | 1.69%   |
| 1.01-2.0    | 1         | 1.69%   |
| 0.51-1.0    | 1         | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 21        | 33.87%  |
| 2.01-3.0  | 20        | 32.26%  |
| 3.01-4.0  | 8         | 12.9%   |
| 4.01-8.0  | 7         | 11.29%  |
| 0.51-1.0  | 5         | 8.06%   |
| 8.01-16.0 | 1         | 1.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 62.71%  |
| 2      | 14        | 23.73%  |
| 3      | 6         | 10.17%  |
| 4      | 1         | 1.69%   |
| 0      | 1         | 1.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 69.49%  |
| Yes       | 18        | 30.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 77.97%  |
| No        | 13        | 22.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 94.92%  |
| No        | 3         | 5.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 77.97%  |
| No        | 13        | 22.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 15        | 25.42%  |
| Germany     | 7         | 11.86%  |
| Canada      | 6         | 10.17%  |
| Italy       | 5         | 8.47%   |
| Brazil      | 4         | 6.78%   |
| Serbia      | 2         | 3.39%   |
| Russia      | 2         | 3.39%   |
| Belgium     | 2         | 3.39%   |
| Austria     | 2         | 3.39%   |
| UK          | 1         | 1.69%   |
| Switzerland | 1         | 1.69%   |
| Spain       | 1         | 1.69%   |
| Slovakia    | 1         | 1.69%   |
| Romania     | 1         | 1.69%   |
| Poland      | 1         | 1.69%   |
| Peru        | 1         | 1.69%   |
| Netherlands | 1         | 1.69%   |
| Malaysia    | 1         | 1.69%   |
| France      | 1         | 1.69%   |
| Finland     | 1         | 1.69%   |
| Czechia     | 1         | 1.69%   |
| Belarus     | 1         | 1.69%   |
| Azerbaijan  | 1         | 1.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Vienna                    | 2         | 3.33%   |
| Orange                    | 2         | 3.33%   |
| Montreal                  | 2         | 3.33%   |
| Zurich                    | 1         | 1.67%   |
| Waycross                  | 1         | 1.67%   |
| Warsaw                    | 1         | 1.67%   |
| Vancouver                 | 1         | 1.67%   |
| Uelzen                    | 1         | 1.67%   |
| Taggia                    | 1         | 1.67%   |
| Tacoma                    | 1         | 1.67%   |
| Surprise                  | 1         | 1.67%   |
| St Petersburg             | 1         | 1.67%   |
| Schaarbeek                | 1         | 1.67%   |
| Saskatoon                 | 1         | 1.67%   |
| Saarlouis                 | 1         | 1.67%   |
| Roseville                 | 1         | 1.67%   |
| Rochester                 | 1         | 1.67%   |
| Reinbek                   | 1         | 1.67%   |
| Prague                    | 1         | 1.67%   |
| Powder Springs            | 1         | 1.67%   |
| Postbauer-Heng            | 1         | 1.67%   |
| Portland                  | 1         | 1.67%   |
| Ottawa                    | 1         | 1.67%   |
| Osasco                    | 1         | 1.67%   |
| Obourg                    | 1         | 1.67%   |
| Neumarkt in der Oberpfalz | 1         | 1.67%   |
| Munich                    | 1         | 1.67%   |
| Moscow                    | 1         | 1.67%   |
| Montebelluna              | 1         | 1.67%   |
| Minsk                     | 1         | 1.67%   |
| Mestre                    | 1         | 1.67%   |
| Lima                      | 1         | 1.67%   |
| Lannion                   | 1         | 1.67%   |
| Lahti                     | 1         | 1.67%   |
| Kitchener                 | 1         | 1.67%   |
| Jagodina                  | 1         | 1.67%   |
| Iasi                      | 1         | 1.67%   |
| Huercal Overa             | 1         | 1.67%   |
| Graniteville              | 1         | 1.67%   |
| Florence                  | 1         | 1.67%   |
| Diss                      | 1         | 1.67%   |
| Diana                     | 1         | 1.67%   |
| Cyberjaya                 | 1         | 1.67%   |
| Curitiba                  | 1         | 1.67%   |
| Corsico                   | 1         | 1.67%   |
| Corona                    | 1         | 1.67%   |
| Cambui                    | 1         | 1.67%   |
| Buffalo                   | 1         | 1.67%   |
| Bratislava                | 1         | 1.67%   |
| Berlin                    | 1         | 1.67%   |
| Benton                    | 1         | 1.67%   |
| Belo Horizonte            | 1         | 1.67%   |
| Belgrade                  | 1         | 1.67%   |
| Bayreuth                  | 1         | 1.67%   |
| Baku                      | 1         | 1.67%   |
| Amsterdam                 | 1         | 1.67%   |
| Allen Park                | 1         | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 13     | 14.29%  |
| WDC                 | 11        | 11     | 13.1%   |
| Seagate             | 9         | 10     | 10.71%  |
| Crucial             | 8         | 12     | 9.52%   |
| Unknown             | 6         | 7      | 7.14%   |
| Kingston            | 6         | 6      | 7.14%   |
| SK hynix            | 5         | 6      | 5.95%   |
| Transcend           | 3         | 3      | 3.57%   |
| LITEON              | 3         | 3      | 3.57%   |
| Intel               | 3         | 3      | 3.57%   |
| Dogfish             | 3         | 3      | 3.57%   |
| Toshiba             | 2         | 2      | 2.38%   |
| SanDisk             | 2         | 2      | 2.38%   |
| SPCC                | 1         | 1      | 1.19%   |
| SABRENT             | 1         | 1      | 1.19%   |
| PNY                 | 1         | 1      | 1.19%   |
| Phison              | 1         | 1      | 1.19%   |
| OCZ                 | 1         | 1      | 1.19%   |
| Netac               | 1         | 1      | 1.19%   |
| Gigabyte Technology | 1         | 1      | 1.19%   |
| GeIL                | 1         | 1      | 1.19%   |
| Fujitsu             | 1         | 1      | 1.19%   |
| Apple               | 1         | 1      | 1.19%   |
| Unknown             | 1         | 1      | 1.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD           | 3         | 3.45%   |
| Unknown SD32G  32GB                       | 2         | 2.3%    |
| SK hynix HFM512GDJTNI-82A0A 512GB         | 2         | 2.3%    |
| Samsung SSD 860 EVO 500GB                 | 2         | 2.3%    |
| Dogfish SSD 128GB                         | 2         | 2.3%    |
| Crucial CT240BX500SSD1 240GB              | 2         | 2.3%    |
| WDC WDS500G2B0B-00YS70 500GB SSD          | 1         | 1.15%   |
| WDC WDS100T1X0E-00AFY0 1TB                | 1         | 1.15%   |
| WDC WD5000LPLX-08ZNTT0 500GB              | 1         | 1.15%   |
| WDC WD5000LPCX-22VHAT0 500GB              | 1         | 1.15%   |
| WDC WD3200BEVT-22ZCT0 320GB               | 1         | 1.15%   |
| WDC WD1600BEVT-60ZCT1 160GB               | 1         | 1.15%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 1.15%   |
| WDC PC SN730 NVMe 1024GB                  | 1         | 1.15%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB        | 1         | 1.15%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 1         | 1.15%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB      | 1         | 1.15%   |
| Unknown SDW32G  32GB                      | 1         | 1.15%   |
| Unknown SD08G  8GB                        | 1         | 1.15%   |
| Unknown ISOCOM  64GB                      | 1         | 1.15%   |
| Unknown DA4064  64GB                      | 1         | 1.15%   |
| Unknown BJTD4R  32GB                      | 1         | 1.15%   |
| Transcend TS256GSSD370S 256GB             | 1         | 1.15%   |
| Transcend TS1GSDOM22V 1GB SSD             | 1         | 1.15%   |
| Transcend TS128GMTS800 128GB SSD          | 1         | 1.15%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 1.15%   |
| Toshiba KBG40ZNT256G MEMORY 256GB         | 1         | 1.15%   |
| SPCC Solid State Disk 128GB               | 1         | 1.15%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 1.15%   |
| SK hynix HFM512GD3JX013N 512GB            | 1         | 1.15%   |
| SK hynix HFM256GDJTNG-8310A 256GB         | 1         | 1.15%   |
| Seagate ST9320421AS 320GB                 | 1         | 1.15%   |
| Seagate ST9160821AS 160GB                 | 1         | 1.15%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 1.15%   |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 1.15%   |
| Seagate ST2000LM003 HN-M201RAD 2TB        | 1         | 1.15%   |
| Seagate ST1000LM048-2E7172 1TB            | 1         | 1.15%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 1.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.15%   |
| Seagate ST1000LM014-1EJ164 1TB            | 1         | 1.15%   |
| SanDisk SD8SNAT-256G-1006 256GB SSD       | 1         | 1.15%   |
| SanDisk SD8SN8U-512G-1006 512GB SSD       | 1         | 1.15%   |
| Samsung SSD 980 PRO 1TB                   | 1         | 1.15%   |
| Samsung SSD 970 EVO 1TB                   | 1         | 1.15%   |
| Samsung SSD 960 EVO 250GB                 | 1         | 1.15%   |
| Samsung SSD 860 EVO M.2 250GB             | 1         | 1.15%   |
| Samsung SSD 860 EVO M.2 1TB               | 1         | 1.15%   |
| Samsung SSD 860 EVO 1TB                   | 1         | 1.15%   |
| Samsung SSD 850 EVO 250GB                 | 1         | 1.15%   |
| Samsung SSD 840 PRO Series 256GB          | 1         | 1.15%   |
| Samsung PM9A1 NVMe 512GB                  | 1         | 1.15%   |
| Samsung MZNLN256HMHQ-00000 256GB SSD      | 1         | 1.15%   |
| Samsung HM500JI 500GB                     | 1         | 1.15%   |
| SABRENT Disk 1TB                          | 1         | 1.15%   |
| PNY CS900 500GB SSD                       | 1         | 1.15%   |
| Phison ESR512GTLCG-EAC-4 512GB            | 1         | 1.15%   |
| OCZ VECTOR 256GB SSD                      | 1         | 1.15%   |
| Netac SSD 256GB                           | 1         | 1.15%   |
| LITEON IT LST-16S9G 16GB SSD              | 1         | 1.15%   |
| LITEON CV1-8B512-HP 512GB SSD             | 1         | 1.15%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 52.94%  |
| WDC                 | 5         | 5      | 29.41%  |
| Toshiba             | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| Fujitsu             | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 18.42%  |
| Crucial             | 7         | 10     | 18.42%  |
| Kingston            | 4         | 4      | 10.53%  |
| Transcend           | 3         | 3      | 7.89%   |
| LITEON              | 3         | 3      | 7.89%   |
| Dogfish             | 3         | 3      | 7.89%   |
| SanDisk             | 2         | 2      | 5.26%   |
| WDC                 | 1         | 1      | 2.63%   |
| SPCC                | 1         | 1      | 2.63%   |
| PNY                 | 1         | 1      | 2.63%   |
| OCZ                 | 1         | 1      | 2.63%   |
| Netac               | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| Gigabyte Technology | 1         | 1      | 2.63%   |
| GeIL                | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 31        | 42     | 43.06%  |
| NVMe | 17        | 24     | 23.61%  |
| HDD  | 17        | 18     | 23.61%  |
| MMC  | 7         | 8      | 9.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 40        | 60     | 61.54%  |
| NVMe | 17        | 23     | 26.15%  |
| MMC  | 7         | 8      | 10.77%  |
| SAS  | 1         | 1      | 1.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 42     | 70.21%  |
| 0.51-1.0   | 13        | 17     | 27.66%  |
| 1.01-2.0   | 1         | 1      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 28.81%  |
| 251-500        | 12        | 20.34%  |
| 501-1000       | 10        | 16.95%  |
| 21-50          | 7         | 11.86%  |
| 51-100         | 5         | 8.47%   |
| 1-20           | 3         | 5.08%   |
| More than 3000 | 2         | 3.39%   |
| 1001-2000      | 2         | 3.39%   |
| 2001-3000      | 1         | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 26        | 43.33%  |
| 21-50          | 14        | 23.33%  |
| 101-250        | 6         | 10%     |
| 51-100         | 6         | 10%     |
| 251-500        | 4         | 6.67%   |
| 501-1000       | 2         | 3.33%   |
| More than 3000 | 1         | 1.67%   |
| 1001-2000      | 1         | 1.67%   |

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
| Works    | 52        | 78     | 80%     |
| Detected | 8         | 9      | 12.31%  |
| Malfunc  | 5         | 5      | 7.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 44        | 64.71%  |
| SK hynix                    | 5         | 7.35%   |
| SanDisk                     | 5         | 7.35%   |
| Samsung Electronics         | 5         | 7.35%   |
| Kingston Technology Company | 2         | 2.94%   |
| AMD                         | 2         | 2.94%   |
| Silicon Image               | 1         | 1.47%   |
| Phison Electronics          | 1         | 1.47%   |
| Nvidia                      | 1         | 1.47%   |
| Micron/Crucial Technology   | 1         | 1.47%   |
| KIOXIA                      | 1         | 1.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 11.11%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 6.94%   |
| SK hynix BC511                                                                   | 3         | 4.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 4.17%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 2.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 2.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 2.78%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 2         | 2.78%   |
| SK hynix Gold P31 SSD                                                            | 1         | 1.39%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 1.39%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1         | 1.39%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 1.39%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.39%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 1.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.39%   |
| Samsung Electronics SATA controller                                              | 1         | 1.39%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.39%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 1.39%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 1.39%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.39%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 1.39%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 1.39%   |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 1.39%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.39%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 1.39%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.39%   |
| Intel SSD 660P Series                                                            | 1         | 1.39%   |
| Intel Non-Volatile memory controller                                             | 1         | 1.39%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 1.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.39%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.39%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.39%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 40        | 59.7%   |
| NVMe | 17        | 25.37%  |
| IDE  | 6         | 8.96%   |
| RAID | 4         | 5.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 50        | 84.75%  |
| AMD    | 9         | 15.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 5.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.39%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 3.39%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 3.39%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 3.39%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 3.39%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 3.39%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 1.69%   |
| Intel Pentium M processor 1.80GHz             | 1         | 1.69%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 1         | 1.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.69%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.69%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 1.69%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.69%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.69%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.69%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.69%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.69%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 1         | 1.69%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 1.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.69%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1.69%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.69%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.69%   |
| Intel Core i5-10500H CPU @ 2.50GHz            | 1         | 1.69%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.69%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.69%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 1.69%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.69%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 1.69%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 1.69%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 1.69%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 1.69%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 1.69%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 1.69%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 1         | 1.69%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.69%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 1         | 1.69%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 1.69%   |
| Intel Atom CPU Z3735G @ 1.33GHz               | 1         | 1.69%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 1.69%   |
| Intel 11th Gen Core i9-11980HK @ 2.60GHz      | 1         | 1.69%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.69%   |
| AMD Sempron SI-42                             | 1         | 1.69%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 1.69%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 1.69%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 1.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.69%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 1         | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 14        | 23.73%  |
| Intel Core i5        | 14        | 23.73%  |
| Intel Celeron        | 7         | 11.86%  |
| AMD Ryzen 7          | 5         | 8.47%   |
| Other                | 4         | 6.78%   |
| Intel Core i3        | 4         | 6.78%   |
| Intel Core 2 Duo     | 2         | 3.39%   |
| Intel Atom           | 2         | 3.39%   |
| Intel Pentium Silver | 1         | 1.69%   |
| Intel Pentium M      | 1         | 1.69%   |
| Intel Genuine        | 1         | 1.69%   |
| AMD Sempron          | 1         | 1.69%   |
| AMD Ryzen 9          | 1         | 1.69%   |
| AMD Ryzen 5          | 1         | 1.69%   |
| AMD Ryzen 3          | 1         | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 27        | 45.76%  |
| 4      | 19        | 32.2%   |
| 8      | 6         | 10.17%  |
| 6      | 3         | 5.08%   |
| 1      | 3         | 5.08%   |
| 14     | 1         | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 59        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 74.58%  |
| 1      | 15        | 25.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 56        | 94.92%  |
| 32-bit         | 3         | 5.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 5         | 8.47%   |
| 0x206a7    | 5         | 8.47%   |
| Unknown    | 4         | 6.78%   |
| 0xa0652    | 3         | 5.08%   |
| 0x406e3    | 3         | 5.08%   |
| 0x306c3    | 3         | 5.08%   |
| 0x0a50000c | 3         | 5.08%   |
| 0x806ea    | 2         | 3.39%   |
| 0x806c1    | 2         | 3.39%   |
| 0x706a1    | 2         | 3.39%   |
| 0x506e3    | 2         | 3.39%   |
| 0x406c4    | 2         | 3.39%   |
| 0x30678    | 2         | 3.39%   |
| 0x20655    | 2         | 3.39%   |
| 0x906ea    | 1         | 1.69%   |
| 0x906a3    | 1         | 1.69%   |
| 0x806eb    | 1         | 1.69%   |
| 0x806e9    | 1         | 1.69%   |
| 0x806d1    | 1         | 1.69%   |
| 0x706a8    | 1         | 1.69%   |
| 0x6fd      | 1         | 1.69%   |
| 0x6fb      | 1         | 1.69%   |
| 0x6e8      | 1         | 1.69%   |
| 0x6d6      | 1         | 1.69%   |
| 0x506c9    | 1         | 1.69%   |
| 0x106e5    | 1         | 1.69%   |
| 0x106c2    | 1         | 1.69%   |
| 0x0a50000b | 1         | 1.69%   |
| 0x08608103 | 1         | 1.69%   |
| 0x08600106 | 1         | 1.69%   |
| 0x08108109 | 1         | 1.69%   |
| 0x08108102 | 1         | 1.69%   |
| 0x02000057 | 1         | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 6         | 10.17%  |
| Skylake          | 5         | 8.47%   |
| KabyLake         | 5         | 8.47%   |
| IvyBridge        | 5         | 8.47%   |
| Zen 3            | 4         | 6.78%   |
| Silvermont       | 4         | 6.78%   |
| Westmere         | 3         | 5.08%   |
| Haswell          | 3         | 5.08%   |
| Goldmont plus    | 3         | 5.08%   |
| CometLake        | 3         | 5.08%   |
| Zen+             | 2         | 3.39%   |
| TigerLake        | 2         | 3.39%   |
| P6               | 2         | 3.39%   |
| Icelake          | 2         | 3.39%   |
| Core             | 2         | 3.39%   |
| Zen 2            | 1         | 1.69%   |
| Nehalem          | 1         | 1.69%   |
| K8 & K10 hybrid  | 1         | 1.69%   |
| Goldmont         | 1         | 1.69%   |
| Broadwell        | 1         | 1.69%   |
| Bonnell          | 1         | 1.69%   |
| Alderlake Hybrid | 1         | 1.69%   |
| Unknown          | 1         | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 61.04%  |
| Nvidia | 19        | 24.68%  |
| AMD    | 11        | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 7.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 6.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 3.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 3.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 3.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.7%    |
| AMD Cezanne                                                                              | 3         | 3.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 2.47%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.47%   |
| Intel HD Graphics 530                                                                    | 2         | 2.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2.47%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.23%   |
| Nvidia TU117M                                                                            | 1         | 1.23%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.23%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 1.23%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.23%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.23%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.23%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 1.23%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.23%   |
| Nvidia GF108M [GeForce GT 550M]                                                          | 1         | 1.23%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1.23%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.23%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                              | 1         | 1.23%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 1         | 1.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.23%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 1         | 1.23%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.23%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.23%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.23%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.23%   |
| Intel HD Graphics 620                                                                    | 1         | 1.23%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.23%   |
| Intel HD Graphics 500                                                                    | 1         | 1.23%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.23%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 1.23%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.23%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.23%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                            | 1         | 1.23%   |
| AMD Renoir                                                                               | 1         | 1.23%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 1.23%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 1         | 1.23%   |
| AMD Lucienne                                                                             | 1         | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 54.24%  |
| Intel + Nvidia | 13        | 22.03%  |
| 1 x AMD        | 5         | 8.47%   |
| 1 x Nvidia     | 3         | 5.08%   |
| AMD + Nvidia   | 3         | 5.08%   |
| Intel + AMD    | 2         | 3.39%   |
| 2 x AMD        | 1         | 1.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 48        | 81.36%  |
| Proprietary | 10        | 16.95%  |
| Unknown     | 1         | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 81.36%  |
| 0.01-0.5   | 5         | 8.47%   |
| 0.51-1.0   | 3         | 5.08%   |
| 7.01-8.0   | 1         | 1.69%   |
| 3.01-4.0   | 1         | 1.69%   |
| 1.01-2.0   | 1         | 1.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 11        | 17.19%  |
| LG Display              | 9         | 14.06%  |
| AU Optronics            | 9         | 14.06%  |
| Samsung Electronics     | 7         | 10.94%  |
| PANDA                   | 4         | 6.25%   |
| BOE                     | 4         | 6.25%   |
| Sharp                   | 3         | 4.69%   |
| Sony                    | 2         | 3.13%   |
| Chi Mei Optoelectronics | 2         | 3.13%   |
| Apple                   | 2         | 3.13%   |
| Ancor Communications    | 2         | 3.13%   |
| Sunplus                 | 1         | 1.56%   |
| Philips                 | 1         | 1.56%   |
| Panasonic               | 1         | 1.56%   |
| Lenovo                  | 1         | 1.56%   |
| InfoVision              | 1         | 1.56%   |
| Hewlett-Packard         | 1         | 1.56%   |
| Goldstar                | 1         | 1.56%   |
| Dell                    | 1         | 1.56%   |
| CPT                     | 1         | 1.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 3.13%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 3.13%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 3.13%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch                 | 1         | 1.56%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 1.56%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 1.56%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 1.56%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 1.56%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 1.56%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC4650 1400x1050 304x228mm 15.0-inch    | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 1.56%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 1.56%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 1.56%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                  | 1         | 1.56%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 1         | 1.56%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch              | 1         | 1.56%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 1.56%   |
| LG Display LCD Monitor LGD06E2 1920x1080 344x194mm 15.5-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch              | 1         | 1.56%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 1         | 1.56%   |
| LG Display LCD Monitor LGD024D 1366x768 294x166mm 13.3-inch              | 1         | 1.56%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 518x324mm 24.1-inch                 | 1         | 1.56%   |
| InfoVision LCD Monitor IVO048E 1366x768 256x144mm 11.6-inch              | 1         | 1.56%   |
| Hewlett-Packard LA2306 HWP294B 1920x1080 509x286mm 23.0-inch             | 1         | 1.56%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 1         | 1.56%   |
| Dell 1907FP DEL4014 1280x1024 376x301mm 19.0-inch                        | 1         | 1.56%   |
| CPT LCD Monitor CPT1C21 1366x768 256x144mm 11.6-inch                     | 1         | 1.56%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch         | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15D6 1920x1080 344x193mm 15.5-inch         | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 1.56%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 1.56%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 1         | 1.56%   |
| BOE LCD Monitor BOE0714 1920x1080 344x193mm 15.5-inch                    | 1         | 1.56%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 1         | 1.56%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch           | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch            | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO123E 1600x900 309x174mm 14.0-inch            | 1         | 1.56%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 1         | 1.56%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                     | 1         | 1.56%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch         | 1         | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 26        | 43.33%  |
| 1366x768 (WXGA)  | 19        | 31.67%  |
| 3840x2160 (4K)   | 3         | 5%      |
| 1600x900 (HD+)   | 2         | 3.33%   |
| 1440x900 (WXGA+) | 2         | 3.33%   |
| 1280x800 (WXGA)  | 2         | 3.33%   |
| 3840x2400        | 1         | 1.67%   |
| 2560x1080        | 1         | 1.67%   |
| 2256x1504        | 1         | 1.67%   |
| 2160x1440        | 1         | 1.67%   |
| 1400x1050        | 1         | 1.67%   |
| 1280x1024 (SXGA) | 1         | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 30        | 46.88%  |
| 13     | 8         | 12.5%   |
| 14     | 6         | 9.38%   |
| 17     | 4         | 6.25%   |
| 11     | 4         | 6.25%   |
| 24     | 3         | 4.69%   |
| 23     | 3         | 4.69%   |
| 19     | 3         | 4.69%   |
| 27     | 2         | 3.13%   |
| 34     | 1         | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 57.81%  |
| 201-300     | 10        | 15.63%  |
| 501-600     | 8         | 12.5%   |
| 351-400     | 7         | 10.94%  |
| 701-800     | 1         | 1.56%   |
| 401-500     | 1         | 1.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 46        | 77.97%  |
| 16/10 | 7         | 11.86%  |
| 5/4   | 2         | 3.39%   |
| 3/2   | 2         | 3.39%   |
| 4/3   | 1         | 1.69%   |
| 21/9  | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 46.88%  |
| 81-90          | 12        | 18.75%  |
| 201-250        | 5         | 7.81%   |
| 51-60          | 4         | 6.25%   |
| 121-130        | 4         | 6.25%   |
| 151-200        | 3         | 4.69%   |
| 71-80          | 2         | 3.13%   |
| 301-350        | 2         | 3.13%   |
| 351-500        | 1         | 1.56%   |
| 251-300        | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 26        | 41.94%  |
| 51-100        | 15        | 24.19%  |
| 101-120       | 14        | 22.58%  |
| 161-240       | 4         | 6.45%   |
| More than 240 | 3         | 4.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 47        | 79.66%  |
| 2     | 10        | 16.95%  |
| 3     | 1         | 1.69%   |
| 0     | 1         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 32        | 34.04%  |
| Intel                    | 31        | 32.98%  |
| Qualcomm Atheros         | 14        | 14.89%  |
| Marvell Technology Group | 4         | 4.26%   |
| MediaTek                 | 3         | 3.19%   |
| TP-Link                  | 2         | 2.13%   |
| Broadcom                 | 2         | 2.13%   |
| Samsung Electronics      | 1         | 1.06%   |
| Ralink Technology        | 1         | 1.06%   |
| Nvidia                   | 1         | 1.06%   |
| Dell                     | 1         | 1.06%   |
| Broadcom Limited         | 1         | 1.06%   |
| ASUSTek Computer         | 1         | 1.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 23        | 21.1%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 4         | 3.67%   |
| Intel Wi-Fi 6 AX200                                                            | 4         | 3.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 3         | 2.75%   |
| Intel Wireless 8260                                                            | 3         | 2.75%   |
| Intel Wireless 7260                                                            | 3         | 2.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 1.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 1.83%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 1.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 1.83%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.83%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.83%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 1.83%   |
| Intel Centrino Advanced-N 6200                                                 | 2         | 1.83%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.83%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1         | 0.92%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 0.92%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1         | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 1         | 0.92%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.92%   |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 0.92%   |
| Ralink RT2070 Wireless Adapter                                                 | 1         | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1         | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 0.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.92%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.92%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.92%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 0.92%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.92%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.92%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.92%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.92%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.92%   |
| Intel Wireless 7265                                                            | 1         | 0.92%   |
| Intel Wireless 3165                                                            | 1         | 0.92%   |
| Intel Wireless 3160                                                            | 1         | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1         | 0.92%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 0.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 0.92%   |
| Intel Centrino Advanced-N 6235                                                 | 1         | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1         | 0.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 0.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 1         | 0.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 0.92%   |
| Dell F3607gw v2 Mobile Broadband Module                                        | 1         | 0.92%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                     | 1         | 0.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 31        | 51.67%  |
| Qualcomm Atheros      | 11        | 18.33%  |
| Realtek Semiconductor | 10        | 16.67%  |
| MediaTek              | 3         | 5%      |
| TP-Link               | 1         | 1.67%   |
| Ralink Technology     | 1         | 1.67%   |
| Broadcom Limited      | 1         | 1.67%   |
| Broadcom              | 1         | 1.67%   |
| ASUSTek Computer      | 1         | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 6.67%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 6.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 5%      |
| Intel Wireless 8260                                                     | 3         | 5%      |
| Intel Wireless 7260                                                     | 3         | 5%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.33%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 3.33%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 3.33%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 3.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.67%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.67%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.67%   |
| Intel Wireless 7265                                                     | 1         | 1.67%   |
| Intel Wireless 3165                                                     | 1         | 1.67%   |
| Intel Wireless 3160                                                     | 1         | 1.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.67%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.67%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.67%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.67%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 1.67%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 1.67%   |
| ASUS 802.11ac NIC                                                       | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 57.45%  |
| Intel                    | 7         | 14.89%  |
| Qualcomm Atheros         | 5         | 10.64%  |
| Marvell Technology Group | 4         | 8.51%   |
| TP-Link                  | 1         | 2.13%   |
| Samsung Electronics      | 1         | 2.13%   |
| Nvidia                   | 1         | 2.13%   |
| Broadcom                 | 1         | 2.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 23        | 47.92%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 4.17%   |
| Intel Ethernet Connection I219-V                                               | 2         | 4.17%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 4.17%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 4.17%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 2.08%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 2.08%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 2.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 2.08%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 2.08%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 2.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 2.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 2.08%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 2.08%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 2.08%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 2.08%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 2.08%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 2.08%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 54.37%  |
| Ethernet | 46        | 44.66%  |
| Modem    | 1         | 0.97%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 73.02%  |
| Ethernet | 17        | 26.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 42        | 71.19%  |
| 1     | 15        | 25.42%  |
| 0     | 2         | 3.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 76.27%  |
| Yes  | 14        | 23.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 46.81%  |
| Realtek Semiconductor           | 5         | 10.64%  |
| Qualcomm Atheros Communications | 5         | 10.64%  |
| IMC Networks                    | 3         | 6.38%   |
| Foxconn / Hon Hai               | 3         | 6.38%   |
| Cambridge Silicon Radio         | 3         | 6.38%   |
| Apple                           | 2         | 4.26%   |
| Lite-On Technology              | 1         | 2.13%   |
| Hewlett-Packard                 | 1         | 2.13%   |
| Dell                            | 1         | 2.13%   |
| ASUSTek Computer                | 1         | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 10        | 21.28%  |
| Realtek Bluetooth Radio                                                             | 4         | 8.51%   |
| Intel Bluetooth Device                                                              | 4         | 8.51%   |
| Intel AX200 Bluetooth                                                               | 4         | 8.51%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 6.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 6.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 6.38%   |
| IMC Networks Wireless_Device                                                        | 2         | 4.26%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 4.26%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 2.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 2.13%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 2.13%   |
| Lite-On Wireless_Device                                                             | 1         | 2.13%   |
| Intel AX210 Bluetooth                                                               | 1         | 2.13%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 2.13%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 2.13%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 2.13%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 2.13%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 2.13%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 2.13%   |
| Apple Bluetooth HCI                                                                 | 1         | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 63.64%  |
| Nvidia                | 14        | 18.18%  |
| AMD                   | 9         | 11.69%  |
| Texas Instruments     | 1         | 1.3%    |
| Realtek Semiconductor | 1         | 1.3%    |
| Plantronics           | 1         | 1.3%    |
| C-Media Electronics   | 1         | 1.3%    |
| Unknown               | 1         | 1.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 9.09%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 9.09%   |
| Nvidia Audio device                                                                               | 6         | 6.82%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 6.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 5.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 3.41%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 3.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 3.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 3.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.27%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 1.14%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.14%   |
| Plantronics BT600                                                                                 | 1         | 1.14%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.14%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 1.14%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 1.14%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.14%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.14%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 1.14%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.14%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.14%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.14%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.14%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 1         | 1.14%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.14%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1         | 1.14%   |
| Unknown                                                                                           | 1         | 1.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 22.86%  |
| SK hynix            | 14        | 20%     |
| Unknown             | 12        | 17.14%  |
| Micron Technology   | 7         | 10%     |
| Kingston            | 7         | 10%     |
| Crucial             | 4         | 5.71%   |
| Unknown (ABCD)      | 2         | 2.86%   |
| Smart               | 2         | 2.86%   |
| Corsair             | 2         | 2.86%   |
| Transcend           | 1         | 1.43%   |
| PNY                 | 1         | 1.43%   |
| Avant               | 1         | 1.43%   |
| Unknown             | 1         | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                                  | 4         | 5.06%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 3         | 3.8%    |
| Unknown RAM Module 8GB SODIMM DDR3                                  | 2         | 2.53%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 2.53%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 2         | 2.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 2.53%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 2         | 2.53%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 1.27%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                          | 1         | 1.27%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 1         | 1.27%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 1.27%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 1.27%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 1.27%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                         | 1         | 1.27%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 1.27%   |
| Transcend RAM TS128MSQ64V6J 1GB SODIMM DDR 667MT/s                  | 1         | 1.27%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 1         | 1.27%   |
| Smart RAM SF4641G8CK8IEGKSBG 8192MB SODIMM DDR4 2400MT/s            | 1         | 1.27%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                        | 1         | 1.27%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.27%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.27%   |
| SK hynix RAM HMT351S6EFR8A 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.27%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.27%   |
| SK hynix RAM HMT351S6AFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 1.27%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.27%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s           | 1         | 1.27%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s              | 1         | 1.27%   |
| SK hynix RAM HMCG66MEBSA095N 8GB SODIMM 4800MT/s                    | 1         | 1.27%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.27%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 1.27%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 1.27%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 1.27%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.27%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 1.27%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 1.27%   |
| SK hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s              | 1         | 1.27%   |
| Samsung RAM Module 4GB SODIMM DDR2 667MT/s                          | 1         | 1.27%   |
| Samsung RAM M471B5773EB0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1.27%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 1         | 1.27%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.27%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.27%   |
| Samsung RAM M471B1G73DHO-CH9 8GB SODIMM DDR3 1333MT/s               | 1         | 1.27%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 1.27%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 1         | 1.27%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.27%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.27%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB SODIMM LPDDR4 2400MT/s              | 1         | 1.27%   |
| PNY RAM Module 8GB SODIMM DDR3 1333MT/s                             | 1         | 1.27%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                          | 1         | 1.27%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.27%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 1         | 1.27%   |
| Micron RAM 4ATF51264HZ-2G6E! 4096MB SODIMM DDR4 2400MT/s            | 1         | 1.27%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 1         | 1.27%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s            | 1         | 1.27%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 1         | 1.27%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.27%   |
| Kingston RAM KHX2400C14S4/8G 8GB Row Of Chips DDR4 2400MT/s         | 1         | 1.27%   |
| Kingston RAM HP594908-HR1-ELD 2GB SODIMM DDR3 1333MT/s              | 1         | 1.27%   |
| Kingston RAM HP16D3LS1KEGR/4G 4GB SODIMM DDR3 1600MT/s              | 1         | 1.27%   |
| Kingston RAM 99U5428-063.A00LF 8192MB SODIMM DDR3 1600MT/s          | 1         | 1.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 24        | 40%     |
| DDR3    | 24        | 40%     |
| DDR2    | 4         | 6.67%   |
| LPDDR4  | 3         | 5%      |
| DDR     | 2         | 3.33%   |
| SDRAM   | 1         | 1.67%   |
| DRAM    | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 58        | 96.67%  |
| Row Of Chips | 2         | 3.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 28        | 41.18%  |
| 4096  | 25        | 36.76%  |
| 2048  | 9         | 13.24%  |
| 1024  | 4         | 5.88%   |
| 32768 | 1         | 1.47%   |
| 16384 | 1         | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 13        | 20.97%  |
| 3200    | 12        | 19.35%  |
| 2400    | 7         | 11.29%  |
| 1333    | 6         | 9.68%   |
| Unknown | 6         | 9.68%   |
| 2667    | 5         | 8.06%   |
| 2133    | 4         | 6.45%   |
| 667     | 4         | 6.45%   |
| 4800    | 1         | 1.61%   |
| 4199    | 1         | 1.61%   |
| 1334    | 1         | 1.61%   |
| 1067    | 1         | 1.61%   |
| 166     | 1         | 1.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P2055 series | 1         | 100%    |

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
| Chicony Electronics                    | 12        | 26.67%  |
| Realtek Semiconductor                  | 5         | 11.11%  |
| Microdia                               | 4         | 8.89%   |
| Acer                                   | 4         | 8.89%   |
| IMC Networks                           | 3         | 6.67%   |
| Sunplus Innovation Technology          | 2         | 4.44%   |
| Lite-On Technology                     | 2         | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.44%   |
| Z-Star Microelectronics                | 1         | 2.22%   |
| Y Media                                | 1         | 2.22%   |
| Suyin                                  | 1         | 2.22%   |
| Silicon Motion                         | 1         | 2.22%   |
| Ricoh                                  | 1         | 2.22%   |
| Quanta                                 | 1         | 2.22%   |
| Primax Electronics                     | 1         | 2.22%   |
| Logitech                               | 1         | 2.22%   |
| Goodong Industry                       | 1         | 2.22%   |
| Alcor Micro                            | 1         | 2.22%   |
| 8SSC20F27145V1SR1BX02P8                | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                        | 2         | 4.44%   |
| Lite-On HP HD Camera                                | 2         | 4.44%   |
| Chicony Integrated Camera                           | 2         | 4.44%   |
| Acer BisonCam, NB Pro                               | 2         | 4.44%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 2.22%   |
| Y Media USB Camera                                  | 1         | 2.22%   |
| Suyin Sony Visual Communication Camera              | 1         | 2.22%   |
| Silicon Motion Web Camera                           | 1         | 2.22%   |
| Ricoh USB2.0 Camera                                 | 1         | 2.22%   |
| Realtek USB Camera                                  | 1         | 2.22%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.22%   |
| Realtek Integrated_Webcam_HD                        | 1         | 2.22%   |
| Realtek Integrated Webcam                           | 1         | 2.22%   |
| Realtek EasyCamera                                  | 1         | 2.22%   |
| Quanta HD User Facing                               | 1         | 2.22%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 2.22%   |
| Microdia Webcam Vitade AF                           | 1         | 2.22%   |
| Microdia WebCam SC-13HDL12639P                      | 1         | 2.22%   |
| Microdia Webcam                                     | 1         | 2.22%   |
| Microdia USB 2.0 Camera                             | 1         | 2.22%   |
| Logitech StreamCam                                  | 1         | 2.22%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                 | 1         | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.22%   |
| IMC Networks Integrated Camera                      | 1         | 2.22%   |
| Goodong Industry USB2.0 HD UVC WebCam               | 1         | 2.22%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 2.22%   |
| Chicony USB 2.0 Camera                              | 1         | 2.22%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 2.22%   |
| Chicony thinkpad t430s camera                       | 1         | 2.22%   |
| Chicony Sony Visual Communication Camera            | 1         | 2.22%   |
| Chicony Lenovo EasyCamera                           | 1         | 2.22%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 2.22%   |
| Chicony HP HD Webcam                                | 1         | 2.22%   |
| Chicony HD User Facing                              | 1         | 2.22%   |
| Chicony 2.0M UVC WebCam                             | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.22%   |
| Alcor Micro USB 2.0 Camera                          | 1         | 2.22%   |
| Acer SunplusIT INC. Integrated Camera               | 1         | 2.22%   |
| Acer BisonCam,NB Pro                                | 1         | 2.22%   |
| 8SSC20F27145V1SR1BX02P8 Integrated Camera           | 1         | 2.22%   |

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


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 42        | 70%     |
| 1     | 15        | 25%     |
| 2     | 3         | 5%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 10        | 52.63%  |
| Fingerprint reader    | 7         | 36.84%  |
| Multimedia controller | 1         | 5.26%   |
| Chipcard              | 1         | 5.26%   |

