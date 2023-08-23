Elementary 7 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Elementary 7.

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

Total: 77

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte  | B560M H                     | [663f9e62db](https://linux-hardware.org/?probe=663f9e62db) | Aug 08, 2023 |
| Acer      | Aspire TC-710 V:1.1         | [f6af1382fd](https://linux-hardware.org/?probe=f6af1382fd) | Aug 08, 2023 |
| Dell      | 0NKW6Y A02                  | [09ae57bb9a](https://linux-hardware.org/?probe=09ae57bb9a) | Aug 05, 2023 |
| Dell      | 0NKW6Y A02                  | [21460cac53](https://linux-hardware.org/?probe=21460cac53) | Aug 05, 2023 |
| Pegatron  | 2A94h                       | [9d5490fb82](https://linux-hardware.org/?probe=9d5490fb82) | Aug 04, 2023 |
| MSI       | A320M-A PRO MAX             | [36dda4bbfa](https://linux-hardware.org/?probe=36dda4bbfa) | Jul 28, 2023 |
| MSI       | A320M-A PRO MAX             | [10fa87c167](https://linux-hardware.org/?probe=10fa87c167) | Jul 28, 2023 |
| ASRock    | X570 Extreme4               | [5b1a74fc68](https://linux-hardware.org/?probe=5b1a74fc68) | Jul 27, 2023 |
| Acer      | Aspire TC-380               | [94f5f10ff2](https://linux-hardware.org/?probe=94f5f10ff2) | Jul 14, 2023 |
| Wortmann  | TERRA_PC                    | [60ece53188](https://linux-hardware.org/?probe=60ece53188) | Jul 13, 2023 |
| ASRock    | X370 Pro4                   | [4e8926a95b](https://linux-hardware.org/?probe=4e8926a95b) | Jul 11, 2023 |
| Lenovo    | 3106 SDK0J40697 WIN 3305... | [784f886357](https://linux-hardware.org/?probe=784f886357) | Jul 10, 2023 |
| Apple     | Mac-F221BEC8                | [881754a433](https://linux-hardware.org/?probe=881754a433) | Jul 09, 2023 |
| Alienware | 07HV66 A00                  | [41d4d9ae84](https://linux-hardware.org/?probe=41d4d9ae84) | Jul 05, 2023 |
| Alienware | 07HV66 A00                  | [2712110727](https://linux-hardware.org/?probe=2712110727) | Jul 05, 2023 |
| Gigabyte  | H81M-S2V                    | [38ae545c1c](https://linux-hardware.org/?probe=38ae545c1c) | Jun 23, 2023 |
| MSI       | B450M PRO-M2 V2             | [4f5e2f9201](https://linux-hardware.org/?probe=4f5e2f9201) | Jun 21, 2023 |
| Pegatron  | IPMIP-GS                    | [fb51893272](https://linux-hardware.org/?probe=fb51893272) | Jun 15, 2023 |
| ECS       | G41T-M                      | [2c148573fc](https://linux-hardware.org/?probe=2c148573fc) | Jun 11, 2023 |
| ASUSTek   | ROG STRIX B350-F GAMING     | [08114e8a97](https://linux-hardware.org/?probe=08114e8a97) | Jun 10, 2023 |
| ASUSTek   | PRIME B450-PLUS             | [93555cfd25](https://linux-hardware.org/?probe=93555cfd25) | Jun 10, 2023 |
| ASUSTek   | PRIME B450-PLUS             | [2e6d82c14f](https://linux-hardware.org/?probe=2e6d82c14f) | Jun 10, 2023 |
| MSI       | MPG Z390 GAMING PRO CARB... | [ddefeff960](https://linux-hardware.org/?probe=ddefeff960) | Jun 08, 2023 |
| MSI       | MPG Z390 GAMING PRO CARB... | [77fe6db865](https://linux-hardware.org/?probe=77fe6db865) | Jun 06, 2023 |
| Gigabyte  | GA-E6010N                   | [563074319d](https://linux-hardware.org/?probe=563074319d) | May 31, 2023 |
| Lenovo    | 3106 SDK0J40697 WIN 3305... | [01076d8e8b](https://linux-hardware.org/?probe=01076d8e8b) | May 30, 2023 |
| ASUSTek   | ROG STRIX B350-F GAMING     | [16b9dfbbe0](https://linux-hardware.org/?probe=16b9dfbbe0) | May 29, 2023 |
| ASUSTek   | PRIME B450-PLUS             | [e29fb14e81](https://linux-hardware.org/?probe=e29fb14e81) | May 26, 2023 |
| ASUSTek   | PRIME B450-PLUS             | [84d0d9807f](https://linux-hardware.org/?probe=84d0d9807f) | May 26, 2023 |
| ASUSTek   | P8H61-MX R2.0               | [3776285fc1](https://linux-hardware.org/?probe=3776285fc1) | May 16, 2023 |
| HP        | 1998                        | [b806151d9f](https://linux-hardware.org/?probe=b806151d9f) | May 12, 2023 |
| Intel     | JSL MRD                     | [76ff5c3bd7](https://linux-hardware.org/?probe=76ff5c3bd7) | May 05, 2023 |
| Dell      | 02N3WF A02                  | [3f10b3ca43](https://linux-hardware.org/?probe=3f10b3ca43) | May 04, 2023 |
| HP        | 1998                        | [6f816ac95a](https://linux-hardware.org/?probe=6f816ac95a) | Apr 29, 2023 |
| HP        | 8055                        | [a897208085](https://linux-hardware.org/?probe=a897208085) | Apr 26, 2023 |
| ASRock    | B660M-C                     | [849fc5d462](https://linux-hardware.org/?probe=849fc5d462) | Apr 25, 2023 |
| Gigabyte  | H410M H V3                  | [8fd18554d1](https://linux-hardware.org/?probe=8fd18554d1) | Apr 24, 2023 |
| MACHINIST | E5-MR9A PRO V1.1            | [eebce73217](https://linux-hardware.org/?probe=eebce73217) | Apr 23, 2023 |
| ASUSTek   | PRIME Z390-A                | [50a18b5e94](https://linux-hardware.org/?probe=50a18b5e94) | Apr 19, 2023 |
| Foxconn   | A76GMV                      | [bafa62c759](https://linux-hardware.org/?probe=bafa62c759) | Apr 18, 2023 |
| Foxconn   | A76GMV                      | [f129cb2de1](https://linux-hardware.org/?probe=f129cb2de1) | Apr 18, 2023 |
| ASUSTek   | PRIME Z390-A                | [e311d21def](https://linux-hardware.org/?probe=e311d21def) | Apr 13, 2023 |
| Lenovo    | 36F7 SDK0J40700 WIN 3258... | [8e05a5e529](https://linux-hardware.org/?probe=8e05a5e529) | Apr 13, 2023 |
| Gigabyte  | Z270-Gaming K3              | [0c03014734](https://linux-hardware.org/?probe=0c03014734) | Apr 12, 2023 |
| MSI       | B450M PRO-M2 MAX            | [5a83c18a3e](https://linux-hardware.org/?probe=5a83c18a3e) | Apr 01, 2023 |
| MSI       | B450M PRO-M2 MAX            | [94f75ee798](https://linux-hardware.org/?probe=94f75ee798) | Apr 01, 2023 |
| Unknown   | Unknown                     | [fb22157f03](https://linux-hardware.org/?probe=fb22157f03) | Mar 28, 2023 |
| AZW       | U59                         | [7674bb8dc9](https://linux-hardware.org/?probe=7674bb8dc9) | Mar 27, 2023 |
| ASUSTek   | M4A785TD-V EVO              | [1674c37cf9](https://linux-hardware.org/?probe=1674c37cf9) | Mar 16, 2023 |
| HP        | 805A                        | [5401e12606](https://linux-hardware.org/?probe=5401e12606) | Mar 14, 2023 |
| HP        | 3033h                       | [ab5e388ea9](https://linux-hardware.org/?probe=ab5e388ea9) | Mar 14, 2023 |
| HP        | 3033h                       | [38ac77726b](https://linux-hardware.org/?probe=38ac77726b) | Mar 13, 2023 |
| MSI       | B450 TOMAHAWK MAX           | [39d0e8595c](https://linux-hardware.org/?probe=39d0e8595c) | Mar 12, 2023 |
| MSI       | B365M PRO-VH                | [023f42d6d1](https://linux-hardware.org/?probe=023f42d6d1) | Mar 12, 2023 |
| Inventec  | Z CLASS A02                 | [c45e770987](https://linux-hardware.org/?probe=c45e770987) | Mar 06, 2023 |
| ASUSTek   | BT6130                      | [dabd3e0232](https://linux-hardware.org/?probe=dabd3e0232) | Mar 01, 2023 |
| Unknown   | Unknown                     | [1c5f8fef49](https://linux-hardware.org/?probe=1c5f8fef49) | Feb 28, 2023 |
| ASUSTek   | ROG STRIX Z690-A GAMING ... | [216ad20179](https://linux-hardware.org/?probe=216ad20179) | Feb 28, 2023 |
| Acer      | Predator G3620              | [72f3382b60](https://linux-hardware.org/?probe=72f3382b60) | Feb 27, 2023 |
| Gigabyte  | Z77X-UD5H                   | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte  | Z77X-UD5H                   | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell      | 07PR60 A01                  | [c071b7ef1c](https://linux-hardware.org/?probe=c071b7ef1c) | Feb 27, 2023 |
| ASUSTek   | TUF X470-PLUS GAMING        | [ce9dda227f](https://linux-hardware.org/?probe=ce9dda227f) | Feb 25, 2023 |
| Gigabyte  | B550 AORUS ELITE            | [13a132516b](https://linux-hardware.org/?probe=13a132516b) | Feb 18, 2023 |
| ASUSTek   | TUF X470-PLUS GAMING        | [76ab936a75](https://linux-hardware.org/?probe=76ab936a75) | Feb 16, 2023 |
| ASUSTek   | H110M-A/M.2                 | [68f0415788](https://linux-hardware.org/?probe=68f0415788) | Feb 16, 2023 |
| ASUSTek   | H110M-A/M.2                 | [2560ba7644](https://linux-hardware.org/?probe=2560ba7644) | Feb 16, 2023 |
| Foxconn   | 2ADA                        | [e0f89bbca1](https://linux-hardware.org/?probe=e0f89bbca1) | Feb 16, 2023 |
| HP        | 805D                        | [217784712c](https://linux-hardware.org/?probe=217784712c) | Feb 14, 2023 |
| MSI       | B85-G43 GAMING              | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| ASUSTek   | TUF X470-PLUS GAMING        | [f0899499e5](https://linux-hardware.org/?probe=f0899499e5) | Feb 13, 2023 |
| ASUSTek   | H110M-A/M.2                 | [76711a4e32](https://linux-hardware.org/?probe=76711a4e32) | Feb 10, 2023 |
| ASUSTek   | H110M-A/M.2                 | [73b3c1c661](https://linux-hardware.org/?probe=73b3c1c661) | Feb 06, 2023 |
| Gigabyte  | F2A88XM-DS2                 | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| ASUSTek   | P7P55 LX                    | [3786e7a211](https://linux-hardware.org/?probe=3786e7a211) | Feb 04, 2023 |
| ASUSTek   | Z170 PRO GAMING             | [c2a4529e33](https://linux-hardware.org/?probe=c2a4529e33) | Jan 30, 2023 |
| Unknown   | HX90                        | [af144f98b6](https://linux-hardware.org/?probe=af144f98b6) | Jan 05, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.15.0-58-generic   | 12       | 21.05%  |
| 5.19.0-32-generic   | 9        | 15.79%  |
| 5.19.0-35-generic   | 6        | 10.53%  |
| 5.19.0-38-generic   | 5        | 8.77%   |
| 5.19.0-46-generic   | 4        | 7.02%   |
| 5.19.0-41-generic   | 4        | 7.02%   |
| 5.15.0-60-generic   | 4        | 7.02%   |
| 6.2.0-26-generic    | 3        | 5.26%   |
| 5.19.0-43-generic   | 3        | 5.26%   |
| 5.19.0-42-generic   | 3        | 5.26%   |
| 5.19.0-40-generic   | 2        | 3.51%   |
| 6.4.5-x64v3-xanmod1 | 1        | 1.75%   |
| 5.15.0-56-generic   | 1        | 1.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.19.0  | 34       | 61.82%  |
| 5.15.0  | 17       | 30.91%  |
| 6.2.0   | 3        | 5.45%   |
| 6.4.5   | 1        | 1.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.19    | 34       | 61.82%  |
| 5.15    | 17       | 30.91%  |
| 6.2     | 3        | 5.45%   |
| 6.4     | 1        | 1.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 55       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 55       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 55       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 48       | 87.27%  |
| LightDM | 7        | 12.73%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 21       | 37.5%   |
| de_DE | 9        | 16.07%  |
| es_ES | 5        | 8.93%   |
| ru_RU | 4        | 7.14%   |
| pt_BR | 3        | 5.36%   |
| it_IT | 3        | 5.36%   |
| tr_TR | 1        | 1.79%   |
| sv_SE | 1        | 1.79%   |
| pt_PT | 1        | 1.79%   |
| pl_PL | 1        | 1.79%   |
| nl_NL | 1        | 1.79%   |
| ja_JP | 1        | 1.79%   |
| fr_FR | 1        | 1.79%   |
| fi_FI | 1        | 1.79%   |
| en_CA | 1        | 1.79%   |
| en_AU | 1        | 1.79%   |
| cs_CZ | 1        | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 52       | 94.55%  |
| EFI  | 3        | 5.45%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 51       | 92.73%  |
| Btrfs | 2        | 3.64%   |
| Xfs   | 1        | 1.82%   |
| Tmpfs | 1        | 1.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 48       | 87.27%  |
| GPT     | 5        | 9.09%   |
| MBR     | 2        | 3.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 98.18%  |
| Yes       | 1        | 1.82%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 96.36%  |
| Yes       | 2        | 3.64%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 12       | 21.82%  |
| Gigabyte Technology | 8        | 14.55%  |
| MSI                 | 6        | 10.91%  |
| Hewlett-Packard     | 5        | 9.09%   |
| Dell                | 3        | 5.45%   |
| ASRock              | 3        | 5.45%   |
| Acer                | 3        | 5.45%   |
| Pegatron            | 2        | 3.64%   |
| Foxconn             | 2        | 3.64%   |
| Unknown             | 2        | 3.64%   |
| Wortmann AG         | 1        | 1.82%   |
| MACHINIST           | 1        | 1.82%   |
| Lenovo              | 1        | 1.82%   |
| Inventec            | 1        | 1.82%   |
| Intel               | 1        | 1.82%   |
| ECS                 | 1        | 1.82%   |
| AZW                 | 1        | 1.82%   |
| Apple               | 1        | 1.82%   |
| Alienware           | 1        | 1.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS H110M-A/M.2                     | 2        | 3.64%   |
| Unknown                              | 2        | 3.64%   |
| Wortmann AG TERRA_PC                 | 1        | 1.82%   |
| Pegatron Pro 3010 Microtower PC      | 1        | 1.82%   |
| Pegatron IPMIP-GS                    | 1        | 1.82%   |
| MSI MS-7C52                          | 1        | 1.82%   |
| MSI MS-7C31                          | 1        | 1.82%   |
| MSI MS-7C02                          | 1        | 1.82%   |
| MSI MS-7B84                          | 1        | 1.82%   |
| MSI MS-7B17                          | 1        | 1.82%   |
| MSI MS-7816                          | 1        | 1.82%   |
| MACHINIST E5-MR9A PRO V1.1           | 1        | 1.82%   |
| Lenovo ThinkCentre M910s 10MLS05C00  | 1        | 1.82%   |
| Inventec Z CLASS                     | 1        | 1.82%   |
| Intel Jasper Lake Client Platform    | 1        | 1.82%   |
| HP ProDesk 600 G2 SFF                | 1        | 1.82%   |
| HP EliteDesk 800 G2 DM 35W           | 1        | 1.82%   |
| HP EliteDesk 705 G2 MT               | 1        | 1.82%   |
| HP Compaq dc7900 Ultra-Slim Desktop  | 1        | 1.82%   |
| HP 1998                              | 1        | 1.82%   |
| Gigabyte Z77X-UD5H                   | 1        | 1.82%   |
| Gigabyte Z270-Gaming K3              | 1        | 1.82%   |
| Gigabyte H81M-S2V                    | 1        | 1.82%   |
| Gigabyte H410M H V3                  | 1        | 1.82%   |
| Gigabyte GA-E6010N                   | 1        | 1.82%   |
| Gigabyte F2A88XM-DS2                 | 1        | 1.82%   |
| Gigabyte B560M H                     | 1        | 1.82%   |
| Gigabyte B550 AORUS ELITE            | 1        | 1.82%   |
| Foxconn A76GMV                       | 1        | 1.82%   |
| Foxconn 400-034                      | 1        | 1.82%   |
| ECS G41T-M                           | 1        | 1.82%   |
| Dell OptiPlex 790                    | 1        | 1.82%   |
| Dell OptiPlex 3070                   | 1        | 1.82%   |
| Dell Inspiron 5675                   | 1        | 1.82%   |
| AZW U59                              | 1        | 1.82%   |
| ASUS Z170 PRO GAMING                 | 1        | 1.82%   |
| ASUS TUF X470-PLUS GAMING            | 1        | 1.82%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4 | 1        | 1.82%   |
| ASUS ROG STRIX B350-F GAMING         | 1        | 1.82%   |
| ASUS PRIME Z390-A                    | 1        | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP EliteDesk         | 2        | 3.64%   |
| Dell OptiPlex        | 2        | 3.64%   |
| ASUS ROG             | 2        | 3.64%   |
| ASUS PRIME           | 2        | 3.64%   |
| ASUS H110M-A         | 2        | 3.64%   |
| Acer Aspire          | 2        | 3.64%   |
| Unknown              | 2        | 3.64%   |
| Wortmann AG TERRA    | 1        | 1.82%   |
| Pegatron Pro         | 1        | 1.82%   |
| Pegatron IPMIP-GS    | 1        | 1.82%   |
| MSI MS-7C52          | 1        | 1.82%   |
| MSI MS-7C31          | 1        | 1.82%   |
| MSI MS-7C02          | 1        | 1.82%   |
| MSI MS-7B84          | 1        | 1.82%   |
| MSI MS-7B17          | 1        | 1.82%   |
| MSI MS-7816          | 1        | 1.82%   |
| MACHINIST E5-MR9A    | 1        | 1.82%   |
| Lenovo ThinkCentre   | 1        | 1.82%   |
| Inventec Z           | 1        | 1.82%   |
| Intel Jasper         | 1        | 1.82%   |
| HP ProDesk           | 1        | 1.82%   |
| HP Compaq            | 1        | 1.82%   |
| HP 1998              | 1        | 1.82%   |
| Gigabyte Z77X-UD5H   | 1        | 1.82%   |
| Gigabyte Z270-Gaming | 1        | 1.82%   |
| Gigabyte H81M-S2V    | 1        | 1.82%   |
| Gigabyte H410M       | 1        | 1.82%   |
| Gigabyte GA-E6010N   | 1        | 1.82%   |
| Gigabyte F2A88XM-DS2 | 1        | 1.82%   |
| Gigabyte B560M       | 1        | 1.82%   |
| Gigabyte B550        | 1        | 1.82%   |
| Foxconn A76GMV       | 1        | 1.82%   |
| Foxconn 400-034      | 1        | 1.82%   |
| ECS G41T-M           | 1        | 1.82%   |
| Dell Inspiron        | 1        | 1.82%   |
| AZW U59              | 1        | 1.82%   |
| ASUS Z170            | 1        | 1.82%   |
| ASUS TUF             | 1        | 1.82%   |
| ASUS P8H61-MX        | 1        | 1.82%   |
| ASUS P7P55           | 1        | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 7        | 12.73%  |
| 2013 | 6        | 10.91%  |
| 2012 | 6        | 10.91%  |
| 2021 | 5        | 9.09%   |
| 2009 | 5        | 9.09%   |
| 2019 | 4        | 7.27%   |
| 2016 | 4        | 7.27%   |
| 2015 | 4        | 7.27%   |
| 2020 | 3        | 5.45%   |
| 2017 | 3        | 5.45%   |
| 2022 | 2        | 3.64%   |
| 2010 | 2        | 3.64%   |
| 2008 | 2        | 3.64%   |
| 2023 | 1        | 1.82%   |
| 2014 | 1        | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 55       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 55       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 55       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 16       | 28.57%  |
| 16.01-24.0  | 13       | 23.21%  |
| 32.01-64.0  | 10       | 17.86%  |
| 8.01-16.0   | 8        | 14.29%  |
| 3.01-4.0    | 6        | 10.71%  |
| 24.01-32.0  | 1        | 1.79%   |
| 64.01-256.0 | 1        | 1.79%   |
| 1.01-2.0    | 1        | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 26       | 45.61%  |
| 1.01-2.0  | 12       | 21.05%  |
| 3.01-4.0  | 10       | 17.54%  |
| 4.01-8.0  | 8        | 14.04%  |
| 8.01-16.0 | 1        | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 38.18%  |
| 2      | 20       | 36.36%  |
| 3      | 8        | 14.55%  |
| 5      | 3        | 5.45%   |
| 4      | 3        | 5.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 64.29%  |
| Yes       | 20       | 35.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 55       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 54.55%  |
| Yes       | 25       | 45.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 56.36%  |
| Yes       | 24       | 43.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 10       | 18.18%  |
| Germany     | 10       | 18.18%  |
| Russia      | 4        | 7.27%   |
| Italy       | 4        | 7.27%   |
| Brazil      | 4        | 7.27%   |
| Spain       | 3        | 5.45%   |
| Netherlands | 3        | 5.45%   |
| India       | 2        | 3.64%   |
| Venezuela   | 1        | 1.82%   |
| Ukraine     | 1        | 1.82%   |
| Turkey      | 1        | 1.82%   |
| Sweden      | 1        | 1.82%   |
| Portugal    | 1        | 1.82%   |
| Mexico      | 1        | 1.82%   |
| Japan       | 1        | 1.82%   |
| Greece      | 1        | 1.82%   |
| France      | 1        | 1.82%   |
| Finland     | 1        | 1.82%   |
| Czechia     | 1        | 1.82%   |
| Chile       | 1        | 1.82%   |
| Canada      | 1        | 1.82%   |
| Australia   | 1        | 1.82%   |
| Argentina   | 1        | 1.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 2        | 3.51%   |
| Amsterdam         | 2        | 3.51%   |
| Yorktown          | 1        | 1.75%   |
| West Jordan       | 1        | 1.75%   |
| Viareggio         | 1        | 1.75%   |
| Valencia          | 1        | 1.75%   |
| Tucson            | 1        | 1.75%   |
| Stuttgart         | 1        | 1.75%   |
| Stockholm         | 1        | 1.75%   |
| Steti             | 1        | 1.75%   |
| St Petersburg     | 1        | 1.75%   |
| Spokane           | 1        | 1.75%   |
| Sao Paulo         | 1        | 1.75%   |
| Santiago          | 1        | 1.75%   |
| Sandim            | 1        | 1.75%   |
| San Marcos        | 1        | 1.75%   |
| Plauen            | 1        | 1.75%   |
| Piea              | 1        | 1.75%   |
| Padova            | 1        | 1.75%   |
| Ojicho            | 1        | 1.75%   |
| Nossen            | 1        | 1.75%   |
| New York          | 1        | 1.75%   |
| Munich            | 1        | 1.75%   |
| Mumbai            | 1        | 1.75%   |
| Morehead City     | 1        | 1.75%   |
| Monsummano Terme  | 1        | 1.75%   |
| Milano            | 1        | 1.75%   |
| Melbourne         | 1        | 1.75%   |
| Mariupol          | 1        | 1.75%   |
| Madrid            | 1        | 1.75%   |
| Los Montesinos    | 1        | 1.75%   |
| Lorena            | 1        | 1.75%   |
| Las Vegas         | 1        | 1.75%   |
| Lanus             | 1        | 1.75%   |
| Lagerdorf         | 1        | 1.75%   |
| Laberweinting     | 1        | 1.75%   |
| Juazeiro do Norte | 1        | 1.75%   |
| Irvine            | 1        | 1.75%   |
| Independence      | 1        | 1.75%   |
| Hürth            | 1        | 1.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 21       | 24     | 20.79%  |
| Seagate                     | 12       | 17     | 11.88%  |
| Samsung Electronics         | 9        | 13     | 8.91%   |
| Toshiba                     | 7        | 9      | 6.93%   |
| Kingston                    | 6        | 6      | 5.94%   |
| SanDisk                     | 5        | 6      | 4.95%   |
| Crucial                     | 5        | 6      | 4.95%   |
| Hitachi                     | 4        | 5      | 3.96%   |
| Team                        | 2        | 3      | 1.98%   |
| PNY                         | 2        | 2      | 1.98%   |
| Netac                       | 2        | 3      | 1.98%   |
| Micron/Crucial Technology   | 2        | 2      | 1.98%   |
| China                       | 2        | 2      | 1.98%   |
| A-DATA Technology           | 2        | 2      | 1.98%   |
| Unknown                     | 2        | 2      | 1.98%   |
| Yeestor                     | 1        | 1      | 0.99%   |
| XrayDisk                    | 1        | 1      | 0.99%   |
| Unknown                     | 1        | 1      | 0.99%   |
| Silicon Motion              | 1        | 1      | 0.99%   |
| SD                          | 1        | 1      | 0.99%   |
| Realtek Semiconductor       | 1        | 1      | 0.99%   |
| OCZ-VERTEX2                 | 1        | 1      | 0.99%   |
| NGFF                        | 1        | 1      | 0.99%   |
| Micron Technology           | 1        | 1      | 0.99%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.99%   |
| LuminouTek                  | 1        | 1      | 0.99%   |
| LITEONIT                    | 1        | 1      | 0.99%   |
| KingDian                    | 1        | 2      | 0.99%   |
| Intenso                     | 1        | 2      | 0.99%   |
| HS-SSD-E100                 | 1        | 2      | 0.99%   |
| Hewlett-Packard             | 1        | 1      | 0.99%   |
| Corsair                     | 1        | 1      | 0.99%   |
| Apacer                      | 1        | 1      | 0.99%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 4        | 3.64%   |
| WDC WD10EZEX-60WN4A0 1TB                              | 3        | 2.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 3        | 2.73%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 2        | 1.82%   |
| Toshiba MQ01ABD100 1TB                                | 2        | 1.82%   |
| Toshiba DT01ACA200 2TB                                | 2        | 1.82%   |
| Samsung SSD 850 EVO 250GB                             | 2        | 1.82%   |
| Crucial CT500MX500SSD1 500GB                          | 2        | 1.82%   |
| Crucial CT240BX500SSD1 240GB                          | 2        | 1.82%   |
| Unknown                                               | 2        | 1.82%   |
| Yeestor 512GB                                         | 1        | 0.91%   |
| XrayDisk 512GB SSD                                    | 1        | 0.91%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 1        | 0.91%   |
| WDC WDS480G2G0C-00AJM0 480GB                          | 1        | 0.91%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 1        | 0.91%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 1        | 0.91%   |
| WDC WD5000AAKS-00V6A0 500GB                           | 1        | 0.91%   |
| WDC WD5000AAKS-00UU3A0 500GB                          | 1        | 0.91%   |
| WDC WD40EZRZ-00GXCB0 4TB                              | 1        | 0.91%   |
| WDC WD2500JB-55GVA0 250GB                             | 1        | 0.91%   |
| WDC WD20EZRX-22D8PB0 2TB                              | 1        | 0.91%   |
| WDC WD20EZRX-00D8PB0 2TB                              | 1        | 0.91%   |
| WDC WD10PURZ-85U8XY0 1TB                              | 1        | 0.91%   |
| WDC WD10EZEX-60ZF5A0 1TB                              | 1        | 0.91%   |
| WDC WD10EZEX-21WN4A0 1TB                              | 1        | 0.91%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 1        | 0.91%   |
| WDC WD10EZEX-00BBHA0 1TB                              | 1        | 0.91%   |
| WDC WD1002FBYS-18W8B0 1TB                             | 1        | 0.91%   |
| Unknown SD/MMC/MS PRO 128GB                           | 1        | 0.91%   |
| Toshiba XG4 NVMe SSD Controller 256GB                 | 1        | 0.91%   |
| Toshiba HDWD110 1TB                                   | 1        | 0.91%   |
| Toshiba DT01ACA100 1TB                                | 1        | 0.91%   |
| Toshiba DT01ACA050 500GB                              | 1        | 0.91%   |
| Team T253X2001T 1TB SSD                               | 1        | 0.91%   |
| Team T253X1480G 480GB SSD                             | 1        | 0.91%   |
| Team L3 SSD 240GB                                     | 1        | 0.91%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 1        | 0.91%   |
| Seagate ST9500325AS 500GB                             | 1        | 0.91%   |
| Seagate ST750LM022 HN-M750MBB 752GB                   | 1        | 0.91%   |
| Seagate ST500LM021-1KJ152 500GB                       | 1        | 0.91%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 20     | 41.46%  |
| Seagate             | 11       | 14     | 26.83%  |
| Toshiba             | 7        | 8      | 17.07%  |
| Hitachi             | 4        | 5      | 9.76%   |
| Unknown             | 1        | 1      | 2.44%   |
| Samsung Electronics | 1        | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 6        | 6      | 13.33%  |
| Samsung Electronics | 5        | 7      | 11.11%  |
| Crucial             | 5        | 6      | 11.11%  |
| WDC                 | 3        | 3      | 6.67%   |
| Team                | 2        | 3      | 4.44%   |
| Seagate             | 2        | 2      | 4.44%   |
| SanDisk             | 2        | 3      | 4.44%   |
| PNY                 | 2        | 2      | 4.44%   |
| China               | 2        | 2      | 4.44%   |
| A-DATA Technology   | 2        | 2      | 4.44%   |
| XrayDisk            | 1        | 1      | 2.22%   |
| SD                  | 1        | 1      | 2.22%   |
| OCZ-VERTEX2         | 1        | 1      | 2.22%   |
| NGFF                | 1        | 1      | 2.22%   |
| Netac               | 1        | 1      | 2.22%   |
| Micron Technology   | 1        | 1      | 2.22%   |
| LITEONIT            | 1        | 1      | 2.22%   |
| KingDian            | 1        | 2      | 2.22%   |
| Intenso             | 1        | 2      | 2.22%   |
| HS-SSD-E100         | 1        | 1      | 2.22%   |
| Hewlett-Packard     | 1        | 1      | 2.22%   |
| Corsair             | 1        | 1      | 2.22%   |
| Apacer              | 1        | 1      | 2.22%   |
| Unknown             | 1        | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 41       | 52     | 44.57%  |
| HDD     | 32       | 49     | 34.78%  |
| NVMe    | 13       | 15     | 14.13%  |
| Unknown | 6        | 7      | 6.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 54       | 104    | 76.06%  |
| NVMe | 13       | 15     | 18.31%  |
| SAS  | 4        | 4      | 5.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 41       | 59     | 56.94%  |
| 0.51-1.0   | 24       | 34     | 33.33%  |
| 1.01-2.0   | 5        | 6      | 6.94%   |
| 3.01-4.0   | 2        | 2      | 2.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 24       | 43.64%  |
| 501-1000   | 13       | 23.64%  |
| 251-500    | 12       | 21.82%  |
| 1001-2000  | 2        | 3.64%   |
| 51-100     | 2        | 3.64%   |
| 21-50      | 1        | 1.82%   |
| 2001-3000  | 1        | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 22       | 40%     |
| 21-50     | 13       | 23.64%  |
| 51-100    | 9        | 16.36%  |
| 101-250   | 8        | 14.55%  |
| 251-500   | 2        | 3.64%   |
| 1001-2000 | 1        | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| Hitachi HTS725050A7E630 500GB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 1        | 1      | 100%    |

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
| Detected | 51       | 114    | 87.93%  |
| Works    | 6        | 8      | 10.34%  |
| Malfunc  | 1        | 1      | 1.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 37       | 50.68%  |
| AMD                          | 18       | 24.66%  |
| Samsung Electronics          | 4        | 5.48%   |
| SanDisk                      | 3        | 4.11%   |
| ASMedia Technology           | 3        | 4.11%   |
| Micron/Crucial Technology    | 2        | 2.74%   |
| Marvell Technology Group     | 2        | 2.74%   |
| Toshiba America Info Systems | 1        | 1.37%   |
| Silicon Motion               | 1        | 1.37%   |
| Realtek Semiconductor        | 1        | 1.37%   |
| MAXIO Technology (Hangzhou)  | 1        | 1.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 15.56%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 6.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 4.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 4.44%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 4.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 3.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 3.33%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 3.33%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 2.22%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 2.22%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 2.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.22%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 2.22%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 2.22%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 2.22%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 1.11%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 1.11%   |
| SanDisk WD Green SN350 NVMe SSD 240GB (DRAM-less)                                       | 1        | 1.11%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.11%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                                   | 1        | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.11%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 1        | 1.11%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 1.11%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                               | 1        | 1.11%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1        | 1.11%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 1.11%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 1.11%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.11%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.11%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 52       | 73.24%  |
| NVMe | 12       | 16.9%   |
| IDE  | 6        | 8.45%   |
| RAID | 1        | 1.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 37       | 67.27%  |
| AMD    | 18       | 32.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 3.64%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 3.64%   |
| Intel Celeron N5105 @ 2.00GHz               | 2        | 3.64%   |
| Intel Xeon CPU W3520 @ 2.67GHz              | 1        | 1.82%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 1.82%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1        | 1.82%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.82%   |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1        | 1.82%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.82%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.82%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 1        | 1.82%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.82%   |
| Intel Core i5-9400T CPU @ 1.80GHz           | 1        | 1.82%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1        | 1.82%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 1.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.82%   |
| Intel Core i5-2500S CPU @ 2.70GHz           | 1        | 1.82%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1        | 1.82%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1        | 1.82%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.82%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 1.82%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 1.82%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.82%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 1.82%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.82%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1.82%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.82%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1        | 1.82%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 1        | 1.82%   |
| Intel 12th Gen Core i7-12700K               | 1        | 1.82%   |
| Intel 12th Gen Core i7-12700F               | 1        | 1.82%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 1        | 1.82%   |
| AMD Sempron 145 Processor                   | 1        | 1.82%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 1.82%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 1        | 1.82%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 1.82%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 1        | 1.82%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 1        | 1.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 9        | 16.36%  |
| Intel Core i7           | 8        | 14.55%  |
| Intel Core i3           | 5        | 9.09%   |
| Other                   | 4        | 7.27%   |
| Intel Celeron           | 4        | 7.27%   |
| AMD Ryzen 5             | 4        | 7.27%   |
| Intel Xeon              | 2        | 3.64%   |
| Intel Core i9           | 2        | 3.64%   |
| Intel Core 2 Duo        | 2        | 3.64%   |
| AMD Ryzen 9             | 2        | 3.64%   |
| AMD Ryzen 7             | 2        | 3.64%   |
| AMD A8                  | 2        | 3.64%   |
| Intel Pentium Dual-Core | 1        | 1.82%   |
| Intel Pentium           | 1        | 1.82%   |
| AMD Sempron             | 1        | 1.82%   |
| AMD Ryzen 5 PRO         | 1        | 1.82%   |
| AMD Ryzen 3             | 1        | 1.82%   |
| AMD Phenom II X6        | 1        | 1.82%   |
| AMD G                   | 1        | 1.82%   |
| AMD E1                  | 1        | 1.82%   |
| AMD Athlon              | 1        | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 21       | 37.5%   |
| 2      | 14       | 25%     |
| 6      | 8        | 14.29%  |
| 8      | 5        | 8.93%   |
| 12     | 4        | 7.14%   |
| 1      | 3        | 5.36%   |
| 5      | 1        | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 55       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 34       | 61.82%  |
| 1      | 21       | 38.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 55       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 87.27%  |
| 0x306a9    | 2        | 3.64%   |
| 0x906e9    | 1        | 1.82%   |
| 0x906c0    | 1        | 1.82%   |
| 0x08108109 | 1        | 1.82%   |
| 0x07030106 | 1        | 1.82%   |
| 0x010000c8 | 1        | 1.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 8        | 14.55%  |
| IvyBridge     | 6        | 10.91%  |
| Skylake       | 5        | 9.09%   |
| Haswell       | 4        | 7.27%   |
| Unknown       | 4        | 7.27%   |
| Zen 3         | 3        | 5.45%   |
| Zen 2         | 3        | 5.45%   |
| Zen           | 3        | 5.45%   |
| Penryn        | 3        | 5.45%   |
| Zen+          | 2        | 3.64%   |
| Steamroller   | 2        | 3.64%   |
| Nehalem       | 2        | 3.64%   |
| K10           | 2        | 3.64%   |
| Westmere      | 1        | 1.82%   |
| Tremont       | 1        | 1.82%   |
| SandyBridge   | 1        | 1.82%   |
| Puma          | 1        | 1.82%   |
| Goldmont plus | 1        | 1.82%   |
| Excavator     | 1        | 1.82%   |
| CometLake     | 1        | 1.82%   |
| Bobcat        | 1        | 1.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 22       | 37.93%  |
| Intel  | 21       | 36.21%  |
| Nvidia | 15       | 25.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 630                                                       | 3        | 5%      |
| Intel HD Graphics 530                                                       | 3        | 5%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 5%      |
| Nvidia GK107 [GeForce GT 640]                                               | 2        | 3.33%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 3.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 3.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 3.33%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 3.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 3.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 3.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.67%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.67%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.67%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.67%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.67%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.67%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.67%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.67%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.67%   |
| Nvidia GA103 [GeForce RTX 3060 Ti]                                          | 1        | 1.67%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.67%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 1.67%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.67%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.67%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1        | 1.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.67%   |
| AMD Wrestler [Radeon HD 6320]                                               | 1        | 1.67%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.67%   |
| AMD RV535 [Radeon X1650 PRO] (Secondary)                                    | 1        | 1.67%   |
| AMD RV535 [Radeon X1650 PRO]                                                | 1        | 1.67%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 1.67%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 20       | 36.36%  |
| 1 x Intel       | 18       | 32.73%  |
| 1 x Nvidia      | 14       | 25.45%  |
| 2 x AMD         | 1        | 1.82%   |
| Intel + 2 x AMD | 1        | 1.82%   |
| Intel + Nvidia  | 1        | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 50       | 90.91%  |
| Proprietary | 5        | 9.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 49       | 89.09%  |
| 7.01-8.0   | 2        | 3.64%   |
| 0.51-1.0   | 2        | 3.64%   |
| 1.01-2.0   | 1        | 1.82%   |
| 0.01-0.5   | 1        | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 14.55%  |
| Goldstar             | 8        | 14.55%  |
| Dell                 | 4        | 7.27%   |
| Acer                 | 4        | 7.27%   |
| Hewlett-Packard      | 3        | 5.45%   |
| Sceptre Tech         | 2        | 3.64%   |
| Philips              | 2        | 3.64%   |
| BenQ                 | 2        | 3.64%   |
| ASUSTek Computer     | 2        | 3.64%   |
| AOC                  | 2        | 3.64%   |
| ___                  | 1        | 1.82%   |
| Vizio                | 1        | 1.82%   |
| ViewSonic            | 1        | 1.82%   |
| Unknown              | 1        | 1.82%   |
| Sony                 | 1        | 1.82%   |
| Positivo             | 1        | 1.82%   |
| NSL                  | 1        | 1.82%   |
| NEC Computers        | 1        | 1.82%   |
| MYS                  | 1        | 1.82%   |
| MSI                  | 1        | 1.82%   |
| Lenovo               | 1        | 1.82%   |
| Kogan                | 1        | 1.82%   |
| Hitachi              | 1        | 1.82%   |
| HannStar             | 1        | 1.82%   |
| Fujitsu Siemens      | 1        | 1.82%   |
| Eizo                 | 1        | 1.82%   |
| CVT                  | 1        | 1.82%   |
| Ancor Communications | 1        | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ___ LCDTV16 ___3393 1366x768                                         | 1        | 1.69%   |
| Vizio E221VA VIZ0070 1920x1080 476x268mm 21.5-inch                   | 1        | 1.69%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch        | 1        | 1.69%   |
| Unknown LCDTV16 3393 1920x1080 1600x900mm 72.3-inch                  | 1        | 1.69%   |
| Sony TV SNY7A02 1360x768 708x398mm 32.0-inch                         | 1        | 1.69%   |
| Sceptre Tech Sceptre Q27 SPT0AD2 2560x1440 597x336mm 27.0-inch       | 1        | 1.69%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch        | 1        | 1.69%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch | 1        | 1.69%   |
| Samsung Electronics SMB2030HD SAM0709 1600x900 443x249mm 20.0-inch   | 1        | 1.69%   |
| Samsung Electronics S27A950D SAM079F 1920x1080 598x336mm 27.0-inch   | 1        | 1.69%   |
| Samsung Electronics S24E450 SAM0C7F 1920x1080 521x293mm 23.5-inch    | 1        | 1.69%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 1        | 1.69%   |
| Samsung Electronics LS27AG55x SAM71E0 2560x1440 597x336mm 27.0-inch  | 1        | 1.69%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch   | 1        | 1.69%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch    | 1        | 1.69%   |
| Positivo MC35120QWQHD NON3503 3440x1440 819x346mm 35.0-inch          | 1        | 1.69%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1        | 1.69%   |
| Philips 220TS PHLC06B 1920x1080 477x268mm 21.5-inch                  | 1        | 1.69%   |
| NSL RGB-27QHD NSL2711 2560x1440 597x336mm 27.0-inch                  | 1        | 1.69%   |
| NEC Computers EA234WMi NEC691E 1920x1080 509x286mm 23.0-inch         | 1        | 1.69%   |
| MYS LCD Monitor MYS1700 1280x1024 360x240mm 17.0-inch                | 1        | 1.69%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                       | 1        | 1.69%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                | 1        | 1.69%   |
| Kogan KAMN27QF7TA KGN0270 2560x1440 698x393mm 31.5-inch              | 1        | 1.69%   |
| Hitachi HISENSE HEC0030 3840x2160 1095x616mm 49.5-inch               | 1        | 1.69%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch          | 1        | 1.69%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch         | 1        | 1.69%   |
| Hewlett-Packard E231 HWP3063 1920x1080 510x287mm 23.0-inch           | 1        | 1.69%   |
| HannStar HSG1074 HSP0019 1920x1080 543x305mm 24.5-inch               | 1        | 1.69%   |
| Goldstar W1953 GSM4BA7 1360x768 406x229mm 18.4-inch                  | 1        | 1.69%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 1        | 1.69%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                  | 1        | 1.69%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch             | 1        | 1.69%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch             | 1        | 1.69%   |
| Goldstar HDR WFHD GSM5BA0 2560x1080 798x334mm 34.1-inch              | 1        | 1.69%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch               | 1        | 1.69%   |
| Goldstar E2260 GSM57E0 1920x1080 477x268mm 21.5-inch                 | 1        | 1.69%   |
| Goldstar 27MP35 GSM5A86 1920x1080 598x337mm 27.0-inch                | 1        | 1.69%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                | 1        | 1.69%   |
| Fujitsu Siemens B27T-7 LED FUS083D 1920x1080 598x336mm 27.0-inch     | 1        | 1.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 30       | 53.57%  |
| 2560x1440 (QHD)    | 6        | 10.71%  |
| 1920x1200 (WUXGA)  | 3        | 5.36%   |
| 1366x768 (WXGA)    | 3        | 5.36%   |
| 3440x1440          | 2        | 3.57%   |
| 2560x1080          | 2        | 3.57%   |
| 1360x768           | 2        | 3.57%   |
| 1280x1024 (SXGA)   | 2        | 3.57%   |
| 3840x2160 (4K)     | 1        | 1.79%   |
| 3840x1080          | 1        | 1.79%   |
| 2560x1600          | 1        | 1.79%   |
| 1680x1050 (WSXGA+) | 1        | 1.79%   |
| 1600x900 (HD+)     | 1        | 1.79%   |
| 1440x900 (WXGA+)   | 1        | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 11       | 18.97%  |
| 27      | 8        | 13.79%  |
| 21      | 8        | 13.79%  |
| 23      | 5        | 8.62%   |
| 18      | 4        | 6.9%    |
| 34      | 3        | 5.17%   |
| 31      | 3        | 5.17%   |
| 19      | 2        | 3.45%   |
| Unknown | 2        | 3.45%   |
| 84      | 1        | 1.72%   |
| 72      | 1        | 1.72%   |
| 49      | 1        | 1.72%   |
| 42      | 1        | 1.72%   |
| 35      | 1        | 1.72%   |
| 32      | 1        | 1.72%   |
| 29      | 1        | 1.72%   |
| 26      | 1        | 1.72%   |
| 22      | 1        | 1.72%   |
| 20      | 1        | 1.72%   |
| 17      | 1        | 1.72%   |
| 14      | 1        | 1.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 23       | 41.07%  |
| 401-500     | 15       | 26.79%  |
| 701-800     | 4        | 7.14%   |
| 601-700     | 4        | 7.14%   |
| 351-400     | 2        | 3.57%   |
| 1501-2000   | 2        | 3.57%   |
| Unknown     | 2        | 3.57%   |
| 801-900     | 1        | 1.79%   |
| 201-300     | 1        | 1.79%   |
| 1001-1500   | 1        | 1.79%   |
| 901-1000    | 1        | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 40       | 72.73%  |
| 16/10   | 6        | 10.91%  |
| 21/9    | 4        | 7.27%   |
| 6/5     | 1        | 1.82%   |
| 4/3     | 1        | 1.82%   |
| 32/9    | 1        | 1.82%   |
| 3/2     | 1        | 1.82%   |
| Unknown | 1        | 1.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18       | 31.58%  |
| 351-500        | 9        | 15.79%  |
| 301-350        | 8        | 14.04%  |
| 151-200        | 6        | 10.53%  |
| 251-300        | 4        | 7.02%   |
| 141-150        | 4        | 7.02%   |
| More than 1000 | 2        | 3.51%   |
| 501-1000       | 2        | 3.51%   |
| Unknown        | 2        | 3.51%   |
| 131-140        | 1        | 1.75%   |
| 101-110        | 1        | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 34       | 65.38%  |
| 101-120 | 13       | 25%     |
| 1-50    | 2        | 3.85%   |
| Unknown | 2        | 3.85%   |
| 121-160 | 1        | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 46       | 83.64%  |
| 2     | 9        | 16.36%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 29       | 36.25%  |
| Intel                    | 25       | 31.25%  |
| Qualcomm Atheros         | 8        | 10%     |
| TP-Link                  | 4        | 5%      |
| Broadcom                 | 3        | 3.75%   |
| Xiaomi                   | 2        | 2.5%    |
| Marvell Technology Group | 2        | 2.5%    |
| Samsung Electronics      | 1        | 1.25%   |
| Ralink                   | 1        | 1.25%   |
| Qualcomm                 | 1        | 1.25%   |
| MediaTek                 | 1        | 1.25%   |
| Linksys                  | 1        | 1.25%   |
| Huawei Technologies      | 1        | 1.25%   |
| ASUSTek Computer         | 1        | 1.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 29.67%  |
| Intel Wireless 3165                                               | 4        | 4.4%    |
| Intel Ethernet Controller I225-V                                  | 3        | 3.3%    |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 2.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 2.2%    |
| Intel I211 Gigabit Network Connection                             | 2        | 2.2%    |
| Intel Ethernet Connection (7) I219-V                              | 2        | 2.2%    |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.2%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 2.2%    |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.1%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 1.1%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 1.1%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 1.1%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 1.1%    |
| TP-Link Archer T4U ver.3                                          | 1        | 1.1%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 1.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.1%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 1.1%    |
| Qualcomm Redmi Note 8                                             | 1        | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 1.1%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.1%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.1%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.1%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 1.1%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 1.1%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.1%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 1.1%    |
| Marvell Group Libertas 802.11b/g Wireless LAN Client Adapter      | 1        | 1.1%    |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless               | 1        | 1.1%    |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]     | 1        | 1.1%    |
| Intel Wireless-AC 9260                                            | 1        | 1.1%    |
| Intel Wireless 8260                                               | 1        | 1.1%    |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.1%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.1%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 10       | 35.71%  |
| Realtek Semiconductor    | 4        | 14.29%  |
| Qualcomm Atheros         | 4        | 14.29%  |
| TP-Link                  | 3        | 10.71%  |
| Marvell Technology Group | 2        | 7.14%   |
| Ralink                   | 1        | 3.57%   |
| MediaTek                 | 1        | 3.57%   |
| Linksys                  | 1        | 3.57%   |
| Broadcom                 | 1        | 3.57%   |
| ASUSTek Computer         | 1        | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                           | 4        | 13.79%  |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2        | 6.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2        | 6.9%    |
| Intel Alder Lake-S PCH CNVi WiFi                              | 2        | 6.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1        | 3.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1        | 3.45%   |
| TP-Link Archer T4U ver.3                                      | 1        | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1        | 3.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1        | 3.45%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1        | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1        | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1        | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1        | 3.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 1        | 3.45%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1        | 3.45%   |
| Marvell Group Libertas 802.11b/g Wireless LAN Client Adapter  | 1        | 3.45%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless           | 1        | 3.45%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235] | 1        | 3.45%   |
| Intel Wireless-AC 9260                                        | 1        | 3.45%   |
| Intel Wireless 8260                                           | 1        | 3.45%   |
| Intel Wi-Fi 6 AX200                                           | 1        | 3.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 1        | 3.45%   |
| ASUS 802.11ac WLAN Adapter                                    | 1        | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 28       | 45.9%   |
| Intel                 | 21       | 34.43%  |
| Qualcomm Atheros      | 5        | 8.2%    |
| Xiaomi                | 2        | 3.28%   |
| Broadcom              | 2        | 3.28%   |
| TP-Link               | 1        | 1.64%   |
| Qualcomm              | 1        | 1.64%   |
| Huawei Technologies   | 1        | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 44.26%  |
| Intel Ethernet Controller I225-V                                  | 3        | 4.92%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 4.92%   |
| Intel I211 Gigabit Network Connection                             | 2        | 3.28%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 3.28%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 3.28%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 3.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.64%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 1.64%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 1.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.64%   |
| Qualcomm Redmi Note 8                                             | 1        | 1.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.64%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 1.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.64%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 1.64%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.64%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.64%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.64%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.64%   |
| Huawei WLZ-AN00                                                   | 1        | 1.64%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                    | 1        | 1.64%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 1.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 56       | 68.29%  |
| WiFi     | 25       | 30.49%  |
| Modem    | 1        | 1.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 40       | 75.47%  |
| WiFi     | 13       | 24.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 30       | 54.55%  |
| 2     | 20       | 36.36%  |
| 3     | 4        | 7.27%   |
| 0     | 1        | 1.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 34       | 61.82%  |
| Yes  | 21       | 38.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 41.67%  |
| Cambridge Silicon Radio         | 5        | 20.83%  |
| Realtek Semiconductor           | 2        | 8.33%   |
| Qualcomm Atheros Communications | 2        | 8.33%   |
| ASUSTek Computer                | 2        | 8.33%   |
| MediaTek                        | 1        | 4.17%   |
| Broadcom                        | 1        | 4.17%   |
| Apple                           | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 5        | 20.83%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 20.83%  |
| Realtek Bluetooth Radio                             | 2        | 8.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 8.33%   |
| Intel AX210 Bluetooth                               | 2        | 8.33%   |
| MediaTek Wireless_Device                            | 1        | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 4.17%   |
| Intel AX201 Bluetooth                               | 1        | 4.17%   |
| Intel AX200 Bluetooth                               | 1        | 4.17%   |
| Broadcom Bluetooth 3.0 USB Dongle                   | 1        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 4.17%   |
| ASUS ASUS USB-BT500                                 | 1        | 4.17%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 37       | 41.57%  |
| AMD                      | 23       | 25.84%  |
| Nvidia                   | 14       | 15.73%  |
| C-Media Electronics      | 6        | 6.74%   |
| Logitech                 | 3        | 3.37%   |
| Razer USA                | 1        | 1.12%   |
| Nordic Semiconductor ASA | 1        | 1.12%   |
| KTMicro                  | 1        | 1.12%   |
| Goldvish                 | 1        | 1.12%   |
| Creative Labs            | 1        | 1.12%   |
| ASUSTek Computer         | 1        | 1.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 5.71%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5        | 4.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 3.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 3.81%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 3.81%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4        | 3.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 2.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 2.86%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 2.86%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 2.86%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 2.86%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 2.86%   |
| AMD FCH Azalia Controller                                                  | 3        | 2.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 2.86%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.9%    |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 1.9%    |
| Intel Jasper Lake HD Audio                                                 | 2        | 1.9%    |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.9%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.9%    |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 1.9%    |
| Razer USA Razer Barracuda X                                                | 1        | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.95%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.95%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.95%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.95%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.95%   |
| Nvidia Audio device                                                        | 1        | 0.95%   |
| Nordic Semiconductor ASA BLE Remote                                        | 1        | 0.95%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1        | 0.95%   |
| Logitech Logi Z407                                                         | 1        | 0.95%   |
| Logitech G432 Gaming Headset                                               | 1        | 0.95%   |
| KTMicro KT USB Audio                                                       | 1        | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 0.95%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 3        | 27.27%  |
| Samsung Electronics | 2        | 18.18%  |
| Unknown (0x5846)    | 1        | 9.09%   |
| CSX                 | 1        | 9.09%   |
| Corsair             | 1        | 9.09%   |
| Apacer              | 1        | 9.09%   |
| A-DATA Technology   | 1        | 9.09%   |
| Unknown             | 1        | 9.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s | 1        | 9.09%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s           | 1        | 9.09%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s           | 1        | 9.09%   |
| Kingston RAM HX426C16FB/4 4GB DIMM DDR4 2800MT/s              | 1        | 9.09%   |
| Kingston RAM HX318C10F/8 8GB DIMM DDR3 1600MT/s               | 1        | 9.09%   |
| Kingston RAM ASU16D3LU1KBG/4G 4GB DIMM DDR3 3200MT/s          | 1        | 9.09%   |
| CSX RAM V01D3L82GB26826813 2GB DIMM 1066MT/s                  | 1        | 9.09%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s          | 1        | 9.09%   |
| Apacer RAM 78.CAGP7.C7Z0B 8GB DIMM DDR4 2400MT/s              | 1        | 9.09%   |
| A-DATA RAM Module 4GB DIMM DDR3 1600MT/s                      | 1        | 9.09%   |
| Unknown                                                       | 1        | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 4        | 44.44%  |
| DDR4    | 3        | 33.33%  |
| SDRAM   | 1        | 11.11%  |
| Unknown | 1        | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 7        | 87.5%   |
| SODIMM | 1        | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 4        | 44.44%  |
| 4096 | 4        | 44.44%  |
| 2048 | 1        | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 27.27%  |
| 2800  | 2        | 18.18%  |
| 3200  | 1        | 9.09%   |
| 2667  | 1        | 9.09%   |
| 2400  | 1        | 9.09%   |
| 2000  | 1        | 9.09%   |
| 1066  | 1        | 9.09%   |
| 533   | 1        | 9.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 50%     |
| Canon               | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Samsung M2020 Series | 1        | 50%     |
| Canon MF4320-4350    | 1        | 50%     |

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
| Sunplus Innovation Technology | 1        | 33.33%  |
| Generalplus Technology        | 1        | 33.33%  |
| Apple                         | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Sunplus 1080P Webcam            | 1        | 33.33%  |
| Generalplus WEB CAM             | 1        | 33.33%  |
| Apple iPhone 5/5C/5S/6/SE/7/8/X | 1        | 33.33%  |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 45       | 81.82%  |
| 1     | 9        | 16.36%  |
| 2     | 1        | 1.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 5        | 45.45%  |
| Network               | 1        | 9.09%   |
| Net/ethernet          | 1        | 9.09%   |
| Multimedia controller | 1        | 9.09%   |
| Graphics card         | 1        | 9.09%   |
| Chipcard              | 1        | 9.09%   |
| Card reader           | 1        | 9.09%   |

