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

Total: 42

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| 6.0.0-12parrot1-amd64 | 29        | 93.55%  |
| 6.1.0-0.deb11.5-amd64 | 1         | 3.23%   |
| 5.10.92-v8+           | 1         | 3.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0.0   | 29        | 93.55%  |
| 6.1.0   | 1         | 3.23%   |
| 5.10.92 | 1         | 3.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 29        | 93.55%  |
| 6.1     | 1         | 3.23%   |
| 5.10    | 1         | 3.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 30        | 96.77%  |
| aarch64 | 1         | 3.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| MATE | 27        | 87.1%   |
| XFCE | 2         | 6.45%   |
| KDE5 | 2         | 6.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 30        | 96.77%  |
| Tty  | 1         | 3.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 22        | 70.97%  |
| Unknown | 8         | 25.81%  |
| SDDM    | 1         | 3.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 17        | 54.84%  |
| en_IN   | 3         | 9.68%   |
| en_AU   | 3         | 9.68%   |
| tr_TR   | 1         | 3.23%   |
| pl_PL   | 1         | 3.23%   |
| es_ES   | 1         | 3.23%   |
| es_AR   | 1         | 3.23%   |
| en_GB   | 1         | 3.23%   |
| de_DE   | 1         | 3.23%   |
| cs_CZ   | 1         | 3.23%   |
| Unknown | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 20        | 64.52%  |
| BIOS | 11        | 35.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 27        | 87.1%   |
| Ext4    | 2         | 6.45%   |
| Xfs     | 1         | 3.23%   |
| Overlay | 1         | 3.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 20        | 64.52%  |
| Unknown | 8         | 25.81%  |
| MBR     | 3         | 9.68%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 90.32%  |
| Yes       | 3         | 9.68%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 64.52%  |
| Yes       | 11        | 35.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 7         | 22.58%  |
| Hewlett-Packard         | 4         | 12.9%   |
| MSI                     | 3         | 9.68%   |
| Gigabyte Technology     | 3         | 9.68%   |
| Dell                    | 3         | 9.68%   |
| ASUSTek Computer        | 3         | 9.68%   |
| Acer                    | 2         | 6.45%   |
| Raspberry Pi Foundation | 1         | 3.23%   |
| Pegatron                | 1         | 3.23%   |
| Google                  | 1         | 3.23%   |
| ASRock                  | 1         | 3.23%   |
| Apple                   | 1         | 3.23%   |
| Alienware               | 1         | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| RPi Raspberry Pi 4 Model B Rev 1.5                  | 1         | 3.23%   |
| Pegatron 520-1030a                                  | 1         | 3.23%   |
| MSI MS-7917                                         | 1         | 3.23%   |
| MSI MS-7623                                         | 1         | 3.23%   |
| MSI Katana GF66 12UC                                | 1         | 3.23%   |
| Lenovo ThinkPad P15v Gen 3 21D8CTO1WW               | 1         | 3.23%   |
| Lenovo ThinkPad P14s Gen 3 21AKCTO1WW               | 1         | 3.23%   |
| Lenovo ThinkPad L15 Gen 3 21C3CTO1WW                | 1         | 3.23%   |
| Lenovo ThinkPad E460 20ETA05KAU                     | 1         | 3.23%   |
| Lenovo ThinkPad E15 Gen 4 21ED003YUS                | 1         | 3.23%   |
| Lenovo Legion 5 15ACH6 82JW                         | 1         | 3.23%   |
| Lenovo IdeaPad 5 15IAL7 82SF                        | 1         | 3.23%   |
| HP ZBook Firefly 15.6 inch G8 Mobile Workstation PC | 1         | 3.23%   |
| HP ZBook Firefly 14 inch G9 Mobile Workstation PC   | 1         | 3.23%   |
| HP ProBook 4540s                                    | 1         | 3.23%   |
| HP Pavilion 15                                      | 1         | 3.23%   |
| Google Lillipup                                     | 1         | 3.23%   |
| Gigabyte H61M-S2PV                                  | 1         | 3.23%   |
| Gigabyte B450 AORUS ELITE                           | 1         | 3.23%   |
| Gigabyte AORUS 15P KD                               | 1         | 3.23%   |
| Dell Vostro 1550                                    | 1         | 3.23%   |
| Dell OptiPlex 7070                                  | 1         | 3.23%   |
| Dell Inspiron 3421                                  | 1         | 3.23%   |
| ASUS X510UAR                                        | 1         | 3.23%   |
| ASUS VivoBook_ASUSLaptop X712DA_M712DA              | 1         | 3.23%   |
| ASUS PRIME X399-A                                   | 1         | 3.23%   |
| ASRock B560M-C                                      | 1         | 3.23%   |
| Apple iMac19,2                                      | 1         | 3.23%   |
| Alienware 17 R5                                     | 1         | 3.23%   |
| Acer Extensa 215-54                                 | 1         | 3.23%   |
| Acer Aspire E5-575                                  | 1         | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 5         | 16.13%  |
| HP ZBook           | 2         | 6.45%   |
| RPi Raspberry      | 1         | 3.23%   |
| Pegatron 520-1030a | 1         | 3.23%   |
| MSI MS-7917        | 1         | 3.23%   |
| MSI MS-7623        | 1         | 3.23%   |
| MSI Katana         | 1         | 3.23%   |
| Lenovo Legion      | 1         | 3.23%   |
| Lenovo IdeaPad     | 1         | 3.23%   |
| HP ProBook         | 1         | 3.23%   |
| HP Pavilion        | 1         | 3.23%   |
| Google Lillipup    | 1         | 3.23%   |
| Gigabyte H61M-S2PV | 1         | 3.23%   |
| Gigabyte B450      | 1         | 3.23%   |
| Gigabyte AORUS     | 1         | 3.23%   |
| Dell Vostro        | 1         | 3.23%   |
| Dell OptiPlex      | 1         | 3.23%   |
| Dell Inspiron      | 1         | 3.23%   |
| ASUS X510UAR       | 1         | 3.23%   |
| ASUS VivoBook      | 1         | 3.23%   |
| ASUS PRIME         | 1         | 3.23%   |
| ASRock B560M-C     | 1         | 3.23%   |
| Apple iMac19       | 1         | 3.23%   |
| Alienware 17       | 1         | 3.23%   |
| Acer Extensa       | 1         | 3.23%   |
| Acer Aspire        | 1         | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 7         | 22.58%  |
| 2021    | 4         | 12.9%   |
| 2012    | 4         | 12.9%   |
| 2020    | 3         | 9.68%   |
| 2018    | 2         | 6.45%   |
| 2017    | 2         | 6.45%   |
| 2014    | 2         | 6.45%   |
| 2023    | 1         | 3.23%   |
| 2019    | 1         | 3.23%   |
| 2016    | 1         | 3.23%   |
| 2015    | 1         | 3.23%   |
| 2013    | 1         | 3.23%   |
| 2010    | 1         | 3.23%   |
| Unknown | 1         | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 21        | 67.74%  |
| Desktop        | 8         | 25.81%  |
| System on chip | 1         | 3.23%   |
| All in one     | 1         | 3.23%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 31        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 30        | 96.77%  |
| Yes  | 1         | 3.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 8         | 25.81%  |
| 3.01-4.0    | 6         | 19.35%  |
| 4.01-8.0    | 5         | 16.13%  |
| 32.01-64.0  | 5         | 16.13%  |
| 8.01-16.0   | 4         | 12.9%   |
| 64.01-256.0 | 2         | 6.45%   |
| 1.01-2.0    | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 14        | 45.16%  |
| 4.01-8.0  | 5         | 16.13%  |
| 3.01-4.0  | 5         | 16.13%  |
| 1.01-2.0  | 3         | 9.68%   |
| 0.51-1.0  | 2         | 6.45%   |
| 8.01-16.0 | 1         | 3.23%   |
| 0.01-0.5  | 1         | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 16        | 51.61%  |
| 2      | 14        | 45.16%  |
| 0      | 1         | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 77.42%  |
| Yes       | 7         | 22.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 83.87%  |
| No        | 5         | 16.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 93.55%  |
| No        | 2         | 6.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 54.84%  |
| No        | 14        | 45.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| USA        | 12        | 38.71%  |
| India      | 3         | 9.68%   |
| Australia  | 3         | 9.68%   |
| UK         | 1         | 3.23%   |
| Turkey     | 1         | 3.23%   |
| Spain      | 1         | 3.23%   |
| Russia     | 1         | 3.23%   |
| Poland     | 1         | 3.23%   |
| Namibia    | 1         | 3.23%   |
| Mongolia   | 1         | 3.23%   |
| Germany    | 1         | 3.23%   |
| Czechia    | 1         | 3.23%   |
| Brazil     | 1         | 3.23%   |
| Bangladesh | 1         | 3.23%   |
| Argentina  | 1         | 3.23%   |
| Algeria    | 1         | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Windhoek               | 1         | 3.23%   |
| Ulan Bator             | 1         | 3.23%   |
| Topeka                 | 1         | 3.23%   |
| Sydney                 | 1         | 3.23%   |
| Seattle                | 1         | 3.23%   |
| Rostov-on-Don          | 1         | 3.23%   |
| Reading                | 1         | 3.23%   |
| Rancho Santa Margarita | 1         | 3.23%   |
| Orallo                 | 1         | 3.23%   |
| Nezvestice             | 1         | 3.23%   |
| Mercedes               | 1         | 3.23%   |
| London                 | 1         | 3.23%   |
| Lochow                 | 1         | 3.23%   |
| Leland                 | 1         | 3.23%   |
| Houston                | 1         | 3.23%   |
| Holsthum               | 1         | 3.23%   |
| Greenville             | 1         | 3.23%   |
| Geneva                 | 1         | 3.23%   |
| Fortaleza              | 1         | 3.23%   |
| Fernandina Beach       | 1         | 3.23%   |
| Eugene                 | 1         | 3.23%   |
| Dhaka                  | 1         | 3.23%   |
| Delhi                  | 1         | 3.23%   |
| Constantine            | 1         | 3.23%   |
| Chandigarh             | 1         | 3.23%   |
| Canberra               | 1         | 3.23%   |
| Bursa                  | 1         | 3.23%   |
| Brisbane               | 1         | 3.23%   |
| Bankura                | 1         | 3.23%   |
| Andover                | 1         | 3.23%   |
| Anchorage              | 1         | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 8         | 10     | 19.05%  |
| Seagate                     | 7         | 8      | 16.67%  |
| Kingston                    | 4         | 4      | 9.52%   |
| WDC                         | 2         | 2      | 4.76%   |
| Unknown                     | 2         | 2      | 4.76%   |
| SK hynix                    | 2         | 2      | 4.76%   |
| Sandisk                     | 2         | 3      | 4.76%   |
| Micron Technology           | 2         | 2      | 4.76%   |
| KIOXIA                      | 2         | 2      | 4.76%   |
| HGST                        | 2         | 2      | 4.76%   |
| Unknown (583)               | 1         | 1      | 2.38%   |
| Toshiba                     | 1         | 1      | 2.38%   |
| Phison                      | 1         | 1      | 2.38%   |
| Kingston Technology Company | 1         | 1      | 2.38%   |
| Hitachi                     | 1         | 1      | 2.38%   |
| Hewlett-Packard             | 1         | 1      | 2.38%   |
| GOODRAM                     | 1         | 1      | 2.38%   |
| Apple                       | 1         | 1      | 2.38%   |
| Apacer                      | 1         | 1      | 2.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WDS500G2B0B-00YS70 500GB SSD        | 2         | 4.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 4.55%   |
| Unknown SD16G  32GB                     | 1         | 2.27%   |
| Unknown HBG4a2  32GB                    | 1         | 2.27%   |
| Unknown (583) Disk 2TB                  | 1         | 2.27%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 2.27%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB | 1         | 2.27%   |
| SK hynix BC511 512GB                    | 1         | 2.27%   |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 2.27%   |
| Seagate ST380215AS 80GB                 | 1         | 2.27%   |
| Seagate ST3802110A 80GB                 | 1         | 2.27%   |
| Seagate ST2000DM008-2FR102 2TB          | 1         | 2.27%   |
| Seagate BUP Slim BK 1TB                 | 1         | 2.27%   |
| Seagate Backup+ Hub BK 12TB             | 1         | 2.27%   |
| Sandisk WD_BLACK SN770 500GB            | 1         | 2.27%   |
| SanDisk NVMe SSD Drive 500GB            | 1         | 2.27%   |
| SanDisk NVMe SSD Drive 1TB              | 1         | 2.27%   |
| Samsung SSD 980 1TB                     | 1         | 2.27%   |
| Samsung SSD 970 EVO Plus 1TB            | 1         | 2.27%   |
| Samsung SSD 970 EVO 1TB                 | 1         | 2.27%   |
| Samsung MZVLQ256HBJD-00BH1 256GB        | 1         | 2.27%   |
| Samsung MZVL2512HCJQ-00BL7 512GB        | 1         | 2.27%   |
| Samsung MZVL2512HCJQ-00B00 512GB        | 1         | 2.27%   |
| Samsung MZAL4512HBLU-00BL2 512GB        | 1         | 2.27%   |
| Samsung MZ7TY256HDHP-000L7 256GB SSD    | 1         | 2.27%   |
| Phison Dash Pro 2TB                     | 1         | 2.27%   |
| Micron MTFDKCD1T0TFK 1TB                | 1         | 2.27%   |
| Micron 2450_MTFDKBA1T0TFK 1TB           | 1         | 2.27%   |
| KIOXIA KXG60ZNV1T02 1TB                 | 1         | 2.27%   |
| KIOXIA KBG5AZNT512G LA 512GB            | 1         | 2.27%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB | 1         | 2.27%   |
| Kingston SNVS500G 500GB                 | 1         | 2.27%   |
| Kingston SNV2S500G 500GB                | 1         | 2.27%   |
| Kingston OM8PCP3512F-AB 512GB           | 1         | 2.27%   |
| Kingston A400 960G SSD                  | 1         | 2.27%   |
| Hitachi HUA722020ALA331 2TB             | 1         | 2.27%   |
| HGST HTS725032A7E630 320GB              | 1         | 2.27%   |
| HGST HTS721010A9E630 1TB                | 1         | 2.27%   |
| HP SSD S700 Pro 1TB                     | 1         | 2.27%   |
| GOODRAM SSDPR-CX400-256-G2 256GB        | 1         | 2.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 8      | 63.64%  |
| HGST    | 2         | 2      | 18.18%  |
| Toshiba | 1         | 1      | 9.09%   |
| Hitachi | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 28.57%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Kingston            | 1         | 1      | 14.29%  |
| Hewlett-Packard     | 1         | 1      | 14.29%  |
| GOODRAM             | 1         | 1      | 14.29%  |
| Apacer              | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 19        | 25     | 48.72%  |
| HDD  | 11        | 12     | 28.21%  |
| SSD  | 7         | 7      | 17.95%  |
| MMC  | 2         | 2      | 5.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 19        | 24     | 50%     |
| SATA | 14        | 17     | 36.84%  |
| SAS  | 3         | 3      | 7.89%   |
| MMC  | 2         | 2      | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 11     | 52.94%  |
| 0.51-1.0   | 5         | 5      | 29.41%  |
| 1.01-2.0   | 2         | 2      | 11.76%  |
| 10.01-20.0 | 1         | 1      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 6         | 19.35%  |
| 101-250        | 5         | 16.13%  |
| 1001-2000      | 5         | 16.13%  |
| 251-500        | 4         | 12.9%   |
| Unknown        | 4         | 12.9%   |
| More than 3000 | 2         | 6.45%   |
| 1-20           | 2         | 6.45%   |
| 21-50          | 1         | 3.23%   |
| 2001-3000      | 1         | 3.23%   |
| 51-100         | 1         | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 11        | 35.48%  |
| 1-20           | 5         | 16.13%  |
| 51-100         | 5         | 16.13%  |
| Unknown        | 4         | 12.9%   |
| 101-250        | 2         | 6.45%   |
| More than 3000 | 1         | 3.23%   |
| 251-500        | 1         | 3.23%   |
| 2001-3000      | 1         | 3.23%   |
| 0              | 1         | 3.23%   |

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
| Works    | 18        | 24     | 52.94%  |
| Detected | 13        | 18     | 38.24%  |
| Malfunc  | 3         | 4      | 8.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 17        | 37.78%  |
| Samsung Electronics          | 8         | 17.78%  |
| AMD                          | 6         | 13.33%  |
| Kingston Technology Company  | 4         | 8.89%   |
| SK hynix                     | 2         | 4.44%   |
| SanDisk                      | 2         | 4.44%   |
| Micron Technology            | 2         | 4.44%   |
| Toshiba America Info Systems | 1         | 2.22%   |
| Phison Electronics           | 1         | 2.22%   |
| KIOXIA                       | 1         | 2.22%   |
| ASMedia Technology           | 1         | 2.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 4         | 8.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 6.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 6.12%   |
| SanDisk WD Black SN770 NVMe SSD                                                         | 2         | 4.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 4.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 4.08%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 4.08%   |
| Micron NVMe Storage Controller                                                          | 2         | 4.08%   |
| Kingston Company Company Non-Volatile memory controller                                 | 2         | 4.08%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 4.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 4.08%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 2         | 4.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 2.04%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1         | 2.04%   |
| SK hynix BC511                                                                          | 1         | 2.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 2.04%   |
| Samsung NVMe SSD Controller PM9B1                                                       | 1         | 2.04%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 2.04%   |
| KIOXIA Non-Volatile memory controller                                                   | 1         | 2.04%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1         | 2.04%   |
| Kingston Company NVMe Controller                                                        | 1         | 2.04%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 1         | 2.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 2.04%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1         | 2.04%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 2.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 2.04%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1         | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1         | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1         | 2.04%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 2.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 21        | 47.73%  |
| NVMe | 19        | 43.18%  |
| RAID | 2         | 4.55%   |
| IDE  | 2         | 4.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 74.19%  |
| AMD    | 7         | 22.58%  |
| ARM    | 1         | 3.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H                  | 2         | 6.45%   |
| Intel Pentium CPU G620 @ 2.60GHz               | 1         | 3.23%   |
| Intel Core i9-10900F CPU @ 2.80GHz             | 1         | 3.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1         | 3.23%   |
| Intel Core i7-6500U CPU @ 2.50GHz              | 1         | 3.23%   |
| Intel Core i5-9500T CPU @ 2.20GHz              | 1         | 3.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz              | 1         | 3.23%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 1         | 3.23%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 1         | 3.23%   |
| Intel Core i3-8100 CPU @ 3.60GHz               | 1         | 3.23%   |
| Intel Core i3-6100U CPU @ 2.30GHz              | 1         | 3.23%   |
| Intel Core i3-3217U CPU @ 1.80GHz              | 1         | 3.23%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 1         | 3.23%   |
| Intel Core i3-2350M CPU @ 2.30GHz              | 1         | 3.23%   |
| Intel 12th Gen Core i7-1265U                   | 1         | 3.23%   |
| Intel 12th Gen Core i7-1260P                   | 1         | 3.23%   |
| Intel 12th Gen Core i7-1255U                   | 1         | 3.23%   |
| Intel 12th Gen Core i5-1235U                   | 1         | 3.23%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 1         | 3.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 3.23%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 1         | 3.23%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz        | 1         | 3.23%   |
| ARM Processor                                  | 1         | 3.23%   |
| AMD Sempron 145 Processor                      | 1         | 3.23%   |
| AMD Ryzen Threadripper 2950X 16-Core Processor | 1         | 3.23%   |
| AMD Ryzen 7 5800H with Radeon Graphics         | 1         | 3.23%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx  | 1         | 3.23%   |
| AMD Ryzen 5 5625U with Radeon Graphics         | 1         | 3.23%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1         | 3.23%   |
| AMD A6-3600 APU with Radeon HD Graphics        | 1         | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Other                  | 11        | 35.48%  |
| Intel Core i3          | 5         | 16.13%  |
| Intel Core i5          | 4         | 12.9%   |
| Intel Core i7          | 2         | 6.45%   |
| AMD Ryzen 7            | 2         | 6.45%   |
| AMD Ryzen 5            | 2         | 6.45%   |
| Intel Pentium          | 1         | 3.23%   |
| Intel Core i9          | 1         | 3.23%   |
| AMD Sempron            | 1         | 3.23%   |
| AMD Ryzen Threadripper | 1         | 3.23%   |
| AMD A6                 | 1         | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 8         | 25.81%  |
| 2      | 8         | 25.81%  |
| 10     | 4         | 12.9%   |
| 6      | 4         | 12.9%   |
| 14     | 2         | 6.45%   |
| 8      | 2         | 6.45%   |
| 16     | 1         | 3.23%   |
| 12     | 1         | 3.23%   |
| 1      | 1         | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 31        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 18        | 58.06%  |
| 1      | 13        | 41.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 31        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 29.03%  |
| 0x906a4    | 3         | 9.68%   |
| 0x906a3    | 3         | 9.68%   |
| 0x806c1    | 2         | 6.45%   |
| 0x306a9    | 2         | 6.45%   |
| 0x0a50000c | 2         | 6.45%   |
| 0xa0655    | 1         | 3.23%   |
| 0x906eb    | 1         | 3.23%   |
| 0x906ea    | 1         | 3.23%   |
| 0x806ea    | 1         | 3.23%   |
| 0x806d1    | 1         | 3.23%   |
| 0x406e3    | 1         | 3.23%   |
| 0x206a7    | 1         | 3.23%   |
| 0x0a201204 | 1         | 3.23%   |
| 0x08108102 | 1         | 3.23%   |
| 0x010000c8 | 1         | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Alderlake Hybrid | 6         | 19.35%  |
| KabyLake         | 4         | 12.9%   |
| Zen 3            | 3         | 9.68%   |
| TigerLake        | 3         | 9.68%   |
| SandyBridge      | 3         | 9.68%   |
| Zen+             | 2         | 6.45%   |
| Skylake          | 2         | 6.45%   |
| IvyBridge        | 2         | 6.45%   |
| K10 Llano        | 1         | 3.23%   |
| K10              | 1         | 3.23%   |
| Icelake          | 1         | 3.23%   |
| Haswell          | 1         | 3.23%   |
| CometLake        | 1         | 3.23%   |
| Unknown          | 1         | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 21        | 52.5%   |
| Nvidia | 11        | 27.5%   |
| AMD    | 8         | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 3         | 7.5%    |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 3         | 7.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 7.5%    |
| Nvidia TU116 [GeForce GTX 1660]                                                       | 2         | 5%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 5%      |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 5%      |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 5%      |
| Nvidia TU117GLM [T600 Laptop GPU]                                                     | 1         | 2.5%    |
| Nvidia TU117GLM [T550 Laptop GPU]                                                     | 1         | 2.5%    |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                  | 1         | 2.5%    |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                              | 1         | 2.5%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 2.5%    |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                           | 1         | 2.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 1         | 2.5%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                        | 1         | 2.5%    |
| Nvidia GA104 [GeForce RTX 3070]                                                       | 1         | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 2.5%    |
| Intel UHD Graphics 620                                                                | 1         | 2.5%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 2.5%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 1         | 2.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 1         | 2.5%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 2.5%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.5%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 1         | 2.5%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 2.5%    |
| AMD RS780L [Radeon 3000]                                                              | 1         | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 2.5%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                    | 1         | 2.5%    |
| AMD Barcelo                                                                           | 1         | 2.5%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 11        | 35.48%  |
| 1 x Nvidia     | 6         | 19.35%  |
| Intel + Nvidia | 5         | 16.13%  |
| 1 x AMD        | 5         | 16.13%  |
| Intel + AMD    | 3         | 9.68%   |
| Other          | 1         | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 28        | 90.32%  |
| Proprietary | 2         | 6.45%   |
| Unknown     | 1         | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 58.06%  |
| 3.01-4.0   | 5         | 16.13%  |
| 5.01-6.0   | 2         | 6.45%   |
| 1.01-2.0   | 2         | 6.45%   |
| 0.51-1.0   | 2         | 6.45%   |
| 7.01-8.0   | 1         | 3.23%   |
| 0.01-0.5   | 1         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 5         | 14.29%  |
| BOE                  | 4         | 11.43%  |
| AU Optronics         | 4         | 11.43%  |
| Chimei Innolux       | 3         | 8.57%   |
| Samsung Electronics  | 2         | 5.71%   |
| Hewlett-Packard      | 2         | 5.71%   |
| Dell                 | 2         | 5.71%   |
| Ancor Communications | 2         | 5.71%   |
| Acer                 | 2         | 5.71%   |
| VIZ                  | 1         | 2.86%   |
| Sharp                | 1         | 2.86%   |
| Pixio                | 1         | 2.86%   |
| LG Electronics       | 1         | 2.86%   |
| Goldstar             | 1         | 2.86%   |
| Element              | 1         | 2.86%   |
| CSO                  | 1         | 2.86%   |
| BOE Technology Group | 1         | 2.86%   |
| Apple                | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                | 2         | 5.71%   |
| VIZ LCD Monitor VA19L HDTV10T                                        | 1         | 2.86%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch              | 1         | 2.86%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch   | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch | 1         | 2.86%   |
| Pixio EULCD-2400DFE WAM2380 1920x1080 530x290mm 23.8-inch            | 1         | 2.86%   |
| LG Electronics LCD Monitor LG HDR WFHD 2560x1080                     | 1         | 2.86%   |
| LG Display LCD Monitor LGD06E4 1920x1080 344x194mm 15.5-inch         | 1         | 2.86%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 2.86%   |
| LG Display LCD Monitor LGD0505 1366x768 344x194mm 15.5-inch          | 1         | 2.86%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch          | 1         | 2.86%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch          | 1         | 2.86%   |
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch     | 1         | 2.86%   |
| Hewlett-Packard LA1956x HWP3021 1280x1024 376x301mm 19.0-inch        | 1         | 2.86%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 1         | 2.86%   |
| Element ELEFW328C ELE3553 1360x768 640x384mm 29.4-inch               | 1         | 2.86%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                    | 1         | 2.86%   |
| Dell P2314T DEL409E 1920x1080 509x286mm 23.0-inch                    | 1         | 2.86%   |
| CSO LCD Monitor CSO1506 1920x1080 344x194mm 15.5-inch                | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch      | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15AA 1366x768 344x194mm 15.5-inch      | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 1         | 2.86%   |
| BOE Technology Group LCD Monitor 3200x1080                           | 1         | 2.86%   |
| BOE LCD Monitor BOE0AB0 1920x1080 344x194mm 15.5-inch                | 1         | 2.86%   |
| BOE LCD Monitor BOE0A64 1920x1080 344x194mm 15.5-inch                | 1         | 2.86%   |
| AU Optronics LCD Monitor AUOE3A0 3840x2400 301x188mm 14.0-inch       | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO662D 1920x1080 293x165mm 13.2-inch       | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO5A99 1920x1200 301x188mm 14.0-inch       | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO1496 2560x1440 382x214mm 17.2-inch       | 1         | 2.86%   |
| Apple iMac APPAE19 3840x2160 475x267mm 21.5-inch                     | 1         | 2.86%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch     | 1         | 2.86%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch     | 1         | 2.86%   |
| Acer H193HQV ACR01B8 1366x768 410x230mm 18.5-inch                    | 1         | 2.86%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                    | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 15        | 44.12%  |
| 1366x768 (WXGA)   | 7         | 20.59%  |
| 3840x2160 (4K)    | 2         | 5.88%   |
| 1920x1200 (WUXGA) | 2         | 5.88%   |
| 3840x2400         | 1         | 2.94%   |
| 3200x1080         | 1         | 2.94%   |
| 2560x1440 (QHD)   | 1         | 2.94%   |
| 2560x1080         | 1         | 2.94%   |
| 1600x900 (HD+)    | 1         | 2.94%   |
| 1360x768          | 1         | 2.94%   |
| 1280x1024 (SXGA)  | 1         | 2.94%   |
| Unknown           | 1         | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 13        | 39.39%  |
| 24      | 3         | 9.09%   |
| 18      | 3         | 9.09%   |
| 14      | 3         | 9.09%   |
| 23      | 2         | 6.06%   |
| 17      | 2         | 6.06%   |
| Unknown | 2         | 6.06%   |
| 32      | 1         | 3.03%   |
| 27      | 1         | 3.03%   |
| 21      | 1         | 3.03%   |
| 19      | 1         | 3.03%   |
| 13      | 1         | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 50%     |
| 501-600     | 6         | 18.75%  |
| 401-500     | 3         | 9.38%   |
| 351-400     | 3         | 9.38%   |
| Unknown     | 2         | 6.25%   |
| 701-800     | 1         | 3.13%   |
| 201-300     | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 24        | 80%     |
| 16/10   | 3         | 10%     |
| Unknown | 2         | 6.67%   |
| 5/4     | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 39.39%  |
| 201-250        | 4         | 12.12%  |
| 81-90          | 3         | 9.09%   |
| 141-150        | 3         | 9.09%   |
| 151-200        | 2         | 6.06%   |
| 121-130        | 2         | 6.06%   |
| Unknown        | 2         | 6.06%   |
| 71-80          | 1         | 3.03%   |
| 351-500        | 1         | 3.03%   |
| 301-350        | 1         | 3.03%   |
| 251-300        | 1         | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 10        | 30.3%   |
| 121-160       | 9         | 27.27%  |
| 101-120       | 6         | 18.18%  |
| 161-240       | 5         | 15.15%  |
| Unknown       | 2         | 6.06%   |
| More than 240 | 1         | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 25        | 80.65%  |
| 2     | 5         | 16.13%  |
| 0     | 1         | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 18        | 34.62%  |
| Intel                 | 15        | 28.85%  |
| Qualcomm Atheros      | 7         | 13.46%  |
| Ralink                | 2         | 3.85%   |
| Xiaomi                | 1         | 1.92%   |
| Ralink Technology     | 1         | 1.92%   |
| Qualcomm              | 1         | 1.92%   |
| OPPO Electronics      | 1         | 1.92%   |
| NetGear               | 1         | 1.92%   |
| Mercucys              | 1         | 1.92%   |
| MediaTek              | 1         | 1.92%   |
| Google                | 1         | 1.92%   |
| Broadcom Limited      | 1         | 1.92%   |
| Broadcom              | 1         | 1.92%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 9         | 14.75%  |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 6         | 9.84%   |
| Intel Wi-Fi 6 AX201                                                                           | 3         | 4.92%   |
| Intel Ethernet Connection (16) I219-V                                                         | 3         | 4.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2         | 3.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2         | 3.28%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                          | 1         | 1.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.64%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.64%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1         | 1.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 1.64%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1         | 1.64%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.64%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.64%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.64%   |
| Qualcomm SM7250-PICASSO _SN:6897A937                                                          | 1         | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1         | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1         | 1.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1         | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 1         | 1.64%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                                                          | 1         | 1.64%   |
| NetGear A6210                                                                                 | 1         | 1.64%   |
| Mercucys 802.11n NIC                                                                          | 1         | 1.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 1.64%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.64%   |
| Intel Wireless 8260                                                                           | 1         | 1.64%   |
| Intel Wireless 7265                                                                           | 1         | 1.64%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 1.64%   |
| Intel I211 Gigabit Network Connection                                                         | 1         | 1.64%   |
| Intel Ethernet Connection I219-V                                                              | 1         | 1.64%   |
| Intel Ethernet Connection (7) I219-LM                                                         | 1         | 1.64%   |
| Intel Ethernet Connection (11) I219-V                                                         | 1         | 1.64%   |
| Google Pixel 7                                                                                | 1         | 1.64%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                                             | 1         | 1.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 40.63%  |
| Realtek Semiconductor | 6         | 18.75%  |
| Qualcomm Atheros      | 5         | 15.63%  |
| Ralink                | 2         | 6.25%   |
| Ralink Technology     | 1         | 3.13%   |
| NetGear               | 1         | 3.13%   |
| Mercucys              | 1         | 3.13%   |
| MediaTek              | 1         | 3.13%   |
| Broadcom Limited      | 1         | 3.13%   |
| Broadcom              | 1         | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 6         | 18.75%  |
| Intel Wi-Fi 6 AX201                                                                           | 3         | 9.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 3.13%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 3.13%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1         | 3.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 3.13%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 3.13%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 3.13%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 3.13%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1         | 3.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 3.13%   |
| NetGear A6210                                                                                 | 1         | 3.13%   |
| Mercucys 802.11n NIC                                                                          | 1         | 3.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 3.13%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 3.13%   |
| Intel Wireless 8260                                                                           | 1         | 3.13%   |
| Intel Wireless 7265                                                                           | 1         | 3.13%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 3.13%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 3.13%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                                            | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 14        | 48.28%  |
| Intel                 | 7         | 24.14%  |
| Qualcomm Atheros      | 3         | 10.34%  |
| Xiaomi                | 1         | 3.45%   |
| Qualcomm              | 1         | 3.45%   |
| OPPO Electronics      | 1         | 3.45%   |
| Google                | 1         | 3.45%   |
| Broadcom              | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 31.03%  |
| Intel Ethernet Connection (16) I219-V                             | 3         | 10.34%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 6.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 6.9%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 3.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.45%   |
| Qualcomm SM7250-PICASSO _SN:6897A937                              | 1         | 3.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 3.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 3.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 3.45%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 1         | 3.45%   |
| Intel I211 Gigabit Network Connection                             | 1         | 3.45%   |
| Intel Ethernet Connection I219-V                                  | 1         | 3.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 3.45%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 3.45%   |
| Google Pixel 7                                                    | 1         | 3.45%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 53.7%   |
| Ethernet | 25        | 46.3%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 55.17%  |
| Ethernet | 13        | 44.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 19        | 61.29%  |
| 1     | 11        | 35.48%  |
| 0     | 1         | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 24        | 77.42%  |
| Yes  | 7         | 22.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 58.82%  |
| Qualcomm Atheros Communications | 2         | 11.76%  |
| Realtek Semiconductor           | 1         | 5.88%   |
| Ralink                          | 1         | 5.88%   |
| Lite-On Technology              | 1         | 5.88%   |
| IMC Networks                    | 1         | 5.88%   |
| Foxconn / Hon Hai               | 1         | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 4         | 23.53%  |
| Intel Bluetooth wireless interface             | 3         | 17.65%  |
| Realtek Bluetooth Radio                        | 1         | 5.88%   |
| Ralink RT3290 Bluetooth                        | 1         | 5.88%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 5.88%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 5.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 5.88%   |
| Intel Bluetooth Device                         | 1         | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 5.88%   |
| Intel AX200 Bluetooth                          | 1         | 5.88%   |
| IMC Networks Bluetooth Radio                   | 1         | 5.88%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 60.53%  |
| AMD    | 8         | 21.05%  |
| Nvidia | 7         | 18.42%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 6         | 14.29%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 3         | 7.14%   |
| Intel Sunrise Point-LP HD Audio                                                   | 3         | 7.14%   |
| Intel Cannon Lake PCH cAVS                                                        | 3         | 7.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3         | 7.14%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 7.14%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 4.76%   |
| Nvidia GA106 High Definition Audio Controller                                     | 2         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2         | 4.76%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1         | 2.38%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 2.38%   |
| Nvidia Audio device                                                               | 1         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 2.38%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 2.38%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 1         | 2.38%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1         | 2.38%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1         | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 2.38%   |
| AMD FCH Azalia Controller                                                         | 1         | 2.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 2.38%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 2.38%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 1         | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 25.81%  |
| SK hynix            | 6         | 19.35%  |
| Micron Technology   | 6         | 19.35%  |
| Crucial             | 4         | 12.9%   |
| Smart               | 1         | 3.23%   |
| Ramos Technology    | 1         | 3.23%   |
| PNY                 | 1         | 3.23%   |
| Patriot             | 1         | 3.23%   |
| fef5                | 1         | 3.23%   |
| A-DATA Technology   | 1         | 3.23%   |
| Unknown             | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s        | 1         | 3.13%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                | 1         | 3.13%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 3.13%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 3.13%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s       | 1         | 3.13%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 3.13%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 3.13%   |
| Samsung RAM Module 1GB Row Of Chips LPDDR4 3733MT/s          | 1         | 3.13%   |
| Samsung RAM Module 16GB SODIMM 4800MT/s                      | 1         | 3.13%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 3.13%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s        | 1         | 3.13%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 3.13%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 3.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 1         | 3.13%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 3.13%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s              | 1         | 3.13%   |
| Ramos RAM EMB2GB481CL4-13HA 2GB DIMM 1227MT/s                | 1         | 3.13%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3600MT/s          | 1         | 3.13%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s           | 1         | 3.13%   |
| Micron RAM MT40A1G16RC-062E:B 8GB SODIMM DDR4 3200MT/s       | 1         | 3.13%   |
| Micron RAM MT40A1G16RC-062E:B 8GB Row Of Chips DDR4 3200MT/s | 1         | 3.13%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s        | 1         | 3.13%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s        | 1         | 3.13%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s        | 1         | 3.13%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s       | 1         | 3.13%   |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                        | 1         | 3.13%   |
| Crucial RAM RM25664BA1339.8FR 2GB DIMM DDR3 1333MT/s         | 1         | 3.13%   |
| Crucial RAM CT8G4SFS832A.M8FRS 8GB SODIMM DDR4 3200MT/s      | 1         | 3.13%   |
| Crucial RAM CT32G4SFD832A.C16FF 32GB SODIMM DDR4 3200MT/s    | 1         | 3.13%   |
| Crucial RAM BLS16G4D32AESC.M16FE 16GB DIMM DDR4 3200MT/s     | 1         | 3.13%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                  | 1         | 3.13%   |
| Unknown                                                      | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 16        | 59.26%  |
| DDR3    | 5         | 18.52%  |
| Unknown | 3         | 11.11%  |
| LPDDR4  | 2         | 7.41%   |
| DDR5    | 1         | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 17        | 68%     |
| DIMM         | 5         | 20%     |
| Row Of Chips | 2         | 8%      |
| Unknown      | 1         | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 8         | 29.63%  |
| 16384 | 6         | 22.22%  |
| 4096  | 6         | 22.22%  |
| 32768 | 3         | 11.11%  |
| 2048  | 2         | 7.41%   |
| 1024  | 2         | 7.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 9         | 33.33%  |
| 2667  | 5         | 18.52%  |
| 1600  | 3         | 11.11%  |
| 4800  | 2         | 7.41%   |
| 2400  | 2         | 7.41%   |
| 3733  | 1         | 3.7%    |
| 3600  | 1         | 3.7%    |
| 3266  | 1         | 3.7%    |
| 2133  | 1         | 3.7%    |
| 1333  | 1         | 3.7%    |
| 1227  | 1         | 3.7%    |

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
| Chicony Electronics           | 7         | 29.17%  |
| IMC Networks                  | 4         | 16.67%  |
| Sunplus Innovation Technology | 2         | 8.33%   |
| Realtek Semiconductor         | 2         | 8.33%   |
| Tobii Technology AB           | 1         | 4.17%   |
| Syntek                        | 1         | 4.17%   |
| Quanta                        | 1         | 4.17%   |
| Primax Electronics            | 1         | 4.17%   |
| Microdia                      | 1         | 4.17%   |
| Luxvisions Innotech Limited   | 1         | 4.17%   |
| Bison Electronics             | 1         | 4.17%   |
| Apple                         | 1         | 4.17%   |
| Acer                          | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                             | 3         | 12.5%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 2         | 8.33%   |
| Tobii AB Eyechip                                                      | 1         | 4.17%   |
| Syntek Integrated Camera                                              | 1         | 4.17%   |
| Sunplus Laptop Integrated Webcam FHD                                  | 1         | 4.17%   |
| Sunplus FHD Camera Microphone                                         | 1         | 4.17%   |
| Realtek Integrated Webcam HD                                          | 1         | 4.17%   |
| Realtek HD WebCam                                                     | 1         | 4.17%   |
| Quanta HD User Facing                                                 | 1         | 4.17%   |
| Primax HP HD Webcam [Fixed]                                           | 1         | 4.17%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 4.17%   |
| Luxvisions Innotech Limited Integrated RGB Camera                     | 1         | 4.17%   |
| IMC Networks VGA UVC WebCam                                           | 1         | 4.17%   |
| IMC Networks Integrated Camera                                        | 1         | 4.17%   |
| Chicony HP Truevision HD                                              | 1         | 4.17%   |
| Chicony HP High Definition 1MP Webcam                                 | 1         | 4.17%   |
| Chicony HP HD Camera                                                  | 1         | 4.17%   |
| Chicony HP 5MP Camera                                                 | 1         | 4.17%   |
| Bison HD Webcam                                                       | 1         | 4.17%   |
| Apple FaceTime HD Camera (Built-in)                                   | 1         | 4.17%   |
| Acer Integrated Camera                                                | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Synaptics | 4         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 50%     |
| Synaptics UWP WBDI Device                                | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 21        | 67.74%  |
| 1     | 8         | 25.81%  |
| 2     | 2         | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 4         | 33.33%  |
| Net/wireless       | 3         | 25%     |
| Net/ethernet       | 2         | 16.67%  |
| Graphics card      | 1         | 8.33%   |
| Chipcard           | 1         | 8.33%   |
| Bluetooth          | 1         | 8.33%   |

