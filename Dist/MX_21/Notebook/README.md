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

Total: 73

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3190               | [b88d7076df](https://linux-hardware.org/?probe=b88d7076df) | Apr 25, 2022 |
| Acer          | Nitro AN515-55              | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| HP            | ProBook 450 G4              | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Dell          | Latitude 3190               | [d1542717be](https://linux-hardware.org/?probe=d1542717be) | Apr 18, 2022 |
| Dell          | Latitude 3190               | [5369d059e6](https://linux-hardware.org/?probe=5369d059e6) | Apr 11, 2022 |
| Gigabyte      | G5 KC                       | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | [46f9e8b140](https://linux-hardware.org/?probe=46f9e8b140) | Apr 07, 2022 |
| Acer          | Aspire A515-56              | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| ASUSTek       | 1101HA                      | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Dell          | Latitude 3190               | [45542e945e](https://linux-hardware.org/?probe=45542e945e) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| TUXEDO        | N7x0WU                      | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Dell          | Latitude 3190               | [ffd3ee8119](https://linux-hardware.org/?probe=ffd3ee8119) | Mar 28, 2022 |
| Framework     | Laptop                      | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Dell          | Latitude 3190               | [960989448e](https://linux-hardware.org/?probe=960989448e) | Mar 21, 2022 |
| Dell          | Latitude 3190               | [6d1ab0283d](https://linux-hardware.org/?probe=6d1ab0283d) | Mar 14, 2022 |
| Dell          | Latitude 3190               | [620f4d4f09](https://linux-hardware.org/?probe=620f4d4f09) | Mar 07, 2022 |
| Dell          | Latitude 3190               | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | Latitude 3190               | [9637b88602](https://linux-hardware.org/?probe=9637b88602) | Feb 21, 2022 |
| Dell          | XPS 17 9710                 | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| Dell          | Latitude 3190               | [6340f68567](https://linux-hardware.org/?probe=6340f68567) | Feb 14, 2022 |
| Sony          | SVE1513Q1ESI                | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude 3190               | [90df65f573](https://linux-hardware.org/?probe=90df65f573) | Feb 07, 2022 |
| Dell          | Latitude E4310              | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Dell          | Latitude 3190               | [2e81dc022b](https://linux-hardware.org/?probe=2e81dc022b) | Jan 31, 2022 |
| Dell          | Latitude 3190               | [9b8e8549fd](https://linux-hardware.org/?probe=9b8e8549fd) | Jan 24, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| Dell          | Latitude 3190               | [3bb6a6428f](https://linux-hardware.org/?probe=3bb6a6428f) | Jan 10, 2022 |
| HP            | EliteBook 840 G3            | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Dell          | Latitude 3190               | [2c483dc59d](https://linux-hardware.org/?probe=2c483dc59d) | Jan 03, 2022 |
| Gigabyte      | P15FV5                      | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| Dell          | Latitude 3190               | [67cba6d321](https://linux-hardware.org/?probe=67cba6d321) | Dec 27, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| ASUSTek       | X550CC                      | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Dell          | Latitude 3190               | [1a96380872](https://linux-hardware.org/?probe=1a96380872) | Dec 20, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Dell          | Latitude 3190               | [5321909b8c](https://linux-hardware.org/?probe=5321909b8c) | Dec 13, 2021 |
| Dell          | Latitude 3190               | [9c532278f1](https://linux-hardware.org/?probe=9c532278f1) | Dec 06, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| Lenovo        | B590 20208                  | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Dell          | Latitude 3190               | [700dd2459e](https://linux-hardware.org/?probe=700dd2459e) | Nov 29, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Dell          | Latitude 3190               | [7f020f1d1f](https://linux-hardware.org/?probe=7f020f1d1f) | Nov 22, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Dell          | Latitude 3190               | [f24ac635ba](https://linux-hardware.org/?probe=f24ac635ba) | Nov 15, 2021 |
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


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.10.0-9-amd64    | 14        | 28%     |
| 5.10.0-13-amd64   | 10        | 20%     |
| 5.14.0-4mx-amd64  | 7         | 14%     |
| 5.10.0-11-amd64   | 6         | 12%     |
| 5.10.0-10-amd64   | 3         | 6%      |
| 5.10.0-8-amd64    | 2         | 4%      |
| 5.10.0-11-686-pae | 2         | 4%      |
| 5.17.0-1-amd64    | 1         | 2%      |
| 5.16.0-4mx-amd64  | 1         | 2%      |
| 5.15.0-3mx-amd64  | 1         | 2%      |
| 5.10.0-5mx-amd64  | 1         | 2%      |
| 5.10.0-13-686-pae | 1         | 2%      |
| 5.10.0-11-686     | 1         | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 36        | 78.26%  |
| 5.14.0  | 7         | 15.22%  |
| 5.17.0  | 1         | 2.17%   |
| 5.16.0  | 1         | 2.17%   |
| 5.15.0  | 1         | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 36        | 78.26%  |
| 5.14    | 7         | 15.22%  |
| 5.17    | 1         | 2.17%   |
| 5.16    | 1         | 2.17%   |
| 5.15    | 1         | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 43        | 93.48%  |
| i686   | 3         | 6.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 32        | 69.57%  |
| KDE5    | 11        | 23.91%  |
| GNOME   | 1         | 2.17%   |
| Budgie  | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 45        | 97.83%  |
| Tty  | 1         | 2.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 34        | 73.91%  |
| SDDM    | 11        | 23.91%  |
| Unknown | 1         | 2.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 22        | 47.83%  |
| de_DE   | 7         | 15.22%  |
| it_IT   | 3         | 6.52%   |
| Unknown | 3         | 6.52%   |
| ru_RU   | 2         | 4.35%   |
| pt_BR   | 2         | 4.35%   |
| sk_SK   | 1         | 2.17%   |
| fr_FR   | 1         | 2.17%   |
| fi_FI   | 1         | 2.17%   |
| es_PE   | 1         | 2.17%   |
| es_ES   | 1         | 2.17%   |
| en_GB   | 1         | 2.17%   |
| de_CH   | 1         | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 34        | 73.91%  |
| BIOS | 12        | 26.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 38        | 82.61%  |
| Overlay | 5         | 10.87%  |
| Btrfs   | 2         | 4.35%   |
| F2fs    | 1         | 2.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 35        | 76.09%  |
| MBR  | 11        | 23.91%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 69.57%  |
| Yes       | 14        | 30.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 52.17%  |
| No        | 22        | 47.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 9         | 19.57%  |
| ASUSTek Computer    | 8         | 17.39%  |
| Hewlett-Packard     | 5         | 10.87%  |
| Sony                | 4         | 8.7%    |
| Dell                | 3         | 6.52%   |
| Samsung Electronics | 2         | 4.35%   |
| MSI                 | 2         | 4.35%   |
| Gigabyte Technology | 2         | 4.35%   |
| Fujitsu Siemens     | 2         | 4.35%   |
| Alienware           | 2         | 4.35%   |
| Acer                | 2         | 4.35%   |
| TUXEDO              | 1         | 2.17%   |
| Framework           | 1         | 2.17%   |
| efirstview          | 1         | 2.17%   |
| Chuwi               | 1         | 2.17%   |
| Apple               | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| TUXEDO N7x0WU                             | 1         | 2.17%   |
| Sony VPCF119FX                            | 1         | 2.17%   |
| Sony VPCEH2N1E                            | 1         | 2.17%   |
| Sony VPCEC3S1E                            | 1         | 2.17%   |
| Sony SVE1513Q1ESI                         | 1         | 2.17%   |
| Samsung 350V5C/351V5C/3540VC/3440VC       | 1         | 2.17%   |
| Samsung 340XAA/350XAA/550XAA              | 1         | 2.17%   |
| MSI GV62 8RD                              | 1         | 2.17%   |
| MSI Alpha 15 B5EEK                        | 1         | 2.17%   |
| Lenovo ThinkPad W541 20EG0005MS           | 1         | 2.17%   |
| Lenovo ThinkPad T440p 20AW002VBR          | 1         | 2.17%   |
| Lenovo ThinkPad T430 23427YU              | 1         | 2.17%   |
| Lenovo ThinkPad E15 Gen 3 20YG008CUS      | 1         | 2.17%   |
| Lenovo ThinkBook 13s-IWL 20R9             | 1         | 2.17%   |
| Lenovo Legion 5 15ACH6H 82JU              | 1         | 2.17%   |
| Lenovo IdeaPad Y700-15ISK 80NV            | 1         | 2.17%   |
| Lenovo G400s VILG1                        | 1         | 2.17%   |
| Lenovo B590 20208                         | 1         | 2.17%   |
| HP ProBook 450 G4                         | 1         | 2.17%   |
| HP EliteBook 850 G3                       | 1         | 2.17%   |
| HP EliteBook 8440p                        | 1         | 2.17%   |
| HP EliteBook 840 G3                       | 1         | 2.17%   |
| HP Compaq Presario CQ60                   | 1         | 2.17%   |
| Gigabyte P15FV5                           | 1         | 2.17%   |
| Gigabyte G5 KC                            | 1         | 2.17%   |
| Fujitsu Siemens LIFEBOOK E8010            | 1         | 2.17%   |
| Fujitsu Siemens ESPRIMO Mobile D9500      | 1         | 2.17%   |
| Framework Laptop                          | 1         | 2.17%   |
| efirstview v01099                         | 1         | 2.17%   |
| Dell XPS 17 9710                          | 1         | 2.17%   |
| Dell Latitude E4310                       | 1         | 2.17%   |
| Dell Latitude 3190                        | 1         | 2.17%   |
| Chuwi GemiBook Pro                        | 1         | 2.17%   |
| ASUS X550CC                               | 1         | 2.17%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 1         | 2.17%   |
| ASUS ROG Strix G712LU_G712LU              | 1         | 2.17%   |
| ASUS ROG Strix G513QC_G513QC              | 1         | 2.17%   |
| ASUS N53SN                                | 1         | 2.17%   |
| ASUS E402MA                               | 1         | 2.17%   |
| ASUS ASUS TUF Gaming A15 FA506QE_TUF506QE | 1         | 2.17%   |
| ASUS 1101HA                               | 1         | 2.17%   |
| Apple MacBook3,1                          | 1         | 2.17%   |
| Alienware m15 R7                          | 1         | 2.17%   |
| Alienware 13 R2                           | 1         | 2.17%   |
| Acer Nitro AN515-55                       | 1         | 2.17%   |
| Acer Aspire A515-56                       | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 8.7%    |
| HP EliteBook             | 3         | 6.52%   |
| Dell Latitude            | 2         | 4.35%   |
| ASUS ROG                 | 2         | 4.35%   |
| TUXEDO N7x0WU            | 1         | 2.17%   |
| Sony VPCF119FX           | 1         | 2.17%   |
| Sony VPCEH2N1E           | 1         | 2.17%   |
| Sony VPCEC3S1E           | 1         | 2.17%   |
| Sony SVE1513Q1ESI        | 1         | 2.17%   |
| Samsung 350V5C           | 1         | 2.17%   |
| Samsung 340XAA           | 1         | 2.17%   |
| MSI GV62                 | 1         | 2.17%   |
| MSI Alpha                | 1         | 2.17%   |
| Lenovo ThinkBook         | 1         | 2.17%   |
| Lenovo Legion            | 1         | 2.17%   |
| Lenovo IdeaPad           | 1         | 2.17%   |
| Lenovo G400s             | 1         | 2.17%   |
| Lenovo B590              | 1         | 2.17%   |
| HP ProBook               | 1         | 2.17%   |
| HP Compaq                | 1         | 2.17%   |
| Gigabyte P15FV5          | 1         | 2.17%   |
| Gigabyte G5              | 1         | 2.17%   |
| Fujitsu Siemens LIFEBOOK | 1         | 2.17%   |
| Fujitsu Siemens ESPRIMO  | 1         | 2.17%   |
| Framework Laptop         | 1         | 2.17%   |
| efirstview v01099        | 1         | 2.17%   |
| Dell XPS                 | 1         | 2.17%   |
| Chuwi GemiBook           | 1         | 2.17%   |
| ASUS X550CC              | 1         | 2.17%   |
| ASUS TUF                 | 1         | 2.17%   |
| ASUS N53SN               | 1         | 2.17%   |
| ASUS E402MA              | 1         | 2.17%   |
| ASUS ASUS                | 1         | 2.17%   |
| ASUS 1101HA              | 1         | 2.17%   |
| Apple MacBook3           | 1         | 2.17%   |
| Alienware m15            | 1         | 2.17%   |
| Alienware 13             | 1         | 2.17%   |
| Acer Nitro               | 1         | 2.17%   |
| Acer Aspire              | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 10        | 21.74%  |
| 2015    | 5         | 10.87%  |
| 2016    | 4         | 8.7%    |
| 2013    | 4         | 8.7%    |
| 2010    | 4         | 8.7%    |
| 2020    | 2         | 4.35%   |
| 2019    | 2         | 4.35%   |
| 2018    | 2         | 4.35%   |
| 2012    | 2         | 4.35%   |
| 2011    | 2         | 4.35%   |
| 2008    | 2         | 4.35%   |
| 2022    | 1         | 2.17%   |
| 2017    | 1         | 2.17%   |
| 2014    | 1         | 2.17%   |
| 2009    | 1         | 2.17%   |
| 2007    | 1         | 2.17%   |
| 2005    | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 46        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 46        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 46        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 16        | 34.78%  |
| 16.01-24.0  | 10        | 21.74%  |
| 8.01-16.0   | 10        | 21.74%  |
| 3.01-4.0    | 3         | 6.52%   |
| 2.01-3.0    | 2         | 4.35%   |
| 32.01-64.0  | 1         | 2.17%   |
| 24.01-32.0  | 1         | 2.17%   |
| 64.01-256.0 | 1         | 2.17%   |
| 1.01-2.0    | 1         | 2.17%   |
| 0.51-1.0    | 1         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 16        | 33.33%  |
| 2.01-3.0  | 13        | 27.08%  |
| 3.01-4.0  | 7         | 14.58%  |
| 4.01-8.0  | 6         | 12.5%   |
| 0.51-1.0  | 5         | 10.42%  |
| 8.01-16.0 | 1         | 2.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 58.7%   |
| 2      | 11        | 23.91%  |
| 3      | 6         | 13.04%  |
| 4      | 1         | 2.17%   |
| 0      | 1         | 2.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 71.74%  |
| Yes       | 13        | 28.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 84.78%  |
| No        | 7         | 15.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 93.48%  |
| No        | 3         | 6.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 80.43%  |
| No        | 9         | 19.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 9         | 19.57%  |
| Germany     | 6         | 13.04%  |
| Italy       | 5         | 10.87%  |
| Canada      | 5         | 10.87%  |
| Brazil      | 3         | 6.52%   |
| Belgium     | 2         | 4.35%   |
| Austria     | 2         | 4.35%   |
| Switzerland | 1         | 2.17%   |
| Spain       | 1         | 2.17%   |
| Slovakia    | 1         | 2.17%   |
| Serbia      | 1         | 2.17%   |
| Russia      | 1         | 2.17%   |
| Poland      | 1         | 2.17%   |
| Peru        | 1         | 2.17%   |
| Netherlands | 1         | 2.17%   |
| Malaysia    | 1         | 2.17%   |
| France      | 1         | 2.17%   |
| Finland     | 1         | 2.17%   |
| Czechia     | 1         | 2.17%   |
| Belarus     | 1         | 2.17%   |
| Azerbaijan  | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Vienna         | 2         | 4.35%   |
| Zurich         | 1         | 2.17%   |
| Waycross       | 1         | 2.17%   |
| Warsaw         | 1         | 2.17%   |
| Vancouver      | 1         | 2.17%   |
| Uelzen         | 1         | 2.17%   |
| Udine          | 1         | 2.17%   |
| Taggia         | 1         | 2.17%   |
| St Petersburg  | 1         | 2.17%   |
| Saskatoon      | 1         | 2.17%   |
| Saarlouis      | 1         | 2.17%   |
| Roseville      | 1         | 2.17%   |
| Rochester      | 1         | 2.17%   |
| Prague         | 1         | 2.17%   |
| Powder Springs | 1         | 2.17%   |
| Postbauer-Heng | 1         | 2.17%   |
| Portland       | 1         | 2.17%   |
| Ottawa         | 1         | 2.17%   |
| Osasco         | 1         | 2.17%   |
| Mussolente     | 1         | 2.17%   |
| Munich         | 1         | 2.17%   |
| Montreal       | 1         | 2.17%   |
| Minsk          | 1         | 2.17%   |
| Milan          | 1         | 2.17%   |
| Lima           | 1         | 2.17%   |
| Lannion        | 1         | 2.17%   |
| Lahti          | 1         | 2.17%   |
| Kitchener      | 1         | 2.17%   |
| Kent           | 1         | 2.17%   |
| Huercal Overa  | 1         | 2.17%   |
| Graniteville   | 1         | 2.17%   |
| Glendale       | 1         | 2.17%   |
| Gilmer         | 1         | 2.17%   |
| Florence       | 1         | 2.17%   |
| Cyberjaya      | 1         | 2.17%   |
| Colfontaine    | 1         | 2.17%   |
| Cambui         | 1         | 2.17%   |
| Brussels       | 1         | 2.17%   |
| Bratislava     | 1         | 2.17%   |
| Bindlach       | 1         | 2.17%   |
| Berlin         | 1         | 2.17%   |
| Belo Horizonte | 1         | 2.17%   |
| Belgrade       | 1         | 2.17%   |
| Baku           | 1         | 2.17%   |
| Amsterdam      | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 15.94%  |
| WDC                 | 10        | 10     | 14.49%  |
| Crucial             | 7         | 13     | 10.14%  |
| Seagate             | 6         | 7      | 8.7%    |
| Kingston            | 6         | 6      | 8.7%    |
| SK Hynix            | 4         | 4      | 5.8%    |
| Transcend           | 3         | 3      | 4.35%   |
| LITEON              | 3         | 3      | 4.35%   |
| Intel               | 3         | 3      | 4.35%   |
| DOGFISH             | 3         | 3      | 4.35%   |
| Unknown             | 2         | 2      | 2.9%    |
| SanDisk             | 2         | 2      | 2.9%    |
| Toshiba             | 1         | 1      | 1.45%   |
| SABRENT             | 1         | 1      | 1.45%   |
| PNY                 | 1         | 1      | 1.45%   |
| Phison              | 1         | 1      | 1.45%   |
| Netac               | 1         | 1      | 1.45%   |
| Gigabyte Technology | 1         | 1      | 1.45%   |
| GeIL                | 1         | 1      | 1.45%   |
| Fujitsu             | 1         | 1      | 1.45%   |
| Unknown             | 1         | 1      | 1.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 3         | 4.23%   |
| SK Hynix HFM512GDJTNI-82A0A 512GB    | 2         | 2.82%   |
| Samsung SSD 860 EVO 500GB            | 2         | 2.82%   |
| Dogfish SSD 128GB                    | 2         | 2.82%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 2.82%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 1.41%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 1.41%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 1.41%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 1.41%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 1.41%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1.41%   |
| WDC PC SN730 NVMe 1024GB             | 1         | 1.41%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB   | 1         | 1.41%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 1.41%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB | 1         | 1.41%   |
| Unknown SDW32G  32GB                 | 1         | 1.41%   |
| Unknown SD32G  32GB                  | 1         | 1.41%   |
| Transcend TS256GSSD370S 256GB        | 1         | 1.41%   |
| Transcend TS1GSDOM22V 1GB SSD        | 1         | 1.41%   |
| Transcend TS128GMTS800 128GB SSD     | 1         | 1.41%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1.41%   |
| SK Hynix HFM512GD3JX013N 512GB       | 1         | 1.41%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 1.41%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 1.41%   |
| Seagate ST500LM000-1EJ162 500GB      | 1         | 1.41%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 1.41%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 1.41%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1.41%   |
| SanDisk SD8SNAT-256G-1006 256GB SSD  | 1         | 1.41%   |
| SanDisk SD8SN8U-512G-1006 512GB SSD  | 1         | 1.41%   |
| Samsung SSD 980 PRO 1TB              | 1         | 1.41%   |
| Samsung SSD 970 EVO 1TB              | 1         | 1.41%   |
| Samsung SSD 860 EVO M.2 250GB        | 1         | 1.41%   |
| Samsung SSD 860 EVO M.2 1TB          | 1         | 1.41%   |
| Samsung SSD 860 EVO 1TB              | 1         | 1.41%   |
| Samsung SSD 850 EVO 250GB            | 1         | 1.41%   |
| Samsung SSD 840 PRO Series 256GB     | 1         | 1.41%   |
| Samsung PM9A1 NVMe 512GB             | 1         | 1.41%   |
| Samsung MZNLN256HMHQ-00000 256GB SSD | 1         | 1.41%   |
| Samsung HM500JI 500GB                | 1         | 1.41%   |
| SABRENT Disk 1TB                     | 1         | 1.41%   |
| PNY CS900 500GB SSD                  | 1         | 1.41%   |
| Phison ESR512GTLCG-EAC-4 512GB       | 1         | 1.41%   |
| Netac SSD 256GB                      | 1         | 1.41%   |
| LITEON IT LST-16S9G 16GB SSD         | 1         | 1.41%   |
| LITEON CV1-8B512-HP 512GB SSD        | 1         | 1.41%   |
| LITEON CV1-8B256 256GB SSD           | 1         | 1.41%   |
| Kingston SKC2500M8250G 250GB         | 1         | 1.41%   |
| Kingston SA400S37480G 480GB SSD      | 1         | 1.41%   |
| Kingston OM8PCP3512F-AI1 512GB       | 1         | 1.41%   |
| Intel SSDSA2BW120G3H 120GB           | 1         | 1.41%   |
| Intel SSDPEKNW512G8 512GB            | 1         | 1.41%   |
| Intel SSDPEKNU512GZ 512GB            | 1         | 1.41%   |
| Gigabyte GP-GSTFS31256GTND 256GB     | 1         | 1.41%   |
| GeIL R3_128GB SSD                    | 1         | 1.41%   |
| Fujitsu MHT2080AH 80GB               | 1         | 1.41%   |
| DOGFISH SSD 512GB                    | 1         | 1.41%   |
| Crucial CT500P2SSD8 500GB            | 1         | 1.41%   |
| Crucial CT500MX500SSD1 500GB         | 1         | 1.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 7      | 42.86%  |
| WDC                 | 4         | 4      | 28.57%  |
| Toshiba             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| SABRENT             | 1         | 1      | 7.14%   |
| Fujitsu             | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 20.59%  |
| Crucial             | 6         | 11     | 17.65%  |
| Kingston            | 4         | 4      | 11.76%  |
| Transcend           | 3         | 3      | 8.82%   |
| LITEON              | 3         | 3      | 8.82%   |
| Dogfish             | 3         | 3      | 8.82%   |
| SanDisk             | 2         | 2      | 5.88%   |
| WDC                 | 1         | 1      | 2.94%   |
| PNY                 | 1         | 1      | 2.94%   |
| Netac               | 1         | 1      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| Gigabyte Technology | 1         | 1      | 2.94%   |
| GeIL                | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 27        | 40     | 46.55%  |
| NVMe | 14        | 19     | 24.14%  |
| HDD  | 14        | 15     | 24.14%  |
| MMC  | 3         | 3      | 5.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 32        | 54     | 64%     |
| NVMe | 14        | 19     | 28%     |
| MMC  | 3         | 3      | 6%      |
| SAS  | 1         | 1      | 2%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 35     | 65%     |
| 0.51-1.0   | 13        | 19     | 32.5%   |
| 1.01-2.0   | 1         | 1      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 12        | 26.09%  |
| 251-500        | 11        | 23.91%  |
| 501-1000       | 9         | 19.57%  |
| 21-50          | 4         | 8.7%    |
| 1-20           | 3         | 6.52%   |
| 51-100         | 3         | 6.52%   |
| 1001-2000      | 2         | 4.35%   |
| More than 3000 | 1         | 2.17%   |
| 2001-3000      | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 41.3%   |
| 21-50          | 9         | 19.57%  |
| 101-250        | 5         | 10.87%  |
| 51-100         | 5         | 10.87%  |
| 251-500        | 4         | 8.7%    |
| 501-1000       | 2         | 4.35%   |
| More than 3000 | 1         | 2.17%   |
| 1001-2000      | 1         | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 50%     |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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
| Works    | 44        | 71     | 88%     |
| Detected | 4         | 4      | 8%      |
| Malfunc  | 2         | 2      | 4%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 35        | 64.81%  |
| Sandisk                     | 5         | 9.26%   |
| SK Hynix                    | 4         | 7.41%   |
| Samsung Electronics         | 3         | 5.56%   |
| Kingston Technology Company | 2         | 3.7%    |
| Silicon Image               | 1         | 1.85%   |
| Phison Electronics          | 1         | 1.85%   |
| Nvidia                      | 1         | 1.85%   |
| Micron/Crucial Technology   | 1         | 1.85%   |
| AMD                         | 1         | 1.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 10.34%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 8.62%   |
| SK Hynix BC511                                                                 | 2         | 3.45%   |
| Sandisk Non-Volatile memory controller                                         | 2         | 3.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 3.45%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 3.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 3.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 3.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 3.45%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 3.45%   |
| SK Hynix Gold P31 SSD                                                          | 1         | 1.72%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1         | 1.72%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 1.72%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.72%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.72%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 1.72%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.72%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                   | 1         | 1.72%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 1         | 1.72%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.72%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.72%   |
| Kingston Company KC2000 NVMe SSD                                               | 1         | 1.72%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.72%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 1         | 1.72%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 1.72%   |
| Intel SSD 660P Series                                                          | 1         | 1.72%   |
| Intel Non-Volatile memory controller                                           | 1         | 1.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.72%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 1.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.72%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 1.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 30        | 56.6%   |
| NVMe | 14        | 26.42%  |
| IDE  | 5         | 9.43%   |
| RAID | 4         | 7.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 84.78%  |
| AMD    | 7         | 15.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 6.52%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 4.35%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 4.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 4.35%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 4.35%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 4.35%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 2.17%   |
| Intel Pentium M processor 1.80GHz             | 1         | 2.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 2.17%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 2.17%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 2.17%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2.17%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 2.17%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 2.17%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 2.17%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 2.17%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 2.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.17%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 2.17%   |
| Intel Core i5-10500H CPU @ 2.50GHz            | 1         | 2.17%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 2.17%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.17%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.17%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 2.17%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 2.17%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 2.17%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 2.17%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 2.17%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 2.17%   |
| Intel Atom CPU Z3735G @ 1.33GHz               | 1         | 2.17%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 2.17%   |
| Intel 11th Gen Core i9-11980HK @ 2.60GHz      | 1         | 2.17%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 2.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 2.17%   |
| AMD Sempron SI-42                             | 1         | 2.17%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 2.17%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 2.17%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 14        | 30.43%  |
| Intel Core i5        | 11        | 23.91%  |
| AMD Ryzen 7          | 5         | 10.87%  |
| Other                | 4         | 8.7%    |
| Intel Core i3        | 2         | 4.35%   |
| Intel Core 2 Duo     | 2         | 4.35%   |
| Intel Celeron        | 2         | 4.35%   |
| Intel Atom           | 2         | 4.35%   |
| Intel Pentium Silver | 1         | 2.17%   |
| Intel Pentium M      | 1         | 2.17%   |
| AMD Sempron          | 1         | 2.17%   |
| AMD Ryzen 9          | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 17        | 36.96%  |
| 4      | 16        | 34.78%  |
| 8      | 6         | 13.04%  |
| 6      | 3         | 6.52%   |
| 1      | 3         | 6.52%   |
| 14     | 1         | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 46        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 38        | 82.61%  |
| 1      | 8         | 17.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 44        | 95.65%  |
| 32-bit         | 2         | 4.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 5         | 10.87%  |
| 0xa0652    | 3         | 6.52%   |
| 0x406e3    | 3         | 6.52%   |
| 0x0a50000c | 3         | 6.52%   |
| 0x806ea    | 2         | 4.35%   |
| 0x806c1    | 2         | 4.35%   |
| 0x506e3    | 2         | 4.35%   |
| 0x306c3    | 2         | 4.35%   |
| 0x30678    | 2         | 4.35%   |
| 0x206a7    | 2         | 4.35%   |
| 0x20655    | 2         | 4.35%   |
| Unknown    | 2         | 4.35%   |
| 0x906ea    | 1         | 2.17%   |
| 0x906a3    | 1         | 2.17%   |
| 0x806eb    | 1         | 2.17%   |
| 0x806e9    | 1         | 2.17%   |
| 0x806d1    | 1         | 2.17%   |
| 0x706a8    | 1         | 2.17%   |
| 0x706a1    | 1         | 2.17%   |
| 0x6fd      | 1         | 2.17%   |
| 0x6fb      | 1         | 2.17%   |
| 0x6d6      | 1         | 2.17%   |
| 0x106e5    | 1         | 2.17%   |
| 0x106c2    | 1         | 2.17%   |
| 0x0a50000b | 1         | 2.17%   |
| 0x08608103 | 1         | 2.17%   |
| 0x08108102 | 1         | 2.17%   |
| 0x02000057 | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Skylake          | 5         | 10.87%  |
| KabyLake         | 5         | 10.87%  |
| IvyBridge        | 5         | 10.87%  |
| Zen 3            | 4         | 8.7%    |
| Westmere         | 3         | 6.52%   |
| SandyBridge      | 3         | 6.52%   |
| CometLake        | 3         | 6.52%   |
| TigerLake        | 2         | 4.35%   |
| Silvermont       | 2         | 4.35%   |
| Haswell          | 2         | 4.35%   |
| Goldmont plus    | 2         | 4.35%   |
| Core             | 2         | 4.35%   |
| Zen+             | 1         | 2.17%   |
| P6               | 1         | 2.17%   |
| Nehalem          | 1         | 2.17%   |
| K8 & K10 hybrid  | 1         | 2.17%   |
| Icelake          | 1         | 2.17%   |
| Bonnell          | 1         | 2.17%   |
| Alderlake Hybrid | 1         | 2.17%   |
| Unknown          | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 36        | 57.14%  |
| Nvidia | 19        | 30.16%  |
| AMD    | 8         | 12.7%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 7.58%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 3         | 4.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 4.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 4.55%   |
| AMD Cezanne                                                               | 3         | 4.55%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 2         | 3.03%   |
| Intel UHD Graphics 620                                                    | 2         | 3.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 3.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 3.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 3.03%   |
| Intel HD Graphics 530                                                     | 2         | 3.03%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 3.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 3.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 3.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.52%   |
| Nvidia TU117M                                                             | 1         | 1.52%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 1.52%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 1.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.52%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 1.52%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 1.52%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 1         | 1.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 1.52%   |
| Nvidia GF108M [GeForce GT 550M]                                           | 1         | 1.52%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 1.52%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 1.52%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                               | 1         | 1.52%   |
| Nvidia C77 [GeForce 8200M G]                                              | 1         | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 1.52%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                       | 1         | 1.52%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 1.52%   |
| Intel HD Graphics 620                                                     | 1         | 1.52%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 1         | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 1.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.52%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 1         | 1.52%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                 | 1         | 1.52%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]             | 1         | 1.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 1.52%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                | 1         | 1.52%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                  | 1         | 1.52%   |
| AMD Lucienne                                                              | 1         | 1.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 47.83%  |
| Intel + Nvidia | 13        | 28.26%  |
| 1 x Nvidia     | 3         | 6.52%   |
| AMD + Nvidia   | 3         | 6.52%   |
| 1 x AMD        | 3         | 6.52%   |
| 2 x AMD        | 1         | 2.17%   |
| Intel + AMD    | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 35        | 76.09%  |
| Proprietary | 10        | 21.74%  |
| Unknown     | 1         | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 80.43%  |
| 0.01-0.5   | 4         | 8.7%    |
| 0.51-1.0   | 3         | 6.52%   |
| 7.01-8.0   | 1         | 2.17%   |
| 3.01-4.0   | 1         | 2.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 9         | 17.65%  |
| LG Display              | 7         | 13.73%  |
| AU Optronics            | 7         | 13.73%  |
| Samsung Electronics     | 5         | 9.8%    |
| BOE                     | 4         | 7.84%   |
| Sharp                   | 3         | 5.88%   |
| PANDA                   | 3         | 5.88%   |
| Sony                    | 2         | 3.92%   |
| Chi Mei Optoelectronics | 2         | 3.92%   |
| Ancor Communications    | 2         | 3.92%   |
| Philips                 | 1         | 1.96%   |
| Panasonic               | 1         | 1.96%   |
| Lenovo                  | 1         | 1.96%   |
| Hewlett-Packard         | 1         | 1.96%   |
| Goldstar                | 1         | 1.96%   |
| CPT                     | 1         | 1.96%   |
| Apple                   | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 3.92%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 3.92%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 3.92%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 1.96%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 1.96%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 1.96%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 1.96%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 1.96%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 1.96%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 1.96%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 1.96%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 1         | 1.96%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch              | 1         | 1.96%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 1.96%   |
| LG Display LCD Monitor LGD06E2 1920x1080 344x194mm 15.5-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD024D 1366x768 294x166mm 13.3-inch              | 1         | 1.96%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 518x324mm 24.1-inch                 | 1         | 1.96%   |
| Hewlett-Packard LA2306 HWP294B 1920x1080 509x286mm 23.0-inch             | 1         | 1.96%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 1         | 1.96%   |
| CPT LCD Monitor CPT1C21 1366x768 256x144mm 11.6-inch                     | 1         | 1.96%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15D6 1920x1080 344x193mm 15.5-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 1.96%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE0714 1920x1080 344x193mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 1         | 1.96%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch           | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch            | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO123E 1600x900 309x174mm 14.0-inch            | 1         | 1.96%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 1         | 1.96%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch         | 1         | 1.96%   |
| Ancor Communications ASUS VW193S ACI19D4 1440x900 408x255mm 18.9-inch    | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 22        | 46.81%  |
| 1366x768 (WXGA)  | 13        | 27.66%  |
| 3840x2160 (4K)   | 3         | 6.38%   |
| 1600x900 (HD+)   | 2         | 4.26%   |
| 1280x800 (WXGA)  | 2         | 4.26%   |
| 3840x2400        | 1         | 2.13%   |
| 2560x1080        | 1         | 2.13%   |
| 2256x1504        | 1         | 2.13%   |
| 2160x1440        | 1         | 2.13%   |
| 1440x900 (WXGA+) | 1         | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 25        | 49.02%  |
| 13     | 6         | 11.76%  |
| 17     | 4         | 7.84%   |
| 14     | 4         | 7.84%   |
| 24     | 3         | 5.88%   |
| 23     | 3         | 5.88%   |
| 27     | 2         | 3.92%   |
| 11     | 2         | 3.92%   |
| 34     | 1         | 1.96%   |
| 19     | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 56.86%  |
| 501-600     | 8         | 15.69%  |
| 201-300     | 7         | 13.73%  |
| 351-400     | 5         | 9.8%    |
| 701-800     | 1         | 1.96%   |
| 401-500     | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 38        | 82.61%  |
| 16/10 | 5         | 10.87%  |
| 3/2   | 2         | 4.35%   |
| 21/9  | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 49.02%  |
| 81-90          | 8         | 15.69%  |
| 201-250        | 5         | 9.8%    |
| 121-130        | 4         | 7.84%   |
| 71-80          | 2         | 3.92%   |
| 51-60          | 2         | 3.92%   |
| 301-350        | 2         | 3.92%   |
| 351-500        | 1         | 1.96%   |
| 251-300        | 1         | 1.96%   |
| 151-200        | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 40.82%  |
| 51-100        | 12        | 24.49%  |
| 101-120       | 10        | 20.41%  |
| 161-240       | 4         | 8.16%   |
| More than 240 | 3         | 6.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 35        | 76.09%  |
| 2     | 9         | 19.57%  |
| 3     | 1         | 2.17%   |
| 0     | 1         | 2.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 26        | 35.14%  |
| Realtek Semiconductor    | 23        | 31.08%  |
| Qualcomm Atheros         | 11        | 14.86%  |
| Marvell Technology Group | 4         | 5.41%   |
| MEDIATEK                 | 3         | 4.05%   |
| TP-Link                  | 2         | 2.7%    |
| Ralink Technology        | 1         | 1.35%   |
| Nvidia                   | 1         | 1.35%   |
| Dell                     | 1         | 1.35%   |
| Broadcom                 | 1         | 1.35%   |
| ASUSTek Computer         | 1         | 1.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 20        | 22.47%  |
| Intel Wi-Fi 6 AX200                                                            | 4         | 4.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 3         | 3.37%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                  | 3         | 3.37%   |
| Intel Wireless 8260                                                            | 3         | 3.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 2.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 2.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 2.25%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 2.25%   |
| Intel Wireless 7260                                                            | 2         | 2.25%   |
| Intel Ethernet Connection I219-V                                               | 2         | 2.25%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 2.25%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 2.25%   |
| Intel Centrino Advanced-N 6200                                                 | 2         | 2.25%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.25%   |
| TP-Link USB 10/100/1000 LAN                                                    | 1         | 1.12%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1         | 1.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1         | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.12%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 1.12%   |
| Ralink RT2070 Wireless Adapter                                                 | 1         | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 1.12%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 1.12%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.12%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 1.12%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.12%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 1.12%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 1.12%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.12%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.12%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 1.12%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.12%   |
| Intel Wireless 7265                                                            | 1         | 1.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 1.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1         | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 1.12%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 1.12%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 1.12%   |
| Intel Centrino Advanced-N 6235                                                 | 1         | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1         | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 1.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 1         | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 1.12%   |
| Dell F3607gw v2 Mobile Broadband Module                                        | 1         | 1.12%   |
| Broadcom BCM4321 802.11a/b/g/n                                                 | 1         | 1.12%   |
| ASUS 802.11ac NIC                                                              | 1         | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 55.32%  |
| Qualcomm Atheros      | 9         | 19.15%  |
| Realtek Semiconductor | 5         | 10.64%  |
| MEDIATEK              | 3         | 6.38%   |
| TP-Link               | 1         | 2.13%   |
| Ralink Technology     | 1         | 2.13%   |
| Broadcom              | 1         | 2.13%   |
| ASUSTek Computer      | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 4         | 8.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 6.38%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 6.38%   |
| Intel Wireless 8260                                                     | 3         | 6.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 4.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 4.26%   |
| Intel Wireless 8265 / 8275                                              | 2         | 4.26%   |
| Intel Wireless 7260                                                     | 2         | 4.26%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 4.26%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 4.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 2.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 2.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.13%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 2.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 2.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 2.13%   |
| Intel Wireless 7265                                                     | 1         | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 2.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 2.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 2.13%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 2.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.13%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 2.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 2.13%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 2.13%   |
| ASUS 802.11ac NIC                                                       | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 23        | 57.5%   |
| Intel                    | 7         | 17.5%   |
| Qualcomm Atheros         | 4         | 10%     |
| Marvell Technology Group | 4         | 10%     |
| TP-Link                  | 1         | 2.5%    |
| Nvidia                   | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 20        | 48.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 4.88%   |
| Intel Ethernet Connection I219-V                                               | 2         | 4.88%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 4.88%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 4.88%   |
| TP-Link USB 10/100/1000 LAN                                                    | 1         | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 2.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 2.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 2.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 2.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 2.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 2.44%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 2.44%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 2.44%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 2.44%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 2.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 51.81%  |
| Ethernet | 39        | 46.99%  |
| Modem    | 1         | 1.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 68%     |
| Ethernet | 15        | 30%     |
| Modem    | 1         | 2%      |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 37        | 80.43%  |
| 1     | 8         | 17.39%  |
| 0     | 1         | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 76.09%  |
| Yes  | 11        | 23.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 47.37%  |
| Qualcomm Atheros Communications | 4         | 10.53%  |
| Realtek Semiconductor           | 3         | 7.89%   |
| IMC Networks                    | 3         | 7.89%   |
| Foxconn / Hon Hai               | 3         | 7.89%   |
| Cambridge Silicon Radio         | 2         | 5.26%   |
| Lite-On Technology              | 1         | 2.63%   |
| Hewlett-Packard                 | 1         | 2.63%   |
| Dell                            | 1         | 2.63%   |
| ASUSTek Computer                | 1         | 2.63%   |
| Apple                           | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 7         | 18.42%  |
| Intel Bluetooth Device                                                              | 4         | 10.53%  |
| Intel AX200 Bluetooth                                                               | 4         | 10.53%  |
| Realtek Bluetooth Radio                                                             | 3         | 7.89%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 2         | 5.26%   |
| IMC Networks Wireless_Device                                                        | 2         | 5.26%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 5.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 5.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 2.63%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 2.63%   |
| Lite-On Wireless_Device                                                             | 1         | 2.63%   |
| Intel AX210 Bluetooth                                                               | 1         | 2.63%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 2.63%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 2.63%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 2.63%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 2.63%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 2.63%   |
| Apple Bluetooth HCI                                                                 | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 38        | 60.32%  |
| Nvidia              | 14        | 22.22%  |
| AMD                 | 7         | 11.11%  |
| Texas Instruments   | 1         | 1.59%   |
| Plantronics         | 1         | 1.59%   |
| C-Media Electronics | 1         | 1.59%   |
| Unknown             | 1         | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Nvidia Audio device                                                        | 6         | 8.57%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 8.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 8.57%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 8.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 5.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 5.71%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 4.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 2.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.86%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 1.43%   |
| Plantronics BT600                                                          | 1         | 1.43%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.43%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1         | 1.43%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.43%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.43%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.43%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 1.43%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.43%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.43%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1         | 1.43%   |
| C-Media Electronics USB Advanced Audio Device                              | 1         | 1.43%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.43%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1.43%   |
| Unknown                                                                    | 1         | 1.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 12        | 21.82%  |
| Samsung Electronics | 12        | 21.82%  |
| Unknown             | 11        | 20%     |
| Micron Technology   | 5         | 9.09%   |
| Kingston            | 4         | 7.27%   |
| Crucial             | 4         | 7.27%   |
| Smart               | 2         | 3.64%   |
| Unknown (ABCD)      | 1         | 1.82%   |
| PNY                 | 1         | 1.82%   |
| Corsair             | 1         | 1.82%   |
| Avant               | 1         | 1.82%   |
| Unknown             | 1         | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 4.92%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 4.92%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 3.28%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 3.28%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 3.28%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 3.28%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.64%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.64%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.64%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 1.64%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.64%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 1.64%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s            | 1         | 1.64%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 1.64%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.64%   |
| SK Hynix RAM HMT351S6EFR8A 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| SK Hynix RAM HMT351S6AFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.64%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s        | 1         | 1.64%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.64%   |
| SK Hynix RAM HMCG66MEBSA095N 8GB SODIMM 4800MT/s                 | 1         | 1.64%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.64%   |
| SK Hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 1         | 1.64%   |
| Samsung RAM Module 4GB SODIMM DDR2 667MT/s                       | 1         | 1.64%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.64%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 1.64%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.64%   |
| PNY RAM Module 8GB SODIMM DDR3 1333MT/s                          | 1         | 1.64%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 1         | 1.64%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.64%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.64%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 1         | 1.64%   |
| Kingston RAM HP594908-HR1-ELD 2GB SODIMM DDR3 1333MT/s           | 1         | 1.64%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 1.64%   |
| Kingston RAM 99U5428-041.A01LF 4GB SODIMM DDR3 1067MT/s          | 1         | 1.64%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 1.64%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| Crucial RAM CT8G4SFS824A.C8FR 8GB SODIMM DDR4 2133MT/s           | 1         | 1.64%   |
| Crucial RAM BLS8G4S240FSDK.8FBD 8GB SODIMM DDR4 2400MT/s         | 1         | 1.64%   |
| Corsair RAM CMSX32GX4M2A3200C22 16GB SODIMM DDR4 3200MT/s        | 1         | 1.64%   |
| Avant RAM J644GU44J2320NQ 32GB SODIMM DDR4 3200MT/s              | 1         | 1.64%   |
| Unknown                                                          | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 21        | 45.65%  |
| DDR3    | 17        | 36.96%  |
| DDR2    | 3         | 6.52%   |
| SDRAM   | 1         | 2.17%   |
| LPDDR4  | 1         | 2.17%   |
| DRAM    | 1         | 2.17%   |
| DDR     | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 45        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 25        | 48.08%  |
| 4096  | 14        | 26.92%  |
| 2048  | 8         | 15.38%  |
| 1024  | 3         | 5.77%   |
| 32768 | 1         | 1.92%   |
| 16384 | 1         | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 11        | 22.92%  |
| 1600    | 8         | 16.67%  |
| 1333    | 5         | 10.42%  |
| Unknown | 5         | 10.42%  |
| 2400    | 4         | 8.33%   |
| 2133    | 4         | 8.33%   |
| 2667    | 3         | 6.25%   |
| 667     | 3         | 6.25%   |
| 4800    | 1         | 2.08%   |
| 4199    | 1         | 2.08%   |
| 1334    | 1         | 2.08%   |
| 1067    | 1         | 2.08%   |
| 166     | 1         | 2.08%   |

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
| Chicony Electronics                    | 9         | 25%     |
| Acer                                   | 4         | 11.11%  |
| Realtek Semiconductor                  | 3         | 8.33%   |
| Microdia                               | 3         | 8.33%   |
| IMC Networks                           | 3         | 8.33%   |
| Sunplus Innovation Technology          | 2         | 5.56%   |
| Lite-On Technology                     | 2         | 5.56%   |
| Z-Star Microelectronics                | 1         | 2.78%   |
| Suyin                                  | 1         | 2.78%   |
| Silicon Motion                         | 1         | 2.78%   |
| Ricoh                                  | 1         | 2.78%   |
| Quanta                                 | 1         | 2.78%   |
| Primax Electronics                     | 1         | 2.78%   |
| Logitech                               | 1         | 2.78%   |
| Goodong Industry                       | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.78%   |
| 8SSC20F27145V1SR19P0BEK                | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                        | 2         | 5.56%   |
| Acer BisonCam, NB Pro                               | 2         | 5.56%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 2.78%   |
| Suyin Sony Visual Communication Camera              | 1         | 2.78%   |
| Silicon Motion Web Camera                           | 1         | 2.78%   |
| Ricoh USB2.0 Camera                                 | 1         | 2.78%   |
| Realtek USB Camera                                  | 1         | 2.78%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.78%   |
| Realtek Integrated Webcam                           | 1         | 2.78%   |
| Quanta HD User Facing                               | 1         | 2.78%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 2.78%   |
| Microdia Webcam Vitade AF                           | 1         | 2.78%   |
| Microdia WebCam SC-13HDL12639P                      | 1         | 2.78%   |
| Microdia Webcam                                     | 1         | 2.78%   |
| Logitech StreamCam                                  | 1         | 2.78%   |
| Lite-On HP HD Webcam                                | 1         | 2.78%   |
| Lite-On HP HD Camera                                | 1         | 2.78%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                 | 1         | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.78%   |
| IMC Networks Integrated Camera                      | 1         | 2.78%   |
| Goodong Industry USB2.0 HD UVC WebCam               | 1         | 2.78%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 2.78%   |
| Chicony USB 2.0 Camera                              | 1         | 2.78%   |
| Chicony thinkpad t430s camera                       | 1         | 2.78%   |
| Chicony Sony Visual Communication Camera            | 1         | 2.78%   |
| Chicony Lenovo EasyCamera                           | 1         | 2.78%   |
| Chicony Integrated Camera                           | 1         | 2.78%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 2.78%   |
| Chicony HD User Facing                              | 1         | 2.78%   |
| Chicony 2.0M UVC WebCam                             | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.78%   |
| Acer SunplusIT INC. Integrated Camera               | 1         | 2.78%   |
| Acer BisonCam,NB Pro                                | 1         | 2.78%   |
| 8SSC20F27145V1SR19P0BEK Integrated Camera           | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 66.67%  |
| Shenzhen Goodix Technology | 2         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader   | 2         | 33.33%  |
| Validity Sensors VFS 5011 fingerprint sensor | 2         | 33.33%  |
| Shenzhen Goodix  FingerPrint Device          | 2         | 33.33%  |

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
| 0     | 31        | 65.96%  |
| 1     | 14        | 29.79%  |
| 2     | 2         | 4.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 9         | 56.25%  |
| Fingerprint reader | 6         | 37.5%   |
| Chipcard           | 1         | 6.25%   |

