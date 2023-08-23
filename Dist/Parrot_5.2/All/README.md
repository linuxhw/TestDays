Parrot 5.2 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Parrot 5.2.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot_5.2/Desktop/README.md) and [notebooks](/Dist/Parrot_5.2/Notebook/README.md).

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

Total: 46

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-dy2xxx            | Notebook    | [ea4a5ccb1a](https://linux-hardware.org/?probe=ea4a5ccb1a) | Jun 29, 2023 |
| Lenovo        | ThinkPad L520 78595GJ       | Notebook    | [52faa96ad0](https://linux-hardware.org/?probe=52faa96ad0) | Jun 17, 2023 |
| Lenovo        | ThinkPad X230 2325UYW       | Notebook    | [c2165f9183](https://linux-hardware.org/?probe=c2165f9183) | May 29, 2023 |
| Dell          | Latitude 7280               | Notebook    | [c9a41b2795](https://linux-hardware.org/?probe=c9a41b2795) | May 24, 2023 |
| Dell          | Vostro 1550                 | Notebook    | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b4861cf35c](https://linux-hardware.org/?probe=b4861cf35c) | Apr 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | Notebook    | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [0f3f45f8e9](https://linux-hardware.org/?probe=0f3f45f8e9) | Apr 13, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | Notebook    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| Gigabyte      | AORUS 15P KD                | Notebook    | [0b53411753](https://linux-hardware.org/?probe=0b53411753) | Apr 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [04c16989b3](https://linux-hardware.org/?probe=04c16989b3) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [b307524661](https://linux-hardware.org/?probe=b307524661) | Apr 06, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [2f61bfa5a5](https://linux-hardware.org/?probe=2f61bfa5a5) | Apr 04, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [1e81e330e1](https://linux-hardware.org/?probe=1e81e330e1) | Apr 04, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [4145a32920](https://linux-hardware.org/?probe=4145a32920) | Apr 03, 2023 |
| Google        | Lillipup                    | Notebook    | [09292890c9](https://linux-hardware.org/?probe=09292890c9) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9edda5f374](https://linux-hardware.org/?probe=9edda5f374) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c25f99afed](https://linux-hardware.org/?probe=c25f99afed) | Mar 28, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0180776452](https://linux-hardware.org/?probe=0180776452) | Mar 26, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [728805785d](https://linux-hardware.org/?probe=728805785d) | Mar 25, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [35030027f5](https://linux-hardware.org/?probe=35030027f5) | Mar 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [0927eb4ba9](https://linux-hardware.org/?probe=0927eb4ba9) | Mar 17, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6752797fe9](https://linux-hardware.org/?probe=6752797fe9) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [2e0019e450](https://linux-hardware.org/?probe=2e0019e450) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [47f7858a60](https://linux-hardware.org/?probe=47f7858a60) | Mar 07, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [143b06f2d6](https://linux-hardware.org/?probe=143b06f2d6) | Mar 06, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [fe287f85c8](https://linux-hardware.org/?probe=fe287f85c8) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [d3bb7ff642](https://linux-hardware.org/?probe=d3bb7ff642) | Mar 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [3a06e7e211](https://linux-hardware.org/?probe=3a06e7e211) | Mar 05, 2023 |
| ASRock        | B560M-C                     | Desktop     | [a93d64aa2c](https://linux-hardware.org/?probe=a93d64aa2c) | Feb 28, 2023 |
| ASRock        | B560M-C                     | Desktop     | [cbbd0a63d4](https://linux-hardware.org/?probe=cbbd0a63d4) | Feb 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [418b5dd7ff](https://linux-hardware.org/?probe=418b5dd7ff) | Feb 27, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [13355a7d07](https://linux-hardware.org/?probe=13355a7d07) | Feb 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [85bc55a850](https://linux-hardware.org/?probe=85bc55a850) | Feb 26, 2023 |
| Dell          | 0C1R19 A02                  | Desktop     | [42ff2c0844](https://linux-hardware.org/?probe=42ff2c0844) | Feb 22, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Alienware     | 17 R5                       | Notebook    | [1d234f85b4](https://linux-hardware.org/?probe=1d234f85b4) | Feb 22, 2023 |
| Alienware     | 17 R5                       | Notebook    | [5b6b8eee92](https://linux-hardware.org/?probe=5b6b8eee92) | Feb 22, 2023 |
| ASRock        | B560M-C                     | Desktop     | [0641c704e9](https://linux-hardware.org/?probe=0641c704e9) | Feb 20, 2023 |
| Google        | Robo360                     | Notebook    | [e7c85b2410](https://linux-hardware.org/?probe=e7c85b2410) | Feb 09, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 6.0.0-12parrot1-amd64 | 32        | 94.12%  |
| 6.1.0-0.deb11.5-amd64 | 1         | 2.94%   |
| 5.10.92-v8+           | 1         | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0.0   | 32        | 94.12%  |
| 6.1.0   | 1         | 2.94%   |
| 5.10.92 | 1         | 2.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 32        | 94.12%  |
| 6.1     | 1         | 2.94%   |
| 5.10    | 1         | 2.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 33        | 97.06%  |
| aarch64 | 1         | 2.94%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| MATE | 30        | 88.24%  |
| XFCE | 2         | 5.88%   |
| KDE5 | 2         | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 33        | 97.06%  |
| Tty  | 1         | 2.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 23        | 67.65%  |
| Unknown | 10        | 29.41%  |
| SDDM    | 1         | 2.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 19        | 55.88%  |
| en_IN   | 3         | 8.82%   |
| en_AU   | 3         | 8.82%   |
| tr_TR   | 1         | 2.94%   |
| pl_PL   | 1         | 2.94%   |
| es_ES   | 1         | 2.94%   |
| es_AR   | 1         | 2.94%   |
| en_ZM   | 1         | 2.94%   |
| en_GB   | 1         | 2.94%   |
| de_DE   | 1         | 2.94%   |
| cs_CZ   | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 20        | 58.82%  |
| BIOS | 14        | 41.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 30        | 88.24%  |
| Ext4    | 2         | 5.88%   |
| Xfs     | 1         | 2.94%   |
| Overlay | 1         | 2.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 20        | 58.82%  |
| Unknown | 10        | 29.41%  |
| MBR     | 4         | 11.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 91.18%  |
| Yes       | 3         | 8.82%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 23        | 67.65%  |
| Yes       | 11        | 32.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 9         | 26.47%  |
| Hewlett-Packard         | 4         | 11.76%  |
| Dell                    | 4         | 11.76%  |
| MSI                     | 3         | 8.82%   |
| Gigabyte Technology     | 3         | 8.82%   |
| ASUSTek Computer        | 3         | 8.82%   |
| Acer                    | 2         | 5.88%   |
| Raspberry Pi Foundation | 1         | 2.94%   |
| Pegatron                | 1         | 2.94%   |
| Google                  | 1         | 2.94%   |
| ASRock                  | 1         | 2.94%   |
| Apple                   | 1         | 2.94%   |
| Alienware               | 1         | 2.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| RPi Raspberry Pi 4 Model B Rev 1.5                  | 1         | 2.94%   |
| Pegatron 520-1030a                                  | 1         | 2.94%   |
| MSI MS-7917                                         | 1         | 2.94%   |
| MSI MS-7623                                         | 1         | 2.94%   |
| MSI Katana GF66 12UC                                | 1         | 2.94%   |
| Lenovo ThinkPad X230 2325UYW                        | 1         | 2.94%   |
| Lenovo ThinkPad P15v Gen 3 21D8CTO1WW               | 1         | 2.94%   |
| Lenovo ThinkPad P14s Gen 3 21AKCTO1WW               | 1         | 2.94%   |
| Lenovo ThinkPad L520 78595GJ                        | 1         | 2.94%   |
| Lenovo ThinkPad L15 Gen 3 21C3CTO1WW                | 1         | 2.94%   |
| Lenovo ThinkPad E460 20ETA05KAU                     | 1         | 2.94%   |
| Lenovo ThinkPad E15 Gen 4 21ED003YUS                | 1         | 2.94%   |
| Lenovo Legion 5 15ACH6 82JW                         | 1         | 2.94%   |
| Lenovo IdeaPad 5 15IAL7 82SF                        | 1         | 2.94%   |
| HP ZBook Firefly 15.6 inch G8 Mobile Workstation PC | 1         | 2.94%   |
| HP ZBook Firefly 14 inch G9 Mobile Workstation PC   | 1         | 2.94%   |
| HP ProBook 4540s                                    | 1         | 2.94%   |
| HP Pavilion 15                                      | 1         | 2.94%   |
| Google Lillipup                                     | 1         | 2.94%   |
| Gigabyte H61M-S2PV                                  | 1         | 2.94%   |
| Gigabyte B450 AORUS ELITE                           | 1         | 2.94%   |
| Gigabyte AORUS 15P KD                               | 1         | 2.94%   |
| Dell Vostro 1550                                    | 1         | 2.94%   |
| Dell OptiPlex 7070                                  | 1         | 2.94%   |
| Dell Latitude 7280                                  | 1         | 2.94%   |
| Dell Inspiron 3421                                  | 1         | 2.94%   |
| ASUS X510UAR                                        | 1         | 2.94%   |
| ASUS VivoBook_ASUSLaptop X712DA_M712DA              | 1         | 2.94%   |
| ASUS PRIME X399-A                                   | 1         | 2.94%   |
| ASRock B560M-C                                      | 1         | 2.94%   |
| Apple iMac19,2                                      | 1         | 2.94%   |
| Alienware 17 R5                                     | 1         | 2.94%   |
| Acer Extensa 215-54                                 | 1         | 2.94%   |
| Acer Aspire E5-575                                  | 1         | 2.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 7         | 20.59%  |
| HP ZBook           | 2         | 5.88%   |
| RPi Raspberry      | 1         | 2.94%   |
| Pegatron 520-1030a | 1         | 2.94%   |
| MSI MS-7917        | 1         | 2.94%   |
| MSI MS-7623        | 1         | 2.94%   |
| MSI Katana         | 1         | 2.94%   |
| Lenovo Legion      | 1         | 2.94%   |
| Lenovo IdeaPad     | 1         | 2.94%   |
| HP ProBook         | 1         | 2.94%   |
| HP Pavilion        | 1         | 2.94%   |
| Google Lillipup    | 1         | 2.94%   |
| Gigabyte H61M-S2PV | 1         | 2.94%   |
| Gigabyte B450      | 1         | 2.94%   |
| Gigabyte AORUS     | 1         | 2.94%   |
| Dell Vostro        | 1         | 2.94%   |
| Dell OptiPlex      | 1         | 2.94%   |
| Dell Latitude      | 1         | 2.94%   |
| Dell Inspiron      | 1         | 2.94%   |
| ASUS X510UAR       | 1         | 2.94%   |
| ASUS VivoBook      | 1         | 2.94%   |
| ASUS PRIME         | 1         | 2.94%   |
| ASRock B560M-C     | 1         | 2.94%   |
| Apple iMac19       | 1         | 2.94%   |
| Alienware 17       | 1         | 2.94%   |
| Acer Extensa       | 1         | 2.94%   |
| Acer Aspire        | 1         | 2.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 7         | 20.59%  |
| 2012    | 5         | 14.71%  |
| 2021    | 4         | 11.76%  |
| 2020    | 3         | 8.82%   |
| 2018    | 2         | 5.88%   |
| 2017    | 2         | 5.88%   |
| 2016    | 2         | 5.88%   |
| 2014    | 2         | 5.88%   |
| 2023    | 1         | 2.94%   |
| 2019    | 1         | 2.94%   |
| 2015    | 1         | 2.94%   |
| 2013    | 1         | 2.94%   |
| 2011    | 1         | 2.94%   |
| 2010    | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 24        | 70.59%  |
| Desktop        | 8         | 23.53%  |
| System on chip | 1         | 2.94%   |
| All in one     | 1         | 2.94%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 34        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 33        | 97.06%  |
| Yes  | 1         | 2.94%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 8         | 23.53%  |
| 16.01-24.0  | 8         | 23.53%  |
| 3.01-4.0    | 6         | 17.65%  |
| 32.01-64.0  | 5         | 14.71%  |
| 8.01-16.0   | 4         | 11.76%  |
| 64.01-256.0 | 2         | 5.88%   |
| 1.01-2.0    | 1         | 2.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 14        | 41.18%  |
| 4.01-8.0  | 8         | 23.53%  |
| 3.01-4.0  | 5         | 14.71%  |
| 1.01-2.0  | 3         | 8.82%   |
| 0.51-1.0  | 2         | 5.88%   |
| 8.01-16.0 | 1         | 2.94%   |
| 0.01-0.5  | 1         | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 19        | 55.88%  |
| 2      | 14        | 41.18%  |
| 0      | 1         | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 76.47%  |
| Yes       | 8         | 23.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 88.24%  |
| No        | 4         | 11.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 94.12%  |
| No        | 2         | 5.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 55.88%  |
| No        | 15        | 44.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| USA        | 12        | 35.29%  |
| India      | 3         | 8.82%   |
| Australia  | 3         | 8.82%   |
| Germany    | 2         | 5.88%   |
| Zambia     | 1         | 2.94%   |
| UK         | 1         | 2.94%   |
| Turkey     | 1         | 2.94%   |
| Spain      | 1         | 2.94%   |
| Russia     | 1         | 2.94%   |
| Poland     | 1         | 2.94%   |
| Pakistan   | 1         | 2.94%   |
| Namibia    | 1         | 2.94%   |
| Mongolia   | 1         | 2.94%   |
| Czechia    | 1         | 2.94%   |
| Brazil     | 1         | 2.94%   |
| Bangladesh | 1         | 2.94%   |
| Argentina  | 1         | 2.94%   |
| Algeria    | 1         | 2.94%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Windhoek         | 1         | 2.94%   |
| Ulan Bator       | 1         | 2.94%   |
| Tecumseh         | 1         | 2.94%   |
| Sydney           | 1         | 2.94%   |
| Skikda           | 1         | 2.94%   |
| Simpsonville     | 1         | 2.94%   |
| Seattle          | 1         | 2.94%   |
| Rostov-on-Don    | 1         | 2.94%   |
| Reading          | 1         | 2.94%   |
| Rawalpindi       | 1         | 2.94%   |
| Prague           | 1         | 2.94%   |
| Mercedes         | 1         | 2.94%   |
| Lusaka           | 1         | 2.94%   |
| Lochow           | 1         | 2.94%   |
| León            | 1         | 2.94%   |
| Leland           | 1         | 2.94%   |
| Lake Forest      | 1         | 2.94%   |
| Houston          | 1         | 2.94%   |
| Hamburg          | 1         | 2.94%   |
| Geneva           | 1         | 2.94%   |
| Fortaleza        | 1         | 2.94%   |
| Fernandina Beach | 1         | 2.94%   |
| Eugene           | 1         | 2.94%   |
| Dhaka            | 1         | 2.94%   |
| Delhi            | 1         | 2.94%   |
| Chandigarh       | 1         | 2.94%   |
| Canberra         | 1         | 2.94%   |
| Bursa            | 1         | 2.94%   |
| Brisbane         | 1         | 2.94%   |
| Brent            | 1         | 2.94%   |
| Bettingen        | 1         | 2.94%   |
| Bankura          | 1         | 2.94%   |
| Andover          | 1         | 2.94%   |
| Anchorage        | 1         | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 8         | 10     | 17.39%  |
| Seagate                     | 7         | 8      | 15.22%  |
| Kingston                    | 4         | 4      | 8.7%    |
| WDC                         | 3         | 3      | 6.52%   |
| Sandisk                     | 3         | 4      | 6.52%   |
| Unknown                     | 2         | 2      | 4.35%   |
| SK hynix                    | 2         | 2      | 4.35%   |
| Micron Technology           | 2         | 2      | 4.35%   |
| KIOXIA                      | 2         | 2      | 4.35%   |
| HGST                        | 2         | 2      | 4.35%   |
| Unknown (583)               | 1         | 1      | 2.17%   |
| Toshiba                     | 1         | 1      | 2.17%   |
| Phison                      | 1         | 1      | 2.17%   |
| Lexar                       | 1         | 1      | 2.17%   |
| Kingston Technology Company | 1         | 1      | 2.17%   |
| KingFast                    | 1         | 1      | 2.17%   |
| Hitachi                     | 1         | 1      | 2.17%   |
| Hewlett-Packard             | 1         | 1      | 2.17%   |
| GOODRAM                     | 1         | 1      | 2.17%   |
| Apple                       | 1         | 1      | 2.17%   |
| Apacer                      | 1         | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WDS500G2B0B-00YS70 500GB SSD        | 2         | 4.17%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 4.17%   |
| WDC WD6400BPVT-60HXZT3 640GB            | 1         | 2.08%   |
| Unknown SD16G  32GB                     | 1         | 2.08%   |
| Unknown HBG4a2  32GB                    | 1         | 2.08%   |
| Unknown (583) Disk 2TB                  | 1         | 2.08%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 2.08%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB    | 1         | 2.08%   |
| SK hynix BC511 512GB                    | 1         | 2.08%   |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 2.08%   |
| Seagate ST380215AS 80GB                 | 1         | 2.08%   |
| Seagate ST3802110A 80GB                 | 1         | 2.08%   |
| Seagate ST2000DM008-2FR102 2TB          | 1         | 2.08%   |
| Seagate BUP Slim BK 2TB                 | 1         | 2.08%   |
| Seagate Backup+ Hub BK 8TB              | 1         | 2.08%   |
| Sandisk WD_BLACK SN770 500GB            | 1         | 2.08%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD     | 1         | 2.08%   |
| SanDisk NVMe SSD Drive 500GB            | 1         | 2.08%   |
| SanDisk NVMe SSD Drive 1TB              | 1         | 2.08%   |
| Samsung SSD 980 1TB                     | 1         | 2.08%   |
| Samsung SSD 970 EVO Plus 1TB            | 1         | 2.08%   |
| Samsung SSD 970 EVO 1TB                 | 1         | 2.08%   |
| Samsung MZVLQ256HBJD-00BH1 256GB        | 1         | 2.08%   |
| Samsung MZVL2512HCJQ-00BL7 512GB        | 1         | 2.08%   |
| Samsung MZVL2512HCJQ-00B00 512GB        | 1         | 2.08%   |
| Samsung MZAL4512HBLU-00BL2 512GB        | 1         | 2.08%   |
| Samsung MZ7TY256HDHP-000L7 256GB SSD    | 1         | 2.08%   |
| Phison Dash Pro 2TB                     | 1         | 2.08%   |
| Micron MTFDKCD1T0TFK 1TB                | 1         | 2.08%   |
| Micron 2450_MTFDKBA1T0TFK 1TB           | 1         | 2.08%   |
| Lexar SSD NS100 512GB                   | 1         | 2.08%   |
| KIOXIA KXG60ZNV1T02 1TB                 | 1         | 2.08%   |
| KIOXIA KBG5AZNT512G LA 512GB            | 1         | 2.08%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB | 1         | 2.08%   |
| Kingston SNVS500G 500GB                 | 1         | 2.08%   |
| Kingston SNV2S500G 500GB                | 1         | 2.08%   |
| Kingston OM8PCP3512F-AB 512GB           | 1         | 2.08%   |
| Kingston A400 960G SSD                  | 1         | 2.08%   |
| KingFast Disk 256GB SSD                 | 1         | 2.08%   |
| Hitachi HUA722020ALA331 2TB             | 1         | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 8      | 58.33%  |
| HGST    | 2         | 2      | 16.67%  |
| WDC     | 1         | 1      | 8.33%   |
| Toshiba | 1         | 1      | 8.33%   |
| Hitachi | 1         | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 20%     |
| SanDisk             | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Lexar               | 1         | 1      | 10%     |
| Kingston            | 1         | 1      | 10%     |
| KingFast            | 1         | 1      | 10%     |
| Hewlett-Packard     | 1         | 1      | 10%     |
| GOODRAM             | 1         | 1      | 10%     |
| Apacer              | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 19        | 25     | 44.19%  |
| HDD  | 12        | 13     | 27.91%  |
| SSD  | 10        | 10     | 23.26%  |
| MMC  | 2         | 2      | 4.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 19        | 24     | 45.24%  |
| SATA | 17        | 20     | 40.48%  |
| SAS  | 4         | 4      | 9.52%   |
| MMC  | 2         | 2      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 13     | 52.38%  |
| 0.51-1.0   | 6         | 6      | 28.57%  |
| 1.01-2.0   | 3         | 3      | 14.29%  |
| 4.01-10.0  | 1         | 1      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 7         | 20.59%  |
| 1001-2000      | 6         | 17.65%  |
| 251-500        | 5         | 14.71%  |
| 101-250        | 5         | 14.71%  |
| Unknown        | 4         | 11.76%  |
| More than 3000 | 2         | 5.88%   |
| 1-20           | 2         | 5.88%   |
| 21-50          | 1         | 2.94%   |
| 2001-3000      | 1         | 2.94%   |
| 51-100         | 1         | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 11        | 32.35%  |
| 51-100         | 6         | 17.65%  |
| 1-20           | 5         | 14.71%  |
| Unknown        | 4         | 11.76%  |
| 101-250        | 3         | 8.82%   |
| More than 3000 | 1         | 2.94%   |
| 251-500        | 1         | 2.94%   |
| 2001-3000      | 1         | 2.94%   |
| 501-1000       | 1         | 2.94%   |
| 0              | 1         | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 25%     |
| Seagate ST380215AS 80GB             | 1         | 1      | 25%     |
| Seagate ST3802110A 80GB             | 1         | 1      | 25%     |
| Hewlett-Packard SSD S700 Pro 1TB    | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 2         | 3      | 66.67%  |
| Hewlett-Packard | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 3      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 20        | 26     | 52.63%  |
| Detected | 15        | 20     | 39.47%  |
| Malfunc  | 3         | 4      | 7.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 20        | 41.67%  |
| Samsung Electronics          | 8         | 16.67%  |
| AMD                          | 6         | 12.5%   |
| Kingston Technology Company  | 4         | 8.33%   |
| SK hynix                     | 2         | 4.17%   |
| SanDisk                      | 2         | 4.17%   |
| Micron Technology            | 2         | 4.17%   |
| Toshiba America Info Systems | 1         | 2.08%   |
| Phison Electronics           | 1         | 2.08%   |
| KIOXIA                       | 1         | 2.08%   |
| ASMedia Technology           | 1         | 2.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 7.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4         | 7.69%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 2         | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 3.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 3.85%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 3.85%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                             | 2         | 3.85%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 3.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 3.85%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 2         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 3.85%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 1.92%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1         | 1.92%   |
| SK hynix BC511 NVMe SSD                                                                 | 1         | 1.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 1.92%   |
| Samsung NVMe SSD Controller PM9B1                                                       | 1         | 1.92%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 1.92%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                              | 1         | 1.92%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 1.92%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                           | 1         | 1.92%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1         | 1.92%   |
| Kingston Company NVMe Controller                                                        | 1         | 1.92%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 1         | 1.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 1.92%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.92%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 1.92%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1         | 1.92%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 24        | 51.06%  |
| NVMe | 19        | 40.43%  |
| RAID | 2         | 4.26%   |
| IDE  | 2         | 4.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 26        | 76.47%  |
| AMD    | 7         | 20.59%  |
| ARM    | 1         | 2.94%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H                  | 2         | 5.88%   |
| Intel Pentium CPU G620 @ 2.60GHz               | 1         | 2.94%   |
| Intel Core i9-10900F CPU @ 2.80GHz             | 1         | 2.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1         | 2.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz              | 1         | 2.94%   |
| Intel Core i5-9500T CPU @ 2.20GHz              | 1         | 2.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz              | 1         | 2.94%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 1         | 2.94%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 1         | 2.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 2.94%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 1         | 2.94%   |
| Intel Core i3-8100 CPU @ 3.60GHz               | 1         | 2.94%   |
| Intel Core i3-6100U CPU @ 2.30GHz              | 1         | 2.94%   |
| Intel Core i3-3217U CPU @ 1.80GHz              | 1         | 2.94%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 1         | 2.94%   |
| Intel Core i3-2350M CPU @ 2.30GHz              | 1         | 2.94%   |
| Intel Core i3-2310M CPU @ 2.10GHz              | 1         | 2.94%   |
| Intel 12th Gen Core i7-1265U                   | 1         | 2.94%   |
| Intel 12th Gen Core i7-1260P                   | 1         | 2.94%   |
| Intel 12th Gen Core i7-1255U                   | 1         | 2.94%   |
| Intel 12th Gen Core i5-1235U                   | 1         | 2.94%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 1         | 2.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 2.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 1         | 2.94%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz        | 1         | 2.94%   |
| ARM Processor                                  | 1         | 2.94%   |
| AMD Sempron 145 Processor                      | 1         | 2.94%   |
| AMD Ryzen Threadripper 2950X 16-Core Processor | 1         | 2.94%   |
| AMD Ryzen 7 5800H with Radeon Graphics         | 1         | 2.94%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx  | 1         | 2.94%   |
| AMD Ryzen 5 5625U with Radeon Graphics         | 1         | 2.94%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1         | 2.94%   |
| AMD A6-3600 APU with Radeon HD Graphics        | 1         | 2.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Other                  | 11        | 32.35%  |
| Intel Core i5          | 6         | 17.65%  |
| Intel Core i3          | 6         | 17.65%  |
| Intel Core i7          | 2         | 5.88%   |
| AMD Ryzen 7            | 2         | 5.88%   |
| AMD Ryzen 5            | 2         | 5.88%   |
| Intel Pentium          | 1         | 2.94%   |
| Intel Core i9          | 1         | 2.94%   |
| AMD Sempron            | 1         | 2.94%   |
| AMD Ryzen Threadripper | 1         | 2.94%   |
| AMD A6                 | 1         | 2.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 11        | 32.35%  |
| 4      | 8         | 23.53%  |
| 10     | 4         | 11.76%  |
| 6      | 4         | 11.76%  |
| 14     | 2         | 5.88%   |
| 8      | 2         | 5.88%   |
| 16     | 1         | 2.94%   |
| 12     | 1         | 2.94%   |
| 1      | 1         | 2.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 21        | 61.76%  |
| 1      | 13        | 38.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 34        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 32.35%  |
| 0x906a4    | 3         | 8.82%   |
| 0x906a3    | 3         | 8.82%   |
| 0x806c1    | 2         | 5.88%   |
| 0x306a9    | 2         | 5.88%   |
| 0x0a50000c | 2         | 5.88%   |
| 0xa0655    | 1         | 2.94%   |
| 0x906eb    | 1         | 2.94%   |
| 0x906ea    | 1         | 2.94%   |
| 0x806ea    | 1         | 2.94%   |
| 0x806e9    | 1         | 2.94%   |
| 0x806d1    | 1         | 2.94%   |
| 0x406e3    | 1         | 2.94%   |
| 0x206a7    | 1         | 2.94%   |
| 0x0a201204 | 1         | 2.94%   |
| 0x08108102 | 1         | 2.94%   |
| 0x010000c8 | 1         | 2.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Alderlake Hybrid | 6         | 17.65%  |
| KabyLake         | 5         | 14.71%  |
| SandyBridge      | 4         | 11.76%  |
| Zen 3            | 3         | 8.82%   |
| TigerLake        | 3         | 8.82%   |
| IvyBridge        | 3         | 8.82%   |
| Zen+             | 2         | 5.88%   |
| Skylake          | 2         | 5.88%   |
| K10 Llano        | 1         | 2.94%   |
| K10              | 1         | 2.94%   |
| Icelake          | 1         | 2.94%   |
| Haswell          | 1         | 2.94%   |
| CometLake        | 1         | 2.94%   |
| Unknown          | 1         | 2.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 24        | 55.81%  |
| Nvidia | 11        | 25.58%  |
| AMD    | 8         | 18.6%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 4         | 9.3%    |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 3         | 6.98%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 3         | 6.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 6.98%   |
| Nvidia TU116 [GeForce GTX 1660]                                                       | 2         | 4.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 4.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 4.65%   |
| Nvidia TU117GLM [T600 Laptop GPU]                                                     | 1         | 2.33%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                                     | 1         | 2.33%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                  | 1         | 2.33%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                              | 1         | 2.33%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 2.33%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                           | 1         | 2.33%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 1         | 2.33%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                        | 1         | 2.33%   |
| Nvidia GA104 [GeForce RTX 3070]                                                       | 1         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 2.33%   |
| Intel UHD Graphics 620                                                                | 1         | 2.33%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 2.33%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 1         | 2.33%   |
| Intel HD Graphics 620                                                                 | 1         | 2.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 1         | 2.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 2.33%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.33%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 1         | 2.33%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 2.33%   |
| AMD RS780L [Radeon 3000]                                                              | 1         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 2.33%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                    | 1         | 2.33%   |
| AMD Barcelo                                                                           | 1         | 2.33%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 14        | 41.18%  |
| 1 x Nvidia     | 6         | 17.65%  |
| Intel + Nvidia | 5         | 14.71%  |
| 1 x AMD        | 5         | 14.71%  |
| Intel + AMD    | 3         | 8.82%   |
| Other          | 1         | 2.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 31        | 91.18%  |
| Proprietary | 2         | 5.88%   |
| Unknown     | 1         | 2.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 61.76%  |
| 3.01-4.0   | 5         | 14.71%  |
| 5.01-6.0   | 2         | 5.88%   |
| 1.01-2.0   | 2         | 5.88%   |
| 0.51-1.0   | 2         | 5.88%   |
| 7.01-8.0   | 1         | 2.94%   |
| 0.01-0.5   | 1         | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 7         | 18.42%  |
| AU Optronics         | 5         | 13.16%  |
| BOE                  | 4         | 10.53%  |
| Chimei Innolux       | 3         | 7.89%   |
| Samsung Electronics  | 2         | 5.26%   |
| Hewlett-Packard      | 2         | 5.26%   |
| Dell                 | 2         | 5.26%   |
| Ancor Communications | 2         | 5.26%   |
| Acer                 | 2         | 5.26%   |
| VIZ                  | 1         | 2.63%   |
| Sharp                | 1         | 2.63%   |
| Pixio                | 1         | 2.63%   |
| LG Electronics       | 1         | 2.63%   |
| Goldstar             | 1         | 2.63%   |
| Element              | 1         | 2.63%   |
| CSO                  | 1         | 2.63%   |
| BOE Technology Group | 1         | 2.63%   |
| Apple                | 1         | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                | 2         | 5.26%   |
| VIZ LCD Monitor VA19L HDTV10T                                        | 1         | 2.63%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch              | 1         | 2.63%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch   | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch | 1         | 2.63%   |
| Pixio EULCD-2400DFE WAM2380 1920x1080 530x290mm 23.8-inch            | 1         | 2.63%   |
| LG Electronics LCD Monitor LG HDR WFHD 2560x1080                     | 1         | 2.63%   |
| LG Display LCD Monitor LGD06E4 1920x1080 344x194mm 15.5-inch         | 1         | 2.63%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 2.63%   |
| LG Display LCD Monitor LGD0505 1366x768 344x194mm 15.5-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch          | 1         | 2.63%   |
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch     | 1         | 2.63%   |
| Hewlett-Packard LA1956x HWP3021 1280x1024 376x301mm 19.0-inch        | 1         | 2.63%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 1         | 2.63%   |
| Element ELEFW328C ELE3553 1360x768 640x384mm 29.4-inch               | 1         | 2.63%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                    | 1         | 2.63%   |
| Dell P2314T DEL409E 1920x1080 509x286mm 23.0-inch                    | 1         | 2.63%   |
| CSO LCD Monitor CSO1506 1920x1080 344x194mm 15.5-inch                | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch      | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15AA 1366x768 344x194mm 15.5-inch      | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 1         | 2.63%   |
| BOE Technology Group LCD Monitor 3200x1080                           | 1         | 2.63%   |
| BOE LCD Monitor BOE0AB0 1920x1080 344x194mm 15.5-inch                | 1         | 2.63%   |
| BOE LCD Monitor BOE0A64 1920x1080 344x194mm 15.5-inch                | 1         | 2.63%   |
| AU Optronics LCD Monitor AUOE3A0 3840x2400 301x188mm 14.0-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO662D 1920x1080 293x165mm 13.2-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO5A99 1920x1200 301x188mm 14.0-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO1496 2560x1440 382x214mm 17.2-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 1         | 2.63%   |
| Apple iMac APPAE19 3840x2160 475x267mm 21.5-inch                     | 1         | 2.63%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch     | 1         | 2.63%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch     | 1         | 2.63%   |
| Acer H193HQV ACR01B8 1366x768 410x230mm 18.5-inch                    | 1         | 2.63%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                    | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 15        | 40.54%  |
| 1366x768 (WXGA)   | 10        | 27.03%  |
| 3840x2160 (4K)    | 2         | 5.41%   |
| 1920x1200 (WUXGA) | 2         | 5.41%   |
| 3840x2400         | 1         | 2.7%    |
| 3200x1080         | 1         | 2.7%    |
| 2560x1440 (QHD)   | 1         | 2.7%    |
| 2560x1080         | 1         | 2.7%    |
| 1600x900 (HD+)    | 1         | 2.7%    |
| 1360x768          | 1         | 2.7%    |
| 1280x1024 (SXGA)  | 1         | 2.7%    |
| Unknown           | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 14        | 38.89%  |
| 24      | 3         | 8.33%   |
| 18      | 3         | 8.33%   |
| 14      | 3         | 8.33%   |
| 23      | 2         | 5.56%   |
| 17      | 2         | 5.56%   |
| 12      | 2         | 5.56%   |
| Unknown | 2         | 5.56%   |
| 32      | 1         | 2.78%   |
| 27      | 1         | 2.78%   |
| 21      | 1         | 2.78%   |
| 19      | 1         | 2.78%   |
| 13      | 1         | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 48.57%  |
| 501-600     | 6         | 17.14%  |
| 401-500     | 3         | 8.57%   |
| 351-400     | 3         | 8.57%   |
| 201-300     | 3         | 8.57%   |
| Unknown     | 2         | 5.71%   |
| 701-800     | 1         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 27        | 81.82%  |
| 16/10   | 3         | 9.09%   |
| Unknown | 2         | 6.06%   |
| 5/4     | 1         | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 38.89%  |
| 201-250        | 4         | 11.11%  |
| 81-90          | 3         | 8.33%   |
| 141-150        | 3         | 8.33%   |
| 61-70          | 2         | 5.56%   |
| 151-200        | 2         | 5.56%   |
| 121-130        | 2         | 5.56%   |
| Unknown        | 2         | 5.56%   |
| 71-80          | 1         | 2.78%   |
| 351-500        | 1         | 2.78%   |
| 301-350        | 1         | 2.78%   |
| 251-300        | 1         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 11        | 30.56%  |
| 51-100        | 10        | 27.78%  |
| 101-120       | 7         | 19.44%  |
| 161-240       | 5         | 13.89%  |
| Unknown       | 2         | 5.56%   |
| More than 240 | 1         | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 28        | 82.35%  |
| 2     | 5         | 14.71%  |
| 0     | 1         | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 19        | 32.76%  |
| Intel                 | 18        | 31.03%  |
| Qualcomm Atheros      | 7         | 12.07%  |
| OPPO Electronics      | 3         | 5.17%   |
| Ralink                | 2         | 3.45%   |
| Xiaomi                | 1         | 1.72%   |
| Ralink Technology     | 1         | 1.72%   |
| Qualcomm              | 1         | 1.72%   |
| NetGear               | 1         | 1.72%   |
| Mercucys              | 1         | 1.72%   |
| MediaTek              | 1         | 1.72%   |
| Google                | 1         | 1.72%   |
| Broadcom Limited      | 1         | 1.72%   |
| Broadcom              | 1         | 1.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 10        | 14.49%  |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 6         | 8.7%    |
| Intel Wi-Fi 6 AX201                                                                           | 3         | 4.35%   |
| Intel Ethernet Connection (16) I219-V                                                         | 3         | 4.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2         | 2.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2         | 2.9%    |
| OPPO SM6375-QRD _SN:0AF7C3B5                                                                  | 2         | 2.9%    |
| Intel Wireless 8265 / 8275                                                                    | 2         | 2.9%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                          | 1         | 1.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.45%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.45%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1         | 1.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 1.45%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1         | 1.45%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.45%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.45%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.45%   |
| Qualcomm SM6150-IDP _SN:488AC473                                                              | 1         | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1         | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1         | 1.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1         | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 1         | 1.45%   |
| OPPO SM6375-QRD _SN:F4A23F05                                                                  | 1         | 1.45%   |
| NetGear A6210                                                                                 | 1         | 1.45%   |
| Mercucys 802.11n NIC                                                                          | 1         | 1.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 1.45%   |
| Intel Wireless 8260                                                                           | 1         | 1.45%   |
| Intel Wireless 7265                                                                           | 1         | 1.45%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 1.45%   |
| Intel I211 Gigabit Network Connection                                                         | 1         | 1.45%   |
| Intel Ethernet Connection I219-V                                                              | 1         | 1.45%   |
| Intel Ethernet Connection (7) I219-LM                                                         | 1         | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                                                         | 1         | 1.45%   |
| Intel Ethernet Connection (11) I219-V                                                         | 1         | 1.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 45.71%  |
| Realtek Semiconductor | 6         | 17.14%  |
| Qualcomm Atheros      | 5         | 14.29%  |
| Ralink                | 2         | 5.71%   |
| Ralink Technology     | 1         | 2.86%   |
| NetGear               | 1         | 2.86%   |
| Mercucys              | 1         | 2.86%   |
| MediaTek              | 1         | 2.86%   |
| Broadcom Limited      | 1         | 2.86%   |
| Broadcom              | 1         | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 6         | 17.14%  |
| Intel Wi-Fi 6 AX201                                                                           | 3         | 8.57%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 5.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 2.86%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 2.86%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1         | 2.86%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 2.86%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 2.86%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 2.86%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 2.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1         | 2.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 2.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 2.86%   |
| NetGear A6210                                                                                 | 1         | 2.86%   |
| Mercucys 802.11n NIC                                                                          | 1         | 2.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 2.86%   |
| Intel Wireless 8260                                                                           | 1         | 2.86%   |
| Intel Wireless 7265                                                                           | 1         | 2.86%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 2.86%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 1         | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 1         | 2.86%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 2.86%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                                            | 1         | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 15        | 44.12%  |
| Intel                 | 9         | 26.47%  |
| Qualcomm Atheros      | 3         | 8.82%   |
| OPPO Electronics      | 3         | 8.82%   |
| Xiaomi                | 1         | 2.94%   |
| Qualcomm              | 1         | 2.94%   |
| Google                | 1         | 2.94%   |
| Broadcom              | 1         | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 29.41%  |
| Intel Ethernet Connection (16) I219-V                             | 3         | 8.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 5.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5.88%   |
| OPPO SM6375-QRD _SN:0AF7C3B5                                      | 2         | 5.88%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 2.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.94%   |
| Qualcomm SM6150-IDP _SN:488AC473                                  | 1         | 2.94%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.94%   |
| OPPO SM6375-QRD _SN:F4A23F05                                      | 1         | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.94%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.94%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.94%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.94%   |
| Google Pixel 7                                                    | 1         | 2.94%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 51.61%  |
| Ethernet | 30        | 48.39%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 59.38%  |
| Ethernet | 13        | 40.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 22        | 64.71%  |
| 1     | 11        | 32.35%  |
| 0     | 1         | 2.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 79.41%  |
| Yes  | 7         | 20.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 57.89%  |
| Qualcomm Atheros Communications | 2         | 10.53%  |
| Realtek Semiconductor           | 1         | 5.26%   |
| Ralink                          | 1         | 5.26%   |
| Lite-On Technology              | 1         | 5.26%   |
| IMC Networks                    | 1         | 5.26%   |
| Foxconn / Hon Hai               | 1         | 5.26%   |
| Broadcom                        | 1         | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 4         | 21.05%  |
| Intel AX201 Bluetooth                          | 4         | 21.05%  |
| Realtek Bluetooth Radio                        | 1         | 5.26%   |
| Ralink RT3290 Bluetooth                        | 1         | 5.26%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 5.26%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 5.26%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 5.26%   |
| Intel Bluetooth Device                         | 1         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 5.26%   |
| Intel AX200 Bluetooth                          | 1         | 5.26%   |
| IMC Networks Bluetooth Radio                   | 1         | 5.26%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter   | 1         | 5.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 26        | 63.41%  |
| AMD    | 8         | 19.51%  |
| Nvidia | 7         | 17.07%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 6         | 13.33%  |
| Intel Sunrise Point-LP HD Audio                                                   | 4         | 8.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4         | 8.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 3         | 6.67%   |
| Intel Cannon Lake PCH cAVS                                                        | 3         | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 3         | 6.67%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 6.67%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 4.44%   |
| Nvidia GA106 High Definition Audio Controller                                     | 2         | 4.44%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1         | 2.22%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 2.22%   |
| Nvidia Audio device                                                               | 1         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 2.22%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 2.22%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 1         | 2.22%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1         | 2.22%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 2.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1         | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 2.22%   |
| AMD FCH Azalia Controller                                                         | 1         | 2.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 2.22%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 2.22%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 1         | 2.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 25%     |
| SK hynix            | 7         | 21.88%  |
| Micron Technology   | 6         | 18.75%  |
| Crucial             | 4         | 12.5%   |
| Smart               | 1         | 3.13%   |
| Ramos Technology    | 1         | 3.13%   |
| PNY                 | 1         | 3.13%   |
| Patriot             | 1         | 3.13%   |
| fef5                | 1         | 3.13%   |
| A-DATA Technology   | 1         | 3.13%   |
| Unknown             | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s           | 1         | 3.03%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                   | 1         | 3.03%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 3.03%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 3.03%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s          | 1         | 3.03%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 3.03%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 3.03%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s          | 1         | 3.03%   |
| Samsung RAM Module 1GB Row Of Chips LPDDR4 3733MT/s             | 1         | 3.03%   |
| Samsung RAM Module 16GB SODIMM 4800MT/s                         | 1         | 3.03%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s           | 1         | 3.03%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s           | 1         | 3.03%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s           | 1         | 3.03%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 3.03%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 3.03%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s           | 1         | 3.03%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                 | 1         | 3.03%   |
| Ramos RAM EMB2GB481CL4-13HA 2GB DIMM 1227MT/s                   | 1         | 3.03%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3600MT/s             | 1         | 3.03%   |
| Patriot RAM 3200 C16 Series 8192MB DIMM DDR4 3266MT/s           | 1         | 3.03%   |
| Micron RAM MT40A1G16RC-062E:B 8GB SODIMM DDR4 3200MT/s          | 1         | 3.03%   |
| Micron RAM MT40A1G16RC-062E:B 8192MB Row Of Chips DDR4 3200MT/s | 1         | 3.03%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s           | 1         | 3.03%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s           | 1         | 3.03%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s           | 1         | 3.03%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s          | 1         | 3.03%   |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                           | 1         | 3.03%   |
| Crucial RAM RM25664BA1339.8FR 2GB DIMM DDR3 1333MT/s            | 1         | 3.03%   |
| Crucial RAM CT8G4SFS832A.M8FRS 8GB SODIMM DDR4 3200MT/s         | 1         | 3.03%   |
| Crucial RAM CT32G4SFD832A.C16FF 32GB SODIMM DDR4 3200MT/s       | 1         | 3.03%   |
| Crucial RAM BLS16G4D32AESC.M16FE 16GB DIMM DDR4 3200MT/s        | 1         | 3.03%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 3.03%   |
| Unknown                                                         | 1         | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 17        | 60.71%  |
| DDR3    | 5         | 17.86%  |
| Unknown | 3         | 10.71%  |
| LPDDR4  | 2         | 7.14%   |
| DDR5    | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 18        | 69.23%  |
| DIMM         | 5         | 19.23%  |
| Row Of Chips | 2         | 7.69%   |
| Unknown      | 1         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 9         | 32.14%  |
| 16384 | 6         | 21.43%  |
| 4096  | 6         | 21.43%  |
| 32768 | 3         | 10.71%  |
| 2048  | 2         | 7.14%   |
| 1024  | 2         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 9         | 32.14%  |
| 2667  | 6         | 21.43%  |
| 1600  | 3         | 10.71%  |
| 4800  | 2         | 7.14%   |
| 2400  | 2         | 7.14%   |
| 3733  | 1         | 3.57%   |
| 3600  | 1         | 3.57%   |
| 3266  | 1         | 3.57%   |
| 2133  | 1         | 3.57%   |
| 1333  | 1         | 3.57%   |
| 1227  | 1         | 3.57%   |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 8         | 30.77%  |
| IMC Networks                  | 4         | 15.38%  |
| Realtek Semiconductor         | 3         | 11.54%  |
| Sunplus Innovation Technology | 2         | 7.69%   |
| Acer                          | 2         | 7.69%   |
| Tobii Technology AB           | 1         | 3.85%   |
| Syntek                        | 1         | 3.85%   |
| Quanta                        | 1         | 3.85%   |
| Primax Electronics            | 1         | 3.85%   |
| Microdia                      | 1         | 3.85%   |
| Luxvisions Innotech Limited   | 1         | 3.85%   |
| Apple                         | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                             | 4         | 15.38%  |
| IMC Networks USB2.0 HD UVC WebCam                                     | 2         | 7.69%   |
| Tobii AB Eyechip                                                      | 1         | 3.85%   |
| Syntek Integrated Camera                                              | 1         | 3.85%   |
| Sunplus Laptop Integrated Webcam FHD                                  | 1         | 3.85%   |
| Sunplus 1080P Webcam                                                  | 1         | 3.85%   |
| Realtek Integrated Webcam_HD                                          | 1         | 3.85%   |
| Realtek Integrated Webcam HD                                          | 1         | 3.85%   |
| Realtek HD WebCam                                                     | 1         | 3.85%   |
| Quanta HD User Facing                                                 | 1         | 3.85%   |
| Primax HP HD Webcam [Fixed]                                           | 1         | 3.85%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 3.85%   |
| Luxvisions Innotech Limited Integrated RGB Camera                     | 1         | 3.85%   |
| IMC Networks VGA UVC WebCam                                           | 1         | 3.85%   |
| IMC Networks Integrated Camera                                        | 1         | 3.85%   |
| Chicony HP Truevision HD                                              | 1         | 3.85%   |
| Chicony HP High Definition 1MP Webcam                                 | 1         | 3.85%   |
| Chicony HP HD Camera                                                  | 1         | 3.85%   |
| Chicony HP 5MP Camera                                                 | 1         | 3.85%   |
| Apple FaceTime HD Camera (Built-in)                                   | 1         | 3.85%   |
| Acer Integrated Camera                                                | 1         | 3.85%   |
| Acer HD Webcam                                                        | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Synaptics | 4         | 80%     |
| Upek      | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 40%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 1         | 20%     |
| Synaptics UWP WBDI Device                                | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Upek        | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 22        | 64.71%  |
| 1     | 10        | 29.41%  |
| 2     | 2         | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 5         | 35.71%  |
| Net/wireless       | 3         | 21.43%  |
| Net/ethernet       | 2         | 14.29%  |
| Chipcard           | 2         | 14.29%  |
| Graphics card      | 1         | 7.14%   |
| Bluetooth          | 1         | 7.14%   |

